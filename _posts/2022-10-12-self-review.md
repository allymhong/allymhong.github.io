---
layout: post
title: "A4: Self-Review + Modifications"
categories: blog
image: project.png
description: My A4 Self-Review, along with Modifications – putting "check yourself before you wreck yourself" into practice.
author: Ally Minju
excerpt: "My A4 Self-Review with Modifications – aka, checking myself before wrecking myself."
---

Welcome to the final piece of A4, where I review myself and update my [Original Fritter Converge](https://allymhong.github.io/blog/2022/10/06/fritter-approaches.html){:target="_blank"} with modifications! Here, I'm putting "check yourself before you wreck yourself" into practice.

## Outline of A4: Self-Review + Modifications

### I. [Self-Review of My Fritter Converge](#i-self-review)

### II. [Summary of Reviews: from Myself, Gianna, and Brandon!](#ii-summary-of-reviews)

### III. [Summary of Modifications to Design](#iii-summary-of-design-modifications)

### IV. Here's my [Updated Fritter Converge](http://allymhong.github.io/blog/2022/10/12/fritter-approaches-updated.html){:target="_blank"}!

## I. Self-Review
_Reviewing my [Original Fritter Converge](https://allymhong.github.io/blog/2022/10/06/fritter-approaches.html){:target="_blank"}._

**A compliment, about General Concept Thoroughness**. Yes, despite A3's Fritter Converge taking me about a total of 30 hours, I enjoyed that I went into the specifics about the metrics and states of how each concept would function – so that my peer reviewers (and future me) would understand how each would practically work. Good job, me, even though it shouldn't have taken as long as it did xD Won't keep on this compliment end too long. (Concept Specificity)

**A criticism, about Fritter Feeds: Bookmark Synchronization. And Bookmarks as a Concept in General**. I was trying to cleverly connect the Bookmarks concept with Fritter Feeds, to emulate the crazy connection between Apple's Trash and general Folders – but I ended up trying to synchronize two concepts that shouldn't be connected. Whereas Apple's Trash only has to tweak one feature by renaming the "Date Added" to "Date Deleted," preserving the basic functionalities of a folder, I'd have to tweak the functionality of features to accommodate a Bookmarks Feed: 
* Remove ranking feature, and only allow Bookmarks Feed to list by latest timestamps of Bookmarks _added_ (rather than by the time Freets have been _posted_)
    * So I'd actually need the Bookmarks Feed to have its own category of ranking
* Wouldn't be able to be accessed on the main Feeds page; would actually need to be addressed through a different route; whereas Hashtags, Citations, and personalized Feeds are all on the main screen

Additionally, when reviewing my pitch, I realized that I was trying to squeeze in the accessibility of Bookmarks to the gist of what Fritter is about. Fritter's main goal is to upgrade user safety in experience; although accessibility and saving Freets would be an addition to this experience, I felt as though the Bookmarks feature was an outlier to the overall goal. Thus, I don't think it's necessary to add to Fritter's Minimally Viable Product (MVP). (Concept Synchronization + Relevancy to the Pitch)

**A speculation, about Reports**. I wonder what kinds of reports can be filed? Will the guidelines be similar to Twitter's? Or will Fritter's have more enforced guidelines, especially with its policy to only allow users 15+ to gain access to post, as well as sensitive content flags having a category of "18+"? Will some reports have harsher consequences than others (forgetting to self-flag for 18+ content, versus posting terroristic comments)? What are the scales?


## II. Summary of Reviews

**My Review.**
* Enjoyed thoroughness of each concept + states
* Bookmarks Feed Synchronization doesn't make as much sense – may make process more complicated; makes more sense to make its own collection – similar to Gianna's suggestion.
    * Also, Bookmarks as a concept isn't as relevant to Fritter's MVP to protect user safety – as Citations (to protect from misinformation), Self-Censorship Flags (protect from sensitive content), and Reports (both + any harmful posts against guidelines) are
* Speculations about Report process: what kinds of Reports can be filed? Similar to Twitter's?
    * Scales on Reports (e.g., reports for terrorism-based content, versus reports for forgetting to self-flag for "18+" content – level of severity for each)

**[Gianna](https://61040-fa22.github.io/portfolio-gtorpey/jekyll/update/2022/10/10/ally-review.html){:target="_blank"}'s Review.**
* Enjoyed Fritter's simple purposes within Report, Citations, and Self-Censorship (Sensitive Content Flag) that ensure user safety
    * Reports can be abused – currently, as long as a Freet is reported, that Freet will automatically be hidden
    * Instead, show that Freets are "Under Review for ____," but don't hide them from Feeds, as users can abuse this concept
* Liked my Upvotes / Downvotes Concept to determine ranking
    * Downvotes allow users to express disagreements privately, unlike Twitter, where it's common to see toxic comments
* Change Turnover Rates for Users that File Reports by going by (# of Legitimate Reports) / (# of Reports a Fritter User has Filed _**that have been reviewed**_)
    * So that the turnover rate doesn't get lowered from reports they may have filed, that haven't been reviewed
* Concept Independence: great for Fritter Feed with Profile, Hashtag, and Citation; but not applicable for Bookmarks; she suggested I create a separate collection for Bookmarks + tighten synchronization
* Questions
    * Will deleting a Freet reduce the # of replies it is related to? What will happen to the link?
    * Clarifications on ReFreeting
        * When ReFreeting, is that ReFreet added to the hashtag or citation feed of the original Freet?
        * Extra State of "Linked Freet" as a reference to the original Freet?
* For Citations Feeds, something as unique as a URL may be difficult to group Freets together; instead, it'd be better to be grouped in a Feed under a more general "topic" (like NFL or U.S. Politics); users can learn more about a specific topic by doing so

**[Brandon](https://61040-fa22.github.io/portfolio-brandontang892/jekyll/update/2022/10/10/a4_ally_hong.html){:target="_blank"}’s Review.**
* Enjoyed the simplicity and utility of the Bookmarks concept for users to look back in time, especially to see if the original claim or prediction turned out to be accurate (for citations)
* Also had speculations about Bookmarks – will users be allowed to save a personal copy of the Freet? so that if users delete the original Freet, those who saved it will be allowed to keep a copy of it? 
    * For accountability and ensuring that users can't easily backtrack from large claims with misinformation – encourages users to think more carefully and thoroughly before they make a post
    * Helps Fritter's goal of reducing misinformation and inappropriate content by holding users accountable to everything they say
* Criticism about Citations – what is a "large claim?"
    * Want a clearer description about how a "large claim" post would be detected in the first place
    * Popularity's not a good enough metric
    * Is the Fritter algorithm explicitly reducing Freets with "large claims" without citations, or will reduced spread of popularity come from citations functionality, where users have a natural suspicion towards posts without citations?


## III. Summary of Design Modifications
* Added "Report" icon to Freets for easier access and on Citations Feeds
    * You can now report Freets without citations for misinformation, if they are making large claims (subjectively)
* Updating Specifications on Why A Freet or User is Reported
    * Adding Gianna's suggestion + adjusting it to show that the "Freet is under review for x" reason; will also allow users to choose to "Show" or "Hide" Freet – similarly to the self-flagged Freets
    * Achieving a balance between hiding unwanted / legitimately reported Freets, but also giving a chance to Freets that were wrongly reported that are still under review
        * But will not show up on any underage users' Feeds
    * It'll only be after review that a Freet would be officially removed
* Changing Turnover Rates for Users that have submitted Reports to (# of Legitimate Reports) / (# of Reports a Fritter User has Filed _**that have been reviewed**_)
* Removal of Concepts for Focus on Fritter User Safety:
    * Removal of "Bookmarks" Concept, and coherently, "Bookmarks Feed" Synchronization from "Fritter Feeds" Concept
        * The synchronization was a bit confusing and unnecessary, as it would functionally operate differently from all other types of Feeds (Citations and Hashtags)
        * Generally, the Bookmarks concept was not a result of the Convergence of Concepts – and does not match the overall theme of protecting Fritter user's safety; although it has utility, I won't include this concept in my MVP
        * Though I thought Brandon's points of how users can check back to see whether or not the posts were proven right or wrong by Citations would've been great, I don't think it's necessarily necessary to accomplish the convergent goals of user safety against misinformation and sensitive content for the MVP; may be a great additional feature if I have time, but not an essential to Fritter
    * Additional Removal of ReFreeting concept, due to concerns for sticking to MVP; ReFreeting is not as relevant to Fritter's user safety promotion; though it would be a nice additional feature later on[^1]
* Updating Rankings to only be by "Popularity" and "Latest" – no longer including "Relevancy" (which was a combination of Popularity and Latest)
    * Updating "Popularity" ranking to no longer be of a count of upvotes/downvotes with _ReFreets_, but a count of upvotes/downvotes with _Replies_.
* Relevant changes to Wireframes: deleting Bookmarks and ReFreets concept, as well as adding "Freet is under review for x"
    * Added "Report" icon to Freets for easier access and on Citations Feeds
* Diving more deeply into Fritter Guidelines (still in the process of drafting fuly) in order to fully enact differences in scales of reviews – updated by case-by-case basis; obviously a user forgetting to self-flag 18+ content will not be reported as severely as a user posting terroristic content
    * For now, for simplicity, reporting options are:
        * Easily report a Freet that is inappropriate on your Feed with the following options: 
        * Misleading Information (must be a Freet without Citations), 
        * Harmful Content Against Guidelines (is not for documentary or educational purposes; excessively gory),
        * Not Flagged Properly,
        * Nude Content Against Guidelines (Fritter does not allow for full nudity; only hinted content);
        * Threatening Language,
        * Other

<!-- ## NOTE: COME BACK TO THIS
* Citations Groupings: maybe instead of by specific URLs (which may amount in the creation of numerous Feeds), grouping by the base of the URL? For example, grouping all citations by NYTimes together? Or following with Gianna's suggestion of Topics
    * Adding Topics tags would make it easier to focus on what kinds of Citations and Feeds would result
    * But similar to Google Scholarly Citations, decided to keep it the same -->


## IV. Access the [Updated Fritter Converge](http://allymhong.github.io/blog/2022/10/12/fritter-approaches-updated.html){:target="_blank"} with all of the above modifications!

––––

[^1]: Though, if I had a ReFreet concept, I would've stuck with Twitter's similar takes of two options: direct reposts, and quoted reposts, which means (1) User that ReFreets directly will just post the same Tweet to their Feed; but these Freets would've been denoted as ReFreeted by said user; (2) User that ReFreets by quoting it would post their Freet to their Feed as an embed; and said user would've been allowed to write content and add additional on their part of the Freet. Either way, ReFreets would not have contributed to the originally mentioned Hashtag or Citation Feeds, unless the ReFreet was a quoted ReFreet directly including the mentioned Hashtag or Citation again onto the added Freet.