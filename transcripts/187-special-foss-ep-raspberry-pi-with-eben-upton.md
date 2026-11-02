---
episode: 187
title: Special FOSS Ep: Raspberry Pi With Eben Upton
date: 2023-04-09
guests: none
duration: 1:10:37
---

[00:00] SPEAKER: - Hey everybody, Will here.
[00:01] SPEAKER: - Hi, I'm Brad.
[00:03] SPEAKER: - We are doing something a little bit different this week.
[00:04] SPEAKER: I'm on vacation.
[00:06] SPEAKER: You're also on vacation?
[00:08] SPEAKER: - No.
[00:09] SPEAKER: - Well, you're about to be on vacation.
[00:10] SPEAKER: - Or actually, yeah, the following week, yes.
[00:11] SPEAKER: There's like a day of overlap there, sure.
[00:14] SPEAKER: - Yeah, you're off now.
[00:15] SPEAKER: Congratulations. - Yeah, that's right.
[00:15] SPEAKER: No, thank you.
[00:17] SPEAKER: - We are, instead of running a new tech pod this week,
[00:19] SPEAKER: we have a FOSPOD episode that we...
[00:22] SPEAKER: Look, if you asked me to pick my favorite FOSPOD episode,
[00:25] SPEAKER: it would be impossible for me to do so
[00:27] SPEAKER: 'cause they're all like children
[00:28] SPEAKER: and I love them all equally,
[00:30] SPEAKER: but we have a fantastic episode of the FOSPOD this week.
[00:35] SPEAKER: We have Eben Upton from the Raspberry Pi Foundation
[00:38] SPEAKER: and Raspberry Pi on to talk about
[00:41] SPEAKER: making these little computers
[00:43] SPEAKER: that have literally changed my life.
[00:45] SPEAKER: Like I don't think we'd be doing this show
[00:48] SPEAKER: were it not, like the Raspberry Pi is one of the things
[00:50] SPEAKER: that opened the door to doing this show for me.
[00:52] SPEAKER: - I think I said it somewhere in this episode,
[00:55] SPEAKER: I think it was pretty much my gateway into Linux
[00:57] SPEAKER: is the first time I ever used Linux
[00:59] SPEAKER: was the first time I got a Pi.
[01:00] SPEAKER: Anyway, yeah, so this is excellent.
[01:03] SPEAKER: If I do say so myself, an excellent conversation.
[01:07] SPEAKER: He's super fascinating to talk to.
[01:08] SPEAKER: Also, this is a never before heard episode.
[01:11] SPEAKER: This is brand new in both the FOSPOD feed
[01:13] SPEAKER: and also going on the tech pod feed here.
[01:15] SPEAKER: So even if you're an avid FOSPOD listener,
[01:17] SPEAKER: you have not heard this one yet.
[01:19] SPEAKER: - Yeah, it's fresh. - That's right.
[01:21] SPEAKER: - Enjoy and have a piece of Pi
[01:23] SPEAKER: with your Raspberry Pi episode.
[01:24] SPEAKER: (upbeat music)
[01:26] SPEAKER: Brad, how many computers did you have in your house in 2010?
[01:29] SPEAKER: - Let's see, a gaming desktop and a laptop,
[01:33] SPEAKER: and I think that's it.
[01:34] SPEAKER: How about you?
[01:35] SPEAKER: - That was probably me too.
[01:36] SPEAKER: I might've had a server.
[01:37] SPEAKER: I think I probably had a server by then,
[01:39] SPEAKER: but it was like a really low powered,
[01:41] SPEAKER: even for the time Adam processor, home server type deal
[01:46] SPEAKER: that was basically just like an SMB share.
[01:48] SPEAKER: I didn't have anything beyond that.
[01:49] SPEAKER: I had a router, which I guess you could argue
[01:51] SPEAKER: is kind of a computer, but not much else.
[01:54] SPEAKER: It was probably running Linux of some sort,
[01:56] SPEAKER: although you may not have known that,
[01:57] SPEAKER: but yeah, like even two computers at that time
[01:59] SPEAKER: felt a little bit extravagant,
[02:01] SPEAKER: but boy, little did we know what was on the way.
[02:04] SPEAKER: - Yeah, how many computers do you have running
[02:05] SPEAKER: in your house right now in 2023, Brad?
[02:06] SPEAKER: - Gosh, well, okay, I've still got a desktop.
[02:09] SPEAKER: I've still got a laptop.
[02:10] SPEAKER: Now I've got this big Linux box over here,
[02:12] SPEAKER: but also at least four Raspberry Pis around here,
[02:16] SPEAKER: maybe more, and if you want to get into,
[02:19] SPEAKER: do containers running on the Raspberry Pis
[02:20] SPEAKER: count as computers, 'cause then we're up to like two dozen.
[02:24] SPEAKER: - Yeah, I'm in a similar, like I have the desktop,
[02:27] SPEAKER: the streaming machine, the NAS, my kid's computer,
[02:29] SPEAKER: my wife's computer, and then about three,
[02:31] SPEAKER: two, three Raspberry Pis at any given time.
[02:33] SPEAKER: - They just keep multiplying, right?
[02:35] SPEAKER: The Raspberry Pi has become so indispensable,
[02:38] SPEAKER: I have thought about adopting a policy
[02:40] SPEAKER: of just having an extra on hand at all times.
[02:42] SPEAKER: I mean, not super feasible right now
[02:44] SPEAKER: 'cause they're hard to come by for supply chain reasons,
[02:46] SPEAKER: which you will hear about shortly,
[02:48] SPEAKER: but sometimes a project urge just strikes
[02:51] SPEAKER: and you need a Raspberry Pi.
[02:53] SPEAKER: Might be nice to just be able to reach
[02:54] SPEAKER: into the drawer and grab one.
[02:57] SPEAKER: - Well, I just set up a home assistant yellow,
[02:59] SPEAKER: which is a Raspberry Pi compute module based project
[03:03] SPEAKER: that freed up one of my old Pi threes,
[03:05] SPEAKER: and I was really excited 'cause like,
[03:06] SPEAKER: I would have more Pis in the house right now,
[03:08] SPEAKER: except for you have not been able to buy them
[03:10] SPEAKER: for the last two years reliably, so.
[03:13] SPEAKER: - Think about the Pi though, it's always useful.
[03:15] SPEAKER: - You can never have too much Pi, that's what I say.
[03:17] SPEAKER: (upbeat music)
[03:23] SPEAKER: (upbeat music)
[03:35] SPEAKER: - Welcome to the FOSPOD.
[03:36] SPEAKER: I'm Will.
[03:37] SPEAKER: - I'm Brad.
[03:38] SPEAKER: - As always, this week's episode of the FOSPOD
[03:40] SPEAKER: is brought to you by Google Open Source.
[03:42] SPEAKER: They bring all the value of open source to Google
[03:44] SPEAKER: and all the resources of Google to open source.
[03:46] SPEAKER: You can find out more at opensource.google.
[03:50] SPEAKER: This week on the FOSPOD, we're talking to Evan Upton,
[03:52] SPEAKER: co-founder and CEO of Raspberry Pi Trading Company,
[03:54] SPEAKER: and well, I mean, he's just a fascinating guy, it turns out.
[03:59] SPEAKER: - And the Raspberry Pi Foundation.
[04:00] SPEAKER: That's something I learned in the course of this interview
[04:04] SPEAKER: was the distinction between those two,
[04:05] SPEAKER: but dude, Raspberry Pi, it's like,
[04:08] SPEAKER: perhaps as big an institution in the maker world,
[04:11] SPEAKER: the open source world, the--
[04:13] SPEAKER: - Manufacturing.
[04:14] SPEAKER: - Yes, I mean, the range of contexts
[04:17] SPEAKER: in which these adorable little fruit flavored
[04:20] SPEAKER: single board computers are used is kind of endless
[04:23] SPEAKER: these days.
[04:24] SPEAKER: - Yeah, it's funny 'cause it's,
[04:25] SPEAKER: we were talking about this before we started the show.
[04:28] SPEAKER: I can't really think of a project that, you know,
[04:31] SPEAKER: in the normy, non-techie world,
[04:33] SPEAKER: people are pretty much completely unaware of,
[04:36] SPEAKER: but like in our circles, everybody knows about this
[04:40] SPEAKER: and it became such a ubiquitous, important part
[04:43] SPEAKER: of the computing ecosystem in like less than a decade really
[04:46] SPEAKER: 'cause like the first Pi boards launched in 2012
[04:50] SPEAKER: and there honestly wasn't a whole lot you could do with them
[04:52] SPEAKER: if you couldn't write code in those early days.
[04:54] SPEAKER: And then projects started building,
[04:57] SPEAKER: like the fact that this single board computer existed
[04:59] SPEAKER: that was 20 or $30 meant that projects would start tailoring
[05:04] SPEAKER: their kind of single service computer projects
[05:07] SPEAKER: specifically for them.
[05:08] SPEAKER: Whether it was like an arcade machine emulator
[05:10] SPEAKER: or an old console emulator or a router or a DNS server
[05:15] SPEAKER: that strips out all advertising from the internet.
[05:17] SPEAKER: - Yes, yeah, print servers, 3D print servers or interfaces,
[05:22] SPEAKER: home assistant, you name it.
[05:23] SPEAKER: - Yeah, network VNC machines.
[05:27] SPEAKER: - Smart mirrors.
[05:28] SPEAKER: - Wait, smart mirrors?
[05:29] SPEAKER: I haven't seen that one.
[05:30] SPEAKER: - Dude, if you never, there are a lot of smart mirror
[05:32] SPEAKER: projects involving Raspberry Pis out there.
[05:34] SPEAKER: They look so cool.
[05:36] SPEAKER: - Oh man, I just put a new medicine cabinet in.
[05:38] SPEAKER: I should do a smart mirror in there.
[05:39] SPEAKER: - You should slap a Raspberry Pi on the guts
[05:42] SPEAKER: of an old monitor on the back of the mirror.
[05:44] SPEAKER: - Yeah, the Pi is such a formative kind of gateway
[05:48] SPEAKER: and open source for me.
[05:49] SPEAKER: I'm pretty sure the first model B I bought
[05:51] SPEAKER: was the first real experience I had with Linux, honestly.
[05:55] SPEAKER: 'Cause like you said, those early projects,
[05:57] SPEAKER: I mean, I wasn't writing code,
[05:58] SPEAKER: but those early, early projects that were available
[06:01] SPEAKER: for the Pi, you kind of couldn't set up
[06:03] SPEAKER: without at least touching a bash prompt, right?
[06:04] SPEAKER: And I don't think I had done a lot of that
[06:06] SPEAKER: prior to getting my first Pi.
[06:08] SPEAKER: So a big deal for, I think, a lot of people's first steps
[06:12] SPEAKER: into the world of Linux and open source.
[06:15] SPEAKER: - Yeah, so for folks who don't know,
[06:16] SPEAKER: the Raspberry Pi is a single board computer.
[06:18] SPEAKER: It runs ARM processors.
[06:20] SPEAKER: There's four main models and a bunch of little sub models
[06:23] SPEAKER: now, maybe five main models.
[06:24] SPEAKER: I think the zero probably counts
[06:25] SPEAKER: as its own thing at this point.
[06:26] SPEAKER: - Yeah, yeah.
[06:27] SPEAKER: - And you can use them for all sorts of things.
[06:29] SPEAKER: There's two things that make them different.
[06:30] SPEAKER: We talk about a little bit in the episode,
[06:32] SPEAKER: but one is that they're, pandemic concerns aside,
[06:36] SPEAKER: typically always available.
[06:37] SPEAKER: So they're not batch products.
[06:38] SPEAKER: They're products that they just continuously manufacture.
[06:40] SPEAKER: You can go to your local electronics store
[06:42] SPEAKER: and get one.
[06:43] SPEAKER: - They still make the original.
[06:45] SPEAKER: - Yeah. - It's been out
[06:45] SPEAKER: for over a decade.
[06:46] SPEAKER: They are committed to making that thing
[06:47] SPEAKER: for several more years.
[06:49] SPEAKER: - The other thing is, what used to be called Raspberry,
[06:52] SPEAKER: and it is now called Raspberry Pi OS,
[06:54] SPEAKER: is a fork of Debian that's basically designed explicitly
[06:58] SPEAKER: to run on these boards.
[06:59] SPEAKER: And there's an installer that you can download for it
[07:02] SPEAKER: that runs on Windows and lets you put the right OS files
[07:05] SPEAKER: on a flash drive or a USB thumb drive
[07:07] SPEAKER: or whatever it is you happen to need
[07:10] SPEAKER: that lets you basically jump straight
[07:13] SPEAKER: into the appliance mode for the Linux setup
[07:15] SPEAKER: for these devices.
[07:16] SPEAKER: You don't necessarily have to start from,
[07:18] SPEAKER: first you install Debian,
[07:19] SPEAKER: and then you apt-get install your,
[07:22] SPEAKER: whatever project it is you want,
[07:23] SPEAKER: and then you have to do all the configuration stuff.
[07:24] SPEAKER: It just works.
[07:25] SPEAKER: - Yes.
[07:27] SPEAKER: Yeah, that's really what it is.
[07:28] SPEAKER: I think this thing has reached a critical mass.
[07:30] SPEAKER: Like it's picked up that level of community support
[07:32] SPEAKER: that you don't have to be a Linux gray beard.
[07:34] SPEAKER: Like there's just endless tutorials and tools and guides
[07:37] SPEAKER: and all kinds of stuff out there to ease you into this.
[07:40] SPEAKER: - To the point that often the projects say,
[07:42] SPEAKER: "Hey, the easiest way to set this up
[07:43] SPEAKER: is to just buy a Raspberry Pi,
[07:45] SPEAKER: install it on the Raspberry Pi.
[07:46] SPEAKER: Don't try to run it in a container
[07:48] SPEAKER: on a normal Linux installer or whatever."
[07:50] SPEAKER: - Yes, unless you're a loon.
[07:52] SPEAKER: Yeah, it's often as simple as here's our image,
[07:55] SPEAKER: here's how to flash it to an SD card.
[07:56] SPEAKER: Just put it in there, press the power button, you're good.
[07:58] SPEAKER: - I think that's all you need to know about this interview.
[08:00] SPEAKER: Let's just get into it with the first time I heard
[08:03] SPEAKER: about a Raspberry Pi in person.
[08:06] SPEAKER: (soft music)
[08:11] SPEAKER: Evan, I went to a lot of Maker Faires in the early 2010s
[08:13] SPEAKER: and the best part of that was always getting
[08:15] SPEAKER: to interview people who'd made a fascinating stuff.
[08:17] SPEAKER: But I usually close those interviews by asking people
[08:20] SPEAKER: what they were excited about at the Maker Faire.
[08:23] SPEAKER: And in 2012 or 2013, I remember I went to one Maker Faire
[08:26] SPEAKER: and five or six people within the first half day said,
[08:31] SPEAKER: "Oh, there's this little computer the size of an Arduino,
[08:33] SPEAKER: you gotta check it out, it's really cool."
[08:35] SPEAKER: And I'm curious, like that was the moment I was like,
[08:38] SPEAKER: "Oh, I should be aware of this thing,
[08:39] SPEAKER: I gotta learn about this."
[08:40] SPEAKER: I'm curious if there was a moment for you
[08:43] SPEAKER: when you realized the Pi was something
[08:44] SPEAKER: that like really filled a need,
[08:46] SPEAKER: like this personal need that maybe first nerds
[08:49] SPEAKER: and then just normal people it turns out had.
[08:52] SPEAKER: - Yes, we had, I mean, obviously this isn't something
[08:57] SPEAKER: that we'd ever imagined was gonna sell a lot of units.
[09:01] SPEAKER: It's the thing we were building to teach,
[09:04] SPEAKER: to encourage kids to come to Cambridge.
[09:05] SPEAKER: And so our idea of success was, you know,
[09:08] SPEAKER: our idea of success was a thousand units
[09:10] SPEAKER: and our idea of wild success was 10,000 units.
[09:13] SPEAKER: I think the point where I realized that we were in trouble
[09:18] SPEAKER: was in the autumn of 2011.
[09:21] SPEAKER: So we had, we'd been working on it since 2008
[09:24] SPEAKER: and we'd sort of told people in May of 2011
[09:28] SPEAKER: that we were doing it and we'd done this
[09:30] SPEAKER: by going to see a guy called Rory Kethlen-Jones,
[09:33] SPEAKER: who's a BBC technology correspondent.
[09:35] SPEAKER: And he took a little video of one of us
[09:39] SPEAKER: holding up a very early Raspberry Pi prototype
[09:41] SPEAKER: and talking about what we were trying to accomplish.
[09:44] SPEAKER: And he got this vast number of YouTube views for his video.
[09:47] SPEAKER: He got me 600,000 YouTube views in a couple of days,
[09:50] SPEAKER: which was kind of cool, but it's very easy to,
[09:52] SPEAKER: you want to apply a very large discount factor
[09:54] SPEAKER: to that number to measure interest.
[09:56] SPEAKER: So yeah, we thought we were fine.
[09:58] SPEAKER: And then we spent a lot of time in 2011
[09:59] SPEAKER: getting from the sort of point.
[10:01] SPEAKER: It was the kick that we needed.
[10:02] SPEAKER: It was the kick in the pants
[10:04] SPEAKER: that we needed to actually go from
[10:06] SPEAKER: noodling away at this thing
[10:07] SPEAKER: to actually trying to turn it into a real project.
[10:11] SPEAKER: So we were spending 2011 going through that process
[10:13] SPEAKER: of productionizing Raspberry Pi.
[10:15] SPEAKER: But we didn't imagine that we had 600,000 people
[10:18] SPEAKER: who were interested enough to buy a Raspberry Pi.
[10:20] SPEAKER: But the point where we realized that we were in trouble
[10:22] SPEAKER: and that we got to sell a lot of these
[10:24] SPEAKER: and that we would have to scale the organization
[10:25] SPEAKER: to support that was when we put an operating system image
[10:29] SPEAKER: online in about November of 2011.
[10:32] SPEAKER: And it got something like, and this was a,
[10:34] SPEAKER: I think that this was a Fedora-based operating system.
[10:38] SPEAKER: And it had something like 50,000,
[10:40] SPEAKER: and you could only run it in QEMU, right?
[10:42] SPEAKER: There was no hardware out there.
[10:43] SPEAKER: So you could run it in a modified QEMU.
[10:46] SPEAKER: We had 50,000 downloads
[10:47] SPEAKER: of a very badly broken operating system
[10:50] SPEAKER: for a computer that didn't exist yet.
[10:52] SPEAKER: And that was the bit where we realized that there was,
[10:54] SPEAKER: that somehow this had tapped into,
[10:57] SPEAKER: it had found in that kind of big parameter space
[11:00] SPEAKER: of the things people were interested in,
[11:01] SPEAKER: we'd accidentally dropped a product
[11:04] SPEAKER: into a completely empty space
[11:06] SPEAKER: where a lot of people were standing.
[11:08] SPEAKER: It was empty of products, but very full of people.
[11:10] SPEAKER: - Yeah, it's probably that.
[11:11] SPEAKER: - The idea that you could get a whole,
[11:14] SPEAKER: I mean, so in those early days,
[11:16] SPEAKER: it was novel to have a Linux ARM machine, right?
[11:19] SPEAKER: Like finding compiled binaries and stuff
[11:21] SPEAKER: for Linux software, it wasn't,
[11:24] SPEAKER: difficult's not right, but it was unusual,
[11:25] SPEAKER: I think, still then.
[11:26] SPEAKER: And there was an inflection point
[11:28] SPEAKER: around the time the second Raspberry Pi came out
[11:31] SPEAKER: that that seemed to stop,
[11:32] SPEAKER: that all of a sudden everybody had Pi-compatible binaries
[11:35] SPEAKER: for everything and all their repos.
[11:37] SPEAKER: - Yeah, I think it was suddenly when we started,
[11:39] SPEAKER: I guess probably 2009, 2010 when we were first working
[11:43] SPEAKER: on what would become the Raspberry Pi platform,
[11:46] SPEAKER: ARM Linux itself, the kernel was an unusual thing, right?
[11:50] SPEAKER: I can't remember, 'cause it existed for a long time
[11:53] SPEAKER: outside the tree.
[11:55] SPEAKER: I guess it had maybe been merged by then,
[11:57] SPEAKER: but ARM Linux was outside the tree for a long time.
[12:00] SPEAKER: It had probably been merged, but probably fairly recently.
[12:03] SPEAKER: There were various distros available,
[12:07] SPEAKER: but it was, yeah, it was all a bit,
[12:08] SPEAKER: everything was a bit special on how you built things.
[12:12] SPEAKER: I remember, you know, trying to find a compiler,
[12:16] SPEAKER: trying to find a pre-built GCC to bootstrap yourself was,
[12:20] SPEAKER: and to build your kernel, wasn't trivial.
[12:22] SPEAKER: And yeah, there's just kind of a moment, you know,
[12:24] SPEAKER: if you draw that line between, I guess,
[12:26] SPEAKER: that point, the kind of 2010, and probably, you could say
[12:31] SPEAKER: maybe the launch of the M1, max, was probably the point
[12:34] SPEAKER: where ARM as a client architecture kind of emerges
[12:38] SPEAKER: completely into the mainstream.
[12:39] SPEAKER: There is that point somewhere in the middle there
[12:41] SPEAKER: where most, where large numbers of applications
[12:44] SPEAKER: were starting to provide binaries,
[12:45] SPEAKER: generally Raspberry Pi binaries, generally binaries
[12:47] SPEAKER: for this slightly unusual, the Raspbian world, right?
[12:51] SPEAKER: So that's ARM7HF, so hard float.
[12:56] SPEAKER: ARM Debian, but built to remove the V7 specific instruction,
[13:02] SPEAKER: so it could run on the ARM1176
[13:05] SPEAKER: that we had in Raspberry Pi 1.
[13:06] SPEAKER: Those sorts of things started to appear
[13:08] SPEAKER: in kind of 2013, 2014, 2015.
[13:10] SPEAKER: - I'm gonna ask you to suspend your humility
[13:12] SPEAKER: for just a second here.
[13:13] SPEAKER: Would you say the Pi was the first kind of primary driver
[13:16] SPEAKER: of ARM adoption in Linux,
[13:17] SPEAKER: or were there other solutions out there concurrently?
[13:20] SPEAKER: - I mean, of course, yeah, Beagle, I would say Beagle,
[13:23] SPEAKER: the Beagle board predates us probably the first
[13:27] SPEAKER: broadly available.
[13:29] SPEAKER: I guess it didn't have the continuous,
[13:30] SPEAKER: one of the interesting things about Raspberry Pi,
[13:32] SPEAKER: and of course, we've been challenged with this
[13:34] SPEAKER: over the last couple of years,
[13:35] SPEAKER: but for most of its life, one of the interesting things
[13:37] SPEAKER: that's characterized Raspberry Pi
[13:38] SPEAKER: is it's kind of continuous available,
[13:40] SPEAKER: continuous high volume availability.
[13:42] SPEAKER: And that was probably a thing
[13:43] SPEAKER: that the Beagle board didn't have.
[13:44] SPEAKER: It was something which was sporadically available.
[13:46] SPEAKER: They would build some and then sell them out
[13:48] SPEAKER: and then build some more.
[13:49] SPEAKER: But it did, and it was probably three or four times
[13:52] SPEAKER: the price, four or five times the price of Raspberry Pi,
[13:54] SPEAKER: but it did fit that same niche.
[13:56] SPEAKER: But yeah, certainly I think we popularized,
[13:59] SPEAKER: we popularized it as a platform.
[14:00] SPEAKER: Sort of going onto that point about the M1 machines,
[14:03] SPEAKER: of course, we were super happy.
[14:04] SPEAKER: We have this object called Raspberry Pi 400, right,
[14:07] SPEAKER: which is a Raspberry Pi 4 built into a compact keyboard.
[14:09] SPEAKER: We launched that about a week before the M1 Macs.
[14:12] SPEAKER: Now I grew up with, not owning, but lusting after,
[14:16] SPEAKER: Acorn Archimedes, the original ARM computer,
[14:20] SPEAKER: the original ARM desktop.
[14:21] SPEAKER: And it was kind of fun that we actually
[14:23] SPEAKER: were first back in market by a week.
[14:25] SPEAKER: We were, after a 20-year period in the wilderness
[14:28] SPEAKER: where there were no kind of consumer-oriented PCs,
[14:32] SPEAKER: we, by a week, were first back in market.
[14:35] SPEAKER: - Very basic chicken and egg question here,
[14:36] SPEAKER: because the Raspberry Pi's foundation,
[14:38] SPEAKER: like the original mission statement,
[14:39] SPEAKER: is educational outreach, right?
[14:40] SPEAKER: So was it a situation of we need to do educational outreach,
[14:44] SPEAKER: and then through brainstorming, you came to,
[14:46] SPEAKER: hey, we can make a tiny, very affordable computer?
[14:48] SPEAKER: Or was it the opposite of, hey, we can make this tiny
[14:51] SPEAKER: computer because the parts and the software are now emerging
[14:54] SPEAKER: and then what can we do with it, oh?
[14:56] SPEAKER: - Yeah, it's interesting, right?
[14:58] SPEAKER: And it's all about how you tell stories, right?
[15:00] SPEAKER: Which bit you want to emphasize.
[15:02] SPEAKER: I think, for me, it was a coming together of those,
[15:06] SPEAKER: it was a perfect coming together of those two strands.
[15:09] SPEAKER: And there wasn't really a chicken and egg.
[15:11] SPEAKER: That I was building little computers,
[15:13] SPEAKER: actually quite Arduino-like little computers.
[15:15] SPEAKER: So there's this thing that if you search
[15:17] SPEAKER: for Raspberry Pi 2006 edition,
[15:19] SPEAKER: there's this rather cobbled together looking piece
[15:22] SPEAKER: of error board that has an Atmel,
[15:24] SPEAKER: so the same chip architecture as the Arduino Uno.
[15:28] SPEAKER: It's an Atmel 644, it's got 512K of SRAM,
[15:32] SPEAKER: and it will drive a standard definition video signal,
[15:34] SPEAKER: and it kind of, it bashes,
[15:36] SPEAKER: actually uses a microcontroller both to run your code,
[15:39] SPEAKER: but also during the display period
[15:41] SPEAKER: to bash out video addresses.
[15:43] SPEAKER: To get this SRAM to drop bytes onto the bus
[15:46] SPEAKER: in the order required to draw something on the screen.
[15:50] SPEAKER: So I was building those things,
[15:52] SPEAKER: and I was also a director of studies in computer science
[15:54] SPEAKER: at the University of Cambridge.
[15:55] SPEAKER: And so I was also experiencing the collapse
[15:59] SPEAKER: in the number of young people
[16:00] SPEAKER: who are interested in computer science.
[16:01] SPEAKER: And we saw this terrible, terrible decline
[16:04] SPEAKER: between the late 1990s and the mid part
[16:06] SPEAKER: of the first decade of the century.
[16:09] SPEAKER: And so I was kind of exposed to both things.
[16:11] SPEAKER: So it was a sort of a natural coming together.
[16:12] SPEAKER: And really, remember, Raspberry Pi is testing the hypothesis
[16:16] SPEAKER: that we used to have loads of kids
[16:18] SPEAKER: who were interested in computers
[16:19] SPEAKER: because there were loads of programmable computers
[16:21] SPEAKER: in kids' lives.
[16:22] SPEAKER: And that when you took those computers away,
[16:24] SPEAKER: because you were largely replacing with games consoles
[16:26] SPEAKER: in a lot of children's lives,
[16:28] SPEAKER: the ultimate piece of very powerful non-programmable hardware
[16:31] SPEAKER: and non-end user programmable hardware.
[16:34] SPEAKER: The disappearance of general purpose computing
[16:36] SPEAKER: made the kids go away.
[16:37] SPEAKER: And if you bring back general purpose computing,
[16:39] SPEAKER: the kids will come back.
[16:40] SPEAKER: That's the hypothesis we're testing.
[16:42] SPEAKER: And it was a kind of hypothesis
[16:43] SPEAKER: that was very easy to stumble upon
[16:44] SPEAKER: if you happen to be both building little computers
[16:47] SPEAKER: and confronting the disappearance
[16:50] SPEAKER: of computing among young people.
[16:52] SPEAKER: So there's not really, it's a kind of a perfect,
[16:55] SPEAKER: a perfect coming together of these two strands
[16:57] SPEAKER: of certainly of my life.
[16:58] SPEAKER: - It's funny 'cause it's an idea
[17:01] SPEAKER: that has shown up multiple times.
[17:03] SPEAKER: You know, growing up in America,
[17:05] SPEAKER: we didn't have the rise of programmable computers as much.
[17:09] SPEAKER: They were much less available, I think, here
[17:11] SPEAKER: than they were in the UK specifically.
[17:13] SPEAKER: And it's a thing that comes up a lot
[17:16] SPEAKER: when I talk to programmers of a certain age, I think,
[17:18] SPEAKER: from the UK specifically.
[17:19] SPEAKER: - The UK is weird and it certainly is a place.
[17:22] SPEAKER: Yeah, if you look at the number of 8-bit computers,
[17:26] SPEAKER: I mean, of course, you know, the United States,
[17:28] SPEAKER: you had your Commodore 64s and you had your trash 80s
[17:30] SPEAKER: and you had a bunch of other architectures
[17:33] SPEAKER: and your Apple IIs.
[17:34] SPEAKER: But if you look at the number of distinct
[17:38] SPEAKER: 8-bit microcomputer architectures
[17:40] SPEAKER: that came out of a country that has a fifth
[17:43] SPEAKER: of the population of the United States,
[17:45] SPEAKER: it's just incredible, right?
[17:46] SPEAKER: You know, look, you look at the number
[17:47] SPEAKER: of architectures that came out of Cambridge,
[17:49] SPEAKER: that came out, developed within five miles
[17:52] SPEAKER: of where I'm sitting, you know, it's just,
[17:53] SPEAKER: there was something about the place
[17:55] SPEAKER: that made it a very fertile ground.
[17:56] SPEAKER: And of course, many of those companies sold 10,000 units.
[18:00] SPEAKER: The two big ones, of course, were Sinclair,
[18:02] SPEAKER: who sold about 5 million of their Spectrum product,
[18:05] SPEAKER: mostly in the UK, but did have some export success.
[18:07] SPEAKER: And then, of course, Acorn, who sold about
[18:09] SPEAKER: one and a half million BBC microcomputers,
[18:12] SPEAKER: failed as a computer company,
[18:14] SPEAKER: but then succeeded in terms of spinning off
[18:16] SPEAKER: this little chip design organization that became Arm.
[18:19] SPEAKER: - Talking about the decline in kind of interest
[18:22] SPEAKER: in computing among young people that you mentioned,
[18:23] SPEAKER: I mean, there's this emerging theme in the tech press,
[18:26] SPEAKER: even these days, that basically says like,
[18:28] SPEAKER: oh, you know, kids don't know what a file system is anymore.
[18:30] SPEAKER: Like, they only know how to type on touch screens now.
[18:32] SPEAKER: Like, do you still think that's true?
[18:33] SPEAKER: Or, I mean, has your foundation made enough inroads?
[18:35] SPEAKER: Are you seeing, are you seeing those tides turn
[18:38] SPEAKER: through your efforts or otherwise?
[18:40] SPEAKER: - I think if you imagine there's this scalar,
[18:43] SPEAKER: this scalar value that we care about,
[18:45] SPEAKER: which is number of applicants to the University of Cambridge,
[18:47] SPEAKER: where the deadline is the 15th of October,
[18:50] SPEAKER: something like that.
[18:51] SPEAKER: So on the 16th of October every year,
[18:52] SPEAKER: you're presented with a scalar number.
[18:54] SPEAKER: That value went from about 600 in 1999
[18:57] SPEAKER: to about 200 to 250 in 2008.
[19:00] SPEAKER: And last year, that scalar was about 1,450.
[19:03] SPEAKER: So we have a little over twice as many applicants
[19:06] SPEAKER: to computer science at the University of Cambridge
[19:07] SPEAKER: as we had at the height of the dot-com boom
[19:09] SPEAKER: when everyone thought that computer science
[19:11] SPEAKER: was a meal ticket, right?
[19:13] SPEAKER: So if you just look at that number,
[19:15] SPEAKER: yes, there has been an absolute sea change
[19:18] SPEAKER: over the last 10 or 12 years.
[19:20] SPEAKER: And I think Raspberry Pi has had a part in that.
[19:23] SPEAKER: I think that the kids who rock up at least
[19:25] SPEAKER: have the good sense to pretend that Raspberry Pi
[19:28] SPEAKER: was the reason for this.
[19:29] SPEAKER: Fascinating thing for me as somebody
[19:31] SPEAKER: who grew up writing computer games on my BBC Micro
[19:34] SPEAKER: and then on my Commodore Amiga,
[19:36] SPEAKER: and had imagined that the primary use case
[19:39] SPEAKER: for Raspberry Pi in education would be software,
[19:41] SPEAKER: the vast majority of these people
[19:42] SPEAKER: say Raspberry Pi in robotics.
[19:44] SPEAKER: So the vast majority of these people
[19:45] SPEAKER: are not having a purely software-mediated interaction
[19:49] SPEAKER: with Raspberry Pi.
[19:50] SPEAKER: It's about physical computing,
[19:51] SPEAKER: which means it's very, very lucky.
[19:53] SPEAKER: I mean, that's obviously somewhere
[19:53] SPEAKER: where Raspberry Pi kind of stands out.
[19:55] SPEAKER: It's not something that I was super excited.
[19:57] SPEAKER: They're those general purpose IO pins on a Raspberry Pi,
[20:00] SPEAKER: which allow you to do all those kind of cool
[20:02] SPEAKER: general purpose computer,
[20:02] SPEAKER: those cool physical computing things.
[20:05] SPEAKER: That was Pete Lomas,
[20:06] SPEAKER: who designed the first-generation Raspberry Pi hardware,
[20:08] SPEAKER: was very keen to expose some of the interface
[20:11] SPEAKER: and capabilities of the chip we were using.
[20:13] SPEAKER: And I didn't care enough to argue with him.
[20:16] SPEAKER: And of course, how lucky we were both,
[20:19] SPEAKER: of course, in the education space,
[20:20] SPEAKER: but also that was the capability
[20:22] SPEAKER: that unlocked the industrial use of Raspberry Pi,
[20:24] SPEAKER: which really now accounts for the majority of our sales.
[20:27] SPEAKER: - I was gonna say the politics of ports
[20:30] SPEAKER: on these kinds of little dev boards is really interesting,
[20:34] SPEAKER: because you have the entire spectrum now, right?
[20:37] SPEAKER: You have a development board
[20:39] SPEAKER: that has a bunch of USB and HDMI and audio outs
[20:41] SPEAKER: and all the things you need to make it
[20:43] SPEAKER: basically a little tiny, either single serving server
[20:46] SPEAKER: or single serving desktop or laptop or whatever you want.
[20:50] SPEAKER: But then you also have the compute modules,
[20:51] SPEAKER: which let you just drop an SOC on a board
[20:54] SPEAKER: that somebody else designs
[20:55] SPEAKER: and plug into whatever ins and outs
[20:57] SPEAKER: that they're looking for.
[20:59] SPEAKER: And I'm curious how you think about that going now
[21:02] SPEAKER: and how it's changed and what you're thinking
[21:04] SPEAKER: about going forward.
[21:06] SPEAKER: - The nice thing with the core platform,
[21:07] SPEAKER: so the SBC, the single board computer platform,
[21:10] SPEAKER: that's kind of classic Raspberry Pi,
[21:11] SPEAKER: it's still the dominant volume runner for us out of seven.
[21:15] SPEAKER: Obviously last year was a rather volume constrained year,
[21:17] SPEAKER: but if you look back to 2021,
[21:19] SPEAKER: when we sold 7 million Raspberry Pi computers of all sorts,
[21:23] SPEAKER: the SBC product, the single board computer product
[21:25] SPEAKER: with its four USB ports and ethernet connector,
[21:29] SPEAKER: that was between five and a half and 6 million units.
[21:31] SPEAKER: And so compute module was on the order of a million,
[21:34] SPEAKER: on the order of a million units.
[21:36] SPEAKER: So the SBC is the volume runner.
[21:39] SPEAKER: We're lucky that we've never had to really make
[21:42] SPEAKER: any decisions to prioritize educational users
[21:46] SPEAKER: of that product or industrial use of that product.
[21:48] SPEAKER: The decisions you make to make it a great educational product
[21:51] SPEAKER: or also make it a great industrial product,
[21:53] SPEAKER: 'cause particularly the kind of robustness,
[21:55] SPEAKER: the reliability and robustness, they're very important.
[21:57] SPEAKER: We always say, what's the worst environment?
[22:00] SPEAKER: What's the more challenging environment?
[22:01] SPEAKER: An oil rig or a kid's bedroom, they're both pretty,
[22:04] SPEAKER: I mean, I've got two kids and I've never been on an oil rig,
[22:07] SPEAKER: but I've been to some power stations.
[22:09] SPEAKER: And a kid's bedroom is a pretty tough environment.
[22:12] SPEAKER: So we kind of, there we've kind of always been able
[22:14] SPEAKER: to kind of like have a happy medium.
[22:17] SPEAKER: You never have to choose one consumer over the other.
[22:20] SPEAKER: We have now compute module, which is purely targeted
[22:22] SPEAKER: to the embedded and industrial space.
[22:25] SPEAKER: And of course we have Pi 400,
[22:26] SPEAKER: which is purely targeted at the consumer space.
[22:28] SPEAKER: So we have put our toes in the water in both directions.
[22:31] SPEAKER: The nice thing is actually both of those are kind of,
[22:34] SPEAKER: most of the investments we make are at the platform level.
[22:37] SPEAKER: So deriving those specific platforms from the core platform,
[22:41] SPEAKER: from the SBC platform is actually quite cheap
[22:43] SPEAKER: from a cost and an engineering perspective.
[22:46] SPEAKER: So we have tried to kind of,
[22:47] SPEAKER: we put this product in the market,
[22:48] SPEAKER: in the middle of the market,
[22:49] SPEAKER: and then we just kind of try to feel out
[22:51] SPEAKER: what people don't like.
[22:52] SPEAKER: And the main thing that people don't like
[22:53] SPEAKER: as they go to scale with the SBC
[22:55] SPEAKER: is they don't like being enslaved
[22:57] SPEAKER: by our form factor choices, right?
[23:00] SPEAKER: And you do see people who, you do see industrial,
[23:03] SPEAKER: that I have a keen eye for the appearance of that boat tail,
[23:10] SPEAKER: the two pairs of USB connectors and the ethernet jack.
[23:14] SPEAKER: And if you look carefully at lots of industrial products,
[23:16] SPEAKER: you see that boat tail a lot, right?
[23:18] SPEAKER: It's the sign that someone's built a big object,
[23:20] SPEAKER: an industrial object,
[23:22] SPEAKER: and there's been enough space inside it.
[23:23] SPEAKER: And so their solution for how do they embed a Raspberry Pi
[23:25] SPEAKER: is they put it inside, they have a wiring loom or a hat
[23:28] SPEAKER: that sits on top of it and mounts their circuitry.
[23:31] SPEAKER: The challenge that people have is when they try to address
[23:34] SPEAKER: more consumer-oriented use cases,
[23:37] SPEAKER: they don't want to have to follow our choices
[23:40] SPEAKER: about onboard peripherals,
[23:41] SPEAKER: they don't have to follow our choices about connector layout
[23:44] SPEAKER: and that's really where the Compute Module products,
[23:46] SPEAKER: they've been kind of a slow burn.
[23:47] SPEAKER: We've actually been doing Compute Modules since 2014.
[23:50] SPEAKER: And it's really only the last couple of years,
[23:52] SPEAKER: and I think with the introduction of Compute Module 4,
[23:54] SPEAKER: that that started to take off like a rocket.
[23:56] SPEAKER: So it's still a small part of our volume,
[23:58] SPEAKER: but by far the largest growing segment of our business.
[24:02] SPEAKER: - I mean, given the lead time on new board designs
[24:05] SPEAKER: and hardware 4, especially the,
[24:07] SPEAKER: like I think about Home Assistant
[24:09] SPEAKER: and folks like that in this space
[24:11] SPEAKER: and like the time it took them to design the board
[24:13] SPEAKER: and all that, if, as that Compute Module factor,
[24:16] SPEAKER: form factor becomes a little more static or stable,
[24:19] SPEAKER: I think it'll help those projects ramp
[24:22] SPEAKER: and lean into that kind of stuff faster and better maybe.
[24:25] SPEAKER: - Yeah, and we've had two distinct form factors
[24:27] SPEAKER: for the Compute Module.
[24:28] SPEAKER: So until up to Compute Module 3, Compute Module 3 Plus,
[24:31] SPEAKER: we have an SODIMM form factor,
[24:33] SPEAKER: where you put a JEDEC SODIMM socket down on your board
[24:35] SPEAKER: and then kind of slide it in
[24:37] SPEAKER: and then clip it in like a memory module.
[24:39] SPEAKER: And then Compute Module 4, we threw that.
[24:41] SPEAKER: And that is that we have continuity of,
[24:43] SPEAKER: we have both backwards and forwards compatibility
[24:45] SPEAKER: in that space.
[24:46] SPEAKER: And then Compute Module 4, we replace that with this,
[24:48] SPEAKER: a pair of high density managed impedance connectors
[24:51] SPEAKER: that you clip down onto the board.
[24:53] SPEAKER: And that's definitely been a good choice.
[24:56] SPEAKER: It's a more space efficient choice.
[24:58] SPEAKER: It's a more cost effective choice.
[25:00] SPEAKER: I guess the other decisions I think we made
[25:01] SPEAKER: with Compute Module 4, which were informed by experience
[25:04] SPEAKER: with earlier modules and have really helped us.
[25:07] SPEAKER: We put Wi-Fi on the board as an option.
[25:09] SPEAKER: I don't really, there's a platform,
[25:12] SPEAKER: I'm not sure if it's defunct now called Android Things,
[25:15] SPEAKER: which is effectively IoT platform built around
[25:17] SPEAKER: the Android kernel and bits of the Android user land.
[25:20] SPEAKER: And I had a very revealing conversation
[25:23] SPEAKER: with a member of the Google Android Things team in Tokyo,
[25:28] SPEAKER: I think back in about 2018.
[25:29] SPEAKER: And he said, well, you really need to put Wi-Fi
[25:33] SPEAKER: on your module because what it means is
[25:34] SPEAKER: as soon as you want to go to scale,
[25:36] SPEAKER: you have to really abandon.
[25:37] SPEAKER: You either have to do a bunch of Wi-Fi engineering yourself
[25:39] SPEAKER: or you kind of have to abandon the Raspberry Pi platform
[25:42] SPEAKER: and the Compute Module platform for another platform.
[25:46] SPEAKER: So we put Wi-Fi on as an option.
[25:48] SPEAKER: That obviously eases a lot of people's integration.
[25:50] SPEAKER: It eases a lot of people's migration from the SPC platform,
[25:53] SPEAKER: which has integrated Wi-Fi into the modular space.
[25:56] SPEAKER: So that was one thing.
[25:56] SPEAKER: The other thing we did was we massively simplified
[25:58] SPEAKER: the power chain.
[26:00] SPEAKER: So earlier Compute Modules,
[26:01] SPEAKER: you have to give them a bunch of rails.
[26:03] SPEAKER: You have to give them a 3V3 rail
[26:05] SPEAKER: and at least a 3V3 and a 1V8 rail.
[26:07] SPEAKER: And I think another rail as well.
[26:09] SPEAKER: You have to put circuitry on your baseboard
[26:11] SPEAKER: that delivers those rails and brings those rails up
[26:13] SPEAKER: and takes them down in order, in the proper order
[26:15] SPEAKER: so that nothing latches up.
[26:16] SPEAKER: Compute Module 4, you give it five volts
[26:18] SPEAKER: and it makes its own rails.
[26:19] SPEAKER: It has a power management IC on there.
[26:20] SPEAKER: It makes its own rails, in fact, it gives you the rails back.
[26:22] SPEAKER: So it'll give you, it'll give you a 3V3 rail
[26:24] SPEAKER: for you to use, as long as you don't draw
[26:26] SPEAKER: too much power from it.
[26:27] SPEAKER: That's been a huge, I struggle, I think, sometimes
[26:30] SPEAKER: when we're, when we're speccing and designing these
[26:32] SPEAKER: to understand what the pain,
[26:33] SPEAKER: where the pain points are going to be.
[26:35] SPEAKER: And so we put these, these products in the market
[26:37] SPEAKER: and sometimes we find that we've,
[26:39] SPEAKER: we've done something that people find painful
[26:40] SPEAKER: and it limits the success of a product.
[26:43] SPEAKER: That was definitely a big,
[26:45] SPEAKER: a big factor in the success of CM4.
[26:47] SPEAKER: - So, you know, we're, we're largely
[26:48] SPEAKER: an open source podcast here.
[26:49] SPEAKER: So I'm curious about open source practices,
[26:51] SPEAKER: large and small.
[26:52] SPEAKER: I'm curious, is there anywhere in the hardware
[26:54] SPEAKER: and software stack that you use open source practices?
[26:57] SPEAKER: For example, can anybody contribute
[26:58] SPEAKER: to core parts of Raspberry Pi OS?
[27:01] SPEAKER: Or is it still like a relatively kind of closed
[27:03] SPEAKER: or professional effort?
[27:06] SPEAKER: - So if you think about the evolution
[27:09] SPEAKER: of the Raspberry Pi software environment from 2011, 2012,
[27:14] SPEAKER: through to the present day,
[27:16] SPEAKER: I think what you're seeing is we have this thing
[27:18] SPEAKER: that's occasionally at the cycle stop on ELF
[27:20] SPEAKER: and that is sometimes disparagingly called the blob,
[27:23] SPEAKER: which is a large closed source software binary
[27:27] SPEAKER: that runs on the closed CPUs in the platform.
[27:31] SPEAKER: So it runs on the VPU, effectively a DSP.
[27:33] SPEAKER: It's actually a fairly powerful DSP,
[27:35] SPEAKER: but really these days we only use the scaler core.
[27:37] SPEAKER: There is a kind of system management processor
[27:40] SPEAKER: and early days, everything ran on there,
[27:42] SPEAKER: everything multimedia related ran on there.
[27:44] SPEAKER: So camera processing, video decode, video encode,
[27:47] SPEAKER: display scan out, controlling the HDMI subsystem.
[27:51] SPEAKER: Did I mention 3D graphics? 3D graphics.
[27:53] SPEAKER: So all of that stuff ran inside the blob.
[27:55] SPEAKER: And then what you've seen over the years
[27:57] SPEAKER: is a kind of carving away of,
[27:59] SPEAKER: so where you have an open,
[28:00] SPEAKER: where you say we have an open fairly famously,
[28:02] SPEAKER: where you had an OpenGL API on the ARM side,
[28:06] SPEAKER: what that was was effectively a serialization shim
[28:09] SPEAKER: that would take the core, serialize them,
[28:10] SPEAKER: pass them over a FIFO and down into this blob,
[28:12] SPEAKER: which would then do what it was told.
[28:13] SPEAKER: Actually, that's kind of great for OpenGL
[28:15] SPEAKER: 'cause OpenGL is designed for that exact,
[28:17] SPEAKER: for that, that's a very natural implementation style
[28:21] SPEAKER: for OpenGL, but it wasn't very pleasing to people
[28:24] SPEAKER: because people couldn't see what was going on inside.
[28:26] SPEAKER: And we were very lucky that I think in about 2014,
[28:32] SPEAKER: we got permission to release the architecture documentation
[28:36] SPEAKER: for the 3D graphics core,
[28:38] SPEAKER: the video core for graphics core in the chip.
[28:40] SPEAKER: And we released this and this is pretty unusual actually
[28:42] SPEAKER: to have good public document.
[28:44] SPEAKER: I was involved in designing the core
[28:45] SPEAKER: and it's pretty unusual to have good public documentation.
[28:47] SPEAKER: That still isn't really the case certainly,
[28:49] SPEAKER: say for the Mali cores that you see in a lot of other SOCs.
[28:52] SPEAKER: And Emma Anholt joined my team at Broadcom
[28:56] SPEAKER: basically to build a Mesa driver stack
[28:59] SPEAKER: around this, using this documentation.
[29:02] SPEAKER: And so from probably 2014, 2015 onwards,
[29:05] SPEAKER: we did have the option to turn off
[29:07] SPEAKER: the 3D graphics element of the blob and use Mesa instead.
[29:11] SPEAKER: And then Emma went on to develop a driver for video core six,
[29:14] SPEAKER: which is the core that we use in the modern Raspberry Pis
[29:17] SPEAKER: and that's then being further improved by Galia.
[29:19] SPEAKER: So on the 3D graphics side,
[29:20] SPEAKER: you saw us turning off a bit of the blob.
[29:23] SPEAKER: And then in the camera processing side,
[29:26] SPEAKER: you saw us turn off the camera processing
[29:27] SPEAKER: and move across to lib camera.
[29:29] SPEAKER: It displays scan out, you saw us turning off that element
[29:32] SPEAKER: and moving across to KMS.
[29:33] SPEAKER: And so really all that's left actually is video encode.
[29:36] SPEAKER: H.264 video encode still runs inside the blob.
[29:39] SPEAKER: And that's really, I mean, it's great
[29:40] SPEAKER: because obviously we can leverage the efforts
[29:43] SPEAKER: of these enormous teams that have put together
[29:44] SPEAKER: these very, very powerful middleware systems.
[29:47] SPEAKER: We can leverage some of those efforts.
[29:49] SPEAKER: We can contribute back to those efforts.
[29:51] SPEAKER: If you look at our education mission,
[29:52] SPEAKER: it means that there's no point,
[29:55] SPEAKER: it's really undesirable for there to be a point
[29:57] SPEAKER: where you have to say, here be dragons, don't look inside.
[29:59] SPEAKER: Don't look inside this black box that does OpenGL.
[30:01] SPEAKER: You really want someone who's sufficiently inquisitive
[30:03] SPEAKER: to be able to go all the way down
[30:04] SPEAKER: and see when I asked, please draw this triangle,
[30:06] SPEAKER: what actually happened deep down at the bottom of the stack
[30:09] SPEAKER: and what do we think is happening inside the hardware?
[30:11] SPEAKER: And I suspect that video encode is still there in the blob.
[30:16] SPEAKER: I suspect probably the next or next but one generation
[30:19] SPEAKER: of Raspberry Pi will get down to a point
[30:21] SPEAKER: where there's effectively only clocks, power, and reset.
[30:23] SPEAKER: And that's fairly traditional.
[30:24] SPEAKER: I mean, Intel chips have the Intel management engine
[30:26] SPEAKER: in there, you often have some little one,
[30:28] SPEAKER: most systems have some little microcontroller,
[30:31] SPEAKER: which is handling, bringing the big cores out of reset,
[30:34] SPEAKER: effectively, and we'll probably get to that point.
[30:36] SPEAKER: That'll be really desirable.
[30:37] SPEAKER: And hopefully we may even get, when we get to that point,
[30:39] SPEAKER: even though there will still be a binary
[30:41] SPEAKER: and probably a signed binary down there
[30:44] SPEAKER: that does those things, you know,
[30:45] SPEAKER: hopefully we'll even be able to publish the source
[30:47] SPEAKER: for that binary so people can even understand
[30:49] SPEAKER: what that's doing.
[30:50] SPEAKER: - Speaking of new functionality
[30:52] SPEAKER: and adding new functionality to the core
[30:54] SPEAKER: and to the CPUs and to the Pis downstream,
[30:57] SPEAKER: how does stuff like machine learning acceleration
[30:59] SPEAKER: and the kind of the stuff that happens in tensor cores
[31:01] SPEAKER: and stuff like that, how does that apply to Pi going forward?
[31:03] SPEAKER: - So we've got an interesting philosophy
[31:05] SPEAKER: about how we decide what to put into a Raspberry Pi
[31:07] SPEAKER: hardware platform.
[31:08] SPEAKER: And it's broadly, you can summarize it as we divide,
[31:11] SPEAKER: we take the cost of the feature and we divide it through
[31:15] SPEAKER: by the fraction of people who will find it useful.
[31:19] SPEAKER: So a feature, a $1 feature that everyone uses
[31:22] SPEAKER: or a 10 cent feature that's used by a 10th of people
[31:27] SPEAKER: get the same priority in our decision-making.
[31:31] SPEAKER: This is actually a really, really hard barrier
[31:33] SPEAKER: for new features to overcome, right?
[31:35] SPEAKER: The only really, if you look at a modern Raspberry Pi,
[31:37] SPEAKER: the only qualitatively new feature
[31:39] SPEAKER: that's in a Raspberry Pi today
[31:40] SPEAKER: that wasn't in the 2012 product is wireless,
[31:43] SPEAKER: is Wi-Fi and Bluetooth.
[31:44] SPEAKER: And that's the only thing that gives a $1 to $2 feature
[31:48] SPEAKER: and it's useful to almost everybody,
[31:50] SPEAKER: pretty much everything else.
[31:51] SPEAKER: There's no ADC, there's no analog to digital converter
[31:53] SPEAKER: on the Raspberry Pi because it'll cost 10 to 20 cents
[31:56] SPEAKER: and we don't think that actually the vast majority
[31:58] SPEAKER: of our users need one.
[31:59] SPEAKER: And so what that philosophy tends to do
[32:02] SPEAKER: is it tends to push lesser used features
[32:04] SPEAKER: off onto external hardware.
[32:07] SPEAKER: And that's always been good.
[32:08] SPEAKER: That's always been good to us as a decision-making heuristic.
[32:12] SPEAKER: And so, yeah, if you wanna do some machine learning
[32:14] SPEAKER: on a Raspberry Pi, actually for 1.8 gigahertz,
[32:18] SPEAKER: A72s is quite a lot of machine learning throughput.
[32:20] SPEAKER: So a lot of people's machine learning requirements
[32:23] SPEAKER: will actually fit onto the CPUs.
[32:25] SPEAKER: If you wanna do more machine learning than that,
[32:26] SPEAKER: you can go and buy a coral,
[32:28] SPEAKER: say a Google coral accelerator, they're about 60 bucks.
[32:30] SPEAKER: They've got about two Tops of inference on there.
[32:34] SPEAKER: And that applies to everything from analog
[32:37] SPEAKER: to digital converters all the way up
[32:38] SPEAKER: to machine learning accelerators.
[32:40] SPEAKER: That's been good to us because it's actually created space
[32:42] SPEAKER: for other people in our ecosystem to innovate.
[32:45] SPEAKER: You know, the fact that we don't try and slurp
[32:47] SPEAKER: all of the functionality into the platform
[32:49] SPEAKER: means that there is a business.
[32:50] SPEAKER: You know, you could start a business selling really nice
[32:53] SPEAKER: digital to analog converters that you connect
[32:55] SPEAKER: to a Raspberry Pi and we won't come and drive over you.
[32:57] SPEAKER: You know, we won't come and add those features
[32:59] SPEAKER: into our platform.
[33:01] SPEAKER: - It's interesting, sometimes what's not on there
[33:03] SPEAKER: leads to as much kind of learning opportunity
[33:05] SPEAKER: as what it is, right?
[33:06] SPEAKER: Like the original model B that I bought,
[33:07] SPEAKER: as you say, it doesn't have a DAC on it.
[33:09] SPEAKER: And I would, first of all, I was like,
[33:10] SPEAKER: why does the music coming out of this thing sound like this?
[33:13] SPEAKER: But second of all, it was like, oh,
[33:14] SPEAKER: so that's what PWM audio is, right?
[33:16] SPEAKER: It's like, I had no idea that that existed as a concept
[33:19] SPEAKER: until I had to work around it
[33:20] SPEAKER: because of what was not on that board
[33:22] SPEAKER: and had to go buy a little, you know,
[33:23] SPEAKER: $5 USB DAC or whatever.
[33:25] SPEAKER: - And of course, that was a wonderful learning experience
[33:28] SPEAKER: for us because we always kind of knew
[33:29] SPEAKER: that you can do better than PWM audio.
[33:32] SPEAKER: - Well, even if the hardware you have
[33:34] SPEAKER: is effectively a filtered pin,
[33:36] SPEAKER: you can do a lot better than just piping PCM audio
[33:40] SPEAKER: into the duty cycle register for a PWM block.
[33:44] SPEAKER: You can do all sorts of clever Sigma Delta
[33:47] SPEAKER: noise shaping stuff, you know, one bit DAC effectively.
[33:50] SPEAKER: What if it was a HiFi would be market,
[33:52] SPEAKER: if it was a HiFi in my childhood at least
[33:53] SPEAKER: would have been marketed as a, you know,
[33:54] SPEAKER: Panasonic would market these things as one bit DACs, right?
[33:57] SPEAKER: And what we've ended up with, you know,
[33:58] SPEAKER: if you go back and you run a modern Raspberry Pi
[34:01] SPEAKER: operating system on the Raspberry Pi one,
[34:02] SPEAKER: and we're quite proud of the year,
[34:03] SPEAKER: that's kind of like a core bit of our ethos
[34:06] SPEAKER: that you can run today's operating system
[34:08] SPEAKER: on the 2012 hardware and it performs pretty well.
[34:11] SPEAKER: Actually you find the audio quality is pretty good
[34:12] SPEAKER: and that's because it's picked up a lot of noise shaping,
[34:15] SPEAKER: a lot of fairly alarming noise shaping code over the years.
[34:19] SPEAKER: - So since you mentioned old Pis,
[34:20] SPEAKER: I feel like one of the ways you can tell you're a nonprofit
[34:23] SPEAKER: and not a corporation is that you're still supporting
[34:25] SPEAKER: decade old products.
[34:26] SPEAKER: So I'm curious, I mean, there's a bunch of questions there.
[34:28] SPEAKER: I mean, the big one for me is, you know,
[34:30] SPEAKER: until pretty recently,
[34:31] SPEAKER: you were offering one 32 bit operating system
[34:33] SPEAKER: that ran across the entire product line.
[34:35] SPEAKER: And I'm sure like philosophically that was, you know,
[34:37] SPEAKER: it's easier to support one platform, et cetera, et cetera.
[34:40] SPEAKER: And then, you know,
[34:40] SPEAKER: you finally started offering a 64 bit option
[34:43] SPEAKER: for newer models.
[34:44] SPEAKER: I mean, does that increase the support burden
[34:46] SPEAKER: kind of exponentially or is it something you've taken
[34:49] SPEAKER: in stride to now be having kind of different
[34:52] SPEAKER: different Raspberry Pi OSs?
[34:53] SPEAKER: - It was a real wrench for us having two
[34:56] SPEAKER: and we limited ourselves to two, sir.
[34:57] SPEAKER: I mean, there's another obvious choice which would be three.
[35:00] SPEAKER: So you could have an ARMv6HF raspbian,
[35:04] SPEAKER: effectively image that ran on Raspberry Pi one
[35:06] SPEAKER: and Raspberry Pi zero.
[35:07] SPEAKER: You could have a ARMv7HF, ARMhf in Debian speak,
[35:15] SPEAKER: that runs on Raspberry Pi two.
[35:17] SPEAKER: And then you could have the ARM64 version
[35:21] SPEAKER: that runs on Raspberry Pi three and later.
[35:23] SPEAKER: So we decided not to do that.
[35:25] SPEAKER: So there's nothing, there's no special Raspberry Pi two
[35:27] SPEAKER: Cortex-A7 build.
[35:29] SPEAKER: - Yeah, it was a bit of a wrench.
[35:30] SPEAKER: I think because of the way that the Debian world works,
[35:33] SPEAKER: actually not too much of a wrench.
[35:35] SPEAKER: You know, an enormous amount of effort goes into,
[35:38] SPEAKER: you know, if you sort of pick
[35:40] SPEAKER: what couldn't we have done Raspberry Pi
[35:43] SPEAKER: without obviously Debian
[35:45] SPEAKER: and the way that Debian thinks about the world.
[35:47] SPEAKER: And so the fact that a lot of effort goes into making
[35:50] SPEAKER: the system fairly architecture neutral
[35:53] SPEAKER: allows us to support two fairly radically
[35:57] SPEAKER: different architectures.
[35:58] SPEAKER: Of course, ARM32 and ARM64
[36:00] SPEAKER: with relatively little engineering effort.
[36:02] SPEAKER: - Have you had any coordination with any other
[36:04] SPEAKER: kind of operating system groups that are non Linux?
[36:06] SPEAKER: I mean, like for example, like FreeBSD has been trying
[36:08] SPEAKER: to bring ARM up to tier one support recently.
[36:10] SPEAKER: Like I tried to install FreeBSD on a Pi two
[36:12] SPEAKER: like three years ago, and it was a rough experience.
[36:15] SPEAKER: Like, do you have any contact with other groups
[36:17] SPEAKER: that are making efforts like that?
[36:18] SPEAKER: - We have sporadic, we have sporadic contact.
[36:20] SPEAKER: So I think you can sort of divide operating system support
[36:23] SPEAKER: for Raspberry Pi into let's say four buckets.
[36:29] SPEAKER: So you've got Linux, various Linux distros.
[36:33] SPEAKER: You have Windows, and of course there are sporadic efforts
[36:37] SPEAKER: from Microsoft and from the community
[36:39] SPEAKER: to make various incarnations of Windows work on Raspberry Pi
[36:42] SPEAKER: some pretty successful, some fairly ropy.
[36:45] SPEAKER: You have, so that was two, you have the BSDs
[36:49] SPEAKER: and we do have some light touch interaction
[36:52] SPEAKER: with the various BSD ecosystems.
[36:54] SPEAKER: Generally trying to answer, trying to answer questions
[36:58] SPEAKER: and also trying to provide where we can software
[37:01] SPEAKER: that interfaces with the various subsystems on the device
[37:05] SPEAKER: which isn't GPL licensed because of course
[37:08] SPEAKER: they have a challenge and there are various subsystems
[37:11] SPEAKER: where they can't really take bits of Linux kernel
[37:13] SPEAKER: where kind of you're close to Linux,
[37:16] SPEAKER: the Linux kernel drivers being the reference,
[37:19] SPEAKER: the software reference architecture,
[37:21] SPEAKER: but of course they're inappropriately licensed
[37:22] SPEAKER: and so we occasionally do work
[37:24] SPEAKER: to try to help people with that problem.
[37:26] SPEAKER: And then you have other operating systems
[37:28] SPEAKER: and that's everything from, you know,
[37:29] SPEAKER: various research operating systems to a RISC OS.
[37:33] SPEAKER: Of course, you know, we've always liked the fact
[37:34] SPEAKER: that you could run the original arm operating system
[37:37] SPEAKER: on Raspberry Pi and we do have a very friendly,
[37:40] SPEAKER: a very friendly relationship with RISCOS Open
[37:41] SPEAKER: who are just up the road from us.
[37:43] SPEAKER: (upbeat music)
[37:47] SPEAKER: - So to change the topic a little bit,
[37:49] SPEAKER: last couple of years have been challenging
[37:51] SPEAKER: for a lot of folks with pandemic supply stuff.
[37:54] SPEAKER: And I'm curious, I mean, I think we all follow
[37:57] SPEAKER: Raspberry Pi locator here.
[37:58] SPEAKER: So it seems like things are getting a little bit better
[38:01] SPEAKER: but I'm curious how you're feeling about where you're at
[38:04] SPEAKER: and what the future holds
[38:06] SPEAKER: and if there's stuff you would do differently
[38:07] SPEAKER: or if this was just an unavoidable side effect
[38:10] SPEAKER: of, you know, a worldwide pandemic.
[38:13] SPEAKER: - I think if I had my time again,
[38:16] SPEAKER: yeah, I would, you know,
[38:17] SPEAKER: what wouldn't I give today for a million, you know,
[38:21] SPEAKER: for an extra million?
[38:22] SPEAKER: Well, of any of the Raspberry Pi chips, actually,
[38:24] SPEAKER: I'm assuming 2711, which is what we used to build Pi 4s.
[38:27] SPEAKER: But what would I give for another million
[38:28] SPEAKER: of any of those chips?
[38:30] SPEAKER: I, and of course it should have been obvious, right?
[38:37] SPEAKER: You know, what was the core?
[38:39] SPEAKER: The core dynamic was a pandemic happened.
[38:43] SPEAKER: Everyone assumed there would be a massive recession.
[38:47] SPEAKER: So stopped ordering businesses,
[38:48] SPEAKER: assumed there'd be a massive recession.
[38:49] SPEAKER: So they went into de-stocking mode.
[38:51] SPEAKER: At the same time, everyone was at home
[38:53] SPEAKER: needing electronic equipment
[38:55] SPEAKER: to continue to participate in society.
[38:57] SPEAKER: And also in most, certainly European North America,
[39:02] SPEAKER: having their income protected by various government schemes
[39:06] SPEAKER: and also unable to spend money on services.
[39:08] SPEAKER: So you have the same income,
[39:10] SPEAKER: but you can no longer go on holiday or go to a restaurant.
[39:12] SPEAKER: So what are you gonna do?
[39:13] SPEAKER: You're gonna buy consumer durables.
[39:14] SPEAKER: And so it was that pair of transients,
[39:16] SPEAKER: the negative going supply transient
[39:18] SPEAKER: and the positive going demand transient were,
[39:20] SPEAKER: you know, if you sat someone down in a business school class
[39:23] SPEAKER: and you described the situation to them in those terms,
[39:26] SPEAKER: of course they would tell you what was gonna happen.
[39:28] SPEAKER: But at the time when we were in the thick of it,
[39:29] SPEAKER: and of course we were,
[39:30] SPEAKER: a lot of us were focusing on not getting COVID,
[39:32] SPEAKER: nobody called this one right.
[39:35] SPEAKER: You know, the big car companies didn't call this one right.
[39:38] SPEAKER: So yeah, if I had my time again,
[39:39] SPEAKER: obviously I would, what would I like?
[39:43] SPEAKER: I would maybe have liked somebody to talk me through it
[39:46] SPEAKER: in business school terms,
[39:46] SPEAKER: 'cause then I could have spotted what I needed to do.
[39:49] SPEAKER: And so towards the end of 2020,
[39:51] SPEAKER: you see things start to come apart.
[39:53] SPEAKER: So you see first blowouts in component lead times.
[39:57] SPEAKER: So components that you would expect to be able to get on,
[39:59] SPEAKER: on 20 week lead times, going out to 52 week lead times.
[40:02] SPEAKER: We were pretty quick in getting orders on
[40:06] SPEAKER: in that environment.
[40:07] SPEAKER: But obviously if lead times instantaneously blow out by,
[40:11] SPEAKER: say three months in one day,
[40:14] SPEAKER: it's inevitably going to create a three month void
[40:17] SPEAKER: in your supply chain.
[40:18] SPEAKER: There's no way you can get orders on fast enough
[40:20] SPEAKER: to fill that three months.
[40:21] SPEAKER: It's just an instantaneous, instantaneous hole.
[40:24] SPEAKER: - And it's not like there's parts,
[40:26] SPEAKER: it's not like you have warehouses full of parts in China
[40:28] SPEAKER: sitting, waiting to go.
[40:30] SPEAKER: Stuff comes in and gets stuck on boards
[40:32] SPEAKER: and the boards go out, right?
[40:33] SPEAKER: - Yeah, and you have some inventory.
[40:34] SPEAKER: I mean, so you have some component inventory
[40:36] SPEAKER: and at any given day you have some component inventory
[40:38] SPEAKER: and you have some finished goods inventory
[40:39] SPEAKER: and your downstream channel has some inventory
[40:42] SPEAKER: and industrial customers of that downstream channel
[40:44] SPEAKER: have some inbound inventory,
[40:47] SPEAKER: which is your finished product, right?
[40:49] SPEAKER: So there's lots of inventory sloshing around in the system,
[40:52] SPEAKER: but no, it's certainly not the case
[40:54] SPEAKER: that you have millions of units of every component
[40:57] SPEAKER: that you need to build a Raspberry Pi.
[41:01] SPEAKER: So you have this blow out.
[41:03] SPEAKER: Then once you get back into a situation
[41:05] SPEAKER: where your orders that you've placed
[41:06] SPEAKER: that were now 52 week lead time arrive,
[41:08] SPEAKER: you end up in an allocation situation.
[41:10] SPEAKER: So you end up in a situation
[41:11] SPEAKER: where even though you have orders on,
[41:13] SPEAKER: you don't get supplied at one-to-one ratio
[41:17] SPEAKER: because there is more the total aggregate demand
[41:19] SPEAKER: exceeds the total aggregate production capacity.
[41:21] SPEAKER: And so the only thing you can really do
[41:22] SPEAKER: is to give everyone a haircut.
[41:24] SPEAKER: So that was the kind of inbound situation for us,
[41:27] SPEAKER: which has persisted really up to the present moment.
[41:31] SPEAKER: It's a situation which is now improving quite rapidly.
[41:34] SPEAKER: And I think what we said when we gave an update in December
[41:37] SPEAKER: was broadly the first calendar quarter of this year
[41:40] SPEAKER: was pretty tough.
[41:42] SPEAKER: You know, it has some bright spots
[41:43] SPEAKER: and I think if you go up by locator,
[41:44] SPEAKER: you'll see what some of those bright spots are right now.
[41:46] SPEAKER: It's things like Raspberry Pi 3A Plus.
[41:48] SPEAKER: Later in this quarter, we'll see Raspberry Pi zero.
[41:51] SPEAKER: We'll see a significant improvement
[41:53] SPEAKER: in Raspberry Pi zero availability,
[41:54] SPEAKER: which is of course kind of cool
[41:55] SPEAKER: 'cause it's still my favorite Raspberry Pi product
[41:57] SPEAKER: at the zero and zero wireless.
[41:59] SPEAKER: So we'll see some improvement
[42:00] SPEAKER: over the course of this quarter,
[42:01] SPEAKER: but it's still a constraint quarter.
[42:03] SPEAKER: Next quarter is broadly speaking a pre-pandemic quarter.
[42:07] SPEAKER: So you can see next quarter as being
[42:09] SPEAKER: one and a half to two million units of inbound inventory
[42:12] SPEAKER: across the various components that we use.
[42:14] SPEAKER: But because you have backlogs,
[42:17] SPEAKER: you need to do better than that.
[42:18] SPEAKER: So that's enough to keep up,
[42:19] SPEAKER: but it's not enough to start to get back.
[42:22] SPEAKER: So I think what you'll see in the second quarter,
[42:24] SPEAKER: much better availability,
[42:25] SPEAKER: but a continuation of things like single unit limits
[42:28] SPEAKER: for consumers and what we call active management
[42:31] SPEAKER: for industrial customers,
[42:32] SPEAKER: where a customer orders something
[42:36] SPEAKER: and rather than just taking their order,
[42:38] SPEAKER: we go back to them and we actively say to them,
[42:40] SPEAKER: is that, do you really need that many units?
[42:42] SPEAKER: It's got anti-sales.
[42:43] SPEAKER: We have sales people here doing anti-sales.
[42:46] SPEAKER: So can I have 10,000 Raspberry Pis?
[42:47] SPEAKER: Well, would 1,000 Raspberry Pis
[42:49] SPEAKER: each month for 10 months be enough, you know?
[42:51] SPEAKER: 'Cause you're trying to detect inventory building.
[42:52] SPEAKER: Well, we call it kind of toilet roll hoarding
[42:54] SPEAKER: in the context of the pandemic
[42:57] SPEAKER: because that will destroy,
[42:58] SPEAKER: that even if you have a sufficient supply,
[43:02] SPEAKER: that kind of begging your neighbor behavior,
[43:03] SPEAKER: which is totally understandable and totally defensible.
[43:05] SPEAKER: And I would absolutely be doing it
[43:06] SPEAKER: if I was buying these units.
[43:10] SPEAKER: You have to find ways to help people.
[43:14] SPEAKER: It's not about stopping people doing it.
[43:16] SPEAKER: It's about making your industrial customers comfortable
[43:19] SPEAKER: that if they don't do it, they'll be fine,
[43:23] SPEAKER: that we'll look after them,
[43:24] SPEAKER: that either they can disclose their true demand to us
[43:27] SPEAKER: and that we will use that in a good way
[43:29] SPEAKER: to help make sure that they don't go lines down
[43:31] SPEAKER: rather than in a bad way to kind of give them a haircut.
[43:34] SPEAKER: So you'll see that though,
[43:35] SPEAKER: those behaviors will persist through Q2,
[43:36] SPEAKER: but it will be a good environment,
[43:38] SPEAKER: but it will be a heavily managed environment.
[43:40] SPEAKER: And then from Q3 onwards this year,
[43:41] SPEAKER: we effectively have an unlimited supply
[43:43] SPEAKER: of pretty much everything we need to make Raspberry Pis.
[43:46] SPEAKER: That will allow us to catch up on our backlogs
[43:48] SPEAKER: and then get back into the situation we wanna be in,
[43:50] SPEAKER: which is where we don't actually need
[43:52] SPEAKER: to touch our customers so much.
[43:54] SPEAKER: We can just put units in channel.
[43:55] SPEAKER: The dream with Raspberry Pi,
[43:56] SPEAKER: where we were for out of 11 years,
[44:00] SPEAKER: for nine out of 11 years in the market,
[44:02] SPEAKER: we've been in a situation where there are
[44:04] SPEAKER: hundreds of thousands to millions of units
[44:06] SPEAKER: of Raspberry Pi in channel.
[44:07] SPEAKER: And if you wake up one morning as an industrial,
[44:10] SPEAKER: as a hobbyist and you want 10, you can have 'em.
[44:12] SPEAKER: If you wake up as an industrial customer
[44:13] SPEAKER: and you want 100,000, you can have 'em.
[44:16] SPEAKER: And that kind of law of large numbers averaging effect
[44:20] SPEAKER: means that actually not many people wake up
[44:23] SPEAKER: on a given day and want 100,000 units.
[44:25] SPEAKER: And therefore you can pull from the channel
[44:27] SPEAKER: and it's as if there's an infinite supply of Raspberry Pis.
[44:29] SPEAKER: - Yeah.
[44:30] SPEAKER: You just said that the Pi Zero is your favorite.
[44:32] SPEAKER: I'm curious why.
[44:33] SPEAKER: - I just, it's the, you can think of Raspberry Pi
[44:37] SPEAKER: as having explored another use of Moore's law.
[44:40] SPEAKER: So the sort of classic PC industry use of Moore's law
[44:43] SPEAKER: is to pick a price point.
[44:44] SPEAKER: And in every, let's say 18 months, two years,
[44:46] SPEAKER: fill that price point up with twice as much compute.
[44:49] SPEAKER: And so you get an exponentially increasing amount
[44:51] SPEAKER: of compute at a given price.
[44:53] SPEAKER: The other thing you could do with Moore's law
[44:54] SPEAKER: is you can pick an amount of compute
[44:56] SPEAKER: and you can ride an exponentially decreasing price curve.
[44:59] SPEAKER: And you can sort of see Raspberry Pi
[45:01] SPEAKER: as a piece of hardware having said in 2010, 2011, 2012,
[45:06] SPEAKER: hey, what would a 2000 era PC cost now actually
[45:10] SPEAKER: because of Moore's law?
[45:11] SPEAKER: Oh, it's $35.
[45:12] SPEAKER: And that was kind of great.
[45:13] SPEAKER: And then we launched Raspberry Pi 2 in 2015.
[45:15] SPEAKER: And what did we do?
[45:15] SPEAKER: We picked $35 and we filled it
[45:17] SPEAKER: with an exponentially increasing amount of compute.
[45:19] SPEAKER: We'd actually just gone back to doing what,
[45:21] SPEAKER: at a different price point,
[45:22] SPEAKER: we've gone back to doing what everybody else does
[45:24] SPEAKER: with Moore's law.
[45:24] SPEAKER: And really Raspberry Pi Zero, I love it
[45:26] SPEAKER: because it's an example of a few months later
[45:30] SPEAKER: realizing that we'd conformed
[45:34] SPEAKER: and then asking ourselves,
[45:35] SPEAKER: well, what if we didn't conform?
[45:36] SPEAKER: What if we said, let's take the 2000?
[45:38] SPEAKER: What now what does a 2000 era PC cost?
[45:41] SPEAKER: Oh, it costs five bucks or 10 bucks.
[45:43] SPEAKER: And so I like it for that.
[45:45] SPEAKER: And the projects you get within a very,
[45:47] SPEAKER: they're very kind of embedded.
[45:50] SPEAKER: It shows up in some of my favorite hobbyist projects
[45:52] SPEAKER: like the high altitude ballooning because it's very light.
[45:55] SPEAKER: It shows up in some of those projects.
[45:57] SPEAKER: So I do love it.
[45:58] SPEAKER: And we've sold a lot of them.
[45:59] SPEAKER: I mean, it's been, I don't know what the total numbers are
[46:03] SPEAKER: but it's probably three or 4 million.
[46:04] SPEAKER: Out of the 50 million,
[46:05] SPEAKER: roughly 50 million Raspberry Pis we've sold,
[46:07] SPEAKER: probably three or 4 million of them
[46:09] SPEAKER: have been these tiny little computers.
[46:11] SPEAKER: - It lives in kind of a fun spot
[46:13] SPEAKER: between like a microcontroller and a full blown PC, right?
[46:17] SPEAKER: - Yeah, and of course we've explored with Pico
[46:19] SPEAKER: which came out a couple of years ago,
[46:21] SPEAKER: which has our own Silicon on it.
[46:23] SPEAKER: It's the first product
[46:24] SPEAKER: that has Raspberry Pi designed Silicon on it.
[46:26] SPEAKER: But we kind of then have explored what does the world below
[46:29] SPEAKER: zero look like?
[46:30] SPEAKER: And we have this $4 Pico product and $6 Pico W product.
[46:34] SPEAKER: Just all trying to understand, how low can we take?
[46:38] SPEAKER: And then the sock, which you can also buy the microcontroller
[46:41] SPEAKER: from us and this is a 50 cent microcontroller.
[46:43] SPEAKER: So, how low can we take that general purpose
[46:46] SPEAKER: computing mission?
[46:47] SPEAKER: - One of the many things that's always fascinated me
[46:49] SPEAKER: about your efforts is how long old models
[46:51] SPEAKER: remain in production.
[46:52] SPEAKER: I mean, the Pi one and two you've committed through 2026
[46:56] SPEAKER: to keep making them.
[46:56] SPEAKER: I'm curious, when the supply constraints really kicked in,
[46:59] SPEAKER: I mean, everybody wants to buy the latest and greatest
[47:01] SPEAKER: of course, but like there's plenty of hobbyist projects
[47:03] SPEAKER: that run just fine on a three or a two,
[47:06] SPEAKER: or my old model B is still sitting here
[47:07] SPEAKER: doing something useful.
[47:09] SPEAKER: Did those old models being still in the channel,
[47:11] SPEAKER: did that take on kind of a renewed importance
[47:12] SPEAKER: when nobody could get fours and CM fours anymore?
[47:16] SPEAKER: Like did those have an uptick?
[47:18] SPEAKER: - It certainly helped that we had access
[47:20] SPEAKER: to two process notes.
[47:21] SPEAKER: So we had core Silicon across two process notes,
[47:24] SPEAKER: 40 nanometers for Pi three and earlier and 28 nanometers.
[47:28] SPEAKER: So you kind of, yeah,
[47:29] SPEAKER: being exposed to more process notes is good.
[47:31] SPEAKER: If I had my way,
[47:32] SPEAKER: I would have been exposed to three or four process notes,
[47:33] SPEAKER: but yeah, two was certainly better than one.
[47:35] SPEAKER: Yeah, we saw people migrating in both directions.
[47:38] SPEAKER: So we saw people driven by month to month
[47:40] SPEAKER: availability behavior.
[47:42] SPEAKER: So we saw people who were using Pi four era hardware
[47:46] SPEAKER: looking to see whether applications could be optimized
[47:49] SPEAKER: to run on early hardware.
[47:50] SPEAKER: We saw people who were using compute module three migrate.
[47:53] SPEAKER: We have a, we have a sort of a,
[47:55] SPEAKER: what's currently a pseudo product called the CM four S
[47:58] SPEAKER: compute module four S,
[47:59] SPEAKER: which is the brains of compute module four
[48:02] SPEAKER: in the compute module three form factor.
[48:04] SPEAKER: And that was developed before the pandemic
[48:06] SPEAKER: as a way to give people a migration path
[48:08] SPEAKER: up to the modern Silicon platform
[48:10] SPEAKER: without having to retool their baseboards.
[48:12] SPEAKER: But it actually ended up doing duty as a way for,
[48:16] SPEAKER: in the periods when we had better 28 nanometer availability
[48:19] SPEAKER: and the 40 nanometer availability,
[48:21] SPEAKER: it did duty as a way for people to get continuity of supply.
[48:25] SPEAKER: There's a product that it is on our,
[48:27] SPEAKER: it is a real and official Raspberry Pi product,
[48:30] SPEAKER: but it has never really been launched.
[48:32] SPEAKER: It's on our website, but it's never really been launched.
[48:35] SPEAKER: It's only been used as a sort of a tactical aid
[48:38] SPEAKER: to some of our industrial customers.
[48:41] SPEAKER: Yeah, it's been, it's interesting.
[48:42] SPEAKER: And even today, as I say, even today,
[48:44] SPEAKER: you're gonna see us come back into availability
[48:47] SPEAKER: and kind of broadly the order in which our products were launched.
[48:52] SPEAKER: So you're gonna see the older, the 3A+ come in,
[48:54] SPEAKER: you see 0W come in, and then probably a Pi 4
[48:58] SPEAKER: will be towards the end of the consumer,
[49:01] SPEAKER: unrestricted volume consumer availability.
[49:04] SPEAKER: Raspberry Pi 4 will probably be towards the end
[49:05] SPEAKER: of the transition.
[49:07] SPEAKER: - Are you all in on ARM for the foreseeable future?
[49:09] SPEAKER: Do you have any thoughts on RISC-V, for example,
[49:12] SPEAKER: which is making a lot of headlines as an open source
[49:15] SPEAKER: instruction set in the kind of the same embedded space?
[49:17] SPEAKER: - It's very hard for me not to be all in on ARM, right?
[49:19] SPEAKER: As somebody who spent his childhood drooling
[49:22] SPEAKER: over economic communities and as a former colleague
[49:25] SPEAKER: of Sophie Wilson, of course, who was responsible
[49:27] SPEAKER: for the design of that instruction set architecture.
[49:30] SPEAKER: It's very hard for me not to be all in on ARM.
[49:32] SPEAKER: I think RISC-V, RISC-V is an interesting development.
[49:35] SPEAKER: People, it's important not to understate the challenges
[49:39] SPEAKER: that a new instruction set architecture face
[49:42] SPEAKER: in terms of adoption.
[49:43] SPEAKER: There's an enormous amount of accumulated
[49:47] SPEAKER: invested engineering effort in the ARM architecture
[49:50] SPEAKER: and the Linux kernel and the various user lands
[49:55] SPEAKER: that run on top of it.
[49:56] SPEAKER: Optimization, so you go look at the FFmpeg source code,
[49:59] SPEAKER: a huge number of neon optimizations for 32 and 64-bit ARM.
[50:04] SPEAKER: Actually, that accumulated base of engineering investment
[50:07] SPEAKER: pales in comparison to the even more enormous level
[50:10] SPEAKER: investment in the Intel architecture.
[50:12] SPEAKER: If you go to some of these places,
[50:14] SPEAKER: you find fast paths for everything from NNX to SSE,
[50:18] SPEAKER: to SSE2, onwards, right?
[50:20] SPEAKER: A whole museum of Intel multimedia instructions.
[50:24] SPEAKER: So, and that stuff that needs to be replicated
[50:27] SPEAKER: in the RISC-V space.
[50:28] SPEAKER: It's not to say it won't be replicated there,
[50:29] SPEAKER: but it does need to be replicated
[50:31] SPEAKER: and that would be a necessary precursor
[50:34] SPEAKER: to us being able to do any sort
[50:35] SPEAKER: of RISC-V based Raspberry Pi product.
[50:37] SPEAKER: So I'm very satisfied with the ARM architecture
[50:41] SPEAKER: is the ARM ecosystem is quite a good place to hang out.
[50:46] SPEAKER: And it's notable that other,
[50:48] SPEAKER: quite a lot of other computer companies
[50:50] SPEAKER: have chosen to go hang out there recently.
[50:51] SPEAKER: And just as the Linux kernel provides a venue
[50:56] SPEAKER: for cooperative collaborative innovation.
[50:58] SPEAKER: So, the ARM instruction set and the various cores
[51:02] SPEAKER: that you can license that execute that instruction set,
[51:05] SPEAKER: they provide the house a similar sort of,
[51:08] SPEAKER: it's a similar environment.
[51:09] SPEAKER: And so there's a similar source of scale advantage.
[51:12] SPEAKER: So it's gonna be interesting to see what happens
[51:13] SPEAKER: with RISC-V.
[51:14] SPEAKER: I think in the microcontroller space,
[51:16] SPEAKER: those advantages are much less pronounced.
[51:19] SPEAKER: And I think where you do see penetration
[51:21] SPEAKER: and I think you'll continue to see penetration
[51:23] SPEAKER: of the RISC-V instruction set architecture
[51:25] SPEAKER: is in microcontrollers and deep embedded.
[51:27] SPEAKER: - Okay, I was gonna say,
[51:28] SPEAKER: one of the things we talk about on the FOSS pod a lot
[51:30] SPEAKER: with smaller projects is funding
[51:33] SPEAKER: and the organization of the, of the organization.
[51:36] SPEAKER: How the business of making these large open source projects
[51:39] SPEAKER: works and I'm, I mean, I think the funding
[51:42] SPEAKER: is probably pretty obvious,
[51:43] SPEAKER: but I bet there's probably stuff
[51:44] SPEAKER: that people don't understand.
[51:45] SPEAKER: And I'm curious what the organizational structure is like
[51:47] SPEAKER: and what your kind of day-to-day involvement
[51:49] SPEAKER: and what your job started as and how it, what it is now.
[51:54] SPEAKER: - The, so the funding, the funding is interesting.
[51:57] SPEAKER: The foundations are Topco's a charity.
[51:59] SPEAKER: The thing I run is Raspberry Pi Limited.
[52:02] SPEAKER: So I run the engineering subsidiary of the foundation.
[52:05] SPEAKER: And so we do the engineer, if you buy Raspberry Pi computer,
[52:07] SPEAKER: it was designed by us and the software was written,
[52:10] SPEAKER: the Raspberry Pi specific bits of software written by us
[52:12] SPEAKER: and the brand is maintained by us.
[52:14] SPEAKER: So we do that bit and then we make money
[52:17] SPEAKER: and then we give that money.
[52:18] SPEAKER: So we reinvest some of the money
[52:19] SPEAKER: in making the Raspberry Pi stuff
[52:21] SPEAKER: and then we give the surplus money
[52:22] SPEAKER: to the foundation that does educational things with it.
[52:25] SPEAKER: And we've returned on the order of 35 million pounds,
[52:28] SPEAKER: I think over the years to the foundation
[52:30] SPEAKER: to fund its educational, its educational work.
[52:32] SPEAKER: So that's the kind of structure.
[52:34] SPEAKER: Where did the money come from in the first place?
[52:35] SPEAKER: A handful of us put money in,
[52:37] SPEAKER: I think we put in about a hundred thousand.
[52:40] SPEAKER: The founding trustees of the foundation
[52:43] SPEAKER: lent the foundation about a hundred thousand pounds
[52:45] SPEAKER: between us, actually for a period of very few months.
[52:48] SPEAKER: And then those loans were then repaid.
[52:50] SPEAKER: So that's for the initial capital.
[52:51] SPEAKER: And actually until 2000 until 2021,
[52:56] SPEAKER: that was until the autumn of 2021,
[52:57] SPEAKER: that was the only money that had gone into Raspberry Pi.
[53:00] SPEAKER: So the whole of Raspberry Pi was bootstrapped off that money
[53:04] SPEAKER: and probably about 30 or 40,000 pounds of donations
[53:07] SPEAKER: from high net worth individuals in Cambridge
[53:09] SPEAKER: who thought it was a good idea.
[53:11] SPEAKER: So that's kind of fun.
[53:13] SPEAKER: And then we did a $45 million funding round
[53:15] SPEAKER: in the autumn of 2021.
[53:18] SPEAKER: A couple of absolutely fantastic supporters of ours
[53:21] SPEAKER: put in $45 million into the trading business,
[53:24] SPEAKER: effectively bought new shares in the trading business
[53:26] SPEAKER: and the trading business then ceases to be a hostel
[53:28] SPEAKER: very much a majority owned subsidiary of the foundation,
[53:31] SPEAKER: but no longer a wholly owned subsidiary.
[53:33] SPEAKER: But that's the only external money
[53:35] SPEAKER: we've actually brought in.
[53:36] SPEAKER: It turns out how my job has evolved,
[53:38] SPEAKER: I guess it's evolved from kind of overseeing everything,
[53:42] SPEAKER: every aspect of Raspberry Pi early on
[53:44] SPEAKER: through to very much that focus on the commercial
[53:46] SPEAKER: and engineering side of it, which is natural for me
[53:49] SPEAKER: 'cause I'm a software engineer originally,
[53:51] SPEAKER: I'm a chip engineer subsequently.
[53:54] SPEAKER: And so kind of having the opportunity really to focus in
[53:58] SPEAKER: on that aspect of things has been great.
[54:01] SPEAKER: We found ourselves a fantastic chief executive
[54:03] SPEAKER: for the foundation, Philip Colligan,
[54:04] SPEAKER: who poached from Nesta, the National Endowment
[54:06] SPEAKER: for Science, Technology and the Arts in the UK.
[54:09] SPEAKER: He was deputy chief executive at Nesta
[54:10] SPEAKER: and he joined us in 2015.
[54:13] SPEAKER: I think he was about for the kind of the early years
[54:15] SPEAKER: of Raspberry Pi actually, the engineering function was big
[54:18] SPEAKER: and the charitable function was small.
[54:20] SPEAKER: And so Philip was probably only at that point
[54:22] SPEAKER: about the fourth employee here of the foundation
[54:26] SPEAKER: and then grew that very, very quickly
[54:28] SPEAKER: through both organic growth and acquisition
[54:30] SPEAKER: to about 150 or organic growth and merger
[54:33] SPEAKER: to about 150 people.
[54:34] SPEAKER: So that's the foundation to us.
[54:36] SPEAKER: The headcount's now rather bigger than us.
[54:38] SPEAKER: And he stayed with us, I mean, he's been with us,
[54:40] SPEAKER: he will have been with us eight years this year
[54:42] SPEAKER: and he's transformed it into,
[54:45] SPEAKER: I think he's transformed the foundation into something
[54:47] SPEAKER: that we didn't envisage when we started.
[54:52] SPEAKER: The existence of the Raspberry Pi computer
[54:53] SPEAKER: was supposed to be the contribution, right?
[54:55] SPEAKER: When now we have a foundation, which obviously
[54:58] SPEAKER: we continue to ensure the Raspberry Pi computers exist,
[55:01] SPEAKER: but the foundation does much more.
[55:03] SPEAKER: Conventional is kind of conventional is not the way.
[55:05] SPEAKER: Conventional sounds disparaging,
[55:06] SPEAKER: it's not really the right word,
[55:08] SPEAKER: but they do much more regular charitable,
[55:11] SPEAKER: the sorts of things you would imagine
[55:12] SPEAKER: that educational charity would do.
[55:14] SPEAKER: They train teachers and they create,
[55:15] SPEAKER: they train teachers and they run clubs
[55:17] SPEAKER: and they create courseware and things like that.
[55:20] SPEAKER: And so it's kind of wonderful to have
[55:21] SPEAKER: both that original strand of the kind of anarchic strand
[55:24] SPEAKER: of just making sure general purpose computing is everywhere
[55:26] SPEAKER: and then also to take some of the money you've made from that
[55:28] SPEAKER: and then go and do more traditional interventions
[55:31] SPEAKER: in the space.
[55:32] SPEAKER: - But for the most part, the day-to-day
[55:33] SPEAKER: of both the charity and the charitable foundation
[55:36] SPEAKER: and the trading company are funded
[55:38] SPEAKER: by obviously sales of hardware, right?
[55:40] SPEAKER: - Yes, that's right, yes, yes, which is cool, right?
[55:44] SPEAKER: We made a lot, we sold 50 million computers
[55:46] SPEAKER: and we don't make very much money when we sell out,
[55:48] SPEAKER: we don't make very much profit when we sell a Raspberry Pi,
[55:50] SPEAKER: but if you sell 50 million of them,
[55:52] SPEAKER: then you do make a bit of money.
[55:54] SPEAKER: - I was gonna say like the idea,
[55:55] SPEAKER: like it sounds like a lot of money
[55:56] SPEAKER: when we talk about it in normal human terms,
[55:58] SPEAKER: but the idea that you bootstrapped a company
[56:00] SPEAKER: that sold 50 million computers on $100,000
[56:03] SPEAKER: is kind of shocking, right?
[56:05] SPEAKER: Like it's an incredible thing.
[56:07] SPEAKER: - I mean, to some extent it's a testament
[56:09] SPEAKER: to the business model.
[56:10] SPEAKER: For the longest time we were a licensing company,
[56:12] SPEAKER: so we're taking a leaf actually out of arms book.
[56:15] SPEAKER: We designed the Raspberry Pi
[56:18] SPEAKER: and we licensed that design
[56:20] SPEAKER: and the use of the Raspberry Pi brand
[56:22] SPEAKER: and obviously the community behind it
[56:25] SPEAKER: to two partners who then made Raspberry Pis
[56:27] SPEAKER: and paid us a royalty.
[56:30] SPEAKER: And the nice thing about that business
[56:31] SPEAKER: is as you grow a traditional manufacturing business,
[56:33] SPEAKER: you kind of see it sucks capital in
[56:35] SPEAKER: because you need to fund inventory.
[56:37] SPEAKER: Your, as we call the working capital loop expands,
[56:42] SPEAKER: you need to fund all of that inventory,
[56:45] SPEAKER: component inventory, finished goods inventory,
[56:47] SPEAKER: receivables waiting for your customers to pay.
[56:49] SPEAKER: You need money as your business gets bigger,
[56:51] SPEAKER: so you suck capital in.
[56:53] SPEAKER: Because we were a licensing company,
[56:55] SPEAKER: the unit economics were a little bit less good
[56:56] SPEAKER: 'cause you're only getting a royalty
[56:57] SPEAKER: rather than getting the full margin on the product.
[57:01] SPEAKER: But it does mean you don't need to suck money in
[57:02] SPEAKER: and that's why the foundation was able
[57:04] SPEAKER: to retain 100% ownership of Raspberry Pi limited
[57:07] SPEAKER: while it grew and thus we're able
[57:10] SPEAKER: to devote all of the entirety of the spare money,
[57:13] SPEAKER: the entirety of the surplus profit.
[57:15] SPEAKER: We were able to devote the entirety of that
[57:17] SPEAKER: to funding the foundation rather than having to share it
[57:20] SPEAKER: between the foundation and people who had come in over time
[57:23] SPEAKER: to contribute capital to the growth of the organization.
[57:25] SPEAKER: - So then that raise in 2021 was to transition
[57:29] SPEAKER: off of the licensing?
[57:30] SPEAKER: - It was certainly to transition to more of a blended model.
[57:33] SPEAKER: We are a much more blended organization now.
[57:35] SPEAKER: So certainly last year, really a substantial majority
[57:39] SPEAKER: of Raspberry Pi computers were actually made by us
[57:41] SPEAKER: or we commissioned the manufacturing.
[57:43] SPEAKER: Nobody makes anything right.
[57:44] SPEAKER: So we paid some people to make it for us.
[57:46] SPEAKER: But yeah, it was a traditional company
[57:48] SPEAKER: with us inside the working capital.
[57:50] SPEAKER: That's obviously capital intensive.
[57:51] SPEAKER: Also a certain amount of that money has obviously gone
[57:53] SPEAKER: to pay for sort of advanced R&D stuff
[57:56] SPEAKER: because of course we continue to try
[57:57] SPEAKER: to make cool new Raspberry Pi things and that's not cheap.
[58:00] SPEAKER: - It's kind of remarkable to me to just sit here
[58:02] SPEAKER: listening to you talk about this
[58:03] SPEAKER: because 50 million units in a decade is a number
[58:06] SPEAKER: that any kind of publicly traded corporation
[58:08] SPEAKER: would salivate over, right?
[58:09] SPEAKER: But yeah, you're working with pretty thin profit margins.
[58:12] SPEAKER: The money mostly is going back into like fairly noble
[58:15] SPEAKER: kind of educational outreach and so forth.
[58:17] SPEAKER: I mean, I don't really have a question here.
[58:19] SPEAKER: It's just kind of, this is almost like a unicorn
[58:21] SPEAKER: of an operation to see something at this scale
[58:24] SPEAKER: that is not trying to maximize shareholder value constantly.
[58:27] SPEAKER: - It's great, right?
[58:28] SPEAKER: It's a wonderful, and most of us who are involved
[58:30] SPEAKER: in Raspberry Pi have had some sort of business experience
[58:32] SPEAKER: before, a more traditional business experience.
[58:34] SPEAKER: So I think for all of us, it's kind of been a wonderful toy,
[58:39] SPEAKER: I guess, just this experience that no one's built
[58:43] SPEAKER: an organization like this before.
[58:45] SPEAKER: And it's interesting to see how far we can take it.
[58:47] SPEAKER: I mean, we've sold 50 million computers.
[58:48] SPEAKER: We fab our own chips.
[58:50] SPEAKER: In fact, again, nobody fabs their own chips.
[58:51] SPEAKER: We pay people to fab our own chips.
[58:52] SPEAKER: We design our own chips.
[58:53] SPEAKER: - You design your own chips.
[58:54] SPEAKER: - And then TSMC fab them for us.
[58:57] SPEAKER: - Just like Apple.
[58:58] SPEAKER: - Yeah, just like everybody else.
[59:00] SPEAKER: And it's kind of interesting to see the breadth
[59:05] SPEAKER: of what you can do within this interestingly constrained
[59:10] SPEAKER: environment.
[59:11] SPEAKER: - Yeah, I think you're probably uniquely positioned
[59:13] SPEAKER: to know more about what people are using Pi's for
[59:16] SPEAKER: than pretty much most anybody we would talk to.
[59:19] SPEAKER: And I'm curious if there are any things
[59:21] SPEAKER: that you were really excited about.
[59:22] SPEAKER: I think you mentioned high altitude ballooning a minute ago.
[59:24] SPEAKER: - The hab stuff's great.
[59:25] SPEAKER: I love the space stuff in general.
[59:27] SPEAKER: So I love our own Astro Pi program
[59:29] SPEAKER: where we've put Pi's on the station
[59:31] SPEAKER: for kids to run the code on.
[59:33] SPEAKER: A lot of European children in Europe have done that.
[59:36] SPEAKER: It's a European space agency collaboration.
[59:39] SPEAKER: So that's a fun one.
[59:40] SPEAKER: I love that actually,
[59:42] SPEAKER: although there are two Astro Pi's on the space station,
[59:46] SPEAKER: there's a bunch more, there are on it at any given day,
[59:48] SPEAKER: a huge number more Raspberry Pi's on the ISS
[59:50] SPEAKER: because they get used as payload controllers
[59:52] SPEAKER: because they're very robust.
[59:54] SPEAKER: And so often actually we have no idea
[59:56] SPEAKER: how many Raspberry Pi's there are on the ISS.
[59:57] SPEAKER: We only tend to find out about these uses
[59:59] SPEAKER: when they get down mast, so that's kind of fun.
[1:00:04] SPEAKER: What else?
[1:00:05] SPEAKER: I just like all the people who've built businesses around it.
[1:00:08] SPEAKER: Whether they're resellers
[1:00:09] SPEAKER: or people who make DAC accessories
[1:00:13] SPEAKER: or people who've built it into some product
[1:00:17] SPEAKER: that they've dreamt up.
[1:00:19] SPEAKER: Just this idea of enabling entrepreneurship,
[1:00:22] SPEAKER: enabling distributed, I love this.
[1:00:25] SPEAKER: I think entrepreneurship, capitalism, business,
[1:00:27] SPEAKER: they're wonderfully powerful tools
[1:00:29] SPEAKER: for good change in the world.
[1:00:31] SPEAKER: And it's wonderful to have had the opportunity
[1:00:33] SPEAKER: to kind of unlock that kind of innovation,
[1:00:35] SPEAKER: which it was getting hard to do, right?
[1:00:37] SPEAKER: You know, was able to walk down to an electronics store
[1:00:41] SPEAKER: and get 6502 out of a bin for about the same price
[1:00:46] SPEAKER: that the biggest company in the world
[1:00:47] SPEAKER: would have paid for a 6502, right?
[1:00:49] SPEAKER: It was a very level playing field in the 1970s and 1980s.
[1:00:52] SPEAKER: And the playing field is not level at all anymore
[1:00:54] SPEAKER: in terms of access to advanced technology.
[1:00:56] SPEAKER: It's very hard, it's not that advanced technology is expensive
[1:00:59] SPEAKER: for some of these companies.
[1:01:00] SPEAKER: It's just unavailable.
[1:01:01] SPEAKER: And so taking really advanced technology
[1:01:03] SPEAKER: and making it available at a very flat price.
[1:01:06] SPEAKER: You know, one thing that characterizes Raspberry Pi
[1:01:08] SPEAKER: is not just the thin margins,
[1:01:09] SPEAKER: but the very flat pricing structure.
[1:01:11] SPEAKER: So people come to us and say, "Oh, so Raspberry Pi is $35.
[1:01:14] SPEAKER: How much will I have to pay for 1,000 Raspberry Pis?"
[1:01:18] SPEAKER: And the answer is $35,000.
[1:01:21] SPEAKER: We know you'll eke out 1,000, it might be $34,000,
[1:01:25] SPEAKER: but it's not $25,000 or $15,000.
[1:01:28] SPEAKER: And that's something that's a commitment
[1:01:31] SPEAKER: we've stayed very true to all the way through.
[1:01:33] SPEAKER: And I think it's obviously important
[1:01:35] SPEAKER: from the educational side,
[1:01:37] SPEAKER: 'cause it means that the people
[1:01:39] SPEAKER: who are at the bottom end of the volume curve are kids.
[1:01:42] SPEAKER: So you don't want to be rinsing the kids.
[1:01:44] SPEAKER: But it's also the thing that's powered
[1:01:46] SPEAKER: this kind of community,
[1:01:47] SPEAKER: this ecosystem of innovation around the platform.
[1:01:50] SPEAKER: - Well, and just so people understand,
[1:01:52] SPEAKER: I mean, when you look at what Intel or Apple
[1:01:55] SPEAKER: or Nvidia spend developing a new chip,
[1:01:58] SPEAKER: they're looking at billions of dollars, in some case,
[1:02:00] SPEAKER: over a really long period of time.
[1:02:02] SPEAKER: And I'm curious what your,
[1:02:04] SPEAKER: like when you're developing a new Pi model,
[1:02:05] SPEAKER: part of it is that you license arms,
[1:02:07] SPEAKER: so you get a lot of stuff with that licensing cost.
[1:02:09] SPEAKER: But I'm curious what you spend developing a new Pi model
[1:02:12] SPEAKER: and what that-
[1:02:13] SPEAKER: - Well, remember most big Raspberry Pi products
[1:02:16] SPEAKER: use merchant silicon,
[1:02:17] SPEAKER: well, use effectively merchant silicon.
[1:02:19] SPEAKER: So we don't develop the chips
[1:02:20] SPEAKER: that are in the big Raspberry Pis, right?
[1:02:22] SPEAKER: That's protocol.
[1:02:23] SPEAKER: So we're not involved in that.
[1:02:25] SPEAKER: When we do the,
[1:02:26] SPEAKER: but just doing the, our bit of that work is,
[1:02:30] SPEAKER: there's many millions of dollars now.
[1:02:31] SPEAKER: So Raspberry Pi 4 was,
[1:02:34] SPEAKER: I mean, I could go and look it up,
[1:02:36] SPEAKER: but Raspberry Pi 4 was probably
[1:02:37] SPEAKER: a two or $3 million program.
[1:02:38] SPEAKER: Raspberry Pi Pico was probably
[1:02:41] SPEAKER: a seven or $8 million program
[1:02:42] SPEAKER: because that did have a chip development in it, right?
[1:02:45] SPEAKER: So that has the RP 2040 microcontroller wrapped up in it.
[1:02:48] SPEAKER: So it's probably RP 2040 is about a $5 million program
[1:02:50] SPEAKER: just on its own.
[1:02:51] SPEAKER: And then you have the board development
[1:02:53] SPEAKER: and the software development on top of that.
[1:02:55] SPEAKER: So it's only getting more expensive.
[1:02:56] SPEAKER: I would imagine, you know, we are,
[1:02:58] SPEAKER: we've kind of taken a pause on new big Raspberry Pis
[1:03:00] SPEAKER: because of the, well,
[1:03:02] SPEAKER: we focus on just making the existing Raspberry Pis available,
[1:03:04] SPEAKER: but I would imagine that any subsequent Raspberry Pi
[1:03:06] SPEAKER: will be a, would be a more than $10 million effort,
[1:03:10] SPEAKER: even without us, you know, even, you know,
[1:03:13] SPEAKER: without a chip development in.
[1:03:15] SPEAKER: - I guess what I'm getting at though,
[1:03:16] SPEAKER: is that the benefit of having the Raspberry Pi
[1:03:18] SPEAKER: as this, as this unit of compute and SOC
[1:03:21] SPEAKER: that you can jam into your projects,
[1:03:22] SPEAKER: is that if you want to build a project
[1:03:25] SPEAKER: that needs a general purpose computer,
[1:03:27] SPEAKER: you don't need to do that work and effort.
[1:03:29] SPEAKER: You can just say, okay,
[1:03:30] SPEAKER: we have this thing that has these ins and outs
[1:03:32] SPEAKER: and jam it into the thing that you want to build.
[1:03:34] SPEAKER: And it's a lot more accessible to the smaller market.
[1:03:37] SPEAKER: - Yeah, we have this,
[1:03:38] SPEAKER: we have this idea of reluctant hardware companies
[1:03:42] SPEAKER: that actually the world was full of reluctant hardware
[1:03:44] SPEAKER: companies when we started as a digital signage companies,
[1:03:47] SPEAKER: thin client companies,
[1:03:49] SPEAKER: people building widgets to go into factories to log data.
[1:03:52] SPEAKER: And all these people who were really software companies,
[1:03:55] SPEAKER: they all wanted to be software companies.
[1:03:56] SPEAKER: What they're differentiating value
[1:03:58] SPEAKER: was in whatever software stack it was that they provided.
[1:04:01] SPEAKER: But in order to get that software stack,
[1:04:02] SPEAKER: you can't sell people software.
[1:04:04] SPEAKER: These are something to run on.
[1:04:05] SPEAKER: And the PC was too expensive
[1:04:07] SPEAKER: and there weren't readily available,
[1:04:09] SPEAKER: embedded PCs at a respectable price point.
[1:04:12] SPEAKER: And therefore people were building a little thin client,
[1:04:14] SPEAKER: going to do all the work of going out and sourcing,
[1:04:17] SPEAKER: causing a look at a memory and bringing up a board,
[1:04:19] SPEAKER: writing a board support and getting an OS port
[1:04:22] SPEAKER: just so they get to the point
[1:04:23] SPEAKER: where they could then run their application,
[1:04:24] SPEAKER: which was there.
[1:04:25] SPEAKER: And that's just so much wasted effort.
[1:04:27] SPEAKER: And that's really the, yeah.
[1:04:29] SPEAKER: What I'm proudest of,
[1:04:30] SPEAKER: I think with Raspberry Pi's contribution there
[1:04:33] SPEAKER: is that we freed a whole heap of companies.
[1:04:35] SPEAKER: And so I talked about the boat tail.
[1:04:37] SPEAKER: Now, actually, you'll see a thin client on a desktop
[1:04:40] SPEAKER: and you look at it and it's got a boat tail on the end
[1:04:42] SPEAKER: 'cause it's actually a Raspberry Pi in a fancy box
[1:04:44] SPEAKER: running somebody's differentiating software application.
[1:04:46] SPEAKER: And that suit the kind of contribution to the public good,
[1:04:51] SPEAKER: not having thousands of talented engineers wasted
[1:04:55] SPEAKER: doing basically undifferentiated grunt hardware design
[1:04:59] SPEAKER: is really, it's a good contribution.
[1:05:01] SPEAKER: And I think ranks actually probably alongside
[1:05:04] SPEAKER: in terms of what those engineers can do
[1:05:06] SPEAKER: now they're freed up,
[1:05:08] SPEAKER: probably ranks alongside the educational impact
[1:05:12] SPEAKER: as in terms of good done by Raspberry Pi.
[1:05:15] SPEAKER: - So I had a big last grand question
[1:05:17] SPEAKER: and you've kind of actually alluded to an answer already,
[1:05:19] SPEAKER: but I wanted to ask what emotion do you feel
[1:05:21] SPEAKER: when you hear the words Raspberry Pi 5?
[1:05:25] SPEAKER: - Terror.
[1:05:27] SPEAKER: Sadness, sadness in that the sort of progress
[1:05:32] SPEAKER: towards Raspberry Pi 5 has been derailed
[1:05:34] SPEAKER: by all of the challenges,
[1:05:37] SPEAKER: pandemic and post-pandemic that have confronted us.
[1:05:41] SPEAKER: I mean, obviously one day there will be a Raspberry Pi 5.
[1:05:43] SPEAKER: We've told people it's not this year and it isn't this year.
[1:05:46] SPEAKER: I think once we get back into our traditional
[1:05:51] SPEAKER: super robust stock position for Raspberry Pi 4,
[1:05:53] SPEAKER: we'll be in a position to think about it,
[1:05:54] SPEAKER: but it is some distance away.
[1:05:56] SPEAKER: These, as I say, they're not cheap programs
[1:05:58] SPEAKER: and the fact they're not cheap
[1:06:00] SPEAKER: implies that they're not quick
[1:06:01] SPEAKER: 'cause it takes time to spend that much money,
[1:06:03] SPEAKER: but we'll get there.
[1:06:04] SPEAKER: And we're lucky that this happened to us
[1:06:06] SPEAKER: when Raspberry Pi 4 was the flagship platform
[1:06:10] SPEAKER: not Raspberry Pi 3, 'cause of course Raspberry Pi 4
[1:06:11] SPEAKER: is enormously more performant
[1:06:13] SPEAKER: and has a lot more headroom in terms of how much
[1:06:17] SPEAKER: more performance we can eke out of it
[1:06:19] SPEAKER: by clever software optimization.
[1:06:21] SPEAKER: - That was kind of my follow-up question.
[1:06:22] SPEAKER: The 4 to me is kind of the first,
[1:06:25] SPEAKER: I shouldn't say real Pi, but like real computer.
[1:06:27] SPEAKER: You know what I mean?
[1:06:28] SPEAKER: It's a quad core, like good IPC,
[1:06:29] SPEAKER: like it finally has full speed ethernet and all that stuff.
[1:06:31] SPEAKER: I mean, in a world with no pandemic,
[1:06:33] SPEAKER: do you think the Pi 4 would have lasted longer
[1:06:35] SPEAKER: than its predecessors even without all the external factors?
[1:06:39] SPEAKER: - Yes, yes, absolutely.
[1:06:40] SPEAKER: It's the first one that delivered
[1:06:41] SPEAKER: on our dream really of a no compromises.
[1:06:45] SPEAKER: You can sit down and we had people, lots of kids did.
[1:06:47] SPEAKER: I mean, we had a lot of charitable work
[1:06:48] SPEAKER: getting these out to people in the pandemic.
[1:06:51] SPEAKER: It's the first one that you can sit down in front of
[1:06:54] SPEAKER: and use as a no compromises entry-level PC.
[1:06:59] SPEAKER: You're not gonna run a big CAD package on it,
[1:07:01] SPEAKER: but you can run a web browser on it.
[1:07:04] SPEAKER: And so it was good that that came along.
[1:07:07] SPEAKER: It's good that was available.
[1:07:08] SPEAKER: And obviously Pi 4 and then Pi 400 during the pandemic.
[1:07:11] SPEAKER: And it was one of the things that sort of sustained me
[1:07:14] SPEAKER: when I was locked in my house
[1:07:15] SPEAKER: was all the pictures of kids getting their Pi 4
[1:07:18] SPEAKER: and then Pi 400 kits.
[1:07:21] SPEAKER: These kids who, you know, we have so many,
[1:07:22] SPEAKER: it was such a crime.
[1:07:28] SPEAKER: Sending all the kids in the country home to work from home
[1:07:32] SPEAKER: and forgetting that huge numbers.
[1:07:36] SPEAKER: I think it was 700,000 households in the UK
[1:07:38] SPEAKER: had kids, but no general purpose computer was just...
[1:07:42] SPEAKER: I mean, it didn't create the inequality.
[1:07:45] SPEAKER: It made us all, it reminded us all the inequality was there.
[1:07:48] SPEAKER: And so to the extent that we were able to get units out
[1:07:50] SPEAKER: to a few tens of thousands,
[1:07:52] SPEAKER: we have some great philanthropic support.
[1:07:54] SPEAKER: We're able to get a few tens of thousands of units out
[1:07:56] SPEAKER: to kids mostly in the UK.
[1:07:58] SPEAKER: Just the looks on their faces when they opened the box
[1:08:00] SPEAKER: and it was a computer inside was amazing.
[1:08:02] SPEAKER: - I think there's no better place
[1:08:03] SPEAKER: to wrap it up than that, Eben.
[1:08:06] SPEAKER: If people want to find out more,
[1:08:07] SPEAKER: what are the best places to find you?
[1:08:10] SPEAKER: - So raspberrypi.com for Raspberry Pi limited stuff.
[1:08:15] SPEAKER: So engineering and products, raspberrypi.org
[1:08:20] SPEAKER: for the Raspberry Pi Foundation
[1:08:21] SPEAKER: and all that good educational work.
[1:08:27] SPEAKER: - That'll do it for us this week.
[1:08:28] SPEAKER: Thanks everybody for listening.
[1:08:30] SPEAKER: Thanks to Eben for coming by and chatting with us
[1:08:32] SPEAKER: and being extremely generous with his time.
[1:08:34] SPEAKER: I know he's always really busy.
[1:08:36] SPEAKER: - Yes, it was a joy, honestly.
[1:08:37] SPEAKER: I mean, I thoroughly enjoyed every interview
[1:08:39] SPEAKER: we've done for the show,
[1:08:40] SPEAKER: but the Raspberry Pi phenomenon has gotten so big
[1:08:44] SPEAKER: that it was a real honor to get to talk to him
[1:08:46] SPEAKER: and see that he's still an engineer at heart.
[1:08:48] SPEAKER: I mean, you never take that out of,
[1:08:50] SPEAKER: no matter how busy he is with other business
[1:08:53] SPEAKER: and foundation stuff,
[1:08:54] SPEAKER: being able to get into the weeds on a technical level
[1:08:56] SPEAKER: with him about the stuff that we talked about
[1:08:58] SPEAKER: was just super gratifying.
[1:09:00] SPEAKER: - Well, it's interesting to see
[1:09:01] SPEAKER: that he still seemed a little surprised
[1:09:04] SPEAKER: that it's become this kind of juggernaut, right?
[1:09:07] SPEAKER: Which is fun.
[1:09:09] SPEAKER: I often tell people that my favorite part about this show
[1:09:11] SPEAKER: is talking to people in different stages
[1:09:13] SPEAKER: of the open source software lifecycle.
[1:09:15] SPEAKER: And in this case, this is a hardware project
[1:09:17] SPEAKER: that is barely 10 years old at this point,
[1:09:20] SPEAKER: a little bit more than 10 years old,
[1:09:21] SPEAKER: and is contributing greatly
[1:09:23] SPEAKER: to a massive number of sectors around the world,
[1:09:28] SPEAKER: far beyond what I think they ever anticipated.
[1:09:30] SPEAKER: So you can find out more about Raspberry Pi
[1:09:32] SPEAKER: at raspberrypi.org for the foundation
[1:09:34] SPEAKER: or raspberrypi.com for the board.
[1:09:38] SPEAKER: And that's Pi, like the number 3.14,
[1:09:41] SPEAKER: not the thing that you put in your mouth.
[1:09:44] SPEAKER: - It's Pi, not P-I-E.
[1:09:45] SPEAKER: - The other thing I will say is the thing we talked about
[1:09:46] SPEAKER: where Raspberry Pi 3s are now becoming more available,
[1:09:51] SPEAKER: we are starting to see that happen in the real world again.
[1:09:55] SPEAKER: So that's, if you want to get a Pi,
[1:09:57] SPEAKER: you don't necessarily, F4s are great.
[1:10:00] SPEAKER: If you can't get a 4 at the real price,
[1:10:02] SPEAKER: a 3 is fine for most of the projects
[1:10:04] SPEAKER: that we've talked about on this show
[1:10:05] SPEAKER: and on the tech pod in the past.
[1:10:07] SPEAKER: - A 3 is no slouch, you know,
[1:10:08] SPEAKER: even if you've got an old 1 or a 2 lying around,
[1:10:10] SPEAKER: those have their uses as well.
[1:10:13] SPEAKER: - Yeah, so this week's episode, as always,
[1:10:15] SPEAKER: is brought to you by Google Open Source.
[1:10:16] SPEAKER: They bring all the power of open source to Google
[1:10:18] SPEAKER: and all the power of Google to open source.
[1:10:20] SPEAKER: You can find out more about them
[1:10:22] SPEAKER: at opensource.google, thanks Google.
[1:10:24] SPEAKER: As always, this week's episode was produced by Matt Purdy
[1:10:27] SPEAKER: and edited by Sabrina Hill, thanks Matt and Sabrina.
[1:10:29] SPEAKER: And we will be back in a couple of weeks
[1:10:31] SPEAKER: with another episode.
[1:10:32] SPEAKER: I think we're gonna talk about KiCad on the next one.
[1:10:34] SPEAKER: - Mm-hmm, we are.
[1:10:36] SPEAKER: - See you all then.
