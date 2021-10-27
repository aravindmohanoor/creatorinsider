[![BOSS TALK: YouTube's VP of Engineering on Recommendations](https://i.ytimg.com/vi/_geqgdIfsaM/maxresdefault.jpg)](https://www.youtube.com/watch?v=_geqgdIfsaM)

## BOSS TALK: YouTube's VP of Engineering on Recommendations

Hello Insiders! Today we have our VP of Engineering, Cristos, here to answer your questions about the recommendation system.



Check it out and leave us your comments and questions below!



Chapters:

0:00 Intro

0:37 Question 1: Can you clarify watch time minutes vs retention as far as recommendations is concerned?

1:50 Question 2: How long does it take on average for a video to be picked up by the recommendation algorithm?

3:16 Question 3: Why do I get recommendations from huge channels I am not subscribed to?

4:27 Subs feed vs Home feed

8:54 Question 4: How do subscriptions influence recommendations, if at all?

9:00 Question 5: What is the view to sub percentage required to be recommended in the first place?

11:56 What is one thing you wish creators knew about how the recommendation system works?



-------------------------------------------



🔍 MORE GREAT RESOURCES FOR CREATORS 🔎



Want to be considered to help us build a better YouTube please sign up here: 

https://www.youtube.com/creatorresearch/?referral_code=CreatorInsider



Creator Insider Japan https://www.youtube.com/channel/UC8Y7Mqtw56UOzYd5MYDtiyQ/



We have 2 official YouTube channels that will also be helpful. Check them out! 



➡ YouTube Creators: https://www.youtube.com/user/creatoracademy



➡ TeamYouTube: https://www.youtube.com/user/YouTubeHelp



-------------------------------------------



👕👚SWAG 🎽☕



Check out our merch here: https://teespring.com/stores/creatorinsider



100% of the proceeds automatically support Red Cross



-------------------------------------------

Please note CI does not provide support - to find the appropriate resource for your question, please check out our Resources video: https://www.youtube.com/watch?v=sGm8dCs70bw



Remember, by commenting here or submitting Unlisted video links to email aliases associated with the channel, your comments, videos and username may be used in an upcoming video.



Creator Insider is an informal YouTube channel to share information from the YouTube Creator technical team with the wider Creator community. We will feature different people talking about the products they work on and changes we are making so you have more context. Please note this is not an official YouTube channel and is an experiment.



#### [0:00:00](https://www.youtube.com/watch?v=_geqgdIfsaM&t=0) |  - How long does it take a

video to get picked up by YouTube's recommendation systems? How do subscriptions influence recommendations? Let's get some answers to those questions and more from Christos Goodrow. He's a VP of Engineering at YouTube, specifically in charge of recommendations. You know, what shows up in your home feed and the up next section. I asked you all for some questions that I should ask Cristos and you came through. If you'd like to skip around, you can do so with the chapter headings below this video. All right. Let's jump in and meet Cristos.  

#### [0:00:30](https://www.youtube.com/watch?v=_geqgdIfsaM&t=30) |  - Great to be here. Thanks for

asking me, Matt. - Thanks for your time. Question from Liron and I hear this a lot. "Can you clarify watch time minutes versus retention as far as recommendations are concerned. Is 50% of a five minute video better or worse than three minutes of a 10 minute video?" Which does your system like better? - I actually get asked this question once in a while. After responsibility, the most important thing for the recommendation system is satisfaction.  

#### [0:01:00](https://www.youtube.com/watch?v=_geqgdIfsaM&t=60) |  So, it really depends on which of

the two videos the viewer is most likely to find satisfying. Which basically means which one are they most likely to give more stars to, when we ask them later in a survey. And so, we find that in general, people tend to be more satisfied when they watched more of the video, which is not a big surprise of course. But this is not true across the board, this is basically on average.  

#### [0:01:30](https://www.youtube.com/watch?v=_geqgdIfsaM&t=90) |  There are instances where people are quite

satisfied for instance, with entertainment videos that they've only watched a small portion of. And so, it really depends on the particular kind of video and even that particular user and what they typically are more satisfied with. - Interesting. Okay. Question from Sarah, "How long does it take on average for a video to be picked up by the recommendation algorithm?" - Ideally, it would happen immediately. And we've worked very hard to try to make our systems faster  

#### [0:02:00](https://www.youtube.com/watch?v=_geqgdIfsaM&t=120) |  so that the new videos can get

into the recommendation system as quickly as possible. In fact, we have special pathways for new videos to ensure that they can get picked up. However, it's not just about getting new videos into the pool of recommendation candidates. The most important thing is also trying to figure out which viewers would be interested in these videos.  

#### [0:02:30](https://www.youtube.com/watch?v=_geqgdIfsaM&t=150) |  And that's something that's especially hard for

new videos because we just don't have as much information about them. So, in some cases you can imagine that it's fairly straightforward if a viewer frequently watches videos from a particular channel and frequently watches them as soon as they're uploaded, then that viewer is a great candidate for this new video. But in other cases where that's not true, it can be very difficult to figure out how to match  

![](https://i.ytimg.com/vi/_geqgdIfsaM/maxres1.jpg)



#### [0:03:00](https://www.youtube.com/watch?v=_geqgdIfsaM&t=180) |  this new video to some particular set

of viewers. And of course if we get it wrong, then that's not gonna help the video at all. So, we've worked very hard on this particular issue and are always trying to come up with better ways to solve the problem. - The question from Joe, "Why do I get recommendations from huge channels I'm not subscribed to? If I wanted to watch, say pewdiepie, I would be subbed. Show me small channels that I wouldn't find on my own." What are your thoughts there?  

#### [0:03:30](https://www.youtube.com/watch?v=_geqgdIfsaM&t=210) |  - We actually tried very hard to

recommend videos from small channels. We have special projects that are trying to do that. The challenge of course is that, with small channels, we have less information about who the audience is for that channel. And so, it's harder to find the viewers who are interested in those videos. In addition to projects that are trying to improve the models and collect more signals for these small channels. We also have a product feature that we're working on,  

#### [0:04:00](https://www.youtube.com/watch?v=_geqgdIfsaM&t=240) |  which is called the new to you

chip. And chips are these buttons that appear at the top of the home feed or the watch next feed, when you pull down and they filter the feed to let's say certain, you know, videos that are about a certain topic. And so, when you pull down on home for instance, and you touch this new to you chip, then you'll see videos that are from channels that you haven't watched before. - Related question. One thing that was a big discovery for me as a creator  

#### [0:04:30](https://www.youtube.com/watch?v=_geqgdIfsaM&t=270) |  who was later hired at YouTube, is

the fact that when we optimized for the subs feed, viewership actually went down. So, when viewers subscribed to all these channels and we brought people to that feed first, they didn't watch as much as the actual home feed that was driven by recommendations. That kinda blew my mind, but at the same time, when I thought about my own subscriptions and I have over 400 and I asked myself like,  

#### [0:05:00](https://www.youtube.com/watch?v=_geqgdIfsaM&t=300) |  "How many of those channels have you

watched this week, Matt?" I realized... not many. Can you talk about that a little bit? - Early on when I came to YouTube, we were thinking about how do we make YouTube more valuable to people and who are the people who seem to get the most value from YouTube? For instance, who are the people who watch the most YouTube? And we noticed that the people who watch the most YouTube and who visit YouTube most frequently had many subscriptions. And so of course, one can imagine thinking, "Well, if we just got people a lot of subscriptions,  

#### [0:05:30](https://www.youtube.com/watch?v=_geqgdIfsaM&t=330) |  then they would tend to use YouTube

more." And so, we created these features where you could instantly subscribe to a bunch of channels all at once. Like, "Oh, you like basketball, here's 15 basketball channels. Push one button and then you're subscribed to all of them." And what we noticed was that people did get a lot more subscriptions, but they didn't watch YouTube much more or visit more frequently. And when we dug into this,  

#### [0:06:00](https://www.youtube.com/watch?v=_geqgdIfsaM&t=360) |  we started asking users how they felt

about their subscriptions. We found that there was just a wide range of reasons why viewers subscribed to a channel. So, there were people on one side who didn't have very many subscriptions and we asked them like, "So, you know, you watch these channels all the time. Why aren't you subscribed?" And people would respond, "Well, you know, I'm already paying for enough now. And I can't afford any more subscriptions." Of course, we told them that it was free and they were still sort of put off by the idea  

![](https://i.ytimg.com/vi/_geqgdIfsaM/maxres2.jpg)



#### [0:06:30](https://www.youtube.com/watch?v=_geqgdIfsaM&t=390) |  that they would have to commit to

something. On the other end of the spectrum. We talked to people who would subscribe to lots and lots of channels, maybe like you. And we would say, "Well, you subscribe to this channel, but you don't watch any more videos from that channel. Why did you subscribe?" And these people would often say, "Well, I saw this one video and it was awesome. And I just wanted to give him a high five. You know, that was a great video, loved it, keep doing what you're doing."  

#### [0:07:00](https://www.youtube.com/watch?v=_geqgdIfsaM&t=420) |  And then we'd say, "Well, would you

like to see more videos?" They're like, "No, no. I don't think I need to see any more videos from that channel. But that one was great and I just really want that creator to feel good about it." And so, when you think about the fact that there's such diversity in this signal called subscriptions, we can't just assume that everybody uses it in one way or another. And we need a system that can support that wide diversity subscription is some indication  

#### [0:07:30](https://www.youtube.com/watch?v=_geqgdIfsaM&t=450) |  that the viewer is interested or has

been interested in content from that channel. So, it means something and a place to start, but we can't, you know, we can't rely on it as a way to find content that the viewer definitely wants to watch. - Is it safe to say then that when creators asked people to subscribe, you know, should they ask in a way that makes it clear, like subscribe if you're going to watch. You know, don't do that blanket,  

#### [0:08:00](https://www.youtube.com/watch?v=_geqgdIfsaM&t=480) |  "Hey, subscribe. Everybody subscribed." Because you want

people committed to watching your videos. Isn't that important? - To be honest, I think there's a lot of reasons why subscriptions are important to subscribers and it's not just about helping the recommendation system find the audience for their viewers. And so, I understand that if creators want the high five, then it's great to ask people to subscribe. But just keep in mind that it doesn't mean that  

#### [0:08:30](https://www.youtube.com/watch?v=_geqgdIfsaM&t=510) |  that viewer or those viewers who are

subscribed are a reliable audience for your videos. And so, if your videos don't get as many views as the number of subscribers you have, it might be because you've got a lot of people who wanted to give you a high five about one video and not watch the next video that you make. - Related question from Liam, "How do subscriptions influence recommendations, if at all?" And there was a similar question. "What is the view to sub percentage required  

#### [0:09:00](https://www.youtube.com/watch?v=_geqgdIfsaM&t=540) |  to be recommended in the first place?"

- There's no explicit formula of view to sub percentage that's required. And I imagine that if we looked across all the channels on YouTube, we'd find a wide range of that statistic for a very successful channel. So, you could imagine a daily vlog might have a very high subscriber to viewer rate because the audience is sort of reliable, subscribed and comes back all the time.  

![](https://i.ytimg.com/vi/_geqgdIfsaM/maxres3.jpg)



#### [0:09:30](https://www.youtube.com/watch?v=_geqgdIfsaM&t=570) |  But if you think about, let's say,

how two channels, right? They may have subscribers, you know, but those people only wanted to know how to do something and not something else. And so, the view of the sub to view ratio might be quite low. And so, it is, like I said it is, an important starting place. If a person is subscribed to a channel, then we know they're at least familiar with that content.  

#### [0:10:00](https://www.youtube.com/watch?v=_geqgdIfsaM&t=600) |  And all things being equal, it's indication

to the recommendation system that this might be a person who's interested in the video. But relative to other things, like what have you watched recently? Or what topics are you interested in? It's not as important as other things. - Similarly, and this is my own question. You know, I uploaded most of my videos, 2011, 2012, and maybe, in prior to that. And I have over a hundred thousand subscribers, but, you know, if I were to upload a video now  

#### [0:10:30](https://www.youtube.com/watch?v=_geqgdIfsaM&t=630) |  and I have maybe, you know, a

year or two ago, I think I got, you know, a couple of thousand views. Are all those people gone? Are all those people who subscribed, have they moved on from either their YouTube accounts or from me as a creator? Do you think? - I really hope that these people aren't gone from YouTube for good and that they found other things to watch while you were on hiatus from your channel. But if they became interested in other things  

#### [0:11:00](https://www.youtube.com/watch?v=_geqgdIfsaM&t=660) |  and your channel has moved on or

your content is different than it was before,. Or they've moved on in their interests, then you can imagine that it wouldn't be a great match anymore. And that you might have to find a new audience. But it could be a place to start. So my expectation is, if you were to upload a new video to that channel, that's been on pause for awhile. Then the recommendation system would start with the former subscribers and see if some of them  

#### [0:11:30](https://www.youtube.com/watch?v=_geqgdIfsaM&t=690) |  were interested in the video. And if

they were, then that would probably grow to a larger base of your subscribers from the old channel. If instead, maybe the viewers have moved on to something else or you're producing a very different kind of content than the old channel had on it. And those first viewers or old subscribers aren't interested in anymore, then the system's gonna have to find a different audience for that new video. - All right, last question. As time goes on, YouTube becomes more and more a part  

#### [0:12:00](https://www.youtube.com/watch?v=_geqgdIfsaM&t=720) |  of society and culture around the world.

I mean, when I was a creator, it was just this kind of obscure website and I was kind of a weirdo for uploading videos. What is one thing you really wish that creators understood about how the recommendation system works? - I think the most important thing to keep in mind is that the recommendation system is for each viewer trying to help that viewer find the videos that will be most satisfying to that viewer. The only way to do this on YouTube with billions of videos,  

#### [0:12:30](https://www.youtube.com/watch?v=_geqgdIfsaM&t=750) |  is via personalization. So, you must keep

in mind that everything about YouTube is personalized. YouTube is a collection of millions of niches. And even the largest channel on YouTube has a very small audience relative to the overall size of YouTube. So, only a fraction of a percent of viewers on YouTube watch even the largest channels.  

#### [0:13:00](https://www.youtube.com/watch?v=_geqgdIfsaM&t=780) |  And so, really it's about finding your

particular audience. - Thanks so much for your time. I think there's some great nuggets in there and practical things that creators and viewers will be interested in. - Thanks, Matt. (upbeat drum music)  