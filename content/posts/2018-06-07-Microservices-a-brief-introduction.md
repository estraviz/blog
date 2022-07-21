---
layout: post
title: "Microservices, a very brief introduction"
description: "An introductory talk about microservices, by Martin Fowler"
categories: [Tech]
comments: true
tags: [Microservices, GOTO, ThoughtWorks, Martin Fowler, Big Ball of Mud]
date: 2018-06-07
---

***
_N.B.: blog entry originally posted in my previous blog, still available [here](https://estraviz.github.io/estraviz2017/software%20design/Microservices-a-brief-introduction/)._
***

Nowadays everybody talks about [microservices](https://en.wikipedia.org/wiki/Microservices) and microservices architecture in software development. But this is not a new concept and has been around in the last years. Well, everybody talks about them but it doesn't mean everybody has been able to refactor their platform in this direction, although might be willing to.

As an introduction to the microservice approach, I recommend this video from [**Martin Fowler**](https://martinfowler.com/), a british software developer[^1] quite popular and author, among others, of books such as [_Refactoring: Improving the Design of Existing Code_](https://www.amazon.com/Refactoring-Improving-Design-Existing-Code/dp/0201485672/) or [_Patterns of Enterprise Application Architecture_](https://www.amazon.com/Patterns-Enterprise-Application-Architecture-Martin/dp/0321127420/). This talk was part of the well-known [**GOTO conferences**](https://blog.gotocon.com/) that took place in Berlin in 2014.

***
{{< youtube wgdBVIX9ifA >}}
***

Fowler summarizes the common characteristics of Microservices in the following list that I want to keep for myself here:

1. Componentization via services.
2. Organized around business capabilities.
3. Product not Projects.
4. Smart endpoints and dumb pipes.
5. Decentralized Governance.
6. Decentralized Data Management.
7. Infrastructure Automation.
8. Design for failure.
9. Evolutionary Design.

Another point to keep in mind, the comparison between Monolith vs. Microservice, as follows:

|         MONOLITH         |    MICROSERVICE     |
| :----------------------: | :-----------------: |
|        Simplicity        | Partial Deployment  |
|       Consistency        |    Availability     |
| Inter-module refactoring | Preserve Modularity |
|                          | Multiple Platforms  |

Other ingredients of microservice architectures:

* Traceable Business Transactions.
* Continuous Delivery.
* Product-centered Teams[^2].
* Multi-Dev Environment.
* Rapid Provisioning.
* Basic Monitoring.
* Rapid Application Deployment.
* DevOps Culture.

Really convincing arguments to abandon the monolith path that soon turns into a [Big Ball of Mud](https://en.wikipedia.org/wiki/Big_ball_of_mud) and follow the microservice way, right? _What do you think?_

For further reference, see also [this article](https://martinfowler.com/articles/microservices.html) from Mr. Fowler (and recommended in the video).

_Regards!_

[^1]: _Martin Fowler works at [**ThoughtWorks**](https://www.thoughtworks.com/) (June, 2018)._
[^2]: _This is currently a matter of active discussion in the company of a good friend of mine (that I'm not going to mention here, sorry)._
