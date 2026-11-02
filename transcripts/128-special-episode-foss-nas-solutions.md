---
episode: 128
title: Special Episode: FOSS NAS Solutions
date: 2022-02-20
guests: none
duration: 1:02:42
---

[00:00] SPEAKER: - Hey Brad, it's a very exciting week this week.
[00:02] SPEAKER: - It is.
[00:03] SPEAKER: I mean, you know, every week has been pretty exciting
[00:05] SPEAKER: around here lately, I would say.
[00:07] SPEAKER: Yes, this is another one.
[00:08] SPEAKER: - Yeah, so this is the second episode.
[00:10] SPEAKER: This is the week that we released the second episode
[00:12] SPEAKER: of the FOSPOD, which as you may know is our new podcast
[00:16] SPEAKER: about free and open source software.
[00:19] SPEAKER: It is about consumer free and open source software though.
[00:22] SPEAKER: So it's the stuff that we talk about on the tech pod.
[00:24] SPEAKER: We like that so we realized it was important to us
[00:26] SPEAKER: and we like it and we wanted to do a new podcast.
[00:28] SPEAKER: So we are doing a new podcast
[00:30] SPEAKER: about free and open source software.
[00:32] SPEAKER: This is also the last week that this podcast
[00:36] SPEAKER: is gonna be in the tech pod feed.
[00:37] SPEAKER: - That's right, it's like the Disney vault,
[00:39] SPEAKER: like it's gonna vanish, right?
[00:41] SPEAKER: - No. - No?
[00:42] SPEAKER: - No, it's not gonna vanish.
[00:43] SPEAKER: It's gonna go into a different feed.
[00:44] SPEAKER: It's in its own feed.
[00:45] SPEAKER: - Oh, where would people find that then?
[00:48] SPEAKER: - Well, you know, it's interesting you asked that
[00:49] SPEAKER: 'cause they can go to FOSPOD.content.town
[00:52] SPEAKER: and get that podcast right there.
[00:54] SPEAKER: And you know what the amazing thing is?
[00:56] SPEAKER: Whether you use the iTunes podcast client,
[00:59] SPEAKER: whether you use Google Play podcast,
[01:01] SPEAKER: whether you listen on Spotify,
[01:02] SPEAKER: it just shows up in your ears every other week.
[01:05] SPEAKER: - Turns out it is in fact possible to subscribe
[01:07] SPEAKER: to multiple podcasts at once.
[01:09] SPEAKER: - What, really?
[01:09] SPEAKER: - We tested it, we tried it ourselves, it works.
[01:12] SPEAKER: - I actually download, I get the FOSPOD
[01:14] SPEAKER: in four different clients right now
[01:15] SPEAKER: 'cause we had to test them all.
[01:16] SPEAKER: So I gotta turn that off 'cause I don't wanna, you know,
[01:18] SPEAKER: I don't wanna juice the numbers
[01:20] SPEAKER: or anything skeezy like that.
[01:22] SPEAKER: But yes, again, the URL is FOSPOD.content.town.
[01:25] SPEAKER: You can subscribe on all the major platforms there.
[01:29] SPEAKER: You can get the actual RSS feed.
[01:31] SPEAKER: So if you use one of the not major platforms
[01:32] SPEAKER: that we're not on yet maybe, you can do it there.
[01:35] SPEAKER: And there's two things to note.
[01:37] SPEAKER: We love feedback.
[01:39] SPEAKER: It's a different format again this week.
[01:40] SPEAKER: We're trying some stuff.
[01:42] SPEAKER: You know, the new show's gotta take a little time
[01:44] SPEAKER: to find their legs sometimes, so.
[01:46] SPEAKER: - Yeah, you know, first show was kind of
[01:48] SPEAKER: primarily an interview episode.
[01:49] SPEAKER: This one was a little bit more
[01:50] SPEAKER: of a kind of a dense information explainer.
[01:52] SPEAKER: You know, we'll be doing probably some hands-on stuff
[01:54] SPEAKER: in the coming weeks.
[01:55] SPEAKER: Definitely more interviews.
[01:56] SPEAKER: We definitely wanna talk to more developers
[01:57] SPEAKER: and stuff like that, but would love to know
[01:59] SPEAKER: what people think about the show week to week
[02:01] SPEAKER: as we figure out what it is.
[02:03] SPEAKER: - And you can send that feedback to FOSPOD@content.town
[02:06] SPEAKER: or you can add us on Twitter @TheFOSPOD.
[02:10] SPEAKER: We're on YouTube.
[02:12] SPEAKER: I think I have comments turned off
[02:13] SPEAKER: just on general principle there,
[02:14] SPEAKER: but that's a venue for listening to the podcast.
[02:17] SPEAKER: And I guess without any further ado,
[02:20] SPEAKER: on with the show.
[02:22] SPEAKER: (upbeat music)
[02:25] SPEAKER: - This week's episode of the FOSPOD
[02:26] SPEAKER: is all about network attached storage.
[02:29] SPEAKER: It's time to get our NAS on.
[02:31] SPEAKER: - Look, man, I don't know what kind of lifestyle
[02:33] SPEAKER: you're living, but every week is NAS time around here.
[02:35] SPEAKER: - It's time to get nasty.
[02:38] SPEAKER: - What, whoa, whoa, whoa, whoa, man.
[02:40] SPEAKER: It's a new podcast, okay?
[02:41] SPEAKER: We have to ease them in.
[02:42] SPEAKER: - We're gonna replicate the hell out of all your terabytes.
[02:46] SPEAKER: - Wait, hang on.
[02:46] SPEAKER: Okay, I only have one question here.
[02:48] SPEAKER: Are we doing terabytes or Tebbit bytes?
[02:50] SPEAKER: - Oh, just play the music.
[02:51] SPEAKER: (upbeat music)
[02:55] SPEAKER: (upbeat music continues)
[03:11] SPEAKER: - Welcome to the FOSPOD, I'm Will.
[03:13] SPEAKER: - I am Brad.
[03:14] SPEAKER: - Hey Brad, how you doing?
[03:15] SPEAKER: - I am doing well.
[03:16] SPEAKER: I'm feeling free and open.
[03:17] SPEAKER: How are you?
[03:18] SPEAKER: - You know, I'm feeling more free and open right now
[03:20] SPEAKER: than I do any other time during the week.
[03:22] SPEAKER: I'm really excited about this week's topic too.
[03:25] SPEAKER: - Yes, people who know us know this.
[03:27] SPEAKER: This is a substantial part of our free time.
[03:29] SPEAKER: - Well, it's kind of where we started with the tech pod
[03:32] SPEAKER: and we haven't talked about it much in the last two years.
[03:35] SPEAKER: So I'm excited to kind of dig back in
[03:37] SPEAKER: and start with the fundamentals
[03:39] SPEAKER: and then build up to where I think people wanna go.
[03:41] SPEAKER: So we're gonna talk about a couple of different things here.
[03:43] SPEAKER: We're gonna talk about why you would want a NAS,
[03:47] SPEAKER: why you want storage attached to your home network,
[03:50] SPEAKER: the upsides, the downsides,
[03:51] SPEAKER: things that are good, things that are bad.
[03:53] SPEAKER: We're gonna get into the different options
[03:55] SPEAKER: that are out there from like some closed source stuff
[03:57] SPEAKER: that you can just buy off the shelf
[03:58] SPEAKER: all the way through your heavy hitters,
[03:59] SPEAKER: like your true NAS and your open media.
[04:02] SPEAKER: - Open media vault.
[04:03] SPEAKER: - Open, thank you, open media vault.
[04:05] SPEAKER: The OMV, look, the OMV is nothing's more hardcore
[04:09] SPEAKER: than the OMV, it turns out.
[04:11] SPEAKER: And then we're gonna talk about like the things
[04:13] SPEAKER: you need to know before you start.
[04:14] SPEAKER: So kind of where to kick off
[04:16] SPEAKER: and how to avoid making mistakes early on
[04:19] SPEAKER: that will haunt you down the road.
[04:21] SPEAKER: - You know, I will just say upfront real fast,
[04:23] SPEAKER: like building my true NAS machine
[04:25] SPEAKER: for about four years ago is like quite literally
[04:27] SPEAKER: the gateway drug that got me into the kind of
[04:29] SPEAKER: false obsession that I entertained to this day.
[04:31] SPEAKER: Like it's been the thing that got me into the command line,
[04:34] SPEAKER: that got me looking at all these different open source
[04:36] SPEAKER: projects that I could be putting to use for myself.
[04:38] SPEAKER: Like it's kind of, it was the thing
[04:40] SPEAKER: that kicked this whole thing off for me.
[04:41] SPEAKER: So it feels like to me, a good place to start.
[04:44] SPEAKER: - Yeah, and it's funny,
[04:45] SPEAKER: it's 'cause I hit the similar path, right?
[04:47] SPEAKER: Like I learned, I had run Linux and stuff before.
[04:50] SPEAKER: I built my first NAS machine,
[04:52] SPEAKER: but I hadn't really engaged with command line stuff
[04:55] SPEAKER: all that much, with the command line software all that much.
[04:57] SPEAKER: And it turned out to be really,
[04:58] SPEAKER: really important to me personally and professionally.
[05:00] SPEAKER: So here we are, as always,
[05:04] SPEAKER: the FOSS pod is brought to you by Google open source,
[05:06] SPEAKER: bringing all the value of open source to Google
[05:08] SPEAKER: and all the resources of Google to open source.
[05:11] SPEAKER: You can find out more at opensource.google.
[05:14] SPEAKER: - Dot.
[05:15] SPEAKER: - Dot Google.
[05:16] SPEAKER: - Dot, dot what?
[05:17] SPEAKER: - No, it's just dot Google.
[05:18] SPEAKER: We're gonna do this every week.
[05:19] SPEAKER: Also a bit of housekeeping, we are hiring.
[05:22] SPEAKER: So we have an editor position
[05:25] SPEAKER: that we're looking to fill on a contract basis.
[05:27] SPEAKER: It's a biweekly, one show every other week,
[05:29] SPEAKER: 'cause that's how often we do the show.
[05:30] SPEAKER: And we also are looking for a host slash producer,
[05:33] SPEAKER: somebody who can join us on the microphone
[05:35] SPEAKER: and talk about topics of interest
[05:37] SPEAKER: to the open source community.
[05:39] SPEAKER: The email address for both of those CVs
[05:41] SPEAKER: is fosspod@content.town.
[05:43] SPEAKER: So send them in, we're talking to people now.
[05:45] SPEAKER: So we're reaching out to people and talking to people
[05:48] SPEAKER: and we're excited to meet new people
[05:50] SPEAKER: as a result of doing this show.
[05:51] SPEAKER: So please, again, it's fosspod@content.town
[05:53] SPEAKER: to send your CVs.
[05:55] SPEAKER: I think without any further ado,
[05:56] SPEAKER: we should get into why people would want a NAS, Brad.
[06:00] SPEAKER: - 'Cause it's rad.
[06:02] SPEAKER: So it's because it's a lot of fun.
[06:03] SPEAKER: I mean, that's not the best reason,
[06:05] SPEAKER: like genuinely enjoy tinkering with it like nothing else,
[06:08] SPEAKER: but like, yeah, we should start with practical benefits
[06:10] SPEAKER: for people who aren't lunatics like us.
[06:12] SPEAKER: So, okay, let me step back.
[06:13] SPEAKER: The basic definition of a NAS,
[06:15] SPEAKER: a network attached storage device
[06:17] SPEAKER: for people who don't know exactly what the name sounds like.
[06:19] SPEAKER: It is just a storage volume sitting on your network
[06:22] SPEAKER: that any other device on your network
[06:23] SPEAKER: that's on your wifi, on your wired ethernet can access.
[06:27] SPEAKER: So it's storage independent of a kind of end user device
[06:30] SPEAKER: like a laptop or a phone or a desktop PC
[06:33] SPEAKER: that can just be shared by everybody in the house.
[06:35] SPEAKER: - So the classic example I always give
[06:37] SPEAKER: is that when I worked my first IT job working in an office,
[06:41] SPEAKER: there was a person who had shared their hard drive
[06:46] SPEAKER: with the Windows hard drive sharing thing.
[06:48] SPEAKER: And everybody else in the department needed a file
[06:50] SPEAKER: that was on that hard drive.
[06:52] SPEAKER: So when she went on vacation one week,
[06:54] SPEAKER: everybody's like, "Hey, I can't get to this drive."
[06:55] SPEAKER: And we had to, it took us ages to track down
[06:58] SPEAKER: which machine was the one
[07:00] SPEAKER: that somebody was hosting their own files on.
[07:01] SPEAKER: When you have a NAS server set up in your house
[07:04] SPEAKER: or in your small business, whatever,
[07:05] SPEAKER: you avoid this problem
[07:06] SPEAKER: 'cause that machine's designed to be always on
[07:08] SPEAKER: and it's designed to just basically serve files
[07:10] SPEAKER: and do other things.
[07:11] SPEAKER: The other kind of secret cool thing
[07:14] SPEAKER: that having an always on machine in your house gives you
[07:18] SPEAKER: is the ability to have software that runs all the time
[07:21] SPEAKER: and do things like host a media server
[07:24] SPEAKER: so you can share ripped DVDs or ripped Blu-rays,
[07:27] SPEAKER: run a VPN so you can get into your house from outside
[07:30] SPEAKER: wherever you are and wherever you happen to be,
[07:32] SPEAKER: run game servers or things like internet of things server,
[07:37] SPEAKER: like Home Assistant, which is an open source project
[07:39] SPEAKER: we'll talk about later that you can use to control lights
[07:42] SPEAKER: and smart internet of things stuff around your house.
[07:45] SPEAKER: - There are considerations to doing this.
[07:47] SPEAKER: One of them is electricity,
[07:49] SPEAKER: leaving something on all the time.
[07:51] SPEAKER: I know people who just run their Windows machine 24/7
[07:53] SPEAKER: so that it can serve files to the rest of their house.
[07:56] SPEAKER: And I'm like, "What are you doing?"
[07:57] SPEAKER: - My Windows machine has a giant video card and a huge CPU
[08:00] SPEAKER: and it's kind of expensive, it turns out.
[08:02] SPEAKER: - Right, so there are options all the way
[08:04] SPEAKER: from a literal hard drive with an Ethernet port in it
[08:06] SPEAKER: on up to a Raspberry Pi or an Intel NUC.
[08:09] SPEAKER: Are we a NUC or a NUC podcast?
[08:11] SPEAKER: - I think we're a NUC as the official pronunciation
[08:13] SPEAKER: as I understand it.
[08:14] SPEAKER: - NUC is where I like to land on that one.
[08:15] SPEAKER: You know, but yeah, like small, cheap
[08:17] SPEAKER: and like low power compute devices like those
[08:19] SPEAKER: that you can hook up to one or more hard drives
[08:21] SPEAKER: on up to like much bigger, like full ATX PCs
[08:25] SPEAKER: running pretty heavy duty kind of NAS operating systems.
[08:27] SPEAKER: Like there's a pretty big spectrum there
[08:29] SPEAKER: of hardware and software solutions that we'll get to.
[08:31] SPEAKER: But you know, there are considerations
[08:32] SPEAKER: like how much electricity is this gonna use
[08:34] SPEAKER: if I leave it on 24/7.
[08:35] SPEAKER: So you need to think about like what your needs are,
[08:37] SPEAKER: what you're willing to bear there
[08:38] SPEAKER: in terms of resource consumption and stuff like that.
[08:40] SPEAKER: I'm kind of a lot to dig into there.
[08:42] SPEAKER: - Well, also with a 24/7 machine,
[08:45] SPEAKER: a machine that's gonna be running 24/7, 365 days a year,
[08:49] SPEAKER: like the spinning drives last a finite time.
[08:52] SPEAKER: And you're looking, in my experience,
[08:53] SPEAKER: between three and five years,
[08:54] SPEAKER: you need to think about replacing all of those disks.
[08:57] SPEAKER: In one way, this is kind of nice
[08:58] SPEAKER: 'cause it means that you know you buy disks
[09:00] SPEAKER: and you look at the amount of space you're using
[09:02] SPEAKER: and you're like, okay, this is gonna last me
[09:03] SPEAKER: for the next three years.
[09:04] SPEAKER: And then you know that you're gonna upgrade
[09:06] SPEAKER: and there will be theoretically larger disks available
[09:08] SPEAKER: at that time at the same or less cost.
[09:11] SPEAKER: And then something like a pandemic happens
[09:12] SPEAKER: and the cost of disks go way up
[09:13] SPEAKER: and you're sitting here thinking, oh,
[09:15] SPEAKER: well, I could just buy replacement disks
[09:17] SPEAKER: that are exactly the same size as what I have.
[09:19] SPEAKER: Why am I spending $1,000 every three years on disks?
[09:22] SPEAKER: It gets kind of expensive pretty quickly.
[09:24] SPEAKER: So it's something to consider before you jump into this.
[09:27] SPEAKER: And there are, I think when we did this two years ago,
[09:30] SPEAKER: two and a half years ago with the first TechPod episodes,
[09:33] SPEAKER: we had kind of jumped into the deep end
[09:35] SPEAKER: because there weren't a lot of other options available
[09:37] SPEAKER: at the time that were compelling
[09:39] SPEAKER: or they were limited in some important way.
[09:42] SPEAKER: And now it's a little bit of a different story.
[09:44] SPEAKER: - Yeah, like the spread and product availability
[09:46] SPEAKER: has gotten much better.
[09:47] SPEAKER: There are a lot more inexpensive
[09:48] SPEAKER: and simpler options out there.
[09:50] SPEAKER: Also, before we get into that stuff,
[09:51] SPEAKER: like I also feel like it's kind of interesting
[09:53] SPEAKER: there is a philosophical split, a schism, if you will,
[09:57] SPEAKER: where I feel like one group of people
[09:58] SPEAKER: is very much moving back toward local data storage,
[10:01] SPEAKER: wanting their own media, like music and movie library,
[10:04] SPEAKER: wanting to manage everything on site again.
[10:06] SPEAKER: And there's a whole other category of people
[10:08] SPEAKER: who are like, get hard drives out of my house.
[10:11] SPEAKER: I'm just going to use cloud storage for everything now.
[10:13] SPEAKER: I don't wanna think about this anymore.
[10:14] SPEAKER: So like there is something to think about there
[10:16] SPEAKER: about whether you want to get into this.
[10:17] SPEAKER: 'Cause I think it's a lot of fun
[10:18] SPEAKER: and it empowers you in a lot of cool ways.
[10:20] SPEAKER: But if you're the type of person
[10:21] SPEAKER: who wants fewer boxes around the house,
[10:24] SPEAKER: there are online options that can do some similar stuff,
[10:26] SPEAKER: but it's a very different use case and philosophy,
[10:29] SPEAKER: depending on what you're looking for.
[10:30] SPEAKER: - But if you're looking for backups
[10:32] SPEAKER: and like photo backup, photo sharing services,
[10:35] SPEAKER: those things are available.
[10:37] SPEAKER: Whether it's Google photos or the iCloud photos
[10:39] SPEAKER: or whatever your phone provides,
[10:42] SPEAKER: or for cloud backup solutions like Backblaze
[10:45] SPEAKER: is a great service that will keep your data safe online
[10:49] SPEAKER: without you having to have a bunch of external drives
[10:51] SPEAKER: around the house.
[10:52] SPEAKER: If you're looking to serve media, it's a little harder
[10:55] SPEAKER: 'cause like the cost per terabyte is really, really high
[10:58] SPEAKER: once you get above about two terabytes
[11:00] SPEAKER: on most of the cloud storage providers.
[11:02] SPEAKER: And they can't interface directly with most media server
[11:06] SPEAKER: software, like your Plexus or your Codys or whatever.
[11:09] SPEAKER: So it's an interesting balance.
[11:11] SPEAKER: I think for our purposes, I think there's two kind of people
[11:16] SPEAKER: that we're doing this episode for.
[11:17] SPEAKER: One is somebody who's curious about a NAS
[11:18] SPEAKER: and wants to kind of dip their toes in,
[11:21] SPEAKER: but maybe not spend a whole bunch of money,
[11:23] SPEAKER: maybe even use hardware that's around.
[11:24] SPEAKER: And one of the things that's interesting about that
[11:25] SPEAKER: is the Raspberry Pi, the rise of the powerful Raspberry Pi
[11:29] SPEAKER: over the last five years means that you can get
[11:31] SPEAKER: a multi-core Raspberry Pi 4 with what?
[11:34] SPEAKER: Like four gigs of memory theoretically for under $100.
[11:37] SPEAKER: - Theoretically, yes.
[11:39] SPEAKER: - Prices are a little bit jacked.
[11:40] SPEAKER: Like you have to pre-order them right now
[11:41] SPEAKER: just because they're in such high demand.
[11:43] SPEAKER: - The current situation, this has been pretty much
[11:45] SPEAKER: the worst possible time to be building something like this,
[11:47] SPEAKER: but in an ideal world, yes.
[11:48] SPEAKER: SBCs, I guess is the generic term,
[11:50] SPEAKER: small board computers for things like Pis.
[11:52] SPEAKER: I mean, that's the most popular, obviously.
[11:54] SPEAKER: Like very inexpensive.
[11:55] SPEAKER: - Yeah.
[11:56] SPEAKER: - Like you can get a $35 Raspberry Pi 4 theoretically
[11:59] SPEAKER: when the price is normalized again.
[12:01] SPEAKER: It'll do everything basic that you could want a NAS to do.
[12:04] SPEAKER: - Well, and I was able to find places to pre-order Pi 4s
[12:07] SPEAKER: that would deliver them in two to four weeks.
[12:10] SPEAKER: So like they're not impossible to get.
[12:11] SPEAKER: You just have to wait a little bit at that retail price.
[12:14] SPEAKER: Don't go to Amazon or Newegg and buy them
[12:16] SPEAKER: 'cause the prices are marked up incredibly right now
[12:18] SPEAKER: on Pi 4s especially.
[12:22] SPEAKER: But yeah, if you put one of our options
[12:24] SPEAKER: that we'll talk about in a little bit is Open Media Vault.
[12:27] SPEAKER: And it runs really well on a Pi 4,
[12:31] SPEAKER: even with like Docker containers running underneath it
[12:34] SPEAKER: with different services running.
[12:35] SPEAKER: So there's a bunch of interesting options
[12:37] SPEAKER: and you don't have to like take your old gaming computer
[12:40] SPEAKER: and strip out the video card to build a NAS
[12:43] SPEAKER: on your network these days.
[12:44] SPEAKER: - That's sad if you want to do that, you certainly can.
[12:47] SPEAKER: - Yeah, it's definitely a viable path.
[12:49] SPEAKER: And it's like, it's one of the things we like to do
[12:51] SPEAKER: rather than throw old hardware in the landfill
[12:54] SPEAKER: is to figure out ways to kind of recycle it
[12:56] SPEAKER: or upcycle it or whatever your term of choice is.
[12:58] SPEAKER: And then that's definitely one of them.
[13:00] SPEAKER: So let's see, downsides, power consumption.
[13:03] SPEAKER: Depending on where you live
[13:04] SPEAKER: and what your per kilowatt hour rate is,
[13:07] SPEAKER: you know, a NAS, a heavyweight NAS box
[13:10] SPEAKER: running the wrong software can cost $20 or $30 a month
[13:12] SPEAKER: to run in power.
[13:14] SPEAKER: The drives have a finite lifespan, we talked about that.
[13:16] SPEAKER: Plan to replace them every three to five years.
[13:18] SPEAKER: - Yeah, I want to jump back in about the power usage.
[13:20] SPEAKER: I mean, you're not wrong, like that's substantial.
[13:22] SPEAKER: But something hit me when you were talking
[13:23] SPEAKER: about backblaze earlier,
[13:24] SPEAKER: which is that for small amounts of data,
[13:26] SPEAKER: stuff like backblaze is great.
[13:27] SPEAKER: But yes, once you get up into the pricing tiers
[13:29] SPEAKER: where you'd be storing the same amount of data
[13:31] SPEAKER: that you might put on a local NAS,
[13:33] SPEAKER: the monthly cost of doing that on a service like backblaze,
[13:35] SPEAKER: I think probably far exceeds
[13:37] SPEAKER: what your electricity is going to run.
[13:38] SPEAKER: - Well, the backblaze backup service
[13:40] SPEAKER: is infinite for storage, for backup.
[13:44] SPEAKER: - That's for desktops. - For desktops.
[13:46] SPEAKER: If you're using their data container services,
[13:48] SPEAKER: it gets really expensive of about two terabytes, yeah.
[13:51] SPEAKER: And if you've taken efforts to reduce your power usage
[13:56] SPEAKER: from the grid, if you have solar panels
[13:57] SPEAKER: or wind generation or something like that,
[13:59] SPEAKER: the cost of running the NAS,
[14:01] SPEAKER: you take that off the top, I think, probably.
[14:04] SPEAKER: There's a lot of time.
[14:06] SPEAKER: Like it takes a fair amount of time to get up and running,
[14:09] SPEAKER: and then a little bit of time regularly for maintenance.
[14:12] SPEAKER: One of the things about putting an always-on machine,
[14:15] SPEAKER: especially if you choose to make it accessible
[14:17] SPEAKER: outside the network, the outside of your LAN,
[14:20] SPEAKER: is that you're adding a massive amount of threat profile
[14:23] SPEAKER: to your home network.
[14:24] SPEAKER: And as a result, you need to run software updates
[14:27] SPEAKER: and you need to run security patches
[14:29] SPEAKER: and you need to update the services that you use
[14:30] SPEAKER: and all of the things that Windows takes care of for you.
[14:34] SPEAKER: You might have to do that yourself on a NAS box.
[14:37] SPEAKER: - Which I personally find to be kind of relaxing.
[14:39] SPEAKER: I mean, that's upkeep
[14:41] SPEAKER: that some people might not want to deal with.
[14:42] SPEAKER: Like it's kind of a once a month,
[14:44] SPEAKER: once every two months, depending on the cadence,
[14:46] SPEAKER: just kind of a cup of coffee on a Saturday morning,
[14:49] SPEAKER: and SSH into three or four Raspberry Pis
[14:51] SPEAKER: and just run some updates.
[14:52] SPEAKER: You know, it's not huge, but it is something to consider.
[14:54] SPEAKER: - It's kind of analogous to changing your oil in a car,
[14:57] SPEAKER: right? - Sure.
[14:58] SPEAKER: - You get up in the morning, you grab your cup of coffee,
[15:00] SPEAKER: you sit down at the chair, you shell into the NAS,
[15:03] SPEAKER: and then you apt-get update all and, you know.
[15:07] SPEAKER: - You got to stick the dipstick into the package manager,
[15:09] SPEAKER: see what comes out.
[15:11] SPEAKER: The way I would phrase it is,
[15:12] SPEAKER: there is a little bit of a hobbyist element
[15:14] SPEAKER: to this stuff for me.
[15:15] SPEAKER: Like I think you do kind of need to enjoy it a little bit
[15:18] SPEAKER: to truly dig into the stuff and keep up with it.
[15:20] SPEAKER: - And it's also a vector to learn about things
[15:23] SPEAKER: you might not learn about otherwise.
[15:24] SPEAKER: Like I learned more about configuring file sharing
[15:27] SPEAKER: for Windows machines by figuring out how to get that running
[15:31] SPEAKER: in FreeNAS 10 years ago than anything else I've done
[15:34] SPEAKER: as running Windows machines professionally even.
[15:37] SPEAKER: So yeah, it's an opportunity for you to learn
[15:39] SPEAKER: how to do shell scripts, how to do all sorts of other
[15:43] SPEAKER: kind of stuff that's like, it's an entry point
[15:45] SPEAKER: into the world of IT administration,
[15:46] SPEAKER: if that's a place you want to go with your career even.
[15:48] SPEAKER: - Or even just stuff you want to know about on the back end,
[15:50] SPEAKER: even if you don't want to work in that field necessarily.
[15:52] SPEAKER: Like I've learned so much about just basic networking
[15:54] SPEAKER: and file sharing, like file systems,
[15:56] SPEAKER: different backup methods, you know.
[15:58] SPEAKER: I've kind of gained a better understanding of like
[16:00] SPEAKER: what GitHub best practices are, you know,
[16:02] SPEAKER: like how are repos managed?
[16:04] SPEAKER: You know, what is a pull request?
[16:05] SPEAKER: Like I didn't know what any of that stuff was
[16:06] SPEAKER: before I got into this and I'm no programmer,
[16:08] SPEAKER: but all of those things are so adjacent
[16:10] SPEAKER: to this type of project that like you just kind of,
[16:13] SPEAKER: the osmosis sets in and you just start learning
[16:15] SPEAKER: and it's a great feeling.
[16:16] SPEAKER: - So the interesting thing is we both kind of started
[16:20] SPEAKER: in the same place with the NAS as a media server slash,
[16:23] SPEAKER: like file depository for the house.
[16:26] SPEAKER: You know, I used to back up my laptops to my NAS,
[16:29] SPEAKER: stuff like that.
[16:30] SPEAKER: - If you've ever suffered catastrophic data loss
[16:32] SPEAKER: in your life, you know how terrible it is.
[16:33] SPEAKER: And that's happened to me a couple of times.
[16:35] SPEAKER: And finally, I was just like, you know what?
[16:37] SPEAKER: I'm going to build a thing that's got some redundancy
[16:38] SPEAKER: built into it where a single hard drive failing
[16:41] SPEAKER: can't hose years worth of data,
[16:43] SPEAKER: as has happened to me in the past.
[16:44] SPEAKER: And so like, that's kind of how I got there.
[16:46] SPEAKER: Like that is actually a pretty significant use case
[16:49] SPEAKER: or justification for doing something like this
[16:51] SPEAKER: is like, it's some resilience to data
[16:53] SPEAKER: that might actually be like very important to you.
[16:55] SPEAKER: - That is the right reason to start, right?
[16:57] SPEAKER: Is, hey, I use a laptop as my main computer.
[16:59] SPEAKER: I carry it out of my house every single day.
[17:01] SPEAKER: The data on that laptop is incredibly,
[17:04] SPEAKER: at incredibly high risk.
[17:05] SPEAKER: Like you leave the laptop on the bus,
[17:06] SPEAKER: somebody steals it, you drop it,
[17:08] SPEAKER: the SSD is soldered to the motherboard now.
[17:11] SPEAKER: Like there's no data recovery for a broken laptop.
[17:14] SPEAKER: If you don't have it backed up.
[17:15] SPEAKER: So the interesting thing is you've taken,
[17:18] SPEAKER: you and I have taken kind of different paths with our NAS.
[17:21] SPEAKER: Mine is pretty much a straight media box.
[17:22] SPEAKER: I store old photos.
[17:24] SPEAKER: I have like my music collection.
[17:26] SPEAKER: I have ripped Blu-rays and DVDs.
[17:28] SPEAKER: I have stuff that I pulled off of the DVR.
[17:32] SPEAKER: But other than that, it's pretty much,
[17:34] SPEAKER: it's pretty low traffic.
[17:35] SPEAKER: It's pretty much me putting files on there occasionally
[17:37] SPEAKER: and then small amounts of data being pulled off
[17:39] SPEAKER: and backups running every night
[17:41] SPEAKER: from the other local machines.
[17:43] SPEAKER: You've gotten a little heavier than I have.
[17:45] SPEAKER: - Yes, and kind of other occupations that I have,
[17:48] SPEAKER: audio and video stuff is a pretty big deal.
[17:50] SPEAKER: So having a place to put large media files
[17:52] SPEAKER: that are recordings, you know,
[17:53] SPEAKER: like they are source files of audio and video stuff
[17:56] SPEAKER: that need to be available at all times and accessed quickly.
[17:58] SPEAKER: So, you know, there are, yeah, there are ways,
[18:00] SPEAKER: there are ways to build a NAS for capacity
[18:03] SPEAKER: or for performance or for redundancy.
[18:05] SPEAKER: Those things to a large degree are kind of mutually
[18:07] SPEAKER: exclusive.
[18:08] SPEAKER: You kind of have to make trade-offs there about like,
[18:09] SPEAKER: do I want more storage space?
[18:10] SPEAKER: Do I want it to be able to survive more drive failures?
[18:13] SPEAKER: Do I want it to serve media faster?
[18:15] SPEAKER: You know, there are a lot of considerations there.
[18:17] SPEAKER: - The interesting thing for me is that I'm getting ready
[18:19] SPEAKER: to upgrade my NAS or upgrade my NAS hardware.
[18:22] SPEAKER: And I want to go a little bit lighter.
[18:23] SPEAKER: I want to use a little bit less power.
[18:25] SPEAKER: I want to have something that's a little bit easier
[18:26] SPEAKER: to manage.
[18:27] SPEAKER: I want to have something that I spend generally speaking,
[18:29] SPEAKER: less time fooling with and more time just using.
[18:32] SPEAKER: And I'm okay, I'm willing to sacrifice some power to do that.
[18:34] SPEAKER: Whereas you're in a situation where you're actually using
[18:36] SPEAKER: a lot of compute on your NAS
[18:39] SPEAKER: and you also have a high throughput needs
[18:41] SPEAKER: and other like a kind of a complicated workflow
[18:44] SPEAKER: at this point.
[18:45] SPEAKER: - You know, Will, if I didn't know better,
[18:46] SPEAKER: I would say this sounds like what we in the business call
[18:48] SPEAKER: a segue into our next section about different NAS options.
[18:54] SPEAKER: - Okay, there are a bunch of different options here.
[18:57] SPEAKER: - Boy, howdy are there.
[18:58] SPEAKER: - Yeah, like you can install Ubuntu or Debian on a computer
[19:03] SPEAKER: of some kind and just turn on SMB and SIFs,
[19:07] SPEAKER: the file sharing formats for windows and bam,
[19:10] SPEAKER: you have a NAS server right there.
[19:12] SPEAKER: - Yeah, although everything you described takes a certain
[19:14] SPEAKER: amount of foreknowledge, let's be clear.
[19:16] SPEAKER: - It's not an easy path.
[19:17] SPEAKER: - Those are Linux, this is something I'd love to hear
[19:20] SPEAKER: from people about like what level of sort of Linux
[19:22] SPEAKER: and kind of FOSS proficiency people are working with.
[19:25] SPEAKER: Those are Ubuntu and Debian are two of the more popular
[19:28] SPEAKER: Linux distros out there, but that is just installing flat,
[19:31] SPEAKER: just a full on Linux distro with no usability tools
[19:35] SPEAKER: on top of it is what you're describing.
[19:36] SPEAKER: So like you absolutely can do that, but that is a rabbit hole
[19:39] SPEAKER: if you don't have a lot of command line
[19:41] SPEAKER: and Linux experience.
[19:42] SPEAKER: - It's both hard to set up and difficult to maintain,
[19:45] SPEAKER: which is kind of two disqualifying things for me.
[19:47] SPEAKER: So I'm gonna say, let's not talk about like,
[19:50] SPEAKER: while you can absolutely install Linux on any computer
[19:52] SPEAKER: and turn it into a server with like a few shell scripts
[19:55] SPEAKER: and a little bit of foreknowledge, we're gonna assume
[19:57] SPEAKER: that people want something that's a little bit more managed
[19:59] SPEAKER: for our purposes.
[20:01] SPEAKER: TrueNAS is the classic example used to be known as FreeNAS
[20:05] SPEAKER: is a BSD based ZFS file system, massive.
[20:11] SPEAKER: It's kind of the grandfather of this entire,
[20:14] SPEAKER: of like the home NAS enthusiast community.
[20:17] SPEAKER: - It's been around forever.
[20:18] SPEAKER: ZFS is an incredibly resilience
[20:20] SPEAKER: and like full featured file system,
[20:22] SPEAKER: but it came out of the server world.
[20:23] SPEAKER: And so it comes with some pretty hefty hardware requirements,
[20:26] SPEAKER: particularly in terms of how much memory it needs.
[20:29] SPEAKER: So for basic home needs for say,
[20:32] SPEAKER: backing up a photo library, or just even a Plex library,
[20:35] SPEAKER: like just the standard home use cases.
[20:38] SPEAKER: TrueNAS and ZFS maybe can be a little heavy
[20:40] SPEAKER: and a little bit much.
[20:41] SPEAKER: If you're doing stuff where resilience really matters,
[20:43] SPEAKER: where say transferring massive terabytes of data around
[20:47] SPEAKER: with a single command is important,
[20:48] SPEAKER: then it's much more appropriate in that context.
[20:51] SPEAKER: But it's kind of like, it's the thing I started with,
[20:53] SPEAKER: but it's the thing that I would probably recommend
[20:55] SPEAKER: people get to last in their sort of,
[20:57] SPEAKER: as they climb the ladder of NAS options.
[21:00] SPEAKER: It's like, it's the deepest rabbit hole
[21:02] SPEAKER: and like one of the more fully featured options,
[21:03] SPEAKER: but it is quite a lot to get into.
[21:05] SPEAKER: - Well, I was gonna say,
[21:06] SPEAKER: I have a friend who's a professional nature photographer
[21:08] SPEAKER: and he goes on trips around the world,
[21:12] SPEAKER: generates terabytes and terabytes
[21:13] SPEAKER: and terabytes of raw photos.
[21:15] SPEAKER: And he has both a portable NAS
[21:18] SPEAKER: that he backs up the files to at the end of the day.
[21:21] SPEAKER: And then that syncs across the internet to his NAS at home.
[21:25] SPEAKER: And he has 50 terabytes of storage in that NAS at home.
[21:29] SPEAKER: Like he's a perfect use case for TrueNAS.
[21:31] SPEAKER: - Absolutely.
[21:32] SPEAKER: - Right, it's a thing where redundancy is important.
[21:35] SPEAKER: The things that he's backing up are irreplaceable
[21:38] SPEAKER: and he's interested in both redundancy and security
[21:42] SPEAKER: and performance, all three of those.
[21:44] SPEAKER: 'Cause he works off of the actual NAS.
[21:46] SPEAKER: I don't have that level of data security
[21:48] SPEAKER: or speed required to stream the Lion King
[21:52] SPEAKER: into my living room.
[21:54] SPEAKER: - Well, Will, you're in luck.
[21:55] SPEAKER: We have some lighter weight options for you.
[21:57] SPEAKER: - That sounds fantastic.
[21:58] SPEAKER: - I think we said it, but just to be clear,
[22:00] SPEAKER: you also are running a TrueNAS machine as of now,
[22:02] SPEAKER: but you're looking to scale down because like you said,
[22:04] SPEAKER: your needs are lighter and you can save on electricity.
[22:06] SPEAKER: You can save on complexity by moving to...
[22:09] SPEAKER: - I think Open Media Vault is...
[22:11] SPEAKER: So Open Media Vault is kind of the...
[22:13] SPEAKER: It's a Linux-based distro based on Debian
[22:17] SPEAKER: that basically is like a managed application
[22:20] SPEAKER: that lives on top of the Linux OS.
[22:23] SPEAKER: And you can install it any number of different ways.
[22:25] SPEAKER: You can install Raspberry Pi OS onto a Raspberry Pi
[22:28] SPEAKER: and then pull down the packages
[22:30] SPEAKER: for the Open Media Vault software on top of that.
[22:33] SPEAKER: Basically what it does is gives you a web-based UI
[22:36] SPEAKER: that you can use to control the guts of the NAS,
[22:39] SPEAKER: the NAS parts of the system.
[22:42] SPEAKER: And also it will handle like the things
[22:43] SPEAKER: like the upgrading Debian for you.
[22:45] SPEAKER: So you get security patches and stuff like that.
[22:47] SPEAKER: TrueNAS has a similar web-based UI for the front end.
[22:52] SPEAKER: I think that's, for me,
[22:54] SPEAKER: that web component is actually really important
[22:56] SPEAKER: because it means that people who aren't proficient
[22:58] SPEAKER: or comfortable working in the shell
[23:00] SPEAKER: can do all the things that they need to do
[23:02] SPEAKER: to set up the machine, keep it running,
[23:04] SPEAKER: add new functionality.
[23:05] SPEAKER: And like that adding new functionality part
[23:07] SPEAKER: is the exciting part about doing an open source NAS to me.
[23:11] SPEAKER: You can go out, you can buy a Synology box
[23:14] SPEAKER: for a few hundred bucks, slam some hard drives in there
[23:16] SPEAKER: and install a Plex plugin and three other things.
[23:19] SPEAKER: But when you get to the point, you're like,
[23:20] SPEAKER: man, I'd really love to run a Quake server on this, right?
[23:23] SPEAKER: My kid's gotten into Minecraft
[23:24] SPEAKER: and I wanna run a Minecraft server at home.
[23:26] SPEAKER: Your options are a little bit more limited
[23:28] SPEAKER: on the closed source solutions.
[23:31] SPEAKER: - Yeah, there are those term key boxes out there,
[23:32] SPEAKER: Synology and QNAP.
[23:34] SPEAKER: - There's a bunch others, yeah.
[23:35] SPEAKER: - They are a lot more just ready to go out of the box,
[23:38] SPEAKER: to be clear.
[23:39] SPEAKER: I mean, those are basically little enclosures
[23:40] SPEAKER: that you just plug some hard drives into
[23:42] SPEAKER: and they've got their own proprietary operating systems
[23:44] SPEAKER: that you also access over a web interface.
[23:46] SPEAKER: And it's that classic trade-off, right?
[23:49] SPEAKER: They're a lot easier to just unbox and get going,
[23:51] SPEAKER: but also you're gonna pay a little bit more
[23:53] SPEAKER: for the amount of compute power you're getting in them
[23:55] SPEAKER: than you would building an open box.
[23:57] SPEAKER: Also, you're subject to the decisions and the policies
[24:00] SPEAKER: that are set by those companies.
[24:02] SPEAKER: For feature support and that kind of thing,
[24:05] SPEAKER: the software that they provide is very much designed
[24:07] SPEAKER: by them, not sort of designed by committee and more open,
[24:10] SPEAKER: like you get in the open source world.
[24:12] SPEAKER: - And also if you're buying something
[24:14] SPEAKER: that is a very common piece of hardware,
[24:17] SPEAKER: then the threat profile for that gets higher,
[24:20] SPEAKER: the more popular the hardware gets.
[24:22] SPEAKER: So we've seen some NAS specific malware out there
[24:25] SPEAKER: that's like ransomware that encrypts your NAS drives
[24:29] SPEAKER: and requires you to pay some Bitcoin
[24:33] SPEAKER: to unlock your business,
[24:34] SPEAKER: which is never what you want, right?
[24:36] SPEAKER: It's never a good outcome.
[24:37] SPEAKER: So we're gonna talk about mostly TrueNAS
[24:41] SPEAKER: and Open Media Vault today, I think.
[24:43] SPEAKER: They're both extensible.
[24:44] SPEAKER: You can both add plugins in the form of either plugins
[24:47] SPEAKER: in TrueNAS's case or Docker containers
[24:49] SPEAKER: in Open Media Vault's case that add functionality
[24:53] SPEAKER: and other types of servers underneath your server.
[24:57] SPEAKER: They handle the maintenance for you.
[24:58] SPEAKER: They handle a lot of the maintenance for you.
[25:00] SPEAKER: So you don't have to worry as much about updating
[25:02] SPEAKER: and things like that.
[25:03] SPEAKER: You can hit a button in a web interface
[25:05] SPEAKER: instead of having to run command line
[25:07] SPEAKER: and update stuff manually.
[25:09] SPEAKER: And like we said, there are a bunch of alternatives.
[25:11] SPEAKER: If you just want backup,
[25:12] SPEAKER: a cloud-based backup is probably better for you
[25:15] SPEAKER: or an external hard drive might be better for you
[25:17] SPEAKER: than a NAS if you only have one computer.
[25:19] SPEAKER: If you have a bunch of computers and a bunch of phones
[25:21] SPEAKER: and stuff that you wanna back up,
[25:22] SPEAKER: then that's when you start thinking about the NAS.
[25:24] SPEAKER: For file sharing, the cloud services
[25:27] SPEAKER: like Google Drive and Dropbox and OneDrive
[25:29] SPEAKER: are really competitive up until you get beyond
[25:33] SPEAKER: about two terabytes, it seems like.
[25:34] SPEAKER: And then the cost per terabyte goes way, way up
[25:37] SPEAKER: compared to what you can get in a box
[25:39] SPEAKER: that lives inside your network.
[25:41] SPEAKER: And the other nice thing about the internal network
[25:43] SPEAKER: is if you are on a provider, internet provider
[25:46] SPEAKER: that provides limited upstream,
[25:48] SPEAKER: then you're not gated by the upstream performance
[25:50] SPEAKER: of your home internet connection.
[25:52] SPEAKER: - That's a good point.
[25:52] SPEAKER: I mean, that is like, that problem is endemic,
[25:54] SPEAKER: especially in the United States.
[25:55] SPEAKER: I don't know if it's as bad elsewhere,
[25:57] SPEAKER: but upstream speeds are,
[25:59] SPEAKER: I have to assume, artificially suppressed.
[26:01] SPEAKER: I mean, maybe there are legitimate reasons
[26:03] SPEAKER: that are not business reasons,
[26:04] SPEAKER: but like it's in a lot of localities,
[26:06] SPEAKER: it is very hard to get very fast upstream for fast uploads
[26:09] SPEAKER: to something like a cloud storage bucket of sorts, right?
[26:12] SPEAKER: You know, you might have downstream
[26:13] SPEAKER: that's like tens of times faster than your upstream.
[26:16] SPEAKER: And so at that point, uploads of backups
[26:18] SPEAKER: of terabytes of data just aren't even practical
[26:20] SPEAKER: from a time standpoint.
[26:21] SPEAKER: - 200 megabits per second down
[26:23] SPEAKER: and 10 megabits per second up
[26:24] SPEAKER: is a really common internet speed in the US.
[26:28] SPEAKER: So those are kind of the options.
[26:30] SPEAKER: That's kind of what's out there.
[26:32] SPEAKER: We're gonna talk about TrueNAS and Open Media Vault.
[26:34] SPEAKER: You can get real complicated and hybridize
[26:37] SPEAKER: and do things like run your software on a small Nuke machine
[26:41] SPEAKER: and run the storage in a Synology NAS.
[26:44] SPEAKER: And you can kind of jam these things together
[26:48] SPEAKER: in all sorts of different ways.
[26:49] SPEAKER: We're gonna hit kind of the more common approaches.
[26:52] SPEAKER: Okay, so we've decided we wanna do a managed install.
[26:56] SPEAKER: Some sort of operating system,
[26:58] SPEAKER: either TrueNAS or Open Media Vault.
[27:00] SPEAKER: I think we should start with Open Media Vault
[27:01] SPEAKER: because it's kind of the slightly less deep entry point.
[27:05] SPEAKER: - Also it's Linux based,
[27:06] SPEAKER: which has a lot of advantages we'll get into.
[27:07] SPEAKER: - It's a little bit easier to set up and install.
[27:09] SPEAKER: If you have a Raspberry Pi laying around,
[27:11] SPEAKER: you can hook that up to an external hard drive
[27:13] SPEAKER: and have like a tester.
[27:15] SPEAKER: Hey, do I really need a NAS for probably stuff
[27:18] SPEAKER: that you have in your house already would be my guess.
[27:20] SPEAKER: The installation process is very straightforward.
[27:23] SPEAKER: You can download an ISO from their website.
[27:26] SPEAKER: You either burn it onto a USB thumb drive
[27:29] SPEAKER: or burn it onto a CD if you still have a CD burner.
[27:32] SPEAKER: And then you just boot off of the,
[27:34] SPEAKER: boot the machine off of that thumb drive and go from there.
[27:38] SPEAKER: - So you've gotten hands-on with Open Media Vault.
[27:40] SPEAKER: I mean, I'm way down the TrueNAS rabbit hole,
[27:41] SPEAKER: but like you've kind of gone through this process.
[27:43] SPEAKER: Would you describe it as pretty user-friendly
[27:45] SPEAKER: to go through that installation setup?
[27:47] SPEAKER: - I thought I had a Raspberry Pi 4 laying around
[27:49] SPEAKER: that I could use to do this and I actually didn't,
[27:52] SPEAKER: but I did set it up on a VM inside my Windows machine
[27:55] SPEAKER: just to kind of test everything.
[27:56] SPEAKER: - Not to derail the conversation.
[27:58] SPEAKER: You've just given me an idea of which is maybe,
[28:00] SPEAKER: maybe it's worth having a cold spare Raspberry Pi
[28:03] SPEAKER: around at all times.
[28:04] SPEAKER: - I literally have one on order that'll be here in March.
[28:07] SPEAKER: So yeah.
[28:08] SPEAKER: - I'm starting to feel like maybe
[28:09] SPEAKER: a plus one Raspberry Pi strategy might be good to have
[28:11] SPEAKER: just like, 'cause you know,
[28:13] SPEAKER: in normal non-price inflation times,
[28:15] SPEAKER: like there are like what, the basic model is 35 bucks, right?
[28:18] SPEAKER: - The two gig memory one is $35, yeah.
[28:20] SPEAKER: - Having one around not doing anything at all times
[28:22] SPEAKER: is pretty handy just in case you have an idea
[28:24] SPEAKER: and wanna try something like this.
[28:26] SPEAKER: - And it's not like they'll conk out over time.
[28:28] SPEAKER: - Right.
[28:29] SPEAKER: - If it's sitting in the box.
[28:30] SPEAKER: So the things I really like about Open Media Vault
[28:32] SPEAKER: is it's pretty lightweight.
[28:33] SPEAKER: It's Linux-based, so you get your power management
[28:36] SPEAKER: and the kind of things you expect
[28:39] SPEAKER: from a modern operating system.
[28:41] SPEAKER: The web interface is really robust
[28:43] SPEAKER: and I was able to do everything I needed to do
[28:45] SPEAKER: to maintain the system from inside that web interface
[28:48] SPEAKER: using their OS installer ISO,
[28:51] SPEAKER: not doing the install Debian first,
[28:54] SPEAKER: then upgrade the Debian to have Open Media Vault
[28:56] SPEAKER: on top using apt-get.
[28:58] SPEAKER: The plugin infrastructure,
[28:59] SPEAKER: because you can just download Docker images
[29:01] SPEAKER: and run Docker images, it's incredibly,
[29:03] SPEAKER: like there are so many options out there.
[29:05] SPEAKER: We'll talk about TrueNAS' plugins in a little bit,
[29:08] SPEAKER: but the Docker images gives you a much easier path
[29:12] SPEAKER: to building your own.
[29:14] SPEAKER: If the default Docker images don't do what you want
[29:16] SPEAKER: or don't behave in a way you want,
[29:18] SPEAKER: it's pretty straightforward for you to set one up yourself
[29:20] SPEAKER: if you're so inclined.
[29:21] SPEAKER: - Yeah, I don't think I can overstate
[29:23] SPEAKER: how much more robust the Linux ecosystem is at this point.
[29:27] SPEAKER: No matter your level of experience as a listener
[29:30] SPEAKER: with the free and open source world,
[29:32] SPEAKER: you know exactly how big Linux is
[29:34] SPEAKER: 'cause it basically rules the world.
[29:35] SPEAKER: I mean, it runs the world at this point.
[29:37] SPEAKER: There is just tremendously more stuff available to run on it
[29:41] SPEAKER: and getting that stuff working is tremendously more,
[29:44] SPEAKER: I guess, compatible is the way I would put it.
[29:45] SPEAKER: A lot of the projects that we'll talk about
[29:47] SPEAKER: like in this episode or even going forward
[29:48] SPEAKER: in future episodes are also available for FreeBSD,
[29:52] SPEAKER: which TrueNAS is based on,
[29:53] SPEAKER: but like, you know, there's always gonna be the risk
[29:55] SPEAKER: that like, oh, some library is not quite compatible
[29:57] SPEAKER: and it's like you're gonna run into some esoteric problem
[29:59] SPEAKER: or you might not be able to get it to run at all,
[30:02] SPEAKER: or a lot of projects just are not available
[30:04] SPEAKER: on the FreeBSD side.
[30:05] SPEAKER: So having a NAS that runs Linux and has Docker support
[30:09] SPEAKER: and uses the most common tools and platforms
[30:12] SPEAKER: that the most people are using
[30:13] SPEAKER: is gonna guarantee way more software availability.
[30:16] SPEAKER: - And in a more timely manner too.
[30:17] SPEAKER: Like often I noticed that things on the TrueNAS side
[30:20] SPEAKER: would lag behind a release or two sometimes,
[30:23] SPEAKER: which is usually fine.
[30:24] SPEAKER: - My Plex client is constantly saying,
[30:26] SPEAKER: hey, there's a server update, you should go get it.
[30:28] SPEAKER: And I'm like, no, it hasn't been added
[30:29] SPEAKER: to the FreeBSD package manager yet,
[30:31] SPEAKER: I can't actually do that.
[30:33] SPEAKER: - Well, so we'll talk about that more in the TrueNAS side,
[30:35] SPEAKER: but I found that the plugin infrastructure on TrueNAS
[30:38] SPEAKER: was frustrating enough and limited enough
[30:41] SPEAKER: that I often would just rebuild plugin functionality
[30:44] SPEAKER: in jails on my own.
[30:45] SPEAKER: - Yes.
[30:46] SPEAKER: - But yeah, on the Open Media Vault side,
[30:48] SPEAKER: the web interface is great.
[30:49] SPEAKER: You can set up new shares, you can combine drives,
[30:52] SPEAKER: you can turn on RAID,
[30:53] SPEAKER: you can do all the things you would expect to
[30:55] SPEAKER: without having to touch a shell at all
[30:57] SPEAKER: once you get the OS installed.
[30:59] SPEAKER: And the OS install process was answering,
[31:01] SPEAKER: I think, seven questions, booting off of a thumb drive,
[31:04] SPEAKER: answering seven or eight questions, and then moving forward.
[31:07] SPEAKER: Now, the hardware best practices for,
[31:11] SPEAKER: well, we'll get into the best practices
[31:13] SPEAKER: for where to install this stuff,
[31:14] SPEAKER: 'cause the weird thing about a lot of these NAS OSs
[31:17] SPEAKER: is you install them from a thumb drive,
[31:19] SPEAKER: but you also are often recommended
[31:21] SPEAKER: to install them to a thumb drive.
[31:24] SPEAKER: There's pros and cons to that,
[31:26] SPEAKER: the number of write cycles that most SD memory,
[31:30] SPEAKER: flash memory, can handle is fairly limited.
[31:33] SPEAKER: And if you're writing, say, log files to those thumb drives,
[31:37] SPEAKER: you'll burn out the drives in a year or two
[31:40] SPEAKER: if you're not careful.
[31:40] SPEAKER: - Or even faster, depending on what you're doing.
[31:42] SPEAKER: I would say, so yes, the running true NAS
[31:45] SPEAKER: off of USB thumb drives was the kind of best practice
[31:49] SPEAKER: for years and years.
[31:50] SPEAKER: I'd say that's kind of finally sort of been deprecated.
[31:52] SPEAKER: Like SSDs, like legit SSDs,
[31:54] SPEAKER: are getting cheap enough at this point
[31:56] SPEAKER: that you can actually just get a couple of SSDs
[31:58] SPEAKER: for this purpose for not that much more.
[32:00] SPEAKER: I bought a couple of 120 gig SSDs for like 20 bucks a piece
[32:04] SPEAKER: that I run my true NAS install off of now.
[32:06] SPEAKER: So SD cards and USB thumb drives generally
[32:09] SPEAKER: are just pretty poor at resilience over time.
[32:12] SPEAKER: - The SSD solution is good.
[32:15] SPEAKER: 'Cause the thing to remember about these OSs
[32:16] SPEAKER: is they're small.
[32:19] SPEAKER: The true NAS install is I think 18 gigs
[32:21] SPEAKER: or something like that.
[32:22] SPEAKER: It's negligible.
[32:25] SPEAKER: The Open Media Vault install was very small too.
[32:27] SPEAKER: I think it was two gigs total or something.
[32:29] SPEAKER: But yeah, I haven't run it on production hardware yet.
[32:32] SPEAKER: That's my next step for the Open Media Vault.
[32:34] SPEAKER: But I'm really excited.
[32:37] SPEAKER: Getting the Docker images up and running
[32:39] SPEAKER: took about five minutes.
[32:41] SPEAKER: And I can grab the images, upload them to the machine
[32:44] SPEAKER: and set them to run.
[32:46] SPEAKER: And then they just run, which is amazing.
[32:48] SPEAKER: - So does OMV have any kind of central repository
[32:51] SPEAKER: of its own kind of one click install,
[32:52] SPEAKER: like click here to install the Plex Docker image?
[32:54] SPEAKER: Or do you have to go out
[32:55] SPEAKER: and do you have to get the images yourself?
[32:57] SPEAKER: I mean, it sounds like even if that's the case,
[32:59] SPEAKER: that's not that difficult, but.
[33:00] SPEAKER: - The repository that it has built in
[33:03] SPEAKER: is a little more limited.
[33:05] SPEAKER: It's like things you would use to manage the server maybe,
[33:07] SPEAKER: rather than necessarily like your full fledged,
[33:11] SPEAKER: hey, here are all the applications you might wanna run.
[33:14] SPEAKER: But one of the things you can add
[33:16] SPEAKER: is a third party repository that adds Docker support
[33:19] SPEAKER: and then adds a handful of other utilities on top of that.
[33:23] SPEAKER: So there's a plugin that backups,
[33:25] SPEAKER: backs up all of the conflict files for the entire thing.
[33:27] SPEAKER: And we'll let you share that, save that wherever you want.
[33:30] SPEAKER: Here's a SCSI over ethernet plugin, if you wanna do that.
[33:35] SPEAKER: - You know, everybody's most common use case.
[33:37] SPEAKER: - You can remote mount remote.
[33:39] SPEAKER: Here's a plugin that lets you mount remote shares.
[33:41] SPEAKER: So if you wanted to do the thing like I was talking about
[33:43] SPEAKER: and have a dedicated NAS box with hard drives in it
[33:46] SPEAKER: and mount the shares from that as file system here,
[33:49] SPEAKER: there's a plugin for that.
[33:50] SPEAKER: So you don't have to fool with Fstab files
[33:52] SPEAKER: and stuff like that.
[33:53] SPEAKER: - Right, but you know,
[33:54] SPEAKER: like there are a bajillion Docker resources
[33:56] SPEAKER: out there at this point.
[33:57] SPEAKER: Like, if you just want to go see like,
[33:59] SPEAKER: hey, what are some containers I can run here
[34:01] SPEAKER: on this new thing I've set up?
[34:02] SPEAKER: And like, you wanna run a Minecraft server for people
[34:04] SPEAKER: or like, you know, plex or whatever kind of thing
[34:07] SPEAKER: you're looking for.
[34:07] SPEAKER: - It's nigh infinite.
[34:09] SPEAKER: - I think, yes, going to Google and typing kind of Docker
[34:12] SPEAKER: and whatever you're looking for
[34:13] SPEAKER: is probably enough to get you started.
[34:14] SPEAKER: There's a lot out there.
[34:15] SPEAKER: - And the nice thing about the way Docker works
[34:17] SPEAKER: is you can actually, like, if you have say,
[34:20] SPEAKER: a home assistant plugin that you need to connect
[34:23] SPEAKER: to like a Z-Wave radio so that it can control
[34:26] SPEAKER: your light bulbs, that's an option too.
[34:28] SPEAKER: Like you have access to those resources,
[34:30] SPEAKER: those hardware resources from inside the Docker containers.
[34:33] SPEAKER: So that's kind of the high level on Open Media Vault.
[34:36] SPEAKER: I think really, if people wanna start out,
[34:39] SPEAKER: the best thing to do is to order a Raspberry Pi 4,
[34:43] SPEAKER: wait three weeks or a month for it to get here,
[34:46] SPEAKER: put it on the, plug an external hard drive into this
[34:49] SPEAKER: and set it up.
[34:50] SPEAKER: Now it will, you'll lose whatever is currently
[34:53] SPEAKER: on that external hard drive.
[34:54] SPEAKER: So you wanna either start with a fresh external hard drive
[34:56] SPEAKER: or backup whatever's on the external hard drive
[34:57] SPEAKER: before you turn it into the NAS box,
[35:00] SPEAKER: because Open Media Vault will reformat it
[35:01] SPEAKER: when you plug it in and set up the new drive.
[35:04] SPEAKER: But it's a good way to get your feet wet
[35:08] SPEAKER: before you get into the deep end with TrueNAS.
[35:12] SPEAKER: (dramatic music)
[35:14] SPEAKER: - Are we doing it?
[35:15] SPEAKER: - Is it time?
[35:16] SPEAKER: - Are we descending the rabbit hole?
[35:17] SPEAKER: - Yeah, so let's go one layer deeper.
[35:19] SPEAKER: Let's peel the onion one more time
[35:20] SPEAKER: and see what's going on with TrueNAS these days, Brad.
[35:23] SPEAKER: - Yeah, so TrueNAS, well, so there's been some rebranding
[35:26] SPEAKER: there, I mean, some of the information,
[35:27] SPEAKER: if you start Googling is gonna maybe be a little confusing
[35:29] SPEAKER: because they rebranded from FreeNAS to TrueNAS
[35:32] SPEAKER: about a year ago, I wanna say at this point, maybe.
[35:35] SPEAKER: - Maybe a little more than that, yeah.
[35:37] SPEAKER: - Year and a half, something like that.
[35:38] SPEAKER: The current consumer product is currently
[35:40] SPEAKER: called TrueNAS Core.
[35:41] SPEAKER: They do have like a TrueNAS enterprise that is
[35:43] SPEAKER: for straight up large corporations,
[35:45] SPEAKER: but the free open source downloadable,
[35:48] SPEAKER: just anybody can get it and run it,
[35:49] SPEAKER: version that is based on FreeBSD is TrueNAS Core.
[35:52] SPEAKER: - And the install process is similar to Open Media Vault,
[35:55] SPEAKER: right, you download it, burn it to a thumb drive,
[35:57] SPEAKER: put it in a machine and install the NAS software
[36:01] SPEAKER: on the machine, on whatever machine.
[36:03] SPEAKER: - So the single biggest selling point of using TrueNAS
[36:05] SPEAKER: is that it allows you to use ZFS,
[36:07] SPEAKER: which is a really advanced file system
[36:08] SPEAKER: that came out of the server world that, like I said,
[36:11] SPEAKER: it's got pretty heavy memory requirements.
[36:12] SPEAKER: You're gonna need like a bare minimum of eight gigabytes
[36:15] SPEAKER: of memory for any heavy duty storage you're doing.
[36:17] SPEAKER: - Well, and the memory requirements go up
[36:19] SPEAKER: the more storage space you add to your drive pool, right?
[36:22] SPEAKER: - To a degree for a home NAS, you're probably gonna be
[36:24] SPEAKER: looking at maybe 16 gigabytes at least
[36:26] SPEAKER: if you really want good performance there.
[36:29] SPEAKER: Also, I should just go ahead and mention here
[36:30] SPEAKER: for the sake of clarity that TrueNAS is meant to be run
[36:33] SPEAKER: on a full-size x86 computer, you know,
[36:35] SPEAKER: that's an Intel Core i5 or a Ryzen of some sort,
[36:39] SPEAKER: but it is not lightweight like Open Media Vault
[36:42] SPEAKER: or other kind of Linux-based solutions.
[36:45] SPEAKER: It will not run on a Raspberry Pi.
[36:47] SPEAKER: You can technically run it on a small x86 box,
[36:50] SPEAKER: like an Intel NUC, but even that is maybe a little dicey
[36:53] SPEAKER: in terms of how many hard drives you can hook up
[36:55] SPEAKER: and the kind of horsepower you're gonna be working with.
[36:57] SPEAKER: It's, TrueNAS really is meant to be put
[36:59] SPEAKER: on a full-size computer, and that's part of where those
[37:02] SPEAKER: kind of hefty electricity requirements come in.
[37:04] SPEAKER: And so, as we've said, the biggest reason to use TrueNAS
[37:07] SPEAKER: is as a vehicle for using ZFS as your file system.
[37:11] SPEAKER: The single biggest advantage of ZFS
[37:13] SPEAKER: is that it really emphasizes resilience.
[37:15] SPEAKER: It allows you to snapshot entire file systems
[37:18] SPEAKER: and essentially keep a copy of them in the background
[37:20] SPEAKER: as they change, and you can roll back to previous snapshots.
[37:22] SPEAKER: It makes it real easy to send snapshots to other drives
[37:24] SPEAKER: or other storage pools or devices on your network.
[37:27] SPEAKER: - Does that also let you go back,
[37:29] SPEAKER: like if you wanna find the version of a file
[37:30] SPEAKER: from like three weeks ago, you can go back in time
[37:32] SPEAKER: and get the version of that file from three weeks ago?
[37:34] SPEAKER: - Absolutely, and like I ended up, like when I,
[37:36] SPEAKER: like I said, it's been a teeth rabbit hole.
[37:37] SPEAKER: Like I've learned how to do all that stuff
[37:38] SPEAKER: from the command line in FreeBSD originally,
[37:40] SPEAKER: but they have since rolled out the option to merge that
[37:44] SPEAKER: with, for example, if you're sharing over SMB
[37:47] SPEAKER: from a TrueNAS machine to Windows.
[37:48] SPEAKER: - CIFS, yeah.
[37:49] SPEAKER: - Standard Windows file sharing stuff, right.
[37:51] SPEAKER: In File Explorer, the CFS snapshots now show up as the,
[37:56] SPEAKER: I think in Windows it's called shadow copies,
[37:58] SPEAKER: is that right?
[37:59] SPEAKER: - Shadow copies is the Windows feature, yeah.
[38:00] SPEAKER: - You can get properties on a folder in Windows
[38:03] SPEAKER: and just hit the previous versions tab
[38:04] SPEAKER: and it will just list out every snapshot
[38:06] SPEAKER: of that folder you have as previous dates.
[38:09] SPEAKER: You can literally just open one of those
[38:10] SPEAKER: as another File Explorer window
[38:12] SPEAKER: that has those previous versions of the files.
[38:14] SPEAKER: If you've deleted something, you can go back and get it.
[38:16] SPEAKER: Snapshots also make it real easy to back up, kinda en masse.
[38:20] SPEAKER: It's a very powerful system if you really want
[38:22] SPEAKER: to make sure you're not gonna lose any data.
[38:24] SPEAKER: It is a lot to learn now.
[38:25] SPEAKER: - Well, and it's a lot of overhead.
[38:27] SPEAKER: Like you need a real computer, you're not gonna run this
[38:30] SPEAKER: on a lightweight embedded NAS box.
[38:33] SPEAKER: You wanna have multiple cores and a bunch of memory.
[38:36] SPEAKER: One of the other things that drew me to TrueNAS early on
[38:39] SPEAKER: were jails.
[38:40] SPEAKER: Well, jails and plugins, kind of two sides of the same coin.
[38:43] SPEAKER: - I think in the TrueNAS parlance,
[38:45] SPEAKER: a plugin really is just a jail underneath.
[38:48] SPEAKER: So a jail is a form of container that is native to FreeBSD.
[38:51] SPEAKER: I think most people know
[38:53] SPEAKER: about virtual machines at this point.
[38:54] SPEAKER: Docker is another example of containerization.
[38:56] SPEAKER: So basically the key difference between virtual machines
[38:59] SPEAKER: or virtualization and containerization
[39:01] SPEAKER: is that VMs replicate an entire hardware stack
[39:03] SPEAKER: from the very basic level up, right?
[39:05] SPEAKER: VMs run their own kernel.
[39:07] SPEAKER: They are a fully self-contained sandboxed virtual computer.
[39:11] SPEAKER: Containers run on the system host,
[39:13] SPEAKER: like they run on the kernel of the host.
[39:15] SPEAKER: They share resources, they're much lower overhead
[39:17] SPEAKER: and more performant,
[39:18] SPEAKER: although not that VMs are like not performant,
[39:20] SPEAKER: but containers are more lightweight in terms of resources,
[39:22] SPEAKER: but they do exist within the kind of ecosystem
[39:25] SPEAKER: of the host that they run on.
[39:26] SPEAKER: They just use kind of name spacing
[39:28] SPEAKER: and other sorts of sandboxing features
[39:30] SPEAKER: to kind of make them discrete from the host.
[39:33] SPEAKER: - When you run PSA UX on a FreeBSD machine
[39:37] SPEAKER: that has jails running,
[39:38] SPEAKER: you see the processes that are running inside those jails
[39:40] SPEAKER: if you're on the root machine.
[39:42] SPEAKER: - Yes, but if you go inside the jail,
[39:43] SPEAKER: inside the jail, the jail thinks it's just a computer
[39:46] SPEAKER: unto itself with nothing happening outside of it.
[39:47] SPEAKER: It's kind of a fascinating model, but yes,
[39:50] SPEAKER: at the host level, you'll see everything
[39:51] SPEAKER: that's running on every jail and machine.
[39:53] SPEAKER: - Well, but the, so the upshot is you can set up,
[39:55] SPEAKER: if you have say five applications
[39:57] SPEAKER: that you want to run on your NAS machine,
[39:59] SPEAKER: like a game server, a media server, a print server,
[40:04] SPEAKER: stuff like that, then you set up a jail for each one
[40:06] SPEAKER: and then each of those is maintained independently
[40:08] SPEAKER: and you can turn them on and off as needed.
[40:10] SPEAKER: - Right, yes.
[40:11] SPEAKER: So in FreeBSD/TrueNAS land,
[40:13] SPEAKER: that's how you would approach kind of discrete system services
[40:16] SPEAKER: like that, you know, Docker does replicate
[40:18] SPEAKER: that kind of same functionality
[40:19] SPEAKER: with a slightly different paradigm
[40:21] SPEAKER: in something like Open Media Vault.
[40:22] SPEAKER: You can do other cool stuff with containers,
[40:24] SPEAKER: like you can assign them their own network IPs
[40:26] SPEAKER: and then, you know, you can even map their names
[40:29] SPEAKER: to a local domain on your, on your network.
[40:32] SPEAKER: You can do like .lan for stuff.
[40:33] SPEAKER: So you could go to like plex.lan
[40:35] SPEAKER: could be the address for your plex.
[40:37] SPEAKER: - Wait, wait, wait, you're a .lan?
[40:39] SPEAKER: - Yeah.
[40:40] SPEAKER: - I'm a .local.
[40:40] SPEAKER: - Well, .local is kind of the industry standard,
[40:42] SPEAKER: but that's two syllables.
[40:43] SPEAKER: That's two more pairs.
[40:45] SPEAKER: - Fair, look, you make a good point.
[40:47] SPEAKER: Do you wanna type five characters or do you wanna type three?
[40:49] SPEAKER: - Fair, now I'm gonna have to change everything.
[40:51] SPEAKER: - But yeah, like, you know, abstracting services out
[40:53] SPEAKER: to little containers has a lot of cool advantages like that.
[40:56] SPEAKER: You know, like they exist as like separate machines
[40:58] SPEAKER: on your network as well as separate little virtual computers
[41:02] SPEAKER: on the host.
[41:03] SPEAKER: - Yeah.
[41:03] SPEAKER: - On top of all those benefits,
[41:04] SPEAKER: I mean, the actual secret real reason
[41:07] SPEAKER: to prefer using containers
[41:09] SPEAKER: for putting all your little services in containers
[41:11] SPEAKER: is that it protects you from screwing anything up
[41:13] SPEAKER: because each container
[41:15] SPEAKER: is its own little self-contained computer.
[41:16] SPEAKER: And like, you know, you can spin a new one up
[41:18] SPEAKER: whenever you feel like it.
[41:19] SPEAKER: If you mess something up in there,
[41:21] SPEAKER: you can kind of just delete it and start over.
[41:23] SPEAKER: You can clone them if you wanna try something
[41:26] SPEAKER: and that may not work.
[41:27] SPEAKER: And then you can just delete that clone
[41:28] SPEAKER: and go back to where you were.
[41:30] SPEAKER: They are just a sandbox way,
[41:32] SPEAKER: especially when you're starting out.
[41:33] SPEAKER: And I cannot stress this enough.
[41:35] SPEAKER: If you don't have a lot of experience, you know,
[41:37] SPEAKER: at a bash prompt or with open source stuff in general,
[41:39] SPEAKER: like it's just the best safety net you can have really
[41:41] SPEAKER: to be able to create a fake computer
[41:44] SPEAKER: that you can then dive into and just tinker around with
[41:46] SPEAKER: and not worry too much about messing up the host
[41:48] SPEAKER: because you can just, you know, hose that container
[41:50] SPEAKER: and make a new one whenever you feel like it.
[41:52] SPEAKER: It's, I highly recommend it,
[41:53] SPEAKER: whatever kind of paradigm you're working with,
[41:55] SPEAKER: whether it's jails or Docker
[41:56] SPEAKER: or there are plenty of other container solutions
[41:59] SPEAKER: in Linux as well.
[42:01] SPEAKER: But if you're really trying to get your feet wet
[42:02] SPEAKER: with this stuff, it's just, it's a fantastic way
[42:05] SPEAKER: to have some peace of mind as you poke at stuff
[42:07] SPEAKER: and sort of figure out how everything works
[42:09] SPEAKER: without worrying that you're going to, you know,
[42:11] SPEAKER: create a lot of work for yourself by ending up
[42:12] SPEAKER: in a situation where you have to say,
[42:14] SPEAKER: wipe the entire TrueNAS install or Open Media Vault
[42:17] SPEAKER: or whatever your OS is, you know, from the ground up
[42:20] SPEAKER: because you did something on the host
[42:22] SPEAKER: that you can't recover from.
[42:23] SPEAKER: Jails and TrueNAS are one way to do that.
[42:25] SPEAKER: Docker and Linux based solutions are another.
[42:27] SPEAKER: There are a bunch of different container solutions out there
[42:29] SPEAKER: and jails are basically full FreeBSD machines.
[42:33] SPEAKER: So like you kind of do need to know what you're doing
[42:35] SPEAKER: at the command line for the most part
[42:36] SPEAKER: to take advantage of that stuff.
[42:38] SPEAKER: But once you do, you can follow basic
[42:40] SPEAKER: how to install processes for whatever service
[42:42] SPEAKER: you want to add and run through the shell scripts
[42:45] SPEAKER: pretty easily is my experience.
[42:47] SPEAKER: Like just generally speaking, the kind of pros
[42:50] SPEAKER: of TrueNAS are that it's incredibly powerful.
[42:52] SPEAKER: You could do a lot with it.
[42:54] SPEAKER: It is a real performance hog.
[42:57] SPEAKER: It's kind of bad on power management.
[43:00] SPEAKER: FreeBS, the current version of TrueNAS is better
[43:01] SPEAKER: than the previous ones have been,
[43:03] SPEAKER: but it does have a tendency to run your CPU
[43:06] SPEAKER: at basically full speed all the time
[43:08] SPEAKER: 'cause it doesn't use the internal power.
[43:10] SPEAKER: BSD is not as good at internal power management
[43:12] SPEAKER: as Linux and Windows are.
[43:14] SPEAKER: Generally speaking, if you know how to set it up
[43:17] SPEAKER: and do a good job setting up,
[43:18] SPEAKER: you can get unbelievable performance out of it.
[43:21] SPEAKER: If you do not, you can really, really hamper your ability
[43:25] SPEAKER: to get good performance out of the machine.
[43:27] SPEAKER: And you may find yourself rebuilding this a couple of times
[43:29] SPEAKER: before you get it right in my experience.
[43:31] SPEAKER: - Yes, like it's very easy to make mistakes,
[43:32] SPEAKER: like laying out your drive arrangement
[43:34] SPEAKER: as like when you make a ZFS volume for the first time.
[43:36] SPEAKER: There are a ton of considerations there about like,
[43:39] SPEAKER: do I wanna make this a RAID-Z situation
[43:41] SPEAKER: where I can lose one or two or even three drives
[43:43] SPEAKER: and not lose my data?
[43:45] SPEAKER: But there are parity requirements there.
[43:46] SPEAKER: Do I wanna do mirrors?
[43:47] SPEAKER: There's a lot there that you really need to be ready
[43:49] SPEAKER: to kind of educate yourself on
[43:51] SPEAKER: to try to not to make too many mistakes upfront.
[43:53] SPEAKER: - There's a couple of things to think about,
[43:54] SPEAKER: and this is a good place to talk about this.
[43:56] SPEAKER: There's the idea of data redundancy,
[43:58] SPEAKER: which means that a drive can fail
[44:00] SPEAKER: and your system stays up.
[44:02] SPEAKER: You don't lose any data when one drive fails.
[44:05] SPEAKER: There's backing up, which is often the better choice.
[44:08] SPEAKER: Like doing an offsite backup
[44:09] SPEAKER: for your network attached storage
[44:12] SPEAKER: takes two times the number of drives
[44:14] SPEAKER: or two times the total amount of storage.
[44:17] SPEAKER: But if you're not writing to the NAS
[44:18] SPEAKER: constantly losing a day's worth of data
[44:21] SPEAKER: is not that big a deal for most people,
[44:24] SPEAKER: 'cause usually in that one day
[44:25] SPEAKER: it'll still be saved someplace else.
[44:27] SPEAKER: The thing to remember always
[44:31] SPEAKER: is that data redundancy is not equal to backup.
[44:34] SPEAKER: - Right, yes, that is a mantra you will hear all the time
[44:37] SPEAKER: if you get deep into the kind of NAS world
[44:39] SPEAKER: is RAID is not backup.
[44:41] SPEAKER: - Yeah, and what that means is if, for example,
[44:44] SPEAKER: you have a virus on your computer at home
[44:47] SPEAKER: and that virus hits your NAS
[44:49] SPEAKER: and deletes all the files on your NAS,
[44:51] SPEAKER: having redundant storage on the NAS
[44:55] SPEAKER: won't necessarily prevent you from losing data in that case.
[44:57] SPEAKER: Now with TrueNAS and ZFS,
[44:59] SPEAKER: if you have the snapshot set up right,
[45:00] SPEAKER: you'll just roll back to a previous snapshot.
[45:01] SPEAKER: It's not a big deal, but don't treat a NAS as backup
[45:06] SPEAKER: unless it is actually backup,
[45:08] SPEAKER: unless you're keeping copies of data
[45:09] SPEAKER: on your local machines and the NAS.
[45:11] SPEAKER: At that point, it is backup.
[45:12] SPEAKER: - Right, RAID is, to a degree, resilient to hardware failure.
[45:15] SPEAKER: Like I said, there are arrangements
[45:17] SPEAKER: that will allow you to lose one or more drives
[45:18] SPEAKER: and keep your data, but then you're in a degraded state
[45:21] SPEAKER: where you've gotta add a new drive
[45:22] SPEAKER: and there are increased stresses
[45:24] SPEAKER: on the remaining drives as you rebuild.
[45:26] SPEAKER: Something else can go wrong there.
[45:28] SPEAKER: It's still a single point of failure.
[45:29] SPEAKER: That's really what it is, is having one,
[45:31] SPEAKER: even if it's a bunch of drives,
[45:33] SPEAKER: it's one entity that is a single point of failure
[45:35] SPEAKER: and just having a second copy
[45:36] SPEAKER: of any important data backed up is still critical
[45:39] SPEAKER: 'cause things can still go wrong.
[45:41] SPEAKER: - Okay, so now I think is a good time to talk about
[45:44] SPEAKER: what's going on in the TrueNAS world.
[45:46] SPEAKER: There's TrueNAS Core, which is BSD-based.
[45:49] SPEAKER: - So this is why I stress the TrueNAS Core name
[45:52] SPEAKER: because they are actually,
[45:53] SPEAKER: IX Systems is the company that primarily runs TrueNAS,
[45:57] SPEAKER: although it is open source, anybody can contribute to it.
[45:59] SPEAKER: So there is a Linux-based version of TrueNAS forthcoming
[46:03] SPEAKER: called TrueNAS Scale.
[46:04] SPEAKER: I haven't tried it yet because it's still
[46:06] SPEAKER: in release candidate phase.
[46:07] SPEAKER: It's not quite ready to go yet
[46:09] SPEAKER: and I'm not quite ready to run pre-release software
[46:13] SPEAKER: on a crucial storage box right now.
[46:15] SPEAKER: - Yeah, just to be clear, when you're setting up your NAS,
[46:17] SPEAKER: you usually go for the stable long-term version,
[46:20] SPEAKER: not the cutting edge version is my advice.
[46:23] SPEAKER: - Building a NAS is when I started learning
[46:25] SPEAKER: to value the uptime number over the version number.
[46:28] SPEAKER: - Yes. - You know,
[46:29] SPEAKER: I'm gonna resist updating every single time
[46:32] SPEAKER: a new version or feature comes out.
[46:33] SPEAKER: - You update when needed, not when not available.
[46:37] SPEAKER: - So ZFS has been essentially available
[46:40] SPEAKER: and production ready in the FreeBSD world for years.
[46:43] SPEAKER: It is built into the kernel.
[46:44] SPEAKER: It's like ready to go, it's considered rock solid.
[46:47] SPEAKER: That has not been the case in the Linux world
[46:49] SPEAKER: where there are license incompatibilities
[46:51] SPEAKER: between the Linux kernel and ZFS
[46:53] SPEAKER: that prevent it from becoming part of the kernel tree.
[46:55] SPEAKER: And so ZFS is incredibly fully featured
[46:58] SPEAKER: and mature now on Linux, but it's still kind of this like,
[47:02] SPEAKER: it does not enjoy a most favored nation status
[47:04] SPEAKER: as a file system, let's say, where it is an add-on.
[47:07] SPEAKER: It is something you have to add.
[47:08] SPEAKER: So it's basically something that IX is doing themselves.
[47:10] SPEAKER: They're integrating ZFS for Linux
[47:12] SPEAKER: into the TrueNAS framework.
[47:14] SPEAKER: So essentially the upshot is it's going to be
[47:16] SPEAKER: a Linux-based version of TrueNAS.
[47:17] SPEAKER: And so you're gonna get Kubernetes
[47:18] SPEAKER: and Docker support with that.
[47:20] SPEAKER: - Which aren't available on the BSD side.
[47:21] SPEAKER: - Right, yeah, so that goes back
[47:23] SPEAKER: to that software compatibility thing I was talking about
[47:25] SPEAKER: is that there's just the ease of finding services
[47:28] SPEAKER: and applications that you wanna run
[47:30] SPEAKER: is so much greater on Linux
[47:32] SPEAKER: that I think this is probably gonna be a pretty big boon
[47:34] SPEAKER: to the TrueNAS world.
[47:36] SPEAKER: Just to give a super quick example,
[47:37] SPEAKER: just to illustrate the point, back early in the pandemic,
[47:39] SPEAKER: I wanted to run a Terraria server
[47:41] SPEAKER: for some friends on my TrueNAS machine.
[47:43] SPEAKER: Terraria, if you're not familiar with it,
[47:44] SPEAKER: is basically 2D Minecraft.
[47:47] SPEAKER: But I went to see if I could set that Terraria server up
[47:50] SPEAKER: on the TrueNAS box, which is FreeBSD.
[47:52] SPEAKER: And it turned out that Mono,
[47:54] SPEAKER: the framework that Terraria is built on
[47:56] SPEAKER: does not exist for FreeBSD,
[47:58] SPEAKER: at least not a current version
[48:00] SPEAKER: that's required to run a Terraria server.
[48:03] SPEAKER: On Linux, that's just trivial.
[48:04] SPEAKER: Like that's essentially the platform
[48:06] SPEAKER: where that is probably the best supported or it's one of.
[48:09] SPEAKER: So just one example out of probably many
[48:12] SPEAKER: where it's just like, oh, this is dead simple
[48:14] SPEAKER: to set up in Linux because of the support is there,
[48:16] SPEAKER: the development resources are there,
[48:17] SPEAKER: and it just doesn't exist for FreeBSD.
[48:19] SPEAKER: So that's one of the big reasons
[48:21] SPEAKER: that I think TrueNAS scale is pretty exciting.
[48:24] SPEAKER: But for the time being, they're saying
[48:25] SPEAKER: that both versions are going to coexist side by side,
[48:27] SPEAKER: depending on what your needs are.
[48:29] SPEAKER: - Okay.
[48:29] SPEAKER: - But if you do end up tumbling down this rabbit hole,
[48:31] SPEAKER: a TrueNAS scale is something that's worth keeping an eye on
[48:34] SPEAKER: as it matures over the coming months.
[48:36] SPEAKER: - I'm really, like TrueNAS scale is kind of the,
[48:38] SPEAKER: maybe the best of both worlds for somebody in my position
[48:42] SPEAKER: where I want something that's a little bit lighter weight,
[48:43] SPEAKER: but also I do like having the snapshots on ZFS
[48:46] SPEAKER: and I do like the ability to roll back old files
[48:49] SPEAKER: as it turns out really convenient.
[48:49] SPEAKER: - Yeah, being able to roll back and grab a file
[48:51] SPEAKER: that I shouldn't have deleted
[48:52] SPEAKER: that I just got a little too antsy and was like,
[48:53] SPEAKER: I'm not going to need this anymore and tossed it.
[48:55] SPEAKER: And six hours later it was like,
[48:56] SPEAKER: boy, I wish I still had that file.
[48:57] SPEAKER: Like that's a great feeling to know like,
[48:59] SPEAKER: oh, I can still go get that.
[49:01] SPEAKER: - Okay, so Brad, if you want to get started with TrueNAS,
[49:03] SPEAKER: what do you do?
[49:03] SPEAKER: Just download the latest version from their website?
[49:05] SPEAKER: Would you start with the Linux version now
[49:07] SPEAKER: or would you go stick with core for the time being?
[49:09] SPEAKER: - If you want to get started with TrueNAS,
[49:11] SPEAKER: step one, take a deep breath.
[49:14] SPEAKER: Step two, I would absolutely not start with TrueNAS scale
[49:18] SPEAKER: unless you're just incredibly brave.
[49:19] SPEAKER: I mean, like I said,
[49:20] SPEAKER: it is a pre-release version of the software
[49:22] SPEAKER: that they have not put out
[49:23] SPEAKER: a full production ready version yet.
[49:25] SPEAKER: TrueNAS core is still the place to start
[49:27] SPEAKER: if you want to give it a try.
[49:28] SPEAKER: Head to the TrueNAS site,
[49:29] SPEAKER: download the install image of the latest version
[49:31] SPEAKER: and give it a shot.
[49:32] SPEAKER: - Grab your Balina Etcher and burn it to a USB thumb drive.
[49:36] SPEAKER: - Yeah, and they've got, you know,
[49:37] SPEAKER: there are blogs and stuff out there you can Google up
[49:38] SPEAKER: that have pretty good recommendations
[49:40] SPEAKER: for hardware configurations, specs and stuff like that.
[49:43] SPEAKER: And like it's, I would say, if you're looking at TrueNAS,
[49:45] SPEAKER: you know, give some of that stuff a read
[49:46] SPEAKER: before you do get into it,
[49:48] SPEAKER: because you will get some insight into like,
[49:50] SPEAKER: how big of a, you know, how much CPU do I need?
[49:52] SPEAKER: How much memory do I need?
[49:53] SPEAKER: And like that might be a decision-making factor.
[49:55] SPEAKER: - Well, and the other thing I would say is with TrueNAS,
[49:57] SPEAKER: especially since it's been around for a really long time,
[49:59] SPEAKER: when you Google, when you're Googling
[50:01] SPEAKER: to find answers about TrueNAS,
[50:03] SPEAKER: make sure you include the current version,
[50:04] SPEAKER: the version number you're using,
[50:06] SPEAKER: because you will find answers to questions
[50:11] SPEAKER: from 10 or 12 years ago in some cases with TrueNAS.
[50:16] SPEAKER: So there is one more higher degree of difficulty mode.
[50:20] SPEAKER: - There is another.
[50:22] SPEAKER: - Proxmox is a hypervisor.
[50:23] SPEAKER: So it's basically an operating system
[50:26] SPEAKER: that runs other operating systems underneath it.
[50:29] SPEAKER: - It's also Debian-based, Debian Linux.
[50:32] SPEAKER: I mean, you can run VMs in TrueNAS as well,
[50:34] SPEAKER: but then you're using the BSD hypervisor, which, you know.
[50:36] SPEAKER: - It's not super performant, it turns out.
[50:38] SPEAKER: - Yeah, I mean, people typically,
[50:39] SPEAKER: from what I've seen about Proxmox,
[50:41] SPEAKER: I have not used it myself,
[50:42] SPEAKER: but people tend to do the opposite
[50:43] SPEAKER: where they run Proxmox as the host.
[50:45] SPEAKER: Like they'll frequently run TrueNAS
[50:46] SPEAKER: in a virtual machine inside of Proxmox.
[50:48] SPEAKER: They might also run like another Linux in there
[50:51] SPEAKER: or something, you know, like you can spin up VMs
[50:53] SPEAKER: and containers, like I was saying before,
[50:55] SPEAKER: they have slightly different use cases,
[50:56] SPEAKER: but Proxmox lets you kind of build
[50:59] SPEAKER: a really multifaceted system of computers virtually
[51:03] SPEAKER: that are all talking to each other
[51:04] SPEAKER: and all performing different functions independently.
[51:07] SPEAKER: It's a lot.
[51:08] SPEAKER: - It's a lot, it's complicated,
[51:10] SPEAKER: especially if you're gonna try to run TrueNAS,
[51:12] SPEAKER: which ZFS requires low level access to the drives.
[51:15] SPEAKER: The setup for that is complicated as a result of that.
[51:18] SPEAKER: So it's definitely a, hey, I know what I'm doing
[51:21] SPEAKER: and I wanna, I'm gonna do something that's gonna be a pain.
[51:24] SPEAKER: But if you are doing, if you're running,
[51:27] SPEAKER: for example, if you wanna run Docker containers
[51:28] SPEAKER: where performance really matters,
[51:30] SPEAKER: you can run a Docker host inside Proxmox
[51:33] SPEAKER: and get probably a much better outcome
[51:34] SPEAKER: than you would running inside of Open Media Vault
[51:36] SPEAKER: or definitely within TrueNAS,
[51:37] SPEAKER: 'cause Docker support and BSD is thin to non-existent.
[51:42] SPEAKER: (upbeat music)
[51:44] SPEAKER: So one of the things that's important
[51:45] SPEAKER: about this whole thing,
[51:46] SPEAKER: and this is something that most people I know
[51:48] SPEAKER: that have built their own TrueNAS machine
[51:50] SPEAKER: find out the hard way,
[51:51] SPEAKER: is you wanna know exactly what you're doing before you start.
[51:55] SPEAKER: This isn't a place to just jump in with two feet
[51:57] SPEAKER: and start installing stuff
[51:57] SPEAKER: and expect it to work out for you.
[52:00] SPEAKER: - I mean, you could.
[52:00] SPEAKER: I'm not speaking from experience or anything,
[52:03] SPEAKER: but you could give it a shot,
[52:05] SPEAKER: just prepare to make a lot of mistakes.
[52:06] SPEAKER: When you, the problem with that approach
[52:10] SPEAKER: is when you make mistakes,
[52:11] SPEAKER: you typically end up having to do re-installs.
[52:13] SPEAKER: So you wanna make sure you're doing that
[52:15] SPEAKER: before you have data.
[52:16] SPEAKER: The thing that I've found that helps more than anything,
[52:19] SPEAKER: 'cause the other big challenge with this
[52:20] SPEAKER: is you'll set something up
[52:21] SPEAKER: and then it runs perfectly for two years
[52:23] SPEAKER: and then something breaks
[52:24] SPEAKER: and you have to figure out what went wrong,
[52:26] SPEAKER: is that if you document your install process
[52:28] SPEAKER: as you're doing the install.
[52:29] SPEAKER: So here's the link to the how-to that I use
[52:31] SPEAKER: to figure out how to do this.
[52:33] SPEAKER: Here's the version of the software that I installed.
[52:35] SPEAKER: Here's the dependencies I had to install.
[52:37] SPEAKER: And I just copy and paste that stuff out of the terminal
[52:39] SPEAKER: or out of the plugin infrastructure or whatever I'm using
[52:42] SPEAKER: as I'm doing it and put into a Google doc.
[52:44] SPEAKER: And then I have that tree full of Google docs
[52:47] SPEAKER: for all the different things that are running on my NAS.
[52:50] SPEAKER: And when something inevitably does break,
[52:52] SPEAKER: I can open up the folder,
[52:54] SPEAKER: search for the thing that I'm looking for
[52:55] SPEAKER: and I get all the information about it
[52:58] SPEAKER: without having to remember what I did two years ago.
[53:00] SPEAKER: - I have saved PDF versions of some old blogs here and there
[53:03] SPEAKER: that seemed like they might go offline at some point
[53:05] SPEAKER: to make sure, absolutely sure.
[53:06] SPEAKER: 'Cause I was the only place on the internet
[53:08] SPEAKER: I could find an answer to the thing I was looking to do.
[53:10] SPEAKER: - Well, yeah, and a lot of the information
[53:12] SPEAKER: about how to do this stuff, especially on the TrueNAS side,
[53:14] SPEAKER: because the Linux installs
[53:17] SPEAKER: are typically pretty well documented.
[53:18] SPEAKER: The BSD installs are a little, sometimes a little kludgy.
[53:23] SPEAKER: I found that the way I would get something to install
[53:26] SPEAKER: was by following a path that somebody started
[53:29] SPEAKER: on a message board that linked to three different how-tos.
[53:33] SPEAKER: And it's like a data archeologist at that point,
[53:37] SPEAKER: trying to find the one truth
[53:39] SPEAKER: of how to install whatever weird library it is you need
[53:42] SPEAKER: for the thing that you're looking for.
[53:44] SPEAKER: So yeah, document the main install,
[53:46] SPEAKER: document the secondary install.
[53:47] SPEAKER: So if you're setting up custom containers,
[53:49] SPEAKER: if you're downloading Docker images,
[53:50] SPEAKER: save links to those Docker images,
[53:52] SPEAKER: or maybe just save the Docker images,
[53:53] SPEAKER: 'cause usually they're not that big.
[53:55] SPEAKER: - Actually, that's something I was gonna say here
[53:56] SPEAKER: is you can really avail yourself of a lot of the tools
[53:58] SPEAKER: that these NAS systems provide
[54:00] SPEAKER: to back up the actual work you've done.
[54:02] SPEAKER: So I assume Open Media Vault has similar equivalents.
[54:05] SPEAKER: Like TrueNAS, you can download a single file
[54:07] SPEAKER: that is just all of the settings
[54:08] SPEAKER: for your entire TrueNAS install.
[54:10] SPEAKER: So if you lose your TrueNAS boot volume,
[54:13] SPEAKER: all you have to do is install it fresh on another drive,
[54:16] SPEAKER: upload that file,
[54:17] SPEAKER: and it just restores literally everything you had.
[54:19] SPEAKER: - I was looking at a plugin
[54:20] SPEAKER: that saves the configuration stuff to Google Drive,
[54:22] SPEAKER: so it's just there, and you pull it down for the next one.
[54:24] SPEAKER: Yeah. - That's very cool.
[54:26] SPEAKER: - So documenting this stuff, hugely important.
[54:29] SPEAKER: Also, especially if you're installing on a thumb drive
[54:32] SPEAKER: or an SD card instead of an SSD,
[54:35] SPEAKER: picking the right SD card is, well, first off,
[54:39] SPEAKER: I generally advise against installing on thumb drives.
[54:41] SPEAKER: - Yes, if you can avoid it,
[54:42] SPEAKER: if you have the option to use like a real SSD,
[54:44] SPEAKER: I would say absolutely do that in a full-size machine.
[54:46] SPEAKER: But obviously, unlike Raspberry Pi,
[54:48] SPEAKER: generally, I mean, there are ways,
[54:50] SPEAKER: if you really wanna get into it, there are other ways,
[54:52] SPEAKER: but generally, you're limited to SD cards
[54:54] SPEAKER: or USB thumb drives,
[54:55] SPEAKER: and both of those are, as we've said, a little flaky.
[54:58] SPEAKER: - Well, the one exception, you can get SD cards now
[55:01] SPEAKER: that are rated for application use,
[55:03] SPEAKER: which means they're tuned for both performance
[55:06] SPEAKER: and wear leveling across the whole flash for writes.
[55:11] SPEAKER: Generally speaking, the SD cards
[55:13] SPEAKER: that are good for application use will have an A1 on them,
[55:17] SPEAKER: and they'll be class 10 writables,
[55:20] SPEAKER: which means that they run at a certain speed,
[55:21] SPEAKER: and they're tuned for wear leveling.
[55:24] SPEAKER: Often, they're like the ones that you buy for a Switch
[55:27] SPEAKER: or for a handheld device or something like that.
[55:31] SPEAKER: They don't cost a whole lot more than regular SD cards.
[55:34] SPEAKER: This seems like one of those things that,
[55:36] SPEAKER: I had never had flash devices fail
[55:38] SPEAKER: until I started using a thumb drive
[55:39] SPEAKER: as the boot drive for my free NAS box.
[55:43] SPEAKER: - Yeah, Raspberry Pis are also notorious
[55:45] SPEAKER: for killing SD cards.
[55:46] SPEAKER: - Yeah, if you are gonna use SD cards,
[55:48] SPEAKER: there will almost always be a point
[55:50] SPEAKER: along the installation of how to say,
[55:53] SPEAKER: hey, if you're doing this on SD cards,
[55:54] SPEAKER: turn off write log writing to the SD card
[55:58] SPEAKER: and write them onto your storage pool
[55:59] SPEAKER: or data drive or whatever.
[56:01] SPEAKER: Instead, 100% do that, or you'll be buying a new SD card
[56:04] SPEAKER: in six months or a year.
[56:06] SPEAKER: - Yes, Google something called log2ram
[56:08] SPEAKER: and follow the instructions.
[56:09] SPEAKER: - So yeah, and then the other thing
[56:10] SPEAKER: to always, always, always remember
[56:13] SPEAKER: is to think about your backup strategy,
[56:15] SPEAKER: 'cause you're saving important data in another place.
[56:19] SPEAKER: You wanna back up the stuff that isn't saved elsewhere.
[56:22] SPEAKER: If you're doing big media,
[56:23] SPEAKER: if you're ripping your Blu-ray collection
[56:25] SPEAKER: or something like that,
[56:26] SPEAKER: you're gonna spend an amount of energy,
[56:27] SPEAKER: both human energy and electricity doing that math
[56:31] SPEAKER: to shrink those files down.
[56:33] SPEAKER: You don't wanna waste that and have to do it again.
[56:35] SPEAKER: So think about your backup strategy for that stuff.
[56:38] SPEAKER: - Blu-rays can be re-ripped,
[56:39] SPEAKER: like that's just more of your time.
[56:41] SPEAKER: But if you're like me,
[56:42] SPEAKER: I've got some priceless family photos
[56:45] SPEAKER: and home movies backed up on my NAS
[56:47] SPEAKER: and stuff like that, you do not wanna lose that stuff.
[56:50] SPEAKER: And so just, I'll go through the catastrophic data loss
[56:53] SPEAKER: situations that I have that are very painful
[56:56] SPEAKER: and just make sure you always have a second copy,
[56:58] SPEAKER: physically distinct from even something like a NAS
[57:02] SPEAKER: that does have some resilience built into it.
[57:04] SPEAKER: - Well, and it's, you know,
[57:05] SPEAKER: just because you have the file stored on a NAS
[57:07] SPEAKER: doesn't mean you can't plug in a big, giant external drive
[57:10] SPEAKER: to that NAS and, you know,
[57:12] SPEAKER: create a snapshot that backs up to that
[57:14] SPEAKER: every once in a while or whatever
[57:15] SPEAKER: for your different data pools.
[57:16] SPEAKER: - That's a good point about backups.
[57:18] SPEAKER: They don't have to be as complex and reliable
[57:20] SPEAKER: as your main NAS, your main RAID, whatever.
[57:22] SPEAKER: Like they can be simpler or cheaper
[57:24] SPEAKER: because they themselves do not have to hold up.
[57:26] SPEAKER: It's just one of the two has to hold up, right?
[57:28] SPEAKER: - For me personally,
[57:29] SPEAKER: I'm much more interested in the backup
[57:31] SPEAKER: than I am in the redundancy.
[57:32] SPEAKER: If my server is down for a few days
[57:35] SPEAKER: because drive conks out and I don't have the Plex server up,
[57:38] SPEAKER: it's not that big a deal as long as I have a good backup.
[57:41] SPEAKER: If I don't have a good backup, then that's bad.
[57:42] SPEAKER: The other thing about backups is they don't count
[57:44] SPEAKER: until you test them and you know that they work.
[57:46] SPEAKER: So make sure that you're actually checking
[57:49] SPEAKER: to see that your data is backed up.
[57:50] SPEAKER: Don't just trust that the process is working.
[57:53] SPEAKER: - And that's the end of this episode, I guess, Brad.
[57:55] SPEAKER: - Yeah, we made it.
[57:56] SPEAKER: - Hey, congratulations.
[57:57] SPEAKER: As always, if you want to listen to this podcast,
[58:00] SPEAKER: you can find it at phosphod.content.town.
[58:02] SPEAKER: This is the last week it's gonna be in the TechPod feed.
[58:04] SPEAKER: So if you're listening to it in the TechPod feed
[58:06] SPEAKER: and you wanna hear it in two more weeks
[58:07] SPEAKER: when there's another episode,
[58:08] SPEAKER: you gotta go to the new URL and hit the subscribe button
[58:11] SPEAKER: or add us in your favorite podcast client.
[58:13] SPEAKER: We should be everywhere now in terms of podcast clients.
[58:16] SPEAKER: If you use a podcast client
[58:18] SPEAKER: and you don't find us when you search, please let us know.
[58:20] SPEAKER: And we will figure out what's going on.
[58:23] SPEAKER: But again, it's phosphod.content.town.
[58:26] SPEAKER: We're hiring, we're looking for both an editor
[58:28] SPEAKER: and a host/producer.
[58:30] SPEAKER: If you have either of those skillsets
[58:32] SPEAKER: and would like to talk about open source software
[58:34] SPEAKER: with Brad and me, the email address to send your CV to
[58:37] SPEAKER: is phosphod@content.town.
[58:40] SPEAKER: And as always, the phosphod is brought to you
[58:43] SPEAKER: by Google Open Source,
[58:45] SPEAKER: bringing all the value of open source to Google
[58:47] SPEAKER: and all the resources of Google to open source.
[58:50] SPEAKER: It's at opensource.google
[58:51] SPEAKER: if you wanna find out more information.
[58:54] SPEAKER: That'll do it for us this week, Brad.
[58:55] SPEAKER: As always, a pleasure.
[58:56] SPEAKER: - Thank you.
[58:57] SPEAKER: - We will be back next week or week after next.
[59:00] SPEAKER: - That's right.
[59:01] SPEAKER: - With more phosphod.
[59:01] SPEAKER: - Bi-weekly podcast.
[59:03] SPEAKER: Did you know that it can mean ether now?
[59:05] SPEAKER: - It's look, it's like irregardlessly.
[59:08] SPEAKER: Now that's actually a word, even though it's not a word.
[59:10] SPEAKER: - It's like right there in the dictionary.
[59:12] SPEAKER: You look up bi-weekly and it says twice a week
[59:14] SPEAKER: or every other week.
[59:15] SPEAKER: - Which one was it originally?
[59:16] SPEAKER: Are we using it badly?
[59:17] SPEAKER: - No, we're on it.
[59:19] SPEAKER: - Okay, phew.
[59:20] SPEAKER: (upbeat music)
[59:24] SPEAKER: - Well, that sure was a podcast.
[59:26] SPEAKER: - It was, I mean, there was intro music
[59:28] SPEAKER: and then outro music.
[59:29] SPEAKER: It's like bookends on your show.
[59:30] SPEAKER: - I like to think that we went on a little bit
[59:32] SPEAKER: of a journey together.
[59:33] SPEAKER: - We did.
[59:34] SPEAKER: - Yeah, we learned about electricity and replication.
[59:38] SPEAKER: We talked about jails.
[59:41] SPEAKER: - I have to tell you.
[59:42] SPEAKER: - Yeah.
[59:43] SPEAKER: - I had a bit of a heart-stopping moment when you said,
[59:46] SPEAKER: your NAS might be costing you $20 to $30 a month to run.
[59:50] SPEAKER: - Yeah.
[59:51] SPEAKER: - And I went, hmm, I mean, I knew it was probably bad,
[59:53] SPEAKER: but ouch.
[59:54] SPEAKER: - I mean, did you, have you done the math yet?
[59:56] SPEAKER: So it's, no. - No.
[59:58] SPEAKER: - You know what, the less I know, the better.
[1:00:00] SPEAKER: - You should get a volt, a power meter and plug it in.
[1:00:03] SPEAKER: - A kilowatt.
[1:00:04] SPEAKER: - Yeah, a kilowatt and plug it in between the NAS
[1:00:06] SPEAKER: and the wall.
[1:00:07] SPEAKER: And then you can, then that unknown entity
[1:00:10] SPEAKER: can become a known entity
[1:00:11] SPEAKER: and you can decide what to do about it.
[1:00:13] SPEAKER: - What if I just continued on in blissful ignorance?
[1:00:15] SPEAKER: - I mean, you could hang a solar panel
[1:00:16] SPEAKER: out of your back window.
[1:00:17] SPEAKER: It faces kind of the right direction.
[1:00:19] SPEAKER: So that'll do it for us this week.
[1:00:21] SPEAKER: As we said at the top of the show,
[1:00:22] SPEAKER: this is the last week that the FOSPOD
[1:00:24] SPEAKER: will be in your tech pod feed,
[1:00:25] SPEAKER: at least unless we do some sort of special crossover episode
[1:00:28] SPEAKER: or something like that.
[1:00:29] SPEAKER: But thank you all for bearing with us
[1:00:31] SPEAKER: as we launch the new show.
[1:00:31] SPEAKER: We hope you like it and please let us know what you think.
[1:00:34] SPEAKER: One way or the other, like positive and negative feedback,
[1:00:36] SPEAKER: both are great.
[1:00:38] SPEAKER: Our, yeah, ultimately we're making the show for you all.
[1:00:41] SPEAKER: So if people don't like it, then we like to know.
[1:00:46] SPEAKER: But now, Brad, we've reached the point in the show
[1:00:48] SPEAKER: where we thank our patrons.
[1:00:49] SPEAKER: - It's my favorite part of the show.
[1:00:50] SPEAKER: - It is a good part of the show.
[1:00:52] SPEAKER: So thank you, patrons.
[1:00:53] SPEAKER: - Thank you.
[1:00:54] SPEAKER: - And if you wanna find out how you can support the tech pod,
[1:00:56] SPEAKER: you can do that by going to tech pod,
[1:00:58] SPEAKER: sorry, patreon.com/techpod,
[1:01:01] SPEAKER: where you can join the ranks of our wonderful producers,
[1:01:03] SPEAKER: including our executive producer gear producers,
[1:01:05] SPEAKER: which who are Paddle Creek Games makers of Fractured Veil,
[1:01:09] SPEAKER: Andrew Slawski, Octo Thorpe, Bunny Crimes, Jacob Chappell,
[1:01:13] SPEAKER: Joel Krauska.
[1:01:14] SPEAKER: Okay, now this is getting out of hand.
[1:01:16] SPEAKER: - Uh-oh.
[1:01:17] SPEAKER: - Twinkle Twinkie has renamed themselves Bears Bears Bears.
[1:01:21] SPEAKER: - Oh boy.
[1:01:22] SPEAKER: - Bears.
[1:01:23] SPEAKER: - Bears is going to be very excited about this.
[1:01:25] SPEAKER: - Bears, look, bears are always excited.
[1:01:27] SPEAKER: But the person bears, who presumably is not an actual bear,
[1:01:31] SPEAKER: but maybe is, I don't know.
[1:01:32] SPEAKER: - I mean, you know, it's hard to say.
[1:01:34] SPEAKER: - David Allen and James Kamik,
[1:01:35] SPEAKER: thank you all to all, everybody who supports the podcast.
[1:01:38] SPEAKER: And as always, if you can't or don't want
[1:01:42] SPEAKER: to support the podcast, that's cool too.
[1:01:43] SPEAKER: Just leave a review or let people know about the show,
[1:01:46] SPEAKER: 'cause that's how we,
[1:01:47] SPEAKER: turns out that's how new podcasts find their audience, so.
[1:01:51] SPEAKER: - Word of mouth, they call it.
[1:01:53] SPEAKER: - Yes, it's the best way.
[1:01:54] SPEAKER: If somebody says, "Hey man, I really like this podcast,"
[1:01:56] SPEAKER: that is, turns out, is a really good way
[1:01:58] SPEAKER: to find out about podcasts that you might like,
[1:01:59] SPEAKER: 'cause presumably that person has good taste,
[1:02:01] SPEAKER: 'cause they're your friend, so there you go.
[1:02:03] SPEAKER: Science.
[1:02:04] SPEAKER: - All of the things and people that I like are good,
[1:02:06] SPEAKER: it turns out.
[1:02:07] SPEAKER: - Yeah, and none of the, I don't,
[1:02:08] SPEAKER: you know what I don't like about people that are bad?
[1:02:10] SPEAKER: Everything.
[1:02:11] SPEAKER: I don't know where we're going with this bit,
[1:02:12] SPEAKER: but that'll do it for us this week.
[1:02:14] SPEAKER: Back next week is a Q&A episode of the TechPod,
[1:02:17] SPEAKER: so if you have Qs, questions that you would like
[1:02:20] SPEAKER: to have turned into As, answers,
[1:02:22] SPEAKER: you can send them to techpod@content.town,
[1:02:25] SPEAKER: or you can post them in the Discord if you are a patron,
[1:02:28] SPEAKER: you have access to that thing.
[1:02:30] SPEAKER: You can get it in there and you can go
[1:02:31] SPEAKER: into the questions seeking answers channel
[1:02:32] SPEAKER: and you can just write something,
[1:02:34] SPEAKER: it will disappear into the ether and Brad and I will see it
[1:02:37] SPEAKER: and potentially turn it into an A next week.
[1:02:39] SPEAKER: See y'all then, thanks for listening everybody.
