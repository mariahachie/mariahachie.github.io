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
cafeteria interactively. Our team chose to work on a raspberry pi because it was different than the other proposed solutions which were software based. I was tasked with writing the Python code which would count the results. I also ended up working on the hardware aspect because I noticed that the others were too busy to finish the project, and I was interested in trying it out. As you can see from the photo above, a button lights up when you press a button.</p>

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
