[![Behind the Algorithms - How Search and Discovery Works on YouTube](https://i.ytimg.com/vi/9Fn79qJa2Fc/maxresdefault.jpg)](https://www.youtube.com/watch?v=9Fn79qJa2Fc)

## Behind the Algorithms - How Search and Discovery Works on YouTube

Hello Insiders! Today we're talking about the algorithm and how it works.



Check it out and leave us your comments and questions below!

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



#### [0:00:00](https://www.youtube.com/watch?v=9Fn79qJa2Fc&t=0) |  - Hey insiders, it's Rachel here and

I'm a product manager on YouTube recommendation system. I've spent the last few years working on YouTube analytics and my job was really to help creators understand their video performance. Today, I wanted to share a presentation that I normally give at conferences that helps explain how the recommendation system works and what factors influence how many impressions your videos receive. I hope it's helpful. Let's get into it. Okay, so in this section, we're gonna cover in general how the recommendation system works  

#### [0:00:30](https://www.youtube.com/watch?v=9Fn79qJa2Fc&t=30) |  and what it's designed to do. If

you learn anything from this presentation, I hope it's that you do not need to be an expert in algorithms or analytics to be successful on YouTube. You just need to understand your audience. So to start, let's talk about the goals of the recommendation system, those have always remained the same. The algorithm is designed to do two things, match viewers with videos they're most likely to watch and enjoy and then hopefully, recommend videos that make them happy. So we really maximize long-term satisfaction, so our viewers keep coming back to YouTube because they know that they'll find videos  

#### [0:01:00](https://www.youtube.com/watch?v=9Fn79qJa2Fc&t=60) |  that they'll like there. Now, although our

goals have always been the same what we optimize for has changed over time. If we go back to 2011, we were optimizing for clicks and views, and this was not unique to YouTube. I think many platforms started recommending videos that people were just likely to click into. But that's not that great of a metric because it may indirectly incentivize click baity or sensational titles, or thumbnails that get people into watch a video but it doesn't make them very satisfied or happy.  

#### [0:01:30](https://www.youtube.com/watch?v=9Fn79qJa2Fc&t=90) |  And we received a lot of your

feedback in and around the 2011 time period that a lot of the viewers home pages or recommendations were these sensational off-putting videos. And so to help correct for that, we moved towards watch time. And how much time somebody spends watching a video or a channel is much more indicative of the quality of the content because if you spend more time watching something it is more likely that you're gonna be interested in it, but watch time is not a perfect metric either. So, I'm sure you've all seen time  

#### [0:02:00](https://www.youtube.com/watch?v=9Fn79qJa2Fc&t=120) |  maybe binging through a series that you

watched hours of but you still didn't feel that good afterwards. And so what we wanted to identify is how do we define quality or valued watch time? And so, what we wanted to optimize more towards is satisfaction. And the way we do that is directly asking viewers about what videos they like and enjoy through surveys, and then actually optimizing for what they like. And not only is satisfaction important but we've also added more and more responsibility objectives  

#### [0:02:30](https://www.youtube.com/watch?v=9Fn79qJa2Fc&t=150) |  because especially in spaces like news or

medical information, it's really important that we raise authoritative voices and content and reduce the spread of any borderline violative content that could harm viewers or contribute to the spread of misinformation. So if you fast forward to today, what we actually optimize for in discovery is much more satisfaction related goals. Like what videos do viewers regularly watch but make them happy as well as making sure that we're doing it responsibly.  

![](https://i.ytimg.com/vi/9Fn79qJa2Fc/maxres1.jpg)



#### [0:03:00](https://www.youtube.com/watch?v=9Fn79qJa2Fc&t=180) |  Okay, so if I just spoke all

the time about satisfaction and you're like, "Well, how do you "actually measure satisfaction?" We serve out millions of surveys per month to viewers. Now, they're not served on every single video. The viewers don't fill this out for every video they watch, we don't wanna overwhelm viewers with surveys. But we use this data to train prediction models to identify which videos are highly satisfying. So an individual viewer may only receive one or two of these surveys per month, but the main point you need to understand is that we no longer consider all watch time on YouTube to be equal.  

#### [0:03:30](https://www.youtube.com/watch?v=9Fn79qJa2Fc&t=210) |  We really focus on satisfaction. Surveys are

one of the most important pieces of data that we use to train this. We don't yet share this data with creators today because we often don't have enough significant data on an individual video for you to really make significant conclusions around it. So sometimes an individual video might only receive five responses. Now that information is valuable to us because we can still train our prediction models and be like, "Okay, identify stuff "that's satisfying in general." But for an individual creator sometimes that's not enough data to act on.  

#### [0:04:00](https://www.youtube.com/watch?v=9Fn79qJa2Fc&t=240) |  We are looking at adding more satisfaction

data and externalizing it to creators. So it is something we're working on. But surveys aren't the only piece of data that we look at for satisfaction. So in addition to that, we also use signals from viewers like not interested feedback. So when videos are recommended to viewers on the homepage or suggested do they click not interested? We also use signals like likes and dislikes and shares to determine whether a video is satisfying. Throughout this presentation I'm gonna use the word recommended or recommendations a lot  

#### [0:04:30](https://www.youtube.com/watch?v=9Fn79qJa2Fc&t=270) |  and I wanted to clarify what I

mean when I say that. So recommendations when I say that, I'm referring to the home page and suggested or the videos that are algorithmically offered up to viewers that they may want to watch on the page when they open youtube.com or the mobile app which is home or the recommendations that are shown alongside the video the viewer is currently watching. So that's what suggested is, so suggested on desktop is like the panel on the side  

#### [0:05:00](https://www.youtube.com/watch?v=9Fn79qJa2Fc&t=300) |  or the videos beneath the, when you're

watching on mobile. Now, creators often refer to the algorithm. We actually have different systems depending on where users are watching videos on YouTube. Like the homepage offers up a broad array of videos when you visit youtube.com and it uses similar signals as suggested, but they are designed to do slightly different things. So, the algorithm is a bit of a misnomer 'cause we actually have multiple systems that are designed to do different things depending on if the viewer is on home, suggested or search.  

#### [0:05:30](https://www.youtube.com/watch?v=9Fn79qJa2Fc&t=330) |  But when I say recommendations, I'm talking

about homepage suggested. This is how the majority of viewers watch and discover videos on YouTube. So it's likely, but these are the top traffic sources for your channel, but that's of course not always the case. A lot of creators ask, how do I optimize my content so I get more views from homer suggested. And the difficult answer is you can't, you can't optimize for a traffic source. You can only optimize for people or viewers. But I will describe how they work  

![](https://i.ytimg.com/vi/9Fn79qJa2Fc/maxres2.jpg)



#### [0:06:00](https://www.youtube.com/watch?v=9Fn79qJa2Fc&t=360) |  and some general things you can do

to optimize to build an audience. So let's start with the homepage. Home offers up a broad array of videos that viewers are most likely to watch when they visit YouTube. And at that stage, we don't have a lot of information about the intent the viewer might have when they're coming to YouTube, maybe they're coming here to learn something or maybe they're coming here to be entertained. So home offers a pretty diverse array of recommendations. And the way it ranks videos is primarily based on two main categories.  

#### [0:06:30](https://www.youtube.com/watch?v=9Fn79qJa2Fc&t=390) |  The first one is performance. So that

means the signal that you're probably already familiar with, like click through rate, average view duration and if the viewers are happy. So performance is really looking at how a video performs when it is offered to viewers on home. So in the context it's shown. So the homepage is really learning from when videos are recommended to viewers on home, what do they do with it? Do they click to watch? Do they click not interested? Do they ignore it and click something else? In addition to that, we have personalization. So if we only use performance like click through rate  

#### [0:07:00](https://www.youtube.com/watch?v=9Fn79qJa2Fc&t=420) |  and average view duration to inform which

recommendations were good for viewers, YouTube would just be like a giant explorer or like trending tab, which is not the case. It's all personalized for the viewers own interest. And so we use a combination of performance and personalization and personalized factors or like how much that individual viewer watches a channel or topic over time, or their recent watch history. That also helps inform, is this a good relevant recommendation for that viewer?  

#### [0:07:30](https://www.youtube.com/watch?v=9Fn79qJa2Fc&t=450) |  Now again, there's nothing you can specifically

do to get more views from home but you can look at your content and think what would a new viewer who has never been exposed or watched any of the content from my channel, what would they do if they saw this recommendation? Like really look at your title and thumbnail from the eyes of a new viewer. This is where a lot of content is discovered for the first time was on the homepage. And so be sure to look at your content and think what a new viewer click to watch if they had otherwise never been exposed to this content.  

#### [0:08:00](https://www.youtube.com/watch?v=9Fn79qJa2Fc&t=480) |  So maybe you have a video that's

like it's my mom's birthday, if you're a vlogging channel, that might be relevant to your core audience but if we recommend that to a new viewer on home they might be likely to ignore that recommendation and click something else because it doesn't mean something for them. Okay, moving on to suggested. Now, suggested is designed to offer the best videos that if you were as most likely to watch next after the one they're currently watching. So suggested to rank videos using a lot of signals such as videos that are often watched together this helps us identify videos that you might not have seen  

#### [0:08:30](https://www.youtube.com/watch?v=9Fn79qJa2Fc&t=510) |  that are relevant to your interests, topically

related videos but also they're not just videos that are relevant to the one you're currently watching, they're also based on your past watch history. They're both personalized and a little bit more related. And suggested, the recommendations are usually a little bit narrowed down compared to the homepage because we already have an idea of what kind of session the viewer is having at that point. Again, can't optimize for suggested but you can optimize to keep people watching your channel. The most effective thing that I've seen creators do  

![](https://i.ytimg.com/vi/9Fn79qJa2Fc/maxres3.jpg)



#### [0:09:00](https://www.youtube.com/watch?v=9Fn79qJa2Fc&t=540) |  is of course develop series or topically

related videos. Those videos are more likely to be recommended together because people are more likely to watch them in the same session. So you can imagine if I'm watching a video about antique music boxes, I'm more likely to get more music box videos in the panel on the side or in suggested. So, if you develop a series that is really consistent or has commonalities between the content, it is more likely to be recommended together, viewers are more likely to watch them one after another.  

#### [0:09:30](https://www.youtube.com/watch?v=9Fn79qJa2Fc&t=570) |  And so series is one effective way

to keep people watching, having a consistent title and thumbnail style is another. So you can imagine when a viewer is looking at everything that they could choose to watch next, there are a lot of options there. And if you have really strong identifiable branding that's consistent, it's really easy to pick out which videos are from your channel and it just makes such decision all the quicker for viewers. And of course, there's other stuff you can do, you can do call to actions to watch more. If you liked this video, I think you'd be interested in another one on my channel.  

#### [0:10:00](https://www.youtube.com/watch?v=9Fn79qJa2Fc&t=600) |  And we have playlist and end screens

and those work too. Okay, another question I often get from creators is should I worry or be concerned about if a video has more or fewer views from a specific traffic source? And I wanted to reassure creators that this is completely normal. Viewers discover videos in different ways and that's expected. So for example, learning or how to videos. They often get more views from search because that's how viewers try and find learning videos. Like we don't know to recommend a video to them when they visit YouTube  

#### [0:10:30](https://www.youtube.com/watch?v=9Fn79qJa2Fc&t=630) |  because we don't have any signals at

that point that they are there on YouTube to learn how to build a work bench. So, how to content often gets more views from search. Music on the other hand often gets more views from playlist or mixes because that's how people listen to music on YouTube is often through autoplay or playlist. News content often gets more views from the homepage because we have a breaking news shelf there and that's how a lot of viewers who are interested in news discover content.  

#### [0:11:00](https://www.youtube.com/watch?v=9Fn79qJa2Fc&t=660) |  And so if you see different traffic

source mixes, video to video, don't worry about it. It's completely normal. It depends on the type of content and how the viewer really is engaging with this type of content on YouTube, but just know that viewers discover videos in different ways and that's completely normal. So if you learned anything from this section, I hope it's that you understand that YouTube's recommendation system is designed to find videos for viewers and not viewers for videos.  

#### [0:11:30](https://www.youtube.com/watch?v=9Fn79qJa2Fc&t=690) |  And what I mean by that is,

sometimes creators have a perception that the recommendation system pushes out or promotes videos to viewers. And in reality, the system is designed to work the opposite way where a viewer visits youtube.com and then our recommendation system pulls in and then ranks the best candidate for that viewer depending on the page that they're on. And so, it is a viewer focused system. So that's all for this first video. In the next one, we're gonna cover what factors influences how many impressions your videos receive  

#### [0:12:00](https://www.youtube.com/watch?v=9Fn79qJa2Fc&t=720) |  and how many people see your video

at the end of the day. As always, keep it real.  