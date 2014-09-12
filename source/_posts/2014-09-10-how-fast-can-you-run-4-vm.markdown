---
layout: post
title: "Speed tech: running 4 virtual appliances on your laptop in 5 sec overall"
date: 2014-09-10 11:54:23 +0200
comments: true
published: false
categories:  capstan tools redis tomcat mysql cassandra
---

**By Dor Laor, Tzach Livyatan**

In the following demo, Dor is running 4 different OSv base virtual appliances
on his laptop:

* Redis
* Tomcat
* MySQL
* Cassandra

Each virtual appliance is a full–blown VM, each with a pre integrated
cloud application, and each launched without terminating the others.

<!-- more -->

<script type="text/javascript" src="https://asciinema.org/a/11914.js" id="asciicast-11914" async></script>

As you can see, application boot time take between sub-second
(Reids) to a few seconds (Cassandra) depending on the application.
The Hypervisor plus OS part of the boot time is less than a second for all cases.

Want more info on Capstan and related topics?  Join the [osv-dev mailing list](https://groups.google.com/forum/#!forum/osv-dev).  You can get regular OSv updates by subscribing to this blog's feed, or folllowing [@CloudiusSystems](https://twitter.com/CloudiusSystems) on Twitter.  
