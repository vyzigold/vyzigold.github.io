---
title: Thoughts on my keyboard layout after a few years
categories:
- Other
comments: true
feature_image: "https://vyzigold.github.io/placeholder.jpg"
---

I'm using a [Programmer Dvorak](https://www.kaufmann.no/roland/dvorak/) keyboard layout since the beginning of 2019, so a little over 6 years. I thought it'd be interesting to take a look back go over my reason of learning a non-standard layout and some pros and cons I encountered over the years.

## Why did I start using Programmer Dvorak?

I had multiple reasons. Back then, I already went through 6 years of education in IT / computer science. I spent a lot of time behind the computer, writing code, usually in C. But even though I went through touch typing courses, I couldn't touch type properly with QWERTZ (we use QWERTZ in Czech instead of QWERTY). My writing style was kind of an "6 fingers, one eye on the keyboard one eye on the screen". After writing like this for so long, I was decently fast and comfortable writing like that. And every time I tried to "touch type" correctly with all 10 fingers, I grew bored of it very quickly as I was just so much slower and it took so much more effort, so I never learned to touch type on QWERTZ.

In early 2019 I bought a new laptop and I thought that if I want to do programming as part of my job, I need to completly change the way I interact with computers. I need to become much more effective at everything I do. This meant learning to touch type (so typing faster and without looking at the keyboard), learning VIM as my main text editor and switching to i3 as my window manager with vim-like shortcuts for literally anything. I also tried to switch to control my webbrowser 100% from the keyboard.

In order to finally learn to touch type, I had to make it hard to use my "hunt and peck" style of writing every time I grew bored of learning to touch type. This meant switching my layout to something not QWERTZ, ideally something that's different from what's fyzically labeled on my keyboard, so that I can't "hunt and peck" even if I tried. So I ended up configuring my new laptop to use the Programmer Dvorak layout and for a few months, I didn't create any convenient way to switch to any other keyboard layout, thanks to which I made it as inconvenient as possible to switch to my old way of writing. If I wanted to use a different layout, I always had to open a terminal and type a few commands to do that. This was the main and I think a pretty good reason to switch to a non QWERTZ/Y keyboard layout.

The other reasons are pretty dumb. Why "Programmer Dvorak" and not some other layout? Because I'm a programmer and it sounds cool! At least to 6 years younger me. I literally came across an article about the Programmer Dvorak layout, didn't do any other research and thought "Cool, I'm gonna learn that".

{% include figure.html image="https://vyzigold.github.io/assets/programmer_dvorak.jpg" caption="Visual aid for learning the layout I made. I used to put this above my screen." %}

## What I don't like about Programmer Dvorak?

There are multiple things I don't like very much and if I was to start learning the layout today, I'd certainly make a few modifications. But since I already learnt the layout, I'm OK with it as is.

#### Numbers
The upper number row looks like this: 7531902468. This is so dumb and I see 0 usefulness in this. Unfortunatelly I don't write numbers often enough to learn to touch type these keys without needing to think about them at least a little bit. What I ended up doing is learning that "number 7 is written by pressing the key with number 2 as the label and so on" and I just look at the keyboard. I think I see a pattern in the numbers. Odd numbers on the left, even on the right. But why is "9" suddenly in the middle? So yea, if I was to start learning the layout from the beginning, I'd rebind the number row.

#### Ctrl+C, Ctrl+V
The "C" and "V" letters are on the right half of the keyboard, so this shortcut either requires you to use both hands or use the right Ctrl key. This makes it hard to use your mouse to highlight something, "Ctrl+C" it, click somewhere else and "Ctrl+V". You need to move your right hand 3 times: highlight -> move hand to the keyboard -> Ctrl+C -> move hand to mouse -> click to somewhere else -> move hand to the keyboard -> Ctrl+V.

#### Moving the cursor in VIM
I wrote, that VIM is my main text editor. I actually started with VIM a little before switching to Programmer Dvorak. In VIM you usually use the keys "hjkl" to move the cursor across lines and characters. On QWERTZ, these keys are right next to each other on the home row on your right hand. On Dvorak, these keys are spread all over the keyboard. This feels pretty natural to me now, since when using VIM, I have both hands on the keyboard anyway, but at the beginning, this was really annoying.

#### Need to configure it everytime
I'm now really used to the Programmer Dvorak layout. I can't really type without it very well. But unfortunatelly this layout isn't available on all distros out of the box and needs additional installation / configuration. Using normal Dvorak isn't enough, since a few keys have different positions between Dvorak and Programmer Dvorak layouts.

## What I do like about Programmer Dvorak?

But of course, there are a lot of things which I like about the layout. Here are a few:

#### Special characters
All the special characters are very easily accessible. This is especially true in comparison with QWERTZ, where you need Alt + <something> for almost everything. On Programmer Dvorak, the number row is by default (without the need to use the Shift key) used for special characters, because while writing code, you're probably writing braces and so on more often than numbers. The semicolon is at the spot of the letter 'Q' on QWERTY, which is making it really easy to reach, which is especially helpful with C like languages. The quote characters are on lower left corner of the keyboard (instead of letter 'Z' or 'Y' depending on layout), so it's also easy to reach.

#### A little better spread of the letters
One thing I never understood about QWERTY is, why you have a semicolon under your right pinky when you just lay your hands on the keyboard. That's one of the most easily reachable key, so it should be used to type some often used letter. On Programmer Dvorak, we have the 'S' character on that position. Also all the vowels are on the left side of the keyboard, which should cause you to switch between which hand is typing a letter more often, resulting in lower stress and faster typing in comparison with writing long sections of a word with a single hand. I haven't done any measurements on that, but if that's true, then it's cool.

## Final thoughts
While the Programmer Dvorak layout has some flaws and I might pick a different layout if I was about to start again, I think it was really helpful in learning to touch type. Without switching to this layout, I'd still "hunt & peck", I'd be slow when writing and I'd need to always keep an eye on the keyboard. So overall I'm glad I made the decission back then and made the switch to a different keyboard layout.
