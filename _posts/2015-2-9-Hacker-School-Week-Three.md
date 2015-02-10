---
layout: post
title: Hacker School&#58; Weeks Three to Five
---

#### Preramble
At the end of [my previous post](/Hacker-School-First-Two-Weeks/) I was already into my fourth week at Hacker School. I'm currently at the start of my sixth week as I'm finishing this. Hopefully this gives my future self and others some perspective on my Hacker School experience.  
<br>
>I'm guessing at a certain  
point the years stop  
mattering and life is  
more appropriately  
measured in decades

There is the feeling as one gets older that time starts to accelerate and the need to split up time into small chunks is no longer necessary. It's a bit like one's age being measured in days, then weeks, then months, and finally years. I'm guessing at a certain point the years stop mattering and life is more appropriately measured in decades.  
<br>

This is going to be long so I totally understand if you  
![didn't read LOL!](/images/didnt_read_lol.gif)

#### Week 3
##### SICP
Most of the people who started the [Structure and Interpretation of Computer Programs](http://en.wikipedia.org/wiki/Structure_and_Interpretation_of_Computer_Programs) (SICP) class at the start of the batch have pretty much given up on it at this point. The learning curve on it is so steep that the experience is more painful than rewarding. I will definitely revisit this at some point when I'm more familiar with [Clojure](http://clojure.org/) so that I'm not struggling with learning Clojure at the same time that I'm trying to do conceptually difficult things in it.

##### Blog
The week started with spending time on writing and learning how to style the blog. I managed to style and write most of the first blog post, but got distracted and stopped working on it toward the end of the week.

##### Machine Learning
The excellent [Stanford Machine Learning course](https://www.coursera.org/course/ml) taught by Andrew Ng started this week. I managed to get through the first week's lesson in one day, but the material is also pretty easy at this point.

>the project has  
grown to a point  
where eventually I  
have to break it out  
into separate files

##### L-Systems
I finished some of the interaction for this project and presented it during Thursday presentations. The code is in one giant > 500 line Javascript file and no frameworks were used. While this was good for learning and rapid development, the project has grown to a point where eventually I have to break it out into separate files. Dealing with UI is also complicated and annoying enough that I plan to handle the UI using [React](http://facebook.github.io/react/index.html).

#### Week 4
##### Project Euler
I was a bit bummed out about dropping SICP. The machine learning course is an involved endeavor and was just starting. It was getting a little tiring only working on the L-Systems project, so I wanted something more bite-sized with fast rewards. People in the previous batch are in their job search phase and they're practicing technical interview questions, so it got me thinking about doing something similar.  
<br>
I remembered doing [Project Euler](https://projecteuler.net) many years back. It's a site where there are programming/math problems that you can attempt to solve in any way you want. If you manage to solve a problem you get to see a forum where you can post and discuss solutions to that problem with other people who have solved that problem.  
<br>
When I last worked on Project Euler problems, I did them in [Python](https://www.python.org/). There are many other people programming in Python here and I haven't touched the language in years. So I figured I would try doing them in Python again. I managed to get through the first 18 problems during the earlier part of the week. It scratched my bite-sized project itch and served as a good refresher for Python basics.

##### Blog
Yay! I finally finished my [first blog post](/Hacker-School-First-Two-Weeks/) about my Hacker School experience!

![L-Systems Tree](/images/l-systems_001.jpg)

##### L-Systems
I finally broke out the one large Javascript file into separate files. I'm using [Gulp](http://gulpjs.com/) as my build system. The files are separated out into [NodeJS](http://nodejs.org/) style modules and reassembled using [browserify](http://browserify.org/). After all the files are combined, they're compressed using [uglify](https://github.com/mishoo/UglifyJS2) for faster loading.  
<br>
You can play around with the tree L-System above <a href="http://emilng.github.io/l-systems/index.html#XL/X:F-[[U]+X]P+F[+FXL]-X,F:FF,L:X-UXPL/F,d-1.8;+,a29.7,d0;-,a-10.7,d2.4;[,b0,a0;],b1,a110.5;U,d-1.9,b0,a-57.5;P,b1,d9.3;L,d0.4,a-169.5/6/x80,y267,a110,i6">here</a>

##### Resident
[Scott Vokes](https://atomicobject.com/culture/scott-vokes) was the Hacker School resident for this week. I didn't get to interact with him very much, but we did manage to grab lunch together. He has really interesting experience with distributed and embedded systems so it was nice to have exposure to these domains that I'm not as familiar with.

#### Week 5


![L-Systems Tree](/images/l-systems_002.jpg)
##### L-Systems
>The code is much clearer 
and cleaner now

The UI has been rewritten with React. The code is much clearer and cleaner now. I've also managed to figure out how to handle some more nuanced interaction behaviors that I've never dealt with before. I presented this project during Thursday presentations and I think it went well. The remaining work on this project is to polish interactions. It's probably at 80 or 90 percent complete, but the saying goes that it takes 80 percent of the time to finish the last 20 percent of the work.  
<br>
You can play around with the above L-System <a href="http://emilng.github.io/l-systems/index.html#F/F:F+F-F-FF/F,d3.8;+,a164.7;-,a-79.64/6/x78,y285,a151,i5">here</a>

##### Resident
[Sam Tobin-Hochstadt](http://homes.soic.indiana.edu/samth/) was this week's resident. I attended several of his talks and learned about his work on [Typed Racket](http://docs.racket-lang.org/ts-guide/) as well as how [JIT compilers](http://en.wikipedia.org/wiki/Just-in-time_compilation) work.

##### Blog
A large chunk of this huge post was written this week.

##### Machine Learning
I finished the second week of lessons, but still have to do the programming homework. Things are still going well so far...

#### Next Steps
The previous batch is ending in a week. So there will be new people to meet and learn from which is great but also a little sad, because I don't know if I'll see some of the people in the previous batch again.  
<br>
I'm really glad I at least got a fairly large project to a mostly finished state through the first half of my batch. The next project that I want to work on is something with web audio which I've never worked with before so that should be fun!




