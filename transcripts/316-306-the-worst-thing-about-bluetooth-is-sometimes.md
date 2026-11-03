---
episode: 316
title: 306: The Worst Thing About Bluetooth Is "Sometimes"
date: 2025-09-28
guests: none
duration: 1:19:38
---

[00:00] SPEAKER: I guess we're doing dark mode today.
[00:02] SPEAKER: - Yeah, I turned on the camera and I turned on the call
[00:07] SPEAKER: and I just saw Brad lit only by the light screen
[00:11] SPEAKER: of what I assume is a light mode monitor.
[00:13] SPEAKER: - See, I've got a Google Doc.
[00:15] SPEAKER: Okay, 'cause as we have well-documented,
[00:17] SPEAKER: Google Docs does not have a dark mode.
[00:19] SPEAKER: So I'm staring at our list of questions
[00:22] SPEAKER: in this giant white browser window.
[00:24] SPEAKER: Check this out.
[00:26] SPEAKER: - Oh, wow.
[00:27] SPEAKER: - That's a dark tab.
[00:28] SPEAKER: - Oh, hello.
[00:30] SPEAKER: - There's no lighting in this room
[00:31] SPEAKER: other than from these monitors
[00:32] SPEAKER: because it's like seven in the morning here.
[00:34] SPEAKER: - There's one strand of fairy lights
[00:36] SPEAKER: in the background behind you.
[00:37] SPEAKER: - Yeah, true.
[00:38] SPEAKER: Yes, I haven't, I didn't do my hair yet.
[00:39] SPEAKER: You're wearing a V-neck white t-shirt.
[00:42] SPEAKER: - The white V-neck t-shirt that I slept in.
[00:45] SPEAKER: - Straight out of bed.
[00:46] SPEAKER: You've got travel coming up, business travel.
[00:48] SPEAKER: And so our recording schedule is a bit wonkier than usual.
[00:52] SPEAKER: - Yeah, we haven't had to do it early, early in a long time.
[00:54] SPEAKER: 7 a.m. used to be our go-to during the pandemic
[00:57] SPEAKER: when I was working at Stray Bomb Bay and had like
[00:59] SPEAKER: a full-time nine to five job.
[01:01] SPEAKER: But yeah, we haven't done it this early in a minute.
[01:04] SPEAKER: But it's, you know, anytime is podcast time.
[01:07] SPEAKER: All I need is a microphone and a...
[01:09] SPEAKER: - That's right.
[01:10] SPEAKER: - Well, I guess a microphone.
[01:11] SPEAKER: - Last night, there was a fun moment last night
[01:13] SPEAKER: 'cause we did the patron episode late last night
[01:15] SPEAKER: and you commented as we were shutting down,
[01:18] SPEAKER: you commented that you got to see
[01:19] SPEAKER: how off our clocks were because you surmised
[01:22] SPEAKER: that all the lights in this office room went off for me
[01:26] SPEAKER: at one time and you surmised that they were all
[01:28] SPEAKER: on a smart timer, which they are.
[01:30] SPEAKER: And you were able to see how offset our clocks are
[01:34] SPEAKER: by watching my lights go off.
[01:35] SPEAKER: - Yeah, either my Windows clock hasn't updated in a minute
[01:38] SPEAKER: or your Pi or whatever's running your cameras
[01:41] SPEAKER: is off by about 10 seconds, so.
[01:44] SPEAKER: - Yeah, well, there's, I mean, there's, well,
[01:45] SPEAKER: there's gotta be some amount of latency there,
[01:47] SPEAKER: not that much.
[01:48] SPEAKER: I have a Raspberry Pi 4 running Home Assistant.
[01:51] SPEAKER: So I guess it's going by whatever time
[01:53] SPEAKER: that Pi is pulling through NTP
[01:56] SPEAKER: and then what's the latency to the smart plugs?
[01:58] SPEAKER: That's gotta be measured in dozens
[02:00] SPEAKER: of milliseconds at most, right?
[02:02] SPEAKER: - Tony, I actually don't know how often my Raspberry Pi,
[02:05] SPEAKER: my Home Assistant Raspberry Pi updates time.
[02:07] SPEAKER: I assume it does it daily.
[02:09] SPEAKER: Probably not more than that.
[02:10] SPEAKER: - Well, you're on what?
[02:11] SPEAKER: Home Assistant OS, like you're on the all-in-one,
[02:14] SPEAKER: like the integrated image.
[02:16] SPEAKER: - Yeah, I'm running a yellow.
[02:17] SPEAKER: - But it's whatever your NTP facility
[02:19] SPEAKER: on that Linux install is set to query at.
[02:21] SPEAKER: - Yeah, I haven't touched it,
[02:22] SPEAKER: so I wonder what their default is
[02:23] SPEAKER: 'cause it's like time matters for that stuff.
[02:25] SPEAKER: - Not to just merge this podcast
[02:27] SPEAKER: with the dual boot diaries entirely,
[02:28] SPEAKER: but I did hear you say the word time, date CTL
[02:32] SPEAKER: on that podcast recently, which-
[02:34] SPEAKER: - Yeah, I did the way that you said not to do.
[02:36] SPEAKER: - I think means that you're using system D time sync D
[02:39] SPEAKER: to manage NTPs, so we could probably find out
[02:41] SPEAKER: what the query interval is for that.
[02:44] SPEAKER: - That's on my desktop on the Pi.
[02:45] SPEAKER: It's a whole different thing 'cause the Pi's managed.
[02:47] SPEAKER: I don't ever, I don't think I've ever logged
[02:50] SPEAKER: into a terminal, into a shell on the Pi.
[02:52] SPEAKER: - There's a very good chance that you're using time sync D
[02:54] SPEAKER: on the Home System OS as well 'cause that's kind
[02:56] SPEAKER: of the standard built-in system D way to do it
[02:59] SPEAKER: on most distros these days.
[03:00] SPEAKER: - Yeah, I wonder if they're based on Raspbian
[03:02] SPEAKER: or whatever Raspberry Pi OS or whatever they call it now.
[03:06] SPEAKER: - Probably, I don't know actually.
[03:08] SPEAKER: That's a whole other topic, like distros for Raspberry Pis
[03:11] SPEAKER: is its own topic because-
[03:13] SPEAKER: - Really is.
[03:14] SPEAKER: - There's like Ubuntu has an official Raspberry Pi image.
[03:16] SPEAKER: I think Fedora might.
[03:18] SPEAKER: There's probably actually quite a few these days,
[03:20] SPEAKER: but I really still like running the official Raspberry Pi OS
[03:24] SPEAKER: just 'cause it seems like the most tailored
[03:26] SPEAKER: to the hardware.
[03:29] SPEAKER: - Yeah, it just has a Linux-based OS.
[03:31] SPEAKER: I wonder if they rolled some of them from scratch.
[03:33] SPEAKER: Oh, it's not based on a regular Linux distro like Ubuntu.
[03:36] SPEAKER: It's built using build root
[03:38] SPEAKER: and is optimized to run Home Assistant.
[03:40] SPEAKER: - Yeah, okay, so they did roll their own.
[03:41] SPEAKER: That's cool.
[03:42] SPEAKER: It's kind of like the Mr.
[03:43] SPEAKER: or like the Mr. runs the most stripped down possible
[03:46] SPEAKER: Linux install imaginable.
[03:47] SPEAKER: Like they also cobbled that thing together from parts,
[03:50] SPEAKER: which is pretty cool.
[03:51] SPEAKER: - Yeah, I think they did this because they use Docker
[03:53] SPEAKER: for a lot of running.
[03:55] SPEAKER: Like they needed Docker optimizations
[03:57] SPEAKER: that I bet are not in Raspberry Pi OS by default.
[03:59] SPEAKER: - There's also just like a ton of stuff
[04:01] SPEAKER: for an embedded device like a Mr. or Home Assistant,
[04:04] SPEAKER: yellow or whatever you're doing.
[04:05] SPEAKER: Like there's just a ton of user space stuff
[04:08] SPEAKER: that you don't need cluttering up a thing
[04:10] SPEAKER: that is meant to just run headless.
[04:12] SPEAKER: - Well, yeah, I mean, that's the Linux benefit, right?
[04:15] SPEAKER: You need to have just what you need.
[04:16] SPEAKER: - That's right.
[04:17] SPEAKER: This is one step closer to doing Linux from scratch.
[04:20] SPEAKER: Let's go.
[04:22] SPEAKER: - You didn't have a response for that.
[04:24] SPEAKER: - I, oh, oh no.
[04:28] SPEAKER: - All right, I'm just leaving that in.
[04:30] SPEAKER: - Oh yeah.
[04:31] SPEAKER: (upbeat music)
[04:52] SPEAKER: (upbeat music continues)
[04:59] SPEAKER: - Welcome to Brad and Will Made a Tech Bot.
[05:01] SPEAKER: I'm Will.
[05:02] SPEAKER: - I'm Brad.
[05:03] SPEAKER: That was a really an amazing thousand yard stare.
[05:05] SPEAKER: - I'm just, I'm just shaking.
[05:06] SPEAKER: I was shaking my head.
[05:07] SPEAKER: I was so shook from that.
[05:09] SPEAKER: I couldn't even shake my head.
[05:10] SPEAKER: I was just like, I don't have anything to say about.
[05:14] SPEAKER: - The very words Linux from scratch
[05:15] SPEAKER: just strike terror into the hearts of everyday users.
[05:20] SPEAKER: - I had a Gentoo phase, right?
[05:22] SPEAKER: I used to compile my own Linux kernel
[05:24] SPEAKER: on a Pentium 200 or 266 or whatever it was I had back then.
[05:28] SPEAKER: It took like 12 hours.
[05:29] SPEAKER: It was not a great experience.
[05:32] SPEAKER: Probably a little better now.
[05:33] SPEAKER: - I might stop invoking Linux from scratch
[05:35] SPEAKER: actually for people like somebody popped up,
[05:37] SPEAKER: again, sorry to just talk Linux
[05:39] SPEAKER: and do boot diaries constantly.
[05:41] SPEAKER: I've been in it a lot lately,
[05:42] SPEAKER: but on the PC world discord in that channel,
[05:44] SPEAKER: somebody popped up who is an engineer by day
[05:47] SPEAKER: and was saying like, hey, I don't know what kind of engineer
[05:49] SPEAKER: I have now it could be some kind of hardware
[05:51] SPEAKER: or electrical or something. - Be a train driver, yeah.
[05:53] SPEAKER: - Also possible, steam engineer.
[05:55] SPEAKER: - Yeah.
[05:56] SPEAKER: - But they said like, hey, I'm an engineer.
[05:58] SPEAKER: I'm used to knowing how things work,
[05:59] SPEAKER: but I'm moving to Linux and I have no idea how things work.
[06:02] SPEAKER: And I would love to gain a better understanding of it.
[06:03] SPEAKER: And I started to say, well,
[06:05] SPEAKER: you could go through Linux from scratch
[06:06] SPEAKER: if you really want to understand all the component parts.
[06:09] SPEAKER: But then the more I started reading about it,
[06:11] SPEAKER: the more I got the sense that Linux from scratch
[06:12] SPEAKER: is actually about how to build a Linux system from source.
[06:16] SPEAKER: Like it's more about,
[06:17] SPEAKER: I think it's more about like the build environment
[06:19] SPEAKER: and how to compile all the parts.
[06:20] SPEAKER: It's more about compiling software potentially
[06:22] SPEAKER: than it is about just like learning
[06:24] SPEAKER: what your computer is made of.
[06:26] SPEAKER: - That makes sense.
[06:27] SPEAKER: - I think like there are a bunch of books out there,
[06:28] SPEAKER: like how Linux works and like the Linux Bible
[06:31] SPEAKER: and stuff like that, that I think might be more appropriate.
[06:33] SPEAKER: If you just want to like know what is systemd,
[06:35] SPEAKER: what is udev, like stuff like that.
[06:36] SPEAKER: I think maybe those books might be a better option
[06:39] SPEAKER: than LFS.
[06:41] SPEAKER: - The hard part of the whole thing though,
[06:43] SPEAKER: is that there's like, there's five things,
[06:46] SPEAKER: five different things that do the thing
[06:47] SPEAKER: that systemd does, right?
[06:50] SPEAKER: So, I mean, maybe not five.
[06:52] SPEAKER: - How do you mean?
[06:53] SPEAKER: - I'm just saying like most of the core low-level systems
[06:57] SPEAKER: seem to have multiple variants that do the same thing
[07:01] SPEAKER: or similar things or newer versions or older versions or.
[07:04] SPEAKER: - In some domains, yeah.
[07:06] SPEAKER: Network configuration is,
[07:08] SPEAKER: I could name six different ways right now
[07:10] SPEAKER: to configure a network on Linux.
[07:12] SPEAKER: Okay, maybe I should save all this.
[07:14] SPEAKER: - Yeah, this isn't the podcast to talk about Linux.
[07:16] SPEAKER: - This is my stealth, like I shouldn't say it.
[07:20] SPEAKER: Stealth attempt to get onto that podcast,
[07:22] SPEAKER: but maybe that's not a bad idea.
[07:23] SPEAKER: - It's gonna happen, okay?
[07:24] SPEAKER: - Oh boy.
[07:25] SPEAKER: - Adam and I talk about it every, yeah.
[07:28] SPEAKER: We have our first few guests coming up, so.
[07:31] SPEAKER: - Do you know how long that show's gonna run
[07:34] SPEAKER: or is it open-ended until you feel like
[07:36] SPEAKER: you've reached the end?
[07:37] SPEAKER: - The joke that we made at the beginning
[07:40] SPEAKER: was that we're gonna end the show by deleting
[07:42] SPEAKER: one of the partitions on our hard drive.
[07:44] SPEAKER: - Oh yeah, I know that.
[07:45] SPEAKER: What I mean is, are you giving yourselves eight weeks
[07:47] SPEAKER: or is it like just, hey, we're just gonna keep doing this
[07:48] SPEAKER: until we feel like it's time?
[07:50] SPEAKER: - Yeah, I think my thought is that once it stops being
[07:54] SPEAKER: about dual booting and that transition,
[07:57] SPEAKER: it just becomes like a practical Linux user podcast
[07:59] SPEAKER: or something like that, so it could be open-ended.
[08:01] SPEAKER: I don't know, we'll see what people,
[08:02] SPEAKER: like if people listen to it, we'll keep doing it, right?
[08:04] SPEAKER: That's the rule of podcasting, so.
[08:07] SPEAKER: You can find it wherever podcasts are found.
[08:08] SPEAKER: I'm gonna stop plugging this.
[08:09] SPEAKER: This is, the streams are crossing.
[08:12] SPEAKER: - Yeah, I apologize.
[08:13] SPEAKER: It's just something I'm enthusiastic about
[08:15] SPEAKER: on a personal level.
[08:16] SPEAKER: It's not even like an attempt to cross-pollinate content
[08:19] SPEAKER: or something.
[08:20] SPEAKER: - No, I mean, look, I love cross-pollinating content,
[08:22] SPEAKER: that's great. - I mean, that's probably
[08:23] SPEAKER: also good, but anyway.
[08:26] SPEAKER: - Yeah, no, we started it because we were kind of both
[08:30] SPEAKER: deeply dissatisfied with Windows, right?
[08:32] SPEAKER: And which brings us to why we're here today,
[08:36] SPEAKER: 'cause we have questions from people who are deeply
[08:38] SPEAKER: dissatisfied from Windows, among other things.
[08:40] SPEAKER: There are also questions from people who wanna know
[08:42] SPEAKER: if like a gazpacho's a smoothie.
[08:44] SPEAKER: We're not gonna do that one, I don't think.
[08:46] SPEAKER: - I really don't know that I am ready for like
[08:48] SPEAKER: is blank a soup discourse?
[08:50] SPEAKER: - It's too early in the morning for that.
[08:52] SPEAKER: - I feel like we've barely freed ourselves
[08:54] SPEAKER: from is blank a sandwich discourse, so anyway.
[08:57] SPEAKER: - I still feel like, yeah, anyway.
[09:02] SPEAKER: - Anyway, a lot of questions this month.
[09:03] SPEAKER: This is the Q&A episode, by the way,
[09:04] SPEAKER: but a lot of questions this month that are not about Linux,
[09:08] SPEAKER: just for people who don't want to hear about that endlessly.
[09:11] SPEAKER: - Yeah, if you have questions, you can send an email
[09:13] SPEAKER: to techpod@content.town, that's techpod@content.town,
[09:17] SPEAKER: or if you're a member of the Patreon,
[09:19] SPEAKER: if you're supporting the show,
[09:20] SPEAKER: 'cause we are a listener-supported show,
[09:23] SPEAKER: you can go into the Q Seeking A's channel in the Discord
[09:26] SPEAKER: and post your questions there.
[09:26] SPEAKER: They'll disappear, but we'll see them
[09:28] SPEAKER: at the end of the month, and then we will pull them
[09:30] SPEAKER: into a blazing white 7 a.m. Google document,
[09:34] SPEAKER: and we'll turn them into A's, so there we go.
[09:38] SPEAKER: You got a Q lined up?
[09:40] SPEAKER: - This is an email from Tim.
[09:42] SPEAKER: - Tim.
[09:43] SPEAKER: - I know I'm a couple of weeks late on this,
[09:45] SPEAKER: but I still wanted to share my stories around Windows 95.
[09:48] SPEAKER: Although I started in computers
[09:50] SPEAKER: back in the Commodore 64 days,
[09:51] SPEAKER: and on the IT type side of things,
[09:53] SPEAKER: in high school with Windows 311,
[09:56] SPEAKER: I have some serious memories of Windows 95 as well.
[09:59] SPEAKER: I especially identified with some of your networking stories
[10:01] SPEAKER: as in my last year of college,
[10:03] SPEAKER: my university brought internet access to the dorms.
[10:07] SPEAKER: My roommates realized the IT staff was small
[10:09] SPEAKER: and created a company that the IT department
[10:13] SPEAKER: would send the students to in order
[10:15] SPEAKER: to purchase a network card and get it installed
[10:17] SPEAKER: and configured in their systems for ResNet access.
[10:20] SPEAKER: - That is incredible.
[10:21] SPEAKER: - That is like brilliant, like what is the term there?
[10:23] SPEAKER: That's not a middleman exactly, that's a...
[10:25] SPEAKER: - That's a middleman.
[10:26] SPEAKER: - Is it a middleman, I guess?
[10:27] SPEAKER: - It's an independent contractor.
[10:28] SPEAKER: It's like a...
[10:30] SPEAKER: - Okay, independent contractor.
[10:31] SPEAKER: My lights just came on, did your lights also just come on?
[10:33] SPEAKER: - No, my lights are on.
[10:34] SPEAKER: I have to hit a button to turn the lights on in here.
[10:36] SPEAKER: - You will see that my office is now lit
[10:38] SPEAKER: as it's normally lit.
[10:40] SPEAKER: - Yeah.
[10:40] SPEAKER: - Anyway, I feel like a middleman doesn't actually do work.
[10:46] SPEAKER: Am I selling middlemen short?
[10:47] SPEAKER: I always feel like a middleman is somebody
[10:48] SPEAKER: who just like sits in between
[10:50] SPEAKER: and doesn't necessarily do the labor.
[10:53] SPEAKER: - I mean, look, they're an independent contractor
[10:56] SPEAKER: is what this is, right?
[10:57] SPEAKER: - That sounds more right,
[10:59] SPEAKER: but this is kind of brilliant, I feel like.
[11:02] SPEAKER: - And the independent contract, so it's funny
[11:04] SPEAKER: 'cause at my university when they started doing that,
[11:06] SPEAKER: they just made the kids who were on work study
[11:09] SPEAKER: in the IT department do that
[11:11] SPEAKER: and computer services do that work.
[11:13] SPEAKER: And they were miserable.
[11:15] SPEAKER: - Yeah, if you're doing the work directly
[11:16] SPEAKER: for the big entity and you're at their mercy
[11:19] SPEAKER: or the mercy of their terms,
[11:21] SPEAKER: but if you create your own company to do that work,
[11:23] SPEAKER: then you start commanding the terms.
[11:25] SPEAKER: - Yeah, so I'm sure they got paid like 40, 50 bucks an hour
[11:28] SPEAKER: depending on what year it was.
[11:30] SPEAKER: And I bet they charged a lovely markup
[11:32] SPEAKER: on the network cards too.
[11:33] SPEAKER: - Oh yeah, I bet, man, that's brilliant.
[11:36] SPEAKER: - Tim goes on here.
[11:37] SPEAKER: "I have nightmares of how difficult it was
[11:39] SPEAKER: to get a network card into some of those mid 90s desktops.
[11:42] SPEAKER: I still have a special hatred for Compaq to this day
[11:46] SPEAKER: because of how crammed full their cases were
[11:48] SPEAKER: making it nearly impossible to add an expansion card
[11:50] SPEAKER: of any kind and the scars to prove it.
[11:53] SPEAKER: Nevermind the ones where the expansion slots
[11:55] SPEAKER: were on some kind of vertical daughter board
[11:58] SPEAKER: that plugged in at a 90 degree angle to the motherboard."
[12:01] SPEAKER: Actually like this jogged a bunch of memories.
[12:03] SPEAKER: I never owned a Compaq, but I knew people who had them
[12:05] SPEAKER: and I remember always hearing, it wasn't just Compaq,
[12:08] SPEAKER: it was like-
[12:09] SPEAKER: - Oh, all the pizza box cases were like that, yeah.
[12:12] SPEAKER: - All the big name PC makers in the 90s
[12:14] SPEAKER: were doing weird proprietary internals on their systems,
[12:17] SPEAKER: right, like they were-
[12:18] SPEAKER: - No, not all of them.
[12:18] SPEAKER: - Not all of them.
[12:19] SPEAKER: Like I think Gateway was pretty good about being open.
[12:22] SPEAKER: - Dell and Compaq were both notorious
[12:24] SPEAKER: and like Packard Bell and eMachines and all those kinds of,
[12:28] SPEAKER: like the cheaper stuff were doing all weird stuff.
[12:31] SPEAKER: And then Gateway and HP to a lesser extent
[12:34] SPEAKER: had pretty good reputations
[12:35] SPEAKER: for doing like user serviceable machines.
[12:38] SPEAKER: - Micron, I think, but yes, I remember hearing
[12:40] SPEAKER: how non-standard the guts of all those PCs were back then.
[12:43] SPEAKER: And like, if you cared about upgrade,
[12:46] SPEAKER: I guess this is like coming from the mid 90s,
[12:47] SPEAKER: like 3D accelerator explosion,
[12:49] SPEAKER: like the reputation was always like,
[12:51] SPEAKER: "Hey, don't buy a Compaq or something like that
[12:53] SPEAKER: if you want to buy a new graphics card to put in it."
[12:56] SPEAKER: - It was, I had a AST Pentium 60 for a while
[13:00] SPEAKER: that was a pizza box with one of those riser cards
[13:03] SPEAKER: and getting a Voodoo card into that was really challenging
[13:07] SPEAKER: because I couldn't, like the cable
[13:09] SPEAKER: that was the jumper cable that did the pass through
[13:11] SPEAKER: for the VGA that came with the Voodoo card
[13:14] SPEAKER: wasn't quite long enough to reach from one,
[13:20] SPEAKER: I guess it was a PCI slot to another PCI slot.
[13:23] SPEAKER: Anyway.
[13:24] SPEAKER: - Yeah, that was always the problem.
[13:26] SPEAKER: Stuff just didn't fit, right?
[13:27] SPEAKER: - Well, and network cards to Tim's point
[13:29] SPEAKER: were a nightmare back at this period, right?
[13:32] SPEAKER: Like you had, they had dip switches and all sorts of stuff
[13:34] SPEAKER: 'cause plug and play wasn't really a thing yet.
[13:36] SPEAKER: - Yep, last bit from Tim here.
[13:39] SPEAKER: I love the references to BBSs as well.
[13:42] SPEAKER: I ran one myself,
[13:43] SPEAKER: can't remember the specific software anymore,
[13:45] SPEAKER: but because we only had one phone line at my house,
[13:48] SPEAKER: it was only up if a friend or user called me on a voice line
[13:51] SPEAKER: on the POTS line first to ask me to turn it on.
[13:54] SPEAKER: - That's really funny.
[13:55] SPEAKER: - That's amazing, I don't know if that quite meets the bar.
[13:58] SPEAKER: Well, I mean, then it is a BBS, but yeah.
[14:01] SPEAKER: - Well, they were asynchronous, right?
[14:03] SPEAKER: That was one of the cool things about them.
[14:04] SPEAKER: I mean, there were chats and stuff like that,
[14:06] SPEAKER: but you could have chats on them is my understanding.
[14:10] SPEAKER: - If I remember, I think the biggest local,
[14:12] SPEAKER: like local call BBS we had was four lines,
[14:14] SPEAKER: if I'm not mistaken,
[14:15] SPEAKER: but I don't remember any kind of synchronous,
[14:17] SPEAKER: like real-time chat features on there,
[14:20] SPEAKER: or if they had that, I certainly never used it,
[14:22] SPEAKER: but maybe they did, but you're right.
[14:24] SPEAKER: It was like, for me, the BBS experience was log in,
[14:27] SPEAKER: see if any new game demos had been posted,
[14:30] SPEAKER: play Legend of the Red Dragon and then log off for the day.
[14:33] SPEAKER: - The funny thing was the game demos were big enough
[14:35] SPEAKER: at that time that it probably would have been faster
[14:37] SPEAKER: to drive to the dude's house that hosted the BBS
[14:39] SPEAKER: with some floppies and then drive back.
[14:43] SPEAKER: - Yeah, I think we talked about modem speeds a good bit
[14:46] SPEAKER: on the Discord the week of that Windows 95 episode.
[14:50] SPEAKER: And my memory is that 28.8 modem is the fastest we ever had,
[14:54] SPEAKER: and it was about three kilobytes a second at best on that.
[14:57] SPEAKER: - Yeah, it seems right.
[14:58] SPEAKER: - I don't, I'm not gonna do the math right now,
[15:01] SPEAKER: but I think it was about five minutes per megabyte
[15:03] SPEAKER: in the best possible conditions.
[15:05] SPEAKER: - That seems about right.
[15:06] SPEAKER: - So yes, it was like, I think there were like
[15:09] SPEAKER: overnight downloads of some demos for me, if I remember.
[15:12] SPEAKER: - Oh, I remember if something was 40 megs,
[15:14] SPEAKER: it would turn it on when you went to bed
[15:16] SPEAKER: and it'll be done by the time I get back from class
[15:18] SPEAKER: the next day.
[15:19] SPEAKER: - Oh my God, now you're reminding me
[15:20] SPEAKER: of the precarity of long downloads.
[15:22] SPEAKER: And if anything bad happened to the phone line midstream,
[15:24] SPEAKER: you were just screwed.
[15:26] SPEAKER: - Yeah.
[15:27] SPEAKER: - Hey, the phone's making that noise again.
[15:30] SPEAKER: Anyway, that's cool.
[15:32] SPEAKER: - I don't think the downloads were resumable back then.
[15:35] SPEAKER: - Sometimes they were, but not normal HTTP ones.
[15:38] SPEAKER: - Anyway, we should move on,
[15:40] SPEAKER: but because I am this exact kind of nerd,
[15:42] SPEAKER: I occasionally will look up lists of BBS software
[15:44] SPEAKER: and try to remember the ones that I used.
[15:46] SPEAKER: I feel like Wildcat is the one I remember
[15:48] SPEAKER: being pretty popular where I lived.
[15:50] SPEAKER: - I never had access, so I don't know.
[15:52] SPEAKER: - I think we had at least one or two Wildcat boards,
[15:55] SPEAKER: but there was a bigger one that I don't remember.
[16:00] SPEAKER: I'll give you this later.
[16:01] SPEAKER: - Greg, you just had that week off work.
[16:02] SPEAKER: Instead of doing all that hard drive business,
[16:04] SPEAKER: you could have set up a tech pod BBS.
[16:06] SPEAKER: - That's right.
[16:07] SPEAKER: I could have probably tracked down a copy of Wildcat
[16:08] SPEAKER: and maybe I'll look into that actually.
[16:10] SPEAKER: - Yeah, it's a good project.
[16:12] SPEAKER: - Anyway, all right, Nathan from Houston.
[16:15] SPEAKER: You mentioned your phone's losing their trade-in value
[16:18] SPEAKER: and it reminded me of this thing
[16:19] SPEAKER: I figured out last time I got a new phone.
[16:20] SPEAKER: This is also kind of brilliant.
[16:22] SPEAKER: - Yeah, it is.
[16:23] SPEAKER: - We keep phones for a while,
[16:24] SPEAKER: so they have pretty much no trade-in value
[16:26] SPEAKER: when getting new phones.
[16:27] SPEAKER: But I realized at least for the carriers, okay,
[16:29] SPEAKER: this is maybe this is a big asterisk here
[16:31] SPEAKER: because I don't, I think a lot of people
[16:33] SPEAKER: don't want to buy into a carrier contract these days.
[16:35] SPEAKER: But anyway, I realized at least for the carriers,
[16:38] SPEAKER: you don't have to trade in the phone you're using.
[16:40] SPEAKER: You can trade in any phone.
[16:42] SPEAKER: So last time we traded in phones,
[16:43] SPEAKER: I looked at what they accepted
[16:45] SPEAKER: and was able to get $1,000 off an S23 Ultra
[16:48] SPEAKER: by spending $185 and $1,000 off an iPhone 15 Plus
[16:53] SPEAKER: by spending $325 on used phones and trading those in.
[16:58] SPEAKER: - That's incredible.
[16:59] SPEAKER: - I can't confirm it works everywhere,
[17:01] SPEAKER: but it worked at AT&T.
[17:03] SPEAKER: - So the problem with the carrier contracts
[17:04] SPEAKER: is that they're usually three years.
[17:06] SPEAKER: - Yeah.
[17:07] SPEAKER: - And you can't, like typically they don't have
[17:09] SPEAKER: a mid go upgrade clause, right?
[17:11] SPEAKER: - Sure, yeah, I mean that for me, that's fine
[17:14] SPEAKER: 'cause I like to keep a phone for a long time anyway.
[17:15] SPEAKER: But I guess if you're on like the,
[17:17] SPEAKER: if you like getting a new phone every year,
[17:18] SPEAKER: that is problematic.
[17:19] SPEAKER: Do you know-
[17:20] SPEAKER: - Every other year.
[17:22] SPEAKER: - Do you know how the math maths out
[17:23] SPEAKER: on modern carrier contracts?
[17:26] SPEAKER: Like, are you spending more or is it just
[17:27] SPEAKER: that it's spread out?
[17:28] SPEAKER: But it's, I mean, do you end up spending effectively
[17:30] SPEAKER: the same amount in the final tally?
[17:33] SPEAKER: - I haven't mathed out the normal carrier contract
[17:35] SPEAKER: because the carriers are so fricking expensive
[17:39] SPEAKER: compared to MVNOs that I think you,
[17:42] SPEAKER: I think that you end up paying,
[17:44] SPEAKER: like you're paying, you end up paying more twice, right?
[17:46] SPEAKER: So you're paying, they're doing 0% financing
[17:48] SPEAKER: for 36 months on the $1,000 of the phone.
[17:51] SPEAKER: - Right.
[17:52] SPEAKER: - But then you're also paying $150 a month more a month
[17:55] SPEAKER: for your cellular service.
[17:57] SPEAKER: - Yeah, you just reminded me and I'm on an MVNO now.
[18:00] SPEAKER: So like that alone is a deal breaker
[18:01] SPEAKER: because my phone bill is now $10 a month
[18:04] SPEAKER: and I'm not giving that up for anything.
[18:05] SPEAKER: - Yeah, but also the money you save on the $10 a month,
[18:09] SPEAKER: you can buy a lot of $1,000 phones over a couple of years.
[18:12] SPEAKER: - Yeah, yes.
[18:13] SPEAKER: Did I talk about-
[18:14] SPEAKER: - Yeah, we talked about it, but is it going okay?
[18:16] SPEAKER: - Well, that's the thing.
[18:17] SPEAKER: Did I talk about the time I ran out of data?
[18:19] SPEAKER: I think I did.
[18:20] SPEAKER: - Yeah, you did.
[18:21] SPEAKER: - I think my carrier-
[18:21] SPEAKER: - When you were in jury duty.
[18:23] SPEAKER: - Just cuts you off.
[18:24] SPEAKER: I can't say every MVNO is that way,
[18:27] SPEAKER: but in my case, like literally when I ran out of data
[18:29] SPEAKER: while I was walking down the street,
[18:32] SPEAKER: they don't even let you like,
[18:34] SPEAKER: they don't even like allow lists their own app
[18:37] SPEAKER: for you to go in and buy more data.
[18:39] SPEAKER: I had to get the wifi
[18:40] SPEAKER: before I could pay another $4 to get more data.
[18:43] SPEAKER: - That's wild.
[18:44] SPEAKER: - It was a little brutal anyway.
[18:46] SPEAKER: - But you're also on the extreme,
[18:48] SPEAKER: like I think if I was doing an MVNO,
[18:50] SPEAKER: I'd do the $20 or $25 a month thing
[18:52] SPEAKER: that gives me unlimited data.
[18:54] SPEAKER: - Totally, I'm on the like a la carte,
[18:56] SPEAKER: you get two gigabytes a month and you pay more for,
[18:59] SPEAKER: which is fine, like it's only $4 for more data.
[19:01] SPEAKER: Like even when I had to double my data,
[19:03] SPEAKER: it was still a $14 phone bill.
[19:04] SPEAKER: Like that's not a problem,
[19:05] SPEAKER: but it'd be nice if they let you re-up anywhere you are.
[19:09] SPEAKER: - If that's wild.
[19:10] SPEAKER: - I think it had defaulted to like
[19:13] SPEAKER: not auto topping off data.
[19:16] SPEAKER: - Ah.
[19:17] SPEAKER: - I think I turned that on and I'm fine now.
[19:19] SPEAKER: Anyway, all right, the second half of Nathan's email.
[19:22] SPEAKER: Hearing about Brad's 16 hard drives
[19:24] SPEAKER: really makes me want him to get some kind of smart meter
[19:26] SPEAKER: for monitoring his electricity usage.
[19:28] SPEAKER: I will jump in here real quick and say
[19:30] SPEAKER: the 16 hard drives is not even remotely permanent.
[19:32] SPEAKER: That was a special case.
[19:35] SPEAKER: You know, that's when I had all those extra drives hooked up.
[19:37] SPEAKER: - Yeah, it's a short term.
[19:39] SPEAKER: - That's not, normally it's 10, anyway.
[19:41] SPEAKER: - 10's still a lot though.
[19:43] SPEAKER: - Sometimes I think he underestimates
[19:45] SPEAKER: how much something can cost when running 24/7.
[19:47] SPEAKER: I assure you, I do not well aware.
[19:50] SPEAKER: It is a constant pain point running the server,
[19:52] SPEAKER: but frankly I balance it out by telling myself
[19:56] SPEAKER: how much I enjoy tinkering with it.
[19:59] SPEAKER: - Yeah.
[19:59] SPEAKER: - It's like kind of my only hobby.
[20:01] SPEAKER: Also it's a work expense, frankly.
[20:03] SPEAKER: Like I use that server for work constantly.
[20:05] SPEAKER: So there's like tax write-offs and stuff involved,
[20:07] SPEAKER: but you're not wrong.
[20:10] SPEAKER: It uses a fair amount of electricity.
[20:13] SPEAKER: When I was looking at making my own NAS,
[20:14] SPEAKER: I could have built it cheaper than a Synology,
[20:16] SPEAKER: but couldn't get the power usage as low.
[20:18] SPEAKER: After a few years, the custom built one
[20:20] SPEAKER: would be more expensive because of the energy cost.
[20:23] SPEAKER: Supposedly the average cost of electricity in California
[20:25] SPEAKER: is 33.52 cents per kilowatt hour.
[20:29] SPEAKER: At 24/7 usage, that would be just under $3 a year per watt,
[20:34] SPEAKER: not including the electricity needed
[20:35] SPEAKER: to cool the home back down.
[20:38] SPEAKER: When you're going to have something running
[20:39] SPEAKER: for five plus years, each watt really adds up.
[20:42] SPEAKER: Yes, like you're totally right about all of this.
[20:45] SPEAKER: So the weird thing is in California,
[20:48] SPEAKER: it's 33, or at least for us,
[20:50] SPEAKER: it's 33 cents per watt kilowatt hour
[20:52] SPEAKER: at our low rate for delivery, for energy.
[20:56] SPEAKER: But then the delivery from PG&E
[20:58] SPEAKER: is another 30 cents per kilowatt hour.
[21:01] SPEAKER: So it's like 70 cents, 65 to 70 cents.
[21:05] SPEAKER: And it goes up on peak hours because we're on the EV plan.
[21:09] SPEAKER: So it's cheap during off-peak, inexpensive during peak.
[21:12] SPEAKER: This is why I have the Synology
[21:14] SPEAKER: and the five watt N100 server.
[21:16] SPEAKER: - Yeah, although I mean, you have to break down
[21:18] SPEAKER: what is consuming power in the boxes.
[21:20] SPEAKER: You know, like the hard drives are not a small percentage,
[21:23] SPEAKER: and that's gonna be the same in a Synology
[21:25] SPEAKER: or a big, giant server.
[21:27] SPEAKER: - Well, that's why I have three hard drives
[21:29] SPEAKER: spinning in my Synology and not 10.
[21:31] SPEAKER: - Yes.
[21:32] SPEAKER: Well, anyway.
[21:34] SPEAKER: - Yeah, but what's the draw on your server?
[21:36] SPEAKER: Have you plugged the watt meter into it, just out of curiosity?
[21:38] SPEAKER: - I have it plugged into a UPS so I can kind of eyeball it,
[21:41] SPEAKER: but I have to mentally subtract
[21:43] SPEAKER: everything else plugged into that UPS
[21:44] SPEAKER: 'cause it just gives you one flat output reading.
[21:47] SPEAKER: I don't know.
[21:49] SPEAKER: It's hard to say.
[21:50] SPEAKER: I bet it's, gosh, it's probably 100 watts or something,
[21:56] SPEAKER: at least, maybe more.
[21:58] SPEAKER: You know what?
[21:59] SPEAKER: I'm gonna like skip to a Discord question here
[22:00] SPEAKER: 'cause there's one that is quite related
[22:02] SPEAKER: to what we're talking about here that I can add on to.
[22:06] SPEAKER: This is a Discord question from Brain.
[22:09] SPEAKER: It's a great username.
[22:11] SPEAKER: I recently came into possession of some large capacity
[22:14] SPEAKER: SAS hard drives.
[22:16] SPEAKER: Initially, I wanted to integrate them
[22:17] SPEAKER: into my mini PC based home lab setup,
[22:19] SPEAKER: but it appears to be an impossible task.
[22:22] SPEAKER: I don't want to invest in a 24 bay JBOD to use these drives.
[22:27] SPEAKER: Is it worth finding a way to use six 12 terabyte SAS drives
[22:30] SPEAKER: or just move on?
[22:32] SPEAKER: I mean, you know what my answer is going to be.
[22:35] SPEAKER: Find a way to use the hard drive.
[22:36] SPEAKER: - Get that 24 drive bay, right?
[22:38] SPEAKER: - Well, maybe not that, that's pretty big.
[22:40] SPEAKER: I mean, I'm taking mini PC to mean like B-Link style
[22:44] SPEAKER: or like kind of tiny Mac mini style box.
[22:48] SPEAKER: So you probably don't want a giant backplane
[22:51] SPEAKER: 24 bay thing sitting around
[22:54] SPEAKER: if you're trying to keep things small.
[22:55] SPEAKER: - My assumption, yeah, mini PC says small form factor
[23:00] SPEAKER: at biggest, which means you're going to have
[23:01] SPEAKER: like two drive bays.
[23:03] SPEAKER: - Yes, I looked this up.
[23:07] SPEAKER: SAS drives apparently need,
[23:09] SPEAKER: and like they need a special interface.
[23:11] SPEAKER: So like you can plug, God, I'm trying to think,
[23:15] SPEAKER: you can plug SATA drives into a SAS interface.
[23:17] SPEAKER: You can't plug SAS drives into a SATA interface.
[23:20] SPEAKER: - It's a one way, but not the other, basically.
[23:22] SPEAKER: - SAS, I barely, what is it?
[23:23] SPEAKER: Serial attached SCSI, I believe is the acronym.
[23:26] SPEAKER: I think it's basically like data center level storage.
[23:30] SPEAKER: So I don't know how you came by these drives.
[23:31] SPEAKER: Although if you got them for free,
[23:33] SPEAKER: as it sounds like you did,
[23:34] SPEAKER: then I extra think you should use them,
[23:35] SPEAKER: but you're going to have to buy a card.
[23:38] SPEAKER: You're going to have to buy like a SAS interface card,
[23:40] SPEAKER: like a host bus adapter to use them, it sounds like.
[23:42] SPEAKER: - The problem is if you're on a mini PC or an ITX machine,
[23:45] SPEAKER: you probably only have one PCI express slot.
[23:47] SPEAKER: And there are problems.
[23:50] SPEAKER: Although I was going to say,
[23:52] SPEAKER: there are now NVMe slot to PC,
[23:56] SPEAKER: like PCIe by four adapters that you can buy.
[24:00] SPEAKER: So you could, yeah.
[24:02] SPEAKER: - What are we even doing?
[24:04] SPEAKER: What are we doing?
[24:05] SPEAKER: - It's all PCI express lanes.
[24:06] SPEAKER: They're all the same.
[24:07] SPEAKER: - I wonder if there's going to be a more formal standard
[24:10] SPEAKER: for plugging cards into NVMe sockets at some point.
[24:14] SPEAKER: - Maybe.
[24:15] SPEAKER: - It feels like that's all motherboards
[24:17] SPEAKER: are shipping these days is NVMe sockets.
[24:20] SPEAKER: - We were talking about this on the full nerd a few weeks
[24:22] SPEAKER: ago, but it feels like the small form factor stuff
[24:24] SPEAKER: and ITX is kind of in a weird, there's a weird,
[24:28] SPEAKER: it's in a weird state of flux right now.
[24:29] SPEAKER: Cause like there's a pretty well established,
[24:32] SPEAKER: like ITX basic shape for computers.
[24:36] SPEAKER: But then there's also people doing a lot of really weird
[24:39] SPEAKER: stuff with like putting PCI express slots on the back
[24:44] SPEAKER: and of those boards and like building things
[24:48] SPEAKER: that are designed to run with like bridges that are,
[24:52] SPEAKER: you know, that will let you put your PCI express cable
[24:54] SPEAKER: someplace else or like, so who knows?
[24:58] SPEAKER: It feels like we need to have another round of,
[25:01] SPEAKER: Hey, here's what the standard is.
[25:03] SPEAKER: Cause that that ITX standard is spun out of like shuttle
[25:07] SPEAKER: cases, proprietary shuttle cases 20 years ago.
[25:10] SPEAKER: - And it's such a mess.
[25:11] SPEAKER: Gordon continues to be right.
[25:13] SPEAKER: We should have moved on from ATX a long time ago.
[25:15] SPEAKER: - Yeah, you're not wrong.
[25:17] SPEAKER: - It feels like, and it feels like I'm trying to think
[25:20] SPEAKER: of the other basic building blocks of modern computing
[25:22] SPEAKER: that have modernized.
[25:23] SPEAKER: Like we finally replaced BIOS with UEFI like 15 years ago
[25:27] SPEAKER: or something, you know what I mean?
[25:28] SPEAKER: There's like a bunch of legacy stuff from 30 to 40 years ago
[25:31] SPEAKER: that has been replaced and it feels like the ATX standard
[25:36] SPEAKER: should have been one of those by now.
[25:37] SPEAKER: - It's even, it's even just stuff like,
[25:41] SPEAKER: Hey, where the CPU has to be on an ATX board
[25:45] SPEAKER: and the orientation of the memory are non-optimal
[25:47] SPEAKER: for Airflow for a lot of reasons.
[25:49] SPEAKER: Like we're starting to see some different kinds of memory
[25:50] SPEAKER: come on board that that'll maybe change that.
[25:53] SPEAKER: But I I'm skeptical whether they'll take off
[25:56] SPEAKER: because they're more, the non stick formats
[26:00] SPEAKER: are gonna be a lot more expensive
[26:01] SPEAKER: and you're gonna have to make some choices
[26:03] SPEAKER: and stuff like that.
[26:04] SPEAKER: So I don't know.
[26:05] SPEAKER: - There's so much you could do.
[26:06] SPEAKER: I mean, the physical form factor is the main thing,
[26:07] SPEAKER: you know, making things tidier
[26:09] SPEAKER: and adding more capabilities and stuff.
[26:10] SPEAKER: But there's also like digital stuff.
[26:12] SPEAKER: You could like, what about better diagnostic information?
[26:14] SPEAKER: Like what if they build that into the spec of CTX
[26:17] SPEAKER: or whatever the next standard is where like,
[26:19] SPEAKER: like what if there was a standard output format
[26:21] SPEAKER: for something better than just like BIOS,
[26:23] SPEAKER: like two digit numerical BIOS error codes?
[26:26] SPEAKER: Like what if you add some standard interface
[26:28] SPEAKER: for getting like real information about what your PC
[26:30] SPEAKER: is doing to fix problems?
[26:32] SPEAKER: - What if, what if Windows had an interface
[26:34] SPEAKER: for getting voltages and temperatures and fan speeds
[26:37] SPEAKER: back out to software?
[26:39] SPEAKER: That would be nice.
[26:40] SPEAKER: The ITX thing though feels more like,
[26:43] SPEAKER: I feel like ATX is in a pretty good place right now.
[26:45] SPEAKER: I feel like the ITX stuff is in a weirder spot.
[26:48] SPEAKER: And, and like, so, so I guess the question for me
[26:52] SPEAKER: on this one is, do they have PCI express slots?
[26:55] SPEAKER: And if they do, then you just buy a SAS PCI express card
[26:58] SPEAKER: and you're good to go.
[27:00] SPEAKER: But if you don't, I don't know what the option is, right?
[27:03] SPEAKER: Like are there SAS back planes that are like USB-C
[27:06] SPEAKER: to SAS bridges?
[27:07] SPEAKER: - I doubt it.
[27:08] SPEAKER: - Cause that seems like it would be not performant and bad.
[27:11] SPEAKER: - It also, my guess is there's just no use case for,
[27:14] SPEAKER: that would drive reproduction of something like that.
[27:16] SPEAKER: Because SAS is again, a data center thing
[27:18] SPEAKER: and data centers don't give a F about anything
[27:20] SPEAKER: except making things work.
[27:23] SPEAKER: You know, like they don't care about tidiness
[27:24] SPEAKER: or modularity or whatever.
[27:27] SPEAKER: So I will say at the flea market a couple of weeks ago,
[27:30] SPEAKER: I saw a 24 bay IBM SAS back plane 2U or 3U, I guess.
[27:40] SPEAKER: Rack mount dealy.
[27:42] SPEAKER: I was like, hey, does this work?
[27:44] SPEAKER: And the guy said, oh yeah, it works.
[27:45] SPEAKER: And I was like, how much do you want for it?
[27:46] SPEAKER: And he told me, and I was like, oh, that's a good deal.
[27:48] SPEAKER: And I didn't buy it and I kind of regret that,
[27:50] SPEAKER: but also I don't have a place for it, so.
[27:52] SPEAKER: - I didn't see that.
[27:53] SPEAKER: Yeah, that's the kind of thing that I feel like
[27:56] SPEAKER: you get the rack first and then you source stuff like that.
[27:59] SPEAKER: - You can just pile the rack stuff up in a pile,
[28:01] SPEAKER: it'll be fine.
[28:02] SPEAKER: - Yes, okay, we'll move on.
[28:04] SPEAKER: I won't give me 30 seconds to mention
[28:06] SPEAKER: one of my own personal bugbears real quick
[28:09] SPEAKER: about this question.
[28:11] SPEAKER: If you're buying old server cards,
[28:12] SPEAKER: like we're talking about here,
[28:13] SPEAKER: like if you're buying an old host bus adapter
[28:15] SPEAKER: and record to brain, if you really want to go down this road
[28:19] SPEAKER: look up like LSI host bus adapters,
[28:21] SPEAKER: that's the type of thing you're gonna need
[28:22] SPEAKER: to plug those SAS drives in.
[28:24] SPEAKER: The thing I have come to understand
[28:25] SPEAKER: is that 15 year old server cards like that
[28:29] SPEAKER: do not support modern ASPM,
[28:30] SPEAKER: which is like power management at the PCI express level.
[28:34] SPEAKER: - Oh, yeah.
[28:35] SPEAKER: - Like I have a SAS controller
[28:38] SPEAKER: and a Mellanox network card in my server
[28:41] SPEAKER: that are both like 15 years old.
[28:44] SPEAKER: When your PCI express cards don't support modern ASPM,
[28:47] SPEAKER: it also limits the C states, the sleep states,
[28:49] SPEAKER: the low power states that your CPU can descend into.
[28:53] SPEAKER: - Oh.
[28:54] SPEAKER: - So I'm probably leaving even more electricity usage
[28:56] SPEAKER: on the table.
[28:57] SPEAKER: This is why I really wanted to address this question.
[28:59] SPEAKER: I'm probably burning even more energy
[29:01] SPEAKER: because my CPU can't, and I've monitored this,
[29:04] SPEAKER: like my CPU can't and the server can't go
[29:07] SPEAKER: into the deepest sleep that you would want
[29:09] SPEAKER: because those cards limit it from doing so.
[29:13] SPEAKER: There is a blog post called the curse of ASPM
[29:16] SPEAKER: that I'm going to link in the show notes
[29:18] SPEAKER: for people who really want to hear
[29:19] SPEAKER: an insanely exhaustive amount more about this.
[29:23] SPEAKER: Subhead of this blog post,
[29:25] SPEAKER: you either get to C8 or you die trying.
[29:29] SPEAKER: - This is, I've looked at this blog post,
[29:30] SPEAKER: it's a crazy blog post.
[29:31] SPEAKER: - It's insane.
[29:32] SPEAKER: It is utterly, this person, I bow to this person.
[29:35] SPEAKER: They went and bought like every card they could find
[29:38] SPEAKER: to try to eliminate this problem.
[29:40] SPEAKER: It's really an incredible amount of detective work.
[29:43] SPEAKER: Anyway, enough about my personal madness.
[29:48] SPEAKER: Let's read something a little more middle of the road here.
[29:51] SPEAKER: Catwill Mew, I'm just going to bounce around
[29:53] SPEAKER: between emails and Discord here.
[29:54] SPEAKER: - Yeah.
[29:56] SPEAKER: - Watching Hollow Knight's Silksong crash Steam
[29:58] SPEAKER: and the eShop and even Xbox,
[30:00] SPEAKER: and thinking back to how the Switch 2 launch
[30:02] SPEAKER: melted down the websites of some of the largest retailers
[30:05] SPEAKER: on the planet, I have to ask, how is this still happening?
[30:09] SPEAKER: Wasn't the whole premise, I'm sorry,
[30:11] SPEAKER: wasn't the whole promise of the cloud
[30:13] SPEAKER: supposed to be infinite scalability?
[30:15] SPEAKER: Is it bad architecture, one weak link in the chain,
[30:19] SPEAKER: sites cheaping out somewhere?
[30:23] SPEAKER: - Yeah, it's wild, right?
[30:24] SPEAKER: - It is, on some level, yes, it's crazy.
[30:27] SPEAKER: On another level though, like, I mean,
[30:28] SPEAKER: this is going back a while, but I remember reading about,
[30:31] SPEAKER: like MMO launches, I feel like,
[30:32] SPEAKER: were the prototypical case of this.
[30:35] SPEAKER: - Well, yeah, and like early MMOs especially,
[30:38] SPEAKER: we didn't have ways to test the way that we do now.
[30:42] SPEAKER: Like it was hard to spin up a thousand users,
[30:45] SPEAKER: fake users to hit your login server at the same time
[30:47] SPEAKER: to see if it was going to hold the rush.
[30:49] SPEAKER: Now people do, like, this is why games like Battlefield
[30:52] SPEAKER: that expect to have big launches do big open betas
[30:55] SPEAKER: that they gradually roll out access to.
[30:58] SPEAKER: And it's also, I think, why they do early access
[31:01] SPEAKER: with like higher editions is so they get an initial,
[31:04] SPEAKER: instead of having one wave, they have three waves
[31:06] SPEAKER: and it gets 30% fewer people on each wave, right?
[31:10] SPEAKER: - Yeah.
[31:13] SPEAKER: The answer I always got here about like,
[31:15] SPEAKER: hey, why do MMO launches still go sideways all the time?
[31:18] SPEAKER: The answer I always got there kind of always amounted
[31:20] SPEAKER: to corporations just red lining their infrastructure
[31:23] SPEAKER: all the time, which is to say like,
[31:25] SPEAKER: they're going to build their infrastructure,
[31:27] SPEAKER: they're going to spec it for the 95% environments
[31:31] SPEAKER: or use case or load level.
[31:34] SPEAKER: They're not going to go out of their way to build
[31:36] SPEAKER: for the 2% insane load of launch, you know what I mean?
[31:39] SPEAKER: Like they're just, they're not going to build
[31:41] SPEAKER: the extra capacity in because they want to save money.
[31:44] SPEAKER: They're not going to build in the capacity
[31:45] SPEAKER: to handle a one-off, like one bad night event.
[31:48] SPEAKER: They're just going to let it do what it's going to do
[31:51] SPEAKER: because 95% of the time it's not going to be near
[31:55] SPEAKER: that level of load and they'll be fine.
[31:56] SPEAKER: - Well, yes, but also for something like a game.
[32:00] SPEAKER: So for example, when you're buying servers
[32:02] SPEAKER: for a game that has dedicated servers,
[32:06] SPEAKER: typically you do, well, I mean, there's a bunch of ways
[32:08] SPEAKER: to do it.
[32:09] SPEAKER: If it's a big game, then you're going to do a mixture
[32:10] SPEAKER: of bare metal servers that you actually have,
[32:12] SPEAKER: like you pay somebody to put some server machines
[32:16] SPEAKER: in a data center someplace.
[32:17] SPEAKER: And often because of the way game servers work,
[32:20] SPEAKER: those aren't like, those aren't giant,
[32:24] SPEAKER: like they're not thread rippers or something like that.
[32:26] SPEAKER: Cause you're not able, like often on a game server,
[32:29] SPEAKER: since game servers are very regularly single threaded,
[32:31] SPEAKER: you want a smaller number of faster cores
[32:35] SPEAKER: because that'll let you have more people on the server
[32:37] SPEAKER: at a time or something like that.
[32:38] SPEAKER: So if you're posting something like Fortnite,
[32:40] SPEAKER: they're going to have a bunch of 14, 900 Ks
[32:44] SPEAKER: in a data center someplace with like one shard
[32:48] SPEAKER: or two Fortnite instances at a time on them, right?
[32:51] SPEAKER: And then they'll also have,
[32:54] SPEAKER: and those hardware machines will be the baseline, right?
[32:57] SPEAKER: And that's what's running all the time.
[33:00] SPEAKER: Cause you can't turn those on and off really,
[33:02] SPEAKER: updating them is a kind of a hassle, yada yada.
[33:05] SPEAKER: They'll also have a cloud solution for like days
[33:09] SPEAKER: that Drake shows up to play on some stream
[33:11] SPEAKER: and a million extra people play Fortnite that day.
[33:14] SPEAKER: And those machines are more expensive per minute
[33:17] SPEAKER: or per hour to run cause they're cloud hosts,
[33:20] SPEAKER: whereas the data center machines are fly rate bus,
[33:22] SPEAKER: bandwidth or something like that.
[33:25] SPEAKER: But you can turn them on and off when you're not using them.
[33:27] SPEAKER: So like figuring out that math is a big part
[33:31] SPEAKER: of what like a DevOps or release managers
[33:34] SPEAKER: or live game ops person does these days.
[33:40] SPEAKER: Now, the place that Cat Will Mu is talking about
[33:44] SPEAKER: is, hey, we have not 10 times,
[33:48] SPEAKER: but a thousand times the number of people
[33:50] SPEAKER: that are usually on this site
[33:51] SPEAKER: or 10,000 times the number of people
[33:52] SPEAKER: usually hitting the site.
[33:54] SPEAKER: And then they find the bottlenecks and the weird edge cases
[33:56] SPEAKER: that don't exist in the day to day.
[33:58] SPEAKER: So Apple is a good example of this.
[34:00] SPEAKER: For iPhone launches for a long time,
[34:03] SPEAKER: everything would be great.
[34:04] SPEAKER: Apple's website would be going great.
[34:06] SPEAKER: You put all your stuff in the cart, you'd order the phone,
[34:09] SPEAKER: and then you'd get to the part
[34:10] SPEAKER: where you put your credit card in and it's like,
[34:11] SPEAKER: oh man, we're not gonna do this.
[34:13] SPEAKER: Or you'd get to the part where you apply
[34:14] SPEAKER: for the Apple financing or Verizon's three-year thing,
[34:19] SPEAKER: and their connections to these outside services
[34:21] SPEAKER: would bomb out, which is why they started doing the,
[34:24] SPEAKER: hey, you can pre-approve your Apple loan,
[34:28] SPEAKER: your Verizon connection, your AT&T connection,
[34:31] SPEAKER: your credit card charge.
[34:32] SPEAKER: - That's very smart.
[34:33] SPEAKER: - A week in advance, and then just on the morning of,
[34:35] SPEAKER: you just get up and log in at five o'clock in the morning
[34:37] SPEAKER: and hit the give me a phone button.
[34:39] SPEAKER: - Sidebar, like I guess they're catering
[34:41] SPEAKER: to a global customer base here,
[34:43] SPEAKER: but why does Apple continue to set the pre-orders
[34:45] SPEAKER: for insane early in the morning US time,
[34:49] SPEAKER: which surely is a huge, huge,
[34:52] SPEAKER: I mean, that's their home territory.
[34:53] SPEAKER: - I bet it's actually so that they don't have
[34:56] SPEAKER: an enormous wave of people all hitting at the same time.
[34:58] SPEAKER: - Oh, I guess, sure, that is a good way
[35:01] SPEAKER: to naturally filter some people out who don't wanna wake up.
[35:04] SPEAKER: - Yeah, they're gonna sell the phones
[35:06] SPEAKER: to the same people.
[35:08] SPEAKER: The question is how can they spread out that
[35:11] SPEAKER: over the infrastructure?
[35:12] SPEAKER: I bet the capitalist me says,
[35:16] SPEAKER: oh, they looked at which time zones
[35:18] SPEAKER: they could hit most effectively at that launch time,
[35:20] SPEAKER: but then the realist me looked at it and was like,
[35:23] SPEAKER: oh, people are gonna buy the phones regardless,
[35:24] SPEAKER: so it doesn't matter.
[35:25] SPEAKER: They just did it whichever way it levels out
[35:27] SPEAKER: the infrastructure hit the most, so.
[35:30] SPEAKER: - I believe that.
[35:31] SPEAKER: - Yeah, anyway, I think every time
[35:33] SPEAKER: they do one of these launches,
[35:34] SPEAKER: they find Target probably discovered five new bottlenecks
[35:37] SPEAKER: on their checkout process on Switch 2 pre-order day.
[35:41] SPEAKER: I am still smarting from that Switch 2 pre-order experience
[35:44] SPEAKER: and Target was the worst of all of them.
[35:46] SPEAKER: - Yeah, 'cause they kept saying that,
[35:47] SPEAKER: like Target was like, hey man, we got a Switch for you.
[35:49] SPEAKER: And then you'd go through the checkout card
[35:51] SPEAKER: and be like, no, we don't have a Switch for you.
[35:52] SPEAKER: - All the others to their credit put me in a queue,
[35:55] SPEAKER: which also screwed me in different ways
[35:56] SPEAKER: because I saw people on my feed who were,
[35:59] SPEAKER: got in the queue way after I did for 10 minutes
[36:01] SPEAKER: and then bought a Switch and I sat in it for an hour
[36:03] SPEAKER: and never got the opportunity,
[36:05] SPEAKER: but at least those just had me looking at a queue.
[36:07] SPEAKER: Whereas Target, I got to the confirm order step,
[36:11] SPEAKER: like four times and it never worked.
[36:13] SPEAKER: - Yeah.
[36:14] SPEAKER: - Infuriating, anyway.
[36:15] SPEAKER: Okay, next email is from Joel.
[36:17] SPEAKER: This is about getting AirPod Pros working with a Steam Deck.
[36:22] SPEAKER: I have MagicPods installed to get my AirPod Pro 2s
[36:25] SPEAKER: working right on my Steam Deck.
[36:27] SPEAKER: You're a Steam Deck guy,
[36:28] SPEAKER: you're gonna have to help me out with some of these terms.
[36:30] SPEAKER: It does require Decky, I have no idea what Decky is,
[36:32] SPEAKER: but if you're down with Homebrew,
[36:34] SPEAKER: it supports every feature I can think of
[36:36] SPEAKER: for the AirPod Pros 2,
[36:39] SPEAKER: including conversation awareness, it's pretty amazing.
[36:42] SPEAKER: I can't recommend it enough.
[36:43] SPEAKER: - So I thought conversation awareness happened
[36:45] SPEAKER: on the headphones, but I guess it doesn't
[36:47] SPEAKER: 'cause I only use my AirPods with Apple stuff.
[36:49] SPEAKER: A Decky loader, for folks who don't know,
[36:51] SPEAKER: is a Homebrew plugin launcher for the Steam Deck
[36:54] SPEAKER: that lets you extend the Steam Deck,
[36:57] SPEAKER: like the Steam Deck handheld UI, not the desktop UI.
[37:01] SPEAKER: - Got it.
[37:02] SPEAKER: - You can style menus,
[37:04] SPEAKER: you can add other storefronts, stuff like that.
[37:07] SPEAKER: - That's cool, yeah, I'm looking at MagicPods here.
[37:09] SPEAKER: Easily control AirPods and Beats headphones and more.
[37:12] SPEAKER: - Well, so the Beats headphones use the same chips
[37:15] SPEAKER: as the AirPods. - Of course, of course.
[37:18] SPEAKER: - But yeah, this looks pretty good.
[37:19] SPEAKER: - Oh, actually it supports a bunch of Samsung Galaxy buds
[37:23] SPEAKER: as well, according to this.
[37:25] SPEAKER: - It looks like it does the...
[37:27] SPEAKER: The big thing is it fixes the Apple devices
[37:31] SPEAKER: grabbing the AirPods back,
[37:33] SPEAKER: and the conversation mode's really quite nice.
[37:37] SPEAKER: I'm gonna have to try this out.
[37:38] SPEAKER: I do not have, I don't have Decky loader
[37:42] SPEAKER: on my current Steam Deck, I don't think right now,
[37:44] SPEAKER: but I'll put that on 'cause this is worth fussing with.
[37:47] SPEAKER: - Yeah. - Seems good.
[37:51] SPEAKER: - I don't know what the term is for the Apple device,
[37:53] SPEAKER: whatever you just said,
[37:54] SPEAKER: the Apple device grabbing the headphones back.
[37:56] SPEAKER: - Yeah, yeah, yeah.
[37:57] SPEAKER: - I don't know what the term for that is,
[37:58] SPEAKER: but that is something I was thinking about
[37:59] SPEAKER: as I have thought about getting AirPod Pro 3s
[38:02] SPEAKER: for potentially for Switch 2's use.
[38:05] SPEAKER: Like, is that a pain dealing with non-Apple devices
[38:09] SPEAKER: and having to like control what device is using them
[38:12] SPEAKER: at any given time?
[38:13] SPEAKER: - So yes and no, you have to...
[38:17] SPEAKER: Whereas with the Apple devices,
[38:20] SPEAKER: when I put my iPhone down and pick up my iPad,
[38:23] SPEAKER: it just switches over automatically, right?
[38:27] SPEAKER: With non-Apple devices on the AirPods,
[38:29] SPEAKER: you have to manually go into the Bluetooth menu
[38:31] SPEAKER: and hit the connect thing.
[38:34] SPEAKER: So it doesn't do it automatically.
[38:36] SPEAKER: - And then what about moving back to an Apple device?
[38:38] SPEAKER: Do you have to manually air again there
[38:40] SPEAKER: or is that smart enough to just do it?
[38:42] SPEAKER: - So you don't have to pair,
[38:44] SPEAKER: but you do have to go into the menu
[38:46] SPEAKER: and hit the connect button
[38:47] SPEAKER: once you're coming back sometimes.
[38:49] SPEAKER: It's like, it's really weird.
[38:52] SPEAKER: - That's the worst thing about Bluetooth is sometimes.
[38:55] SPEAKER: - Well, I think the rule is if they're in the case,
[38:57] SPEAKER: then it resets the connection
[38:59] SPEAKER: and it just goes to whatever thing you're using again.
[39:01] SPEAKER: But if you like have them in your ears
[39:03] SPEAKER: and you want to use your phone
[39:04] SPEAKER: and then you switch to the Steam Deck
[39:05] SPEAKER: and then you want to switch back to the Switch
[39:07] SPEAKER: and then you want to switch back to the phone,
[39:09] SPEAKER: you're going to have to do some Bluetooth menu work.
[39:12] SPEAKER: - Like that's the most annoying thing
[39:13] SPEAKER: about dealing with Bluetooth pairing
[39:14] SPEAKER: is that it's never, it never seems consistent to me.
[39:16] SPEAKER: Like sometimes my watch will just find the earbuds
[39:21] SPEAKER: when I pull them out of the case.
[39:22] SPEAKER: Sometimes I have to go in there and tell it to do it again.
[39:25] SPEAKER: - Yeah, so it's way better
[39:27] SPEAKER: than the traditional Bluetooth method, which is,
[39:30] SPEAKER: hey, your headphones support X number of connections
[39:34] SPEAKER: and everything kind of works okay
[39:36] SPEAKER: until you get X plus one number of devices.
[39:39] SPEAKER: It's not as good, it's not as good as the default.
[39:43] SPEAKER: Like I want to see what this implementation is
[39:44] SPEAKER: 'cause I've not used a non-Apple implementation of this.
[39:51] SPEAKER: And it looks like they have a Windows version
[39:52] SPEAKER: of this thing too, of MagicPods.
[39:54] SPEAKER: So you can get it for other non-Apple devices,
[39:57] SPEAKER: which is exciting.
[39:58] SPEAKER: I'm gonna set this up on my laptop and my Steam Deck.
[40:04] SPEAKER: The other thing is after we talked about
[40:06] SPEAKER: the AirPods Pro first-generation had a hard time
[40:10] SPEAKER: connecting to Steam Decks for whatever reason,
[40:12] SPEAKER: multiple people wrote in to let us know
[40:14] SPEAKER: that the AirPod Pros 2 didn't have that problem.
[40:17] SPEAKER: They changed whatever, either Valve or Apple
[40:21] SPEAKER: changed whatever was the issue
[40:23] SPEAKER: as people were able to connect with that.
[40:25] SPEAKER: And I've since connected my AirPod Pros 2
[40:28] SPEAKER: to the Switch 2 and it works great.
[40:29] SPEAKER: - Yeah, I'm gonna give the threes a little longer
[40:31] SPEAKER: to see what people's experiences are with various devices.
[40:34] SPEAKER: I did a little bit of cursory looking around on Reddit,
[40:36] SPEAKER: on the Switch 2 subreddit about Bluetooth headphones
[40:40] SPEAKER: in general on there.
[40:41] SPEAKER: And the results did not sound super encouraging.
[40:43] SPEAKER: People said like, people said it's basically the same
[40:46] SPEAKER: as similar at least to the Switch 1.
[40:48] SPEAKER: You're looking at like 150 milliseconds of latency
[40:50] SPEAKER: to Bluetooth headphones because Nintendo uses
[40:53] SPEAKER: like old Bluetooth and old codecs and stuff.
[40:57] SPEAKER: I mean, you know, again, some of that depends
[40:59] SPEAKER: on how sensitive you are to that kind of thing.
[41:00] SPEAKER: But that sounds like kind of a lot to me.
[41:02] SPEAKER: So I don't know if the dream might be dead.
[41:05] SPEAKER: I'm not sure.
[41:06] SPEAKER: - 150 milliseconds is a lot.
[41:08] SPEAKER: - Yeah, it is.
[41:10] SPEAKER: - You know, you could just get a wire plugged in headphones.
[41:13] SPEAKER: - It's true.
[41:15] SPEAKER: I don't know, man, dealing with corded noise canceling
[41:18] SPEAKER: headphones on an airplane is kind of getting old.
[41:21] SPEAKER: - I mean, I will, yeah.
[41:23] SPEAKER: That's true. - Anyway, yeah.
[41:25] SPEAKER: - All right, last email from Mike, speaking of Nintendo.
[41:29] SPEAKER: Say you managed to get a ticket to the Nintendo museum
[41:31] SPEAKER: in Japan and are salivating at all the exclusive
[41:34] SPEAKER: Nintendo merch available from such a trip.
[41:37] SPEAKER: At what point would you say that there are too many
[41:39] SPEAKER: coffee mugs to take back with you
[41:41] SPEAKER: to the United States?
[41:43] SPEAKER: I believe they sell 17 or more coffee mugs
[41:45] SPEAKER: for a variety of Nintendo systems.
[41:47] SPEAKER: I will say, unless something has changed
[41:49] SPEAKER: in the last few months, it's 15.
[41:52] SPEAKER: I thought of Brad because on an Exelander podcast,
[41:56] SPEAKER: Brad mentioned wanting to have a complete set.
[41:57] SPEAKER: The reason I know the number of coffee mugs
[41:59] SPEAKER: is because I now own 14 of them.
[42:01] SPEAKER: - Really?
[42:02] SPEAKER: - Yes.
[42:03] SPEAKER: - Wow.
[42:04] SPEAKER: - Largely thanks to an incredibly kind benefactor
[42:09] SPEAKER: who was willing to haul some mugs across the ocean for me.
[42:13] SPEAKER: - Can you go to the museum without having a ticket?
[42:18] SPEAKER: 'Cause the tickets are kind of hard, right?
[42:19] SPEAKER: - No, as far as I know, it's still a multi-month lead time,
[42:24] SPEAKER: I think, to get a ticket for the museum.
[42:26] SPEAKER: - Wow.
[42:27] SPEAKER: - I believe this benefactor said they would have brought
[42:30] SPEAKER: all 15, but they were sold out of the Switch mug on the day.
[42:33] SPEAKER: - Ah, boo.
[42:34] SPEAKER: - And I still let him owe that person a beer.
[42:36] SPEAKER: They were incredibly kind to do that.
[42:39] SPEAKER: - Wow.
[42:40] SPEAKER: - I've been meaning to order that Switch one.
[42:43] SPEAKER: I found an exporter in Japan that sells them
[42:46] SPEAKER: for like not too bad of a markup.
[42:48] SPEAKER: - Okay.
[42:49] SPEAKER: - And I never got around to doing it
[42:50] SPEAKER: before the tariffs went into effect,
[42:51] SPEAKER: and now I don't know how that's going to affect
[42:54] SPEAKER: something like this.
[42:56] SPEAKER: - Oh yeah, so they say, yeah, you can only get in
[42:58] SPEAKER: if you have a ticket, that's wild.
[43:00] SPEAKER: - Yeah, yes, the museum is definitely absolutely not
[43:03] SPEAKER: just show up and go.
[43:04] SPEAKER: - It almost seems like if you want to go to the museum
[43:06] SPEAKER: and you don't live in Japan, you get your tickets
[43:10] SPEAKER: and then book your entire trip around going to the museum.
[43:13] SPEAKER: - Yep.
[43:14] SPEAKER: - That's wild.
[43:15] SPEAKER: - Yep, still quite exclusive.
[43:16] SPEAKER: I have to assume in another year or two,
[43:18] SPEAKER: it'll probably die down a little bit.
[43:20] SPEAKER: - I mean, you say that, but maybe not.
[43:21] SPEAKER: - One would hope, but I don't know.
[43:24] SPEAKER: Anyway, to answer your question,
[43:25] SPEAKER: no number of mugs is too many.
[43:28] SPEAKER: Those are extremely nice mugs.
[43:30] SPEAKER: I love them deeply.
[43:33] SPEAKER: - I was going to say, I'm starting to pare down mugs
[43:36] SPEAKER: and I'm keeping the couple that I have
[43:38] SPEAKER: that are handmade by friends and family members
[43:41] SPEAKER: and like the Aperture Science ones,
[43:43] SPEAKER: and that's pretty much it.
[43:44] SPEAKER: Everything else is going.
[43:46] SPEAKER: The old tested mug, I still have one of those.
[43:48] SPEAKER: - Yes, I'm actually unpacking all of my old giant bomb
[43:51] SPEAKER: glassware and ceramic merch away.
[43:54] SPEAKER: - Wow.
[43:55] SPEAKER: - So it doesn't get broken at this point.
[43:57] SPEAKER: Anyway.
[43:58] SPEAKER: - There you go.
[43:59] SPEAKER: - All right.
[44:00] SPEAKER: Late night rec.
[44:02] SPEAKER: How many sets of sheets do you own?
[44:04] SPEAKER: How many did you own when you were living alone?
[44:06] SPEAKER: How many is too many?
[44:08] SPEAKER: - Okay, I have, I don't remember how many I owned
[44:10] SPEAKER: when I was living alone
[44:11] SPEAKER: 'cause that was a hundred years ago at this point,
[44:14] SPEAKER: but I have two identical white sheets for each bed
[44:20] SPEAKER: so that you don't have to take,
[44:22] SPEAKER: so I can take the sheets off, put new sheets on
[44:26] SPEAKER: and not have to like have the bed down all day
[44:30] SPEAKER: while we're washing sheets.
[44:31] SPEAKER: I don't have two duvet covers.
[44:33] SPEAKER: So the duvet cover is separate from that.
[44:36] SPEAKER: - Okay.
[44:37] SPEAKER: - And then we also have sets of flannel sheets
[44:38] SPEAKER: for both beds.
[44:40] SPEAKER: I'd say we have probably three or four sets now.
[44:44] SPEAKER: - Yeah.
[44:46] SPEAKER: - We are on, well, it's gotten a little looser,
[44:48] SPEAKER: more loose than I would like lately.
[44:50] SPEAKER: We need to get our act back together,
[44:51] SPEAKER: but we became like,
[44:53] SPEAKER: we became like change the sheets once a week.
[44:55] SPEAKER: - Oh God, that's too much.
[44:57] SPEAKER: - What are you talking about?
[44:59] SPEAKER: - Like once a week?
[45:00] SPEAKER: - Yeah, hell yeah.
[45:01] SPEAKER: - What are you doing in there, man?
[45:03] SPEAKER: - Nothing, I mean, it's just,
[45:04] SPEAKER: I just like sleeping in clean sheets.
[45:06] SPEAKER: - I do like sleeping in clean sheets, but I mean,
[45:08] SPEAKER: so I guess you're like, I do the sheets more often
[45:12] SPEAKER: than I do the duvet cover.
[45:13] SPEAKER: For me, for a long time, I used to not use a top sheet.
[45:16] SPEAKER: I would just do the duvet covers.
[45:17] SPEAKER: That meant you had to watch the duvet cover every time,
[45:19] SPEAKER: which is an enormous pain in the ass.
[45:21] SPEAKER: 'Cause you got to take the thing out
[45:22] SPEAKER: and you got to tie it back in and it's just a lot.
[45:26] SPEAKER: When we switched to using a top sheet again,
[45:28] SPEAKER: then watching the duvet cover
[45:30] SPEAKER: became an every other time I watched this sheet situation.
[45:35] SPEAKER: But yeah, I don't know.
[45:36] SPEAKER: - Yeah, I mean, to be clear,
[45:37] SPEAKER: we only wash the fitted sheets and top sheets regularly,
[45:41] SPEAKER: like the duvet or blankets on top of that
[45:44] SPEAKER: don't get washed nearly as often.
[45:45] SPEAKER: But I tried to get a little science-y with this
[45:48] SPEAKER: and Google around for tests of bacteria,
[45:53] SPEAKER: dead skin, dust mites, whatever.
[45:55] SPEAKER: - Yeah.
[45:56] SPEAKER: - 'Cause everywhere you go, the feedback seems to be,
[45:58] SPEAKER: hey, you're probably not washing your sheets enough,
[46:00] SPEAKER: but couldn't find anything super definitive.
[46:03] SPEAKER: - Big laundry detergent wants you to think that, Brad.
[46:06] SPEAKER: - Probably, what started it for me
[46:08] SPEAKER: was becoming a night shower during the pandemic.
[46:10] SPEAKER: - Yep.
[46:12] SPEAKER: - At that point, it was basically,
[46:14] SPEAKER: okay, I'm going to bed clean now
[46:15] SPEAKER: because I'm showering right before bed every night
[46:17] SPEAKER: and so I want the sheets to be clean as well.
[46:20] SPEAKER: - But then if you're going to bed clean,
[46:23] SPEAKER: then the sheets get dirty a lot slower.
[46:25] SPEAKER: - Yeah, but then you just maximize your cleanliness
[46:27] SPEAKER: by both showering at night and changing the sheets more often.
[46:29] SPEAKER: - Too far, man.
[46:31] SPEAKER: - I gotta say, we switched from kind of fancy sheets
[46:36] SPEAKER: that we used to use for a long time
[46:37] SPEAKER: when they got really expensive during the pandemic
[46:40] SPEAKER: and we tried a bunch of cheap sheets from different places
[46:45] SPEAKER: and the Target, like the Target brand,
[46:48] SPEAKER: the nice Target brand sheets with the deep pockets in that
[46:51] SPEAKER: are my favorite sheets we've ever had.
[46:53] SPEAKER: I think they're easy to make the bed,
[46:56] SPEAKER: the gussets on the side are deep enough
[47:00] SPEAKER: that they work on even the super thick mattresses
[47:03] SPEAKER: in my daughter's room
[47:05] SPEAKER: and they have the top and bottom labeled, which I love.
[47:11] SPEAKER: Like, so when you're trying to figure out
[47:12] SPEAKER: which side is which on a queen size bed,
[47:14] SPEAKER: which is basically square, it's really nice.
[47:17] SPEAKER: - That is smart.
[47:18] SPEAKER: - Yeah.
[47:19] SPEAKER: - All right, Ambush Penguin Charlie.
[47:22] SPEAKER: - Also don't buy shit from Target, I guess, right now.
[47:24] SPEAKER: I forgot. - Yeah.
[47:25] SPEAKER: - Yeah.
[47:26] SPEAKER: - Yes.
[47:27] SPEAKER: - Okay, Ambush Penguin Charlie writes in,
[47:30] SPEAKER: what's your process for documenting yourself
[47:32] SPEAKER: when you're setting up something like a new operating system
[47:34] SPEAKER: or an app install?
[47:35] SPEAKER: I've heard you mentioned this several times
[47:36] SPEAKER: on different podcasts
[47:37] SPEAKER: and I'm curious what that looks like for you in practice.
[47:40] SPEAKER: Software setup feels one and done and ephemeral enough
[47:43] SPEAKER: that it's hard for me to remember, plan ahead
[47:45] SPEAKER: or take notes as I go.
[47:47] SPEAKER: Unlike hardware installs, which feels higher stakes
[47:50] SPEAKER: and so I pre-plan, then I then use the end product
[47:53] SPEAKER: to trace backwards to aid in filling in gaps
[47:55] SPEAKER: and documentation.
[47:56] SPEAKER: - Oh, so okay, I got kind of obsessive about this
[47:59] SPEAKER: when I started doing server stuff
[48:00] SPEAKER: with the FreeNAS and TrueNAS years and years ago
[48:03] SPEAKER: 'cause I would do something clever
[48:06] SPEAKER: and then a year later it would break or need updating
[48:08] SPEAKER: and I wouldn't remember how to update it
[48:10] SPEAKER: or fix it when it broke
[48:11] SPEAKER: and then I'd have to recreate all the work
[48:13] SPEAKER: that was doing that.
[48:14] SPEAKER: So the tool that I've used has changed off and on
[48:17] SPEAKER: over the years.
[48:18] SPEAKER: I used simple note type note taking apps for a long time.
[48:23] SPEAKER: These days I'm using Notion just 'cause it's easy,
[48:26] SPEAKER: it syncs automatically with everything.
[48:27] SPEAKER: The free version is more than enough
[48:29] SPEAKER: for personal note taking
[48:31] SPEAKER: and I have basically a tree in my Notion
[48:34] SPEAKER: that's just like one that's the computers in the house
[48:40] SPEAKER: and then the other one is things I've figured out how to do
[48:43] SPEAKER: and my bar for that is if I had to Google some stuff
[48:47] SPEAKER: and read a bunch of forum posts
[48:48] SPEAKER: to figure out how to do something, I write it down
[48:50] SPEAKER: and I used to just do links to those forum posts
[48:54] SPEAKER: but I've gotten burned enough by the link rot
[48:56] SPEAKER: that now I just copy and paste the relevant shit
[48:59] SPEAKER: along with the link and put that in the documentation.
[49:02] SPEAKER: So it's not like I'm writing docs
[49:04] SPEAKER: that I would post on the internet someplace.
[49:06] SPEAKER: I'm literally just giving myself enough information
[49:09] SPEAKER: to understand what I did
[49:11] SPEAKER: and how to recreate it if I need to.
[49:13] SPEAKER: And then also if I do something and they're like,
[49:18] SPEAKER: here's how to update it,
[49:19] SPEAKER: I usually copy that information over too
[49:21] SPEAKER: 'cause for whatever reason, I can never remember
[49:24] SPEAKER: how to update the pie hole
[49:25] SPEAKER: even though I just have to log in with SSH
[49:28] SPEAKER: and type pie hole up or whatever.
[49:30] SPEAKER: - Pie hole dash upgrade.
[49:31] SPEAKER: - Yeah, dash upgrade.
[49:32] SPEAKER: - Maybe it's dash up actually.
[49:34] SPEAKER: I've moved on as we have mentioned.
[49:37] SPEAKER: - Yeah.
[49:38] SPEAKER: - That's a way better answer than mine
[49:39] SPEAKER: which is that I don't document anything
[49:41] SPEAKER: because I just can't be bothered which is what it is.
[49:46] SPEAKER: It leads to every time something breaks
[49:48] SPEAKER: having to go do the detective work
[49:49] SPEAKER: of figuring out what broke and what I did
[49:52] SPEAKER: and how to recreate it.
[49:54] SPEAKER: But anyway.
[49:56] SPEAKER: - Yeah, it's-
[49:57] SPEAKER: - I mean, there's never gonna be a hard and fast answer
[50:00] SPEAKER: for this, but what's more work?
[50:02] SPEAKER: Like doing the documentation as you go
[50:04] SPEAKER: or doing extra work to fix something
[50:06] SPEAKER: 'cause you don't remember how on the backend,
[50:08] SPEAKER: like it's more work in both cases.
[50:10] SPEAKER: So I'm not sure what's worse.
[50:12] SPEAKER: - For me, I just do five minutes of copying and pasting
[50:15] SPEAKER: and then dump it into the notion bucket basically.
[50:20] SPEAKER: I hosed the Debbie install on my server
[50:22] SPEAKER: a month or about six weeks ago
[50:24] SPEAKER: when I was moving to Trixie when it came out
[50:26] SPEAKER: to rebuild that entire thing from scratch.
[50:28] SPEAKER: So that was kind of an extreme example.
[50:30] SPEAKER: - Yeah.
[50:32] SPEAKER: - And then to be clear,
[50:33] SPEAKER: the old install was entirely there.
[50:35] SPEAKER: It just wasn't working.
[50:36] SPEAKER: - That's always nice.
[50:37] SPEAKER: - And so the point is I could copy
[50:39] SPEAKER: all the configuration files and stuff over.
[50:41] SPEAKER: It was substantially easier
[50:43] SPEAKER: than doing literally everything from scratch,
[50:45] SPEAKER: but yes, it does bite you occasionally.
[50:47] SPEAKER: - Yeah.
[50:49] SPEAKER: - Tactical tug.
[50:51] SPEAKER: - Tug boat, just to be clear.
[50:52] SPEAKER: This is my understanding.
[50:53] SPEAKER: They came in and clarified.
[50:54] SPEAKER: - That's right.
[50:55] SPEAKER: They came in and said they also were referring
[50:57] SPEAKER: to a tug boat actually.
[50:58] SPEAKER: - They directly cited a military, I think, tug boat
[51:04] SPEAKER: that was used in like combat harbors or something.
[51:07] SPEAKER: - So we were right.
[51:09] SPEAKER: - Yeah.
[51:10] SPEAKER: - All right.
[51:11] SPEAKER: - It's the British who are wrong, Brad.
[51:12] SPEAKER: - That's right, yes.
[51:13] SPEAKER: As always.
[51:14] SPEAKER: - Yeah.
[51:15] SPEAKER: - Okay, this is a big question.
[51:18] SPEAKER: How do game engines work?
[51:20] SPEAKER: You'll hear things like a game X is built
[51:22] SPEAKER: on the unreal engine or the unity engine and so on,
[51:25] SPEAKER: but how does that affect the game?
[51:26] SPEAKER: And what does it mean for me as a gamer?
[51:28] SPEAKER: Is it just a bragging rights similar to a fuck you,
[51:31] SPEAKER: my car has a V8 or is it something
[51:34] SPEAKER: to actually pay attention to as a gamer or user?
[51:37] SPEAKER: As a gamer or user, no, absolutely not.
[51:39] SPEAKER: Like if the game is good, if it runs well,
[51:41] SPEAKER: that's all that matters from the perspective of a player.
[51:45] SPEAKER: - There's a lot of discourse about this, Brad.
[51:47] SPEAKER: - Yeah, dude, I don't even know how much I'd like
[51:49] SPEAKER: that stuff drives me up the wall.
[51:52] SPEAKER: Every single topic on the planet
[51:54] SPEAKER: has a grifter class attached to it now.
[51:57] SPEAKER: - You're not wrong, yeah.
[51:58] SPEAKER: - And even the subject,
[52:00] SPEAKER: even the sub sub category of video game engines
[52:03] SPEAKER: has a whole like legion of grifters on Twitter now
[52:06] SPEAKER: who like outrage bait over like,
[52:08] SPEAKER: oh, the unreal engine sucks ass.
[52:09] SPEAKER: Like, oh, based Kojima productions
[52:12] SPEAKER: using the godlike Decima engine.
[52:14] SPEAKER: Like there's people out there who basically will just say,
[52:16] SPEAKER: hey, if this game uses engine X, it sucks.
[52:18] SPEAKER: If it uses engine Y, it's amazing.
[52:20] SPEAKER: And like, they seem to think it's as simple as that
[52:23] SPEAKER: because they get paid on engagement now.
[52:26] SPEAKER: So that's not the case at all.
[52:28] SPEAKER: - I feel a little bit maybe responsible for some of this
[52:32] SPEAKER: because at Maximum PC in like 2001 or 2002,
[52:35] SPEAKER: I wrote a feature that was really popular about game engines
[52:40] SPEAKER: and what different ones brought to the table.
[52:44] SPEAKER: But yeah, to your point, the dialogue around
[52:48] SPEAKER: Unity blows, unreal sucks, blah, blah, blah.
[52:52] SPEAKER: Like I was watching a streamer the other day
[52:53] SPEAKER: and it was not to put somebody on blast,
[52:56] SPEAKER: but they were talking about how
[52:59] SPEAKER: standing on rocks was slidey in the same way
[53:02] SPEAKER: and Rust and Tarkov, both Unity games.
[53:06] SPEAKER: But that is, yes, that is a physics thing
[53:08] SPEAKER: that is probably tied to Unity physics,
[53:11] SPEAKER: the Unity physics engines that they use.
[53:13] SPEAKER: But also it's because the collider on top of the rocks
[53:16] SPEAKER: in those games is not big enough for the player capsule
[53:20] SPEAKER: to fit on so the physics doesn't know what to do, right?
[53:23] SPEAKER: So like everybody attributes stuff to janky engines
[53:27] SPEAKER: or bloat or whatever.
[53:29] SPEAKER: And generally speaking, these are all decisions made
[53:32] SPEAKER: by game developers or by publishers or by expediency.
[53:36] SPEAKER: And the game engine, what the game engine provides
[53:41] SPEAKER: is a framework for making a game, right?
[53:43] SPEAKER: Like that's it, it provides a series of APIs
[53:46] SPEAKER: that you can use to draw things on the screen
[53:48] SPEAKER: and take input from users and connect to networks
[53:52] SPEAKER: and server infrastructure.
[53:55] SPEAKER: - Handles internal game logic that governs everything
[53:58] SPEAKER: from upgrade mechanics to menus to world simulation
[54:01] SPEAKER: and physics, player input, like you said, rendering,
[54:03] SPEAKER: like it's a huge part of it, sound, playback, music.
[54:07] SPEAKER: - But the asterisk on all of that is that
[54:10] SPEAKER: all of that stuff also, like the game logic stuff,
[54:14] SPEAKER: no game engines provide game logic stuff.
[54:16] SPEAKER: That's all written from scratch
[54:17] SPEAKER: for every single game ever, right?
[54:19] SPEAKER: Physics is, you have a physics engine
[54:22] SPEAKER: that you can do basic things with,
[54:25] SPEAKER: but for the most part, the game developer says,
[54:28] SPEAKER: okay, here's what the jump length is gonna,
[54:29] SPEAKER: like there's no, the unreal feel is because unreal ships
[54:34] SPEAKER: a bunch of unreal engine demos
[54:36] SPEAKER: that a lot of people use as the basis of their,
[54:40] SPEAKER: like if you're making a shooter,
[54:42] SPEAKER: the common wisdom is start with unreal shooter
[54:45] SPEAKER: as your template, because then you can also use assets
[54:47] SPEAKER: from the unreal asset store,
[54:49] SPEAKER: because they're gonna be pre-baked for that shooter template
[54:52] SPEAKER: 'cause that's what,
[54:54] SPEAKER: everybody has a shared common language there, right?
[54:58] SPEAKER: So that means that like your capsule,
[54:59] SPEAKER: your player capsule sizes are all the same
[55:01] SPEAKER: as that shooter template
[55:02] SPEAKER: and that makes games feel necessarily the same.
[55:04] SPEAKER: You don't have to do that, that's an option, right?
[55:07] SPEAKER: It's a, if you're making a $300 million game,
[55:10] SPEAKER: you're not gonna do that.
[55:11] SPEAKER: If you're making a game that you wanna feel
[55:14] SPEAKER: like it can compete with a $300 million game,
[55:16] SPEAKER: but costs $5 million, then you're probably gonna do that.
[55:18] SPEAKER: And that's kind of it.
[55:21] SPEAKER: - I mean, and game engines are just software
[55:23] SPEAKER: and software can be made to do anything if you modify it
[55:26] SPEAKER: and adapt it to your needs enough.
[55:29] SPEAKER: - Yeah. - I mean, within reason,
[55:30] SPEAKER: like obviously you're like, but you see it all the time,
[55:33] SPEAKER: like you see developers talking about this,
[55:35] SPEAKER: like they used UE5 or whatever,
[55:38] SPEAKER: but then they ripped out blank component
[55:40] SPEAKER: and rewrote their own or something or modified it,
[55:42] SPEAKER: you know what I mean?
[55:43] SPEAKER: Like you can customize and adapt the engine to do things
[55:48] SPEAKER: that it wasn't made to do out of the box
[55:49] SPEAKER: or to massage the way it does things.
[55:52] SPEAKER: But I mean, like you said, that requires work
[55:55] SPEAKER: and that requires scoping around that work and et cetera.
[55:58] SPEAKER: - Well, and there's big downstream consequences.
[56:00] SPEAKER: So like we rewrote a big chunk of the sound
[56:03] SPEAKER: of the WY's sound engine implementation in Unreal
[56:09] SPEAKER: when we were working on the Anacrusis.
[56:10] SPEAKER: And it turned out to be a huge boondoggle
[56:13] SPEAKER: because when we needed to take a new Unreal update
[56:17] SPEAKER: to fix a different bug, that required a ton of refactoring
[56:20] SPEAKER: to support, to bring our changes forward
[56:23] SPEAKER: into the new version.
[56:24] SPEAKER: And like, so like generally speaking,
[56:28] SPEAKER: if you're working on a budget,
[56:30] SPEAKER: if you're working in an indie scale,
[56:32] SPEAKER: you don't wanna, even if you have source code access,
[56:34] SPEAKER: which everybody does now,
[56:36] SPEAKER: like don't, you don't wanna modify the,
[56:39] SPEAKER: you don't wanna modify the source code of the engine
[56:42] SPEAKER: because you wanna be able to take those engine upgrades.
[56:45] SPEAKER: Because like, if you're, say you're shipping a game on Godot
[56:48] SPEAKER: and you release it on Steam originally
[56:51] SPEAKER: and then Sony and Nintendo call and they're like,
[56:53] SPEAKER: "Hey, we'd like to get your game on our platforms."
[56:55] SPEAKER: But the plugins that work with the Sony infrastructure
[56:58] SPEAKER: and the Nintendo infrastructure
[57:00] SPEAKER: are on two different versions of Godot.
[57:02] SPEAKER: Like you have to be able to port your game
[57:04] SPEAKER: to those different engines of Godot,
[57:06] SPEAKER: or you have to spend way more time backporting
[57:09] SPEAKER: the PlayStation infrastructure plugin
[57:10] SPEAKER: and the Nintendo infrastructure plugins
[57:13] SPEAKER: to work on your game.
[57:16] SPEAKER: So it's like keeping your stuff portable
[57:19] SPEAKER: and easily upgradable makes a ton of sense.
[57:22] SPEAKER: But yeah, just generally speaking,
[57:24] SPEAKER: the YouTubers who bitch about Unreal and Unity
[57:26] SPEAKER: and all that stuff are not generally
[57:29] SPEAKER: particularly well-informed.
[57:30] SPEAKER: - No, they are definitely not.
[57:31] SPEAKER: Like, I feel like Kojima Productions
[57:33] SPEAKER: is an excellent test case for people taking the wrong lesson
[57:36] SPEAKER: from the situation because, okay,
[57:38] SPEAKER: they shipped the two Metal Gear Solid 5 games
[57:40] SPEAKER: on the Fox engine,
[57:42] SPEAKER: and now they've shipped the two Death Stranding games
[57:44] SPEAKER: on the Decima engine.
[57:46] SPEAKER: On a technical level,
[57:47] SPEAKER: one of the thing that all those games have in common
[57:48] SPEAKER: is that they look very good for the hardware
[57:50] SPEAKER: and they're also very performant for how good they look.
[57:53] SPEAKER: And for some reason, people have taken the lesson from that
[57:56] SPEAKER: of, oh, the Fox engine is so godly.
[57:59] SPEAKER: Oh, the Decima engine is so godly.
[58:01] SPEAKER: Nobody ever seems to stop and think,
[58:02] SPEAKER: maybe Kojima Productions is just really good
[58:04] SPEAKER: at building within the scope
[58:06] SPEAKER: of what their technology can support.
[58:07] SPEAKER: You know, like maybe they are really good
[58:09] SPEAKER: at understanding how to get good visuals
[58:11] SPEAKER: out of their technology without pushing it so hard
[58:13] SPEAKER: that the performance suffers.
[58:14] SPEAKER: Like it's never, hey, these developers are good
[58:16] SPEAKER: at their jobs.
[58:17] SPEAKER: It's always, oh, the software they're using
[58:19] SPEAKER: is so amazing or sucks.
[58:20] SPEAKER: - Yeah, but they make that software too.
[58:22] SPEAKER: - Right.
[58:23] SPEAKER: - But also there's two things there.
[58:25] SPEAKER: There's one, there's a novelty aspect
[58:27] SPEAKER: so that because it's not using the same unreal renderer
[58:31] SPEAKER: and all that stuff, the same unreal lighting model,
[58:33] SPEAKER: things look different and different,
[58:35] SPEAKER: our brains think different is good, right?
[58:36] SPEAKER: Which is good, that's a good thing, awesome for them.
[58:40] SPEAKER: The other thing is those are not general purpose engines.
[58:42] SPEAKER: Those are engines that are built for specific games.
[58:45] SPEAKER: And like, there's a reason they didn't bring,
[58:47] SPEAKER: I mean, there's multiple reasons
[58:48] SPEAKER: they didn't bring Fox forward for the new thing,
[58:50] SPEAKER: but like they spent hundreds of millions of dollars
[58:52] SPEAKER: making Death Stranding.
[58:53] SPEAKER: It's an enormous amount of money.
[58:55] SPEAKER: And like, you're not, they built a bespoke engine for that.
[59:00] SPEAKER: We saw what happened, you know, a battlefield,
[59:03] SPEAKER: a dice made a bespoke engine for battlefield
[59:06] SPEAKER: years and years ago.
[59:07] SPEAKER: And when EA tried to adapt that to general purpose use
[59:10] SPEAKER: the same way that Epic turned unreal
[59:12] SPEAKER: over a decade and a half into a multi-purpose game engine,
[59:16] SPEAKER: it was an enormous disaster on almost every front.
[59:19] SPEAKER: Like all of those games that shipped with Frostbite
[59:21] SPEAKER: had problems.
[59:22] SPEAKER: And like, it was, there were production problems,
[59:26] SPEAKER: there were delays, there was bad crunch,
[59:28] SPEAKER: there was all the stuff that makes video games shitty
[59:31] SPEAKER: because they were taking a bespoke engine
[59:34] SPEAKER: that was built to make battlefield games
[59:36] SPEAKER: and trying to jam Need for Speed and I can't remember what else.
[59:40] SPEAKER: Yeah, Mass Effect and Dragon Age and all of these other,
[59:44] SPEAKER: all of these other not fast paced military shooters
[59:48] SPEAKER: with vehicles games into them.
[59:50] SPEAKER: - Anthem grade?
[59:51] SPEAKER: - Yeah.
[59:52] SPEAKER: - That's a great example.
[59:53] SPEAKER: - Yeah, so like.
[59:54] SPEAKER: - Battlefield is another great example that you still see
[59:56] SPEAKER: where these types of people that talk shit about engines
[59:59] SPEAKER: all the time or talk shit about game developers will post,
[1:00:02] SPEAKER: like they'll post like the intro or that aircraft carrier
[1:00:04] SPEAKER: scene from battlefield three, I think it's three
[1:00:06] SPEAKER: or maybe four.
[1:00:07] SPEAKER: And they're just like, games looked like this 15 years ago,
[1:00:10] SPEAKER: what happened?
[1:00:11] SPEAKER: And the subtext is always why are game developers so bad
[1:00:13] SPEAKER: at their jobs now?
[1:00:14] SPEAKER: Like that's always what they're never stopping to realize
[1:00:16] SPEAKER: exactly what you just said of like,
[1:00:18] SPEAKER: that is like an on rails cinematic sequence of a person
[1:00:21] SPEAKER: in a plane on an aircraft carrier.
[1:00:23] SPEAKER: Like there's no geometry in that scene except for a plane
[1:00:26] SPEAKER: and an aircraft carrier, you know what I mean?
[1:00:27] SPEAKER: It's not like, there's not a big open world environment
[1:00:30] SPEAKER: with all kinds of like, with a massive possibility space
[1:00:33] SPEAKER: or whatever, it is a very constrained effectively hallway
[1:00:37] SPEAKER: scene, which like you said, with technology built exactly
[1:00:40] SPEAKER: around the needs of that scene, it's like the.
[1:00:42] SPEAKER: - Well, it's like fighting games.
[1:00:43] SPEAKER: Fighting games look really good because they blow
[1:00:45] SPEAKER: the entire console's poly budget on two characters
[1:00:48] SPEAKER: and a little bit of background.
[1:00:49] SPEAKER: - And a background with a fixed front camera angle, right?
[1:00:51] SPEAKER: Like, you know, like Brendan and Sanjay talked about that
[1:00:53] SPEAKER: on the skin deep episode.
[1:00:54] SPEAKER: I was like, you know, why didn't the,
[1:00:56] SPEAKER: why didn't the Doom 3 lighting catch on because it looked
[1:00:58] SPEAKER: so much better than everything else at the time.
[1:01:00] SPEAKER: And they were like, because it didn't scale beyond the game
[1:01:02] SPEAKER: with like tight, dark hallways, basically, you know, like,
[1:01:06] SPEAKER: like a lot of game engines are built specifically
[1:01:08] SPEAKER: for the needs of what the game is doing
[1:01:10] SPEAKER: and do not work beyond that.
[1:01:12] SPEAKER: Anyway, like there's just so, so much more nuance
[1:01:15] SPEAKER: to the technical implementation of modern video games
[1:01:18] SPEAKER: than a lot of the sort of outrage class on social media
[1:01:22] SPEAKER: gives credit to.
[1:01:23] SPEAKER: - Well, and then the last part of it is that the art
[1:01:27] SPEAKER: makes a huge difference, right?
[1:01:29] SPEAKER: Like if you look at, I love to reference Star Wars Outlaws
[1:01:33] SPEAKER: for this because that game is art dense in a way
[1:01:36] SPEAKER: that even most triple A games aren't these days, right?
[1:01:40] SPEAKER: When you walk through one of those cityscapes,
[1:01:43] SPEAKER: there's a bazillion physics based props everywhere you look.
[1:01:47] SPEAKER: And like the game looks, it looks grimy and gross
[1:01:52] SPEAKER: the way you want a 70s Star Wars to look.
[1:01:55] SPEAKER: And that's not engine, that is a bazillion people
[1:02:01] SPEAKER: in 10 studios around the world spent five years making pots,
[1:02:07] SPEAKER: like bespoke pots and trash cans and plants
[1:02:10] SPEAKER: and little guys and weird shit that's on tables
[1:02:13] SPEAKER: and stools that only work for one specific kind of
[1:02:19] SPEAKER: Star Wars alien and like all sorts of nonsense.
[1:02:22] SPEAKER: It's not like the engine just takes that work
[1:02:26] SPEAKER: and displays it.
[1:02:26] SPEAKER: It's not, it's like praising your word processor, right?
[1:02:30] SPEAKER: - Yes.
[1:02:31] SPEAKER: - So anyway.
[1:02:32] SPEAKER: - Like, you know, even a very well architected
[1:02:34] SPEAKER: performant engine can buckle if you cram too much stuff
[1:02:37] SPEAKER: in there at one time, right?
[1:02:38] SPEAKER: - Yeah.
[1:02:38] SPEAKER: But also don't listen to people who yell about this stuff
[1:02:41] SPEAKER: on YouTube 'cause usually they're kind of doofuses.
[1:02:43] SPEAKER: - Yup.
[1:02:44] SPEAKER: - Yup.
[1:02:45] SPEAKER: - Digital Foundry is the exception.
[1:02:47] SPEAKER: - Yes.
[1:02:48] SPEAKER: - Well informed.
[1:02:49] SPEAKER: - I mean, those folks who read white papers.
[1:02:51] SPEAKER: - Well, I mean, you know.
[1:02:52] SPEAKER: - They're paying attention to what goes on as SIGGRAPH
[1:02:55] SPEAKER: like they are not.
[1:02:56] SPEAKER: - They understand white papers is I think
[1:02:57] SPEAKER: the more important thing.
[1:02:58] SPEAKER: Yeah.
[1:02:59] SPEAKER: - Right, yes.
[1:03:00] SPEAKER: Okay, a question from Hornet.
[1:03:02] SPEAKER: Why is it that my phone can recognize what song
[1:03:04] SPEAKER: is being played inside a crowded restaurant
[1:03:06] SPEAKER: from inside my pocket?
[1:03:08] SPEAKER: But when I call someone, I sound like I'm using
[1:03:10] SPEAKER: the microphone that came with the Xbox Live starter kit
[1:03:12] SPEAKER: in 2002.
[1:03:14] SPEAKER: - It's 'cause of the codecs that we use for phone calls.
[1:03:16] SPEAKER: If you use FaceTime audio, it sounds nice.
[1:03:19] SPEAKER: - Yeah, sure.
[1:03:20] SPEAKER: I mean, I guess there's a lot of questions here.
[1:03:21] SPEAKER: A, what kind of phone are you using?
[1:03:23] SPEAKER: B, what is facilitating the phone call on the software end?
[1:03:27] SPEAKER: - Yeah, but like.
[1:03:28] SPEAKER: - There's a lot of variables there, but.
[1:03:29] SPEAKER: - I was gonna say like codec.
[1:03:34] SPEAKER: The codecs are, they upgraded the basic codec
[1:03:39] SPEAKER: for voice calls a few years ago.
[1:03:41] SPEAKER: It used to be a GSM, like a really incredibly low bit rate.
[1:03:46] SPEAKER: And now with the LTE change,
[1:03:48] SPEAKER: they changed it to a higher bit rate,
[1:03:51] SPEAKER: but it's still pretty low by modern standards.
[1:03:56] SPEAKER: Voice over LTE is the current thing.
[1:04:01] SPEAKER: And it's like, I'm trying to find the codec bit rate,
[1:04:04] SPEAKER: but it's still shockingly low.
[1:04:05] SPEAKER: It's like 512 kilobits or something like that.
[1:04:10] SPEAKER: Voice quality, you may be unsurprised to hear,
[1:04:14] SPEAKER: it sounds like there are multiple types of like subcategories
[1:04:16] SPEAKER: even within the voice over LTE.
[1:04:18] SPEAKER: - Shocking.
[1:04:19] SPEAKER: - The AMR WB plus codec has a wide bit range
[1:04:23] SPEAKER: from 5.2 to 48 kilobits.
[1:04:26] SPEAKER: Yeah, you're right, even 48 is pretty small.
[1:04:29] SPEAKER: - Yeah.
[1:04:29] SPEAKER: - Yes, offers a wide range of bit rates
[1:04:31] SPEAKER: from 5.9 kilobits to 128.
[1:04:33] SPEAKER: 128 is like better, I guess.
[1:04:38] SPEAKER: - 128 is like, it's the quality we post the podcast at.
[1:04:43] SPEAKER: - Yeah, although, I mean, that's a different,
[1:04:45] SPEAKER: that's using an MP3.
[1:04:45] SPEAKER: - Different codec, yeah.
[1:04:46] SPEAKER: - The MP3, the quality is a function of both bit rate
[1:04:49] SPEAKER: and kind of general quality of the codec at encoding data.
[1:04:55] SPEAKER: Compressing it rather.
[1:04:56] SPEAKER: So we can't say for exactly, but anyway, that's a, oh.
[1:05:00] SPEAKER: - Yeah.
[1:05:01] SPEAKER: - It looks like Fraunhofer, remember them?
[1:05:03] SPEAKER: - Yeah, figures of the MP3.
[1:05:05] SPEAKER: - Yes, Fraunhofer, the creators of the MP3,
[1:05:07] SPEAKER: like notoriously, the people you had to pay money to
[1:05:11] SPEAKER: back in the day for an MP3 or MP2 player.
[1:05:14] SPEAKER: - Yep.
[1:05:15] SPEAKER: - Or, you know, the vanguard of codec licensing fees,
[1:05:20] SPEAKER: let's say.
[1:05:21] SPEAKER: Anyway, apparently they have been in the voiceover LTE game
[1:05:24] SPEAKER: because of course, anyway.
[1:05:28] SPEAKER: - But yeah, their thing hasn't taken off, so anyway.
[1:05:31] SPEAKER: - That's been the whole point of, like you said,
[1:05:34] SPEAKER: kind of voice calls over FaceTime or I mean everything,
[1:05:37] SPEAKER: WhatsApp.
[1:05:37] SPEAKER: - WhatsApp, Signal, yeah, all that.
[1:05:39] SPEAKER: - They all have built-in voice calls
[1:05:41] SPEAKER: that are higher quality.
[1:05:41] SPEAKER: I'm sure Google has similar stuff on Android
[1:05:45] SPEAKER: to Apple's FaceTime stuff.
[1:05:47] SPEAKER: - Yeah, I think so, yeah.
[1:05:49] SPEAKER: I mean, you use Signal or FaceTime or WhatsApp
[1:05:53] SPEAKER: is what most people do.
[1:05:55] SPEAKER: - What is, do you know what the,
[1:05:56] SPEAKER: what is the wifi calling option on iPhones?
[1:05:59] SPEAKER: Is that something, is that an Apple level feature
[1:06:01] SPEAKER: or is that a carrier, like general phone technology?
[1:06:04] SPEAKER: - That is the carrier delivering
[1:06:06] SPEAKER: your LTE calls over the wifi network.
[1:06:09] SPEAKER: It's basically bridging when you're at home,
[1:06:11] SPEAKER: it'll bridge off of their network and onto yours
[1:06:14] SPEAKER: so that you have better signal.
[1:06:15] SPEAKER: - So that's less, I've got it, got it.
[1:06:17] SPEAKER: So that's less about better phone call quality
[1:06:20] SPEAKER: and more about just better signal if,
[1:06:22] SPEAKER: if you're in a shitty cell signal area.
[1:06:25] SPEAKER: - Well, it lets you get SMS messages and phone calls
[1:06:28] SPEAKER: if you're off of their grid, which is nice.
[1:06:31] SPEAKER: - Okay, yeah, that's totally different, that makes sense.
[1:06:34] SPEAKER: Okay, last question.
[1:06:36] SPEAKER: - Yeah.
[1:06:37] SPEAKER: - I hope you have a good answer for this
[1:06:38] SPEAKER: 'cause this is, this is a complicated one from Zander.
[1:06:41] SPEAKER: - Oh, I thought it was the hair care one, poop.
[1:06:42] SPEAKER: - Oh, that one's easy, we'll save that one.
[1:06:44] SPEAKER: - Okay.
[1:06:46] SPEAKER: - Zander, I've been looking for some new home accessories,
[1:06:50] SPEAKER: lamps and arts, et cetera, and I'm having a hard time
[1:06:53] SPEAKER: figuring out what is just a drop shipper
[1:06:55] SPEAKER: reselling Alibaba items versus who are the originators
[1:06:59] SPEAKER: of a piece that got duped by manufacturers in China
[1:07:03] SPEAKER: versus what is just originally from Alibaba
[1:07:05] SPEAKER: or a dupe of a much more expensive item
[1:07:07] SPEAKER: that isn't made anymore.
[1:07:09] SPEAKER: I can find posts on Reddit for some items
[1:07:11] SPEAKER: that support all three positions.
[1:07:13] SPEAKER: What do you do to sort through dupes?
[1:07:15] SPEAKER: - This is, this is, I like to think of this
[1:07:18] SPEAKER: as the Etsy problem now.
[1:07:19] SPEAKER: - Okay, sure.
[1:07:20] SPEAKER: - Because Etsy started out as a place that like,
[1:07:23] SPEAKER: perhaps people would make one-offs and sell them
[1:07:25] SPEAKER: to people who are interested in buying cool art.
[1:07:28] SPEAKER: Like a small press expo, but on the internet.
[1:07:31] SPEAKER: And now it's just a bunch of Alibaba drop shippers
[1:07:33] SPEAKER: and a handful of original artists.
[1:07:35] SPEAKER: - Real quick, drop shipper, drop shipper is a middleman,
[1:07:38] SPEAKER: right, like to the earlier points,
[1:07:40] SPEAKER: like the drop shipper is somebody who basically orders
[1:07:42] SPEAKER: and resells stuff, is that correct?
[1:07:44] SPEAKER: - It depends, sometimes they're warehousing stuff,
[1:07:46] SPEAKER: like sometimes they're buying stuff and then reselling it,
[1:07:48] SPEAKER: but they are a middleman, yeah.
[1:07:50] SPEAKER: - Okay.
[1:07:52] SPEAKER: - I don't think middleman has a real hard definition,
[1:07:54] SPEAKER: but I can be wrong.
[1:07:55] SPEAKER: - But what I mean is a drop shipper is just somebody
[1:07:57] SPEAKER: who is facilitating the sale of something
[1:07:59] SPEAKER: somebody else made, right, like they're just like importing
[1:08:01] SPEAKER: and reselling.
[1:08:02] SPEAKER: - Yeah, but that's what Walmart does too.
[1:08:04] SPEAKER: - Well, yes, but I don't know, I mean that term
[1:08:06] SPEAKER: has become pretty commonly used, I feel like in this era,
[1:08:10] SPEAKER: but maybe it's something that's reserved
[1:08:11] SPEAKER: for like small individual sellers.
[1:08:14] SPEAKER: - Well, I think drop shipper specifically means somebody
[1:08:16] SPEAKER: who's like buying it and having it shipped direct
[1:08:19] SPEAKER: from Alibaba to the customer rather than like
[1:08:24] SPEAKER: going through a warehouse.
[1:08:25] SPEAKER: - Never taking physical possession of the item.
[1:08:27] SPEAKER: - Yeah, I think technically probably the Etsy folks
[1:08:30] SPEAKER: who do this are not necessarily doing that,
[1:08:32] SPEAKER: I think that they're probably buying like a run of stickers
[1:08:35] SPEAKER: or whatever and then getting them here
[1:08:37] SPEAKER: and then packaging them up and reshipping them
[1:08:39] SPEAKER: when they sell them on Etsy for a 10X markup.
[1:08:43] SPEAKER: But yeah, I don't know what a good,
[1:08:46] SPEAKER: like I look at the reviews, I don't buy stuff
[1:08:49] SPEAKER: that looks like it could have come from Alibaba on,
[1:08:51] SPEAKER: like if I'm gonna do, honestly, the easiest way to do it
[1:08:55] SPEAKER: is to go look at AliExpress and see if you can find
[1:08:57] SPEAKER: the same thing on AliExpress and then if that's the case,
[1:08:59] SPEAKER: then you know that's where it came from.
[1:09:01] SPEAKER: - Yeah.
[1:09:02] SPEAKER: - And then for stuff like furniture,
[1:09:04] SPEAKER: I buy either used local, like I watch Craigslist
[1:09:07] SPEAKER: or Facebook market or whatever or buy direct from Ikea
[1:09:11] SPEAKER: or whatever, you know, I'm not buying designer furniture
[1:09:14] SPEAKER: right now, I have a kid.
[1:09:18] SPEAKER: But the, like if I was, I would go to local places
[1:09:23] SPEAKER: that are reputable would be my guess.
[1:09:25] SPEAKER: - Yeah, that's the best advice I can give here.
[1:09:28] SPEAKER: I'm not buying a lot of like home goods and accessories
[1:09:31] SPEAKER: that would fit into this category,
[1:09:32] SPEAKER: but I guess I do run into this with electronics sometimes.
[1:09:35] SPEAKER: - Yeah, shoes too oddly.
[1:09:37] SPEAKER: - Yeah, like I talked about on the patron episode
[1:09:40] SPEAKER: that I think probably up by the time this posts,
[1:09:43] SPEAKER: I bought a very specific right angle USB cable.
[1:09:47] SPEAKER: - Yeah.
[1:09:48] SPEAKER: - It was a right angle USB B 3.0 cable,
[1:09:51] SPEAKER: like very, very specific, hard to find.
[1:09:55] SPEAKER: The first one I bought didn't work
[1:09:56] SPEAKER: and it has to be returned, but it's a piece of junk.
[1:09:59] SPEAKER: The reason I bring this up is there are sites out there
[1:10:01] SPEAKER: that specialize in weird specific cables like this.
[1:10:04] SPEAKER: Like I found one site that was selling
[1:10:06] SPEAKER: the exact kind of cable I need for $50.
[1:10:09] SPEAKER: And so there was one other one on Amazon I hadn't tried yet
[1:10:12] SPEAKER: besides the one that didn't work.
[1:10:14] SPEAKER: And I was literally like eyeballing the molding
[1:10:16] SPEAKER: around the cable where like the cable
[1:10:19] SPEAKER: meets the connector and stuff.
[1:10:20] SPEAKER: - Oh, to see if there was too much flange or whatever?
[1:10:22] SPEAKER: - Well, no, no, trying to see if that $50 cable
[1:10:24] SPEAKER: on that external site was actually the exact same cable
[1:10:28] SPEAKER: out of the same factory as the $10 one on Amazon
[1:10:31] SPEAKER: that I hadn't tried yet.
[1:10:32] SPEAKER: - Yeah.
[1:10:33] SPEAKER: - 'Cause I was trying to find a cable that worked,
[1:10:35] SPEAKER: but I didn't want to spend $50 on it
[1:10:37] SPEAKER: if it was actually just a huge markup
[1:10:39] SPEAKER: on the exact same cable I could have gotten
[1:10:41] SPEAKER: for a fifth of the price.
[1:10:42] SPEAKER: So like in some cases, I guess it's down
[1:10:45] SPEAKER: to just eyeballing like tiny details on the item
[1:10:47] SPEAKER: to see if it's actually the same thing you'd be getting
[1:10:50] SPEAKER: on AliExpress for way less.
[1:10:52] SPEAKER: - The other thing like for cables and electronics
[1:10:55] SPEAKER: and stuff like that, there's also like Grainger
[1:10:58] SPEAKER: and McMaster's car and like there's a bazillion
[1:11:01] SPEAKER: actual real places that sell good stuff that you can go to.
[1:11:07] SPEAKER: In my experience, the real problems are the ones
[1:11:10] SPEAKER: that allow third-party sellers.
[1:11:12] SPEAKER: So like Amazon and Newegg and Etsy and all of these,
[1:11:15] SPEAKER: and eBay, frankly, at this point,
[1:11:17] SPEAKER: which was all third-party sellers.
[1:11:19] SPEAKER: But you're not gonna get a bad,
[1:11:24] SPEAKER: you're not gonna get a knockoff if you order the thing
[1:11:26] SPEAKER: from McMaster's car, right?
[1:11:27] SPEAKER: - Yeah, yeah, but you're gonna pay for it.
[1:11:30] SPEAKER: - I mean, but don't pay for expedited shipping
[1:11:33] SPEAKER: is the lesson there.
[1:11:34] SPEAKER: 'Cause it's real, it's like $75 every time
[1:11:37] SPEAKER: I've done it by accident.
[1:11:38] SPEAKER: Anyway, I think this is as good a place as any.
[1:11:40] SPEAKER: Oh, do you wanna do one more?
[1:11:42] SPEAKER: Are we saving that one for next time?
[1:11:43] SPEAKER: - Yeah, let's do the haircare one real quick.
[1:11:45] SPEAKER: - Okay.
[1:11:47] SPEAKER: - Also from Ambush Penguin Charlie,
[1:11:48] SPEAKER: getting a twofer this month.
[1:11:50] SPEAKER: How much of your haircare and maintenance is done at home
[1:11:52] SPEAKER: versus at a barber or salon?
[1:11:54] SPEAKER: You have beard trimming folks for folks with equally long
[1:11:57] SPEAKER: beards that have grown longer than a wall can keep short?
[1:12:00] SPEAKER: What about long hair tips?
[1:12:01] SPEAKER: Always curious about other people's methods.
[1:12:03] SPEAKER: I recently started going to a haircut place again.
[1:12:06] SPEAKER: - Oh, wow.
[1:12:07] SPEAKER: - After asking my girlfriend to trim my hair
[1:12:10] SPEAKER: for most of the last five years,
[1:12:12] SPEAKER: when the pandemic started.
[1:12:14] SPEAKER: - Did you go to a barber or a salon?
[1:12:17] SPEAKER: - It is a neighborhood haircut place
[1:12:19] SPEAKER: that is a block and a half from here.
[1:12:21] SPEAKER: - Okay, that's pretty good.
[1:12:22] SPEAKER: - That has been here for like 30 years,
[1:12:23] SPEAKER: and I never even noticed it before.
[1:12:25] SPEAKER: - They're doing a nice job.
[1:12:26] SPEAKER: You look good.
[1:12:26] SPEAKER: - Well, thank you.
[1:12:27] SPEAKER: They charge $15 a haircut.
[1:12:29] SPEAKER: - I need to start coming to your place.
[1:12:30] SPEAKER: My guy's way more expensive than that.
[1:12:32] SPEAKER: - I give roughly double that
[1:12:34] SPEAKER: because that's still a third of what a haircut costs
[1:12:37] SPEAKER: around here.
[1:12:38] SPEAKER: - Yeah, I mean, 60 bucks is the cheapest
[1:12:39] SPEAKER: I've found one lately.
[1:12:41] SPEAKER: - Yes.
[1:12:43] SPEAKER: - So I do, I mean, I go to the haircut.
[1:12:46] SPEAKER: I get my haircut at the barber,
[1:12:48] SPEAKER: and then I occasionally will pay for a beard trim.
[1:12:51] SPEAKER: I used to do it more when they were 10 bucks
[1:12:53] SPEAKER: and now that it's $25, I'm less enthusiastic about it.
[1:12:58] SPEAKER: I have a nice set of wall trimmers
[1:13:02] SPEAKER: that I keep a guard on.
[1:13:04] SPEAKER: I put like a three guard on or a two guard on,
[1:13:06] SPEAKER: and I use, like I brush the beard when I need to trim it,
[1:13:11] SPEAKER: and I just freehand it real careful off the,
[1:13:16] SPEAKER: but I don't touch the guard to the skin, obviously.
[1:13:19] SPEAKER: I'm just shaping, it's like using hedge trimmers.
[1:13:22] SPEAKER: You got to kind of glide above.
[1:13:25] SPEAKER: - Do you ever think about just losing the beard?
[1:13:27] SPEAKER: - I have asked if that is an option,
[1:13:29] SPEAKER: and I've been told by my child who has never seen me
[1:13:32] SPEAKER: without a beard, except for in pictures,
[1:13:34] SPEAKER: that she would freak the fuck out, was the direct quote.
[1:13:37] SPEAKER: - I saw a viral post going around the other day
[1:13:40] SPEAKER: of, I did not see it before.
[1:13:42] SPEAKER: They did not include a before picture of a guy
[1:13:45] SPEAKER: who clearly has had a long beard for a long time,
[1:13:48] SPEAKER: but it was like, hey, we're picking up our child
[1:13:50] SPEAKER: from school, beard reveal kind of thing of like,
[1:13:53] SPEAKER: child gets in the backseat, dad turns around to say hi.
[1:13:56] SPEAKER: - That is not an okay way to do it, man.
[1:13:57] SPEAKER: - She straight up started crying.
[1:13:59] SPEAKER: - Yeah, I think my daughter is old enough now
[1:14:01] SPEAKER: that she wouldn't start crying,
[1:14:02] SPEAKER: but it would be disturbing for her.
[1:14:04] SPEAKER: - Yeah, sure. - And also I like the beard.
[1:14:05] SPEAKER: I don't know what my face looks like under there anymore.
[1:14:07] SPEAKER: It could be a nightmare.
[1:14:08] SPEAKER: - That was my real question is, do you like having it?
[1:14:10] SPEAKER: Because it is maintenance, like it is, you know,
[1:14:12] SPEAKER: I'm sure it presents some challenges
[1:14:14] SPEAKER: when you're eating soup and things like that.
[1:14:15] SPEAKER: - It's less maintenance than shaving every day was though,
[1:14:19] SPEAKER: and I have a signature look, I think now, I don't know.
[1:14:21] SPEAKER: Is it important to have a signature look
[1:14:23] SPEAKER: in our line of work? - Sure, sure, probably.
[1:14:25] SPEAKER: Do you ever think about like trimming it way down
[1:14:26] SPEAKER: to like kind of a close cropped again?
[1:14:29] SPEAKER: - I come up and down as this, I like it a little long
[1:14:31] SPEAKER: 'cause I like to, I wanna lengthen the face
[1:14:33] SPEAKER: just a little bit, you know, but yeah,
[1:14:39] SPEAKER: I've been, let's see, about six months ago,
[1:14:42] SPEAKER: I did the thing where I took like 10% off a week
[1:14:45] SPEAKER: for two or three weeks just to see if anybody noticed
[1:14:47] SPEAKER: and nobody noticed 'cause I did it slowly and gradually
[1:14:49] SPEAKER: and you know, it's fine.
[1:14:51] SPEAKER: Yeah, if it gets too long, it's a real pain in the butt
[1:14:54] SPEAKER: and then you have to start like,
[1:14:56] SPEAKER: yeah, you don't wanna find food in there.
[1:14:58] SPEAKER: - Yeah, also I guess, you know, once it grows out,
[1:15:00] SPEAKER: it's not a problem anymore.
[1:15:01] SPEAKER: Like I am perpetually, I hate the feeling of New Beard.
[1:15:05] SPEAKER: - Oh yeah, no. - It's all itchy and ugh.
[1:15:08] SPEAKER: - No, no, no, what's it, like it's soft now.
[1:15:11] SPEAKER: I put oil on it every day to keep it like soft and shiny
[1:15:16] SPEAKER: and yeah, it's like the maintenance is low most of the time.
[1:15:21] SPEAKER: It's like every week or every other week,
[1:15:23] SPEAKER: I give it a touch up trim and bring the sides in.
[1:15:26] SPEAKER: The problem, honestly, the problem is that most barbershops
[1:15:28] SPEAKER: now, when you ask for a beard trim, they're like,
[1:15:30] SPEAKER: well, what number do you want?
[1:15:31] SPEAKER: I'm like, I don't want one number.
[1:15:32] SPEAKER: I want shorter on the sides and on the bottom
[1:15:35] SPEAKER: 'cause like obviously it's a freaking long beard.
[1:15:38] SPEAKER: So then they wanna do like a scissor cut on it
[1:15:40] SPEAKER: and I'm like, I don't, I'll just do this myself, I got it.
[1:15:44] SPEAKER: - The hard part is the mustache 'cause like you gotta like,
[1:15:47] SPEAKER: you gotta, you can really mess yourself up
[1:15:50] SPEAKER: if you get into the mustache region the wrong way.
[1:15:52] SPEAKER: Nobody wants, and I can't pull off like an Amish beard
[1:15:55] SPEAKER: where it's just like no mustache, but the beard,
[1:15:57] SPEAKER: that's not, I don't think that's a good look for me.
[1:15:58] SPEAKER: - Like that's probably not gonna work.
[1:16:00] SPEAKER: - Yeah, on that note, I think we'll wrap it up
[1:16:02] SPEAKER: for this month, this week's episode.
[1:16:06] SPEAKER: Thanks to everybody who sent in questions.
[1:16:07] SPEAKER: As always, you can send them to techpod@content.town
[1:16:09] SPEAKER: or post them in the Question Seeking Answers channel
[1:16:11] SPEAKER: in the Discord if you're a member of the TechPod Patreon
[1:16:15] SPEAKER: and support the show.
[1:16:16] SPEAKER: If you do that, we appreciate you very much.
[1:16:17] SPEAKER: Thank you, thank you.
[1:16:20] SPEAKER: - Yes, we do.
[1:16:20] SPEAKER: - If you'd like to find out how you can support the show,
[1:16:23] SPEAKER: you can go to patreon.com/techpod
[1:16:26] SPEAKER: where for five bucks a month,
[1:16:27] SPEAKER: you get access to the Discord,
[1:16:29] SPEAKER: you get, it's full of beautiful nerds, just to be clear.
[1:16:32] SPEAKER: - It is. - Wonderful people.
[1:16:34] SPEAKER: - Yep.
[1:16:34] SPEAKER: - Talking about Linux and nerdy stuff and--
[1:16:37] SPEAKER: - Plenty of other stuff too.
[1:16:38] SPEAKER: - Like there's a bunch of other things like food,
[1:16:40] SPEAKER: the food channel has been popping off lately.
[1:16:42] SPEAKER: We're coming up on Thanksgiving,
[1:16:44] SPEAKER: which is like prime TechPod food channel season
[1:16:47] SPEAKER: as far as I'm concerned.
[1:16:48] SPEAKER: - Yeah, thriving video game discussion.
[1:16:50] SPEAKER: - Yeah. - Went old.
[1:16:51] SPEAKER: I've been spending a little time
[1:16:52] SPEAKER: in the old ass computers channel recently.
[1:16:54] SPEAKER: - Yeah.
[1:16:55] SPEAKER: - Some fun stuff going on in there.
[1:16:56] SPEAKER: Friend of the show, E, told me about something
[1:16:59] SPEAKER: called FujiNet the other day.
[1:17:00] SPEAKER: - Ooh.
[1:17:01] SPEAKER: - Which I think there's a hardware
[1:17:03] SPEAKER: and a software component to it.
[1:17:05] SPEAKER: And it's like specific to each old computer,
[1:17:07] SPEAKER: but it's basically an attempt to, okay,
[1:17:09] SPEAKER: FujiNet is a multi peripheral emulator
[1:17:11] SPEAKER: and wifi network device for vintage computers.
[1:17:13] SPEAKER: So it's like, oh, I saw something similar to this
[1:17:17] SPEAKER: for the NSX is how this conversation started,
[1:17:19] SPEAKER: which it was a cartridge for the NSX
[1:17:21] SPEAKER: that has wifi hardware and a network stack built into it.
[1:17:24] SPEAKER: It's basically like wifi support for old computers
[1:17:27] SPEAKER: that are a predate wifi by 30 years.
[1:17:29] SPEAKER: - Oh, that's cool.
[1:17:30] SPEAKER: - But it lets you, it basically lets you load old software
[1:17:33] SPEAKER: over a network to old computers.
[1:17:35] SPEAKER: - That sounds wonderful.
[1:17:36] SPEAKER: - I mean, this is, I'm looking right here, you know,
[1:17:38] SPEAKER: Apple II, Atari, Commodore, Tandy,
[1:17:41] SPEAKER: like all old computers are getting support for this
[1:17:43] SPEAKER: where you can basically load like games and other programs
[1:17:46] SPEAKER: from the internet over a little wifi plugin
[1:17:49] SPEAKER: that fools the old computer
[1:17:50] SPEAKER: into thinking it's something else.
[1:17:52] SPEAKER: - That sounds wonderful.
[1:17:53] SPEAKER: - A lot of neat stuff going on out there.
[1:17:55] SPEAKER: - Yeah, it's a good community of people.
[1:17:57] SPEAKER: You also get access to the Patreon exclusive episode.
[1:17:59] SPEAKER: This month, Brad and I just kind of rambled about,
[1:18:02] SPEAKER: well, Linux stuff and some other things
[1:18:03] SPEAKER: that we're working on.
[1:18:06] SPEAKER: You can do all that by going to patreon.com/techpod.
[1:18:09] SPEAKER: Again, it's patreon.com/techpod.
[1:18:11] SPEAKER: And if you're in your car, hey, just tell your phone,
[1:18:15] SPEAKER: hey, leave me a reminder to subscribe to the tech pod
[1:18:17] SPEAKER: when I get out of the car.
[1:18:19] SPEAKER: - Yep, the highest possible use of such technology.
[1:18:21] SPEAKER: - Yeah, exactly.
[1:18:23] SPEAKER: As always, thanks to everybody who supports the show.
[1:18:25] SPEAKER: We appreciate you.
[1:18:25] SPEAKER: We are listener supported.
[1:18:27] SPEAKER: But a special thank you goes out
[1:18:29] SPEAKER: to our executive producer tier patrons,
[1:18:31] SPEAKER: including James Kamik, David Allen, Twinkle Twinkie,
[1:18:35] SPEAKER: Bunny Money, Jordan Lippett, Andrew Slawski,
[1:18:38] SPEAKER: Infelicitous Rips, Jason Lee, and Pantheon,
[1:18:42] SPEAKER: makers of the HS3 high-speed 3D printer.
[1:18:45] SPEAKER: It's the end of the month, so we also want to do a shout out
[1:18:47] SPEAKER: to our associate producer tier supporters,
[1:18:49] SPEAKER: including Graham Banks, Thomas Shea, Chad Rita,
[1:18:53] SPEAKER: P-Tibbs, Steve Lin, Tom Fuller, Just Associate Wedge,
[1:18:58] SPEAKER: Arthur Gies, Nathan Phelps, Ben Tallman, Tom Hilton,
[1:19:03] SPEAKER: Andre M. Burke, P.E., Andrew Dicey Sholdice,
[1:19:08] SPEAKER: Alejandro Navarro, Matt Walker,
[1:19:10] SPEAKER: parentheses Walkman8080, close parentheses,
[1:19:13] SPEAKER: Sanjik Kumar, Felix Kramer, Kerp, Brutal Kerfuffle,
[1:19:18] SPEAKER: and Eric, thanks everybody so much.
[1:19:19] SPEAKER: We appreciate y'all.
[1:19:20] SPEAKER: - Yeah, we would not be here without you.
[1:19:22] SPEAKER: Thank you.
[1:19:23] SPEAKER: - No, we absolutely would not.
[1:19:24] SPEAKER: And that'll do it for us this week.
[1:19:26] SPEAKER: I hope everybody has a lovely week,
[1:19:27] SPEAKER: and we will see you next week
[1:19:30] SPEAKER: with another edition of the Tech Pod.
[1:19:31] SPEAKER: As always, please consider the environment
[1:19:33] SPEAKER: before printing this podcast.
[1:19:34] SPEAKER: Bye, everybody.
[1:19:35] SPEAKER: (upbeat music)
