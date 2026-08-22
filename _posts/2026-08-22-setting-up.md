---
title: "Setting up"
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags:
  - micro:bit
  - plans
---

Welcome to **Sarah and Bibliobot** 👋

I, **Sarah**, will be starting my MSc Information and Library Studies course next month, and plan to use this blog to keep track of my learning and improve my writing. I will be accompanied by my trusty friend **Bibliobot** on this journey, because robots are obviously the best companions.

<!--more-->

Bibliobot is a BBC micro:bit controlled robot, but does not yet have a physical body! I have build micro:bit robots many times in the past, both to use with young people in workshops, and to fight (badly) in Robot Wars style battles. So the code is ready, the electronics have been tested, I just need to put it together and give Bibliobot a super-cute face.

I plan to build Bibliobot in the next couple of months (once I have cleared some space by working through a big pile of craft supplies!), so for now, imagine the cute face with this small snippet of code:

```ruby
from microbit import *
while True:
    if accelerometer.is_gesture('shake'):
        display.show(Image.ANGRY)
        sleep(1000)
    else:
        display.show(Image.HAPPY)
```

Visit the [Python editor](https://python.microbit.org/) to run it on a simulated micro:bit.