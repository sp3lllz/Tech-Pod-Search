---
episode: 326
title: 316: I Don't Like the Sparkle
date: 2025-12-07
guests: none
duration: 1:02:54
---

[00:00] SPEAKER: - Sounds like you've got the old NTFS dirty bit over there.
[00:03] SPEAKER: - Look, the number of times Windows crashes
[00:06] SPEAKER: and I reboot and I reboot into Linux,
[00:08] SPEAKER: I'm like, why the hell is going on?
[00:09] SPEAKER: My stuff isn't working.
[00:11] SPEAKER: And then I look at all my mounts
[00:12] SPEAKER: and all my NTFS mounts are dirty and thus unwriteable.
[00:16] SPEAKER: And that causes unpredictable things
[00:18] SPEAKER: for things like my Steam library is three.
[00:21] SPEAKER: That's how many times it's happened in the last week.
[00:23] SPEAKER: - Last thing you want is an unclean Windows install.
[00:26] SPEAKER: - I mean, the unclean Windows install,
[00:28] SPEAKER: we're referencing last week's episode
[00:31] SPEAKER: of Dual Boot Diaries, I guess.
[00:32] SPEAKER: - Which I listened to very excitedly.
[00:34] SPEAKER: That at some point you mentioned me
[00:36] SPEAKER: and said I must be yelling at my radio,
[00:37] SPEAKER: but in fact I was not.
[00:39] SPEAKER: I was excitedly listening to what you were talking about
[00:41] SPEAKER: because there were like three different things in there.
[00:42] SPEAKER: I was like, oh, I know how to fix that.
[00:43] SPEAKER: I can, I should hit him up.
[00:45] SPEAKER: But that NTFS dirty bit thing, A, sucks.
[00:49] SPEAKER: - Yeah.
[00:50] SPEAKER: - B can be fixed with a single command.
[00:52] SPEAKER: - Oh, can you fix it without having to boot
[00:53] SPEAKER: back into Windows?
[00:54] SPEAKER: - All it is is a flag being set on the NTFS volume
[00:57] SPEAKER: that says this was not mounted,
[00:59] SPEAKER: this was not unmounted or shut down properly.
[01:00] SPEAKER: Like don't remount it 'cause it might be fucked up.
[01:03] SPEAKER: You literally can run one command
[01:04] SPEAKER: to just clear that flag and then it's fine.
[01:06] SPEAKER: - Oh my God.
[01:07] SPEAKER: - That would have fixed all your problems.
[01:09] SPEAKER: You just needed to boot into something that you could run.
[01:11] SPEAKER: - Well, okay, so that, the dirty bit
[01:14] SPEAKER: wasn't what caused me to reinstall Windows.
[01:16] SPEAKER: The thing that caused me to reinstall Windows
[01:18] SPEAKER: was that I messed up the boot partition
[01:19] SPEAKER: and I didn't, rather than just fixing it the easy way
[01:23] SPEAKER: by booting into the Windows installer and doing that,
[01:26] SPEAKER: which I did the second time it broke.
[01:28] SPEAKER: - Yeah, so that was another, I guess,
[01:29] SPEAKER: I didn't know you can use the installer for this,
[01:31] SPEAKER: but you can also just make a Windows recovery USB stick
[01:34] SPEAKER: that will do stuff like that for you.
[01:35] SPEAKER: So that was another, again, I wasn't yelling at the radio.
[01:38] SPEAKER: I was like excitedly going,
[01:39] SPEAKER: "Oh, I need to tell him about a thing."
[01:42] SPEAKER: I forget how you do it, you can Google this,
[01:43] SPEAKER: but there is a way to create a Windows recovery USB
[01:46] SPEAKER: from within Windows and then you just boot off of that
[01:48] SPEAKER: in the future when you have boot problems in Windows
[01:50] SPEAKER: and it will fix those.
[01:52] SPEAKER: - Honestly, the automatic startup repair thing
[01:54] SPEAKER: has never once worked for me in the last,
[01:57] SPEAKER: since they implemented it like 15 years ago, 20 years ago,
[02:00] SPEAKER: but you can do it manually.
[02:01] SPEAKER: Like you can just wipe that partition entirely
[02:03] SPEAKER: and then create a new MBR or new UEFI boot thing
[02:08] SPEAKER: and then it's doable.
[02:10] SPEAKER: - Yeah, this is from people on our Linux channel.
[02:12] SPEAKER: Like the purpose of that thing
[02:13] SPEAKER: is to fix broken Windows bootloader.
[02:15] SPEAKER: - Yeah.
[02:16] SPEAKER: - So I would recommend go making one of those.
[02:18] SPEAKER: - I like it.
[02:19] SPEAKER: - Yeah, there's something else, but I've forgotten what it was.
[02:22] SPEAKER: - I had to get up this morning
[02:23] SPEAKER: just before we started this podcast
[02:25] SPEAKER: because I have had an outstanding project
[02:27] SPEAKER: that I haven't done yet.
[02:28] SPEAKER: - That is.
[02:29] SPEAKER: - And I had to walk into the room with the thermostat
[02:31] SPEAKER: and manually reach out to it with my hand
[02:34] SPEAKER: and turn the knob.
[02:35] SPEAKER: - Welcome to living like us commoners.
[02:37] SPEAKER: - I don't know how I'm gonna deal with this.
[02:39] SPEAKER: I gotta, look, I gotta install a couple of Docker containers
[02:43] SPEAKER: and then I gotta flash some firmware.
[02:46] SPEAKER: It's all pretty rote, pretty straightforward.
[02:49] SPEAKER: - That's modern living.
[02:50] SPEAKER: Just gotta install a couple of Docker,
[02:51] SPEAKER: set up a couple of Docker containers to run your thermostat.
[02:55] SPEAKER: - Look, it's not a large house, I realize that.
[02:57] SPEAKER: It's like no more than maybe 15 steps to the thermostat
[02:59] SPEAKER: from anywhere in the house.
[03:01] SPEAKER: But when I'm sitting here at my desk
[03:03] SPEAKER: and I have to get up and I mean,
[03:05] SPEAKER: I guess I have wireless headphones,
[03:06] SPEAKER: so I don't have to take my headphones off again anymore.
[03:08] SPEAKER: Seems pretty lazy when I think about it, really.
[03:11] SPEAKER: - Nope.
[03:12] SPEAKER: Look, I'm sitting here thinking about
[03:13] SPEAKER: buying a Switch 2 controller and selecting for controllers
[03:16] SPEAKER: by which ones will wake up the system from the couch
[03:19] SPEAKER: 'cause not all of them do that still.
[03:20] SPEAKER: - I like those 8BitDo ones, 8BitDo ones.
[03:23] SPEAKER: - Yeah, those are shake to wake,
[03:26] SPEAKER: which I'm not sure how I feel about it.
[03:27] SPEAKER: - Shake to wake the controller?
[03:29] SPEAKER: - No, you know, to wake the system.
[03:30] SPEAKER: So the, is it 8BitDo or 8BitDo?
[03:33] SPEAKER: - Adam says do.
[03:34] SPEAKER: - Yes, that's where I, a decade of verbal muscle memory
[03:40] SPEAKER: was called into question when I heard him saying 8BitDo
[03:42] SPEAKER: recently, but it sounded like he,
[03:43] SPEAKER: it sounded like he had that on good authority,
[03:45] SPEAKER: so I'm inclined to think he's right.
[03:47] SPEAKER: - I believe he's had meetings with them before.
[03:49] SPEAKER: - Yeah, so I think that's probably actually the case,
[03:51] SPEAKER: but anyway, the recent 8BitDo controllers
[03:54] SPEAKER: with a firmware update will wake the Switch 2,
[03:56] SPEAKER: but not with a button.
[03:58] SPEAKER: You pick the controller up and shake it,
[04:00] SPEAKER: which offends my digital input sensibilities.
[04:03] SPEAKER: - My ultimate Bluetooth controller,
[04:06] SPEAKER: which is the controller I've used for the Switch 1
[04:08] SPEAKER: and Switch 2 is plugged in, like it has a little dock,
[04:13] SPEAKER: and the dock has one of their 2.4 gigahertz dongles in.
[04:17] SPEAKER: - Into the Switch?
[04:18] SPEAKER: - No, it's into the bottom of the dock.
[04:20] SPEAKER: - Right, but I mean, we're talking about the Switch,
[04:21] SPEAKER: not PC. - Plugging into the Switch
[04:22] SPEAKER: and now the Switch 2.
[04:23] SPEAKER: I also use it for the Steam Deck, honestly.
[04:25] SPEAKER: - Maybe that's different.
[04:26] SPEAKER: It might be different using that dongle.
[04:28] SPEAKER: - So yeah, when you use the dongle,
[04:30] SPEAKER: it shows up as a wired controller,
[04:31] SPEAKER: so you just press the center button like anything else.
[04:33] SPEAKER: - That would be the different,
[04:34] SPEAKER: oh, I didn't know you could use a 2.4 gigahertz for that.
[04:36] SPEAKER: - Uh-huh, it's great. - Interesting.
[04:38] SPEAKER: I think the shake to wake was strictly over Bluetooth,
[04:40] SPEAKER: like if you connect it as a Bluetooth controller
[04:42] SPEAKER: as if it's a pro controller or something.
[04:44] SPEAKER: - Why would that work when the button doesn't, though?
[04:46] SPEAKER: That's ridiculous. - I don't know, I have no idea.
[04:48] SPEAKER: It's the weirdest thing.
[04:49] SPEAKER: Apparently even the Switch 1 pro controller
[04:51] SPEAKER: will not wake the Switch 2.
[04:53] SPEAKER: - Yeah, I knew that, yeah.
[04:55] SPEAKER: - Speaking of not getting up to do things,
[04:58] SPEAKER: this is important functionality.
[05:01] SPEAKER: - I've thought about moving my Switch 2 dock
[05:04] SPEAKER: to the other side of the room.
[05:05] SPEAKER: I think we talked about this on the podcast a few weeks ago.
[05:07] SPEAKER: - Oh yes, the subterranean HDMI.
[05:10] SPEAKER: - Yeah, the Discord had a lot of ideas.
[05:12] SPEAKER: They were like, yeah, just run the Discord
[05:14] SPEAKER: around underneath, I mean, the HDMI around underneath.
[05:17] SPEAKER: Get a one-way fiber HDMI.
[05:20] SPEAKER: You can poke a tiny hole through
[05:22] SPEAKER: and put the ends on when you get set up,
[05:25] SPEAKER: and then you're good to go.
[05:27] SPEAKER: And I was like, that does sound pretty good.
[05:28] SPEAKER: And then I looked at what those fiber HDMI cables cost,
[05:30] SPEAKER: and I was like, I don't have 'em to pay that much, so.
[05:32] SPEAKER: - Yeah, well, I mean, I got one for pretty cheap,
[05:34] SPEAKER: like 50 bucks.
[05:35] SPEAKER: The problem is it doesn't work.
[05:36] SPEAKER: - Yeah, that seems bad.
[05:37] SPEAKER: - I was actually just Googling about this the other day
[05:39] SPEAKER: because I am back to wanting to play PC games
[05:42] SPEAKER: in the living room again recently,
[05:44] SPEAKER: and every single fiber HDMI cable you can find out there
[05:48] SPEAKER: is just nothing but people going,
[05:49] SPEAKER: and I had the same experience.
[05:50] SPEAKER: I bought two of them, and they both had the same thing.
[05:52] SPEAKER: Like, oh, this works,
[05:52] SPEAKER: but it drops connection every three minutes.
[05:54] SPEAKER: Like, I lose picture for five to 10 seconds
[05:57] SPEAKER: while it tries to re-handshake every couple of minutes,
[05:59] SPEAKER: and it's just, it's so close to being there,
[06:02] SPEAKER: but it's not quite there.
[06:03] SPEAKER: - Let me get you to share the good word
[06:05] SPEAKER: about moonlight and sunshine.
[06:06] SPEAKER: - Yeah, I just need to get something
[06:08] SPEAKER: that can run moonlight properly.
[06:10] SPEAKER: My TV sure ain't cutting it.
[06:12] SPEAKER: (upbeat music)
[06:40] SPEAKER: - Welcome to "Brad and Will Made a Tech Pod."
[06:42] SPEAKER: I'm Will.
[06:43] SPEAKER: - I'm Brad.
[06:44] SPEAKER: - Brad.
[06:46] SPEAKER: It's that time of month again.
[06:49] SPEAKER: - Is it?
[06:50] SPEAKER: - Well, I mean, no, we don't, it's like,
[06:52] SPEAKER: I was just trying, I didn't have anything to say.
[06:54] SPEAKER: I don't have a baby rejoinder for this one.
[06:56] SPEAKER: We are-
[06:57] SPEAKER: - It's that time of month when stuff is happening.
[06:59] SPEAKER: - Yeah, stuff and things have happened.
[07:01] SPEAKER: - Turns out to be kind of all times of month, actually.
[07:04] SPEAKER: - Yeah, we have, I don't know,
[07:07] SPEAKER: it's not exactly a news roundup.
[07:09] SPEAKER: It's kind of a deeper dive into some things
[07:11] SPEAKER: we've talked about a little bit before, some new things.
[07:16] SPEAKER: So we're doing a threefer here.
[07:18] SPEAKER: We're gonna talk more about DDR prices
[07:19] SPEAKER: 'cause some new stuff has come to light
[07:21] SPEAKER: and some new things are happening
[07:22] SPEAKER: and none of it's good for people
[07:25] SPEAKER: who like to build computers.
[07:26] SPEAKER: - I know we just talked about this recently,
[07:28] SPEAKER: although then it was a little more on a focus
[07:30] SPEAKER: on the impending storage pricing crisis
[07:32] SPEAKER: that seems to be coming and not the current DDR prices,
[07:35] SPEAKER: but some shit has gone down in the last day
[07:39] SPEAKER: that was so extreme
[07:41] SPEAKER: that we kind of couldn't not talk about it some more.
[07:45] SPEAKER: - Well, and I think that there's some more,
[07:47] SPEAKER: I mean, we talked about the downstream stuff before.
[07:48] SPEAKER: We talked about, well, we'll get into it.
[07:52] SPEAKER: We're also gonna talk about why the Steam Machine,
[07:55] SPEAKER: Valve's new standalone console,
[07:58] SPEAKER: Steam Deck without a screen, basically,
[08:01] SPEAKER: doesn't have HDMI 2.1.
[08:03] SPEAKER: - Yeah, Earth Technica has done some good reporting
[08:05] SPEAKER: and talking to Valve there.
[08:08] SPEAKER: And the answer may surprise you.
[08:09] SPEAKER: - And then I also wanna talk about a thing
[08:11] SPEAKER: that has bothered me recently as some,
[08:15] SPEAKER: well, there's been a lot of AI encroaching in places
[08:17] SPEAKER: that are a pain in the ass to turn off.
[08:20] SPEAKER: Specifically, I use Firefox.
[08:21] SPEAKER: I've used Firefox for a long time.
[08:23] SPEAKER: I've given Firefox money, Mozilla money in the past.
[08:25] SPEAKER: - Really?
[08:26] SPEAKER: - They came to me and asked for money recently
[08:28] SPEAKER: as basically the same day I went through
[08:31] SPEAKER: a really involved process to turn off all of the AI crap
[08:35] SPEAKER: that they've added to Firefox.
[08:37] SPEAKER: And I didn't give them money.
[08:38] SPEAKER: I'm not giving them money while they're adding AI stuff.
[08:40] SPEAKER: And I sent them a note that said that.
[08:41] SPEAKER: So I would encourage you to do the same
[08:42] SPEAKER: if you feel that way.
[08:43] SPEAKER: - You're not the only Firefox user I know
[08:45] SPEAKER: who has gone through this same process in the last few days
[08:48] SPEAKER: of jumping through some hoops to pull that shit out of there.
[08:51] SPEAKER: - Yeah, and then the other side of this
[08:53] SPEAKER: is that Sean Hollister at The Verge
[08:56] SPEAKER: has been writing about Google's AI news bot.
[08:59] SPEAKER: So this is the thing that creates the headlines in news,
[09:01] SPEAKER: has been munging up people's headlines
[09:04] SPEAKER: by making AI summaries of the stories into the headlines.
[09:07] SPEAKER: We'll talk about it.
[09:08] SPEAKER: Anyway, let's kick off with the fun stuff, the DDR prices.
[09:13] SPEAKER: - Yes, fun.
[09:14] SPEAKER: - Hashtag fun.
[09:15] SPEAKER: - I got to tell you, man, I am coming here fresh off of,
[09:18] SPEAKER: this is early Friday morning that we were recording this.
[09:21] SPEAKER: I'm coming in here fresh off of having watched
[09:23] SPEAKER: Gamers Nexus' new video, which just went up
[09:24] SPEAKER: early this morning.
[09:25] SPEAKER: - Yeah, Steve has feelings about this.
[09:27] SPEAKER: - In which, man, Steve is on one in that video
[09:30] SPEAKER: like I have not seen before.
[09:32] SPEAKER: He is seriously at his most CNBC, like Jim Cramer,
[09:35] SPEAKER: rant-ist that I have ever seen.
[09:38] SPEAKER: Like he is really just going at it.
[09:40] SPEAKER: - The difference is that Steve understands
[09:43] SPEAKER: the things he's talking about and I don't think
[09:44] SPEAKER: Jim Cramer ever has.
[09:45] SPEAKER: - To be clear, I am very specifically talking about
[09:47] SPEAKER: the presentation style, not the content,
[09:49] SPEAKER: 'cause I would not credit Jim Cramer
[09:53] SPEAKER: in terms of expertise in any way,
[09:54] SPEAKER: but it was very much the ranting about the merger
[09:58] SPEAKER: of government and industry and the screwing over,
[10:02] SPEAKER: if not full-on destruction of the American consumer.
[10:05] SPEAKER: - Yeah, so the thing, we talked about this
[10:08] SPEAKER: a little bit a couple weeks ago when it first started
[10:10] SPEAKER: coming to light and prices started going up,
[10:12] SPEAKER: but there's a global RAM shortage caused by the rise
[10:17] SPEAKER: of AI data, so the incredible amount of AI data center
[10:20] SPEAKER: growth that's happening right now.
[10:22] SPEAKER: - Yeah, can I real quick jump in here?
[10:23] SPEAKER: I know AI is A, definitely culpable for a lot of the stuff,
[10:28] SPEAKER: and B, also kind of the most obvious target,
[10:30] SPEAKER: but we should probably be clear here,
[10:33] SPEAKER: even if the AI bubble bursts tomorrow,
[10:36] SPEAKER: data centers are not going away.
[10:39] SPEAKER: Data centers run all of the services that everybody
[10:41] SPEAKER: in the world uses constantly now,
[10:42] SPEAKER: so this seems like it's going to be some degree of problem,
[10:46] SPEAKER: whether or not the AI business sticks around
[10:49] SPEAKER: in some ongoing fashion.
[10:50] SPEAKER: - There's a large difference in scale, though.
[10:52] SPEAKER: This is a Wendell topic over level one techs,
[10:56] SPEAKER: but the construction of AI data centers
[10:59] SPEAKER: requires a ton more power, and because of the way those,
[11:05] SPEAKER: especially the ones that they're using to train models work,
[11:09] SPEAKER: they need an incredible amount of RAM
[11:11] SPEAKER: compared to a normal data center that's a bunch of servers
[11:14] SPEAKER: that are sliced up into virtual servers, basically.
[11:16] SPEAKER: - That's fair, even when you see people out there
[11:18] SPEAKER: talking about speccing out home AI workstations
[11:21] SPEAKER: for training workloads and so forth,
[11:23] SPEAKER: you see them talking about buying 128 gig of RAM,
[11:26] SPEAKER: 256 gig of RAM.
[11:27] SPEAKER: - Yeah, and those big racks, I can't remember
[11:31] SPEAKER: what the big racks that NVIDIA cells have,
[11:33] SPEAKER: but I want to say it was something like four terabytes
[11:35] SPEAKER: of RAM for a full-height data center rack, right?
[11:42] SPEAKER: So the thing about RAM, and I apologize
[11:45] SPEAKER: 'cause I've talked about this multiple places,
[11:47] SPEAKER: and I'm not sure I remember how much we got into it here,
[11:50] SPEAKER: but the thing about RAM is there's three companies
[11:53] SPEAKER: that make RAM, SK Hynix, Samsung, and Micron.
[11:57] SPEAKER: Like the manufacturer, the actual RAM chips,
[11:59] SPEAKER: the DCs, five, six, whatever, RAM chips.
[12:03] SPEAKER: And that supply that they can make is relatively constrained
[12:07] SPEAKER: once they get up to the maximum production
[12:09] SPEAKER: for any particular type of RAM.
[12:11] SPEAKER: So that market has traditionally been really, really stable
[12:14] SPEAKER: outside of natural disasters and stuff like that.
[12:16] SPEAKER: So the prices follow a pretty fixed curve,
[12:20] SPEAKER: kind of in the same way that the console business
[12:22] SPEAKER: has early peaks at the start of the generation
[12:25] SPEAKER: and then kind of tails off until the next generation
[12:27] SPEAKER: of hardware comes out, right?
[12:28] SPEAKER: And it's a similar kind of shaped curve for RAM pricing.
[12:32] SPEAKER: Typically, the new generation of RAM comes out,
[12:35] SPEAKER: it's really expensive, that supply is low at the beginning,
[12:38] SPEAKER: production ramps up, we get a wide proliferation of products
[12:42] SPEAKER: and then the prices go down until they stop manufacturing
[12:45] SPEAKER: and then it starts to go back up again
[12:47] SPEAKER: because the supply dwindles.
[12:48] SPEAKER: - Yeah, and we should mention a corollary to this.
[12:50] SPEAKER: We talked about this some when Adam was on
[12:52] SPEAKER: about your visit to the Intel fab recently.
[12:55] SPEAKER: Fabrication capacity is not something
[12:57] SPEAKER: that you just spin up more of on a lark.
[12:59] SPEAKER: - No. - It is extraordinarily
[13:02] SPEAKER: expensive and slow to ramp up more production.
[13:05] SPEAKER: So it's not like these companies can just be like,
[13:06] SPEAKER: hey, let's throw another couple of production lines on
[13:09] SPEAKER: so we can keep supplying the consumer DDR5 market.
[13:11] SPEAKER: Like that's not going to happen.
[13:13] SPEAKER: - Well, it's worth saying these aren't cutting edge fabs,
[13:20] SPEAKER: right, it's not like Intel's 18A process in Arizona,
[13:25] SPEAKER: it's not like TSMC's four nanometer process
[13:27] SPEAKER: we talked about where they're using bleeding edge technology
[13:32] SPEAKER: and they're doing incredibly small process size, right?
[13:37] SPEAKER: It's more mainstream than that.
[13:40] SPEAKER: But these companies are traditionally very conservative.
[13:43] SPEAKER: They don't adjust to market conditions.
[13:46] SPEAKER: They make their production schedules
[13:47] SPEAKER: are done well in advance.
[13:48] SPEAKER: They sell a lot of their product
[13:50] SPEAKER: in contracts years in advance.
[13:52] SPEAKER: So like Nvidia or Lenovo or Dell or HP
[13:56] SPEAKER: will buy X amount of RAM from Micron or Samsung
[13:59] SPEAKER: or SK Hynix or someone and they buy that in bulk
[14:04] SPEAKER: and they buy that in contracts years in advance, right?
[14:06] SPEAKER: So that amount of that production
[14:07] SPEAKER: is already claimed and gone, right?
[14:09] SPEAKER: They can't, like they have to make that
[14:11] SPEAKER: or else they're going to be in default to their contracts
[14:13] SPEAKER: and they have problems.
[14:16] SPEAKER: Then there's stuff like data centers, right?
[14:18] SPEAKER: So that sells in a different channel
[14:20] SPEAKER: and the data center people say,
[14:21] SPEAKER: okay, we're building a 100 megawatt data center.
[14:23] SPEAKER: We need 400 exabytes of memory or whatever, right?
[14:27] SPEAKER: So when can you supply that and how can you get it to us?
[14:29] SPEAKER: And we want a package like this and blah, blah, blah.
[14:32] SPEAKER: And then the Slack traditionally has gone
[14:34] SPEAKER: to consumer market, the stuff that you buy at Best Buy
[14:37] SPEAKER: and Micro Center and Newegg and Amazon and places like that.
[14:43] SPEAKER: And that's often sold through to people like Patriot
[14:46] SPEAKER: and Crucial was one of those, Corsair sells RAM,
[14:49] SPEAKER: like all these companies, G.Skill,
[14:52] SPEAKER: all of these companies that sell enthusiast RAM
[14:54] SPEAKER: or whether it's enthusiast or just plain green sticks,
[14:57] SPEAKER: it's all sold through to these relatively smaller companies
[15:01] SPEAKER: that do direct to consumer business.
[15:04] SPEAKER: Now, what's happened is the increase
[15:08] SPEAKER: in data center RAM requirements have gone up to the point
[15:12] SPEAKER: that instead of just selling that RAM through HP and Dell
[15:16] SPEAKER: and Super Micro and all the companies that do rack sales,
[15:23] SPEAKER: now the data center people are just buying
[15:25] SPEAKER: the RAM allocations up directly
[15:27] SPEAKER: and companies like Nvidia are saying,
[15:29] SPEAKER: hey, we aren't going to sell RAM for you
[15:32] SPEAKER: on these processes anymore.
[15:35] SPEAKER: If you want the RAM, you have to get it directly
[15:37] SPEAKER: from the manufacturer.
[15:37] SPEAKER: - Interesting. - Yeah.
[15:39] SPEAKER: - Who handles the assembly though?
[15:40] SPEAKER: 'Cause it still needs to go on some kind of--
[15:42] SPEAKER: - Nvidia says, hey, get us the thing,
[15:44] SPEAKER: we'll put it on the board.
[15:45] SPEAKER: - And you really? - You have to source it.
[15:47] SPEAKER: Yeah. - That's crazy.
[15:48] SPEAKER: - Yeah.
[15:50] SPEAKER: So, and what's happened is the amount of investment
[15:54] SPEAKER: in data centers right now, like OpenAI is talking
[15:57] SPEAKER: about building a trillion dollars worth of data centers.
[15:59] SPEAKER: Where they're gonna get the money for that, who knows.
[16:01] SPEAKER: If you wanna know more about that,
[16:02] SPEAKER: read Ed Zitron's newsletter.
[16:04] SPEAKER: He talks about the fact that they're blowing through,
[16:07] SPEAKER: they've blown through venture capital.
[16:09] SPEAKER: They're now at a scale that the investment banks
[16:12] SPEAKER: won't fool with them anymore 'cause they have so much money
[16:14] SPEAKER: in the pipe and they're onto sovereign wealth funds.
[16:17] SPEAKER: And after they run out of sovereign wealth funds,
[16:18] SPEAKER: it remains to be seen where the money comes from because--
[16:21] SPEAKER: - That's when society finishes eating itself quite frankly.
[16:25] SPEAKER: People will get into that later.
[16:27] SPEAKER: - So anyway, like the scale at which they're building
[16:32] SPEAKER: data centers right now is such that power companies
[16:35] SPEAKER: in parts of the country are saying, hey,
[16:36] SPEAKER: you can't build any more data centers here.
[16:38] SPEAKER: We can't continue to service these without degrading
[16:42] SPEAKER: the experience, the service for the humans
[16:45] SPEAKER: that use our product, right?
[16:46] SPEAKER: So Pennsylvania's power company, West Pennsylvania's,
[16:48] SPEAKER: or East Pennsylvania's power company said,
[16:50] SPEAKER: no more data centers, you can't build any more here.
[16:54] SPEAKER: And we're seeing this enormous rollout and it's absorbed
[16:57] SPEAKER: so much of the RAM capacity that the consumer space
[17:02] SPEAKER: is getting squeezed and as a result, RAM prices have
[17:05] SPEAKER: more than doubled, like at this point,
[17:09] SPEAKER: I think when I looked the other day,
[17:11] SPEAKER: a 64 gig set of DDR5 6000, so like not JetEx spec,
[17:17] SPEAKER: but basic, like your basic enthusiast RAM cost 400 bucks.
[17:23] SPEAKER: - Yeah, 6000 is what I put in this machine
[17:25] SPEAKER: two and a half years ago.
[17:26] SPEAKER: So it's like hardly, it's not even close to bleeding edge.
[17:29] SPEAKER: - Mm-mm, it's basically the, hey, here's what Intel
[17:33] SPEAKER: and AMD recommend for your enthusiast CPUs.
[17:36] SPEAKER: And a year ago that cost 125, 150 bucks.
[17:41] SPEAKER: - Yeah, like literally the reason I put 64 in this machine
[17:44] SPEAKER: and not 32 is that at the time the price difference
[17:47] SPEAKER: was like not nothing, but it was pretty minuscule.
[17:50] SPEAKER: It was, like you said, it was well under $200,
[17:52] SPEAKER: like 150, 160, 190 for the very fast.
[17:57] SPEAKER: - For the nice stuff with lights, yeah.
[17:58] SPEAKER: - 64 gig and that's, yeah, a thing of the past.
[18:02] SPEAKER: Yeah, 32 gig, sorry, 32 gig kits now are costing $400,
[18:07] SPEAKER: not 64 gig kits, 64 gig kits are much more expensive.
[18:11] SPEAKER: - You're seeing a bunch of headlines now.
[18:12] SPEAKER: I mean, these are somewhat sensationalized headlines,
[18:15] SPEAKER: but it's like, oh, 64 gig of RAM now costs more
[18:17] SPEAKER: than a PlayStation 5, stuff like that,
[18:18] SPEAKER: or a PlayStation 5 Pro.
[18:20] SPEAKER: - I don't think that's, I don't think that's that far off.
[18:25] SPEAKER: Yeah, a 64 gig kit of G.Skill 6000 mega transfer RAM
[18:30] SPEAKER: that's expo and XMP is $619 on Amazon today.
[18:35] SPEAKER: - Fucking crazy, that's like more
[18:37] SPEAKER: than many graphics cards were.
[18:38] SPEAKER: All the graphics cards, as we've said before,
[18:40] SPEAKER: are also affected by this because they have RAM on them.
[18:42] SPEAKER: - It's to this, well, the RAM that's used for graphics card
[18:45] SPEAKER: is less affected 'cause it is a different kind of RAM.
[18:48] SPEAKER: - Yeah, yeah, although AMD just announced their,
[18:50] SPEAKER: it's not a lot of big bump,
[18:51] SPEAKER: but they are bumping the cost of their 1970 cards
[18:54] SPEAKER: by a little bit. - I think everything,
[18:55] SPEAKER: we're gonna see bumps that uses RAM,
[18:57] SPEAKER: including SSDs and hard drives,
[18:59] SPEAKER: everything that uses RAM is gonna get more expensive.
[19:05] SPEAKER: So the other thing about this is,
[19:07] SPEAKER: the other thing that's happened is this makes the cost
[19:10] SPEAKER: of DDR4 hasn't gone up yet.
[19:14] SPEAKER: So those AM4 systems that are hanging on.
[19:18] SPEAKER: Like you can build an AM4 system that has a video card
[19:21] SPEAKER: and 32 gigs of RAM for less than what 64 gigs
[19:26] SPEAKER: of DDR5 costs right now. - Interesting.
[19:29] SPEAKER: - Like it is wild. - Like what speed of DDR4?
[19:32] SPEAKER: - It's gonna be like 3,200 or 3,500 or something.
[19:35] SPEAKER: - I'm not sure, what was the high end that DDR4 topped out
[19:37] SPEAKER: at stably before we moved on to DDR5?
[19:40] SPEAKER: Like I think they were getting close to 4,000.
[19:42] SPEAKER: - I think the fastest I ran was 3,600.
[19:45] SPEAKER: - Yeah, I think stable, that's probably about right.
[19:47] SPEAKER: - But yeah, you can get a G.Skill Trident Z kit DDR4
[19:54] SPEAKER: for 204 bucks right now.
[19:55] SPEAKER: That's even gone up a little bit in the last week.
[19:57] SPEAKER: - For what capacity? - 32 gigs.
[19:59] SPEAKER: - Oh, okay, like that's, I mean, it sucks
[20:00] SPEAKER: that this is necessary, but that if you badly need
[20:03] SPEAKER: to build a computer right now, that's not the worst option.
[20:05] SPEAKER: - Yeah, 32 gigs is, I mean, look, that is a bad option.
[20:10] SPEAKER: I don't know, like what I do,
[20:13] SPEAKER: I think we're gonna see people making tough choices.
[20:15] SPEAKER: Like when this happened in the '90s, so in '93, I think,
[20:19] SPEAKER: or '94, there was a huge earthquake in Taiwan
[20:22] SPEAKER: that knocked a lot of the memory capacity off.
[20:26] SPEAKER: And as a result, you started seeing people doing crazy stuff
[20:29] SPEAKER: like IBM started building machines with eight RAM slots.
[20:32] SPEAKER: So if you wanted an eight-megabyte system,
[20:34] SPEAKER: you had eight one-megabyte chips in there.
[20:37] SPEAKER: And a lot of vendors were doing that
[20:38] SPEAKER: because it was easier to get those,
[20:40] SPEAKER: those one-megabyte chips were inexpensive,
[20:42] SPEAKER: whereas the four-megabyte SIMs, I guess, back then,
[20:48] SPEAKER: were crazy, crazy expensive.
[20:50] SPEAKER: So it's a weird, it's gonna be weird
[20:56] SPEAKER: for a little bit.
[20:57] SPEAKER: - Yeah, I mean, the difference here is that, I mean,
[20:59] SPEAKER: you've seen this in other areas, you know,
[21:01] SPEAKER: there were floods that took out hard drive capacity
[21:02] SPEAKER: in Thailand in the past.
[21:05] SPEAKER: The difference is that those were all unpredictable,
[21:07] SPEAKER: natural events.
[21:09] SPEAKER: All of this is self-inflicted.
[21:11] SPEAKER: - Yeah, well- - This is all by choice,
[21:12] SPEAKER: especially the actual news item today,
[21:14] SPEAKER: which we need to get to.
[21:15] SPEAKER: - Yeah, so the reason we're talking about this today
[21:17] SPEAKER: is on Wednesday of this week, Crucial, Micron,
[21:20] SPEAKER: who owns Crucial, the RAM,
[21:22] SPEAKER: the, I think, probably biggest consumer RAM vendor.
[21:25] SPEAKER: - Are they?
[21:27] SPEAKER: Probably up there.
[21:27] SPEAKER: - They're up there.
[21:28] SPEAKER: - Like, again, Micron is one of the three suppliers,
[21:30] SPEAKER: manufacturers of memory,
[21:32] SPEAKER: and Crucial is their kind of house brand.
[21:33] SPEAKER: It was their consumer-facing label for not just RAM,
[21:37] SPEAKER: but SSDs, which we'll get to.
[21:39] SPEAKER: - Yeah, and they've been around
[21:40] SPEAKER: for 20-plus years at this point.
[21:43] SPEAKER: Crucial, Micron's just shutting down Crucial
[21:45] SPEAKER: 'cause they'd rather sell direct to AI.
[21:46] SPEAKER: They'd rather use that inventory to sell to AI data centers.
[21:49] SPEAKER: - Yeah, yep, that is the long and the short of it.
[21:53] SPEAKER: Technically, that doesn't mean
[21:54] SPEAKER: they wouldn't still keep supplying ICs
[21:56] SPEAKER: to other, to the GSkills and Corsairs of the world,
[21:59] SPEAKER: but practically, it probably does mean that
[22:01] SPEAKER: because, well, why would they be doing this
[22:03] SPEAKER: if they were still willing to supply
[22:06] SPEAKER: to any consumer business in the first place?
[22:08] SPEAKER: - So my understanding of the way this market works
[22:10] SPEAKER: is that it's more complicated than that.
[22:11] SPEAKER: It's not, it's that production is bought years in advance.
[22:15] SPEAKER: Like, people are buying wafers of RAM chips years in advance
[22:19] SPEAKER: to the point that, like, Dell and Lenovo and HP
[22:22] SPEAKER: probably aren't going to be super affected
[22:24] SPEAKER: by these price changes for quite a while.
[22:25] SPEAKER: I mean, don't worry, they're gonna raise the prices
[22:30] SPEAKER: to meet market conditions because they can.
[22:33] SPEAKER: But, you know, the allotments for those big companies
[22:37] SPEAKER: that are buying millions and millions and millions
[22:39] SPEAKER: of terabytes of RAM every year are set well in advance.
[22:43] SPEAKER: And it's part of the non-SLAC space
[22:46] SPEAKER: that the RAM manufacturers have that they have to produce
[22:50] SPEAKER: and they know what they're selling it at and yada yada,
[22:52] SPEAKER: right, it's the, it's the stuff that normally
[22:57] SPEAKER: would go to the consumers, the GSkills and the Patriots
[22:59] SPEAKER: and the Crucials and all those companies
[23:04] SPEAKER: that is skin squeezed, right?
[23:08] SPEAKER: So the stuff that's on contract is gonna be sold
[23:11] SPEAKER: at contract for the rate that the contracts
[23:12] SPEAKER: were established at.
[23:13] SPEAKER: If you hadn't done your 2026 and 2027 memory allocations yet
[23:18] SPEAKER: when the prices started going up,
[23:20] SPEAKER: then you are really, really turbo fucked now.
[23:22] SPEAKER: - Cool.
[23:23] SPEAKER: - And I also think, like, while the big guys
[23:26] SPEAKER: are probably gonna be fine 'cause they're buying
[23:27] SPEAKER: an enormous volume, I think the folks like Framework
[23:30] SPEAKER: and System76 and all the kind of smaller, Razor,
[23:34] SPEAKER: all of the smaller enthusiast computing places
[23:38] SPEAKER: are gonna probably have problems.
[23:39] SPEAKER: So, 'cause their prices are gonna go up
[23:42] SPEAKER: to market price and that's rough.
[23:45] SPEAKER: - Yeah, yeah, I should just mention real quick here,
[23:47] SPEAKER: I mean, all of this discussion's been focused
[23:50] SPEAKER: on RAM because that's where the price inflation
[23:51] SPEAKER: is currently happening.
[23:52] SPEAKER: We did mention a couple of weeks ago
[23:54] SPEAKER: that SSDs are headed in the same direction.
[23:56] SPEAKER: Crucial, not a small player in the consumer SSD space.
[24:00] SPEAKER: - No, Crucial's a fairly big SSD vendor as well.
[24:03] SPEAKER: - Like the Crucial, I think P1 is the classic mid tier,
[24:06] SPEAKER: like, pretty good bang for the buck SSD
[24:09] SPEAKER: that has been around for several years now.
[24:11] SPEAKER: Like, they're not, you know, they're not SK Hynix
[24:15] SPEAKER: and Samsung and Western Digital Black level
[24:18] SPEAKER: of like, gamer performance, but they are like,
[24:20] SPEAKER: that Crucial has been a good solid mid tier,
[24:22] SPEAKER: like, run your Windows install SSD option for a while now.
[24:26] SPEAKER: So that going away as well is also pretty harmful.
[24:28] SPEAKER: - I'll actually go one step above that.
[24:31] SPEAKER: The Crucial T700, which was one of the early Gen 5
[24:34] SPEAKER: PCIe NVMEs, was one of the top performers.
[24:39] SPEAKER: It was up there with the very fastest.
[24:41] SPEAKER: So like, they have, yeah, it's a huge loss
[24:46] SPEAKER: for the enthusiasts.
[24:47] SPEAKER: I mean, they cater to multiple tiers
[24:49] SPEAKER: of the storage market as well, because it's bad.
[24:51] SPEAKER: - And I think, so there's two things
[24:54] SPEAKER: that worry me about this.
[24:54] SPEAKER: One is the obvious, the short term impacts
[24:56] SPEAKER: on people who need to buy RAM,
[24:58] SPEAKER: 'cause RAM is a thing that dies occasionally
[24:59] SPEAKER: and you have to buy new stuff.
[25:00] SPEAKER: So I hope for your sake that you stockpiled
[25:04] SPEAKER: a set of DDR5 sticks a few years ago and you're good to go.
[25:10] SPEAKER: I think I have a couple of sticks that I probably could RMA
[25:13] SPEAKER: that are a little hinky that I'm probably going to hit
[25:15] SPEAKER: the button on that I wasn't going to bother with before,
[25:17] SPEAKER: 'cause they were only 32 gigs or 16 gigs or something.
[25:19] SPEAKER: - Sure.
[25:21] SPEAKER: - The other thing is big giant companies like Micron
[25:25] SPEAKER: deciding to exit the consumer space
[25:27] SPEAKER: is a grim portent for the future, I think.
[25:31] SPEAKER: I think, you know, we've often said,
[25:33] SPEAKER: oh, Nvidia makes 10, 9% of its revenue, whatever,
[25:36] SPEAKER: from selling consumer GPUs, but each of the wafers
[25:41] SPEAKER: that they cut into 35, 40 GPUs could make 12 or 15
[25:47] SPEAKER: data center chips that are way more profitable, right?
[25:51] SPEAKER: And those are made up numbers, I'm not, I'm just saying.
[25:53] SPEAKER: Like each wafer that they're running through TSMC's
[25:57] SPEAKER: four nanometer process is something
[25:58] SPEAKER: that could be data center chips.
[26:00] SPEAKER: And every time they sell consumer chips instead,
[26:03] SPEAKER: they're leaving that money on,
[26:04] SPEAKER: they're leaving money on the table.
[26:05] SPEAKER: - Yeah, I mean, if you read the wording
[26:06] SPEAKER: of the Micron press release, they don't say
[26:08] SPEAKER: that the data center market is more profitable
[26:10] SPEAKER: or lucrative or whatever.
[26:12] SPEAKER: They use the term fastest growing.
[26:14] SPEAKER: - Yeah.
[26:15] SPEAKER: - So it doesn't matter if even consumer revenue
[26:17] SPEAKER: is increasing year over year,
[26:18] SPEAKER: data center revenue is increasing faster.
[26:20] SPEAKER: - Gotta pull all the money.
[26:21] SPEAKER: - Yes, it's the classic chasing growth forever.
[26:23] SPEAKER: Like this really gets into the angle
[26:25] SPEAKER: that this Gamers Nexus video takes
[26:27] SPEAKER: and I recommend you watch it.
[26:28] SPEAKER: It is that channel at its most political
[26:30] SPEAKER: that I have ever seen, like by far,
[26:32] SPEAKER: because he leads with, he leads with the,
[26:35] SPEAKER: and I am not surprised this is the case,
[26:37] SPEAKER: but I never thought to look into it before.
[26:39] SPEAKER: The number of government grants and tax breaks
[26:41] SPEAKER: that Micron has gotten over in recent years
[26:44] SPEAKER: are in the numerous numbers of billions,
[26:47] SPEAKER: both state and local tax breaks, chips act grants.
[26:50] SPEAKER: They are taking enormous amounts of public money
[26:53] SPEAKER: and using it to completely fuck the people
[26:56] SPEAKER: giving them the money.
[26:57] SPEAKER: - Well, and it's not just the consumer,
[26:59] SPEAKER: it's not just the enthusiast computing market,
[27:01] SPEAKER: which is relatively small, right?
[27:02] SPEAKER: It's also, this is also gonna trickle down
[27:05] SPEAKER: into everybody who has to buy a computer or a phone
[27:08] SPEAKER: or any kind of device that is thinking sand, right?
[27:14] SPEAKER: Which is like computers getting more expensive
[27:18] SPEAKER: is bad for the overall economy
[27:19] SPEAKER: because a lot of the work that we do
[27:21] SPEAKER: is based around computers.
[27:23] SPEAKER: The RAM vendors have gotten in trouble in the past
[27:25] SPEAKER: for colluding and fixing prices and all that stuff
[27:27] SPEAKER: and have been fined pretty mightily by the EU and the US.
[27:31] SPEAKER: - I actually got, I got money from a Corsair
[27:33] SPEAKER: class action settlement over price fixing many years ago.
[27:37] SPEAKER: So it's, okay, yes, that's not unheard of.
[27:40] SPEAKER: I would argue that that took place
[27:41] SPEAKER: in a very different world than we are now entering.
[27:44] SPEAKER: - Well, that's true.
[27:45] SPEAKER: - Which is also a point made in that video,
[27:47] SPEAKER: which is that Micron sure did give money
[27:49] SPEAKER: to the Trump Ballroom and Inaugural Committee, for example.
[27:52] SPEAKER: And there sure was a smiling handshake photo
[27:56] SPEAKER: of Micron CEO and Howard Lutnick on Twitter
[27:59] SPEAKER: the day this move was announced.
[28:01] SPEAKER: - Look, you bring your gold bar into the Oval Office
[28:03] SPEAKER: and everything's nice and legal now.
[28:05] SPEAKER: That's just the way it works.
[28:06] SPEAKER: - It's hard not to get angry watching the headlines
[28:08] SPEAKER: laid out, you know, six point whatever billion
[28:11] SPEAKER: from the CHIPS Act, two billion in state tax breaks
[28:13] SPEAKER: to this new fab facility.
[28:15] SPEAKER: I mean, like it is, it really smacks of classic socializing
[28:19] SPEAKER: of production and privatization of profits.
[28:22] SPEAKER: - Yeah.
[28:23] SPEAKER: - Which, look, man, I don't wanna get too political here,
[28:26] SPEAKER: but you know the Domino meme?
[28:27] SPEAKER: - No, it's the little one to the big one?
[28:29] SPEAKER: - Crucial exits of the consumer memory markets.
[28:34] SPEAKER: - Pretty small Domino, let's be real.
[28:36] SPEAKER: - Yeah.
[28:37] SPEAKER: - But like all this shit really adds.
[28:38] SPEAKER: This is just another, yet another feature
[28:40] SPEAKER: of the endless affordability crisis right now.
[28:42] SPEAKER: Like at some point, too many examples, too many like,
[28:46] SPEAKER: this is just societal death by a thousand cuts.
[28:48] SPEAKER: Like this is the kind of thing that really starts
[28:50] SPEAKER: to shake faith in the system generally
[28:53] SPEAKER: when enough of these happen.
[28:55] SPEAKER: - Well, it turns out corruption,
[28:57] SPEAKER: look, I learned about corruption from the Clone Wars, right?
[28:59] SPEAKER: When Ahsoka went to the Mandalore
[29:01] SPEAKER: to teach the Mandalorians about corruption.
[29:04] SPEAKER: It's a real good episode of a children's TV show.
[29:07] SPEAKER: - And small Domino, crucial exits to the market,
[29:09] SPEAKER: large Domino, society is overthrown.
[29:13] SPEAKER: - I've been yelling on the full nerd
[29:16] SPEAKER: about buying seeds a lot lately.
[29:19] SPEAKER: Seeds are always fungible, man.
[29:21] SPEAKER: Somebody next year, two years from now,
[29:23] SPEAKER: somebody's gonna be like, man, I really miss having turnips.
[29:25] SPEAKER: I'm gonna be like, buddy, I got you.
[29:26] SPEAKER: Here's some turnip seeds, go plant some turnips.
[29:29] SPEAKER: Yeah, now give me your gold bars.
[29:31] SPEAKER: - Whatever, man, we've been like,
[29:32] SPEAKER: the public has been funding vaccine research
[29:34] SPEAKER: and medical research that then-
[29:36] SPEAKER: - The public has been funding fossil fuel companies, Brad.
[29:39] SPEAKER: - That then entirely turns privatized
[29:41] SPEAKER: the second it brings money in for fucking decades.
[29:43] SPEAKER: - Yep, we fund fossil fuel companies,
[29:45] SPEAKER: we fund all sorts of stuff.
[29:47] SPEAKER: - Same shit, different industry.
[29:49] SPEAKER: - Yeah, it's great, good news.
[29:51] SPEAKER: - Yep, things are going great.
[29:53] SPEAKER: - But you know what is good?
[29:54] SPEAKER: The steam machine.
[29:55] SPEAKER: - Yeah, seems like it. - You know what's not great?
[29:57] SPEAKER: - What's that?
[29:58] SPEAKER: - HDMI 2.1.
[29:59] SPEAKER: - Well, okay, I'd say on a technical level,
[30:01] SPEAKER: HDMI 2.1 is pretty good.
[30:03] SPEAKER: Maybe perhaps on a, political's not the right term,
[30:05] SPEAKER: but on a policy level, maybe it's not great.
[30:09] SPEAKER: - Yeah, for people who are running Linux machines,
[30:11] SPEAKER: building Linux machines, HDMI 2.1,
[30:14] SPEAKER: a lot of the features are turned off.
[30:15] SPEAKER: I didn't know this.
[30:16] SPEAKER: - A bit inaccessible, yeah, I didn't either.
[30:18] SPEAKER: So I think they announced when the steam machine
[30:20] SPEAKER: was first delineated that it would not support HDMI 2.1,
[30:24] SPEAKER: and we've talked about this in the ancient past,
[30:26] SPEAKER: but 2.1 is the good one for playing video games.
[30:29] SPEAKER: - Yeah.
[30:30] SPEAKER: It's the first HDMI spec that allows 4K at 120 Hertz.
[30:35] SPEAKER: It's the one that introduced VRR, the variable refresh,
[30:38] SPEAKER: where the display refresh syncs to the frame rate output,
[30:42] SPEAKER: which is different from G-Sync and FreeSync,
[30:44] SPEAKER: we should be clear.
[30:45] SPEAKER: Like those are-
[30:46] SPEAKER: - Yeah, what's the difference there?
[30:47] SPEAKER: Do you know, I'm actually fuzzy on that.
[30:48] SPEAKER: - They're just different methods of doing the same thing.
[30:51] SPEAKER: - Oh, okay.
[30:52] SPEAKER: - Like G-Sync was first, FreeSync came along,
[30:53] SPEAKER: which is more open and kind of nominally backed by AMD.
[30:57] SPEAKER: HDMI 2.1 VRR is just another implementation
[31:01] SPEAKER: of the same concept.
[31:02] SPEAKER: And it's the one specific to the HDMI spec.
[31:05] SPEAKER: - Got it, okay.
[31:06] SPEAKER: - So like, and we'll get to this as we talk about
[31:09] SPEAKER: what the steam machine can do.
[31:10] SPEAKER: There are all kinds of examples of, for example,
[31:12] SPEAKER: consumer living room TVs that can do HDMI 2.1 VRR,
[31:15] SPEAKER: but cannot do FreeSync.
[31:17] SPEAKER: - Yeah, that makes sense.
[31:18] SPEAKER: - I guess that seems like that's also especially
[31:20] SPEAKER: even more common with receivers.
[31:22] SPEAKER: Like most, like any receiver with 2.1 support
[31:25] SPEAKER: is gonna take HDMI VRR,
[31:27] SPEAKER: but it will not necessarily take FreeSync.
[31:29] SPEAKER: - I would think you have to plug your stuff
[31:30] SPEAKER: directly into the TV to get FreeSync support.
[31:33] SPEAKER: - Yes, that's, there might be receivers
[31:35] SPEAKER: with FreeSync support, but that sounds unlikely to me.
[31:37] SPEAKER: But again, not even-
[31:38] SPEAKER: - Do people still use receivers?
[31:39] SPEAKER: - I do.
[31:40] SPEAKER: - You use an old one like me.
[31:41] SPEAKER: - Well, yeah, but it's not many people,
[31:44] SPEAKER: but it's A, it's still the only way to drive big speakers
[31:47] SPEAKER: unless you've got some kind of external amp.
[31:50] SPEAKER: B, unless you're getting some,
[31:52] SPEAKER: maybe I shouldn't say dodgy HDMI switcher.
[31:54] SPEAKER: I think there are some pretty good ones out there,
[31:56] SPEAKER: but it's like, it's probably the best supported way
[31:59] SPEAKER: to get way more HDMI ports on your TV.
[32:01] SPEAKER: - Yeah, but I guess my time of needing way more HDMI ports
[32:06] SPEAKER: has maybe gone away.
[32:07] SPEAKER: Like it's not like, in the old days,
[32:09] SPEAKER: I used to have five different streaming boxes
[32:10] SPEAKER: and a DVD player and some consoles,
[32:13] SPEAKER: so you could get all the different streaming services.
[32:14] SPEAKER: Now you just have all the streaming services
[32:16] SPEAKER: work on everything.
[32:17] SPEAKER: - Yeah, well, as somebody who has to cover
[32:18] SPEAKER: every video game system, I guess I'm an outlier,
[32:20] SPEAKER: but I had still four on a TV is still too limiting for me.
[32:24] SPEAKER: - Okay.
[32:25] SPEAKER: - Like six is fine.
[32:26] SPEAKER: Six, I can absolutely get away.
[32:27] SPEAKER: But also like, I have a PS3 hooked up in the living room,
[32:30] SPEAKER: 'cause what if I want to play a PS1 or PS2 game
[32:34] SPEAKER: on the TV at some point?
[32:35] SPEAKER: Like that might come in handy.
[32:37] SPEAKER: - I just grab it from the garage
[32:38] SPEAKER: and plug it in when I want that.
[32:40] SPEAKER: - I was thinking about searching for my copy
[32:43] SPEAKER: of "Metal Gear Solid 2" over the holiday break
[32:45] SPEAKER: and putting it in that PS3.
[32:46] SPEAKER: - Oh yeah, I played the Dreamcast in a few weeks ago.
[32:50] SPEAKER: - Right, it's nice to have.
[32:52] SPEAKER: Of course, I mean, that's where like the retro tank
[32:53] SPEAKER: and stuff like that comes in handy for old analog stuff.
[32:56] SPEAKER: - Or having an old TV, it turns out.
[32:58] SPEAKER: - Anyway, I digress.
[33:00] SPEAKER: Okay, the Steam Machine does not support HDMI 2.1.
[33:03] SPEAKER: Auto low latency mode is the other big one
[33:05] SPEAKER: on 2.1 for games people.
[33:07] SPEAKER: - That's the thing that switches the HDMI port to games mode
[33:10] SPEAKER: when you have a game device plugged in.
[33:11] SPEAKER: - It basically tells like the TV or the receiver
[33:13] SPEAKER: or whatever else in the chain.
[33:15] SPEAKER: Like, hey, turn off all of your post-processing
[33:17] SPEAKER: that adds latency.
[33:18] SPEAKER: Drop to your game mode or whatever you want to call it.
[33:21] SPEAKER: That's the thing that will give the best gaming experience
[33:23] SPEAKER: and then change back if you change to some other source.
[33:26] SPEAKER: - Got it.
[33:27] SPEAKER: - Anyway, like 2.1 has a lot of features
[33:29] SPEAKER: that are pretty useful for playing games.
[33:32] SPEAKER: I guess this is actually about a year and a half old,
[33:35] SPEAKER: but the Ars Technica story pointed back to this happening.
[33:40] SPEAKER: I think it was in February of 2024
[33:42] SPEAKER: and then added some new stuff talking to Valve
[33:44] SPEAKER: about the Steam Machine in particular.
[33:46] SPEAKER: The HDMI forum apparently declared
[33:47] SPEAKER: about a year and a half ago
[33:49] SPEAKER: that it would not allow open source implementations
[33:51] SPEAKER: of HDMI 2.1, so fucking consortiums, man.
[33:57] SPEAKER: - Why would they do this?
[33:59] SPEAKER: - I don't know what they're,
[34:00] SPEAKER: I didn't dig too much into their rationale
[34:02] SPEAKER: other than I assume it just has to be about control, right?
[34:05] SPEAKER: You know, they charge member companies
[34:08] SPEAKER: of the forum membership fees.
[34:10] SPEAKER: They charge licensing fees on HDMI hardware.
[34:13] SPEAKER: Like it is, you know, it's how they make their money.
[34:16] SPEAKER: - Yeah, there's no-- - That's my best guess.
[34:18] SPEAKER: - There's no public version of the 2.1 spec either.
[34:21] SPEAKER: - Yes, they don't publish the 2.1 spec.
[34:23] SPEAKER: And so I'm maybe getting a little car before the horse here.
[34:27] SPEAKER: I assume there's nothing stopping you legally
[34:31] SPEAKER: from reverse engineering 2.1 and implementing it yourself.
[34:35] SPEAKER: - God, we really need to watch "Helton Catch Fire."
[34:37] SPEAKER: - Yes, we really should.
[34:38] SPEAKER: But I don't even know how practical that is.
[34:41] SPEAKER: It may be that the 2.1 spec is of such complexity
[34:44] SPEAKER: that that's not even realistic to do.
[34:46] SPEAKER: - Well-- - But also,
[34:49] SPEAKER: this is where you get into the policy
[34:51] SPEAKER: or political aspect of this,
[34:52] SPEAKER: and I don't mean government political,
[34:53] SPEAKER: I mean like inter-entity relationship political here.
[34:57] SPEAKER: But like, even as like as a member company,
[35:00] SPEAKER: you would not wanna run afoul of the HDMI forum
[35:02] SPEAKER: by going out on your own and doing this
[35:06] SPEAKER: in spite of them, right?
[35:07] SPEAKER: Like that probably gets your membership pulled
[35:09] SPEAKER: or gets you penalized in some way that's unpalatable.
[35:12] SPEAKER: - What a load of crap though.
[35:15] SPEAKER: Like, I mean, so I assume somebody has done
[35:18] SPEAKER: a closed source blob implementation of HDMI 2.1,
[35:21] SPEAKER: 'cause I know that there's like ultra 4K Blu-ray players
[35:27] SPEAKER: that are running Linux in the underside, right?
[35:30] SPEAKER: - Maybe. - But then they probably
[35:31] SPEAKER: have some sort of closed-- - Well, yes.
[35:33] SPEAKER: The PS5, as we know, runs FreeBSD,
[35:35] SPEAKER: and that does HDMI 2.1, so clearly,
[35:38] SPEAKER: clearly open source operating systems,
[35:39] SPEAKER: there are ways to make it work in a way
[35:41] SPEAKER: that does not run afoul of the HDMI forum.
[35:43] SPEAKER: - But I mean, I guess my assumption is
[35:45] SPEAKER: that you can do a closed source implementation
[35:47] SPEAKER: on an open system, but they're not gonna let anybody
[35:50] SPEAKER: open source the HDMI 2.1 implementation
[35:52] SPEAKER: because they don't want it to be public
[35:54] SPEAKER: so that they can, then they can't charge people.
[35:55] SPEAKER: That sucks.
[35:56] SPEAKER: - Closed source blobs of proprietary technology
[35:59] SPEAKER: are pretty common, even in open source.
[36:03] SPEAKER: My router, for example, runs Linux,
[36:05] SPEAKER: but it has a proprietary driver or blob
[36:09] SPEAKER: that makes it actually run at full speed,
[36:11] SPEAKER: which is why you can't install other operating systems
[36:13] SPEAKER: on that thing unless you wanna eat
[36:14] SPEAKER: like a 60% performance penalty.
[36:16] SPEAKER: - Boo. - Closed source.
[36:19] SPEAKER: Anyway. - Yeah, so what's the TL;DR?
[36:21] SPEAKER: Does that mean that there's no VRR on the Steam machine?
[36:25] SPEAKER: - Yes, that seems to be the case,
[36:27] SPEAKER: at least out of the HDMI port.
[36:29] SPEAKER: - It has a DisplayPort port, too?
[36:31] SPEAKER: - It does have a DisplayPort port,
[36:33] SPEAKER: and DisplayPort has its own separate standard,
[36:36] SPEAKER: but I think DisplayPort only does FreeSync.
[36:37] SPEAKER: Like, it can't do HDMI VRR, so.
[36:40] SPEAKER: - Well, yeah. - So again, you're limited,
[36:42] SPEAKER: depending on what kind of TV and optional receiver you have,
[36:45] SPEAKER: there might not be able to get VRR out of the Steam machine.
[36:48] SPEAKER: There is one-- - I hate this.
[36:50] SPEAKER: - There's one interesting thing.
[36:51] SPEAKER: Kyle Orland-Rith is our story,
[36:53] SPEAKER: and he talked to Valve a little bit.
[36:55] SPEAKER: Valve has actually devised a way to get 4K
[36:58] SPEAKER: at 120 frames per second out of HDMI 2.0 output,
[37:02] SPEAKER: which is what they're doing out of this thing.
[37:03] SPEAKER: - Okay. - This thing,
[37:05] SPEAKER: we should say the Steam machine has 2.1 hardware in it.
[37:08] SPEAKER: They just can't implement the 2.1 support because, again.
[37:11] SPEAKER: - Yeah. - HDMI Forum policy.
[37:14] SPEAKER: They're using Chroma subsampling, though, to 2.0,
[37:17] SPEAKER: sorry, this is a lot of numbers, 2.0 tops out at 4K 60.
[37:20] SPEAKER: - Yeah. - 2.0 debuted
[37:22] SPEAKER: the same year as the PS4 and the Xbox One,
[37:24] SPEAKER: just for reference. - 2013, I think.
[37:26] SPEAKER: - 2013, yes. - Yeah.
[37:27] SPEAKER: - So that just rounded into the historical context.
[37:30] SPEAKER: Yeah, so 4K 60 is the best that can do.
[37:33] SPEAKER: Valve is upping that to 120
[37:35] SPEAKER: by effectively reducing the color depth
[37:38] SPEAKER: somewhat substantially.
[37:39] SPEAKER: I don't know how much from this write-up.
[37:41] SPEAKER: - They said it might impact text rendering
[37:43] SPEAKER: for games with a lot of text.
[37:45] SPEAKER: - Yeah, apparently I guess that was the Arting's assessment
[37:47] SPEAKER: of this, not of Valve's technique,
[37:50] SPEAKER: but just generally how Chroma subsampling
[37:52] SPEAKER: affects color depth and kind of visual perception.
[37:55] SPEAKER: I always, I had to go do a quick refresher on this
[37:58] SPEAKER: 'cause I always forget, you know, Chroma is color,
[38:00] SPEAKER: Luma is brightness.
[38:02] SPEAKER: Those are the two main components of a video signal, right?
[38:04] SPEAKER: - Yeah. - And I always forget,
[38:05] SPEAKER: I mean, this is just a feature
[38:06] SPEAKER: of rods and cones in your eye, right,
[38:07] SPEAKER: that basically the human eye is more sensitive
[38:10] SPEAKER: to brightness than it is to color variation.
[38:13] SPEAKER: And so you can, you can't mess with the brightness,
[38:15] SPEAKER: but you can reduce the color in certain ways
[38:18] SPEAKER: without people noticing too much.
[38:20] SPEAKER: - Yeah, well, this is why
[38:21] SPEAKER: there's like five different versions of HDR specs as well,
[38:23] SPEAKER: right, is 'cause they choose to compress different things.
[38:26] SPEAKER: - And different levels of, from a sampling,
[38:29] SPEAKER: you know, 444 or 422, et cetera.
[38:32] SPEAKER: So I don't know what the numbers are here,
[38:34] SPEAKER: but apparently Valve is basically compressing
[38:36] SPEAKER: the chroma of part of the signal to such an extent
[38:39] SPEAKER: that they can double the frame rate,
[38:42] SPEAKER: which seems pretty impressive.
[38:44] SPEAKER: - It's wild to me that HDMI isn't doing that,
[38:49] SPEAKER: like, they're not even letting AMD do a driver for this
[38:52] SPEAKER: when AMD is a member of the forum.
[38:53] SPEAKER: - So that's where that news that I mentioned
[38:55] SPEAKER: from about a year and a half ago came from
[38:57] SPEAKER: was that they kind of handed their verdict down to AMD,
[39:00] SPEAKER: that no, you can't implement this
[39:01] SPEAKER: in your open source driver.
[39:03] SPEAKER: - I hate this. - Yeah, it's a bummer.
[39:05] SPEAKER: It's a real shitfests of close standards.
[39:10] SPEAKER: - It's an absolute turd sandwich.
[39:11] SPEAKER: - Yes, it's a real bummer.
[39:13] SPEAKER: - So I guess use DisplayPort and buy TVs with DisplayPort
[39:16] SPEAKER: is the answer?
[39:17] SPEAKER: - This is kind of getting into a different domain here,
[39:19] SPEAKER: but it kind of reminds me of the situation
[39:21] SPEAKER: around video codec licensing and how--
[39:24] SPEAKER: - Oh, it is, yeah.
[39:25] SPEAKER: - You know, and how overly restrictive licensing
[39:28] SPEAKER: can actually end up shooting yourself in the foot
[39:30] SPEAKER: and maybe even killing your valuable standard,
[39:33] SPEAKER: because look at what happened in the,
[39:35] SPEAKER: remember talking to Jean-Baptiste at VLC at VideoLAN?
[39:38] SPEAKER: - Oh yeah, oh yeah.
[39:39] SPEAKER: - Remember how much he hated H.265 and VP9 and--
[39:43] SPEAKER: - Yep.
[39:44] SPEAKER: - You know how you're hearing a whole lot
[39:45] SPEAKER: about EV1 everywhere because it doesn't have
[39:47] SPEAKER: licensing fees attached to it?
[39:48] SPEAKER: - Really weird, yeah.
[39:50] SPEAKER: - I mean, that's purely a software example here, though,
[39:53] SPEAKER: where unfortunately here we've got 20 years
[39:56] SPEAKER: of legacy HDMI ports out there.
[39:58] SPEAKER: Like I don't think, when you've got a physical standard
[40:01] SPEAKER: that has proliferated to this extent,
[40:02] SPEAKER: I don't think we're going to see HDMI go away anytime soon,
[40:05] SPEAKER: but this still sucks.
[40:06] SPEAKER: - So the big question I have is if you use the,
[40:10] SPEAKER: like this, Kyle's R story says you can use
[40:14] SPEAKER: the DisplayPort 1.4 out port and convert it to HDMI
[40:17] SPEAKER: using a dongle, which makes me wonder if the best,
[40:20] SPEAKER: if that's gonna have the desired outcome.
[40:22] SPEAKER: - I don't think so.
[40:23] SPEAKER: I try to do a little digging on this.
[40:24] SPEAKER: I have experienced this in the past with my Pi KVM.
[40:28] SPEAKER: DisplayPort, built into its spec,
[40:30] SPEAKER: has something called DisplayPort Dual Mode.
[40:33] SPEAKER: You'll see it denoted as DP++ a lot.
[40:36] SPEAKER: They have, I think they even have
[40:37] SPEAKER: a little graphic designed logo around this.
[40:39] SPEAKER: - Of course they do.
[40:40] SPEAKER: - What that is is DisplayPort's version
[40:42] SPEAKER: of outputting an HDMI signal.
[40:45] SPEAKER: So if you buy, you can buy passive, in fact, I did this,
[40:48] SPEAKER: you can buy like a passive DisplayPort to HDMI cable.
[40:51] SPEAKER: In my case, I got the Pi KVM and hooked it into my NAS,
[40:54] SPEAKER: which is a full-size motherboard.
[40:57] SPEAKER: Pi KVM takes HDMI capture in,
[41:00] SPEAKER: and my motherboard has both DisplayPort and HDMI out,
[41:02] SPEAKER: so of course I just grabbed any old HDMI cable
[41:04] SPEAKER: and went HDMI to HDMI.
[41:06] SPEAKER: Pi KVM had a terrible problem.
[41:08] SPEAKER: Every time I would reboot the machine,
[41:09] SPEAKER: it would lose the handshake,
[41:10] SPEAKER: the video signal wouldn't come back.
[41:12] SPEAKER: Just all kinds of the most infuriating,
[41:14] SPEAKER: why is this video signal not working type nonsense.
[41:18] SPEAKER: On a lark, because they're cheap,
[41:19] SPEAKER: I just bought a $10 DisplayPort to HDMI cable
[41:22] SPEAKER: because I went and read about the DisplayPort Dual Mode thing
[41:25] SPEAKER: and I was like, oh, DisplayPort supports HDMI,
[41:27] SPEAKER: I should see if this works.
[41:30] SPEAKER: Instantly worked perfectly and has never stopped working,
[41:32] SPEAKER: like going HDMI to deep, or sorry,
[41:34] SPEAKER: going DP to HDMI worked better than going pure HDMI,
[41:38] SPEAKER: like DisplayPort was putting out cleaner,
[41:41] SPEAKER: more usable HDMI than HDMI was.
[41:44] SPEAKER: Anyway, that's a long-winded preamble for saying,
[41:47] SPEAKER: I don't know what DP Dual Mode would do with HDMI 2.1,
[41:52] SPEAKER: I can't imagine they are implementing those features
[41:55] SPEAKER: over DisplayPort, that's probably not the case.
[41:57] SPEAKER: - It's gonna be 4K 60 probably, right?
[41:59] SPEAKER: - Or it maybe would do 120,
[42:01] SPEAKER: but I doubt it does things like VRR and ALLM and such.
[42:06] SPEAKER: Anyway, this is just a real bummer
[42:07] SPEAKER: of like Valve is literally shipping hardware
[42:10] SPEAKER: that can do this better standard
[42:12] SPEAKER: and they are just prevented from doing it
[42:13] SPEAKER: because of which operating system they choose to run
[42:16] SPEAKER: on their hardware,
[42:17] SPEAKER: which happens to be the open operating system or one of them.
[42:20] SPEAKER: - Maybe going from analog was a mistake.
[42:22] SPEAKER: - Yep, I can't disagree with that, remember?
[42:26] SPEAKER: I think we've said this before,
[42:27] SPEAKER: remember when the video signal was stupid?
[42:29] SPEAKER: - Yeah.
[42:30] SPEAKER: - Remember when it was just a dumb signal
[42:31] SPEAKER: with no encoding in it,
[42:32] SPEAKER: it was just electrical pulses without any processors
[42:37] SPEAKER: on display controllers on either end,
[42:39] SPEAKER: processing encryption and handshaking and authentication.
[42:43] SPEAKER: - They had pins for the luminance
[42:45] SPEAKER: for each of the individual colors
[42:47] SPEAKER: and then they had a chroma pin and you were good,
[42:49] SPEAKER: that's all you needed, it was perfect.
[42:50] SPEAKER: - Yep, can't disagree.
[42:55] SPEAKER: Maybe it'll change in the future, I don't know,
[42:57] SPEAKER: but it doesn't sound like the forum
[42:58] SPEAKER: is likely to bend on this anytime soon.
[43:03] SPEAKER: - Well, you know what is likely to bend,
[43:06] SPEAKER: well, no, they're not gonna bend anytime soon
[43:08] SPEAKER: on this either, AI encroaching into more things.
[43:13] SPEAKER: The Google News, I don't know, do you use Google News?
[43:15] SPEAKER: I use Google News all the time.
[43:17] SPEAKER: - No, when you put this in the notes,
[43:18] SPEAKER: I had to look up what Google News even is as a product,
[43:21] SPEAKER: I'm not entirely sure.
[43:22] SPEAKER: That's not the same as,
[43:23] SPEAKER: it's not the successor to Google Reader, is it?
[43:26] SPEAKER: - Well, I mean, that's probably what Google would have said,
[43:28] SPEAKER: but no, Google News is, news.google.com
[43:31] SPEAKER: is their news search engine.
[43:33] SPEAKER: - Oh, I see, okay.
[43:34] SPEAKER: - But it also feeds the results on that,
[43:37] SPEAKER: it's where all the AMP stories go,
[43:38] SPEAKER: so if you're a publisher and you made it work with Google
[43:41] SPEAKER: to do a pre-formatted Google version of your post
[43:44] SPEAKER: that they host so it's really fast,
[43:48] SPEAKER: they also, in the app, in the Google app on your phone,
[43:52] SPEAKER: they do a programmatic newsfeed that's quite good,
[43:54] SPEAKER: really useful, it's tuned to your interests,
[43:56] SPEAKER: it's, you know, I get gaming and tech
[43:59] SPEAKER: and all the things that I'm interested in in the,
[44:03] SPEAKER: and they're one of the few places that separates tech
[44:06] SPEAKER: in a way that makes sense, so they,
[44:09] SPEAKER: like the entrepreneurial tech they delineate,
[44:13] SPEAKER: like fundraising and like AI startups and all that nonsense
[44:17] SPEAKER: is a separate category from like enthusiast tech,
[44:19] SPEAKER: the stuff that I actually care about.
[44:21] SPEAKER: So it's really useful, it's a really useful service to me,
[44:24] SPEAKER: I use it all the time, and they've started doing
[44:26] SPEAKER: these AI summaries of the headlines,
[44:29] SPEAKER: I'm gonna see if I can find one here on the feed.
[44:31] SPEAKER: So here we go, normally a headline is just the headline
[44:35] SPEAKER: that the publisher posts, so on the benefit,
[44:37] SPEAKER: like here's one from Hackaday that's on the benefits
[44:40] SPEAKER: of filling 3D prints with spray foam,
[44:42] SPEAKER: and then there's a picture of a 3D print
[44:44] SPEAKER: that's been cut open and it's clearly filled
[44:46] SPEAKER: with spray foam, oh get it, that makes sense.
[44:49] SPEAKER: Now this next article is from Tom's Hardware
[44:52] SPEAKER: and instead of having a headline, it has,
[44:54] SPEAKER: gaming-focused Linux distro, Bizite,
[44:56] SPEAKER: reported over a petabyte of ISO downloads in one month,
[44:59] SPEAKER: equating to roughly 150,000 downloads.
[45:02] SPEAKER: This surge, dot, dot, dot, C-more.
[45:05] SPEAKER: When you click C-more, it continues this long-ass,
[45:08] SPEAKER: not headline, right?
[45:09] SPEAKER: - I mean, is it formatted like a headline?
[45:11] SPEAKER: - So on these, instead of the headline being on the bottom,
[45:14] SPEAKER: which is where they usually are below the image,
[45:15] SPEAKER: usually it's like an eyebrow with the publication,
[45:20] SPEAKER: then a picture, then a headline, and that's it,
[45:22] SPEAKER: that's all you get, maybe a heart.
[45:24] SPEAKER: On these, there's this little blurb
[45:26] SPEAKER: that's like the TLDR for the article,
[45:29] SPEAKER: so you don't even have to click through,
[45:31] SPEAKER: and then there's the headline, then there's the picture,
[45:33] SPEAKER: then there's the headline.
[45:34] SPEAKER: - I mean, this is really just the eventual conclusion
[45:37] SPEAKER: of a set of media platforms and a societal inclination
[45:40] SPEAKER: to never read past the headline, right?
[45:42] SPEAKER: - I mean--
[45:43] SPEAKER: - Like they're just serving the market, perhaps.
[45:46] SPEAKER: - You're not wrong, but at the bottom
[45:48] SPEAKER: of the little AI description on these,
[45:49] SPEAKER: it always says, "Generated with AI,
[45:51] SPEAKER: "which can make mistakes."
[45:52] SPEAKER: Now, a friend of the show, Sean Hollister,
[45:55] SPEAKER: over at The Verge has been writing about this,
[45:56] SPEAKER: 'cause they have, their headlines have been having mistakes.
[46:02] SPEAKER: And he wrote an article called,
[46:04] SPEAKER: "Google's AI Newsbot is Still Confused,
[46:06] SPEAKER: "But No Longer Replacing Our Headlines."
[46:10] SPEAKER: They had a, they had a replacing,
[46:15] SPEAKER: they had a problem where an article on PC Gamer,
[46:21] SPEAKER: the headline replacement was,
[46:23] SPEAKER: "Baldur's Gate 3 Players Exploit Children."
[46:26] SPEAKER: - Great.
[46:27] SPEAKER: - The story was, Baldur's Gate 3 players
[46:29] SPEAKER: discovered an exploit using Polymorph and Dominate
[46:33] SPEAKER: that impacts children models or something in the game.
[46:37] SPEAKER: - Okay.
[46:38] SPEAKER: - But the thing is, the AI didn't know what the exploit,
[46:41] SPEAKER: didn't know that exploit meant in this context,
[46:44] SPEAKER: a way to do something with the game
[46:46] SPEAKER: that the vendor didn't intend,
[46:48] SPEAKER: not, "Hey, we're exploiting children."
[46:54] SPEAKER: The bot, their bot was sending pre-built DIY builds
[46:59] SPEAKER: and linking to stories on other topics entirely
[47:02] SPEAKER: for their thing.
[47:04] SPEAKER: And now it seems to be doing better,
[47:07] SPEAKER: but also this is a terrible feature
[47:08] SPEAKER: and Google should stop doing it because it's really bad.
[47:11] SPEAKER: - I mean, I assume, I don't know a ton about AMP,
[47:13] SPEAKER: but I assumed it has to be built into that, that they...
[47:17] SPEAKER: - Yeah.
[47:18] SPEAKER: - And the AMP participants are very able to specify
[47:20] SPEAKER: exactly what their aggregated headline should be, right?
[47:24] SPEAKER: - Well, no, not anymore, I think that's the problem.
[47:26] SPEAKER: - Well, no, what I mean is that functionality existed, right?
[47:28] SPEAKER: Like Google has to be doing that.
[47:30] SPEAKER: And it's not like the people who supply news to Google
[47:35] SPEAKER: don't have a way of saying,
[47:36] SPEAKER: "This is exactly what our headline should be."
[47:38] SPEAKER: - Oh, 100%.
[47:39] SPEAKER: - That's what I mean.
[47:40] SPEAKER: - The bad news is, so you can turn off sources,
[47:43] SPEAKER: you can give feedback on this.
[47:45] SPEAKER: You can't actually, as far as I can tell, say,
[47:48] SPEAKER: "Hey, I don't want any more of these fucking AI summaries."
[47:53] SPEAKER: - Are they denoted very clearly as such?
[47:55] SPEAKER: - Kind of, it has a little disclaimer at the bottom.
[47:59] SPEAKER: The format is different, which I recognize,
[48:01] SPEAKER: I assume most people probably don't.
[48:03] SPEAKER: - Does it have the AI sparkle?
[48:04] SPEAKER: That's the real question.
[48:05] SPEAKER: And this is really just a way for me to sidebar here.
[48:08] SPEAKER: How did we land on this little sparkly graphic as the...
[48:11] SPEAKER: - It's magic.
[48:12] SPEAKER: - Is that like, but I feel like I'm starting to see that
[48:15] SPEAKER: on things that aren't very self-evidently AI related.
[48:18] SPEAKER: - I think I saw it on toothpaste the other day.
[48:20] SPEAKER: - Right, like I feel like that is just starting
[48:22] SPEAKER: to appear everywhere now, which as bad as it is
[48:26] SPEAKER: that there are AI features everywhere,
[48:27] SPEAKER: you have to dodge and watch out for.
[48:28] SPEAKER: At least they had that little graphic on them,
[48:30] SPEAKER: but now that's infecting everything.
[48:31] SPEAKER: So it's gonna be even harder to tell what's AI.
[48:34] SPEAKER: - So there is no sparkle.
[48:36] SPEAKER: And some of these are actually aggregates
[48:38] SPEAKER: about the same story on multiple sites.
[48:41] SPEAKER: So like this Bizite article that I read a minute ago
[48:44] SPEAKER: is on Tom's Hardware, ZDNet and Windows Central
[48:47] SPEAKER: and Fudzilla and a bunch of other places.
[48:49] SPEAKER: So it's like a, they're making like a landing page
[48:51] SPEAKER: for the story about Bizite download surging,
[48:54] SPEAKER: which is like maybe kind of useful,
[48:57] SPEAKER: but also it's a bad, this is a bad implementation.
[49:01] SPEAKER: They needed to fix this.
[49:02] SPEAKER: - Yep, agreed.
[49:03] SPEAKER: I have developed a Pavlovian aversion
[49:05] SPEAKER: to that little sparkle graphic.
[49:07] SPEAKER: I don't know about you.
[49:08] SPEAKER: - I don't, I don't like the sparkle.
[49:10] SPEAKER: So speaking of places that the sparkle shows up on Hackaday
[49:14] SPEAKER: on, let's see, flamedfury.com,
[49:19] SPEAKER: which is someone's personal blog,
[49:21] SPEAKER: like some programmer's blog had a fantastic post
[49:24] SPEAKER: at the end of October called Disable AI in Firefox.
[49:29] SPEAKER: - This must be why this has been going around.
[49:31] SPEAKER: Like I said, I've heard from other people
[49:32] SPEAKER: I know who use Firefox.
[49:34] SPEAKER: - Yeah, well, so Firefox has been kind of quietly
[49:38] SPEAKER: encroaching AI into the browser experience.
[49:41] SPEAKER: There was a thing in the sidebar that nobody uses
[49:43] SPEAKER: that you could add your favorite chat bot the other day,
[49:46] SPEAKER: whether it's Gemini or chat GPT or co-pilot,
[49:49] SPEAKER: or there was one or two others.
[49:52] SPEAKER: They also have had this thing where you can long
[49:55] SPEAKER: kind of click a link and it pops up a little AI
[49:57] SPEAKER: generated preview of what's at the other end of that link.
[50:00] SPEAKER: They're all completely useless garbage.
[50:04] SPEAKER: You can turn off these features individually,
[50:08] SPEAKER: but it was a little bit challenging
[50:09] SPEAKER: and it wasn't immediately apparent where you could do them.
[50:12] SPEAKER: And some of them, when you turn them off,
[50:13] SPEAKER: you can't turn them back on again,
[50:14] SPEAKER: which is I think a really interesting choice,
[50:16] SPEAKER: like that AI links preview.
[50:18] SPEAKER: Once you click the button on that,
[50:19] SPEAKER: on the version of Firefox,
[50:20] SPEAKER: I have the option to turn it back on,
[50:22] SPEAKER: just disappears from the control panel.
[50:24] SPEAKER: You have to do it in the config flags.
[50:27] SPEAKER: Anyway, this blog, Flame Fury,
[50:30] SPEAKER: we'll put the link in the show notes,
[50:31] SPEAKER: has a list of all of the about config flags
[50:36] SPEAKER: that you can just turn off to turn off all of this stuff.
[50:39] SPEAKER: It took me about five minutes.
[50:40] SPEAKER: It's fabulous, highly recommended Firefox.
[50:44] SPEAKER: My Firefox feels faster.
[50:45] SPEAKER: I haven't actually done benchmarks or testing,
[50:46] SPEAKER: but what a load of crap.
[50:50] SPEAKER: Please don't do this anymore, Firefox.
[50:51] SPEAKER: - You just did it all manually through the Firefox config?
[50:55] SPEAKER: 'Cause I've heard, I think there were people
[50:57] SPEAKER: putting out scripts to do this now.
[50:59] SPEAKER: - Yeah, I'm always a little, I'm a little hinky on that.
[51:03] SPEAKER: I'm not gonna read the script to figure out what it does.
[51:05] SPEAKER: I guess for something that it's like 12 options here,
[51:08] SPEAKER: I think for this. - Yes, yes.
[51:11] SPEAKER: - For something that's this simple,
[51:12] SPEAKER: it's faster for me to just fix it manually
[51:15] SPEAKER: than to read the script
[51:17] SPEAKER: and make sure the script doesn't do anything devious.
[51:19] SPEAKER: - Yeah, like I am a little, I'm a little,
[51:21] SPEAKER: I'm more than a little wary of kind of like shortcut scripts
[51:24] SPEAKER: that purport to do things like this for you.
[51:26] SPEAKER: I mean, 95% of them are fine to be clear,
[51:28] SPEAKER: but they're way too easily a vector for bad behavior
[51:33] SPEAKER: to trust all of them blindly.
[51:35] SPEAKER: So this seems like an incredible misread
[51:39] SPEAKER: of the Firefox audience by Mozilla.
[51:44] SPEAKER: It seems crazy to me.
[51:45] SPEAKER: Like, do they not understand that people who use Firefox
[51:48] SPEAKER: are very frequently doing so ideologically
[51:51] SPEAKER: because they don't wanna use Google-based
[51:54] SPEAKER: or like bigger corporate browsers
[51:55] SPEAKER: with more of this shit in there?
[51:57] SPEAKER: - Well, I think there's two things, right?
[51:59] SPEAKER: One is that Mozilla has traditionally gotten
[52:01] SPEAKER: most of its revenue from Google, right?
[52:03] SPEAKER: - Yes, is that still the case?
[52:05] SPEAKER: I know that that came up because the word going around,
[52:09] SPEAKER: I don't, surely Google's never said this out loud,
[52:11] SPEAKER: but the word going around was that that was really
[52:13] SPEAKER: just a protective play on Google's part
[52:16] SPEAKER: against any kind of antitrust from the government.
[52:19] SPEAKER: That would be basically a way for them to say,
[52:20] SPEAKER: hey, look, we support other browsers.
[52:21] SPEAKER: Like, please don't take Chrome from us.
[52:24] SPEAKER: But now that we're not in a world
[52:26] SPEAKER: where that matters anymore,
[52:27] SPEAKER: are they even still giving the money?
[52:29] SPEAKER: - Well, so as part of the monopoly lawsuit,
[52:32] SPEAKER: I think there was a, that was part of the question.
[52:38] SPEAKER: Google hasn't pulled the money from those
[52:39] SPEAKER: as far as we know yet.
[52:40] SPEAKER: - Okay.
[52:44] SPEAKER: - It's traditionally been cheaper for them to fund Mozilla
[52:48] SPEAKER: so that there's real browser competition,
[52:50] SPEAKER: Chromium competition, than it is to not fund Mozilla.
[52:55] SPEAKER: But anyway, we'll see what happens with that.
[52:58] SPEAKER: That's no way to know.
[53:01] SPEAKER: - Yeah, I'm just, again, kind of surprised
[53:04] SPEAKER: they actually made this move in the first place.
[53:06] SPEAKER: - Well, I was gonna say that the reason,
[53:08] SPEAKER: I actually understand how you get into,
[53:10] SPEAKER: how you're Mozilla and you end up in a place
[53:11] SPEAKER: where you're like, oh yeah, we gotta put AI stuff in Firefox.
[53:14] SPEAKER: And it's the, like, this is the struggle for every startup,
[53:18] SPEAKER: everybody that's trying to raise money right now,
[53:21] SPEAKER: is if you don't have some sort of AI strategy,
[53:23] SPEAKER: nobody's gonna write you a check.
[53:24] SPEAKER: - Sure.
[53:27] SPEAKER: - But even if your audience is vehemently anti-AI,
[53:30] SPEAKER: and that's why we see things like game studios
[53:33] SPEAKER: and indie game studios that are like,
[53:35] SPEAKER: yeah, we're exploring AI tooling, blah, blah, blah, blah,
[53:38] SPEAKER: blah, when that stuff is gonna be absolute poison
[53:40] SPEAKER: in the market for 90% of games, 99% of games.
[53:45] SPEAKER: So I don't, like, I understand how they get there.
[53:48] SPEAKER: I think it's a horrible misread of their audience probably,
[53:51] SPEAKER: given the kind of people who are likely to use Firefox.
[53:53] SPEAKER: - Yeah.
[53:54] SPEAKER: - But yeah, I think making it difficult to turn off
[53:57] SPEAKER: is the real crime, honestly.
[53:58] SPEAKER: - Yeah, yes.
[53:59] SPEAKER: - But I think having a button in the control panel
[54:02] SPEAKER: that was like, hey, disable all the AI crap
[54:04] SPEAKER: would go a long way.
[54:05] SPEAKER: - Yeah, like one easy button,
[54:06] SPEAKER: we're just right clicking the feature itself
[54:08] SPEAKER: and hitting disable or something for sure.
[54:11] SPEAKER: You know, at the same time, like,
[54:13] SPEAKER: Firefox's existing audience is not necessarily sufficient
[54:17] SPEAKER: to keep Firefox going in a very healthy way.
[54:21] SPEAKER: Like Firefox's market share is like abysmally low.
[54:24] SPEAKER: - It's like 1%.
[54:25] SPEAKER: - It's like one to 2% on any given month, it seems like.
[54:28] SPEAKER: - Well, and they've made changes recently too.
[54:30] SPEAKER: Like, I don't know if you saw, but they,
[54:32] SPEAKER: Firefox bought Pocket, Mozilla bought Pocket a long time ago,
[54:35] SPEAKER: the kind of like the read on a plain white page article
[54:40] SPEAKER: company, read it later company, I guess is what it is.
[54:43] SPEAKER: - Yeah.
[54:44] SPEAKER: - And that, the Pocket metadata
[54:47] SPEAKER: used to fill their blank homepage.
[54:49] SPEAKER: So like, you know, they have the normal thing,
[54:52] SPEAKER: they have some sponsored links, they have your links,
[54:54] SPEAKER: the ones you use most commonly,
[54:55] SPEAKER: and they have a Google search bar for your site of choice,
[54:59] SPEAKER: for your search of choice on their default homepage.
[55:03] SPEAKER: And it used to be all Pocket links,
[55:05] SPEAKER: which was kind of useful,
[55:05] SPEAKER: 'cause it was like stuff that Pocket, you know,
[55:08] SPEAKER: filters up to the top of Pocket,
[55:09] SPEAKER: and it was a useful list of things.
[55:12] SPEAKER: Now they're doing that all programmatically,
[55:14] SPEAKER: and it's just the normal turn of dipshit stuff
[55:18] SPEAKER: with sponsored obvious scams.
[55:21] SPEAKER: So it's like, hey, Kill Bill is back in theaters
[55:23] SPEAKER: in a new version, it'll never play the same.
[55:25] SPEAKER: Speaker Johnson pleads with Republicans
[55:27] SPEAKER: to keep concerns private after tumultuous week.
[55:30] SPEAKER: 14 benefits seniors are entitled to,
[55:32] SPEAKER: but often forget to claim.
[55:34] SPEAKER: And like, it's a real devaluation of the brand.
[55:39] SPEAKER: Like I've turned off, I used to always use that homepage
[55:42] SPEAKER: and look at the homepage,
[55:43] SPEAKER: 'cause there were always interesting things there,
[55:45] SPEAKER: 'cause anything that 20,000 people add to their Pocket
[55:48] SPEAKER: is gonna be probably worth taking a look at, right?
[55:51] SPEAKER: And this stuff is just the same garbage
[55:53] SPEAKER: you get on the homepage of MSN or CNN
[55:55] SPEAKER: or the New York Times or anything, so thumbs down.
[55:59] SPEAKER: - Yep.
[56:00] SPEAKER: - And I realize I'm complaining about here,
[56:04] SPEAKER: they're doing the exact same thing that Google News does,
[56:07] SPEAKER: and I'm complaining about it.
[56:08] SPEAKER: I realize the hypocrisy here,
[56:11] SPEAKER: but the difference is that the Google News implementation
[56:13] SPEAKER: is actually really good,
[56:15] SPEAKER: and this implementation is really pretty generic, so.
[56:18] SPEAKER: - Yeah, I like it, it's impossible to be free of biases,
[56:21] SPEAKER: the best you can do is be aware of them.
[56:23] SPEAKER: - Yeah.
[56:24] SPEAKER: - And rationalize them.
[56:25] SPEAKER: - Yeah, I love rationalizing things.
[56:27] SPEAKER: - Yes, we need more browsers in the world.
[56:31] SPEAKER: - I mean, yeah, it's interesting.
[56:33] SPEAKER: We talked to the guys who make Cosmic from System 76
[56:38] SPEAKER: on an upcoming episode of "The Dual Boy Diaries,"
[56:40] SPEAKER: it'll be up next week, about Cosmic,
[56:43] SPEAKER: which is their desktop environment
[56:45] SPEAKER: that's about to come out of beta.
[56:47] SPEAKER: And we asked them why they did it,
[56:51] SPEAKER: 'cause there's plenty of desktop environments for Linux,
[56:53] SPEAKER: and they're like, well, nobody was doing the things
[56:55] SPEAKER: that we thought were important here,
[56:56] SPEAKER: and building toward the future and all that.
[56:59] SPEAKER: And having multiple companies, multiple groups of people
[57:03] SPEAKER: making things from different perspectives,
[57:06] SPEAKER: it turns out, is incredibly valuable
[57:08] SPEAKER: to the overall health of an ecosystem, so yeah, I agree.
[57:11] SPEAKER: More people making good stuff is good.
[57:14] SPEAKER: - Not just more browsers,
[57:15] SPEAKER: but more browser rendering engines would be nice,
[57:17] SPEAKER: but I don't know.
[57:18] SPEAKER: - I knew we have three, right?
[57:19] SPEAKER: - Yeah, more or less.
[57:21] SPEAKER: I mean, at least two of them are forks of each other.
[57:24] SPEAKER: - Yeah, but ancient forks now.
[57:26] SPEAKER: - Yeah, yeah, actually, I don't know why,
[57:27] SPEAKER: I just went back down this rabbit hole.
[57:29] SPEAKER: I have to remind myself every couple of years
[57:31] SPEAKER: which rendering engine was which.
[57:33] SPEAKER: Did you know WebKit was forked from KDE
[57:35] SPEAKER: now that you're in the Linux land?
[57:37] SPEAKER: I always forget that. - Oh, yeah, oh, yeah.
[57:39] SPEAKER: - I always forget that all the browser engines
[57:40] SPEAKER: that run the entire web came out of fricking KDE originally.
[57:45] SPEAKER: Like WebKit forked from that,
[57:47] SPEAKER: and then I'm pretty sure Google forked Blink from WebKit.
[57:51] SPEAKER: - That was my recollection.
[57:52] SPEAKER: That was ancient history at this point.
[57:53] SPEAKER: It was like 20 years ago.
[57:55] SPEAKER: - And then Firefox, Firefox's Gecko is independent,
[57:59] SPEAKER: or did it also come out of WebKit?
[58:01] SPEAKER: - I think Firefox Gecko came out of its own thing,
[58:03] SPEAKER: but I don't remember.
[58:04] SPEAKER: I think it came out of the old Firefox code base.
[58:07] SPEAKER: It was a refactor.
[58:08] SPEAKER: - Yeah, that sounds right.
[58:09] SPEAKER: And then there's the Ladybird project,
[58:11] SPEAKER: which is relatively new.
[58:12] SPEAKER: I think they're looking to ship a browser,
[58:14] SPEAKER: like an alpha next year or something.
[58:16] SPEAKER: - That's exciting. - Which is its own
[58:17] SPEAKER: fully new from the ground up web engine.
[58:22] SPEAKER: - Yeah, Gecko has been based,
[58:26] SPEAKER: Gecko was a refactor of Netscape.
[58:30] SPEAKER: - Oh, oh, right, okay, of course, yes.
[58:33] SPEAKER: - Yep. - Anyway, standards.
[58:36] SPEAKER: - There we go.
[58:38] SPEAKER: So I guess that's probably as good a place as any
[58:40] SPEAKER: to wrap it up. - Yeah.
[58:42] SPEAKER: - AI still sucks for multiple reasons.
[58:45] SPEAKER: - Yes, the affordability crisis is only getting worse.
[58:48] SPEAKER: The, dude, I don't know if you watched
[58:50] SPEAKER: that Gamers Nexus video,
[58:51] SPEAKER: but the darkest thing, for PC enthusiasts to be clear,
[58:54] SPEAKER: like there are darker, broader economic trends at work,
[58:57] SPEAKER: but like for people who like building gaming PCs,
[59:01] SPEAKER: the darkest thing he mentions in that video
[59:03] SPEAKER: is the idea that effectively the ability
[59:05] SPEAKER: to build and own your own computer
[59:08] SPEAKER: is slowly but surely being taken away.
[59:10] SPEAKER: - Yep. - And that eventually
[59:11] SPEAKER: the idea is just going to be for you to rent computing time
[59:14] SPEAKER: on some remote server.
[59:15] SPEAKER: - Yeah, and the way they do that
[59:16] SPEAKER: is just by buying all the RAM, it turns out.
[59:18] SPEAKER: - Right, and effectively, I mean,
[59:20] SPEAKER: this is whether intentionally
[59:21] SPEAKER: or just as a downstream consequence
[59:23] SPEAKER: of both market forces and corruption.
[59:25] SPEAKER: If it just emerges organically,
[59:27] SPEAKER: the result is going to be the same of it's going to be,
[59:29] SPEAKER: it's going to become more and more inaccessible
[59:32] SPEAKER: to build and own your own computer.
[59:34] SPEAKER: - I've been-- - It's about the darkest
[59:36] SPEAKER: cyberpunk shit I could imagine in this very specific domain.
[59:40] SPEAKER: - I've been watching those videos of the guys
[59:42] SPEAKER: that take old phones and then mill off the storage
[59:47] SPEAKER: and put bigger storage on or mill off the CPU
[59:50] SPEAKER: and then put faster CPUs on.
[59:51] SPEAKER: - Nice.
[59:52] SPEAKER: - And I'm like, yeah, that's where we're going.
[59:54] SPEAKER: Like get ready, get good at drag soldering, baby.
[59:56] SPEAKER: - Seriously, like that is, I've made this reference before
[59:59] SPEAKER: 'cause I only saw this movie recently a couple years ago,
[1:00:01] SPEAKER: but like that's the Henry Rollins character
[1:00:03] SPEAKER: in Johnny Demonic, right?
[1:00:04] SPEAKER: - Yeah. - Like the William Gibson
[1:00:05] SPEAKER: vision of like dude in a workshop.
[1:00:08] SPEAKER: - Yep. - Except instead of working
[1:00:09] SPEAKER: on gas engines, he's like pulling circuit boards apart
[1:00:12] SPEAKER: and jury rigging better chips onto things.
[1:00:14] SPEAKER: And there's people out there soldering bigger SSDs
[1:00:17] SPEAKER: onto their MacBook Pro motherboards and stuff.
[1:00:20] SPEAKER: - Oh yeah. - Like it's gonna get
[1:00:21] SPEAKER: weird out there.
[1:00:22] SPEAKER: - Have you seen the guys that do the DIY home e-wasting?
[1:00:27] SPEAKER: - No. - We talked about this already?
[1:00:29] SPEAKER: - Did we think about it off air?
[1:00:30] SPEAKER: I think we discussed this at some point recently.
[1:00:33] SPEAKER: - Yeah, so there's YouTube channels where they show you
[1:00:36] SPEAKER: how to harvest the valuable metals out of your old e-waste
[1:00:41] SPEAKER: so you can pull the gold and silver
[1:00:43] SPEAKER: and whatever out, platinum. - Right, yep.
[1:00:46] SPEAKER: - Wild. - Mm-hmm.
[1:00:47] SPEAKER: - Anyway, yeah, it's a grim future.
[1:00:49] SPEAKER: But anyway, thanks for supporting the show.
[1:00:50] SPEAKER: We appreciate you all. - Mm-hmm, we sure do.
[1:00:53] SPEAKER: - Sorry for the bad news episode, I guess.
[1:00:55] SPEAKER: - Yeah.
[1:00:56] SPEAKER: - But as always, we're brought to you by listeners.
[1:00:59] SPEAKER: We wouldn't be here without you, all the listeners,
[1:01:01] SPEAKER: and we appreciate each and every one of you.
[1:01:04] SPEAKER: If you wanna find out how you can support the show
[1:01:05] SPEAKER: and get access to the Patreon-exclusive Discord
[1:01:08] SPEAKER: as well as the monthly Patreon-exclusive episode,
[1:01:11] SPEAKER: you can go to patreon.com/techpod,
[1:01:13] SPEAKER: where for $5 a month, that's all it costs.
[1:01:16] SPEAKER: It's like a third of a cup of coffee these days.
[1:01:18] SPEAKER: It's a quarter of a San Francisco sandwich.
[1:01:22] SPEAKER: I don't know what gas costs 'cause I'm an electric car,
[1:01:24] SPEAKER: but maybe a gallon of gas, I don't know.
[1:01:27] SPEAKER: You get access to the Discord,
[1:01:28] SPEAKER: you get access to the Patreon-exclusive episodes,
[1:01:30] SPEAKER: and you support Brad and me in our quest
[1:01:33] SPEAKER: to continue bringing you an awesome tech podcast
[1:01:35] SPEAKER: every single week. - Yeah.
[1:01:37] SPEAKER: - So again, it's patreon.com/techpod.
[1:01:40] SPEAKER: - I found it useful recently,
[1:01:42] SPEAKER: and I swear to God, this is not an upsell for our Patreon.
[1:01:45] SPEAKER: - No, please, upsell our Patreon.
[1:01:47] SPEAKER: - I mean, this is actually me putting myself
[1:01:49] SPEAKER: in the consuming.
[1:01:50] SPEAKER: I found it pretty useful to look at things
[1:01:52] SPEAKER: in terms of like, alternate purchases.
[1:01:54] SPEAKER: I mean, I know people do this all the time,
[1:01:55] SPEAKER: but in terms of the sandwich or cup of coffee type of analogy,
[1:01:59] SPEAKER: like I signed up for some like, sub stacks and stuff
[1:02:02] SPEAKER: over Black Friday and was just like, you know what?
[1:02:03] SPEAKER: Yeah, I absolutely get three cups of coffee's worth
[1:02:06] SPEAKER: of value or way more out of this thing every month.
[1:02:10] SPEAKER: Of course I should support that.
[1:02:11] SPEAKER: - Yeah, I think about it as like, you know,
[1:02:15] SPEAKER: are we 1/20th of the value of a 64 gig pack
[1:02:19] SPEAKER: of DDR5 6000?
[1:02:20] SPEAKER: Yeah, absolutely.
[1:02:22] SPEAKER: Every month.
[1:02:24] SPEAKER: Anyway, we appreciate each and every one of you,
[1:02:25] SPEAKER: but we very, I wanna give a very special thank you
[1:02:27] SPEAKER: to our executive producer, to your patrons,
[1:02:30] SPEAKER: including Jason Lee, Infelicitous Rips, Andrew Slosky,
[1:02:34] SPEAKER: Jordan Lippett, Bunny Jerk, David Allen,
[1:02:36] SPEAKER: James Kamik, and Pantheon, makers of the HS3
[1:02:40] SPEAKER: high-speed 3D printer.
[1:02:42] SPEAKER: Thank you all so, so much.
[1:02:43] SPEAKER: - Thank you.
[1:02:44] SPEAKER: - And that, I guess, will do it for us this week.
[1:02:46] SPEAKER: We will be back next week with another edition
[1:02:49] SPEAKER: of the TechPod.
[1:02:49] SPEAKER: Until then, please consider the environment
[1:02:52] SPEAKER: before printing this podcast.
