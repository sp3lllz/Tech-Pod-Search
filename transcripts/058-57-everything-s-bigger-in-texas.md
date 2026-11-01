---
episode: 58
title: 57: Everything's Bigger in Texas
date: 2020-10-18
guests: none
duration: 1:11:24
---

[00:00] SPEAKER: - Did you see that thing Battle Frankie posted
[00:01] SPEAKER: after last week's episode?
[00:03] SPEAKER: - Which one?
[00:04] SPEAKER: A lot of people post a lot of things.
[00:06] SPEAKER: - The normalized human time when you compare
[00:09] SPEAKER: one clock cycle in a CPU at three gigahertz
[00:12] SPEAKER: to one second of real world time.
[00:15] SPEAKER: - Yeah, that thing was very eye-opening, let's say.
[00:18] SPEAKER: - I did not, I understood this, I thought,
[00:21] SPEAKER: but this illustrates it in the best way I've ever seen.
[00:24] SPEAKER: - Yeah, I knew all that stuff intuitively,
[00:26] SPEAKER: but to see it quantified is a very different thing.
[00:29] SPEAKER: Why don't you explain exactly what we're talking about here.
[00:31] SPEAKER: - Yeah, it's hard to understand like what a nanosecond,
[00:33] SPEAKER: how a nanosecond relates to, say, a microsecond, right?
[00:37] SPEAKER: So on a three gigahertz clock cycle,
[00:40] SPEAKER: one clock cycle takes about three tenths of a nanosecond.
[00:44] SPEAKER: So that's three 10 billionths of a second, I guess.
[00:49] SPEAKER: And if you normalize that to one second,
[00:52] SPEAKER: then accessing the level one cache
[00:54] SPEAKER: of the one that's built into the CPU takes three seconds.
[00:58] SPEAKER: The level two cache takes nine seconds,
[01:01] SPEAKER: and the level three cache takes 43 seconds,
[01:04] SPEAKER: which is bonkers.
[01:05] SPEAKER: Like that's the big thing that we were talking about
[01:07] SPEAKER: on the chip that holds the whole thing together.
[01:11] SPEAKER: Accessing RAM, which takes between 70 and 100 nanoseconds,
[01:15] SPEAKER: depending on the clock speed and latency of your RAM,
[01:18] SPEAKER: would be equivalent to 3.5 to 5.5 minutes.
[01:21] SPEAKER: So it's like-
[01:22] SPEAKER: - That was the part where my eyes flew wide open.
[01:25] SPEAKER: Like the cache stuff makes sense.
[01:26] SPEAKER: It's like, yeah, okay, sure, the level three cache
[01:27] SPEAKER: is gonna take a good number of clock cycles
[01:30] SPEAKER: to possess the slowest one, of course.
[01:32] SPEAKER: But then once we hit the RAM one,
[01:34] SPEAKER: and I was like, wait, system RAM's supposed
[01:35] SPEAKER: to be very fast, right?
[01:36] SPEAKER: Like that's the fastest thing outside of the CPU in-
[01:39] SPEAKER: - It is. - Computer.
[01:42] SPEAKER: - Yeah. - But this normalized figure
[01:43] SPEAKER: being like five minutes to access was...
[01:47] SPEAKER: - Yeah, so like the CPU wants something
[01:49] SPEAKER: that's in physical RAM on the motherboard,
[01:52] SPEAKER: on the chips that you socket into your motherboard,
[01:54] SPEAKER: and like it has to wait the equivalent of five minutes
[01:56] SPEAKER: to get the answer back, that's bananas.
[01:59] SPEAKER: - It's wild.
[02:00] SPEAKER: Well, keep going. - It gets worse.
[02:02] SPEAKER: To access an NVMe SSD I/O,
[02:05] SPEAKER: which is usually about between seven and 150 microseconds,
[02:09] SPEAKER: that's the equivalent of two hours to two days.
[02:13] SPEAKER: - That's a long time.
[02:14] SPEAKER: - It's like getting a letter.
[02:17] SPEAKER: A rotational disk I/O-
[02:20] SPEAKER: - Oh, you mean a hard drive.
[02:21] SPEAKER: - A hard drive.
[02:22] SPEAKER: - One to 10 milliseconds of computer time
[02:24] SPEAKER: is equivalent to 11 days to four months.
[02:27] SPEAKER: - That's...
[02:28] SPEAKER: - Pony Express, man.
[02:30] SPEAKER: - If that, maybe carrier pigeon, I don't know.
[02:34] SPEAKER: - We've got to get this letter to Chisholm by October.
[02:38] SPEAKER: Don't worry, the Pony Express has...
[02:41] SPEAKER: Internet latency comes into play next.
[02:43] SPEAKER: Internet San Francisco to New York City,
[02:45] SPEAKER: about a 40 millisecond ping, which is, I think, optimistic.
[02:49] SPEAKER: This is equivalent to about 1.2 years.
[02:51] SPEAKER: - That's quite a while.
[02:53] SPEAKER: - That's, yeah, that's...
[02:55] SPEAKER: Look, some people, some people's whole life.
[02:58] SPEAKER: The internet from San Francisco to Australia,
[03:01] SPEAKER: 183 milliseconds is six years.
[03:06] SPEAKER: Rebooting your virtualized OS,
[03:09] SPEAKER: like if you have an OS running in a VM hypervisor
[03:12] SPEAKER: on your machine, about four seconds on the PC, 127 years,
[03:17] SPEAKER: compared to the one cycle, one second clock time.
[03:22] SPEAKER: - That's longer than a lifetime.
[03:24] SPEAKER: - Rebooting the virtualization hypervisor,
[03:26] SPEAKER: I assume that's what they're talking about here,
[03:27] SPEAKER: is 40 seconds, that's 1,200 years.
[03:30] SPEAKER: And mashing the reset button on your computer
[03:33] SPEAKER: and letting it come back up,
[03:34] SPEAKER: which takes about 90 seconds, three millennia.
[03:39] SPEAKER: - So processor has seen some shit.
[03:42] SPEAKER: - Yeah, this is some dark magic.
[03:45] SPEAKER: I think that this was posted, I should have grabbed the link,
[03:49] SPEAKER: but this was in an article that they had linked
[03:51] SPEAKER: to elsewhere, from elsewhere.
[03:54] SPEAKER: And I found it incredibly informative.
[03:57] SPEAKER: - It's kind of a disturbance, a little bit unsettling to me.
[04:02] SPEAKER: - It's a little scary when you think about how much...
[04:05] SPEAKER: This is from a site called formulaceblack.com.
[04:10] SPEAKER: And if you Google compute performance distance of data
[04:13] SPEAKER: as measure of latency, it'll pop up for you.
[04:17] SPEAKER: And we'll put a link in the show notes, too.
[04:19] SPEAKER: But yeah, this is like...
[04:21] SPEAKER: We spent a long time talking about how to visualize
[04:24] SPEAKER: this kind of time scale at Maximum PC,
[04:26] SPEAKER: and this is easily the best,
[04:27] SPEAKER: and should have been the most obvious solution for that.
[04:31] SPEAKER: I don't think I would have trusted our math, frankly,
[04:34] SPEAKER: 'cause I would have gotten to the,
[04:35] SPEAKER: oh, it takes 1.2 years to send a packet
[04:37] SPEAKER: from New York to San Francisco, and been like,
[04:39] SPEAKER: yeah, we probably didn't carry a zero right here somewhere.
[04:42] SPEAKER: We should go back and plug this back into the spreadsheets.
[04:44] SPEAKER: - Yeah, but a site with formulace in the name,
[04:46] SPEAKER: I think you can probably rest assured
[04:48] SPEAKER: that their data is good.
[04:50] SPEAKER: I don't know, this is unsettling to me,
[04:52] SPEAKER: both from the standpoint of putting into relief
[04:55] SPEAKER: how much of our lives we are spending in front of computers.
[04:58] SPEAKER: - Yeah.
[04:59] SPEAKER: - And also just thinking about a CPU's experience of time
[05:02] SPEAKER: longer than you think will.
[05:03] SPEAKER: - It's funny. - Longer than you think.
[05:05] SPEAKER: - There's, in Neal Stephenson's "Seveneves,"
[05:09] SPEAKER: which is one of my favorite books,
[05:11] SPEAKER: he, they talk about, like, there's a space-based society,
[05:15] SPEAKER: and they talk about processors and memory
[05:19] SPEAKER: and things like that that you can't build in outer space
[05:21] SPEAKER: because of cosmic radiation messing.
[05:23] SPEAKER: Like, there's a reason we still use, like,
[05:26] SPEAKER: 80 CPUs on a lot of space probes,
[05:31] SPEAKER: and it's because they're higher process,
[05:34] SPEAKER: you know, very large processes by today's standards,
[05:37] SPEAKER: so that a stray particle smashing into the CPU
[05:41] SPEAKER: as it's flying through space doesn't jack up the mash
[05:44] SPEAKER: and crash the whole thing, right?
[05:46] SPEAKER: - Literally, you literally need a bigger surface area
[05:48] SPEAKER: on the chip to try to be more resilient.
[05:51] SPEAKER: - Wider pathways for the electrons are safer,
[05:53] SPEAKER: is my understanding.
[05:54] SPEAKER: I'm sure that somebody in the Discord will correct me
[05:56] SPEAKER: when I'm wrong on that, but.
[05:58] SPEAKER: - That's wild. - Yeah, it's a trip.
[06:00] SPEAKER: - We do have people working in space technology there.
[06:02] SPEAKER: - Exactly.
[06:03] SPEAKER: - Last question, all right,
[06:04] SPEAKER: this is gonna be the longest cold opening history
[06:06] SPEAKER: of this podcast.
[06:07] SPEAKER: - Oh, we're not even close to that.
[06:09] SPEAKER: - I take it, I take it you haven't read the jaunt.
[06:11] SPEAKER: I don't think you got my reference a minute ago.
[06:12] SPEAKER: - No.
[06:13] SPEAKER: - Oh, man, okay. - What's the jaunt?
[06:15] SPEAKER: - I can't, I shouldn't tell you,
[06:17] SPEAKER: 'cause I think you should read it.
[06:18] SPEAKER: It's a Stephen King short story about teleportation
[06:22] SPEAKER: that you should really read
[06:24] SPEAKER: if you want to look at these numbers
[06:25] SPEAKER: and feel that sense of creeping dread.
[06:28] SPEAKER: (upbeat music)
[06:39] SPEAKER: (upbeat music)
[06:57] SPEAKER: - Welcome to "Brad and Will Made a Tech Pod."
[06:59] SPEAKER: I'm Will.
[07:00] SPEAKER: - Brad, hey, hello, hi.
[07:01] SPEAKER: - Hi, hi, hello, hi, hi, hi, hi.
[07:03] SPEAKER: - What's happening?
[07:05] SPEAKER: - We're doing a podcast, Brad.
[07:06] SPEAKER: - Oh, crap, oh, shit, I gotta go get my--
[07:08] SPEAKER: - Yeah, when Mr. Softy, the ice cream truck, came to town,
[07:10] SPEAKER: I put on a pair of dungarees last Thursday, so.
[07:13] SPEAKER: - Fair, you don't wanna show your knees to the ice cream guy.
[07:16] SPEAKER: - No.
[07:17] SPEAKER: - You need some level of decorum when you go buy ice cream.
[07:19] SPEAKER: - It is, like, if you are going to order
[07:22] SPEAKER: a ridiculous ice cream cone for an adult,
[07:24] SPEAKER: like something rolled in sprinkles
[07:25] SPEAKER: or dusted with Oreos ground up or something like that,
[07:28] SPEAKER: you need to have a certain modicum of decency, I think.
[07:31] SPEAKER: - Gotta put on your business pants.
[07:33] SPEAKER: - Exactly.
[07:35] SPEAKER: - So we've got an interesting topic today.
[07:39] SPEAKER: - Yes.
[07:40] SPEAKER: - We were talking the other day about early video cards
[07:44] SPEAKER: and I had, I guess I hadn't forgotten,
[07:48] SPEAKER: but I hadn't considered, there was once a time
[07:52] SPEAKER: in the early days of 3D accelerators
[07:55] SPEAKER: when there were at least seven or eight different vendors
[07:58] SPEAKER: actively selling cards in that space.
[08:03] SPEAKER: - Yeah, and I'm sad we didn't save this exercise
[08:05] SPEAKER: for this episode.
[08:06] SPEAKER: We played it out on Discord last night,
[08:08] SPEAKER: but we kind of, I tried to run down,
[08:11] SPEAKER: kind of walk down memory lane
[08:12] SPEAKER: and remember what all those companies were
[08:13] SPEAKER: and now I kind of know what they are,
[08:14] SPEAKER: but we should try to recreate it here
[08:16] SPEAKER: just for the sake of the audience.
[08:19] SPEAKER: Also just a little bit of context for this episode,
[08:21] SPEAKER: I don't know about you, but I think for me,
[08:23] SPEAKER: I've just had this topic on the brain a lot
[08:24] SPEAKER: because this is the first time in, I don't know,
[08:28] SPEAKER: four or five years at least that I felt genuinely excited
[08:32] SPEAKER: about new PC hardware between the 3080s
[08:36] SPEAKER: and the new AMD, the new Ryzens and stuff.
[08:40] SPEAKER: PC hardware for the longest time for me has just been like,
[08:42] SPEAKER: ah, I guess I'll get a new CPU, sure, why not?
[08:44] SPEAKER: Like it's cheap enough right now, you know?
[08:46] SPEAKER: Like there's not, there's just not been a lot
[08:48] SPEAKER: to be excited about there.
[08:49] SPEAKER: Like the 1080, I feel like was that,
[08:51] SPEAKER: like that was a big leap forward.
[08:54] SPEAKER: Like, you know, maybe the RTX cards were interesting,
[08:56] SPEAKER: but not as fast as you wanted, the 20 series,
[08:58] SPEAKER: but like Reddit, we're at a sweet spot right now
[09:00] SPEAKER: where I'm like, I'm actually staring at hardware builds
[09:03] SPEAKER: a lot right now again and like fantasizing.
[09:05] SPEAKER: So that takes me back to the mid nineties
[09:08] SPEAKER: and those heady days of 8,000 3D accelerators
[09:11] SPEAKER: coming out all the time.
[09:12] SPEAKER: - Well, you'll see right now,
[09:13] SPEAKER: you'll see an actual real world performance improvement
[09:16] SPEAKER: for like spending money on new hardware, right?
[09:22] SPEAKER: In a way that you often don't, which is exciting.
[09:26] SPEAKER: So let's, I guess let's, let's start with,
[09:31] SPEAKER: like obviously everybody remembers 3D FX.
[09:34] SPEAKER: - Yeah.
[09:36] SPEAKER: - And then Nvidia had the Revo 128 early on.
[09:40] SPEAKER: ATI rolled out the 3D rage, well.
[09:45] SPEAKER: - Hang on, I'm just gonna play act what I did last night.
[09:47] SPEAKER: Okay, so what I was able to come up with
[09:49] SPEAKER: off the top of the head was the first one
[09:52] SPEAKER: that came to mind was the rendition verite.
[09:54] SPEAKER: - The original DirectX card, yeah.
[09:57] SPEAKER: - The rendition verite, obviously the 3D effect,
[09:59] SPEAKER: like the Voodoo stuff was like the thing
[10:01] SPEAKER: as soon as it came out, like nothing else mattered
[10:03] SPEAKER: for a while there.
[10:05] SPEAKER: - Well, actually that's not true.
[10:05] SPEAKER: It wasn't until Quake came out
[10:07] SPEAKER: that the Voodoo stuff really mattered.
[10:08] SPEAKER: - Well, yeah, GeoQuake was the thing
[10:10] SPEAKER: that made 3D accelerators a thing, frankly.
[10:13] SPEAKER: - 'Cause like, I think you've got MechWarrior
[10:15] SPEAKER: or something with your Voodoo card, MechWarrior 2,
[10:18] SPEAKER: and it was like a lightly texture mapped version
[10:21] SPEAKER: of the software rendered MechWarrior game.
[10:24] SPEAKER: - Not that 3D accelerated also.
[10:26] SPEAKER: I think I bought that game at a Sam's Club,
[10:28] SPEAKER: so I really lost out there.
[10:29] SPEAKER: - I bought it multiple times, I'm sure.
[10:31] SPEAKER: I came with every video card you bought for a while there.
[10:33] SPEAKER: - You know what, I would have bought it
[10:34] SPEAKER: just for that soundtrack multiple times.
[10:36] SPEAKER: That's totally fair.
[10:37] SPEAKER: - A fine game.
[10:38] SPEAKER: - So for whatever reason, I came up with rendition
[10:40] SPEAKER: and 3D effects, and then I stalled out
[10:42] SPEAKER: and started thinking about like Number 9 and Matrox,
[10:44] SPEAKER: which I don't think fit into this conversation that well.
[10:47] SPEAKER: - Well, so Number 9 never really released a 3D accelerator.
[10:50] SPEAKER: They were wholly focused on 2D and video,
[10:53] SPEAKER: is my understanding, and they kind of disappeared.
[10:55] SPEAKER: I think they got bought by somebody.
[10:57] SPEAKER: I don't actually know what happened to Number 9.
[11:00] SPEAKER: I also don't think that their bit of selling graphics cards
[11:10] SPEAKER: with Beatles tie-ins would probably fly in today's world.
[11:16] SPEAKER: - Why not?
[11:17] SPEAKER: I mean, I agree with you.
[11:18] SPEAKER: It was a bit too twee for my taste,
[11:21] SPEAKER: but I feel like the people at Apple Records
[11:24] SPEAKER: would probably have something to say about that now
[11:26] SPEAKER: in a way that they would not have been aware of back then.
[11:28] SPEAKER: - You're probably right.
[11:29] SPEAKER: Like I'm sitting here looking at their Wikipedia page
[11:31] SPEAKER: and some of their products
[11:32] SPEAKER: for people that are not familiar with Number 9.
[11:35] SPEAKER: Revolution, Imagine, Pepper.
[11:38] SPEAKER: - I feel like Revolution-
[11:39] SPEAKER: - Ticket to Ride.
[11:40] SPEAKER: - Yeah, Ticket to Ride was where they went off the rails
[11:42] SPEAKER: in terms of like-
[11:43] SPEAKER: - Naming a graphics card Ticket to Ride
[11:45] SPEAKER: is like, yes, absolutely.
[11:46] SPEAKER: That is a bridge too far.
[11:48] SPEAKER: - I mean, that said though,
[11:48] SPEAKER: there's a board game called Ticket to Ride, right?
[11:51] SPEAKER: - Well, that's fine.
[11:52] SPEAKER: I mean, that's probably got trains in it or something.
[11:53] SPEAKER: I mean, I'm fine with that,
[11:54] SPEAKER: but that's not a video card, you know?
[11:57] SPEAKER: So yeah, I mean, we'll probably touch on it some more,
[12:00] SPEAKER: but for whatever reason, my mind went to Matrox and Number 9,
[12:02] SPEAKER: which are more like 2D graphics cards,
[12:04] SPEAKER: which is like for people who were not doing PC stuff
[12:06] SPEAKER: in the nineties, yes,
[12:07] SPEAKER: you used to just have to buy a 2D graphics card.
[12:10] SPEAKER: - Yeah, went in the VL bus slot.
[12:12] SPEAKER: - Right, so you reminded me that ATI was active back then.
[12:16] SPEAKER: For whatever reason, in my mind, ATI was not a player
[12:19] SPEAKER: until the Radeon stuff,
[12:20] SPEAKER: but obviously they were in it way before that.
[12:22] SPEAKER: - So yeah, they made 2D cards.
[12:25] SPEAKER: Like that's where they started,
[12:25] SPEAKER: 2D cards and video processing stuff.
[12:27] SPEAKER: And they were like a real, they were,
[12:33] SPEAKER: like in the 2D graphics card realm,
[12:36] SPEAKER: there was like S3 kind of at the low end performant,
[12:39] SPEAKER: but not very good, maybe.
[12:40] SPEAKER: Not like didn't the image quality, here's the fun thing.
[12:43] SPEAKER: 2D graphics cards, image quality mattered.
[12:46] SPEAKER: Like some of them were better at it than others.
[12:48] SPEAKER: - That's why, I mean, we're kind of getting back
[12:51] SPEAKER: onto 2D cards and off the topic of 3D accelerators here,
[12:53] SPEAKER: but like I lusted after a Matrox millennium for so long.
[12:58] SPEAKER: I think whatever like, whatever crappy,
[13:00] SPEAKER: no name pre-built computer we had at home
[13:02] SPEAKER: had a similarly crappy, no name 2D card in it.
[13:06] SPEAKER: - Yeah.
[13:06] SPEAKER: - And desktop literally did not look great.
[13:08] SPEAKER: Like I don't remember, I don't know how to qualify that
[13:10] SPEAKER: 'cause in my mind, like I can't call to mind
[13:15] SPEAKER: what the desktop looked like,
[13:16] SPEAKER: but I think things were like maybe a little too fuzzy
[13:17] SPEAKER: or like it was something about like the VGA output
[13:20] SPEAKER: was not clean enough or something like that, I forget.
[13:22] SPEAKER: - So part of it was that the RAMDAC,
[13:26] SPEAKER: the thing that converted the digital signal
[13:28] SPEAKER: into an analog signal that went out across VGA,
[13:32] SPEAKER: if they were slow or bad,
[13:33] SPEAKER: you'd get fuzzy signals on the VGA.
[13:37] SPEAKER: - Also is about color reproduction and like window rendering
[13:40] SPEAKER: speed and stuff like that.
[13:42] SPEAKER: Like in Windows 3.1 with the right video card,
[13:45] SPEAKER: you could preview the window while you drug it around.
[13:48] SPEAKER: - Oh sure.
[13:49] SPEAKER: - And if you didn't have the right video card,
[13:50] SPEAKER: it would just be like an outline,
[13:51] SPEAKER: a box outline of an empty window.
[13:54] SPEAKER: - Yeah, the little dotted line outline.
[13:55] SPEAKER: - And then you could watch it literally draw back in
[13:58] SPEAKER: from the top to the bottom, if you had a slow video card.
[14:01] SPEAKER: - Our card was not that bad, thankfully, but I remember,
[14:04] SPEAKER: I remember wanting a millennium just because yeah,
[14:06] SPEAKER: it accelerated Windows stuff more
[14:08] SPEAKER: and it had very nicely clean, clean signal.
[14:11] SPEAKER: - 32 bit baby.
[14:12] SPEAKER: - Yeah.
[14:13] SPEAKER: - Well, so the thing that happened
[14:15] SPEAKER: around the time 3D accelerator started taking off was
[14:18] SPEAKER: that the, what had previously been low
[14:20] SPEAKER: in mid range 2D parts became pretty good,
[14:25] SPEAKER: like good enough, right?
[14:26] SPEAKER: So S3, ATI, Revolution was always on the high end or sorry,
[14:32] SPEAKER: number nine was always on the high end, stuff like that.
[14:35] SPEAKER: But so, so Matrox and ATI, both fine Canadian companies.
[14:39] SPEAKER: - Yes.
[14:41] SPEAKER: - The Rage 2 was kind of,
[14:43] SPEAKER: I think it was billed as a 3D accelerator
[14:45] SPEAKER: and you could get it with a copy of a MechWarrior 2,
[14:50] SPEAKER: but it was like kind of lightly texture mapped,
[14:54] SPEAKER: but not really was the thing I recall on that one.
[14:58] SPEAKER: - Was that their first major card, the Rage 2
[15:00] SPEAKER: in the 3D space and was that an all-in-one card
[15:03] SPEAKER: or was that an add-on?
[15:03] SPEAKER: - It was an all-in, all of these were all-in-one cards,
[15:05] SPEAKER: except for the 3DFX stuff, they were interesting.
[15:10] SPEAKER: - And PowerVR, PowerVR was 3D only too.
[15:13] SPEAKER: - Yeah, so we haven't, just to fully,
[15:14] SPEAKER: before we move on, just to finish our little rundown
[15:17] SPEAKER: of the roster here, S3, I guess was huge,
[15:20] SPEAKER: but I had completely in my mind, like glossed over the fact
[15:24] SPEAKER: that they even existed at that time.
[15:27] SPEAKER: - S3 was a big deal.
[15:28] SPEAKER: - Like it took me a minute, it took me a minute,
[15:29] SPEAKER: but the name S3 Verge finally floated back
[15:32] SPEAKER: into my consciousness.
[15:34] SPEAKER: - V-I-R-G-E.
[15:36] SPEAKER: - Right, but I couldn't remember if it was E-R or I-R.
[15:38] SPEAKER: That's how much I had forgotten it, but.
[15:41] SPEAKER: - But loads of 2D cards into like Compaq and Packard Bell
[15:45] SPEAKER: and like all the, they sold a lot to OEMs, the big OEMs.
[15:51] SPEAKER: And they also would kind of run,
[15:55] SPEAKER: so one of the defining gate for me on 3D accelerators
[16:00] SPEAKER: in like 1996, '97, '98 was would it run Quake?
[16:05] SPEAKER: Like in the days before DirectX, before Direct3D
[16:09] SPEAKER: and more, well like the second wave of 3D accelerated games
[16:13] SPEAKER: that started in like '97, like it was,
[16:16] SPEAKER: if it didn't run GLQuake,
[16:17] SPEAKER: it didn't count as a 3D accelerator,
[16:18] SPEAKER: even if it did like a little bit of bit mip mapping
[16:20] SPEAKER: and stuff like that on some textures.
[16:23] SPEAKER: And the Rage 2 wouldn't run Quake.
[16:26] SPEAKER: The Matrox Millennium wouldn't run Quake.
[16:28] SPEAKER: The S3 cards wouldn't run Quake.
[16:30] SPEAKER: - Just a 2D card, right?
[16:32] SPEAKER: - Well, yeah, but I mean, yeah,
[16:33] SPEAKER: it wasn't until the Mystique that Matrox had a card
[16:36] SPEAKER: that would run Quake, kind of.
[16:37] SPEAKER: - They tried.
[16:39] SPEAKER: - So the ATI's first Quake card was the Rage Pro,
[16:43] SPEAKER: which was also one of the first AGP cards,
[16:45] SPEAKER: which we'll get to in a minute.
[16:46] SPEAKER: - Yeah.
[16:48] SPEAKER: - Okay, so S3, I don't think S3 ever,
[16:51] SPEAKER: in the time period that mattered,
[16:52] SPEAKER: made a compelling 3D card.
[16:56] SPEAKER: Would you categorize them as an also ran in this space?
[16:59] SPEAKER: - Well, so one of the things that's interesting about any,
[17:01] SPEAKER: oh, hold on, we have a couple more.
[17:02] SPEAKER: Intel was making 3D accelerators?
[17:04] SPEAKER: - So Intel, when you threw that out there,
[17:06] SPEAKER: I was like, wait, what?
[17:07] SPEAKER: I don't remember that in the slightest.
[17:10] SPEAKER: - So they made, they partnered with Lockheed
[17:12] SPEAKER: and a company called Chips and Technologies
[17:14] SPEAKER: that Intel ended up buying a little bit later
[17:18] SPEAKER: and released the i740, which was another early AGP card.
[17:24] SPEAKER: And it was, if you recall, RAM was really expensive
[17:27] SPEAKER: and hard to get then during that time period.
[17:30] SPEAKER: - Vaguely.
[17:32] SPEAKER: - So like there'd been some sort of disaster,
[17:35] SPEAKER: an earthquake or a fire or something
[17:36] SPEAKER: that cratered RAM production in '93 or '94,
[17:40] SPEAKER: and it took a long time to come back online
[17:42] SPEAKER: 'cause it was a different time back then.
[17:44] SPEAKER: So a lot of the AGP design was set up
[17:49] SPEAKER: so that you could run video stuff out of system memory
[17:53] SPEAKER: rather than having to have eight megabytes of RAM
[17:58] SPEAKER: in the system and another four megabytes of RAM
[18:00] SPEAKER: on the video card.
[18:01] SPEAKER: - Which was an astronomical amount of RAM.
[18:03] SPEAKER: - It's shocking, it was shocking.
[18:05] SPEAKER: - Hundreds of dollars.
[18:06] SPEAKER: - I might've had 16 megabytes on my PC at that point.
[18:09] SPEAKER: - Oh really?
[18:10] SPEAKER: I think I probably had eight and was pretty happy.
[18:11] SPEAKER: Anyway.
[18:12] SPEAKER: - Maybe it was eight, I forget,
[18:13] SPEAKER: but I mean, that's back when RAM was like $50 a megabyte.
[18:18] SPEAKER: - More than that, at one point I paid 150 bucks per megabyte
[18:21] SPEAKER: for a two megabyte upgrade.
[18:23] SPEAKER: - Wow, that is physically painful to hear.
[18:26] SPEAKER: - That was in like '93 though.
[18:28] SPEAKER: - Okay, yeah.
[18:29] SPEAKER: So I just glanced at the Intel, the i740 page,
[18:32] SPEAKER: Wikipedia page, and that came out of '98.
[18:34] SPEAKER: So we're kind of swinging back and forth
[18:36] SPEAKER: across a two, three year time span
[18:38] SPEAKER: back and front here a little bit.
[18:41] SPEAKER: - So yeah, it's a weird time
[18:43] SPEAKER: because during the launch of the first version of,
[18:46] SPEAKER: the Revo 128 launched at a time
[18:49] SPEAKER: when probably the only 3D accelerated things
[18:51] SPEAKER: were Quake and Unreal and maybe like terminal,
[18:58] SPEAKER: there were some, probably some 3D realms game,
[19:00] SPEAKER: like terminal reality or something
[19:00] SPEAKER: that was 3D accelerated at that point.
[19:02] SPEAKER: - Sure, that sounds right.
[19:03] SPEAKER: - But it was like mostly-
[19:05] SPEAKER: - Very limited.
[19:06] SPEAKER: - Yeah, it was, and there were some flight sims.
[19:08] SPEAKER: I feel like Falcon, wasn't Falcon 6.0 3D accelerated
[19:11] SPEAKER: for the first time maybe?
[19:12] SPEAKER: - Oh, was it, was it that far along?
[19:14] SPEAKER: I thought they were on like 3.0 that thing.
[19:15] SPEAKER: - Or Windows 3.0.
[19:16] SPEAKER: Yeah, it was the one with the big binder.
[19:18] SPEAKER: - Yeah, 3.0 came out in '91.
[19:20] SPEAKER: Did they ever even get past 4.0?
[19:22] SPEAKER: I thought that was the last Falcon.
[19:23] SPEAKER: - Maybe I'm, maybe I'm, maybe I'm conflating-
[19:26] SPEAKER: - 4.0, 4.0 was '98.
[19:28] SPEAKER: So that was probably 3D accelerated at that point.
[19:30] SPEAKER: So, well, just to kind of start back at the start
[19:33] SPEAKER: before we get too much into the AGP in the late '90s stuff,
[19:36] SPEAKER: like obviously like 3D effects,
[19:38] SPEAKER: like a friend of mine got a Voodoo card, you know,
[19:41] SPEAKER: not long after GL Quake came out and like,
[19:44] SPEAKER: I went over to his house and saw it and fell out of my chair,
[19:48] SPEAKER: you know, like the defining moment in my history
[19:50] SPEAKER: with both technology and video games.
[19:52] SPEAKER: But like, you could,
[19:53] SPEAKER: did you have much contact with that stuff
[19:55] SPEAKER: before the Voodoo came along?
[19:56] SPEAKER: Like, I'm trying to get a sense of what there,
[19:58] SPEAKER: what was in the market before the Voodoo,
[20:00] SPEAKER: but when that kind of, you know,
[20:02] SPEAKER: obviously that revolutionized everything, but like-
[20:05] SPEAKER: - Well, so like I bought a Rage 2 card
[20:07] SPEAKER: when I built a PC the first time.
[20:09] SPEAKER: - Okay.
[20:10] SPEAKER: - Or, and put that in, it may have been even before that,
[20:15] SPEAKER: it may have been in my, in the Pentium 60
[20:18] SPEAKER: that I bought when I went to UT.
[20:20] SPEAKER: And like, I was kind of unimpressed with it.
[20:23] SPEAKER: Like 3D accelerators until the Voodoo card
[20:26] SPEAKER: seemed like kind of like,
[20:28] SPEAKER: it seemed like a cool thing for SGI to do.
[20:31] SPEAKER: And it seemed like something that wasn't real
[20:33] SPEAKER: for people at home.
[20:34] SPEAKER: So like, if you played like the rendition
[20:38] SPEAKER: V Quake port that they made.
[20:39] SPEAKER: So the other thing that's important to note
[20:41] SPEAKER: is that up until Quake,
[20:44] SPEAKER: most games only supported external,
[20:48] SPEAKER: like a proprietary vendor specific APIs.
[20:51] SPEAKER: So like Glide for 3FX.
[20:53] SPEAKER: - Glide is the famous example.
[20:54] SPEAKER: - Exactly, rendition wrote V Quake,
[20:58] SPEAKER: which was for their Verite would be with that V1000.
[21:01] SPEAKER: - Oh, V Quake.
[21:02] SPEAKER: - And I think Carmack helped with that, obviously.
[21:05] SPEAKER: - So I'm, not to derail, but I'm sitting here,
[21:07] SPEAKER: there is, of course, there is a GitHub repo
[21:09] SPEAKER: that has every plan file update he ever wrote.
[21:14] SPEAKER: So I'm just sitting here control F-ing it.
[21:17] SPEAKER: And it's funny, like, so Quake came out in mid 96
[21:19] SPEAKER: and I'm sitting here looking at an entry
[21:20] SPEAKER: for December 13th, 96, where he says for the record,
[21:25] SPEAKER: here is my impression of the 3D hardware
[21:26] SPEAKER: I have worked with, blah, blah, blah.
[21:28] SPEAKER: - This was a defining moment for me, this plan file.
[21:31] SPEAKER: - So basically the two consumer cards on this list
[21:35] SPEAKER: are the rendition Verite at $150
[21:38] SPEAKER: and the 3D effects Voodoo at $300.
[21:41] SPEAKER: - Yep.
[21:42] SPEAKER: - And then like eight or 10 workstation cards
[21:45] SPEAKER: that no mortal could ever have contact with.
[21:47] SPEAKER: - The 3D Labs one, the SGI Herrick stuff.
[21:50] SPEAKER: - The Intergraph Intense 3D, the SGI 02,
[21:53] SPEAKER: the SGI Impact, the, let's see.
[21:56] SPEAKER: - Just to be clear, the SGI 02 was like a $50,000 computer,
[21:59] SPEAKER: as I recall.
[22:00] SPEAKER: - Yes, that literally, this SGI Impact entry,
[22:02] SPEAKER: he said here a full system was literally 25 to $50,000.
[22:06] SPEAKER: - Yeah.
[22:06] SPEAKER: - And SGI Infinite Reality was over $100,000.
[22:09] SPEAKER: - Yeah, and those machines, those boxes for those things
[22:12] SPEAKER: were huge, like they were like mini computer type spaces,
[22:16] SPEAKER: not PCs.
[22:17] SPEAKER: - His quick write-up of the SGI Infinite Reality,
[22:20] SPEAKER: which is the $100,000 workstation,
[22:23] SPEAKER: fill rate from hell, polygons from hell,
[22:26] SPEAKER: if you don't trip up on state changes,
[22:27] SPEAKER: nothing will come within shouting distance of the system,
[22:30] SPEAKER: you would expect that.
[22:31] SPEAKER: - Yeah, for 100%.
[22:32] SPEAKER: - The reason I bring this up is that like,
[22:34] SPEAKER: like I said, outside of the Verite and the Voodoo,
[22:37] SPEAKER: like everything else on here is extremely high-end
[22:39] SPEAKER: workstation hardware, there just wasn't that much out there.
[22:41] SPEAKER: Sorry, there was one other card on here,
[22:43] SPEAKER: the 3D Labs Per Media for $300.
[22:45] SPEAKER: - That was a workstation card.
[22:47] SPEAKER: - Yeah, okay, yes.
[22:48] SPEAKER: - A well-supported low-end OpenGL card,
[22:51] SPEAKER: so I guess, yeah, that would be for workstation stuff.
[22:53] SPEAKER: - So it was a thing, if I recall correctly,
[22:55] SPEAKER: it had a, it was the least expensive way
[22:58] SPEAKER: to get a fully fledged OpenGL stack,
[23:00] SPEAKER: because the OpenGL driver for the 3D effects cards
[23:06] SPEAKER: was just a wrapper, so it wrapped the OpenGL calls
[23:10] SPEAKER: to Glide calls.
[23:11] SPEAKER: - Okay.
[23:12] SPEAKER: - And it wasn't, like, it wasn't a full implementation,
[23:14] SPEAKER: and because that card was a standalone 3D accelerator
[23:16] SPEAKER: and couldn't do stuff in Windows, a lot of OpenGL stuff,
[23:19] SPEAKER: like you couldn't run your OpenGL CAD programs on that.
[23:22] SPEAKER: - Right.
[23:23] SPEAKER: - Also, probably 'cause it didn't have a memory.
[23:25] SPEAKER: - And so that's why you were having to get
[23:26] SPEAKER: a bespoke version of Quake for every card, right?
[23:29] SPEAKER: - Exactly.
[23:30] SPEAKER: - Quake, GLQuake, 'cause they were all being written
[23:31] SPEAKER: directly to what those cards could do.
[23:33] SPEAKER: - Well, so GLQuake was written for OpenGL.
[23:35] SPEAKER: - Oh, right, right, yes, it would run on any GL hardware.
[23:37] SPEAKER: - Yeah, VQuake, so Carmack did VQuake
[23:40] SPEAKER: with the rendition people, I think,
[23:41] SPEAKER: and then after that, he was like,
[23:43] SPEAKER: "I'm not building a bunch of proprietary Quakes.
[23:47] SPEAKER: "There's no other, we're gonna do this in OpenGL."
[23:49] SPEAKER: And like, that immediately made OpenGL a gaming API
[23:53] SPEAKER: when it had previously been for the, like, workstations
[23:58] SPEAKER: and CAD and stuff like that.
[24:00] SPEAKER: - Previously had been for doing your effects
[24:02] SPEAKER: in Terminator 2 and Jurassic Park.
[24:03] SPEAKER: - Pretty much, yeah.
[24:04] SPEAKER: - And stuff like that.
[24:05] SPEAKER: - It was a weird, it was a weird time, like--
[24:07] SPEAKER: - It was a really weird, interesting time
[24:09] SPEAKER: with all this stuff being very emergent
[24:10] SPEAKER: and not well-defined, like, I'd not to,
[24:12] SPEAKER: we won't harp on his plan files for this whole episode,
[24:15] SPEAKER: but if you scroll down two more entries
[24:17] SPEAKER: past the one I was just reading from,
[24:19] SPEAKER: you get to what I consider
[24:20] SPEAKER: probably the seminal plan update.
[24:22] SPEAKER: - Okay.
[24:23] SPEAKER: - Which is December 23rd, 1996,
[24:25] SPEAKER: entitled OpenGL versus Direct3D.
[24:28] SPEAKER: - Oh, and this was when they were talking about,
[24:29] SPEAKER: this was before Direct3D was even out, right?
[24:31] SPEAKER: - Right.
[24:32] SPEAKER: - Or '96, you said?
[24:34] SPEAKER: - Yeah, this was December '96,
[24:35] SPEAKER: so that's like six-ish months after Quake came out.
[24:38] SPEAKER: - Oh, so that's after, that's when Direct3D 3.0,
[24:41] SPEAKER: DirectX 3.0 had launched in September of that year,
[24:45] SPEAKER: and we were, like, DirectX 1 and 2
[24:47] SPEAKER: were kind of, like, not worth speaking of.
[24:50] SPEAKER: - Right, and like, this is full-on, like, soapbox mode,
[24:53] SPEAKER: he's just here kinda opining about how these things work
[24:58] SPEAKER: and how much he likes or hates them,
[25:00] SPEAKER: and there's like straight-up,
[25:01] SPEAKER: there's straight-up code snippets in this thing
[25:02] SPEAKER: of, like, showing how Vertex operations work
[25:04] SPEAKER: in each one and stuff like this,
[25:06] SPEAKER: but it was just such a, it was such an early time,
[25:09] SPEAKER: and the stuff was so ill-defined
[25:10] SPEAKER: and, like, all over the place, you know?
[25:12] SPEAKER: - Well, I mean, the big argument was that
[25:15] SPEAKER: the DirectX APIs kind of limited what you could do,
[25:21] SPEAKER: like, well, it didn't give you direct control
[25:23] SPEAKER: over the hardware in a way that was,
[25:25] SPEAKER: it abstracted things out a little bit further
[25:27] SPEAKER: than people like Carmack wanted.
[25:30] SPEAKER: I think in the, with the idea that it would be easier
[25:33] SPEAKER: for normal human programmers that weren't John Carmack
[25:36] SPEAKER: or Tim Sweeney or, you know, Charlie Brown
[25:38] SPEAKER: or whoever to build off of.
[25:40] SPEAKER: - Right, but also, it became necessary in a world
[25:43] SPEAKER: with, like, 800 different cards on the market, right?
[25:46] SPEAKER: Like, at some point, you can't be writing directly
[25:48] SPEAKER: to the hardware of every model of card out there.
[25:50] SPEAKER: - Well, so then it shifted the burden from the developers
[25:54] SPEAKER: to write for the individual hardware to the driver vendors
[25:56] SPEAKER: to, like, not jack up the drivers.
[25:58] SPEAKER: - Ah, yes, which led to our current state
[26:01] SPEAKER: of 500-megabyte graphics driver downloads every two weeks.
[26:04] SPEAKER: - Yeah, exactly.
[26:06] SPEAKER: - That makes sense, but was there a lot of, like,
[26:09] SPEAKER: FUD around Microsoft?
[26:10] SPEAKER: I feel like I vaguely remember, like, Jesus.
[26:14] SPEAKER: I mean, this was-
[26:14] SPEAKER: - Was there FUD?
[26:16] SPEAKER: - This was squarely in the middle of the, like,
[26:18] SPEAKER: people writing Microsoft with a dollar sign in it era
[26:21] SPEAKER: of people not trusting Microsoft.
[26:23] SPEAKER: - This is when they were being,
[26:24] SPEAKER: this is when the antitrust suit was in the,
[26:26] SPEAKER: in the bearish beginnings, right?
[26:28] SPEAKER: - I guess so, yeah.
[26:29] SPEAKER: - This is when they were doing the stuff
[26:30] SPEAKER: that got them sued by the federal government for-
[26:33] SPEAKER: - That's fair.
[26:34] SPEAKER: - Yeah.
[26:35] SPEAKER: It was-
[26:36] SPEAKER: - Embrace, extend, extinguish.
[26:37] SPEAKER: - Like, yeah, I feel like,
[26:39] SPEAKER: I feel like a lot of the concern about,
[26:42] SPEAKER: the concern about Microsoft owning the APIs that drove 3D
[26:45] SPEAKER: was the same thing that we hear people talking about
[26:47] SPEAKER: with Facebook and VR right now, where, you know,
[26:50] SPEAKER: you didn't want this monolithic company to own
[26:54] SPEAKER: the thing that the future, you know,
[26:56] SPEAKER: the APIs that the future was built on.
[26:59] SPEAKER: It ended up, like, the thing that ended up happening is,
[27:03] SPEAKER: as the hardware vendors coalesced into,
[27:06] SPEAKER: from eight or nine vendors into two vendors,
[27:09] SPEAKER: or maybe three if you count Intel,
[27:12] SPEAKER: the, it ended up being the hardware vendors
[27:14] SPEAKER: driving those APIs as much as Microsoft.
[27:17] SPEAKER: So it, like, it ended up working out.
[27:19] SPEAKER: If we had only ended up with one,
[27:22] SPEAKER: if we only ended up with either Intel or AMD,
[27:24] SPEAKER: ATI and Intel, I think we'd be in a much different situation
[27:29] SPEAKER: and we wouldn't be seeing the kind of performance
[27:30] SPEAKER: that we are on graphics today.
[27:32] SPEAKER: So it was lucky that those two companies survived.
[27:35] SPEAKER: - 'Cause they pushed it forward so much.
[27:38] SPEAKER: - They push each other, yeah.
[27:39] SPEAKER: - Yeah, yeah.
[27:40] SPEAKER: - The competition's good, it turns out.
[27:41] SPEAKER: - Yeah, before we move on too much
[27:43] SPEAKER: from the beginnings here,
[27:44] SPEAKER: I happen to have the rendition Wikipedia page
[27:46] SPEAKER: in front of me, and I just have to mention the naming
[27:49] SPEAKER: on some of this stuff.
[27:50] SPEAKER: - Yeah.
[27:51] SPEAKER: - They had an API for DOS called Speedy 3D.
[27:54] SPEAKER: - That sounds great.
[27:55] SPEAKER: How fast was it?
[27:56] SPEAKER: Was it speedy? - I don't know, I just,
[27:58] SPEAKER: like I just can't help thinking about
[27:59] SPEAKER: like Speedy Gonzalez here,
[28:01] SPEAKER: scrolling down some of the products
[28:05] SPEAKER: that were released to Sierra.
[28:07] SPEAKER: Wait, that can't be, that's not the game maker Sierra.
[28:09] SPEAKER: That's gotta be, really?
[28:10] SPEAKER: - I think that's somebody else.
[28:11] SPEAKER: I think that's what became Sierra's logic maybe.
[28:13] SPEAKER: - No, it totally links to the Sierra online Wikipedia page.
[28:17] SPEAKER: Apparently Sierra put out a rendition card
[28:19] SPEAKER: called the Screamin' 3D.
[28:21] SPEAKER: - Oh yeah, we had one of those in the lab at maximum PC.
[28:24] SPEAKER: - Really?
[28:25] SPEAKER: - It was the box was on the wall.
[28:26] SPEAKER: - I totally am sitting here Googling the box art
[28:29] SPEAKER: for Screamin' 3D right now.
[28:31] SPEAKER: I need to see that.
[28:32] SPEAKER: - Oh, the box art for these was all bad.
[28:35] SPEAKER: - If you think video card boxes are ridiculous now,
[28:37] SPEAKER: go back to the mid nineties.
[28:39] SPEAKER: - Oh yeah.
[28:41] SPEAKER: - But anyway, so yeah, like I don't know
[28:45] SPEAKER: where to go with this.
[28:46] SPEAKER: I mean, rendition was out there like in my mind,
[28:48] SPEAKER: like some months before the Voodoo came along,
[28:51] SPEAKER: the quake was a thing.
[28:52] SPEAKER: - That's correct, yeah.
[28:53] SPEAKER: - And then the Voodoo came along
[28:54] SPEAKER: and like changed everything of course,
[28:56] SPEAKER: but to touch on something you mentioned earlier,
[28:58] SPEAKER: I did not realize that it was the,
[29:01] SPEAKER: I didn't realize the Voodoo was the exception
[29:02] SPEAKER: to the rule about being an all-in-one integrated card.
[29:04] SPEAKER: Like 'cause the Voodoo was an add-in card
[29:07] SPEAKER: and you had to run a literal analog pass-through cable.
[29:10] SPEAKER: - You plug your video, you had a little short VGA cable
[29:13] SPEAKER: that plugged from your main video card into the Voodoo card.
[29:15] SPEAKER: - Yeah, your desktop card.
[29:17] SPEAKER: - Yeah, and then you plugged the monitor
[29:18] SPEAKER: into the Voodoo card and then literally do a state switch.
[29:22] SPEAKER: Like the Voodoo card would detect
[29:23] SPEAKER: that you'd launched something that used Glide
[29:24] SPEAKER: and it would turn off the pass-through
[29:27] SPEAKER: and just render itself.
[29:28] SPEAKER: - You would, at least with the card I had,
[29:30] SPEAKER: which I believe was the Orchid Righteous 3D is the one I had.
[29:33] SPEAKER: - Oh yeah, that was one of the two.
[29:35] SPEAKER: It was that or the Diamond Monster 3D.
[29:37] SPEAKER: - It was not the Diamond Monster,
[29:38] SPEAKER: which was the gold standard to most people, but-
[29:40] SPEAKER: - I think they were both exactly the same cards,
[29:42] SPEAKER: just to be clear.
[29:43] SPEAKER: - They were all practically the same,
[29:44] SPEAKER: except now seems like the time to touch on my teenage lust
[29:47] SPEAKER: for the Canopus Pure 3D.
[29:49] SPEAKER: - No, that was a card.
[29:50] SPEAKER: - Which was just a Voodoo card,
[29:51] SPEAKER: except it had two extra megabytes of memory.
[29:54] SPEAKER: I think it had six megabytes of memory on it.
[29:55] SPEAKER: - Well, Canopus did some other weird stuff too,
[29:57] SPEAKER: 'cause they had an integrated card
[29:59] SPEAKER: that was like a 2D card with a daughter card on it
[30:04] SPEAKER: that was the 3D FX card.
[30:06] SPEAKER: So it was all in one thing and it,
[30:08] SPEAKER: also Canopus did internal pass-throughs
[30:12] SPEAKER: if you had a Canopus 2D card and a Canopus 3D card.
[30:15] SPEAKER: - Maybe that's what I was interested in.
[30:17] SPEAKER: They were, I believe that was a Japanese company.
[30:20] SPEAKER: - So yeah, they made arcade boards
[30:22] SPEAKER: was the other thing they did,
[30:23] SPEAKER: 'cause they did those obsidian,
[30:27] SPEAKER: I wanna say, what was that jet,
[30:30] SPEAKER: the jet ski race game, the arcade game?
[30:39] SPEAKER: Anyway.
[30:40] SPEAKER: - Just pretend we remembered.
[30:41] SPEAKER: - Yeah, they made,
[30:42] SPEAKER: people are screaming at their radios right now,
[30:44] SPEAKER: but they made a bunch of,
[30:46] SPEAKER: they made the 3D,
[30:48] SPEAKER: like for a lot of those early arcade cabinets
[30:51] SPEAKER: that were driven by 3D FX hardware,
[30:54] SPEAKER: they made those boards and put enough RAM on them
[30:56] SPEAKER: that they could run at like arcade resolutions.
[31:00] SPEAKER: And they would also jam multiple texturing units on,
[31:03] SPEAKER: which is like, that's the interesting thing about the,
[31:07] SPEAKER: so first off, all of these cards are passively cooled.
[31:09] SPEAKER: At most they had a heat sink,
[31:11] SPEAKER: which was sometimes viewed as a negative
[31:13] SPEAKER: in the press at the time.
[31:15] SPEAKER: - Right.
[31:16] SPEAKER: I'm sitting here looking at the Canopus Wikipedia page,
[31:19] SPEAKER: which is very short, it's like three paragraphs,
[31:21] SPEAKER: but it says when the Voodoo 2 was released,
[31:23] SPEAKER: the Canopus Pure 3D 2 was praised for the fact
[31:26] SPEAKER: that their cards were shorter
[31:27] SPEAKER: than the competitors Voodoo 2 cards.
[31:29] SPEAKER: - Yeah, yeah, it fit in more cases.
[31:30] SPEAKER: Well, like, so I had an AST Pentium 60 at that point,
[31:35] SPEAKER: I think, and that card was a pizza box case.
[31:38] SPEAKER: And like, there were a small number,
[31:40] SPEAKER: like if you had a giant long chonker video card,
[31:43] SPEAKER: it just wouldn't go in there.
[31:45] SPEAKER: - Right, but God was like, was the mentality basically
[31:48] SPEAKER: that if you need a heat sink on your card,
[31:49] SPEAKER: you have screwed up on the design end somehow?
[31:51] SPEAKER: - Pretty much, yeah.
[31:52] SPEAKER: Like my Pentium 60 didn't have a heat sink.
[31:54] SPEAKER: It was just a bare chip.
[31:55] SPEAKER: - My Pentium 75 did not either,
[31:57] SPEAKER: and that machine became quite unstable over time.
[31:59] SPEAKER: - Shocking that, who knew?
[32:01] SPEAKER: - Granted, to be fair, I had overclocked it to 75,
[32:03] SPEAKER: so that probably, or no, no, no, I'm sorry.
[32:05] SPEAKER: It was a 75 to 90.
[32:06] SPEAKER: - Yeah, that was the job.
[32:07] SPEAKER: - I had a 75, and it was not stable at 100,
[32:10] SPEAKER: but I could overclock it to 90,
[32:12] SPEAKER: and then it became borderline unusable after about a year.
[32:16] SPEAKER: - Yeah, weird, weird that.
[32:18] SPEAKER: - I was gonna mention with the pass-through
[32:21] SPEAKER: on the Voodoo cards,
[32:23] SPEAKER: I don't know if it was just the one I had,
[32:24] SPEAKER: or maybe they all did this,
[32:25] SPEAKER: but you would hear that good solid metallic thunk sound
[32:29] SPEAKER: every time it switched over to the 3D card.
[32:31] SPEAKER: - Yeah, I think that was in the monitor though, wasn't it?
[32:34] SPEAKER: 'Cause it was a refresh change, probably.
[32:35] SPEAKER: - Maybe it was the monitor, I swear.
[32:36] SPEAKER: - It was like a kachunk.
[32:38] SPEAKER: - Yeah.
[32:40] SPEAKER: - There wasn't like a physical switch in the cards though.
[32:42] SPEAKER: - No, no, no, no.
[32:43] SPEAKER: - There was no solenoid popping or anything like that.
[32:44] SPEAKER: - You think it was more of a kachunk than a thunk?
[32:46] SPEAKER: - So they did, 3DFX did the,
[32:49] SPEAKER: there's a lot, it was a weird time because it also,
[32:55] SPEAKER: so what a 3D, these things weren't called GPUs
[32:59] SPEAKER: 'cause there wasn't a lot of processing.
[33:00] SPEAKER: Basically they were just texture mapping engines on a card.
[33:03] SPEAKER: - I think 3D accelerator was the accepted term back then.
[33:06] SPEAKER: - That's what we called them, yeah.
[33:08] SPEAKER: And they would, basically the CPU would do
[33:12] SPEAKER: all the triangle setup and all that stuff,
[33:14] SPEAKER: and it would establish a mesh,
[33:15] SPEAKER: and then the video cards would handle Z buffering,
[33:18] SPEAKER: so they'd see what was visible in that scene,
[33:21] SPEAKER: and then they'd apply textures to it.
[33:23] SPEAKER: And there were a wide variety of approaches to that.
[33:27] SPEAKER: Power VR did this tile-based thing
[33:30] SPEAKER: where they didn't do visibility checks
[33:35] SPEAKER: on the whole scene at once.
[33:36] SPEAKER: They would just do the little chunks,
[33:38] SPEAKER: and then that would save them a buttload
[33:40] SPEAKER: of memory bandwidth, basically,
[33:41] SPEAKER: 'cause they were only pulling textures
[33:43] SPEAKER: for things that they would actually map.
[33:45] SPEAKER: As I recall, that was also one of the ones
[33:47] SPEAKER: that had problems in their OpenGL stack
[33:50] SPEAKER: where there were giant cracks in the world
[33:52] SPEAKER: where the tiles didn't line up right or something.
[33:54] SPEAKER: I don't know exactly what was happening there,
[33:56] SPEAKER: but I remember in that instance it was bad.
[34:01] SPEAKER: The other thing that was weird about Power VR
[34:02] SPEAKER: was it was a standalone 3D accelerator,
[34:05] SPEAKER: but you could do 3D in a window on that
[34:09] SPEAKER: because it passed over to the 2D cards frame buffer
[34:14] SPEAKER: across PCI. - Oh, interesting.
[34:16] SPEAKER: Right, I don't know if we mentioned it.
[34:17] SPEAKER: That was another limitation of the Voodoo
[34:18] SPEAKER: was that it could not do window 3D, only full screen.
[34:21] SPEAKER: - No window 3D on the Voodoo 1 or Voodoo 2,
[34:23] SPEAKER: only on the Rush and the Banshee and the 3D eventually.
[34:26] SPEAKER: - Right, right, those were their integrated cards.
[34:28] SPEAKER: The other downside that I didn't mention of,
[34:30] SPEAKER: and then maybe this was also model-specific,
[34:32] SPEAKER: but it made my 2D desktop look like shit.
[34:34] SPEAKER: - It made everything fuzzy, yeah.
[34:35] SPEAKER: - Which made me want to die
[34:37] SPEAKER: because that was right after I got a Matrox millennium.
[34:40] SPEAKER: I finally got the good 2D desktop card
[34:43] SPEAKER: that made everything nice and sharp and smooth.
[34:44] SPEAKER: - Oh no. - And then I got a Voodoo
[34:46] SPEAKER: and it made it look like shit again.
[34:48] SPEAKER: - So the other thing about all of these cards
[34:50] SPEAKER: is that they were really low resolution.
[34:52] SPEAKER: Like at a time when a normal desktop
[34:55] SPEAKER: was probably 800 by 600,
[34:57] SPEAKER: I don't think you could run a Voodoo 1 card
[34:59] SPEAKER: above 640 by 480.
[35:01] SPEAKER: - No, definitely not at any, maybe not at all,
[35:04] SPEAKER: but definitely not at any level of performance.
[35:06] SPEAKER: - Yeah, sure. - Yeah, and like,
[35:11] SPEAKER: the thing that was amazing about those early cards
[35:14] SPEAKER: is you went from like these kind of not grainy exactly,
[35:18] SPEAKER: but it just felt, it was real grungy.
[35:21] SPEAKER: Software rendering in Quake,
[35:22] SPEAKER: while a technical Marvel was kind of scuzzy feeling.
[35:28] SPEAKER: And then when you loaded up something
[35:30] SPEAKER: that could do mipmapping on the textures,
[35:32] SPEAKER: which is basically where it looks,
[35:34] SPEAKER: it has different resolutions of the texture
[35:36] SPEAKER: and the video card knows to drop the right one
[35:39] SPEAKER: in at the right distances.
[35:41] SPEAKER: You got these unbelievably clear textures.
[35:43] SPEAKER: You're like, wait,
[35:43] SPEAKER: is this what this game is supposed to look like?
[35:45] SPEAKER: And I played it all the way through not looking like this?
[35:48] SPEAKER: This is kind of magic.
[35:50] SPEAKER: And then games like, and still,
[35:54] SPEAKER: like if you're looking at a texture
[35:55] SPEAKER: that would have had multiple mipmap levels across,
[35:59] SPEAKER: like if you're looking down the length of a wall, right?
[36:02] SPEAKER: You would get one of the mipmap levels in the wall
[36:04] SPEAKER: 'cause we didn't have a nice tropic filtering
[36:06] SPEAKER: or trilinear filtering or anything like that
[36:07] SPEAKER: on the cards at that point.
[36:08] SPEAKER: So it wasn't able to sample different mip levels
[36:10] SPEAKER: based on where the,
[36:14] SPEAKER: for the different distances of that same texture
[36:17] SPEAKER: that you were looking at.
[36:19] SPEAKER: But it was still kind of incredible.
[36:21] SPEAKER: And then when the Voodoo 2 came out,
[36:24] SPEAKER: all of a sudden you had multi-texturing
[36:25] SPEAKER: that could happen in one pass.
[36:28] SPEAKER: So like each frame could have multiple,
[36:30] SPEAKER: two textures applied to each surface.
[36:33] SPEAKER: So you'd have like a lighting texture and a picture texture.
[36:38] SPEAKER: Right?
[36:38] SPEAKER: Okay.
[36:40] SPEAKER: Trying to think of some other
[36:41] SPEAKER: like real world use cases for that.
[36:42] SPEAKER: I mean, is that when you were able to start applying
[36:44] SPEAKER: like decals to walls, like bullet holes and blood
[36:46] SPEAKER: and stuff like that, or?
[36:47] SPEAKER: That was probably later.
[36:48] SPEAKER: 'Cause I feel like the Voodoo 2 actually had,
[36:50] SPEAKER: like there were three chips on the texture, on the chip.
[36:52] SPEAKER: There was one that was the main, the FX chip,
[36:55] SPEAKER: and then there were two TX chips
[36:57] SPEAKER: that each was responsible for one texture pass
[37:00] SPEAKER: per cycle per frame.
[37:02] SPEAKER: So you could do that before,
[37:06] SPEAKER: but it would take multiple passes on each frame to do it.
[37:12] SPEAKER: To do a multi-texturing pass is my understanding,
[37:14] SPEAKER: but I could be wrong.
[37:15] SPEAKER: I don't know.
[37:16] SPEAKER: This was from a time before
[37:18] SPEAKER: when people talked about this stuff.
[37:19] SPEAKER: Like now Nvidia and ATI, when they release new GPUs,
[37:24] SPEAKER: they dump, they sit down with all the tech press
[37:26] SPEAKER: and they're like, okay, here's exactly how this stuff works.
[37:28] SPEAKER: Here's how deep the pipelines go.
[37:30] SPEAKER: Here's how much cache each part has.
[37:32] SPEAKER: Here's what the programmable parts
[37:34] SPEAKER: of the pipeline are capable of.
[37:36] SPEAKER: And back then they just released the cards
[37:38] SPEAKER: and there was a like one page spec sheet
[37:39] SPEAKER: that they handed out to people at Comdex
[37:42] SPEAKER: when they wanted to buy, when they came in
[37:44] SPEAKER: and like compact rolled in and they're like,
[37:46] SPEAKER: well, here's what our new video card can do.
[37:48] SPEAKER: It's like, it costs this much.
[37:50] SPEAKER: It's gonna get this many blit marks and it'll run Quake.
[37:57] SPEAKER: And people are like, okay.
[37:58] SPEAKER: And we're putting that in every compact
[38:00] SPEAKER: that we're shipping this year.
[38:01] SPEAKER: - Good enough.
[38:02] SPEAKER: - Yeah.
[38:03] SPEAKER: - Ship it.
[38:04] SPEAKER: - It was a weird time, for sure.
[38:07] SPEAKER: - Was the Voodoo 2 another pass-through card?
[38:09] SPEAKER: That was still not a full one.
[38:10] SPEAKER: - Voodoo 2 was a pass-through card.
[38:11] SPEAKER: - Still not a full desktop card, right?
[38:13] SPEAKER: - But also the Voodoo 2 had an internal SLI port
[38:16] SPEAKER: so you could put two of them in.
[38:18] SPEAKER: - Oh God, is that when SLI started?
[38:19] SPEAKER: - That's when SLI started and it would let you play it,
[38:21] SPEAKER: I think, 1280, 1024 by 768 if you had two of them in SLI.
[38:27] SPEAKER: And the funny thing is, because of the way that card worked,
[38:30] SPEAKER: it is maybe the last time that adding a second video card
[38:33] SPEAKER: to your system gave you a one-to-one increase
[38:36] SPEAKER: in performance for each,
[38:37] SPEAKER: like you get double the performance for each.
[38:39] SPEAKER: Assuming, again, because all of the triangle setup
[38:43] SPEAKER: and all of that stuff was done on the CPU,
[38:44] SPEAKER: assuming your CPUs had a fast enough floating point
[38:47] SPEAKER: to do that.
[38:48] SPEAKER: - So they set very poor expectations for SLI early on
[38:51] SPEAKER: that it never lived up to again.
[38:52] SPEAKER: - Well, but also, when I upgraded from a Voodoo 1
[38:56] SPEAKER: to a Voodoo 2, I was on a K6, like 166 or 200
[39:01] SPEAKER: or something that had bad floating point
[39:02] SPEAKER: but good integer math.
[39:04] SPEAKER: And it turned out that I saw no performance increase
[39:08] SPEAKER: going from the Voodoo 1 to the Voodoo 2
[39:11] SPEAKER: because the CPU couldn't keep up with the card at all.
[39:15] SPEAKER: Everything was CPU bound then.
[39:17] SPEAKER: - So, hmm, like there's a couple of stories here.
[39:21] SPEAKER: I mean, there's the thing where 80% of these companies
[39:25] SPEAKER: just fell away and either got acquired
[39:27] SPEAKER: or went out of business or whatever.
[39:29] SPEAKER: - Well, that happens when there's a big shift in the way,
[39:32] SPEAKER: like it happened with phones too, right?
[39:35] SPEAKER: Like when the iPhone came out and Android rolled out,
[39:38] SPEAKER: Nokia and Motorola and all those companies
[39:42] SPEAKER: that had been making dumb phones for 10, 15, 20 years,
[39:47] SPEAKER: a lot of them didn't survive that transition.
[39:50] SPEAKER: - I mean, I guess it's the natural evolution
[39:51] SPEAKER: of a new market being created essentially, right?
[39:53] SPEAKER: 'Cause that's what happened with phones
[39:54] SPEAKER: and that's what happened here.
[39:56] SPEAKER: There was no market for 3D accelerators and then there was.
[39:58] SPEAKER: And so everybody tried to get in
[39:59] SPEAKER: and then only a couple of them made it out.
[40:01] SPEAKER: - Well, and even the ones that did make it out,
[40:05] SPEAKER: like 3D effects got bought by Nvidia
[40:07] SPEAKER: in the early 2000s, right?
[40:09] SPEAKER: - So that's like, there are two stories here.
[40:11] SPEAKER: There's the story of when I got a TNT
[40:13] SPEAKER: and like everything changed.
[40:14] SPEAKER: - Yeah, yeah.
[40:15] SPEAKER: - That was, that like the Voodoo
[40:17] SPEAKER: was like an amazing proof of concept
[40:18] SPEAKER: but the TNT was the first Nvidia card
[40:21] SPEAKER: for people who don't know.
[40:23] SPEAKER: So like those are the kind of twin narratives here
[40:25] SPEAKER: are I got my first Nvidia card and granted,
[40:28] SPEAKER: I had sounds like the first couple of Nvidia cards
[40:30] SPEAKER: were not amazing,
[40:31] SPEAKER: but the TNT was kind of mind blowing at the time.
[40:34] SPEAKER: So there's like kind of the rise of Nvidia
[40:36] SPEAKER: and the all-in-one card that was actually very good.
[40:38] SPEAKER: And then there is the like meteoric rise
[40:41] SPEAKER: and fall of 3D effects.
[40:43] SPEAKER: Like 3D effects went from the name in 3D graphics
[40:45] SPEAKER: to not even a going concern in the space of like,
[40:49] SPEAKER: what, four years?
[40:50] SPEAKER: - Five years, I think, yeah.
[40:51] SPEAKER: - Like they got, I think they got acquired
[40:53] SPEAKER: by Nvidia in 2000 ish.
[40:55] SPEAKER: - It was right when I started at Maximum PC, as I recall,
[40:58] SPEAKER: 'cause they sent us a Voodoo five 6,000.
[41:03] SPEAKER: - Right.
[41:03] SPEAKER: - Like a proto board with like wires dangling off of it
[41:06] SPEAKER: that where it was an engineering sample.
[41:08] SPEAKER: - Like the Voodoo five even make it to market?
[41:10] SPEAKER: - Never made it, maybe the low end version did,
[41:13] SPEAKER: but the big, the four processor one
[41:15] SPEAKER: never made it to market.
[41:16] SPEAKER: - Right, so like for them to go from the card to get
[41:20] SPEAKER: in the Voodoo and Voodoo two era to like,
[41:23] SPEAKER: I assume they basically sold at fire sale prices
[41:25] SPEAKER: to Nvidia.
[41:27] SPEAKER: - I mean, I think they bought IP and engineers
[41:29] SPEAKER: and that was it.
[41:30] SPEAKER: - Right, right.
[41:31] SPEAKER: - So the thing that's, the TNT is an interesting card
[41:35] SPEAKER: 'cause like TNT and Rage Pro,
[41:38] SPEAKER: like both of those are really important.
[41:39] SPEAKER: Rage Pro was in a lot of gateway machines, as I recall,
[41:43] SPEAKER: and Dell machines.
[41:44] SPEAKER: So like if you were buying computers for,
[41:48] SPEAKER: (sneezes)
[41:49] SPEAKER: Excuse me, say a computer lab in 2000, '98, '99,
[41:54] SPEAKER: all of a sudden, like a commodity computer could run Quake.
[41:58] SPEAKER: Right, so it wasn't like you needed some weird add-in
[42:01] SPEAKER: video card that made your 2D desktop look like crap
[42:03] SPEAKER: and was gonna have all sorts of weird requirements.
[42:08] SPEAKER: It just worked.
[42:10] SPEAKER: - And that was GLQuake?
[42:11] SPEAKER: - That was GLQuake, yeah.
[42:13] SPEAKER: The TNT was the higher end version of that.
[42:16] SPEAKER: The TNT was a really compelling part at,
[42:19] SPEAKER: like when the Revo 128 launched,
[42:21] SPEAKER: there was, I think I sent you last night,
[42:23] SPEAKER: was there was a big interview in boot in like '96,
[42:26] SPEAKER: I guess, or '97, maybe even '98,
[42:29] SPEAKER: where David Kirk, who was the chief scientist at Nvidia
[42:32] SPEAKER: for a long time, was basically doing the apology tour
[42:36] SPEAKER: for Revo 128 driver problems
[42:39] SPEAKER: and overall shortcomings in that part.
[42:41] SPEAKER: And then they rolled out the TNT,
[42:43] SPEAKER: which he had hinted at in that interview.
[42:46] SPEAKER: And it was, A, the drivers were really solid,
[42:49] SPEAKER: which it was a lesson Nvidia learned early
[42:51] SPEAKER: that without good drivers,
[42:53] SPEAKER: it didn't matter how fast the hardware was.
[42:56] SPEAKER: And two, it really ripped, like it was fast.
[43:00] SPEAKER: You could run Quake in a window, you could play GLQuake,
[43:03] SPEAKER: everything, and it was performant,
[43:06] SPEAKER: and you could play at high resolutions even.
[43:09] SPEAKER: - That was my Quake 2 card, is my memory of the TNT.
[43:12] SPEAKER: A TNT maybe sometime after Quake 2 came out,
[43:15] SPEAKER: and it was also, it was an all-in-one card,
[43:18] SPEAKER: so it was nice to just have one card that did desktop
[43:21] SPEAKER: and really nice 3D graphics, but also, yeah,
[43:23] SPEAKER: it was fast as hell in my memory.
[43:27] SPEAKER: - So it's funny, for a long time,
[43:28] SPEAKER: I had a TNT card and a Voodoo card in my computer
[43:32] SPEAKER: at the same time, just because it was still,
[43:36] SPEAKER: like Quake 1 still worked better on the Voodoo card
[43:39] SPEAKER: than it did on the TNT card
[43:40] SPEAKER: because of driver implementation weirdness.
[43:43] SPEAKER: - Okay, sure.
[43:43] SPEAKER: - And I was still playing competitive Quake 1
[43:46] SPEAKER: on the LPB leagues at that point.
[43:49] SPEAKER: - Sure.
[43:50] SPEAKER: - Or the HPB leagues, sorry, the hyping people leagues.
[43:54] SPEAKER: - You're talking to somebody who got,
[43:56] SPEAKER: I got a 3DFX card and started playing Quake on that
[43:59] SPEAKER: because my Pentium 75 couldn't run it for shit in software,
[44:02] SPEAKER: but then I got a Pentium 200 later,
[44:04] SPEAKER: and I was getting such a high frame rate
[44:05] SPEAKER: in software Quake on that thing
[44:07] SPEAKER: that I went back to software Quake
[44:08] SPEAKER: because I would rather have the frame rate.
[44:10] SPEAKER: - You were probably one of those people
[44:10] SPEAKER: that would have played NetQuake instead of Quake World.
[44:13] SPEAKER: - I'm not quite gonna go that far.
[44:16] SPEAKER: - We talked about those Carmack plan updates,
[44:17] SPEAKER: but I remember you'd see a new plan update from Carmack
[44:20] SPEAKER: and you're like, "Is this gonna be about Quake World?
[44:22] SPEAKER: "Is this gonna be about GLQuake?"
[44:23] SPEAKER: Either one was fine.
[44:24] SPEAKER: - Yeah, I was reading about the Quake World announcement.
[44:27] SPEAKER: I was reading that post last night
[44:29] SPEAKER: when he basically almost had in hand
[44:33] SPEAKER: came in front of the Quake community
[44:34] SPEAKER: and was just like, in so many words,
[44:36] SPEAKER: was just like, look, we get it, the internet performance
[44:40] SPEAKER: for NetQuake is unacceptable.
[44:43] SPEAKER: I'm going to fork the code base and start over
[44:46] SPEAKER: and deliver a new online client for people.
[44:48] SPEAKER: Also, there's an amazing line in there.
[44:52] SPEAKER: Gosh, I don't know if I can find it
[44:53] SPEAKER: off the top of the head right now.
[44:55] SPEAKER: - The first time I played Quake World was at my dad's office
[44:59] SPEAKER: 'cause it came out while I was home on Christmas break,
[45:02] SPEAKER: and I drove, literally got in the car
[45:03] SPEAKER: and drove to the office and downloaded it
[45:05] SPEAKER: and put it on his work computer
[45:08] SPEAKER: and played software Quake World on his modem there
[45:11] SPEAKER: 'cause we didn't have a computer at the house
[45:12] SPEAKER: at mom and dad's house at that point.
[45:14] SPEAKER: And I was just like, oh God, I can play this on the modem.
[45:16] SPEAKER: This is just a whole new world.
[45:19] SPEAKER: - Actually playable, it felt like a real video game.
[45:21] SPEAKER: This is the line from the plan file
[45:24] SPEAKER: where he basically reveals the existence of Quake World
[45:27] SPEAKER: where he describes it as a pet research project.
[45:30] SPEAKER: "If it looks feasible,
[45:31] SPEAKER: "I would like to see internet-focused gaming
[45:33] SPEAKER: "become a justifiable biz direction for us.
[45:36] SPEAKER: "It's definitely cool, but it is uncertain
[45:37] SPEAKER: "if people can actually make money at it."
[45:40] SPEAKER: - So I'm sure when he says it's uncertain
[45:42] SPEAKER: people can actually make money at it,
[45:43] SPEAKER: they were looking at those pay-to-play modem dial-in services
[45:47] SPEAKER: like Duango where you paid like five bucks a month
[45:51] SPEAKER: and you could dial into a local thing
[45:52] SPEAKER: and play Doom against other people in your town.
[45:55] SPEAKER: - Yes, obviously there were early attempts
[45:57] SPEAKER: at monetizing that kind of stuff,
[45:59] SPEAKER: but it's just in light of history
[46:00] SPEAKER: and where things have gone seeing somebody say,
[46:03] SPEAKER: "I don't know if you can make money at online gaming,
[46:05] SPEAKER: "but we're gonna mess with it."
[46:06] SPEAKER: - I don't know, man, maybe.
[46:08] SPEAKER: - Kind of amusing.
[46:10] SPEAKER: - But yeah, so we were talking about consolidation.
[46:12] SPEAKER: If we go down this list of the eight companies,
[46:14] SPEAKER: so we have 3DFX, PowerBR, Nvidia, ATI,
[46:17] SPEAKER: Matrox, S3, Intel, and Rendition.
[46:20] SPEAKER: Rendition's gone.
[46:23] SPEAKER: I actually don't know what happened to them.
[46:24] SPEAKER: - Let me see here. - I'm sure they got bought
[46:26] SPEAKER: by somebody, but 3DFX got bought by Nvidia
[46:29] SPEAKER: in the early 2000s, mostly for patents and engineers,
[46:34] SPEAKER: is my understanding.
[46:35] SPEAKER: - Micron purchased Rendition.
[46:38] SPEAKER: - Micron, the memory manufacturer?
[46:40] SPEAKER: - That's what this says.
[46:41] SPEAKER: - Wow, interesting.
[46:43] SPEAKER: - As a source of embedded graphics solutions
[46:45] SPEAKER: for their own line of motherboards.
[46:48] SPEAKER: - There you go.
[46:51] SPEAKER: PowerVR ended up focusing on mobile,
[46:54] SPEAKER: and they are one of the main SOC GPU vendors
[46:59] SPEAKER: for ARM processors.
[47:02] SPEAKER: - To this day, right? - To this day.
[47:03] SPEAKER: - That name still exists.
[47:05] SPEAKER: With a little detour into the Dreamcast.
[47:08] SPEAKER: - That's true, yeah, they did.
[47:09] SPEAKER: The V2 version of the TileVR architecture
[47:12] SPEAKER: was the thing that made the Dreamcast work.
[47:15] SPEAKER: Look, there was a lot of scene drama around the Dreamcast,
[47:17] SPEAKER: 'cause everybody thought they were going,
[47:19] SPEAKER: Sega had everybody thinking they were going
[47:20] SPEAKER: in the Dreamcast.
[47:21] SPEAKER: 3DFX sued them for $155 million.
[47:24] SPEAKER: - What?
[47:25] SPEAKER: - Yeah.
[47:26] SPEAKER: Because they had given proprietary hardware information
[47:29] SPEAKER: because they thought 3DFX was gonna power the Dreamcast.
[47:33] SPEAKER: 3DFX did a lot of arcade boards for Sega,
[47:35] SPEAKER: is my understanding, in that time period.
[47:37] SPEAKER: - I think that's right, yeah.
[47:38] SPEAKER: - I feel like somebody else also thought
[47:41] SPEAKER: they were going in the Dreamcast,
[47:43] SPEAKER: and then it turned out, going in the Dreamcast
[47:45] SPEAKER: wouldn't have helped anyone, really, probably.
[47:47] SPEAKER: - Nah, not so much.
[47:48] SPEAKER: That console lasted, what, about a year and a half?
[47:51] SPEAKER: - If that, yeah.
[47:52] SPEAKER: - Roughly.
[47:54] SPEAKER: - Okay, so PowerVR, Nvidia obviously is Nvidia,
[47:57] SPEAKER: and they're powering the future.
[47:59] SPEAKER: ATI got bought by AMD in 2006.
[48:02] SPEAKER: They spun out, they had bought BitBoy's Oi,
[48:06] SPEAKER: which was one of those hushed tones on message boards
[48:09] SPEAKER: and used net companies. - Oh my god, dude.
[48:12] SPEAKER: The game that BitBoy's was talking about,
[48:14] SPEAKER: their forthcoming product that never materialized.
[48:16] SPEAKER: - Well, and they came out of the demo scene,
[48:19] SPEAKER: like Swedish demo scene.
[48:20] SPEAKER: - Yes, yes, they were from Scandinavia, right?
[48:22] SPEAKER: So they were a bunch of 64K coders and stuff like that,
[48:25] SPEAKER: and I'm trying to remember what claims they were making.
[48:27] SPEAKER: I just-- - That part doesn't matter.
[48:29] SPEAKER: - They were quoting numbers and performance metrics
[48:33] SPEAKER: that sounded completely impossible.
[48:34] SPEAKER: - They were talking about next-gen,
[48:36] SPEAKER: it was the equivalent of them talking about ray tracing
[48:38] SPEAKER: in 2005, right? - Right, right.
[48:41] SPEAKER: And the fact that they never actually shipped a product.
[48:44] SPEAKER: - So they got bought by ATI right before AMD bought ATI,
[48:48] SPEAKER: and then when AMD bought ATI for five billion dollars
[48:53] SPEAKER: or whatever, which was an enormous amount of money then,
[48:56] SPEAKER: they spun BitBoy's back out to Qualcomm,
[49:00] SPEAKER: who then developed the thing that they were talking about
[49:02] SPEAKER: into the Adreno processor, which also is in a lot of,
[49:06] SPEAKER: like that's Qualcomm's GPU SOC component.
[49:09] SPEAKER: - So the BitBoy's people actually shipped a product.
[49:11] SPEAKER: - And hey, look at those letters in Adreno, Brad.
[49:15] SPEAKER: - Yeah? - Is it an anagram?
[49:18] SPEAKER: - Maybe, maybe.
[49:21] SPEAKER: - For a popular ATI graphics processor.
[49:24] SPEAKER: - Oh hey, look at that. - Yeah.
[49:26] SPEAKER: - Who would've thought?
[49:27] SPEAKER: - Yeah, so I think everybody feels good about that.
[49:30] SPEAKER: ArtX was another one of those companies
[49:31] SPEAKER: that was like in the 30 companies
[49:34] SPEAKER: that were developing 3D accelerator technologies
[49:36] SPEAKER: in like the late '90s that ended up getting bought by ATI.
[49:40] SPEAKER: That's what ended up in the Dolphin, I guess,
[49:43] SPEAKER: which became the GameCube, yeah.
[49:45] SPEAKER: - Which reminded me that GameCubes
[49:46] SPEAKER: straight up have an ATI sticker on them.
[49:48] SPEAKER: - Don't they?
[49:49] SPEAKER: - Hell yeah, yeah, right on the front, purple spot.
[49:51] SPEAKER: - If I remember just like the drink guest
[49:53] SPEAKER: had a Windows CE logo on there somewhere.
[49:55] SPEAKER: - Yep, yep, I mean, let's see,
[49:58] SPEAKER: Matrox still makes graphics video processing stuff
[50:02] SPEAKER: and like video wall installations and stuff like that.
[50:06] SPEAKER: - I was sure that Matrox would have been
[50:07] SPEAKER: one of those casualties of this era,
[50:08] SPEAKER: but yeah, they're still out there.
[50:10] SPEAKER: Yeah, like they make a lot of embedded solutions
[50:12] SPEAKER: for like if you've got some giant video wall
[50:13] SPEAKER: you need to power.
[50:14] SPEAKER: - Well, so Matrox always, they came around
[50:17] SPEAKER: in like the early 2000s to maximum PC.
[50:19] SPEAKER: They were the first ones who were like,
[50:21] SPEAKER: "Hey, we think this multi-monitor thing
[50:23] SPEAKER: "is gonna be a big deal.
[50:26] SPEAKER: "And here's a solution that will let you play
[50:29] SPEAKER: "your video game across three monitors stretched around."
[50:33] SPEAKER: And of course they were like CRTs with big fat bezels
[50:35] SPEAKER: and stuff like that, so it was kinda goofy at the time.
[50:38] SPEAKER: - It was too expensive and too bulky to be feasible back then.
[50:42] SPEAKER: - Drive it really, 'cause it's 20 pixels.
[50:44] SPEAKER: - Yeah, but they weren't wrong.
[50:45] SPEAKER: - They were not wrong.
[50:47] SPEAKER: - S3 was bought by...
[50:54] SPEAKER: Oh God, I can't remember who bought them.
[50:56] SPEAKER: I wanna say Intel, but I don't think that's right.
[51:00] SPEAKER: - I looked it up last night
[51:01] SPEAKER: and I am totally forgetting here.
[51:02] SPEAKER: Let me just...
[51:04] SPEAKER: - Intel, obviously.
[51:06] SPEAKER: - Oh, they're owned by HTC.
[51:07] SPEAKER: - HTC, that's right.
[51:08] SPEAKER: - And in fact, the S3 name I believe is still in use.
[51:13] SPEAKER: - On mobile parts, probably?
[51:17] SPEAKER: - I might be wrong about that, actually.
[51:20] SPEAKER: - Well, so Intel, after the i740 and the i752,
[51:24] SPEAKER: which was the follow-up, they did multiple other,
[51:28] SPEAKER: like they went through the whole Larrabee thing
[51:29] SPEAKER: where they were gonna revolutionize the graphics pipeline
[51:31] SPEAKER: with a bunch of low-fi x86 cores.
[51:35] SPEAKER: - Right.
[51:36] SPEAKER: - And then it just basically disappeared.
[51:40] SPEAKER: And rendition, you said, ended up at...
[51:44] SPEAKER: - I've already forgotten.
[51:45] SPEAKER: It's so hard to keep all this stuff, Micron.
[51:46] SPEAKER: - Micron, yeah, that's right.
[51:47] SPEAKER: - Yes.
[51:48] SPEAKER: - So yeah, it was a weird...
[51:51] SPEAKER: And during this time, there were so many...
[51:53] SPEAKER: Everybody looked at what the hardware was capable of
[51:56] SPEAKER: and where the market was going,
[51:57] SPEAKER: and they decided different approaches
[52:00] SPEAKER: to how to feed those markets.
[52:03] SPEAKER: So rendition and Intel were looking at the price of memory
[52:07] SPEAKER: and were like, "Well, nobody's gonna put lots and lots
[52:09] SPEAKER: of memory on these cards ever.
[52:11] SPEAKER: So we should just roll out these high-speed interfaces
[52:17] SPEAKER: to system memory and let everybody do everything
[52:19] SPEAKER: out of system memory."
[52:20] SPEAKER: And NVIDIA and ATI looked at what the CPUs were capable of
[52:25] SPEAKER: in terms of triangle setup.
[52:26] SPEAKER: More like, "We're gonna hit a wall on this really fast,
[52:28] SPEAKER: so we need to get some computation on these processors
[52:32] SPEAKER: so it's not just doing mipmapping and trilinear filtering."
[52:35] SPEAKER: - Thus the dawn of hardware transform and lighting.
[52:38] SPEAKER: - Then yeah, that's when the GPU,
[52:40] SPEAKER: when NVIDIA launched the GeForce 256
[52:42] SPEAKER: and ATI launched the Radeon six months later,
[52:45] SPEAKER: it was a transformative moment.
[52:49] SPEAKER: - Totally, I didn't know that, I'm sorry.
[52:51] SPEAKER: - Oh no, no, I mean, in that like,
[52:53] SPEAKER: the computationally expensive part of playing games
[52:56] SPEAKER: on these 3D accelerators suddenly moved off of the CPU
[53:00] SPEAKER: and onto the GPU.
[53:01] SPEAKER: - Right, like that conceptually is the beginning
[53:03] SPEAKER: of the modern era of the GPU, right?
[53:05] SPEAKER: - I think so, yeah.
[53:07] SPEAKER: - I didn't realize the Radeon was that close to the GeForce
[53:09] SPEAKER: in getting to market.
[53:10] SPEAKER: - So I started at Maximum PC.
[53:12] SPEAKER: This is easy for me to remember.
[53:13] SPEAKER: I started at Maximum PC in June of 2000
[53:16] SPEAKER: and my first meeting with a vendor
[53:18] SPEAKER: while as a Maximum PC employee was a Radeon meeting
[53:22] SPEAKER: like the second day I was there.
[53:24] SPEAKER: And so they probably didn't roll it out
[53:26] SPEAKER: for another three months at that point
[53:27] SPEAKER: 'cause everybody brought us stuff super early
[53:29] SPEAKER: so we could have timely coverage.
[53:32] SPEAKER: But that was a big deal.
[53:35] SPEAKER: - In my mind, I mean, this is probably
[53:36] SPEAKER: because I always bought NVIDIA products,
[53:38] SPEAKER: so that's just what I remember.
[53:39] SPEAKER: But like in my mind, I don't remember the Radeon name
[53:41] SPEAKER: being out there until Half-Life 2,
[53:42] SPEAKER: but that's obviously a marketing.
[53:43] SPEAKER: That's a legacy.
[53:44] SPEAKER: - That was way later, yeah.
[53:45] SPEAKER: - They're marketing, right?
[53:46] SPEAKER: They obviously were around way before that, so.
[53:48] SPEAKER: - So the thing about, the thing about,
[53:51] SPEAKER: so one of the things that NVIDIA did
[53:53] SPEAKER: that turned out to be really smart
[53:55] SPEAKER: because of the thing that you just said
[53:56] SPEAKER: is that they rolled out, DDR memory was late coming.
[54:00] SPEAKER: So they just rolled out an SDR version of the GeForce
[54:03] SPEAKER: like six months before the DDR cards.
[54:05] SPEAKER: - I was still on a TNT1, so I bought an SDR GeForce
[54:09] SPEAKER: because I needed, I was desperate to have it.
[54:13] SPEAKER: 'Cause that was the era of Quake 3
[54:15] SPEAKER: and I really needed Quake 3 to run better.
[54:18] SPEAKER: - It turns out the DDR cards,
[54:19] SPEAKER: since everything was fill rate limited,
[54:20] SPEAKER: were almost twice as fast as the SDR cards.
[54:22] SPEAKER: - Yeah, that was perhaps a hasty decision.
[54:25] SPEAKER: I was always off cycle for whatever reason.
[54:26] SPEAKER: I got a Voodoo 1, but then I tried to stretch my hardware
[54:30] SPEAKER: as long as I could, just for money reasons.
[54:31] SPEAKER: So I skipped the Voodoo 2 and I got a TNT1,
[54:38] SPEAKER: and then the TNT2 came along, it was dramatically better.
[54:41] SPEAKER: - Yeah.
[54:43] SPEAKER: - Then I got a GeForce 256 SDR because I was due for a card
[54:47] SPEAKER: and then the DDR version came out, it was massively better.
[54:49] SPEAKER: And then the GeForce 2 was even better than that.
[54:53] SPEAKER: I think I stayed on that, I'm trying to remember.
[54:56] SPEAKER: I want to say I stayed on that GeForce 256
[55:01] SPEAKER: until the GeForce 4.
[55:02] SPEAKER: - Probably three or four would have been
[55:03] SPEAKER: the next smart upgrade, yeah.
[55:05] SPEAKER: - I skipped the GeForce 3
[55:07] SPEAKER: 'cause that was when I started a GameSpot.
[55:08] SPEAKER: So I was playing a ton of games on consoles,
[55:10] SPEAKER: 'cause that was my coverage beat.
[55:13] SPEAKER: So I didn't get a, I think I got like the low end GeForce 4
[55:16] SPEAKER: was my next card after that.
[55:17] SPEAKER: - Well, I was gonna say the weird,
[55:19] SPEAKER: so that's when the GeForce 4,
[55:23] SPEAKER: I think is when they started differentiating,
[55:26] SPEAKER: like they started having multiple SKUs
[55:29] SPEAKER: that weren't just clocked down versions of the same chip.
[55:32] SPEAKER: They were like versions of the chip that didn't bin
[55:34] SPEAKER: or that parts were burned out on or something.
[55:37] SPEAKER: And like they had the GeForce MX,
[55:39] SPEAKER: I think was the low end version of those cards.
[55:41] SPEAKER: And then the TI's were the high ends
[55:42] SPEAKER: and then the regular ones were just the G forces.
[55:45] SPEAKER: - I had a, I believe I had a TI 4200.
[55:48] SPEAKER: - That was a fine card, all right,
[55:50] SPEAKER: they did numbers on those, I forgot.
[55:51] SPEAKER: - Yes, so which was the low end of there was,
[55:54] SPEAKER: it was the TI 4200, 4400 and 4600, so.
[55:58] SPEAKER: - Well, so that was a weird time
[55:59] SPEAKER: because the pipelines were still fixed functions.
[56:01] SPEAKER: So it wasn't like a general purpose compute pipeline.
[56:03] SPEAKER: Like if they wanted to add new features,
[56:05] SPEAKER: then they had to put Silicon on for it
[56:07] SPEAKER: or you had to do it on the CPU.
[56:09] SPEAKER: And it wasn't until the 5 series with the leaf blower,
[56:13] SPEAKER: the 5800 that that changed, which was a few years later.
[56:18] SPEAKER: So, and that's when the general purpose compute pipeline
[56:22] SPEAKER: happened on the GPU really, that's when that started.
[56:24] SPEAKER: Like they weren't feature complete
[56:25] SPEAKER: for a few more years after that,
[56:27] SPEAKER: 'cause they didn't have like, they didn't have full
[56:29] SPEAKER: if and XOR, all the different gates that you need.
[56:34] SPEAKER: But it was pretty cool.
[56:36] SPEAKER: - So that pretty much takes us into the modern era,
[56:38] SPEAKER: both in terms of like the internal design of what a GPU is
[56:41] SPEAKER: and also in the market dominance
[56:43] SPEAKER: of the companies that made it through.
[56:44] SPEAKER: But the last thing I wanted to touch on real quick
[56:47] SPEAKER: or just expand on was if you have a good sense
[56:51] SPEAKER: of why 3D effects cratered so hard and so fast.
[56:54] SPEAKER: - Yeah, they never made a compelling 2D, 3D part.
[56:58] SPEAKER: - Is that all it was?
[56:59] SPEAKER: - I mean, it was first mover disadvantage, right?
[57:04] SPEAKER: So they established the market and they set it up
[57:07] SPEAKER: and then they didn't ever have a,
[57:10] SPEAKER: like their products were always niche products
[57:13] SPEAKER: in a market that needed to be mainstream
[57:14] SPEAKER: and Nvidia and ATI had mainstream parts immediately.
[57:18] SPEAKER: - They couldn't go in commodity PCs
[57:20] SPEAKER: because they were an extra part, not a replacement part.
[57:24] SPEAKER: Like they couldn't replace the desktop card,
[57:25] SPEAKER: they had to be there in addition to a desktop card.
[57:27] SPEAKER: - Yeah, so instead of adding like four bucks
[57:29] SPEAKER: to the cost of the thing for Compaq or Packard Bell
[57:32] SPEAKER: or e-machines or whoever, it was another 150 bucks
[57:36] SPEAKER: to the OEM and they weren't,
[57:38] SPEAKER: like unless they could sell it into gamers, it wasn't.
[57:42] SPEAKER: Like if you look at it from a,
[57:44] SPEAKER: if you're the purchaser for Compaq
[57:45] SPEAKER: who's selling 2 million PCs a year or something
[57:48] SPEAKER: and you're looking at ATI with the Rage Pro
[57:50] SPEAKER: and Nvidia with the TNT2 and 3D effects
[57:54] SPEAKER: with a TNT2 plus a Voodoo 2 or Voodoo Banshee,
[57:59] SPEAKER: whatever, Voodoo 3.
[58:01] SPEAKER: Their Voodoo 3 performance was never very good, right?
[58:04] SPEAKER: Like those cards couldn't compete
[58:06] SPEAKER: with the TNT2 and the Rage Pro.
[58:09] SPEAKER: - Voodoo 3 was an all-in-one, to be clear.
[58:12] SPEAKER: - Yeah, everything after Voodoo 2 was an all-in-one.
[58:14] SPEAKER: - Okay, the Banshee was just straight up bad, right?
[58:16] SPEAKER: - Banshee was straight up bad.
[58:18] SPEAKER: The Voodoo Rush was really bad.
[58:19] SPEAKER: The Banshee was an okay 2D card
[58:22] SPEAKER: that had kind of passable 3D on it.
[58:25] SPEAKER: The Voodoo 3 was fine.
[58:28] SPEAKER: Like it was not a bad card necessarily.
[58:30] SPEAKER: It just wasn't, like it wasn't as competitive with Nvidia.
[58:33] SPEAKER: And I think they, I feel like they also leaned on Glide
[58:36] SPEAKER: longer than they should have
[58:37] SPEAKER: where Nvidia was building robust direct 3D
[58:40] SPEAKER: and OpenGL drivers that were native.
[58:43] SPEAKER: Voodoo was using the Glide wrapper for OpenGL
[58:46] SPEAKER: for a long time.
[58:46] SPEAKER: - I think now that you mentioned it,
[58:48] SPEAKER: I think that was another revelation of getting that TNT
[58:50] SPEAKER: was that it just played a lot more games.
[58:52] SPEAKER: - Like I said, the Revo 128 was a real wake-up call,
[58:55] SPEAKER: I feel like, at Nvidia, where they were like,
[58:58] SPEAKER: "Oh, right, it doesn't matter how good our hardware is
[59:00] SPEAKER: "if the drivers suck."
[59:02] SPEAKER: And like they invested--
[59:03] SPEAKER: - API support is lacking.
[59:05] SPEAKER: - Yeah, yeah, they've spent a lot of time.
[59:08] SPEAKER: I mean, if you look at the size of their dev rel org
[59:11] SPEAKER: in Nvidia versus other comparable companies then,
[59:14] SPEAKER: and even probably now, it's pretty astounding
[59:18] SPEAKER: how aggressively they spend money on that.
[59:21] SPEAKER: And it makes a lot of sense.
[59:22] SPEAKER: - That reputation persists to this day,
[59:24] SPEAKER: like you see it on message boards all the time.
[59:25] SPEAKER: And in fact, like that's, in the back of my mind,
[59:27] SPEAKER: like Nvidia's the one with the good drivers.
[59:29] SPEAKER: Like that's a big part of the reason
[59:30] SPEAKER: that I always bought their cards.
[59:31] SPEAKER: - Yeah.
[59:37] SPEAKER: I thought we were gonna talk about direct 3D and OpenGL
[59:39] SPEAKER: in this, we kind of skipped past this,
[59:41] SPEAKER: but at the same time, the undercurrent behind all of this
[59:43] SPEAKER: was like, what's gonna be the future of 3D rendering?
[59:47] SPEAKER: Is it gonna be this weird open consortium
[59:49] SPEAKER: or is it gonna be direct 3D?
[59:50] SPEAKER: And it turns out that the open consortium
[59:54] SPEAKER: never was able to move fast enough
[59:56] SPEAKER: to support the new hardware.
[59:57] SPEAKER: So like people, like vendors were always writing
[1:00:00] SPEAKER: OpenGL extensions to support the new,
[1:00:02] SPEAKER: like the hardware transform and lighting
[1:00:04] SPEAKER: and the bump mapping and the normal maps and all that stuff.
[1:00:07] SPEAKER: And just never landed on the OpenGL side.
[1:00:13] SPEAKER: It made supporting OpenGL really difficult.
[1:00:15] SPEAKER: - Right, and like that dynamic persists to this day, right?
[1:00:18] SPEAKER: Like DX 12 was robust and mature and on the market for ages
[1:00:22] SPEAKER: before Vulkan really became a thing, right?
[1:00:24] SPEAKER: - It's...
[1:00:26] SPEAKER: - I don't know if those are
[1:00:26] SPEAKER: as directly comparable in this case.
[1:00:28] SPEAKER: - Yeah, Vulkan is complicated for whole other reasons, but...
[1:00:33] SPEAKER: - I came upon a Twitter thread of graphics programmers
[1:00:36] SPEAKER: the other day kind of grousing about Vulkan
[1:00:38] SPEAKER: in a way that I hadn't seen before.
[1:00:40] SPEAKER: Maybe think maybe my understanding of Vulkan
[1:00:42] SPEAKER: is not as complete as it could be.
[1:00:44] SPEAKER: - Was it the one about the,
[1:00:45] SPEAKER: here's the number of lines of code it takes
[1:00:47] SPEAKER: to draw a triangle in Vulkan?
[1:00:48] SPEAKER: - Something like that?
[1:00:49] SPEAKER: - Yeah. - Yeah.
[1:00:51] SPEAKER: - The other weird thing about Direct3D,
[1:00:53] SPEAKER: like they iterated Direct3D so fast at that time period.
[1:00:57] SPEAKER: Like they never released Direct3D.
[1:00:59] SPEAKER: There was no Direct3D 1.
[1:01:01] SPEAKER: Direct3D 2.0 launched in June of 1996.
[1:01:04] SPEAKER: Direct3D 3.0 launched in September of that same year.
[1:01:08] SPEAKER: - Wow.
[1:01:09] SPEAKER: - So like four months, five months, right?
[1:01:12] SPEAKER: And like, I think the only Direct3D 2 game
[1:01:15] SPEAKER: I ever remember playing was Tom Clancy's "SSN",
[1:01:17] SPEAKER: that submarine, like the underwater piloting game
[1:01:22] SPEAKER: where you flew the submarine like a plane.
[1:01:25] SPEAKER: And they, like, they didn't really,
[1:01:30] SPEAKER: like Microsoft was iterating that so quickly
[1:01:32] SPEAKER: that they were releasing Direct3D 3.0 A, 3.0 B, 3.0 C,
[1:01:37] SPEAKER: month to month to month.
[1:01:39] SPEAKER: So you're always downloading these new things.
[1:01:41] SPEAKER: But as a result, by the time they got to five or six,
[1:01:45] SPEAKER: I guess by the time they got to five,
[1:01:47] SPEAKER: 'cause they skipped four, it was robust and like worked.
[1:01:51] SPEAKER: - I feel like I remember DirectX 5
[1:01:54] SPEAKER: lasting for a very long time.
[1:01:55] SPEAKER: - Five. - Irritatively.
[1:01:56] SPEAKER: - Five was for a while.
[1:01:58] SPEAKER: Eight was when they added the programmable pipeline stuff.
[1:02:01] SPEAKER: - Yeah, those are like five, eight, 11, and 12
[1:02:05] SPEAKER: are the big milestones in my memory.
[1:02:07] SPEAKER: - Yeah, so the other big hardware thing,
[1:02:10] SPEAKER: the early hardware feature that made a huge impact
[1:02:12] SPEAKER: on like visual quality that we haven't talked about yet
[1:02:16] SPEAKER: was the G, the Matrox G400, which was the Post Mystique.
[1:02:20] SPEAKER: It was like their Rage Pro competitor, I guess,
[1:02:23] SPEAKER: or Rage 128 maybe competitor,
[1:02:26] SPEAKER: around the same time as the TNT.
[1:02:28] SPEAKER: And it had bump map, it had hardware bump mapping support.
[1:02:30] SPEAKER: - Oh, huh.
[1:02:31] SPEAKER: - Which was really novel and literally no one used it, so.
[1:02:36] SPEAKER: - 'Cause it was the only card that had it.
[1:02:37] SPEAKER: - It was the only card that had it, yeah.
[1:02:38] SPEAKER: - But, I mean, that kind of thing came back around
[1:02:40] SPEAKER: with the GeForce 3, right?
[1:02:43] SPEAKER: - Yeah, GeForce 3 was the first one
[1:02:45] SPEAKER: that had bump mapping on the Nvidia side, I think.
[1:02:47] SPEAKER: The G400 might've been later when I think,
[1:02:49] SPEAKER: I might've reviewed that when I was at Maximum PC,
[1:02:51] SPEAKER: when I think about it.
[1:02:53] SPEAKER: I'd have to-- - It was a fun time.
[1:02:54] SPEAKER: - It's been a while.
[1:02:57] SPEAKER: - It was a big mess.
[1:03:00] SPEAKER: It was easy to place the wrong bet back then
[1:03:02] SPEAKER: 'cause there were so many products on the market
[1:03:03] SPEAKER: and everything was so immature.
[1:03:05] SPEAKER: - Well, on the other hand,
[1:03:06] SPEAKER: the cards were really cheap compared to today.
[1:03:09] SPEAKER: Like the cards were 200 bucks at the high end.
[1:03:11] SPEAKER: - Yes, that's fair.
[1:03:12] SPEAKER: Things have gotten a little pricier
[1:03:14] SPEAKER: now that you mentioned it.
[1:03:15] SPEAKER: - I mean, 200 bucks was worth more then,
[1:03:17] SPEAKER: but when I went, I remember going to Electronics Boutique
[1:03:21] SPEAKER: to buy a Voodoo 2, I had pre-ordered,
[1:03:24] SPEAKER: I was one of two people in Knoxville, Tennessee
[1:03:26] SPEAKER: who pre-ordered a Voodoo 2 from our Electronics Boutique
[1:03:29] SPEAKER: and I got a Creative Labs 3DFX Voodoo 2 card
[1:03:33] SPEAKER: that the serial number was like 0, 0, 0, 0, 0, 0, 0,
[1:03:36] SPEAKER: 32.
[1:03:38] SPEAKER: - What?
[1:03:38] SPEAKER: - Yeah.
[1:03:39] SPEAKER: - Do you still have it?
[1:03:40] SPEAKER: - No, I got rid of it years ago.
[1:03:41] SPEAKER: I know.
[1:03:42] SPEAKER: - It might be worth something.
[1:03:43] SPEAKER: - I probably have a picture.
[1:03:44] SPEAKER: It wasn't, I looked.
[1:03:45] SPEAKER: - Oh, that was the last thing I wanted to mention
[1:03:46] SPEAKER: before we probably wrap this thing up,
[1:03:48] SPEAKER: but do you remember the weird,
[1:03:51] SPEAKER: I hesitate to use the word cult,
[1:03:52] SPEAKER: but there was like an insanely diehard fan base
[1:03:55] SPEAKER: around three effects,
[1:03:57] SPEAKER: like way longer than there should have been.
[1:03:58] SPEAKER: - Oh yeah.
[1:03:59] SPEAKER: - There were people clinging to their Voodoos
[1:04:01] SPEAKER: way after it was clear that the industry had moved on.
[1:04:03] SPEAKER: - Look, I had a Voodoo 2 card in my machine
[1:04:07] SPEAKER: well into the Quake 3 era, right?
[1:04:09] SPEAKER: - Okay, yeah.
[1:04:10] SPEAKER: - Yeah, it was...
[1:04:12] SPEAKER: - Like if you Google, I should pull this up,
[1:04:14] SPEAKER: like if you Google images of the Voodoo 5,
[1:04:17] SPEAKER: what an obscene thing that is.
[1:04:19] SPEAKER: - Oh.
[1:04:20] SPEAKER: - The Voodoo 5 was the one that was gonna plug
[1:04:20] SPEAKER: straight into the wall, right?
[1:04:21] SPEAKER: - Voodoo 5 6000, like I said,
[1:04:23] SPEAKER: we got an engineering sample and it had a power brick
[1:04:26] SPEAKER: that was the size of like a gaming laptop power brick
[1:04:29] SPEAKER: that you plugged into a,
[1:04:30] SPEAKER: like a dipole port on the back of the card.
[1:04:33] SPEAKER: - Right, and then into the wall, right?
[1:04:34] SPEAKER: - Into the wall, yeah.
[1:04:36] SPEAKER: - Like directly into the wall,
[1:04:37] SPEAKER: did not run off the PC's power supply.
[1:04:38] SPEAKER: - No, and it was an incredibly,
[1:04:41] SPEAKER: it was like a workstation length card.
[1:04:43] SPEAKER: It was really, really long.
[1:04:45] SPEAKER: - Like if you Google pictures of this thing,
[1:04:46] SPEAKER: it looks Photoshopped.
[1:04:47] SPEAKER: It looks like somebody has copy pasted a video card
[1:04:49] SPEAKER: on top of itself.
[1:04:50] SPEAKER: - It had four of those, like,
[1:04:53] SPEAKER: I don't even know what those fans were called,
[1:04:54] SPEAKER: but it was like a really specific size heat sink fan combo
[1:04:58] SPEAKER: and it had four of them on it, as I recall.
[1:05:00] SPEAKER: - It's gigantic.
[1:05:01] SPEAKER: It's got a handle on it.
[1:05:02] SPEAKER: The other end of the card has a handle on it.
[1:05:04] SPEAKER: - So that was supposed to,
[1:05:05] SPEAKER: so in the olden days, there were slots,
[1:05:08] SPEAKER: like there was a slot that the screw went in
[1:05:10] SPEAKER: and then the other end of the case for a full length,
[1:05:13] SPEAKER: for a full length card,
[1:05:14] SPEAKER: there was a slot that the other end would go in
[1:05:18] SPEAKER: to support both sides of the card.
[1:05:20] SPEAKER: And that's what that handle was.
[1:05:22] SPEAKER: - That's amazing.
[1:05:23] SPEAKER: - It was to make it reach.
[1:05:24] SPEAKER: - And then the reason I bring it up is I just,
[1:05:26] SPEAKER: I have this memory and this may have been like 100 people,
[1:05:28] SPEAKER: I don't know, and not that big a deal,
[1:05:32] SPEAKER: but there was this weird boutique community of people
[1:05:34] SPEAKER: trying to get their hands on like the Voodoo 5 samples
[1:05:37] SPEAKER: that had gotten out into the wild.
[1:05:38] SPEAKER: - Oh, they were highly desirable, yeah.
[1:05:40] SPEAKER: - And there was like a user effort
[1:05:42] SPEAKER: to maintain Glide and bring it forward
[1:05:44] SPEAKER: so they could keep playing games on 3D effects,
[1:05:45] SPEAKER: even after that was no longer a going concern.
[1:05:47] SPEAKER: They really should have just bought an Nvidia or an ATI card,
[1:05:50] SPEAKER: but they were just like desperately trying
[1:05:52] SPEAKER: to keep 3D effects on life support.
[1:05:54] SPEAKER: - I wonder if somebody ever made like a DirectX or OpenGL
[1:05:57] SPEAKER: to Glide wrapper to go the other way
[1:06:00] SPEAKER: so you can play Glide games on OpenGL cards
[1:06:03] SPEAKER: or direct 3D cards.
[1:06:04] SPEAKER: - If there's anything I've learned about the internet
[1:06:06] SPEAKER: is that if you have to ask, I wonder if ever someone did X,
[1:06:10] SPEAKER: the answer is yes.
[1:06:11] SPEAKER: - It was a fascinating time because stuff
[1:06:16] SPEAKER: was happening constantly.
[1:06:17] SPEAKER: Like you would look at plan files for, like I said,
[1:06:20] SPEAKER: like the people who are doing graphics programming
[1:06:22] SPEAKER: at 3D Realms and ID and Epic and places like that, Valve.
[1:06:29] SPEAKER: And you would see all sorts of amazing stories come out
[1:06:34] SPEAKER: as a result of that.
[1:06:35] SPEAKER: - Yeah, things were just iterating way faster back then
[1:06:38] SPEAKER: than they do now.
[1:06:38] SPEAKER: - We have a couple of friends of the pod
[1:06:40] SPEAKER: who are like X 3D effects folk
[1:06:43] SPEAKER: that are probably far enough out of NDAs
[1:06:45] SPEAKER: now that we might be able to get them on to talk.
[1:06:47] SPEAKER: So I'll have to ask around.
[1:06:48] SPEAKER: - That would be fun.
[1:06:50] SPEAKER: - But that time, like those guys,
[1:06:55] SPEAKER: they were in Texas and they built this thing.
[1:06:57] SPEAKER: And I don't think at the beginning,
[1:06:59] SPEAKER: they didn't realize what they had.
[1:07:01] SPEAKER: And then I think they had more,
[1:07:02] SPEAKER: they thought they had more than they did real quickly.
[1:07:05] SPEAKER: - Everything's bigger in Texas, right?
[1:07:07] SPEAKER: - Something like that.
[1:07:09] SPEAKER: But yeah, it was a fun time to be an enthusiast.
[1:07:13] SPEAKER: - For sure.
[1:07:14] SPEAKER: - I guess that's it for today.
[1:07:16] SPEAKER: - Yeah, we'll walk down memory lane.
[1:07:19] SPEAKER: - Yeah, I guess we've reached the point in the show
[1:07:22] SPEAKER: where we talk about the Patreon.
[1:07:27] SPEAKER: If you would like to support Brad and Will Made a Tech Pod,
[1:07:33] SPEAKER: you can by going to patreon.com/techpod.
[1:07:35] SPEAKER: For as little as two bucks a month,
[1:07:37] SPEAKER: you will get access to the fabulous Tech Pod Discord
[1:07:41] SPEAKER: where you find out things like how long time is
[1:07:47] SPEAKER: for a CPU versus human scale.
[1:07:49] SPEAKER: And let's see what else we've talked about.
[1:07:52] SPEAKER: We got a shout out.
[1:07:56] SPEAKER: I idly asked a question in chat the other day
[1:07:58] SPEAKER: and then one of our fabulous users made an app,
[1:08:02] SPEAKER: web app that does that thing.
[1:08:04] SPEAKER: - Literally coded a solution for us
[1:08:08] SPEAKER: to fulfill a very specific need that we had.
[1:08:10] SPEAKER: I cannot express my gratitude enough.
[1:08:13] SPEAKER: You know who you are.
[1:08:14] SPEAKER: - I think we can out them, right?
[1:08:16] SPEAKER: Chris Tarn?
[1:08:17] SPEAKER: - Yeah.
[1:08:18] SPEAKER: - Made beep30.com.
[1:08:20] SPEAKER: If you do a podcast and you need to sync it,
[1:08:22] SPEAKER: we've tried it this week.
[1:08:23] SPEAKER: I'll let you know how it goes next week, I guess.
[1:08:24] SPEAKER: I don't know if you want to bring that much load to that.
[1:08:26] SPEAKER: I don't know how much capacity he's got to serve that page.
[1:08:29] SPEAKER: - Look, I'm comfortable.
[1:08:32] SPEAKER: - You want to out this thing?
[1:08:33] SPEAKER: - This is a burgeoning business.
[1:08:34] SPEAKER: - Yeah, I guess so.
[1:08:36] SPEAKER: - I want to support all of our fabulous patrons.
[1:08:42] SPEAKER: And yeah, there's just interesting conversations
[1:08:45] SPEAKER: basically every day in there.
[1:08:46] SPEAKER: It's a fabulous place to hang out.
[1:08:49] SPEAKER: I have enjoyed having human contact
[1:08:53] SPEAKER: during these dark times.
[1:08:55] SPEAKER: - Helps for sure.
[1:08:57] SPEAKER: - Yeah, it's a lovely spot.
[1:09:00] SPEAKER: And as always, we thank all of our patrons.
[1:09:02] SPEAKER: For more, if you spend five bucks a month,
[1:09:04] SPEAKER: you get access to the monthly patron exclusive episode
[1:09:08] SPEAKER: where we usually talk about projects.
[1:09:11] SPEAKER: I moved everything over to home assistant last week
[1:09:13] SPEAKER: 'cause smart things goes away today.
[1:09:15] SPEAKER: - I am following, let's say four to six weeks
[1:09:20] SPEAKER: behind in your footsteps.
[1:09:22] SPEAKER: How's it going? - I also just,
[1:09:24] SPEAKER: let's say I spent a lot of last weekend
[1:09:25] SPEAKER: messing with home assistant on my NAS.
[1:09:29] SPEAKER: - It's really neat.
[1:09:30] SPEAKER: - And then, well, no, not on the NAS, it's not.
[1:09:32] SPEAKER: - Oh no, the NAS is a pain in the ass.
[1:09:33] SPEAKER: I just bought a Raspberry Pi 'cause it was way easier.
[1:09:35] SPEAKER: - Not in FreeBSD, so yes, I too just bought
[1:09:37] SPEAKER: a Raspberry Pi 4 to do things like that on
[1:09:41] SPEAKER: because it's not going to happen in BSD.
[1:09:45] SPEAKER: But we got the Pi 4 here.
[1:09:47] SPEAKER: What do you, well, we should save this.
[1:09:49] SPEAKER: This episode's long already.
[1:09:50] SPEAKER: - Yeah, we'll talk about it.
[1:09:51] SPEAKER: I'm debating whether to put Raspbian or Ubuntu on that thing.
[1:09:54] SPEAKER: - I did Raspbian.
[1:09:55] SPEAKER: Raspbian's easier to maintain.
[1:09:57] SPEAKER: - Yeah, that's fair.
[1:10:00] SPEAKER: - As always, thank you to all of our patrons,
[1:10:02] SPEAKER: but especially our executive producer level patrons,
[1:10:04] SPEAKER: Jacob Chappell, Andrew Cotton, and David Allen.
[1:10:07] SPEAKER: Without all of your all support,
[1:10:08] SPEAKER: we wouldn't still be making the podcast.
[1:10:10] SPEAKER: So thank you all so much.
[1:10:12] SPEAKER: We would just be having these conversations in Discord
[1:10:14] SPEAKER: and it would be just for us and we'd be completely wasted.
[1:10:17] SPEAKER: So we appreciate you all a bunch.
[1:10:21] SPEAKER: And thanks to Julian for doing transcripts
[1:10:25] SPEAKER: every week for the show.
[1:10:26] SPEAKER: - Yeah, that sounds awesome.
[1:10:27] SPEAKER: - If you have friends who are deaf or hard of hearing
[1:10:29] SPEAKER: and you think that they would be interested in the show,
[1:10:31] SPEAKER: you can share it with them.
[1:10:32] SPEAKER: The transcripts are available at techpod.content.counttown.
[1:10:36] SPEAKER: There's a big transcripts button there.
[1:10:38] SPEAKER: And we have them for like the last eight,
[1:10:40] SPEAKER: five or six episodes, seven episodes now, I think.
[1:10:42] SPEAKER: So that is awesome.
[1:10:44] SPEAKER: And if you like them, please let us know
[1:10:45] SPEAKER: so we keep doing them 'cause like if nobody uses them,
[1:10:48] SPEAKER: we're probably gonna not, you know.
[1:10:51] SPEAKER: But if anybody's finding them useful, we would like to know.
[1:10:54] SPEAKER: - Yeah.
[1:10:57] SPEAKER: - I guess that's it for us.
[1:10:58] SPEAKER: - Yeah.
[1:10:59] SPEAKER: We'll fire up some GLQuake.
[1:11:01] SPEAKER: - I kinda wanna, yeah, can we play some GLQuake?
[1:11:03] SPEAKER: - Is the master server still up?
[1:11:05] SPEAKER: I don't know.
[1:11:06] SPEAKER: - I think we can just, look, I know your IP,
[1:11:08] SPEAKER: you know my IP, we can put our IPs together and--
[1:11:10] SPEAKER: - That's true.
[1:11:11] SPEAKER: - The question is who gets the ping advantage?
[1:11:13] SPEAKER: I don't know, I'm happy to host, that's all I'm saying.
[1:11:16] SPEAKER: - We'll have to shoot for it.
[1:11:17] SPEAKER: - Okay, okay.
[1:11:19] SPEAKER: See you all next week.
[1:11:19] SPEAKER: Thanks for listening everybody, bye.
[1:11:20] SPEAKER: Have a good one.
[1:11:21] SPEAKER: (upbeat music)
