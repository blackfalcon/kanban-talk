# Kanban in the enterprise

#### Roles, responsibilities and delivery 

## A Brief history of Project Management

* Waterfall - everything was planned out ahead of time and executed in an orderly fashion. Change was disruptive and _change management_ was difficult at best. 
* Agile - the antithesis of Waterfall. _adjective_ **able to move quickly and easily.** That's it, nothing more. 
* SCRUM - practice of Agile that was based on a defined body of work that would be delivered within the scope of a sprint. Name was taken from Rugby, metaphor is that 'the team acts as one unit to deliver'
* Kanban - a scheduling system for lean manufacturing and just-in-time manufacturing that was adopted as a just-in-time software delivery model. 

## Kanban vs SCRUM

* Difference between `commit` and `pull` models
* SCRUM locks in a Sprint and work assigned. There are rules of engagement. Short sprints allow for work flexibility, but there is no flexibility within the scope of the sprint.
* If the scope of a story changes within the sprint, that work is ejected and recycled for an upcoming sprint. 
* Kanban is more focused on the work being done, not the work that was committed to. 
* Maximum flexibility within the scope of a sprint.
* As work is completed, new work is simply `pulled` from the backlog. 
* Backlog is groomed in real time for allow for maximum flexibility. 
* Kanban has rules of engagement that ensure that not too much work is being worked on at the same time (WIP Limits). 
* SCRUM defines a `sprint` as a deliverable block of work that fits in time. Kanban defines a `sprint` as a time box in which to measure how much work was delivered. 
* SCRUM maintains work cycles in which work is delivered, agility is achieved via short cycles. 
* Kanban seeks to drive out fear and resistance to change in order to facilitate beneficial change, agility is achieved by iterative process improvements.  

## General practice

* Visualize
* Limit work in progress
* Manage flow
* Make policies explicit
* Implement feedback loops
* Improve collaboratively, evolve experimentally

Complicated software need not apply ... sticky notes will work just fine! 

## Kanban board

the following is an example of a Kanban board wish WIP Limits

| backlog | Selected for Dev | In Dev (3) | Code Review (2) | In test (2) | Deployed |
|---|---|---|---|---|
| Story card | Story card | Story card | Story card | Story card | Story card |
| Story card | Story card | Story card | Story card | Story card | Story card |
| Story card | Story card | Story card |   |   | Story card |
| Story card | Story card |   |   |   | Story card |
| Story card | Story card |   |   |   | Story card |
| Story card | Story card |   |   |   | Story card |
| Story card |   |   |   |   | Story card |

## What makes a good card/story?

* Summary
* Scope
* Done when ...

## Planning

* Short meetings to ensure that devs are aware of stories in the pipeline
* Discussion ensures that points of a good story are addressed and everyone understands
* Scope of work is determined based on what is reusable and what is needed new
* Estimates are rough and based on what is `known` at the time
* Sizing is best estimated in complexity and risk, not time and materials
* Fibonacci number sequence increases complexity with scale, some prefer this method
* Small, Medium, Large is another way of spitballing estimates
* Prior to moving a card from `Selected for Dev` to `In Dev`, the dev should __re-estimate__ the work to ensure that initial estimates are in scope (last chance to alter expectations).

















