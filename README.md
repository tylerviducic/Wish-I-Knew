# What I Wish I Knew When I Started Doing Experimental Nucear Physics

## Introduction

The idea for this document came during a conversation with Sean Dobbs in which I was lamenting that I finally, in year 7 of my PhD, started implementing good software practices into my analysis workflow. While it's better that I learned and used these things later rather than never, I was frustrated that extremely useful and important practices such as, "writing functions", and, "using github" weren't taught to me when I joined the ODU Nuclear Phyiscs research group. Now, It's not Dr. Amaryan or Dr Kuhn's fault - it's not their job to teach us these things; their job is to teach us physics, not software engineering - but it is frustrating nonetheless.

During the aforementioned lamenting, Sean told me:

> maybe if you have time, you should write a short presentation or wiki page of "software things I wish I had known when I started out as a grad student", to help others out

This document is my attempt at that. While thinking about knowledge I wanted to pass on to the newest generation of ~~underpaid code monkeys~~ graduate students, I realized that the scope of that "wisdom" extends beyond good coding practices. 

To whomever reads this, I hope you find it useful. It's not comprehensive, and it's not gospel. It's just a collection of things I wish I knew when I started doing experimental nuclear physics.

## The Basics
Welcome to the world of experimental nuclear physics! When you tell your family/friends/enemies/strangers what you do, the first thing that they will ask you inevitably will be "oh so like, making bombs?" 

No, not like making bombs. 

What we do, day to day, is *write code*. Signifigantly less impressive, huh? Your typical work day will be spent  writing code to perform a host of tasks. That code can be data analysis, data acquisition, data simulation, or any number of other things, but you will be writing code. This is your life now. 

Many, though not all, of course, are not really prepared for this reality. Many, though not all, have fairly limited programming experience, especially *practical* experience - what we do obviously goes beyond:
```cpp
cout << "Hello World!" << endl;
```
So my absolute first piece of advice is this: **learn to code**.

### Learn to Code
Learning how to code, not just learning how to use `ROOT` or `GEANT4` or whatever it is your project will require, is, in my opinion, vitally important. Understanding the basics of programming, and how to write good code, will make your life much, much easier in the long run. When I say learn to code, i mean learn the underlying concepts of programming, not just how to use a specific language. And "learn to code" implies that you should learn to code *well*. 

// TODO: maybe rework this a little to highlight OOP and clean code principals

This may not be true for every advisor. This may not be true for *most* advisors. But anectodtally, I've found that most students are pushed for **results** when they start their research project. This isn't bad, per se, but experience has taught me that this may not be an optimal strategy. For example, the first code I ever used during my PhD was written by an older student who was doing a similar project to the one my advisor envisioned for me. For *over a year*, I spent most of my mind changing numbers in that code and running it. It would take over an hour to run each time and I wouldn't really do much between the these small "knob turns", as I called them. That is a lot of wasted time. My advisor, understandably, wasn't overly happy with how long very minor updates took, but at the time I didn't know how to fix it. It wasn't until I started working on a software service project for CLAS12 with Gaggik Gavalian that I really learned not only the underlying pricipals of Object Oriented Programming, but how to write good, clean code. 

This was a pretty "lifechanging" experience for me. Suddenly, I saw ways to improve on that script I spent a year changing numbers in. I saw ways to make it faster, more efficient, and more flexible. I saw ways to make it more readable, and more maintainable. I saw ways to make it better. And I did. I rewrote it. It was faster. I was absle to produce more results in less time. I was able to do more science. It wasn't perfect by any stretch and I was still making many mistakes I look back on and cringe at, but it was better. If I had learned how to code first instead of just pressing for preliminary physics results, I would have saved myself (and my advisor) a lot of time and frustration.

ROOT, which is probably the library you will be using for your research, is great. It's powerful and convenient. But if you don't understand Object Oriented Programming, you're really going to struggle to use it to its potential. Understanding what a Class is, what an Object is, what funcitons are, what pointeers are, what inheretence is, will all make you **better** at using the library because you'll understand the concepts the library is built on. You will be able to leverage more of the library more effectively, and in the long run, do much more science.

So, take some time when you start your research project and really just learn how to code. 





