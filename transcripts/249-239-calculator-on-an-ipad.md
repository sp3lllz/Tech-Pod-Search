---
episode: 249
title: 239: Calculator on an iPad?!
date: 2024-06-16
guests: none
duration: 1:46:47
---

[00:00] SPEAKER: Brad, we did it.
[00:01] SPEAKER: What did we do?
[00:02] SPEAKER: Well, a couple weeks ago, we came out and we were like, "You know what's stupid? Microsoft
[00:05] SPEAKER: recall." You know who agrees with us now?
[00:07] SPEAKER: Who's that?
[00:08] SPEAKER: Microsoft.
[00:09] SPEAKER: That's right. TechPod activism has scored its first victory.
[00:13] SPEAKER: In fairness, when we were doing that show, I was like, "Do I have to say, 'Hey, it would be
[00:18] SPEAKER: really stupid to save this in an unencrypted database?'" Recall for people who don't remember,
[00:24] SPEAKER: it's the feature that takes the screenshot of everything on your computer, including
[00:27] SPEAKER: passwords and financial data and stuff like that, and then dumps it in a database where
[00:31] SPEAKER: it's machine-imaged and recognized to know what is on each screenshot. Then it's searchable,
[00:38] SPEAKER: which seems like an interesting idea, not something I'm going to turn on.
[00:42] SPEAKER: The privacy people were like, "Oh, it's really bad. Somebody gets a hold of your computer, blah,
[00:45] SPEAKER: blah, blah, blah." I was like, "The computer's hard drive is encrypted with BitLocker,
[00:49] SPEAKER: presumably because that's on by default on machines that this is on by default on."
[00:53] SPEAKER: Shouldn't be that big a deal unless they did something dopey like save it in an unencrypted
[00:58] SPEAKER: user space where every application that's running on the computer can have access to it.
[01:03] SPEAKER: We didn't even talk about malicious users who have access to your computer, like domestic
[01:06] SPEAKER: violence situations. That's on me. I always forget to think about stuff from that context.
[01:13] SPEAKER: Apparently, nobody at Microsoft had thought about any of this stuff either, because on a June 13th
[01:18] SPEAKER: update to a blog post - I'm reading a PCWorld.com story here - on a June 13th update to a blog post
[01:24] SPEAKER: Microsoft originally published on June 7th, they announced that Recall will now be released as a
[01:29] SPEAKER: preview to the Insider program in the coming weeks. This is four days before the copilot
[01:36] SPEAKER: plus PCs using the Qualcomm Snapdragon 10 or X Elite start shipping. They're pulling this at,
[01:44] SPEAKER: I would describe this as, I think it's safe to say this is the last minute.
[01:47] SPEAKER: It will not be in at launch, is what you're saying?
[01:50] SPEAKER: Not in at launch, no. It was going to be a shipping beta for everyone, and now it's not in at launch.
[02:00] SPEAKER: They're saying that now they'll turn off Recall by default. It will require Windows Hello to use
[02:06] SPEAKER: Recall and will, in the future, use just-in-time encryption and decryption to secure the stored
[02:12] SPEAKER: data further. But yeah, they're going to need more time to add that stuff.
[02:16] SPEAKER: Yes, and decrypting on the fly at the last possible minute seems like the only way that
[02:21] SPEAKER: could possibly be acceptable. I mean, they're still going to
[02:24] SPEAKER: index all the information that's in those - presumably, I think the way it worked was
[02:29] SPEAKER: it looks at the picture, at the screenshots. It does an image pass on the screenshot. It's
[02:34] SPEAKER: supposed to do this all locally on the NPU, which is like this 40 tops processor inside the
[02:40] SPEAKER: Lunar Lake or Snapdragon. I can't remember what the AMD one is. The AM5 stuff, I guess.
[02:46] SPEAKER: What is the T in tops?
[02:48] SPEAKER: Terra.
[02:48] SPEAKER: Okay. It feels like there's a missing unit type in there. Terra, what operations perspective?
[02:54] SPEAKER: Trillions of operations.
[02:55] SPEAKER: Trillions, but what kind, though? Flops is floating point operations, for example.
[03:00] SPEAKER: This is just a lot of them.
[03:02] SPEAKER: A lot of some kind of...
[03:03] SPEAKER: Tensor, I think, maybe. I don't know.
[03:05] SPEAKER: Okay, well, that's an NVIDIA turn. Not to split hairs here, but...
[03:08] SPEAKER: Google uses that, too, right?
[03:10] SPEAKER: Google uses Tensor, too.
[03:11] SPEAKER: Maybe so. Or TensorFlow is a thing. I guess that is a generic AI term, but NVIDIA has
[03:17] SPEAKER: "tensor cores" on their GPUs, but I guess you're right. That is a generic AI thing.
[03:22] SPEAKER: According to dictionary.com, tops just means it's ranked among the highest as
[03:26] SPEAKER: inability, performance, comprehensiveness, or quality.
[03:29] SPEAKER: Oh, good. Now I know what that means.
[03:31] SPEAKER: As in, his work is tops. That car is tops. Then there's more about other things that
[03:36] SPEAKER: I'm not going to read on the podcast because there might be kids listening.
[03:38] SPEAKER: Is it matrix multiplication? Is it matrix math operations? Anyway, it doesn't matter.
[03:43] SPEAKER: It doesn't matter.
[03:44] SPEAKER: Matters to me.
[03:46] SPEAKER: I mean, it does matter, but look, here's the thing that Microsoft told us all.
[03:50] SPEAKER: You need 40 of them, more is better, but you don't need 300. You just need 40 or 50.
[03:57] SPEAKER: I saw some benchmarks are starting to circulate for the Snapdragon 10 Elite.
[04:01] SPEAKER: I don't know if you've seen...
[04:02] SPEAKER: Yeah, it's just X. It's not 10.
[04:04] SPEAKER: Is it X?
[04:05] SPEAKER: Yeah, 10 is the website or the operating system from Apple, not the Snapdragon Elite.
[04:10] SPEAKER: The... I saw some gaming benchmarks going around, specifically comparing to Meteor Lake,
[04:14] SPEAKER: the last year's laptop part from Intel.
[04:16] SPEAKER: Well, they've tested 12... I think at Computex, they said they tested 1200,
[04:20] SPEAKER: as many as 1200 games tested.
[04:23] SPEAKER: It was like keeping pace with Meteor Lake. I would not say a lot of profound wins on that front,
[04:29] SPEAKER: and people seemed shocked by that.
[04:32] SPEAKER: We talked about this on the PC World podcast last week. The problem that they have...
[04:38] SPEAKER: Everybody's looking at this and thinking, "Oh, it's going to be like Apple,"
[04:40] SPEAKER: where all of a sudden, everybody's suddenly magically making ARM versions of their executables,
[04:45] SPEAKER: and it's not going to happen because Apple had the benefit of saying,
[04:48] SPEAKER: "Hey, we're not going to sell any of the old Macs anymore,"
[04:51] SPEAKER: and everybody buys new Macs every five years.
[04:56] SPEAKER: If you wanted to keep selling software to your customers, you had to get on the train.
[05:01] SPEAKER: The Windows isn't going to be like that.
[05:03] SPEAKER: Windows people will be running a fucking Sandy Lake from 10 years ago in 15 years still.
[05:09] SPEAKER: Obviously, there is no ARM version of Counter-Strike yet. There's obviously some overhead
[05:13] SPEAKER: with the instruction translation or whatever, but still, people seem very shocked that...
[05:17] SPEAKER: The bigger point is I got the sense people have maybe built this chip up in their minds
[05:21] SPEAKER: a little too much as a profound next big thing in the Windows space.
[05:27] SPEAKER: To give some context, Gordon and I over at PCWorld talked over all the Computex keynotes last week,
[05:34] SPEAKER: starting with Nvidia, which was just talking about big AI iron, basically. It was fine.
[05:42] SPEAKER: We had 12 to 1,500 people watching all of those keynotes on the PCWorld channel,
[05:46] SPEAKER: and then when we got to Qualcomm on Sunday night, it went down to 400.
[05:50] SPEAKER: Really?
[05:51] SPEAKER: Yeah. I think the enthusiast crowd probably knows what's up.
[05:55] SPEAKER: Here's the thing. Qualcomm is saying they want to have 50% of the PC market share
[06:00] SPEAKER: in five years by 2030, I think, which seems aggressive.
[06:05] SPEAKER: Yes.
[06:06] SPEAKER: But if they actually have SOCs to push down into $200 laptops,
[06:13] SPEAKER: because all of these are launching at around $1,000, that's not out of the question.
[06:16] SPEAKER: No, maybe. I can say from experience, having had an M1 MacBook for a couple of years,
[06:22] SPEAKER: battery life sells hard. That is the killer feature, more than performance, more than
[06:28] SPEAKER: anything else. It's the fact that you can open that thing up in the morning, use it all day,
[06:32] SPEAKER: the fan never kicks on, and then at the end of the day, you've still got 60% battery or better.
[06:36] SPEAKER: Yeah. My wife uses her laptop all around the house. There's one place that there's a plug,
[06:41] SPEAKER: and she just plugs it in maybe twice a week, once or twice a week.
[06:44] SPEAKER: Right. Yes.
[06:46] SPEAKER: I think the thing that people are excited about is that there's finally something
[06:50] SPEAKER: to push ARM on Windows that actually seems like it might not suck. It all depends on how Prism is.
[06:57] SPEAKER: Those benchmarks are the first benchmarks we've seen about Prism. They didn't tout any
[07:02] SPEAKER: performance numbers in any of the stuff. Honestly, I think for this category, I don't think games
[07:06] SPEAKER: matter as much as productivity stuff. No, it's just the only metric I have managed to find so far.
[07:14] SPEAKER: The big surprise for me out of all the Computex stuff, not to completely tangentize this tangent
[07:19] SPEAKER: of a tangent, is the PC OEMs were treating Co-Pilot Plus as if it was the second coming
[07:27] SPEAKER: of Centrino. I think Intel even mentioned Centrino when they were talking about it.
[07:31] SPEAKER: Centrino for the olds is when Intel was like, "Hey, we're going to put Wi-Fi on the chipset
[07:36] SPEAKER: for your laptop." Then they did a whole bunch of ads that were like, "Hey, you like the internet,
[07:42] SPEAKER: right? What if you could use the internet from your couch in your living room while
[07:45] SPEAKER: you're watching TV?" Then they basically destroyed all of human culture after that point.
[07:50] SPEAKER: But they sold a boatload of laptops, like an insane number of laptops.
[07:54] SPEAKER: Well, hey, any amount of damage is acceptable as long as the number goes up.
[08:24] SPEAKER: [music]
[08:27] SPEAKER: Welcome to Brad and Will Made a Tech Bot. I'm Will.
[08:30] SPEAKER: Hi, I'm Brad. Hello. That was the shortest cold open to show in history. You waited
[08:35] SPEAKER: looking at mine. It was like five seconds, maybe.
[08:37] SPEAKER: Not even five seconds from ending that cold open to saying welcome.
[08:41] SPEAKER: Well, okay, so here's the thing, though. That was when PCs went from being a thing that you
[08:46] SPEAKER: put on your desktop to a laptop for most people, that Centrino bump. That's what the OEMs think
[08:52] SPEAKER: is going to happen. I'm breaking all sorts of rules here because we're carrying over the cold
[08:57] SPEAKER: open conversation into the main episode anyway. What was the timeframe for Centrino? I'm looking
[09:02] SPEAKER: it up. I can tell you. 2002, 2003.
[09:04] SPEAKER: 2003, yeah. Sure.
[09:08] SPEAKER: It was around the time when battery life was getting to the point that laptops would run for
[09:12] SPEAKER: a few hours rather than an hour. The screens were okay. LCDs were getting good. It was an actual
[09:21] SPEAKER: moment. They were doing Super Bowl ads where it was like, "Hey, look at me. I'm watching the
[09:26] SPEAKER: Super Bowl and I have my stats open at the same time." It was a big deal.
[09:32] SPEAKER: Yeah. We were rolling up on that. What was it? 2006, probably, when the first plastic
[09:37] SPEAKER: MacBooks came out. The ones right before the first aluminum unibody.
[09:42] SPEAKER: The aluminum unibody was later that night. I was supposed to say 2008 or 2009.
[09:46] SPEAKER: Yeah, because I bought one when I started a giant bomb and they had just come out. Then I was
[09:50] SPEAKER: extremely excited to have my first laptop. Brian had had one of the white plastic MacBooks before
[09:55] SPEAKER: that. I remember that was the first laptop I looked at and was like, "Oh my God, that looks
[09:59] SPEAKER: awesome. Finally, that looks like something I would actually spend money on."
[10:02] SPEAKER: Yeah. When I started at giant bomb, my desktop, I had a desktop that I think I built or brought
[10:10] SPEAKER: or something. I can't remember. I used a laptop. It was my main computer there. It was the first
[10:17] SPEAKER: time that it ever happened because I'd always had desktops before then. That was in 2010.
[10:21] SPEAKER: Brad, today, speaking of white plastic MacBooks.
[10:25] SPEAKER: Speaking of more and more functionality being condensed into smaller and smaller devices.
[10:29] SPEAKER: Yeah. Last week was WWDC, the worldwide developer conference for Apple, which is, I think,
[10:37] SPEAKER: the keynote for that is the most dense, "Hey, here's what we're doing and here's what we think
[10:42] SPEAKER: about what we should be doing," that they give all year. The rest of their keynotes are about
[10:46] SPEAKER: selling something, and this is about selling them, their software. I think it's worth delving into,
[10:53] SPEAKER: even for people who aren't Apple people. This was an interesting one. On the heels of Computex,
[11:02] SPEAKER: where everybody was talking about AI, AI, AI, AI, AI, and then Nvidia's stock went up and they
[11:09] SPEAKER: became a $3 trillion company and yada, yada, fortunes were made, all this stuff. It was
[11:18] SPEAKER: interesting. Coming out of Computex, I thought, "In order to have a communication with shareholders
[11:26] SPEAKER: that works out for these big tech companies, this is the year that everybody's going to explain
[11:30] SPEAKER: their AI strategy." On the hardware side, it's just like, "Hey, we got tops." On the software
[11:37] SPEAKER: side, Microsoft is like, "Hey, you're going to be able to do all this stuff with AI," and then
[11:42] SPEAKER: they don't show you anything you can do with AI that any normal human being is ever going to want
[11:48] SPEAKER: to do. Or, alternately, they show something that's super highly specific, that's like a specialist
[11:53] SPEAKER: task like checking radiology images for tumors or machine robotic vision stuff or whatever.
[12:03] SPEAKER: That stuff's cool. I'm okay with that stuff. The generating images to send to your mom a Mother's
[12:08] SPEAKER: Day card. Father's Day is coming up, and I would much rather have my daughter and wife draw some
[12:14] SPEAKER: shit with crayons than go to mid-journey and generate a card for me. What if your phone
[12:22] SPEAKER: could generate something from something they drew with crayons? That sounds a little bit better,
[12:26] SPEAKER: I guess. Anyway, it seems like they've spent a lot of time thinking about, "Hey, here's what
[12:31] SPEAKER: the AI demos are that normal people are going to actually want." It seems like they still employ
[12:38] SPEAKER: people at Apple that use computers like normal human beings. We didn't talk about it, really,
[12:46] SPEAKER: because it was terrible, but the Google keynote from their developer conference a couple weeks
[12:49] SPEAKER: ago from Google I/O, their AI examples were like, "Do any normal people still work at this place?
[12:56] SPEAKER: This is all weird shit." Anyway, they started, as they often do at WWDC, with a really cringy
[13:04] SPEAKER: segment in an airplane. They skydove. It kind of reminded me of that Google Glass keynote that we
[13:11] SPEAKER: talked about a few months ago when they had the action sports people jump out of the airplane.
[13:18] SPEAKER: It's exactly that, except fake. Yeah, except for they faked it.
[13:21] SPEAKER: Shout out to... Oh, sorry. It's not Dr. Feelgood. It's Kickstart My Heart. We were talking about
[13:28] SPEAKER: this before the show. The pilot, as they were about to skydive, puts on a Motley Crue song on-
[13:32] SPEAKER: That's Phil Schiller, just to be clear. What's that?
[13:34] SPEAKER: The pilot was Phil Schiller. Oh, was it?
[13:37] SPEAKER: Yeah. I believe a pilot in real life is the joke.
[13:40] SPEAKER: I would believe that. I referred to it to you before we started as a retro iPod, and then I
[13:46] SPEAKER: felt weird about that. It's the first iPod.
[13:48] SPEAKER: Well, yes, but also we were adults when that came out. We were professionally doing this stuff when
[13:55] SPEAKER: that came out, and now thinking of it as retro is very strange.
[13:57] SPEAKER: Look at my hairline. It was definitely retro.
[14:00] SPEAKER: Yes. Very good production values. If anybody on earth has the money to throw
[14:06] SPEAKER: at making a dumb bit look really nice in their presentation, it is Apple.
[14:11] SPEAKER: Yeah. It's maybe the most expensive dad joke I've ever seen.
[14:15] SPEAKER: Sure. Yeah.
[14:17] SPEAKER: The fact that they had all the presenters parachuting out of this, except for Tim,
[14:20] SPEAKER: parachuting out of this plane. He was already standing on the roof.
[14:24] SPEAKER: Yeah. Craig Federinghi's bicycle helmet/skydiving helmet that they clearly built on one of their
[14:31] SPEAKER: CNC machines in there was pretty good. It was a very silly, very silly bit.
[14:36] SPEAKER: God, I didn't even think... I mean, of course Apple has unbelievable amounts of expensive
[14:40] SPEAKER: rapid prototyping hardware, but I just never really thought about how freeing that would be.
[14:45] SPEAKER: Somebody has to... Yeah.
[14:47] SPEAKER: Just to be able to just make something like a helmet to spec whenever you need it as a prop.
[14:53] SPEAKER: Go sculpt me a fancy hair helmet for a one-off joke with a glint on...
[14:57] SPEAKER: At least they didn't do the glint on the teeth when he smiled and winked at the camera.
[15:00] SPEAKER: Sure. Sure. Well, it's one thing though to be able to iteratively work on better and
[15:06] SPEAKER: better chamfering on your phone housing, but to be able to just go make a thing like a helmet.
[15:12] SPEAKER: Like think about the room. They have the lab and then they have a room,
[15:15] SPEAKER: a warehouse full of blocks of styrofoam to carve shit out of.
[15:18] SPEAKER: Right. They just have untold amounts of raw materials.
[15:21] SPEAKER: Yeah. So, okay. So then they actually talk about what's going on. There was the normal
[15:25] SPEAKER: bit about how awesome we are as a company and how well things are going for us. They talked about...
[15:31] SPEAKER: I'm going to go just in the interest of making this something if you want to scroll through the
[15:35] SPEAKER: videos to see pictures of. At the same time we're talking about it, I'm going to go in order they
[15:40] SPEAKER: went, which is probably... I think I get why they went in this order. It's probably not what I would
[15:45] SPEAKER: have done, but hey, that's why I'm not in charge. They talked about Vision OS first. The people who
[15:52] SPEAKER: use Apple Vision Pro a lot seemed generally underwhelmed that they called this Vision OS 2
[15:59] SPEAKER: about the four month mark since this thing came out, five months mark since this thing came out.
[16:03] SPEAKER: Sure. Well, let's say maybe they feel they need to goose the excitement around this
[16:07] SPEAKER: headset a little bit. Yeah. The big feeling I got about this is that photos must really
[16:13] SPEAKER: move hardware. There's a bunch of stuff about the enhancements to the way the spatial photos work.
[16:19] SPEAKER: Yeah. I mean, I'm happy for people who are excited by stuff like that. I don't really
[16:23] SPEAKER: get the appeal because it's all fake. I mean, it's not recording any actual spatial data,
[16:28] SPEAKER: right? I assume it's just carving up a 2D image, right?
[16:31] SPEAKER: No. So the phone will record actual spatial data because it has a depth camera. Yeah. The
[16:37] SPEAKER: iPhone, since the 12 or 13 or something, had a depth camera on the back.
[16:42] SPEAKER: Okay. I guess I couldn't see that from the on-screen demo they gave necessarily,
[16:45] SPEAKER: but I guess that... Okay. There is some value to it if you're replicating actual real world space.
[16:50] SPEAKER: Yeah. The depth effect is nice. I don't know. Clearly the people who... They have data about
[16:59] SPEAKER: the people who are using that that are really... When I used Norms, I watched some videos of his
[17:03] SPEAKER: kids and it was cool. It felt more like you were watching a real thing in the same way that it was
[17:09] SPEAKER: super dystopian because you were sitting there with the headset on. We don't need to get to that.
[17:11] SPEAKER: We've talked about that before. They added new gestures that make it easier to open the home menu,
[17:17] SPEAKER: check the time, stuff like that. You don't have to stare up at the ceiling anymore like you used to.
[17:22] SPEAKER: The big thing, I think, was the virtual display enhancement for Mac users, where if you look at
[17:30] SPEAKER: your MacBook, you can just pop up a virtual display. You can open the display basically
[17:35] SPEAKER: on your headset. The keyboard, if you have a MacBook, a Mac keyboard now, it'll punch through
[17:41] SPEAKER: the VR so you see the physical object in your representation of the virtual world, which is good.
[17:50] SPEAKER: Those two things work together to give you an enormous virtual display that's... They support
[17:56] SPEAKER: ultra-wide screen and huge... They were making it huge. It looked like it wrapped around your
[18:00] SPEAKER: whole... It looked like a real neck killer the way they showed it in the video, but I think there's a
[18:04] SPEAKER: way to do that that it would be incredibly useful. - I think, didn't they describe it as it's like
[18:08] SPEAKER: having two 4K displays side by side in terms of real estate, which is quite a lot of screen? I'm
[18:14] SPEAKER: curious why this is just now coming about. Are there improvements in bandwidth they've hit or
[18:18] SPEAKER: something? Why couldn't they do this before, I guess? - My guess is that they needed something
[18:23] SPEAKER: to be in sync on OS 10 and... Or OS 11, sorry. - It's like 15 now, right? - Oh, right. They
[18:32] SPEAKER: went back to numbering, right? So it's Mac OS, sorry. They needed something to be in sync
[18:39] SPEAKER: across both. So they were probably using something fairly straightforward, like a remote desktop or
[18:43] SPEAKER: something, and now it's something... We'll talk about more in the future, but they have a thing
[18:48] SPEAKER: in Mac OS that lets you pull your iPhone into the desktop, and it seems like they've done something
[18:54] SPEAKER: to make the latency go down on that. So I wonder if they had some fundamental work that they did to
[18:58] SPEAKER: improve this technology. Because it seems like for Vision Pro, there's uses for bringing your phone
[19:03] SPEAKER: and your watch screen and stuff like that, and bringing your phone into the MacBook,
[19:07] SPEAKER: bringing your Mac into the Vision Pro. It seems like they've done some work.
[19:12] SPEAKER: There's a train mode, because it uses accelerometers and gyroscopes as well as SLAM
[19:18] SPEAKER: to position yourself in the world. So when you're inside a closed environment that the SLAM is
[19:24] SPEAKER: registering no movement, but your gyroscopes and accelerometers are registering movement,
[19:30] SPEAKER: you need a different algorithm to counteract that differentiation.
[19:39] SPEAKER: They had a plane mode before. Now you have a train mode, too. Don't use this on the subway,
[19:45] SPEAKER: because you'll get mugged, please. And then there's an AirPlay receiver. So you can AirPlay
[19:51] SPEAKER: stuff from phones or iPads or other devices into the Apple Vision Pro, which seems good.
[19:57] SPEAKER: That all sounds nice, but nothing moving the needle exactly. I see people
[20:02] SPEAKER: hand-wringing a bit about the relative success or failure of that device to date.
[20:08] SPEAKER: So I think this is still the normal loop. If you look at when the iPad came out in March,
[20:15] SPEAKER: they did the second version of the iPadOS, but it was just a 0.2 or something that fall. This
[20:20] SPEAKER: feels like that. I think next year is the year that you see the crazy stuff. They did talk about
[20:28] SPEAKER: having an app adoption, having 2,000 apps, so they have basically one app for every person who's
[20:33] SPEAKER: using one of those every day now. Look, I think that there's a world... If I was a primary Mac
[20:42] SPEAKER: person and I was sitting in our whiskey basement where there was a bazillion people around,
[20:48] SPEAKER: we didn't have a bunch of big monitors, there wasn't room for a bunch of big monitors,
[20:51] SPEAKER: I could see using something like that. Ryan would have mocked you mercilessly.
[20:56] SPEAKER: I think Ryan would have just walked up and punched me in the back of the head every time I had it on,
[21:00] SPEAKER: probably. But anyway, that's VisionOS. I don't think we need to spend any more time on it.
[21:05] SPEAKER: Who cares? The interesting thing about this keynote is they just spent an hour talking
[21:13] SPEAKER: about the first whole half. They didn't really talk about AI stuff at all. Occasionally they'd
[21:17] SPEAKER: say this is machine learning enhanced or something like that. We'll have some of that stuff in here.
[21:23] SPEAKER: This is also where Craig ripped off the quick release jumpsuit and was wearing his normal nerd
[21:30] SPEAKER: shit underneath. The first thing they showed was cosmetic stuff. The home screen adjustments,
[21:38] SPEAKER: where you have night mode and day mode for icons, as well as your wallpaper and images and stuff
[21:44] SPEAKER: like that. This stuff I'm kind of excited about. The first thing they showed is something that
[21:49] SPEAKER: Android people have had since the very first release of Android. I definitely saw plenty
[21:54] SPEAKER: of Android users confused at that, getting attention, just like, "Wait, you couldn't
[21:58] SPEAKER: do that already?" Nope. They've been at the top and going down ever since iOS launched.
[22:03] SPEAKER: You can kind of cheat it by using the app tray shortcut, like Siri suggested apps. You can have
[22:08] SPEAKER: some apps at the bottom and some apps at the top. If you want to have your apps all near the bottom
[22:13] SPEAKER: of the phone where your thumb is, you can do that now. Yay. Exciting. I guess good. The icon styles
[22:20] SPEAKER: for dark mode are cool. The thing I couldn't tell was if developers have to generate these or if it
[22:26] SPEAKER: happens automatically. It seemed at first like developers had to generate them. Then the way
[22:30] SPEAKER: they were showing it working, it looked like it just happens automatically, which is really cool.
[22:34] SPEAKER: Yeah. Like the iPad. Maybe iPhone, iOS as well, but definitely iPad has been able for years to
[22:41] SPEAKER: just do smart color invert as an accessibility feature. Yeah. Yeah. That's simple math, right?
[22:47] SPEAKER: Yeah. I wouldn't be surprised if they're doing something similar.
[22:50] SPEAKER: I think they're pulling background and foreground out using the onboard machine stuff and then
[22:57] SPEAKER: adjusting tones intelligently based on that. You can also theme your tones across the entire
[23:03] SPEAKER: thing. If you want to make all of your icons have a green tint or yellow tint or a blue tint,
[23:07] SPEAKER: you can do that. I enjoyed people on Twitter pulling the brand guides, brand Bibles for
[23:14] SPEAKER: let's like meta, Google. I'm trying to think of two or three others. I saw all of them. All of
[23:22] SPEAKER: them are like, this should be the logo. This is how the logo should always be presented. It should
[23:26] SPEAKER: never be changed in shape or size or color. Does meta own my phone or do I own my phone?
[23:33] SPEAKER: Apple do not care. Yeah. You've been able to do this with Android Launchers for ages too. This
[23:38] SPEAKER: is a thing that's been around for years and years. I watched people when they let you create custom
[23:44] SPEAKER: shortcuts, icons for shortcuts. People went ham doing this with their phones and instead of having
[23:52] SPEAKER: screens full of apps, they had screens full of shortcuts to their apps that were the custom
[23:57] SPEAKER: shortcut. Basically, you made a shortcut that looked like the app and had the same name as
[24:02] SPEAKER: the app and had a different icon for the app that was a shortcut to launching the app.
[24:06] SPEAKER: That is an incredible amount of work to change an icon.
[24:10] SPEAKER: It took a lot of time. When we got the tray on iOS and were able to keep most of the applications
[24:19] SPEAKER: there and use the homepage as a screen of shortcuts, which is what I switched to
[24:23] SPEAKER: immediately. Do you still have wall after wall of icons?
[24:28] SPEAKER: Yes, but only because I'm too lazy. We'll talk about it later. Another feature they announced
[24:34] SPEAKER: is something I'm going to finally use to clean up my years of cruft on my home screen.
[24:40] SPEAKER: You can change the tense. People were posting some real horror shows on Blue Sky and Twitter that I
[24:46] SPEAKER: saw that they'd created. I am excited. I think this is a legit exciting feature. It means
[24:53] SPEAKER: everybody's phones aren't going to look exactly the same, which is nice. It means if you have
[24:57] SPEAKER: a picture of your kid on your homepage, you can move the icon so they don't cover up their face,
[25:01] SPEAKER: which I also like. They're changing control center. I'm not sure about this one.
[25:09] SPEAKER: Really? This was one of probably the biggest things I was bullish on.
[25:13] SPEAKER: Control center is the thing you swipe down from the top right. It has hot shortcuts.
[25:18] SPEAKER: Oh, on your phone. Yes. Okay. I'm sitting here going, "Oh, it's from the bottom up."
[25:23] SPEAKER: You're on the old phone.
[25:24] SPEAKER: Phones with home buttons. Yeah. You swipe down from the top right. It has controls for music
[25:30] SPEAKER: playback, your Bluetooth audio outputs, some home stuff, volume, brightness, airplane mode,
[25:38] SPEAKER: Bluetooth. You can customize all kinds of stuff. I think that's the biggest thing here is that it's
[25:44] SPEAKER: far more customizable now, and it sounds like third-party developers can start adding widgets
[25:48] SPEAKER: to it now as well. Even before, you'd put the Notes app in there, alarms, the QR code reader.
[25:54] SPEAKER: Trying to think what else. Flashlight. I'm trying to think what else I've got online.
[25:57] SPEAKER: All of those shortcuts are now stuff that people can develop into, can build into. That was
[26:02] SPEAKER: previously locked back. Also, it means that the flashlight and camera button on your home screen
[26:08] SPEAKER: are not fixed anymore, and you can control what goes there. The thing that I don't know that I
[26:14] SPEAKER: love is adding multiple pages. I think that that's a place where having a quick access with one page
[26:20] SPEAKER: is really valuable, and having multiple pages seems like a step back. Yeah. I mean, it's optional.
[26:24] SPEAKER: You know, I kind of see where you're coming from, but it seems like they've also just expanded the
[26:28] SPEAKER: size of the page. Well, it scrolls infinitely right now. Does it? Yeah, mine does. I realized
[26:33] SPEAKER: I didn't. So all of my Apple home stuff is in there, and mine got kind of long as a result.
[26:39] SPEAKER: I do kind of like the idea of moving the home automation stuff onto its own tab,
[26:42] SPEAKER: and I think the media playback stuff goes on its own tab is the way it looked like in the screenshots.
[26:47] SPEAKER: Is that mandatory? It seems like it's structured because there are icons for the second and third
[26:52] SPEAKER: pages. Interesting. Maybe there's more pages after that you can make. I don't know. Okay. Home
[26:56] SPEAKER: controls are like the thing I use Control Center for the most, so I hope those are not like extra
[27:00] SPEAKER: clicks to get to now. My guess is that that front page is still you can put whatever you want on it,
[27:04] SPEAKER: and then the other two are specialized. You also can bind if you have a phone with the action
[27:10] SPEAKER: button, which is what they replaced the hardware silent switch with. You can bind that to whatever
[27:19] SPEAKER: you want to any of these actions now too, it seems like. That's cool. I kind of wish they had just
[27:24] SPEAKER: added the action button to the physical mute toggle and not replaced. But it doesn't work
[27:29] SPEAKER: because then it's because the physical mute toggle is on and off, and this is a momentary.
[27:37] SPEAKER: No, no, I'm saying that's what I mean. You could have just left the mute toggle as it was and given
[27:41] SPEAKER: you an action button to customize separately from that. I just appreciate having the physical
[27:46] SPEAKER: feedback of just sticking my hand in my pocket and knowing instantly if the phone is already
[27:50] SPEAKER: muted or not. That's true. They had new privacy stuff. You can lock an app so that you say this
[27:59] SPEAKER: needs a face ID or touch ID or code authentication before you open it. That also means when you do
[28:08] SPEAKER: that, it means that the bits from inside that app won't show up for Siri or search or presumably
[28:12] SPEAKER: the AI stuff unless it's unlocked, which is good, I guess. I feel like this is something that
[28:18] SPEAKER: corporate people want probably because you work in HR at some big company, you can put your HR
[28:24] SPEAKER: app behind those locks and then you're not accidentally leaking information into Siri and
[28:28] SPEAKER: search. Yeah, that makes more sense than I was trying to figure out how in a parental control
[28:32] SPEAKER: context this would be useful because I guess maybe parents hand their phone to their children
[28:37] SPEAKER: occasionally, but what you're describing makes a lot more sense. Well, so parents hand phones to
[28:41] SPEAKER: kids a lot. There's some things like password manager is a bad example because it automatically
[28:47] SPEAKER: unlocks, but the other example I'm sure is porn. People who have their homebrew porn don't want to
[28:55] SPEAKER: have that on their phone where it's easily accessed in case they hand their phone to somebody, right?
[29:02] SPEAKER: The other one is you can hide apps and put them in a locked folder that just isn't visible at all,
[29:08] SPEAKER: which there's a lot of reasons you would want that. We don't need to speculate about that,
[29:13] SPEAKER: I guess. Then there's more granular controls over context sharing. Just to be clear, I'm sure that
[29:20] SPEAKER: people in the Discord comments thread are going to post a whole bunch of entirely innocent reasons
[29:28] SPEAKER: you would want that. I have not been able to come up with any of them in the two days that I've been
[29:32] SPEAKER: thinking about this. More granular controls over context sharing. When an app asks you for access
[29:39] SPEAKER: to your contacts, it will say, instead of saying, "Hey, do you want to give no access to your
[29:44] SPEAKER: contacts or access to all of your contacts?" You can say, "No, I only want to give access to these
[29:49] SPEAKER: two contacts because these are the two that matter." Just how the photo library works with a
[29:53] SPEAKER: lot of apps now? You have to approve each photo. Exactly. Then the same thing again for local
[29:57] SPEAKER: device access. It'll say, "Okay, my scale app is able to connect via Bluetooth to my scale,
[30:04] SPEAKER: and my blood pressure cuff app is able to connect via Bluetooth to my blood pressure cuff,
[30:08] SPEAKER: but they don't get access to my Apple TV and all the other devices on my LAN." This is good stuff.
[30:15] SPEAKER: They've added RCS support to messages. I missed that until I saw it in your notes
[30:19] SPEAKER: just now. That's huge. I guess every other carrier and endpoint phone target also needs
[30:26] SPEAKER: to support it before that really matters. No, it's already done. We're already there.
[30:29] SPEAKER: Is Apple literally the last one? Apple is the last one. I think a couple of
[30:32] SPEAKER: the carriers in the US don't, but presumably they'll come online around the time they do.
[30:38] SPEAKER: RCS is the successor protocol to SMS, which was the original text message standard,
[30:43] SPEAKER: which I was looking at it a little bit recently. I don't have the whole feature list in front of me.
[30:47] SPEAKER: It's not, I don't think it's as good as iMessage or messages or whatever you're calling it these
[30:50] SPEAKER: days. It's not as good as any of the proprietary things, but it's better. It's bigger pictures,
[30:58] SPEAKER: more Unicode support, stuff like that. It's text messaging that's getting closer
[31:03] SPEAKER: to the feature set of something like iMessage. I want to say initially it was not end-to-end
[31:09] SPEAKER: encrypted, but that actually Apple might've stepped in. I think they got involved with
[31:13] SPEAKER: revising the spec and it might be encrypted now. I'm not sure.
[31:16] SPEAKER: I don't know about that. The encryption was back and forth,
[31:20] SPEAKER: so I don't know where it ended. I should look that, but the bigger point,
[31:22] SPEAKER: especially with just all the blue bubble, green bubble, message war shit that gets extremely
[31:28] SPEAKER: tedious. Having a better baseline text messaging standard kind of helps there.
[31:35] SPEAKER: I don't know that it helps with the spam problem, unfortunately.
[31:38] SPEAKER: Yeah. God, that's gotten awful.
[31:43] SPEAKER: It does mean that if you send a photo to an Android person, they're not going to get a
[31:47] SPEAKER: 2007 resolution photo back, which is nice. Yes. That's the important stuff.
[31:53] SPEAKER: I don't think RCS is probably worth a full episode. Maybe when we do another potpourri
[31:57] SPEAKER: small topic episode, we'll put it in there because it seems like we could do a half
[32:00] SPEAKER: episode on that probably. Tap backs. Now, the little exclamation point or thumbs up or thumbs
[32:06] SPEAKER: down or question mark or haha, you can add. Now, you can add any emoji, any sticker,
[32:16] SPEAKER: and the new generated emojis, which we'll talk about in a minute, I think. I'm not sure about
[32:21] SPEAKER: that, actually. You can do scheduled sends. The Android people are laughing again because that's
[32:26] SPEAKER: been an Android forever. You can do more text formatting. You can do strikethroughs and text
[32:32] SPEAKER: now. You can be extra smarmy in your text messages. There's more text effects, so more
[32:40] SPEAKER: bumps and bangs and drizzles in and all that stuff. You can do satellite. You can send
[32:45] SPEAKER: messages via satellite. Yeah, that seems huge.
[32:49] SPEAKER: I don't think you can receive messages via satellite. I think they were very careful
[32:52] SPEAKER: to only say send. It works the same way as their remote, "Hey, I'm stuck away from the
[33:00] SPEAKER: cell network and I'm trapped." The 137-hour scenario, basically.
[33:04] SPEAKER: Yeah. The number of situations of somebody hiking in the wrong direction in a national
[33:09] SPEAKER: park and getting in major trouble that this could help alleviate is pretty huge.
[33:13] SPEAKER: Yeah. I know people whose lives probably wouldn't have been saved by this.
[33:17] SPEAKER: I also know someone, yes. Did they go into detail about how this is available? Can you just
[33:24] SPEAKER: turn this on and use this at any time, or does it depend on certain network conditions not being
[33:28] SPEAKER: present before it'll offer it? You have to be offline.
[33:32] SPEAKER: You have to be someplace where you're outside of range of cell service. You basically say,
[33:38] SPEAKER: "Hey, it pops up a thing," and you have to do the thing where you aim it at the sky in
[33:42] SPEAKER: the right place and all that stuff. It helps you get there.
[33:45] SPEAKER: I hope that logic is foolproof. I hope it's not like, "Oh, it technically thinks it can
[33:49] SPEAKER: see a signal, so it's not going to give you this," even though the signal is not actually
[33:52] SPEAKER: functional type stuff. I've had the SOS stuff pop up on my iPhone
[33:56] SPEAKER: before when there's no signal. When I hit the button, it gave me the option to start the thing.
[34:08] SPEAKER: They're not charging for this, which I thought was interesting.
[34:10] SPEAKER: Yeah, that's awesome.
[34:11] SPEAKER: I assume the cost is low. I am curious if it's two-way. It seems like it's only one way. It's
[34:16] SPEAKER: like, "Hey, did you get to the campsite?" "Yeah, I got to the campsite."
[34:20] SPEAKER: I'll tell you when I get to the campsite was the example they gave, I think.
[34:24] SPEAKER: It would be a little nerve-wracking in a disaster situation. You can update people you know with
[34:28] SPEAKER: what's going on, but then you won't know until somebody shows up.
[34:32] SPEAKER: Don't know if people left you unread. Well, in the disaster situation, you get two-way.
[34:37] SPEAKER: When you use the SOS, you get a, "Hey, we're connecting you with blah, blah, blah,"
[34:41] SPEAKER: and then they dispatch somebody to your position. You can send pins, I think, was one of the things
[34:47] SPEAKER: it said you could do. That's interesting. It works with SMS and iMessage users, so they'll
[34:54] SPEAKER: get you over to the SMS network. They added a bunch of new mail stuff,
[34:58] SPEAKER: which I'm always curious about how many people actually use the Apple Mail app on their phone.
[35:03] SPEAKER: Yeah, I use it occasionally. That's what I use for mail if I use mail on my phone,
[35:08] SPEAKER: for what it's worth. Oh, really?
[35:09] SPEAKER: I'm mostly tied into various Gmail/Google apps accounts.
[35:14] SPEAKER: Yeah, I just use the Gmail app. I'm messing up.
[35:18] SPEAKER: I guess that would work, too.
[35:22] SPEAKER: I've started using it on the job hunt, because I set up a special email address just for that,
[35:26] SPEAKER: so that I would not have 23 years of spam coming into those addresses, as well.
[35:34] SPEAKER: The big thing that they're doing is auto-categorization of messages,
[35:38] SPEAKER: not just based on who are your priority contacts, but based on stuff you've interacted with. They're
[35:43] SPEAKER: applying machine learning to spam filtering and mail categorization, so it knows that this is all
[35:50] SPEAKER: from the same company. It'll dump those all together and give you digest versions and stuff
[35:54] SPEAKER: like that, which is kind of interesting. They're adding trail hikes to maps.
[36:01] SPEAKER: You can send cash directly from person to person by bumping your phones together.
[36:06] SPEAKER: That seems awesome. Obviously, A, it's only with other iPhone users. B,
[36:10] SPEAKER: they need to be opted into Apple Cash, so it's a relatively limited,
[36:15] SPEAKER: self-selecting pool of people you can do this with.
[36:17] SPEAKER: I think everybody can get, send, and receive Apple Cash if you have a credit card attached
[36:22] SPEAKER: to your Apple ID. You might be right.
[36:26] SPEAKER: You might have to have a phone that'll do Apple Cash transactions.
[36:31] SPEAKER: I got Apple Cash. My sister-in-law sent me Apple Cash when I had never used it before,
[36:35] SPEAKER: and had never signed up for anything. It just shows up as a credit to your credit card?
[36:40] SPEAKER: Here's 90 bucks. To your credit card?
[36:43] SPEAKER: No, it shows up in my Apple Cash bucket. Apple became a bank.
[36:46] SPEAKER: Oh, right. Okay, yes. I forgot that they are technically their own financial intermediary now.
[36:52] SPEAKER: So it just sits in limbo? It's like a PayPal, right? Basically, it's like until you set up
[36:57] SPEAKER: an actual bank account or something to transfer it into, it just kind of sits there?
[37:02] SPEAKER: Yeah. I could transfer it back out to my debit card,
[37:04] SPEAKER: or alternately, you could just use it anywhere that people take Apple Pay.
[37:10] SPEAKER: Yeah, that's fine. The nice thing about it is it's anonymous. If you're buying something
[37:17] SPEAKER: at a street fair or something, you don't want to give that person your email address or Venmo or
[37:20] SPEAKER: whatever, you could just bump your phone to their phone, and then they don't have to have a square
[37:24] SPEAKER: payment or anything. It's just a cash transaction. I assume there are limits on how much you can do
[37:29] SPEAKER: that, so they don't have vendors just using it instead of a cash register.
[37:33] SPEAKER: Yeah, I'm just thinking of my youth, how often you'd be out with friends,
[37:38] SPEAKER: splitting drinks, going out to dinner, stuff like that, just the ease of being able to just
[37:42] SPEAKER: throw money at each other. That seems huge. Or like when we were working in the same office,
[37:47] SPEAKER: and you'd be like, "Hey, can you run grab me?" You're going to the Udon place where you grab me
[37:50] SPEAKER: some noodles, and then I had to figure out how to get you $9. Yeah, so this is good. Venmo has
[37:57] SPEAKER: already solved this problem for people you know, but the anonymity is nice. They're adding game
[38:03] SPEAKER: mode. This has been on the Mac for a minute. It minimizes background activity, turns off
[38:07] SPEAKER: notifications and stuff like that, and it improves the responsiveness of your Bluetooth
[38:13] SPEAKER: controller and AirPods. I don't know how it does that. I'm curious about that. I got to read about
[38:18] SPEAKER: that. Photos are getting more machine learning stuff, which we'll talk about in a minute,
[38:25] SPEAKER: but they did a complete redesign. It's a unified app with a single view. There's no more of those
[38:29] SPEAKER: multiple tabs where you're like, "Where's my camera roll? I can't find my camera roll. What
[38:33] SPEAKER: even is a camera roll anymore?" The grid shows your entire library, it looks like now, scrolling
[38:39] SPEAKER: back infinitely in days, months, or years. It has a bunch of collections that seem to be auto-generated.
[38:46] SPEAKER: They talked about those more in the AI section at the end, so we'll come back to that, I guess.
[38:50] SPEAKER: Yeah, that all seems good. The Photos app has been a mess for a while to me.
[38:55] SPEAKER: The thing that they do that I really like, because most of my other... Google constantly wants me to
[39:00] SPEAKER: delete screenshots and receipts. I take pictures of screenshots of things that I need to save,
[39:05] SPEAKER: and then they end up in my photo roll. I don't want to delete them, but Apple was just like,
[39:10] SPEAKER: "Hey, what if we hide them? That sounds great. We'll hide this shit out of those."
[39:15] SPEAKER: I use a standalone app for that kind of thing.
[39:18] SPEAKER: That's crazy.
[39:19] SPEAKER: Well, I've been using it since before. It was viable to use just your photos for that
[39:23] SPEAKER: sort of thing. I use Genius Scan, remember that?
[39:26] SPEAKER: Yeah, I used to use that.
[39:28] SPEAKER: Mainly because it can... What's the term? It basically can take a photo and make it
[39:33] SPEAKER: grayscale very easily, something like a receipt or an NDA, which I've signed a shitload of NDAs
[39:38] SPEAKER: in my career. You know what I mean? It's basically as good as kind of having a scanner. You can take
[39:42] SPEAKER: a picture of a thing and it'll kind of flatten it and make it look more presentable as a document,
[39:46] SPEAKER: and it can export to PDF straight into your Dropbox very easily.
[39:49] SPEAKER: Well, so the Dropbox app just does that now too.
[39:52] SPEAKER: Oh, does it?
[39:52] SPEAKER: Yeah.
[39:53] SPEAKER: Interesting.
[39:53] SPEAKER: Has for a long time. Genius Scan got eaten by everybody else who works with
[39:58] SPEAKER: Docu... Because I think your iPhone will even do that if you send it to your drive folder now.
[40:03] SPEAKER: Anyway, that's it. That was it for iOS stuff. It seems pretty good.
[40:09] SPEAKER: Yeah, it's a lot of stuff.
[40:11] SPEAKER: The audio and home section was next. If Siri asks you something while you have your AirPods in,
[40:16] SPEAKER: you can shake your head or nod your head to answer.
[40:19] SPEAKER: That is right up there behind shaking your phone to undo on the list of public gestures
[40:24] SPEAKER: I'm not really keen to make.
[40:27] SPEAKER: It's just a real subtle one.
[40:28] SPEAKER: I don't know, man.
[40:29] SPEAKER: I thought this was good. I use my AirPods a lot though.
[40:32] SPEAKER: I mean, I can see the utility. You just look kind of silly.
[40:35] SPEAKER: I mean, I have white sticks hanging out of my ears. I remember how silly those
[40:39] SPEAKER: were when they first came out. Now you can't walk anywhere without seeing 10 pairs of them.
[40:42] SPEAKER: Yeah. You know, I guess people are used to just seeing individuals walking around talking to
[40:47] SPEAKER: nobody now, that kind of thing. So whatever.
[40:50] SPEAKER: It used to be that we assumed they were old,
[40:52] SPEAKER: like '80s Mac fans when you saw that at Macworld. They do voice isolation when you're using your
[40:57] SPEAKER: AirPods walking around in loud or windy areas so that they just pull out the voice for the receiver,
[41:03] SPEAKER: for the person who's not you. So you're talking to somebody on the phone and they get a clear
[41:07] SPEAKER: signal even though it's loud. I feel like they've done this for years and they're just doing a
[41:12] SPEAKER: better version of this now. And then personalized spatial audio is coming to games. This is the
[41:17] SPEAKER: thing where you take a picture where you scan your ear with the depth camera and they change
[41:22] SPEAKER: the way the model for the spatialized audio works based on that, which works shockingly well.
[41:28] SPEAKER: I already gave my ears to Mark Cerny. Sorry.
[41:31] SPEAKER: Sorry, Mark Cerny. They also have stuff coming for HomePods, but it all seemed kind of tedious.
[41:39] SPEAKER: TVOS stuff, they're adding Insight, which is basically Amazon's X-ray feature.
[41:45] SPEAKER: Yeah.
[41:45] SPEAKER: The thing where it shows you what actors on the screen and what music's playing in the background,
[41:49] SPEAKER: and there's a little bit about the show.
[41:50] SPEAKER: Yeah. I thought Amazon may have some form of this, but in this case, you can click the song
[41:57] SPEAKER: and add it straight to your Apple Music Library, which is a nice tight integration with their music
[42:01] SPEAKER: service.
[42:02] SPEAKER: Yeah. So Amazon's X-ray started as a Kindle feature where it would tell you, it would pull context
[42:09] SPEAKER: related information out of the book that you were reading and you could click on it. It was really
[42:14] SPEAKER: great when you're reading Game of Thrones books, because there were so many fucking characters.
[42:17] SPEAKER: So you'd click on it and it would give you the quick bio of the character and show you all the
[42:22] SPEAKER: other places that person's name popped up. They added it to the Amazon video service.
[42:31] SPEAKER: They don't do music, I think. Maybe they do music, but it's mostly actors, I think is what I've seen
[42:35] SPEAKER: there. It's basically the kind of thing you only see when you pause the TV, because I don't ever
[42:39] SPEAKER: use it. This stuff also comes up on your phone when you use your phone as the remote. They're
[42:47] SPEAKER: adding enhanced dialogue for more TVs and more speakers, including AirPods and HomePods, which
[42:53] SPEAKER: is good. The enhanced dialogue thing is the thing that basically uses filtering to make voices
[42:59] SPEAKER: stronger and background noise lower so you can hear dialogue better.
[43:04] SPEAKER: Yeah. It's great that this is finally, it took like five years of think pieces about why does everybody
[43:09] SPEAKER: use subtitles all the time now before people started paying actual algorithmic attention to
[43:14] SPEAKER: fixing the problem. It's nice to see that it's actually happening. Like Jellyfin, the Plex
[43:19] SPEAKER: competitor, the open source one, they just added a feature also that lets you kind of, there are
[43:25] SPEAKER: multiple ways to handle the stereo down mixing now. If you have like a 5.1, something that you're
[43:30] SPEAKER: watching crank up the center channel for voice. Hilariously, and maybe this is a story for another
[43:35] SPEAKER: time. The dropdown list of stereo algorithms to use are taken straight from a stack exchange post
[43:43] SPEAKER: that I was already aware of. Cause I fiddled with this in FFmpeg like a year ago, like
[43:47] SPEAKER: cause I was sick of watching movies and not being able to hear what people say.
[43:50] SPEAKER: Yeah. Do you have a 2.0 set up or do you have no?
[43:54] SPEAKER: Yes, I have a 2.0 set up. So the Jellyfin developers landed on the exact same stack
[43:57] SPEAKER: exchange post I did and are using the exact same FFmpeg parameters that I was using manually
[44:04] SPEAKER: because they're the dropdown algorithms that are literally named after the poster usernames.
[44:09] SPEAKER: That's really funny.
[44:10] SPEAKER: It's really stupid, but it's awesome. It's awesome that people are finally like really
[44:15] SPEAKER: all it is is you just, I'm guessing in 90% of cases, you just need the center channel
[44:19] SPEAKER: to be a little bit amplified over everything else.
[44:21] SPEAKER: So I was going to say my, I have a, I got rid of the rear speakers on my stuff years ago cause
[44:26] SPEAKER: they were a pain in the ass and my room doesn't really accommodate them. But I left the center
[44:30] SPEAKER: channel and my center channel is just always like three notches higher than the side channels.
[44:35] SPEAKER: And I have never experienced this problem.
[44:36] SPEAKER: That is, that is the way to go for sure. I see a lot of people seem to blame the working like
[44:41] SPEAKER: sound mixers and you know, like the Hollywood people that are doing the sound mixes. I'm
[44:45] SPEAKER: guessing it's less my, my feeling, my gut feeling is it's less their fault and more of the fault of
[44:50] SPEAKER: the devices doing the on the fly mixing. So if it works the same way it works in games,
[44:54] SPEAKER: which I'm sure it doesn't, but in games you generally make the highest quality mix for
[44:59] SPEAKER: like 7.1 or whatever. And then the others are just generated automatically. And my guess is
[45:04] SPEAKER: that the automatic generations are not great. Right. And whereas in the old days, I'm sure
[45:08] SPEAKER: that they did a DTS and it'll be digital and like, you know, 15 different stereo mixes.
[45:14] SPEAKER: And now the stereo is just like, good luck. Right. And then in a lot of cases you don't
[45:18] SPEAKER: even have a stereo mix in the media. It's just your receiver or soundbar or whatever,
[45:22] SPEAKER: or Plex doing the mixing. And they're not doing a good job of doing that elegantly. Anyway,
[45:28] SPEAKER: nice that this is getting fixed and God help you if you only are using the speakers that are built
[45:32] SPEAKER: into your TV in this, the year 2020 form. This is adding on a feature that they had years ago
[45:39] SPEAKER: that I really liked the ask Siri on your remote. What did they just say? And it rolls back like
[45:45] SPEAKER: 10 seconds and pops up subtitles on the screen. Yeah. That's something Roku has had for a long
[45:50] SPEAKER: time. If you rewind, it'll turn subtitles on up to the point you rewound from. I want to say this
[45:55] SPEAKER: was a first of the modern. This may have even been on the, the, the last of the not modern Apple TVs.
[46:02] SPEAKER: It was the, it was the first one that it was definitely on the first one with an a processor.
[46:08] SPEAKER: The subtitles now pop up when you pause or rewind or rewind or mute rather. They support 29, 21,
[46:16] SPEAKER: nine format projectors for Apple TV, which means you don't have weird black bars on the side of
[46:20] SPEAKER: your stuff if you're a top and bottom of your stuff for using a wide format. And they added
[46:25] SPEAKER: screensaver portraits to Apple TV. This actually, the screensaver portrait stuff that they did,
[46:30] SPEAKER: I guess this is, this will come up later, so nevermind, but Snoopy, you can have Snoopy on
[46:34] SPEAKER: your Apple TV and he'll come out and do stuff with Woodstock now, which finally great. WatchOS
[46:40] SPEAKER: is the next, was the next thing they hit. They talked about fitness and now they finally support
[46:44] SPEAKER: pauses for streaks if you're injured or like traveling or can't do your streaks. So you can
[46:50] SPEAKER: like get a Duolingo style pause on your, on your fitness streaks, which is good.
[46:56] SPEAKER: I guess that's cool for people who like, I, the gamification stuff is neat. I don't,
[47:01] SPEAKER: I don't like hang my hat on it necessarily, but. When I get a good, not working out streak going,
[47:07] SPEAKER: I don't want to break that, man. Sure. Fair. There's a new fitness screen that shows more
[47:14] SPEAKER: stuff and it's dynamically generated. Yeah. It's I hope that like, I'm trying, I think up to now
[47:21] SPEAKER: you have to go to your phone for anything more than basically that day as a workout. And even
[47:24] SPEAKER: that's not super well exposed. It's really like the last workout you did, you can see kind of
[47:28] SPEAKER: everything, but if like, if you want to see that week's activity, you can't do it on the watch.
[47:33] SPEAKER: And so I hope they are out there making it a little, a little easier to see more summary data
[47:37] SPEAKER: there. Well, you get right now you get the weekly. Oh yeah, you're right. So you get,
[47:44] SPEAKER: you just get the day. It is all limited to that day. Which I like, I use, I use the fitness
[47:49] SPEAKER: tracking constantly on the watch. So that's nice to hear. Yeah, that's good. And then the workout
[47:56] SPEAKER: intensity thing is nice too, where it looks at your age, your relative fitness level, and then
[48:02] SPEAKER: it kind of tells you, okay, you did three really intense workouts this week. You should maybe take
[48:06] SPEAKER: it easy on this fourth day. That would be handy for yes. And, and that's both dynamically generated
[48:13] SPEAKER: and customizable, like adjustable. If you feel like it's done a bad job, they added a new health
[48:19] SPEAKER: app that pulls all of the stuff. It seems like all of the stuff, the watch can measure together.
[48:24] SPEAKER: My guess is that this is leading up to having blood pressure on the next watch called the
[48:29] SPEAKER: vitals app. Oh, that would be wild. Blood pressure would be huge. They want to sell me a new watch.
[48:35] SPEAKER: That's a good way to do it. Yes, for sure. But also like this is just great anyway,
[48:38] SPEAKER: because having all that stuff scattered across different apps is such a pain.
[48:43] SPEAKER: Yeah. They have blood ox and breathing rate, heart rate, that kind of stuff all in this app.
[48:52] SPEAKER: It notifies you. It has different tiers of notifications, including a kind of severe one,
[48:57] SPEAKER: if multiple things are way out of range. So if your blood ox drops and your heart rate drops,
[49:02] SPEAKER: it's probably going to let you know that something bad is happening. My guess is you'll probably
[49:05] SPEAKER: already know, but I don't know. Never had that happen before. And then the smart stack,
[49:12] SPEAKER: which is that thing. It's the thing that I always forget exists.
[49:17] SPEAKER: I don't use it either. You get to it by rolling the crown
[49:23] SPEAKER: and it's more dynamic and developers can add activities to the smart stack now.
[49:27] SPEAKER: So it's not just Apple stuff. Yeah. I have not used that
[49:31] SPEAKER: single time since they introduced it. Yeah. Well, it's the normal path on Apple,
[49:37] SPEAKER: new Apple features where if they don't make it accessible to the apps that I actually use,
[49:40] SPEAKER: then it's only useful for people who only use Apple apps.
[49:44] SPEAKER: Yeah. I'm going to be keeping an eye on this year's watch announcement. Pretty heavy rumors.
[49:49] SPEAKER: They're doing like the first, like real major redesign of the form factor since the watch
[49:53] SPEAKER: started. That's interesting.
[49:56] SPEAKER: Probably, I mean, probably the biggest rumor there is they're supposedly going to a magnetic band
[50:00] SPEAKER: attachment rather than kind of the mechanical like slot design they have now.
[50:03] SPEAKER: I don't know if I like that. The mechanical slots really sturdy.
[50:06] SPEAKER: Yes. I mean, obviously, and it will break compatibility with every band you've ever bought.
[50:11] SPEAKER: There's a, I assume you've seen the rumors around the switch to also using magnetic
[50:16] SPEAKER: connection for the joy cons. Oh no, I haven't seen that.
[50:19] SPEAKER: There's some new type of battery or not battery magnet. I don't remember the name of it's
[50:23] SPEAKER: some kind of electrically activated magnet, but it's not an electromagnet. It's not a,
[50:27] SPEAKER: you need to keep supplying current to keep this active. You just switch it on and off.
[50:31] SPEAKER: Yes. It's like a toggle. Like once you hit it with current, it, it goes to magnetic and then
[50:35] SPEAKER: stays that way. That's cool.
[50:37] SPEAKER: And so I wonder if they're doing the same thing here because it must be a pretty
[50:41] SPEAKER: sturdy degree of magnetism. If that actually can, anyway, the, the idea there is they can
[50:46] SPEAKER: make it thinner because they have more space inside the housing without the inset for the
[50:50] SPEAKER: band stuff. I'm really curious what they do to redesign it this year.
[50:55] SPEAKER: I mean, we we've heard redesign rumors on that for the last couple of years. So it'll be,
[50:59] SPEAKER: it'll be interesting to see. I don't know. I think my, like, depending on what the
[51:03] SPEAKER: jump in price is, the ultra looks really compelling to me because extra battery life
[51:07] SPEAKER: seems better than like, I would happily have bigger, bigger battery with longer battery life
[51:13] SPEAKER: than, than the smaller, more svelte package. But anyway.
[51:18] SPEAKER: Yeah. You, you wear your watch 24 seven, right?
[51:20] SPEAKER: Pretty much.
[51:21] SPEAKER: I just check it on. I have a charger on the nightstand. I just check it on there every
[51:24] SPEAKER: night. So the battery life isn't a thing for me.
[51:26] SPEAKER: So I had, it's funny. I had a, this is a, this is a example of the thing getting smarter and
[51:31] SPEAKER: being more stupid simultaneously. I got a notification the other day that was like,
[51:35] SPEAKER: yo, your sleep patterns are really disrupted this week. You should look at it. And it's
[51:38] SPEAKER: cause I hadn't been going to bed with the watch on, but I'd been taking a nap in the
[51:42] SPEAKER: afternoon. So it was like, you've gone from getting seven to six and a half hours of sleep
[51:46] SPEAKER: to one hour of sleep a day. You should really think about adjusting your life, man.
[51:50] SPEAKER: How are you still functioning?
[51:51] SPEAKER: Yeah. I was fine. It turns out. So iPadOS was next. Same. It's getting all the same
[51:59] SPEAKER: stuff as the phone, basically. There's a bunch of new stuff. So home screen personalization
[52:04] SPEAKER: on the same year, which is kind of unusual because usually that like that kind of feature
[52:07] SPEAKER: lags a year on iPad. There are tab bars that are in the iPadOS apps that have like a tray
[52:16] SPEAKER: on the left or right side of the screen are now customizable. So you can drag stuff from
[52:21] SPEAKER: that tray into the tab bar to click quick change between things, which is nice. They
[52:29] SPEAKER: added a ton of new pencil stuff, like a ton, ton. The the big one was the math, the notes,
[52:41] SPEAKER: the math notes stuff.
[52:42] SPEAKER: Yeah. So I wasn't clear if that is falls under their Apple intelligence umbrella or,
[52:48] SPEAKER: I mean, I assume that's active there.
[52:50] SPEAKER: I think it's well, actually, hang on. We've buried the lead here. They're putting the
[52:55] SPEAKER: goddamn calculator on the iPad.
[52:57] SPEAKER: Oh, I wasn't going to acknowledge that that was something that we should celebrate at
[53:01] SPEAKER: this late date, but I believe the math notes are part of the calculator app.
[53:06] SPEAKER: So the math notes are integrated throughout the OS. They're in notes. They're in all sorts
[53:11] SPEAKER: of other places, but they demoed it in the calculator app. So when you turn the iPad
[53:15] SPEAKER: sideways and you have the pencil out, you can just write on the iPad like it's an 1800
[53:21] SPEAKER: slate chalk and slate math tool. And when you equals the equation, it just solves the
[53:31] SPEAKER: equation for you.
[53:32] SPEAKER: That's pretty cool. I have to say.
[53:34] SPEAKER: It seems pretty cool.
[53:35] SPEAKER: That's watching it in action. That is some future technology.
[53:39] SPEAKER: Yeah, I feel bad. PCalc and we've a bunch of friends who've made calculator apps over
[53:46] SPEAKER: the years and charged 99 cents for them are going to have some challenges this year.
[53:52] SPEAKER: They sure locked a lot of stuff this year.
[53:53] SPEAKER: Yes. There's another one we'll get to. Apple Sherlock's without mercy.
[53:57] SPEAKER: Yeah. Sherlocking for people who don't know is when they take a tool that has been a paid
[54:02] SPEAKER: established tool that billions of Mac users buy, and then they just integrate it into
[54:07] SPEAKER: the OS without killing that person's market immediately. Anyway, they added a lot of stuff
[54:14] SPEAKER: for notes, a lot of just general handwriting stuff. One of the things that I like is that
[54:17] SPEAKER: they tidy up your handwriting for you. Like they learn what your handwriting looks like
[54:20] SPEAKER: and can make an idealized version of that for you, which is a little creepy, but like
[54:25] SPEAKER: my handwriting looks like shit. So it's useful. Yeah. Less shitty handwriting seems good.
[54:32] SPEAKER: You could draw on screen shares.
[54:34] SPEAKER: Yes. That's more future talent. The hand-drawn calculations and the handwriting correction
[54:40] SPEAKER: both are just like, that's like some back to the future stuff. You know what I mean?
[54:44] SPEAKER: That's some stuff, that's some AT&T you will stuff.
[54:47] SPEAKER: Well, yeah. And the handwriting correction is seems less gross to me, less weird to me
[54:54] SPEAKER: because like the resolution of the panel and the pencil and all that is such that it's not,
[55:00] SPEAKER: if you don't have the exact right kind of handwriting, it's really hard to do handwriting
[55:03] SPEAKER: on the iPad. So making it more accessible seems good. You could draw on screen shares.
[55:11] SPEAKER: There was a bunch of other stuff. It's funny. I think this is all coming to all of the pencils
[55:15] SPEAKER: too. I don't think they didn't specify that this was only coming to the new pencil and the
[55:19] SPEAKER: new iPad Pro. I think this is for everyone, at least for the most part. And then they did the
[55:24] SPEAKER: parkour transition where Craig ran down some stairs. I air quoted Craig for audio listeners
[55:31] SPEAKER: and he like jumped over barricades and it was bad.
[55:34] SPEAKER: Well, executives like to have fun too. What is his role there?
[55:37] SPEAKER: He's in charge of software.
[55:40] SPEAKER: That's a pretty big job, I guess. I've like kind of lost track of the, like the Phil Schillers and
[55:45] SPEAKER: was Eddie Q one. Is he still there?
[55:47] SPEAKER: No, I think there's only like three executives that are still there when Steve was there.
[55:51] SPEAKER: Okay. Yeah. Kind of losing track of who's who.
[55:54] SPEAKER: I mean, at some point you make enough money that you're like, I'm probably good. And I don't want
[55:58] SPEAKER: to have to work so hard anymore unless you really, really love the work. So Mac OS, Sequoia, Craig
[56:05] SPEAKER: started this segment with a really extended bit about how the people who named shit like to get
[56:09] SPEAKER: high continuing in his long tradition of jokes about naming an OS version of Mac OS weed.
[56:17] SPEAKER: There's a town in California called weed.
[56:18] SPEAKER: I didn't, what was there? I need to, I need to get, this sounds awful. I need to go watch this.
[56:22] SPEAKER: It's pretty bad. They did a really nice like motion graphics thing where it was like
[56:27] SPEAKER: moving through trees. They're like, like you're, you're going to the Sierras and like,
[56:31] SPEAKER: it's like, it's really beautiful. And then there's a terrible VO over it. Anyway, it doesn't matter.
[56:35] SPEAKER: You know, I'm going to say I'm a little burnt over the nature names for code names,
[56:39] SPEAKER: or they're not even code names anymore. There's product names.
[56:41] SPEAKER: Well, I mean, look, eventually they'll run out of parks and then they're going to like,
[56:45] SPEAKER: it'll be like, welcome, welcome to Mac OS Salesforce tower.
[56:50] SPEAKER: Shoot me. You know what was bad-ass? What? Big cats.
[56:54] SPEAKER: Big cats.
[56:56] SPEAKER: Fucking Mac OS 10 Panther.
[56:58] SPEAKER: But you know what the problem with big cats is?
[57:00] SPEAKER: What's that?
[57:01] SPEAKER: There's only like 15 breeds of them.
[57:03] SPEAKER: Yeah. What if you, okay. What if you went to slightly smaller wild cats? Could we do
[57:06] SPEAKER: like Mac OS Manul?
[57:09] SPEAKER: I don't know. It sounds too much like manure, dude.
[57:11] SPEAKER: You should, you should go look up a Manul. It's a very,
[57:14] SPEAKER: M-A-N-O-O-L?
[57:16] SPEAKER: M-A-N-U-L. It's a very comical looking animal.
[57:19] SPEAKER: Oh, wow. It looks like a meme cat.
[57:22] SPEAKER: Right? It's like a, it's like a, it's like a, if a cat was a basketball.
[57:26] SPEAKER: Oh, they have these at the, at the, at the desert zoo in, in Palm desert, Palm Springs.
[57:34] SPEAKER: Really?
[57:35] SPEAKER: I think so. Is it a mountain cat? No.
[57:39] SPEAKER: Anyway, it doesn't matter.
[57:42] SPEAKER: What else? You know what else matters?
[57:44] SPEAKER: What's that?
[57:44] SPEAKER: All the other stuff from the iOS and the iPad OS is coming to Mac OS.
[57:48] SPEAKER: That's great.
[57:49] SPEAKER: Hikes and maps, math notes, but you can type because there's no touch screen on Mac still
[57:53] SPEAKER: inexplicably messages, stuff, all that is in there.
[57:58] SPEAKER: It's crazy that Microsoft beat Apple to the punch on making your tablet also your laptop.
[58:03] SPEAKER: Look, man, it's a, they're two distinct devices that run exactly the same hardware minus the
[58:08] SPEAKER: touch screen.
[58:09] SPEAKER: Oh, I'm sure they have enormous amounts of data about how many people buy both a Mac
[58:12] SPEAKER: book and an iPad.
[58:13] SPEAKER: I mean, yeah, one is a consumption device and one is a creation device, Brad, even though
[58:18] SPEAKER: they both have keyboards and track pads. It's fine.
[58:20] SPEAKER: I mean, to be fair, that's pretty much how I use them.
[58:23] SPEAKER: We didn't talk about this yet because this is, I think the first place they talked about
[58:26] SPEAKER: it, but there's a passwords app coming to all Mac Apple devices.
[58:31] SPEAKER: Yeah, they're basically, it sounds like it's, it is the same, generally the same functionality
[58:35] SPEAKER: that's been in like the iCloud kit toolkit, but they're kind of splitting it out into
[58:39] SPEAKER: its own app, right?
[58:41] SPEAKER: Yeah.
[58:41] SPEAKER: It seems like they're going a little further.
[58:43] SPEAKER: I can't think it's going to, they didn't say that it supports pass keys.
[58:46] SPEAKER: I assume it has to support pass keys at this point.
[58:49] SPEAKER: So, cause all the, because like if you have a device that doesn't support pass keys at
[58:53] SPEAKER: this point, you've kind of made a mistake.
[58:56] SPEAKER: It's available for windows as part of iCloud for windows app, which sounds ominous.
[59:02] SPEAKER: Yes.
[59:02] SPEAKER: Kind of, because otherwise I would actually think about trying this maybe as my main password
[59:07] SPEAKER: manager, but it really depends on how tightly it integrates with browsers on windows, which
[59:10] SPEAKER: I'm guessing it doesn't very well.
[59:12] SPEAKER: My guess is it runs great with edge on windows or something dope.
[59:16] SPEAKER: Like they'll pick the one browser that's the dopiest possible choice and then that'll
[59:19] SPEAKER: be the one.
[59:20] SPEAKER: Yeah, like I'm guessing, I'm guessing hoping for like a Chrome extension is way too much
[59:25] SPEAKER: to wish for here.
[59:26] SPEAKER: Well, I use Firefox, so I know I'm hosed.
[59:28] SPEAKER: Yes.
[59:31] SPEAKER: Like the good news for people who use existing password managers, whether it's BitLocker
[59:37] SPEAKER: one password or whatever, bit warden, sorry, or one password or whatever.
[59:43] SPEAKER: I don't think this is going to affect any like if you only live in the Mac or in the Apple
[59:50] SPEAKER: ecosystem, you're fine using this, right?
[59:53] SPEAKER: If you use any windows machines or God forbid something like a steam decker or a Linux machine
[59:58] SPEAKER: or anything else, Chromebook, I would think really hard about signing up for putting all
[1:00:05] SPEAKER: my passwords in a place that's a vendor specific implementation.
[1:00:08] SPEAKER: Yes, agreed.
[1:00:09] SPEAKER: Same thing applies to Microsoft or Google.
[1:00:11] SPEAKER: Frank, they did a bunch of stuff.
[1:00:15] SPEAKER: Continuity has been in for ages.
[1:00:17] SPEAKER: This is the thing that gave you a universal clipboard so you could copy something on your
[1:00:21] SPEAKER: phone and paste it in on your Mac or iPad.
[1:00:24] SPEAKER: They're adding new stuff to it.
[1:00:25] SPEAKER: The iPhone mirroring, which we talked a little bit about before, basically means that if
[1:00:29] SPEAKER: you've been able to get your phone notifications on your Mac for a while, what this means now
[1:00:36] SPEAKER: is that when you click a phone notification on your map, it opens a view of the phone.
[1:00:40] SPEAKER: Yeah, it's on your screen.
[1:00:42] SPEAKER: Yeah, we should be explicit about this is literally like one click screen mirroring
[1:00:46] SPEAKER: from your phone to your laptop and you can just interact with the phone with the touchpad
[1:00:50] SPEAKER: as if it's huge.
[1:00:52] SPEAKER: It seems like having a touch screen on the Mac would be really nice with this feature.
[1:00:55] SPEAKER: Well, I mean, the touchpad or trackpad is big enough and does multi-touch.
[1:01:00] SPEAKER: It's kind of the same.
[1:01:01] SPEAKER: Yeah, I know, but I'm just saying it's just right there.
[1:01:06] SPEAKER: One tiny step away.
[1:01:08] SPEAKER: Look, I don't want to filth up my laptop screen, all right.
[1:01:11] SPEAKER: I think this is awesome.
[1:01:12] SPEAKER: I think this is really cool.
[1:01:13] SPEAKER: It's huge.
[1:01:13] SPEAKER: This is the thing I was referring to earlier about like finally cleaning up my god awful
[1:01:17] SPEAKER: mess of a home screen.
[1:01:19] SPEAKER: Yeah, it's time.
[1:01:20] SPEAKER: To be fair, I have like two and a half pages of apps because at some point I got tired
[1:01:23] SPEAKER: of either deleting or organizing into folders when I downloaded stuff.
[1:01:27] SPEAKER: And I also don't use 90% of the apps on my phone anyway.
[1:01:31] SPEAKER: Anyway, like being able to just pull up the phone on the MacBook and use the trackpad
[1:01:34] SPEAKER: and more quickly just, you know, grind through all that organization.
[1:01:40] SPEAKER: Pretty nice.
[1:01:41] SPEAKER: Yeah, you can also drag and drop into phone apps.
[1:01:44] SPEAKER: They demoed.
[1:01:45] SPEAKER: That's crazy.
[1:01:45] SPEAKER: Dragging something from I think Final Cut into a generation, like a sharing app on the
[1:01:51] SPEAKER: phone.
[1:01:51] SPEAKER: Now, does that go both ways?
[1:01:52] SPEAKER: Because if I can open an app through this on the phone and drag it to my desktop, that's
[1:01:56] SPEAKER: like life changing.
[1:01:57] SPEAKER: I don't, my guess is you have to open the phone on the laptop and drag it from the phone
[1:02:02] SPEAKER: to the desktop, but yes.
[1:02:03] SPEAKER: Yeah, that's what I mean.
[1:02:04] SPEAKER: That's fine.
[1:02:04] SPEAKER: I would assume so.
[1:02:05] SPEAKER: Yeah, that's, that's huge.
[1:02:08] SPEAKER: The phone stays locked while you're mirroring it and it's on standby and like this standby
[1:02:13] SPEAKER: thing where you have it sideways on a, on a, like a magnetic stand even stays on if you
[1:02:18] SPEAKER: have, is that so we keep it on your desk?
[1:02:21] SPEAKER: And yeah, I think, like, I think this is a super cool feature.
[1:02:26] SPEAKER: I mean, it's awesome.
[1:02:27] SPEAKER: Makes me want a Mac.
[1:02:29] SPEAKER: Good job.
[1:02:29] SPEAKER: Yeah.
[1:02:30] SPEAKER: Did they, did they say anything about how this would affect like your phone being stolen
[1:02:33] SPEAKER: kind of situation?
[1:02:34] SPEAKER: What do you mean?
[1:02:35] SPEAKER: Like, does it work over cell?
[1:02:37] SPEAKER: Does it have to be on a local wifi?
[1:02:39] SPEAKER: My guess is it has to be local.
[1:02:40] SPEAKER: Okay.
[1:02:41] SPEAKER: So you would not be able to like, I mean, there's plenty, they have plenty of other
[1:02:45] SPEAKER: anti-theft features built in at this point.
[1:02:46] SPEAKER: It's not the end of the world, but yeah, I don't think you're able to remote into it.
[1:02:50] SPEAKER: I bet you can't look out of the camera while you're using the mirrored screen probably.
[1:02:54] SPEAKER: Yeah.
[1:02:56] SPEAKER: They've added tiling for windows, which I was reasonably sure that they had in like the
[1:03:01] SPEAKER: Jaguar days or something.
[1:03:02] SPEAKER: Nope.
[1:03:03] SPEAKER: Really?
[1:03:03] SPEAKER: As someone who like, you know, every time I go home, I work exclusively off of that
[1:03:08] SPEAKER: MacBook, that, that fifth 14 inch screen.
[1:03:11] SPEAKER: It sucks trying to, trying to record a podcast where you need like a video window, your audio
[1:03:18] SPEAKER: editing app of choice, like a, like a browser full of notes or like a feed of a game to
[1:03:23] SPEAKER: look at it.
[1:03:24] SPEAKER: It's impossible.
[1:03:25] SPEAKER: It is like, that's why I use the iPad as a second screen when I'm out there as a second
[1:03:29] SPEAKER: monitor because window management on, on a Mac is abysmal.
[1:03:33] SPEAKER: This is, this is like the Android thing where windows users are laughing because yeah, there's
[1:03:40] SPEAKER: been like next to no snapping.
[1:03:42] SPEAKER: I mean, there's a little, I don't need, we don't need to get into it, but I, but the
[1:03:45] SPEAKER: demo video looks like pretty much what I want.
[1:03:48] SPEAKER: I think their whole thing, I guess what I'm thinking about is their whole, what was it?
[1:03:53] SPEAKER: You hit command tab or something and it gave you like the quick view of all the windows
[1:03:58] SPEAKER: I open on your computer, which was nice on a laptop.
[1:04:00] SPEAKER: So you could switch back and forth between windows quickly.
[1:04:02] SPEAKER: Anyway, this seems really good.
[1:04:04] SPEAKER: Long over time.
[1:04:06] SPEAKER: You can do background replacement in FaceTime now.
[1:04:08] SPEAKER: I assume this is also coming to the other devices as well.
[1:04:12] SPEAKER: And they, they talked about games in the most Apple-y way possible, citing such 2024 bangers
[1:04:20] SPEAKER: as control and control was timeless.
[1:04:24] SPEAKER: Death Stranding director's cut also timeless.
[1:04:30] SPEAKER: Yeah.
[1:04:31] SPEAKER: The big thing that they announced was that their, their porting toolkit is they're revving
[1:04:35] SPEAKER: it to a new version.
[1:04:37] SPEAKER: And then also Assassin's Creed is coming to Mac OS and all iDevices.
[1:04:43] SPEAKER: The one that's coming out this year.
[1:04:44] SPEAKER: Shadows?
[1:04:45] SPEAKER: Shadows.
[1:04:47] SPEAKER: Yeah, that, that, that porting toolkit, they worked with the people who do wine on that.
[1:04:52] SPEAKER: Oh, okay.
[1:04:54] SPEAKER: Code weavers, yeah.
[1:04:55] SPEAKER: Yeah.
[1:04:57] SPEAKER: Yeah.
[1:04:58] SPEAKER: It sounds like they're making an actual push to get more games ported more easily.
[1:05:01] SPEAKER: That's cool.
[1:05:01] SPEAKER: I mean, maybe they're bringing down the proton stuff and all that.
[1:05:05] SPEAKER: I'm curious to see how that runs on a laptop.
[1:05:07] SPEAKER: Like on the phone, it's like an interesting academic exercise, but it's not something
[1:05:10] SPEAKER: I would ever play.
[1:05:12] SPEAKER: But like, I assume the GPU's in, in the M chips on the laptops are actually like relatively
[1:05:17] SPEAKER: beefy.
[1:05:18] SPEAKER: I mean, they're like souped up versions of the iPad one, right?
[1:05:21] SPEAKER: Well, yeah, maybe it won't be that great, actually, I don't know, but I'm still curious.
[1:05:25] SPEAKER: The upscalers are good.
[1:05:26] SPEAKER: And anyway, the also has game mode on the Mac, which has been there for a long time,
[1:05:30] SPEAKER: but they're adding the Bluetooth latency stuff to this as well.
[1:05:34] SPEAKER: I may have already been there.
[1:05:35] SPEAKER: So sometimes they announce things that they've already had.
[1:05:38] SPEAKER: And then the other big thing on Mac OS is that you can get Apple pay on third party
[1:05:42] SPEAKER: browsers, which is a, is a wonderful for people who don't use Safari, despite it being the
[1:05:46] SPEAKER: world's fastest browser or whatever stuff they say every time.
[1:05:49] SPEAKER: Yes, which no longer exists on windows.
[1:05:51] SPEAKER: Yeah.
[1:05:52] SPEAKER: So thus we reached the end of the, Hey, here are the things coming to products.
[1:05:57] SPEAKER: And now we're going to talk about the thing that the shareholders are going to be excited
[1:06:00] SPEAKER: about.
[1:06:01] SPEAKER: Apple AI, the only, the acronym for the one, the one true acronym for Apple intelligence.
[1:06:08] SPEAKER: Okay.
[1:06:09] SPEAKER: So they pitched, we've heard a lot about AI.
[1:06:13] SPEAKER: It's a lot of, Hey, you can have the computer right for you.
[1:06:17] SPEAKER: This is not their approach was different than that, which I thought was, I was kind of surprised
[1:06:21] SPEAKER: by they build it as personal intelligence, which is intelligence that understands you.
[1:06:25] SPEAKER: And I realized that they're one of like two companies that can probably do this, meaning
[1:06:31] SPEAKER: that they have access, trusted access to your contacts and calendar and photos and all of
[1:06:37] SPEAKER: the things that you need for this to work.
[1:06:40] SPEAKER: Google does for Android users.
[1:06:42] SPEAKER: Microsoft doesn't really, cause like I don't use my, like my photos don't live on my computer
[1:06:47] SPEAKER: anymore.
[1:06:47] SPEAKER: My contacts barely live on my computer.
[1:06:52] SPEAKER: And the, the things that they were pitching were things like asking it to get a, to make
[1:06:57] SPEAKER: a collection of all the pictures of your kid playing baseball over the last five years
[1:07:02] SPEAKER: and stuff like that, which is like, actually it's, it's why I signed up for Google photos
[1:07:08] SPEAKER: 10 years ago is because it was able to do context aware search inside the photos.
[1:07:13] SPEAKER: And when I searched for a picture of a dog, it popped up all the pictures of the dog in
[1:07:17] SPEAKER: my library.
[1:07:18] SPEAKER: So like this stuff is, it's kind of interesting.
[1:07:22] SPEAKER: Their pitch is that, you know, Apple's the privacy company is, is their longstanding
[1:07:28] SPEAKER: pitch.
[1:07:29] SPEAKER: They're saying that they're doing mostly they're doing on device processing, same way that
[1:07:32] SPEAKER: Copilot Plus does with the NPUs on everything from an A17 Pro and an M1 and newer.
[1:07:39] SPEAKER: Yeah.
[1:07:40] SPEAKER: So, I mean, I feel like, I feel like if any giant trillion dollar corporation has earned
[1:07:44] SPEAKER: that trust, they've come the closest, you know, like secure, like they were probably
[1:07:49] SPEAKER: first with like the secure enclave and the SOC, right?
[1:07:51] SPEAKER: Like there was the whole like refusing to unlock stuff for the FBI thing.
[1:07:55] SPEAKER: Like they seem to like walk the walk.
[1:07:58] SPEAKER: I think I trust them more than I trust any of the other trillion dollar companies.
[1:08:01] SPEAKER: Yes.
[1:08:01] SPEAKER: Yeah, low bar to be clear.
[1:08:03] SPEAKER: Low bar.
[1:08:04] SPEAKER: Yeah.
[1:08:05] SPEAKER: The private cloud compute.
[1:08:06] SPEAKER: So this is where it gets hinky is that they also have this thing that they call private
[1:08:10] SPEAKER: cloud compute, which uses server models with what they called private servers.
[1:08:15] SPEAKER: I haven't seen any security people do the take down, like the breakdown of how this
[1:08:19] SPEAKER: actually works yet.
[1:08:20] SPEAKER: So we'll probably talk about this in the future, maybe in a Q and A episode.
[1:08:23] SPEAKER: No, what does that use for?
[1:08:25] SPEAKER: Is that just like stuff that's too heavy for your phone itself to handle?
[1:08:28] SPEAKER: They have to shunt it to the cloud compute?
[1:08:30] SPEAKER: Yeah, so there's two different layers of, "Hey, we're going to shunt this to the cloud."
[1:08:33] SPEAKER: There's the one that uses this, and then there's the one that goes to chat GPT when
[1:08:37] SPEAKER: you talk to Siri, like we'll talk about later on.
[1:08:40] SPEAKER: They're saying that they encrypt stuff between the device and the server, but I don't
[1:08:44] SPEAKER: understand how sending it to a private -- it's not like they're giving me a private cloud
[1:08:50] SPEAKER: instance, right?
[1:08:51] SPEAKER: They're not giving each user a private cloud instance.
[1:08:53] SPEAKER: So somewhere there's an opportunity to log queries that go through and stuff like that.
[1:08:58] SPEAKER: So I don't understand how it's not leaky in a way that most modern AI stuff is.
[1:09:04] SPEAKER: But I mean, they are running these machines, they're running it on Apple hardware.
[1:09:07] SPEAKER: So they're like, as they say, they're in the tool chain top to bottom.
[1:09:11] SPEAKER: So I guess that's good.
[1:09:14] SPEAKER: I don't know.
[1:09:17] SPEAKER: That's not a concern.
[1:09:18] SPEAKER: I'm not worried about Intel or Nvidia hacking the AI pipeline and stealing my data.
[1:09:23] SPEAKER: I am worried about Apple using my data to make their AI stuff better.
[1:09:28] SPEAKER: That's understandable.
[1:09:29] SPEAKER: You, you, you, you touched on a question I was just sitting here wondering about, which
[1:09:32] SPEAKER: is like, I wonder what Apple's backend stack looks like, you know, like, because like for
[1:09:36] SPEAKER: training or just for everything, like their server infrastructure and their data centers
[1:09:40] SPEAKER: for the, like this stuff, the training, all of it, you know, like, I, I guess what I mean
[1:09:44] SPEAKER: is like, you know, how much, how much like Linux and BSD are they using on the backend
[1:09:48] SPEAKER: versus, cause you know, like Mac OS is a, it's a certified Unix.
[1:09:51] SPEAKER: It's a literal Unix, but it's not exactly like purpose built for massive data center
[1:09:56] SPEAKER: use. So when they say, so when they say it's like, it's Apple all the way up and down the
[1:10:01] SPEAKER: stack, they didn't say that I saw that, but they said it was running on Apple hardware.
[1:10:05] SPEAKER: Oh, okay.
[1:10:05] SPEAKER: I see the private servers.
[1:10:07] SPEAKER: So like, I w I wonder what they're using to train.
[1:10:09] SPEAKER: I wonder if they're buying big Nvidia clusters or AMD clusters or something to train.
[1:10:13] SPEAKER: Right.
[1:10:13] SPEAKER: I wonder if they're like, I wonder cause there's two aspects.
[1:10:18] SPEAKER: There's what does the model run on?
[1:10:20] SPEAKER: Which is what they're talking about here.
[1:10:22] SPEAKER: There's also, what did they train the model on and where do they get the data for that?
[1:10:25] SPEAKER: So I, yeah, I don't, I don't know.
[1:10:27] SPEAKER: I want to see the breakdown of this.
[1:10:28] SPEAKER: We'll talk about it in the future.
[1:10:29] SPEAKER: Cause I'm curious about it.
[1:10:32] SPEAKER: They're redesigning Siri almost completely.
[1:10:34] SPEAKER: Like this is, this is the big, the big thing this year.
[1:10:37] SPEAKER: It seems like this might be the biggest thing in this entire presentation.
[1:10:41] SPEAKER: Cause it sounds like they're finally turning Siri into what I try to use it as and get
[1:10:44] SPEAKER: frustrated constantly by it not working that way.
[1:10:48] SPEAKER: Yeah.
[1:10:48] SPEAKER: And just to be clear, they've pitched this a couple of times in the past, like the original
[1:10:51] SPEAKER: pitch for Siri was it's going to know everything about you.
[1:10:53] SPEAKER: So it can, it can combine the two different things in a way that you want.
[1:10:58] SPEAKER: And, and it never really worked.
[1:11:00] SPEAKER: And it's like, you had to learn how to work with it.
[1:11:03] SPEAKER: It's constraints.
[1:11:04] SPEAKER: And this seems like it's adding ability to parse more complicated things.
[1:11:09] SPEAKER: Yes.
[1:11:09] SPEAKER: That's, that's amazing.
[1:11:10] SPEAKER: I'm constantly just asking it.
[1:11:11] SPEAKER: Well, not constantly, but I, you know, occasionally I try to get Siri to harness more context
[1:11:16] SPEAKER: than it's capable of actually understanding for, for just basic tasks, you know, for like,
[1:11:21] SPEAKER: for like tweaking reminders or something like that.
[1:11:23] SPEAKER: You know, or like I use a lot of alarms for things like, you know, like when to take medications
[1:11:26] SPEAKER: and when to get that, when to get that weekly, too good to go produce order.
[1:11:30] SPEAKER: We always get, you know what I mean?
[1:11:31] SPEAKER: And like, and I always wanted, I want to be able to say to Siri, like, Hey, Hey, go delete
[1:11:36] SPEAKER: every alarm that contains this word or whatever, you know what I mean?
[1:11:40] SPEAKER: Like, like just something selective and contextual like that.
[1:11:43] SPEAKER: And it never knows how to do stuff like that.
[1:11:45] SPEAKER: Yeah.
[1:11:45] SPEAKER: So, so it seems like they're doing a lot more of that.
[1:11:49] SPEAKER: They did, they, the demo that they gave had somebody stumbling over their words as they
[1:11:52] SPEAKER: were asking it to do something and it, and it recovered and did the right thing.
[1:11:56] SPEAKER: Like I think she said, I need the weather tomorrow for Muir beach.
[1:12:00] SPEAKER: And then she changed it to Muir woods or something like that.
[1:12:04] SPEAKER: The it's contextual, the, the contextual, the context of the conversation carries over
[1:12:11] SPEAKER: past between queries.
[1:12:13] SPEAKER: Yeah, that's huge.
[1:12:14] SPEAKER: So you can talk about somebody and then it'll say, okay, add them to the, to the invite
[1:12:18] SPEAKER: for this and it'll add that it'll know which person is them.
[1:12:21] SPEAKER: That's another one of those natural language things that you just expect to be there.
[1:12:24] SPEAKER: Like they, it was like, this thing has just been in the uncanny valley for a long time
[1:12:28] SPEAKER: of you expect it to do more than it can because it feels like it should.
[1:12:31] SPEAKER: Well, it's funny because the way I've always worked with it is I know it works this way.
[1:12:35] SPEAKER: So I just do the thing the way that I know it works rather than the way I would expect.
[1:12:39] SPEAKER: I would have this conversation with a human.
[1:12:40] SPEAKER: Right.
[1:12:40] SPEAKER: Like that's how I usually tend to do things as well, but like it just, I feel like maybe
[1:12:44] SPEAKER: it's the promise of it has never really been fulfilled and that's frustrating.
[1:12:47] SPEAKER: Well, and it's often for me, often when the failures happen, they stack.
[1:12:53] SPEAKER: So like if you ask it to start playing music and it plays the wrong music and then you
[1:12:58] SPEAKER: have to correct it and correct it and correct it, it just gets worse and worse and worse
[1:13:01] SPEAKER: because it gets more and more confused.
[1:13:04] SPEAKER: They redesigned it.
[1:13:05] SPEAKER: The ball's gone.
[1:13:06] SPEAKER: So it pulses in from the edge of the screen now using the curved bits on the edge of the
[1:13:10] SPEAKER: glass.
[1:13:10] SPEAKER: I thought that pulse looked kind of cool.
[1:13:12] SPEAKER: I wonder if they're doing that, excuse me, on the handful of hard edge 16 by like, or
[1:13:18] SPEAKER: not 16 by nine, but you know, like I still have a phone that is just a rectangle screen.
[1:13:23] SPEAKER: I don't think you're going to get the, you're not going to get it because you don't have
[1:13:27] SPEAKER: the right processor.
[1:13:28] SPEAKER: Oh, right.
[1:13:29] SPEAKER: Yes.
[1:13:30] SPEAKER: Well, I wonder if that's just a full article across the product line brand makeover though
[1:13:35] SPEAKER: for that.
[1:13:36] SPEAKER: I'm not going to get the AI features, but are they still going to refresh the look of
[1:13:39] SPEAKER: Siri across the whole product line?
[1:13:40] SPEAKER: I don't know.
[1:13:41] SPEAKER: We'll see.
[1:13:41] SPEAKER: It's an interesting question.
[1:13:42] SPEAKER: They're a bajillion because I don't know if we mentioned you need, you need a, a, a, a...
[1:13:47] SPEAKER: So last year's high-end processor and M1.
[1:13:50] SPEAKER: Yes.
[1:13:50] SPEAKER: You need an iPhone 15 Pro or newer to use any of this stuff.
[1:13:53] SPEAKER: So there's a ton of iPhones that aren't going to be able to do any of this.
[1:13:55] SPEAKER: It's 14 Pro.
[1:13:57] SPEAKER: Is it?
[1:13:57] SPEAKER: Because isn't it A18 this year?
[1:13:59] SPEAKER: Oh, maybe I'm, I might be right.
[1:14:01] SPEAKER: I thought they said it was the A15 Pro.
[1:14:03] SPEAKER: Anyway.
[1:14:04] SPEAKER: Anyway.
[1:14:04] SPEAKER: Yeah, it doesn't matter.
[1:14:07] SPEAKER: The double tap on the bottom of the screen to type to Siri is nice.
[1:14:12] SPEAKER: I think that's really good.
[1:14:13] SPEAKER: And then that's, yeah, that's cool.
[1:14:16] SPEAKER: Yeah.
[1:14:16] SPEAKER: Cause it's like, there's times when you're laying in bed or something, you want to change
[1:14:18] SPEAKER: something and it gives you an easy way to do two things at once.
[1:14:21] SPEAKER: Sure.
[1:14:22] SPEAKER: And then it's aware it's using the machine vision stuff to know what's on the screen
[1:14:26] SPEAKER: when you talk to it.
[1:14:26] SPEAKER: So if you have a recipe open, it knows it, it can look at it and be like, Oh, this is
[1:14:30] SPEAKER: a recipe.
[1:14:31] SPEAKER: What should I do now?
[1:14:33] SPEAKER: Like I'm, I, I saw that and I was like, Oh, when I'm cooking, I'm going to use this.
[1:14:38] SPEAKER: Cause I often have three timers going and they're for different things.
[1:14:42] SPEAKER: And I can just say, Hey, start a timer for the, for the potatoes, blah, blah, blah.
[1:14:47] SPEAKER: Whatever the recipe says.
[1:14:48] SPEAKER: I wonder if it has deep hooks into content yet, where you can say like, Hey, take, take
[1:14:52] SPEAKER: just the recipe on this webpage and turn it into a PDF and put it in files or something
[1:14:56] SPEAKER: like that.
[1:14:57] SPEAKER: They talked about that kind of stuff.
[1:15:00] SPEAKER: They're, they're building a bunch of default intents for different app types.
[1:15:04] SPEAKER: They said they're going to continue to do those.
[1:15:06] SPEAKER: So it's like pre-trained stuff, like adding filters to photos and working in spread, manipulating
[1:15:11] SPEAKER: spreadsheets and stuff like that.
[1:15:14] SPEAKER: Like the weird thing about all of this is that all of this sounds pretty good.
[1:15:20] SPEAKER: It doesn't really solve any of my other concerns about the AI stuff, but it seems like these
[1:15:25] SPEAKER: use cases are like the cases that they're set up are designed to minimize the places
[1:15:31] SPEAKER: where the machine can lie to you as the, as the opportunity to generate a lie to make
[1:15:37] SPEAKER: you happy.
[1:15:38] SPEAKER: And, and that like that minus the energy stuff, which I still am freaked out about solves
[1:15:44] SPEAKER: a lot of the problems that I have with some of the generative, the broader generative
[1:15:47] SPEAKER: stuff.
[1:15:49] SPEAKER: The writing tools is another example of them.
[1:15:51] SPEAKER: Instead of generating something from scratch, like helping you make this stuff that you
[1:15:55] SPEAKER: write better.
[1:15:56] SPEAKER: I'm skeptical that any of this is going to be worth a shit.
[1:15:59] SPEAKER: I mean, yeah, I frees framed on some of the examples they showed and it's not something
[1:16:03] SPEAKER: I would use necessarily, but I can see how some people would like it.
[1:16:07] SPEAKER: We're also arguably probably better writers than most of the general population because
[1:16:11] SPEAKER: we spent like 10 years getting yelled at for bad writing.
[1:16:13] SPEAKER: Like I've, you know, we've, we've written countless articles and like triple countless
[1:16:19] SPEAKER: numbers of emails in our careers.
[1:16:21] SPEAKER: But, but more than that, going through the editorial process where your stuff is edited
[1:16:24] SPEAKER: and you get questioned on stuff is a really good way to get better at writing fast.
[1:16:28] SPEAKER: Right.
[1:16:28] SPEAKER: That's what I meant.
[1:16:29] SPEAKER: I could see why it would be useful to a lot of people.
[1:16:31] SPEAKER: Yeah.
[1:16:33] SPEAKER: Sorry, let me, let me jump in.
[1:16:34] SPEAKER: But like crucially, they did not say or show any kind of feature that will just generate
[1:16:39] SPEAKER: text for you, right?
[1:16:40] SPEAKER: Did not at all.
[1:16:42] SPEAKER: They showed automatic rewriting where you like highlight a paragraph and you're like,
[1:16:45] SPEAKER: Hey, here's five different versions of this that you can choose from, which is kind of
[1:16:48] SPEAKER: like, that's, that's like that, that seems moderately useful.
[1:16:52] SPEAKER: Yeah.
[1:16:52] SPEAKER: That actually sounds kind of, I mean, that, that is maybe something I would look at just
[1:16:55] SPEAKER: as a, as a way to get some kind of feedback or variation, but crucially you always, it
[1:17:01] SPEAKER: seems like you always have to provide the material first.
[1:17:05] SPEAKER: So, so I think my take on this whole thing is that instead of having people generate
[1:17:10] SPEAKER: queries to generate text, they're doing an interesting job of, of creating a building
[1:17:15] SPEAKER: tools that create queries for you prompts for them, for the AI models for you.
[1:17:19] SPEAKER: So what they're doing is using, I'm sure they're just generating a prompt that when
[1:17:23] SPEAKER: you highlight the text, it says, Hey, make a version of this that's less aggressive or
[1:17:27] SPEAKER: more aggressive or more professional or more casual or whatever.
[1:17:31] SPEAKER: And they're giving you, they're giving you the, the kind of finding that you need to
[1:17:35] SPEAKER: generate those prompts without you having to know how to generate a prompt, which is,
[1:17:38] SPEAKER: which is smart.
[1:17:39] SPEAKER: I hate it, but it's smart.
[1:17:41] SPEAKER: And then I actually wrote, I hate this in the notes at this point.
[1:17:45] SPEAKER: And then I said, technically, I don't hate this.
[1:17:47] SPEAKER: I liked that it's about changing work and not starting from zero, but like, it's still
[1:17:51] SPEAKER: just generating a prompt for you.
[1:17:53] SPEAKER: Um, uh, parsing emails for events and stuff like that is, seems wonderful.
[1:17:58] SPEAKER: That's part of this too.
[1:18:00] SPEAKER: So like it, it sees that there's your friends that you talk to are asking you to come to
[1:18:04] SPEAKER: a barbecue and then it's going to automatically generate a barbecue calendar thing for you,
[1:18:08] SPEAKER: which sounds wonderful.
[1:18:10] SPEAKER: And it might be enough to get me to stop using Gmail and fantastic Cal.
[1:18:14] SPEAKER: Okay.
[1:18:14] SPEAKER: So about this time is when I thought, uh, this stuff is starting to sound too good to
[1:18:18] SPEAKER: be true.
[1:18:19] SPEAKER: Okay. Uh, they got to reduce notifications focus, which is just like, I kind of want
[1:18:25] SPEAKER: that on all the time.
[1:18:26] SPEAKER: Yeah.
[1:18:27] SPEAKER: I'm very torn on this one because a, I got excited when I saw it because it's very necessary.
[1:18:32] SPEAKER: B it just kind of feels like, Hey, we're just going to cover up the problem rather than
[1:18:36] SPEAKER: actually fix the root of the problem, which is that there are way too many notifications.
[1:18:39] SPEAKER: Well, so the solve for the problem is to have a tool that helps you turn off notifications
[1:18:44] SPEAKER: in mass.
[1:18:45] SPEAKER: Yeah.
[1:18:45] SPEAKER: Right. Cause that's what I really want is I want something that's like, yo, these are
[1:18:49] SPEAKER: the 10 applications you've never opened a notification for just turn this shit off.
[1:18:54] SPEAKER: Yes.
[1:18:54] SPEAKER: That would be very nice.
[1:18:55] SPEAKER: Um, there's also, I mean, there's kind of a granularity problem in some cases, maybe
[1:18:59] SPEAKER: this isn't super widespread, but you have things like Uber where you absolutely need
[1:19:03] SPEAKER: the notifications for your driver is here.
[1:19:05] SPEAKER: Yeah.
[1:19:06] SPEAKER: But they also send you all kinds of ad bullshit via notification all the time.
[1:19:10] SPEAKER: And that's a, that's a, you got to get into the preferences for the application, not a
[1:19:14] SPEAKER: system level problem, right?
[1:19:15] SPEAKER: Yeah. That is fair.
[1:19:16] SPEAKER: Yeah. But, but I mean, there's a way both on Android and iOS, I believe to prior to
[1:19:23] SPEAKER: say, Hey, this is a high priority notification within your notification chain.
[1:19:27] SPEAKER: That already existed.
[1:19:28] SPEAKER: Yeah. That's existed for a long time. So they should, um, cause like, like I can get, I
[1:19:34] SPEAKER: think I want to say, I can't remember the specific example, but I have something that
[1:19:39] SPEAKER: when I was in a do not disturb, it pushed a notification through and I was like, Oh,
[1:19:42] SPEAKER: that's interesting. But it was a notification I actually needed because it was something
[1:19:45] SPEAKER: high priority. Um, I think the, the general, like, so the general idea of this feature
[1:19:51] SPEAKER: is you can put a focus and it's unclear to me if this is a focus setting for focuses
[1:19:57] SPEAKER: you've created, or if this is a new type of focus, but it's a, we only let through
[1:20:02] SPEAKER: important notifications setting, which previously you could do for like favorite
[1:20:07] SPEAKER: people. So you could say, okay, I always want to get text messages. Brad's one of my
[1:20:11] SPEAKER: favorite people. I always want to get text messages. He sends me, sends me a text
[1:20:14] SPEAKER: message, but you couldn't say these are the apps or these are the messages within the
[1:20:20] SPEAKER: apps that are the important ones. Like your Uber example, or, Hey, door dash just left
[1:20:24] SPEAKER: food on your front step. Or, um, I don't know something else that you're, there's a
[1:20:29] SPEAKER: smoke alarm going off in your house. Um, and this seems like they're applying machine
[1:20:35] SPEAKER: learning to that. Now I'm a little skeptical, but this, this seems like the kind of
[1:20:40] SPEAKER: problem that machine learning should be good for. Yeah. You would hope so. It's
[1:20:43] SPEAKER: just that the penalty for failure is extreme. If the thing you miss is extremely
[1:20:48] SPEAKER: unmissable, I assume they err on the side of not missing rather than missing, but I
[1:20:52] SPEAKER: could make Billy who knows. Yeah. One would hope. Um, yeah. So that, that was
[1:20:57] SPEAKER: interesting. Then we get into the, like the, the horror show with the image
[1:21:00] SPEAKER: creation stuff. This is where it started to go off the rails for me. So it was a
[1:21:03] SPEAKER: real hard swing here. Uh, they, they have these Jen Moji things, which is like, you
[1:21:08] SPEAKER: know, the memo G's, you love them, you know, them, it's like a little, little
[1:21:12] SPEAKER: picture of you and you can animate it that you can make it your avatar. If
[1:21:16] SPEAKER: you're in a FaceTime call, it's a, it's a, yeah, it's a little already a little bit
[1:21:20] SPEAKER: of a nightmare factory, but it makes it, it's like the cool guy version of me.
[1:21:24] SPEAKER: They're a cultural institution at this point. Yeah. But it, it followed the
[1:21:27] SPEAKER: traditional path of, Hey, uh, all my friends are going to start using it. It's
[1:21:32] SPEAKER: like, it's like, uh, the snap, uh, what are those snap stickers? The, the, the, um,
[1:21:36] SPEAKER: Snapchat owns them. They're like hip, hip, hip, something. Hold on. Hip. Nope.
[1:21:44] SPEAKER: Not hip camp. Uh, snap. I don't remember what it's called. Shoot. Snapchat.
[1:21:50] SPEAKER: I keep wanting to say Hipstamatic, which was very different thing.
[1:21:53] SPEAKER: It was not that. Let me see. I have the app still installed. I'm sure more,
[1:21:57] SPEAKER: let's click more emoji. Live demo folks. I disabled the app because it annoyed me,
[1:22:03] SPEAKER: I guess, at some point in the past, anyway, uh, it used to be a thing that
[1:22:09] SPEAKER: Snapchat owned and you could make little avatar versions of you and then send
[1:22:14] SPEAKER: pictures of yourself to your friends. And, uh, it started out as a thing that
[1:22:19] SPEAKER: all of my friends were using ironically to indicate how stupid it was. And then
[1:22:23] SPEAKER: pretty soon we were actively communicating using the stupid thing that we
[1:22:26] SPEAKER: all hated. That's, that's the problem with irony. Yeah. Uh, it can become
[1:22:30] SPEAKER: sincerity when you're not looking it, uh, it is bitmoji is what it was. Oh,
[1:22:37] SPEAKER: bit. Yes. Okay. Yes. So then that's what the, then they introduced an emoji,
[1:22:42] SPEAKER: which was kind of Apple's take on this without like the star Wars branding and
[1:22:45] SPEAKER: all the stuff that they tied in because I want to say the, the bitmoji probably
[1:22:49] SPEAKER: made a fair amount of money for Snapchat given by how many like integrations they
[1:22:53] SPEAKER: got with guardians of the galaxy and all that stuff. Uh, this, the next step of
[1:22:58] SPEAKER: that is genmoji, which is AI created generative memojis, which like you could
[1:23:05] SPEAKER: have a sloth memoji and you could have, uh, whatever. I like, I don't, they,
[1:23:10] SPEAKER: look, I don't understand how this is generative. It just seems like they had
[1:23:15] SPEAKER: people making a bunch of these, but I guess it's generative. I don't know.
[1:23:20] SPEAKER: Yeah. I mean, a lot of, I think the examples are very contextual or
[1:23:23] SPEAKER: situational, right? It's like, I don't just want a cat dress as a chef. I need
[1:23:27] SPEAKER: the cat dressed as a chef to be making a lasagna. Yeah. And it also needs to be
[1:23:32] SPEAKER: worried about my days. Yes, indeed. Yeah. Um, it's like, I feel less bad
[1:23:37] SPEAKER: about this cause this feels less infringy. Yeah. Yeah. So I mean, A, A, I
[1:23:42] SPEAKER: definitely kind of get the need because there's certainly been times that I wish
[1:23:45] SPEAKER: there was an extremely specific bespoke emoji I could drop as a very specific
[1:23:49] SPEAKER: joke that didn't exist. And if to be able to make that, is there something to
[1:23:54] SPEAKER: that idea? But yeah, also like, what did they train this on? Like emojis?
[1:23:58] SPEAKER: They're training this on emojis and art they created presumably, and then
[1:24:01] SPEAKER: general purpose pictures of things. Right. Like, like pictures, pictures of
[1:24:05] SPEAKER: food, pictures of animals. And then, and then the art style comes from the
[1:24:08] SPEAKER: existing giant pool of emoji that they control. Yeah. But like at the same
[1:24:12] SPEAKER: time, if I can type in, I want a genmoji version of me, you know, uh,
[1:24:19] SPEAKER: drinking a tea in the, like the Kermit meme, but in the style of Lisa Frank.
[1:24:24] SPEAKER: And if it does that, then I feel bad about it again. So hopefully, hopefully
[1:24:28] SPEAKER: they're not stealing people's art, I guess. Oh, I thought this was constrained
[1:24:31] SPEAKER: to looking like the existing emoji style. They do look like the existing emoji
[1:24:36] SPEAKER: style, but often the constraints, the rails on this stuff are pretty easy to
[1:24:40] SPEAKER: bypass. So as always the, the it's all in the implementation, I think.
[1:24:46] SPEAKER: Yeah. Actually, now that I'm looking at something like, like the initial, the
[1:24:49] SPEAKER: initial ones they show examples of, or like, you know, like the very classic
[1:24:53] SPEAKER: emoji, smiley face, just round yellow smiley face, except with cucumber slices
[1:24:57] SPEAKER: for eyes, like that, like that, that could be an existing emoji, right? Like
[1:25:01] SPEAKER: that could have come right out of the pool on your phone already. But then,
[1:25:05] SPEAKER: yeah, as you, as you get a little deeper into the video, you see some stuff
[1:25:09] SPEAKER: with backgrounds on it. And there's like, here's my cat chef example,
[1:25:14] SPEAKER: actually. And yes, that one is a little bit more of a bespoke art style with
[1:25:17] SPEAKER: like a full on background and everything. Of course, you know, the other angle
[1:25:21] SPEAKER: with that though, is like, what is this replacing? I feel like, like, like what
[1:25:24] SPEAKER: are the pertinent questions about generative AI you need to ask? Where do
[1:25:28] SPEAKER: they get the data they trained on? What role is this playing and what is it
[1:25:32] SPEAKER: replacing? Right. And I guess in fairness, it's not like there's a thriving
[1:25:37] SPEAKER: like app store of emoji artists. This is undercutting. You know what I mean?
[1:25:43] SPEAKER: I will tell you there is a large market in artists building pixel art imagery
[1:25:48] SPEAKER: for Twitch streams and YouTube streams and stuff like that.
[1:25:51] SPEAKER: Sure. But I mean, specifically in the context of where this can be used,
[1:25:53] SPEAKER: which is iMessage, right? Like they don't, they don't let you bring outside
[1:25:56] SPEAKER: images in that way, right? Aren't you limited to what they provide already?
[1:26:00] SPEAKER: So stickers fit in that category of things you can add in, but you can't do
[1:26:05] SPEAKER: stickers as, so the thing is you can add these as like the hit, the hit reactions
[1:26:10] SPEAKER: on all your iMessages now. Stickers were kind of that. I still think the
[1:26:14] SPEAKER: stickers are gated somehow. I'm not, I don't, I don't really use the stickers,
[1:26:18] SPEAKER: so it's hard for me to, all of my stickers are emoji and like animal. It's
[1:26:27] SPEAKER: like the animals that you can make be your avatar doing different emoji
[1:26:34] SPEAKER: reactions. So it's like, here's a skull with its head exploding off with a
[1:26:38] SPEAKER: mushroom cloud on it or crying or with stars or whatever. I assume that's,
[1:26:42] SPEAKER: that one's not in China, probably. Here's the poop emoji looking very
[1:26:47] SPEAKER: surprised and very upset and grumpy and with naughty language bleeps over its
[1:26:51] SPEAKER: mouth. Yeah. So it's weird. I don't know.
[1:26:54] SPEAKER: Yeah. It is, it is a bit weird, but you know, like if for something where
[1:26:58] SPEAKER: you're just looking for a one-time throwaway joke that you're never going
[1:27:01] SPEAKER: to use again, not like you're going to pause your text conversation and go
[1:27:04] SPEAKER: commission an artist to make that for you. So.
[1:27:07] SPEAKER: There's an argument about devaluing the value of art, but like I said, since
[1:27:12] SPEAKER: it's, since it's, it feels less to me, it feels less bad to me somehow
[1:27:16] SPEAKER: because it feels like a souped up character creator. Sure. Like it feels
[1:27:20] SPEAKER: like you could build a non AI version of this tool and it would, it would
[1:27:23] SPEAKER: work effectively the same way. For all we know, this may not even be an AI
[1:27:26] SPEAKER: version of this tool. This could just be a non AI version of this tool that
[1:27:30] SPEAKER: they're dumping an infinite amount of art into. Yeah. There's also image
[1:27:35] SPEAKER: playground, which is there. This honestly, this is another one of those
[1:27:39] SPEAKER: things that feels like a graphic, like a prompt generator. So it is a, you
[1:27:45] SPEAKER: can describe the image of the thing you want. Grandma wearing, looking very
[1:27:50] SPEAKER: happy and doing something. Birthday was one of the ones that they gave.
[1:27:54] SPEAKER: There's an API, so you can integrate it in your apps and they showed
[1:27:57] SPEAKER: generating images of different things that people were putting into a bunch
[1:28:02] SPEAKER: of different places. And it seemed very easy and kind of like, it's the
[1:28:07] SPEAKER: least interesting thing I can think of using this technology for. Yeah.
[1:28:12] SPEAKER: Some of the images I see coming out of this thing are less appealing. They
[1:28:15] SPEAKER: sound a lot of them are real bad than the emoji context. Yeah. So so yeah,
[1:28:22] SPEAKER: like, like I think the, I think the gen Moji thing is kind of potentially
[1:28:26] SPEAKER: interesting in the same way that like your, your, your your stickers and
[1:28:31] SPEAKER: your, your, your emoji and your, and your, what was the other one? Bitmoji
[1:28:36] SPEAKER: same way they were. Yeah. Yeah. I mean, I, again, I think, I think just
[1:28:39] SPEAKER: within the very narrow and crucially private context of goofing with or
[1:28:44] SPEAKER: trolling your friends. Yeah. It's it's a little bit less bad of an issue.
[1:28:50] SPEAKER: And part of that is because they did not go harder with generative stuff
[1:28:54] SPEAKER: across the rest of this announcement. Yeah. Like this is kind of the, what
[1:28:58] SPEAKER: we've just described as far as I can tell, it's kind of the extreme of what
[1:29:01] SPEAKER: they're offering here, right? I think it's the closest to what I would
[1:29:04] SPEAKER: describe as a traditional AI application. Yes. The other thing that they
[1:29:09] SPEAKER: added is this image, one thing that transforms rough sketches. So a lot of
[1:29:13] SPEAKER: this stuff is ending up in note in the notes app specifically. There's a lot
[1:29:16] SPEAKER: of like the text, text wiggle, like the text correction and the handwriting
[1:29:21] SPEAKER: correction and the math, the math notes stuff is all ending up in the notes
[1:29:25] SPEAKER: app. There's a lot of like, Hey, you can record a lecture and it'll
[1:29:31] SPEAKER: generate an AI generated summary of that lecture after the lecture is over,
[1:29:36] SPEAKER: or it will generate just notes for you if you want, which like, you're not
[1:29:40] SPEAKER: going to lie. That one sounds okay. Like automatically, like nobody there's
[1:29:45] SPEAKER: value in taking meeting notes, having been the person who takes meeting
[1:29:49] SPEAKER: notes in most of the meetings I've been in for the last 20 years. But it's
[1:29:53] SPEAKER: also really interesting to have a machine do that. So you can focus on
[1:29:57] SPEAKER: like being a more active participant in the meeting a lot of times. Right.
[1:30:01] SPEAKER: That, that kind of makes me realize this could probably be used to generate
[1:30:05] SPEAKER: podcast chapters at some point. Let's not get crazy. I'm not saying I would
[1:30:10] SPEAKER: do that. I would probably never trust it, but. Yeah. Like, that's a good
[1:30:17] SPEAKER: point though. Cause a lot of the stuff I would use this stuff for is stuff
[1:30:21] SPEAKER: that I would love to do if I had more time, but because I don't have time
[1:30:25] SPEAKER: to go back and check it. And I know that these are machines that we've
[1:30:28] SPEAKER: taught to lie. I'm less inclined to treat the output of this as
[1:30:33] SPEAKER: trustworthy. There's a great, from the chat GPT section, there's a great
[1:30:39] SPEAKER: little disclaimer at the bottom of the chat GPT interface in Siri, where it
[1:30:44] SPEAKER: says check information for mistakes at the bottom of every chat GPT
[1:30:49] SPEAKER: interaction. So, yeah, that's a ring endorsement, I guess. So the image
[1:30:56] SPEAKER: wand, you move it over, you'd like do a rough sketch in your note, note,
[1:31:01] SPEAKER: notes document, and then you kind of just highlight it with this. It's just
[1:31:05] SPEAKER: like a, it's like a normal drawing tool, but it turns the rough sketch
[1:31:08] SPEAKER: into an image. I'm wildly curious to try this. Yeah. So I mean, it'd be
[1:31:13] SPEAKER: fun to see what it comes up with. I don't know. There's also something,
[1:31:16] SPEAKER: there's a certain artistry even to like crappy dashed off rough sketches.
[1:31:23] SPEAKER: Sometimes, sometimes the expressiveness and even something that's
[1:31:26] SPEAKER: simple is preferable to something that looks nice and professional.
[1:31:29] SPEAKER: Like there was a, there was a person on Reddit for years that would just
[1:31:31] SPEAKER: do shitty paint drawings of things that people asked for. It was great.
[1:31:36] SPEAKER: I love that photo editing lets you, like, this is the thing that's
[1:31:41] SPEAKER: existed in Photoshop and a lot of other things it's in the photos app.
[1:31:43] SPEAKER: Now it lets you take stuff out of the background really easily.
[1:31:48] SPEAKER: What is that? What they call those like kind of content aware features
[1:31:52] SPEAKER: basically? Well, Adobe calls it content aware race and stuff like that.
[1:31:56] SPEAKER: It's basically cloning the right part of the background or inferring
[1:32:00] SPEAKER: what's in the background. I'm sure it's going to create some real nightmares,
[1:32:04] SPEAKER: but also like there's a, there's a real appeal of being able to do that easily.
[1:32:10] SPEAKER: Google, Google has a feature where if you take like 10 pictures of a big
[1:32:13] SPEAKER: group of people, it'll take the good heads from each of the people in the,
[1:32:17] SPEAKER: in the, in the, you know, how like the one picture where nine people are good
[1:32:22] SPEAKER: and one person blinks and they'll take a good head from one of the other
[1:32:25] SPEAKER: pictures and put it on that person for the, for the other one.
[1:32:30] SPEAKER: I think that's maybe more useful ultimately, but I also spent a lot of
[1:32:34] SPEAKER: time taking pictures of large groups of children, which is a fucking nightmare.
[1:32:37] SPEAKER: Yes. I can imagine.
[1:32:39] SPEAKER: You'll note, you'll note the sample photo they used here has a very like
[1:32:43] SPEAKER: easily repeatable background. It's a bunch of like gravel or rocks and
[1:32:47] SPEAKER: water. Well, and it's a beach, which the machines understand.
[1:32:50] SPEAKER: That's what I mean. It's like the, the, the sample image they've used here is
[1:32:53] SPEAKER: probably very easy for the machine to replicate this repeatable background
[1:32:58] SPEAKER: over top of the people that they want to remove.
[1:32:59] SPEAKER: And also the context of the things they were moving. Like one person is a
[1:33:03] SPEAKER: person holding a selfie stick, I think. And the other one is a, is like
[1:33:07] SPEAKER: a guy with the tall hat at the Queen's house.
[1:33:11] SPEAKER: What are they called?
[1:33:12] SPEAKER: Bee feeders?
[1:33:13] SPEAKER: No, no, they have the, they have the flat hats, not the tall ones.
[1:33:16] SPEAKER: Oh, I don't know.
[1:33:18] SPEAKER: Royal guard or something. Anyway, we're not English.
[1:33:21] SPEAKER: We don't have to know this natural language search for phone camera and
[1:33:26] SPEAKER: pictures and videos, which is like, I kind of was surprised that this wasn't
[1:33:30] SPEAKER: in there already. I thought you could search for dog on, on the iPhone and it
[1:33:33] SPEAKER: would give you a dog, give you the pictures of a dog.
[1:33:38] SPEAKER: Am I missing something here? I definitely searched with texts.
[1:33:42] SPEAKER: Searching inside videos is new.
[1:33:44] SPEAKER: Yes. That, and sure that definitely maybe, maybe it's just more robust text
[1:33:48] SPEAKER: search.
[1:33:48] SPEAKER: It may be smarter. It may be that it doesn't know people. I don't.
[1:33:53] SPEAKER: Yeah. Like the, the example they're using here says Maria cartwheeling on
[1:33:56] SPEAKER: the grass. So I guess it's able to identify specific people.
[1:34:02] SPEAKER: And some, when I search for dog running, I get nothing. When I search for
[1:34:05] SPEAKER: dog, I get pictures of dogs.
[1:34:09] SPEAKER: So anyway that's good. I guess I, I assume that computer is going to run
[1:34:13] SPEAKER: on the phone while it's plugged in and charging at night.
[1:34:17] SPEAKER: Cause this feels like something you shouldn't have to run on the cloud.
[1:34:20] SPEAKER: Yeah.
[1:34:21] SPEAKER: The movie I wrote movie is generated based on context and time. And I, oh,
[1:34:26] SPEAKER: this is generating like the, the kind of, Hey, do you remember you can,
[1:34:31] SPEAKER: you can prompt it to generate specific movies based on verbal or written
[1:34:36] SPEAKER: prompts. And it uses context of the images and the time they were taken and
[1:34:42] SPEAKER: the location they were taken all basically like, this is one of those
[1:34:44] SPEAKER: things that Apple could do because they have access to photos and contacts
[1:34:47] SPEAKER: and your location data and all this stuff. So they make like a clip, real
[1:34:51] SPEAKER: video of your different assembling, a bunch of different shots from
[1:34:56] SPEAKER: different time periods where you're doing, like, I think the classic
[1:35:00] SPEAKER: example is, Hey, here's every time I took my kid fishing between the time
[1:35:03] SPEAKER: they were born. And when they were like the most recent time we went
[1:35:06] SPEAKER: fishing and it makes a kind of like fishing through the ages thing or
[1:35:10] SPEAKER: something. These, this is one of the things that you're looking at me. Like
[1:35:14] SPEAKER: I'm a crazy person. I, I literally have a widget for the Google photos
[1:35:19] SPEAKER: version of this on my home screen, because it always pops up something
[1:35:21] SPEAKER: that makes me either really happy or super bummed. If it shows me like a
[1:35:26] SPEAKER: picture of the dog just before she died. Yes. I certainly get that. I've
[1:35:30] SPEAKER: been, I've been there. Yeah. Live recording calls along with the notes,
[1:35:35] SPEAKER: auto record and summarize. So if you're on the phone with somebody, you
[1:35:39] SPEAKER: can hit a button and it'll start recording and say, this call is being
[1:35:42] SPEAKER: recorded by the iPhone or something like that. Oh, it does insert
[1:35:45] SPEAKER: something. Cause I was going to say, you should probably be conscious of
[1:35:48] SPEAKER: local surveillance laws. Yeah. Whether you're a two party or one party state
[1:35:53] SPEAKER: and all that, but they specifically said it probably notifies all everybody
[1:35:56] SPEAKER: on the call. And then you get a text summary at the end, which is awesome.
[1:36:01] SPEAKER: That sounds really good. Yeah. This stuff is all free with iOS 18. They're
[1:36:07] SPEAKER: not charging for it, which I thought was interesting. Well, barely standard
[1:36:11] SPEAKER: for Apple. I mean, they are still a hardware company at their heart at
[1:36:14] SPEAKER: heart at their core, but I mean, they do, they do charge for the, there's a
[1:36:18] SPEAKER: lot of services they charge for now. Yeah. You're right. A month. You're
[1:36:21] SPEAKER: right. I mean, what is, what is their, what is their big umbrella service?
[1:36:25] SPEAKER: Apple one, is that what it's called? Yeah. Are you in that? Apple one plus,
[1:36:28] SPEAKER: which has fitness too. Oh God. What? Yeah. So the Apple one, I think I paid
[1:36:33] SPEAKER: 20 bucks a month for Apple one. Okay. Cause of the, cause of phone storage.
[1:36:37] SPEAKER: I think, so I'm going to tell you, if this stuff works as well as they
[1:36:40] SPEAKER: demoed it, I'm going to switch. I'm going to stop paying for Google
[1:36:43] SPEAKER: photos and move my photos back into Apple. I think that makes sense. I
[1:36:46] SPEAKER: mean, as far as charging for this stuff, like this is, I don't feel like this
[1:36:50] SPEAKER: all rolls up into one service that you could necessarily get away with
[1:36:53] SPEAKER: charging money for like, like some of these features are pretty cool in
[1:36:58] SPEAKER: and of themselves, but it's not like, this is not like some cohesive hole.
[1:37:01] SPEAKER: I feel like I think, I think I think that some of this stuff, like the way
[1:37:07] SPEAKER: I would charge for this, if I were building a service around, it would
[1:37:09] SPEAKER: be to put an umbrella that you get access to like the better level of the
[1:37:16] SPEAKER: cloud. You get the cloud AI stuff. If you're a subscriber to the one to
[1:37:19] SPEAKER: some tier of one or storage or something like that. Yeah. Speaking of
[1:37:24] SPEAKER: money, I might be out of scope for this episode. I think I saw the
[1:37:27] SPEAKER: Apple's deal with chat GPT or with open AI is like extremely disadvantageous
[1:37:31] SPEAKER: to open AI. Well, so we haven't talked about the chat GPT thing yet. Oh,
[1:37:35] SPEAKER: that's okay. Yeah. We'll get to that. So basically if you ask Siri
[1:37:39] SPEAKER: something and it gets a query, it doesn't understand that it thinks chat
[1:37:43] SPEAKER: GPT can understand, like you ask it to plan a menu for you was the example
[1:37:48] SPEAKER: they gave, which seems like a fucking terrible idea given. Anyway, just
[1:37:52] SPEAKER: don't, don't, don't ask chat GPT to plan your vacations unless you like
[1:37:56] SPEAKER: having bad vacations. Sure. It asks, Siri asks permission to share the
[1:38:01] SPEAKER: question and then dumps it out to chat GPT. And then that chat GPT lies to
[1:38:07] SPEAKER: you. So open AI didn't get paid for this, which is according to Ed Zitron.
[1:38:13] SPEAKER: He said that they negotiated a, Hey, we're just going to do this for you
[1:38:17] SPEAKER: deal for exposure, which is incredible because it's an enormous cost for
[1:38:22] SPEAKER: them. It's only to the free tier of chat GPT stuff. So you get presumably
[1:38:27] SPEAKER: whatever the most current three tier chat GPT model is. And it does have
[1:38:34] SPEAKER: the check information for mistakes, disclaimer at the bottom, which is
[1:38:38] SPEAKER: incredible to me. If you're paying, you don't have to have an account to
[1:38:42] SPEAKER: use it. So it just, it just goes through. I assume they're giving you
[1:38:46] SPEAKER: like a, they're making a, a hash account for your phone. That is just
[1:38:50] SPEAKER: always you. And then you do get paid features if you're logged into chat
[1:38:56] SPEAKER: GPT on the phone and they want to do other AI models in the future as
[1:38:59] SPEAKER: well. So like, I wonder if you can do like a, like a llama three or
[1:39:03] SPEAKER: stable diffusion or something like that. That's running on a local
[1:39:05] SPEAKER: machine. I'm curious about that. And that's it. The last thing they
[1:39:14] SPEAKER: closed with was, Hey, they want to make all this stuff accessible to
[1:39:17] SPEAKER: developers starting in the fall when this ships to users. So they're
[1:39:21] SPEAKER: building out intents that have a pre-structured queries and stuff like
[1:39:26] SPEAKER: that. So it's relatively easy to add it for the, or I assume as much
[1:39:30] SPEAKER: stuff as they can get done between now and then. But betas are out now
[1:39:35] SPEAKER: for developers. Public betas will be later this month and everything
[1:39:39] SPEAKER: ships in the fall. Same as always along with new phones, new phones,
[1:39:45] SPEAKER: and probably, probably new. I think we're due for new watches around
[1:39:49] SPEAKER: then too. I can't remember if they do watches in the fall now.
[1:39:52] SPEAKER: They definitely do. They might announce them at the same event as the
[1:39:55] SPEAKER: phone or maybe like a month later or something. I'm not sure.
[1:39:59] SPEAKER: Anyway. It was like, what did, what, what, what did you think after all
[1:40:02] SPEAKER: this? Like, where'd you end up? I mean, I'm not like jumping out of my
[1:40:06] SPEAKER: chair for any of this stuff. Well, you, you mean the whole thing or just
[1:40:09] SPEAKER: the AI stuff? Yeah. What's I would ask what's like, I came out of this
[1:40:13] SPEAKER: pretty like feeling like I didn't, I expected to be pretty down on
[1:40:18] SPEAKER: whatever AI stuff they came out with. And I'm, I would say I'm neutral
[1:40:24] SPEAKER: on all of this. That's like, there's nothing in the AI stuff. Is there
[1:40:27] SPEAKER: anything I'm like jumping out of my chair to use? It seems like the least
[1:40:30] SPEAKER: bad implementation of this technology of anybody who's using it at the
[1:40:34] SPEAKER: moment. That seems right. Or the least damaging. Yeah. Yeah. I mean,
[1:40:39] SPEAKER: how useful it is remains to be seen. Like some, some of the, like, like we
[1:40:43] SPEAKER: talked about before, like the, the, like the handwriting cleanup, the,
[1:40:46] SPEAKER: the live math equation solving stuff like that is just pretty, pretty
[1:40:51] SPEAKER: clearly beneficial. It's cool. Nothing else. Yes. Like for me, the, the,
[1:40:57] SPEAKER: it feels like I think a lot of this stuff would have landed harder if they
[1:41:01] SPEAKER: hadn't essentially made these same promises multiple times in the past,
[1:41:05] SPEAKER: especially like the stuff around Siri having context awareness between
[1:41:08] SPEAKER: conversations and stuff like that. This is all stuff that they've said they
[1:41:11] SPEAKER: have working in the past and then just never shipped or if they did ship it,
[1:41:15] SPEAKER: it didn't work very well. Yeah. I think the Siri one, like if it's
[1:41:19] SPEAKER: making Siri more robust and able to more naturally just do things that you
[1:41:24] SPEAKER: ask it to instantly a lot of massaging and guardrails and running into
[1:41:29] SPEAKER: ceilings that, yeah, that, that, that could be huge. I've been looking at
[1:41:34] SPEAKER: for people who understand what they're talking about to talk about how the
[1:41:38] SPEAKER: private cloud compute stuff works. There was a, there was an article on past
[1:41:43] SPEAKER: company that was kind of interesting, but not what I was looking for. So
[1:41:47] SPEAKER: we'll talk more about that as we get more detail. I think that there was a
[1:41:50] SPEAKER: session the day that we recorded this that talks about it how it all, how it
[1:41:55] SPEAKER: all like what the backend infrastructure is like. So there'll probably be
[1:41:58] SPEAKER: more about that soon. And if there's stuff we'll link it in the discord and
[1:42:01] SPEAKER: probably tweet about it or whatever your modern post Twitter equivalent is.
[1:42:06] SPEAKER: Yeah. I broadly, I would say like among the AI stuff, like Siri is the only
[1:42:10] SPEAKER: thing there that looks actually functional to me. Everything else is at
[1:42:13] SPEAKER: best kind of novel. The stuff I'm the most excited about is, is fully outside
[1:42:16] SPEAKER: of the AI. It's like better control center, RCS supports, fricking windows
[1:42:22] SPEAKER: snapping to corners and MacOS. You know, it's like the stuff I'm excited about
[1:42:26] SPEAKER: is just a bunch of basic usability features that they have lacked and
[1:42:30] SPEAKER: should have had already. I'm pretty excited about the idea to add
[1:42:36] SPEAKER: smarter filtering to the notifications. I think if that works, that that's
[1:42:41] SPEAKER: really exciting. I think the I think the, the the note, the, the enhance,
[1:42:48] SPEAKER: like honestly, I think the secret Sherlock of this is all the 50 million
[1:42:51] SPEAKER: notes, note-taking apps that everybody uses. Because I think that the, I
[1:42:56] SPEAKER: didn't even talk about it, but the, the free form thing, they're basically
[1:43:00] SPEAKER: doing a deck creation tool in there. So you basically can make your, you can
[1:43:05] SPEAKER: make scenes for freeform where you do your drawing and then you can say,
[1:43:10] SPEAKER: okay, start on this one and then move the framing. So it scootches across
[1:43:14] SPEAKER: the big, huge freeform canvas onto the next one and onto the next one, onto
[1:43:17] SPEAKER: the next one for like presentations and stuff like that, that are hand
[1:43:21] SPEAKER: drawn and really cool. I think, I think that like, I think, but I think the
[1:43:26] SPEAKER: note, if they make notes good, and it's a place where you could put
[1:43:30] SPEAKER: handwriting and drawing and audio and all of this stuff and automatically
[1:43:35] SPEAKER: generate summaries and things like that. I think that's really neat.
[1:43:38] SPEAKER: Yeah. Like it's, it's kind of crazy to think of notes as a potential killer
[1:43:42] SPEAKER: app, but then it should have always been the killer app though. You're,
[1:43:46] SPEAKER: you're, you're maybe not wrong, but that, that immediately raises the
[1:43:48] SPEAKER: question for me though, is, is there still as much value there if you don't
[1:43:51] SPEAKER: have the pencil? Well, so for me, I think about like when I was in college,
[1:43:57] SPEAKER: there was, when you'd have a big lecture, there'd often be like, everybody
[1:44:02] SPEAKER: would walk up and put like a tape recorder on the, on the pedestal in
[1:44:06] SPEAKER: front of the speaker and they'd record the lecture. Right. And I imagine
[1:44:10] SPEAKER: walking up and setting my phone on that and setting it to record and then
[1:44:14] SPEAKER: taking notes into the same document that that's recording into on my iPad
[1:44:18] SPEAKER: or my laptop in the, in the, in the carrels, in the seats. And like, that
[1:44:25] SPEAKER: seems kind of compelling. So I don't know. I don't know that I'm going to
[1:44:31] SPEAKER: put my phone up on the counter. That seems like a disaster when it starts
[1:44:34] SPEAKER: ringing or something. But you know, the look, the machine will know that
[1:44:37] SPEAKER: I'm in class, so I shouldn't have the notifications going and it's probably
[1:44:42] SPEAKER: fine. The fitness stuff, the vitals thing seems to be good. Yes. That's a
[1:44:46] SPEAKER: big one of, of the things I'm excited about. Like if they do a blood
[1:44:49] SPEAKER: pressure watch, I would be very stoked about that. Those rumors have been
[1:44:54] SPEAKER: going for a long time though, and it hasn't shipped yet. And then the
[1:44:58] SPEAKER: home screen customization on the phone and iPad, I know don't laugh Android
[1:45:01] SPEAKER: people, but the ability to do the shading and stuff is compelling. So
[1:45:06] SPEAKER: that's what I'm excited about. And AirPlay receiver on the Apple vision
[1:45:10] SPEAKER: pro. Oh, he doesn't want that. Of course. I don't, I don't have a Mac,
[1:45:14] SPEAKER: so I don't care about the iPhone screen on your Mac. Anyway, I think
[1:45:17] SPEAKER: that's as good a place to wrap it up as any. Brad, as always, thanks for,
[1:45:21] SPEAKER: for talking about this stuff with me. It's fun. Thank you. And if you would
[1:45:25] SPEAKER: like to talk to people about this, a great place to do that is on the tech
[1:45:27] SPEAKER: pod discord, where you can be surrounded by like-minded individuals who like
[1:45:33] SPEAKER: the same nerdy, weird, interesting stuff that you and Brad and I are all
[1:45:38] SPEAKER: into. You can join by going to patreon.com/techpod. The show is
[1:45:42] SPEAKER: listener supported. That means we don't take money from advertisers. We're
[1:45:45] SPEAKER: not, we're not the money we make is the money we take directly from you,
[1:45:49] SPEAKER: the listener. So if you would like to support the show, you can go again to
[1:45:52] SPEAKER: patreon.com/techpod. And for five bucks a month, you get access to the
[1:45:56] SPEAKER: discord, you get the patron exclusive episode, and you help Brad and I, you
[1:46:01] SPEAKER: know, live our lives, which we really appreciate. Goodbye. Yeah. So, as
[1:46:06] SPEAKER: always, we like to thank, end every episode by thanking our patrons, but we
[1:46:10] SPEAKER: want to give an extra special thank you to our executive producer, to your
[1:46:14] SPEAKER: patrons, including Andrew Slosky, Paddle Creek Games, Makers of Fractured
[1:46:19] SPEAKER: Veil, Jordan Lippett, Bunny Fiend, Joel Krauska, Twinkle Twinkie, David
[1:46:24] SPEAKER: Allen, James Kamik, and Pantheon, makers of the HS3 high-speed 3D printer. Oh,
[1:46:30] SPEAKER: and Paddle Creek Games, Makers of Fractured Veil. That's right. I missed
[1:46:33] SPEAKER: one there. So thank you all for your support. We appreciate you. And we will
[1:46:37] SPEAKER: see everyone next week. Bye, everybody.
