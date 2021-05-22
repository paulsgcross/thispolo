---
layout: post
title:  "Greetings"
date:   2021-05-19
comments: true
---
# An introduction
Hi there, nice to meet you.

So, who the hell am I, what am I, and what the even is this blog thing about any way?

Well, my name is Paul. I might be an indie game developer given that I have made a game (almost). Lastly, this blog is going to be a place to post updates and musings on all things relating to the former.

This initial blog post to give a rambling overview on the sort of person I am, some stuff I've been doing, and if you think I have anything worth saying. Later posts will include thoughts on game design and programming challenges. There may even be a spat of creative writing on here too... God help us all.

## Why video games?
I love them. Simple as that. Grew up with them and was inspired by them. My major inspirations are:


- Majora's Mask
- Super Metroid
- Mother 3
- Dark Souls
- Shadow of the Colossus
- Monkey Island
- Kyntt's Underground
- Big Rigs: Over the Road Racing


Do I think games should be fun? Not exclusively. Like any piece of art, the intention is to elicit a particular set of feelings and fun can be one of those feelings.

I also enjoy the challenges that video games present and often find myself wondering 'What makes a good game?' and 'What can I do to help push the medium that little bit further?'

I often obssess over New Ways of Play (NWoP). Probably the thing I like to do most is how can I take a previously defined genre and evolve it in some way. Tinker with it's boundaries a bit. It's a fun excercise and I'm working towards making these ideas real.

## Is you a professional mate?
Do I have professional game or software development experience? No, just grossly passionate and always willing to learn.

## What about your experience?
In terms of game dev experience, I've built my own game with some help from friends. Hopefully it will be released soon. During it's development, I stumbled through several game engines and frameworks until I got something that worked.

I made the aforementioned game in the Haxe programming language. It's relatively young and not as big of a player in the programming world like C++ or Java. But, I like it, and I'll stay with it  for game development. It's nice to see the language grow and it's fun to help contribute to it. Meanwhile, my non-game dev projects are done in Python and C.

## Game design and programming first
Sometimes, programming is often viewed as a means to an end. Understandable. I have a lot of game ideas I want to express but there's this pesky amount of programming ground work I have to do to make that happen... Maybe use Unity, or UE, or another pre-programmed engine?

Early on, I went the route of using other peoples' game engines. What ensued was a nightmare of trying to fit square pegs in round holes. When a project grew in complexity, I suddenly found myself struggling against the foundations laid before me. A bizarre tug of war between what the engine would let me do and what I needed to do for the game. It probably would have been easier to design the whole thing myself rather than finding weird work-arounds and boiler plate fixes on their code. Instead it feels to me that to engineer a game to work exactly as intended, then you need to lay the exact foundations inside the program to support it.

## Principles in programming
Haxe is objected-oriented, so I went off and learnt the [SOLID](https://en.wikipedia.org/wiki/SOLID) principles of object-oriented design. Some open-source frameworks and game engines under-utilise these principles, and ultimately their code-base suffers for it, and their users suffer for it in kind. I would like to avoid this.

I also do not want it to be necessary to read yards of documentation to even understand what a single function does. I want code to be [clean](https://gist.github.com/wojteklu/73c6914cc446146b8b533c0988cf8d29). A monolithic monster function is fine if the project is for your eyes only but not if you want other people to use your tools. Actually scratch that, it's terrible for productivity if you ever decide to take a break. You won't know what the hell anything does. You should be able to understand what something does immediately. It should be readable. It'll save you time in the long run.

Games should also be readily testable with unit tests. [Test-driven development](https://en.wikipedia.org/wiki/Test-driven_development) (TDD) helps you avoid bugs and I hate bugs. Computer bugs are the least cool members of the insect family. I've wasted enough hours playing my game from the beginning just to see if a small change later on would work to realise that TDD is something I would have benefitted from.

## I wanna make good tools
Going one step further, I'm also seeking to create some tools in Haxe that would help alleviate problems often encountered by other hopeful game devs such as myself. So, from this point on, I've decided to do two things:

1. Build an exceptionally flexible cross-platform framework for game development.
2. Avoid generalised all-purpose 'game engines' and instead design bespoke, easily-extensible, engines for a particular game genre at hand.

For 1. the movitation was simple; if you want to take a pre-existing game built on Windows and build it for some new-fangled Video Game Console, you should never ever have to touch the game itself. It should be easier than climbing Mount Everest to create the necessary code to make your game work on a new platform. A framework should be a collection of related tools that let you lay the foundations you need.

For 2. I quickly discovered that projects on all-purpose game engines, such as Unity, tend to get... confusing... really quickly. They seem to be okay for smaller projects but an utter nightmare for anything larger. Meanwhile, it was very easy to design shooter-oriented games in something like the Source Engine but utterly horrific if you wanted to do anything beyond that. So to me, it would be nice to levy the benefits of creating systems easily without things getting confusing, i.e. the clarity of the Source Engine with the flexibility of Unity.

## And that's it for now
That probably outlines my less radical ideas when it comes to the technical side of game development. Next post, I will outline what I like about Haxe. I also have some more arty-related thoughts too... It's only going to get weirder from here on.
