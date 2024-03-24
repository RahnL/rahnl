---
layout: post
title: Geek Moment - Writing a C# program on Azure VM from Nexus 7
date: 2013-11-11 09:08
author: Rahn
comments: true
categories: [Programming]
---
You know the old saying "more exciting than watching paint dry?"  Well, that's what I was doing, sitting in the backyard waiting for some paint to dry while the kids were running around and I had my Nexus 7 on hand. So, what should I do?

Let's create a virtual machine on Azure and write a quick hello world program...All from the Nexus!

Below are the screen shots of what I did...every step of this was done from the little ol' Android. The only thing I've done from the computer was shutdown the VM when I was done, and write this blog post.

I'm using the Remote Desktop client from Microsoft. (<a href="https://play.google.com/store/apps/details?id=com.microsoft.rdc.android">RD Client</a> in the Play store.)

First, in Chrome, connect to the Azure management portal and create a new VM.  Only thing of note here was for some reason, it was kind of tough to scroll to the bottom right to hit the next button in the wizards.  I also went back to set the endpoints for the RDP port to one I know works from my home network.
<a href="http://gonesomewhere.com/wp-content/uploads/2013/11/Create-VM-step-1.png"><img class="aligncenter size-full wp-image-287" alt="Create VM step 1" src="http://gonesomewhere.com/wp-content/uploads/2013/11/Create-VM-step-1.png" width="600" height="375" /></a>

<a href="http://gonesomewhere.com/wp-content/uploads/2013/11/Create-VM-step-2.png"><img class="aligncenter size-large wp-image-288" alt="Create VM step 2" src="http://gonesomewhere.com/wp-content/uploads/2013/11/Create-VM-step-2.png" width="600" height="375" /></a>

<a href="http://gonesomewhere.com/wp-content/uploads/2013/11/Create-VM-step-3.png"><img class="aligncenter size-large wp-image-289" alt="Create VM step 3" src="http://gonesomewhere.com/wp-content/uploads/2013/11/Create-VM-step-3.png" width="600" height="375" /></a>

<a href="http://gonesomewhere.com/wp-content/uploads/2013/11/Create-VM-step-4.png"><img class="aligncenter size-large wp-image-290" alt="Create VM step 4" src="http://gonesomewhere.com/wp-content/uploads/2013/11/Create-VM-step-4.png" width="600" height="375" /></a>

<a href="http://gonesomewhere.com/wp-content/uploads/2013/11/Create-VM-step-5.png"><img class="aligncenter size-large wp-image-291" alt="Create VM step 5" src="http://gonesomewhere.com/wp-content/uploads/2013/11/Create-VM-step-5.png" width="600" height="375" /></a>

Once the VM is created and running, get the IP address from the Monitor tab in the dashboard.
<a href="http://gonesomewhere.com/wp-content/uploads/2013/11/Create-VM-step-6.png"><img class="aligncenter size-large wp-image-292" alt="Create VM step 6" src="http://gonesomewhere.com/wp-content/uploads/2013/11/Create-VM-step-6.png" width="738" height="607" /></a>

Switch to the Remote Desktop Client,and setup a new connection using the IP address from above, along with the public port for the RDP endpoint.

<a href="http://gonesomewhere.com/wp-content/uploads/2013/11/Create-VM-step-7.png"><img class="aligncenter size-large wp-image-293" alt="Create VM step 7" src="http://gonesomewhere.com/wp-content/uploads/2013/11/Create-VM-step-7.png" width="600" height="375" /></a>

Connect to the VM, and enter your credentials you used when creating the machine.

<a href="http://gonesomewhere.com/wp-content/uploads/2013/11/Create-VM-step-8.png"><img class="aligncenter size-large wp-image-294" alt="Create VM step 8" src="http://gonesomewhere.com/wp-content/uploads/2013/11/Create-VM-step-8.png" width="600" height="375" /></a>

Open Visual Studio, sign in, and write a program.
<a href="http://gonesomewhere.com/wp-content/uploads/2013/11/Create-VM-step-9.png"><img class="aligncenter size-large wp-image-295" alt="Create VM step 9" src="http://gonesomewhere.com/wp-content/uploads/2013/11/Create-VM-step-9.png" width="600" height="375" /></a>

<a href="http://gonesomewhere.com/wp-content/uploads/2013/11/Create-VM-step-10.png"><img class="aligncenter size-large wp-image-296" alt="Create VM step 10" src="http://gonesomewhere.com/wp-content/uploads/2013/11/Create-VM-step-10.png" width="600" height="375" /></a>

Presto!
<a href="http://gonesomewhere.com/wp-content/uploads/2013/11/Create-a-VM-step-11.png"><img class="aligncenter size-large wp-image-297" alt="Create a VM step 11" src="http://gonesomewhere.com/wp-content/uploads/2013/11/Create-a-VM-step-11-1024x640.png" width="1024" height="640" /></a>

Afternoon fun, and now the paint is dry.
(I was painting various things for upcoming crafts on my wife's blog, <a href="http://oyveyaday.com">oyveyaday.com</a>, if you want to check it out.)
