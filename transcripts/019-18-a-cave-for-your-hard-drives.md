---
episode: 19
title: 18: A Cave for Your Hard Drives
date: 2020-01-19
guests: none
duration: 59:37
---

[00:00] SPEAKER: Well now we can never repeat that.
[00:01] SPEAKER: No, I know it's never gonna be as good.
[00:02] SPEAKER: We just did a perfect intro and now it's completely wasted because I hadn't pressed record yet.
[00:06] SPEAKER: What a dumbass.
[00:07] SPEAKER: I was so excited about my NUT server.
[00:09] SPEAKER: Look, we'll talk about your NUT server at the end of the episode where it belongs.
[00:12] SPEAKER: It's gonna make you wait.
[00:13] SPEAKER: Yeah.
[00:14] SPEAKER: You gotta build up the tension.
[00:16] SPEAKER: NUT server is all about tension and release, I can tell you that.
[00:20] SPEAKER: So, look, the dick jokes happen on the stream, Brad, at thegiantbomb.com.
[00:28] SPEAKER: This is nothing but testicle jokes from here on out.
[00:30] SPEAKER: That's what we do here.
[00:58] SPEAKER: Welcome to Brad and Will Made a Tech Pod, I'm Will.
[01:02] SPEAKER: I'm Brad.
[01:03] SPEAKER: This is the number one podcast where people talk about a single topic each week.
[01:06] SPEAKER: What's our topic?
[01:07] SPEAKER: Will.
[01:07] SPEAKER: NAS.
[01:08] SPEAKER: Network Attached Storage.
[01:10] SPEAKER: That sounds nasty.
[01:12] SPEAKER: Need another soda.
[01:16] SPEAKER: No one...
[01:17] SPEAKER: You'll need plenty of sodas as you bang away on your NAS trying to get stuff to work.
[01:21] SPEAKER: Look, caffeine is...
[01:22] SPEAKER: Never always SSH.
[01:25] SPEAKER: Yes.
[01:26] SPEAKER: Nothing seems simple.
[01:29] SPEAKER: I think we're getting a little field of the topic here.
[01:31] SPEAKER: But yeah, so you and I have both...
[01:34] SPEAKER: A few years ago, you sent me one of those messages that started a really,
[01:37] SPEAKER: really long thread that went for probably a year.
[01:40] SPEAKER: We were like, "Hey, you run a free NAS server, right?"
[01:42] SPEAKER: Question mark.
[01:43] SPEAKER: It's like, "Oh, do I?"
[01:46] SPEAKER: I did a video, I think a video, maybe an article about this that tested years ago.
[01:50] SPEAKER: But yeah, I've been running a free NAS server for like probably six or seven years now.
[01:53] SPEAKER: It's probably...
[01:54] SPEAKER: Wow.
[01:54] SPEAKER: Yeah.
[01:54] SPEAKER: Geez, you've been in there for a good long while.
[01:56] SPEAKER: I've been in through some major changes.
[01:58] SPEAKER: Yeah, I guess so.
[02:00] SPEAKER: I'm coming up on two years here.
[02:01] SPEAKER: But I feel like at some point, NAS was a term that I heard about 10 years ago or something,
[02:07] SPEAKER: and I assumed it was just something in the enterprise world that I would never care about.
[02:11] SPEAKER: But then I feel like it's a topic that has started breaching the mainstream and the consumer level
[02:17] SPEAKER: a lot more than I would have expected in the last year or two.
[02:19] SPEAKER: So there's two ways to look at it.
[02:22] SPEAKER: Servers have existed for years, like small business.
[02:25] SPEAKER: One of my first jobs was building servers for small businesses, so they'd have a
[02:29] SPEAKER: shared place to dump files in the world before Dropbox or Google Drive or whatever.
[02:34] SPEAKER: But now we're in a little bit of a different space.
[02:38] SPEAKER: And it turns out that a lot of us have big media collections.
[02:42] SPEAKER: If you have a kid, you probably shoot 15 or 20,000 photos a year with your phone.
[02:47] SPEAKER: Those have to be stored someplace.
[02:49] SPEAKER: And as we move more mobile, it's been nice to move some of that big storage
[02:53] SPEAKER: off of laptop hard drives that are usually too small and into a shared...
[02:58] SPEAKER: All a network attached storage base is a hard drive that's connected to the network in your house.
[03:03] SPEAKER: It's just the storage volume on your network instead of hooked up to a PC.
[03:06] SPEAKER: And they can range anywhere from a fully fledged PC server to a Windows machine that just has a
[03:13] SPEAKER: bunch of hard drives in it, to a dedicated NAS box from a company like Synology, all the way down to
[03:21] SPEAKER: Western Digital sells hard drives that you can hook up to Wi-Fi.
[03:24] SPEAKER: Yeah, I forgot until we were about to start this, you reminded me that, yeah,
[03:28] SPEAKER: you literally can buy what is essentially just a hard drive that can connect to...
[03:32] SPEAKER: That is technically a NAS.
[03:33] SPEAKER: Yeah, it just looks like an external USB hard drive.
[03:36] SPEAKER: And usually they even have USB ports.
[03:38] SPEAKER: If you want to copy the stuff over the first time fast, you can.
[03:41] SPEAKER: Then they hook up to Wi-Fi.
[03:42] SPEAKER: Right.
[03:44] SPEAKER: So there's a lot of...
[03:47] SPEAKER: I feel like that's the definition, right?
[03:49] SPEAKER: It's literally just a bucket on your network that you can source up.
[03:52] SPEAKER: Sometimes they're connected to the internet, sometimes they're not.
[03:54] SPEAKER: That's a choice you can make.
[03:56] SPEAKER: I'm sorry.
[03:57] SPEAKER: I guess it really is just driven by the amount of media that the average person isn't.
[04:00] SPEAKER: Or not media, but data.
[04:03] SPEAKER: It's just piling up, right?
[04:05] SPEAKER: It goes even beyond photos and personal stuff.
[04:09] SPEAKER: We back up our iPhones and put those on because an iPhone backup can get pretty big these days.
[04:13] SPEAKER: We put those on the NAS because that's a large amount.
[04:16] SPEAKER: But really, you do?
[04:18] SPEAKER: There's a little bit of a hoarding aspect there.
[04:20] SPEAKER: Oh, see, I...
[04:20] SPEAKER: I'm just trying to play it safe.
[04:21] SPEAKER: I paid the 50 cents a month or whatever for iCloud to back up.
[04:25] SPEAKER: Yeah.
[04:26] SPEAKER: It's the only thing I use iCloud for, is iOS backups.
[04:27] SPEAKER: Well, I've got weird situations where I've got an old iPhone backup that's got text messages
[04:33] SPEAKER: with, let's say, someone who's no longer with us.
[04:35] SPEAKER: Oh, yeah, yeah.
[04:36] SPEAKER: I don't want to lose that necessarily.
[04:38] SPEAKER: Yeah, you can pull those out.
[04:39] SPEAKER: Yeah, there are tools to export SMS or iMessage conversations and stuff like that.
[04:45] SPEAKER: But yeah, so that stuff exists.
[04:47] SPEAKER: That stuff is all out there.
[04:51] SPEAKER: Having a dedicated place to back up all of your local computers, really, really nice.
[04:56] SPEAKER: Having a place to store your photos, having just a machine that's always on that can run
[05:00] SPEAKER: stuff that makes your photos always accessible, or that lets you do weird home automation
[05:08] SPEAKER: hacks, like make things that aren't compatible with Siri or Apple HomePod.
[05:14] SPEAKER: HomeKit.
[05:15] SPEAKER: HomeKit, thank you.
[05:16] SPEAKER: Home something, home whatever, Apple's home business.
[05:19] SPEAKER: Work with Apple's home business.
[05:22] SPEAKER: And there's benefits to all that.
[05:23] SPEAKER: And there's different levels of capability at the different levels of complexity on the
[05:30] SPEAKER: server.
[05:30] SPEAKER: Plex is probably the actual most common use case, I would say.
[05:35] SPEAKER: I call mine "SmithFlicks" because it's like Netflix, but for Smiths.
[05:38] SPEAKER: You do.
[05:39] SPEAKER: It's true.
[05:40] SPEAKER: Yeah, and so Plex is a piece of software that lets you share movies and TV shows that you've
[05:45] SPEAKER: presumably ripped, but I guess also potentially stolen within your home, or also with people
[05:53] SPEAKER: outside your house, if you have fast enough internet.
[05:57] SPEAKER: And it is fantastic.
[06:01] SPEAKER: In the days before Netflix and Disney+ and Hulu let you copy things onto a device to
[06:06] SPEAKER: watch when you're offline, like for example, if you're taking a small child on an airplane
[06:09] SPEAKER: ride, Plex was incredible.
[06:12] SPEAKER: Like five, seven years ago, six years ago when my daughter was new and we would go on
[06:17] SPEAKER: an air...
[06:18] SPEAKER: Five years ago when she was two and we were going on an airplane ride and I could just
[06:21] SPEAKER: copy Totoro and Little Mermaid and whatever else she wanted to Winnie the Pooh onto an
[06:26] SPEAKER: iPad and give that to her.
[06:27] SPEAKER: So she just zoned out in front of a TV for three hours on the airplane.
[06:30] SPEAKER: Sure.
[06:30] SPEAKER: Terrific.
[06:31] SPEAKER: Yeah.
[06:31] SPEAKER: And this is just anecdotal that having read through dozens, if not hundreds of conversations
[06:36] SPEAKER: on the internet over the last few years about NASA's Plex is far and away the most cited
[06:42] SPEAKER: example of things that people want to do with their NASA.
[06:46] SPEAKER: Plex and local backup are the two things that I did before anything else.
[06:49] SPEAKER: Yes.
[06:50] SPEAKER: I guess we should kind of start at the bottom in terms of like what devices are available.
[06:53] SPEAKER: Yeah.
[06:54] SPEAKER: Like my path to wanting a NAS was that I only ever had...
[06:58] SPEAKER: I've never had more than two terabytes of storage in my Windows machine.
[07:01] SPEAKER: I had like a single two terabyte hard drive.
[07:04] SPEAKER: It started...
[07:06] SPEAKER: Like I just didn't need that much really.
[07:08] SPEAKER: You didn't get a six terabyte drive for like 75 cents.
[07:11] SPEAKER: I mean, I bought that like eight years ago or something.
[07:12] SPEAKER: So I had one two terabyte drive that started throwing smart errors.
[07:15] SPEAKER: Well, that's just...
[07:16] SPEAKER: Throw it in the trash.
[07:17] SPEAKER: Yeah.
[07:17] SPEAKER: I mean, it's still going.
[07:19] SPEAKER: It never actually died.
[07:20] SPEAKER: It still works, technically.
[07:23] SPEAKER: Like I only had one two terabyte hard drive and like a small SSD that I can install a
[07:26] SPEAKER: few games on, right?
[07:27] SPEAKER: Yeah.
[07:28] SPEAKER: And so at a certain point I saw that drive was starting to error out.
[07:31] SPEAKER: And I was like, well, I guess it's time to buy another hard drive.
[07:33] SPEAKER: Like what's big now?
[07:34] SPEAKER: You know, what can I get?
[07:35] SPEAKER: A four terabyte?
[07:35] SPEAKER: A six?
[07:36] SPEAKER: What's going on?
[07:36] SPEAKER: You just went back for another two.
[07:38] SPEAKER: No, I didn't.
[07:38] SPEAKER: Oh, okay.
[07:39] SPEAKER: That's when I stopped.
[07:41] SPEAKER: Okay.
[07:41] SPEAKER: That's when I stopped and took stock of like, okay, do I really want to go buy another hard
[07:45] SPEAKER: drive and throw it in this PC and then toss out this two terabyte one when it dies?
[07:49] SPEAKER: No.
[07:49] SPEAKER: Or should I like step up and like make something that's kind of a cool central repository for
[07:54] SPEAKER: everything and throw it on the network?
[07:55] SPEAKER: And that's when I started looking into getting the NAS.
[07:57] SPEAKER: But I actually spent the first few months pretty convinced.
[08:00] SPEAKER: I was going to get a Synology because they're by far, I mean, I've never bought one.
[08:04] SPEAKER: I've never actually used one, but from what I can tell, like by far the most like turn
[08:08] SPEAKER: key off the shelf solution.
[08:10] SPEAKER: I mean, and that's the benefit is you get, it's a, I think they're usually like atom
[08:14] SPEAKER: Intel atom processors or something.
[08:15] SPEAKER: And that's what ultimately stopped me, but we'll get to that.
[08:17] SPEAKER: So they're a little lower power, but they're relatively inexpensive.
[08:20] SPEAKER: And it's basically like a box with a little CPU and a little bit of memory that you can
[08:24] SPEAKER: jam a whole boatload of hard drives into.
[08:26] SPEAKER: It looks like a little hard drive cave.
[08:28] SPEAKER: Like if you, if you look at a picture of one, it's just a, it's like a black box with a
[08:31] SPEAKER: big gaping front where a bunch of hard drives can plug in.
[08:34] SPEAKER: Yeah.
[08:35] SPEAKER: So it's one of those things that so when I started, when I started on this path, the
[08:39] SPEAKER: choices were basically I wanted, I wanted a Plex server because I have a bunch of Blu-rays
[08:43] SPEAKER: and DVDs and stuff like that.
[08:45] SPEAKER: And I mean, this is slightly legally ambiguous territory, but like a place to dump ROMs.
[08:51] SPEAKER: Yeah, because solutions for running old games are getting pretty cool these days.
[08:56] SPEAKER: You know, you can like a Mr.
[08:58] SPEAKER: Is Mr.
[08:59] SPEAKER: Is the, is the prototypical example, but even raspberry pies will do a lot of cool stuff.
[09:03] SPEAKER: You know, we got to do a Mr.
[09:04] SPEAKER: Episode as well.
[09:05] SPEAKER: I need to buy one.
[09:05] SPEAKER: I need the same to actually start fiddling with one, but point being, there are a lot
[09:09] SPEAKER: of cool.
[09:10] SPEAKER: And then particularly a lot of embedded solutions for stuff like that now.
[09:14] SPEAKER: Yeah.
[09:14] SPEAKER: And I wanted something where like, okay, I can just keep one collection of everything,
[09:18] SPEAKER: one collection of like my movies, my music, like ROMs, whatever.
[09:21] SPEAKER: And then any device I get down the line, like if I build a Mr.
[09:24] SPEAKER: If I, I want to get a raspberry PI four at some point, just having that one SMB share
[09:28] SPEAKER: on the network.
[09:28] SPEAKER: And I can always just point whatever device I'm tinkering with at that same share at any
[09:32] SPEAKER: time and not have to worry about like, Oh, I'm going to copy 500 gig of files over to
[09:35] SPEAKER: this SD card or whatever it is.
[09:37] SPEAKER: You know what I mean?
[09:37] SPEAKER: Well, that's it.
[09:38] SPEAKER: That seems exactly right.
[09:39] SPEAKER: And, and having that stuff all in one place makes it easier to back up.
[09:43] SPEAKER: Yeah.
[09:44] SPEAKER: I like also makes it a little more challenging to back up.
[09:46] SPEAKER: We need to remember to talk about backups at the end here.
[09:50] SPEAKER: Okay. So the NAS is a place to dump a bunch of files and then maybe run some stuff on
[09:55] SPEAKER: top that gives you access to them in interesting ways.
[09:57] SPEAKER: And so we're like running stuff on top is where I kind of, that's where the record
[10:00] SPEAKER: scratch happened when I was looking at the Synology stuff.
[10:03] SPEAKER: Well, so in the two years, since you built your NAS that's that world has changed.
[10:08] SPEAKER: They have been getting better.
[10:09] SPEAKER: Yeah.
[10:09] SPEAKER: The low end processes have gotten more capable.
[10:10] SPEAKER: The software has gotten better at using the hardware extensions built into the CPU to
[10:17] SPEAKER: do like video training, like, like two years ago and NAS wouldn't have been able to do
[10:20] SPEAKER: video transcode and now probably can.
[10:23] SPEAKER: I think when I was first looking at them a couple of years ago, they were just barely
[10:25] SPEAKER: had that capability.
[10:26] SPEAKER: But like you said, they were all I think they were mostly Intel atom based.
[10:30] SPEAKER: I think there were some of the low end ones were even arm based.
[10:32] SPEAKER: Yeah.
[10:33] SPEAKER: Like not a lot of horsepower there.
[10:34] SPEAKER: Yeah.
[10:34] SPEAKER: It's you don't, you don't have the muscle.
[10:36] SPEAKER: So, so I went the other way when I did mine and just turned my old gaming PC into a NAS
[10:41] SPEAKER: box, which is the least efficient way in terms of power of electricity use.
[10:47] SPEAKER: But it's super easy.
[10:48] SPEAKER: And, you know, there's some trade offs to that, but no.
[10:52] SPEAKER: And I went with FreeNAS because it was kind of what was available.
[10:54] SPEAKER: It was either that or run a Linux machine and do everything yourself and do everything
[10:58] SPEAKER: myself.
[10:59] SPEAKER: And not the benefit at the time of FreeNAS was that it supported a file system called
[11:03] SPEAKER: ZFS.
[11:05] SPEAKER: And what ZFS does is lets you basically put a whole bunch of drives in a pool.
[11:10] SPEAKER: And as long as they're more or less the same size, you can do redundancy and stuff like
[11:14] SPEAKER: that.
[11:15] SPEAKER: It does a lot of stuff.
[11:15] SPEAKER: I mean, it's from the enterprise world.
[11:17] SPEAKER: It was conceived for servers, like what, a couple of decades ago or something.
[11:20] SPEAKER: It's been around for a long time.
[11:21] SPEAKER: Like pretty much anybody who knows their shit about storage will tell you that ZFS is the
[11:25] SPEAKER: best file system on the planet.
[11:27] SPEAKER: It's a, it's a modern file system in a way that NTFS and EXTFS kind of are not anymore.
[11:33] SPEAKER: Right.
[11:33] SPEAKER: Like it supports, it supports RAID at the file system level or at the command line level.
[11:37] SPEAKER: It's got checksumming built into it for, you know, error correction and detection.
[11:42] SPEAKER: It's got a lot of redundancy features.
[11:44] SPEAKER: It's got native snapshotting so you can have multiple versions of a drive that...
[11:48] SPEAKER: Exactly.
[11:48] SPEAKER: Or like shadow volumes is what Windows calls that, but it works way better.
[11:52] SPEAKER: Right.
[11:52] SPEAKER: All that stuff is built in at the base level.
[11:55] SPEAKER: Well, and more importantly, when it fails, you can replace a drive and it'll resilver
[11:59] SPEAKER: out, resliver out, sorry, the, like the data that was spread that was on that drive back
[12:06] SPEAKER: from the other drives over a period of hours.
[12:08] SPEAKER: So it's designed to be seamless.
[12:10] SPEAKER: It's a kind of overkill for home use.
[12:12] SPEAKER: Kind of.
[12:12] SPEAKER: Yeah.
[12:13] SPEAKER: But if you're talking about ripping a collection of like a thousand Blu-rays and DVDs, it was
[12:18] SPEAKER: at the time when like four terabyte hard drives were huge and $500, it was the only way to
[12:24] SPEAKER: keep that many movies on one volume.
[12:27] SPEAKER: And the thing about the server is it turns out you don't really need to keep that many
[12:34] SPEAKER: videos on one volume just because of the way the Plex server works.
[12:40] SPEAKER: I think Plex can combine multiple physical storage locations into one library seamlessly,
[12:47] SPEAKER: but it wasn't the case back then.
[12:49] SPEAKER: So, and one of the things we got a lot of, the reason we're doing this episode is when
[12:53] SPEAKER: we did the questions episode a couple of weeks ago, we got like six or a significant percentage
[12:59] SPEAKER: of the overall questions we received were about.
[13:01] SPEAKER: Yes.
[13:02] SPEAKER: We got just enough NAS questions that I was like, oh, we should save these and just do
[13:05] SPEAKER: a NAS episode probably.
[13:07] SPEAKER: So I think the most basic question was basically, hey, I want a NAS, should I get something
[13:11] SPEAKER: like a Synology or a QNAP, one of those embedded boxes, or should I build a machine and put
[13:16] SPEAKER: like a NAS oriented OS on it?
[13:19] SPEAKER: And honestly, where we are now, it's nice to have my own collections.
[13:23] SPEAKER: I like that a lot, but the ability to save stuff on an iPad or phone from Netflix and
[13:30] SPEAKER: Hulu and Amazon and Disney Plus and all of those over the top services.
[13:36] SPEAKER: It's like 90% of why I started with the Plex server.
[13:39] SPEAKER: Like I've had a lot of fun doing a lot of different stuff with mine that I hadn't expected
[13:43] SPEAKER: to do in the first place.
[13:44] SPEAKER: But it's been interesting to see a lot of people actually go the complete opposite direction
[13:48] SPEAKER: with the stuff and just completely issue any collection at all.
[13:51] SPEAKER: Try to like banish local storage from their lives entirely and just go cloud everything.
[13:55] SPEAKER: And I think that's totally doable.
[13:56] SPEAKER: Yeah, that is absolutely even like two years later after I built all this stuff is like
[14:01] SPEAKER: kind of a valid option.
[14:02] SPEAKER: Even if you want compute, you can spin up AWS.
[14:05] SPEAKER: You can run Plex on AWS.
[14:06] SPEAKER: Yeah, you can run on EC2.
[14:08] SPEAKER: You can run cloud compute nodes to do some of the stuff you would like to do in your
[14:12] SPEAKER: house.
[14:13] SPEAKER: So it's expensive.
[14:14] SPEAKER: It's not.
[14:15] SPEAKER: Yes.
[14:16] SPEAKER: You're looking at like minimum probably of 20 bucks a month for AWS if you have a small
[14:19] SPEAKER: collection.
[14:20] SPEAKER: Right.
[14:21] SPEAKER: But yeah, it is totally doable.
[14:25] SPEAKER: So yeah, I think you have to think about what your use cases are.
[14:29] SPEAKER: If you just want to back up a bunch of machines locally and you're talking about laptops
[14:34] SPEAKER: that have 256 gig SSDs in them, you should be able to you want to think about the amount
[14:39] SPEAKER: of data space you need for backups as enough to keep three days, three weeks and one month
[14:47] SPEAKER: or maybe three months up to three months of storage.
[14:51] SPEAKER: So what that means is you keep if it's January, that means you'll have a monthly backup from
[14:57] SPEAKER: you'll have daily backups for the last three to five days.
[15:00] SPEAKER: Right.
[15:00] SPEAKER: So it's Saturday, you'll have like a checkup on Friday, Thursday, Wednesday, Tuesday, Monday
[15:06] SPEAKER: that are all diffs, just the differential backup, just the stuff that's changed on the
[15:12] SPEAKER: hard drive from the Sunday backup.
[15:14] SPEAKER: Right.
[15:14] SPEAKER: And then you'll keep three Sundays, right?
[15:16] SPEAKER: So you'll keep the Sunday, the current Sunday, Sunday a week ago, Sunday a week before that.
[15:21] SPEAKER: And then you'll keep the first Sunday of the month for the three preceding months as well.
[15:25] SPEAKER: Like it's basically the Mac OS time machine model, right?
[15:28] SPEAKER: Exactly.
[15:28] SPEAKER: It's just like you've got by date sort of previous iterations of your storage volume.
[15:33] SPEAKER: Well, but time machine goes constantly.
[15:34] SPEAKER: It's continuous.
[15:35] SPEAKER: It never stops.
[15:36] SPEAKER: But I mean, when you browse it, they break it out by date.
[15:38] SPEAKER: Yeah.
[15:40] SPEAKER: But the upshot is, and the reason this is a good time to talk about this, I talk about
[15:44] SPEAKER: this a lot, I feel like, but the difference between redundancy and backup, redundancy
[15:47] SPEAKER: is when we talk about RAID, which is a redundant array of inexpensive disks.
[15:52] SPEAKER: And what that means is if one drive fails, the machine doesn't go down.
[15:55] SPEAKER: Yeah.
[15:55] SPEAKER: Right.
[15:56] SPEAKER: Or you don't lose any data.
[15:57] SPEAKER: You don't lose any data.
[15:58] SPEAKER: There's a bunch of different ways to do that.
[16:00] SPEAKER: RAID and redundant disks like ZFS don't save you from things like viral attacks, like virus
[16:08] SPEAKER: attacks, malware that locks you out of your computer, things like that.
[16:11] SPEAKER: Backups can actually do that.
[16:12] SPEAKER: Yeah.
[16:13] SPEAKER: So you like having a RAID array in a NAS box does not replace backing up that NAS box.
[16:19] SPEAKER: Right.
[16:20] SPEAKER: Which is for the love of God, back up your hard drives, back up your business, because
[16:27] SPEAKER: for example, if you realize today that you've deleted something two weeks ago that you really,
[16:31] SPEAKER: really need, then you can actually go back into the backup, find the file you need and
[16:36] SPEAKER: it's there.
[16:36] SPEAKER: Yeah.
[16:37] SPEAKER: The RAID, ZFS might have it.
[16:39] SPEAKER: Yeah.
[16:40] SPEAKER: Most systems won't.
[16:42] SPEAKER: A hardware RAID won't.
[16:44] SPEAKER: And back your stuff up.
[16:47] SPEAKER: That's the TLDR.
[16:49] SPEAKER: One of the neat things about using a NAS box is often you can pay, rather than paying for
[16:53] SPEAKER: a cloud backup provider for all of the computers in your house, you can just back up the storage
[16:59] SPEAKER: volume on the NAS box and you don't have to pay anybody else, which is nice.
[17:03] SPEAKER: Yes.
[17:04] SPEAKER: So yeah, I think if you're trying to decide like, "Hey, I want storage on my network.
[17:09] SPEAKER: Should I go whole hog or should I just get one of these integrated solutions?"
[17:13] SPEAKER: Basically ask yourself, "Do I just want storage on the network?
[17:16] SPEAKER: Like, do I just want a place to put files?"
[17:18] SPEAKER: Store photos and music and yeah.
[17:20] SPEAKER: And if the answer is yes, something like a Synology is totally adequate.
[17:24] SPEAKER: Yeah.
[17:24] SPEAKER: Or if you're just doing backups and you have a bunch of laptops, like an eight terabyte
[17:28] SPEAKER: USB hard drive that connects to the network and let it rip.
[17:31] SPEAKER: I mean, there are even routers that you can plug USB hard drives into that essentially
[17:35] SPEAKER: can perform the same functions.
[17:36] SPEAKER: I mean, they're going to be real light, but it gives you a place to store back.
[17:39] SPEAKER: So the benefit of going with a more powerful machine, and Synology fits into this category,
[17:44] SPEAKER: is that you'll actually be able to saturate your network connection with even a low power
[17:48] SPEAKER: dedicated NAS versus an external hard drive that has network connection.
[17:52] SPEAKER: Sure.
[17:53] SPEAKER: And definitely compared to any WiFi device.
[17:56] SPEAKER: Yeah.
[17:56] SPEAKER: So the thing that stopped me when I was looking at the Synologies, and I feel like the sweet
[18:00] SPEAKER: spot is probably like a four bay.
[18:02] SPEAKER: Probably, yeah.
[18:03] SPEAKER: That's something you could plug four hard drives into and that gives you some redundancy.
[18:06] SPEAKER: Because you want at least...
[18:07] SPEAKER: Basically, when we're talking about redundancy, what you're going to be looking at in practical
[18:10] SPEAKER: terms is losing at least one disk's worth of storage.
[18:13] SPEAKER: So if you plug in four drives and you have one drive's worth of redundancy, that means
[18:18] SPEAKER: you can lose one of those drives and not lose any data.
[18:21] SPEAKER: But that also means that the total amount of usable storage is number of drives minus
[18:25] SPEAKER: one.
[18:25] SPEAKER: So for example, if you have four terabyte drives and you plug in four four terabyte
[18:29] SPEAKER: drives and you set them up to be redundant, then you'll have 12 terabytes of storage versus
[18:35] SPEAKER: 16 terabytes of storage.
[18:36] SPEAKER: Or if you like, there are a lot of people that will tell you that you should have no
[18:40] SPEAKER: less than two drives worth of redundancy, which means that you would only have eight
[18:44] SPEAKER: terabytes of usable space out of 16 total.
[18:48] SPEAKER: So that means you can lose two drives and still not lose anything.
[18:51] SPEAKER: But this is...
[18:52] SPEAKER: And with FreeNAS, the software that runs on the Synology boxes and the software that we're
[18:56] SPEAKER: both running, we'll talk about different software in a sec, you can choose how much redundancy
[19:00] SPEAKER: you want when you set up the drive array.
[19:02] SPEAKER: It's just a question of how much storage you're willing to lose in the process.
[19:07] SPEAKER: I'm about to say something controversial.
[19:08] SPEAKER: Oh, no.
[19:10] SPEAKER: If you have a good backup scheme, I think having a good backup scheme, then that means
[19:15] SPEAKER: having something that you run and that you test and you can restore, that you know works.
[19:19] SPEAKER: You mean like a secondary backup?
[19:20] SPEAKER: I mean, just a backup.
[19:21] SPEAKER: I mean, a backup for the server.
[19:22] SPEAKER: A backup of the NAS.
[19:23] SPEAKER: Yeah, backup of the NAS.
[19:24] SPEAKER: A backup of your backup.
[19:26] SPEAKER: I mean, yeah.
[19:28] SPEAKER: Trust me, I get it.
[19:29] SPEAKER: Backup, you know, dog, backup your backup.
[19:31] SPEAKER: If you like backups, you can backup while you're backing up.
[19:34] SPEAKER: If you have a good backup scheme, that's more important than having redundancy.
[19:38] SPEAKER: I agree with that, sure.
[19:39] SPEAKER: I think redundancy for home use.
[19:41] SPEAKER: Like if you're in an office environment, and the weird thing about FreeNAS specifically
[19:45] SPEAKER: is people use it for small work group servers all the time.
[19:48] SPEAKER: Small business.
[19:49] SPEAKER: People use it for big work group servers, like 50 and 100 person work groups.
[19:52] SPEAKER: And then people also use it to play pirated movies on their flex machine in their house.
[19:56] SPEAKER: Right.
[19:58] SPEAKER: So it's a real wide range of use cases.
[20:01] SPEAKER: It's a broad spectrum NAS solution.
[20:02] SPEAKER: Yeah, and if you're the dude that's pirating a shitload of movies, probably don't bother
[20:06] SPEAKER: backing that up because they're just going to pirate them again when the hard drives bomb out.
[20:10] SPEAKER: Right.
[20:11] SPEAKER: But again, if you've got like, like I said, if you've got stuff that's like personally
[20:14] SPEAKER: important to you on there and hard to replace or irreplaceable.
[20:17] SPEAKER: Yeah.
[20:17] SPEAKER: Redundancy is nice.
[20:18] SPEAKER: Make sure, yeah, you shouldn't not have it, but it's not the end all be all of data retention.
[20:24] SPEAKER: And then it can still fail.
[20:26] SPEAKER: The nice thing about the redundancy is usually you get a smart error.
[20:30] SPEAKER: Smart is a thing that tells you when your hard drive is behaving out of the normal.
[20:35] SPEAKER: A smart error, which tells you you should go to Amazon and buy a new hard drive right then.
[20:39] SPEAKER: Smart errors mean that a dry failure may be imminent.
[20:41] SPEAKER: Exactly.
[20:42] SPEAKER: So other things to think about before you step down this path is that this isn't a cheap project.
[20:50] SPEAKER: Even if you're using like an old gaming PC, which I think both of us did for the motherboard CPU
[20:55] SPEAKER: and memory, the drives you should plan to replace the drives, especially if you're running them 24/7
[20:59] SPEAKER: every three to five years at most, you'll probably run out of space depending on what you're using
[21:06] SPEAKER: the drive for before that time. But you want to have a motherboard with a lot of SATA ports
[21:12] SPEAKER: because you're not going to be using like M2 SSDs or anything like that right now.
[21:17] SPEAKER: And you want a budget for replacing and probably upgrading the drives at least every,
[21:23] SPEAKER: like I said, three-ish.
[21:24] SPEAKER: I start getting nervous when the drives are three years old.
[21:27] SPEAKER: Okay.
[21:28] SPEAKER: Yeah.
[21:28] SPEAKER: I waited for a sale and bought a fifth drive of the type that I already had.
[21:33] SPEAKER: And it's in the closet just in case.
[21:35] SPEAKER: Well, so then the nice thing about this is you can, if you know that you're going to
[21:40] SPEAKER: move your four terabyte array to a four, eight terabyte array drive, you can kind of keep an
[21:47] SPEAKER: eye on sales and you can ride that sweet spot where you're paying a hundred bucks per drive,
[21:53] SPEAKER: but you just have to be aware of it.
[21:55] SPEAKER: Yeah.
[21:56] SPEAKER: So ultimately when I was going to, I was pretty close to pulling the trigger on a
[21:59] SPEAKER: Synology until, like I said, I started looking at like what the CPU was in there and how much
[22:03] SPEAKER: they cost and like you're kind of paying a lot for what you're getting horsepower wise.
[22:06] SPEAKER: Well, what you're paying for with the Synology is drive cage and hot swap ability and stuff like
[22:10] SPEAKER: that. And also the fact that you don't have to futz with the OS at all.
[22:14] SPEAKER: Right. It's like an ease of use. It's a turnkey integrated thing. But I started looking at like,
[22:19] SPEAKER: oh man, these enclosures are getting three, $400. And then like you said, I started looking at like
[22:25] SPEAKER: what PC hardware I had in the closet doing nothing and thinking like, I could spend about the same,
[22:30] SPEAKER: maybe a little bit, 150, $200 more and build like a whole PC with what I've already got here.
[22:35] SPEAKER: And then you don't have to transcode videos.
[22:37] SPEAKER: Yeah. And then you've got a, like a modern real proper ass, like quad cores,
[22:41] SPEAKER: Intel CPU in there and a lot of memory and a lot of headroom to do other stuff,
[22:46] SPEAKER: which is what I ended up doing.
[22:47] SPEAKER: Okay. So, so I've gotten to the point I've decided, I think this is a good idea. This
[22:51] SPEAKER: is something I need to do. What are the choices I have to make?
[22:54] SPEAKER: In terms of like what, what hardware do I use? What software do I use? Let's start with software,
[23:00] SPEAKER: but like there's a bunch of software options that weren't there when I started doing this.
[23:03] SPEAKER: That's where things have gotten weird because like, like you've been in,
[23:06] SPEAKER: you've been deep in freelance for a long time. Like, like Vinnie from China bomb is another,
[23:11] SPEAKER: he's another friend of ours who was deep into that world. So like I was able to kind of draft
[23:15] SPEAKER: off you guys and like kind of, you know, pick people's brains and stuff like that.
[23:19] SPEAKER: But the point I'm making is like, it seems like when you guys got into it,
[23:21] SPEAKER: that was kind of the only real well-supported option. And now there's a lot of stuff out there.
[23:25] SPEAKER: So at the time, like if you were really reasonably comfortable doing Linux stuff,
[23:29] SPEAKER: you could build something that was comparable, but it probably wouldn't support ZFS. And ZFS
[23:34] SPEAKER: was a big part of the draw. Cause one of the, one of the other benefits of ZFS is you can,
[23:37] SPEAKER: you can clone drives across pretty much any pipeline. So like if you have,
[23:43] SPEAKER: if you have eight drives in the machine, you can make an exact copy of one array really easily.
[23:48] SPEAKER: But also if you have enough Slack space on your system or have four extra drives in your system,
[23:53] SPEAKER: we can connect using cryptography and the internet. And like, I can back up my stuff to you and you
[23:58] SPEAKER: can back up your stuff to me. Literally use like a pipe at the command line and pipe the entire
[24:03] SPEAKER: contents of your storage volume through SSH over to your house. If you wanted to, or like some
[24:09] SPEAKER: crazy shit, I could bring my server over here and we can make a copy of my server on your server.
[24:14] SPEAKER: And it would take three days to copy over, but like it's wild. Like when you really start digging
[24:17] SPEAKER: into how flexible, and again, this is stuff like to be clear, you really need to be, you need to
[24:22] SPEAKER: be not only comfortable with the idea of spending an entire Saturday tinkering with this stuff,
[24:26] SPEAKER: but you need to feel like that might be a good time. If that's not you, then this is not something
[24:31] SPEAKER: you really want to get into. It requires a tremendous amount of, of toil. But only,
[24:37] SPEAKER: but in like sporadic chunks. Yeah, totally. To do like, to do like really esoteric stuff like that.
[24:42] SPEAKER: I mean, yeah. So, so I went with FreeNAS. There's other options out there. I think if I were doing
[24:48] SPEAKER: this today, I would probably just do a Ubuntu server. Really? So that's the thing that I'm
[24:52] SPEAKER: seeing a lot more people getting into these days because like Linux is just such a more active,
[24:59] SPEAKER: actively developed community platform. And CFS support has gotten really good on Linux.
[25:04] SPEAKER: CFS support is good on Linux. At the time when FreeNAS was relatively new or when I got into
[25:10] SPEAKER: FreeNAS, it wasn't relatively new. They had a plugin architecture so that like you didn't have
[25:15] SPEAKER: to fool with, with I can't remember what the apt-get equivalent is on FreeBSDM. You didn't
[25:23] SPEAKER: have to find a good package maintainer who's maintaining packages of Plex and whatever other
[25:29] SPEAKER: software you wanted to install. You just matched a button in the web UI and it worked. We should
[25:32] SPEAKER: step back a little bit and say basically like all the things you might want to do on a NAS that has
[25:37] SPEAKER: the headroom to do stuff besides storage. Ideally for the end user would exist in like a plugin kind
[25:43] SPEAKER: of format. Or as a package maintainer. Or as something that is like as self-contained and
[25:48] SPEAKER: easy to install and implement as possible. Yeah. The challenge of installing stuff on
[25:52] SPEAKER: BSD and Linux is that there's usually a boatload of dependencies. So like in order for Plex to work,
[25:58] SPEAKER: it has to have H.264 codecs and has to have transcode software and it has all this other
[26:02] SPEAKER: stuff. And all those libraries need to be installed in some fashion. Like nothing works,
[26:07] SPEAKER: nothing just works. Well, so at worst case you want to use like the built-in package manager to
[26:10] SPEAKER: do that. Which works kind of like the App Store in a lot of ways. You just see all the other stuff
[26:17] SPEAKER: that gets installed, whereas the App Store just does it for you. Or even better in some... I don't
[26:24] SPEAKER: actually use any Free NAS plugins anymore. I do everything at the command line in jails because
[26:29] SPEAKER: the plugins were too limited. Yeah. So that's the thing. I was going to say, that's a benefit for
[26:36] SPEAKER: Synology users who don't have the extra horsepower to run stuff in containers. I'll explain what
[26:43] SPEAKER: container. So container is like a virtual machine that runs inside the OS and lets you run a whole
[26:49] SPEAKER: other minimal version of free BSD inside like a virtual machine that's somehow very lightweight.
[26:58] SPEAKER: I don't know how that stuff works. I think it uses like virtualization, hypervisor stuff. I'm
[27:02] SPEAKER: not super clear on that stuff. But the thing I was going to say is it seems like the biggest knock
[27:07] SPEAKER: against using Free NAS right now is that it's moving away from this containerized model at
[27:11] SPEAKER: exactly the time that the entire rest of the world is going like head first in that direction.
[27:15] SPEAKER: I think, I mean, well, the jails... So Free NAS and Free BSD have a concept called jails,
[27:21] SPEAKER: which basically lets you isolate processes that may be like security risks or whatever.
[27:26] SPEAKER: It's a little sandbox version of the OS.
[27:28] SPEAKER: Yeah, exactly.
[27:29] SPEAKER: And that's where I run everything. But like you said, it means you have to get in there.
[27:32] SPEAKER: As things stand right now, you have to get in there at the command line. And if you're lucky,
[27:36] SPEAKER: just download like a pre-compiled binary package of something. If you're unlucky,
[27:41] SPEAKER: you're going to end up on the GitHub repo of the thing you want to run and literally talking to the
[27:45] SPEAKER: guy who develops it. In the one case where I had to do that, he was extremely friendly and I helped
[27:50] SPEAKER: him squash a couple of bugs because that was fun.
[27:52] SPEAKER: That was for your NUT server?
[27:53] SPEAKER: That was not for my NUT server.
[27:54] SPEAKER: Okay.
[27:55] SPEAKER: This is for the little music server that I run. On one level, it's super gratifying because I
[28:00] SPEAKER: actually went through the install script for the Free BSD compilation process and had to tweak some
[28:05] SPEAKER: stuff to make it work. And once I got it working, it was awesome. On the other hand, you really want
[28:09] SPEAKER: to spend your time doing stuff like that.
[28:11] SPEAKER: I was much more into spending my time doing stuff like that when I didn't have a seven-year-old
[28:15] SPEAKER: that I could be playing with and hanging out with instead. So yeah, this is definitely a place where
[28:22] SPEAKER: the software is free, but your time is not. So be aware of that.
[28:30] SPEAKER: At this point, I'm probably on Freeness until the next time I upgrade hard drives,
[28:34] SPEAKER: just because it's enough of a pain in the ass to migrate for 12 terabytes of data or whatever
[28:40] SPEAKER: I have on my array right now, that I'm not going to do it. I'm not confident enough in my web
[28:48] SPEAKER: backup, my internet-based backup, that I would just say, "Fuck it, I'm going to format these
[28:52] SPEAKER: drives and reinstall from scratch Ubuntu." There's other options now too, which a lot of people are
[28:58] SPEAKER: running hypervisors. We talked about this a little bit before the show, but a hypervisor is just a
[29:03] SPEAKER: virtual machine manager that lives just above the BIOS level of your computer. And then you can run
[29:08] SPEAKER: like Ubuntu and Freeness and whatever other nonsense you want to run all in the same machine.
[29:15] SPEAKER: It does a lot of the stuff that jails do in Free BSD, Freeness, off the shelf.
[29:21] SPEAKER: So unlike the extreme other end of the spectrum from the jails in Free BSD,
[29:26] SPEAKER: you hear the term "Docker" a lot. That's the containerized stuff that I was talking about
[29:30] SPEAKER: before. The model that people are moving to now is stuff like Docker. You just download a container
[29:34] SPEAKER: that has everything set up inside of it already for you. That is a true plugin, really.
[29:39] SPEAKER: It's what's a virtual machine. Docker is kind of like how EC2... It's similar to old school
[29:45] SPEAKER: virtual machines, but you can do individual applications in them, is the key.
[29:49] SPEAKER: Yeah. The upshot is that a lot of the work is done for you. You don't have to compile anything. You
[29:54] SPEAKER: generally don't have to configure much. It's kind of ready to go out of the box.
[29:57] SPEAKER: If somebody is maintaining a Docker container for something that you want,
[30:02] SPEAKER: and they didn't make weird choices, which sometimes happens because it's all open source,
[30:06] SPEAKER: then Docker containers are a really good way to do a lot of that stuff. Ubuntu supports Docker
[30:09] SPEAKER: containers much better than Freeness does now. They're actually deprecating Docker support
[30:13] SPEAKER: entirely in Free NAS. But BHive is the same concept.
[30:16] SPEAKER: Similar stuff. Yeah. But the support is just not great there. The Linux world,
[30:20] SPEAKER: that stuff is a lot better supported. I almost feel like there is a real opportunity for a
[30:26] SPEAKER: Linux-based competitor to Free NAS to come in and maybe do that stuff better.
[30:30] SPEAKER: I'm surprised that there isn't some front end for home server.
[30:33] SPEAKER: There are. There's stuff like Unraid, which is a paid closed source Linux-based.
[30:38] SPEAKER: No, thanks.
[30:39] SPEAKER: But they use different file systems. I don't think the robust storage support is there.
[30:44] SPEAKER: There's Open Media Vault, which is another Debian-based NAS kind of front end.
[30:50] SPEAKER: I don't think there's anything on the level of Free NAS out there right now in terms of feature set.
[30:53] SPEAKER: That might not be a bad thing given the scope of Free NAS is problematic sometimes. It's so big.
[31:00] SPEAKER: I guess so. I mean, it does a lot for you. It's a web-based front end.
[31:03] SPEAKER: You administrate it through a web browser.
[31:05] SPEAKER: That's true.
[31:06] SPEAKER: And it's relatively simple to set up your storage volumes,
[31:09] SPEAKER: and it'll automate periodic file system checks to make sure everything's cool.
[31:13] SPEAKER: But you also have to do a lot of reading before you set up that machine the first time.
[31:17] SPEAKER: Yes, yes.
[31:17] SPEAKER: Because you can make some choices that will really haunt you.
[31:20] SPEAKER: Yes.
[31:20] SPEAKER: As I did until the first time I upgraded my hard drives in the Free NAS box.
[31:24] SPEAKER: Sure. Yeah.
[31:25] SPEAKER: And then the other option is just to keep running Windows on the Windows machine.
[31:29] SPEAKER: Yeah, totally.
[31:29] SPEAKER: Because you can run the Plex server on top of that.
[31:31] SPEAKER: I actually, I meant to, when we were talking about like Synologies and the kind of
[31:34] SPEAKER: easier entry level stuff at the top of this, I meant to mention that like, I don't know,
[31:38] SPEAKER: 80% of the stuff you can do with some elaborate open source setup, like a Free NAS box,
[31:43] SPEAKER: you can just do with a Windows machine with drives plugged into it.
[31:46] SPEAKER: Pretty like you can run a hyper, you can run VirtualBox and run your,
[31:50] SPEAKER: your, or put a Docker container. I think you can put Docker containers on Windows.
[31:53] SPEAKER: I'm not sure about that.
[31:54] SPEAKER: I think so.
[31:54] SPEAKER: I mean, just in terms of like, you know, storage spaces and Windows will let you do basic RAID.
[31:58] SPEAKER: I don't think it's as robust as, it's definitely not as robust as what you're going to get with CFS,
[32:02] SPEAKER: but like, you can RAID drives and Windows, you can run a Plex server on Windows.
[32:06] SPEAKER: You can do a lot of that basic stuff.
[32:07] SPEAKER: Exactly.
[32:09] SPEAKER: Like you're probably not going to use CUPS to provide an AirPrint server.
[32:12] SPEAKER: AirPrint support for your 10-year-old laser printer.
[32:15] SPEAKER: Wait, does CUPS support?
[32:16] SPEAKER: It took a lot of work. I had to find a Python script and some homebrew driver somebody wrote.
[32:22] SPEAKER: Oh man, I already have a web interface for mine.
[32:23] SPEAKER: So I can show it to you later.
[32:26] SPEAKER: That's going to be fun.
[32:27] SPEAKER: Like I'm running all kinds of cool shit on, on my Free NAS machine,
[32:29] SPEAKER: but it took so much work to get a lot of it up and running that like, I,
[32:32] SPEAKER: I can't recommend it unless it really sounds like it would be fun to you.
[32:36] SPEAKER: It's like tinkering with an old car, not something you do.
[32:39] SPEAKER: Yes.
[32:40] SPEAKER: Yeah. Okay. So the other thing to think about is how much is power consumption.
[32:44] SPEAKER: If you have an old desktop PC that's running a NAS for you versus taking a small embedded processor
[32:50] SPEAKER: and a Synology or something like that, you're going to use a lot more electricity.
[32:53] SPEAKER: Like a Synology is going to be very low cost in terms of your electric bill.
[32:57] SPEAKER: In, in I mean, the hard drives still have to spin, but, but which is a lot of the energy.
[33:02] SPEAKER: Right. But you don't have like a, you don't have a gaming oriented CPU sitting there.
[33:05] SPEAKER: Yeah. Well, and also at least in the old days,
[33:08] SPEAKER: a lot of the older BSD kernels were really bad about power management because they were designed
[33:11] SPEAKER: for servers. They actually still are. Yeah. So really, I don't know in the weeds you want to get
[33:15] SPEAKER: on this stuff. So the CPU is basically running a hundred percent all the time. Like I'm running,
[33:19] SPEAKER: um, basically what I ended up doing was like, you could run a Free NAS machine on like a, um,
[33:24] SPEAKER: easily like a Core i3 or even like, don't they still sell Pentiums, right?
[33:29] SPEAKER: Pentium is a, yeah, it's a straight down. It's like a, it's a sub i3.
[33:32] SPEAKER: Yeah. It's between Atom and Core. Like you could, from what I've read,
[33:36] SPEAKER: you could run a Free NAS machine on a Pentium just fine. But I had a mother,
[33:39] SPEAKER: I had an old motherboard, but not an old CPU. Okay.
[33:41] SPEAKER: And I was going to have to buy a CPU to put in that board. And when I started
[33:44] SPEAKER: looking at the price difference between an i3 and an i7, it was like 50 bucks.
[33:48] SPEAKER: Yeah. And you bought the i7? No. Well, so yeah, what I did was like,
[33:51] SPEAKER: wait, I could buy a better CPU for my gaming machine and put this old CPU from the gaming
[33:55] SPEAKER: machine in the NAS. Oh, perfect.
[33:57] SPEAKER: So that's how everybody wins. So that's how I ended up with 6,700 K in my NAS.
[34:01] SPEAKER: Oh, okay. The reason I brought this up is that what you said about the power consumption is
[34:05] SPEAKER: definitely true because I found after I got that thing up and running that even right now,
[34:09] SPEAKER: Free NAS out of the box will not put that CPU into a low power state when it's idle.
[34:13] SPEAKER: No. So I looked at the power consumption
[34:15] SPEAKER: and it was sitting there running at four gigahertz, 24/7 for no reason.
[34:18] SPEAKER: Did you figure out how to fix that? Yeah.
[34:19] SPEAKER: Oh, I need to talk to you about that. Yes. I can show you.
[34:22] SPEAKER: I did it on the last machine that I built and then the new one,
[34:25] SPEAKER: I haven't figured out how to do it again. You can set the C-state of the CPU. C-states
[34:29] SPEAKER: are our power levels, basically like frequency and voltage.
[34:33] SPEAKER: On a boot up or something. Yeah.
[34:35] SPEAKER: You set it as a tunable in the Free NAS interface.
[34:37] SPEAKER: Oh, interesting. You need to set it to C3, I think.
[34:40] SPEAKER: I mean, I looked at my power consumption for my Free NAS server and it's like 20 bucks a month.
[34:43] SPEAKER: Yeah. I think it added somewhere around $10 a month for me.
[34:48] SPEAKER: Because of the way the tiers work where we are, it pushed us into the next higher tiers,
[34:52] SPEAKER: we started paying penalty. It kind of sucks.
[34:54] SPEAKER: Yeah. But at the same time, like I said,
[34:56] SPEAKER: I've got that print server running on there. I'm running Homebridge, which I know we've talked
[34:59] SPEAKER: about before, which gives you Apple Home support on home automation devices that don't natively
[35:04] SPEAKER: have it. Stuff like that. I'm running a bunch of little services in the background that do
[35:09] SPEAKER: little stuff around the house. It's very useful.
[35:11] SPEAKER: So it is useful to leave that thing on all the time, even if it does kind of cost.
[35:15] SPEAKER: Yeah. 240 bucks a year versus buying a new $100 printer.
[35:21] SPEAKER: But you didn't send a printer to landfill, Brad. That's the important thing.
[35:23] SPEAKER: I made use of something I had. Exactly.
[35:25] SPEAKER: Reduce, reuse, recycle. Which is always the goal.
[35:28] SPEAKER: Okay. So we can talk about what we run a little bit. You've done it. I'm running an X99 board
[35:32] SPEAKER: with whatever my last, I think a 6850K, which is a hexa core, old hexa core.
[35:37] SPEAKER: I'm actually using an ASIS gaming. I had a motherboard in the closet that I've never
[35:42] SPEAKER: used that I got as part of a bundle, but I didn't necessarily want that board,
[35:45] SPEAKER: but that's what I ended up with. So I had bought a different board.
[35:48] SPEAKER: So the one thing that's really nice that I wish that the board that I'm using now
[35:52] SPEAKER: had that it doesn't is the serial port over network support. So you can basically get the
[35:58] SPEAKER: serial console, which gives you console into it without having to go into the other room.
[36:05] SPEAKER: Because like right now it's up on a shelf in my garage. And in order for me to get it down,
[36:10] SPEAKER: when I need to fix something that breaks, which happens like realistically, maybe once a year,
[36:15] SPEAKER: I have to turn it off. That sucks.
[36:16] SPEAKER: I have to unplug it. I have to carry it down into the living room. I have to plug it into
[36:19] SPEAKER: a monitor and keyboard, put a video card in. Wait, you can't just SSH into it?
[36:23] SPEAKER: Depends on how broken it is. Oh, that's very broken.
[36:25] SPEAKER: Yeah. If it's broken enough that it's not booting into free, it's stuck at the boot menu.
[36:27] SPEAKER: I see. I see.
[36:28] SPEAKER: Then I have to unplug it and plug it into a monitor and keyboard. But I mean,
[36:33] SPEAKER: all the other side of that is that the motherboards that support that console over
[36:39] SPEAKER: network standard are like server motherboards. So you're gonna have to buy a separate motherboard,
[36:43] SPEAKER: which may or may not be something you want. IPEMI, I think is the name for that.
[36:46] SPEAKER: IPEI. Then he has one of those.
[36:48] SPEAKER: Oh, really? His board has that. Of course he does. Jealous.
[36:51] SPEAKER: Storage. Let's see. One of the questions we got was about which drives to buy.
[36:57] SPEAKER: The manufacturers are making drives that are labeled NAS drives now.
[37:00] SPEAKER: Western Digital codes theirs by color. It's like...
[37:02] SPEAKER: Reds, I think.
[37:03] SPEAKER: Yeah. So I think greens are the cheap or the budget drives. Blacks are sort of like your
[37:07] SPEAKER: gaming performance drive. Nobody should buy black drives anymore. No,
[37:10] SPEAKER: 'cause you have an SSD for that stuff. Oh, sure. Yes. Yes. And reds are the
[37:15] SPEAKER: quote unquote NAS drives. Yeah. So the difference is that they're rated for different MBTFs
[37:20] SPEAKER: because the NAS drives are assumed to be always on.
[37:22] SPEAKER: Is that mean time between failure? Mean time between failure. And the way I buy drives
[37:28] SPEAKER: isn't by looking at what type they buy. Backblaze, which is one of the online backup companies,
[37:33] SPEAKER: does a few times a year, a really good roundup of here are the drives that we've bought over
[37:38] SPEAKER: the last year and they're buying tens of thousands of drives a month. Here's what's failed at what
[37:43] SPEAKER: rates. Yeah. They've got really detailed statistics on their failure rates. That's how I ended up
[37:47] SPEAKER: buying my drives too. And I go and look at specific model numbers there and buy the drives
[37:52] SPEAKER: that they're... There's always stuff on the edge that looks good, that they've only bought 500
[37:57] SPEAKER: drives. You wanna get into the fat part where it's like, we bought 10,000 of these and a 10th
[38:02] SPEAKER: of a percent have failed after three years. Something that they have healthy five figures of
[38:06] SPEAKER: in their network. One thing that's worth pointing out. So when I was looking at drives, I almost
[38:11] SPEAKER: bought some 7,200 RPM drives. Yeah. Don't. Which is, yeah, totally not worth it 'cause not only do
[38:16] SPEAKER: they put out more heat and use more energy and I'm guessing maybe don't last as long. I could
[38:20] SPEAKER: be wrong on that. More heat, more energy usually means that they don't last as long. I can't say
[38:24] SPEAKER: for sure that they fail faster than a 5,400 RPM. But it's not necessary. But yeah, the big thing
[38:28] SPEAKER: is... The big thing to know is that your storage is gonna be constrained by your network speed.
[38:31] SPEAKER: Yeah. Like you're not... I mean, some stuff you do on the machine itself is gonna obviously gonna
[38:35] SPEAKER: be accessing the drives. Maybe it's... This network tops out at like a little over 100...
[38:42] SPEAKER: 950 megabits per second. Yeah. So it's a little over a hundred megabytes a second.
[38:46] SPEAKER: Yeah. I don't think spinning potters will get over a hundred megabytes a second probably.
[38:52] SPEAKER: Maybe. Maybe. Maybe it's equivalent. I don't know. I can't remember. It's been a long time.
[38:56] SPEAKER: Yeah. But the point is you're gonna put a cache... I would recommend putting a cache.
[39:02] SPEAKER: So there's three types of storage that are gonna be in your free NAS box. You're gonna
[39:05] SPEAKER: have something that you boot off of that the OS is installed onto. And in the old days,
[39:10] SPEAKER: they recommended you use a USB thumb drive for that.
[39:12] SPEAKER: They still do, but that can be spotty because those USB thumb drives are such shitty products
[39:18] SPEAKER: that they fail a lot. Yeah. So you can buy a 128 gigabyte SSD for 20 bucks now. That's what you're
[39:25] SPEAKER: gonna install your OS to because it's reliable and good. Yeah. That's a good thing to put your...
[39:29] SPEAKER: You're gonna have a cache drive potentially. So that...
[39:34] SPEAKER: This is optional. Maybe less true than it used to be.
[39:36] SPEAKER: Oh, really? But yeah. Oh, well, I just put an old 128.
[39:39] SPEAKER: Listen to this old man. It's been a while since you've been in the game.
[39:42] SPEAKER: Oh, but I can buy a day. I have to have a cache drive.
[39:46] SPEAKER: My understanding is that that's relevant to some workloads, especially in workplace type.
[39:50] SPEAKER: Heavy reads and writes. Yeah. I think it's only really relevant to heavy sequential reads.
[39:56] SPEAKER: Oh, good to know. Oh, okay. Well, I'll investigate further.
[39:59] SPEAKER: The free NAS people... And this is for free NAS only. I can't speak to other stuff,
[40:02] SPEAKER: but they have a lot of recommendations out there now. They straight up have a blog post
[40:06] SPEAKER: that you can Google pretty easily. Oh, that's like a media server?
[40:09] SPEAKER: Well, no. Specifically, it's like, "Hey, what hardware should I buy?"
[40:11] SPEAKER: Yeah. And it's just like, "Okay,
[40:13] SPEAKER: here's how much memory you actually realistically need for how much storage you want. Should you put
[40:16] SPEAKER: in a cache drive like you mentioned? Maybe, maybe, probably not, depending on what you're doing with
[40:20] SPEAKER: it." They have good guidelines out there now for if you really want to build a machine like this.
[40:25] SPEAKER: Yeah. They didn't have that when I did it last time.
[40:27] SPEAKER: That, I think, a blog post is three years old or something.
[40:29] SPEAKER: Okay. So maybe you made it out of cache drive, but definitely installing on the SSD. I was
[40:34] SPEAKER: losing USB thumb drives at a rate of one a year for a while there.
[40:38] SPEAKER: I had to die in the last six months. Even buying expensive... I was buying nice brand name...
[40:44] SPEAKER: Totally. Yeah. I'm buying the nicest... It's funny. I started to say I was buying the most
[40:48] SPEAKER: expensive Samsung flash drives I could get. And by that, I mean they're $12 a piece because that's
[40:53] SPEAKER: literally for a 32 gig flash drive, that's the most you can spend on one. And I was like, "Surely,
[40:58] SPEAKER: these will last because it's the nicest." But yeah, and I had one fail or start failing,
[41:04] SPEAKER: like throwing errors and put off. I was like, "Ah, the other one's fine. I can let it go."
[41:08] SPEAKER: I put it off for like three months and then the other one started failing and then the whole
[41:11] SPEAKER: machine went down. Yeah. No, it's not great.
[41:13] SPEAKER: Recovering it was terrifying. So yeah, I like backblaze. I've had really good luck
[41:19] SPEAKER: using the backblaze method to figure out what drives to buy.
[41:21] SPEAKER: Yeah. But do you feel like NAS drives are generally worth it?
[41:27] SPEAKER: I think... They tend to have better warranties.
[41:29] SPEAKER: So they have better warranties. They're usually three-year warranties rather than
[41:32] SPEAKER: one-year warranties. So you might get a failure in that three years?
[41:35] SPEAKER: I have had warranty replaced NAS drives. The other thing is, at least the time I had the
[41:40] SPEAKER: drive fail, the NAS drive fail, they did a cross-ship for me, which was nice.
[41:45] SPEAKER: So they shipped me the new drive. I had to give them a credit card, obviously,
[41:48] SPEAKER: but they shipped me the new drive and that never happened when I had a consumer drive fail.
[41:53] SPEAKER: They are supposedly made to be a little more resilient and more...
[41:57] SPEAKER: Slightly better lube on the bearings.
[41:59] SPEAKER: Maybe. Yes, I don't know.
[42:00] SPEAKER: But they're made to run 24/7 for longer periods of time.
[42:04] SPEAKER: I'm always terrified turning off a drive. My guess is that probably they do use a
[42:09] SPEAKER: different lubrication on the bearings because they're designed to be on all the time.
[42:12] SPEAKER: Yeah.
[42:13] SPEAKER: Because the scary thing, when I was starting out in IT, my boss told me, "Oh yeah, on this server,
[42:18] SPEAKER: if you turn it off for more than an hour or two, you got to whack the hard drive with a hammer
[42:22] SPEAKER: when it spins back up," which basically just jars the lubricant in the bearings enough that
[42:28] SPEAKER: they were able to get over the rotational friction from the... Yeah. Anyway, it was scary.
[42:34] SPEAKER: I don't like that.
[42:35] SPEAKER: I'm always scared turning it off. I just like to leave it on all the time.
[42:37] SPEAKER: Yeah. That's probably safe.
[42:38] SPEAKER: I mean, another issue you run into in this category is should you pay for the ones that
[42:44] SPEAKER: are actually labeled NAS or should you do like a lot of people do now and shuck drives out of
[42:49] SPEAKER: the Western Digital enclosures because supposedly those are the same thing.
[42:52] SPEAKER: I'm always scared to shuck drives.
[42:53] SPEAKER: Yeah. Same here.
[42:54] SPEAKER: And also sometimes they have non-standard interfaces on the shuck drives.
[42:57] SPEAKER: Yeah. Occasionally, you'll have to put a piece of tape over one of the pins or something to
[43:01] SPEAKER: get it to spin up.
[43:02] SPEAKER: When you say shuck a drive, you mean take an external enclosure that they sell at Best Buy
[43:06] SPEAKER: for cheap.
[43:06] SPEAKER: Yes. Yes.
[43:07] SPEAKER: Yeah.
[43:08] SPEAKER: For a long period of time, at least the internet scuttlebutt was... I don't know how well this was
[43:12] SPEAKER: ever actually confirmed, but supposedly the white label drives in those enclosures, and by white
[43:17] SPEAKER: label, I mean unmarked OEM labeled drives, were supposedly reds.
[43:22] SPEAKER: That would make sense.
[43:23] SPEAKER: So you were getting the nice high-end NAS drive for two-thirds of the price or something like
[43:27] SPEAKER: that? That's never really been confirmed? Yeah. I'm like you. I'm not brave enough.
[43:32] SPEAKER: I would rather pay the premium.
[43:33] SPEAKER: It's cheaper to pay the extra 10 bucks because the thing is it's not that much of a premium.
[43:37] SPEAKER: Yeah. Again, I'm putting old family home movies and stuff on this thing. Data that is personally
[43:43] SPEAKER: important to me, I'm willing to pay a little bit extra.
[43:46] SPEAKER: So a blue one-terabyte drive is 45 bucks right now. A red... Well, they don't make red.
[43:53] SPEAKER: I don't know if they even make one-terabyte reds anymore.
[43:54] SPEAKER: No, they don't make red one-terabytes. So a 12-terabyte... Jesus, I got to get new drives.
[43:58] SPEAKER: A 12-terabyte red drive is 363 bucks on Amazon right now.
[44:03] SPEAKER: Mine are six. I think they were like 180 bucks each.
[44:05] SPEAKER: I think my guess is eight is probably the sweet spot right now.
[44:08] SPEAKER: Yeah.
[44:08] SPEAKER: So red...
[44:09] SPEAKER: They go on sale a lot. The 10-gig reds were like 130 bucks for a little while there.
[44:15] SPEAKER: So red eight is getting... So the other thing is sometimes things get expensive because demand for
[44:19] SPEAKER: a specific size goes up because somebody who's a data designer buys 4,000 of the same drive from
[44:25] SPEAKER: Amazon. So 10-terabyte reds are not available right now. That's weird.
[44:30] SPEAKER: Like I said, they were on sale a while back.
[44:32] SPEAKER: Oh yeah, they were on a hell of a sale if they were 150 bucks because they're 250 used on Amazon.
[44:35] SPEAKER: Maybe it was 180 or something like that, but they were on a deep sale.
[44:38] SPEAKER: Anyway, the point is you don't want to buy the biggest drive, even though that's going to be
[44:43] SPEAKER: your initial... You want to buy middle of the back because that's where your price per...
[44:47] SPEAKER: Look at price per terabyte or price per gigabyte, not overall price for your drives.
[44:51] SPEAKER: Yeah.
[44:52] SPEAKER: Let's see what an eight-terabyte blue drive costs just for comparison.
[44:56] SPEAKER: And blues are 7,200 RPM, I think, usually. Maybe not.
[44:59] SPEAKER: So six-terabyte single drive blue is 137 bucks. So it is a pretty good premium there.
[45:04] SPEAKER: Anyway, we talked about add-ons, the other stuff you can run.
[45:09] SPEAKER: That matters much more if you're buying an embedded NAS, something like a Synology
[45:14] SPEAKER: or something like that. I think Synology, you can get to a command line, you can run more and more
[45:18] SPEAKER: of what you want on it. But if you're buying something that doesn't run in an x86 CPU,
[45:22] SPEAKER: especially, you're going to be limited in what you can run based on what their package is for.
[45:27] SPEAKER: So look at that stuff in advance. That's it. I like Plex. I used to run Subsonic until
[45:38] SPEAKER: Spotify added Beatles and Led Zeppelin a few years ago.
[45:42] SPEAKER: You don't need that.
[45:42] SPEAKER: And then I was like, "I'm probably fine now."
[45:44] SPEAKER: Like I said, I'm running that little home music server to stream my...
[45:48] SPEAKER: That's what Subsonic does, basically.
[45:50] SPEAKER: I'm running my... I mean, we could sit here all day and talk about the stuff. I'm running
[45:53] SPEAKER: the controller for my Wi-Fi access point.
[45:55] SPEAKER: I think you're running much better stuff than I am.
[45:57] SPEAKER: On the NAS.
[45:57] SPEAKER: What's the controller for your Wi-Fi access point?
[45:59] SPEAKER: It's the UniFi controller. It's Ubiquiti stuff.
[46:01] SPEAKER: Oh, okay.
[46:02] SPEAKER: The interface, the management interface for the Wi-Fi access point does not run on the access point.
[46:06] SPEAKER: Of course not. You have to run it on an external machine.
[46:09] SPEAKER: This is why people shouldn't... Anyway, okay. Different conversation.
[46:11] SPEAKER: You could run it in Windows if you wanted to.
[46:13] SPEAKER: You're running your power, your NUT server.
[46:16] SPEAKER: Never even talked about my NUT server.
[46:18] SPEAKER: I know.
[46:18] SPEAKER: You've been wanting to talk about your NUT server for ages.
[46:20] SPEAKER: I bought a UPS that has been sitting in the box under my desk for the last six weeks.
[46:24] SPEAKER: Uninterruptible power supply.
[46:26] SPEAKER: Finally spent the last few days setting it up.
[46:28] SPEAKER: Okay. How does it work?
[46:30] SPEAKER: So modern UPSs have USB ports on them.
[46:32] SPEAKER: Yes.
[46:32] SPEAKER: And they can report out a ton of diagnostic info over that port.
[46:36] SPEAKER: There's an open source package called Network UPS Tools, or NUT.
[46:40] SPEAKER: I'm shaking my head.
[46:42] SPEAKER: That... It's pretty flexible. It can do a lot of stuff,
[46:45] SPEAKER: but I ended up installing it on a Raspberry Pi and plugging that into the UPS.
[46:49] SPEAKER: Okay.
[46:49] SPEAKER: And then...
[46:50] SPEAKER: Why not just run it on the FreeNAS server?
[46:52] SPEAKER: I wanted it running on a separate... So we could sit here all day and digress about this stuff.
[46:57] SPEAKER: FreeNAS is an appliance. That's how the developer looks at it.
[47:00] SPEAKER: Okay.
[47:01] SPEAKER: Like they don't want you in there monkeying with stuff more than you really should be.
[47:04] SPEAKER: Or if you do, they want you to stay in jail.
[47:06] SPEAKER: You should do it all in jails, like running system level services in FreeNAS
[47:10] SPEAKER: that are outside the scope of FreeNAS is not the best idea.
[47:13] SPEAKER: This is a really important point because I did this at the beginning and I really messed myself up.
[47:16] SPEAKER: Yes. You really... You should not be
[47:18] SPEAKER: installing external software directly on the base FreeNAS system at all.
[47:21] SPEAKER: The reason you don't want to do that is when FreeNAS upgrades,
[47:24] SPEAKER: it will wipe away everything you do that's in the base OS.
[47:27] SPEAKER: And you can end up overwriting things they've customized and screw stuff up. It's a bad idea.
[47:32] SPEAKER: Yeah. But the jails give you the flexibility...
[47:35] SPEAKER: Yes. There's no downside to using jails.
[47:37] SPEAKER: I very well probably could have run in a jail, I guess. Although in this use case,
[47:44] SPEAKER: the base FreeNAS system is also a nut client.
[47:46] SPEAKER: You could do that.
[47:47] SPEAKER: Probably could, but I wanted something low power to run the thing that manages the UPS on
[47:52] SPEAKER: in case the power goes out so it doesn't drain the battery fast.
[47:55] SPEAKER: And you want to be able to run that after the FreeNAS machine is off.
[47:58] SPEAKER: That's what that's really... Yes. That's actually what I'm getting at.
[48:01] SPEAKER: So Raspberry Pi uses like what? A watt and a half or something.
[48:03] SPEAKER: Yeah. It's like a phone. So I'm using that as the nut server.
[48:06] SPEAKER: And plus what's a fucking... What is a Raspbian installation on in terms of sentimental value?
[48:11] SPEAKER: You can just hose that thing and start over. It takes like 10 minutes.
[48:13] SPEAKER: In 10 minutes, if you feel like you screwed something up.
[48:17] SPEAKER: Point being, I've got that thing monitoring the NAS... I mean the UPS.
[48:20] SPEAKER: So it keeps track of what the charge level is. Is it on wall power or battery, etcetera, etcetera.
[48:26] SPEAKER: You can set up conditions on it. So I have it set up so that when it either hits 50% battery
[48:32] SPEAKER: or 15 minutes left of runtime, whichever comes first. Okay.
[48:35] SPEAKER: I'm running the nut client service on the FreeNAS machine and my Windows machine.
[48:39] SPEAKER: So if those machines are on, the Raspberry Pi will tell them to shut down.
[48:42] SPEAKER: Wow. They shut down.
[48:43] SPEAKER: Wait, are those machines plugged into the UPS too?
[48:46] SPEAKER: Yeah. Okay.
[48:47] SPEAKER: Yes. So if I happen to go out, if I happen to leave the house with both those machines on
[48:50] SPEAKER: and the power goes out and the battery gets down to half,
[48:52] SPEAKER: then the Raspberry Pi tells those machines to shut down.
[48:54] SPEAKER: Does it turn off your monitors too? They're so small.
[48:57] SPEAKER: They're not plugged in the electricity. Very funny. They're not plugged into the UPS.
[49:00] SPEAKER: Okay. That's probably best.
[49:02] SPEAKER: Anyway, like whatever. I won't sit here and ramble about it, but like my,
[49:05] SPEAKER: my router also runs Linux. So I figured I should try to get that gracefully shut down in case of
[49:09] SPEAKER: power outage. Sure.
[49:10] SPEAKER: So I spent some time figuring out how to get the, wow, the nut server to also tell the router to
[49:15] SPEAKER: shut down because running nut on the router was not an option.
[49:18] SPEAKER: This is a deep level of nerdery. I wasn't expecting that today.
[49:21] SPEAKER: I had figured out that I could tell the, I could have the Pi SSH, a shutdown command through the
[49:25] SPEAKER: router, but I needed it to work without me being there to type the password in. So I generated a
[49:30] SPEAKER: private key pair. Wow.
[49:31] SPEAKER: So that the nut could tell the router what to do without authenticating.
[49:34] SPEAKER: So I think the weirdest thing that I run on my Plex, on my server, I run home kit,
[49:41] SPEAKER: whichever, which if you do any home automation stuff is really handy.
[49:44] SPEAKER: Homebridge. Homebridge.
[49:45] SPEAKER: Yeah. Yeah. I've got that.
[49:47] SPEAKER: I used to run my DVD ripping software in a virtual machine.
[49:52] SPEAKER: Huh? It stopped working when they,
[49:54] SPEAKER: when they took away PHP, the, the virtual box client for free NAS a few, few versions ago.
[50:00] SPEAKER: But I rebuilt it in Docker and that worked okay for a while.
[50:03] SPEAKER: Now I just do it on the desktop because my desktop machines way faster.
[50:08] SPEAKER: But I run a tool that organizes media in my folders.
[50:14] SPEAKER: So I just dump when I rip something, I dump it in a folder and it looks at the file name,
[50:19] SPEAKER: which is usually like blues brothers 19. It's the, it's the movie name and the year
[50:24] SPEAKER: that it came out and it goes and hits the free DDB databases for movies,
[50:30] SPEAKER: the movie database and all that stuff at TV stuff.
[50:32] SPEAKER: If it's a TV show and it, it puts it in because Plex now is recommending
[50:37] SPEAKER: that you put movies in a folder. Plex has a weirdly insistent that you name
[50:41] SPEAKER: all your files and directories in a certain way.
[50:43] SPEAKER: Well, and, and if you want to do like extra features,
[50:46] SPEAKER: cause I've started ripping extra features on all old DVDs.
[50:50] SPEAKER: You got to put everything in subfolders. Yeah. That sounds like a huge pain.
[50:53] SPEAKER: So it does it all automatically for me. It's just some script I found that some dude wrote.
[50:57] SPEAKER: And those are always the best, some script or some tiny program that somebody wrote.
[51:02] SPEAKER: Yeah, exactly. I mean, that, that is the cool thing about this. Is it like somebody
[51:06] SPEAKER: will have had a problem and they'll solve it by going and writing this big long bash script
[51:11] SPEAKER: or something. And then they just check it up on GitHub with some documentation.
[51:15] SPEAKER: Like that. I mean, again, not to ramble about this forever,
[51:18] SPEAKER: but that might be the most gratifying interaction I've had with a human being
[51:20] SPEAKER: on the internet in years was trying to help the author of this little music
[51:24] SPEAKER: server debug a couple of problems. He didn't call you a noob or anything.
[51:26] SPEAKER: Oh, he was super, he went, he went and forked. He, he forked the repo with a custom
[51:31] SPEAKER: debug level logging change specifically for me. That's awesome. He said, Hey,
[51:35] SPEAKER: clone into this branch and compile that and run it. And then send me the log.
[51:40] SPEAKER: Like, yeah, it's kind of amazing. There's something really fun about
[51:43] SPEAKER: running a machine that you can do almost everything from the command line on.
[51:46] SPEAKER: Totally. And the best part is like when he did that, I didn't actually go through the
[51:52] SPEAKER: get process of cloning that repo. I just went and looked at the branch. I went and looked at
[51:56] SPEAKER: the change he made. And then I went into the source that was hurting on my machine and changed
[51:59] SPEAKER: it myself. I just recompiled it. Like it's so fun messing with that stuff.
[52:03] SPEAKER: So there's some stuff that I learned along the way. And I think there's stuff you learned
[52:06] SPEAKER: a long way, and they also are doing much better about giving guidelines to people who are like
[52:11] SPEAKER: building home servers now. Cause when I started, it was pretty much like, Oh, you wanted to use
[52:15] SPEAKER: this for home. You're crazy. The big one is memory requirements. Well, okay. Actually the very biggest
[52:23] SPEAKER: one that I found is that it's really important when you set up a machine to document all the
[52:26] SPEAKER: stuff you install on it so that if it ever fails and you have to rebuild it or you want to like,
[52:31] SPEAKER: whatever, if something bad happens, it's much better to find out that you forgot to reinstall
[52:36] SPEAKER: home kit by looking at the list of things you have installed. Like I just have a Google doc
[52:40] SPEAKER: that is basically, here's all of the stuff that's installed. Here's whether it lives in a jail with
[52:44] SPEAKER: something else. Here's whether it lives in a July on its own. And, and here's like, like the, like,
[52:50] SPEAKER: here's the command line flag that I tripped to set the CPU power state. Cause I like,
[52:56] SPEAKER: like you don't want to have to remember because you will forget about all this stuff. Like right
[52:59] SPEAKER: now I'm like super hot on all this UPS stuff. I spent all this time setting up, but six months
[53:03] SPEAKER: from now I've forgotten 90% of what I did. Yeah. And like, like I'm going to make an image of the
[53:08] SPEAKER: SD card in that raspberry PI, just in case that thing dies and I need to restore it without doing
[53:12] SPEAKER: all that work. Well, and you want to save, not just like the information, the settings, but you
[53:16] SPEAKER: want to save the source so you can go back and figure out like, like where, how you, how you
[53:22] SPEAKER: backed into getting this Debian port of something to run on a free NAS jail. Right. I've got an
[53:26] SPEAKER: entire folder of, of links to web tutorials on stuff like that. Exactly. It's a deep ass rabbit
[53:32] SPEAKER: hole and make sure that this is really something you want to spend your time on. And I've even on
[53:36] SPEAKER: some of them, especially if it's on message boards, I've copied the actual information and pasted it
[53:40] SPEAKER: in because those links will change. You're worried that stuff will go away at some point. So yeah.
[53:46] SPEAKER: When I was starting this out, they told you to do one terabyte of storage of Ram for every,
[53:51] SPEAKER: sorry, one gigabyte of Ram for every terabyte of storage in your ZFS, which I think is not.
[53:55] SPEAKER: That is the, that's that has been the common perception, but that's not according to that
[53:58] SPEAKER: blog post from the free NAS people. Like I said, it's not necessary anymore. I said, I want,
[54:02] SPEAKER: I think they said up to about a hundred terabytes of storage. You're good with, I want to say 24 gig
[54:06] SPEAKER: of memory or maybe even 16. That's pretty good. Yeah. I've got 16 and it's totally fine. So I
[54:13] SPEAKER: had some Ram fail last year and went down to, I think eight for awhile. That was definitely
[54:18] SPEAKER: not bad. I guess that I guess it was constantly paging with a 16 terabyte CFS started as a server
[54:25] SPEAKER: file system, like portability and like efficiency. I don't think we're probably primary design goals.
[54:30] SPEAKER: No. ECC Ram. They used to always recommend that you use ECC Ram. ECC Ram has built an error
[54:37] SPEAKER: correction and it's a little bit slower and a lot more expensive. Usually requires a special
[54:41] SPEAKER: motherboard and processor. Oh, right. And tell us about that stuff. Sometimes depends on how
[54:47] SPEAKER: old the processor is. Well, last I checked, this was two years ago, but I threes could use ECC
[54:53] SPEAKER: memory and I sevens could not, of course, because they want you to buy a Z if you want the horsepower
[54:57] SPEAKER: of an I seven, they want you to pay for a Xeon. So it's, it's forney. But the upshot is the reason
[55:03] SPEAKER: you need ECC is in case a cosmic Ray hits the Ram while something that's about to be written in ZFS
[55:08] SPEAKER: is in memory. Yeah. You're probably okay. Yeah. I mean, it's the same as every other file system.
[55:13] SPEAKER: Yeah. Like it's not, you're not increasing your chances. There's some weird urban legend that
[55:17] SPEAKER: there, the CFS is prone to data corruption, which is the opposite of true. Yeah. But if you have
[55:23] SPEAKER: mission critical data, then if you're building a server for work for this by ECC, we want ECC.
[55:29] SPEAKER: Yeah. If you're doing it to save your movies at home and like it only matters during rights.
[55:35] SPEAKER: Also, that's the other thing. It's not, it's not going to like, you're not going to lose something
[55:39] SPEAKER: during a read. And for most of most home uses, rights are infrequent and reads are more frequent.
[55:45] SPEAKER: This, this, this whole thing about ECC memory turned into like an old school internet flame war
[55:49] SPEAKER: from what I saw. I'm sure we're going to get comments to the point that there's like a,
[55:53] SPEAKER: there's kind of an infamous forum thread where one of the authors of ZFS stepped into this thread and
[55:57] SPEAKER: basically said, no, no. Yeah. You don't have to worry about this. It's not actually like that.
[56:01] SPEAKER: It's no more prone to this than any other file system. Yeah. I think that's it. Yeah. I think
[56:07] SPEAKER: those are the big ones for me. I feel bad. This was a really rambly episode of this thing.
[56:12] SPEAKER: It's a big topic. There's a lot. And it's, it's, I mean, kind of running one of these
[56:17] SPEAKER: servers is a big rambly topic. Yes, it really is. I can feel my beard growing longer and turning
[56:24] SPEAKER: grayer as we talk about this. It's one of those things that like, you'll be, you'll have a problem
[56:29] SPEAKER: you want to solve and you troll down a bunch of message board threads. It's really important when
[56:34] SPEAKER: you're searching for information on this to look for the version numbers specific, specifically the
[56:38] SPEAKER: version you're running, like the whole string, it's like 10.7.639-U3. And that'll, that'll help
[56:46] SPEAKER: cut down a lot of the noise. I ran into a problem with my wifi controller last week because they
[56:51] SPEAKER: don't support the current version of MongoDB. They only support the previous version, but this is why
[56:55] SPEAKER: I want to switch to Ubuntu, but the package had gotten updated to the newer version. So it broke
[56:59] SPEAKER: part of the controller. So yeah, it's oh, other, other thing I learned the hard way. Don't if you
[57:06] SPEAKER: don't upgrade without making sure you read the release notes really thoroughly to make sure
[57:10] SPEAKER: you're not doing something that's going to break the upgrade. If you do upgrade, you can always
[57:14] SPEAKER: roll back to the last version really easily because it's all just stored in ZFS. I have,
[57:17] SPEAKER: I have fully become the guy who doesn't want to update anything that's working at this point. No,
[57:22] SPEAKER: no, no. Yeah. If it's working and it's still supported, still getting security patches,
[57:25] SPEAKER: never update. Like the thrill of updating firmware and seeing the version number go up. Like you have
[57:29] SPEAKER: to a hundred percent let go of that because it will screw you more often than not for no benefit.
[57:34] SPEAKER: Assume you're going to spend at least an afternoon fixing shit after you do a big upgrade. Like when
[57:38] SPEAKER: you get stuff working, just lock it in and let it go. Just learn, learn to appreciate uptime rather
[57:45] SPEAKER: than version numbers increasing. That's the cool number. Yeah. But I think that's, I mean,
[57:48] SPEAKER: that's a high point. This started out as an ass episode, but I feel like it kind of turned into a
[57:53] SPEAKER: general like Unix running open source software kind of episode, which is really where this whole
[57:58] SPEAKER: kind of thing leads. I think I used to have a friend who ran a magazine call. I still have a
[58:02] SPEAKER: friend, but he used to run a magazine called maximum Linux when I was at maximum PC. And he
[58:07] SPEAKER: said, one of the first things he said that got him in trouble with the unit Linux community was
[58:11] SPEAKER: that Linux is only free if you value your time at nothing. Sure. And it's very true in this case.
[58:18] SPEAKER: Did you know that Linux is not a Unix? Yeah. Free BSD is a Unix.
[58:21] SPEAKER: Free BSD is a Unix. Mac OS is a Unix. Well, Mac OS is free BSD.
[58:25] SPEAKER: Well, no, but I mean like Unix has a definition that you have to meet.
[58:28] SPEAKER: Linux is POSIX compliant, but not Unix. Yes. You have to meet specific requirements
[58:31] SPEAKER: to be considered a Unix. Yeah. So Mac OS is and Linux is not.
[58:34] SPEAKER: Linus wanted nothing to do with that nonsense. I guess not.
[58:37] SPEAKER: Yeah. That's going to do it for us this week. If you liked the podcast, tell your friends.
[58:42] SPEAKER: Yeah. Use the social medias.
[58:44] SPEAKER: Yeah. Post the good word. Spread it. If you have
[58:47] SPEAKER: questions about NAS stuff that we didn't get into here.
[58:49] SPEAKER: Yeah. This was so scattershot. I'm sure if there's any clarification.
[58:53] SPEAKER: Yeah. Fire them off. That you'd be interested in.
[58:54] SPEAKER: If you'd like to yell at us about ECC Ram, you can send your comments to
[58:58] SPEAKER: notus@techpod@content.town. Those other guys with that other tech pod.
[59:04] SPEAKER: Yeah. Somebody else. I don't know. Send it to the bomb cast or something. I don't want to
[59:07] SPEAKER: hear about it. But we'll be back next week with more Tech Pod. Thanks for listening, everybody.
[59:12] SPEAKER: We'll see you all next time.
[59:34] SPEAKER: [MUSIC PLAYING]
