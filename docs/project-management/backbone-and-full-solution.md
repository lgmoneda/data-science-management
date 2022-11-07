---
layout: page
title: Backbone & Full solution
parent: Story Mapping
grand_parent: Project
nav_order: 1
---

# Defining the backbone

In the high-level description, we should have everyone in the room contributing equally and engaging in the conversation.

Do not worry if a particular stage does not make sense for developers, like parts in which the user interacts with existing elements that won't change. For example, for a new version of a recommender system, in which the team doesn't want to change the interface, all users' interactions with a product until they get the recommendation will be already implemented.

The important thing is to have a cohesive story at the top. A story that makes sense for everyone in the company under that product's influence.

<div align="center">
<figure>
	<a href="../../images/project/backbone.svg" name="Backbone">
		<img  style="width:650px;margin:10px" src="../../images/project/Backbone.svg"/>
	</a>
		<!-- <figcaption>Putting together the many common terms for these two stages</figcaption> -->
</figure>
</div>

For the following row, people from the different functional teams more involved in certain stages should start breaking it into steps that still make sense for non-technical people but are helpful to implementation.

## Mapping everything needed to have the full solution up and running


The team will now map everything they need to implement to make the story they have agreed on happen. Go column by column, following the backbone. "What is the relevant data? What do we need to have it?"

The level of description of what we map should still need breaking to become actionable tasks. Remember, the room is full of cross-functional people, so getting into too many details now is not the idea.

If there are too many items and various things under the same column, think if it is not possible to split the second line in the backbone into different stages.

In the image we show all the stories after this process. They can be more specific (service names, internal process, etc). 

<div align="center">
<figure>
	<a href="../../images/project/complete-solution.svg" name="Complete solution">
		<img  style="width:650px;margin:10px" src="../../images/project/complete-solution.svg"/>
	</a>
		<!-- <figcaption>Putting together the many common terms for these two stages</figcaption> -->
</figure>
</div>



Even during the backbone definition, some open questions and assumptions will start pop-up. Take notes of them to not lose track, and avoid getting into sub-discussions. Keep a single path by making assumptions and registering them. These notes will be vital for the next stage. They are in the left of the image, accumulating with the uncertainties we could map during the backbone. Naturally, they will get more technical.

For example, in our case, the team might start a short discussion or recover it from the RFC on the scoring time for the model, which implies in changes on the model design. In the image, we show these notes in the left. 

