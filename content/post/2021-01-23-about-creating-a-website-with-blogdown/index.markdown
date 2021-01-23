---
title: About creating a website with blogdown
author: ''
date: '2021-01-23'
slug: []
categories: []
tags:
  - blogdown
  - R Markdown
---
<div style="text-align: justify"> 

_This post gives a brief overview of this website and what resources were used to create it._

<!--more-->
### About this website and a small note

This website was created with the R package [blogdown](https://github.com/rstudio/blogdown) and uses the [Rocinante](https://github.com/mavidser/hugo-rocinante/) theme. It is hosted on Netlify and is accessible via an [rbind.io](https://support.rbind.io/about/) URL. And it wasn't all that hard thanks to the tools listed in the remainder of this post. 

This overview does not go into technical aspects, nor is it a step-by-step tutorial. There are already plenty of these, written in a more understandable way than I ever could.[^1]
Rather, in the following I present those books, websites, blogs and other resources that made it easier for me to create a website (or rather made it possible in the first place). This is by no means a complete list of all the useful information available on the subject, but merely the materials I used.  

At the beginning a brief disclaimer: I have not read any of the books in their entirety. Mostly, I skimmed the first few chapters and then went directly to the chapter that I thought would provide answers to my questions. Whether this was the most efficient approach I cannot judge in retrospect - perhaps I would have saved some time if I had consistently read a book from beginning to end. On the other hand, my approach showed me how wonderfully helpful the R community is; more on that later. But now to the really interesting things!

### Getting Started

To begin with, I would like to refer to the most important book by far for me on the subject: [blogdown: Creating Websites with R Markdown](https://bookdown.org/yihui/blogdown/) by Yihui Xie, Amber Thomas and Alison Presmanes Hill. It served as an excellent starting point for my project. From the installation, over a quite motivating example for the start, up to the deployment of the website and advanced topics. This book was the first one I used when I was interested in building a website with blogdown - and I don't know if I would have actually approached the project without it. 

Another useful resource was [Making a Website with R and the Blogdown Package: Step-by-Step](https://makingwebsiteswithr.rbind.io/) by Deniz Çivril and Clinton Merck. I found this site to be very practical and written in a way that makes it easy for beginners to understand. The many graphics and gifs definitely made it a fun read. But even the most fun eventually passes - I reached this point when I wanted to put my website online. 

I remembered the recommendation in [blogdown: Creating Websites with R Markdown](https://bookdown.org/yihui/blogdown/deployment.html) which favored hosting static websites with Netlify. And since I didn't want to manually upload my public folder to Netlify every time I changed something on the site, I decided to look into GitHub. Which was a rather bold decision, as I was to discover later on. For me, [XKCD](https://xkcd.com/1597/) hits the nail on the head here:

![For me, XKCD hits the nail on the head here.](git_xkcd.png)

For my GitHub adventure, I found another book very useful: [Happy Git and GitHub for the useR](https://happygitwithr.com/) by Jenny Bryan, the STAT 545 TAs and Jim Hester. Without prior knowledge, I was able to start quickly and implement what I had in mind.

At this point I would like to highlight one thing in particular: the content presented here is available free of charge on the internet. I think it is absolutely fantastic that the authors listed are making their works available for free and I would like to thank them very much for this. And especially in this last step, I often consulted other resources to answer questions: be it on [StackOverflow](https://stackoverflow.com/questions/tagged/blogdown), blogposts or anywhere else. I think without all these active authors, questioners and question answerers it would have taken me much longer, because most of the time someone already had the problem in the past and a solution could already be found somewhere. 

### A few concluding words

There are a lot of good reasons to be confident and tackle your own website project, even as someone who's just getting started with R. Because even though it can be a frustrating project at times, I found the process of creating it very rewarding. It motivated me immensely to be able to see the result right away! And if you're still not encouraged, check out this great lightning talk on ["Becoming an R blogger"](https://rstudio.com/resources/rstudioconf-2020/becoming-an-r-blogger/) by Rebecca Barter at rstudio::conf 2020.

[^1]: [This comment](https://support.rbind.io/about/) in particular led me to write this post here:
      > If you have received help from the Rbind community, please consider giving back in the future by helping newcomers after you know more about websites and become familiar with blogdown.

</div>

