---
episode: 204
title: 194: All I Want Is Simple Determinism!
date: 2023-08-06
guests: none
duration: 1:10:43
---

[00:00] SPEAKER: OK, we were setting up to record and you just casually tossed off as we were about to press
[00:04] SPEAKER: record.
[00:06] SPEAKER: Something along the lines of I just updated the weekly challenge in our game.
[00:10] SPEAKER: Yeah.
[00:11] SPEAKER: And I was, I was a bit gobsmacked because when you describe a process like that, I assume
[00:16] SPEAKER: it requires like three engineers and an hour of each person's time to do something like
[00:22] SPEAKER: that.
[00:23] SPEAKER: And instead it sounds like you maybe like changed one value in a backend and really
[00:26] SPEAKER: I just want to talk about your game's backend.
[00:29] SPEAKER: So wow.
[00:30] SPEAKER: That sounds filthy when you put it that way.
[00:31] SPEAKER: So I, I, I went to a control panel.
[00:33] SPEAKER: This is the anacrusis we're talking about.
[00:35] SPEAKER: It's available on Steam and X-Box you can mail it for 20 bucks.
[00:37] SPEAKER: You don't say.
[00:38] SPEAKER: It's a left for dead co-op shooter.
[00:42] SPEAKER: We shoot aliens made by Chet Valasek, the lead at Valve for left for dead.
[00:49] SPEAKER: And we just, we just rolled out versus mode a couple of weeks ago.
[00:53] SPEAKER: Yes.
[00:54] SPEAKER: It's so updating the backend.
[00:55] SPEAKER: It's very exciting.
[00:56] SPEAKER: I go to a webpage, are you with me so far?
[00:59] SPEAKER: Yes.
[01:00] SPEAKER: And then I click on a thing that says game records.
[01:05] SPEAKER: Okay.
[01:06] SPEAKER: Okay.
[01:07] SPEAKER: And then it opens up a page that has a text field in there.
[01:09] SPEAKER: That's got a bunch of Jason in it for all the stuff that we can configure outside of
[01:13] SPEAKER: the game without having to make a build.
[01:15] SPEAKER: So like we, we've, we've actually done a bunch of like, we have some special, like some,
[01:19] SPEAKER: some enemy spawns are in there so we can like, we can juice up the, the, the rarer enemies
[01:25] SPEAKER: on special occasions if we want.
[01:29] SPEAKER: We can turn on and off things like boat kick and features that we weren't sure we're going
[01:33] SPEAKER: to work right when we rolled them out.
[01:34] SPEAKER: So we didn't have to do a new build to fix them.
[01:38] SPEAKER: But in there also is the current weekly challenge.
[01:40] SPEAKER: So I've scrolled down until I got to the part where it says weekly challenge.
[01:45] SPEAKER: And then I took the number that was in the weekly challenge slot and added one to it
[01:50] SPEAKER: and I hit save.
[01:52] SPEAKER: Okay.
[01:53] SPEAKER: And then from the moment I did that, the next person who connected to the, to the, to the
[01:57] SPEAKER: server to, to set up matchmaking was in magic.
[02:02] SPEAKER: I consider myself a connoisseur and aficionado of content management systems.
[02:07] SPEAKER: This is not a good one.
[02:08] SPEAKER: Having, having, yeah.
[02:09] SPEAKER: Okay.
[02:10] SPEAKER: I was going to get to that and having, having worked on websites for as long as I have,
[02:13] SPEAKER: I have, I have been putting content into forms, pressing publish for over 20 years.
[02:18] SPEAKER: And you've been there like, just to be clear for people who are like use WordPress today,
[02:22] SPEAKER: what a CMS looked like when you started out at Gamespot, when I was working at Maximum
[02:25] SPEAKER: PC is not what you would expect.
[02:28] SPEAKER: Like they were not good.
[02:30] SPEAKER: Like I became acquainted with the term R-Sync like 20 years before my recent like Unix open
[02:36] SPEAKER: source stuff, because the original Gamespot CMS like exposed to the R-Sync process as
[02:43] SPEAKER: assets for being pushed to the website.
[02:45] SPEAKER: We had producers, we had people who, whose entire jobs it was to take articles and screenshots
[02:50] SPEAKER: and turn them into articles on the thing because even the CMS that was built by the corporation
[02:56] SPEAKER: for that was too technical for normal people to do.
[02:59] SPEAKER: Well, it's funny.
[03:00] SPEAKER: We always used to laugh at you all for having people that did that work for you.
[03:02] SPEAKER: Cause we had in magazine world, we had to do that cause they didn't care enough to put
[03:05] SPEAKER: employees on, you know, that, that kind of work.
[03:08] SPEAKER: But like.
[03:09] SPEAKER: Well, I mean, I, a, because I was mostly doing previews where we were like trying to compete
[03:14] SPEAKER: to be first with all the information, B just because it's me and my personality, I actually
[03:19] SPEAKER: went and learned all that stuff myself, the stuff the producers did and stopped sending
[03:24] SPEAKER: content to them and just started doing all the markup and stuff myself, just to get the,
[03:28] SPEAKER: cause you know, you had to send it over there and they might have a backlog and you might
[03:31] SPEAKER: ask them to like, Hey, this is priority.
[03:33] SPEAKER: Can you get this done quicker?
[03:34] SPEAKER: But like it was way faster to just do it myself.
[03:36] SPEAKER: But, but I mean, it's important to note, we're not talking about like typing it into a field
[03:41] SPEAKER: and uploading some pictures, like you had to size, you had to make the thumbnails, you
[03:45] SPEAKER: had to size all the images manually.
[03:48] SPEAKER: You had to, you had to often place HTML tags in for the images that referenced where the
[03:54] SPEAKER: image was going to be on the server when you put it there, because it probably wasn't there
[03:58] SPEAKER: yet.
[03:59] SPEAKER: And like there was a bunch, like it was weird when I was working at ours, we used front
[04:03] SPEAKER: page, which was a really funny, but I think about it now, but like it was, it was a WYSIWYG
[04:09] SPEAKER: editor and it would handle all the uploads, but it was also really stupid because if two
[04:14] SPEAKER: people edited the front page file, there was no way to lock the file on the server side.
[04:18] SPEAKER: So if two people were in that file at the same time, whoever saved glass would erase
[04:22] SPEAKER: the other person's work.
[04:23] SPEAKER: Had that experience many times.
[04:25] SPEAKER: Yeah.
[04:26] SPEAKER: So, yeah, I think we've talked about it before, but getting to WYSIWYG media and seeing the
[04:31] SPEAKER: editor that those guys had built, it was like, it was like a top five in my career moment
[04:36] SPEAKER: of like, Holy shit, this is the future.
[04:38] SPEAKER: Like, Oh my God, I'm working with some incredible people.
[04:40] SPEAKER: That was not to say, not to say that there were not a lot of incredible people at GameSpot,
[04:45] SPEAKER: but like corporate bureaucracy and, you know, like building new things at a giant corporation
[04:50] SPEAKER: is a very different thing than it is a little startup.
[04:53] SPEAKER: Well, yeah.
[04:54] SPEAKER: And, and it's funny cause I, I think I actually made fun of when, when the AOL Engadget folks
[05:01] SPEAKER: left AOL to go start the Verge.
[05:05] SPEAKER: And I think it was Josh Topolski was like, this is, we, one of the things that made us
[05:08] SPEAKER: want to move is we looked at their CMS and it was the best CMS we'd ever seen.
[05:11] SPEAKER: And I was like, okay, so I would never say that publicly cause you sound like a doofus,
[05:16] SPEAKER: but also I totally get it because I had the same exact reaction cause we'd moved from
[05:20] SPEAKER: Drupal, which was like relatively up to date and current and like WYSIWYG and you could
[05:24] SPEAKER: drag and drop images and the whole thing in the editor.
[05:28] SPEAKER: But seeing what, what Dave and Ethan and Andy and, and all those and Koontz and all those
[05:32] SPEAKER: guys had made at WYSIWYG was a whole different world.
[05:36] SPEAKER: My corn, shout out to my corn too.
[05:37] SPEAKER: Don't forget my corn.
[05:38] SPEAKER: Yeah.
[05:39] SPEAKER: And the people over there making that stuff go up, that was an amazing tech shop.
[05:42] SPEAKER: Yeah.
[05:43] SPEAKER: It was, it was well, and they were building it good because they wanted it like a lot
[05:48] SPEAKER: of times in corporate America at that time, especially you'd get something that was good
[05:52] SPEAKER: enough.
[05:53] SPEAKER: And they just built something that was good because, because also it was user because
[05:56] SPEAKER: users used it too.
[05:57] SPEAKER: Like is that like the ultimate dog fooding basically that like, and in fact I remember
[06:02] SPEAKER: that being a selling point when I got there, it was like, Hey, the editor you guys are
[06:05] SPEAKER: putting using to put content on the website is the same editor repeat like everybody else
[06:09] SPEAKER: is going to use forum posts and Wiki content and like, yeah.
[06:12] SPEAKER: Well, it's, it's one of those things.
[06:14] SPEAKER: It's funny.
[06:15] SPEAKER: We had the same thing happen with the Anacrusis.
[06:16] SPEAKER: Like we, we built the game and then we added mod tools after it had been out for about
[06:20] SPEAKER: six months.
[06:21] SPEAKER: Right.
[06:22] SPEAKER: So that, so that people could download a special version of it in real ed and make hats and
[06:26] SPEAKER: player skins and all that stuff.
[06:28] SPEAKER: And the moment we built a pipeline into the mod tool side to add hats to the game, adding
[06:34] SPEAKER: hats to the game became infinitely easier for the artists.
[06:37] SPEAKER: And all of a sudden they, they were like, I'm going to make a Valentine's day hat this
[06:40] SPEAKER: year.
[06:41] SPEAKER: I'm going to make some Christmas hats and, and like, you know, the making the user facing
[06:46] SPEAKER: pipeline, something that normal be like, I have put hats into our, into the game, right?
[06:51] SPEAKER: So I was able to go to sketch fab, download some assets and put a texture on them and
[06:56] SPEAKER: smack them up in the game.
[06:57] SPEAKER: And they have blinky lights in the whole thing.
[07:00] SPEAKER: It's it's making something that's user facing and accessible makes it easier and faster
[07:05] SPEAKER: for everyone now, I will say users weren't allowed to update podcasts, the whiskey media
[07:11] SPEAKER: thing.
[07:12] SPEAKER: And when I asked Dave to put an hour, minutes and seconds timer, instead of just making
[07:16] SPEAKER: me calculate how long a two hour and 20 minute podcast was in seconds, he said, well, you
[07:20] SPEAKER: do that once a week.
[07:21] SPEAKER: And Ryan does that once a week and Rory does that once a week.
[07:25] SPEAKER: So that's three people's time.
[07:26] SPEAKER: It takes about 20 seconds to do it.
[07:27] SPEAKER: It would take me a day to put that in.
[07:30] SPEAKER: So you're going to keep calculating hours, minutes and seconds and seconds.
[07:34] SPEAKER: I get it.
[07:35] SPEAKER: Yeah.
[07:36] SPEAKER: Yeah.
[07:37] SPEAKER: Real quick.
[07:38] SPEAKER: Two things.
[07:39] SPEAKER: Is this the Santa Cruz's back end?
[07:40] SPEAKER: Is that something that like comes along with unreal engine or is that something that you
[07:43] SPEAKER: all built yourself entirely?
[07:45] SPEAKER: So we work with a partner called Excel byte.
[07:48] SPEAKER: They handle they help us with matchmaking and they run turn servers and stuff like that.
[07:52] SPEAKER: They also host the so in order to do cross platform matchmaking, you have to have some
[08:00] SPEAKER: place that has a data store that lets you connect an Xbox accounts and steam accounts.
[08:05] SPEAKER: And they do all of that stuff.
[08:07] SPEAKER: That's the reason we started out working with them.
[08:09] SPEAKER: And then they have a bunch of other things that you can add on to that service.
[08:14] SPEAKER: It's interesting because anybody that does cross platform matchmaking, you're going to
[08:17] SPEAKER: have to have a third party account, which means there's gtpr requirements and ccpr requirements
[08:22] SPEAKER: from California, which, you know, it's nice to have somebody manage.
[08:26] SPEAKER: It also means that you have to check that little box on steam that says this has a third
[08:29] SPEAKER: this requires a third party account.
[08:32] SPEAKER: Even if you don't ever expose the account to users, which we don't.
[08:36] SPEAKER: So people get upset and think you're going to make them do like an account for a service
[08:39] SPEAKER: that they're not enthusiastic about.
[08:41] SPEAKER: Well, that's a big ouch.
[08:42] SPEAKER: I have my other question.
[08:43] SPEAKER: So it sounded like, did I understand correctly?
[08:45] SPEAKER: You were just editing a big, raw JSON form.
[08:48] SPEAKER: It's not taking all those values and exposing them as nice, tidy little web UI elements.
[08:53] SPEAKER: It is an enormous JSON form.
[08:56] SPEAKER: Hey, that's good to, okay, it sounds, it sounds like the CMS has a little way to go.
[09:00] SPEAKER: Well, you know, all I know is that this week's weekly challenge is called no safety and it
[09:06] SPEAKER: means that the airlocks are malfunctioning.
[09:09] SPEAKER: So you have to hold off giant hordes of aliens while you wait for the doors to open before
[09:14] SPEAKER: you can get to safety.
[09:15] SPEAKER: Also it's all maps where the airlocks are really super scary.
[09:19] SPEAKER: So good luck.
[09:20] SPEAKER: Big thanks to Jason.
[09:22] SPEAKER: Shout out.
[09:51] SPEAKER: Welcome to Brad and Will Made a Tech Pod.
[09:54] SPEAKER: I'm Will.
[09:55] SPEAKER: I'm Brad.
[09:56] SPEAKER: Hello.
[09:57] SPEAKER: Hello.
[09:58] SPEAKER: Um, this week we got something a little bit unusual planned.
[10:01] SPEAKER: Do we?
[10:02] SPEAKER: I mean, it's, it's not, it's not, we've done, we've done, we've, we've worked in this realm
[10:07] SPEAKER: before, but this is a new twist on the, on the, on the taste that we've done.
[10:10] SPEAKER: We had, let's say two to three topics that we didn't think would sustain a full episode.
[10:17] SPEAKER: They're kind of, they're kind of, uh, follow ups to things we've done in the past.
[10:21] SPEAKER: Talked about in the past or updates, and we wanted to kind of delve in and, uh, you know,
[10:28] SPEAKER: let people know what's going on with some of the stuff that we've talked about in recent
[10:31] SPEAKER: weeks, either on the patron episode or on Q and a or other places.
[10:35] SPEAKER: Yeah.
[10:36] SPEAKER: Some of, some of the stuff is, is, is, is our topic.
[10:39] SPEAKER: Some of these are topics, subject verb agreements.
[10:42] SPEAKER: Topics are hard.
[10:43] SPEAKER: Uh, that, that we've, that we've kind of only touched on casually, like, like, like we're
[10:47] SPEAKER: gonna talk about wire guard here cause we've both been working with that a good bit lately.
[10:50] SPEAKER: But like, I think we, I think we only casually talked about that on the patron episode this
[10:54] SPEAKER: month.
[10:55] SPEAKER: I don't think we've ever even covered that one.
[10:56] SPEAKER: I, in the past, I have said that wire guard is good, which I stand by.
[11:00] SPEAKER: Yes.
[11:01] SPEAKER: I've, I've always known it was good conceptually, but I never had a functional enough set up
[11:04] SPEAKER: to like say so in practice, but now I do and it rules.
[11:08] SPEAKER: Yeah.
[11:09] SPEAKER: Um, for people who don't know, wire guard is a lightweight VPN that you can run to give
[11:13] SPEAKER: you an easy way to connect to your house safely so that you don't have to have a bunch of
[11:16] SPEAKER: ports with services that may or may not be super secure exposed to the internet.
[11:20] SPEAKER: Yeah.
[11:21] SPEAKER: Um, what else were we talking about today?
[11:23] SPEAKER: Uh, well, so, so I did my fourth or fifth long, maybe sixth now long road trip with
[11:29] SPEAKER: the, with the bolt.
[11:30] SPEAKER: We're two and a half years into having this thing and I wanted to kind of, the last time
[11:34] SPEAKER: we talked about it was a fair amount of time ago and things have changed a little bit.
[11:37] SPEAKER: Things are, some things are better, some things are worse.
[11:39] SPEAKER: It was interesting cause this time we drove during the hottest summer on record through
[11:44] SPEAKER: areas that were 120 degrees Fahrenheit, which is 50 degrees Celsius ish.
[11:50] SPEAKER: It's pretty hot.
[11:51] SPEAKER: Uh, so we're gonna talk about that.
[11:52] SPEAKER: Talk about what we've learned.
[11:53] SPEAKER: I have some questions for the community and I were, you know, like I said, we're two and
[11:57] SPEAKER: a half years into a three year lease on this car.
[11:59] SPEAKER: I think at this point, both my wife and I are pretty committed to the electric car lifestyle.
[12:03] SPEAKER: Sure.
[12:04] SPEAKER: I didn't, okay.
[12:05] SPEAKER: I didn't realize it was decision time.
[12:06] SPEAKER: Yeah.
[12:07] SPEAKER: And we, and we're, we're thinking about what's next and I want to get a little feedback from
[12:10] SPEAKER: the audience on that.
[12:11] SPEAKER: And what else you got, Brad?
[12:13] SPEAKER: Well, you proposed this, but I have, I have material here, a little coffee update couple
[12:17] SPEAKER: weeks after the cough.
[12:18] SPEAKER: I've I'm a couple of weeks into daily cold brewing and I thought I might briefly describe
[12:23] SPEAKER: where I'm at with that and how it's going.
[12:26] SPEAKER: Yeah.
[12:27] SPEAKER: I, um, people really liked the coffee episodes.
[12:28] SPEAKER: We'll do some more food tech if, if folks are into it.
[12:31] SPEAKER: Yeah.
[12:32] SPEAKER: I was, I was, I was pleased, pleasantly surprised at the response to the coffee episode.
[12:36] SPEAKER: Um, I, uh, have been people that have asked about, uh, the bypass brewers, which we talked
[12:43] SPEAKER: about in that episode a little bit.
[12:44] SPEAKER: I am waiting, I've looked at what's available and for what I make, I'm looking at, I'm waiting
[12:50] SPEAKER: for the next level pulser, uh, brewer to come available, which is like a single serving
[12:54] SPEAKER: bypass brewer.
[12:55] SPEAKER: And when we do that, we'll, we'll, I'll report when it, when that comes out, it's supposed
[12:58] SPEAKER: to be released in August, um, which is now.
[13:01] SPEAKER: So when that's out, I'll, um, I'll update it and I'll, I'll, I'll get one and update
[13:06] SPEAKER: you all.
[13:07] SPEAKER: Oh, thanks.
[13:08] SPEAKER: You're good.
[13:09] SPEAKER: I hope.
[13:10] SPEAKER: Hopefully updates are good.
[13:11] SPEAKER: Cause we're about to do a bunch.
[13:12] SPEAKER: Yeah.
[13:13] SPEAKER: Let's get, let's get to it.
[13:14] SPEAKER: What's what's going on.
[13:15] SPEAKER: Uh, so, so you're, okay.
[13:16] SPEAKER: So for people, I don't even think we need to get into what we talked about the patron
[13:18] SPEAKER: episode, but yeah, no, I I've been using WireGuard at home for like three years now as part of
[13:25] SPEAKER: my home assistant install.
[13:26] SPEAKER: Oh wow.
[13:27] SPEAKER: I thought you just set it up recently.
[13:28] SPEAKER: No, no, no.
[13:29] SPEAKER: I set it up, um, before I went to Palm desert the first time in 2021 so that I could, um,
[13:35] SPEAKER: so I could connect to, uh, my server and stuff inside the house without having to open a
[13:40] SPEAKER: bunch of scary ports.
[13:42] SPEAKER: Um, and it's, it's been absolutely flawless.
[13:44] SPEAKER: I use it almost the only time I messed up was when I, when AT&T decided they were going
[13:48] SPEAKER: to reset my router and I didn't turn the port back on for it.
[13:51] SPEAKER: Um, and then that was a problem.
[13:53] SPEAKER: It turns out.
[13:54] SPEAKER: Yeah.
[13:55] SPEAKER: Yeah.
[13:56] SPEAKER: It's pretty set and forget.
[13:57] SPEAKER: I would say from what I've seen so far.
[13:58] SPEAKER: Um, so I should we talk about just the basics of what it is a little bit, I guess.
[14:02] SPEAKER: What is your, what is your history with VPNs?
[14:04] SPEAKER: My, my history with VPNs is like every company, every big company I have worked for has required
[14:09] SPEAKER: one of some nature and they all suck to varying degrees and are a huge pain in the ass.
[14:14] SPEAKER: See, this is where future and, uh, and real companies have separated each other and future.
[14:20] SPEAKER: They were like, eh, that's probably fine.
[14:22] SPEAKER: Just open up supports.
[14:23] SPEAKER: Wow.
[14:24] SPEAKER: I could call the up until about 2005 I could call the IT guy and be like, Hey, I need,
[14:28] SPEAKER: I need port.
[14:29] SPEAKER: Uh, I need a public facing IP address with port 80 on it.
[14:33] SPEAKER: And they'd be like, Oh yeah, sure.
[14:34] SPEAKER: Okay.
[14:35] SPEAKER: I gotcha.
[14:36] SPEAKER: Yeah.
[14:37] SPEAKER: You know, something that also just occurred to me, I say every company I have worked for,
[14:40] SPEAKER: but actually they're all, all of the big companies I've worked for have just been various permutations
[14:44] SPEAKER: of the same big company.
[14:46] SPEAKER: That's true.
[14:47] SPEAKER: Yeah.
[14:48] SPEAKER: Different incarnations.
[14:49] SPEAKER: Different ownership and names.
[14:50] SPEAKER: Uh, but, but there was always, there was always like some very annoying like Cisco VPN client
[14:55] SPEAKER: you had to install on your work machine or something that you had to use to access any
[14:58] SPEAKER: resources at work.
[14:59] SPEAKER: So like VPN became synonymous with something that was an extreme pain and like, you know,
[15:05] SPEAKER: it would like the connection was not stable.
[15:07] SPEAKER: It would like the computer went to sleep, it might drop or something like that.
[15:10] SPEAKER: It was extremely, and it was slow.
[15:11] SPEAKER: Yeah.
[15:12] SPEAKER: Wasn't, it was never performant.
[15:13] SPEAKER: We used IPSEC for a long time at the end days of future and it was always slow.
[15:19] SPEAKER: Um, so, so WireGuard is like pretty new.
[15:22] SPEAKER: It's like what, five, six, seven years, it's sometime in the last decade.
[15:28] SPEAKER: Yeah.
[15:29] SPEAKER: Yeah.
[15:30] SPEAKER: Um, it's a much simpler VPN.
[15:31] SPEAKER: It's uh, it kind of acts more like the way SSH uses public and private key pairs, um,
[15:38] SPEAKER: where all it's doing is encrypting the traffic going back and forth between two end points.
[15:42] SPEAKER: There's no server concept.
[15:43] SPEAKER: Every, everything is just a peer quote unquote.
[15:46] SPEAKER: Um, and point to point, there's no, there's no multi-point, right?
[15:49] SPEAKER: Yes.
[15:50] SPEAKER: Yeah.
[15:51] SPEAKER: So you can do things like, and we'll get into it.
[15:52] SPEAKER: This is what I've done with it.
[15:53] SPEAKER: You can do things where like you have a single peer behind your firewall, your router, and
[15:57] SPEAKER: you can't access your whole LAN where that WireGuard peer is acting as sort of a gateway
[16:01] SPEAKER: to everything else.
[16:02] SPEAKER: Yeah.
[16:03] SPEAKER: But as far as WireGuard is concerned, every connection is just two machines talking to
[16:07] SPEAKER: each other.
[16:08] SPEAKER: Um, yeah, all it's doing is encrypting the traffic back and forth based on validating
[16:13] SPEAKER: those public and private keys.
[16:14] SPEAKER: So as long as that, that is set up, everything just works.
[16:18] SPEAKER: And it's not like, like, I don't know what kind of VPN you used, what the, the, the IPSec
[16:23] SPEAKER: like IPSec was used in the future.
[16:25] SPEAKER: It's like, I don't know if that was wrapped in any like corporate client or, or anything
[16:30] SPEAKER: like that.
[16:31] SPEAKER: But like, like, I guess, I guess what I'm trying to explain, and it's been so long since
[16:34] SPEAKER: I used some of those old VPNs, it's hard to characterize, but you always thought of it
[16:38] SPEAKER: as like an active connection, something that had to be maintained, you know, something
[16:41] SPEAKER: you had to like, click a connect button and like go through a login and like hope the
[16:45] SPEAKER: connection stayed up.
[16:46] SPEAKER: And yeah, it almost worked like a modem login for a lot of ways.
[16:50] SPEAKER: Yes.
[16:51] SPEAKER: That's, that's what I'm trying to get at.
[16:52] SPEAKER: Like WireGuard feels much more passive to me and in the background and seamless and
[16:55] SPEAKER: just there and not something you actually have to think about.
[16:58] SPEAKER: Yeah.
[16:59] SPEAKER: Like if you put it on your phone or your iPad or whatever, you can literally set it up as
[17:03] SPEAKER: a VPN entry in iOS and then just flip the VPN toggle on the settings page and it'll
[17:09] SPEAKER: run everything through that, through that connection.
[17:12] SPEAKER: Right.
[17:13] SPEAKER: And if things are set up well enough, it's performant enough and low overhead enough
[17:16] SPEAKER: that you can kind of leave that connected all the time.
[17:18] SPEAKER: I often forget to turn it off when I don't need it anymore and don't notice for days.
[17:23] SPEAKER: Yeah.
[17:24] SPEAKER: So I'm, I'm never going to turn it off.
[17:25] SPEAKER: I think.
[17:26] SPEAKER: Really?
[17:27] SPEAKER: I think I'm, I think I'm getting to the point where I am just going to leave it on, on my
[17:29] SPEAKER: phone all the time.
[17:30] SPEAKER: Well, I mean, that's kind of a thing now.
[17:32] SPEAKER: Like if you subscribe to Apple's all in one, you know, they're, they're souped up iCloud
[17:38] SPEAKER: that has music and games and Apple arcade and all that stuff, then they'll give you
[17:44] SPEAKER: an always on VPN connection to mask your traffic to the, to the larger, to wherever you're
[17:52] SPEAKER: connected through.
[17:53] SPEAKER: Interesting.
[17:54] SPEAKER: That's cool.
[17:55] SPEAKER: I did not know that.
[17:56] SPEAKER: Yeah.
[17:57] SPEAKER: All the the also there's like an official WireGuard client for, for Mac OS for windows,
[18:00] SPEAKER: for iOS, et cetera, et cetera, but they all let you set up a kind of inclusion exclusion
[18:07] SPEAKER: rules for connections, basically like say if I connect to any of these specific wifi
[18:14] SPEAKER: SSIDs connect automatically, or if I connect to any wifi that is not one of these SSIDs
[18:20] SPEAKER: connect automatically.
[18:21] SPEAKER: If I go onto cellular connect, you know, you know what I mean?
[18:24] SPEAKER: So like what I'm, what I'm saying is like, I can basically tell it like, okay, if my
[18:28] SPEAKER: iPhone is on my home wifi, don't use it obviously.
[18:31] SPEAKER: Yeah.
[18:32] SPEAKER: But the second I go out the door and that wifi disconnects and I dropped a cellular,
[18:35] SPEAKER: it just in those two just connect over.
[18:37] SPEAKER: Yeah.
[18:38] SPEAKER: It's really nice.
[18:39] SPEAKER: It's cool.
[18:40] SPEAKER: The, the, the, the, and the reason you would do this, there's two reasons you would do this.
[18:44] SPEAKER: One is so that if you're on a public wifi, people can't snoop on your traffic, whatever
[18:48] SPEAKER: you're doing.
[18:49] SPEAKER: Cause your traffic all goes through your home network at that point too, is so that you
[18:53] SPEAKER: can access stuff inside your home network while you're not at home.
[18:55] SPEAKER: So whether it's like a home assistant server without having to have the ports open, whether
[18:59] SPEAKER: it's you know, your, your Plex server, whether it's being able to remote into your machine,
[19:03] SPEAKER: whether it's be able to access an SMB share on a windows machine or even a, you can do
[19:07] SPEAKER: all of that stuff with the, with the remote client on the, on the, on the VPN.
[19:11] SPEAKER: Okay.
[19:12] SPEAKER: So what are you, what are you running?
[19:13] SPEAKER: So I'm running this on a home assistant plugin.
[19:14] SPEAKER: The install for that was literally going to the home assistant community store and searching
[19:19] SPEAKER: for WireGuard and pressing install.
[19:21] SPEAKER: And then I had to copy, I think I had to copy two files.
[19:25] SPEAKER: One was a configuration file.
[19:27] SPEAKER: That's like a text config with the SSH key pairs.
[19:30] SPEAKER: And then the other one is just a QR code that I aim my phone at and it, and it just magically
[19:35] SPEAKER: sets up the connection inside the WireGuard app.
[19:37] SPEAKER: Yeah.
[19:38] SPEAKER: There are a lot of different ways to set this up.
[19:39] SPEAKER: I mean, you can do it like if you really want to get down in the weeds, you can set it up
[19:44] SPEAKER: on just a basic clinics machine, but then you have to like, you know, make sure the
[19:47] SPEAKER: kernel module loads and do a bunch of configuration and stuff, but there are a bunch of much easier
[19:51] SPEAKER: ways to set it up.
[19:53] SPEAKER: A lot of people on our discord really like tail scale, which is a commercial service
[19:57] SPEAKER: that they use WireGuard at the core.
[20:00] SPEAKER: I've never used it, but I think they actually extend the concept and basically make like
[20:04] SPEAKER: a mesh network of WireGuard peers is my understanding.
[20:08] SPEAKER: It is, it is a commercial service, but they have a free tier.
[20:11] SPEAKER: Just, just to be clear, this isn't a sponsored conversation.
[20:14] SPEAKER: No, no, no, no, no.
[20:15] SPEAKER: This is, this is, this is me having gone off the discord a bunch of times talking about
[20:19] SPEAKER: WireGuard and a bunch of people saying like, just use tail scale.
[20:21] SPEAKER: Like it's super easy.
[20:23] SPEAKER: You should just use that.
[20:24] SPEAKER: And I'm like, oh, but I want to do it the hard way.
[20:26] SPEAKER: Yes.
[20:27] SPEAKER: So we have not used the service or had any interaction with it, but that is the recommendation.
[20:32] SPEAKER: The free tier gives you up to three users, up to a hundred devices.
[20:35] SPEAKER: So there's, there's that if you want to check that out, there's if you, if you have a raspberry
[20:40] SPEAKER: pie, you want to run this on, there's something called pie VPN, which is a little open source
[20:45] SPEAKER: project that's I think it's kind of like a wizard sort of step through a bunch of choices
[20:51] SPEAKER: type configuration and just go through it that way.
[20:54] SPEAKER: Is there a pie?
[20:55] SPEAKER: Is it part of the pie installer, pie OS installer?
[20:57] SPEAKER: No, it's a, it's a separate thing.
[20:59] SPEAKER: You set it up kind of like pie hole.
[21:00] SPEAKER: Okay.
[21:01] SPEAKER: I mean, they're, they're totally unrelated, but it's a similar kind of thing.
[21:04] SPEAKER: So you install raspberry pie OS and then grab a package from a repository someplace.
[21:09] SPEAKER: It's a couple of command line commands, but they tell you exactly how to do it.
[21:13] SPEAKER: If you just go to pie VPN dot IO, I haven't tried this one either, but this was another
[21:16] SPEAKER: recommendation a lot of people had of like, oh, if you want to run on a pie this will
[21:21] SPEAKER: make that pretty easy.
[21:23] SPEAKER: Okay.
[21:24] SPEAKER: So if you want to run on a pie VPN more and more router options are starting to have it
[21:28] SPEAKER: built in.
[21:29] SPEAKER: Yeah.
[21:30] SPEAKER: The, the, the, the dream OS ubiquity stuff, you can download it as a plugin as I recall.
[21:35] SPEAKER: Okay.
[21:36] SPEAKER: So yeah.
[21:37] SPEAKER: Pretty much all the, like, so all, all the sort of DIY router OS's that people use like
[21:42] SPEAKER: PF sense, open sense via OS.
[21:44] SPEAKER: Those all have it built in, tightly integrated.
[21:48] SPEAKER: I don't know what the state of like consumer level routers is yet.
[21:51] SPEAKER: I don't know if any, any of the net gears or, you know, the TP link archers or anything
[21:55] SPEAKER: are starting to include it or not.
[21:57] SPEAKER: I haven't.
[21:58] SPEAKER: So the, the mesh, the Google mesh ones don't have it.
[22:02] SPEAKER: I have used those recently cause my parents have those.
[22:05] SPEAKER: Yeah.
[22:06] SPEAKER: I haven't looked at I haven't looked at the other third party routers and the long consumer
[22:10] SPEAKER: level routers at a long time.
[22:11] SPEAKER: Yeah.
[22:12] SPEAKER: I'm guessing, I'm guessing none of, none of them have it built in like out of the box or
[22:16] SPEAKER: you'd have to do something weird, like run like, you know, tomato or open WRT or something
[22:22] SPEAKER: like that.
[22:23] SPEAKER: Open WRT is a big one.
[22:24] SPEAKER: I want to say there might be another, yeah.
[22:27] SPEAKER: Like if you flash a third, like an open source thing, you can do it that way.
[22:31] SPEAKER: The other option is instead of, so if you do it on the, on the router, it simplifies
[22:34] SPEAKER: a lot of the routing and so forth because the routers already doing all the routing.
[22:39] SPEAKER: If your router can't do it, you can run it behind your firewall on something like I'm
[22:42] SPEAKER: doing it on a PI four.
[22:43] SPEAKER: Yeah, the only, the only catch of running it behind your firewall on a PI four is that
[22:47] SPEAKER: you have to have different private IP addresses for each network or else the routing gets
[22:53] SPEAKER: weird.
[22:54] SPEAKER: So like if you, if you have, if you're on a way network, that's one 92 to one six eight
[22:58] SPEAKER: dot one dot something in the home network is one 92 to one six eight dot one dot something.
[23:02] SPEAKER: Sometimes that can be weird.
[23:03] SPEAKER: Sometimes it works itself out.
[23:04] SPEAKER: So I, I, I felt a little smug because I changed my, I changed my, my lands address range like
[23:12] SPEAKER: two or three years ago for this exact reason.
[23:14] SPEAKER: Even though I didn't have VPN then to 10, 15 or something.
[23:17] SPEAKER: Yeah.
[23:18] SPEAKER: Because you can't be, you can't be on somebody else's wifi that is using the same address
[23:21] SPEAKER: range as yours.
[23:22] SPEAKER: And like you said, every router out of the box uses one 92 dot one 68 because the addresses
[23:29] SPEAKER: will collide.
[23:30] SPEAKER: You'll have addresses, you'll have the same address happening on their land and somewhere
[23:33] SPEAKER: on your land and it won't go what to do with it.
[23:35] SPEAKER: So I, again, I haven't tried any of the, like the PI VPNs, tail scales, stuff like that
[23:41] SPEAKER: that handles all that stuff.
[23:42] SPEAKER: I assume they help automate some of that stuff as well.
[23:47] SPEAKER: But I believe that the home assistant set up when it does it, it's, it looks at what
[23:52] SPEAKER: your IP address is internally and sets up a second, a different range for the, for the
[23:57] SPEAKER: wire guard.
[23:58] SPEAKER: And just to be clear, I think you can do, I think you can have, it's, it's that the
[24:03] SPEAKER: wire guard and the adjacent networks can't be the same.
[24:06] SPEAKER: I think that the, the two networks you're tunneling between may be able to actually be the same because they get translated through the wire guard address.
[24:13] SPEAKER: Yes.
[24:14] SPEAKER: That might be right.
[24:15] SPEAKER: If you're, I've, I've been doing a lot of networking set up with the stuff I, I learned
[24:19] SPEAKER: what IP masquerading is finally in this process.
[24:23] SPEAKER: Yeah.
[24:24] SPEAKER: That was, that was a big one that let's, that, that, that saved us from IP before pain a long
[24:28] SPEAKER: time ago.
[24:30] SPEAKER: I finally made myself learn exactly how a subnet mask works finally, permanently for
[24:35] SPEAKER: all time.
[24:36] SPEAKER: You've got to just, just keep adding zeros until it works.
[24:39] SPEAKER: That's the plan.
[24:40] SPEAKER: Yes.
[24:41] SPEAKER: Uh, anyway, I had, um, rod bun, who was my first boss out of college, sat down with me
[24:46] SPEAKER: in front of a chalkboard at the university of Tennessee at the biology department one
[24:49] SPEAKER: afternoon.
[24:50] SPEAKER: Cause I was like, I don't understand how IP addresses work.
[24:52] SPEAKER: And he was like, okay, here you go.
[24:54] SPEAKER: And he wrote down an IP address and then he put the subnet mask underneath it.
[24:59] SPEAKER: And he's like, and he showed, he, he did four different IP addresses in four different subnet
[25:03] SPEAKER: masks.
[25:04] SPEAKER: So the way the subnet, the subnet mask is basically saying, okay, we're limiting this
[25:08] SPEAKER: block of numbers to the same block, right?
[25:10] SPEAKER: So if it's a two 55, that means the, if you have one 92 to one six eight dot one dot whatever,
[25:16] SPEAKER: then two 55 is saying in the first set of numbers is saying that one night that it's
[25:20] SPEAKER: always going to be one 92 to 55 in the second set of numbers saying it's always going to
[25:23] SPEAKER: be one six eight to 55 in the third set of numbers is saying it's always going to be
[25:27] SPEAKER: the same number there.
[25:29] SPEAKER: So, if you put zero there, it can be anywhere from zero to 255 and you can change that number
[25:35] SPEAKER: as, as, as you, as you see fit 255 means that, that, that octet, that, that number is fixed.
[25:43] SPEAKER: Zero means it can be anything.
[25:45] SPEAKER: It gets harder because there are different types of notation to express the same concept.
[25:49] SPEAKER: Like there's the one you're talking about, but there's a slash 24, there's a slash something
[25:53] SPEAKER: like it, I, the thing I finally clued into is that that slash whatever is the number
[25:58] SPEAKER: of bits, which is why you generally see it as a multiple of eight because an IPv4 address
[26:04] SPEAKER: is four eight bit numbers.
[26:06] SPEAKER: So if it's like slash 24, that means three of the four octets are fixed on the last one
[26:11] SPEAKER: generally is not, or whichever one is denoted by zero.
[26:14] SPEAKER: Yeah.
[26:15] SPEAKER: Yeah.
[26:16] SPEAKER: And I think it has, I mean, I guess it could be one of the other ones, but the routing
[26:19] SPEAKER: won't work right then.
[26:20] SPEAKER: Cause you've accepted the router to be one anyway, it gets, it gets weird cause you can
[26:24] SPEAKER: have non-standard, you can have like slash 20, which means like part of one of the, we
[26:30] SPEAKER: shouldn't get into it.
[26:31] SPEAKER: Yeah.
[26:32] SPEAKER: No, this is a different, this is a different episode.
[26:33] SPEAKER: I did not go that far in understanding it.
[26:34] SPEAKER: Hopefully this is what this is communicating is that if you choose to set all this stuff
[26:37] SPEAKER: up yourself, you're going to have to learn a lot of pretty low level networking stuff.
[26:42] SPEAKER: Yeah.
[26:43] SPEAKER: My advice is just do the home assistant install.
[26:45] SPEAKER: It's really easy.
[26:46] SPEAKER: Yeah.
[26:47] SPEAKER: So I think just about anybody should choose one of the easier options to set this stuff
[26:51] SPEAKER: up.
[26:52] SPEAKER: What are your resources online to figure out how to do this stuff?
[26:56] SPEAKER: So I learned something interesting while I was away this time because I usually only
[26:58] SPEAKER: use the VPN on my phone.
[27:00] SPEAKER: I don't often use it on my computer, but I turned out to need, I need to do some typing
[27:04] SPEAKER: in terminals while I was gone.
[27:06] SPEAKER: And in order to do that, I set up the VPN on my home machine.
[27:12] SPEAKER: I'd only ever set up one tunnel before though.
[27:15] SPEAKER: And yeah, this makes perfect sense in retrospect, but you got to have a tunnel per machine if
[27:20] SPEAKER: you want them to be connected simultaneously.
[27:22] SPEAKER: Yes.
[27:23] SPEAKER: And when you tried to connect two machines to the same tunnel at the same time, unsurprisingly
[27:27] SPEAKER: weird things happened.
[27:28] SPEAKER: I bet.
[27:29] SPEAKER: Do by tunnel, you mean like literally both of the external clients were trying to be
[27:33] SPEAKER: the same peer with the same IP address and everything?
[27:35] SPEAKER: From the same IP address also.
[27:37] SPEAKER: Yeah.
[27:38] SPEAKER: Yes.
[27:39] SPEAKER: I can see that.
[27:40] SPEAKER: It was not like that.
[27:41] SPEAKER: I assume that the DNS mask on the, on the router on one end of the other just didn't
[27:45] SPEAKER: know what to do with what was coming in.
[27:48] SPEAKER: And like you'd get, you'd get, it would, it would work fine for about two minutes and
[27:53] SPEAKER: then it would be weird for a minute and then it would work fine for about two minutes and
[27:57] SPEAKER: it'd be weird for a minute.
[27:58] SPEAKER: Yeah.
[27:59] SPEAKER: I could see that being an issue.
[28:00] SPEAKER: Yeah.
[28:01] SPEAKER: Turning off VPN on the phone solved the problem immediately.
[28:02] SPEAKER: Yes.
[28:03] SPEAKER: I mean, I guess how you set this up is going to determine how much of this you even see,
[28:07] SPEAKER: but the, like the, the thing behind your firewall or your router, whatever it is at home that
[28:10] SPEAKER: you set this up on its configuration will have a different peer section for each client
[28:15] SPEAKER: you want to connect it to because they all need their own, their own settings.
[28:19] SPEAKER: So like I've got, I've got phone, tablet and laptop and each one of those is its own little
[28:24] SPEAKER: peer configuration.
[28:26] SPEAKER: That stuff is exposed on the home assistant one in a text file, just in the config file
[28:30] SPEAKER: for the home assistant install.
[28:32] SPEAKER: And it's, it's relatively easy to get into.
[28:34] SPEAKER: Got it.
[28:35] SPEAKER: Let's see here.
[28:37] SPEAKER: Yeah.
[28:38] SPEAKER: Like I probably shouldn't get into all of the very arcane routing stuff I had to do.
[28:43] SPEAKER: I'm, I'm just running this on a PI four.
[28:45] SPEAKER: Did you get multicast to work?
[28:46] SPEAKER: That was the other.
[28:47] SPEAKER: Okay.
[28:48] SPEAKER: So I haven't, I have not gotten there yet.
[28:49] SPEAKER: I've been looking at it and thinking about whether I actually want to go through that
[28:52] SPEAKER: pain or not what I, what I wanted, like the basic explanation of what I'm doing is I'm
[28:57] SPEAKER: running it on a PI four because my router is too slow.
[29:01] SPEAKER: Basically like the throughput on doing it on my edge router is just way too slow.
[29:05] SPEAKER: We should mention that like, like any VPN there's encryption here.
[29:08] SPEAKER: So the speed of the device you're running it on will determine what kind of throughput
[29:11] SPEAKER: you're getting because it has to crunch all that encryption.
[29:13] SPEAKER: Well, and also specifically if you have hardware support for the encryption that WireGuard
[29:17] SPEAKER: uses, which I think is AES 256, but I can't remember.
[29:20] SPEAKER: Yeah.
[29:21] SPEAKER: It uses a bunch of cryptography that is supposedly, you know, pretty, pretty selected for speed
[29:25] SPEAKER: for performance.
[29:26] SPEAKER: Yeah.
[29:27] SPEAKER: Anyway, the PI four I've got is like an order of magnitude faster than the edge router for
[29:32] SPEAKER: this.
[29:33] SPEAKER: So I'm doing it on the PI four, but that means the PI four has to be able to be the mediator
[29:38] SPEAKER: between the WireGuard network and my LAN.
[29:40] SPEAKER: So that took a bunch of routing stuff that I had to set up that I had never done before
[29:43] SPEAKER: and it didn't work.
[29:45] SPEAKER: And then it did.
[29:46] SPEAKER: This is a good project for learning how network stuff works.
[29:50] SPEAKER: That's exactly what this has been like.
[29:52] SPEAKER: Don't subject yourself to this if you don't care about any of this stuff, but I have absolutely
[29:55] SPEAKER: come away from this, like with a much better basic understanding of, of, of basic networking.
[30:02] SPEAKER: And I apologize.
[30:03] SPEAKER: It isn't, it isn't, it is a cha cha 20 for symmetric encryption, not AES.
[30:09] SPEAKER: It's fun.
[30:10] SPEAKER: If you go to wireguard.com, they straight up show you the white papers for how all this
[30:13] SPEAKER: stuff works.
[30:14] SPEAKER: If you just want to see the like academic description of all this stuff.
[30:19] SPEAKER: That's how, that's how encryption should work, Brad.
[30:21] SPEAKER: Yeah.
[30:22] SPEAKER: But it's extremely well-respected I should say like, like every networking professional
[30:26] SPEAKER: I know, or, you know, just generally the industry, this, this, this thing is seen as the gold
[30:31] SPEAKER: standard for security in this space, but absolutely all you have to do if you're running it behind
[30:38] SPEAKER: your firewall, not on the firewall, all you have to do is open one port to point to whatever
[30:43] SPEAKER: WireGuard is running on.
[30:44] SPEAKER: And my understanding is if the key pairs, the private and public keys are not in place
[30:49] SPEAKER: to do the authentication, it'll just reject any packet that comes from anything that doesn't
[30:53] SPEAKER: have, have those in place.
[30:55] SPEAKER: So it's, it's like the attack surface is extremely small.
[30:59] SPEAKER: Yep.
[31:00] SPEAKER: Yeah.
[31:01] SPEAKER: And like you said, one port, so, and it's a weird port that nobody, nobody else uses.
[31:04] SPEAKER: You can also configure it to be whatever port you want.
[31:06] SPEAKER: Yeah.
[31:07] SPEAKER: A couple other quick notes, you can in the configuration, you specify like how much,
[31:11] SPEAKER: have like what ranges of addresses you want to be WireGuarded, I guess I would say.
[31:17] SPEAKER: So you can do things like make a split tunnel where you say like, okay, all the, I want
[31:21] SPEAKER: the address range of my land to be part of this, but not anything else.
[31:25] SPEAKER: And that means that traffic to your house, to anything in your house goes through the
[31:29] SPEAKER: WireGuard encryption, but traffic out to the bigger internet just goes straight from you
[31:32] SPEAKER: to the internet.
[31:33] SPEAKER: So, cause otherwise you're tunneling all your traffic back and forth through your house
[31:36] SPEAKER: and you may not want that.
[31:38] SPEAKER: So, yeah.
[31:39] SPEAKER: So that's what I've actually done.
[31:40] SPEAKER: So it's just, just stuff to my house will go through the WireGuard.
[31:43] SPEAKER: Everything else will just go to the internet.
[31:44] SPEAKER: Oh, see, I want it all through the, through the WireGuard.
[31:47] SPEAKER: Certainly also valid.
[31:48] SPEAKER: And then that's what you would want if you were like, so I'm going to set up a different
[31:51] SPEAKER: profile to use in like airports and coffee shops.
[31:53] SPEAKER: Right.
[31:54] SPEAKER: And that one, you absolutely want everything to go through.
[31:57] SPEAKER: There's a, there's, this is a thing that people decide they want after they've learned how
[32:00] SPEAKER: IP sniffers work and sit on a public, public on a public wifi access point sometime and
[32:07] SPEAKER: see, just watch the traffic going, just watch it moving.
[32:10] SPEAKER: Yes.
[32:11] SPEAKER: I think we've, I think I mentioned this on the patron episode.
[32:13] SPEAKER: I became acquainted with TCP dump in the, in the process of setting all this stuff up.
[32:18] SPEAKER: And if you just run that thing on, even on your LAN and you see all the traffic flying
[32:23] SPEAKER: back and forth all the time, when you think nothing is actually happening, I can't even
[32:28] SPEAKER: what it looks like on, on a public wifi.
[32:30] SPEAKER: It's also stuff like DNS queries, right.
[32:32] SPEAKER: Like even stuff that's not necessarily like you, you, yeah.
[32:35] SPEAKER: Anyway, it's, it's weird internet of things, things talking to each other and stuff like
[32:39] SPEAKER: that.
[32:40] SPEAKER: But what else here one, one quick little thing I'll mention that that was a happy surprise
[32:45] SPEAKER: for me that I did not plan.
[32:48] SPEAKER: I use my pie holes here.
[32:49] SPEAKER: I use as the DNS servers for my network.
[32:52] SPEAKER: You have a redundant series of pie holes as DNS servers, as I recall.
[32:55] SPEAKER: Yes.
[32:56] SPEAKER: And what I've seen is all the clients on my land, see the two pie holes discreetly as
[33:02] SPEAKER: the DNS servers.
[33:03] SPEAKER: I use DHCP to, to distribute that here.
[33:06] SPEAKER: So when I set those up as the DNS and my wire guard config manually, and even think about
[33:12] SPEAKER: this working this way, but even when I don't do a full tunnel to my house, when I'm doing
[33:16] SPEAKER: that split tunnel where the internet traffic just goes straight out without going through
[33:20] SPEAKER: the wire guard.
[33:21] SPEAKER: Oh, you still get the DNS ad blocking on the pie hole.
[33:23] SPEAKER: My wire guard clients are still querying my pie holes at home as their DNS.
[33:27] SPEAKER: So I'm still getting the benefits of, of the ad, the DNS level ad blocking without, without
[33:32] SPEAKER: the traffic actually having to tunnel through my house.
[33:35] SPEAKER: So it's still faster.
[33:37] SPEAKER: You might've just convinced me to to set up the VPN to turn on automatically when I leave
[33:42] SPEAKER: this.
[33:43] SPEAKER: That is, that was the moment when I was like, you know what, I'm just gonna leave this on
[33:45] SPEAKER: all the time.
[33:46] SPEAKER: Yeah.
[33:47] SPEAKER: That's pretty good.
[33:48] SPEAKER: It's pretty good.
[33:49] SPEAKER: It's pretty good.
[33:50] SPEAKER: So yeah, this is yeah, it's, it's, it's, it's, it's one of the things that I like to do when
[33:51] SPEAKER: I leave the wire guard, yeah, it's, it's, it's, it's one of the things that I wasn't
[33:54] SPEAKER: sure was going to be useful, but I set it up cause it was easy and then I use it all
[33:57] SPEAKER: the time.
[33:58] SPEAKER: Yes.
[33:59] SPEAKER: Yes.
[34:00] SPEAKER: My, my setup was not easy.
[34:01] SPEAKER: Uh, I don't recommend it unless you really just want to throw yourself in the deep end
[34:04] SPEAKER: and figure out how networking stuff works.
[34:07] SPEAKER: I did.
[34:08] SPEAKER: The other thing is I'm going on a trip for a lot of August and did not have time to,
[34:12] SPEAKER: I want to replace this edge router, but I didn't have time to like pick a box and set
[34:16] SPEAKER: up an open, open sense or Vio S or something in the couple of weeks I had.
[34:20] SPEAKER: But I do have this PI four and then I found out, Oh, why are guard runs extremely fast
[34:23] SPEAKER: on a PI four?
[34:24] SPEAKER: I'm just going to do that.
[34:25] SPEAKER: Yeah.
[34:26] SPEAKER: Mine's, mine's running on a PI four and it's great.
[34:27] SPEAKER: It's running in a Docker container on home assistant and it's fantastic.
[34:30] SPEAKER: It does.
[34:31] SPEAKER: It doesn't require a lot of juice.
[34:32] SPEAKER: It turns out.
[34:33] SPEAKER: Yeah.
[34:34] SPEAKER: That's pretty awesome.
[34:35] SPEAKER: Okay.
[34:36] SPEAKER: Third big drive, uh, this summer we went to Palm desert, which is 500 miles almost exactly.
[34:44] SPEAKER: It's a nine and a half hour drive.
[34:47] SPEAKER: If there's light traffic, um, God, I didn't know it was that long with an hour and a half
[34:51] SPEAKER: of charging at least maybe two hours.
[34:53] SPEAKER: If it's slow.
[34:54] SPEAKER: Oh my God.
[34:55] SPEAKER: That is a long day.
[34:56] SPEAKER: I don't think I realized it was that big of a commitment.
[34:58] SPEAKER: It's a big drive.
[34:59] SPEAKER: Um, so the, we bought a bolt, uh, we released a bolt two and a half years ago now.
[35:06] SPEAKER: We talked about it around the time we got it.
[35:08] SPEAKER: Some things have changed.
[35:09] SPEAKER: The batteries degraded a little bit.
[35:10] SPEAKER: It's it's, it's still, you know, it's still a three charge drive down for the most part.
[35:16] SPEAKER: Um, is that just anecdotal or does it actually expose any kind of tools or any diagnostic
[35:21] SPEAKER: info where you can see that the runtime is less than it used to be?
[35:24] SPEAKER: It doesn't expose information, but I plugged an ODBD ODBE, uh, connector into the, to the,
[35:31] SPEAKER: to the car.
[35:32] SPEAKER: So I can pull out the actual, uh, capacity and stuff from the, from the data that doesn't
[35:36] SPEAKER: usually provide to users.
[35:38] SPEAKER: Um, so this was the hottest summer ever, Brad.
[35:41] SPEAKER: I don't know if you've heard that.
[35:43] SPEAKER: Have heard.
[35:44] SPEAKER: Yes.
[35:45] SPEAKER: I mean, it's probably the hottest summer ever until next summer or the summer after if we're
[35:49] SPEAKER: being real.
[35:50] SPEAKER: Um, but it was 115 air temperature Fahrenheit, which is 47 degrees Celsius for our European
[35:56] SPEAKER: and Australian friends, um, on the drive down.
[36:00] SPEAKER: And then there were some consequences that we hadn't experienced before as a result of
[36:04] SPEAKER: that.
[36:05] SPEAKER: Um, the on pavement temperature when we would get out in the central, so central valley
[36:09] SPEAKER: of California for people don't know is, is very hot.
[36:12] SPEAKER: Uh, even, even at the best of times, this was the hottest I've ever experienced it.
[36:17] SPEAKER: And, um, the temperature on the pavement was 120 plus most places.
[36:22] SPEAKER: I think I took a picture where the car thermometer was like, it's 128 degrees outside.
[36:26] SPEAKER: Um, like all batteries, the car battery has an optimal, both discharge and charge temperature.
[36:35] SPEAKER: And most cars have some sort of system to help manage that temperature.
[36:39] SPEAKER: Basically this comes up in, in like, in the idea that you have to heat the battery in
[36:43] SPEAKER: winter so that you get like it, like the energy you put in to bring the battery up to temperature
[36:48] SPEAKER: is less than the energy you lose by running the battery when it's cold.
[36:52] SPEAKER: Um, so, so like often if you're, so if you live someplace cold, if you live in Vermont
[36:57] SPEAKER: or Montana or something, you leave your car plugged in, even if it's charged so that the
[37:01] SPEAKER: car's heater will turn on and keep the battery at like 50, you know, 30 Celsius, 25 Celsius, whatever.
[37:12] SPEAKER: It's going to be a problem when summers are hot, too, because once the batteries get above
[37:15] SPEAKER: about 105 degrees, the way they charge starts changing.
[37:21] SPEAKER: So, they have to cool them as well.
[37:23] SPEAKER: And newer, like Tesla's do a heat pump, the heat pump has to have multiple valves to control
[37:29] SPEAKER: the, the airflow cause like the, the, um, or the glycol flow, I guess in the case of
[37:35] SPEAKER: the Tesla, uh, because the battery needs to be hotter than you're going to want.
[37:39] SPEAKER: Like the heat pump will also serve the cabin of the car.
[37:41] SPEAKER: So like the heat pump for the battery, the temperature, the battery wants to be at will
[37:45] SPEAKER: be 20 degrees warmer than the temperature the cab wants to be at.
[37:48] SPEAKER: So you have to have them multiple.
[37:49] SPEAKER: It's a couple, it's a little bit of a complicated thing.
[37:52] SPEAKER: Uh, the real quick, remind me where your battery is again in the car.
[37:57] SPEAKER: Oh, it's, they're almost always low in the frame.
[37:59] SPEAKER: So on the, on underneath the frame somewhere low, like often is subject to potentially
[38:06] SPEAKER: some effects of whatever's going on down there, temperature wise, it's usually pretty well
[38:11] SPEAKER: insulated just because they're, they also want to have firewall in case there's a puncture
[38:16] SPEAKER: or something.
[38:17] SPEAKER: There's a fire in the battery.
[38:18] SPEAKER: Right.
[38:19] SPEAKER: Yes.
[38:20] SPEAKER: Um, the, uh, the, the thing on this one is the bolt has a, has a compressor, like a normal
[38:27] SPEAKER: air conditioning compressor.
[38:28] SPEAKER: It uses a resistive heater for the winter, which is a little bit less efficient.
[38:32] SPEAKER: Uh, it's also a cheap car, so you know, you get what you pay for.
[38:36] SPEAKER: Um, and I think at the time that they were originally designing the bolt, the heat pump
[38:39] SPEAKER: idea was relatively new.
[38:41] SPEAKER: Um, so anyway, uh, the optimal charging temperature seems to be around a hundred Fahrenheit, maybe
[38:47] SPEAKER: up to a hundred and three hundred and four.
[38:49] SPEAKER: It started to slow down dramatically once you got much above a hundred and two, it seemed
[38:53] SPEAKER: like from, from what I was pulling from the ODB sensor and our experience watching the
[38:59] SPEAKER: chargers.
[39:00] SPEAKER: Um, it's, and, but by slow, I mean the fastest our car will charge is 50 watt, 50 kilowatts
[39:07] SPEAKER: per hour or kilowatt hours per hour, I guess for a total capacity of 58 or 60 kilowatt
[39:14] SPEAKER: hours.
[39:15] SPEAKER: Okay.
[39:16] SPEAKER: But, uh, the, the bolt is notorious for actually being a slow charger because Chevrolet was
[39:20] SPEAKER: very conservative with the charging profile.
[39:22] SPEAKER: So once you get to about 55 or 60%, it starts to slow down.
[39:26] SPEAKER: Um, just in the same way that like your iPhone slows down, once it gets to 80% charge, the
[39:31] SPEAKER: bolt slows down when it gets half full.
[39:33] SPEAKER: So by the time you get to like 70%, you're going at 25 or 30 kilowatt hours per hour.
[39:38] SPEAKER: And the closer you get to a hundred, the slower it gets.
[39:40] SPEAKER: Can I, can I jump in real quick and ask if there's, is there any kind of community like
[39:44] SPEAKER: homebrew community for like modifying charging profiles on this or other cars?
[39:48] SPEAKER: I have intentionally not looked at that because I have a leased car and not a purchased car.
[39:52] SPEAKER: Sure.
[39:53] SPEAKER: That's smart.
[39:54] SPEAKER: I'm also, yeah, I'm definitely not saying you should partake of that, but I would be
[39:56] SPEAKER: shocked if there is not some like hardcore car forum out there with people talking about
[40:01] SPEAKER: tweaking the charging profiles.
[40:03] SPEAKER: Well, so, um, the part of it is that you don't want to do that cause you're going to decrease
[40:08] SPEAKER: the battery life, right?
[40:10] SPEAKER: Like the harder you charge, the less long the battery is going to cost and the batteries
[40:13] SPEAKER: are 10 or 12 grand, right?
[40:14] SPEAKER: They're expensive batteries.
[40:15] SPEAKER: So that is the conventional wisdom, of course, but you know, some, some people like to throw
[40:19] SPEAKER: caution to the wind on things like that.
[40:21] SPEAKER: Yeah.
[40:22] SPEAKER: I mean, it is flying close to the sun.
[40:24] SPEAKER: Um, the, the, the upshot is that when we hit the first charge at Harris ranch, it was 126
[40:31] SPEAKER: degrees on the pavement and we charged at about 25 kilowatt hours per hour the entire
[40:36] SPEAKER: time, which meant that it took a long time to charge a pretty big decrease.
[40:40] SPEAKER: Um, and like even, even before we're getting into temperature ranges, like just you describing
[40:45] SPEAKER: on a good day, the charging overhead for this trip being what did you say?
[40:48] SPEAKER: Like 90 minutes?
[40:49] SPEAKER: An hour and a half is the best case probably.
[40:51] SPEAKER: Like even that sounds like, you know, if you think about it in combustion engine terms,
[40:55] SPEAKER: you know, spending an hour and a half stopping at gas stations, like that's already a lot
[41:00] SPEAKER: of overhead.
[41:01] SPEAKER: So when you like double that, that's rough.
[41:03] SPEAKER: So the experience, um, the experience we've had is that it's usually like one fairly long
[41:08] SPEAKER: stop, like one 45 minute stop and then a couple of 25 or 30 minute stops.
[41:12] SPEAKER: Um, you know, actually that's maybe you think about it in like health terms, getting up
[41:16] SPEAKER: and walking around after sitting that long, maybe not the worst thing.
[41:19] SPEAKER: Well, yeah, realistically the short stops are you get up, you walk, you go to the bathroom,
[41:23] SPEAKER: you maybe grab a snack, you walk around for five minutes and then it's time to go, which
[41:27] SPEAKER: is, which is pretty, it's much more humane than pulling into a gas station, making everybody
[41:32] SPEAKER: stay in the car or run into the bathroom, driving through the McDonald's drive through
[41:36] SPEAKER: and, and, uh, blasting off.
[41:38] SPEAKER: It means that I often will get like, honestly, it means that instead of eating a burger and
[41:43] SPEAKER: fries, I often will get a salad and sit and eat the salad on, on a, at a picnic bench
[41:48] SPEAKER: at the charging stop.
[41:49] SPEAKER: If we're not someplace, it's 130 degrees outside.
[41:52] SPEAKER: That sounds like being humane to yourself.
[41:54] SPEAKER: I went to, I went to school about a five hour, like the minimum five hour drive from, from
[41:59] SPEAKER: my parents' house.
[42:00] SPEAKER: And I spent like the entire time visiting family while I was in college, trying to make
[42:04] SPEAKER: that drive without stopping.
[42:07] SPEAKER: Yep.
[42:08] SPEAKER: That's probably not good.
[42:09] SPEAKER: You should probably stop every so often and move around because circulation in your legs
[42:13] SPEAKER: is a thing.
[42:14] SPEAKER: Yeah.
[42:15] SPEAKER: Yeah.
[42:16] SPEAKER: Um, so I, yeah, like I don't, I wish that the car, I wish that all of the stops for
[42:20] SPEAKER: the car were like the 18 or 20 minute stops and not the, the 45 minutes, the 45 minute
[42:25] SPEAKER: stop is a pain.
[42:26] SPEAKER: That one's a, that one's a little rough, especially, especially when it becomes 90 minutes.
[42:30] SPEAKER: Yeah.
[42:31] SPEAKER: So the challenge, so we didn't actually do any 90 minutes.
[42:34] SPEAKER: We just did shorter, shorter, more shorter stops, which was fine.
[42:41] SPEAKER: In retrospect, if we'd gone the slightly longer route down 101, which is down the coast where
[42:46] SPEAKER: it's a lot cooler and also there's less competition for chargers, we probably would have made
[42:53] SPEAKER: it there in the same or slightly faster time.
[42:56] SPEAKER: That's insane that you're like, I mean, we're all having to think about a lot of factors
[43:00] SPEAKER: we didn't used to have to think about, but like planning your route partially based on
[43:03] SPEAKER: how hot it's going to be to, to go faster.
[43:06] SPEAKER: Yeah.
[43:07] SPEAKER: Well, and then there's, there's the added benefit of 101 being not a road where everybody's
[43:13] SPEAKER: going 90 miles an hour.
[43:15] SPEAKER: So your efficiency is better because you're going 65 or 70 instead of 75 or 80.
[43:19] SPEAKER: Sure.
[43:20] SPEAKER: And just to be clear, like going seven, if you've never driven on I five down the central
[43:24] SPEAKER: valley, if you don't keep up with traffic, you will die.
[43:26] SPEAKER: Yeah.
[43:27] SPEAKER: Um, it is, it is nothing but long, straight, flat highway.
[43:31] SPEAKER: And people go, um, actually it's better these days, but in the old days, people would go
[43:36] SPEAKER: 80 miles.
[43:37] SPEAKER: Like it was an, if it was an 80 mile, if you weren't going 80 miles an hour, people would
[43:40] SPEAKER: blow by you like they were standing still and you'd get like super tailgated and the
[43:44] SPEAKER: whole thing.
[43:45] SPEAKER: That's, that's how it was back home when I was driving between the mountains and Raleigh.
[43:49] SPEAKER: Also it was like 80, 85 or you're dressed in the slow lane.
[43:53] SPEAKER: North Carolina drivers are notorious too, Brad, I don't want to say anything, but your
[43:57] SPEAKER: people don't know how to, don't know, don't know how to work an interstate.
[44:02] SPEAKER: Yeah.
[44:03] SPEAKER: So the other thing that was happening was that the chargers were overheating.
[44:07] SPEAKER: So like we were, we were parked next to like ionics, which are really incredibly fast chargers,
[44:15] SPEAKER: charging cars.
[44:16] SPEAKER: And they were saying they were seeing like half the speed because the chargers were running
[44:20] SPEAKER: less efficiently because of the intense heat, because a lot of the charging stations don't
[44:24] SPEAKER: have shade in the valley and that's going to change.
[44:27] SPEAKER: I think that they're going to have to put shade on all of them now because the ones
[44:31] SPEAKER: that were shaded were fine and the ones that weren't were not.
[44:35] SPEAKER: But like the thing that was happening to us is the car couldn't keep up, the air conditioning
[44:40] SPEAKER: in the car couldn't keep up with keeping the battery cool and keeping the cabin cool.
[44:44] SPEAKER: So we had to choose to either turn the AC off in the car while it was charging in sweat
[44:50] SPEAKER: or just take the slow charge.
[44:53] SPEAKER: We chose the slow charge.
[44:56] SPEAKER: As hot as it gets there, I was concerned that if we let the AC, if we turn the AC off and
[45:01] SPEAKER: just turn the car off to charge, by the time we got back in the car, we would never get
[45:07] SPEAKER: the car cool again because it was so insanely hot.
[45:13] SPEAKER: And then the other thing is that the chargers were really congested.
[45:17] SPEAKER: We drove down the weekend before 4th of July, it was the most competition for chargers I've
[45:22] SPEAKER: ever seen.
[45:23] SPEAKER: I am never, ever going to do a trip that long, like a three-charge trip.
[45:28] SPEAKER: Just to be real, three-charge trips probably are not great.
[45:34] SPEAKER: You want to start with a full battery, you want to drive 250 miles, you want to charge,
[45:39] SPEAKER: and then you want to be where you're going.
[45:41] SPEAKER: So you want to be a 300-350 mile trip.
[45:44] SPEAKER: Basically, LA is one stop and then maybe a top off when you get close to that town from
[45:51] SPEAKER: San Francisco.
[45:55] SPEAKER: The three-charge stops, it's stressful to worry about whether there's going to be spaces
[46:00] SPEAKER: and how long you're going to have to wait for a charge spot and all that stuff.
[46:03] SPEAKER: Maybe we made our country too big.
[46:06] SPEAKER: I mean, it's possible.
[46:08] SPEAKER: The West, especially, when I was a kid, would we have tried to drive 500 miles in a day?
[46:15] SPEAKER: No, we would have stopped midway and got a Motel 6 and piled up the next morning and
[46:19] SPEAKER: driven 250 miles each day.
[46:21] SPEAKER: I think occasionally, not that I am planning to move back home, but I think occasionally
[46:26] SPEAKER: about what would be involved if I did.
[46:28] SPEAKER: And part of that would be a cross-country drive.
[46:31] SPEAKER: And now I'm thinking about the logistics of driving cross-country in an electric car,
[46:35] SPEAKER: and that seems like a lot.
[46:37] SPEAKER: So it's not, if you do-
[46:39] SPEAKER: Not that I would do that, but now it's a thought experiment and that seems maybe not entirely
[46:45] SPEAKER: viable.
[46:46] SPEAKER: Well, so we went through the whole process.
[46:48] SPEAKER: If the car charged, for example, the car that we're looking at, we talked to a bunch of
[46:52] SPEAKER: people at charge stops about how they like their cars.
[46:55] SPEAKER: And the one that everybody loves most is the Ioniq, which is a Hyundai.
[46:59] SPEAKER: It's one of the faster-charging non-Teslas.
[47:01] SPEAKER: That's the same brand as the chargers you were talking about?
[47:07] SPEAKER: Those are also them?
[47:08] SPEAKER: Or did I mix up branding?
[47:10] SPEAKER: What was the brand of the chargers?
[47:12] SPEAKER: The charger brand is Electrify America.
[47:14] SPEAKER: That's the ones that we generally find to be the most reliable.
[47:17] SPEAKER: The Ioniq is a brand of car.
[47:19] SPEAKER: Okay.
[47:20] SPEAKER: I thought you had also said the chargers were Ioniq.
[47:22] SPEAKER: I misremembered.
[47:23] SPEAKER: No, no, no.
[47:24] SPEAKER: So talking to those folks, it charges at 350 kilowatt hours per hour, right?
[47:32] SPEAKER: One of the women next to us pulled in with the 8%, the same 8% we had.
[47:35] SPEAKER: By the time we were at 27%, she was at 80%.
[47:39] SPEAKER: So if you have that, it's literally 15, 20 minutes each time you stop.
[47:46] SPEAKER: So you go in, you grab some food, you go to the bathroom, you eat, you unplug and go.
[47:53] SPEAKER: It just means that you eat sitting in the car at the charge stop or in the restaurant
[47:56] SPEAKER: or whatever, rather than shoveling food down your mouth while you're driving down the highway
[48:00] SPEAKER: at 80 miles an hour, which is probably an improvement for everyone on the road.
[48:08] SPEAKER: When Gina and I moved out here, I think we did four 500-mile days, five 500-mile days,
[48:14] SPEAKER: which was basically 10 hours of driving a day in the U-Haul.
[48:21] SPEAKER: I would do that in a heartbeat with not our car.
[48:25] SPEAKER: It's just the bolt charges slow.
[48:30] SPEAKER: I'm never driving on a holiday weekend again.
[48:31] SPEAKER: When we returned on Tuesday, the first Tuesday in August, it was fine.
[48:37] SPEAKER: There were no competition for chargers.
[48:40] SPEAKER: Everything was available.
[48:41] SPEAKER: It was a piece of cake.
[48:42] SPEAKER: Then, it's funny, I was talking to Norm about this because he has a Model 3.
[48:48] SPEAKER: The charging situation for road trips on the Tesla is such, because the Tesla software
[48:52] SPEAKER: talks to the battery and knows what the battery is.
[48:56] SPEAKER: It knows where all the superchargers are.
[48:58] SPEAKER: It's like, "OK, you're going here.
[49:00] SPEAKER: Here's where I think you're going to charge.
[49:02] SPEAKER: If you do better on your consumption, then you can go a little bit further to this next one.
[49:06] SPEAKER: If you don't, then you can stop here."
[49:08] SPEAKER: The problem with the non-Teslas is that we would often be at 30% battery, where the tool
[49:16] SPEAKER: that I use to plan routes wanted us to stop, and that meant we would miss 18% of our fastest
[49:24] SPEAKER: charging time.
[49:25] SPEAKER: The time from 10% to 50% is the fastest charging you can do.
[49:30] SPEAKER: You want to min-max that time.
[49:33] SPEAKER: It's like some video game business happening here.
[49:35] SPEAKER: You want to get as close to 10% as you can and then charge up to 50% or 60% rather than
[49:42] SPEAKER: starting at 28% and going to 70%.
[49:45] SPEAKER: There's a tool, we've talked about it before, called A Better Route Planner, which is an app.
[49:48] SPEAKER: It's a website.
[49:50] SPEAKER: You can hook it up to the ODB data out of the port in the car.
[49:53] SPEAKER: But it's still way fiddlier than it needs to be for route planning.
[50:00] SPEAKER: It doesn't account for things like the Bolt being -- it accounts for the Bolt being shitty
[50:05] SPEAKER: at charging, but not in a way that lets you min-max that as efficiently as possible.
[50:10] SPEAKER: On the way back, we ended up doing the whole trip in 10.5 hours, which is I think the best
[50:15] SPEAKER: time we've ever done.
[50:16] SPEAKER: Oh, okay.
[50:17] SPEAKER: That's respectable.
[50:18] SPEAKER: A lot of what you're describing sounds like it's just a lot of teething pains and this
[50:23] SPEAKER: very extremely distinctive category of car, you know what I mean?
[50:29] SPEAKER: This type of driving, this technology has not been around that long in the grand scheme
[50:33] SPEAKER: of how long cars have existed, so hopefully a lot of this will get worked out.
[50:37] SPEAKER: I think it's a combination of that, and also the fact that there's not -- one of the big
[50:42] SPEAKER: changes that's happened in the three years we've been doing this drive is that there's
[50:47] SPEAKER: a lot more chargers on that corridor now, all the way through.
[50:51] SPEAKER: It used to be that there was a charger dead spot that was 80 miles along from Grapevine
[50:55] SPEAKER: to Santa Clarita.
[50:57] SPEAKER: Now there's chargers at the top of the Grapevine, there's chargers -- there's multiple chargers
[51:01] SPEAKER: all the way down, not quite at every stop, but every second or third exit on the way
[51:06] SPEAKER: now it seems like you can find some sort of charging.
[51:09] SPEAKER: So missing one or having one that's full and going onto the next one or whatever isn't
[51:14] SPEAKER: as much of a disaster as it would have been, say, three years ago.
[51:16] SPEAKER: That's good.
[51:17] SPEAKER: There's also a lot more electric cars on the road, so there's a lot more competition for
[51:20] SPEAKER: those spaces.
[51:21] SPEAKER: Vary, real quick, I know we covered this when we did the full episode on this, but what's
[51:25] SPEAKER: the payment structure generally like for these third-party charging stations?
[51:30] SPEAKER: So you have an app, you either pay per time spent at the plug or per kilowatt hour.
[51:37] SPEAKER: Typically it costs me $20, $25 to drive 500 miles, not counting what I have in the car
[51:42] SPEAKER: when I leave my house in the morning.
[51:45] SPEAKER: So I think we paid 16 bucks on the way up on Tuesday for three charges, which is like,
[51:53] SPEAKER: you couldn't do that for any gas car, I don't think.
[51:57] SPEAKER: Just kind of stuff that we have covered here that seems like it needs to change or will
[52:01] SPEAKER: change, like cooling of batteries and charging stations.
[52:03] SPEAKER: I mean, it's a sad commentary on the state of things, but I assume that car manufacturers
[52:08] SPEAKER: are going to maybe start thinking more about cooling batteries as well as heating them.
[52:13] SPEAKER: Yeah.
[52:14] SPEAKER: I mean, they already do think about cooling batteries, but I think the question is, is
[52:19] SPEAKER: the cooling going to be adequate for the challenges of the changing climate?
[52:24] SPEAKER: That's what I really meant.
[52:25] SPEAKER: They're going to think more about increasing the range of cooling they can handle.
[52:28] SPEAKER: Well, yeah.
[52:29] SPEAKER: And also stuff like not putting the chargers and the charging spots in direct sun, right?
[52:34] SPEAKER: Even when it was 105 degrees out and we were in a shaded spot, the air conditioner in the
[52:40] SPEAKER: car didn't have to work as hard to keep the car cool as it did when we were in the direct
[52:43] SPEAKER: sun and the car temperature was reading 130 degrees.
[52:48] SPEAKER: It's interesting because I really enjoy the min maxing aspect of trying to figure out
[52:56] SPEAKER: where the stops should be and all that.
[52:58] SPEAKER: It drives my wife absolutely bonkers.
[53:01] SPEAKER: It sounds fun to me too when you talked about, even though a better route planner is maybe
[53:04] SPEAKER: not ideal, that sounds like a fun efficiency problem of charting all that stuff out.
[53:10] SPEAKER: Yeah.
[53:11] SPEAKER: It's exactly what I like about satisfactory and factorial and all those kinds of things.
[53:14] SPEAKER: And it's like, she's like, I don't want to do calculus in my head to figure out where
[53:19] SPEAKER: I should charge.
[53:20] SPEAKER: So no, thank you.
[53:21] SPEAKER: That was the other big category besides battery cooling that I was thinking about that may
[53:25] SPEAKER: hopefully will get better is maybe the other manufacturers will try to come up with a more
[53:30] SPEAKER: Tesla like solution for that sort of thing.
[53:32] SPEAKER: Although, although based on the little bit I've done looking into the quality of car
[53:36] SPEAKER: manufacturer designed entertainment systems and entertainment software, maybe relying
[53:41] SPEAKER: on them to create that kind of software is not great.
[53:45] SPEAKER: Yeah.
[53:47] SPEAKER: It's weird because you'd think that that car information would be available through CarPlay.
[53:53] SPEAKER: And I don't know if it's just that the version of CarPlay that's in my car is old or if the
[53:58] SPEAKER: specs for CarPlay, I went and looked at it before the show and it's unclear without the
[54:01] SPEAKER: developer license, which is different for CarPlay stuff because they only license Ford
[54:06] SPEAKER: and Mercedes and places like that.
[54:09] SPEAKER: It's unclear if that information is even accessible or if it's the manufacturers are choosing
[54:13] SPEAKER: not to pass that through to apps potentially.
[54:16] SPEAKER: I understand why they wouldn't give your phone app access to the two way communication with
[54:22] SPEAKER: the cars, like telemetrics and telemetry and all that stuff.
[54:27] SPEAKER: But it does seem like having apps that have that information would make it much easier
[54:33] SPEAKER: to find charging.
[54:35] SPEAKER: I also am curious if, like I did a little bit of research before we left to find out
[54:39] SPEAKER: if ABRP is still the best option for this.
[54:42] SPEAKER: If there's some other tool, I would love to hear it.
[54:46] SPEAKER: If people have had better success with some other tool, I would love to hear about it
[54:49] SPEAKER: because it's interesting because Gina and I can set up the app on our phones exactly
[54:57] SPEAKER: the same way with exactly the same data and exactly the same route.
[55:01] SPEAKER: And she will get completely different results than I do.
[55:04] SPEAKER: That's not what you want.
[55:07] SPEAKER: Which is, I don't know, it's just frustrating.
[55:13] SPEAKER: It's frustrating when you know that there's a better route that you should be able to
[55:16] SPEAKER: make and it won't confirm or deny.
[55:18] SPEAKER: It won't let you just say, "Hey, go here.
[55:21] SPEAKER: I want to go here and charge.
[55:23] SPEAKER: I think that this one's going to be better and it won't tell you what the time split
[55:27] SPEAKER: is."
[55:28] SPEAKER: So anyway.
[55:29] SPEAKER: Deterministic route planning or bust?
[55:31] SPEAKER: Yeah, exactly.
[55:32] SPEAKER: All I want is simple determinism.
[55:37] SPEAKER: Brad, what's up with coffee?
[55:38] SPEAKER: How are you doing in the cold brew?
[55:39] SPEAKER: What's up with coffee is coffee is pretty good, man.
[55:42] SPEAKER: I don't know if you've heard.
[55:44] SPEAKER: Look, I did a French press the entire time I was in the desert.
[55:47] SPEAKER: It turns out I like a French press.
[55:49] SPEAKER: Who knew?
[55:50] SPEAKER: Yeah.
[55:51] SPEAKER: Yeah.
[55:52] SPEAKER: You know, I've gotten some French press experience here.
[55:53] SPEAKER: Yeah.
[55:54] SPEAKER: Quick coffee update.
[55:55] SPEAKER: I'm two weeks now into daily cold brew, so I thought I would maybe touch on where I'm
[55:59] SPEAKER: at with that.
[56:00] SPEAKER: So your strategy has been to make concentrate and then dilute it with hot water to warm
[56:04] SPEAKER: it up so it's drinkable as a hot coffee rather than like you're not making cold iced coffee
[56:09] SPEAKER: with your cold brew.
[56:10] SPEAKER: No, no, no.
[56:11] SPEAKER: Yes.
[56:12] SPEAKER: So getting the ratio where I want it, I'm not sure I'm actually there yet, but I'm getting
[56:14] SPEAKER: closer.
[56:15] SPEAKER: Like that's been probably the hardest part is figuring that out.
[56:19] SPEAKER: What to do the brewing in is also a point of contention.
[56:24] SPEAKER: I think those are probably the two big variables I'm still dialing in.
[56:27] SPEAKER: I started out trying to do a very concentrated concentrate.
[56:30] SPEAKER: Yeah.
[56:31] SPEAKER: That's more challenging.
[56:32] SPEAKER: Right?
[56:33] SPEAKER: Yeah.
[56:34] SPEAKER: Yeah.
[56:35] SPEAKER: I'm talking like one to four coffee to water, one to five, but it's like at that, at that
[56:40] SPEAKER: point it almost gets hard to immerse all the grounds in enough water to actually do the
[56:45] SPEAKER: brew properly.
[56:46] SPEAKER: Oh yeah.
[56:47] SPEAKER: I assume you have to just pour the, pour the grounds into the coffee and then filter them
[56:50] SPEAKER: out.
[56:51] SPEAKER: Right?
[56:52] SPEAKER: Yes, pretty much so.
[56:53] SPEAKER: Like I wanted something that concentrated because I liked the coffee hot and you need
[56:56] SPEAKER: to add a lot of hot water to liquid that's been in the fridge, obviously to make it hot.
[57:01] SPEAKER: That makes sense.
[57:02] SPEAKER: But, but yeah, it has kind of turned out to not be super practical to do something that
[57:07] SPEAKER: concentrated.
[57:08] SPEAKER: You had recommended a one to 10.
[57:10] SPEAKER: That's what I usually do for my, but I do iced and then add milk to it usually.
[57:13] SPEAKER: Yeah.
[57:14] SPEAKER: So you don't, you don't have the heat component to worry about.
[57:16] SPEAKER: I've seen everything from like I've seen everything from like a one to seven, one to eight, one
[57:20] SPEAKER: to 10 out there.
[57:22] SPEAKER: Every site, every coffee site has its own opinions about what is ideal.
[57:26] SPEAKER: So the coarseness of the grind is another one that I still haven't fully settled on.
[57:29] SPEAKER: Some places say do as course as your grinder can do.
[57:33] SPEAKER: And then others are like, ah, if you actually put it at about like 80% course or something,
[57:38] SPEAKER: it's maybe going to be a little sweeter.
[57:39] SPEAKER: Well, if you, and also if you're doing a paper filter versus a metal mesh, like if you're
[57:45] SPEAKER: using a French press to strain out the grounds, you want it coarse so you don't have chunks
[57:48] SPEAKER: that come through.
[57:49] SPEAKER: Right.
[57:50] SPEAKER: If you're using a, if you're running it through a paper filter, you can go finer and get more
[57:53] SPEAKER: extraction.
[57:54] SPEAKER: That's probably how you make your more, more concentrated concentrate actually.
[57:59] SPEAKER: Yeah.
[58:00] SPEAKER: The other, the other, so, so there's the concentrate ratio.
[58:02] SPEAKER: The other ratio to think about is the drinkable ratio and for that I have mostly seen recommendations
[58:06] SPEAKER: between like one to 15 to one to 18 ish.
[58:10] SPEAKER: And this is the amount of concentrate to hot water you're adding?
[58:13] SPEAKER: Yes.
[58:14] SPEAKER: Well, no, that's the eventual ratio of coffee to water.
[58:18] SPEAKER: So, so for example, if you're doing a one to nine you know, coffee, coffee to water to
[58:25] SPEAKER: brew, then you double the one, double the amount of liquid you do half and half boiling
[58:28] SPEAKER: water and concentrate.
[58:30] SPEAKER: Got it.
[58:31] SPEAKER: After the fact.
[58:32] SPEAKER: And that's, that's where I've landed, I've been doing one to nine and then when I pour
[58:36] SPEAKER: the concentrate to, to heat it up, to drink it, I'll, I'll put in an amount and then just
[58:40] SPEAKER: double it.
[58:41] SPEAKER: That makes the math very easy.
[58:42] SPEAKER: Oh, okay.
[58:43] SPEAKER: To, and that my, our kettle goes to two, two, two 12 obviously.
[58:48] SPEAKER: So I jacked it all the way up and I, I get, I get what I just barely consider hot enough
[58:53] SPEAKER: to drink liquid out of fridge cooled concentrates and boiling water.
[58:59] SPEAKER: That sounds pretty good.
[59:00] SPEAKER: Basically like it's, it's, I have to drink it pretty quick or it starts getting lukewarm
[59:04] SPEAKER: in a way I don't love.
[59:05] SPEAKER: I don't know how you feel about less than hot coffee, but
[59:07] SPEAKER: I just drank my last sip and it's probably about 140 right now.
[59:12] SPEAKER: It's not great.
[59:13] SPEAKER: Yeah.
[59:14] SPEAKER: Yeah.
[59:15] SPEAKER: It's, it's a little, it's like, it's like flat beer.
[59:16] SPEAKER: It's just not, it does not go.
[59:20] SPEAKER: We did a, we did a story about this.
[59:22] SPEAKER: There was a study you've done about this that we wrote about it right up and tested years
[59:25] SPEAKER: and years ago where there's like, there's a sweet spot above 160 Fahrenheit.
[59:30] SPEAKER: And then once you get below a hundred, like colder is, is actually good.
[59:34] SPEAKER: Yes.
[59:35] SPEAKER: I could tell you that.
[59:36] SPEAKER: But yeah.
[59:37] SPEAKER: Like you, like you want hot or cold.
[59:38] SPEAKER: You don't want in the middle.
[59:39] SPEAKER: No.
[59:40] SPEAKER: I mean, I'm finding at that ratio, I'm still finding like the body.
[59:43] SPEAKER: So yeah.
[59:44] SPEAKER: See, I'm able to, I'm using what I learned in that coffee episode a couple of weeks ago.
[59:48] SPEAKER: The, the body is still quite rich.
[59:50] SPEAKER: I find at that concentration.
[59:52] SPEAKER: So you could add more hot water theoretically to that.
[59:55] SPEAKER: I could.
[59:56] SPEAKER: I could.
[59:57] SPEAKER: But also I love how kind of thick and velvety it is.
[59:59] SPEAKER: It's got a nice mouthfeel when you get, when you get a good immersion brew, right?
[1:00:04] SPEAKER: Really it tastes so much better.
[1:00:05] SPEAKER: I can't, we've been, I've, I'm actually using Dunkin Donuts whole beans right now for this
[1:00:09] SPEAKER: and even that is quite good.
[1:00:11] SPEAKER: Okay.
[1:00:12] SPEAKER: With the cold brew I'm finding.
[1:00:13] SPEAKER: Have you done your homework?
[1:00:14] SPEAKER: Have you gone to the fancy coffee shop yet?
[1:00:17] SPEAKER: Not yet.
[1:00:18] SPEAKER: Not yet.
[1:00:19] SPEAKER: But sure enough.
[1:00:20] SPEAKER: You're right.
[1:00:21] SPEAKER: This, I looked at the Dunkin Donuts.
[1:00:22] SPEAKER: It's, it's a, it's a medium roast.
[1:00:23] SPEAKER: Like you said, all the, all the classic American coffee is a medium roast.
[1:00:27] SPEAKER: Yep.
[1:00:28] SPEAKER: That's, that's what people like.
[1:00:29] SPEAKER: Yes.
[1:00:30] SPEAKER: So I think, I think I'm pretty happy with the ratio I've got going for now.
[1:00:34] SPEAKER: I have been using the French press daily to make enough for myself and my partner.
[1:00:41] SPEAKER: So you do it at night or the morning, you do it in the morning and then it sits for
[1:00:44] SPEAKER: 24 hours?
[1:00:45] SPEAKER: Cause that's the other, the time, the time it extracts is the other variable.
[1:00:49] SPEAKER: There are so many variables.
[1:00:50] SPEAKER: There's coarseness of grind, there's ratio, there's how long you steep it.
[1:00:54] SPEAKER: Yeah.
[1:00:55] SPEAKER: I think you had recommended not to go past 24 hours.
[1:00:58] SPEAKER: I've kind of been aiming for like 18 to 20 hours.
[1:01:01] SPEAKER: That seems, I think, I think in my experience for at least cold brew for, for iced coffees,
[1:01:07] SPEAKER: there's not a lot of difference between any more than 12 and less than 24.
[1:01:11] SPEAKER: Once you get beyond 24, you get to start, start getting a little bitter in my experience.
[1:01:14] SPEAKER: Interesting.
[1:01:15] SPEAKER: Maybe I should start trying like 12 and see if I can actually tell the difference because
[1:01:18] SPEAKER: if there's not much to be gained by going longer than maybe I could simplify things
[1:01:22] SPEAKER: because planning the lead time for this has been a whole thing, you know, like I'm essentially
[1:01:27] SPEAKER: making two days from now's coffee today.
[1:01:31] SPEAKER: You know what I mean?
[1:01:32] SPEAKER: It's like, Hey, I got to put this in and let it go for most of the day.
[1:01:35] SPEAKER: And then harvest.
[1:01:36] SPEAKER: I've been using the term harvest the coffee, but like do that the night before.
[1:01:41] SPEAKER: So basically I'm like, like the coffee I'm making Wednesday afternoon, I'm going to drink
[1:01:45] SPEAKER: Friday morning, basically.
[1:01:47] SPEAKER: So are you going to invest, are you going to invest in a, in a dedicated device for
[1:01:52] SPEAKER: this?
[1:01:53] SPEAKER: I've thought about it.
[1:01:54] SPEAKER: I think the Tadi one, there's also some recommendations for the OXO cold brew that I think we talked
[1:01:59] SPEAKER: about those a little bit.
[1:02:00] SPEAKER: Yeah.
[1:02:01] SPEAKER: The OXO is the one like the OXO seems good.
[1:02:03] SPEAKER: The Tadi is too big is at least the one that I had was, was ridiculously big, really icky.
[1:02:12] SPEAKER: Yeah.
[1:02:13] SPEAKER: And we're, we're pretty short on counter space also.
[1:02:14] SPEAKER: So I'm going to keep trying to work with what we have for now that I did not have a lot
[1:02:19] SPEAKER: of French press.
[1:02:20] SPEAKER: I had, in fact, I had zero French press experience before I started doing this cleaning a French
[1:02:24] SPEAKER: press every day has already gotten old enough that I don't think I want to do it anymore.
[1:02:29] SPEAKER: You know that the bottom unscrews, right?
[1:02:31] SPEAKER: Yeah.
[1:02:32] SPEAKER: Yeah.
[1:02:33] SPEAKER: But that's exactly why it takes a little bit longer than I want to deal with every day
[1:02:36] SPEAKER: to take the whole thing apart and scrub it all.
[1:02:38] SPEAKER: And Oh, I just unscrewed it and put it in the dishwasher.
[1:02:42] SPEAKER: Oh, okay.
[1:02:43] SPEAKER: Well, we don't, we don't run the dishwasher every day for two people.
[1:02:46] SPEAKER: So that's not an option there anyway.
[1:02:50] SPEAKER: I think I'm going to ditch the French press.
[1:02:52] SPEAKER: I might've mentioned this before.
[1:02:54] SPEAKER: We have a rumble jar.
[1:02:56] SPEAKER: What's a rumble jar.
[1:02:57] SPEAKER: That sounds like, that sounds like you, like you get, you get in it with the pink ladies
[1:03:00] SPEAKER: down at the sock hop.
[1:03:01] SPEAKER: Uh huh.
[1:03:02] SPEAKER: I'm not gonna leave that there.
[1:03:06] SPEAKER: What's a rumble jar, Brad?
[1:03:07] SPEAKER: I'll just leave that there.
[1:03:08] SPEAKER: I'm trying to pull up their website so I can give you some actual measurements.
[1:03:11] SPEAKER: It's just a, it's just a metal cylinder with a little rubber lid that snaps onto it.
[1:03:16] SPEAKER: Oh, is it a thing that like you put it in a, in a bigger picture or something?
[1:03:20] SPEAKER: It is, it is exactly a size to fit the average Mason jar.
[1:03:24] SPEAKER: Oh, okay.
[1:03:25] SPEAKER: So like a one quart Mason jar.
[1:03:27] SPEAKER: So with the rubber lid on, it actually like hugs the, the, the mouth of the Mason jar
[1:03:31] SPEAKER: and kind of not too tightly, but it fits snugly enough to kind of sit.
[1:03:37] SPEAKER: It's just a metal cylinder with some extremely small, like machined micro holes.
[1:03:42] SPEAKER: Yeah.
[1:03:43] SPEAKER: I'm, I'm again, trying to find, I could tell you how big the holes are if I can just find
[1:03:46] SPEAKER: them, but I mean, the idea is that you have a metal filter that lets you do your coffee
[1:03:50] SPEAKER: without having to do a,
[1:03:53] SPEAKER: I found it.
[1:03:54] SPEAKER: Yes.
[1:03:55] SPEAKER: Excuse me.
[1:03:56] SPEAKER: 200 micron holes.
[1:03:57] SPEAKER: Oh, those are laser holes.
[1:03:58] SPEAKER: Those are tiny holes.
[1:03:59] SPEAKER: They're tiny holes.
[1:04:00] SPEAKER: They're like, they're almost too small to see unless you hold it up close to your face.
[1:04:04] SPEAKER: Like a cone.
[1:04:05] SPEAKER: So, so the reason I wasn't using it before, just to get a little bit more into the nitty
[1:04:08] SPEAKER: gritty when I was making that super concentrate or trying to that small amount of water, because
[1:04:13] SPEAKER: it's such a thin cylinder.
[1:04:15] SPEAKER: It's a pretty tall column of grounds.
[1:04:17] SPEAKER: Yeah.
[1:04:18] SPEAKER: It was not even enough water to fully immerse the grounds.
[1:04:20] SPEAKER: It was actually not.
[1:04:21] SPEAKER: That won't work.
[1:04:22] SPEAKER: But now that I'm doing nine to one, I think that actually will be enough.
[1:04:25] SPEAKER: So I'm going to try that because then you would just take a giant Mason jar, fill the
[1:04:29] SPEAKER: rumble jar with coffee, pour all the water in, let it sit much easier.
[1:04:34] SPEAKER: You can also, so the Hario that I use, I wasn't grinding fine enough for when, when I couldn't
[1:04:42] SPEAKER: get all of the grounds submerged in the amount of water I was supposed to be using, it was
[1:04:45] SPEAKER: because I wasn't grinding the coffee fine enough because the finer ground coffee will
[1:04:49] SPEAKER: be less volume.
[1:04:50] SPEAKER: So is that why everybody recommends course grind for cold brew, the filtering, not because
[1:04:55] SPEAKER: of some extractive factor, because it's easier to filter out the grounds and you don't want
[1:05:00] SPEAKER: to overextract like overextracting tastes bad.
[1:05:03] SPEAKER: So that might be my last big question.
[1:05:05] SPEAKER: And that's certainly something that's hard to measure is not just for the quality of
[1:05:09] SPEAKER: the coffee, but especially how much caffeine I'm consuming.
[1:05:12] SPEAKER: I'm wondering, I'm wondering like, are you definitely getting more caffeine the longer
[1:05:17] SPEAKER: you, you steep, do you know, or is that something that levels off after 12 hours?
[1:05:22] SPEAKER: Haven't the foggiest.
[1:05:23] SPEAKER: Okay.
[1:05:24] SPEAKER: I anecdotally it's hard to, it's hard to evaluate your own perception, but I feel like I'm probably
[1:05:30] SPEAKER: more caffeinated than I used to be.
[1:05:32] SPEAKER: I don't ever feel like I can see through time after drinking the cold brew that I make.
[1:05:36] SPEAKER: Okay.
[1:05:37] SPEAKER: Okay.
[1:05:38] SPEAKER: Like I'm not super affected by caffeine.
[1:05:41] SPEAKER: Okay.
[1:05:42] SPEAKER: I am.
[1:05:43] SPEAKER: That's something I really need to be conscious of.
[1:05:44] SPEAKER: So anyway, that's probably the last thing that I'm really trying to dial in, but enjoy
[1:05:49] SPEAKER: the coffee a lot more.
[1:05:51] SPEAKER: It's tastes significantly better.
[1:05:53] SPEAKER: The thing about the cold brew is it, it is a, is a really reliable way to make a really
[1:05:57] SPEAKER: nice cup of coffee.
[1:05:58] SPEAKER: Yes.
[1:05:59] SPEAKER: Yes.
[1:06:00] SPEAKER: It's a little fiddlier in the morning because I have to get up, I get up, filter water and
[1:06:03] SPEAKER: then boil the water in the kettle and then get the scale out and have to like measure
[1:06:06] SPEAKER: out the concentrate to the, you know, it's, it's just slightly more work even after the
[1:06:10] SPEAKER: fact to drink it, but it's, it's worth it.
[1:06:13] SPEAKER: Tastes good.
[1:06:14] SPEAKER: There you go.
[1:06:15] SPEAKER: So I think that's a show there's, there's three updates, three things we've been doing
[1:06:19] SPEAKER: lately that we're like probably in retrospect, maybe we could have gotten a whole episode
[1:06:23] SPEAKER: out of WireGuard, but I feel like, I feel like, I feel like VPNs are, VPNs are a weird
[1:06:29] SPEAKER: space cause they're like niche.
[1:06:32] SPEAKER: I didn't think I needed one until I had one.
[1:06:34] SPEAKER: And then I was like, Oh, this is, it turns out it's pretty good.
[1:06:36] SPEAKER: Yes.
[1:06:37] SPEAKER: Yeah.
[1:06:38] SPEAKER: It's sorry.
[1:06:39] SPEAKER: That may have been a little jumbled with that section.
[1:06:40] SPEAKER: Like it's, it's something that I understand just well enough to start worrying that I
[1:06:43] SPEAKER: don't understand it well enough to explain it to somebody, but it it's been pretty awesome.
[1:06:49] SPEAKER: And I feel like there are more and more use cases for the average person as people are
[1:06:53] SPEAKER: running like Plex or Jellyfin at home and want to be able to access that.
[1:06:57] SPEAKER: And judging by the number of podcasters that are advertising VPN software on a, on a week
[1:07:04] SPEAKER: to week basis, apparently they're very popular.
[1:07:07] SPEAKER: So yeah, I, you know, just, just as a, as another basic piece of information, we should
[1:07:12] SPEAKER: mention like this does not replace a commercial VPN service.
[1:07:16] SPEAKER: This is just VPN ending into your house.
[1:07:18] SPEAKER: All your traffic is still going through your ISP from your house.
[1:07:21] SPEAKER: Yeah.
[1:07:22] SPEAKER: If you're using a VPN to say, mask your IP address because you're doing something that
[1:07:25] SPEAKER: you don't want any multinational media conglomerates to know about this WireGuard solution will
[1:07:30] SPEAKER: not solve that problem for you.
[1:07:32] SPEAKER: Yes.
[1:07:33] SPEAKER: But you can, and people on our discord do this, and it seems like it's getting easier
[1:07:36] SPEAKER: all the time.
[1:07:37] SPEAKER: You can just like make your own VPN of that nature by getting a, like a, a VPS virtual
[1:07:43] SPEAKER: private server.
[1:07:44] SPEAKER: You can just set up WireGuard on that.
[1:07:46] SPEAKER: And then you do have a secure tunnel through the internet, although then you're subject
[1:07:51] SPEAKER: to whoever provides that cloud instance.
[1:07:54] SPEAKER: And instead of, instead of a VPN company, you're dealing with cloud companies.
[1:07:57] SPEAKER: Well, and you have to maintain it yourself when like you're running your $5 a month line
[1:08:00] SPEAKER: node, it probably costs more than just paying somebody to do VPN for you.
[1:08:04] SPEAKER: Yeah.
[1:08:05] SPEAKER: Well, I mean the, the bigger concerns there are people worry about commercial VPN providers,
[1:08:09] SPEAKER: like logging what they do and stuff like that.
[1:08:11] SPEAKER: Maybe they're not as private as they are advertised to be.
[1:08:14] SPEAKER: Don't do illegal stuff on the internet is the other way to handle this.
[1:08:18] SPEAKER: You could just take that tack anyway.
[1:08:19] SPEAKER: You know what's not illegal though?
[1:08:21] SPEAKER: What's that?
[1:08:22] SPEAKER: Supporting your favorite broadcast, Brad.
[1:08:23] SPEAKER: Oh, that is both legal and morally correct.
[1:08:26] SPEAKER: Yeah.
[1:08:27] SPEAKER: Did you know that Brad and Will Made of TechPod is a 100% listener supported show?
[1:08:31] SPEAKER: I did know that.
[1:08:32] SPEAKER: We don't take, like you can listen to us talk about how awesome WireGuard is because you
[1:08:36] SPEAKER: know that we've not taken any advertising money to talk about VPNs.
[1:08:41] SPEAKER: But we do that because listeners like you support the show through our Patreon at patreon.com/techpod.
[1:08:46] SPEAKER: Again, it's patreon.com/techpod, where for five bucks a month, you get access to the
[1:08:51] SPEAKER: fabulous Patreon exclusive episode, as well as access to the TechPod Discord, which is
[1:08:57] SPEAKER: full of beautiful nerds just like you, who have an incredible amount of information to
[1:09:04] SPEAKER: share about a wide variety of topics, from mechanical calculators all the way down to
[1:09:11] SPEAKER: setting up audio gear and getting good lights for your battle station at home.
[1:09:17] SPEAKER: The coffee conversation that happened after the coffee episode two weeks ago, it's still
[1:09:21] SPEAKER: going.
[1:09:23] SPEAKER: I think we're going to have to do a coffee channel for the spinoff from the coffee conversation.
[1:09:29] SPEAKER: I liked that midway through that conversation about the coffee stuff, there was a scotch
[1:09:34] SPEAKER: and whiskey fork of that conversation.
[1:09:36] SPEAKER: I was just about to bring that up.
[1:09:37] SPEAKER: I didn't mean to hijack the coffee chat with whiskey chat, but that was fun, too.
[1:09:42] SPEAKER: Look, if you want to put some dirt in your booze, I'm not going to judge you.
[1:09:49] SPEAKER: It was coffee time, Brad.
[1:09:53] SPEAKER: It's a wonderful group of people.
[1:09:57] SPEAKER: We are lucky to have you all as part of the community around the weird show that we do.
[1:10:05] SPEAKER: As always, we like to thank all of our patrons, but especially our executive producer tier
[1:10:10] SPEAKER: patrons, including Nick Johnston, Paddle Creek Games, makers of Fractured Veil, Andrew Slosky,
[1:10:16] SPEAKER: Jordan Lippett, Bunnyfiend, Just Wedge 3.0, Joel Krauska, Twinkie, The General Contractor,
[1:10:23] SPEAKER: David Allen, James Kamik, and Pantheon, makers of the HS3 high-speed 3D printer.
[1:10:30] SPEAKER: That's us this week.
[1:10:32] SPEAKER: Thanks for listening, everybody.
[1:10:33] SPEAKER: We will be back next week with another tech pod.
[1:10:37] SPEAKER: See you all then!
[1:10:40] SPEAKER: (upbeat music)
