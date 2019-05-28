---
layout: post
title: Towards a GURPS Solo Engine
date:   2019-05-27 20:07:00 -0400
comments: true
categories: gurps
tags: [solo roleplaying]
---
I've been playing my World War 2 game, still. Still haven't gotten away from it!

But I also realized that I kind of missed just screwing around, and not worrying too much about stuff. Even though I run a very prep-lite game, and I don't worry too much about it, it's still something where I can't just ghost the heck out when I get bored. And I, fickle and all, have trouble relaxing when I'm signing a lease rather than sitting down for a play session.

That, of course, and I have played solo in the past. I've referred in the past to [Ubiquitous Rat]("http://ubiquitousrat.net/") and his blog. He's posted [many, many times about solo play]("http://ubiquitousrat.net/?tag=solo"). So I can't 100% credit him for it, but he certainly made it sound like fun.

There are a thousand ways to play solo. There's simple systems and complex systems. There's structured systems and freeform. And furthermore there's CYOA adventure books, where the whole thing is written out for you, similar to 3rd Edition's *All In A Night's Work*. And there's just one problem:

For all that you can use them with other rules, ***why the hell would you?***

<!-- more -->

One of the things that immediately gets pointed out when you read an introduction to Solo Roleplaying is what the whole idea is. After all, isn't RP a social experience? Some part of it is about performance, and experiencing a story alongside other people.

Well, okay, so then you have people asking how you can be a player and GM at the same time. Wouldn't you always know what was going to happen? And then they point out, that's what dice are for... it's a conversation that, very likely, everyone who's talked about this subject has had. Possibly with themselves, at some point. *That's what the dice are for.*

But okay. I can jive with that. But what's the fundamental difference between the question, "Do I recognize the man pointing a gun at me?" and the question, "Does the bullet kill me?" The difference is... nothing. You're asking a yes-no question, you've probably got a pretty good idea how much you want to weight each answer, and you've probably got a game rule to roll to find out.

Like, maybe you've met him before, but you didn't take Eidetic Memory [5]. Or maybe you've really never heard of this chump before. In a game with a GM, he makes a decision about whether or not the two of you have met, and then maybe he has you roll IQ to see if you remember the lackey who was sitting on the couch of Jimmy the Spider's office.

So you either lean hard on the rules, or you lean hard on the engine. Or you roll a *lot* of dice, and you try to drive two cars at once.

Which is fine sometimes, but particularly when you're looking at a system like Mythic, where rolls have features other than simple "yes" or "no" answers, every time you lean on the rules for even a moment, you're missing out on the opportunity to roll doubles at or under the Chaos Factor, and having a random event occur. Which is part of the game! Someone worked hard for this!

So I want something that feels more integrated into GURPS as a concept. I've got some thoughts, but I'm not sure. More as things develop, but I'll post what I'm planning on trying once I've finished this little adventure:

## The Basics

Roll 3d6 versus the TN! Just like GURPS! When things are easier, add a bonus to the TN. When things are harder, subtract a penalty from the TN. For consistency with GURPS 4e, we'll call Easy +1, Average +0, Hard -1, and Very Hard -2. You can extrapolate from there, hopefully. (This is a place where I may need work. Possibly a lot of work!)

Borrowing the concept of Chaos from Mythic, the default Chaos is 3. If you roll doubles or triples on 3d6, and the number on the die is 3-, then you consult an oracle. I don't have one yet, but hopefully one is going to come later. Chaos also contributes to TN; 2 gives +1, 3 gives +0, 4 gives -1, 5 gives -2, and so on in both directions. When things basically went good, decrease Chaos. When things basically went bad, increase Chaos. For games which feature combat, you might want to consider raising the Chaos every scene where the characters get into combat, as well!

The issue then comes down to assigning TNs and their outcomes, and that's where I've got a few possibilities.

### Option 1: Yes and No With Crits

| 4- |Critical Yes! [Yes, and something emphatically yes-like] |
| 10- |Yes |
| 16- |No |
| 17+ |Critical No! [No, and something emphatically no-like] |

### Option 2: Yes, and...

| 4- |Yes, and [something yes-like], and furthermore [something else yes-like]! |
| 7- |Yes, and... [something yes-like] |
| 10- |Yes |
| 13- |No |
| 16- |No, and... [something no-like] |
| 17+ |No, and [something no-like], and furthermore [something else no-like]! |

We've added an intermediate option here.

However, I've heard a couple people suggest that they're not big fans of simple yes-and-no, and I'm not sure whether or not I agree with that. But I will say, Option 2 features some awfully lonely-looking options!

### Option 3: Yes, but...

Building on Option 2...

| 4- |Yes, and [something yes-like], and furthermore [something else yes-like]! |
| 7- |Yes, and... [something yes-like] |
| 9- |Yes |
| 10 |Yes, but... [something no-like] |
| 11 |No, but... [something yes-like] |
| 13- |No |
| 16- |No, and... [something no-like] |
| 17+ |No, and [something no-like], and furthermore [something else no-like]! |

and then, if you really don't want simple answers...

### Option 4: I said YES BUT!

| 4- |Yes, and [something yes-like], and furthermore [something else yes-like]! |
| 7- |Yes, and... [something yes-like] |
| 10- |Yes, but... [something no-like] |
| 13- |No, but... [something yes-like] |
| 16- |No, and... [something no-like] |
| 17+ |No, and [something no-like], and furthermore [something else no-like]! |

This one makes sure that you always have some complication or mitigating factor, and never just have the dice go "Oh, yeah, sure." Whether or not this is a problem for you is really up to you!

And of course, all of these could easily be done without the criticals, as well. I won't re-do the tables to show how that would work, but it's not hard to figure out.

I think, when I finally do my testing, I'm going to use Option 4, and as for oracles... well, I'll probably want to crib notes from Mythic to a degree, but then I'm going to be using either playing card cartomancy stuff, or using my new Petit Jeu Lenoremand deck, because I won't use it for anything *but* gaming oracles in any case.
