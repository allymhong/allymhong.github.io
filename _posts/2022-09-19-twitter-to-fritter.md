---
layout: post
title: "A1: Twitter to Fritter"
categories: blog
image: project.png
description: This is my first blog post.
author: Ally Minju
excerpt: "An analysis + critique of Twitter, featuring interviews with social media users from Los Angeles, through the lens of Value Sensitive Design (VSD). Learning from Twitter's benefits and downfalls in creating Fritter: a Fret-Free Twitter :)"
---

Hey all~ Welcome to my first blog post. If you haven't met me, I'm Ally Minju! [You can check out my official introduction](/about/){:target="_blank"} (it's short and sweet). But for this post, all you need to know is that I'm a third-year MIT undergrad in Software Studio (6.1040 / 6.170) – and I'm here to share:
- my analysis + critique of Twitter
- intriguing Twitter stories from my interviews with social media users from Los Angeles

through the lens of Value Sensitive Design (VSD): a systematic, principled approach to designing tech centered around human experiences and values. 

Learning about Twitter's strengths and shortcomings from personal experience, press media, and interviewing users will help me think about what I'd need in creating *Fritter: a Fret-Free Twitter*! :)

## Outline of Analysis

### I. [Value Sensitive Design (VSD)](#value-sensitive-design-vsd)

* [Stakeholders](#stakeholders)
    * Indirect Stakeholders
    * Non-targeted Use
* [Time](#time)
    * Adaptation
    * Sustained Friendships
* [Pervasiveness](#pervasiveness)
    * Crossing National Boundaries
    * Widespread Use
* [Values](#values)
    * Value Tensions
    * User Experience of Values


### II. [Interviews](#interviews)
* [Planning](#planning)
    * Choosing Interviewees
    * Interview Questions + Notes
* [Interview: Chiara](#interview-chiara)
    * Summary
    * Synthesis
* [Interview: Gideon](#interview-gideon)
    * Summary
    * Synthesis


# I. Value Sensitive Design (VSD)

## Stakeholders
_**Indirect Stakeholders.**_ There are multiple roles in which people will be affected by Twitter without having directly interacted with it. Here are three key _indirect_ stakeholder roles and their concerns:
1. The Tweeted – those who are the subject of Tweets are inevitably affected, as their information is now shared and posted to a public or private following. Indirect stakeholders include *anyone* Tweeted about – and it's especially concerning for those whose personal information is posted without permission (aka ["doxxed"](https://help.twitter.com/en/rules-and-policies/personal-information){:target="_blank"}). I've witnessed artists whose albums/songs were leaked, as well as peers who have been negatively "Subtweeted" about by others (mostly in non-discreet ways, often resulting in [cyber-bullying](https://www.verywellfamily.com/subtweeting-and-vaguebooking-what-parents-need-to-know-460585){:target="_blank"}). Below is an (Urban) dictionary example of a Subtweet:

    ![Alt](/assets/images/subtweeting.jpg)


2. Constituents of Governments, Representatives, and Elected Officials on Twitter – major announcements, newsbreaks, and alerts by governmental Twitter accounts affect constituents, whether they are direct or indirect Twitter users. Most of us are all too familiar with how Trump's Tweets would shift the state of [the stock market](https://www.forbes.com/sites/chuckjones/2019/08/24/unpacking-trumps-tweets-about-the-fed-and-china/?sh=4d95dbb18b6e){:target="_blank"}, domestic affairs, and relationships with different nations like [North Korea](https://www.theguardian.com/us-news/2018/sep/10/trump-almost-sent-tweet-north-korea-imminent-attack){:target="_blank"}. A lesser known story that we've studied in 11.138 (Civic Tech Prototyping with Prof. Sarah Williams) is how the city of Philadelphia utilizes Twitter to make announcements and encourage dialogue with residents. Constituents inactive on Twitter would miss out on local health alerts like this one about a junkyard tire fire in 2021:

    <blockquote class="twitter-tweet"><p lang="en" dir="ltr">Fire Update: Samples taken from the fire have found NO toxic chemicals at levels that would be harmful to your health. However, there is still particulate matter in the air from the smoke. (1/2)</p>&mdash; Philadelphia Public Health (@PHLPublicHealth) <a href="https://twitter.com/PHLPublicHealth/status/1458511038492643336?ref_src=twsrc%5Etfw">November 10, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

    But maybe it's a good thing considering that Philly's Public Health Department was actually Tweeting misinformation, considering that [15 different toxic chemicals were found from the fire](https://whyy.org/articles/after-a-junkyard-fire-philly-sent-an-emergency-alert-less-than-2-of-affected-residents-got-it/?utm_source=dlvr.it&utm_medium=twitter){:target="_blank"}.


3. Consumers of News Oulets + Other Social Media – despite the possibilities of spreading misinformation – even from verified governmental accounts (like Philly's Public Health department shown above), news articles and other social media outlets typically cite or screenshot Tweets to spread information and trends. As a typical reader of news articles myself, I would find Tweets embedded as a source of verified content – which [normalizes the readers' perception of Tweets as legitimate sources and gives Twitter that authority](https://www.niemanlab.org/2021/03/when-journalists-put-tweets-in-news-stories-do-they-transfer-too-much-power-to-twitter/){:target="_blank"}.

_**Non-targeted Use.**_ Twitter has been used for unplanned or nefarious purposes. As mentioned above in the first role of indirect stakeholders, Twitter users who are out to blackmail, shame, or put others in harm can do so simply by doxxing, or spreading private information about others. People have done so by leaking or threatening to leak others' addresses, nude content, and other sensitive data (credit card info, passwords, family info, etc.). Twitter has also gathered complaints on [Reddit threads](https://www.reddit.com/r/unpopularopinion/comments/gyf7tv/twitter_has_a_serious_child_porn_problem_and_no/){:target="_blank"} about its lack of banning accounts with child sexual exploitative and abusive content; these accounts are known to use certain hashtags to even trade or sell with other users. Recently, [Twitter has banned a total of ~45k Indian accounts: ~42k for promoting child porn and non-consensual nudity, and ~2k for spreading terrorism](https://in.mashable.com/tech/37880/twitter-suspends-over-45k-indian-accounts-over-child-sexual-exploitation-non-consensual-nudity-repor){:target="_blank"}. Finally, even with all the CAPTCHA's to check if you're really a human, Twitter suffers from bots - [around 16.5 million of them](https://www.makeuseof.com/how-many-bots-on-twitter/){:target="_blank"}. To prevent these non-target issues, Fritter would ideally use two-factor authentication with phone numbers paired with more challenging CAPTCHA in order to prevent bot, hacker, terrorist, and exploitative accounts from being made – as well as come with a more efficient reporting system, as [Twitter takes up to 7 days to suspend accounts for violation](https://help.twitter.com/en/rules-and-policies/enforcement-options){:target="_blank"}.


## Time
_**Adaptation.**_
> "You are what you eat."

The above quote takes on a different meaning when applied to Twitter – not that users are what they Tweet, but I believe and have observed that users become similar to the media they constantly consume. Twitter could support both extremely positive and negative lifestyle changes. If a user dedicates their entire Twitter account to posting about the gym, and only follows updated daily fitness goals + tips, Twitter has the power to enable positive change to that user's health while keeping them up-to-date with new exercises. On the other hand, if a Twitter user's feed is consistently filled with sensitive material, such as graphic violence, for the sake of authentic news coverage – then the user may suffer from exposure detrimental towards mental health. Twitter is a tool that is designated to keep users coming back to the screen - so with constant use, a user's feed can be intentionally designed to motivate positive lifestyle changes, as well as tear down.

As for Tweeters, as discussed in L3, restricting or modifying the ways we communicate on social media may change how we express ourselves over time. Just as Gmail's SmartCompose feature could changes user expression in emails, the inherent character limitation in Tweets can, over time, evolve how they express through text. In his article, Ian Leslie - a British journalist and author of books on human behavior - reflects upon how being forced to write concise, witty Tweets within 280 characters, while maintaining style on ["Twitter made [him] smarter"](https://ianleslie.substack.com/p/how-twitter-made-me-smarter){:target="_blank"}. In agreement with the above paragraph, Leslie also acknowledges that Twitter has the power to make us more stupid - and *it's really up to us on how we use Twitter as a tool to achieve either result*.

For more intentional usage and acknowledgment of social media as a tool, Fritter would allow for users to create accounts with personal interests and possibly intended goals. 

_**Sustained Friendships.**_
Twitter, through its hashtags (and its hashtag boards), allows for users with common interests to find and discuss with each other on public threads. From these discussions, users can get to know more about each other; they can also Direct Message (DM) each other, or Retweet with their own response. In short, it's easy to make new friends and enemies on Twitter. How do you make enemies? Simply enter into heated discussions, be disrespectful, or disagree against mob mentality).

But with the factor of longevity - sustaining friendships (or enmities, if you prefer) five years from now, there's a lot more work to be done. Three ways Twitter may influence friendships + family relationships based on the social networking platform include:

1. Politics + Virtue Signaling: in the U.S., within 5 years, we'll have one more presidential election cycle to go through. During that time, with U.S.'s tense political state, many Twitter-based users will most likely have relationships tested through the pressure to:
    * keep political interests discreet, 
    * virtue signal for sides through Likes and Retweets, and
    * even post about matters themselves,

    even if that means users may resort to [virtue signaling](https://dictionary.cambridge.org/us/dictionary/english/virtue-signalling){:target="_blank"}. Many relationships fell apart during the posting of the infamous [Blackout Tuesday](https://www.vice.com/en/article/93yadd/what-black-out-tuesday-can-teach-us-about-virtue-signaling){:target="_blank"} during the BLM movement - where many users were posting to demonstrate allyship, several were infurious about how those who posted were flooding hashtags and trends for vital information for protestors, and some were even breaking off connections with those who didn't post the square. It was messy, and I was relieved that I was off of social media at the time; though I'm definitely expecting more of these politics-based scenarios that may affect relationships within 5 years.

2. Life Updates: friends and family constantly updating their feed with their lives or latest updates on other common interests (like K-pop stans with the latest Jimin pictures) allows for continued conversations throughout time. These life updates not only help users stay connected virtually, but allows for the strengthening and growth of relationships - especially with Gen Z and common Twitter users beginning to adult.

3. Inactivity: on the other hand, app inactivity would most likely fizzle out Twitter-based relationships - unless said relationships are maintained in other spaces.


## Pervasiveness
_**Crossing National Boundaries.**_
Challenges that Twitter encounters when used in other countries include:
* Freedom of Speech and Banning "Propaganda": political, pro-Western posts in the U.S. may not be displayed in countries like China - creating inconsistency in information and world news communicated to users.
* Lost in Translation: with distinct cultures already set in place within countries like South Korea, Reddit user r/loveonlyoung posts to ask for help on understanding [Korean Twitter slang](https://www.reddit.com/r/Korean/comments/ln94ak/korean_twitter_slang/){:target="_blank"}. With communities to reach out to, communication will be easier; but even as a native Korean speaker, I would've had a difficult time trying to jump into Korean Twitter due to its own developed culture. So for non-Korean speakers, even with a Translation feature, the slang and cultural practices would be more difficult to understand.
* Differences in Policy: 

_**Widespread Use.**_
As the use of Twitter has spread to millions of users, interactions within the app have drastically changed. As Twitter continues to grow, three synergistic benefits will also become more powerful:
1. Mass Awareness - Quick and Powerful World News: Tweets provide instantaneous news - which is powerful for emergency situations, such as fire evacuation routes; alerts for the stock market; and imperative world news. [Twitter is often reports faster than published news articles and other media](https://www.google.com/search?q=twitter+has+the+fastest+news&rlz=1C5CHFA_enUS1000US1000&oq=twitter+has+the+fastest+news&aqs=chrome..69i57j69i64.3350j0j1&sourceid=chrome&ie=UTF-8#:~:text=Is%20Twitter%20Really,02/26%20%E2%80%BA%20i...){:target="_blank"} - so it's beneficial for verified news outlets + governmental agencies to use Twitter to deliver news quickly.
2. Advocation for People Groups (Minorities, Organizations, Businesses): with more users than ever before, and with synergistic mass awareness of people groups, typically underground causes, minorities, organizations, and businesses can push and meet goals for their calls to actions with bigger support systems + widespread awareness + advocacy.
3. Outside-the-box Perspectives from All Around the World: those who have never had a platform to speak can now share their unique perspectives, cultures, and ideas on Twitter - allowing for diffusion, new conversations, and shared cultures.

Three potential breakdowns (that we've already seen) also include:
1. Mass Misinformation - Quicker than its Correction: 
2. Cultural Appropriation - : 
3. Loss of Voice for Individuals: with growth towards billions of users on Twitter, the design must account for all the voices speaking into feeds; with only a certain number of national and local hashtag trends, maybe it's time to make trends further personalized.


## Values
Twitter's mission is to "[give everyone the power to create and share ideas and information instantly without barriers](https://investor.twitterinc.com/contact/faq/default.aspx#:~:text=The%20mission%20we%20serve%20as,a%20free%20and%20global%20conversation.){:target="_blank"}." It was harder to find a statement of their values.

Twitter, within its Terms of Service, states that users grant Twitter a license to make their ["content available to the rest of the world and to let others do the same,"](https://twitter.com/en/tos){:target="_blank"} demonstrated through their notable Retweet feature. 

_**Value Tensions.**_


_**User Experience of Values.**_



# II. Interviews
## Planning
_**Choosing Interviewees.**_ When choosing interviewees and thinking of matching criteria, I quickly thought of Chiara from Los Angeles and Gideon from South Korea, my good friends who are active Twitter users.

* Chiara is a 21-yo fashionista studying nursing in Los Angeles. She's a writer who enjoys reading Twitter threads and occassionally posts. She's your go-to person for popular trends, styles, and news – and she stayed active on Twitter throughout COVID. Chiara has also been active on TikTok and Instagram. I planned to ask her specific questions on her usage of Twitter and various social media throughout a politically heightened time such as the rise of COVID, BLM protests, and the StopAsianHate movement.

* Gideon is a 22-yo UCLA political science alumni from South Korea, well-versed in "Korean Twitter." He's also a prolific jazz musician, instrumentalist, and beat producer who has utilized social media to post music and create connections within the hip-hop and jazz scene. I planned to delve into his different experiences within using Twitter in the U.S. and South Korea –  as he would have deep insight into the two Twitter cultures.

[_**Interview Questions + Notes**_.](https://www.dropbox.com/s/a65kj2ra0tiyz5k/Interview%20Questions%20%2B%20Notes.pdf?dl=0){:target="_blank"} Not as organized as I'd like them to be - my handwriting was playing catch up with the interviewees' voices; thankfully they consented to recording, so I was able to backtrack and directly quote them. I also stuck loosely to the interview questions; because my interviewees and I were already close, I didn't need to "build rapport" from scratch – rather, I was able to kickstart into evoking stories after catching up with them. With these stories, I went with the flow and what questions felt right, rather than stick to the outline. 

## Interview: Chiara
> "Twitter makes me feel in touch with reality." - Chiara


_**Summary.**_

_**Synthesis.**_

## Interview: Gideon
> "It's not that Twitter made [people] act a way, but Twitter exposed people who act like this. It's not that social media changes people, but it rather reveals people." - Gideon

_**Summary.**_


_**Synthesis.**_