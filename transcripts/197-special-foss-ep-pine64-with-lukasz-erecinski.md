---
episode: 197
title: Special FOSS Ep: Pine64 With Lukasz Erecinski
date: 2023-06-18
guests: none
duration: 1:03:18
---

[00:00] SPEAKER: - Hey everybody.
[00:01] SPEAKER: - Hi, wait, I'm not everybody, but hi.
[00:04] SPEAKER: - Well, you're part of the subset that is everybody.
[00:06] SPEAKER: - I'm somebody.
[00:08] SPEAKER: - This week we have something special planned for you all.
[00:10] SPEAKER: We had a, this is an episode that wouldn't have actually
[00:13] SPEAKER: existed without the tech pod as it is,
[00:16] SPEAKER: but it's specifically the tech pod discord.
[00:18] SPEAKER: We have a representative from the Pine 64 group
[00:24] SPEAKER: coming on the show to talk about their products
[00:26] SPEAKER: and their open source stuff and all that.
[00:28] SPEAKER: And it's, we thought it'd be an interesting thing
[00:30] SPEAKER: to have on both feeds, honestly.
[00:32] SPEAKER: It's on the FOSBOD feed, it's on the tech pod feed.
[00:34] SPEAKER: We apologize for the double dip this week.
[00:36] SPEAKER: - Yeah, you're traveling.
[00:39] SPEAKER: - I'm going to, I've been dealing with some family stuff
[00:41] SPEAKER: and yeah, and I'm not, it was a good time
[00:45] SPEAKER: to have a FOSBOD episode.
[00:47] SPEAKER: Also, Brad, you're in the middle of the launch
[00:50] SPEAKER: of a million games or maybe the launch of eight games
[00:52] SPEAKER: as the case may be.
[00:53] SPEAKER: - Yes.
[00:54] SPEAKER: - So it's been a lot of talking for both of us this week.
[00:57] SPEAKER: - Games and not E3 streams.
[01:00] SPEAKER: Like they would be E3 streams if E3 hadn't died.
[01:03] SPEAKER: - Nope, there's no E3, just streams.
[01:05] SPEAKER: But yeah, we'll be back next week with a regular episode
[01:08] SPEAKER: and thank you all for listening
[01:11] SPEAKER: and stay tuned till the end of the show
[01:12] SPEAKER: for the patron thank yous.
[01:14] SPEAKER: (upbeat music)
[01:21] SPEAKER: I think one of my favorite categories of hardware
[01:25] SPEAKER: is the thing that you hear about and you're like,
[01:28] SPEAKER: wow, that sounds too good to be true, right?
[01:30] SPEAKER: - Yeah, it's like the thing you would love to get
[01:32] SPEAKER: on Christmas morning.
[01:34] SPEAKER: - Yeah, or like, hey, here's a CPU from Intel
[01:37] SPEAKER: or AMD that you can overclock 50% over its stock clocks
[01:42] SPEAKER: or some sort of device that you're like,
[01:47] SPEAKER: wow, that is not just incredible,
[01:49] SPEAKER: it's better than anything I have,
[01:50] SPEAKER: but also it's very, very inexpensive.
[01:52] SPEAKER: - Yes, it's the deep bang for the buck category of product.
[01:56] SPEAKER: - Exactly, and there's one of those that came up for us
[01:59] SPEAKER: fairly recently in the tech pod discord.
[02:01] SPEAKER: It initially sounded like, and I actually say this,
[02:03] SPEAKER: I actually say this in the interview,
[02:05] SPEAKER: it sounded like an internet of shit thing, right?
[02:07] SPEAKER: Like some unnecessarily connected device
[02:10] SPEAKER: with firmware and all sorts of nonsense
[02:12] SPEAKER: when you've had an analog thing that's been built
[02:15] SPEAKER: for the same way since the '50s in your house already.
[02:20] SPEAKER: And then I got it, and I was like, this is incredible.
[02:23] SPEAKER: This is an incredible device.
[02:25] SPEAKER: It's changed the way I do that kind of work,
[02:27] SPEAKER: and it costs like $25.
[02:29] SPEAKER: We're talking about the PineSil, in case you didn't know.
[02:31] SPEAKER: It's an open source RISC-V powered soldering iron
[02:36] SPEAKER: that is powered off of a USB-C plug,
[02:38] SPEAKER: or you can use a barrel connector if you want.
[02:40] SPEAKER: You can plug it into a lot of USB power supplies.
[02:43] SPEAKER: It has specific requirements,
[02:45] SPEAKER: but they're still readily available.
[02:48] SPEAKER: And it's easily the best soldering iron I've ever owned.
[02:51] SPEAKER: - I follow the exact same trajectory you did.
[02:53] SPEAKER: The first time you told me about it,
[02:54] SPEAKER: I was like, why in God's name
[02:55] SPEAKER: do we need our soldering irons to be smart now?
[02:57] SPEAKER: And now that I bought one and used it, I totally get it.
[03:00] SPEAKER: And now we are following that trail
[03:03] SPEAKER: all the way back to the source
[03:04] SPEAKER: and talking to the company that makes both that
[03:06] SPEAKER: and a bunch of other products
[03:07] SPEAKER: that also follow that same philosophy.
[03:10] SPEAKER: (upbeat music)
[03:18] SPEAKER: (upbeat music)
[03:28] SPEAKER: - Welcome to the FOSPOD.
[03:30] SPEAKER: I'm Will.
[03:31] SPEAKER: - I'm Brad.
[03:32] SPEAKER: - This week's FOSPOD is brought to you by Google Open Source.
[03:34] SPEAKER: They bring all of the value of open source to Google
[03:36] SPEAKER: and all of the resources of Google to open source.
[03:39] SPEAKER: Brad, I'm really excited to have this conversation
[03:42] SPEAKER: 'cause I didn't fully appreciate how broad
[03:44] SPEAKER: the range of products that Pine64 creates.
[03:49] SPEAKER: I didn't know about their...
[03:50] SPEAKER: Like coming into this interview
[03:51] SPEAKER: where we started doing the research,
[03:52] SPEAKER: I didn't know anything about the origins of the company,
[03:55] SPEAKER: what they've been doing,
[03:56] SPEAKER: what they're looking forward in the future,
[03:58] SPEAKER: what they do off as kind of weird side projects.
[04:00] SPEAKER: It's kind of all side projects.
[04:02] SPEAKER: It's an interesting company.
[04:03] SPEAKER: It's an interesting application of open source.
[04:06] SPEAKER: They are, I think, probably a more open hardware company
[04:11] SPEAKER: than any of the other hardware folks we've talked to.
[04:13] SPEAKER: And we're gonna talk to Łukasz Aronczynski,
[04:16] SPEAKER: who's the senior advisor at the Pine64 project,
[04:18] SPEAKER: about the whole thing right now.
[04:20] SPEAKER: Before we get any further,
[04:22] SPEAKER: can you kind of give us the rundown
[04:24] SPEAKER: of the breadth of the offering
[04:26] SPEAKER: in all the different places that Pine64 has their hands in?
[04:32] SPEAKER: - Yes.
[04:32] SPEAKER: And we never thought we'd be making a soldering iron.
[04:35] SPEAKER: It was supposed to be a complete side project, but yes.
[04:38] SPEAKER: So soldering iron, a smartwatch, amazing piece of kit,
[04:43] SPEAKER: which we're really proud of.
[04:45] SPEAKER: Two smartphones, the PinePhone and PinePhone Pro,
[04:48] SPEAKER: currently a laptop, PineBook Pro.
[04:51] SPEAKER: Tablets, which includes an e-paper reader,
[04:56] SPEAKER: which isn't available to the public per se,
[04:58] SPEAKER: but if you're a developer, you can get a unit to develop on.
[05:03] SPEAKER: Two tablets, one of which is the first tablet
[05:05] SPEAKER: with a RISC-V SoC in the world, at least to my knowledge,
[05:10] SPEAKER: as well as a number of maker hardware,
[05:13] SPEAKER: including quite specialized power supply units
[05:19] SPEAKER: and accessories for the phone,
[05:22] SPEAKER: such as the specialized back cases,
[05:24] SPEAKER: which allow the phone's functionality to be expanded,
[05:29] SPEAKER: as well as obviously a whole wide range
[05:31] SPEAKER: of single board computers.
[05:32] SPEAKER: - Yeah, I was gonna say the single board computers
[05:34] SPEAKER: are everything from the standard single board computers
[05:38] SPEAKER: that we all know and love, all the way up to things
[05:41] SPEAKER: that are IP cameras that are powered over ethernet
[05:44] SPEAKER: that you can jam into whatever case you want.
[05:47] SPEAKER: It's a fascinating range of projects.
[05:49] SPEAKER: How did you get involved?
[05:50] SPEAKER: How'd you get started with the project?
[05:51] SPEAKER: How'd you get involved?
[05:53] SPEAKER: - I started in 2015, right after the Kickstarter.
[05:59] SPEAKER: So I wasn't a part of the Kickstarter campaign.
[06:01] SPEAKER: I was brought in after the Kickstarter
[06:04] SPEAKER: to sort of find the way forward for the project
[06:07] SPEAKER: and figure out what we're doing next.
[06:09] SPEAKER: - This was for the single board computer,
[06:10] SPEAKER: the first single board computer?
[06:11] SPEAKER: - Correct, so although the Pine64 Model A
[06:17] SPEAKER: was commercially a significant success,
[06:20] SPEAKER: from a marketing and community perspective,
[06:23] SPEAKER: it didn't go particularly well.
[06:26] SPEAKER: So at that time, there was a lot of sort of soul searching
[06:29] SPEAKER: within the project, trying to figure out
[06:32] SPEAKER: what's the next step, if there is a next step actually
[06:35] SPEAKER: for a short period of time.
[06:37] SPEAKER: And I was brought on board, the founder, TLM,
[06:41] SPEAKER: he flew into London where I lived at a time.
[06:43] SPEAKER: He met me for a pint and he said, "So what do you think?
[06:47] SPEAKER: "Do you think we can build a community, run this thing,
[06:50] SPEAKER: "and take it forward?"
[06:52] SPEAKER: And I said, "Yeah, I think it's doable.
[06:54] SPEAKER: "Nothing is lost at this point in time.
[06:56] SPEAKER: "We can totally give it a go."
[06:58] SPEAKER: And we decided to pursue a number of other products.
[07:03] SPEAKER: - How was that first board a failure?
[07:05] SPEAKER: I just had a curiosity from a community standpoint.
[07:07] SPEAKER: - Right, so the first point of failure was
[07:10] SPEAKER: that although TL is an excellent engineer
[07:15] SPEAKER: and a very well established sort of businessman,
[07:18] SPEAKER: an entrepreneur, he at the time had very little
[07:22] SPEAKER: marketing capabilities of his own.
[07:24] SPEAKER: So what they did, him and the co-founder,
[07:28] SPEAKER: was they basically hired a marketing company
[07:33] SPEAKER: to run the Kickstarter.
[07:34] SPEAKER: And probably he wasn't even fully aware
[07:38] SPEAKER: of where they're gonna take this.
[07:40] SPEAKER: And instead of the vision, which was always there,
[07:43] SPEAKER: to build a piece of hardware and build a software community
[07:45] SPEAKER: around it, bringing developers on board,
[07:49] SPEAKER: what happened was that the advertisement went out
[07:53] SPEAKER: as an end-user finished product.
[07:55] SPEAKER: So that brought in, in a sense, the wrong crowd initially
[07:59] SPEAKER: of people who experienced this sort of,
[08:00] SPEAKER: a Raspberry Pi sort of experience out of the box,
[08:03] SPEAKER: which certainly was not the case at the time.
[08:06] SPEAKER: - And the idea of that first board was to build a 60,
[08:08] SPEAKER: at the time Raspberry Pis were only 32-bit ARM computers,
[08:11] SPEAKER: and the idea was to build a 64-bit single board computer
[08:15] SPEAKER: that was maybe more open or just more community-driven
[08:19] SPEAKER: at the time?
[08:20] SPEAKER: - More community-driven, aimed at a different,
[08:24] SPEAKER: so the idea was to have it aimed at a different
[08:26] SPEAKER: sort of demographic, to have it aimed at developers
[08:29] SPEAKER: who would really work on the 64-bit architecture on ARM,
[08:32] SPEAKER: which wasn't really that well established at the time.
[08:35] SPEAKER: - Ah, and the idea is if there's hardware,
[08:37] SPEAKER: then you can kickstart that community,
[08:39] SPEAKER: and then you got a bunch of consumers in
[08:41] SPEAKER: who just wanted to run Plex and emulators
[08:44] SPEAKER: on their A64 boards and were disappointed
[08:47] SPEAKER: because it was a little wrong still.
[08:49] SPEAKER: - This is absolutely what happened in a nutshell, yes.
[08:52] SPEAKER: So, you know, soon after the kickstart,
[08:54] SPEAKER: there was definitely, you know, a sense of,
[08:56] SPEAKER: so what do we do now, right?
[08:58] SPEAKER: Because the product is good, the board was good,
[09:00] SPEAKER: the developers who received it were quite happy.
[09:03] SPEAKER: The issue where all the other people
[09:05] SPEAKER: who now had a negative experience
[09:07] SPEAKER: because they couldn't do all the things
[09:08] SPEAKER: that they expected to be able to do with it,
[09:11] SPEAKER: and then they felt, you know, lied to.
[09:14] SPEAKER: So when I was brought in, you know,
[09:18] SPEAKER: I was there as a sort of liaison between the community,
[09:22] SPEAKER: that being both the development community
[09:24] SPEAKER: as well as regular end users and the pine store,
[09:27] SPEAKER: the company, to sort of figure out
[09:31] SPEAKER: where we're going collectively from there on.
[09:35] SPEAKER: - If we could step back to the period
[09:37] SPEAKER: before the Kickstarter for just a minute,
[09:39] SPEAKER: I know TL, I was surprised to find out
[09:42] SPEAKER: TL was responsible for the popcorn hour,
[09:44] SPEAKER: which is a name I haven't seen in a long time,
[09:45] SPEAKER: but I'm curious if his experience with that product
[09:50] SPEAKER: informed or kind of led to him veering in this direction,
[09:53] SPEAKER: because I never owned one myself,
[09:55] SPEAKER: but it was one of the first really big kind of phenomenons
[09:59] SPEAKER: in the set top kind of media player space.
[10:03] SPEAKER: You know, like early Apple TV, Roku, that type of stuff.
[10:05] SPEAKER: Like I remember like anecdotally
[10:07] SPEAKER: just seeing people all over the place
[10:09] SPEAKER: super passionate about their popcorn hours.
[10:11] SPEAKER: And I'm curious, A, was there anything like open source
[10:14] SPEAKER: and community oriented about the popcorn hour
[10:16] SPEAKER: and B, you know, is that kind of what led
[10:18] SPEAKER: to TL going in this direction?
[10:21] SPEAKER: - Yeah, for sure it did.
[10:22] SPEAKER: I mean, I don't know the story in its entirety.
[10:25] SPEAKER: You would have to ask him about this, I suppose,
[10:27] SPEAKER: but it's my understanding that what happened
[10:30] SPEAKER: was that obviously when he was doing
[10:31] SPEAKER: the popcorn hour video audio players at the time,
[10:35] SPEAKER: there were a number of them
[10:37] SPEAKER: which gathered a significant following
[10:40] SPEAKER: and among those who participated were Linux developers
[10:44] SPEAKER: and open source developers.
[10:46] SPEAKER: And they brought open software to these SOCs.
[10:50] SPEAKER: I believe these were quite specialized sigma SOCs
[10:53] SPEAKER: used in these devices.
[10:55] SPEAKER: And I know for a fact that TL saw that a product
[11:00] SPEAKER: which exists, which is in a sense a finished product
[11:04] SPEAKER: on launch, those were very much end user devices
[11:06] SPEAKER: from the get-go.
[11:07] SPEAKER: These weren't, these were sort of a different,
[11:11] SPEAKER: they were aimed at a different audience
[11:12] SPEAKER: at audio files specifically.
[11:15] SPEAKER: He saw that a device can be made better or improved upon
[11:19] SPEAKER: by having open source community members kind of work on it.
[11:23] SPEAKER: And so in this way, the company opened up
[11:27] SPEAKER: a little bit as well, because they saw, you know,
[11:30] SPEAKER: how this contribution is ultimately also profitable to them,
[11:35] SPEAKER: which isn't completely obvious if you're running
[11:38] SPEAKER: this sort of company, you know, it may seem obvious to us now
[11:41] SPEAKER: especially from where I'm saying, but back then,
[11:44] SPEAKER: especially back then in Asia, this wasn't necessarily
[11:47] SPEAKER: a very obvious decision and choice to make, right?
[11:50] SPEAKER: So they went to sigma, they said, you know,
[11:52] SPEAKER: how much of this information can we disclose?
[11:54] SPEAKER: How much can we provide it to community members?
[11:57] SPEAKER: And, you know, ultimately this certainly this experience,
[12:00] SPEAKER: this first encounter with open source
[12:01] SPEAKER: and how it can make an existing product better
[12:04] SPEAKER: and extend this lifetime has certainly given him
[12:08] SPEAKER: a sort of an idea to explore the open source world further.
[12:12] SPEAKER: - It's hard to remember now, but at that time,
[12:14] SPEAKER: the other people that were building hardware
[12:16] SPEAKER: that was based on Linux were actively working
[12:19] SPEAKER: against the communities in a lot of cases,
[12:20] SPEAKER: like the router manufacturers and those folks were just,
[12:24] SPEAKER: they weren't breaking the rules of the license,
[12:27] SPEAKER: but they were definitely weren't making it easy
[12:29] SPEAKER: to participate for end users.
[12:31] SPEAKER: And that was, I think, the exciting thing to me
[12:33] SPEAKER: about Popcorn Hour, the community first approach
[12:35] SPEAKER: is something that we've talked to a bunch of projects
[12:37] SPEAKER: at this time, and there's a handful of communities
[12:39] SPEAKER: that actually work, that operate that way.
[12:42] SPEAKER: It's interesting, like, does that go all the way down
[12:44] SPEAKER: to like product decisions and what direction
[12:47] SPEAKER: you're gonna go next or like where does the line
[12:49] SPEAKER: between what you all wanna do internally
[12:52] SPEAKER: and what the community wants to do,
[12:53] SPEAKER: how do you decide where that line is, I guess,
[12:55] SPEAKER: is the first place to start?
[12:57] SPEAKER: - Excellent question, so this has shifted over the years.
[13:00] SPEAKER: Right now, the project is very large.
[13:04] SPEAKER: Initially, when we started and when I kind of got
[13:06] SPEAKER: into the position of community manager
[13:09] SPEAKER: and brought in people from established projects on board,
[13:11] SPEAKER: as well as community developers and kind of huddled them
[13:14] SPEAKER: together and said, so what do you guys wanna do next?
[13:16] SPEAKER: And what we used to do was we built a piece of hardware,
[13:20] SPEAKER: we sent it out to the developers,
[13:22] SPEAKER: they gave direct feedback, they told us what they want.
[13:26] SPEAKER: This came back to us, and then when we had something
[13:30] SPEAKER: that would resemble an early prototype,
[13:32] SPEAKER: we would share it with the community
[13:34] SPEAKER: and hear the community's feedback, so like end users'
[13:36] SPEAKER: feedback, and this worked for a time.
[13:39] SPEAKER: In terms of scale, it becomes quite difficult
[13:43] SPEAKER: when you have a lot of people who wanna chip in
[13:47] SPEAKER: and have their say, and then, you know,
[13:50] SPEAKER: when you ask a question, when you ask people a question,
[13:53] SPEAKER: you have to be sure that you wanna hear the answer.
[13:55] SPEAKER: So like, last thing which we did where we involved
[13:59] SPEAKER: the entire community was the keyboard for the PinePhone
[14:02] SPEAKER: and the PinePhone Pro, and that made us realize
[14:08] SPEAKER: how difficult it is sometime now with the size
[14:10] SPEAKER: of the project to open it up to discussion,
[14:12] SPEAKER: especially something as subjective as a keyboard layout
[14:15] SPEAKER: and all the things that people wanna see in such a thing.
[14:18] SPEAKER: It becomes quite overwhelming when you get so much feedback
[14:21] SPEAKER: and you have to figure out, right now we asked,
[14:24] SPEAKER: so now we are in this position where if we wouldn't ask,
[14:27] SPEAKER: we could have gone and done something
[14:29] SPEAKER: that we thought was right, but now that we asked,
[14:31] SPEAKER: we have to incorporate some of this feedback
[14:34] SPEAKER: and the best of it, so we felt obliged to do so,
[14:37] SPEAKER: but this has ultimately delayed the keyboard project
[14:40] SPEAKER: by, I don't remember, by nearly a year.
[14:44] SPEAKER: So, but in principle, what we do right now internally
[14:47] SPEAKER: is we come up with an idea of what we wanna do.
[14:50] SPEAKER: So let's say it's another phone,
[14:52] SPEAKER: whatever it is that we wanna do.
[14:54] SPEAKER: So we have an idea for a phone, and then we look around
[14:57] SPEAKER: and see what components are available to us
[14:59] SPEAKER: at a reasonable price and what we can be sure
[15:04] SPEAKER: is gonna be available to us three years down the road as well
[15:08] SPEAKER: and then we establish, we make contact with the vendors
[15:11] SPEAKER: and stuff like that.
[15:12] SPEAKER: We usually, we have boots on the ground in Shenzhen,
[15:15] SPEAKER: so we have people in Shenzhen, so it's, you know,
[15:18] SPEAKER: we like to have direct contact with the vendors
[15:21] SPEAKER: to talk to them and have a proper understanding
[15:24] SPEAKER: of how their supply chain looks like.
[15:27] SPEAKER: So yeah, so we figure out what we wanna do,
[15:30] SPEAKER: what we can base it upon.
[15:33] SPEAKER: Only then do we bring in developers
[15:35] SPEAKER: from within the closest circle to talk about it, right?
[15:39] SPEAKER: We don't open everything up to the choice
[15:42] SPEAKER: of even the closest community because if you ask,
[15:45] SPEAKER: especially the very techie people, you know,
[15:47] SPEAKER: what would you like to see in like in your next phone,
[15:49] SPEAKER: you're gonna hear that they want really high-end stuff
[15:52] SPEAKER: and you know, all of these sort of things,
[15:54] SPEAKER: but ultimately nobody's gonna buy it.
[15:56] SPEAKER: So we make some of the business decision quite early
[15:59] SPEAKER: about what makes sense for us to make,
[16:01] SPEAKER: but then, you know, choice of cameras, choice of LCD panel,
[16:06] SPEAKER: choice of modem even, and stuff like that,
[16:08] SPEAKER: this is largely up to debate with the closest of the closest
[16:11] SPEAKER: and then we open it further and further and further
[16:13] SPEAKER: and then we can present it to the community broadly.
[16:16] SPEAKER: - It's interesting because, you know,
[16:18] SPEAKER: on the software projects that are more community-driven,
[16:21] SPEAKER: it's a feature choice, right?
[16:22] SPEAKER: It's like, hey, do we add support for this file format
[16:25] SPEAKER: or something like that?
[16:26] SPEAKER: For you all, your choices are so tied
[16:30] SPEAKER: to what hardware is available and what fits into the,
[16:33] SPEAKER: like, you know, stuff like thermal budgets
[16:35] SPEAKER: and like, it's incredibly, to me,
[16:38] SPEAKER: it's the thing that makes this project so neat
[16:39] SPEAKER: is that there's any community involvement at all
[16:43] SPEAKER: in the hardware decisions and that side of it
[16:46] SPEAKER: and you're not just saying, hey,
[16:47] SPEAKER: here's the hardware platform we built this time,
[16:49] SPEAKER: which is essentially what Raspberry Pi does, right?
[16:51] SPEAKER: They're like, hey, here's what we built.
[16:53] SPEAKER: See what you all can, let's see what you all can do with it
[16:55] SPEAKER: and then we'll figure out what you've done
[16:57] SPEAKER: and integrate that stuff into the next rev.
[16:59] SPEAKER: - Yeah, I kind of, I want to read a quote real quick
[17:02] SPEAKER: from your philosophy page.
[17:04] SPEAKER: I mean, you've touched on this pretty directly already,
[17:06] SPEAKER: but still just to see it stated kind of dogmatically
[17:08] SPEAKER: is just really unique for this kind of project.
[17:11] SPEAKER: We usually announce what we're working on
[17:12] SPEAKER: well ahead of the shipping date
[17:13] SPEAKER: many months before a device is released
[17:15] SPEAKER: so that you have plenty of time to request product features,
[17:18] SPEAKER: suggest changes, ask for and make changes
[17:20] SPEAKER: to documentation, et cetera,
[17:21] SPEAKER: before the first iteration of the device
[17:23] SPEAKER: rolls off the factory line.
[17:24] SPEAKER: So I'm curious, is this the type of thing
[17:27] SPEAKER: that you think maybe is only possible in recent years
[17:30] SPEAKER: now that we're in this age of kind of rapid prototyping
[17:33] SPEAKER: and like kind of affordable,
[17:35] SPEAKER: smaller batch hardware manufacturing?
[17:37] SPEAKER: I mean, is this the type of thing that it seems like
[17:40] SPEAKER: would have been impossible like a decade ago?
[17:45] SPEAKER: - Yes, certainly.
[17:46] SPEAKER: I mean, for sure this has a lot to do with it.
[17:49] SPEAKER: The other thing, which, you know,
[17:51] SPEAKER: we touched on TL, the founder of Pine64,
[17:55] SPEAKER: a part of the reason why we are able to do this
[17:59] SPEAKER: is because we have the abilities to turn around products
[18:03] SPEAKER: very quickly in a prototype fashion
[18:05] SPEAKER: in Shenzhen in China, ultimately, right?
[18:09] SPEAKER: So we can have three or four or five prototypes
[18:12] SPEAKER: or something built with very different components
[18:16] SPEAKER: inside them.
[18:17] SPEAKER: Now these are outrageously expensive
[18:19] SPEAKER: if you're building one of something.
[18:20] SPEAKER: So, you know, it's sometimes it's good to build, you know,
[18:23] SPEAKER: three or four different options of potential hardware.
[18:27] SPEAKER: And especially if it's quite modular,
[18:29] SPEAKER: then developers can basically just, you know,
[18:31] SPEAKER: mail it between each other or FedEx it between each other
[18:34] SPEAKER: and kind of take a look at the different versions
[18:37] SPEAKER: and options which they have.
[18:39] SPEAKER: So yes, it has become possible probably
[18:42] SPEAKER: in the past five years, but I don't think it is possible to,
[18:47] SPEAKER: especially when you have something as complex as a phone,
[18:51] SPEAKER: I don't think, you know, rapid prototyping helps much here.
[18:53] SPEAKER: You have to have access to the actual vendors
[18:57] SPEAKER: and people who know that there is a reason
[19:01] SPEAKER: why you wanna build one or five of something, right?
[19:04] SPEAKER: Because they know that you're gonna come back
[19:06] SPEAKER: and have a hundred, a thousand, 10,000
[19:08] SPEAKER: or however many hundred thousand units later, yeah.
[19:12] SPEAKER: - The relationships with the people
[19:13] SPEAKER: that run the factories, it turns out,
[19:15] SPEAKER: I guess in order to get them to make one of them for you,
[19:17] SPEAKER: you have to, they have to know you're gonna come back
[19:19] SPEAKER: and make it worth their time later.
[19:20] SPEAKER: - Yes, yes, because even if a prototype costs,
[19:23] SPEAKER: say a 10 fold or 20 fold of the finished product,
[19:27] SPEAKER: ultimately you're taking up a lot of time
[19:30] SPEAKER: also of their staff and engineers.
[19:32] SPEAKER: So it's, if you are not somebody who has a track record,
[19:38] SPEAKER: especially these days after the pandemic,
[19:41] SPEAKER: when a lot of companies, a lot of factories in China
[19:44] SPEAKER: have gone out of business during the pandemic, right?
[19:47] SPEAKER: They have established clients.
[19:51] SPEAKER: Many of them are not super keen
[19:53] SPEAKER: on taking on experimental hardware.
[19:57] SPEAKER: - Well, yeah, new risk.
[19:58] SPEAKER: It's a risk averse business to start with, right?
[20:01] SPEAKER: How many people work for Pine64?
[20:04] SPEAKER: Like how many people are involved with the,
[20:06] SPEAKER: are part of the full-time business now?
[20:08] SPEAKER: - There's a lot.
[20:10] SPEAKER: In the United States, you have three people, including TL.
[20:14] SPEAKER: Here in Europe, you have two people, one me being included.
[20:18] SPEAKER: But then Malaysia is where there's R&D
[20:23] SPEAKER: and there's quite a few people working there.
[20:26] SPEAKER: Hong Kong is where the main office is currently.
[20:28] SPEAKER: There's quite a few people working there.
[20:30] SPEAKER: That's where you have support, dispatch and stuff like that.
[20:34] SPEAKER: And then there's contractors in Shenzhen,
[20:36] SPEAKER: who including like scouts and people
[20:39] SPEAKER: who we have a long running relationship for,
[20:42] SPEAKER: like contact with vendors and other distributions,
[20:48] SPEAKER: distributors and stuff.
[20:49] SPEAKER: - And those folks find distributors in factories
[20:52] SPEAKER: and like logistics stuff for shipping finished project
[20:55] SPEAKER: and stuff like that?
[20:56] SPEAKER: - Correct, yes, that's exactly it.
[20:58] SPEAKER: So they are contracted,
[21:01] SPEAKER: but many of them have been with us for many years.
[21:04] SPEAKER: - Is there somebody in that decision chain
[21:07] SPEAKER: who is like the go or no go,
[21:10] SPEAKER: somebody has to make the decision finally,
[21:13] SPEAKER: we're not getting consensus from the community
[21:15] SPEAKER: or the internal teams.
[21:16] SPEAKER: Are there hierarchies for, we're the hardware side,
[21:20] SPEAKER: we're the software side and stuff like that?
[21:24] SPEAKER: - Yes, there is a person who gets to say,
[21:27] SPEAKER: yes, we're doing it or no, we're not doing it.
[21:29] SPEAKER: And that is definitely TL.
[21:31] SPEAKER: Then there's people like myself and the current community,
[21:36] SPEAKER: matter crowds who get to have a significant say
[21:39] SPEAKER: in whether something is going forward
[21:41] SPEAKER: and pitch in ideas and review stuff as it's coming in
[21:46] SPEAKER: and see if it makes any sense to continue
[21:49] SPEAKER: with a particular project.
[21:51] SPEAKER: But this is quite fluid.
[21:54] SPEAKER: There have been a few instances even within the recent year
[21:58] SPEAKER: where two or three trusted community developers
[22:02] SPEAKER: basically overruled what we wanted to do internally
[22:05] SPEAKER: with relationship to the hardware.
[22:08] SPEAKER: Something which required us to pay a significant amount
[22:13] SPEAKER: of extra money for a feature.
[22:16] SPEAKER: But ultimately that feature found itself into the product.
[22:18] SPEAKER: And so, yes, there is a cutoff point,
[22:22] SPEAKER: which is TL saying, we cannot do this,
[22:25] SPEAKER: it's impossible to do this.
[22:27] SPEAKER: But there's always a debate.
[22:28] SPEAKER: Sometimes these debate get quite heated
[22:31] SPEAKER: and sometimes they leak into the public as well.
[22:35] SPEAKER: And these are the sort of things that happen here.
[22:38] SPEAKER: - Boot ROMs on phones and things like that.
[22:40] SPEAKER: - Yes.
[22:41] SPEAKER: - That's how you know you've arrived as an open project
[22:43] SPEAKER: when drama is spilling out into blog posts
[22:45] SPEAKER: as people take sides.
[22:48] SPEAKER: - Yes.
[22:49] SPEAKER: For the record, Martin, Bram and I met at Fasten this year
[22:52] SPEAKER: and we had a beer and everything's fine.
[22:55] SPEAKER: So to anyone listening, we're all good.
[22:58] SPEAKER: - I was gonna say, so for people who aren't super dialed
[23:01] SPEAKER: into the scene on this particular...
[23:04] SPEAKER: This was really low key scene drama for Linux projects
[23:08] SPEAKER: in our experience.
[23:09] SPEAKER: - Very polite, extremely polite.
[23:11] SPEAKER: - And the concern was about boot loaders
[23:14] SPEAKER: and how it would apply to alternate operating systems
[23:16] SPEAKER: on the PinePhone.
[23:18] SPEAKER: I realize now as we're talking about the PinePhone,
[23:20] SPEAKER: we haven't actually talked about the kind of scope
[23:22] SPEAKER: and scale of the product offering that Pine64 is doing yet.
[23:26] SPEAKER: - Yeah, the range, the breadth of the product offering
[23:29] SPEAKER: is kind of astonishing to me.
[23:30] SPEAKER: I mean, like you said, the initial Kickstarter
[23:32] SPEAKER: was for a small board computer.
[23:34] SPEAKER: You've got products like for example,
[23:36] SPEAKER: your desktop power, USB power supply.
[23:38] SPEAKER: I love the kind of...
[23:40] SPEAKER: There's a bit of an industrial look to it.
[23:41] SPEAKER: You know, it's got a screen that literally tells you
[23:44] SPEAKER: the voltage and amperage of all USB ports on there.
[23:46] SPEAKER: It looks like something that would have been on like,
[23:48] SPEAKER: my grandfather was a machinist
[23:50] SPEAKER: and it was like the kind of equipment he might use, you know.
[23:53] SPEAKER: But also now you've shifted toward,
[23:56] SPEAKER: you've got a smartwatch, you've got earbuds on the way.
[23:59] SPEAKER: More sort of like packaged consumer oriented stuff
[24:02] SPEAKER: that obviously still open firmware, still hackable
[24:05] SPEAKER: and stuff you can tinker with,
[24:07] SPEAKER: but more everyday sort of carry around items.
[24:11] SPEAKER: Was that shift toward things like earbuds and smartwatches?
[24:13] SPEAKER: Was that entirely organically driven by the community
[24:16] SPEAKER: or was that ever in the initial roadmap
[24:18] SPEAKER: that like we're gonna start with more open
[24:20] SPEAKER: and then go to more consumer?
[24:22] SPEAKER: - No, I'll be completely honest with you here.
[24:24] SPEAKER: No, these weren't community suggested projects.
[24:31] SPEAKER: These are things we know the community will be keen on
[24:35] SPEAKER: because it allows a lot of hacking,
[24:38] SPEAKER: a lot of fun things to be done.
[24:39] SPEAKER: I mean, the pine saw has become huge, for instance.
[24:43] SPEAKER: The pine time has also become huge
[24:45] SPEAKER: and on a different scale, but also huge.
[24:47] SPEAKER: The earbuds, I think, so the pine buds probably,
[24:50] SPEAKER: I think that they have a lot of potential
[24:52] SPEAKER: and we have seen a lot of interest in them.
[24:54] SPEAKER: But ultimately these are business decisions
[24:58] SPEAKER: because the project needs to make enough money
[25:02] SPEAKER: to make things that do not make money.
[25:04] SPEAKER: So say the smartphones,
[25:07] SPEAKER: they for instance do not generate a profit, right?
[25:10] SPEAKER: They are there simply because we wanted
[25:13] SPEAKER: to do a smartphone, right?
[25:16] SPEAKER: Similarly with the laptops, with the arm laptops,
[25:19] SPEAKER: quite similarly with the tablets.
[25:21] SPEAKER: So with the pine tab V and the pine tab two.
[25:25] SPEAKER: So there needs to be things within our range
[25:28] SPEAKER: that do generate the funds to do the things
[25:31] SPEAKER: that are more fun.
[25:33] SPEAKER: And definitely there's no need to hide the fact
[25:37] SPEAKER: that the pine saw, the pine time, the pine buds,
[25:41] SPEAKER: as well as some of the modules are designed
[25:44] SPEAKER: to generate that profit to do some of the fun things
[25:46] SPEAKER: that we, the other fun things we do, yeah.
[25:49] SPEAKER: - Yeah, with hardware especially and especially with,
[25:51] SPEAKER: since you're doing RISC-V hardware now,
[25:54] SPEAKER: there's a chicken or egg situation
[25:56] SPEAKER: where you have to build the hardware
[25:57] SPEAKER: so that the software can exist,
[25:59] SPEAKER: so that the hardware can sell.
[26:01] SPEAKER: And I assume that's the point with the laptops
[26:04] SPEAKER: and the tablets and the smartphones
[26:06] SPEAKER: is to build up these ecosystems
[26:08] SPEAKER: for people using Linux for phones
[26:13] SPEAKER: so that these actually do become viable platforms
[26:15] SPEAKER: at some point in the future.
[26:16] SPEAKER: And I assume you don't always want them
[26:18] SPEAKER: to be projects that are losing money eventually, I hope.
[26:22] SPEAKER: I assume you want them to drive revenue
[26:24] SPEAKER: for the company, but yeah.
[26:25] SPEAKER: - I mean, there's definitely some products
[26:27] SPEAKER: that do not need to make revenue,
[26:29] SPEAKER: such as the phones, right?
[26:31] SPEAKER: We just wanna see Linux on smartphones
[26:33] SPEAKER: and we wanna see a future where there is an alternative
[26:37] SPEAKER: to the current operating systems, right?
[26:41] SPEAKER: And one way of doing that is making sure
[26:43] SPEAKER: that everybody can get their hands on one if they want one.
[26:47] SPEAKER: From the moment we conceived of this idea,
[26:51] SPEAKER: we figured we'll pretty much sell it at costs
[26:55] SPEAKER: just to make sure that everybody
[26:56] SPEAKER: who really wants one can get one, right?
[26:59] SPEAKER: So they're not losing money,
[27:01] SPEAKER: but they're not generating revenue,
[27:03] SPEAKER: but something has to generate revenue.
[27:04] SPEAKER: And there's definitely some products
[27:06] SPEAKER: that are designed to generate revenue within the lineup.
[27:10] SPEAKER: - It's remarkable to me that you talk about
[27:12] SPEAKER: things like the Pine Time smartwatch
[27:13] SPEAKER: as being the sort of popular volume movers,
[27:16] SPEAKER: the profit generating products,
[27:18] SPEAKER: because I was ready to come in here
[27:20] SPEAKER: and say that your prices are just astonishingly low.
[27:23] SPEAKER: I mean, the Pine Time currently on your site
[27:26] SPEAKER: is selling for 26.99 and I looked at that
[27:28] SPEAKER: and I was just like, there has to be a zero missing here.
[27:31] SPEAKER: Like, how is this possible?
[27:32] SPEAKER: I mean, even though you say
[27:33] SPEAKER: that these are successful revenue drivers,
[27:35] SPEAKER: I mean, I don't know how much you wanna get
[27:38] SPEAKER: into the business model, but I mean,
[27:39] SPEAKER: these are, I assume, like relatively low profit margin.
[27:42] SPEAKER: I mean, it seems remarkable what you're getting,
[27:46] SPEAKER: looking at what else is out there
[27:47] SPEAKER: from more closed companies in the same space for this price.
[27:51] SPEAKER: - Sure, but even if, let's say, they each generate,
[27:55] SPEAKER: so even if the Pine Sol and the Pine Time
[27:56] SPEAKER: just generate a dollar or a dollar and a half
[28:00] SPEAKER: in very large quantities,
[28:02] SPEAKER: which these have had significant uptake,
[28:05] SPEAKER: you know, this is perfectly fine.
[28:07] SPEAKER: And then compute modules,
[28:10] SPEAKER: while Raspberry Pi compute module has been, you know,
[28:15] SPEAKER: the standard very much in the West,
[28:18] SPEAKER: the So Pine compute module has been taken up
[28:21] SPEAKER: in significant parts of Asia, you know, for a long time now,
[28:26] SPEAKER: used in everything from rail signage
[28:29] SPEAKER: to slot machines and what have you.
[28:33] SPEAKER: And those sort of things make phones and tablets
[28:39] SPEAKER: with RISC-V, RISC-V processors possible, yeah.
[28:43] SPEAKER: - So what's the common thread for all this?
[28:44] SPEAKER: Is it, hey, we can get electronics manufactured?
[28:48] SPEAKER: Like we have, is that the sauce of the company?
[28:50] SPEAKER: Or is it, we're really good at SOCs?
[28:53] SPEAKER: Or, you know, what connects the Pine Sol and the phone?
[28:57] SPEAKER: Or is it just, hey, this is the thing
[28:58] SPEAKER: we want to exist in the world.
[28:59] SPEAKER: What connects the Pine Sol and the phone
[29:01] SPEAKER: and the tablet and the laptop
[29:02] SPEAKER: and the SOC and the power station?
[29:07] SPEAKER: - Right, so there's definitely a maker side
[29:10] SPEAKER: to this equation.
[29:11] SPEAKER: You know, even things such as the phone
[29:13] SPEAKER: can be dismantled.
[29:15] SPEAKER: We actually, you know, if you break it,
[29:17] SPEAKER: we encourage you to fix it yourself.
[29:19] SPEAKER: There's spare parts on the website and stuff like that.
[29:22] SPEAKER: - I love that, by the way.
[29:23] SPEAKER: That's my favorite thing.
[29:25] SPEAKER: - It's a question of, you know,
[29:26] SPEAKER: undoing 12 screws or whatever,
[29:27] SPEAKER: and you'll be fine.
[29:29] SPEAKER: You'll have it, you know,
[29:30] SPEAKER: I'm not particularly technically savvy,
[29:32] SPEAKER: but I've taken apart dozens of them and fixed many of them.
[29:36] SPEAKER: They're really quite trivial to fix if you drop it.
[29:40] SPEAKER: You know, it's a question of 20 minutes for me
[29:43] SPEAKER: to fix one, so no biggie.
[29:45] SPEAKER: But there is also a lead thread,
[29:47] SPEAKER: which goes from when we create a single board computer,
[29:51] SPEAKER: a single board computer is obviously a standalone device,
[29:55] SPEAKER: but it is also a basis,
[29:57] SPEAKER: a platform upon which we sometimes, not always,
[30:00] SPEAKER: but usually decide to build more products, right?
[30:04] SPEAKER: So there are particular SOCs,
[30:06] SPEAKER: which we see particularly high potential in, right?
[30:09] SPEAKER: Usually from SOC vendors who are more friendly
[30:13] SPEAKER: or more keen to cooperate with the open source community.
[30:17] SPEAKER: There's definitely,
[30:18] SPEAKER: some of the products are created
[30:20] SPEAKER: just because we wanna see them exist.
[30:23] SPEAKER: There are some products which exist
[30:25] SPEAKER: because there is a need for them to exist
[30:28] SPEAKER: in the business world.
[30:29] SPEAKER: So this would be the compute modules,
[30:32] SPEAKER: like Soppines were massively huge.
[30:35] SPEAKER: There are products which exist
[30:37] SPEAKER: simply because they didn't exist before,
[30:39] SPEAKER: and we didn't know if there was a market for them or not,
[30:42] SPEAKER: such as a open smartwatch.
[30:44] SPEAKER: And it turns out that it is,
[30:46] SPEAKER: I mean, I'll be honest, it's a phenomenal project, right?
[30:50] SPEAKER: When we were talking first about the PineSoul,
[30:53] SPEAKER: nobody would understand why,
[30:55] SPEAKER: why would anyone want to have a soldering iron
[30:59] SPEAKER: that connects via Bluetooth to your desktop
[31:03] SPEAKER: to display how hot the tip is?
[31:06] SPEAKER: But it turns out that a lot of people want that.
[31:09] SPEAKER: So you never know.
[31:11] SPEAKER: - That specifically is a feature
[31:12] SPEAKER: that my much more expensive soldering station
[31:15] SPEAKER: from a company that's been making soldering irons
[31:16] SPEAKER: for a hundred years does not offer
[31:19] SPEAKER: at anything other than ridiculous professional level prices.
[31:23] SPEAKER: So when I saw,
[31:25] SPEAKER: it was literally the fastest time
[31:26] SPEAKER: when I saw the PineSoul that I've ever gone from,
[31:29] SPEAKER: oh God, another thing's USB connected
[31:31] SPEAKER: or another thing's Bluetooth connected.
[31:32] SPEAKER: Why do we need this?
[31:33] SPEAKER: To, oh wow, I've hit the order button.
[31:36] SPEAKER: It's gonna be here in three days.
[31:37] SPEAKER: That sounds fantastic.
[31:38] SPEAKER: So it is a place where having smart control
[31:41] SPEAKER: over your temperature actually makes a difference
[31:43] SPEAKER: in how well you can solder.
[31:44] SPEAKER: Also the size of the thing
[31:46] SPEAKER: and the fact that I can run it off a USB power pack.
[31:48] SPEAKER: So I have a portable soldering iron
[31:50] SPEAKER: that doesn't use butane and works anywhere.
[31:53] SPEAKER: And I won't torch my boards when I'm doing stuff with it.
[31:55] SPEAKER: It is a transformative device for me.
[31:58] SPEAKER: So I appreciate you all a lot.
[32:00] SPEAKER: I guess what I'm saying is thank you
[32:01] SPEAKER: for making the internet of shit soldering iron.
[32:04] SPEAKER: - Yeah, but the PineSoul isn't the first soldering iron
[32:09] SPEAKER: to run the open operating system
[32:11] SPEAKER: or the open firmware for it.
[32:13] SPEAKER: There have been others,
[32:15] SPEAKER: except we reached out to Ben Rallum directly.
[32:19] SPEAKER: We said, hey, we wanna make one of those things.
[32:22] SPEAKER: They seem like, they seem fun.
[32:25] SPEAKER: Would you like to tell us what you wanna see
[32:27] SPEAKER: in one of these?
[32:28] SPEAKER: And he came aboard and he told us exactly
[32:30] SPEAKER: what he wanted to see in such a soldering iron.
[32:33] SPEAKER: And we said, all right, well, we'll make it happen.
[32:36] SPEAKER: And here we are.
[32:36] SPEAKER: And this is why it's ultimately a better soldering iron
[32:40] SPEAKER: than the alternatives which were available at the time.
[32:42] SPEAKER: It's because he came in and he said, look,
[32:44] SPEAKER: this is what people are looking in these little things.
[32:48] SPEAKER: And he worked, he really guided us through this
[32:52] SPEAKER: and made a very good product.
[32:55] SPEAKER: And then when we wanted to do the V2,
[32:57] SPEAKER: we really spoke to him for months about it
[33:00] SPEAKER: not to make it into a gimmick,
[33:03] SPEAKER: but make it into something that
[33:05] SPEAKER: does what it already does better,
[33:07] SPEAKER: because ultimately for those who care about two seconds
[33:12] SPEAKER: or three seconds faster heat up time,
[33:15] SPEAKER: the V2 does heat up ridiculously fast
[33:18] SPEAKER: even compared to the V1.
[33:20] SPEAKER: But then we thought, what else can we do
[33:23] SPEAKER: that would open up the possibilities
[33:25] SPEAKER: with the soldering iron?
[33:27] SPEAKER: Bluetooth was one of the options.
[33:30] SPEAKER: - I mean, I almost feel like you're doing
[33:31] SPEAKER: a public service here because like with the Pine Soul,
[33:33] SPEAKER: just like with the smartwatch,
[33:35] SPEAKER: the thing is selling for $26 right now.
[33:37] SPEAKER: And when Will told me, I had never heard of it before
[33:39] SPEAKER: until Will got one and described it to me.
[33:41] SPEAKER: And I was like, well, that easily
[33:42] SPEAKER: is gonna be two or $300 minimum.
[33:44] SPEAKER: And I looked at it, the site had just fell out of my chair.
[33:47] SPEAKER: You know what I mean?
[33:48] SPEAKER: It's like I solder something maybe once a year,
[33:50] SPEAKER: but at that price range and with this level of features
[33:53] SPEAKER: and openness, like why wouldn't I get one, right?
[33:56] SPEAKER: Like it's just, I feel like it's in a category
[33:59] SPEAKER: where just about anybody who's even like soldering curious
[34:01] SPEAKER: could grab one at fairly low risk and give it a shot, right?
[34:05] SPEAKER: - Yeah.
[34:06] SPEAKER: And I mean, if you like Brisk 5 microcontrollers,
[34:09] SPEAKER: it's running on a Brisk 5 microcontroller.
[34:12] SPEAKER: And we even made a breakup board for it,
[34:14] SPEAKER: which you can pick up if you wanna use it
[34:18] SPEAKER: just to learn about Brisk 5 as a platform.
[34:21] SPEAKER: - I think it's the first Brisk 5 processor
[34:23] SPEAKER: I had in the house.
[34:24] SPEAKER: I'm reasonably sure of that.
[34:25] SPEAKER: - Oh yeah, all right, yeah.
[34:26] SPEAKER: - Is it fair to say the Pine Soul
[34:27] SPEAKER: is sort of the breakout product
[34:29] SPEAKER: in terms of market penetration?
[34:30] SPEAKER: And I know like it rises up
[34:33] SPEAKER: in the Amazon search results a lot now.
[34:34] SPEAKER: Is it kind of the most visible?
[34:37] SPEAKER: - Right, in that sense, yes, yes.
[34:39] SPEAKER: Because obviously there's relatively few people in the world
[34:43] SPEAKER: who want a Linux smartphone, right?
[34:46] SPEAKER: Or in general, there's a few people
[34:48] SPEAKER: who want the Linux laptop
[34:50] SPEAKER: and especially one which runs ARM,
[34:51] SPEAKER: there's very few such people still.
[34:53] SPEAKER: I mean, statistics don't lie.
[34:55] SPEAKER: So yes, in terms of share volume, yes, absolutely.
[35:01] SPEAKER: This is probably the product
[35:03] SPEAKER: that has seen the most adoption
[35:07] SPEAKER: throughout all sorts of circles, makers,
[35:11] SPEAKER: but I've seen them everywhere, literally.
[35:13] SPEAKER: But the pine time,
[35:14] SPEAKER: there's a lot of people in conventions
[35:16] SPEAKER: who you're gonna see wearing a pine time
[35:18] SPEAKER: and following the pandemic,
[35:22] SPEAKER: this was the first FOSTA when I went
[35:23] SPEAKER: and just saw how many pine phones there are
[35:26] SPEAKER: in the community, it's completely nuts.
[35:28] SPEAKER: - One of the cues that I had
[35:29] SPEAKER: that the pine sole has achieved pretty broad penetration
[35:32] SPEAKER: is that it's the one product,
[35:34] SPEAKER: or at least I assume at least the first one
[35:36] SPEAKER: that has had a cloning problem
[35:38] SPEAKER: that there are counterfeit pine soles out there now.
[35:40] SPEAKER: I'm sure from a design and logistics standpoint,
[35:43] SPEAKER: it was annoying to deal with that problem.
[35:44] SPEAKER: But is it also a little flattering
[35:47] SPEAKER: that you've made something popular
[35:48] SPEAKER: and robust enough that people want to try to copy it?
[35:51] SPEAKER: - Of course, of course it is flattering.
[35:53] SPEAKER: We estimate that anywhere between 10 to 20 times more,
[35:58] SPEAKER: that there have been 10 to 20 times more copies sold
[36:02] SPEAKER: than the original pine sole V1.
[36:05] SPEAKER: We've put in a security feature into the V2,
[36:10] SPEAKER: which allows you to check
[36:13] SPEAKER: whether you have a genuine device or not,
[36:17] SPEAKER: but that's just for you.
[36:19] SPEAKER: I mean, that's just whether you want to support us
[36:22] SPEAKER: and the project.
[36:24] SPEAKER: But I'm sure they gotta be able to replicate it otherwise,
[36:27] SPEAKER: just fine as well in a month's time or two months time.
[36:31] SPEAKER: - So I was gonna say how,
[36:34] SPEAKER: you say you have these leader products
[36:36] SPEAKER: that are generating revenue
[36:37] SPEAKER: that support the rest of the pine64 business.
[36:41] SPEAKER: And I'm curious, you look at a margin
[36:45] SPEAKER: that you can sell the device for and you're like,
[36:46] SPEAKER: okay, we're gonna put this percentage back.
[36:49] SPEAKER: Is there funding from other sources
[36:50] SPEAKER: that aren't selling hardware
[36:51] SPEAKER: or is everything funded off of selling hardware
[36:53] SPEAKER: at this point?
[36:54] SPEAKER: - Everything, we do not have as,
[36:56] SPEAKER: so there are internally a few principles.
[36:59] SPEAKER: One is that we do not have any,
[37:02] SPEAKER: that the only stakeholders are community members
[37:07] SPEAKER: and developers, so we do not have anyone else exerting
[37:11] SPEAKER: any type of pressure on us.
[37:14] SPEAKER: This is kind of, because we do wanna do weird things, right?
[37:19] SPEAKER: If I were to go, the pine time was my idea, right?
[37:23] SPEAKER: Were I to go and pitch an open smartwatch
[37:27] SPEAKER: in a traditional setting, I would have been turned down.
[37:30] SPEAKER: It just simply did not make sense at the time, right?
[37:34] SPEAKER: So no, we do not have other means of revenue.
[37:37] SPEAKER: I mean, it is all hardware.
[37:39] SPEAKER: So there's no other source of income.
[37:42] SPEAKER: - I'm curious how open your hardware designs are.
[37:44] SPEAKER: I mean, obviously that is a goal of the company,
[37:46] SPEAKER: but I assume there are just certain legal restrictions
[37:49] SPEAKER: in terms of the vendors you work with.
[37:50] SPEAKER: And I don't know about schematics and documentation.
[37:53] SPEAKER: Are there limits to how much you can expose to the developers
[37:57] SPEAKER: in terms of IP and proprietary technology
[38:00] SPEAKER: that like the vendors that you work with
[38:02] SPEAKER: just won't allow you to make open?
[38:05] SPEAKER: - This will vary from one product to the other,
[38:07] SPEAKER: but in general, because we work with developers so closely,
[38:11] SPEAKER: what happens is that we will sometimes,
[38:15] SPEAKER: we will usually settle only for a component
[38:18] SPEAKER: if we can get the schematic for it, right?
[38:23] SPEAKER: So we will never buy something where we know
[38:26] SPEAKER: that we have no contact with the vendor.
[38:28] SPEAKER: We have no information about it
[38:29] SPEAKER: and no one is interested in working on it, right?
[38:32] SPEAKER: So for instance, with the Python Pro,
[38:35] SPEAKER: we had a really lovely camera for the rear facing camera,
[38:39] SPEAKER: which we could have gotten,
[38:42] SPEAKER: we could have a steady supply of it,
[38:44] SPEAKER: but there was no real work on it being done in Linux.
[38:49] SPEAKER: Nobody really had any interest working on it.
[38:53] SPEAKER: We had no documentation for it.
[38:54] SPEAKER: So we had to basically go and settle on something else,
[38:57] SPEAKER: something which has all of this support
[38:59] SPEAKER: and interest and work.
[39:01] SPEAKER: So in general, with regard to openness,
[39:04] SPEAKER: we make sure to get as much data as we can from the vendor
[39:09] SPEAKER: where SDKs and stuff like that are pertinent.
[39:12] SPEAKER: We always get it from the vendor
[39:13] SPEAKER: and make sure that this is delivered to developers.
[39:17] SPEAKER: Where there hasn't been any efforts made,
[39:20] SPEAKER: so like LCD panels bring up of these LCD panels in Linux,
[39:24] SPEAKER: you know, it's from the ground up.
[39:26] SPEAKER: We have company representatives who basically say,
[39:30] SPEAKER: yeah, we'll come in and we'll talk to the devs
[39:32] SPEAKER: and we'll let the devs know, you know,
[39:34] SPEAKER: you're going in the right direction, that sort of thing.
[39:37] SPEAKER: Then we have, with respect to the main SOC,
[39:40] SPEAKER: we have very good contact with Rockchip
[39:43] SPEAKER: and now with other vendors as well,
[39:46] SPEAKER: who have, you know, they have been good
[39:49] SPEAKER: when it comes to the open community,
[39:51] SPEAKER: open source community.
[39:52] SPEAKER: And then everything that is ours that we do,
[39:55] SPEAKER: we document and we make it available to the community.
[39:58] SPEAKER: We stop at basically providing Gerber files,
[40:02] SPEAKER: which is the kind of the stop point.
[40:05] SPEAKER: And, you know, the reason for it is not so much
[40:10] SPEAKER: because we don't want you making your own phone.
[40:14] SPEAKER: It's that we know that where we manufacture and make things,
[40:18] SPEAKER: we could see, you know, if the Pine Soul can be cloned,
[40:22] SPEAKER: so can the Pine Phone with the right files and much faster.
[40:26] SPEAKER: - Does doing development in public in the open
[40:28] SPEAKER: make it harder to kill stuff as it's going
[40:31] SPEAKER: when you see it's not going to work out?
[40:33] SPEAKER: Do you get to the point that you've announced something
[40:36] SPEAKER: and you're like, oh, we shouldn't be making this
[40:38] SPEAKER: and you've had to kill stuff as you're in progress?
[40:41] SPEAKER: - Yes, absolutely.
[40:42] SPEAKER: The IP cam, which we call the cube,
[40:45] SPEAKER: everybody on the team thought it's a great idea.
[40:49] SPEAKER: Turns out nobody's interested in it.
[40:53] SPEAKER: The SOC was great.
[40:54] SPEAKER: The actual camera module was good.
[40:56] SPEAKER: The design I thought was pretty solid.
[40:58] SPEAKER: You could run any type of, you know, Linux on it
[41:02] SPEAKER: and just stream from it or there's,
[41:04] SPEAKER: I'm blanking on it right now,
[41:05] SPEAKER: but there is one dedicated Linux distribution
[41:09] SPEAKER: or basically it's a, what is it called?
[41:11] SPEAKER: MotionEye, is that what it's called?
[41:13] SPEAKER: Which is made for basically like security cameras
[41:17] SPEAKER: and stuff that could run on it.
[41:18] SPEAKER: And it seemed like a great idea.
[41:19] SPEAKER: You have a, you know, an open Nanny cam or security cam.
[41:24] SPEAKER: It seemed like a great idea,
[41:25] SPEAKER: but ultimately the interest was not there.
[41:27] SPEAKER: So we did kill it off.
[41:30] SPEAKER: There's very few projects that we killed off
[41:33] SPEAKER: because there was no interest, however.
[41:34] SPEAKER: There were a few which we had to kill off,
[41:37] SPEAKER: especially during the pandemic,
[41:38] SPEAKER: because there was no means to manufacture them.
[41:41] SPEAKER: But otherwise, you know,
[41:43] SPEAKER: I think that the cube is probably the only example
[41:46] SPEAKER: that comes into my head of something which we killed off
[41:49] SPEAKER: because there was no interest in it.
[41:51] SPEAKER: - Okay, so it is listed as out of stock on your site.
[41:53] SPEAKER: So it is literally out of production, just done?
[41:56] SPEAKER: - It is out of production, yeah.
[41:57] SPEAKER: - Okay.
[41:58] SPEAKER: - I would say that we haven't really lost interest
[42:00] SPEAKER: in the concept and definitely want to explore it more,
[42:04] SPEAKER: but perhaps in a more modular fashion.
[42:07] SPEAKER: So we made this tiny little microcontroller SBC
[42:13] SPEAKER: called the AUX 64, which is Linux capable.
[42:17] SPEAKER: And we are developing sort of a camera module
[42:20] SPEAKER: which will attach to it.
[42:22] SPEAKER: So you would be able to sort of transform it
[42:25] SPEAKER: into a sort of a cube spiritual successor
[42:28] SPEAKER: for those few who are interested in the device.
[42:31] SPEAKER: - I wanted to dig into just a little bit
[42:33] SPEAKER: what it's like using the Pine phone,
[42:34] SPEAKER: because, you know, of all your products,
[42:36] SPEAKER: obviously a phone is the most universal, you know,
[42:38] SPEAKER: not everybody uses a laptop or a smartwatch,
[42:40] SPEAKER: but everybody's got a phone.
[42:41] SPEAKER: So I'm just kind of, I'm curious,
[42:43] SPEAKER: especially for people who aren't Linux developers
[42:45] SPEAKER: who are less tinkering inclined,
[42:47] SPEAKER: what the out of the box experience is like
[42:49] SPEAKER: with Linux on a phone.
[42:50] SPEAKER: You've standardized around Manjaro at this point
[42:53] SPEAKER: on your phones, although I assume the other open phone OSs
[42:56] SPEAKER: are still an option to install.
[42:58] SPEAKER: - Absolutely, yeah.
[42:59] SPEAKER: - But I'm just kind of curious,
[43:00] SPEAKER: like when you booted up for the first time,
[43:01] SPEAKER: in terms of, I guess, just onboarding, you know, App Store,
[43:05] SPEAKER: like what are the sort of common phone analogs like on there
[43:09] SPEAKER: in terms of usability compared to the closed, bigger,
[43:12] SPEAKER: you know, Apples and Googles of the world?
[43:14] SPEAKER: - I'll tell you this.
[43:15] SPEAKER: It depends on how you look at it.
[43:17] SPEAKER: So it is the most successful Linux on mobile effort thus far.
[43:23] SPEAKER: And the development over the past two years
[43:26] SPEAKER: has just gone, you know, a very long way, right?
[43:31] SPEAKER: Like we are at a point where all key features
[43:35] SPEAKER: of the original PinePhone, as well as the PinePhone Pro,
[43:38] SPEAKER: although to a slightly lesser degree,
[43:40] SPEAKER: are functional on the device.
[43:42] SPEAKER: And from a purely hardware perspective,
[43:45] SPEAKER: these are the most, some of the most open devices period.
[43:49] SPEAKER: Like even down to the modem,
[43:51] SPEAKER: you can flash the modem with, where permissible,
[43:55] SPEAKER: you can flash the modem on your own with open firmware.
[43:59] SPEAKER: How is the experience compared to say Android or iOS?
[44:04] SPEAKER: I think that this is nowhere close
[44:08] SPEAKER: to something you would want to give somebody
[44:10] SPEAKER: who's highly dependent on either of these platforms
[44:13] SPEAKER: and has never had any contact with Linux.
[44:17] SPEAKER: Those people who think that we should be targeting
[44:20] SPEAKER: the general population and general public,
[44:23] SPEAKER: I do not agree with this point of view.
[44:27] SPEAKER: Depending on which numbers you believe,
[44:29] SPEAKER: there's anywhere between 20 to 60 million
[44:33] SPEAKER: active Linux users in the world.
[44:36] SPEAKER: And there are nowhere close
[44:38] SPEAKER: to 20 to 60 million PineFones out there.
[44:44] SPEAKER: At best, there's a few hundred thousand PineFones out there.
[44:48] SPEAKER: And I think that this is a very big market
[44:51] SPEAKER: in and of its own.
[44:53] SPEAKER: So once we convince potentially those people
[44:56] SPEAKER: who already use Linux on their desktop computers
[44:59] SPEAKER: to have a phone with Linux,
[45:01] SPEAKER: we can go after people who rely on Android
[45:05] SPEAKER: or iOS in their daily life.
[45:07] SPEAKER: How does it compare?
[45:08] SPEAKER: It doesn't really compare particularly well is the answer.
[45:12] SPEAKER: I mean, you can browse, you can set up an email client,
[45:14] SPEAKER: you could make and receive calls,
[45:17] SPEAKER: you can take photographs, you can do some chats
[45:22] SPEAKER: which have ARM clients for Linux.
[45:26] SPEAKER: But I mean, it will not do your banking app
[45:28] SPEAKER: or your travel card or whatever it is that people do
[45:34] SPEAKER: on a daily basis with their Android or iOS phones.
[45:38] SPEAKER: You can install Spotify on it for those who care.
[45:41] SPEAKER: So, but I mean, it is a different experience altogether.
[45:45] SPEAKER: It does feel like a early proof of concept,
[45:50] SPEAKER: regardless of which operating system you settle on.
[45:53] SPEAKER: And some of these operating systems are much more polished.
[45:56] SPEAKER: Some of these operating systems are mobile operating systems
[46:02] SPEAKER: which happened to be Linux.
[46:05] SPEAKER: And some of these operating systems are Linux
[46:08] SPEAKER: which happened to run on mobile, right?
[46:10] SPEAKER: So there are fractions in communities
[46:13] SPEAKER: within the broader community as well
[46:16] SPEAKER: who require different things
[46:18] SPEAKER: or want to see different things on the PinePhone,
[46:21] SPEAKER: on the PinePhone Pro.
[46:22] SPEAKER: - I've been tempted to pick one up honestly,
[46:24] SPEAKER: just to noodle with and see what,
[46:25] SPEAKER: just to get the experience, see where it's at.
[46:28] SPEAKER: Because the last time I looked at a Linux phone
[46:31] SPEAKER: was probably three or four years ago
[46:33] SPEAKER: and they were early prototypes of things
[46:36] SPEAKER: that people weren't maybe even showing publicly.
[46:39] SPEAKER: And it was rough to unusable at that point.
[46:42] SPEAKER: So, you know, there's a curve that we've seen
[46:45] SPEAKER: with a lot of open source projects where things,
[46:47] SPEAKER: where development starts slow
[46:48] SPEAKER: and then there reaches a point where the,
[46:50] SPEAKER: it's the typical capitalist hockey puck graph, right?
[46:53] SPEAKER: Where all of a sudden the features are coming,
[46:55] SPEAKER: the number of developers increases
[46:57] SPEAKER: and the features go up and up.
[46:58] SPEAKER: Like, do you feel like you're reaching,
[47:00] SPEAKER: are you working toward that point
[47:01] SPEAKER: or do you see that point in the future for the PinePhone?
[47:04] SPEAKER: Or is that, you think further off
[47:06] SPEAKER: than we should be thinking about right now?
[47:08] SPEAKER: - That is a super difficult question.
[47:12] SPEAKER: I think that our core community wants different things
[47:17] SPEAKER: from the phone than say my wife or my mom, right?
[47:23] SPEAKER: And that is a bit of a problem
[47:26] SPEAKER: because the convenience that an Android phone,
[47:29] SPEAKER: which is synced up to Google Cloud
[47:31] SPEAKER: and all that stuff gives you, it is by design,
[47:36] SPEAKER: is not replicable in the PinePhone.
[47:39] SPEAKER: But by the sort of, by the design, by the philosophy of it.
[47:44] SPEAKER: So I don't know how to answer this one.
[47:46] SPEAKER: I mean, what I'll say is this,
[47:49] SPEAKER: I hope that the list iteration of the PinePhone
[47:52] SPEAKER: or the next iteration or the next after that,
[47:54] SPEAKER: or somebody else, some other company or person
[47:57] SPEAKER: who has now a PinePhone gets inspired by it
[47:59] SPEAKER: and creates something that will make everyone
[48:03] SPEAKER: in the Linux community and the open source community say,
[48:06] SPEAKER: I want one of these things.
[48:08] SPEAKER: Like I genuinely want one.
[48:10] SPEAKER: And that it will meet their needs and requirements for it.
[48:14] SPEAKER: So whether we make it or somebody else make it,
[48:16] SPEAKER: to me personally, it doesn't really matter
[48:18] SPEAKER: as long as it gets made, right?
[48:20] SPEAKER: And everybody wants to really work on it.
[48:23] SPEAKER: - And there's also something to be said for just,
[48:25] SPEAKER: especially in a world where people are becoming more,
[48:28] SPEAKER: Corey Doctor has been yelling about privacy
[48:30] SPEAKER: for 25 years at this point.
[48:31] SPEAKER: But I think there's more momentum from normal users,
[48:35] SPEAKER: even non-Linux users about the ownership of their own data
[48:39] SPEAKER: and living outside of those closed ecosystems.
[48:43] SPEAKER: So, I mean, maybe there will be momentum there
[48:45] SPEAKER: in the future and people are willing to make a few sacrifices
[48:48] SPEAKER: to get something that's off of the Google grid
[48:50] SPEAKER: or the Apple, off of Apple's ecosystem.
[48:53] SPEAKER: So fingers crossed, I guess.
[48:56] SPEAKER: Do you all do user research?
[48:58] SPEAKER: Like did you do focused user research
[49:00] SPEAKER: or is it more informal?
[49:02] SPEAKER: Like how do you decide which direction to go with products?
[49:07] SPEAKER: How do you decide which products to support?
[49:08] SPEAKER: How do you know that a product you're building
[49:10] SPEAKER: for the market you're personally familiar with
[49:13] SPEAKER: is going to work in Southeast Asia or North America
[49:16] SPEAKER: or Africa or wherever else you care to sell stuff?
[49:20] SPEAKER: - Well, we don't because we do not really collect
[49:23] SPEAKER: any information or data.
[49:25] SPEAKER: I mean, we ran a poll about a year ago asking people,
[49:30] SPEAKER: how do you find your phone?
[49:32] SPEAKER: Like what do you run on it?
[49:35] SPEAKER: How do you use it as your daily driver?
[49:37] SPEAKER: Is it your spare phone or are you disappointed with it
[49:43] SPEAKER: and is it in your drawer
[49:45] SPEAKER: and you haven't picked it up for a year?
[49:46] SPEAKER: I mean, we ask all sorts of questions
[49:49] SPEAKER: and this is a poll from at least a year ago.
[49:51] SPEAKER: I can't remember when I put it out.
[49:53] SPEAKER: And I think, I don't know, maybe like four or 5,000 people
[49:57] SPEAKER: answered or something like that.
[49:59] SPEAKER: Obviously the number of existing users
[50:01] SPEAKER: is much, much greater.
[50:03] SPEAKER: So a lot of this we get via a sort of a,
[50:07] SPEAKER: almost like an osmosis by just being a part of the community
[50:10] SPEAKER: and talking to people on a daily basis,
[50:13] SPEAKER: just like regularly in the chat and just saying,
[50:16] SPEAKER: seeing what it is that people talk about,
[50:18] SPEAKER: what it is that they're excited about.
[50:20] SPEAKER: What is it that they wanna see?
[50:22] SPEAKER: What is it that they're disappointed with?
[50:24] SPEAKER: I mean, ultimately we don't need to run these things
[50:26] SPEAKER: because we're very much a part of the community.
[50:28] SPEAKER: Like I check the chat every single day
[50:31] SPEAKER: and everybody who wants to chat with me,
[50:33] SPEAKER: they can chat with me.
[50:35] SPEAKER: But we don't have any focus groups and stuff like that.
[50:38] SPEAKER: - I'm sure you can only say so much
[50:39] SPEAKER: about perspective, product ideas,
[50:41] SPEAKER: things that may or may not happen,
[50:42] SPEAKER: but are there any sort of pie in the sky goals
[50:46] SPEAKER: or ideas that the team has had for product categories
[50:50] SPEAKER: or spaces you'd like to get into that you either haven't yet
[50:53] SPEAKER: or like would be very difficult to do?
[50:55] SPEAKER: - Yeah, there are a few.
[50:57] SPEAKER: So we definitely are looking at the next pine time
[51:05] SPEAKER: and we're working extremely closely
[51:07] SPEAKER: with the development community
[51:09] SPEAKER: around that project infinity time that runs on the pine time
[51:15] SPEAKER: and they definitely have some awesome ideas.
[51:18] SPEAKER: And this is just to be clear to anyone listening,
[51:21] SPEAKER: this is quite far out for us.
[51:23] SPEAKER: It's still months away from prototyping,
[51:28] SPEAKER: but we're ping pong ideas.
[51:29] SPEAKER: And in general, we are super interested in RISC-V
[51:32] SPEAKER: as an architecture and where that can take us
[51:37] SPEAKER: in the next years.
[51:38] SPEAKER: And I've spoken about this pretty openly
[51:42] SPEAKER: that we definitely,
[51:45] SPEAKER: many of the devices that you see us do,
[51:49] SPEAKER: which we have already made
[51:50] SPEAKER: and which we have spoken about being interested in making,
[51:53] SPEAKER: which are arm-based,
[51:55] SPEAKER: we definitely will be making some of them
[51:58] SPEAKER: with RISC-V processors in the future as well.
[52:01] SPEAKER: So this is basically no secret.
[52:03] SPEAKER: So it's just a question of which makes sense.
[52:08] SPEAKER: A RISC-V watch is a really fun thing, I think,
[52:12] SPEAKER: and something that I would be very keen on seeing happen
[52:15] SPEAKER: in the next 18 months or so.
[52:18] SPEAKER: But, you know, a RISC-V laptop sounds equally fun.
[52:24] SPEAKER: I mean, but there are many, many different options here.
[52:28] SPEAKER: - RISC-V is kind of the last big topic
[52:30] SPEAKER: I wanted to ask you about.
[52:31] SPEAKER: I'm curious if you can speak from a kind of business
[52:33] SPEAKER: and contractual standpoint
[52:35] SPEAKER: about what it's like working with it.
[52:36] SPEAKER: I mean, for people who don't know,
[52:37] SPEAKER: RISC-V, it's an open source architecture,
[52:41] SPEAKER: kind of comparable to ARM in the mobile space
[52:43] SPEAKER: in terms of capabilities,
[52:44] SPEAKER: but open source and royalty-free, license-free,
[52:47] SPEAKER: is that accurate?
[52:49] SPEAKER: Is that an accurate way to put it?
[52:50] SPEAKER: - Yes, so this is accurate for the cores.
[52:53] SPEAKER: - Okay.
[52:54] SPEAKER: - So RISC-V has a lot of benefits to it
[53:01] SPEAKER: and it's super exciting for developers
[53:05] SPEAKER: because they, you know, the instruction set,
[53:09] SPEAKER: the ISA for RISC-V is basically available on GitHub
[53:12] SPEAKER: and they can contribute to it.
[53:14] SPEAKER: And you have a chance to help evolve the platform
[53:17] SPEAKER: on a very, very raw metal level.
[53:21] SPEAKER: So that's super interesting.
[53:22] SPEAKER: From a manufacturer's perspective,
[53:26] SPEAKER: RISC-V has the benefit, well, has multiple benefits.
[53:31] SPEAKER: One is that with time due to many more producers
[53:38] SPEAKER: creating RISC-V SOCs, there's gonna be more competition.
[53:41] SPEAKER: And because RISC-V does not depend on the license,
[53:45] SPEAKER: which you have to pay per design,
[53:48] SPEAKER: these will provide more power at a lower cost to end users.
[53:55] SPEAKER: Now, there's a lot of people,
[53:56] SPEAKER: and I'm guilty of this as well,
[53:58] SPEAKER: of saying that, you know, oh, RISC-V is so early
[54:00] SPEAKER: and it's gonna be, you know,
[54:02] SPEAKER: it's coming up slowly and stuff.
[54:04] SPEAKER: But if you compare how fast RISC-V is coming up
[54:08] SPEAKER: or Linux is coming up on RISC-V
[54:10] SPEAKER: compared to early days of ARM,
[54:12] SPEAKER: I mean, this is day and night.
[54:15] SPEAKER: I mean, we can already run Linux in a very hacky
[54:19] SPEAKER: and poor and unpleasant way on RISC-V today
[54:23] SPEAKER: with basically people have been so excited about it
[54:26] SPEAKER: that even before there were broadly available
[54:29] SPEAKER: single-board computers and development platforms
[54:31] SPEAKER: with RISC-V, we already had Linux on.
[54:34] SPEAKER: I think that what we saw with Raspberry Pi and ARM
[54:37] SPEAKER: and Linux happen in, what was it, 2012?
[54:43] SPEAKER: - 2012, yeah. - Yeah.
[54:45] SPEAKER: We're gonna see RISC-V really explode
[54:49] SPEAKER: in the next five years.
[54:51] SPEAKER: And I think Linux is gonna be
[54:54] SPEAKER: an extremely well-supported operating system
[54:57] SPEAKER: on the platform.
[54:58] SPEAKER: And I don't necessarily wanna get into the politics
[55:02] SPEAKER: of things, but if you
[55:06] SPEAKER: account for what Chinese companies
[55:09] SPEAKER: can and cannot manufacture at this point in time,
[55:14] SPEAKER: I think we're gonna see a lot of very powerful
[55:16] SPEAKER: RISC-V chips coming out of China
[55:18] SPEAKER: at very reasonable prices within 24 months,
[55:22] SPEAKER: giving ARM architecture a real run for its money.
[55:27] SPEAKER: - I'm a pretty active Debian user.
[55:28] SPEAKER: And from what I've looked at,
[55:29] SPEAKER: like the number of Debian packages being built for RISC-V
[55:33] SPEAKER: is like over 90%, I believe, at this point.
[55:34] SPEAKER: I mean, the penetration, the adoption
[55:36] SPEAKER: has been kind of alarming to see
[55:40] SPEAKER: how rapidly it's played out.
[55:41] SPEAKER: Do you have a sense from a,
[55:43] SPEAKER: I mean, like you said, obviously ARM is much more mature.
[55:46] SPEAKER: It's been around longer.
[55:46] SPEAKER: The SOCs are more robust and capable,
[55:49] SPEAKER: but do you have a sense of how fast RISC-V SOCs,
[55:52] SPEAKER: at least the ones you're using,
[55:53] SPEAKER: are approaching those capabilities
[55:55] SPEAKER: in terms of raw compute and GPU and stuff like that?
[55:58] SPEAKER: Is it getting competitive yet?
[56:01] SPEAKER: - No, but it will get there very, very fast.
[56:04] SPEAKER: And I mean, fast as in by the end of this year.
[56:07] SPEAKER: But now I also do not necessarily wanna get too technical
[56:10] SPEAKER: because I would be speaking out of term
[56:12] SPEAKER: because I am not the right person to speak about it.
[56:15] SPEAKER: But there is a misconception within the community
[56:19] SPEAKER: about RISC-V as well.
[56:20] SPEAKER: I mean, RISC-V shares many of the hurdles
[56:23] SPEAKER: that we had with ARM and still have with ARM.
[56:27] SPEAKER: Just because the cores are open
[56:29] SPEAKER: doesn't mean that everything around these cores is open.
[56:32] SPEAKER: And it's not.
[56:34] SPEAKER: - Right, the SOC manufacturers can still check a GPU
[56:37] SPEAKER: on the SOC that you have no access to internals on, right?
[56:41] SPEAKER: - Yeah, I think that's like on Raspberry Pis and so forth,
[56:43] SPEAKER: like Broadcom will put something in the SOC
[56:45] SPEAKER: that is completely closed
[56:47] SPEAKER: and undocumented, right, and proprietary.
[56:49] SPEAKER: - And then you have to rely on the goodwill of said GPU.
[56:56] SPEAKER: I mean, you mentioned GPU,
[56:57] SPEAKER: but there could be any other things that go into these SOCs,
[57:00] SPEAKER: memory controllers, what have you.
[57:02] SPEAKER: Then you have to rely on the goodwill of these companies
[57:04] SPEAKER: that they wanna cooperate with you.
[57:06] SPEAKER: And to be fair, I'm not gonna mention any names,
[57:09] SPEAKER: but there are companies that have had
[57:12] SPEAKER: a terrible track record,
[57:14] SPEAKER: but now that they found themselves on RISC-V platforms
[57:19] SPEAKER: and they're feeling the pressure,
[57:22] SPEAKER: they are more or less reluctantly going ahead
[57:27] SPEAKER: and open sourcing their drivers just by the pressure, right?
[57:33] SPEAKER: This is what happens.
[57:34] SPEAKER: I mean, when we go back to ARM and look at
[57:39] SPEAKER: why is the RK3399 so well supported in Linux?
[57:44] SPEAKER: So that's what you have in the Pinebook Pro
[57:46] SPEAKER: and the PinePhone Pro.
[57:47] SPEAKER: The reason is because Google built a Chromebook
[57:51] SPEAKER: based off it a couple of years ago and Google came in
[57:54] SPEAKER: and he said open source and Rockchip did
[57:58] SPEAKER: because there was pressure, right?
[58:00] SPEAKER: And this is a different type of pressure,
[58:02] SPEAKER: but now that there is RISC-V adoption
[58:04] SPEAKER: and RISC-V adoption from end users and enthusiasts
[58:08] SPEAKER: who apply pressure to particular companies,
[58:10] SPEAKER: these companies see this,
[58:12] SPEAKER: they also maybe see some benefit in it in open sourcing.
[58:16] SPEAKER: And now that there's a much bigger uptake
[58:18] SPEAKER: and it's not just business who uptakes these SOCs.
[58:22] SPEAKER: So they're starting to open source as well.
[58:25] SPEAKER: I mean, I don't wanna jump the gun on RISC-V,
[58:30] SPEAKER: but I do see a huge potential in RISC-V
[58:33] SPEAKER: in the next five years.
[58:37] SPEAKER: - I would love to hear, Lukasz,
[58:39] SPEAKER: where can people find out more about Pine64
[58:42] SPEAKER: and find out more about you?
[58:45] SPEAKER: - So about Pine64, we have a site for the organization.
[58:50] SPEAKER: So that's pine64.org.
[58:52] SPEAKER: There's a blog, which I and others contribute to,
[58:56] SPEAKER: right at writing monthly news at the end of each month.
[59:01] SPEAKER: And then we're on Twitter, on Mastodon and on Telegram,
[59:07] SPEAKER: where we sort of stream news and information
[59:11] SPEAKER: on the fairly regular.
[59:17] SPEAKER: - Thank you, Lukasz, for coming on the podcast.
[59:19] SPEAKER: We'd love to have you here
[59:20] SPEAKER: and love to learn more about Pine64.
[59:23] SPEAKER: - Yes, getting to hear...
[59:25] SPEAKER: Yeah, getting to talk to somebody who's got experience
[59:27] SPEAKER: in this kind of like a murky, nebulous world
[59:29] SPEAKER: of how electronics get made these days
[59:31] SPEAKER: is always super illuminating because like, you know,
[59:34] SPEAKER: we're pretty awash in inexpensive electronics these days.
[59:39] SPEAKER: And I think most people sort of just,
[59:41] SPEAKER: their relationship is just sort of,
[59:43] SPEAKER: I ordered online and it shows up at my house and that's it.
[59:45] SPEAKER: So hearing from, you know,
[59:47] SPEAKER: the prototype phase through manufacturing,
[59:49] SPEAKER: and especially with the community relationship model
[59:52] SPEAKER: that Pine64 has, like it just,
[59:53] SPEAKER: just a fascinating look behind the curtain
[59:56] SPEAKER: and how a lot of the stuff gets made.
[59:58] SPEAKER: - I often say that open source hardware feels like,
[1:00:01] SPEAKER: like the kind of good early cyberpunk novels
[1:00:04] SPEAKER: where it's like some guy in a back room
[1:00:06] SPEAKER: that has a bunch of circuses hacking stuff together.
[1:00:08] SPEAKER: - Yes.
[1:00:10] SPEAKER: - This is what this really feels like.
[1:00:11] SPEAKER: This feels like that in a not dystopian way,
[1:00:14] SPEAKER: if that makes sense.
[1:00:15] SPEAKER: I know cyberpunk's-
[1:00:16] SPEAKER: - 100%.
[1:00:17] SPEAKER: - Apparently dystopian, whatever, yada yada.
[1:00:19] SPEAKER: - I don't know if I made this comparison in that interview.
[1:00:21] SPEAKER: I may have, but like any product that feels like
[1:00:24] SPEAKER: it would be the favorite brand
[1:00:25] SPEAKER: of the Henry Rollins character from Johnny Mnemonic,
[1:00:28] SPEAKER: like the cyberpunk mechanic guy is probably pretty cool.
[1:00:32] SPEAKER: - Yeah, and there's also a repairability aspect
[1:00:35] SPEAKER: to the whole thing that I really, really like.
[1:00:37] SPEAKER: So please make sure you check out Pine64.
[1:00:40] SPEAKER: As we said in the interview,
[1:00:41] SPEAKER: they love to get contributors,
[1:00:43] SPEAKER: whether it's people writing documentation,
[1:00:44] SPEAKER: people requesting stuff for new hardware.
[1:00:48] SPEAKER: It was a fascinating interview,
[1:00:49] SPEAKER: and thanks again to Will Cash for coming by.
[1:00:51] SPEAKER: And that will do it for this week's episode of the show.
[1:00:53] SPEAKER: As always, the FOSPOD is brought to you
[1:00:55] SPEAKER: by Google Open Source.
[1:00:56] SPEAKER: They bring all the value of open source to Google
[1:00:58] SPEAKER: and all the resources of Google to open source.
[1:01:01] SPEAKER: Matt Purdy produced this episode,
[1:01:02] SPEAKER: and Sabrina Hill edited it.
[1:01:04] SPEAKER: Thanks you all for listening.
[1:01:05] SPEAKER: We'll be back soon with another episode of the FOSPOD.
[1:01:08] SPEAKER: (upbeat music)
[1:01:14] SPEAKER: - Brad, we've reached the point of the show
[1:01:15] SPEAKER: where we thank our patrons.
[1:01:16] SPEAKER: - We have, thank you, patrons.
[1:01:18] SPEAKER: - Thank you, patrons.
[1:01:19] SPEAKER: As always, if you would like to support the TechPod,
[1:01:21] SPEAKER: you can go to patreon.com/techpod.
[1:01:23] SPEAKER: Again, it's patreon.com/techpod.
[1:01:26] SPEAKER: And for five bucks a month,
[1:01:27] SPEAKER: you get access to the fabulous TechPod Discord,
[1:01:30] SPEAKER: which literally inspired the show.
[1:01:31] SPEAKER: People were talking about this Pine cell
[1:01:33] SPEAKER: months and months and months ago on the TechPod Discord.
[1:01:35] SPEAKER: And I was like, I am incredibly skeptical,
[1:01:38] SPEAKER: as I said in the intro,
[1:01:39] SPEAKER: incredibly skeptical of this smart,
[1:01:42] SPEAKER: why does a soldering iron need to be smart?
[1:01:44] SPEAKER: I have one with a dial on it
[1:01:45] SPEAKER: that lets me set the temperature.
[1:01:46] SPEAKER: That's all I need.
[1:01:48] SPEAKER: I was wrong.
[1:01:49] SPEAKER: I was very wrong.
[1:01:51] SPEAKER: But yeah, we thank you all for your support every month.
[1:01:56] SPEAKER: - Yes, thank you.
[1:01:57] SPEAKER: Through Discord, incredible resource.
[1:01:58] SPEAKER: Not only did they turn us on to the Pine cell,
[1:02:01] SPEAKER: when I got mine and I couldn't get it to update on my PC
[1:02:04] SPEAKER: for some unknown USB compatibility reason,
[1:02:07] SPEAKER: then I had to go to my laptop
[1:02:08] SPEAKER: and compile a version of the flashing utility.
[1:02:11] SPEAKER: - Wow.
[1:02:12] SPEAKER: - To get it to work.
[1:02:12] SPEAKER: I wouldn't have been able to get that done either
[1:02:14] SPEAKER: without the help of people on the Discord.
[1:02:16] SPEAKER: (laughing)
[1:02:18] SPEAKER: Just an endless resource.
[1:02:20] SPEAKER: - As always, every week we like to thank
[1:02:22] SPEAKER: our executive producer tier patrons,
[1:02:24] SPEAKER: including Nick Johnston,
[1:02:25] SPEAKER: Paddle Creek Games makers of Fractured Veil,
[1:02:27] SPEAKER: Andrew Slosky, the Bunny Daemon.
[1:02:29] SPEAKER: Sorry, the Bunny Daemon.
[1:02:31] SPEAKER: - Yeah.
[1:02:32] SPEAKER: - Just Wedge, Joel Krauska, Twinkle, Twinkie2049,
[1:02:35] SPEAKER: David Allen, and James Kamik.
[1:02:37] SPEAKER: Thank you all so, so much.
[1:02:38] SPEAKER: - Thank you.
[1:02:39] SPEAKER: - We will be back next week again with a regular episode.
[1:02:42] SPEAKER: - If I have time to do some reading while I'm gone,
[1:02:44] SPEAKER: we might be able to start the Bluetooth trip.
[1:02:45] SPEAKER: - Oh, oh.
[1:02:47] SPEAKER: - I know, maybe, maybe.
[1:02:49] SPEAKER: Just putting it out there's a possibility.
[1:02:51] SPEAKER: - Dabbling with forces we may not understand, man.
[1:02:53] SPEAKER: - I'm just saying there are Finnish, Danish pirates out there
[1:03:00] SPEAKER: and we're going to find out what color their teeth are.
[1:03:03] SPEAKER: And that's, we're gonna start with the Danish pirate.
[1:03:05] SPEAKER: We're gonna go through the entire history
[1:03:06] SPEAKER: of the Danish piracy.
[1:03:07] SPEAKER: And then eventually we'll get to Erikson and Sony
[1:03:10] SPEAKER: making a super team to invent radios on the phones.
[1:03:17] SPEAKER: See you all next week.
[1:03:18] SPEAKER: Bye, everybody.
