---
layout: post
title: "Intuitive Interpretation of Confidence Interval"
date: 2020-07-26
---

## 26 July 2020 &nbsp; &nbsp; &nbsp; Personal website launched 

Over the past few weeks, I have been trying to figure out how to interpret confidence intervals. Specifically, I wanted to understand why a statement like "there is a 95% probability that the population mean is within this calculated confidence interval" is wrong.  It seems that even some people who teach statistics for a living also have this question. The common explanation is that, once a sample is drawn and the CI is calculated, either it contains the population mean or it does not. One person on YouTube uses the ring toss game to explain. A 95% CI is similar to a ring with the size that will ring the post 95% of the time. Once the ring is tossed, either it catches the post or it does not. Hence you cannot say there is 0.95 probability that it has caught the post.  

<p>But this explanation got me thinking: say I play a “blind” ring-tossing game with a host. The rule of this game is that I must turn my back to the post when tossing the ring. This means, after I have tossed s a ring, I do not know if the ring catches the post or not. Now, I pick a 95% CI ring and toss it. The host asks me to estimate the probability of the ring having caught the post. Based on the fact that 95 times out of 100 the ring will catch the post, my subjective belief should be 0.95.  

<p>After thinking about this example for some time, an idea came to me: a 0.95 CI involves two steps of randomness: the ring size (which is random) and the tossing (also random). A 0.95 CI means that the COMBINED effect of these two random steps is 0.95. Therefore, once the first step is taken (ie the ring size is fixed), you cannot say the probability of the second step (tossing) is 0.95. 

<p>I am not sure if this intuitive explanation is correct (probably not), but for now I will assume it is correct and put side this problem which has been bugging me for a long time. 
