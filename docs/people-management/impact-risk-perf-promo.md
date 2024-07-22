---
layout: page
title: Impact, Risk, and their relationship with performance grades and promotions
parent: People
nav_order: 9
mathjax: true
description: A model to understand your impact and risk-taking decisions in a company, and what you can expect from how they link to  performnace evaluation and promotions
image: https://lgmoneda.github.io/data-science-management/images/people/impact-possibilities-frontier.png
---

# Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

# What does impact mean?

We often use the term "impact" on the [ladder](/docs/people-management/career-ladder) to discuss performance. We can define impact as causing the business outcomes that get a company closer to its most audacious goal and accomplish its mission at best. For example, [OpenAI's](https://openai.com/charter/) "ensure that advanced AI systems benefit all of humanity." Or [Google's](https://www.google.com/search/howsearchworks/our-approach/) "organize the world's information and make it universally accessible and useful".

It is simple but so high-level that we must bridge it with our day-to-day.

## Objective Key Results as a compass
{: .no_toc }

Companies usually set Objective Key Results (OKRs) at a company level, cascading them to every team, which uses their context to define their OKRs to accomplish the former. If not OKRs, they do it with any other approach that represents the same thing: direction and destiny. 

OKRs translate a business strategy into the most important objective results to guide teams with metrics and achievements they consider impactful. If a team agrees on a well-defined OKR, any activities towards achieving it are impactful—the more they contribute, the higher the impact.

Depending on the company culture, everyone might have a chance to influence their team's OKR, which means contributing to defining what impact is in one's context. 

Nonetheless, there are nuances.

### Dysfunctional OKRs
{: .no_toc }

A team might define their OKRs badly due to:
- not understanding their role in the company;
- lacking a vision that guides their long-term strategy;
- not providing room for Data Science contribution;
- using metrics that we cannot estimate the impact of our actions;
- bad translation of strategy into OKRs.

Usually, managers and team leaders are accountable for OKRs' quality. Companies expect technical leaders (Lead/Staff+) to challenge and define them with the former group. A dysfunctional OKR is not a miss for non-leaders but will undermine their potential to drive impact.

<div align="center">
<figure>
	<a href="../../images/people/impact-as-delta-reality-vision.svg" name="Diffusion curve">
		<img  style="width:550px;margin:10px" src="../../images/people/impact-as-delta-reality-vision.svg"/>
	</a>
		<figcaption>Impact is in the eyes of the team, who they report to, and their customers because it depends on a team's definition of where they want to be and the acceptance of who they serve. Imagine the above image in a multi-dimensional space, where every dimension is something the team cares about and idealizes; then you have the delta distance as the notion that the team will use for impact in their context </figcaption>
</figure>
</div>

### Is the impact from different teams comparable?
{: .no_toc }

The existence of a team should imply that a company believes its work is essential. If its work is not comparable to that of other teams, one can challenge people allocation. Notice that comparable differs from commensurable (a comparison by an equal measure). Take into consideration the nature or stage of the teams. Team organization is part of setting people up for success, and managers are accountable for it.

However, even under equal importance, opportunities might be unevenly distributed because of circumstances we can't control, which can create better environments to drive impact in particular teams in a specific period. This opportunity distribution is too dynamic for individuals to use as a guide.

## What happens around OKRs is also impactful
{: .no_toc }

The longer the chain connecting an action to a business outcome, the trickier it is to evaluate how impactful its contribution is. However, it does not mean we should shy away from doing it, mainly because we understand that a company's success depends on behaviors, how delivery happens, and work that enables others.

Activities that enable the OKRs or prevent us from regressing are impactful—for example, keeping critical systems running, debugging crashes, or preventing them by addressing technical debt. Efficiency is another easy guide: reducing costs, shutting down non-useful projects and processes, etc. One can suggest whether we should include OKRs related to them for their team.

For non-objective contributions or behaviors, build the chain about the action and how it contributes to the team's OKRs to ensure the work is meaningful for the group. For example:

A push to be inclusive and generate a safe space -> engagement from all the team members to share ideas and challenge each other -> more good ideas popped up and more bad ideas were shut down -> the discovery process became more efficient -> the team prioritized more impactful projects to deploy -> higher impact in the OKRs;

We can change the action from the above example by many tasks that are hardly directly represented as an OKR, like onboarding, documentation, sharing knowledge, and other glue work (Reilly)[^fn1]. It is easier to use a downstream consequence of the first action or to expect the effect on the OKRs as evidence to support these contributions as impactful.

## Time frame, ambiguity, and audacity
{: .no_toc }

Teams usually set objectives every quarter, semester, or year in some form, such as OKRs. They guide the short-term impact. Developing a new platform for the whole company, launching a new product, a program to reduce attrition, etc, are projects that will likely not show their full impact in a single cycle. In this case, OKRs might reflect short-term wins or [leading indicators](https://www.investopedia.com/terms/l/leadingindicator.asp#:~:text=Leading%20indicators%20are%20measurable%20pieces,economic%20or%20business%20trend%20occurs.) that people believe will reach the long-term objective. These OKRs might not create an excellent opportunity for impact in the short term, but they can support skill development and a long-term effect that will pay off.

Educational and cultural problems are usually ambiguous, with a solution that is non-trivial or impossible to measure. When working on them, one can inspect for impact using proxies.
- Access: are people consuming the created resources? Do they recommend it to other people?
- Adoption: Are people using its language and rationale as a tool to have conversations about this topic in their day-to-day lives?
- Direct feedback: Have people directly cited it as useful?

When working on non-trivial internal or external products, the team will likely go through an adoption curve [^fn3] and different product life cycle stages. 

<div align="center">
<figure>
	<a href="https://upload.wikimedia.org/wikipedia/commons/thumb/1/11/Diffusion_of_ideas.svg/2880px-Diffusion_of_ideas.svg.png" name="Diffusion curve">
		<img  style="width:450px;margin:10px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/11/Diffusion_of_ideas.svg/2880px-Diffusion_of_ideas.svg.png"/>
	</a>
		<figcaption>Longer projects require us to slice them and understand what impact means at their different stages. <a href="https://en.wikipedia.org/wiki/Diffusion_of_innovations"> Source.</a> </figcaption>
</figure>
</div>

In the early stage, we can use metrics related to the delta benefits in a proof of concept: reduced processing time, model performance, cost reduction, etc. Or going from zero to one: having the first instance of an agreed beneficial output or outcome. During the expansion, the monetary benefits or the adoption likely become considerable to track. The level of service becomes essential, so keeping a couple of guardrails metrics translates into impact, too. For an internal product that leadership wants to have all teams using, it ends up in a migration; then, looking into the percentage of instances from all the possible instances can provide an idea of impact; for example, 84% of all use cases migrated to use project X. 

Why would people engage in long-term or ambiguous initiatives?

Significant opportunities will pressure a company as it grows, and it becomes more and more attractive in terms of return if appropriately tackled. The risk-return trade-off will eventually push people towards the audacity to work on it.

### You don't need to necessarily associate your work with a monetary value to be recognized
{: .no_toc }

Translating projects' impact into money is great because that's a common language, and a company must be profitable. 

However, it is not always possible or convenient to do it. Regardless, you will need or want to associate it with value related to your team or company's objectives.

Consider the experience of creating or maintaining an important internal product. 

Let's illustrate it with some numbers:
200 MAU (Monthly Active Users)
A merge time of 3 days
An NPS (Net Promoter Score) of -50
Imagine users commonly say it is painful to use.

Imagine a team transforming it so contributions reflect in production in 5 minutes, the NPS becomes 90, and the MAU grows to 400.

We don't need to estimate its value to show how transformational it was for the company. 

Obsessing transforming projects into monetary value is a trap that many folks get into, and it is dangerous because it can divert attention to opportunities that are easier to associate with money instead of the most impactful ones. For example, cost savings projects. Though they hit a company's bottom line directly, it is rare to have on them the most impactful thing a team should be doing - only teams whose costs are meaningful on a company scale will live in this situation often.

# Taking Risks 

A risk is an exposure to an undesirable result. Why would we be exposed to it? In exchange for a higher potential return. That's the risk-return trade-off. The higher the risk we assume, the higher the return we expect if the outcome is realized.

Let's use a simple model to describe the situation using mathematical expectations. We know it is not how we think it in the day-to-day. The most common way to deal with this information is to have a matrix where we attribute scores to projects (1=low, 5=high) to classify their complexity, uncertainty, magnitude of the benefit, etc. However, this exercise makes it easier to associate risk-taking better.

We can decompose an activity's expected impact into its expected value, discounted by the cost of opportunity.

$$
\text{E}[\text{Impact}] = \int\limits^{\infty}_{-\infty}\! v\cdot f(v)\, dv.\notag - C_{\text{opportunity}}
$$

The $$f(v)$$ is the probability density function, which guides the likelihood of the possible outcomes from the activity, while $$v$$ represents the activity value. It means the impact comes from the interaction of the chances of observing the different possible outcomes discounted by the best other activity we could be doing.

For example, considering activity A with only two possible outcomes, total failure with a chance of <span style=" color:magenta;"><b>50%</b></span> and outcome of <span style=" color:red;"><b>0</b></span>, and total success with a chance of <span style=" color:purple;"><b>50%</b></span> and outcome of <span style=" color:green;"><b>100</b></span>, given we could do an activity B that provides us with a benefit of <span style=" color:orange;"><b>20</b></span> with an <span style=" color:blue;"><b>80%</b></span> chance and <span style=" color:teal;"><b>0</b></span> with <span style=" color:brown;"><b>20%</b></span>, the expected impact would be:

<span style="color:magenta;"><b>0.5</b></span> * <span style="color:red;"><b>0</b></span> + <span style="color:purple;"><b>0.5</b></span> * <span style="color:green;"><b>100</b></span> - (<span style="color:blue;"><b>0.8</b></span> * <span style="color:orange;"><b>20</b></span> + <span style="color:brown;"><b>0.2</b></span> * <span style="color:teal;"><b>0</b></span>) = <span style="color:black;"><b>34</b></span>


Since we already discount Activity B as the cost of opportunity and Activity A has a positive expected impact, we should go for it!

The following image shows the difference between two activities with different associated risks in a more realistic continuous world.

<div align="center">
<figure>
	<a href="../../images/people/low-high-risk-activities.svg" name="likelihood-impact curves">
	<img  style="width:450px;margin:10px" src="../../images/people/low-high-risk-activities.svg"/>
	</a>
		<figcaption>A higher risk activity will offer the potential of a great impact (the longer tail in the right) at the cost of a higher likelihood of low impact (the concentration in the orange curve in the left part)</figcaption>
</figure>
</div>

We could simply maximize the expected impact when choosing our activities. However, we only have estimates; we don't have actual values for the components. Additionally, the interaction of the activity, environment, people involved, and approach will influence f(v): the shape of the distribution changes depending on us!

Imagine we are unprepared to tackle activity A, so its success chance drops from <span style=" color:purple;"><b>50%</b></span> to <span style=" color:purple;"><u><b>10%</b></u></span>, which makes total failure <span style=" color:red;"><u><b>90%</b></u></span>. In this case, the expected impact of doing A:

<span style="color:red;"><u><b>0.9</b></u></span> * <span style="color:teal;"><b>0</b></span> + <span style="color:purple;"><u><b>0.1</b></u></span> * <span style="color:green;"><b>100</b></span> - (<span style="color:blue;"><b>0.8</b></span> * <span style="color:orange;"><b>20</b></span> + <span style="color:brown;"><b>0.2</b></span> * <span style="color:teal;"><b>0</b></span>) = <span style="color:black;"><b>-6</b></span>

Now, tackling B looks more promising.

### Splitting the inherent and reducible uncertainties
{: .no_toc }

Every activity will have inherent uncertainty and ambiguity in its outcome. But we should distinguish it from getting along with a lousy formulation of the problem or ill-defined experiments and assumptions. De-risking an opportunity by studying the issue, analyzing available data, timing, etc., is part of the work when tackling any opportunity. However, it becomes more important when the risk is higher.

## Untested assumptions make opportunities riskier
{: .no_toc }

As we propose something new, we assume many things we don't know for sure. They are our assumptions or hypotheses. An opportunity with many untested assumptions is riskier than another with just a few or without any. A few examples of assumptions from different types (Torres)[^fn2]:

- Desirability assumption: Does anyone want it? Will the customers get value from it?

- Viability assumption: Is it viable for the business? Should we build it?

- Feasibility assumption: Can we build it? Is it technically possible? Do we have the correct data?

- Usability assumption: Is it usable? Will customers understand how to use it? Are they able to do what we need them to do?

- Ethical assumption: Is there any potential harm in building this idea?

## Opportunity Cost
{: .no_toc }

When we allocate our time to do something, we choose not to work on everything else. The actual cost of a project differs from the time we use to deliver:  we need to discount the benefits of working on its alternatives. Alternatives have their own risks and uncertainties regarding their benefits.

## Not all activities that fail to drive business outcomes fail equally
{: .no_toc }

Even if an initiative fails to drive business impact, how it happened and what the team produced during the process can bring value.

Valuable things even under no short-term business impact:

- The team tested many assumptions and documented them well so that other people could reuse them;

- The team approached the project addressing critical assumptions first and aborted the project in a short period;

- The problem and the customer need were well-sized, and it is valuable to know it;

- Solutions were well documented, and people can reuse or avoid following wrong paths in the future;

- The team designed their experiments well;

- The team collected and properly shared all the exciting facts to compose the company's body of knowledge. The team made the company know better about its business;

- Prioritizing working on it was well justified considering the cost of opportunity and the excellent time management during it;

All these assets mean that it is impactful to address an uncertain project with high quality. Poorly approaching it degrades the project's expected impact. Illustrating it:

<div align="center">
<figure>
	<a href="../../images/people/poorly-approached-risk.svg" name="Poorly approached risky activity">
		<img  style="width:450px;margin:10px" src="../../images/people/poorly-approached-risk.svg"/>
	</a>
		<figcaption> How a team faces a high-risk project changes the likelihood of its impact. When evaluating performance, people will consider it beyond the project's outcome, especially when it didn't impact. </figcaption>
</figure>
</div>

We can list a couple of behaviors that usually follow when people do it poorly.

<u>Bad risk taking</u>
- Assume your customer wants what the team will build and discover it only after building;
- Don't verify the technical feasibility of every project step at the beginning. Getting surprised by it in the middle or end of it;
- Assume their customer will be able to use what they build and only get a notion about it after the release;
- Running in circles, the team didn't extract much knowledge from the failure;
- Discover in the middle of the project that the problem they are working with will have a low impact;
- The team works on an approach for a couple of months, but in the last integration, it doesn't solve the problem.

## Tooling for risk-taking 
{: .no_toc }

In general, product management is a discipline that offers many tools to build under uncertainty. I recommend reading the [Product section](/product-management/), especially on the Opportunity Solution Tree. Also, considering uncertainty is a continuous effort in an initiative, I cover it for project management in the section about [Defining releases](/docs/project-management/releases).

## The counterfactual impact 
{: .no_toc }

To debias the perceived impact of an individual due to the inherited uncertainty, the natural impact of a project, or external effects on their OKRs, one can do a counterfactual exercise:

This project had a very significant business impact, but how would it have been different if other people had been allocated to it instead of the actual team?
 This project failed to deliver business value, but how would it have been different if we had allocated other people to it instead of the actual team?

These questions help us not overestimate or underestimate individuals' importance in the team. A typical case is when OKRs benefit from or degrade due to market conditions or any out-of-control condition, for example. It is also helpful for individuals to identify how their particular skills and interests can impact the company in unexpectedly positive ways.

# How does impact relate to performance grades and promotions?

Considering my experience, conversations with people who worked in big tech, and articles about big tech culture (mostly from the [Pragmatic Engineer](https://www.pragmaticengineer.com/)), I consider the following model good for "self-career management." Notice that it is a simplification that we hope to be helpful.

From now on, we are using the non-reductionist definition of impact, normalized by the counterfactual evaluation exercise. Keep in mind that performance grades classify cycles and not individuals.

Let's use a 1-to-5 cycle grade system from [Google](https://www.cnbc.com/2022/05/06/google-says-its-raising-employee-pay-in-performance-review-revamp.html): not enough impact, moderate impact, significant impact, outstanding impact, and transformative impact. 

Two things will define grade and promotion: the impact size and the nature of the work to achieve it. In the following image, we represent performance as a vector and use two parameters to characterize it. The axis represents the scope of the activities performed.

<div align="center">
<figure>
	<a href="../../images/people/level-next-impact.svg" name="Model for performance and promo">
		<img  style="width:450px;margin:10px" src="../../images/people/level-next-impact.svg"/>
	</a>
		<figcaption>There is impact and the way or role one plays to drive it. </figcaption>
</figure>
</div>

The magnitude λ defines the impact to which the company should reward using a performance grade, while the θ will contribute to a promotion.

However, people do not have all the possible combinations available. We can perform within a boundary defined by Skills and Opportunities.

<div align="center">
<figure>
	<a href="../../images/people/impact-possibilities-frontier.svg" name="Impact Possibilities frontier">
		<img  style="width:550px;margin:10px" src="../../images/people/impact-possibilities-frontier.svg"/>
	</a>
		<figcaption>Our skills and opportunities provide a frontier of possibilities to drive impact. </figcaption>
</figure>
</div>

The Impact Possibilities Frontier (IPF) provides potential impact, while performance makes that possibility real. It realizes that potential. One can perform far from one's boundary, which means one cannot fully realize one's skills and opportunities.

The definition of the grade is not a hardline but a region based on the expected performance for every level. The regions represent grades for a cycle on the current level. The scale changes for the next level. For example, a high magnitude impact (λ) that makes the cycle a "Transformative Impact" for the current level could be classified as a "Significant Impact" for the next level.


<div align="center">
<figure>
	<a href="../../images/people/perf-grades-and-impact.svg" name="Performance evaluation and impact">
		<img  style="width:550px;margin:10px" src="../../images/people/perf-grades-and-impact.svg"/>
	</a>
		<figcaption>A way to model how impact and performance evaluation relate</figcaption>
</figure>
</div>

The following image represents the evolution of what "Significant Impact" means for different levels. A promotion updates the expectations and exposes individuals to developing skills and operating in a scope that can drive higher impact.

<div align="center">
<figure>
	<a href="../../images/people/mid-grade-by-level.svg" name="Mid-grade by level">
		<img  style="width:550px;margin:10px" src="../../images/people/mid-grade-by-level.svg"/>
	</a>
		<figcaption>A way to represent the base impact expectation for growing seniority levels</figcaption>
</figure>
</div>


When promoting someone or hiring them at a certain level, we consider their IPF will enable them to impact according to "Significant Impact" in the first cycle at that level. As someone starting at a new level, their IPF does not enable them to impact via the next level as much as needed to have enough magnitude to meet its base expectations. Naturally, the IPF will expand unevenly, first in the direction of the current level and later to the next level.

<div align="center">
<figure>
	<a href="../../images/people/ipf-evolution.svg" name="The evolution of the IPF">
		<img  style="width:550px;margin:10px" src="../../images/people/ipf-evolution.svg"/>
	</a>
		<figcaption>The usual case is that one expands their skills to drive higher impacts in their current scope before exploring skills from the next role</figcaption>
</figure>
</div>

Though grades are individual, be mindful of how much they depend on teamwork. Further, even considering OKRs need to align with the company's interests, we cannot overlook the role of intrinsic motivation in particular challenges that drive performance up.

## Representing risk in our model
{: .no_toc }

So far, we are looking at λ as the magnitude of what happened in the cycle. When considering the risks involved in an activity, we can represent the risk-return trade-off by adding intervals to the IPF associated with an individual and an opportunity they plan to tackle (dashed lines). As we take risks, we expect to have the reward integrated into the risk-return trade-off itself. As described previously, how we approach it, which is related to one's skills, plays an essential role in making that opportunity impactful.


<div align="center">
<figure>
	<a href="../../images/people/representing-risk-model.svg" name="Impact risk">
		<img  style="width:550px;margin:10px" src="../../images/people/representing-risk-model.svg"/>
	</a>
		<figcaption>We can with a higher risk and uncertain activity impacts the opportunity input of someone or team's IPF and changes the frontier of possible impact</figcaption>
</figure>
</div>

## How taking risks relates to performance? Do companies punish risk-taking?
{: .no_toc }


When we connect risk-taking and innovation, there is a broadly accepted notion that companies need to consistently take risks to survive [^fn4]. Thus, leaders want to engage people in taking smart risks. Nonetheless, it is necessary for people management and technical tracks, as leadership necessarily involves decision-making under uncertainty and facing ambiguous problems. In general, there will be no way to achieve expectations of higher levels or develop skills for the next scope without some risk-taking via ill-definition, longer time frames, etc.

At the same time, companies can't blindly reward risk-taking. If one rewards risk-taking without context, there will be no incentive to perform low-risk work organizations depend on, such as keeping systems working. People will jump from one Minimum Viable Product to another if one makes unattractive the work of guaranteeing healthy systems or fixing existing products, software, models, etc. 

Punishing or providing unconstrained rewards for risk-taking will damage a company in the long run.

Though doing great work on de-risking projects won't get the maximum reward possible if it fails to bring value to the company to complement the impact, consistently doing a great job on risk-taking will eventually drive a higher outcome. Then, rewarding risk-taking simply follows what was exposed previously.

# References 
{: .no_toc }

[^fn1]: Reilly, Tanya. ["Being Glue — No Idea Blog."](https://noidea.dog/glue) No Idea Blog, Being Glue — No Idea Blog . Accessed 31 August 2022.
[^fn2]: Torres, Teresa. Continuous Discovery Habits: Discover Products That Create Customer Value and Business Value. Product Talk LLC, 2021.
[^fn3]: Rogers, E. M. (2010). Diffusion of innovations. Simon and Schuster.
[^fn4]: Christensen, C. M. (2013). The innovator's dilemma: when new technologies cause great firms to fail. Harvard Business Review Press.
