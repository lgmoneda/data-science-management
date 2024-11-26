---
layout: page
title: Product
has_children: true
permalink: /product-management/
---

## What is product management and what is there for Data Science?
* What is product management, and what is there for Data Science?

When we talk about Product Management, we think about Product Managers and products we use, e.g., Spotify. We know a product divides into several small products, like the Podcasts inside Spotify, and it gets subdivided until it fits a single team, like a "Podcast recommendation", which we identify as a "product feature" as a customer.

This interpretation aligns with the definition by ProductPlan [^fn1]:

> Product management is the practice of strategically driving the development, market launch, and continual support and improvement of a company's products.

As a Data Science professional, you might think it is not something for you since your work is not launched to the market frequently, or even ever. Don't worry. "Product" is more general than that. Looking into a definition:

> 1. an article or substance that is manufactured or refined for sale.
> 2. a thing or person that is the result of an action or process.

When we talk about Product Management for particular expertise, like Data Science, we are interested in the broader meaning, which is the result of the work of a group where all the members or part of them are Data Science specialists, which goes beyond external products and product features.

There are two kinds of products.

- External Product: a customer-facing product. An externally offered product an individual uses to solve a need.
- Internal Product: an employee-facing product. An internal tool an individual uses to do their job better.

I see four Product Management for Data Science classes that are worth differentiating to approach.

- External Products with AI features: it is about the needs of external customers.
- Internal Platforms to enable AI practitioners: it is about the needs of internal customers.
- Decision-making: It typically happens around a decision regarding an external product, but it might not be related to fulfilling the customer's need. E.g., optimizing marketing expends on bringing new customers for a product. It is associated with the result of a group's work towards an objective. It is about the needs of the business.
- Software systems: data science happens with the support of software systems, which generate and process data, intercommunicate, etc. It is about software systems needs.

We will try to answer in all these classes: Why should we do it? What should we build to achieve it? When can Machine Learning help in our objective? Which systems creation or changes will get us there?

As commented in the [Project](https://datascienceleadership.com/project-management/) section, the Product decisions interface the project management stage. In the same way, the "Why should we do it?" from Product will interface Strategy, Vision, and Team leadership, or we can even consider they are all part of the Product area.

<div align="center">
<figure>
	<a href="../../images/product/where_is_product.svg" name="Diminishing returns">
		<img  style="width:700px;margin:10px" src="../../images/product/where_is_product.svg"/>
	</a>
		<figcaption>The most influential decisions regarding Product in a team happen in the vision and strategy level.</figcaption>
</figure>
</div>

In this general sense of Product Management, one can't exercise a leadership role in Data Science without supporting, contributing, or leading Product Management in their team. What is the "Product Manager" role then?

> A product manager is the person who identifies the customer need and the larger business objectives that a product or feature will fulfill, articulates what success looks like for a product, and rallies a team to turn that vision into a reality. [^fn2]

Notice Product Management existed before the Product Managers since customer needs and business objectives were fulfilled before this role was created. It means it is a specialist.

Nonetheless, knowing the customer needs is increasingly more challenging as the customer gets far from the developer, and they represent a large and heterogeneous group. The Product Manager is a specialist in identifying these needs. Though they are typically associated with external products and customers, they can be important for internal customers, business, and systems needs.

If you want to see it clearly, pick a project from your team. Keep asking why the team is working on it. It will hit a need at some point. The work to finding out this need and answer the questions until it becomes a project is what we call here Product Management.

<div class= "mermaid mermaid-language">
flowchart TD

classDef classDefault fill:#286748,color:#FFF,stroke-width:2px,stroke:#286748;
classDef classFork fill:#8b0000,color:#FFF,stroke-width:2px,stroke:#286748;
classDef classTech fill:#ff8c00,color:#FFF,stroke-width:2px,stroke:#286748;
classDef classManager fill:#6495ed,color:#FFF,stroke-width:2px,stroke:#286748;

A[A coupon-referral elasticity model] -->|Why?| B(We need to know how likely a customer will referral when given a coupon)
B -->|Why?| C(the Promotions team wants to optimize their coupon distribution)
C -->|Why?| D(the Growth team has new customers target that won't be hit without improvements in acquisition)
D --> |Why?| E(Growth is a top business need following the company strategy for the next two years)
E --> |Why?| F(The company faces emerging competitors)

style A fill:#286748, color:#fff

%%Style
class A classDefault;
class B classDefault;
class C classDefault;
class D classDefault;
class E classDefault;

</div>
<script async src="https://unpkg.com/mermaid@8.14.0/dist/mermaid.min.js"></script>

However, it doesn't mean you necessarily need a specialist, or they own the entire understanding of the needs. See how incompatible it is to imagine a Data Science or ML Engineering leader working in an internal platform who doesn't know how to uncover the needs of their internal customers except if a specialist does it, or a leader in a product team without any idea on the current business needs and how the decisions they own can contribute to fulfilling them, or a technical leader that needs someone else to tell them how the current system can't fulfill the business goals their company has in two years. Leadership involves a great understanding and ownership of the Product side, including effectively interacting with and leading Product Managers.

Whenever the Product challenge is large and cross-functional, it is advisable to have a Product specialist on the team. The same thing goes for Project Management: when it becomes complex and touches multiple teams, a Program Management specialist becomes desirable.

I have experience with decision-making and a short experience with internal platforms. I'm currently building some with external products. I expect to build this material incrementally as I learn. It is intended to help Managers, Technical leaders, and Product Managers working with Data Science and AI.

## References

[^fn1]: [The Ultimate Guide to Product Management](https://www.productplan.com/learn/what-is-product-management/), ProductPlan.
[^fn2]: [Product Manager: The role and best practices for beginners](https://www.atlassian.com/agile/product-management/product-manager)
