## HealthSoft - SQA

Welcome one the SQA website of HealthSoft. The goal of the SQA office is to improve practices in order to get better software quality.

> _Abstract:_ For the redaction of this document, I was largely inspired by my experience at Sogilis, a French company developing high quality software, where I worked the last year. We use at Sogilis agile as a disruptive way, not only as a process of software development, but also as a methodology for the management of the whole company. I was really inspired by this methodology and I really think that combined with the good team, you can achieve very high quality software. At Sogilis, the minimum requirement is zero defect.

## Who am I?

My name is Nicolas COMTE I oversee the Software Quality Assurance office of HealthSoft, my student number is D16124638, and you can contact me with my email: d16124638 [at] mydit.ie

## Why a SQA office?

During many years HealthSoft worked very well without any SQA Office. But as the company grow, and our customers are being more exigent we must adapt our process and our way of developing software.
That's what the SQA Office if intended for. During the following weeks, we will discuss together and review our actual practices and identify an aspect that needs improvement.
Then we'll plan the actions to take and act in consequences.
Finally, we'll evaluate the results and the benefits of the actions taken, and plan again other actions if needed.

## State of art

The actual process of project management is following a waterfall cycle.
The major disadvantage of this project cycle is that we cannot assure an effective monitoring with the customer.
It adds a lot of latency and misunderstanding from both sides (customer and developer). Moreover, it adds a lot of confusion when the customer wants to change a thing at a really advanced stage of development when it has not been thank from the start.
Also, there is not much feedback from the development team about the problems they encounter and sometimes it can lead to a huge delay in the delivery.

## Agile method, Scrum master: a new solution

### Agile

To manage a project such as a software development there is different ways to do. Here at HealthSoft since a long time we use a traditional waterfall method. You all use it every day on every project and it works.
Recently, in the 1990 a new method was introduced. This method is called __Agile method.__ This method is particularly adapted to the software development environment and is today widely used in many companies.
Agile method is ruled by a manifesto, which is accessible at the following address: [agilemanifesto.org](http://agilemanifesto.org/)

Here are the 12 principles of the Agile Manifesto (_source: [agilemanifesto.org/iso/en/principles](http://agilemanifesto.org/iso/en/principles.html)_)

* Our highest priority is to satisfy the customer
through early and continuous delivery
of valuable software.

* Welcome changing requirements, even late in
development. Agile processes harness change for
the customer's competitive advantage.

* Deliver working software frequently, from a
couple of weeks to a couple of months, with a
preference to the shorter timescale.

* Business people and developers must work
together daily throughout the project.

* Build projects around motivated individuals.
Give them the environment and support they need,
and trust them to get the job done.

* The most efficient and effective method of
conveying information to and within a development
team is face-to-face conversation.

* Working software is the primary measure of progress.

* Agile processes promote sustainable development.
The sponsors, developers, and users should be able
to maintain a constant pace indefinitely.

* Continuous attention to technical excellence
and good design enhances agility.

* Simplicity--the art of maximizing the amount
of work not done--is essential.

* The best architectures, requirements, and designs
emerge from self-organizing teams.

* At regular intervals, the team reflects on how
to become more effective, then tunes and adjusts
its behavior accordingly.

### Scrum master


> The authors described a new approach to commercial product-development that would increase speed and flexibility, based on case studies from manufacturing firms in the automotive, photocopier and printer industries. They called this the holistic or rugby approach, as the whole process is performed by one cross-functional team across multiple overlapping phases, where the team "tries to go the distance as a unit, passing the ball back and forth". (In rugby football, a scrum refers to a tight-packed formation of players with their heads down who attempt to gain possession of the ball.)

>_source: [Wikipedia]( https://goo.gl/rxUOZs)._

Scrum is an agile framework that introduce a set of processes in accordance with the Agile manifest. In this framework, the team self-organize and can make change quickly. The three pillars of Scrum are __transparency, inspection,__ and __adaptation__. The team need to inspect the product being developed frequently so they can spot any problem or deviance as soon as possible. Each member of the team must trust and be open. Here are the 5 values a team member should match:
* Commitment: You individually commit to achieve your team goals.
* Courage: You know you have the courage to work through conflict and challenges as a team, and do the right thing.
* Focus: You focus your work on what is in your backlog, and your work is only done through the backlog.
* Openness: You must be totally transparent about what you do, and more importantly about the challenge you encounter. There is no judgment here, you are part of a team and you work with the help of the team to resolve the challenge you face.
* Respect: You respect each member of the team as technically capable of doing the work, and when they face a problem, you work with them as a team to solve it.

In Scrum master, there is three different roles.
The __Product Owner__ is the person representing the customer’s stakeholders. There is only one PO for each project.  His role is to write customer-centric items as user stories. User stories are an informal way to explain a core feature of a software system, written in natural language. The Product Owner role must not be combined with the Scrum Master role. The Product Owner focus on the business side of the product and should not dictate how the team reaches a technical solution.

The __Scrum Master__ is a facilitator, and there is only one Scrum Master per team. The SM is __NOT__  a team leader of project manager. His role is to act as a buffer between the development team and any distracting influences. The Scrum Master also help the team for example to work on the Definition of Done for the product. The Definition of Done is all the criteria required to define a task as done. He also helps the team to work together by acting as a facilitator. A huge responsibility of the Scrum Master is also to educate the PO in Scrum principles and agile methodology.  *__Although the title of scrum master sounds powerful, the scrum master is not the project leader and is not held accountable for outcomes. The team as a whole is responsible for outcomes.__*

The __Development Team__ is responsible for delivering the product at the end of each sprint. A Development Team should not excess 10 persons. A development team is self-organized and is cross-functional

## How a typical project will look like?
![Scrum Framework](https://upload.wikimedia.org/wikipedia/commons/thumb/d/df/Scrum_Framework.png/1024px-Scrum_Framework.png?1491904277229 "Scrum Framework")

Here is the Scrum framework, which should inspire the way you should manage the project you will work on.

1. First of all, when a new project comes, you'll have to decide who wants to work on it depending of your skills and availabilities. Once the team created, you'll have to choose a product owner, and a scrum master. They will remain until the end of the project.
2. The next step is the product owner will have to work with the stakeholder to define what must be done from a product point of view.
3. Then the development team will have to define a sprint planning, and fill the backlog according to what the stakeholder wants. _Please note that a sprint can't be longer than a month_
4. You start the sprint; a sprint is divided in may tasks
    1. Every morning you start with the Daily Scrum, where you will ask to you and your team. What did I do yesterday? What I will do today? Do I need help form someone else on something?
    2. You take a card in the backlog, and you work on it, until it is done.
    3. You can't work on two tasks of the backlog simultaneously
5. When the sprint ends, you have two meetings to do
    1. Sprint review, where you'll discuss about the work done during the sprint, and re plan the work not done for the next sprint. You'll also present the work to the stakeholders as a __demo__.
    2. Sprint retrospective, you'll reflect on how the past sprint went, and what you can improve or what is good and how to keep it good.
6. Then a new sprint start



## Why Agile & scrum master? / The Benefits

Now that you understand how Agile and Scrum works, I'll explain why we chose that as our new process.
First of all, one of the biggest problem we had is that each time we have a new project, it ends up with some heavy modifications asked by the stakeholders at a very late stage of development, which force our team to sometime redesign the whole project architecture. This naturally lead to a poor quality in the written code, and a long delay for the customer. If I can do an analogy, it's like driving the titanic through icebergs, the boat is slow to react and it take a lot of time for it to react. And it ends up by hitting an iceberg sometime. Instead, we want to have the best reactivity and adaptability to avoid every iceberg. This is what agile method offer us. By doing sprints we are more likely to react rapidly to the new specs of the customer if he needs to adapt the project to something new on the market for example. We have to keep in mind that the software we are developing for our stockholders are done to serve the market and the business, not the opposite. So, it is our responsibility to adapt to the market if needed. And by providing flexibility to the customer, we allow him to react more easily to the need of his market.
Our guideline for that should be __responding to change over following a plan.__
Internally, Agile also helps us as with Scrum retrospectives we have a regular feedback of the work we are doing and what we can improve, and most importantly what are we doing good and how to keep it good.
All those advantages result first in a very good ability to respond quickly to the changes of the customer, and in a second time it allows us to develop better software as we will work __with__ the customer, and not only for the customer. We can think the architecture of the code at an early stage ready to be adapted if the customer needs to, and discuss with him in which way it could be adapted if needed, so we advance the good things to do. Combined to our existing process such as continuous integration on the unit test system, and the Test Dirven Development methodology we are using, we can ensure a very high level of quality. It also helps us a lot if we have to reorient the project in another direction the check for regression.


## How are we going to implement it?

First, you will assist to a few formation days, where we are going to discuss with you properly how works Scrum, describe each role in a Scrum team, and doing a bit of exercises.
We will go in depth about the concept of Scrum, explaining what is a sprint, a Daily Scrum, a retrospective, the sprint review and how to perform a good demo to the customer, and more. We also must adapt our invoice system as we won't charge the customer for once like in the waterfall system, but at the end of every few sprints. Basically, it will be planned before the sprints starting, we will discuss a number of feature the version should have, and what is the most important first. When that version is delivered, we plan a new version and we keep going like that until the software is fully developed.
Also, the contract will have to be adapted to this new method. Indeed, changing to an Agile framework affect all the departments of the company. Now we are working __with__ the customer we will have to be covered in case of behaviour from him if something goes wrong. It is a total new way to work for the customer, and as they are not used to work in that kind of continuous flux of information and solicitation it can be tough for them to work in those conditions and it can lead to major arguments.
After this formation passed for all the staff, and once the new invoice system introduced and the law department adapted our contracts, we will start to change all the rest. The idea is that every time a team finish a project, they will have the possibility to split, and create new teams for the incoming projects. They will have to keep in mind that a team must be multidisciplinary. They also will have to choose a Scrum Master, and a Product Owner.

## Measurement

* we don't want to monitor you or your work, we trust you, but still have metrics you agree with so if failure we can understand why and __improve next time__
    * working software is the primary metric
* Definition of done
* Meeting with the scrum master and the PO



----------------------
----------------------


## References

* http://agilemanifesto.org/iso/en/principles.html
* http://whatis.techtarget.com/definition/scrum-master
* https://www.wikiwand.com/en/Scrum_(software_development)
* http://sogilis.com
