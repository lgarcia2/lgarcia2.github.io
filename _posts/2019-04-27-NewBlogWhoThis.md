---
layout:            post
title:             "New Blog, Who's This"
date:              2019-04-26 10:00:00 -0400
tags:              Jekyll Github Hexo Integration Deployment Blog
category:          Non-Technical
author:            lgarcia
---

## I've made a new blog! Again!

Every blog of mine starts out with a post like this. So why not continue the pattern? Yes, it is very redundant to keep making different iterations of blogs every couple years. However, I'm hoping this time its different (said everyone). All of my previous blog iterations have generally been custom solutions. That is, in order to hone and practice my developer skills, I've implemented various web frameworks in order to come up with a blog that works for me. The good news is that I definately gained knowledge and experience from the process. The bad news is that since they were custom solutions, it wasn't always the easiest to contribute to my own blog. I'm hoping that by avoiding custom work and switching to an established solution, contributing and keeping up with the blog will be easier. Basically, I'm trying to make the barrier to entry easier, hoping that I'll contribute more.

## Introducing Jekyll

I chose [Jekyll](https://jekyllrb.com/) as my 'established solution'. Its an application developed with Ruby that takes markdown, along with some style information, to generate a static website. The main idea being that a person could write their blog posts in markdown and use Jekyll to quickly interpret and serve the content on a website. For me, the 'pros' are that its easy to work with, easy to contribute to, and has a lot of support. Unfortunately, there are some 'cons' as well. If I'm hosting a static site, its hard to embed 'dynamic' behavior. A few years ago, again, to practice my developer skills, I made my own version of a url shortner like [bit.ly](https://bitly.com/). Unfortunately, since this is a static site I am unable to embed and host some of my projects like that (You can read more in the Github Pages section).  With that in mind though, I can always host a project somewhere else and link to it if needed. So in the end, the restrictiveness of a static site wasn't a very big 'con' to me. However, there was another major 'pro' in using a static site: hosting.

## Github Pages

A major feature of [Github](https://github.com/) thats come out in fairly recent history has been their Github Pages concept. In essence, if you commit static web files to a repository in Github, you can configure the repository in such a way that Github will host the static website for you. Given that Github is free (for personal use) this is a great way to host a website for free. If we go back to my running 'pros' and 'cons' list, this is a pretty good 'pro'. It also continues the ease of contribution since all I should need is Jekyll and an internet connection to contribute.

## A Note On Integration

One of the big concepts being used in modern development is Continuous Integration/Continuous Deployment (CICD). Unfortunately, one of the things I havent quite worked out yet, is how to better improve my deployment pipeline. For example, in writing this post and pushing it live, I have to have Ruby, Jekyll, and Git installed, I have to run Jekyll against the new markdown file, and finally push the new generated site to Github. I have Git, and will continue to have Git installed on all my machines but I'm not a Ruby developer. That is, Ruby and Jekyll are definately a dependency that I don't work with on a day to day basis. As such, my desktop is the only machine I currently have running Jekyll. This restricts me to contributing to the blog only when I'm on my desktop or when Ruby and Jekyll are installed on a machine I'm working with. This isn't very portable so CICD is something that I'd like to improve upon going forward. That is, I'd like to be able to commit changes and have the site automatically generated and re-committed so that I only have to worry about committing to Github.

## Thoughts on Jekyll Alternatives

In picking which static site generator I had also tried [Hexo](https://hexo.io/). Instead of relying on Ruby, hexo uses a Node package. So if you're not a fan of Ruby, or have different dependencies to manage, Hexo might be a better option for you. In my experience, it does seem more flexible. However, it also seems more verbose and a tiny bit cumbersome. I've spent an equally small amount of time with both Jekyll and Hexo so there are definately things I haven't come across in both options, but either should work for getting a blog up and running quickly with Github pages. There are more static site generators than these two, but since I haven't worked with them I won't comment.

## Final Thoughts

I'm sure I'll have more opinions as I continue writing posts and continue to work with Jekyll, but so far my experience has been great. I've been able to customize this site to my hearts content and have not run into anything in my way. I hope that going forward, I achieve my goal of contributing more to this blog and that Jekyll helps in that regard.

