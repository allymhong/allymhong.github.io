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

### I. [Value Sensitive Design (VSD)](#i-value-sensitive-design-vsd)

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


### II. [Interviews](#ii-interviews)
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


3. Consumers of News Outlets + Other Social Media – despite the possibilities of spreading misinformation – even from verified governmental accounts (like Philly's Public Health department shown above), news articles and other social media outlets typically cite or screenshot Tweets to spread information and trends. As a typical reader of news articles myself, I would find Tweets embedded as a source of verified content – which [normalizes the readers' perception of Tweets as legitimate sources and gives Twitter that authority](https://www.niemanlab.org/2021/03/when-journalists-put-tweets-in-news-stories-do-they-transfer-too-much-power-to-twitter/){:target="_blank"}.

_**Non-targeted Use.**_ Twitter has been used for unplanned or nefarious purposes. As mentioned above in the first role of indirect stakeholders, Twitter users who are out to blackmail, shame, or put others in harm can do so simply by doxxing, or spreading private information about others. People have done so by leaking or threatening to leak others' addresses, nude content, and other sensitive data (credit card info, passwords, family info, etc.). Twitter has also gathered complaints on [Reddit threads](https://www.reddit.com/r/unpopularopinion/comments/gyf7tv/twitter_has_a_serious_child_porn_problem_and_no/){:target="_blank"} about its lack of banning accounts with child sexual exploitative and abusive content; these accounts are known to use certain hashtags to even trade or sell with other users. Recently, [Twitter has banned a total of ~45k Indian accounts: ~42k for promoting child porn and non-consensual nudity, and ~2k for spreading terrorism](https://in.mashable.com/tech/37880/twitter-suspends-over-45k-indian-accounts-over-child-sexual-exploitation-non-consensual-nudity-repor){:target="_blank"}. Finally, even with all the CAPTCHA's to check if you're really a human, Twitter suffers from bots - [around 16.5 million of them](https://www.makeuseof.com/how-many-bots-on-twitter/){:target="_blank"}. To prevent these non-target issues, Fritter would ideally use two-factor authentication with phone numbers paired with more challenging CAPTCHA in order to prevent bot, hacker, terrorist, and exploitative accounts from being made – as well as come with a more efficient reporting system, as [Twitter takes up to 7 days to suspend accounts for violation](https://help.twitter.com/en/rules-and-policies/enforcement-options){:target="_blank"}.


## Time
_**Adaptation.**_
> "You are what you eat."

The above quote takes on a different meaning when applied to Twitter – not that users are what they Tweet, but I believe and have observed that users become similar to the media they constantly consume. Twitter could support both extremely positive and negative lifestyle changes. If a user dedicates their entire Twitter account to posting about the gym, and only follows updated daily fitness goals + tips, Twitter has the power to enable positive change to that user's health while keeping them up-to-date with new exercises. On the other hand, if a Twitter user's feed is consistently filled with sensitive material, such as graphic violence, for the sake of authentic news coverage – then the user may suffer from exposure detrimental towards mental health. Twitter is a tool that is designed to keep users coming back to the screen - so with constant use, a user's feed can be intentionally curated to motivate positive lifestyle changes, as well as tear down.

As for Tweeters, as discussed in L3, restricting or modifying the ways we communicate on social media may change how we express ourselves over time. Just as Gmail's SmartCompose feature could change user expression in emails, the inherent character limitation in Tweets can, over time, evolve how they express through text. In his article, Ian Leslie - a British journalist and author of books on human behavior - reflects upon how being forced to write concise, witty Tweets within 280 characters, while maintaining style on ["Twitter made [him] smarter"](https://ianleslie.substack.com/p/how-twitter-made-me-smarter){:target="_blank"}. In agreement with the above paragraph, Leslie also acknowledges that Twitter has the power to make us more stupid - and *it's really up to us on how we use Twitter as a tool to achieve either result*.

For more intentional usage and acknowledgment of social media as a tool, Fritter would allow for users to create accounts with personal interests and possibly intended goals. 

_**Sustained Friendships.**_
Twitter, through its hashtags (and its hashtag boards), allows for users with common interests to find and discuss with each other on public threads. From these discussions, users can get to know more about each other; they can also Direct Message (DM) each other, or Retweet with their own response. In short, it's easy to make new friends and enemies on Twitter. How do you make enemies? Simply enter into heated discussions, be disrespectful, or disagree against mob mentality).

But with the factor of longevity - sustaining friendships (or enmities, if you prefer) five years from now, there's a lot more work to be done. Three ways Twitter may influence friendships + family relationships based on the social networking platform include:

1. Politics + Virtue Signaling: in the U.S., within 5 years, we'll have one more presidential election cycle to go through. During that time, with U.S.'s tense political state, many Twitter-based users will most likely have relationships tested through the pressure to:
    * keep political interests discreet, 
    * virtue signal for sides through Likes and Retweets, and
    * even post about matters themselves,

    even if that means users may resort to [virtue signaling](https://dictionary.cambridge.org/us/dictionary/english/virtue-signalling){:target="_blank"}. Many relationships fell apart during the posting of the infamous [Blackout Tuesday](https://www.vice.com/en/article/93yadd/what-black-out-tuesday-can-teach-us-about-virtue-signaling){:target="_blank"} during the BLM movement - where many users were posting to demonstrate allyship, several were furious about how those who posted were flooding hashtags and trends for vital information for protestors, and some were even breaking off connections with those who didn't post the square. It was messy, and I was relieved that I was off of social media at the time; though I'm definitely expecting more of these politics-based scenarios that may affect relationships within 5 years.

    <blockquote class="twitter-tweet"><p lang="en" dir="ltr">Me on my way to unfollow everybody that “went silent” for blackout tuesday but hasn’t posted/said anything all week <a href="https://t.co/FTq4DvCaNO">pic.twitter.com/FTq4DvCaNO</a></p>&mdash; Jasmine Imon (@JasmineImon) <a href="https://twitter.com/JasmineImon/status/1268035959263760385?ref_src=twsrc%5Etfw">June 3, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>



2. Life Updates: friends and family constantly updating their feed with their lives or latest updates on other common interests (like K-pop stans with the latest Jimin pictures) allows for continued conversations throughout time. These life updates not only help users stay connected virtually, but allows for the strengthening and growth of relationships - especially with Gen Z and young Twitter users beginning to adult.

3. Inactivity: on the other hand, app inactivity would most likely fizzle out Twitter-based relationships over 5 years, unless said relationships are maintained in other spaces.


## Pervasiveness
_**Crossing National Boundaries.**_
Challenges that Twitter encounters when used in other countries include:
* Banning Twitter Altogether due to "Propaganda": Twitter is banned or restricted in countries like China, Iran, North Korea, and Russia - creating inconsistency in information and world news communicated to users - and the dividing of shared knowledge throughout the world. Continuing as we are may result in the separation of Twitter ecosystems, rather than pervasiveness across national boundaries.
* Differences in Internet Policy: differences in another nation's Internet policies may limit app activity in certain countries; for example, India had changed Information Technology (IT) rules in the past year – and as a result, imposed takedown orders on Tweets and accounts; in response, [Twitter filed a lawsuit, claiming that New Delhi had abused its power to violate "the freedom of speech guaranteed to citizen-users of the platform."](https://techcrunch.com/2022/07/05/twitter-sues-india-government/){:target="_blank"} Navigating differences in Internet policy may require features to comply with governmental updates, to prevent future lawsuits.
* Lost in Translation: with distinct cultures already set in place within countries like South Korea, Reddit user r/loveonlyoung posts to ask for help on understanding [Korean Twitter slang](https://www.reddit.com/r/Korean/comments/ln94ak/korean_twitter_slang/){:target="_blank"}. With communities to reach out to, communication will be easier; but even as a native Korean speaker, I would've had a difficult time trying to jump into Korean Twitter due to its own developed culture. So for non-Korean speakers, even with a Translation feature, the slang and cultural practices would be more difficult to understand. As these cultures develop furthermore without ease of introduction or diffusion, traveling Twitter users - including non-native residents of foreign countries - may stick to their native Twitter language, along with the foreign nation's Internet policies to prevent the same extent of rights they had initially: creating inconsistency across borders.

_**Widespread Use.**_
As the use of Twitter has spread to millions of users, interactions within the app have drastically changed. As Twitter continues to grow, three synergistic benefits will also become more powerful:
1. Mass Awareness - Quick and Powerful World News: Tweets provide instantaneous news - which is powerful for emergency situations, such as fire evacuation routes; alerts for the stock market; and imperative world news. [Twitter often reports faster than published news articles and other media](https://www.google.com/search?q=twitter+has+the+fastest+news&rlz=1C5CHFA_enUS1000US1000&oq=twitter+has+the+fastest+news&aqs=chrome..69i57j69i64.3350j0j1&sourceid=chrome&ie=UTF-8#:~:text=Is%20Twitter%20Really,02/26%20%E2%80%BA%20i...){:target="_blank"} - so it's beneficial for verified news outlets + governmental agencies to use Twitter to deliver news quickly. With more users, they will be able to reach groups that were never reached before.
2. Advocating for People Groups (Minorities, Organizations, Businesses): with more users than ever before, and with synergistic mass awareness of people groups, typically underground causes, minorities, organizations, and businesses can push and meet goals for their calls to actions with bigger support systems + widespread awareness + advocacy.
3. Outside-the-box Perspectives from All Around the World: those who have never had a platform to speak can now share their unique perspectives, cultures, and ideas on Twitter - allowing for diffusion, new conversations, and shared cultures.

Three potential breakdowns (that we've already seen) also include:
1. Mass Misinformation: apparently, fake news travels around quicker than its correction on Twitter; with more users - and scaled increase in Retweets of misinformation, it may be even more difficult to successfully filter out fake news media.
2. Cultural Appropriation - Loss of Healthy Cultural Boundaries: with cultural practices shared and demonstrated to the public - and without clear boundaries set (or acknowledgement of such boundaries), cultural practices are easily emulated by other groups. An extreme example case includes that of Oli London, a British YouTuber, who identifies as "Korean" after undergoing 18 surgeries to look like Jimin:
    <blockquote class="twitter-tweet"><p lang="en" dir="ltr">I fully identify as Korean after undergoing my final transitional surgeries. 🇰🇷</p>&mdash; Oli London (@OliLondonTV) <a href="https://twitter.com/OliLondonTV/status/1405491888979861507?ref_src=twsrc%5Etfw">June 17, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
3. Loss of Voice for Individuals: with growth towards billions of users on Twitter, the design must account for all the voices speaking into feeds; with only a certain limit of national and local hashtag trends, it may be time to make trends further personalized.


## Values
Twitter's mission is to "[give everyone the power to create and share ideas and information instantly without barriers](https://investor.twitterinc.com/contact/faq/default.aspx#:~:text=The%20mission%20we%20serve%20as,a%20free%20and%20global%20conversation.){:target="_blank"}."

Finally, according to Comparably, Twitter's statement of values includes growing its ["business in a way that makes [it] proud. Recognize that passion and personality matter. Communicate fearlessly to build trust. Defend and respect the user's voice. Reach every person on the planet. Innovate through experimentation. Seek diverse perspectives. Be rigorous. Get it right."](https://www.comparably.com/companies/twitter/mission){:target="_blank"}

_**Value Tensions.**_
Twitter experiences the following value tensions within their own stated values (from the statement quoted above):
1. "Build Trust": Moderated Speech + Content vs. "[Communicating] Fearlessly" - fearless communication  powerfully promotes the freedom of expression and being unapologetically yourself. But what if speaking up reveals mistrust, miscommunication, and misinformation? Or speaking up involves graphic, nude, or sensitive content? What would build more trust? Moderated speech and content, where an algorithm can censor or shadowban content? Or leaving Twitter as is and only implementing an effective "Report" feature - where users decide for themselves whether a Tweet has gone too far. Twitter as of now takes up to 7 days to review reports; so Fritter would make the process more efficient with a speedier review turnaround. Twitter also allows for a "Sensitive Content" flag, so that viewers of sensitive posts are aware, while posters can still post unapologetically. Design features that would allow for more moderation include the removal of hashtagging sensitive words (like "porn" or "suicide"), or the default separation of such words from the beginning (which users could change in Settings).
2. Respect: No Disrespect Allowed vs. "Defend and respect the user's voice" with a twist: even when that user is disrespecting another individual or group - it's hard to draw the line of what is and isn't permissible disrespect. Dramatic Twitter threads where users go back-and-forth with name-calling, trolling, blaming, gossiping, arguing, and [mobbing](https://www.washingtonpost.com/opinions/2019/07/06/twitter-mobs-show-worst-people-also-best/){:target="_blank"} sometimes serve as a source of entertainment for consumers and groups:
    <blockquote class="twitter-tweet"><p lang="en" dir="ltr">i love when people fight on twitter. it’s so therapeutic to read.</p>&mdash; Madison Garman (@madigarman) <a href="https://twitter.com/madigarman/status/1521226410215415808?ref_src=twsrc%5Etfw">May 2, 2022</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

The "Report" button as is on Twitter would allow users to determine whether the line of disrespect is crossed by other users. A design feature that may help when mobs are all-out to block one person is by tracking whether certain groups of users have a pattern of spam-reporting other users. Finally, a design feature that would prevent more disrespect altogether is the option of the Twitter thread-owner, or users mentioned, to hide insensitive or hateful Tweets - this option could also be automated, as YouTube hides certain replies with hateful or spammy keywords. Even allowing Twitter thread-starters to review future Tweets posted would help moderate discussion while still giving the user autonomy.

3. "Seek diverse perspectives." vs. "Get it right." When diverse perspectives are in discussion of matters still in the air (such as matters with gaps in information and high probabilities of misinformation), would discussing such perspectives create more room to "get it wrong?" Where is the line? When theories about current realities are in discussion, a Twitter-based design feature that would help promote more diverse stances - without clumping threads of debate and heated arguments - is using the anonymous "Poll" feature, for users to share their viewpoints, observe others', and view how many users agree or disagree.

_**User Experience of Values.**_
Users can experience Twitter affecting their values through how the platform implements its rules, moderates content, and updates features. Twitter valuing the freedom of expression in "fearless communication to build trust" can result in non-targeted use (as mentioned before) - with sensitive content like nudity, exploitation, and graphic violence being posted. [Yet Twitter allows for consented nudity, as well as graphic violence "for documentary or educational" purposes](https://help.twitter.com/en/rules-and-policies/media-policy){:target="_blank"}, as long as the content is flagged as "Sensitive Content." This flag was introduced as a feature in 2017. The use of Twitter and its unique allowance for media with violence and nudity, as long as it's flagged, shows that it truly values the freedom of expression for users.

As someone who got a Twitter for updated news during the summer 2020 California fires, I definitely appreciate the ease of communication without filtering or obtuse moderation - even when certain accounts were Tweeting wildfire updates back-to-back, I appreciated that I was able to intake each Tweet immediately. Yet, as I continued to scroll through my timeline, I would see more violent content - I won't forget seeing horses trying to escape their stalls as they burned down. Sometimes these kinds of posts did not flag themselves as "Sensitive," and I was often the first to see these kinds of posts (as I closely followed hashtags of nearby fires, as I wanted to stay on watch for evacuation). These kinds of posts have left a scarring mental image for a while, and that was due to Twitter's upholding of instantaneous, "fearless communication." I both gain and lose from this value - yet from then on, I decided to try to physically look away and scroll fast whenever I inferred posts contained sensitive content (when unflagged). The feature of flagging aligns with me, but beforehand I've also experienced more curiosity from a post being blocked - whereas I may have just scrolled past it when I know how horrible the experience it'll be. I've stayed away from Twitter for a while now, so I haven't had new brutal mental images to fill my head. But I've also been missing out on real-time news.


# II. Interviews
## Planning
_**Choosing Interviewees.**_ When choosing interviewees and thinking of matching criteria, I quickly thought of Chiara from Los Angeles and Gideon from South Korea, my good friends who are active Twitter users.

* Chiara is a 21-yo fashionista studying nursing in Los Angeles. She's a writer who enjoys reading Twitter threads and occasionally posts. She's your go-to person for popular trends, styles, and news – and she stayed active on Twitter throughout COVID. Chiara has also been active on TikTok and Instagram. I planned to ask her specific questions on her usage of Twitter and various social media throughout the polarizing rise of COVID, BLM protests, and #StopAsianHate.

* Gideon is a 22-yo UCLA political science alumni from South Korea, well-versed in "Korean Twitter." He's also a prolific jazz musician, instrumentalist, and beat producer who has utilized social media to post music and create connections within the hip-hop and jazz scene. I planned to delve into his different experiences within  Twitter in the U.S. and South Korea –  as he would have deep insight into the two Twitter cultures.

[_**Interview Questions + Notes**_.](https://www.dropbox.com/s/a65kj2ra0tiyz5k/Interview%20Questions%20%2B%20Notes.pdf?dl=0){:target="_blank"} Not as organized as I'd like them to be - my handwriting was playing catch up with the interviewees' voices; thankfully they consented to recording, so I was able to backtrack and directly quote them. I also stuck loosely to the interview questions; because my interviewees and I were already close, I didn't need to "build rapport" from scratch – rather, I was able to kickstart into evoking stories after catching up with them. With these stories, I went with the flow and what questions felt right, rather than stick to the outline. 

## Interview: Chiara
> "Twitter makes me feel in touch with reality." - Chiara


_**Summary.**_
Chiara reads Tweets in her free time, between studying - and she prefers doing so over watching movies. She's more of a _reader_ of threads, as she doesn't post often. Although she also scrolls on TikTok, she prefers partaking in Twitter's stronger communities of text-based threads over TikTok's stream of one-sided, directed, audiovisual content. 

She found that TikTok has a much more ad-based, curated feed that depends on trends due to its profit-based nature. TikTok is also a lot quicker to ban accounts, whereas Twitter has "less cancel culture" as an app. I asked her, "[Didn't cancel culture start on Twitter?](https://en.wikipedia.org/wiki/Cancel_culture){:target="_blank"}" She acknowledged that it did, but with a TikTok's bigger potential to go viral, Twitter's practice of taking accounts down after up to 7 days seemed much less intense. She said,

> "Tweets are more remembered in society, while on TikTok you're cancelled quickly - whether you're known or unknown."

Chiara emphasized several times throughout the one-hour-interview that Twitter stays true to *authenticity*. She highlights better opportunities for people to express themselves on the platform, instead of "[pleasing] certain audiences for the algorithm" – and it's easy to find people to resonate with. To augment the benefits of Twitter communities, she shared a personal realization: as she grew in her faith as a Christian over the pandemic, she noticed that her Twitter feed and community grew with her.

Despite its only downfall of the lack of promotion for in-person events and activities (where TikTok and Facebook events shine through), Twitter has made Chiara feel in touch with reality. She pointed out how the app funnels authentic content, with news outlets and TikTok videos frequently sourcing Tweets to back up stories. She joked, 

> "I think it's funny how they're not looking to in-person interviews, it's like Twitter became the ".gov" of social media."

To contrast Twitter's widespread perception of credibility, I asked Chiara if she had any experience with misinformation and fake news on Twitter.

She was quick to mention the Johnny Depp vs. Amber Heard trials, a topic that flooded social media. She said that the trials fueled a lot of Tweets that "should've been flagged," as users would tell stories appearing as the truth against Heard's case, taking advantage of its perceived reliability. Tip jars were placed in Starbucks and local stores for customers to pick sides, despite the heavy nature of the domestic violence trial. 

> <blockquote class="twitter-tweet"><p lang="en" dir="ltr">The Place I’m eating at has a Johnny Depp and Amber heard tip jar!!😁 🤣 <a href="https://twitter.com/hashtag/JusticeForJohnny?src=hash&amp;ref_src=twsrc%5Etfw">#JusticeForJohnny</a> <a href="https://t.co/mbRz4qguqq">pic.twitter.com/mbRz4qguqq</a></p>&mdash; Eva (@EML22) <a href="https://twitter.com/EML22/status/1524059301106659329?ref_src=twsrc%5Etfw">May 10, 2022</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

The movement for mass support for Depp and hate towards Heard was largely fueled by Twitter; however, after Depp won the trials, users backtracked to find supporting evidence for Heard. Yet in the aftermath, the damage had been done: Heard's image was ruined, and users have sent death threats to Heard. Chiara was overwhelmed by her timeline being filled with back-to-back Tweets during the seven weeks of trials - and she would instead spend time watching Hulu shows to wind down.

Another time she'd end up staying off of Twitter was when BLM protests took. She was directly impacted by how slow Twitter was to filter or flag "sensitive content." She recalls seeing videos of near-dead and severely injured bodies on the streets of protests, attached to Tweets with calls to action. Although Chiara resonated with the fight against police brutality, she felt that the Tweets were wrongly guilt-tripping and shaming Twitter users who didn't protest as well.

With having seen such triggering media, she declared that she would never allow her kids to go on it - not until they were 17. She herself started using Twitter when she was 15 - but she noted that Gen Z was the experimental generation - popular social media's first user-base. With all that she's experienced now, Chiara expressed concern about the current 13+ age requirement. She couldn't imagine seeing the aforementioned graphic content she had at 13. "That's just way too young."

All in all, Chiara enjoys Twitter when timelines aren't drowning in high-stake or stressful trends. It especially helped her stay connected to friends and find new communities throughout COVID. She concluded that although it's dangerous to see how Twitter seems "reliable," it still is the most authentic app space for expression.

_**Synthesis.**_
Interviewing Chiara provided further insight into what makes Twitter different from other popular social media platforms. As a once-avid TikToker and less experienced Twitter user, gaining her insight on her experiences on both apps helped me gain understanding as a user and designer. I resonated with her concerns with how TikTok seems much more targeted and algorithmically curated, whereas as a Twitter user, you would be able to build your own timeline. Yet, as discovered through her stories on the Depp v. Heard trials + BLM, that option to formulate your own timeline seems to disappear when movements, arguments, and trends with high stress take social media. A design feature that would help users that also feel overwhelmed by such topic flooding should have the option to mute certain hashtags or Tweets from entering their timeline. This way, certain topics can be avoided in times where there seems to be no escaping them. This way, Fritter could keep users on its platform during polarized times. To improve upon Twitter's slow response (upwards of 7 days) to user-based reports as well, Fritter will have a faster turnaround to answer reports. TikTok, with its [algorithmic-based shadowbans](https://www.makeuseof.com/what-is-tiktok-shadowbanning/#:~:text=A%20TikTok%20shadowban%20is%20an,frequently%20as%20they%20did%20before){:target="_blank"} and accoutn bans, has a turnaround of ~24 hours - which may be too quick. Capping the turnaround at 3-4 days may be a good balance in between, with a heightened need for quicker turnarounds during times of high stakes due to sensitive content and increased number of posts.

Finding and navigating the contradictions within the freedom of expression - to be authentic - and the appearances of reliability - revealed value tensions within Chiara's user experience. Although she was able to retain feeling in touch with reality, with the easy spread of misinformation and abuse of Twitter's elevated stance as the ".gov of social media," it may be confusing for users and indirect stakeholders to discern what the facts truly are. [Twitter implemented a new "crisis misinformation policy" to crack down on harmful posts spreading lies during times of emergencies](https://www.npr.org/2022/05/19/1100100329/twitter-misinformation-policy-ukraine#:~:text=SAN%20FRANCISCO%20%E2%80%94%20Twitter%20is%20stepping,times%20of%20conflict%20or%20crisis.){:target="_blank"} - adding warning labels to debunked posts, disabling users from interacting with misinforming Tweets, and no longer automatically recommending with misleading claims. Whether or not Fritter would implement similar policies depends on if Fritter will be a platform to communicate real-time news during crises - as this constraint does step into limiting the freedom of speech on Twitter. I'm just still not sure about the efficacy of implementing accurate fact-checking at the speed of Tweets (or soon, Freets).

What I do know is that Twitter's allowance of freedom of speech and "authenticity," despite its coupling with sensitive content like graphic violence and nudity, created more benefits for Chiara - through more genuine expression with friends and community groups on the platform. And that's something that Fritter needs to maintain with just the right amount of moderation to limit harmful, non-targeted use.


## Interview: Gideon
> "It's not that Twitter made [people] act a way, but Twitter exposed people who act like this. It's not that social media changes people, but it rather reveals people." - Gideon

_**Summary.**_
Gideon started using Twitter in his first-year of high school in South Korea and grew his music-based, beat promotion account to 60k followers, which was "surprisingly easy" for him. He compared how it was much more difficult to grow in the same scale on YouTube and Instagram, due to the platforms' requirements to create original content; he saw similarities with rapid growth and ease of content creation with TikTok. He noted that by his 70th Tweet, he had gained 3k followers on Twitter, whereas by his 70th video on YouTube, he had only amassed had 1k subscribers. Gideon acknowledged the pervasiveness of Twitter space, saying:

> "No matter how niche you are, you can always find an audience on Twitter."

Gideon noted that you could easily amass a following by simply Tweeting about hot trends on Twitter's hashtag board. In 2017, a Twitter debacle on the topic of feminism was so substantial that even South Korean celebrities had to give their two cents. Yoo Ah In, trivialized feminism in a Tweet - and Twitter blew up. Gideon believes that this debacle was so extensive that the South Korean sociocultural climate was all affected. When he Tweeted on the matter with a trending hashtag, he gained 1500 followers instantaneously.

Unfortunately, he had to delete his Twitter account when he posted strongly opinionated Tweets on Korean Twitter during the BLM movement. As an avid listener of jazz, Gideon recalls his teacher telling him that jazz isn't generalized American music - rather, it is black music. Having studied the roots of the genre, he is quick to acknowledge the Afro-centric roots in hip hop and rap music. However, when BLM took social media two summers ago, Korean hip hop rappers tried to promote their music and take advantage of the market. When #StopAsianHate started trending shortly after, Korean rappers like Owen Ovadoz came out to say that they didn't support BLM:

> ![]["assets/images/owen.jpeg"]


Gideon was baffled; how could these K-hip-hop artists, after appropriating black culture by getting dreadlocks, incorporating ebonics, and greatly benefiting from shows like "Show Me The Money" (basically the K-hip-hop version of X Factor) - come out _against_ BLM? 

Gideon used his account to voice these concerns. He Tweeted out,
> "Why don't we use platforms to promote BLM for equity? We should discuss and participate in this as partakers in Afrocentric cultures."

He unsurprisingly received a lot of hate from K-Hip-Hop Twitter, but he retained support from his followers in K-Jazz Twitter, as users were more likely to understand the Afrocentric roots of jazz. But when he got into an intense argument in his Tweet's thread, the user on the other side actually found out the school Gideon went to and sent threats through DM's. Gideon grew paranoid and decided to delete his account as a result. 

He rejoined Twitter with a new handle when he started attending school in UCLA in 2021; while there, he noticed the differences between Korean and U.S.-based Twitter. He learned of the origins of the #MeToo movement in America (which started in 2006 on MySpace) - and compared with the trending "indigenized" #MeToo on Korean Twitter in ~2018. By "indigenized," he meant that the culture and trends become molded to fit into Korean society. With its own global cultural market with #KPopTwitter, one of the largest subcultures of Twitter, he's observed that Korean Twitter often attracts new users – and doesn't need to reach to other cultures. Gideon roughly estimated that ~30% of U.S. Twitter / social media trends show up in hashtag boards and timelines, whereas the remaining ~70% includes self-started Korean trends.

In terms of differences in policy, Twitter in South Korea:
* blocks any potential propaganda-like content from North Korea – hence, Gideon was unable to see posts from famous North Korean refugees until he came to the U.S.
* requires a IPIN phone number verification + legally checks your DM's when provoked. Why? Well, after a [17-year-old girl kkidnapped and murdered an 8-year-old in Incheon, South Korea](https://ko.wikipedia.org/wiki/%EC%9D%B8%EC%B2%9C_%EC%B4%88%EB%93%B1%ED%95%99%EC%83%9D_%EC%82%B4%ED%95%B4_%EC%82%AC%EA%B1%B4){:target="_blank"} inspired by connections with Korean Hannibal Twitter (a community inspired by the show on Hannibal Lecter, the infamous cannibalistic serial killer), Korean Twitter policies enacted verification requirements and 

What he admires about Twitter
Cons with mob mentality and fake news stories
New policy on Twitter to approve for fact checks

_**Synthesis.**_
