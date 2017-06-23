# How to impress your stakeholders with an outstanding demonstration

Each ceremony is a good oportunity to show off the most recent development of the product. The review is the time to make each stakeholder catch up with the latest improvements of their investment.

## What is a demonstration ?

A demonstration is a privileged time shared between the scrum team and the stakeholders. It shall last no longer than 15 minutes.

The stakeholders are not following on a daily basis the evolution of the product. They want to see the result of your work. The demonstration shows the current state of the product and what's remaining to be developped. 
It allows the stakeholders to:
* acknowledge the success of the past sprint.
* introduce the focal point of the developments to be undertaken during the next sprint. 

It is the perfect introduction to a ceremony's review.

## Prepare your demonstration

A good demonstration is a prepared demonstration.

#### What you absolutely want to avoid during your demonstration:
* A glitch: everything shall work as planned
* An internet outage or a malfunctionning server: it will delay your review, and consequently will shift your ceremony's end
* Off-handed, uninterested, distracted stakeholders: this demonstration is for them, and for them only

In order to avoid previously mentionned situations, the following steps will maximize your chances of succes.

#### Required material to run a demonstration:
* **Your stakeholders**, especially your sponsor.
* **Your application running**. Avoid local environment (too slow) and production (you can't control production data and don't want to interfere with it)
* **Your computer**. You need your client's focus, their don't need their computer.
* **A large screen** or a projector to display your demonstration onto.

#### Preparation of your demonstration
* **You need to know what to show:** check when your sponsor was present at a demo before this one. Gather all developments carried out during this period of time.
* **You need to prepare your computer:** preload the application in one of your web browser tab. Turn on the *Do not disturb* mode of your notification center.
* **You need to master the data you will use to demonstrate:** add the entities you may need for the purpose of the demonstration to your environment database the day before.
* **You need to master the behavior of your application:** if possible, unwind your full demonstration beforehand to ensure no glitch will surprize you during the real thing.

## Run your demonstration

### Who should present ?

Ideally, **a developper should lead the demonstration**.
* Scrum master may struggle preparing the working environment for the demonstration
* Architects might not be aware of the full range of the features developped during the sprint, as they are commited to multiple projects at once

On AssuranceVie.com, we suffered from a distracted sponsor during one of our review. It led to a change of sprint goal during the sprint after the sponsor realized we were not in line with his idea of the product's priority.
Our action was to **let the sponsor run a prepared demonstration scenario** during the next review, ensuring his full attention for the rest of the review.

### How to present ?

* The **guide line of your demonstration** is the features you identified during your preparation. 

* **Emphasize the added value of your work:** insist on the weak points the product had before the developments, and how beneficial your team is for your client's product.

* **Don't use shortcut during your demonstration.** The persons that will use your product may not have your skills. During your demonstration, you are no longer a developper. **You endorse the role of the final user of the product, act accordingly.**
They will feel outsided if they can't reproduce your exact gestures. Don't skip any part of the process you may assume obvious. You are familiar with the new features of the product, your stakeholders aren't.

1. Do not modify the url by hand (changing an id or any other parameter).
2. Do not use your url's history. Show how to get to your demonstration from the application starting point.
3. Do not use form auto-fillers

* **Describe what you do as you're doing it**. You need to present both visually and orally to maximize your sponsor's attention.

* **Show only what needs to be demonstrated**. Do not quit the demonstration. One of your collegue can use his computer to write down sponsor comment or next sprint tickets. Don't excessively move your mouse or click anywhere. Turn off your notifications before the review. 

* When you need to fill in fake data to demonstrate your feature, **use stakeholders related fake data**. For exemple, if you need to add a new customer, act as if your new customer was your sponsor. Saying his name out loud will catch his attention.

* **Increase the value of the MEP** (if any was done during the sprint) at the end of your demonstration, concluding that all features shown during the demonstration are **now in production**. The value you added is already available to your client's final user.

### How to conclude ?

The demonstration is the starting point of the discussion regarding development to be undertaken during the next sprint. This discussion may already have started during the demonstration (uncomplete processes, slight modifications required by the sponsor).

* **Ask your sponsors if they have questions/remarks**
* **Switch back to trello to start the review**

## FAQ

#### The current development is mainly technical, I have nothing to show to my sponsor. How should I run my demonstration ?

On InDx, a SG project, we were opening a REST API dedicated to other SG applications during 6 sprints. We used different supports to demonstrate our work:
* Our MEP flowchart, particular to SG projects, allowed us to show off the accomplished steps and the remaining ones in order to ensure the application would be in production before the end of the project. Use color to identify the newly checked items.
* We built diagrams showing the API workflow, emphazing which part of the workflow was not developed before the sprint.
* We used Postman to simulate application calls to the API and show the received answer.
