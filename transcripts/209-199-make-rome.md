---
episode: 209
title: 199: MAKE ROME
date: 2023-09-10
guests: none
duration: 1:09:16
---

[00:00] SPEAKER: So Brad, this morning, as I was making coffee before we recorded, I was pouring the coffee
[00:04] SPEAKER: and updating all of my iOS devices simultaneously.
[00:07] SPEAKER: Yes, as one does in the year 2023.
[00:10] SPEAKER: Just a perfectly normal thing to do.
[00:11] SPEAKER: And I was thinking, you know what would be nice?
[00:13] SPEAKER: If this update had happened last night automatically without me having to think about it, and also
[00:17] SPEAKER: if I had a coffee refractometer, so I could see how well I was extracting my coffee.
[00:22] SPEAKER: Again, normal morning thoughts for 7.30 in the morning.
[00:25] SPEAKER: This is just the way my brain works.
[00:27] SPEAKER: I can't, I feel like I want to dig into both of these, but I don't know where to start,
[00:31] SPEAKER: so I'm going to leave it up to you.
[00:32] SPEAKER: It's a choose your own adventure, Brad.
[00:34] SPEAKER: That exploit was a rude awakening at 6.30 this morning when I first read about it.
[00:38] SPEAKER: Holy.
[00:39] SPEAKER: You mean, hey, let me send you an image and it will totally pwn your phone.
[00:43] SPEAKER: It's 12 o'clock.
[00:44] SPEAKER: Do you know where your iPhone is?
[00:46] SPEAKER: Did you know?
[00:47] SPEAKER: I learned, I didn't know about lockdown mode on iPhones until then.
[00:50] SPEAKER: No, I didn't either.
[00:51] SPEAKER: We should step back and just talk about, there's a very bad iOS exploit in the wild now.
[00:56] SPEAKER: It's I think it affects everything iOS, Mac OS, all Apple stuff.
[01:01] SPEAKER: So update your Apple devices today.
[01:03] SPEAKER: The distinction is, and it's right here in italics.
[01:08] SPEAKER: I've not heard of the citizen lab.
[01:09] SPEAKER: Are you familiar with them?
[01:10] SPEAKER: Yeah, they do.
[01:11] SPEAKER: They do like they're, they're a public service.
[01:14] SPEAKER: This is how they build themselves.
[01:15] SPEAKER: I gather they're one of these, these kind of watchdog groups that identifies CVEs.
[01:19] SPEAKER: Well, there's, there's money in bug bounties, right?
[01:22] SPEAKER: Like big, big companies pay a lot of money for people who find new exploits and stuff
[01:26] SPEAKER: like that.
[01:27] SPEAKER: Yes.
[01:28] SPEAKER: And you can fund a business that way.
[01:29] SPEAKER: Yes.
[01:30] SPEAKER: So even they, in their disclosure have this in all in italics, the exploit is capable
[01:33] SPEAKER: of compromising iPhones, running the latest version of iOS italics without any interaction
[01:38] SPEAKER: from the victim.
[01:39] SPEAKER: Yeah.
[01:40] SPEAKER: Like that's the part, that's the part that makes it so crazy.
[01:42] SPEAKER: I don't think I've ever seen an exploit where you didn't have to like click on or activate
[01:46] SPEAKER: or run something malicious actively before you were exploited.
[01:50] SPEAKER: Oh, Brad, let me tell you about the great worm situation of the early 2000s, pre-Windows
[01:56] SPEAKER: XP SP2.
[01:57] SPEAKER: You could just plug a computer on the, on the open network and it would be infected
[02:01] SPEAKER: in like eight minutes.
[02:02] SPEAKER: We've talked about this before.
[02:03] SPEAKER: If you're going to run on the internet without a firewall, there's no helping you.
[02:07] SPEAKER: It was a gentler time.
[02:08] SPEAKER: Okay.
[02:09] SPEAKER: Yes.
[02:10] SPEAKER: But yeah, like this is literally, if you get an infected iMessage, your phone is compromised.
[02:14] SPEAKER: That's it.
[02:15] SPEAKER: Like all they have to do is send you the right payload through an iMessage and you're fucked.
[02:19] SPEAKER: Yeah.
[02:20] SPEAKER: If you listen to this on Monday, it's probably already too late.
[02:22] SPEAKER: You should probably just light your phone on fire at this point.
[02:25] SPEAKER: Hack the planet.
[02:26] SPEAKER: No, it's like, it's whatever.
[02:27] SPEAKER: I mean, you'd have to be actively targeted.
[02:29] SPEAKER: Like this is probably something that only public figures need to worry about, but really
[02:32] SPEAKER: it's probably something mostly that only like people who run afoul of nation states have
[02:37] SPEAKER: to worry about, but still it's bad.
[02:39] SPEAKER: Well, I mean, you say that, but unlike most other exploits of this variety, this one they
[02:44] SPEAKER: did find in the wild.
[02:45] SPEAKER: So it's bad.
[02:46] SPEAKER: Like, like it's out there.
[02:47] SPEAKER: They discovered this one because of someone's phone that they analyzed that had already
[02:51] SPEAKER: been infected by it.
[02:53] SPEAKER: On the other side of this, the coffee refractor is a thing that you put a little drop of coffee
[02:57] SPEAKER: in.
[02:58] SPEAKER: It tells you how many, like what the percentage of solids is it's in the device.
[03:00] SPEAKER: Dude, that's some Star Trek shit.
[03:02] SPEAKER: I've just been thinking about that as I continue to dabble with cold brew coffee and I have
[03:07] SPEAKER: cut caffeine mostly entirely out of my life.
[03:10] SPEAKER: Oh God, I'm sorry.
[03:11] SPEAKER: Well, it's, it's for the best.
[03:13] SPEAKER: It's for the best.
[03:14] SPEAKER: Well, let's say we have so much caffeinated coffee left that I'm still, I flouted your
[03:20] SPEAKER: advice and bought a five pound bag of decaf.
[03:22] SPEAKER: Yeah.
[03:23] SPEAKER: How's that going for you?
[03:24] SPEAKER: That's fine so far.
[03:25] SPEAKER: Okay.
[03:26] SPEAKER: Anyway, I'm cutting, now I'm cutting like decaf and caffeinated.
[03:30] SPEAKER: So, so it's just another variable in the chain of what am I getting out of this cold brew?
[03:34] SPEAKER: You know, it's like,
[03:35] SPEAKER: So it's funny because the last time I looked at this, getting a refractometer was like
[03:41] SPEAKER: a better part of a thousand bucks.
[03:43] SPEAKER: And now, now there are some, some that are like 80 bucks on Amazon from China.
[03:49] SPEAKER: Okay.
[03:50] SPEAKER: And I'm like, maybe I'm going to get one of these seems like what's, what is there?
[03:55] SPEAKER: Is there a bad idea?
[03:56] SPEAKER: Well, this one's like a visual one that you look through.
[03:58] SPEAKER: What are we getting out of this?
[03:59] SPEAKER: Like caffeine, caffeine content, like oil, solids, solids dissolved in the water, like
[04:05] SPEAKER: how much stuff is in the water.
[04:07] SPEAKER: It's just, it's just kind of how saturated is this liquid?
[04:10] SPEAKER: It lets you know how much you've extracted out of the beans and into the, into the, into
[04:14] SPEAKER: the coffee.
[04:15] SPEAKER: Well, you don't know what compounds or anything like that.
[04:17] SPEAKER: Yeah.
[04:18] SPEAKER: I mean, well, if you ground up coffee and put it in the water, you know that it's coffee
[04:21] SPEAKER: compounds.
[04:22] SPEAKER: Okay.
[04:23] SPEAKER: Fine.
[04:24] SPEAKER: It's not like a spectrometer that'll tell you this is this much carbon and this much
[04:29] SPEAKER: phosphate and this much look, I, I, I can't tell you that it's some sort of magically
[04:35] SPEAKER: corrosive argon gas, Brad.
[04:37] SPEAKER: I don't understand that.
[04:39] SPEAKER: I'm mainly just curious how much caffeine is ending up in there, but
[04:43] SPEAKER: I'm sure that there's some sort of calculation you can do based on the, but, but that I think
[04:46] SPEAKER: you have to do know how much caffeine is in the beans and that varies from varietal to
[04:50] SPEAKER: varietal, I believe.
[04:51] SPEAKER: So anyway, there you go.
[04:53] SPEAKER: Refractometers update your iOS devices.
[04:56] SPEAKER: Sounds like it's time for a podcast.
[05:26] SPEAKER: Welcome to Brad and Will made a tech pod.
[05:28] SPEAKER: I'm Will.
[05:29] SPEAKER: I'm Brad.
[05:30] SPEAKER: I'm Brad.
[05:31] SPEAKER: I'm Will.
[05:32] SPEAKER: Okay.
[05:33] SPEAKER: Just, just, just in case it didn't take the first time.
[05:37] SPEAKER: Look, school has started now.
[05:40] SPEAKER: And as a result, like during the summer months, when we podcast, we often podcast early in
[05:46] SPEAKER: the morning and I get up and I have the house all to myself.
[05:49] SPEAKER: I have an hour and a half usually before we go where I can like finalize show notes and
[05:54] SPEAKER: I can get my stuff together and like have some, have a little bit of quiet Will time
[05:59] SPEAKER: to prepare for a pod.
[06:00] SPEAKER: Sorry.
[06:01] SPEAKER: Is that, I started to say, wait, are they like leaving for summer camp at 6 AM?
[06:04] SPEAKER: But then it occurred to me, Oh, they're probably still asleep.
[06:08] SPEAKER: The idea of sleeping past like six o'clock is hard for me to fathom at this point.
[06:13] SPEAKER: All the decent people in my house are asleep until nine during the summer.
[06:17] SPEAKER: Oh, that sounds good.
[06:18] SPEAKER: Yeah.
[06:19] SPEAKER: It's nice for them.
[06:20] SPEAKER: So now during the winter months, when school's on, everything starts at six 30 and it's full
[06:28] SPEAKER: chaos for an hour and a half and they leave at about seven 50.
[06:32] SPEAKER: So that means that I have 10 minutes instead of the traditional 90 minutes to, to, to do
[06:39] SPEAKER: my pod peration.
[06:40] SPEAKER: Right.
[06:41] SPEAKER: You've done some pretty good pod peration here in 10 to 15 minutes.
[06:46] SPEAKER: Yeah.
[06:47] SPEAKER: So anyway, there, there we go.
[06:48] SPEAKER: This week, we're going to talk about the kind of stuff that people don't talk about about
[06:52] SPEAKER: making video games often working on a small studio.
[06:55] SPEAKER: I've got to be engaged with some of this, not all of this.
[06:58] SPEAKER: For sure.
[06:59] SPEAKER: You make it sound so salacious.
[07:00] SPEAKER: What?
[07:01] SPEAKER: What do you mean?
[07:02] SPEAKER: It's the stuff nobody talks about the filthy underpinnings of the game industry.
[07:07] SPEAKER: Talk about such secrets.
[07:08] SPEAKER: We don't want to hear about like per force servers and talk about, talk to talk about
[07:11] SPEAKER: such scandalous subjects as your build server.
[07:14] SPEAKER: Yeah.
[07:15] SPEAKER: You want to come down to team city with me, Brad team city makes the build server software
[07:21] SPEAKER: that we use.
[07:22] SPEAKER: I don't wait.
[07:23] SPEAKER: I'm sorry.
[07:24] SPEAKER: What is it called?
[07:25] SPEAKER: Team city.
[07:26] SPEAKER: Oh, I thought you were, I thought that was a Microsoft teams joke.
[07:27] SPEAKER: No, no.
[07:28] SPEAKER: We use teams too.
[07:29] SPEAKER: We love teams.
[07:30] SPEAKER: It's fine.
[07:31] SPEAKER: Seattle studio.
[07:32] SPEAKER: We've team nothing better than a good Microsoft product.
[07:33] SPEAKER: Oh, is that a, Oh, team city is a jet brains thing.
[07:36] SPEAKER: Team city is a jet brains thing.
[07:37] SPEAKER: They make a, they it's the, that is literally, okay.
[07:40] SPEAKER: So anyway, we're going to talk about, we're going to talk about the things that are like
[07:43] SPEAKER: the backend stuff that makes game studios work and that makes it easy to publish games.
[07:48] SPEAKER: As I like to think of it, the, like, we're going to talk about how you build a video
[07:52] SPEAKER: game, not how you like develop and make a video game, but how like you turn all that
[07:56] SPEAKER: work into a functional running program.
[07:59] SPEAKER: Yeah.
[08:00] SPEAKER: So, so for, so for example, when I make a change to the sound stuff in the game, I submit
[08:05] SPEAKER: it to our, our source control software.
[08:07] SPEAKER: We use per force.
[08:08] SPEAKER: It's popular in the games.
[08:09] SPEAKER: We'll talk about that in a minute, the, the, the, then that goes up onto the source control
[08:17] SPEAKER: server.
[08:18] SPEAKER: And at some point in the future, somebody will say, okay, Hey, well, or realistically
[08:21] SPEAKER: every night at 3 AM, our build servers look at the, at the source control stuff.
[08:26] SPEAKER: And they say, they're like, Hey, isn't anybody submit anything today?
[08:29] SPEAKER: If they did, then we'll make a new build.
[08:30] SPEAKER: And if not, then we'll just use yesterday's build stays.
[08:35] SPEAKER: And then those get built, they get uploaded to steam and the next morning, our, our internal
[08:39] SPEAKER: branches are updated with like the latest, uh, daily play test build, which is, which
[08:44] SPEAKER: is, uh, which is our, like the current it's, it's equivalent of a nightly in like open
[08:50] SPEAKER: source.
[08:51] SPEAKER: Absolutely.
[08:52] SPEAKER: I started this, I'm sure every studio is different.
[08:55] SPEAKER: I'm like shocked to hear it's that automated, not the build process.
[08:58] SPEAKER: Cause of course you, why not automate nightly builds the part where you deploy it to steam,
[09:03] SPEAKER: even though I'm sure that's like filtered to a few testers, like not, that's certainly
[09:06] SPEAKER: not for public consumption.
[09:07] SPEAKER: But the idea of it, the idea that a build is going out the door, even to testers without
[09:11] SPEAKER: anybody touching it is kind of crazy to me.
[09:13] SPEAKER: Well, so that internal build is just internal.
[09:15] SPEAKER: Like that's not even for, that's not even for external testers.
[09:18] SPEAKER: We don't generally, okay.
[09:19] SPEAKER: We have in the past made those builds available to internal testers, but so, so there's more,
[09:25] SPEAKER: okay, let's take it, let's take a step, take a step back.
[09:28] SPEAKER: Most studios probably have at least two and probably three to five private builds, or
[09:37] SPEAKER: plus the release, the release build that everybody, that everybody that's bought the game has
[09:41] SPEAKER: access to.
[09:42] SPEAKER: So there's like, there's going to be a debug slash development build that has all the hooks
[09:46] SPEAKER: that people can hook their, their engine tools into to see like what's going on inside the
[09:51] SPEAKER: game.
[09:52] SPEAKER: Right.
[09:53] SPEAKER: And that you don't want to put out.
[09:54] SPEAKER: There's usually like, if it's a multiplayer game, there's like a staging environment or
[09:57] SPEAKER: a development environment one where you can hook into the server and see the same stuff.
[10:01] SPEAKER: Sometimes those are the same build in our, in our game they are.
[10:04] SPEAKER: There's a private testing pre-release, like a release candidate build that's essentially
[10:11] SPEAKER: a ready to ship to machines build.
[10:13] SPEAKER: So, so there's development builds, there's testing builds, and then there's builds that
[10:17] SPEAKER: you give to, to customers, to players.
[10:19] SPEAKER: And there are different divisions inside of us.
[10:22] SPEAKER: Usually the testing one has some debug hooks and we'll dump extra debug stuff.
[10:26] SPEAKER: It may have cheats enabled so that the QA folks can, can bypass like, you know, can
[10:32] SPEAKER: spawn specific weapons.
[10:33] SPEAKER: Like if there's a change to a weapon, you want to spawn like 50 of those and try a bunch
[10:36] SPEAKER: of different circumstances, stuff like that.
[10:39] SPEAKER: In multiplayer game, you obviously don't want to leave that stuff in for the shipping build.
[10:42] SPEAKER: And then, and then there's the shipping builds and the shipping candidate builds and all
[10:45] SPEAKER: that stuff.
[10:46] SPEAKER: Yeah.
[10:47] SPEAKER: I've, this is just kind of tangential, like having covered console games for a long time.
[10:50] SPEAKER: I've always assumed that's why, or that's a big part of the, the debug stuff is a big
[10:54] SPEAKER: part of the reason that console dev kits are so much beefier than the actual console hardware
[10:57] SPEAKER: because you need a ton, ton of extra memory and maybe extra compute to handle all the
[11:02] SPEAKER: crazy extra debug stuff you have to run on top of the actual game.
[11:05] SPEAKER: That's my understanding of that.
[11:07] SPEAKER: It's that's a double edged sword because you can use debug kits to test, but you, we like,
[11:12] SPEAKER: we had a bug with one of the X-Boxes, I think that was only, it didn't happen on the debug
[11:20] SPEAKER: kits because they had that extra memory.
[11:22] SPEAKER: That's I was going to say, it seems like you'd have to do some very meticulous like resource
[11:25] SPEAKER: and performance profiling to make sure you're not exceeding your eventual hardware target
[11:30] SPEAKER: budget.
[11:31] SPEAKER: Cause we did not realize that that was the problem.
[11:33] SPEAKER: So we didn't realize it was a problem when we were testing.
[11:36] SPEAKER: Cause we assumed that when you flip those to retail mode, then they work like retail
[11:40] SPEAKER: kits, but they don't.
[11:41] SPEAKER: That sounds like in an X-Box context, cause that's the only one that's got modes of that
[11:46] SPEAKER: nature.
[11:47] SPEAKER: I believe so.
[11:48] SPEAKER: Yeah.
[11:49] SPEAKER: That's we only ship on X-Box.
[11:50] SPEAKER: So okay.
[11:51] SPEAKER: So you have all these different things.
[11:54] SPEAKER: Each of those is a pipeline in your, in your build server.
[11:57] SPEAKER: Right.
[11:58] SPEAKER: And the build server has basically all of the stuff on it that you need to make the
[12:06] SPEAKER: game, either the debug versions, the testing versions, the shipping versions, whatever.
[12:11] SPEAKER: And on all the platforms that you release.
[12:13] SPEAKER: So like it'll have all of the libraries and all of the compiler stuff and what it has
[12:18] SPEAKER: on it varies widely based on your game, the platforms you ship on, whether it's a console
[12:23] SPEAKER: game or PC game, whatever, but the build server knows like, Hey, grab these commits, do, hook
[12:36] SPEAKER: into the different API versions and then you need to make a version for steam and you make
[12:39] SPEAKER: a version for epic.
[12:40] SPEAKER: You need to make a version for the X-Box one for X-Box series for windows store, all the
[12:45] SPEAKER: places you might ship the game.
[12:46] SPEAKER: It'll it'll build those.
[12:47] SPEAKER: And each of those takes time.
[12:48] SPEAKER: Like it's a, it's a fairly involved process.
[12:49] SPEAKER: I've got, I could probably spend the rest of this podcast talking to you about your
[12:53] SPEAKER: build server and the concept in general, from, from everything from like the general specs
[12:58] SPEAKER: and how they're built at a low level to like how you manage different build environments
[13:02] SPEAKER: based on the pile targets and platforms and stuff like that.
[13:05] SPEAKER: Like are most, I'm sure it varies, like, you know, I'm trying to think like, what's the
[13:11] SPEAKER: biggest Ubisoft team out there?
[13:13] SPEAKER: I mean, your studio is quite small.
[13:14] SPEAKER: A lot of the indie developers are just a single digit number of people, but then there are
[13:17] SPEAKER: like a hundred strong studios out there, like 500 people or something these days or bungee
[13:23] SPEAKER: is like gigantic.
[13:24] SPEAKER: Right?
[13:25] SPEAKER: So like, I'm sure, I'm sure what constitutes like a build server or build farm is very
[13:30] SPEAKER: different as, as size scales.
[13:33] SPEAKER: Yeah.
[13:34] SPEAKER: We have a baby ass baby build farm.
[13:35] SPEAKER: It's only like three machines.
[13:36] SPEAKER: Oh, even though I'm actually surprised, even at your size, that it's multiple machines
[13:40] SPEAKER: I was going to ask, like, is it, is it all just kind of, I assume off the shelf commodity
[13:44] SPEAKER: hardware these days?
[13:45] SPEAKER: I mean, CPU's are very fast in general, right?
[13:47] SPEAKER: Yeah.
[13:48] SPEAKER: I think I feel like more cores and more memory, it's a real right turn intensive thing.
[13:54] SPEAKER: My guess is like, we've been looking at upgrading our build servers at some point in the future.
[13:59] SPEAKER: Just because we're on the time we built these machines or bought these machines, I don't
[14:05] SPEAKER: think that there were a lot of really large NVME SSDs available at a scale that we could
[14:11] SPEAKER: okay.
[14:13] SPEAKER: So you have to have a lot like the, the there's a lot of space, it requires a lot of space.
[14:17] SPEAKER: So if you like, our game is like 16 gigs on steam, which decompresses down to like 30 gigs
[14:22] SPEAKER: when you, when you, when you unpack it.
[14:26] SPEAKER: And to do the builds and have, you have to have all the source code files.
[14:29] SPEAKER: You have to have the compiled binary assets that make up the game and the unreal project,
[14:34] SPEAKER: all that stuff.
[14:35] SPEAKER: It's, it's big, it's like 500 gigs of space for the project for the current version of
[14:41] SPEAKER: the project.
[14:42] SPEAKER: That's pretty big.
[14:43] SPEAKER: Yeah.
[14:44] SPEAKER: I mean, you know, like a relatively small scale game.
[14:47] SPEAKER: I'm not saying like your game is small or whatever, but like, but like it's like a million
[14:50] SPEAKER: dollars.
[14:51] SPEAKER: It's not a big game.
[14:52] SPEAKER: Right.
[14:53] SPEAKER: Like it's a focused game.
[14:54] SPEAKER: It's a multiplayer only game more or less, you know?
[14:55] SPEAKER: Yes.
[14:56] SPEAKER: Yeah.
[14:57] SPEAKER: And that, and that's, that's like you said, that's half a terabyte for a, an indie multiplayer
[15:00] SPEAKER: game.
[15:01] SPEAKER: Like imagine, imagine what the total kind of asset or package size is for like your
[15:07] SPEAKER: average sprawling console RPG.
[15:09] SPEAKER: Yeah, to give you some context, I think Chet likes to say that Far Cry 6 had more studios
[15:15] SPEAKER: that worked on it than we had people that worked on the end of Cruces.
[15:19] SPEAKER: Sure.
[15:20] SPEAKER: And, and some of those studios, like the Ubisoft Shanghai is like a thousand people.
[15:24] SPEAKER: It's they're enormous.
[15:25] SPEAKER: Right.
[15:26] SPEAKER: Yeah.
[15:27] SPEAKER: So, so they have a whole, like where we had a person who did this for a while and then
[15:31] SPEAKER: it shifted out to like, to be part of somebody else's job or a couple other people's jobs.
[15:36] SPEAKER: And this, this at someplace like Ubisoft, I assume that there's entire teams that do
[15:40] SPEAKER: nothing but this kind of DevOps work, right where they're, where they're, you know, everybody
[15:45] SPEAKER: has their own per force and then stuff filters up and their Knightleys are real weird.
[15:49] SPEAKER: I'm sure.
[15:50] SPEAKER: I don't even like, I can't even, the amount of art that goes into something like an Assassin's
[15:53] SPEAKER: Creed.
[15:54] SPEAKER: I don't, I can't imagine that you have a daily build cycle.
[15:58] SPEAKER: And then, and then you hear about things like Destiny 1 where Bungie didn't, had problems
[16:02] SPEAKER: with their backend and like they had their, just to be clear, the build server doesn't
[16:08] SPEAKER: do the computationally expensive stuff like build light maps and stuff like that.
[16:11] SPEAKER: That happens either an artist does that, or we have a build a light map machine that,
[16:15] SPEAKER: that does that.
[16:16] SPEAKER: Interesting.
[16:17] SPEAKER: So what are the, what are, when you say an artist does that, do they, would they have
[16:20] SPEAKER: that hard, surely they wouldn't have that hardware at their desk, right?
[16:23] SPEAKER: I assume that's like heavier iron than like would be in an end user context.
[16:27] SPEAKER: Okay, so for our game, again, this is a place where things differ based on the scale of
[16:33] SPEAKER: your game, right?
[16:34] SPEAKER: Yeah.
[16:35] SPEAKER: On our game, I can run the light maps in like 40 minutes on my 40/90.
[16:39] SPEAKER: Oh, okay.
[16:40] SPEAKER: Cause there, there are GPU, there's a GPU accelerated light map maker now.
[16:43] SPEAKER: Oh, of course, of course.
[16:44] SPEAKER: See, my, my brain is very stuck in the nineties back when like every, every like Quake licensee
[16:48] SPEAKER: had a, had a, like a light map.
[16:50] SPEAKER: You don't have an SGI machine in any place running this stuff.
[16:52] SPEAKER: Like running radiosity calculations.
[16:54] SPEAKER: Yeah, no.
[16:55] SPEAKER: I mean, like the ray tracing stuff has accelerated that pretty dramatically.
[16:59] SPEAKER: It's not, it's not real time, but it's like, it's gone from a, Hey, you start this before
[17:04] SPEAKER: you leave work at the end of the day and then you come back in the morning and it's maybe
[17:06] SPEAKER: done to Hey, you can hit the button and yeah, like on a 30, 70, it'll be done in like an
[17:12] SPEAKER: hour.
[17:13] SPEAKER: Okay.
[17:14] SPEAKER: You can go eat lunch and come back.
[17:15] SPEAKER: Maybe take a nap.
[17:16] SPEAKER: Yeah, I guess, I guess this is a good time to point out like the stuff we're talking
[17:19] SPEAKER: about in terms of how fast you can, you know, crunch calculations and produce a build like
[17:23] SPEAKER: that has very real implications for workflow, right?
[17:26] SPEAKER: Like how fast you can check changes in and get a build out and test them like just dictates
[17:31] SPEAKER: how fast you can move on to the next thing.
[17:33] SPEAKER: Right?
[17:34] SPEAKER: Yeah.
[17:35] SPEAKER: And, and so we have, so, so the two things to take away from this are even a simple game
[17:38] SPEAKER: that's only shipping on two platforms, we ship on steam and Xbox right now, when we
[17:43] SPEAKER: release something, it makes five builds, right?
[17:48] SPEAKER: So each of those builds takes an hour to two hours.
[17:51] SPEAKER: A lot of that is just disc churn.
[17:53] SPEAKER: There's not a lot of, there's not a lot of complicated stuff.
[17:55] SPEAKER: It's not like we're baking light maps or something on all of those builds.
[17:58] SPEAKER: And like that takes, that takes a long time.
[18:01] SPEAKER: We also have a, Hey, here's, we want to do something quick for testing that just jams
[18:04] SPEAKER: it up on, on a special steam branch.
[18:06] SPEAKER: And that's like an hour, hour and a half, but it's, it still takes time.
[18:09] SPEAKER: It's a, it's upload bandwidth and it's it's, it's the compiling time and all that kind
[18:15] SPEAKER: of stuff.
[18:16] SPEAKER: Yeah, I assume it's, it's probably safe to say that the common commercial engines like
[18:19] SPEAKER: unreal and unity have, I assume, have focused on iteration time as a, as a single point.
[18:24] SPEAKER: I don't think they give a flying fuck about iteration time.
[18:28] SPEAKER: Nevermind then.
[18:29] SPEAKER: Well, you, you mentioned the bungee example, which like, from my understanding, that was
[18:32] SPEAKER: just like a legacy tech issue.
[18:34] SPEAKER: You know, they had just been working on the same core architecture in their engine for
[18:38] SPEAKER: so long that there were just a lot of legacy things that made it cause that, that was very
[18:42] SPEAKER: widely reported about the first game that like, you know, like kind of like you said,
[18:46] SPEAKER: it took 12 hours to bake them to see a map change or something nuts, right?
[18:50] SPEAKER: Like replace one pickup in the map.
[18:52] SPEAKER: This may not be a hundred percent accurate, but it will make a very minor change to the
[18:55] SPEAKER: map.
[18:56] SPEAKER: And then you'd have to wait like all night and come back the next morning before you could
[18:58] SPEAKER: test the map again.
[18:59] SPEAKER: Yeah.
[19:00] SPEAKER: I think so.
[19:01] SPEAKER: I don't know about bungees example in particular, but, but the other thing is, so I say that
[19:07] SPEAKER: I don't think the, the engine makers give a fuck about that, but like there is unreal
[19:12] SPEAKER: has play an editor, right?
[19:13] SPEAKER: So you can hit a button in the game and it'll load up the game with whatever kind of starting
[19:17] SPEAKER: state you say.
[19:18] SPEAKER: So you can say, okay, I want to play in versus mode.
[19:20] SPEAKER: I want to play in survival mode.
[19:21] SPEAKER: I want to do this, this, this, and then you can play through the game there.
[19:24] SPEAKER: It's not exactly one to one.
[19:26] SPEAKER: Like there's some places where it's a little bit weird and you can get, you can put yourself
[19:31] SPEAKER: in trouble there.
[19:32] SPEAKER: But if you're making like, if you're making like, for example, when I'm making audio changes,
[19:36] SPEAKER: I can make my change, hit the play an editor button and, and get an idea, a pretty good
[19:41] SPEAKER: idea of what the end result is going to be.
[19:43] SPEAKER: You mean when you're getting your wise on what I'm getting my wise on if other stuff
[19:49] SPEAKER: is less like light map changes, you still have to make the light maps.
[19:51] SPEAKER: If you want to see what, what happens and there's always a, did this, did this run right?
[19:57] SPEAKER: Or is there some weird math glitch to the cosmic Ray hit the GPU at the wrong moment
[20:00] SPEAKER: and jack up the whole thing.
[20:02] SPEAKER: But, but that usually results in like weird artifacting, not, not a broken bill, not a
[20:08] SPEAKER: broken build.
[20:09] SPEAKER: So the, the, the thing about the thing about like light maps are a weird one cause it's
[20:13] SPEAKER: always a balance between, Hey, how long do I want to bake the light map and Hey, what
[20:18] SPEAKER: level of janky artifacting my okay with and a shadow in a corner of the map that nobody
[20:22] SPEAKER: ever sees.
[20:24] SPEAKER: And it turns out the answer is you're probably okay with a little bit of artifacting in a
[20:26] SPEAKER: weird corner that nobody ever sees.
[20:29] SPEAKER: And if that's a continual problem that you can put something in that corner that will
[20:32] SPEAKER: kind of fix that problem and tell it to spend a little more time there.
[20:34] SPEAKER: I don't know if this is getting to like 3d graphics engineering for you or if you can
[20:38] SPEAKER: speak to this, but like, can you elaborate on like what constitutes a light map in 2023?
[20:43] SPEAKER: Like I hear a lot about light probes.
[20:45] SPEAKER: Like are those synonymous at this point?
[20:46] SPEAKER: Like I don't know what the and, and also, are we talking about fully static lighting
[20:50] SPEAKER: at this point?
[20:51] SPEAKER: Like are, are those types of quote unquote light maps, like things that you place and
[20:55] SPEAKER: then don't move?
[20:56] SPEAKER: Like, is that still, how does that, how does that work these days?
[20:58] SPEAKER: Yeah.
[20:59] SPEAKER: So depending on the platforms you're shipping on, for example, like if you're making an
[21:04] SPEAKER: Oculus quest game, you can have a relatively meager number of dynamic lights, dynamic lights
[21:09] SPEAKER: or lights that can move that can be on or, or, well, I mean, light map lights can be
[21:13] SPEAKER: on or off too, but the option is intensity, you move around and stuff like that.
[21:17] SPEAKER: Yeah.
[21:18] SPEAKER: They're there.
[21:19] SPEAKER: You can, you can programmatically during the gameplay and they are on traditional hardware,
[21:25] SPEAKER: very expensive, like they call it, especially on mobile stuff.
[21:28] SPEAKER: They're really expensive to run, which is why I like lighting has been like the, the
[21:32] SPEAKER: it's hard to say the Holy grail, but that's more like the white whale, I feel, I feel
[21:36] SPEAKER: like of, of 3d graphics since the beginning of time, right?
[21:39] SPEAKER: Like that's always the thing that takes the most work and that people throw the most different
[21:42] SPEAKER: like techniques at the wall to try to solve.
[21:45] SPEAKER: Well, and it's, and it's a thing that our brains, our brains know what lights do, what
[21:49] SPEAKER: light does in the real world, just instinctively.
[21:51] SPEAKER: We understand it.
[21:52] SPEAKER: So it's a place where when the light doesn't look right, you know, it nearly, this doesn't
[21:55] SPEAKER: look good or, or, or it's, alternately you can go with a really stylized approach and
[21:59] SPEAKER: then you, it doesn't matter if it looks good.
[22:01] SPEAKER: Do you just have to be internally consistent?
[22:04] SPEAKER: The, the, the, the, there's a bunch of different ways to cheat having a bunch of dynamic lights
[22:11] SPEAKER: in the game.
[22:12] SPEAKER: That's, that's the kind of TLDR and the different engines use a bunch of different ways inside
[22:17] SPEAKER: an engine.
[22:18] SPEAKER: You can choose to use a bazillion different ways.
[22:21] SPEAKER: The exciting, this is one of the reasons people are excited about UE5 is that because of the
[22:26] SPEAKER: things that they're doing, you can have dynamic, like dynamic lights because of the way they're
[22:31] SPEAKER: using the ray tracing hardware and, and, and some stuff that they've done on the back end
[22:35] SPEAKER: of the engine, dynamic lights as a solution for your game are much more viable than they
[22:41] SPEAKER: have been in the past.
[22:42] SPEAKER: So you can have a game that is entirely dynamic lights, like the sky, the sun is a dynamic
[22:47] SPEAKER: light.
[22:48] SPEAKER: And, and like, so for example, in PUBG, the sun moves across the sky, right?
[22:52] SPEAKER: But they move the sun across the sky by generating light maps at all the different positions
[22:56] SPEAKER: the sun can be, and then blending between them as the time changes in the game.
[23:00] SPEAKER: Yeah.
[23:01] SPEAKER: Is that why in some games you'll, if you look at kind of the shadows on the ground, you'll
[23:03] SPEAKER: see them moving in very rigid increments.
[23:06] SPEAKER: Yeah.
[23:07] SPEAKER: Yeah.
[23:08] SPEAKER: And, and so they don't blend between them when they're moving in rigid increments.
[23:11] SPEAKER: But at the end of the day, all the light map is, is a texture that says how bright a part
[23:14] SPEAKER: of the map is.
[23:15] SPEAKER: Right.
[23:16] SPEAKER: Right.
[23:17] SPEAKER: And then the light probes and stuff like that are just, just further refined, give you more
[23:21] SPEAKER: control over specific subsets of the game and stuff like that, or dynamic control over
[23:25] SPEAKER: a different area, stuff like that.
[23:26] SPEAKER: Right.
[23:27] SPEAKER: So like fully, fully not to turn this into lighting chat, but like fully generalized
[23:31] SPEAKER: dynamic lighting has all that's, that's the Holy grail that I was talking about.
[23:34] SPEAKER: Like ever since like Doom 3, it's always been like different techniques of chasing.
[23:38] SPEAKER: Like we don't want to have to bake any, any rigid, unchangeable lights into this game.
[23:42] SPEAKER: If we can make everything work in the same way dynamically, then or even in different
[23:46] SPEAKER: ways dynamically.
[23:47] SPEAKER: And typically game lighting doesn't work the same way that light works in the real life
[23:51] SPEAKER: in real, in real life, you know, a light source exudes photons, the photons bounce off of
[23:55] SPEAKER: things.
[23:56] SPEAKER: And then the photons that smash into your eyeballs are, are represent colors and, and,
[24:01] SPEAKER: and information like their wavelength has changed based on what they've been absorbed
[24:05] SPEAKER: and re-emitted into in a video game.
[24:09] SPEAKER: Typically they, you blast rays out from the eyeballs and you see what you can see, and
[24:15] SPEAKER: then you kind of back it, you reverse engineer into what color those should be.
[24:18] SPEAKER: Yes, I was going to bring that up as, as, as I've read a little bit about the current
[24:21] SPEAKER: ray tracing techniques.
[24:22] SPEAKER: I was surprised to find out that they do it in reverse of the way that, that it works
[24:25] SPEAKER: in the real world.
[24:26] SPEAKER: Turns out it's a lot cheaper cause you have to do a bunch of pixels, a bunch of rays that
[24:29] SPEAKER: nobody ever sees.
[24:30] SPEAKER: Yes.
[24:31] SPEAKER: So like that stuff is super fascinating and I could barely speak to it.
[24:33] SPEAKER: Although I was actually just looking at the Reeser white paper yesterday, are you familiar
[24:36] SPEAKER: with that?
[24:37] SPEAKER: I haven't read it yet.
[24:39] SPEAKER: It's what Cyberpunk uses for their path tracing mode.
[24:41] SPEAKER: It's a, it's a relative, I think it's white paper was published in like 2019, 2020.
[24:46] SPEAKER: It's just a new, it's a new algorithm for ray casting that is like wildly more efficient.
[24:51] SPEAKER: It's probably, it's probably like less accurate if you're running an offline render farm and
[24:55] SPEAKER: you want pure, pure image quality, but it's not going to use that, but it's great for
[24:59] SPEAKER: video games.
[25:00] SPEAKER: It sounds like R E S T I R like it's the math is super over my head.
[25:04] SPEAKER: I didn't even bother trying to understand it.
[25:06] SPEAKER: But if you, if you Google that, you'll get straight to the Nvidia like research page
[25:09] SPEAKER: for it.
[25:10] SPEAKER: And you can see a picture of like, here's the, here's the, here's the, here's the kind
[25:14] SPEAKER: of like, it's not a point cloud, but what is the, you know, the, the undi noise, like
[25:18] SPEAKER: just the, the speckled image that you see of like, here's, here's where every ray hit
[25:21] SPEAKER: a surface with the traditional algorithm and then right next to what research does.
[25:25] SPEAKER: And it's like orders of magnitude, more samples, more dense.
[25:28] SPEAKER: Yeah.
[25:29] SPEAKER: So it's cool.
[25:30] SPEAKER: It's really cool seeing all this research stuff going on.
[25:31] SPEAKER: That's like massively accelerating how that stuff works.
[25:33] SPEAKER: We're let's, we should probably get back to building games.
[25:36] SPEAKER: I'm sorry to turn this into 3D graphics time.
[25:38] SPEAKER: Well, so the, I mean, that's why we don't focus too much on stuff like light maps.
[25:42] SPEAKER: Like we, we set up a big Threadripper machine in the office and let that be the light maps
[25:46] SPEAKER: server.
[25:47] SPEAKER: And then, and then the artists can say, okay, I need to bake level, you know, episode three
[25:51] SPEAKER: level two.
[25:53] SPEAKER: And that sends a command to that server and it runs the light maps and like an hour later
[25:57] SPEAKER: it uploads it, it makes it commit to the source control.
[26:01] SPEAKER: That's like, Hey, new light maps for episode three level two.
[26:04] SPEAKER: That's okay.
[26:05] SPEAKER: That's interesting.
[26:06] SPEAKER: So that's, that's what I was wondering about when I said like, are, are these types of
[26:09] SPEAKER: servers just commodity hardware these days?
[26:11] SPEAKER: Like Threadripper is not exactly end user hardware, but it's also not like, it's also
[26:15] SPEAKER: not a hundred thousand dollar supercomputer type stuff.
[26:19] SPEAKER: Like you, like you said, that's like, what is like a decent Threadripper build is like
[26:23] SPEAKER: five grand or something.
[26:24] SPEAKER: I don't think we've been spent that much, but, but yeah, basically the build servers
[26:31] SPEAKER: will benefit from more cores, but you don't need like a workstation, like a multi-core
[26:36] SPEAKER: workstation machine.
[26:37] SPEAKER: You just need something with a shitload, like a Threadripper, a big Intel machine will totally
[26:42] SPEAKER: do it.
[26:43] SPEAKER: And you're probably better off given that while one build is building, like we would
[26:48] SPEAKER: be better off having four small machines than two big machines.
[26:51] SPEAKER: I think we have two big machines now.
[26:53] SPEAKER: And because we have five builds to make when we hit the button then, and they can't run
[26:59] SPEAKER: in parallel on the same machine, we would be better off having five NUCs with a lot
[27:04] SPEAKER: of storage attached to them than two big 64 core machines, which is what we have now.
[27:09] SPEAKER: So why are those two machines not in some kind of cluster situation where they're both
[27:12] SPEAKER: working on the same, or is each one doing a discrete build?
[27:14] SPEAKER: Each one is doing its own build because of the way the build process, you can't come.
[27:18] SPEAKER: Yeah.
[27:19] SPEAKER: Like I guess theoretically we could put VMs on them, but also you pay for TeamCity based
[27:23] SPEAKER: on the number of machines that you have.
[27:25] SPEAKER: So like it's, as with everything, you can put a bunch of numbers in a spreadsheet and
[27:31] SPEAKER: then you get a curve where you're like, okay, here's the sweet spot.
[27:33] SPEAKER: We're willing to pay this much money a year to get a build in an hour versus a third of
[27:38] SPEAKER: that to get a build in two hours.
[27:40] SPEAKER: Right.
[27:41] SPEAKER: And it turns out the two hour number is usually the right number.
[27:44] SPEAKER: Yes.
[27:45] SPEAKER: Okay.
[27:46] SPEAKER: So then once the builds are made on the build server, theoretically, if you've done, if
[27:51] SPEAKER: you set yourself up right, it should just go to the platforms.
[27:54] SPEAKER: Like it should just be uploaded into the back ends of the platforms.
[27:58] SPEAKER: Disclaimer.
[28:00] SPEAKER: So some are more reliable than others.
[28:03] SPEAKER: There's a button in TeamCity that you can press that's like, "Hey man, re-run the upload
[28:08] SPEAKER: process."
[28:09] SPEAKER: So TeamCity sets this up as like, I've used Jenkins before in the past, which is a similar
[28:14] SPEAKER: piece of software that's open source, but TeamCity sets this up as a series of tasks.
[28:18] SPEAKER: So it's like build for Steam, build for Xbox, build for Xbox One, build for Windows.
[28:25] SPEAKER: And then the next step in that chain is deploy to Microsoft, deploy to Steam.
[28:32] SPEAKER: So if the build completes correctly and it doesn't deploy, you just hit the deploy button
[28:37] SPEAKER: and it uploads it again.
[28:38] SPEAKER: It's fine.
[28:39] SPEAKER: Okay.
[28:40] SPEAKER: I didn't realize TeamCity also handled the uploads and hooked into those back ends directly.
[28:43] SPEAKER: Is that built in or is that something that you have to script, like here's the upload
[28:48] SPEAKER: target for Steam, here's the API keys, do you have to build that part yourself?
[28:54] SPEAKER: So yeah, I didn't set this up on our end.
[28:56] SPEAKER: I did it for our Jenkins server as a FU, but basically, Steam just has a bunch of command
[29:04] SPEAKER: line utilities that you can script into.
[29:06] SPEAKER: So it's a lot of PowerShell scripting.
[29:09] SPEAKER: From TeamCity's perspective, this is all just PowerShell scripting and it has hooks into
[29:14] SPEAKER: some of the compilers and stuff like that, so you can see how it's going.
[29:17] SPEAKER: But mostly it's just like, "Hey, I'm going to run some scripts in a sequence of orders
[29:21] SPEAKER: and then I'm also going to archive a bunch of files for you.
[29:23] SPEAKER: I know how to handle the file archiving bits."
[29:25] SPEAKER: But also that's probably PowerShell scripting too.
[29:27] SPEAKER: I haven't actually looked at those to see how they work, but basically when you're setting
[29:32] SPEAKER: up a small game studio, it's good to have one person who's really excited about doing
[29:35] SPEAKER: PowerShell scripting.
[29:36] SPEAKER: Well, because all this stuff has to run on Windows, right?
[29:41] SPEAKER: You run this on Windows because that's where your environment is and if you're shipping
[29:45] SPEAKER: to Xbox, I guess they'd probably let you build on Linux now.
[29:49] SPEAKER: But realistically, you're going to run on Windows for most of this if you're a small
[29:52] SPEAKER: studio.
[29:53] SPEAKER: That makes sense.
[29:54] SPEAKER: If anybody, any game devs listening to this, I want to write in, I wonder if the WSL2 changes
[30:00] SPEAKER: that at all.
[30:01] SPEAKER: Like if Linux build environment on Windows is more viable now that that's a factor.
[30:05] SPEAKER: So we set that stuff up.
[30:07] SPEAKER: Well, you could definitely build a Linux build on Windows.
[30:09] SPEAKER: Oh, a Linux build, yes.
[30:10] SPEAKER: I'm talking about-
[30:11] SPEAKER: We could build a Linux build no problem if we wanted.
[30:13] SPEAKER: Supporting a Linux build is a whole other issue.
[30:14] SPEAKER: No, no.
[30:15] SPEAKER: I meant like managing your whole build and environment.
[30:17] SPEAKER: That probably doesn't make sense.
[30:18] SPEAKER: Like you probably, you want to build for the OS on the OS, right?
[30:22] SPEAKER: Yeah, I don't know what the Unreal Linux situation is.
[30:25] SPEAKER: I know that they have a Linux pipeline, but I bet it's from Windows.
[30:28] SPEAKER: I don't know.
[30:29] SPEAKER: I haven't looked at that.
[30:31] SPEAKER: Supporting Linux is fraught with peril.
[30:36] SPEAKER: I love Linux as much as the next person, I think everybody knows that, but the beautiful
[30:40] SPEAKER: thing this team has done is let us support Linux without having to actually test more
[30:43] SPEAKER: stuff.
[30:44] SPEAKER: Because the other thing is, each of these builds adds testing overhead, right?
[30:48] SPEAKER: Every time you make a new version of the game that you have to release to people, you have
[30:51] SPEAKER: to test stuff.
[30:55] SPEAKER: With a small team testing five versions of the game, even just to test the stuff that
[31:01] SPEAKER: we change from build to build -- we've gone a little bit out of order here -- even just
[31:09] SPEAKER: testing the stuff you change is a huge task.
[31:12] SPEAKER: If you have a patch that has 20 changes and you have five versions, that means you have
[31:16] SPEAKER: to test those 20 changes on five different builds of the game and see what works and
[31:22] SPEAKER: what doesn't.
[31:23] SPEAKER: If there's any weird regressions, it's complicated.
[31:25] SPEAKER: Do you as a studio have a standard suite of tests outside of, like you said, if you change
[31:31] SPEAKER: five things, of course you have to test those five things.
[31:34] SPEAKER: Is there also just a short checklist of these are the basics we have to reconfirm every
[31:39] SPEAKER: single time there's a new build that these work?
[31:41] SPEAKER: That would be a good idea.
[31:43] SPEAKER: I mean, obviously, that's constrained by resources and human power.
[31:48] SPEAKER: Yeah.
[31:49] SPEAKER: I mean, we do have a list of things that we test, but also the game's early access.
[31:54] SPEAKER: If we were releasing -- we're a relatively small game, we're in early access, and also
[32:01] SPEAKER: we can move quickly, so we can release a follow-up patch within a day, basically.
[32:06] SPEAKER: We typically ask our wonderful community of players to help with that kind of stuff and
[32:11] SPEAKER: let us know if we've done something really bad.
[32:15] SPEAKER: Because the challenge of, hey, if we change something about the way matchmaking works,
[32:21] SPEAKER: we can test matchmaking a little bit internally, but not really.
[32:24] SPEAKER: We can't test across regions and stuff like that, because we only have people in the United
[32:27] SPEAKER: States.
[32:30] SPEAKER: It's difficult for us to find out if we've actually messed something up with matchmaking
[32:36] SPEAKER: until it's actually on the live game, is the unfortunate thing.
[32:39] SPEAKER: My assumption is, people might be listening and thinking, well, if you only change five
[32:44] SPEAKER: things, why do you have to test anything other than five things?
[32:46] SPEAKER: But my assumption is that it's very hard to predict second- and third-order consequences
[32:52] SPEAKER: of seemingly -- I mean, it's straight up a butterfly flaps its wings on map two and type
[32:59] SPEAKER: stuff.
[33:00] SPEAKER: I don't know.
[33:01] SPEAKER: So yeah, a lot of stuff's interconnected.
[33:02] SPEAKER: A lot of stuff's -- for example, the attenuation profiles for environment sounds in the game
[33:07] SPEAKER: are often shared across levels, which is a choice somebody made a long time ago that
[33:13] SPEAKER: seems crazy now.
[33:14] SPEAKER: [laughs]
[33:15] SPEAKER: It's on you to this day.
[33:17] SPEAKER: Yeah.
[33:18] SPEAKER: It means that if I change how far away you can hear a fan on level one of episode one,
[33:23] SPEAKER: then all of a sudden, a big, huge blower on episode five or four is going to sound like
[33:27] SPEAKER: a jet engine, and I won't know it until I play episode four three days later.
[33:34] SPEAKER: The better example of that probably is something like the player's collision capsule had to
[33:40] SPEAKER: change a few months ago.
[33:47] SPEAKER: Whoever wrote the AI code for the bots, when a player gets gooed and our game gets incapacitated,
[33:52] SPEAKER: you shoot them to knock the goo off of them and free them.
[33:55] SPEAKER: The person who wrote the bots was like, "Oh, the player collision capsule's a little bit
[33:58] SPEAKER: off, so I'll just aim at the 20 units right of the collision capsule in Cartesian space
[34:06] SPEAKER: to free them when they get gooed, and it'll just work itself out."
[34:09] SPEAKER: That was great, until we fixed the collision capsule, and now all the bots are shooting
[34:13] SPEAKER: 20 units to the right of where the player actually is, so the bots just don't ever free
[34:20] SPEAKER: players anymore.
[34:23] SPEAKER: We find that out because we play every day.
[34:25] SPEAKER: That's a bad example of that.
[34:30] SPEAKER: If we change something about the way you invite friends to the game on Steam, and that had
[34:34] SPEAKER: knock-on effects on Xbox, we might not think to check that, because who knows?
[34:40] SPEAKER: That's what build servers do.
[34:42] SPEAKER: They make the game, they turn the code into game, and then they push the game to the server,
[34:46] SPEAKER: if you've said that, to the platforms.
[34:48] SPEAKER: From there, you can go to a UI thing and push the build live, where you open up a web interface
[34:53] SPEAKER: someplace and you're like, "Okay, I want this upload to be the live game on servers right
[34:57] SPEAKER: now."
[34:58] SPEAKER: I want to ask more about the build process.
[35:00] SPEAKER: I don't want to get too much into the weeds, and I also don't know how much of it you set
[35:02] SPEAKER: up yourself.
[35:03] SPEAKER: I didn't set up any of the build process.
[35:06] SPEAKER: I didn't know how to go in and press the button to make a build.
[35:09] SPEAKER: Maybe that answers the question, because I was going to ask if there is just a button
[35:12] SPEAKER: to press, at least with Unreal these days, like you're not necessarily running.
[35:16] SPEAKER: I'm curious about which compiler is being used, and what's the build environment and
[35:20] SPEAKER: the tool chain look alike and stuff, but I'm guessing that at least with a commercial engine,
[35:24] SPEAKER: that's probably all pretty much dictated and set up by the engine.
[35:28] SPEAKER: Yeah, so that's all Unreal stuff.
[35:30] SPEAKER: We use some of the stuff we use, like the different APIs that we use from Microsoft
[35:36] SPEAKER: for the Xbox stuff, and all that have different requirements for Visual C and XNA, or X and
[35:41] SPEAKER: whatever the current Xbox backend stuff is called, whatever their API package is called.
[35:51] SPEAKER: That's all set up in the scripts for the compiling scripts with the building scripts that somebody
[35:55] SPEAKER: set up for TeamCity two years ago, at this point probably three years ago.
[35:58] SPEAKER: Interesting.
[35:59] SPEAKER: There are starting to be some open source game engines out there now, and I'm sure those
[36:05] SPEAKER: types of questions are maybe more relevant there.
[36:06] SPEAKER: I'm sure they automate some of that stuff, too.
[36:09] SPEAKER: Just to be clear, this isn't Unreal automation.
[36:11] SPEAKER: This is stuff that we built internally.
[36:14] SPEAKER: This is why TeamCity is a product we pay for, that takes the stuff that I could build -- just
[36:22] SPEAKER: to be clear, I could load up my computer in Unreal right now and hit a button that says,
[36:26] SPEAKER: "Hey, make an Xbox version of this game."
[36:28] SPEAKER: I guess I don't have Visual C installed, but if I did, Visual Studio installed it.
[36:31] SPEAKER: If I did, then I could make a version of the game that I could upload to the Microsoft
[36:35] SPEAKER: backend or to Steam, and people would be able to play.
[36:38] SPEAKER: But, in order to do that, it's going to tie up my computer for an hour and a half, and
[36:43] SPEAKER: then I'm going to have to manually upload it.
[36:45] SPEAKER: Actually, Steam doesn't let you upload stuff bigger than a certain size, so I'd have to
[36:48] SPEAKER: get the Steam command line tool to upload it and all the credentials and all that stuff.
[36:53] SPEAKER: This is a way to manage -- what a build server does is give you a way to make those builds
[36:59] SPEAKER: without having to give everybody in the organization the Steam keys and the Xbox keys and all the
[37:04] SPEAKER: crypto stuff that you need to sign the Xbox games and all of that stuff.
[37:08] SPEAKER: So, it lets you keep your information secure that's important to the thing, but also more
[37:15] SPEAKER: widely distribute the ability to actually make the game than just one person.
[37:20] SPEAKER: Yeah, that's fascinating to think about Steam as a development tool in that context and
[37:23] SPEAKER: not as an end-user distribution platform.
[37:25] SPEAKER: Like, four of four, like you said, build management and dispersal to people who don't necessarily
[37:33] SPEAKER: need to worry about that sort of thing on the team.
[37:36] SPEAKER: And it's also worth mentioning that Steam is really neat, because they give you the
[37:39] SPEAKER: ability to put infinite -- A, they let developers hand out keys without having to pay for them
[37:45] SPEAKER: or something stupid like that.
[37:47] SPEAKER: B, they also let you do branches, so you can do betas and stuff like that that are either
[37:52] SPEAKER: public or private.
[37:53] SPEAKER: People use them for all sorts of interesting stuff.
[37:55] SPEAKER: The other day, I was poking around dead cells, and they have in their beta branches public
[38:02] SPEAKER: versions of every past version of dead cells, I think, is in there.
[38:06] SPEAKER: So, if you want to go back and play launch dead cells, you can.
[38:09] SPEAKER: That's cool.
[38:10] SPEAKER: Yeah.
[38:11] SPEAKER: Like, if you have a server backend infrastructure, obviously that's not going to work.
[38:15] SPEAKER: But you can do whatever you want.
[38:17] SPEAKER: When we wanted to test versus publicly, like semi-publicly, we could just generate a branch
[38:25] SPEAKER: with a passcode on it and share that with the community, then people could load it up
[38:29] SPEAKER: and play the game.
[38:30] SPEAKER: Yeah.
[38:31] SPEAKER: Like, all the Steam developer docs largely are public.
[38:35] SPEAKER: You can go read about a lot of that stuff.
[38:36] SPEAKER: Like, I've looked into some of how the backend branching stuff works, and they give you an
[38:40] SPEAKER: amazing amount of granular control over who has access to a given branch and stuff like
[38:45] SPEAKER: that.
[38:46] SPEAKER: Yeah.
[38:47] SPEAKER: And it's up to us, then, to make sure that we don't share, for example, the branch with
[38:52] SPEAKER: the developer credentials or whatever that kind of stuff is in there.
[38:57] SPEAKER: Yeah.
[38:58] SPEAKER: Well, real quick before we move on, just to touch on a couple of the open source game
[39:03] SPEAKER: engines that I mentioned.
[39:04] SPEAKER: Godot is the big one that I hear about for the most part.
[39:07] SPEAKER: G-O-D-O-T.
[39:08] SPEAKER: Yeah.
[39:09] SPEAKER: We're waiting for it still.
[39:10] SPEAKER: Yes.
[39:11] SPEAKER: I bet they get that a lot.
[39:13] SPEAKER: Look, they named the game engine.
[39:15] SPEAKER: It's their own fault.
[39:16] SPEAKER: I guess you may have a point there.
[39:19] SPEAKER: It's not like me, where I was named Will Smith, and then 20 years later, somebody got famous.
[39:23] SPEAKER: They knew what Godot was when they named it that.
[39:25] SPEAKER: Yes.
[39:26] SPEAKER: I mean, I don't know if this is true, or I can't say for sure this is true, but I kind
[39:30] SPEAKER: of see Godot spoken about a lot in the context of Unity.
[39:33] SPEAKER: I see a lot of, like every time Unity does something unpopular, I'll see some game developers
[39:37] SPEAKER: on Twitter say, "Well, maybe it's time to finally start learning Godot."
[39:40] SPEAKER: So I wonder if it has similar application or similar amount of scope.
[39:44] SPEAKER: I would say disaffection with Unity seems to be pretty high in my communities right
[39:48] SPEAKER: now.
[39:51] SPEAKER: I haven't looked at Godot yet.
[39:52] SPEAKER: I don't know where Godot's at.
[39:53] SPEAKER: There's also Bevy.
[39:54] SPEAKER: I don't know about that one.
[39:55] SPEAKER: I don't know about that one.
[39:56] SPEAKER: I think it is pretty, I shouldn't say limited, I get the sense it's fairly early.
[40:01] SPEAKER: It's written in Rust.
[40:02] SPEAKER: Okay.
[40:03] SPEAKER: And there's some people on our Discord have spoken highly of it or at least have, I think,
[40:08] SPEAKER: enjoyed tinkering with it.
[40:11] SPEAKER: It's hard to not do a commercial product if you're spending, like if you think about your
[40:18] SPEAKER: investment in a commercial game engine versus the payroll of your small studio, even like
[40:27] SPEAKER: with five or six people, it's scary to not have, like, I don't know that Godot has a
[40:33] SPEAKER: support infrastructure around it at this point that's adequate.
[40:37] SPEAKER: Yeah, you absolutely want like proper support, commercial support for something like that
[40:41] SPEAKER: in an actual business.
[40:42] SPEAKER: I was throwing that stuff out there more as a, like, if you're curious about this stuff,
[40:47] SPEAKER: here are a couple of free engines you can go to and download and mess with yourself
[40:51] SPEAKER: if you just want to like kind of see how some of these pieces are put together.
[40:53] SPEAKER: I was going to say also, I think both Unity and, so one of the things that surprised me
[40:57] SPEAKER: about all of this stuff is that at small scale, most of the software is relatively inexpensive
[41:01] SPEAKER: or free.
[41:02] SPEAKER: So, for example, our source control per force is free until you have more than five users.
[41:07] SPEAKER: Oh.
[41:08] SPEAKER: Yeah.
[41:09] SPEAKER: I mean, you still have to pay for a server to host it and all, or you have to host it
[41:12] SPEAKER: yourself.
[41:13] SPEAKER: I guess that's kind of, that's like been the model though, right?
[41:16] SPEAKER: Did Unreal kick that off like 15 ish years, maybe 20?
[41:19] SPEAKER: I feel like the first time they did the build something Unreal thing after that, they announced
[41:24] SPEAKER: that you could download it for free and previously it had been like you have to pay a million
[41:27] SPEAKER: dollars to get access to Unreal.
[41:29] SPEAKER: Right.
[41:30] SPEAKER: Which was obviously smart.
[41:31] SPEAKER: Like you want to put the tools in people's hands with barrier to entry and then once
[41:35] SPEAKER: they start making money, you start taking some of that money.
[41:38] SPEAKER: I was just saying that one thing I forgot about on the build server front is that if
[41:42] SPEAKER: you have internal tooling, the build server probably also manages and updates and distributes
[41:46] SPEAKER: that to people.
[41:47] SPEAKER: Okay.
[41:48] SPEAKER: So, for example, we have a custom version of Unreal editor because we modified our Unreal
[41:52] SPEAKER: editor to do things that were specific to the game.
[41:56] SPEAKER: And when we update that, the build server does that and then you run a batch file on
[41:59] SPEAKER: your computer that downloads the latest version of it from a server someplace.
[42:04] SPEAKER: Anyway, yeah, the different game engines, like everybody always wants to talk about
[42:11] SPEAKER: game engines.
[42:12] SPEAKER: And it's funny because as I get further into this, it's more and more clear that really
[42:18] SPEAKER: the game engine matters way less than people think it does.
[42:23] SPEAKER: I'm sure on the developer side, it's a means to an end, right?
[42:26] SPEAKER: Like it's just a tool.
[42:27] SPEAKER: Yeah.
[42:28] SPEAKER: I mean, well, it's a toolbox, right?
[42:31] SPEAKER: Well, yes.
[42:32] SPEAKER: Yes.
[42:33] SPEAKER: Because when you buy Unreal, you're getting all of their...
[42:37] SPEAKER: If you want to make a big ass open world, it turns out Unreal is pretty good at that
[42:40] SPEAKER: because what Epic uses Unreal to make is a big ass open world game, right?
[42:45] SPEAKER: If you want to do destructible stuff, they're good at that.
[42:48] SPEAKER: If you want to ship stuff on mobile, maybe Unreal is not your choice, right?
[42:54] SPEAKER: There are probably better choices than that.
[42:56] SPEAKER: If you want to make a text adventure, Unreal, probably massive overkill, right?
[43:02] SPEAKER: There's much better choices for that.
[43:03] SPEAKER: But there's just a lot of options out there now, which is I think good for everyone.
[43:10] SPEAKER: Yeah.
[43:11] SPEAKER: Yeah.
[43:12] SPEAKER: I mean, a lot of that seems to have come from YouTube and I don't know how to describe like
[43:19] SPEAKER: forum chatter.
[43:20] SPEAKER: I guess it's like a kind of discussion among consumers and users about which game looks
[43:25] SPEAKER: better and runs better and what engine is it on, oh, everybody should use that engine.
[43:29] SPEAKER: Like it's just kind of a very reductive style of discourse.
[43:32] SPEAKER: I'm as guilty of this as the next person.
[43:34] SPEAKER: I did a what you need to know about game engines article in like 2005 for Maximum PC.
[43:41] SPEAKER: And I was like, look, Gabriel, really?
[43:42] SPEAKER: They're doing some crazy stuff up there.
[43:44] SPEAKER: Look at what the people in Norway are doing, the dice, they got cool things going.
[43:48] SPEAKER: And then we all know how to Frostbite turned out.
[43:50] SPEAKER: So my bad.
[43:53] SPEAKER: But yeah, it's more like all those YouTube videos about, oh, I could tell this is a Unity
[43:59] SPEAKER: game cause it has the Unity look what they're, what they're identifying is, Hey, these people
[44:03] SPEAKER: use Unity's default lighting model and which is a fine choice.
[44:09] SPEAKER: I don't know.
[44:10] SPEAKER: It's just YouTube.
[44:12] SPEAKER: I don't like YouTube discourse.
[44:13] SPEAKER: The older I get bread, there should we, should we talk about a source control or QA next
[44:21] SPEAKER: source control was the first topic, but we kind of blew past it a little bit.
[44:24] SPEAKER: It's fine.
[44:25] SPEAKER: Well, we talked about per force.
[44:26] SPEAKER: I mean, the interesting thing here with games to me is that like, when I think about source
[44:31] SPEAKER: control, it's a source, it's a method of versioning, right?
[44:33] SPEAKER: Like just to be clear, it is a method of like keeping your code base in sync between multiple
[44:39] SPEAKER: developers, managing changes and versions that you can roll back to and et cetera, et
[44:43] SPEAKER: cetera.
[44:44] SPEAKER: But when I've always thought about source control, it's purely in the context of text
[44:48] SPEAKER: files, which are code, but then, but then like you mentioned, you've got like, you've
[44:52] SPEAKER: got mass amounts of assets, sounds, textures, sounds like 3D models, Maya files.
[45:01] SPEAKER: And I, and I'm sure this varies between studios, but I like, I wonder how much, I don't know
[45:07] SPEAKER: what the trend is about.
[45:08] SPEAKER: Like do, does a single artist generally kind of have ownership of a model, for example,
[45:11] SPEAKER: like a specific character model, or are there like a bunch of different artists working
[45:14] SPEAKER: on the same model at different times?
[45:16] SPEAKER: So I'm going to say, well, generally only one person can check something out at a time
[45:21] SPEAKER: that's like,
[45:22] SPEAKER: I mean, I mean, successively, like, like, oh, like I'm sure, I'm sure it happens that
[45:27] SPEAKER: maybe somebody else will go back and touch something up if somebody else is busy or whatever.
[45:30] SPEAKER: I'm just wondering how much of those types of assets need to also be versioned and controlled.
[45:34] SPEAKER: All of them.
[45:35] SPEAKER: Cause if you're spending money making them, you should version them.
[45:37] SPEAKER: Of course.
[45:38] SPEAKER: Like, like just realistically, if you have, if you have cost in something, it should be
[45:43] SPEAKER: on your Perforce.
[45:44] SPEAKER: Like we even keep marketing images on the Perforce.
[45:47] SPEAKER: I phrased that poorly.
[45:48] SPEAKER: I meant more just, I wonder how many different people are touching things that aren't because
[45:51] SPEAKER: like code you're constantly collaborating on with different people.
[45:54] SPEAKER: Art is the same.
[45:55] SPEAKER: So there are, there are, I mean, it depends on the scale of your studio.
[45:58] SPEAKER: If you're a one programmer, one artist studio, then one person's doing all the art.
[46:02] SPEAKER: Right.
[46:03] SPEAKER: But if you have 10 people working on the game, then, and eight of them are artists, then
[46:07] SPEAKER: probably eight people will touch a lot of the, six or eight people will touch a lot
[46:10] SPEAKER: of the stuff in the game.
[46:11] SPEAKER: For example, if you're talking about a character, a character is a good example.
[46:18] SPEAKER: So if you want to make a new character for the game, you have a concept artist probably
[46:22] SPEAKER: that draws, draws pictures of what it looks, what the character looks like, shows them
[46:25] SPEAKER: in some different positions, shows some like potential animation ideas, stuff like that.
[46:30] SPEAKER: Then that person hands that, that concept off to a character artist, the character,
[46:34] SPEAKER: and often, oftentimes, especially at a small studio, the character artist, the concept
[46:39] SPEAKER: artist will be somebody who also does other things, they do texture work, or they do like
[46:43] SPEAKER: punching up of environments or something like that.
[46:45] SPEAKER: They're just, they're just good at drawing, too.
[46:46] SPEAKER: You get a twofer with that person if you're lucky.
[46:50] SPEAKER: Sometimes it's the character artist.
[46:52] SPEAKER: The character artist will model that character out if it's a 3D game or draw sprites if it's
[46:55] SPEAKER: a 2D game.
[46:57] SPEAKER: And then the character artist hands the model off to the, to the technical artist.
[47:01] SPEAKER: The technical artist rigs it so that it can move so that it has, you know, so you can
[47:05] SPEAKER: hook it into the animation system of the game and the technical artist hands it to the animator
[47:08] SPEAKER: and the animator puts the animations on it.
[47:11] SPEAKER: That's a, that's a never ending job because, you know, there's thousands of animators,
[47:15] SPEAKER: like, like we have dozens and dozens and dozens of stumble animations in our game for like
[47:19] SPEAKER: aliens when they get shot so that when you shoot them in the legs, they stumble appropriately.
[47:25] SPEAKER: Stumble artist has to take over at that point.
[47:27] SPEAKER: So many stumbles.
[47:28] SPEAKER: But yeah, I think that's where I was being reductive or overly simplifying the situation.
[47:32] SPEAKER: I didn't, I guess I didn't realize all those disciplines had like abstracted out into different
[47:36] SPEAKER: roles as much as they apparently have, like I kind of was thinking of it from probably
[47:40] SPEAKER: a very old fashioned, like full stack, like, well, if you model it and then you animate
[47:44] SPEAKER: it and then it's done.
[47:45] SPEAKER: Right.
[47:46] SPEAKER: But it sounds like that those, I'm sure just like everything else, things get so complicated
[47:50] SPEAKER: that they have to spin out into different roles.
[47:52] SPEAKER: Right.
[47:53] SPEAKER: Yeah.
[47:54] SPEAKER: And each of those has different strengths, right?
[47:55] SPEAKER: Like the person who's good at sculpting a soft body model is maybe not going to be great
[47:59] SPEAKER: at figuring out how the movement should work for them.
[48:02] SPEAKER: Right.
[48:03] SPEAKER: Because doing animating is really hard, doing the rig is a technically challenging job that
[48:09] SPEAKER: also requires people to like, like technical artist is one of those technical artists is
[48:16] SPEAKER: like associate editor in the publishing business, right?
[48:18] SPEAKER: An associate editor, depending on which publisher, which, which, which, whether you're at a magazine
[48:22] SPEAKER: or website or what magazine or website you're at an associate editor could be the lowest
[48:26] SPEAKER: person on the totem pole, or it could be the person who does the vast majority of work
[48:30] SPEAKER: on the publication, like the frontline work, and then all of their work gets filtered up
[48:35] SPEAKER: through other people.
[48:36] SPEAKER: Right.
[48:37] SPEAKER: A technical artist is they can be doing rigs for character models or for anything that
[48:42] SPEAKER: moves in the game.
[48:43] SPEAKER: They can be writing shaders.
[48:44] SPEAKER: They can be helping the VFX artists with, with like, with like writing scripts to, to,
[48:50] SPEAKER: to make the VFX work.
[48:52] SPEAKER: They can be hooking stuff like virtual visual effects into the game.
[48:55] SPEAKER: Right.
[48:56] SPEAKER: They can be building particle systems or lighting models or all sorts of like crazy, crazy,
[49:01] SPEAKER: broad spectrum.
[49:03] SPEAKER: But a lot of that work is stuff like rigging skeletons on, on and rigging, rigging character
[49:09] SPEAKER: meshes.
[49:10] SPEAKER: Anyway.
[49:11] SPEAKER: So yeah, everybody touches everything.
[49:14] SPEAKER: And like when, when you get all that done, then an engineer has to hook it into the,
[49:18] SPEAKER: into the game, like has to actually put it in and say, okay, this can be it, but in the
[49:21] SPEAKER: spawn tables, here's the AI for it.
[49:24] SPEAKER: Here's the, here's the, here's the, the game, the gameplay designer will say, here's what
[49:28] SPEAKER: it, what?
[49:29] SPEAKER: Okay.
[49:30] SPEAKER: It has an attack.
[49:31] SPEAKER: It has a ranged attack.
[49:32] SPEAKER: It's gonna be a fireball.
[49:33] SPEAKER: It's gonna be an ice ball.
[49:34] SPEAKER: Is it going to be a laser?
[49:35] SPEAKER: Is it going to be him picking up rocks from the ground and throwing them at you?
[49:38] SPEAKER: And, and like, so 20 people will touch that even if it's a 10 person studio, somehow,
[49:42] SPEAKER: I don't know how that works, but
[49:43] SPEAKER: That'll make sense.
[49:46] SPEAKER: So, so you, you fall to use Perforce, is that like super common, would you say in game development?
[49:51] SPEAKER: So in, in like tech world, get is what people get, get is what people seem to use.
[49:59] SPEAKER: Engineers like get, cause it's really good at doing code.
[50:01] SPEAKER: There's a lot of, a lot of, a lot of good command line tools, so you can just jam out
[50:05] SPEAKER: commits really fast.
[50:06] SPEAKER: Right.
[50:07] SPEAKER: Yeah.
[50:08] SPEAKER: I'm, I'm, I'm thinking more once, once a mass quantity of binary assets are also involved,
[50:11] SPEAKER: like, like I, like I said, traditionally, I think of, of get as, as a text only thing,
[50:16] SPEAKER: but, but you've, you've mentioned here, GitHub LFS, is that a, what is, what is that?
[50:20] SPEAKER: Yeah.
[50:21] SPEAKER: It's their binary, is their binary tool.
[50:24] SPEAKER: We use LFS at, at foo with kind of mixed results.
[50:28] SPEAKER: It was fine.
[50:29] SPEAKER: It was also brand new when we were using it at foo.
[50:31] SPEAKER: So I'm sure, I'm sure it's come along pretty nicely.
[50:34] SPEAKER: I think it stands for large file system, but I'm not a large file storage.
[50:38] SPEAKER: And it basically gives you versioning on, on binary assets.
[50:42] SPEAKER: It's a little like Perforce has been around for a long time.
[50:46] SPEAKER: You probably, if you're a small team and you've had somebody who works in dev ops or on production
[50:49] SPEAKER: or whatever at a studio, they probably know how to use Perforce.
[50:53] SPEAKER: It's not particularly complicated to set.
[50:55] SPEAKER: It's it requires a fair amount of touching, but it isn't, it isn't complicated touching,
[51:00] SPEAKER: if that makes sense.
[51:02] SPEAKER: And, and also as with many things, the fact that you're, that most of the people you'll
[51:09] SPEAKER: hire in know how to probably use Perforce is important.
[51:16] SPEAKER: The big thing you get from source control is the ability to roll stuff back.
[51:18] SPEAKER: If you make a change, you don't like it.
[51:19] SPEAKER: You can say, "OK, I only want to do this part of this change," or whatever.
[51:22] SPEAKER: Perforce does that.
[51:23] SPEAKER: The knock against Perforce is it's expensive.
[51:26] SPEAKER: Like, GitHub, both from a licensing perspective per user and from a hosting perspective, it
[51:34] SPEAKER: can be pretty unwieldy.
[51:36] SPEAKER: Part of that is because game assets get large.
[51:39] SPEAKER: I think at one point, our Perforce repo was two terabytes because we had versions of all
[51:45] SPEAKER: sorts of old versions of different stuff and weird offshoot projects and all sorts of other stuff.
[51:52] SPEAKER: But you can't self-host it.
[51:53] SPEAKER: You can put it on a machine in your premises, then you're responsible for figuring out how
[51:55] SPEAKER: to back it up and all that stuff.
[51:58] SPEAKER: But it is a thing you can do.
[52:02] SPEAKER: You can also put it on a $300 a month colo machine someplace, and it'd probably be fine.
[52:10] SPEAKER: It's free, it's one of those things that's free for the first five people, and then once
[52:14] SPEAKER: you go beyond that, you have to talk to somebody and they're like, "OK, here's what we're going
[52:17] SPEAKER: to charge you."
[52:19] SPEAKER: Call for a quote.
[52:20] SPEAKER: If you have to ask, you're in too deep.
[52:25] SPEAKER: But it's reliable and good, and it's what most game studios use, is my understanding,
[52:30] SPEAKER: if they can afford it.
[52:33] SPEAKER: They actually built an add-on for the engineers so that you can just interface with your Perforce
[52:38] SPEAKER: repo through Git now, which I thought was pretty funny.
[52:41] SPEAKER: That's pretty good.
[52:44] SPEAKER: Your Git commits into Perforce now.
[52:46] SPEAKER: That's the build environment equivalent of using the Vim bindings in VS code.
[52:51] SPEAKER: It really and truly is.
[52:58] SPEAKER: I mean, that's kind of it.
[52:59] SPEAKER: It's source control, man.
[53:00] SPEAKER: It's important.
[53:01] SPEAKER: Here's my question.
[53:03] SPEAKER: Who manages all of this stuff?
[53:05] SPEAKER: Because between the source control and the build server, it seems like you would need
[53:08] SPEAKER: a full-time person just to focus on doing all of this.
[53:13] SPEAKER: It's one of those things that like when we set up the company and when we first started
[53:16] SPEAKER: doing daily builds, one of our engineers set all this stuff up, right?
[53:20] SPEAKER: OK.
[53:21] SPEAKER: Maybe it is automated enough that you'd actually...
[53:23] SPEAKER: I was asking that somewhat facetiously because I was expecting an answer of like, "Yeah,
[53:27] SPEAKER: it sure would be nice to have somebody to focus on just this, but maybe it actually
[53:32] SPEAKER: is more sustainable than it used to be, or than it sounds."
[53:36] SPEAKER: Well, so for a long time, we were doing a cloud host for the Perforce, which was expensive
[53:40] SPEAKER: but nice because we didn't have to do any server maintenance stuff.
[53:45] SPEAKER: The server maintenance, it's not turnkey, but it's like, "Hey, you can spend a couple
[53:49] SPEAKER: hours a month working on something and it's probably fine."
[53:54] SPEAKER: If something breaks, then everything stops while you fix that.
[53:58] SPEAKER: That's kind of what I was thinking about.
[53:59] SPEAKER: This is a weird tangential example, but it made me think back to which Pixar movie?
[54:03] SPEAKER: Was it "Toy Story 2," I think?
[54:04] SPEAKER: "Toy Story 2," yeah.
[54:05] SPEAKER: "Toy Story 2," you can read about this.
[54:08] SPEAKER: There are articles from the time describing this.
[54:10] SPEAKER: They basically lost the movie.
[54:12] SPEAKER: There's a bonus feature.
[54:13] SPEAKER: There's a short on the DVD.
[54:15] SPEAKER: It's on YouTube.
[54:16] SPEAKER: I think you guys did some stuff around that, didn't you?
[54:21] SPEAKER: I thought I saw some tested work cited as reading about that.
[54:24] SPEAKER: When they posted it, Wes did a short post about it, I believe.
[54:28] SPEAKER: That's what I was thinking of.
[54:30] SPEAKER: Anyway, the whole studio ground to a halt because it was all hands on deck trying to
[54:33] SPEAKER: recover stuff, work that had been lost.
[54:36] SPEAKER: I was just thinking along those same lines, if something bad happens where backups need
[54:41] SPEAKER: to be restored or X, Y, Z, it seems like having somebody who was permanently on top of that
[54:46] SPEAKER: situation would be better than having to pull people off of their actual work to fix things.
[54:51] SPEAKER: Well, yeah, but also you have to pay that person the time when there's nothing bad happening.
[54:55] SPEAKER: So pros and cons.
[54:57] SPEAKER: Again, this is one of those places where being a Swiss army knife is sometimes useful because
[55:03] SPEAKER: if you're looking for an indie studio job and somebody's like, "Hey, what else do you
[55:06] SPEAKER: know besides the thing that you do 20 days a month?"
[55:11] SPEAKER: And they're like, "Oh, well, I ran the Perforce server at my last studio."
[55:15] SPEAKER: I was like, "Oh, OK."
[55:18] SPEAKER: Somebody says I love PowerShell scripting in a job interview, you're like, "Fuck, yes.
[55:22] SPEAKER: You're my boy."
[55:23] SPEAKER: And then back away slowly.
[55:24] SPEAKER: Yeah, no, and then you never talk to that person again.
[55:30] SPEAKER: So I was gonna say the last thing that people don't think about, I think often, is that
[55:34] SPEAKER: you have to have some core source of truth.
[55:37] SPEAKER: So you need a place that everyone has access to that you put your documentation for how
[55:43] SPEAKER: to do stuff in the game.
[55:45] SPEAKER: So for example, if you want to put a new sound into Wwise, here's the process for doing that
[55:50] SPEAKER: with our game because it's different for every single game on the face of the earth because
[55:56] SPEAKER: when you get Wwise, you get access to source code and people make source code changes and
[56:00] SPEAKER: they build tools that work specifically with your type of game.
[56:03] SPEAKER: Our game has a bazillion external lines of dialogue that are triggered by things that
[56:07] SPEAKER: happen in gameplay.
[56:11] SPEAKER: Wwise isn't set up for that.
[56:12] SPEAKER: We have a system that triggers that in the game and then hands off the audio file to
[56:18] SPEAKER: trigger to Wwise and then Wwise just plays the audio file.
[56:21] SPEAKER: That's a completely non-standard way to do that.
[56:23] SPEAKER: Normally, you would just put the dialogue into Wwise and then build a bunch of independent
[56:26] SPEAKER: triggers and it would have been an unbelievable amount of work on our end to hook all that
[56:31] SPEAKER: up.
[56:32] SPEAKER: I can tell you from having fiddled with a zillion open source projects at this point
[56:35] SPEAKER: and also having recently done a couple of very small utilities myself, it seems very
[56:39] SPEAKER: easy to build bespoke functionality and then not document how to use it.
[56:43] SPEAKER: Look, I don't want to pick on the person who did this because they started on the right
[56:47] SPEAKER: path and then got distracted and did something else, which happens a lot at small studios.
[56:52] SPEAKER: But I was looking for how to add this the other day, and I went to the Wiki page for
[56:59] SPEAKER: it.
[57:00] SPEAKER: The thing I saw was, this page is a stub.
[57:03] SPEAKER: So, you know...
[57:06] SPEAKER: Barker, everyone loves a stub.
[57:07] SPEAKER: Hill: Yeah, everybody loves a stub.
[57:10] SPEAKER: So, you want core source of truth for both documentation.
[57:13] SPEAKER: You want to also have work that needs to be done, a place to put tasks that's shared across
[57:18] SPEAKER: the team.
[57:19] SPEAKER: There's a lot of stuff that anybody can do, or any subset of the team can do.
[57:24] SPEAKER: You just want to have a bin of things to work on.
[57:29] SPEAKER: The way we often would work is, if we had a four-month loop on a patch, on a big patch,
[57:34] SPEAKER: we would spend a four-week loop on a patch.
[57:39] SPEAKER: We would spend two weeks working on features, and then the third week would be all the bugs
[57:45] SPEAKER: that we found in that time period, in that two weeks, would go into a bug bin.
[57:50] SPEAKER: Then, the engineers and the artists and everybody who didn't have other stuff to be doing would
[57:54] SPEAKER: just sit and mow down those lists of bugs.
[57:58] SPEAKER: They'd grab the first one out of the pool that they looked like they knew how to fix
[58:01] SPEAKER: and tackle it.
[58:02] SPEAKER: Barker, I assume that's where terms like "agile" and "scrum" come in.
[58:06] SPEAKER: Those are just different philosophies for tackling project management and flow and scheduling
[58:12] SPEAKER: and stuff.
[58:13] SPEAKER: Kline>> Yeah, they're a higher concept than that.
[58:19] SPEAKER: If you think about personal organization and scheduling, like the 40 boxes or whatever,
[58:25] SPEAKER: that thing, they're frameworks in which you can manage a team's time across disciplines.
[58:38] SPEAKER: I think the core -- I'm bad at this, because this isn't the side of the stuff I ever do.
[58:42] SPEAKER: I think the idea of "agile" is that you ship every X period of time, and you devote a certain
[58:48] SPEAKER: percentage of that time to new stuff, and a certain percentage of that time to fixing
[58:52] SPEAKER: bugs, and a certain percentage of that time to doing -- "scrum" is a little bit of a different
[58:56] SPEAKER: approach.
[58:57] SPEAKER: Barker, I'm throwing out, clearly, jargon that I cannot well define myself.
[59:03] SPEAKER: The point is, there are entire modes of thinking built around making this stuff more efficient.
[59:09] SPEAKER: Kline>> Yeah, this is all stuff that came from somebody reading the Mythical Man month
[59:12] SPEAKER: 20 years ago.
[59:13] SPEAKER: Barker, yes.
[59:14] SPEAKER: I remember hearing about that book in the 90s from game developers, or seeing them talk
[59:18] SPEAKER: about it.
[59:19] SPEAKER: Kline>> Yeah, well, the idea of the Mythical Man month is that if you have a project that's
[59:25] SPEAKER: going to take one person two months, and you add two people, it's going to take three months
[59:29] SPEAKER: instead of two months, instead of one month.
[59:34] SPEAKER: So yeah, the idea is that you have to build in some way to communicate and some way to
[59:39] SPEAKER: share information.
[59:40] SPEAKER: That's what a lot of these tools are for.
[59:41] SPEAKER: A lot of people use Wikis.
[59:44] SPEAKER: Confluence is just a hosted wiki platform that's private, and you can build docs in
[59:49] SPEAKER: relatively easily.
[59:50] SPEAKER: People use Notion and stuff like that for that, as well.
[59:52] SPEAKER: Barker, I feel like Trello picked up some steam, because when Epic launched the Epic
[59:57] SPEAKER: store, they published their Trello board publicly for people to look at to see what they were
[1:00:01] SPEAKER: working on.
[1:00:02] SPEAKER: Kline>> So, publishing public Trello boards was very popular five years ago.
[1:00:07] SPEAKER: That's just become a thing that people do, especially if you're an early access title
[1:00:10] SPEAKER: or something like that.
[1:00:11] SPEAKER: It's good to have a public Trello, because people understand it.
[1:00:13] SPEAKER: Trello is more in the task management side.
[1:00:17] SPEAKER: The idea Trello, Jira, stuff like that are what often do that.
[1:00:25] SPEAKER: With Trello, you break down individual tasks and subtasks.
[1:00:30] SPEAKER: For example, in our building a new character model aspect, you'd have a Trello or a Jira
[1:00:35] SPEAKER: task that was, "Hey, add character model X to the game."
[1:00:40] SPEAKER: Then there'd be subtasks for concept, creating the character model, rigging the model, doing
[1:00:46] SPEAKER: the base animations you need to get in the game, adding the gameplay design, adding it
[1:00:50] SPEAKER: to the game, hooking it up to the spawn tables, and stuff like that.
[1:00:56] SPEAKER: Depending on how big the team is, that can be anywhere from a thing that somebody does
[1:01:02] SPEAKER: as part of their job, or if you have a conscientious small team, everybody can just do it.
[1:01:08] SPEAKER: Everybody manages their own stuff, and then you go through and work down the list together.
[1:01:13] SPEAKER: If you have a Ubisoft-sized Assassin's Creed team, I assume they have 20 people at each
[1:01:21] SPEAKER: studio that do that work.
[1:01:23] SPEAKER: They have people on the individual teams.
[1:01:25] SPEAKER: They have some sort of core.
[1:01:28] SPEAKER: If anybody at Ubisoft wants to share how you do this, I'm fascinated by it, because it
[1:01:32] SPEAKER: seems like a nightmarish job.
[1:01:34] SPEAKER: I'm sure they hand out tasks like, "Make Rome to Ubisoft Shanghai."
[1:01:42] SPEAKER: Then there are notes in there of places that have to exist.
[1:01:45] SPEAKER: It has to have the Coliseum, it has to have the blah, blah, blah.
[1:01:52] SPEAKER: From there, the individual teams at the individual studios parse out what they're working on.
[1:02:00] SPEAKER: Because of the scale of that art and the size of that art, I'm sure that Ubisoft Shanghai
[1:02:05] SPEAKER: works on one part of the map, and somebody works on a different part of the map.
[1:02:08] SPEAKER: Same thing for Fortnite.
[1:02:09] SPEAKER: Fortnite has a bazillion contributors for it now.
[1:02:16] SPEAKER: People call that a producer, is what it often ends up being.
[1:02:21] SPEAKER: Those are folks that manage the Trello, manage the Jira, manage the Confluence, and help
[1:02:28] SPEAKER: keep the whole team on time.
[1:02:30] SPEAKER: Honestly, having a good, well-populated Jira with the actual tasks helps you know how much
[1:02:35] SPEAKER: time stuff's going to take more than anything else.
[1:02:38] SPEAKER: They're always outliers in a bug that'll take one person four days to figure out, or a week
[1:02:42] SPEAKER: to figure out.
[1:02:43] SPEAKER: Often, if it's building a new map for the game, you know that's going to be a month
[1:02:51] SPEAKER: for an environment artist, and that's all they're going to do that month.
[1:02:53] SPEAKER: You can just put that down and know that's what they're going to do.
[1:02:57] SPEAKER: Then it'll be another three months to pretty that up after they've done the first pass.
[1:03:01] SPEAKER: That's so crazy to think about.
[1:03:03] SPEAKER: Again, I know I keep referencing this, but coming off that Romero book, reading about
[1:03:06] SPEAKER: some of his stories about staying up all night and making an entire Doom map, it's just like,
[1:03:12] SPEAKER: "I just decided to stay up all night, and by 6 a.m., I had a finished map that ended
[1:03:15] SPEAKER: up in Doom II."
[1:03:18] SPEAKER: Just the complexity, the increase, the orders of magnitude increase in complexity in building
[1:03:22] SPEAKER: things like environments in the last 20, 30 years.
[1:03:26] SPEAKER: Building from 2D to 3D was a big one.
[1:03:28] SPEAKER: But then, think about the fidelity.
[1:03:30] SPEAKER: I think what Quake 1 characters were, like, 300 polys or something.
[1:03:37] SPEAKER: You think about that versus a normal mapped, modern, first-person shooter game character
[1:03:41] SPEAKER: that's a million polys, effectively.
[1:03:49] SPEAKER: This is why, if you want to make a game with a small team, you don't make something that
[1:03:52] SPEAKER: looks like Metal Gear Solid 5 or Call of Duty or whatever.
[1:03:56] SPEAKER: It's because it's too many people.
[1:03:57] SPEAKER: There are more people making guns in Call of Duty than working on most indie teams,
[1:04:02] SPEAKER: I think, at this point.
[1:04:04] SPEAKER: That checks out.
[1:04:05] SPEAKER: Yeah.
[1:04:06] SPEAKER: That's why the guns are all animated and cool.
[1:04:09] SPEAKER: When they do those cool animations where the guy is running and he looks at his gun as
[1:04:12] SPEAKER: he's running, he holds up and does something you've never seen him do before, somebody
[1:04:16] SPEAKER: spent a month working on that.
[1:04:18] SPEAKER: I'm guessing that's a month that a lot of smaller studios don't have.
[1:04:22] SPEAKER: Seems like a bad way to spend your money.
[1:04:26] SPEAKER: Trello's good.
[1:04:27] SPEAKER: It gives you public visibility.
[1:04:31] SPEAKER: It's important to have that shared source of truth, so that if somebody gets hit by
[1:04:35] SPEAKER: a bus or somebody doesn't have time to ... Honestly, it's just nice, so you don't have to go ask
[1:04:41] SPEAKER: the person who knows how to do everything how to do everything to have that documentation.
[1:04:47] SPEAKER: You're buying future time for yourself when you write good docs.
[1:04:52] SPEAKER: So, that's it.
[1:04:53] SPEAKER: There's a ton of stuff we didn't talk about here that other people ... Also, the important
[1:04:58] SPEAKER: thing to think about with games, every single game is different from every other game, including
[1:05:05] SPEAKER: sequels inside the same studios.
[1:05:07] SPEAKER: Everybody has different processes.
[1:05:10] SPEAKER: What is a producer at one job?
[1:05:11] SPEAKER: Is a publisher at a different one?
[1:05:14] SPEAKER: There's all sorts of DevOps stuff.
[1:05:18] SPEAKER: This all lives under the shell of DevOps, I think.
[1:05:22] SPEAKER: It's kind of crazy.
[1:05:23] SPEAKER: It's a weird thing.
[1:05:24] SPEAKER: I don't think I've heard a whole lot of people talk about it publicly, so maybe our nerdy
[1:05:30] SPEAKER: audience will enjoy it.
[1:05:31] SPEAKER: I hope you like this.
[1:05:32] SPEAKER: Yeah.
[1:05:33] SPEAKER: Hopefully this gives some insight into the nuts and bolts part of getting a video game
[1:05:37] SPEAKER: out the door.
[1:05:38] SPEAKER: Yeah.
[1:05:39] SPEAKER: The big thing for me was realizing that realistically, most of the time when you make a change to
[1:05:45] SPEAKER: the game, you're not going to get to test it in the game until the next day at the earliest.
[1:05:51] SPEAKER: It's not like you press compile, and then it's on the test version of your iPhone in
[1:05:55] SPEAKER: 10 minutes, like a phone app.
[1:05:58] SPEAKER: Yes.
[1:05:59] SPEAKER: So, anyway.
[1:06:00] SPEAKER: Making games.
[1:06:01] SPEAKER: Game dev.
[1:06:02] SPEAKER: Making games.
[1:06:03] SPEAKER: Nobody should do it.
[1:06:04] SPEAKER: Every game is a miracle.
[1:06:05] SPEAKER: Whoa.
[1:06:06] SPEAKER: All right.
[1:06:07] SPEAKER: Making games is...
[1:06:08] SPEAKER: I enjoy making games, but it is...
[1:06:11] SPEAKER: We're pushing a patch this morning, actually.
[1:06:13] SPEAKER: Look, you're not the first nor the 10th developer I've heard say something like that.
[1:06:18] SPEAKER: Yeah.
[1:06:19] SPEAKER: That's a pretty widely held opinion.
[1:06:21] SPEAKER: Basically the fact that any game ever ships is a surprise to me.
[1:06:24] SPEAKER: When somebody ships a game, they're like, "How did they ship this when it had this many
[1:06:27] SPEAKER: bugs?"
[1:06:28] SPEAKER: I'm like, "Man, I know exactly how that happened."
[1:06:29] SPEAKER: At some point, you've got to get it out the door.
[1:06:32] SPEAKER: Yes.
[1:06:33] SPEAKER: Yeah.
[1:06:34] SPEAKER: If you have questions, please send them in.
[1:06:36] SPEAKER: We'll answer them in the next Q&A at techpod@content.town or the Questions Seeking Answers channel on
[1:06:41] SPEAKER: the Discord.
[1:06:42] SPEAKER: If you're not in the Discord and would like to be in the Discord, you can do so by becoming
[1:06:47] SPEAKER: a fabulous techpod patron.
[1:06:49] SPEAKER: You can?
[1:06:50] SPEAKER: Yeah.
[1:06:51] SPEAKER: Thanks.
[1:06:52] SPEAKER: Brad, did you know this is a listener-supported show?
[1:06:53] SPEAKER: I've heard.
[1:06:54] SPEAKER: I saw a friend of the pod talking about advertising, Jeff Gerstmann talking about advertising on
[1:06:59] SPEAKER: his Blue Sky yesterday.
[1:07:01] SPEAKER: I was like, "Man, I don't want to have to deal with advertising."
[1:07:04] SPEAKER: Look, all it's going to do is annoy people into signing up for the Patreon, so they get
[1:07:09] SPEAKER: the ad-free version.
[1:07:10] SPEAKER: I'd rather just ask them to support the podcast nicely and say, "Hey, we'd rather not have
[1:07:15] SPEAKER: to annoy anyone.
[1:07:16] SPEAKER: We'd rather just have no ads," is where I land.
[1:07:19] SPEAKER: You can support the podcast by going to patreon.com/techpod.
[1:07:24] SPEAKER: Again, it's patreon.com/techpod.
[1:07:28] SPEAKER: Because you have to say everything three times, I'm going to say it again.
[1:07:30] SPEAKER: Wait.
[1:07:31] SPEAKER: I can say it.
[1:07:32] SPEAKER: Oh, yeah.
[1:07:33] SPEAKER: What is it, Brad?
[1:07:34] SPEAKER: Is it patreon.com/techpod?
[1:07:35] SPEAKER: It is patreon.com/techpod.
[1:07:36] SPEAKER: Wait.
[1:07:37] SPEAKER: You said it four times.
[1:07:38] SPEAKER: Does that now cancel out?
[1:07:39] SPEAKER: One of the three?
[1:07:40] SPEAKER: I think more people are going to sign up, because we said the fourth.
[1:07:44] SPEAKER: You can go to the Patreon.
[1:07:46] SPEAKER: You can sign up for five bucks a month to get access to the Patreon-exclusive episode.
[1:07:51] SPEAKER: Last month, we talked about a bunch of stuff.
[1:07:54] SPEAKER: People seemed to really like it.
[1:07:56] SPEAKER: It generated a lot of conversation in the new episode discussion subforum.
[1:08:00] SPEAKER: Oh, and it did exactly what you said it might do, which is that people started posting their
[1:08:04] SPEAKER: own tips.
[1:08:05] SPEAKER: I got a tip out of there yesterday that made me very happy.
[1:08:08] SPEAKER: Yep.
[1:08:09] SPEAKER: Yep.
[1:08:10] SPEAKER: For five bucks, you can join our ranks of executive producer tier patrons who we thank
[1:08:17] SPEAKER: every month, including Nick Johnston, Paddle Creek Games' makers of Fractured Veil -- that's
[1:08:21] SPEAKER: coming out in October, by the way.
[1:08:25] SPEAKER: Andrew Slosky, Jordan Lippett, Bunnyfiend, Just Wedge 3.0, Joel Krauska, Twinkle Twinkie,
[1:08:32] SPEAKER: David Allen, James Kamek, and Pantheon, makers of the HS3 high-speed 3D printer.
[1:08:37] SPEAKER: Thank you all so much.
[1:08:38] SPEAKER: Yes, thank you, one and all.
[1:08:42] SPEAKER: And that'll do it for us this week.
[1:08:43] SPEAKER: We'll be back next week.
[1:08:44] SPEAKER: Yeah.
[1:08:45] SPEAKER: I think next week we might talk about iOS stuff, huh?
[1:08:46] SPEAKER: Because it's time.
[1:08:47] SPEAKER: No, wait a minute.
[1:08:48] SPEAKER: I've got another idea.
[1:08:49] SPEAKER: Ooh.
[1:08:50] SPEAKER: We'll talk about it.
[1:08:51] SPEAKER: Foreshadow?
[1:08:52] SPEAKER: Okay, we'll talk about offline.
[1:08:53] SPEAKER: It's a milestone, let's say.
[1:08:54] SPEAKER: Oh.
[1:08:55] SPEAKER: Oh, my.
[1:08:56] SPEAKER: We'll discuss, and we'll see what we come up with.
[1:08:59] SPEAKER: Yeah.
[1:09:00] SPEAKER: New iOS is imminent.
[1:09:01] SPEAKER: Maybe we should talk about that.
[1:09:02] SPEAKER: Yeah, I'm toying with installing the beta.
[1:09:03] SPEAKER: I don't know if it's a good idea or not.
[1:09:04] SPEAKER: Ugh.
[1:09:05] SPEAKER: Ugh.
[1:09:06] SPEAKER: They're not usually beta anymore by this point.
[1:09:09] SPEAKER: I don't know.
[1:09:10] SPEAKER: For this exploit that just happened.
[1:09:11] SPEAKER: Well, fair.
[1:09:12] SPEAKER: Fair.
[1:09:13] SPEAKER: Okay, we'll see you all next week.
[1:09:14] SPEAKER: Thanks for listening, everybody.
[1:09:15] SPEAKER: Have a good one.
[1:09:16] SPEAKER: Bye.
