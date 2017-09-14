---
layout:     post
title:      "Raspberry Pi Survey Machine"
subtitle:   "my first foray into hardware"
date:       2017-01-20 12:00:00
author:     "Mariah Achie"
categories: "project"
header-img: "img/rpi-led.jpg"
---
<p>During my co-op placement at Toyota, our national manager challenged our department to collect survey results in the
cafeteria interactively. Our team chose to work on a raspberry pi because it was different than the other proposed solutions which were software based. I was tasked with writing the Python code which would count the results. I also ended up working on the hardware aspect because I noticed that the others were too busy to finish the project, and I was interested in trying it out. As you can see from the photo above, an LED lights up when you press its corresponding button, registering one vote.</p>

<a href="#">
  <img src="{{ site.baseurl }}/img/enter-question.jpg" alt="Enter a question" width="50%" style="display:block; margin: auto; padding-top:40px"/>
</a>
<span class="caption text-muted">Step 1: Enter a question and press the "Enter" button.</span>
<a href="#">
  <img src="{{ site.baseurl }}/img/question.jpg" alt="How's it going?" width="50%" style="display:block; margin: auto; padding-top:40px"/>
</a>
<span class="caption text-muted">Step 2: Question displays on the screen with appropriate labels. Click the physical buttons to respond to the survey.</span>
<a href="#">
  <img src="{{ site.baseurl }}/img/results.jpg" alt="Results" width="50%" style="display:block; margin: auto; padding-top:40px"/>
</a>
<span class="caption text-muted">Step 3: Click on the "Results" tab and view the results!</span>

<p>All in all, I really enjoyed working on this project and it'll be put to good use in Toyota's head ofice. I used Python Flask and a few open source JavaScript libraries for the UI, and SQL lite to save the answers. I also had some fun with wiring the circuits, as seen below:</p>

<a href="#">
  <img src="{{ site.baseurl }}/img/switch.jpg" width="75%"  style="display:block; margin: auto; padding-top:40px"/>
</a>
<span class="caption text-muted">Don't mind my dad's hand!</span>
<a href="#">
  <img src="{{ site.baseurl }}/img/inside-rpi.jpg"  style="display:block; margin: auto; padding-top:40px"/>
</a>
<span class="caption text-muted">Really messy, but at least the circuits work</span>

<p>I applied my knowledge of threading so that I could program the RPi to count votes while also displaying the UI. I also used object oriented features of Python to create a class to store a survey result, instead of using a global variable to store one survey at a time. In theory, more than one device should be able to control the RPi if connected to the same Wi-Fi network and the IP address typed in. I didn't get a chance to do stress testing as it wasn't a priority and the team only needed a POC, but it would be interesting to see how the Pi handles multiple devices concurrently.</p>
