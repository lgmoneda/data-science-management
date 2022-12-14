---
layout: page
title: Relevant ML concepts
parent: Project
mathjax: true
nav_order: 3
---


# Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

# Relevant Machine Learning systems concepts
## Batch & Real-time

Batch and Real-time are systems' characteristics. For Machine Learning Systems, a batch model scores a large volume of data at once, typically daily, weekly, or monthly. Still, it can also be associated with an essential mark for the customer journey after 30 days of inactivity.

The Real-time model must react under milliseconds or seconds to a signal and generate an output. E.g., a customer finishes the registration flow, and we run the model using the data generated by registration to create an output that we will use for decision-making.

We will illustrate it using the scoring time concept and the recurrent example.

## Scoring time

The scoring time (or scoring event) is a modeling concept that influences the ML system design. It helps visualize the inputs as past behavior, the target as a future event, and how the output can be used for a decision.

We can think of the interplay between scoring time and a batch or real-time model as a decision regarding benefits and costs. We might find out the effect of the scoring time is relevant and opt to invest in a real-time model, while we can also come from the complexity of a real-time model and influence the scoring time to adapt for a batch model.

Using our example of the Coupon-referral program, we can imagine many different settings.

### Real-time options
#### Real-time decision after registration

We score a customer just after their registration, at their release. We will use the information the user provides and any other data source we have available at the acquisition stage.

For the target, we can consider their referral behavior in a time window between the release time and the first 1, 2, and 15 days.

<div align="center">
<figure>
	<a href="../../images/project/real-time-scoring-time.svg" name="Real Time Scoring event">
		<img  style="width:650px;margin:10px" src="../../images/project/real-time-scoring-time.svg"/>
	</a>
		<!-- <figcaption>Putting together the many common terms for these two stages</figcaption> -->
</figure>
</div>

#### Real-time decision during a time window

Instead of using the customer release as the event, we can score them using other behaviors we can observe after release: at every new login, after checking a restaurant and not finishing an order, etc. We can again set a time window, especially if there is an understanding of the part of the customer journey we focus on, so we score every login in the first 30 days after release, for example. Or we could keep it perpetual.

Now the target needs to be relative to that event. A flag for a referral or its quantity in a time window after the event.

### Batch options
#### Batch decision after registration

Every day at some specified time, we can run our model, score all the customers we released the day before, store a decision, and propagate it at a convenient time, like as soon as possible via e-mail, in the next login, etc.

Though some customers have more information and behavior, we are still looking at their data as they were recently released. So it uses the same information from the real-time model triggered by the release but cannot provide the output to decide at the release time.

#### Batch daily decision

Instead of cutting at the release time, we can decide to provide a time range that enables us to get their behavior since release. We need to define an event to make a similar cut for all the cases. It can again mimic the real-time model that continuously gets behavior data to make the decision. Again, we can't deliver the decision as-of the last information used to make it.

### Scoring and action time

The scoring time influences when we can deliver the decision based on the output. We can break the effect of the scoring time into two stages: how much it changes the available information and how much it gets affected by when we deliver the decision to a customer.

As we have seen in the previous section, the scoring time will change the available information, impacting the model performance. Here it is a modeling decision that will affect the product performance.

However, the decision to deliver the coupon just after registration, after one day from registration, at any day in the first 30 days after registration, or at any time while the customer is active is a product decision we can investigate separately from the model.

We could have experimented with all these settings without involving ML and defined their benefits to contrast with the costs of the ML systems that can support them.

### Scoring population

Another option is which cases we should score. In most cases, we are talking about new customers, and we set a unique scoring event and a single decision: score every new customer after release and make a single decision on providing them a coupon and a nudge to referral.

In other cases, we were continuously scoring them. In this case, we can filter them to avoid situations we are not interested. E.g., we want to nudge with a coupon only people who haven't referred yet (either with or without a coupon).

### Relevant factors for batch against real-time regarding modeling

The batch options have more data available but do not use it. They create a gap in available information and decision. And that's exactly the factor that will guide us in defining how relevant it is: how dependent on fresh data when predicting the behavior of interest? Is the data regarding the customer behavior from a week ago and their static characteristics the most determinant or do we depend a lot on what happened in the last hour?

## Offline & Online stages

There are different terms to describe these two stages of ML Systems. Offline, or learning, for building a model on top of a given dataset. And Online, Serving, or Scoring, when we talk about the model working in the intended environment and usage.

The usual approaches of offline model validation imply the traditional dataset split and metrics. However, Online validation is necessary because of the usual offline-online evaluation gap. It is the difference between the conditions in which we train a model and the ones we apply it.

There are engineering and modeling sources for the difference. As the ML model in the online stage is a piece of software, it is prone to all sorts of engineering bugs. Since many things influence data generation and phenomena, the available data or the current state of the problem can differ a lot online.

As we want to use the model for decision-making and do not feel happy with Offline evaluation metrics, the Online stage is the most important for us, that's what brings value to the business, and we should strive to have it as soon as possible.

## How to deal with so many design options and the wild online world?

Notice that the problem statement is different in every setting, and the needed data to train also changes. We often change settings that do not appear explicitly in the input data.

$$

\begin{align}
\begin{split}
{}& P(\text{Referral} \mid \text{do} = \text{coupon}, \text{do} = \text{nudge message}) \\
{}& P(\text{Referral} \mid \text{do} = \text{coupon}) \\
{}& P(\text{Referral} \mid \text{do} = \text{coupon one day after release}) \\
\end{split}
\end{align}

$$

Of course, the change is very small in a couple of them. And one can train with data generated in one setting and apply it in the other. But the team needs to have these assumptions clear.

The chances are the impact of many of the design options won't be relevant. Running experiments on the most important is a good option, but sticking to a simple design, solving it, and then challenging the current solutions with further experiments is usually easier to sell, as the team has profits to justify the costs of further experiments.

However, the gap between offline and online has the same effect. It will add underlying characteristics to the data and the solution the team might be aware of. For example, the promotions and campaigns from competitors, new features of the product, etc.

We will see how we can deal with them during the project development.
