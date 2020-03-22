---
layout: post
title:  "The importance of .inputrc file"
date:   2020-03-22 16:18:35 +0100
categories: shell terminal
---
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight shell %}
$ cat ~/.inputrc 
set convert-meta off
set meta-flag on
set output-meta on
set bell-style none
set completion-ignore-case on
set print-completions-horizontally off
set visible-stats on
set show-all-if-ambiguous on
set comment-begin #

"\e[A": history-search-backward
"\e[B": history-search-forward

"\e[Z": complete

{% endhighlight %}

