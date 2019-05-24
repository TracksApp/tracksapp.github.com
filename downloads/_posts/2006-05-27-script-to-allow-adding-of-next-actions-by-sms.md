---
layout: post
date: 2006-05-27 
author: bsag 
title: "Script to allow adding of next actions by SMS" 
categories: [downloads] 
comments: true
sharing: true
footer: true
---

Version: sms_todo.pl

[File URL](/assets/code/sms_todo.pl.zip)

<p>Eric Lesh has written a great Perl script which you can use from a mobile phone by sending an SMS or email containing the details of the action to add. In his words on the mailing list:</p>

<p>&#8220;Tracks has been great to me, but too often I find myself without a computer when I have to write down something important.&nbsp; I am lazy, and suffer from my-Moleskine-is-too-nice-to-write-in-itis, so usually.&nbsp; I just don&#8217;t write anything down at all. Since I usually have my cell phone, and it can send emails through SMS, this seemed the ideal candidate for adding next actions.&#8221;</p>

<p>&#8220;To make it work, add a procmail recipe like so:&#8221;</p>

<pre>
<code>
 :0:
 * ^From:.*MYNUMBER@MYPROVIDER.COM
 | /path/to/sms_todo.pl
</code>
</pre>

<p>&#8220;With Evolution, Mail.app, Outlook, or whatever else you use for mail, there is probably a way to do this also.&nbsp; Just pipe the email through the script when it comes from your phone.&#8221;</p>

<p>&#8220;Messages should be in the format:<br />
Email Bill about TPS reports.&nbsp; Context computer.&#8221;</p>

<p>Thanks, Eric! For those who might not know how to send an SMS to an email address, you probably need to check your provider&#8217;s site for details, but for T-Mobile UK, I found that I could send an SMS to 191 in the following form:</p>

<p>email@mydomain.com#Email bill about TPS reports. Context computer.</p>

<p>&nbsp;</p> 
