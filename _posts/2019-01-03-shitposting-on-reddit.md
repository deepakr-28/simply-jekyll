---
title: optimum time to shitpost on reddit
tags: Data-Analysis
comments: true
---

This post was inspired by a friend of mine who analyzed the price difference between Amazon and eBay to get you the most savings on purchases using an extension called unlooted, which is a very cool read and you should check it out!

**Disclaimer**: I have made a lot of assumptions from my analysis of this data. There is high probability it might be subjective and biased. Please do point out in the comments if you have anything to add or correct.

So now onto our task at hand. Why would you want to time your posts? Definitely to increase the reach and the upvotes you get. But Reddit is not a mainstream social media like Facebook or Instagram. It’s a mostly anonymous social media where communities collectively exist. So why would you possibly want your post to reach the front-page? From the top of my head, a few logical options would be

* You’re a bot and you want to hijack peoples mind and spread false propaganda.

* You’re seeking validation by amassing the imaginary points (karma) which the community gives you as upvotes.

* Your “meme” is a disguised product advertisement which would fetch you a lot more sales if you somehow managed to make it into the front-page.

Okay, now we have a motive to get to the front-page and all that remains is the how-tos of getting there. So I made this considerably easier for you by flexing my new analytical skills and some visualizations. But remember, at the end of the day, this would only give your post a marginal advantage. If your post isn’t good enough for the community, it wouldn’t take off.

## Some Heads-up

So as a prerequisite, you need to understand Reddit and it’s userbase. Reddit is occupied mostly by **North Americans** (45%), the most popular subreddits like **r/worldnews**, **r/tech**, **r/dankmemes**, **r/economics**, also reflects this user composition. Most of the time, it is the content from these established subreddits that make it onto the r/all. Our analysis would only cover the process of getting into the front-page from one of these popular subreddits.

![Source: [Statista](https://www.statista.com/statistics/325144/reddit-global-active-user-distribution/)](https://cdn-images-1.medium.com/max/2000/1*oMwR892YVbkWXJyXclandw.png)*Source: [Statista](https://www.statista.com/statistics/325144/reddit-global-active-user-distribution/)*

The data was gathered using the PRAW package and the free [pushshift.io](https://pushshift.io/) API. You can view the scrapper that I wrote [here](https://github.com/isht3/ShitePost-Analysis/blob/master/scrap-bot.py). The data I collected had over 100,000 post instances collected over a period of the first 3 weeks of December.

Reddit database uses the UTC timezone so all of the analysis is done on UTC timezone itself.

## ***Weekday Analysis***

We’ll be looking into the data of one such active subreddit, **r/dankmemes**. It has over 1.5 million subscribers and receives over 3000 memes (shitposts) per day. It peaks out on the weekend where it rises to 5200 and hits lows on Wednesdays. I’m assuming we can safely, to an extent, take the insights that we observe on this subreddit and generalize it to the popular part of Reddit.

![Count of posts](https://cdn-images-1.medium.com/max/2000/1*COimEkKcYjhVlfO7yd8gFg.png)*Count of posts*

This behaviour is expected. People are more active during the weekend and during the middle of the work week, everyone is too brain tired to upvote and make memes.

![](https://cdn-images-1.medium.com/max/2000/1*XTTUvUUCbTlg-YzBLBCzEw.png)

But don’t be fooled, even though the average number of upvotes on a post is around 600, about 90% of the posts get **less than 1000** **upvotes **and doesn’t see the light of the front-page. In total 20% of the posts don’t even get more than a single upvote.

![](https://cdn-images-1.medium.com/max/2000/1*CYYPc28jFChEPraP6YGOoQ.png)

## Time Series Analysis

Let’s start looking at the trends during a typical day. This is where things start getting really really interesting, and I had to make some assumptions on why things are such, but feel free to correct me in the comment section if you got anything to add.

If we look at the time series graph during the day, we can see a downward-trend where there is a **three-fold decrease **in the content posted. So this is where the country demography of the platform becomes very prominent. Because for the active majority of Reddit it’s too early to be active (North America).

After that, we can see an increase in the frequency as people really start shitposting from about 1 pm to 10 pm. Fair enough to assume that people have more time and energy to make and post stuff later in the workday.

![](https://cdn-images-1.medium.com/max/2000/1*598DE0hNL420HVSlj6FjOw.png)

***But…***

If we look at the average upvotes during the day, counterintuitively the demand for posts actually increases during the downtime of 5 am to 12 pm, which we take away from the steep rise in the average upvotes during this period, where it literally **quadruples **for posts, even though a good portion of Reddit is inactive. People want more content during this time but there is a deficiency of that, which I’m assuming is due to a good portion of the content creators (North Americans) are either sleeping or on their morning commute but the demand for content stays the same due to the other part of the world being active during this time.

![](https://cdn-images-1.medium.com/max/2000/1*2dqErFZvBKFDk0290y358A.png)

So the takeaway is that

* There is a very distinct content gap which needs to be filled on Reddit during the time period **5 am to 1 pm UTC** because the global demand for content stays the same but a good portion of the content creators isn’t very active.

* You have a higher chance of getting upvotes if you post during the depression period to fill in the content-needs of 50% of the world and you can, statistically speaking quadruple the reach of the post.

* The night time is the most competitive time to post as there is a surplus amount of posts available to fit the demand but there is enough traffic to consume that information.

After this partial 6-hour content downtime, we can see the count increasing again signifying that people aren’t being productive in the office.

So the general consensus? You could take lessons from these trends to optimize the timing of your posts on Reddit, but I’d just ignore these and just focus on making original, entertaining and informative content which is assured to get recognition anyway irrespective of time or day.

In my original Notebook, I’ve made a much more detailed analysis of the data. Feel free to check that out and adapt my scrapper and notebook on any of the subreddits to gain insights and let me know what fun things you find out! Also, if have some cool ideas that I should do a similar analysis of, drop it in the comment section!

[https://github.com/isht3/ShitePost-Analysis](https://github.com/isht3/ShitePost-Analysis)
