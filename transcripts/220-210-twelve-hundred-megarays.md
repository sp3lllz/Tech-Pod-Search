---
episode: 220
title: 210: TWELVE HUNDRED MEGARAYS
date: 2023-11-26
guests: none
duration: 59:23
---

[00:00] SPEAKER: Hey Brad, I've been thinking about building a render cluster.
[00:04] SPEAKER: As one does, two days before Thanksgiving.
[00:06] SPEAKER: Well, so we're in the final push on the Anacrusis, and one of the things you do at the very end
[00:11] SPEAKER: of a game dev cycle is bake a whole buttload of lightmaps.
[00:17] SPEAKER: And lightmaps aren't like a... they're not as intense as they were in, say, the Quake
[00:26] SPEAKER: days when, you know, Carmack bought a SGI workstation that took three days to bake a lightmap on
[00:33] SPEAKER: a single level or anything like that.
[00:35] SPEAKER: I was going to say, this is taking me back to the days of reading plan files, where you're
[00:38] SPEAKER: going to have to get a two CPU deck alpha to do this, and then two CPUs both running
[00:43] SPEAKER: at 400 megahertz.
[00:44] SPEAKER: I'm going to tell you, I'm probably running a little bit faster than two CPUs running
[00:48] SPEAKER: at 400 megahertz these days.
[00:51] SPEAKER: But even with the 13900K and the 4090, it takes a while to bake a lightmap on a decent
[01:00] SPEAKER: sized Anacrusis level.
[01:01] SPEAKER: And I was looking around and I was like, I have my old computer with a 3080 Ti, and then
[01:05] SPEAKER: I have the kiddo's computer with a 3080 Ti.
[01:09] SPEAKER: And Unreal has this thing called Swarm that's just built in that if I run a coordinator
[01:14] SPEAKER: on one of the machines and give it some hard drive space, and then run the Swarm client
[01:20] SPEAKER: and put the Swarm on and Unreal on each of the other computers, then it'll just do the
[01:27] SPEAKER: math.
[01:28] SPEAKER: Yeah.
[01:29] SPEAKER: I thought this was going to have to be some ramshackle thing that was going to take days
[01:31] SPEAKER: of setup.
[01:32] SPEAKER: I did not realize they had built it in that elegantly, that it's just like run an installer
[01:36] SPEAKER: on other machines, and now they're helping you make a game?
[01:38] SPEAKER: So the thing I haven't sussed out yet, and I haven't got to...
[01:41] SPEAKER: There's a lot of docs.
[01:42] SPEAKER: It is going to be a little ramshackle, just to be clear.
[01:45] SPEAKER: But the thing I haven't sussed out yet is if I have to put the projects on all the other
[01:51] SPEAKER: machines because the project's like 500 gigs, so it's pretty big.
[01:54] SPEAKER: That's a lot.
[01:55] SPEAKER: Yeah.
[01:56] SPEAKER: At that point, the cost and time of getting the project on all of the different machines,
[02:01] SPEAKER: including...
[02:02] SPEAKER: I don't think my daughter's SSD is big enough to hold 500 gigs of project and the stuff
[02:05] SPEAKER: that she uses her computer for, honestly.
[02:07] SPEAKER: So there may be no upside.
[02:10] SPEAKER: I'm kind of curious if running this on the 3080 and the 4090 at the same time is going
[02:14] SPEAKER: to give me any appreciable benefit because the 4090 can do like 1200 rays per second
[02:21] SPEAKER: or something.
[02:22] SPEAKER: 1200 mega rays per second.
[02:24] SPEAKER: 1200 mega rays.
[02:26] SPEAKER: It's very much like a...
[02:29] SPEAKER: It's like a Sega ad from the '90s.
[02:32] SPEAKER: We do more mega rays than NES don't or something.
[02:35] SPEAKER: Anyway, the point is, I don't know if there's going to be an upside to running this on last
[02:42] SPEAKER: gen, not high-end hardware when I'm comparing it to what I'm running on on the main PC.
[02:47] SPEAKER: So I might set it up on just two PCs and see what happens, and then if it's faster, I'll
[02:51] SPEAKER: run on the other.
[02:52] SPEAKER: But also by the time I get it done, probably it will be done because there's like 25 levels
[02:58] SPEAKER: and I'm through five of them already.
[03:00] SPEAKER: Getting down to it.
[03:01] SPEAKER: Does it have to run on the GPU?
[03:02] SPEAKER: No, you can do it on the CPU, but it takes like 10 hours per level on the CPU still.
[03:08] SPEAKER: It's substantial.
[03:09] SPEAKER: What card is in your daughter's machine out of curiosity?
[03:11] SPEAKER: She's a 3080, I think.
[03:13] SPEAKER: Oh, wow.
[03:14] SPEAKER: Wow.
[03:15] SPEAKER: Okay.
[03:16] SPEAKER: Look, when good things run downhill in this house, so...
[03:18] SPEAKER: Fair.
[03:19] SPEAKER: Yeah, I get it.
[03:20] SPEAKER: I know how it goes.
[03:21] SPEAKER: I would love to hear about the outcome of your growing network of, is this rig going
[03:27] SPEAKER: to achieve sentience at some point?
[03:28] SPEAKER: I don't know.
[03:29] SPEAKER: God, I hope not.
[03:30] SPEAKER: If I have an hour or two to set it up this weekend, I'll put it together and we'll see.
[03:35] SPEAKER: Even if I don't get it done and use it for the actual game, I might set it up and do
[03:39] SPEAKER: it just to have the experience because it's like literally in like '96 when I was making
[03:45] SPEAKER: Quake Rocket Arena levels, Quake 1 Rocket Arena levels, I was like, I have two computers
[03:49] SPEAKER: here.
[03:50] SPEAKER: I could do this on a cluster and I could never make that work, the Quake light map rendering
[03:54] SPEAKER: cluster thing.
[03:56] SPEAKER: There's also just something so highfalutin about the word cluster.
[04:00] SPEAKER: Are you doing HPC in there?
[04:01] SPEAKER: Is this high performance computing or this is like straight up research?
[04:05] SPEAKER: Look, I just need more GPUs, man.
[04:07] SPEAKER: Just give me some more.
[04:08] SPEAKER: I need a workstation board with like 17 GPUs in it and then I'll let it rip.
[04:14] SPEAKER: What if you have like six PCIe slots and you just put a bunch of cards in there?
[04:18] SPEAKER: Have all these cards.
[04:19] SPEAKER: See, that's the thing.
[04:20] SPEAKER: When you said you were going to make a cluster, I was like, okay, he's going to spend the
[04:24] SPEAKER: company money and order like five more computers and they're all going to be identical, but
[04:27] SPEAKER: the idea that this is just a makeshift cluster, including your daughter's computer is amazing.
[04:31] SPEAKER: Well, I mean, but that's how it works at game studios, right?
[04:35] SPEAKER: Before like everybody leaves their computer on when they leave at the end of the day at
[04:38] SPEAKER: a game studio.
[04:39] SPEAKER: And then you can do a CPU light bake in like four hours instead of 30.
[04:43] SPEAKER: Wow.
[04:44] SPEAKER: You already got all that nice workstation hardware just sitting around.
[04:47] SPEAKER: Or just a bunch of off the shelf commodity computers, because that's the way most game
[04:50] SPEAKER: game developers don't have workstation money usually.
[04:55] SPEAKER: Look, the definition of workstation is a bit flexible these days, let's say.
[04:59] SPEAKER: That's true.
[05:00] SPEAKER: [MUSIC PLAYS]
[05:28] SPEAKER: Welcome to Brad and Will Made a Tech Pod.
[05:31] SPEAKER: I'm Will.
[05:32] SPEAKER: I'm Brad.
[05:33] SPEAKER: Hello.
[05:34] SPEAKER: Hello, Brad.
[05:35] SPEAKER: Hi.
[05:36] SPEAKER: Hi.
[05:37] SPEAKER: Hi.
[05:38] SPEAKER: It's early.
[05:39] SPEAKER: We're recording early for the first time in quite a while, but it's a busy day today.
[05:41] SPEAKER: This might be the earliest we've ever recorded.
[05:43] SPEAKER: We said 7 a.m.
[05:44] SPEAKER: It is now 742.
[05:45] SPEAKER: No, we recorded some FOSPODs with people in Europe at 7 a.m.
[05:48] SPEAKER: Of course.
[05:49] SPEAKER: Or six in a couple of cases, I think.
[05:51] SPEAKER: Have we ever done a six maybe?
[05:53] SPEAKER: Some of those people were like, I would like to record at four o'clock in the afternoon.
[05:57] SPEAKER: And I was like, oh, okay.
[05:59] SPEAKER: That sounds great.
[06:00] SPEAKER: Anyway, we're here.
[06:01] SPEAKER: We're talking about something open source again, I guess.
[06:04] SPEAKER: Yeah.
[06:05] SPEAKER: Adjaisance.
[06:06] SPEAKER: Yeah.
[06:07] SPEAKER: Valve was kind enough.
[06:08] SPEAKER: Well, the Valve last week announced a new Steam Deck.
[06:11] SPEAKER: The Steam Deck OLED.
[06:12] SPEAKER: New-ish.
[06:13] SPEAKER: I would call it a mid-season refresh, I think.
[06:16] SPEAKER: A rev.
[06:17] SPEAKER: Yeah.
[06:18] SPEAKER: It's like the 1.5 version.
[06:19] SPEAKER: It's not quite a two.
[06:21] SPEAKER: Yeah.
[06:22] SPEAKER: Definitely.
[06:23] SPEAKER: But it's like that Switch refresh.
[06:25] SPEAKER: That nice one that you looked at and you're like, man, that's a pretty nice looking Switch.
[06:28] SPEAKER: But we're also getting near the end of the Switch generation.
[06:30] SPEAKER: Maybe I'll...
[06:31] SPEAKER: I don't know if I'm going to get an OLED Switch now, and then my wife was like, hey, I want
[06:33] SPEAKER: a Switch.
[06:34] SPEAKER: Will you get me that new OLED one?
[06:35] SPEAKER: I was like, yes.
[06:36] SPEAKER: I will get you that new OLED one.
[06:37] SPEAKER: Now you don't have a choice.
[06:38] SPEAKER: Yeah.
[06:39] SPEAKER: So...
[06:40] SPEAKER: Yeah.
[06:41] SPEAKER: I actually said that on the next Lander podcast when we talked about this thing, how much
[06:43] SPEAKER: it's like the Switch OLED.
[06:44] SPEAKER: Like it's actually kind of shockingly like it, you know, like slightly bigger OLED screen,
[06:49] SPEAKER: slightly, just barely, barely faster internals, better battery life, a little bit.
[06:53] SPEAKER: But it's, you know, it's like kind of almost all the bullet points are just slightly better.
[06:57] SPEAKER: Well, so on this one, it feels like they wanted to do the OLED version, which makes a lot
[07:02] SPEAKER: of sense because some of the competitors that are coming out in the wake of the launch steam
[07:06] SPEAKER: deck are OLED, and there's real benefits to that.
[07:12] SPEAKER: The rest of it, I think, follows on from, hey, if you're going to redesign the board
[07:15] SPEAKER: to work with OLED, the box to work with OLED, then you can do things like, you know, update
[07:21] SPEAKER: the SOC and change the way the power supply works and kind of stuff like that.
[07:28] SPEAKER: The internal charging, charging, charging ecosystem rather.
[07:33] SPEAKER: So, so yeah, not the 2.0, it's a mid-season refresh with a really nice screen.
[07:37] SPEAKER: The battery life is slightly better because there's more, more space, you know, the package
[07:43] SPEAKER: for an LCD versus the package for an OLED takes up less volume inside the box.
[07:48] SPEAKER: The box is essentially identical.
[07:50] SPEAKER: Like the OLED one has a red button on top and the not OLED button has a not red power
[07:56] SPEAKER: button.
[07:57] SPEAKER: That's how you know.
[07:58] SPEAKER: Yeah.
[07:59] SPEAKER: That's the way you can tell.
[08:00] SPEAKER: The sticks are a little bit different.
[08:01] SPEAKER: They did a couple of other things like the, the first Rev sticks tended to collect skin
[08:05] SPEAKER: cruft around the, like the top is in a solid piece cause it has those touch sensitive sticks.
[08:11] SPEAKER: So like they, they redesigned the top of the sticks so they can, so they theoretically
[08:15] SPEAKER: will collect less skin goo in the groove there.
[08:19] SPEAKER: I don't want human on my electronics.
[08:21] SPEAKER: I don't know about you.
[08:22] SPEAKER: This is a personal device, so it's my human, so I'm okay with it, but I don't even like
[08:26] SPEAKER: that.
[08:27] SPEAKER: But you know, I get the brush out and brush the goo out every once in a while.
[08:31] SPEAKER: So, so is, is the form factor identical enough that you could just put it right in a case
[08:35] SPEAKER: for the original steam deck and it would fit without issue.
[08:37] SPEAKER: Okay.
[08:38] SPEAKER: So it weighs 5% less.
[08:39] SPEAKER: I think that's the only way you could distinguish it from the outside if you didn't look at
[08:43] SPEAKER: the red button.
[08:44] SPEAKER: All right.
[08:45] SPEAKER: Um, the, the form factor is identical, the ergonomics are the same, the touch pads are
[08:50] SPEAKER: like, like I said, some of the mechanics inside are a little bit different, but for the most
[08:53] SPEAKER: part, everything feels exactly the same.
[08:55] SPEAKER: The buttons feel the same.
[08:56] SPEAKER: The D pad feels the same.
[08:57] SPEAKER: The sticks feel the same.
[08:58] SPEAKER: Uh, the touch screen at the screen is a little bit larger cause it is an OLED, so it's 7.4
[09:04] SPEAKER: inches versus seven inches.
[09:05] SPEAKER: It's the same resolution, which is also like the, the switch OLED, I believe.
[09:10] SPEAKER: Yeah.
[09:11] SPEAKER: It's weird because the, like a lot of reviewers are reporting the resolution is 1280 by 720.
[09:17] SPEAKER: The steam site reports the resolution for both, both devices is 1280 by 800.
[09:22] SPEAKER: I don't exactly know what it's hard to tell on the internals, which what is, what is actually
[09:26] SPEAKER: true.
[09:27] SPEAKER: The, the OS I think reports 1280 by 800.
[09:29] SPEAKER: So, okay.
[09:30] SPEAKER: Yeah.
[09:31] SPEAKER: I think that was the same as the original.
[09:32] SPEAKER: Yeah.
[09:33] SPEAKER: Also just like the switch OLED, it's slightly bigger screen, but same resolution.
[09:36] SPEAKER: So the pixel density technically is just slightly lower, but it's probably not noticeable in
[09:40] SPEAKER: practice.
[09:41] SPEAKER: Well, and the, the, because it's an OLED, the blacks are really, really good.
[09:44] SPEAKER: So you get like less dithering on, on like dark scenes and stuff like that.
[09:48] SPEAKER: Like the, for example, the, the launch screens, it has like little, little, uh, like pre-roll,
[09:55] SPEAKER: like, you know, like the little logos that play when you turn on a console, you can download
[09:59] SPEAKER: a whole boatload of those.
[10:00] SPEAKER: There's a couple of them that are on solid black backgrounds.
[10:03] SPEAKER: And so when you turn it on laying in bed at night, it just looks like a steam logo floating
[10:07] SPEAKER: in space in front of you in a dark room, basically.
[10:10] SPEAKER: That's amazing.
[10:11] SPEAKER: That's pretty good.
[10:12] SPEAKER: That's pretty good.
[10:13] SPEAKER: I don't, I don't have a steam deck, but can I just shout out valve for a allowing you
[10:16] SPEAKER: to customize the boot up animation because I've never seen that in any kind of console
[10:19] SPEAKER: like device before.
[10:20] SPEAKER: And that's amazing.
[10:21] SPEAKER: But B even having a boot up animation at all, because I don't know why every other console
[10:27] SPEAKER: has basically except kind of the X-Box has abandoned the lost art of the console boot
[10:32] SPEAKER: up animation, but I love them.
[10:34] SPEAKER: And it's the saddest thing in the world that nobody does them anymore.
[10:36] SPEAKER: Well, I assume it's because like they don't need them anymore.
[10:39] SPEAKER: Right?
[10:40] SPEAKER: I guess.
[10:41] SPEAKER: I don't know.
[10:42] SPEAKER: They do do them, but like with the sleep states, you just don't see them very often.
[10:44] SPEAKER: Like my PlayStation.
[10:45] SPEAKER: Oh, PS five has nothing now or just, well, I mean, it has the sparkly as it fades into
[10:50] SPEAKER: the login screen, but I'm talking like a, like a gala logo and, and animation treatment
[10:56] SPEAKER: with cool music kind of thing.
[10:58] SPEAKER: Like the game cube, the three 60 PlayStation two, like there have been such good examples
[11:03] SPEAKER: of those.
[11:04] SPEAKER: Anyway, bring them back, please.
[11:05] SPEAKER: So valve did these in the most valve way possible by making part of the steam point store.
[11:10] SPEAKER: So your loyalty points can be traded in for different, different launch screens.
[11:15] SPEAKER: Wait, can you not just, can you not just like copy your own file in?
[11:18] SPEAKER: You can also copy your own files, but like the ones that they made are pretty like, there's
[11:23] SPEAKER: like, they're, they're pretty good.
[11:24] SPEAKER: You can, you can go look at them even if you don't have a steam deck, I guess is what I'm
[11:27] SPEAKER: saying.
[11:28] SPEAKER: You can also get replacement keyboard skins for at the point store as well.
[11:33] SPEAKER: Anyway.
[11:34] SPEAKER: Um, so that's it, this is, it's a little bit early for this, like in the, in the life cycle,
[11:39] SPEAKER: except for the, you know, PC life cycles, shorter than console life cycle.
[11:44] SPEAKER: Um, the, the steam deck was announced in July of 2021, I think in a non pandemic world,
[11:50] SPEAKER: they probably would have started selling them then, uh, they shipped units in February of
[11:55] SPEAKER: 2022.
[11:56] SPEAKER: Like they were widely available by that summer.
[11:58] SPEAKER: I got mine in June, um, and a bazillion, like multiple companies have shipped competitors,
[12:04] SPEAKER: like big companies, small companies.
[12:05] SPEAKER: There's a ton of weird stuff out of China that is like small PC that runs steam OS kind
[12:11] SPEAKER: of, and that you can do steam decky stuff on.
[12:15] SPEAKER: Yeah.
[12:16] SPEAKER: Uh, like, uh, so you just put out the ROG Ally, Lenovo just put out the Legion Go, which
[12:20] SPEAKER: I saw one of those in person at PC world and they are gigantic.
[12:23] SPEAKER: Yeah.
[12:24] SPEAKER: Um, I, a Neo is one of those companies in China that has, I think, I believe it's I
[12:30] SPEAKER: a Neo.
[12:31] SPEAKER: If you're on our discord, go to the mister and emulation channel and scroll back a little
[12:34] SPEAKER: bit.
[12:35] SPEAKER: I, a Neo just announced like eight or 10 different new handhelds, all in different form factors.
[12:40] SPEAKER: Like there's one that looks like a game boy.
[12:42] SPEAKER: There's one that's got a slide on it, like the old Nokia or, um, uh, sidekick and stuff
[12:47] SPEAKER: like that.
[12:48] SPEAKER: Like they, they are going ham on just like every kind of handheld you can handhelds are
[12:52] SPEAKER: big business office.
[12:54] SPEAKER: This is what the China manufacturing process can do.
[12:57] SPEAKER: It's it's kind of remarkable, but anyway, um, and then they announced the OLED November,
[13:01] SPEAKER: like November 16th.
[13:02] SPEAKER: So shorter than I like, I knew it hadn't been that long, but when you put these dates out
[13:07] SPEAKER: like this, like steam decks have only been in people's hands for about a year and a half.
[13:12] SPEAKER: And now here we are with a, like I said, I think in a non pandemic world, we would have
[13:17] SPEAKER: had steam decks six months earlier than we did properly.
[13:20] SPEAKER: Um, I think maybe we'll get into this as we talk about different aspects of this thing,
[13:24] SPEAKER: but I wonder if there are supply chain realities that made it more expedient to just go ahead
[13:28] SPEAKER: and do this.
[13:29] SPEAKER: And it's not just purely, they pushed for this, but it was more like, Oh, we should
[13:33] SPEAKER: do this.
[13:34] SPEAKER: Cause the parts are now available and maybe even cheaper.
[13:36] SPEAKER: I think that, um, like look, so gamers next is to a good tear down, which we'll talk about
[13:40] SPEAKER: in a minute, which we can get into some of that stuff.
[13:42] SPEAKER: Uh, but I guess before we go any further, I should just lead with this steam deck.
[13:46] SPEAKER: If you don't know, is a handheld gaming PC that costs like around 300, $500, depending
[13:53] SPEAKER: on which model you get.
[13:54] SPEAKER: Uh, and it has an AMD SOC system on a chip in it running arch Linux, and it uses this,
[14:00] SPEAKER: this, uh, software emulation layer called proton that basically lets you run windows
[14:05] SPEAKER: normalize windows games on Linux at, in a performant way.
[14:09] SPEAKER: Uh, uh, so, so you can play, so you can play not quite all, but a lot of your mostly single
[14:15] SPEAKER: player steam games on Linux relatively easily.
[14:20] SPEAKER: And then I also played like Diablo four on, before it was on steam, I was able to like
[14:24] SPEAKER: load battle net on the Linux box and, and play Diablo four on my steam deck as well
[14:30] SPEAKER: this summer.
[14:31] SPEAKER: So like, God, it's also weird that Diablo four is on steam, but anyway, I mean, that's
[14:37] SPEAKER: a whole other thing.
[14:38] SPEAKER: Like the fact that the fact that like every call of duty that wasn't on steam before is
[14:43] SPEAKER: also available for the steam awards this year because it was newly released on steam this
[14:48] SPEAKER: year.
[14:49] SPEAKER: Yeah.
[14:50] SPEAKER: Yeah.
[14:51] SPEAKER: Anyway.
[14:52] SPEAKER: Um, so, okay, let me, let me add to that real quick.
[14:53] SPEAKER: You can also just run windows on your steep deck.
[14:55] SPEAKER: You can, when I first got it, I probably would have said, Hey, you should maybe think about
[15:00] SPEAKER: this.
[15:01] SPEAKER: If you're serious about playing like games that are, that have, for example, DRM or anti
[15:06] SPEAKER: cheat that doesn't work on Linux, right?
[15:08] SPEAKER: Cause like easy and I cheat a lot of the anti cheat stuff doesn't just like they, because
[15:13] SPEAKER: it's kernel level.
[15:14] SPEAKER: It's not going to work with proton ever.
[15:15] SPEAKER: And the developers have to actively support it by writing Linux, uh, Linux run times,
[15:19] SPEAKER: which weirdly Tim Epic isn't going to write a easy anti cheat binaries for Linux.
[15:26] SPEAKER: So the Fortnite can run on this, on the valve steam deck.
[15:29] SPEAKER: I don't understand why anyway, uh, the, uh, it's the hardware changes.
[15:35] SPEAKER: Like I said, physically the shell feels the same.
[15:36] SPEAKER: It's 20, it's literally 29 grams lighter.
[15:39] SPEAKER: That's less.
[15:40] SPEAKER: That's about the amount of coffee that I put in my grinder every morning.
[15:43] SPEAKER: I can't feel 29 grams in my hands.
[15:45] SPEAKER: Really.
[15:46] SPEAKER: I think mice and mice are my context for this recently.
[15:50] SPEAKER: I think like about 30 grams is like a decent reduction in mouse weights because people
[15:55] SPEAKER: care about mouse weights a lot these days, but, but not a huge one.
[15:59] SPEAKER: My mouse weighs 58 grams.
[16:01] SPEAKER: So it's two of these.
[16:02] SPEAKER: That's too light.
[16:03] SPEAKER: That thing's going to blow away in the wind.
[16:05] SPEAKER: Yeah.
[16:06] SPEAKER: Yeah.
[16:07] SPEAKER: It turns out it's been on my desk for awhile.
[16:08] SPEAKER: Anyway.
[16:09] SPEAKER: Um, the screen 7.4 inches versus seven inches.
[16:11] SPEAKER: It's the same size cut out in the case.
[16:13] SPEAKER: I bought a new screen protector for this one and just jammed it on there as the same exact
[16:17] SPEAKER: one is for the, for the steam, all of the non OLED steam deck.
[16:21] SPEAKER: Uh, it, it has the way they described the brightness of the OLED screen is that it's
[16:26] SPEAKER: 600 nits, but it can spike up regionally to a hundred and different places for bright
[16:30] SPEAKER: areas.
[16:31] SPEAKER: I started to a thousand and bright areas.
[16:33] SPEAKER: Oh, thousands.
[16:34] SPEAKER: It's not that's most slouch.
[16:37] SPEAKER: I have never turned it up to full brightness once and then immediately turned it down.
[16:41] SPEAKER: Yeah, like a thousand on a handheld, a battery operated handheld is quite good.
[16:45] SPEAKER: I think my TV, which is pretty bright as TVs go tops out at like 1500, I think.
[16:50] SPEAKER: Yeah.
[16:51] SPEAKER: It's like a thousand to 1500 is the, is the range for TVs.
[16:55] SPEAKER: OLEDs I think are a little bit dimmer than LCDs usually.
[16:58] SPEAKER: Yeah.
[16:59] SPEAKER: Um, uh, it has a much wider gamut than the original OLED at the original LCD steam deck.
[17:03] SPEAKER: It's 102% of the DCI P3 gamut versus 48.5% on the old screen.
[17:10] SPEAKER: Actually you can beat a hundred percent of DCI P3.
[17:13] SPEAKER: Apparently.
[17:14] SPEAKER: Yes.
[17:15] SPEAKER: Uh, and it supports HDR, but only at least for right now, only in the steam, like 10
[17:20] SPEAKER: foot UI, not on the steam desktop.
[17:22] SPEAKER: Cause like, because this is a Linux machine, you can actually shell out to the arch desktop
[17:27] SPEAKER: and do like Linux stuff.
[17:29] SPEAKER: If you want to install emulators or whatever, uh, the HDR stuff doesn't work there.
[17:35] SPEAKER: It's worth mentioning.
[17:36] SPEAKER: I think that this is the first HDR implementation for Linux that they did for this device.
[17:41] SPEAKER: Yeah.
[17:42] SPEAKER: As frequently as a common daily Linux user, I would believe that that had not been approached
[17:46] SPEAKER: before now.
[17:47] SPEAKER: Well, well, but I mean, it's important for games because a games are kind of the one,
[17:52] SPEAKER: one of two real HDR applications that are fairly mainstream right now.
[17:56] SPEAKER: The other one being movies, uh, the, the, that means that the other OLED steam deck
[18:03] SPEAKER: competitors don't necessarily support HDR in your games in the same way that this, that
[18:09] SPEAKER: this device does.
[18:10] SPEAKER: Yeah.
[18:11] SPEAKER: Yeah.
[18:12] SPEAKER: That's actually one of the cool things about the steam deck and valves contributions to
[18:16] SPEAKER: Linux, which you will hear more about in the forthcoming FOS pod.
[18:18] SPEAKER: I swear it's still coming.
[18:19] SPEAKER: Uh, but, but they, you know, they, they are driving a lot of development of various Linux
[18:22] SPEAKER: features and subsystems forward a lot faster than they would be otherwise because they
[18:26] SPEAKER: have the weight of this device and its success behind them.
[18:30] SPEAKER: Exactly.
[18:31] SPEAKER: So like there's a conversation often about the res, well, okay, first off the OLED blacks
[18:37] SPEAKER: are like, I have a phone that's an OLED screen, I guess, which is the main, my main interaction
[18:43] SPEAKER: with OLED screens.
[18:44] SPEAKER: I guess I've had VR headsets that had OLED screens.
[18:46] SPEAKER: I think the blacks are crazy good.
[18:50] SPEAKER: Like it is so nice when you look at this thing, especially in a dark room, it's, it's, it's
[18:55] SPEAKER: like looking at, I don't know, it's hard to, it's hard to describe how good it is to look
[19:00] SPEAKER: at into the void.
[19:02] SPEAKER: Yeah.
[19:03] SPEAKER: There's, there's, there's no, I, you forget how much your brain filters out the dithering
[19:09] SPEAKER: that happens on most LCD screens in the dark grays to black areas.
[19:13] SPEAKER: And that just doesn't exist on this thing at all.
[19:16] SPEAKER: Yeah.
[19:17] SPEAKER: Yeah.
[19:18] SPEAKER: And there are battery life benefits, right.
[19:19] SPEAKER: And a mobile device to having parts of the screen that can just turn off when not needed.
[19:22] SPEAKER: Yeah.
[19:23] SPEAKER: It's like the discord trick to make your, your discord go to OLED friendly mode on the
[19:28] SPEAKER: phone where like you just, the black pixels just don't take any energy to render.
[19:35] SPEAKER: It doesn't support the, the display on the device doesn't support a variable refresh
[19:40] SPEAKER: rates.
[19:41] SPEAKER: I does support multiple refresh rates off of the 90 refresh rates.
[19:45] SPEAKER: People are saying you can go down to 20 Hertz with some hacks.
[19:47] SPEAKER: I think out of the box, it does 30 and 40 and 60 and 90 the, if you plug it into the
[19:55] SPEAKER: dock and plug it into a TV that supports variable refresh rate, it will support variable refresh
[20:01] SPEAKER: rate in that mode.
[20:02] SPEAKER: So you can do an external variable refresh rate display, but not the internal screen.
[20:06] SPEAKER: Okay.
[20:07] SPEAKER: Before we move on from the screen, I'm going to pepper one of my supply chain questions
[20:10] SPEAKER: in here about OLEDs.
[20:11] SPEAKER: Do you think, are we getting to the point where supply chain realities are such that
[20:16] SPEAKER: it actually is more cost effective or like the economies of scale are now there where
[20:20] SPEAKER: it makes more sense to go OLED than LCD.
[20:22] SPEAKER: I don't know if we're quite at that tipping point yet, but another thing informing this
[20:26] SPEAKER: question is like leaks are coming out about the next iPhone se which has Apple's low end
[20:32] SPEAKER: budget iPhone.
[20:33] SPEAKER: Yeah.
[20:34] SPEAKER: And the rumor is they're going to an OLED screen on that thing as well.
[20:37] SPEAKER: And that made me wonder like, okay, is it actually just more cost effective to build
[20:42] SPEAKER: with OLED now or are we getting there than LCDs?
[20:45] SPEAKER: I think, I mean, I think the benefits are the lack of the smaller volume inside the
[20:50] SPEAKER: device.
[20:51] SPEAKER: So if you're talking about something that's small, like a phone that lets them increase
[20:55] SPEAKER: the power of the CP, especially on the se, which is a relatively small volume compared
[20:59] SPEAKER: to modern phones, the, the, that means that they can bump up the CPU APU or SOC in that
[21:06] SPEAKER: device higher to have a higher performance and higher TDP and still have decent battery
[21:12] SPEAKER: life would be my guess because like the battery is substantially larger, hold on.
[21:17] SPEAKER: It's a 50 watt hour versus a 40 watt hour battery in the new one, in the new Steam Deck
[21:22] SPEAKER: OLED, which is a, you know, a 25% increase in volume for the battery because it's not
[21:27] SPEAKER: like the density has gotten better on the energy there.
[21:30] SPEAKER: So like that means that battery is a lot bigger than it was previously.
[21:34] SPEAKER: Okay.
[21:35] SPEAKER: Yeah.
[21:36] SPEAKER: Maybe it's the, maybe it's the other benefits of OLED and more than more so than cost because
[21:39] SPEAKER: I mean, I'm sure OLEDs are getting cheaper to manufacture with, but so I'm sure LCDs
[21:43] SPEAKER: also continue to drop.
[21:45] SPEAKER: So maybe it's not a cost thing.
[21:46] SPEAKER: It's more just the other benefits are yeah, I mean, OLEDs are definitely like, I think
[21:51] SPEAKER: the Delta between the two is lower than it's ever been now.
[21:53] SPEAKER: And that's going to continue to be true every minute of every day from here forward.
[21:57] SPEAKER: Right.
[21:58] SPEAKER: But I, I think, I think I don't think that there are easy answers for manufacturing on
[22:04] SPEAKER: this kind of stuff.
[22:05] SPEAKER: Like it is cause like they get better battery life because of the OLED blacks.
[22:09] SPEAKER: They also get better battery life because of the increased battery size, but that means
[22:14] SPEAKER: that they are then going to have to spend more on the battery.
[22:16] SPEAKER: So it's going to like, there's, there's a ton of downstream costs and they had to completely
[22:19] SPEAKER: redesign the inside of the box basically.
[22:22] SPEAKER: Right.
[22:23] SPEAKER: Let's do we want to talk about the resolution?
[22:27] SPEAKER: I feel like the resolution comes up a lot and I, I, I kind of felt like, Oh, it's a
[22:32] SPEAKER: bummer that this isn't a 10 ADP thing until I started using it.
[22:36] SPEAKER: And then when I realized where the limits of power for the SOC are like 1280 by 800,
[22:42] SPEAKER: 1280 by seven 20, it makes a lot of sense.
[22:44] SPEAKER: I think.
[22:45] SPEAKER: Yeah.
[22:46] SPEAKER: For games.
[22:47] SPEAKER: I mean, that's, that's the thing.
[22:48] SPEAKER: Would you really want it to be 10 ADP with the realities of, of, of its performance even
[22:51] SPEAKER: at seven 20 already, I think at the screen size you're dealing with on this thing, especially
[22:57] SPEAKER: running at seven 20 P and running at 12 80, 10 ADP would eat significant battery for very
[23:03] SPEAKER: little benefit.
[23:04] SPEAKER: Yeah.
[23:05] SPEAKER: Especially in a world where you can run FSR on this device and get like upscaling and
[23:09] SPEAKER: all that.
[23:10] SPEAKER: And it doesn't make a ton of sense anyway.
[23:12] SPEAKER: So the screen's real good.
[23:13] SPEAKER: Like it's, it's, it's the screen is fantastic.
[23:15] SPEAKER: If you have a first gen steam deck, it's, I don't think the screen is a reason to like,
[23:20] SPEAKER: it's the screen is good.
[23:21] SPEAKER: It's the best thing about it.
[23:23] SPEAKER: I don't think it's, Hey, I got to get rid of my old steam deck and get a new street
[23:26] SPEAKER: steam deck territory.
[23:27] SPEAKER: I think you hold off and wait for the second rev or maybe the third, depending on how you
[23:31] SPEAKER: use it.
[23:32] SPEAKER: Right.
[23:33] SPEAKER: A gamer's nexus did a really good tear down and highlighted a bunch of stuff that's changed
[23:37] SPEAKER: that valve didn't actually talk about on their press materials.
[23:42] SPEAKER: They are doing a new rev of the APU of the AMD APU.
[23:46] SPEAKER: It's the same basic APU.
[23:48] SPEAKER: It's on a smaller process.
[23:49] SPEAKER: It's on TSMC's N6 process, which means it's going to be more efficient and probably because
[23:56] SPEAKER: of the way thermal throttling works on these kinds of APUs probably means you get a little
[24:01] SPEAKER: bit more performance in the same thermal envelope.
[24:06] SPEAKER: But, but, but like not, you know, suddenly, suddenly your, your game that was running
[24:11] SPEAKER: at 10 frames a second, isn't going to run at 60 frames a second.
[24:14] SPEAKER: It's going to run.
[24:15] SPEAKER: It's 12 frames per second.
[24:16] SPEAKER: Now it's, it's a pretty negligible and that's another place where the, the switch the switch
[24:20] SPEAKER: refresh the OLED and the, and the light also got a slightly die shrunk.
[24:24] SPEAKER: I should've, I should've pulled a new story on this, but I read about this six nanometer
[24:27] SPEAKER: process with TSMC and the context of the recent PlayStation five models.
[24:32] SPEAKER: Apparently, apparently TSMC has some process where seven, even the seven nanometer designs
[24:39] SPEAKER: can be shrunk down to six without much work on the part of the client client is client
[24:45] SPEAKER: is the word, I guess like they don't have to like substantially redesign the ship to,
[24:50] SPEAKER: to do that.
[24:51] SPEAKER: And I believe that's what happened with the, the newer PS fives as well.
[24:53] SPEAKER: So that seems like something maybe we'll see more of.
[24:55] SPEAKER: Yeah.
[24:56] SPEAKER: They, they described the steam deck SOC as semi custom, which to me means that they have
[25:01] SPEAKER: put the like valve has said, Hey, we want a couple of things that aren't standard tacked
[25:06] SPEAKER: onto this.
[25:09] SPEAKER: The one thing that is the big win about the smaller process too, because of the lower
[25:13] SPEAKER: thermals on the, on the CPU portion is that the GPU doesn't clock down as much when it
[25:17] SPEAKER: hits the 15 watt max, max draw.
[25:20] SPEAKER: So like that actually can have some fairly measurable impacts on games that were GPU
[25:27] SPEAKER: limited.
[25:28] SPEAKER: Yeah.
[25:29] SPEAKER: So that means like not substantially higher highs in the frame rate, but maybe, maybe
[25:33] SPEAKER: steady or lows, like maybe, maybe the you're kind of 1% lows are more consistent.
[25:38] SPEAKER: If you're not having it clocked down a bunch.
[25:41] SPEAKER: It's not something that I have been able to consciously notice switching back and forth
[25:45] SPEAKER: between them playing the same game.
[25:47] SPEAKER: If that, if that helps sure.
[25:50] SPEAKER: That's probably good to state, you know, like I'm, I'm sure, in fact, I've seen a fair amount
[25:54] SPEAKER: of hand reading from people who feel like they have not had a steam deck for very long
[25:57] SPEAKER: looking at this thing, going like, Oh, but maybe it's important to say like, Hey, this
[26:01] SPEAKER: thing is better, but it's not some radical leap forward.
[26:05] SPEAKER: Yeah.
[26:06] SPEAKER: In terms of like performance difference between this one and the old one I don't like it.
[26:12] SPEAKER: It reminds me of like a 3DS refresh almost right.
[26:16] SPEAKER: When, when like they added the DSI stuff and you're like, Oh, this is cool.
[26:20] SPEAKER: It works in two games, a similar camera on here that they will never, ever use.
[26:25] SPEAKER: Yeah, exactly.
[26:26] SPEAKER: This is more substantial on a camera of course, but it is, but also it's, it is quite literally
[26:33] SPEAKER: I can switch back and forth between them.
[26:35] SPEAKER: And unless I'm looking at the red button on the top, I won't, or the finger crust in the
[26:40] SPEAKER: sticks.
[26:41] SPEAKER: I won't know the difference between the two by, by like it's other than this, the screen's
[26:48] SPEAKER: pretty noticeable, depending on whether the game he supports, you're playing supports
[26:51] SPEAKER: HDR or not.
[26:52] SPEAKER: Yeah.
[26:53] SPEAKER: They redesigned the board a lot.
[26:55] SPEAKER: Steve gets into this a lot in the gamers nexus review tear down.
[26:58] SPEAKER: If you're interested, you should take a look at it.
[27:00] SPEAKER: They basically disassembled both steam decks and laid out all the parts side by side and
[27:06] SPEAKER: talked about what's changed in them all the way down to like, like the, the board has
[27:12] SPEAKER: the previous boards had four memory chips on them.
[27:14] SPEAKER: These have two there's more memory bandwidth because they're running at 102 gigabytes per
[27:20] SPEAKER: second versus 88 gigabytes per second, which I think is a 16% jump.
[27:26] SPEAKER: The battery's bigger.
[27:27] SPEAKER: The cooler is flipped upside down.
[27:29] SPEAKER: So they, they, his, the thought was that they thought that having the intake facing hot
[27:34] SPEAKER: stuff would pull some air over them and that maybe in practice it didn't actually do much.
[27:38] SPEAKER: So they flipped it around.
[27:39] SPEAKER: So it was easier to assemble or disassemble or whatever, maybe quieter.
[27:44] SPEAKER: I do notice that when the fan spins up, it's a little bit quieter than the old one, but
[27:49] SPEAKER: that could also just be lack of dust and cruft in the, in the blades, making the old one
[27:54] SPEAKER: louder.
[27:55] SPEAKER: Lack of human in there.
[27:56] SPEAKER: I mean, man, we are just, we are constant gross humans are constant gross machines.
[28:04] SPEAKER: I happened to be at PC world the day that they announced this thing and I was talking
[28:06] SPEAKER: to Adam about it and he commented just off hand, I didn't actually ask him to elaborate.
[28:11] SPEAKER: He commented that that extra memory bandwidth would especially matter with an APU.
[28:15] SPEAKER: And I was trying to figure out why is it maybe just cause all the compute is on one ship.
[28:19] SPEAKER: So having CPU and GPU both able to access memory faster is a boon.
[28:24] SPEAKER: Yeah.
[28:25] SPEAKER: It's because the GPU doesn't have discrete memory.
[28:26] SPEAKER: So the bottleneck is, is harder on the APU.
[28:30] SPEAKER: Also, it's worth saying pretty much every unreal game for unreal four game ever is memory
[28:36] SPEAKER: bandwidth bound on, on high end GPUs.
[28:39] SPEAKER: I don't know how it works on the APU.
[28:41] SPEAKER: I haven't actually thought about that a lot, but, but like more memory, like more memory
[28:46] SPEAKER: bandwidth is always good.
[28:48] SPEAKER: Adam is correct.
[28:49] SPEAKER: For sure.
[28:50] SPEAKER: Yes.
[28:51] SPEAKER: The other thing that they did that I actually, I think is this pretty substantial change
[28:54] SPEAKER: that they didn't, I was surprised they didn't talk about it cause it's kind of a, the first,
[28:58] SPEAKER: the first steam deck is bad at charging.
[29:00] SPEAKER: Like if you're, if you're charging it when it's off, it's great.
[29:04] SPEAKER: If you're charging it and playing at the same time, it gets weirdly hot, like not like dangerously
[29:10] SPEAKER: hot, but like, I feel like at this point we know how chargers work and like devices shouldn't
[29:14] SPEAKER: have to spin up fans to charge, but it definitely was, was running hotter when you plugged it
[29:19] SPEAKER: in.
[29:20] SPEAKER: If you're playing for a long time, you need to top off the battery and it charged kind
[29:23] SPEAKER: of slow.
[29:24] SPEAKER: I mean, it's a big battery, but, but with a 45 watt charger, I mean, I guess the math
[29:30] SPEAKER: works out, but it felt like it felt like it always took at least two hours to charge which,
[29:36] SPEAKER: which is, which is kind of a lot the, the, the new board, the charging infrastructure
[29:41] SPEAKER: on it is such that it has to, it has double the ingest components in whatever the bits
[29:48] SPEAKER: are that make the electricity go into the device so that it can charge and run more
[29:52] SPEAKER: effectively.
[29:53] SPEAKER: And it doesn't, it doesn't seem to get as hot when you're doing that, which is nice
[29:56] SPEAKER: even when you're playing a kind of intensive game.
[30:00] SPEAKER: There's a bunch of other stuff that they put in the box that's kind of minor.
[30:03] SPEAKER: There's a longer power cable on the led models, which, which, which is two and a half meters
[30:08] SPEAKER: versus one and a half meters before, which sounds stupid, but the extra meter means you
[30:12] SPEAKER: can sit on a chair and have the power cord running into the, into the device with your
[30:18] SPEAKER: charging while you're playing.
[30:19] SPEAKER: And it's not a hassle.
[30:22] SPEAKER: It's still a 45 watt charger, a wifi jumped from five to 60, which is, it's hard to tell,
[30:30] SPEAKER: but I think it's, it's making downloads a little bit faster.
[30:32] SPEAKER: They also have flipped on the download, the game from your steam install on your desktop
[30:37] SPEAKER: thing across the local network lately, which is hella fast.
[30:42] SPEAKER: That's awesome.
[30:43] SPEAKER: So yeah, that's probably runs at line speed practically.
[30:47] SPEAKER: Yeah.
[30:48] SPEAKER: It's it, I think you're saturating the, the SSD on the, on the steam deck probably would
[30:53] SPEAKER: be my guess for the MMC card, if you're using one of the MMC card slots.
[30:57] SPEAKER: What wifi do you have in your house right now?
[30:59] SPEAKER: 6E I have two APs, one's a six and one's a 6E.
[31:03] SPEAKER: Oh, okay.
[31:04] SPEAKER: Oh, can you mix them safely like that?
[31:06] SPEAKER: Just hands off to whichever.
[31:09] SPEAKER: Yeah.
[31:10] SPEAKER: Just whichever node you're on gets the fast, the six and 6E it's the throughput isn't that
[31:15] SPEAKER: much better.
[31:16] SPEAKER: It's the, it's the congestion relief stuff.
[31:20] SPEAKER: I just bought the 6E one because it was cheap when I needed a second one.
[31:23] SPEAKER: It was, it was on sale.
[31:26] SPEAKER: Let's see the there's a two part case now.
[31:32] SPEAKER: So like if you, the old case was pretty bulky and was designed to carry it around and be
[31:36] SPEAKER: a droppable and all that, there's one big, one big piece, the new one, you can pull out
[31:40] SPEAKER: the inner liner on and it makes it just like a sleeve to keep it from getting scratched
[31:43] SPEAKER: up.
[31:44] SPEAKER: If you want to chuck it in like a messenger bag or a backpack or something.
[31:46] SPEAKER: That's smart.
[31:47] SPEAKER: Does that case come with every skew?
[31:49] SPEAKER: Comes with every skew.
[31:50] SPEAKER: Wow.
[31:51] SPEAKER: That's nice.
[31:52] SPEAKER: Their packaging is really like, I always feel weird talking about packaging, but as we've
[31:56] SPEAKER: made more environmentally friendly packaging, it's really good.
[31:58] SPEAKER: Their packaging or the actual, like if you have it on the shelf in a store is just that
[32:03] SPEAKER: case with a cardboard sleeve around it and like a, a lock tight thing on the zippers
[32:09] SPEAKER: so you can unzip it.
[32:12] SPEAKER: The shipping box is just slightly larger than that.
[32:16] SPEAKER: Like it's like that hangs in a frame suspended in one box.
[32:19] SPEAKER: So it's hardly any cardboard it's, it's, there's no plastic or stuff in the shipping stuff,
[32:24] SPEAKER: which is, which is well done.
[32:27] SPEAKER: There's a special limited edition version that has transparent shell.
[32:30] SPEAKER: I, my question was, Hey, is there going to be an atomic purple one, which to which I
[32:36] SPEAKER: got smiles and, and it's like polite chuckles.
[32:42] SPEAKER: And it still supports, please don't follow the analog model of a bunch of limited edition
[32:47] SPEAKER: colorway drops that valves not like that.
[32:50] SPEAKER: They're not going to be like that.
[32:52] SPEAKER: I hope not.
[32:53] SPEAKER: But like also I would love to have a orange one, like GameCube orange one.
[32:57] SPEAKER: Sure.
[32:58] SPEAKER: Yeah, you know, I bet, I bet someone can hook you up.
[33:02] SPEAKER: There's a reasonably robust market for aftermarket parts for these things already.
[33:06] SPEAKER: Oh yes.
[33:07] SPEAKER: I believe that.
[33:08] SPEAKER: So, so you can, and, and they do embrace the iFixit lifestyle.
[33:13] SPEAKER: Like there are guides for, you can, you can buy replacement parts, you can upgrade stuff.
[33:18] SPEAKER: You can, you can upgrade the SSD internally.
[33:20] SPEAKER: You can buy replacement sticks, buy replacement screens, buy replacement motherboards, the
[33:25] SPEAKER: whole thing, like it's user serviceable in a way that is shocking for this kind of device.
[33:31] SPEAKER: And it still supports all the stuff that made the old Steam Deck awesome, like Emu deck
[33:34] SPEAKER: and Chiaki, which is the PS, the stream from your PS5 thing, game pass streaming still
[33:40] SPEAKER: works.
[33:41] SPEAKER: Moonlight works.
[33:42] SPEAKER: All of the stuff that you're accustomed to is, is still good there.
[33:45] SPEAKER: Yeah.
[33:46] SPEAKER: And speaking of storage, it seems like they're de-emphasizing the EMMC storage in the, in
[33:51] SPEAKER: the, in the product line.
[33:52] SPEAKER: Yeah, so one of the things I got watching Steve's Gamers Nexus tear down and, and this
[33:57] SPEAKER: move away from the EMMC thing, first off, I, I had, so I had a 256 gig model original
[34:03] SPEAKER: OLED that I, original LCD Steam Deck that I bought, I put a big MMC card in it.
[34:09] SPEAKER: Really couldn't tell a difference between the MMC and the, and the SSD in terms of like
[34:14] SPEAKER: load times.
[34:15] SPEAKER: Interesting.
[34:16] SPEAKER: The install times were way worse on the MMC.
[34:18] SPEAKER: Sure.
[34:19] SPEAKER: But like when you're playing the games, it wasn't, it wasn't a big impact.
[34:23] SPEAKER: The, the, the thing that was rough about the MMCs is that like those cards are just not
[34:30] SPEAKER: super reliable.
[34:31] SPEAKER: Oh, for sure.
[34:32] SPEAKER: So just a big SD card.
[34:34] SPEAKER: Yeah.
[34:35] SPEAKER: It's a big SD card that like you're, it's probably, it's probably fine until it isn't.
[34:39] SPEAKER: Right?
[34:40] SPEAKER: Yes.
[34:41] SPEAKER: You'll talk through the pricing real quick and what they've done to the, I think we might
[34:45] SPEAKER: have skipped over that part.
[34:46] SPEAKER: Yeah, I was going to say that for the end of this frame right here, but no, that's fine.
[34:50] SPEAKER: So the there's three models now that are new.
[34:53] SPEAKER: They're also selling the old 64 gig MMC models for 350 bucks while they last.
[34:58] SPEAKER: But they aren't gonna be making more of those.
[35:01] SPEAKER: It's 450 bucks for the 512 meg, 512 gig OLED, 650 for the one terabyte OLED, 256 gigabytes
[35:10] SPEAKER: for the LCD version, 256, 256 gigabyte LCD version is $400.
[35:16] SPEAKER: So it's like a $50 bump for storage and OLED, which feels like a great, pretty good deal
[35:22] SPEAKER: to me.
[35:23] SPEAKER: For only another $50, once you're already up to 400, it's hard not to get the OLED one.
[35:29] SPEAKER: Yeah.
[35:30] SPEAKER: At the same time, all the other benefits.
[35:32] SPEAKER: At the same time, that 64 gig EMMC old model, if you can get it for 350 bucks is, is I,
[35:40] SPEAKER: you should check this before you buy it.
[35:41] SPEAKER: But my understanding at least at launch was that they still had an SD slot, an NVME slot
[35:46] SPEAKER: in them.
[35:47] SPEAKER: So you can, if you're comfortable cracking it open and taking it apart, you can buy those
[35:50] SPEAKER: SS.
[35:51] SPEAKER: You can buy a two terabyte SSD for like 150 bucks now.
[35:54] SPEAKER: So when you want storage, you can chuck it on somebody on the discord.
[35:57] SPEAKER: It was, it was a, it was a quick sale, $89 for a crucial two terabyte NVME.
[36:02] SPEAKER: It's back up to like 110 right now, but like the SSDs are getting so cheap, a 350 steam
[36:07] SPEAKER: deck and a cheap SSD would be a pretty good deal.
[36:09] SPEAKER: Yeah.
[36:10] SPEAKER: And well, and you can buy them separately so you can buy one now and then buy the other
[36:12] SPEAKER: one later when you want it.
[36:15] SPEAKER: And I will say, like I said, the compromise on the EMC SD card is install time, not play,
[36:22] SPEAKER: not at play.
[36:23] SPEAKER: So it's not bad.
[36:24] SPEAKER: I like, my intention is to put an SSD card, an SD card with a whole bunch of ROMs in when
[36:29] SPEAKER: I install EMU deck on the, on the new one.
[36:32] SPEAKER: Yeah.
[36:33] SPEAKER: 200 for the leap from five 12 to 10, one terabyte OLED is a bit much, are they still doing weird
[36:37] SPEAKER: stuff like, you know, like better reflective coating on the screen for the top tier one
[36:41] SPEAKER: and like exclusive keyboard skin.
[36:44] SPEAKER: It has the anti glare treatment on the high end one.
[36:48] SPEAKER: The limited edition version, which I think maybe is already sold out, I'm not sure was,
[36:54] SPEAKER: was another 50 bucks on top of the 650 bucks.
[36:59] SPEAKER: I think I feel like, like I get why this happens and it's because it's, it's, this is the Apple,
[37:07] SPEAKER: the phone model leaking over where storage bumps are a thing that people understand.
[37:12] SPEAKER: So you charge more for the expensive one, having a lot of space is really convenient
[37:17] SPEAKER: on it.
[37:18] SPEAKER: Like I, I, it's still unclear to me how long these devices are going to last for people
[37:23] SPEAKER: like for, for me, and we can talk about this in a minute.
[37:27] SPEAKER: If you're playing games on the device, like we're starting to already see the limits as
[37:32] SPEAKER: we start to see the, the first, I want to say current gen only console games come out.
[37:38] SPEAKER: So like, I think when we see, for example, Spider-Man 2 land on this thing next year,
[37:44] SPEAKER: Miles Morales runs great on it.
[37:45] SPEAKER: Miles Morales and Spider-Man, which were PS4, PS5 cross, cross gen titles look fantastic,
[37:52] SPEAKER: play great, really, really wonderful.
[37:54] SPEAKER: My guess is that the PS5 exclusive games and the Xbox series exclusive games are going
[38:00] SPEAKER: to have started having problems on these.
[38:02] SPEAKER: Yeah.
[38:03] SPEAKER: I would believe that.
[38:04] SPEAKER: I was, I was lucky enough to be on the full nerd yesterday with Alex Petalia from Digital
[38:09] SPEAKER: Foundry.
[38:10] SPEAKER: Oh yeah.
[38:11] SPEAKER: And I posed the thought experiment to him of when do you think a game ships with only
[38:16] SPEAKER: ray tracing support?
[38:17] SPEAKER: I think I was going for the kind of maximal question of like, when do you see a game with
[38:21] SPEAKER: no no razzle request lighting at all?
[38:25] SPEAKER: But he, and I was like, oh, is that 10 years, 15 years, but he actually, he made it a more
[38:29] SPEAKER: realistic answer of a game that requires ray tracing.
[38:32] SPEAKER: Not necessarily that is pure ray tracing, but he actually said like one to two years,
[38:36] SPEAKER: he sees games coming out that are going to require hardware level ray tracing.
[38:41] SPEAKER: And Spider-Man 2 came up because on the PS5, there is no, even the, even the most reduced
[38:48] SPEAKER: performance mode on the PS5 version of Spider-Man 2 still has like ray traced reflections and
[38:54] SPEAKER: requires some level of ray tracing hardware.
[38:56] SPEAKER: So like, yeah, this does seem like the kind of thing.
[38:59] SPEAKER: I don't, I don't know what feature set that APU supports, like what level of our DNA features
[39:03] SPEAKER: they have in there or whatever, but like, it does seem like we're going to get to the
[39:06] SPEAKER: point where we're going to be back to the old, like the pixel shader days again, right?
[39:11] SPEAKER: Of like, Hey, if your GPU doesn't have pixel shading support, you're not going to play
[39:15] SPEAKER: Doom 3, right?
[39:16] SPEAKER: Like games are going to start requiring actual features on, on newer GPUs at some point.
[39:22] SPEAKER: I think, I mean, so I've been thinking about minimum, minimum spec requirements for PC
[39:28] SPEAKER: games lately.
[39:29] SPEAKER: And spending a lot of time at Steam looking at the hardware survey results as a result
[39:33] SPEAKER: of that, like, you have to remember the 2080s, a four year old card now, right?
[39:38] SPEAKER: Like we're we're everybody, like in a lot of ways, PC hardware went on pause because
[39:44] SPEAKER: of the Bitcoins, the, the Ethereum stuff and, and the, and the pandemic and the longer console
[39:50] SPEAKER: generation.
[39:51] SPEAKER: Yeah.
[39:52] SPEAKER: And, and a very long console generation that also spanned into the first three years of
[39:57] SPEAKER: the next console generation for a lot of people.
[40:01] SPEAKER: But at the same time, like we're like a four year old mid-level card has ray tracing support
[40:09] SPEAKER: now.
[40:10] SPEAKER: Right.
[40:11] SPEAKER: So I think, I think, I think he's, I think he's actually absolutely right that we're
[40:13] SPEAKER: going to see, like, I would not be surprised if we see cards that require ray tracing games
[40:17] SPEAKER: require ray tracing in the next six months or a year, whenever I, and, and like that
[40:24] SPEAKER: we'll leave this hardware behind with an asterisk.
[40:28] SPEAKER: Yeah.
[40:29] SPEAKER: And the asterisk is the game streaming games from your desktop PC in the other room.
[40:34] SPEAKER: If you have a big desktop PC in the other room is fucking awesome on this thing with
[40:39] SPEAKER: the also asterisk that you have to have decent wifi you're running on an old 802.11n network.
[40:44] SPEAKER: It's not going to be great.
[40:45] SPEAKER: If you're running on a six or 60 or probably even five network, cause my garage APs of
[40:50] SPEAKER: five still, I think it works great at in the living room.
[40:54] SPEAKER: It's really, really good.
[40:57] SPEAKER: It's gone.
[40:58] SPEAKER: It's I played, I played as much as almost all of the star field that I played.
[41:02] SPEAKER: I played with this on watching TV, like sitting in the living room at night, hanging out with
[41:07] SPEAKER: the fam, just kind of doodling at star field.
[41:10] SPEAKER: And the experience was really good on the old steam deck.
[41:13] SPEAKER: Stream from your PC.
[41:14] SPEAKER: You mean stream stream from the PC I played, I laid in bed and played cyberpunk last night
[41:18] SPEAKER: I yeah, like generally speaking, if I want to play a big triple a game on the steam deck
[41:27] SPEAKER: and I'm going to be at home, I don't even bother installing it.
[41:29] SPEAKER: I just hit the stream button and stream it from the desktop PC.
[41:32] SPEAKER: It's wired into the network.
[41:33] SPEAKER: Yeah.
[41:34] SPEAKER: That makes sense.
[41:35] SPEAKER: I mean, I also live in a house that has a high contention for the big TV in the living
[41:40] SPEAKER: room.
[41:41] SPEAKER: So but there is a dock out there.
[41:43] SPEAKER: Like I could, I could drop the steam deck into the dock and connect a dual sense to
[41:46] SPEAKER: it and play that way as well, which I have with the old one, I haven't the new one as
[41:51] SPEAKER: much.
[41:52] SPEAKER: I haven't had time to do that.
[41:53] SPEAKER: I, like I said earlier, I played Diablo four native on it using battle net.
[41:57] SPEAKER: I've played a couple of origin games.
[42:00] SPEAKER: I installed a park right three from the Ubisoft launcher, like all of the other non steam
[42:06] SPEAKER: PC launchers work.
[42:07] SPEAKER: You can install Epic even on it.
[42:10] SPEAKER: The only thing that consistently doesn't work is either stuff that requires a lot of text
[42:15] SPEAKER: input because the onscreen keyboards kind of a pain in the ass and you're just, you're
[42:18] SPEAKER: just not going to want to do that.
[42:20] SPEAKER: Like I would never play Baba is you on this probably because of the text input, right?
[42:25] SPEAKER: I'm sure it works.
[42:28] SPEAKER: Fortnite rocket league, fall guys, pub G anything that uses easy anti-cheat isn't going to work.
[42:36] SPEAKER: Apex legends works because they're anti-cheats compatible.
[42:38] SPEAKER: They made their anti-cheat compatible.
[42:42] SPEAKER: I don't know.
[42:43] SPEAKER: I don't think it's a good idea, but theoretically you can play counter-strike on this thing
[42:45] SPEAKER: that'll work.
[42:46] SPEAKER: Sure.
[42:47] SPEAKER: Steam has a really pretty granular breakdown of what does and doesn't work on each game,
[42:54] SPEAKER: partly through cert testing, but partly also through reports from players about things
[42:57] SPEAKER: they have problems with often, often a game will have the, Hey, this doesn't run too great,
[43:04] SPEAKER: but the only thing that's the problem is you have to open up manually, open the onscreen
[43:08] SPEAKER: keyboard to type in your name when you create a character at the very start.
[43:11] SPEAKER: And then that's the last thing that doesn't work if it has decent controller support.
[43:16] SPEAKER: So generally speaking, it's, it's like, you don't get surprises when you're downloading
[43:23] SPEAKER: something very often with this the, the, on the streaming stuff, I, Oh, last thing I play
[43:32] SPEAKER: play a ton.
[43:33] SPEAKER: It's great.
[43:34] SPEAKER: I play a ton of indie games on it.
[43:35] SPEAKER: It's basically like indie game switch.
[43:38] SPEAKER: For me, I was playing dead cells machine or something.
[43:41] SPEAKER: Yeah.
[43:42] SPEAKER: I play a lot of dead cells.
[43:43] SPEAKER: I played, I did a complete run through of Hades from start to finish earlier this summer.
[43:48] SPEAKER: I did.
[43:49] SPEAKER: I do play a lot of dead cells.
[43:50] SPEAKER: It's funny.
[43:51] SPEAKER: You mentioned that I play I played, I've been playing just on, I played Dave, well, Dave,
[43:55] SPEAKER: the divers on indie game, but it it's sorry.
[43:57] SPEAKER: You're sorry.
[43:58] SPEAKER: No, no, no.
[43:59] SPEAKER: That's yes.
[44:00] SPEAKER: You have, you have taken the correct moral position.
[44:03] SPEAKER: I mean, I don't know anyway.
[44:09] SPEAKER: It's complicated.
[44:10] SPEAKER: Well, Hey, I mean, you're as, as an independent game developer, you have a, you have a valid
[44:15] SPEAKER: perspective on this.
[44:16] SPEAKER: I'm not ever going to fault any independent developer that is, has a game in development
[44:22] SPEAKER: and somebody is like, Hey, we would like to give you a lot of money and buy your studio.
[44:25] SPEAKER: I, I never going to fault.
[44:27] SPEAKER: If anybody wants to come by our studio, give me a call, please.
[44:30] SPEAKER: Sure.
[44:31] SPEAKER: It's no longer be independent, independent, but if we were independent while the game
[44:36] SPEAKER: was being made, I might still call that an indie game.
[44:39] SPEAKER: Anyways.
[44:40] SPEAKER: Look, the hardest part of the two hardest parts of game development are making the game
[44:46] SPEAKER: and then also the money stuff, right?
[44:50] SPEAKER: So yeah, like, like that kind of game runs fabulously on it.
[44:53] SPEAKER: The battery life is really, really long when you get into stuff like miles Morales or starfield
[44:58] SPEAKER: or cyberpunk running natively on the box.
[45:00] SPEAKER: The battery life is in, is a couple of three hours, two, three hours, depending on what
[45:04] SPEAKER: settings you use.
[45:06] SPEAKER: And like, if you get into the steam deck subreddit, you can get into like, they're, they're like
[45:11] SPEAKER: mileage hackers telling you exactly what you can install and what settings you can flip
[45:16] SPEAKER: to make your game go from three hours to two hours to three and a half hours.
[45:22] SPEAKER: But it's still, there's a limited amount of gas in the tank.
[45:26] SPEAKER: The streaming battery life is insane.
[45:28] SPEAKER: Like I, you can stream for six or eight hours.
[45:32] SPEAKER: Like when I was playing starfield, I didn't plug in at all until I was done playing.
[45:35] SPEAKER: And then it would charge back up and I would, I would be fine.
[45:40] SPEAKER: It, that streaming stuff used to be kind of fiddly, right?
[45:43] SPEAKER: Like for a while there, the summer, there was a bug where the audio would drop out after
[45:47] SPEAKER: like 10 minutes and then you wouldn't be able to get it back and you'd have to restart the
[45:50] SPEAKER: whole thing on both computers and they get involved getting up and walking into the office
[45:54] SPEAKER: and fixing, and it just sucked.
[45:58] SPEAKER: Fortnite and sunshine, which are the open source implementations of the Nvidia game
[46:01] SPEAKER: stream protocol, solved that completely.
[46:05] SPEAKER: They're a little bit more fiddly, but not too bad there.
[46:07] SPEAKER: It's also a much easier way to get non steam games working streaming.
[46:13] SPEAKER: So if you want to play Fortnite on your steam deck, you can stream it from Epic on your
[46:16] SPEAKER: PC to the steam deck pretty easily.
[46:22] SPEAKER: The what I will say is when I tried to stream cyberpunk earlier this year, it was a pain
[46:28] SPEAKER: in the ass and it ended up with me walking.
[46:30] SPEAKER: Like I say, it's fiddly.
[46:32] SPEAKER: What I mean is you often would have to get up and walk into the office, do something
[46:35] SPEAKER: on the real computer, and then suddenly it would work.
[46:38] SPEAKER: You'd have to switch the game from full screen to borderless or change the resolution manually
[46:43] SPEAKER: or whatever.
[46:44] SPEAKER: Now it just sets the settings right.
[46:45] SPEAKER: And it starts and it's like I clicked the place cyberpunk game button on the steam deck
[46:52] SPEAKER: stream it and it just worked first try out of the box.
[46:55] SPEAKER: It handled the launcher stuff well.
[46:58] SPEAKER: It switched between the virtual mouse mode and the controller modes when it needed to.
[47:01] SPEAKER: Like I could use the touch screen to do input on the launcher.
[47:05] SPEAKER: All of the weird stuff that used to be kind of a pain in the ass just work.
[47:09] SPEAKER: So props to Valve for the work on that because it is much better.
[47:13] SPEAKER: Didn't drop the sound after 30 minutes, all of that.
[47:16] SPEAKER: I did have to turn HDR on on my monitor to get HDR streaming working.
[47:21] SPEAKER: I didn't think HDR streaming would ever work.
[47:23] SPEAKER: So I was kind of impressed by that.
[47:25] SPEAKER: That's impressive.
[47:26] SPEAKER: Over the valve, the steam streaming?
[47:28] SPEAKER: Over the valve stream streaming.
[47:29] SPEAKER: Not moonlight.
[47:30] SPEAKER: Not moonlight.
[47:31] SPEAKER: Wow.
[47:32] SPEAKER: Yeah, that's cool.
[47:33] SPEAKER: Yeah.
[47:34] SPEAKER: And again, that was like I changed the settings in cyberpunk to turn HDR on once I turned
[47:38] SPEAKER: on the HDR monitor.
[47:39] SPEAKER: I assume that if you don't have an HDR monitor hooked up to your PC, you can't stream HDR
[47:43] SPEAKER: to the steam deck.
[47:44] SPEAKER: Which cyberpunk HDR did you use?
[47:46] SPEAKER: Because it has two and I'm not sure which one to use.
[47:48] SPEAKER: I've never heard of either one of them.
[47:51] SPEAKER: I think they are HDR 10 PQ and or I think it's PQ and the other one is SC RGB.
[47:58] SPEAKER: I don't know what those HDRs are.
[48:00] SPEAKER: My monitor only supported one of them.
[48:02] SPEAKER: So I chose the one that is supported.
[48:04] SPEAKER: Okay.
[48:05] SPEAKER: I guess my TV must support too, but they look the same to me.
[48:07] SPEAKER: Oh yeah.
[48:08] SPEAKER: And just to test, I did, I did, you know, you can disconnect a steam deck and then reconnect
[48:12] SPEAKER: to another steam to another streaming endpoint.
[48:16] SPEAKER: And I connected the HDR cyberpunk to the old steam deck and boy, was that a mess.
[48:21] SPEAKER: So it was actually streaming across the HDR, which was kind of nice.
[48:28] SPEAKER: And apparently the last thing that I saw this morning was doing like last notes is that
[48:32] SPEAKER: now you can, it supports external storage.
[48:34] SPEAKER: So if you have like a USB SSD plugged into your steam doc, your steam deck doc, then
[48:41] SPEAKER: you can have a whole host of games to just like when you plug it in, did they just show
[48:44] SPEAKER: up in your library?
[48:45] SPEAKER: Yeah.
[48:46] SPEAKER: That's cool.
[48:47] SPEAKER: Yeah.
[48:48] SPEAKER: So that's the steam deck.
[48:49] SPEAKER: I think it's pretty good.
[48:50] SPEAKER: Yeah.
[48:51] SPEAKER: If I was buying one today, I would buy one of the OLED ones.
[48:53] SPEAKER: Yeah.
[48:54] SPEAKER: For 50 bucks.
[48:55] SPEAKER: Yeah.
[48:56] SPEAKER: Like we said, for, for, for an extra 50 bucks, it seems like a no brainer for all the, all
[48:59] SPEAKER: the marginal, but significant improvements.
[49:01] SPEAKER: Yeah.
[49:02] SPEAKER: And if they sold OLED, if they sold atomic purple or what was the Nintendo game cube
[49:06] SPEAKER: orange color spice orange, I believe was the name spice orange.
[49:11] SPEAKER: I would buy a spice orange shell for this thing.
[49:13] SPEAKER: Like, like a, you couldn't, they couldn't take my money fast enough.
[49:17] SPEAKER: Pumpkin spice game cube.
[49:19] SPEAKER: Fuck that.
[49:20] SPEAKER: I want spice orange.
[49:21] SPEAKER: That's that's spice orange is like, is like the spice melange Brad and the sleeper must
[49:25] SPEAKER: awaken.
[49:26] SPEAKER: Yeah.
[49:27] SPEAKER: So that's, that's it.
[49:29] SPEAKER: I think it's good.
[49:30] SPEAKER: I, I find myself using the steam deck.
[49:33] SPEAKER: It's not every day, but most days I pick it up and use it for something in a house where
[49:38] SPEAKER: you have a use case for a handheld.
[49:40] SPEAKER: It seems like a pretty, if not the handheld to get the one thing that I'm, I didn't get
[49:45] SPEAKER: a chance to do, because we haven't, it hasn't been sunny here is I was hoping that I could
[49:49] SPEAKER: go out and like ride in the car and see if I could use it in the car.
[49:53] SPEAKER: Cause the old one just, just fundamentally didn't ever get bright enough to use in like
[49:57] SPEAKER: a bright car in the summertime.
[50:01] SPEAKER: But yeah, that's, that that's next, I guess, TBD.
[50:05] SPEAKER: I wrote down the word steam deck two here.
[50:07] SPEAKER: We covered this on the next Lander podcast a little bit.
[50:10] SPEAKER: Was it the verge?
[50:12] SPEAKER: Somebody talked to Pierre Lou graffiti valve and asked just like, Hey, what about an actual
[50:18] SPEAKER: new steam deck with new guts and everything that gave a very, I would say an answer that
[50:24] SPEAKER: was both very direct and very noncommittal in that they said like, Hey, we're always
[50:28] SPEAKER: looking at the state of APUs and batteries and like all the things that make up a steam
[50:32] SPEAKER: deck, but like we don't have any explicit plans yet, but, but specifically what they
[50:37] SPEAKER: said was like, we really value consistency and performance target and battery life.
[50:41] SPEAKER: And we're not going to like rush into a second steam deck until those, until those, you know,
[50:47] SPEAKER: those, those vectors converge in a place that we're happy with on faster hardware.
[50:51] SPEAKER: So I think they didn't like say two years away, but I think there was some kind of language
[50:56] SPEAKER: that was sort of like at least, at least two or three years before there's hardware that
[51:00] SPEAKER: is up to snuff.
[51:01] SPEAKER: I think Lawrence Yang has been quoted, this is the worst way to attribute something, but
[51:07] SPEAKER: I have seen at Lawrence Yang, a quote attributed as saying that you shouldn't expect anything
[51:11] SPEAKER: before 2025, which, which like, if we're thinking about what the next gate is on what games
[51:18] SPEAKER: you'll be able to play on these things, it is, Hey, they need an APU that can do whatever
[51:23] SPEAKER: min spec ray tracing will be going forward.
[51:26] SPEAKER: And, and that's, that seems like it's a ways off.
[51:29] SPEAKER: Yeah.
[51:30] SPEAKER: It seems like a kind of a quiet year next year on some fronts, like no new steam deck.
[51:34] SPEAKER: Like the rumors are that there will not be a new Nvidia generation next year.
[51:37] SPEAKER: That's going to be 25 as well.
[51:39] SPEAKER: I mean, they're usually like Nvidia is if their stuff is selling well, they'll do an
[51:44] SPEAKER: 18 month cycle without hesitation.
[51:46] SPEAKER: Right.
[51:47] SPEAKER: And that's just a little bit of an extension for that.
[51:49] SPEAKER: Yes.
[51:50] SPEAKER: I think, I mean, I, I don't like the, honestly, the only thing I don't like about this model
[51:58] SPEAKER: is that the ergonomics aren't always, it is not super comfortable ergonomically.
[52:04] SPEAKER: It is, it is if you're sitting and playing in your lap, but then you're looking down
[52:07] SPEAKER: on your head.
[52:08] SPEAKER: If I'm propped up in bed, it often puts my wrist in a situation that I don't like.
[52:12] SPEAKER: Yeah.
[52:13] SPEAKER: I think even the switch is that way for me and this thing is way bigger and heavier.
[52:16] SPEAKER: So like there needs to be like people, people should make some like handheld pillows.
[52:20] SPEAKER: Well, so the, the, I have switched grips that I bought at target for like 15 bucks that
[52:25] SPEAKER: clip onto the switch that make it work in bed or in a recline in a supine position on
[52:30] SPEAKER: the sofa or whatever.
[52:32] SPEAKER: And also the switch has the benefit of you being able to crack those side, side joy cons
[52:37] SPEAKER: off and hold them wherever is comfortable, which this doesn't exactly have.
[52:40] SPEAKER: I mean, you could plug in a controller, but that seems dopey.
[52:43] SPEAKER: Yeah.
[52:44] SPEAKER: But yeah, I would like more like ironically, I would like more low end on the grippy side
[52:50] SPEAKER: that most of the place to grip is on the high end, but that's where you use your, like that's,
[52:55] SPEAKER: you're using those fingers for other things.
[52:57] SPEAKER: So you end up in a weird, weird position.
[52:59] SPEAKER: Yeah.
[53:00] SPEAKER: I think it's, I think it's pretty good.
[53:02] SPEAKER: The touch, the touch pads.
[53:04] SPEAKER: It's funny, the stuff that I thought was dopey when they announced it, like the touch pads
[53:07] SPEAKER: and all that ends up being incredibly useful, especially in like desktop mode, because it
[53:12] SPEAKER: gives you a really nice track pad surface.
[53:15] SPEAKER: So you don't have to try to hit touch targets on unlike the Linux desktop, which is, which
[53:19] SPEAKER: is hard.
[53:20] SPEAKER: Yeah.
[53:21] SPEAKER: It's a, it's a remarkable device.
[53:23] SPEAKER: My, my secret hope and norm as I was, as I was, as I've been using this for the last
[53:28] SPEAKER: year and change, this seems like it's a path toward the guts of a VR headset.
[53:36] SPEAKER: That's stand, that's standalone slash streaming, right from a, from a desktop PC.
[53:42] SPEAKER: And I would like that just cause I'd like to see somebody that's not Facebook making
[53:46] SPEAKER: a dedicated, dedicated standalone VR headset, like an index two or something.
[53:56] SPEAKER: I would like to see something that you don't necessarily, that you can play untethered
[53:59] SPEAKER: and tethered.
[54:00] SPEAKER: Yes.
[54:01] SPEAKER: Yes.
[54:02] SPEAKER: Like I think, I think it's pretty clear that the future of VR is untethered.
[54:05] SPEAKER: Yes.
[54:06] SPEAKER: And I think if you don't, like I look at an APU and a decent battery life and all that
[54:11] SPEAKER: stuff, and I'm like, this is, yeah, you can hang this on a belt or put it on the back
[54:15] SPEAKER: of your head.
[54:16] SPEAKER: Now we have not seen X86 in a VR headset.
[54:21] SPEAKER: Those are all arm based and there you have much, much more stringent performance requirements
[54:26] SPEAKER: than you do on a handheld.
[54:27] SPEAKER: So I don't know.
[54:28] SPEAKER: Think about how nice it would be to play Alex on a, on a standalone headset.
[54:32] SPEAKER: Oh, I know.
[54:33] SPEAKER: I get it.
[54:34] SPEAKER: That'd be cool.
[54:35] SPEAKER: I, there are crazy people just for the record that plug docs into steam decks and then plug
[54:40] SPEAKER: indexes or other VR headsets into the, into the steam deck and then backpack the steam
[54:45] SPEAKER: deck.
[54:46] SPEAKER: So more power is not impossible.
[54:48] SPEAKER: Yeah.
[54:49] SPEAKER: So there we go.
[54:51] SPEAKER: Yeah.
[54:52] SPEAKER: Sounds pretty good.
[54:53] SPEAKER: That is the steam deck.
[54:54] SPEAKER: I would say it's pretty good.
[54:55] SPEAKER: I I'm going to reiterate, if you already have a steam deck and you buy this, you're going
[55:00] SPEAKER: to probably be disappointed.
[55:02] SPEAKER: If you do not have a steam deck, you should absolutely, and you're going to buy one by
[55:05] SPEAKER: this one.
[55:06] SPEAKER: This is the one to buy for sure.
[55:08] SPEAKER: Yeah.
[55:09] SPEAKER: And, and that'll do it, I guess for us this week.
[55:12] SPEAKER: Yeah.
[55:13] SPEAKER: Cool.
[55:14] SPEAKER: Brad, we've reached the part of the show where we thank our patrons.
[55:17] SPEAKER: Thank you.
[55:18] SPEAKER: Patrons.
[55:19] SPEAKER: This is the last episode of the month.
[55:20] SPEAKER: Is it?
[55:21] SPEAKER: It is in fact, this one, we didn't even say it.
[55:22] SPEAKER: This would have been an emails episode, but then this hot device landed, I guess we'll
[55:26] SPEAKER: do emails next month.
[55:27] SPEAKER: So that means I need to thank two tiers of patrons.
[55:29] SPEAKER: So that's why I asked, but as always, this is the part of the show where we think our
[55:33] SPEAKER: patrons.
[55:34] SPEAKER: So thank you, patrons.
[55:35] SPEAKER: Yes.
[55:36] SPEAKER: Thank you.
[55:37] SPEAKER: We appreciate everybody who supports the show, whether, whether financially or just by telling
[55:40] SPEAKER: your friends and leaving iTunes reviews and stuff like that.
[55:43] SPEAKER: But we do offer a very special thank you to our executive producer, to your patrons, including
[55:48] SPEAKER: our newly upgraded dollar sign, dollar sign, Andrew Slosky, Paddle Creek Games, makers
[55:55] SPEAKER: of Fractured Veil, David Allen, James Cammack, Joel Krauska, Jordan Lippett, Just Wedge,
[56:01] SPEAKER: Nick Johnston, Pantheon, makers of the HS3 high-speed 3D printer and Twinkle Twinkie.
[56:07] SPEAKER: Thank you all so much.
[56:08] SPEAKER: Yes.
[56:09] SPEAKER: Thank you.
[56:10] SPEAKER: And since it's the end of the month and we'd normally do Q&A, we still will thank our associate
[56:13] SPEAKER: producer patrons who we also appreciate very much, including Alejandro Navarro, Andre M.
[56:18] SPEAKER: Burke, Arthur Gies, Ben Tolman, Eric, Eric Frey, Eric Klein, Eric IV soon to be the first
[56:26] SPEAKER: after the great Eric war.
[56:27] SPEAKER: That's one, two, three, four Eric's.
[56:29] SPEAKER: Still no Eric's, but that's okay.
[56:31] SPEAKER: Getting there.
[56:32] SPEAKER: I think the Eric's, the Eric's continue to grow, I guess is when maybe we'll have a fifth
[56:38] SPEAKER: Eric next month.
[56:39] SPEAKER: We'll have to see.
[56:40] SPEAKER: You know, you can write whatever you want for your name on Patreon.
[56:42] SPEAKER: So I'm just going to put that out there.
[56:43] SPEAKER: Wait, wait, wait.
[56:44] SPEAKER: You, are you suggesting that dollar sign dollar sign is not someone's real name?
[56:48] SPEAKER: I don't know.
[56:51] SPEAKER: Ask the government.
[56:52] SPEAKER: Okay.
[56:53] SPEAKER: Okay.
[56:54] SPEAKER: Felix Kramer, Graham Brinks, Jad Rita, Matt Walker, parentheses Walkman 8080, close parentheses,
[57:00] SPEAKER: Nathan Phelps, Sanchik Kumar, Steve Lin, Thomas Shea, and Tom Hilton.
[57:04] SPEAKER: Thank you all so, so much.
[57:05] SPEAKER: We really appreciate everybody's support and I didn't say this to the front cause I'm off
[57:10] SPEAKER: my game today, but when you subscribe to the Patreon, you get access to the patron exclusive
[57:15] SPEAKER: episodes and you get access to the fabulous tech pod discord, which is full of like the,
[57:20] SPEAKER: I think the gift, the gift the gift exchange stuff is closed now, but like there's just
[57:25] SPEAKER: lovely conversations happening all the time.
[57:27] SPEAKER: And then look, Brad, did you know, and this is what we should have done the cold open
[57:32] SPEAKER: on, but did you know that the children now use discord mod as a slur?
[57:39] SPEAKER: I saw that being discussed shocking.
[57:42] SPEAKER: Is that like their version of cop?
[57:45] SPEAKER: They are the, I think the implication is it's the kind of person who wouldn't allow memes
[57:49] SPEAKER: in general.
[57:50] SPEAKER: Huh?
[57:51] SPEAKER: Okay.
[57:52] SPEAKER: We allow memes in general.
[57:53] SPEAKER: We're cool.
[57:54] SPEAKER: That's why I got called out by a teen, a surly teenager when I was out a few weeks ago when
[57:59] SPEAKER: I was wearing a discord partner t-shirt because they sent me a hoodie a few years ago that
[58:03] SPEAKER: has like discord partner and huge block letters down the arm.
[58:07] SPEAKER: And he was like, what are you a discord mod or something?
[58:09] SPEAKER: I was like, Oh my God.
[58:10] SPEAKER: I mean, kind of, I guess, but it sounds like this is a bad thing.
[58:13] SPEAKER: So I'm going to say not really.
[58:15] SPEAKER: All discord mods are bad.
[58:18] SPEAKER: Ad-mad?
[58:19] SPEAKER: Passions.
[58:20] SPEAKER: Ad-mad?
[58:21] SPEAKER: Yeah.
[58:22] SPEAKER: A-D-ad-mad.
[58:23] SPEAKER: Exactly.
[58:24] SPEAKER: Our discord mods are great and, and mostly just shepherd conversations and help people
[58:30] SPEAKER: explain, understand when they're mansplaining and stuff like that.
[58:33] SPEAKER: So it's a, it's a friendly place to chat.
[58:35] SPEAKER: We try to make it inclusive for everybody.
[58:36] SPEAKER: If we're not, let us know.
[58:37] SPEAKER: We would love to hear about it, but, but lots of good conversations all day, every day talking
[58:43] SPEAKER: about everything from like CPU bracket mounting and how much thermal goo to use to extreme
[58:52] SPEAKER: storage solutions and, and like a good tool to tune your guitar.
[58:57] SPEAKER: So Mr. Scene Drama, you name it.
[59:00] SPEAKER: Is Mr. Scene Drama?
[59:01] SPEAKER: Uh, maybe a little bit.
[59:02] SPEAKER: Oh, I'm going to send a question in for next week.
[59:04] SPEAKER: There's been, there's been some weird sniping back and forth on Twitter recently between
[59:08] SPEAKER: people working on different projects in the Mr. Sphere.
[59:12] SPEAKER: This is a good reminder to send your emails for next week's Q&A episode to techbot@content.town
[59:16] SPEAKER: or to post some of the questions seeking answers channel in the discord.
[59:19] SPEAKER: That'll do it for us, Brad.
[59:21] SPEAKER: See you all next week.
