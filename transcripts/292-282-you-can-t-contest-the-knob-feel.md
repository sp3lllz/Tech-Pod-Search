---
episode: 292
title: 282: You Can't Contest the Knob Feel
date: 2025-04-13
guests: none
duration: 1:12:13
---

[00:00] SPEAKER: - Did you know you can run your own firmware on Kindles now?
[00:03] SPEAKER: - I just weirdly the other day got a YouTube recommendation
[00:07] SPEAKER: along the lines of it's time to de-Amazon your Kindle.
[00:10] SPEAKER: So I guess I did know that.
[00:12] SPEAKER: - Yeah, people were talking about it
[00:13] SPEAKER: in the Discord this morning.
[00:14] SPEAKER: And I was, when they first figured out
[00:17] SPEAKER: how to jailbreak them years and years ago,
[00:19] SPEAKER: I looked at what you could do with the jailbroken Kindle.
[00:22] SPEAKER: And it was basically like, you can put Linux on it
[00:26] SPEAKER: and you can run a Sudoku app.
[00:27] SPEAKER: And there was some, there was like a version of Snake
[00:31] SPEAKER: or something, and that was pretty much it.
[00:33] SPEAKER: - Yeah, I also have been of the mind
[00:34] SPEAKER: that it never really seemed worth it.
[00:36] SPEAKER: But when you mentioned the Snake is on there, I might-
[00:38] SPEAKER: - Well, so I was curious to see,
[00:40] SPEAKER: 'cause there's this whole, there's a whole interface
[00:42] SPEAKER: for like your DRM-free audio books and eBooks
[00:46] SPEAKER: that you buy from places now.
[00:48] SPEAKER: - Yeah, 'cause that was the big thing, you know,
[00:49] SPEAKER: the big, what do you wanna call it?
[00:51] SPEAKER: The DRM kerfuffle of a couple months ago,
[00:53] SPEAKER: the way that they changed your ability
[00:55] SPEAKER: to get your stuff off of there.
[00:56] SPEAKER: - Well, and there's tools now, kind of like Plex,
[01:00] SPEAKER: but for eBooks and books and comics in audio bookshelf.
[01:05] SPEAKER: And so I was looking at it and I was like,
[01:07] SPEAKER: oh, is this a thing, is this a thing I can do?
[01:12] SPEAKER: And then the answer turns out it's no.
[01:14] SPEAKER: - But your model is not capable?
[01:16] SPEAKER: - No, no, no, my model's capable.
[01:17] SPEAKER: There's like no interface with any kind of external,
[01:22] SPEAKER: like what I want is a thing that I can put books on my NAS
[01:25] SPEAKER: and then pull them over onto the Kindle
[01:27] SPEAKER: and all the stuff that they have are like,
[01:29] SPEAKER: yo, you can use Glibri and plug it into USB on your computer.
[01:33] SPEAKER: I'm like, no, I'm uninterested in this as a concept.
[01:37] SPEAKER: - You want to use your device to consume media
[01:38] SPEAKER: like a normal person.
[01:39] SPEAKER: - Yeah, I want something that is painless,
[01:42] SPEAKER: easy, fast, and cheap.
[01:44] SPEAKER: - And free, not free as in like,
[01:47] SPEAKER: I'm not gonna use the free as in beer thing here,
[01:49] SPEAKER: but I don't mean free as in no money,
[01:51] SPEAKER: I mean free as in like liberating, right?
[01:53] SPEAKER: - Exactly.
[01:54] SPEAKER: - You can freely be able to put documents onto your device
[01:56] SPEAKER: and consume them.
[01:57] SPEAKER: - Exactly, so anyway, so here we are.
[02:00] SPEAKER: It's a bad news on the Kindle hacking front, it seems like,
[02:05] SPEAKER: but I mean, maybe things will change, who knows?
[02:09] SPEAKER: - Well, first of all, I feel like I have got a laundry list
[02:11] SPEAKER: of like six to eight different hacking.
[02:13] SPEAKER: I use hacking in kind of not sneer quotes,
[02:16] SPEAKER: but goofy quotes here.
[02:17] SPEAKER: Like I'm not actually hacking things,
[02:18] SPEAKER: but you know what I mean?
[02:19] SPEAKER: Like I'm constantly looking at like,
[02:21] SPEAKER: did I put open WRT on my UniFi access points?
[02:25] SPEAKER: Like it's the old Linksys custom firmware disease, right?
[02:27] SPEAKER: Carried over to every device you own.
[02:29] SPEAKER: Like I'm constantly looking around at things
[02:31] SPEAKER: and thinking like, what if that RAM and open source thing
[02:34] SPEAKER: that's made by three people instead of whatever
[02:37] SPEAKER: the company put on there, but Kindle is on that list
[02:39] SPEAKER: and I have been thinking since I saw that video.
[02:41] SPEAKER: - Once I set Portainer up on my little server guy,
[02:46] SPEAKER: so that running Docker containers is like
[02:49] SPEAKER: a web-based interface instead of me having to remember
[02:51] SPEAKER: some esoteric commands that I'm never gonna remember
[02:53] SPEAKER: three months from now.
[02:54] SPEAKER: I've started making all,
[02:55] SPEAKER: I've started asking all sorts of questions like,
[02:57] SPEAKER: hey, can I run Pi-hole in a Docker on my Linux box?
[03:01] SPEAKER: And the answer is yes.
[03:02] SPEAKER: - Yes, you can.
[03:04] SPEAKER: - The real answer is probably it's better to have it
[03:06] SPEAKER: just on a dedicated machine for something
[03:08] SPEAKER: that both doles out all the IP addresses in my house.
[03:11] SPEAKER: - Okay, check this out.
[03:13] SPEAKER: - Yeah.
[03:14] SPEAKER: - What if your second Pi-hole ran in the Docker container?
[03:16] SPEAKER: - Okay, so I'm gonna go and tell you,
[03:18] SPEAKER: I did get to that point.
[03:20] SPEAKER: I was like, what if I just run the exact same configuration
[03:23] SPEAKER: Pi-hole on an x86 box in this Docker container?
[03:28] SPEAKER: And then I have redundancy.
[03:30] SPEAKER: So I have two DNS servers instead of just one.
[03:33] SPEAKER: But then I realized what would happen though.
[03:35] SPEAKER: 'Cause what would happen is I wouldn't realize
[03:37] SPEAKER: that the first DNS server has gone down.
[03:39] SPEAKER: 'Cause it doesn't like, it's like maybe once a year,
[03:42] SPEAKER: I need to reboot the thing.
[03:44] SPEAKER: And what would happen then is I wouldn't notice
[03:46] SPEAKER: that it went down until the second one went down a year in.
[03:50] SPEAKER: And so realistically, I'd always have checking the first DNS,
[03:54] SPEAKER: the DNS is down and DNS would get real slow
[03:56] SPEAKER: for inexplicable reasons.
[03:58] SPEAKER: And nobody would complain about it.
[03:59] SPEAKER: I just be like, man, the internet's really slow.
[04:00] SPEAKER: But I wouldn't look at it.
[04:02] SPEAKER: - You've uncovered a use case where redundancy
[04:04] SPEAKER: is somehow a net negative.
[04:05] SPEAKER: (upbeat music)
[04:20] SPEAKER: (upbeat music continues)
[04:34] SPEAKER: - Welcome to "Brad and Will Made a Tech Pod."
[04:36] SPEAKER: I'm Will. - I'm Brad.
[04:37] SPEAKER: - Brad, it's time.
[04:40] SPEAKER: - I'm for...
[04:42] SPEAKER: - I did a pregnant pause there, did you catch that?
[04:43] SPEAKER: - I did.
[04:44] SPEAKER: - It's time...
[04:45] SPEAKER: - The anticipation is building here.
[04:47] SPEAKER: - It's time to talk about,
[04:49] SPEAKER: I don't wanna say ill-advised purchases,
[04:52] SPEAKER: but we try not to fetishize old technology here.
[04:57] SPEAKER: - Yeah, well, maybe you do.
[04:59] SPEAKER: Or we try it unsuccessfully, perhaps.
[05:02] SPEAKER: - Like I dream of a world
[05:03] SPEAKER: where I don't fetishize old technology.
[05:05] SPEAKER: - Okay, yes, it's good to have goals.
[05:07] SPEAKER: - Yeah, and about a month ago, I failed.
[05:11] SPEAKER: We were at the electronics flea market and I bought a...
[05:14] SPEAKER: I saw my childhood TV.
[05:16] SPEAKER: We talked about this.
[05:17] SPEAKER: I have since plugged it in, hooked up to the mystery.
[05:20] SPEAKER: We're gonna talk about that today.
[05:21] SPEAKER: - Yes, we're here to talk about CRTs.
[05:23] SPEAKER: - I did a minor repair on it.
[05:25] SPEAKER: - Okay, that's awesome.
[05:28] SPEAKER: - It turns out I like the CRT a lot.
[05:30] SPEAKER: The colors are real good.
[05:31] SPEAKER: It's real bright.
[05:32] SPEAKER: And I forgot what video games used to look like.
[05:34] SPEAKER: - I wanna draw a line here.
[05:37] SPEAKER: - Yeah, hi.
[05:37] SPEAKER: - In the context of fetishizing old technology
[05:39] SPEAKER: around the things you grew up with.
[05:42] SPEAKER: I think it is perfectly fine to fetishize the things
[05:45] SPEAKER: that were formative for you.
[05:47] SPEAKER: And maybe not CRTs writ large
[05:49] SPEAKER: or you don't need to own every tape deck ever made,
[05:51] SPEAKER: but you might wanna own the tape deck
[05:53] SPEAKER: that you had as a child, right?
[05:54] SPEAKER: Which is exactly what you've done here.
[05:56] SPEAKER: I've gone the other direction, which we'll also get to.
[05:58] SPEAKER: But I think as a subcategory of being into old stuff,
[06:02] SPEAKER: being into the old stuff that was yours
[06:04] SPEAKER: is perfectly fine and even good.
[06:07] SPEAKER: - So you're saying if I go to eBay right now
[06:09] SPEAKER: and I search for 1981 Kenner at at Walker,
[06:15] SPEAKER: and I look at this and I'm like,
[06:16] SPEAKER: "Oh, this is only, the yellow ones that are classic
[06:19] SPEAKER: are only 200 bucks."
[06:20] SPEAKER: - Acceptable use of funds.
[06:22] SPEAKER: - Oh, I'm gonna have to talk to my wife about this.
[06:24] SPEAKER: I bet she has different feelings.
[06:25] SPEAKER: - Possibly, how big are those things?
[06:28] SPEAKER: - Like two feet tall, they're not that big.
[06:30] SPEAKER: - That's decent, I had a friend
[06:32] SPEAKER: that had the Millennium Falcon and that thing was large.
[06:35] SPEAKER: - I had, so my, the Star Wars toys that I like,
[06:38] SPEAKER: I had a bunch of, I had a TIE fighter and an X-wing
[06:40] SPEAKER: and an A-wing and all that, B-wing,
[06:42] SPEAKER: all these spaceships, right, the fighters.
[06:45] SPEAKER: But then the big one that I had was the Millennium Falcon
[06:49] SPEAKER: and I wanted desperately to get an AT-AT.
[06:52] SPEAKER: I think I've told this before,
[06:53] SPEAKER: but my parents bought me the Ewok Village instead
[06:55] SPEAKER: 'cause they thought it was cooler.
[06:57] SPEAKER: They were like, "Look, it has an elevator,
[06:59] SPEAKER: there's an escape hatch."
[07:00] SPEAKER: That AT-AT, all it does is stand there,
[07:02] SPEAKER: it's like the AT-AT is the coolest thing
[07:03] SPEAKER: that Star Wars has ever made, mom, dad.
[07:06] SPEAKER: - Grit your teeth and say thank you.
[07:07] SPEAKER: - I said thank you and I played with the,
[07:10] SPEAKER: look, I'll tell you, the Transformers
[07:12] SPEAKER: had some real adventures in the Ewok Village as a child.
[07:14] SPEAKER: Like Transformers, Star Wars, everybody, big fights there.
[07:18] SPEAKER: But I always wanted that Kenner AT-AT.
[07:22] SPEAKER: Okay, another hard swerve here,
[07:24] SPEAKER: but these AT-ATs are all yellow, just like SNESs get.
[07:28] SPEAKER: - Oh, that's- - Yeah.
[07:30] SPEAKER: - I've been sifting, we'll get into this,
[07:31] SPEAKER: I've been sifting through old consoles all week
[07:33] SPEAKER: and that yellow plastic is a particular form of ick for me.
[07:38] SPEAKER: It's like it triggers something,
[07:39] SPEAKER: something stomach-turning when I see it.
[07:41] SPEAKER: - Well, Wes Fanlon, back in the tested days,
[07:44] SPEAKER: did a thing about how to fix this.
[07:46] SPEAKER: It has to do with de-brominating or something.
[07:49] SPEAKER: - Yeah, I think, isn't the process colloquially
[07:51] SPEAKER: called retrobriting, I think, if you want to look it up.
[07:53] SPEAKER: Although I think that's like spelled with zero
[07:55] SPEAKER: and B-R-I-T-E, if you're Googling this,
[07:57] SPEAKER: it's not how you would normally expect it to be spelled.
[08:00] SPEAKER: It'll only look retrobrite. - Perfect.
[08:03] SPEAKER: But it also tends to make the plastic a little more brittle,
[08:07] SPEAKER: which probably doesn't matter for your SNES,
[08:09] SPEAKER: but on something as thin as these old Kenner toys, it might.
[08:13] SPEAKER: - Yeah, my Super Nintendo's got it really bad.
[08:15] SPEAKER: The front of my Dreamcast, not the back for whatever reason,
[08:18] SPEAKER: which normally the entire panel,
[08:20] SPEAKER: or the entire piece of plastic kind of yellows consistently.
[08:24] SPEAKER: But on my Dreamcast, the entire top,
[08:26] SPEAKER: which again is one piece of plastic,
[08:28] SPEAKER: is like on the front is yellowed.
[08:30] SPEAKER: It might've been like a sun exposure thing.
[08:32] SPEAKER: - Yeah, maybe, maybe, that's weird.
[08:35] SPEAKER: But we're not here to talk about plastic
[08:36] SPEAKER: and yellowing and all that stuff today.
[08:38] SPEAKER: Although we are gonna talk about old stuff.
[08:39] SPEAKER: We're gonna talk about CRTs, cathode ray tubes.
[08:41] SPEAKER: - Yeah, not broadly.
[08:43] SPEAKER: This is not gonna be like your one-stop shop
[08:45] SPEAKER: for all things CRT.
[08:46] SPEAKER: I think this is gonna be much more hands-on.
[08:48] SPEAKER: Like you and I both obtained CRTs recently
[08:50] SPEAKER: and have been messing with them.
[08:52] SPEAKER: Although CRT is from very different eras.
[08:54] SPEAKER: So this is more of like a,
[08:55] SPEAKER: I think that this will be more of a hands-on report.
[08:57] SPEAKER: Just kind of like, here's all the goofy stuff
[08:59] SPEAKER: we've had to get into to work with these.
[09:01] SPEAKER: - Yeah, a trip report.
[09:02] SPEAKER: So I was at the flea market, I bought this CRT.
[09:05] SPEAKER: It's the one, it's literally the same TV I had as a kid.
[09:09] SPEAKER: Right, like the one that my Nintendo and my TI-99-4A
[09:13] SPEAKER: and later my SNES were all hooked up to.
[09:15] SPEAKER: I got a different TV when I went to college.
[09:17] SPEAKER: I got like a 19 inch Sharp that's in deep storage
[09:21] SPEAKER: in the city that I kind of want to go dig out now,
[09:26] SPEAKER: actually, after this whole experience.
[09:28] SPEAKER: - Wait, you have a storage unit here?
[09:30] SPEAKER: - Yeah, I have a storage unit.
[09:31] SPEAKER: - Really?
[09:32] SPEAKER: - Well, I lived in a 400 square foot apartment
[09:34] SPEAKER: when I first moved here.
[09:34] SPEAKER: So I've had a storage unit for 20 years now,
[09:37] SPEAKER: which I don't, let's not talk about that too much.
[09:39] SPEAKER: - How often do you visit your storage unit?
[09:41] SPEAKER: - Twice a year.
[09:42] SPEAKER: - Really?
[09:42] SPEAKER: Just to check in? - Yeah, probably.
[09:43] SPEAKER: - Wait, just keep an eye on things or?
[09:45] SPEAKER: - So for a long time, we kept like Christmas decorations
[09:47] SPEAKER: and stuff there.
[09:49] SPEAKER: And then not so much that, but of late,
[09:52] SPEAKER: it's been going to, like we're trying to clear out
[09:55] SPEAKER: the one in the city, honestly,
[09:56] SPEAKER: because it's a pain to get to, it's pretty small.
[09:59] SPEAKER: It's in an ancient building.
[10:01] SPEAKER: And like, I'd rather have one that's closer to the house
[10:05] SPEAKER: that I don't have to drive for 30 minutes to get to.
[10:08] SPEAKER: So we've been gradually emptying it out is the kind of TLDR.
[10:12] SPEAKER: But it's mostly stuff that was like when I moved
[10:15] SPEAKER: from a four bedroom house into a 400 square foot apartment,
[10:17] SPEAKER: didn't fit anymore, which is an incredibly stupid thing
[10:21] SPEAKER: to store for an extended period of time.
[10:23] SPEAKER: So anyway, we don't need to talk about that too, too much.
[10:27] SPEAKER: But what I do want to, so the TV is a GE,
[10:29] SPEAKER: it's an 11 inch GE RF only set,
[10:32] SPEAKER: which means it does not have an RCA plug
[10:35] SPEAKER: or even a coaxial plug.
[10:37] SPEAKER: It has four screws on the back,
[10:39] SPEAKER: two leads for VHF and two leads for UHF.
[10:42] SPEAKER: - Sorry, can I stop you and have you read the model number?
[10:45] SPEAKER: - Yeah, you want the model number?
[10:45] SPEAKER: It's the General Electric 10, alpha beta,
[10:49] SPEAKER: 3406, whiskey, foxtrot 02.
[10:53] SPEAKER: - Rolls off the tongue.
[10:54] SPEAKER: - Yeah, let me tell you, the nice thing is, very searchable.
[10:58] SPEAKER: There was one page on the internet with information about it
[11:01] SPEAKER: and it had no, nothing of value.
[11:05] SPEAKER: The GE page recognized it as a GE part number,
[11:08] SPEAKER: like the GE part number lookup recognized it
[11:11] SPEAKER: as a GE serial number or model number format,
[11:14] SPEAKER: but didn't have any information about it.
[11:15] SPEAKER: 'Cause it's from like 1984, '85.
[11:17] SPEAKER: - Oh, was it that recent?
[11:18] SPEAKER: I was thinking like mid '70s or something.
[11:21] SPEAKER: - No, so I think, so I could for $22
[11:25] SPEAKER: buy a photo fact original manual,
[11:30] SPEAKER: which contains schematics, voltages, waveforms,
[11:33] SPEAKER: component location guides, parts list,
[11:35] SPEAKER: and adjustments covering this particular model of TV,
[11:39] SPEAKER: but I didn't want to pay $22 for that.
[11:41] SPEAKER: - Kind of pricey for a manual.
[11:43] SPEAKER: It really is crazy though.
[11:44] SPEAKER: Like this is one of those rare Google searches
[11:45] SPEAKER: where you put that, like you said,
[11:47] SPEAKER: you put that number into Google,
[11:49] SPEAKER: four results come back, like literally four pages
[11:52] SPEAKER: and that's it on the entirety of Google.
[11:55] SPEAKER: - Yeah, it's, well, I mean,
[11:57] SPEAKER: it is a random series of letters and numbers,
[11:59] SPEAKER: but yeah, so it's an 11 inch TV.
[12:02] SPEAKER: It's got real good clicky volume knob that turns it on.
[12:05] SPEAKER: It's got a VHF and UHF knob, but it's got one of those,
[12:09] SPEAKER: I don't know, I had forgotten this,
[12:11] SPEAKER: but it has a two stage knob.
[12:12] SPEAKER: So it has one that is like a big chunky knob
[12:15] SPEAKER: that clonks and goes from channel to channel.
[12:18] SPEAKER: So for like from U to two to three to four
[12:21] SPEAKER: up to 13 or whatever.
[12:22] SPEAKER: And then inside that knob, there's a little dial
[12:25] SPEAKER: that you can use to like fine tune the tuning
[12:28] SPEAKER: to get it on exactly the frequency they want.
[12:33] SPEAKER: So you get a real nice clean picture
[12:35] SPEAKER: if there was any analog TV anymore.
[12:37] SPEAKER: - Yeah, we had a TV with that exact same knob
[12:38] SPEAKER: and it may have also been a GE,
[12:40] SPEAKER: but I don't know how common that was generally
[12:42] SPEAKER: for analog TVs of that era, that specific,
[12:44] SPEAKER: that little kind of knob within a knob for fine tuning.
[12:47] SPEAKER: - This is the only TV we had that had that,
[12:49] SPEAKER: well, actually, you know what, that's not true.
[12:51] SPEAKER: 'Cause I think our Philco set in the living room,
[12:53] SPEAKER: the 19 inch, that was the family TV had a big chunky knob.
[12:57] SPEAKER: And then I think you had another little dial
[12:59] SPEAKER: on the outside of the knob that you could turn
[13:01] SPEAKER: to tune it in.
[13:02] SPEAKER: Maybe this is what all pre-digital click TVs had.
[13:06] SPEAKER: - Maybe, I'm sorry, Philco still to me,
[13:09] SPEAKER: just sounds like a fake company
[13:10] SPEAKER: from Ren and Stimpy or something.
[13:12] SPEAKER: - Isn't Philco Phillips company?
[13:14] SPEAKER: - Is it?
[13:16] SPEAKER: - Philco is an American electronics manufacturer
[13:18] SPEAKER: headquartered in, oh, it's short
[13:19] SPEAKER: for the Philadelphia Battery Company.
[13:21] SPEAKER: - Okay, sure.
[13:23] SPEAKER: - A pioneer in battery radio and television production.
[13:26] SPEAKER: It was purchased by Ford, renamed Philco Ford,
[13:29] SPEAKER: sold to GTE in 1974 and was purchased by Phillips in 1981,
[13:33] SPEAKER: which became a subsidiary of the Dutch company Phillips
[13:36] SPEAKER: in 1987.
[13:38] SPEAKER: In North America, the Philco brand is owned by Phillips
[13:40] SPEAKER: and other markets, it's owned by Electrolux.
[13:44] SPEAKER: - Electrolux also sounds like a fake company name.
[13:47] SPEAKER: - Electrolux is one of the great,
[13:49] SPEAKER: that was the thing that happened in the '60s, right?
[13:51] SPEAKER: They started jamming, if you had standard oil company,
[13:56] SPEAKER: was your name, you'd rename it to Esso,
[13:57] SPEAKER: 'cause it was short for, but you spell it out.
[14:01] SPEAKER: Electrolux is one of those, I believe,
[14:05] SPEAKER: it's a Swedish company originally.
[14:07] SPEAKER: - Do they make vacuums?
[14:08] SPEAKER: I wanna say we might've had an Electrolux vacuum
[14:09] SPEAKER: when I was a kid.
[14:11] SPEAKER: - Electrolux was famous for bag vacuums specifically.
[14:14] SPEAKER: - Sure.
[14:16] SPEAKER: Does the TV also have the combination power on
[14:20] SPEAKER: and volume knob?
[14:21] SPEAKER: - Yeah, it makes the best click.
[14:23] SPEAKER: - Yes, like it's a little knob
[14:25] SPEAKER: and it's got an extremely meaty click
[14:27] SPEAKER: when you turn it to the right to turn the TV on,
[14:28] SPEAKER: but then you keep turning it to turn the volume up.
[14:30] SPEAKER: - In fact, I'm actually gonna drag it in here
[14:32] SPEAKER: after we record and I'll record some samples
[14:35] SPEAKER: of the clocks and the clicks so that I can put them in,
[14:38] SPEAKER: 'cause it's unlike anything.
[14:39] SPEAKER: I'd forgotten, like I think I talked about this before
[14:43] SPEAKER: on either here or one of the other podcasts,
[14:45] SPEAKER: when my daughter was exposed to the knob for the first time,
[14:49] SPEAKER: she was like, this is the best thing I've ever seen in my,
[14:51] SPEAKER: like, this is the best feeling control
[14:53] SPEAKER: I've ever touched in my life.
[14:54] SPEAKER: It's got very good knob feel, although maybe I shouldn't.
[14:57] SPEAKER: - Look, you can't contest the knob feel, Brad.
[15:01] SPEAKER: - No, I suppose not.
[15:02] SPEAKER: I'm gonna put a call out right here.
[15:04] SPEAKER: This is where I'm going to put the click sounds
[15:05] SPEAKER: that you send me, just for an easy venue in this edit.
[15:24] SPEAKER: - Behold the glory of the clicks.
[15:27] SPEAKER: - Yeah, right?
[15:27] SPEAKER: It's like, and I'll be like, hey, it's a click
[15:30] SPEAKER: and then it's a kachunk and let you know which one's which.
[15:33] SPEAKER: The UHF knob also makes a good turn.
[15:35] SPEAKER: No reason to use any of that anymore,
[15:36] SPEAKER: 'cause it's all cell phone.
[15:37] SPEAKER: It's all 5G now or 4G, LTE, whatever.
[15:40] SPEAKER: - I think the inputs on this thing
[15:42] SPEAKER: are the interesting part to me or the lack thereof,
[15:44] SPEAKER: 'cause I don't think I remember ever having a TV
[15:47] SPEAKER: that didn't at least have a coaxial input for RF on it.
[15:51] SPEAKER: So what does this have exactly?
[15:52] SPEAKER: - This has two screws for UHF and two screws for VHF.
[15:57] SPEAKER: So in order to convert the coaxial,
[15:59] SPEAKER: you have to have a transformer.
[16:01] SPEAKER: And that transformer is a 75 ohm to 300 ohm adapter
[16:05] SPEAKER: that converts the coaxial to the two U-shaped hooks
[16:12] SPEAKER: that go into those screws.
[16:16] SPEAKER: And I just took, normally you'd put those on
[16:18] SPEAKER: in addition to the antenna in the old days,
[16:22] SPEAKER: but I just took the antenna off 'cause there's no signal.
[16:25] SPEAKER: So it doesn't matter.
[16:26] SPEAKER: We're channel three only here, baby.
[16:28] SPEAKER: - And when you say screws,
[16:29] SPEAKER: I mean like these are literally screws
[16:30] SPEAKER: that you can screw in and out on the set.
[16:32] SPEAKER: Like you're just kind of-
[16:33] SPEAKER: - They are standard flat screws
[16:35] SPEAKER: with a little square metal pad underneath
[16:38] SPEAKER: that has a connection.
[16:39] SPEAKER: I'll take a picture.
[16:40] SPEAKER: You can use this for show art if you want.
[16:42] SPEAKER: - And you just insert the wire and almost like,
[16:45] SPEAKER: I mean, there's a similar like screw in terminal
[16:47] SPEAKER: on the back of a lot of like AV receivers
[16:49] SPEAKER: for speaker wire, right?
[16:50] SPEAKER: Like same kind of deal.
[16:52] SPEAKER: - No, those have a specific name.
[16:56] SPEAKER: This is literally just a flat screw
[16:59] SPEAKER: with a metal pad underneath it.
[17:01] SPEAKER: And you want to mash the U-shaped connector
[17:03] SPEAKER: on this transformer into that.
[17:05] SPEAKER: So then, because I have to be able to get the analog out
[17:10] SPEAKER: from the mister, we'll talk about that in a minute,
[17:14] SPEAKER: but the analog out from the mister, I'm using RCA
[17:17] SPEAKER: just because it's the easiest thing I can get in.
[17:20] SPEAKER: And to convert the RCA into the RF signal
[17:23] SPEAKER: that this TV needs to generate picture,
[17:26] SPEAKER: I'm using an old VCR.
[17:27] SPEAKER: - Of course, the classic.
[17:29] SPEAKER: - Yeah.
[17:29] SPEAKER: - It's the classic maneuver.
[17:30] SPEAKER: It's just a shove of an old VCR in the chain.
[17:32] SPEAKER: - Yep, but to hit that TV VCR button, it all works.
[17:35] SPEAKER: And it's funny because my kid's been playing games on this
[17:40] SPEAKER: and I don't think she still knows how to turn it on
[17:42] SPEAKER: because it's like, first you got to turn on the TV,
[17:44] SPEAKER: you got to make sure it's on channel three,
[17:45] SPEAKER: then you got to turn on the VCR,
[17:47] SPEAKER: make sure it's on TV/VCR.
[17:49] SPEAKER: Make sure the channel on the VCR is set to AV
[17:53] SPEAKER: because the AV comes in the RCA ports.
[17:55] SPEAKER: And then you got to turn on the mister and navigate
[17:58] SPEAKER: with all the weird mister controls to get into the thing.
[18:01] SPEAKER: - Most of that sounds doable for a kid.
[18:02] SPEAKER: I mean, even turning the TV on like the knob stuff
[18:04] SPEAKER: is tactile and you can figure that out.
[18:06] SPEAKER: I bet it's the channel requirements
[18:07] SPEAKER: that are what would throw a child
[18:09] SPEAKER: who was born in the 21st century.
[18:11] SPEAKER: Like it's like, who today has experience of TVs
[18:14] SPEAKER: needing to be on the right channel for signals to work
[18:17] SPEAKER: or you know what I mean?
[18:18] SPEAKER: - Yeah, now when you turn on,
[18:19] SPEAKER: like when you put your switch into the dock
[18:21] SPEAKER: and hit the button, it just, everything gets set up for you.
[18:24] SPEAKER: You don't need a harmony remote now.
[18:25] SPEAKER: You know, it just, it just works.
[18:28] SPEAKER: Well, and also like, I think I've done a bad
[18:31] SPEAKER: with my mister configuration
[18:33] SPEAKER: in terms of how I opened the mister menus
[18:36] SPEAKER: using the game pads.
[18:38] SPEAKER: 'Cause I hit like up and start on the game pad
[18:41] SPEAKER: in order to open the mister menu.
[18:43] SPEAKER: I don't remember where I set that at this point.
[18:46] SPEAKER: - Oh, that is, that's rough.
[18:47] SPEAKER: Yeah, you can put that just on a single button press
[18:50] SPEAKER: if you have enough buttons on your controller.
[18:52] SPEAKER: - So I don't have enough buttons on my controller
[18:53] SPEAKER: is the problem.
[18:54] SPEAKER: - Yeah.
[18:55] SPEAKER: - Yeah, so it has to be a cord.
[18:56] SPEAKER: - That's kind of the kind of the mister,
[18:58] SPEAKER: I guess the mister control recommendation
[19:00] SPEAKER: I've always found is like, you kind of always want like
[19:02] SPEAKER: nice controller plus one in terms of number of buttons.
[19:05] SPEAKER: Like you need all the buttons you need for the games
[19:07] SPEAKER: plus at least one or two extras for menu type stuff.
[19:10] SPEAKER: - Well, we're mostly playing SNES and NES stuff right now.
[19:13] SPEAKER: So it's all like, I'm using those 8BitDo SN30
[19:17] SPEAKER: like the ones that don't have the analog sticks.
[19:19] SPEAKER: It's just like a SNES controller shaped game pad.
[19:22] SPEAKER: - Yeah, that does put you at kind of a disadvantage.
[19:23] SPEAKER: I use a, I use a DualShock 4 mainly for mine,
[19:26] SPEAKER: which has the like the little PS,
[19:28] SPEAKER: little PlayStation button is my menu button
[19:30] SPEAKER: 'cause it's an extra, works well.
[19:32] SPEAKER: - That makes sense.
[19:33] SPEAKER: So yeah, anyway, so that's that.
[19:36] SPEAKER: I ended up upgrading the mister in order to get this to work
[19:38] SPEAKER: 'cause I had a digital output on it before
[19:41] SPEAKER: and I didn't want to do,
[19:43] SPEAKER: I didn't want to add the latency of an HDMI to analog.
[19:47] SPEAKER: Like I don't have a retro tinker,
[19:49] SPEAKER: one of those, you know, one of the fancy DHDM-ers
[19:53] SPEAKER: and I didn't want to buy a cheap one
[19:55] SPEAKER: 'cause they had latency
[19:56] SPEAKER: and the cables I needed to do it the cheap way
[19:59] SPEAKER: were $8 less than just replacing the IO board on my mister
[20:04] SPEAKER: with one of the fancy new ones.
[20:06] SPEAKER: I don't know if you've seen it,
[20:08] SPEAKER: but Mr. Addons has added a two new IO board options.
[20:14] SPEAKER: There's an analog one and a digital one.
[20:16] SPEAKER: The digital one also does analog,
[20:19] SPEAKER: which is important to note.
[20:20] SPEAKER: The analog one is really cool, especially for you,
[20:23] SPEAKER: because you can hook it,
[20:24] SPEAKER: you can have the analog going simultaneously
[20:27] SPEAKER: with the digital.
[20:28] SPEAKER: So like if you wanted to stream an old game,
[20:29] SPEAKER: you could put HDMI out into your capture card,
[20:32] SPEAKER: but play the game on your TV, which is like,
[20:35] SPEAKER: I remember when Dan Reichert tried to do that
[20:37] SPEAKER: with Punch Out at Giant Bomb 10 years ago
[20:40] SPEAKER: and poor Jason had to do like some heavy duty
[20:44] SPEAKER: video engineering work to get that to happen.
[20:46] SPEAKER: - We ran into the same thing
[20:47] SPEAKER: when I was streaming Super Mario Brothers 2,
[20:49] SPEAKER: the Japanese version,
[20:50] SPEAKER: like the original brutally punishing one.
[20:53] SPEAKER: - The Lost Levels, you mean?
[20:54] SPEAKER: - Yes, the Lost Levels.
[20:55] SPEAKER: We had to pull that out of the studio,
[20:57] SPEAKER: big matrix switcher chain
[20:59] SPEAKER: 'cause I was adding enough latency
[21:00] SPEAKER: that I was just like missing very obvious jumps
[21:03] SPEAKER: in that game and stuff,
[21:03] SPEAKER: 'cause those games have zero tolerance for latency.
[21:07] SPEAKER: - As an aside on that, there's a really good,
[21:10] SPEAKER: I think the Celeste developers did a,
[21:13] SPEAKER: hey, here's why some platforms feel hard
[21:16] SPEAKER: and some feel easy,
[21:17] SPEAKER: and they showed all the ways
[21:18] SPEAKER: that like modern platformers cheat
[21:19] SPEAKER: to make sure that you land the jumps
[21:21] SPEAKER: that you should by rights miss.
[21:23] SPEAKER: - Yeah, that's like a,
[21:24] SPEAKER: if it's the same Twitter thread
[21:26] SPEAKER: I'm thinking of that you're talking about,
[21:27] SPEAKER: that's like a canonical thread of game development Twitter,
[21:30] SPEAKER: where they went through like a bunch of like,
[21:33] SPEAKER: there needs to be a term for this
[21:34] SPEAKER: 'cause games have been doing this
[21:35] SPEAKER: since time immemorial, right?
[21:36] SPEAKER: But the little like invisible sort of like usability tweaks,
[21:40] SPEAKER: I guess I would say,
[21:41] SPEAKER: or like fudging things, like you said,
[21:42] SPEAKER: it was like, oh, you know,
[21:43] SPEAKER: if you're within six pixels of making a jump,
[21:45] SPEAKER: we just have you make the jump,
[21:46] SPEAKER: even though you technically would have missed it by rules.
[21:50] SPEAKER: - Yeah, and when you play,
[21:51] SPEAKER: that's the big thing for her.
[21:52] SPEAKER: She's been playing Super Mario Brothers.
[21:54] SPEAKER: It doesn't fudge jumps.
[21:57] SPEAKER: - Only if you miss, you just straighten the hole.
[21:59] SPEAKER: - NES games definitely were by the book.
[22:02] SPEAKER: - Yeah.
[22:03] SPEAKER: - Yeah, I did look at the,
[22:04] SPEAKER: those Mr. Atons boards that he has come out with actually,
[22:08] SPEAKER: for reasons I'll get into,
[22:09] SPEAKER: but the IO direct board is the one you're talking about.
[22:11] SPEAKER: That's like, it's like a digital IO board,
[22:13] SPEAKER: but it also can do analog out
[22:15] SPEAKER: because it uses a little bridge,
[22:16] SPEAKER: like literally uses, I guess that's the one you got, right?
[22:19] SPEAKER: It's the uses a little HDMI bridge
[22:21] SPEAKER: from the HDMI out on the Mr. to an HDMI in on this thing,
[22:25] SPEAKER: and then it converts it to the Saturn plug.
[22:28] SPEAKER: - So that's exactly it.
[22:29] SPEAKER: Yeah, it uses the Saturn 10 pin mini din,
[22:31] SPEAKER: which I believe we rated as a D in our rating of connectors,
[22:35] SPEAKER: but it's, and you can get a bunch of different tails for it.
[22:38] SPEAKER: I just bought the,
[22:39] SPEAKER: like they sell one that has like VGA
[22:41] SPEAKER: and component and the whole deal.
[22:45] SPEAKER: I just bought the $10 RCA only one
[22:49] SPEAKER: 'cause that's what I had the option for.
[22:51] SPEAKER: - Yeah, I priced out this whole setup too.
[22:53] SPEAKER: I thought about, I ended up going a much cheaper route
[22:56] SPEAKER: 'cause I turned out to have basically 90%
[22:59] SPEAKER: of what I needed already.
[23:00] SPEAKER: But yeah, I was looking at like a,
[23:02] SPEAKER: it's like 50 bucks for that board.
[23:03] SPEAKER: The Saturn plug to every connector
[23:06] SPEAKER: you would ever need the cable is like 35 bucks.
[23:09] SPEAKER: - 35 bucks, yeah.
[23:09] SPEAKER: - Like need a new power supply to run the whole thing on.
[23:12] SPEAKER: So it was gonna be like a hundred bucks,
[23:13] SPEAKER: which is like, nah, not nothing.
[23:15] SPEAKER: - So I'm just running it on a normal USB.
[23:18] SPEAKER: I have a 25 watt Anker power brick.
[23:23] SPEAKER: That's plugged into it, it's running fine.
[23:27] SPEAKER: But yeah, so I ended up going to the digital one also
[23:28] SPEAKER: because it lets you keep both memory sticks in.
[23:31] SPEAKER: I ended up through,
[23:33] SPEAKER: because when we did the original Mr. episode,
[23:36] SPEAKER: I bought my Mr. card from a guy in Portugal
[23:40] SPEAKER: who had a really hard time shipping.
[23:42] SPEAKER: And the shipping during the pandemic was slow.
[23:45] SPEAKER: So I'd given up on it.
[23:46] SPEAKER: I just ordered a new memory stick.
[23:48] SPEAKER: And then like two days after the new one arrived,
[23:49] SPEAKER: the first one finally got here.
[23:51] SPEAKER: - I remember the saga.
[23:52] SPEAKER: I too am an owner of Portuguese Ram.
[23:54] SPEAKER: - Yeah.
[23:55] SPEAKER: - I think that's ultimate Mr. is the vendor in Portugal.
[23:58] SPEAKER: - I think so, yeah.
[23:59] SPEAKER: - I found his stuff to be quite good.
[24:00] SPEAKER: - But the upshot was I ended up with two Ram sticks.
[24:02] SPEAKER: And when we got to cores that could use two Ram sticks,
[24:05] SPEAKER: I was good to go.
[24:06] SPEAKER: So I just jammed them in there.
[24:08] SPEAKER: And I decided like the ability to run analog
[24:11] SPEAKER: and the main difference that I could tell on these
[24:14] SPEAKER: was that on the analog board,
[24:15] SPEAKER: you can only run one memory stick,
[24:17] SPEAKER: but you can simultaneously pipe video out
[24:20] SPEAKER: the analog outputs and HDMI.
[24:22] SPEAKER: - That's correct.
[24:23] SPEAKER: - Which is really cool for people like you
[24:28] SPEAKER: that stream old games, less useful for me,
[24:32] SPEAKER: who's mostly just gonna sit in front of a TV
[24:34] SPEAKER: and play old games.
[24:35] SPEAKER: - To be clear, the ability to get analog
[24:37] SPEAKER: and digital video out at the same time
[24:39] SPEAKER: is way more useful day to day than two Ram sticks.
[24:43] SPEAKER: - Yeah.
[24:43] SPEAKER: - Like for people who don't know,
[24:46] SPEAKER: like the most you're getting out of dual Ram at this point
[24:48] SPEAKER: is like slightly higher accuracy in a couple of cores.
[24:51] SPEAKER: - Actually, I think the Saturn core still does work.
[24:55] SPEAKER: They're fairly substantially better with two.
[24:57] SPEAKER: - I think the 32X core, I haven't looked in a while,
[25:01] SPEAKER: but last time I looked,
[25:02] SPEAKER: the 32X core was one of those ones
[25:04] SPEAKER: that was weirdly complicated and needed more Ram too,
[25:06] SPEAKER: because of the way they composite stuff
[25:09] SPEAKER: between the Saturn and the 32X bits.
[25:12] SPEAKER: - Yeah, we should say there have been some arcade cores
[25:14] SPEAKER: and I believe the Jaguar core that is forthcoming
[25:17] SPEAKER: where they are talking like it's going to require two Ram.
[25:20] SPEAKER: - Why does the Jaguar core require two Ram sticks?
[25:23] SPEAKER: - Look, man, it's the only 64-bit game in town
[25:26] SPEAKER: at the time, right?
[25:28] SPEAKER: - God, that thing is so, okay.
[25:29] SPEAKER: Well, anyway, we don't have to get into that, but yeah.
[25:31] SPEAKER: - The extra Ram requirement is just a latency thing.
[25:34] SPEAKER: It's just that they need more memory bandwidth
[25:36] SPEAKER: to work with than one stick can provide.
[25:38] SPEAKER: So maybe the Jaguar was doing some, who knows?
[25:42] SPEAKER: - Yeah, it had some really fast SD Ram.
[25:45] SPEAKER: So yeah, so a couple of things that I had
[25:47] SPEAKER: while I was going.
[25:48] SPEAKER: One is that I love that they shipped the service manual
[25:51] SPEAKER: on this TV.
[25:52] SPEAKER: It's just, it's like, it's in a little plastic cubby
[25:54] SPEAKER: that's built into the frame of the TV on the back.
[25:58] SPEAKER: It has a note that says, "This is the service manual.
[26:00] SPEAKER: It's only accessible for inside the case.
[26:02] SPEAKER: Do not open if you're an end user."
[26:04] SPEAKER: - What?
[26:05] SPEAKER: - Yeah.
[26:06] SPEAKER: - Wait, so can you see it in there or like?
[26:08] SPEAKER: - Yes, you can see it,
[26:09] SPEAKER: but the hole is too small to pull it out.
[26:11] SPEAKER: - So what, is there some specialized tool
[26:13] SPEAKER: you need to get it open?
[26:14] SPEAKER: - Well, no, you just unscrew it.
[26:15] SPEAKER: But like, people knew not to unscrew TVs
[26:18] SPEAKER: 'cause there's shit in there that would kill you.
[26:19] SPEAKER: - Oh, okay, this was an honor system thing?
[26:22] SPEAKER: - Yeah, this is a straight up,
[26:23] SPEAKER: hey, the repair tech isn't gonna have the manual
[26:25] SPEAKER: for every TV.
[26:26] SPEAKER: So we're just chipping our TV with the manual built in.
[26:29] SPEAKER: - That's smart.
[26:30] SPEAKER: - It's like, it's really clever.
[26:33] SPEAKER: And the fact that it's there in a window
[26:34] SPEAKER: that you can see it says,
[26:35] SPEAKER: hey, you know, if I'm the repair tech,
[26:37] SPEAKER: I know what to do without having to like phase one,
[26:40] SPEAKER: open the back of this thing.
[26:41] SPEAKER: - Right, and it actually was useful in a world
[26:43] SPEAKER: where independent third-party TV repair actually existed
[26:46] SPEAKER: and that isn't so much a thing anymore.
[26:49] SPEAKER: - And you couldn't just type 100-AB-3406-WF02 into Google
[26:54] SPEAKER: and get a $22 manual for the TV,
[26:56] SPEAKER: which just to be clear is half of what I paid for the TV.
[26:58] SPEAKER: - Yeah, but you're just reminding me though
[27:00] SPEAKER: of driving around town as a kid in the '80s
[27:02] SPEAKER: and just seeing like TV repair shops all over the place
[27:04] SPEAKER: 'cause that used to be a thing.
[27:06] SPEAKER: - Yeah, the appliance repair guy would come out.
[27:09] SPEAKER: Now the appliance repair guy comes out
[27:10] SPEAKER: and he charges you 500 bucks.
[27:12] SPEAKER: He looks at the dishwasher.
[27:12] SPEAKER: He's like, yeah, you should just replace that dishwasher.
[27:15] SPEAKER: Like, thank you for the five.
[27:16] SPEAKER: That was an incredible use of my money and time.
[27:18] SPEAKER: Thank you.
[27:19] SPEAKER: - At least seems to be the universal advice these days
[27:21] SPEAKER: is just buy a new one.
[27:22] SPEAKER: - Well, anyway, so the picture was a little jumpy though,
[27:27] SPEAKER: out of the box.
[27:28] SPEAKER: So I talked to a friend of the show, Steve Lynn,
[27:30] SPEAKER: and was like, hey, this feels like I should just take
[27:33] SPEAKER: the knob off and blast some contact cleaner situation.
[27:36] SPEAKER: And he's like, yeah, that's exactly what I would do first.
[27:38] SPEAKER: He's like, if you have to replace the knob switch,
[27:42] SPEAKER: the switch inside the knob, it's gonna be complicated
[27:45] SPEAKER: and a pain in the butt.
[27:47] SPEAKER: But usually contact cleaner just does this.
[27:49] SPEAKER: And so I took it off, got a can of contact cleaner.
[27:52] SPEAKER: I blasted it right on the switch,
[27:53] SPEAKER: turned the switch around a few times,
[27:55] SPEAKER: turned the tuning dial around a few times.
[27:57] SPEAKER: Works like a charm.
[27:58] SPEAKER: - Great. - Yeah.
[27:59] SPEAKER: - Love a quick fix.
[28:01] SPEAKER: - Yeah, it's the easiest thing I've fixed in like in years.
[28:04] SPEAKER: So I think that's it.
[28:06] SPEAKER: I think that's the whole thing.
[28:07] SPEAKER: - I've got a question about maintaining your TV
[28:09] SPEAKER: and also my TV, which is let's say at least 20 years
[28:14] SPEAKER: newer than yours, if not 25.
[28:17] SPEAKER: But I don't know if the question is relevant
[28:18] SPEAKER: to both TVs or not.
[28:19] SPEAKER: And I guess I'll just ask now,
[28:21] SPEAKER: since we're still talking about your TV,
[28:22] SPEAKER: this could be like highly electrically ignorance.
[28:26] SPEAKER: - Yes.
[28:27] SPEAKER: - Are there capacitors in that TV?
[28:28] SPEAKER: There are, right?
[28:29] SPEAKER: It's like we're using like normal modern style
[28:32] SPEAKER: of capacitors and TVs at that time, right?
[28:36] SPEAKER: - I don't know if they're huge capacitors,
[28:38] SPEAKER: but there will absolutely be scary capacitors inside.
[28:41] SPEAKER: Like the reason you don't take TVs apart,
[28:42] SPEAKER: if you don't know what you're doing
[28:43] SPEAKER: is that there are scary capacitors
[28:45] SPEAKER: in almost everything with a cathode ray tube.
[28:47] SPEAKER: - Right.
[28:47] SPEAKER: Yeah, I don't know.
[28:48] SPEAKER: I'm way out over my skis on asking questions like this
[28:51] SPEAKER: 'cause I barely understand this stuff.
[28:52] SPEAKER: But like you're getting into territory with CRTs now
[28:55] SPEAKER: where they're old enough that you see
[28:56] SPEAKER: a lot of people talk about replacing the capacitors
[28:59] SPEAKER: because as they age and give out,
[29:01] SPEAKER: it affects the quality of the image, right?
[29:03] SPEAKER: Like it causes actual issues with the video output
[29:07] SPEAKER: or display.
[29:08] SPEAKER: - And there's for popular TVs for like the PVTs
[29:11] SPEAKER: and stuff like that that people use
[29:12] SPEAKER: for a lot of classic game stuff.
[29:14] SPEAKER: And for arcade monitors,
[29:16] SPEAKER: there's a lot of guidance about how to do that.
[29:18] SPEAKER: - Right.
[29:19] SPEAKER: That's what I was wondering.
[29:20] SPEAKER: But again, that question is,
[29:23] SPEAKER: your TV is a quarter of a century older than mine probably.
[29:25] SPEAKER: So they're in different categories
[29:27] SPEAKER: or phases of their lifespan.
[29:29] SPEAKER: But I'm just wondering like when do you know it's time
[29:31] SPEAKER: to start replacing capacitors?
[29:33] SPEAKER: - Well, fundamentally the capacitors
[29:36] SPEAKER: should last a really long time
[29:37] SPEAKER: unless there was some sort of mechanical
[29:39] SPEAKER: or chemical defect in them
[29:40] SPEAKER: when they were manufacturing them, right?
[29:41] SPEAKER: It's like, you don't have to replace,
[29:45] SPEAKER: like we think about capacitor failures
[29:49] SPEAKER: because there have been multiple famous failures
[29:52] SPEAKER: of noteworthy capacitors.
[29:54] SPEAKER: - Yes, I am sitting here laughing
[29:55] SPEAKER: because my TV came out in 2002,
[29:57] SPEAKER: which I think is right around that territory
[30:01] SPEAKER: that the bad capacitor plague took place.
[30:03] SPEAKER: - Yeah, Microsoft or Nvidia or Microsoft
[30:07] SPEAKER: put a bunch of bad capacitors on Enforce motherboards
[30:09] SPEAKER: 'cause they were a little bit cheaper than the other ones.
[30:12] SPEAKER: The clock capacitor on the original Xbox
[30:14] SPEAKER: is another classic example.
[30:16] SPEAKER: There's a bunch.
[30:17] SPEAKER: And what happens generally is they get swollen
[30:19] SPEAKER: and then leak and then the shit that they leak
[30:21] SPEAKER: is real bad for motherboards and causes cascading failures.
[30:25] SPEAKER: So you wanna, like if you have an original Xbox,
[30:28] SPEAKER: you wanna clip that clock capacitor off now,
[30:30] SPEAKER: even if you're not gonna put a new one on.
[30:33] SPEAKER: If you have an Enforce motherboard,
[30:35] SPEAKER: just upgrade your computer
[30:36] SPEAKER: and put that in e-waste at this point.
[30:38] SPEAKER: - Yeah, I was just holding my Enforce motherboard
[30:41] SPEAKER: three days ago as a matter of fact.
[30:43] SPEAKER: - Oh my God, Brad.
[30:44] SPEAKER: - I've had, we were off at Nexlander this week.
[30:46] SPEAKER: My dual projects have been,
[30:48] SPEAKER: A, I went and bought eight big new nice plastic storage bins
[30:53] SPEAKER: and have been unloading closets and boxes
[30:55] SPEAKER: and kind of reorganizing and consolidating old stuff.
[30:58] SPEAKER: - I do, I can't help but notice that there is an arcade stick
[31:01] SPEAKER: with a green ball top behind you.
[31:04] SPEAKER: - Hang on, are we just gonna do a live pan
[31:06] SPEAKER: this camera around the room?
[31:07] SPEAKER: - Oh wow, I didn't realize you could do this.
[31:09] SPEAKER: Ooh, that's a nice cable coils.
[31:12] SPEAKER: - A lot of the stuff is in bins already.
[31:14] SPEAKER: - I love it.
[31:14] SPEAKER: Your bins are the best.
[31:16] SPEAKER: Do those seal, do those top seal on those?
[31:18] SPEAKER: - They're not waterproof.
[31:20] SPEAKER: - But they're like, the air won't get in.
[31:23] SPEAKER: - I think we might've talked about this
[31:24] SPEAKER: back with the hurricane business a few months ago
[31:27] SPEAKER: 'cause I went and bought,
[31:28] SPEAKER: in fact, I bought the same type of bins here
[31:29] SPEAKER: that I bought back home a few months ago
[31:30] SPEAKER: 'cause I wanted them all to be stack compatible.
[31:33] SPEAKER: - Oh yeah, that's important.
[31:34] SPEAKER: - You know, at some future date
[31:36] SPEAKER: when all these bins live in the same place
[31:37] SPEAKER: but when I was picking out those bins a few months ago,
[31:40] SPEAKER: I did find waterproof ones that,
[31:41] SPEAKER: what's the industry standard waterproof rating?
[31:44] SPEAKER: It's like IPV or whatever.
[31:45] SPEAKER: - IP something, something, yeah.
[31:47] SPEAKER: Like they had a literal numerical rating
[31:49] SPEAKER: on these bins at the store
[31:51] SPEAKER: that were in fact airtight and fully sealed
[31:53] SPEAKER: but they were way more expensive.
[31:55] SPEAKER: - Well, so I don't know if you want,
[31:56] SPEAKER: like where we live, where I live,
[31:58] SPEAKER: I don't know that you want airtight
[31:59] SPEAKER: just because you don't,
[32:01] SPEAKER: if you do that then you have to put in like silica gel
[32:04] SPEAKER: or something to suck the moisture out because it's wet.
[32:07] SPEAKER: - I don't know if these were actually fully airtight
[32:09] SPEAKER: but they were supposed to be waterproof at least.
[32:10] SPEAKER: - Okay, okay.
[32:12] SPEAKER: - Anyway.
[32:13] SPEAKER: - Did I see a Nintendo 64 over there
[32:14] SPEAKER: underneath your TV, Brad?
[32:15] SPEAKER: - Yes, well, not under the TV.
[32:17] SPEAKER: There is an N64 in one of these bins behind me.
[32:19] SPEAKER: You did not see it on the floor though.
[32:21] SPEAKER: On the floor, there's a GameCube and a PS2 Slim
[32:25] SPEAKER: and my Mr. Rat's Nest.
[32:26] SPEAKER: So yeah, my two projects this week
[32:28] SPEAKER: were A, start going through all these bins
[32:30] SPEAKER: which has necessarily had me handling things
[32:33] SPEAKER: like an Enforce motherboard
[32:34] SPEAKER: and my original Xbox and GameCube and stuff.
[32:37] SPEAKER: And the other project was get the CRT working finally
[32:40] SPEAKER: with the Mr. and some of this other stuff.
[32:42] SPEAKER: So I guess I'll talk about my TV a little bit.
[32:45] SPEAKER: - Yeah.
[32:46] SPEAKER: - It's a Toshiba 14AF42, see?
[32:49] SPEAKER: - Oh yeah, the 14AF42, that's a classic.
[32:51] SPEAKER: - Nice and pronounceable, you know,
[32:53] SPEAKER: like a good modern TV model number.
[32:55] SPEAKER: - Is it a 14, is it 14AF?
[32:58] SPEAKER: - You jest, but the 42 actually turns out
[33:01] SPEAKER: to have been a highly desirable model
[33:02] SPEAKER: because they made 43 through 46 after this.
[33:06] SPEAKER: It was, they made 41 through 46 total for this line.
[33:09] SPEAKER: Apparently the 43s and on,
[33:11] SPEAKER: they switched to a different jungle chip, I want to say.
[33:15] SPEAKER: Is that the right term?
[33:16] SPEAKER: - Is this Dota business again?
[33:18] SPEAKER: Are we getting back into jungling?
[33:19] SPEAKER: - No, it's not.
[33:20] SPEAKER: I think it's like an RGB thing.
[33:21] SPEAKER: It's like, okay, I have now just Googled jungle chip.
[33:25] SPEAKER: And in fact, an integrated circuit found
[33:26] SPEAKER: in most analog TVs in the 1990s.
[33:28] SPEAKER: It takes a composite video signal
[33:30] SPEAKER: from the radio frequency receiver electronics
[33:32] SPEAKER: and turns it into separate RGB outputs, okay.
[33:35] SPEAKER: - Okay, so this is the big difference
[33:37] SPEAKER: between your TV and my TV.
[33:38] SPEAKER: 'Cause my TV is designed to take a,
[33:43] SPEAKER: signals from the airwaves, radio waves,
[33:46] SPEAKER: and it uses those signals with analog circuits
[33:50] SPEAKER: to change the position of the electron gun
[33:53] SPEAKER: in such a way that colors and pictures come out of the tube.
[33:58] SPEAKER: - Yes.
[33:59] SPEAKER: - Like it is directly reading the airwaves.
[34:02] SPEAKER: Yours is doing some magic with computers.
[34:04] SPEAKER: - Some slightly more advanced video processing
[34:06] SPEAKER: going on inside this TV.
[34:08] SPEAKER: So, this thing is a highly desirable TV.
[34:11] SPEAKER: It's only 14 inches, but it has composite S-video
[34:16] SPEAKER: and component on it.
[34:18] SPEAKER: - Holy shit, component on a TV from that era
[34:20] SPEAKER: is impressive, yeah.
[34:21] SPEAKER: - Or a TV that size is the main thing.
[34:23] SPEAKER: Like you did not see component on TVs
[34:25] SPEAKER: probably smaller than like 27 inches back then,
[34:27] SPEAKER: or maybe 20, I don't know, but like.
[34:29] SPEAKER: - I think the first TV I had component on
[34:31] SPEAKER: was that 36 inch Panasonic tube.
[34:34] SPEAKER: And that was so you could do the anamorphic squeeze
[34:36] SPEAKER: on that bad boy.
[34:37] SPEAKER: - Ah, the anamorphic squeeze.
[34:38] SPEAKER: Magic, the first day.
[34:39] SPEAKER: - Can we talk about the anamorphic squeeze for a sec?
[34:41] SPEAKER: - Ah, the anamorphic squeeze was pretty.
[34:43] SPEAKER: I never quite understood what was going on electronically
[34:47] SPEAKER: inside the TV when you did this,
[34:48] SPEAKER: but it was basically like late era CRTs
[34:52] SPEAKER: had higher resolution than, you explain it.
[34:56] SPEAKER: - Okay, so what you were doing was
[34:58] SPEAKER: you were using the entire resolution of the TV
[35:01] SPEAKER: for the rendered picture on a letterbox image.
[35:05] SPEAKER: So on a standard DVD 480p resolution,
[35:12] SPEAKER: they would have a square picture.
[35:14] SPEAKER: And if it was widescreen,
[35:15] SPEAKER: the top third or top eighth and bottom eighth, whatever,
[35:19] SPEAKER: the black bars would be burned into the video, right?
[35:22] SPEAKER: They'd be baked into the video.
[35:23] SPEAKER: On anamorphic discs, they used all of the lines
[35:27] SPEAKER: for the picture.
[35:28] SPEAKER: So you got more image data,
[35:30] SPEAKER: but your TV had to know what to do with it
[35:32] SPEAKER: or your DVD player had to know what to do with it.
[35:33] SPEAKER: And either-
[35:34] SPEAKER: - 'Cause otherwise it came out looking vertically stretched.
[35:37] SPEAKER: - Tall and stretched, it looks like coneheads.
[35:38] SPEAKER: - Right, 'cause it was in fact stretched on the disc.
[35:41] SPEAKER: - Yeah, see pixels weren't square.
[35:43] SPEAKER: So on a TV that knew what to do,
[35:45] SPEAKER: it would take all of those pixels, all that image,
[35:48] SPEAKER: and scrunch it in and put the black bars in
[35:51] SPEAKER: just by not aiming the electron gun there.
[35:54] SPEAKER: And you'd get a higher quality picture,
[35:57] SPEAKER: imperceptibly higher quality picture.
[35:59] SPEAKER: - I thought it was pretty perceptible.
[36:01] SPEAKER: - I will tell you, on all the other TVs I saw it on,
[36:06] SPEAKER: I was unimpressed until I got that 36 inch Panasonic.
[36:09] SPEAKER: And I was like, okay, I kind of get it.
[36:11] SPEAKER: - Yeah.
[36:12] SPEAKER: - Like that size, it makes a difference.
[36:13] SPEAKER: - My roommate in college in the dorm
[36:15] SPEAKER: spent like all of his money on an ICV at some point.
[36:18] SPEAKER: - Hell yeah.
[36:19] SPEAKER: - Like basically just saved and like went without eating
[36:24] SPEAKER: or whatever, like he bent his will
[36:25] SPEAKER: toward getting a nice TV for a room.
[36:27] SPEAKER: - We all were in college at one point
[36:30] SPEAKER: and we're like, you know what?
[36:31] SPEAKER: If I can buy a semester's worth of ramen
[36:34] SPEAKER: and Chef Boyardee for $47,
[36:38] SPEAKER: and that means I'll have $550 left from my meal plan
[36:42] SPEAKER: that I can use to buy a new video card
[36:44] SPEAKER: or whatever studentship we bought at the time.
[36:47] SPEAKER: - I think it was a Sony Vega.
[36:48] SPEAKER: Anyway, that was right in the heyday of DVDs getting big.
[36:50] SPEAKER: And that was the first place I ever saw
[36:52] SPEAKER: the anamorphic squeeze and it was a revelatory moment,
[36:56] SPEAKER: I will say.
[36:58] SPEAKER: - So anyway, okay.
[36:59] SPEAKER: So your, I bet your TV doesn't do the squeeze
[37:02] SPEAKER: just because of-
[37:03] SPEAKER: - I don't, I doubt it.
[37:04] SPEAKER: I highly doubt it.
[37:05] SPEAKER: - Because of the size, yeah.
[37:06] SPEAKER: - I don't think so.
[37:07] SPEAKER: This was a sidewalk find as a matter of fact.
[37:10] SPEAKER: Actually, I hope he doesn't mind me saying
[37:12] SPEAKER: Steve Lin was my generous benefactor on this TV.
[37:15] SPEAKER: He found this TV on the sidewalk.
[37:17] SPEAKER: - Wow, we found my TV in a parking lot.
[37:20] SPEAKER: - Yeah, technically, but it was being-
[37:22] SPEAKER: - It was at a swap meet, I guess, so.
[37:25] SPEAKER: - It was the object of commerce at that point.
[37:26] SPEAKER: You know, like they wanted money for it.
[37:28] SPEAKER: This thing was just sitting there.
[37:29] SPEAKER: - Wow, that's pretty good.
[37:31] SPEAKER: - And he's the type of guy to rescue a CRT
[37:33] SPEAKER: from the sidewalk when he sees one.
[37:35] SPEAKER: - Look, I know that there,
[37:36] SPEAKER: we have multiple listeners in the audience
[37:38] SPEAKER: who will pick up a sidewalk TV, a CRT, should they see one?
[37:43] SPEAKER: - So I kind of started Googling around
[37:44] SPEAKER: and like reading some Reddit stories after he gave me this,
[37:46] SPEAKER: just kind of seeing what other people do.
[37:48] SPEAKER: And like, it's a thing.
[37:49] SPEAKER: Like you can find these fairly regularly,
[37:52] SPEAKER: like, especially if you go to e-waste places,
[37:53] SPEAKER: but even just on the sidewalk,
[37:55] SPEAKER: there's plenty of stories on Reddit of people
[37:58] SPEAKER: sometimes finding like very valuable old TVs,
[38:01] SPEAKER: but you'll frequently, you'll see things like,
[38:03] SPEAKER: oh, they had cut the power cable off of it.
[38:05] SPEAKER: And so I had to like put a new power cord in.
[38:06] SPEAKER: - Why would you do that?
[38:07] SPEAKER: - Or stuff like that.
[38:09] SPEAKER: - The heck's wrong with you putting it on the sidewalk?
[38:12] SPEAKER: The nice thing is they're pretty easy to fix
[38:16] SPEAKER: for the most part, even if they're broken, right?
[38:18] SPEAKER: Assuming you don't kill yourself on the capacitors.
[38:20] SPEAKER: - Yes, I mean, I think you definitely, like, okay,
[38:22] SPEAKER: maybe we should just say anybody listening to this
[38:24] SPEAKER: who's never opened a CRT before,
[38:25] SPEAKER: please look up what to do if you open a CRT.
[38:28] SPEAKER: - Yeah, the good news is there's a lot of YouTube videos.
[38:30] SPEAKER: I watched a bunch of them before I decided
[38:31] SPEAKER: I wasn't gonna do it and was gonna take it over
[38:34] SPEAKER: to Steve's house and ask him for help if I wanted to do that.
[38:38] SPEAKER: And then the contact cleaner worked,
[38:39] SPEAKER: so I don't have to worry about it.
[38:40] SPEAKER: - I need to learn how to discharge a CRT properly
[38:43] SPEAKER: at some point.
[38:44] SPEAKER: - I watched Vinny do it on a joust machine
[38:46] SPEAKER: in the basement of the old whiskey media office
[38:48] SPEAKER: back in the day.
[38:49] SPEAKER: And it was real scary.
[38:50] SPEAKER: 'Cause like he touched a screwdriver to two things
[38:52] SPEAKER: and it made a really loud noise
[38:54] SPEAKER: and his arm whammed back into space
[38:56] SPEAKER: and it was all he could do to hold onto the screwdriver.
[38:58] SPEAKER: And I was like, I don't know, no thank you.
[39:00] SPEAKER: - Yeah.
[39:01] SPEAKER: - Unsubscribe.
[39:02] SPEAKER: - Yes, anyway, he found it on the sidewalk.
[39:04] SPEAKER: The infrared sensor did not work on it.
[39:09] SPEAKER: - Does it have buttons?
[39:10] SPEAKER: - It only has power on channel and volume on the front.
[39:13] SPEAKER: So you can't change inputs without a remote on this TV.
[39:16] SPEAKER: So you can see why. - Oh, that sucks.
[39:17] SPEAKER: - You can see why somebody probably junked it
[39:19] SPEAKER: when they realized they could no longer switch inputs.
[39:21] SPEAKER: - Yeah.
[39:23] SPEAKER: - He sourced a new IR receiver for it,
[39:24] SPEAKER: which he said at this point
[39:25] SPEAKER: it was getting pretty hard to find.
[39:26] SPEAKER: Like you could find the part number for what you need,
[39:29] SPEAKER: but finding the actual part is getting tough.
[39:31] SPEAKER: So I think he said he bought like five of them just in case.
[39:34] SPEAKER: - Wow.
[39:35] SPEAKER: - But so he did replace the IR receiver
[39:37] SPEAKER: and had to source a new remote.
[39:38] SPEAKER: Obviously there was no remote on the sidewalk
[39:42] SPEAKER: and got it working.
[39:43] SPEAKER: And then later on.
[39:45] SPEAKER: - Is this the one that he replaced
[39:47] SPEAKER: with the TV that he bought when I bought my bad TV?
[39:50] SPEAKER: - Yes, he got that TV on when you bought,
[39:51] SPEAKER: the same day you bought your old TV
[39:53] SPEAKER: at the flea market last month.
[39:54] SPEAKER: And this was his like test bench fixing old consoles,
[39:57] SPEAKER: just like test screen kind of thing.
[40:00] SPEAKER: So he didn't need this one anymore when he got that PVM.
[40:03] SPEAKER: So it very generously found its way to my house.
[40:06] SPEAKER: - Wow.
[40:07] SPEAKER: - So I went through the same process you did
[40:09] SPEAKER: of once I had the TV ready to go,
[40:11] SPEAKER: like staring at the mister, trying to think like,
[40:13] SPEAKER: what's the best way to get video out of this thing
[40:14] SPEAKER: into this TV?
[40:15] SPEAKER: And obviously in my case, I had a lot of options
[40:17] SPEAKER: 'cause S-Video component, there's a lot of stuff I could do.
[40:21] SPEAKER: - That's a lot.
[40:22] SPEAKER: - It's a lot.
[40:23] SPEAKER: The mystery project, like you go to the compatibility site
[40:26] SPEAKER: and there's like a giant matrix.
[40:27] SPEAKER: I'm sure you've seen this table, right?
[40:29] SPEAKER: Of like connector types, signal types,
[40:32] SPEAKER: because like it's not just, you know,
[40:33] SPEAKER: like S-Video is not a signal or S-Video is a signal type,
[40:36] SPEAKER: sorry, but like over component, for example, or VGA,
[40:40] SPEAKER: you've got like RGB, I think RGSB is another one.
[40:44] SPEAKER: There's like multiple flavors of RGB.
[40:46] SPEAKER: There's whatever comes out of component, which is,
[40:49] SPEAKER: I've never known how to pronounce this.
[40:50] SPEAKER: - YP-
[40:51] SPEAKER: - YPBR.
[40:52] SPEAKER: - Yeah.
[40:53] SPEAKER: - Is how it's the actual-
[40:54] SPEAKER: - It's chroma luminance in one other,
[40:57] SPEAKER: I can't remember what the other one is, blacks maybe.
[41:00] SPEAKER: We talked about this on the video episode.
[41:01] SPEAKER: I can't, it's just, it's gone from my head.
[41:03] SPEAKER: - I don't know if there's a way to pronounce that,
[41:05] SPEAKER: that is not just the letters.
[41:08] SPEAKER: Anyway, like figuring out what you can get out of a mister
[41:10] SPEAKER: over different connection types
[41:12] SPEAKER: and what will be accepted by your average TV
[41:15] SPEAKER: is kind of complicated.
[41:16] SPEAKER: - It like, and it's not just complicated from a,
[41:19] SPEAKER: like you have to, in the old days of analog video,
[41:22] SPEAKER: you basically like plug the yellow wire into the yellow wire
[41:25] SPEAKER: or the red wire to the red wire,
[41:26] SPEAKER: the white wire to the right wire and it worked.
[41:28] SPEAKER: - That was kind of, yes,
[41:29] SPEAKER: that was the extent of what I did back in the day basically.
[41:32] SPEAKER: - Yeah, with this, you have to like set up the mister,
[41:35] SPEAKER: the software in the mister to output the right video
[41:37] SPEAKER: using the right output.
[41:39] SPEAKER: And it was, it's fairly intense.
[41:41] SPEAKER: - Yeah, it makes you realize there was way,
[41:43] SPEAKER: way more going on under the hood
[41:44] SPEAKER: of getting video out of stuff back in the day
[41:47] SPEAKER: than you realize.
[41:48] SPEAKER: - Except also it just kind of worked.
[41:49] SPEAKER: - Well, sure.
[41:50] SPEAKER: - So, so yeah, the, the component stuff is chroma
[41:54] SPEAKER: is the other thing, is the other output.
[41:56] SPEAKER: So it's luminance chroma and Y, whatever Y is, anyway.
[42:01] SPEAKER: - So I, like I said, I looked at that mister add-on stuff
[42:04] SPEAKER: and I was like, ah, this is,
[42:06] SPEAKER: this is not intended to be my permanent analog mister setup.
[42:09] SPEAKER: This is just, I just want to kind of get a quick
[42:10] SPEAKER: and dirty output going to play around with it.
[42:12] SPEAKER: Cause I want to get, you know,
[42:13] SPEAKER: there's a lot more interesting mister products coming out
[42:16] SPEAKER: these days that have got analog stuff built into them.
[42:19] SPEAKER: So I kind of want to get one of those for,
[42:22] SPEAKER: for my more permanent setup.
[42:24] SPEAKER: So I was just looking for something quick and cheap here.
[42:26] SPEAKER: - Do you have a case for your mister or just,
[42:28] SPEAKER: are you raw dogging it still?
[42:29] SPEAKER: - No, remember, remember you laser cut me
[42:31] SPEAKER: some nice little acrylic plates for the top and bottom,
[42:35] SPEAKER: like a fan mount.
[42:36] SPEAKER: - Yeah, yeah.
[42:37] SPEAKER: - So I've still just got the open,
[42:38] SPEAKER: I've got the open PCB stack still.
[42:41] SPEAKER: - And do you, do you have a, do you have an analog,
[42:43] SPEAKER: do you have an input board on top?
[42:44] SPEAKER: - Oh no, so I've, I've never had an IO board
[42:46] SPEAKER: cause I've never had an info one before.
[42:48] SPEAKER: - You want my old one?
[42:49] SPEAKER: - Well, sure, if you're looking to get rid of it.
[42:52] SPEAKER: - Yeah.
[42:53] SPEAKER: - I don't know if I'd, well, we'll talk later.
[42:55] SPEAKER: I might use it, I'm not sure if I would,
[42:57] SPEAKER: I'll have to think about how that would fit.
[42:59] SPEAKER: - Decide it's available if you want it,
[43:01] SPEAKER: it's just going to age in my garage.
[43:03] SPEAKER: - It might get, you'll take it to the storage locker
[43:05] SPEAKER: and then it will get way better.
[43:07] SPEAKER: - 20 years from now, people are going to be like,
[43:08] SPEAKER: what the hell is this weird thing?
[43:09] SPEAKER: - The thing will be ripe.
[43:11] SPEAKER: - Yeah, ready to go.
[43:12] SPEAKER: - Yeah, so, so the Mr. also, they added a feature
[43:15] SPEAKER: three, four years ago, like later into the project
[43:18] SPEAKER: called direct video that lets you actually get analog video
[43:21] SPEAKER: out of the HDMI port.
[43:23] SPEAKER: - That's amazing.
[43:23] SPEAKER: - Which I know sounds crazy.
[43:24] SPEAKER: I have no idea what kind of magic they're doing,
[43:26] SPEAKER: sending signals on different HDMI pins or whatever.
[43:29] SPEAKER: - Well, so there's an HDMI,
[43:31] SPEAKER: there's always been an HDMI to analog option
[43:34] SPEAKER: as part of the spec, yeah.
[43:36] SPEAKER: - Oh, I didn't know that.
[43:36] SPEAKER: - So you used to be able to get an HDMI adapter.
[43:39] SPEAKER: It's part of the back compatibility stuff.
[43:42] SPEAKER: So you used to really get like HDMI to VGA adapters
[43:44] SPEAKER: and stuff like that.
[43:45] SPEAKER: - That's exactly what I bought here.
[43:46] SPEAKER: - Oh yeah.
[43:47] SPEAKER: - This is what I ended up doing.
[43:48] SPEAKER: So in fact, that's how that feature is intended to be used.
[43:51] SPEAKER: When you turn on direct video, you need exactly that,
[43:54] SPEAKER: an HDMI to VGA adapter.
[43:56] SPEAKER: But that ties back into the different signal types
[43:58] SPEAKER: that I was talking about earlier,
[43:59] SPEAKER: where I think all you're getting out of VGA at that point
[44:02] SPEAKER: is RGB, so you need something that can take RGB,
[44:04] SPEAKER: which this TV cannot.
[44:06] SPEAKER: Does that make sense?
[44:07] SPEAKER: - Yeah.
[44:08] SPEAKER: - Like what I'm saying is,
[44:09] SPEAKER: I couldn't just get this VGA adapter.
[44:11] SPEAKER: - Oh, 'cause you need YPBP-Y.
[44:15] SPEAKER: - So you couldn't just get a dumb passive VGA
[44:20] SPEAKER: or DB9 to component adapter and feed that into the TV,
[44:25] SPEAKER: 'cause it's a signal that the TV can't understand.
[44:28] SPEAKER: So you would need yet another converter box
[44:30] SPEAKER: to convert that into component coming out of the VGA, right?
[44:34] SPEAKER: What I ended up doing is I have,
[44:36] SPEAKER: I actually have a little S-video converter,
[44:39] SPEAKER: VGA to S-video that was made by Mr. Add-ons
[44:41] SPEAKER: that Steve let me have
[44:43] SPEAKER: when he was offloading some of this stuff.
[44:45] SPEAKER: But that thing takes power,
[44:46] SPEAKER: like I don't get any image out of it
[44:48] SPEAKER: unless I have to power that off a USB brick,
[44:50] SPEAKER: because it is doing some active something.
[44:54] SPEAKER: - That is happening.
[44:55] SPEAKER: - Comb filter, I don't know,
[44:56] SPEAKER: some kind of encoding is turning the RGB VGA signal
[44:59] SPEAKER: into S-video somehow as it passes through that thing.
[45:02] SPEAKER: - Weird.
[45:03] SPEAKER: - Anyway, it is a fairly ugly Frankenstein's mess
[45:06] SPEAKER: of HDMI to VGA, VGA to little box, box to S-video.
[45:11] SPEAKER: You know, it's a lot.
[45:12] SPEAKER: - Okay, so the cables are a problem, right?
[45:15] SPEAKER: 'Cause I have power, I have the multiple audio,
[45:18] SPEAKER: the audio, the yellow, red, white RCA's going into the VCR.
[45:25] SPEAKER: And then I have a big giant long coax cable
[45:28] SPEAKER: going from the VCR to the TV.
[45:31] SPEAKER: But I also have a bunch of USB cables
[45:34] SPEAKER: going to the controllers,
[45:35] SPEAKER: 'cause I'm not using wireless on any of those,
[45:37] SPEAKER: 'cause wireless is kind of a pain in the butt
[45:40] SPEAKER: in all of these contexts.
[45:41] SPEAKER: And also it feels weird to stand there
[45:43] SPEAKER: and use a SNES controller
[45:45] SPEAKER: and not have it be plugged into the thing
[45:47] SPEAKER: that you're talking to,
[45:48] SPEAKER: even though I realize that we're past that
[45:50] SPEAKER: in the 21st century.
[45:54] SPEAKER: I don't know that there's a solve for the wire problem.
[45:56] SPEAKER: - Yeah, I don't think so.
[45:58] SPEAKER: I mean, the solve is carve out some space behind the TV
[46:01] SPEAKER: where you can tuck it away and not have to see it,
[46:03] SPEAKER: and then you can just press buttons and stuff.
[46:04] SPEAKER: - Well, sure.
[46:05] SPEAKER: If you need to interact with it, that's a bigger problem.
[46:08] SPEAKER: - Just as a point of clarification,
[46:10] SPEAKER: the HDMI legacy analog compatibility requires devices
[46:15] SPEAKER: that know how to export VGA analog signals out through HDMI.
[46:21] SPEAKER: - Interesting, okay.
[46:22] SPEAKER: - They're not, like all HDMI ports aren't good
[46:25] SPEAKER: with the HDMI to VGA adapter.
[46:26] SPEAKER: This was the part I wanted to look up
[46:28] SPEAKER: to make sure I got right.
[46:29] SPEAKER: - Okay, I had no idea that was part of the spec.
[46:31] SPEAKER: I thought that was just some kind of like ground up
[46:33] SPEAKER: witchcraft that the mystery developers had concocted.
[46:36] SPEAKER: I didn't realize that was something
[46:37] SPEAKER: they were piggybacking on.
[46:38] SPEAKER: - No, in the early days of HDMI,
[46:40] SPEAKER: and when you'd get video cards that had HDMI,
[46:42] SPEAKER: often you'd have either a DVI,
[46:44] SPEAKER: which like DVI does have that built into the spec, right?
[46:46] SPEAKER: Like you can get a passive DVI to VGA cable
[46:50] SPEAKER: 'cause there are analog pins inside the DVI cable.
[46:54] SPEAKER: - Right.
[46:55] SPEAKER: In this case though, your adapter has to go with a device
[47:00] SPEAKER: that knows how to use the adapter.
[47:01] SPEAKER: And the adapters may be specific to devices
[47:04] SPEAKER: that I don't know.
[47:05] SPEAKER: Anyway, so how is it?
[47:07] SPEAKER: Are you enjoying it?
[47:08] SPEAKER: - Looks great, yeah.
[47:09] SPEAKER: It's like, I mean, I've had, it's been, God,
[47:11] SPEAKER: almost five years since I put my MiSTer together
[47:13] SPEAKER: right around five years.
[47:14] SPEAKER: So it's not like a new thing or whatever,
[47:16] SPEAKER: but like there's something more transportive
[47:19] SPEAKER: about playing it on the type of screen
[47:21] SPEAKER: that it was made to be played on, right?
[47:22] SPEAKER: Or the games were made to be played on.
[47:23] SPEAKER: Like I can play old arcade games all I want
[47:26] SPEAKER: on these nice modern digital LCD screens.
[47:31] SPEAKER: There's something that enhances the feeling
[47:34] SPEAKER: of getting away with something illicit, you know?
[47:36] SPEAKER: When I'm playing like Ninja Turtles or The Simpsons
[47:39] SPEAKER: or you name it, like any game
[47:42] SPEAKER: that you pumped quarters into back in the day,
[47:44] SPEAKER: like playing it on an actual CRT in your house feels like,
[47:47] SPEAKER: oh wow, like my 10-year-old dream
[47:51] SPEAKER: of owning a Teenage Mutant Ninja Turtles machine.
[47:53] SPEAKER: It's like kind of being realized here.
[47:55] SPEAKER: Well, I mean, you're not wrong.
[47:57] SPEAKER: There's a, the thing I noticed before I did anything else
[48:02] SPEAKER: was how even when the dial was kind of janky still,
[48:07] SPEAKER: like the colors are intense, like really, really bright,
[48:12] SPEAKER: even compared to like my nice OLED 4K monitor and all that.
[48:17] SPEAKER: And as I was setting up the MiSTer to work on the TV,
[48:20] SPEAKER: I had it plugged into the capture card on my computer
[48:22] SPEAKER: and I was running it on the screen, on this nice OLED,
[48:26] SPEAKER: and I put that screen view, the screen window
[48:30] SPEAKER: that we talked about a couple of weeks ago,
[48:32] SPEAKER: up on top of it, and it looks really nice.
[48:34] SPEAKER: Like it looks good, it has good scan lines,
[48:37] SPEAKER: the whole thing, everything you want.
[48:39] SPEAKER: But damn, when you plug it into the real TV,
[48:41] SPEAKER: it's pretty amazing.
[48:42] SPEAKER: Now, one of the things that's interesting on mine
[48:45] SPEAKER: is when I, I aimed the high-speed camera on my phone at it
[48:49] SPEAKER: just to see what, see if I could see scan lines
[48:51] SPEAKER: to show the kiddo how it worked.
[48:53] SPEAKER: And they're diagonal, so there's like a diagonal bar,
[48:57] SPEAKER: which I assume is the blanking, is the blank,
[49:00] SPEAKER: is the blank screen, the blank passes
[49:02] SPEAKER: that you're seeing or something, I don't know.
[49:04] SPEAKER: It's really weird, it's not like anything I've seen before.
[49:07] SPEAKER: It's also only 240 hertz camera,
[49:09] SPEAKER: so it might be that it's not fast enough
[49:11] SPEAKER: to pick it up reliably, but.
[49:14] SPEAKER: - One thing I found is that I had most of the cores
[49:17] SPEAKER: that I use regularly, I had turned on a bunch of the fake,
[49:22] SPEAKER: you know, scan line and shadow mask type stuff,
[49:24] SPEAKER: like a lot of the video processing.
[49:26] SPEAKER: It's supposed to replicate the look of a CRT,
[49:28] SPEAKER: and I had forgotten about that,
[49:29] SPEAKER: so as I was playing all these things on this TV
[49:31] SPEAKER: for the first time, I had to remind myself like,
[49:34] SPEAKER: oh wait, I'm overlaying a bunch of fake scan lines
[49:36] SPEAKER: and fake shadow mask patterns on top of a real TV
[49:39] SPEAKER: that has real physical versions of that stuff,
[49:41] SPEAKER: so I could turn all that stuff off.
[49:44] SPEAKER: - I went through and made sure I had the right audio chip
[49:47] SPEAKER: for the RNS and Genesis that I had.
[49:51] SPEAKER: I declared Mr. Bankruptcy when I started out on this.
[49:55] SPEAKER: I kept, my ROM stuff was all organized and right,
[49:58] SPEAKER: but I wiped out the settings folder
[49:59] SPEAKER: and just started from scratch
[50:00] SPEAKER: because it had been long enough.
[50:03] SPEAKER: And like, it's been, so my Mr. goes through intense periods
[50:08] SPEAKER: of use and then ages for six or eight months at a time.
[50:10] SPEAKER: - That'll happen.
[50:12] SPEAKER: - So like the last time I probably got into it
[50:14] SPEAKER: was when the PS1 core was new.
[50:16] SPEAKER: - Okay.
[50:17] SPEAKER: - Maybe the N64 core.
[50:18] SPEAKER: - It's been a couple of years.
[50:19] SPEAKER: - And it's been a minute.
[50:21] SPEAKER: So like, it was nice to come in
[50:23] SPEAKER: with a relatively fresh start.
[50:25] SPEAKER: Now, configuring all the cores
[50:28] SPEAKER: and having to dig a keyboard and stuff out
[50:30] SPEAKER: to make it all work was a little bit of a hassle.
[50:32] SPEAKER: - Yes, actually that brings me to,
[50:33] SPEAKER: I can't believe I was about to forget this,
[50:35] SPEAKER: but the troubleshooting phase of getting this thing working.
[50:39] SPEAKER: - Yeah, so mine just worked.
[50:41] SPEAKER: - Yeah, yours, because you did the sensible thing
[50:44] SPEAKER: and got the all-in-one board
[50:45] SPEAKER: that kind of just does all this for you.
[50:47] SPEAKER: - Well, no, I still had to set up in the Mr. NE,
[50:49] SPEAKER: I had to set up the resolution and all that stuff, right.
[50:52] SPEAKER: But in that, but like I did that on the computer
[50:55] SPEAKER: and then I moved it into the other room with the TV.
[50:56] SPEAKER: And when I plugged it in, it just, I was really shocked.
[50:59] SPEAKER: I was expecting to have a real back and forth
[51:01] SPEAKER: and a pain in the ass.
[51:02] SPEAKER: - Well, what I mean is I went the direct video route
[51:04] SPEAKER: where I've just had to go buy a,
[51:05] SPEAKER: I bought a just a $10 Ugreen HDMI to VGA adapter,
[51:08] SPEAKER: but there's all kinds of conflicting info out there
[51:10] SPEAKER: about which adapters work and which don't.
[51:12] SPEAKER: And then when I was going through this extra
[51:15] SPEAKER: kind of little encoder dongle to turn it into S-video,
[51:17] SPEAKER: like it just introduced all kinds of extra variables
[51:20] SPEAKER: that might or might not work based on like exactly
[51:23] SPEAKER: what ship is in this VGA adapter I got.
[51:26] SPEAKER: - So this is literally, I was reading these how-tos
[51:29] SPEAKER: 'cause you had recommended that you had said,
[51:30] SPEAKER: hey, you can do this.
[51:31] SPEAKER: And Steve pointed me to her a couple of things
[51:33] SPEAKER: and the Mr. Jan will help me with similar info.
[51:36] SPEAKER: And I looked at it all and I was like,
[51:37] SPEAKER: if I end up buying three VGA to HDMI adapters,
[51:40] SPEAKER: I might as well have just bought the Mr. add-ons board.
[51:43] SPEAKER: - That was my fear.
[51:43] SPEAKER: That was exactly it.
[51:44] SPEAKER: And even, you know, you can return stuff.
[51:46] SPEAKER: It's not the end of the world if it doesn't work.
[51:48] SPEAKER: - But it's a hassle.
[51:49] SPEAKER: - But that was the thing.
[51:50] SPEAKER: It was just like, oh man,
[51:51] SPEAKER: like I've got some time off this week.
[51:52] SPEAKER: I really just want to play with this thing.
[51:53] SPEAKER: I don't want to cycle through three or four adapters,
[51:56] SPEAKER: trying to find one that works.
[51:57] SPEAKER: All of this is a preamble for me saying,
[52:00] SPEAKER: when I finally got all this stuff hooked up
[52:01] SPEAKER: and started trying to make it work,
[52:04] SPEAKER: what I was getting, it's kind of hard to,
[52:05] SPEAKER: I actually posted a video on the Discord
[52:07] SPEAKER: if you want to go look at it,
[52:07] SPEAKER: but it's kind of hard to describe.
[52:08] SPEAKER: I was getting like sort of three images
[52:12] SPEAKER: of the image side by side.
[52:13] SPEAKER: All scrolling horrors are vertically, very rapidly.
[52:16] SPEAKER: - Yeah, that seems bad.
[52:17] SPEAKER: - It was like, okay, well maybe I just got a bad adapter
[52:19] SPEAKER: or like one that is not compatible
[52:20] SPEAKER: with whatever the Mr. is doing.
[52:22] SPEAKER: I spent like most of a morning trying to troubleshoot stuff.
[52:26] SPEAKER: - Do you have to just switch the component cables?
[52:28] SPEAKER: - Trying to figure out what was going on with this thing.
[52:30] SPEAKER: It finally got to the point where I could not find help
[52:32] SPEAKER: anywhere else, so I ended up on the actual Mr. Discord
[52:34] SPEAKER: in the help channel, posting a video there.
[52:37] SPEAKER: People were going like, oh, I've got that same equipment.
[52:39] SPEAKER: Like I haven't seen that, that's weird.
[52:41] SPEAKER: Can you post your INI file?
[52:43] SPEAKER: - Yeah.
[52:44] SPEAKER: - And I was like, sure, I drag it in there.
[52:47] SPEAKER: The person who's helping me,
[52:48] SPEAKER: the very top of the INI file,
[52:50] SPEAKER: it's like kind of a classic INI
[52:52] SPEAKER: where it's arranged into sections.
[52:54] SPEAKER: Each section name goes in brackets.
[52:57] SPEAKER: The person was like, can you add a bracket
[53:00] SPEAKER: at the beginning of the first line?
[53:02] SPEAKER: - Oh my God, really?
[53:03] SPEAKER: - And I was like, are you fucking kidding me?
[53:05] SPEAKER: Are you actually serious right now?
[53:07] SPEAKER: Somehow in tweaking and going and changing the settings
[53:10] SPEAKER: to turn on all the analog video stuff,
[53:12] SPEAKER: I had, and yes, I was using Vim for this,
[53:15] SPEAKER: I had somehow deleted the first bracket
[53:17] SPEAKER: at literally the first character of the file.
[53:19] SPEAKER: - Look, Vim does all sorts of things for you.
[53:21] SPEAKER: It'll mess up your Mr. INI, no problem.
[53:23] SPEAKER: That's amazing.
[53:24] SPEAKER: - Anyway, it was basically failing
[53:27] SPEAKER: to parse the entire INI file
[53:29] SPEAKER: because the first section name
[53:30] SPEAKER: did not have the proper brackets in closing.
[53:34] SPEAKER: - It's like we always say here,
[53:35] SPEAKER: Brad and Will made a tech pod.
[53:36] SPEAKER: If something's broken, it's probably Vim.
[53:38] SPEAKER: - I was like over the moon when I saw this.
[53:40] SPEAKER: I can tell you exactly what happened also
[53:41] SPEAKER: because X is the delete character key in Vim
[53:45] SPEAKER: and control X is save and quit.
[53:47] SPEAKER: And at some point I'm quite positive
[53:50] SPEAKER: I had tried to save and quit a file
[53:52] SPEAKER: and it had not registered command mode
[53:54] SPEAKER: with the colon for whatever reason.
[53:55] SPEAKER: And instead it just took the X and deleted it.
[53:58] SPEAKER: Anyway.
[53:59] SPEAKER: - Which Vim user has not suffered
[54:01] SPEAKER: this exact same indignity, Brad?
[54:02] SPEAKER: You should put a couple extra brackets at the front
[54:04] SPEAKER: so you're good to go now.
[54:05] SPEAKER: - Anyway, as embarrassing as that was,
[54:06] SPEAKER: I was over the moon that they had caught that though,
[54:08] SPEAKER: because I had just been banging my head on this thing
[54:10] SPEAKER: for most of a morning.
[54:11] SPEAKER: And it probably would have taken me forever
[54:13] SPEAKER: to discover that myself.
[54:16] SPEAKER: - But it's interesting 'cause if you'd,
[54:18] SPEAKER: when I was editing my Mr. INI,
[54:20] SPEAKER: I opened it up.
[54:21] SPEAKER: I just opened up the Samba share on my Mr.
[54:24] SPEAKER: from my Windows machine and opened Notepad++,
[54:27] SPEAKER: which has this syntax highlighting stuff.
[54:29] SPEAKER: So when you have a missing bracket,
[54:30] SPEAKER: it just highlights everything after that bracket.
[54:33] SPEAKER: That's not working.
[54:35] SPEAKER: I'm just gonna take a screenshot of your face right now here.
[54:38] SPEAKER: Yep, that's going in the file.
[54:42] SPEAKER: I'm sorry about your Vim problems.
[54:43] SPEAKER: - It's fine.
[54:44] SPEAKER: It was not, look, Vim's fine.
[54:46] SPEAKER: And it honestly felt pretty good when they caught that.
[54:51] SPEAKER: And I SSH'd into the thing, added the bracket,
[54:53] SPEAKER: saved it, turned the Mr. or rebooted the Mr.
[54:55] SPEAKER: and it just worked.
[54:56] SPEAKER: I was like, okay, that actually felt very good
[54:59] SPEAKER: to go change one character
[55:00] SPEAKER: and have it solve all of these problems.
[55:03] SPEAKER: It was a good time. - That's really funny.
[55:04] SPEAKER: - It was a good time. - This is really funny.
[55:06] SPEAKER: - Yes, anyway.
[55:08] SPEAKER: - So I went through as part of the Mr.,
[55:11] SPEAKER: I had at one point mounted,
[55:13] SPEAKER: I made some choices when I first set up the Mr.
[55:15] SPEAKER: And I think when I was,
[55:16] SPEAKER: 'cause I mount my ROMs are for the most part
[55:18] SPEAKER: stored on the NAS, so that I don't have,
[55:22] SPEAKER: I have like a small SSD, a small SD card in the Mr.
[55:27] SPEAKER: And I think I at one point had mounted,
[55:30] SPEAKER: I'd mounted the ROMs in like a subfolder of the subfolder
[55:33] SPEAKER: they were supposed to be in
[55:33] SPEAKER: instead of the subfolder they were supposed to be in.
[55:35] SPEAKER: So they were like, I had multiple ghost Mr.
[55:39] SPEAKER: folder hierarchies on my SD card
[55:42] SPEAKER: and I had to go through and clean up all that stuff.
[55:44] SPEAKER: But the nice thing is, as a result of cleaning all that stuff
[55:47] SPEAKER: up and getting the BIOSes and the places
[55:48] SPEAKER: where they're expected to be
[55:49] SPEAKER: and getting the config files for the different cores
[55:52] SPEAKER: where they're supposed to be,
[55:53] SPEAKER: is that now stuff is just really easy to manage
[55:55] SPEAKER: and I can flip it on and remote into it
[55:59] SPEAKER: and do it from a PC or laptop.
[56:01] SPEAKER: So I can sit there with my laptop in another room
[56:04] SPEAKER: with the Mr. just connected over wifi
[56:06] SPEAKER: and it works pretty good for the most part.
[56:08] SPEAKER: The wifi connection's not stable enough to do like,
[56:12] SPEAKER: to move like big ROMs onto it,
[56:14] SPEAKER: but also I can just put those on on the NAS
[56:16] SPEAKER: and it turns out that works fine.
[56:17] SPEAKER: - Yeah, two things here on the storing all your games
[56:20] SPEAKER: on the NAS thing that really proved its worth
[56:23] SPEAKER: like the next day when I found there, you know,
[56:25] SPEAKER: like a lot of people are making old games or sorry,
[56:27] SPEAKER: new games for old consoles, you know,
[56:28] SPEAKER: you're like developers making like,
[56:29] SPEAKER: hey, we made a shoot 'em up for the Genesis or whatever.
[56:33] SPEAKER: A Japanese developer has put out a new side scrolling
[56:35] SPEAKER: shooter, side scrolling shooter.
[56:37] SPEAKER: - Ooh.
[56:38] SPEAKER: - Like similarly Gradius, Life Force, that style of shooter.
[56:40] SPEAKER: - Oh wow.
[56:41] SPEAKER: - Not the vertically scrolling one like 1943 or whatever.
[56:44] SPEAKER: - Or Xevious or whatever, yeah.
[56:45] SPEAKER: - They had, I found a demo ROM of it.
[56:48] SPEAKER: Like they're only selling physical parts.
[56:50] SPEAKER: There's no digital release.
[56:51] SPEAKER: So you literally can't even buy the ROM
[56:53] SPEAKER: from them if you want to.
[56:54] SPEAKER: - Is this that Genesis, is this a Genesis game?
[56:56] SPEAKER: Is that what it is?
[56:57] SPEAKER: - No, it's an NES game.
[56:58] SPEAKER: The name is very esoteric and I cannot remember at all
[57:01] SPEAKER: what it is right now.
[57:02] SPEAKER: Like it is completely escaping me.
[57:04] SPEAKER: - I saw a Genesis game that's like this yesterday too.
[57:06] SPEAKER: It's like a Metroidvania.
[57:08] SPEAKER: - Yeah, I would believe that that is also in progress.
[57:10] SPEAKER: I mean, I think there are a lot of, like there are, you know,
[57:12] SPEAKER: there are new GBA games being made all the time now.
[57:15] SPEAKER: Trying to find the name of the game just to fill it in here.
[57:17] SPEAKER: But anyway, like the point is when I found that demo ROM
[57:22] SPEAKER: of it, I just threw it on the right folder on the NAS
[57:24] SPEAKER: and swiveled my chair around and turned the MiSTer on
[57:26] SPEAKER: and there it was just ready to play, right?
[57:27] SPEAKER: - Yeah, it's really nice.
[57:28] SPEAKER: It takes a minute for the NAS to mount the Samba share,
[57:32] SPEAKER: but the MiSTer to mount the Samba share.
[57:34] SPEAKER: - Yes, I have been finding that.
[57:35] SPEAKER: So that's the other thing I was gonna say is on the subject
[57:37] SPEAKER: of having your MiSTer on wifi.
[57:39] SPEAKER: This might have been better than finding that bracket error
[57:43] SPEAKER: and fixing it.
[57:44] SPEAKER: - Which is?
[57:45] SPEAKER: - I pulled a router that I've had in the box
[57:47] SPEAKER: for eight years out and put it back into service.
[57:50] SPEAKER: - Oh, and you're using it as a bridge?
[57:51] SPEAKER: - Yeah, so we're gonna set up my oldest new SARTI N66.
[57:54] SPEAKER: You remember that one?
[57:55] SPEAKER: - Yeah.
[57:56] SPEAKER: - The classic. - It's a classic, yeah.
[57:57] SPEAKER: - The classic N router that everybody bought.
[57:59] SPEAKER: - I used that one until it actually died.
[58:01] SPEAKER: - Yeah.
[58:02] SPEAKER: - Mine conked out eventually.
[58:03] SPEAKER: - Yeah, so I've like, you know, holding on to old stuff
[58:06] SPEAKER: I know is kind of fraught and perhaps some of us,
[58:10] SPEAKER: perhaps some of us do it a little bit to access.
[58:11] SPEAKER: I get it.
[58:12] SPEAKER: - Sometimes hoarding is good, Brad.
[58:13] SPEAKER: - Like I do think that maybe keeping your previous
[58:16] SPEAKER: wifi router around just in case is actually not the worst
[58:19] SPEAKER: thing to do because A, router is critical infrastructure.
[58:22] SPEAKER: So if yours dies, it's nice to have something
[58:24] SPEAKER: to plug in on the spot.
[58:26] SPEAKER: But B, you know, like it's getting wired internet
[58:28] SPEAKER: in a corner of a room where it's not feasible
[58:30] SPEAKER: to run a cable is, I mean, it's not actual wired internet,
[58:34] SPEAKER: but like what I mean is like I could get a wifi adapter
[58:37] SPEAKER: for the mister and set it up on there,
[58:39] SPEAKER: which is probably gonna be not great
[58:40] SPEAKER: because it's tiny little USB dongle
[58:41] SPEAKER: with a tiny antenna in it.
[58:44] SPEAKER: Or I can use this dedicated box
[58:45] SPEAKER: that's got multiple big antennas and turn that into.
[58:48] SPEAKER: - So I'll tell you, I use the wifi, the little tiny dongle
[58:51] SPEAKER: and it's fine.
[58:52] SPEAKER: - I'm sure it's fine.
[58:53] SPEAKER: It's the problem, I was having a problem with it briefly
[58:57] SPEAKER: when I first started setting this up where it was hooking up
[58:59] SPEAKER: to the wrong access point because I have access points
[59:02] SPEAKER: on either side of the house.
[59:04] SPEAKER: And it was hooking up to the one that was far away
[59:06] SPEAKER: from where I was sitting just because I think signal
[59:08] SPEAKER: was too high where it was.
[59:10] SPEAKER: And once I fixed that, it's been really good.
[59:14] SPEAKER: Like I load PlayStation games and everything across it.
[59:16] SPEAKER: It's fine.
[59:17] SPEAKER: I played Parappa for the first time.
[59:19] SPEAKER: - Wow.
[59:20] SPEAKER: - I never played Parappa because it doesn't really play
[59:21] SPEAKER: on LCDs.
[59:22] SPEAKER: - Oh yeah, right.
[59:24] SPEAKER: Speaking of games that are not latency tolerant.
[59:27] SPEAKER: - No.
[59:28] SPEAKER: - Parappa is not forgiving about missed inputs.
[59:30] SPEAKER: - So the problem with Parappa on my TV is that I have,
[59:33] SPEAKER: it has like a frame around the edges of the tube
[59:35] SPEAKER: that almost vignette it.
[59:37] SPEAKER: And all the UI that you need to play the game
[59:39] SPEAKER: is covered up by that thing.
[59:40] SPEAKER: - Sure.
[59:41] SPEAKER: - I'll have to get the other TV out to play that I guess.
[59:43] SPEAKER: - But the other thing I was gonna say real quick
[59:45] SPEAKER: about the wifi is that.
[59:46] SPEAKER: - Yeah, I absolutely believe like a normal dongle
[59:48] SPEAKER: would be just fine.
[59:49] SPEAKER: I also am going to plug in my PS2 though.
[59:52] SPEAKER: - Oh, okay.
[59:53] SPEAKER: - 'Cause I've got another project brewing there.
[59:56] SPEAKER: - Playing Tony Hawk 3?
[59:57] SPEAKER: - Mess around with maybe trying to load some PS2 games
[1:00:00] SPEAKER: over the network.
[1:00:01] SPEAKER: - Ooh.
[1:00:01] SPEAKER: - From a Samba share.
[1:00:02] SPEAKER: - Okay.
[1:00:03] SPEAKER: - Which I have not started on yet,
[1:00:05] SPEAKER: but getting wifi on a PS2 is way, way trickier
[1:00:08] SPEAKER: than getting wifi on a mister.
[1:00:10] SPEAKER: So I figured why not just set up the bridge
[1:00:12] SPEAKER: with the router and just plug everything into that instead.
[1:00:16] SPEAKER: I also pulled out my classic ASCII AV selector.
[1:00:19] SPEAKER: Anybody knows?
[1:00:20] SPEAKER: - What's an ASCII AV selector?
[1:00:22] SPEAKER: - ASCII is like the classic Japanese peripheral maker.
[1:00:25] SPEAKER: - Oh.
[1:00:26] SPEAKER: - Like made a lot of Nintendo and Super Nintendo controllers.
[1:00:29] SPEAKER: I think, if I'm not mistaken,
[1:00:32] SPEAKER: I want to say they were the actual manufacturer
[1:00:34] SPEAKER: of the NES advantage.
[1:00:36] SPEAKER: - Really?
[1:00:37] SPEAKER: - Not ASCII branded, obviously.
[1:00:38] SPEAKER: Nintendo put their own name on that, but they.
[1:00:40] SPEAKER: - The two button joystick with turbo buttons.
[1:00:43] SPEAKER: I had both of those.
[1:00:44] SPEAKER: - Yes, yes.
[1:00:44] SPEAKER: Anyway, the ASCII selector is just a nice little
[1:00:47] SPEAKER: like five or six way analog audio video changer, switcher,
[1:00:52] SPEAKER: selector kind of thing, which I imported, I believe.
[1:00:54] SPEAKER: It's Japanese made, got Japanese text on the back.
[1:00:57] SPEAKER: I think the point I'm trying to make is that I was the kind
[1:01:00] SPEAKER: of nerd who had to import the best AV selector.
[1:01:03] SPEAKER: - Right, I don't, I'm not surprised.
[1:01:05] SPEAKER: - And not just buy whatever crap was at Walmart at the time
[1:01:07] SPEAKER: in the late nineties.
[1:01:09] SPEAKER: - I was gonna say the other thing that I saw
[1:01:11] SPEAKER: at the flea market last week is, or last month is the,
[1:01:15] SPEAKER: is one of those things that sits underneath your monitor
[1:01:16] SPEAKER: on your desk with like power.
[1:01:18] SPEAKER: It's a power strip with individual buttons for the computer,
[1:01:21] SPEAKER: the monitor, the printer, your modem, and then other.
[1:01:25] SPEAKER: I kind of wish I had bought that, useless.
[1:01:29] SPEAKER: But it would look real good underneath the,
[1:01:30] SPEAKER: underneath the TV and would replicate the exact setup
[1:01:33] SPEAKER: that I had as a youth.
[1:01:35] SPEAKER: - Yeah, yeah.
[1:01:36] SPEAKER: Anyway, it's been, it's been fun pulling old stuff out
[1:01:37] SPEAKER: and plugging it in.
[1:01:38] SPEAKER: I've been going through old PS2 and GameCube memory cards
[1:01:41] SPEAKER: to see if my save games are still on there.
[1:01:43] SPEAKER: They are.
[1:01:44] SPEAKER: - It's amazing.
[1:01:44] SPEAKER: - And I have to find a way to dump those soon.
[1:01:46] SPEAKER: My Xbox does not power on.
[1:01:48] SPEAKER: - Oh no.
[1:01:49] SPEAKER: - My original Xbox does not turn on.
[1:01:50] SPEAKER: - Did you crack it open and had you clipped the clock?
[1:01:52] SPEAKER: - Yeah, I took the clock capacitor and one other
[1:01:55] SPEAKER: 'cause I put them in a little Ziploc baggie
[1:01:57] SPEAKER: and taped it to the console just for reference, I guess.
[1:01:59] SPEAKER: Was probably my thinking there.
[1:02:01] SPEAKER: So I know that I pulled two capacitors out of that thing.
[1:02:04] SPEAKER: Like three or four years ago, maybe three years ago.
[1:02:06] SPEAKER: - It was around the time we started the podcast,
[1:02:08] SPEAKER: if I recall.
[1:02:09] SPEAKER: - Anyway, that thing's still faster or not, does not,
[1:02:13] SPEAKER: oh, actually maybe the other capacitor I took out
[1:02:15] SPEAKER: was load bearing perhaps.
[1:02:16] SPEAKER: I didn't consider that.
[1:02:18] SPEAKER: Now that I think about it, the clock capacitor,
[1:02:20] SPEAKER: the system-
[1:02:21] SPEAKER: - It just won't keep real-time clock, right?
[1:02:23] SPEAKER: - Unless I think it's the last revision of Xbox,
[1:02:25] SPEAKER: actually needs it in to boot,
[1:02:26] SPEAKER: but all the previous ones, which mine is,
[1:02:29] SPEAKER: work fine without it.
[1:02:30] SPEAKER: But maybe that other capacitor I took out actually
[1:02:33] SPEAKER: probably need to open that thing back up
[1:02:35] SPEAKER: and try to service it.
[1:02:35] SPEAKER: - It's got this ASCII-
[1:02:36] SPEAKER: - At some point.
[1:02:37] SPEAKER: - This ASCII, the video switcher is incredible.
[1:02:41] SPEAKER: - The one I have?
[1:02:42] SPEAKER: - Yeah, the one you have.
[1:02:42] SPEAKER: I found it on surugayaha.com.
[1:02:47] SPEAKER: - The selector?
[1:02:48] SPEAKER: - The selector, yeah.
[1:02:49] SPEAKER: - The AV selector, it's nice.
[1:02:50] SPEAKER: - Another hard ASCII AV selector.
[1:02:52] SPEAKER: - You wanna talk about chunky, chunky buttons.
[1:02:54] SPEAKER: Those buttons make a very good thunk when you click them.
[1:02:57] SPEAKER: - They look pretty good.
[1:02:59] SPEAKER: Yeah, so it's been fun getting into the analog stuff.
[1:03:02] SPEAKER: The big surprise for me was how excited
[1:03:05] SPEAKER: my daughter was about it.
[1:03:06] SPEAKER: I didn't expect her to get into it at all.
[1:03:08] SPEAKER: - Of course, I mean, we've talked a little bit.
[1:03:09] SPEAKER: I think like the youth are kind of having a moment
[1:03:11] SPEAKER: with analog technology, right?
[1:03:12] SPEAKER: With film cameras and stuff like that as well.
[1:03:15] SPEAKER: - Yeah, maybe.
[1:03:16] SPEAKER: - Because that tapes.
[1:03:17] SPEAKER: - For her, it's like, I don't know, she's,
[1:03:21] SPEAKER: it's been fun 'cause we'll play Mario to get,
[1:03:23] SPEAKER: she'll take a turn in Mario and she'll be like,
[1:03:24] SPEAKER: "Hey dad, I got to the fourth world."
[1:03:26] SPEAKER: And I'll then play and have a hell of a time
[1:03:31] SPEAKER: 'cause the game's way harder than I remember it being.
[1:03:34] SPEAKER: I finally can do the thing where you run and slide
[1:03:36] SPEAKER: underneath a one height brick when you're big Mario again,
[1:03:39] SPEAKER: which I wasn't sure that those 8BitDo controllers
[1:03:43] SPEAKER: were capable of, but they are.
[1:03:46] SPEAKER: I was just old and couldn't do it anymore.
[1:03:48] SPEAKER: The next thing I want to look at is getting a snack
[1:03:50] SPEAKER: so I can plug in my old controllers maybe.
[1:03:53] SPEAKER: - Or that ultra low latency.
[1:03:55] SPEAKER: - Well, and I have a zapper here too.
[1:03:57] SPEAKER: So I can play light gun games.
[1:03:59] SPEAKER: - Yeah, sure.
[1:04:00] SPEAKER: It's the final frontier of Mr. Stuff
[1:04:02] SPEAKER: is playing light gun games.
[1:04:04] SPEAKER: - Look, I did the thing with a retro pie years ago
[1:04:08] SPEAKER: where I set up a Wiimote, I set up two candles
[1:04:10] SPEAKER: on the side of the TV and used a Wiimote as a light gun.
[1:04:13] SPEAKER: That was fun, and it worked surprisingly well
[1:04:17] SPEAKER: for like House of the Dead and stuff like that.
[1:04:20] SPEAKER: But yeah, I haven't played,
[1:04:22] SPEAKER: like I haven't played Hogan's Alley in 30 years.
[1:04:24] SPEAKER: I don't think Hogan's Alley is very good, but who knows?
[1:04:27] SPEAKER: Maybe it is, maybe it's fun.
[1:04:28] SPEAKER: - You might've been missing something back then.
[1:04:30] SPEAKER: - Yeah, look, all I wanted was a copy of Hogan's Alley
[1:04:34] SPEAKER: and they got me Gumshoe 'cause they were like,
[1:04:35] SPEAKER: this is gonna be, this is an adventure game
[1:04:37] SPEAKER: about a private detective.
[1:04:38] SPEAKER: You love detectives.
[1:04:39] SPEAKER: I was like, well, I do love detectives, that is correct.
[1:04:41] SPEAKER: - Is Gumshoe good?
[1:04:42] SPEAKER: I've never played Gumshoe.
[1:04:43] SPEAKER: - So I thought Gumshoe was bad for a long time.
[1:04:47] SPEAKER: And then a friend of the show, Jeff Gershman,
[1:04:49] SPEAKER: did as part of his ranking of Nintendo games,
[1:04:53] SPEAKER: he got to Gumshoe a few weeks ago.
[1:04:55] SPEAKER: And because I've talked so much shit
[1:04:56] SPEAKER: about Gumshoe over the years, everybody like dumped it to me
[1:05:00] SPEAKER: and watching him play Gumshoe made me think
[1:05:02] SPEAKER: maybe I'm wrong about Gumshoe.
[1:05:04] SPEAKER: - Oh, okay.
[1:05:05] SPEAKER: - Yeah, so if you wanna play Gumshoe sometime, let me know.
[1:05:08] SPEAKER: I can set it up.
[1:05:10] SPEAKER: I think maybe, look, it's like Top Gun.
[1:05:13] SPEAKER: Maybe I just wasn't enough of a gamer back then
[1:05:15] SPEAKER: to land on the aircraft carrier successfully.
[1:05:18] SPEAKER: But now I can do it one or two out of five times, so.
[1:05:22] SPEAKER: - For a game about a hard-boiled detective in a trench coat,
[1:05:24] SPEAKER: there sure are a lot of like balloons and tropical,
[1:05:26] SPEAKER: like palm trees and stuff.
[1:05:28] SPEAKER: - Well, look, you go where the case takes you, man.
[1:05:31] SPEAKER: - Fair, that's true.
[1:05:32] SPEAKER: - And I think you had to shoot the pink balloons
[1:05:35] SPEAKER: or you had to jump into the pink balloon.
[1:05:37] SPEAKER: The way it worked was you made the guy jump.
[1:05:39] SPEAKER: It was kind of like one of those endless runner games
[1:05:44] SPEAKER: 'cause you can't stop him.
[1:05:45] SPEAKER: He's just always going right.
[1:05:47] SPEAKER: And you make him jump by shooting him,
[1:05:49] SPEAKER: but also you can shoot other stuff
[1:05:50] SPEAKER: like bottles that people hug at you.
[1:05:52] SPEAKER: - I didn't realize Gumshoe was an endless runner.
[1:05:55] SPEAKER: - Well, we didn't have endless runners then, right?
[1:05:57] SPEAKER: - That's true.
[1:05:57] SPEAKER: - Gumshoe was just a platformer.
[1:05:59] SPEAKER: - Way ahead of its time.
[1:06:00] SPEAKER: - Light gun platformer.
[1:06:02] SPEAKER: - But the last thing I was gonna say,
[1:06:03] SPEAKER: I guess my biggest revelation in messing with all this stuff
[1:06:07] SPEAKER: is how much my brain has been poisoned
[1:06:08] SPEAKER: in the intervening decades
[1:06:10] SPEAKER: by dealing with modern digital signals.
[1:06:14] SPEAKER: I am so attuned now to like,
[1:06:16] SPEAKER: okay, there's gonna be some kind of handshaking
[1:06:17] SPEAKER: going on here.
[1:06:18] SPEAKER: I've gotta make sure things are on the right input.
[1:06:19] SPEAKER: I probably need to turn these on in the right order.
[1:06:21] SPEAKER: If the console doesn't see a viable input on the other end,
[1:06:25] SPEAKER: it's probably gonna drop to like a low resolution.
[1:06:27] SPEAKER: You know what I mean?
[1:06:28] SPEAKER: There's so many quote-unquote "smart things" going on
[1:06:30] SPEAKER: with devices talking to each other now
[1:06:32] SPEAKER: that it's been kind of weirdly retroactively revelatory,
[1:06:37] SPEAKER: I would say, to like go back to a time when it was like,
[1:06:40] SPEAKER: oh, this is just an electrical signal coming out of here.
[1:06:42] SPEAKER: Like I just plugged this connector into this plug
[1:06:45] SPEAKER: and it fits snugly.
[1:06:46] SPEAKER: There's no retention mechanism.
[1:06:48] SPEAKER: It's just a plug.
[1:06:49] SPEAKER: It's just sending electricity.
[1:06:50] SPEAKER: It's just gonna send the electricity,
[1:06:52] SPEAKER: whether the TV is on or not,
[1:06:54] SPEAKER: whether it's on the right input or not.
[1:06:55] SPEAKER: You know what I mean?
[1:06:56] SPEAKER: Like working with these types of analog signals is like,
[1:06:58] SPEAKER: it's been a weird kind of history lesson
[1:07:00] SPEAKER: to go back to this stuff.
[1:07:01] SPEAKER: - Well, so agreed.
[1:07:04] SPEAKER: And the other thing I noticed,
[1:07:06] SPEAKER: so I had a VCR, I mean, I'm using a VCR in my pipeline here,
[1:07:10] SPEAKER: and I had some VHS tapes around
[1:07:12] SPEAKER: that I'd been doing some archival type stuff on before.
[1:07:16] SPEAKER: And it's kind of amazing.
[1:07:18] SPEAKER: I had forgotten what it's like to watch stuff
[1:07:20] SPEAKER: without like digital compression artifacts
[1:07:23] SPEAKER: because our brains filter out those compression artifacts.
[1:07:25] SPEAKER: Now, like we're so used to seeing a little bit
[1:07:27] SPEAKER: of square shimmeriness and blockiness.
[1:07:30] SPEAKER: And like even on the newer codecs, like AB1H265,
[1:07:34] SPEAKER: you still see different kinds of artifacts.
[1:07:36] SPEAKER: They're not as bad as like the MPEG-2,
[1:07:38] SPEAKER: the old MPEG-2 artifacts that were on DVDs,
[1:07:40] SPEAKER: but you forget how much your brain filters that stuff out.
[1:07:44] SPEAKER: And to me, the hardest part of this whole thing has been,
[1:07:51] SPEAKER: so there's, I think there's a vertical
[1:07:53] SPEAKER: and horizontal sync knobs on the back
[1:07:55] SPEAKER: that you can access with a screw.
[1:07:58] SPEAKER: But on the front, there's like saturation and color,
[1:08:00] SPEAKER: color, which is I think saturation and tint,
[1:08:03] SPEAKER: which is like the hue where you can change,
[1:08:05] SPEAKER: like make blue look green or pink or whatever.
[1:08:10] SPEAKER: Getting the saturation right,
[1:08:11] SPEAKER: I don't remember what it was supposed to look like,
[1:08:13] SPEAKER: and I don't have like a navy essentials to plug into this.
[1:08:15] SPEAKER: - Right. - To calibrate it.
[1:08:17] SPEAKER: - Yeah, I've had a similar experience with this thing.
[1:08:18] SPEAKER: 'Cause I mean, in this case,
[1:08:20] SPEAKER: the settings are digital, not knobs like yours,
[1:08:22] SPEAKER: but it's the same type of thing of like,
[1:08:24] SPEAKER: how sharp is the CRT supposed to look?
[1:08:26] SPEAKER: Like, where is the brightness supposed to be?
[1:08:28] SPEAKER: I don't remember what the like perceptually,
[1:08:30] SPEAKER: like what are the ideal settings on this thing?
[1:08:32] SPEAKER: I don't, I've lost that kind of sense memory.
[1:08:35] SPEAKER: - Well, and then, so the other interesting thing
[1:08:37] SPEAKER: that came out as I was, so my daughter,
[1:08:40] SPEAKER: we were talking about how it works, right?
[1:08:41] SPEAKER: Versus like how a flat screen TV works.
[1:08:44] SPEAKER: And as I was explaining,
[1:08:47] SPEAKER: I realized that there's a bunch of stuff about this
[1:08:49] SPEAKER: that I don't actually really understand.
[1:08:50] SPEAKER: Like, I know there's an electron gun in the back
[1:08:52] SPEAKER: and that excites some phosphors in the front of the thing,
[1:08:54] SPEAKER: but how does that make color?
[1:08:56] SPEAKER: And how does one signal coming over the airwaves
[1:09:00] SPEAKER: make every TV, regardless of how big or small it is,
[1:09:03] SPEAKER: work the same way?
[1:09:04] SPEAKER: And it turns out when you go look for that stuff,
[1:09:07] SPEAKER: there's a lot of like weirdly esoteric,
[1:09:09] SPEAKER: almost like approaching lost knowledge.
[1:09:12] SPEAKER: And there are YouTube videos about this
[1:09:15] SPEAKER: and there are obviously Wikipedia articles
[1:09:16] SPEAKER: and there's people who've talked about
[1:09:18] SPEAKER: how the technology works,
[1:09:19] SPEAKER: but there's a lot of like rubber meets the road of,
[1:09:23] SPEAKER: like if you wanted to manufacture a new CRT today,
[1:09:25] SPEAKER: I don't, I think we're almost to the point
[1:09:27] SPEAKER: that there's not enough people left
[1:09:29] SPEAKER: that understand how to make these,
[1:09:30] SPEAKER: that we'd be able to recreate this technology now
[1:09:34] SPEAKER: if we wanted to.
[1:09:34] SPEAKER: So it's kind of cool to own like a,
[1:09:36] SPEAKER: you know, it's like owning a coelacanth, right?
[1:09:40] SPEAKER: We got living fossils going here, which I like.
[1:09:43] SPEAKER: - Yeah, and they'll probably outlive us.
[1:09:45] SPEAKER: - I don't know about that.
[1:09:46] SPEAKER: - Actually, this is the last thing before we wrap up here.
[1:09:49] SPEAKER: You mentioned to me beforehand, you're going to upload,
[1:09:52] SPEAKER: you're gonna make an entry for your model
[1:09:53] SPEAKER: and upload some photos of it to the CRT database.
[1:09:56] SPEAKER: - I am, yeah.
[1:09:56] SPEAKER: - Are you going to follow through on that?
[1:09:57] SPEAKER: - I don't know, we'll see.
[1:09:58] SPEAKER: Now that you said it on the podcast, I probably have to.
[1:10:01] SPEAKER: I got to get a good place to take pictures.
[1:10:02] SPEAKER: - I think that's always the problem.
[1:10:03] SPEAKER: That's why I brought it up.
[1:10:04] SPEAKER: I was, the CRT database.com is what I'm talking about.
[1:10:07] SPEAKER: I was able to find that Toshiba on there
[1:10:08] SPEAKER: and got some pretty good information
[1:10:10] SPEAKER: about what it can do from that site.
[1:10:12] SPEAKER: So I was pretty bummed to find that your TV is not on there.
[1:10:15] SPEAKER: - Nope.
[1:10:16] SPEAKER: - But you can fix that.
[1:10:18] SPEAKER: - I can make it happen.
[1:10:19] SPEAKER: - Like you can add to the collective share of knowledge
[1:10:22] SPEAKER: in the world by documenting this 40 to 45 year old television.
[1:10:27] SPEAKER: - This is the worst shaming you've ever done to me, Brad.
[1:10:30] SPEAKER: - You need to do this for humanity.
[1:10:32] SPEAKER: - This is my penance for the VIM, all the VIM jokes.
[1:10:39] SPEAKER: Okay, I will find a place to take pictures and do that.
[1:10:41] SPEAKER: I'll make it happen.
[1:10:44] SPEAKER: And on that note, you can help us make it happen
[1:10:48] SPEAKER: by signing up for the Patreon.
[1:10:49] SPEAKER: Brad and Will Made a Tech Pod is a listener supported show.
[1:10:52] SPEAKER: We wouldn't be here without you, true listeners.
[1:10:55] SPEAKER: And we appreciate everyone's support.
[1:10:59] SPEAKER: If you would like to learn how to subscribe to the Patreon
[1:11:01] SPEAKER: and get access to the Discord
[1:11:02] SPEAKER: and get our monthly Patreon exclusive episodes,
[1:11:04] SPEAKER: where you heard us talk about the beginnings of this
[1:11:07] SPEAKER: a month ago, a little bit,
[1:11:09] SPEAKER: when we came back from the flea market.
[1:11:13] SPEAKER: I don't know if, I may or may not go tomorrow.
[1:11:15] SPEAKER: The next one is tomorrow.
[1:11:16] SPEAKER: Well, it's the day that you're,
[1:11:18] SPEAKER: if you're listening to this at midnight on Sunday
[1:11:21] SPEAKER: and you live in the Bay Area,
[1:11:22] SPEAKER: you can get up and be there at six o'clock in the morning.
[1:11:25] SPEAKER: - That's true.
[1:11:26] SPEAKER: - And be there when it happens.
[1:11:27] SPEAKER: I think that there's some listeners coming for this one.
[1:11:28] SPEAKER: So I should get my ass in gear and get up there,
[1:11:31] SPEAKER: but it's gonna be a challenge.
[1:11:34] SPEAKER: If you would like to learn how to subscribe to the show,
[1:11:36] SPEAKER: you can go to patreon.com/techpod.
[1:11:38] SPEAKER: It's five bucks a month.
[1:11:39] SPEAKER: It helps us immeasurably.
[1:11:40] SPEAKER: We really appreciate every listener.
[1:11:42] SPEAKER: - We certainly do.
[1:11:43] SPEAKER: - And we especially appreciate our executive producer
[1:11:46] SPEAKER: tier patrons, including Jason Lee, Andrew Slosky,
[1:11:51] SPEAKER: Jordan Lippett, Bunny Themed, Twinkle Twinkie,
[1:11:54] SPEAKER: David Allen, James Kamik, and Pantheon,
[1:11:57] SPEAKER: makers of the HS3 high-speed 3D printer.
[1:12:00] SPEAKER: Thank you all so, so much.
[1:12:01] SPEAKER: - Thank you.
[1:12:02] SPEAKER: - And on that note, we will be back next week
[1:12:04] SPEAKER: with another edition of the tech pod.
[1:12:08] SPEAKER: Always a pleasure, Brad.
[1:12:09] SPEAKER: - Thank you, same to you.
[1:12:10] SPEAKER: - And remember, please consider the environment
[1:12:11] SPEAKER: before printing this podcast.
[1:12:12] SPEAKER: Bye.
