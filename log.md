# 100 Days Of Code - Log

<!--
### Day 0: February 30, 2016 (Example 1)
##### (delete me or comment me out)

**Today's Progress:** 

**Thoughts:** 

**Link to work:** 

-->

### Day 1: January 3, 2017

**Today's Progress:** Learnt and coded some flexbox CSS on www.flexboxdefense.com. Got to Level 9 today.

**Thoughts:** Flexboxes aren't too hard, but this tutorial probably isn't covering all of it. I'll need to know enough of it to implement an upcoming project.

**Links to work:** ![flexbox defense](http://i.imgur.com/A4O2Mlu.jpg)

----

### Day 2: January 5, 2017

_Skipped yesterday due to traveling the whole day._

**Today's Progress:** Finished flexboxdefense! Wasn't too hard overall. Also started on my new project, Ultimate Tic Tac Toe.

**Thoughts:** Okay, flexbox *definitely* is harder than flexboxdefense shows. Tried making a simple 3x3 grid using flexbox, failed miserably, ending up with something that looks nothing like a grid. Will check out [CSS Tricks' exhaustive guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) for more information tomorrow.

**Links to work:**
- Flexbox Defense: ![complete all levels](http://i.imgur.com/WOiHIan.jpg)
- [Ultimate Tic Tac Toe prototype grid](https://github.com/Mindstormer619/ult-ttt/commit/2f4695b1ed0918c99c5b56107931d84e7b3991c6)

----

### Day 3: January 6, 2017

**Today's Progress:** Did something different today! Taught basic HTML, CSS and JavaScript at a college gamedev workshop. We're building (a simple version of) the Chrome dino game!

**Thoughts:** Teaching code is great fun. Also quite exhausting. Also wrote a crapton of other code today, but unfortunately those have to be in private repositories at the moment.

**Link to work:** Unfortunately, no links today. I'll add the link to the repo when it goes public. My anonymized contributions should be visible on my Github graph, however.

----

### Day 4: January 7, 2017

**Today's Progress:** Completed [Flexbox Froggy](http://flexboxfroggy.com). Also taught how to make a simple version of the [Chrome Dinosaur Game](https://gitlab.com/mindstormer619/chrome-dino) in a six-hour workshop at MEPCO-Schlenk Engineering College, Sivakasi - TN (India).

**Thoughts:** Even more teaching today! The workshop basically continued from the previous day, and concluded today. Pretty much totally exhausted, so I didn't have much time to learn much more about flexboxes. Flexbox Froggy contains a bit more stuff to it than Flexbox Defense does (see Day 1), so learnt more flex properties (`flex-flow`, `flex-wrap` and `align-content`). Also it contains twice the number of levels, so that's great.

Tomorrow I'm mostly free from commitments, so I'm planning on spending a lot more time working with flexboxes. Also gonna read those guides I've linked earlier.

**Link to work:**
- Flexbox Froggy: ![froggy completed](http://i.imgur.com/JeZUI5c.jpg)
- Chrome Dino (I made this a few months ago, but pretty much live-coded this again during the workshop): https://gitlab.com/mindstormer619/chrome-dino

----

### Day 5: January 8, 2017 (more like 9th, it's really late right now)

**Today's Progress:** Made that freakin flexbox grid I have been trying to make for SO LONG! Lots of trial-and-error later, I finally got *exactly* what I was looking to create today. 

**Thoughts:** Initially the whole thing was pretty hit-and-miss. I was trying a lot of stuff, and nothing was really looking the way I wanted it to, or used some weird hack that didn't exactly set things correctly. (Technically even now I'm using *one* weird hack, but if you know of a non-hacky way to make something look *square* using plain CSS, please let me know).

But now I think I'm getting the hang of it. And the whole thing's great fun now :smile:

**Link to work:**

I've quick-hosted the output [here](http://spider.nitt.edu/~darthsid/flextest).

The code is part of [this repository](https://github.com/Mindstormer619/ult-ttt) -- the commit is linked [here](https://github.com/Mindstormer619/ult-ttt/commit/5510ef706ea950e6397d31605fafa2fd22c75b06).

----

### Day 6: January 9, 2017

**Today's Progress:** Made a full Ultimate Tic Tac Toe grid using flexbox, completing that which I was halfway through yesterday. The grid now looks glorious:

![ULTIMATE TIC TAC TOEEEEEE!!!](http://i.imgur.com/esbh8wC.jpg)

Also more small changes on the server side of things. I'll be using socket.io websockets to communicate between the game players and the server.

**Thoughts:** Truth be told, there wasn't *that* much progress today. Heart was just not in it. Spent most of the day procrastinating over other stuff, so I'm pretty sure I could have finished a lot more in the time I took to do this today had I spent a little more time earlier reading up some prerequisites rather than just winging it along. Tomorrow will be a better day.

I'm pretty sure I'm getting the total hang of flexboxes though. They're super-neat.

A two-player game is a fairly complicated application. I'll have to spend some serious time planning how the client-server interaction works out and how I can minimize the amount of stuff that needs to be done on the server to keep it zipping through games.

**Link to work:** I merged the code back to master in a nice little squashed commit, so it's right at [this commit](ac1ea3d959f0e974dc482e63d854d1eec2b358d4) showing only the nice result and not the PITA trial-and-error I had to do to get here.

OSHIT I JUST REALIZED deleting the PR branch would make some of the previous links I've sent up here moot. I'll see what I can do about it.

----

### Day 7: January 10, 2017

**Today's Progress:**
- Read about [JWT authenticated sockets](https://auth0.com/blog/auth-with-socket-io/) and played around with them a bit.
- Taught about basic relational database modeling and concepts during a two-hour seminar at my local college coding club.
- CRed (Code Reviewed) a bit of code from an ongoing project that some of us are working on.

**Thoughts:** Overall, a productive day for the most part. However I didn't have the time to advance my own projects much today. I seriously need to stop beginning working on these so late at night lol.

**Link to work:** I've got no links right now because the actual amount of written code at the end was virtually nil. Will put an update once I make the actual authenticated sockets for the UTTT game.

----

### Day 8: January 11, 2017

**Today's Progress:** Fiddled around with getting Handlebars partials to work. They just did not. This took really long smh.

**Thoughts:** I've gotta start getting used to this. I mean it's not like this is the first time I'm coming across libraries that have cryptic documentation... but I tried way too long and something about this is just not making any sense and I'm beginning to wonder why what I'm doing is so complicated to accomplish when it really should not be.

The main problem I'm finding with Node is that (aside from being built on JavaScript which is fundamentally an absolute scum-of-the-earth language) many packages are expected to work with each other a lot but have extremely limited documentation on how you get that actually done. Take for example, express with sessions, socket.io with express (for which I literally had to look at another [*repository*](https://github.com/onedesign/express-socketio-tutorial) made by someone who complained about exactly the same thing), handlebars with express (the HBS documentation describes stuff using handlebars as a standalone frontend JS object, not as an express-integrated Node library)... the list goes on. (Wow I just noticed that all of those have Express in them. For something that's supposed to integrate with a lot of other stuff the number of working examples available is notoriously small.)

Most of the time, getting it to work is a trivial deal involving a couple lines of extra configuration. But the problem is _when that is not documented, the configuration **ceases** to be a trivial deal_. It becomes a much longer process of looking at online tutorials and examples and StackOverflow and asking fellow devs who've managed to get it work in the past.

This is getting ridiculous tbh. For those who might want to help, what I'm trying to do is really simple, which is include a handlebars partial within the main layout page (which contains the HTML `<head>` section), however the partial itself (containing a JS script) is defined in an inline fashion inside the `index.hbs` file. For more context, the commit is linked below.

**Link to work:** The commit is linked [here](https://github.com/Mindstormer619/ult-ttt/commit/531a0ce65eecd3f78cfcdcd6f07f53de7620768a). If you're good at Handlebars (especially in Express configurations), you're welcome to help. I'm [@Mindstormer619](https://twitter.com/Mindstormer619) on Twitter.

----

### Day 9: January 13, 2017

_Skipped yesterday due to illness._

**Today's Progress:** Made a working prototype of authenticated websockets on socket.io! _feelsgoodman.jpg_

**Thoughts:** This felt great. Development felt right for once after quite a while. Maybe I'm just not a frontend person lol.

I'm still trying to flesh out the details of the game itself, but at least the stuff I'm prototyping is actually working the way I expect it to. Though socket.io's documentation is not the *best* I've seen, it's workable at the least.

There'll soon be a point where I'll have to focus less on the code itself and more on the game architecture. Development will be slower on those days. Hopefully pseudocode counts in the 100DaysOfCode Challenge :smile:

About Handlebars... I have a friend who knows how to work with partials. Just waiting for a couple days for him to be available to help me with it. For now I don't intend to waste any more time fiddling around with something I only have a half-assed chance of getting to work.

**Link to work:** Commit linked [here](https://github.com/Mindstormer619/ult-ttt/commit/ecf5d1d7ffee966ba6fff57febe2028021420486). I also just started a channel on Telegram where I have automatic updates for the `ult-ttt` repository. Reach out to me on [@Mindstormer619](https://t.me/Mindstormer619) if you want in on the live notifications.

----

### Day 10: January 14, 2017

**Today's Progress:** Successfully made a blank WebGL canvas, unsuccessful attempt at putting a 2D object in there.

**Thoughts:** **_WOO CHALLENGE COMPLETION 10% ONE TENTH THERE WOOOOOOOOOOO_**

_Ahem._

Okay, WebGL is _difficult!_ There's so many _numbers_ and magic constants and weird abbreviated functions and scripts in other languages and graphics jargon and math and so many other weirdybits. This was totally unexpected. I thought I could break from UTTT and have a nice chill coding session doing some monkey-see-monkey-do from Mozilla's [MDN pages on WebGL](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API/Tutorial) but nonononononoooo shit has just *got* to fail on me left right and center.

Heck I'm pretty sure I have exactly the same source code as their demo source... I pretty much put a two-pane view and checked them side-by-side and couldn't find anything wrong. But hey, their code works and mine... doesn't. Canvas remains as black as ever.

And all this effort to get a freakin white square on the screen. Add to that the fact that I understood only about 40% of what I was doing. Most of this flies over my head and the main issue seems to be that they assume you're familiar with OpenGL already (which I'm not, so it's more like *my* issue, but why would I blame myself amirite?)

I've had it with this. I'll look into more detailed WebGL tutorials later, when I feel up to it. Tomorrow, perhaps, I'll look into some libraries that will hopefully ease things up. Not really *looking* to learn graphics programming in depth at the moment, more like getting something specific to work... so a library will do.

**Link to work:** Commit linked [here](https://github.com/Mindstormer619/webgl-experiments/commit/332fdf875d618dcb535afc868313ec28a3ff351c). Most of the content is ditto from [this page](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API/Tutorial/Adding_2D_content_to_a_WebGL_context) (in fact, I would argue that it's *all* the content, not just most of it. BUT IT IS NOT WORKING.)

----

### Day 11: January 15, 2017

**Today's Progress:**

Made a basic working threejs demo referenced in [threejs documentation](https://threejs.org/docs/index.html#Manual/Introduction/Creating_a_scene). Also made a couple of modifications to ensure that I'm really understanding what I'm doing. Thankfully it worked.

**Thoughts:** Man, this is so much easier than raw WebGL code. It's beginning to look like I can use ThreeJS for the other WebGL project I have planned (which will also go up on my Github, worry you not).

Stellar documentation on that software right there. I'm a graphics programming noob but I still got virtually 100% of what I coded.

**Link to work:** Commit linked [here](https://github.com/Mindstormer619/webgl-experiments/commit/bda740acb3c19f8678864dc6cbad67be259dc4d0).

----

### Day 12: January 16, 2017

**Today's Progress:** Made a swinging mouse-controllable cylinder thingy using ThreeJS. Halfway there for the main project I'm aiming to complete!

**Thoughts:** This was fairly easy. I'm gonna spend some time reading more tutorials, docs and blogs to try and figure out exactly what goes into making ThreeJS models look exactly the way I want them to. Also there's physics to worry about, which I'll have to look into.

But yeah, today's work specifically was pretty damn simple. Hopefully I can get a full prototype of what I want to make ready by next week.

**Link to work:** Commit linked [here](https://github.com/Mindstormer619/webgl-experiments/commit/10a394ce40ddeee3e54fd8b70b8b3ad2f0c15744).

Here's what it looks like in action:

![Simple movable rod](http://i.imgur.com/mRfVwDU.jpg)

Yeah, I know, it looks like nothing much. The actual running thing is slightly more impressive :grin:

----

### Day 13: January 17, 2017

**Today's Progress:** Solved a problem from Reddit's [r/dailyprogrammer](https://reddit.com/r/dailyprogrammer) instead of that usual project I'm working on. Good to change things up once in a while.

The question is [here](https://www.reddit.com/r/dailyprogrammer/comments/5llkbj/2017012_challenge_298_easy_too_many_parentheses/).

**Thoughts:** This problem was... interesting. Not too difficult, but it's definitely not what I would call an "easy" problem, as the question maker has marked it. Spent a good half hour thinking about how to get at the solution and whiteboarding various approaches. Or probably I'm just not as good at it as others are.

![shrug](http://i.imgur.com/DGCDjV3.jpg)

I *am* really happy with the way I approached the problem though. In hindsight it still seems like the most logical way to tackle the problem, so that's that. I'll add an explanation readme to the solution gist sometime later.

**Link to work:** Solution is [in this gist](https://gist.github.com/Mindstormer619/5fc6c558138546fd90fc3c5bfdeec023). Hit me up directly if you want to discuss it. Would recommend tackling it without looking at the solution first.

----

### Day 14: January 25, 2017

I'm back after a _loooong_ break! My laptop hard disk met with a nice little dose of catastrophic failure and filesystem corruption, so here I am after several (quite fruitless) attempts at recovery, `chkdsk`ing and finally shredding all the HDD contents and installing a fresh Ubuntu image. Whew.

Technically this is Day 15: I *did* work on something on the night my HDD decided to die on me. But I don't exactly remember what it was, and I have a feeling it wasn't much, so I'm not counting it.

**Today's Progress:** Made some progress with the two-person socket communication that's instrumental for `ult-ttt` to work. It's nothing complete yet, but at least I have a clear picture of things moving ahead.

**Thoughts:** Today I spent a good deal of time rubberducking and whiteboarding stuff, and it helped immensely in clarifying my own thoughts about how to proceed. I've listed out (albeit a bit haphazardly) what I have on my general approach to this. The full thing isn't completely fleshed out yet, but that's just a matter of time.

**Link to work:** Gist linked here: [Two Person Socket code](https://gist.github.com/Mindstormer619/6bf5a2a9ca7a4f98da24712fb6512645). I'll commit and push it when it gets a bit more complete so I can actually test things.

----

### Day 15: January 27, 2017

Okay, I totally skipped yesterday. I have no excuse, I simply got caught up with other stuff and totally forgot about my code hour till it was way too late. I had a couple hours of coding done in the morning yesterday, but that's part of a project I consider "work" and not something that I personally *want* to do, so I'm not counting that. So yeah, I did skip a day for pretty much no reason. This will never happen again.

**Today's Progress:** Today I had simply *epic* progress. I completed a working two-person communication system using websockets! This feels so great.

**Thoughts:**

So yeah, I found that once I get into the swing of things, I can really get immersed in the process. Like I spent two entire hours on this without realizing it. Getting something to actually *work* gives you a great rush. I feel more pumped than I have anytime this whole week :)

*aside*

Shortly before I started today, I went on to find a good Pomodoro timer for Ubuntu. I had [Tomighty](http://tomighty.org/) installed on my previous system, but it turns out (to my great chagrin) that Tomighty is offered on Windows... and Mac. No Linux. Great. The only thing worse than switching OSes is not being able to find software that was on your previous OS. (Speaking of which, if someone can get me Notepad2-mod on Linux, I will be *extremely* thankful.)

The great thing is I finally found this: [Gnome Pomodoro Timer](http://gnomepomodoro.org/). This works fantastically... probably even better than Tomighty did. I really love the neat and clean visuals, and the general simplicity of the app (which was what attracted me to Tomighty in the first place). Also it's got a great bird-chirping thing going on when the timer is on which is really nice ambient music to sit and code to.

*/aside*

All right, back to the regularly scheduled update. Yesterday I felt pretty terrible about myself about totally forgetting to do this. I was pretty sure I had reached this nice habit-forming state now. I guess the tendency to do this late at night and the whole week that I missed due to my machine crapping out took their general toll and I just, well, forgot.

Well, at least to myself, I made it up today. Did quite a bit of proper prototyping and got a nice working two-person socket communication system. This system is instrumental to the Ultimate Tic Tac Toe game that I want to create. I need to clean up the code and make it usable, but hey, at least I know that the general principle works now, and I can go ahead with the actual system.

Again, I cannot overstate how great this felt. Just seeing the thing actually working after numerous different logs and debug sessions... it felt seriously great.

**Link to work:** Please do check it out! The commit is [here](https://github.com/Mindstormer619/ult-ttt/commit/46310a336855246b92479ac1cbff30e6b3620854). Or you could just go to https://github.com/Mindstormer619/ult-ttt and navigate to the `proto` branch. Do a normal `npm install` and run the server. You should be able to communicate between two different browser windows.

I'm gonna try embedding a video demo here below. Dunno if Github markdown supports embeds.

_Okay turns out it doesn't. The video demo link is [here](https://www.useloom.com/share/f9e94050e4dc11e6b14c091dee11d2d4)._

----

### Day 16: January 28, 2017

**Today's Progress:** Did some code-review and documentation work for a project today. Not too interesting, not quite complete, but it's necessary stuff.

**Thoughts:** This is part of an extensive refactor on a project I'm working on. Each time I work on refactoring codebases, I begin to get how much work it actually is. It's something that appears simple at the beginning, but actually isn't easy to measure with respect to how long it's gonna take to complete.

**Link to work:** Unfortunately it's in a private repository as of right now (and I haven't committed those changes yet, they're still very much in progress.) I'll post the update here after the repo goes public.

----

### Day 17: January 29, 2017

**Today's Progress:** More documentation and code reviewing. This can go on for a while; that project is a fairly large one. Also set up and played around with [autosub](https://github.com/agermanidis/autosub).

**Thoughts:** Got a nice solid two hours in today. Pomodoro timers are so darn useful.

I'm currently examining and documenting a database schema and associated models. Did you know that PHPMyAdmin has an excellent DB Designer tool that lets you visualize your database with all its fields and relations, and can also generate a one-click report of the entire thing? I didn't.

Databases are tricky things to refactor. Schema refactoring often means writing new migrations that maintain integrity of the existing data and don't cause any data to disappear. Also it gets trickier when there are more tables because you have to basically check every pair of tables for possible relationships (making it a quadratic-time check). Isn't gonna be too simple.

The autosub thing is for another project of mine (yes, that's a lot of projects. I have even more lined up lol). Today all I did was play around with it, by giving it some audio files that I recorded using [Audacity](http://www.audacityteam.org/). It did way better than I expected it to perform. Seriously fast too.

I fully intend to read and understand its source code over the coming week or so. Updates, as usual, will be here.

**Link to work:** Sadly, no link today as well. A lot of the stuff I do isn't always open-source because of other constraints. But okay, my proof-of-work is to be a matter of public record, so here's a screenshot of our issues page at the moment.

![Issues Page](http://i.imgur.com/ZnlnV6i.png)

----

### Day 18: January 30, 2017

**Today's Progress:** Worked with figuring out and processing XML output from YouTube's timedtext automatic English captions. I think it worked :)

**Thoughts:** Using Python's XML processor wasn't too difficult. Most of the time went in examining the XML file and figuring out its structure so I could use what looked like it was useful out of it.

I took the output of this hilarious video: [STAR\_'s GTA: I Like Killing Jerma](https://youtu.be/dUWEnhDR-88).

This is for the same project as the autosub thing.

**Link to work:** Here's a screenshot of my final Python code and the XML file after quite a bit of tinkering:

![Automatic English caption processing](http://i.imgur.com/KEl79pQ.jpg)

----

### Days 19-20: January 31 & February 1, 2017

**Today's Progress:** Okay, I pretty much forgot to update this log yesterday. What I did today and yesterday are a part of a single project. It involved creating an admin panel with various database access routes for a site I made for a college event. Pretty intensive work. Took *several* hours over the past couple days.

**Thoughts:**

Generally, this is a project that I don't count, because it's something I consider "work" most of the time, and as per the 100DaysOfCode rules, you aren't supposed to count code you write at work. However, the past couple days have been a bit different and I'm counting it because...

1. I've been pretty much totally swamped by this (and one other project. Yes, that's a lot of projects. I currently have five going on simultaneously.), so I haven't had any time to code anything else. Yes, I did spend some time doing other hobbies and stuff, but the thing with coding is that you can't just do it *anytime*, while you're tired or not in the right frame of mind. Code I've produced during those times have almost always required a rewrite.
2. Contrary to the other days on which I code this project, I did learn something (or rather re-learnt something). Turns out I had forgotten about mass assignment vulnerabilities in web development, as well as Express middleware, so these past couple days let me relearn those. I also learnt about hooks and instance methods in Sequelize, which helped me develop my own basic code for protected fields in database models.

So yeah, that's about it. It was a productive couple of days, all things considered.

**Link to work:** Unfortunately, this is closed-source at the moment too. It will be open after the event ends, after which I'll link it here. But here's a quick commit shortlog of all the commits I made over the last couple of days.

![Commits in the last couple days](http://i.imgur.com/EtsbRw6.png)

----

### Day 21: February 5, 2017

_Was traveling for the past three days._

**Today's Progress:** Back on processing captions of YouTube videos! Today I tried figuring out the general structure, and perform a few tests and analysis on YouTube captioning content.

**Thoughts:** Working with Python for tasks like this is great fun. I _highly highly highly recommend_ the excellent software by [Jupyter](http://jupyter.org/), especially the Notebook application, for easy development and documentation of Python scripts and projects.

Learnt how to work properly with the XML module in Python, and also gained some insight into what YouTube's captioning works. Whatever I've figured for now is documented in the notebook.

**Link to work:** Notebook viewable at [this nbviewer link](https://nbviewer.jupyter.org/urls/gist.githubusercontent.com/Mindstormer619/2207b5280856866bd231df8b54b81cba/raw/916d0f7b404e4ba7c0198ab44e6b307f3709d7d6/youtube-timedtext-processing.ipynb).

----

### Day 22: February 6, 2017

**Today's Progress:** This work is part of an upcoming NLP assignment. Since I learnt something while doing it, I'm including it here.

Learnt about a couple NLP-related concepts, like TTR and Zipf's Law while on this. Also learnt how to work with generators on Python.

**Thoughts:** Generators are a bit tricky to understand on first try. They're like functions that return, but _don't_. I guess I have the hang of it now though.

**Link to work:** [Jupyter notebook here](https://nbviewer.jupyter.org/urls/gist.githubusercontent.com/Mindstormer619/b8f4cd43d04150d5b27761aca967e7ab/raw/c04d2e1efd99c2fe339bd4c09ecdc5eeb9d633cb/nlp-stats.ipynb).

----

### Day 23: February 7, 2017

_Filling in for yesterday. Was a bit too tired to fill in the log._

**Today's Progress:** Completed some more from the NLP assignment. *Implemented* Zipf's law, for which I had to revisit matplotlib, and learnt and coded verification of Heap's Law. Also documented the whole thing.

**Thoughts:** Matplotlib is fun lol. Also Jupyter Notebook is the greatest thing to ever be invented.

**Link to work:** [Updated notebook](https://nbviewer.jupyter.org/urls/gist.githubusercontent.com/Mindstormer619/b8f4cd43d04150d5b27761aca967e7ab/raw/4ba505623ae954607327b3f24f106fd2872bd144/nlp-stats.ipynb).

----

### Day 24: February 8, 2017

**Today's Progress:** Today was 100% reading source code and writing documentation for an upcoming refactor. This went on for a solid four Pomodoros, or two hours. So that's 200% reading source code, I guess :)

**Thoughts:** So this is part of that same large codebase refactor I was talking about back on Day 16. We're in the phase of listing out as many issues as we can and making sure our design decisions are agreed upon and documented before moving on to the next stage of refactoring, since the only thing worse than having to rewrite your code is having to rewrite it *twice*.

This is likely gonna take some time. Along with the refactor itself, we're looking at a solid month here.

**Link to work:** Unfortunately, currently private repo. Here's a screenshot of part of the documentation though:

![Refactoring notes page](http://i.imgur.com/RJjq7ZL.png)

----

### Day 25, February 9, 2017

_A quarter way there WOOOOOHOOOOOO_

**Today's Progress:** Implemented the Levenshtein Distance algorithm in Java, following a lot of clean-code principles I learnt in Robert C Martin's book, appropriately titled [Clean Code: A Handbook of Agile Software Craftsmanship](https://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882).

**Thoughts:** This took a while, but felt GREAT. It's been a while since I've felt this good writing code because this was the first time in a while I have seriously made an attempt to write the code in a clean manner.

I figured I'd implement this because it's been a while since I approached some base algorithms, and I read this in my NLP subject syllabus so I decided _why not, it's quick to write anyway_.

**Link to work:** Please do check it out (I love showing off good code, _especially_ if it's written by me): [EditDistance.java](https://gist.github.com/Mindstormer619/55fb4883ac454d154c08252125422c56). Also please send any praise/feedback/improvements/suggestions/criticism [my way](https://t.me/Mindstormer619).

----

### Day 26: February 10, 2017

**Today's Progress:** More documentation work and issue creation. We're up to 19 open issues now, most of which target refactoring and pretty major changes.

**Thoughts:** Documentation work is pretty tiring but also pretty rewarding. I like going over old documentation and commit messages from time-to-time and reading about my own development process and how that's changed over time.

**Link to work:** Again, private repository. Got this sneak peek of part of the documentation I wrote though.

![Part of the refactoring notes](http://i.imgur.com/QzJZ9YM.png)

----

### Day 27: February 17, 2017

_Back after exam week! It's good to be back!_

**Today's Progress:** More documentation work, same site. There's a *lot* to work on.

**Thoughts:** The more I read through the source, the more I see to fix it. Reading Robert Martin's Clean Code helped immensely. I'm seeing myself reason more about my code than ever before.

**Link to work:** ¯\\\_(ツ)\_/¯

----

## Day 28: February 18, 2017

**Today's Progress:** Something different today. Started learning [Vue.js](https://vuejs.org) today! Got as far as completing the Getting Started guide.

**Thoughts:** Vue is definitely _very_ interesting. Seems well-worth checking out. You'll see more of it here soon.

**Link to work:** There's [this fiddle](https://jsfiddle.net/0vu041qw/1/), and then there's also this below. Enjoy.

![kUSj.png](https://uploadit.us/images/kUSj.png)

----

## Day 29: February 19, 2017

**Today's Progress:** Made some good progress towards this other project I'm working on, involving transcripts, captioning and alignment.

I'll add more details here later. So far it's pretty much rough scripting work so it's not exactly well documented. This is big stuff though.

**Thoughts:** Well, it felt great getting something working that I've been thinking about different approaches for about a month now.

**Link to work:** [Notebook link here](http://nbviewer.jupyter.org/urls/gist.githubusercontent.com/Mindstormer619/2207b5280856866bd231df8b54b81cba/raw/350adb5e8a143357674ae23c4af0542fcb0e0a55/youtube-timedtext-processing.ipynb).

----

## Day 30: February 20, 2017

**Today's Progress:** Started on the path for resolving issues over that project I was documenting for several days. Today involved getting some integration tests to work.

**Thoughts:** After-the-fact testing is a little painful to implement :(

**Link to work:** Private repo for now. Will update links later.

----

## Day 31: February 21, 2017

**Today's Progress:** Wrested for about three hours with setting up some performance improvements on aforementioned tests (see Day 30). Unfortunately, it doesn't seem like I got anywhere.

**Thoughts:** Laravel's dependency container seems to be fighting with my PHPUnit for some reason. Hopefully after a good rest I'll be able to see exactly what's wrong.

**Link to work:** --

----

## Day 32: February 22, 2017

**Today's Progress:** Okay, got those perf improvements in!

**Thoughts:** Bash is the greatest thing ever made. Ever.

Man this took me so much longer than it should have. After trying a lot more shit in the direction of getting the framework dependencies loaded before the test `@beforeClass` methods started executing, and failing miserably, all I did was write a simple 3-line script. Problem solved (at least for now).

Tests now run in 41 seconds, down from 4 minutes. That's *huge*.

Also did some other renaming/refactoring stuff.

**Link to work:** --

----

## Day 33: February 23, 2017

_One thirds there!_

**Today's Progress:** Reviewed a lot of code, wrote some more tests

**Thoughts:** Long live the Code Review feature on Github! A most excellent addition.

**Link to work:** Screenshot of a part of the review:

![uySP.png](https://uploadit.us/images/uySP.png)

----

## Day 34-35: February 24 and 25, 2017

**Today's Progress:** One very complex test, lots of database wrangling, and one site deploy that gave me a nice case of the nerves. Many, many hours.

**Thoughts:** I would like to say I have been writing PHP code. I would, however, be more inclined to say that I have been waging a war against PHP. PHP is so, so bad to work with. By God, so bad. Even Laravel, being quite beautiful, can't help you sometimes. It's painful.

It's been a stressful couple of days. I need some sleep.

**Link to work:** Here's a screenshot:

![bPQMy.png](https://uploadit.us/images/bPQMy.png)

----

## Day 36: February 26, 2017

**Today's Progress:** Okay, so that test still isn't passing. Today was one long debugging session.

**Thoughts:** It's not solved yet. I think the error I'm getting is due to some weird differences between sqlite and MySQL in working with data.

Will explore more and come to a conclusion tomorrow.

**Link to work:** Screenshot of the failure:

![screen](https://cdn.img42.com/6b0e34d6582f1ab1184f131875b6f1ec.png)

----

## Day 37: February 27, 2017

**Today's Progress:** Fixed that bug! *YAAAAAAAAAAAAAAAAY!* Found another! *NOOOOOOOOOOOOOOOO!* Pretty sure I know the cause of it! *OKAYYYYYYYYYY!*

**Thoughts:** Good god debugging can be a gigantic pain in the ass. It gets especially worse when you're trying to use a database which you can only interact with via the command line, a half-baked language you don't really understand, and a gazillion different files and DB versions that you keep mixing up. Don't judge me, there've been a lot of changes recently okay!

**Link to work:** Now this is a tricky one. While the test may *look* like it's passing, it's actually not working at all :)

![test or not?](https://img42.com/jHOGo+)

----

_Note: Apologies! I've been pretty swamped by a lot of stuff these past three days. We've had a lot of stuff happening in college, and I've been in a lot of meetings so most days begin with me running off somewhere and end with returning to the room tired as hell. I've done bits and pieces of code over the last few days, nothing serious or targeted to an hour, so I'm not gonna count it. It's on from today!_


## Day 38: February 28, 2017

**Today's Progress:** Finished that damn test. It's a long, complex integ test that checks a fairly major important portion of our application logic.

**Thoughts:** Testing is quite fun! I'm gonna get my feet wet for the first time writing unit tests for a project that *I* maintain (I did write tests at the last internship I did, but that was easier because there already *were* tests that I could get ideas from and I didn't have to think about things like test architecture and stuff.)

**Link to work:** Here's a screenshot of the test as it runs now. It uses this database file, which it downloads automatically if it doesn't have the file locally, off a static server (I gitignore all sqlite files). Then it just proceeds to run the test.

![Test with wget download db](https://img42.com/oUSLz+)

----
