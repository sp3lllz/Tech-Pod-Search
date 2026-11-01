---
episode: 35
title: 34: My Other Computer Is a Datacenter
date: 2020-05-10
guests: none
duration: 1:03:36
---

[00:00] SPEAKER: I love this mug you sent me.
[00:01] SPEAKER: I'm glad you like it. It was the biggest handle I had.
[00:05] SPEAKER: Look, you told me - so you gave me a mug in January when I was in Chicago and saw you and you said,
[00:10] SPEAKER: "Hey, put this in your hand and feel it." And it was literally the first time anybody had ever
[00:14] SPEAKER: said that I should think about how a mug fits in my hand and I didn't - like, I'd never considered
[00:20] SPEAKER: it before. I'd always just bought the mug that had the picture on it that I wanted and I was
[00:27] SPEAKER: absolutely heartbroken when I dropped a pole on it a few months ago and it broke. So I was stoked to
[00:32] SPEAKER: get a fresh big handle bad boy here with a lovely blue glaze. So...
[00:38] SPEAKER: A lot of potters hate handles. They hate making them because they can be tricky. And I always,
[00:44] SPEAKER: when I first started, focused on form. I focused on, like, what looks pretty or has a nice negative
[00:51] SPEAKER: space or whatever the other - and never really thought about, like, how it felt in my hand.
[00:56] SPEAKER: And then I was studying under this potter a year and a half ago, two years ago, and she's like,
[01:01] SPEAKER: "All right, we're going to do handles. We're going to make handles for an hour straight and just
[01:05] SPEAKER: attach them to a bucket. Like, just do anything to keep making handles." And I think I made 43
[01:10] SPEAKER: handles in an hour. Like, I just motored through them. And you could clearly look at the first five
[01:16] SPEAKER: which was garbage, but the last five were just like, yeah, it's starting to get there. It's kind
[01:20] SPEAKER: of neat. And then I started to think about, like, really what makes it feel like it's hugging your
[01:24] SPEAKER: fingers. The mug hugs your fingers.
[01:54] SPEAKER: - Welcome to Brad and Will Made a Tech Pod. I'm Will. Brad, unfortunately, well, he's here.
[02:02] SPEAKER: He's listening. But he had some surgery this week and his head is packed full of gauze. So
[02:08] SPEAKER: rather than talk to us and make us hear the horrible non-dulcet tones of Brad's gauze-packed
[02:15] SPEAKER: nose, I'm here with my pal, Brian Fitzpatrick, of TOC, but formerly of Google and a bunch of
[02:23] SPEAKER: other stuff that we'll get to. And we're gonna talk about some old technology. Fitz,
[02:27] SPEAKER: welcome to the show. Hello. - Thanks. Thanks for having me. Good to see you. Good to catch
[02:31] SPEAKER: up a little. - If you're a long-time listener to Still Entitled, you've heard me talk about an
[02:38] SPEAKER: event that happens in Chicago in January called OrdCamp that Fitz, along with a team of really,
[02:44] SPEAKER: really brilliant people, has been running for, what, like 12 years now?
[02:47] SPEAKER: - 12 years. We've done 12 of them, yeah. - Yeah. And it is the event that he runs
[02:56] SPEAKER: is a collection of brilliant, interesting, fascinating, fun people that come together and
[03:03] SPEAKER: kind of share the things that they're interested and passionate about. And it's a really incredible
[03:10] SPEAKER: cross-disciplinary event. And it's one of my favorite things that I get to do when I get to
[03:15] SPEAKER: go. So thank you for that. But you've also been doing technology stuff for... You're one of the
[03:22] SPEAKER: fabled Greybeards, Fitz. I don't want to out you. - Yeah. No, no worries. I've been doing this for
[03:27] SPEAKER: 26 years now. Yeah. - You started with one of the early code management systems, right?
[03:33] SPEAKER: - Well, I started before that. I mean, that was sort of the thing that helped me, I think,
[03:39] SPEAKER: really get out there. I was doing open source stuff, working on... I did work on Subversion
[03:43] SPEAKER: when it first started in 2000. And Subversion launched in 2003. I have not been using Subversion
[03:49] SPEAKER: for longer than it's actually existed, which is kind of funny. For longer than I actually used it.
[03:56] SPEAKER: But yeah, and I started doing CGI programming with Perl back in '94 when it was like Mosaic
[04:03] SPEAKER: and Netscape had just come out. And I don't know, I just loved it. I think at a late start,
[04:08] SPEAKER: I didn't start till I was 24. - Oh, so did you... Were you like a CS guy? - No, I majored in Latin,
[04:16] SPEAKER: minored in Greek and pottery. - Wow. - So my mom thought I was gonna be homeless. - I mean,
[04:23] SPEAKER: look, it worked out okay for you, I guess. - I always have a hobby. - That's funny. I did Latin
[04:29] SPEAKER: and ancient Greek and those contributed to me being able to write really well.
[04:35] SPEAKER: - Yeah. - Because you can't... You're not gonna do well at Latin if you don't... Doing well at Latin
[04:42] SPEAKER: makes you really, really, really understand English grammar in a way that is fascinating,
[04:48] SPEAKER: I always found. But yeah, so okay. So you worked on Subversion, which was... I mean, I guess we
[04:54] SPEAKER: could explain what Subversion is, but it's basically a predecessor to Git or one of the
[04:59] SPEAKER: more modern code management systems at this point, right? - I'd agree. Yeah, it was a centralized
[05:03] SPEAKER: version control system built to replace CVS, which was the original open source version control
[05:10] SPEAKER: system that everyone used back in the '90s and 2000s up until Subversion basically supplanted
[05:16] SPEAKER: that and then Git supplanted that. - And then that took you to Google, right? - Yeah, I started at
[05:24] SPEAKER: Google, I don't know, a year and a year and a half after Subversion launched. - And you were part of
[05:31] SPEAKER: a crowd that seemed like they didn't wanna move to California but wanted to work for Google and
[05:37] SPEAKER: you ended up somehow staying in Chicago? - Yes, somehow. I don't know how that worked
[05:41] SPEAKER: out. That was kind of fascinating. I basically said, "Yeah, I'm staying here and I'd love to
[05:45] SPEAKER: work for Google." And wound up with me starting Google's engineering office in Chicago along with
[05:50] SPEAKER: my friend Ben, who you know very well. - Yeah, I love Ben. Ben's great. And Google... So when we
[05:57] SPEAKER: get to Google, we're gonna get to the interesting part, I think the really interesting part of the
[06:00] SPEAKER: story because Google... In addition to day job stuff that you did, you started the takeout,
[06:09] SPEAKER: what is now I think called the Google takeout program which lets you extract all of your data
[06:15] SPEAKER: from the giant faceless multinational tech company so that you can move it to other places or
[06:21] SPEAKER: whatever. But I mean, that initiative wouldn't... I was at Maximum PC when you all started doing
[06:27] SPEAKER: that and I saw that and I was like, "Oh, this is something I had never thought these enormous tech
[06:30] SPEAKER: companies were gonna allow." And it kind of set a really positive tone for data portability in a way
[06:38] SPEAKER: that Google was giving us all these free services. There was absolutely no... There was no need for
[06:45] SPEAKER: Google to release the data that we'd given to Google. So it was a refreshing thing and I'm
[06:51] SPEAKER: curious, that process, how much of that was... How much of a fight was it to get that to happen
[06:59] SPEAKER: inside the company at the time? Were people on board or was it a challenge?
[07:03] SPEAKER: It was actually effortless and so far as I went and talked to... I basically went to Eric Schmidt
[07:10] SPEAKER: at the time and said, "Hey, I really wanna do this thing." And he's like, "Well, why are you asking me
[07:14] SPEAKER: permission? Just go, you should be doing this. Of course you should be doing this." Because he had
[07:18] SPEAKER: been... One of the things that... There are two things that inspired me to start it. One was Eric
[07:24] SPEAKER: kept giving talks internally and externally where he talked about the fact that Google doesn't lock
[07:28] SPEAKER: in your data. Like other companies where it's impossible to get your data out or export it,
[07:34] SPEAKER: we make it easy to go. And I thought like, "Yeah, we kinda do. The door's open, but in some cases,
[07:40] SPEAKER: you really gotta bang your shoulder up against it and I think it could be better." And then I
[07:44] SPEAKER: wound up having a conversation, there's a long story behind this, but due to an article about
[07:48] SPEAKER: me in ValleyWag that misquoted me, I met this Google PM named Jess, who was the one that
[07:55] SPEAKER: initially threw the idea about the Data Liberation Project. She called it Data Portability. And we
[08:00] SPEAKER: were just getting ready to roll it out and then dataportability.org came out. And I looked at this
[08:05] SPEAKER: and I'm like, "This is never gonna go anywhere." And this was like 2008, 2009. And so we decided
[08:11] SPEAKER: to go Data Liberation, sort of like Guerrilla Army type marketing. And I'm glad we did 'cause
[08:17] SPEAKER: dataportability.org is still there and it sort of hasn't done a whole lot, frankly.
[08:21] SPEAKER: - Well, but I mean, if you've never used the takeout service, it's really neat. You go in,
[08:26] SPEAKER: you log into your Google account and then you say, "Okay, I wanna download all this stuff." And it
[08:29] SPEAKER: says, "Okay, we're gonna zip this up and we'll let you know when the download's ready." And then
[08:35] SPEAKER: you can get everything from email, stuff that's uploaded to photos, stuff that's uploaded to
[08:40] SPEAKER: YouTube. - Your blog, anything.
[08:43] SPEAKER: - Yeah. All of it. And it works.
[08:47] SPEAKER: - The really cool thing about it is we initially launched with zip because that was the easiest
[08:51] SPEAKER: thing to get done and build the pipeline. But now you can point your stuff straight at Dropbox. You
[08:57] SPEAKER: can push your stuff right at Microsoft OneDrive. And Google started the data transfer project in
[09:03] SPEAKER: the last, I don't know, year and a half, two years ago, which is an open source project to allow
[09:07] SPEAKER: anyone basically to build an endpoint for takeout. Not just for takeout, but for this sort of
[09:13] SPEAKER: protocol of transferring data from one place to the other so that it doesn't turn into a technology
[09:18] SPEAKER: problem to integrate with other services. It turns into basically a sort of a procedural problem
[09:23] SPEAKER: where you vet the service and make sure that they're legit before you hook up to hook up to
[09:26] SPEAKER: them. - So I guess shortly after that,
[09:30] SPEAKER: you left Google, right? Or maybe- - Shortly, I mean, six years
[09:34] SPEAKER: after that, after we started it, yeah. - But along the way, one of my favorite
[09:42] SPEAKER: things at Org Camp every year is you take a lunchtime Saturday tour of the Chicago Google
[09:48] SPEAKER: Museum, which is a little nook on one of the floors in the Google office. I can't remember which one,
[09:54] SPEAKER: but it's got all this weird science and tech ephemera from the Chicago. It seems like it's
[10:00] SPEAKER: mostly from the Chicago area, but also from Google's history and a bunch of other things.
[10:05] SPEAKER: And there is some stuff there that I've never seen in actual real museums. For example,
[10:12] SPEAKER: there's an old, I think you said second generation Google rack, maybe?
[10:15] SPEAKER: - Yeah, there's a second generation rack. A first generation rack is in the Computer Science History
[10:21] SPEAKER: Museum or Computer History Museum in Mountain View, right by Google. I tried to get one of
[10:27] SPEAKER: those, but they don't ship. They fall apart because they're literally held together with zip ties.
[10:32] SPEAKER: - So those are the ones that when we would hear stories about Google
[10:36] SPEAKER: engineers building machines and stacking them on, I think, what was it? Pieces of
[10:43] SPEAKER: particle board or something? - It was a cork board. They call them the cork board racks,
[10:47] SPEAKER: the first generation, because they would just basically had these bits of sheet metal and they
[10:51] SPEAKER: would put a thin layer of cork board on just basically to keep the motherboard from shorting
[10:56] SPEAKER: out against the metal rack. - Yeah, and they're not screwed in. They're just rested and zip tied
[11:01] SPEAKER: in the corner holes, right? - They weren't even zip tied. They were just rested on there.
[11:05] SPEAKER: The back wall of the rack was a zip tied together wall of fans, basically.
[11:11] SPEAKER: - Wow. - And the whole thing was just like, it's just super, super sketch. If you're ever in the
[11:16] SPEAKER: museum in Mountain View, go check it out. You're like, it's sort of canted a little bit to the side
[11:22] SPEAKER: 'cause it's like gonna fall over in any moment. - It reminds me of the, I can't remember what the,
[11:28] SPEAKER: what the, it's the people in one of the Douglas Adams books that the supercomputer is pushing
[11:34] SPEAKER: space flight on and they build the jankiest spaceship in the world in the universe. And you
[11:40] SPEAKER: look at it and everybody's like, I can't believe this thing flew. And you kind of look at those
[11:43] SPEAKER: old racks and you're like, I really, this is what made search good. I can't, I don't, I don't know
[11:48] SPEAKER: if I buy this. - Well, I mean, there's a couple of things that were groundbreaking for that. First of
[11:52] SPEAKER: all, they didn't have pretty bezels. They didn't have blinking lights. They didn't come, everyone
[11:56] SPEAKER: didn't have a CD drive. Everyone didn't have all these, you know, all this stuff that you expected
[12:01] SPEAKER: in a server. And also they weren't designed to be sturdy and last. The premise was hardware will
[12:07] SPEAKER: fail no matter what, especially as you get into larger numbers. So let's just plan on it failing
[12:11] SPEAKER: and go as cheap as we can. The other thing was they were optimizing for square footage and the
[12:16] SPEAKER: use of electricity because at the time in late nineties, early two thousands data centers were
[12:21] SPEAKER: charging you per square foot, not per watt used. And so by maximizing this, and then by the time
[12:27] SPEAKER: Google got to second gen rack, which is the one that I have in the museum here, they would base,
[12:33] SPEAKER: they were still renting data center space at the time instead of building their own data centers.
[12:37] SPEAKER: But the really cool thing is they would roll all these racks into a data center and they would use
[12:43] SPEAKER: so much electricity and cooling that half the data center would be left empty. - Wow. - Because they
[12:48] SPEAKER: just couldn't put anything else in there. - So like you, you guys were trying to build, they were
[12:52] SPEAKER: trying to build Comtronium basically there rather than... Brad asks, what kind of systems are we
[13:00] SPEAKER: talking about in those zip tied racks, architecture, OS, stuff like that? - Well, it was all
[13:05] SPEAKER: basically a version of Linux. I don't know about the gen one rack, but the gen two rack that I have
[13:12] SPEAKER: was dual Pentium threes. And they were just like, they had two different kinds of racks. Okay. So
[13:20] SPEAKER: let me back up a second. So I decided I wanted to get a rack for the office. The whole reason this
[13:25] SPEAKER: museum thing exists is because I was like, we're out in Chicago. We should have cool nerd stuff
[13:31] SPEAKER: like they have out in Mountain View because in Mountain View building 42, they had a first gen
[13:34] SPEAKER: rack in the lobby and they've got all this sort of cool stuff out there. And I'm like, there's
[13:38] SPEAKER: no reason we shouldn't have this here. So you may remember early days, Google had this thing called
[13:43] SPEAKER: the geo display, which is this rotating earth with little pillars of light showing where searches
[13:47] SPEAKER: were happening. So I built one of those machines and had that in the office, which was cool. And
[13:52] SPEAKER: then I'm like, we need to get a rack. And so I tried to get the gen one rack and failed because
[13:56] SPEAKER: they just said, we can't ship them. They'll fall apart. Then I managed to sort of wheeze on my way
[14:01] SPEAKER: into getting a gen two rack shipped. And so there's two of them. One is what they call a serving rack,
[14:07] SPEAKER: which would have 40 machines, 20 per side. And it was basically CPU, just for serving up search
[14:13] SPEAKER: queries, handling, whatever types of data ads, et cetera. Then they had a rack that they affectionately
[14:20] SPEAKER: called a disk full rack because it was full of disks that was for storage. And so the one that
[14:25] SPEAKER: I wound up getting was a disk full rack, and that's 40 machines. Each machine's a Pentium 3,
[14:30] SPEAKER: dual Pentium 3, and each machine had eight hard disks in it. Now there were originally 20 megabyte
[14:37] SPEAKER: hard disks and they all like plugged into these little off-board daughter cards. At some point,
[14:43] SPEAKER: hold on, 20 megabyte or 20 gigabyte disks? I'm sorry. It would have had to be 20 gigabyte,
[14:49] SPEAKER: right? No, this was early 2000s. This was 2003 era. So I don't know that that would have been 20,
[14:59] SPEAKER: but yeah, it would have been 20 gigabyte. Yeah, 20 megabyte would have been like mid 90s. Yeah,
[15:02] SPEAKER: 20 megabyte would have been... See, this is the problem with starting with computers in the 80s,
[15:07] SPEAKER: is that I get my megabytes and gigabytes confused all the time. Oh, it's easy to be off by an order
[15:12] SPEAKER: of magnitude on the reg, yeah. Yeah, so 20 gigabyte disks. And Google was desperate for
[15:18] SPEAKER: storage space because they were running on a straight basis or a log. So at some point,
[15:22] SPEAKER: they went through and converted all these to 400 gigabyte drives. And as you well know,
[15:28] SPEAKER: the problem with making your basement 20 times larger, but still having the same wee little
[15:33] SPEAKER: basement door, gave you all sorts of IO problems. And these racks were legendary for just being
[15:40] SPEAKER: super difficult to get data into and off of. But that's the rack that we have at Google Chicago.
[15:47] SPEAKER: And the cool thing about it is I was so ignorant going into this, I had no idea how much this thing
[15:53] SPEAKER: weighed. Yeah, there's 40 machines and each one has eight hard drives. So that's 320 hard drives.
[16:00] SPEAKER: Yes, and you've got the rack and you've got all the other metal and stuff. The weight of this
[16:05] SPEAKER: rack is just under 1500 pounds. And so the delivery guy showed up and he was super confused.
[16:12] SPEAKER: He's like, where's the data center? And I'm like, oh, there's no data center. This is just an
[16:16] SPEAKER: office. He's like, I can't deliver this. I'm like, why not? He's like, well, your ramp has a
[16:20] SPEAKER: one inch lip at the bottom and we can't get over that. And I'm like, well, can't you just tilt it
[16:24] SPEAKER: back? And he just looked at me like I had three heads and we wound up somehow not killing ourselves
[16:31] SPEAKER: with like seven or eight people getting this rack up and rolling it down the hallway to where it
[16:36] SPEAKER: lived. And it was one of those things where it was running a standing wave through the floor
[16:41] SPEAKER: of the office because it was so heavy. And when the building management people find out what I
[16:46] SPEAKER: brought into the building, they were furious because the building wasn't rated for this.
[16:51] SPEAKER: And so we wound up having to literally like put it right next to a load bearing
[16:54] SPEAKER: column. Couldn't move it, had all these rules and restrictions around it.
[16:58] SPEAKER: It's a good thing you're in earthquake territory, I guess.
[17:01] SPEAKER: Right. Right.
[17:02] SPEAKER: Is there anywhere online people can see pics of this stuff? Like are these available online
[17:08] SPEAKER: places or are they still kind of semi-secret?
[17:10] SPEAKER: I don't think they're semi-secret. This was also known as a breadboard rack because it looked like
[17:17] SPEAKER: giant breadboards, these big metal sheets that were in there. And so I bet you if you search
[17:23] SPEAKER: around for Google breadboard rack, you could find something or other. They're just super ghetto
[17:28] SPEAKER: looking, especially now that it's a 17-year-old piece of hardware. And it's another funny story
[17:34] SPEAKER: about this. I actually created a sticker that I wound up giving out like 30,000 of at Google
[17:40] SPEAKER: that said my other computer's data center.
[17:45] SPEAKER: So, oh, go ahead.
[17:47] SPEAKER: No, I'd say this sticker was, lots of people reuse it. My other computer's a book. The
[17:53] SPEAKER: security team made my other computer's your computer and the hardware ops people made.
[18:00] SPEAKER: My other computer is made of razorblades and hate because these machines had so many sharp edges
[18:07] SPEAKER: that they were required to wear gloves after a while to handle them because people were
[18:10] SPEAKER: just getting their fingers sliced to ribbons.
[18:13] SPEAKER: I was going to say, I looked at this and it reminded me of the worst of the 90s PC cases
[18:18] SPEAKER: in that it is like the die stamped metal with the super sharp edges. This is before the
[18:27] SPEAKER: point. I mean, now obviously Google buys enough hardware that they just say, hey, we want,
[18:32] SPEAKER: this is the giant motherboard manufacturer. Here's the motherboard we want with this stuff
[18:37] SPEAKER: on it. And this configuration, this many slots and this many drive ports and all that stuff.
[18:41] SPEAKER: But back then I assume this was mostly off the shelf hardware or not really.
[18:46] SPEAKER: Yeah. Completely off the shelf, bulk stock crap. And there was a switch built into the middle of
[18:54] SPEAKER: the rack too. So everything basically just plugged into there. You would roll in and basically plug
[18:59] SPEAKER: in three or four things into the wall and then plug in one ethernet cable and off you went.
[19:05] SPEAKER: So like you can turn up a data center really quickly and burn it in really quickly. There's
[19:09] SPEAKER: two other things that merit note about this rack. And one was very controversial is that
[19:15] SPEAKER: all the drives were just basically instead of screwing them all in because drives, drives feel
[19:19] SPEAKER: all the time, especially when you have hundreds of thousands of them, they were all Velcro down.
[19:24] SPEAKER: And go ahead. I was just saying mechanical hard drives of that time didn't have accelerometers
[19:30] SPEAKER: and stuff if they were jostled. So like moving the rack when it was, I guess moving a 1500
[19:35] SPEAKER: pound rack was probably challenging. So. Right. I mean, well, you wouldn't, you obviously,
[19:40] SPEAKER: you know, wouldn't bump it around a lot, but and that the heads would be parked when it was moving
[19:44] SPEAKER: and you wouldn't move it when it was on. But there were two things that were interesting.
[19:47] SPEAKER: One is that, you know, software engineers were like, oh, this is fine. You know, these
[19:51] SPEAKER: racks, these drives can handle this sort of, you know, vibration, et cetera, without being mounted,
[19:56] SPEAKER: you know, screwed down. Well, it turned out they would do fine on reads, but on writes,
[20:00] SPEAKER: they would fail like 50% of the time because of the vibrations. And it just got worse as they
[20:05] SPEAKER: added more drives. So, you know, eventually the hardware engineers did the, I told you so thing.
[20:10] SPEAKER: The other thing, the other thing fun to note about this is that these, these racks were just
[20:16] SPEAKER: so poorly built and so what slammed out so quickly that it was sometimes very difficult to get the
[20:22] SPEAKER: lower servers pushed in because the machine would, the sides would bow in or out. And so the, the,
[20:29] SPEAKER: the documented protocol for getting the last bottom machine back in all the way was to lay
[20:35] SPEAKER: on your back in front of it and kick it until it went in. - The early days of tech, pretty,
[20:45] SPEAKER: pretty janky, it turns out. What, what was the, like, how many of these were we, are we talking
[20:53] SPEAKER: about? Like, were these things that they were just building as fast as they could, and there were
[20:56] SPEAKER: tens of thousands of them eventually, or was this something that there were a few hundred of,
[20:59] SPEAKER: and it would, and that was all that was needed to run the Google of the time.
[21:04] SPEAKER: - I'd say it's somewhere between those two or I don't know the exact number,
[21:08] SPEAKER: but it was definitely in the five digits range at least. I mean, yeah, four to five digits.
[21:14] SPEAKER: - And then they, eventually they transitioned to building custom enclosures and custom racks so
[21:20] SPEAKER: that they can increase the density even more. And now we're looking at like four use with 32 CPU's
[21:25] SPEAKER: and a bazillion drives and all that stuff, right? - Yeah. I mean, everything now is super custom,
[21:29] SPEAKER: including the data centers themselves. Like they're, they're really amazing. I've been,
[21:33] SPEAKER: I've been to some cool places. I've been to, I've been inside the Fermi lab Tevatron,
[21:38] SPEAKER: I've been to Argonne national labs, electron accelerator, and I've been in a Google data
[21:43] SPEAKER: center. And the, the last generation that was there when I left in 2014 blew my mind,
[21:50] SPEAKER: absolutely blew my mind. - The science of how can we pack more compute into the smallest amount of
[21:55] SPEAKER: space and cooling footprint has been, has been really, it's, it's gone a lot of, we've got a
[21:59] SPEAKER: lot of places in the last 20 years, right? - Sure has. Yeah. It's all about electricity
[22:03] SPEAKER: at that point. That's your, that's generally your limiting factor. - Well, yeah, there's a reason we
[22:07] SPEAKER: build them in places where there's a lot of hydroelectric power or a lot of sun and, and a
[22:11] SPEAKER: lot of cool water, right? - Right. Yeah. There's one in Finland, I think, you know. - Yeah. I know
[22:18] SPEAKER: that there's a bunch on like the Columbia river in Oregon and Washington places like, you know,
[22:23] SPEAKER: yeah, it's, it's like, what are the other things that matter for data centers? I guess speed of
[22:27] SPEAKER: light. So distance to the places that you need the resources or does that even matter really?
[22:32] SPEAKER: - Intersection of electricity and good fiber is, is basically it. But yeah, I mean, that's the
[22:37] SPEAKER: reason I used to, when, when I would do tours of the office and especially with school students,
[22:42] SPEAKER: I would ask them like, why do you think Google has data centers all the way around the world?
[22:45] SPEAKER: And they would come up with a lot of different answers, but no one ever got the right answer,
[22:47] SPEAKER: which is that the light isn't fast enough. So if everything's in North America, people have way
[22:53] SPEAKER: around the globe, you're adding, you know, a seventh of a second to everything, which is a lot.
[22:57] SPEAKER: - Wait, when the search query takes a third of a second, a sixth of a second, then a seventh of a
[23:02] SPEAKER: second lag is a lot, right? - Everything starts to add up. Yeah.
[23:04] SPEAKER: - Let's, let's switch tracks a little bit and talk. One of the other things that's fascinating
[23:10] SPEAKER: about the Google museum is you have a very large electromagnet there.
[23:14] SPEAKER: - I do. I do. It's very large, yellow 850 pound superconducting electromagnet.
[23:21] SPEAKER: - Everyone has one. - So, so, okay. So it's
[23:26] SPEAKER: electromagnet. It's from the Tevatron, right? - That's right. The Fermilab Tevatron. Yeah.
[23:30] SPEAKER: - Which was? - Which is, it was a high speed
[23:33] SPEAKER: experiment to find particles, right? I mean, it was high speed, high.
[23:39] SPEAKER: - High energy. - High energy. Thank you. Yeah.
[23:42] SPEAKER: High energy physics. Yeah. That was worked on for years, if not decades.
[23:45] SPEAKER: - Yep. - Yeah.
[23:47] SPEAKER: - I was just going to say, put you a particle accelerator in the Chicago land area at Fermilab.
[23:54] SPEAKER: And this thing, the stand, I don't know if you guys built the stand or if they built the stand,
[24:00] SPEAKER: but the table for it is, is pretty impressive. - I bought the stand.
[24:05] SPEAKER: - Oh, you bought the stand. Okay. - Yeah. It's rated for 34,000 pounds.
[24:09] SPEAKER: Cause so I bought one. Well, let me, let's back up. We should talk about how we got it, right?
[24:13] SPEAKER: So on September 30th, 2011, they shut down the Tevatron because they have the large Hadron
[24:19] SPEAKER: Collider now. And an interesting note, Fermi did a lot of the magnet research and a lot of the
[24:23] SPEAKER: magnet R and D for the LHC because they were the ones with the expertise. So anyway, it was
[24:30] SPEAKER: announced that it was shut down and I immediately emailed a friend of mine that worked over there.
[24:35] SPEAKER: And I'm like, dude, it's the Fermilab Tevatron shut down. Can you get me a magnet from it?
[24:39] SPEAKER: And he wrote me back and I don't know, can we swear on this podcast?
[24:42] SPEAKER: - Yeah, fuck yeah. - He's like,
[24:44] SPEAKER: you have no fucking idea what you're asking for. And I'm like, what do you mean? He's like,
[24:48] SPEAKER: they're huge. I'm like, well, get me a small one. And so I have a small one that's 850 pounds and
[24:55] SPEAKER: four feet long. The large ones are multiple tons in like 20 to 40 feet long, something very long.
[25:02] SPEAKER: But there's two kinds of magnets in the Tevatron. One is a steering magnet, which is basically,
[25:08] SPEAKER: it's a dipole, has two poles and basically turns the beam a little bit to the left or a little bit
[25:12] SPEAKER: to the right as it goes around this mile ring, mile long ring or mile diameter. I think it's
[25:17] SPEAKER: might be mile diameter. - I think it's mile circumference.
[25:19] SPEAKER: - Mile circumference. It's big, whatever it is. I mean, it's so big they have Buffalo or bison
[25:24] SPEAKER: living in the middle of it, right? - The comments will let us know.
[25:27] SPEAKER: - Yeah. And then the small ones are quadrupoles. They're focusing magnets. There's four poles.
[25:32] SPEAKER: They basically squeeze the beam down every so often as it goes around. There's about 774
[25:40] SPEAKER: of the dipoles in the ring. And then there's 250 of the quadrupoles. And so in any case,
[25:47] SPEAKER: my friend, he humored me and we went back and forth and basically just over a year later,
[25:53] SPEAKER: I got the magnet. Like it had to go through so much red tape and everything. And I bought it
[25:59] SPEAKER: off of eBay. That's how I got it. They called me up and they said, "We finally figured this out.
[26:04] SPEAKER: How do you want to buy it?" I said, "What is easiest for you?" And they said, "Really eBay's
[26:08] SPEAKER: the easiest." And I said, "Well, can you make it a buy it now? Cause I don't want someone else to
[26:12] SPEAKER: stack this up." Because they had to go to all this thing where they had to put it up for scrap. I
[26:16] SPEAKER: mean, no one bought it for scrap. Like no one would buy it. And so I clicked the buy it now
[26:20] SPEAKER: button off of eBay and had it shipped to the office. I bought a table for it that was rated
[26:26] SPEAKER: for one ton. And I'm like, "I figured 2X the rating, that'll be totally fine." And this table
[26:32] SPEAKER: wobbled back and forth so much. It scared the heck out of our facilities people. And like,
[26:37] SPEAKER: you need to buy a bigger, better table. So the table we have now is like 350 pounds and you could
[26:42] SPEAKER: park a truck on it. It's bananas. - I have to ask how much an 800 pound Tevatron magnet costs on
[26:52] SPEAKER: buy it now on eBay? - Well, so when they said, "Can you buy it now?" They sort of did this sort
[26:59] SPEAKER: of sucking in their teeth. "We're going to have to raise the price a good bit if you put it on
[27:04] SPEAKER: buy it now." And I said, "Well, okay. What is the price going to be with buy it now?" And they said,
[27:09] SPEAKER: "It's going to be $150." - You're paying less than a buck a pound. That's pretty good. - It's
[27:20] SPEAKER: basically a scrap price, but only two of these magnets have ever left Fermi. One's at the
[27:26] SPEAKER: Smithsonian, I believe it's in storage. And this one is on display at the museum in Google Chicago.
[27:31] SPEAKER: - So Brad wants to know, is it safe to assume you've never tried to put power on the magnet?
[27:36] SPEAKER: - It is very safe to assume that for two reasons. One, we don't have that kind of power. Two,
[27:43] SPEAKER: we don't have liquid helium to cool it. - Oh, man. Always a problem, it turns out,
[27:51] SPEAKER: the liquid helium. - Yeah, yeah. And it's got these cool sort of bendy connectors on the side
[27:56] SPEAKER: where they use to connect everything together. And you can look down the beam line. It's really
[28:02] SPEAKER: an amazing piece of high energy physics history. And I'm super happy to have that. But there was
[28:07] SPEAKER: some concern about people, is it going to affect laptops or phones walking by and that kind of
[28:12] SPEAKER: thing? And they're like, "No, it's basically a giant hunk of iron at this point." Although the
[28:17] SPEAKER: magnet itself inside the iron yoke is niobium titanium. - You don't want to degauss every
[28:23] SPEAKER: credit card in the building when you fire that thing up. I think that you said the one that you
[28:27] SPEAKER: have was a spare. Is that right? - Yeah, it was a spare. As my contact at Fermilab put,
[28:35] SPEAKER: you're never going to remove any magnet from the Tevatron itself because they are imbued with
[28:39] SPEAKER: administradium, which is to say there's so much red tape involved in getting something out of
[28:44] SPEAKER: there because basically they're hot, having been shot through with protons, high-speed protons for
[28:49] SPEAKER: so many years. There's a little level of radiation in them. So this was a spare. And they cleaned it
[28:54] SPEAKER: all up and they repainted it and they re-stenciled it and it's all pretty when we got it. But I had
[28:58] SPEAKER: to buy an engine hoist to move it off of the pallet onto the thing because how do you move
[29:04] SPEAKER: something that heavy? - Somewhere at Google Chicago, there's an engine hoist just rolling
[29:08] SPEAKER: around in a back storage room. - That is correct. - Very good. Did you have all the stuff in the
[29:13] SPEAKER: old Google office before they moved to the new place? - Yeah, the old space was the one that had
[29:18] SPEAKER: the problem with the weight of the rack. The new space building is in an old cold storage building.
[29:23] SPEAKER: You could park cars in there. It's no problem. - Okay. That makes more sense. Yeah. So one of
[29:28] SPEAKER: the other things that's really fascinating about the space in Google, and there's a bunch more
[29:33] SPEAKER: stuff we could get into, but your collection of esoteric storage devices there has some stuff that
[29:40] SPEAKER: I'd never seen before, which is, I mean, look, I've been doing this for a little bit. And you have
[29:49] SPEAKER: everything from old analog formats going all the way back to early record cylinders and things like
[29:55] SPEAKER: phonograph cylinders and things like that, all the way up to micro, micro cassettes and weird disc
[30:03] SPEAKER: formats. I think there's a German phonograph tape thing that's in there somewhere. - The teffy phone,
[30:09] SPEAKER: yeah. - That one is the weirdest because it seems like it's a vinyl tape, right? Like a kind of
[30:17] SPEAKER: thick vinyl tape in a cartridge. - Read by a needle. Yeah. It's the weirdest thing ever. But
[30:25] SPEAKER: it's a beautiful red vinyl, whatever type of plastic type of thing. I don't know what it is,
[30:30] SPEAKER: but yeah, it's pretty cool. - That one, I assume you have to rewind. It's a record you have to
[30:35] SPEAKER: rewind, but I don't know for sure. - No, I don't think so. I think it's like an A-track. I think
[30:39] SPEAKER: it's got a loop. - So I don't know how A-tracks, so A-tracks are one of those ones I never bothered
[30:44] SPEAKER: to spend the 20 minutes on Wikipedia to figure out how it works. What are the more interesting,
[30:52] SPEAKER: like, I mean, obviously there's like zip discs and side quest discs and all those big external
[30:56] SPEAKER: hard drive things in there, but what are some of the, do you have some highlights and favorites
[30:59] SPEAKER: from that section, Fitz? - Yeah. So the teffy phone is by far one of my favorites. I just,
[31:06] SPEAKER: I love that idea. I love the film collection 'cause I've got everything from eight millimeter
[31:12] SPEAKER: to 35, to 70, and then to IMAX. I think I let you pick up that IMAX trailer that I've got. It's like
[31:18] SPEAKER: a 30 second IMAX trailer that weighs 15 pounds. - It's a disc of celluloid that is- - It's mylar.
[31:27] SPEAKER: - Oh, sorry, yeah, mylar 'cause that celluloid would have caught on fire by now probably.
[31:32] SPEAKER: It's really, really heavy. And like, it's really fun when you have people and everybody's holding
[31:39] SPEAKER: up the different sizes of the film. It's really nice to, it gives you a really firm representation
[31:45] SPEAKER: of, hey, here's the difference in, you know, everything from, like you said, home eight
[31:50] SPEAKER: millimeter all the way through the IMAX and the CinemaScope and all the different projection
[31:54] SPEAKER: formats. - Yeah. And to give you a feeling for like what you're talking about, take your pinky
[31:58] SPEAKER: fingernail and look at it. That's about the size of an eight millimeter frame. So you can hold that
[32:04] SPEAKER: to the light and you can maybe make out if it's a person or a house or something. The IMAX frame is
[32:10] SPEAKER: hold your phone up, hold your extra large phone up, which I have one. That's probably two frames
[32:15] SPEAKER: side by side of IMAX right there. So you can not only tell what's in it, but who's in it. Like,
[32:21] SPEAKER: one of the frames I got is Robin Williams on a horse. And you can clearly see it's Robin
[32:25] SPEAKER: Williams standing on a horse because it's just that big. And there's just that much resolution
[32:30] SPEAKER: there. - Yeah, the IMAX is almost like, it's like the size of your palm almost, depending on how big
[32:36] SPEAKER: your hands are. - Yeah, it's ridiculous. - Go ahead. - I was gonna say that the other, going way back,
[32:46] SPEAKER: the giant digital disc pack that I've got, it's 175 megabytes. I think it's 12 or so,
[32:53] SPEAKER: 14 inch platters, and it weighs in the order of 40 pounds. And this was the other thing they would
[32:59] SPEAKER: go and put in those giant dishwasher size disc drives in a data center. And you'd spin the top
[33:05] SPEAKER: off and you close the lid of the dishwasher and the heads come in from the side and read the data
[33:10] SPEAKER: off of it. - It looked, those things looked like a tub washer, really. - Yeah, yeah. They're just
[33:16] SPEAKER: enormous. - We did a video at Tested years ago with one of the, I guess it's one of the things
[33:23] SPEAKER: that followed that, but that IBM, I want to say it's like a two megabyte hard drive or something
[33:27] SPEAKER: from the sixties that Adam got someplace. When we hung that from the ceiling in his shop, it took
[33:36] SPEAKER: three people and a chain hoist to get it up there. And I feel like it was in the early days of us
[33:44] SPEAKER: working with Adam at Tested. And I was standing there with this 80 or a hundred pound disc drive
[33:50] SPEAKER: on my shoulder, on my hands, up above my head. And I was thinking, man, I hope his ceiling
[33:56] SPEAKER: joists are as strong as he said they are, 'cause otherwise I'm going to get flattened here. - That
[34:00] SPEAKER: was the first thing I thought when he pointed it out to me when I was over there a couple of years
[34:04] SPEAKER: ago. I was like, oh man. Yeah, I mean, that's like, that was big data, right? This stuff was
[34:10] SPEAKER: heavy. But like the whole point around this was collecting things that for storing data over the
[34:16] SPEAKER: years, 'cause so many people collected old machines, but like that gets really bad really
[34:21] SPEAKER: quickly. Like in, as in like build a warehouse because it's just so big. So as I sort of like
[34:27] SPEAKER: went forward and backward, different folks would send me different things. Different folks would
[34:31] SPEAKER: recommend stuff. I've got a deck of punch cards, which is really cool. Like I just adore punch
[34:36] SPEAKER: cards 'cause I grew up with them 'cause my dad did computer stuff and they were everywhere in
[34:40] SPEAKER: our house. They were for grocery lists, you know, you could cut them into strips and make little
[34:44] SPEAKER: chains of like decoration, all sorts of stuff. - My grandparents' house had that as well. My
[34:49] SPEAKER: grandmother worked on early punch card stuff in the fifties and sixties and seventies, so.
[34:53] SPEAKER: - It was so interesting. It was so tangible, you know? Yeah, million different kinds of tapes.
[34:58] SPEAKER: Tapes, I think is the most obnoxious category because, and I will back up and say, when I
[35:04] SPEAKER: started doing this, I started collecting this because I'm like, oh, this is a nice finite thing
[35:08] SPEAKER: to collect. I was wrong. It is absolutely infinite because there's so many- - Storage formats.
[35:14] SPEAKER: - Yes, so there's so many different, really weird, not broadly used formats out there,
[35:20] SPEAKER: like the Tefiphone, you know? They probably made a thousand or a couple of thousand of those,
[35:25] SPEAKER: I guess, you know? - Well, and especially in the early days of computing, there were so many
[35:30] SPEAKER: people who had shifted from making, so many companies that shifted from making analog tape
[35:34] SPEAKER: stuff to digital tape stuff. There were probably, I remember at one point in the nineties, I was
[35:40] SPEAKER: specking out a backup system for our server cluster at the place I was working. And there were
[35:45] SPEAKER: probably 20 different vendors making completely incompatible tape backup systems that could hold
[35:52] SPEAKER: anywhere from what, maybe one gig to 10 gigs per tape or something like that. And that stuff could
[35:59] SPEAKER: get out of control. The different disc formats is a fun part of your thing. You know, I did notice
[36:06] SPEAKER: you didn't have one of those little pocket zip discs. I don't know if you remember those,
[36:12] SPEAKER: but they were maybe 40 or 80 megs. They were mostly for MP3 players and they were two inches
[36:19] SPEAKER: across, maybe an inch and a half across. I think they only ever made one device that played them.
[36:24] SPEAKER: - A removable zip? - It was a removable zip
[36:27] SPEAKER: for portable use. I might have one in the garage that I can bring out next time I see you.
[36:32] SPEAKER: - Yeah, I've never actually been aware of those. So I've got a spreadsheet that,
[36:37] SPEAKER: I should share this with you, that's got a list of all the known formats or particular types that I
[36:43] SPEAKER: have so that folks can go through and be like, oh yeah, I have that or add to it or remove from it.
[36:47] SPEAKER: You know, that's how Rob Pike actually, I was having dinner with him years ago and
[36:52] SPEAKER: we were talking about this and he was like, oh, do you have a 12 inch swarm disc in there? I'm like,
[36:56] SPEAKER: wait, what? 'Cause I've got an optical, I've got a three and a half and a five and a quarter.
[37:04] SPEAKER: I didn't know they made a 12, but I found one and it's like a laser disc in a cartridge. It's
[37:08] SPEAKER: amazing. - Wow.
[37:09] SPEAKER: - Yeah, they're huge. - Wow, that's bonkers. I guess it still
[37:13] SPEAKER: fits in a rack, right? - Yeah.
[37:15] SPEAKER: - The audio cassettes, the scale at which Sony made audio cassettes from very, very tiny spy
[37:24] SPEAKER: tape size all the way up to, what's the big one, like five inches across or something?
[37:29] SPEAKER: - Oh, it's at least five. Yeah, it's five, six, something like that. It's just enormous.
[37:34] SPEAKER: - Yeah, but it looks like a normal, it looks like a micro cassette, but it's just huge.
[37:39] SPEAKER: - Yeah, and the fun ones, again, it comes down to like weight and size. So I've got the tiny little
[37:46] SPEAKER: micro cassettes, which are smaller than the ones people are familiar with. Sony made this itty
[37:49] SPEAKER: bitty one that's like an inch across. And then, you know, we've got the reel to reel stuff,
[37:53] SPEAKER: got a quarter inch. I don't actually have half inch, I don't know. I've got the nine track
[37:57] SPEAKER: tape, which is all the old spinny tapes you'd see in the old data center pictures, early original
[38:03] SPEAKER: Tron, you know, type stuff like that. And then I've got one inch mastering tape, and then my
[38:07] SPEAKER: favorite two inch mastering tape is basically for 24 track analog recording. It's the kind of stuff
[38:14] SPEAKER: that the Beatles like, you know, recorded on in the very towards the Abbey Road days. But this,
[38:21] SPEAKER: it's just so heavy. It's just, it's this, you know, 10 inch reel that weighs like
[38:26] SPEAKER: 15 pounds or something. - Oh yeah. I mean, yeah. When you think about
[38:34] SPEAKER: the density of data storage, what's happened to the density of data storage over the last 20 years
[38:38] SPEAKER: and now, and the cost at the same time, like I, the other day I had to buy 128 gig micro SD card.
[38:44] SPEAKER: It's smaller than my pinky nail. It holds 128 gigabytes. And I think I paid 20 bucks for it,
[38:50] SPEAKER: 25 bucks for it, maybe like, yeah, it's, it's amazing. - Well, that's the thing that I point
[38:55] SPEAKER: out to folks is I've got this display at Google with all this stuff in it and a whole lot more,
[39:00] SPEAKER: we've only really scratched the surface of it, but you could basically put all of this onto a single
[39:06] SPEAKER: drive that you could go out and buy commercially today. - And I think there's a, like the space is
[39:12] SPEAKER: limited that you have for the museum there, but there's a fascinating, like, you know, you know
[39:18] SPEAKER: how they present paleontological displays at natural history museums now, and they start,
[39:22] SPEAKER: like they show the bones through time. So you understand that the Tyrannosaurus and the,
[39:26] SPEAKER: and the brontosaurus didn't live at the same time period because, you know, they were separated by,
[39:29] SPEAKER: you know, 30 million years or whatever. - Right. - There's an argument that like,
[39:33] SPEAKER: there'd be a neat way to put all that stuff on a timeline. So you can actually see it and see what
[39:38] SPEAKER: happened to the data density and the cost and the, and the weight and all that over, over the,
[39:42] SPEAKER: you know, the 40 years that that stuff has been, has been made. - I think I'd love to do something
[39:48] SPEAKER: like that. That's a great idea. - I think, I think that's a pretty good place to wrap it up, Fitz,
[39:53] SPEAKER: if you, if you, unless you have, well, let's see, did we, oh, I got some questions coming in from
[39:59] SPEAKER: Brad, hot text questions from Brad. I'll, I'll, he's typing. - Well, while he's typing, I'll throw
[40:09] SPEAKER: a couple of other interesting things on there. I've got, we got in the museum, one is the,
[40:13] SPEAKER: so we've got laser discs, which people have probably seen somewhere, 12, it's like a 12
[40:17] SPEAKER: inch CD, right? We also have capacitance, capacitance electronic disc, which is a predecessor
[40:22] SPEAKER: to the laser disc that used a very fine needle, like a record for tracking. And, but the problem
[40:28] SPEAKER: is, is that they couldn't get any dust in there because it was, the needle track was still fine.
[40:33] SPEAKER: So RCA put them in a, in a case, a sleeve. So you would stick this long sleeve into the front of
[40:39] SPEAKER: this reader and then pull it out and it would, it would sort of grab the disc. - And would the sleeve
[40:44] SPEAKER: like, did have brushes to brush dust off as it was going in? - It did, it had a gentle little like,
[40:50] SPEAKER: you know, linear like brush at the end of it to sort of keep the dust out. But they still
[40:55] SPEAKER: got dusted and went, got destroyed. - So this is a little bit of a swerve back to the start of the
[41:00] SPEAKER: conversation, but you said you started, you considered it a late start that you only got
[41:04] SPEAKER: into, into coding at age 24. This is from Brad, by the way. - Yeah. - What would you say to someone
[41:09] SPEAKER: who's developing an interest in the subject past the age of 40? - Go for it. Like, I don't think
[41:14] SPEAKER: anything is, is too late. I mean, I got, I got a late start relative to most people that write
[41:19] SPEAKER: software. You know, I mean, most of the people I hire today are, you know, just out of college
[41:24] SPEAKER: or whatever, not, and they've been doing it since high school. People are starting to write code.
[41:28] SPEAKER: It's, it's more accessible for people to not only write code, but get the resources to learn about
[41:33] SPEAKER: it. Like in 94, when I was first starting all this, it was like save up money to buy an O'Reilly book.
[41:38] SPEAKER: - Yeah. - Now it's just, use Google and Stack Overflow and you're halfway there, right? For
[41:43] SPEAKER: writing code. - Yeah. And like before, before Linux, if you wanted a code, like you had to
[41:49] SPEAKER: save money to buy your environment to write code and compile in, right? - To buy a compiler. Yeah.
[41:54] SPEAKER: - So I would say that I don't think anyone's too old to learn it. Like just, if there's something
[41:59] SPEAKER: you're interested in or curious about, start digging in and start, find something you want
[42:04] SPEAKER: to build, just like, or, or find something, some way of learning that works best for you.
[42:08] SPEAKER: I'm not a classroom learner. I'm a, I'm a sort of hacker type of person. People would say I'm
[42:13] SPEAKER: self-taught, but I say that I went and found a bunch of teachers when it came to this stuff. So
[42:18] SPEAKER: if that's what works for you, go for it. If, if you're a classroom learner, take a class,
[42:23] SPEAKER: buy a book, whatever works for you. But I don't think there's any too late anywhere around
[42:28] SPEAKER: learning how to program. - Do you, do you like, does it matter what language, like what you start?
[42:36] SPEAKER: Like, I know, like I learned to code. I took CS 100 when I was in college and was like, oh,
[42:40] SPEAKER: this probably isn't for me. And then 20 years later I got an Arduino kit and that information,
[42:45] SPEAKER: that knowledge translated straight ahead into, into how to write code for Arduinos.
[42:49] SPEAKER: But also at the same time, there was something really satisfying to me about making a change on
[42:54] SPEAKER: my computer that could affect something physical in the world, like turn a motor or light up a
[42:58] SPEAKER: light, make a buzz sound, whatever it was. And that, that made it a lot easier for me to get
[43:03] SPEAKER: going. But I know like a lot of people teach Swift. A lot of people teach Python, learn Python
[43:08] SPEAKER: now. What's where, where would you recommend starting or do you think it matters? - I think
[43:12] SPEAKER: a lot of it depends on what your interests are to your point. Like you, you found the interaction
[43:17] SPEAKER: between software and the physical world interesting. And that, that sparked your interest,
[43:21] SPEAKER: which is great. Like then Arduino is definitely the way to go with that. I, you know, when I was
[43:27] SPEAKER: a kid, I had an Apple two C and my brother and I, you know, I learned basics and 6502 assembler.
[43:33] SPEAKER: And then I got a Mac and I learned some Pascal and a tiny little bit of C, but it never really
[43:39] SPEAKER: grabbed me. I just, there was something about the client side stuff that I wasn't interested in.
[43:44] SPEAKER: When my little brother, my little snot notes, brother who was in college at the time studying
[43:50] SPEAKER: engineering he introduced me to Unix and Pearl. And that was my gateway drug. That was the thing
[43:57] SPEAKER: that caught my, because I was writing something that I could affect on a webpage that was just
[44:01] SPEAKER: go out there and other people could see. I thought that was, that graphs got me excited. So what is
[44:06] SPEAKER: the thing that gets you excited? I will say, I think you can make a mistake if you started like,
[44:10] SPEAKER: you know, doing X 86 assembler, you're probably going to quit before you get anywhere.
[44:14] SPEAKER: So, you know, I think Python's a great thing. I think Arduino is great. I think
[44:19] SPEAKER: things that are easier, I would avoid compiled languages. Frankly, I would start with C or Java.
[44:26] SPEAKER: Start with something that can get you a return on investment pretty quickly. The reason I think
[44:30] SPEAKER: Pearl worked really great for me is because Larry Wall was a classicist. I was also a classicist,
[44:35] SPEAKER: so I could learn Pearl much like I had learned Latin, Greek or Italian. And it was like little
[44:41] SPEAKER: bits at a time have speak like baby Pearl and then get adolescent Pearl and then et cetera.
[44:45] SPEAKER: So, you know, find what you, find what works for you.
[44:48] SPEAKER: Well, and now, now everybody has like, it's funny. Somebody, somebody asked me once what
[44:54] SPEAKER: they should do. Like what do they need to buy anything? I was like, yeah, maybe a second monitor
[44:58] SPEAKER: because it turns out almost all of the programmers I know now almost always have like the complete
[45:04] SPEAKER: reference guide up on the left side on the, on their other monitor, you know, because,
[45:10] SPEAKER: you know, when you're dealing with these more complex languages now, there's a lot to keep
[45:13] SPEAKER: in your head and, and you kind of, you need to think about how the algorithms work, not
[45:18] SPEAKER: necessarily the syntax or whatever of what you're working on in all cases. So there's nothing wrong
[45:23] SPEAKER: with having that second monitor open with, with your, with your code examples and your,
[45:27] SPEAKER: your reference guides and all that stuff. Yeah. I mean, I think there is a,
[45:31] SPEAKER: it is a mistake to think that people who have been coding for many, many years
[45:36] SPEAKER: just remember everything and just sit down and like, you know, start typing something out like
[45:39] SPEAKER: that right out of their head. Absolutely not. Like I still forget, like, what is a particular
[45:45] SPEAKER: function to do something? What are the order of arguments? What's this magic number? Yada, yada,
[45:49] SPEAKER: yada. Reference is the way it goes. Like I pulled up good. I've seen swordfish. I know how coding
[45:55] SPEAKER: works. Okay. Oh God. What, what's the worst movie representation of programming you've ever seen?
[46:04] SPEAKER: Oh, I don't know. I really don't know. Like it's not a there's, I can't pick out one particular
[46:10] SPEAKER: movie because there's, it's usually just the, like the silly stuff when something goes wrong
[46:13] SPEAKER: and you hit a bug and like the keyboard sparks, like that's probably the thing that's, you know,
[46:18] SPEAKER: or the other thing is the w when I was, when I was at Apple, we were creating these widgets for
[46:22] SPEAKER: web stuff that we could reuse. And one of the ones we, one of my colleagues created was called
[46:27] SPEAKER: the Hollywood login panel. And it was like little dancing lights around you, like your username and
[46:31] SPEAKER: login. But if you just typed in like admin as the username and hacker, it just bypassed all login
[46:36] SPEAKER: and got you into the app. Like, Oh God. Yeah. What, what, well, okay. So then what's the best,
[46:42] SPEAKER: do you think the one that was, was well done? It's not a movie, but I think Mr. Robot was really
[46:48] SPEAKER: well done. Okay. You know, I haven't seen a lot of, I haven't seen a lot of the other stuff like
[46:53] SPEAKER: Halton catch fire, a bunch of friends like that. I haven't seen it yet. It's up in my queue. But like
[46:57] SPEAKER: I watched the first season, Mr. Robot, and I was like, Oh, they definitely were talking to some
[47:00] SPEAKER: people who were in computer security here. Yeah. That one, I remember watching the first
[47:04] SPEAKER: season of that and was like, Oh yeah, they have a, their consults are really good on this. Yeah.
[47:10] SPEAKER: I've got another question from Brad. This one is in the context of Git eventually coming along and
[47:14] SPEAKER: supplanting subversion as someone who worked closely on a major project used throughout
[47:18] SPEAKER: the open source community, like SVN, what did it feel like to see what was basically
[47:23] SPEAKER: the next generation version of your work come along and become more prominent?
[47:27] SPEAKER: I think my disappointment with it, I was certainly disappointed. Let's be honest.
[47:35] SPEAKER: My disappointed stemmed from a different place than most people would think.
[47:38] SPEAKER: One is that the user interface for Git is just terrifyingly bad. Like I often,
[47:45] SPEAKER: I often say half jokingly only have maybe a third jokingly that you should never let kernel
[47:49] SPEAKER: programmers write usual land software because it's, it's like a, it's like a Gatling gun that
[47:54] SPEAKER: just like randomly shoots at different people. And you're, you're going to blow your foot off
[47:58] SPEAKER: like once a week with it. And people have built sort of guard rails around it and wrappers and
[48:02] SPEAKER: things like that. But the other thing that really concerned me was the fact with distributed version
[48:07] SPEAKER: control, it's really easy to hide in a cave. It's especially for younger people who are learning.
[48:12] SPEAKER: And, you know, Ben and I wrote about this in debugging teams. If you, if you do all your
[48:19] SPEAKER: work and then don't share it with someone, because you, you can just like commit it all locally,
[48:23] SPEAKER: and then you can rebase and basically just burp out your perfect finished product and share with
[48:28] SPEAKER: the rest of your team. A you're more likely to not share more often, often enough so that you can
[48:33] SPEAKER: like get feedback, ongoing feedback. And two, you're likely to make mistakes that you don't
[48:37] SPEAKER: have to make. But three, like people make mistakes all the time. Like just don't be afraid to show
[48:42] SPEAKER: your work kind of a thing. And so those were the big concerns. But beyond that, like beyond a
[48:47] SPEAKER: certain point, I think subversion actually didn't meet the needs. It continued to be centralized.
[48:53] SPEAKER: It was still built on the repository that I haven't looked at it since 2007 is the last time
[48:58] SPEAKER: I worked on subversion. But at the time that the repository is still built in this data structure
[49:03] SPEAKER: that I didn't think fit it fit what they really needed to do proper merge tracking and some of
[49:08] SPEAKER: the features that they needed to move forward. So I'm, I'm glad that something else, something
[49:14] SPEAKER: better is out there tool wise. Personally, like for a lot of my pet projects, I've used Mercurial
[49:21] SPEAKER: for a long time because it actually had a very good interface and I liked it a great deal.
[49:26] SPEAKER: But like GitHub has done a great job of basically building an ecosystem and a support structure
[49:32] SPEAKER: around Git. And so I'm totally fine with it now. I'm glad that I was just, I will, I will say I'm
[49:39] SPEAKER: glad I was part of what enabled the world to get to Git because I was, I was the person who finally
[49:46] SPEAKER: shipped CVS to SVN, which was the thing that converted millions and millions and millions of
[49:51] SPEAKER: lines of code from the old CVS system to subversion. And once, once you got it out of CVS in the
[49:57] SPEAKER: subversion, then you could take it anywhere. But CVS was such a janky piece of crap. I actually
[50:04] SPEAKER: gave talks about this piece of software. It was called making apples from applesauce because
[50:08] SPEAKER: CVS was such a mess that by analyzing it and running, I don't know, a dozen passes through
[50:14] SPEAKER: it to get it into subversion. I could actually tell you information about your data that you
[50:18] SPEAKER: couldn't find out from CVS because it didn't version operations, but I could basically
[50:22] SPEAKER: window box these things and say, Oh, well, this operation must have happened in here. So we'll
[50:26] SPEAKER: just bisect that and drop it in. So I'm glad we got people into that. We wound up in the end with
[50:32] SPEAKER: a tool that's much more usable, but I still do worry about people sort of hiding their work and
[50:36] SPEAKER: being afraid to share as much. Well, there's a, there's, there's a one universal for, we run
[50:42] SPEAKER: foo on Git and I'm going to GitHub with the LDS stuff and all that. One of the things that I've
[50:50] SPEAKER: found is that everybody who uses Git on the reg has a post-it note or a note document someplace
[50:55] SPEAKER: with like, here are the commands to use when you fuck it up really bad. And, and everybody's
[51:02] SPEAKER: commands are a little bit different. It's yeah, it's, it's, there's a little, there's a, there's
[51:08] SPEAKER: a you can do so much and so many different ways that it's, there's an inconsistency that's
[51:14] SPEAKER: challenging for certain, certain types of people. So I totally get that. People say, you say a lot
[51:22] SPEAKER: about command line software, but I really, this is something that I actually spent a lot of time on
[51:26] SPEAKER: when I was working in subversion for consistency and a smart command line syntax that people could
[51:34] SPEAKER: actually re remember and get help with, et cetera. There there's, I'm no great designer when it comes
[51:40] SPEAKER: to like web stuff, even though I've been doing web stuff for the past five years at talk.
[51:44] SPEAKER: But when it came to command line stuff, I really put a lot of thought into the design of that
[51:48] SPEAKER: command line. Brad says last question, not to put you on the spot, but would you come back again
[51:54] SPEAKER: sometime? I'd love to pick your brain for an awfully long time. Absolutely. I really enjoy
[51:58] SPEAKER: chatting with you. This is super fun. It's just like having a chance to catch up with you and
[52:01] SPEAKER: nerd out about stuff. Well, look, that's, that's the, you know, the, the, the joke I often see is
[52:06] SPEAKER: that it's, it's a, it's a, the podcast is an excuse for middle-aged white men to have meaningful
[52:10] SPEAKER: conversations with each other. So there you go. Fitz, this is opportunity for you to plug some
[52:18] SPEAKER: stuff. Talk obviously is awesome. Yeah, thanks. I that's what I've been doing for the last five
[52:24] SPEAKER: years. I left Google to start talk with Nick Kukonis and you know, we're, it's, it's a weird
[52:29] SPEAKER: world we're in right now with COVID-19 and everything. But we basically, when we started
[52:35] SPEAKER: working at home our team sat down and said, well, restaurants are closing globally and we're, we're
[52:40] SPEAKER: a system that helps restaurants book. What can we do to help these restaurants? You should explain
[52:44] SPEAKER: what talk does normally before I think, because I got a lot of people don't know. I was so talk,
[52:50] SPEAKER: explore talk.com. We are a booking system. Some people will say like open table and I would say,
[52:55] SPEAKER: yeah, except it doesn't suck. We were basically, you know, a modern version of a booking system
[53:03] SPEAKER: for restaurants where we do everything a restaurant needs, which up until two months
[53:07] SPEAKER: ago included things like regular reservations, like cost zero dollars, events, prepaid dinners,
[53:14] SPEAKER: pre-fixed dinners, where you pay for the whole meal before deposits, where you can pay part
[53:17] SPEAKER: of the meal before add-ons where you can choose like a wine pairing or a truffle supplement, or,
[53:23] SPEAKER: you know, a cookbook, cheese course, cheese course, that kind of thing beforehand.
[53:29] SPEAKER: And so that's, that's what we're doing. And also a whole lot of really good software to help the
[53:34] SPEAKER: restaurant manage everything better. A complex customer relationship management software that
[53:40] SPEAKER: would allow you to remember that, you know, Oh, this person's left-handed, they drink sparkling
[53:44] SPEAKER: water. Their spouse's name is Steve. Their anniversary is this, et cetera. So you basically
[53:49] SPEAKER: keep information about your regulars and give them a better treatment because the days of
[53:54] SPEAKER: there being a single maitre d that remembers everyone are long gone effectively. And so this
[54:00] SPEAKER: is what we started doing in December of 2014. I've got a fantastic product team that is doing
[54:05] SPEAKER: amazing work. It's a beautiful piece of software too, if you've ever used it. But when basically
[54:12] SPEAKER: every restaurant in the world shut down in the course of a week, we said, well, what do we do?
[54:17] SPEAKER: What can we do to help these restaurants with the software we have? And my team worked literally
[54:21] SPEAKER: for like five days straight and burped out a thing called talk to go, which is also does delivery and
[54:26] SPEAKER: pickup now. So we do all that stuff plus delivery and pickup. And the cool thing about that is most
[54:32] SPEAKER: delivery or pickup services are the kind of thing where you get on the phone or you pull up your app
[54:37] SPEAKER: and you order it and it shows up as soon as possible. Right. And that might be 25 minutes,
[54:42] SPEAKER: but if it was super slammed, it might be an hour and a half, which tends to get into like, Oh,
[54:46] SPEAKER: this sucks. I'm really hungry territory. But our system's all about time slots. And so we basically
[54:53] SPEAKER: allow a restaurant to say, yeah, I can do up to 20 meals every 15 minutes from five o'clock to
[54:57] SPEAKER: nine o'clock. But between seven and eight, I can do 25 meals because we're really going to push hard.
[55:02] SPEAKER: And so people can book in advance. So if it's like Friday morning and I'm like, oh,
[55:07] SPEAKER: hey, I want to order from Loyalist tonight and get a burger. Yeah. What time do you want to pick it
[55:12] SPEAKER: up? Oh, I'll pick it up at seven up. Seven's already sold out. Six thirties already sold out.
[55:17] SPEAKER: I'll pick it up at six 15. That's cool. And so the restaurant, you talk about flattening the curve,
[55:22] SPEAKER: this peak that hits like at seven o'clock, you have to push that down and say, this is,
[55:27] SPEAKER: this is as much as our our kitchen can handle and then push it out to the shoulders so that you can
[55:34] SPEAKER: actually get, give more people meals. You can do more business with fewer people in the restaurant,
[55:40] SPEAKER: which is important because they're having to space things out right now. So anyway,
[55:44] SPEAKER: we launched that mid-March and it's been just a roller coaster ever since they're trying to get
[55:48] SPEAKER: more restaurants onto this. So yeah, it's, it's interesting because it's so when I don't remember
[55:53] SPEAKER: if it was you or Nick that pitched me on the original idea for talk at OrdCamp five, four,
[55:58] SPEAKER: five years ago. But, but Nick is a restaurateur who owns the Alinea group in Chicago. And like,
[56:07] SPEAKER: this seemed, whereas the people I know that work with OpenTable describe it as something
[56:11] SPEAKER: that they have to do to remain in business. Like you guys took this from both a customer,
[56:17] SPEAKER: you know, diner perspective, but also from the restaurant perspective to, to build something
[56:21] SPEAKER: that's useful and good. And like you started doing, you started out with prefix, prefix menus
[56:29] SPEAKER: so that, and, and I think it was Nick was telling me about this was the idea was that you could get,
[56:32] SPEAKER: if, if you know that Wednesday night is always thin, you have the same number of people at the
[56:36] SPEAKER: restaurant on Wednesday night, working at the restaurant on Wednesday night as you do on
[56:39] SPEAKER: Saturday or Friday. So, so you're paying those people regardless, your, your cost is the same.
[56:44] SPEAKER: The only thing you're not spending on is the extra food that that's going out on the tables that
[56:48] SPEAKER: night. But if you can get more people into the restaurants on those nights, even if it means
[56:52] SPEAKER: reducing your price on the less demand, less in demand nights, then, then you can, you could do
[56:56] SPEAKER: like prefixes on Wednesday nights and make more money for the restaurant, have more people eating
[57:01] SPEAKER: your food. And, and it was a, it was a good experience for everybody all the way around.
[57:05] SPEAKER: It seems like this is, this is a natural extension of that from, you know, for, for the challenging
[57:10] SPEAKER: times that we face right now. Absolutely. I mean, that's where Nick did actually have a talk about
[57:14] SPEAKER: this at our camp. I think it would have been six years ago because some of my current employees,
[57:17] SPEAKER: some of my current engineers actually had gone to that talk. And then they're working with me today.
[57:22] SPEAKER: But yeah, originally it came about because two things, one no-shows even restaurants that have
[57:29] SPEAKER: more demand than they have availability still have no-shows. And it's not just, you know a table of
[57:36] SPEAKER: four doesn't show up at all. It's a table of four shows up as three. And, and I will say this,
[57:40] SPEAKER: there are these people out there who I would call monsters who booked tables of four for two people,
[57:44] SPEAKER: just cause they want more space. Oh, you're basically depriving a restaurant of revenue
[57:48] SPEAKER: because you want to be more comfortable in a restaurant. Well, it's not gonna be a problem
[57:52] SPEAKER: going forward cause you're going to get more space. But the second thing is that variable
[57:56] SPEAKER: price. The thing you pointed out is that so many people want to go on a Friday or Saturday night,
[58:01] SPEAKER: but not as many people want to go on a Tuesday or Wednesday. So just like if you go to a ball
[58:06] SPEAKER: game and you're sitting right behind home plate, you know, paying 300 bucks, you know, people don't
[58:10] SPEAKER: sit there and look back up in the, in the, you know, seats way up in the second upper deck and
[58:15] SPEAKER: say, God, you know, I can't believe this guy's only paid 70 bucks. Nobody's sitting there crying
[58:20] SPEAKER: over that. And so the thought was, well, if, if the same way as if there's the same thing with
[58:25] SPEAKER: demand in a restaurant, what's raised prices a little bit on Friday and Saturday at seven and
[58:30] SPEAKER: eight, but then lower prices on Tuesday and Wednesday. And what that came out with is the
[58:36] SPEAKER: system where you, you start just again, that curve at peak curve, you spread it out and you fill the
[58:41] SPEAKER: restaurant more. And, and another thing you said is the real thing that brought me to want to create
[58:46] SPEAKER: talk with Nick wasn't that I was just wasn't happy at Google. I was having a blast at Google.
[58:51] SPEAKER: The fact is, is that the idea, the original concept of talk is something that's good for
[58:56] SPEAKER: both the guests and the restaurants. So we agreed early on that if we can align our business model
[59:02] SPEAKER: with keeping the guests and the restaurants happy, then we've got a recipe for success versus a lot
[59:09] SPEAKER: of systems that we saw out there that were just like, Oh, we're going to build this concierge
[59:12] SPEAKER: service to help, you know, rich students that forgot to make a booking. They can pay an extra
[59:15] SPEAKER: 50 bucks and get a table that they wanted Friday at five or seven o'clock, which doesn't help the
[59:20] SPEAKER: restaurant at all. It doesn't help 99.9% of the world. And so that's what sort of brought us
[59:27] SPEAKER: along to this. And it's been really exciting to see how it's evolved because like, there's so
[59:32] SPEAKER: many different ways a restaurant could be booked because if you've got, if you've got high demand,
[59:38] SPEAKER: seven days a week, great, then you can do all sorts of stuff. Most restaurants don't have that.
[59:42] SPEAKER: Yeah. Most restaurants that are open have high demand on a Friday and a Saturday. Great. How can
[59:47] SPEAKER: we push some of that off to non peak times and leverage like that demand to create something
[59:52] SPEAKER: better for the guests. And the last thing is, but dealing with no shows appropriately, you can,
[59:58] SPEAKER: you wind up with this thing where people that want to get in the restaurant can, and the people that
[1:00:03] SPEAKER: are going to screw you over can't, you know, the people that make two or three reservations
[1:00:07] SPEAKER: on a Tuesday and then decide where to go last minute on a Friday. So people really do that.
[1:00:12] SPEAKER: That's horrible. Yeah. And the thing is that most restaurants treat every one of their guests like
[1:00:16] SPEAKER: they're a deadbeat when really it's only 15 to 20%. So the stuff that we have allows you
[1:00:21] SPEAKER: basically to keep your book open for the people that are committed to showing up and then weed
[1:00:26] SPEAKER: out the deadbeats. So it's anti deadbeat software. Fits if people want to find you on Twitter,
[1:00:31] SPEAKER: where can they do that? I am on Twitter at The Real Fits.
[1:00:34] SPEAKER: Very good. This is the part of show where I usually talk to Brad about the Patreon.
[1:00:39] SPEAKER: But I'm just going to talk about a little bit myself. We have at great after extended
[1:00:46] SPEAKER: conversation, we've added one more new channel to the Patreon to the discord, which you can get if
[1:00:51] SPEAKER: you subscribe at the $2 a month level. And it is called code code code. It's because the NAS
[1:00:57] SPEAKER: channel was getting clogged up with people talking about Linux programming. So that's there. We've
[1:01:04] SPEAKER: got the food channel has been popping off. I talked about my maker, the project that I,
[1:01:10] SPEAKER: my daughter and I made for Mother's Day tomorrow. Yesterday. I mean, we made it over the last week,
[1:01:15] SPEAKER: but it's been, we've been talking about it in the maker channel. It's an incredible resource.
[1:01:19] SPEAKER: Somebody this morning came to me with a Mr. Question. Do you know what the Mr.
[1:01:22] SPEAKER: is fits? You'll like this. I do not. It's a FPGA based emulation device that emulates
[1:01:28] SPEAKER: everything probably up to the PlayStation era. Not the PlayStation era is not there yet,
[1:01:33] SPEAKER: but it it's uses FPGAs to physically mimic, you know, actually mimic the circuitry in
[1:01:39] SPEAKER: SNES is Genesis is a turbo graphics Capcom CFS arcade boards, some old arcade boards,
[1:01:48] SPEAKER: stuff like that. So you can actually play, you know, as, as my favorite example is that the
[1:01:53] SPEAKER: Genesis shipped with different audio chips in different regions and different versions of the
[1:01:57] SPEAKER: hardware. So you can actually get the Genesis audio chip that you grew up with and have,
[1:02:03] SPEAKER: have the bleeps and bloops sound exactly like you want. I love it. So yeah, he messaged me with a
[1:02:09] SPEAKER: Mr. Question. I was like, I don't know the answer to this because I don't have mine yet, but you can
[1:02:13] SPEAKER: hit the discord and someone there will have the answer. He's like, I was helped within like five
[1:02:16] SPEAKER: minutes. So it's a wonderful community. It's like people are incredibly knowledgeable about a bunch
[1:02:23] SPEAKER: of things. You can get access to them if you sign up for the Patrion and our first subscriber
[1:02:29] SPEAKER: exclusive episode went up last week as well, where Brad and I talked about the plan for this month,
[1:02:34] SPEAKER: including talking to people like Fitz. So you can find that at patrion.com/techpod.
[1:02:41] SPEAKER: And if you don't want to sub to the Patrion, tell like three friends about the podcast. That's all
[1:02:47] SPEAKER: we ask. We want you to tell your friends about this thing that we make and appreciate everybody
[1:02:51] SPEAKER: who's listening, everybody who's backing the show. As always, we want to thank our executive
[1:02:56] SPEAKER: producer level patrons. These folks make the podcast possible every month along with everybody
[1:03:02] SPEAKER: on the Patrion. Andrew Cotton, David Allen and Jacob Chappell. Thank you so much for supporting
[1:03:07] SPEAKER: the show and we will be back next week with another episode. Thanks for coming by Fitz.
[1:03:11] SPEAKER: This was awesome. It's my pleasure. Good to see you. Thanks a lot.
[1:03:26] SPEAKER: [Music]
