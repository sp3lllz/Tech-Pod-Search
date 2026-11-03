---
episode: 287
title: 277: Very Ultra
date: 2025-03-09
guests: none
duration: 1:19:11
---

[00:00] SPEAKER: - So I've been testing a different CPU
[00:03] SPEAKER: for an upcoming PC world thing.
[00:05] SPEAKER: And when I swapped out the CPU in my machine
[00:09] SPEAKER: with a ostensibly faster machine,
[00:11] SPEAKER: and then I fired stuff up and started playing games
[00:14] SPEAKER: and seeing how it worked, everything was slower.
[00:17] SPEAKER: - That seems the reverse of what you would want.
[00:20] SPEAKER: - Well, it turns out what I had to do
[00:23] SPEAKER: was clean the chipset drivers
[00:26] SPEAKER: and reinstall the chipset drivers in Windows.
[00:28] SPEAKER: - Oh.
[00:29] SPEAKER: - And then everything was groovy.
[00:31] SPEAKER: - Is that that AMD thing of like,
[00:33] SPEAKER: hey, you shouldn't just swap CPUs.
[00:34] SPEAKER: You have to kind of reinstall Windows.
[00:36] SPEAKER: I remember that from when I had the 7950 X3D.
[00:39] SPEAKER: - Well, so the reinstall Windows was specifically
[00:41] SPEAKER: for dual CCD, going from one CCD to dual CCD chips.
[00:46] SPEAKER: I'm going from a one CCD to a one CCD,
[00:48] SPEAKER: and I don't understand why,
[00:50] SPEAKER: I don't understand why this would work this way.
[00:53] SPEAKER: And it's-
[00:54] SPEAKER: - I don't understand why any of this would be necessary.
[00:56] SPEAKER: Like you would think the drivers would,
[00:58] SPEAKER: like what is being keyed in the drivers
[01:00] SPEAKER: to specific hardware at time of install
[01:02] SPEAKER: that can't be changed later.
[01:04] SPEAKER: That's a strange design.
[01:06] SPEAKER: - So I'm gonna ask about it.
[01:07] SPEAKER: I want to do some more investigation.
[01:08] SPEAKER: I think it's the Windows thread scheduler changes
[01:10] SPEAKER: on a per CPU basis.
[01:12] SPEAKER: So if like you're changing from Intel to AMD or vice versa,
[01:14] SPEAKER: you obviously are gonna have a different one.
[01:17] SPEAKER: - A, I would believe that,
[01:18] SPEAKER: but B, why is that still, still why is that necessary?
[01:20] SPEAKER: Like you would hope that even the scheduling infrastructure
[01:22] SPEAKER: was robust enough to understand,
[01:24] SPEAKER: you know what doesn't have this problem?
[01:26] SPEAKER: - Macs?
[01:27] SPEAKER: - Linux.
[01:28] SPEAKER: - Wow, what an amazing coincidence.
[01:30] SPEAKER: - You can just boot a Linux install on anything
[01:32] SPEAKER: and it'll just kind of work.
[01:33] SPEAKER: I mean, you know, unless you're missing drivers
[01:35] SPEAKER: like that need a kernel module or something anyway, go on.
[01:37] SPEAKER: - I'll be honest, I, if I had,
[01:40] SPEAKER: if I could play Fortnite on Linux,
[01:41] SPEAKER: I would probably be running a Linux desktop today
[01:44] SPEAKER: right now, even as we speak.
[01:45] SPEAKER: - That doesn't seem like it's in the cards,
[01:46] SPEAKER: unless Epic has, unless Tim Epic has a dramatic change
[01:51] SPEAKER: of heart about Linux at some point.
[01:52] SPEAKER: - Well, I don't think Tim Epic hates that Linux.
[01:54] SPEAKER: I think Tim Epic hates Valve.
[01:56] SPEAKER: - Oh, sure.
[01:58] SPEAKER: - And I think that's why Fortnite's,
[01:59] SPEAKER: 'cause the anti-cheat that's in Fortnite
[02:03] SPEAKER: is in other games that run on Linux
[02:05] SPEAKER: and are Steam Deck certified.
[02:06] SPEAKER: It's a choice.
[02:07] SPEAKER: - Oh, I didn't know that.
[02:08] SPEAKER: - He does not want to help the Steam Deck out
[02:10] SPEAKER: by putting the Fortnite's on it.
[02:12] SPEAKER: - Even though they make tremendous amounts of money
[02:14] SPEAKER: from Fortnite, although granted the Steam Deck install day
[02:18] SPEAKER: is probably not a big enough number to make a huge dent
[02:21] SPEAKER: in, well, the Fortnite revenue.
[02:23] SPEAKER: - And realistically, I mean, I guess if I had like,
[02:27] SPEAKER: if I had a bunch of kids and they all wanted to play
[02:28] SPEAKER: PC games, like buying a bunch of $400 Steam Decks
[02:32] SPEAKER: probably is a good entry point for that,
[02:34] SPEAKER: rather than building a bunch of PCs.
[02:35] SPEAKER: - Oh yeah, oh yeah.
[02:37] SPEAKER: Although honestly, the way that,
[02:39] SPEAKER: the way I see people talking about moving to desktop Linux,
[02:41] SPEAKER: especially once Valve puts out their actual desktop Steam OS,
[02:44] SPEAKER: which I think sounds like it's getting close.
[02:46] SPEAKER: - This year sometime, yeah.
[02:48] SPEAKER: - Like I actually wonder if that number gets big enough
[02:50] SPEAKER: that Epic kind of has to fold.
[02:52] SPEAKER: - I mean, it could be, obviously it's a self-selecting group
[02:55] SPEAKER: 'cause it's people who like the kind of stuff that we talk
[02:57] SPEAKER: about here, but I'm hearing more from normal human beings
[03:01] SPEAKER: about Linux than I ever have before.
[03:03] SPEAKER: - Yeah, I mean, yes.
[03:04] SPEAKER: And algorithms are also a thing, you know, like even,
[03:07] SPEAKER: even Blue Sky, which has algorithm lists or supposedly,
[03:11] SPEAKER: I mean, you know, it's still got a discover feed.
[03:12] SPEAKER: Like of course that's gonna be tailored to my interests,
[03:15] SPEAKER: but yes, I am seeing a shocking uptick in posts
[03:18] SPEAKER: from people saying, fuck Windows, I'm out, it's time.
[03:20] SPEAKER: - Well, I mean, so I installed desktop Linux the other day
[03:24] SPEAKER: on a machine to do some testing and I had forgotten
[03:28] SPEAKER: what it's like to do a new, to like to boot into an OS
[03:30] SPEAKER: for the first time and it not try to sell me six things.
[03:34] SPEAKER: I talked about this on a newsletter a couple of weeks ago,
[03:35] SPEAKER: too, but it's like, it's remarkable, right?
[03:38] SPEAKER: Like the number, you don't even, even Apple does it now.
[03:41] SPEAKER: It's like, hey, you want to sign up for, hey man,
[03:44] SPEAKER: we got this real good service that has TV and games.
[03:47] SPEAKER: And then you also, it'll save your photos and all of your
[03:50] SPEAKER: stuff gets backed up and it's only 20 bucks a month
[03:52] SPEAKER: for your whole family, you should totally sign up for it.
[03:54] SPEAKER: - Where's Apple doing that, just on mobile?
[03:56] SPEAKER: - No, it happens on a new Mac.
[03:57] SPEAKER: When you upgrade your Mac, it hits you too.
[03:59] SPEAKER: - Wait, really?
[04:00] SPEAKER: - On my wife's Mac, it did.
[04:01] SPEAKER: The nice thing that Apple, the place that Apple is good
[04:04] SPEAKER: about it is if you're already paying them,
[04:05] SPEAKER: then they don't hit you again.
[04:07] SPEAKER: - Sure, yeah.
[04:07] SPEAKER: - Right, the Microsoft solution is, hey,
[04:10] SPEAKER: I see that you're paying for Microsoft Office right now.
[04:13] SPEAKER: Why don't we just suggest that you could pay us
[04:16] SPEAKER: for Microsoft Office and then be like, oh no,
[04:18] SPEAKER: you're already doing this rather than just not show that.
[04:20] SPEAKER: - Yes. - Anyway.
[04:21] SPEAKER: - I think that there is a deeper episode to come
[04:23] SPEAKER: on desktop Linux in the relatively near future.
[04:25] SPEAKER: I've also been dabbling with it a little bit.
[04:27] SPEAKER: - Yeah. - Currently,
[04:28] SPEAKER: I've got Fedora and Nix OS installed at the moment.
[04:30] SPEAKER: I've got like five others queued up
[04:32] SPEAKER: that I'm gonna try out at some point, but like,
[04:34] SPEAKER: I don't know if I would be able to daily drive it
[04:36] SPEAKER: 'cause I still think about all the stuff I use on Windows
[04:38] SPEAKER: that does not have an immediate analog.
[04:41] SPEAKER: - Or, you know, it has analogs, but are not as good.
[04:43] SPEAKER: You know, like Affinity Photo and is probably
[04:46] SPEAKER: maybe not the best example 'cause yes,
[04:47] SPEAKER: there are image editing programs on Linux.
[04:49] SPEAKER: Are they as good as Affinity or Photoshop?
[04:52] SPEAKER: Not necessarily, like Music Bee,
[04:55] SPEAKER: the kind of iTunes replacement that I use is Windows only.
[04:58] SPEAKER: There's just a lot of little day-to-day quality of life-y
[05:01] SPEAKER: sorts of applications that I would miss a lot.
[05:04] SPEAKER: So I don't know, we'll see.
[05:05] SPEAKER: - Apparently Affinity works with bottles now.
[05:07] SPEAKER: - Bottles?
[05:09] SPEAKER: - Bottles, the, the-
[05:11] SPEAKER: - Was that a wine thing or something?
[05:13] SPEAKER: - It's a wine thing, yeah.
[05:14] SPEAKER: - Okay, I don't know that I wanna mess with wine.
[05:16] SPEAKER: We'll see. - Well.
[05:17] SPEAKER: - We'll see a lot of things.
[05:18] SPEAKER: - Yeah, yeah, we'll see.
[05:20] SPEAKER: We'll see if we have, you know, who knows?
[05:22] SPEAKER: Who knows what tomorrow brings?
[05:24] SPEAKER: - It feels like a big year for we'll see.
[05:26] SPEAKER: (upbeat music)
[05:50] SPEAKER: (upbeat music)
[05:54] SPEAKER: - Welcome to Brad and Will Made a Tech Pod.
[05:57] SPEAKER: I'm Will.
[05:57] SPEAKER: - I'm Brad, hello.
[05:59] SPEAKER: - Hi, we'll see.
[06:00] SPEAKER: - We'll see, what will we see?
[06:02] SPEAKER: - What are we gonna talk about this week?
[06:03] SPEAKER: We'll see, I don't know.
[06:05] SPEAKER: - Figure it out as we go.
[06:07] SPEAKER: - No, we know what we're gonna talk about this week.
[06:08] SPEAKER: - Everybody's feeling punchy lately.
[06:11] SPEAKER: - It's like, okay, I don't wanna talk about politics a lot,
[06:15] SPEAKER: but the thing that I had forgotten
[06:16] SPEAKER: about the bad times before
[06:18] SPEAKER: are how each week seems like simultaneously
[06:21] SPEAKER: 15 minutes and two years.
[06:22] SPEAKER: - Oh, it's insane.
[06:23] SPEAKER: - Yeah. - It's crazy.
[06:24] SPEAKER: I have every other podcast and my rotation
[06:27] SPEAKER: has been replaced by politics podcasts at this point.
[06:30] SPEAKER: Like literally just feed has been purged of everything else
[06:32] SPEAKER: 'cause I don't have room for anything else
[06:34] SPEAKER: with all the politics podcasts I'm listening to right now.
[06:37] SPEAKER: - I'm taking breaks.
[06:38] SPEAKER: I can't pay attention all the time 'cause it breaks me.
[06:40] SPEAKER: - I find this phenomenon extends to every domain in my life
[06:44] SPEAKER: that like everything is being crowded out by this right now.
[06:47] SPEAKER: Put some.
[06:49] SPEAKER: - Well, Mike Masnick this morning posted on Tech Dirt,
[06:52] SPEAKER: which if you don't read Tech Dirt,
[06:54] SPEAKER: Tech Dirt's one of the great remaining tech blogs, I think.
[06:57] SPEAKER: And he was like, look, if you wanna avoid politics,
[07:01] SPEAKER: I got bad news for you
[07:02] SPEAKER: 'cause Tech Dirt's a democracy blog now
[07:04] SPEAKER: because we all have to be democracy blogs
[07:07] SPEAKER: if we wanna continue having democracies.
[07:10] SPEAKER: And I respect that a lot.
[07:12] SPEAKER: Good for Mike.
[07:13] SPEAKER: - Oh, wow.
[07:14] SPEAKER: I took a look at it just now.
[07:15] SPEAKER: It was full on just like a politics blog now.
[07:18] SPEAKER: - Oh, yeah.
[07:19] SPEAKER: - I mean, it's still fairly tech oriented
[07:21] SPEAKER: like a magistrate judge,
[07:22] SPEAKER: if geofence warrants are unconstitutional,
[07:24] SPEAKER: so are cell tower dumps.
[07:25] SPEAKER: I mean, that's still pretty technical.
[07:27] SPEAKER: - But that's also, that is the most Tech Dirt article
[07:30] SPEAKER: that they could possibly post, right?
[07:32] SPEAKER: But also he's taught, they were like, he's just saying,
[07:34] SPEAKER: hey, we're not gonna ignore this stuff because you can't.
[07:37] SPEAKER: - Yeah.
[07:38] SPEAKER: - It's important, it turns out.
[07:40] SPEAKER: - Maybe not coincidentally,
[07:41] SPEAKER: I have also been developing a bit more of an interest
[07:43] SPEAKER: in information security recently.
[07:46] SPEAKER: - Weird, what a weird coincidence.
[07:49] SPEAKER: - But I won't bore you with my efforts
[07:51] SPEAKER: to generate TPM backed SSH keys right now.
[07:55] SPEAKER: - No, we don't need to, look.
[07:56] SPEAKER: - We'll talk about that later.
[07:57] SPEAKER: - I learned that my BitLocker key is stored for my laptop,
[08:01] SPEAKER: is stored in my Microsoft account last night.
[08:04] SPEAKER: I didn't know that.
[08:05] SPEAKER: - Yes, they do that.
[08:05] SPEAKER: - That's very convenient.
[08:06] SPEAKER: - Yeah, the BitLocker keys, I think,
[08:07] SPEAKER: automatically get put in OneDrive for safety.
[08:09] SPEAKER: - Yeah, that's correct.
[08:11] SPEAKER: 'Cause I updated my BIOS and I didn't realize
[08:13] SPEAKER: that the laptop ship was BitLocker on.
[08:15] SPEAKER: And I was like, oh crap, I'm free to build this laptop.
[08:17] SPEAKER: Then it was like, hey, your key might be
[08:19] SPEAKER: in your OneDrive account, in your Microsoft account,
[08:22] SPEAKER: and I button downloaded and put it on a thumb drive
[08:24] SPEAKER: and plugged it in there and it just worked.
[08:25] SPEAKER: - That's cool, that's cool.
[08:27] SPEAKER: - Saved me.
[08:28] SPEAKER: - People complain about TPMs a lot, makes them work for you.
[08:31] SPEAKER: - I was gonna say, I didn't realize,
[08:33] SPEAKER: so switching CPUs in this machine
[08:36] SPEAKER: that I'm using in the same D machine,
[08:38] SPEAKER: I didn't realize that the Windows Hello stuff
[08:40] SPEAKER: is tied to the TPM 'cause every time, yeah.
[08:43] SPEAKER: - You were opening a door here.
[08:45] SPEAKER: - Oh no.
[08:46] SPEAKER: - 'Cause that's exactly the SSH stuff I was talking about.
[08:48] SPEAKER: - Yeah, like-
[08:49] SPEAKER: - So when I generated an S key, S key, sorry, SK,
[08:53] SPEAKER: SSH key, do you know what I'm talking about?
[08:55] SPEAKER: Like when you-
[08:55] SPEAKER: - No.
[08:56] SPEAKER: - When you, it's UB key stuff.
[08:58] SPEAKER: I gather that this is the same thing that works on a UB key,
[09:00] SPEAKER: like when you generate the-
[09:01] SPEAKER: - Yeah, FIDO, FIDO, whatever.
[09:03] SPEAKER: - Right, so like the encryption algorithm,
[09:05] SPEAKER: when you generate the key instead of like ECDSA,
[09:08] SPEAKER: it's ECDSA dash SK, meaning-
[09:11] SPEAKER: - Okay.
[09:11] SPEAKER: - Meaning generate this key against your hardware token,
[09:13] SPEAKER: which could be a UB key or it could be your TPM.
[09:16] SPEAKER: But the thing I was gonna say is when you generate
[09:18] SPEAKER: that key in Windows, it full on pops up
[09:20] SPEAKER: a Windows Hello prompt, and you have to pin number
[09:24] SPEAKER: or face ID or thumbprint to generate the key.
[09:27] SPEAKER: - I ordered a fingerprint sensor-
[09:29] SPEAKER: - Did you?
[09:30] SPEAKER: - To jam underneath my desk yesterday.
[09:30] SPEAKER: - Did you? - Yeah.
[09:31] SPEAKER: - I wanna hear more about that.
[09:32] SPEAKER: - Yeah, that was a challenging,
[09:35] SPEAKER: we'll talk about that maybe on the Q&A episode
[09:37] SPEAKER: or the patron episode this month,
[09:38] SPEAKER: 'cause the reviews were all over the place on those.
[09:41] SPEAKER: And there's a bunch of like 17 to $18 USB thumb drivey
[09:46] SPEAKER: looking ones that are just like a USB plug
[09:48] SPEAKER: and then a thing that you'd tap your finger on.
[09:50] SPEAKER: They all promise the same like half second read time,
[09:55] SPEAKER: but the reviews on them are all over the place.
[09:57] SPEAKER: And some of them have like thousands of reviews
[10:00] SPEAKER: and like a 4.2 or 4.1.
[10:03] SPEAKER: But then when you look at the one star reviews,
[10:06] SPEAKER: they're inevitably, hey, this thing worked
[10:08] SPEAKER: for a couple of weeks and then it stopped working.
[10:11] SPEAKER: So I don't know, I bought a $17 one.
[10:13] SPEAKER: I'll let you know how it goes.
[10:14] SPEAKER: - Okay, I'll be curious to hear about that.
[10:16] SPEAKER: I know something that is managing your biometric security.
[10:19] SPEAKER: I think I would be inclined to go
[10:20] SPEAKER: for the slightly more expensive name brand option
[10:22] SPEAKER: if it came down to it.
[10:24] SPEAKER: - I think I got, no, actually I didn't buy that.
[10:26] SPEAKER: I bought the $27 Kensington one is what I got.
[10:29] SPEAKER: - Yeah, Kensington is the brand I saw
[10:30] SPEAKER: that I recognize when I looked for those.
[10:32] SPEAKER: - It had worse reviews than a lot of the knockoffs,
[10:35] SPEAKER: other than the names that I didn't recognize.
[10:37] SPEAKER: We'll see how it goes.
[10:39] SPEAKER: But I'm excited, I have a little USB duper
[10:41] SPEAKER: that I'm gonna go just tape up underneath the deck,
[10:44] SPEAKER: glue up under the desk, like right where my finger goes.
[10:46] SPEAKER: - Yeah, that sounds good. - So I can scan in.
[10:48] SPEAKER: - I should maybe do that too.
[10:50] SPEAKER: - Yeah, why wouldn't you?
[10:52] SPEAKER: I've gotten used to having the fingerprint sensor
[10:53] SPEAKER: on the laptop and it turns out it's really nice.
[10:55] SPEAKER: - Yeah.
[10:57] SPEAKER: - Speaking of things that are really nice,
[11:01] SPEAKER: we've got a kind of hardware potpourri.
[11:03] SPEAKER: This is probably our last PC hardware state of the union
[11:06] SPEAKER: for quite a while 'cause all the video cards are out,
[11:09] SPEAKER: except for the real low end stuff from Nvidia and AMD
[11:12] SPEAKER: and all of the CPUs are out now.
[11:14] SPEAKER: - With one kind of major exception,
[11:16] SPEAKER: but it's soon and probably not anything you're not expecting.
[11:20] SPEAKER: I don't know.
[11:21] SPEAKER: - I think it's pretty predictable given what we,
[11:24] SPEAKER: like there's a little couple of questions about it
[11:25] SPEAKER: we can talk about, but.
[11:26] SPEAKER: - That's the 9950 X3D that we're referring to.
[11:29] SPEAKER: - Yeah, the Ryzen, the AMD part.
[11:31] SPEAKER: The big 16 core and I think that's probably it
[11:33] SPEAKER: for CPU's this year, which we'll get to,
[11:35] SPEAKER: but I think from the sound of it.
[11:37] SPEAKER: - I think we'll see stuff down,
[11:39] SPEAKER: like we'll see down, you know,
[11:42] SPEAKER: down the stack versions, material.
[11:44] SPEAKER: Yeah, right now the high and high mid are filled out
[11:48] SPEAKER: and we don't have like low end equivalents,
[11:50] SPEAKER: but people don't really cover that stuff all that much.
[11:52] SPEAKER: 'Cause if you're buying a Celeron,
[11:54] SPEAKER: it turns out you probably don't care about performance
[11:56] SPEAKER: all that much.
[11:57] SPEAKER: - Although actually, I mean, we'll get to it.
[11:58] SPEAKER: Maybe we'll save this for the end,
[11:59] SPEAKER: but there is stuff going on in low power CPU's.
[12:02] SPEAKER: I am very excited about it.
[12:04] SPEAKER: - Well, yeah, so let's start with the Radeon stuff.
[12:07] SPEAKER: 'Cause the embargoes and the reviews drop
[12:10] SPEAKER: for the Radeon 9070 XT and 9070.
[12:14] SPEAKER: These are, it seems like the top of AMD's new stack.
[12:19] SPEAKER: They've said this generation with RDNA 4
[12:22] SPEAKER: that they're not chasing Nvidia at the high end.
[12:25] SPEAKER: And it looks like they're going for the kind of high margin,
[12:28] SPEAKER: high volume or lower margin, high volume parts
[12:32] SPEAKER: that are in the 550-ish MSRP.
[12:36] SPEAKER: - Yeah, what is the XT 599 I wanna say?
[12:39] SPEAKER: - The XT is 599 MSRP and then the other one's 50 bucks.
[12:43] SPEAKER: The 9070 is 50 bucks less.
[12:45] SPEAKER: We talked about this in the full nerd a little bit this week,
[12:47] SPEAKER: but presumably that's because of the 9070 exists
[12:51] SPEAKER: so that the cards that don't bin at the XT speed,
[12:56] SPEAKER: they can still sell them.
[12:58] SPEAKER: - Still get sold, that makes sense.
[13:00] SPEAKER: - Typically that non XT is kind of a bad deal
[13:02] SPEAKER: on the AMD side.
[13:04] SPEAKER: But in this case, I was watching the Digital Foundry review
[13:08] SPEAKER: earlier this morning and they do dollars per frame,
[13:12] SPEAKER: which is a funny metric to me.
[13:14] SPEAKER: - Honestly, that might be the metric.
[13:16] SPEAKER: - Yeah, and to their point, they were like,
[13:19] SPEAKER: the 9070 non XT dollars per frame is less bad
[13:23] SPEAKER: than it usually is.
[13:24] SPEAKER: - So, but they seem like really good cards.
[13:27] SPEAKER: The big change with RDNA 4 is that they've added
[13:32] SPEAKER: hardware acceleration for ray tracing and tensor core,
[13:35] SPEAKER: like neural AI type workloads to these GPUs finally.
[13:39] SPEAKER: - Better hardware ray tracing, we should say.
[13:41] SPEAKER: - Well, no, in previous days,
[13:43] SPEAKER: the ray tracing ran on the shader cores on the RDNA 3.
[13:46] SPEAKER: - All of it?
[13:47] SPEAKER: - Yeah, so that's why the performance was so shit.
[13:50] SPEAKER: - Oh my God, I had no idea that was the case.
[13:52] SPEAKER: - Yeah, so basically what you were doing
[13:55] SPEAKER: was sacrificing shader performance to run ray tracing.
[13:59] SPEAKER: And it was a real double whammy of, let me put it this way.
[14:04] SPEAKER: There's a way to make it run right.
[14:05] SPEAKER: And you see it happen on the consoles
[14:07] SPEAKER: that do ray tracing stuff because you just have to balance,
[14:12] SPEAKER: like when you're in a ray tracing,
[14:13] SPEAKER: when you're making your ray tracing game
[14:14] SPEAKER: for say the Xbox series, you have to balance
[14:17] SPEAKER: your shader utilization with your ray tracing stuff.
[14:21] SPEAKER: And you can do it if you know what the hardware is.
[14:23] SPEAKER: But if you're building,
[14:25] SPEAKER: if you're in the real world making PC games
[14:27] SPEAKER: and you're doing ray tracing stuff
[14:29] SPEAKER: for the 80% of the market that's on NVIDIA hardware,
[14:32] SPEAKER: then you're building for tensor cores
[14:34] SPEAKER: and not expecting that shader model performance to drop.
[14:39] SPEAKER: So that's why you have games like Black Myth Wukong
[14:41] SPEAKER: really performing badly when you flip on ray tracing on AMD.
[14:45] SPEAKER: - Yeah, that makes sense.
[14:46] SPEAKER: - So that's fixed now.
[14:47] SPEAKER: - I had no idea about that.
[14:48] SPEAKER: That is, that brings some things into relief.
[14:51] SPEAKER: - Yeah, it explains, like it's why the recommendation
[14:54] SPEAKER: for previous Radeon cards has been,
[14:59] SPEAKER: if you don't care about ray tracing, these are fine cards.
[15:02] SPEAKER: If you care about ray tracing, you should buy the other one.
[15:04] SPEAKER: - Yeah, yeah, I had heard that for ages.
[15:06] SPEAKER: The thing I didn't realize is that they literally
[15:08] SPEAKER: did not even have hardware ray tracing.
[15:09] SPEAKER: - Nope.
[15:10] SPEAKER: - But that would explain the performance delta there.
[15:13] SPEAKER: Here's my big question about these
[15:15] SPEAKER: or about AMD's strategy here.
[15:18] SPEAKER: - Yeah.
[15:19] SPEAKER: - Was it around CES that they came out and said,
[15:22] SPEAKER: "Hey, we're not gonna have a high-end part this generation,
[15:25] SPEAKER: like don't expect that, we're targeting the mid range here."
[15:28] SPEAKER: - Yeah.
[15:29] SPEAKER: - Do you think on the roadmap or in R&D,
[15:32] SPEAKER: the 9070 XT was a flagship part
[15:34] SPEAKER: that they thought would compete?
[15:36] SPEAKER: Or was this always the mid range part
[15:39] SPEAKER: and they just didn't ship what would have been
[15:40] SPEAKER: the high-end part?
[15:41] SPEAKER: - My guess is that this was always the mid range part.
[15:45] SPEAKER: - Okay.
[15:45] SPEAKER: - The other theory I have is that maybe
[15:48] SPEAKER: they were looking at doing a disaggregated architecture
[15:53] SPEAKER: and that they were gonna put multiples of these
[15:55] SPEAKER: on one GPU package.
[15:57] SPEAKER: - Yeah.
[15:58] SPEAKER: - But that seems, nobody's done that
[15:59] SPEAKER: and I'm sure there's good reasons for that,
[16:01] SPEAKER: but I don't know enough about how chip design works
[16:03] SPEAKER: to know why you wouldn't do that.
[16:04] SPEAKER: - Yeah, there's been, there's a bunch of talk about UDNA,
[16:07] SPEAKER: which is the next gen architecture
[16:08] SPEAKER: that will succeed our DNA for.
[16:10] SPEAKER: And this is from some people on the Discord.
[16:12] SPEAKER: I tried to look up more information on this
[16:15] SPEAKER: and could not find it, but their suggestion
[16:17] SPEAKER: was that UDNA might be disaggregated.
[16:20] SPEAKER: - I haven't seen anything that implies that.
[16:22] SPEAKER: - I could not.
[16:23] SPEAKER: - As I like rumors.
[16:24] SPEAKER: - I could not find anything specific there either, but.
[16:28] SPEAKER: - I mean, look, disaggregate, going disaggregated
[16:30] SPEAKER: in the CPU has been really good for AMD.
[16:32] SPEAKER: So my understanding is that if you want to,
[16:36] SPEAKER: the reason nobody's doing, like the reason Nvidia
[16:38] SPEAKER: is making these enormous Blackwell dies
[16:41] SPEAKER: is because the interconnects between different compute dies
[16:46] SPEAKER: on a GPU would have to be much faster than on a CPU.
[16:51] SPEAKER: - Yeah.
[16:51] SPEAKER: - And, you know, in order for it not to impact performance.
[16:55] SPEAKER: This is why we don't do SLI anymore is 'cause, you know,
[16:57] SPEAKER: the SLI, the PCI express bus,
[17:01] SPEAKER: even with the SLI bridge thing was not fast enough
[17:06] SPEAKER: or multiple GPUs to make sense given the timeframes,
[17:10] SPEAKER: you know, given that it's two milliseconds
[17:12] SPEAKER: for each frame that's rendered these days.
[17:15] SPEAKER: - Yeah, like you're getting into territory
[17:16] SPEAKER: where like any amount of cabling or even like traces
[17:19] SPEAKER: on a PCB is too much, you know,
[17:21] SPEAKER: like it just needs to all be on the same chip.
[17:23] SPEAKER: - Yeah, latency matters.
[17:25] SPEAKER: So anyway, yeah, but the point is,
[17:30] SPEAKER: these cards are reviewing really well.
[17:32] SPEAKER: The performance is really good.
[17:33] SPEAKER: They're showing decent ray tracing perf.
[17:36] SPEAKER: It's a little up and down from game to game.
[17:39] SPEAKER: It's probably worth mentioning that a lot
[17:41] SPEAKER: of the heavy ray tracing games that we all use
[17:43] SPEAKER: for benchmarks like Wukong and Cyberpunk.
[17:49] SPEAKER: Wait, Indiana Jones doesn't have a built-in benchmark,
[17:51] SPEAKER: so I haven't actually tested that.
[17:53] SPEAKER: But I mean, like the performance is all over the place
[17:57] SPEAKER: and a lot of these are Nvidia implementations
[18:01] SPEAKER: 'cause there wasn't AMD hardware
[18:03] SPEAKER: that did hardware accelerated ray tracing
[18:04] SPEAKER: until just recently.
[18:06] SPEAKER: So, you know, like Wednesday, just to be clear.
[18:10] SPEAKER: - Yeah, I mean, I wonder like what are the,
[18:13] SPEAKER: like DXR, DirectX ray tracing
[18:16] SPEAKER: is kind of the main generalized API for ray tracing.
[18:20] SPEAKER: I don't know if they're, well, there's Vulkan.
[18:21] SPEAKER: I guess Vulkan has also gotten ray tracing support, so.
[18:25] SPEAKER: - Yeah, so, well, and like the full path tracing
[18:30] SPEAKER: implementations are often, depending on the game,
[18:34] SPEAKER: either built by the developers with help from Nvidia
[18:37] SPEAKER: or like I assume there's some sort of co-marketing agreement
[18:41] SPEAKER: for some of these games that have full path tracing, right?
[18:44] SPEAKER: So, you know, put that in your conspiracy pipe
[18:49] SPEAKER: and smoke it, if you will.
[18:53] SPEAKER: But yeah, so the perf is really good though
[18:55] SPEAKER: at that mid range, at that $550 price point.
[18:58] SPEAKER: - The gist I've gotten from looking at benchmarks
[19:00] SPEAKER: and reviews is that like a 9070 XT is like
[19:04] SPEAKER: somewhere between a 5070 and a 5070 TI,
[19:07] SPEAKER: depending on the game.
[19:08] SPEAKER: Like I think I saw in a few benchmarks
[19:10] SPEAKER: that maybe even beat out the 5070 TI just barely,
[19:13] SPEAKER: but it's kind of like low to mid end
[19:16] SPEAKER: of the 50 series for 600 bucks.
[19:19] SPEAKER: - But also the 5070 TI is a $650 card
[19:22] SPEAKER: that you can't really get for less than $900 right now.
[19:24] SPEAKER: - I mean, what's going on with price markups
[19:26] SPEAKER: is like a whole separate conversation,
[19:28] SPEAKER: which mostly really sucks.
[19:30] SPEAKER: Except I think some of these, I think the AMD cards,
[19:33] SPEAKER: at least some of them have been landing in MSRP.
[19:36] SPEAKER: So yeah, some of the cards are landing in MSRP.
[19:40] SPEAKER: Nvidia had two 5070s, I think an XFX and a SUSE.
[19:46] SPEAKER: Might've been a gigabyte too,
[19:48] SPEAKER: that were MSRP priced cards for the 5070 at 550.
[19:53] SPEAKER: They also had a couple of 5070 TIs
[19:55] SPEAKER: that were MSRP priced that actually shipped,
[19:58] SPEAKER: but those cards are insanely hard to get.
[20:01] SPEAKER: And like all of these cards are going the moment,
[20:07] SPEAKER: basically the moment they go on sale right now,
[20:09] SPEAKER: 'cause demand is really high.
[20:10] SPEAKER: - Yeah, I have not seen the PC channel and the Discord
[20:13] SPEAKER: this buzzy about maybe any product launch,
[20:17] SPEAKER: but definitely a graphics card launch in a while.
[20:19] SPEAKER: Like people are, these AMD cards are,
[20:22] SPEAKER: I think, going to go very fast.
[20:24] SPEAKER: - And I think I might've said the wrong prices a minute ago,
[20:27] SPEAKER: the 9070 is 550 and the 9070 XT is 600 bucks.
[20:30] SPEAKER: - Yeah, that's right.
[20:31] SPEAKER: - Okay.
[20:32] SPEAKER: - Yes, this is just a weird aside.
[20:34] SPEAKER: It's kind of, it's been funny talking about,
[20:37] SPEAKER: or I'm sorry, seeing people talk about like the clamoring
[20:41] SPEAKER: for some of the brands that people are talking about here,
[20:43] SPEAKER: because it's almost, it's largely different vendors
[20:46] SPEAKER: I feel like in the AMD space these days
[20:48] SPEAKER: than you see in Nvidia.
[20:49] SPEAKER: 'Cause Nvidia is like, Nvidia is all a SUSE
[20:51] SPEAKER: and gigabyte and MSI and like,
[20:53] SPEAKER: I guess ASRock is making cards now.
[20:55] SPEAKER: It's mostly motherboard makers actually,
[20:57] SPEAKER: I guess now that EVGA is gone,
[20:58] SPEAKER: but it's like big brands like that.
[21:00] SPEAKER: And then over here, it's like, oh, I got the Sapphire card
[21:03] SPEAKER: where I'm getting the power color or the XFX.
[21:05] SPEAKER: It's like, there's nothing wrong with those brands.
[21:07] SPEAKER: It's just, I never see them referenced anymore
[21:09] SPEAKER: because people talk about Nvidia so damn much
[21:11] SPEAKER: that it just kind of like drives home what a,
[21:16] SPEAKER: I don't know if you see change is not the right word,
[21:18] SPEAKER: but like it's kind of a reframing of the graphics race here
[21:20] SPEAKER: where like AMD has actually got a product
[21:22] SPEAKER: people really want again.
[21:23] SPEAKER: And it's kind of cool to see different names popping up.
[21:26] SPEAKER: - Yeah, AMD, I mean, these are all like classic AMD
[21:30] SPEAKER: graphics vendors. - Yeah, I know.
[21:32] SPEAKER: - But yeah, it's been interesting to see.
[21:35] SPEAKER: I think that there's a couple of things causing,
[21:38] SPEAKER: okay, so there's a couple of things happening.
[21:39] SPEAKER: One is a lot of the up and down of the Nvidia pricing
[21:43] SPEAKER: is because they announced pricing at CES.
[21:48] SPEAKER: And then before they knew what the tariff situation
[21:51] SPEAKER: was gonna be. - Darn.
[21:53] SPEAKER: - And then that means that the vendors have to choose
[21:56] SPEAKER: to eat the MSR, the tariff in their pricing if they can.
[22:00] SPEAKER: And most of them are not gonna do that
[22:01] SPEAKER: because they're all out to make money.
[22:04] SPEAKER: So it's a really unfortunate,
[22:06] SPEAKER: like it's left a lot of ambiguity in the pricing
[22:10] SPEAKER: for these AIB cards. - Yeah, I get it.
[22:13] SPEAKER: I mean, on the Patreon episode last week,
[22:15] SPEAKER: I complained about how expensive
[22:17] SPEAKER: the supposedly budget iPhone 16E is.
[22:19] SPEAKER: And I'm sure some of that is probably absorbing tariffs
[22:21] SPEAKER: as well. - 10 or 20% for everything,
[22:23] SPEAKER: 20% for everything in China, I think is what it is now.
[22:26] SPEAKER: - Good stuff.
[22:29] SPEAKER: Yeah, so like they're selling out really fast.
[22:34] SPEAKER: It seems like the MSRP cards sold out
[22:36] SPEAKER: almost immediately this morning.
[22:37] SPEAKER: I'm looking at a PC world article by Mike Crider
[22:40] SPEAKER: that talks about that.
[22:41] SPEAKER: Five minutes after the time of sale went on,
[22:46] SPEAKER: you could get cards that were marked up about 150 bucks.
[22:49] SPEAKER: I wouldn't do that.
[22:50] SPEAKER: Like just like don't, unless like,
[22:54] SPEAKER: so the thing that's happening is people
[22:56] SPEAKER: who are sitting on like 20, 80 systems right now
[22:58] SPEAKER: are looking for upgrades, right?
[23:00] SPEAKER: 'Cause those 1080 TI's, those 2080's, those 1070's,
[23:03] SPEAKER: those 1060's especially are starting to feel the pinch.
[23:07] SPEAKER: - Yeah, and I mean, this card isn't,
[23:08] SPEAKER: for the money, if you get it at retail
[23:11] SPEAKER: is an unbelievable upgrade over cards like that.
[23:13] SPEAKER: - Yeah, I mean, like you're upgrading a card that was,
[23:17] SPEAKER: if you're upgrading a 1080 TI,
[23:18] SPEAKER: you're upgrading a $700 card
[23:20] SPEAKER: to a card that's a little bit cheaper
[23:22] SPEAKER: and is gonna be way faster.
[23:25] SPEAKER: - I don't think we did 1080 TI numbers.
[23:29] SPEAKER: He might've done 1080 TI numbers with the 5070.
[23:33] SPEAKER: But the, we did 1080 TI numbers for the 5070,
[23:40] SPEAKER: no, for the Battle Mage cards when we reviewed those
[23:44] SPEAKER: to see what you get.
[23:45] SPEAKER: And it's actually, the average frame rates
[23:47] SPEAKER: are kind of the same, but the 1% lows on a 1080 TI
[23:51] SPEAKER: versus a new card that you buy today
[23:54] SPEAKER: are dramatically, dramatically better.
[23:56] SPEAKER: - Sure.
[23:56] SPEAKER: - So you're getting smoother frame rates
[23:58] SPEAKER: with less micro stutter and less freezes
[24:00] SPEAKER: and stuff like that.
[24:01] SPEAKER: And you know, that's what you want, I think.
[24:06] SPEAKER: For what it's worth, the other Brad in my life,
[24:08] SPEAKER: Brad Charcus over at PC World really liked the 50,
[24:11] SPEAKER: the 9070 XT.
[24:13] SPEAKER: - Yeah, I can see it.
[24:14] SPEAKER: You know, like we should also mention,
[24:16] SPEAKER: so like kind of every pillar of the card
[24:20] SPEAKER: outside of game performance has also gotten better.
[24:22] SPEAKER: You know, like when you look at, we talk about Nvidia
[24:24] SPEAKER: a lot in this context of like, hey, Nvidia cards
[24:27] SPEAKER: have a lot of fringe benefits
[24:28] SPEAKER: that are not just raw performance, you know,
[24:30] SPEAKER: like obviously DLSS is huge, like the ray tracing
[24:34] SPEAKER: has been best in class and also in the ink,
[24:36] SPEAKER: the onboard video encoder for better streaming and stuff,
[24:41] SPEAKER: you know, has also been industry leading.
[24:43] SPEAKER: So apparently like all of that is significantly better
[24:46] SPEAKER: for AMD now on this gen.
[24:48] SPEAKER: So like FSR4, their latest version of their upscaling tech
[24:51] SPEAKER: apparently is like, it's all digital foundry saying like,
[24:54] SPEAKER: hey, it's finally really good.
[24:55] SPEAKER: Like it's finally competitive with DLSS.
[24:58] SPEAKER: And apparently AMD's video encoder has been terrible
[25:02] SPEAKER: for a long time.
[25:03] SPEAKER: - It's bad to the point that nobody supports it.
[25:06] SPEAKER: - Yes, yes.
[25:06] SPEAKER: Like I keep an eye on EposVox on YouTube
[25:09] SPEAKER: has been doing quality comparisons between NV Ink,
[25:13] SPEAKER: Quicksync, which is Intel's streamer encoder.
[25:16] SPEAKER: And AMD's is so rarely used.
[25:19] SPEAKER: I can't even remember what it's called.
[25:20] SPEAKER: Is it AMF? I want to say, I forget.
[25:22] SPEAKER: Anyway, it doesn't matter.
[25:24] SPEAKER: The point is he also posted a video that said that,
[25:26] SPEAKER: hey, the onboard video encoding on these new radions
[25:30] SPEAKER: is finally totally fine.
[25:31] SPEAKER: Like it's, 'cause he does actual quantitative analysis
[25:36] SPEAKER: of the video quality and it's like right up there
[25:37] SPEAKER: with NVIDIA stuff now.
[25:38] SPEAKER: It's like, it's kind of impressive.
[25:40] SPEAKER: Like they really just like on every metric,
[25:43] SPEAKER: they have gotten this card competitive to the point
[25:46] SPEAKER: that I would almost actually consider using one now
[25:48] SPEAKER: for stuff that's not just the raw performance.
[25:51] SPEAKER: - Yeah, the FSR4 stuff is really neat.
[25:54] SPEAKER: They like, as is often the case with AMD,
[25:56] SPEAKER: they have a little bit of an outreach
[25:58] SPEAKER: and developer engagement problem,
[26:00] SPEAKER: just because NVIDIA is an enormous company
[26:03] SPEAKER: and employs a buttload of people in their dev rel team.
[26:07] SPEAKER: AMD doesn't have that, those kinds of resources.
[26:10] SPEAKER: So they have a bunch of games
[26:12] SPEAKER: that are supported out of the gate,
[26:13] SPEAKER: but they, you have to use a driver,
[26:17] SPEAKER: like it applies at the driver level.
[26:19] SPEAKER: So if you flip it on in there,
[26:21] SPEAKER: what's it called?
[26:22] SPEAKER: The Ryzen, no, no, the Catalyst software, I think.
[26:25] SPEAKER: Or Adrenaline software.
[26:28] SPEAKER: Catalyst is the old one.
[26:30] SPEAKER: So the Adrenaline software you do is you say,
[26:32] SPEAKER: hey, I want to use FSR4.
[26:33] SPEAKER: And then some games that support FSR 3.1,
[26:38] SPEAKER: it'll override the FSR number.
[26:43] SPEAKER: It'll override the version of FSR
[26:45] SPEAKER: that ships with the game to the FSR4 one
[26:48] SPEAKER: that uses the AI up-sampling
[26:51] SPEAKER: instead of the old shader model up-sampling.
[26:55] SPEAKER: - Yeah, that thought did occur to me
[26:56] SPEAKER: as I was thinking, we'll get into this in a second,
[26:58] SPEAKER: like as I was thinking like,
[26:59] SPEAKER: maybe I should move to one of these cards
[27:00] SPEAKER: for a number of reasons.
[27:01] SPEAKER: But that did hit me that like any game older
[27:04] SPEAKER: than six or eight months, maybe a year,
[27:07] SPEAKER: you're still going to be on older,
[27:09] SPEAKER: frappier versions of things like FSR.
[27:11] SPEAKER: So it's not great if you play a lot of games
[27:14] SPEAKER: that are not brand spanking new.
[27:17] SPEAKER: - Yeah, I mean, and that also is one of the questions
[27:20] SPEAKER: we get when we were talking about these cards, right?
[27:23] SPEAKER: Is, hey, how are the drivers?
[27:25] SPEAKER: 'Cause a lot of people have had problems
[27:26] SPEAKER: with AMD drivers before.
[27:28] SPEAKER: And like realistically, the games that we tried
[27:33] SPEAKER: out of the gate, Adam ran benchmarks
[27:37] SPEAKER: and then spent a couple of days
[27:38] SPEAKER: just playing as many games as he could touch.
[27:40] SPEAKER: And the results were pretty good.
[27:43] SPEAKER: But the stuff like, hey, the FSR4
[27:45] SPEAKER: is not natively supported.
[27:46] SPEAKER: You have to do this weird control panel override.
[27:50] SPEAKER: And it crashed in a couple of tests
[27:52] SPEAKER: with the pre-release driver, which not unusual.
[27:54] SPEAKER: Like the 1590 had some crashes
[27:57] SPEAKER: and that first post 1590 launch driver
[28:00] SPEAKER: that Nvidia released was,
[28:02] SPEAKER: I had a really awful time with it.
[28:05] SPEAKER: But it's always something that's nervous making.
[28:09] SPEAKER: - Yeah, I could see that.
[28:11] SPEAKER: I mean, unless you literally have no video card
[28:13] SPEAKER: and you absolutely need something immediately,
[28:15] SPEAKER: I don't think it would maybe be prudent
[28:17] SPEAKER: to give it three months for supply and prices to settle down
[28:21] SPEAKER: and see how drivers shape up and stuff like that.
[28:24] SPEAKER: - Yeah, I mean, here's the thing.
[28:25] SPEAKER: If you can get one of these at MSRP,
[28:27] SPEAKER: I think it's, and you're in the market for a card,
[28:30] SPEAKER: I think it's okay to go for it.
[28:31] SPEAKER: But yeah, like it's, you're not gonna have a bad time.
[28:35] SPEAKER: But I do, and like the one place
[28:38] SPEAKER: that AMD has an enormous advantage is the graphics drivers
[28:42] SPEAKER: and Linux.
[28:43] SPEAKER: Like they are, their Linux drivers are world-class.
[28:46] SPEAKER: - Well, or their own source is the big thing.
[28:48] SPEAKER: Like that's the split there.
[28:49] SPEAKER: And so I've been looking at this,
[28:51] SPEAKER: I've got a 4090 in this machine,
[28:52] SPEAKER: but I have also been dabbling with some desktop Linuxes
[28:55] SPEAKER: and probably will continue to do so.
[28:56] SPEAKER: So I was like, and I need a smaller card.
[28:58] SPEAKER: That's the other thing.
[29:00] SPEAKER: My, this 4090 is a four slot card effectively.
[29:04] SPEAKER: It was like three and a half slots already
[29:06] SPEAKER: before I replaced the shroud
[29:07] SPEAKER: and put some Noctua fans on it.
[29:09] SPEAKER: And now it's like basically a four slot,
[29:11] SPEAKER: which really limits my motherboard options
[29:13] SPEAKER: for when I want to upgrade.
[29:15] SPEAKER: So I was, I've also kind of wanted to get
[29:16] SPEAKER: onto a smaller physically graphics card.
[29:19] SPEAKER: So I was looking at this and I was like,
[29:21] SPEAKER: you know, AMD like just works on Linux
[29:23] SPEAKER: where in video you have to jump through extra hoops,
[29:25] SPEAKER: like certain things on the desktop still don't work as well.
[29:28] SPEAKER: Like problems get fixed much slower.
[29:32] SPEAKER: It's a pretty big performance downgrade
[29:34] SPEAKER: from a 4090 to a 1970 XT though.
[29:37] SPEAKER: - It is a pretty substantial performance downgrade.
[29:40] SPEAKER: If you're playing at 1080p, it doesn't matter.
[29:41] SPEAKER: If you're playing at 4K, you're going to feel it.
[29:43] SPEAKER: - I'm at 1440, so I'm kind of in the middle of that.
[29:46] SPEAKER: - Yeah, these are pretty clearly 1440p cards
[29:50] SPEAKER: for the most part,
[29:52] SPEAKER: especially if you're talking about ray tracing games,
[29:54] SPEAKER: 'cause you know, the ray tracing,
[29:56] SPEAKER: like Indiana Jones and the Star Wars Outlaws
[29:58] SPEAKER: and all those use a ton of memory
[30:01] SPEAKER: and they will fill a 16 gig card.
[30:04] SPEAKER: - So there is no option for more RAM.
[30:06] SPEAKER: That's the only one on the market.
[30:07] SPEAKER: - 16 gigs.
[30:09] SPEAKER: - Yeah.
[30:12] SPEAKER: - But you can play 4K raster games pretty easily.
[30:15] SPEAKER: Like I played some Fortnite the other day
[30:17] SPEAKER: and got really nice perf out of that at 4K,
[30:20] SPEAKER: but you're not gonna, you know,
[30:22] SPEAKER: you're not gonna, like the weird thing is I've been,
[30:26] SPEAKER: we've been testing these OLED monitors.
[30:28] SPEAKER: MSI sent me one of the 4K 240 Hertz OLEDs
[30:33] SPEAKER: that they released at CES.
[30:36] SPEAKER: And honestly, if you're sitting,
[30:38] SPEAKER: like this is the most, like the overall verdict,
[30:42] SPEAKER: we don't need to get into the Nvidia stuff
[30:44] SPEAKER: 'cause you've already talked about it.
[30:45] SPEAKER: The 5070 is kind of a stinker.
[30:47] SPEAKER: The 5070 Ti I think is okay.
[30:50] SPEAKER: The internet's upset that it doesn't have as much RAM
[30:52] SPEAKER: as they felt like it should.
[30:54] SPEAKER: - Does it have 16 also?
[30:55] SPEAKER: - It's 16, they think it should be 24.
[30:58] SPEAKER: Because you know, of course, why shouldn't it have 24?
[31:01] SPEAKER: They made a decision like four years ago
[31:03] SPEAKER: about how much RAM that card should have
[31:04] SPEAKER: and it seemed reasonable at the time.
[31:06] SPEAKER: And then three games came out
[31:08] SPEAKER: that filled your video card RAM for the first time
[31:11] SPEAKER: in the entirety of the time
[31:12] SPEAKER: that I remember covering video cards, right?
[31:16] SPEAKER: So like, I'm not making, just to be clear,
[31:19] SPEAKER: not making excuses for Nvidia.
[31:21] SPEAKER: They just missed the, they misprojected
[31:23] SPEAKER: when they specked out this card ages ago.
[31:27] SPEAKER: Like if you're on a last gen video card,
[31:28] SPEAKER: either AMD or Nvidia, and you have $1,000 burning a hole
[31:33] SPEAKER: in your pocket for a new, to buy something new,
[31:36] SPEAKER: I would buy one of these OLED monitors
[31:38] SPEAKER: before I would buy either of these new video cards.
[31:41] SPEAKER: Right, it is an enormous upgrade.
[31:44] SPEAKER: The HDR support is really nice.
[31:46] SPEAKER: It actually works in Windows 11 finally.
[31:49] SPEAKER: And 240 hertz OLED with good blacks
[31:51] SPEAKER: and like a thousand nit panel is fricking gorgeous looking.
[31:57] SPEAKER: - It's honestly, it's the pure blacks,
[31:59] SPEAKER: the contrast, the classic OLED advantages
[32:01] SPEAKER: that would move the needle for me
[32:03] SPEAKER: because like even these like relatively decent IPS panels
[32:07] SPEAKER: that I have, contrast is just shit on PC monitors
[32:10] SPEAKER: in general, LCD ones, or has been traditionally.
[32:13] SPEAKER: So like- - It's rough, yeah.
[32:14] SPEAKER: - Like getting real actual black levels
[32:16] SPEAKER: on a PC monitor would be real nice.
[32:18] SPEAKER: But I was looking at 1440p OLED monitors the other day
[32:22] SPEAKER: just for fun, I'm not actually gonna buy anything,
[32:25] SPEAKER: but like even those are still like $700, which is just,
[32:30] SPEAKER: no, that's for something I don't need, that's too much.
[32:35] SPEAKER: - Well, I mean, this is firmly in the realm
[32:37] SPEAKER: of if you use this all the time and this is the thing,
[32:40] SPEAKER: you know, go nuts, but-
[32:41] SPEAKER: - I mean, I'm in front of this computer
[32:43] SPEAKER: for 10 plus hours a day, but-
[32:45] SPEAKER: - Yeah, your eyes deserve, you should get two,
[32:47] SPEAKER: one for each eye.
[32:50] SPEAKER: The 1440p ones are also the Pulsar ones,
[32:52] SPEAKER: I think in some cases, so they go up to 500 hertz,
[32:54] SPEAKER: which means you can run the CRT emulation
[32:58] SPEAKER: phosphor stuff on them. - CRT shader.
[33:00] SPEAKER: - Yeah, the Blur Busters one.
[33:02] SPEAKER: - Now I might be back on port.
[33:03] SPEAKER: - Yeah, you need to put it in portrait though
[33:06] SPEAKER: so you can play Donkey Kong, that's the real test.
[33:09] SPEAKER: Okay, so other things going on,
[33:13] SPEAKER: anything else on the Radeon side
[33:14] SPEAKER: before we skip through the Nvidia
[33:15] SPEAKER: and then tell stuff real fast?
[33:17] SPEAKER: - I mean, I wrote down next gen console applications here,
[33:20] SPEAKER: like this all seems very promising
[33:23] SPEAKER: for whatever the next boxes end up being,
[33:25] SPEAKER: 'cause all the rumors, I mean,
[33:29] SPEAKER: the console design rumors are very hard to nail down.
[33:32] SPEAKER: It doesn't sound like,
[33:33] SPEAKER: definitely nothing is in production yet.
[33:35] SPEAKER: I don't know that any specs
[33:36] SPEAKER: have been 100% fully locked yet.
[33:37] SPEAKER: Maybe on the Xbox side, there was a report from,
[33:39] SPEAKER: I think, Windows Central recently
[33:41] SPEAKER: that the next Xbox is past the pitch phase
[33:44] SPEAKER: and has been approved, so maybe that design is locked.
[33:46] SPEAKER: I don't know, but like-
[33:48] SPEAKER: - That makes sense.
[33:49] SPEAKER: - This is really exciting
[33:50] SPEAKER: because I think we've talked about before,
[33:52] SPEAKER: like these previous consoles landed
[33:54] SPEAKER: at a really terrible time for graphics technology.
[33:57] SPEAKER: - Yeah, it's-
[33:58] SPEAKER: - It was right before ray tracing
[34:01] SPEAKER: really got serious in hardware,
[34:03] SPEAKER: right before machine learning upscaling happened,
[34:06] SPEAKER: like a number of very critical foundational technologies
[34:10] SPEAKER: were just starting to happen
[34:12] SPEAKER: when the current consoles came out.
[34:14] SPEAKER: - When did they launch, 2019?
[34:16] SPEAKER: - 2020.
[34:17] SPEAKER: - 2020, winter of 2020, like during the pandemic?
[34:20] SPEAKER: - Yeah, November, 2020.
[34:22] SPEAKER: - Yeah, so-
[34:23] SPEAKER: - So they don't have,
[34:24] SPEAKER: they've got like very, very limited FSR support.
[34:27] SPEAKER: They've got, you know, whatever shader-based ray tracing
[34:30] SPEAKER: AMD was capable of five years ago.
[34:33] SPEAKER: - Yeah, well, they've got the FSR support
[34:34] SPEAKER: that runs on the shader model, shader units,
[34:36] SPEAKER: just like on every other AMD video card up until Wednesday.
[34:40] SPEAKER: - So like breakdowns of the PS5 Pro that I saw
[34:43] SPEAKER: theorized that it was using a fair number
[34:45] SPEAKER: of RDNA4 features similar to what we're looking at here.
[34:48] SPEAKER: - That's interesting.
[34:49] SPEAKER: - And so if you project out another three to four years,
[34:52] SPEAKER: ah, maybe, ah, three years tops probably, right?
[34:57] SPEAKER: Like I'm surely, I think it sounds like by 27 or 28,
[35:00] SPEAKER: we're gonna see proper new consoles
[35:02] SPEAKER: and there's even a rumor floating around.
[35:04] SPEAKER: This was on like, how was it?
[35:06] SPEAKER: And the site starts with a W, you know,
[35:09] SPEAKER: the one WWCC tech, WCF tech, you know what I'm talking about?
[35:14] SPEAKER: - Oh, WCCF tech, yeah.
[35:15] SPEAKER: - Yeah, that's the one, that's the one.
[35:16] SPEAKER: So, I mean, this was a rumor from there.
[35:18] SPEAKER: You tell me how credible those things are,
[35:19] SPEAKER: but there was a rumor floating around on there
[35:22] SPEAKER: that the PlayStation 6 will have 3D V-cache support as well.
[35:26] SPEAKER: - That seems like fanboy wishful thinking.
[35:29] SPEAKER: - I don't know.
[35:30] SPEAKER: The point I'm making though is, I mean,
[35:31] SPEAKER: whether it does or not, like look at,
[35:34] SPEAKER: look at how many like pretty significant new technologies
[35:36] SPEAKER: have come online in games performance
[35:38] SPEAKER: since these current consoles shipped.
[35:42] SPEAKER: So it seems, it seems pretty promising for the next gen.
[35:45] SPEAKER: I think that a lot of this stuff can make its way in there.
[35:48] SPEAKER: - Like the, this is the first one,
[35:51] SPEAKER: this is the first new GPU architecture AMD's released
[35:55] SPEAKER: since the last consoles came out
[35:57] SPEAKER: that feels like an actual upgrade
[35:58] SPEAKER: rather than just an incremental upgrade.
[36:01] SPEAKER: And I think like my assumption is
[36:06] SPEAKER: if they think the Xbox is locked on paper,
[36:10] SPEAKER: that means they have an APU picked out.
[36:12] SPEAKER: You know, they've worked with AMD to design an APU
[36:16] SPEAKER: and we're into the process.
[36:18] SPEAKER: 'Cause it's usually a five-year loop on the,
[36:20] SPEAKER: from the initial design phase to like tape out to shipping.
[36:25] SPEAKER: So yeah, I don't know.
[36:27] SPEAKER: It's interesting.
[36:28] SPEAKER: It's, I mean, if this is the basis of the next gen consoles,
[36:33] SPEAKER: that's fantastic, right?
[36:35] SPEAKER: I mean, it may be that this is the basis
[36:37] SPEAKER: and it's thicker pipelines
[36:39] SPEAKER: or more memory bandwidth or whatever.
[36:41] SPEAKER: - Yeah, there are only two weeks.
[36:42] SPEAKER: - Yeah, typically the consoles both have used
[36:44] SPEAKER: unified memory with the GPU and CPU,
[36:46] SPEAKER: which gives them a lot of interesting efficiencies
[36:48] SPEAKER: that don't exist across the PCI express bus and the PC.
[36:51] SPEAKER: - Yeah, they've been doing that since the 360,
[36:53] SPEAKER: but then also like the current consoles,
[36:55] SPEAKER: like the Zen 2 cores have way less cache
[36:57] SPEAKER: than the desktop parts.
[36:58] SPEAKER: So like there's always trade-offs back and forth anyway.
[37:01] SPEAKER: - On an interesting note,
[37:03] SPEAKER: Adam and I did a live stream over at PC World
[37:06] SPEAKER: when these, with the embargo lifted for these cards.
[37:09] SPEAKER: And one of the things that we tested
[37:11] SPEAKER: that I hadn't actually seen anywhere
[37:12] SPEAKER: as we tested kind of casually,
[37:15] SPEAKER: what Cyberpunk perf, how it was impacted
[37:19] SPEAKER: by slower PCI express.
[37:21] SPEAKER: 'Cause somebody asked if they had a PCIe three
[37:23] SPEAKER: or PCIe four system, how would one of these cards do?
[37:28] SPEAKER: So we flipped it off.
[37:29] SPEAKER: We flipped it down from five to four to three to one.
[37:32] SPEAKER: And like, yeah, it was old.
[37:35] SPEAKER: - That's fun.
[37:37] SPEAKER: - And the perf difference was negligible.
[37:40] SPEAKER: - Really?
[37:40] SPEAKER: - Yeah, it was like 1.2 frames a second at most.
[37:44] SPEAKER: - For which versions of the bus?
[37:49] SPEAKER: - To go from five to one,
[37:50] SPEAKER: it was like 1.2 frames per second total.
[37:52] SPEAKER: - Total on one?
[37:53] SPEAKER: - Yeah, I don't think most games are optimized
[37:55] SPEAKER: to not need to send anything.
[37:57] SPEAKER: Like this is why the video cards have so much RAM, right?
[37:59] SPEAKER: - Yes, fair.
[38:00] SPEAKER: - Like your load times may be better
[38:02] SPEAKER: if you have faster PCI express.
[38:03] SPEAKER: - Very fair.
[38:04] SPEAKER: - But your in-game frame rate was pretty negligibly hit.
[38:08] SPEAKER: We also turned off resize bar
[38:09] SPEAKER: and had a similar impact on Cyberpunk at least.
[38:11] SPEAKER: Now that may be more dependent on different games
[38:14] SPEAKER: and different drivers.
[38:15] SPEAKER: But, so we didn't test on old hardware in this case
[38:18] SPEAKER: 'cause it's a pain in the ass.
[38:20] SPEAKER: - I mean, I guess it makes sense.
[38:21] SPEAKER: Like whatever data needs to go back and forth
[38:23] SPEAKER: between the CPU and the GPU is like relatively small.
[38:26] SPEAKER: - Yeah.
[38:27] SPEAKER: - It's not like bandwidth between the card
[38:30] SPEAKER: and the processor should not be a limiting factor
[38:32] SPEAKER: for, you know, ray tracing setup and whatever.
[38:36] SPEAKER: - You optimize it so that it's not,
[38:38] SPEAKER: because like in the case of like Indiana Jones,
[38:40] SPEAKER: when you fill up video card RAM on that game,
[38:43] SPEAKER: it goes from 40 or 50 frames a second
[38:45] SPEAKER: to three frames a second.
[38:47] SPEAKER: Really, really reliably.
[38:48] SPEAKER: So you're not gonna run Indiana Jones on Supreme
[38:53] SPEAKER: with a 16 gig card.
[38:55] SPEAKER: - Is that the name of their top tier graphics?
[38:57] SPEAKER: - They call it Supreme, yeah.
[38:59] SPEAKER: - That's great.
[39:00] SPEAKER: - The other one I saw the other day
[39:02] SPEAKER: that was really good was somebody has Very Ultra.
[39:03] SPEAKER: They have Ultra and then Very Ultra.
[39:05] SPEAKER: And I was like, that's Very Ultra is fucking fantastic.
[39:07] SPEAKER: I love that.
[39:08] SPEAKER: - That's really funny.
[39:09] SPEAKER: - Yeah.
[39:10] SPEAKER: So, okay.
[39:11] SPEAKER: So Intel also rolled out Battle Maze.
[39:12] SPEAKER: We talked about this a little bit earlier this year.
[39:15] SPEAKER: There's been more testing.
[39:19] SPEAKER: People have been doing ongoing testing with them.
[39:21] SPEAKER: The drivers are generally,
[39:23] SPEAKER: like the big question after the first arc cards,
[39:26] SPEAKER: the A580 and A480 and A470, I think,
[39:32] SPEAKER: where the drivers were pretty rough for a while.
[39:34] SPEAKER: And it seems like Intel's worked most of that out.
[39:40] SPEAKER: There was also some brouhaha
[39:44] SPEAKER: about how those cards worked on older boards
[39:47] SPEAKER: that don't support resizable bar or have slower CPU's
[39:50] SPEAKER: 'cause a classic Intel move with their hardware
[39:53] SPEAKER: is to use the CPU for things that typically aren't used for
[39:56] SPEAKER: in that device.
[40:01] SPEAKER: That is still a little bit less clear.
[40:03] SPEAKER: So I would love, it's funny,
[40:07] SPEAKER: I kinda wanna dig out my 9900K machine
[40:10] SPEAKER: and do some perf testing
[40:12] SPEAKER: 'cause if you have a 9900K, probably still fine
[40:17] SPEAKER: from a CPU standpoint for a lot of people,
[40:21] SPEAKER: but you're not gonna, if you put a 1590 in it,
[40:24] SPEAKER: you're not gonna see the lift that you would
[40:25] SPEAKER: if you put it in a 9800X3D or something like that.
[40:28] SPEAKER: - Sure.
[40:30] SPEAKER: - And then it does ray trace.
[40:31] SPEAKER: It has hardware accelerated ray tracing.
[40:34] SPEAKER: It also has a new version of XeSS,
[40:36] SPEAKER: their super sampling and frame gen protocols.
[40:40] SPEAKER: It's all AI accelerated now.
[40:42] SPEAKER: It uses the machine, the tensor core equivalents,
[40:46] SPEAKER: same as AMD does.
[40:48] SPEAKER: And it's worth mentioning, FSR4 and XeSS2, I think,
[40:52] SPEAKER: neither of those work,
[40:54] SPEAKER: but while XeSS1 and FSR3, 2, and 1 worked
[40:57] SPEAKER: on non-AMD hardware and non-Intel hardware,
[41:00] SPEAKER: the new versions are locked to the hardware
[41:02] SPEAKER: that ships with them.
[41:05] SPEAKER: Everybody's doing their own hardware
[41:06] SPEAKER: and machine learning stuff now.
[41:09] SPEAKER: One other question about Battlemage,
[41:11] SPEAKER: back when these, the newest ones,
[41:13] SPEAKER: the B580 and 7, or I guess 70s newer.
[41:16] SPEAKER: Anyway, this generation, when they came out,
[41:18] SPEAKER: one of the things I saw about driver quality
[41:20] SPEAKER: was that people said that older games
[41:21] SPEAKER: were struggling pretty well,
[41:23] SPEAKER: like DirectX 9 era stuff, particularly.
[41:27] SPEAKER: Was not great.
[41:28] SPEAKER: Can you speak to how older games are doing now?
[41:30] SPEAKER: - So I didn't test any DX9 stuff,
[41:34] SPEAKER: like DX9 games not in the normal
[41:37] SPEAKER: benchmark rotation these days.
[41:39] SPEAKER: They had problems with DX11 performance
[41:41] SPEAKER: on the Alchemist, the A480 and A470 cards.
[41:49] SPEAKER: The, so I don't know what the DX9 situation is,
[41:54] SPEAKER: but DX11 was much better on the Battlemage cards
[41:57] SPEAKER: than it was on Alchemist.
[41:58] SPEAKER: And also, by the end of the Alchemist,
[42:01] SPEAKER: by the end of life on, not end of life,
[42:03] SPEAKER: but by the end of the, you know,
[42:05] SPEAKER: the drivers had improved on Alchemist.
[42:07] SPEAKER: I actually think they're using that DXBK wrapper
[42:10] SPEAKER: to wrap DX11 games to Vulkan.
[42:13] SPEAKER: - Interesting. - 'Cause they're like,
[42:15] SPEAKER: you would, look, I'm gonna tell you a secret, Brad.
[42:18] SPEAKER: There's a lot of games that run on DX11
[42:21] SPEAKER: that have performance problems,
[42:22] SPEAKER: and they're just like, hey man,
[42:23] SPEAKER: what if we just put this Vulkan wrapper in,
[42:25] SPEAKER: and then a lot of your weird bottlenecks
[42:27] SPEAKER: just kind of fix themselves.
[42:28] SPEAKER: - Seems to be working well
[42:29] SPEAKER: for a lot of situations these days.
[42:31] SPEAKER: - Yeah, so that's what's going on with Intel.
[42:34] SPEAKER: Those cards are 250 bucks.
[42:35] SPEAKER: So if you're sitting on a 1080 or a 10 series card
[42:39] SPEAKER: or 20 series, 2060 or something,
[42:41] SPEAKER: and are looking for an upgrade,
[42:43] SPEAKER: assuming you don't get hit by the low-powered CPU problem,
[42:47] SPEAKER: which, again, I read a bunch of reviews of this,
[42:51] SPEAKER: and there's no real consensus.
[42:52] SPEAKER: Some people blame it on resized bars,
[42:54] SPEAKER: some people blame it on not-of-cores,
[42:56] SPEAKER: some people blame it on a lack of certain instructions.
[42:59] SPEAKER: There's no, I don't see a clear consensus.
[43:01] SPEAKER: So Hardware Unboxed has done some stuff on that.
[43:05] SPEAKER: I feel like First Level Text
[43:08] SPEAKER: did some good stuff on that as well.
[43:10] SPEAKER: So yeah, I don't know.
[43:11] SPEAKER: Yeah, it's a weird recommendation.
[43:14] SPEAKER: - I mean, I've said this before.
[43:15] SPEAKER: I mean, it's great to see, you know,
[43:17] SPEAKER: well, right now everybody's got their own market segment,
[43:19] SPEAKER: which is less great than if everybody was competing
[43:21] SPEAKER: against each other head to head.
[43:23] SPEAKER: You know, like Intel's in the low end,
[43:25] SPEAKER: AMD's in the mid range,
[43:26] SPEAKER: and Nvidia still owns the high end.
[43:28] SPEAKER: Like it obviously would be better
[43:30] SPEAKER: if everybody had high end and low end and et cetera, et cetera.
[43:33] SPEAKER: But still, much like with AMD finally getting competitive
[43:37] SPEAKER: again on CPUs a few years ago.
[43:40] SPEAKER: - Yeah.
[43:41] SPEAKER: - Like it's just exciting to see some actual competition
[43:43] SPEAKER: taking place again.
[43:44] SPEAKER: And really kind of calls into question
[43:47] SPEAKER: what the future of Nvidia's desktop graphics efforts are.
[43:50] SPEAKER: I mean, let's be real here.
[43:52] SPEAKER: Nvidia probably could not give less of,
[43:53] SPEAKER: like Jensen Huang could not give less of a shit.
[43:55] SPEAKER: - Something like 12 times as much revenue from AI
[43:58] SPEAKER: as from desktop graphics.
[44:00] SPEAKER: - This is not me saying like,
[44:00] SPEAKER: "Oh, Nvidia's are in real trouble here."
[44:02] SPEAKER: But like the state of their desktop graphics offering
[44:05] SPEAKER: like does have some questions swirling around it
[44:08] SPEAKER: between what's going on with these competing cards
[44:10] SPEAKER: and also some of the problems here
[44:12] SPEAKER: that we are about to discuss.
[44:13] SPEAKER: - Yeah, so the Nvidia stuff, there's a lot of smoke.
[44:17] SPEAKER: It's hard to know what's actual smoke and what's just,
[44:21] SPEAKER: well, what's literal smoke, what's figurative smoke,
[44:24] SPEAKER: and what's just somebody blowing smoke, I guess.
[44:28] SPEAKER: - The 12 volt, two by six thing,
[44:30] SPEAKER: I think we talked about this a little bit.
[44:32] SPEAKER: There's, once again, Nvidia has this new high power,
[44:37] SPEAKER: more manageable cable for supplemental power to video cards.
[44:42] SPEAKER: It's a 600 watt cable.
[44:43] SPEAKER: It's part of PCI Express now.
[44:45] SPEAKER: It's part of the PCI Express, PCI 3.0.
[44:48] SPEAKER: - Yeah, we did discuss this recently
[44:49] SPEAKER: 'cause I remember being shocked at the revelation
[44:52] SPEAKER: that this was an Nvidia designed connector
[44:54] SPEAKER: that got kind of backfilled into a spec.
[44:56] SPEAKER: - Yeah, but I mean, that's how PCI Express happened too,
[44:59] SPEAKER: for what it's worth.
[45:00] SPEAKER: - Yeah, I mean, anyway,
[45:01] SPEAKER: we don't have to belabor this point too much,
[45:02] SPEAKER: but there are at least isolated instances
[45:05] SPEAKER: of this connector melting again.
[45:08] SPEAKER: - So there were a handful of people that came out early.
[45:10] SPEAKER: I haven't seen a whole lot more.
[45:12] SPEAKER: So it seems like it's maybe a combination
[45:15] SPEAKER: of people who are using the connector
[45:17] SPEAKER: beyond its rated wear life,
[45:19] SPEAKER: due to the number of rated duty cycles,
[45:23] SPEAKER: weird aftermarket cables, all that stuff.
[45:26] SPEAKER: - I am, it's definitely not a problem
[45:29] SPEAKER: for the cards that aren't the 1590.
[45:31] SPEAKER: The 1590 is just like it's a 575 watt card
[45:35] SPEAKER: and it's a 600 watt cable.
[45:37] SPEAKER: So if you have any point of failure
[45:41] SPEAKER: when you're running on a 1590, it's a little scary.
[45:43] SPEAKER: - Yeah.
[45:45] SPEAKER: - And the kind of TLDR on what happens
[45:50] SPEAKER: is if one or more of the cables that carry the current
[45:55] SPEAKER: on the 12 volt two by six are not connected properly,
[46:00] SPEAKER: the cards just try to suck all the power that they need
[46:03] SPEAKER: through one or two of the cables instead of three.
[46:06] SPEAKER: And that's not good.
[46:10] SPEAKER: Or six, I guess, instead of six.
[46:11] SPEAKER: Yeah, it seems bad.
[46:12] SPEAKER: - Seems like a questionable design.
[46:15] SPEAKER: - They also have had this ROP problem.
[46:17] SPEAKER: - Yeah, like that seems more damning
[46:19] SPEAKER: than the power connector stuff
[46:20] SPEAKER: because how was this not caught?
[46:21] SPEAKER: Like, come on.
[46:23] SPEAKER: - Yeah, the ROP thing is, we talked about this.
[46:26] SPEAKER: I feel like I'm doing so many podcasts
[46:28] SPEAKER: where I talk about this stuff now,
[46:29] SPEAKER: it's hard for me to keep track
[46:29] SPEAKER: of what I've talked about where.
[46:31] SPEAKER: - Fully identify with that.
[46:32] SPEAKER: I think we talked about this briefly
[46:34] SPEAKER: on the patron episode last week, but.
[46:37] SPEAKER: - Yeah.
[46:37] SPEAKER: - So mentioning here, if we are evaluating
[46:39] SPEAKER: the kind of future of NVIDIA's graphics hardware,
[46:43] SPEAKER: like this is, some of these cards shipped
[46:46] SPEAKER: with a number of ROPs, raster operation pipelines disabled.
[46:51] SPEAKER: - Yeah, so the theory is that this is just a matter
[46:54] SPEAKER: of binning, having some unintended consequences.
[46:58] SPEAKER: Binning is when they tested a card
[47:00] SPEAKER: and they over-spec all of these cards now, right?
[47:04] SPEAKER: So they build them with more graphics pipelines
[47:05] SPEAKER: than they intend to ship with them.
[47:07] SPEAKER: And then they just turn off the ones
[47:08] SPEAKER: that perform at least well
[47:10] SPEAKER: when they're doing the testing on them.
[47:13] SPEAKER: - Right, the problem is when you sell a card at one spec
[47:17] SPEAKER: and then some subset of the cards
[47:18] SPEAKER: that you sell under that label are actually below that spec.
[47:22] SPEAKER: - Not saying they're not wrong, they didn't fuck up.
[47:26] SPEAKER: What I'm saying is the mistake is
[47:28] SPEAKER: that when they disqualified certain parts of the chip
[47:32] SPEAKER: that were adjacent to each other,
[47:33] SPEAKER: it disabled entire pipeline, raster operation pipelines,
[47:37] SPEAKER: that's what the ROP stands for,
[47:40] SPEAKER: that were not being used then
[47:41] SPEAKER: because all of the downstream units
[47:44] SPEAKER: in that ROP were not being used anymore.
[47:48] SPEAKER: - Yeah.
[47:49] SPEAKER: - The performance impact was pretty negligible.
[47:51] SPEAKER: It seems like I think they said half a percent
[47:53] SPEAKER: of cards are probably affected,
[47:55] SPEAKER: but it's all the five series cards and it's embarrassing.
[47:58] SPEAKER: It's a mistake they shouldn't have made.
[47:59] SPEAKER: - Yeah, and reports are coming out in the last day or two
[48:02] SPEAKER: that it looks like Nvidia has denied them
[48:04] SPEAKER: that apparently this may affect laptops
[48:05] SPEAKER: with mobile 50 parts in them as well.
[48:08] SPEAKER: - I don't know.
[48:09] SPEAKER: It's easy to tell, you just load up GPU-Z
[48:11] SPEAKER: and it tells you how many ROPs you have.
[48:12] SPEAKER: And if it's not the number that's on their website,
[48:14] SPEAKER: then you call them and they send you a new card.
[48:16] SPEAKER: The annoying thing is you have to go
[48:18] SPEAKER: to the manufacturers if you have an AIB,
[48:20] SPEAKER: which means you may be waiting a little bit
[48:22] SPEAKER: to get the replacement card
[48:23] SPEAKER: because the supplies are still really tight
[48:25] SPEAKER: on especially the high-end parts.
[48:26] SPEAKER: - Yeah, I guess maybe to focus what I was saying earlier,
[48:30] SPEAKER: like the questions this raises
[48:31] SPEAKER: around Nvidia's desktop graphics are like,
[48:34] SPEAKER: where are their priorities right now?
[48:35] SPEAKER: Like, I mean, that's a pretty rhetorical question.
[48:37] SPEAKER: I think we know where their priorities are,
[48:39] SPEAKER: but it's like, you know, if this was really a focus,
[48:43] SPEAKER: if this division or this business was a focus for them,
[48:48] SPEAKER: you would think the QA effort would be such
[48:50] SPEAKER: that something like this would have been caught?
[48:53] SPEAKER: - I think that this realistically,
[48:56] SPEAKER: if I'm ranking which of these problems are worse
[48:58] SPEAKER: between the 12 volt, two by six and the ROP thing,
[49:01] SPEAKER: the ROP thing is mostly a paper problem
[49:04] SPEAKER: that the vast majority of people
[49:05] SPEAKER: aren't going to realize is a problem
[49:07] SPEAKER: unless they load up GPU-Z.
[49:09] SPEAKER: - No, but the second it's discovered
[49:10] SPEAKER: and you find out that you were, let's be real,
[49:13] SPEAKER: this could affect your $2,800, 50, 90.
[49:16] SPEAKER: - Oh.
[49:17] SPEAKER: - Like that's not a good feeling once you know about it.
[49:19] SPEAKER: - No, 100%, but I guess what I'm saying
[49:22] SPEAKER: is it's an invisible failure,
[49:24] SPEAKER: whereas melting the cable that the power goes
[49:27] SPEAKER: into your video card from is bad.
[49:31] SPEAKER: And when you, there've been every electronic,
[49:34] SPEAKER: every electrical engineer in the world apparently
[49:36] SPEAKER: has tapped in with, hey, this is an easy problem
[49:39] SPEAKER: that they could have fixed
[49:40] SPEAKER: if they added a couple of circuits to the board.
[49:42] SPEAKER: - That's the bigger point I'm trying to make here
[49:44] SPEAKER: is that just these are things for one of,
[49:48] SPEAKER: let's be real here,
[49:49] SPEAKER: one of the most valuable companies in the world.
[49:51] SPEAKER: This doesn't seem great.
[49:53] SPEAKER: - And I wonder how much of this,
[49:55] SPEAKER: I mean, we know brain drain is happening at Nvidia
[49:59] SPEAKER: from people who we know who've worked there
[50:01] SPEAKER: for a really long time.
[50:03] SPEAKER: The people who had low stock prices
[50:07] SPEAKER: and sold when the stock was at like $900 or whatever
[50:11] SPEAKER: don't work there anymore.
[50:12] SPEAKER: And I'm assuming that that wasn't just
[50:14] SPEAKER: in the us facing parts of the business,
[50:16] SPEAKER: but in the people who did the power
[50:20] SPEAKER: and the people who did the ROP testing
[50:22] SPEAKER: and all of the other things.
[50:24] SPEAKER: - That's a real interesting problem
[50:26] SPEAKER: to become a victim of your own success
[50:27] SPEAKER: as a large corporation like that.
[50:29] SPEAKER: - I mean, I'm not weeping for Nvidia,
[50:32] SPEAKER: but yeah, I wonder if they're gonna see a decline
[50:35] SPEAKER: as a result of brain drain at the high end.
[50:39] SPEAKER: 'Cause once you have 20 or $30 million worth of stock
[50:43] SPEAKER: and you're 50 years old,
[50:47] SPEAKER: what are they gonna give you that's worth coming back?
[50:50] SPEAKER: - Unless you just love the job that much.
[50:54] SPEAKER: I don't think I would still be there.
[50:55] SPEAKER: - I mean, I know a lot of people there
[50:57] SPEAKER: who are true believers and who are gonna work
[51:00] SPEAKER: until they're not able to work anymore, right?
[51:02] SPEAKER: Because they think that they're building artificial
[51:05] SPEAKER: intelligence, like actual artificial intelligence,
[51:07] SPEAKER: not Markov chains.
[51:12] SPEAKER: But also a lot of people don't and just wanna spend time
[51:14] SPEAKER: with their wives and buy a house on the lake, right?
[51:17] SPEAKER: So anyway, that's what's up with...
[51:21] SPEAKER: Oh, and then the other thing is the paper launch.
[51:23] SPEAKER: Like they haven't...
[51:26] SPEAKER: It's hard to know whether it's a paper launch
[51:28] SPEAKER: or whether it's just supply is so outstripped by demand.
[51:33] SPEAKER: 'Cause the demand, especially on the high end,
[51:35] SPEAKER: is still really, really high.
[51:36] SPEAKER: Like cards are dropping with $800 markups,
[51:39] SPEAKER: like stock normal ass video cards.
[51:42] SPEAKER: - That's rough.
[51:43] SPEAKER: - And they're gone in like three minutes.
[51:44] SPEAKER: So Central Computer, our local screwdriver shop
[51:48] SPEAKER: here in the Bay Area, had a...
[51:53] SPEAKER: Yo, we just don't have these.
[51:56] SPEAKER: I've never seen it before on their site.
[51:59] SPEAKER: When you search for 5090s...
[52:00] SPEAKER: Okay, so they actually do have 5090s listed on the site.
[52:05] SPEAKER: Now, the only one that has a price
[52:08] SPEAKER: is the MSI G5090 32 GTC Gaming Trio OC Edition,
[52:16] SPEAKER: which has a price of $2639.
[52:20] SPEAKER: - That's quite a bit of money.
[52:21] SPEAKER: - Yeah, the water-cooled Supreme, the other MS...
[52:25] SPEAKER: It's all MSI boards.
[52:26] SPEAKER: There's one PNY board on here too.
[52:28] SPEAKER: But for a while, they just had a...
[52:30] SPEAKER: When you went to the 5090 page, it just said,
[52:32] SPEAKER: "Hey, we don't have these in bundles, in systems,
[52:35] SPEAKER: or in standalone boards, so please don't call."
[52:38] SPEAKER: Which I've never seen before.
[52:39] SPEAKER: - That's funny for a retailer.
[52:41] SPEAKER: Shout out to Central.
[52:42] SPEAKER: - Yeah.
[52:43] SPEAKER: - Shout out to computer shops.
[52:44] SPEAKER: I know we've said this before,
[52:45] SPEAKER: but there was an item I have been trying to get my hands on.
[52:49] SPEAKER: It's just a set of key caps for this keyboard.
[52:50] SPEAKER: It's nothing crazy, but they have been out of stock
[52:53] SPEAKER: in the normal vendor locations for ages.
[52:56] SPEAKER: And I was like, man,
[52:57] SPEAKER: I wish I could get some of those key caps,
[52:58] SPEAKER: but I just can't find them anywhere.
[53:00] SPEAKER: What do you know?
[53:01] SPEAKER: Every Central in the area around here
[53:02] SPEAKER: has like two or three of them in stock.
[53:04] SPEAKER: So I'm just gonna go and buy a set at a store in person.
[53:08] SPEAKER: What a concept.
[53:10] SPEAKER: - I love Central so much.
[53:12] SPEAKER: And the customer service is kind of bad,
[53:16] SPEAKER: but it's applied equally to everybody who hits the door.
[53:19] SPEAKER: So I'm okay with that.
[53:21] SPEAKER: - I've had a decent experience there.
[53:23] SPEAKER: - Honestly, the only time I have a problem
[53:24] SPEAKER: is when I need them to unlock something from one
[53:26] SPEAKER: of the cabinets and there's never anybody around
[53:28] SPEAKER: when that happens.
[53:29] SPEAKER: - That's fair.
[53:30] SPEAKER: I've found most of the people there I talk to
[53:31] SPEAKER: to be pretty knowledgeable though.
[53:33] SPEAKER: It seems like they're actually into the product.
[53:35] SPEAKER: - Yeah, like when you ask them,
[53:38] SPEAKER: so when I ask them for something specific,
[53:42] SPEAKER: they know enough to know that it's something specific
[53:44] SPEAKER: and they don't try to push me on to whatever else
[53:46] SPEAKER: they're looking for, like it's really nice.
[53:50] SPEAKER: It's nice to have that kind of store here.
[53:52] SPEAKER: We don't have micro centers yet where we are.
[53:54] SPEAKER: Although when that one opens in the South Bay,
[53:56] SPEAKER: we should go.
[53:57] SPEAKER: - Yeah, I'm totally, I'm down, I'm down.
[54:00] SPEAKER: So yeah, so the page, the 50 series page
[54:05] SPEAKER: has a bunch of updates.
[54:07] SPEAKER: The 5090 says we still do not have any 5090 GPUs
[54:10] SPEAKER: for sale in systems or standalone.
[54:12] SPEAKER: ETA is not yet clear.
[54:14] SPEAKER: We will announce as soon as we receive updates.
[54:18] SPEAKER: Excitement and demand for this latest generation
[54:20] SPEAKER: of Nvidia GeForce GPUs is as high as ever.
[54:22] SPEAKER: We wish we had them available for you sooner
[54:23] SPEAKER: and in greater quantity.
[54:25] SPEAKER: As of now, supply is still very limited.
[54:27] SPEAKER: We will always share the latest updates with you
[54:28] SPEAKER: as we confirm them and that's it.
[54:33] SPEAKER: They've done five updates since the January 30th launch
[54:36] SPEAKER: of the 5090s.
[54:37] SPEAKER: - That's quite a bit of communication.
[54:39] SPEAKER: - I mean, they have banners at the top of the page.
[54:41] SPEAKER: There's one that's the RTX 50 series alert sign up,
[54:45] SPEAKER: AMD RX 9000 alert sign up and Ryzen 9 X3D alert sign up.
[54:50] SPEAKER: So good for them.
[54:51] SPEAKER: - I wonder what the state of 40 series stock is
[54:54] SPEAKER: in the channel these days.
[54:55] SPEAKER: Are they just gone?
[54:56] SPEAKER: Is that why it just completely dried up?
[54:58] SPEAKER: That's a bummer.
[54:58] SPEAKER: - Nothing.
[55:00] SPEAKER: So that's the other side of this, right?
[55:01] SPEAKER: Is if you don't wanna get this five series Nvidia card
[55:04] SPEAKER: or a nine series Ryzen or a Battlemage card,
[55:07] SPEAKER: you can just buy the last generation, right?
[55:09] SPEAKER: No, get fucked.
[55:10] SPEAKER: They don't exist anymore.
[55:11] SPEAKER: - Sucks.
[55:12] SPEAKER: - Well, so the nice thing is for GPUs aftermarket stuff
[55:18] SPEAKER: has been off the table during the two and three series,
[55:22] SPEAKER: especially generations because of the Ethereum mining
[55:25] SPEAKER: and the number of GPUs that got bought
[55:27] SPEAKER: and then torched doing that.
[55:29] SPEAKER: I think that the 40 series and the 9000 series,
[55:33] SPEAKER: or sorry, 7000 series from AMD are probably safe
[55:38] SPEAKER: 'cause they didn't exist until the Ethereum stuff
[55:41] SPEAKER: was already done.
[55:42] SPEAKER: So while you might buy something from an AI farm,
[55:46] SPEAKER: it's not quite as bad a life for a GPU
[55:49] SPEAKER: as the Ethereum mining was.
[55:53] SPEAKER: So if you wanna buy a used 4090,
[55:58] SPEAKER: it doesn't feel great, but I think it's not a terrible,
[56:02] SPEAKER: especially if you're buying from a normal person
[56:03] SPEAKER: and not somebody who's doing AI stuff.
[56:06] SPEAKER: - Yeah, the only 40 cards that Central has in stock
[56:09] SPEAKER: at this point are from 4060s.
[56:11] SPEAKER: - They'll be around for a long time.
[56:12] SPEAKER: - Yeah.
[56:15] SPEAKER: - You wanna talk about CPUs a little bit?
[56:16] SPEAKER: Oh, wait, wait, we forgot one last Nvidia scene drama.
[56:23] SPEAKER: They killed 32-bit CUDA support for the five series.
[56:26] SPEAKER: - I saw that, that's fresh on the heels of,
[56:28] SPEAKER: or I mean, technically it happened in the same product
[56:30] SPEAKER: as the death of 32-bit PhysX support.
[56:34] SPEAKER: - Well, it's not just 32-bit PhysX support,
[56:36] SPEAKER: it's hardware accelerated PhysX support.
[56:39] SPEAKER: So that means that the,
[56:41] SPEAKER: I think there were several dozen in like 2008
[56:44] SPEAKER: when a Jia was selling PhysX acceleration cards.
[56:49] SPEAKER: - Oh, this was after, wasn't it?
[56:50] SPEAKER: I thought that, I thought a Jia got bought
[56:53] SPEAKER: and discontinued these separate cards
[56:56] SPEAKER: some years earlier than that.
[56:57] SPEAKER: - So they sold a separate card, they got bought,
[57:00] SPEAKER: but the separate card and the GPU acceleration
[57:03] SPEAKER: were the same thing.
[57:04] SPEAKER: So, okay, history lesson.
[57:07] SPEAKER: A Jia is this company that they wanted to get,
[57:11] SPEAKER: they saw the success of Nvidia's branding of a video card
[57:15] SPEAKER: processor as a GPU.
[57:17] SPEAKER: And they were like, hey man, we can do our own PU,
[57:20] SPEAKER: we're gonna make a PhysX processing unit.
[57:22] SPEAKER: - That's right.
[57:23] SPEAKER: - And so then they did, and they released with it
[57:27] SPEAKER: PhysX middleware that was free for everyone to use.
[57:29] SPEAKER: You didn't have to pay them per unit sold
[57:32] SPEAKER: or part of your revenue.
[57:34] SPEAKER: - Classic thing, they were in the hardware business.
[57:36] SPEAKER: - Yeah, and then they weren't in the hardware business
[57:39] SPEAKER: anymore, really, 'cause Nvidia bought them
[57:41] SPEAKER: for their PhysX library.
[57:44] SPEAKER: But there were games that came out that used the PPU,
[57:47] SPEAKER: or alternately, I think around the GeForce 8800,
[57:51] SPEAKER: 8000 series, the first, hold on, what are we on now?
[57:55] SPEAKER: The 5000, it's like two laps ago maybe, 2008?
[58:00] SPEAKER: - 2008 is when they bought a Jia,
[58:01] SPEAKER: so the cards that came out shortly after that.
[58:04] SPEAKER: - Yeah, so that's, at that point you could say,
[58:06] SPEAKER: hey, I want to use my video card to accelerate PhysX,
[58:11] SPEAKER: or you could just put a second video card in your computer,
[58:13] SPEAKER: which was great for Nvidia, they loved that.
[58:15] SPEAKER: So there were games that came out that utilized
[58:19] SPEAKER: the hardware physics acceleration.
[58:22] SPEAKER: Batman Arkham Asylum, Mirror's Edge are two of the big ones,
[58:25] SPEAKER: but like Auto Assault was one of them,
[58:27] SPEAKER: Four Lens 2 was one of them, just two.
[58:32] SPEAKER: - Cryostasis, remember Dave Snyder's game of 2008?
[58:35] SPEAKER: - Cryostasis was one of them, yeah.
[58:37] SPEAKER: - Hadn't had, actually, I've got a list here,
[58:39] SPEAKER: that's a decent number of games, it looks like.
[58:42] SPEAKER: - It is, there's a bunch of games that you can no longer
[58:45] SPEAKER: play, there's a bunch of MMOs from that time period
[58:47] SPEAKER: that just don't exist anymore.
[58:50] SPEAKER: City of Villains was one of them, right?
[58:51] SPEAKER: - Yeah, yeah, we should stress real quick here,
[58:54] SPEAKER: we're not talking about your average CPU-based,
[58:56] SPEAKER: or sorry, Havok physics that you've been seeing in games
[58:59] SPEAKER: for 20 years now, it's pretty serious.
[59:03] SPEAKER: Pull up some YouTube videos of some of the PhysX
[59:05] SPEAKER: effects and the games we're talking about here,
[59:07] SPEAKER: like there's some like pretty outlandish stuff
[59:10] SPEAKER: that you don't see in current games.
[59:12] SPEAKER: - It was mostly cloth physics or extra garbage in the level
[59:15] SPEAKER: were the two main things that seemed to have,
[59:18] SPEAKER: I reviewed a bunch of these cards when they came out,
[59:20] SPEAKER: BFG made one, and also it's worth mentioning
[59:26] SPEAKER: that we're not, this doesn't have any impact at all
[59:29] SPEAKER: on anybody that uses the software PhysX API,
[59:33] SPEAKER: that an enormous number of Unreal 4
[59:35] SPEAKER: and 3 games shipped with.
[59:37] SPEAKER: - Yeah, this is like specifically games
[59:38] SPEAKER: that we're using this version of the hardware-based
[59:41] SPEAKER: acceleration from around this era,
[59:43] SPEAKER: so this is more of a game preservation thing than anything.
[59:46] SPEAKER: - Yeah, and those games will still run,
[59:47] SPEAKER: they all have a toggle that lets you turn off
[59:49] SPEAKER: PhysX hardware acceleration.
[59:51] SPEAKER: Also, you can run, if you have a lot of cores in your CPU,
[59:55] SPEAKER: you can just run PhysX hardware acceleration on your CPU now.
[59:58] SPEAKER: I ran, we tested this during the livestream the other day,
[1:00:02] SPEAKER: and I played Batman Arkham Asylum
[1:00:04] SPEAKER: with this stuff turned all the way up on a 9800X3D,
[1:00:08] SPEAKER: and it was like 60 frames a second, pretty solid.
[1:00:11] SPEAKER: - Okay, well, did you hit any serious physics calculations
[1:00:14] SPEAKER: that you could tell, though?
[1:00:15] SPEAKER: - I mean, Batman's cape is on every single shot of that game
[1:00:18] SPEAKER: so we did not, I did not see as much garbage laying around
[1:00:23] SPEAKER: as I remember seeing in those PhysX games.
[1:00:28] SPEAKER: But yeah, so the other thing that's worth considering
[1:00:32] SPEAKER: about this is if you really, really care about this,
[1:00:33] SPEAKER: you can put literally any old Nvidia card
[1:00:36] SPEAKER: into your machine as a second GPU, and it'll just work.
[1:00:40] SPEAKER: So anyway.
[1:00:42] SPEAKER: - Yeah, I mean, it's not impossible to still play
[1:00:45] SPEAKER: those games the way they were meant to be played.
[1:00:48] SPEAKER: - Yeah, so it's a preservation, like you said,
[1:00:52] SPEAKER: it's a preservation issue.
[1:00:53] SPEAKER: If I'm ranking the severity of the GeForce drama right now,
[1:00:57] SPEAKER: it's like 12 volt, two by six is number one,
[1:01:00] SPEAKER: ROPS is number two, price gouging/tariffs/price uncertainty
[1:01:06] SPEAKER: slash availability are number two, ROPS are number three,
[1:01:10] SPEAKER: and then 32-bit CUDA is like a distant 12th.
[1:01:13] SPEAKER: - Yeah, yeah.
[1:01:15] SPEAKER: - So anyway.
[1:01:16] SPEAKER: - But it's still kind of sad to see.
[1:01:18] SPEAKER: - It's a bummer, yeah.
[1:01:20] SPEAKER: I mean, look, I get them not wanting to support that stuff
[1:01:23] SPEAKER: forever and ever, but it would have been cool
[1:01:26] SPEAKER: to build a wrapper for 32-bit CUDA or something like that.
[1:01:30] SPEAKER: - Maybe that'll still come, I don't know.
[1:01:33] SPEAKER: But I mean, when the GPUs are getting physically
[1:01:36] SPEAKER: as big as they are on these current cards,
[1:01:38] SPEAKER: I guess I can see the need to eliminate things
[1:01:40] SPEAKER: from the die that aren't critical anymore.
[1:01:43] SPEAKER: - Well, and it's unclear if this is a need
[1:01:45] SPEAKER: to eliminate something from the die or just,
[1:01:46] SPEAKER: hey, we don't want to have to support this ancient shit
[1:01:49] SPEAKER: that nobody uses on our drivers anymore.
[1:01:50] SPEAKER: - Yeah, it could also just be that.
[1:01:53] SPEAKER: - You want to talk about CPUs a bit?
[1:01:55] SPEAKER: - Yeah, I don't think there's a ton to update on here
[1:01:57] SPEAKER: 'cause most of everything has been out for a while,
[1:01:59] SPEAKER: but what do you got?
[1:02:00] SPEAKER: - Yeah, we'll rise in 9950 X3Ds as evidenced
[1:02:04] SPEAKER: by the central page that says,
[1:02:06] SPEAKER: hey, do you want to sign up for notifications
[1:02:07] SPEAKER: about when these are going to be available
[1:02:09] SPEAKER: are probably coming soon.
[1:02:11] SPEAKER: - Okay.
[1:02:12] SPEAKER: Oh, has the date actually not been announced yet?
[1:02:18] SPEAKER: Has the date been announced yet?
[1:02:20] SPEAKER: - So anyway.
[1:02:21] SPEAKER: - Publicly announced, you can answer,
[1:02:22] SPEAKER: you can tell me if the date has been publicly confirmed
[1:02:25] SPEAKER: or not.
[1:02:25] SPEAKER: - I don't know, dude.
[1:02:26] SPEAKER: - Oh, you don't know.
[1:02:27] SPEAKER: Okay, I thought you were being coy
[1:02:29] SPEAKER: about something you did know.
[1:02:30] SPEAKER: - I do know something, but we got to cut this part out.
[1:02:33] SPEAKER: - Nope, nope, I just looked it up.
[1:02:35] SPEAKER: They have in fact been announced.
[1:02:36] SPEAKER: - Okay, what's March 12th?
[1:02:38] SPEAKER: So that's next--
[1:02:39] SPEAKER: - Pricing and date.
[1:02:41] SPEAKER: - It's next Wednesday.
[1:02:42] SPEAKER: - 9900 X3D, which I assume is still 12 cores.
[1:02:44] SPEAKER: I don't have it in front of me.
[1:02:45] SPEAKER: - 12 cores, yeah.
[1:02:46] SPEAKER: - Is 599, the 9950 X3D, which is 16 cores is 699.
[1:02:51] SPEAKER: And this is the hybrid, the dual CCD one
[1:02:55] SPEAKER: where one has the 3DV cache and a whole buttload L3 cache
[1:02:58] SPEAKER: and one has no 3DV cache that runs
[1:03:02] SPEAKER: at slightly higher speeds.
[1:03:03] SPEAKER: - Which I, you know, I still, I thought it was neat
[1:03:05] SPEAKER: to begin with when I had one of the previous gen,
[1:03:07] SPEAKER: but I don't know that I'm ready to jump back in.
[1:03:09] SPEAKER: - I think that the big question I have about this
[1:03:12] SPEAKER: is if the Windows Task Scheduler stuff
[1:03:15] SPEAKER: that they rolled out around the time
[1:03:17] SPEAKER: of the 9,000 series launch is actually going
[1:03:19] SPEAKER: to improve the problems that you and a lot of other people
[1:03:23] SPEAKER: had with the last gen of these.
[1:03:24] SPEAKER: - To be fair, I didn't have a lot of identifiable problems
[1:03:27] SPEAKER: that you could trace to the split CCD design.
[1:03:31] SPEAKER: - Yeah.
[1:03:31] SPEAKER: - I didn't get a lot of the stuttering
[1:03:33] SPEAKER: that was supposed to be the telltale sign
[1:03:37] SPEAKER: that that was a problem.
[1:03:37] SPEAKER: I did have it assigning games through the wrong cores.
[1:03:40] SPEAKER: Like I did see that happening when I would tab out
[1:03:42] SPEAKER: and look at, or have task manager up or process lasso
[1:03:46] SPEAKER: or whatever I was looking at at the time.
[1:03:48] SPEAKER: - Love process lasso, yeah.
[1:03:49] SPEAKER: - Like I would see game threads ending up
[1:03:51] SPEAKER: on the wrong cores occasionally.
[1:03:55] SPEAKER: - About what you want.
[1:03:56] SPEAKER: - But it never seemed to like manifest as a huge problem
[1:03:58] SPEAKER: in terms of stutters and stuff like that.
[1:04:00] SPEAKER: Anyway, that was the first version of that part.
[1:04:02] SPEAKER: Like that was the first time they had ever even tried that.
[1:04:04] SPEAKER: So here we are, God, almost two years later now.
[1:04:08] SPEAKER: - Yeah, ish.
[1:04:09] SPEAKER: - With all of the advancements
[1:04:12] SPEAKER: that have taken place since then.
[1:04:13] SPEAKER: So I'll be curious to see how this second stab
[1:04:15] SPEAKER: has turned out.
[1:04:16] SPEAKER: - Yeah, me too.
[1:04:18] SPEAKER: The other thing that's happened
[1:04:19] SPEAKER: is people have started doing new benchmark passes
[1:04:22] SPEAKER: on the CPU's that came out last fall.
[1:04:24] SPEAKER: - Oh.
[1:04:25] SPEAKER: - We talked about it at the time,
[1:04:26] SPEAKER: but both AMD and Intel
[1:04:29] SPEAKER: had technical back-end
[1:04:33] SPEAKER: shenanigans read difficulties.
[1:04:34] SPEAKER: It wasn't intentional.
[1:04:36] SPEAKER: It was difficulties where everybody involved
[1:04:39] SPEAKER: felt like the launch day benchmarks
[1:04:42] SPEAKER: that were posted on YouTube and across the web
[1:04:45] SPEAKER: probably didn't actually reflect
[1:04:46] SPEAKER: what those chips would be capable of doing in the end, right?
[1:04:50] SPEAKER: - I still see people occasionally
[1:04:52] SPEAKER: very snidely dropping Zen 5% on social media.
[1:04:56] SPEAKER: - Yeah.
[1:04:57] SPEAKER: So Wendell over at Level One Text
[1:05:02] SPEAKER: is a real good YouTube channel
[1:05:03] SPEAKER: for people who like real hardcore nerdery.
[1:05:06] SPEAKER: - Yes, he has a video up that I have not watched yet
[1:05:08] SPEAKER: about the 9070 XT on Linux specifically.
[1:05:12] SPEAKER: - Yeah.
[1:05:13] SPEAKER: - That's his beat.
[1:05:14] SPEAKER: - Yeah, he's always good for Pharaonic's benchmarks.
[1:05:17] SPEAKER: - Oh, I love Pharaonic's.
[1:05:19] SPEAKER: Just don't read the comments.
[1:05:21] SPEAKER: - Look, he has racks in his lab.
[1:05:23] SPEAKER: He has racks with multi-phase power in his lab.
[1:05:25] SPEAKER: So Wendell knows what's up.
[1:05:27] SPEAKER: But the point is,
[1:05:28] SPEAKER: he went back and retested a 285K
[1:05:31] SPEAKER: and a 285 non-K machine
[1:05:34] SPEAKER: and was really pleasantly surprised by the perf,
[1:05:38] SPEAKER: by the delta between the benchmarks that we saw at launch
[1:05:41] SPEAKER: because they had some power management problems.
[1:05:43] SPEAKER: They were sleeping the CPU
[1:05:44] SPEAKER: when they shouldn't be basically.
[1:05:46] SPEAKER: And it's an interesting watch if you care about that.
[1:05:50] SPEAKER: It made me reconsider the 285
[1:05:55] SPEAKER: as like, I've been on the 7800 X3D for a while now.
[1:05:59] SPEAKER: And the thing I will say about it is
[1:06:02] SPEAKER: the perf is really good in games
[1:06:04] SPEAKER: and it's a little bit frustrating
[1:06:06] SPEAKER: when I'm doing productivity stuff
[1:06:07] SPEAKER: coming from a 24 core Intel machine before.
[1:06:13] SPEAKER: - Prior to this, right?
[1:06:14] SPEAKER: - Yeah, an error like obviously is very good
[1:06:16] SPEAKER: on application productivity type stuff.
[1:06:18] SPEAKER: - Yeah, well, yeah.
[1:06:21] SPEAKER: - It was up there.
[1:06:22] SPEAKER: - It was not as good as 14900K.
[1:06:23] SPEAKER: It was better than AMD.
[1:06:26] SPEAKER: - Oh, you mean the one that just rules your power bill?
[1:06:29] SPEAKER: It's still among the fastest.
[1:06:31] SPEAKER: - I'm already paying 500 bucks a month for power.
[1:06:33] SPEAKER: Why not go, why not add another 20 on there?
[1:06:35] SPEAKER: - Yeah, Tech Power Up did some benchmarks.
[1:06:38] SPEAKER: You know, AMD and Intel both issued both BIOS updates
[1:06:42] SPEAKER: and also there were Windows updates like scheduler fixes
[1:06:45] SPEAKER: in the wake of Arrow Lake and Zen 5.
[1:06:48] SPEAKER: Tech Power Up a few weeks ago,
[1:06:49] SPEAKER: I've got the benchmarks in front of me,
[1:06:50] SPEAKER: did benchmarks on Arrow Lake 285K
[1:06:55] SPEAKER: between like shipping drivers and BIOS and Windows
[1:06:59] SPEAKER: and then the kind of the current updates to everything.
[1:07:01] SPEAKER: Some cases there were huge gaps.
[1:07:04] SPEAKER: Like Alan Wake 2 at 1080p was a difference of
[1:07:09] SPEAKER: and it's like 27 frames per second, pretty huge,
[1:07:13] SPEAKER: but some games showed next to no change.
[1:07:16] SPEAKER: So it's very situational, but in some cases
[1:07:19] SPEAKER: there were pretty dramatic improvements.
[1:07:24] SPEAKER: - Yeah, I was kind of pleasantly surprised.
[1:07:27] SPEAKER: I think we're gonna revisit it at PC World
[1:07:28] SPEAKER: if we can find some time,
[1:07:30] SPEAKER: because I wanna spend time using,
[1:07:33] SPEAKER: the other thing Wendell said is that
[1:07:34] SPEAKER: in his experiential stuff,
[1:07:36] SPEAKER: just using the machine for a few weeks,
[1:07:39] SPEAKER: he was really pleasantly surprised
[1:07:41] SPEAKER: by how performant it felt,
[1:07:44] SPEAKER: which is like on the eight core machine,
[1:07:47] SPEAKER: I occasionally get OS hitches that I definitely notice
[1:07:51] SPEAKER: and it's like, hey, I launched,
[1:07:53] SPEAKER: it's when I boot the computer up
[1:07:54] SPEAKER: and it's launching all the applications that run at startup
[1:07:56] SPEAKER: and like a few things stall out
[1:07:59] SPEAKER: 'cause there's just not a thread available for them, right?
[1:08:03] SPEAKER: And having more threads fixes that problem.
[1:08:05] SPEAKER: So anyway, that's that.
[1:08:09] SPEAKER: The Ryzen, I think most people redid the Ryzen benchmarks
[1:08:13] SPEAKER: actually when they did the 285K reviews
[1:08:17] SPEAKER: because the fixes for that had been in by then.
[1:08:20] SPEAKER: But yeah, that's what's going on in that front.
[1:08:22] SPEAKER: - That's cool.
[1:08:23] SPEAKER: I was interested in Aero Lake for a little bit.
[1:08:25] SPEAKER: I decided to chill when the gaming performance
[1:08:28] SPEAKER: came in under par, let's say.
[1:08:30] SPEAKER: - Yeah.
[1:08:31] SPEAKER: - So I've been keeping an eye on Panther Lake
[1:08:32] SPEAKER: is supposed to be the successor,
[1:08:33] SPEAKER: the first one on Intel's own fab.
[1:08:36] SPEAKER: - Yeah, this is the Intel 18A process now.
[1:08:37] SPEAKER: - Yeah, the 18A process that we've talked about
[1:08:39] SPEAKER: in the past.
[1:08:41] SPEAKER: Rumor as of the last few days coming out of analyst spaces
[1:08:44] SPEAKER: is that Panther Lake might now be a 2026 release.
[1:08:49] SPEAKER: Unfortunately.
[1:08:50] SPEAKER: - I would bet dollars to donuts
[1:08:51] SPEAKER: that they'll roll something out by the end of the year
[1:08:53] SPEAKER: and it'll be a real soft supply at launch.
[1:08:57] SPEAKER: - That was kind of what the analysts were.
[1:09:00] SPEAKER: I think Ming-Chi Kuo was one of the people
[1:09:02] SPEAKER: that posted about this.
[1:09:04] SPEAKER: It may be a tail end of 2025 like on paper,
[1:09:08] SPEAKER: but general availability probably sometime next year,
[1:09:11] SPEAKER: unfortunately.
[1:09:12] SPEAKER: I'm very curious to see how that one turns out.
[1:09:16] SPEAKER: - Yeah, I mean, it's a real make or break situation
[1:09:19] SPEAKER: for Intel, it seems like.
[1:09:21] SPEAKER: - Yeah.
[1:09:24] SPEAKER: - Like they made this huge investment in US fabs
[1:09:27] SPEAKER: and they have to get something back from it
[1:09:30] SPEAKER: or they're going to have problems.
[1:09:34] SPEAKER: - Yeah, yeah, that's about all there is to say
[1:09:36] SPEAKER: about that right now,
[1:09:37] SPEAKER: but maybe a little bit longer to wait on the next gen Intel.
[1:09:40] SPEAKER: And I don't know where AMD is at.
[1:09:42] SPEAKER: I mean, if they're just shipping the 16 core gaming
[1:09:46] SPEAKER: Zen 5 parts, I'm assuming any next gen CPUs
[1:09:50] SPEAKER: are good ways off for them.
[1:09:51] SPEAKER: - Well, I mean, one of the reasons we said
[1:09:53] SPEAKER: this was the last time we're gonna talk about this
[1:09:54] SPEAKER: for a while is my assumption is that we aren't going
[1:09:56] SPEAKER: to have new CPUs until Panther Lake
[1:10:00] SPEAKER: and my assumption is AMD will be on the Zen 5 stuff
[1:10:04] SPEAKER: for 18 months, at least.
[1:10:06] SPEAKER: - Yeah, I was thinking maybe early next year
[1:10:07] SPEAKER: for what I assume will be Zen 6 or whatever they call it.
[1:10:10] SPEAKER: - That makes sense.
[1:10:12] SPEAKER: - Can I get the thing in here that I'm actually
[1:10:15] SPEAKER: the most excited about real quick?
[1:10:17] SPEAKER: - Yeah.
[1:10:18] SPEAKER: - Wildcat Lake.
[1:10:19] SPEAKER: - I don't know what that one is.
[1:10:20] SPEAKER: I saw it here on the list.
[1:10:21] SPEAKER: - So I'm sure you probably remember me having talked
[1:10:24] SPEAKER: in the past about Alder Lake Inn.
[1:10:26] SPEAKER: - Yeah.
[1:10:27] SPEAKER: - Which is probably maybe what's in your Beelink
[1:10:29] SPEAKER: or no, yours is before that.
[1:10:30] SPEAKER: I think yours is 11th gen.
[1:10:32] SPEAKER: - It's the one, Alder Lake Inn is the one before Raptor.
[1:10:36] SPEAKER: Well, it's the one before what became Raptor Lake, right?
[1:10:39] SPEAKER: - Well, Alder Lake was the 12th gen desktop part,
[1:10:42] SPEAKER: but we're talking CPUs in the small fanless,
[1:10:45] SPEAKER: low power space.
[1:10:47] SPEAKER: - Gotcha.
[1:10:48] SPEAKER: - Alder Lake Inn, it's like the N100, N200, N150.
[1:10:52] SPEAKER: It's that line.
[1:10:53] SPEAKER: - Yeah, yeah.
[1:10:54] SPEAKER: - It's kind of the thing you buy right now
[1:10:55] SPEAKER: if you're gonna make a little Plex machine
[1:10:57] SPEAKER: 'cause they've got quick sync or like a very powerful
[1:11:00] SPEAKER: home router, for example.
[1:11:02] SPEAKER: - Mine is an N5105, which is an 11th gen.
[1:11:06] SPEAKER: - Yeah, I think that's right before
[1:11:07] SPEAKER: the Alder Lake Inn stuff came out.
[1:11:09] SPEAKER: Anyway, these are all rumors, completely subject to change,
[1:11:11] SPEAKER: but coming out of supply chain or wherever,
[1:11:14] SPEAKER: Wildcat Lake supposedly is going to be the successor
[1:11:16] SPEAKER: to Alder Lake Inn.
[1:11:18] SPEAKER: - Oh.
[1:11:19] SPEAKER: - So like full on next gen version of the low power CPUs
[1:11:23] SPEAKER: that are going into these little kind of
[1:11:25] SPEAKER: very heavily network enabled router boxes
[1:11:27] SPEAKER: and stuff like that.
[1:11:29] SPEAKER: It sounds awesome based on these rumors.
[1:11:30] SPEAKER: These rumors could be, you know,
[1:11:33] SPEAKER: always grain of salt, I guess, out of the stuff.
[1:11:35] SPEAKER: Although I feel like leaks and rumors probably generally
[1:11:37] SPEAKER: from vetted people are more accurate than not these days,
[1:11:41] SPEAKER: or at least within a ballpark, right?
[1:11:43] SPEAKER: - Yeah, yeah.
[1:11:44] SPEAKER: - If not fully.
[1:11:46] SPEAKER: - Look, there's enough stuff in the chain
[1:11:47] SPEAKER: that like the leaks have a better chance of being real now
[1:11:51] SPEAKER: than they ever used to be.
[1:11:52] SPEAKER: - That's what it is.
[1:11:53] SPEAKER: There's too much interconnectedness,
[1:11:55] SPEAKER: between companies and shipping partners and marketing
[1:11:57] SPEAKER: and you name it, too many people have access
[1:12:00] SPEAKER: to information these days.
[1:12:03] SPEAKER: The gist of Wildcat Lake is they're talking
[1:12:06] SPEAKER: two performance cores and four LPE cores,
[1:12:10] SPEAKER: low power efficiency cores,
[1:12:11] SPEAKER: which is like what's in Lunar Lake.
[1:12:13] SPEAKER: - Yeah.
[1:12:15] SPEAKER: - So, and those are like the next gen versions
[1:12:18] SPEAKER: like Cougar Cove and Darkmont would be the,
[1:12:20] SPEAKER: I have no idea about the performance of those things.
[1:12:23] SPEAKER: I'd like, I assume those are just a linear increase
[1:12:27] SPEAKER: in performance and not some offshoot
[1:12:29] SPEAKER: that might make concessions somewhere.
[1:12:31] SPEAKER: But anyway, and they're saying this would be fabbed
[1:12:34] SPEAKER: on 18A as well.
[1:12:35] SPEAKER: - Oh, that's interesting.
[1:12:36] SPEAKER: - Like very low TDP.
[1:12:38] SPEAKER: - Well, so the Lunar Lake stuff is an evolutionary dead end,
[1:12:41] SPEAKER: but the performance cores in that
[1:12:43] SPEAKER: and the efficiency cores in that are moving forward
[1:12:46] SPEAKER: in different processors is my understanding.
[1:12:48] SPEAKER: - Yeah, so this report says these things
[1:12:50] SPEAKER: would be trickling down from Panther Lake.
[1:12:55] SPEAKER: So, you know, it sounds like if the stuff is real,
[1:12:58] SPEAKER: the next gen version of this, you know,
[1:13:01] SPEAKER: these little fanless Intel boxes are everywhere
[1:13:03] SPEAKER: or even ones with fans, like the B links are everywhere now,
[1:13:06] SPEAKER: but like what's happening in the low power space
[1:13:09] SPEAKER: with x86 I think is kind of some of the most exciting stuff
[1:13:12] SPEAKER: happening in CPU's right now.
[1:13:13] SPEAKER: 'Cause that means more cool little boxes
[1:13:15] SPEAKER: that don't suck a lot of power around the house
[1:13:17] SPEAKER: doing things.
[1:13:18] SPEAKER: - Yeah, I mean, that's exactly it.
[1:13:20] SPEAKER: Like I'm stoked about the ability to run,
[1:13:25] SPEAKER: like my B-Link is starting to show its age a little bit.
[1:13:28] SPEAKER: It's having trouble with 4K stuff, quick sync setup.
[1:13:32] SPEAKER: So yeah.
[1:13:33] SPEAKER: - Like the idea of a little box that pulls 10 or 15 Watts
[1:13:35] SPEAKER: and maybe doesn't even have a fan running in it
[1:13:37] SPEAKER: or maybe a small one that is faster than my gaming PC
[1:13:40] SPEAKER: of eight years ago, pretty rad.
[1:13:44] SPEAKER: You know, like if that's my router,
[1:13:45] SPEAKER: which it's going to be if the stuff comes together,
[1:13:47] SPEAKER: like that's very exciting to me.
[1:13:49] SPEAKER: - I tested, well, and the other interesting thing
[1:13:51] SPEAKER: that's happened is Intel as it,
[1:13:53] SPEAKER: when Intel sold off the Nuke line,
[1:13:55] SPEAKER: a bunch of other people started making them
[1:13:57] SPEAKER: and they're doing interesting stuff.
[1:13:59] SPEAKER: Like I tested out an MSI QB Nuke,
[1:14:02] SPEAKER: one of their little like 0.8 liter computers,
[1:14:05] SPEAKER: not whatever they call it, but it had,
[1:14:10] SPEAKER: it was like, it was a box that I looked at and I was like,
[1:14:12] SPEAKER: these people clearly think that
[1:14:13] SPEAKER: this is going to be a router, right?
[1:14:15] SPEAKER: 'Cause it had two ethernet ports.
[1:14:17] SPEAKER: It has HDMI, it has an external two pin header for power,
[1:14:21] SPEAKER: for the power switch.
[1:14:22] SPEAKER: - Oh, interesting.
[1:14:24] SPEAKER: - I mean, I think that's so that if you hang it off
[1:14:26] SPEAKER: of a VESA mount on the back of your monitor,
[1:14:28] SPEAKER: then you plug that in and you put a button
[1:14:30] SPEAKER: where you can see it.
[1:14:31] SPEAKER: But also it means that if you wanted to use it
[1:14:34] SPEAKER: with like your Pi KVM, you just run the jumper to the jumper
[1:14:37] SPEAKER: and you're good to go, right?
[1:14:39] SPEAKER: There's no shenanigans.
[1:14:40] SPEAKER: - That's nice to hear that like known companies like that
[1:14:43] SPEAKER: are getting in on the space.
[1:14:44] SPEAKER: 'Cause I'm still maybe a little on the fence
[1:14:46] SPEAKER: about ordering a no name box from AliExpress
[1:14:50] SPEAKER: to use as my router, so we'll see.
[1:14:52] SPEAKER: - Yeah, but yeah, I think low power, low power PC,
[1:14:57] SPEAKER: like, look, I plugged the watt meter into my computer
[1:15:01] SPEAKER: the other day just to see what I was drawing.
[1:15:04] SPEAKER: And it's like, I'm pulling 247.1 Watts right now,
[1:15:08] SPEAKER: just on the desktop without the monitors or the lights
[1:15:11] SPEAKER: or anything else that I'm using.
[1:15:12] SPEAKER: - Okay.
[1:15:14] SPEAKER: - And I'm thinking maybe I should, like, it might be cheaper
[1:15:17] SPEAKER: for me to buy a $300 NUC that I use for desktop stuff
[1:15:20] SPEAKER: and then switch on the gaming PC
[1:15:22] SPEAKER: when I wanted to do the gaming PC stuff.
[1:15:23] SPEAKER: - God, I didn't even think, that's crazy.
[1:15:25] SPEAKER: I didn't even think about something like that.
[1:15:26] SPEAKER: - Yeah.
[1:15:27] SPEAKER: - And you could get a visa mount
[1:15:28] SPEAKER: on the back of your monitor and just stick the little NUC
[1:15:31] SPEAKER: on the monitor and you'll never even see it.
[1:15:32] SPEAKER: - Dangle it off there, yeah, exactly.
[1:15:36] SPEAKER: - All right, let me throw out my pie in the sky finisher
[1:15:41] SPEAKER: for this little conversation.
[1:15:42] SPEAKER: - Okay, what do you got?
[1:15:43] SPEAKER: - You can shake your head at me
[1:15:44] SPEAKER: and then we can end this episode.
[1:15:45] SPEAKER: - All right, I love shaking my head.
[1:15:47] SPEAKER: - Whenever I finally get whatever this box is going to be
[1:15:49] SPEAKER: that I ended up buying to replace my router,
[1:15:51] SPEAKER: I think I might just put bare Linux on it.
[1:15:54] SPEAKER: - Oh, Jesus Christ.
[1:15:55] SPEAKER: - I think I might go all the way.
[1:15:57] SPEAKER: - How good are you a firewall configuration, Brad?
[1:15:59] SPEAKER: - Not very.
[1:16:00] SPEAKER: - That's a bad idea then.
[1:16:00] SPEAKER: - That is 100% the thing I need to bone up on.
[1:16:03] SPEAKER: - You need to bone, but you need to bone harder
[1:16:06] SPEAKER: than you've ever boned before
[1:16:07] SPEAKER: if you're gonna run a naked Linux machine on the internet.
[1:16:10] SPEAKER: Or you're going to, it's either, you have to choose
[1:16:13] SPEAKER: whether you want to be the boner or the boney.
[1:16:15] SPEAKER: - Yes, I know.
[1:16:16] SPEAKER: - 'Cause if you do not have your firewall shit dialed in,
[1:16:19] SPEAKER: you will be boned, not boning.
[1:16:22] SPEAKER: - In fairness, it's pretty easy to go maximal firewall
[1:16:25] SPEAKER: and then very slowly walk back the ports you need
[1:16:28] SPEAKER: and the protocols from there.
[1:16:30] SPEAKER: - I just-
[1:16:31] SPEAKER: - It's easy to let nothing through.
[1:16:33] SPEAKER: The trick is not letting too much through.
[1:16:36] SPEAKER: But like how much is there in a router?
[1:16:38] SPEAKER: There's a firewall, you need a DHCP server.
[1:16:40] SPEAKER: You might have to set some custom routes.
[1:16:43] SPEAKER: You might have to set some custom routes
[1:16:44] SPEAKER: if you're doing anything fancy.
[1:16:46] SPEAKER: - Yeah, you need the NAT stuff and-
[1:16:49] SPEAKER: - Like, I think it's doable.
[1:16:52] SPEAKER: - I mean, yeah, it's doable.
[1:16:54] SPEAKER: Is it smart?
[1:16:55] SPEAKER: Absolutely not.
[1:16:56] SPEAKER: No, that's a bad idea.
[1:16:58] SPEAKER: - Quite a, there are a number of people on Discord
[1:17:00] SPEAKER: who have been doing it for a while.
[1:17:02] SPEAKER: - Yeah, but like, look, they're just messing with you, man.
[1:17:06] SPEAKER: This is a terrible idea.
[1:17:08] SPEAKER: Like, here's the thing.
[1:17:09] SPEAKER: You just need to think about what happens
[1:17:12] SPEAKER: when it stops working for two days
[1:17:15] SPEAKER: and how much of a pain in the ass that's gonna be.
[1:17:17] SPEAKER: - Nah, we'll see.
[1:17:18] SPEAKER: - It'd be like, this is where PFSense
[1:17:19] SPEAKER: or OpenSense comes into place, right?
[1:17:22] SPEAKER: - Yeah, maybe.
[1:17:22] SPEAKER: Maybe.
[1:17:23] SPEAKER: - Like, it's, you know, it's a true,
[1:17:26] SPEAKER: it's a vetted open source.
[1:17:28] SPEAKER: - You're not wrong.
[1:17:29] SPEAKER: I would probably start with OpenSense.
[1:17:32] SPEAKER: - I mean, no, you're not.
[1:17:32] SPEAKER: - Probably.
[1:17:33] SPEAKER: - You're gonna do the bad thing.
[1:17:35] SPEAKER: This is a bad idea, Brad.
[1:17:37] SPEAKER: This is a bad idea.
[1:17:39] SPEAKER: But you know what's a great idea?
[1:17:42] SPEAKER: Supporting this podcast.
[1:17:44] SPEAKER: We are a listener-supported show.
[1:17:45] SPEAKER: - True.
[1:17:46] SPEAKER: - That means we don't take money from ads.
[1:17:48] SPEAKER: We don't take product placements.
[1:17:50] SPEAKER: Nobody's paid us money to talk about this today,
[1:17:52] SPEAKER: except for you, the listener.
[1:17:53] SPEAKER: And without you, we wouldn't be here,
[1:17:55] SPEAKER: so we appreciate each and every one of you.
[1:17:56] SPEAKER: But especially, oh, but if you wanna learn
[1:17:59] SPEAKER: how to support the show, I need to tell you that
[1:18:00] SPEAKER: 'cause I haven't done that yet.
[1:18:02] SPEAKER: I'm off my game today 'cause the carbon dioxide level
[1:18:05] SPEAKER: in my office right now is very high
[1:18:06] SPEAKER: 'cause we've been talking for a long time.
[1:18:09] SPEAKER: - It's patreon.com/techpod.
[1:18:11] SPEAKER: You can go to patreon.com/techpod
[1:18:13] SPEAKER: and for five bucks a month,
[1:18:14] SPEAKER: you get access to the Patreon Discord,
[1:18:17] SPEAKER: which is full of beautiful nerds just like you.
[1:18:19] SPEAKER: You get access to the Patreon, Patreon exclusive episode.
[1:18:23] SPEAKER: And well, I mean, those two things are it,
[1:18:25] SPEAKER: but they're both very good.
[1:18:27] SPEAKER: You would like them if you go to, yeah.
[1:18:29] SPEAKER: - And you keep this podcast going.
[1:18:31] SPEAKER: - And yeah, and we, yeah, we get paid.
[1:18:34] SPEAKER: - Podcast itself would not exist without you.
[1:18:36] SPEAKER: - Food is important to me, my family,
[1:18:38] SPEAKER: Brad, his family, everyone.
[1:18:40] SPEAKER: So yeah, with that in mind,
[1:18:43] SPEAKER: we're gonna thank our executive producer to your patrons
[1:18:45] SPEAKER: who we think every single week,
[1:18:46] SPEAKER: including Jason Lee, Andrew Slosky, Jordan Lippitt,
[1:18:51] SPEAKER: Bunny Fiend, Twinkle Twinkie, David Allen,
[1:18:54] SPEAKER: James Kamik, and Pantheon, makers of the HS3
[1:18:57] SPEAKER: high-speed 3D printer.
[1:18:58] SPEAKER: Thank you all so, so much.
[1:18:59] SPEAKER: - Yeah, thank you.
[1:19:01] SPEAKER: - And that'll do it for us this week.
[1:19:02] SPEAKER: We will be back next week
[1:19:03] SPEAKER: with another edition of the Tech Pod.
[1:19:04] SPEAKER: Until then, please consider the environment
[1:19:06] SPEAKER: before printing this podcast.
[1:19:09] SPEAKER: (upbeat music)
