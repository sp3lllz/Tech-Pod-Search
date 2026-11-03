---
episode: 309
title: 299: Donkey Kong Is a Florida Man
date: 2025-08-10
guests: none
duration: 1:14:48
---

[00:00] SPEAKER: - Hey, remember that period of a few weeks earlier this year
[00:02] SPEAKER: when I got way into computer security?
[00:05] SPEAKER: - You mean, I like to think it was your secure boot phase.
[00:08] SPEAKER: - I went real deep on signing EFI boot loaders
[00:12] SPEAKER: and the Linux kernel and stuff like that
[00:14] SPEAKER: to work with secure boot,
[00:16] SPEAKER: because I felt I insisted that secure boot be on
[00:19] SPEAKER: on all my computers.
[00:20] SPEAKER: - And I remember saying, man, nobody uses secure boot.
[00:23] SPEAKER: It's fine, just turn it off
[00:24] SPEAKER: and then make installing Linux easy.
[00:26] SPEAKER: - I'm making that hand motion, you know,
[00:28] SPEAKER: where you kind of polish your hand on your shirt.
[00:30] SPEAKER: - Oh, oh, that's what that is, okay.
[00:32] SPEAKER: - Somebody was ahead of the curve.
[00:33] SPEAKER: - Yeah, okay, so there's some things that happened
[00:36] SPEAKER: in the last like 15 years of computers
[00:39] SPEAKER: and they're kind of black boxes
[00:41] SPEAKER: and secure boot is one of those for me, right?
[00:44] SPEAKER: Like I understand theoretically what's happening,
[00:46] SPEAKER: but I don't understand the impacts of how it works
[00:48] SPEAKER: and all the BIOSes, sorry, UEFIs,
[00:52] SPEAKER: have different descriptions in there
[00:54] SPEAKER: of what the settings are.
[00:56] SPEAKER: And the one time I've screwed it up,
[00:59] SPEAKER: it ended up with me reinstalling Windows
[01:00] SPEAKER: 'cause I couldn't recover the Windows install
[01:04] SPEAKER: with the keys that I had or something.
[01:06] SPEAKER: - Now that part I don't get.
[01:07] SPEAKER: A lot of the fear mongering I've been seeing,
[01:08] SPEAKER: hang on, we should back up, point of order.
[01:10] SPEAKER: The reason we're even talking about secure boot
[01:11] SPEAKER: is that the Battlefield 6 Beta is running this weekend
[01:14] SPEAKER: and on PCs. - Which owns,
[01:15] SPEAKER: just for the record, it's a good one.
[01:17] SPEAKER: - I should check that out.
[01:18] SPEAKER: - Yeah.
[01:19] SPEAKER: - But on PC, it requires you,
[01:20] SPEAKER: it's level of anti-cheat requires you
[01:23] SPEAKER: to have secure boot enabled on your PC.
[01:25] SPEAKER: In order to run it.
[01:26] SPEAKER: - This is part of the new anti-cheat.
[01:29] SPEAKER: The next Cod, Cod Blob 7,
[01:31] SPEAKER: is gonna have a secure boot required anti-cheat as well.
[01:34] SPEAKER: - Same thing.
[01:34] SPEAKER: - And I think part of the theory is
[01:37] SPEAKER: they want to make sure that you're not running A in a VM.
[01:40] SPEAKER: They wanna make sure you're not running Windows in a VM
[01:42] SPEAKER: so then you can monkey with the state of the VM
[01:44] SPEAKER: from outside the VM.
[01:46] SPEAKER: B, that's the only thing I can think of
[01:49] SPEAKER: 'cause I don't think anybody's running
[01:51] SPEAKER: boot level cheating programs.
[01:53] SPEAKER: - Probably not.
[01:55] SPEAKER: I think there's also the enabling secure boot
[01:58] SPEAKER: also flips onto the flag that requires signed drivers,
[02:01] SPEAKER: which means that hardware hacking devices
[02:04] SPEAKER: that people use that are like,
[02:06] SPEAKER: I think PCI express cards that interface with software
[02:08] SPEAKER: and then can communicate across the system bus or something.
[02:11] SPEAKER: - Wait, hang on, I need to stop you.
[02:13] SPEAKER: Are you suggesting there is cheating hardware out there?
[02:15] SPEAKER: - My understanding, there was a,
[02:17] SPEAKER: I spent some time in the Steam forums this weekend, Brad.
[02:20] SPEAKER: - Okay, I need to know about this.
[02:22] SPEAKER: Not that I want to cheat,
[02:24] SPEAKER: but conceptually, that sounds absolutely bizarre.
[02:26] SPEAKER: - So there was a thread,
[02:29] SPEAKER: and I'm gonna see if I can find it,
[02:31] SPEAKER: where Battlefield 6 said,
[02:33] SPEAKER: "Hey, we wanted to share an update
[02:35] SPEAKER: from our anti-cheat team on secure boot and cheats."
[02:37] SPEAKER: And then they explained why they did that
[02:39] SPEAKER: and how many people they banned, yada, yada, yada.
[02:41] SPEAKER: And then the third guy responding
[02:44] SPEAKER: is a guy named Smoke with a dollar sign as the S,
[02:47] SPEAKER: and he has like a weird font for the M-O-K-E,
[02:51] SPEAKER: said, "Again, secure boot does nothing to deal with cheats.
[02:54] SPEAKER: All it takes is a hundred dollar side tower
[02:57] SPEAKER: to spoof a kernel level handshake on that rig."
[02:59] SPEAKER: - Side tower? - Which I assume means
[03:01] SPEAKER: you're plugging in a DM,
[03:04] SPEAKER: it says a cheater can buy a DMA card fuser in KM box
[03:07] SPEAKER: for less than a hundred bucks,
[03:08] SPEAKER: which when I did some Googling
[03:09] SPEAKER: are things you plug into another computer
[03:11] SPEAKER: that you plug into your gaming computer
[03:13] SPEAKER: and let you manipulate the state of memory in the game.
[03:17] SPEAKER: - Interesting. - Anyway.
[03:19] SPEAKER: - Yeah, on the secure boot requires signed drivers,
[03:23] SPEAKER: I think that might be at the discretion
[03:24] SPEAKER: of the operating system kernel or policy.
[03:27] SPEAKER: - I mean, I'm talking about in Windows specifically.
[03:29] SPEAKER: - Yeah, in Windows, I'm sure that's the case.
[03:31] SPEAKER: I think it's definitely the case in Linux
[03:33] SPEAKER: that if you're running secure boots,
[03:34] SPEAKER: then the kernel requires kernel modules to be signed as well.
[03:38] SPEAKER: - Yeah, that makes sense.
[03:39] SPEAKER: - Secure boot, since you asked or you said,
[03:41] SPEAKER: you know, it's one of those things that's like out there
[03:43] SPEAKER: and people have heard of it
[03:44] SPEAKER: but don't necessarily know exactly,
[03:45] SPEAKER: it's just a way of making sure
[03:47] SPEAKER: that nothing in the chain of executables
[03:49] SPEAKER: that have to boot when you turn a computer on
[03:51] SPEAKER: until you get to an operating system login screen
[03:53] SPEAKER: have been tampered with.
[03:54] SPEAKER: - Yeah.
[03:55] SPEAKER: - So, and they do that simply by enrolling
[03:57] SPEAKER: a set of private keys in your UEFI.
[04:00] SPEAKER: Also, I'm gonna take a pause here.
[04:01] SPEAKER: There was a point like a year or two ago
[04:03] SPEAKER: where I insisted that I would never use the term UEFI,
[04:06] SPEAKER: that it would always be BIOS.
[04:08] SPEAKER: - Yeah, here we are, huh?
[04:09] SPEAKER: - Well, then I actually look into what UEFI is and does.
[04:13] SPEAKER: And now it's actually, I hate saying it,
[04:15] SPEAKER: it's a terrible acronym,
[04:16] SPEAKER: but I think it's like, it is so much more robust
[04:19] SPEAKER: and it does so many more things than the old BIOS
[04:21] SPEAKER: that I feel like making the distinction
[04:22] SPEAKER: was actually useful, anyway.
[04:23] SPEAKER: - Well, the other one was basic and now it's universal.
[04:25] SPEAKER: - Yes, I guess it's the, but it's just hard to say.
[04:28] SPEAKER: - UEFI, that's what we say at PC World.
[04:30] SPEAKER: - I thought that really, I just, mm, UEFI, UEFI.
[04:32] SPEAKER: - You could say UEFI, I guess.
[04:34] SPEAKER: - Wait, UEFI, like Final Fantasy VII, UEFI?
[04:36] SPEAKER: - I don't know about that.
[04:37] SPEAKER: - Okay, if I make that connection,
[04:38] SPEAKER: maybe that makes sense in my brain.
[04:40] SPEAKER: - I played, I only played the first part of Final Fantasy VII.
[04:43] SPEAKER: I don't think there's a UEFI in that one.
[04:45] SPEAKER: - She's the ninja character, she's an optional character.
[04:47] SPEAKER: Actually, I believe you don't have to recruit her.
[04:48] SPEAKER: I think she is optional to get.
[04:50] SPEAKER: - I've only gotten to the end of the first one,
[04:52] SPEAKER: not the second one.
[04:54] SPEAKER: - Yeah, the real Final Fantasy VII.
[04:56] SPEAKER: - She is very prominently the new character in Rebirth,
[04:59] SPEAKER: although she actually, they introduced her in a DLC
[05:01] SPEAKER: for remake, but then, anyway.
[05:03] SPEAKER: - Okay, anyway.
[05:04] SPEAKER: - Moving on. - The point is.
[05:05] SPEAKER: - The point is, yes, like you have keys,
[05:08] SPEAKER: you have private keys enrolled in your UEFI
[05:10] SPEAKER: and then everything from the UEFI bootloader,
[05:13] SPEAKER: the UEFI launches that then launches the OS kernel,
[05:16] SPEAKER: like all of those binaries
[05:18] SPEAKER: have to be signed with public keys.
[05:20] SPEAKER: Sorry, other way around.
[05:21] SPEAKER: - Private keys.
[05:22] SPEAKER: - I'm sorry, it's other way around.
[05:23] SPEAKER: You have to sign them with the private key
[05:25] SPEAKER: and then they're checked against the public key.
[05:27] SPEAKER: You are not wrong that secure boot implementations
[05:29] SPEAKER: in UEFI's can be terrible.
[05:31] SPEAKER: - Wild.
[05:32] SPEAKER: - Can be terrible.
[05:33] SPEAKER: - Well.
[05:34] SPEAKER: - There are a bunch of different ways to do it.
[05:35] SPEAKER: In Windows, whatever, you just turn secure boot on
[05:38] SPEAKER: in the BIOS because Windows is signed with,
[05:40] SPEAKER: Microsoft is a certificate authority,
[05:42] SPEAKER: or in fact, the certificate authority.
[05:44] SPEAKER: - Must be nice.
[05:44] SPEAKER: - For valid secure boot keys.
[05:46] SPEAKER: So like every motherboard on the planet
[05:48] SPEAKER: is going to work with Windows and secure boot.
[05:49] SPEAKER: In fact, I had saw people,
[05:51] SPEAKER: a lot of the idiot fear mongering that has sprung up
[05:53] SPEAKER: in the wake of this requirement is just like,
[05:56] SPEAKER: I can't even wrap my head around it.
[05:57] SPEAKER: There's people out there go,
[05:58] SPEAKER: oh, it hurts your performance
[05:59] SPEAKER: or oh, you'll break your motherboard.
[06:01] SPEAKER: Like those things are impossible.
[06:02] SPEAKER: That's ridiculous.
[06:03] SPEAKER: But turning it on in the BIOS
[06:04] SPEAKER: is definitely can be more complicated than it should be.
[06:07] SPEAKER: Like my motherboard, which is a nice motherboard.
[06:09] SPEAKER: Sometimes this setting doesn't stick
[06:11] SPEAKER: for two or three reboots.
[06:12] SPEAKER: - That's great.
[06:13] SPEAKER: - You just have to keep doing it over and over.
[06:15] SPEAKER: At one point it unenrolled,
[06:17] SPEAKER: it cleared my custom key that I had enrolled in there
[06:19] SPEAKER: and then it wouldn't boot either until I,
[06:21] SPEAKER: when really, anyway.
[06:22] SPEAKER: - It's Microsoft with a dollar sign
[06:24] SPEAKER: doing their dirty business is the way it looks like to me.
[06:26] SPEAKER: - No, well, that one's on a series, but anyway.
[06:28] SPEAKER: - So yeah, the problem I had when I nuked the machine,
[06:32] SPEAKER: Windows install, I had, it's an older machine.
[06:35] SPEAKER: It's the 9900K machine.
[06:39] SPEAKER: So it was early-ish for secure boot.
[06:42] SPEAKER: And I think that I nuked the keys that it was using.
[06:45] SPEAKER: I think it was using a separate set of keys.
[06:47] SPEAKER: I had enrolled a separate key at some point for Windows 10
[06:50] SPEAKER: and I switched to Windows 11 and it didn't translate
[06:53] SPEAKER: or what, I didn't change it over or something.
[06:55] SPEAKER: Anyway, the upshot was it failed to boot
[06:57] SPEAKER: with a secure boot error over and over and over again
[06:59] SPEAKER: until I was just like, it's just gonna be easier
[07:00] SPEAKER: to reinstall Windows on this machine and fix this problem.
[07:02] SPEAKER: - Wait, so you couldn't just turn secure boot off?
[07:05] SPEAKER: - Uh-uh.
[07:05] SPEAKER: - You should have been able to.
[07:06] SPEAKER: - Nope, didn't work.
[07:09] SPEAKER: - Like I said, I've had mine stick where I had to just keep
[07:12] SPEAKER: turning it off and rebooting like two or three times
[07:15] SPEAKER: before it would actually do it.
[07:16] SPEAKER: - It's possible I had that.
[07:17] SPEAKER: That was a, that's a gigabyte board, I think.
[07:19] SPEAKER: But I, look, I spent about 20 minutes on it
[07:24] SPEAKER: and I reached the point where I was like,
[07:25] SPEAKER: this is a simple machine.
[07:26] SPEAKER: I have everything backed up.
[07:27] SPEAKER: It'll take me like 20 minutes to reinstall it.
[07:28] SPEAKER: So I'll just do that.
[07:29] SPEAKER: - Yeah.
[07:30] SPEAKER: The interaction between UEFI and operating systems
[07:33] SPEAKER: is fascinating to me.
[07:34] SPEAKER: Like, did you know that Windows updates
[07:36] SPEAKER: will modify secure boot keys in your UEFI?
[07:39] SPEAKER: - Yeah, I'm aware of that too.
[07:40] SPEAKER: That's how I nuked my cache to install the other day.
[07:43] SPEAKER: - There's, there's the DB and the DBX.
[07:45] SPEAKER: The DB is like the good keys.
[07:47] SPEAKER: The DBX is the list of banned keys.
[07:49] SPEAKER: - Whoa.
[07:50] SPEAKER: - That is put out by like security professionals.
[07:53] SPEAKER: - How did you get your key banned?
[07:55] SPEAKER: - Certain keys become compromised over time.
[07:58] SPEAKER: - Oh.
[07:59] SPEAKER: - Like if the private key gets out there,
[08:00] SPEAKER: then it's useless at that point.
[08:02] SPEAKER: Like earlier or whatever, I'm not a cryptographer,
[08:05] SPEAKER: but whatever, whatever part of that chain of.
[08:07] SPEAKER: - Yeah, if your private key is no longer private,
[08:09] SPEAKER: then it becomes useless for cryptography, yes.
[08:11] SPEAKER: - Or it's maybe it's like the certificate signing key
[08:14] SPEAKER: or something, some key gets out there
[08:15] SPEAKER: and then those keys are useless from a security standpoint.
[08:17] SPEAKER: So they have to be revoked.
[08:19] SPEAKER: Anyway, like if you watch your UEFI after a Windows update,
[08:22] SPEAKER: sometimes you'll see the number on the DBX tick up
[08:24] SPEAKER: because, because Microsoft has stealth banned
[08:27] SPEAKER: a few more secure boot keys in your UEFI.
[08:29] SPEAKER: - Great.
[08:30] SPEAKER: - Computing is fascinating, I find.
[08:33] SPEAKER: - I mean, it's infinitely complex.
[08:35] SPEAKER: - And infinitely diverse.
[08:39] SPEAKER: So I guess, good job.
[08:41] SPEAKER: - Mm-hmm, good job.
[08:42] SPEAKER: (upbeat music)
[09:05] SPEAKER: (upbeat music)
[09:10] SPEAKER: - Welcome to "Brad and Will Made a Tech Pod."
[09:13] SPEAKER: I'm Will.
[09:14] SPEAKER: - I'm Brad.
[09:15] SPEAKER: - Hey, "Battlefield 6" though, pretty good.
[09:17] SPEAKER: The tanks, I laid on the back of a tank and healed a guy,
[09:20] SPEAKER: healed the tank while other people were shooting at me
[09:22] SPEAKER: until somebody sniped me off the back of the tank
[09:24] SPEAKER: and I was like, "Yeah, I deserve that."
[09:25] SPEAKER: - How's it look?
[09:26] SPEAKER: - It looks like a single player game, Brad.
[09:29] SPEAKER: Like it's almost too much visual noise
[09:31] SPEAKER: for a multiplayer game.
[09:32] SPEAKER: - Okay.
[09:33] SPEAKER: - Like they do a thing where they put little diamonds
[09:36] SPEAKER: on top of everybody.
[09:38] SPEAKER: So you can see the enemies in the field
[09:42] SPEAKER: when they've been pinged by somebody on your team better
[09:44] SPEAKER: 'cause like it's noisy.
[09:46] SPEAKER: - Interesting, like the PC version, I assume?
[09:48] SPEAKER: - Yeah, well, I mean, it's "Battlefield."
[09:51] SPEAKER: - Yeah, okay.
[09:52] SPEAKER: - It's a mouse keyboard game, Brad.
[09:53] SPEAKER: - Fair, fair.
[09:54] SPEAKER: - I'm excited 'cause they're taking another step,
[09:56] SPEAKER: the old battle royale.
[09:57] SPEAKER: And you know how I feel about a battle royale.
[09:59] SPEAKER: - Wait, has "Battlefield" ever done that before?
[10:01] SPEAKER: - They did "Firebreak" with "Battlefield 5," I think.
[10:06] SPEAKER: - Okay.
[10:06] SPEAKER: - Which was bad.
[10:09] SPEAKER: All the destructible buildings and stuff made it
[10:12] SPEAKER: so there was no cover.
[10:13] SPEAKER: So that it meant whoever had a tank won the game,
[10:15] SPEAKER: which, you know, like real talk, tanks win wars.
[10:19] SPEAKER: But battle royales, it wanted to be a little more,
[10:22] SPEAKER: you know, infantry-based than that, I think.
[10:24] SPEAKER: Anyway.
[10:25] SPEAKER: - This is 100% like modern military, real world,
[10:27] SPEAKER: like serious tone, like no personality at all.
[10:30] SPEAKER: - I think it's very serious.
[10:34] SPEAKER: Jay and Silent Bob aren't there.
[10:36] SPEAKER: - Yeah.
[10:36] SPEAKER: - They had a King of the Hill mode,
[10:37] SPEAKER: but it does not feature Hank and Bobby Hill
[10:39] SPEAKER: in their new rebooted Hulu Plus series.
[10:42] SPEAKER: - I didn't even mean that so much as like, you know,
[10:44] SPEAKER: at least 2142 had a little bit of a futuristic angle.
[10:46] SPEAKER: Like the ones that are just here's present day
[10:49] SPEAKER: military technology and modern uniforms
[10:52] SPEAKER: and it's just real life or I kinda was over that
[10:57] SPEAKER: 10 plus years ago.
[11:00] SPEAKER: - So the weapons are all fake versions of real weapons.
[11:06] SPEAKER: They do have stuff, like they do have future tech
[11:09] SPEAKER: in the like skill trees, right?
[11:12] SPEAKER: So like, I don't know.
[11:16] SPEAKER: But basically the missiles are fire and forget, aim it,
[11:19] SPEAKER: you have to deal with drop or lock on to air targets
[11:22] SPEAKER: and then they can fire flares.
[11:24] SPEAKER: There's no like space laser or anything like that,
[11:28] SPEAKER: if that's what you're asking.
[11:29] SPEAKER: - I would describe this as a classic mainline battlefield.
[11:32] SPEAKER: - Okay, all right, sure.
[11:34] SPEAKER: - I don't know if they're using real countries.
[11:35] SPEAKER: I haven't sussed that out yet on the,
[11:38] SPEAKER: I keep meaning to check the load screens
[11:39] SPEAKER: to see if they have place names
[11:41] SPEAKER: or if they're making up fake countries in the Middle East
[11:43] SPEAKER: so that, you know.
[11:46] SPEAKER: But it looks like PMC versus military is the battle,
[11:49] SPEAKER: which seems ripped from the headlines.
[11:51] SPEAKER: - It sure does.
[11:52] SPEAKER: - Yeah, you know what else is ripped from the headlines?
[11:55] SPEAKER: - What's that?
[11:56] SPEAKER: - Buy-in appliances.
[11:58] SPEAKER: - Sure.
[11:59] SPEAKER: - I guess we have a two for a day.
[12:00] SPEAKER: - Everybody's doing it.
[12:01] SPEAKER: Yes, this is, we're reporting a little late this week.
[12:03] SPEAKER: We have a two for things have been going on.
[12:05] SPEAKER: - Yeah, I went to Super Nintendo World.
[12:07] SPEAKER: We're gonna talk about that and the tech that is there
[12:10] SPEAKER: 'cause they did some neat stuff and I wanna,
[12:12] SPEAKER: I would like to compare and contrast that
[12:14] SPEAKER: with the Star Wars land of Batuu in Disneyland.
[12:17] SPEAKER: - All right, that sounds fun.
[12:19] SPEAKER: - But yeah, I wanna hear about your
[12:22] SPEAKER: your appliance buying adventures first.
[12:26] SPEAKER: - I bought an appliance for the first time in my life.
[12:28] SPEAKER: I've just never, I've rented since I became an adult.
[12:31] SPEAKER: - You never bought a microwave oven?
[12:33] SPEAKER: - Yeah, but I don't think I count that.
[12:35] SPEAKER: - Okay, major appliance.
[12:37] SPEAKER: - Anything that could be like delivered normally from Amazon
[12:39] SPEAKER: I feel like is not in the scope here.
[12:43] SPEAKER: I'm talking something that's too big for one person to carry.
[12:46] SPEAKER: - Okay, that makes sense.
[12:47] SPEAKER: - And something that you're potentially gonna have
[12:48] SPEAKER: for a very long time.
[12:49] SPEAKER: Although, I mean, again, it's not my fridge.
[12:51] SPEAKER: We just rent, but our fridge randomly crapped out last week.
[12:55] SPEAKER: - What happened to it?
[12:56] SPEAKER: - And I didn't bother to deduce.
[13:00] SPEAKER: - Did the freezer stay cold and the top stay?
[13:02] SPEAKER: - Freezer stayed cold, but not cold enough.
[13:06] SPEAKER: The inside, okay, I'll just walk you
[13:08] SPEAKER: through the whole thing.
[13:09] SPEAKER: - Yeah, paint us a word picture, Brad.
[13:11] SPEAKER: - The, at some point it was definitely,
[13:13] SPEAKER: I knew it to be an older fridge.
[13:15] SPEAKER: I'd never bothered to try to figure out how old
[13:16] SPEAKER: until all this went down.
[13:18] SPEAKER: But the compressor like Tuesday-ish
[13:21] SPEAKER: started making some noises, let's say.
[13:24] SPEAKER: - Oh, bad noises.
[13:25] SPEAKER: - It was making like a clicking, grinding kind of sound.
[13:27] SPEAKER: - Yep, that'll happen.
[13:29] SPEAKER: - Getting increasingly angrier sounding.
[13:33] SPEAKER: And I just ignored it.
[13:35] SPEAKER: - Yeah, that's what it does.
[13:35] SPEAKER: - I was like, that's probably not great, but like.
[13:38] SPEAKER: - This is the benefit of renting, Brad.
[13:40] SPEAKER: Is it like, you hear a noise like that?
[13:41] SPEAKER: I hear a noise like that, panic sets into my heart.
[13:45] SPEAKER: 'Cause I'm like, I'm about to spend a lot of money.
[13:46] SPEAKER: You hear a noise like that,
[13:47] SPEAKER: you're like, that's somebody else's problem.
[13:49] SPEAKER: - Well, but yes, but it's both the benefit
[13:51] SPEAKER: and the curse of renting though,
[13:52] SPEAKER: because the thing I don't like is that
[13:55] SPEAKER: there's overhead involved.
[13:56] SPEAKER: There are other people in the chain
[13:57] SPEAKER: of decision-making involved, like.
[13:59] SPEAKER: - Oh yeah.
[14:00] SPEAKER: - The advantage you have as a homeowner
[14:01] SPEAKER: is that when it dies,
[14:02] SPEAKER: you don't have to wait for anybody else to sign off
[14:04] SPEAKER: or wait for them to get a refrigerator ordered
[14:06] SPEAKER: or you know what I mean?
[14:07] SPEAKER: - Yeah, the downside is that I have to write a check.
[14:09] SPEAKER: It's not like I can call the bank and be like,
[14:11] SPEAKER: hey, can I knock off two grand for a new refrigerator
[14:14] SPEAKER: for my mortgage payment this month?
[14:16] SPEAKER: - Well, okay, we'll get to it.
[14:17] SPEAKER: But let's say the budget for our new fridge
[14:19] SPEAKER: was far, far lower than two grand.
[14:23] SPEAKER: - I mean, the entry point for new fridges
[14:26] SPEAKER: is like $1,200, $1,300 it seems like now.
[14:29] SPEAKER: - Nope, nope, not even close.
[14:30] SPEAKER: - Oh, okay, nevermind.
[14:31] SPEAKER: - Not even half that.
[14:32] SPEAKER: - Oh, you've got a hose then.
[14:33] SPEAKER: - Oh, whatever, it's perfectly suitable for the space.
[14:37] SPEAKER: But it was making a bad noise.
[14:41] SPEAKER: And I was like, it'll probably be fine.
[14:42] SPEAKER: I don't want to have to deal with
[14:44] SPEAKER: contacting somebody about this.
[14:46] SPEAKER: - Yeah.
[14:46] SPEAKER: - It'll probably be fine.
[14:48] SPEAKER: By Wednesday night though,
[14:49] SPEAKER: the noise had gotten loud enough that it occurred to me.
[14:51] SPEAKER: And also I had some yogurt and I was like,
[14:54] SPEAKER: this doesn't seem quite as cold as it used to be.
[14:57] SPEAKER: - Uh-oh.
[14:58] SPEAKER: - And decided to put a thermometer in there,
[15:02] SPEAKER: 55 degrees Fahrenheit.
[15:03] SPEAKER: - That's too warm for a fridge.
[15:05] SPEAKER: - It sure is.
[15:06] SPEAKER: - You want your fridge to be 40-ish.
[15:07] SPEAKER: - Yeah, so we've talked,
[15:09] SPEAKER: we've kind of talked weirdly a lot about food safety
[15:12] SPEAKER: and spoilage and bacterial growth on this podcast,
[15:15] SPEAKER: but it's always been in a bit of a flippant manner I found.
[15:18] SPEAKER: - Look, I have long said that every single human being
[15:22] SPEAKER: should have to take some aspect of microbiology
[15:25] SPEAKER: as it pertains to food safety,
[15:27] SPEAKER: because most people make some real weird assumptions
[15:31] SPEAKER: about what makes food go bad.
[15:33] SPEAKER: And it would be really helpful
[15:34] SPEAKER: if everybody understood the actual mechanism.
[15:37] SPEAKER: So then they're much less likely to poison themselves
[15:39] SPEAKER: by leaving an egg out overnight and then eating it.
[15:42] SPEAKER: - Yeah, oh God, I had to research how eggs are handled
[15:45] SPEAKER: in this country and whether, anyway, we'll get to that.
[15:47] SPEAKER: We're stupid with eggs here just 'cause we don't like poop.
[15:50] SPEAKER: - Yes, but now it is time to talk frankly
[15:52] SPEAKER: and seriously about the guidance here,
[15:53] SPEAKER: because I've had to do a crash course and all that stuff.
[15:57] SPEAKER: My assumptions were not too far off the mark,
[15:59] SPEAKER: but I was definitely a little bit looser
[16:01] SPEAKER: than the recommendations, which are,
[16:05] SPEAKER: it needs to be below 40 Fahrenheit
[16:06] SPEAKER: in there kind of all the time.
[16:08] SPEAKER: There's really not much of a grace period at all.
[16:10] SPEAKER: - You actually want it to be,
[16:12] SPEAKER: you want it to be a little bit lower
[16:14] SPEAKER: so that when you open the door and close it,
[16:15] SPEAKER: the recovery period takes you back to 40, not above 40.
[16:19] SPEAKER: - Or below 40, right, like a 38 it seems like
[16:22] SPEAKER: is what I saw is the general recommendation.
[16:26] SPEAKER: - It depends on the fridge.
[16:27] SPEAKER: Like our fridge, if we have it 38
[16:29] SPEAKER: at the bottom in the front,
[16:30] SPEAKER: the top where the air comes out of the freezer
[16:33] SPEAKER: will freeze whatever's up there solid, so anyway.
[16:37] SPEAKER: - And zero degrees Fahrenheit in the freezer,
[16:40] SPEAKER: which surprised me 'cause I would think that like
[16:42] SPEAKER: kind of anything south of the freezing point
[16:44] SPEAKER: would be adequate, but.
[16:45] SPEAKER: - Again, it's about the recovery period.
[16:48] SPEAKER: You don't want stuff to thaw and freeze
[16:49] SPEAKER: and thaw and freeze.
[16:50] SPEAKER: You want it to be cold enough that when you open the door
[16:51] SPEAKER: and look in there for a minute, it doesn't thaw everything.
[16:54] SPEAKER: - Yeah, so the freezer in the shitty fridge
[16:57] SPEAKER: was actually holding about 10.
[16:59] SPEAKER: - Okay, so that stuff's probably fine.
[17:01] SPEAKER: - Yeah, yeah, so that's the, we'll get to it.
[17:03] SPEAKER: That's the only food we did not lose.
[17:04] SPEAKER: - Okay, you probably have some mustard in there
[17:07] SPEAKER: that's okay, maybe pickles.
[17:09] SPEAKER: - We saved some ketchup.
[17:10] SPEAKER: - Okay.
[17:11] SPEAKER: - That's about it, but whatever.
[17:13] SPEAKER: It's still a non-starter with the main fridge compartment
[17:16] SPEAKER: at 55.
[17:17] SPEAKER: - Yeah, no.
[17:19] SPEAKER: - So long story short, I contacted the landlord
[17:23] SPEAKER: and you tell me if this was a good move or not.
[17:26] SPEAKER: I volunteered to handle the acquisition
[17:29] SPEAKER: and selection of the new fridge.
[17:31] SPEAKER: - Well, so I thought that was a good idea
[17:33] SPEAKER: until a few minutes ago when you were describing
[17:36] SPEAKER: your budget range, which gave me pause
[17:38] SPEAKER: because yeah, you're in contractor territory
[17:42] SPEAKER: when you're south of two grand in San Francisco these days.
[17:44] SPEAKER: - They were looking to come in around $600
[17:47] SPEAKER: before any taxes and delivery fees.
[17:51] SPEAKER: - Do they even sell fridges for $600?
[17:53] SPEAKER: - Oh yeah, oh yeah.
[17:54] SPEAKER: - Does it have an ice maker or anything?
[17:56] SPEAKER: - No, no, this is the most zero frills price range
[18:01] SPEAKER: category of refrigerator product you can imagine.
[18:03] SPEAKER: - Did you have an ice maker before?
[18:05] SPEAKER: - No, we didn't have any of that stuff.
[18:06] SPEAKER: - Okay.
[18:07] SPEAKER: - It was a very basic, I mean, it's an apartment
[18:09] SPEAKER: and also it's a pretty small space.
[18:10] SPEAKER: There's a cabinet overhang that is 65 inches,
[18:14] SPEAKER: which it turns out there are not a lot of upright fridges
[18:16] SPEAKER: that fit in that space anyway.
[18:18] SPEAKER: - How big is this?
[18:19] SPEAKER: Is this like an 18 cubic foot fridge?
[18:21] SPEAKER: - It was 17.5, which is, but our old one was 15.8.
[18:24] SPEAKER: So this is still in that space, yeah.
[18:27] SPEAKER: - Do you pay for electricity in your unit
[18:28] SPEAKER: or does he pay for electricity?
[18:29] SPEAKER: - Yes, yes, we do.
[18:30] SPEAKER: - Did you get one that is okay?
[18:32] SPEAKER: - It's Energy Star, we'll get to the one we got.
[18:34] SPEAKER: - Okay, okay.
[18:35] SPEAKER: - But I think it's a net gain overall,
[18:37] SPEAKER: but I went into the fridge after all this was going down.
[18:41] SPEAKER: It was bought in 2003.
[18:43] SPEAKER: - Yeah, I mean, fridges last a long time.
[18:45] SPEAKER: - But yes, so like at first 2003 struck me as like,
[18:48] SPEAKER: man, this thing is probably ready to go.
[18:50] SPEAKER: But then my parents' fridge, nice like upstairs fridge
[18:53] SPEAKER: is like 25 years old.
[18:55] SPEAKER: - So our fridge-
[18:56] SPEAKER: - And my grandma's old fridge is in the basement,
[18:59] SPEAKER: which is from well over 40 years, I think.
[19:02] SPEAKER: - Well, so there's a time on appliances,
[19:06] SPEAKER: especially now as we've gotten better at making stuff
[19:08] SPEAKER: and stuff gets a little bit more efficient,
[19:11] SPEAKER: right up until the point at which we killed
[19:12] SPEAKER: the Energy Star program and the ability
[19:14] SPEAKER: to track that stuff a few months ago,
[19:17] SPEAKER: where keeping old appliances that run on electricity
[19:21] SPEAKER: is probably costing you more than you would say,
[19:23] SPEAKER: than you would save.
[19:25] SPEAKER: - That's probably true.
[19:26] SPEAKER: - Keeping an 80s refrigerator at this point,
[19:28] SPEAKER: A, is not gonna be,
[19:29] SPEAKER: unless you've replaced the seals and everything,
[19:31] SPEAKER: it's gonna be leaky, so that means it's gonna run
[19:33] SPEAKER: all the time, it means it's gonna use a ton of electricity.
[19:37] SPEAKER: But, okay, so first off, I wanna share,
[19:40] SPEAKER: I wanna like, I've been looking for a refrigerator
[19:43] SPEAKER: for a long time.
[19:44] SPEAKER: - Oh.
[19:45] SPEAKER: - The space that they made in the custom cabinetry
[19:48] SPEAKER: in our cabinets fits like four models of refrigerator.
[19:52] SPEAKER: - Yeah, that's kind of where we were at.
[19:54] SPEAKER: - Yeah, it's like, damn the people to hell
[19:58] SPEAKER: who decided to do this.
[19:59] SPEAKER: And also because our fridge is right up against the wall,
[20:02] SPEAKER: it has to have a specific kind of hinge
[20:04] SPEAKER: or else you won't be able to open the left side at all,
[20:08] SPEAKER: because it hits the, like, if the hinge pokes out
[20:11] SPEAKER: past the edge of the thing,
[20:12] SPEAKER: like what if it was hanging out with cabinets
[20:14] SPEAKER: on either side, it would be no problem.
[20:16] SPEAKER: But with the wall there, if the door opens the wrong way,
[20:20] SPEAKER: then the door will only open like 30 degrees
[20:23] SPEAKER: and that is obviously bad, so.
[20:25] SPEAKER: - Yeah.
[20:26] SPEAKER: - Anyway.
[20:27] SPEAKER: - Yeah, this experience, we've also got some stuff
[20:28] SPEAKER: in the floor that limits the range of door motion here.
[20:31] SPEAKER: This whole experience, if and when I ever own a home,
[20:34] SPEAKER: I think I'm sold on the, like,
[20:36] SPEAKER: as freestanding a refrigerator as possible concept.
[20:39] SPEAKER: - Yeah, just put it in the middle of the room.
[20:40] SPEAKER: - Yep, that's right.
[20:41] SPEAKER: - Just worship it.
[20:44] SPEAKER: - All right, so this brings us to Friday
[20:48] SPEAKER: when the temperature in the fridge had been above 50 degrees
[20:51] SPEAKER: for over two days.
[20:53] SPEAKER: - Also, I gotta say, I'm shocked
[20:55] SPEAKER: that there are $600 fridges in A, I know what you pay
[20:59] SPEAKER: for rent and it's a little offensive
[21:01] SPEAKER: that he's gonna hit you for, yeah, get a $600 fridge
[21:04] SPEAKER: with no ice maker, water, any of that nonsense.
[21:07] SPEAKER: - I'm of two minds on that stuff
[21:09] SPEAKER: because every single person, I mean, like,
[21:11] SPEAKER: I think almost every refrigerator I have come across ever
[21:13] SPEAKER: that has water and ice dispensers in it,
[21:16] SPEAKER: one of those things is broken.
[21:18] SPEAKER: - Like, I've had those for the last 30 years, Brad,
[21:20] SPEAKER: and I've never had a problem with them.
[21:22] SPEAKER: - I mean, that's a data point of one.
[21:24] SPEAKER: - Okay.
[21:25] SPEAKER: - Like, I am telling you, I have run
[21:26] SPEAKER: into so many broken ice makers in refrigerators.
[21:29] SPEAKER: Like, I'm kind of, it's the old TV/VCR combo problem.
[21:34] SPEAKER: Like, I don't like combining a lot of functionality
[21:37] SPEAKER: into one unit because the more things it can break on there,
[21:40] SPEAKER: the harder it gets to maintain.
[21:41] SPEAKER: - I mean, okay, so in fairness,
[21:43] SPEAKER: I have replaced an ice maker before,
[21:45] SPEAKER: but it was like a $70 part that took 15 minutes to swap out.
[21:49] SPEAKER: So it's not like it was a hard-
[21:51] SPEAKER: - That's fine, but whatever, I can fill up an ice tray.
[21:53] SPEAKER: I'm not worried about that.
[21:54] SPEAKER: - Wow.
[21:55] SPEAKER: - But we gotta talk about throwing out the food.
[21:58] SPEAKER: - Yeah.
[21:59] SPEAKER: - 'Cause it very, like I said, it very quickly became clear
[22:02] SPEAKER: we were not keeping anything
[22:03] SPEAKER: that had not been in the freezer.
[22:05] SPEAKER: - You just put on Too Good To Go and call it a day?
[22:08] SPEAKER: - Sure.
[22:09] SPEAKER: - No, do you have a compost bin?
[22:12] SPEAKER: - Yeah, there is a bin downstairs.
[22:13] SPEAKER: It was a scene, man.
[22:16] SPEAKER: We are not that far removed from our last Costco run.
[22:20] SPEAKER: - Oh no.
[22:21] SPEAKER: - So there were like, there were jumbo economy-sized
[22:24] SPEAKER: containers of, let's see, there was a big thing of kimchi
[22:28] SPEAKER: that had just opened and it had like one serving from.
[22:31] SPEAKER: - Kimchi's probably okay, actually.
[22:32] SPEAKER: - Everything said refrigerate
[22:34] SPEAKER: after opening, refrigerate, refrigerate.
[22:36] SPEAKER: Like we just decided to, we decided to go zero tolerance,
[22:41] SPEAKER: clean slate, let's not risk it.
[22:43] SPEAKER: - I mean, I will say having had bad food poisoning,
[22:49] SPEAKER: it's like, yeah, also your landlord should pay
[22:51] SPEAKER: for replacing the food.
[22:53] SPEAKER: - Yeah, well, we'll see how that goes.
[22:55] SPEAKER: - Yeah.
[22:57] SPEAKER: - Anyway, there was one point though,
[23:00] SPEAKER: it was like a giant thing of sauerkraut,
[23:01] SPEAKER: a giant thing of kimchi.
[23:04] SPEAKER: God, I'm trying to think what else.
[23:05] SPEAKER: - A lot of fermented cabbage in your life these days,
[23:06] SPEAKER: huh, Brad?
[23:07] SPEAKER: - Pickles, there was a whole thing of pickles
[23:09] SPEAKER: that we had barely gotten into.
[23:10] SPEAKER: - I think pickles are probably,
[23:11] SPEAKER: I would have kept the pickles.
[23:13] SPEAKER: - I considered that for all of the fermented stuff,
[23:15] SPEAKER: but they all, the wording on all the labels
[23:17] SPEAKER: was direct enough that I just decided it was not worth,
[23:21] SPEAKER: it was not worth saving the 15 to 20 bucks on that stuff.
[23:24] SPEAKER: But my girlfriend was handling a lot of that disposal.
[23:28] SPEAKER: And at one point she just dumped all that stuff
[23:30] SPEAKER: into the sink.
[23:31] SPEAKER: - Yeah.
[23:32] SPEAKER: - And I had to take a picture of it
[23:33] SPEAKER: 'cause it looked like weirdly artistic.
[23:35] SPEAKER: - Well, that's show art.
[23:35] SPEAKER: - There was something weirdly artsy
[23:39] SPEAKER: about the look of like this giant bed of kimchi
[23:42] SPEAKER: and then this layer of sauerkraut
[23:44] SPEAKER: and this pile of pickles.
[23:45] SPEAKER: - There's probably somebody on TikTok
[23:47] SPEAKER: who makes like portraits of people
[23:49] SPEAKER: using fermented cabbage dishes.
[23:52] SPEAKER: I bet that smelled good.
[23:54] SPEAKER: - It was pungent.
[23:55] SPEAKER: - It was pungent from all the way down
[23:57] SPEAKER: the other end of the house.
[23:59] SPEAKER: - Yeah.
[24:00] SPEAKER: - Anyway, the food disposal was a whole thing,
[24:02] SPEAKER: but again, we just decided to treat it
[24:03] SPEAKER: as kind of a clean slate.
[24:04] SPEAKER: Let's just start over, buy all new stuff.
[24:07] SPEAKER: So here we are.
[24:08] SPEAKER: - Yeah.
[24:09] SPEAKER: - Anyway, on the fridge selection.
[24:11] SPEAKER: - Yeah, so I was gonna say,
[24:12] SPEAKER: like if you had like a real budget to do this,
[24:14] SPEAKER: I can imagine that the fridge selection
[24:16] SPEAKER: is fraught and difficult.
[24:18] SPEAKER: At the budget he gave you,
[24:19] SPEAKER: I imagine there's like three choices
[24:21] SPEAKER: and they're all kind of crappy.
[24:22] SPEAKER: - There were actually quite a few choices.
[24:24] SPEAKER: Again, it was the cabinet overhang overhead
[24:26] SPEAKER: being so low that it was the actual heating factor.
[24:28] SPEAKER: - Yep, that always sucks.
[24:29] SPEAKER: - It was not the price
[24:30] SPEAKER: because there were quite a few models
[24:31] SPEAKER: and they were fuzzy.
[24:33] SPEAKER: They sent me one suggestion that was 650
[24:37] SPEAKER: and I think they would have wiggled a little bit
[24:40] SPEAKER: on a better model.
[24:41] SPEAKER: But again, what I ended up doing
[24:43] SPEAKER: was just filtering by height
[24:45] SPEAKER: and that got it down to not very many models, it turned out.
[24:49] SPEAKER: 'Cause there were like so many models
[24:51] SPEAKER: that were like two inches too tall.
[24:53] SPEAKER: Like it was such a small margin, but anyway.
[24:55] SPEAKER: - A little bit dremel.
[24:56] SPEAKER: (laughs)
[24:57] SPEAKER: - I did look at the bottom of that overhang
[24:59] SPEAKER: and I was like,
[25:00] SPEAKER: I bet you can take a couple inches off that beam.
[25:01] SPEAKER: - Yeah, it's hard to do.
[25:02] SPEAKER: It turns out without it looking real janky.
[25:06] SPEAKER: - I talked to Vinny and Alex at Nexlander
[25:08] SPEAKER: about it a little bit
[25:09] SPEAKER: 'cause they're both homeowners
[25:10] SPEAKER: and I got a couple of recommendations
[25:12] SPEAKER: that they have gotten in the past
[25:14] SPEAKER: that they passed along that I thought were interesting.
[25:15] SPEAKER: - Okay.
[25:16] SPEAKER: - The one Alex had been told
[25:19] SPEAKER: was focus on brands that just make appliances
[25:23] SPEAKER: versus brands that make everything.
[25:26] SPEAKER: - That used to be true.
[25:27] SPEAKER: I don't know that I necessarily agree with that anymore.
[25:29] SPEAKER: - So the brands that just make appliances
[25:31] SPEAKER: are like Whirlpool and Maytag.
[25:33] SPEAKER: - It's Western brands versus Eastern brands typically
[25:35] SPEAKER: 'cause the Eastern brands
[25:37] SPEAKER: are generally vertically integrated
[25:38] SPEAKER: across a wide variety of industries.
[25:40] SPEAKER: - Right, and the other category
[25:41] SPEAKER: is stuff like Samsung and LG that makes TVs and everything.
[25:45] SPEAKER: - So the thing about Whirlpool and Maytag
[25:49] SPEAKER: are all owned by one company now.
[25:51] SPEAKER: - Oh, I didn't know that.
[25:52] SPEAKER: - So yeah, I learned this when I bought a hot water heater.
[25:54] SPEAKER: There was a Maytag hot water heater
[25:56] SPEAKER: that I thought was a nice expensive one
[25:57] SPEAKER: and it turns out it's just a world shitty janky one
[26:00] SPEAKER: with the same badge on it.
[26:02] SPEAKER: - Good to know.
[26:07] SPEAKER: - The thing I would say is generally speaking,
[26:09] SPEAKER: especially if you're spending your own money,
[26:10] SPEAKER: go to someplace that actually sells those appliances
[26:13] SPEAKER: like that specializes in appliances, not Best Buy.
[26:17] SPEAKER: And then I like to ask the repair guys.
[26:21] SPEAKER: So for example, when our fridge conked out,
[26:24] SPEAKER: I asked the repair guy who came to fix the fridge
[26:26] SPEAKER: what his favorite brand of fridge was,
[26:28] SPEAKER: which ones he doesn't see.
[26:30] SPEAKER: And he's like, oh, here are the ones that I like for that.
[26:32] SPEAKER: - Kind of like which one would you buy for yourself?
[26:34] SPEAKER: - Yeah, which one do you have?
[26:35] SPEAKER: - Although if he recommends you one
[26:37] SPEAKER: that doesn't need a lot of repairs,
[26:38] SPEAKER: that's less repair work for him.
[26:40] SPEAKER: - I mean, true, true.
[26:43] SPEAKER: But it's worked really well on the hot water heater front.
[26:46] SPEAKER: The hot water heater guys were like,
[26:47] SPEAKER: yeah, don't buy these brands.
[26:49] SPEAKER: They're all the same thing.
[26:50] SPEAKER: They're just rebadged and when they have a problem,
[26:51] SPEAKER: they all have the same problem.
[26:53] SPEAKER: - Yeah, we ended up with an LG
[26:54] SPEAKER: because it's what fits the space.
[26:58] SPEAKER: It was the biggest internal capacity we could get
[27:00] SPEAKER: that would fit in that small height.
[27:02] SPEAKER: - Yeah.
[27:03] SPEAKER: - But the thing that Vinnie said he has heard
[27:06] SPEAKER: is that these days it's the very, very cheap fridges
[27:11] SPEAKER: and the very, very expensive ones that last forever.
[27:14] SPEAKER: It's the mid range.
[27:15] SPEAKER: - I think that's probably right.
[27:16] SPEAKER: - It's the mid range that are not too expensive
[27:19] SPEAKER: but have a ton of features crammed into them
[27:21] SPEAKER: or the ones that are constantly breaking down.
[27:23] SPEAKER: - It's the Terry Pratchett work boot theory, right?
[27:26] SPEAKER: If you can afford the,
[27:27] SPEAKER: you either buy the cheap one 50 times,
[27:30] SPEAKER: but I think that these days the cheap one
[27:32] SPEAKER: is actually made for people like you who have,
[27:34] SPEAKER: like people who rent apartments and stuff like that
[27:37] SPEAKER: and don't want to be hassled.
[27:40] SPEAKER: Whereas the mid range stuff is aspirationally upgraded,
[27:44] SPEAKER: but kind of crappy.
[27:45] SPEAKER: And the prices on that is low enough
[27:47] SPEAKER: and I don't know what the margin is,
[27:48] SPEAKER: but like the number of features they pack in there,
[27:50] SPEAKER: but keep the price down probably means
[27:52] SPEAKER: that the quality of the product is lower, right?
[27:55] SPEAKER: - Well, or so for example,
[27:58] SPEAKER: our stove had a issue out of the gate
[28:01] SPEAKER: when we bought it a few years ago
[28:02] SPEAKER: and the repair guy came out and was like,
[28:03] SPEAKER: yeah, I've seen a lot of these.
[28:04] SPEAKER: They just did, they just had cold solders on the line,
[28:07] SPEAKER: which our Sony receivers had cold solders on the screens.
[28:12] SPEAKER: And is that an intentional choice
[28:13] SPEAKER: designed to make it last a limited period of time
[28:15] SPEAKER: before you have to upgrade it?
[28:16] SPEAKER: Or is that just somebody fucked up on the line
[28:19] SPEAKER: and there's no way to know, right?
[28:21] SPEAKER: - That's the old incompetence versus malice.
[28:23] SPEAKER: - Yeah, yeah, except for Sony has a real reputation
[28:27] SPEAKER: for doing cold solders.
[28:28] SPEAKER: So, you know, maybe a little from column A,
[28:31] SPEAKER: a little from column B.
[28:32] SPEAKER: - Yeah, sure.
[28:35] SPEAKER: - I like this theory a lot.
[28:36] SPEAKER: I think this one reads to me.
[28:40] SPEAKER: - Yeah, and one thing Vinny said
[28:41] SPEAKER: is that those super, super high end ones
[28:43] SPEAKER: are also just fridges.
[28:44] SPEAKER: Like those really, you know,
[28:46] SPEAKER: we're talking the like $7,000 fridges
[28:48] SPEAKER: for the wealthy or whatever,
[28:49] SPEAKER: but like the high end. - Sub-zeros
[28:51] SPEAKER: and all that stuff, yeah.
[28:52] SPEAKER: - At the high end, a lot of them
[28:53] SPEAKER: are also just basic fridges with a bunch of frills
[28:55] SPEAKER: because you just want a thing that is quality
[28:57] SPEAKER: and does its job well.
[28:58] SPEAKER: - So honestly, this is what's kept us
[29:00] SPEAKER: from upgrading our fridge.
[29:02] SPEAKER: 'Cause like when the ice maker conked out,
[29:05] SPEAKER: I looked at it, I was like,
[29:06] SPEAKER: am I gonna spend 70 bucks on a new ice maker
[29:07] SPEAKER: or am I just gonna spend 1200 on a new fridge?
[29:11] SPEAKER: And then I looked at what the new fridge is,
[29:13] SPEAKER: what the like 1200 to $2,000,
[29:15] SPEAKER: I mean, what was 1200 then and now is probably two grand,
[29:18] SPEAKER: what those fridges, what those fridges,
[29:21] SPEAKER: what you get in those.
[29:23] SPEAKER: And it's in a invariably like high complexity.
[29:26] SPEAKER: So we like an ice maker
[29:27] SPEAKER: and we like water in the fridge with a filter.
[29:32] SPEAKER: And getting, they moved the ice makers out of the freezers
[29:37] SPEAKER: 'cause they're less convenient.
[29:38] SPEAKER: 'Cause people wanted ice in the door.
[29:42] SPEAKER: And as a result,
[29:43] SPEAKER: you have these really complicated ice makers
[29:44] SPEAKER: that either shuttle ice up from the freezer
[29:47] SPEAKER: down to the front,
[29:49] SPEAKER: or it takes up all of one door with an ice maker
[29:53] SPEAKER: that is less efficient and prone to clogging
[29:57] SPEAKER: and all this stuff that just sucks.
[30:00] SPEAKER: So-
[30:00] SPEAKER: - Yeah, I am, like I said,
[30:02] SPEAKER: this is my first appliance purchase or selection process.
[30:04] SPEAKER: I'm getting a taste of what I will be like as a homeowner.
[30:07] SPEAKER: It's going to be minimalism and modularity all the way.
[30:11] SPEAKER: Like it's just going to be everything.
[30:13] SPEAKER: It's going to be the Unix philosophy applied to a house.
[30:16] SPEAKER: Like every tool has one job and it needs to do it well.
[30:19] SPEAKER: - Well, so I think you can get,
[30:21] SPEAKER: I mean, I think there are still good appliances
[30:23] SPEAKER: in these categories.
[30:24] SPEAKER: I think the problem is you're not gonna find them at Best Buy.
[30:27] SPEAKER: You're not gonna find them at Lowe's and Home Depot,
[30:29] SPEAKER: really in my experience.
[30:31] SPEAKER: So like washing machines and dryers are fine
[30:33] SPEAKER: to get at Home Depot and Lowe's.
[30:36] SPEAKER: Like I think actually we bought ours at Best Buy
[30:37] SPEAKER: 'cause they had a deal and they price matched.
[30:42] SPEAKER: I like buying something like a fridge
[30:44] SPEAKER: that's gonna stick with me for 20 years,
[30:47] SPEAKER: someplace that will swap it out for a different one
[30:49] SPEAKER: if I don't like it when I get there.
[30:51] SPEAKER: 'Cause the other big problem with a lot of this stuff
[30:53] SPEAKER: is that the user interface choices,
[30:55] SPEAKER: and I don't mean software,
[30:56] SPEAKER: I mean like how you interact with the device,
[30:59] SPEAKER: you're not going to realize, annoy the shit out of you
[31:01] SPEAKER: until it's too late if you buy it at Best Buy.
[31:04] SPEAKER: - There's already like three things about this one
[31:06] SPEAKER: that are like slightly more annoying than the old one,
[31:07] SPEAKER: but there are enough upsides to it that I'm calling it.
[31:11] SPEAKER: At least a breakeven if not a net gain.
[31:14] SPEAKER: - Well, more space is good, yeah.
[31:16] SPEAKER: - It's got more space,
[31:17] SPEAKER: but like the top shelf is weirdly limited
[31:19] SPEAKER: and can't be adjusted.
[31:20] SPEAKER: So our big, like you said,
[31:21] SPEAKER: we also like to keep a big water filter
[31:23] SPEAKER: pitcher thing in there.
[31:25] SPEAKER: That thing no longer fits on the top shelf,
[31:27] SPEAKER: which is a real bummer.
[31:28] SPEAKER: - Yeah, if you've got a fridge with water in it,
[31:30] SPEAKER: you'd not have this problem.
[31:31] SPEAKER: - I suppose that's the case maybe.
[31:33] SPEAKER: - So before people write in and tell me
[31:36] SPEAKER: that the water pipe to their fridge burst
[31:39] SPEAKER: and it caused them to flood their house,
[31:40] SPEAKER: I know it happens, I'm fine taking that risk.
[31:44] SPEAKER: - Yes, the biggest net gain, I'll just say it now,
[31:48] SPEAKER: just got a few more points to get through here,
[31:49] SPEAKER: but it is so much quieter than the old one.
[31:52] SPEAKER: And I think you've been in our apartment before, right?
[31:55] SPEAKER: Like our kitchen and our living room are directly adjacent
[31:58] SPEAKER: and there's not a door, it's like they had cut the wall out,
[32:00] SPEAKER: it's just completely open.
[32:02] SPEAKER: So the fridge is open air 15 feet away from me
[32:05] SPEAKER: when we're watching TV, playing games, whatever.
[32:09] SPEAKER: And even before the old fridge started getting very angry,
[32:12] SPEAKER: it was pretty loud when the compressor kicked on.
[32:14] SPEAKER: - Maybe that was a warning sign in retrospect.
[32:16] SPEAKER: - Maybe, cannot even hear this thing from the couch.
[32:19] SPEAKER: I literally, when it's running, cannot even hear it.
[32:20] SPEAKER: Like that alone is, yeah, that's a huge gain.
[32:25] SPEAKER: Anyway, I'll get to the last bit
[32:29] SPEAKER: of the selection stuff here.
[32:31] SPEAKER: It is an energy star and so that helps I'm sure
[32:35] SPEAKER: with the efficiency and the noise and stuff like that.
[32:37] SPEAKER: I got really excited though, once I was granted some agency
[32:40] SPEAKER: to pick this thing out myself within a budget.
[32:42] SPEAKER: - Okay.
[32:43] SPEAKER: - Because I've been kind of fascinated with the phenomenon
[32:45] SPEAKER: of the bottom freezer drawer.
[32:47] SPEAKER: - So we have a bottom freezer drawer
[32:49] SPEAKER: and I have mixed feelings about it, but go on.
[32:51] SPEAKER: - Yeah, so that's what I found
[32:52] SPEAKER: when I started looking into them.
[32:54] SPEAKER: I mean, first of all, I found that there were zero models
[32:57] SPEAKER: available that fit within our tight budget.
[32:59] SPEAKER: - Yeah, that's an upgrade feature at this point.
[33:01] SPEAKER: - Yes, that clearly was, I've quickly realized
[33:04] SPEAKER: that has been positioned as a luxury add-on.
[33:07] SPEAKER: - It also has more parts because the freezer on top
[33:10] SPEAKER: has, there has to be an impeller in the bottom ones
[33:15] SPEAKER: to get cold air from the freezer to the fridge.
[33:17] SPEAKER: - So this goes back to my minimalism
[33:19] SPEAKER: is that now that I've actually read about this,
[33:20] SPEAKER: I think that my dreams of bottom freezer
[33:24] SPEAKER: have been dashed for all time.
[33:26] SPEAKER: Because there are, I mean, it literally is less efficient.
[33:29] SPEAKER: Like you're gonna use more electricity.
[33:30] SPEAKER: The top freezer is common for a reason,
[33:35] SPEAKER: not just 'cause it's cheaper to make.
[33:36] SPEAKER: Like it's actually more efficient to operate the fridge.
[33:40] SPEAKER: I looked it up, the Department of Energy says
[33:42] SPEAKER: that classic top freezer models are 10 to 25%
[33:45] SPEAKER: more energy efficient than bottom freezer.
[33:48] SPEAKER: - That's crazy.
[33:49] SPEAKER: - Which is kind of a lot.
[33:51] SPEAKER: I wasn't, I couldn't find definitively the reason for that.
[33:54] SPEAKER: I found a couple of suggestions.
[33:56] SPEAKER: One suggestion I found is that there is a more natural
[33:59] SPEAKER: convection cycle of warm and cold air flowing
[34:02] SPEAKER: in the top freezer.
[34:03] SPEAKER: But I think those compartments are air tight.
[34:06] SPEAKER: So like-
[34:07] SPEAKER: - No, no, no.
[34:08] SPEAKER: The air moves from the freezer-
[34:10] SPEAKER: - Are the freezer and fridge connected?
[34:11] SPEAKER: - The way the fridge is cooled is there's a fan that moves
[34:14] SPEAKER: or there's a system that moves air from the cold freezer
[34:17] SPEAKER: to the refrigerator.
[34:21] SPEAKER: And it maintains the temperature by cycling the amount
[34:23] SPEAKER: of air that's allowed in and out.
[34:25] SPEAKER: But on the, because cold, because heat rises-
[34:28] SPEAKER: - Yeah, 'cause cold air, the cold air from the freezer
[34:30] SPEAKER: sinks into the fridge compartment.
[34:31] SPEAKER: - Naturally sinks.
[34:32] SPEAKER: - Yeah, the problem is on the downhill ones,
[34:34] SPEAKER: you have to have some sort of mechanism that brings air
[34:36] SPEAKER: from the cold bottom to the top.
[34:38] SPEAKER: - Yep, and that's just another thing to break.
[34:39] SPEAKER: So I guess I'll never have one.
[34:41] SPEAKER: - I will tell you on our fridge that did break
[34:43] SPEAKER: about 10 years after we bought the house.
[34:45] SPEAKER: And it cost, it was a classic $25 part hour of labor,
[34:51] SPEAKER: $400 worth of food that was ruined
[34:54] SPEAKER: because the fridge got warm and we didn't realize it
[34:56] SPEAKER: until we had a similar warm yogurt moment.
[34:59] SPEAKER: - No, thank you.
[35:01] SPEAKER: I also, I read elsewhere that it may also have to do
[35:03] SPEAKER: with the placement of the compressor
[35:05] SPEAKER: that on the top freezer models, the compressor is farther
[35:07] SPEAKER: away from the refrigerated compartments.
[35:10] SPEAKER: - Oh, that makes sense.
[35:11] SPEAKER: And on these it's below where it's gonna heat up probably.
[35:14] SPEAKER: - Right, because compressors generate heat, right?
[35:17] SPEAKER: - Yeah, yeah, yeah.
[35:18] SPEAKER: - So anyway, no more, no more, no more bottom freezer.
[35:22] SPEAKER: - So what I will say having had one of these bottom freezers
[35:26] SPEAKER: for like 10 years, we were side by side people
[35:27] SPEAKER: for years and years, which I quite like.
[35:29] SPEAKER: - Yeah, that's what my parents have.
[35:31] SPEAKER: - The bottom freezer lets you hold a lot more stuff
[35:35] SPEAKER: in your freezer and make it more accessible
[35:37] SPEAKER: if you're like, for example, when we make a soup
[35:41] SPEAKER: or something and freeze it, we put it into freezer bags
[35:44] SPEAKER: and lay them out flat so they freeze like hanging files.
[35:48] SPEAKER: - Sure.
[35:49] SPEAKER: - And then they go in there.
[35:50] SPEAKER: It's an enormous pain in the ass
[35:51] SPEAKER: if you have a lot of frozen vegetables.
[35:53] SPEAKER: So like we have frozen peas and stuff like that in there
[35:55] SPEAKER: or like smoothie frozen stuff and those bags just
[36:00] SPEAKER: like become amorphous blobs in the basket at the bottom.
[36:06] SPEAKER: I would much rather have this side by side
[36:08] SPEAKER: if I were doing it again.
[36:09] SPEAKER: This is one of the reasons, like I keep waiting.
[36:11] SPEAKER: One of the problems we have is because of where the wall is,
[36:15] SPEAKER: the side by side absolutely will not work
[36:18] SPEAKER: because of the hinges hitting the doors
[36:20] SPEAKER: and then the wall and all that stuff.
[36:22] SPEAKER: So anyway, I keep hoping somebody's gonna make a better
[36:25] SPEAKER: side by side hinge, but yeah, I like the fridge on top.
[36:31] SPEAKER: The fridge on top is incredibly convenient
[36:33] SPEAKER: when you're in there looking for stuff
[36:35] SPEAKER: when you're pulling stuff out.
[36:38] SPEAKER: It's funny 'cause our fridges from the time
[36:40] SPEAKER: before they started adding all the electronic crap
[36:42] SPEAKER: to the fridges, so like the bonus features for us
[36:46] SPEAKER: are like pull out drawers, pull out shelves.
[36:51] SPEAKER: So like you can grab the shelf and pull it out.
[36:56] SPEAKER: It's not, I don't know, it's weird.
[37:00] SPEAKER: The newer ones are much weirder, I think.
[37:02] SPEAKER: - Yeah, I could see that.
[37:03] SPEAKER: - And then you get like all this weird electronic crap
[37:04] SPEAKER: that you really don't need.
[37:06] SPEAKER: - I don't know that there are any circuit boards
[37:07] SPEAKER: in this one.
[37:08] SPEAKER: I mean, there's probably something-
[37:09] SPEAKER: - There are, yeah.
[37:09] SPEAKER: - There's probably something very basic, but very basic.
[37:11] SPEAKER: - Probably no IC.
[37:13] SPEAKER: - Okay, a couple other things real quick.
[37:15] SPEAKER: I mean, this is common to anybody who buys things online,
[37:19] SPEAKER: I guess these days, but appliances I feel like
[37:20] SPEAKER: are an extreme example.
[37:22] SPEAKER: Sifting through reviews for this was a complete mess.
[37:25] SPEAKER: - Well, part of the problem, the big problem
[37:27] SPEAKER: is there's no skews.
[37:28] SPEAKER: So we looked at this when we started testing.
[37:31] SPEAKER: Like Maytag and Whirlpool make separate skews
[37:33] SPEAKER: of the exact same refrigerator-
[37:35] SPEAKER: - For different retailers.
[37:36] SPEAKER: - With slightly different fascia on it.
[37:37] SPEAKER: Or Lowe's, Home Depot, Best Buy, Walmart,
[37:41] SPEAKER: all the places you can buy fridges.
[37:42] SPEAKER: - Yep.
[37:44] SPEAKER: - And it means that it's really, really hard to do reviews
[37:47] SPEAKER: because you can't often tell that they're the same part.
[37:50] SPEAKER: - And it's so that Home Depot can say,
[37:54] SPEAKER: oh yeah, we price match everything.
[37:56] SPEAKER: And then there's nothing to price match against
[37:57] SPEAKER: 'cause it's all different skews.
[37:59] SPEAKER: - Good stuff.
[38:00] SPEAKER: - Great.
[38:01] SPEAKER: - I went to Consumer Reports.
[38:03] SPEAKER: They wanted a subscription to show the review
[38:05] SPEAKER: for this refrigerator, but it was very unclear to me
[38:08] SPEAKER: based on the way they blurred the page out,
[38:09] SPEAKER: whether a human had even done a test on this refrigerator.
[38:13] SPEAKER: It kind of looked like what was being blurred out
[38:15] SPEAKER: was really not much more than the manufacturer's specs.
[38:19] SPEAKER: - So my experience when I buy,
[38:21] SPEAKER: I don't actually know how well
[38:23] SPEAKER: they cover this part of the market.
[38:26] SPEAKER: I know that when you're buying,
[38:28] SPEAKER: if you're spending 2,000,
[38:29] SPEAKER: like when I bought hot water heaters and stuff like that,
[38:31] SPEAKER: when I've had to spend a couple of grand on an appliance,
[38:33] SPEAKER: I usually shell out for a month or two of Consumer Reports
[38:37] SPEAKER: because they're generally pretty good.
[38:38] SPEAKER: And even if they don't have a review of a particular model,
[38:41] SPEAKER: they'll have reviews of other models from that vendor,
[38:43] SPEAKER: which kind of gives me a read on the situation.
[38:48] SPEAKER: - I will say, I think Consumer Reports is really good
[38:50] SPEAKER: at the kind of speeds and feeds side of reviewing,
[38:55] SPEAKER: like how energy efficient is it?
[38:56] SPEAKER: How much space does it have?
[38:57] SPEAKER: Does it have like convenient features,
[39:00] SPEAKER: like the pullout shelves or adjustable shelves
[39:02] SPEAKER: or stuff like that?
[39:03] SPEAKER: I don't think they're particularly good
[39:04] SPEAKER: at user experience stuff.
[39:06] SPEAKER: So like, for example, we bought a toaster oven one time,
[39:09] SPEAKER: I looked at the Consumer Reports review of it
[39:11] SPEAKER: and they were like, oh yeah, we absolutely love this.
[39:13] SPEAKER: And then I got it and it was the user interface
[39:16] SPEAKER: for the thing was unintelligible to humans.
[39:19] SPEAKER: And I was like, did you guys try to make a piece of toast
[39:21] SPEAKER: in this thing?
[39:22] SPEAKER: 'Cause I'm a reasonably smart person
[39:24] SPEAKER: and I can't figure it out.
[39:25] SPEAKER: So we took that one back and got a different one.
[39:27] SPEAKER: - All right.
[39:28] SPEAKER: Yeah, if it had been my fridge and my house,
[39:30] SPEAKER: I probably would have shelled out for the sub.
[39:32] SPEAKER: But also again, it didn't look like they had done a review.
[39:34] SPEAKER: And I think, like you said,
[39:36] SPEAKER: they probably are not covering this segment
[39:38] SPEAKER: of the market very intensively.
[39:41] SPEAKER: - I don't know, like I kind of wonder,
[39:42] SPEAKER: 'cause I feel like this is like the contractor side
[39:45] SPEAKER: of the market, right?
[39:46] SPEAKER: And I feel like those people do a lot of volume
[39:51] SPEAKER: and maybe, like, I don't know.
[39:52] SPEAKER: I'd be curious to find out.
[39:55] SPEAKER: Like I said, I don't really look at this.
[39:57] SPEAKER: I think of this as like a garage fridge, right?
[40:00] SPEAKER: - So we're getting to that, this thing is absolutely,
[40:02] SPEAKER: this is literally labeled as a garage ready fridge,
[40:05] SPEAKER: which I think might have some implications
[40:06] SPEAKER: on the thermodynamics of it.
[40:08] SPEAKER: And looking at user reviews,
[40:10] SPEAKER: absolutely the majority of people I think I saw
[40:13] SPEAKER: were using it as a garage fridge.
[40:14] SPEAKER: - Guys, let's put the beer.
[40:16] SPEAKER: - Yeah, that's right.
[40:17] SPEAKER: But, man, having a garage and hanging out in your garage
[40:21] SPEAKER: and drinking a beer in your garage sounds pretty good.
[40:25] SPEAKER: Anyway.
[40:25] SPEAKER: - Yeah, most of the guys I know that do that
[40:26] SPEAKER: in my neighborhood don't seem particularly happy though.
[40:28] SPEAKER: So maybe, you know.
[40:30] SPEAKER: - Fair, maybe not something to aspire to.
[40:34] SPEAKER: I went through a lot of user reviews on Lowe's
[40:36] SPEAKER: and Home Depot and that's by places that had them
[40:39] SPEAKER: and on LG sites, like the phenomenon of-
[40:41] SPEAKER: - Oh, I love that.
[40:42] SPEAKER: - Phenomenon of user reviews on the site made by the company
[40:47] SPEAKER: that makes the product is just often weird.
[40:49] SPEAKER: They're all five stars.
[40:50] SPEAKER: - Is that a, oh really?
[40:53] SPEAKER: I guess if you like a fridge enough to go
[40:56] SPEAKER: to the manufacturer's website and leave a review,
[40:58] SPEAKER: you either really love it or really hate it.
[41:00] SPEAKER: - Yeah, I don't know.
[41:01] SPEAKER: I guess they're legitimate.
[41:03] SPEAKER: But I can't remember which one of those retailers it was.
[41:06] SPEAKER: It might've been Home Depot.
[41:08] SPEAKER: A lot of the reviews were marked as influencer reviews
[41:11] SPEAKER: or part of some like pilot.
[41:13] SPEAKER: I can't remember how they phrased it.
[41:15] SPEAKER: It was part of some like pilot promotional influencer
[41:17] SPEAKER: type of program or something.
[41:18] SPEAKER: I mean, to their credit, I think all three of those sites
[41:22] SPEAKER: did mark legitimate purchases, verified purchases.
[41:24] SPEAKER: So you could filter by. - That's good.
[41:26] SPEAKER: - You could see who had actually just paid for the thing
[41:28] SPEAKER: and reviewed it.
[41:29] SPEAKER: - Who's doing influencer reviews of garage fridges?
[41:32] SPEAKER: - I can't remember exactly what the wording was on that,
[41:34] SPEAKER: but it was enough to make me think those reviews were maybe,
[41:37] SPEAKER: you know, it's kind of like the Amazon reviews
[41:40] SPEAKER: or even the Steam user reviews that are marked like,
[41:43] SPEAKER: oh, received as promotional product or whatever.
[41:45] SPEAKER: - Yeah, Amazon has been seeding reviews
[41:48] SPEAKER: with some like prime reviewers for years and years now.
[41:52] SPEAKER: - Yeah, and one of those retailers had the same user reviews
[41:56] SPEAKER: from the LG site and mixed in.
[41:57] SPEAKER: And at least again, they were labeled as
[42:00] SPEAKER: from the manufacturer's site,
[42:01] SPEAKER: but I thought that was another weird way to muddy up.
[42:04] SPEAKER: - Look, man, the home warehouse business is wild.
[42:07] SPEAKER: - Really, that's the impression I was getting.
[42:09] SPEAKER: Anyway, we'll wrap this up.
[42:10] SPEAKER: But yeah, so that LG we got is labeled as garage ready,
[42:14] SPEAKER: which I got the sense means it's rated to perform
[42:18] SPEAKER: in higher ambient temperature.
[42:20] SPEAKER: - It could be that it works
[42:22] SPEAKER: within a wider range of temperatures.
[42:24] SPEAKER: It could be that it's noisier.
[42:25] SPEAKER: It could be that it doesn't work well
[42:27] SPEAKER: in a cabinet in an enclosed space.
[42:30] SPEAKER: I think it's probably just marketing though,
[42:32] SPEAKER: that they're saying, hey, this is a fridge
[42:33] SPEAKER: you can put in your garage 'cause it's cheap.
[42:35] SPEAKER: - Well, part of that description said it's rated to work
[42:38] SPEAKER: in an ambient temperature up to a hundred Fahrenheit.
[42:40] SPEAKER: - I think that's probably normal fridge though, Joe.
[42:42] SPEAKER: - Some of the reviews, some of the user reviews
[42:44] SPEAKER: maybe disagree with that part a little bit, but I-
[42:47] SPEAKER: - It's been a hundred degrees in my house
[42:48] SPEAKER: when we've had a bad heat wave before.
[42:50] SPEAKER: - Yeah, and then last thing, this is,
[42:54] SPEAKER: I'm sure old hat for anybody who's ever bought a fridge.
[42:55] SPEAKER: I was surprised that it takes,
[42:57] SPEAKER: they said it takes 24 hours for it to be fully cold.
[43:00] SPEAKER: - Yeah.
[43:01] SPEAKER: - Because I have a thermometer in there
[43:02] SPEAKER: and like literally this thing seems very powerful.
[43:04] SPEAKER: That for like two hours, the freezer was reading minus 10.
[43:08] SPEAKER: - Well, yeah, but they-
[43:09] SPEAKER: - But there's nothing in there.
[43:10] SPEAKER: - The other stuff has to cool down and then, yeah.
[43:13] SPEAKER: - So is that, I was wondering,
[43:14] SPEAKER: is that that the actual like structure of the fridge
[43:17] SPEAKER: has to get cold as well?
[43:18] SPEAKER: - I think you're probably the first person
[43:19] SPEAKER: who's ever read those instructions, Brad.
[43:21] SPEAKER: - Well, the delivery guys also like stressed
[43:23] SPEAKER: on the way out the door.
[43:24] SPEAKER: They're like, hey, it's 24 hours
[43:25] SPEAKER: before it'll be all the way cold.
[43:27] SPEAKER: - Oh, there you go.
[43:28] SPEAKER: There's mass, it has mass.
[43:30] SPEAKER: - Right, like it's not that I'm worried about it.
[43:31] SPEAKER: I'm just curious what the physics of that are.
[43:33] SPEAKER: Like, I just like knowing how things work
[43:35] SPEAKER: and why they are the way they are.
[43:36] SPEAKER: I wondered if that meant that like parts
[43:38] SPEAKER: of the actual structure of the fridge
[43:40] SPEAKER: had to reach equilibrium.
[43:42] SPEAKER: - Is your thermometer metal?
[43:43] SPEAKER: - It is metal.
[43:44] SPEAKER: - Yeah, so the inside of the fridge is plastic, right?
[43:48] SPEAKER: - Yes.
[43:49] SPEAKER: - So metal conducts heat.
[43:50] SPEAKER: So the air to metal interface is gonna be way better
[43:53] SPEAKER: than the air to plastic interface is my guess.
[43:55] SPEAKER: - Of course, okay.
[43:56] SPEAKER: - Yeah.
[43:57] SPEAKER: - Good to know, all right.
[43:58] SPEAKER: - But you need a steel refrigerator
[44:00] SPEAKER: so then it cools down real fast.
[44:02] SPEAKER: And if you lick it, you'll stick to it.
[44:03] SPEAKER: - Okay, anyway.
[44:06] SPEAKER: - Yeah.
[44:07] SPEAKER: - I'm excited to have a refrigerator again.
[44:08] SPEAKER: Eating out for every meal actually
[44:09] SPEAKER: is not all it's cracked up to be.
[44:11] SPEAKER: - No, it sucks.
[44:12] SPEAKER: - Yeah.
[44:13] SPEAKER: - It's bad for you.
[44:14] SPEAKER: - I bet you ate out a lot at Super Nintendo World.
[44:17] SPEAKER: - So yeah, we went to Universal Hollywood,
[44:21] SPEAKER: which is like a small theme park
[44:24] SPEAKER: on the side of the North Hollywood Hills in Los Angeles.
[44:27] SPEAKER: We were down in Los Angeles for something else
[44:29] SPEAKER: and had an extra day and we were like,
[44:31] SPEAKER: hey, I wanna see Super Nintendo World,
[44:33] SPEAKER: which is the new addition to Universal's host
[44:36] SPEAKER: of theme parks, I guess.
[44:40] SPEAKER: That's the place where they have the Harry Potter world.
[44:42] SPEAKER: They have some Simpsons stuff.
[44:45] SPEAKER: They have Jurassic Park rides.
[44:48] SPEAKER: It's where Back to the Future used to be
[44:50] SPEAKER: before they got rid of that rip.
[44:53] SPEAKER: And the famous The Waterworld,
[44:55] SPEAKER: famously The Waterworld show is there
[44:56] SPEAKER: with the jet skis and the fire.
[44:58] SPEAKER: Yeah, I still haven't been.
[44:59] SPEAKER: - Nobody else in my family has any interest
[45:02] SPEAKER: in going to see The Waterworld show.
[45:03] SPEAKER: So I get hosed out of going every time.
[45:05] SPEAKER: - Did I hear, I should look this up.
[45:07] SPEAKER: After we did Waterworld for the Next Lander WatchCast
[45:10] SPEAKER: last fall, I will always remember it
[45:13] SPEAKER: because it was the night of the election.
[45:15] SPEAKER: - Oh God, that's grim.
[45:16] SPEAKER: - Which anyway, I thought I might've read
[45:19] SPEAKER: after we did that WatchCast and I was googling around
[45:22] SPEAKER: that that Waterworld attraction is like insanely popular.
[45:25] SPEAKER: - It fills up every time.
[45:26] SPEAKER: - Yeah.
[45:27] SPEAKER: - Yeah, you have to get in line for it.
[45:28] SPEAKER: For all of the iffy reputation of the movie
[45:31] SPEAKER: that that attraction is like actually one
[45:33] SPEAKER: of their most successful things.
[45:34] SPEAKER: - All I know is every time I've been there,
[45:36] SPEAKER: occasionally you see a big flare go up,
[45:39] SPEAKER: which I assume is the smokers seeing the swimmer.
[45:44] SPEAKER: - Are they doing like smokers and makeup and everything?
[45:46] SPEAKER: - I assume that they have Dennis Hopper's
[45:48] SPEAKER: animated corpse there.
[45:50] SPEAKER: - Man.
[45:51] SPEAKER: - But yeah, they jumped jet skis through rings of fire
[45:54] SPEAKER: in a giant tank, Brad.
[45:55] SPEAKER: Why would I not want to see that?
[45:56] SPEAKER: I might have to put that on my list anyway.
[45:58] SPEAKER: - If you want to go sometime,
[45:59] SPEAKER: let me know, I'll totally go down with you.
[46:00] SPEAKER: So.
[46:01] SPEAKER: - I'm having a word trip in the Ionic.
[46:03] SPEAKER: I'm gonna see if that thing goes on a, okay, anyway.
[46:05] SPEAKER: - Okay, so hold on, side note.
[46:07] SPEAKER: We drove, this is the first time we've done a long,
[46:09] SPEAKER: like more than one charge drive with the Ionic.
[46:11] SPEAKER: - Oh, I thought you had done LA trips.
[46:14] SPEAKER: - I haven't been to LA since we got that car really.
[46:16] SPEAKER: No, I've been down to the Valley a few times,
[46:19] SPEAKER: we went to Tahoe, but we charged, we left full,
[46:25] SPEAKER: charged at Harris Ranch, which is basically
[46:27] SPEAKER: the halfway point, and we got all the way to Santa Clarita
[46:30] SPEAKER: and had enough charge to get there with like 10%
[46:33] SPEAKER: to the hotel with 10% left.
[46:36] SPEAKER: - Okay, now.
[46:36] SPEAKER: - And then I had to pee, so we stopped at Walmart
[46:38] SPEAKER: and charged and peed for like five minutes,
[46:40] SPEAKER: but that was it.
[46:41] SPEAKER: - Was that getting white knuckle on the charge?
[46:43] SPEAKER: - No.
[46:44] SPEAKER: - When you were approaching 10%?
[46:45] SPEAKER: - No.
[46:45] SPEAKER: - That's a calculation of are we going to really
[46:47] SPEAKER: screw ourselves if we try to push this?
[46:49] SPEAKER: - 10% is 30 miles.
[46:50] SPEAKER: So I did, I called the hotel to make sure they had chargers
[46:54] SPEAKER: because if they didn't have like L2 chargers there,
[46:56] SPEAKER: I would have stopped and put more juice in it,
[46:59] SPEAKER: so I didn't have to fool with it the next day,
[47:01] SPEAKER: but yeah, no, it was good.
[47:03] SPEAKER: - How long did you have to charge at Harris Ranch?
[47:05] SPEAKER: - We charged for 25 minutes, I think.
[47:08] SPEAKER: Like we had stopped and picked up some food,
[47:11] SPEAKER: the kiddo went and sat and ate at a picnic bench,
[47:13] SPEAKER: I went to the barbecue place across the street,
[47:15] SPEAKER: grabbed a barbecue sandwich, ate half of that,
[47:17] SPEAKER: and we were ready to go.
[47:18] SPEAKER: - All right.
[47:19] SPEAKER: - Yeah, it was good.
[47:20] SPEAKER: - Sounds okay.
[47:21] SPEAKER: - It was good.
[47:23] SPEAKER: - Okay, so Universal Studios.
[47:26] SPEAKER: It's also worth mentioning, they have the studio tour there,
[47:29] SPEAKER: which is where you get on the studio tour bus,
[47:31] SPEAKER: like you're going to drive around the back lots
[47:32] SPEAKER: and they drive around the back lots a little bit
[47:34] SPEAKER: and then it turns out to be a fucking awesome ride.
[47:36] SPEAKER: - I like the thing from the wizard.
[47:38] SPEAKER: - I don't know, I've never seen the wizard.
[47:40] SPEAKER: - You're probably good, actually.
[47:42] SPEAKER: We did that for the watch cast as well,
[47:44] SPEAKER: and man, talk about movies that don't hold up.
[47:46] SPEAKER: - Is that the Fred Savage Nintendo one?
[47:47] SPEAKER: - Yes, that's the Fred Savage road trip across the country
[47:50] SPEAKER: to the Nintendo World Championship movie.
[47:52] SPEAKER: - Oh man.
[47:53] SPEAKER: - It's bad.
[47:54] SPEAKER: - Oh, that sucks.
[47:55] SPEAKER: But yeah, so you ride the cart and you see young
[47:59] SPEAKER: Peter Jackson talking about King Kong and also,
[48:01] SPEAKER: anyway, it's good, it's a good ride.
[48:05] SPEAKER: So Super Nintendo World, you walk into,
[48:08] SPEAKER: it's down in the lower lot, down near the sound stages,
[48:12] SPEAKER: and you kind of walk around a corner and you see
[48:16] SPEAKER: a tunnel, a pipe, and like Mario Brothers Hills,
[48:20] SPEAKER: and you walk through the pipe and there's a bunch
[48:22] SPEAKER: of lights and stuff, and then later in the day
[48:23] SPEAKER: when it's really hot and people are looking for shade,
[48:25] SPEAKER: there's a bunch of people sitting around the edges of it,
[48:28] SPEAKER: kind of just enjoying shade and stale air in there
[48:30] SPEAKER: with everybody else, and then you turn a corner
[48:33] SPEAKER: and there's like Mario 64 pictures that you could,
[48:39] SPEAKER: I mean, they look like you could jump into.
[48:41] SPEAKER: When you try and jump into them, it doesn't work,
[48:44] SPEAKER: but they change and they have the pictures of the ba-bam,
[48:48] SPEAKER: big ba-bam on the hill and all this other stuff,
[48:51] SPEAKER: and then you turn another corner and it's like
[48:53] SPEAKER: you're in a Super Mario Brothers game.
[48:57] SPEAKER: Like how thoroughly, like how extensive
[48:59] SPEAKER: are the decorations?
[49:01] SPEAKER: You can't see any, there's a couple places
[49:04] SPEAKER: when you're in there that you can see a couple
[49:06] SPEAKER: of high-rise skyscrapers poking out,
[49:08] SPEAKER: but the rest of it, you can't see anything.
[49:11] SPEAKER: So you see a hill that looks like a vertical
[49:16] SPEAKER: Super Mario Brothers 3 level with piranha plants
[49:19] SPEAKER: and cactus guys and koopas and all,
[49:24] SPEAKER: there's keys all over the place.
[49:27] SPEAKER: I guess those are Super Mario Brothers 3 keys, I guess.
[49:30] SPEAKER: - Keys.
[49:31] SPEAKER: - The circle with the key in it.
[49:33] SPEAKER: - Circle with the key in it?
[49:35] SPEAKER: - Yeah, it's like a pickup you get sometimes.
[49:36] SPEAKER: You usually have to collect multiples to do something.
[49:39] SPEAKER: - I was thinking about the Mario 2 keys,
[49:40] SPEAKER: but that doesn't sound like-- - It's not the Mario 2 key,
[49:42] SPEAKER: no, no. - Yeah, okay.
[49:43] SPEAKER: - There's Mario 2 representation at all here.
[49:45] SPEAKER: - Yeah, I know, that theme.
[49:47] SPEAKER: - I didn't see any Shy Guys.
[49:48] SPEAKER: That game does not get its due.
[49:50] SPEAKER: - Birdo, Birdo erasure will not stand.
[49:52] SPEAKER: - Is it possible to color asphalt,
[49:55] SPEAKER: or I don't know if that's what they're putting down there,
[49:58] SPEAKER: but it seems like-- - You can paint it,
[49:59] SPEAKER: but this is like a treated floor surface.
[50:01] SPEAKER: It looks like bricks and stuff.
[50:03] SPEAKER: - Oh, so they do make it.
[50:04] SPEAKER: - Yeah, yeah.
[50:05] SPEAKER: Oh yeah, it is incredibly well done.
[50:10] SPEAKER: There's much like the shade things are mushrooms,
[50:13] SPEAKER: like toadstool mushrooms.
[50:17] SPEAKER: There's mini games throughout,
[50:19] SPEAKER: so I guess we have to start out
[50:22] SPEAKER: by saying the first thing they do
[50:23] SPEAKER: when you're going to Nintendo World,
[50:25] SPEAKER: they don't really hit you over the head with it,
[50:26] SPEAKER: but if you do your homework,
[50:27] SPEAKER: you're like, "You should get amiibo wristbands."
[50:30] SPEAKER: - Oh, is that optional?
[50:31] SPEAKER: - You don't have to get 'em,
[50:33] SPEAKER: but they're 50, 45 bucks a pop pop, I think,
[50:36] SPEAKER: and they're slap bracelets with amiibos in 'em,
[50:38] SPEAKER: and you can get 'em in Mario.
[50:41] SPEAKER: There's two Mario flavors.
[50:42] SPEAKER: There's a red Mario and then a gold Mario.
[50:45] SPEAKER: There's a Daisy, a Peach, and a Yoshi, maybe a Luigi,
[50:50] SPEAKER: but no Waluigi, no,
[50:52] SPEAKER: like Daisy is the farthest off character you get access to.
[50:56] SPEAKER: - This is just a Mario-ass theme park, it sounds like.
[50:58] SPEAKER: I mean, it's called Super Nintendo World, right?
[51:01] SPEAKER: Not Super Mario World.
[51:02] SPEAKER: - Well, so in other parks in Universal Japan
[51:05] SPEAKER: and Universal Florida, Orlando, I guess,
[51:09] SPEAKER: they have a Donkey Kong bonanza ride now too.
[51:12] SPEAKER: So they may not be bonanza,
[51:14] SPEAKER: but they have a Donkey Kong ride.
[51:15] SPEAKER: - Like a Zelda version of this
[51:17] SPEAKER: would be very appealing to me.
[51:19] SPEAKER: - I want a Zelda version.
[51:20] SPEAKER: I want a Luigi's Mansion ride real bad.
[51:23] SPEAKER: I think that would be rad.
[51:24] SPEAKER: But anyway, so-
[51:25] SPEAKER: - Amiibo wristbands.
[51:26] SPEAKER: - So amiibo wristbands, there's blocks and question blocks.
[51:29] SPEAKER: There's like brick blocks
[51:29] SPEAKER: and question blocks all over the place.
[51:30] SPEAKER: You can punch them.
[51:32] SPEAKER: - Wow.
[51:33] SPEAKER: - When you punch them, if you use your amiibo hand,
[51:36] SPEAKER: it registers your punch,
[51:37] SPEAKER: and it tracks every punch that you do in the park
[51:40] SPEAKER: 'cause you scan a QR code in the back of the amiibo wristband
[51:43] SPEAKER: with your phone,
[51:45] SPEAKER: and then it hooks you up to a leaderboard, right?
[51:47] SPEAKER: So you can kind of, there's multiple aspects.
[51:52] SPEAKER: There's a scavenger hunt
[51:53] SPEAKER: where you have to tap all the blocks.
[51:55] SPEAKER: There's things you can bump it up against,
[51:58] SPEAKER: and that will light up an 8-bit Mario or Peach or Bowser
[52:04] SPEAKER: or whatever in the world around you.
[52:06] SPEAKER: - And we assume this is just NFC standard stuff?
[52:09] SPEAKER: - Just standard S.
[52:10] SPEAKER: You can tap it on your Switch when you get home,
[52:12] SPEAKER: and it shows up as a Mario amiibo.
[52:15] SPEAKER: - Oh, it actually works as an amiibo in the ecosystem?
[52:17] SPEAKER: - Regular ass amiibo.
[52:19] SPEAKER: - But not a special one.
[52:20] SPEAKER: It's not classed as its own like Super Nintendo World one.
[52:23] SPEAKER: It's just rings up as one of the retail ones.
[52:24] SPEAKER: - They work the other place that Mario amiibos work.
[52:28] SPEAKER: I think technically they're in a special group in the thing.
[52:32] SPEAKER: Like they don't, I haven't,
[52:35] SPEAKER: I don't think I've played a Mario game since then,
[52:37] SPEAKER: but I'll tap it and see, yeah.
[52:40] SPEAKER: - Not a huge deal.
[52:41] SPEAKER: I mean, I was thinking what I was,
[52:42] SPEAKER: the reason I was asking if they are classed
[52:44] SPEAKER: as their own specific amiibo is they could block
[52:46] SPEAKER: specific unique rewards up behind them in games and stuff.
[52:48] SPEAKER: I don't know if they'll do that or not.
[52:49] SPEAKER: - I would hope so.
[52:50] SPEAKER: For 47 bucks, I would like some special rewards.
[52:52] SPEAKER: - Well, but also, I mean, we'll get into it here,
[52:54] SPEAKER: but I've looked a little bit into the world
[52:56] SPEAKER: of spoofing amiibos.
[52:59] SPEAKER: - Oh, I've done the hell out of it.
[53:00] SPEAKER: When we were deep in Animal Crossing,
[53:01] SPEAKER: I bought a bunch of those discs.
[53:03] SPEAKER: I haven't bought an amiibo in five years.
[53:05] SPEAKER: - Yeah, so it is wildly doable.
[53:07] SPEAKER: - There's an app called Ally on your phone
[53:09] SPEAKER: that you put it into dark mode or something,
[53:12] SPEAKER: and then you can just download a spreadsheet
[53:15] SPEAKER: full of amiibo codes, and look, I'm just saying,
[53:18] SPEAKER: getting the Zelda costumes in Tears of the Kingdom
[53:20] SPEAKER: was pretty easy.
[53:21] SPEAKER: Anyway, okay, so there's the scavenger hunt aspect.
[53:26] SPEAKER: There's also a series of mini games throughout the park.
[53:29] SPEAKER: So mini games are like, they're themed for different ages,
[53:33] SPEAKER: mostly accessible to pretty young kids,
[53:36] SPEAKER: and some of them are run around and punch some alarm clocks
[53:39] SPEAKER: when the lights turn red, right?
[53:41] SPEAKER: And when you successfully complete a mini game challenge,
[53:44] SPEAKER: then you get a gold key that if you tap your wristband,
[53:48] SPEAKER: it also shows up in the app.
[53:50] SPEAKER: When you collect multiples, three of those gold keys,
[53:52] SPEAKER: you unlock a Bowser Jr. fight, which was fucking rad.
[53:57] SPEAKER: So you go into this room where there's no line,
[53:59] SPEAKER: 'cause nobody knows that they should be doing this,
[54:01] SPEAKER: and hardly anybody's actually doing this,
[54:03] SPEAKER: 'cause it didn't look like very many people
[54:04] SPEAKER: bought the wristbands.
[54:06] SPEAKER: But you stand in front of a big screen
[54:08] SPEAKER: with like five or six other people,
[54:09] SPEAKER: and you see your silhouette on that screen,
[54:13] SPEAKER: and it's like a fiery kind of background,
[54:15] SPEAKER: like a Bowser fight in a modern Mario game background.
[54:20] SPEAKER: And it gives you a countdown, three, two, one, go,
[54:21] SPEAKER: and it tells you what to do.
[54:23] SPEAKER: And you punch Bob-ombs and Koopa shells as they come down.
[54:27] SPEAKER: You have to duck under bullet bills
[54:30] SPEAKER: that cross the screen at different times.
[54:32] SPEAKER: You have to punch power-ups,
[54:34] SPEAKER: and it looks like your silhouette is a shadow
[54:37] SPEAKER: from the projection behind you,
[54:38] SPEAKER: but then when you hit a mushroom, the silhouette gets big.
[54:43] SPEAKER: And when you jump, your guy jumps way, way, way up
[54:46] SPEAKER: in the air, like 10, 15 feet up in the air.
[54:49] SPEAKER: It's like five minutes.
[54:50] SPEAKER: It's really stupid.
[54:51] SPEAKER: It was really good.
[54:52] SPEAKER: It made me wish that there was more stuff like that
[54:56] SPEAKER: tied to the amiibo wristbands.
[54:58] SPEAKER: - I bet the people who build modern theme park attractions
[55:00] SPEAKER: like this have some of the most fun doing their jobs
[55:03] SPEAKER: of anybody on the planet.
[55:04] SPEAKER: - I think it's gotta be a fun job, yeah.
[55:06] SPEAKER: 'Cause like just the nexus of like user experience
[55:09] SPEAKER: and modern technology and creativity and the whole thing,
[55:13] SPEAKER: you know, it's just like, you can,
[55:15] SPEAKER: there's so many ideas and probably near unlimited budget
[55:18] SPEAKER: or, you know, like pretty hefty budget.
[55:20] SPEAKER: Like you can, the range of like crazy ideas you can have
[55:23] SPEAKER: and then just execute in that space must be really fun.
[55:25] SPEAKER: - Well, I mean, like this was gamier than most of these
[55:29] SPEAKER: that I've seen have been, right?
[55:30] SPEAKER: Which like, I wanna say in the wizarding world
[55:34] SPEAKER: of Harry Potter, there's, they have like stations
[55:37] SPEAKER: as you're walking around the shops area
[55:40] SPEAKER: where you can buy a wand for 80 or 100 bucks, I'm sure,
[55:44] SPEAKER: and you wave it in front of some cameras
[55:46] SPEAKER: and then it makes some prop that's in a shop window
[55:49] SPEAKER: do something like lift up off the ground
[55:51] SPEAKER: or shake or something.
[55:52] SPEAKER: And this stuff felt more impactful for this,
[55:56] SPEAKER: A, because everybody can engage with like,
[55:57] SPEAKER: all the kids were up there punching blocks
[55:59] SPEAKER: when they had wristbands or not
[56:00] SPEAKER: 'cause punching the blocks makes a good sound
[56:02] SPEAKER: and it like lit up and it was fun, right?
[56:04] SPEAKER: - Oh, wait, so you could get in there without a wristband or?
[56:07] SPEAKER: - Yes.
[56:08] SPEAKER: - In fact, I was gonna ask earlier how they gate access
[56:10] SPEAKER: to this thing if you have to.
[56:11] SPEAKER: - It's just, you walk in,
[56:13] SPEAKER: it's just a normal part of the park.
[56:14] SPEAKER: There's no gate.
[56:16] SPEAKER: I think they do a first hour,
[56:17] SPEAKER: you have to have a reservation.
[56:19] SPEAKER: - Oh, I'm sorry, maybe it's the way the notes were worded.
[56:22] SPEAKER: I thought you had to do something with the wristbands
[56:24] SPEAKER: to like unlock access to this thing, that's not the case?
[56:26] SPEAKER: - The Bowser Jr. thing you can only do
[56:28] SPEAKER: if you've completed the scavenger hunt.
[56:31] SPEAKER: - Okay, that's what I was asking.
[56:32] SPEAKER: - The rest of Super Nintendo World,
[56:34] SPEAKER: you can just walk into.
[56:35] SPEAKER: - Yeah, yeah, yeah.
[56:36] SPEAKER: But that's what I meant though.
[56:37] SPEAKER: How do they limit access to Bowser Jr.
[56:39] SPEAKER: with the wrist?
[56:40] SPEAKER: Do you have to swipe the wristband to open the door
[56:41] SPEAKER: or something?
[56:42] SPEAKER: - So yeah, you walk up and hit a wristband on a thing
[56:44] SPEAKER: and it's like turns one color if you're approved
[56:46] SPEAKER: and another if you're not.
[56:48] SPEAKER: - Got it.
[56:49] SPEAKER: - Only one person in your party had to be approved.
[56:51] SPEAKER: So if you're going with your kid
[56:53] SPEAKER: and you don't wanna spend $300 on wristbands,
[56:55] SPEAKER: you can just get one and make one kid do all the work
[56:57] SPEAKER: and then everybody can benefit.
[57:00] SPEAKER: - They had some other stuff.
[57:02] SPEAKER: Oddly, the other Nintendo brand
[57:07] SPEAKER: that was represented here that wasn't Mario was Pikmin.
[57:12] SPEAKER: There were little Pikmin all through the park,
[57:14] SPEAKER: kind of hidden all over the place.
[57:15] SPEAKER: And some of the scavenger hunt things were like,
[57:19] SPEAKER: look at Pikmin.
[57:20] SPEAKER: You know the binoculars, the big green binoculars
[57:22] SPEAKER: from the 3D Mario games?
[57:24] SPEAKER: They had those up on a kind of out of the way edge
[57:27] SPEAKER: of the park that you didn't go to
[57:28] SPEAKER: if you weren't doing the scavenger hunt stuff.
[57:31] SPEAKER: And it had a digital,
[57:34] SPEAKER: like it was basically like a camera with a screen
[57:37] SPEAKER: and you could aim it and zoom in and out
[57:41] SPEAKER: at different parts of the park
[57:42] SPEAKER: and see like Pikmin hiding up on the top
[57:46] SPEAKER: of the far side of the thing
[57:47] SPEAKER: where you'd never be able to see it otherwise.
[57:50] SPEAKER: It was weird and like oddly half-assed.
[57:55] SPEAKER: Like it felt like there should be more stuff there.
[57:58] SPEAKER: Like I simultaneously really enjoyed the Bowser Jr. thing.
[58:02] SPEAKER: I thought the scavenger hunt was kind of okay,
[58:04] SPEAKER: but like the right amount of tedious,
[58:06] SPEAKER: like you only had to get three of the keys,
[58:09] SPEAKER: which was like you kind of could do incidentally
[58:12] SPEAKER: if you were just whacking blocks when you walked by them.
[58:17] SPEAKER: I wish that there was more stuff like the Bowser thing
[58:19] SPEAKER: 'cause it felt like that was really fun.
[58:21] SPEAKER: It was really clever.
[58:22] SPEAKER: It felt like a game which feels appropriate
[58:24] SPEAKER: for Super Nintendo World.
[58:27] SPEAKER: And overall it was pretty good.
[58:28] SPEAKER: The other thing I want to say is
[58:30] SPEAKER: in the Star Wars land in Disney,
[58:32] SPEAKER: they have the same kind of stuff, right?
[58:33] SPEAKER: So there's areas that you can interact with as a guest
[58:39] SPEAKER: that like sometimes make things happen.
[58:42] SPEAKER: Like Kylo Ren's spaceship will shoot smoke
[58:44] SPEAKER: if you've done enough things for the empire
[58:47] SPEAKER: or for the resistance when you're going through that park.
[58:51] SPEAKER: And the way that works is you have an app on your phone
[58:55] SPEAKER: and you interact with the app directly.
[58:57] SPEAKER: And if you do that enough, eventually like cast members
[58:59] SPEAKER: will come in and pull you into things sometimes
[59:02] SPEAKER: or like you'll be able to do interactions
[59:04] SPEAKER: with the big props.
[59:05] SPEAKER: You'll be able to open a door that normally doesn't open
[59:07] SPEAKER: and go see something secret and stuff like that.
[59:10] SPEAKER: But the downside of that is that if you're there
[59:13] SPEAKER: with the kids who are too young to have,
[59:14] SPEAKER: A, everybody's walking around with their fucking phone out
[59:17] SPEAKER: the whole time, which sucks.
[59:19] SPEAKER: B, if you're there with kids that are too young
[59:22] SPEAKER: to have phones, you end up in the,
[59:25] SPEAKER: hey dad, can I use your phone?
[59:27] SPEAKER: Or hey mom, can I use your phone?
[59:29] SPEAKER: So then you're paying hundreds of dollars
[59:31] SPEAKER: to go to Disneyland and be outside
[59:32] SPEAKER: and spend fun family time together
[59:34] SPEAKER: so that all of your kids can be glued to their phone
[59:36] SPEAKER: doing the bullshit.
[59:37] SPEAKER: Or worse, you're a parent and you wanna do the bullshit
[59:41] SPEAKER: and then you're on your phone neglecting the fun family.
[59:46] SPEAKER: Like it's just having your phone,
[59:47] SPEAKER: like I actually, my initial reaction on,
[59:51] SPEAKER: hey, we have to spend 50 bucks
[59:52] SPEAKER: on these stupid fucking wristbands was bad.
[59:55] SPEAKER: And then once I realized that I was walking
[59:57] SPEAKER: around Super Nintendo Land and nobody had their phones out,
[1:00:00] SPEAKER: I was like, oh, this is actually pretty good.
[1:00:01] SPEAKER: - Yeah, I was gonna say like that's probably the one upside
[1:00:04] SPEAKER: of the Disney strategy is it's maybe not free,
[1:00:07] SPEAKER: but at least cheaper to use a phone app
[1:00:09] SPEAKER: instead of this wristband training.
[1:00:10] SPEAKER: - Yeah, so the phone app's free.
[1:00:12] SPEAKER: - Oh, it is free.
[1:00:12] SPEAKER: - Yeah, like it's just a subset of the Disney park.
[1:00:15] SPEAKER: So if you go to a modern park, you download the app
[1:00:18] SPEAKER: 'cause it has the maps and the wait times
[1:00:20] SPEAKER: and all that stuff on it.
[1:00:22] SPEAKER: You also, depending on which park you're at,
[1:00:26] SPEAKER: I think the Disney FastPass stuff
[1:00:27] SPEAKER: all works through the app now too.
[1:00:29] SPEAKER: So you can say, hey, I wanna FastPass for Haunted Mansion
[1:00:34] SPEAKER: if you're not in Haunted Mansion,
[1:00:35] SPEAKER: and then it tells you what time to show up
[1:00:37] SPEAKER: and you skip the line.
[1:00:38] SPEAKER: - Yeah, I mean, $45 per person
[1:00:40] SPEAKER: for even a modest size family is not nothing.
[1:00:43] SPEAKER: Like that's a pretty substantial cost,
[1:00:44] SPEAKER: but also once you're at a modern theme park,
[1:00:46] SPEAKER: I guess, and for a penny and for a pound
[1:00:47] SPEAKER: at that point anyway.
[1:00:49] SPEAKER: They're gonna turn you upside down and shake
[1:00:50] SPEAKER: the money out of you.
[1:00:51] SPEAKER: - But that sounds like a massively better,
[1:00:53] SPEAKER: like I have started developing some derision
[1:00:58] SPEAKER: for the amount of noses buried in phones
[1:01:00] SPEAKER: in modern society these days.
[1:01:02] SPEAKER: And so like an experience that explicitly keeps people
[1:01:05] SPEAKER: off their phones and doing a thing
[1:01:06] SPEAKER: and looking at a thing seems pretty good.
[1:01:08] SPEAKER: - It was nice.
[1:01:09] SPEAKER: And some of the mini games were really fun.
[1:01:10] SPEAKER: Like one of them, you had to control a Koopa shell.
[1:01:13] SPEAKER: Like you had to punch a Koopa shell
[1:01:16] SPEAKER: that was going back and forth across,
[1:01:17] SPEAKER: just stuck bouncing for eternity.
[1:01:20] SPEAKER: And if you punched at the right time,
[1:01:21] SPEAKER: it would go up and hit a power block
[1:01:22] SPEAKER: and then some stuff would happen.
[1:01:23] SPEAKER: And that was kind of fun.
[1:01:26] SPEAKER: Like overall styling was really good.
[1:01:29] SPEAKER: There's also a ride,
[1:01:30] SPEAKER: obviously the Mario Kart ride is there.
[1:01:32] SPEAKER: Bowser's Fury or Bowser's Revenge or something.
[1:01:34] SPEAKER: I can't remember what it's actually called.
[1:01:36] SPEAKER: But it's a combo kart.
[1:01:39] SPEAKER: Like you ride a kart with three other people.
[1:01:42] SPEAKER: And then you also put on this AR headset.
[1:01:47] SPEAKER: They do it, they give you a Halo kind of headband
[1:01:50] SPEAKER: that you put on, like the PSVR ones.
[1:01:54] SPEAKER: And then when you sit down in the kart,
[1:01:55] SPEAKER: there's a wired in pair of goggles
[1:01:58] SPEAKER: that just snap onto that headband that you're wearing.
[1:02:03] SPEAKER: And you tap your Meebo onto the steering wheel
[1:02:05] SPEAKER: to let the car know that you're you.
[1:02:08] SPEAKER: And then there's a game kind of like
[1:02:10] SPEAKER: the Buzz Lightyear adventure at Disneyland,
[1:02:12] SPEAKER: the old one that you drive around and shoot stuff.
[1:02:13] SPEAKER: But it's all, the kart, the car ride is riding around
[1:02:18] SPEAKER: in this really lovely stylized area.
[1:02:21] SPEAKER: And then the game is shooting Koopalings
[1:02:25] SPEAKER: that shoot in front of you with shells.
[1:02:27] SPEAKER: Collecting shells and shooting Koopalings
[1:02:29] SPEAKER: and shooting extra stuff in the environment.
[1:02:31] SPEAKER: - So it's all PVE.
[1:02:32] SPEAKER: - It's all PVE.
[1:02:34] SPEAKER: One person can control the steering
[1:02:35] SPEAKER: or maybe multiple people control.
[1:02:37] SPEAKER: It seems like one person controlled the steering
[1:02:39] SPEAKER: in the karts that we were in.
[1:02:41] SPEAKER: - The big issue I have with this ride in general
[1:02:44] SPEAKER: is that you didn't need the ride for the game to work.
[1:02:48] SPEAKER: And the way the AR headset is set up,
[1:02:50] SPEAKER: it's really, really bright.
[1:02:51] SPEAKER: So you're not really,
[1:02:53] SPEAKER: like you're seeing overlays on the world
[1:02:55] SPEAKER: that are three-dimensional and tracked,
[1:02:57] SPEAKER: but not like the brightness of the world
[1:03:00] SPEAKER: versus the brightness of the things
[1:03:02] SPEAKER: that are being projected on the AR screen as such.
[1:03:04] SPEAKER: You can't really see the world, which is a bummer
[1:03:07] SPEAKER: because the world design is awesome.
[1:03:10] SPEAKER: - How, what's the word I'm looking for?
[1:03:12] SPEAKER: How pervasive are the images?
[1:03:13] SPEAKER: They are images.
[1:03:14] SPEAKER: Is it like a ton of your view is constantly obscured?
[1:03:18] SPEAKER: - It's not a ton of your view, but it's-
[1:03:19] SPEAKER: - It's not rendering landscape or anything.
[1:03:21] SPEAKER: It's just entities.
[1:03:22] SPEAKER: - Just the Koopalings.
[1:03:23] SPEAKER: - Okay.
[1:03:24] SPEAKER: - Yeah, so, and it does, it's funny
[1:03:25] SPEAKER: 'cause it does an interesting thing at the start
[1:03:27] SPEAKER: where the tutorial section is 2D 16-bit era Koopalings.
[1:03:33] SPEAKER: And then once you transition out of there,
[1:03:35] SPEAKER: it becomes the modern Mario Kart 8 Koopaling 3D renders.
[1:03:39] SPEAKER: - That's neat.
[1:03:40] SPEAKER: - But yeah, the fundamental problem is that you,
[1:03:44] SPEAKER: the game is so pervasive that you don't focus on the,
[1:03:49] SPEAKER: it's hard to focus on the ride.
[1:03:50] SPEAKER: - Sure.
[1:03:51] SPEAKER: - I think the ride maybe is a little underwhelming actually
[1:03:53] SPEAKER: is probably why it's like that.
[1:03:55] SPEAKER: But, and so you shoot the Koopalings
[1:03:57] SPEAKER: by aiming with your head.
[1:03:58] SPEAKER: So you aim with your head and you have two trigger buttons
[1:04:00] SPEAKER: on your steering wheel and you shoot shells,
[1:04:04] SPEAKER: whatever power up you have by aiming and shooting.
[1:04:06] SPEAKER: - Sure.
[1:04:07] SPEAKER: - And then they give you your car, a score at the end
[1:04:10] SPEAKER: and let you know how you stacked up against the people
[1:04:12] SPEAKER: in the other lane, as well as everybody else
[1:04:15] SPEAKER: who rode that week, which is weird.
[1:04:18] SPEAKER: I don't know how they're tracking this.
[1:04:19] SPEAKER: That's the other interesting thing
[1:04:22] SPEAKER: is it seemed to be motion tracked.
[1:04:24] SPEAKER: I don't know if they're keeping everybody in sync
[1:04:26] SPEAKER: with everybody else, but like the Koopalings
[1:04:28] SPEAKER: rode down the track when they were riding away from you.
[1:04:31] SPEAKER: They didn't just fly off into space or whatever.
[1:04:33] SPEAKER: - Interesting.
[1:04:34] SPEAKER: - So like they're doing some aspect of 6DOF tracking
[1:04:38] SPEAKER: with it and it felt pretty good.
[1:04:42] SPEAKER: I mean, AR is a little more forgiving than VR
[1:04:44] SPEAKER: in terms of like motion sickness and stuff,
[1:04:46] SPEAKER: but none of the people we were with
[1:04:48] SPEAKER: who sometimes have motion sickness issues have any problems.
[1:04:50] SPEAKER: - All right.
[1:04:51] SPEAKER: - Yeah.
[1:04:52] SPEAKER: - I assume this part is so Mario centric to synergize
[1:04:56] SPEAKER: with the success of the movie or put it another way,
[1:04:58] SPEAKER: I would guess maybe any planned Zelda attractions
[1:05:02] SPEAKER: might be something they're saving for that movie
[1:05:05] SPEAKER: to come out and be huge.
[1:05:06] SPEAKER: - I don't think they've announced any Zelda movies.
[1:05:09] SPEAKER: None of this was movie.
[1:05:10] SPEAKER: - No, there is a movie.
[1:05:11] SPEAKER: - I'm sorry, Zelda rides.
[1:05:12] SPEAKER: - Oh, rides, yeah.
[1:05:13] SPEAKER: - None of this was movie focused.
[1:05:16] SPEAKER: - Well, yeah, but what I just mean that Mario is like,
[1:05:18] SPEAKER: I mean, Mario is always bigger than anything else
[1:05:20] SPEAKER: Nintendo has, but like Mario is extra, extra huge
[1:05:23] SPEAKER: in the wake of that movie.
[1:05:24] SPEAKER: - I mean, I guess that's why they did
[1:05:26] SPEAKER: the Donkey Kong thing next probably.
[1:05:28] SPEAKER: - Maybe.
[1:05:28] SPEAKER: - It's weird 'cause like, so like the cues,
[1:05:32] SPEAKER: one of the things that Universal does really well
[1:05:33] SPEAKER: is their cue styling is really good.
[1:05:35] SPEAKER: So when you're waiting in line,
[1:05:36] SPEAKER: there's a ton of interesting stuff to look at.
[1:05:38] SPEAKER: And it like, the cue is walking through Bowser's castle.
[1:05:41] SPEAKER: - Okay.
[1:05:42] SPEAKER: - So you're like, there's a huge picture of Bowser.
[1:05:43] SPEAKER: There's like, but it's all Mario Kart eight styling.
[1:05:47] SPEAKER: So like the track, like the circuits are all there's,
[1:05:52] SPEAKER: there's badges for the circuits on the walls everywhere.
[1:05:54] SPEAKER: They're all the Mario Kart eight ones.
[1:05:56] SPEAKER: The trophies are all the Mario Kart eight ones.
[1:05:58] SPEAKER: - So you're saying they have old Donkey Kong?
[1:06:00] SPEAKER: - I'm saying they have old Donkey Kong, classic DK.
[1:06:03] SPEAKER: - They have obsolete Donkey Kong.
[1:06:04] SPEAKER: - I don't know if Donkey Kong actually shows up in there.
[1:06:07] SPEAKER: They have bananas, but I don't know if I saw Donkey Kong
[1:06:09] SPEAKER: in this way.
[1:06:10] SPEAKER: I mean, Donkey Kong's in Florida, not in,
[1:06:12] SPEAKER: he's a Florida man, not in.
[1:06:13] SPEAKER: - Yes.
[1:06:13] SPEAKER: (laughing)
[1:06:15] SPEAKER: - Welcome, welcome to your Florida Kong.
[1:06:17] SPEAKER: (laughing)
[1:06:21] SPEAKER: I mean, I'm not wrong.
[1:06:23] SPEAKER: - I think you're probably exactly right.
[1:06:25] SPEAKER: - Yeah.
[1:06:27] SPEAKER: So, so yeah, it's like, it's really,
[1:06:31] SPEAKER: I love walking through the queues.
[1:06:34] SPEAKER: The lines weren't too bad.
[1:06:35] SPEAKER: It was like a 50 minute wait,
[1:06:37] SPEAKER: most of the time we were there.
[1:06:40] SPEAKER: And then they do like a whole tutorial video
[1:06:42] SPEAKER: where they show you how to put on the helmet
[1:06:43] SPEAKER: and how to play the game.
[1:06:44] SPEAKER: They show you how to play the game like three times,
[1:06:46] SPEAKER: which I thought was interesting.
[1:06:48] SPEAKER: And yeah, that like, that's pretty much,
[1:06:51] SPEAKER: that's pretty much it.
[1:06:53] SPEAKER: We had lunch at the Toadstool Cafe,
[1:06:56] SPEAKER: which I'd been recommended to get a reservation for.
[1:07:02] SPEAKER: It was park, pretty good.
[1:07:05] SPEAKER: I would say good to very good for park food.
[1:07:08] SPEAKER: - I'm looking for a menu.
[1:07:09] SPEAKER: - Yeah, we had, I had a Mario burger.
[1:07:12] SPEAKER: Everything has mushrooms on it.
[1:07:14] SPEAKER: - Oh, wow.
[1:07:15] SPEAKER: - 'Cause it's in a mushroom kingdom.
[1:07:17] SPEAKER: - I love mushrooms, but some people certainly do not.
[1:07:19] SPEAKER: - Well, so most of our party does not like mushrooms.
[1:07:23] SPEAKER: One of the things that I think they did
[1:07:24] SPEAKER: a kind of crap job on is all of the food
[1:07:26] SPEAKER: that you order at a sit-down place at Universal,
[1:07:29] SPEAKER: you can get them to customize
[1:07:30] SPEAKER: 'cause they make it all to order.
[1:07:32] SPEAKER: So it's not like typical theme parks
[1:07:33] SPEAKER: where there's 50 million corn dogs back there
[1:07:35] SPEAKER: and you just get the corn dog that they make for everybody.
[1:07:37] SPEAKER: So we got all of our stuff without mushrooms
[1:07:39] SPEAKER: and like the fries came without truffle oil
[1:07:41] SPEAKER: and all that stuff, but they don't really make that clear
[1:07:45] SPEAKER: until you're talking to a person ordering food,
[1:07:47] SPEAKER: which like was a source of stress.
[1:07:50] SPEAKER: - I finally found the menu.
[1:07:52] SPEAKER: - Yeah.
[1:07:53] SPEAKER: - Mozzarella cheese fettuccine Alfredo.
[1:07:55] SPEAKER: - Yeah, it was a real plate of pasta.
[1:07:57] SPEAKER: I saw somebody get that at the table next to us.
[1:07:59] SPEAKER: Somebody got this enormous Bowser's dynamite meatball,
[1:08:02] SPEAKER: I think.
[1:08:03] SPEAKER: - Bowser's fireball challenge.
[1:08:05] SPEAKER: - There you go.
[1:08:06] SPEAKER: It was the biggest meatball I've ever seen, Brad.
[1:08:08] SPEAKER: - It's a one pound meatball topped with mozzarella cheese
[1:08:11] SPEAKER: served with mushroom marinara sauce.
[1:08:12] SPEAKER: - It looked like the size of my head.
[1:08:15] SPEAKER: - Bowser puff pastry.
[1:08:16] SPEAKER: - We didn't get those, but they look pretty good.
[1:08:19] SPEAKER: - They have both a Mario burger and a Luigi burger.
[1:08:21] SPEAKER: - The Luigi burger is chicken, which I feel like is,
[1:08:26] SPEAKER: I feel like Luigi will not stand for this slight.
[1:08:28] SPEAKER: Do we not remember the year of Luigi people?
[1:08:31] SPEAKER: That's all I'm saying.
[1:08:34] SPEAKER: We got peach cupcakes.
[1:08:36] SPEAKER: If I had known that the peach cupcakes
[1:08:37] SPEAKER: were as big as they were,
[1:08:38] SPEAKER: we could have split one of them for the three of us,
[1:08:41] SPEAKER: but we took one home.
[1:08:42] SPEAKER: - So there's something funny about reading peach cupcake,
[1:08:46] SPEAKER: raspberry filled cupcake.
[1:08:47] SPEAKER: It's like, it's a peach cupcake filled with raspberry.
[1:08:50] SPEAKER: - I know what's her name, I'm not a fruit.
[1:08:53] SPEAKER: - Peach contains multitudes.
[1:08:55] SPEAKER: She loves both peach, but her favorite color is pink.
[1:08:58] SPEAKER: So everything in there was pink.
[1:09:00] SPEAKER: And yeah, I will say the food there was better
[1:09:03] SPEAKER: than the crusty burger,
[1:09:04] SPEAKER: which is where we ate dinner that night.
[1:09:06] SPEAKER: - Oh man, that's a lot of themed food for one day.
[1:09:09] SPEAKER: - It was a lot of themed food, Brad.
[1:09:12] SPEAKER: So yeah, Mario Kart, okay.
[1:09:15] SPEAKER: Mario, Super Nintendo World, awesome.
[1:09:18] SPEAKER: Maybe figure out how to do a bootleg band
[1:09:20] SPEAKER: rather than pay the 57 bucks if you're,
[1:09:23] SPEAKER: I don't know how you would register
[1:09:24] SPEAKER: your bootleg amiibo band to their app is the thing.
[1:09:27] SPEAKER: And without the app,
[1:09:28] SPEAKER: I think it would be a little bit less fun.
[1:09:31] SPEAKER: Yeah.
[1:09:33] SPEAKER: - Interesting, all right.
[1:09:34] SPEAKER: - Yeah.
[1:09:35] SPEAKER: - Oh, I found a picture.
[1:09:35] SPEAKER: I finally found a picture of these wristbands.
[1:09:37] SPEAKER: Those look awesome.
[1:09:38] SPEAKER: - They're very cool.
[1:09:39] SPEAKER: - To be fair, those look really cool actually.
[1:09:42] SPEAKER: - Like A, slap bracelets, still awesome
[1:09:45] SPEAKER: after all these years.
[1:09:47] SPEAKER: B, I got the gold Mario one, so I turned it upside down.
[1:09:50] SPEAKER: So it looked like a Wario one.
[1:09:51] SPEAKER: I thought that was pretty good.
[1:09:53] SPEAKER: C, pretty uncomfortable over the length of the day.
[1:09:56] SPEAKER: I'm gonna say.
[1:09:57] SPEAKER: - I can see it better, they're quite big.
[1:09:59] SPEAKER: - Well, but also the bend on the slap bracelet
[1:10:02] SPEAKER: is not such that it is a size for an adult wrist.
[1:10:07] SPEAKER: I wish they had more character representation
[1:10:09] SPEAKER: in the wristband choices.
[1:10:10] SPEAKER: - Sure, all right.
[1:10:13] SPEAKER: - Yeah, so Super Nintendo World, I would go back.
[1:10:15] SPEAKER: I don't know if I'm gonna go to a Florida one,
[1:10:17] SPEAKER: but maybe I'll go to the one in Japan.
[1:10:18] SPEAKER: That looks cool.
[1:10:19] SPEAKER: And yeah, give me a Luigi's Mansion game.
[1:10:22] SPEAKER: That's all I want.
[1:10:23] SPEAKER: It's never gonna happen, is it?
[1:10:25] SPEAKER: - Game or attraction?
[1:10:26] SPEAKER: - Attraction.
[1:10:27] SPEAKER: - I'm gonna say no to both.
[1:10:29] SPEAKER: - I mean, look, there's a Luigi's Mansion arcade game
[1:10:32] SPEAKER: that's pretty dope.
[1:10:32] SPEAKER: - Oh, okay.
[1:10:33] SPEAKER: - Have you ever seen that?
[1:10:34] SPEAKER: - No, I have not.
[1:10:35] SPEAKER: I mean, they just did three, not that many years ago, but.
[1:10:37] SPEAKER: - Yeah, those make money.
[1:10:39] SPEAKER: The arcade game has a big giant ghost,
[1:10:43] SPEAKER: I can't remember the name of the vacuum cleaner,
[1:10:45] SPEAKER: but it's the ghost vacuum.
[1:10:46] SPEAKER: - Okay.
[1:10:47] SPEAKER: - And you get to hold it in the booth.
[1:10:48] SPEAKER: - Succotron 5000, I don't remember.
[1:10:51] SPEAKER: - Yeah, it's Gus, isn't it Gus something?
[1:10:53] SPEAKER: - Oh, yes.
[1:10:54] SPEAKER: Now I need to know, before we end this podcast,
[1:10:56] SPEAKER: I'm going to look that up.
[1:10:58] SPEAKER: - This is why we do this podcast,
[1:10:59] SPEAKER: 'cause I was getting ready to go look to it.
[1:11:00] SPEAKER: - Poltergust 3000.
[1:11:01] SPEAKER: - Poltergust, that's a good name.
[1:11:03] SPEAKER: - It's pretty good.
[1:11:03] SPEAKER: - That deserves a ride, man.
[1:11:04] SPEAKER: That's all I'm saying.
[1:11:05] SPEAKER: - Sure.
[1:11:07] SPEAKER: - That'll do it for us this week.
[1:11:08] SPEAKER: Thanks, everybody, for listening.
[1:11:10] SPEAKER: Brad, I'm glad you had a voyage of discovery.
[1:11:12] SPEAKER: - Uh-huh, personal growth.
[1:11:14] SPEAKER: - Yeah.
[1:11:15] SPEAKER: - We are, let's see, about six hours out
[1:11:18] SPEAKER: from the 24 hour mark.
[1:11:20] SPEAKER: - Gonna go grocery shopping?
[1:11:21] SPEAKER: - I think we should probably go buy some groceries.
[1:11:23] SPEAKER: - Seems nice, yeah, seems like you could get some ham.
[1:11:25] SPEAKER: - Need to do a Costco run, though.
[1:11:27] SPEAKER: - I mean, rent a car, head down to Costco.
[1:11:30] SPEAKER: - Yep, yep.
[1:11:32] SPEAKER: - As always, "Brad and Will Made a Tech Pod"
[1:11:34] SPEAKER: is a listener-supported show.
[1:11:35] SPEAKER: That means we would not be here without you, the listeners.
[1:11:38] SPEAKER: We appreciate each and every one of you.
[1:11:40] SPEAKER: If you would like to find out how to support the show,
[1:11:42] SPEAKER: you can go to patreon.com/techpod.
[1:11:45] SPEAKER: Again, that's patreon.com/techpod,
[1:11:49] SPEAKER: where for five bucks a month,
[1:11:50] SPEAKER: you get access to the fabulous Tech Pod Discord,
[1:11:52] SPEAKER: which is full of nerds who will talk about
[1:11:55] SPEAKER: all sorts of interesting things.
[1:11:56] SPEAKER: I had a conversation in there the other day,
[1:11:57] SPEAKER: and I'm completely blanking on what it was right now,
[1:12:00] SPEAKER: but it was incredibly helpful.
[1:12:03] SPEAKER: Damn, what was it?
[1:12:04] SPEAKER: Was it when my monitor died?
[1:12:05] SPEAKER: No.
[1:12:06] SPEAKER: - Maybe.
[1:12:08] SPEAKER: - What were we talking about?
[1:12:09] SPEAKER: It was in the PC hardware channel.
[1:12:11] SPEAKER: - From colon Will, actually, what is your username?
[1:12:14] SPEAKER: It's not Will.
[1:12:15] SPEAKER: - Will.
[1:12:16] SPEAKER: My username on Discord is Will, it was a bad choice.
[1:12:19] SPEAKER: - Oh, that's why it's coming up.
[1:12:21] SPEAKER: - I said, surely, surely I'm not gonna be able to get
[1:12:24] SPEAKER: just Will as a username.
[1:12:27] SPEAKER: - I can't get it to come up in search.
[1:12:28] SPEAKER: Discord search is bad.
[1:12:32] SPEAKER: - Discord search is bad.
[1:12:34] SPEAKER: I couldn't get it either.
[1:12:35] SPEAKER: Anyway, you get access to the Discord.
[1:12:37] SPEAKER: You get the monthly Patreon exclusive episode
[1:12:39] SPEAKER: where we talk about projects that are going on
[1:12:41] SPEAKER: and things that we find interesting, but not so interesting.
[1:12:44] SPEAKER: We're gonna do a full episode about,
[1:12:47] SPEAKER: and other stuff, just things and stuff.
[1:12:50] SPEAKER: Sometimes we have an interview with people.
[1:12:52] SPEAKER: We might do some more interviews there,
[1:12:54] SPEAKER: 'cause I liked doing those interviews and it was fun.
[1:12:57] SPEAKER: But that'll do it for us this month.
[1:12:58] SPEAKER: Thanks everybody for listening.
[1:13:00] SPEAKER: Oh, wait, executive producer tier patrons.
[1:13:02] SPEAKER: We especially appreciate our executive producer tier patrons,
[1:13:05] SPEAKER: including Jason Lee, Andrew Slosky, Jordan Lippitt,
[1:13:09] SPEAKER: Bunny Fiend, Twinkle Twinkie, David Allen,
[1:13:12] SPEAKER: James Kamik, and Pantheon,
[1:13:14] SPEAKER: makers of the HS3 high-speed 3D printer.
[1:13:17] SPEAKER: Thank you all so, so much.
[1:13:18] SPEAKER: - Yes, thank you.
[1:13:20] SPEAKER: - And that'll do it for us this month.
[1:13:22] SPEAKER: We will be back this week.
[1:13:25] SPEAKER: Feels like it's been a month already.
[1:13:26] SPEAKER: It's already mid-August.
[1:13:27] SPEAKER: What's happening, man?
[1:13:29] SPEAKER: - We've been over this.
[1:13:30] SPEAKER: - Yeah, time was fungible, I understand.
[1:13:33] SPEAKER: - You know what's happening.
[1:13:34] SPEAKER: - Your fudgehogs is getting older every day,
[1:13:37] SPEAKER: so it's getting gray back there.
[1:13:39] SPEAKER: - Fudgehog is eternal.
[1:13:41] SPEAKER: - Okay, fudgehog, fudgehog will never...
[1:13:43] SPEAKER: Look, we need a fudgehog land is what we need.
[1:13:45] SPEAKER: Where's the Viva Pinata land?
[1:13:46] SPEAKER: - You don't even say the...
[1:13:48] SPEAKER: - Can you imagine?
[1:13:50] SPEAKER: Brad, I did get my picture taken with Toad.
[1:13:52] SPEAKER: - Okay.
[1:13:53] SPEAKER: - I didn't wait in the Mario and Luigi line
[1:13:54] SPEAKER: 'cause they were too long.
[1:13:55] SPEAKER: - Toad deserves love too.
[1:13:57] SPEAKER: - Yeah, Toad was super stoked.
[1:13:58] SPEAKER: I got my picture taken with Toad
[1:14:00] SPEAKER: and a fake Krusty the Clown, so.
[1:14:02] SPEAKER: - Toad picks things up the fastest.
[1:14:04] SPEAKER: - Yeah.
[1:14:05] SPEAKER: - Arguably the best character.
[1:14:06] SPEAKER: - Fastest jump too.
[1:14:08] SPEAKER: - Yeah, true.
[1:14:08] SPEAKER: Easily in the bad Mario game, Toad is the best.
[1:14:14] SPEAKER: But yeah, we'll be back next week
[1:14:15] SPEAKER: with another edition of the Tech Pod.
[1:14:16] SPEAKER: Thanks for listening, everybody, every, ah-ha.
[1:14:19] SPEAKER: Thanks for listening, everybody.
[1:14:20] SPEAKER: I can't say everybody today, Brad.
[1:14:22] SPEAKER: - I'm not cutting any of this out.
[1:14:23] SPEAKER: - Goddammit, no, you gotta cut this out.
[1:14:25] SPEAKER: - Nope, nope, try again.
[1:14:26] SPEAKER: - Thanks for listening, everyone,
[1:14:28] SPEAKER: and we will be back next week
[1:14:29] SPEAKER: with another edition of the Tech Pod.
[1:14:30] SPEAKER: As always, please consider the environment
[1:14:33] SPEAKER: before printing this podcast.
[1:14:34] SPEAKER: (upbeat music)
[1:14:38] SPEAKER: [BLANK_AUDIO]
