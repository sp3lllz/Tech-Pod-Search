---
episode: 314
title: 304: Gamify Your Sleep
date: 2025-09-14
guests: none
duration: 1:13:14
---

[00:00] SPEAKER: All right. I need some advice. I have a PC question for you and also for our audience.
[00:04] SPEAKER: I'm just going to kind of crowdsource the advice here a little bit because I can't screw this up.
[00:08] SPEAKER: Yeah. The personal computer. I can help you with that.
[00:10] SPEAKER: Yes. The IBM compatible.
[00:12] SPEAKER: Yeah.
[00:12] SPEAKER: Okay. I'm sure you must have tried this at some point in the past.
[00:16] SPEAKER: I need to power some hard drives hooked up to a computer, but not off the power supply
[00:21] SPEAKER: running that computer.
[00:22] SPEAKER: Yeah. You can buy a thing that does that. I have it right here.
[00:25] SPEAKER: No, no, no, no. You're okay for the audio listeners out there, which is a hundred percent of you.
[00:31] SPEAKER: The thing you just held up is some kind of like SATA to USB-C thing.
[00:36] SPEAKER: Yeah. You plug it to USB-C into the computer and then you just jam the other end into the,
[00:40] SPEAKER: into the butt of your hard drive.
[00:41] SPEAKER: Also, this is four hard drives and I think they might be 7,200 RPM. So that might not cut it.
[00:46] SPEAKER: So you get four of those.
[00:48] SPEAKER: Okay. I've got an extra ATX power supply.
[00:50] SPEAKER: Okay. You can do that.
[00:53] SPEAKER: This is like weirdly hard to research or I have not been able to find a lot of like very
[00:56] SPEAKER: definitive. Yes, this is how you do this. But what I've gathered looking online is that you can plug
[01:01] SPEAKER: the drives into the ATX power supply and just bridge those two pins, right? The, whatever,
[01:07] SPEAKER: whichever two pins it is on the 24 pin ATX connector, you can just kind of jump it.
[01:11] SPEAKER: Yeah. So I used to do that with a paperclip. You'd cut a piece of paperclip off and fold
[01:15] SPEAKER: it over and jam it across the two pins.
[01:17] SPEAKER: So I don't even have to do that. I've got my, my good seasonic power supply came with
[01:21] SPEAKER: like an official one of those that you plug into the thing that.
[01:24] SPEAKER: A jumper. Does it have a resistor on to put a little bit of load on it too?
[01:27] SPEAKER: I don't know about that.
[01:29] SPEAKER: So I was gonna say the thing, the thing that I would do is I'm sure somebody makes one. I have,
[01:33] SPEAKER: I don't actually own one, but I'm sure somebody makes a thing that you plug into the ATX connector
[01:38] SPEAKER: that does the jump or puts a switch across those, across those pins and also puts a resistor. So you
[01:45] SPEAKER: get a load on whatever rail you're, because, because the thing, and it may not be a problem
[01:49] SPEAKER: on new power supplies, but at least in the old days, you always had to make sure you put a
[01:53] SPEAKER: resistor on, on that. Cause if you ran the power supply without any load on or with too low a load,
[01:58] SPEAKER: then bad things would happen.
[02:00] SPEAKER: What kind of bad things? So this is, this is what I'm worried about.
[02:02] SPEAKER: You'd kill the power supply.
[02:03] SPEAKER: Oh, okay. This is what I'm worried about. Cause it's for basically brand new hard drives. It's
[02:07] SPEAKER: the ones I bought last year on Black Friday sales and stuff. I'm finally three years after I bought
[02:12] SPEAKER: that USB enclosure to do backups from my server. And I think, I think that enclosure has been
[02:18] SPEAKER: sitting here on the floor for three years. Sometimes they just have to age.
[02:22] SPEAKER: I think that's my project for while we're off from next Lander next week. Cause I'm
[02:26] SPEAKER: finally going to start doing those raspberry PI backups down the hall of my NAS Smiley.
[02:30] SPEAKER: Can I ask a stupid question?
[02:32] SPEAKER: Yes.
[02:33] SPEAKER: Why don't you just use the USB enclosure?
[02:35] SPEAKER: Cause it's incredibly slow. Incredibly slow.
[02:38] SPEAKER: Oh.
[02:39] SPEAKER: So this is something I found out. I think, did I talk about this?
[02:42] SPEAKER: We talked about this. Yeah.
[02:44] SPEAKER: No, this detail though. I don't know if I ever circled back around and
[02:47] SPEAKER: told you this detail is USB three, our drive enclosure. It takes four drives and they're
[02:52] SPEAKER: like SATA connections and it's got a SATA controller in it that they plug into. I could
[02:56] SPEAKER: never figure out why that thing was so slow. And then at some point I looked at the specs
[02:59] SPEAKER: and realized that it's SATA two.
[03:02] SPEAKER: That shouldn't make that much of a difference though.
[03:03] SPEAKER: You wouldn't think it would make that much of a difference, but it totally does.
[03:06] SPEAKER: Well, yeah. Does it, does it like do some weird striping across the drives or does each drive
[03:11] SPEAKER: show up as its own device when you plug it in?
[03:13] SPEAKER: It's J bod. It's just the drives to show up to the operating system. So that's fine.
[03:17] SPEAKER: But I'm talking like four times slower than running the drive straight off of the motherboard
[03:23] SPEAKER: SATA controller.
[03:24] SPEAKER: So, I mean, this thing was $8 and you could just buy four of them. It does say it works
[03:28] SPEAKER: with any hard drive. So it gets enough power to spin the metal.
[03:31] SPEAKER: I've got this extra. I've got a very nice extra ATX power supply just sitting right here.
[03:36] SPEAKER: Okay. Well, I mean, so yeah. So then in that case you, you get a big resistor and a couple
[03:41] SPEAKER: of wires and a paperclip and you're good to go. Just make sure you, you, you're really,
[03:46] SPEAKER: really sure which pin is the one pin when you're counting.
[03:50] SPEAKER: Cause if you jam them in the wrong ones, the magic smoke comes out.
[03:53] SPEAKER: Well, I think that tester only goes on one way. It's the, the, the thing that came with
[03:57] SPEAKER: my other power supply. Like I think it only goes in one way. So that's fine.
[04:01] SPEAKER: Are you using it with the power supply it came with?
[04:04] SPEAKER: Yes.
[04:05] SPEAKER: Okay. Then you're good to go.
[04:06] SPEAKER: Like do I time it with the boot of the machine? I guess if the SATA ports are set to hot pluggable
[04:11] SPEAKER: in the UEFI, it should be okay to just power them up whenever.
[04:15] SPEAKER: I would turn the secondary power supply on first and then turn the computer on.
[04:19] SPEAKER: Really?
[04:20] SPEAKER: Yeah. But also why don't you just plug it into your main power supply?
[04:24] SPEAKER: Cause I'm out of SATA. This is in my server that already has 10 hard drives in it.
[04:28] SPEAKER: Oh, that's too many hard drives, Brad.
[04:30] SPEAKER: That's a lot. Well, so what if that was about to be 16 hard drives? That's even more.
[04:34] SPEAKER: That's too many hard drives, Brad.
[04:36] SPEAKER: Well, look, when you insist on mirroring everything, the drive count goes up rapidly.
[04:41] SPEAKER: Fair.
[04:43] SPEAKER: How do I turn it off? Do I just flip the rocker switch on the power supply when I'm done?
[04:48] SPEAKER: Just unplug it.
[04:50] SPEAKER: Well, I could just turn the switch off if I'm going to do that.
[04:52] SPEAKER: I mean, flip the switch off. Yeah. The same thing.
[04:54] SPEAKER: Do I shut the machine? Like same, like inverse of the question I just asked about booting up.
[04:58] SPEAKER: Do I shut the main machine down first and then power off the drives or?
[05:02] SPEAKER: I mean, I would just unmount those drives and do the safe eject thing and then
[05:07] SPEAKER: yank the power.
[05:08] SPEAKER: But I don't, I mean, SATA is supposed to be hot pluggable, but I'm always a little bit hinky
[05:13] SPEAKER: about that unless it's in a hot plug rack or something.
[05:17] SPEAKER: Like I said, I really hope to hear from some people on the Discord who have done something
[05:21] SPEAKER: like this before I try this.
[05:24] SPEAKER: So the safe way to do it is to turn off the server first and then turn off the drive power.
[05:31] SPEAKER: Yeah.
[05:32] SPEAKER: Because the drives can spin without any data connection on them. There's no problem.
[05:36] SPEAKER: Okay. All right.
[05:37] SPEAKER: Yeah. Like I said, I'll, I'll wait for, for feedback from the audience before I try this,
[05:41] SPEAKER: but I'm.
[05:42] SPEAKER: Or you could buy this little guy.
[05:43] SPEAKER: Gonna try this.
[05:44] SPEAKER: It's pretty good.
[05:46] SPEAKER: I used it to back up a whole bunch of crappy old SSDs.
[05:49] SPEAKER: I mean, does that just spin up the drive?
[05:50] SPEAKER: Well, yeah, you probably haven't even tried that with a hard drive.
[05:52] SPEAKER: Like, I don't, I don't know that that really fixes my problem though, of powering drives
[05:56] SPEAKER: off of something other than the computer that's running them, but still got the weird sync stuff.
[06:01] SPEAKER: Look, I think you could just get rid of your USB cage and just plug those into four of
[06:06] SPEAKER: those into, into the Raspberry Pi.
[06:08] SPEAKER: With what?
[06:09] SPEAKER: And leave it dangling.
[06:10] SPEAKER: With what?
[06:11] SPEAKER: Wait, is that, is that, is that power and data over USB-C?
[06:14] SPEAKER: Power and data over USB-C. Yeah.
[06:15] SPEAKER: I don't, what am I going to plug four USB-Cs and two on a Raspberry Pi?
[06:19] SPEAKER: Well, you get an A to C hub.
[06:21] SPEAKER: I don't think that hub is going to supply power to run four hard drives.
[06:26] SPEAKER: You just, look, Brad, life finds a way.
[06:28] SPEAKER: Okay.
[06:28] SPEAKER: I will, I will make this work.
[06:31] SPEAKER: I'm going to make a JBOD with four of these and a whole bunch of old SSDs.
[06:34] SPEAKER: I'll let you know how it goes.
[06:35] SPEAKER: All right.
[07:04] SPEAKER: Welcome to Brad and Will Made in Tech Pod.
[07:06] SPEAKER: I'm Will.
[07:07] SPEAKER: Hi Brad.
[07:08] SPEAKER: See, I was just going to talk about blueberry muffins.
[07:10] SPEAKER: Blueberry muffins as opposed to raspberry pies?
[07:12] SPEAKER: Look, my wife went to the grocery store and she got these Dolly Parton branded flavored,
[07:17] SPEAKER: I guess.
[07:18] SPEAKER: Dolly Parton flavored blueberry muffins.
[07:20] SPEAKER: We got to stop talking about food items flavored by people.
[07:25] SPEAKER: I mean, it just says, hold on, I'm going to look it up.
[07:28] SPEAKER: It's Dolly Parton.
[07:30] SPEAKER: Dolly Parton branded, not Dolly Parton flavored.
[07:32] SPEAKER: Thank you.
[07:33] SPEAKER: Well, I'm sorry, the Selena Gomez ones did not say branded.
[07:35] SPEAKER: It just said flavored.
[07:37] SPEAKER: Yeah, I know.
[07:38] SPEAKER: This one says it's Dolly Parton's blueberry muffin and bread mix.
[07:41] SPEAKER: And I will tell you, pretty baller blueberry muffins.
[07:44] SPEAKER: Oh, this is Duncan Hines.
[07:46] SPEAKER: It's a Duncan Hines mix.
[07:47] SPEAKER: It's like a cake mix.
[07:48] SPEAKER: It's like a Dolly Parton special edition blueberry muffin.
[07:51] SPEAKER: It's a collab, I think.
[07:54] SPEAKER: How is it?
[07:54] SPEAKER: It's fantastic.
[07:55] SPEAKER: It was really, I ate two of them.
[07:57] SPEAKER: I was like, I'm gonna have a muffin.
[07:58] SPEAKER: And then the muffin was so good.
[07:59] SPEAKER: It was gone.
[08:00] SPEAKER: So I horked down another one before the podcast real quick.
[08:02] SPEAKER: So I'm double muffin Friday over here.
[08:05] SPEAKER: All right.
[08:06] SPEAKER: Okay.
[08:06] SPEAKER: Well, you're fueled up and ready to talk about mobile devices.
[08:10] SPEAKER: Yeah.
[08:11] SPEAKER: I mean, I guess I should have technically had an apple muffin.
[08:15] SPEAKER: Nobody makes computers named blueberries anymore.
[08:17] SPEAKER: But there aren't a lot of apple muffin recipes out there, are there?
[08:21] SPEAKER: I've never seen an apple muffin.
[08:22] SPEAKER: Usually they're branny.
[08:24] SPEAKER: Yeah, there's like cranberry.
[08:26] SPEAKER: It's applesauce muffins.
[08:28] SPEAKER: Trying to think of other fruit muffins.
[08:30] SPEAKER: So I do an applesauce, like a dark, like dark flower brand kind of muffiny deal.
[08:38] SPEAKER: Sometimes those are pretty delish.
[08:39] SPEAKER: That sounds all right.
[08:40] SPEAKER: They're real moist, but they're not appley.
[08:42] SPEAKER: I think apple is usually streusel.
[08:44] SPEAKER: And you know, your Danish is an apple Danish.
[08:48] SPEAKER: Sometimes I like a donut, an apple cinnamon donut filled with the goop.
[08:54] SPEAKER: How about an apple watch?
[08:57] SPEAKER: I mean, I would watch an apple.
[08:59] SPEAKER: That's what you're saying to see what happens.
[09:01] SPEAKER: Like the other day I pulled out a parking space.
[09:03] SPEAKER: There was one behind me and I almost ran over it with the car.
[09:05] SPEAKER: And I was like, oh no, I don't want to do that.
[09:06] SPEAKER: Then my tires will be slippery.
[09:08] SPEAKER: That would be bad.
[09:08] SPEAKER: Yeah.
[09:09] SPEAKER: But I think you're talking about apple cores, apple watch.
[09:14] SPEAKER: I'm sorry.
[09:14] SPEAKER: The new one.
[09:15] SPEAKER: Apple cores.
[09:17] SPEAKER: Isn't it called apple core?
[09:18] SPEAKER: I think we're torturing this fruit.
[09:20] SPEAKER: Yeah, I know.
[09:20] SPEAKER: Sorry.
[09:21] SPEAKER: Look, I'm on iced coffee.
[09:23] SPEAKER: So I don't drink as much coffee before we start the podcast right now.
[09:25] SPEAKER: That's fair.
[09:26] SPEAKER: I woke up at four thirty this morning.
[09:28] SPEAKER: So I'm also a little ragged, but we were talking about what to do for the topic this
[09:33] SPEAKER: week and the apple event happened and you suggested it.
[09:35] SPEAKER: And I was like, oh, you feel like apple stuff is like kind of whatever these days.
[09:41] SPEAKER: Do we really need to cover another apple thing?
[09:43] SPEAKER: And then I actually started looking through all these products and I was like,
[09:45] SPEAKER: oh, this actually seems like a pretty strong year for refreshes of apple stuff.
[09:49] SPEAKER: There's actually a lot to talk about here.
[09:50] SPEAKER: I mean, I think so.
[09:52] SPEAKER: Yeah.
[09:52] SPEAKER: The TLDR is that they did their normal September event the other day and they
[09:55] SPEAKER: announced the usual slate of phones, plus a new phone that we've never seen before.
[10:00] SPEAKER: It's then spoilers, I guess.
[10:04] SPEAKER: And then they they're updating that AirPod Pro three with some stuff that's interesting
[10:08] SPEAKER: as a as a person who uses AirPod Pro two's every single day.
[10:13] SPEAKER: And then the watch updates kind of, I think the most map part of the whole thing.
[10:16] SPEAKER: I mean, well, doesn't know.
[10:18] SPEAKER: I mean, it's not there's nothing radical about it, but it's I might be enough to
[10:22] SPEAKER: make me get this watch.
[10:23] SPEAKER: So their core message are on the Apple watches.
[10:26] SPEAKER: If you don't buy this, you're going to die.
[10:28] SPEAKER: That's quite how they presented it, but sure.
[10:31] SPEAKER: Like, look, man, the opening segment for this, the opening video for this scene is
[10:35] SPEAKER: a whole bunch of people in like medical distress who or who made hiking mistakes,
[10:41] SPEAKER: whose lives were then saved by their Apple watches.
[10:44] SPEAKER: I don't usually do this for these apple episodes,
[10:46] SPEAKER: but I watched the entirety of the presentation last night.
[10:49] SPEAKER: Yeah, that segment on Apple Watch saved my life was like.
[10:54] SPEAKER: The most like sort of hard string tugging.
[10:58] SPEAKER: I mean, look, I guess Apple Watch will if you don't buy this, you will die is better
[11:02] SPEAKER: than buy this or we'll kill you.
[11:04] SPEAKER: So like, good job, Apple.
[11:06] SPEAKER: It still feels a bit much.
[11:10] SPEAKER: They're adding a couple of new sensors that are like the the one of the big themes was,
[11:16] SPEAKER: hey, we're adding machine learning, not necessarily generative AI, but machine learning,
[11:21] SPEAKER: plus stuff that we're already doing or two modified sensors or two new sensors to get
[11:26] SPEAKER: some new juice out of the old the old devices.
[11:29] SPEAKER: One of those things is a high blood pressure test suite thing.
[11:34] SPEAKER: It's not exactly a blood pressure sensor, but they're using the cameras and the watch
[11:38] SPEAKER: to detect how the actual blood flows through your veins to detect.
[11:43] SPEAKER: I assume they're looking for like second order.
[11:49] SPEAKER: Second order indicators of blood high blood pressure, right, rather than putting the cuff
[11:53] SPEAKER: on your arm and actually measuring the temperature, the pressure at which you have to squeeze
[11:59] SPEAKER: the arm before blood stops coming through.
[12:01] SPEAKER: You're not getting what I can never remember is it was a systolic, systolic and diastolic
[12:06] SPEAKER: or those systolic and diastolic are the two things.
[12:09] SPEAKER: You're not getting the two numbers out of this, to be clear.
[12:11] SPEAKER: But also, I think that they said they definitely were quick to say like, this will not detect
[12:17] SPEAKER: all instances of hypertension, but it will catch a lot of them.
[12:20] SPEAKER: Yeah, the idea is it's the same reason that when you go to the dentist, they always check
[12:24] SPEAKER: your blood pressure.
[12:24] SPEAKER: It's because most people who have high blood pressure don't realize they have high blood
[12:28] SPEAKER: pressure until after it should already have been treated.
[12:30] SPEAKER: Yeah.
[12:31] SPEAKER: And so, yeah, it seems like there's like more and more thought in the medical community
[12:36] SPEAKER: that high blood pressure contributes to like a lot more other bad conditions than maybe
[12:42] SPEAKER: was previously understood.
[12:43] SPEAKER: That's entirely possible.
[12:45] SPEAKER: Like I've seen it referenced in regards to dementia, for example.
[12:49] SPEAKER: Oh, yeah.
[12:50] SPEAKER: And things like that.
[12:51] SPEAKER: It's like things you wouldn't expect, you know, beyond just like heart attack and stuff.
[12:54] SPEAKER: Yeah.
[12:55] SPEAKER: So it could actually be pretty good, a pretty good thing to have.
[12:58] SPEAKER: I mean, honestly, this is one of the things as somebody who has a family history of high
[13:01] SPEAKER: blood pressure and takes my blood pressure at least once a month at home with a meter
[13:06] SPEAKER: on the advice of my medical professionals.
[13:10] SPEAKER: This is a compelling like a blood pressure sensor is really interesting in the watch.
[13:15] SPEAKER: The thing that they're doing where they like over a period of time give you a notification
[13:20] SPEAKER: if they think you should go have it checked out isn't exactly what I'm looking for.
[13:23] SPEAKER: I actually was hoping that they would have something that gives me the numbers that I'm
[13:26] SPEAKER: supposed to send to my doc that I'm supposed to track to make sure I don't need to call
[13:29] SPEAKER: my doctor.
[13:30] SPEAKER: Right.
[13:30] SPEAKER: Yeah.
[13:30] SPEAKER: I mean, I think that's probably just outside the scope of what something like this can
[13:33] SPEAKER: do on your wrist.
[13:35] SPEAKER: Yeah. And, and like in reality, I, I got a prescription for a thing that was a hundred
[13:40] SPEAKER: bucks, I think that I just, I charge like once a year and I put it on my watch.
[13:45] SPEAKER: I put it on my, my arm.
[13:46] SPEAKER: It puffs up the, it gives the number on my phone and then, you know, it tells me when
[13:51] SPEAKER: I need to call the doctor.
[13:54] SPEAKER: They're doing more sleep stuff, which I thought was interesting.
[13:56] SPEAKER: Yeah, is the sleep score thing new?
[13:58] SPEAKER: Cause like they've been doing sleep tracking for a while, but is it like gamify your sleep
[14:03] SPEAKER: as you've written in the notes?
[14:04] SPEAKER: Yeah, they gamify your sleep.
[14:06] SPEAKER: Is that, that's, that has not been done before?
[14:10] SPEAKER: They would give you a graph before.
[14:11] SPEAKER: So if you look at your, if you go to your health app on your phone, you would get this
[14:15] SPEAKER: graph that has like it's four colors.
[14:19] SPEAKER: It's red, light blue, medium blue, and purple.
[14:22] SPEAKER: And they indicate the different stages of sleep.
[14:24] SPEAKER: And it kind of shows you where you are in different stages based on the time of night.
[14:30] SPEAKER: So you can see like, Oh, I woke up at two o'clock in the morning to pee last night,
[14:33] SPEAKER: right?
[14:34] SPEAKER: When you look at this graph, the new thing is that they give you a sleep score on a daily
[14:39] SPEAKER: basis that tells you, Hey, last night I scored 20 to 20 for interruptions.
[14:45] SPEAKER: I woke up twice and I was up for two minutes total and then went right back to sleep, which
[14:50] SPEAKER: you know, pretty normal.
[14:51] SPEAKER: There was a garbage truck that came by at four o'clock in the morning and I had to pee
[14:53] SPEAKER: at two o'clock in the morning.
[14:55] SPEAKER: Does that thing ever show you wake ups that you don't remember?
[14:57] SPEAKER: Like obviously you get up to go pee, you remember that, but like, do you, do you see periods
[15:01] SPEAKER: of wakingness on there that you were not aware of at the time?
[15:05] SPEAKER: I mean, look, my lawyers advised me not to answer this question.
[15:10] SPEAKER: But no, I, I don't, I don't actually look at it all that often.
[15:13] SPEAKER: Okay.
[15:14] SPEAKER: And I'm, I am an incredibly light sleeper usually.
[15:17] SPEAKER: So like when my wife comes to bed or when my wife gets up to go to the bathroom or like,
[15:22] SPEAKER: like the garbage truck, three streets over drives by or some kid blows by on a motorcycle
[15:27] SPEAKER: at 60 miles an hour, I'm going to wake up.
[15:30] SPEAKER: Whether I get out of bed or not, like it seems to be tied to movement.
[15:34] SPEAKER: So like, obviously if I get up and get out of bed, then it's going to change.
[15:38] SPEAKER: That also does, it's also always tracks stuff like your breathing rates and stuff like that
[15:43] SPEAKER: while you're asleep, your heart rate while you're asleep, maximum maxes and mins.
[15:47] SPEAKER: But so the new thing is, is this score where it just says, Hey, last night you slept four
[15:52] SPEAKER: hours and 19 minutes.
[15:53] SPEAKER: That's a 23 out of 50.
[15:54] SPEAKER: That wasn't great.
[15:56] SPEAKER: So like last night, I'm going to give my actual numbers here.
[16:00] SPEAKER: I guess.
[16:01] SPEAKER: Good job me.
[16:02] SPEAKER: I put the iOS beta on my phone the other day so that I could do this.
[16:05] SPEAKER: You're welcome America.
[16:06] SPEAKER: Oh, I got a 23 out of 50 because my duration was only four hours and 19 minutes for total
[16:12] SPEAKER: sleep.
[16:12] SPEAKER: Wait, I'm sorry.
[16:13] SPEAKER: Is this the sleep score that you're talking about?
[16:14] SPEAKER: This is the sleep score.
[16:15] SPEAKER: Yeah.
[16:15] SPEAKER: Oh, so does this, this is not limited to the new watch?
[16:19] SPEAKER: No.
[16:19] SPEAKER: So this is just a feature of, of, and I actually, I don't even have the new OS on the watch.
[16:25] SPEAKER: This is just using the old OS on the watch on the new OS on the phone.
[16:28] SPEAKER: They did not make it clear that this is just rolling out to everybody.
[16:31] SPEAKER: It's weird how they act like things are new features for the devices that maybe are just
[16:36] SPEAKER: features for the entire line.
[16:39] SPEAKER: I got a 30 out of 30 because my bedtime was only two minutes later than average.
[16:44] SPEAKER: And I got a 20 out of 20 because I only had two interruptions to wake up.
[16:47] SPEAKER: So two minutes total.
[16:49] SPEAKER: So your sleep is just so.
[16:53] SPEAKER: I only knocked down a 73.
[16:55] SPEAKER: The interesting thing is I was able to go back and pull, like, I can see my old data
[16:59] SPEAKER: from previous weeks and like, I never hit excellent.
[17:03] SPEAKER: I'm never an excellent sleeper.
[17:04] SPEAKER: Apparently my highest score is an 87 on Friday, August 1st.
[17:10] SPEAKER: So I guess that was a restful night for me.
[17:12] SPEAKER: Now something to aspire to.
[17:14] SPEAKER: Yeah.
[17:15] SPEAKER: I think it's awesome that they do this.
[17:17] SPEAKER: I cannot go to bed and I cannot sleep with a watch on.
[17:20] SPEAKER: So I will never benefit from this, but it's cool.
[17:22] SPEAKER: They do it.
[17:23] SPEAKER: I it's funny.
[17:25] SPEAKER: I slept with the watch for years and years and years.
[17:27] SPEAKER: And I used to have that soft stretchy wristband, the non-plastic one.
[17:33] SPEAKER: And that one was fabulous for sleeping with.
[17:36] SPEAKER: The one I have now is a little less good, but it turns out I don't mind.
[17:39] SPEAKER: I don't sleep with the watch every night anymore though.
[17:40] SPEAKER: It's like maybe twice a week.
[17:42] SPEAKER: It yells at me.
[17:43] SPEAKER: Yeah.
[17:45] SPEAKER: I had the last thing real quick on the health tip before we talk about the hardware improvements.
[17:49] SPEAKER: This is actually from last month, but they apparently have finally settled this patent
[17:54] SPEAKER: dispute over the blood oxygenation feature.
[17:56] SPEAKER: Remember that they took out of, I think it was series nine and 10.
[18:00] SPEAKER: It's in seven and eight, nine and 10.
[18:02] SPEAKER: I think I have an eight and it's still got the blood ox, but I forget what the ins and
[18:06] SPEAKER: outs of it were.
[18:07] SPEAKER: There was some medical device company that they got into a patent dispute with.
[18:11] SPEAKER: Yeah.
[18:11] SPEAKER: They tried to buy a company if I recall.
[18:13] SPEAKER: And then the company said, no, we don't want to get bought.
[18:15] SPEAKER: So they just reinvented their technology and broke their patents.
[18:17] SPEAKER: And then the company sued them and it's been tied up in court.
[18:20] SPEAKER: Yeah.
[18:20] SPEAKER: Yeah.
[18:20] SPEAKER: Anyway, so they, they have brought the blood ox feature back to all watches, I guess, that
[18:25] SPEAKER: lasted, including this new one.
[18:27] SPEAKER: That's nice.
[18:28] SPEAKER: It's unclear how they, they, they, I think they described it as redesigned as the term
[18:31] SPEAKER: they use and it's unclear to me how they got around this patent issue.
[18:35] SPEAKER: It sounds like maybe they shunted the processing off to your phone as a way of circumventing
[18:39] SPEAKER: the patent.
[18:40] SPEAKER: Like maybe, maybe the, maybe the patent was for like the wearable itself does the processing.
[18:43] SPEAKER: So now, now it seems like the watch reports all the data to your phone to do the blood
[18:49] SPEAKER: ox calculation.
[18:50] SPEAKER: Ah, yes.
[18:50] SPEAKER: A loophole.
[18:51] SPEAKER: I'm not clear if you can still just see the number on your watch, like you used to be
[18:55] SPEAKER: able to.
[18:56] SPEAKER: So that might be a bit of a downgrade.
[18:57] SPEAKER: I'm not clear, but at least it's back in some form, which is nice.
[19:00] SPEAKER: I'll be honest.
[19:01] SPEAKER: The only time I've ever really used that is the first time I had COVID when I was really
[19:05] SPEAKER: sick and my wife was trying to stay out of the room that I was in and I just shared the
[19:11] SPEAKER: blood ox data with her so she could look at it when it, when it ran.
[19:15] SPEAKER: And then, then I didn't, she didn't have to worry about it.
[19:17] SPEAKER: And I didn't have to worry about it.
[19:18] SPEAKER: It was really good.
[19:19] SPEAKER: That's neat.
[19:19] SPEAKER: That's that's, that is a futuristic scenario that you just described.
[19:23] SPEAKER: That's, that's cool.
[19:23] SPEAKER: I mean, yeah, I've not used it often for anything particularly actionable about, but hey, it
[19:29] SPEAKER: sucks losing functionality that you used to have.
[19:31] SPEAKER: So it's nice that it's nice that it's back.
[19:33] SPEAKER: Sometimes I like to see how high I can make the number go.
[19:35] SPEAKER: Yeah.
[19:36] SPEAKER: My number, my biggest number is a hundred.
[19:38] SPEAKER: Yeah, that's turns out.
[19:40] SPEAKER: Yeah, that's about as high as you can go.
[19:41] SPEAKER: Yeah.
[19:42] SPEAKER: Can't beat a hundred percent, I guess.
[19:43] SPEAKER: I don't know that you can oversaturate your blood.
[19:46] SPEAKER: So they have three new watches.
[19:48] SPEAKER: Apple watch 11, Apple watch ultra three, Apple watch se three.
[19:54] SPEAKER: They kind of seem like they're all basically the same watch this go round.
[19:59] SPEAKER: What do you mean?
[20:00] SPEAKER: Or like, or they all seem very iterative on their previous incarnations.
[20:03] SPEAKER: If that's what you mean.
[20:04] SPEAKER: Yeah.
[20:04] SPEAKER: Well, okay.
[20:05] SPEAKER: So the, the, the, another one of the overarching themes is they're putting ceramic, uh, ceramic
[20:11] SPEAKER: shield too.
[20:11] SPEAKER: I think they call it.
[20:14] SPEAKER: So has ceramic shield been term that Apple, that's there.
[20:19] SPEAKER: That's there.
[20:19] SPEAKER: Hey, we took the hard glass and then did some ionization business to make it harder.
[20:23] SPEAKER: And now they're now, guess what, Brad?
[20:25] SPEAKER: What's that even harder than it was before.
[20:28] SPEAKER: Yeah, they, they, they definitely like three different times in that presentation talk
[20:33] SPEAKER: about how the ceramic, the ceramic layer bonds with the glass at the atomic level.
[20:38] SPEAKER: Well, that, that, that makes, I mean, if you're ionizing the glass or whatever I look, man,
[20:42] SPEAKER: they name stuff weird.
[20:44] SPEAKER: Okay.
[20:44] SPEAKER: Yeah, they do.
[20:46] SPEAKER: So the thing though that I noted, I don't believe what the watch is that they didn't
[20:50] SPEAKER: say the word ceramic shield like they did with all the iPhone models.
[20:53] SPEAKER: They did.
[20:54] SPEAKER: They definitely talked about ceramic coating on the watch glass, but they did not actually
[20:58] SPEAKER: use the, they didn't use the ceramic shield term there.
[21:01] SPEAKER: I don't think they use capital C, capital S ceramic shield around the watch, but they
[21:04] SPEAKER: did say, they did say they're doing the ceramic layer on the watch now.
[21:08] SPEAKER: And they said, they said the new watch glass is two times as scratch resistant as the 10
[21:12] SPEAKER: was, which is good for me because my eight is scratched to hell.
[21:15] SPEAKER: Yeah.
[21:15] SPEAKER: I mean, they get, they get scratched and there's not really a way you can put a screen protector
[21:19] SPEAKER: on because of the curved nature of the.
[21:21] SPEAKER: Yeah.
[21:21] SPEAKER: I wouldn't want to anyway, honestly.
[21:24] SPEAKER: Look, I don't mind a little bit of a screen protector, but but yeah.
[21:28] SPEAKER: So yeah, you're right. There is no ceramic shield mentioned on the Apple watch page.
[21:31] SPEAKER: I don't know if that's actually notable, but it kind of jumped out to me and I liked it.
[21:35] SPEAKER: You know, if the two X number can be believed, that seems pretty good.
[21:38] SPEAKER: Cause like I said, mine, my three year old watch is pretty dinged up at this point.
[21:43] SPEAKER: I mean, they look, it takes a beating mine.
[21:45] SPEAKER: I'm on a watch that I think is a year older than yours.
[21:48] SPEAKER: And I'm, this is the first one I've looked at and thought, oh, maybe I should upgrade,
[21:51] SPEAKER: but I think I'm going to go another.
[21:52] SPEAKER: I think I'm going to, I think I'm going to ride this one down until they stop doing updates
[21:56] SPEAKER: for it.
[21:56] SPEAKER: And then I'll buy another one.
[21:57] SPEAKER: That's valid.
[21:58] SPEAKER: The thing for me is that last year it got thinner and a bigger screen.
[22:02] SPEAKER: Yeah.
[22:02] SPEAKER: And so like thinner, bigger screen, way more scratch resistant.
[22:07] SPEAKER: And the other one is that they are now claiming 24 hours of battery life instead of 18.
[22:12] SPEAKER: Yeah.
[22:12] SPEAKER: Like all of those together is like pretty compelling to me.
[22:16] SPEAKER: So it's, it's funny because mine has almost always given me 24 hours of battery.
[22:21] SPEAKER: Like I often will put mine in, I guess with the, with the fast charge,
[22:26] SPEAKER: my use is that usually when I'm in the shower, I put it on the charger when I'm wearing it
[22:29] SPEAKER: around the clock.
[22:30] SPEAKER: Oh, sure.
[22:30] SPEAKER: And that's usually enough to get me where I need to be.
[22:32] SPEAKER: Yeah.
[22:32] SPEAKER: It's, it's not, battery life's not a huge problem for me.
[22:35] SPEAKER: I have gotten to the point where I'm, if I have like a long exercise day, like if I'm
[22:39] SPEAKER: out for like an hour and I listen to podcasts straight off the watch, which is like Bluetooth
[22:44] SPEAKER: audio and it's doing position tracking and exercise tracking and stuff.
[22:49] SPEAKER: Like I, I'm definitely having days where I'm below 10% by the time I put it back on the
[22:53] SPEAKER: charger.
[22:53] SPEAKER: If on days that I go on long walks and actually hit the button that says, Hey, do you want
[22:58] SPEAKER: to record an outdoor walk?
[22:59] SPEAKER: And it does heart rate and all that while I'm exercising.
[23:02] SPEAKER: It's a, it's you're, you're absolutely right.
[23:04] SPEAKER: That's what that definitely hits him more.
[23:05] SPEAKER: So having a little extra buffer would be nice.
[23:07] SPEAKER: I mean, it's not a deal breaker, but like all of these improvements together are maybe
[23:11] SPEAKER: enough for me to, cause I use the watch constantly.
[23:13] SPEAKER: I really it's like kind of core to my daily operation.
[23:17] SPEAKER: It's funny because for me, it's just a thing that buzzes when I need to look at the phone
[23:20] SPEAKER: most of the time.
[23:21] SPEAKER: That's actually like my least favorite feature of the watch.
[23:26] SPEAKER: I've actually thought about moving all notifications back to the phone, but well, I mean, look,
[23:31] SPEAKER: look, it's it's it's mostly when I'm out, like if I'm in the PC world officer in the
[23:36] SPEAKER: studio or something, I have it set so that it pings when my wife or daughter texts me
[23:40] SPEAKER: pretty much.
[23:41] SPEAKER: And that's it.
[23:42] SPEAKER: And and I don't miss those anymore, which is nice.
[23:45] SPEAKER: Let's see.
[23:45] SPEAKER: They also added a new modem, which they're saying is more efficient, gives better
[23:51] SPEAKER: coverage on the cellular models.
[23:53] SPEAKER: Is this the first time it's had 5g?
[23:55] SPEAKER: They kind of made it sound that way.
[23:57] SPEAKER: I think so.
[23:58] SPEAKER: I don't, I don't, I don't know that it matters for the watch.
[24:01] SPEAKER: Well, it only matters in so far as like, that's what's more, maybe more available now.
[24:05] SPEAKER: Well, I guess LTE is probably going to be with us for quite a while as a fallback, but
[24:10] SPEAKER: like it's to me, it's more about like what has better signal coverage?
[24:14] SPEAKER: Like what are you going to get a better experience with as opposed to like raw speed?
[24:19] SPEAKER: Yeah.
[24:20] SPEAKER: A hundred, a hundred percent.
[24:23] SPEAKER: It's interesting.
[24:24] SPEAKER: They didn't talk about using, so they developed their own modem this spring.
[24:27] SPEAKER: And as far as I know, this is, they didn't say that this is their modem.
[24:30] SPEAKER: This is still somebody else's modem.
[24:34] SPEAKER: I assume it's Qualcomm.
[24:35] SPEAKER: Yeah.
[24:35] SPEAKER: It's going to have to be a different design in a package.
[24:38] SPEAKER: The small, obviously, than what's in the phone.
[24:40] SPEAKER: Well, maybe.
[24:42] SPEAKER: But yeah, I would assume that at some point in the future, all of the cellular modems
[24:46] SPEAKER: will be Apple designed across their entire product line.
[24:49] SPEAKER: Absolutely.
[24:50] SPEAKER: Sure.
[24:50] SPEAKER: They are moving in that direction for the watches as well.
[24:53] SPEAKER: There's two finishes, aluminum and titanium.
[24:56] SPEAKER: The aluminum is in black, silver, rose gold and gray.
[25:00] SPEAKER: Yeah.
[25:01] SPEAKER: The titanium is natural golden slate and they're not the shiny titanium.
[25:05] SPEAKER: They're the, they're the kind of natural finished titanium, like the iPhone 15 and 16.
[25:10] SPEAKER: What is, is titanium harder than aluminum?
[25:12] SPEAKER: What's the advantage?
[25:13] SPEAKER: Titanium is harder and lighter and it doesn't bend very much.
[25:17] SPEAKER: It's very, very, uh, uh, it has high tensile strength.
[25:21] SPEAKER: I think is what that's called.
[25:22] SPEAKER: I can't remember.
[25:23] SPEAKER: Apple watch three is 800.
[25:26] SPEAKER: Sorry.
[25:26] SPEAKER: That starts at 400 bucks and goes out three ultra three.
[25:29] SPEAKER: Yeah.
[25:30] SPEAKER: Um, 800 bucks.
[25:32] SPEAKER: It's the same big flat screen as the last one.
[25:34] SPEAKER: It looks like it's a little bit thinner.
[25:36] SPEAKER: They say it's bigger and brighter.
[25:38] SPEAKER: It has satellite connectivity that you can send messages with now if you have a cellular
[25:42] SPEAKER: plan, which is kind of nice.
[25:43] SPEAKER: Yeah.
[25:43] SPEAKER: That's been on the phone for a while, right?
[25:46] SPEAKER: Yeah.
[25:46] SPEAKER: But I think this is the first time it's been on the watch alone and it's up to 42 hours
[25:50] SPEAKER: of battery now.
[25:51] SPEAKER: Other than that, it seems kind of the same.
[25:52] SPEAKER: That's 42 hours of battery is kind of crazy, but I mean, most people don't need that.
[25:57] SPEAKER: But that's 42 hours in like full power mode.
[25:59] SPEAKER: If you put it in low power mode, it goes even longer.
[26:00] SPEAKER: Oh wow.
[26:01] SPEAKER: Yeah.
[26:02] SPEAKER: So that's, I mean, that, that thing feels like it's actually made for people who are
[26:05] SPEAKER: doing straight up outdoor adventuring type stuff.
[26:08] SPEAKER: Or people who work in technology.
[26:11] SPEAKER: Brad, you know, I see a lot of them just walking around San Francisco.
[26:14] SPEAKER: I get it.
[26:14] SPEAKER: I, I continue to really like the flat screen on that thing.
[26:19] SPEAKER: Yeah.
[26:19] SPEAKER: And I, and I much less like the grotesque size of it.
[26:23] SPEAKER: The flat screen is the big draw for me.
[26:26] SPEAKER: And I even less like the grotesque size of the price.
[26:29] SPEAKER: Like I wish, I wish I could get, I wish I could get the price and general size of these
[26:35] SPEAKER: standard like series 11, but with a flat, not the, I mean, I don't mind the, like the
[26:39] SPEAKER: bubble shape glass too much, but I, I kind of like the flat.
[26:43] SPEAKER: Well, the flight glass, you could actually put a screen protector on so it doesn't get
[26:46] SPEAKER: gouged up.
[26:47] SPEAKER: Yeah.
[26:48] SPEAKER: The thing that's interesting.
[26:49] SPEAKER: So this is basically right at the price that the old watches were when they had the stainless
[26:55] SPEAKER: cases.
[26:56] SPEAKER: Right.
[26:56] SPEAKER: Okay.
[26:56] SPEAKER: So like to me, this makes a lot more sense than buying the titanium finish normal Apple
[27:04] SPEAKER: watch, I think.
[27:05] SPEAKER: Sure.
[27:06] SPEAKER: Because you do get that extra battery life and the satellite stuff.
[27:08] SPEAKER: And like, if you want to go scuba diving, you can do that.
[27:11] SPEAKER: Whatever it's just too big for me, I think.
[27:14] SPEAKER: Yeah.
[27:14] SPEAKER: I have dainty girl risks, so I'm not going to probably wear a watch that big.
[27:19] SPEAKER: Apple watch se three starts at 250 bucks.
[27:23] SPEAKER: Seems like pretty big upgrade here.
[27:24] SPEAKER: That's got the same chip as the other two now.
[27:26] SPEAKER: Yeah.
[27:26] SPEAKER: So this is, I want to say they do this every three years.
[27:29] SPEAKER: It seems like now maybe four years.
[27:30] SPEAKER: Cause my daughter got an se two the year that we got one of those for her the year it came
[27:35] SPEAKER: out.
[27:37] SPEAKER: And yeah, it's an S 10 chip always on screen.
[27:40] SPEAKER: Finally, for that, the old ones didn't have an always on screen battery life was kind
[27:44] SPEAKER: of always a problem on it.
[27:46] SPEAKER: It has all the gestures that the newer watches have now, which it hasn't had recently.
[27:50] SPEAKER: And it gets the sleep apnea and sleep score and temperature sensing and fall detection
[27:54] SPEAKER: and all the stuff that's on the newer model Apple watches.
[27:56] SPEAKER: It's carried forward into the 11 and the ultra three.
[27:59] SPEAKER: Does it, does it have all the health stuff?
[28:00] SPEAKER: Like the hypertension, probably not.
[28:05] SPEAKER: They didn't say anything about the hypertension.
[28:06] SPEAKER: I think it has the stuff.
[28:08] SPEAKER: I think it's basically the last year stuff, not this year stuff because sleep apnea was
[28:12] SPEAKER: the last year thing.
[28:13] SPEAKER: I believe sure.
[28:14] SPEAKER: 18 hour battery life.
[28:15] SPEAKER: It has fast charging now, which is the big deal.
[28:17] SPEAKER: The old one was a slow charger, like the Apple series one and newer and newer charger speed.
[28:23] SPEAKER: So it took like two hours to charge overnight.
[28:26] SPEAKER: The fast charging means you get like eight hours and 15 minutes, which is nice.
[28:30] SPEAKER: And it comes in starlight and midnight, which I guess are dark and light versions.
[28:35] SPEAKER: I don't know.
[28:35] SPEAKER: I don't think you can get a cell modem with that either.
[28:37] SPEAKER: That's the big, that's the big differentiator.
[28:40] SPEAKER: Got it.
[28:42] SPEAKER: And, and as always, it's like the small one is 250 and the big one is a hundred bucks
[28:46] SPEAKER: more, I believe.
[28:47] SPEAKER: So, so that's it.
[28:48] SPEAKER: That's watches.
[28:49] SPEAKER: They're like, I don't know.
[28:52] SPEAKER: I, the, the, I was, I was hoping the blood pressure was going to be more thinner, better,
[28:59] SPEAKER: smaller, whatever.
[29:00] SPEAKER: Seems fine.
[29:01] SPEAKER: If you don't have a watch, get a watch.
[29:02] SPEAKER: If you, if you don't want to watch, that's fine.
[29:04] SPEAKER: Seems like a good time to get in.
[29:05] SPEAKER: If you don't have, I'm, I'm, I'm on the fence.
[29:07] SPEAKER: I might get this one or I might try to squeeze one more year out, but this, this feels like
[29:12] SPEAKER: a good solid all around upgrade.
[29:14] SPEAKER: Yeah.
[29:14] SPEAKER: It's not bad.
[29:15] SPEAKER: AirPod pro three.
[29:16] SPEAKER: This is my favorite Apple product.
[29:18] SPEAKER: I think right now, pretty, pretty, pretty wide margin.
[29:21] SPEAKER: They're saying that the audio sounds better, which they do every time I'll let you know
[29:25] SPEAKER: when I get a pair and I'll tell you how they actually sound.
[29:28] SPEAKER: You don't say our sound producing device has better sound this time.
[29:31] SPEAKER: The big claim is that they're say they're active noise canceling is two, two times better
[29:35] SPEAKER: than the pro two, which is already kind of remarkable.
[29:39] SPEAKER: Like the pro two.
[29:41] SPEAKER: I don't, I'm afraid to use the noise canceling when I'm like out in public for fear that
[29:46] SPEAKER: I won't hear a bus or something coming up on me.
[29:48] SPEAKER: Wow.
[29:48] SPEAKER: It's really good at filtering background stuff.
[29:53] SPEAKER: The transparency mode is incredible on those.
[29:56] SPEAKER: It doesn't sound like you have headphones in that are piping things through.
[29:59] SPEAKER: It just sounds like what's outside.
[30:01] SPEAKER: The big change on that is that you're getting your own voice now through that as well.
[30:05] SPEAKER: So it should be, my guess is it's going to be indistinguishable from not having AirPods
[30:10] SPEAKER: in.
[30:10] SPEAKER: Wait, what does the transparency filter or like, how does it determine what the lead
[30:16] SPEAKER: through and whatnot?
[30:16] SPEAKER: So there's three modes, right?
[30:18] SPEAKER: Transparency is, it works like your ears don't have anything in them.
[30:22] SPEAKER: It's letting everything through.
[30:23] SPEAKER: It lets everything through.
[30:24] SPEAKER: I think, I think it'll reduce volume.
[30:26] SPEAKER: You can set it to reduce volume of loud sounds.
[30:28] SPEAKER: If you don't want to get hearing damage.
[30:30] SPEAKER: There's the noise canceling, which is the don't let anything through, right?
[30:33] SPEAKER: And that means it's hard to hear people talking to you.
[30:36] SPEAKER: I sometimes, if I'm having trouble, if I want to take a nap and the house is loud, I'll
[30:39] SPEAKER: put those in in the afternoon and then people have to come touch me because they can't
[30:43] SPEAKER: talk to me from the door basically.
[30:45] SPEAKER: And then the third one is the adaptive mode, which kind of splits the difference and it
[30:50] SPEAKER: uses some processing on the device to decide what to let through and what to filter.
[30:54] SPEAKER: So like traffic noise, water, water running, wind noise, stuff like that gets filtered
[31:02] SPEAKER: out.
[31:03] SPEAKER: But the, but the, it detects voices and sends them through.
[31:08] SPEAKER: The active noise canceling is, I, so I might, I might also, I've been waiting on a third
[31:12] SPEAKER: gen pod pro to buy in and the active noise canceling is like the reason I want them.
[31:19] SPEAKER: I think basically I'm still using corded Bose noise canceling headphones on flights.
[31:24] SPEAKER: And I think my last trip, I finally reached the end of my patients for corded headphones
[31:29] SPEAKER: on a flight.
[31:30] SPEAKER: So I, yeah, I bought a pair of the twos four years ago, I think when they, when they were,
[31:35] SPEAKER: when they came, like I bought them the day they came out cause I'd been waiting and the
[31:41] SPEAKER: ANC is as good as anything.
[31:42] SPEAKER: Like it's as good as the best Sony stuff I've ever heard.
[31:45] SPEAKER: Okay.
[31:45] SPEAKER: That's, that's a strong endorsement.
[31:46] SPEAKER: I wouldn't have minded maybe a little bit of indication of what their methodology was
[31:51] SPEAKER: for saying, Hey, it's two X better noise canceling than the pro two it's four X better than the
[31:55] SPEAKER: pro one, like maybe some metrics to help underpin that termination would have been nice, but
[32:00] SPEAKER: whatever.
[32:01] SPEAKER: It's well, and also it's weird because when those aren't like, there's no zero point on
[32:07] SPEAKER: those, on those, on those bars, right?
[32:10] SPEAKER: Like there's no, there's no, I guess there's a hundred percent noise reduction and you
[32:15] SPEAKER: can get closer to that bar.
[32:16] SPEAKER: So each time you get closer, it's going to be a smaller, each two X will be a smaller
[32:22] SPEAKER: reduction in noise.
[32:23] SPEAKER: But I, anyway they're apparently, they're designed to fit in your ears better, which
[32:28] SPEAKER: is nice.
[32:29] SPEAKER: I use foam tips on mine instead of the ones, the, the latex ones that they come with or
[32:35] SPEAKER: silicone ones that they come with because the silicone ones irritate my skin and the
[32:38] SPEAKER: foam ones don't.
[32:41] SPEAKER: They've they talked about a lot live translation, which is, which people have Samsung and Google
[32:46] SPEAKER: have both taken a stab at this now.
[32:47] SPEAKER: And both of them were kind of duds by all reports.
[32:50] SPEAKER: Okay.
[32:51] SPEAKER: But the idea is that it filters down the other person's actual voice and you hear a translation
[32:58] SPEAKER: in your language, in your ears moments after they say the thing that they're saying.
[33:06] SPEAKER: You can also pair it with your phone so that you can say things back to the person and
[33:09] SPEAKER: they'll hear that they'll either get a written or spoken description of your, of what you're
[33:14] SPEAKER: saying to them.
[33:16] SPEAKER: And then they did a, they had one part of the video that showed people doing a back
[33:20] SPEAKER: and forth chat where everybody involved was wearing AirPod Pros and they were all hearing
[33:24] SPEAKER: one guy was speaking Portuguese and the other guy was speaking in English and everybody
[33:28] SPEAKER: was able to hear everybody in their own language.
[33:31] SPEAKER: And it was magical.
[33:32] SPEAKER: Yeah.
[33:33] SPEAKER: Kind of getting into like the Star Trek universal translator territory.
[33:36] SPEAKER: Kind of, I mean, I don't, I don't believe for a second that this works as seamlessly
[33:41] SPEAKER: as that or, yeah, this, this sounds like a, you know, like you said, kind of a first
[33:45] SPEAKER: gen attempt at something like this.
[33:48] SPEAKER: And you know, it's probably going to be maybe on the AirPod Pro 5 or something is when this
[33:54] SPEAKER: will really reach maturity and be like seamlessly usable.
[33:56] SPEAKER: But you know, it's, it's an interesting idea.
[33:58] SPEAKER: Well, my guess is that it uses the AI acceleration stuff, the neural processing stuff on the
[34:04] SPEAKER: phone.
[34:04] SPEAKER: This isn't actually obviously happening on the earbud itself.
[34:07] SPEAKER: There's no way.
[34:09] SPEAKER: Well, I mean, there, there are ways, but like, I don't, I don't think we're there yet.
[34:13] SPEAKER: And I guess what I mean is I don't, I don't think there's any way they could do it on
[34:16] SPEAKER: the, the, the earbuds in a way that would be acceptable.
[34:19] SPEAKER: Like, I'm sure you could probably do some version of this.
[34:22] SPEAKER: It would just be slow and crappy.
[34:23] SPEAKER: Yeah, but that's what I mean.
[34:24] SPEAKER: Like to kind of achieve the experience that Apple's probably going for.
[34:27] SPEAKER: I'm sure that stuff's going through the phone.
[34:30] SPEAKER: I'm so anyway, I'm curious about, I'm curious about how this works in practice.
[34:35] SPEAKER: I'm, I'm coloring me skeptical here.
[34:38] SPEAKER: Yeah.
[34:39] SPEAKER: They made them smaller.
[34:39] SPEAKER: They fit in your ears better.
[34:41] SPEAKER: There's new sensors on them, including oh, and, and this is one of my favorite topics
[34:48] SPEAKER: that people don't ever think about.
[34:50] SPEAKER: If you design products that fit like the 90th percentile of people, like the 90 most common,
[34:55] SPEAKER: like the most common body shapes and you cut off, you know, 800 million people or something,
[35:02] SPEAKER: they're adding, they're shipping with more tips and design the
[35:06] SPEAKER: AirPods to fit in more people's ears more effectively.
[35:09] SPEAKER: I, and they said it was based on 3d scans of people's ears, which is one of the things
[35:13] SPEAKER: you do when you set up the ANC and transparency mode for the phone, if you want it to work
[35:19] SPEAKER: well.
[35:20] SPEAKER: So you aim your depth camera at the side of your head with your, when you're, when you're
[35:24] SPEAKER: setting them up and it makes a picture of your ear and then changes the way it models
[35:28] SPEAKER: the sound a little bit for that.
[35:31] SPEAKER: But the shipping with five tips is nice.
[35:33] SPEAKER: Cause if you have, if you want your kids to be able to use these, or if you want, if you
[35:37] SPEAKER: have big ear holes, I guess you need bigger and or smaller ear tips.
[35:42] SPEAKER: And it's IP 57 sweat and water resistance, which means don't go in the pool with them.
[35:45] SPEAKER: But if it rains, you're fine.
[35:47] SPEAKER: Is that new?
[35:49] SPEAKER: On this generation, that's new.
[35:50] SPEAKER: They had a lesser version of the water resistance on the previous one.
[35:53] SPEAKER: So IP 48, I think, but I'm not, don't quote me on that.
[35:55] SPEAKER: That's that's like maybe my one reservation for getting these is, I don't know that I
[36:00] SPEAKER: would ever use these for working out.
[36:01] SPEAKER: I would probably stick to my like $30 sound cores that are perfectly fine.
[36:06] SPEAKER: Well, so I would say so I paid for Apple, Apple care on the AirPods last time, mainly
[36:15] SPEAKER: because the batteries get the, I was worried that the batteries were going to conk out
[36:20] SPEAKER: in the ear pods.
[36:21] SPEAKER: They do a good job managing battery with them, doing the slow charge past 80% and only charging
[36:26] SPEAKER: when you need and all that stuff.
[36:29] SPEAKER: I had problems getting one of the AirPods to charge when I went to the, when I was getting
[36:36] SPEAKER: near the end of my Apple care period.
[36:39] SPEAKER: And so I went to the Apple store and they just gave me a brand new one.
[36:41] SPEAKER: I would go to, I would, I would, if you're going to work out, I would pay for Apple care.
[36:44] SPEAKER: If you're not, I probably wouldn't.
[36:46] SPEAKER: So I was going to say it's like $2 a month or something for Apple care on these.
[36:51] SPEAKER: How long does that last?
[36:52] SPEAKER: Is that two years?
[36:53] SPEAKER: Two years.
[36:54] SPEAKER: It was basically the, when I got them, I got them for 50 bucks off and then paid an additional
[36:58] SPEAKER: 50 bucks for Apple care, which meant that I got a free pair at the end of the end of
[37:01] SPEAKER: the two year period.
[37:02] SPEAKER: That's a pretty good deal.
[37:03] SPEAKER: These would probably be for flights and when going around town, probably not for exercise
[37:07] SPEAKER: for me.
[37:09] SPEAKER: I'm going to go ahead and tell you, I use them a lot in the house, hooked up to the
[37:12] SPEAKER: Apple TV when I don't want to make noise and I'm watching TV, which works well.
[37:17] SPEAKER: I'd probably wear them.
[37:18] SPEAKER: I listened to a lot of podcasts around the house doing chores and stuff.
[37:21] SPEAKER: Probably wear them for that too.
[37:22] SPEAKER: Anyway, podcasts, eh?
[37:24] SPEAKER: Keep keeping them clean and nice, you know, for a pair of earbuds this nice, I would want
[37:28] SPEAKER: to keep them in good shape.
[37:29] SPEAKER: But yeah, see, I use them until they explode.
[37:32] SPEAKER: I mean, I've read the AirPod press twos down probably for what it's worth.
[37:37] SPEAKER: Heart rate sensing is neat.
[37:39] SPEAKER: It seems like they, this is all new, right?
[37:41] SPEAKER: It seems like they basically made this so that you don't need a watch or a phone on
[37:45] SPEAKER: you to do the basic fitness tracking anymore.
[37:48] SPEAKER: Well, I mean, you still need a watch to do some of the fitness tracking, but you don't
[37:52] SPEAKER: need a watch to do heart rate sensing.
[37:54] SPEAKER: The heart rate sensing works through.
[37:56] SPEAKER: There's a sensor that touches the skin inside your ears and it works basically the same
[38:00] SPEAKER: way as the Apple Watch version.
[38:03] SPEAKER: The interesting thing is like the Apple Watch one, you have to be kind of still for it to
[38:08] SPEAKER: work because like if you bounce your wrist around too much, it stops working.
[38:11] SPEAKER: Apparently these AirPods are pretty secure in your ears because like I would guess that
[38:16] SPEAKER: they don't move.
[38:16] SPEAKER: They're not super heavy.
[38:17] SPEAKER: I don't know.
[38:18] SPEAKER: I'm curious to see how that works.
[38:19] SPEAKER: Yeah.
[38:19] SPEAKER: The watch sensing is a bit of a problem for me when I exercise because I have to tighten
[38:23] SPEAKER: the band.
[38:24] SPEAKER: Like you said, like I like to keep it a little bit loose around the house where it kind of
[38:27] SPEAKER: slides a little bit, but then it can't read anything if I keep it like that when I'm out
[38:31] SPEAKER: moving around.
[38:31] SPEAKER: So I have to, I have to tighten it basically to the point that my wrist gets incredibly
[38:36] SPEAKER: sweaty with the, um, I have the, what do they call it, sport loop.
[38:40] SPEAKER: It's the, it's like, it's the solid silicone one that like doesn't breathe at all.
[38:45] SPEAKER: So my wrist is just like extremely gross and sweaty by the time I get back.
[38:49] SPEAKER: So I'm getting one of the Velcro nylon loops next time.
[38:52] SPEAKER: Yeah.
[38:52] SPEAKER: So anyway, um, nice to, nice to have this.
[38:56] SPEAKER: I'm trying to like figure out the use case here though.
[38:58] SPEAKER: Like putting all this exercise sensing stuff in the earbuds is cool, but what's the point
[39:05] SPEAKER: of having earbuds if you don't have another device on you anyway to play audio from,
[39:10] SPEAKER: you know?
[39:10] SPEAKER: Well, I think a lot of people do phones and don't, don't have a watch.
[39:13] SPEAKER: Yeah, maybe so.
[39:14] SPEAKER: Yeah.
[39:14] SPEAKER: I mean, I think, I think they're, my guess is that they have some pretty strong data
[39:18] SPEAKER: that getting people into the Apple fitness ecosystem makes them customers for life.
[39:21] SPEAKER: Uh huh.
[39:22] SPEAKER: Therefore more entry points into the Apple fitness ecosystem equals more customers for life.
[39:27] SPEAKER: Now this makes perfect sense.
[39:29] SPEAKER: Um, the battery's better on these.
[39:31] SPEAKER: It's eight hours on a single charge versus I think six previously for the AirPods themselves.
[39:36] SPEAKER: Is that like eight hour hours of playback?
[39:38] SPEAKER: That's eight hours of playback on the air, on the air.
[39:41] SPEAKER: So the, the, for folks who don't know the AirPods, the case has a battery and the each
[39:45] SPEAKER: individual AirPod has a battery that's eight hours on the, on the pods.
[39:50] SPEAKER: You plug it back into the mothership to get, to refill that.
[39:53] SPEAKER: And that usually takes like 15 minutes or something.
[39:55] SPEAKER: It's really fast.
[39:55] SPEAKER: I think that's everything now.
[39:57] SPEAKER: Like I've got, I've got multiple sets of earbuds, like cheaper ones, like from multiple
[40:03] SPEAKER: sources.
[40:03] SPEAKER: And like they all, like everybody has just adopted the Apple style of the cases, the
[40:07] SPEAKER: battery.
[40:09] SPEAKER: And it turns out getting rid of the connection ports on the, using inductive charges, getting
[40:14] SPEAKER: rid of the connection ports is a good way to keep them from getting ruined when they
[40:17] SPEAKER: get wet.
[40:17] SPEAKER: It turns out.
[40:20] SPEAKER: The 10 hours of transparency mode, which it's interesting.
[40:23] SPEAKER: Cause like when I went to see that Taylor Swift concert and I wanted to not blow my
[40:26] SPEAKER: ears out, I just put the AirPods in and put it in the, in the adaptive mode and it let
[40:32] SPEAKER: the music through in it.
[40:33] SPEAKER: And it muffled the sound enough that I wasn't able to like, I didn't have ringing ears
[40:38] SPEAKER: and I could still talk to people around me.
[40:39] SPEAKER: Yeah, that's cool.
[40:41] SPEAKER: We don't have it in the notes, but they mentioned the hearing aid aspect of these as well.
[40:45] SPEAKER: And like the battery is better there as well.
[40:47] SPEAKER: That's the transparency mode stuff.
[40:48] SPEAKER: Yeah, there's no, there's no there's no changes to the hearing aid stuff for this model versus
[40:54] SPEAKER: the previous one.
[40:54] SPEAKER: So if you're using the previous ones, the only difference is the battery life improvement.
[41:00] SPEAKER: And they did talk about a conversation mode change and then didn't reference it again.
[41:03] SPEAKER: So I don't know what that was about.
[41:04] SPEAKER: I couldn't find anything, any follow up about that.
[41:08] SPEAKER: But the conversation mode is, is the thing that focuses it.
[41:13] SPEAKER: It's an adaptive thing that brings human voices to the forefront.
[41:17] SPEAKER: So like if you like, I have trouble picking out people's noises in people's voices, rather
[41:22] SPEAKER: in environments that have a lot of background hubbub, especially if their voices are in
[41:26] SPEAKER: certain ranges.
[41:27] SPEAKER: And this, this uses the adaptive mode to help with that.
[41:31] SPEAKER: Yeah, I think I'm in for these.
[41:33] SPEAKER: Of all the products in this announcement, like I might, I might upgrade my watch.
[41:37] SPEAKER: I might not, but I don't have like nice high quality earbuds.
[41:40] SPEAKER: Mine are all pretty crappy.
[41:41] SPEAKER: You've been AirPod curious for a while.
[41:43] SPEAKER: It's time.
[41:43] SPEAKER: And so here's the other thing, and hopefully we'll get some testing data when these come
[41:49] SPEAKER: out on this, but I would assume the AirPods 2 also are perfectly adequate for this.
[41:55] SPEAKER: It's Switch 2.
[41:56] SPEAKER: That's the other thing or Switch, because the other reason I've clung to my accorded
[42:00] SPEAKER: noise canceling headphones is that the Switch 1 has pretty crappy Bluetooth audio support.
[42:05] SPEAKER: Yeah.
[42:05] SPEAKER: And it was nice to just plug headphones straight into that thing and not have latency and stuff.
[42:09] SPEAKER: But if, if the Switch 2 works well with these, without any real appreciable latency, I am
[42:14] SPEAKER: a hundred percent in because that was kind of my last, that was my last holdout on nice
[42:18] SPEAKER: earbuds.
[42:19] SPEAKER: So I think I've used the Pro 2s with the Switch 2.
[42:23] SPEAKER: The, the one thing you should know about the, the AirPod Pros is because they use their
[42:29] SPEAKER: like semi proprietary layer on top of Bluetooth.
[42:33] SPEAKER: If you start using them with non Apple devices, then it's a little more fiddly to connect
[42:40] SPEAKER: them.
[42:41] SPEAKER: Like if you, if you move from your iPad to your phone, to your TV, to your Mac, and you're
[42:47] SPEAKER: all in the Mac ecosystem, it just goes to whichever device you're using and you don't
[42:51] SPEAKER: have to think about it.
[42:51] SPEAKER: You don't have to do anything.
[42:52] SPEAKER: Yeah.
[42:53] SPEAKER: It's really nice.
[42:53] SPEAKER: Oh my God.
[42:54] SPEAKER: Are you serious?
[42:54] SPEAKER: Cause I have to, my, my little sound cores, I have to, depending on if I want to listen
[42:58] SPEAKER: off the watch or the phone, that's like, takes some very annoying fiddling in the settings.
[43:03] SPEAKER: So that's rad.
[43:04] SPEAKER: Yeah.
[43:04] SPEAKER: So like you just hit the airplay button and pick the AirPods out of the list, including
[43:10] SPEAKER: on the TV.
[43:11] SPEAKER: Like this is what, this is one of the, this is what I love about the Apple TV.
[43:13] SPEAKER: So I've often up at like, I wake up early in the morning and I often want to watch like
[43:16] SPEAKER: TV that Gina is not interested in watching or the kiddo is not interested in watching.
[43:20] SPEAKER: And so I'll load it up in the living room, put the AirPods in, get the full positional
[43:24] SPEAKER: sound and like, I don't make any noise and wake up anybody in the house, which is awesome.
[43:30] SPEAKER: Yeah.
[43:30] SPEAKER: Old guy problems.
[43:32] SPEAKER: Anyway, whatever I can, I can handle some, a little bit of paring fiddliness with the
[43:36] SPEAKER: switch if it works well.
[43:37] SPEAKER: What I was going to say is you should actually look for that in reviews.
[43:40] SPEAKER: Cause they, they have their history of supporting non-Apple products is janky.
[43:44] SPEAKER: Usually they're good on PCs and phones.
[43:47] SPEAKER: For whatever reason, I could never get my, my AirPod pros to work right with the steam
[43:51] SPEAKER: deck.
[43:53] SPEAKER: Like they just don't want to pair with the Bluetooth and the steam deck, which is entirely
[43:57] SPEAKER: possible.
[43:57] SPEAKER: It's a weird Linux thing on the steam deck side, but anyway, stuff to know about.
[44:01] SPEAKER: Okay.
[44:01] SPEAKER: I'll keep an eye on that.
[44:02] SPEAKER: I'm sure it, you know, it will take any time for people on Reddit to talk about how it
[44:05] SPEAKER: works.
[44:06] SPEAKER: Yeah.
[44:07] SPEAKER: Okay.
[44:07] SPEAKER: So phones, three phones this year.
[44:12] SPEAKER: There's an iPod iPhone.
[44:15] SPEAKER: There's an iPhone.
[44:16] SPEAKER: There's an no iPod.
[44:17] SPEAKER: Sadly, there's an iPhone, there's an iPhone pro with a max version that's the bigger one.
[44:24] SPEAKER: And there's a new one, an iPhone air, which is like a skinny iPhone.
[44:28] SPEAKER: Yeah.
[44:28] SPEAKER: Which has been rumored for like months, if not years at this point.
[44:32] SPEAKER: But here it is.
[44:33] SPEAKER: Yeah.
[44:33] SPEAKER: I think one of the, one of the tech tubers I, I follow, I was watching their coverage
[44:38] SPEAKER: of this.
[44:38] SPEAKER: That was there was like, yeah, this looks like half of a full of a, of a foldable iPhone.
[44:44] SPEAKER: If you're, if you're asking me and I was like, oh wow, okay, here we are.
[44:48] SPEAKER: Okay.
[44:48] SPEAKER: So we're going to run through these pretty quick.
[44:50] SPEAKER: Basically everything has the a 19 processor.
[44:54] SPEAKER: The pro has a pro version.
[44:56] SPEAKER: The air has a pro version.
[44:58] SPEAKER: Both.
[44:58] SPEAKER: So really it's just the base 17 is the only one that has the non-pro.
[45:03] SPEAKER: Yeah.
[45:03] SPEAKER: And the only difference is that the pro has six cores on the, on the iPhone pro, six GPU
[45:09] SPEAKER: cores and the iPhone the 19 pro on the air, I think only has five and the, and the a 19 on the iPhone also only has five cores on the GPU.
[45:20] SPEAKER: Seem like they all have the same CPU cores though.
[45:23] SPEAKER: It's four, it's six cores, two bigs and four littles, which they've been doing for a long time.
[45:27] SPEAKER: They didn't talk about Ram in the keynote.
[45:29] SPEAKER: I don't know if they posted Ram specs, but the rumor I heard is that there's more Ram
[45:32] SPEAKER: and all of these, which makes sense for AI stuff.
[45:37] SPEAKER: So I'd like the TLDR here is that I think that the stock, the base iPhone, these, this
[45:42] SPEAKER: is a huge winner this year because it gets a bunch of previously pro features that they
[45:48] SPEAKER: haven't put on this before.
[45:49] SPEAKER: Yeah, I will, we'll address the E model situation at the end, but I had kind of, I've been on
[45:54] SPEAKER: an SE and kind of, cause I just don't need much in a phone.
[45:58] SPEAKER: And I had been thinking, you know, when I'm done with this, I'll move to the, one of these
[46:01] SPEAKER: new E budget models.
[46:03] SPEAKER: But then I took a look at this thing, A, the E, the 16E that came out earlier this year
[46:07] SPEAKER: is kind of expensive for a quote unquote budget phone.
[46:10] SPEAKER: Yeah.
[46:11] SPEAKER: But also this base 17 has gotten so much stuff that wasn't the pro.
[46:16] SPEAKER: That's it.
[46:17] SPEAKER: That it's actually starting to feel silly.
[46:19] SPEAKER: Maybe it's only an extra like $200 for way more functionality in the camera and the screen
[46:25] SPEAKER: on and on.
[46:26] SPEAKER: Like it's this, this base model is like shockingly kind of generous.
[46:29] SPEAKER: I feel like by Apple standards.
[46:31] SPEAKER: Yeah, I kind of felt like that too.
[46:32] SPEAKER: So other thing is across the line, everything starts at 256 gigabytes now, which is, I think
[46:38] SPEAKER: that feels like the right amount of storage for this.
[46:40] SPEAKER: Yeah.
[46:41] SPEAKER: So a 256 gig, that's what I have now, but 256 base is, is like pretty generous unless
[46:47] SPEAKER: you're shooting like tons of video or whatever.
[46:49] SPEAKER: I feel like.
[46:49] SPEAKER: I think this is maybe the first time they've ever had a base model phone that I wasn't
[46:53] SPEAKER: like, Oh man, that's too small.
[46:54] SPEAKER: Yeah.
[46:55] SPEAKER: Yes.
[46:55] SPEAKER: That's absolutely every single time prior.
[46:57] SPEAKER: It's been like, I don't feel great buying the base storage.
[47:02] SPEAKER: So just to close the loop on the storage stuff though, it seems like there's only one upgrade
[47:07] SPEAKER: option on those iPhone.
[47:08] SPEAKER: Yeah.
[47:09] SPEAKER: The regular iPhone is from 256 to 512.
[47:12] SPEAKER: And that is a $200 upgrade.
[47:14] SPEAKER: Which then puts you in iPhone air and iPhone prime territory.
[47:18] SPEAKER: But it used to, it used to only be a hundred dollars for the first storage upgrade.
[47:21] SPEAKER: So they have not, they've, they've eliminated that option.
[47:24] SPEAKER: Well, look, you go out and buy a, I mean, it's, it's, it's, I used to always hate this
[47:29] SPEAKER: argument because it's kind of specious I thought, but like a 200 to five, the difference in
[47:36] SPEAKER: price between a 256 and a 512 gig SSD, which is essentially what we're talking about here
[47:41] SPEAKER: is not a hundred.
[47:42] SPEAKER: It's not 200 bucks.
[47:43] SPEAKER: The storage upgrade pricing has always felt like a very high, high margin situation.
[47:48] SPEAKER: But of course, cause it's Apple.
[47:50] SPEAKER: Also worth mentioning when you trade the phones back in, they don't ask you what, what, how
[47:55] SPEAKER: much capacity you have.
[47:56] SPEAKER: It's just as the, what model is this and is it is in good condition or bad condition?
[48:00] SPEAKER: You don't say, although it's interesting though, between this base storage upgrade.
[48:03] SPEAKER: And I don't know if you've seen all the, at least MacBook pros.
[48:07] SPEAKER: I'm not sure about errors, but at least the new MacBook pros all started 24 gig now.
[48:11] SPEAKER: Oh, that's that's Ram?
[48:13] SPEAKER: Yes.
[48:14] SPEAKER: I think they started 24.
[48:16] SPEAKER: They have a 24 gig option now, like the point being better.
[48:19] SPEAKER: Yeah.
[48:19] SPEAKER: Yes.
[48:20] SPEAKER: That's what I mean is like the, I feel like the, the insultingly small Ram and storage
[48:24] SPEAKER: base baseline specs that Apple has been kind of notorious for, feels like it's maybe softening
[48:30] SPEAKER: a little bit.
[48:31] SPEAKER: That's good.
[48:33] SPEAKER: So there's no big version of this.
[48:35] SPEAKER: They haven't done that in a couple of years.
[48:36] SPEAKER: Apparently I didn't realize that it seemed like the 15 was the last plus model.
[48:40] SPEAKER: Yeah, it makes sense.
[48:42] SPEAKER: The display gets the 120 Hertz adaptive refresh rate screen.
[48:45] SPEAKER: This is the one for me, like this is the one that tipped me over into like, maybe I'm not
[48:49] SPEAKER: going to get the budget one next time I buy a phone, maybe I will just get the base model
[48:52] SPEAKER: because having, having the promotion in the base model and not having to get a pro for
[48:56] SPEAKER: that is huge.
[48:57] SPEAKER: Yeah.
[48:58] SPEAKER: With that, you also get the always on lock screen, which I think I want to say that wasn't,
[49:02] SPEAKER: I think that's, that's an adaptive refresh rate feature because they turn the refresh
[49:06] SPEAKER: rate way, way down.
[49:07] SPEAKER: Yeah.
[49:08] SPEAKER: So it would have to be like, they, they like the watch is the same way.
[49:10] SPEAKER: They drop it to one Hertz when it's not doing anything to save battery life.
[49:14] SPEAKER: So, so no base iPhone has ever had the always on screen.
[49:17] SPEAKER: I don't believe so.
[49:18] SPEAKER: I don't, I don't know that for sure.
[49:21] SPEAKER: 3000 nits peak brightness.
[49:23] SPEAKER: It has the ceramic shield too, which is there more scratches.
[49:26] SPEAKER: Okay.
[49:26] SPEAKER: The watch was two times more scratch resistant than the last one.
[49:29] SPEAKER: This is three times more scratch resistant than the last one.
[49:32] SPEAKER: Brad.
[49:32] SPEAKER: Well, that's, that's the ceramic shield two difference.
[49:34] SPEAKER: Yeah.
[49:35] SPEAKER: That's, that's what does it.
[49:35] SPEAKER: And it has an anti-reflective coating, which is nice.
[49:38] SPEAKER: Does this only have the ceramic on the front glass?
[49:40] SPEAKER: Like not on the back.
[49:42] SPEAKER: I believe so.
[49:43] SPEAKER: I don't think they talked about the back having ceramic shield.
[49:46] SPEAKER: Cause they call it, we'll get to the air in a second, but they called it out on the air
[49:49] SPEAKER: as saying, Hey, this has ceramic shield all the way around.
[49:51] SPEAKER: So I assume that's not the case on the base.
[49:53] SPEAKER: Man.
[49:54] SPEAKER: If that thing didn't have ceramic shield all the way around, it would just, you might as
[49:57] SPEAKER: well just, it might as well just explode the battery out the back.
[50:00] SPEAKER: Snap like a twig the first time you sat down.
[50:03] SPEAKER: Exactly.
[50:04] SPEAKER: Okay.
[50:05] SPEAKER: So we talked about the SOC it's three millimeter, three nanometer, rather a 19 looking at their,
[50:11] SPEAKER: at their block diagram of the, of the thing it's like half CPU and GPU, 30% AI crap.
[50:17] SPEAKER: And then the rest is at the other stuff, the modems and all the stuff that makes the thing
[50:21] SPEAKER: work.
[50:21] SPEAKER: I don't necessarily mind the NPU stuff because it feels like Apple's use of that stuff is
[50:26] SPEAKER: much more like just additive to their base experience, as opposed to, here's a bunch
[50:30] SPEAKER: of generative shit.
[50:31] SPEAKER: You don't want, you know, like setting stuff like genmojis aside, but.
[50:35] SPEAKER: I don't think they talked about chat GPT integration at all.
[50:38] SPEAKER: They did use the term LLM two or three times, but.
[50:41] SPEAKER: But all of their mo almost all of their AI and machine learning examples were like machine
[50:49] SPEAKER: learning examples, not generative stuff.
[50:51] SPEAKER: Right.
[50:51] SPEAKER: It was like, you know, machine learning to profile your health data or like visual search
[50:55] SPEAKER: for like, you know, draw a circle around this bench that you are this stool that you want
[50:59] SPEAKER: to search and have it search Google for that.
[51:01] SPEAKER: Or, you know, it's like.
[51:02] SPEAKER: There was a little bit about like customizing, summarizing things for you and stuff like
[51:07] SPEAKER: that, which I guess is LLM stuff.
[51:08] SPEAKER: But anyway.
[51:09] SPEAKER: Yeah.
[51:10] SPEAKER: Cameras, this is the thing people care about.
[51:12] SPEAKER: Oh, 50% charge in 20 minutes with a wired charge.
[51:14] SPEAKER: It's faster charging.
[51:16] SPEAKER: And this does get live translation on the iPhone for this model, because it has all
[51:20] SPEAKER: the MPU stuff.
[51:23] SPEAKER: Cameras, rear cameras are 48 megapixel.
[51:27] SPEAKER: It's that dual fusion main camera, which is the thing they rolled out last year.
[51:30] SPEAKER: It has basically two sets of optics inside it through some magic and software to 48 megapixel
[51:37] SPEAKER: main camera and you get a 12 megapixel 2x telephoto, which they described as optical
[51:42] SPEAKER: quality, which seems like digital zoom to me.
[51:44] SPEAKER: Optical quality screams, not actually optical.
[51:47] SPEAKER: Yeah.
[51:50] SPEAKER: There's also a 48 megapixel fusion ultra wide, which is there.
[51:54] SPEAKER: Like it's the 0.5 zoom wide angle lens.
[51:57] SPEAKER: So you can get real up close on people and do macro shots and stuff.
[52:01] SPEAKER: Front cameras across the board, I think, got an upgrade.
[52:04] SPEAKER: It's the they call it the center stage front camera.
[52:06] SPEAKER: It's a square sensor.
[52:08] SPEAKER: And that means that if you want to, so previously sensors were, were 16 by nine or four, three
[52:14] SPEAKER: aspect ratio.
[52:16] SPEAKER: So if you wanted to change to be landscape or portrait, you actually had to rotate the
[52:19] SPEAKER: phone since it's square.
[52:20] SPEAKER: It just picks that intelligently based on how many people are in the frame.
[52:24] SPEAKER: Right.
[52:25] SPEAKER: It just crops based on face detection and stuff like that.
[52:27] SPEAKER: That's neat.
[52:27] SPEAKER: That's that seems like a cool change.
[52:29] SPEAKER: And also like, I don't care about camera stuff as much as some people, but like it's
[52:34] SPEAKER: another thing where all this camera stuff added in with the promotion and with, you
[52:38] SPEAKER: know, some of this other stuff, like really makes this feel like a pretty compelling package
[52:43] SPEAKER: for, for a base model.
[52:45] SPEAKER: Getting the nice cameras.
[52:46] SPEAKER: It turns out as nice.
[52:48] SPEAKER: They also stabilize action mode, like action mode on the rear camera with that.
[52:52] SPEAKER: So if you're running or something, it'll give you, it uses the edges of the frame to
[52:55] SPEAKER: make the picture more stable.
[52:56] SPEAKER: Yeah.
[52:58] SPEAKER: As the person with long arms who often ends up having to take the family selfies.
[53:01] SPEAKER: I appreciate this mode a lot.
[53:02] SPEAKER: Yeah.
[53:02] SPEAKER: Cause it means they don't have to do the scary reach.
[53:04] SPEAKER: It's smart.
[53:05] SPEAKER: Smart usability stuff.
[53:07] SPEAKER: iPhone pro is a, Oh, so hold on.
[53:10] SPEAKER: That comes in five colors, lavender, blue, black, white, and sage, which is green lavender's
[53:16] SPEAKER: purple.
[53:18] SPEAKER: And it starts at 800 bucks.
[53:19] SPEAKER: I think us, I don't think prices went up on anything, which, you know, shout outs to Apple.
[53:24] SPEAKER: I guess they made, I guess they went and paid fealty.
[53:26] SPEAKER: So we don't, maybe that's, maybe we don't shout out to Apple for this.
[53:31] SPEAKER: iPhone pro is aluminum this year, not titanium.
[53:35] SPEAKER: Actually.
[53:35] SPEAKER: Sorry.
[53:35] SPEAKER: Real quick is, is, was the 16 also 800 is this, has this been the pricing for awhile?
[53:40] SPEAKER: I it's really hard to find launch Apple pricing.
[53:43] SPEAKER: Cause they, it goes away the moment they do it.
[53:45] SPEAKER: I think it was 600.
[53:46] SPEAKER: I think it was 800 bucks.
[53:47] SPEAKER: Okay.
[53:48] SPEAKER: I think this has been 800 bucks for a long time, but I don't.
[53:51] SPEAKER: Should wondering if terrorists had played a role here, but it sounds like maybe no.
[53:54] SPEAKER: The, the, the pro is the same price as it's always been for what it's worth.
[53:58] SPEAKER: That's the one I bought most recently.
[54:00] SPEAKER: So good to know.
[54:01] SPEAKER: Okay.
[54:02] SPEAKER: So the pro they've moved away from the titanium body back to aluminum which is,
[54:07] SPEAKER: which is interesting.
[54:08] SPEAKER: Cause I like the titanium a lot.
[54:10] SPEAKER: It's the, I don't use a case.
[54:13] SPEAKER: It's been basically indestructible.
[54:14] SPEAKER: I've dropped it on concrete and doesn't have any gouges in it or anything.
[54:17] SPEAKER: Interesting.
[54:17] SPEAKER: Okay.
[54:18] SPEAKER: So they, they did their they did their like industrial porn presentation of showing
[54:22] SPEAKER: machining the out of a solid block of aluminum and multiple anodization baths and so on.
[54:27] SPEAKER: But they voiceover use the term unibody.
[54:31] SPEAKER: But they've done unibody.
[54:33] SPEAKER: Like the, the frames for these are been one piece for a long time.
[54:36] SPEAKER: I could have sworn she said this was the first unibody iPhone.
[54:39] SPEAKER: Oh, maybe, maybe.
[54:40] SPEAKER: I don't know.
[54:42] SPEAKER: Um, the silver orange and blue.
[54:45] SPEAKER: Dude, that orange is rad.
[54:47] SPEAKER: It looks cool.
[54:48] SPEAKER: It looks nice.
[54:48] SPEAKER: Is there no black option?
[54:50] SPEAKER: Is this the first time there has not, there has not been a black option on an iPhone model?
[54:54] SPEAKER: I don't think they had a black option on the titanium ones either.
[54:57] SPEAKER: Oh, wild.
[54:58] SPEAKER: Uh, I don't know.
[54:59] SPEAKER: I always buy white.
[55:00] SPEAKER: So, um, not that that's, that's a question I'm not prepared to answer.
[55:04] SPEAKER: All right.
[55:04] SPEAKER: Well, let's it's, it's got a big giant battery and it looks, so there's a whole,
[55:11] SPEAKER: they call this thing the plateau.
[55:13] SPEAKER: It looks like a pimple hanging off the back of your iPhone.
[55:15] SPEAKER: I don't, I don't like it.
[55:16] SPEAKER: It's like goes across the entire back.
[55:19] SPEAKER: It has the cameras in it.
[55:20] SPEAKER: Yeah, this is, I mean, we'll also talk about this with the iPhone air.
[55:24] SPEAKER: I am kind of over camera bumps, honestly, I know they're a fact of life now and they're
[55:28] SPEAKER: not going away and that sucks, but I would actually just take a thicker phone that flattened
[55:32] SPEAKER: the back of the phone again.
[55:33] SPEAKER: Well, this is where you and I differ.
[55:35] SPEAKER: We'll talk about that in a minute.
[55:36] SPEAKER: I just wanted to lie flat on a surface.
[55:39] SPEAKER: So Brad, I think they're putting the whole, all the electric, it looks like they're putting
[55:42] SPEAKER: all the electronics for the phone, all the boards, everything that makes the phone work
[55:46] SPEAKER: in that plateau.
[55:47] SPEAKER: On the pro?
[55:48] SPEAKER: I don't know about on the pro, definitely on the air.
[55:50] SPEAKER: The air.
[55:51] SPEAKER: Yeah, we'll get to the air.
[55:52] SPEAKER: That sounds right for the air.
[55:53] SPEAKER: I'm not so sure about the pro though.
[55:55] SPEAKER: They didn't, they didn't show a cutaway of the pro that I saw.
[55:58] SPEAKER: So but, but it's the same size and there's, I mean, there's the vapor chamber and all
[56:02] SPEAKER: that stuff.
[56:02] SPEAKER: So anyway.
[56:04] SPEAKER: Dude, this thing has a vapor chamber.
[56:05] SPEAKER: Yeah, it's stupid.
[56:06] SPEAKER: Is this the first phone that has ever had a vapor chamber and certainly the first one
[56:09] SPEAKER: I have heard of?
[56:10] SPEAKER: Absolutely.
[56:10] SPEAKER: There's absolutely been an Android phone that's done a vapor chamber, but it was a bad idea
[56:14] SPEAKER: there.
[56:15] SPEAKER: Okay.
[56:15] SPEAKER: So the antennas go around the plateau.
[56:18] SPEAKER: There's glass, it's like a glass aluminum sandwich there that makes the whole thing
[56:23] SPEAKER: work.
[56:25] SPEAKER: It's ceramic shield, 2.0 front and back.
[56:28] SPEAKER: The back glass is kind of small.
[56:29] SPEAKER: It's just that big patch in the middle underneath the, underneath the plateau.
[56:33] SPEAKER: Yeah.
[56:35] SPEAKER: They did all this to maximize battery space, apparently, which is like, Hey, shout outs
[56:39] SPEAKER: to battery.
[56:39] SPEAKER: We love batteries.
[56:41] SPEAKER: It's basically the same SOC as the iPhone Air except this one has one extra GPU core,
[56:49] SPEAKER: I believe.
[56:50] SPEAKER: And it has a thermal management system that they put in a foam that has a vapor chamber
[56:54] SPEAKER: filled with deionized water that can move heat from this SOC to the other parts of the
[57:02] SPEAKER: phone to dissipate cooling.
[57:03] SPEAKER: They talked about using the aluminum instead of the titanium cause it has better heat dissipation
[57:07] SPEAKER: capability.
[57:09] SPEAKER: I think it's pretty ridiculous to use a vapor chamber in a phone, but also my phone gets
[57:13] SPEAKER: hot as hell.
[57:14] SPEAKER: So I get it.
[57:14] SPEAKER: I guess they know what they're doing.
[57:16] SPEAKER: Yeah.
[57:18] SPEAKER: I guess I'd rather have that than a fan.
[57:20] SPEAKER: So, and they talked about.
[57:22] SPEAKER: God help us.
[57:23] SPEAKER: Yeah.
[57:24] SPEAKER: They they've talked about US versions of the, depending on the region you're in, you can
[57:28] SPEAKER: get either a physical SIM or an eSIM on the iPhone Pro still.
[57:32] SPEAKER: I didn't realize they were doing.
[57:34] SPEAKER: The US we get eSIMs exclusively, I believe.
[57:36] SPEAKER: Oh, actually my SC, I guess my SC3 does have a SIM slot.
[57:39] SPEAKER: Yeah, yeah, yeah.
[57:41] SPEAKER: I thought they had gone eSIM only on everything already.
[57:44] SPEAKER: And then, you know, they talk about like not having the physical SIM slot gives them more
[57:47] SPEAKER: battery space.
[57:48] SPEAKER: So the camera, the camera is that fusion camera.
[57:50] SPEAKER: They, they, all three of the cameras are those fusion cameras with the dual optics business
[57:55] SPEAKER: that lets them say it's not digital zoom somehow.
[57:58] SPEAKER: There's an 8X optical zoom on the, on the, on the telephoto.
[58:03] SPEAKER: The sensor for the telephoto is bigger than last gen.
[58:06] SPEAKER: It's the, it's a new telephoto sensor.
[58:07] SPEAKER: This go round, so better low light, all the normal stuff that happens every time they
[58:10] SPEAKER: update the sensor, they're still applying a ton of machine learning to everything to
[58:15] SPEAKER: pretty it up and combine the outputs from the three sensors and all that.
[58:20] SPEAKER: So, yeah, and you basically each of the three lenses, each of the three camera sensors has
[58:25] SPEAKER: two modes.
[58:26] SPEAKER: So you go from ultra wide to the 8X telephoto and everything in between.
[58:31] SPEAKER: Apparently I filmed this entire event on iPhone 17 Pros and it was a very good looking presentation.
[58:36] SPEAKER: Do you think they shot all those drone shots with iPhone?
[58:38] SPEAKER: Yeah, of course.
[58:39] SPEAKER: Yeah, totally.
[58:39] SPEAKER: You just, you get hangers that hang the phone off the bottom of the drone.
[58:42] SPEAKER: Lot of drone shots in this thing.
[58:44] SPEAKER: They, they love a drone shot, man.
[58:46] SPEAKER: They also do boom shots at the Apple headquarters too.
[58:49] SPEAKER: So they're quiet.
[58:50] SPEAKER: It was, it was very good looking video.
[58:51] SPEAKER: I have to say.
[58:52] SPEAKER: Yeah.
[58:52] SPEAKER: So the pro like they, they keep adding weird pro level features into the iPhone pro.
[58:58] SPEAKER: That was my big takeaway.
[58:59] SPEAKER: Like I, I don't keep up with high end iPhone models cause I'm not in that market.
[59:03] SPEAKER: Yeah.
[59:04] SPEAKER: I've always assumed the iPhone pro was just the fancy one for people who wanted to spend
[59:08] SPEAKER: a ton of money on their phone.
[59:10] SPEAKER: No, that's right.
[59:11] SPEAKER: Well, I'm sure it is that as well, just like the Apple watch ultra is ostensibly for people
[59:14] SPEAKER: who go diving and mountaineering, but also for people who sit in offices.
[59:19] SPEAKER: But my big takeaway from this though, was like, this thing is actually like extremely
[59:24] SPEAKER: production level with some of the features they're adding in terms of like, you know,
[59:28] SPEAKER: actual film and TV production environments.
[59:30] SPEAKER: Like they've added pro res raw support.
[59:32] SPEAKER: They've had pro res.
[59:34] SPEAKER: They've had raw support.
[59:34] SPEAKER: They haven't had pro res raw support, I believe.
[59:36] SPEAKER: Yeah.
[59:36] SPEAKER: Okay.
[59:38] SPEAKER: Let's got gen lock now.
[59:40] SPEAKER: I was gonna say the crazy thing to me is that they have gen lock, which is a thing that
[59:42] SPEAKER: you use to sync frame, like the frame capture timing on multiple cameras at the same time.
[59:48] SPEAKER: If you're working in a production thing, so you can have clean frame, perfect cuts from
[59:52] SPEAKER: one camera to another.
[59:54] SPEAKER: Right.
[59:55] SPEAKER: And they're doing that with a black magic pro doc.
[59:57] SPEAKER: That's not available until like next year.
[59:59] SPEAKER: I think that doc is hilarious because it's got like BNC connectors on it.
[1:00:04] SPEAKER: Like obviously that's all like standard expected production level hardware.
[1:00:08] SPEAKER: It's just the hardware.
[1:00:09] SPEAKER: It ends and it terminates in a tiny little USB-C cable that plugs into your phone.
[1:00:13] SPEAKER: You know, it's just like, it's the blending of production to your hardware with the thing
[1:00:18] SPEAKER: that goes in your pocket that you make phone calls on.
[1:00:20] SPEAKER: That's just kind of a, it's just a weird juxtaposition to me.
[1:00:23] SPEAKER: Obviously it all works.
[1:00:24] SPEAKER: I mean, so I think the other thing is there, they added higher speed transfer out of the
[1:00:29] SPEAKER: USB port because the other phones have USB two data and USB three power.
[1:00:35] SPEAKER: Yeah, sure.
[1:00:36] SPEAKER: Classic iPhone.
[1:00:38] SPEAKER: Yup.
[1:00:38] SPEAKER: The, this one does USB three up to 10 gigabits.
[1:00:41] SPEAKER: I think just about to ask if it, I wonder if it goes up to 10.
[1:00:44] SPEAKER: That's cool.
[1:00:45] SPEAKER: Yeah.
[1:00:46] SPEAKER: Well, kind of, it's still like, it's still less good than external media for the poor
[1:00:50] SPEAKER: person who has to corral media at a shoot.
[1:00:53] SPEAKER: Yeah.
[1:00:53] SPEAKER: My assumption is if people are using these in actual real production environments, they
[1:00:57] SPEAKER: have like 10 phones and they're cycling between them.
[1:00:59] SPEAKER: Yeah.
[1:01:00] SPEAKER: I'm wildly curious to hear if people are actually shooting stuff on iPhone pros that
[1:01:04] SPEAKER: Apple isn't paying for.
[1:01:05] SPEAKER: That was exactly my question is that it felt like every time they've talked about using
[1:01:09] SPEAKER: like shooting serious stuff on iPhones before, it's just been like a marketing bullet point
[1:01:13] SPEAKER: for Apple.
[1:01:14] SPEAKER: Yeah.
[1:01:14] SPEAKER: Hey guys, we got Steven Soderbergh to shoot something or hey guys, we got Spike Jones
[1:01:18] SPEAKER: to shoot something.
[1:01:20] SPEAKER: Right.
[1:01:20] SPEAKER: But that, that presentation at the end of this showing this being used in, I mean, these
[1:01:23] SPEAKER: were mocked up obviously production environments, but like, are people actually just using this
[1:01:28] SPEAKER: on film sets now?
[1:01:29] SPEAKER: Look, I think the thing that you should think about this as is if Kevin Smith was making
[1:01:34] SPEAKER: clerks today, instead of putting $40,000 worth of camera rental stuff on his, on his credit
[1:01:40] SPEAKER: cards, he would probably just buy an iPhone pro and a little steady cam and a couple and
[1:01:46] SPEAKER: rent some dollies and stuff.
[1:01:47] SPEAKER: Yeah.
[1:01:48] SPEAKER: You put it in that context.
[1:01:49] SPEAKER: Actually, no, it's Kevin Smith.
[1:01:50] SPEAKER: So he's not going to get dollars.
[1:01:51] SPEAKER: He's just going to get one tripod and frame it in exactly the same way for every single
[1:01:55] SPEAKER: shot and it's done.
[1:01:56] SPEAKER: Yeah.
[1:01:56] SPEAKER: Yeah.
[1:01:56] SPEAKER: But would you put it in that context of like up and coming, you know, people, people that
[1:01:59] SPEAKER: used to shoot on little eight millimeter cameras now can get something like this, like that,
[1:02:03] SPEAKER: that makes more sense than like Michael Bay is shooting action scenes with this thing
[1:02:07] SPEAKER: or something.
[1:02:08] SPEAKER: Yeah.
[1:02:08] SPEAKER: I think, I mean, Soderbergh shot, shot that movie famously with the iPhone 10, I think,
[1:02:13] SPEAKER: or eight.
[1:02:14] SPEAKER: I can't remember.
[1:02:14] SPEAKER: It was a long time ago.
[1:02:15] SPEAKER: He's just, he's enough of a filmmaking nerd that he probably considered that like an interesting
[1:02:19] SPEAKER: challenge.
[1:02:20] SPEAKER: Well, right. And he also remember started making stuff on like eight millimeter and
[1:02:23] SPEAKER: videotape.
[1:02:24] SPEAKER: Right.
[1:02:24] SPEAKER: Like famously.
[1:02:25] SPEAKER: Yeah.
[1:02:25] SPEAKER: So yeah.
[1:02:27] SPEAKER: Anyway, I think it's, I think it's, it's good that this stuff is accessible.
[1:02:32] SPEAKER: I'm like, yeah, I don't, I don't think the next Transformers movie is going to be shot
[1:02:36] SPEAKER: on iPhone pro.
[1:02:38] SPEAKER: Right.
[1:02:38] SPEAKER: And then the last one is the iPhone air, which is like, I was fascinated by this.
[1:02:42] SPEAKER: So it's, it's a really, really thin iPhone.
[1:02:45] SPEAKER: It has a polished titanium frame.
[1:02:47] SPEAKER: So it's shiny and very pretty.
[1:02:50] SPEAKER: It splits the gap.
[1:02:51] SPEAKER: The iPhone pro starts at 10 99 plus a hundred bucks for the max version, plus more money
[1:02:56] SPEAKER: for the bigger storage.
[1:02:57] SPEAKER: Up to 10 terabytes.
[1:02:58] SPEAKER: Well, the two terabytes makes sense for people who are using it in a, in a, in a shooting
[1:03:03] SPEAKER: environment.
[1:03:03] SPEAKER: Of course.
[1:03:04] SPEAKER: It's still just the idea of two terabytes on a phone is just kind of wild.
[1:03:07] SPEAKER: I mean, let me tell you, I shot my, one of my kids talent shows with iPhone raw one time
[1:03:13] SPEAKER: and man, I wish I had a bigger phone because it took an hour long talent show was 85 gigabytes
[1:03:18] SPEAKER: for something ridiculous.
[1:03:19] SPEAKER: I believe it.
[1:03:22] SPEAKER: The, the air splits the gap.
[1:03:24] SPEAKER: It starts at the grand it's, it looks, it's basically just like the phone pimple and the
[1:03:31] SPEAKER: battery.
[1:03:32] SPEAKER: And that's the entire thickness of the thing.
[1:03:35] SPEAKER: It's got the ceramic shield glass on both sides.
[1:03:38] SPEAKER: I think everything is in the bump on that phone, all the hardware that makes the phone
[1:03:42] SPEAKER: a phone.
[1:03:43] SPEAKER: It lives inside the, inside the plateau.
[1:03:45] SPEAKER: Yeah.
[1:03:45] SPEAKER: That bad.
[1:03:46] SPEAKER: I believe that this is not for me.
[1:03:47] SPEAKER: I don't know about you.
[1:03:48] SPEAKER: Like I don't need a phone this thin and I especially don't love the very top heavy nature
[1:03:52] SPEAKER: of having this giant module at the top of this.
[1:03:55] SPEAKER: Otherwise like wafer thin.
[1:03:57] SPEAKER: I was getting ready to pre-order one.
[1:03:58] SPEAKER: I meant to do it this morning and I forgot when I was up.
[1:04:00] SPEAKER: Wow.
[1:04:01] SPEAKER: Okay.
[1:04:02] SPEAKER: I, I love a small phone.
[1:04:04] SPEAKER: Like if they made an iPhone mini, I would have bought that this, this go round.
[1:04:09] SPEAKER: It's not a small footprint though.
[1:04:10] SPEAKER: It's just thin.
[1:04:11] SPEAKER: It's like, it's still a six and a half inch screen.
[1:04:13] SPEAKER: Like it's still like the X and Y of it are basically the same as any normal phone.
[1:04:17] SPEAKER: But for me, the weight is a huge deal because like I use my phone a lot.
[1:04:22] SPEAKER: I know you don't.
[1:04:23] SPEAKER: We'll see.
[1:04:24] SPEAKER: We'll see how people feel once they get it in the hand.
[1:04:26] SPEAKER: But, but again, putting all the electronics at the top of the phone, I wonder how the
[1:04:30] SPEAKER: balance is going to feel.
[1:04:31] SPEAKER: I'm sure, I'm sure Apple figured this out, but.
[1:04:34] SPEAKER: I'm going to see, let's see if I get the white one in 256 gigabytes.
[1:04:40] SPEAKER: I don't want to trade in.
[1:04:41] SPEAKER: I'm going to trade in if I do it, but I'm just going to buy it.
[1:04:44] SPEAKER: I know there's already stories going around.
[1:04:45] SPEAKER: Like I looked at pack rumors this morning, it was already like, here's how long it's
[1:04:48] SPEAKER: going to take now if you didn't order to pre-order to get one.
[1:04:50] SPEAKER: And it was like a month now.
[1:04:52] SPEAKER: Damn.
[1:04:53] SPEAKER: Well, I might as well not get it then.
[1:04:54] SPEAKER: Yep.
[1:04:54] SPEAKER: Yeah, I get mine.
[1:04:56] SPEAKER: If I ordered it right now, it delivers between September 29th and October 6th.
[1:05:00] SPEAKER: So an extra 10 days.
[1:05:03] SPEAKER: So yeah, it looks, it looks real thin.
[1:05:04] SPEAKER: It looks like it bends if you put it in your back pocket.
[1:05:08] SPEAKER: It comes in black, white, gold, and blue.
[1:05:12] SPEAKER: All these screens are 3000 nits, I think.
[1:05:14] SPEAKER: Even the, even the regular iPhone one.
[1:05:17] SPEAKER: So it'd be real bright in daylight.
[1:05:18] SPEAKER: Yeah.
[1:05:18] SPEAKER: So all the, all the iPhone 17s have promotion now.
[1:05:22] SPEAKER: And this has the Apple N1, which is their wifi, Bluetooth and thread chip in it.
[1:05:27] SPEAKER: I think, I think both this and the pro I'm not sure about the regular iPhone.
[1:05:30] SPEAKER: They didn't mention that.
[1:05:32] SPEAKER: I think it's interesting that the phones have thread radios now.
[1:05:35] SPEAKER: Yeah.
[1:05:36] SPEAKER: I don't know what they'll use that for, but I guess you could use the phone as a
[1:05:39] SPEAKER: smart device controller potentially or, or to hook them up to your network.
[1:05:44] SPEAKER: Probably is the thing.
[1:05:44] SPEAKER: Yeah.
[1:05:45] SPEAKER: Yeah.
[1:05:45] SPEAKER: That makes sense.
[1:05:47] SPEAKER: It has a C1X, which is the second, second version of their first modem.
[1:05:50] SPEAKER: Yeah.
[1:05:51] SPEAKER: So I want to say it was the 16E that shipped earlier this year, the budget 16 was the first
[1:05:55] SPEAKER: one that had the C1, which was their first generation in-house cellular modem.
[1:06:00] SPEAKER: Cause I think they were using Qualcomm previously for that.
[1:06:02] SPEAKER: Yeah.
[1:06:02] SPEAKER: Qualcomm before.
[1:06:05] SPEAKER: This, this sounds like an improved version of the C1 as opposed to a full side.
[1:06:09] SPEAKER: They probably would have called it a C2 if it was full second gen.
[1:06:12] SPEAKER: Yeah. They said it's faster and uses less power.
[1:06:14] SPEAKER: So like 30% less power, which makes me wonder.
[1:06:17] SPEAKER: They did not mention this being in the base 17.
[1:06:20] SPEAKER: So do we think it's not in the base 17?
[1:06:21] SPEAKER: I don't think it's in the pro either, Brad.
[1:06:23] SPEAKER: I think that, I think that this is, I wonder if this is how they managed to make it so small.
[1:06:28] SPEAKER: Oh, okay.
[1:06:29] SPEAKER: This was like a, Hey, we got this together as fast as we could for this thin phone.
[1:06:33] SPEAKER: Yeah.
[1:06:33] SPEAKER: My guess is that this, that the, how many of these they make is the gate on how many
[1:06:37] SPEAKER: of these phones they can make.
[1:06:38] SPEAKER: That makes sense because when you say, Hey, this is the modem and this uses 30 less, 30%
[1:06:42] SPEAKER: less power, it's kind of a bummer for it to not be in the other models.
[1:06:45] SPEAKER: But it is, it is just one component of the system.
[1:06:48] SPEAKER: That's probably not gonna make a huge, huge difference to overall battery life.
[1:06:52] SPEAKER: The big thing about this is it only has one camera on the back.
[1:06:56] SPEAKER: So it's got one quad mode camera.
[1:07:00] SPEAKER: Basically it's the 48 megapixel, 12 megapixel,
[1:07:04] SPEAKER: two X zoom, same as the iPhone seven, the regular iPhone.
[1:07:11] SPEAKER: Four lenses in your pocket is the thing that they said, I thought that was a big one.
[1:07:16] SPEAKER: I'm pretty sure.
[1:07:16] SPEAKER: No, I'm pretty sure they said eight lenses in your pocket, which I don't know about that.
[1:07:21] SPEAKER: We'll see how the upscaling works.
[1:07:24] SPEAKER: And all of these, you can do dual capture video on now.
[1:07:26] SPEAKER: So front and back at the same time.
[1:07:28] SPEAKER: Yeah.
[1:07:28] SPEAKER: Yeah.
[1:07:28] SPEAKER: That's actually, I don't know if you can do that on the normal iPhone.
[1:07:32] SPEAKER: I think that might be Aaron pro only.
[1:07:37] SPEAKER: So like you can record the video they showed as you recording yourself at your kids' soccer game,
[1:07:41] SPEAKER: which is weirdly centering you at your child's soccer game, but whatever.
[1:07:45] SPEAKER: I'm not here to judge probably.
[1:07:49] SPEAKER: They do adaptive power mode.
[1:07:50] SPEAKER: They talked about adaptive power mode in this, which I'm curious if I think,
[1:07:54] SPEAKER: I assume that's an iOS 26 feature coming to the new version of iOS where it watches how you,
[1:08:02] SPEAKER: it tracks how you use your battery over time and adjust things like performance to, so that you,
[1:08:10] SPEAKER: so it ensures you have battery at the times that you need it most.
[1:08:14] SPEAKER: Your daughter will be thrilled.
[1:08:16] SPEAKER: Dude.
[1:08:17] SPEAKER: I don't even want to talk about it.
[1:08:19] SPEAKER: Leaving the house with 30% battery has never been more workable.
[1:08:23] SPEAKER: I'm sure it's not coming to her 13 mini.
[1:08:25] SPEAKER: No.
[1:08:27] SPEAKER: They, they, they're finally, they showed a bunch of accessories with this.
[1:08:31] SPEAKER: They're making a MagSafe battery that is designed to nestle in under the plateau on this.
[1:08:37] SPEAKER: It looks very thin.
[1:08:38] SPEAKER: It gets it to basically normal iPhone pro battery life with the MagSafe.
[1:08:41] SPEAKER: I think it's very funny that both adding a battery and also equalizing the thickness of that top
[1:08:46] SPEAKER: module bump thing kind of, kind of just turns it into a normally sized phone.
[1:08:51] SPEAKER: I, I look, I did the, I did the eyeballing on the measurements and I think with the ring
[1:08:55] SPEAKER: that I put on the back of my phone, it's going to be exactly the right thickness
[1:08:59] SPEAKER: to, to balance out the pimple.
[1:09:01] SPEAKER: So we'll see.
[1:09:03] SPEAKER: I think it's really funny that they're making an official cross body strap for the iPhone.
[1:09:07] SPEAKER: I had never heard of this before we were watching the presentation last night.
[1:09:10] SPEAKER: And then I was like, what the, who does then?
[1:09:12] SPEAKER: And my girlfriend was like, Oh yeah, these are like all over Amazon.
[1:09:15] SPEAKER: Wildly popular.
[1:09:16] SPEAKER: The TikTok shop is full of them.
[1:09:18] SPEAKER: Really?
[1:09:19] SPEAKER: Yeah.
[1:09:20] SPEAKER: So it was basically a body strap to be clear, what we're talking about is effectively kind
[1:09:23] SPEAKER: of a cross body, like shoulder strap that you hang your phone from.
[1:09:27] SPEAKER: Yeah, I don't know.
[1:09:29] SPEAKER: Okay, sure.
[1:09:30] SPEAKER: The two edges of the strap hit, hit in the two bottom corners of the phone.
[1:09:35] SPEAKER: It seems like a really good way to get your phone stolen, but what do I know?
[1:09:37] SPEAKER: Or damaged, you know, it just feels like having your phone swing around
[1:09:40] SPEAKER: all over the place is maybe a little risky, but okay.
[1:09:43] SPEAKER: I'm curious if the old MagSafe batteries are going to work with the plateau.
[1:09:48] SPEAKER: But that's pretty much it, I guess.
[1:09:50] SPEAKER: I bet not.
[1:09:52] SPEAKER: I'm happy.
[1:09:52] SPEAKER: I'm happy for you.
[1:09:53] SPEAKER: The iPhone air is not for me.
[1:09:55] SPEAKER: Yeah.
[1:09:55] SPEAKER: See, I look, I'm gonna go and tell you, I'm ordering it.
[1:10:00] SPEAKER: I'm not, I'm not doing the in-person trade-in.
[1:10:03] SPEAKER: So I have a week or two to decide if I want to keep it because I'm a little skeptical.
[1:10:07] SPEAKER: All right.
[1:10:07] SPEAKER: I'd be curious to hear about it for sure.
[1:10:09] SPEAKER: But this is absolutely not something I will ever want.
[1:10:12] SPEAKER: That's the thing is I, I do, I want to, I want to try it and see if I like it.
[1:10:16] SPEAKER: Like I said, I would like the iPhone 17, except with the case as thick as the camera bump
[1:10:21] SPEAKER: to accommodate more battery would be like the perfect phone to me.
[1:10:24] SPEAKER: Yeah, I can see that.
[1:10:25] SPEAKER: It does not seem to be the direction that Apple is ever going to go in.
[1:10:29] SPEAKER: No, I don't think so.
[1:10:30] SPEAKER: Because they, thinness seems to be king there.
[1:10:33] SPEAKER: Look, thinness is king.
[1:10:35] SPEAKER: I guess that's it for the show.
[1:10:37] SPEAKER: That's it, right?
[1:10:38] SPEAKER: Sure.
[1:10:38] SPEAKER: That's about it.
[1:10:38] SPEAKER: Yeah.
[1:10:39] SPEAKER: They didn't talk about a mini.
[1:10:40] SPEAKER: They didn't talk about an E.
[1:10:42] SPEAKER: Yeah.
[1:10:42] SPEAKER: So that's the big question for me, although less of a question now that the base model
[1:10:45] SPEAKER: is so appealing, I don't know that I'm actually as interested in an E, especially with the
[1:10:50] SPEAKER: 16E being dramatically more expensive than the SE was.
[1:10:54] SPEAKER: That was the big disappointment of the E.
[1:10:55] SPEAKER: I was just like, oh, they're just going to rebrand the SE, which was like under $500.
[1:10:59] SPEAKER: But when they bumped it up to base $600 price, and like when you look at how much more you're
[1:11:05] SPEAKER: getting in the base model, like the promotion, like way better camera, all this other stuff,
[1:11:08] SPEAKER: like the E model, I don't know.
[1:11:11] SPEAKER: That's it for me.
[1:11:12] SPEAKER: I like, I think the big surprise for me was that the iPhone, the base iPhone is the big
[1:11:18] SPEAKER: winner this time.
[1:11:19] SPEAKER: I think the air is neat and interesting and I'm glad that they're trying new things.
[1:11:23] SPEAKER: Yeah.
[1:11:23] SPEAKER: I'm kind of surprised we didn't see a foldy phone.
[1:11:25] SPEAKER: Although I get why.
[1:11:26] SPEAKER: Cause the, those get like everybody I know that has one of those, when I look at it,
[1:11:30] SPEAKER: I think, oh, that where the, where the fold happens in the phone would make me crazy.
[1:11:34] SPEAKER: Yeah.
[1:11:34] SPEAKER: Same.
[1:11:37] SPEAKER: Last thing I'll say on the E, I don't, I don't think it was even guaranteed that we're going
[1:11:39] SPEAKER: to get a 17E next year because the SE was only like in every three or four year release,
[1:11:45] SPEAKER: but all the Mac rumor, all the Apple rumor sites seem to be treating the 17E as a done
[1:11:49] SPEAKER: deal for next year.
[1:11:50] SPEAKER: So it seems like we, maybe we will be getting annual budget phones now.
[1:11:53] SPEAKER: Yeah.
[1:11:54] SPEAKER: That makes sense.
[1:11:55] SPEAKER: I don't think you're wrong, but it's less budget.
[1:11:57] SPEAKER: So yeah.
[1:11:59] SPEAKER: But I guess that's some good places.
[1:12:00] SPEAKER: I need to wrap it up as always.
[1:12:03] SPEAKER: Brad will made a tech pod as a listener supported show.
[1:12:04] SPEAKER: We wouldn't be here without you all the listeners.
[1:12:07] SPEAKER: So if you would like to find out how to support the show, you can go to Patrion.
[1:12:10] SPEAKER: It's patrion.com/tech pod where for five bucks a month, you get access to the discord.
[1:12:14] SPEAKER: You get the monthly patron exclusive episode where you hear us talk about, well, kind of
[1:12:19] SPEAKER: a wide ranging variety of topics these days.
[1:12:21] SPEAKER: Yeah, come tell me how to not blow up these external hard drives, but I'm going to try
[1:12:26] SPEAKER: to power or these guys.
[1:12:29] SPEAKER: If you're a very malicious person, come and tell me how to blow the vibe.
[1:12:32] SPEAKER: No, don't do that.
[1:12:33] SPEAKER: No, no.
[1:12:35] SPEAKER: But yeah, as always, thanks to everybody who supports the show, but a very special thank
[1:12:40] SPEAKER: you to our executive producer, to your patrons, including Jason Lee in Felicitous Rips, Andrew
[1:12:47] SPEAKER: Slosky, Jordan Lippett, Bunny Money, Twinkle Twinkie, David Allen, James Kammack, and Pantheon,
[1:12:53] SPEAKER: makers of the HS3 high speed 3d printer.
[1:12:56] SPEAKER: Thank you all so, so much.
[1:12:57] SPEAKER: Thank you.
[1:12:58] SPEAKER: Brad, I guess that's it.
[1:12:59] SPEAKER: I hope you have a lovely weekend and we will see everybody next week.
[1:13:04] SPEAKER: Please consider the environment before printing this podcast.
