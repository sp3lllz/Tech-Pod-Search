---
episode: 160
title: Special FOSS Ep: OctoPrint With Gina Häußge
date: 2022-10-02
guests: none
duration: 1:30:13
---

[00:00] SPEAKER: - Brad, I don't have any tattoos.
[00:01] SPEAKER: - No.
[00:02] SPEAKER: - I know, it's shocking.
[00:03] SPEAKER: - It's I am just flabbergasted, phlegmics.
[00:06] SPEAKER: You don't seem like much of a tattoo kind of guy, but go on.
[00:10] SPEAKER: - Well, like I'm into the idea conceptually,
[00:12] SPEAKER: but I've never really liked anything long enough
[00:15] SPEAKER: to feel like I can commit to it
[00:17] SPEAKER: for that kind of length of time.
[00:18] SPEAKER: - That is obstacle number one is not being able
[00:20] SPEAKER: to decide what I want on my body for the rest of my life.
[00:23] SPEAKER: - Yeah, like I don't, I've never, like I like my kid,
[00:26] SPEAKER: but you know, it's weird.
[00:28] SPEAKER: I might have put her face on my back.
[00:30] SPEAKER: Anyway, the point is, I'm looking at our show notes,
[00:33] SPEAKER: our show art for the last couple of weeks,
[00:35] SPEAKER: and I think I see something that I like enough maybe
[00:38] SPEAKER: to put on my body for all eternity.
[00:40] SPEAKER: - Hang on, I have to guess now.
[00:42] SPEAKER: Are we talking tech or phos?
[00:44] SPEAKER: - Phos, this is a phos.
[00:45] SPEAKER: - Oh, not tech.
[00:46] SPEAKER: Is it the Blender logo?
[00:49] SPEAKER: - No, it is not the Blender logo.
[00:51] SPEAKER: - Is it the cute little octopus of Octoprint?
[00:53] SPEAKER: - It is not the cute little octopus.
[00:55] SPEAKER: It is a good octopus, but it is not the Octoprint octopus.
[00:58] SPEAKER: - Wait a minute.
[00:59] SPEAKER: - Yeah, hi.
[01:00] SPEAKER: - Is it the curl logo?
[01:02] SPEAKER: - No, no, not the curl logo.
[01:05] SPEAKER: - Huh, okay, well, there's only so many options here.
[01:08] SPEAKER: - Yeah, that's true.
[01:09] SPEAKER: - I'm guessing it's not this picture of a GitHub repo.
[01:12] SPEAKER: - No.
[01:14] SPEAKER: - Really running out of logo.
[01:15] SPEAKER: Wait a minute.
[01:16] SPEAKER: - Yeah.
[01:17] SPEAKER: - Hang on.
[01:19] SPEAKER: Okay, if this is it.
[01:21] SPEAKER: - Yeah.
[01:22] SPEAKER: - Mad respect.
[01:23] SPEAKER: - Hello, hi.
[01:24] SPEAKER: - Is it the Windows 95 network neighborhood icon?
[01:27] SPEAKER: - I'm looking at it, I'm like, I deeply identify
[01:29] SPEAKER: with that Windows 95 network neighborhood icon.
[01:31] SPEAKER: - That's, okay, look.
[01:33] SPEAKER: - It speaks to me, 'cause you know what?
[01:34] SPEAKER: It's all about connection, Brad.
[01:35] SPEAKER: - It's true, so you're not wrong.
[01:37] SPEAKER: I mean, these two computers are connected
[01:39] SPEAKER: by a right angle pipe of some kind.
[01:40] SPEAKER: I mean, it's like they're right there.
[01:42] SPEAKER: - One has a green screen, one has a blue screen.
[01:44] SPEAKER: It's the metaphor for Windows.
[01:46] SPEAKER: - Is that actually, is that the metaphor
[01:47] SPEAKER: for iMessage versus SMS?
[01:50] SPEAKER: - That's where it all started.
[01:51] SPEAKER: Well, except for blue is the, blue is iMessage,
[01:53] SPEAKER: and yeah, right, yeah.
[01:55] SPEAKER: - Green is SMS.
[01:55] SPEAKER: - Green is for bad people.
[01:56] SPEAKER: I mean, Android people, whatever.
[01:58] SPEAKER: - I picked the show art for all these episodes,
[01:59] SPEAKER: and normally I just put the logo of the project
[02:02] SPEAKER: for the FOSPOD, but the Samba logo was not
[02:06] SPEAKER: of such proportions that would fit into SimpleCasts.
[02:09] SPEAKER: Kind of, I guess that's a one by one frame.
[02:12] SPEAKER: - Well, it's, I mean, it's more pixels than that,
[02:13] SPEAKER: but it's a one to one ratio.
[02:14] SPEAKER: - One to one ratio is what I mean, yeah.
[02:16] SPEAKER: - You can go up to like, you can put 512 pixels in there,
[02:18] SPEAKER: if you want, you can put three pixels in, they don't guess.
[02:20] SPEAKER: - The Samba logo is extremely wide
[02:22] SPEAKER: and extremely not tall,
[02:23] SPEAKER: so it doesn't fit into a square well.
[02:25] SPEAKER: And then I was like, you know what is vaguely square shaped,
[02:27] SPEAKER: is the icon set from Windows 95.
[02:30] SPEAKER: - Home of SMB, that was like SMB two, right?
[02:33] SPEAKER: Or one point something. - Was it really?
[02:34] SPEAKER: - I can't remember.
[02:35] SPEAKER: - So were you working with SMB at that time?
[02:38] SPEAKER: - No, I was in college then.
[02:39] SPEAKER: - Okay.
[02:40] SPEAKER: - I mean, I was, but I didn't know anything about it.
[02:42] SPEAKER: I knew enough, like that was back in the time
[02:43] SPEAKER: when I knew enough to make a network work,
[02:46] SPEAKER: and that was pretty much it.
[02:48] SPEAKER: Didn't know how, I didn't understand TCPs or IPs,
[02:51] SPEAKER: I vaguely understood that you had to get an IP address
[02:53] SPEAKER: from somewhere if you wanted to share internet.
[02:56] SPEAKER: But beyond that, all bets were off.
[02:59] SPEAKER: - Point to point protocol is just about the only protocol
[03:02] SPEAKER: I was aware of at that time.
[03:03] SPEAKER: - We were just slipping back then, man.
[03:04] SPEAKER: - Yes, we arguably are still slipping.
[03:08] SPEAKER: (upbeat music)
[03:21] SPEAKER: (upbeat music continues)
[03:36] SPEAKER: - Welcome to Brad and Will Make a Tech FOSPOD, I'm Will.
[03:39] SPEAKER: - I'm the open source Brad, that doesn't make any sense.
[03:42] SPEAKER: Hello.
[03:43] SPEAKER: - Hi, hello.
[03:44] SPEAKER: We're doing something a little bit different this week.
[03:45] SPEAKER: It's been a minute since we launched this new podcast
[03:48] SPEAKER: in the dawn of 2022.
[03:50] SPEAKER: Now we're coming into 2022's late middle age.
[03:55] SPEAKER: - Dude, I was at Costco earlier.
[03:58] SPEAKER: - Uh-huh, speaking of late middle age.
[04:00] SPEAKER: - The holiday decks are out.
[04:03] SPEAKER: - What?
[04:04] SPEAKER: - The holiday decks, the decorations, the Christmas trees.
[04:07] SPEAKER: - Wait, Christmas stuff is out?
[04:08] SPEAKER: It's not even Halloween yet.
[04:09] SPEAKER: - It is quite literally still September,
[04:11] SPEAKER: and Christmas trees with active lit up Christmas lights
[04:15] SPEAKER: were out, holiday blend coffee was around and for sale.
[04:19] SPEAKER: - Gosh, have I missed the pumpkin spice window already?
[04:22] SPEAKER: - Oh, I saw a new affront to nature
[04:24] SPEAKER: in the pumpkin spice category.
[04:26] SPEAKER: It was like, it was pumpkin spice something
[04:28] SPEAKER: that should not have been, and I can't remember what it was.
[04:30] SPEAKER: - What's like, what wouldn't benefit
[04:32] SPEAKER: from being pumpkin spice?
[04:34] SPEAKER: Like deodorant, not good pumpkin spice, I'm gonna say.
[04:37] SPEAKER: - I think it was a pumpkin spice dipping sauce
[04:40] SPEAKER: right in the middle between like the hummus
[04:42] SPEAKER: and the artichoke dip and stuff.
[04:43] SPEAKER: There was a pumpkin spice dip.
[04:45] SPEAKER: - Pumpkin spice flavored goo?
[04:47] SPEAKER: - Yes.
[04:48] SPEAKER: - I don't know about that one.
[04:50] SPEAKER: - Yeah.
[04:52] SPEAKER: - I'm not a huge fan of the pumpkin spice.
[04:54] SPEAKER: I like a pumpkin pie, which has pumpkin spice.
[04:57] SPEAKER: - Oh, you're a pumpkin pie.
[04:58] SPEAKER: I didn't think I was a fan of pumpkin pie
[05:00] SPEAKER: until I had yours and Gina's pumpkin pie,
[05:02] SPEAKER: and then I was like, whoa.
[05:04] SPEAKER: - Wait, what's this and Gina's crap?
[05:05] SPEAKER: I make that one by hand.
[05:06] SPEAKER: - Wait, really?
[05:07] SPEAKER: - Yeah, that's all me. - The entire thing?
[05:08] SPEAKER: - Uh-huh, from scratch usually.
[05:10] SPEAKER: - Okay, well then your single handed pumpkin pie
[05:13] SPEAKER: is pretty damn good.
[05:14] SPEAKER: - Look, she makes a lot of the other stuff,
[05:15] SPEAKER: but the pies belong to me.
[05:18] SPEAKER: Yeah, look, I'm not a huge fan of the pumpkin spice latte.
[05:21] SPEAKER: I've tried it, I've been there.
[05:22] SPEAKER: I've tasted the forbidden fruit,
[05:24] SPEAKER: and I was like, oh, this is okay.
[05:25] SPEAKER: Too sweet for me.
[05:26] SPEAKER: - You mean the forbidden gourd?
[05:28] SPEAKER: - Yeah, yes, the forbidden gourd.
[05:30] SPEAKER: I do really, really, really, really like
[05:33] SPEAKER: a peppermint mocha, though.
[05:35] SPEAKER: I'll go in for a peppermint mocha.
[05:36] SPEAKER: That's some chocolatey coffee pepperminty business
[05:44] SPEAKER: I can get behind.
[05:45] SPEAKER: - But this week, instead of doing a new tech pod,
[05:49] SPEAKER: we wanted to highlight a recent,
[05:52] SPEAKER: what, like, okay, first off,
[05:54] SPEAKER: the Fosbod sits at the initial launch.
[05:56] SPEAKER: You know, you always find your legs with a new podcast.
[05:58] SPEAKER: It's changed a little bit.
[05:59] SPEAKER: It's gotten a little bit more interviewy of late.
[06:01] SPEAKER: And we've done interviews with a ton of incredible guests
[06:05] SPEAKER: who run projects and work on projects,
[06:08] SPEAKER: ranging from Wikipedia and Home Assistant to Curl.
[06:13] SPEAKER: We, like, we've talked to people who've written code
[06:15] SPEAKER: that runs on Mars.
[06:16] SPEAKER: - We have.
[06:17] SPEAKER: - That's a trip.
[06:17] SPEAKER: We talked to the student insurrectionists,
[06:21] SPEAKER: one of the student insurrectionists who founded VLC
[06:25] SPEAKER: and works on VLC, Jean Baptiste.
[06:28] SPEAKER: - VLC episode, pretty great.
[06:30] SPEAKER: - Audio quality, not great.
[06:31] SPEAKER: Content, 10 out of 10, I'm gonna say.
[06:33] SPEAKER: - He had a lot of very interesting
[06:34] SPEAKER: and opinionated things to say.
[06:36] SPEAKER: - The number of fucks he gave was zero.
[06:38] SPEAKER: - Special life goal achieved.
[06:40] SPEAKER: We talked to Foon.
[06:41] SPEAKER: - We did talk to Foon about 3D Movie Maker.
[06:45] SPEAKER: - Yeah, Twitter's own Foon.
[06:47] SPEAKER: - Yeah.
[06:48] SPEAKER: - One of the best followers on Twitter.
[06:49] SPEAKER: - I mean, consistently, consistently the,
[06:52] SPEAKER: I don't know what, like Foon just,
[06:54] SPEAKER: like every once in a while, you'll just open up Twitter
[06:56] SPEAKER: and be like, oh, Foon's taking something apart again.
[06:58] SPEAKER: And like yesterday it was a keyboard
[07:02] SPEAKER: that didn't, it had like McCherry MX key caps on it.
[07:05] SPEAKER: But then when they took the caps off
[07:07] SPEAKER: and looked at what was underneath,
[07:08] SPEAKER: it was just like a membrane key.
[07:10] SPEAKER: So the MX key caps were just into a plunger
[07:12] SPEAKER: that smashed to the membrane keyboard.
[07:14] SPEAKER: I was like, this is amazing.
[07:15] SPEAKER: - Yeah, data forensics are happening again.
[07:18] SPEAKER: They did like a 40 megabyte hard drive
[07:20] SPEAKER: from the late 80s one time,
[07:22] SPEAKER: which first of all took all kinds of bizarre partitioning
[07:26] SPEAKER: and file system utilities to even access.
[07:28] SPEAKER: - I'm sure.
[07:29] SPEAKER: - But then they found the intact emails on there
[07:31] SPEAKER: from like whatever business was using that hard drive
[07:33] SPEAKER: in the late 80s.
[07:34] SPEAKER: - Who was using email in the late, that's amazing.
[07:36] SPEAKER: - It was, yeah.
[07:37] SPEAKER: - Probably like IPM or somebody.
[07:38] SPEAKER: - 40 gig hard, 40 meg hard drive was pretty big back then.
[07:41] SPEAKER: - I'm kind of fudging dates and sizes a little bit,
[07:43] SPEAKER: but you can just, it was something like that.
[07:45] SPEAKER: Anyway.
[07:46] SPEAKER: - So yeah, we talked to Foon.
[07:48] SPEAKER: We talked to Paul Schautzen from Home Assistant.
[07:50] SPEAKER: We talked to Daniel Stenberg from Curl.
[07:53] SPEAKER: We've talked to, like we said, Jean Baptiste.
[07:54] SPEAKER: We talked to the two of the folks who work on Blender.
[07:58] SPEAKER: - Yeah, Deli and Pablo from, those guys were great.
[08:01] SPEAKER: - Yeah, that was fantastic.
[08:02] SPEAKER: - Really interesting conversation on Blender.
[08:04] SPEAKER: - And then the most recent episode,
[08:06] SPEAKER: we have Jeremy Allison, who is one of the co-creators
[08:09] SPEAKER: and current maintainers of the Samba project,
[08:11] SPEAKER: which like it's, so like we've had this interesting spectrum
[08:15] SPEAKER: of people who are kind of have established wildly popular,
[08:19] SPEAKER: like best in class kind of applications,
[08:21] SPEAKER: like Jim Bailey from OBS and, you know,
[08:24] SPEAKER: Jean Baptiste from VLC and stuff like that.
[08:26] SPEAKER: We talked to people who do plumbing on the internet,
[08:27] SPEAKER: like Daniel Stenberg at Curl and Jeremy at Samba.
[08:32] SPEAKER: - Yes.
[08:33] SPEAKER: - This episode that we're running here today
[08:36] SPEAKER: is one of my absolute favorites
[08:38] SPEAKER: 'cause it's a project that's a little bit newer.
[08:40] SPEAKER: Like it's a project that's kind of grown
[08:42] SPEAKER: with the ecosystem that it supports.
[08:43] SPEAKER: And it's Gina from OctoPrint came in and sat down with us.
[08:49] SPEAKER: And we talked about kind of where,
[08:52] SPEAKER: how that project got started, how it, where it is now,
[08:56] SPEAKER: what like the future of it holds.
[08:59] SPEAKER: 'Cause 3D printing, you know, she started that in 2011
[09:02] SPEAKER: or 2012 when 3D printing was brand,
[09:05] SPEAKER: like consumer 3D printing was brand new.
[09:07] SPEAKER: And with OctoPrint, if you don't know,
[09:10] SPEAKER: is a print server for 3D printers.
[09:12] SPEAKER: So, you know, normally when you run a 3D printer,
[09:14] SPEAKER: well, we talk about it in the episode,
[09:15] SPEAKER: I'm not gonna reiterate here,
[09:16] SPEAKER: but it served a really important purpose.
[09:19] SPEAKER: I used it back in the early, early days
[09:21] SPEAKER: before we really even had, like I ran it on a computer,
[09:23] SPEAKER: not even a Raspberry Pi back then.
[09:26] SPEAKER: It was hugely important for me with the 3D mystery object
[09:28] SPEAKER: and for other stuff we were printing around the office.
[09:30] SPEAKER: And her project is at a different place.
[09:33] SPEAKER: It's, she's at the point now where it's getting too big
[09:36] SPEAKER: for her to do everything herself.
[09:38] SPEAKER: And she's having to like rework the project
[09:40] SPEAKER: so that other people can contribute to it meaningfully.
[09:42] SPEAKER: And it's a really interesting contrast
[09:44] SPEAKER: to some of the other folks we've talked to along the way.
[09:47] SPEAKER: - It seems like she's at the inflection point
[09:49] SPEAKER: where she is going from just developer
[09:51] SPEAKER: to now developer and maintainer.
[09:52] SPEAKER: Or, I mean, I guess you're always a maintainer
[09:55] SPEAKER: even when you're the sole developer,
[09:56] SPEAKER: but I guess the air traffic control aspect
[09:59] SPEAKER: of being a maintainer is going to come to the fore
[10:01] SPEAKER: as soon as she starts taking contributions
[10:04] SPEAKER: from other developers.
[10:05] SPEAKER: - Yeah, she said she paused,
[10:08] SPEAKER: we talk about this a lot in the episode,
[10:09] SPEAKER: but she talks about literally pausing new work
[10:13] SPEAKER: in order to like do documentation and stuff
[10:16] SPEAKER: that will let other people help her accelerate the project.
[10:19] SPEAKER: And it's interesting 'cause as a contrast to Home Assistant
[10:23] SPEAKER: where we talked to Paulus, like he went through that.
[10:26] SPEAKER: He's been like, this seems like the fire and flame
[10:29] SPEAKER: that open source projects that get past a certain level
[10:31] SPEAKER: of success and popularity kind of have to get through,
[10:34] SPEAKER: especially when they support broad hardware ecosystems
[10:38] SPEAKER: as both of those projects do, so.
[10:40] SPEAKER: - Also just real quick, I mean, you'll hear more about this,
[10:43] SPEAKER: but just to pique people's interests
[10:45] SPEAKER: or maybe wet their whistles a little bit,
[10:47] SPEAKER: like I learned a lot about just 3D printing,
[10:49] SPEAKER: what the 3D printing stack entails
[10:51] SPEAKER: and the ups and downs of that process.
[10:52] SPEAKER: And like, there's a lot of neat stuff that OctoPrint does
[10:55] SPEAKER: besides what you might imagine.
[10:56] SPEAKER: Like you could, let's say you want to put your 3D printer
[10:58] SPEAKER: out in the garage so you don't have to breathe fumes
[11:01] SPEAKER: and you can like hook a webcam into it
[11:03] SPEAKER: and use that to observe your print remotely
[11:06] SPEAKER: in addition to doing the kind of microcontroller-y aspects
[11:09] SPEAKER: of running the print.
[11:10] SPEAKER: Anyway, there's a lot of interesting info
[11:12] SPEAKER: and even if you don't know anything about 3D printing
[11:14] SPEAKER: or think you care about it,
[11:15] SPEAKER: there's actually a lot to learn in this episode.
[11:18] SPEAKER: - For the 3D printing expert and the 3D printing curious
[11:21] SPEAKER: is what I would say.
[11:22] SPEAKER: You can even do machine learning on those videos
[11:25] SPEAKER: so that you see if like the print's going bad,
[11:27] SPEAKER: it's really cool.
[11:27] SPEAKER: - Oh, wow.
[11:28] SPEAKER: There's plugins that do visual,
[11:32] SPEAKER: like machine visual recognition of spigotification.
[11:35] SPEAKER: It's really neat.
[11:36] SPEAKER: It's a neat project.
[11:37] SPEAKER: - Are you ever afraid of technology?
[11:39] SPEAKER: You ever like occasionally,
[11:40] SPEAKER: does that just mean I'm getting old?
[11:41] SPEAKER: Like occasionally my like fascination and awe give way
[11:44] SPEAKER: to terror briefly when I hear things like that.
[11:47] SPEAKER: - What's the rule?
[11:48] SPEAKER: Anything that existed before you were seven
[11:50] SPEAKER: has always existed.
[11:51] SPEAKER: Anything that's invented between the time you're seven
[11:54] SPEAKER: and 35 is exciting and cool.
[11:56] SPEAKER: And anything that's invented after year 35 is terrifying.
[11:59] SPEAKER: - I don't like where this is going.
[12:00] SPEAKER: - Yeah, I got bad news for you, Brad.
[12:03] SPEAKER: Yeah, but anyway, our talk with Gina is great.
[12:06] SPEAKER: You should give the episode a listen.
[12:08] SPEAKER: If you enjoy it, please go over to phospod.content.town
[12:11] SPEAKER: and mash that subscribe button, add it to your feed reader,
[12:15] SPEAKER: or you can find us in all the listings now as well.
[12:19] SPEAKER: You have a nice backlog of excellent episodes to listen to.
[12:21] SPEAKER: There'll be more coming in the not too distant future.
[12:25] SPEAKER: We also would love it if anybody who likes the show
[12:28] SPEAKER: would go over to iTunes and mash the review button.
[12:30] SPEAKER: It's still like going there and putting a star rating
[12:33] SPEAKER: on the episode is still one of the best ways
[12:35] SPEAKER: to help podcasts get distribution.
[12:37] SPEAKER: Whether it's our show or anybody else's,
[12:40] SPEAKER: like leaving reviews on iTunes for your favorite podcast,
[12:44] SPEAKER: even if you don't listen to them on iTunes
[12:46] SPEAKER: or with the Apple podcast app or whatever,
[12:49] SPEAKER: really helpful for podcasters.
[12:50] SPEAKER: - And iTunes reviews invented before I turned 35.
[12:52] SPEAKER: So pretty awesome, please.
[12:55] SPEAKER: Please participate.
[12:57] SPEAKER: - And that's it.
[12:58] SPEAKER: I think that, oh, oh, oh, we're doing a,
[13:00] SPEAKER: we want to do a question and answer episode.
[13:02] SPEAKER: - Yeah, we're toying with the idea at least
[13:03] SPEAKER: of doing like a Q and A type episode on the Phosphod.
[13:06] SPEAKER: So with phospod@content.town.
[13:09] SPEAKER: - Yeah, that is an email address
[13:10] SPEAKER: that you can send a question to and we will answer it.
[13:12] SPEAKER: We will hopefully turn it into an A.
[13:15] SPEAKER: We're specifically looking for questions
[13:16] SPEAKER: that we need to go out and get people to answer.
[13:18] SPEAKER: 'Cause we have this large network of folks
[13:20] SPEAKER: who've been on the show and we're talking to you
[13:22] SPEAKER: about future episodes and stuff like that.
[13:24] SPEAKER: And we want to loop them in
[13:25] SPEAKER: and maybe get some like live answers
[13:28] SPEAKER: from experts on their projects about stuff.
[13:30] SPEAKER: So yeah, we're going to abuse our network basically
[13:33] SPEAKER: to do a Q and A episode.
[13:34] SPEAKER: It's going to take like 10 times the effort
[13:36] SPEAKER: of a normal Q and A of a normal episode
[13:38] SPEAKER: of the podcast probably, but here we go.
[13:40] SPEAKER: - It's certainly true.
[13:42] SPEAKER: Even people we haven't had on previously,
[13:44] SPEAKER: if you've got people in the wider open source world
[13:46] SPEAKER: that you would like to put a Q to, we can do our best.
[13:49] SPEAKER: We've got some connections.
[13:50] SPEAKER: - Yeah, we'll make an effort to turn it into an A.
[13:52] SPEAKER: No promises, but we'll see what we can do.
[13:54] SPEAKER: Again, the email address is--
[13:55] SPEAKER: - Fospod@content.town.
[13:58] SPEAKER: - Fospod@content.town, very good.
[13:59] SPEAKER: It's a good email address.
[14:01] SPEAKER: So I guess without further ado,
[14:03] SPEAKER: 17 minutes into this recording,
[14:05] SPEAKER: let's throw it over to past us,
[14:08] SPEAKER: who interviewed Gina from Octoprint.
[14:10] SPEAKER: (dramatic music)
[14:12] SPEAKER: Hey Brad, do you remember the first time
[14:14] SPEAKER: I came down to the basement at Giant Bomb in Sausalito
[14:16] SPEAKER: and showed you a 3D printed ring
[14:20] SPEAKER: that looked vaguely like a deer
[14:22] SPEAKER: and you all were kind of professionally disinterested in it?
[14:26] SPEAKER: - No, that was the finest 3D print
[14:28] SPEAKER: I had ever seen to date at the time.
[14:30] SPEAKER: - That was the only 3D print you'd ever seen
[14:32] SPEAKER: at the time, though, correct?
[14:33] SPEAKER: - Completely professional high quality product
[14:35] SPEAKER: that you turned out there.
[14:36] SPEAKER: I mean, look, that was early days for 3D printing
[14:38] SPEAKER: and even in the best of circumstances,
[14:41] SPEAKER: making kind of warmed over plastic behave itself,
[14:44] SPEAKER: not the smallest feat, right?
[14:46] SPEAKER: - Yeah, it was, okay, so yeah,
[14:47] SPEAKER: the ring was a vaguely ring-shaped thing
[14:49] SPEAKER: made of goopy plastic and the MakerBot cupcake
[14:52] SPEAKER: that Norm and I built in the old Whiskey Media offices
[14:55] SPEAKER: in 2010 was early, to say the least.
[14:58] SPEAKER: It was a finicky machine that was hard to keep running
[15:01] SPEAKER: and hard to get good results out of,
[15:03] SPEAKER: but occasionally you could do something
[15:05] SPEAKER: that was kind of magical.
[15:07] SPEAKER: And in the preceding 12 years, 13 years,
[15:10] SPEAKER: the technology has improved dramatically,
[15:12] SPEAKER: both in terms of the printers,
[15:14] SPEAKER: the kits and the motors that are available
[15:16] SPEAKER: to drive the printers,
[15:17] SPEAKER: the electronics that drive the printers are more powerful.
[15:19] SPEAKER: And the results that you get out of
[15:21] SPEAKER: even a really inexpensive 3D printer right now
[15:23] SPEAKER: are like far and away better than anything
[15:26] SPEAKER: we ever got out of our old cupcake
[15:28] SPEAKER: or even the subsequent printers we use
[15:31] SPEAKER: over the next couple of years.
[15:32] SPEAKER: - Sure, but Will, there are so many printers
[15:34] SPEAKER: on the market now.
[15:35] SPEAKER: What if there were, let's say like a home assistant,
[15:39] SPEAKER: but for 3D printers where you had one interface
[15:41] SPEAKER: that could talk to all of them
[15:43] SPEAKER: and make everything work under a kind of common scheme?
[15:46] SPEAKER: - Oh, you mean something like a print server
[15:48] SPEAKER: for 3D printers?
[15:49] SPEAKER: - Sure, something like that.
[15:50] SPEAKER: If only we could do an episode about something like that.
[15:53] SPEAKER: - If only.
[15:54] SPEAKER: (upbeat music)
[16:13] SPEAKER: Welcome to the FOSPOT, I'm Will.
[16:14] SPEAKER: - I'm Brad.
[16:15] SPEAKER: - Brad, this week I am very, very excited
[16:18] SPEAKER: to introduce our guest.
[16:20] SPEAKER: We, on the show this week,
[16:23] SPEAKER: have Gina Hoyska of the OctoPrint project,
[16:28] SPEAKER: which is, it's a print server for 3D printers.
[16:31] SPEAKER: - Dude, 3D printing very close to your heart.
[16:35] SPEAKER: Not something I have ever dabbled with.
[16:36] SPEAKER: Like I just am an outsider looking in,
[16:38] SPEAKER: but like A, this was a fascinating conversation.
[16:41] SPEAKER: Like she was so interesting to listen to.
[16:43] SPEAKER: But B, I have no idea how, let's say,
[16:47] SPEAKER: ramshackle the 3D printing process
[16:50] SPEAKER: is without something like OctoPrint.
[16:52] SPEAKER: - Well, okay, I wouldn't say it's ramshackle.
[16:54] SPEAKER: The process is pretty straightforward, right?
[16:56] SPEAKER: You take a 3D model that's an STL or an OBJ
[16:58] SPEAKER: or some relatively standard file format
[17:01] SPEAKER: that describes a 3D shape in space, right?
[17:04] SPEAKER: And then you use a tool called a slicer
[17:06] SPEAKER: and you position that shape on the print bed
[17:09] SPEAKER: and the slicer looks at it and says,
[17:12] SPEAKER: okay, we're gonna cut it up into this many layers
[17:14] SPEAKER: 'cause this is the vertical resolution of the printer,
[17:16] SPEAKER: how thick the layers that the printer prints are.
[17:18] SPEAKER: And you orient it on the bed
[17:20] SPEAKER: so that you get the best results for what you want,
[17:21] SPEAKER: whether you want like a flat bottom or whatever.
[17:24] SPEAKER: There's a bunch of nuance to that,
[17:25] SPEAKER: but this is all stuff that people have to do.
[17:28] SPEAKER: And then that slicer turns that 3D model
[17:30] SPEAKER: into a series of layers.
[17:32] SPEAKER: And the layers are represented
[17:34] SPEAKER: by the movements of the print head
[17:35] SPEAKER: or the movements of whatever the mechanism is
[17:37] SPEAKER: that generates the material for each layer.
[17:39] SPEAKER: And then it goes up a layer
[17:40] SPEAKER: and then it does the same thing again.
[17:42] SPEAKER: And eventually you have this stack of slices
[17:44] SPEAKER: that becomes a 3D object.
[17:47] SPEAKER: Now, the tricky part is
[17:49] SPEAKER: that the slicer generates this stuff called G code,
[17:51] SPEAKER: which is basically software that describes
[17:54] SPEAKER: how the print head moves.
[17:57] SPEAKER: It literally is like go from X zero zero to X one seven,
[18:01] SPEAKER: you know, X seven Y four
[18:04] SPEAKER: and move the motor that extrudes the plastic this speed
[18:07] SPEAKER: during that entire movement, stuff like that.
[18:10] SPEAKER: And that G code is both printer specific
[18:13] SPEAKER: and is incredibly important
[18:15] SPEAKER: to getting a high quality print out of your printer.
[18:18] SPEAKER: So if your slicer does a bad job,
[18:19] SPEAKER: you're not gonna have a good print.
[18:20] SPEAKER: There's nothing you can do about it at that point.
[18:22] SPEAKER: - Right, that's an example of the kind of stuff
[18:23] SPEAKER: I'm talking about.
[18:24] SPEAKER: Like for example, what you just said,
[18:26] SPEAKER: the fact that G code is unique
[18:28] SPEAKER: to kind of the maker of the 3D printer, right?
[18:30] SPEAKER: Like it's not a universal language.
[18:31] SPEAKER: And another fact that came out of this conversation
[18:34] SPEAKER: that blew my mind and OctoPrint helps with stuff like this
[18:37] SPEAKER: is that it's not like you are loading that entire design
[18:40] SPEAKER: onto onboard memory on the 3D printer
[18:42] SPEAKER: and just pressing a button and walking away.
[18:44] SPEAKER: Like you had to maintain a steady flow of information
[18:47] SPEAKER: to the printer from like whatever PC
[18:49] SPEAKER: you were feeding it from.
[18:50] SPEAKER: And like, that's a place where OctoPrint
[18:52] SPEAKER: helps smooth the process.
[18:53] SPEAKER: We'll get into that.
[18:54] SPEAKER: - Well, yeah, so these days,
[18:56] SPEAKER: most printers do have onboard memory
[18:57] SPEAKER: and lets you load it directly onto the board.
[19:00] SPEAKER: There are benefits to doing it with a host based connection,
[19:03] SPEAKER: which is what it's, you know,
[19:04] SPEAKER: usually in the old days in 2010,
[19:06] SPEAKER: when we were printing in the tested office,
[19:07] SPEAKER: we would plug the cupcake with a USB port
[19:10] SPEAKER: that had a serial connection over that USB port
[19:13] SPEAKER: to a host machine.
[19:14] SPEAKER: And the G code would be fed from a machine,
[19:16] SPEAKER: a piece of software running on that computer over.
[19:18] SPEAKER: Now, if like the CPU usage spiked
[19:20] SPEAKER: or the computer froze for a second or two,
[19:22] SPEAKER: it would jack up your print
[19:23] SPEAKER: 'cause everything would get out of whack basically,
[19:26] SPEAKER: which was- - That just blows my mind.
[19:27] SPEAKER: Like, why would anybody want to deal with that?
[19:29] SPEAKER: - Well, yeah. - Now they don't have to.
[19:30] SPEAKER: - And the prints were, you know, 12, 13, 14 hours sometimes
[19:34] SPEAKER: for a big one.
[19:35] SPEAKER: So like the cost of failure there is really, really high
[19:37] SPEAKER: in terms of time,
[19:38] SPEAKER: 'cause you get like one or two shots a day
[19:40] SPEAKER: on a big, highly complex print.
[19:42] SPEAKER: The other thing was there was no way to monitor it.
[19:44] SPEAKER: So these prints take a long time.
[19:46] SPEAKER: You don't necessarily want to have the thing
[19:47] SPEAKER: that's spitting out the ABS plastic
[19:49] SPEAKER: sitting in your workspace
[19:50] SPEAKER: whether you're gonna look at it,
[19:51] SPEAKER: 'cause it smells bad and it'll give you a headache.
[19:53] SPEAKER: And it's probably not super healthy over the longterm.
[19:56] SPEAKER: So, but also you don't want to leave this thing
[19:59] SPEAKER: that has a 200 degree Celsius hot end
[20:01] SPEAKER: spewing plastic out unsupervised,
[20:03] SPEAKER: 'cause it's kind of a fire hazard,
[20:05] SPEAKER: not like a bad fire hazard,
[20:06] SPEAKER: but it's like just often enough
[20:07] SPEAKER: that you want to keep an eye on it.
[20:09] SPEAKER: So OctoPrint does both of those things.
[20:11] SPEAKER: It feeds the G-code to the printers.
[20:13] SPEAKER: It lets you hook up cameras and things like that
[20:15] SPEAKER: to the device so you can kind of track what's going on.
[20:18] SPEAKER: And it does all sorts of other fancy stuff.
[20:20] SPEAKER: Like there's all like cool machine learning visual,
[20:23] SPEAKER: we'll talk about with Gina in a minute.
[20:24] SPEAKER: - Yeah, yeah.
[20:25] SPEAKER: It sounds like it does quite a bit more
[20:26] SPEAKER: than just that basic stuff.
[20:27] SPEAKER: But yeah, why don't we let Gina tell us all about it?
[20:30] SPEAKER: - This week's FOSBOD is brought to you by Google Open Source.
[20:33] SPEAKER: They bring all the value of open source to Google
[20:35] SPEAKER: and all the resources of Google to open source.
[20:38] SPEAKER: You can find out more about Google Open Source
[20:39] SPEAKER: at opensource.google.
[20:42] SPEAKER: (upbeat music)
[20:46] SPEAKER: I'm curious how you got started with OctoPrint.
[20:47] SPEAKER: Like were you working with 3D printing for work or for fun
[20:51] SPEAKER: and you had a problem to solve?
[20:53] SPEAKER: What was your path to thinking,
[20:54] SPEAKER: oh, I need to make a print server for 3D printers?
[20:57] SPEAKER: - Yeah, so first of all, maybe I should start
[20:59] SPEAKER: how I even got into 3D printing in the first place.
[21:03] SPEAKER: And it so happened that I was at this hacker conference
[21:05] SPEAKER: hacking at random in 2009 in the Netherlands.
[21:09] SPEAKER: And in one tent, or maybe it was also a brick building,
[21:13] SPEAKER: I can't remember,
[21:13] SPEAKER: they had set up some of these new 3D printers.
[21:17] SPEAKER: So the patents had just expired a couple of years prior
[21:19] SPEAKER: or maybe even one year prior.
[21:21] SPEAKER: I can't remember right now the exact timeline.
[21:23] SPEAKER: And suddenly there were these things now for me to look at
[21:26] SPEAKER: and be mesmerized by like pieces of plastic
[21:30] SPEAKER: just happening out of thin air into existence,
[21:34] SPEAKER: a bit like replicators from Star Trek
[21:36] SPEAKER: or something like that.
[21:36] SPEAKER: And that was kind of when I figured,
[21:38] SPEAKER: okay, this is a very fascinating technology,
[21:41] SPEAKER: but I did not have space for something like that
[21:43] SPEAKER: at that time.
[21:43] SPEAKER: So, and then suddenly friends, nerdy friends of mine
[21:47] SPEAKER: started to acquire 3D printers left and right.
[21:49] SPEAKER: And we are now in something like 2010, 2011.
[21:53] SPEAKER: And then in 2012, I moved into a bigger apartment,
[21:57] SPEAKER: which I'm also actually still in.
[21:59] SPEAKER: And suddenly I have found myself in the possession of space
[22:03] SPEAKER: to acquire a 3D printer.
[22:04] SPEAKER: So after some back and forth and research and all that,
[22:06] SPEAKER: I bought myself a 3D printer, set it up here in my office,
[22:09] SPEAKER: put it next to my PC.
[22:11] SPEAKER: And back then these things were really, really dumb.
[22:13] SPEAKER: So they did not have the capability
[22:15] SPEAKER: of running a print shop themselves,
[22:17] SPEAKER: but you had to tether them to your computer
[22:19] SPEAKER: or to your laptop or whatnot,
[22:20] SPEAKER: and then spool and stream the full job to them
[22:23] SPEAKER: over the duration of the job.
[22:25] SPEAKER: So if your PC decided to do an upgrade in the meantime,
[22:28] SPEAKER: your print was broken.
[22:30] SPEAKER: If you wanted to play a game, which I'm also a gamer,
[22:33] SPEAKER: which is something that I tend to do in my free time
[22:36] SPEAKER: when I'm sitting in front of my desk,
[22:38] SPEAKER: then you were running the risk of interrupting your print
[22:41] SPEAKER: by slowdowns or something like that.
[22:43] SPEAKER: So that was a bit suboptimal.
[22:45] SPEAKER: And also there is the addition of printers,
[22:48] SPEAKER: produce noise, produce fumes,
[22:50] SPEAKER: and this thing was sitting next to me for hours on end,
[22:54] SPEAKER: so that was a bit annoying.
[22:55] SPEAKER: And I figured, okay, this year in 2012,
[22:59] SPEAKER: the Raspberry Pi had just been released,
[23:00] SPEAKER: which was this little, or is this little,
[23:02] SPEAKER: about 35, 40-ish bucks kind of single PCB computer.
[23:07] SPEAKER: And I figured, well, I'm sure there is some software
[23:10] SPEAKER: out of there that I can just throw on the thing
[23:12] SPEAKER: and then put a Wi-Fi dongle on it.
[23:14] SPEAKER: The Raspberry Pi back then did not even have Wi-Fi
[23:16] SPEAKER: on board yet, throw that in my spare bathroom,
[23:19] SPEAKER: monitor it from my phone or something like that,
[23:21] SPEAKER: and then I know what is going on,
[23:23] SPEAKER: but I do not have to sit next to it,
[23:25] SPEAKER: and also it does not take up my PC
[23:27] SPEAKER: and also not the whole office, basically.
[23:30] SPEAKER: And so I got myself a Raspberry Pi,
[23:32] SPEAKER: and then I looked for software that would do what I wanted,
[23:35] SPEAKER: and I couldn't find any.
[23:36] SPEAKER: So there were some, I think, two or three packages
[23:39] SPEAKER: that basically treated the printer like a black box,
[23:42] SPEAKER: like shooting it code and hoping it would do the right thing
[23:45] SPEAKER: but no kind of feedback loop.
[23:47] SPEAKER: And that was something that really was not something
[23:49] SPEAKER: that I wanted, because printers back then
[23:52] SPEAKER: were even less reliable than they are these days.
[23:56] SPEAKER: So you really wanted to keep an eye on it,
[23:58] SPEAKER: especially during the crucial first half an hour
[24:00] SPEAKER: or something like that,
[24:01] SPEAKER: to make sure that bed adhesion was working
[24:02] SPEAKER: and the temperatures kept up and stuff like that.
[24:05] SPEAKER: And so I figured, okay, there is nothing like that.
[24:08] SPEAKER: Maybe I should just sit down and build.
[24:11] SPEAKER: So maybe some words on my background.
[24:14] SPEAKER: I've always been a nerd.
[24:15] SPEAKER: I learned coding at the age of seven.
[24:17] SPEAKER: I got into computer science at university,
[24:20] SPEAKER: and I later turned software engineer
[24:23] SPEAKER: slash technical architect stuff.
[24:25] SPEAKER: So that was my background back there,
[24:27] SPEAKER: being like a corporate drone during the day,
[24:30] SPEAKER: and then at night tinkering with pet projects
[24:33] SPEAKER: because coding to this day is still like my major passion.
[24:37] SPEAKER: - How did you get started coding at,
[24:38] SPEAKER: like seven seems early.
[24:40] SPEAKER: - Yeah, especially in the 80s, right?
[24:42] SPEAKER: (laughs)
[24:44] SPEAKER: Yeah, that was when my parents got the first computer
[24:47] SPEAKER: back then from my uncle actually,
[24:49] SPEAKER: an old Apple IIe that he no longer needed,
[24:52] SPEAKER: which was, it had this green shaded monitor
[24:56] SPEAKER: and it came with two five and a quarter inch floppy drives
[25:00] SPEAKER: and that was it.
[25:02] SPEAKER: And naturally me as a six or seven year old,
[25:04] SPEAKER: seeing that thing,
[25:05] SPEAKER: I was all about gaming and playing games with it.
[25:08] SPEAKER: And my dad on the other hand, however,
[25:10] SPEAKER: he took me to the side and was like,
[25:11] SPEAKER: no, this is a working machine.
[25:12] SPEAKER: This is a tool.
[25:13] SPEAKER: This is not a toy, but I can show you something.
[25:16] SPEAKER: And then he showed me the first couple of lines of basic
[25:19] SPEAKER: and I wrote my first code.
[25:21] SPEAKER: And then we went into this a bit
[25:23] SPEAKER: as a daddy daughter kind of thing.
[25:24] SPEAKER: My mom also chimed in here and there
[25:26] SPEAKER: and then also coded some stuff up.
[25:28] SPEAKER: So it was a bit of a family thing at first,
[25:30] SPEAKER: but it kind of totally clicked with me
[25:33] SPEAKER: because I also love, still love,
[25:36] SPEAKER: and back then already loved playing with Lego
[25:39] SPEAKER: and building stuff with Lego.
[25:40] SPEAKER: And to me, coding still to this day,
[25:44] SPEAKER: just feels like building stuff out of Lego,
[25:47] SPEAKER: but the bricks never run out.
[25:48] SPEAKER: And if I'm missing a certain kind of brick,
[25:50] SPEAKER: I can just build it.
[25:52] SPEAKER: - I never thought about it like that before.
[25:53] SPEAKER: It makes a ton of sense.
[25:54] SPEAKER: - What kind of coding work were you doing as you put it
[25:56] SPEAKER: as a corporate drone before you started working
[25:58] SPEAKER: on OctoPrint full time?
[25:59] SPEAKER: Were you doing coding that already worked with hardware
[26:01] SPEAKER: in your day job at that time or?
[26:03] SPEAKER: - No less, I mean, yeah, in a way,
[26:05] SPEAKER: every kind of code works with hardware, right?
[26:07] SPEAKER: But I was mostly working as a consultant
[26:12] SPEAKER: doing custom solution development for various clients
[26:15] SPEAKER: with a bit of a focus on IPTV stuff,
[26:18] SPEAKER: like coding recording back ends and set up box front ends
[26:23] SPEAKER: and stuff like this in various languages,
[26:26] SPEAKER: primarily Java though.
[26:27] SPEAKER: So building OctoPrint in Python was a bit of a diversion
[26:31] SPEAKER: from a usual kind of thing as well.
[26:33] SPEAKER: I had been a system administrator
[26:36] SPEAKER: during my university days and so got familiar with Python
[26:38] SPEAKER: during that time because you have automation
[26:41] SPEAKER: or something like that, it's just beautiful.
[26:43] SPEAKER: And then when I sat down during my Christmas break of 2012
[26:48] SPEAKER: and was wondering, so how do I get this,
[26:50] SPEAKER: what I'm envisioning here,
[26:52] SPEAKER: this remote control slash baby monitor thingy
[26:55] SPEAKER: for my 3D printer now somehow built in a way
[26:59] SPEAKER: that it will actually be done within like one or two weeks.
[27:03] SPEAKER: Yeah, the word done is a bit ironic
[27:05] SPEAKER: given that we are now almost 10 years later
[27:07] SPEAKER: and I'm still working on it, but so that it's usable.
[27:10] SPEAKER: Let's call it like that.
[27:11] SPEAKER: And I fell over what is still available by the way,
[27:15] SPEAKER: which is the Cura Slicer and the Cura Slicer back then
[27:17] SPEAKER: and I think also still had the ability
[27:20] SPEAKER: to also connect to a printer and talk to a printer
[27:22] SPEAKER: and stream stuff to a printer.
[27:24] SPEAKER: So I took this part and Cura is written in Python.
[27:26] SPEAKER: So I took this part and build up all around it.
[27:29] SPEAKER: In the beginning, I had absolutely no idea
[27:31] SPEAKER: how to communicate with a printer.
[27:32] SPEAKER: I figured, oh, it's a serial interface.
[27:34] SPEAKER: It can't be so difficult and it turns out
[27:36] SPEAKER: that this is one of the most stressful
[27:37] SPEAKER: and complicated parts of my whole job now
[27:41] SPEAKER: because yeah, we don't really have
[27:44] SPEAKER: a proper well-defined standard there.
[27:46] SPEAKER: So every printer vendor and every firmware vendor
[27:49] SPEAKER: does things slightly differently,
[27:51] SPEAKER: which makes it an absolute nightmare to interface with.
[27:53] SPEAKER: But back then I was naive and optimistic
[27:57] SPEAKER: and just took this basic com layer from Cura
[28:01] SPEAKER: and built my web interface in Flask on top of it.
[28:04] SPEAKER: And within, I think around, yeah,
[28:08] SPEAKER: I sat down on it sometime around December 20th or 23rd
[28:13] SPEAKER: and by 25th it was already printing and giving me feedback.
[28:17] SPEAKER: And then I also added a webcam feed
[28:19] SPEAKER: and by the end of my vacation come January,
[28:23] SPEAKER: I figured, okay, it's doing everything that I wanted it to.
[28:25] SPEAKER: I'm just going to throw it up now on GitHub
[28:27] SPEAKER: or something like that and yeah, post some stuff
[28:32] SPEAKER: publicly about it on Google Plus back then
[28:34] SPEAKER: was still my hood, so to speak.
[28:36] SPEAKER: And then I'll return to my normal life.
[28:39] SPEAKER: And then suddenly emails started pouring in
[28:42] SPEAKER: from all over the world and tickets started showing up
[28:44] SPEAKER: in my GitHub issue tracker where people were like,
[28:46] SPEAKER: eh, I've been meaning to have something like this for ages
[28:50] SPEAKER: or that's beautiful, I never thought I needed this
[28:53] SPEAKER: but now I can't live without it anymore, things like that.
[28:56] SPEAKER: And it started growing and growing and growing.
[29:01] SPEAKER: And by mid of 2013, I actually talked to my boss
[29:05] SPEAKER: about reducing my job to four days a week
[29:07] SPEAKER: so that I could have one week dedicated to OctoPrint,
[29:11] SPEAKER: obviously out of my own pocket.
[29:13] SPEAKER: And then by early 2014, I had to realize that this one week,
[29:19] SPEAKER: one day per week was not even remotely doing it justice
[29:22] SPEAKER: anymore either because the user base was just growing
[29:24] SPEAKER: and growing and growing.
[29:25] SPEAKER: And at that time I was approached by a Spanish technology
[29:29] SPEAKER: company who was also building 3D printers.
[29:32] SPEAKER: And they said, hey, we want to invite you to Madrid.
[29:35] SPEAKER: And then they flew me in and then we talked
[29:37] SPEAKER: and it turned out that they really enjoyed my work
[29:39] SPEAKER: on OctoPrint and just wanted me to be able
[29:41] SPEAKER: to do it full time.
[29:42] SPEAKER: - Oh, that's fabulous.
[29:43] SPEAKER: - Yeah, that was nice because it also came
[29:46] SPEAKER: with an absolutely perfect timing because I was really
[29:50] SPEAKER: starting to wonder how to juggle both
[29:53] SPEAKER: of these responsibilities in my life, the paying job
[29:56] SPEAKER: and the little paying job and this creation of mine
[30:01] SPEAKER: that I felt was gaining a lot of traction
[30:03] SPEAKER: and that I was really not doing it justice
[30:06] SPEAKER: due to a lack of time.
[30:07] SPEAKER: - Had you done open source work before this
[30:08] SPEAKER: or was this the first open source project
[30:10] SPEAKER: you contributed to?
[30:11] SPEAKER: - Nah, I did some, yeah.
[30:12] SPEAKER: So actually I did open source before I knew
[30:16] SPEAKER: what open source was.
[30:17] SPEAKER: So back then the stuff that I published very, very early
[30:21] SPEAKER: in the very early 2000s, I just threw that up
[30:25] SPEAKER: for people to use.
[30:26] SPEAKER: I didn't know what open source licenses were
[30:28] SPEAKER: or something like this, but that is how I started.
[30:31] SPEAKER: And then I also, I was a contributor
[30:33] SPEAKER: to the Docker Wiki project for a while
[30:35] SPEAKER: and the maintainer Andreas Gor is still also
[30:37] SPEAKER: a close person, a friend of mine.
[30:39] SPEAKER: So I already made friendships through open source
[30:43] SPEAKER: before I had my own big project going.
[30:45] SPEAKER: So that's kind of nice.
[30:47] SPEAKER: (upbeat music)
[30:51] SPEAKER: - So I installed Octoprint because I foolishly,
[30:54] SPEAKER: I desperately needed to have a 3D printer.
[30:56] SPEAKER: I didn't wanna spend my own money on one.
[30:57] SPEAKER: So I justified it by telling the people
[30:59] SPEAKER: that owned the site that I was working on at the time
[31:01] SPEAKER: that we would just do a weekly print
[31:03] SPEAKER: and make a time-lapse video that we put on YouTube
[31:05] SPEAKER: and people would love that.
[31:06] SPEAKER: And it turns out two of those things were true.
[31:09] SPEAKER: And in 2010, when we built the cupcake,
[31:11] SPEAKER: getting a 3D printer to work reliably once a week
[31:15] SPEAKER: turned out to be a pretty substantial challenge.
[31:17] SPEAKER: - Oh yeah, yeah.
[31:18] SPEAKER: But by the time you came around with Octoprint,
[31:21] SPEAKER: I think we were on a MakerBot or a Replicator
[31:23] SPEAKER: or something like that and eventually moved to PrinterBots
[31:25] SPEAKER: and the market for printers exploded right around the time
[31:28] SPEAKER: that you kicked off with Octoprint.
[31:30] SPEAKER: How much has that explosion of that 3D printer market,
[31:33] SPEAKER: like just the sheer volume of 3D printers
[31:36] SPEAKER: been both important to you and also,
[31:38] SPEAKER: I have to imagine it's an absolute nightmare
[31:40] SPEAKER: supporting a million different printers.
[31:43] SPEAKER: - It is, yeah, it absolutely is.
[31:46] SPEAKER: And yeah, so this explosion kind of coincided
[31:49] SPEAKER: with my move towards first being full-time working
[31:54] SPEAKER: on Octoprint, but still employed.
[31:56] SPEAKER: And then later when this company that I mentioned
[31:58] SPEAKER: ran out of money for endeavors like that,
[32:00] SPEAKER: also yeah, this boom and this enormous amount
[32:04] SPEAKER: of people out there now with printers allowed me to say,
[32:08] SPEAKER: okay, I'm going to risk this.
[32:09] SPEAKER: I'm going to try if I can do this through crowdfunding
[32:12] SPEAKER: back in 2016 and that has been working well since then.
[32:16] SPEAKER: So, I mean, in the beginning,
[32:18] SPEAKER: we only had a very, very small number of companies
[32:20] SPEAKER: producing printers commercially
[32:22] SPEAKER: and usually it was a case of find someone with a printer
[32:24] SPEAKER: and have them print some parts for you,
[32:26] SPEAKER: the vitamins you add yourself
[32:28] SPEAKER: with the vitamins being stuff like screws
[32:30] SPEAKER: and linear rails and whatnot.
[32:32] SPEAKER: And then you build that and hopefully at some point
[32:36] SPEAKER: it would actually work or sometimes it didn't.
[32:39] SPEAKER: And then people like MakerBot and Ultimaker
[32:42] SPEAKER: and later also PrinterBot and stuff came on the scene
[32:46] SPEAKER: and made this a bit more accessible for the masses
[32:48] SPEAKER: and that was also when I jumped in.
[32:50] SPEAKER: And then after that, then came China, right?
[32:54] SPEAKER: And that was really when the whole boom happened,
[32:56] SPEAKER: when we got these cheap printers
[32:58] SPEAKER: where it was pretty much a race to the bottom,
[33:00] SPEAKER: sadly not only in price, but also in quality.
[33:02] SPEAKER: So there have been some safety hazards over the years
[33:05] SPEAKER: and also some absolutely horrible things in firmware
[33:10] SPEAKER: that I had to work around.
[33:12] SPEAKER: And so that has been a bit of a gift and a curse
[33:15] SPEAKER: at the same time.
[33:16] SPEAKER: On the one hand, it made the whole technology
[33:17] SPEAKER: really accessible for a lot of people
[33:19] SPEAKER: who have done really, really awesome things with it.
[33:22] SPEAKER: On the other hand, it has made the whole landscape
[33:26] SPEAKER: so very much fragmented
[33:27] SPEAKER: and with a multitude of electronics
[33:29] SPEAKER: that I can encounter with OctoPrint,
[33:31] SPEAKER: with a multitude of firmware
[33:32] SPEAKER: that I can encounter with OctoPrint
[33:34] SPEAKER: that writing code to interface with all the 3D printers
[33:38] SPEAKER: under the sun out there is really, really challenging
[33:41] SPEAKER: and I had absolutely not anticipated
[33:44] SPEAKER: how much work that would be.
[33:45] SPEAKER: I thought the biggest challenge would be the web interface
[33:47] SPEAKER: and the API and designing that stuff
[33:50] SPEAKER: so that people would actually want to use it.
[33:52] SPEAKER: But, and I mean that as also a big challenge.
[33:54] SPEAKER: And now I also have the plug-in system
[33:55] SPEAKER: that I have to think about and things like that.
[33:57] SPEAKER: But whenever I need to do something
[34:00] SPEAKER: in the communication layer,
[34:02] SPEAKER: let's just say the gray in my hair
[34:05] SPEAKER: has really increased over the past 10 years.
[34:09] SPEAKER: And I think at least some of that is due to OctoPrint.
[34:12] SPEAKER: - How many actual platforms would you say there are
[34:14] SPEAKER: that you have to support?
[34:15] SPEAKER: Like in the smart home space, for example,
[34:17] SPEAKER: there will be like smart plugs
[34:18] SPEAKER: from a zillion different vendors,
[34:19] SPEAKER: but then you look and see that like,
[34:21] SPEAKER: oh, 90% of these are all using the same controller chips.
[34:23] SPEAKER: So that's actually just one interface.
[34:25] SPEAKER: Is there a similar situation in 3D printers
[34:27] SPEAKER: where a lot of the like rebadged models
[34:29] SPEAKER: are all actually using the same controller hardware?
[34:31] SPEAKER: - Yeah, so thankfully we have a bunch of,
[34:33] SPEAKER: let's say firmware families.
[34:36] SPEAKER: So on one hand, there is Marlin,
[34:38] SPEAKER: which is still I think the biggest player.
[34:40] SPEAKER: I have some stats up on stats.octoprint.org
[34:43] SPEAKER: that people can look at if they are interested
[34:45] SPEAKER: in what firmware I use.
[34:47] SPEAKER: But there is Marlin.
[34:49] SPEAKER: Then there is various forks of that also
[34:52] SPEAKER: that have slight different implementations here and there.
[34:55] SPEAKER: Then Repetier firmware is also something
[34:58] SPEAKER: that is still present.
[35:00] SPEAKER: We have Clipper.
[35:01] SPEAKER: We used to have something called,
[35:04] SPEAKER: how was it called, Redeem, maybe, not sure right now.
[35:09] SPEAKER: And some other stuff,
[35:11] SPEAKER: some self-cooked things that I like to just call.
[35:14] SPEAKER: Yeah, it's tricky for some of the things
[35:16] SPEAKER: to give them a name even,
[35:18] SPEAKER: because if the firmware doesn't identify itself
[35:20] SPEAKER: with some name, then you have to give it some name.
[35:22] SPEAKER: So one firmware out there I just call CBDMated,
[35:26] SPEAKER: because that is what the firmware prints out
[35:28] SPEAKER: when you run it.
[35:29] SPEAKER: But yeah, no idea who actually made it.
[35:31] SPEAKER: It just ships with some Chinese printers
[35:33] SPEAKER: and has some very, very interesting interpretations
[35:36] SPEAKER: of the communication protocol,
[35:37] SPEAKER: which require an OctoPrint plugin to fix,
[35:40] SPEAKER: or rather to standardize and to make usable again.
[35:44] SPEAKER: - You had mentioned that some of the firmware
[35:46] SPEAKER: is shipped with things that were shocking to you.
[35:48] SPEAKER: Like what kind of,
[35:50] SPEAKER: I mean, a 3D printer is an inherently semi-dangerous thing.
[35:53] SPEAKER: It has a hot end that gets, what, 200 Celsius,
[35:55] SPEAKER: and it runs something that'll catch on fire
[35:57] SPEAKER: if you leave it in there long enough through that end.
[36:00] SPEAKER: But what do you find that's dangerous?
[36:02] SPEAKER: - So one of the things that OctoPrint
[36:04] SPEAKER: actually started warning people about
[36:06] SPEAKER: after one too many posts on Reddit
[36:08] SPEAKER: about actually burned down printers
[36:11] SPEAKER: was that some vendors ship their printers
[36:14] SPEAKER: with the so-called thermal runaway protection disabled.
[36:17] SPEAKER: And that is simply a feature in firmware
[36:19] SPEAKER: that will look at how much power
[36:21] SPEAKER: is it currently putting into the heater,
[36:23] SPEAKER: and what kind of temperature difference
[36:25] SPEAKER: is it measuring with the thermistor that is in the hot end.
[36:29] SPEAKER: And if it sees that one thing is rising,
[36:31] SPEAKER: but the other isn't, then there is some kind of disconnect.
[36:34] SPEAKER: So either the heater cartridge is stuck in on position
[36:38] SPEAKER: or something like that,
[36:39] SPEAKER: or the thermistor fell out of the hot end,
[36:40] SPEAKER: which, yes, is something that can happen,
[36:43] SPEAKER: especially in, let's say, sub-quality components
[36:46] SPEAKER: or sub-par quality components.
[36:49] SPEAKER: And the problem with this is if you buy cheap thermistors
[36:52] SPEAKER: and cheap hardware in general,
[36:54] SPEAKER: that sometimes that's hardware in these thermistors
[36:57] SPEAKER: and also your controllers and whatnot can be a bit flaky.
[37:00] SPEAKER: And this flakiness then will lead to false positives
[37:03] SPEAKER: of this thermal runaway protection.
[37:05] SPEAKER: So some vendors are going the route of,
[37:07] SPEAKER: instead of fixing their components,
[37:09] SPEAKER: they're simply disabling the watchdog.
[37:11] SPEAKER: And then if something breaks,
[37:14] SPEAKER: you might suddenly have a hot end
[37:16] SPEAKER: that is not sitting at 200 degrees, but at 600 degrees.
[37:19] SPEAKER: And the PTFE tube inside is now releasing
[37:22] SPEAKER: some chlorine compounds or something like that.
[37:25] SPEAKER: So a burning printer is not necessarily the worst thing
[37:28] SPEAKER: that can happen to you in this case,
[37:30] SPEAKER: or the only thing that can happen to you.
[37:32] SPEAKER: And yeah, so I started identifying firmware
[37:35] SPEAKER: also for this reason, to just be able to tell people,
[37:38] SPEAKER: "Hey, the firmware you're running there,
[37:40] SPEAKER: that has this very, very, very bad flaw,
[37:43] SPEAKER: and you really need to get this fixed,
[37:45] SPEAKER: flash different firmware or read up here
[37:48] SPEAKER: on how to configure it properly," stuff like that.
[37:51] SPEAKER: - It's interesting 'cause the more I spent 3D printing,
[37:54] SPEAKER: the less I wanted to sit next to a 3D printer all day
[37:56] SPEAKER: while it was running.
[37:57] SPEAKER: I don't know that people necessarily understand,
[38:00] SPEAKER: 3D prints, especially FDM, the fuse deposition
[38:03] SPEAKER: where you spit the plastic out,
[38:04] SPEAKER: it's often a really lengthy time-consuming process.
[38:07] SPEAKER: A short print can be a couple of hours
[38:09] SPEAKER: and a long one can be several days.
[38:11] SPEAKER: How long was it before you got OctoPrint to a point,
[38:14] SPEAKER: especially with those early pies,
[38:16] SPEAKER: that it was able to handle a really long, huge project
[38:19] SPEAKER: on one of the bigger printers?
[38:21] SPEAKER: How do you optimize that versus the person
[38:23] SPEAKER: who has a $400 home, somebody who's a professional?
[38:29] SPEAKER: 'Cause I know both professionals and enthusiasts
[38:31] SPEAKER: who use OctoPrint, and it's a very different market
[38:33] SPEAKER: and very different failure--
[38:35] SPEAKER: - Tolerance?
[38:36] SPEAKER: - Yeah, exactly, failure tolerance.
[38:37] SPEAKER: - Yeah, so funnily enough, I rarely had any kind
[38:42] SPEAKER: of stability issues from the get-go.
[38:43] SPEAKER: So it was not me who did the first multiple day print
[38:49] SPEAKER: on OctoPrint, but it was actually someone
[38:50] SPEAKER: that I knew from Google+ who messaged me,
[38:53] SPEAKER: and hey, by the way, this Taj Mahal print here
[38:56] SPEAKER: that went on for 28 hours or something flawlessly,
[38:59] SPEAKER: why are OctoPrints?
[38:59] SPEAKER: Thank you again.
[39:00] SPEAKER: And it was like, okay, cool, apparently this works.
[39:03] SPEAKER: I mean, the thing is, if you figure out
[39:05] SPEAKER: how to reliably communicate with the printer,
[39:07] SPEAKER: whether you do it for one hour or for 200 of them
[39:11] SPEAKER: is not necessarily the problem.
[39:12] SPEAKER: The bigger problem here is instead actually stuff
[39:15] SPEAKER: like will the print actually stick to the bed long enough?
[39:18] SPEAKER: Will the filament tangle?
[39:20] SPEAKER: Will horrible, horrible things happen due to a cat
[39:22] SPEAKER: in the room?
[39:23] SPEAKER: You don't know about all of that.
[39:24] SPEAKER: So the idea behind OctoPrint really in that point
[39:26] SPEAKER: was you cannot, I mean, okay, I have to add a caveat here.
[39:31] SPEAKER: Obviously OctoPrint will tell you when you set it up
[39:33] SPEAKER: for the very first time that you should never leave
[39:35] SPEAKER: your print unattended and that you should make sure
[39:38] SPEAKER: that at any point in time when something goes wrong,
[39:40] SPEAKER: a human can intervene and prevent a fire
[39:43] SPEAKER: or prevent whatever.
[39:46] SPEAKER: Still, I'm leaving my prints unattended myself
[39:48] SPEAKER: because I trust my printer.
[39:49] SPEAKER: I know that my printer is electronically sound
[39:52] SPEAKER: and the only, yeah, the worst thing that can happen
[39:55] SPEAKER: actually just happened this morning when I woke up
[39:57] SPEAKER: to a whole print bed full of maybe five hours
[40:01] SPEAKER: of extruded filament, completely not attached to anything.
[40:05] SPEAKER: So what we call spaghetti.
[40:08] SPEAKER: So spaghetti for breakfast is the stuff
[40:12] SPEAKER: that still can happen.
[40:13] SPEAKER: Although there are actually OctoPrint plugins
[40:15] SPEAKER: that can help you with that through machine learning
[40:17] SPEAKER: and picture analysis from the webcam
[40:20] SPEAKER: and then tell apart a working print from a spaghetti print
[40:23] SPEAKER: and then stop the print job for you.
[40:25] SPEAKER: I did not have anything like that installed.
[40:27] SPEAKER: But yeah, so in general, from my personal experience,
[40:31] SPEAKER: the bigger issue is really with the reliability
[40:33] SPEAKER: of the printer from a mechanical perspective
[40:35] SPEAKER: or from the filament from a mechanical perspective.
[40:38] SPEAKER: And the software so far has rarely been the issue.
[40:41] SPEAKER: I am very happy about that and I knock on wood
[40:45] SPEAKER: that it stays this way, but yeah.
[40:47] SPEAKER: Some issues that we had actually was where,
[40:51] SPEAKER: so most common thing that you install OctoPrint on
[40:53] SPEAKER: is a Raspberry Pi and that is what I was originally
[40:56] SPEAKER: writing it for, but it runs on everything.
[40:58] SPEAKER: The problem is with Raspberry Pis, they are a bit,
[41:03] SPEAKER: how do I say, choosy when it comes to the power supply
[41:06] SPEAKER: that they accept as adequate.
[41:08] SPEAKER: And a lot of people are seeing the micro USB input
[41:11] SPEAKER: or these days they use BC input on the Raspberry Pi
[41:14] SPEAKER: and think, oh, I still have a phone charger
[41:16] SPEAKER: lying around here somewhere and use that to power that thing
[41:19] SPEAKER: with the result that it is browning out left and right
[41:22] SPEAKER: and causing all kind of weird things.
[41:24] SPEAKER: And there was a time when I was constantly getting reports
[41:27] SPEAKER: like OctoPrint suddenly stopped by print at, I don't know,
[41:31] SPEAKER: 5 a.m. in the morning or something like that.
[41:33] SPEAKER: And it was one of these issues where it's absolutely
[41:36] SPEAKER: impossible to reproduce, where it's absolutely impossible
[41:38] SPEAKER: to debug, but at some point I started,
[41:42] SPEAKER: I got the idea that might be a good idea to just monitor
[41:45] SPEAKER: whether the Pi was getting enough power.
[41:47] SPEAKER: And then it turned out that a lot,
[41:50] SPEAKER: maybe even most of these issues that I observed
[41:52] SPEAKER: over the years was down to the Pi browning out,
[41:55] SPEAKER: losing the serial connection to the printer,
[41:57] SPEAKER: losing a network connection, losing whatnot,
[42:01] SPEAKER: losing its marbles and deciding to just send
[42:03] SPEAKER: half the lines over, stuff like that.
[42:05] SPEAKER: And ever since OctoPrint is warning people
[42:08] SPEAKER: about these under voltage situations,
[42:11] SPEAKER: it has caused a number of tickets due to these,
[42:15] SPEAKER: made go down significantly.
[42:17] SPEAKER: On the other hand, it has opened me up to a lot
[42:20] SPEAKER: of angry users who feel like I'm overstepping my boundaries
[42:24] SPEAKER: by telling them that their power supplies are inadequate
[42:27] SPEAKER: and that it is perfectly fine because it says three amps
[42:31] SPEAKER: on it and that cannot be a browning out issue.
[42:33] SPEAKER: And it must be my code that is at fault,
[42:36] SPEAKER: at which point I don't usually point them to the fact
[42:38] SPEAKER: that I'm actually just using the Raspberry Pi's own code
[42:41] SPEAKER: and that if says it is browning out,
[42:43] SPEAKER: then it is browning out regardless
[42:46] SPEAKER: of whether that is correct or not.
[42:47] SPEAKER: And then I cannot help them
[42:48] SPEAKER: and they need to fix the power supply.
[42:50] SPEAKER: But yeah, that is an ongoing battle still.
[42:53] SPEAKER: - Do you have any contact
[42:54] SPEAKER: with the Raspberry Pi Foundation at all?
[42:55] SPEAKER: Have you ever spoken to them about stuff like this?
[42:57] SPEAKER: Like I've bought endless Pis over time
[42:59] SPEAKER: and I'm a little surprised that they don't more aggressively
[43:02] SPEAKER: push that issue on people.
[43:03] SPEAKER: You know, they're very like politely like,
[43:06] SPEAKER: we like our official power supply.
[43:08] SPEAKER: Like you should look for one that does this,
[43:10] SPEAKER: but it's not, they're maybe not as forceful
[43:12] SPEAKER: about hammering that requirement home as they could be.
[43:15] SPEAKER: - I mean, they built in the way at least
[43:17] SPEAKER: that you can detect it.
[43:18] SPEAKER: And also if you run their UI,
[43:20] SPEAKER: if you put that thing not headless,
[43:22] SPEAKER: like I usually booted,
[43:23] SPEAKER: but actually with a monitor and stuff attached,
[43:25] SPEAKER: you will see a little warning thingy pop up
[43:28] SPEAKER: in the upper right corner, I think.
[43:30] SPEAKER: If you have under voltage,
[43:32] SPEAKER: so they are aware of the problem, I think,
[43:34] SPEAKER: but they, yeah, for some reason,
[43:36] SPEAKER: they are not actively pushing it.
[43:38] SPEAKER: I do have contact in there though,
[43:39] SPEAKER: but frankly I figured if I just rebuild the same mechanism
[43:44] SPEAKER: that they already have in the UI and warn people
[43:47] SPEAKER: and constantly annoy people.
[43:50] SPEAKER: So some stuff in OctoPrint is now also disabled
[43:52] SPEAKER: if it is detecting an ongoing under voltage situation,
[43:55] SPEAKER: because we, for example, we saw the problem
[43:57] SPEAKER: that people were installing very CPU intense plugins
[44:01] SPEAKER: during or whether the plugin installation itself
[44:03] SPEAKER: was CPU intense because it had to compile some stuff
[44:06] SPEAKER: or something during an under voltage situation.
[44:08] SPEAKER: And then the whole installation failed
[44:11] SPEAKER: or things were wonky and corrupted after that.
[44:15] SPEAKER: So things like plugin installation are now simply disabled
[44:18] SPEAKER: when you are experiencing an under voltage.
[44:21] SPEAKER: And that has also made this whole error situation
[44:24] SPEAKER: or this whole bug report family completely go away
[44:28] SPEAKER: at the cost of some people, of course, being disgruntled
[44:30] SPEAKER: because again, the whole with the overstay.
[44:32] SPEAKER: It's funny how many people are actually angry
[44:35] SPEAKER: when you tell them that what they have has a problem
[44:37] SPEAKER: because they are completely and utterly convinced
[44:40] SPEAKER: that no, it hasn't and you are wrong.
[44:42] SPEAKER: - Einstein said that the universe and human stupidity
[44:46] SPEAKER: are the only two things that are infinite.
[44:47] SPEAKER: I would say entitlement is another one probably.
[44:49] SPEAKER: - Yeah, absolutely.
[44:50] SPEAKER: And I think he also said he's not entirely sure
[44:52] SPEAKER: about the universe.
[44:54] SPEAKER: - Yes, yeah, of course, of course.
[44:55] SPEAKER: That's the important part of the quote, I think.
[44:57] SPEAKER: I was excited to hear you still get to have time
[44:59] SPEAKER: to print stuff and you get to print stuff.
[45:00] SPEAKER: I'm curious what you use your 3D printers for
[45:02] SPEAKER: at this point in time.
[45:04] SPEAKER: - Mostly functional stuff.
[45:05] SPEAKER: And actually, that was all I ever did.
[45:08] SPEAKER: So I got this in the first place
[45:09] SPEAKER: because I wanted to be able to,
[45:12] SPEAKER: you know, when you walk around your house and you think,
[45:14] SPEAKER: ah, it would be so nice if there was some part
[45:16] SPEAKER: that did this and that so that I can just solve
[45:19] SPEAKER: this one little tiny paper cut that I experience every day.
[45:22] SPEAKER: So I started doing that.
[45:24] SPEAKER: For example, a couple of years ago,
[45:26] SPEAKER: and that's still going strong,
[45:27] SPEAKER: I designed a splash guard for the kitchen sink
[45:29] SPEAKER: because every time that I was using it,
[45:32] SPEAKER: it was splashing to the left over the counter
[45:34] SPEAKER: and that was annoying me.
[45:36] SPEAKER: And so I just designed something with some acrylic sheet
[45:39] SPEAKER: and some hinges and some printed parts
[45:41] SPEAKER: that I can now pull out and then everything to the left
[45:44] SPEAKER: is protected from water splash.
[45:46] SPEAKER: It's silly, but it helped me.
[45:48] SPEAKER: And also the kitchen sink,
[45:49] SPEAKER: the faucet was a bit stupid to handle.
[45:52] SPEAKER: And so I built a little, designed a little extension
[45:55] SPEAKER: for that was something like two hours of a print
[45:57] SPEAKER: has been going strong now for five years
[45:59] SPEAKER: and is something that I use every day
[46:01] SPEAKER: and don't even think about anymore
[46:03] SPEAKER: and has improved my life so much.
[46:06] SPEAKER: And recently I bought myself an e-bike
[46:08] SPEAKER: and also a trailer for it.
[46:09] SPEAKER: So because I'm trying to replace my car
[46:12] SPEAKER: for all these short trips that you just buy yourself
[46:15] SPEAKER: and maybe carrying some groceries or something like that.
[46:18] SPEAKER: So, and for that, I also bought two heavy duty D-locks
[46:23] SPEAKER: and then I found myself in the weird position
[46:25] SPEAKER: that I now had these locks,
[46:26] SPEAKER: but no way to mount them to the bike.
[46:27] SPEAKER: So I designed a mount for that.
[46:30] SPEAKER: And that went over several iterations
[46:32] SPEAKER: until it was finally doing what I wanted it to,
[46:34] SPEAKER: but now it's working beautifully
[46:36] SPEAKER: and is something that I'm very, very proud of.
[46:39] SPEAKER: - There's something really satisfying
[46:41] SPEAKER: about that iterative loop.
[46:42] SPEAKER: It's the thing that I like about 3D printing
[46:43] SPEAKER: and just computer, laser cutting, 3D printing,
[46:45] SPEAKER: whatever it is you're doing.
[46:47] SPEAKER: - Absolutely, yeah.
[46:47] SPEAKER: - Where you build the first version, you're like,
[46:49] SPEAKER: "Oh, this is pretty good, but it's not quite right."
[46:51] SPEAKER: And then you're like, "I think I can do it better."
[46:52] SPEAKER: And you go back and you iterate it three
[46:54] SPEAKER: or four or five times and then all of a sudden
[46:56] SPEAKER: you have something that's exactly,
[46:57] SPEAKER: exactly what you were hoping it would be.
[46:59] SPEAKER: - Yeah, and that dispute.
[47:00] SPEAKER: And it also makes you think about the problem
[47:02] SPEAKER: from various angles.
[47:03] SPEAKER: Because for example, for printing,
[47:04] SPEAKER: you really have to think about how can I print that?
[47:07] SPEAKER: Because if you use something that uses FDM,
[47:10] SPEAKER: you have the problem that you kind of have
[47:11] SPEAKER: to fight gravity here and there.
[47:13] SPEAKER: Because if you're printing something
[47:14] SPEAKER: that imagine is shaped like a T,
[47:17] SPEAKER: if you're trying to print these horizontal bars
[47:20] SPEAKER: up in the end up there,
[47:21] SPEAKER: and you're simply basically splurging the molten plastic
[47:24] SPEAKER: out of a nozzle up there, it will just drop down.
[47:27] SPEAKER: There will be nothing stopping it from falling down.
[47:29] SPEAKER: So in 3D printing, you always have to think about stuff
[47:31] SPEAKER: like support placement, support structure placement.
[47:34] SPEAKER: Then you also have to think about for mechanical parts,
[47:36] SPEAKER: for example, for the bike lock,
[47:37] SPEAKER: I explicitly modeled it on the bike lock mount.
[47:40] SPEAKER: I modeled it so that all the weight would be held
[47:44] SPEAKER: not by the layer adhesion,
[47:46] SPEAKER: so not by the parts where the layers are stuck together,
[47:49] SPEAKER: but actually by the lines that make up,
[47:51] SPEAKER: so the loops that make up the individual layers
[47:53] SPEAKER: so that this would be really, really strong
[47:55] SPEAKER: in the direction of force.
[47:58] SPEAKER: And that of course then made,
[48:00] SPEAKER: cost me a few head scratches on how to design that thing
[48:03] SPEAKER: so that it was still printable
[48:05] SPEAKER: without a ton of support and things like that.
[48:08] SPEAKER: And I really like how this makes you,
[48:10] SPEAKER: I don't get to print as much as I originally planned to
[48:14] SPEAKER: when I bought the printer in the first place,
[48:17] SPEAKER: because I'm more busy with the software side of things,
[48:19] SPEAKER: but here and there, whenever something just annoys me
[48:23] SPEAKER: or I need to solve something,
[48:25] SPEAKER: then I sit down and whip up FreeCAD
[48:28] SPEAKER: and design it in that and go through some iterations.
[48:32] SPEAKER: And that is also something that I really, really enjoy.
[48:35] SPEAKER: Also something that I assume we'll have to do
[48:38] SPEAKER: is I need to program a bunch of smart plugs
[48:42] SPEAKER: and I need a programming jig for them
[48:43] SPEAKER: so that I can easily attach the serial interface for that.
[48:46] SPEAKER: And that is something where I was looking around
[48:48] SPEAKER: for something that was already done to do that,
[48:50] SPEAKER: but I couldn't find it.
[48:52] SPEAKER: And then I found a print, but that didn't work as well.
[48:55] SPEAKER: And then I figured, well,
[48:56] SPEAKER: maybe I can laser cut this just from sheet stock
[48:59] SPEAKER: rather easily.
[49:00] SPEAKER: So I just have to sit down, cut it out,
[49:02] SPEAKER: and then I have a laser cutter sitting right behind me.
[49:04] SPEAKER: So, which by the way also runs OctoPrint.
[49:08] SPEAKER: - That's a good opportunity to talk about this.
[49:09] SPEAKER: OctoPrint has kind of gone from this thing
[49:11] SPEAKER: that was for 3D printers to like,
[49:12] SPEAKER: it seems like everything that runs GD
[49:13] SPEAKER: or many things that run G code, is that,
[49:15] SPEAKER: like where does OctoPrint end, I guess, is a-
[49:18] SPEAKER: - In principle, OctoPrint is still
[49:20] SPEAKER: the snappy web interface for your 3D printer.
[49:22] SPEAKER: So it is very much too focused on 3D printers.
[49:25] SPEAKER: But with the plug-in system, it's of course easy
[49:28] SPEAKER: to just swap out certain parts of OctoPrint,
[49:31] SPEAKER: suppress others, add others.
[49:33] SPEAKER: So in case of the laser printer
[49:36] SPEAKER: that I have in my office here,
[49:38] SPEAKER: that is actually more like an engraver,
[49:40] SPEAKER: but it is enough to cut some plywood and stuff.
[49:42] SPEAKER: And that is produced by a company in Munich
[49:45] SPEAKER: who had this idea for a cheap and affordable laser cutter,
[49:50] SPEAKER: but lacked the software.
[49:51] SPEAKER: And we met at a fair and got to talk at a trade show.
[49:55] SPEAKER: I should maybe rather say.
[49:57] SPEAKER: And we got to talk and yeah,
[49:59] SPEAKER: then they simply took OctoPrint
[50:00] SPEAKER: and adapted it to their needs and that worked well.
[50:04] SPEAKER: So it's kind of fun that whenever I use this laser cutter,
[50:07] SPEAKER: I now also use my software,
[50:09] SPEAKER: even though it doesn't look even remotely
[50:11] SPEAKER: like my software anymore.
[50:13] SPEAKER: So yeah, kind of fun.
[50:14] SPEAKER: And I also know that some people
[50:16] SPEAKER: have also used it for CNC routers.
[50:17] SPEAKER: And I think there is at least one pick and place project
[50:22] SPEAKER: out there that uses it then for, yeah,
[50:25] SPEAKER: pick and place population of PCBs.
[50:29] SPEAKER: But yeah, in general, I mean, at its core,
[50:32] SPEAKER: OctoPrint is something that can stream G code
[50:35] SPEAKER: over a serial connection to something
[50:37] SPEAKER: and then give you feedback about this via a web socket,
[50:40] SPEAKER: via a web interface or an API, whatever you want.
[50:45] SPEAKER: So it can be adapted to a lot of stuff,
[50:47] SPEAKER: though my focus still is on 3D printers.
[50:50] SPEAKER: - So where does OctoPrint fit in the 3D printing stack
[50:52] SPEAKER: for people who haven't spent time 3D printing,
[50:54] SPEAKER: maybe don't understand the intricacies of the process?
[50:57] SPEAKER: - Usually if you want to print something,
[50:58] SPEAKER: and let's assume you already have the 3D object
[51:02] SPEAKER: that you want to print and you do not have to figure out
[51:03] SPEAKER: how to design that first.
[51:04] SPEAKER: So you download it from 3Dworks or from printables.com
[51:07] SPEAKER: or something like that.
[51:08] SPEAKER: And now you have this STL or 3MF file sitting there.
[51:11] SPEAKER: And the first thing that you need to do now is,
[51:13] SPEAKER: what you have there is basically a mesh of triangles
[51:16] SPEAKER: that make up a three dimensional object.
[51:18] SPEAKER: That is not something that the printer can do anything about
[51:21] SPEAKER: or do anything with.
[51:22] SPEAKER: So what you first need to do is run it through a slicer.
[51:25] SPEAKER: And the slicer is basically a piece of software
[51:27] SPEAKER: that takes this 3D mesh and then slices it up
[51:31] SPEAKER: into individual layers based on a lot of parameters
[51:34] SPEAKER: that you can configure.
[51:35] SPEAKER: And then from those layers also generates
[51:38] SPEAKER: the individual commands for the printer to run through.
[51:43] SPEAKER: So imagine a 3D printer and an FDM 3D printer,
[51:45] SPEAKER: I should add as basically a hot glue gun
[51:49] SPEAKER: mounted to a 3D gentry.
[51:50] SPEAKER: So you can move it in X and Y direction
[51:52] SPEAKER: and you can also move it up into Z.
[51:55] SPEAKER: And what the slicer now does is pretty much create the path
[52:01] SPEAKER: that this glue gun is now supposed to take
[52:04] SPEAKER: and also include the commands at which point
[52:07] SPEAKER: it is supposed to extrude how much of the glue
[52:09] SPEAKER: or in this case molten plastic into the spot
[52:11] SPEAKER: where it is currently at.
[52:13] SPEAKER: And at the end then something called the g-code file
[52:17] SPEAKER: drops out and this contains all the information
[52:20] SPEAKER: like all the layer commands and all the movement commands
[52:23] SPEAKER: and also stuff like what temperature to heat up the bed
[52:26] SPEAKER: and the nozzle and maybe also the chamber to at what point,
[52:29] SPEAKER: when to start, what fan, at what speeds, stuff like that.
[52:33] SPEAKER: And now you also, you need to get this somehow
[52:36] SPEAKER: to the printer.
[52:36] SPEAKER: And these days the easiest way to do that
[52:38] SPEAKER: is to just throw it on an SD card or on a USB stick
[52:41] SPEAKER: and go to your printer and put it in
[52:44] SPEAKER: and then on the printer you select some option in the menu
[52:48] SPEAKER: and tell it to print this file and then it will do that.
[52:51] SPEAKER: And that works fine.
[52:52] SPEAKER: This is however something that 10 years ago
[52:55] SPEAKER: was something that no printer could do.
[52:58] SPEAKER: It also has the downside
[52:59] SPEAKER: that it completely lacks a feedback loop.
[53:01] SPEAKER: So the thing is you now have your printer sitting there
[53:04] SPEAKER: maybe working for days on end
[53:06] SPEAKER: and every time that you have to want to figure out
[53:08] SPEAKER: if it is still doing what it is supposed to be doing
[53:10] SPEAKER: and how long it will still take,
[53:13] SPEAKER: you have to physically go next to your printer
[53:16] SPEAKER: and look at it with your own eyes.
[53:18] SPEAKER: And that is annoying with really long print jobs.
[53:22] SPEAKER: So Octoprint comes in is instead of you throwing
[53:25] SPEAKER: this piece of G code that fell out of your slicer
[53:27] SPEAKER: onto an SD card or a USB stick
[53:29] SPEAKER: and then physically walking it over your printer,
[53:32] SPEAKER: you instead upload it to a thing
[53:34] SPEAKER: that is connected to your printer
[53:35] SPEAKER: and talks to it via a serial interface.
[53:37] SPEAKER: And that is Octoprint.
[53:38] SPEAKER: And then in Octoprint's web interface,
[53:41] SPEAKER: so you go into your browser,
[53:42] SPEAKER: you can access that from the same PC as your slicer,
[53:46] SPEAKER: for example, go into your browser
[53:48] SPEAKER: and then you can select this file for printing
[53:50] SPEAKER: and fire it off.
[53:51] SPEAKER: And then you not only get progress information
[53:53] SPEAKER: and temperature control, but also webcam overview.
[53:55] SPEAKER: And you can even install plugins
[53:57] SPEAKER: that send you notifications on your phone
[53:59] SPEAKER: when it reaches certain percentages
[54:01] SPEAKER: or when it's done or it warns you about errors or stuff.
[54:05] SPEAKER: With the current generation of slicers,
[54:07] SPEAKER: so the most common ones, Cura, Prusa Slicer, Super Slicer,
[54:11] SPEAKER: they all even have either natively built in
[54:15] SPEAKER: or accessible via a plugin, Octoprint integration.
[54:18] SPEAKER: So instead of you having to now locate the file
[54:21] SPEAKER: that your slicer produced on your disc
[54:23] SPEAKER: and then uploading it through the web interface
[54:25] SPEAKER: in Octoprint, you tell your slicer,
[54:27] SPEAKER: "By the way, my printer is accessible via Octoprint
[54:30] SPEAKER: on this and this IP with this and this API key."
[54:32] SPEAKER: And then the slicer, after slicing the file,
[54:35] SPEAKER: will just send it to Octoprint, maybe even power up
[54:38] SPEAKER: the printer if needed and yeah, do all of that for you
[54:42] SPEAKER: and also show you the progress then in your slicer.
[54:45] SPEAKER: So that is kinda neat.
[54:47] SPEAKER: - The thing that I didn't understand
[54:48] SPEAKER: when I started 3D printing is that if you hand your printer
[54:50] SPEAKER: a piece of G-code, it's just gonna run through the steps
[54:53] SPEAKER: of that G-code no matter what, whether it's working or not.
[54:57] SPEAKER: - Exactly, there is no,
[54:58] SPEAKER: so we don't have a closed loop system there or something.
[55:01] SPEAKER: If you run your printer through a piece of G-code
[55:03] SPEAKER: and at some point just hold the extruder or the head,
[55:07] SPEAKER: the print head tight in your fist,
[55:09] SPEAKER: it will make some horrible grinding noises
[55:11] SPEAKER: but it will use its stepper position
[55:13] SPEAKER: and if you then let loose again,
[55:15] SPEAKER: it will simply try to continue on its merry way.
[55:18] SPEAKER: The problem is it will completely be offset
[55:20] SPEAKER: and horrible things happen then
[55:22] SPEAKER: and it ruins the whole print.
[55:24] SPEAKER: And this is because the 3D printers as we know them today,
[55:28] SPEAKER: they just use run-of-the-mill NEMA 17 stepper motors.
[55:33] SPEAKER: So you can tell them something like go to this position
[55:36] SPEAKER: but you cannot say at what position are you,
[55:39] SPEAKER: which means the firmware can only pray and hope
[55:42] SPEAKER: after firing of a movement command
[55:43] SPEAKER: and it will actually be executed.
[55:46] SPEAKER: With the heating, we have a bit more control
[55:49] SPEAKER: but still not much because again,
[55:50] SPEAKER: thermal runaway can be a thing and such.
[55:53] SPEAKER: And yeah, it boils down to a lot of stuff can go wrong
[55:56] SPEAKER: at any given point.
[55:57] SPEAKER: So you really do not want to just leave it running for days
[56:01] SPEAKER: and then come back to what I woke up to this morning
[56:04] SPEAKER: but way, way worse.
[56:05] SPEAKER: Yeah.
[56:06] SPEAKER: - I think the worst thing we ever did was make,
[56:09] SPEAKER: it's amazing how much plastic it can extrude
[56:11] SPEAKER: when it's spaghettifying.
[56:12] SPEAKER: - Yeah.
[56:13] SPEAKER: - Because you'll just get an enormous snarl of like a ball
[56:17] SPEAKER: three feet around a plastic
[56:18] SPEAKER: that's going for hours and hours and hours.
[56:20] SPEAKER: - I had a bit of a problem getting all of the garbage
[56:22] SPEAKER: that was generated by this mishap this morning
[56:24] SPEAKER: into my garbage bin.
[56:25] SPEAKER: So, (laughs)
[56:28] SPEAKER: and it wasn't that much. - The printers are faster now.
[56:30] SPEAKER: - But yeah, I mean, if you squeeze something through an 0.4
[56:34] SPEAKER: or in my case right now, an 0.6 nozzle,
[56:37] SPEAKER: it gets really, really thin.
[56:38] SPEAKER: So even small amounts of plastic that you squeeze
[56:41] SPEAKER: through such a nozzle can become very, very long.
[56:45] SPEAKER: And yeah, so it always looks kind of funny.
[56:49] SPEAKER: And it is a bit frustrating if it was something
[56:51] SPEAKER: that you were hoping would be done by the morning
[56:53] SPEAKER: and then it is only angel hair or spaghetti or whatever,
[56:56] SPEAKER: but it's okay.
[56:58] SPEAKER: We live and learn.
[56:59] SPEAKER: This is the process, right?
[57:01] SPEAKER: - So if resources were not a concern,
[57:02] SPEAKER: if you had unlimited time, money, contributors, everything,
[57:05] SPEAKER: is there, what's your fantasy feature for OctoPrint?
[57:07] SPEAKER: Is there like one thing you would just love to get in there
[57:09] SPEAKER: if you had the capability to do so?
[57:12] SPEAKER: - There's actually one thing that I've been sitting on now
[57:15] SPEAKER: for years, which is rebuilding the comm layer. (laughs)
[57:20] SPEAKER: Because right now that comm you occasionally,
[57:21] SPEAKER: that is just like naturally organically grown thing
[57:25] SPEAKER: that tries to talk to every printer under the sun.
[57:28] SPEAKER: And I have a refactor going on,
[57:30] SPEAKER: but every time that I sit down and work on it,
[57:32] SPEAKER: something happens.
[57:34] SPEAKER: So the first time that I actually started working on that,
[57:38] SPEAKER: the whole funding situation happened where I lost this job
[57:40] SPEAKER: with the 3D printing company stuff
[57:42] SPEAKER: and had to go look into the crowdfunding.
[57:44] SPEAKER: So that put this on the back burner.
[57:46] SPEAKER: The second time that I really had time for that,
[57:48] SPEAKER: let's just say a 16 year relationship broke apart.
[57:52] SPEAKER: And so that was a bit of fun.
[57:54] SPEAKER: Then the next time I had the time to actually work on that,
[57:58] SPEAKER: the pandemic hit.
[57:59] SPEAKER: And yeah, so this thing is really under a bad star,
[58:03] SPEAKER: I have the feeling.
[58:04] SPEAKER: But this would be the first thing that I would tackle.
[58:06] SPEAKER: Then another thing that I immediately would look into
[58:09] SPEAKER: is I'm still using JavaScript libraries
[58:12] SPEAKER: and tooling from 2012.
[58:15] SPEAKER: You can imagine that this is a bit of a problem
[58:18] SPEAKER: these time and ages.
[58:20] SPEAKER: So we are planning on,
[58:22] SPEAKER: and with we, I mean the regular contributors and I,
[58:25] SPEAKER: we are planning on replacing Octoprint's UI
[58:27] SPEAKER: somewhere down the road.
[58:28] SPEAKER: The challenge here is the plugin situation
[58:30] SPEAKER: because the plugins use the same UI system.
[58:33] SPEAKER: So yeah, how to do this without nuking a whole ecosystem,
[58:37] SPEAKER: right?
[58:38] SPEAKER: And also just finding the time to sit down
[58:39] SPEAKER: and finally figure out what to do,
[58:41] SPEAKER: how, when, where, and why.
[58:43] SPEAKER: Because as I said,
[58:44] SPEAKER: every time that I think I have time for stuff like that,
[58:47] SPEAKER: something horrible happens.
[58:49] SPEAKER: - Yeah, I'm glad you mentioned the plugin system
[58:51] SPEAKER: 'cause I think the plugin system is a real strength
[58:53] SPEAKER: of Octoprint.
[58:54] SPEAKER: You know, the fact that you can apply machine learning
[58:58] SPEAKER: to tell if the printer's gone bad from a webcam feed is like,
[59:02] SPEAKER: if I told 2010 or 2011 me that that was a feature
[59:04] SPEAKER: of 3D printers 10 years down the road,
[59:07] SPEAKER: my mind would be blown.
[59:08] SPEAKER: Do you have plugins that you find
[59:10] SPEAKER: that feel like magic to you or?
[59:12] SPEAKER: - Octolabs.
[59:13] SPEAKER: So Octoprint has this natively built-in time lapse feature,
[59:17] SPEAKER: which I originally really just added for debugging reasons.
[59:20] SPEAKER: And/or maybe to show off a bit how a print actually works.
[59:25] SPEAKER: And then Brad took this to 11 by creating Octolabs.
[59:30] SPEAKER: And that was quite a funny experience
[59:32] SPEAKER: because suddenly there was this dude
[59:34] SPEAKER: on the Octoprint issue tracker
[59:36] SPEAKER: who was asking for weird features to be added left and right
[59:39] SPEAKER: to pause stuff and interact with the com layer
[59:41] SPEAKER: in ways that I never anticipated,
[59:43] SPEAKER: but he seemed pleasant enough to work with and ask nicely.
[59:46] SPEAKER: And so we worked together.
[59:47] SPEAKER: And then I learned why he was asking for all of that stuff.
[59:51] SPEAKER: And that was, yeah, basically developing Octolabs.
[59:53] SPEAKER: And Octolabs is this time lapse for Octoprint on steroids
[59:57] SPEAKER: where you don't just have, I don't know,
[1:00:00] SPEAKER: a picture taken every two seconds
[1:00:01] SPEAKER: and then you see the printer go really fast
[1:00:04] SPEAKER: all over the screen and everything wobbles.
[1:00:06] SPEAKER: And with a bed slinger,
[1:00:07] SPEAKER: so a printer that moves the bed back and forth
[1:00:09] SPEAKER: for the Y axis, you pretty much see nothing
[1:00:11] SPEAKER: because everything just is constantly in motion.
[1:00:14] SPEAKER: And he built this plugin that now can at certain points
[1:00:17] SPEAKER: for example, on layer change or at certain points in time,
[1:00:20] SPEAKER: just move the printed out of the way, take a picture,
[1:00:22] SPEAKER: then move the print head back.
[1:00:23] SPEAKER: And she also has modes where it looks like the print head
[1:00:26] SPEAKER: is just constantly going in circles over the print
[1:00:29] SPEAKER: while it grows up from the bed.
[1:00:31] SPEAKER: And yeah, he built all of that as an Octoprint plugin.
[1:00:34] SPEAKER: And the first time that I saw a time lapse
[1:00:37] SPEAKER: generated with Octolabs, my mind was blown
[1:00:40] SPEAKER: because I had no idea that this was something
[1:00:41] SPEAKER: that was possible with Octoprint.
[1:00:45] SPEAKER: And yeah, that is also usually,
[1:00:48] SPEAKER: so if you see some print job time lapse
[1:00:50] SPEAKER: where the print job is just growing out of the bed
[1:00:53] SPEAKER: and the nozzle is doing fancy movements above it
[1:00:56] SPEAKER: and everything looks just like it is synced up and stuff,
[1:00:59] SPEAKER: that is usually Octolabs and that has also boosted
[1:01:02] SPEAKER: Octoprint adoption by a ton single-handedly.
[1:01:05] SPEAKER: - The initial time lapse feature
[1:01:07] SPEAKER: was why I installed Octoprint at the beginning
[1:01:08] SPEAKER: 'cause it made the production process
[1:01:10] SPEAKER: for our time lapses a lot easier.
[1:01:12] SPEAKER: But the stuff that you can do with Octolabs
[1:01:14] SPEAKER: is unbelievable, it's so cool.
[1:01:16] SPEAKER: - It's amazing.
[1:01:16] SPEAKER: He even allows you to test some G-photo integration
[1:01:19] SPEAKER: so you can attach a mirrorless or a DSLR
[1:01:23] SPEAKER: or something like that to take the pictures
[1:01:25] SPEAKER: instead of your run of the mill webcam
[1:01:26] SPEAKER: and it's just amazing what this spits out.
[1:01:30] SPEAKER: And then he, a couple of years later,
[1:01:31] SPEAKER: he actually came up with ArcWelder.
[1:01:33] SPEAKER: So the thing is with most printers
[1:01:35] SPEAKER: or most printer firmware and slicers,
[1:01:37] SPEAKER: so slicers usually when you have some model
[1:01:39] SPEAKER: that is like circle shaped, it just say a cylinder,
[1:01:43] SPEAKER: you want to print a cylinder.
[1:01:44] SPEAKER: Your average slicer will now go there
[1:01:47] SPEAKER: and slice this apart into individual layers
[1:01:49] SPEAKER: and then each circle will not be turned
[1:01:52] SPEAKER: into a circle command for the printer
[1:01:53] SPEAKER: but actually segmented into individual lines.
[1:01:56] SPEAKER: And the shorter those line segments,
[1:01:58] SPEAKER: the faster stuff needs to be sent
[1:02:00] SPEAKER: over the serial interface now to the printer
[1:02:02] SPEAKER: in order to keep it fed with commands
[1:02:04] SPEAKER: so that it doesn't start to stutter.
[1:02:05] SPEAKER: And this is actually a problem that we see a lot
[1:02:08] SPEAKER: with very fast prints and very curvy prints
[1:02:11] SPEAKER: streamed over OctoPrint to firmware
[1:02:14] SPEAKER: with very small command buffers,
[1:02:16] SPEAKER: which is a very interesting combo,
[1:02:18] SPEAKER: but that leads to stuttering print jobs.
[1:02:21] SPEAKER: And maybe there's also some performance bottlenecks
[1:02:23] SPEAKER: here and there still in OctoPrint's code
[1:02:24] SPEAKER: that I'm trying to iron out whenever I find them
[1:02:27] SPEAKER: but there is a logical ceiling caused by the serial board rate
[1:02:31] SPEAKER: and bandwidth available and the thing
[1:02:33] SPEAKER: that every line has to be sent, acknowledged
[1:02:35] SPEAKER: and then the next sent and acknowledged
[1:02:37] SPEAKER: and also checksum and whatnot.
[1:02:39] SPEAKER: The thing is though that most firmware out there
[1:02:40] SPEAKER: actually supports circle commands or rather arc commands.
[1:02:43] SPEAKER: So there are codes G2 and G3 to tell the printer
[1:02:48] SPEAKER: or rather the print head to move in a circle
[1:02:50] SPEAKER: with this and this center point
[1:02:53] SPEAKER: and this radius from this start angle
[1:02:56] SPEAKER: to this end angle or something like that.
[1:02:58] SPEAKER: I think the actual coordination is a bit different
[1:03:01] SPEAKER: but you get the idea.
[1:03:03] SPEAKER: So you can basically just create arcs,
[1:03:05] SPEAKER: counterclockwise and clockwise.
[1:03:06] SPEAKER: But the slicers do not output code that utilizes this
[1:03:11] SPEAKER: because not all firmware does it.
[1:03:12] SPEAKER: And we heard there is a lot of fragmentation out there.
[1:03:15] SPEAKER: So you can, a slicer has the same problem in that regard.
[1:03:17] SPEAKER: Like I do with OctoPrint,
[1:03:19] SPEAKER: I have to interface with the printers.
[1:03:21] SPEAKER: They have to generate code that the printers can understand.
[1:03:23] SPEAKER: So better say that sorry and leave out the arc commands.
[1:03:27] SPEAKER: And Brad now came and with ArcWelder created a tool
[1:03:31] SPEAKER: that will analyze the G code and detect things
[1:03:35] SPEAKER: that could be arcs and rewrite it so it contains arcs.
[1:03:39] SPEAKER: And that can reduce the whole G code by 50 or 60%
[1:03:43] SPEAKER: and obviously also increase the speed
[1:03:44] SPEAKER: with which it can be transmitted by a lot.
[1:03:46] SPEAKER: And that is stuff this guy just comes up with
[1:03:50] SPEAKER: and whips out of his sleeve.
[1:03:53] SPEAKER: And that is really, really astonishing.
[1:03:55] SPEAKER: - It seems like the fragmented nature
[1:03:57] SPEAKER: is kind of a pro and a con of the 3D printing ecosystem.
[1:04:00] SPEAKER: Do you think, is there any movement at all
[1:04:02] SPEAKER: to unify firmware API for the thing that OctoPrint does?
[1:04:07] SPEAKER: - So funnily enough, a couple of years ago, I tried that.
[1:04:10] SPEAKER: I tried to just sit down and write a spec for G code.
[1:04:14] SPEAKER: And people from the CNC world will now say
[1:04:17] SPEAKER: there is already a spec for G code,
[1:04:19] SPEAKER: NIST numbers, something or other, yeah.
[1:04:21] SPEAKER: The problem is that 3D printers use something
[1:04:24] SPEAKER: they also call G code, but which is in fact a file format
[1:04:28] SPEAKER: and a serial interface protocol thingy,
[1:04:30] SPEAKER: whereas the NIST specification for CNC machining
[1:04:33] SPEAKER: is only a file format with a very limited command set.
[1:04:37] SPEAKER: And when 3D printers were created
[1:04:39] SPEAKER: in the way that we know them now,
[1:04:40] SPEAKER: people took this CNC stuff and adapted it
[1:04:43] SPEAKER: and hacked it together and just made it somehow work,
[1:04:46] SPEAKER: but it grew organically and in various, various shapes
[1:04:49] SPEAKER: and forms, depending on who was working on what.
[1:04:54] SPEAKER: And a couple of years back, I decided, okay,
[1:04:55] SPEAKER: enough is enough, this is just an absolute nightmare.
[1:04:58] SPEAKER: I need to try to somehow generalize this,
[1:05:01] SPEAKER: at least find a common ground, document it,
[1:05:04] SPEAKER: and make people agree that this is how we are going
[1:05:08] SPEAKER: to do things from now on.
[1:05:09] SPEAKER: And herding cats would have been easier.
[1:05:13] SPEAKER: I got together some people from the wrap-wrap
[1:05:16] SPEAKER: and from the 3D printing community, and it just,
[1:05:20] SPEAKER: let's just say it devolved into name calling here and there,
[1:05:23] SPEAKER: and that was where I decided, okay,
[1:05:25] SPEAKER: this is not going to work that way.
[1:05:27] SPEAKER: So my current idea is just to,
[1:05:30] SPEAKER: as part also of the documentation effort,
[1:05:31] SPEAKER: to just document what OctoPrint supports
[1:05:33] SPEAKER: and then have other people just adapt to that
[1:05:36] SPEAKER: because anything else.
[1:05:36] SPEAKER: At least what I achieved is that I am in the loop
[1:05:39] SPEAKER: on some firmware developments now going on
[1:05:41] SPEAKER: after one too many cases with, yeah,
[1:05:44] SPEAKER: someone unintentionally broke something in a pull request,
[1:05:47] SPEAKER: and then suddenly a whole bunch of printers
[1:05:50] SPEAKER: didn't work with OctoPrint anymore,
[1:05:52] SPEAKER: and I had to field your bug reports for that.
[1:05:54] SPEAKER: So at least that got this communication going, kind of,
[1:05:57] SPEAKER: but yeah.
[1:06:00] SPEAKER: Let's just say there's a lot of ego in this whole community.
[1:06:03] SPEAKER: (laughing)
[1:06:04] SPEAKER: - Fair.
[1:06:05] SPEAKER: We've got just a couple of short questions
[1:06:07] SPEAKER: from listeners here.
[1:06:08] SPEAKER: - Yeah.
[1:06:09] SPEAKER: - One is, what do you think of the evolution
[1:06:11] SPEAKER: of AI-based failure detection and correction?
[1:06:14] SPEAKER: Do you think that that is something,
[1:06:16] SPEAKER: A, is that in a place that it needs to be now,
[1:06:18] SPEAKER: or is there a lot more work to do there?
[1:06:19] SPEAKER: And B, is that something that you think
[1:06:21] SPEAKER: will make 3D printing more accessible
[1:06:22] SPEAKER: to people who are less technical?
[1:06:24] SPEAKER: - I personally really enjoy what I'm seeing there.
[1:06:27] SPEAKER: I have to admit that I so far have not used it myself.
[1:06:29] SPEAKER: I maybe should install Obico later
[1:06:32] SPEAKER: to avoid another mishap like last night once
[1:06:36] SPEAKER: on the coming morning, but from what I can see,
[1:06:38] SPEAKER: they have already come a long, long way.
[1:06:41] SPEAKER: And what I think that the next step should actually be
[1:06:43] SPEAKER: in that regard is less AI
[1:06:44] SPEAKER: and more focused maybe on the mechanical parts,
[1:06:46] SPEAKER: because currently we're trying
[1:06:48] SPEAKER: to solve everything in software,
[1:06:49] SPEAKER: and I also noticed this a lot
[1:06:51] SPEAKER: in the feature requests for OctoPrint where people like,
[1:06:53] SPEAKER: oh, OctoPrint should tell me if the print bed is not clear,
[1:06:55] SPEAKER: or OctoPrint should do this and that
[1:06:57] SPEAKER: and work around firmware limitations and some such.
[1:07:00] SPEAKER: And I think not everything should be,
[1:07:03] SPEAKER: or we should, as a community,
[1:07:04] SPEAKER: we should not try to beat every problem
[1:07:07] SPEAKER: into submission with software,
[1:07:09] SPEAKER: because sometimes the easier
[1:07:10] SPEAKER: and also the cleaner solution really is
[1:07:13] SPEAKER: to solve it in hardware.
[1:07:14] SPEAKER: And for things like, for example, layer skipping,
[1:07:18] SPEAKER: where at some point the print head got stuck somewhere,
[1:07:21] SPEAKER: for example, on the print object itself,
[1:07:23] SPEAKER: and now you have an offset
[1:07:24] SPEAKER: on every consecutive layer due to that,
[1:07:26] SPEAKER: things like this could be really easily solved
[1:07:29] SPEAKER: with a closed loop system on the stepper
[1:07:31] SPEAKER: where we would actually know
[1:07:32] SPEAKER: where they are at the given moment
[1:07:34] SPEAKER: and not where we hopefully send them to,
[1:07:36] SPEAKER: but where they actually are.
[1:07:37] SPEAKER: And these are solved problems.
[1:07:39] SPEAKER: It's just expensive technology or not that expensive,
[1:07:42] SPEAKER: but way more expensive than 150 euros at the hardware store
[1:07:46] SPEAKER: that we are currently,
[1:07:47] SPEAKER: or that a lot of people are currently willing
[1:07:49] SPEAKER: to pay for a printer.
[1:07:52] SPEAKER: And yeah, I think that would be one big step to take.
[1:07:56] SPEAKER: Of course, 3D printing for our masses
[1:07:58] SPEAKER: is always something where I'm a bit unsure
[1:08:01] SPEAKER: whether that is the right approach,
[1:08:02] SPEAKER: because a 3D printer is still something very technical,
[1:08:07] SPEAKER: and I'm not sure that we want to dump them down enough
[1:08:12] SPEAKER: that they can be something that everyone can easily operate,
[1:08:17] SPEAKER: because at that point,
[1:08:18] SPEAKER: usually they either become proprietary,
[1:08:21] SPEAKER: which we do not want because we've been there,
[1:08:24] SPEAKER: and the result were printers that cost millions,
[1:08:27] SPEAKER: or they become limited.
[1:08:30] SPEAKER: And we probably also do not want to do that
[1:08:32] SPEAKER: because then we will have less than we have now.
[1:08:35] SPEAKER: So personally, I think a 3D printer is a tool
[1:08:39] SPEAKER: like a CNC machine is, like, I don't know,
[1:08:42] SPEAKER: like a power drill is, like a saw is,
[1:08:46] SPEAKER: like my laser cutter is.
[1:08:47] SPEAKER: And for a tool, you need to learn some stuff first.
[1:08:50] SPEAKER: It is not something that you simply put into your bedroom
[1:08:53] SPEAKER: and then have your toddler use or something like that,
[1:08:58] SPEAKER: but it is a tool, it is a machining tool.
[1:09:00] SPEAKER: It is a very approachable one, in my opinion,
[1:09:04] SPEAKER: compared to all the other stuff,
[1:09:05] SPEAKER: also because the most that it produces is fumes and noise,
[1:09:09] SPEAKER: and not a lot of chips and stuff flying around and no powder.
[1:09:14] SPEAKER: Of course, if you're working with resin printers,
[1:09:17] SPEAKER: the situation is a bit different
[1:09:19] SPEAKER: because then you have a lot of very, very toxic chemicals
[1:09:21] SPEAKER: that you are now suddenly handling.
[1:09:23] SPEAKER: But the FTM printer side is very, very easy
[1:09:26] SPEAKER: and approachable, I think, but it is still a tool.
[1:09:29] SPEAKER: And I don't think that our expectation should be
[1:09:32] SPEAKER: that this should turn from a tool
[1:09:34] SPEAKER: to something like a paper printer,
[1:09:39] SPEAKER: because it is a very, very more complex process,
[1:09:41] SPEAKER: and it will always be a more complex process.
[1:09:43] SPEAKER: - What's the most interesting place
[1:09:45] SPEAKER: you've found people using OctoPrint,
[1:09:47] SPEAKER: or you've heard of people using OctoPrint?
[1:09:48] SPEAKER: Are there any notable ones?
[1:09:50] SPEAKER: - I mean, what I really love is whenever I hear
[1:09:52] SPEAKER: about someone using them in a classroom for the curriculum,
[1:09:56] SPEAKER: where the students actually design stuff,
[1:09:59] SPEAKER: learn how to shape things in a cut program,
[1:10:01] SPEAKER: maybe do something like,
[1:10:03] SPEAKER: first they go through how is a function formed,
[1:10:05] SPEAKER: and then rotate that around some axes,
[1:10:08] SPEAKER: and then extrude that or export that into a cut program,
[1:10:11] SPEAKER: and then slice that and send that off to a printer
[1:10:13] SPEAKER: and suddenly you have a figurine
[1:10:15] SPEAKER: that is based on a mathematical formula
[1:10:17] SPEAKER: that you entered into something.
[1:10:19] SPEAKER: And things like this is where I think it really helps kids
[1:10:23] SPEAKER: and young adults to learn that they are in control
[1:10:27] SPEAKER: of the world around them,
[1:10:28] SPEAKER: and that they can do more than just consume
[1:10:31] SPEAKER: and take whatever is already created,
[1:10:33] SPEAKER: but that they can actually shape the world around them.
[1:10:36] SPEAKER: And I've also had the pleasure
[1:10:39] SPEAKER: of when I was still at my old job,
[1:10:41] SPEAKER: but already doing Octopint on the site,
[1:10:44] SPEAKER: at some point we organized a little maker get together
[1:10:47] SPEAKER: in the company, and I dragged my 3D printer in there
[1:10:50] SPEAKER: and showed it off and fired it off and printed some whistles
[1:10:53] SPEAKER: where the P inside the whistle
[1:10:54] SPEAKER: was already inside the whistle.
[1:10:56] SPEAKER: So you had to break it off afterwards,
[1:10:58] SPEAKER: but it was inside, printed inside.
[1:10:59] SPEAKER: And there were three kids there of a colleague
[1:11:01] SPEAKER: who were absolutely blown away.
[1:11:04] SPEAKER: I gave each of them a whistle.
[1:11:05] SPEAKER: I'm not sure if the colleague
[1:11:06] SPEAKER: would still talk to me after that,
[1:11:08] SPEAKER: but the glowing in the eyes,
[1:11:12] SPEAKER: that was just absolutely amazing.
[1:11:14] SPEAKER: Like they understood what was happening there
[1:11:17] SPEAKER: and they understood the process.
[1:11:18] SPEAKER: And I think it might have shifted something in their heads
[1:11:21] SPEAKER: as to how to approach the world, even a tiny, tiny bit.
[1:11:25] SPEAKER: I know that it did for me when I got access to a 3D printer,
[1:11:28] SPEAKER: how it started making me not look at a problem and go,
[1:11:32] SPEAKER: but rather maybe if I just do this
[1:11:35] SPEAKER: and then design something like that,
[1:11:36] SPEAKER: and then add some screws here and hey, solved.
[1:11:40] SPEAKER: - It has the same loop as like the first time
[1:11:42] SPEAKER: you use an Arduino to do something
[1:11:43] SPEAKER: and instead of changing something on a screen with code,
[1:11:47] SPEAKER: you turn on a light or turn on a motor with code,
[1:11:49] SPEAKER: it has the same, it gives you the same good brain.
[1:11:52] SPEAKER: - Absolutely.
[1:11:53] SPEAKER: And that's, I guess that's also why
[1:11:54] SPEAKER: I maybe also am drawn to electronics,
[1:11:56] SPEAKER: which is also something that I tinker with.
[1:11:58] SPEAKER: So it all just tickles the same part of my brain.
[1:12:01] SPEAKER: I think this problem solving
[1:12:04] SPEAKER: and then being able to build something custom
[1:12:07] SPEAKER: to your specific problem,
[1:12:09] SPEAKER: but maybe not so custom
[1:12:11] SPEAKER: that it cannot also be used by others.
[1:12:12] SPEAKER: So that is also something that I find very rewarding
[1:12:15] SPEAKER: and like just solving an issue,
[1:12:18] SPEAKER: not only for me, but also for others
[1:12:19] SPEAKER: and reducing the time that collective humankind
[1:12:23] SPEAKER: has to spend on problems, maybe.
[1:12:25] SPEAKER: - I love it.
[1:12:26] SPEAKER: I can't think of a better way to spend your time.
[1:12:28] SPEAKER: - Right?
[1:12:29] SPEAKER: It is fun.
[1:12:30] SPEAKER: (upbeat music)
[1:12:33] SPEAKER: - So one of the things we're really interested in
[1:12:35] SPEAKER: on the show is kind of the lifestyle
[1:12:37] SPEAKER: of making your living from an open source project.
[1:12:39] SPEAKER: You're full-time on Octoprint
[1:12:40] SPEAKER: and you're pretty much just crowdfunding
[1:12:42] SPEAKER: the project at this point. - Exactly.
[1:12:43] SPEAKER: - Is that the model?
[1:12:44] SPEAKER: - Yeah, exactly.
[1:12:45] SPEAKER: So I have a patron, I have GitHub sponsors.
[1:12:48] SPEAKER: I have some ad revenue from the forums
[1:12:51] SPEAKER: and the main webpage and the plugin repository as well.
[1:12:54] SPEAKER: I have some merchandise going on as well,
[1:12:58] SPEAKER: but that's not really generating much revenue.
[1:13:00] SPEAKER: That's more like people were asking for it.
[1:13:02] SPEAKER: And so I figured, well, okay, here is a spreadsheet store.
[1:13:04] SPEAKER: Have fun.
[1:13:05] SPEAKER: And all of that combined is actually paying my salary,
[1:13:10] SPEAKER: so to speak.
[1:13:11] SPEAKER: And that is pretty amazing.
[1:13:12] SPEAKER: I am still kind of stumped that this works.
[1:13:15] SPEAKER: And I actually am also a bit skeptical
[1:13:18] SPEAKER: if it will work endlessly, but currently it looks good
[1:13:21] SPEAKER: and I'm just going with it and happy that it is working.
[1:13:26] SPEAKER: 'Cause it has enabled me to work full-time on Octoprint
[1:13:28] SPEAKER: and really concentrate fully on it.
[1:13:30] SPEAKER: And even better than the employment situation
[1:13:33] SPEAKER: that I had before, because there I also had a bit,
[1:13:35] SPEAKER: of course, the employer had some interest in Octoprint,
[1:13:38] SPEAKER: steering it in certain directions.
[1:13:39] SPEAKER: And while I was still fully in control, of course,
[1:13:42] SPEAKER: I had to always juggle a bit with regards
[1:13:44] SPEAKER: to what to spend my time on.
[1:13:46] SPEAKER: And so now I simply concentrate on the things
[1:13:49] SPEAKER: that I think will bring the most value
[1:13:52] SPEAKER: to the community in one way or the other.
[1:13:54] SPEAKER: So currently, for example, the biggest next task
[1:13:57] SPEAKER: is actually something that only on second look
[1:14:01] SPEAKER: will bring value to the community.
[1:14:03] SPEAKER: Because the thing is that, yeah, this year so far
[1:14:05] SPEAKER: has been very, very intense for some reason.
[1:14:07] SPEAKER: I think, so the pandemic brought in a ton of more users
[1:14:11] SPEAKER: because everyone was buying printers to print PPE
[1:14:15] SPEAKER: and then keeping the printers
[1:14:17] SPEAKER: and continuing to print stuff.
[1:14:18] SPEAKER: So the last, let's say three years have been
[1:14:22] SPEAKER: even more stressful and even more work intense as before.
[1:14:24] SPEAKER: And it's now come to a point where I'm noticing
[1:14:26] SPEAKER: that the project as it is needs to change in that way
[1:14:31] SPEAKER: that I need to make it sustainable for me again
[1:14:33] SPEAKER: and for reasons of my own mental health.
[1:14:35] SPEAKER: So the current idea is, or the current push
[1:14:38] SPEAKER: is towards better documentation, better contributor help.
[1:14:41] SPEAKER: Because the thing is that even 10 years in
[1:14:44] SPEAKER: or almost 10 years in,
[1:14:46] SPEAKER: most of the code is still only written by me.
[1:14:49] SPEAKER: So recently, so over the last couple of releases
[1:14:52] SPEAKER: that has gotten a bit better
[1:14:53] SPEAKER: and I'm actually seeing a lot of pull requests now
[1:14:56] SPEAKER: that I didn't have to take care of and such,
[1:14:58] SPEAKER: but it's still mostly a one woman show
[1:15:01] SPEAKER: and that only scales so much.
[1:15:03] SPEAKER: So the goal now is to really try to open this up more,
[1:15:07] SPEAKER: make it more accessible, get a ton of that stuff
[1:15:10] SPEAKER: that currently only lives in my head
[1:15:11] SPEAKER: about knowledge of the system,
[1:15:13] SPEAKER: knowledge about the G-code communication stack,
[1:15:16] SPEAKER: knowledge about various firmware quirks and stuff,
[1:15:19] SPEAKER: all of this somehow documented.
[1:15:21] SPEAKER: And this is like a behemoth of work,
[1:15:24] SPEAKER: but I think it will be worth it.
[1:15:25] SPEAKER: Even though at first, I think the regular user of OctoPrint
[1:15:29] SPEAKER: will probably not immediately see that as a benefit,
[1:15:31] SPEAKER: but long-term, I think it definitely will be a benefit
[1:15:34] SPEAKER: for the project as a whole.
[1:15:36] SPEAKER: - It seems like this is a turn
[1:15:37] SPEAKER: that most successful projects hit at some point,
[1:15:39] SPEAKER: where they go from either one
[1:15:41] SPEAKER: or a small number of contributors
[1:15:43] SPEAKER: to realizing that they need to be building the infrastructure
[1:15:47] SPEAKER: so that a lot more people can contribute.
[1:15:49] SPEAKER: Do you have the sense that there are people waiting,
[1:15:52] SPEAKER: eager, ready to go and start contributing code,
[1:15:54] SPEAKER: making pull requests?
[1:15:55] SPEAKER: - I talk very openly about situations like these.
[1:15:59] SPEAKER: Also, I have this monthly or semi-monthly devlog
[1:16:02] SPEAKER: for OctoPrint for my Patreons mostly,
[1:16:04] SPEAKER: but I also push the recordings public for everyone after,
[1:16:07] SPEAKER: where I also talk about things like that.
[1:16:09] SPEAKER: And whenever I mentioned that, I'm just feeling overwhelmed
[1:16:12] SPEAKER: and that I need to look into somehow making all of this
[1:16:16] SPEAKER: a bit more sustainable.
[1:16:17] SPEAKER: Again, I always get people like, how can I help?
[1:16:20] SPEAKER: So the will is there.
[1:16:21] SPEAKER: The problem is that right now,
[1:16:23] SPEAKER: the project is simply not in a state
[1:16:24] SPEAKER: where I can just point someone somewhere and say go,
[1:16:27] SPEAKER: because that will only generate even more work
[1:16:30] SPEAKER: because then I have to teach them first.
[1:16:32] SPEAKER: So the idea is to get the teaching out upfront
[1:16:34] SPEAKER: and then hopefully scale it that way.
[1:16:38] SPEAKER: And in some way, I actually already did this
[1:16:42] SPEAKER: when I created a plugin system back in 2015,
[1:16:44] SPEAKER: because before that, whenever someone wanted a new feature
[1:16:47] SPEAKER: in OctoPrint, they had to request it from me to build,
[1:16:50] SPEAKER: and maybe they also build it themselves,
[1:16:53] SPEAKER: but then after I had to maintain it myself.
[1:16:55] SPEAKER: And with the plugin system, I now have the situation
[1:16:58] SPEAKER: that when someone wants something that is not suitable
[1:17:01] SPEAKER: for the general public or not usable for the general public,
[1:17:04] SPEAKER: because for example, it targets a very specific piece
[1:17:07] SPEAKER: of hardware that additional hardware lights
[1:17:10] SPEAKER: that are attached to the Raspberry Pi
[1:17:12] SPEAKER: or a very specific notification service
[1:17:15] SPEAKER: or something like that.
[1:17:16] SPEAKER: That is not something that should go into core,
[1:17:17] SPEAKER: but now I can tell people, hey, just build it as a plugin.
[1:17:20] SPEAKER: And then people can install it and use it.
[1:17:23] SPEAKER: And that way I already have
[1:17:25] SPEAKER: at least this maintenance overload spread over,
[1:17:28] SPEAKER: I think something like 300,
[1:17:31] SPEAKER: no, it's not 300 plugin authors,
[1:17:34] SPEAKER: but something like 300 plugins.
[1:17:35] SPEAKER: I have to look that up,
[1:17:36] SPEAKER: but over a massive amount of shoulders.
[1:17:39] SPEAKER: And the good thing is that people who write plugins
[1:17:41] SPEAKER: and write many plugins and are really into writing plugins
[1:17:44] SPEAKER: sooner rather than later,
[1:17:45] SPEAKER: also learn about the internals of OctoPrint
[1:17:48] SPEAKER: and then also help here and there, there.
[1:17:51] SPEAKER: And this is how I currently recruit contributors.
[1:17:55] SPEAKER: And that has been very fruitful,
[1:17:57] SPEAKER: but it would be really nice, I think,
[1:17:59] SPEAKER: to make it even easier to get a grasp of how stuff works,
[1:18:03] SPEAKER: because it's still something where if you are interested
[1:18:06] SPEAKER: into getting into OctoPrint development right now,
[1:18:08] SPEAKER: you will have to do a lot of legwork
[1:18:11] SPEAKER: because you will have to sit down and read through the code.
[1:18:13] SPEAKER: I mean, I do my best in documenting it well
[1:18:16] SPEAKER: and making it so that you can really read it
[1:18:18] SPEAKER: and understand it,
[1:18:19] SPEAKER: but you still will need some while to navigate the code base
[1:18:23] SPEAKER: to figure out which components will live where,
[1:18:25] SPEAKER: what part talks to what and stuff like this.
[1:18:28] SPEAKER: And these are things that are currently absolutely, yeah,
[1:18:32] SPEAKER: living inside my head and ready to be called there
[1:18:35] SPEAKER: even after four weeks of vacation, as I'm just noticing.
[1:18:38] SPEAKER: But it's something that not everyone obviously has,
[1:18:42] SPEAKER: and it would be nice to just have some kind of documentation
[1:18:45] SPEAKER: also documenting the code structures,
[1:18:47] SPEAKER: documenting the whole architecture, also design decisions,
[1:18:50] SPEAKER: because often I get things
[1:18:52] SPEAKER: where someone influenced something,
[1:18:55] SPEAKER: but in a way that will cause issues
[1:18:57] SPEAKER: because they have no thought about this, this, this, this,
[1:19:00] SPEAKER: and that, and things like that I think are way less likely
[1:19:04] SPEAKER: to happen if you have more of a larger overview
[1:19:07] SPEAKER: about how everything fits together and clicks together.
[1:19:10] SPEAKER: - Is your end goal to get to the point that you can say,
[1:19:12] SPEAKER: hey, here's a list of tasks that need to be done
[1:19:14] SPEAKER: and people can just grab them and do pull requests
[1:19:16] SPEAKER: and get there? - That would be wonderful,
[1:19:18] SPEAKER: yeah. - Okay.
[1:19:19] SPEAKER: - Yeah, yeah.
[1:19:19] SPEAKER: - Yeah, more people writing code
[1:19:22] SPEAKER: means it's better for everybody, right?
[1:19:23] SPEAKER: - I mean, it's not only writing code,
[1:19:25] SPEAKER: it would also be nice having help in writing documentation,
[1:19:27] SPEAKER: improving documentation and such,
[1:19:29] SPEAKER: but for that you also have to first, of course,
[1:19:31] SPEAKER: get an entry way into the platform and all that.
[1:19:35] SPEAKER: And that is something where I found the project
[1:19:37] SPEAKER: to be severely lacking at the moment because it's just,
[1:19:41] SPEAKER: I mean, you find a lot of very beginner-friendly things,
[1:19:43] SPEAKER: like how do you install OctoPrint?
[1:19:45] SPEAKER: How do you install plugins into it and things?
[1:19:48] SPEAKER: I also have a plugin tutorial which covers the basics
[1:19:51] SPEAKER: on how to get up running and also points you
[1:19:53] SPEAKER: to various spaces where you can go to try more.
[1:19:56] SPEAKER: And then of course, there's also a whole bunch of plugins
[1:19:58] SPEAKER: that you can just look at and figure out
[1:20:00] SPEAKER: how they did certain things,
[1:20:03] SPEAKER: but that will only get you so far.
[1:20:05] SPEAKER: And I have a certain quality expectation
[1:20:10] SPEAKER: when it comes to the code of OctoPrint
[1:20:12] SPEAKER: in order to be able to,
[1:20:15] SPEAKER: or in order to enable contributors to meet that,
[1:20:18] SPEAKER: I think I have to do some more legwork
[1:20:19] SPEAKER: in order to give them the information
[1:20:22] SPEAKER: and the background that they need to know what is what
[1:20:26] SPEAKER: and why things should be done in a certain way
[1:20:29] SPEAKER: and not others, and yeah.
[1:20:31] SPEAKER: - Well, then there's infrastructure
[1:20:32] SPEAKER: and stuff like code reviews and all.
[1:20:33] SPEAKER: There's a ton that goes into the post work
[1:20:35] SPEAKER: once people do the contributions as well,
[1:20:37] SPEAKER: which I think a lot of people who use open source projects
[1:20:39] SPEAKER: maybe don't exactly understand.
[1:20:41] SPEAKER: - Yeah, the pull requests are always a bit
[1:20:44] SPEAKER: of a mixed bag in that regard.
[1:20:45] SPEAKER: So thankfully, often it's a case of you look at the code
[1:20:49] SPEAKER: and it looks fine and you just merge it and say thank you
[1:20:51] SPEAKER: and hooray, another bug solved
[1:20:54] SPEAKER: and another small improvement made, everything is fine.
[1:20:57] SPEAKER: But often it's also a case, for example,
[1:20:59] SPEAKER: yesterday I found myself in a situation,
[1:21:01] SPEAKER: or was it the day before yesterday, it's all a blur,
[1:21:03] SPEAKER: where I was reviewing a pull request that someone had sent
[1:21:07] SPEAKER: and I was really struggling to describe
[1:21:11] SPEAKER: the downside of the current design
[1:21:13] SPEAKER: and why another design would be better.
[1:21:14] SPEAKER: And it took me something like an hour or so
[1:21:16] SPEAKER: to somehow put my thoughts on paper, so to speak,
[1:21:20] SPEAKER: and communicate it to them.
[1:21:21] SPEAKER: And I'm still not sure if I did this correctly
[1:21:23] SPEAKER: because I haven't heard back yet,
[1:21:25] SPEAKER: but it would have taken me five minutes to do it myself.
[1:21:28] SPEAKER: But these five minutes, I mean,
[1:21:30] SPEAKER: if I always take these five minutes and do it myself,
[1:21:32] SPEAKER: that doesn't educate anyone,
[1:21:35] SPEAKER: that doesn't teach the others how to do this properly.
[1:21:37] SPEAKER: So taking this time to teach and to explain
[1:21:41] SPEAKER: and to motivate and maybe also to just walk them
[1:21:45] SPEAKER: through my own thoughts and my approach to solution,
[1:21:49] SPEAKER: discovery and all that, that pays off,
[1:21:53] SPEAKER: but it costs a lot of time.
[1:21:55] SPEAKER: So what I never understand is really how projects like,
[1:22:00] SPEAKER: for example, Home Assistant that gets swamped
[1:22:03] SPEAKER: in pull requests, how they do that,
[1:22:05] SPEAKER: because all of this stuff has to be reviewed.
[1:22:07] SPEAKER: All of this stuff has to be coached.
[1:22:08] SPEAKER: And I'm certainly not at a point yet
[1:22:10] SPEAKER: where I would be able to handle
[1:22:14] SPEAKER: that amount of pull requests, for example.
[1:22:16] SPEAKER: As wonderful as it is to get
[1:22:18] SPEAKER: these many community contributions,
[1:22:20] SPEAKER: they always also cost time to handle
[1:22:24] SPEAKER: and that is something that I think would be lovely
[1:22:27] SPEAKER: if more people also understood
[1:22:28] SPEAKER: that if the pull request sits around a while,
[1:22:31] SPEAKER: that doesn't mean I'm not interested in it
[1:22:33] SPEAKER: or that I don't like it or I'm simply too chicken
[1:22:37] SPEAKER: to tell them, but it might just be a simple resource problem.
[1:22:41] SPEAKER: - When we had Paulis on the show,
[1:22:42] SPEAKER: I think he said they have 16 people
[1:22:45] SPEAKER: who are working in different aspects of Home Assistant, so.
[1:22:47] SPEAKER: - Yeah, yeah, we are in contact as well.
[1:22:50] SPEAKER: - Yeah.
[1:22:51] SPEAKER: - If you have amount of people that,
[1:22:53] SPEAKER: I now also have some people who helped me
[1:22:54] SPEAKER: with reviewing and stuff, but still the,
[1:22:57] SPEAKER: due to the lack of knowledge transfer from the past,
[1:23:00] SPEAKER: I still am stuck on a lot of stuff that I have to do myself.
[1:23:04] SPEAKER: - So you're based in Germany and a good number
[1:23:06] SPEAKER: of the maintainers and open source developers
[1:23:08] SPEAKER: that we've talked to are based in various parts of Europe.
[1:23:11] SPEAKER: Do you feel like Europe is maybe a better
[1:23:13] SPEAKER: and more supportive environment for people
[1:23:15] SPEAKER: to do open source work full-time?
[1:23:18] SPEAKER: - Maybe full-time because we have this healthcare thing
[1:23:20] SPEAKER: that is better implemented.
[1:23:23] SPEAKER: - That's what I was hoping you would say.
[1:23:24] SPEAKER: - Yeah, I mean, I'm not saying that our approach
[1:23:27] SPEAKER: to healthcare is perfect.
[1:23:28] SPEAKER: In fact, I could rent probably for another hour or so
[1:23:32] SPEAKER: about everything that is wrong
[1:23:34] SPEAKER: with the German approach to healthcare,
[1:23:37] SPEAKER: but at least I do not have to worry
[1:23:39] SPEAKER: about developing a toothache or breaking my hand
[1:23:42] SPEAKER: or something, I mean, I still would worry
[1:23:44] SPEAKER: about breaking my hand, but I wouldn't worry
[1:23:46] SPEAKER: about the invoice from the hospital or something like that,
[1:23:50] SPEAKER: but rather about when will I be able to work again?
[1:23:52] SPEAKER: Can I ever go climbing again or something like that?
[1:23:56] SPEAKER: So I think that might be a factor, but I don't know.
[1:24:01] SPEAKER: I also see a lot of, at least from the plugin maintainers,
[1:24:04] SPEAKER: a bunch of them are from the US,
[1:24:07] SPEAKER: but as you said, none of them full-time.
[1:24:09] SPEAKER: So yeah, maybe that is indeed the thing.
[1:24:12] SPEAKER: - It also seemed like at least in the past,
[1:24:15] SPEAKER: maybe like in primary schools and early education,
[1:24:19] SPEAKER: you all did a better job teaching kids how to program,
[1:24:22] SPEAKER: it seems like, than we did here.
[1:24:23] SPEAKER: I know you were self-taught, but-
[1:24:25] SPEAKER: - I wouldn't say that about my school, I have to say.
[1:24:27] SPEAKER: - Okay, okay, it's mostly the Norwegians, I think.
[1:24:31] SPEAKER: - Yeah, I mean, the Scandinavian side of things
[1:24:33] SPEAKER: is regarding education, the education system is top notch,
[1:24:37] SPEAKER: so that is pretty damn amazing what they are doing there.
[1:24:40] SPEAKER: (upbeat music)
[1:24:44] SPEAKER: - Thanks again to Gina for coming by and chatting with us.
[1:24:46] SPEAKER: This has been fascinating.
[1:24:46] SPEAKER: I've been using OctoPrint since almost the beginning.
[1:24:49] SPEAKER: We used it on some of the early MakerBots
[1:24:52] SPEAKER: that we used at the Tested Office
[1:24:53] SPEAKER: for the Print the Mystery.
[1:24:55] SPEAKER: We did a series of videos where we printed a new object
[1:24:57] SPEAKER: every week-ish for five years, I think, four and a half years
[1:25:01] SPEAKER: and it was literally the reason I gave to the people
[1:25:05] SPEAKER: in charge of money, I was like,
[1:25:06] SPEAKER: "Hey, we need to buy a 3D printer."
[1:25:08] SPEAKER: They were like, "Well, if you're only getting one video out
[1:25:09] SPEAKER: "of I'm not spending $1,000," and I was like,
[1:25:11] SPEAKER: "What if we did a video every week with it?"
[1:25:13] SPEAKER: They were like, "Yes, that's what we're looking for."
[1:25:16] SPEAKER: - Now that's ROI.
[1:25:17] SPEAKER: - Yeah, and then it ended up being an enormous boondoggle
[1:25:20] SPEAKER: that took hours and hours and hours every week
[1:25:22] SPEAKER: for a four-minute video that 50,000 people watched.
[1:25:25] SPEAKER: - Well, hey, I got that little headphone hook out of it
[1:25:28] SPEAKER: from you, so totally worth it.
[1:25:30] SPEAKER: - Oh, that's true, I printed you a headphone hook, right?
[1:25:32] SPEAKER: - Yes, and a tiny Super Meat Boy.
[1:25:35] SPEAKER: - Yeah, I printed a tiny Joey Famelli, our producer.
[1:25:37] SPEAKER: - That's amazing.
[1:25:38] SPEAKER: - It sat on our dining room table for a really long time,
[1:25:40] SPEAKER: but if you'd like to know more about OctoPrint,
[1:25:42] SPEAKER: you can find out more at octoprint.org.
[1:25:44] SPEAKER: It runs on a bunch of pies.
[1:25:46] SPEAKER: I've run it on, Gina said not to run it on low end,
[1:25:49] SPEAKER: on old pies now, but a pie three will run it fantastic,
[1:25:52] SPEAKER: is my understanding, and when I get a new 3D printer,
[1:25:55] SPEAKER: I'm gonna plug it back up, and I kinda got the hankering
[1:25:59] SPEAKER: for 3D printer as a result of talking to Gina about this.
[1:26:02] SPEAKER: - Yeah, I could see it.
[1:26:03] SPEAKER: Also, listen to Gina.
[1:26:04] SPEAKER: Don't use a substandard power supply with your Raspberry Pi.
[1:26:07] SPEAKER: - Yeah, never. - Just don't.
[1:26:08] SPEAKER: - Never.
[1:26:09] SPEAKER: It was also fascinating to talk to somebody
[1:26:11] SPEAKER: who's at this stage of their open-source journey,
[1:26:14] SPEAKER: where she's now into the place where she's doing the work
[1:26:17] SPEAKER: to expand the audience for contributors to the project.
[1:26:21] SPEAKER: - I think, I wanna say, I'm thinking back,
[1:26:23] SPEAKER: I think she's the first maintainer we've heard
[1:26:26] SPEAKER: essentially say that they're still writing
[1:26:28] SPEAKER: basically all the code themselves.
[1:26:30] SPEAKER: - Yeah, everybody else we've talked to
[1:26:31] SPEAKER: has gone through this trial.
[1:26:36] SPEAKER: From talking to different people over the last six months
[1:26:38] SPEAKER: since we started doing the show,
[1:26:39] SPEAKER: it seems like everybody reaches a point
[1:26:42] SPEAKER: where they're like, okay, I have to do some work
[1:26:43] SPEAKER: so that other people can do the work
[1:26:45] SPEAKER: and help me do the work.
[1:26:47] SPEAKER: And like Paula said, Home Assistant did this long ago.
[1:26:51] SPEAKER: With Gina, it seems like she's just reaching that point
[1:26:53] SPEAKER: and I'm excited to see how it goes for her
[1:26:55] SPEAKER: and I'm sure she would love contributors soon, so.
[1:26:59] SPEAKER: I guess that'll do it for us this week.
[1:27:01] SPEAKER: This episode of the FOSSPOD, as always,
[1:27:03] SPEAKER: is brought to you by Google Open Source.
[1:27:05] SPEAKER: They bring all the value of open source to Google
[1:27:07] SPEAKER: and all the resources of Google to open source.
[1:27:11] SPEAKER: Matt Purdy produced this episode and Sabrina Hill edited it.
[1:27:14] SPEAKER: We'll be back in two weeks
[1:27:16] SPEAKER: with another episode of the FOSSPOD.
[1:27:18] SPEAKER: I don't know about you, Brad,
[1:27:19] SPEAKER: but I'm feeling a little samba in my life.
[1:27:21] SPEAKER: - Samba, really?
[1:27:25] SPEAKER: - Samba.
[1:27:26] SPEAKER: - People can't see you dancing in this video call.
[1:27:29] SPEAKER: - Oh, this is awkward.
[1:27:30] SPEAKER: - Yeah, I don't know.
[1:27:31] SPEAKER: Yeah, dude, I've been spending a lot of time
[1:27:33] SPEAKER: in smb.conf recently, so.
[1:27:36] SPEAKER: The next episode, well-timed for me.
[1:27:39] SPEAKER: See y'all then.
[1:27:41] SPEAKER: (upbeat music)
[1:27:46] SPEAKER: Well, that was a fabulous interview.
[1:27:47] SPEAKER: What lovely and intelligent people, too much?
[1:27:52] SPEAKER: - If we do say so ourselves.
[1:27:54] SPEAKER: - Yes, oh, I thought you did an excellent job, Brad.
[1:27:57] SPEAKER: - Well, thank you, same to you.
[1:27:58] SPEAKER: We're just the best.
[1:27:59] SPEAKER: - We really do kick ass, modest.
[1:28:02] SPEAKER: I realized that the,
[1:28:03] SPEAKER: as I was looking at the FOSSPOD page
[1:28:05] SPEAKER: for the first time in a while,
[1:28:06] SPEAKER: I realized that the joke description of the show
[1:28:08] SPEAKER: that I typed in and never changed is still there.
[1:28:11] SPEAKER: - Oh, these. - Which is,
[1:28:12] SPEAKER: from the creative geniuses
[1:28:13] SPEAKER: behind "Brad and Will Made a Tech Pod."
[1:28:15] SPEAKER: - It was, that was an extremely considered
[1:28:17] SPEAKER: tongue-in-cheek kind of thing.
[1:28:19] SPEAKER: - Yeah, last minute.
[1:28:20] SPEAKER: I hope people get that joke,
[1:28:21] SPEAKER: 'cause otherwise we just sound like incredible assholes.
[1:28:23] SPEAKER: - They have to, right?
[1:28:25] SPEAKER: - I would hope so.
[1:28:26] SPEAKER: But nobody would say that earnestly, right?
[1:28:29] SPEAKER: - Oh, no, that is,
[1:28:31] SPEAKER: people absolutely would say that earnestly.
[1:28:33] SPEAKER: I would hope not about a podcast.
[1:28:35] SPEAKER: But anyway, speaking of people
[1:28:38] SPEAKER: who aren't incredible assholes
[1:28:39] SPEAKER: and are actually really delightful, wonderful people,
[1:28:41] SPEAKER: this is the part of the show where we thank our patrons.
[1:28:43] SPEAKER: - Thank you, patrons.
[1:28:44] SPEAKER: - Thank you, patrons.
[1:28:46] SPEAKER: As always, if you would like to find out
[1:28:48] SPEAKER: how you can support "Brad and Will Made a Tech Pod,"
[1:28:50] SPEAKER: you can leave an iTunes review,
[1:28:51] SPEAKER: but even better, you can go to patreon.com/techpod
[1:28:54] SPEAKER: and mash that subscribe button.
[1:28:56] SPEAKER: For as little as two bucks a month,
[1:28:57] SPEAKER: you can get access to the fabulous Tech Pod Discord,
[1:29:00] SPEAKER: where there's a bunch of beautiful nerds
[1:29:01] SPEAKER: who talk about things that are almost certainly
[1:29:04] SPEAKER: gonna be of interest to you
[1:29:05] SPEAKER: if you've made it this far into this podcast,
[1:29:07] SPEAKER: including 3D printing and Linux
[1:29:09] SPEAKER: and running things on Raspberry Pis and--
[1:29:12] SPEAKER: - I missed a conversation in the Linux channel today
[1:29:14] SPEAKER: about shell customization,
[1:29:16] SPEAKER: people sharing their aliases.
[1:29:18] SPEAKER: - Look, I'm gonna tell you a secret
[1:29:20] SPEAKER: about being the person who's one of the two people
[1:29:22] SPEAKER: whose name is on the podcast,
[1:29:24] SPEAKER: is that when you go into the channel
[1:29:25] SPEAKER: and you dredge up a four-hour-old conversation--
[1:29:28] SPEAKER: - Oh, I know, yeah, yeah, yeah.
[1:29:29] SPEAKER: - No one's gonna complain.
[1:29:30] SPEAKER: - I know.
[1:29:31] SPEAKER: - With great power, great responsibility, yada yada.
[1:29:34] SPEAKER: This is the part of the show where we thank our patrons.
[1:29:36] SPEAKER: So, as always, a very special thank you
[1:29:39] SPEAKER: goes out to our executive producer tier patrons,
[1:29:41] SPEAKER: including Paddle Creek Games, makers of Fractured Veil,
[1:29:44] SPEAKER: Andrew Slosky, Do The Bunny Crime, Serve The Bunny Time.
[1:29:49] SPEAKER: This is getting a little intense now.
[1:29:51] SPEAKER: - Lyrical.
[1:29:52] SPEAKER: - Wedge, Joel Krauska, Twinkle Twinkie, and James Kamik.
[1:29:56] SPEAKER: Thank you all so, so much.
[1:29:57] SPEAKER: We appreciate you all.
[1:29:58] SPEAKER: - Yes, we do.
[1:29:59] SPEAKER: - And I guess that will do it for us this week.
[1:30:02] SPEAKER: I hope everybody has a lovely, lovely, lovely week,
[1:30:05] SPEAKER: and we'll be back next week with another fresh episode
[1:30:09] SPEAKER: of Brad and Will Made a Tech Pod.
[1:30:11] SPEAKER: See you all next week.
