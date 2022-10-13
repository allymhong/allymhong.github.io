---
layout: post
title: "A4: Fritter Approaches [Updated] :D"
categories: blog
image: project.png
description: Tired of the spread of misinformation? What about seeing sensitive content on your feed without any warning? Explore what Fritter has to offer, in convergence!
author: Ally Minju
excerpt: "Tired of the spread of misinformation? What about seeing sensitive content on your feed without any warning? Explore what Fritter has to offer, in convergence!"
---

The long awaited Fritter, the Fret-Free Twitter, is near, so get hype! Explore Fritter's design in *convergence*~. Here, I pitch Fritter; delve into concepts included within Fritter's Minimally Viable Product (MVP); discuss Synchronizations on how concepts are linked together, usually to produce automation; cover essential views and interactions through Wireframes; and finally, address Tradeoffs within Fritter.

Below is an outline of what I cover throughout Fritter Converge!

## Outline of Fritter Converge

### I. [See Our Pitch!](#i-pitch)

### II [Fritter's Convergent Concepts](#ii-fritter-convergent-concepts)

1. [Freet (Post). [Adjusted]](#1-freet-post-adjusted)
2. [Follow.](#2-follow)
3. [Fritter Feeds. [Adjusted]](#3-fritter-feeds-adjusted)
4. [User.](#4-user)
5. [Citations. [Invention]](#5-citations-invention)
6. [Self-Censorship (Sensitive Content Flag). [Adjusted]](#6-self-censorship-sensitive-content-flag-adjusted)
7. [Report.](#7-report)
8. [Upvote / Downvote. [Adopted]](#8-upvote--downvote-adopted)


### III. [Our Synchronizations](#iii-synchronizations)

### IV. [View Wireframes](#iv-wireframes)

### V. [Our Tradeoffs](#v-tradeoffs)


# I. Pitch
*Tired of the spread of misinformation? What about seeing sensitive content on your feed with no warning? Worried about the youth seeing and being exposed to such graphic content?*

No need to fear. Fritter is near; it is a revolutionary social media platform that allows users to stay connected with each other and authentically communicate news, ideas, and thoughts to the world – with minimalized misinformation and properly flagged sensitive content.

Fritter is the Fret-Free app that successfully tackles Twitter’s biggest issues with the lack of information transparency and user safety.

How? We open the doors for our users to:
* easily cite their own Freets’ source of information; and
* efficiently censor their own Freets, protecting users who filter out sensitive content and warning users who don’t;
    * all flagged content will not be able to be accessed by underage users; and
    * a specific censor for 18+ was added, which specifically is a filter that may not be sensitive for 18+ users, but will be for underage users.

Fritter is Fret-Free for a community of trusted users who value the transparency, quality, and safety of information in Freets. 


# II. Fritter Convergent Concepts

## 1. Freet (Post). [Adjusted]
_**Purpose**_. Publish a post with text (up to 280 characters) and/or media (photos or videos, limited to 5 total) and communicate with other Fritter users. Text may include hashtags, an adopted concept from Twitter and most of social media – which self-tags the Freet.

_**Operating Principle**_. When a user publishes a Freet, it is associated with that user as the author, as well as any hashtags and citations.

_**States**_.
* Set of Freets posted by user who posted Freet
* Timestamps of each Freet posted
* Counts of Upvotes, Downvotes, and Replies
* Linked Hashtags
* Linked Citations
* Status of Sensitive Content Flag (can be flagged for Nudity, Violence, Sensitive, Language, and/or 18+)
* Pertaining Freet Replies…
    * If the Freet is a reply to another Freet: the parent Freet
    * If the Freet has replies from other Freets: the children Freets
* Display Status: Active, Censored, or Hidden
* Report Status, when Freet is reported by Fritter users (status can be null, needing review, undergoing review, or reviewed)
    * Count of total Reports received

_**Actions**_.
* Create a Freet: user u creates their own Freet i
    * add Freet i to set of Freets created by user u
    * add Freet i to set of Freets with any included hashtags and citations
    * if user u self-censored Freet i with a sensitive content flag, add a layer of warning to warn users with specific type of flag
    * post Freet i on relevant Fritter Feeds:
        * post Freet i on the user u’s own Feed and profile
        * post Freet i on each of user u’s follower’s Feed
        * if there are citations, post Freet i on each citation’s Feed
        * if there are hashtags, post Freet i on each hashtag’s Feed
        exception: if Freet i is flagged ~AT ALL~ (not just limited to the 18+ flag), and the viewer of the Freet is under 18 years old, the Freet will not be posted to the underage viewer’s Feed.
    * update the ranking of Freets on all relevant Fritter Feeds, sorted by either the latest Freet using timestamps, or ranking by combination of counts of upvotes/downvotes and Replies
* Delete a Freet: user u deletes their own Freet j
    * discard Freet j from set of posts associated with user u and user u’s profile, which synchronously deletes Freet j from all associated Feeds (to followers, hashtags, and citations)
* Reply to Freet: user u replies to Freet m with Freet n
    * similar to the process of “Create a Freet” for Freet n, except that Freet m and Freet n are now connected. Freet Replies may be viewed when user clicks on either Freet
        * Freet m is Freet n’s parent
        * Freet n is Freet m’s child
    * +1 to the Reply count for Freet m


## 2. Follow.
_**Purpose**_. Allows users to stay updated with the Freets of other users, hashtags, or citations. Also allows users to have an accessible list of who and what they are updated with on their profile.

_**Operating Principle**_. When a user follows another user, hashtag, or citation, the user now is a follower of that other user, hashtag, or citation. All the Freets from what the user follows is now integrated into the user’s personalized homepage Fritter Feed.

_**States**_.
* Following or not following (another user, citation, or hashtag)
* Followed or not followed (by another user)

_**Actions**_.
* Follow: user u follows user i; hashtag j; citation k
    * user u’s “Following” list on their own profile updates to include user i; hashtag j; citation k
        * user u: +1 to “Following” count
        * user i; hashtag j; citation k: +1 to “Followers” count
    * user i’s “Followers” list on their own profile updates to include user u
    * user u’s homepage Fritter Feed updates with Freets from user i; Freets with hashtag j; Freets with citation k
* Unfollow: user u unfollows user i; hashtag j; citation k
    * user u’s “Following” list on their own profile updates to remove user i; hashtag j; citation k
        * user u: -1 to “Following” count
        * user i; hashtag j; citation k: -1 to “Followers” count
    * user i’s “Followers” list on their own profile updates to remove user u
    * user u’s homepage Fritter Feed no longer includes and will remove any Freets from user i; Freets with hashtag j; Freets with citation k


## 3. Fritter Feeds. [Adjusted]
_**Purpose**_. Feeds are the collection of relevant Freets, for easy-viewing for users. Users have a main Fritter Feed on their homepage with an amalgam of other users, hashtags, and citations that they follow.
* Every user has their own Feed listing their own Freets on their profile.
* Every existing hashtag has its own Feed of associated Freets.
* Every existing citation has its own Feed of associated Freets.


_**Operating Principle**_. Users may view their main Fritter Feed, which includes all the latest and/or most popular Freets from their following. Users may explore Feeds associated with specific hashtags, citations, and other users (through other users’ profiles).


_**States**_.
* The last time a user updated their Feed, or how much time has elapsed (as the Feed updates on its own – for a default of 5 minutes, which may be changed later in Settings)
* Ranking Freets:
    * By order of timestamps
    * By number of upvotes/downvotes and Replies
* The set of posts associated with specific user profiles, hashtags, and citations


_**Actions: inherently synchronized.**_.
Update Feed: when user u refreshes a Feed or views a Feed for the first time in >5 minutes, the Feed will update with ranking dependent on:

If Feed is personalized Feed for user, or for specific users profiles, hashtags, citations:
* Ranking for these Feeds is determined by “Popularity” (determined by counts of Upvotes/Downvotes with Replies) and “Latest” (only by timestamps)
* Feed will stay updated with associated users, hashtags, and citations with this refresh, as well as who the user has followed and unfollowed
* Feed will also stay updated with report status of specific Freets and Fritter users – if the statuses are “needing review” or “under review,” these Freets and Fritter users will be censored in Feeds when updated
    * As well as “display” status


## 4. User.
_**Purpose**_. Identification, security, and gathering information in one account. If anyone wants to post to Fritter, or add their own upvote/downvote, etc. – they must first create an account; when creating an account, the person must log in their information (name, username, biography) and enact 2-Factor authentication for security. Then, all published Freets by said person will be gathered by their Fritter account. Profile Feeds are then able to be created.


_**Operating Principle**_. When someone creates a Fritter User, they now have an official Fritter account used for identification and gathering of posted data in one place. Other Users may identify each other through this concept. Users have unique usernames and are able to interact on Freets through various ways – Upvote/Downvote and Report; post their own Freets, which will be linked on their profiles; as well as follow or unfollow other users, hashtags, and citations.


_**States**_.
* A User’s Profile will contain the following:
    * Customizable Name
    * Username (must be unique – essentially User ID)
    * Biography (Optional)
    * Age (Optionally Displayed)
    * User’s Feed: a list of all the Freets a User has posted
* Date of Birth and Password for Security
    * If User is under 18 years old, User may not follow flagged (for sensitive content) users or see any censored posts
* User Phone Number and/or Email for 2-Factor-Authentication
* Following List: User may follow other users, hashtags, and citations
* Followers List: a list of other users that follow the User
* _#_ of Reports Received, # of Reports Given, # of Legitimate Reports Given
* Self-Censorship Flag Status of Account


_**Actions**_.
* Create New User account
    * Creates Name, Username, Biography (Optionally), enters Date of Birth, Password, and Phone Number and/or Email for 2-Factor-Authentication
* Delete User account
    * Deletes all above information, as well as User profile and Freets tied to user – can no longer be accessed or viewed by other Users or the public
* Edit User Information: Name, Username, Biography, Password, Phone Number or Email for verification
    * Cannot edit Date of Birth
* Follow/Unfollow: can follow/unfollow another User, hashtag, or citation of interest
    * +1/-1 from Following List
* Self-flag User: can censor User’s own account



## 5. Citations. [Invention]
_**Purpose**_. To prevent the spread of misinformation, users will now be able to cite their own sources (must be web-based; in other words, source must have a URL) within their Freet. With Freets making big claims, and prone to go viral and be shared – they may be less likely to be shared if there are no valid citations. The more reputable sources are provided within a Freet, the more likely that the information provided is reputable as well.


_**Operating Principle**_. When a Fritter User posts a Freet with large claims, they may cite their sources, which are solely web-based (must have a URL), to back up their claims. If the User wishes to cite non-web-based media, the User can link to the nearest URL that the source has; for example, if the User wants to cite a book, then the User must provide a URL where you can view or purchase the book. When a Fritter User sees a Freet with large claims, without any citations (or no reputable citations), then the Freet will more likely be reported as misinformation.


_**States**_.
* List of Citations (can be none; limit is z number of citations)
* Each Citation has a Feed of Freets that have cited it
    * And a count of users that have cited it
* Each Citation has a list and count of users that follow it
* Each Citation has a report status


_**Actions**_.
* Add Citation i: Users posting Freets may add Citation i to back up any claims within a Freet
    * Freet will be linked to Citation i’s Feed
    * +1 for Citation i’s total count of Freets
* Remove Citation i: 
    * Freet will be removed from Citation i’s Feed
    * -1 for Citation i’s total count of Freets
* Report Citation i: User may report Citation i, and its status will be updated to “needing review”
    * All Freets that link Citation i will still be visible – but Citation i will be flagged as “needing review,” to let users be aware of its status and as a warning
* Follow/Unfollow Citation: Users may follow or unfollow a citation’s feed



## 6. Self-Censorship (Sensitive Content Flag). [Adjusted]

_**Purpose**_. To prevent the spread of sensitive content in Feeds without warning (and the spread of all sensitive content to users under 18), the sensitive content flag has been adjusted to be easily accessible when users create a Freet. Freets may be censored for language, generally 18+ content, graphic violence, nudity, and generally sensitive content. Users may flag their whole profiles to automatically have all of their Freets flagged, and their profiles unavailable to view for underage Fritter users – and censored for all other Fritter users.


_**Operating Principle**_. When a user creates a Freet with sensitive content, or if the Freet contains foul language, or any of the above valid reasons for flagging, the user may easily flag their own content. Once their Freet is posted, it will either show up with a warning wall, blurring the contents of their Freet to relevant Feeds; users that are underage will automatically not be able to access their content. A user viewing a flagged Freet can either view the Freet, or hide the Freet from the Feed they are currently viewing. When a user self-censors their own profile, all their Freets will be automatically flagged and will not be shown for underage users.


_**States**_.
* Self-flagged, or not flagged (applies to accounts and Freets)
* Flagging Options: 
    * Language
    * 18+ (may sound redundant, but this is for content that is “adult,” such as an adult joke – but does not contain any nudity, particularly sensitive content, bad language, or graphic violence)
    * Graphic Violence
    * Nudity
    * Generally Sensitive Content (may include triggering stories or 
* Flag Status of Photos or Videos within a Freet, or the text of a Freet.


_**Actions**_.
* Self-flag Freet with Flagging options before or after posting.
* Self-flag user profile with Flagging options to censor all Freets.
* Uncensor: view the contents of censored Freet.
* Hide: hide the censored Freet from current view of Feed.


## 7. Report.
_**Purpose**_. Flag a Freet, Fritter User, or citation with violent, sexual, or graphic content (including photos, videos, and language) without proper self-flagging or censorship; even with proper censorship, the purpose of the Report feature is to flag media, Fritter users, or linked citations that go against Fritter guidelines. We don’t allow Freets with full exposure to nudity, non-educational (non-documentary based) violent media, harassment-based or terroristic content, and directed abusive content that threatens the safety of our users.


_**Operating Principle**_. When a user reports a Freet, Fritter User, or citation, there are several options for why the Freet may be reported, including failing to censor itself for sensitive content. The status of the Freet will now be marked as “Needing Review.”



_**States**_.
* Report Freet, Fritter User, or Citation; or Already Reported (can be “needing review,” “under review,” and “reviewed”)
* Counts
    * _#_ of Reports a Freet, Fritter User, or Citation has received
    * _#_ of Reports a Fritter User has filed
    * _#_ of Reports were legitimate reports (after team reviews them)[^1]
* Turnover Rate: (# of Legitimate Reports) / (# of Reports a Fritter User has Filed _**that have been reviewed**_)
    * Counting this in order to filter out users who spam or mass report Freets


_**Actions**_.
* Report a Freet: user u reports Freet j, posted by user w
    * +1 to user w’s # of Reports received
    * +1 to user u’s # of Reports filed
    * user u will have the option to block user w’s future Freets from showing up on any of user u’s Feeds; and disallow user w from viewing user u’s future Freets and profiles
* Report a Fritter user: user u reports user w
    * +1 to user w’s # of Reports received
    * +1 to user u’s # of Reports filed
    * user u will have the option to block user w’s future Freets from showing up on any of user u’s Feeds; and disallow user w from viewing user u’s future Freets and profiles
* Report a Fritter Citation: user u reports citation i
    * +1 to citation i’s # of Reports received
    * +1 to user u’s # of Reports filed
    * user u will have the option to block future Freets linking citation i

**“Freet,” “Report,” and “Fritter Feed” Synchronizations**
* Censor Freet from all relevant Feeds and the poster’s User Profile once placed “needing review” or  “under review”
    * Once a Freet receives a review, it will automatically be censored, just as self-flagged Freets are, but with the reason that they are being reviewed; but it will not be removed from the set of relevant Freets within a Feed
    * Freet display status will now be "censored"

_System may be prone to change_[^2]
* Delete Freet from all relevant Feeds and User Profile, when # of Freet Reports Received reaches x
* Disabling Citation from Future Use: when # of Reports of Citation reaches a certain threshold, or if Fritter team deems Citation as going against community guidelines, it can no longer be cited
    * Mainly for sensitive content, or links causing viruses, or compromising security
    * Notes specific citation on linked Freets as “under review,” for users to see
* Suspension of Fritter User Access: user u’s # of Reports Received reaches y
    * User may not access account for some amount of time
* Warning to Fritter User About Deletion: user u had been suspended previously, and received more reports (that is close to the maximum number of reports received, z)
* Deletion of Fritter User Access: user u reaches # of z Reports Received

## 8. Upvote / Downvote. [Adopted]
_**Purpose**_. Rate a Freet with an “Upvote,” through which the user generally expresses approval, and/or a “yes;” or with a “Downvote,” through which the user generally expresses disapproval, and/or a “no.”

_**Operating Principle**_. When a user Upvotes a Freet, the user expresses “+1” count of approval and/or “yes,” and the Freet is boosted upon ranking systems within Feeds for better viewing. When a User Downvotes a Freet, the user expresses “-1” count of approval, and/or “yes.” A Freet may only be Upvoted, Downvoted, or Un-voted (in which the user cancels their vote) – a user may not do all at once.

_**States**_.
* Upvoted, Downvoted, Unvoted.

_**Actions**_.
* Upvote a Freet
* Downvote a Freet
* Unvote a Freet (by tapping on the same icon that is highlighted, or selected at that moment)

Note: The Upvote / Downvote / Unvote metrics will affect the ranking of all Feeds.

# III. Synchronizations

Explicit Synchronizations mentioned:
* under the actions of [Concept (3): Fritter Feeds](#3-fritter-feeds-adjusted), and [Concept (7): Report](#7-report).

In summary: when users the report content to report a Freet, Fritter user, or citation, the view of Fritter Feeds are affected. 
* Freets “under review” will be censored from Feeds and will show the reason it's being filtered; 
* Fritter users “under review” are prone to get suspended, warned, or deleted from Fritter as a whole; and 
* Citations are displayed to be “under review,” and be censored with warnings from User’s personalized Feeds.

Posting Freets updates a user’s Feed; posting Freets with citations and/or hashtags updates both citation and hashtag feeds. 

Upvoting and downvoting affect the ranking of Fritter Feeds.

Censoring Freets also affects what is displayed on certain User’s Feeds (removed from underage Feeds), and how they are displayed (displayed with relevant warning).



# IV. Wireframes

Exploring a few screenshots from my wireframes:

## Adding Citations to a Freet
Add citations to your Freet to back up any claims by tapping on the "Citations" icon (with quotations) and adding your URL to your site-ation.
> ![Alt](/assets/images/fritter_converge/create_citations.png)

## Main Page, the Personalized Feed
This is the main personalized feed, dependent on users, hashtags, and citations you may follow. You can see here the first post uses #hashtags, and the second has the citation from above (in purple). If you tap on the purple link, it will lead you to the URL. 

As written on the first Freet, you can explore the #hashtag feed by tapping on the hashtag; and you can explore the citation feeds by tapping on "Cited by 2 others..." below the purple citation itself. 
> ![Alt](/assets/images/fritter_converge_updated/home_page.png)


## Explore Citations Feed
Explore all other Freets that have linked the same citation. You can access this page through any Freet with the same citation, or by searching for the URL or citation name (by the title of the web-page and author, if applicable). You can also report the citation if it is inappropriate.
> ![Alt](/assets/images/fritter_converge_updated/citation_feed.png)

## Explore Hashtag Feed
Similarly, explore all Freets posted with a specific hashtag in the hashtag feed.
> ![Alt](/assets/images/fritter_converge_updated/hashtag_feed.png)

## Creating a Freet with a Self-Censorship Flag
Easily self-censor your Freets with the self-censorship flag icon on the bar above the keyboard. You can select what to flag the Freet for; in this case, the Freet contains vulgar language.
> ![Alt](/assets/images/fritter_converge/create_self_flag.png)

## Example of a Censored Freet on a Feed
Here is the Freet from above that we self-flagged for language. As you can see, the Freet is visibly covered and noted to have been flagged for Language! This will warn users, and give users the option to Hide the Freet from the Feed they're currently viewing, or Show the Freet's contents.
> ![Alt](/assets/images/fritter_converge_updated/hidden_flagged_freet.png)

## Example of Reporting Freet on a Feed
Easily report a Freet that is inappropriate on your Feed with the following options: 
* Misleading Information (must be a Freet without Citations), 
* Harmful Content Against Guidelines (is not for documentary or educational purposes; excessively gory),
* Not Flagged Properly,
* Nude Content Against Guidelines (Fritter does not allow for full nudity; only relevant for photos/video content);
* Threatening Language,
* Other

> ![Alt](/assets/images/fritter_converge_updated/report_freet.png)

## Example of Viewing Freet Under Review
Here is a Freet that has been reported. You can choose to show or hide the Freet with the fair warning of the report. Reported Freets will not show up on underage users' personalized Feeds.
> ![Alt](/assets/images/fritter_converge_updated/view_reported_freet.png)

Journey through more of my wireframes, starting with the creation of a post with Citations [at this Figma link here](https://www.figma.com/file/FyGYlfh5yL0PMIZxXcBXn1/Ally's-Updated-Wireframes?node-id=4%3A1224){:target="_blank"}; or you can also view the embed of all the files below:
<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FFyGYlfh5yL0PMIZxXcBXn1%2FAlly's-Updated-Wireframes%3Fnode-id%3D4%253A1224" allowfullscreen></iframe>


Within this wireframe, I've included:
* Various Feeds:
    * Personalized Main Home Feed
    * Citations Feed
    * Hashtag Feed
* Composing and Viewing a Freet with Citations, and
* Composing and Viewing a Freet with Self-Censorship Flagging (for Language, in this case).



# V. Tradeoffs

**Site-ations.** Fritter’s Citations feature will only allow for web-based sources (must have a URL). But what about resources not available on the web, such as books, journals, paintings, and other media without their contents available for viewing online? For this scenario, to allow for one format of citations – and easier verification – I traded the spectrum of available citations for efficiency, accessibility, and convenience for web scraping. Once the Citations feature collects data and feedback from launching Fritter as an MVP, depending on what Users say and experience – the Fritter team may add to the list of possible forms of citations.

**Two Extremes: Risking Safety? Or Overly Censored Media?** To improve upon Twitter’s lack of moderation of sensitive content, I tried to strike the right balance between ultimate censorship and freedom of speech. But what options will fit best? And what about addressing concerns from social media users like one of my interviewees, [Chiara](/../blog/2022/09/19/twitter-to-fritter.html#interview-chiara){:target="_blank"}, of protecting the youth from sensitive and vulgar content? By limiting underage users from seeing *any* self-flagged censored content, including language, I traded off Fritter’s youth’s freedom of speech and viewing of content, for robust user safety and trust in Fritter’s platform by adults who are wary of social media platforms. I hope to gain more feedback to achieve an even better balance, but Fritter’s priorities are user safety and building trust amongst users, over freer expression.


**Privatizing Upvotes/Downvotes.** An essential Twitter feature is the “Likes” concept, which automatically bookmarks and displays all Tweets that a user has liked, on their user profile. Not only that, users are able to see who reacted to their Tweets. Fritter is prioritizing user privacy and anonymity in voting for Freets, by disabling the “Likes” feature – and adopting a more Reddit-like approach to upvoting and downvoting Freets. We are trading off user-tied Likes to show support and agreement for the hope of more unbiased voting systems, untied to the User’s image. This change in feature is to prevent pressuring users from reacting, privatize interests, and prevent hopping on trends of virtue signaling (which is disingenuous).




_Footnotes._

[^1]: may be automated with new metrics, rather than reviewed by a team on a case-by-case basis; MVP (Minimally Viable Product) may start off this way, though.

[^2]: system of determining whether or not a Fritter User will be suspended, warned, or deleted may differ and change to be based on metrics of volume, how popular the user is, and consider the turnover rates of users filing the reports, etc. In the process of brainstorming this process + studying reporting processes of other social media platforms.