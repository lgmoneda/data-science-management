---
layout: page
title: What is your job description?
parent: Technical Leadership
nav_order: 5
mathjax: true
description: what job postings, professionals, books, and the between the lines say about the Staff Data Scientist and Machine Learning Engineer job
image: https://lgmoneda.github.io/data-science-management/images/technical/graph.jpg
---

# Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

# Introduction

There are many differences in titles and career ladders in the tech industry, including those for Data Scientists and Machine Learning Engineers.

However, there are two common trends. The first is that companies have enabled long-term career progression for technical people. This means that individuals can advance from roles like Staff, Senior Staff, Principal, to Distinguished, which are equivalent to traditional management titles like Director, Senior Director, and VP, over a period of time and based on their performance and skills.

Playing roles of high influence without going to the people and executive management side is great.

Nonetheless, the second commonality is the need for more clarity around these roles: how to get there? What are they doing? Tanya Reilly [^fn1] cites how, after getting to the Staff level, she spotted unspoken expectations and missing skills she couldn’t even describe. These could include the ability to manage complex projects, lead and mentor teams, and make strategic decisions.

For the purpose of this session, 'Staff+' refers to roles from the 'Staff' level upwards, indicating a higher level of responsibility, influence, and impact. The goal of this session is to provide a general idea of and follow through on the expectations surrounding these roles in your company.



# Formal expectations
## Where is it on a career ladder?

A career ladder provides a structure for scope progression. Here’s an example of a ladder for Data Science (see more details in the [article dedicated to ladders](https://datascienceleadership.com/docs/people-management/career-ladder)).

<div class="mermaid mermaid-language">
flowchart TD

classDef classDefault fill:#286748,color:#FFF,stroke-width:2px,stroke:#286748;
classDef classFork fill:#8b0000,color:#FFF,stroke-width:2px,stroke:#286748;
classDef classTech fill:#ff8c00,color:#FFF,stroke-width:2px,stroke:#286748;
classDef classManager fill:#6495ed,color:#FFF,stroke-width:2px,stroke:#286748;

A[Intern] --> B[Jr Data Scientist]
B --> C[Mid-level Data Scientist]
C --> D[Senior Data Scientist]
D --> E[Staff Data Scientist]
D --> F[Data Science Manager]

F --> G[Senior Data Science Manager]
G --> H[Data Science Director]
H --> I[Data Science Senior Director]
I --> J[Vice President - VP of Data Science]

E --> L[Senior Staff Data Scientist]
L --> M[Principal Data Scientist]
M --> O[Senior Principal Data Scientist]
O --> P[Distinguished Data Scientist]

style A fill:#286748, color:#fff

%%Style
class A classDefault;
class B classDefault;
class C classDefault;
class D classDefault;
class E classTech;
class F classManager;
class G classManager;
class H classManager;
class I classManager;
class J classManager;
class L classTech;
class M classTech;
class N classTech;
class O classTech;
class P classTech;
class D classFork;

</div>
<script async src="https://unpkg.com/mermaid@8.14.0/dist/mermaid.min.js"></script>


I split the tech career using the senior level in the ladder article. Before it, one ramps up their autonomy to deliver. At the senior level, they optimize this autonomy. At the post-senior levels, they enter the Staff region. In this region, the influence and impact should ramp up.

In the Staff+ region (post-senior), projects will increase in complexity. Sometimes, it is pure technical complexity. In other cases, it is organizational complexity, like replacing an important legacy system, in which one expects a lot of negotiation and interaction with multiple people from different expertise.

Regardless of the component driving the complexity and ambiguity (novelty, importance, size, interconnections), one expects the Staff professional to absorb it and have the clarity to approach it. Having clarity doesn’t mean knowing everything needed at the beginning. Still, it is about [dealing with uncertainty smartly](https://datascienceleadership.com/docs/people-management/impact-risk-perf-promo#taking-risks). The clarity they provide to people around work more efficiently.

These problems are also likely to set the foundations for many years. It means people will deal with the good and bad consequences of the design choices made at this time for many years (e.g., 5+ years). Experience usually comes into play at this moment, when the Staff+ will recognize important factors that caused future pain on teams from projects they have been part of or learned from. The better the skills in playing this multiple-years-ahead pre-mortem, the higher the momentum created by every initiative and the potential to advance and innovate in that domain by future initiatives that build on top confidently.

There are nuances regarding the expectations depending on the team’s needs that make Staff+ work differ, but we will approach this in the following workshop.

## How do people look for Staff+ in job descriptions?

Let’s review the job postings to see how they define the responsibilities of Staff+. I will link a copy since I expect these pages to expire.

For a [Staff+ Software Engineer at Google](https://pastebin.com/S0Xf4J0z), most of them contain the same bullet points on responsibilities:


> - Provide technical leadership on high-impact projects.
> - Influence and coach a distributed team of engineers.
> - Facilitate alignment and clarity across teams on goals, outcomes, and timelines.
> - Manage project priorities, deadlines, and deliverables.
> - Design, develop, test, deploy, maintain, and enhance large-scale software solutions.

There are explicit expectations for managing project priorities, deadlines, and deliverables. Mentoring others, developing specific projects (high-impact, large-scale, and ambiguous), and providing clarity are base expectations for technical leadership we have seen from the ladder.

For a position for [Staff Data Scientist](https://pastebin.com/Em8Cp0De), the responsibilities are:

> - Perform analysis utilizing relevant tools (e.g., SQL, R, Python). Provide analytical thought leadership through proactive and strategic contributions (e.g., suggests new analyses, infrastructure or experiments to drive improvements in the business).
> - Own outcomes for projects by covering problem definition, metrics development, data extraction and manipulation, visualization, creation, and implementation of analytical/statistical models, as well as presentation to stakeholders.
> - Develop solutions, lead, and manage problems that may be ambiguous and lacking clear precedent by framing problems, generating hypotheses, and making recommendations from a perspective that combines both, analytical and product-specific expertise.
> - Oversee the integration of cross-functional and cross-organizational project/process timelines, develop process improvements and recommendations, and help define operational goals and objectives.
> - Directly or indirectly oversee the contributions of others and develop colleagues’ capabilities in the area of specialization.


It says the same thing but changes to a Data Scientist’s context. We can map every item to the more generic version contained in the software engineer version.

For a [Principal Data Scientist at Amazon](https://pastebin.com/SpZ2iAUx):


> The Principal Data Scientist (DS) on this team is a technical expert and strategic thought leader responsible for tackling highly complex and ambiguous problems. They lead the charge in translating Prime Video’s mission into organizational north-star goals, shaping the product and engineering mental models around causal success measurement, and having a long-lasting influence on the product and engineering roadmap.
A successful candidate will have proven expertise in statistical modeling, machine learning, and experiment design, along with a solid practical understanding of the strengths and weaknesses of various scientific approaches. They excel at deep diving into complex problems, driving innovative scientific solutions, and effectively communicating key takeaways to influence business and product decisions. They set best practices for data-driven decision-making and advise on high-judgment decisions with competing interests.
As a strategic Principal Scientist, you will interact frequently with senior leadership, identify investment opportunities, develop long-term strategies, and propose, influence prioritization, and deliver on goals. You will define organizational success measures and be technically fearless with a passion for building scalable science and engineering solutions. You will serve as a key scientific resource in full-cycle development, from conception and design to implementation, testing, documentation, delivery, and maintenance.
You will also play a pivotal role in career development and mentoring and actively contribute to the hiring process.


We can compare the three so far and find they share ambiguity, impact, longer-range influence, expertise, and strategic role.

Even when we look to a Research role, like a [Staff Research Scientist at Google](https://pastebin.com/EuaksTgu), we find commonalities like dealing with ambiguity, providing clarity, caring about the long-term, and growing a community:

> - Author research papers to share and generate impact of research results across organization and in the research community.
> - Assist in research growth by sharing research trends and best practices within the community by reviewing academic papers, and serving on program committees and grant panels.
> - Deliver on large portions of a project by defining the data structure, framework, design, and evaluation metrics for research solution development and implementation. Identify timelines and obtain resources needed.
> - Identify new and upcoming research areas by interacting with potential external and internal collaborators. Develop long-term research strategy and plans to expand the impact of Google research.
> - Identify complex but defined problems/gaps in existing technology and engage stakeholders and leaders to address them.

Ultimately, the expectations around Staff+ in technical fields are very similar, though it isn’t trivial to read those five bullet points and execute on that level.

# What does Staff+ say they do?

I interviewed a few Staff+ Machine Learning Engineers and Data Scientists working in the same company as me to illustrate their development path to other coworkers. When talking to [Luam Totti](https://www.linkedin.com/in/luam-totti-95088919/), he mentioned

> The problems you tackle should be more complex and ambiguous, ideally unsolvable by anyone at a lower level.

This ambiguity means a Staff+ has something precious to offer to the team: clarity. To provide it, they will have to understand the problem deeply and formulate it to maximize the chance the team can be effective and impactful. Luam cited a couple of questions when digging into a problem:


> - How important is this to my company?
> - Given its importance, how deep should we go into this?
> - Are there more fundamental problems that are causing this? What are they? Can we solve them instead?
> - What are the main components that can be thought about separately?
> - What are the hard requirements for a solution?


When asked how his work differs from that of a Senior or Lead in the same project, it becomes clear how the clarity provided by Staff+ serves the other professionals. It gives them structure and boundaries to build upon. The more junior, the stricter the solution space they are supposed to play with.

> Staff+: “Why aren’t our new spend models improving our limit decisions?”
>
> Lead: “Given this new unbiased test data, what are the causal models we need to solve this problem?”
>
> Senior: “If I want to predict X, what features should I use, which algorithms will I try and which results I want to see?”


It is then a natural consequence that Staff+ have an increasing impact: their answers to the very first inquiries regarding a problem will increase or constrain the impact of a couple of other developers.

Another Staff+ Machine Learning Engineer, [Caique Lima](https://www.linkedin.com/in/caiquelima/), cited the same pattern when developing: he designs the high-level solution, while he delegates the design of the components to the other team members. This is useful for developing them (it is still an open problem) and increasing the team’s throughput.

Caique mentions how he started to focus more on sharing his ideas with the team when delegation became the norm for his work.


> Something that also changed is that today I focus way more on how I share my ideas with the team in order to build together with them the bigger project. If your peers aren’t on the same page as you, it will be really hard to delegate tasks.


Beyond writing less code than before and investing more in design, coordination, communication, and planning, Caique cites how working on a significant problem implies setting the path for himself and the team, deciding which risks to take, and balancing short—and long-term deliveries.

[Guilherme Peixoto](https://www.linkedin.com/in/guilhermepeixoto/), a Staff Data Scientist, gets to the same points regarding the importance of the problems you work on and delegation, coming from a perspective on time availability and opportunity cost.


> Understanding that my time is valuable, learning how to delegate, and thinking in terms of constraints (technical, costs, business…). So I’d say that learning what not to address, I think. As technical-oriented people, there are projects that we trick ourselves into thinking we can roll up our sleeves and tackle ourselves. But every time I decide on what to do, there’s an opportunity cost of what I’m choosing not to do. And as my scope grew larger, the opportunity cost grew higher. This is not to say that there are projects that are beneath me, but my time has become better equipped to be spent on defining direction and making sure that deliverables meet quality standards (be it from a statistical, software, or scalability perspective) rather than developing those projects myself most of the time. So I need to choose carefully what I’ll review, supervise, guide, or develop, and navigate the fine line in between.

Differently from the others, Peixoto was a Staff Data Scientist in a business/product team. He noticed that impact won’t scale if you can only pick problems that the solution lies entirely within your expertise or technical field. Naturally, he had to expand to deal more frequently with product managers, designers, engineers, and business analysts to expand the sort of problems to which he could contribute to the solution.

It is common in all three how it involves increasingly harder tech problems that at the same time demand way more soft skills - communication, planning, alignment, mediation, negotiation, etc. Placing them together, one can derive how being a Staff+ in their context will be by identifying what is needed to solve the significant and ambiguous problems from their domain. In some teams, it will have a higher weight on understanding the company’s underlying infrastructure; in others, it will get you to talk to multiple internal customers. The relevant problems will also change in nature even in the same team, so one also needs to think about the domain’s cycles and evolution, and how favorable it is to their personal taste in terms of skills it will demand from them.

# Structuring expectations for Staff+

Two interesting resources try to capture all these nuances and provide structure for people in the Tech track: Staff Engineer, leadership beyond the Management Track [^fn2] and The Staff Engineer’s Path [^fn1]. I will briefly expose their framework.

Larson [^fn2] splits it into five broad responsibilities.

- **Setting technical direction**: setting, refreshing, or editing the direction the team needs to take on certain technical aspects to serve the broader organization’s long-term goal. The team wants to do better, but there will be vague and conflicting ideas. Having a clear state to pursue and a couple of principles, guidelines, and definitions about how to get there is precious to a group, and defining it in a tech domain demands technical knowledge.
- **Mentorship and sponsorship**: effectively growing the team around you to achieve the milestones from the direction you supported them to set.
- **Providing engineering perspective**: taking your expertise perspective into cross-functional rooms composed of leaders, including people more senior than you.
- **Exploration**: teams and companies sometimes try to break their status quo cages by defining a small group to explore alternatives. Staff+ is commonly assigned to this group.
- **Being glue**: doing the [needed and invisible work](https://www.noidea.dog/glue) that’s not glamorous but makes things happen sooner.

Regarding the expectations on setting technical direction, Larson mentions that the Staff+ would act as a “part-time product manager for technology”. Software engineering's products interface became intuitive because of how pervasive digital services are today. So, people got used to describing the goal of Software Engineers using user stories and use cases. This seems to take away from more junior engineers their critical sense regarding whether the team is building the right thing to solve the problem - or even to know which problem they are solving. In Data Science, it isn’t that natural (yet) for non-data scientists to connect the problem to what a data scientist actually has to do to contribute to the solution, which means fewer people dictating the solution for Data Scientists and “translating business problems into Machine Learning tasks” being an essential skill since the beginning of the data science career. I think Software Engineering had a similar path in the past. Still, somewhere along the decades, people get used to delegating to product managers (PMs) to define what the team should pursue because they can very well describe a solution that would solve the end customer’s pain. It gets to a point where a PM becomes a necessary member of a team where you have engineers. I believe that all successful tech leaders have excellent product management skills, just as you expect in their package, along with a couple of communication skills. In a health team, PMs and tech leaders contribute to the understanding of the problem level differently, and also share the build and exploration of the solution space. One hypothesis on the hard time some technical folks have on growing to the Staff+ region is that some lived in this very constrained environment where they were demanded to only make implementation decisions, while the definition and decisions on what the team would produce were delegated entirely. So, suddenly, they need to expand a skill to the same level that other professionals have been developing for 5-10 years. The more tangible the consequences of your technical decisions become to non-technical people, the more you exercise the Product Management skills you will carry for your entire career. I open up Product Management in [another section](https://datascienceleadership.com/product-management/), and I talk about leading your domain as a [tech-driven way to lead a career](https://datascienceleadership.com/docs/technical-leadership/tech-driven-career) in another article.

Reilly [^fn1] splits the Staff+'s expectations into three pillars:

- **Big picture thinking**: being able to see and plan beyond the immediate needs of a team. It includes understanding and consuming broader visions about the company and understanding the evolution of your technical domain. It can generate initiatives spanning a couple of years via multiple projects.
- **Execution**: execute initiatives that contain large amounts of ambiguity and challenges that go beyond technology.
- **Leveling up**: increasing the level at which your craft happens around you. The more senior, the larger the radius. Both through direct activities, like teaching and mentoring, and by being a role model.

As you can see, both perspectives cover the same aspects. We can map them as follows:

<div class="mermaid mermaid-language">
flowchart LR

classDef classDefault fill:#286748,color:#FFF,stroke-width:2px,stroke:#286748;
classDef classFork fill:#8b0000,color:#FFF,stroke-width:2px,stroke:#286748;
classDef classTech fill:#ff8c00,color:#FFF,stroke-width:2px,stroke:#286748;
classDef classManager fill:#6495ed,color:#FFF,stroke-width:2px,stroke:#286748;


A1["Setting technical direction"]
A2["Mentorship and sponsorship"]
A3["Providing engineering perspective"]
A4["Exploration"]
A5["Being glue"]


B1["Big picture thinking"]
B2["Execution"]
B3["Leveling up"]

A1 --> B1
A2 --> B3
A3 --> B1
A4 --> B2
A5 --> B2
A5 --> B3

class A1 classDefault;
class A2 classDefault;
class A3 classDefault;
class A4 classDefault;
class A5 classDefault;

class B1 classManager;
class B2 classManager;
class B3 classManager;

</div>
<script async src="https://unpkg.com/mermaid@8.14.0/dist/mermaid.min.js"></script>

# Situations where managers look for Staff+ Data Scientists and Machine Learning Engineers

The previous sections contain what leaders expect from a Staff+ Data Scientist, Machine Learning Engineer, or Engineer. However, there is a lot between the lines! As someone who has worked as a people manager and talked to others in this position, I have seen a couple of situations where this demand appears that illustrate well the role.

As we have seen in the section [Conway’s Law and team boundaries](https://datascienceleadership.com/docs/technical-leadership/conway-law-team-boundaries), the Machine Learning wave in the industry started around 2014, so we now have 10+ years of people applying it massively. In ML, many decisions can trap a team and erode its evolution. After generations of ML solutions, some teams start to get trapped. For example, the feedback loop between what a model predicts, the decision made with the prediction, and the effect of the prediction on an outcome we care about that feeds again into a model’s future version as the target. This loop can turn an ML model from value creation to value destruction. A recommender system biased by its previous recommendations is an example. It takes a bit of experience and seniority to notice this pattern and a lot more seniority to break it. Usually, breaking it is harder than not getting into it in the first place, which gives me one generic pattern I’ve seen: *people will look for a Staff+ when they realize that many bad or naive decisions taken in the last ~5 years trapped their team*. In this case, the expected outcome is to get the team out of that cage, which is an effort people expect to take multiple years, though they want to see incremental results from solving it progressively.

When a sub-field in ML is new, either to the field or only to a company’s scope (for example, computer vision for a company unused to work with it), and depending on the size of the business bet supported by it, people will look for a Staff with some experience on that field, or to correlated fields. GenAI is what naturally comes to mind at this moment. Many companies spin up their GenAI first team by grabbing some of their most senior folks or going to the market after them. The expectation here is that the Staff Data Scientist or Staff Machine Learning Engineer will know how to navigate a novel area, learn quickly what matters the most, build foundations even if the market hasn’t them well defined for that sub-field, and quickly start delivering value by leveraging that hot topic.

As a company matures in applying ML, another effect is that a couple of models will become so important to its revenue streams that even the most straightforward approaches will have a positive return on investment by having a Staff+ owning it. Selling ads, making recommendations, setting product prices dynamically, evaluating creditworthiness, etc., are the main engines for many businesses. Leaders on these teams will have a huge responsibility, and the teams related to these topics are prone to grow a lot, so the responsibility needs to be shared, and addin more experienced pair of eyes becomes helpful. The expectations of a Staff Data Scientist or Machine Learning Engineer, in this case, are primarily related to keeping a very high bar, leading quick reactions to crises, and eventually leading step changes since these teams have a tendency to go for incremental improvements for longer periods than others since marginal gains translate into large amounts of value to the company.

# Workshop #4 - Job description

[Miro template](https://miro.com/app/board/uXjVKms1KIM=/?share_link_id=752512685457).

The provocation of this activity is: Does your idea of the role of a Staff member on your team match the image of other team leaders?

The activity is to write a Staff+ job description and expectations for your team. You might be someone in a Staff+ level or 1-2 levels below. If on level, you have done something like that already. But I often see people not trying to translate. Instead of only writing down “setting the team direction”, it is better to identify which aspects the team lacks direction the most, and you could generate the most impact by clarifying it. A level below is a great moment to think about it because it clarifies what stretch means in your context.

Then, show it to your manager and/or team leader. Iterate until you have a shared understanding of your role or what stretching to a Staff Data Scientist / Machine Learning Engineer means.

# References

[^fn1]: Reilly, T. (2022). The staff engineer’s path: a guide for individual   contributors navigating growth and change. : O’Reilly Media, Incorporated.
[^fn2]: Larson, W., & Reilly, T. (2021). Staff engineer: leadership beyond the management track.
