---
title: 'The Riddler: dice rolling'
date: 2020-05-21
permalink: /posts/2020/05/dungeondice
excerpt: "Somehow making Dungeons and Dragons nerdier"
tags:
  - statistics
---

*Dungeons and Dragons* is not just about rolling dice. It's about collaborative storytelling, solving problems creatively, and exercising the imagination. The game has remained popular in the decades since its release for good reason, and during that time it's compiled a large fan base (which includes some [well-known figures](https://en.wikipedia.org/wiki/Dungeons_%26_Dragons_in_popular_culture#Players)).

To be fair, though, dice rolling is very much a big part of it. Most events that take place in the game are dictated by one or more rolls of dice of different varieties (none more iconic than the 20-sided die, or D20), as supervised by the Dungeon Master (DM) whose job it is to craft the imaginary universe the characters inhabit. The more difficult or unlikely the event, the higher the dice roll meeds to be. Want to jump across a narrow stream? Rolling a D20 for 5 or better would probably do it. Want to jump across raging rapids full of flesh-eating piranhas? Maybe to make it aross the target number to beat is 18.

Sometimes, a DM can reward you as a player for being creative. Say you decide to throw some food into the river to distract the piranhas. The DM can give you *advantage* on the river-jumping roll, meaning that you get to roll the D20 two times and pick the higher number of the two rolls to determine your success.

But the DM giveth, and the DM taketh away. She can also give you *disadvantage*, meaning that you roll twice and use the smaller of the two rolls. So if your character twisted their ankle earlier in the adventure, you might have disadvantage when trying to make the jump.

What if we take the idea further and consider what *disadvantage of advantage* looks like? That means that you roll with advantage twice, and use the smaller of the two resulting numbers. Here is a diagram showing an example:

![diagram](/images/for-posts/dungeondice/diagram.png){:class="img-responsive"}

The black numbers correspond to the results of D20 rolls. For each pair of rolls, we take advantage by selecting the higher number to get two green numbers. Finally, we take disadvantage by using the smaller of the two green numbers to get to the final red number. 

This brings us to [last week's Riddler Classic](https://fivethirtyeight.com/features/can-you-find-the-best-dungeons-dragons-strategy/). What is the expected roll you get with either disadvantage of advantage (which I will refer to as DisAdv form now on) or advantage of disadvantage (AdvDis)? And what is the probability of each approach beating a specific target number, \\( N \\)?

Solving these questions exactly can be done using 

![diagram](/images/for-posts/dungeondice/d20.png){:class="img-responsive"}

Simulations and plots
-Plot of probability to roll individual number

![diagram](/images/for-posts/dungeondice/advantage-vs-disadvantage.png){:class="img-responsive"}

![diagram](/images/for-posts/dungeondice/advdis-vs-disadv.png){:class="img-responsive"}

![diagram](/images/for-posts/dungeondice/comparison-all.png){:class="img-responsive"}


Conclusions

Technical Details
------
Math for calculating expected values



