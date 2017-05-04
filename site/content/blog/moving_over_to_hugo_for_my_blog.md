+++
date = "2017-01-08T10:04:42-08:00"
title = "Moving over to Hugo"
keywords = ["static website generator","hugo"]
description = "Moving over to Hugo for my website."
removecomments = false
draft = false
images = [""]

+++

I've had several false starts on blogging over the years. I usually get caught up in blogging for companies. 

This year I made a commitment to blog for myself and be more active in branding myself online. I've chosen Hugo as the platform. I took at look at several other web and blogging platforms from medium to Wordpress. I found myself graviating towards static website generators as I didn't want to deal with all the security headaches that come with managing a database backed website like WordPress, especially when my main use case is to ocasionally write. 

For my last company, I used [ExpressionEngine](https://expressionengine.com/) which is a very capable system, although it too requires more maintenance than I wanted to deal with. Medium is extremely easy to use, but you don't own your own traffic. So it's great to syndicate a perspective of your content to their audience but it may not materially affect your own website in terms of traffic and certainly not rank. 

In the end I found myself drawn to Hugo. Static generators are faster in general compared to their database backed bretheren. But Hugo is written in Go which makes it incredibly performant. I also liked the fact that it is a single binary and you don't need to an expert to install it. 

When packaged with build tools, it also very easy to use. Blog posts are done in markdown. And because it's hosted on GitHub it benefits from git version control. For this particular blog, I'm using the Victor Hugo Build Template provided by Netlify so I can quickly push new blog posts and have the site rebuilt in seconds.

One of the perceived potential downsides with this setup is that at first glance it's a bit more CLI heavy and scary to novice users - but I find it much easier to use overall. I draft my blog posts in advance using MacDown and sometimes IAWriter and then just push them when I'm ready.

I still remember WordPerfect and using codes to write your documents. I've never been a fan of GUI tools for writing as I find they distract you from actually writing content.

The one area where they shine is in getting multiple contributors to author content. As a sole writer for this blog this has never been an issue. And for small companies, forwarding the markdown and image files to a user isn't much overhead at all. Even then, we're starting to see a lot of innovation in this space with regards to to GUI based front ends to static webstite generators like Contentful.

Expect the layout and design here to change. I'm not using a theme on this site, although many are available. lean and pure CSS FlexBox.