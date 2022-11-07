---
layout: page
title: Strategic decisions
parent: Project
nav_order: 8
---

# Strategic decisions

## What to do when getting to a stepping stone

Finishing a release will offer a stepping stone. Suppose the team decided to deliver business value earlier. In that case, the team can see how impactful it was and the cost of the subsequent releases and choose to stop the project at that stage and pursue other opportunities.

If we have focused on knowledge, it will enable us to make decisions on the solution design and define the following releases, which will require new story mapping sessions. Or even shut down the project.

A Design Review is a good ritual to take the release result and discuss the next steps with stakeholders. We will talk about it in the communication session.

## Simulating the stepping stones for our example

It is still a simplified view on the discussions and decisions, but it is more fair than the snapshot of the timeline.

<div align="center">
<figure>
	<a href="../../images/project/releases-strategic-decisions.svg" name="Strategic release decisions">
		<img  style="width:700px;margin:10px" src="../../images/project/releases-strategic-decisions.svg"/>
	</a>
		<figcaption></figcaption>
</figure>
</div>

## Embrace risk with the right diligence

The team won't be able to exclude all the uncertainty and risks involved in the project. It might not have all the needed data or take too much time.

Learning to take smart risks is necessary in a Data Science project. Getting along with risks means: acknowledging, exposing, listing the trade-off, setting a way to monitor it, and creating a mitigation plan if they become real.

This is an excellent task for technical leaders in the team.

E.g., our coupon-referral model could run in the acquisition stage to decide to give a coupon right away after the registration flow. One of the most important features depends on the acquisition or registration flow, which can be changed (number of screens, their design, etc.). Should the team include that feature in the model? What happens if the change occurs? How would we check if it degraded the model? How could we react?

If you try to answer all these questions during development for all the possible risk scenarios, the project will get excessively long. Know which risks you want to mitigate by analyzing or preparing the solution for it and which ones you will monitor and react to.
