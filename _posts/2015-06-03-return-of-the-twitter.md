---
layout: post
title:  "Return of the Twitter"
date:   2015-06-03 00:07:00
categories: portfolio blog twitter
---
So, at the behest and social pressure of the existence of social networking, I decided to reclaim [my twitter account][tweettweet]. 

This reminded me of something I worked on a long time ago for school. It was basically my first foray into technology and computer science as of college.

I was an engineering student at the time, and I was getting tired of the usual bullshit, so I got involved with the faculty and their interests. I got conscripted to help manage a project for tracking the usage of my university's transit (Buses. Yay.) system. The problem was that there were too many inconsistencies in the data, and not enough results to be derived. 

So, we (me and two other engineering students) had about 30 students at our disposal, and they all were handed paper forms because *this was how we'd always done it*. They were told to go get on buses and count how many people get on and off, and then hand in those forms. 

I hate using paper.

So. My solution: I came up with a way to aggregate data using a zero budget communication engine. Because text messages can be used to tweet and practically all students have texting now, I created a bunch of twitter accounts and offered for people to point their phones at them. Then, I created a master account that aggregated all of those tweets via 'following' them. Using cUrl to pull the posts down through the twitter API, I generated some XML files. By enforcing a relatively strict data format and applying a little regular expression magic, I was able to gather data paperlessly with zero investment, and provide accurate and delicious analytics. 

That was probably the first taste of web technology that I ever had. And I loved it.

[tweettweet]:      https://twitter.com/unarmed1618
