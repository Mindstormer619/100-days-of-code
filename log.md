# 100 Days Of Code - Attempt 3 - Log

We're on Attempt 3, and I fully plan to go the distance with this one. No slacking!

I'm livestreaming this _entire_ thing on [Twitch](https://twitch.tv/mindstormer619). Catch me on stream to say hi, ask questions, provide criticism (literally anything goes as long as it's constructive), and learn! 😄

<!--
### Day 0: February 30, 2016 (Example 1)
##### (delete me or comment me out)

**Today's Progress**: Fixed CSS, worked on canvas functionality for the app.

**Thoughts:** I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality.

**Link to work:** [Calculator App](http://www.example.com)

### Day 0: February 30, 2016 (Example 2)
##### (delete me or comment me out)

**Today's Progress**: Fixed CSS, worked on canvas functionality for the app.

**Thoughts**: I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality.

**Link(s) to work**: [Calculator App](http://www.example.com)


### Day 1: 2020-11-27

**Progress:** 

**Thoughts:** 

**Link(s) to work:** 

----------

-->

----------

### Day 1: 2020-11-26

**Progress:** Worked on the design approach for the core of Plutus.

**Thoughts:** I'm starting a new project, an expense manager Android app written in Kotlin, a language and environment I'm not completely comfortable with. I actually started some basic setup and code for this a few days prior, but I realized that I hit a roadblock with what I wanted to attempt pretty quickly. I figured that the best way to gain some direction was to plot out a basic user interaction for one of the core aspects of the app.

**Link(s) to work:** https://youtu.be/EvzzWFSnXfg

----------

### Day 2: 2020-11-27

**Progress:** Implemented a regular expression parser for parsing incoming purchase/credit notification messages and extracting useful fields. The regex parser works on the basis of capture groups.

**Thoughts:** The initial implementation is going to be a bit unfriendly to the user, but it allows us to get off the ground quickly. I'll be using an interface which generalizes exactly how a Message Parser is implemented, so we can get more implementations of it later on and allow the user to select at runtime.

**Link(s) to work:** Temporary Twitch VOD is at https://www.twitch.tv/videos/817469850. I'll add the YT link as soon as I'm able to export it.

----------

### Day 3: 2020-11-28

**Progress:** Today I chose to pause the project work and instead spend a couple of hours on [Kotlin Koans](https://play.kotlinlang.org/koans).

**Thoughts:** Since I'm (relatively) new to the nuances of Kotlin, I figured I could spend some time understanding the _innumerable_ language features, and some of its oddities. Kotlin is certainly a language for the experienced programmer.

Found some interesting information about the language, including the fact that SAM-lambda conversions (SAM = _Single Abstract Method_) only work on SAM interfaces, **not** SAM abstract classes.

**Link(s) to work:** Temporary Twitch VOD is at https://www.twitch.tv/videos/818484105. I'll add the YT link as soon as I'm able to export it.

----------

### Day 4: 2020-11-29

**Progress:** Did another set of the Kotlin katas -- today's were specifically on Collections. After that, I spent a bit of time mapping out the next part of Project Plutus, the transaction mapping (which takes in a set of text components extracted from the message, and maps them to the Transaction object which is to be persisted.)

**Thoughts:** Kotlin has a _ton_ of different features for collections -- all sorts of operations on sorting, mapping, folding (basically `reduce`, except it starts with an initial value instead of the first element of the collection), max/min operations, the works. It's possible to reduce vast amounts of Java code to incredibly concise Kotlin.

Interesting thing I learnt: Java functions cannot be called from the Kotlin side using _named parameters_, because apparently the JVM bytecode is not guaranteed to preserve function parameter names.

**Link(s) to work:** Temporary Twitch VOD is at https://www.twitch.tv/videos/819637072. I'll add the YT link as soon as I'm able to export it.

----------

### Day 5: 2020-11-30

**Progress:** Today I went over another leg of the Kotlin exercises (they call them Koans, but those aren't koans dangit), specifically the one around Properties. Struggled a bit with understanding Delegates, but I get it now. About precisely 1 hour of work.

**Thoughts:** I intended to do a bit more on the main project today, but having shifted to morning streams, I had to cut it off after an hour in order to start my regular work day. Hopefully from tomorrow I'll be able to wake up a bit earlier so I can go on for a bit longer. It's hard switching habits to that of a morning person 😁.

Delegates afforded the most amount of trouble for me. One thing I understood was that a delegate for a mutable property most likely needs to maintain some kind of internal state of its own. The topmost example given in the Kotlin documentation is _terrible_ for understanding how Delegate setters function, and should probably be changed. I'll think about adding in a PR for updating that.

**Link(s) to work:** Temporary Twitch VOD is at https://www.twitch.tv/videos/820533114. I'll add the YT link as soon as I'm able to export it.

----------
