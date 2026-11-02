---
episode: 243
title: 233: My Wife Is a LaserDisc Guy
date: 2024-05-05
guests: none
duration: 1:34:29
---

[00:00] SPEAKER: - Okay, something magical has happened in Mr. Land.
[00:02] SPEAKER: - Ooh, I love magical stuff.
[00:04] SPEAKER: Let me guess, if you send a note
[00:07] SPEAKER: and a self-addressed stamped envelope,
[00:09] SPEAKER: then the Mr. People will send you a free Mr. of your choice
[00:13] SPEAKER: with your choice of add-ons for the next 10 days only.
[00:17] SPEAKER: - Self-addressed stamped envelope is not a phrase
[00:20] SPEAKER: I've heard since probably the mid '90s.
[00:22] SPEAKER: - You don't work in the realm of SASEs anymore?
[00:25] SPEAKER: - No, I'm not buying a lot of cereal
[00:28] SPEAKER: that gives away action figures anymore.
[00:29] SPEAKER: - Did you have to, you didn't have to send,
[00:31] SPEAKER: I guess you did have to send a,
[00:32] SPEAKER: you have to have to send a sassy for those sometimes.
[00:35] SPEAKER: - Yeah, well, maybe not for packaged goods.
[00:38] SPEAKER: - What was the best action figure you got for free?
[00:41] SPEAKER: - Oh, I don't know if I ever sent off for anything.
[00:43] SPEAKER: I probably did.
[00:44] SPEAKER: - I got Yak Face from "Return of the Jedi."
[00:47] SPEAKER: - Yak Face?
[00:47] SPEAKER: - Yeah, he was one of the Jabba's Palace aliens.
[00:51] SPEAKER: I got him and I got an emperor, I think.
[00:53] SPEAKER: - Yakface.com, serving Star Wars collectors worldwide, says...
[00:58] SPEAKER: Oh, there's way too many action figures in here.
[00:59] SPEAKER: - Anyway.
[01:00] SPEAKER: - There were a ton that you could mail off for, yeah.
[01:02] SPEAKER: Boba Fett was a mail-off one at first.
[01:04] SPEAKER: - Oh yeah, that's huge.
[01:05] SPEAKER: I think that mail-in Boba Fett
[01:06] SPEAKER: is maybe the most valuable Star Wars toy that exists.
[01:09] SPEAKER: - Well, that was a thing that you could actually,
[01:11] SPEAKER: the most valuable ones are the Boba Fetts
[01:12] SPEAKER: that had the actual shooting backpack rocket.
[01:15] SPEAKER: - Yeah, like the one, oh, those,
[01:16] SPEAKER: 'cause those didn't make it to the market?
[01:17] SPEAKER: - There's only seven of them or something, yeah.
[01:19] SPEAKER: But yeah, those mail-off Boba Fetts worth quite a bit.
[01:22] SPEAKER: - Oh, anyway, the mister.
[01:24] SPEAKER: - Yeah, back to the mister.
[01:26] SPEAKER: - The magical thing that's happened
[01:27] SPEAKER: is somebody has cloned the DE-10 Nano,
[01:29] SPEAKER: the board that forms the basis of the mister.
[01:31] SPEAKER: - What do you mean clone?
[01:32] SPEAKER: You mean they took the same FPGA and the same arm chip
[01:36] SPEAKER: and jammed them on a board together and-
[01:38] SPEAKER: - So same FPGA, yes, but not same board design.
[01:41] SPEAKER: - Okay.
[01:42] SPEAKER: - So here's what happened is this person, Taki Udon,
[01:45] SPEAKER: is a person in the mister community
[01:47] SPEAKER: who I was not super familiar with,
[01:48] SPEAKER: but they posted on Twitter like a week ago,
[01:51] SPEAKER: a picture of a DE-10.
[01:52] SPEAKER: So the DE-10 Nano is the,
[01:54] SPEAKER: it's made by Terasic, subsidized by Intel.
[01:57] SPEAKER: It's a student academic development board for FPGA stuff,
[02:00] SPEAKER: and that's why it became the basis of the mister project,
[02:03] SPEAKER: 'cause it was subsidized for academic purposes, blah, blah,
[02:05] SPEAKER: blah. - It was available
[02:06] SPEAKER: and inexpensive.
[02:07] SPEAKER: - People know the story.
[02:08] SPEAKER: It is way less inexpensive than it used to be.
[02:10] SPEAKER: It's like pushing $250 now.
[02:12] SPEAKER: I think you can at least get them now,
[02:13] SPEAKER: 'cause for a while it was pushing 250
[02:15] SPEAKER: and you couldn't even find them.
[02:16] SPEAKER: I think they are purchasable now,
[02:18] SPEAKER: but the price has inflated so much
[02:19] SPEAKER: that it's kind of started growing out of reach
[02:22] SPEAKER: of what people want to spend
[02:23] SPEAKER: on an emulation retro device, right?
[02:26] SPEAKER: - Wow, yeah, they've gotten really expensive.
[02:27] SPEAKER: Even on mister add-ons, they're 250 bucks
[02:30] SPEAKER: and they are currently unavailable.
[02:32] SPEAKER: - Yes, so this clone that Maki Uno posted a picture of,
[02:35] SPEAKER: it's not the exact same board layout.
[02:37] SPEAKER: It's very similar.
[02:38] SPEAKER: It's the same size, the same form factor,
[02:39] SPEAKER: but you can see looking at it,
[02:41] SPEAKER: there are fewer traces, there are fewer resistors,
[02:44] SPEAKER: whatever on there, like there's just less stuff on the board
[02:47] SPEAKER: and some of the ports have been changed as well,
[02:48] SPEAKER: but it is that same SOC.
[02:50] SPEAKER: The SOC on that thing is made by Altera.
[02:52] SPEAKER: It's called the Cyclone 5, which is both the FPGA
[02:55] SPEAKER: and there's a single arm core on that same chip,
[02:57] SPEAKER: which is what runs the Linux in that thing
[02:59] SPEAKER: that handles file IO and networking and stuff like that.
[03:02] SPEAKER: So everybody looked at that and was like,
[03:05] SPEAKER: how is this possible?
[03:07] SPEAKER: Because if you go to, I can't remember if I went
[03:08] SPEAKER: to Digi-Key or Mouser or one of the other,
[03:10] SPEAKER: if you go look up the Cyclone 5 on,
[03:11] SPEAKER: I think it was Digi-Key that I looked at,
[03:13] SPEAKER: the chip alone, they are selling for $325.
[03:16] SPEAKER: - Like just the bare chip, not attached to a board.
[03:19] SPEAKER: - Just the FPGA.
[03:20] SPEAKER: - Yeah, that's a lot.
[03:21] SPEAKER: - So people were like, what are you doing?
[03:22] SPEAKER: Are you harvesting FPGAs off of defective
[03:26] SPEAKER: or like end of life devices
[03:28] SPEAKER: that you're getting your hands on?
[03:29] SPEAKER: 'Cause that happens.
[03:30] SPEAKER: You know, how people harvest ICs all the time
[03:32] SPEAKER: off of old stuff to repurpose.
[03:34] SPEAKER: - That's where all the Mr. SDRAM guests come from
[03:36] SPEAKER: for the most part.
[03:37] SPEAKER: - Or people were like, are you using some kind
[03:39] SPEAKER: of weird clone that might not be reliable
[03:41] SPEAKER: or might be inferior in some way?
[03:43] SPEAKER: So finally somebody tweeted at him about that issue
[03:47] SPEAKER: and he was just like, they were like, hey,
[03:49] SPEAKER: you're selling this Mr. Clone for way less
[03:51] SPEAKER: than just this chip costs.
[03:52] SPEAKER: And he was like, yeah,
[03:53] SPEAKER: that's the narrative that's going around,
[03:54] SPEAKER: but Altera actually gave an incredibly good competitive price
[03:58] SPEAKER: at bulk order volume.
[04:00] SPEAKER: Basically he's saying like, this thing is worth,
[04:02] SPEAKER: or this thing costs way, way, way less
[04:04] SPEAKER: than you think it does,
[04:05] SPEAKER: based on what these like small batch part sellers
[04:07] SPEAKER: are dealing it.
[04:08] SPEAKER: So this kind of changes everything in that scene.
[04:11] SPEAKER: - Yeah, 'cause like a $99 board in there means
[04:13] SPEAKER: you can build a Mr. for what the D10 nano board costs
[04:16] SPEAKER: right now, basically.
[04:17] SPEAKER: - So there's multiple components to this.
[04:18] SPEAKER: Actually, yes, what you just said is the first one,
[04:20] SPEAKER: it's just gonna be way, way lower cost of entry
[04:22] SPEAKER: to get into this thing now.
[04:23] SPEAKER: 'Cause it's a $99 board.
[04:25] SPEAKER: They have also redesigned the SDRAM
[04:27] SPEAKER: that usually goes for upwards of 60 bucks to 15.
[04:30] SPEAKER: - Oh, thank God.
[04:31] SPEAKER: - So a full Mr. set up now is assuming all this works,
[04:34] SPEAKER: it's gonna cost $115.
[04:35] SPEAKER: Full meaning like bare bones,
[04:37] SPEAKER: like you can play games on it, but that's about it.
[04:39] SPEAKER: - But then the other thing is,
[04:40] SPEAKER: if we're not relying on that D10 nano board,
[04:42] SPEAKER: we can also do things like build different form factors
[04:44] SPEAKER: like the-
[04:45] SPEAKER: - That is exactly it.
[04:46] SPEAKER: So that's what's really exciting about this.
[04:48] SPEAKER: But before I even get to that,
[04:49] SPEAKER: like even this first clone board they're working on,
[04:52] SPEAKER: they've made some minor improvements
[04:53] SPEAKER: that even there are gonna be huge.
[04:55] SPEAKER: Like, you had to get your own USB OTG hub
[04:58] SPEAKER: to plug into the D10.
[04:59] SPEAKER: 'Cause the D10 can't take just like a controller.
[05:01] SPEAKER: You can't just plug that in and have it see a USB device.
[05:04] SPEAKER: It needs a, which costs like 50 bucks
[05:06] SPEAKER: if you get the nice USB hub board add on.
[05:09] SPEAKER: They've built the OTG hub right into this clone port
[05:12] SPEAKER: and put a USB-A port on it.
[05:13] SPEAKER: You don't even need a USB hub anymore.
[05:15] SPEAKER: You can buy just this board and that RAM
[05:17] SPEAKER: and plug your controller straight into this thing.
[05:18] SPEAKER: The point is they're making little design improvements
[05:21] SPEAKER: or to step back, the real point is
[05:23] SPEAKER: now they are no longer beholden to whatever dev boards
[05:26] SPEAKER: are coming out of Terasic or Xilinx
[05:27] SPEAKER: or whoever they would have had to repurpose
[05:30] SPEAKER: like expensive dev boards from in the past.
[05:32] SPEAKER: Now they can build their own boards
[05:34] SPEAKER: purpose designed to spec exactly what they want.
[05:36] SPEAKER: - For old computer and video game emulation.
[05:39] SPEAKER: That is fantastic.
[05:40] SPEAKER: - The FPGA is the only thing on that thing
[05:41] SPEAKER: that actually really matters.
[05:43] SPEAKER: That actually cost money and that was hard to get.
[05:45] SPEAKER: Now that that thing apparently is not hard to get
[05:47] SPEAKER: or expensive anymore,
[05:48] SPEAKER: the community can just start building its own boards
[05:50] SPEAKER: around that ship to do exactly what they want
[05:52] SPEAKER: and nothing else.
[05:53] SPEAKER: - Oh man.
[05:54] SPEAKER: - Yeah, so we're basically gonna start getting boards now
[05:56] SPEAKER: that do more and cost less because they don't have
[05:59] SPEAKER: all the stuff on that development board you didn't need
[06:01] SPEAKER: but they do have stuff that wouldn't have been on there.
[06:03] SPEAKER: - So does that mean also we'll see handheld stuff?
[06:05] SPEAKER: - Yes, so he's already said flat out.
[06:07] SPEAKER: He's like, hey, this clone board that is the same form factor
[06:09] SPEAKER: that aims to just be 100% compatible with the real thing
[06:12] SPEAKER: is going to come first.
[06:13] SPEAKER: Then we are working on a much more elaborate board
[06:16] SPEAKER: in a console style form factor
[06:17] SPEAKER: that's gonna have a lot more stuff built into it.
[06:19] SPEAKER: So like he already said on the Mr. Discord,
[06:21] SPEAKER: the RAM is gonna be built into that board
[06:23] SPEAKER: but you can imagine what else they might put in there.
[06:24] SPEAKER: Like wifi and Bluetooth could be built in
[06:27] SPEAKER: 'cause you need adapters for that right now.
[06:29] SPEAKER: - There's no reason you couldn't put the D-pads
[06:31] SPEAKER: and buttons and triggers and stuff on there.
[06:33] SPEAKER: - So I fully expect one of these nice console style versions
[06:36] SPEAKER: to have all the analog video outputs hardware built in
[06:39] SPEAKER: 'cause right now you have to get yet another add on board
[06:41] SPEAKER: to add that so they could just put the VGA output,
[06:44] SPEAKER: the analog video out right on that thing.
[06:46] SPEAKER: - What bus does the analog video go?
[06:48] SPEAKER: Does it go over I2C or something
[06:50] SPEAKER: or is it on some other weird bus?
[06:52] SPEAKER: - It goes over the GPIO headers.
[06:53] SPEAKER: So maybe that is I2C, I'm not sure.
[06:56] SPEAKER: - But it's probably they're just saying,
[06:57] SPEAKER: "Hey, the GPIO, these headers are the analog driver outs."
[07:01] SPEAKER: - Yeah, so that is actually the big quandary right now
[07:04] SPEAKER: is you can't have,
[07:05] SPEAKER: you can only have either the analog video out
[07:07] SPEAKER: or a second stick RAM,
[07:08] SPEAKER: which second stick RAM is not that useful right now
[07:11] SPEAKER: but there are some very limited use cases for it.
[07:12] SPEAKER: Anyway, the sky's the limit now
[07:14] SPEAKER: for what they are going to be able to just build themselves
[07:17] SPEAKER: for this project.
[07:18] SPEAKER: - That's exciting.
[07:19] SPEAKER: - It's super exciting.
[07:19] SPEAKER: A handheld, they already flat out said
[07:21] SPEAKER: after that console thing we're doing,
[07:23] SPEAKER: we're gonna make a handheld.
[07:24] SPEAKER: - Wow.
[07:25] SPEAKER: - 'Cause this thing also uses less power than the D10
[07:27] SPEAKER: 'cause they're using better power switching hardware
[07:29] SPEAKER: or whatever.
[07:30] SPEAKER: - So how does this new FPGA compare
[07:33] SPEAKER: in terms of performance to the,
[07:35] SPEAKER: is it the same, it's the same cycle in five?
[07:37] SPEAKER: - Exact same chip.
[07:37] SPEAKER: - Okay.
[07:38] SPEAKER: - Yeah, like exact same, like it runs the same software.
[07:40] SPEAKER: He said they didn't even have to fork the Mr. Software
[07:42] SPEAKER: and tweak anything, it's running the stock stuff.
[07:44] SPEAKER: - Okay, so then where does this leave the cores
[07:47] SPEAKER: that we can't run on the current D10 Nano?
[07:50] SPEAKER: Probably the same place.
[07:51] SPEAKER: Like we're gonna have the same upper limit on this.
[07:53] SPEAKER: - Yeah, same chip, same logic elements, same everything.
[07:56] SPEAKER: And they're going for a hundred percent compatibility
[07:58] SPEAKER: so it'll have all the same drawbacks for now.
[08:00] SPEAKER: The thing that I, you know, maybe more learned people
[08:02] SPEAKER: can step in here and add some context
[08:04] SPEAKER: but the thing that really jumps out to me though now
[08:07] SPEAKER: is like what happens when a better FPGA
[08:10] SPEAKER: it's this kind of low sensible volume pricing
[08:13] SPEAKER: where now you don't need to wait for some company
[08:15] SPEAKER: to put out a like an $800 development board
[08:17] SPEAKER: that happens to have a better FPGA on it.
[08:19] SPEAKER: If you can just get those chips directly
[08:21] SPEAKER: then like the successor to the Mr.
[08:23] SPEAKER: could just be built to purpose, right?
[08:25] SPEAKER: - Is this just happening now
[08:27] SPEAKER: because somebody like called whoever makes the Cyclone
[08:30] SPEAKER: and was like, "Hey, would you like to buy some of those?"
[08:32] SPEAKER: Or like presumably somebody had to write a check
[08:35] SPEAKER: for them to get bulk pricing on this, right?
[08:37] SPEAKER: - Yeah, I mean, it sounds like they contacted
[08:38] SPEAKER: the manufacturer directly, but by all accounts
[08:41] SPEAKER: it was all just driven by the fact that the prices
[08:43] SPEAKER: just keep going up on this stuff rather than down.
[08:45] SPEAKER: - I guess it makes it that when the prices keep going up
[08:48] SPEAKER: there's a place where the line between the price
[08:51] SPEAKER: the current price of the existing thing
[08:53] SPEAKER: and the cost of making a new thing cross
[08:56] SPEAKER: and then it makes sense to start making the new thing.
[08:58] SPEAKER: Yeah, man, that's cool.
[08:59] SPEAKER: - It's awesome.
[08:59] SPEAKER: I mean, my Mr. set up when I got in
[09:01] SPEAKER: was like 220 all in for everything.
[09:04] SPEAKER: And now you see regularly see bundles going around
[09:06] SPEAKER: for like $600 granted that has like kind of everything
[09:09] SPEAKER: you could possibly get for it.
[09:10] SPEAKER: But there's this Mars project they're saying
[09:12] SPEAKER: is gonna be like 700.
[09:13] SPEAKER: Like it was just like this race to the top.
[09:15] SPEAKER: What's the name of the new board?
[09:17] SPEAKER: - There is no name yet.
[09:18] SPEAKER: Like there's just kind of, you know,
[09:20] SPEAKER: I'll throw a link to that video in the show notes for this
[09:22] SPEAKER: where he kind of talks through his methodology
[09:25] SPEAKER: and design philosophy and stuff.
[09:26] SPEAKER: You know, I should offer a caveat here probably.
[09:28] SPEAKER: I don't think this person has actually really delivered
[09:30] SPEAKER: any kind of hardware in the scene yet before.
[09:33] SPEAKER: So this could be all a bunch of nonsense,
[09:35] SPEAKER: smoke and mirrors until we have products in our hands
[09:36] SPEAKER: and we can test them and everything.
[09:37] SPEAKER: But he did post a video of the prototype
[09:40] SPEAKER: hooked up and working yesterday.
[09:42] SPEAKER: So it's like, seems pretty legit so far,
[09:44] SPEAKER: but just to summarize though, it's like a week or two ago,
[09:48] SPEAKER: the whole Mr. Project felt kind of stagnant,
[09:50] SPEAKER: especially on the hardware side.
[09:51] SPEAKER: Like there just hasn't really been much going on
[09:54] SPEAKER: other than like some incremental progress
[09:56] SPEAKER: on cores here and there, but especially like hardware wise,
[09:58] SPEAKER: like it's just kind of been the hardware
[10:00] SPEAKER: for the last like two, three years.
[10:02] SPEAKER: And all of a sudden, like now out of nowhere now,
[10:03] SPEAKER: it's like, we've got a hundred dollar Mr. coming.
[10:05] SPEAKER: We've got a big elaborate like console all in one form factor
[10:09] SPEAKER: with all the features built into it.
[10:10] SPEAKER: And he's even saying that console thing
[10:11] SPEAKER: has got like one big new feature
[10:13] SPEAKER: that is a secret that nobody has done before.
[10:15] SPEAKER: And I have no idea what that's even gonna be.
[10:18] SPEAKER: Then a handheld,
[10:19] SPEAKER: which he actually just said on the discord is dockable.
[10:22] SPEAKER: So that's probably gonna be like a switch
[10:24] SPEAKER: analog pocket situation where you can play it handheld
[10:26] SPEAKER: and plug it into a TV.
[10:28] SPEAKER: And then there's like, I didn't even mention,
[10:29] SPEAKER: there's two more like lower cost reduced feature set
[10:32] SPEAKER: consoles coming by like all of this by the end of the year.
[10:35] SPEAKER: And who knows like what the Mr. 2 could be built around
[10:38] SPEAKER: a whole new FPGA at some point now that this seems like
[10:40] SPEAKER: it might be possible from a supply chain standpoint,
[10:42] SPEAKER: it's just like a crazy amount of stuff happening at once,
[10:45] SPEAKER: which again, granted is all being promised by one person,
[10:48] SPEAKER: but if all this stuff pans out,
[10:49] SPEAKER: it's gonna be like retro game Christmas.
[10:51] SPEAKER: (upbeat music)
[11:12] SPEAKER: (upbeat music continues)
[11:19] SPEAKER: - Welcome to Brad and Will Made a Tech Pod.
[11:22] SPEAKER: I'm Will.
[11:22] SPEAKER: - I'm Brad.
[11:23] SPEAKER: Hello.
[11:24] SPEAKER: - I'm a little hoarse.
[11:25] SPEAKER: I was doing some screaming this morning.
[11:27] SPEAKER: - I am also a bit hoarse.
[11:28] SPEAKER: Some high jinks, some subterranean high jinks were happening.
[11:32] SPEAKER: - I play those kinds of games and I'm like,
[11:34] SPEAKER: I'm not gonna do the screaming thing.
[11:36] SPEAKER: And then they're very good at the jump scares
[11:38] SPEAKER: and you end up screaming and usually dying in my case.
[11:42] SPEAKER: I think you were more effective at running away usually.
[11:44] SPEAKER: - Oh, you're also doing it for the likes though.
[11:47] SPEAKER: - That's true.
[11:48] SPEAKER: I mean, if I get the likes, if I get those,
[11:50] SPEAKER: if people like to subscribe,
[11:52] SPEAKER: any amount of physical harm, it's worth it.
[11:54] SPEAKER: - What good is your life if you don't have likes?
[11:56] SPEAKER: - It's, God, that's grim.
[11:58] SPEAKER: - We were playing content warning, we should say.
[12:01] SPEAKER: - Yeah, we were playing content warning
[12:02] SPEAKER: on Nextlander this morning.
[12:04] SPEAKER: - Pretty awesome, which is basically a lethal company,
[12:06] SPEAKER: except instead of trying to get scrap,
[12:07] SPEAKER: you're trying to record your friends dying
[12:09] SPEAKER: for social media clout.
[12:12] SPEAKER: - And speaking of home video formats.
[12:15] SPEAKER: - Okay, all right, nice.
[12:16] SPEAKER: - Bringing it on back to the good old days.
[12:20] SPEAKER: We had a request, several users asked us
[12:23] SPEAKER: to dig into this over the last four months,
[12:24] SPEAKER: so I'm not gonna name anyone in particular,
[12:26] SPEAKER: but we had a request for an episode about video formats,
[12:31] SPEAKER: home video media formats specifically.
[12:33] SPEAKER: - History of home video, I guess.
[12:35] SPEAKER: - Yeah, and we started doing the research on this
[12:38] SPEAKER: and realized there's a lot, actually,
[12:42] SPEAKER: kind of a shocking amount to talk about,
[12:44] SPEAKER: starting with a little bit of reel-to-reel film,
[12:50] SPEAKER: like 16 and eight millimeter film,
[12:53] SPEAKER: going all the way through.
[12:54] SPEAKER: So we're gonna do this in two parts.
[12:55] SPEAKER: I don't know if we're gonna do 'em back-to-back,
[12:56] SPEAKER: but we're gonna do 'em in two parts
[12:58] SPEAKER: where the first one is the analog formats
[13:01] SPEAKER: and then when it jumps over to the digital formats,
[13:04] SPEAKER: we're gonna take a pause and then we're gonna do that
[13:06] SPEAKER: as a separate thing, 'cause in some ways,
[13:09] SPEAKER: the analog stuff is really weird
[13:10] SPEAKER: and there's a lot of choices made in the '70s and '80s.
[13:16] SPEAKER: - The real Wild West kind of vibe to everything, for sure.
[13:20] SPEAKER: - Yeah, but also the dawn of DVD and digital eight
[13:23] SPEAKER: and all those kind of digital tape formats
[13:25] SPEAKER: felt like the beginning of the modern age in a lot of ways,
[13:30] SPEAKER: where we were just distributing the bits on disks
[13:32] SPEAKER: instead of over the internet like we do now.
[13:34] SPEAKER: - Yeah, there's kind of a tidy dividing line, I think,
[13:36] SPEAKER: between this analog era
[13:37] SPEAKER: and when digital stuff started catching on.
[13:39] SPEAKER: I mean, probably mid-'90s, but like '97 with the DVDs,
[13:43] SPEAKER: kind of a real beginning of this second era.
[13:46] SPEAKER: So I guess we'll be going up to kind of right before that.
[13:48] SPEAKER: - Yeah, that sounds right.
[13:49] SPEAKER: So we're looking at specifically stuff
[13:53] SPEAKER: that was meant for home.
[13:54] SPEAKER: So we're not gonna talk about like commercial Betamax
[13:57] SPEAKER: or commercial SVHS or old reel-to-reel tapes
[13:59] SPEAKER: or anything like that.
[14:00] SPEAKER: - I do have this Betacam Wikipedia tab open.
[14:02] SPEAKER: - Okay, so we can talk about Betacam for a sec,
[14:05] SPEAKER: 'cause like, you know, anyway, but for the most part,
[14:08] SPEAKER: it's stuff that's designed to hook up to a TV
[14:11] SPEAKER: and watch at home, whether it's prerecorded
[14:14] SPEAKER: or something that you record yourself,
[14:15] SPEAKER: like in terms of camcorders, stuff like that.
[14:17] SPEAKER: - Yeah, yeah, I think because like today,
[14:19] SPEAKER: it is utterly impossible to remember this,
[14:21] SPEAKER: but I think even when you and I were growing up,
[14:23] SPEAKER: or I mean, you're like four years older than me.
[14:25] SPEAKER: - I was born in '75.
[14:26] SPEAKER: - You probably remember maybe a little better than I do
[14:28] SPEAKER: a time before you could watch video on demand at home
[14:32] SPEAKER: in any way whatsoever.
[14:33] SPEAKER: Like I barely even remember that
[14:35] SPEAKER: because by the time I have memories,
[14:37] SPEAKER: we had a VCR in the house, right?
[14:38] SPEAKER: But like, it was not much before that,
[14:41] SPEAKER: that you watched what was on broadcast TV
[14:43] SPEAKER: or you watched nothing.
[14:44] SPEAKER: - So what I remember explicitly,
[14:47] SPEAKER: there's two early VHS memories that I have.
[14:49] SPEAKER: One is that in like 1981,
[14:50] SPEAKER: when I was probably six years old,
[14:53] SPEAKER: the guy who, my dad, the guy who had the office,
[14:56] SPEAKER: kind of like his office neighbor across the street
[14:59] SPEAKER: from his realtor shop, ran a copying machine company
[15:03] SPEAKER: and he always bought new technology stuff.
[15:05] SPEAKER: And he loaned us his VHS, portable VHS kit,
[15:10] SPEAKER: which came in two like shoulder sling bags
[15:13] SPEAKER: that had a giant fat connector between them.
[15:16] SPEAKER: And one had the tape unit in it,
[15:18] SPEAKER: and one was the thing that you hooked up to the TV.
[15:20] SPEAKER: And he gave us a copy of, I think, "The Black Hole,"
[15:23] SPEAKER: which we watched when I was six years old
[15:25] SPEAKER: and it scared the living shit out of me.
[15:27] SPEAKER: The other one was when I went to my grandparents' house
[15:31] SPEAKER: that same year, probably maybe the year after,
[15:33] SPEAKER: they had a tape player that I assume,
[15:37] SPEAKER: I don't know how they did it actually,
[15:38] SPEAKER: but it had a button you could press
[15:39] SPEAKER: that would record what you were playing on the tape
[15:42] SPEAKER: to some sort of internal buffer,
[15:44] SPEAKER: which I assume was just a tape
[15:45] SPEAKER: that was permanently built into the box.
[15:48] SPEAKER: And then you could rewind that and play that back
[15:51] SPEAKER: and record it on another tape.
[15:52] SPEAKER: So you could do a two-generation dupe of a tape,
[15:57] SPEAKER: which seems like the kind of thing
[15:58] SPEAKER: that would have gotten you in trouble with the law,
[16:00] SPEAKER: with the studios back then,
[16:03] SPEAKER: 'cause it was definitely meant for duplication.
[16:05] SPEAKER: But anyway, so those are my two.
[16:09] SPEAKER: Yeah, we did that.
[16:10] SPEAKER: I feel like I made a copy of Buck Rogers for my grandmother
[16:15] SPEAKER: 'cause she liked Buck Rogers.
[16:16] SPEAKER: - A noble purpose.
[16:17] SPEAKER: Our first VCR was one of those two unit doohickeys.
[16:20] SPEAKER: I mean, one side was literally just the tape deck
[16:23] SPEAKER: and kind of nothing else.
[16:24] SPEAKER: On the other side, I guess, was the sort of tuner
[16:27] SPEAKER: and playback kind of part.
[16:28] SPEAKER: - Well, back then, they were all top loading, right?
[16:30] SPEAKER: Those two side ones were definitely,
[16:32] SPEAKER: the one that we borrowed was a top loader.
[16:34] SPEAKER: You had to put it in the top and then smash the thing down.
[16:37] SPEAKER: But before all that, there was home film.
[16:43] SPEAKER: Home film was wildly popular in the '60s and '70s.
[16:46] SPEAKER: It was kind of expensive 'cause you had to get
[16:48] SPEAKER: a million little pictures developed
[16:49] SPEAKER: every time you send a piece of a film in.
[16:51] SPEAKER: You usually had to mail it off someplace.
[16:53] SPEAKER: But cameras, projectors, and development
[16:56] SPEAKER: were things that you could order from Sears or whatever,
[16:59] SPEAKER: and you would get your camera and your projector.
[17:02] SPEAKER: And then for like around the modern equivalent of a grand,
[17:06] SPEAKER: they were a couple hundred bucks in most cases,
[17:08] SPEAKER: you could record video and send it off someplace
[17:11] SPEAKER: and you'd come back two weeks later
[17:12] SPEAKER: and you could watch videos of your family
[17:14] SPEAKER: as if they were shot by cinematographers
[17:16] SPEAKER: and auteurs in Hollywood.
[17:17] SPEAKER: - Or you could record films.
[17:19] SPEAKER: - Films, did I say videos?
[17:20] SPEAKER: - Yes, you said videos and I wonder, that makes me wonder,
[17:23] SPEAKER: like, what was the genesis of the word video
[17:25] SPEAKER: and when did that actually come into common usage?
[17:27] SPEAKER: Because back then it was films generally, right?
[17:30] SPEAKER: Or movies that people would say,
[17:31] SPEAKER: but like where did the word video come from
[17:34] SPEAKER: and when did that become?
[17:35] SPEAKER: - I wonder if video had to do with the,
[17:37] SPEAKER: 'cause for a long time, if you think about it,
[17:39] SPEAKER: like the ability to record TV was a real innovation.
[17:44] SPEAKER: For much of the first like first 15 years of TV,
[17:47] SPEAKER: in a lot of cases, the shows were literally broadcast
[17:51] SPEAKER: and blasted out of the airwaves
[17:53] SPEAKER: and there was no method to record them
[17:55] SPEAKER: other than pointing a camera at a screen,
[17:58] SPEAKER: a film camera at the screen, right?
[18:00] SPEAKER: So you either did things on film, shot things on film
[18:04] SPEAKER: and then did a tele scene where you projected the film
[18:07] SPEAKER: onto a wall and used the video camera just to show that
[18:11] SPEAKER: or you did a straight live broadcast
[18:14] SPEAKER: of whatever it was you were showing.
[18:17] SPEAKER: Do you find some stuff about video?
[18:18] SPEAKER: - Yes, yep.
[18:19] SPEAKER: - You look like a man who has information.
[18:21] SPEAKER: - At least according to the online etymology dictionary,
[18:23] SPEAKER: the word video was coined in 1935
[18:26] SPEAKER: as a visual equivalent of audio from a Latin word
[18:29] SPEAKER: that's spelled the same way, how's your Latin?
[18:31] SPEAKER: - I took four years in high school.
[18:33] SPEAKER: - B-I-D-E-O?
[18:35] SPEAKER: - Yeah, that reads as video, I believe.
[18:37] SPEAKER: - This is also just pronounced video, Latin?
[18:40] SPEAKER: - Video is, I think, to see, vidi, vidi, vidi, vidi, vidi.
[18:43] SPEAKER: - Yes, it translates to I see,
[18:46] SPEAKER: but how would you pronounce it?
[18:48] SPEAKER: - Well, it's a dead language, so we have no idea.
[18:49] SPEAKER: - Oh really, is it actually--
[18:50] SPEAKER: - If you wanna know how to pronounce Latin,
[18:52] SPEAKER: you have to ask somebody who's Catholic.
[18:53] SPEAKER: I'm, I am not, I just took Latin in high school.
[18:56] SPEAKER: - I thought Latin pronunciation
[18:57] SPEAKER: was still at least somewhat understood.
[18:59] SPEAKER: Or wait, actually-- - Yeah, sure it is,
[19:00] SPEAKER: but four years in high school.
[19:01] SPEAKER: - Yeah, haven't I seen some arguments
[19:02] SPEAKER: about how a C is pronounced in Latin,
[19:04] SPEAKER: like isn't there disagreement?
[19:06] SPEAKER: - Cuz versus, there's no suh sound, I think, is the, yeah.
[19:10] SPEAKER: There's a lot of stuff, there's like Js or Js or,
[19:13] SPEAKER: depending on whether you learn Latin,
[19:16] SPEAKER: ecclesiastical Latin or classical Latin,
[19:19] SPEAKER: depends on how you pronounce the Cs
[19:21] SPEAKER: and the Js and stuff like that.
[19:23] SPEAKER: I have some questions about "Indiana Jones 3"
[19:26] SPEAKER: as a result of this, just for the--
[19:29] SPEAKER: - Fair, fair.
[19:30] SPEAKER: Anyway, like I, you know, the history of like film stock
[19:33] SPEAKER: and cinema and all that stuff,
[19:34] SPEAKER: obviously way out of scope for this podcast,
[19:36] SPEAKER: but it probably goes without saying
[19:37] SPEAKER: that these '50s, '60s, well, mainly '60s, right?
[19:40] SPEAKER: You said it was when this stuff became big,
[19:41] SPEAKER: but these like '60s and '70s film formats
[19:44] SPEAKER: are just smaller, less capable versions
[19:47] SPEAKER: of the same things they were projecting
[19:48] SPEAKER: and filming movies on since the beginning of time.
[19:50] SPEAKER: - Kind of, I mean, there were three main home uses.
[19:53] SPEAKER: There was 16 millimeter,
[19:54] SPEAKER: which is based on the cheap film standard.
[19:57] SPEAKER: It's a cheaper film standard.
[19:59] SPEAKER: It was introduced in 1923.
[20:01] SPEAKER: The big thing about that is that film stock back then
[20:03] SPEAKER: was a nitrate base, which was basically,
[20:05] SPEAKER: it meant you were carrying canisters full of bombs around.
[20:08] SPEAKER: (laughing)
[20:09] SPEAKER: And the acetate base would burn,
[20:12] SPEAKER: but not quite as enthusiastically.
[20:15] SPEAKER: 24 frames per second, just like 35 mil,
[20:18] SPEAKER: like clerks and scrubs and movies in "Rise Kingdom,"
[20:21] SPEAKER: and a bunch of movies are shot on 16 mil film still.
[20:26] SPEAKER: Eight millimeter was released in 1932.
[20:28] SPEAKER: It was even cheaper than eight millimeter.
[20:30] SPEAKER: Usually you ran that at, yeah, than 16 millimeter, sorry.
[20:34] SPEAKER: Usually you ran that at 16 frames per second.
[20:37] SPEAKER: This was the one that was popular at home most.
[20:40] SPEAKER: It was, the film was pretty cheap.
[20:43] SPEAKER: There was sound available on a magnetic track
[20:46] SPEAKER: or on a light track on the side.
[20:48] SPEAKER: - Oh, that's fascinating.
[20:49] SPEAKER: I had no idea about that.
[20:50] SPEAKER: - Yeah, and it was discontinued in '92,
[20:52] SPEAKER: which presumably VHS was the final nail
[20:55] SPEAKER: in the coffin of eight millimeter.
[20:57] SPEAKER: And then Super 8 was eight millimeter film
[20:59] SPEAKER: that had smaller perforation,
[21:01] SPEAKER: so there's a bit more image space
[21:02] SPEAKER: on either side of the frame.
[21:04] SPEAKER: And it came in a cartridge, so it was easier to,
[21:07] SPEAKER: you didn't have to thread stuff through.
[21:09] SPEAKER: - Okay, yes, I guess I have seen those types of cameras
[21:12] SPEAKER: that have a little cartridge thing.
[21:14] SPEAKER: - Yeah, it had a little hook thing
[21:15] SPEAKER: that you smacked down
[21:16] SPEAKER: and it just kind of fed it automatically.
[21:18] SPEAKER: It also did sound, and usually it was 18 frames a second
[21:21] SPEAKER: as well.
[21:22] SPEAKER: - Probably in the major motion picture,
[21:24] SPEAKER: Super 8 is where I saw a Super 8 camera.
[21:26] SPEAKER: I have to guess.
[21:27] SPEAKER: - Oh, maybe.
[21:28] SPEAKER: - Among other places,
[21:29] SPEAKER: but I did not realize there were home film solutions
[21:33] SPEAKER: for capturing sound back then.
[21:34] SPEAKER: Like I, my mom has a family friend
[21:37] SPEAKER: or like I had a family friend.
[21:38] SPEAKER: This was like more like my grandparents' family friend,
[21:41] SPEAKER: but he passed away some years ago
[21:43] SPEAKER: and his son going through his things later
[21:45] SPEAKER: found a reel of what I guess must've been 16 millimeter film
[21:49] SPEAKER: and had it developed,
[21:50] SPEAKER: or maybe it had already been developed anyway.
[21:52] SPEAKER: Nobody knew what was on it until they projected it.
[21:54] SPEAKER: And it turned out to be a bunch of footage
[21:56] SPEAKER: of my grandparents in their thirties
[21:58] SPEAKER: and my mom when she was like seven.
[22:00] SPEAKER: - Oh man.
[22:01] SPEAKER: - But that had no sound, you know?
[22:02] SPEAKER: So I just, I associate,
[22:04] SPEAKER: or maybe it's like a wonder years thing as well, right?
[22:06] SPEAKER: Like I just associate that 50s, 60s type of home movie
[22:09] SPEAKER: shot on film as having no sound.
[22:12] SPEAKER: - So from what I could tell, the sound was not,
[22:15] SPEAKER: the sound added a lot of cost.
[22:17] SPEAKER: You think about what microphones were like back then.
[22:19] SPEAKER: I don't believe, like my family's home movies
[22:22] SPEAKER: from that time did not have sound either.
[22:24] SPEAKER: When we had them digitized to VHS or DVD or whatever,
[22:27] SPEAKER: the people who, the people who did the digitization
[22:31] SPEAKER: picked like stock music and put like,
[22:34] SPEAKER: if it was like a kid playing,
[22:35] SPEAKER: there'd be some sort of rambunctious
[22:37] SPEAKER: kind of xylophone music.
[22:39] SPEAKER: Yeah, it was, it was funny.
[22:40] SPEAKER: - That's exactly what we got
[22:41] SPEAKER: with whoever they sent that thing off to.
[22:43] SPEAKER: And the first thing I did was just mute it
[22:45] SPEAKER: while I was watching it.
[22:46] SPEAKER: - Yeah, that seems right.
[22:48] SPEAKER: So then, and then before that,
[22:49] SPEAKER: there was a reel to reel tapes, which were not,
[22:53] SPEAKER: after that rather, there were reel to reel tapes,
[22:55] SPEAKER: which were analog magnetic tapes.
[22:58] SPEAKER: They were not, they were available for consumers,
[23:01] SPEAKER: but they were not particularly common.
[23:03] SPEAKER: They were fiddly 'cause you had to thread the tape manually
[23:06] SPEAKER: through the read and write heads.
[23:07] SPEAKER: And people mostly used them to record stuff off of the TV.
[23:10] SPEAKER: They were much more common in a professional context
[23:13] SPEAKER: where they would record like,
[23:16] SPEAKER: yeah, the networks would broadcast stuff over satellite
[23:19] SPEAKER: or microwave feeds to their affiliates
[23:22] SPEAKER: and they'd record those transmissions.
[23:25] SPEAKER: And then they'd air them when it was time to show,
[23:27] SPEAKER: you know, Ozzie and Harriet or whatever,
[23:29] SPEAKER: leave it to Beaver in the afternoon,
[23:30] SPEAKER: probably Star Trek is a better example, syndicated stuff.
[23:33] SPEAKER: - Be clear, we're talking about the big classic console
[23:36] SPEAKER: with two gigantic reels that are just kind of exposed
[23:38] SPEAKER: to the air with the tape between them
[23:40] SPEAKER: that you kind of know what those look like
[23:42] SPEAKER: in your mind's eye.
[23:42] SPEAKER: But I didn't know you could do video on those.
[23:44] SPEAKER: I always thought those were just for audio.
[23:46] SPEAKER: - Well, I mean, they're just tape, right?
[23:49] SPEAKER: - Well, you have to have something to interpret
[23:51] SPEAKER: what's on the tape, right?
[23:52] SPEAKER: And I didn't realize that had been developed
[23:53] SPEAKER: at that time for video.
[23:54] SPEAKER: - Well, so that happened in this, I can't,
[23:58] SPEAKER: I didn't actually find out,
[23:59] SPEAKER: I didn't look to see when that was,
[24:00] SPEAKER: but my recollection is that was during the '60s or late '50s
[24:03] SPEAKER: that we got the ability to easily record stuff
[24:05] SPEAKER: without using film.
[24:08] SPEAKER: So, okay, so that takes us up to this,
[24:10] SPEAKER: probably the late '60s, early '70s.
[24:15] SPEAKER: A lot of like eight millimeter and super eight
[24:18] SPEAKER: were often used for like news journalists.
[24:22] SPEAKER: 16 mil also was used for journalists.
[24:26] SPEAKER: The rise of tape cassettes,
[24:29] SPEAKER: the invention of tape cassettes is the next big thing,
[24:31] SPEAKER: 'cause it took all that mechanism
[24:33] SPEAKER: that was in the reel-to-reel and put it in a container
[24:37] SPEAKER: that let it automatically thread the read and write heads
[24:40] SPEAKER: through the tape in a way
[24:41] SPEAKER: that made it simpler to use, basically.
[24:44] SPEAKER: - And you can see why removing the potential for user error
[24:47] SPEAKER: is huge in that situation,
[24:49] SPEAKER: as fragile as tape is and as fiddly as it would be
[24:51] SPEAKER: to have to string it between reels all the time
[24:53] SPEAKER: and not screw it up.
[24:54] SPEAKER: - Exactly, and that brings us to the great video "War,"
[24:58] SPEAKER: which everybody knows about.
[25:00] SPEAKER: It was, for all intents and purposes, the first format war.
[25:05] SPEAKER: There were two functionally identical products,
[25:07] SPEAKER: one that was open and one that was closed.
[25:09] SPEAKER: Betamax was originally released in 1975,
[25:15] SPEAKER: five days before I was born.
[25:17] SPEAKER: It was the very first in the long line of Sony products
[25:20] SPEAKER: that was pitched as, "This is the good one,
[25:23] SPEAKER: "which is why it's more expensive."
[25:25] SPEAKER: - Boy, that's like the entire theme
[25:28] SPEAKER: of Sony Consumer Electronics for as long as I've known them.
[25:31] SPEAKER: - Yep, I mean, look, it's worked sometimes
[25:33] SPEAKER: and sometimes not so much.
[25:34] SPEAKER: - I mean, look, those TVs were very good,
[25:36] SPEAKER: like the Walkman, the Discman.
[25:38] SPEAKER: They have made a lot of good products over the years.
[25:40] SPEAKER: - The Bravia TVs, they made a lot of money on.
[25:44] SPEAKER: Turns out, in this case, nobody cared, not really.
[25:49] SPEAKER: Technically, it was pretty similar to VHS.
[25:51] SPEAKER: There were 250, so important note here.
[25:54] SPEAKER: On analog video formats,
[26:00] SPEAKER: we measure the lines of light and dark,
[26:03] SPEAKER: like the dark, the bright,
[26:05] SPEAKER: the resolution of the black and white
[26:07] SPEAKER: or the light intensity parts of the picture
[26:12] SPEAKER: separately from the color information, the chroma.
[26:14] SPEAKER: So luminance is the,
[26:16] SPEAKER: luma or luminance is the light and dark,
[26:18] SPEAKER: chroma is the color.
[26:20] SPEAKER: And typically, this split in beta
[26:23] SPEAKER: is pretty representative.
[26:27] SPEAKER: It's 250 lines of luma resolution, the black and white,
[26:30] SPEAKER: 'cause that's what our eyes are more sensitive to,
[26:32] SPEAKER: and 30 lines equivalent of chroma.
[26:36] SPEAKER: So if we're talking about a digital image,
[26:38] SPEAKER: it would be 333 by 486 pixels of luminance,
[26:42] SPEAKER: 40 by 486 of chroma.
[26:44] SPEAKER: - Yeah, I thought this 40 by 486 in the notes was a typo.
[26:47] SPEAKER: Like, I would never have guessed the ratio was that big.
[26:51] SPEAKER: - I mean, if you think about it,
[26:53] SPEAKER: we're just getting the color blobs in the right spot,
[26:55] SPEAKER: and then your brain looks at what's light and what's dark,
[26:58] SPEAKER: and it works itself out.
[26:59] SPEAKER: - Yeah, that makes sense.
[27:00] SPEAKER: I think we've talked about this before.
[27:02] SPEAKER: I figured it was kind of a,
[27:02] SPEAKER: that's a cognitive, neurological perception thing, right?
[27:06] SPEAKER: The brain just kind of makes it work.
[27:08] SPEAKER: - It's that our brains are really good
[27:09] SPEAKER: at detecting light and dark spots from each other,
[27:11] SPEAKER: and kind of crappy at color, is my understanding.
[27:14] SPEAKER: - Sure.
[27:15] SPEAKER: - And so these are,
[27:17] SPEAKER: this information's contained in some bands,
[27:19] SPEAKER: in some bands on the tape.
[27:21] SPEAKER: So a certain number of megahertz goes to luminance,
[27:23] SPEAKER: a certain number of megahertz goes to chroma,
[27:25] SPEAKER: and then a little bit goes to audio.
[27:27] SPEAKER: The higher quality, I argue,
[27:30] SPEAKER: is based entirely on the right head speed of the player
[27:32] SPEAKER: spinning faster than VHS,
[27:34] SPEAKER: which theoretically gave the player more bandwidth.
[27:37] SPEAKER: It had a little bit more resolution, but not that much.
[27:41] SPEAKER: But the main thing, well, okay, so there's two things.
[27:45] SPEAKER: One is that the reason it's called Betamax
[27:47] SPEAKER: is because the mechanism that the tape head uses to,
[27:52] SPEAKER: that pulls, the mechanism that pulls the tape
[27:55] SPEAKER: out of the machine basically jammed a thing up
[27:58] SPEAKER: in the hole in the back of the tape cassette,
[28:03] SPEAKER: and then pulled the tape all the way around the reed head
[28:06] SPEAKER: so it could get to both the inside and the outside,
[28:08] SPEAKER: and it made a shape that looked like the Greek letter beta.
[28:13] SPEAKER: - Okay.
[28:14] SPEAKER: - In the inside the machine,
[28:15] SPEAKER: if you look at it from the top down.
[28:16] SPEAKER: - Sure, that's as good a reason to name it that as any.
[28:19] SPEAKER: - I'm gonna put some show notes in here.
[28:20] SPEAKER: There's a link in the show notes to some YouTube videos
[28:23] SPEAKER: that show the transport mechanisms.
[28:25] SPEAKER: Technology Connections has done a bunch on this
[28:28] SPEAKER: over the years, but let's see if I can embed the video.
[28:32] SPEAKER: I should have done this before we started.
[28:35] SPEAKER: It's a really good, it's really amazing.
[28:38] SPEAKER: I had no idea how these worked,
[28:40] SPEAKER: and it makes me really appreciate the front loading VCR
[28:42] SPEAKER: as an innovation more than I ever did as a youth.
[28:47] SPEAKER: Now, as is often the case, the VHS format,
[28:51] SPEAKER: it does basically the same thing.
[28:54] SPEAKER: They started working in the early '70s and released in '76.
[28:58] SPEAKER: It was pitched as an open competitor
[29:01] SPEAKER: to Sony's licensed Betamax so you could join the coalition
[29:04] SPEAKER: and get cross-licensing or whatever
[29:06] SPEAKER: with everybody else who's working in there.
[29:08] SPEAKER: - Versus, just to be clear, to make a beta deck,
[29:10] SPEAKER: you had to pay Sony royalties, licensing fees?
[29:13] SPEAKER: - You had to pay licensing on each unit,
[29:15] SPEAKER: sold probably to Sony.
[29:18] SPEAKER: They had 12 objectives when they set out to make this,
[29:20] SPEAKER: JVC did this, started this.
[29:22] SPEAKER: They wanted the system to be compatible
[29:23] SPEAKER: with any ordinary TVs.
[29:25] SPEAKER: The picture quality had to be similar
[29:26] SPEAKER: to a normal air broadcast.
[29:28] SPEAKER: The tape must have at least
[29:29] SPEAKER: a two-hour-long recording capacity.
[29:31] SPEAKER: Tapes must be interchangeable between machines.
[29:33] SPEAKER: That means you can record on yours and hand it to me
[29:35] SPEAKER: and I can play it on mine.
[29:37] SPEAKER: The overall system should be versatile,
[29:39] SPEAKER: meaning it can be scaled and expanded,
[29:41] SPEAKER: such as adding video cameras
[29:42] SPEAKER: or dubbing between two recorders, et cetera.
[29:45] SPEAKER: Recorders should be affordable, easy to operate,
[29:47] SPEAKER: and have low maintenance costs.
[29:49] SPEAKER: And the recorders must be capable
[29:50] SPEAKER: of being produced in high volume.
[29:52] SPEAKER: Their parts must be interchangeable
[29:53] SPEAKER: and they must be easy to service.
[29:55] SPEAKER: Pretty straightforward stuff.
[29:56] SPEAKER: - Yeah, it's like a noble list of goals
[29:57] SPEAKER: with the possible exception of picture quality
[29:59] SPEAKER: must be similar to a normal air over-the-air broadcast,
[30:02] SPEAKER: which like kind of stretching the definition
[30:05] SPEAKER: of similar a little bit, but sure.
[30:07] SPEAKER: - I mean, look, the VHS recording was,
[30:12] SPEAKER: in the era of the tubes they were making in 1976,
[30:16] SPEAKER: probably looked similar.
[30:17] SPEAKER: - Yeah, fair.
[30:18] SPEAKER: - I think as the tubes got higher dot pitches
[30:20] SPEAKER: and stuff like that and the TVs got bigger,
[30:23] SPEAKER: the weaknesses of them started to show themselves more,
[30:26] SPEAKER: would be my guess.
[30:27] SPEAKER: - Yeah, that's fair.
[30:27] SPEAKER: I just looked up what became of JVC,
[30:29] SPEAKER: if they're still a thing or not.
[30:30] SPEAKER: They technically are, but they're part of,
[30:33] SPEAKER: they're now part of JVC Kenwood Holdings Incorporated.
[30:37] SPEAKER: I don't feel like JVC is much of a consumer-facing brand.
[30:41] SPEAKER: - I do not think that they are anymore.
[30:46] SPEAKER: So let's see, they did this, they released these in 1976.
[30:51] SPEAKER: The image quality, again, image quality format
[30:54] SPEAKER: is a function of the bandwidth they used in the recording,
[30:56] SPEAKER: multiplied by the tape speed.
[31:00] SPEAKER: It works, the other thing that uses the chroma sub-sampling
[31:04] SPEAKER: where it separates out the brightness and color info
[31:07] SPEAKER: is the JPEG spec.
[31:08] SPEAKER: - Yeah, it's funny, I just saw that in a YouTube video
[31:11] SPEAKER: like two days before we recorded this podcast.
[31:13] SPEAKER: Somebody talking about that's exactly how a JPEG
[31:15] SPEAKER: image compression works.
[31:17] SPEAKER: - So the other thing that happened here
[31:19] SPEAKER: is that they allowed for different tape speeds.
[31:23] SPEAKER: So they identified early that users
[31:27] SPEAKER: were going to care about a number
[31:29] SPEAKER: and they picked the right one.
[31:31] SPEAKER: So they, by doing standard play, medium play,
[31:36] SPEAKER: extended play, and super long play speeds--
[31:38] SPEAKER: - I was just gonna, you didn't write them in the notes,
[31:40] SPEAKER: I was gonna challenge you to name them, but you just did.
[31:43] SPEAKER: Except, was there an MP?
[31:44] SPEAKER: I know there was standard play, long play.
[31:47] SPEAKER: - It was either long play or extended play,
[31:49] SPEAKER: depending on your VCR, I think, probably.
[31:51] SPEAKER: But the point was, you either got two hours,
[31:54] SPEAKER: four hours, or six hours on a standard tape.
[31:57] SPEAKER: And that difference in record speed,
[32:00] SPEAKER: meaning by running the tape through the head slower
[32:02] SPEAKER: and thus degrading your picture quality even further,
[32:05] SPEAKER: but letting you jam more stuff onto your $5 tape,
[32:08] SPEAKER: blank tape, turned out to be a real important decision.
[32:12] SPEAKER: - Yeah, you're really taking me back.
[32:15] SPEAKER: Now that I think about it, for me, it was six hours
[32:18] SPEAKER: per tape or nothing, it was just like,
[32:19] SPEAKER: I've got to cram as much as I can on this thing.
[32:21] SPEAKER: - I set The Simpsons to record every day.
[32:24] SPEAKER: It was on three times a day when I was in college,
[32:26] SPEAKER: and I just recorded an hour and a half of Simpsons
[32:29] SPEAKER: every single day.
[32:29] SPEAKER: - Did you end up with a full library eventually,
[32:31] SPEAKER: or close to it?
[32:33] SPEAKER: - I had a big chunk from the syndication,
[32:36] SPEAKER: whatever was in syndication at the time,
[32:38] SPEAKER: through season nine or something.
[32:40] SPEAKER: - That's pretty impressive.
[32:41] SPEAKER: I checked, it's SP, LP, and EP.
[32:44] SPEAKER: - SP, LP, and EP, okay.
[32:45] SPEAKER: - So I'm pretty sure my VCR, which I have behind me,
[32:50] SPEAKER: was super long play, is what they called that.
[32:53] SPEAKER: - Wait, like your classic, your VCR of record,
[32:57] SPEAKER: the VCR of antiquity, still have?
[33:00] SPEAKER: - I have the VCR that I bought
[33:02] SPEAKER: when I went to college right here.
[33:03] SPEAKER: - Okay, well now I've got to fill,
[33:05] SPEAKER: 'cause he's turning around and picking up
[33:06] SPEAKER: what is sure to be a chunky piece of '80s, maybe '90s.
[33:11] SPEAKER: You went to college.
[33:12] SPEAKER: - '90s, thank you.
[33:13] SPEAKER: - Sure.
[33:14] SPEAKER: - So here, I want to give you the sound, though.
[33:16] SPEAKER: I want to play the sound that plays
[33:19] SPEAKER: when you load the tape into this thing,
[33:20] SPEAKER: 'cause it's a good sound.
[33:21] SPEAKER: - That's a reasonably svelte piece of electronics
[33:24] SPEAKER: for the era.
[33:25] SPEAKER: Here we go.
[33:28] SPEAKER: - Did it come through or no?
[33:29] SPEAKER: - Yes, that was pretty good.
[33:30] SPEAKER: - I'm gonna put one in.
[33:37] SPEAKER: So that sound is a much simpler tape extraction mechanism.
[33:43] SPEAKER: They had a larger groove in the back of VHS tapes.
[33:47] SPEAKER: Sorry, smaller groove, but with multiple places.
[33:49] SPEAKER: And what happened was these pins went up
[33:51] SPEAKER: and pulled it up and wrapped it around the tape head.
[33:53] SPEAKER: So a lot less tape had to come out,
[33:55] SPEAKER: which meant there had to be a lot less slack
[33:57] SPEAKER: at the beginning and end of the tape.
[33:58] SPEAKER: - Interesting.
[33:59] SPEAKER: - But it also meant that it was more straightforward.
[34:04] SPEAKER: It was just a more straightforward mechanism, frankly.
[34:06] SPEAKER: The cartridges were a little bit bigger
[34:08] SPEAKER: for the VHS than the Betamax, physically.
[34:12] SPEAKER: And yeah, like I said, they did the multiple speeds.
[34:15] SPEAKER: But I would encourage everybody
[34:17] SPEAKER: to load up this YouTube link in the chat.
[34:22] SPEAKER: I'm gonna send it to you right now, Brad.
[34:24] SPEAKER: - In the show notes.
[34:25] SPEAKER: - In the show notes, in the chat.
[34:27] SPEAKER: Jesus, I'm so tired.
[34:29] SPEAKER: - Too much time on Twitch.
[34:30] SPEAKER: - Too many words today.
[34:31] SPEAKER: Let me find the right time code for you here.
[34:34] SPEAKER: - Did you just say too many words?
[34:35] SPEAKER: - Too many words today.
[34:36] SPEAKER: - Can we sidebar here?
[34:38] SPEAKER: This just occurred to me.
[34:39] SPEAKER: Do you think it's possible that you have a,
[34:40] SPEAKER: I want a number of words that you can speak per day
[34:43] SPEAKER: and then they start going in random directions after that?
[34:47] SPEAKER: - That is 100%, not just a theory.
[34:52] SPEAKER: I would say that is fact.
[34:53] SPEAKER: Okay, so I'm gonna send you this link.
[34:55] SPEAKER: What I'm gonna do is I'm gonna do a countdown
[34:58] SPEAKER: and I think we should watch this together
[34:59] SPEAKER: 'cause it's pretty good and it's gonna blow your mind.
[35:02] SPEAKER: Okay, in three, two, one, play.
[35:06] SPEAKER: - Now we're gonna watch what happens
[35:08] SPEAKER: when all these mechanisms fire out.
[35:10] SPEAKER: You'll first see the loading motor start to turn down here.
[35:13] SPEAKER: - That's a lot of parts.
[35:14] SPEAKER: - And then you'll see the tape get extracted
[35:15] SPEAKER: from the cassette and wound around the head drum.
[35:18] SPEAKER: So as I put the cassette in, there goes the cassette
[35:24] SPEAKER: and the tape is pulled around the head drum, 180 degrees.
[35:28] SPEAKER: The head drum spins at 1800 revolutions per minute.
[35:32] SPEAKER: - 1800 RPMs.
[35:35] SPEAKER: That guy talks exactly like someone who makes a habit
[35:39] SPEAKER: of getting inside VCRs.
[35:40] SPEAKER: - We have a picture on the screen.
[35:42] SPEAKER: - Yeah, that's it.
[35:44] SPEAKER: You can stop now, but yeah.
[35:45] SPEAKER: - You're right though.
[35:46] SPEAKER: Like that's very little slack to have to pull.
[35:47] SPEAKER: Like it's only maybe what, a couple inches maybe?
[35:51] SPEAKER: Can't see much scale reference in here
[35:54] SPEAKER: 'cause it's up close,
[35:54] SPEAKER: but it doesn't look like it's very little tape
[35:57] SPEAKER: that has to be pulled out from the tape.
[35:59] SPEAKER: - Okay, so the VHS one, it's really straightforward.
[36:02] SPEAKER: It grabs it, it wraps around the read-write head
[36:05] SPEAKER: and it pulls out like an extra five inches of tape probably.
[36:09] SPEAKER: The beta one has a pin that grabs the tape
[36:14] SPEAKER: and wraps it all the way around.
[36:15] SPEAKER: It needs to have 180 degrees of contact
[36:17] SPEAKER: with the read-write head in order for the machine to work.
[36:19] SPEAKER: And since the technology underlying the VHS is the same,
[36:23] SPEAKER: the VHS uses two pins to pull it around
[36:25] SPEAKER: and pulls it just past the midway point
[36:27] SPEAKER: of the read-write head drum,
[36:29] SPEAKER: which is a cylinder in the middle of the player.
[36:32] SPEAKER: The beta one has one pin on a gear
[36:35] SPEAKER: that goes around the outside edge of the read-write head
[36:39] SPEAKER: and pulls it through like 270 degrees
[36:41] SPEAKER: of that read-write circle
[36:43] SPEAKER: so that a big giant chunk of tape ends up rubbed
[36:47] SPEAKER: against the drum,
[36:47] SPEAKER: which spins again at like 1800 revolutions per minute.
[36:51] SPEAKER: - Yeah, I mean, if you visualize how much tape
[36:53] SPEAKER: you would need to pull out to be able to make
[36:55] SPEAKER: a reasonable looking reek letter beta.
[36:57] SPEAKER: - It's like twice as much as the VHS,
[36:59] SPEAKER: maybe a little bit more.
[37:00] SPEAKER: - Yeah, you can imagine how much more tape
[37:01] SPEAKER: would have to come out just to do that.
[37:03] SPEAKER: - Well, and the knock-on effect of that is that it means
[37:06] SPEAKER: that in a cartridge that starts smaller
[37:08] SPEAKER: than the VHS cartridge, there's extra space that's used
[37:12] SPEAKER: for the extra slack that has to be at the beginning
[37:14] SPEAKER: before the first recording to give enough blank,
[37:19] SPEAKER: not tape, tape at that point.
[37:21] SPEAKER: And then there's a whole bunch of other stuff they do
[37:23] SPEAKER: to make sure that it didn't crash
[37:25] SPEAKER: into the end of the tape and all that stuff.
[37:27] SPEAKER: The Technology Connections video is definitely
[37:28] SPEAKER: worth watching if you're interested in this stuff.
[37:30] SPEAKER: There's a bunch of weird esoterica about how these,
[37:33] SPEAKER: how both of these formats work
[37:35] SPEAKER: that make it a very interesting read.
[37:37] SPEAKER: - Yeah, that channel does good work.
[37:39] SPEAKER: - So, okay, so that's where the tapes are out.
[37:42] SPEAKER: Everything's great.
[37:44] SPEAKER: None of the content creators are upset about the fact
[37:46] SPEAKER: that you can suddenly copy movies and TV shows at home,
[37:49] SPEAKER: right?
[37:50] SPEAKER: - Definitely, they don't want to exercise an iron grip
[37:52] SPEAKER: over how people, how and when and how often people
[37:54] SPEAKER: watch their stuff without paying for it.
[37:56] SPEAKER: - Turns out that's not right.
[37:57] SPEAKER: - Sony was sued by Universal Studios in 1984,
[38:02] SPEAKER: and it went all the way to the Supreme Court.
[38:04] SPEAKER: This is the famous Betamax case is what people call this.
[38:07] SPEAKER: And it resulted in a legal determination
[38:11] SPEAKER: that home taping of TV shows for the purposes
[38:15] SPEAKER: of time shifting them was legal,
[38:17] SPEAKER: was a legal fair use of copyrighted materials
[38:21] SPEAKER: because they were significant that,
[38:23] SPEAKER: and thus that home video cassette recorders
[38:26] SPEAKER: were legal technologies because of significant
[38:29] SPEAKER: non-infringing uses.
[38:30] SPEAKER: - Can you imagine how different the history,
[38:32] SPEAKER: the entire history of home media would be
[38:35] SPEAKER: if this decision had gone the other way?
[38:37] SPEAKER: - I mean, I think that we would have had,
[38:41] SPEAKER: there would have been a quashing effect on a lot of,
[38:44] SPEAKER: on computing.
[38:45] SPEAKER: - Yes.
[38:46] SPEAKER: - Like the internet and computing would have had problems
[38:48] SPEAKER: if it was determined that we could ban entire branches
[38:50] SPEAKER: of technology because of copyright infringement
[38:52] SPEAKER: against movie studios.
[38:53] SPEAKER: - Right, like how many innovations and inventions
[38:55] SPEAKER: just would never have even been pursued
[38:57] SPEAKER: because of this legal sort of Damocles
[38:59] SPEAKER: hanging over everything.
[39:00] SPEAKER: - And just to be clear though,
[39:02] SPEAKER: it wasn't that there was an expectation
[39:04] SPEAKER: there was gonna be a ban.
[39:06] SPEAKER: The idea was that the studios felt that the manufacturers
[39:09] SPEAKER: were liable for any copyright infringement committed
[39:12] SPEAKER: by purchasers of the devices,
[39:14] SPEAKER: which would have not banned them for a legal sense,
[39:18] SPEAKER: but would have prevented them from making them
[39:19] SPEAKER: or let them, required them to do major work
[39:22] SPEAKER: to make sure that you couldn't actually record
[39:24] SPEAKER: anything useful with them.
[39:25] SPEAKER: - Right.
[39:26] SPEAKER: - So, okay, so that, the good news is
[39:29] SPEAKER: the Supreme Court went the right way on that.
[39:31] SPEAKER: It established the fair use doctrine for,
[39:33] SPEAKER: that allowed you to copy media
[39:34] SPEAKER: that you would have had legal access to,
[39:37] SPEAKER: which just to be clear, not a law,
[39:38] SPEAKER: it's just the Supreme Court said,
[39:39] SPEAKER: "Hey, this is cool," 40 years ago.
[39:42] SPEAKER: And like that's never backfired on us in any way, shape,
[39:45] SPEAKER: or form when the Supreme Court says something's okay
[39:46] SPEAKER: and then changes their mind later.
[39:49] SPEAKER: I'm looking at the camera.
[39:50] SPEAKER: But yeah, so that's basically where the tape stuff
[39:54] SPEAKER: ends now.
[39:55] SPEAKER: - But it did not stop them from developing
[39:57] SPEAKER: copy protection for tapes anyway.
[39:58] SPEAKER: - I was gonna say that was the next step
[40:00] SPEAKER: is that they did have to develop copy protection for tapes.
[40:02] SPEAKER: So the Macrovision analog/analog protection system
[40:07] SPEAKER: was a simple, relatively simple copy protection
[40:09] SPEAKER: that rendered copies garbled or unwatchable
[40:12] SPEAKER: by jacking up the automatic gain circuit
[40:14] SPEAKER: on recording devices.
[40:16] SPEAKER: What this means is in the blank space,
[40:18] SPEAKER: on each analog frame, there was some blank space
[40:21] SPEAKER: above and below the picture that was used for things
[40:24] SPEAKER: like v-sync and gain and stuff like that.
[40:28] SPEAKER: What they would do is spike the gain signal
[40:31] SPEAKER: on a purchase tape.
[40:34] SPEAKER: If you bought a copy of Tango and Cash,
[40:37] SPEAKER: they would have the tape that you bought
[40:39] SPEAKER: had these juiced gain pulses on there
[40:44] SPEAKER: that would jack up the tracking on subsequent recordings.
[40:48] SPEAKER: So the first one would look fine
[40:49] SPEAKER: when you played it on most VCRs.
[40:51] SPEAKER: Of course, it didn't work on all VCRs.
[40:52] SPEAKER: This would jack up some VCRs.
[40:54] SPEAKER: But on the second one, it would say,
[40:56] SPEAKER: hey, this is not something we can do.
[40:58] SPEAKER: This signal means it's not legal for us
[41:00] SPEAKER: to make a copy of it.
[41:01] SPEAKER: It just wouldn't work, or it would be badly corrupted.
[41:03] SPEAKER: - I have not heard the word Macrovision in 25 years or more.
[41:09] SPEAKER: - I feel like there was a version of Macrovision
[41:10] SPEAKER: on a lot of DVDs in addition to the DVD CCA stuff.
[41:13] SPEAKER: - That's possible, but from the early to mid '90s,
[41:16] SPEAKER: that really brought back some memories of frustration.
[41:19] SPEAKER: It sounds like a dirty word.
[41:20] SPEAKER: - Yeah, so there were variants of both Betamax and VHS.
[41:24] SPEAKER: Betamax had Super Betamax,
[41:26] SPEAKER: which was mostly a professional format,
[41:28] SPEAKER: so we're not, or sorry, BetaCam rather.
[41:30] SPEAKER: - Yeah, BetaCam, which was higher quality.
[41:34] SPEAKER: - Higher quality, used a single cog wheel
[41:36] SPEAKER: to drive tape through some sort of wizardry.
[41:38] SPEAKER: I don't know how that would have worked.
[41:40] SPEAKER: It was used in pro environments
[41:41] SPEAKER: because they wanted better than NTSC quality
[41:46] SPEAKER: so that they could do edits without any loss
[41:48] SPEAKER: by the time it went, without any noticeable image loss
[41:51] SPEAKER: for the NTSC outputs.
[41:53] SPEAKER: - Yeah, 120 lines of chroma versus the, what is it,
[41:56] SPEAKER: 30 or 40 in the consumer Betamax?
[41:58] SPEAKER: - Yeah, yeah, and it's worth mentioning
[42:01] SPEAKER: all of these analog formats.
[42:03] SPEAKER: When you would do a copy of a copy,
[42:04] SPEAKER: there's degradation each time.
[42:07] SPEAKER: So by the time you got to a second or third generation output
[42:11] SPEAKER: there was a noticeable decrease in the quality,
[42:13] SPEAKER: which is why you use professional quality cameras
[42:17] SPEAKER: even in the pre-HD days that had higher resolutions,
[42:20] SPEAKER: like these Betacam devices.
[42:21] SPEAKER: There was also VHSC for the home market.
[42:24] SPEAKER: There was a Betamax camcorders as well.
[42:28] SPEAKER: There weren't very many of them.
[42:29] SPEAKER: They didn't last for very long.
[42:32] SPEAKER: But VHSC was a electrically compatible, mechanical,
[42:37] SPEAKER: smaller mechanical VHS tape that was basically,
[42:41] SPEAKER: that you could basically put it into a mechanical caddy
[42:44] SPEAKER: that had a little motor in it that would thread,
[42:47] SPEAKER: pull the tape out of the baby cartridge
[42:49] SPEAKER: and put it where the big cartridge was expected
[42:51] SPEAKER: to have tape in the player when you put it in the caddy
[42:54] SPEAKER: and then you could just plug that caddy
[42:55] SPEAKER: into a normal VHS player and it would work right.
[42:59] SPEAKER: - That's cool.
[42:59] SPEAKER: I don't know if I ever saw VHS-C anywhere.
[43:03] SPEAKER: - That was mostly used in post-shoulder mounted camcorders
[43:09] SPEAKER: when you had a handicam-sized camcorder.
[43:12] SPEAKER: Those were all VHS-C.
[43:13] SPEAKER: And then, in 1987, there was also Super VHS,
[43:17] SPEAKER: which was available everywhere.
[43:20] SPEAKER: Didn't really sell a whole lot of them, apparently.
[43:23] SPEAKER: It upped the resolution on VHS to 400 lines effective,
[43:28] SPEAKER: which was 420 minus the V-Sync area.
[43:33] SPEAKER: And like Betacam, it was higher than NTSC resolution,
[43:36] SPEAKER: which made it look good and it was viable
[43:39] SPEAKER: for professional newsroom edits and stuff like that.
[43:43] SPEAKER: It got used in learning environments a lot
[43:46] SPEAKER: 'cause it was cheaper than Betacam,
[43:48] SPEAKER: but it provided similar results.
[43:51] SPEAKER: And it worked the same way as VHS.
[43:53] SPEAKER: In fact, you could play VHS tapes in a Super VHS player.
[44:00] SPEAKER: You generally couldn't play Super VHS tapes in a VHS player
[44:04] SPEAKER: unless you had a special kind of VHS player
[44:06] SPEAKER: that also understood how the Super VHS tapes worked,
[44:11] SPEAKER: which would make them backwards compatible in some odd way.
[44:17] SPEAKER: There was also Super VHS-ET,
[44:19] SPEAKER: which lets you record on traditional VHS tapes,
[44:21] SPEAKER: which were much cheaper, but at a higher quality
[44:24] SPEAKER: than you could on a normal VHS tape, usually.
[44:27] SPEAKER: - Yeah, this says Super VHS required S-video
[44:30] SPEAKER: for best results, which who had S-video access in 1987?
[44:36] SPEAKER: - Hardly anyone, but SCART was taking off
[44:38] SPEAKER: in Europe by then. - In Europe, yes.
[44:40] SPEAKER: So America got completely screwed on the SCART front
[44:43] SPEAKER: for whatever reason, but.
[44:45] SPEAKER: - Well, but so we had, I had S-video
[44:48] SPEAKER: by the time I bought my TV in 1993,
[44:50] SPEAKER: probably when I went to college, my first TV.
[44:53] SPEAKER: So it wasn't too far off.
[44:55] SPEAKER: - I was just going through old CRTs
[44:57] SPEAKER: when I was at home last month,
[44:59] SPEAKER: and I didn't, I didn't, 'cause I still have,
[45:01] SPEAKER: we still have all these TVs,
[45:02] SPEAKER: 'cause I begged my parents not to throw them out.
[45:05] SPEAKER: I did not get a TV with S-video on it until 2001,
[45:10] SPEAKER: I believe. - Wow.
[45:11] SPEAKER: - Yeah.
[45:11] SPEAKER: - So Xbox GameCube era, huh?
[45:13] SPEAKER: - Yes, PS2, I distinctly remember getting that TV
[45:16] SPEAKER: and playing Final Fantasy X on it,
[45:17] SPEAKER: if that tells you anything.
[45:19] SPEAKER: - Well, so the interesting thing about the video formats
[45:23] SPEAKER: is in the beginning of this time period,
[45:25] SPEAKER: in the early '80s, you were probably using
[45:27] SPEAKER: an FM modulator plugged into the antenna
[45:29] SPEAKER: and turning your TV to channel three or four.
[45:31] SPEAKER: - Yes. - Or two, I guess.
[45:33] SPEAKER: - By the end of this, RCA inputs were pretty common
[45:36] SPEAKER: on TVs by the late '80s.
[45:38] SPEAKER: So you could get a signal that put the luminance and chroma
[45:42] SPEAKER: on two wires and blasted them from your VHS player
[45:47] SPEAKER: to your TV and let you record inputs as well, same way.
[45:51] SPEAKER: - Yeah, and then what is S-video's, like six pins?
[45:53] SPEAKER: Is that right?
[45:54] SPEAKER: - S-video's five or six, yeah,
[45:56] SPEAKER: and it separates out the luminance and chroma, I believe,
[45:59] SPEAKER: but not onto separate signals with a ground,
[46:02] SPEAKER: I think is what it is.
[46:03] SPEAKER: But then you need component or RGB or SCART
[46:06] SPEAKER: to split the colors out individually.
[46:08] SPEAKER: - Yeah, to split the individual colors out.
[46:10] SPEAKER: - This is for later.
[46:12] SPEAKER: I talked about this on the "Nextlander" Ramblecast recently.
[46:14] SPEAKER: I don't think I told you one of the old trinitrons
[46:16] SPEAKER: in the basement of my parents is one of the ones
[46:19] SPEAKER: that's easy to mod for SCART.
[46:20] SPEAKER: - Wow, really? - Yeah.
[46:21] SPEAKER: - Oh, that's amazing. - It's quite easy.
[46:23] SPEAKER: I mean, I'm still afraid to open up a CRT,
[46:25] SPEAKER: even though the thing hasn't been turned on in years,
[46:27] SPEAKER: to be fair.
[46:28] SPEAKER: - Well, if you have a screwdriver
[46:30] SPEAKER: and are okay discarding capacitors, not bad.
[46:32] SPEAKER: - Yes, I'm gonna have to learn a lot of
[46:35] SPEAKER: fundamental electrical concepts
[46:36] SPEAKER: before I open up that TV someday
[46:38] SPEAKER: and try to mod SCART into it.
[46:40] SPEAKER: - You're probably, I mean,
[46:43] SPEAKER: when was the last time it was plugged in, like 30 years ago?
[46:45] SPEAKER: - No, it was in use probably in the last decade
[46:47] SPEAKER: at some point. - Oh, okay.
[46:48] SPEAKER: Yeah, you're in the danger zone then still.
[46:51] SPEAKER: - The actual mod looks pretty easy
[46:52] SPEAKER: in terms of soldering and stuff.
[46:54] SPEAKER: - Brad, we have one simple rule here,
[46:56] SPEAKER: which is don't electrocute yourself.
[46:57] SPEAKER: - Okay, fine, if you insist.
[47:00] SPEAKER: - So just to put a bow
[47:03] SPEAKER: on the VHS beta conversation,
[47:07] SPEAKER: who won?
[47:09] SPEAKER: They sold a buttload of VHS players
[47:11] SPEAKER: and they sold some Betamax players.
[47:13] SPEAKER: - I don't think I've ever seen a beta deck.
[47:15] SPEAKER: That's not, I take it back, I worked at GameSpot,
[47:17] SPEAKER: so there were Betacam tapes everywhere for broadcast stuff,
[47:20] SPEAKER: but I've never seen like a beta player
[47:21] SPEAKER: in somebody's house ever.
[47:23] SPEAKER: - I remember seeing them when I was a really little kid,
[47:25] SPEAKER: then they all went away.
[47:26] SPEAKER: Yeah, and I never ever went to a video store
[47:28] SPEAKER: where you could rent beta tapes.
[47:29] SPEAKER: Like by the time I was going to video stores,
[47:31] SPEAKER: that was all, they were all gone.
[47:33] SPEAKER: - Yes.
[47:34] SPEAKER: - To give you an idea of what was going on,
[47:35] SPEAKER: in 1980, VHS had a 60% market share,
[47:38] SPEAKER: which was the, I think the 40% mark for beta
[47:41] SPEAKER: was the peak for them.
[47:45] SPEAKER: And that was before the real explosion in sales
[47:47] SPEAKER: happened in the mid-80s.
[47:49] SPEAKER: - You know, the expectation of acquiring licensing fees
[47:52] SPEAKER: for this whole thing seems maybe a little foolhardy
[47:55] SPEAKER: in retrospect on Sony's part.
[47:56] SPEAKER: - Well, when we talk about digital formats,
[47:59] SPEAKER: we'll get to the time that it worked out for them.
[48:02] SPEAKER: - Sure.
[48:02] SPEAKER: - But I think you're probably right.
[48:06] SPEAKER: It definitely didn't work out in this case.
[48:07] SPEAKER: They won the quality battle kind of and lost the war.
[48:12] SPEAKER: - But just barely, right?
[48:13] SPEAKER: So like the thing, that's the thing I've been waiting
[48:16] SPEAKER: to say at the end of this conversation is,
[48:18] SPEAKER: I mean, this podcast is good at making me check
[48:21] SPEAKER: like sort of, not urban legend,
[48:23] SPEAKER: but like apocryphal stories about technology and stuff
[48:26] SPEAKER: on a regular basis, but this is a big one
[48:29] SPEAKER: where I've always assumed that that story was correct
[48:32] SPEAKER: about beta being like profoundly superior to VHS
[48:37] SPEAKER: or at least like appreciably so.
[48:39] SPEAKER: You know, like the story was always like,
[48:40] SPEAKER: oh, beta was better, VHS won out by being cheaper.
[48:43] SPEAKER: You know, like the good enough thing always wins
[48:45] SPEAKER: over the best thing, but this comparison makes them sound
[48:49] SPEAKER: like they were on basically footing.
[48:51] SPEAKER: - Yeah, I think, so Technology Connections talks about this
[48:53] SPEAKER: quite a bit in their VHS and beta combos.
[48:57] SPEAKER: I unfortunately don't have a beta player here
[49:00] SPEAKER: to do side-by-sides on.
[49:02] SPEAKER: I think in the modern context
[49:03] SPEAKER: where we're used to looking at 4K plus video,
[49:06] SPEAKER: I think both of them are going to look terrible
[49:08] SPEAKER: in a way that is difficult to describe
[49:10] SPEAKER: when you haven't looked at VHS video in a long time.
[49:12] SPEAKER: - Yeah.
[49:14] SPEAKER: - But I do, I think that,
[49:16] SPEAKER: so I did some more research on this
[49:18] SPEAKER: 'cause speaking of urban legends,
[49:19] SPEAKER: the thing I had always heard was that beta lost
[49:22] SPEAKER: because Sony wouldn't allow pornography on the platform.
[49:25] SPEAKER: - That's the other one that, yes,
[49:26] SPEAKER: I've heard that one for years too.
[49:29] SPEAKER: - Technology Connections said that was bunk
[49:30] SPEAKER: and I did some further digging and after reading more,
[49:34] SPEAKER: I think they're probably right.
[49:37] SPEAKER: Mainly because Sony didn't, Sony sold tapes, right?
[49:40] SPEAKER: They didn't license the tapes
[49:42] SPEAKER: to the people who made the content.
[49:45] SPEAKER: There was nothing stopping people
[49:46] SPEAKER: from putting pornography on Betamax
[49:48] SPEAKER: other than nobody had Betamax players
[49:49] SPEAKER: that they could sell pornography to.
[49:51] SPEAKER: - Sure.
[49:52] SPEAKER: I think that the fact that the tapes
[49:57] SPEAKER: couldn't hold a feature film for the most part
[49:59] SPEAKER: was probably the deal breaker for Betamax
[50:02] SPEAKER: as a going concern.
[50:04] SPEAKER: - Yeah, like I said, being able to fit six hours on a tape
[50:07] SPEAKER: was everything at that time.
[50:09] SPEAKER: - But also being able to fit Star Wars on a tape
[50:13] SPEAKER: or Jaws on a tape was important, right?
[50:16] SPEAKER: You couldn't get a copy of Batman
[50:17] SPEAKER: because Batman wouldn't fit on one Betamax tape.
[50:20] SPEAKER: You needed two.
[50:21] SPEAKER: - It wasn't until much later on when Heat came out
[50:23] SPEAKER: and Michael Mann was like,
[50:26] SPEAKER: "Yo, we gotta get this thing out,
[50:28] SPEAKER: "but I'm not letting you EP this.
[50:30] SPEAKER: "This has gotta be SP all the way through."
[50:32] SPEAKER: So we had two tape sets of,
[50:34] SPEAKER: I think Heat and The Godfather
[50:35] SPEAKER: were the two VHS movies I bought
[50:37] SPEAKER: that had two tape versions, yeah.
[50:41] SPEAKER: - First thing, right?
[50:42] SPEAKER: - It was maybe Lawrence of Arabia.
[50:44] SPEAKER: I can't remember.
[50:45] SPEAKER: Anyway. - Yeah, yes.
[50:46] SPEAKER: - The upshot was the VHS one
[50:49] SPEAKER: because you could buy a six hour tape.
[50:51] SPEAKER: I think that's probably fair.
[50:52] SPEAKER: - Yes, VHS one and then enjoyed,
[50:54] SPEAKER: at least in the United States,
[50:55] SPEAKER: enjoyed pretty much unchallenged market dominance
[50:57] SPEAKER: until the late '90s.
[50:59] SPEAKER: DVD came out in '97, but it was still a year or two
[51:02] SPEAKER: before that really started penetrating.
[51:03] SPEAKER: So VHS was big for a long time.
[51:06] SPEAKER: - It took a while before DVD players were cheap enough
[51:08] SPEAKER: that a lot of people had them.
[51:09] SPEAKER: But in the meantime, before DVD,
[51:12] SPEAKER: the people who cared about quality had another alternative,
[51:15] SPEAKER: maybe two. - Way before DVD, actually.
[51:17] SPEAKER: That was another thing that blew me away
[51:19] SPEAKER: in researching this episode was how early laser disc
[51:21] SPEAKER: was a thing.
[51:23] SPEAKER: - So laser disc is, like, the interesting thing about this
[51:25] SPEAKER: is that the time from launch to mass,
[51:28] SPEAKER: to any kind of mass acceptance on all of this stuff
[51:30] SPEAKER: was really slow by modern standards.
[51:33] SPEAKER: Like it took a long time before VHS,
[51:37] SPEAKER: between when VHS launched in 1976 to 1983 and 1984,
[51:41] SPEAKER: when there were VHS players in a majority of US households.
[51:45] SPEAKER: Laser disc, likewise, launched in 1978.
[51:48] SPEAKER: - It was originally under the name Discovision?
[51:50] SPEAKER: - Yes, yes, that was- - I did not know that.
[51:52] SPEAKER: - Uh-huh, yes, MCA, also remember MCA?
[51:56] SPEAKER: - Yeah, Rip MCA.
[51:57] SPEAKER: - Speaking of old media companies
[51:59] SPEAKER: that don't seem to be around anymore.
[52:00] SPEAKER: - Oh, I thought you were talking about the Beastie Boy.
[52:02] SPEAKER: - Oh, no, but yes, yes, laser disc originally was marketed,
[52:05] SPEAKER: brought to market and marketed by MCA
[52:07] SPEAKER: under the name of Discovision. (laughs)
[52:10] SPEAKER: - That's amazing.
[52:11] SPEAKER: - Before Pioneer later came along
[52:13] SPEAKER: and I believe bought all the rights to the format.
[52:15] SPEAKER: And then that's when they renamed it to laser disc
[52:17] SPEAKER: and also used, I believe,
[52:18] SPEAKER: the term laser vision here and there.
[52:20] SPEAKER: - I wanna know if they had like a thing
[52:21] SPEAKER: that played at the beginning of every movie
[52:23] SPEAKER: that was like a da, da, da, da, da, da, da, da, da, da, da,
[52:27] SPEAKER: with like Discovision swooping in
[52:28] SPEAKER: in like '70s psychedelic text treatment.
[52:31] SPEAKER: - Big mirror ball descending from the ceiling.
[52:34] SPEAKER: - Yeah, crazy motion graphics.
[52:35] SPEAKER: - As part of the, yes, we should do some research on that.
[52:39] SPEAKER: I have no idea of the original, like the R&D,
[52:41] SPEAKER: the technological development on optical storage technology,
[52:45] SPEAKER: meaning, you know, like same way CDs work.
[52:47] SPEAKER: We're talking about a disc with pits and lands, you know,
[52:50] SPEAKER: a little kind of kind of trying to think, not grooves,
[52:52] SPEAKER: but you know, those are basically like gaps
[52:53] SPEAKER: and high and low elevation basically
[52:56] SPEAKER: on a kind of microscopic scale on the disc,
[52:58] SPEAKER: which are read by a laser.
[52:59] SPEAKER: Like that technology goes back to the early '60s
[53:02] SPEAKER: from what I saw, like the first work
[53:04] SPEAKER: on the optical and laser storage technology
[53:07] SPEAKER: that went into laser disc started in like 1963
[53:11] SPEAKER: and then came to market by 1978.
[53:13] SPEAKER: So like two years after VHS,
[53:15] SPEAKER: laser disc was on the market, which is crazy to me.
[53:18] SPEAKER: - So is it still doing pits and lands though,
[53:20] SPEAKER: or is it doing an actual analog wave on the disc?
[53:23] SPEAKER: - So that was probably the biggest thing about laser disc
[53:26] SPEAKER: that I discovered in looking into this,
[53:27] SPEAKER: 'cause I've always wondered about that.
[53:29] SPEAKER: So laser disc used analog audio and video primarily.
[53:32] SPEAKER: As far as I can tell, it only ever used analog video
[53:35] SPEAKER: and it primarily used analog audio,
[53:37] SPEAKER: but there were some limited uses of digital audio
[53:40] SPEAKER: on laser disc.
[53:41] SPEAKER: - Did you get Dolby digital, I think on some later,
[53:44] SPEAKER: what are the digital Dolby formats?
[53:45] SPEAKER: I don't know that it was actually Dolby digital,
[53:47] SPEAKER: but you could get one of the digital Dolby audio formats
[53:49] SPEAKER: on some of the later laser discs.
[53:51] SPEAKER: - Might've been like AC3 or something like that.
[53:53] SPEAKER: - That seems right.
[53:54] SPEAKER: - That was a mid eighties digital audio format.
[53:57] SPEAKER: So the way it works is you're still using pits and lands,
[54:00] SPEAKER: but it's the spacing between the,
[54:03] SPEAKER: I guess the lands are the raised parts, right?
[54:05] SPEAKER: And the pits are the lower parts.
[54:07] SPEAKER: It's the spacing that describes the kind of,
[54:09] SPEAKER: the frequency modulation of the analog signal.
[54:12] SPEAKER: So if you go on Wikipedia,
[54:14] SPEAKER: there's a nice little overlay that shows the,
[54:16] SPEAKER: what are effectively digital pits and lands, right?
[54:18] SPEAKER: They're just like cliffs, you know,
[54:19] SPEAKER: that's just like a square wave looking thing,
[54:21] SPEAKER: but they overlay that with the analog signal.
[54:23] SPEAKER: So you can see how the signal is transformed or how it,
[54:26] SPEAKER: how it interprets the spacing,
[54:28] SPEAKER: the size of the gaps between the raised areas as.
[54:31] SPEAKER: - As like the steepness of the curve or something?
[54:34] SPEAKER: - Yes, basically.
[54:35] SPEAKER: I'm sure there's math going on there that I don't understand,
[54:38] SPEAKER: but when you look at it visually,
[54:40] SPEAKER: it's actually like pretty, pretty easy to understand.
[54:42] SPEAKER: - Oh, it's like the midpoint of the curve is at the end
[54:44] SPEAKER: of the square waves.
[54:46] SPEAKER: - Yes.
[54:47] SPEAKER: - Wow, that is a trip.
[54:48] SPEAKER: - Right, it's, it's like, and again,
[54:49] SPEAKER: it's something I've always wondered about because to me,
[54:51] SPEAKER: it was like, how could something be like CDs are digital,
[54:53] SPEAKER: DVDs are digital.
[54:54] SPEAKER: How could you be reading this with a laser in the format
[54:56] SPEAKER: that optical discs are made in and get analogs information
[55:00] SPEAKER: off of it and it turns out you're kind of transforming
[55:03] SPEAKER: digital information into analog frequency modulation.
[55:06] SPEAKER: - Wow, that is crazy.
[55:08] SPEAKER: - Okay.
[55:09] SPEAKER: - It's cool.
[55:10] SPEAKER: - It's like FM radio almost.
[55:11] SPEAKER: - Sure.
[55:12] SPEAKER: - It's frequency modulated.
[55:13] SPEAKER: Okay.
[55:14] SPEAKER: - Yes, yes.
[55:15] SPEAKER: - Weird.
[55:16] SPEAKER: - Yeah, so laser discs, you know, they're giant CDs.
[55:19] SPEAKER: So everybody knows what a CD is like,
[55:21] SPEAKER: but laser discs predate CDs by, I don't know how many years,
[55:23] SPEAKER: CDs, I think we're mid eighties, right?
[55:26] SPEAKER: - I think 84, 82, I can't remember.
[55:29] SPEAKER: - But the technology that went into laser discs is what
[55:31] SPEAKER: informed the creation of the CDD, sorry, the CD, the DVD,
[55:35] SPEAKER: like all the subsequent optical disc formats kind of
[55:38] SPEAKER: descended from the tech that was developed for laser discs.
[55:40] SPEAKER: So those basically were first in the optical storage realm.
[55:45] SPEAKER: They were 12 inch discs.
[55:48] SPEAKER: For our purposes, it's easiest to just say that each disc
[55:51] SPEAKER: held 60 minutes per side in TSC or 64 minutes for PAL.
[55:55] SPEAKER: There were discs that kind of spun at different speeds
[55:57] SPEAKER: that held half that much.
[55:59] SPEAKER: - Yeah, so it's about angular velocity versus linear
[56:02] SPEAKER: velocity of the track and whether it spun faster
[56:05] SPEAKER: when you got closer to the center of the spindle or not.
[56:08] SPEAKER: - Right, but for our purposes, in terms of like buying
[56:10] SPEAKER: movies at retail on laser discs, it was 60 per side,
[56:13] SPEAKER: not 30 in the US.
[56:15] SPEAKER: - And just for the vast majority of users,
[56:18] SPEAKER: the thing you used a laser disc for was buying movies
[56:21] SPEAKER: at retail or, yeah.
[56:24] SPEAKER: - So I don't have the chroma and luma information in front
[56:26] SPEAKER: of me, but it was 425 lines for NTSC resolution.
[56:30] SPEAKER: So substantially better than what you were getting on the
[56:33] SPEAKER: analog tapes of the time.
[56:36] SPEAKER: Had chapter markers, chapter skipping like DVD would later,
[56:40] SPEAKER: which in the eighties was like completely unthinkable
[56:43] SPEAKER: for anybody who'd ever seen a laser disc.
[56:45] SPEAKER: - It was magic.
[56:46] SPEAKER: The first time I saw somebody with a laser disc,
[56:48] SPEAKER: I was like, oh wow, this is incredibly cool.
[56:50] SPEAKER: - Yes, originally I would not have expected this.
[56:53] SPEAKER: Apparently originally laser discs were cheaper to make
[56:55] SPEAKER: than tapes.
[56:57] SPEAKER: - That makes sense, right?
[56:58] SPEAKER: - Yeah, when you think about it, you're just stamping
[57:00] SPEAKER: like a big piece of plastic.
[57:01] SPEAKER: I mean, obviously there are layers there, you know,
[57:03] SPEAKER: there's a substrate and stuff, but, and you know,
[57:05] SPEAKER: you talked about how many moving parts are in a tape
[57:07] SPEAKER: and how fragile they are, but that did invert over time.
[57:11] SPEAKER: From what I gathered, it seemed like maybe the cost
[57:13] SPEAKER: of materials, like the plastic did not come down
[57:15] SPEAKER: that rapidly while of course, economies of scale set in
[57:18] SPEAKER: for VHS tapes that ultimately made them way cheaper to make.
[57:23] SPEAKER: - And also replication, like replication facilities.
[57:27] SPEAKER: Cause like to mass produce a tape,
[57:29] SPEAKER: you had to put a master tape in and then copy a bazillion
[57:32] SPEAKER: copies off of that at the second.
[57:34] SPEAKER: So you didn't have a lot of generational loss, right?
[57:37] SPEAKER: - Yeah.
[57:38] SPEAKER: - So, presumably there were facilities where they would load
[57:42] SPEAKER: up a thousand tapes and copy them all at once,
[57:45] SPEAKER: but I'm sure we didn't have that in the early days.
[57:47] SPEAKER: - Yes, another advantage of laser discs,
[57:49] SPEAKER: we didn't really talk about this with tapes and this also
[57:51] SPEAKER: is relevant to the next bizarre format we're going to talk
[57:54] SPEAKER: about is durability because tapes wear out over time.
[57:58] SPEAKER: Although I don't think I ever had a retail tape die,
[58:01] SPEAKER: like break or get truly unwatchable.
[58:03] SPEAKER: - Yeah, you could do it.
[58:05] SPEAKER: It was hard.
[58:06] SPEAKER: It usually was a fault of the player.
[58:07] SPEAKER: It seemed like, or something got jammed in the,
[58:09] SPEAKER: in the cartridge, which would then jam up the works.
[58:11] SPEAKER: - Definitely a tape deck could eat a tape if mechanically
[58:14] SPEAKER: like the tape could just get pulled out wrong
[58:16] SPEAKER: and ruined that way.
[58:17] SPEAKER: But I mean, also, I mean just like basic wear and tear
[58:19] SPEAKER: from watching too much, like it, I guess it is possible
[58:21] SPEAKER: to wear a tape out eventually.
[58:24] SPEAKER: Laser discs theoretically, like CDs,
[58:25] SPEAKER: if you handle them perfectly in pristine conditions,
[58:28] SPEAKER: they theoretically will last forever.
[58:30] SPEAKER: - Store vertically in a cool dry place.
[58:33] SPEAKER: - Wait, was that actually a thing, vertical?
[58:35] SPEAKER: - Uh-huh, you gotta keep them vertical 'cause they warp.
[58:37] SPEAKER: - Oh, interesting. - And if they warp,
[58:38] SPEAKER: they delaminate and if they, and ask me why,
[58:40] SPEAKER: it's 'cause I have a whole big box of them
[58:41] SPEAKER: sitting in my office here.
[58:43] SPEAKER: - Wait, hang on, were you a laser disc guy?
[58:45] SPEAKER: - No, my wife was a laser disc guy.
[58:47] SPEAKER: - Wait, what?
[58:48] SPEAKER: - Yeah. - Wow.
[58:49] SPEAKER: Gonna talk to her about that sometime.
[58:50] SPEAKER: - When she was in, when we first started dating,
[58:54] SPEAKER: a friend of hers was like, I'm getting rid of all
[58:55] SPEAKER: my laser, one of her old roommates was like,
[58:57] SPEAKER: I'm getting rid of my laser discs, does anybody want them?
[58:59] SPEAKER: - Oh, that's even better.
[59:00] SPEAKER: - Fuck yes, I will take them.
[59:01] SPEAKER: - Oh, that's even better than having to buy
[59:03] SPEAKER: all your laser discs yourself is to just be bequeath them.
[59:06] SPEAKER: - Well, she did have to buy them,
[59:07] SPEAKER: but it was at a fraction of the price.
[59:09] SPEAKER: - Fire sale. - Yeah.
[59:10] SPEAKER: We have, I think, the Godfather and Jurassic Park,
[59:13] SPEAKER: not the Japanese Star Warses, but the pre-ruining
[59:18] SPEAKER: Star Warses. - The pre-special edition,
[59:20] SPEAKER: like the mid-90s. - The mid-90s, normal release,
[59:23] SPEAKER: yeah. - The covers that are like
[59:25] SPEAKER: the half face of the Stormtrooper, Invader, and Yoda.
[59:27] SPEAKER: - No, these are before that, these are the ones
[59:30] SPEAKER: that are still the watercolor paintings.
[59:32] SPEAKER: - Oh, like the poster art?
[59:33] SPEAKER: - The poster art, yeah.
[59:34] SPEAKER: - I bought, well, I never owned a laser disc player,
[59:37] SPEAKER: but actually, I take that back, we have one that we got
[59:39] SPEAKER: for free that was a hand-me-down from a school now.
[59:42] SPEAKER: My parents might've gotten rid of it by now,
[59:44] SPEAKER: but we had at some point a free laser disc player,
[59:46] SPEAKER: but I did buy those THX Star Wars laser discs
[59:49] SPEAKER: the very last release before the special editions came out.
[59:53] SPEAKER: They're still factory sealed, but I think they've been
[59:55] SPEAKER: stored horizontally for 25 years.
[59:58] SPEAKER: - We'll just put 'em on eBay,
[59:59] SPEAKER: you don't have to tell anybody that, it's fine.
[1:00:01] SPEAKER: - That might be the thing to do.
[1:00:03] SPEAKER: - Like, I think, as with many things around this era,
[1:00:07] SPEAKER: there are a lot of things that you're told to do
[1:00:09] SPEAKER: that are unclear what the provenance of that information is.
[1:00:12] SPEAKER: I have no idea if that's how you're actually supposed
[1:00:13] SPEAKER: to handle laser discs.
[1:00:15] SPEAKER: That's how I was told by my wife,
[1:00:17] SPEAKER: who is our house's laser disc expert, it turns out.
[1:00:20] SPEAKER: - Yes.
[1:00:22] SPEAKER: - So, the interesting thing about laser discs
[1:00:25] SPEAKER: is they were usually double-sided, right?
[1:00:27] SPEAKER: So, in order to get two hours of movie on a laser disc,
[1:00:31] SPEAKER: you had to flip, get out and flip them over,
[1:00:34] SPEAKER: or if you were rich, you had a flipping laser disc player,
[1:00:37] SPEAKER: which I assume had mirrors and two read heads, maybe,
[1:00:41] SPEAKER: so the laser would bounce up to the top.
[1:00:43] SPEAKER: I don't know how that would've worked, but.
[1:00:45] SPEAKER: - What precision of mirror do you need?
[1:00:47] SPEAKER: Well, maybe the tolerance was higher,
[1:00:49] SPEAKER: or it was better than I would think.
[1:00:50] SPEAKER: Like, I would think that you would need
[1:00:51] SPEAKER: some extremely precise mirror to make the laser.
[1:00:55] SPEAKER: - So, I don't know how it worked in laser discs,
[1:00:57] SPEAKER: but often in analog stuff,
[1:00:59] SPEAKER: the way the aiming circuit would work
[1:01:01] SPEAKER: is it would be self-correcting based on signal strength.
[1:01:05] SPEAKER: So, when the signal strength got low, it would move,
[1:01:08] SPEAKER: it would reorient until it was in the right,
[1:01:11] SPEAKER: until it was getting stronger signal again,
[1:01:13] SPEAKER: just as a factor of the circuit design.
[1:01:15] SPEAKER: - That's cool.
[1:01:18] SPEAKER: - So, yeah, laser disc was for a format
[1:01:23] SPEAKER: that I think it's safe to say probably
[1:01:25] SPEAKER: was a failure in the long run.
[1:01:27] SPEAKER: It ran for a long time.
[1:01:28] SPEAKER: People were buying laser discs a while into the '90s.
[1:01:30] SPEAKER: - Yeah, Pioneer, actually, I believe I read
[1:01:31] SPEAKER: Pioneer stopped making laser disc players only in 2009.
[1:01:35] SPEAKER: - Yeah, the image quality was quite good,
[1:01:38] SPEAKER: especially compared to VHS and Betacam, or Betamax,
[1:01:41] SPEAKER: but even compared to early DVD stuff.
[1:01:44] SPEAKER: Like, the difference between the analog video
[1:01:47] SPEAKER: and the MPEG-2 compression,
[1:01:50] SPEAKER: we would often watch the analog,
[1:01:53] SPEAKER: the laser disc versions of movies
[1:01:55] SPEAKER: that we would have in multiple places.
[1:01:57] SPEAKER: - Really?
[1:01:57] SPEAKER: - Because the analog, like, Jurassic Park was much,
[1:02:01] SPEAKER: like, MPEG-2 was unkind to the dark scenes
[1:02:04] SPEAKER: in Jurassic Park.
[1:02:04] SPEAKER: - Sure.
[1:02:05] SPEAKER: - And it worked pretty well on the laser disc.
[1:02:07] SPEAKER: - Yeah, makes sense.
[1:02:09] SPEAKER: Couple other, like, factoids about laser disc.
[1:02:11] SPEAKER: Like you said, it did not catch on much in North America
[1:02:14] SPEAKER: beyond kind of like a format for video files.
[1:02:16] SPEAKER: Apparently, it was quite big in Asia.
[1:02:18] SPEAKER: Like, it was very, very big in Japan.
[1:02:20] SPEAKER: - Makes sense.
[1:02:20] SPEAKER: - It was cheaper in Japan for whatever reason.
[1:02:22] SPEAKER: Hong Kong is another market where it caught on.
[1:02:25] SPEAKER: There's a lot of anime out there on laser disc.
[1:02:27] SPEAKER: Common conception or misconception, rather,
[1:02:30] SPEAKER: about laser discs that I held until I read about this stuff
[1:02:33] SPEAKER: was that it was read-only.
[1:02:34] SPEAKER: - Oh, no, they were writable ones,
[1:02:36] SPEAKER: but not many people had them.
[1:02:37] SPEAKER: - Yes, in fact, there were two different
[1:02:39] SPEAKER: recordable laser disc formats.
[1:02:41] SPEAKER: They were write-once, read-many formats,
[1:02:43] SPEAKER: so you could only kind of like a CDR.
[1:02:46] SPEAKER: Well, there are rewritable CDRs, but you know what I mean.
[1:02:49] SPEAKER: Like, there were formats where you would buy
[1:02:50] SPEAKER: a blank laser disc and could write to them once
[1:02:52] SPEAKER: and that was it, but from what I read,
[1:02:54] SPEAKER: those were only ever marketed for professional uses.
[1:02:56] SPEAKER: Basically, they were used for data storage in some cases,
[1:02:59] SPEAKER: but they never really came to market
[1:03:01] SPEAKER: in any kind of like consumer format.
[1:03:02] SPEAKER: - Yeah, you could do back,
[1:03:03] SPEAKER: like there were computer backup solutions that used those,
[1:03:05] SPEAKER: as I recall, for like archival data.
[1:03:08] SPEAKER: I think they overestimated, as with CD,
[1:03:10] SPEAKER: they overestimated the long-term viability of the laser disc
[1:03:14] SPEAKER: as a backup media, an archival media.
[1:03:17] SPEAKER: - Yes.
[1:03:18] SPEAKER: - What was the other one?
[1:03:18] SPEAKER: What was the other record, there was just a rewritable one?
[1:03:22] SPEAKER: - I don't believe there were any rewritable ones.
[1:03:23] SPEAKER: I believe there were both.
[1:03:25] SPEAKER: - So they weren't, like the CD-RWs and DVD-RWs use dye
[1:03:28] SPEAKER: that can be basically reset if you hit it
[1:03:30] SPEAKER: with a certain frequency or power of laser.
[1:03:33] SPEAKER: And I assume we hadn't gotten to that technology yet.
[1:03:36] SPEAKER: - CRV discs, CRV component recordable video disc
[1:03:40] SPEAKER: is the name of one of them.
[1:03:42] SPEAKER: Those had to be stored in disc caddies.
[1:03:45] SPEAKER: - Oh, 'cause they were so fragile?
[1:03:46] SPEAKER: - Yes.
[1:03:47] SPEAKER: - Boy.
[1:03:48] SPEAKER: - Recorded once per side.
[1:03:50] SPEAKER: The recordable laser video disc was the other.
[1:03:54] SPEAKER: - Ah, yes, the RLV.
[1:03:57] SPEAKER: - Function exactly like a CD-R disc.
[1:03:59] SPEAKER: - Okay.
[1:04:00] SPEAKER: - Have to give a shout out to Dragon's Lair
[1:04:03] SPEAKER: and what laser disc did for early FMV video games.
[1:04:06] SPEAKER: - I didn't, I don't think as a kid,
[1:04:08] SPEAKER: I realized that Dragon's Lair was like hand animated
[1:04:10] SPEAKER: that was just giving chapters on a laser disc.
[1:04:12] SPEAKER: - Oh yeah, oh yeah.
[1:04:13] SPEAKER: - I just thought that was what video games
[1:04:15] SPEAKER: were supposed to look like.
[1:04:16] SPEAKER: I was like, that's a good video game
[1:04:17] SPEAKER: and all these others are crap.
[1:04:18] SPEAKER: - Yes, there was a full on laser disc player
[1:04:20] SPEAKER: in every Dragon's Lair machine.
[1:04:22] SPEAKER: American laser games, anybody makers of Mad Dog McCree?
[1:04:26] SPEAKER: Among others.
[1:04:27] SPEAKER: - Okay, without the Mad Dog McCree, it turns out.
[1:04:28] SPEAKER: - Who shot Johnny Rock.
[1:04:31] SPEAKER: - I never saw, the only one of those I'm familiar with
[1:04:33] SPEAKER: I think is Mad Dog.
[1:04:34] SPEAKER: And that's only because of giant bomb stuff
[1:04:35] SPEAKER: 'cause we did, we had people who were big fans.
[1:04:38] SPEAKER: - Yeah, I don't think I really saw those
[1:04:39] SPEAKER: in arcades much at all back in the day,
[1:04:41] SPEAKER: but I was familiar with them from magazines
[1:04:43] SPEAKER: and then they started coming out on things like 3DO
[1:04:44] SPEAKER: after a while, once CD systems started getting big.
[1:04:48] SPEAKER: - You could get Dragon's Lair for your NPC one computer.
[1:04:51] SPEAKER: - Yes.
[1:04:52] SPEAKER: - I never was, I don't know if anybody,
[1:04:55] SPEAKER: was it possible to get good at Dragon's Lair?
[1:04:57] SPEAKER: - Well, you could like memorize it, sure.
[1:04:59] SPEAKER: - You could just have to spend a lot of money.
[1:05:01] SPEAKER: - Memorize the inputs and timing against each scene
[1:05:03] SPEAKER: and beat it on one credit if you knew what you were doing.
[1:05:05] SPEAKER: - But perfect arcade game.
[1:05:07] SPEAKER: - Is that a fun use of your time?
[1:05:09] SPEAKER: I'm not sure.
[1:05:10] SPEAKER: - I don't know, you get to see the whole story
[1:05:11] SPEAKER: and I think people had special feelings
[1:05:13] SPEAKER: about the female leads in most of those games as well.
[1:05:16] SPEAKER: - That's, yes, Daphne, is that her name?
[1:05:18] SPEAKER: - Daphne was the one in Dragon's Lair.
[1:05:21] SPEAKER: I don't think I ever saw,
[1:05:22] SPEAKER: I only saw the later Space Aces that weren't FMV games.
[1:05:26] SPEAKER: - Yeah, last thing about Laserdisc that I was reminded of
[1:05:29] SPEAKER: in reading about this is that some movies
[1:05:32] SPEAKER: still have yet to ever be released on a more recent format.
[1:05:35] SPEAKER: There were some movies that last came out on Laserdisc
[1:05:38] SPEAKER: and that's basically the best
[1:05:40] SPEAKER: and possibly only way to watch them.
[1:05:43] SPEAKER: - Yeah, well, especially if you think about all the movies
[1:05:45] SPEAKER: that the original prints were lost on recently,
[1:05:49] SPEAKER: there's probably quite a bit of stuff
[1:05:50] SPEAKER: that's only available on Laserdisc at this point.
[1:05:52] SPEAKER: - Yes.
[1:05:53] SPEAKER: - And I wonder, it's always interesting
[1:05:57] SPEAKER: 'cause when the special editions of Star Wars came out,
[1:06:01] SPEAKER: the early versions of the Harmey cuts and stuff like that
[1:06:04] SPEAKER: used a lot of Laserdisc footage until there was, I think,
[1:06:06] SPEAKER: a New Zealand broadcast in HD
[1:06:11] SPEAKER: or something that they ended up using
[1:06:12] SPEAKER: for a lot of the other stuff, but anyway.
[1:06:13] SPEAKER: - Yes, that's correct.
[1:06:15] SPEAKER: So anyway, a lot of those Laserdiscs
[1:06:16] SPEAKER: are very sought after today for movies and anime and stuff
[1:06:19] SPEAKER: that has never come out on anything else
[1:06:21] SPEAKER: and there's a big scene around capturing those
[1:06:23] SPEAKER: in increasingly higher qualities,
[1:06:26] SPEAKER: which we should touch on at the end of this.
[1:06:27] SPEAKER: - Well, I was gonna say, one of the interesting things
[1:06:29] SPEAKER: that's come out in the last few years,
[1:06:30] SPEAKER: and we'll talk about this at the end,
[1:06:32] SPEAKER: but is that because this stuff is analog,
[1:06:35] SPEAKER: your ability to pull,
[1:06:37] SPEAKER: like there's not an upper limit
[1:06:38] SPEAKER: to the quality of the capture.
[1:06:40] SPEAKER: I mean, there is an upper limit, but it's not a binary,
[1:06:44] SPEAKER: is it the good version or is it less than the good version
[1:06:47] SPEAKER: like it is with a DVD copy or something like that?
[1:06:49] SPEAKER: - Yes, but it does turn out to be significantly higher
[1:06:51] SPEAKER: quality than what any of the players
[1:06:53] SPEAKER: on the market can produce.
[1:06:54] SPEAKER: - Oh, that's interesting.
[1:06:55] SPEAKER: - Yeah, so we'll talk about that at the end.
[1:06:57] SPEAKER: There's a fascinating scene around capturing analog video
[1:07:01] SPEAKER: from some of this old media.
[1:07:02] SPEAKER: Before we get there, should do another little digression
[1:07:05] SPEAKER: here into a failed format,
[1:07:07] SPEAKER: and it's a bizarre, fascinating failed format.
[1:07:09] SPEAKER: - I'd never heard of this one, Brad.
[1:07:11] SPEAKER: - I've been aware of this for a while,
[1:07:13] SPEAKER: but I wasn't super clear on how it worked.
[1:07:15] SPEAKER: The capacitance electronic disc.
[1:07:18] SPEAKER: - This is another format that I think we have to shout out,
[1:07:21] SPEAKER: Technology Connections, because they've done hours
[1:07:23] SPEAKER: and hours and hours of videos about this thing.
[1:07:25] SPEAKER: - They have like a two hour long series of videos about CD.
[1:07:28] SPEAKER: - Yeah.
[1:07:29] SPEAKER: - Which hit the market in 1981, it was made by RCA.
[1:07:32] SPEAKER: Apparently started development in 1964.
[1:07:36] SPEAKER: - Wow.
[1:07:37] SPEAKER: - Although it started originally, so I mean,
[1:07:38] SPEAKER: so not to bury the lead here.
[1:07:40] SPEAKER: CD functions like a record, like a vinyl record,
[1:07:44] SPEAKER: like an LP, which is to say there is an actual stylus.
[1:07:46] SPEAKER: There's basically a needle that reads the disc.
[1:07:50] SPEAKER: - I'm making indistinguishable, incomprehensible noises.
[1:07:55] SPEAKER: How does that work?
[1:07:56] SPEAKER: - So, but it's not picking up physical grooves,
[1:08:00] SPEAKER: physical variations, the way a record player would use me,
[1:08:04] SPEAKER: where the needle is actually like physically writing
[1:08:08] SPEAKER: what it's playing.
[1:08:09] SPEAKER: - Yeah.
[1:08:10] SPEAKER: - In this case, that's where the capacitance
[1:08:11] SPEAKER: in the CD name comes in.
[1:08:13] SPEAKER: It's actually reading these information stored
[1:08:16] SPEAKER: on the disc electrically.
[1:08:17] SPEAKER: The stylus, the needle for want of a better term,
[1:08:22] SPEAKER: is capacitive and it's basically forming a circuit
[1:08:25] SPEAKER: with the disc as it's reading the data electrically from it.
[1:08:29] SPEAKER: - Wow.
[1:08:29] SPEAKER: - So it's still touching the disc
[1:08:31] SPEAKER: and it's still physically touching the disc.
[1:08:33] SPEAKER: And the course of development,
[1:08:34] SPEAKER: they ended up putting a layer of silicone on the disc
[1:08:36] SPEAKER: as kind of a lubricant to try to increase the longevity
[1:08:41] SPEAKER: of both the stylus and the discs.
[1:08:44] SPEAKER: - This already sounds like a bad idea, Brad.
[1:08:46] SPEAKER: - So the reason I mentioned that it works
[1:08:48] SPEAKER: like a record player is that in the sixties,
[1:08:49] SPEAKER: when they started working on this,
[1:08:50] SPEAKER: originally it was an attempt to increase the amount
[1:08:52] SPEAKER: of audio you could store on an LP.
[1:08:55] SPEAKER: - So that your depressed poet society album
[1:09:00] SPEAKER: could fit on one CD disc instead of two?
[1:09:02] SPEAKER: - Yes, exactly.
[1:09:03] SPEAKER: I mean, they accomplished that goal apparently very well.
[1:09:06] SPEAKER: I didn't look at the ratio of how much more audio
[1:09:08] SPEAKER: this could store than a regular vinyl record,
[1:09:10] SPEAKER: but I'm sure it's quite large.
[1:09:11] SPEAKER: But it languished in development for so long
[1:09:14] SPEAKER: that by the time they had decided to make it a video format
[1:09:17] SPEAKER: and got it done in two markets,
[1:09:19] SPEAKER: LaserDisc had beaten them by three years
[1:09:21] SPEAKER: and LaserDisc was already superior.
[1:09:22] SPEAKER: - Wow.
[1:09:24] SPEAKER: - It's a 12 inch disc, just like LaserDisc.
[1:09:26] SPEAKER: It holds about the same amount.
[1:09:27] SPEAKER: I think it's also 60 minutes per side.
[1:09:30] SPEAKER: Probably the craziest thing about this format,
[1:09:32] SPEAKER: if you've never seen it,
[1:09:33] SPEAKER: is it turned out that these discs were incredibly susceptible
[1:09:37] SPEAKER: to being disrupted by dust,
[1:09:39] SPEAKER: not just dust sticking on the disc,
[1:09:40] SPEAKER: but apparently like if I understood dust plus humidity,
[1:09:44] SPEAKER: contacting these discs would create permanent damage
[1:09:46] SPEAKER: to the disc in some way or permanent distortion.
[1:09:48] SPEAKER: - Because the dust could hold a charge?
[1:09:50] SPEAKER: - During testing, it was shown that exposure to dust
[1:09:52] SPEAKER: caused skipped grooves.
[1:09:54] SPEAKER: If dust was allowed to settle on the discs,
[1:09:56] SPEAKER: the dust would absorb moisture from the air
[1:09:57] SPEAKER: and cement the dust particle to the disc surface.
[1:10:01] SPEAKER: - Oh boy.
[1:10:01] SPEAKER: - Causing the stylus to jump back
[1:10:03] SPEAKER: in a locked groove situation.
[1:10:05] SPEAKER: Thus, and I'll just read the rest of this
[1:10:07] SPEAKER: 'cause it explains their solution.
[1:10:09] SPEAKER: Thus, an idea was developed in which the disc
[1:10:10] SPEAKER: would be stored and handled in a plastic caddy
[1:10:13] SPEAKER: from which the CED would be extracted by the player
[1:10:17] SPEAKER: so that exposure to dust would be minimized.
[1:10:19] SPEAKER: I put a very short video in the show notes
[1:10:21] SPEAKER: that you can watch that is just somebody with a CD player
[1:10:24] SPEAKER: showing how it works.
[1:10:25] SPEAKER: It's literally like a record, like an LP size,
[1:10:27] SPEAKER: you know what an album cover looks like for an LP?
[1:10:30] SPEAKER: It's like that, the cartridge is big and broad like that,
[1:10:34] SPEAKER: big square with the movie poster on it.
[1:10:36] SPEAKER: You stick that entire giant caddy into the player,
[1:10:40] SPEAKER: wait about three seconds and then pull the caddy back out.
[1:10:43] SPEAKER: And at that point, the disc has been grabbed by the player
[1:10:46] SPEAKER: and is stored inside ready for playback.
[1:10:48] SPEAKER: - Oh, wow.
[1:10:49] SPEAKER: - Yes.
[1:10:50] SPEAKER: - Actually, this is a trip.
[1:10:52] SPEAKER: - Yes, it's pretty wild.
[1:10:53] SPEAKER: And the guy, and this is just one of these little
[1:10:56] SPEAKER: throwaway YouTube videos where the guy just pointed a camera
[1:10:59] SPEAKER: at his screen and player and talked over for three minutes,
[1:11:01] SPEAKER: but he mentions in there, he's like,
[1:11:03] SPEAKER: "Yeah, this is known as a skippy format,
[1:11:05] SPEAKER: but if you're careful with your discs
[1:11:07] SPEAKER: and you keep your player in good shape,
[1:11:08] SPEAKER: it's really not a problem."
[1:11:09] SPEAKER: - Wow.
[1:11:10] SPEAKER: - So I don't believe CED had chapter markers
[1:11:13] SPEAKER: the way laser disc did, but you could jog back and forth
[1:11:15] SPEAKER: through it quite quickly.
[1:11:17] SPEAKER: He shows that off in there.
[1:11:18] SPEAKER: You can kind of fast forward minutes at a time very quickly.
[1:11:21] SPEAKER: - Do you have a sense of how dense were the grooves
[1:11:24] SPEAKER: compared to a traditional record?
[1:11:26] SPEAKER: - The groove is 657 nanometers wide
[1:11:29] SPEAKER: and has a length of up to 12 miles per disc.
[1:11:32] SPEAKER: - So that's way bigger, that's way more dense
[1:11:34] SPEAKER: than an LP, I think.
[1:11:37] SPEAKER: - Yeah, I would think so.
[1:11:39] SPEAKER: At any rate, one side effect of the way this thing works
[1:11:43] SPEAKER: that occurred to me is that this was a way to,
[1:11:45] SPEAKER: you know how people display LP album art,
[1:11:48] SPEAKER: sometimes they frame it or put it up
[1:11:50] SPEAKER: on the wall in their homes.
[1:11:51] SPEAKER: This would have kind of been a way
[1:11:52] SPEAKER: to get a cool version of that for movies
[1:11:55] SPEAKER: because that's what these caddies were exactly
[1:11:57] SPEAKER: was just a big record cover looking
[1:12:00] SPEAKER: movie poster display thing.
[1:12:02] SPEAKER: Would have been a cool way to do some found art later.
[1:12:04] SPEAKER: - I mean, they look like giant, they look like...
[1:12:08] SPEAKER: Well, so there was a moment when Blu-ray was being developed
[1:12:11] SPEAKER: where it was thought that it was gonna have to be
[1:12:13] SPEAKER: in caddies too 'cause they hadn't figured out
[1:12:14] SPEAKER: to make the discs not scratch and scratches disrupted.
[1:12:18] SPEAKER: The grooves were so fine that scratches were very disruptive.
[1:12:22] SPEAKER: - Yeah, I actually, I've heard this in the notes.
[1:12:24] SPEAKER: Can you help me remember in what capacity CD caddies
[1:12:28] SPEAKER: were used in the early days of CD-ROM?
[1:12:29] SPEAKER: Like did some CDs ship in caddies or was it...
[1:12:32] SPEAKER: - Some players had caddies.
[1:12:34] SPEAKER: - That's what it was.
[1:12:35] SPEAKER: Some CD-ROMs had caddies and you put the disc in the caddy
[1:12:37] SPEAKER: and then loaded the caddy, correct?
[1:12:39] SPEAKER: - Yeah, so my first CD-ROM player was a caddy CD-ROM player
[1:12:43] SPEAKER: and it was because it spun at 2X speed, I believe,
[1:12:47] SPEAKER: which meant that, I don't know, I assume it needed the caddy
[1:12:51] SPEAKER: because they couldn't spindle it up
[1:12:53] SPEAKER: at high speeds or something.
[1:12:55] SPEAKER: - Yeah, that makes sense.
[1:12:57] SPEAKER: - But yeah, so fast forward, quick, smooth, fast forward
[1:13:02] SPEAKER: and rewind from the video that I saw on the CD.
[1:13:05] SPEAKER: - Yes.
[1:13:06] SPEAKER: - What a weird format.
[1:13:08] SPEAKER: - You could pause it, but you didn't get a freeze frame of,
[1:13:11] SPEAKER: you didn't get a freeze frame of the video.
[1:13:12] SPEAKER: - Oh, did it just stop?
[1:13:13] SPEAKER: - No, because it kept spinning and it couldn't just hang.
[1:13:16] SPEAKER: It couldn't linger on one single frame
[1:13:18] SPEAKER: because it just kept spinning, you know, so.
[1:13:21] SPEAKER: Sorry, I think I totally glossed over
[1:13:23] SPEAKER: the video quality of this thing.
[1:13:24] SPEAKER: It was about 240 lines of resolution,
[1:13:26] SPEAKER: so this actually did not look much better
[1:13:27] SPEAKER: than VHS and beta of the time.
[1:13:29] SPEAKER: - Oh, that seems, well, and also it wasn't durable.
[1:13:32] SPEAKER: Like RCA said, you could only play 500 times or something.
[1:13:35] SPEAKER: - That was the other thing is that RCA,
[1:13:36] SPEAKER: that the manufacturer themselves estimated
[1:13:38] SPEAKER: that a retail movie could be played back about 500 times.
[1:13:41] SPEAKER: - That means it's not much better for wear than a VHS tape.
[1:13:44] SPEAKER: - Right, so, I mean, granted, you know,
[1:13:47] SPEAKER: are you really gonna watch a movie that you bought
[1:13:48] SPEAKER: 500 times, probably not very often.
[1:13:51] SPEAKER: - I'm gonna go and tell you, if you have kids
[1:13:52] SPEAKER: and you buy movies for them to watch,
[1:13:54] SPEAKER: often you, I assure you, I've seen Frozen 500 times
[1:13:57] SPEAKER: in all 11 years of my daughter's life.
[1:13:59] SPEAKER: - That's fair.
[1:14:00] SPEAKER: - Probably also the Little Mermaid.
[1:14:02] SPEAKER: - Yes, anyway, that's why I mentioned earlier
[1:14:04] SPEAKER: that laser discs theoretically could be played forever.
[1:14:06] SPEAKER: Obviously there are plenty of other factors involved there,
[1:14:08] SPEAKER: but that was explicitly not the case with this other
[1:14:12] SPEAKER: competing disc format, but CEDs were going to wear out
[1:14:16] SPEAKER: relatively quickly.
[1:14:16] SPEAKER: - What a weird thing, like I have no,
[1:14:20] SPEAKER: unlike the laser discs and the different tape formats,
[1:14:23] SPEAKER: I have absolutely no exposure to this
[1:14:25] SPEAKER: in a real world context at all.
[1:14:27] SPEAKER: I never saw one of these, I don't think.
[1:14:29] SPEAKER: - It did not last long.
[1:14:30] SPEAKER: It launched in 1981 under the name Selectavision.
[1:14:34] SPEAKER: - It's a pretty good name.
[1:14:35] SPEAKER: - That's a good ass 80s product name, actually.
[1:14:38] SPEAKER: - Why do you think they called it select?
[1:14:39] SPEAKER: Is it 'cause you could select where to drop the needle
[1:14:41] SPEAKER: and play at any time?
[1:14:42] SPEAKER: - I don't know, maybe.
[1:14:43] SPEAKER: - Do you think you could like DJ it and like spin this,
[1:14:45] SPEAKER: it's like release the motor and like spin the video
[1:14:48] SPEAKER: like you would if you were a hip hop DJ?
[1:14:51] SPEAKER: It's kind of amazing.
[1:14:52] SPEAKER: - Open up the top of your player to do that, I guess.
[1:14:54] SPEAKER: - You'd have to have a clean room,
[1:14:55] SPEAKER: probably given how dust prone they were.
[1:14:57] SPEAKER: - Sure.
[1:14:59] SPEAKER: Anyway, like I said, by the time they came out,
[1:15:01] SPEAKER: laser disc was already better.
[1:15:03] SPEAKER: So this really did not go anywhere.
[1:15:04] SPEAKER: It came out in '81.
[1:15:05] SPEAKER: They stopped making players by '84
[1:15:08] SPEAKER: and they stopped making movies in '86.
[1:15:10] SPEAKER: - Dead format.
[1:15:10] SPEAKER: - Yep, yep, but a fascinating one.
[1:15:13] SPEAKER: - You know, it lasted longer than HD DVD.
[1:15:15] SPEAKER: - Yeah, fair, that's true.
[1:15:16] SPEAKER: - Next on the list are some home video formats,
[1:15:20] SPEAKER: notably Video 8.
[1:15:22] SPEAKER: This was in 1985.
[1:15:24] SPEAKER: It's pretty much also ended up being a Sony format,
[1:15:26] SPEAKER: but it was co-developed with Kodak, JVC,
[1:15:28] SPEAKER: Hitachi, Matsushita/Panasonic, and Philips.
[1:15:33] SPEAKER: In 1986, most of the partners that weren't Sony
[1:15:35] SPEAKER: announced plans to embrace VHS-C for their cameras instead.
[1:15:40] SPEAKER: And the main benefit of Video 8
[1:15:42] SPEAKER: was a smaller, skinnier cartridge,
[1:15:44] SPEAKER: so you could do high quality video
[1:15:47] SPEAKER: on like handy cam style camcorders.
[1:15:52] SPEAKER: It was not compatible in any way with VHS,
[1:15:56] SPEAKER: but because everything had RCA plugs,
[1:15:58] SPEAKER: the cam recorder and your VHS player,
[1:16:01] SPEAKER: it was pretty easy to do a one generation loss transfer
[1:16:04] SPEAKER: from the camcorder to a VHS player or whatever.
[1:16:07] SPEAKER: - God, this is making me realize
[1:16:08] SPEAKER: how long and varied Sony's history is
[1:16:10] SPEAKER: of trying to create their own formats that they control.
[1:16:13] SPEAKER: - Yeah, I think this was a natural offshoot.
[1:16:15] SPEAKER: Like the Video 8 stuff, the video quality on it
[1:16:19] SPEAKER: was noticeably better 'cause it had more lines of resolution.
[1:16:21] SPEAKER: I wasn't, now I say that, I wasn't actually able
[1:16:24] SPEAKER: to find a clear definition of what the Video 8 format was.
[1:16:28] SPEAKER: It's like, I'm sure it's out there.
[1:16:30] SPEAKER: I'm gonna get a bazillion comments.
[1:16:32] SPEAKER: It was the upgraded version, Hi8,
[1:16:34] SPEAKER: which came out in the late '80s or early '90s,
[1:16:37] SPEAKER: gave you 400 total lines of resolution
[1:16:40] SPEAKER: of which there was still some split off for the V-Sync,
[1:16:42] SPEAKER: but you got a better than NTSC basically format.
[1:16:48] SPEAKER: But it worked with NTSC or PAL, just like VHS and beta.
[1:16:53] SPEAKER: - Yeah, but I mean, sorry, sorry.
[1:16:55] SPEAKER: From beta max to this, to Video 8, to was Minidisc?
[1:17:01] SPEAKER: - Proprietary, was that proprietary or no?
[1:17:04] SPEAKER: - Oh, Minidisc was absolutely proprietary, yeah.
[1:17:06] SPEAKER: - Like to the various memory stick formats
[1:17:10] SPEAKER: that they tried to foist on people instead of SD cards.
[1:17:12] SPEAKER: Like Sony really, I think they may have finally
[1:17:15] SPEAKER: learned their lesson, but that was probably mostly forced
[1:17:17] SPEAKER: by the kind of end of physical formats.
[1:17:19] SPEAKER: - You say they finally learned their lesson,
[1:17:20] SPEAKER: but they're, you know, Blu-ray is now more than 15 years old
[1:17:25] SPEAKER: almost and 10 years old and it turns out they get a check
[1:17:30] SPEAKER: every time somebody buys a Blu-ray disc.
[1:17:32] SPEAKER: - Oh yeah, it was all worth it, I'm sure.
[1:17:35] SPEAKER: - Yeah, they finally, all you need is the last one
[1:17:37] SPEAKER: it turns out and you win.
[1:17:39] SPEAKER: - Yes, yes.
[1:17:40] SPEAKER: - So High 8 came out in the early '90s,
[1:17:41] SPEAKER: it was better resolution Video 8.
[1:17:45] SPEAKER: Those Video 8 tapes will play in a High 8 camera,
[1:17:48] SPEAKER: but not the other way around, obviously.
[1:17:50] SPEAKER: And we'll talk about it next time,
[1:17:52] SPEAKER: but there was a later extension to High 8
[1:17:54] SPEAKER: that made it digital in the early 2000s.
[1:17:59] SPEAKER: - These were basically camcorder formats
[1:18:01] SPEAKER: that you bought the tapes that you needed
[1:18:03] SPEAKER: for the camcorder you have and that was pretty much it.
[1:18:05] SPEAKER: - That's when tapes started getting small.
[1:18:07] SPEAKER: - I have a High 8 VHS, a High 8 camcorder
[1:18:10] SPEAKER: that I bought in the late '90s.
[1:18:11] SPEAKER: - That's cool.
[1:18:12] SPEAKER: - Yeah, it's fine.
[1:18:13] SPEAKER: - Yeah, I'm sure it was.
[1:18:15] SPEAKER: We should talk about Sony HDVS briefly here.
[1:18:18] SPEAKER: It's kind of out of scope for this episode
[1:18:20] SPEAKER: 'cause it never became a home format,
[1:18:22] SPEAKER: although it might have in an alternate universe.
[1:18:24] SPEAKER: - Yeah, this is, my grandparents were super stoked
[1:18:27] SPEAKER: about this in the '80s.
[1:18:28] SPEAKER: - Really?
[1:18:28] SPEAKER: - Yeah, they were, my grandparents loved
[1:18:31] SPEAKER: a good advance in TV.
[1:18:33] SPEAKER: - Oh, wow, I'm very impressed they even knew about this.
[1:18:36] SPEAKER: - So my grandmother, her dad,
[1:18:39] SPEAKER: when they were kids in England, in pre-war England,
[1:18:43] SPEAKER: hung, like literally hand-built a radio
[1:18:48] SPEAKER: and ran copper wire around the crown molding
[1:18:51] SPEAKER: of their living room so they could listen
[1:18:53] SPEAKER: to the first broadcast on BBC One when she was a kid.
[1:18:56] SPEAKER: - That's amazing.
[1:18:57] SPEAKER: - Like the long history of being into the new technology
[1:18:59] SPEAKER: shed, I guess, in my family.
[1:19:00] SPEAKER: - That is rad.
[1:19:03] SPEAKER: The Sony HDVS really never proceeded past
[1:19:06] SPEAKER: like a very expensive production setup,
[1:19:09] SPEAKER: but it was their first attempt at analog HD video
[1:19:11] SPEAKER: at a time when it had not been standardized yet.
[1:19:13] SPEAKER: - And they did a lot of like press tour stuff with this
[1:19:16] SPEAKER: as my, like the, if I had to guess,
[1:19:18] SPEAKER: my grandmother knew about this because of Newsweek
[1:19:20] SPEAKER: would probably be the place she would have picked it up.
[1:19:22] SPEAKER: - I can see that.
[1:19:23] SPEAKER: They kind of, from the sound of it,
[1:19:25] SPEAKER: they basically jumped the gun and they kind of tried
[1:19:27] SPEAKER: to predict what they thought was going to be
[1:19:29] SPEAKER: the analog high definition broadcast standard
[1:19:31] SPEAKER: and kind of develop that preemptively.
[1:19:33] SPEAKER: They did end up with an analog video pipeline
[1:19:35] SPEAKER: that Wikipedia described it as a resolution of 1125 lines,
[1:19:39] SPEAKER: but only 1035 active ones.
[1:19:41] SPEAKER: So I guess there's something in the overscan
[1:19:43] SPEAKER: or I'm not sure exactly what the-
[1:19:44] SPEAKER: - It's probably Vsync and metadata would be my guess.
[1:19:48] SPEAKER: - But not, you know, not far off at all
[1:19:49] SPEAKER: from the 1080p that people finally settled on
[1:19:52] SPEAKER: for the digital high definition standard.
[1:19:54] SPEAKER: - Wasn't 16 by nine though.
[1:19:56] SPEAKER: - It was later.
[1:19:56] SPEAKER: So I think I don't have it in front of me right now.
[1:19:58] SPEAKER: I think it was like five by four was the original ratio,
[1:20:04] SPEAKER: but then it became 16 by nine in the late eighties.
[1:20:08] SPEAKER: I believe by the late eighties it had become 16 by nine.
[1:20:10] SPEAKER: Yeah, sorry, five to three.
[1:20:12] SPEAKER: Five to three was the original aspect ratio
[1:20:15] SPEAKER: and then later 16 by nine.
[1:20:16] SPEAKER: - Okay, so that's 15 by nine, basically?
[1:20:19] SPEAKER: - Yeah. - Yeah, okay.
[1:20:21] SPEAKER: - At any rate, this never made it home.
[1:20:22] SPEAKER: There was never any home format
[1:20:26] SPEAKER: that this was distributed on.
[1:20:27] SPEAKER: There were no TVs that could display it at the time.
[1:20:29] SPEAKER: So obviously, apparently when this came out,
[1:20:32] SPEAKER: it came out in 1986 and a basic production setup
[1:20:34] SPEAKER: which was literally one camera,
[1:20:36] SPEAKER: a monitor and a tape recorder was a million and a half dollars
[1:20:39] SPEAKER: - Wow.
[1:20:40] SPEAKER: - And the tapes cost $2,500 per hour of tapeable footage.
[1:20:45] SPEAKER: - Do you think this is 'cause of the cameras and stuff
[1:20:47] SPEAKER: where it was basically built by hand?
[1:20:49] SPEAKER: - Maybe, I don't know. - These are one-offs?
[1:20:50] SPEAKER: - I don't know.
[1:20:51] SPEAKER: From what I read, it sounds like
[1:20:52] SPEAKER: they sold these production setups in the dozens at best.
[1:20:54] SPEAKER: - That seems right.
[1:20:55] SPEAKER: - For how expensive it was.
[1:20:57] SPEAKER: It was used here and there,
[1:20:59] SPEAKER: like a couple of feature films were shot on it,
[1:21:01] SPEAKER: a couple of TV movies,
[1:21:02] SPEAKER: a fair number of concert films from the sound of it.
[1:21:06] SPEAKER: The Genesis Invisible Touch Tour,
[1:21:08] SPEAKER: apparently was shot on this.
[1:21:10] SPEAKER: Very, very limited use in production.
[1:21:13] SPEAKER: And in most cases,
[1:21:15] SPEAKER: if somebody even saw footage shot with this,
[1:21:17] SPEAKER: it was transferred to film and shown in theaters
[1:21:19] SPEAKER: or shown over NTSC, which would have lost a lot
[1:21:22] SPEAKER: of the quality anyway of a broadcast.
[1:21:24] SPEAKER: - Yeah, you sent me some YouTube videos
[1:21:25] SPEAKER: that seemed to be ripped from like a high quality
[1:21:28] SPEAKER: analog source that were really, it was,
[1:21:31] SPEAKER: it's funny, when I watched them at first,
[1:21:32] SPEAKER: I wasn't, I didn't clock anything as being weird about them.
[1:21:36] SPEAKER: But then when you pointed out what I should be looking for,
[1:21:38] SPEAKER: it was like, oh, right.
[1:21:39] SPEAKER: All of this stuff is stuff that you don't see
[1:21:41] SPEAKER: on modern digital equipment.
[1:21:43] SPEAKER: - Yeah, I've got a link to the show notes.
[1:21:44] SPEAKER: The Sony, the Metamorphosis demo from 1990
[1:21:47] SPEAKER: is like fairly famous.
[1:21:49] SPEAKER: I think it's only been about four years ago,
[1:21:51] SPEAKER: maybe less that somebody found like an original copy
[1:21:54] SPEAKER: and captured it in high definition.
[1:21:57] SPEAKER: But it is high def analog video.
[1:21:59] SPEAKER: So it's like roughly the resolution of 1080p
[1:22:02] SPEAKER: that you're used to,
[1:22:03] SPEAKER: but with all of the characteristics of analog video,
[1:22:06] SPEAKER: you know, like, like in this, this,
[1:22:07] SPEAKER: there's a bunch of footage of like kind of a dance party
[1:22:09] SPEAKER: in a studio here.
[1:22:10] SPEAKER: And you see like every time the camera
[1:22:12] SPEAKER: pans across the studio lights,
[1:22:13] SPEAKER: you get those like streaky after images,
[1:22:16] SPEAKER: kind of trails on the, on the bright lights and stuff.
[1:22:18] SPEAKER: It's just kind of uncanny to me to see something this clear
[1:22:21] SPEAKER: and crisp from the late eighties,
[1:22:23] SPEAKER: but with those hallmarks of,
[1:22:25] SPEAKER: of what analog video looked like back then.
[1:22:27] SPEAKER: - I also wonder if watching them on an analog TV,
[1:22:30] SPEAKER: instead of being filtered through the, you know,
[1:22:32] SPEAKER: the YouTube digital compression thing,
[1:22:35] SPEAKER: the pipeline would, would make them stand out even more.
[1:22:38] SPEAKER: Cause like there's, there's a thing that happens
[1:22:41] SPEAKER: with brains where like when DVD was popular
[1:22:45] SPEAKER: and, and, and like I was getting digital cable
[1:22:49] SPEAKER: and digital satellite TV, we're getting,
[1:22:51] SPEAKER: we're both MPEG-2 compression on every channel.
[1:22:54] SPEAKER: Your brain eventually started filtering out
[1:22:56] SPEAKER: all the MPEG-2 compression artifacts.
[1:22:58] SPEAKER: When you go back and watch MPEG-2 video now,
[1:23:01] SPEAKER: the compression artifacts are really, really visible
[1:23:03] SPEAKER: and, and, and really stand out.
[1:23:06] SPEAKER: I assume the same thing's happened with the stuff
[1:23:07] SPEAKER: that H.264 and H.265 and,
[1:23:09] SPEAKER: and at some point in the future AV1 will do as well.
[1:23:13] SPEAKER: But I, I, my bet is that this looks the, on a CRT,
[1:23:17] SPEAKER: this would look remarkable.
[1:23:19] SPEAKER: - Probably, yeah.
[1:23:21] SPEAKER: Unfortunately not a lot of HD CRTs around to see.
[1:23:23] SPEAKER: - No, sadly no.
[1:23:24] SPEAKER: - At this point.
[1:23:25] SPEAKER: I do, I do wish whoever had gotten their hands
[1:23:27] SPEAKER: on the hardware and this tape and had captured it,
[1:23:29] SPEAKER: had put out a kind of raw version that hadn't run
[1:23:32] SPEAKER: through the shitty YouTube compression.
[1:23:34] SPEAKER: - Yeah.
[1:23:35] SPEAKER: - It would be a cool historical artifact to have.
[1:23:37] SPEAKER: The other reason I was going to say this footage
[1:23:38] SPEAKER: is very famous, at least to me, and this is,
[1:23:41] SPEAKER: this is going back to being in like Mr. Land.
[1:23:43] SPEAKER: This, this was used in all kinds of other Sony contexts,
[1:23:46] SPEAKER: like the PlayStation one developer disc that they put out
[1:23:50] SPEAKER: that demos a bunch of what the PlayStation one can do.
[1:23:53] SPEAKER: - Wait, what?
[1:23:54] SPEAKER: - Really?
[1:23:55] SPEAKER: - Uses this footage on it, except in like shitty,
[1:23:57] SPEAKER: shitty low quality motion JPEG or whatever codec.
[1:24:00] SPEAKER: - The CD is what they, what they CDV1 I think, right?
[1:24:03] SPEAKER: - And that CD, you know,
[1:24:04] SPEAKER: it's also got the famous T-Rex 3D model on it,
[1:24:07] SPEAKER: but that CD lets you like map this video
[1:24:10] SPEAKER: onto a bunch of like floating spheres and cubes
[1:24:13] SPEAKER: and do weird manipulations on it.
[1:24:14] SPEAKER: So like Sony used this footage in like R&D and like test
[1:24:18] SPEAKER: and development contexts for a long time
[1:24:21] SPEAKER: after they shot this.
[1:24:22] SPEAKER: So it's like, it's pretty visible.
[1:24:24] SPEAKER: So it's cool that somebody went back
[1:24:25] SPEAKER: and found the original quality version.
[1:24:28] SPEAKER: - That's a trip.
[1:24:30] SPEAKER: So I think that takes us to the end of the analog scene
[1:24:32] SPEAKER: for the most part.
[1:24:33] SPEAKER: - Pretty much, yeah.
[1:24:34] SPEAKER: - I'd be curious if people feel like we missed something,
[1:24:36] SPEAKER: please let us know techpod@content.town
[1:24:39] SPEAKER: as the email address.
[1:24:41] SPEAKER: Should we talk about, I want to talk about the duping,
[1:24:43] SPEAKER: the preservation scene for this stuff.
[1:24:45] SPEAKER: 'Cause like there is,
[1:24:47] SPEAKER: there's a lot of really amazing stuff happening with people,
[1:24:51] SPEAKER: which is, it's the right time for it to happen
[1:24:52] SPEAKER: 'cause we're reaching the end of life
[1:24:54] SPEAKER: on a lot of older analog tapes now,
[1:24:56] SPEAKER: especially if they weren't stored
[1:24:58] SPEAKER: in pretty stable conditions.
[1:25:02] SPEAKER: But yeah, I'm curious what's going on
[1:25:05] SPEAKER: with the preservation scene, right?
[1:25:06] SPEAKER: - Yeah, I'm just gonna describe this from memory
[1:25:08] SPEAKER: 'cause I haven't dug into it too much.
[1:25:09] SPEAKER: Like this would be a whole episode unto itself
[1:25:11] SPEAKER: and I wouldn't even undertake that episode
[1:25:13] SPEAKER: unless I actually buy some of this equipment
[1:25:15] SPEAKER: and try to start doing some of it, which I have considered.
[1:25:18] SPEAKER: - We can have an expert guest on too for this one.
[1:25:20] SPEAKER: - We certainly could.
[1:25:21] SPEAKER: But I want to mess with this.
[1:25:23] SPEAKER: I've got some use cases for this
[1:25:25] SPEAKER: that I'm kind of waffling on
[1:25:26] SPEAKER: whether it's worth getting into or not.
[1:25:28] SPEAKER: There's kind of multiple projects, some hardware,
[1:25:30] SPEAKER: some software in open source that have kind of come together
[1:25:33] SPEAKER: to make all this stuff happen.
[1:25:35] SPEAKER: The oldest one I'm familiar with is LDD code, LD-D code,
[1:25:39] SPEAKER: which is straight up just a GitHub repository
[1:25:41] SPEAKER: you can go find, which as you might expect,
[1:25:43] SPEAKER: stands for laser disc decode.
[1:25:44] SPEAKER: That has been used in combination with a device called,
[1:25:47] SPEAKER: I believe the pronunciation is the doomsday duplicator,
[1:25:50] SPEAKER: even though it's spelled like a domes day,
[1:25:53] SPEAKER: which I believe is some UK listeners
[1:25:56] SPEAKER: are yelling at the radio right now.
[1:25:57] SPEAKER: I think it was some kind of educational broadcast
[1:25:59] SPEAKER: or something.
[1:26:00] SPEAKER: - Is this the made for TV movie
[1:26:03] SPEAKER: that freaked everybody in the UK out?
[1:26:05] SPEAKER: - No, I don't think so.
[1:26:06] SPEAKER: I think that's, oh God, what is the name of that movie?
[1:26:08] SPEAKER: That, oh, it's on the tip of my tongue.
[1:26:09] SPEAKER: I know what you're talking about.
[1:26:10] SPEAKER: The post-apocalyptic, the nuclear war one.
[1:26:12] SPEAKER: - Yeah.
[1:26:13] SPEAKER: - That's not Threads, is it?
[1:26:16] SPEAKER: - I don't know.
[1:26:17] SPEAKER: - I believe that's Threads, the 1984,
[1:26:20] SPEAKER: I'm looking at it now, TV movie.
[1:26:22] SPEAKER: - It is Threads, yes.
[1:26:23] SPEAKER: - I've heard that movie spoken about
[1:26:26] SPEAKER: in Hushtones for a long time.
[1:26:28] SPEAKER: - I have British friends who have been like,
[1:26:30] SPEAKER: yeah, don't watch that.
[1:26:31] SPEAKER: It's bad, it'll mess you up.
[1:26:33] SPEAKER: - That movie has been infamous on forums and stuff
[1:26:35] SPEAKER: for a long time for, yes.
[1:26:37] SPEAKER: - Right, if they were the grave of the fireflies
[1:26:39] SPEAKER: in terms of things I'm never gonna watch.
[1:26:41] SPEAKER: - Very much so.
[1:26:42] SPEAKER: I don't know what the origin of the term doomsday is
[1:26:44] SPEAKER: in this context, but long story short,
[1:26:46] SPEAKER: let me cut to the chase here on what the hardware element
[1:26:48] SPEAKER: of why this is interesting.
[1:26:50] SPEAKER: And now there is a VHS decode
[1:26:52] SPEAKER: that has descended from the LDD code project,
[1:26:55] SPEAKER: which kind of does the same thing for VHS,
[1:26:56] SPEAKER: as you might imagine.
[1:26:57] SPEAKER: Here's what they're doing though.
[1:26:58] SPEAKER: And the hardware has an FPGA in it.
[1:27:01] SPEAKER: Like it's a whole development thing
[1:27:02] SPEAKER: you need to put together on multiple boards
[1:27:04] SPEAKER: that's like $350, it's not trivial.
[1:27:06] SPEAKER: - It's not too bad though.
[1:27:08] SPEAKER: - Not too bad.
[1:27:09] SPEAKER: What these devices are doing is going into laser discs,
[1:27:12] SPEAKER: players, and VHS decks that expose this functionality
[1:27:16] SPEAKER: and tapping directly into the RF signal
[1:27:18] SPEAKER: that's coming straight off the media.
[1:27:20] SPEAKER: - Oh, off of the read head.
[1:27:21] SPEAKER: So before it goes through all the image processing.
[1:27:23] SPEAKER: - Exactly, before it touches any of the video output
[1:27:26] SPEAKER: hardware in that specific player and whatever transforms
[1:27:29] SPEAKER: and reduction in quality happen as it goes to screen.
[1:27:32] SPEAKER: - Oh, so you get the benefit
[1:27:33] SPEAKER: of the high quality analog read heads
[1:27:35] SPEAKER: and you run it through modern video processing signal?
[1:27:38] SPEAKER: - Yes, you are getting the purest possible analog signal
[1:27:41] SPEAKER: off of the given media,
[1:27:42] SPEAKER: whether it's VHS tape or laser disc or what have you.
[1:27:45] SPEAKER: So it's within some margin of error,
[1:27:48] SPEAKER: because like you said,
[1:27:48] SPEAKER: that you're still having to run it through some processing
[1:27:50] SPEAKER: and try to like massage it to look right.
[1:27:52] SPEAKER: But it's effectively the highest quality
[1:27:55] SPEAKER: you can possibly pull off of that media,
[1:27:57] SPEAKER: because it's basically exactly the information
[1:27:59] SPEAKER: stored on the disc, give or take.
[1:28:01] SPEAKER: - Oh, that's fascinating.
[1:28:02] SPEAKER: - It's awesome, it's amazing, yes.
[1:28:05] SPEAKER: So that's where people are at with that stuff.
[1:28:07] SPEAKER: And that's why I specifically mentioned
[1:28:09] SPEAKER: the thing about laser discs kind of still holding
[1:28:12] SPEAKER: some movies up from any newer formats.
[1:28:17] SPEAKER: Like that's kind of the only way you can watch stuff.
[1:28:19] SPEAKER: There are people out there you can see on Twitter,
[1:28:20] SPEAKER: like Chris Person who works with Aftermath
[1:28:23] SPEAKER: and a number of other places,
[1:28:25] SPEAKER: like he's big into the scene.
[1:28:26] SPEAKER: He's Papa Pichu, P-I-S-H-U on Twitter.
[1:28:30] SPEAKER: He tweets about this stuff all the time.
[1:28:31] SPEAKER: He actually is one of those people
[1:28:33] SPEAKER: who's like getting their hands on obscure anime
[1:28:35] SPEAKER: and stuff like that,
[1:28:36] SPEAKER: that doesn't exist outside of laser disc.
[1:28:38] SPEAKER: Or exists in very poor quality otherwise.
[1:28:41] SPEAKER: - Yeah, yeah.
[1:28:42] SPEAKER: - And is making very high quality backups
[1:28:44] SPEAKER: or captures of it to preserve for historical value.
[1:28:48] SPEAKER: - Well, it's funny, I was thinking about it
[1:28:49] SPEAKER: 'cause I've been doing work at PC World
[1:28:52] SPEAKER: a couple of days a week, the last couple of months.
[1:28:54] SPEAKER: And they used to host Mac World,
[1:28:59] SPEAKER: and also hosted PC World event keynotes and stuff
[1:29:03] SPEAKER: where things that we talked about
[1:29:05] SPEAKER: in that Pirates of Silicon Valley episode
[1:29:06] SPEAKER: a couple of weeks ago happened.
[1:29:09] SPEAKER: And when you go look at the YouTube videos
[1:29:10] SPEAKER: of those events, they're not great.
[1:29:13] SPEAKER: - Oh.
[1:29:14] SPEAKER: - I wanna find, yeah, it's fascinating.
[1:29:17] SPEAKER: - I've talked to Adam before about some of the stuff
[1:29:19] SPEAKER: they might have lurking on old tapes from Apple keynotes
[1:29:23] SPEAKER: and stuff that might be of immense historical value.
[1:29:26] SPEAKER: - iPhone keynote would be amazing to get.
[1:29:28] SPEAKER: - Yeah.
[1:29:29] SPEAKER: - Absolutely.
[1:29:30] SPEAKER: I've mentioned that specific one to him for sure.
[1:29:32] SPEAKER: But yeah, like in any way that's where the efforts
[1:29:35] SPEAKER: are at these days for kind of trying to capture
[1:29:37] SPEAKER: and preserve stuff that's locked up
[1:29:39] SPEAKER: on these old analog formats.
[1:29:41] SPEAKER: There are a couple of cheaper options
[1:29:43] SPEAKER: that are similar to this that are almost as good.
[1:29:46] SPEAKER: There's one that uses like a $30 capture card
[1:29:48] SPEAKER: off of AliExpress that's apparently like pretty close.
[1:29:52] SPEAKER: - And do you have to like take apart the VCR
[1:29:54] SPEAKER: and solder stuff in?
[1:29:55] SPEAKER: - I don't know about soldering.
[1:29:57] SPEAKER: So I've never gotten that far into looking
[1:29:59] SPEAKER: down the rabbit hole.
[1:30:00] SPEAKER: - Okay.
[1:30:01] SPEAKER: - You might be soldering stuff
[1:30:02] SPEAKER: or you might be just clamping onto things.
[1:30:03] SPEAKER: I'm not sure.
[1:30:05] SPEAKER: - I mean, my guess is you're soldering onto stuff
[1:30:06] SPEAKER: on the bottom of the board,
[1:30:07] SPEAKER: just so you have like extra leads coming off, but.
[1:30:10] SPEAKER: - Yeah, and it requires compatible players.
[1:30:13] SPEAKER: Not every player apparently makes it easy
[1:30:15] SPEAKER: or possible to do this. - That makes sense.
[1:30:16] SPEAKER: - So there's also the necessity of hunting down,
[1:30:20] SPEAKER: but apparently it's pretty easy.
[1:30:21] SPEAKER: Like you see people all the time say like,
[1:30:22] SPEAKER: "Oh, I found like one of these Panasonic Blue Line players
[1:30:25] SPEAKER: at Goodwill for $5 that is now my capture setup."
[1:30:28] SPEAKER: So they're still out there.
[1:30:29] SPEAKER: I'll mention for anybody who's listening to this,
[1:30:32] SPEAKER: who messes with this stuff, the thing, my use case,
[1:30:35] SPEAKER: the thing I've thought about doing with this
[1:30:37] SPEAKER: is we've got some old VHS home movies from the 80s
[1:30:40] SPEAKER: that were recorded on an 80s era VHS camcorder,
[1:30:43] SPEAKER: which as you can imagine are not great quality.
[1:30:45] SPEAKER: - 180 lines for a lot of those it turns out, yeah.
[1:30:48] SPEAKER: - So like my thought there is like,
[1:30:49] SPEAKER: yes, they're very low quality
[1:30:51] SPEAKER: because of the hardware of the era,
[1:30:52] SPEAKER: but still if I could lift those from the tapes
[1:30:54] SPEAKER: at the best quality possible, given the limitations,
[1:30:57] SPEAKER: is that worth it or not?
[1:30:58] SPEAKER: We got them captured and put on DVD a few years ago,
[1:31:01] SPEAKER: but I don't know that those captures were conducted
[1:31:03] SPEAKER: in the best possible way and they're MPEG-2 compressed now.
[1:31:06] SPEAKER: - Those are often like, yeah,
[1:31:09] SPEAKER: like not done at a high quality.
[1:31:11] SPEAKER: - Right, like I'm guessing that's whatever setup
[1:31:13] SPEAKER: my mom sent them to or some kind of prosumer deck
[1:31:15] SPEAKER: that was probably going out of S-video at best or something
[1:31:19] SPEAKER: into some kind of PC capture of 10 years ago plus.
[1:31:23] SPEAKER: So anyway, I'm debating like,
[1:31:25] SPEAKER: is it worth going down this rabbit hole
[1:31:26] SPEAKER: to try to get these home movies, this family stuff,
[1:31:29] SPEAKER: which is very sentimental in a higher quality?
[1:31:30] SPEAKER: I'm not sure.
[1:31:31] SPEAKER: - I mean, my general advice on that is,
[1:31:34] SPEAKER: it's better to get it while the tapes still work.
[1:31:36] SPEAKER: - Yeah, that's the other thing.
[1:31:38] SPEAKER: - Than to not, than to wait for the perfect transfer
[1:31:41] SPEAKER: and hope that you have a way to do it better
[1:31:44] SPEAKER: at some point in the future.
[1:31:44] SPEAKER: - It's not waiting for a better option.
[1:31:46] SPEAKER: It's, is it worth, is there actually even gonna be
[1:31:49] SPEAKER: a noticeable difference from the DVDs that we already have?
[1:31:52] SPEAKER: And that I can't answer.
[1:31:53] SPEAKER: That, I mean, you probably won't have the good stock music.
[1:31:56] SPEAKER: So that's it.
[1:31:57] SPEAKER: That's the tour, part one, we'll call that.
[1:32:00] SPEAKER: That's the analog edition of the history of home video.
[1:32:06] SPEAKER: I'm, the CD stuff was the big revelation for me.
[1:32:08] SPEAKER: I'd never heard of that.
[1:32:09] SPEAKER: And also I was shocked at how little the difference
[1:32:13] SPEAKER: in quality on beta and VHS was given all those beta peoples
[1:32:18] SPEAKER: yelling about how good beta was.
[1:32:20] SPEAKER: - Yes, that was revelation.
[1:32:22] SPEAKER: - Yeah, if you think beta is better,
[1:32:23] SPEAKER: please don't leave a comment, we're fine.
[1:32:27] SPEAKER: - Not a big beta resurrection scene out there
[1:32:31] SPEAKER: from what I've seen.
[1:32:32] SPEAKER: - I don't know, man.
[1:32:33] SPEAKER: People yell about anything, but you know what I do love?
[1:32:37] SPEAKER: - What's that?
[1:32:37] SPEAKER: - Is our listeners.
[1:32:39] SPEAKER: - Me too.
[1:32:39] SPEAKER: - Brad and Will Made a Tech Pod
[1:32:40] SPEAKER: is a listener supported podcast.
[1:32:42] SPEAKER: That means without listeners like you, we wouldn't be here.
[1:32:45] SPEAKER: We wouldn't be making a show, so.
[1:32:47] SPEAKER: - I love them not least of all because they keep us going.
[1:32:50] SPEAKER: - Yeah, because they, if you would like to find out
[1:32:52] SPEAKER: how you can support the show monetarily,
[1:32:54] SPEAKER: which we appreciate in these times especially,
[1:32:58] SPEAKER: you can go to patreon.com/techpod.
[1:33:00] SPEAKER: Again, it's patreon.com/techpod.
[1:33:03] SPEAKER: And where for five bucks a month,
[1:33:05] SPEAKER: you gain access to the fabulous Tech Pod Discord.
[1:33:07] SPEAKER: You get access to a wonderful community of nerds,
[1:33:09] SPEAKER: just like you, who love to talk about things like,
[1:33:12] SPEAKER: is beta better than VHS?
[1:33:13] SPEAKER: Or what the hell is this CED thing anyway?
[1:33:16] SPEAKER: I've never heard of that.
[1:33:17] SPEAKER: That seems like something Brad and Will made up
[1:33:18] SPEAKER: on this episode.
[1:33:19] SPEAKER: But no, there's two hours of Technology Connection videos
[1:33:21] SPEAKER: out on the internet.
[1:33:22] SPEAKER: You can go watch and learn more about it right now.
[1:33:25] SPEAKER: Again, it's patreon.com/techpod.
[1:33:27] SPEAKER: And while we thank all of our listeners every month
[1:33:30] SPEAKER: and all of our patrons every month,
[1:33:31] SPEAKER: we give an extra special thank you
[1:33:33] SPEAKER: to our executive producer tier patrons,
[1:33:34] SPEAKER: including Andrew Slosky,
[1:33:37] SPEAKER: Paddle Creek Games, makers of Fractured Veil,
[1:33:39] SPEAKER: Jordan Lippett, Octo Thorpe Buddy Redacted,
[1:33:43] SPEAKER: Just Wedge, Twinkle Twinkie, David Allen, James Kamik,
[1:33:46] SPEAKER: and Pantheon, makers of the HS3 high-speed 3D printer.
[1:33:50] SPEAKER: Thank you all so, so much.
[1:33:51] SPEAKER: We appreciate you.
[1:33:52] SPEAKER: Yes, we do.
[1:33:53] SPEAKER: And on that note, I think we'll sign off for the week.
[1:33:58] SPEAKER: I think we should give it a rest
[1:33:59] SPEAKER: between this week and this one and the part two though.
[1:34:02] SPEAKER: I think we should give it a minute to stew.
[1:34:04] SPEAKER: I think we should maybe consult a friend next week
[1:34:06] SPEAKER: and see if there's a fun project out there for people.
[1:34:09] SPEAKER: Oh, interesting idea.
[1:34:11] SPEAKER: I mean, who knows what we're gonna do?
[1:34:13] SPEAKER: Tune in next week and find out.
[1:34:15] SPEAKER: Thanks for listening.
[1:34:16] SPEAKER: Everybody see you then.
[1:34:16] SPEAKER: (upbeat music)
[1:34:21] SPEAKER: [BLANK_AUDIO]
