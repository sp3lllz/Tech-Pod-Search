---
episode: 321
title: 311: The Fab Floor
date: 2025-11-02
guests: none
duration: 1:28:51
---

[00:00] SPEAKER: OK, apparently I need to use this cold open to defend my honor.
[00:04] SPEAKER: Oh, no, you're listening to the other podcast, aren't you?
[00:07] SPEAKER: From the vicious slander that apparently has been aired
[00:11] SPEAKER: on a competing Linux podcast.
[00:13] SPEAKER: Wait, what did Adam say?
[00:18] SPEAKER: I think it was more you.
[00:19] SPEAKER: What did I do?
[00:20] SPEAKER: The refined is not a bootloader conversation came up.
[00:23] SPEAKER: Oh, yeah, it doesn't matter.
[00:24] SPEAKER: And it does matter.
[00:26] SPEAKER: Nope, doesn't matter.
[00:27] SPEAKER: Here we are to talk about why it matters.
[00:29] SPEAKER: You brought this on yourself.
[00:30] SPEAKER: Here we go. Technically correct.
[00:32] SPEAKER: Oh, it's not. It is. Listen, OK.
[00:34] SPEAKER: All right. This is this is the diary's material potentially.
[00:37] SPEAKER: So, OK, I would keep it short.
[00:39] SPEAKER: I will just say, though, if you are getting to the point where you are manually
[00:42] SPEAKER: configuring your boot process, which you are clearly flirting with now.
[00:45] SPEAKER: Oh, no, you haven't listened to this week's episode yet.
[00:48] SPEAKER: Oh, OK. Did you abandon the.
[00:50] SPEAKER: No, I did it. It's done.
[00:52] SPEAKER: OK, well, then that's the only point I would make is that it's important
[00:55] SPEAKER: to know what each piece is doing and what is happening at each stage
[00:58] SPEAKER: of the boot process.
[00:59] SPEAKER: If you are going to manually configure things, you don't know what.
[01:02] SPEAKER: The reason I say refined is not a bootloader is because you still need a bootloader.
[01:06] SPEAKER: If you have refined, you still need a bootloader downstream of refined.
[01:09] SPEAKER: Yeah, it's a bootloader loader.
[01:10] SPEAKER: Yeah, OK. He calls it a boot manager.
[01:12] SPEAKER: I read I spent a lot of time on Rod's books.
[01:14] SPEAKER: I learned about it all.
[01:15] SPEAKER: Dude, you've been on Rod's books.
[01:17] SPEAKER: Now we can speak a common language.
[01:19] SPEAKER: I you're going to you're probably going to yell at your radio again this week
[01:22] SPEAKER: because I explained to Adam how a UEFI boots into the OS
[01:27] SPEAKER: to explain a problem he's been having.
[01:29] SPEAKER: And I know and I prefaced it by saying this is the gist, not an expert.
[01:36] SPEAKER: Uh huh. I know you're going to be yelling at your radio.
[01:39] SPEAKER: That's why I spent a lot of time on Rod's books and I have a fully functional
[01:42] SPEAKER: refined dot com with a manually configured bootload.
[01:46] SPEAKER: OK, now we can now we can speak the same language.
[01:48] SPEAKER: I don't know about that, but I still say bootloader loader.
[01:51] SPEAKER: That's fine. I think as long as you're differentiating.
[01:54] SPEAKER: But I mean, again, though, the real point there is if you're actually going
[01:57] SPEAKER: to manually write a refined dot com as you are now doing.
[02:00] SPEAKER: Yeah, you still have to point refined at a bootloader.
[02:03] SPEAKER: That's true. Refined can't run an operating system kernel.
[02:06] SPEAKER: It has to boot a bootloader that then launches an operating system kernel,
[02:09] SPEAKER: unless you may have noticed.
[02:12] SPEAKER: I don't know if you've gotten this far yet,
[02:13] SPEAKER: because this is how I'm doing my butter if a sub volume distro set up.
[02:17] SPEAKER: Refined can manually start the Linux kernel itself.
[02:20] SPEAKER: That's what I'm doing.
[02:21] SPEAKER: And you might be asking, well, where is the bootloader in that situation?
[02:25] SPEAKER: Is it refined? It's the Linux kernel.
[02:27] SPEAKER: Oh, right. Because it can boot itself if it speaks.
[02:30] SPEAKER: Yeah, I think that's fucking crazy.
[02:31] SPEAKER: And rad is it's called.
[02:33] SPEAKER: I think they call it like an EFI stub loader.
[02:35] SPEAKER: And it has to be it has to be compiled into the kernel.
[02:38] SPEAKER: Like it's possible that you have a kernel that does not support that
[02:40] SPEAKER: if they didn't compile it that way.
[02:41] SPEAKER: But yes, like the kernel, the kernel can be its own bootloader.
[02:45] SPEAKER: And that ties into this whole move toward.
[02:47] SPEAKER: I think they refer to it as unified kernel images. Yeah.
[02:50] SPEAKER: Now, which is another thing that's coming about, I feel like alongside
[02:54] SPEAKER: like immutable distros as a way of saying like, hey, here is a whole
[02:57] SPEAKER: and complete Linux OS that can't be fucked up, that I can't not ever boot.
[03:02] SPEAKER: Like if we just start using the kernel as its own bootloader,
[03:04] SPEAKER: then it probably fixes some reliability problems with the boot process.
[03:08] SPEAKER: It solves some problems.
[03:09] SPEAKER: Now, the real irony of this whole thing is that when I was setting up Linux
[03:13] SPEAKER: the first time, I chose refined because it was billed as the one
[03:17] SPEAKER: that would just auto configure itself.
[03:18] SPEAKER: It would look at all the BFI boot partitions and make you a list of them
[03:22] SPEAKER: with a graphical interface that looked halfway decent and scaled right
[03:25] SPEAKER: on laptops with high resolution screens. Sure.
[03:28] SPEAKER: And so I picked that one because it didn't require manual configuration.
[03:33] SPEAKER: And then the thing that I ended up having to create the manual
[03:37] SPEAKER: configuration for it, for creating snapper snapshots,
[03:41] SPEAKER: an interface for booting into an older snapper snapshot.
[03:45] SPEAKER: Turns out, if I just used grub, that would have been supported automatically
[03:48] SPEAKER: because it's the default.
[03:49] SPEAKER: Ha ha. So, you know, I kind of was hoisted by my own Picard here.
[03:53] SPEAKER: Yeah. Yep. Yep.
[03:54] SPEAKER: I know the feeling. I know the feeling.
[04:18] SPEAKER: Welcome to Brad and Will Made a Tech Pod. I'm Will.
[04:28] SPEAKER: I'm Brad. Yeah, Picard's.
[04:31] SPEAKER: We have a we have a banger of an episode for you here this week.
[04:36] SPEAKER: Yes. And Linux is not really mentioned even once, as far as I remember.
[04:40] SPEAKER: So you're in luck.
[04:41] SPEAKER: You mentioned it when we talked about thread directing.
[04:43] SPEAKER: Oh, well, barely. Yeah.
[04:45] SPEAKER: But a couple of weeks ago, I got to go down
[04:48] SPEAKER: to Chandler, Arizona, to Intel's fab 53,
[04:54] SPEAKER: where the new 18A process is being made and learn all about the first chip
[04:58] SPEAKER: to roll out with that, which is called Panther Lake.
[05:00] SPEAKER: And I went there with my friend and colleague from PC World, Adam Patrick
[05:05] SPEAKER: Murray, to talk about to to learn about this stuff.
[05:09] SPEAKER: So Adam, we managed to get Adam in here for a return visit on the show.
[05:11] SPEAKER: I think this is, I don't know, nth visit to the tech pod.
[05:15] SPEAKER: Welcome to the show, Adam Patrick Murray.
[05:17] SPEAKER: Let's talk about Intel's Panther Lake.
[05:20] SPEAKER: I'm back doing weird voices today, I guess.
[05:23] SPEAKER: Glad to get you guys on a podcast together.
[05:25] SPEAKER: Finally. Yeah, Will, it's great meeting you, Brad.
[05:28] SPEAKER: Long time no see.
[05:29] SPEAKER: I heard you needed a Linux expert, so I'm glad you brought me on.
[05:33] SPEAKER: Glad you workshop that one a few minutes ago and compiled any good journals lately.
[05:38] SPEAKER: Oh, yeah, I'm doing a left and right.
[05:40] SPEAKER: That's just what I do.
[05:42] SPEAKER: It's my thing.
[05:42] SPEAKER: Look at Adam's favorite thing in the world is installing new Linux distros.
[05:45] SPEAKER: It turns out he just he just can't stop.
[05:48] SPEAKER: I literally did it twice today already.
[05:51] SPEAKER: Great. What do you got on deck?
[05:53] SPEAKER: I need to know who to go to.
[05:55] SPEAKER: Yeah. All right.
[05:57] SPEAKER: Also, we have an upcoming video on on PC World's YouTube channel
[06:01] SPEAKER: about the bee box, and I was reminded that that haiku OS is out there.
[06:06] SPEAKER: And I was like, you know what? Maybe I should try that one as well.
[06:08] SPEAKER: Yeah, do you forget forget the Linux podcasts?
[06:11] SPEAKER: When are we going to get the haiku podcast?
[06:13] SPEAKER: That's season two, man.
[06:14] SPEAKER: Season two of The Dual Boot Diaries, haiku and Linux.
[06:17] SPEAKER: You know, trust me, trust me.
[06:18] SPEAKER: I had strong feelings about your conversation about, hey,
[06:20] SPEAKER: which OS will we go to from here?
[06:22] SPEAKER: Yeah. Look, what was the new contender?
[06:25] SPEAKER: Somebody sent in the one that's all virtualized.
[06:28] SPEAKER: Do you remember? Oh, EXVM.
[06:32] SPEAKER: I don't know. That's a that's a show about ESXI.
[06:36] SPEAKER: Yes, I was the VMware thing.
[06:40] SPEAKER: No, man, I can't remember what it was called.
[06:42] SPEAKER: It was the thing that somebody sent into the letters episode last week.
[06:46] SPEAKER: And when I looked at it, it was like everything's running in a virtualized container.
[06:50] SPEAKER: Oh, oh, yeah.
[06:51] SPEAKER: The EXWM is the the emacs where it's like it's all just emacs.
[06:56] SPEAKER: Yeah, the whole desktop manager is emacs.
[06:59] SPEAKER: The whole operating system running emacs that, yeah, OK, that checks out.
[07:02] SPEAKER: Anyway, but anyway, yeah, we're here we're here today to talk about Intel.
[07:06] SPEAKER: Adam and I went Intel Intel brought us to Arizona
[07:11] SPEAKER: a couple of weeks ago to see the their new fab
[07:14] SPEAKER: and to find out what's coming up with their next gen mobile and data center processors.
[07:18] SPEAKER: And like spoiler alert, we skipped the data center processor bit
[07:21] SPEAKER: and went to the fab and learned about laptops and then,
[07:25] SPEAKER: you know, did other stuff the data center day because we're fine there.
[07:29] SPEAKER: Yeah, hands are like, I guess that's probably appropriate for your audiences.
[07:33] SPEAKER: I mean, is that Xeon still is that is that or the dance?
[07:37] SPEAKER: All right. That's like Clearwater Lake or whatever.
[07:39] SPEAKER: Right. Clear Forest is Clearwater Forest.
[07:42] SPEAKER: It's all it's all code name stuff right now.
[07:43] SPEAKER: Yeah. Clearwater Forest is data center.
[07:45] SPEAKER: And it's like for the kind of CPUs that that it seemed like the kind of CPUs
[07:50] SPEAKER: that Nvidia did the deal to get access to in their inference machines
[07:53] SPEAKER: that they're using to train new models with.
[07:56] SPEAKER: But but like I said, I went to the first like 30 minutes of that session.
[07:59] SPEAKER: I was like, we're never going to talk about this in a professional context.
[08:01] SPEAKER: I went did something useful. That's not consumer stuff.
[08:04] SPEAKER: But yeah, you did see consumer stuff.
[08:06] SPEAKER: We did. We talk about that.
[08:07] SPEAKER: Can we talk about the junket real fast before we get to the CPUs?
[08:10] SPEAKER: Yeah. Yeah. They don't call it a junket.
[08:13] SPEAKER: As somebody who has been on endless numbers of video game
[08:16] SPEAKER: junkets over the last 20 years, although not so much these days. Yeah.
[08:20] SPEAKER: Like what is a CPU press trip like?
[08:24] SPEAKER: It probably smells the same.
[08:26] SPEAKER: OK, the game. Yeah, I'm just kidding.
[08:28] SPEAKER: No, they're sure everyone has smelled great. Yeah.
[08:32] SPEAKER: Well, this one, I would say specifically,
[08:35] SPEAKER: a lot of the junkets around like technology deep dives like this are
[08:41] SPEAKER: are around trade shows, right?
[08:44] SPEAKER: So CS, Computex, things like that. So.
[08:48] SPEAKER: The best case scenario is something like this where you can have time dedicated.
[08:53] SPEAKER: You don't want too much time.
[08:54] SPEAKER: I feel like this one actually went on a little longer than needed to.
[08:57] SPEAKER: But for the most part, you want time to just sit there
[09:01] SPEAKER: and absorb and get to chat with people, not only from the company
[09:05] SPEAKER: that you're visiting, but also other press and analysts around.
[09:09] SPEAKER: So this one, like when we're at trade shows,
[09:12] SPEAKER: there's a whole mixture of analysts, press influencers,
[09:17] SPEAKER: the whole the whole gamut.
[09:19] SPEAKER: At this one, there was a lot of analysts,
[09:22] SPEAKER: a lot of press, but more traditional press, I will say.
[09:25] SPEAKER: And then there were only a couple that I would consider influencers.
[09:31] SPEAKER: So it was it was a lot more.
[09:34] SPEAKER: I mean, I was there, man.
[09:35] SPEAKER: Classic. Yeah. Oh, yeah. I'm sorry.
[09:36] SPEAKER: Yeah. Will will the influencer.
[09:38] SPEAKER: I was the biggest influencer there.
[09:40] SPEAKER: Pretty, pretty serious.
[09:41] SPEAKER: OK. Did did they at any point try to put you in a helicopter or perhaps a dune buggy?
[09:47] SPEAKER: No, they put it. They let's go inside the fab.
[09:49] SPEAKER: OK. All right.
[09:50] SPEAKER: Then this is different than a lot of video game press strips.
[09:54] SPEAKER: The other big difference between most of the video game stuff I was exposed to
[09:58] SPEAKER: at Maximum PC and later on is that they also brought the actual people
[10:03] SPEAKER: that do stuff here.
[10:05] SPEAKER: So like most of the video game stuff, you'd have the people
[10:07] SPEAKER: who were trained to talk about the video game, and that was maybe it.
[10:10] SPEAKER: And there'd be people like that.
[10:12] SPEAKER: You'd be talking to somebody.
[10:13] SPEAKER: You'd be like, oh, yeah, I designed all the combat for the multi
[10:15] SPEAKER: for this multiplayer mode when they were doing the demos.
[10:18] SPEAKER: But they didn't like make those people readily available for you to talk to.
[10:22] SPEAKER: And like at this, we sat down with with Tom Peterson Tap.
[10:26] SPEAKER: Talked about GPUs.
[10:27] SPEAKER: He was just walking around and like hanging out.
[10:29] SPEAKER: We could sit down with him at dinner.
[10:30] SPEAKER: Stephen Robinson, who's in charge of X86, was there.
[10:34] SPEAKER: And we could talk to him about X86 architecture stuff like the smart people.
[10:40] SPEAKER: Yeah. Tap like essentially spearheaded G-Sync.
[10:44] SPEAKER: The whole G-Sync initiative at Nvidia.
[10:46] SPEAKER: This the the X86 architect guy.
[10:49] SPEAKER: I mean, he was a nice guy.
[10:50] SPEAKER: He just looked like a normal guy.
[10:52] SPEAKER: You know, he's like, oh, OK, cool.
[10:54] SPEAKER: We're just hanging out.
[10:54] SPEAKER: I was like, what? What hot new instructions are coming down the pike?
[10:57] SPEAKER: He's like, we're not talking about forward looking products right here.
[10:59] SPEAKER: But we talked to the person who the
[11:03] SPEAKER: both Stephen and Tap and Rajshree Chabuskar,
[11:08] SPEAKER: who is the they're all Intel fellows, which is like
[11:13] SPEAKER: I think when Tap was on the the full nerd a few weeks ago,
[11:15] SPEAKER: he described it as the person who's able to kind of cut through the
[11:18] SPEAKER: the the kind of the back and forth arguing that engineers like to do by saying,
[11:23] SPEAKER: you know, I think that this is probably the right way to go.
[11:25] SPEAKER: So they have a little bit more weight.
[11:26] SPEAKER: But like Rajshree is in charge of thread director. Right.
[11:30] SPEAKER: The thing that determines what goes on PCOR is what goes on e-cores
[11:33] SPEAKER: and how they like how that communicates with the OS's.
[11:36] SPEAKER: And so we were able to have much deeper conversations
[11:40] SPEAKER: about how things actually work with the people who really know
[11:43] SPEAKER: instead of being filtered through the PR and marketing team,
[11:46] SPEAKER: which is like those people are great, but.
[11:49] SPEAKER: They they don't have the same level of knowledge as.
[11:53] SPEAKER: Hey, I'm in charge of X86 right now.
[11:55] SPEAKER: Yeah, I mean, especially with such an intensely technical subject.
[11:58] SPEAKER: Yeah, like I was I was over my head talking to Stephen just to be like, I
[12:02] SPEAKER: was like, I'm really excited to talk to you.
[12:05] SPEAKER: I have no idea what to ask because like this is a level of how this works
[12:08] SPEAKER: that goes beyond what I've ever really cared about.
[12:11] SPEAKER: I didn't say it that way, but like that's the reality.
[12:14] SPEAKER: Well, also, like I would say,
[12:16] SPEAKER: you know, you're looking for like extracurricular activities.
[12:20] SPEAKER: I think this one, because of the tours through the fab,
[12:23] SPEAKER: like they were going literally for three days straight, almost four days.
[12:27] SPEAKER: What? Oh, four. Yeah.
[12:29] SPEAKER: And like 10 hours a day or 12 hours. I can't remember exactly.
[12:32] SPEAKER: So like, I think they were so busy coordinating all that stuff
[12:36] SPEAKER: that they just didn't worry too much about the other stuff.
[12:39] SPEAKER: That's fine. I mean, I'm mostly joking.
[12:41] SPEAKER: To be clear, we usually skipped the extracurricular activities
[12:44] SPEAKER: because we had to work. But yeah, well, I'll say the Ryzen 7000 launch,
[12:49] SPEAKER: which was like the first junket that Gordon and I went to
[12:52] SPEAKER: after a gourd mong, the late gourd mong.
[12:56] SPEAKER: We went to it like kind of post pandemic.
[12:58] SPEAKER: It was like the first one of those.
[13:00] SPEAKER: And it was at a resort in outside of Austin, Texas.
[13:05] SPEAKER: And they did have like an ax throwing time that you can go through some axes,
[13:09] SPEAKER: you know, things like that sounds like the classic junket.
[13:12] SPEAKER: So those exist still.
[13:14] SPEAKER: And like the meals and stuff,
[13:17] SPEAKER: it was all just catered by the hotel and was just like it was nice hotel food,
[13:22] SPEAKER: but it wasn't anything super like it was hot, hot table buffet
[13:26] SPEAKER: style everywhere we went and like cold sandwich boxes and stuff.
[13:30] SPEAKER: Like it was the kind of stuff you get it
[13:31] SPEAKER: like it was better than when you get a convention center
[13:34] SPEAKER: in like the meeting room or something like that, but not like not fancy.
[13:39] SPEAKER: Yeah, that sounds reasonable.
[13:41] SPEAKER: They did have hold on. They did. This is really important.
[13:43] SPEAKER: They did have miniature horses delivering beer one night.
[13:46] SPEAKER: What? Yes. Oh, yeah.
[13:49] SPEAKER: This was during that is the evening dinner time. Yeah.
[13:54] SPEAKER: Yeah. So the minute the miniature horses were taco and Corona were their names
[13:58] SPEAKER: and they had like coolers on either side of their back
[14:01] SPEAKER: that were kind of balanced against each other with like a little napkin
[14:04] SPEAKER: holder and an umbrella and limes.
[14:06] SPEAKER: And then they have tiny sombreros into servitude.
[14:10] SPEAKER: I mean, look, what are who am I to say
[14:13] SPEAKER: that we shouldn't take control of the natural world, Brad?
[14:16] SPEAKER: That is more bacchanalian than anything I ever saw on a video game trip.
[14:19] SPEAKER: I got to I petted Corona and I gave him a snack and he was we're best friends now.
[14:25] SPEAKER: So I'm over here and he's besmirching of taco or Corona.
[14:28] SPEAKER: The rate that same evening, they also had a couple of people set up
[14:31] SPEAKER: doing leather work so you could make your own leather suitcase badge.
[14:36] SPEAKER: OK, all right. Yeah. So, yeah.
[14:39] SPEAKER: All right. Well, we're here to talk about CPU.
[14:41] SPEAKER: So, yeah, see, you got to use central processing units.
[14:45] SPEAKER: Well, actually, there it's it's not just the CPU.
[14:47] SPEAKER: There's APS or I'm sorry, GPUs, NPs.
[14:51] SPEAKER: All of the P's were talked about.
[14:53] SPEAKER: Well, the big thing is that like this is weird.
[14:57] SPEAKER: This is now like the kind of like the second full generation
[15:01] SPEAKER: of Intel's disaggregated design.
[15:03] SPEAKER: So Lunar Lake and Arrow Lake and Meteor Lake,
[15:06] SPEAKER: which are kind of different paths down the same trail,
[15:10] SPEAKER: all have triplets in the same way that the Ryzans have had for a long time.
[15:14] SPEAKER: And they were talking about what they learned.
[15:17] SPEAKER: The big thing about Panther Lake is it's the first thing on Intel's 18A process,
[15:21] SPEAKER: which is their like next generation cutting edge fab process.
[15:28] SPEAKER: Like intended to be a TSMC competitor, right?
[15:30] SPEAKER: I mean, I'm sure that's what they would like to say.
[15:32] SPEAKER: But is that does that seem realistic?
[15:35] SPEAKER: Well, yeah, I mean, they they they were very clear the whole time being like,
[15:40] SPEAKER: we believe this is the most advanced process in the world.
[15:44] SPEAKER: And it's produced right here in the great US of A.
[15:48] SPEAKER: Interesting. They were they were hammering that home.
[15:51] SPEAKER: So and not to mention the previous CEO
[15:55] SPEAKER: was kind of the the spearhead of this this whole effort.
[15:59] SPEAKER: So he doesn't get to see the fruits of of this labor.
[16:02] SPEAKER: I mean, who knows how long 18A was actually in development?
[16:05] SPEAKER: Maybe it was way beyond
[16:07] SPEAKER: Pat's time. But yeah. Yeah.
[16:10] SPEAKER: So, OK, so the big stuff on Panther Lake, it's like I said, it's a
[16:14] SPEAKER: it's a heterogeneous there's multiple processes.
[16:17] SPEAKER: They're almost all Intel processes, except for a couple of the GPU core
[16:22] SPEAKER: options are TSMC, all of the GPU.
[16:27] SPEAKER: Oh, I thought the four was an Intel one. OK.
[16:33] SPEAKER: But yeah, so there's basically the cores are the tiles on this core
[16:36] SPEAKER: and they're calling these S.O.C.s still.
[16:38] SPEAKER: But it doesn't stand for system on a chip anymore.
[16:42] SPEAKER: That was its system of chips now is what they're calling.
[16:45] SPEAKER: Yeah, I'm sorry. What?
[16:46] SPEAKER: Yeah, it was a growing audience when that one went out. Yeah. Yeah.
[16:52] SPEAKER: But but the main.
[16:53] SPEAKER: OK, so the big stuff that's changed, smaller transistor size,
[16:57] SPEAKER: the nanometer scale of the transistors seems to be getting kind of wobbly
[17:01] SPEAKER: and in a way that you report the number because everybody's.
[17:06] SPEAKER: Like it seems like maybe that's not going down anymore.
[17:08] SPEAKER: Now we're doing new stuff to make the machines run more
[17:12] SPEAKER: better at lower temperatures and voltages.
[17:15] SPEAKER: The big jump here is it seems like they're moving beyond
[17:20] SPEAKER: FinFET gates, which was the thing that rolled out about 10 years ago.
[17:24] SPEAKER: And that was so if you think about the way a transistor gate works,
[17:28] SPEAKER: there's a conductor that goes through something and then there's a
[17:31] SPEAKER: gate around it that prevents that signal for me.
[17:34] SPEAKER: It either stops the signal from going through or lets the signal go through.
[17:37] SPEAKER: And FinFET is called a FinFET because the conductor that goes through
[17:41] SPEAKER: was a vertical like vertical poking out of the semiconductor base. Right.
[17:46] SPEAKER: So it generally is pretty good.
[17:49] SPEAKER: But if you put too much voltage through, there'd be leakage
[17:51] SPEAKER: around the edges of the gate,
[17:52] SPEAKER: around the edges of the conductor that don't go through the gate. Right.
[17:56] SPEAKER: What they're doing now is they're lifting that that conductor out of the stratum
[18:01] SPEAKER: and making the gate a three dimensional loop around the conductor.
[18:06] SPEAKER: And at that point, it's that's why they call it ribbon fed because it goes
[18:09] SPEAKER: the conductor is completely encircled by gate now.
[18:13] SPEAKER: So they're there.
[18:14] SPEAKER: What they're saying is there's a lot less leakage or maybe no leakage.
[18:17] SPEAKER: That part was kind of unclear.
[18:19] SPEAKER: They didn't give they were there as a general rule.
[18:22] SPEAKER: We should we should start this out.
[18:24] SPEAKER: They wouldn't talk about yields at all,
[18:25] SPEAKER: no matter how we tried to trick them into asking answering those questions.
[18:29] SPEAKER: Well, it's still early, right?
[18:31] SPEAKER: I mean, they announced full production. Yeah, they announced full production.
[18:35] SPEAKER: Oh, they are. OK, it's not early.
[18:38] SPEAKER: Well, the rubber has met the road then the day that we were there,
[18:42] SPEAKER: like they maybe four days before we were there,
[18:45] SPEAKER: they announced that the fab was fully operational on October 9th.
[18:48] SPEAKER: So it's like like we were not.
[18:52] SPEAKER: It is still early in production.
[18:53] SPEAKER: And as they said, they're still ramping production.
[18:56] SPEAKER: Like we when we were on the fab tour, we'll talk about this later.
[18:59] SPEAKER: There were places where there were holes, where it was very clear
[19:01] SPEAKER: that there were going to be some really expensive machines
[19:03] SPEAKER: that just haven't been delivered or installed yet. I see.
[19:07] SPEAKER: And I can I I want to digress too much here.
[19:10] SPEAKER: This is like the most basic like transistor one on one stuff.
[19:12] SPEAKER: But do you know what the mechanism of action is
[19:15] SPEAKER: that causes the gate to interrupt signal through the transistor?
[19:20] SPEAKER: I mean, it's not obviously it's not mechanical at a nanometer scale.
[19:24] SPEAKER: Like what do you know?
[19:25] SPEAKER: Do you know what what is what is what is the operation there
[19:27] SPEAKER: that is interrupting the electrical current going through or not?
[19:31] SPEAKER: Yeah. When when basically there's signals
[19:35] SPEAKER: that go into the transistor base that apply into the gate,
[19:39] SPEAKER: into the base of the gate that make it more or less
[19:43] SPEAKER: electrically conductive based on how much electricity goes into it. Got it.
[19:47] SPEAKER: So if there's current at the base that it's open and if there's not,
[19:50] SPEAKER: then it's closed. OK.
[19:52] SPEAKER: And that's the extent of my knowledge on how this works.
[19:55] SPEAKER: OK, good enough.
[19:57] SPEAKER: Please don't ask follow up questions.
[19:59] SPEAKER: Next question. Yeah. So.
[20:04] SPEAKER: The next thing is the power of is
[20:07] SPEAKER: so the way that the power comes into the way
[20:10] SPEAKER: for the things that turn those gates open and closed.
[20:13] SPEAKER: And those are kind of buses, is my understanding, kind of like a
[20:17] SPEAKER: in the in the sense of like a system bus like that, like the power comes in on lanes
[20:21] SPEAKER: and then they can open or closed based on state of the chip.
[20:24] SPEAKER: What's being used to not is that those have come in on the front side
[20:29] SPEAKER: for all eternity.
[20:31] SPEAKER: And now they're making those poke through the chip
[20:34] SPEAKER: and coming in from the backside now, which will improve cooling
[20:38] SPEAKER: and reduce power loss reduction and basically allow them for scaling
[20:43] SPEAKER: to scale more power into the chip, which gives them better performance.
[20:48] SPEAKER: And they specifically like they wouldn't talk about performance.
[20:51] SPEAKER: They wouldn't talk about yields at all, really, other than to give
[20:54] SPEAKER: really general numbers like it's 15 percent performance
[20:58] SPEAKER: per watt improvement between 18 a and Intel three, which means nothing. Right.
[21:04] SPEAKER: In what? Yeah.
[21:05] SPEAKER: But performance per watt, Adam, performance per watt.
[21:10] SPEAKER: And then, like many of the talks, this this whole talk about
[21:13] SPEAKER: what fundamentally has changed at the low level with this process was
[21:17] SPEAKER: this is the most advanced semiconductor facility in the world.
[21:20] SPEAKER: Like they said that three or four times throughout the throughout
[21:23] SPEAKER: these presentations.
[21:24] SPEAKER: I mean, do you think, OK, this is a very big question
[21:27] SPEAKER: that they certainly would not have addressed?
[21:28] SPEAKER: I mean, are we going to see iPhones?
[21:30] SPEAKER: You know, we're going to see like the A20 or whatever the next.
[21:33] SPEAKER: I mean, maybe not the next one, but like three iPhones from now.
[21:36] SPEAKER: Is Apple going to be fabbing SOCs in this place?
[21:39] SPEAKER: Adam's making a face.
[21:41] SPEAKER: Yeah. I mean, I'm sure Intel would love
[21:44] SPEAKER: to expand their partnership to work with Apple.
[21:48] SPEAKER: So I think that's going to happen.
[21:51] SPEAKER: You know, I mean, we will see.
[21:53] SPEAKER: They showed an arm chip that they built on 18 a
[21:58] SPEAKER: the my understanding is that the big
[22:01] SPEAKER: the big thing keeping Intel,
[22:05] SPEAKER: Intel fabs, Intel foundry fabs accessible only to Intel as a customer
[22:10] SPEAKER: is that the rest of the world uses a certain kind of tool chain
[22:14] SPEAKER: and process to design chips and Intel uses their own thing.
[22:18] SPEAKER: This is I talked to Dr.
[22:21] SPEAKER: Ian Cutrus, who is tech tech potato on YouTube about this a few weeks ago,
[22:25] SPEAKER: a few months ago now, I guess, or last year even.
[22:28] SPEAKER: And his his answer is that
[22:32] SPEAKER: Intel does something, does this one way.
[22:34] SPEAKER: Everybody else does it the other way.
[22:36] SPEAKER: Part of the reason that Intel has been building chips on TSMC
[22:40] SPEAKER: beyond the fact that they didn't have competitive processes for those chips
[22:44] SPEAKER: is that they needed to build that internal knowledge
[22:48] SPEAKER: so that these U.S. fabs can be competitive with the TSMC fabs in Taiwan.
[22:54] SPEAKER: And whether they're successful at that, we're not going to know for a while.
[22:59] SPEAKER: So, yeah, I don't know part.
[23:01] SPEAKER: The other part of it, though, that's interesting is because of the way
[23:03] SPEAKER: the packaging works on these chips with the foveros and all that stuff.
[23:07] SPEAKER: Like there's nothing to say that Nvidia can't make a chiplet
[23:10] SPEAKER: at TSMC in Taiwan, ship it to Chandler to be assembled
[23:14] SPEAKER: and put that on with Intel 18 a CPU dies and other stuff, right?
[23:21] SPEAKER: I mean, yeah, after after that announcement of the partnership with Intel
[23:24] SPEAKER: and Nvidia working together in some capacity, which it's still too early.
[23:29] SPEAKER: They keep telling us this is just the announcement, the intent to work together.
[23:33] SPEAKER: We probably won't see anything for years.
[23:36] SPEAKER: Yeah, I think it's the packaging part that Nvidia is very keen on,
[23:41] SPEAKER: that this foveros technology is is probably
[23:45] SPEAKER: where Intel is going to be able to to hang their hat on.
[23:48] SPEAKER: Should we talk about that, like what I've heard the term foveros
[23:51] SPEAKER: a million times, and I still don't quite know what it is.
[23:54] SPEAKER: So foveros is the is the kind of glue that holds all these chips together.
[23:58] SPEAKER: OK, it's it's it's a it's a general interconnect material
[24:05] SPEAKER: that has varying bump pictures for the connection points for the chiplets.
[24:11] SPEAKER: And they talked about, like, for example, the data center
[24:14] SPEAKER: parts have a different density than the than the consumer parts,
[24:16] SPEAKER: just because they want way more chip to chip chiplet to chiplet interconnection
[24:21] SPEAKER: and communication than you get, than you need on the on the
[24:24] SPEAKER: on the mobile parts where there's only basically one compute tile.
[24:29] SPEAKER: So foveros S, I think
[24:33] SPEAKER: is the 36 micron bump pitch
[24:37] SPEAKER: that's on the current chipping parts.
[24:41] SPEAKER: The that's going to go to 10 microns now.
[24:45] SPEAKER: So seven hundred and seventy two to sixteen hundred bumps per millimeter
[24:49] SPEAKER: millimeter squared to 10 K bumps per millimeter squared.
[24:55] SPEAKER: And then Clearwater Forest is going to be nine microns on that pitch.
[25:00] SPEAKER: And what that basically means is how many connections each chiplet can have.
[25:03] SPEAKER: So that's the gate of that's the gate for chiplet to chiplet communication.
[25:09] SPEAKER: They also did a bunch of other stuff that we should talk about.
[25:10] SPEAKER: Like we should talk about
[25:13] SPEAKER: the the S.O.C. chip, the one that has all the IO
[25:16] SPEAKER: and all the other stuff on it that makes the CPU work.
[25:18] SPEAKER: That isn't an 18A chip.
[25:20] SPEAKER: So there's the 18A chip.
[25:22] SPEAKER: There's the S.O.C. chip, which is like all the chip housekeeping
[25:26] SPEAKER: memory controllers and that kind of stuff, as well as sometimes some e-cores.
[25:29] SPEAKER: And then there's compute die and GPU die.
[25:34] SPEAKER: Before we move on, like interconnect is actually like one of the main things
[25:38] SPEAKER: I wanted to talk to you guys about, because like that's been one of the big
[25:40] SPEAKER: weaknesses on the horizon for so long since since they went to Chiplets.
[25:44] SPEAKER: Right. Like it's the relatively slow infinity fabric between Chiplets
[25:48] SPEAKER: is kind of the big problem when you get it's the whole reason we are still living
[25:51] SPEAKER: with core parking, right?
[25:53] SPEAKER: Because when you get a process running on one die, trying to hit the cache
[25:56] SPEAKER: on the other die or whatever it is like talking between those two chips,
[26:00] SPEAKER: Chiplets is relatively slow enough to cause hitching and games
[26:04] SPEAKER: and other issues like that.
[26:05] SPEAKER: Like, did you get any sense if if like the Foveros tech
[26:09] SPEAKER: will alleviate that issue or won't face that issue to the same degree?
[26:13] SPEAKER: I mean, were they talking in such real world terms about things like that?
[26:17] SPEAKER: I asked about that when I was talking to Stephen.
[26:20] SPEAKER: Did you ask at all?
[26:22] SPEAKER: No, I didn't talk too much about that.
[26:25] SPEAKER: So the answer, they wouldn't give a clear answer on that
[26:28] SPEAKER: because they're not doing consumer multi chip
[26:33] SPEAKER: multi compute chip products at this point.
[26:35] SPEAKER: None of those were on the announce like everything that's being announced
[26:39] SPEAKER: like there were like I said, there was an eight core, a 16 core
[26:42] SPEAKER: and a 16 core with a big GPU model all talked about.
[26:46] SPEAKER: OK, now all of those are one compute tile.
[26:51] SPEAKER: Right. Like Arrow Lake is all single compute tile.
[26:54] SPEAKER: I think that the rumors I mean, this is this is getting further down the road,
[26:57] SPEAKER: like the rumors swirling about Nova Lake
[26:59] SPEAKER: or that they are going to start shipping to compute tile designs.
[27:02] SPEAKER: But that's I mean, that's 18 years away now.
[27:06] SPEAKER: Yeah, it's actually not fully accurate because the the main tile
[27:09] SPEAKER: that has the IO and stuff like that has low power e-cores
[27:13] SPEAKER: where that you can expand the bigger 16 core option actually adds
[27:18] SPEAKER: a whole nother section with with other processor cores, e-cores on it.
[27:23] SPEAKER: So I'm getting out over my skis here now.
[27:26] SPEAKER: I've read that like those LPE cores are not on the ring bus,
[27:29] SPEAKER: but I barely know what the ring bus actually is.
[27:31] SPEAKER: I don't know what the effects of that are.
[27:34] SPEAKER: I don't I don't remember the actual layout.
[27:37] SPEAKER: I'd have to bring up the slides. I do. OK.
[27:40] SPEAKER: So the the layout is that the four p cores share an L2.
[27:45] SPEAKER: The four p cores are all connected via L3 cache.
[27:49] SPEAKER: Everything's everything on the computer is connected via L3 cache.
[27:53] SPEAKER: The e-cores are connected via shared L2 in clumps of four.
[27:58] SPEAKER: So if you have four e-cores and four p-cores on that compute tile,
[28:05] SPEAKER: then the e-cores have L2 to L2
[28:09] SPEAKER: can talk across the L2 cache that's shared between them.
[28:13] SPEAKER: The p-cores can talk across the L3 cache shared between them.
[28:16] SPEAKER: And if you need to dump something out to those LP, those low power e-cores
[28:21] SPEAKER: that are on the on the on the on the on the main IO die,
[28:26] SPEAKER: then that's a really expensive process.
[28:29] SPEAKER: And we talked about I talked about this with Rajshree a lot,
[28:32] SPEAKER: because it actually comes up in benchmarking like the thread
[28:34] SPEAKER: director performance and the way
[28:37] SPEAKER: the way the system and the OS know whether it's worth computationally speaking,
[28:42] SPEAKER: moving a thread from a p-core to an e-core and e-core to a p-core
[28:46] SPEAKER: is is very dependent on like how long it takes to transfer the data.
[28:50] SPEAKER: Like how many clock cycles it takes to transfer the data.
[28:53] SPEAKER: And she she was talking specifically about like twenty thousand clock cycles
[28:57] SPEAKER: as an expensive as an expensive switchover,
[29:00] SPEAKER: which is like one two hundred thousandth of a second.
[29:03] SPEAKER: Just to be clear, right?
[29:04] SPEAKER: We're we're talking about infinitesimal slices of time.
[29:09] SPEAKER: But and I'm not going to get into that whole thread director thing.
[29:12] SPEAKER: You should like the conversation I have with her.
[29:14] SPEAKER: I think that video is on the full nerd channel, right, Adam?
[29:16] SPEAKER: The full nerd network YouTube channel.
[29:18] SPEAKER: Yeah, is was fast.
[29:20] SPEAKER: Like it was I learned so much about how that stuff works
[29:23] SPEAKER: and why it's hard. I knew it was one of the big computer science problems
[29:27] SPEAKER: going into that conversation.
[29:28] SPEAKER: And I came out with a much better understanding of why it's difficult
[29:32] SPEAKER: and a better understanding of kind of where we are with that stuff,
[29:35] SPEAKER: because it's it really plagues all of the modern architectures.
[29:39] SPEAKER: Apple, Intel, AMD, everybody is having the same problems.
[29:43] SPEAKER: Well, an AMD is is working on this as well.
[29:47] SPEAKER: Like you reference the the chip design that has made them kind of
[29:52] SPEAKER: made their mark on the industry and changed a lot of things with Strix Halo.
[29:57] SPEAKER: I was watching a video by a gentleman
[30:00] SPEAKER: we actually met while we were there that his YouTube is called High Yield.
[30:04] SPEAKER: The he essentially does a real deep dive architecture stuff.
[30:07] SPEAKER: I've learned a lot from him. I'm no expert.
[30:09] SPEAKER: It was it was great to chat with him, but he actually did a really good
[30:14] SPEAKER: deep dive of the of like the I guess topology might be the right word
[30:19] SPEAKER: of Strix Halo and how AMD seems to be using that
[30:24] SPEAKER: to experiment with a new type of interconnect that fuses the huge GPU
[30:30] SPEAKER: that they have on on that processor with the the rest of the processing.
[30:35] SPEAKER: And like, at least according to him, this is like super advanced stuff.
[30:39] SPEAKER: So that's why I think
[30:42] SPEAKER: Strix Halo is important.
[30:44] SPEAKER: And then this this Fovaro stuff is definitely important on the Intel side.
[30:47] SPEAKER: So one of the things they talked about, like TAP in his talk,
[30:51] SPEAKER: when he's talking about GPU stuff, talked about using,
[30:54] SPEAKER: especially for like games that are built for consoles,
[30:57] SPEAKER: using the 8E cores probably makes more sense than using the 4P cores
[31:01] SPEAKER: because the 8E cores have that shared L2 cache.
[31:05] SPEAKER: And also they're they're comparable in terms of like instruction sets
[31:08] SPEAKER: and functionality to the era of current generation CPU cores.
[31:15] SPEAKER: So you don't get any like it's not like there's AVX2 instructions
[31:18] SPEAKER: or something like that in the in these games that are going to take
[31:21] SPEAKER: that the P cores are going to take advantage of, right?
[31:23] SPEAKER: Because the current current consoles have Zen 2 cores in them.
[31:26] SPEAKER: So it's not like you need a lot of modern desktop cores to equal that.
[31:30] SPEAKER: That's exactly it, actually.
[31:31] SPEAKER: Yeah. When I talked to I had a dinner
[31:35] SPEAKER: set up between AMD and Sony about Project Amethyst.
[31:39] SPEAKER: Mark Cerny was there.
[31:41] SPEAKER: That was the first time I got to chat with him.
[31:43] SPEAKER: And he was saying at least, you know, I mean,
[31:46] SPEAKER: they weren't talking about forward looking features,
[31:48] SPEAKER: but he was talking about how even on the PlayStation 5 Pro,
[31:51] SPEAKER: the Zen 2 based CPU cores in there were in there.
[31:54] SPEAKER: He didn't feel like that was a limiting factor,
[31:56] SPEAKER: that it was more other things that that they're working on.
[32:01] SPEAKER: And yeah, the same.
[32:03] SPEAKER: And the other thing to think about is that these are these are very
[32:07] SPEAKER: compact APUs, like
[32:10] SPEAKER: all the all the wattage going into that needs to be shared.
[32:13] SPEAKER: All the heat dissipation is is makes a huge difference compared to desktop.
[32:18] SPEAKER: Right. These these are packages that are going to be put in laptops
[32:23] SPEAKER: than light devices, handheld gaming PCs.
[32:25] SPEAKER: So the more the more perform or the the the more juice
[32:30] SPEAKER: you put you put into high performance cores might take up some of that
[32:36] SPEAKER: overhead when you'd rather be sending all that juice to the GPU. So.
[32:40] SPEAKER: And and the big like the big thing that's happening with this
[32:45] SPEAKER: this generation, like last generation, we saw Meteor Lake
[32:49] SPEAKER: and Lunar Lake and Lunar Lake was kind of the mainstream part.
[32:53] SPEAKER: And Meteor Lake was like, sorry, rather
[32:58] SPEAKER: was in the like desktop replacement kind of workstation mobile parts. Right.
[33:03] SPEAKER: With this, Panther Lake is going to take over all of that.
[33:06] SPEAKER: And both the mainstream.
[33:09] SPEAKER: Well, not necessarily, because they in all their slides,
[33:13] SPEAKER: which once again, a lot of them are vague for a lot of reasons.
[33:17] SPEAKER: They never mentioned Air Lake HX competitors.
[33:20] SPEAKER: So I was just graphics are like the highest end,
[33:24] SPEAKER: like real thick, chunky, eight pound gaming laptops.
[33:28] SPEAKER: Usually it's you know, you got a low power
[33:30] SPEAKER: CPU, kind of a mid range and then a really high power one.
[33:34] SPEAKER: They seem to indicate that the HX this would
[33:38] SPEAKER: like the top end configuration of the core count would would replace that.
[33:43] SPEAKER: But they never set it on any of the slides.
[33:45] SPEAKER: All they were doing was comparing it versus Lunar Lake and Air Lake H.
[33:50] SPEAKER: So I don't know if that means anything, but there might be another spot
[33:53] SPEAKER: in the stack.
[33:55] SPEAKER: I still believe that that Air Lake on the desktop is going to get a refresh.
[34:00] SPEAKER: And I think maybe the highest end laptops will also get an Air Lake refresh.
[34:04] SPEAKER: But yeah, we don't know.
[34:05] SPEAKER: Those are, you know, there's other benchmarks for the I7 270K just pop
[34:10] SPEAKER: plus just popped up or whatever they're calling it.
[34:12] SPEAKER: But it's not like Panther Lake is explicitly mobile only. Right.
[34:15] SPEAKER: There is no desktop component to this next generation that we're talking about.
[34:19] SPEAKER: Right.
[34:20] SPEAKER: Yeah, unless you fuse it to a mini ITX motherboard or something.
[34:23] SPEAKER: I mean, we've seen some of this stuff, but yeah, this is this is meant for
[34:27] SPEAKER: for mobile computing of various sources.
[34:30] SPEAKER: OK, got it. So that's kind of the high points.
[34:33] SPEAKER: They talked about the GPU stuff a little bit.
[34:35] SPEAKER: It's still like it's Intel, they're calling it XE3,
[34:38] SPEAKER: but it's basically the same core as the as the B series desktop GPUs.
[34:45] SPEAKER: What are you saying?
[34:45] SPEAKER: That's what will be in this the next CPUs like in Panther Lake?
[34:48] SPEAKER: That's what's in Panther Lake.
[34:50] SPEAKER: That's the same technology.
[34:51] SPEAKER: It's not the same architecture, maybe a smaller,
[34:56] SPEAKER: smaller total grunt or whatever.
[34:58] SPEAKER: But and so that's what's in like the current arc cards is what you're saying.
[35:02] SPEAKER: That's in the arc B series cards. Yeah, yeah.
[35:04] SPEAKER: So that battle mage, you know, like B5AD.
[35:07] SPEAKER: OK, well, that seems respectable for an integrated GPU.
[35:11] SPEAKER: Yeah, they've done stuff like added multi frame gen.
[35:13] SPEAKER: They're not doing the kind of last second mouse
[35:17] SPEAKER: warp mouse movement warping that video is doing with their five series cards.
[35:22] SPEAKER: But like the performance, it seems fine.
[35:25] SPEAKER: Like we got to I got to play the new painkiller game
[35:28] SPEAKER: on one of their dev boards, one of their dev machines.
[35:32] SPEAKER: But it was a pretty rough demo just just because I was playing
[35:36] SPEAKER: with a mouse and keyboard on a 40 inch TV about eight inches from my face.
[35:40] SPEAKER: So it was it was it was non nonoptimal.
[35:44] SPEAKER: The what I will say is that the multi frame gen on that
[35:48] SPEAKER: on that demo, like even doing something simple, like trying to land the mouse
[35:51] SPEAKER: on the corner of a pillar or something like that was really, really challenging.
[35:54] SPEAKER: So it was a little floatier than I would want for a mouse and keyboard.
[35:57] SPEAKER: But it seemed fine on the gamepad.
[35:59] SPEAKER: Wait, to be clear, you were playing on an integrated GPU on a panther like machine,
[36:02] SPEAKER: not a discrete.
[36:03] SPEAKER: Yeah, I mean, it was I don't they didn't have the machine out.
[36:07] SPEAKER: They had a lot of Panther Lake dev units, which were like
[36:11] SPEAKER: I had sorry, Knuck, bigger than Knuck size
[36:16] SPEAKER: open boxes with small coolers.
[36:19] SPEAKER: Oh, these 40 watt coolers on them are these are these like prototype,
[36:23] SPEAKER: like not for production, like, yeah, kind of similar to when we would see consoles
[36:28] SPEAKER: before they came out and it was not the console.
[36:30] SPEAKER: It was some giant cobbled together.
[36:32] SPEAKER: They had a mixture like they did have like
[36:35] SPEAKER: they had one of the same things that I actually saw at Computex,
[36:38] SPEAKER: which was kind of like a huge dev box board, like not pretty at all.
[36:43] SPEAKER: Yes, I love seeing utilitarian.
[36:45] SPEAKER: Yeah, I think hardware like that.
[36:47] SPEAKER: They did show off the first, yeah, Knuck style development kit,
[36:51] SPEAKER: which is a little more polished, but still meant, you know, for developer usage.
[36:56] SPEAKER: It was not I didn't see one that was powered on.
[36:59] SPEAKER: The only stuff that I saw running that was powered on were reference laptops,
[37:04] SPEAKER: which are usually taken from an OEM and just kind of configured
[37:07] SPEAKER: with a different platform.
[37:09] SPEAKER: So I I don't know.
[37:11] SPEAKER: Do you remember seeing any of the the.
[37:13] SPEAKER: So the painkiller one wasn't out on the shelf.
[37:15] SPEAKER: It was running on something that was in a cabinet.
[37:17] SPEAKER: So I don't know what it was.
[37:19] SPEAKER: The other ones were almost all I think that they had one of those dev kit
[37:22] SPEAKER: boxes running something in the middle, but I don't remember for sure.
[37:27] SPEAKER: Anyway, it doesn't matter like the demos were like they had some premiere demos.
[37:30] SPEAKER: They had a bunch of A.I.
[37:31] SPEAKER: crap that was kind of iffy.
[37:33] SPEAKER: I just I also think like it is.
[37:36] SPEAKER: I mean, it's hard to set up an event like this, right?
[37:38] SPEAKER: It takes it takes a lot.
[37:39] SPEAKER: You know, my hat's off to people who have to organize this kind of stuff
[37:42] SPEAKER: because I'm sure it's a lot.
[37:44] SPEAKER: But unfortunately, and you kind of pointed out a little bit
[37:47] SPEAKER: sometimes like the environment that you try something out in
[37:51] SPEAKER: just like kind of like sets the tone, if that makes sense.
[37:55] SPEAKER: Like I listen to Digital Foundry a lot.
[37:57] SPEAKER: And very often they'll say they'll go to something like
[38:01] SPEAKER: recently they went to what was before you for Gamescom.
[38:05] SPEAKER: And they took some demos at Gamescom.
[38:07] SPEAKER: But like the TV had like motion smoothing on.
[38:11] SPEAKER: And it was just not the HDR wasn't calibrated right.
[38:14] SPEAKER: And, you know, like they're like, guys, I can't
[38:17] SPEAKER: I can't really pay attention to what you're showing here
[38:19] SPEAKER: when the when the environment that I'm supposed to see it on
[38:22] SPEAKER: is not doing it justice.
[38:23] SPEAKER: So I think part of it was that that for will.
[38:26] SPEAKER: But I'm sure you deal with that all the time with with games, right?
[38:29] SPEAKER: When you go to see something.
[38:31] SPEAKER: I think that was like the infamous games beat Cuphead footage thing, right?
[38:35] SPEAKER: Was that like wasn't he wasn't he like kind of Dean Takahashi?
[38:39] SPEAKER: I think didn't he say he was like
[38:40] SPEAKER: like talking to a PR person and kind of half paying attention to the game
[38:44] SPEAKER: when they were recording that? Yeah.
[38:45] SPEAKER: I mean, the error there was then going and recording posting that footage.
[38:49] SPEAKER: Like, I mean, is it like that's where you maybe practice
[38:53] SPEAKER: some editorial discretion and say, oh, this footage is maybe not usable,
[38:56] SPEAKER: but but it absolutely happens all the time that like, hey, this
[38:59] SPEAKER: this environment that I'm checking this out in is compromised in one
[39:02] SPEAKER: to three different ways.
[39:04] SPEAKER: And I've got to kind of
[39:06] SPEAKER: integrate that into my impressions.
[39:08] SPEAKER: That that's why it's hard because it's just like like not that I'm
[39:12] SPEAKER: and I'm not saying that your experience was not valid.
[39:14] SPEAKER: Well, it's just more like like that is not how not representative.
[39:19] SPEAKER: So like when when it's like, oh, yeah, we got to try something,
[39:22] SPEAKER: but it was for all intents and purposes, not worth anything
[39:27] SPEAKER: because it was, you know, just a bad experience.
[39:30] SPEAKER: It was prerelease hardware, prerelease software on a game
[39:33] SPEAKER: that just barely got announced all that kind of stuff.
[39:35] SPEAKER: And it's just like, oh.
[39:36] SPEAKER: When you talk about organizing these events and how herculean
[39:39] SPEAKER: that task must be like, I think about they probably had to commit
[39:42] SPEAKER: to the footprint of that demo station way before they knew
[39:46] SPEAKER: if that demo would actually be ready to show or not.
[39:48] SPEAKER: Right. Like they had to
[39:49] SPEAKER: they had to build out a list of here's what we're going to show with this thing.
[39:52] SPEAKER: Probably weeks in advance of saying, hey, this demo is actually functional.
[39:56] SPEAKER: I'm a hundred percent sure.
[39:58] SPEAKER: Like like like the actual demos, I'm sure are all coming in as hot as possible.
[40:02] SPEAKER: And that's why like I'm always so like I like going to these things
[40:06] SPEAKER: and learning about the technology and, you know, growing my
[40:10] SPEAKER: my knowledge set, because I'm still pretty, pretty fairly early in my journey here.
[40:15] SPEAKER: But like really the fun part is like, OK, when when can I get it
[40:20] SPEAKER: and try it out for myself, have my own experiences in a in in,
[40:24] SPEAKER: you know, a controlled environment?
[40:26] SPEAKER: You know, we always say wait for independent testing because it isn't.
[40:30] SPEAKER: It is important in a lot of ways, but that's what I'm always excited.
[40:33] SPEAKER: It's like, OK, cool.
[40:34] SPEAKER: Thank you for showing me all this stuff.
[40:35] SPEAKER: But man, when can I get my hands on it?
[40:37] SPEAKER: Because, yeah, I just I want to I want to see it.
[40:40] SPEAKER: I want to feel it.
[40:41] SPEAKER: I want to see how how it works.
[40:44] SPEAKER: So, OK, so I did.
[40:46] SPEAKER: I do have an update on something that I'd forgotten.
[40:48] SPEAKER: We asked during the architecture roundtable when Stephen was talking
[40:52] SPEAKER: and we asked what the bandwidth between the CPU and GPU tile was like,
[40:58] SPEAKER: because they're both connected via that Phovros backhaul.
[41:01] SPEAKER: And he specifically said it can be as high as they want.
[41:04] SPEAKER: Like there's it depends on how many of the the connections you choose to use
[41:10] SPEAKER: up to like like you can do
[41:13] SPEAKER: you can bump up the frequency and you can do up to like one hundred
[41:15] SPEAKER: and fifty gigabits per second.
[41:18] SPEAKER: But the thing he said is once you do that, then you start shifting bottlenecks
[41:21] SPEAKER: around and there's definitely sweet spots at different places that require
[41:27] SPEAKER: that are difficult to predict because of the way you're moving the bottlenecks.
[41:31] SPEAKER: The takeaway I had from this is that when they're working inside these SOCs,
[41:35] SPEAKER: especially when they're talking about doing bigger GPUs in some places
[41:39] SPEAKER: than others, is that you can get kind of the same benefits
[41:43] SPEAKER: that we see by using APUs on consoles where they share different parts of the
[41:48] SPEAKER: of the of the they share some high speed connections
[41:52] SPEAKER: and then some low speed connections out to memory and stuff like that.
[41:54] SPEAKER: So you can end up in these weird hybrid architectures that are
[41:58] SPEAKER: similar to desktop, but not exactly analogous
[42:02] SPEAKER: and have some real strengths over the change
[42:06] SPEAKER: where the bottlenecks are on these on these new processors.
[42:09] SPEAKER: And I thought I thought that was kind of interesting.
[42:11] SPEAKER: But also they're not at a point where like the GPU can dig into L3 cache
[42:15] SPEAKER: on the compute die, although it can do like some he said snooping,
[42:20] SPEAKER: which I don't know if that's a technical term or not. But anyway.
[42:24] SPEAKER: Speaking of gaming.
[42:26] SPEAKER: Yeah, I was surprised by how much they talked about handheld gaming.
[42:31] SPEAKER: That's obviously one of the new areas.
[42:33] SPEAKER: And I know, Brad, you have not really messed around with it too much.
[42:37] SPEAKER: But then also talked a lot about AI,
[42:40] SPEAKER: you know, multi frame gen and all that kind of stuff.
[42:43] SPEAKER: When TAP was on the full nerd,
[42:44] SPEAKER: we had a very long discussion about where he thought AI was going.
[42:48] SPEAKER: But then also ray tracing, like the ray tracing performance in this GPU
[42:52] SPEAKER: is one of the places where they wanted to really boost performance
[42:55] SPEAKER: because it is such a big thing.
[42:57] SPEAKER: Like, man, there's been so much talk
[43:00] SPEAKER: recently about the next gen consoles.
[43:03] SPEAKER: I know you guys have talked about it over on next lander, stuff like that.
[43:07] SPEAKER: It's it's always interesting to hear
[43:11] SPEAKER: you guys not or or maybe I don't know how to phrase this.
[43:14] SPEAKER: You guys talk way less about ray tracing over a next lander
[43:18] SPEAKER: and like that kind of stuff than what a lot of these junkets
[43:22] SPEAKER: will talk about and like, yeah, I've always wanted to like
[43:26] SPEAKER: write in a question to next lander and be like, you know, are you
[43:30] SPEAKER: do you guys notice the ray tracing stuff?
[43:32] SPEAKER: How do you guys feel about the ray tracing stuff?
[43:34] SPEAKER: Obviously, they're building that into the hardware.
[43:37] SPEAKER: Mark Cerny is coming out saying, you know, that it's it's an important part.
[43:41] SPEAKER: Yeah, I mean, I personally I remain incredibly bullish about the role
[43:46] SPEAKER: of ray tracing and development and graphics in the long term.
[43:50] SPEAKER: But I think we're still like on the in the middle of the
[43:54] SPEAKER: you know, whatever we're defining as long term, right?
[43:56] SPEAKER: Like I felt like when real time ray tracing first became a thing, it was like, OK,
[44:00] SPEAKER: this is going to take like 10 to 15 years
[44:02] SPEAKER: before this is absolutely integral and everywhere.
[44:05] SPEAKER: And I would add that I think that is also kind of not a popular
[44:09] SPEAKER: topic among the mainstream right now. Yeah.
[44:13] SPEAKER: Because we're not to that point yet.
[44:15] SPEAKER: Like a lot of people still just see it as a a feature that offers
[44:18] SPEAKER: diminishing returns for a huge performance hit.
[44:22] SPEAKER: And also, I feel like a lot of people don't know that they're seeing it right.
[44:26] SPEAKER: I mean, especially like on PC, there's usually a toggle, some sort of,
[44:30] SPEAKER: you know, hey, do you want to turn ray tracing on?
[44:32] SPEAKER: Do you want path tracing, things like that on console?
[44:35] SPEAKER: You're usually picking between different quality modes.
[44:38] SPEAKER: And sometimes the quality mode will say, oh, yeah, this involves ray tracing.
[44:42] SPEAKER: But sometimes you have to wait for the digital foundry video
[44:45] SPEAKER: where they're like, oh, by the way, this part of this pipeline is using ray tracing.
[44:51] SPEAKER: You know, it's one of those things where it's like, man,
[44:53] SPEAKER: how do you how do you really sell that?
[44:55] SPEAKER: How do you get excited for next consoles when it's like, man,
[44:57] SPEAKER: check out this ray tracing performance?
[44:59] SPEAKER: I don't think they're going to have to sell it so much
[45:01] SPEAKER: as it's just going to become a fact of life, because when the next consoles
[45:04] SPEAKER: come out, they are going to be so capable of ray tracing
[45:06] SPEAKER: that everybody's just going to adopt it into their pipeline.
[45:08] SPEAKER: And I think it'll just it'll just be there.
[45:11] SPEAKER: I love that optimism.
[45:13] SPEAKER: Well, I mean, you're seeing it now, you're seeing it like like Indiana
[45:16] SPEAKER: Jones and Doom were the big games this year that you can't run
[45:20] SPEAKER: on non ray tracing hardware. Like that's true.
[45:22] SPEAKER: I think there are going to be tremendously more games.
[45:24] SPEAKER: In fact, I think just about every game.
[45:26] SPEAKER: But again, that's that's 10 years from now is what I'm saying.
[45:28] SPEAKER: It's like it's not going to be until the next consoles have a pretty significant
[45:32] SPEAKER: install base that then developers because that's how it's always gone since
[45:37] SPEAKER: since the 3D, 2D transition, since the PS2 generation, if not before.
[45:41] SPEAKER: It's always been the consoles, what the consoles can do dictates
[45:44] SPEAKER: what trickles down to PCs.
[45:47] SPEAKER: And so once every console on the market, like even the switch
[45:50] SPEAKER: two has capable ray tracing, right?
[45:52] SPEAKER: I mean, once every every console on the market can do
[45:55] SPEAKER: significant ray tracing, then developers are going to be like, OK, well,
[45:58] SPEAKER: now that we are doing this by default on the set top boxes,
[46:02] SPEAKER: it's also going to come to every PC game.
[46:05] SPEAKER: Yeah. And that it's it's it's just interesting, right?
[46:08] SPEAKER: It's like you always hear a bunch of buzzwords
[46:10] SPEAKER: and the companies are like, to a certain degree, we have to put the cart
[46:13] SPEAKER: before the horse and we need we need to use in millions of of CPUs before
[46:20] SPEAKER: or processors before, you know, you can see anything
[46:23] SPEAKER: that actually uses it day to day. Right.
[46:26] SPEAKER: It's interesting getting capable ray tracing into,
[46:30] SPEAKER: you know, mainstream laptop hardware, the kind of computers
[46:34] SPEAKER: that most people buy is part of that. Right.
[46:37] SPEAKER: And I think that's that's that's a step in in that direction,
[46:41] SPEAKER: whether it's it's obviously not going to perform as well as a discrete
[46:45] SPEAKER: standalone GPU or console even.
[46:47] SPEAKER: But but it's a step in the direction.
[46:49] SPEAKER: Yeah, I mean, it's it's it's it's the kind of thing where, like, you know,
[46:52] SPEAKER: iPhones also have ray tracing hardware in them.
[46:54] SPEAKER: Now, like at some point in the not too distant future,
[46:57] SPEAKER: every current shipping product is going to have some amount of ray tracing
[47:00] SPEAKER: and some amount of machine learning capability.
[47:03] SPEAKER: And it's just going to become a mundane fact of software development.
[47:07] SPEAKER: Like everything else.
[47:08] SPEAKER: And then the other the other part of that is that as the comes more capable,
[47:12] SPEAKER: then we'll see software that actually takes advantage of it.
[47:14] SPEAKER: Like there were a handful. Yeah, that's what I mean.
[47:16] SPEAKER: There were a handful of puzzles in Indiana Jones
[47:18] SPEAKER: that used the light rendering to be as part of the puzzle.
[47:22] SPEAKER: But it was kind of it was it wasn't super common in that game. Right.
[47:25] SPEAKER: There weren't a bazillion of those.
[47:27] SPEAKER: So and also, if you didn't know how it worked,
[47:32] SPEAKER: then it was functionally no different than like a light reflection puzzle
[47:35] SPEAKER: in Breath of the Wild or Tears of the Kingdom 10 years ago. Yeah. And and like.
[47:40] SPEAKER: Like, I thought it was cool because I recognized it and I saw it,
[47:43] SPEAKER: but everybody else is just like, oh, OK, whatever.
[47:46] SPEAKER: I mean, that's always been part of the hard sell with ray tracing, right?
[47:48] SPEAKER: Is that the fakery?
[47:49] SPEAKER: The fakery got so good that telling the difference between fake lighting
[47:54] SPEAKER: and quote unquote real or realistic, physically realistic lighting.
[47:58] SPEAKER: Look, it's hard for a lot of people.
[47:59] SPEAKER: It's the same industry, though, that counts the reflections on sweat
[48:02] SPEAKER: on people's faces, on console jumps.
[48:06] SPEAKER: So like, hey, look, look at your nose.
[48:08] SPEAKER: Shadowing the side of your face should be an easy talking point
[48:11] SPEAKER: after puddle gate anyway.
[48:14] SPEAKER: To me, to me, the ray tracing thing has always been a dark alleyway phenomenon,
[48:18] SPEAKER: meaning that like every game that has fake lighting
[48:20] SPEAKER: gets a lot of nice artistic attention in the critical path.
[48:25] SPEAKER: But like dark little alleyways off to the side, they don't bother doing
[48:28] SPEAKER: all the hand tuned lighting to make everything look super great, right?
[48:32] SPEAKER: Like the thing with ray tracing is like, hey, everything is the same lighting now.
[48:35] SPEAKER: Like it's like they don't have to go in and hand place lights
[48:37] SPEAKER: and an art direct lighting to make things look the way they want.
[48:42] SPEAKER: Like like now algorithmically,
[48:43] SPEAKER: just everything gets the same kind of realistic lighting globally.
[48:47] SPEAKER: The early ray tracing demos, right, that were touted out
[48:50] SPEAKER: where there is battlefield or even control where they're like, oh, well,
[48:53] SPEAKER: look at these reflections. Wow, these reflections.
[48:55] SPEAKER: And even I was like, it's cool stuff, but and it wasn't until
[48:59] SPEAKER: like the global illumination stuff like Metro was just like, oh, wow.
[49:04] SPEAKER: That like that is impressive for me because you could actually like
[49:08] SPEAKER: like real light bouncing around.
[49:10] SPEAKER: Yes, that's exactly that kind of stuff.
[49:12] SPEAKER: That's exactly it.
[49:13] SPEAKER: I got I got kind of bummed out when ray tracing became the even for people
[49:16] SPEAKER: who were into it, it kind of became the like better reflections tech,
[49:19] SPEAKER: quote unquote, for a long time, because like bounce lighting is the actual
[49:23] SPEAKER: super interesting, like brain tickling one for me is like,
[49:28] SPEAKER: you know, light shines on this apple
[49:30] SPEAKER: and then it picks up red in its in its bounces.
[49:32] SPEAKER: You know, now now you've got like a red glow on the thing is bouncing out, too.
[49:36] SPEAKER: Like that's the kind of stuff you didn't really see before.
[49:39] SPEAKER: Well, and there's secondary and tertiary effects as well.
[49:42] SPEAKER: So not to make this whole thing a treatise
[49:45] SPEAKER: on why ray tracing rules and the Internet's wrong.
[49:48] SPEAKER: But but but like because the cost of moving lights
[49:52] SPEAKER: and changing things that affect the light rendering in a game
[49:55] SPEAKER: goes down for developers when they're iterating,
[49:58] SPEAKER: it means they're able to iterate more and they're able to make more changes.
[50:01] SPEAKER: And they spend less time on that and more time on other things.
[50:04] SPEAKER: And then there's the whole tertiary effect of, oh, by the way,
[50:07] SPEAKER: if we have hardware that's really good at tracing rays,
[50:10] SPEAKER: we can make more realistic sound models and things like that.
[50:13] SPEAKER: And we because we can use that same hardware to do to do sound renders.
[50:16] SPEAKER: Yes, I have spoken to at least one game developer
[50:19] SPEAKER: who has talked about how excited they are to use the.
[50:23] SPEAKER: Use the properties of ray tracing hardware for things other than lighting
[50:26] SPEAKER: and sound sound was one of those like A.I., not not machine learning A.I.,
[50:31] SPEAKER: but enemy A.I. was another one like they basically were very excited about,
[50:35] SPEAKER: like, you know, it's because it's just hardware for modeling interactions
[50:38] SPEAKER: in a physical space.
[50:39] SPEAKER: So you can think of all the other ways that that would be useful beyond lighting.
[50:43] SPEAKER: Well, it's funny.
[50:44] SPEAKER: I talked to somebody the other day who's building a
[50:46] SPEAKER: pathing system for their game that uses the ray tracing hardware. Right.
[50:50] SPEAKER: Because like the expensive and hard thing about generating what's pathable
[50:54] SPEAKER: and what's not is that you run this thing that takes hours and hours to run.
[50:57] SPEAKER: But if you have ray tracing hardware in the machine,
[50:59] SPEAKER: you know, you're going to have that.
[51:00] SPEAKER: You can change that dynamically based on changes in the environment
[51:03] SPEAKER: in a way that's unscripted.
[51:05] SPEAKER: And like like anyway, there's there's a bunch of cool knock on effects
[51:08] SPEAKER: that come with ray tracing hardware that aren't reflections or shadows or
[51:12] SPEAKER: or reflected light even.
[51:14] SPEAKER: So anyway, yeah, my my my feeling is it's going to be like next consoles
[51:18] SPEAKER: plus three years or so before we really start seeing like
[51:21] SPEAKER: kind of universal effects.
[51:23] SPEAKER: I think that's showing up in games maybe four years.
[51:26] SPEAKER: I don't know. I mean, anyway, the good thing is, I think I think
[51:30] SPEAKER: I think it's going to be based on the sales rate and how long the
[51:33] SPEAKER: like the the kind of transitory part of the generation is.
[51:37] SPEAKER: Like if we look at last go round, there was a long period
[51:40] SPEAKER: from launch of PS5 and Xbox Series X
[51:44] SPEAKER: to the games not being released on PS4 and Xbox One. Yes.
[51:49] SPEAKER: And I think like that being so long kind of held back
[51:52] SPEAKER: that first part of the generation.
[51:54] SPEAKER: Yeah, that's totally right.
[51:55] SPEAKER: And that's going to be the gate on this, because the thing is
[51:59] SPEAKER: the hardware has been there for a while.
[52:00] SPEAKER: UE5 is good at ray tracing both in software and in hardware.
[52:04] SPEAKER: And we'll like the technologies there.
[52:07] SPEAKER: The people who've been working on this will be able to do it.
[52:09] SPEAKER: The question is, does it make a market sense
[52:10] SPEAKER: because they want to be able to sell games on PS5?
[52:12] SPEAKER: I don't think they care about the Series X.
[52:13] SPEAKER: So that's half of that problem solved anyway.
[52:17] SPEAKER: Should we talk about the fab?
[52:18] SPEAKER: Yeah, because I think this was this was the cool.
[52:21] SPEAKER: Like this is why I went to this trip.
[52:23] SPEAKER: I could have looked at the slides when I got back and gotten most.
[52:26] SPEAKER: I mean, actually, that's not true.
[52:28] SPEAKER: Talking to the Intel Fellows was it was incredibly informative
[52:32] SPEAKER: and super worth making the trip to Arizona for.
[52:35] SPEAKER: The fab tour was kind of icing on the cake for me.
[52:38] SPEAKER: Did you guys put on bunny suits?
[52:40] SPEAKER: We did. Oh, yeah.
[52:42] SPEAKER: Head to toe. We had a we had a beard nets.
[52:46] SPEAKER: Yeah. As well as hair nets.
[52:48] SPEAKER: Well, back when I had a beard back in those days.
[52:51] SPEAKER: Yeah. No. Yeah.
[52:52] SPEAKER: I felt like because we had small groups.
[52:55] SPEAKER: I think it was like 12 of us that was going in one at a time.
[52:58] SPEAKER: Yeah, that's right.
[52:58] SPEAKER: Ten or twelve one at a time, like the group at a time.
[53:01] SPEAKER: And yeah, they I felt like I was a piece of meat getting shut through
[53:05] SPEAKER: because they would give you your suit, your whole your whole setup,
[53:09] SPEAKER: and then they would have somebody like help you do it step by step.
[53:13] SPEAKER: And it was intense.
[53:14] SPEAKER: They kind of warned you it was going to be warm inside the suit.
[53:18] SPEAKER: But also in some ways, like then later when we were in it,
[53:22] SPEAKER: like we could kind of stick out our nose and they were like, oh, yeah, it's fine.
[53:26] SPEAKER: You can have your nose exposed.
[53:28] SPEAKER: We want you to be comfortable.
[53:29] SPEAKER: It's like, wait, I thought you just had us go through all this stuff to minimize
[53:33] SPEAKER: dust particles in the air, skin particles.
[53:36] SPEAKER: Does that officially qualify as a clean room, did they say?
[53:38] SPEAKER: Oh, yeah.
[53:39] SPEAKER: So there's ISO standards for clean rooms that are based on how much particulate
[53:43] SPEAKER: there is per square foot or square meter of air or cubic meter, rather, of air.
[53:48] SPEAKER: And this one is not.
[53:50] SPEAKER: So this fab, the 18A fab that we were in and which was fab, what, 50, 53?
[53:57] SPEAKER: Oh, I don't remember the numbers.
[53:59] SPEAKER: I don't remember. Anyway,
[54:01] SPEAKER: the we we went through basically one fab to get to the new fab.
[54:05] SPEAKER: And both of those use these things called foops that are enclosed wafer holders.
[54:11] SPEAKER: They're like, we've seen them at the flea market before.
[54:14] SPEAKER: They're like big plastic containers that are the ones they were kind of orangey,
[54:18] SPEAKER: I assume, to keep certain wavelengths of light out.
[54:21] SPEAKER: And they carry the wafers from machine to machine.
[54:24] SPEAKER: And these caddies that ride on rails above the floor of the fab, like 30 feet up.
[54:29] SPEAKER: And so they have a lower standard than some other fabs
[54:33] SPEAKER: that use exposed wafers where they need, you know, much lower particulate.
[54:38] SPEAKER: They wear fully enclosed heads or rebreathers or masks or whatever.
[54:42] SPEAKER: But yeah, we so we walked into the the like the clean room
[54:45] SPEAKER: to get into the clean room area.
[54:46] SPEAKER: We had to be badged in through a gate.
[54:48] SPEAKER: And once we were on the other side of the gate, we stepped in and put
[54:53] SPEAKER: like foot coverings on shoe coverings on.
[54:55] SPEAKER: I was waiting to hear about the booties.
[54:56] SPEAKER: I knew that they had to be in there.
[54:58] SPEAKER: Yeah. So we put booties on to keep dirt from our shoes off of the floor
[55:02] SPEAKER: in the clean room gowning area.
[55:04] SPEAKER: And then we put on beard nets
[55:05] SPEAKER: and hair nets to keep the particulate from our face,
[55:08] SPEAKER: because like the humans, the grossest thing in the whole fab, right?
[55:11] SPEAKER: We're just constantly shedding and anywhere really, not just that.
[55:16] SPEAKER: And so then we we got we went in, they sized us up for the bunny suits.
[55:21] SPEAKER: The people there immediately knew what we were doing and fit us perfectly.
[55:25] SPEAKER: And we got the bunny suits and then outer outer.
[55:28] SPEAKER: Oh, and we put on gloves before we got into the clean room area, too.
[55:32] SPEAKER: Like two clothes. Yeah.
[55:34] SPEAKER: So we put on the gloves.
[55:36] SPEAKER: We put on we got boots, we got a hood, we got a bunny suit
[55:41] SPEAKER: and we put the bunny suit on, then put the boots on on top of those.
[55:45] SPEAKER: But the hood, which got tucked into the bunny suit,
[55:48] SPEAKER: had our hair nets and beard nets on already and put on like
[55:54] SPEAKER: latex gloves on top of the cotton gloves.
[55:56] SPEAKER: Is that right? Or was it the other way around?
[55:57] SPEAKER: Latex first and then cotton. Yeah.
[55:59] SPEAKER: So night trial, we use night trials, latex allergy people didn't die.
[56:05] SPEAKER: But we didn't have to wear a mask like the hood kind of covered
[56:08] SPEAKER: your mouth, kind of covered your nose if you wanted to.
[56:12] SPEAKER: And we put goggles on on top of the glasses we were wearing
[56:16] SPEAKER: or if you wore eyeglasses.
[56:19] SPEAKER: And then and then once that was all done, we like put our little badges on.
[56:23] SPEAKER: So they knew we were part of a tour and not to be trifled with
[56:26] SPEAKER: and kind of got let out into the fab floor, which was almost like
[56:32] SPEAKER: the thing that struck me immediately was how much movement there was.
[56:35] SPEAKER: There was there was.
[56:38] SPEAKER: A lot of people, a lot of machines scurrying,
[56:41] SPEAKER: like the caddies that carried the foops around were constantly going
[56:46] SPEAKER: and they were carrying the what?
[56:47] SPEAKER: The foops, the things that carried the fiber, the the the wafers, the wafers.
[56:54] SPEAKER: And I thought, yeah, they look like little plastic containers
[56:57] SPEAKER: that just have a like a stack of wafers in it.
[57:01] SPEAKER: And like that, that's sealed as well.
[57:03] SPEAKER: So like, I think that's why like they have multiple layers of ceiling.
[57:07] SPEAKER: Like I always thought of a clean room is like a like a like
[57:10] SPEAKER: kind of like a medical space. Right.
[57:12] SPEAKER: And you got very limited people in there and they're doing stuff real carefully.
[57:15] SPEAKER: This was like, I mean, this is a huge, huge building,
[57:19] SPEAKER: you know, with with dozens and dozens of people all doing all this
[57:22] SPEAKER: different kind of stuff.
[57:24] SPEAKER: And they were talking about how the advance, the filtration system
[57:27] SPEAKER: was in the building, like the air, the the air was moving from top to bottom.
[57:33] SPEAKER: And the bottom grading was like vented.
[57:35] SPEAKER: And it was just like, yeah.
[57:37] SPEAKER: So even if you shed a particle, it was going to be sucked into the floor
[57:40] SPEAKER: within a matter of seconds.
[57:42] SPEAKER: And like you could feel it, just to be clear,
[57:44] SPEAKER: you could feel the breeze even inside the bunny suit.
[57:48] SPEAKER: And so so you walk into this room and there's like a bunch of hallways
[57:53] SPEAKER: that I think were food like drop points so they could drop those caddies.
[57:57] SPEAKER: I sent you a link to a way for a way for world article
[57:59] SPEAKER: that explains what hoops are and doesn't exactly show them.
[58:02] SPEAKER: But it stands for kind of kind of looks like a record holder.
[58:05] SPEAKER: Yeah. It's almost like a big CD changer, honestly, a CD changer cartridge.
[58:11] SPEAKER: But they're they're there.
[58:13] SPEAKER: It stands for front opening unified pod or front opening universal pod.
[58:18] SPEAKER: And the idea is that they're sealed containers
[58:20] SPEAKER: that carry the wafers from machine to machine.
[58:23] SPEAKER: So like these caddies are zooping along 20 or 30 miles an hour, 30 feet in the air.
[58:27] SPEAKER: And there's a bunch of tubes and stuff coming up out of the floor.
[58:31] SPEAKER: And the whole thing is set up.
[58:32] SPEAKER: And I talked to the guy was like, do your guys play Factorio when they go home?
[58:36] SPEAKER: Is this like the shit that they love?
[58:38] SPEAKER: Because the whole thing is set up
[58:40] SPEAKER: so that the really expensive machines are never sitting idle, right?
[58:43] SPEAKER: Like as soon as one of the foops gets lifted off, the next one gets put in place
[58:48] SPEAKER: so that it's fooping constantly like like it's foop to foop, man.
[58:53] SPEAKER: Never stops me fooping. Yeah.
[58:57] SPEAKER: So so yeah.
[58:59] SPEAKER: So you see these things I've cracked up at them.
[59:02] SPEAKER: I'm sorry. You see these things done.
[59:04] SPEAKER: You see these things flying around and then they get to the machine
[59:07] SPEAKER: that they're above and it lowers down the caddy on like two wires
[59:11] SPEAKER: from this from this thing 30 feet in the air and drops it directly
[59:15] SPEAKER: on the foop mounting port.
[59:17] SPEAKER: And then the machine docks with it and sucks the the wafers in does its thing
[59:22] SPEAKER: and then spits them back out, probably in the same same place. Right.
[59:27] SPEAKER: And and all of the machines are lined up.
[59:30] SPEAKER: So those foop docks are even with each other and directly below the tracks.
[59:33] SPEAKER: That that seems to be the main defining characteristic.
[59:36] SPEAKER: And then the guy who gave us the tour, Bill, something or other,
[59:41] SPEAKER: was saying that they're they're
[59:45] SPEAKER: like that whole structure is something like they have they have buffers
[59:49] SPEAKER: for the slower machines so that the expensive machines have
[59:53] SPEAKER: have have wafers ready to go that are like X number of minutes deep
[59:57] SPEAKER: in case one of the machines goes down.
[59:59] SPEAKER: So that this thing that costs half a billion dollars is never sitting idle,
[1:00:02] SPEAKER: basically. Sure. Yeah. That makes sense.
[1:00:04] SPEAKER: Yeah. It was kind of crazy tense.
[1:00:06] SPEAKER: Yeah. Like in that that was the weird part is that, yeah, they were I mean,
[1:00:10] SPEAKER: what, like 40 feet, 30 feet over? I think 30 feet probably. Yeah.
[1:00:13] SPEAKER: Yeah. Like really high. And when they would go down into the machine,
[1:00:17] SPEAKER: they're coming down just by like a couple of wires.
[1:00:19] SPEAKER: And they're not they're not like swaying in the wind or something like that.
[1:00:22] SPEAKER: It just looked like they came straight down, came back up
[1:00:25] SPEAKER: three miles an hour, like kind of seems pretty fast
[1:00:27] SPEAKER: for delicate stuff like that to be whizzing around overhead.
[1:00:30] SPEAKER: But it's all I mean, it's all sealed and it's like all that.
[1:00:33] SPEAKER: There's no it's not like rattling around in there.
[1:00:35] SPEAKER: Yeah. I want to ask real quick in your notes here.
[1:00:39] SPEAKER: Yeah. You have you have listed that this land was bought in the 70s.
[1:00:42] SPEAKER: Yes. And they sorry.
[1:00:45] SPEAKER: And then they broke ground in the 90s.
[1:00:47] SPEAKER: Is this a is this a brand new facility?
[1:00:49] SPEAKER: So or is there was there have there been parts
[1:00:52] SPEAKER: of this facility that were already in operation prior to this?
[1:00:55] SPEAKER: This this fab is new like this. This fab is.
[1:00:59] SPEAKER: Yeah, because it's huge.
[1:01:00] SPEAKER: It's bigger than any of the ones I've done before.
[1:01:02] SPEAKER: So so my actual ultimate question here,
[1:01:04] SPEAKER: have they been working on this facility since the 90s?
[1:01:07] SPEAKER: No, no, no. There's other fabs at this facility.
[1:01:10] SPEAKER: That's what I was. So, OK.
[1:01:11] SPEAKER: So there's a lot of other processes going on with other,
[1:01:14] SPEAKER: you know, process technologies.
[1:01:16] SPEAKER: So, OK, I think that they had I think they said they have a million
[1:01:20] SPEAKER: or two million square feet of fab space at this at this campus.
[1:01:25] SPEAKER: The clean room area you like you can walk from one fab to the other,
[1:01:29] SPEAKER: all in clean room.
[1:01:31] SPEAKER: You can move flops from clean room to clean room.
[1:01:34] SPEAKER: But I mean, I don't it seemed like they don't do a whole ton of that.
[1:01:39] SPEAKER: They did anybody ask why they set up a water
[1:01:42] SPEAKER: intensive industrial process in the desert?
[1:01:45] SPEAKER: Yeah, I did ask that.
[1:01:46] SPEAKER: That was one of the first things I said.
[1:01:48] SPEAKER: This is fab 52, by the way, not not.
[1:01:52] SPEAKER: So the reason they did in the desert is because being tectonically stable
[1:01:56] SPEAKER: and having reliable power is like the water problem is tractable
[1:02:01] SPEAKER: and they can reclaim a fairly enormous amount of water.
[1:02:05] SPEAKER: I think they said they go through nine million gallons of water a day
[1:02:08] SPEAKER: and they treat some enormous percentage of it.
[1:02:11] SPEAKER: I don't think they have an exact number,
[1:02:15] SPEAKER: but the power and tectonic stability is much more important.
[1:02:18] SPEAKER: As the person who's giving us the tour said, if they had known
[1:02:22] SPEAKER: that the organ fabs are on a huge fault
[1:02:26] SPEAKER: at the time that they built them, they probably wouldn't have built them there.
[1:02:29] SPEAKER: Oh, OK. And it's interesting because, of course, Taiwan has the other big fabs
[1:02:33] SPEAKER: like this, and it's also on like pure Ring of Fire out there.
[1:02:36] SPEAKER: So I asked what happens if there's an earthquake, because they do
[1:02:41] SPEAKER: occasionally have earthquakes that Southern California earthquakes
[1:02:44] SPEAKER: sometimes make it through to Arizona.
[1:02:46] SPEAKER: And basically all of the seismically sensitive machines
[1:02:50] SPEAKER: have the equivalent of like old hard drive head parking technology
[1:02:53] SPEAKER: where they just immediately freeze and shut down.
[1:02:56] SPEAKER: If there's any kind of ground trembler
[1:03:00] SPEAKER: and also the building is somewhat seismically isolated, apparently.
[1:03:05] SPEAKER: The other thing that Adam and we didn't talk about at all
[1:03:07] SPEAKER: is that there's subfloor beneath the area where this is all built.
[1:03:12] SPEAKER: Where like a lot of the machines, you see the tops poking out,
[1:03:15] SPEAKER: but they're like icebergs and the rest of them are like that.
[1:03:18] SPEAKER: 75 percent of the machine is in the subfloor underneath where like water
[1:03:21] SPEAKER: and chemicals and whatever, you know, ions and stuff come through.
[1:03:26] SPEAKER: Like I've been in a couple of places that are mechanically
[1:03:29] SPEAKER: incredibly complicated before, like car factories and stuff like that.
[1:03:32] SPEAKER: And I've never seen anything that had this level of density
[1:03:36] SPEAKER: when it comes to technology and kind of what you see.
[1:03:40] SPEAKER: So it's pretty wild.
[1:03:42] SPEAKER: Yeah, no, I mean, the actual fab tour was definitely
[1:03:47] SPEAKER: once of a lifetime kind of thing.
[1:03:48] SPEAKER: There's been other opportunities in the past and I've never been able to attend.
[1:03:52] SPEAKER: So I appreciate going and checking it out.
[1:03:55] SPEAKER: And just like it is it is crazy.
[1:03:58] SPEAKER: But not that I take any of this PC hardware for granted,
[1:04:02] SPEAKER: but at the end of the day, when you're playing a game or,
[1:04:05] SPEAKER: you know, working on Excel or something like that, you're not thinking about
[1:04:08] SPEAKER: all the crazy technologies that it took just to get that that CPU into your hands.
[1:04:14] SPEAKER: Yeah, I mean, the thing about the thing about,
[1:04:17] SPEAKER: you know, semiconductor fabrication to me is that it's so elemental, you know,
[1:04:21] SPEAKER: it's just metal, it's just giant disks of metal that they are turning
[1:04:24] SPEAKER: into something that can do all the things a computer can do.
[1:04:27] SPEAKER: Like, it's just hard to wrap your head around that process sometimes.
[1:04:31] SPEAKER: Well, in these.
[1:04:33] SPEAKER: So this this fab in particular takes wafers in and spits wafers out.
[1:04:38] SPEAKER: There's no like they're not cutting the chips out here or anything like that.
[1:04:41] SPEAKER: They're only doing those compute tiles here right now.
[1:04:43] SPEAKER: They're not doing the other.
[1:04:45] SPEAKER: They're stamping the wafers. Yeah.
[1:04:47] SPEAKER: Etching whatever the technical term is in smartening.
[1:04:51] SPEAKER: Yeah. And then and then the other thing is that it operates 24/7, 365.
[1:04:57] SPEAKER: And there's always around 4000 people on campus, which I didn't like.
[1:05:01] SPEAKER: A lot of the other fab situations that I've been familiar
[1:05:04] SPEAKER: with are a little more automated and a little less human intensive.
[1:05:08] SPEAKER: But like there were a lot load of people around here all the time.
[1:05:11] SPEAKER: Kind of kind of crazy to think about
[1:05:13] SPEAKER: punching the clock on the graveyard shift at the at the 18 a fab.
[1:05:17] SPEAKER: I mean, you wouldn't you wouldn't be able to tell there's no windows.
[1:05:20] SPEAKER: There's nothing like the lighting was had to be weird anyway,
[1:05:24] SPEAKER: for whatever reason of, you know, light waves.
[1:05:28] SPEAKER: But yeah, it's got to be intense for sure.
[1:05:31] SPEAKER: I mean, so the other the couple other things
[1:05:33] SPEAKER: that I thought were kind of weird and interesting.
[1:05:35] SPEAKER: Apparently, if you work with copper in the fab,
[1:05:38] SPEAKER: because it's a contaminant at a molecular level,
[1:05:43] SPEAKER: you only can work on like, yeah, they make you wear a different suit,
[1:05:47] SPEAKER: a different color suit, and you use different tools.
[1:05:49] SPEAKER: You come in through a different door.
[1:05:52] SPEAKER: And every time they walk by the non copper people, they give you a noogie.
[1:05:56] SPEAKER: Like, yeah, like, man, it is really, really classist over there.
[1:05:59] SPEAKER: Different. Oh, go ahead.
[1:06:01] SPEAKER: So I'm sorry. You mean contaminant for the fabrication process?
[1:06:04] SPEAKER: I assume not for human beings.
[1:06:06] SPEAKER: Yeah. Contaminant for the fabrication process.
[1:06:08] SPEAKER: Got it. They they like they really like the machines
[1:06:12] SPEAKER: either had copper, OK, or no copper written on the side of all of them.
[1:06:17] SPEAKER: And it was because like a handful of atoms of copper
[1:06:20] SPEAKER: can contaminate a whole wafer or a whole machine.
[1:06:23] SPEAKER: Apparently, it seemed real, real serious.
[1:06:25] SPEAKER: They were very serious about that.
[1:06:27] SPEAKER: I guess that makes sense.
[1:06:28] SPEAKER: It would it would alter the conductivity properties, right?
[1:06:30] SPEAKER: To have a different metal mix presumably. Yeah.
[1:06:33] SPEAKER: They didn't we weren't allowed to wear a hair product or
[1:06:38] SPEAKER: like makeup, cologne, makeup,
[1:06:41] SPEAKER: nothing, nothing with volatile esters in it.
[1:06:44] SPEAKER: Basically, they did tell us we could wear deodorant, which was I was grateful for.
[1:06:49] SPEAKER: I skipped it just for fun.
[1:06:50] SPEAKER: Yeah. I mean, I thought about it,
[1:06:51] SPEAKER: but I decided for your benefit, I would I would I would do it or not.
[1:06:56] SPEAKER: And yeah, like it was I think we were inside for maybe 45 minutes
[1:06:59] SPEAKER: and walked like, what, a half a mile or something.
[1:07:01] SPEAKER: We couldn't take any electronics in both from an E.M.
[1:07:05] SPEAKER: interference perspective, because a lot of the machines are E.M. sensitive,
[1:07:09] SPEAKER: but also obviously because they didn't want us taking pictures.
[1:07:11] SPEAKER: And they like it was funny because we saw like machines
[1:07:15] SPEAKER: running old software, like old versions of windows and stuff
[1:07:18] SPEAKER: hooked up to different things.
[1:07:20] SPEAKER: And when we asked what those machines were, they were like, well,
[1:07:21] SPEAKER: we we're not talking about that machine today.
[1:07:24] SPEAKER: We're not, you know, blah, blah, blah.
[1:07:26] SPEAKER: Sneak some spy photos onto a rage bait YouTube channel.
[1:07:29] SPEAKER: Intel's running 18A on Windows seven.
[1:07:33] SPEAKER: Absolutely. We're running Windows seven.
[1:07:36] SPEAKER: We did see the EUV machine, which is the half billion dollar
[1:07:40] SPEAKER: extreme lithography machine that's like the size of three school buses.
[1:07:45] SPEAKER: And we get to touch it.
[1:07:46] SPEAKER: They didn't let us touch it.
[1:07:48] SPEAKER: Yeah, it's big. Yeah, it's big.
[1:07:50] SPEAKER: It's nondescript.
[1:07:51] SPEAKER: You could walk by it and just think it was nothing.
[1:07:53] SPEAKER: But yeah, it was it was intense.
[1:07:55] SPEAKER: And there was space for at least two more of those next to it.
[1:07:58] SPEAKER: So, you know, are those the ones that I keep seeing stuff
[1:08:02] SPEAKER: about the supply chain for those is like a single point of failure
[1:08:05] SPEAKER: where it's like one company in Germany makes the mirrors,
[1:08:08] SPEAKER: like one company in Denmark makes this and that. I don't know.
[1:08:12] SPEAKER: It seems like they're all mostly bespoke, but they also really specialized.
[1:08:17] SPEAKER: Yeah, like they did.
[1:08:18] SPEAKER: I don't think that machine even had logos on it for whoever made it.
[1:08:21] SPEAKER: It's like it's like it's like if you have to ask
[1:08:24] SPEAKER: where you get an EUV machine, you're probably out of luck, I guess.
[1:08:28] SPEAKER: You're probably dealing with some nation state level approvals or something.
[1:08:31] SPEAKER: Yeah. To be clear, they do this.
[1:08:35] SPEAKER: This this machine operates in vacuum
[1:08:37] SPEAKER: and you can't use glass for mirrors because the EUV light,
[1:08:42] SPEAKER: the extreme ultraviolet light is absorbed by both air and glass.
[1:08:47] SPEAKER: So they did they had to do all sorts of like
[1:08:50] SPEAKER: crazy material science stuff to make these things even possible.
[1:08:54] SPEAKER: Anyway, that that was kind of the hype.
[1:08:58] SPEAKER: We stopped at the EUV machine and they made us turn around and go back.
[1:09:01] SPEAKER: We didn't get to see what's on the other side of that.
[1:09:03] SPEAKER: And it's unclear to me if that machine it was really long.
[1:09:06] SPEAKER: I don't know if like the wafers went in one end
[1:09:09] SPEAKER: and they got blasted by the thing at the end of it,
[1:09:11] SPEAKER: or if it was like going on a little line down it and stuff was happening as it went.
[1:09:14] SPEAKER: So who knows? Is it possible to say I don't even think we could tell
[1:09:18] SPEAKER: like where the food centered that I didn't see a food poll on those now.
[1:09:24] SPEAKER: Yeah, and there wasn't like people manning it either.
[1:09:26] SPEAKER: Like nobody was like standing around it.
[1:09:28] SPEAKER: It was just just sitting there doing its thing.
[1:09:30] SPEAKER: But like talking about how they kept keep that thing fed
[1:09:34] SPEAKER: was giving me real, real factorio and satisfactory flashbacks to like,
[1:09:40] SPEAKER: oh, OK, so you need a hopper that stores
[1:09:42] SPEAKER: foops that are ready for this that's nearby.
[1:09:45] SPEAKER: And and the guy Bill, who's taking us on the tour, was like, yeah,
[1:09:49] SPEAKER: all that stuff kind of happens like the systems that drive that just know that
[1:09:53] SPEAKER: the the poop that they're carrying has this wafer on it at this stage.
[1:09:57] SPEAKER: And it needs to go to this area next.
[1:09:59] SPEAKER: And it knows that there's slack space at these five places.
[1:10:02] SPEAKER: And it just puts it the one that's closest.
[1:10:04] SPEAKER: And he's like, it's not it's it's almost like a packetized delivery network,
[1:10:09] SPEAKER: like a network, like an IP network, but for wafers,
[1:10:13] SPEAKER: which which like when he explained it that way, it made sense.
[1:10:15] SPEAKER: So that's wild. Yeah, that's all wild.
[1:10:19] SPEAKER: It was it was like being in Willy Wonka's
[1:10:22] SPEAKER: chocolate factory, but less Hugh Grant and more foops.
[1:10:27] SPEAKER: Snowsberries taste like snowsberries.
[1:10:29] SPEAKER: Yeah. Adam didn't let us taste snowsberries.
[1:10:32] SPEAKER: Adam didn't pick any USB keys off the floor either.
[1:10:34] SPEAKER: So I was looking. Yeah.
[1:10:36] SPEAKER: Not that I wouldn't have.
[1:10:38] SPEAKER: Yeah, probably for the best.
[1:10:39] SPEAKER: Yeah. Yeah. Is this a good place to ask some wrap up questions?
[1:10:43] SPEAKER: Let's do it. So as somebody who wants somebody
[1:10:48] SPEAKER: who's ready for a new desktop CPU, there is nothing here for me yet.
[1:10:51] SPEAKER: Right. Like this is Panther Lake is all mobile, like Nova Lake.
[1:10:54] SPEAKER: They're not even saying the words right.
[1:10:55] SPEAKER: Like there's nothing for me to grasp on to yet.
[1:10:58] SPEAKER: And they have confirmed no Panther Lake on desktop. Right.
[1:11:01] SPEAKER: So. Right. OK.
[1:11:02] SPEAKER: They haven't said what's next.
[1:11:04] SPEAKER: But like I said, I I believe that it's going to be an Air Lake refresh.
[1:11:07] SPEAKER: That's yes. But but as far as as far as like a fully next generation
[1:11:13] SPEAKER: desktop part on 18A and stuff, that's all that sounds like that's all a good ways off.
[1:11:18] SPEAKER: I mean, yeah. Or maybe they skip 18A for desktop.
[1:11:21] SPEAKER: I don't even know.
[1:11:23] SPEAKER: I have seen I have seen the term 14A starting to float around.
[1:11:27] SPEAKER: Yeah. So I actually don't know.
[1:11:30] SPEAKER: Do you guys have any sense of like how did Intel get on this leapfrog
[1:11:34] SPEAKER: Hayden Swear Lake Meteor Lake and Lunar Lake were mobile only.
[1:11:38] SPEAKER: And then like Air Lake got a desktop part and now Panther is mobile only again.
[1:11:41] SPEAKER: Is it is it purely a function of laptops or what cell now?
[1:11:44] SPEAKER: And they just are not emphasizing desktop parts as much or what?
[1:11:48] SPEAKER: No, they've done that in the past before.
[1:11:50] SPEAKER: Like Ice Lake was mobile only.
[1:11:52] SPEAKER: OK. And that was around like 10th Gen.
[1:11:56] SPEAKER: Yeah. Yeah. So like they do that every once in a while.
[1:11:59] SPEAKER: And and I think that's the thing is that like where AMD takes pride
[1:12:03] SPEAKER: on sale scaling the same core from mobile to all the way up to the server.
[1:12:09] SPEAKER: Intel usually has different platforms for different market segments.
[1:12:14] SPEAKER: I think I think it's more like, oh, hey, lunar lake.
[1:12:18] SPEAKER: We really wanted something that was power efficient
[1:12:21] SPEAKER: that had the NPU that could hit copilot plus.
[1:12:25] SPEAKER: We can't or there's no point in scaling this technology to a desktop part.
[1:12:29] SPEAKER: Let's have something else do that.
[1:12:31] SPEAKER: Like Intel, Intel kind of plays mix and match,
[1:12:34] SPEAKER: which is why they're really leaning into Foveros kind of stuff.
[1:12:38] SPEAKER: And so something that they've always said before.
[1:12:42] SPEAKER: Whether it's around NPU or why they got rid of hyper threading
[1:12:47] SPEAKER: or why they've used TSMC sometimes and their own process
[1:12:51] SPEAKER: sometimes is like, oh, we use the right part for the right time
[1:12:55] SPEAKER: or, you know, something along those lines.
[1:12:56] SPEAKER: So like they they they pretty much mix and match.
[1:12:59] SPEAKER: So this isn't unprecedented to have architectures
[1:13:03] SPEAKER: that that are on one area and not the other.
[1:13:06] SPEAKER: OK, that makes sense.
[1:13:07] SPEAKER: The kind of feeling I wanted I got was that they knew
[1:13:11] SPEAKER: that Lunar Lake was going to be really good early on,
[1:13:15] SPEAKER: like the performance was going to be there for mainstream parts.
[1:13:17] SPEAKER: It was capped at 32 gigs because of the memories on the on the chip,
[1:13:22] SPEAKER: 32 gigs of RAM.
[1:13:24] SPEAKER: But like so.
[1:13:26] SPEAKER: So that bought them headroom to do more with this.
[1:13:29] SPEAKER: Although this also still feels like a fairly concerned,
[1:13:33] SPEAKER: like this feels like the small bump rather than the big bump.
[1:13:36] SPEAKER: If we're looking at the kind of old tick tock metaphor
[1:13:39] SPEAKER: that every time you mentioned while you were there,
[1:13:42] SPEAKER: he's like, well, we really don't like that metaphor anymore.
[1:13:44] SPEAKER: But this one's definitely a tick, not a tock.
[1:13:46] SPEAKER: And we were like, OK, thanks.
[1:13:48] SPEAKER: That clears this up a great deal.
[1:13:49] SPEAKER: So I always thought tick tock was backwards anyway,
[1:13:53] SPEAKER: because isn't tock supposed to be the...
[1:13:56] SPEAKER: Oh, no, let's not get through this.
[1:13:58] SPEAKER: Yeah, I think we got into that with the Intel people.
[1:14:00] SPEAKER: Yeah, people were trying to argue that the tock was the next generation
[1:14:03] SPEAKER: and the tick was the evolved version.
[1:14:05] SPEAKER: Or like, what are you talking about? That is backwards.
[1:14:07] SPEAKER: We had the stupidest conversation with a really smart person
[1:14:10] SPEAKER: about this at one point.
[1:14:11] SPEAKER: And I don't I like at the end of it, everybody was like, I have regrets.
[1:14:14] SPEAKER: Let's just never mention this again.
[1:14:16] SPEAKER: Yeah, yeah, yeah, let's talk about something else.
[1:14:18] SPEAKER: Yeah, I think the thing is, is that for for many years,
[1:14:22] SPEAKER: I mean, like the way I step back and look at it, when Ryzen when Ryzen hit, we had
[1:14:29] SPEAKER: like we had like core wars of like, hey, how many cores can you get?
[1:14:33] SPEAKER: Right. And I think we're we've I mean, there's maybe talk about
[1:14:38] SPEAKER: whatever the next version might be able to scale up to more cores.
[1:14:42] SPEAKER: But for the most part, we've settled at there's a lot of cores.
[1:14:46] SPEAKER: We have a lot of cores.
[1:14:47] SPEAKER: We should probably figure out efficiency.
[1:14:50] SPEAKER: We should figure out scheduling, things like that.
[1:14:52] SPEAKER: So I feel like a lot of the a lot of that is swung back in that direction.
[1:14:57] SPEAKER: Lunar Lake was a big part of it.
[1:14:59] SPEAKER: Obviously, Qualcomm, you know, with
[1:15:03] SPEAKER: with their Snapdragon elite stuff was pushing for it.
[1:15:07] SPEAKER: AMD, you know, definitely continues to refine that stuff.
[1:15:11] SPEAKER: So I yeah, I think like that's what we're looking at for for a good while.
[1:15:18] SPEAKER: It's kind of refining efficiency, which is a big deal.
[1:15:22] SPEAKER: And honestly, like, yes, there was a lot of stuff
[1:15:25] SPEAKER: that scratched heads around Air Lake on the desktop.
[1:15:29] SPEAKER: But if there's one thing you can say is that, hey, it was more efficient.
[1:15:34] SPEAKER: So, yes, maybe it wasn't the top of the gaming charts,
[1:15:37] SPEAKER: but it used way less power and used less heat or produced less heat.
[1:15:43] SPEAKER: And like like, yeah, that doesn't look sexy on the back of a box.
[1:15:46] SPEAKER: But I mean, that's I'm OK with that.
[1:15:48] SPEAKER: That's totally that's a big deal for me.
[1:15:50] SPEAKER: So I will absolutely I'll absolutely take like 90 percent of the performance
[1:15:54] SPEAKER: or like 60, 70 percent of the power consumption of the of the high end,
[1:15:57] SPEAKER: like the market leader, like 100 percent all the time now. Yeah.
[1:16:01] SPEAKER: Like that's that's that's exciting to hear,
[1:16:03] SPEAKER: because those have been the pain points of the last few years. Right.
[1:16:06] SPEAKER: Like scheduling being a mess on on Ryzen's and Intel.
[1:16:11] SPEAKER: It's a mess everywhere through the roof.
[1:16:12] SPEAKER: Like CPUs have kind of not been in a great place this decade
[1:16:15] SPEAKER: in a lot of ways to me.
[1:16:16] SPEAKER: And it sounds like these are the growing pains that needed to happen
[1:16:20] SPEAKER: for these new paradigms to really take hold and mature.
[1:16:24] SPEAKER: Yeah, the big two, like I asked Rajshree about the thread scheduler.
[1:16:28] SPEAKER: One of the things I hadn't really fully understood
[1:16:30] SPEAKER: is that that's a kind of conversation between the CPU and the OS,
[1:16:33] SPEAKER: not just the CPU saying this, because no one has complete
[1:16:38] SPEAKER: a complete picture, like neither side has a complete picture.
[1:16:42] SPEAKER: And and her take was that they were pretty long way
[1:16:45] SPEAKER: along the way of making that process.
[1:16:48] SPEAKER: Like they've gotten most of the pain points out of that from their perspective.
[1:16:52] SPEAKER: Also, at the end of the day, though, and they kept hammering home,
[1:16:55] SPEAKER: like they're they're just providing hints to the OS. Yeah.
[1:16:59] SPEAKER: Hints. That's not a conversation.
[1:17:01] SPEAKER: That's that's a hint. That's true.
[1:17:02] SPEAKER: Like like like that. That feels very.
[1:17:04] SPEAKER: Yeah. Like, oh, you know what?
[1:17:05] SPEAKER: This is what we think you should do.
[1:17:06] SPEAKER: But they did say at the end of the day, the scheduling is on the operating system.
[1:17:12] SPEAKER: And because Will and I are our Linux experts now,
[1:17:15] SPEAKER: we actually did get to ask some questions of like, hey, does
[1:17:17] SPEAKER: how does the scheduling work on Linux versus Windows and things like that?
[1:17:23] SPEAKER: Her answer was it really depends on which version of the of the kernel
[1:17:26] SPEAKER: you're using, because the newer ones are pretty good and the older ones are kind of bad.
[1:17:30] SPEAKER: So, yeah, I can I can tell you as somebody who followed the kernel mailing list
[1:17:33] SPEAKER: for several months, watching Intel engineers send patches for for big little core scheduling.
[1:17:39] SPEAKER: That's yeah. Yeah.
[1:17:41] SPEAKER: So it was it was really fascinating.
[1:17:43] SPEAKER: I have a better understanding of how this stuff works.
[1:17:45] SPEAKER: I came out with the big takeaway for me
[1:17:49] SPEAKER: is that they're still sticking with the big little cores.
[1:17:52] SPEAKER: The little cores are getting more competent all the time.
[1:17:55] SPEAKER: And the big cores are, you know,
[1:17:59] SPEAKER: like I used to think the big cores were the interesting thing.
[1:18:01] SPEAKER: Now I'm kind of on team little core for the way that I work most of the time.
[1:18:05] SPEAKER: And like I almost given the opportunity, I would probably buy an oops,
[1:18:09] SPEAKER: all ecores CPU before these weird hybrid architectures to simplify things.
[1:18:15] SPEAKER: Yeah, like I'm very excited about the prospects of Wildcat Lake,
[1:18:18] SPEAKER: which I know that's all rumors.
[1:18:20] SPEAKER: You guys can't speak to that because obviously Intel isn't going to confirm.
[1:18:22] SPEAKER: They didn't talk about any of that.
[1:18:24] SPEAKER: Yeah, but the rumors about that.
[1:18:25] SPEAKER: I'm looking at that for like a router or whatever and thinking, like,
[1:18:28] SPEAKER: could you just disable the p cores on that and just use the LPE cores?
[1:18:32] SPEAKER: Because those are plenty fast now and.
[1:18:34] SPEAKER: Well, and remember when Alder Lake came out and it was the first time
[1:18:38] SPEAKER: they had the performance cores and efficiency cores.
[1:18:44] SPEAKER: I can't remember who had brought it up,
[1:18:46] SPEAKER: but somebody said that they equated the ecores
[1:18:50] SPEAKER: to the performance of a 9900K p core.
[1:18:55] SPEAKER: And I don't remember the generation.
[1:18:57] SPEAKER: It was like Skylake.
[1:18:58] SPEAKER: It was that was the thing I always heard was that the Alder Lake ecores
[1:19:02] SPEAKER: were roughly the performance of like the cores of a 6700K or a 6500K,
[1:19:06] SPEAKER: which is like, yeah, that's still not that old of a CPU.
[1:19:11] SPEAKER: And I mean, yeah, that's what's in my machine.
[1:19:13] SPEAKER: Right. Is it 9900K? Yeah. Yeah.
[1:19:16] SPEAKER: And I did try to ask and I don't remember the answer.
[1:19:19] SPEAKER: Now I'd have to go back and look at my notes.
[1:19:20] SPEAKER: I don't have them right here, but I did try to ask, like, hey, what are what is
[1:19:24] SPEAKER: the what is the the processing grunt of an ecore right now equate to?
[1:19:28] SPEAKER: Like how many generations back do we need to go to?
[1:19:31] SPEAKER: That's a great question.
[1:19:32] SPEAKER: The p core. And I think he said Alder Lake p core.
[1:19:36] SPEAKER: No, he said he said the IPC is Raptor Lake.
[1:19:41] SPEAKER: Oh, no, no. I didn't write down what the answer was.
[1:19:45] SPEAKER: I have I have your question.
[1:19:47] SPEAKER: And I did not write down the answer because I'm a dope.
[1:19:49] SPEAKER: What you're saying is basically
[1:19:50] SPEAKER: which generations p core is equal to the current generation ecore. Exactly.
[1:19:54] SPEAKER: Yeah. If I remember correctly, it was somewhere around like 12th gen.
[1:19:57] SPEAKER: Like, yeah, that's crazy.
[1:19:59] SPEAKER: That is crazy. Yeah.
[1:20:00] SPEAKER: And on a smaller process.
[1:20:03] SPEAKER: Yeah. No, you know, way more like the idea of
[1:20:06] SPEAKER: a way more power efficient, say, like four core little box
[1:20:09] SPEAKER: that is as fast as an Alder Lake would have been.
[1:20:11] SPEAKER: But with way, way less power consumption like that, we're really in like a
[1:20:15] SPEAKER: we're a golden age for like home networking tinkerer types. Oh, yeah.
[1:20:20] SPEAKER: Buy a bunch of cheap little powerful low power boxes and do fun stuff with them.
[1:20:24] SPEAKER: Well, and really like and that's like imagine
[1:20:28] SPEAKER: imagine chips that are all oops, all low power ecores. Yes. Right.
[1:20:32] SPEAKER: Like you actually have three sizes, of course.
[1:20:35] SPEAKER: So that's that's that's the rumor of what wildcat.
[1:20:38] SPEAKER: That's if you look at all the wildcat like leaks.
[1:20:41] SPEAKER: It's like two pea cores, four LPE cores.
[1:20:44] SPEAKER: And that's why I'm thinking, can you just disable those pea cores
[1:20:46] SPEAKER: and just roll with a quad core that's like close to an older lake, apparently.
[1:20:51] SPEAKER: So those LPE cores are all on the are on the I/O die,
[1:20:55] SPEAKER: which is where the memory controller and all that, the MPU and all that crap is.
[1:20:58] SPEAKER: And they're clocked lower.
[1:20:59] SPEAKER: Yeah, you know, the next next two or three years
[1:21:01] SPEAKER: going to be very exciting for new CPUs from the sound of things.
[1:21:04] SPEAKER: I think so. Yeah.
[1:21:05] SPEAKER: Well, except for at the end of the day.
[1:21:07] SPEAKER: And this is what we're talking about with this thread scheduling thing.
[1:21:10] SPEAKER: It all depends on the OS, because if Windows still has issues with scheduling,
[1:21:16] SPEAKER: you know, there's only so much Intel and AMD and Qualcomm can do.
[1:21:21] SPEAKER: I've heard there are other operating systems that might be able to help.
[1:21:24] SPEAKER: Yeah. Yeah. Run cache 2025.
[1:21:26] SPEAKER: I'm talking about free BSD now.
[1:21:28] SPEAKER: Year of Linux, baby.
[1:21:31] SPEAKER: You know, actually, the year of the free BSD desktop is coming.
[1:21:35] SPEAKER: Yeah. No. Well, actually, this is a real quick side before we get out of here.
[1:21:39] SPEAKER: We had a friend of the show, Wendell, from level one techs on on Tool Boot Diaries.
[1:21:45] SPEAKER: Trust me, I listened to that episode.
[1:21:47] SPEAKER: I love Wendell. I love Wendell.
[1:21:49] SPEAKER: I have to speak to Wendell now because half the shit he was talking about
[1:21:52] SPEAKER: is like extremely stuff I want to pick his brain about.
[1:21:55] SPEAKER: You have to talk to Wendell. Yeah.
[1:21:58] SPEAKER: And one of the things he was talking about was that
[1:22:01] SPEAKER: because, you know, he does a lot of consulting and stuff for corporations.
[1:22:06] SPEAKER: That's kind of his main stuff.
[1:22:08] SPEAKER: The YouTube, the level one stuff is just the fun side stuff, which is crazy.
[1:22:13] SPEAKER: But he was saying that actually because of all this stuff
[1:22:16] SPEAKER: that's going on with with Windows and Microsoft kind of,
[1:22:20] SPEAKER: you know, hitting the rake really hard, that
[1:22:24] SPEAKER: stepping on the rake or what is the rake like stepping on the rug?
[1:22:28] SPEAKER: Yeah. And then it just.
[1:22:29] SPEAKER: Oh, OK. Yeah, sorry.
[1:22:32] SPEAKER: That that that actually, you know, it's not so much the year of Linux,
[1:22:36] SPEAKER: which I mean, we are seeing some some play on that, obviously.
[1:22:40] SPEAKER: But he's seeing a lot of people move over to Mac OS that secretly this is actually
[1:22:45] SPEAKER: this could be the year of Mac OS, because that that's a better
[1:22:49] SPEAKER: or that's a safer place for people to land because they probably
[1:22:53] SPEAKER: already have an iPhone.
[1:22:54] SPEAKER: So they're like, oh, I hate this Windows stuff.
[1:22:57] SPEAKER: I'm just going to go over to Mac.
[1:22:58] SPEAKER: So what I'm saying is that we need to make a Mac podcast, apparently.
[1:23:02] SPEAKER: Oh, yeah. I use I use and quite enjoy a MacBook Pro.
[1:23:07] SPEAKER: Mac OS. I don't want to go back.
[1:23:09] SPEAKER: It's for professionals.
[1:23:10] SPEAKER: I don't want to go back. Mac OS is an excellent offer.
[1:23:12] SPEAKER: And my Mac OS is more Unix than Linux is.
[1:23:14] SPEAKER: You're more low. OK, well, now I'm in. Yeah.
[1:23:17] SPEAKER: Have you ever tried to load Linux on a Mac?
[1:23:20] SPEAKER: Somebody else? Yes. Yeah, I've got I've got Fedora running on my old.
[1:23:23] SPEAKER: I have a very old 2011 MacBook Air that's running Fedora just fine.
[1:23:27] SPEAKER: My girlfriend uses for light tasks that are pretty good.
[1:23:31] SPEAKER: We should have her on the Dolby Diaries.
[1:23:33] SPEAKER: My Mac is a it's an M1, which compatibility
[1:23:37] SPEAKER: with with the ARM Macs is a little bit more limited right now.
[1:23:40] SPEAKER: Like there's a Sahi Linux, which is a good chunk of the way there.
[1:23:43] SPEAKER: But there's still quite a bit of hardware
[1:23:45] SPEAKER: that doesn't work with ARM Macs and Linux yet.
[1:23:48] SPEAKER: But again, I mean, whatever we're getting way off topic here and you have to go.
[1:23:51] SPEAKER: But like Mac OS has enough of the common POSIX Unix like stuff in it.
[1:23:56] SPEAKER: But I don't need Linux on a MacBook like Mac OS is good for that.
[1:24:00] SPEAKER: It does all the same shit.
[1:24:01] SPEAKER: Dolby Diaries season three, baby. That's right. That's right.
[1:24:04] SPEAKER: We'll talk about the Mac.
[1:24:06] SPEAKER: Let's talk about my Mac OS package manager.
[1:24:09] SPEAKER: Haiku year two, Mac OS year three.
[1:24:14] SPEAKER: BSD year four, year four.
[1:24:16] SPEAKER: And then compile your own kernel year five.
[1:24:19] SPEAKER: Like getting to roll your own Linux year five. Yeah, perfect.
[1:24:23] SPEAKER: Great. Thanks for coming by, Adam.
[1:24:25] SPEAKER: Always a pleasure to see you.
[1:24:26] SPEAKER: It's nice to finally get to do a podcast with you.
[1:24:28] SPEAKER: I've been a big fan for a long time and really appreciate your time
[1:24:32] SPEAKER: over there, PC World and The Full Nerd.
[1:24:35] SPEAKER: For folks who don't know, because I'm bad at telling them
[1:24:37] SPEAKER: where can they find you and your work?
[1:24:40] SPEAKER: Yeah, so I am the head of video at PC World and The Full Nerd.
[1:24:45] SPEAKER: So go over to PC World's YouTube channel.
[1:24:47] SPEAKER: Go over to The Full Nerd Network, which is a series of podcasts.
[1:24:52] SPEAKER: We have The Full Nerd podcast where we talk about
[1:24:55] SPEAKER: DIY desktop computing and all that fun stuff.
[1:24:58] SPEAKER: I have a podcast with Will talking about Linux called The Dual Boot Diaries.
[1:25:02] SPEAKER: I have a third podcast coming up talking about tiny computing platforms.
[1:25:08] SPEAKER: So handhelds, mini PCs, laptops, retro devices, things like that.
[1:25:14] SPEAKER: So look forward to that.
[1:25:16] SPEAKER: Is the retro stuff that we did with
[1:25:19] SPEAKER: I don't want to say who, but is that going on Full Nerd or PC World?
[1:25:22] SPEAKER: That's going on PC World, Retro Roadshow.
[1:25:25] SPEAKER: Yeah, Retro Roadshow brought a TI 99 4A and a B-Box,
[1:25:29] SPEAKER: the PowerPC B-Box, BOS box buy, so we could get hands on with those.
[1:25:35] SPEAKER: And there's videos of both of those coming shortly.
[1:25:37] SPEAKER: I just watched the newest cut today.
[1:25:40] SPEAKER: Is it good? Yeah, they turn it out real good.
[1:25:42] SPEAKER: I think people are really going to like these historical deep dives.
[1:25:45] SPEAKER: I really got to nerd out on stuff I'd never.
[1:25:47] SPEAKER: Well, one of those machines I spent a lot of time with, one of them
[1:25:49] SPEAKER: I spent no time at all with and was really excited about.
[1:25:51] SPEAKER: So but it started your career, started my career.
[1:25:53] SPEAKER: Yeah, exactly. Look forward to that.
[1:25:55] SPEAKER: Anyway, thanks. Thanks, Adam.
[1:25:56] SPEAKER: Thanks for coming by.
[1:25:57] SPEAKER: And we'll see you see you next week on the Full Nerd.
[1:26:00] SPEAKER: Bye. Next time I'll have a beard.
[1:26:02] SPEAKER: Hopefully, I hope so.
[1:26:03] SPEAKER: There's no video here, so I don't know if you have a beard or not.
[1:26:06] SPEAKER: Yeah. Thanks, dude.
[1:26:10] SPEAKER: Thanks for coming by, Adam.
[1:26:12] SPEAKER: Please check out the Full Nerd and Dual Boot Diaries.
[1:26:14] SPEAKER: They're both, you know, I think they're good podcasts.
[1:26:17] SPEAKER: I'm on both of them, but but definitely go check out
[1:26:21] SPEAKER: the stuff on the PC World YouTube channel if you like computer stuff.
[1:26:24] SPEAKER: I listened to DBD Weekly at this point, it seems.
[1:26:28] SPEAKER: It's I feel like for so many years, the rule was, oh,
[1:26:31] SPEAKER: you don't have to listen to your friend's podcast.
[1:26:33] SPEAKER: And then I never do.
[1:26:35] SPEAKER: Yeah, I almost never do.
[1:26:36] SPEAKER: Like I'm trying to think like
[1:26:37] SPEAKER: I listen to the Andor run of a more civilized age earlier this year.
[1:26:41] SPEAKER: Yeah. And now I'm listening to this and that might be it.
[1:26:45] SPEAKER: But apologies to all of my other friends who do podcasts.
[1:26:48] SPEAKER: But I think those are the only friend casts I have ever listened to.
[1:26:52] SPEAKER: I listen to more friend casts when I'm in the car a lot,
[1:26:54] SPEAKER: when I have a lot of commuting to do or when I'm driving to L.A. or something.
[1:26:58] SPEAKER: But but yeah, for the most part, it's it's AMCA.
[1:27:02] SPEAKER: And then a couple of tech podcasts.
[1:27:03] SPEAKER: But if you if you like the show and you want to support the show,
[1:27:07] SPEAKER: we are listening to support it.
[1:27:08] SPEAKER: We don't take money for ads. We don't take money other places.
[1:27:12] SPEAKER: We only take money from you, the listener, because that's who we want to work for.
[1:27:15] SPEAKER: And you can do that.
[1:27:16] SPEAKER: You can give us money by going to patreon dot com slash tech pod
[1:27:20] SPEAKER: where five bucks will buy you access to the Discord,
[1:27:24] SPEAKER: which is full of nerds that talk about stuff like we talk about on the tech pod
[1:27:27] SPEAKER: all day, as well as the monthly patron exclusive episode where this month
[1:27:33] SPEAKER: I feel like we recorded that yesterday
[1:27:35] SPEAKER: and we just kind of talked about like Halloween decorations and other like
[1:27:40] SPEAKER: we were kind of all over the place, but it was a fun, rambly conversation.
[1:27:43] SPEAKER: Fixing inflatable decoration.
[1:27:45] SPEAKER: Yeah, probably some Linux in there.
[1:27:48] SPEAKER: Homeschooling. Yeah. Yeah.
[1:27:51] SPEAKER: Working on your house. Yeah.
[1:27:53] SPEAKER: House projects. Yeah, that's probably up by now.
[1:27:56] SPEAKER: Oh, yeah. Yeah, you can get that now.
[1:27:57] SPEAKER: If you if you suddenly get all of them, there's like 70 of them.
[1:28:00] SPEAKER: If you want more tech fun.
[1:28:01] SPEAKER: Yeah. So that'll do it for us.
[1:28:04] SPEAKER: As always, thanks to everybody who subscribes at patreon dot com slash check.
[1:28:08] SPEAKER: But a very special thank you to our executive producer, dear patrons,
[1:28:11] SPEAKER: including Jason Lee and Felicitous Rips.
[1:28:14] SPEAKER: Andrew Slosky, Jordan Lippett, celebrating 40 years of bunny crimes.
[1:28:19] SPEAKER: Congratulations. Bunny crimes.
[1:28:20] SPEAKER: Twinkle Twinkie, David Allen, James Cammack and Pantheon
[1:28:23] SPEAKER: makers of the HS three high speed 3D printer.
[1:28:25] SPEAKER: Thank you all so, so much. Thank you.
[1:28:28] SPEAKER: And that'll do it for us this week.
[1:28:29] SPEAKER: We'll be back next week with another edition of the tech pod.
[1:28:31] SPEAKER: Until then, please consider the environment before printing this podcast,
[1:28:35] SPEAKER: which we also talked about last week.
[1:28:41] SPEAKER: [BLANK_AUDIO]
