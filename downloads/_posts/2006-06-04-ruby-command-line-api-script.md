---
layout: post
date: 2006-06-04 
author: bsag 
title: "Ruby command line API script" 
categories: [downloads] 
comments: true
sharing: true
footer: true
---

Version: newTodo.rb

[File URL](/assets/code/newTodo.rb.zip)

Damien Cirotteau has written a nice Ruby script to add a new next action from the command line. He writes:

<blockquote>
<p>
I have set up a small ruby script to add a Next Action in tracks. All the parameters (user name, token,...) are written in hard in the script and configurable from the command line. Instructions are in the script or run "newTodo.rb -h". I use it mainly to add todos from the command line and from my Mail application.
</p>

<p>
In the process of reorganizing my (digital) life I have also changed my mail application from Mutt to Sylpheed. Sylpheed lets you define custom actions. One of mine that I apply to a message for which I am waiting a reply is shown below. Context 6 is my waiting for context:
</p>
</blockquote>

<pre>
<code>
newTodo -c 6 "Waiting from`cat %f|grep From:|sed -e 's/^From://'` about `cat %f|grep Subject:|sed -e 's/^Subject://'`" [0]
</code>
</pre>

Thanks, Damien! 
