---
layout: page
title: Defining a Starter Project
parent: People
nav_order: 2
---

# Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

# Defining a Starter Project in Data Science
{: .no_toc }
A new Data Scientist or Machine Learning Engineer is going to join the team soon. One of the most important steps during the onboarding is the starter project: the first real thing the new member will do.

However, it shouldn't be any project. The starter project can set the tone for new hires' first couple of months in the company. Regardless of the new member seniority, the definition of the starter project requires attention. A Data Science Manager should pick one that respects the recent member ramp-up, delivers value, maximizes learning, generates momentum, and gets rid of the impostor syndrome.

The principles in this article are general, but the examples focus on Data Science.

<div align="center">
<figure>
	<a href="http://lgmoneda.github.io/images/starter-project/kelly-sikkema-O5XJoxrYbQo-unsplash.jpg" name="Blank Page">
		<img  style="width:550px;margin:10px" src="http://lgmoneda.github.io/images/starter-project/kelly-sikkema-O5XJoxrYbQo-unsplash.jpg"/>
	</a>
		<figcaption>A starter project is a start that should not look like starting on something new. No blank page feelings. <br>Source: Kelly Sikkema</figcaption>
</figure>
</div>

## The requirements of a good starter project

### Not time sensitive
{: .no_toc }
A non-time-sensitive project does not block any initiative, team member, or external agent. It is a period when learning comes first, and delivery comes next. A hard deadline could make the new member sacrifice their education to not compromise the team. Furthermore, it can be pretty stressful to be pressured in an environment where it is still unclear how to get things done.

It does not mean the project could be delivered at any moment, but the deadline is so forward in time you can abstract from it. Estimate the new person will take at least twice as long as an onboarded member and set a project that won't generate stress even if they take four-time as long.

A red flag is having the new member build a necessary piece of an important project. E.g., a database, dataset, or infrastructure required to deploy a model the team is working on or will do soon. Working in a project that involves many team members makes it more likely the delivery timing is essential to enable other members to do their work. Or even worse, a project which is already late.

### Clear description and Definition of Done
{: .no_toc }
That's what we want all the time and for everybody. However, there are initiatives for which defining their success criterion is more straightforward. Chose them. You want that at the end of the starter project, something very concrete and valuable to the team happens, like:

- A recommendation to use or not a particular approach in the next version of a model;
- A great demonstration that a new source of data is or is not valuable;
- A deployed model making decisions, or discarding an ML model to make that decision;

To achieve it, think if you can tell an objective way to check if the analysis can be linked to a decision or if the code should hit production. If the team is unsure how to make these decisions using the new member's work outcomes, avoid it as a starter project.

Your company probably has expectations on how raw the demands should get to people at a different level. While more junior members execute obvious tasks, more senior ones deal with ambiguity and shape what needs to be performed.

However, at the beginning, it is better to consider the person belongs to one or two more junior levels than the one they were hired. If you hired a Data Scientist, provide the support you would give to a Junior Data Scientist. If it was a Staff, treat them as a senior. I'd suggest further to treat anyone above Staff as a Senior when they start. It means providing a ridiculously well-documented project in a tool like Jira, Trello, and Asana. Link tasks to the right documentation, explicit help channels, break it the most you can (and for jr members, it means to a level of hourly or daily tasks). Let the person know you are doing it for them because it is the starter project, and use it to set the bar of what you expect them to do by themselves after it.

### Zero or low ambiguity, no external dependencies
{: .no_toc }
A zero ambiguity problem won't generate changes in the direction. It won't place the new person in a position no one in the company can help them.

Do not offer a project the team failed in the past! There is likely ambiguity if the team fell on it in the past.

Evidently, avoid a project that is or might be blocked. For example, if its data depends on an external agent or the team is unsure if the available data has the quality to enable the project.

Testing a new data source in an existing model is a great option. But if the data is not available yet, it becomes a poor choice.

### A buddy who knows how to execute the project
{: .no_toc }
A current team member should be able to execute that project from the beginning to the end without any change in the initial plan. Set one of the team members in this situation as the buddy of the new hire.

It will enable very productive pairings, great and specific answers, and a trust in the new member that they have the perfect support to succeed in their first endeavor.

That's why the previous requirement is essential. The lower the ambiguity, the higher the chance one member or more of the team fits in this description and can play the buddy role perfectly. Since you will treat the new hire as more junior, a buddy from the same level can do a great job.

### Relatively short
{: .no_toc }
We might be tempted to say "the shorter, the better", but it is not precise. Accumulating mini-tasks and calling them a starter project is likely related to bugs, unexciting things, barely important tasks, etc. As they are very short and quick, they can become too specific and not enable the new member to generalize. For example, fixing the model monitoring for a specific metric that is broken. It is likely the person could execute it. Still, they build without learning how to set up a complete model monitoring for a future model.

We want the shortest but constrained to all the other requirements.

A good time is 2-8 weeks because it is long enough to include different stack parts and meaningful chunks of work. The more end to end, the better, but always zero or low ambiguity. If the person's core job is to deploy ML models, develop the shortest project about deploying a model.

Finishing a successful project quickly and presenting it to the team creates a lot of momentum.

### It prepares the person for the following projects
{: .no_toc }
A project might respect all the requirements but fail to prepare the new member for the following projects. It is expected they will use at least one tool, programming language, system, etc., that will be important for most of their following projects.

Eventually, Data Science projects touch engineering or analytics stack. Avoid using a starter project who would most teach about a "nice to have skill" for their role. For example, Machine Learning Engineers might not frequently touch the microservices at your company. Though it is very cool to have this skill, and many great MLEs will leverage it, it is better to use the starter project to build core skills, which they will need in most future projects.

The same goes for a Data Scientist. You might have a project that involves 20% of data knowledge and 80% of finances. It is an ok project for onboard members. Still, suppose it is uncommon for Data Scientists to leverage financial knowledge in their projects at your company. In that case, it is investing 80% of the starter project in skills they are unlikely to use in the next couple of months.

## How to make it perfect

These items make the good starter project a perfect one.

### High probability of being impactful
{: .no_toc }

Prefer to provide something impactful. Delivering value in a new company is extremely relieving for the new hire. Everyone on the team will feel excited about it. Usually, tasks related to cost reduction are unambiguous and impactful.

We know Data Science projects might require some exploration before you tell their potential impact. If needed, do this exploration before the person joins to decide about the starter project: checking data volume, the money involved in a decision, if there is variability in customer behavior for a particular action, etc.

If it involves making decisions, prepare the ground to discover if the team or the company is open to doing it. Even a clear profitable decision can find resistance if it chances customer experience.

### High visibility
{: .no_toc }
Another trait that can make a starter project perfect is visibility and contributing to a critical part of the company. This kind is usually related to future improvements to an essential solution. If your team has an ML model making decisions, consider having the new member test a couple of specific approaches. For example, adding new features, feature engineering, excluding features, simplifying, etc. Any marginal improvement in a critical solution is likely impactful. They will recognize their work integrated into a project with a lot of visibility: "Wow, our main recommendation model uses this kind of features because of the work I did!".

At the same time, if they do not improve it, the team is happy to have its documentation. You can broadcast to all Data Scientists in the company about the effectiveness of that approach. As long as the next version itself was not dependent on this source of improvement, it is okay.

### It is easy to estimate impact
{: .no_toc }
A project can be deemed impactful without an easy way to measure it. For example, a tool that makes a process take less time and is used by 20+ people monthly is likely to be called impactful. Since we want to make the new hire's success as explicit as possible, picking a starter project which we can pinpoint the monetary benefit is perfect.

### Instead of one starter project, offer a few and in a ramp-up
{: .no_toc }
As recommended, in a starter project, it is good to offer the new members a support as they are more junior than their current level. One way of doing it is breaking the starter project into a few with progressive expectations and challenges.

It is useful when there isn't a starter project that follows all the requirements, but you can see 2-3 that follow some of them but disjoint. A 1-2 weeks project can be called a warm-up. If you need two warm-ups to teach two important parts of the stack, go for it. For Data Scientists, it is usually doing "offline" analysis. The kind that tells us which direction we should move in the future: include a new feature or not in an existing model, include or stop using a rule-based solution, do a presentation about the data acquired in a recent experiment, etc. For a Machine Learning Engineer, deploying a toy model, or doing an update like excluding a broken feature in an existing non-important model can teach the end-to-end in a light task before going for more challenge.

Still, the warm-up projects need to follow most requirements and prepare for the next projects since we use them to ramp up the new person. They need to expose the new member to the company's tools, flows, processes, and business. If the warm-up dit not stretch the person at all, reconsider the next steps in the ramp-up to adjust them.

## Relaxing the conditions

### I just hired this DS / MLE because we have this very important and time-sensitive project
{: .no_toc }
It will happen frequently. In these cases, the warm-up project with the ramp-up is a good strategy.

The warm-up project can be related to the ambitious one. It can be a slice of it. Examples I've seen working: the research phase of a new model version or understanding the underlying data. In these cases, it is essential to mark it as a stage with a specific delivery. So when the person delivers it, they feel they have accomplished something meaningful and created momentum for the challenging project.

### It is a new team; we have no idea about what a Data Scientist could do and anyone to be a buddy
{: .no_toc }
There are alternatives. First, to avoid being demotivated by ambiguous projects no one in the company knows how to execute, consider asking another team to onboard and provide a starter project for this person. Second, there is a chance that applying data science to that particular use-case is not new for a company member whose not in the new team. Look to someone to help you specify the project following the characteristics we highlighted earlier.

However, this whole situation is tricky despite the starter project. The more junior the member, the higher the risk of allocating in a new team. Before finding out the starter project, think if it makes sense to have that member assuming that position.

### The team has no project with low ambiguity
{: .no_toc }
If it happens, use one or two warm-up projects to mostly teach tooling. If the starter project is ambiguous, let the new member know. And make sure you have enough people around to support you. It is challenging in two ways. First, you will guide a new member in an initiative that would be hard even for an onboard one. Second, it becomes trickier to distinguish if an eventual poor performance is due to the initiative or the new member is not ramping-up as expected.

## The checklists
Let's create two checklists. The first is to guarantee we're setting the new hire for success. Think about the Starter Project you have in mind and ask yourself if you have or can offer what is described. You should tick all the boxes.

<table class="styled-table" style="margin-left:auto;margin-right:auto">
    <thead>
        <tr>
            <th style="text-align:center">Requirements</th>
            <th style="text-align:center"></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>This project won't block someone in the company if not delivered in time</td>
            <td style="text-align:center;font-size:18px">&square; </td>
        </tr>
		<tr>
            <td>The team knows how the project's output becomes an outcome for the company</td>
            <td style="text-align:center;font-size:18px">&square; </td>
        </tr>
		<tr>
            <td>There's a very detailed description of the project in a tool like Jira</td>
            <td style="text-align:center;font-size:18px">&square; </td>
        </tr>
		<tr>
            <td>There is no ambiguity, it is unlikely the project direction will change</td>
            <td style="text-align:center;font-size:18px">&square; </td>
        </tr>
		<tr>
            <td>The project progress do not depend on external agents</td>
            <td style="text-align:center;font-size:18px">&square; </td>
        </tr>
        <tr>
            <td>The buddy knows very well how to execute the whole project</td>
            <td style="text-align:center;font-size:18px">&square; </td>
        </tr>
		<tr>
            <td>The project will take only 2-8 weeks, even considering a new hire pace</td>
            <td style="text-align:center;font-size:18px">&square; </td>
        </tr>
		<tr>
            <td>The knowledge acquired on it will be used in most future projects</td>
            <td style="text-align:center;font-size:18px">&square; </td>
        </tr>
    </tbody>
</table>

Following the requirements, having a positive experience in the starter project becomes likely. However, we can make it awesome! The more ticks you have in the following list, the better.


<table class="styled-table" style="margin-left:auto;margin-right:auto;width:581px">
    <thead>
        <tr>
            <th style="text-align:center">The awesome starter project checklist</th>
            <th style="text-align:center"></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>It involves one of the team's main problems or solutions</td>
            <td style="text-align:center;font-size:18px">&square; </td>
        </tr>
		<tr>
            <td>It is easy to estimate monetary impact, and it is likely high</td>
            <td style="text-align:center;font-size:18px">&square; </td>
        </tr>
		<tr>
            <td>It saves money from a very costly process</td>
            <td style="text-align:center;font-size:18px">&square; </td>
        </tr>
		<tr>
            <td>It is broken in a few projects of progressively difficulty</td>
            <td style="text-align:center;font-size:18px">&square; </td>
        </tr>
		<tr>
            <td>It is likely to expose the new hire to other business teams</td>
            <td style="text-align:center;font-size:18px">&square; </td>
        </tr>
		<tr>
            <td>The project can be a reference to solve a similar problem in another team</td>
            <td style="text-align:center;font-size:18px">&square; </td>
        </tr>
		<tr>
            <td>There's an audience who would be very interested in a presentation about it</td>
            <td style="text-align:center;font-size:18px">&square; </td>
        </tr>
    </tbody>
</table>

## Examples

### Evaluating a new data source for the team's main model
{: .no_toc }
A new data source provides novel data to feed a Machine Learning model. When it is an external source, the team needs to evaluate if integrating makes sense. It is one of the main drivers of a new version of a specific model.

In this case, the team was not working on a new version yet. There was no time pressure. The data needed to evaluate was already available, with no external blocks. It was likely the new data would improve the model. We knew exactly how to say yes or no to this decision by looking at the project results. It was likely to be a yes, and it was! The starter project of the person triggered the work of a business architect and engineering, then from machine learning engineers and data scientists. It was included and significantly impacted the team's primary model. Though the feedback was long, the new hire could recognize their work importance.

### Developing a nice-to-have batch model
{: .no_toc }
A batch Machine Learning model scores new examples periodically fed by stored data. In contrast, a real-time model needs to score a new example generated by an action with low latency. Engineering-wise, real-time models are more complicated.

Looking at the backlog, the most impactful project in the team was a real-time model - which included a few external dependencies. However, a starter project is not any project, so the prioritization process changes. To onboard a new Machine Learning engineer, we decided to work on a different project, a batch model whose impact was smaller.

Why has it worked well? There wasn't time pressure and dependencies. The buddy knew how to execute all the tasks assigned to the new hire. The model was not complex, the audacity and ambiguity were low, so the project has not changed from what was initially proposed. After finishing it, the new hire worked in the real-time model, which offered the right challenge level to flow.

### Developing a new version of an important model
{: .no_toc }
Commonly, there is no way to avoid having the new hire working on a critical project. In this example, other team members worked in the previous two versions of it and were ready for new challenges. So we have decided to allocate the new members on it.

Two things were crucial to make it work. First, a short warm-up project to prepare for it. It took the form of a research phase that could stack new changes to the following version, but without depending on their impact to justify it. Second, having the previous developers as buddies of the two new hires and explicitly making them accountable for their success. Furthermore, this new version had a very clear value proposition, no ambiguity.

It has broken the non-time-sensitive requirement. However, the timeframe wasn't particularly challenging, and the buddies were close enough to mitigate it. On the other hand, the impact and importance of the project provided huge exposition.

## Conclusion

Defining a starter project requires the Data Science manager to balance many things. Fight hard to fill in all the requirements. Consciously relax them if needed at the expense of allocating more of your attention to make it succeed. The high investment during this stage will pay off quickly.

<!-- ## References -->

<!-- [^fn1]: Arjovsky, M., Bottou, L., Gulrajani, I., & Lopez-Paz, D., Invariant Risk Minimization (2019). -->
<!-- [^fn2]: Lu, C., Wu, Y., Hern\'andez-Lobato, Jo\'se Miguel, & Sch\"olkopf, Bernhard, Nonlinear invariant risk minimization: a causal approach, arXiv preprint arXiv:2102.12353, (2021). -->
