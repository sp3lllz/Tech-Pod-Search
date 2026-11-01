---
episode: 54
title: 53: The Mass-to-Volume Ratio
date: 2020-09-20
guests: none
duration: 1:07:49
---

[00:00] SPEAKER: - Hey Brad. - Yeah.
[00:01] SPEAKER: - I got Windows 2004 last night.
[00:04] SPEAKER: - You're in the future, you're living in 2004 now.
[00:06] SPEAKER: - I haven't installed it yet,
[00:07] SPEAKER: but I have a full command line interface.
[00:09] SPEAKER: - It's like the late night man used to say,
[00:11] SPEAKER: ♪ In the year 2004 ♪
[00:13] SPEAKER: (laughing)
[00:15] SPEAKER: - So, I have no idea what that is actually.
[00:18] SPEAKER: - Wait, what?
[00:18] SPEAKER: - No, I've never heard that one before.
[00:19] SPEAKER: - That's the Andy Richter,
[00:21] SPEAKER: that's the previous iteration of Conan O'Brien,
[00:24] SPEAKER: or was that two iterations ago?
[00:25] SPEAKER: The first-- - The one on NBC?
[00:27] SPEAKER: - The first iteration of Conan O'Brien,
[00:28] SPEAKER: which was I believe late night.
[00:30] SPEAKER: - Late night, with Conan O'Brien.
[00:32] SPEAKER: - Late night with Conan O'Brien,
[00:33] SPEAKER: his first real late night show.
[00:34] SPEAKER: That was, do you remember that?
[00:37] SPEAKER: I don't remember the in the year 2000 bit.
[00:40] SPEAKER: - Brad, I'm gonna go ahead and tell you something bad.
[00:41] SPEAKER: ♪ In the year 2000 ♪
[00:43] SPEAKER: - I am super hoarse right now,
[00:45] SPEAKER: 'cause I'm slightly hungover.
[00:47] SPEAKER: (laughing)
[00:49] SPEAKER: - Look, that was 20 years ago, man.
[00:51] SPEAKER: - Oh, a little more than that actually,
[00:54] SPEAKER: like 22, 23, 24 years ago, 25.
[00:57] SPEAKER: That was when I was in high school,
[00:58] SPEAKER: so that was like 20, maybe 25 years ago.
[01:01] SPEAKER: - That might've been the time period I wasn't watching,
[01:02] SPEAKER: 'cause if when you were in high school,
[01:03] SPEAKER: I would have been in college
[01:04] SPEAKER: and I was just, I was doing other things.
[01:06] SPEAKER: - Yeah, what is it about college
[01:08] SPEAKER: that makes you not watch TV?
[01:10] SPEAKER: - I didn't have a TV for a while.
[01:11] SPEAKER: - Okay, that was me too, actually.
[01:13] SPEAKER: - Yeah, and then I got a TV
[01:15] SPEAKER: and it was mostly used to play NHL 96, it turns out.
[01:18] SPEAKER: - Okay, yeah, it's a good collegiate activity.
[01:20] SPEAKER: - Yeah, well, like it's the one time,
[01:23] SPEAKER: at that time in your life, in my life at least,
[01:25] SPEAKER: being able to play multiplayer games was a brand new thing.
[01:28] SPEAKER: Like having constant access to multiplayer games was new.
[01:31] SPEAKER: - Having constant access to people around to play them
[01:34] SPEAKER: was also, you didn't have to like drive to somebody's house,
[01:37] SPEAKER: they were just around.
[01:38] SPEAKER: - Yeah, you could just be like,
[01:39] SPEAKER: "Hey man, I got the 4Tap, you wanna play some NHL?"
[01:42] SPEAKER: And you'd be like, "Yeah, I'll play some NHL."
[01:44] SPEAKER: - Yeah, that's what living in the future is.
[01:48] SPEAKER: - So I gotta say the first thing that Windows 2004 did
[01:51] SPEAKER: is I have this task scheduler thing set up
[01:53] SPEAKER: to run a Python script that makes my audio controller
[01:57] SPEAKER: work with my interface, right?
[02:00] SPEAKER: And the first thing Windows 2004 did was break that.
[02:03] SPEAKER: - Nice, great, yep, that's the dark secret
[02:07] SPEAKER: of living the streamlined automation life in Windows
[02:10] SPEAKER: is that it's just a giant house of cards.
[02:12] SPEAKER: - Yeah, so task scheduler seems like it maybe
[02:14] SPEAKER: doesn't like Python scripts now or something.
[02:16] SPEAKER: I don't think I can just like load the WSL stuff
[02:19] SPEAKER: and set up a crontab and maybe never think about this again.
[02:22] SPEAKER: - You spend hours and hours setting up task scheduler
[02:25] SPEAKER: and group policy and shortcuts of all varieties.
[02:31] SPEAKER: - Yeah.
[02:31] SPEAKER: - And along comes a Windows update and just goes,
[02:37] SPEAKER: it all collapses.
[02:39] SPEAKER: - I have not spent as much time engaging
[02:41] SPEAKER: with task scheduler as you have.
[02:43] SPEAKER: - Sucks, it's terrible.
[02:44] SPEAKER: - It's bad, yeah, I was gonna say that.
[02:47] SPEAKER: The secret of it is it sucks ass.
[02:48] SPEAKER: - It doesn't work.
[02:50] SPEAKER: - No.
[02:50] SPEAKER: - It doesn't work reliably, it doesn't schedule tasks,
[02:53] SPEAKER: which is right there in the name.
[02:55] SPEAKER: - Oh, it schedules them.
[02:56] SPEAKER: - It does, but not reliably.
[02:57] SPEAKER: It's not always clear what user is running them.
[02:59] SPEAKER: So sometimes the thing you wanna do,
[03:01] SPEAKER: you don't actually have like privileges to do.
[03:03] SPEAKER: - Well, and also sometimes like the one job
[03:08] SPEAKER: that task scheduler has is to look at some conditions
[03:10] SPEAKER: and when those conditions are fulfilled to do a thing.
[03:13] SPEAKER: Sometimes it looks at the conditions,
[03:15] SPEAKER: the conditions are fulfilled.
[03:16] SPEAKER: - And it just doesn't.
[03:17] SPEAKER: - And it just doesn't do anything.
[03:17] SPEAKER: - Yeah, totally, well, that's what I'm getting at sometimes
[03:19] SPEAKER: and it doesn't tell you why, that's the thing.
[03:21] SPEAKER: - No.
[03:22] SPEAKER: - It might have tried to do the thing
[03:23] SPEAKER: and was told by the system,
[03:25] SPEAKER: you don't have the rights to do this,
[03:26] SPEAKER: but it never tells you that.
[03:27] SPEAKER: - But I can't like, I need to find like
[03:30] SPEAKER: the command line interface for task scheduler
[03:32] SPEAKER: so I can run a task to see what's happening at the console.
[03:35] SPEAKER: - It has that, we can talk later.
[03:37] SPEAKER: Or I can just tell you right now what it is actually, hold up.
[03:40] SPEAKER: - Yeah, tell me right now.
[03:41] SPEAKER: - I've got a whole bunch of them set up right now.
[03:43] SPEAKER: I've got, do you wanna know what,
[03:45] SPEAKER: this is gonna turn into the whole episode
[03:46] SPEAKER: if we keep going like this.
[03:47] SPEAKER: - Do I wanna know what love is?
[03:48] SPEAKER: Yes, show me, give me a moment.
[03:50] SPEAKER: - Do you want me to tell you what command line stuff
[03:53] SPEAKER: I have set up that I can just type a word in to make happen
[03:56] SPEAKER: rather than navigating?
[03:57] SPEAKER: - This feels strangely kinky, but okay.
[04:01] SPEAKER: - For example, 'cause you know,
[04:03] SPEAKER: like most of the stuff in Windows,
[04:04] SPEAKER: you have to navigate like five layers of menus, right?
[04:06] SPEAKER: To find the button you want to click.
[04:08] SPEAKER: - Yeah.
[04:09] SPEAKER: - So like I have automated things like switching
[04:10] SPEAKER: between the light and dark theme in Windows.
[04:13] SPEAKER: So.
[04:14] SPEAKER: - Why would you ever switch
[04:15] SPEAKER: between the light and dark theme in Windows?
[04:16] SPEAKER: - 'Cause I like the light theme during the day
[04:17] SPEAKER: and the dark theme at night.
[04:19] SPEAKER: - Doesn't it do that automatically now?
[04:20] SPEAKER: - No, it does not.
[04:21] SPEAKER: - What?
[04:22] SPEAKER: - We've talked about this, man.
[04:24] SPEAKER: So.
[04:25] SPEAKER: - I thought it did that automatically now.
[04:26] SPEAKER: - I have shortcuts called light and dark.
[04:30] SPEAKER: And I can pop up the start menu and type light
[04:33] SPEAKER: and it will automatically switch to the light theme.
[04:36] SPEAKER: I have one called desk swap that will swap
[04:39] SPEAKER: which one is my primary desktop.
[04:42] SPEAKER: - Wow.
[04:44] SPEAKER: - I've got a variety of them that's mute
[04:47] SPEAKER: and unmute various input devices, sound input devices.
[04:51] SPEAKER: - Oh yeah, that's a near soft jam right there, right?
[04:54] SPEAKER: - Yes, no, I use task scheduler for that.
[04:56] SPEAKER: But hold up, let me tell you, I was just gonna tell you,
[05:00] SPEAKER: schtasks.exe is the command line version of task scheduler.
[05:07] SPEAKER: So you can run schtasks/run and the name of the task.
[05:13] SPEAKER: That's for automating.
[05:14] SPEAKER: That's for your-
[05:15] SPEAKER: - This is a fantastic, incredibly useful cold open.
[05:16] SPEAKER: - That's for your automating purposes.
[05:18] SPEAKER: We'll talk more later.
[05:20] SPEAKER: (upbeat music)
[05:46] SPEAKER: (upbeat music)
[05:51] SPEAKER: - Welcome to Brad and Will Made a Tech Pod.
[05:53] SPEAKER: I'm Will.
[05:54] SPEAKER: - I'm Brad, how you doing, Will?
[05:56] SPEAKER: - I'm over here making a tech pod.
[05:57] SPEAKER: How about you, man?
[05:58] SPEAKER: - That's right, man.
[05:59] SPEAKER: It's just here we are on a Saturday morning
[06:00] SPEAKER: feeling just lively and crisp, ready to talk.
[06:03] SPEAKER: - Everything's great.
[06:04] SPEAKER: - Yeah, nothing bad at all.
[06:07] SPEAKER: Whatever, I'm sorry.
[06:08] SPEAKER: Things are fine.
[06:10] SPEAKER: - Look.
[06:11] SPEAKER: - They're not fine, but they're fine.
[06:13] SPEAKER: - Yeah, everything's fine.
[06:15] SPEAKER: - I slept on the couch last night, not because
[06:17] SPEAKER: of any infractions, I didn't do anything wrong.
[06:19] SPEAKER: - Okay, you just couldn't be bothered to get up?
[06:22] SPEAKER: - No, my daughter has been in our room
[06:27] SPEAKER: the last couple of nights and we are a queen size bed house.
[06:30] SPEAKER: So it's three people in a bed is too many people.
[06:32] SPEAKER: - That's a lot.
[06:33] SPEAKER: - So I, discretion was the better part of valor last night.
[06:36] SPEAKER: I chose to just, you know, couch sleep.
[06:39] SPEAKER: - She's enough of an actual little person now
[06:41] SPEAKER: that she occupies a full half of the bed.
[06:43] SPEAKER: Not so much like a two people plus a tiny human.
[06:48] SPEAKER: Like there's kind of.
[06:49] SPEAKER: - If she just occupies half of the bed,
[06:51] SPEAKER: she's doing better than she ever has.
[06:53] SPEAKER: She's, you know, she's a full sprawl sleeper.
[06:57] SPEAKER: It's like arms, legs in all starfish positions.
[07:01] SPEAKER: - Punching way above her weight class on the bed occupancy.
[07:05] SPEAKER: - Her mass to volume ratio is off the charts.
[07:08] SPEAKER: - Oh boy.
[07:10] SPEAKER: - But yeah, so we're, we're a little,
[07:14] SPEAKER: things are, we're great.
[07:16] SPEAKER: We're doing great.
[07:17] SPEAKER: - Fine, fine, I think it's fine.
[07:18] SPEAKER: - What are we going to talk about today?
[07:20] SPEAKER: Well, first off.
[07:22] SPEAKER: - Yes.
[07:23] SPEAKER: - I want to point out, we're still reading
[07:23] SPEAKER: Hitchhiker's Guide.
[07:26] SPEAKER: - Yes.
[07:27] SPEAKER: - Oh, Brad, you've got to get on this.
[07:28] SPEAKER: It's coming up.
[07:29] SPEAKER: - I know, I need to get in.
[07:30] SPEAKER: So I read, I read both intros or I read both
[07:33] SPEAKER: like the forward and the introduction.
[07:35] SPEAKER: - The Neil Gaiman one and the Douglas Adams one.
[07:37] SPEAKER: - The forward written by Neil Gaiman,
[07:38] SPEAKER: which largely restated what was written
[07:40] SPEAKER: in the introduction by Douglas Adams, but that's okay.
[07:43] SPEAKER: - Yes.
[07:44] SPEAKER: - I found, I will say this.
[07:47] SPEAKER: I found the Douglas Adams authored introduction
[07:51] SPEAKER: wildly more charming.
[07:54] SPEAKER: - I, look.
[07:55] SPEAKER: - Nothing against Neil Gaiman, but like there was something,
[07:57] SPEAKER: there's just a certain lilt to the way that Douglas Adams,
[08:01] SPEAKER: like his phrasing, if that's what I'm in for, I'm excited.
[08:05] SPEAKER: That's what I'm trying to say.
[08:06] SPEAKER: - We'll get to this when we talk about the book,
[08:08] SPEAKER: but the thing that has struck me rereading this is how much
[08:12] SPEAKER: of modern discourse is shaped by the weird quirks,
[08:15] SPEAKER: especially in our friend circle,
[08:17] SPEAKER: by the weird quirks of the Douglas Adams' use of language.
[08:21] SPEAKER: - Okay, great.
[08:23] SPEAKER: I'm excited about that.
[08:24] SPEAKER: Like, there's just something about like that.
[08:27] SPEAKER: There's a certain idiosyncrasy of like speech patterns
[08:29] SPEAKER: that I really go for.
[08:31] SPEAKER: It's like in the intro, like it stuck with me.
[08:33] SPEAKER: That's how memorable it is that like,
[08:36] SPEAKER: when he was talking about being drunk in a field in Austria,
[08:39] SPEAKER: when he had the idea for the book.
[08:40] SPEAKER: - Outside Innsbruck.
[08:41] SPEAKER: - Yes, like his, the way he described his drunkenness was,
[08:46] SPEAKER: if I remember the phrasing,
[08:48] SPEAKER: we are speaking of the mild inability to stand up.
[08:52] SPEAKER: It's like, okay, you got the point across.
[08:53] SPEAKER: That's very, those are very tidy and economical
[08:56] SPEAKER: and slightly charming way to get that idea across.
[08:58] SPEAKER: - Yeah, so it's been fun rereading those.
[09:03] SPEAKER: This was our challenge for hitting a thousand patrons.
[09:08] SPEAKER: We're at almost 1100 now.
[09:10] SPEAKER: - Wow, geez.
[09:11] SPEAKER: - Yeah, a lot of people signed up this month.
[09:12] SPEAKER: A lot of people are stoked about Hitchhiker's Guide.
[09:14] SPEAKER: - Everybody wants to read Hitchhiker's Guide.
[09:16] SPEAKER: Thank you, that's, wow, that's flattering.
[09:18] SPEAKER: The last thing I'll say about it real quick is I,
[09:21] SPEAKER: it doesn't look that long.
[09:24] SPEAKER: - It's not.
[09:24] SPEAKER: - Maybe it's the omnibus edition that I've got,
[09:26] SPEAKER: but like I thought somebody had said,
[09:28] SPEAKER: it was like your kind of standard 300 page novel,
[09:30] SPEAKER: but like in the omnibus, it's like 180 pages or something.
[09:35] SPEAKER: - It's like, depending on how fast you read,
[09:38] SPEAKER: I think Mike Kendall told me it was going to be five hours.
[09:41] SPEAKER: - Oh, okay, yeah.
[09:42] SPEAKER: - Yeah, at the outside.
[09:44] SPEAKER: - Not a problem, I got plenty of time.
[09:46] SPEAKER: - It's a good Sunday afternoon.
[09:47] SPEAKER: - Yeah, so I'm getting ready to get into it
[09:48] SPEAKER: and I am looking forward to it.
[09:49] SPEAKER: I know somebody, at least one person I've seen
[09:51] SPEAKER: on the Discord said they just finished reading it
[09:53] SPEAKER: for the first time and we're just in love with it, so.
[09:56] SPEAKER: - It is, one of the things that we'll talk,
[09:59] SPEAKER: that I want to talk about is it is striking to me
[10:01] SPEAKER: how prescient it is for a thing that is written
[10:04] SPEAKER: in the late 70s about the modern technology of today.
[10:09] SPEAKER: - I don't know if that's a good thing or not.
[10:12] SPEAKER: - Pros and cons.
[10:12] SPEAKER: - Okay.
[10:13] SPEAKER: - Anyway, today we didn't mean to make this Nvidia month,
[10:17] SPEAKER: but Nvidia, yeah, I got announced.
[10:19] SPEAKER: - We went into this podcast with this topic in mind
[10:22] SPEAKER: and it occurred to me like we probably need to say
[10:23] SPEAKER: like this is not sponsored by Nvidia.
[10:26] SPEAKER: - Yeah, no, we, but--
[10:28] SPEAKER: - We are doing this show purely
[10:30] SPEAKER: because this is a very newsworthy topic.
[10:32] SPEAKER: - Well, I mean, the new GPUs came out
[10:33] SPEAKER: and they were also discussing.
[10:35] SPEAKER: - Yes, it's just like Nvidia has no chill at the moment.
[10:38] SPEAKER: They just keep dominating the news.
[10:40] SPEAKER: - Well, yeah, and we had the game streaming thing last week,
[10:42] SPEAKER: which is not entirely an Nvidia thing,
[10:44] SPEAKER: but like the thing that I like best
[10:47] SPEAKER: and I think is maybe not the easiest to use,
[10:49] SPEAKER: but the best results is the Nvidia solution with Moonlight.
[10:53] SPEAKER: - Can I ask real fast not to derail this?
[10:55] SPEAKER: How is Moonlight?
[10:56] SPEAKER: I don't know if we covered this.
[10:59] SPEAKER: How is Moonlight on the physical Steam Link,
[11:01] SPEAKER: the actual box that Valve sold?
[11:02] SPEAKER: Like, is it adequate?
[11:04] SPEAKER: - So that's where I run it.
[11:05] SPEAKER: It seems like the hardware in the, so the--
[11:09] SPEAKER: - Because that hardware cannot do H.265
[11:12] SPEAKER: is the reason that I ask, so I wonder--
[11:13] SPEAKER: - That's it, yeah.
[11:14] SPEAKER: - So I wonder if H.264 is up to the task.
[11:16] SPEAKER: - It's fine for 1080p.
[11:18] SPEAKER: I have not tried, you can't do 4K on the Steam Link.
[11:21] SPEAKER: - Yeah, okay.
[11:22] SPEAKER: - The setup is a little fiddly.
[11:26] SPEAKER: Like, there's not an auto updater for Moonlight,
[11:28] SPEAKER: and I'm not sure if that's because Moonlight is still early
[11:31] SPEAKER: or if it's that there's some limitation of the Steam Link
[11:34] SPEAKER: that won't let applications update themselves.
[11:36] SPEAKER: - But just performance latency-wise, it's fine?
[11:38] SPEAKER: - It's great.
[11:39] SPEAKER: I played a fair amount of Death Stranding,
[11:43] SPEAKER: or Watch Dogs 2 last night for, yeah, using it.
[11:46] SPEAKER: - I might actually get that Steam Link out of the box
[11:49] SPEAKER: and put Moonlight on it, see how it is.
[11:50] SPEAKER: - If you haven't, so I use one Steam Link that is WiFi,
[11:54] SPEAKER: one that is ethernet, they both work fine.
[11:58] SPEAKER: The WiFi one is a little bit,
[12:00] SPEAKER: occasionally you get graphics artifacts.
[12:02] SPEAKER: The wired one, I never see that.
[12:04] SPEAKER: - Are there kind of your commercial video streaming
[12:08] SPEAKER: entertainment apps available for the Steam Link?
[12:11] SPEAKER: Probably not.
[12:12] SPEAKER: - Not really.
[12:12] SPEAKER: You can't get Netflix for it.
[12:13] SPEAKER: - Right, okay, that's what I meant, okay.
[12:14] SPEAKER: So it could not be a good Apple TV replacement necessarily?
[12:18] SPEAKER: - I think you're better off with a dedicated piece
[12:20] SPEAKER: of hardware for that that is not Steam Link.
[12:23] SPEAKER: - So the flip side of that is I think probably,
[12:27] SPEAKER: I just got iOS 14 on, or TVOS 14 on my Apple TV yesterday.
[12:32] SPEAKER: So I haven't tried the new support for controllers,
[12:35] SPEAKER: but theoretically they fixed controller support
[12:37] SPEAKER: with this release of iOS or TVOS.
[12:40] SPEAKER: - Wait, was it broken before?
[12:42] SPEAKER: - Well, so it supported all the sticks and buttons
[12:44] SPEAKER: except for the clicky, the sticks on the Apple TV
[12:48] SPEAKER: and the iOS devices were the M5 standard.
[12:52] SPEAKER: So they would map to that,
[12:54] SPEAKER: which meant there was no clicky sticks,
[12:57] SPEAKER: which is fine if you're playing games built for iOS,
[12:58] SPEAKER: but if you're trying to play stuff that's built for the PC
[13:00] SPEAKER: that expects to have clicky sticks,
[13:02] SPEAKER: you had situations where there were weird cords
[13:04] SPEAKER: where you had to press the Xbox button
[13:06] SPEAKER: on your Xbox controller and it was not great.
[13:10] SPEAKER: - No.
[13:12] SPEAKER: - But today we're talking about why this ARM Nvidia deal,
[13:15] SPEAKER: and it's an interesting, the reason we're talking about it
[13:19] SPEAKER: is 'cause it's one of the biggest semiconductor deals
[13:22] SPEAKER: of all time.
[13:22] SPEAKER: - Yeah, for sure.
[13:24] SPEAKER: Nvidia has acquired ARM for $40 billion in cash and stock.
[13:28] SPEAKER: - Yes, Nvidia is the biggest semiconductor company
[13:32] SPEAKER: right now, they're the biggest chip designer.
[13:36] SPEAKER: And it's important because the two parts of,
[13:41] SPEAKER: so Nvidia, we all know Nvidia 'cause they make video cards
[13:43] SPEAKER: and they made the switch CPU, GPU, SOC,
[13:47] SPEAKER: you know, all of this other stuff.
[13:50] SPEAKER: - Games, mostly games kind of applications
[13:52] SPEAKER: is where they have been known forever.
[13:55] SPEAKER: - Right, but the games are kind of the secondary part
[13:59] SPEAKER: of Nvidia's business these days.
[14:02] SPEAKER: 'Cause it seems like they're trying to be the hardware
[14:05] SPEAKER: that runs the machine learning infrastructure of our future,
[14:08] SPEAKER: of future compute.
[14:10] SPEAKER: - Like I kind of had an inkling of this before,
[14:12] SPEAKER: but like this deal has made it very obvious
[14:14] SPEAKER: that Nvidia is kind of leading this whole other life,
[14:17] SPEAKER: I feel like.
[14:18] SPEAKER: Like they kind of have a double life now, right?
[14:20] SPEAKER: Of like everybody knows them for their gaming applications,
[14:22] SPEAKER: but like they're getting into data centers
[14:25] SPEAKER: and machine learning and potentially some other stuff
[14:28] SPEAKER: off of this deal that has nothing to do with games.
[14:31] SPEAKER: - Well, they've been in that for like,
[14:33] SPEAKER: there's a very good reason that they released Ampere first
[14:36] SPEAKER: as a data center product, right?
[14:38] SPEAKER: Not as a compute, a machine learning compute product,
[14:41] SPEAKER: not a gaming product.
[14:44] SPEAKER: - So Arm, if you don't know what Arm is,
[14:48] SPEAKER: Arm is a chip designer design company out of the UK
[14:55] SPEAKER: that basically spun out of Apple and Acorn, I think.
[14:59] SPEAKER: - Did, did it really? - Or Apple and Acorn
[15:01] SPEAKER: started it.
[15:02] SPEAKER: - I didn't know that.
[15:04] SPEAKER: - Hold on, I want to make sure I got that right.
[15:06] SPEAKER: - I had no idea.
[15:08] SPEAKER: Arm Holdings or Arm Limited now is the...
[15:12] SPEAKER: Yeah, so Acorn computers developed
[15:14] SPEAKER: the Acorn risk machine architecture in the '80s
[15:18] SPEAKER: and then Apple puts money into them.
[15:20] SPEAKER: - That's where Arm comes from.
[15:22] SPEAKER: - Yeah, but now Arm stands for advanced risk machine
[15:26] SPEAKER: rather than Acorn risk machine,
[15:28] SPEAKER: which is what they originally did.
[15:29] SPEAKER: Anyway, the point is they designed CPUs
[15:32] SPEAKER: and then licensed that technology out to everybody.
[15:34] SPEAKER: And they, unlike Intel, which say designs a CPU
[15:39] SPEAKER: and then makes that CPU and then sells it to you.
[15:42] SPEAKER: - And that's the only way you can get it.
[15:43] SPEAKER: - Yeah, that's it.
[15:45] SPEAKER: Arm says, "Hey, here's all the bits that go into our CPUs."
[15:48] SPEAKER: These systems on a chip, SOCs.
[15:52] SPEAKER: You can get whatever you want.
[15:54] SPEAKER: You can take the pieces you want.
[15:55] SPEAKER: You can, like, if you want this, here's a package,
[15:58] SPEAKER: here's the overall box.
[16:00] SPEAKER: And then you can kind of Chinese menu it out
[16:02] SPEAKER: where you say, "I want one of this math coprocessor
[16:06] SPEAKER: and six of these linear math accelerators."
[16:09] SPEAKER: And you can take the bits that they give you and assemble
[16:12] SPEAKER: them however you want.
[16:13] SPEAKER: - Right, and like if you're Apple, for example,
[16:14] SPEAKER: you can be like, "Ah, you can keep your GPU.
[16:16] SPEAKER: We have our own now, and we're gonna put our own GPU
[16:20] SPEAKER: on the die with your Arm stuff."
[16:22] SPEAKER: - Exactly, so you're licensing an instruction set
[16:26] SPEAKER: and a chip design is my understanding with Arm.
[16:29] SPEAKER: - Yes, I wrote, I started writing the notes.
[16:31] SPEAKER: Like, I don't know that either of us are equipped
[16:32] SPEAKER: to get into this, or if we even need to,
[16:34] SPEAKER: the whole kind of like CISC versus risk dichotomy.
[16:37] SPEAKER: - We can talk about it a little bit.
[16:38] SPEAKER: But like I've been interested in what it means for 25 years,
[16:43] SPEAKER: but I've never a hundred percent gotten my head around it.
[16:45] SPEAKER: - Yeah, so.
[16:48] SPEAKER: - Or should we even like talk about what an instruction set
[16:50] SPEAKER: is for people that don't know?
[16:52] SPEAKER: Like it's essentially the very base level operations
[16:56] SPEAKER: that a CPU is carrying out inside itself, right?
[16:59] SPEAKER: - Pretty much, and so at one level there's like the Turing,
[17:04] SPEAKER: the set of Turing, the things you need to be Turing complete
[17:07] SPEAKER: in a computer, which is like ands and ors and nors.
[17:10] SPEAKER: - You're talking Alan Turing, not the Turing GPU.
[17:14] SPEAKER: - Yeah, I'm talking about Alan Turing,
[17:15] SPEAKER: who the Turing GPU is named after, yes.
[17:17] SPEAKER: - Just to be clear.
[17:19] SPEAKER: - So at like the low level,
[17:21] SPEAKER: all of the math that happens in the computers
[17:23] SPEAKER: is like four or five different kinds
[17:24] SPEAKER: of mathematical operations.
[17:25] SPEAKER: But when you go up a level,
[17:28] SPEAKER: then you start to build specific functions on the chip
[17:33] SPEAKER: that are hardware accelerated
[17:34] SPEAKER: that makes certain types of math faster.
[17:36] SPEAKER: So like the difference between integer math
[17:38] SPEAKER: and floating point math is a good example of that.
[17:40] SPEAKER: If you think back to the old 386, 387 days,
[17:45] SPEAKER: Intel said, okay, these are mostly integer processors.
[17:48] SPEAKER: And if you need floating point math,
[17:50] SPEAKER: then you can buy this extra 387 chip that sockets in.
[17:55] SPEAKER: - A math co-processor that you can stick on your board.
[17:57] SPEAKER: - Yeah.
[17:58] SPEAKER: - And then eventually that logic started being included
[18:00] SPEAKER: just inside the CPU 'cause it made sense.
[18:03] SPEAKER: - Well, because it turns out
[18:04] SPEAKER: that we're a buttload of applications
[18:06] SPEAKER: for massive amounts of floating point math, like games.
[18:11] SPEAKER: - I don't know if this is illustrative or not
[18:15] SPEAKER: for people who aren't computer scientists,
[18:16] SPEAKER: which I certainly am not.
[18:17] SPEAKER: But for example, you can go on Wikipedia
[18:20] SPEAKER: and just pull up a list of every instruction
[18:22] SPEAKER: in the x86 instruction set, for example.
[18:25] SPEAKER: - For example.
[18:25] SPEAKER: - And you can scroll down and it's literally just like,
[18:28] SPEAKER: like there's an operation called add, which adds.
[18:31] SPEAKER: There's like add with carry.
[18:32] SPEAKER: There is convert byte to word, compare operands,
[18:36] SPEAKER: convert word to double word, decrement by one,
[18:40] SPEAKER: signed multiply, you know what I mean?
[18:42] SPEAKER: Like those are just, and to clarify for my own benefit
[18:45] SPEAKER: as well as anybody listening, like those are fixed functions
[18:49] SPEAKER: that are implemented in the hardware of the chip, right?
[18:51] SPEAKER: - When you are talking about somebody writing machine code,
[18:54] SPEAKER: they are writing code that calls
[18:55] SPEAKER: these specific instructions, right?
[18:57] SPEAKER: - Right.
[18:58] SPEAKER: - So, whereas if you write a C program,
[19:01] SPEAKER: you write a program that has some basic human readable logic
[19:05] SPEAKER: that isn't just a series of math instructions
[19:07] SPEAKER: that then becomes translated into that by a compiler.
[19:11] SPEAKER: - Right, so yeah, so like, so everything from,
[19:14] SPEAKER: at the end of the day, like everything from the highest level
[19:16] SPEAKER: like Python or JavaScript or whatever down to C,
[19:19] SPEAKER: to any compiled language, like at the end of the day,
[19:22] SPEAKER: all that's actually happening on the CPU
[19:23] SPEAKER: is these instructions being executed.
[19:25] SPEAKER: - It's interpreted down into this stuff, yes.
[19:26] SPEAKER: - It's just that the compiler is what handles
[19:27] SPEAKER: turning the human code into machine operations and okay.
[19:33] SPEAKER: - So in the 90s or late 80s, I guess,
[19:38] SPEAKER: the CPU architectures had gotten large
[19:41] SPEAKER: and the instruction sets were increasingly complicated.
[19:45] SPEAKER: - Complex you might say.
[19:46] SPEAKER: - Well, that's a retronym, you know.
[19:48] SPEAKER: - Is it?
[19:49] SPEAKER: - The complex was a response
[19:50] SPEAKER: to reduced instruction set computing.
[19:53] SPEAKER: - Oh, really?
[19:54] SPEAKER: Okay.
[19:54] SPEAKER: - Yeah, so these guys, I think the MIPS people
[19:57] SPEAKER: came up with this first,
[19:58] SPEAKER: but it seems like it was maybe developed
[19:59] SPEAKER: in parallel multiple places.
[20:00] SPEAKER: - What, like the concept of risk?
[20:02] SPEAKER: - Yeah.
[20:03] SPEAKER: - I think I read this morning, it started in Berkeley.
[20:05] SPEAKER: I think it started in academia.
[20:09] SPEAKER: - Well, anyway, but the point is,
[20:11] SPEAKER: rather than have a large complicated set of instructions
[20:14] SPEAKER: that did a bunch of accelerated things,
[20:16] SPEAKER: they were like, why don't we just make
[20:17] SPEAKER: all the processes run faster and keep them simpler?
[20:22] SPEAKER: And I think specifically a fixed length.
[20:25] SPEAKER: So where complicated instructions could use multiple cycles
[20:28] SPEAKER: per compute, these are the same size instructions
[20:33] SPEAKER: that run at the same speed so you can do things more.
[20:36] SPEAKER: - Okay, okay.
[20:37] SPEAKER: - We're getting into computer science stuff
[20:38] SPEAKER: that doesn't matter here.
[20:39] SPEAKER: - Yeah, yeah, yeah.
[20:39] SPEAKER: And that's pretty far out of our depth.
[20:42] SPEAKER: So you're saying like the instruction has to like execute
[20:44] SPEAKER: and complete within the same cycle kind of situation?
[20:46] SPEAKER: - Or within a specified number of cycles.
[20:49] SPEAKER: - I see, I see.
[20:50] SPEAKER: - The other thing that is important to know
[20:52] SPEAKER: about all this stuff,
[20:53] SPEAKER: is this was like in the '90s when Mac and PC people
[20:56] SPEAKER: were crazier and would yell at each other
[20:58] SPEAKER: about which computer was better.
[20:59] SPEAKER: - Yes.
[21:00] SPEAKER: - You'd hear all this RISC versus CISC stuff.
[21:02] SPEAKER: Back then, there was an appreciable difference.
[21:04] SPEAKER: - Well, a lot of power PC,
[21:06] SPEAKER: like people would wear power PC t-shirts and stuff like that.
[21:08] SPEAKER: - People wore all sorts of bad t-shirts.
[21:10] SPEAKER: Like I had one of those color shifting t-shirts.
[21:12] SPEAKER: We don't need to talk about sartorial choices.
[21:15] SPEAKER: The point is, in the modern context,
[21:18] SPEAKER: there isn't really a CISC versus RISC anymore.
[21:22] SPEAKER: There are RISC CPUs, RISC instruction sets
[21:25] SPEAKER: with complex elements,
[21:27] SPEAKER: and there are complex instruction sets
[21:29] SPEAKER: with the RISC-like elements.
[21:31] SPEAKER: They're all, everything's mishmashed together now.
[21:35] SPEAKER: - Yes, multiple people who absolutely know
[21:37] SPEAKER: what they're talking about have told me basically
[21:39] SPEAKER: that like, yeah, even a modern x86 CPU
[21:41] SPEAKER: has RISC-like elements inside it.
[21:44] SPEAKER: - Well, I mean, the point, the big thing,
[21:47] SPEAKER: we should do an episode about this
[21:48] SPEAKER: 'cause it's really interesting,
[21:49] SPEAKER: but the Pentium 4 was a turning point for all of this stuff.
[21:52] SPEAKER: 'Cause the Pentium 4, they were like,
[21:53] SPEAKER: we can make these really crazy complex, super deep pipelines
[21:56] SPEAKER: and we can predict what's gonna happen fast enough
[21:58] SPEAKER: that we can run it at like five, six gigahertz.
[22:00] SPEAKER: It's gonna be so fucking fast.
[22:02] SPEAKER: It's gonna blow your ears off.
[22:04] SPEAKER: It's gonna be the most amazing thing ever.
[22:05] SPEAKER: And then it didn't work.
[22:06] SPEAKER: And that was the moment that like the CISC wave broke
[22:09] SPEAKER: and they were like, well, maybe we should simplify
[22:12] SPEAKER: this whole thing and make it just parallel, real parallel.
[22:15] SPEAKER: So anyway.
[22:16] SPEAKER: - So, I mean, I guess back to the actual topic at hand,
[22:18] SPEAKER: moving back to the ARM stuff,
[22:21] SPEAKER: my understanding of why ARM is so big in the mobile space
[22:23] SPEAKER: is that primarily it's because it's so power efficient,
[22:26] SPEAKER: the performance per watt is very good.
[22:28] SPEAKER: Is that a direct result
[22:30] SPEAKER: of the way that the RISC stuff processes instructions?
[22:33] SPEAKER: - I don't know if it's a direct result
[22:34] SPEAKER: of the way the RISC stuff processes instructions
[22:37] SPEAKER: or a direct result of the design goals
[22:40] SPEAKER: of the ARM processors over the years.
[22:43] SPEAKER: - I see, I see.
[22:44] SPEAKER: - Like you can make a really power hungry RISC chip,
[22:47] SPEAKER: just like you can make a really efficient CISC chip,
[22:51] SPEAKER: you know, like there are some 0.3 watt TDP iX86 processors.
[22:58] SPEAKER: - Okay.
[23:00] SPEAKER: - But just--
[23:01] SPEAKER: - You're just not getting a lot of performance
[23:02] SPEAKER: out of them necessarily.
[23:03] SPEAKER: - Well, not even that, people don't use them
[23:06] SPEAKER: for the types of things that you use ARM processors for
[23:08] SPEAKER: because the market has gone in the ARM direction.
[23:10] SPEAKER: - Right, right, that's what I mean.
[23:10] SPEAKER: Like that's why there aren't phones
[23:12] SPEAKER: with X86 mobile chips in them.
[23:14] SPEAKER: - I mean, there are, you just don't know
[23:15] SPEAKER: what even there's what they are.
[23:16] SPEAKER: Yeah. - What?
[23:17] SPEAKER: - Yeah, you can buy X86, X86 Android phones
[23:20] SPEAKER: or you could for a while, I don't know if you still can.
[23:22] SPEAKER: - That's bizarre.
[23:24] SPEAKER: - So, okay, so SoftBank bought ARM a few years ago.
[23:28] SPEAKER: SoftBank is a investment holding company from Japan
[23:33] SPEAKER: who invested in such companies as WeWork, Theranos and Uber.
[23:37] SPEAKER: - Oh no, oh no.
[23:39] SPEAKER: - They--
[23:40] SPEAKER: - It's a questionable portfolio.
[23:42] SPEAKER: - Look, they've done some stuff that worked out for them,
[23:44] SPEAKER: but like it's not, they've not had great times
[23:46] SPEAKER: the last few years it seems like.
[23:48] SPEAKER: And they sold their stake in ARM
[23:55] SPEAKER: for $40 billion in stock and cash to Nvidia
[23:58] SPEAKER: or they want to, they've announced that they want to.
[24:01] SPEAKER: This is a huge deal.
[24:04] SPEAKER: It is interesting because they didn't talk about it
[24:07] SPEAKER: with investors or regulators
[24:09] SPEAKER: before they announced that they wanna do this.
[24:12] SPEAKER: And there's a pretty heavy regulatory burden here
[24:14] SPEAKER: 'cause the UK, the U.S., China, and maybe even Japan
[24:18] SPEAKER: are gonna care about this.
[24:19] SPEAKER: - Okay, and the EU, right?
[24:22] SPEAKER: - Well, no, 'cause it's UK.
[24:25] SPEAKER: So probably not the EU by the time the deal
[24:28] SPEAKER: has to pass regulatory bounds.
[24:29] SPEAKER: - Maybe not.
[24:31] SPEAKER: - But yeah, it's gonna be a while before this is active.
[24:37] SPEAKER: This is an announcement of intent,
[24:39] SPEAKER: not an announcement of success.
[24:43] SPEAKER: - It's interesting and it's important
[24:46] SPEAKER: because there are literally billions of ARM chips
[24:48] SPEAKER: shipped every year made by Apple, Qualcomm, Samsung, Nvidia,
[24:54] SPEAKER: and a bunch of other smaller companies
[24:55] SPEAKER: that you probably don't know about.
[24:56] SPEAKER: - Yeah, so should we just rattle off
[24:58] SPEAKER: kind of the most of the typical devices
[25:00] SPEAKER: you would find ARM chips in?
[25:01] SPEAKER: It's like every, it's every iPhone on the market,
[25:03] SPEAKER: just about every Android phone in the market.
[25:05] SPEAKER: - Almost every Android phone, yeah.
[25:06] SPEAKER: - Just damn near every tablet on the market of any kind.
[25:09] SPEAKER: The switch.
[25:10] SPEAKER: - Well, no, no, 'cause like Surface and stuff like that
[25:12] SPEAKER: are all x86, like anything.
[25:14] SPEAKER: - Yeah, but that's, I feel like they're sort of stretching
[25:16] SPEAKER: the definition of tablet there.
[25:17] SPEAKER: Like that's moving, that's almost moving
[25:19] SPEAKER: in the computer laptop-y kind of space.
[25:21] SPEAKER: - Well, I mean, it is a laptop.
[25:22] SPEAKER: It's just a laptop without a keyboard attached.
[25:24] SPEAKER: - Yeah, like the Surfaces are weird hybrid devices
[25:26] SPEAKER: that are, but the iPad, all the Amazon Fire stuff.
[25:31] SPEAKER: - Oculus Quest.
[25:32] SPEAKER: - Yes, yes, the Switch, the Nintendo Switch is ARM-based.
[25:37] SPEAKER: - Some routers, which is shocking.
[25:40] SPEAKER: - Oh, they're the Raspberry Pi, like all, practically,
[25:42] SPEAKER: practically all of the, the entire-
[25:44] SPEAKER: - The MiSTer.
[25:44] SPEAKER: - Well, yeah, the MiSTer has an ARM core on it
[25:46] SPEAKER: in addition to the FPGA.
[25:48] SPEAKER: Pretty much the entire single board computer scene,
[25:50] SPEAKER: like the Raspberry Pi and the,
[25:52] SPEAKER: all that stuff is ARM-based.
[25:54] SPEAKER: - I haven't torn one apart to see or looked at a tear down,
[25:57] SPEAKER: but my guess is like stuff like Alexa's and Google Homes
[26:00] SPEAKER: and all of those like Nest screen things,
[26:03] SPEAKER: your video doorbells, a lot of your web,
[26:05] SPEAKER: your like internet connected webcams.
[26:09] SPEAKER: - Any kind of internet of home smart device
[26:12] SPEAKER: probably has an ARM chip in it?
[26:14] SPEAKER: - Yeah.
[26:15] SPEAKER: - And it's an internet of things smart device.
[26:17] SPEAKER: - Like suffice to say, if it is not a,
[26:20] SPEAKER: if it's not an Intel or AMD made x86 based device,
[26:23] SPEAKER: like the odds are it's ARM.
[26:24] SPEAKER: - Well, no, there's also MIPS.
[26:26] SPEAKER: - Well, yeah, so like my router,
[26:28] SPEAKER: well, I didn't want to get into that.
[26:29] SPEAKER: That's kind of an edge case.
[26:30] SPEAKER: Like my router has a MIPS chip in it, but-
[26:32] SPEAKER: - So a lot of networking stuff
[26:33] SPEAKER: has MIPS chips because they're cheaper.
[26:35] SPEAKER: - In fact, we'll get to that.
[26:35] SPEAKER: That is a topic to talk about later,
[26:37] SPEAKER: but ARM is extraordinarily widespread is the point.
[26:40] SPEAKER: - Also, do you know what else has ARM?
[26:42] SPEAKER: - What's that?
[26:43] SPEAKER: - The world's fastest supercomputer.
[26:44] SPEAKER: - Oh, really?
[26:46] SPEAKER: - Yeah, so supercomputers and data centers
[26:49] SPEAKER: have butt loads of ARM chips now.
[26:51] SPEAKER: - Okay, so that is a relatively recent development, right?
[26:54] SPEAKER: - The last five, 10 years probably, yeah.
[26:56] SPEAKER: - Yeah, yeah.
[26:57] SPEAKER: - And the reason that happens is because in a data center,
[27:01] SPEAKER: in a supercomputer context, well, okay,
[27:04] SPEAKER: data, two different use cases.
[27:06] SPEAKER: Data centers care a lot about performance per watt
[27:09] SPEAKER: and performance both in terms of heat generated
[27:11] SPEAKER: and power consumed.
[27:12] SPEAKER: - Yeah, I feel like you hear a lot about the cooling needs
[27:15] SPEAKER: of a data center, right?
[27:16] SPEAKER: Like to the extent that that sometimes helps dictate
[27:20] SPEAKER: where they're built, stuff like that.
[27:21] SPEAKER: - There's a reason that data centers get built
[27:23] SPEAKER: on the Columbia River in Oregon,
[27:25] SPEAKER: and it's because there's a lot of hydroelectric power
[27:27] SPEAKER: and a lot of cool water.
[27:28] SPEAKER: - Yeah.
[27:30] SPEAKER: - So yeah, you see, basically that's where we're at.
[27:36] SPEAKER: Is like, there are some places where you want a big giant
[27:40] SPEAKER: X86 or X64 CPU with hundreds of cores and the whole thing.
[27:46] SPEAKER: But also there are places that there that you're gonna want
[27:48] SPEAKER: something that's lower power and less,
[27:50] SPEAKER: a little bit less capable maybe,
[27:51] SPEAKER: but also does exactly what you need it to in the place.
[27:54] SPEAKER: - Do you ever want to just hang out in a data center?
[27:59] SPEAKER: - They're really loud.
[28:00] SPEAKER: - Well, I'm sure you'd probably want some noise canceling.
[28:01] SPEAKER: I bet noise canceling headphones would work extremely well
[28:04] SPEAKER: in that white noise kind of environment.
[28:06] SPEAKER: But like, are you, 'cause that's the ideal use case
[28:10] SPEAKER: for noise canceling headphones.
[28:12] SPEAKER: But are you as big a fan of air conditioning as I am?
[28:15] SPEAKER: - I mean, right now, yes.
[28:16] SPEAKER: I am 100% a fan of air conditioning.
[28:18] SPEAKER: I would love to have air conditioning.
[28:19] SPEAKER: It seems like it'd be really nice.
[28:20] SPEAKER: - How cool do you think it is in your average data center?
[28:22] SPEAKER: Don't you want to just go in there
[28:24] SPEAKER: and like lie down on the floor for a while?
[28:26] SPEAKER: - So I've never been in a data center.
[28:27] SPEAKER: I've been in a supercomputer before and it was not
[28:32] SPEAKER: a comfortable environment for humans.
[28:33] SPEAKER: - Oh, is it too cold?
[28:35] SPEAKER: - It was very cold.
[28:36] SPEAKER: - Really?
[28:37] SPEAKER: Are we talking like convenience store
[28:39] SPEAKER: walk-in freezer type cold or what?
[28:42] SPEAKER: Surely not that cold.
[28:43] SPEAKER: - It was not, no, it was not 40 degrees.
[28:45] SPEAKER: It was probably 65.
[28:47] SPEAKER: - Oh, that sounds pretty good.
[28:48] SPEAKER: - It was chilly.
[28:49] SPEAKER: - That sounds pretty good.
[28:50] SPEAKER: - Look, I was in Texas and it was great
[28:53] SPEAKER: for the first minute or two.
[28:54] SPEAKER: And then you're like, "Oh man, it's kind of cold in here."
[28:56] SPEAKER: You know when you're walking through the grocery store
[28:59] SPEAKER: in the summertime and you get into the freezer aisle
[29:02] SPEAKER: or the open, the butter aisle where the refrigerators
[29:05] SPEAKER: are all open, wasting a ton of energy every day.
[29:07] SPEAKER: It's like that one where you're like,
[29:09] SPEAKER: "Oh man, I wish I wasn't wearing shorts right now,
[29:10] SPEAKER: but this feels okay."
[29:11] SPEAKER: - That sounds great.
[29:13] SPEAKER: - Yeah.
[29:15] SPEAKER: - If anybody can get us into a data center, let me know.
[29:18] SPEAKER: - The supercomputer angle is interesting too,
[29:20] SPEAKER: because in supercomputers, they use ARM processors
[29:23] SPEAKER: to reduce latency and like kind of traffic cop
[29:28] SPEAKER: a lot of the interactions between the other processors
[29:30] SPEAKER: in the setup and different supercomputers
[29:36] SPEAKER: have different requirements.
[29:37] SPEAKER: Like I spoke to somebody who works on supercomputers
[29:41] SPEAKER: that do fluid dynamics calculations where like
[29:44] SPEAKER: they're trying to figure out how wind interacts
[29:45] SPEAKER: with skyscrapers to affect weather patterns in big cities.
[29:50] SPEAKER: And in order to do that, like every particle
[29:54] SPEAKER: that simulates a bit of wind has to be able to talk
[29:57] SPEAKER: to every other particle 'cause they all interact
[29:59] SPEAKER: and you end up with these massively complex situations
[30:02] SPEAKER: where latency really matters.
[30:04] SPEAKER: And if one part of the simulation gets out of sync
[30:07] SPEAKER: with the others, then the whole thing has to be scrapped
[30:10] SPEAKER: and started over.
[30:11] SPEAKER: So like they build these clusters
[30:13] SPEAKER: so that there's a negligible latency
[30:16] SPEAKER: from one side to the other, and you need a bunch of CPUs
[30:19] SPEAKER: like evenly distributed through the network to do that.
[30:21] SPEAKER: - To manage that.
[30:22] SPEAKER: - Am I right in assuming that maybe the ARM cores
[30:24] SPEAKER: in that scenario are not handling the heavy math
[30:26] SPEAKER: of the simulation or they're just doing the,
[30:28] SPEAKER: like you said, the traffic hopping, the bookkeeping
[30:30] SPEAKER: to keep everything in sync and that sort of thing?
[30:33] SPEAKER: - Probably some of both, but I don't know.
[30:35] SPEAKER: I'm not an expert, that is a level of granularity
[30:38] SPEAKER: that I do not have on this topic.
[30:40] SPEAKER: - I mean, yeah, I'm just sort of like throwing that question
[30:42] SPEAKER: out into the ether, but I would wonder
[30:44] SPEAKER: if they're using like some kind of ASIC
[30:46] SPEAKER: or something like GPU ask almost
[30:49] SPEAKER: to handle the heavy compute aspect of that task.
[30:53] SPEAKER: - So my understanding is that they're set up in a way
[30:56] SPEAKER: that they, that you have processors
[31:00] SPEAKER: that are tuned for specific things.
[31:01] SPEAKER: So like you'll have x86 cores
[31:03] SPEAKER: for doing lots of big floating point math.
[31:05] SPEAKER: - That's what I was getting at.
[31:06] SPEAKER: - Like that is pipelineable and deep,
[31:09] SPEAKER: and then you'll do GPU cores for massively parallel stuff
[31:13] SPEAKER: where you need thousands upon thousands upon thousands
[31:15] SPEAKER: of cores, not hundreds of cores.
[31:17] SPEAKER: And then, yeah, I think the ARM processors
[31:19] SPEAKER: are gonna be the kind of making sure everybody gets fed
[31:23] SPEAKER: basically, all the different cores
[31:26] SPEAKER: are getting the data they need in the right time.
[31:30] SPEAKER: So, okay, so like, why does Nvidia want ARM?
[31:35] SPEAKER: - Why does Nvidia want ARM?
[31:37] SPEAKER: - Well, yeah, they like having market share.
[31:41] SPEAKER: - Yes.
[31:42] SPEAKER: - And if you look at, Nvidia is right now,
[31:47] SPEAKER: as a video game graphics company, sure,
[31:49] SPEAKER: they very much wanna be the machine learning,
[31:52] SPEAKER: AI hardware provider, and you can tell that
[31:57] SPEAKER: by looking at how they're pushing Ampere
[31:59] SPEAKER: to workstations and data centers.
[32:01] SPEAKER: You can look at the fact that they're putting 10,000
[32:04] SPEAKER: shader cores on these GPUs
[32:07] SPEAKER: with like dedicated machine learning units
[32:09] SPEAKER: and ARM also you can get dedicated machine learning
[32:13] SPEAKER: acceleration on ARM chips now.
[32:15] SPEAKER: - Yeah, and like we should mention,
[32:17] SPEAKER: like a lot of Nvidia's own messaging
[32:19] SPEAKER: around this deal pertains to AI specifically.
[32:22] SPEAKER: Like they, like the line I pulled out here
[32:24] SPEAKER: is that ARM is based in Cambridge
[32:26] SPEAKER: and they said that they want to turn the Cambridge location
[32:28] SPEAKER: into quote, a new global center of excellence in AI research.
[32:33] SPEAKER: - Yes, well, and like if you think about Nvidia's path
[32:38] SPEAKER: over the last 20 years, 'cause this is like
[32:41] SPEAKER: a 24 year old, 23 year old company now,
[32:43] SPEAKER: that they looked at the PC graphics market
[32:47] SPEAKER: and were like, look, we can build,
[32:48] SPEAKER: we can start building these,
[32:50] SPEAKER: A, there's a market for PC graphics,
[32:52] SPEAKER: but B, this market provides a path
[32:55] SPEAKER: to massively parallel machine learning accelerators,
[32:59] SPEAKER: ray tracing accelerators, all of that stuff.
[33:01] SPEAKER: And they use the market demand for games and 3D graphics
[33:08] SPEAKER: to do, to pay for the R&D to get to the point
[33:12] SPEAKER: that they had machine learning processors.
[33:13] SPEAKER: - Can we just generally use the terms AI
[33:17] SPEAKER: and machine learning interchangeably in this context?
[33:19] SPEAKER: 'Cause they use AI in most of their messaging.
[33:23] SPEAKER: - I think AI is the more consumer friendly term, right?
[33:27] SPEAKER: - But just to be clear, they mean basically the same thing.
[33:30] SPEAKER: - Yeah, I mean, we could just call it,
[33:31] SPEAKER: you know, linear, statistical linear math,
[33:34] SPEAKER: but it's, you know, people are gonna be
[33:36] SPEAKER: less interested in that.
[33:37] SPEAKER: But yeah, machine learning and AI, essentially, I mean not--
[33:39] SPEAKER: - Yeah, I'm just trying to clarify.
[33:41] SPEAKER: - I would say machine learning is probably a subset of AI
[33:44] SPEAKER: if we wanted to be highly technical,
[33:46] SPEAKER: but I don't think it matters.
[33:47] SPEAKER: - Okay.
[33:48] SPEAKER: So Nvidia has sold ARM chips in the past.
[33:52] SPEAKER: The Tegra is in the Switch.
[33:54] SPEAKER: It was in the Nvidia Shield and the Shield Pro,
[33:57] SPEAKER: I think the iron. - It still is, yeah.
[33:58] SPEAKER: Yeah, it still is.
[33:59] SPEAKER: I mean, yeah, I looked at the Tegra roadmap before this
[34:02] SPEAKER: and like they've got a new one on the way.
[34:05] SPEAKER: Of course, I mean, well, you know, whatever.
[34:06] SPEAKER: There are rumors about a new Switch next year.
[34:08] SPEAKER: So like there would be a new one in that, for example.
[34:13] SPEAKER: - Well, but like they haven't made big inroads
[34:15] SPEAKER: into the phone market.
[34:16] SPEAKER: There were a couple of phones that shipped on Tegra
[34:17] SPEAKER: a few years ago.
[34:18] SPEAKER: - Was that Razer phone on Nvidia?
[34:21] SPEAKER: - I feel like maybe--
[34:23] SPEAKER: - The gamer phone.
[34:24] SPEAKER: - It seemed like their performance per watt
[34:27] SPEAKER: was not, which in turn meant you had bad battery life
[34:31] SPEAKER: on the phone, wasn't where you wanted it.
[34:34] SPEAKER: But it's been pretty good on like the Switch,
[34:37] SPEAKER: while the initial launch Switch
[34:39] SPEAKER: didn't have the best battery life,
[34:41] SPEAKER: it's more than sufficient for like what I've been using
[34:44] SPEAKER: over the last four years or five years,
[34:45] SPEAKER: however long it's been.
[34:46] SPEAKER: - So one thought I had about this acquisition,
[34:48] SPEAKER: like obviously there's data centers
[34:50] SPEAKER: and super computer stuff.
[34:51] SPEAKER: There's machine learning research.
[34:53] SPEAKER: Like there's a lot of applications for this,
[34:55] SPEAKER: but like you tell me if this is an accurate perception
[34:58] SPEAKER: of the mobile market.
[34:59] SPEAKER: Like Apple's arm-based chips are like insane, right?
[35:03] SPEAKER: - God tier, yeah.
[35:04] SPEAKER: - Yeah, like they hired, they went out and hired
[35:06] SPEAKER: like some of the best chip designers in the world, right?
[35:09] SPEAKER: - And spent billions of dollars.
[35:10] SPEAKER: - Because they have unthinkable amounts of money.
[35:13] SPEAKER: But my understanding of the Android market
[35:15] SPEAKER: is like the Qualcomm's and like the Android,
[35:17] SPEAKER: or the ARM chips in that space just don't keep up, right?
[35:20] SPEAKER: With that.
[35:21] SPEAKER: - I don't think it's that they spec up,
[35:24] SPEAKER: like if you look at-
[35:25] SPEAKER: - Not saying they're bad necessarily, it's just that-
[35:27] SPEAKER: - Well, it's a different situation
[35:30] SPEAKER: 'cause like Apple knows what their software team is doing
[35:33] SPEAKER: and they have the software-
[35:34] SPEAKER: - Yeah, that's fair, that's fair.
[35:35] SPEAKER: - They turn their software roadmap
[35:35] SPEAKER: to the hardware roadmap so they can like really
[35:39] SPEAKER: get everything out of every bit of silicon
[35:40] SPEAKER: that they put in that chip.
[35:41] SPEAKER: - Right.
[35:42] SPEAKER: If say, if you're LG and you're buying a Qualcomm processor,
[35:47] SPEAKER: you probably aren't gonna spend the billion dollars a year
[35:49] SPEAKER: that you need to turn that off the shelf processor
[35:52] SPEAKER: into the custom processor like Apple does.
[35:55] SPEAKER: - Totally, but I mean, the point I'm getting at
[35:57] SPEAKER: is like to use the most recent example
[35:59] SPEAKER: when the iPhone SE came out,
[36:00] SPEAKER: like all the reviews were just like,
[36:03] SPEAKER: it is insane the performance advantage
[36:06] SPEAKER: that this budget Apple phone has
[36:08] SPEAKER: over the current flagship Android phones.
[36:10] SPEAKER: So what I'm getting at is like,
[36:12] SPEAKER: I wonder if Nvidia maybe sees an opportunity
[36:14] SPEAKER: to become like the dominant SOC supplier
[36:18] SPEAKER: in the Android space off of this.
[36:20] SPEAKER: - So my guess is that they're probably going to pull out
[36:24] SPEAKER: of the Android SOC space as part of the regulatory burden
[36:28] SPEAKER: for this deal to happen.
[36:29] SPEAKER: - Interesting, yes, I actually, yeah,
[36:30] SPEAKER: that's totally a good point.
[36:32] SPEAKER: That's like antitrust stuff, not withstanding,
[36:34] SPEAKER: could they be possibly be looking to do that?
[36:37] SPEAKER: - I think Nvidia is more interested in the data center
[36:39] SPEAKER: and making sure that things like TensorFlow cores
[36:42] SPEAKER: end up in other people's phones.
[36:44] SPEAKER: - Okay, 'cause this exact idea was floated as well
[36:48] SPEAKER: in some of the Android press that I looked at
[36:51] SPEAKER: or something going to the Android media market
[36:52] SPEAKER: and like people speculating that like,
[36:54] SPEAKER: there's kind of nothing stopping Nvidia
[36:56] SPEAKER: from holding the best of like, they can keep licensing.
[37:02] SPEAKER: - I think the regulatory stuff in China and the UK
[37:05] SPEAKER: would probably be the thing that stops that.
[37:07] SPEAKER: - The idea to expand on it is just that
[37:09] SPEAKER: they could keep licensing the arm designs
[37:10] SPEAKER: that they currently make to the same customers,
[37:13] SPEAKER: but that they could like have a slightly competitive,
[37:17] SPEAKER: slightly more competitive version.
[37:19] SPEAKER: - Yeah, they'll keep the good one for themselves.
[37:21] SPEAKER: - Right, or something along those lines.
[37:23] SPEAKER: - I would be shocked if that is allowed to happen.
[37:27] SPEAKER: Like in the US, I wouldn't be surprised
[37:28] SPEAKER: if it's allowed to happen.
[37:29] SPEAKER: The EU and the UK, that's not going to fly.
[37:32] SPEAKER: - Maybe this is just expressing my complete lack of faith
[37:35] SPEAKER: in any kind of antitrust action to ever take place again.
[37:39] SPEAKER: Unless it's politically motivated.
[37:41] SPEAKER: - I think, well, here's the thing.
[37:43] SPEAKER: Given that Nvidia has essentially no market share
[37:45] SPEAKER: in that space right now, my guess is that they sacrifice
[37:48] SPEAKER: the potential future there for licensing out instruction set
[37:53] SPEAKER: 'cause here's the thing is if they do something
[37:55] SPEAKER: too anti-competitive, there are other similar,
[37:59] SPEAKER: but not directly compatible instructions
[38:02] SPEAKER: that we use out there, including some open stuff.
[38:05] SPEAKER: - Yes, that stuff is probably,
[38:07] SPEAKER: it's not even arm related necessarily,
[38:08] SPEAKER: but that's probably the actual most fascinating aspect
[38:11] SPEAKER: of this topic, but we'll get to that.
[38:13] SPEAKER: - Yeah, so I don't, I think my guess is that Nvidia
[38:18] SPEAKER: will protect the switch and shield business
[38:21] SPEAKER: for set top boxes and 'cause honestly,
[38:25] SPEAKER: like if you're thinking about Nvidia,
[38:26] SPEAKER: if Nvidia's Tegra problem is that they perform really well,
[38:29] SPEAKER: but their performance per watt and battery life are bad,
[38:33] SPEAKER: tablets make a ton of sense like the switch,
[38:35] SPEAKER: like the shield tablet, set top boxes make a ton of sense
[38:39] SPEAKER: where your performance per watt is less important
[38:41] SPEAKER: as long as you can passively cool it, nobody cares.
[38:43] SPEAKER: So I think we'll see them sacrifice the ability
[38:47] SPEAKER: to be in phones 'cause it like, it's not like they're not,
[38:49] SPEAKER: is it, here's the question you need to ask is,
[38:52] SPEAKER: is it better for Nvidia to make a little bit of money
[38:56] SPEAKER: on every single one of the one or 2 billion phones
[38:59] SPEAKER: that are sold every year or to make a lot of money
[39:02] SPEAKER: on some small percentage of the market
[39:04] SPEAKER: because they piss everybody off
[39:05] SPEAKER: and they all switched to MIPS or whatever.
[39:07] SPEAKER: - Sure, sure, yes, that is an actual exact question I have
[39:10] SPEAKER: when we get to the MIPS and RISC-V stuff,
[39:12] SPEAKER: but I'll save that for now.
[39:15] SPEAKER: - I think it's, like I said, I think it's much more likely
[39:17] SPEAKER: that we'll see it go the other way
[39:18] SPEAKER: where Nvidia makes tensor cores and things like that,
[39:23] SPEAKER: like specific parts of the current GPU architecture,
[39:27] SPEAKER: things like their H.264 and H.265 live encoders,
[39:31] SPEAKER: which are really good,
[39:32] SPEAKER: make them available to ARM licensees
[39:35] SPEAKER: along with the other IP.
[39:37] SPEAKER: - What you're saying is it's less likely
[39:38] SPEAKER: that Nvidia is going to take the ARM tech
[39:40] SPEAKER: and kind of pull it behind their curtain
[39:42] SPEAKER: and more likely that some of the Nvidia tech
[39:43] SPEAKER: is gonna bleed back into the publicly available ARM stuff?
[39:46] SPEAKER: - I would really, really hope that the regulatory,
[39:50] SPEAKER: one of the three or four regulatory agencies involved
[39:54] SPEAKER: would ensure that that doesn't happen.
[39:56] SPEAKER: - Right, so like an example is like ARM has a GPU design
[39:59] SPEAKER: that they can license along with the CPU stuff,
[40:03] SPEAKER: but you're saying that like Nvidia graphics
[40:06] SPEAKER: could end up replacing that Mali GPU design, for example.
[40:10] SPEAKER: - Even some subset, like small bits and pieces.
[40:13] SPEAKER: The other thing is like their PowerVR
[40:16] SPEAKER: has a whole ARM GPU division,
[40:19] SPEAKER: like they sell a buttload of ARM GPUs too.
[40:21] SPEAKER: Like there are, there have been three companies
[40:24] SPEAKER: making ARM GPUs for a while, four if you count Apple,
[40:27] SPEAKER: even though they don't sell those external vendors.
[40:31] SPEAKER: Like there's, the beautiful thing about ARM
[40:34] SPEAKER: is if LG wants or Qualcomm wants Nvidia's GPU,
[40:40] SPEAKER: they can do that.
[40:40] SPEAKER: If they want their own GPU, they can do that.
[40:42] SPEAKER: If they want PowerPC, they can do that.
[40:43] SPEAKER: And you can assemble the chips however you want.
[40:45] SPEAKER: It's up to you.
[40:47] SPEAKER: It's like Lego, but way more complicated
[40:49] SPEAKER: and expensive to build.
[40:52] SPEAKER: So yeah, like I think that's it.
[40:54] SPEAKER: I think, and so the outside edge case for this
[40:58] SPEAKER: is that I think we're gonna see Nvidia dropping ARM CPUs
[41:03] SPEAKER: in weird places in the future.
[41:05] SPEAKER: We saw a little bit of this with the Ampere stuff
[41:07] SPEAKER: and the direct storage API to accelerate storage,
[41:12] SPEAKER: which in reality isn't going to start happening
[41:14] SPEAKER: for like two or three years
[41:15] SPEAKER: because it takes the API's a while to roll out.
[41:19] SPEAKER: I think we'll see in the next five or 10 years,
[41:23] SPEAKER: we'll see Nvidia dropping ARM CPUs on GPUs to reduce the,
[41:30] SPEAKER: simply because there's often math
[41:32] SPEAKER: that you need to do in games that is latency dependent.
[41:35] SPEAKER: Like this is one of the benefits consoles have,
[41:38] SPEAKER: is that because the consoles use a shared CPU memory pools,
[41:42] SPEAKER: where the CPU and GPU are both talking
[41:44] SPEAKER: to the same memory all the time,
[41:45] SPEAKER: it's really inexpensive for the GPU to pass something off
[41:49] SPEAKER: to the CPU and then come back to the GPU again.
[41:51] SPEAKER: - Also the CPU and the GPU are on the same die,
[41:53] SPEAKER: so there is no--
[41:54] SPEAKER: - Often, yeah.
[41:55] SPEAKER: - There's a system bus to communicate over.
[41:58] SPEAKER: - Right, and whereas on the PC,
[42:00] SPEAKER: the GPU has to talk across the PCI express bus,
[42:03] SPEAKER: which like on a GPU that's running at 3,000,
[42:06] SPEAKER: thousands of megahertz,
[42:08] SPEAKER: you're looking at sometimes five or 10 or 20 clock cycles
[42:11] SPEAKER: on the GPU before a communication can happen
[42:14] SPEAKER: across the PCI express bus.
[42:15] SPEAKER: Anyway.
[42:16] SPEAKER: - My one question about that idea of including
[42:18] SPEAKER: like arm designs on a graphics card, for example,
[42:22] SPEAKER: is like, I mean, would you agree that Nvidia
[42:24] SPEAKER: probably employs a lot of the best integrated circuit
[42:27] SPEAKER: designers in the world at this point?
[42:29] SPEAKER: - I, it would be hard for me to say that.
[42:31] SPEAKER: - Okay.
[42:32] SPEAKER: - But sure, the results are good.
[42:34] SPEAKER: - That's what I mean.
[42:35] SPEAKER: - Yeah.
[42:36] SPEAKER: - The proof is in the pudding there, it seems,
[42:38] SPEAKER: but like, do you think like a general purpose,
[42:40] SPEAKER: like arm set up on a graphics card would make more sense
[42:43] SPEAKER: than like, or let me back up.
[42:45] SPEAKER: - They seem really good at designing logic on their cards
[42:49] SPEAKER: built for purpose, right?
[42:50] SPEAKER: Or designed for purpose, like this direct storage stuff.
[42:53] SPEAKER: Like you assume that there is hardware on those GPUs
[42:56] SPEAKER: that is very good at decompressing that data.
[42:59] SPEAKER: Like would it make sense to have a more general purpose unit
[43:04] SPEAKER: on there as opposed to just designing whatever you need?
[43:08] SPEAKER: - Look, it's not outside the realm of possibility
[43:09] SPEAKER: that we're going to be plugging NVMe drives
[43:11] SPEAKER: onto your video card in five years.
[43:15] SPEAKER: - Okay, so at that point, a very small low power arm core
[43:18] SPEAKER: that handled that IO would make sense or something like that.
[43:21] SPEAKER: - I see, yeah.
[43:21] SPEAKER: - Okay.
[43:22] SPEAKER: - Like that's kind of what I was getting at
[43:25] SPEAKER: a couple of weeks ago when we did the 3080 stuff.
[43:28] SPEAKER: When I mentioned, I mentioned that the graphics card
[43:31] SPEAKER: is rapidly becoming like the central feature of a PC.
[43:34] SPEAKER: - Hey guys, plug your mouse into your video card
[43:37] SPEAKER: for the best performance.
[43:38] SPEAKER: - Right, like have your video card
[43:39] SPEAKER: handle your storage IO now.
[43:41] SPEAKER: You know, like at some point the graphics card
[43:42] SPEAKER: is the computer.
[43:44] SPEAKER: - Well, I mean, that's what Jen Sun's been trying
[43:46] SPEAKER: to make happen for 20 years.
[43:47] SPEAKER: - That's what I mean.
[43:48] SPEAKER: Like, I feel like we're moving toward that
[43:50] SPEAKER: where like what does this, I mean, obviously you need a CPU,
[43:53] SPEAKER: but like it's increasingly marginalized it seems like.
[43:56] SPEAKER: - It was literally a talking point,
[43:59] SPEAKER: I think around the like the GeForce,
[44:01] SPEAKER: probably the 5800 launch, 5900 launch maybe
[44:04] SPEAKER: when they started doing compute
[44:05] SPEAKER: on like general purpose compute on GPUs.
[44:09] SPEAKER: He's like, yeah, this is going to be the most important
[44:10] SPEAKER: processor in your computer from now on.
[44:12] SPEAKER: - Right.
[44:13] SPEAKER: - And you know, turns out probably sounded hyperbolic then,
[44:17] SPEAKER: but it was probably correct.
[44:18] SPEAKER: - Like I'm trying to conceptualize in my head
[44:21] SPEAKER: the weird fuzzy shifting line between the graphics card
[44:25] SPEAKER: and like say the motherboard.
[44:27] SPEAKER: Like for expansion purposes, it would never make sense
[44:31] SPEAKER: to turn a graphics card into a motherboard
[44:32] SPEAKER: and literally have the GPU on the board
[44:35] SPEAKER: and just plug a CPU into it.
[44:36] SPEAKER: But like, it feels like we're kind of like,
[44:38] SPEAKER: that distinction is becoming less meaningful.
[44:42] SPEAKER: Does that make sense?
[44:44] SPEAKER: - Yeah, well, when you look at those big compute clusters
[44:46] SPEAKER: where they have like a huge board
[44:48] SPEAKER: with a shitload of PCI slots and lanes,
[44:50] SPEAKER: and then you just drop eight boards into it with one CPU,
[44:54] SPEAKER: like the amount of power that goes to doing the GPU math
[44:59] SPEAKER: versus the CPU math is strongly, strongly, strongly
[45:03] SPEAKER: in favor of the GPU side.
[45:04] SPEAKER: - Right.
[45:06] SPEAKER: - It's a weird, like computers are going to be real weird
[45:08] SPEAKER: in about 10 years.
[45:09] SPEAKER: - Yeah, totally.
[45:10] SPEAKER: - That's the TLDR.
[45:11] SPEAKER: - Totally, that's kind of what I'm getting at.
[45:12] SPEAKER: But like at some point, if the graphics card
[45:13] SPEAKER: is handling 90% of your system functionality anyway,
[45:16] SPEAKER: why not just make that the whole system?
[45:18] SPEAKER: - Well, yeah.
[45:20] SPEAKER: I mean, it's, I mentioned that there are people
[45:25] SPEAKER: in our audience I know who are further into this,
[45:28] SPEAKER: down this rabbit hole of what computers look like
[45:29] SPEAKER: in 10 years than we are.
[45:31] SPEAKER: - Yes.
[45:31] SPEAKER: - I'm really curious to hear their reaction
[45:33] SPEAKER: to this conversation.
[45:34] SPEAKER: - I literally copied and pasted a conversation
[45:36] SPEAKER: out of the discord a few days ago
[45:37] SPEAKER: about like where CPUs are going in the next 10 to 15 years
[45:40] SPEAKER: that like frankly made my head explode.
[45:44] SPEAKER: Some really wild stuff in there.
[45:46] SPEAKER: - Well, I mean, and this isn't like, this isn't,
[45:49] SPEAKER: it's not idle speculation.
[45:52] SPEAKER: Like look at what a computer looked like in 2000.
[45:55] SPEAKER: When I moved to California,
[45:56] SPEAKER: I think I had a dual core Celeron machine.
[46:00] SPEAKER: So two physical packages,
[46:03] SPEAKER: socketed into two sockets on the motherboard.
[46:06] SPEAKER: And like the difference in that computer
[46:09] SPEAKER: and the computer that is in my pocket now is astounding.
[46:12] SPEAKER: - Orders of magnitude, right?
[46:14] SPEAKER: - Yeah, it's because of ARM.
[46:15] SPEAKER: - Yeah.
[46:16] SPEAKER: - And like everything, the wireless internet connection
[46:18] SPEAKER: is better than my wired internet connection was.
[46:20] SPEAKER: My screen is way higher resolution.
[46:22] SPEAKER: I can do more things at the same time than I could then.
[46:26] SPEAKER: Like it's, yeah, it's bonkers.
[46:27] SPEAKER: The whole thing's crazy.
[46:28] SPEAKER: - Yes.
[46:29] SPEAKER: Yeah, the acceleration of development of technology
[46:31] SPEAKER: has been pretty dizzying for me.
[46:34] SPEAKER: - It's a lot of, yeah, a lot of that is on ARM.
[46:37] SPEAKER: Like the rise of phones that move billions of units a year,
[46:44] SPEAKER: like left the opportunity to really push the technology
[46:48] SPEAKER: because there was a lot of money at stake and yeah.
[46:52] SPEAKER: - But just, I mean, not to get off on some old man rant,
[46:55] SPEAKER: but like if you started on,
[46:57] SPEAKER: if you started out with parallel ports
[46:58] SPEAKER: and text mode only displays and that sort of thing,
[47:03] SPEAKER: like where we are now versus where we are then
[47:05] SPEAKER: is like, quite frankly, hard to grapple with sometimes.
[47:08] SPEAKER: - It has been a long road.
[47:09] SPEAKER: - Yeah, but I'll finish a short one.
[47:13] SPEAKER: - I mean, yeah, you remember,
[47:15] SPEAKER: I remember taking hours to download a one megabyte driver.
[47:20] SPEAKER: - Yeah, yeah.
[47:23] SPEAKER: - So Brad, what do you think this means for phones?
[47:25] SPEAKER: - 300 baud, 300 baud.
[47:26] SPEAKER: - I never had a 300 baud.
[47:27] SPEAKER: I started with a 14.4, I think.
[47:29] SPEAKER: - Yeah, so did I.
[47:30] SPEAKER: I didn't either.
[47:30] SPEAKER: I just, I know it existed.
[47:31] SPEAKER: I'm sorry, what were you asking?
[47:33] SPEAKER: - Look, I couldn't hear you.
[47:34] SPEAKER: My audio coupler came off the phone.
[47:36] SPEAKER: So we got to re-sync this modem call.
[47:40] SPEAKER: - Jam that thing back in there.
[47:41] SPEAKER: You got to rerun your init string.
[47:44] SPEAKER: - What does this mean for phones?
[47:46] SPEAKER: - For phones?
[47:47] SPEAKER: - For phones.
[47:48] SPEAKER: - Oh, you mean like right now?
[47:49] SPEAKER: - Yeah, right now.
[47:49] SPEAKER: If V is buying ARM, shit, is my phone going to be bad now?
[47:52] SPEAKER: - We covered my apparently abortive idea
[47:55] SPEAKER: that they were going to try to dominate the Android space.
[47:57] SPEAKER: So probably not a ton at the moment.
[48:01] SPEAKER: Maybe the Android, like you said,
[48:03] SPEAKER: the Android SOCs get better GPUs or something like that,
[48:07] SPEAKER: or more machine learning acceleration, something like that.
[48:10] SPEAKER: But like that's probably five, maybe not five,
[48:14] SPEAKER: but like that's probably like minimum three,
[48:16] SPEAKER: four years away from showing up and shipping products, right?
[48:18] SPEAKER: With the regulatory overhead and the R&D to product cycle
[48:24] SPEAKER: lead times and stuff like that.
[48:25] SPEAKER: - I think they suggested this is going to take 18 months
[48:28] SPEAKER: to get approval and maybe close.
[48:30] SPEAKER: - Right.
[48:31] SPEAKER: - So yeah, I think my assumption is,
[48:35] SPEAKER: my assumption is there's not going to be too much work
[48:37] SPEAKER: happening by other parties on anything that comes out of
[48:41] SPEAKER: this until that deal is closed.
[48:42] SPEAKER: - This is, here's like a really high level legal
[48:45] SPEAKER: and business question.
[48:46] SPEAKER: Is there anything to stop them from beginning R&D
[48:48] SPEAKER: with this purchase in mind prior to the deal
[48:51] SPEAKER: being fully approved?
[48:53] SPEAKER: - I have no idea.
[48:54] SPEAKER: - Yeah, right.
[48:55] SPEAKER: Like, I don't know any, I quite literally don't know anybody
[48:57] SPEAKER: who would know the answer to that question.
[48:59] SPEAKER: We need like high level, like IP lawyer types
[49:03] SPEAKER: and regulatory, like antitrust law types
[49:06] SPEAKER: to answer a question like that, right?
[49:08] SPEAKER: - The amount of anxiety I had when I had bought a house,
[49:11] SPEAKER: but hadn't closed on it yet and had gotten the keys
[49:13] SPEAKER: and started knocking holes in the walls.
[49:15] SPEAKER: - Right.
[49:16] SPEAKER: - Was very high, I can't imagine.
[49:18] SPEAKER: - That's literally that question, right?
[49:19] SPEAKER: Like, is it okay for them to start knocking holes
[49:21] SPEAKER: in the dry wall before the--
[49:24] SPEAKER: - I don't, I honestly don't know.
[49:25] SPEAKER: - Before they've got the deed in their hands.
[49:27] SPEAKER: - I mean, do they exchange IP?
[49:29] SPEAKER: - I guess, I mean, probably not.
[49:30] SPEAKER: - Probably not.
[49:31] SPEAKER: - 'Cause it's all proprietary and secret.
[49:32] SPEAKER: - Yeah, you're probably right, you're probably right.
[49:35] SPEAKER: - I mean, but I assume they're talking,
[49:36] SPEAKER: I assume like they start, I assume anytime you have,
[49:39] SPEAKER: like I know in media spaces, 'cause I've worked
[49:41] SPEAKER: with some people who went through a giant merger recently,
[49:44] SPEAKER: like they were talking to, everybody was talking
[49:45] SPEAKER: to everybody, but nothing was happening,
[49:48] SPEAKER: but everybody knew what was coming.
[49:50] SPEAKER: So I'd say that's probably what happened.
[49:51] SPEAKER: I don't know, I'm curious to hear what people think.
[49:53] SPEAKER: - Do you ever--
[49:54] SPEAKER: - If you're in a video, send us an email or signal me.
[49:58] SPEAKER: - Do you ever have this tendency when you see
[49:59] SPEAKER: a deal of this magnitude?
[50:00] SPEAKER: I mean, like you said, this is like basically
[50:02] SPEAKER: practically the biggest deal that's ever been made.
[50:04] SPEAKER: Do you ever have a tendency to look at that
[50:06] SPEAKER: and try to ascribe some kind of like organization
[50:08] SPEAKER: and method to the whole thing?
[50:10] SPEAKER: Like think like, oh, there must be a plan,
[50:12] SPEAKER: like fully written down and they know exactly
[50:14] SPEAKER: what they're doing and they're gonna execute it.
[50:15] SPEAKER: But like then what you just described
[50:17] SPEAKER: is the actual reality of, it's actually just a bunch
[50:19] SPEAKER: of human beings flailing around, trying to figure it out
[50:23] SPEAKER: for a period of months to years, right?
[50:25] SPEAKER: - I mean, you don't spend $40 billion
[50:27] SPEAKER: if you don't have a plan for what you want to do
[50:29] SPEAKER: with the thing you're buying, right?
[50:31] SPEAKER: - Right, but it's not all set in stone.
[50:33] SPEAKER: - You know, I mean, I think everything's fluid
[50:36] SPEAKER: and like there's some parts of the arm business
[50:37] SPEAKER: that are getting spun off that Nvidia didn't want,
[50:40] SPEAKER: stuff like that.
[50:41] SPEAKER: - Yeah, I mean, there's much more of a human,
[50:43] SPEAKER: like in the moment kind of human elements
[50:46] SPEAKER: of the decision-making, right?
[50:47] SPEAKER: Than you might think.
[50:48] SPEAKER: - Yeah, yeah, yeah.
[50:49] SPEAKER: - Yes.
[50:55] SPEAKER: I was a little, $40 billion is a staggering amount of money.
[51:00] SPEAKER: Given the scale of that arm business,
[51:02] SPEAKER: I was a little bit surprised that it was only $40 billion.
[51:06] SPEAKER: - I could see that, sure.
[51:07] SPEAKER: - Like when arm sold a few years ago for 20 or 30 billion,
[51:11] SPEAKER: whatever it was, I was kind of surprised that it was only,
[51:16] SPEAKER: I assume that the licensing fees aren't onerous per chip.
[51:20] SPEAKER: - Okay, well that is a good segue into the next topic then,
[51:23] SPEAKER: 'cause I was wondering about that exact thing.
[51:26] SPEAKER: - Yeah, I mean, I'm curious.
[51:30] SPEAKER: I mean, these are very not public numbers.
[51:32] SPEAKER: It's funny, it's even hard.
[51:35] SPEAKER: I was trying to figure out how much
[51:37] SPEAKER: of the global Microsoft processor business,
[51:40] SPEAKER: like across all architectures
[51:42] SPEAKER: and all markets arm represented,
[51:45] SPEAKER: 'cause it has to be a significant portion.
[51:50] SPEAKER: But like that stuff is even all buried
[51:52] SPEAKER: in really expensive analyst reports
[51:54] SPEAKER: about microprocessor, if I wanted to pay five or $6,000,
[51:59] SPEAKER: I could have gotten a report that would let me know
[52:00] SPEAKER: exactly how much microprocessor business arm gets
[52:04] SPEAKER: and what their licensing model looks like.
[52:05] SPEAKER: But I didn't spend that five grand, Brad, I'm sorry.
[52:08] SPEAKER: - Sounds like we need a $5,000 tier on the Patreon next month
[52:11] SPEAKER: to get this analyst report in our hands.
[52:14] SPEAKER: - Give us the 5,000 bucks,
[52:15] SPEAKER: we'll buy one analyst report a month.
[52:16] SPEAKER: - That's right, that's right.
[52:17] SPEAKER: - And we'll put it right back into the pod.
[52:20] SPEAKER: - You can just send us the report if you have it.
[52:22] SPEAKER: I won't tell anybody.
[52:23] SPEAKER: (indistinct)
[52:27] SPEAKER: - So yeah, I guess that brings us
[52:29] SPEAKER: to kind of the last big topic here,
[52:30] SPEAKER: which you have written these notes
[52:32] SPEAKER: as are there alternatives to arm for phones?
[52:35] SPEAKER: - Not really right now, but maybe soon.
[52:37] SPEAKER: - But yeah, it seems like it's getting there.
[52:38] SPEAKER: - Well, I mean, Intel has been trying to push an x86
[52:41] SPEAKER: that part for phones for a really long time
[52:43] SPEAKER: and nobody's biting.
[52:44] SPEAKER: - Good luck with that, as we said.
[52:47] SPEAKER: - But I think MIPS and RISC-V have both shown.
[52:53] SPEAKER: RISC-V.
[52:55] SPEAKER: - Is it RISC-V?
[52:56] SPEAKER: - Yeah, it's RISC-V.
[52:57] SPEAKER: - Oh, I thought it was RISC-V.
[52:58] SPEAKER: - It's the fifth, yeah, I agree, that sounds better,
[53:00] SPEAKER: but it is the fifth generation of RISC.
[53:02] SPEAKER: - If it was, why is the hyphen in there if it's five?
[53:05] SPEAKER: - According to them.
[53:06] SPEAKER: It's right there on the Wikipedia page, man.
[53:07] SPEAKER: - I hate this.
[53:08] SPEAKER: - I don't know what to tell you.
[53:09] SPEAKER: - I regret, look, I was pro RISC, so RISC-V is-
[53:13] SPEAKER: - RISC-V pronounced RISC-V.
[53:16] SPEAKER: - God.
[53:17] SPEAKER: - That's literally how the Wikipedia page starts.
[53:18] SPEAKER: That also came out of Berkeley, actually.
[53:19] SPEAKER: So I looked into it while we were talking about it.
[53:21] SPEAKER: We were both right earlier.
[53:23] SPEAKER: The concept of RISC started at Berkeley,
[53:25] SPEAKER: but then MIPS was the company
[53:27] SPEAKER: that spun off of that research
[53:29] SPEAKER: and was the first commercial entity to offer a RISC.
[53:33] SPEAKER: - But it seems like there was parallel development
[53:36] SPEAKER: happening in other places at the same time,
[53:37] SPEAKER: 'cause DC had a MIPS chip, a RISC chip, and all that.
[53:41] SPEAKER: - Is that like how calculus was created
[53:43] SPEAKER: by more than one person simultaneously?
[53:44] SPEAKER: - Leibniz and Leibniz and Newton, yes.
[53:48] SPEAKER: But-
[53:49] SPEAKER: - Newton got the win, though,
[53:50] SPEAKER: when he spoke English, it turns out.
[53:51] SPEAKER: - Yeah, yeah.
[53:53] SPEAKER: - But he had a better publicist, I think.
[53:55] SPEAKER: - Yeah, that whole Apple thing is very easy to remember.
[53:57] SPEAKER: - Yeah, also apocryphal.
[53:59] SPEAKER: - Yes, I'm sure, I'm sure.
[54:00] SPEAKER: But there's a little bit of public myth-making
[54:03] SPEAKER: goes a long way in getting people to remember you,
[54:05] SPEAKER: it turns out.
[54:07] SPEAKER: So yeah, which one do we wanna talk about?
[54:09] SPEAKER: Well, it's kind of the same topic.
[54:11] SPEAKER: - Well, RISC-V is gonna be, is an open source architecture.
[54:15] SPEAKER: - It's literally an open source instruction set
[54:17] SPEAKER: in the way that open source software is freely available.
[54:21] SPEAKER: - You can take that instruction set
[54:23] SPEAKER: and add a few billion dollars and hundreds of people
[54:27] SPEAKER: and maybe thousands of people,
[54:29] SPEAKER: and you can have a CPU in a few years.
[54:31] SPEAKER: - Yeah, I guess that's the big difference here,
[54:32] SPEAKER: is that a single programmer can take
[54:35] SPEAKER: an open source repository and do something cool with it,
[54:39] SPEAKER: and the barrier is very low.
[54:40] SPEAKER: - Depends on the repository, but yeah.
[54:42] SPEAKER: - Well, you know what I mean, though.
[54:42] SPEAKER: A single person can develop software pretty effectively,
[54:45] SPEAKER: depending on what they're doing and how skilled they are,
[54:46] SPEAKER: but to take an open instruction set
[54:50] SPEAKER: and actually turn it into a tangible product
[54:51] SPEAKER: takes unthinkable amounts of money and skill
[54:56] SPEAKER: to design the chip.
[54:58] SPEAKER: Getting chips made is incredibly expensive and difficult.
[55:00] SPEAKER: It's not like some little garage startup
[55:04] SPEAKER: is not gonna take this and change the world, right?
[55:06] SPEAKER: - I mean, they might.
[55:07] SPEAKER: - Well, maybe, maybe.
[55:08] SPEAKER: - That's not out of the question.
[55:09] SPEAKER: - I guess not.
[55:10] SPEAKER: - It's not, this isn't...
[55:14] SPEAKER: - I still firmly, you know, that's a really good question.
[55:17] SPEAKER: Like, is there, is this still a market
[55:20] SPEAKER: that a garage startup or even like a billion dollar startup
[55:24] SPEAKER: can compete in?
[55:25] SPEAKER: - Maybe.
[55:26] SPEAKER: - Probably.
[55:27] SPEAKER: - The thing that stuck out to me in reading about RISC-V
[55:30] SPEAKER: is it's something about ARM, actually,
[55:32] SPEAKER: that I didn't really, it had never occurred to me,
[55:34] SPEAKER: which is that like RISC-V being open,
[55:36] SPEAKER: you can take the literal base instruction set
[55:38] SPEAKER: and do whatever you want with it.
[55:39] SPEAKER: - Right.
[55:40] SPEAKER: - I did not realize that an ARM license
[55:42] SPEAKER: is not anywhere near that permissive.
[55:45] SPEAKER: You're essentially, like you can extend the ARM designs,
[55:49] SPEAKER: but not that much in comparison.
[55:51] SPEAKER: Does that make sense?
[55:52] SPEAKER: Like, it sounds like you're largely kind of taking the cores
[55:55] SPEAKER: that ARM offers with some customizations
[55:57] SPEAKER: that you can specify, but you can't like,
[55:59] SPEAKER: you cannot just take the ARM instruction set and license it
[56:01] SPEAKER: and then make your own shift from the ground up with it.
[56:03] SPEAKER: - No, you can do that.
[56:04] SPEAKER: That's what Apple did specifically.
[56:06] SPEAKER: - Oh, okay.
[56:07] SPEAKER: This thing I was reading was wrong about that then.
[56:10] SPEAKER: - Well, what you're saying is you can't license
[56:14] SPEAKER: the instructions for ARM and then build your own chip.
[56:21] SPEAKER: They'll, like a lot of businesses, if the price is right,
[56:25] SPEAKER: you can do the thing you're looking for, right?
[56:27] SPEAKER: - Sure, but maybe that's like written
[56:29] SPEAKER: into the licensing agreement and then it costs more
[56:31] SPEAKER: or something like that, right?
[56:31] SPEAKER: - Right.
[56:32] SPEAKER: - That's what I'm getting at is like,
[56:34] SPEAKER: you're not just gonna pay ARM a flat rate,
[56:35] SPEAKER: take those instructions and then go off to the races
[56:37] SPEAKER: and do your own thing.
[56:38] SPEAKER: - Yeah, if you license the Cortex-A9,
[56:41] SPEAKER: you're licensing the chunks that make up the Cortex-A9
[56:44] SPEAKER: and then how you assemble them is up to you.
[56:45] SPEAKER: - That's what I'm getting at is you,
[56:47] SPEAKER: whereas the difference is with something like a RISC-V
[56:49] SPEAKER: or actually now MIPS, which we're getting to,
[56:52] SPEAKER: you can take the literal instructions
[56:54] SPEAKER: and like build your own CPU core from the ground up
[56:57] SPEAKER: is my understanding.
[56:59] SPEAKER: - And that is, so I'm gonna be interested to see
[57:04] SPEAKER: if open source projects can handle this.
[57:07] SPEAKER: My guess is that probably they can't.
[57:10] SPEAKER: Like it seems like too big a thing for the typical chaos
[57:13] SPEAKER: of an open, of a big open source project.
[57:16] SPEAKER: - I could see that.
[57:18] SPEAKER: - I also don't know.
[57:20] SPEAKER: - Should we mention the MIPS stuff before we get too much?
[57:22] SPEAKER: - Yeah, the MIPS stuff is interesting.
[57:26] SPEAKER: - They have opened, they have open sourced
[57:28] SPEAKER: their architecture, which like you said,
[57:29] SPEAKER: has been around since the '80s, right?
[57:30] SPEAKER: Like MIPS, my router has a MIPS 64 CPU, for example.
[57:36] SPEAKER: - Yeah, like a lot of networking hardware
[57:39] SPEAKER: is powered by MIPS processors.
[57:40] SPEAKER: - So it's really interesting, especially interesting
[57:42] SPEAKER: in the context of my router, the edge router four,
[57:44] SPEAKER: 'cause like I SSH into it, it's just running Debian,
[57:47] SPEAKER: but it is a, you know, it had obviously by nature,
[57:50] SPEAKER: it has to be a MIPS 64 compiled version of Debian.
[57:54] SPEAKER: - Yeah.
[57:55] SPEAKER: - So like when I'm going on, when I go on there
[57:56] SPEAKER: and add like the app repository to look around
[57:58] SPEAKER: for like software to install on there,
[58:00] SPEAKER: like there have to be MIPS 64 compiled versions
[58:03] SPEAKER: of those, of those, those binaries available to actually
[58:06] SPEAKER: do anything with them, you know what I mean?
[58:09] SPEAKER: - It's, it's, but like, it's an interesting,
[58:14] SPEAKER: like it's, if you look at ARM as embedded processors,
[58:17] SPEAKER: which is what we would have called these like 10 years ago,
[58:20] SPEAKER: MIPS is the original kind of embedded processor, right?
[58:23] SPEAKER: - Right, right.
[58:24] SPEAKER: - But I think there was even a MIPS version
[58:26] SPEAKER: of Windows NT up until four.
[58:28] SPEAKER: - Sounds right, 'cause I think they were
[58:30] SPEAKER: in workstations back then, right?
[58:32] SPEAKER: - Yeah, they, they were, they were early risk chips
[58:35] SPEAKER: and people were excited about them
[58:36] SPEAKER: so they ended up in weird places.
[58:38] SPEAKER: - So this article, this article you linked
[58:40] SPEAKER: basically makes it sound like MIPS has just lost
[58:42] SPEAKER: dramatic amounts of market share to ARM over the years.
[58:45] SPEAKER: - Well, that's the, so the challenge is that as ARM
[58:47] SPEAKER: has developed more performance per watt for higher end CPUs,
[58:51] SPEAKER: for higher end SoCs for phones, they, they still have like
[58:55] SPEAKER: a really deep well of designs that go back, you know,
[58:58] SPEAKER: and can scale down to less capable devices
[59:01] SPEAKER: that don't need, don't need the same kind of hardware.
[59:04] SPEAKER: But yeah, they still, they're 10 billion chips
[59:06] SPEAKER: chipped that use MIPS, I think is what they advertise.
[59:09] SPEAKER: - Okay, that's not exactly nothing.
[59:12] SPEAKER: - Like a small chip manufacturer still is selling billions
[59:16] SPEAKER: and billions of chips.
[59:17] SPEAKER: - Okay, that's fair.
[59:18] SPEAKER: But the point is they have now opened their architecture.
[59:21] SPEAKER: - Yeah.
[59:22] SPEAKER: - Just like RISC-V except they are a commercial company
[59:25] SPEAKER: that has also made this open.
[59:27] SPEAKER: - So yeah, like there are, so the takeaway on this,
[59:31] SPEAKER: if the, if the question we're answering is,
[59:33] SPEAKER: are there alternatives for ARM for phones?
[59:35] SPEAKER: The answer kind of not right now, but maybe in the future.
[59:39] SPEAKER: - Well, they're like, they're available.
[59:40] SPEAKER: It's just, nobody has done the insane amount of like work
[59:42] SPEAKER: it would take to actually implement them in that role.
[59:45] SPEAKER: - Yeah, and in the timescale, like if we're looking at,
[59:48] SPEAKER: you know, two to three years to close this deal,
[59:51] SPEAKER: is there a way, like, will there, could Apple switch
[59:55] SPEAKER: from ARM to MIPS or ARM to RISC-V, five, whatever?
[59:59] SPEAKER: RISC-V, RISC-V, could they in the time, like,
[1:00:04] SPEAKER: I wonder if Apple would have committed to full ARM
[1:00:08] SPEAKER: after this deal closed.
[1:00:10] SPEAKER: I know that's been a thing that's been obviously
[1:00:12] SPEAKER: in the works for 10 years on their side,
[1:00:14] SPEAKER: but Apple and Nvidia have a kind of inimical relationship
[1:00:18] SPEAKER: that has not been great.
[1:00:21] SPEAKER: And I'll be interested to see how they react to this.
[1:00:23] SPEAKER: - Yes, so that was like, when you mentioned like,
[1:00:25] SPEAKER: maybe the ARM licensing fees are not actually that high,
[1:00:27] SPEAKER: like that was the exact question I wanted to address
[1:00:29] SPEAKER: with this was, would Apple switch?
[1:00:32] SPEAKER: Is it worth it?
[1:00:32] SPEAKER: Like, you know, Apple being like one of the most
[1:00:35] SPEAKER: cash-rich companies in the world, right?
[1:00:37] SPEAKER: Is it, and with the number of devices they sell,
[1:00:39] SPEAKER: like are the licensing fees on ARM just low enough
[1:00:41] SPEAKER: that it's not worth the investment for them to switch
[1:00:43] SPEAKER: to a licensing-free kind of situation?
[1:00:47] SPEAKER: - So there's multiple components.
[1:00:50] SPEAKER: One is that ARM has been optimized relentlessly
[1:00:52] SPEAKER: for the last 13 years in a way that these other
[1:00:55] SPEAKER: architectures have not, but like,
[1:00:57] SPEAKER: they're not as fully understood.
[1:00:59] SPEAKER: They don't know where the slow and the fast,
[1:01:01] SPEAKER: where the bottlenecks are.
[1:01:02] SPEAKER: They don't, like, we don't have institutional knowledge
[1:01:05] SPEAKER: in how to design really fast, capable MIPS processors
[1:01:09] SPEAKER: or RISC-V processors for phones and other tablets
[1:01:14] SPEAKER: and set-top boxes.
[1:01:15] SPEAKER: - Like, I'm just throwing this out there,
[1:01:17] SPEAKER: but this would probably be at least like,
[1:01:19] SPEAKER: what, a decade long undertaking to implement?
[1:01:22] SPEAKER: - Yeah, my guess is that Apple looked at the power
[1:01:25] SPEAKER: performance curves on ARM in like 2007,
[1:01:28] SPEAKER: when they started selling iPhones and they were like,
[1:01:30] SPEAKER: hey, you know, if this continues at this rate,
[1:01:32] SPEAKER: the Intel line and the ARM line are gonna cross
[1:01:35] SPEAKER: in about 2020, 2018.
[1:01:38] SPEAKER: And at that point we could start not doing Intel chips
[1:01:40] SPEAKER: anymore if we wanted.
[1:01:41] SPEAKER: And that's been the process this whole time.
[1:01:43] SPEAKER: That's been in the works this whole time.
[1:01:44] SPEAKER: So yeah, you're looking at 10 years from now,
[1:01:48] SPEAKER: from the starting line to when you start seeing
[1:01:51] SPEAKER: viable competitors shipping.
[1:01:53] SPEAKER: And like everything else, you'll start seeing
[1:01:55] SPEAKER: like weird dev kits two or three years before
[1:01:59] SPEAKER: the actual viable products get done.
[1:02:01] SPEAKER: Like, you know, if you think back to that first Chromebook
[1:02:04] SPEAKER: Intel released, it was slow and useless.
[1:02:07] SPEAKER: And then two years later, they're pretty nice
[1:02:09] SPEAKER: and worth having.
[1:02:10] SPEAKER: - Yeah, but some of the, just the little bit
[1:02:12] SPEAKER: I've been reading about these open architectures,
[1:02:14] SPEAKER: like analysts in that space seem pretty bullish
[1:02:17] SPEAKER: on their future though.
[1:02:19] SPEAKER: - I would, I think that's, I think,
[1:02:22] SPEAKER: I think anytime you get a monolithic company,
[1:02:27] SPEAKER: like the people will be hedging,
[1:02:29] SPEAKER: but we'll be investing in these as a hedge
[1:02:31] SPEAKER: against NVIDIA and against NVIDIA behaving badly.
[1:02:34] SPEAKER: - We've got one gigantic company now controlling
[1:02:37] SPEAKER: a frightening amount of the space.
[1:02:39] SPEAKER: - Yeah.
[1:02:40] SPEAKER: - These are just alternatives that might become more relevant
[1:02:44] SPEAKER: in the future. - Yeah.
[1:02:45] SPEAKER: So that's, I guess that's it.
[1:02:47] SPEAKER: - Yeah, it's a fascinating topic.
[1:02:48] SPEAKER: It's like, we're obviously not,
[1:02:50] SPEAKER: neither hardware designers nor programmers.
[1:02:52] SPEAKER: It's like pretty-- - Nor analysts, frankly.
[1:02:54] SPEAKER: - Heady stuff here.
[1:02:55] SPEAKER: And we're just kind of trying to make sense of it
[1:02:57] SPEAKER: as best we can, but I think it's fascinating.
[1:02:59] SPEAKER: - Look, man, it's a confusing world.
[1:03:01] SPEAKER: We just want to figure out what's going on out there.
[1:03:03] SPEAKER: - Yeah.
[1:03:06] SPEAKER: - We've reached the portion of the show
[1:03:07] SPEAKER: where we thank our patrons.
[1:03:09] SPEAKER: - Yeah.
[1:03:10] SPEAKER: - The currently 1,090 people.
[1:03:13] SPEAKER: - Jeez.
[1:03:14] SPEAKER: - Like what we do enough to give us money
[1:03:17] SPEAKER: or want to get access to the Discord or want to hear
[1:03:19] SPEAKER: the patron exclusive episode every month.
[1:03:21] SPEAKER: - Yes, yes.
[1:03:22] SPEAKER: Or just want us to continue to continue to keep doing this.
[1:03:25] SPEAKER: - Yeah, you can find out how to support the Patreon
[1:03:28] SPEAKER: at patreon.com/techpod.
[1:03:32] SPEAKER: Next week is our email episode.
[1:03:33] SPEAKER: - Is it?
[1:03:34] SPEAKER: - Yeah.
[1:03:35] SPEAKER: - Okay, that's good.
[1:03:36] SPEAKER: That means I've got one more episodes worth of buffer
[1:03:39] SPEAKER: before I have to finish that book.
[1:03:41] SPEAKER: - Yeah. - Okay.
[1:03:42] SPEAKER: - Yeah, you've got two weeks, maybe three,
[1:03:44] SPEAKER: depending on whether we do.
[1:03:45] SPEAKER: It's good to know what kind of timeframe
[1:03:47] SPEAKER: you're working with.
[1:03:48] SPEAKER: - Look, just Sunday afternoon, Brad.
[1:03:50] SPEAKER: - Yeah, yeah, just need to find a sunbeam
[1:03:52] SPEAKER: and kind of relax in it.
[1:03:55] SPEAKER: - But yeah, so we're gonna, I'll open up
[1:03:57] SPEAKER: a Hitchhiker's Guide to the Galaxy channel
[1:04:00] SPEAKER: in the Discord this week.
[1:04:01] SPEAKER: So if patrons want to discuss it,
[1:04:03] SPEAKER: then they will be able to.
[1:04:06] SPEAKER: We've had a lot of, as always, lovely conversations.
[1:04:09] SPEAKER: I learn something new every time I dip into the Discord.
[1:04:13] SPEAKER: And I learned about panorama stitching of,
[1:04:20] SPEAKER: how photography on Mars works the other day,
[1:04:23] SPEAKER: which was amazing.
[1:04:26] SPEAKER: Just talking about how the panorama stitched
[1:04:28] SPEAKER: and how you do self-inspections of the wheels
[1:04:30] SPEAKER: and the rover and all that stuff.
[1:04:32] SPEAKER: It was awesome, super cool.
[1:04:33] SPEAKER: - We have someone there who works on it.
[1:04:35] SPEAKER: - Yeah, yeah.
[1:04:38] SPEAKER: So if you want to find out more
[1:04:41] SPEAKER: about how to join the Patreon or back the show,
[1:04:43] SPEAKER: it's two bucks to get access to the Discord,
[1:04:45] SPEAKER: and you can find out about that at patreon.com/techpod.
[1:04:50] SPEAKER: As always, thank you to our executive producer-level patrons,
[1:04:53] SPEAKER: Andrew Cotton, David Allen, and Jacob Chappell.
[1:04:56] SPEAKER: - Yes, thank you so much.
[1:04:57] SPEAKER: - And everybody who supports the show.
[1:04:58] SPEAKER: - Yes, thank you, everyone.
[1:04:59] SPEAKER: - And if you can't support the show financially,
[1:05:02] SPEAKER: tell your friends.
[1:05:02] SPEAKER: We had so many good tweets last week,
[1:05:04] SPEAKER: I had to stop retweeting them all
[1:05:07] SPEAKER: because I didn't want to be spammy.
[1:05:09] SPEAKER: But we appreciate you.
[1:05:11] SPEAKER: - Friendly and flattering tweets out there.
[1:05:13] SPEAKER: I should, maybe I should start using Twitter again.
[1:05:15] SPEAKER: I don't know.
[1:05:16] SPEAKER: - Look, Brad, let's not get crazy here.
[1:05:18] SPEAKER: - I don't know, man.
[1:05:20] SPEAKER: - You know what?
[1:05:23] SPEAKER: I have found the secret to no bummer Twitter.
[1:05:25] SPEAKER: - Yeah?
[1:05:26] SPEAKER: - Well, it's not no bummer, it's mostly no bummer Twitter.
[1:05:29] SPEAKER: (laughing)
[1:05:30] SPEAKER: - Speaking of hedging. - You turn off free tweets.
[1:05:32] SPEAKER: - Okay.
[1:05:33] SPEAKER: - And you do that by just going to twitter.com
[1:05:35] SPEAKER: and typing in the mute filters area.
[1:05:38] SPEAKER: You do a keyword mute for RT colon,
[1:05:41] SPEAKER: and then they go away forever.
[1:05:42] SPEAKER: - I was going to say,
[1:05:43] SPEAKER: I was surprised that they built that functionality in,
[1:05:45] SPEAKER: but it sounds like they didn't.
[1:05:46] SPEAKER: - Oh, they don't.
[1:05:47] SPEAKER: - They didn't, but you figured it out.
[1:05:48] SPEAKER: - I told a Twitter engineer
[1:05:49] SPEAKER: that you could do this the other day by accident
[1:05:51] SPEAKER: or an ex Twitter engineer that you could do this
[1:05:53] SPEAKER: and I might've fucked us, but I apologize if I did.
[1:05:59] SPEAKER: And then also if you filter out HTTPS colon slash slash,
[1:06:03] SPEAKER: you'll get rid of almost all the links.
[1:06:05] SPEAKER: I think images still come through,
[1:06:07] SPEAKER: but it's nobody promoting bullshit,
[1:06:09] SPEAKER: which I realized is a little bit hypocritical
[1:06:10] SPEAKER: on my part, but whatever.
[1:06:12] SPEAKER: And yeah, because the thing is people see something
[1:06:16] SPEAKER: that they feel like, oh man, this is important,
[1:06:17] SPEAKER: but I don't want to talk about this.
[1:06:18] SPEAKER: It's a huge bummer.
[1:06:19] SPEAKER: I'll just smash the retweet button.
[1:06:21] SPEAKER: I've done my job.
[1:06:22] SPEAKER: And then it's just,
[1:06:23] SPEAKER: everybody's just retweeting shit that bums them out.
[1:06:27] SPEAKER: So yeah, anyway, Twitter's bad, but the tech pod is good.
[1:06:31] SPEAKER: So thank you all for supporting us.
[1:06:33] SPEAKER: We appreciate it.
[1:06:34] SPEAKER: - We are a better Twitter.
[1:06:35] SPEAKER: - Yes.
[1:06:36] SPEAKER: Well, but the thing is the discord is the thing,
[1:06:39] SPEAKER: like I get out of the discord now,
[1:06:42] SPEAKER: what I used to get out of Twitter
[1:06:44] SPEAKER: when Twitter was good in like 2008,
[1:06:46] SPEAKER: and it was just me goofing with my friends.
[1:06:47] SPEAKER: - And in 2008, I was getting out of Twitter
[1:06:49] SPEAKER: what I previously got out of IRC.
[1:06:51] SPEAKER: So like, whatever, this is a whole episode topic,
[1:06:55] SPEAKER: but I think the internet is undertaking a process
[1:06:59] SPEAKER: of wrapping back around to smaller,
[1:07:01] SPEAKER: more enclosed communities again, perhaps.
[1:07:03] SPEAKER: - Hold on, where did you get out of,
[1:07:06] SPEAKER: what did you get out of IRC?
[1:07:08] SPEAKER: Did we replace human contact with IRC in the 90s?
[1:07:11] SPEAKER: Is that what happened?
[1:07:12] SPEAKER: - I mean, that's very presumptuous of you to think
[1:07:13] SPEAKER: that I had human contact in the first place.
[1:07:15] SPEAKER: (laughing)
[1:07:19] SPEAKER: Look, there were not a lot of people importing
[1:07:22] SPEAKER: weird Japanese PlayStation games
[1:07:24] SPEAKER: in my little hodunk rural town.
[1:07:26] SPEAKER: - That's the reason you were the anime editor,
[1:07:28] SPEAKER: I guess, for so long.
[1:07:29] SPEAKER: - I had to go far afield.
[1:07:31] SPEAKER: - Fair.
[1:07:32] SPEAKER: - To find like minds, let's say.
[1:07:34] SPEAKER: - Fair.
[1:07:36] SPEAKER: Okay, well, we'll see you next week.
[1:07:37] SPEAKER: If you have questions, send them into techpod@content.town.
[1:07:40] SPEAKER: We're doing questions next week,
[1:07:41] SPEAKER: so please send us some good ones,
[1:07:43] SPEAKER: and we will see you all next time.
[1:07:46] SPEAKER: Bye, everybody.
[1:07:46] SPEAKER: (upbeat music)
