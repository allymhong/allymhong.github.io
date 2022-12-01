---
layout: post
title: "A6: Fritter Frontend!"
categories: blog
image: project.png
description: Exploring Frontend Principles on Wireframe + What I've Done So Far.
author: Ally Minju
excerpt: "Exploring Frontend Principles on Wireframe + What I've Done So Far."
---

Before jumping into any backend, let's first throwback to the [wireframes I drafted in A4: my self-review](https://allymhong.github.io/blog/2022/10/12/fritter-approaches-updated.html#iv-wireframes) - and explore what they mean in-depth through heuristic evaluation.

**Heuristic Evaluation**.
*Usability Criteria*: capture the broad overall goals that your visual and interactive designs might be trying to satisfy – *Pleasantness* and *Learnability*
* With Fritter’s wireframes being basically based off of Twitter’s sleek design, *Pleasantness* of the design is high, and I expect that *Learnability* will be a lot easier for people who have used Twitter before – though I have heard that navigating Twitter is not as easy to navigate in comparison to other social media.
    * To further support *Pleasantness*, the color schemes all lign up with each other, and the sleek deisgn is light on the eyes – and allows for users to scroll down on the captivating interface.
* But because Fritter is a condensed, focused version of Twitter (with its 4-5 main concepts within its Minimally Viable Product), I think that Fritter would be easier to navigate, as I’ve had difficulty navigating and understanding the amalgam of Twitter’s features and concepts within concepts.
    * Although self-flagging and upvoting are easy to understand, I think users may be confused by citations, which is denoted by the Quotations mark. I think to help with *learnability*, a tutorial would be ideal. 
    * Same with the Citations feed – a demonstration would be helpful, although it follows the same layout as a Hashtag feed.

*Physical Heuristics*: describe characteristics about the user interface that affect how users might operate it – *Mapping* and *Gestalt Principles*
* For physical heuristics, I decided to focus on modularity, as this theme of design has heavily impacted my perspective on software design throughout 6.1040. I believe that the mapping of the interface elements match their functions – I haven’t matched the creation of an account along with the log-in, but to be in accordance with mapping, I would do so by including all User conceptual items with each of the relevant inputs (for example, an input form with the month, day, and year for Birthdays, to make it more intuitive for the user). With what I have so far, I included an "Upvote" button with an upvote icon (up arrow emoji) – that should be intuitive with most people who have used social media before – but once again, a tutorial may be required for those who are newer to the Interwebs.
* I think that the *Gestalt Principles* are pretty intuitive for a lot of users who have used social media before – which is the main target audience, as Fritter is the place for users who are upset with today's social media (with misinformation, unflagged sensitive content, and underage users being exposed to such content), so I wanted to make the mapping as close to existing social media. 
    * For ease on Fritter backend, friends and TAs have recommended that I made Citations and selfFlagging for Freets its own Schema for modularity. I ended up doing so for Citations, due to the information it contains, but I prioritized the Gestalt Principles in design – these Citations and selfFlagging principles are inherently tied to the Freets, so I wanted to make sure that the input process would be included during the drafting process. 
    * Hence, I created the checkbox process. And allowed selfFlagging to be a parameter within Freet's Schema. As for Citations, I would post them along with the Freet – so that users will not have to add Citations to their Freets after the fact. I honestly pondered these principles very deeply and entered into thought loops, and tried to take notes about the processes. I believe that grouping relevant concepts together – while keeping modularity (as the wireframes show, that self-Flagging/censorship is within a Freet draft, but still within its own box and a checkbox for simple parsing), as well as the Citations under the Quotations icon – though I think this section could be even more intuitive, not only through tutorials, but more guidance for users – possibly even suggestions of Citations, as this concept is an invention.


*Linguistic Level*: describe cultural conventions and norms about the interface – *Consistency* and *Recognition vs. recall*.
* 


**Vue.js Frontend Minimally Viable Product (MVP)**
*Btw... we ran out of time :'(*
Fritter's first release with Vue.js Frontend is finally here! [Check out our Minimally Viable Product here](https://fritter-frontend-bay.vercel.app/#/)!

* [And here's my GitHub repo README.md file with all the API routing!](https://github.com/allymhong/fritter-backend/blob/main/README.md)


Sadly couldn't get to desining more of the frontend, which is normally my favorite part of coding! Thank you so much for your hard work and grading through! :D