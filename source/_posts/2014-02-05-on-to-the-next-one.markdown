---
layout: post
title: "On To The Next One"
date: 2014-02-05 19:35:23 -0500
comments: true
categories: 
---
Well I've finally switched fully off my old VPS with [linode](https://www.linode.com/)! There are
many reasons why I finally chose to do this, chief among them was cost. While at $20/mo it wasn't
exactly breaking the bank, I came to realize I wasn't really **using** it. No one really visited my
[blog](http://web.archive.org/web/20130930150100/http://blog.jeffalwilson.com/) (much like they
won't visit this one), and its main purpose was to host my private Git repositories, serve as a
SOCKS proxy, and serve my mail.

## The Blog ##

My old blog didn't get much traffic. Let me rephrase that, my old blog didn't get much traffic from
humans looking to read my blog. What it _did_ get traffic from was crawlers, or even crackers,
looking to exploit my Wordpress installation. They even succeeded on multiple occassions. For a
random unheard of blog that no one cared about, it was simply too much work to keep up.

Once again I followed the path of my former peer from Virginia Tech
[Ben Hilburn](http://hokietux.net/blog/). Ben had switched to using 
[GitHub Pages](http://pages.github.com/) as a host, and [Octopress](http://octopress.org/) as a
blogging platform. This worked beautifully for me. With this setup, the burden of hosting falls in
the both trusty and capable hands of GitHub, while I'm free to post to my blog in a cozy, Linux
terminal addict friendly way, oh and don't forget everything is versioned with Git! This also means
that my blog is now just a set of static HTML/CSS/JS, very secure, and is still "dynamic" in that I
can easily update it with posts. The only issue was the manner of a comment section, which was
swiftly handled by the Octopress's built-in support for [Disqus](https://disqus.com/).

## Git Hosting and SOCKS Proxy ##

TODO!

## Mailserver ##

TODO!
