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


### Day 1: 2020-12-01

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

### Day 6: 2020-12-01

**Progress:** Worked on another part of the design, which defines mappers for converting message components into the pieces which make up the transaction (like the amount, or the counterparty data). Also worked on refactoring some existing code -- I realized I could use interfaces for any classes that I hadn't yet defined.

**Thoughts:** It was an interesting stream since I got a new random person joining the stream, and I notice that I'm a lot more focused when I know I'm being watched 😁.

The limitation of using an interface as a class substitute (in order to code in that part of the implementation later) is that you can't force any _constructor behavior_. The same applies to abstract classes as neither of them have constructors in the first place. I ran into this issue with the `Money` class I was trying to implement, because I needed the behavior that limits the decimal scale to 2 at construction time.

Some interesting definitions: _Scale_ refers to the number of places after the decimal point, while _precision_ is the number of significant digits, or digits that matter (precision is counted in TOTAL, not just for the ones after the decimal point). 180.25 has precision 5 and scale 2, while the same number with precision 2 and scale 5 would be 1.80000E2 (I think).


**Link(s) to work:** Temporary Twitch VOD is at https://www.twitch.tv/videos/821572414. I'll add the YT link as soon as I'm able to export it.

----------

### Day 7: 2020-12-02

**Progress:** Wrote what looks like _most_ of the rest of the code for the Thing-That-Generates-Transactions, which I've helpfully titled `TransactionGenerator` (until I can think of a better name I suppose). Also a bit more refactoring. The refactoring is really an ongoing thing, I guess I should stop mentioning it.

**Thoughts:** I was *really* sleepy this morning, and I guess it showed because I took twice as long to think about what I was trying to do than I normally do. It's hard to switch to being a morning person. Guess I still need practice.

I seem to be hitting some kind of mental roadblock with the path forward. Probably time to hit the iterative design pit stop again and work on refining my mental idea of the implementation.

**Link(s) to work:** Temporary Twitch VOD is at https://www.twitch.tv/videos/822809189. I'll add the YT link as soon as I'm able to export it.

----------

### Day 8: 2020-12-03

**Progress:** Completed the Kotlin katas! 2 short sections, one on Builders and one on Generics. I thought I might be able to divert some time to MockK, but no such luck.

**Thoughts:** Kotlin has _a lot of features_. Right as I neared completion of the exercises, I saw whole _sections_ of concepts in the documentation which were not even mentioned in the katas. Good lord.

Also generics are incredibly complicated to understand and I will be tackling them tomorrow.

Something I learnt: _Receivers_ are objects on which methods are called. So if you call `a.foo(b)`, `b` is a parameter, but `a` is the receiver. Useful terminology for understanding extension functions.

**Link(s) to work:** Temporary Twitch VOD is at https://www.twitch.tv/videos/823953049. I'll add the YT link as soon as I'm able to export it.

----------

### Day 9: 2020-12-04

**Progress:** Based on the katas yesterday, I decided to take a deeper look at the concept of Generics in Kotlin and Java. Did almost all of the Generics stuff, except for [Star Projections](https://kotlinlang.org/docs/reference/generics.html#star-projections).

**Thoughts:** The ideas are fairly complicated, but in essence I got a few takeaways:

* If you're only gonna _output_ a particular generic type `T`, mark it as `out T`. This is the _producer configuration_.
  * You can now use any `T` or its subtype while reading from it.
* If you're only gonna _input_ a particular generic type `T`, mark it as `in T`. This is the _consumer configuration_.
  * You can now use any `T` or its supertype while writing to it.

I don't think I've still fully been able to define what covariance and contravariance are, but I'm getting there. I got completely stuck at Star Projections though. I'll be tackling that again tomorrow.

Interesting note: Java arrays are _not_ invariant, which means that `String[] extends Object[]`.

**Link(s) to work:** Temporary Twitch VOD is at https://www.twitch.tv/videos/825060401. I'll add the YT link as soon as I'm able to export it.

----------

<!-- Add missing entries here! -->

----------

### Day 13: 2020-12-08

**Progress:** The core of the application is mostly complete. Some exception conditions remain to be tested, but for the most part it's expected to work.

**Thoughts:** MockK is pretty fantastic. I'm still trying to get the hang of how to work with it, but so far it's been great for isolating the behavior of dependencies.

**Link(s) to work:** 

----------

### Day 14: 2020-12-09

**Progress:** Little break from the project, today I did Day 1 and 2 of [Advent Of Code](https://adventofcode.com). All in Kotlin, of course 😄

**Thoughts:** AoC puzzles are _so fun!_ This is the textbook example for how to write good questions that test your logic and programming basics, while at the same time not focusing too hard on minutiae of performance and convoluted algorithms. I'm really having fun with this. Also, it's pretty incredible what Kotlin can do with its extensive standard library of extension functions. For example:

```kotlin
"aaaabbb".count {it == 'a'}  // returns 4
```

**Link(s) to work:** 

----------

### Day 15: 2020-12-10

**Progress:** 

**Thoughts:** 

**Link(s) to work:** 

----------

### Day 16: 2020-12-11

**Progress:** 

**Thoughts:** 

**Link(s) to work:** 

----------

### Day 17: 2020-12-12

**Progress:** 

**Thoughts:** 

**Link(s) to work:** 

----------

### Day 18: 2020-12-13

**Progress:** 

**Thoughts:** 

**Link(s) to work:** 

----------

**Skipped 2020-12-14 due to work running incredibly late.**

----------

### Day 19: 2020-12-15

**Progress:** 

**Thoughts:** 

**Link(s) to work:** 

----------

### Day 20: 2020-12-16

**Progress:** Completed AoC Day 10, and half of Day 11. So essentially we did one question, but half of one and half of another.

**Thoughts:** Day 10 Part 2 was a _very_ interesting question, in that it _requires_ memoization to solve! Otherwise it runs on and on forever. With memoization it actually completed almost instantaneously (less than half a second in Kotlin). That's pretty amazing.

Day 11 Part 1 has an interesting problem layout. Will be fun to solve Part 2 tomorrow morning.

**Link(s) to work:** 

----------