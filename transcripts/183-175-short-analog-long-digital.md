---
episode: 183
title: 175: Short Analog, Long Digital
date: 2023-03-12
guests: none
duration: 1:16:34
---

[00:00] SPEAKER: - I've gotten to do something new at work lately.
[00:03] SPEAKER: - That's always fun.
[00:04] SPEAKER: - Yeah, they let me put Unreal on my computer,
[00:09] SPEAKER: Unreal out on my computer,
[00:10] SPEAKER: and I'm working on a game mode for the Anacrusis.
[00:16] SPEAKER: - What do you mean they let you?
[00:18] SPEAKER: I thought anybody can just download,
[00:20] SPEAKER: that's your computer, right?
[00:21] SPEAKER: Anybody can just download that thing and install it.
[00:23] SPEAKER: - Well, yeah, but like I, okay, so when I was at FU,
[00:26] SPEAKER: we had a problem where I made a submission,
[00:29] SPEAKER: 'cause I used to get in Unity
[00:30] SPEAKER: and do a little hacking and stuff there.
[00:32] SPEAKER: Just know enough to be dangerous.
[00:34] SPEAKER: And let's say I caused a Git problem
[00:38] SPEAKER: that made us lose a couple of days or maybe more work,
[00:41] SPEAKER: which felt real bad.
[00:43] SPEAKER: - Oh. - Yeah.
[00:45] SPEAKER: - Could you illuminate what the problem was that you caused?
[00:48] SPEAKER: - I submitted some shit
[00:49] SPEAKER: that corrupted a whole big mess of stuff.
[00:51] SPEAKER: And then when I reverted,
[00:54] SPEAKER: I reverted the whole thing instead of just my parts.
[00:57] SPEAKER: And look, mistakes were made.
[00:59] SPEAKER: Let's just say that. - Okay, okay.
[01:01] SPEAKER: - I think the problem was it caused,
[01:03] SPEAKER: I took over some checkouts that other people had,
[01:06] SPEAKER: and then they weren't able to submit their work.
[01:09] SPEAKER: But anyway, it doesn't, there was a sequence of events
[01:11] SPEAKER: that ended up with somebody losing a couple of days of work
[01:13] SPEAKER: and I felt really bad.
[01:14] SPEAKER: And I was like, I'm gonna stay out of source control
[01:15] SPEAKER: at this point, because my people should not be here.
[01:18] SPEAKER: I'm a generalist.
[01:19] SPEAKER: - There's a reason that multiple websites exist
[01:21] SPEAKER: to make Git easier to deal with.
[01:24] SPEAKER: - Yeah, so anyway, I was like,
[01:27] SPEAKER: hey, I have an idea for a thing.
[01:28] SPEAKER: And people were like, that sounds like a cool idea
[01:31] SPEAKER: for a new kind of holdout map in the anacrusis.
[01:37] SPEAKER: 'Cause right now, our holdout maps
[01:38] SPEAKER: are very much like left for dead holdout maps,
[01:40] SPEAKER: where you have a central area that you kind of defend,
[01:43] SPEAKER: and then maybe you have to go capture some points
[01:45] SPEAKER: or something on the edges of that area
[01:47] SPEAKER: to force you to move around a little bit.
[01:48] SPEAKER: But you don't really, you don't traverse a map per se.
[01:51] SPEAKER: You're basically staying in one combat arena.
[01:54] SPEAKER: And I was like, what if, what if instead of doing that,
[01:57] SPEAKER: you had to traverse a map
[01:58] SPEAKER: while you're capturing these points,
[01:59] SPEAKER: and then at the end, something exciting happens?
[02:02] SPEAKER: They were like, that's a good idea.
[02:03] SPEAKER: You should build that.
[02:04] SPEAKER: And I was like, oh, well, I shouldn't do that.
[02:05] SPEAKER: That's a bad idea.
[02:06] SPEAKER: And then they were like, no, just go download.
[02:08] SPEAKER: Here's the Wiki page that tells you
[02:11] SPEAKER: how to download the repo and set up Unreal,
[02:16] SPEAKER: our version of Unreal Ed, and let it rip.
[02:19] SPEAKER: Have fun.
[02:20] SPEAKER: - Give a game designer a fish, he'll design for a day.
[02:23] SPEAKER: Teach a game designer to fish, he'll design for a lifetime.
[02:26] SPEAKER: - Well, and also at the same time,
[02:28] SPEAKER: we're doing more, we have a lot of people building mods
[02:34] SPEAKER: right now and our documentation needs help.
[02:35] SPEAKER: And like, I don't understand enough about how Unreal works
[02:38] SPEAKER: to help with the documentation.
[02:40] SPEAKER: So this is, it's like two birds with one stone.
[02:41] SPEAKER: I have to do something fun.
[02:42] SPEAKER: And then now I can help with the documentation as well.
[02:45] SPEAKER: - Are you writing any code or script in this process?
[02:48] SPEAKER: Or is it all like visual?
[02:49] SPEAKER: Like, I don't know exactly.
[02:51] SPEAKER: I mean, I know the Unreal Engine tools are quite robust,
[02:53] SPEAKER: but I don't know if it's all like visual scripting for stuff
[02:56] SPEAKER: like this at this point,
[02:57] SPEAKER: or like how are you interfacing with all this?
[02:59] SPEAKER: - The answer is it's complicated.
[03:02] SPEAKER: The version of the, so we're on Unreal 4.27.
[03:09] SPEAKER: We haven't moved Anacrusis to 5.1 or whatever.
[03:11] SPEAKER: I don't, that may or may not happen
[03:13] SPEAKER: at some point in the future.
[03:15] SPEAKER: The, there's like multiple tiers of code.
[03:18] SPEAKER: And some of this stuff is specific to our game
[03:20] SPEAKER: and some of it's engine specific.
[03:22] SPEAKER: Like in the engine, there's the idea that you can write code
[03:25] SPEAKER: in like chunks of code, like functions,
[03:27] SPEAKER: just like in C++, right?
[03:29] SPEAKER: But then there's also these things called blueprints,
[03:31] SPEAKER: which can kind of serve as API interfaces
[03:34] SPEAKER: between a more visual scripting language
[03:37] SPEAKER: and, or between chunks of code.
[03:39] SPEAKER: So you can like pass variables
[03:40] SPEAKER: from one piece of code to another.
[03:41] SPEAKER: And like, you can make things do things,
[03:44] SPEAKER: but somebody has to have written the underlying code
[03:47] SPEAKER: for those things to happen.
[03:48] SPEAKER: So, so that visual thing is called blueprints.
[03:51] SPEAKER: And basically like the rules of our game
[03:54] SPEAKER: all run in a big blueprint that is, that says, okay,
[03:58] SPEAKER: the game starts with four players
[04:00] SPEAKER: on these types of spawn points.
[04:02] SPEAKER: And then they have to, you know,
[04:04] SPEAKER: they have to go from here to there
[04:07] SPEAKER: and the game ends on that spawn point.
[04:09] SPEAKER: And along the way, this, these series of functions
[04:12] SPEAKER: will be running in the background.
[04:14] SPEAKER: And the blueprints can be a mixture of things
[04:15] SPEAKER: that are other blueprints or C++ code,
[04:19] SPEAKER: or maybe some other stuff that I don't know about,
[04:22] SPEAKER: 'cause I haven't gotten too far.
[04:23] SPEAKER: I mostly work in blueprints right now, just because,
[04:26] SPEAKER: and honestly, I mostly work in not,
[04:28] SPEAKER: I mostly work one layer up in the,
[04:30] SPEAKER: above the blueprints in like a map logic layer,
[04:33] SPEAKER: which is a thing that one of our designers kind of built,
[04:40] SPEAKER: like in the style of Quake, modern Quake engine
[04:43] SPEAKER: or idtech engine map scripting stuff.
[04:46] SPEAKER: So like the stuff that I'm working on
[04:47] SPEAKER: is actually map entities that have triggers attached to them.
[04:52] SPEAKER: And those triggers are pulled from blueprints
[04:55] SPEAKER: and the blueprints then run C++ code if they need it,
[04:59] SPEAKER: 'cause there's API end points
[05:01] SPEAKER: that let the blueprints connect to the C++ code.
[05:04] SPEAKER: But also this is a really mature project.
[05:06] SPEAKER: This is the thing that we've been working on
[05:07] SPEAKER: for three years now.
[05:08] SPEAKER: And like two dozen people have touched it,
[05:12] SPEAKER: three dozen people have touched it
[05:13] SPEAKER: probably over that three year period almost.
[05:16] SPEAKER: And it's, there's a lot of like kind of,
[05:19] SPEAKER: oh yeah, no, this is the way it works here,
[05:20] SPEAKER: but this isn't stuff that's in every game
[05:23] SPEAKER: and probably not the way we would design it
[05:24] SPEAKER: if we were starting from scratch today.
[05:26] SPEAKER: But like, so the upshot is for the map logic.
[05:30] SPEAKER: So an example of the thing I can do with map logic is
[05:32] SPEAKER: I have a series of triggers
[05:35] SPEAKER: and one of the triggers starts the holdout, right?
[05:38] SPEAKER: When somebody presses a button, it starts the whole,
[05:40] SPEAKER: one of the triggers changes the level context
[05:44] SPEAKER: from, hey, this is a campaign level
[05:45] SPEAKER: to this is a holdout level,
[05:46] SPEAKER: or this is holdout level to a campaign level
[05:48] SPEAKER: by just destroying a bunch of campaign entities.
[05:51] SPEAKER: So like switches that you only use in campaign mode,
[05:53] SPEAKER: stuff like that.
[05:54] SPEAKER: The next one starts the holdout part of the thing,
[05:57] SPEAKER: which includes spawning enemies
[05:59] SPEAKER: and setting up the capture points and all that stuff.
[06:02] SPEAKER: And there's some like randomization triggers in there
[06:05] SPEAKER: that make it a little bit different every time
[06:06] SPEAKER: and stuff like that.
[06:08] SPEAKER: So like you can do a ton without touching any code
[06:11] SPEAKER: is the takeaway.
[06:13] SPEAKER: And if you can get into the blueprints,
[06:14] SPEAKER: then you can do a lot more,
[06:16] SPEAKER: including like change the way the mode works entirely
[06:19] SPEAKER: and stuff like that.
[06:20] SPEAKER: So yeah, it's been weird and fun.
[06:22] SPEAKER: - Just make sure you don't pull out any load bearing entities.
[06:25] SPEAKER: - I am, look, I have been,
[06:27] SPEAKER: I was asked very nicely not to submit any changes
[06:29] SPEAKER: to blueprints that are referenced across the entire project.
[06:32] SPEAKER: 'Cause that's the problem.
[06:33] SPEAKER: Like that's like the matter compiler,
[06:35] SPEAKER: the thing that gives out perks
[06:36] SPEAKER: is used in every level of the game.
[06:38] SPEAKER: So if I make a change to that,
[06:40] SPEAKER: there is some big downstream consequences.
[06:42] SPEAKER: Now I can make an instance of that
[06:43] SPEAKER: and do whatever I want to it in my instance
[06:45] SPEAKER: that lives in my level.
[06:46] SPEAKER: But I shouldn't, I don't touch the parent classes.
[06:49] SPEAKER: - Always play in the sandbox.
[06:51] SPEAKER: - Love this, look, they saw what I was doing.
[06:53] SPEAKER: 'Cause initially they were like,
[06:54] SPEAKER: hey, you can just edit it on the layer in the level.
[06:57] SPEAKER: 'Cause there's also level layers in Unreal.
[07:00] SPEAKER: So like in each level of the map,
[07:03] SPEAKER: there's a lighting level and there's a geo level
[07:05] SPEAKER: and there's a gameplay level and there's a sound level
[07:08] SPEAKER: and there's a voice level and all this stuff.
[07:10] SPEAKER: And they were like, we'll just make you a holdout level
[07:12] SPEAKER: and you could just edit in there
[07:13] SPEAKER: and just tag stuff appropriately.
[07:15] SPEAKER: And then they saw what I did the first day
[07:17] SPEAKER: and they were like, we're gonna make you a copy of the level
[07:20] SPEAKER: and we're gonna revert,
[07:22] SPEAKER: then copy your stuff over to the new copy of the level.
[07:24] SPEAKER: And then we're gonna revert your changes to the main level.
[07:27] SPEAKER: I was like, that's probably best.
[07:28] SPEAKER: - They didn't pat your head while they did that, did they?
[07:30] SPEAKER: - No, they were very nice about it.
[07:32] SPEAKER: But I did break the event that happens
[07:36] SPEAKER: at the end of the level, not in a permanent way,
[07:38] SPEAKER: but like in a way that I would have had to go back
[07:41] SPEAKER: and do a little bit, anyway.
[07:42] SPEAKER: But the option is now I can change the geo of the level
[07:44] SPEAKER: and that's really fun 'cause I'm like changing
[07:45] SPEAKER: where paths are and stuff like that.
[07:47] SPEAKER: So yeah, it's been neat.
[07:48] SPEAKER: It's been neat to learn.
[07:49] SPEAKER: It's like this week, it's that sweet spot for new learning
[07:53] SPEAKER: where you're like, hey, on day one,
[07:56] SPEAKER: I don't even know what the thing is that I need,
[07:58] SPEAKER: the name of the thing.
[07:59] SPEAKER: I don't even know the name of the thing that I need to know
[08:01] SPEAKER: so I can search for a thing to figure out
[08:03] SPEAKER: what I should be doing.
[08:05] SPEAKER: And now I feel pretty like dangerously proficient
[08:08] SPEAKER: is what I would say at this point.
[08:09] SPEAKER: Dave, when you go from not knowing,
[08:11] SPEAKER: when you don't know what you don't know
[08:14] SPEAKER: and you end up at least you know what you don't know.
[08:17] SPEAKER: Yeah, that's progress.
[08:18] SPEAKER: I'm right in the Dunning-Kruger sweet spot right now, man.
[08:21] SPEAKER: (upbeat music)
[08:39] SPEAKER: (upbeat music continues)
[08:49] SPEAKER: Welcome to Brad and Will Made a Tech Pod, I'm Will.
[08:52] SPEAKER: I'm Brad.
[08:53] SPEAKER: That was a really fast time, Brad.
[08:55] SPEAKER: Was it?
[08:56] SPEAKER: I've been working on it.
[08:56] SPEAKER: Yeah, you've been workshopping it?
[08:58] SPEAKER: You like do this in the shower?
[08:59] SPEAKER: Well, when I edit it every week,
[09:00] SPEAKER: there's always a pause there that I frequently cut out
[09:03] SPEAKER: 'cause I don't know, like maybe it's just a latency thing.
[09:07] SPEAKER: It's never as snappy as I think it is when I say it.
[09:10] SPEAKER: It felt pretty snappy today.
[09:11] SPEAKER: It's like you were, it's like you used the force
[09:13] SPEAKER: to anticipate the welcome.
[09:14] SPEAKER: Well, fingers crossed.
[09:15] SPEAKER: There's no silence there to cut out.
[09:17] SPEAKER: Finger, yeah, exactly.
[09:18] SPEAKER: Brad, this week we have a,
[09:21] SPEAKER: I was trying to get a pun, but I got nothing.
[09:24] SPEAKER: I was gonna say novel, but it's not a book.
[09:25] SPEAKER: It's, the topic this week is right in front of us.
[09:30] SPEAKER: It's- It's right.
[09:32] SPEAKER: Yeah, it's-
[09:33] SPEAKER: It's hands-on, I've got my hands on it right now.
[09:36] SPEAKER: Yeah, we were sitting here and we were like,
[09:38] SPEAKER: what's the oldest thing?
[09:40] SPEAKER: I think this is probably also an episode,
[09:42] SPEAKER: but like what's the oldest piece of technology you use
[09:45] SPEAKER: on the day-to-day?
[09:45] SPEAKER: Don't answer that, that's for later.
[09:47] SPEAKER: Okay.
[09:47] SPEAKER: That's a future question.
[09:50] SPEAKER: But in doing that, I was sitting here
[09:53] SPEAKER: looking around my desk and I was like, wait,
[09:54] SPEAKER: I have a bunch of interesting stuff on my desk
[09:56] SPEAKER: and I'm about to go through and rewire everything
[09:58] SPEAKER: after about a year.
[09:59] SPEAKER: And I wanna talk about what has,
[10:01] SPEAKER: we wanna talk about what is on our desks.
[10:03] SPEAKER: Yeah.
[10:04] SPEAKER: And what is working and what isn't
[10:06] SPEAKER: in terms of like the wiring.
[10:07] SPEAKER: Yeah, actually in my case, I'm excited to talk about
[10:10] SPEAKER: what's not on my desk, which is cords.
[10:13] SPEAKER: That sounds nice.
[10:14] SPEAKER: I just very recently, like a month ago,
[10:17] SPEAKER: reached cord zero, like not a single wire
[10:20] SPEAKER: running across my desk.
[10:20] SPEAKER: So that's, that is part of the impetus for this.
[10:23] SPEAKER: Well, I'm, yeah, I don't have that kind of discipline,
[10:27] SPEAKER: I don't think.
[10:27] SPEAKER: I'm a, my desk is a chaos engine and I'm okay with that.
[10:31] SPEAKER: I've, I'm not, look, I don't need to live your minimalist
[10:34] SPEAKER: lifestyle to feel fulfilled.
[10:36] SPEAKER: It's so good.
[10:38] SPEAKER: But I do, I do enjoy having my desk wire situation solved
[10:45] SPEAKER: and like going, like going through and evaluating,
[10:47] SPEAKER: going through and evaluating this,
[10:49] SPEAKER: there's some stuff that works really, really well.
[10:50] SPEAKER: Like I love the, the reusable zip ties,
[10:54] SPEAKER: switching from Velcro ties or single use zip ties
[10:57] SPEAKER: to the reusable ones with little push button
[10:59] SPEAKER: has been- What?
[11:00] SPEAKER: Yeah, have you ever- Oh my God.
[11:02] SPEAKER: Yeah, so they have a- Oh my God.
[11:04] SPEAKER: The clicky part has a little push down.
[11:06] SPEAKER: No.
[11:07] SPEAKER: And then when you need to get a cable out,
[11:08] SPEAKER: you just push the thing down, unzip the zip tie
[11:10] SPEAKER: a little bit. Oh man.
[11:11] SPEAKER: And then I'll, yeah.
[11:13] SPEAKER: I bought like 300 of the classic zip ties
[11:16] SPEAKER: from Monoprice a few years ago,
[11:17] SPEAKER: and I've still got like 250 left.
[11:19] SPEAKER: So it's going to be a while before I get to the-
[11:20] SPEAKER: Just donate them to needy children, Brad.
[11:22] SPEAKER: Yes, you're right. It's fine.
[11:23] SPEAKER: Yeah, put it, it's a life-changing thing.
[11:27] SPEAKER: Five minutes into this episode
[11:28] SPEAKER: and I've already learned something actionable.
[11:29] SPEAKER: I mean, I've got a decent number of the Velcro zip ties,
[11:32] SPEAKER: which are also reusable, but.
[11:34] SPEAKER: They get, so the problem with the Velcro ones for me
[11:36] SPEAKER: is that they collect dust over a period of time
[11:40] SPEAKER: in a way that is icky.
[11:42] SPEAKER: Sure.
[11:43] SPEAKER: So I'm not a huge fan of those.
[11:44] SPEAKER: And also they're not, they don't have the strength
[11:47] SPEAKER: that I need for the size, scope and scale of cables.
[11:50] SPEAKER: I have- Fair, fair.
[11:52] SPEAKER: Anyway, I thought what we should do,
[11:54] SPEAKER: see, you're in a pretty,
[11:56] SPEAKER: you're happy with your situation now-ish.
[11:58] SPEAKER: I, let's say, hmm, within my means,
[12:03] SPEAKER: I'm living within my means, let's say.
[12:05] SPEAKER: Okay, I like that.
[12:07] SPEAKER: With the space that I've got
[12:08] SPEAKER: and the desk that I've got and et cetera, et cetera,
[12:11] SPEAKER: I've kind of hammered it into a shape I can live with.
[12:15] SPEAKER: Yeah.
[12:15] SPEAKER: If I had a bigger space and got a new desk though,
[12:17] SPEAKER: I would definitely make some changes, but anyways.
[12:19] SPEAKER: Well, so yeah, and I have a sit stand
[12:21] SPEAKER: that I go up and down on pretty much every day.
[12:24] SPEAKER: Like physically, you mean not in terms of your opinion?
[12:27] SPEAKER: No, no, no, yeah, I love the desk.
[12:29] SPEAKER: I literally, I sit here and when I get tired of sitting
[12:32] SPEAKER: that I stand up and my back is better for it
[12:34] SPEAKER: and generally healthier.
[12:36] SPEAKER: Okay, that could have been interpreted
[12:38] SPEAKER: as you like it sometimes and not so much others.
[12:40] SPEAKER: No, I absolutely love it, it's my favorite.
[12:43] SPEAKER: So like it said, but it presents a unique challenge
[12:46] SPEAKER: in terms of the stuff that's coming from the top
[12:50] SPEAKER: has to go to the bottom somehow and yeah.
[12:53] SPEAKER: That's always, I mean, granted,
[12:55] SPEAKER: I'm like an obsessive cable router.
[12:58] SPEAKER: That's actually, you know what?
[12:58] SPEAKER: I have zero cords touching the top of the desk
[13:00] SPEAKER: or the floor underneath, but because of that,
[13:04] SPEAKER: that's been always the thing that worried me the most
[13:06] SPEAKER: about a standing desk or a sit stand in particular.
[13:09] SPEAKER: If it was just a standing desk, it would not be a problem,
[13:11] SPEAKER: but having to accommodate for two heights
[13:14] SPEAKER: while wanting to mount and like route every cable.
[13:16] SPEAKER: Yeah, there's a lot of like cable slack issues
[13:19] SPEAKER: that you'd have to worry about there.
[13:20] SPEAKER: The solution I have for that is works,
[13:23] SPEAKER: but it is not like, I don't love it.
[13:25] SPEAKER: So should I ask now or should we get to it in line?
[13:28] SPEAKER: Well, why don't we do, let's do yours first.
[13:29] SPEAKER: 'Cause I think yours is like you like,
[13:33] SPEAKER: I like my reusable zip ties,
[13:35] SPEAKER: but I think yours is the success story here.
[13:37] SPEAKER: Really?
[13:38] SPEAKER: Your desk is really, like my desk is,
[13:40] SPEAKER: I'm gonna go and tell you,
[13:41] SPEAKER: if you looked at my desk, it would give you hives, right?
[13:44] SPEAKER: And you're gonna ask me to take a picture of it
[13:46] SPEAKER: and I'm gonna be real and tell you that what I'm gonna do
[13:48] SPEAKER: when you ask me to do that is I'm gonna spend
[13:50] SPEAKER: about an hour cleaning it off
[13:52] SPEAKER: and leave it a little bit messy still.
[13:54] SPEAKER: - You have to capture it in the moment.
[13:55] SPEAKER: - No, I'm not, look, there's a Lumia 910 on my desk.
[13:58] SPEAKER: I've made choices with my life that I'm not happy with.
[14:01] SPEAKER: - Everything, I need a photo in situ
[14:04] SPEAKER: of what you got going on.
[14:05] SPEAKER: Also, you showed me that 920 right before this
[14:07] SPEAKER: and I got kind of excited.
[14:09] SPEAKER: It's not the yellow one.
[14:10] SPEAKER: It's not the canonical Lumia 920, but still.
[14:13] SPEAKER: - The blue one's the good one.
[14:14] SPEAKER: - Yeah, you think so?
[14:16] SPEAKER: - Yeah, the yellow, I don't like a, I like a darker.
[14:18] SPEAKER: Anyway.
[14:19] SPEAKER: - I don't remember which of my many discords
[14:21] SPEAKER: came up on recently that somebody was posting photos
[14:24] SPEAKER: of their Lumia 920 and now you've got yours out
[14:26] SPEAKER: and it reminded me, man, I wish I had gotten a Lumia 920
[14:29] SPEAKER: back in the day.
[14:30] SPEAKER: - I couldn't get it to charge, which kind of bums me out
[14:34] SPEAKER: 'cause I think it's probably completely unopenable.
[14:36] SPEAKER: - Man, that's a bummer.
[14:39] SPEAKER: Have I said this before?
[14:39] SPEAKER: I'm pretty sure I've mentioned this before.
[14:41] SPEAKER: My Windows phone and my one Android phone,
[14:45] SPEAKER: both are on their last attempt to put the security code in
[14:48] SPEAKER: before they lock themselves out forever.
[14:50] SPEAKER: - How did you, do you not,
[14:51] SPEAKER: I always use the same security code.
[14:53] SPEAKER: - Well, let's see.
[14:54] SPEAKER: So on the Android, I was using the pattern-based one,
[14:56] SPEAKER: the shape, not the number.
[14:57] SPEAKER: - Oh God, yeah, that's a disaster.
[14:58] SPEAKER: - And I don't really, I mean,
[15:00] SPEAKER: the Windows phone was so long, it was like 10 years ago.
[15:02] SPEAKER: I was definitely using a different code at that point.
[15:06] SPEAKER: - I just wanted to play hexic.
[15:08] SPEAKER: - I mean, I can't blame you for that.
[15:09] SPEAKER: I mean, there's nothing like truly replaceable on there.
[15:13] SPEAKER: I would like, you know, I wouldn't mind seeing
[15:14] SPEAKER: what photos are on there and stuff like that,
[15:16] SPEAKER: but I mean, it's not gonna kill me if I never get it back.
[15:18] SPEAKER: - I wonder if you could just break the encryption on them
[15:20] SPEAKER: at this point.
[15:21] SPEAKER: - I don't know about that.
[15:22] SPEAKER: - I have a 4090, give me the image, I can just let it rip.
[15:27] SPEAKER: - I did crack a password protected zip a couple of years ago
[15:31] SPEAKER: that I've had for like 20 years, anyway.
[15:33] SPEAKER: - So yeah, Brad, what's on your desk?
[15:35] SPEAKER: - Okay, so should we just take inventory here?
[15:38] SPEAKER: - Yeah, let's take stock of the situation first.
[15:40] SPEAKER: - Okay, yeah, there's like a million different angles
[15:42] SPEAKER: to go from with this, 'cause like I've been looking
[15:44] SPEAKER: on mechanical keyboards a little bit again lately,
[15:46] SPEAKER: so we could talk briefly about that.
[15:48] SPEAKER: - Well, yeah, I mean--
[15:49] SPEAKER: - As we go down the line.
[15:51] SPEAKER: - Kind of the impetus for this episode is,
[15:53] SPEAKER: I saw a lot of talk in the Discord this week,
[15:55] SPEAKER: and also on Mastodon, people were posting,
[15:58] SPEAKER: there's a couple of really good videos that came out
[16:00] SPEAKER: this week about how people have managed zero cable
[16:02] SPEAKER: or cable light clean desks with like,
[16:06] SPEAKER: but most of them are people using a MacBook Pro
[16:10] SPEAKER: as their main computer and like they put it
[16:12] SPEAKER: into a docking station and then it hooks up
[16:15] SPEAKER: to one or two monitors and it's really like,
[16:19] SPEAKER: I don't wanna say it, but it's kind of easy mode.
[16:21] SPEAKER: - Huh, okay.
[16:23] SPEAKER: - Like you wanna impress me, get like three or four monitors,
[16:26] SPEAKER: a couple of desktops, you know, some lights,
[16:31] SPEAKER: some three cameras, the whole thing.
[16:33] SPEAKER: - I prefer a non-judgmental discussion
[16:35] SPEAKER: of desk organization techniques, but--
[16:38] SPEAKER: - I'm not, look, I was like, okay, it's cool
[16:42] SPEAKER: that you made custom right-angle XLR mounts
[16:45] SPEAKER: for your speakers, that is actually really neat,
[16:48] SPEAKER: but also, yeah, your problems are,
[16:54] SPEAKER: the magnitude of your challenge is low
[16:56] SPEAKER: compared to a gamer desktop, anyway.
[16:58] SPEAKER: - Fair, fair, okay, all right.
[17:01] SPEAKER: Yeah, I will say when we did the PSVR2 streaming
[17:05] SPEAKER: two, three weeks ago, you know, when you occasionally,
[17:08] SPEAKER: you will see what that headset sees, right,
[17:10] SPEAKER: from when it would drop to that inside out view,
[17:13] SPEAKER: people were seeing what I see when I sit at this desk,
[17:15] SPEAKER: although, you know, it was a black and white
[17:17] SPEAKER: kind of weird digitalized version a little bit.
[17:20] SPEAKER: - Wait, it doesn't, the PlayStation
[17:22] SPEAKER: doesn't stop you from exporting that?
[17:24] SPEAKER: - Oh no, it just shows it in the,
[17:26] SPEAKER: what do they call it, in like everything,
[17:28] SPEAKER: they have a name for it, it's like the companion view
[17:30] SPEAKER: or whatever that goes to the TV.
[17:31] SPEAKER: - Wow, that's a trip because it like--
[17:33] SPEAKER: - It outputs it to the TV.
[17:34] SPEAKER: - Like when I was playing God of War the other day,
[17:37] SPEAKER: they, they, they HDCP or don't stream out the,
[17:41] SPEAKER: the, the, like the Sony logo that pops up
[17:45] SPEAKER: before the game starts, the video there just doesn't play
[17:48] SPEAKER: on the Chiaki stream, anyway.
[17:50] SPEAKER: - But yeah, the view of your room,
[17:52] SPEAKER: they are happy to let anybody--
[17:53] SPEAKER: - Thanks, Sony.
[17:54] SPEAKER: - Anyway, everybody on the stream got to see what I see
[17:57] SPEAKER: from my desk and the first comments I saw were just like,
[17:59] SPEAKER: "Wow, that's a clean desk," and I felt very good.
[18:02] SPEAKER: - Yeah, I mean, look, I'm gonna go and tell you,
[18:03] SPEAKER: I've seen your desk, I've stopped by your house unexpectedly
[18:06] SPEAKER: before your desk has always been shockingly clean.
[18:08] SPEAKER: - It takes some effort.
[18:10] SPEAKER: You're not wrong when you say that it's some work.
[18:12] SPEAKER: - Mine lasted about a month when I did that last time.
[18:16] SPEAKER: - I actually, like we talked about last week,
[18:17] SPEAKER: like when I'm, when I'm in one of these, like,
[18:19] SPEAKER: PC fixing explosions, my desk was a mess.
[18:23] SPEAKER: Like a huge mess, there were like 30 different things
[18:26] SPEAKER: all over it at that point,
[18:27] SPEAKER: but that's not the preferred state of affairs.
[18:29] SPEAKER: Okay, let's get started here.
[18:30] SPEAKER: - Yeah, let's get, let's get into it.
[18:31] SPEAKER: - Okay, so I, yeah, like I said, I, I,
[18:34] SPEAKER: as of buying this wireless mouse a few weeks ago,
[18:37] SPEAKER: which has vastly exceeded my expectations.
[18:40] SPEAKER: That was about, that was the last holdout
[18:41] SPEAKER: of cords on my desk.
[18:42] SPEAKER: So I'm using an Apple magic aluminum Bluetooth keyboard
[18:48] SPEAKER: with windows.
[18:48] SPEAKER: - Best keyboard ever made is my understanding.
[18:50] SPEAKER: - It's, look, it's very quiet.
[18:52] SPEAKER: - Yeah, it is very quiet.
[18:53] SPEAKER: - I've been thinking about it.
[18:54] SPEAKER: I've been, again, looking at wireless mechanicals,
[18:57] SPEAKER: thinking like, yeah, maybe I should.
[19:00] SPEAKER: But when you're on an open mic, as much as I am,
[19:02] SPEAKER: having this extremely quiet keyboard is pretty nice.
[19:07] SPEAKER: Cannot recommend using this keyboard with windows,
[19:09] SPEAKER: even though I do it, it's not especially compatible.
[19:14] SPEAKER: I guess I'm saying it works.
[19:15] SPEAKER: - You don't get a lot of like,
[19:17] SPEAKER: the bells and whistles aren't there, right?
[19:20] SPEAKER: - If by bells and whistles,
[19:21] SPEAKER: you mean a battery readout, then yes.
[19:23] SPEAKER: - How long does the battery last though?
[19:25] SPEAKER: - Like a month.
[19:26] SPEAKER: - And it's like a AA, right?
[19:27] SPEAKER: - No, no, no, it's rechargeable.
[19:29] SPEAKER: - Oh, you have the rechargeable one?
[19:30] SPEAKER: - Yes, this keyboard has a lightening port on it.
[19:33] SPEAKER: - Ew, wait, did you plug it in like a phone?
[19:38] SPEAKER: - Well, it's lightening into anything like a USB-A
[19:40] SPEAKER: or whatever.
[19:41] SPEAKER: - But is it, okay, is the lightening port someplace stupid
[19:45] SPEAKER: where you can't use the keyboard where it's plugged in?
[19:47] SPEAKER: - No, it's right here on the-
[19:49] SPEAKER: - Oh, on the back.
[19:50] SPEAKER: - It's right there on the back.
[19:50] SPEAKER: - Okay, so you know, it's funny,
[19:52] SPEAKER: you've said that you have this keyboard.
[19:53] SPEAKER: I assumed you were talking about the one with the roll
[19:56] SPEAKER: on the back, the one before that that had two AAs.
[19:59] SPEAKER: - No, this one is like wafer thin.
[20:01] SPEAKER: I mean, how thin is this thing?
[20:02] SPEAKER: Like probably a centimeter.
[20:05] SPEAKER: - It doesn't look ergonomically sound.
[20:06] SPEAKER: It's a centimeter and a half on the back probably.
[20:09] SPEAKER: - At its thickest point.
[20:11] SPEAKER: Yeah, Windows cannot pull the battery life on this thing.
[20:14] SPEAKER: - Of course not.
[20:14] SPEAKER: Why would you use the standard USB way to do that?
[20:17] SPEAKER: There's a proprietary way that won't work with any other OS.
[20:20] SPEAKER: - So I just have to guess at the battery level,
[20:22] SPEAKER: but otherwise it works.
[20:25] SPEAKER: I got this Logitech G502X light speed,
[20:28] SPEAKER: which we talked about on the patron episode a little bit
[20:29] SPEAKER: and a couple of weeks ago, I love this thing.
[20:32] SPEAKER: - It sounds like they've changed the light speed tech
[20:34] SPEAKER: so that it doesn't eat battery anymore too.
[20:36] SPEAKER: - Dude, it's crazy.
[20:37] SPEAKER: I can, hold on, let me pull up the onboard memory manager
[20:39] SPEAKER: right now and tell you, I am at 75% right now.
[20:46] SPEAKER: I charge it about 20 minutes a week.
[20:50] SPEAKER: - Jesus, really? - And that's about it.
[20:51] SPEAKER: Yes, so far.
[20:53] SPEAKER: So from 100% at the end of the week,
[20:56] SPEAKER: it'll be down to like 85%, maybe 82, something like that.
[21:01] SPEAKER: And that's like pretty heavy daily use.
[21:04] SPEAKER: And then 20, 30 minutes plugged in.
[21:06] SPEAKER: So also having this mouse and the battery
[21:08] SPEAKER: not being easily replaceable,
[21:10] SPEAKER: meaning I want the battery longevity
[21:11] SPEAKER: to be as good as possible,
[21:13] SPEAKER: has prompted me to finally go out.
[21:14] SPEAKER: I know we've talked about this before,
[21:15] SPEAKER: but I need to refresh my memory.
[21:17] SPEAKER: Like, hey, what are the best battery charging practices
[21:19] SPEAKER: to extend the life of the battery?
[21:21] SPEAKER: - Yeah, don't fill it all the way up.
[21:22] SPEAKER: Don't run it all the way down.
[21:24] SPEAKER: - The thing I settled on was kind of try to keep it
[21:26] SPEAKER: between basically like 60 and 80%,
[21:28] SPEAKER: 60 to 85, something like that.
[21:30] SPEAKER: And so that's why I've been charging it
[21:32] SPEAKER: like 20 minutes a week, basically.
[21:35] SPEAKER: I don't charge it all the way back to full.
[21:36] SPEAKER: - I don't wanna, I'm not gonna yuck your yums here,
[21:39] SPEAKER: but it's really easy to replace the battery in those mice.
[21:43] SPEAKER: - Well, no, that's great.
[21:44] SPEAKER: I mean, that makes me happy then,
[21:45] SPEAKER: 'cause the longer I can use this mouse, the better,
[21:47] SPEAKER: 'cause I love everything about it.
[21:48] SPEAKER: - So the trick on that is that you have to,
[21:51] SPEAKER: the screws are all hidden under the skates on the bottom.
[21:54] SPEAKER: So you'll have to get a replacement set of skates.
[21:56] SPEAKER: But then you just unscrew it and you, huh?
[21:58] SPEAKER: - Do you ruin the skates getting them off?
[22:00] SPEAKER: - They're not gonna be as good as they are now.
[22:02] SPEAKER: And also, the skates wear out over time.
[22:05] SPEAKER: Like even when you're using a soft pad,
[22:06] SPEAKER: I replace the skates every couple of years at the outside.
[22:08] SPEAKER: - Oh, interesting, okay.
[22:11] SPEAKER: - And if you're using a hard pad, they go faster.
[22:12] SPEAKER: - Yeah.
[22:15] SPEAKER: - But then the battery is just,
[22:16] SPEAKER: you can order the batteries on Amazon
[22:18] SPEAKER: and swap a replacement part in really easily.
[22:22] SPEAKER: - Yeah, yeah, I just, everything from the button feel,
[22:25] SPEAKER: they moved to mechanical optical switches
[22:26] SPEAKER: on this new version of the-
[22:27] SPEAKER: - Yeah, this is awesome.
[22:28] SPEAKER: - The X is a refresh of the longstanding 502
[22:31] SPEAKER: that just came out like six months ago.
[22:33] SPEAKER: - Which is like newest sensor and new switches and stuff.
[22:37] SPEAKER: - Yeah, new switches, like ton of buttons.
[22:39] SPEAKER: These little rubberized grips on the side are great.
[22:42] SPEAKER: Like it glides like a dream.
[22:43] SPEAKER: The battery life is amazing.
[22:44] SPEAKER: Like I just could not be happier.
[22:45] SPEAKER: It's a very expensive mouse, but worth every penny.
[22:49] SPEAKER: Speaking of the mousing surface,
[22:50] SPEAKER: I've got a very old funk pad here still.
[22:55] SPEAKER: As a mousing surface.
[22:57] SPEAKER: - Ooh, I found one of those
[22:58] SPEAKER: when I was cleaning out the garage the other day.
[23:00] SPEAKER: - It's still good.
[23:01] SPEAKER: - I am.
[23:02] SPEAKER: - For like 15 years,
[23:03] SPEAKER: it still looks like it did when I got it.
[23:05] SPEAKER: - It's funny, I switched to a soft pad during the PUBG days.
[23:08] SPEAKER: - Huh.
[23:09] SPEAKER: - 'Cause I was trying to reduce all friction
[23:13] SPEAKER: as much as possible.
[23:14] SPEAKER: - Interesting, maybe soft pads aren't what they used to be.
[23:16] SPEAKER: Like my memory of soft mouse pads
[23:18] SPEAKER: is basically from the nineties.
[23:19] SPEAKER: You know, that kind of weird,
[23:20] SPEAKER: like that felt on rubber sort of thing.
[23:23] SPEAKER: I don't know what people are doing these days.
[23:24] SPEAKER: - Yeah, it's like a slippery,
[23:26] SPEAKER: it's like a slippery, super slippery neoprene
[23:28] SPEAKER: on the Logitech one I have now.
[23:30] SPEAKER: - Maybe I should look into new mousing surfaces.
[23:32] SPEAKER: - You're, you're, oh, you didn't get the,
[23:34] SPEAKER: you didn't get the light speed charger pad, right?
[23:36] SPEAKER: - No, I did not, 'cause that was a cord.
[23:38] SPEAKER: - I was gonna say, it comes with both.
[23:39] SPEAKER: It comes with a hard and a soft pad,
[23:42] SPEAKER: which is one of the reasons it's so fricking expensive.
[23:44] SPEAKER: - Yeah, I mean, that would have just been replacing
[23:45] SPEAKER: the mouse cord with a pad cord, like a pad cord.
[23:49] SPEAKER: - Well, yeah, like in my head,
[23:51] SPEAKER: I think maybe I should put the pad off on a side table
[23:54] SPEAKER: or something someplace and just put the mouse there
[23:56] SPEAKER: when I walk away at the end of the night
[23:57] SPEAKER: and let it charge overnight.
[23:59] SPEAKER: - Yeah.
[24:00] SPEAKER: - But also I don't care that much, it turns out.
[24:02] SPEAKER: - Yeah, yeah.
[24:02] SPEAKER: So yeah, I mean, that was kind of what I thought
[24:04] SPEAKER: I would end up doing with the corded charging on the mouse,
[24:07] SPEAKER: but instead it's like I said,
[24:08] SPEAKER: it's like I basically go eat lunch on Saturday
[24:11] SPEAKER: while it's plugged in and I come back
[24:13] SPEAKER: and it's fine for the week.
[24:14] SPEAKER: It's kind of amazing.
[24:16] SPEAKER: Let's see here.
[24:17] SPEAKER: All right, I've got the,
[24:19] SPEAKER: I've got the classic Cambridge Soundworks PowerCube speakers
[24:22] SPEAKER: that we've talked about before.
[24:24] SPEAKER: - Yeah.
[24:25] SPEAKER: - Along the back I have a Macbook.
[24:25] SPEAKER: - Just to be clear, those are '90s era
[24:27] SPEAKER: or early 2000s era computer speakers,
[24:30] SPEAKER: analog computer speakers.
[24:31] SPEAKER: - I was in the dorm.
[24:32] SPEAKER: I was playing a lot of Quake III when I bought these.
[24:34] SPEAKER: - Yeah, they are really good.
[24:35] SPEAKER: That subwoofer was good for Quake.
[24:37] SPEAKER: - Those things, yes.
[24:38] SPEAKER: Good speakers are good speakers, they last.
[24:40] SPEAKER: - Do you use speakers a lot
[24:41] SPEAKER: or are you mostly headphones these days?
[24:42] SPEAKER: - I only use speakers for like just casually listening
[24:45] SPEAKER: to music while I'm dinking around with the NAS
[24:48] SPEAKER: or something like that.
[24:48] SPEAKER: Like anything, especially any kind of production recording,
[24:52] SPEAKER: streaming stuff is headphones,
[24:54] SPEAKER: but even playing games is headphones at this point.
[24:56] SPEAKER: They're purely for just like listening to whatever.
[24:58] SPEAKER: - I have to imagine the pigs would be a little traumatized
[25:01] SPEAKER: if you like fired up some Call of Duty
[25:03] SPEAKER: and like had loud thumps.
[25:05] SPEAKER: - Yes, for sure.
[25:07] SPEAKER: So along the back I've got my Macbook Pro USB-C charger.
[25:11] SPEAKER: I've got an Anker wireless phone charging stand.
[25:15] SPEAKER: I've got my Panic Playdate, which I use as a desk clock
[25:18] SPEAKER: 'cause it stays on all the time.
[25:20] SPEAKER: - Do you see they put the,
[25:21] SPEAKER: they rolled out their catalog this week?
[25:23] SPEAKER: - Yes, I want to try those games.
[25:24] SPEAKER: - Crank to buy.
[25:26] SPEAKER: - Wait, really?
[25:27] SPEAKER: - Yeah.
[25:28] SPEAKER: - Oh, I hadn't tried the store yet.
[25:29] SPEAKER: Is that a free series? - It's fucking great.
[25:31] SPEAKER: Yeah.
[25:31] SPEAKER: - Are you like filling up a meter?
[25:33] SPEAKER: - You crank the meter to confirm the purchase.
[25:35] SPEAKER: - That's, oh, they listened to our episode.
[25:37] SPEAKER: - It's very good.
[25:39] SPEAKER: - Let's see here.
[25:40] SPEAKER: That's kind of, I mean,
[25:41] SPEAKER: I've got like a vase with some bamboo growing out of it.
[25:43] SPEAKER: We don't need to get into the desk decorations.
[25:46] SPEAKER: - I need some green in here.
[25:48] SPEAKER: - I highly recommend to plan on your desk
[25:50] SPEAKER: if you can find space for it.
[25:52] SPEAKER: And if you have light.
[25:55] SPEAKER: I'm sorry.
[25:56] SPEAKER: - Oh no, I was going to say,
[25:57] SPEAKER: and then do like, what's your monitor such these days?
[25:59] SPEAKER: - Yeah, so I've got two 27 inch 1440p monitors
[26:01] SPEAKER: on a single two monitor arm.
[26:04] SPEAKER: - So do you have them like centered in front of you
[26:06] SPEAKER: or do you have one centered and one off to the side?
[26:08] SPEAKER: - Oh, I cannot.
[26:09] SPEAKER: I believe, no offense to people who like it this way.
[26:11] SPEAKER: But when the people who have two monitors
[26:13] SPEAKER: and they sit kind of with their face
[26:15] SPEAKER: staring directly at the seam in between them,
[26:18] SPEAKER: like I just don't understand.
[26:21] SPEAKER: But yeah, I do basically sort of main monitor,
[26:23] SPEAKER: side monitor.
[26:24] SPEAKER: Like I have, I have left monitor
[26:25] SPEAKER: is just front on perpendicular to my face,
[26:28] SPEAKER: to my sight line.
[26:30] SPEAKER: And then I've got another one kind of cocked
[26:31] SPEAKER: off to the right 45 degrees ish for discord
[26:34] SPEAKER: and stuff like that.
[26:35] SPEAKER: - I was gonna say, this is a little off topic,
[26:36] SPEAKER: but do you do like, I used to do when I was side by side,
[26:38] SPEAKER: I would do like communications monitor
[26:40] SPEAKER: or maybe reference monitor and then like work monitor.
[26:43] SPEAKER: - That's exactly what it is.
[26:44] SPEAKER: The side monitor is for discord, for my email clients,
[26:47] SPEAKER: for like, if I'm working in a terminal window
[26:51] SPEAKER: and I've got some instructions for something up,
[26:52] SPEAKER: then that goes on the side monitor, stuff like that.
[26:55] SPEAKER: That's exactly, exactly it, yeah.
[26:58] SPEAKER: And then the last thing is my camera setup,
[27:00] SPEAKER: which is not on the desk at all times.
[27:02] SPEAKER: I've got an Elgato key light.
[27:06] SPEAKER: - You take the light and the camera and everything off?
[27:08] SPEAKER: - I have to, so we haven't gotten to what's under the desk,
[27:10] SPEAKER: but I've got two Ikea Signum.
[27:13] SPEAKER: You can tell we did the homework
[27:14] SPEAKER: and we looked up all the product names
[27:16] SPEAKER: for all the stuff we use.
[27:18] SPEAKER: I've got two Ikea cable racks.
[27:19] SPEAKER: It's the Signum is the product name.
[27:22] SPEAKER: - Oh man, yeah, that's nice.
[27:24] SPEAKER: That's better, they're like center pole
[27:27] SPEAKER: with a basket that hangs on either side.
[27:29] SPEAKER: - Yeah, like I guess the only downside,
[27:31] SPEAKER: if you can call it that, is they screw in,
[27:33] SPEAKER: like they're pretty heavy and you have to kind of,
[27:34] SPEAKER: you have to screw into the desk to mount them.
[27:37] SPEAKER: - Screwing in is a good thing.
[27:39] SPEAKER: - But they're mounted right on the back underhang
[27:42] SPEAKER: of the desk and so the desk mount clamp thing
[27:45] SPEAKER: that came with the key light wouldn't fit because they're,
[27:48] SPEAKER: I actually tried bending a couple of those,
[27:49] SPEAKER: you see the little like metal loops on them?
[27:51] SPEAKER: I actually tried bending a couple of those down
[27:53] SPEAKER: to try to make room for the mount for the key light,
[27:55] SPEAKER: but it just wouldn't, I couldn't get it in there.
[27:57] SPEAKER: - How deep is your desk?
[27:58] SPEAKER: Is it only 24 inches?
[28:00] SPEAKER: - No, actually. - Or is it 30?
[28:03] SPEAKER: - Probably about 30 if I had to guess.
[28:05] SPEAKER: Maybe more actually, it's a pretty big desk.
[28:07] SPEAKER: It's from, this desk is from the CRT days,
[28:09] SPEAKER: so it's got depth to it.
[28:11] SPEAKER: Anyway, so I bought the Elgato weighted stand.
[28:16] SPEAKER: It's basically just a base replacement.
[28:18] SPEAKER: You take the little desk clamp off
[28:19] SPEAKER: and it's just a big 10 pound metal disc instead.
[28:23] SPEAKER: So I basically just have to set the camera on the desk
[28:26] SPEAKER: when I'm using it and take it away when I'm not.
[28:29] SPEAKER: - So it's funny 'cause I've been looking at the,
[28:32] SPEAKER: I have the Elgato key light stands too
[28:33] SPEAKER: and I've been thinking about doing,
[28:37] SPEAKER: I wish I could do just a mount, a flat mount.
[28:41] SPEAKER: - What does that mean?
[28:42] SPEAKER: - Like through the, like could drill a hole
[28:44] SPEAKER: and mount through the desk rather than,
[28:49] SPEAKER: like rather than use the edge clamps.
[28:51] SPEAKER: - Sure, yeah, I can see that.
[28:53] SPEAKER: - Yeah, 'cause like the monitor,
[28:54] SPEAKER: the mic stands often will have like a thing
[28:56] SPEAKER: where you drill a quarter inch hole or whatever and yeah.
[28:59] SPEAKER: - Yes.
[29:02] SPEAKER: - Oh, actually, you know what else I have thought
[29:04] SPEAKER: about doing, so my camera is on a friction arm.
[29:08] SPEAKER: - Yeah.
[29:08] SPEAKER: - Like, you know what those are,
[29:09] SPEAKER: it's basically a jointed metal contraption.
[29:11] SPEAKER: - Yeah, they're fantastic.
[29:12] SPEAKER: - Tighten the joints and it'll kind of bend
[29:13] SPEAKER: into whatever configuration.
[29:14] SPEAKER: - Is it universal where you have one lever
[29:18] SPEAKER: handles all the joints?
[29:19] SPEAKER: - There's one release that kind of makes
[29:21] SPEAKER: the whole thing go slack.
[29:22] SPEAKER: - That's awesome.
[29:23] SPEAKER: - It can be hard to like level the camera
[29:24] SPEAKER: 'cause as soon as you release the tension on the arm,
[29:26] SPEAKER: everything just falls apart.
[29:28] SPEAKER: - Well, do you not have a knobbly guy on the end of the arm?
[29:31] SPEAKER: Like a ball joint, a ball mount?
[29:33] SPEAKER: - Yes, yes.
[29:34] SPEAKER: - Okay.
[29:35] SPEAKER: - Yes, what I've thought about doing
[29:37] SPEAKER: is actually just bolting that friction arm
[29:40] SPEAKER: directly to the monitor stand
[29:42] SPEAKER: and maybe getting a little like ring light
[29:44] SPEAKER: to go around the camera that could fit
[29:45] SPEAKER: maybe on the camera mount
[29:47] SPEAKER: and just removing this key light entirely from the equation.
[29:50] SPEAKER: - So the ring, so you have a space,
[29:53] SPEAKER: yeah, that's interesting.
[29:54] SPEAKER: - I don't know how, I don't know if that might be too heavy
[29:56] SPEAKER: for these monitor arms though, I'm not sure.
[29:58] SPEAKER: - The monitor arm should be fine.
[30:00] SPEAKER: The question is, can you get the friction mount
[30:02] SPEAKER: for the Elgato thing around the tube for the monitor arm?
[30:05] SPEAKER: - Yeah.
[30:06] SPEAKER: - 'Cause my monitor tubes are long,
[30:07] SPEAKER: are too big for the Elgato friction mounts.
[30:11] SPEAKER: 'Cause I bought one of them thinking I could do that
[30:13] SPEAKER: and then it didn't work 'cause I read the docs, it turns out.
[30:15] SPEAKER: - Yeah, anyway, I was kind of forced into this modular
[30:18] SPEAKER: like mobile camera setup 'cause I couldn't mount it
[30:22] SPEAKER: but now that I have it, I kind of actually prefer it
[30:24] SPEAKER: 'cause I just put the camera back in the corner of the room
[30:26] SPEAKER: when I'm done with it
[30:27] SPEAKER: and then there isn't a camera staring at me 24/7.
[30:29] SPEAKER: - Well, it's, I mean, you just put the lens cap
[30:32] SPEAKER: on the camera too.
[30:33] SPEAKER: - Well, yeah, but it's just less clutter, you know,
[30:35] SPEAKER: it's just, now I've got a bunch of nice framed pictures
[30:37] SPEAKER: up here and now I can see them.
[30:39] SPEAKER: - And less clutter above the monitor,
[30:41] SPEAKER: that's an interesting idea, anyway.
[30:43] SPEAKER: - Yes, yes, I don't wanna belabor my entire like
[30:46] SPEAKER: under the desk setup 'cause we'll be here all day.
[30:50] SPEAKER: - But you've mounted a bunch of stuff up under the desk.
[30:53] SPEAKER: - Yeah, so I've got a bunch of stuff mounted under the desk.
[30:54] SPEAKER: Like I said, I've got those Ikea cable racks
[30:56] SPEAKER: mounted in the back with like, dude, dozens
[31:00] SPEAKER: of cables running through them.
[31:02] SPEAKER: Could not even tell you how many cables are back there.
[31:04] SPEAKER: 'Cause like I said, there are no cables touching the floor.
[31:08] SPEAKER: So every manner of HDMI and USB and audio cable
[31:12] SPEAKER: and you name it, network cables,
[31:14] SPEAKER: like it's just endless cables back there,
[31:19] SPEAKER: but it makes it very easy to vacuum under the desk.
[31:21] SPEAKER: - And did you like get right length cables
[31:27] SPEAKER: for that or did you just kind of bundle up extras
[31:28] SPEAKER: in that signum?
[31:29] SPEAKER: - I usually buy longer than I might need
[31:33] SPEAKER: and then just coil stuff as needed.
[31:35] SPEAKER: - Yeah.
[31:36] SPEAKER: - I use a lot of zip ties or twist ties and stuff like that.
[31:38] SPEAKER: 'Cause you never know when you might need extra slack.
[31:41] SPEAKER: - How often do you need extra slack though
[31:42] SPEAKER: is the question I'm asking myself now.
[31:45] SPEAKER: - Yeah, it depends, but also it's not a big deal
[31:46] SPEAKER: to just loop something a few times
[31:48] SPEAKER: to deal with the extra length.
[31:50] SPEAKER: - That's true.
[31:52] SPEAKER: - Let's see, so I've got my router network switch
[31:56] SPEAKER: and two power strips are also mounted
[31:57] SPEAKER: to the back of the desk.
[31:58] SPEAKER: - Ooh, you put the router under there too.
[32:00] SPEAKER: - Yes, yes, I like invisible technology.
[32:03] SPEAKER: I like not seeing things.
[32:04] SPEAKER: - I mean, I guess my router's in the garage,
[32:06] SPEAKER: so it's a little different situation.
[32:08] SPEAKER: - That's the dream is to just put it in a different room,
[32:10] SPEAKER: but let's see, I've got like three raspberry pies
[32:13] SPEAKER: in that signum area.
[32:15] SPEAKER: - Okay.
[32:18] SPEAKER: They're mounted underneath too?
[32:20] SPEAKER: - Not mounted, those are just sitting in the--
[32:21] SPEAKER: - Oh, they're just sitting in the trays.
[32:23] SPEAKER: - Signum forms like kind of a basket sort of shape.
[32:25] SPEAKER: - Yeah.
[32:26] SPEAKER: - So there's pies in there doing different stuff.
[32:29] SPEAKER: There's an HDMI switcher in there.
[32:31] SPEAKER: It's a lot of stuff.
[32:32] SPEAKER: It is a lot of stuff behind, mounted behind
[32:35] SPEAKER: and in that cable rack under the desk.
[32:37] SPEAKER: - Which, do you have an HDMI switcher
[32:38] SPEAKER: that is like stripping HDCP or is it just for,
[32:41] SPEAKER: just so you have like five cables for your console
[32:43] SPEAKER: so you can stream?
[32:44] SPEAKER: - Yeah, it's just for different, it's for outputs.
[32:46] SPEAKER: It's like, it's so I could output straight to these monitors
[32:49] SPEAKER: before I go into the capture card.
[32:50] SPEAKER: - Got it, okay. - Stuff like that.
[32:51] SPEAKER: I had one, my old one stripped HDCP,
[32:53] SPEAKER: but those are harder to find these days.
[32:55] SPEAKER: - Yeah, it turns out it's getting one
[32:57] SPEAKER: that's a newer HDMI spec that strips HDCP is challenging.
[33:01] SPEAKER: - Yeah, the consortium started cracking down on that stuff
[33:04] SPEAKER: from what I understand.
[33:05] SPEAKER: - Weird. - Yeah.
[33:09] SPEAKER: - Okay, so your setup is kind of similar to mine.
[33:14] SPEAKER: I've got a couple of stream decks on the desktop,
[33:17] SPEAKER: one for each PC.
[33:19] SPEAKER: - Okay.
[33:21] SPEAKER: - So I have two PCs.
[33:21] SPEAKER: This is where we should start.
[33:22] SPEAKER: I have two PCs 'cause there's one PC
[33:24] SPEAKER: that does just the video stuff for me,
[33:26] SPEAKER: which is kind of at this point, a legacy of the,
[33:32] SPEAKER: of the PUBG days when like, when I was playing a game
[33:36] SPEAKER: that would take every amount of horsepower you had
[33:39] SPEAKER: and like you were barely holding 70 frames a second.
[33:42] SPEAKER: I just took an old PC and moved OBS over to that
[33:45] SPEAKER: and now I'm kind of, this is the life I live now.
[33:50] SPEAKER: So, but it complicates things, right?
[33:53] SPEAKER: So there's two audio interface, there's a mixer
[33:55] SPEAKER: that takes in a bunch of audio that's not on my desk.
[33:58] SPEAKER: It's on top of a, says some filing cabinets off to the side.
[34:04] SPEAKER: So it means that like, if I want to sit here
[34:05] SPEAKER: and do something with my daughter or something,
[34:07] SPEAKER: then we can have three microphones and it's no problem.
[34:09] SPEAKER: But it also means that there's a lot more wires.
[34:13] SPEAKER: So I've got the two stream decks.
[34:15] SPEAKER: I've got three monitors, two are on one stand in a up down.
[34:19] SPEAKER: So I have like the 1080p gaming monitor,
[34:21] SPEAKER: low and then a 4K kind of reference in email
[34:25] SPEAKER: and everything else monitor up high.
[34:26] SPEAKER: I use fancy zones a lot.
[34:28] SPEAKER: - Oh, fancy zones is great.
[34:29] SPEAKER: I've just started using it in the last couple of weeks.
[34:31] SPEAKER: - It's really good.
[34:32] SPEAKER: - I don't know why, I've had power toys,
[34:34] SPEAKER: the modern power toy, remember old power toys?
[34:37] SPEAKER: - Yeah.
[34:38] SPEAKER: - Remember Windows 95 power toys?
[34:39] SPEAKER: - I remember what I was felt like,
[34:41] SPEAKER: so I felt like I was so special
[34:42] SPEAKER: 'cause I knew about power toys.
[34:43] SPEAKER: - It straight up felt like Wizard of Oz
[34:46] SPEAKER: pulling the curtain back and seeing the machinery type stuff.
[34:49] SPEAKER: I don't know why I have neglected modern current power toys
[34:52] SPEAKER: for so long,
[34:54] SPEAKER: but there's some really good stuff in there.
[34:55] SPEAKER: Fancy zones is right at the top.
[34:58] SPEAKER: - Yeah, fancy zones is the one that I,
[35:01] SPEAKER: like fancy zones is the one that got me to install it
[35:03] SPEAKER: before I switched to Windows 11.
[35:05] SPEAKER: - So does Windows 11 have essentially
[35:07] SPEAKER: that same functionality built in at the base level?
[35:09] SPEAKER: - Yeah, like if you hover over the maximize button,
[35:12] SPEAKER: you get a quad of six potential window configurations.
[35:17] SPEAKER: - But can you define those though?
[35:19] SPEAKER: 'Cause that's the thing about fancy,
[35:20] SPEAKER: for people who don't know fancy zones.
[35:21] SPEAKER: - Yeah, fancy zones lets you,
[35:23] SPEAKER: like the default ones are pretty good.
[35:25] SPEAKER: It's like half vertical, you have 50, 50 vertical,
[35:29] SPEAKER: 20, 66, 20, 33 vertical, 33, 33, 33 vertical.
[35:35] SPEAKER: And then there's like a 25, 50, 25 vertical split
[35:39] SPEAKER: and a quad and a half and two quarters.
[35:43] SPEAKER: So like, it's like it gets about 90% of the way there
[35:47] SPEAKER: just with the defaults, I would say.
[35:48] SPEAKER: - Yeah, just to be clear, fancy zones
[35:50] SPEAKER: and what you're talking about are just ways
[35:51] SPEAKER: to snap windows to existing kind of templates,
[35:54] SPEAKER: to existing layouts.
[35:55] SPEAKER: - Frames inside your monitor resolution.
[35:59] SPEAKER: - Yeah, the thing about fancy zones and power toys
[36:01] SPEAKER: is you can create your layouts
[36:03] SPEAKER: and they're like surprisingly powerful.
[36:06] SPEAKER: You can even do overlapping layouts.
[36:09] SPEAKER: - Yeah, and I think you can even lock,
[36:12] SPEAKER: it may be a different tool that lets you do this,
[36:14] SPEAKER: but you can lock specific things to,
[36:17] SPEAKER: like you can say, always keep Discord in this zone.
[36:20] SPEAKER: - Yeah, that's pretty awesome.
[36:22] SPEAKER: Anyway, so do you have to crane your neck
[36:26] SPEAKER: to look up at the 4K monitor?
[36:28] SPEAKER: - No, so my desk is set up so that the top
[36:33] SPEAKER: of the 1080p monitor is my eye line,
[36:37] SPEAKER: is like even with my eye line when I'm sitting up straight.
[36:39] SPEAKER: And then I kind of just, I kind of rock back in the chair
[36:42] SPEAKER: a little bit when I look at the top one
[36:43] SPEAKER: for an extended period of time.
[36:44] SPEAKER: - That's not so bad.
[36:46] SPEAKER: - So when I originally set up the over under,
[36:48] SPEAKER: I have it set so that you can rotate the whole thing,
[36:50] SPEAKER: like just invert it, and I set up a shortcut
[36:55] SPEAKER: that would let me basically flip the orientation
[36:58] SPEAKER: and flip the two monitors in windows.
[37:00] SPEAKER: And then I used it twice and it was a huge pain in the ass
[37:02] SPEAKER: 'cause of the cables and I never did it again.
[37:04] SPEAKER: 'Cause I initially thought, oh, well, while I'm working,
[37:06] SPEAKER: I'll do the 4K on the bottom and when I'm not working,
[37:08] SPEAKER: but then cameras, so the other thing is my cameras
[37:12] SPEAKER: are between the two monitors so that when I'm looking
[37:15] SPEAKER: at things, it looks like I'm looking,
[37:16] SPEAKER: when I'm looking at the monitors,
[37:17] SPEAKER: it looks like I'm looking at the camera.
[37:18] SPEAKER: - Oh, interesting.
[37:20] SPEAKER: - So I get that over camera position rather than
[37:24] SPEAKER: having to look, being off to the side or whatever.
[37:27] SPEAKER: - Sure.
[37:30] SPEAKER: - So there's one camera, this is again,
[37:33] SPEAKER: the problem with having two computers.
[37:35] SPEAKER: There's one camera for the streaming computer
[37:37] SPEAKER: and then there's one camera for when I'm on zooms at work
[37:39] SPEAKER: during the day and they're both like three inches apart
[37:42] SPEAKER: from each other and it feels really stupid to have both.
[37:46] SPEAKER: There's the Elgato, I have an Elgato charging stand,
[37:51] SPEAKER: a MagSafe one with like a little keypad on the bottom
[37:54] SPEAKER: so that I can charge like AirPods or Kindle or whatever
[37:57] SPEAKER: on the bottom and smack my phone on the charging mount
[38:00] SPEAKER: while I'm sitting here.
[38:02] SPEAKER: I have an 18 by 24 inch cutting mat,
[38:05] SPEAKER: which I keep down for when I'm using glue
[38:08] SPEAKER: or cutting something or soldering or something like that
[38:11] SPEAKER: where I don't wanna get stuff on the desk surface.
[38:13] SPEAKER: - Sure, that's smart.
[38:16] SPEAKER: - I also, when I put this desk together, I was like,
[38:19] SPEAKER: right, this is just, I live now in a world
[38:22] SPEAKER: where I can just replace the desk surface
[38:23] SPEAKER: when it gets grody for not too much money.
[38:27] SPEAKER: I have a road, I think I have the same road mic arm
[38:29] SPEAKER: as you do.
[38:30] SPEAKER: - Yes, PSA one.
[38:32] SPEAKER: - Yeah, PSA one.
[38:33] SPEAKER: I don't, I kinda don't like it 'cause it goes up
[38:36] SPEAKER: and then comes down.
[38:37] SPEAKER: - Yeah, I've had similar issues with mine.
[38:41] SPEAKER: It's not bad, it seems like the build quality
[38:43] SPEAKER: may not be what it used to be.
[38:45] SPEAKER: - I mean, mine's 15 years old probably at this point
[38:48] SPEAKER: and I've lubed it a couple of times
[38:51] SPEAKER: and I have to tighten it up occasionally
[38:52] SPEAKER: but other than that, it's pretty fine.
[38:54] SPEAKER: - I mean, it gets the job done.
[38:56] SPEAKER: - It would be nice to have something
[38:57] SPEAKER: that just comes in below my sight line,
[38:59] SPEAKER: I think is where I'm at with that
[39:01] SPEAKER: and then pops the mic up.
[39:03] SPEAKER: - Yeah, that's kinda what I've got.
[39:04] SPEAKER: I mean, this isn't gonna play on an audio podcast
[39:05] SPEAKER: but I'll show you that that's kinda how I've got my mod.
[39:09] SPEAKER: - Did you upside down it?
[39:11] SPEAKER: - Yes, not the mic arm.
[39:13] SPEAKER: This is super not quiet.
[39:15] SPEAKER: - Oh, so you just have it super straight.
[39:17] SPEAKER: Your, yours is further away.
[39:18] SPEAKER: The problem, you have yours far enough away
[39:21] SPEAKER: that it can be straight.
[39:22] SPEAKER: Mine is not that far away unfortunately.
[39:24] SPEAKER: - I forgot to mention my mic arm.
[39:25] SPEAKER: Yes, I mount the mic arm basically as far away
[39:28] SPEAKER: as it possibly can be at the corner of the,
[39:30] SPEAKER: far corner of the desk.
[39:31] SPEAKER: - Yeah, see, I could put mine on the far corner of the desk
[39:34] SPEAKER: but if I did that, I would have to run the XLR cable
[39:38] SPEAKER: across every single data and power cable
[39:41] SPEAKER: that comes into my desktop and that seemed like a bad idea.
[39:44] SPEAKER: - So I moved the audio interface close to the mic.
[39:47] SPEAKER: - Ah, there you go.
[39:49] SPEAKER: - Short analog run, long digital run.
[39:51] SPEAKER: - Yeah, it makes sense.
[39:54] SPEAKER: Because the mixer is so big,
[39:56] SPEAKER: I don't have that option really,
[39:57] SPEAKER: is the downside of my setup.
[40:01] SPEAKER: The monitors are all on Ergotron mounts,
[40:03] SPEAKER: which are those big sturdy ones that like hospitals use.
[40:06] SPEAKER: - Oh, wow.
[40:07] SPEAKER: - They're really, really nice in that they don't wobble
[40:11] SPEAKER: and stuff like that.
[40:12] SPEAKER: Like when the desk moves, they move a little bit,
[40:14] SPEAKER: but they're pretty sturdy and they just stay in place
[40:16] SPEAKER: and there's no sag or anything like that ever.
[40:18] SPEAKER: - That's good.
[40:19] SPEAKER: These EchoGear or this EchoGear one
[40:20] SPEAKER: is also a relatively tight, like monitors that bounce
[40:23] SPEAKER: when you type or whatever would drive me completely insane.
[40:25] SPEAKER: - Yeah, they don't, I can type as hard as I want.
[40:28] SPEAKER: If I bump the table, they move.
[40:30] SPEAKER: - These Ergotrons look pretty, they look like robot arms.
[40:34] SPEAKER: They look like something that Boston Dynamics produced.
[40:36] SPEAKER: - They're pretty beefy.
[40:38] SPEAKER: Well, so the thing is with the 4K and the 1080p
[40:40] SPEAKER: on the same one, so the monitors are 4K and 1080p
[40:43] SPEAKER: and then there's also a 34 inch ultra wide
[40:45] SPEAKER: on the mounted vertically, of course, on the other one.
[40:49] SPEAKER: And in order to manage those weights,
[40:52] SPEAKER: it had to be a pretty beefy arm.
[40:54] SPEAKER: - These are not cheap monitor arms.
[40:57] SPEAKER: - I was very strategic when I was getting monitor arms
[41:01] SPEAKER: and bought them when they do a sale every year
[41:04] SPEAKER: around the end of the year.
[41:05] SPEAKER: - Okay, this triple monitor on,
[41:08] SPEAKER: granted it's just one of the ones on their site, $700.
[41:12] SPEAKER: - So I got all of these for in the 150ish range.
[41:15] SPEAKER: - That's reasonable, that's much more in line
[41:18] SPEAKER: with what most of the other brands are that I've seen.
[41:20] SPEAKER: - Yeah, like if you watch,
[41:21] SPEAKER: you can get them for the same price.
[41:23] SPEAKER: Now the problem with them is that they're designed
[41:25] SPEAKER: for like commercial and enterprise settings
[41:27] SPEAKER: and they're not, they don't necessarily have
[41:30] SPEAKER: the cable channels required for a consumer,
[41:34] SPEAKER: like I'm gonna go and tell you,
[41:37] SPEAKER: I'm gonna pull all of the USB cables out of my monitors,
[41:39] SPEAKER: 'cause I don't ever use the USB hubs
[41:41] SPEAKER: that are built into the monitors.
[41:42] SPEAKER: And it just clogs up the cable channels
[41:45] SPEAKER: so that they're like, it's too tight.
[41:48] SPEAKER: - Yeah, I don't even use the USB hubs in my monitors.
[41:51] SPEAKER: What do people, what's the use case for those these days?
[41:53] SPEAKER: Like I could maybe see previously
[41:56] SPEAKER: you might've plugged your mouse and keyboard into them
[41:57] SPEAKER: or something along those lines.
[41:59] SPEAKER: But like, first of all, they're not even exposed enough
[42:01] SPEAKER: to be convenient to use.
[42:03] SPEAKER: And second of all, I don't know what I would put in there
[42:04] SPEAKER: even if they were.
[42:05] SPEAKER: - So I used to plug my webcam into them,
[42:07] SPEAKER: but then I got these USB-C, like 3.1 webcams
[42:11] SPEAKER: that like the monitor hub is not,
[42:15] SPEAKER: you don't wanna plug them into a hub basically.
[42:18] SPEAKER: The other thing is like when I was doing food stuff,
[42:25] SPEAKER: I had an eye tracker plugged into one of them
[42:26] SPEAKER: 'cause that was useful in minimized cables.
[42:29] SPEAKER: The other thing that I did have on the ultra wide
[42:32] SPEAKER: for a long time that I really loved
[42:33] SPEAKER: and I probably should bring back
[42:35] SPEAKER: was like just a cheap USB LED light
[42:38] SPEAKER: that was like a strip light
[42:39] SPEAKER: that you glued up on the bottom edge of the monitor
[42:41] SPEAKER: and you could toggle it on and off
[42:43] SPEAKER: and it just pulled USB power.
[42:44] SPEAKER: So you could like downlight the back of your desk,
[42:47] SPEAKER: which was really convenient.
[42:49] SPEAKER: - Seems cool.
[42:50] SPEAKER: I've got an RGB kind of home kit,
[42:54] SPEAKER: you know, home automation addressable RGB strip
[42:57] SPEAKER: on the back of my desk pointed at the wall.
[43:00] SPEAKER: So I guess I get some kind of nice like backlighting
[43:04] SPEAKER: under, not under the monitors,
[43:05] SPEAKER: but against the wall behind everything.
[43:08] SPEAKER: - That's fancy.
[43:09] SPEAKER: - Yeah, it's nice.
[43:10] SPEAKER: - Okay, so I have that,
[43:12] SPEAKER: I have the cable manager on those Ergotron arms,
[43:15] SPEAKER: like I said, not the best.
[43:16] SPEAKER: It doesn't let you hide stuff all the way,
[43:18] SPEAKER: it just lets you get it kind of close.
[43:20] SPEAKER: I have too many key lights,
[43:21] SPEAKER: the Elgato ones on stands clamped to the edge of the table
[43:23] SPEAKER: just to front light me
[43:25] SPEAKER: when I'm doing something that needs good lights.
[43:28] SPEAKER: I use a drop control keyboard these days
[43:30] SPEAKER: with a wrist rest.
[43:31] SPEAKER: I've been working on switching to the keyboardio model 100,
[43:35] SPEAKER: but it's hard to take the time to be bad at typing
[43:39] SPEAKER: to learn how to use the new keyboard, it turns out.
[43:42] SPEAKER: - It's kind of reminds me of getting used to VIM.
[43:45] SPEAKER: It's like disrupting your typing workflow
[43:48] SPEAKER: is pretty difficult.
[43:49] SPEAKER: - Yeah, it turns out typing,
[43:51] SPEAKER: like me not having to think about typing
[43:52] SPEAKER: is really important to the work that I do all the time.
[43:57] SPEAKER: I have a switch for, so I have a USB switch
[44:00] SPEAKER: that's not a KVM, it's just like a dumb USB switch
[44:03] SPEAKER: that just physically switches the connection
[44:06] SPEAKER: for the keyboard and mouse between the two PCs
[44:09] SPEAKER: for those rare moments when input director fails
[44:12] SPEAKER: and I can't get the mouse and keyboard
[44:14] SPEAKER: over to the second PC.
[44:17] SPEAKER: There's a Google, so that switch I'm actually gonna move
[44:20] SPEAKER: to the bottom of the desk.
[44:21] SPEAKER: So I'm gonna tape it up underneath
[44:22] SPEAKER: and have like a secret press button for when I need to,
[44:26] SPEAKER: the rare times I need to use it
[44:27] SPEAKER: 'cause I use it like once a month probably.
[44:30] SPEAKER: I have a Google Nest Hub Mini that's like,
[44:32] SPEAKER: it's essentially a digital photo frame
[44:33] SPEAKER: that I can control music on the speaker in my office with.
[44:39] SPEAKER: And then my mister and the consoles kind of come in and out
[44:44] SPEAKER: on the back of the desk.
[44:47] SPEAKER: - Sure.
[44:49] SPEAKER: - So under, I have a 12-port power strip that Anker makes.
[44:53] SPEAKER: I have a cheap AmazonBasics like 10-port USB 3.1 hub
[44:59] SPEAKER: that also provides a fair amount of USB power
[45:01] SPEAKER: for things like those Anker key lights are USB power now.
[45:06] SPEAKER: - Oh, wow. - So the mini ones.
[45:07] SPEAKER: So they just plug into that.
[45:13] SPEAKER: I think I'm gonna switch my cable trays
[45:15] SPEAKER: with the ones you have 'cause they look better.
[45:17] SPEAKER: But I have these, they're like baskets
[45:20] SPEAKER: and they open only on one side.
[45:21] SPEAKER: So it's like a wire, it's like a U-shape basically.
[45:24] SPEAKER: And you screw one end of the U into the wood
[45:26] SPEAKER: and then the other end of the U is the bottom.
[45:28] SPEAKER: And it means that you can either get to them
[45:30] SPEAKER: from the person side of the desk
[45:33] SPEAKER: or the backside of the desk, but not both.
[45:35] SPEAKER: - Oh, okay.
[45:36] SPEAKER: - Which is a little challenging.
[45:37] SPEAKER: - Yeah, these signums are open,
[45:39] SPEAKER: completely open on both sides.
[45:40] SPEAKER: - Yeah, that seems really nice.
[45:44] SPEAKER: - My desk has a back panel though,
[45:45] SPEAKER: so I can't get to the closer open side.
[45:48] SPEAKER: But theoretically, if your desk was open underneath,
[45:51] SPEAKER: that would be very convenient.
[45:53] SPEAKER: - Yeah, so my desk is open underneath,
[45:54] SPEAKER: which means that you can see all the crimes
[45:56] SPEAKER: when you're walking on the backside of the desk.
[45:59] SPEAKER: But also I just decided I don't care about that.
[46:01] SPEAKER: - Yeah, you just gotta get over that.
[46:03] SPEAKER: I mean, the upside of having that vertical back panel
[46:05] SPEAKER: on the desk is that's what the router and switch
[46:07] SPEAKER: and power strips are mounted to.
[46:09] SPEAKER: I would not have that if I didn't have a button,
[46:11] SPEAKER: but the downside is I can't get to the cable rack
[46:12] SPEAKER: very conveniently at all.
[46:13] SPEAKER: - I wondered where you got the space.
[46:14] SPEAKER: Well, the nice thing about the sit-stand
[46:16] SPEAKER: is that when I wanna work under there,
[46:17] SPEAKER: I just raise it up enough that I can sit up straight.
[46:20] SPEAKER: And I don't have to lay on my back
[46:22] SPEAKER: and reach my arms up the whole time.
[46:24] SPEAKER: I also use a lot of short extension cords.
[46:27] SPEAKER: So like those little, they're like three inch to six inch.
[46:30] SPEAKER: - Yes, I also have a bundle of those in the drawer.
[46:32] SPEAKER: - Yeah, and those are really good
[46:34] SPEAKER: for not having a wall wart hanging off
[46:37] SPEAKER: of the power strip that's under there
[46:38] SPEAKER: 'cause they tend to fall out in my experience.
[46:41] SPEAKER: - Also some of them are just big.
[46:44] SPEAKER: Some of them take up too much space
[46:45] SPEAKER: and block one or both of the outlets next to them.
[46:48] SPEAKER: - Yeah, and it's worth saying like,
[46:51] SPEAKER: I think I screwed the power strip in,
[46:53] SPEAKER: but I believe that the USB hub,
[46:57] SPEAKER: the USB switcher is under there too,
[46:58] SPEAKER: the box that does the actual switching.
[47:01] SPEAKER: And then there's a couple other small things.
[47:03] SPEAKER: I just double-sided tape.
[47:04] SPEAKER: I double-sided foam taped them up under there
[47:07] SPEAKER: and like no regrets.
[47:11] SPEAKER: - Sounds good.
[47:12] SPEAKER: - I can scrape it off with a putty knife if I need to.
[47:14] SPEAKER: - Sure.
[47:15] SPEAKER: - And then the other, so then the other,
[47:18] SPEAKER: the two other things.
[47:18] SPEAKER: Well, there's a headphone hook
[47:20] SPEAKER: that has both my like production headphones
[47:23] SPEAKER: and my gaming headphones.
[47:26] SPEAKER: I have the vertebra cable channel thing,
[47:29] SPEAKER: which is designed for sit-stand desks.
[47:31] SPEAKER: So it's like a series of joints
[47:33] SPEAKER: and there's four cable channels
[47:35] SPEAKER: and then you put the cables in.
[47:36] SPEAKER: I don't love that thing.
[47:37] SPEAKER: So if people have better suggestions
[47:38] SPEAKER: for how to manage the cables that need to go up and down
[47:43] SPEAKER: when the desk goes up and down,
[47:44] SPEAKER: I would love to hear them.
[47:46] SPEAKER: It's fine, but it kind of flaps around
[47:49] SPEAKER: and it isn't as movie, it isn't as easy moving
[47:53] SPEAKER: as I was hoping given that there's like three monitor cables
[47:56] SPEAKER: and a couple of power cables and all the USB cables
[47:59] SPEAKER: that go from the desktop to the other computer
[48:02] SPEAKER: and stuff like that.
[48:05] SPEAKER: And then the last thing is I got those cable locks
[48:09] SPEAKER: on the edges.
[48:11] SPEAKER: So those let me hold the case.
[48:13] SPEAKER: So I have a bunch of things that do have cables
[48:15] SPEAKER: but I have them all running straight back
[48:18] SPEAKER: and the cable locks on the edges
[48:20] SPEAKER: let me anchor the backside of the desk,
[48:23] SPEAKER: run of the cable and like lock it in place
[48:25] SPEAKER: so there's no slack and there's no wiggle
[48:28] SPEAKER: and then the rest of it just goes in the tray up underneath.
[48:32] SPEAKER: But then the cable locks, if you don't know,
[48:33] SPEAKER: are these little, they're like,
[48:35] SPEAKER: it's like a plastic thing with like,
[48:36] SPEAKER: they look like little mushrooms
[48:38] SPEAKER: that are all close enough together.
[48:39] SPEAKER: They'll hold, they bend and you can snap the cables in place
[48:42] SPEAKER: and then, yeah, they go from there.
[48:46] SPEAKER: - C-A-B-L-O-X if you want to.
[48:49] SPEAKER: - Yes, yeah, I just got a variety pack
[48:53] SPEAKER: and kind of got hooked on them.
[48:56] SPEAKER: But like my, so the things that are working really well
[49:00] SPEAKER: are the lights and the monitor stand.
[49:03] SPEAKER: The cameras are kind of always a pain in the ass
[49:05] SPEAKER: 'cause they always require adjustment.
[49:08] SPEAKER: Like either I change how I sit in the chair
[49:11] SPEAKER: or the lights change or like it gets tilted or whatever.
[49:15] SPEAKER: I don't know what causes that,
[49:17] SPEAKER: but I think I need to build a custom solution for that.
[49:20] SPEAKER: - So that's one of the nice things
[49:21] SPEAKER: about having my camera mounted to that key light
[49:23] SPEAKER: is they just always point in the same direction.
[49:26] SPEAKER: So I got a, so the camera's on that friction arm,
[49:31] SPEAKER: like I said, and once you get that thing level,
[49:35] SPEAKER: you kind of don't ever want to touch it again
[49:36] SPEAKER: 'cause getting it level again is a kind of a nightmare.
[49:39] SPEAKER: But I bought a little quick release mount
[49:41] SPEAKER: to go between the friction arm and the camera.
[49:43] SPEAKER: So you just snap a little lever
[49:45] SPEAKER: and the camera itself comes right off.
[49:47] SPEAKER: - Oh, that's nice.
[49:48] SPEAKER: So then it's not always on the arm
[49:49] SPEAKER: when you're not using it?
[49:50] SPEAKER: - Not that, well, I leave it on there when I'm not using it,
[49:53] SPEAKER: but if you ever, not that I rarely ever use this camera
[49:56] SPEAKER: as a camera and not for streaming,
[49:58] SPEAKER: but if you ever do need to take it off,
[49:59] SPEAKER: you can, it'll pop right off the mount
[50:01] SPEAKER: so you don't have to mess with your arm.
[50:02] SPEAKER: - Oh, 'cause you use a DSLR still.
[50:04] SPEAKER: - Yeah, it's mirrorless, yeah.
[50:05] SPEAKER: - Mirrorless, okay.
[50:07] SPEAKER: - And the other nice thing is that
[50:09] SPEAKER: that quick release mount has levels in it, so.
[50:12] SPEAKER: - Oh, that's nice.
[50:13] SPEAKER: - You can get your camera quite level
[50:14] SPEAKER: without having to like look at the output
[50:17] SPEAKER: if you do need to level it.
[50:18] SPEAKER: - Yeah, that's one of the things that's frustrating to me
[50:20] SPEAKER: about my current setup is that when I'm leveling,
[50:24] SPEAKER: I have to be behind the desk
[50:25] SPEAKER: where I can't see the thing that's in the front of the desk.
[50:27] SPEAKER: So I like have to get my daughter or my wife
[50:29] SPEAKER: or somebody sitting here and be like,
[50:30] SPEAKER: "Hey, is that, look at the picture frames, is it level?"
[50:33] SPEAKER: - That's exactly.
[50:34] SPEAKER: So that was the thing I left out when I was saying before,
[50:36] SPEAKER: if you, when you loosen the friction arm, it just collapses.
[50:39] SPEAKER: Like all the tension goes out of it
[50:40] SPEAKER: and your expensive camera just fucking slams into the desk
[50:44] SPEAKER: if you're not holding it up.
[50:45] SPEAKER: So that's what I mean is you have to be holding that thing
[50:47] SPEAKER: all the time while it's loosened.
[50:49] SPEAKER: - Yeah.
[50:49] SPEAKER: - So you're basically like craning your arm over the monitor
[50:52] SPEAKER: to try to hold the camera in place
[50:53] SPEAKER: while you're like trying to peer down at the monitor
[50:55] SPEAKER: to see if you're level or not.
[50:57] SPEAKER: So yeah, getting those levels was key.
[50:59] SPEAKER: - Yeah, the other stuff is like the Elgato camera.
[51:02] SPEAKER: So I use those face cams.
[51:04] SPEAKER: This sounds like an Elgato shill podcast,
[51:06] SPEAKER: but they don't pay us or anything
[51:07] SPEAKER: or they don't give us hardware.
[51:10] SPEAKER: Those face cams are pretty good webcams,
[51:12] SPEAKER: especially the 1080p ones for the money.
[51:15] SPEAKER: Like it looks indistinguishable.
[51:17] SPEAKER: Like they have good sensors
[51:19] SPEAKER: and they work in all sorts of light conditions
[51:21] SPEAKER: and I've been quite happy with them.
[51:22] SPEAKER: Except like once every month or every other month,
[51:27] SPEAKER: you have to unplug and replug it.
[51:29] SPEAKER: And that is kind of an annoyance.
[51:32] SPEAKER: - So those are just straight USB?
[51:34] SPEAKER: - They're straight USB, yeah.
[51:35] SPEAKER: Well, they're USB-C, they have to be 3.0 or 3.0.
[51:39] SPEAKER: They have a specific USB requirement to get the full,
[51:43] SPEAKER: 'cause they send higher,
[51:45] SPEAKER: they don't send compressed back to the computer.
[51:47] SPEAKER: So it's not like, they're a little weird.
[51:51] SPEAKER: Also, I think that,
[51:52] SPEAKER: I wanna say they have Linux support problems,
[51:53] SPEAKER: but I can't remember.
[51:55] SPEAKER: I think they're host-based, so.
[51:57] SPEAKER: - Yeah, Jonathan on the Debian FOSS pod
[51:59] SPEAKER: talked about modern webcams being a real pain
[52:02] SPEAKER: to support in Linux, actually.
[52:03] SPEAKER: - I did not realize that there was a webcam problem
[52:06] SPEAKER: in Linux these days, yeah.
[52:07] SPEAKER: - 'Cause things have gotten very closed
[52:09] SPEAKER: and proprietary there.
[52:10] SPEAKER: Anyway, which stream,
[52:12] SPEAKER: do you just have normal, the Stream Deck regular?
[52:15] SPEAKER: - So I have an XL hooked up to the Stream PC,
[52:18] SPEAKER: which has all the like OBS and audio.
[52:21] SPEAKER: Like I have buttons for all of the audio inputs,
[52:23] SPEAKER: so I can turn them on and off.
[52:25] SPEAKER: I got, when they announced that one with the knobs,
[52:28] SPEAKER: I bought the one with the knobs for the main PC,
[52:33] SPEAKER: thinking it would be nice to have a way to control volumes.
[52:36] SPEAKER: And then it turns out nobody's written the software
[52:38] SPEAKER: to let me interface with my mixer yet.
[52:40] SPEAKER: So either I have to set up like a,
[52:46] SPEAKER: because the mixer is hooked up to the Stream PC,
[52:49] SPEAKER: I can't connect to it over USB.
[52:51] SPEAKER: And it's a little fraught.
[52:55] SPEAKER: As I'm saying this now,
[52:56] SPEAKER: I'm thinking maybe I should switch the mixer
[52:58] SPEAKER: to hook up to the main PC
[53:00] SPEAKER: and then just pipe the signal
[53:06] SPEAKER: from the mixer into the DAC on the Stream PC.
[53:11] SPEAKER: - Over what?
[53:12] SPEAKER: - Over an analog, like it's just an analog out
[53:16] SPEAKER: from the mixer into the DAC on the main PC,
[53:19] SPEAKER: which is what I do now.
[53:20] SPEAKER: - That would work.
[53:21] SPEAKER: - Yeah, I don't know, we'll see.
[53:23] SPEAKER: The whole thing seems fraught.
[53:25] SPEAKER: - Yeah. - More cables.
[53:26] SPEAKER: - Yes, for sure, speaking of more cables.
[53:28] SPEAKER: So this is another place where length comes in
[53:30] SPEAKER: on those cables that I'm running behind.
[53:33] SPEAKER: So I've got a Stream Deck XL
[53:34] SPEAKER: that I've just been sitting in a box for some time
[53:37] SPEAKER: that I swear I'm gonna start using soon.
[53:39] SPEAKER: - It's surprisingly convenient.
[53:41] SPEAKER: - Seems way too useful not to be.
[53:43] SPEAKER: There are so many things.
[53:45] SPEAKER: Like when I think about it, it's less like OBS functions,
[53:47] SPEAKER: although some of that would be nice,
[53:48] SPEAKER: but it's more like putting all my monitor inputs
[53:51] SPEAKER: on Stream Deck buttons.
[53:52] SPEAKER: - Yep.
[53:53] SPEAKER: - So I just switch between monitor inputs
[53:54] SPEAKER: on that control surface.
[53:55] SPEAKER: - You mean you want to control your monitor?
[53:59] SPEAKER: Yeah, okay.
[54:00] SPEAKER: - Like I keep thinking of and then forgetting other stuff
[54:03] SPEAKER: I would put on a Stream Deck,
[54:04] SPEAKER: but there's a ton of stuff.
[54:05] SPEAKER: Well, like audio inputs and outputs,
[54:08] SPEAKER: like active recording and output device in Windows
[54:12] SPEAKER: and stuff like that.
[54:13] SPEAKER: - I've been doing, I have like Photoshop and Premiere
[54:17] SPEAKER: and like, yeah, there are a bunch of like productivity
[54:24] SPEAKER: shortcut implementations that you hook in
[54:27] SPEAKER: that will let you control, like there's one for resolve.
[54:33] SPEAKER: Yeah, anyway.
[54:34] SPEAKER: - Okay, so trying to stick to cord zero
[54:37] SPEAKER: and use something like a Stream Deck can be challenging.
[54:40] SPEAKER: So that's the other place where having extra long cords
[54:43] SPEAKER: is nice because in a lot of cases,
[54:44] SPEAKER: I'll kind of hook the top of a cord
[54:46] SPEAKER: that I don't, something I don't plug in all the time,
[54:48] SPEAKER: like my camera, for example, the power for the camera
[54:51] SPEAKER: and for the key light are separate.
[54:54] SPEAKER: - So you just have a dangler?
[54:55] SPEAKER: - So they kind of, yeah, but like,
[54:57] SPEAKER: because of the way things are, you can't see,
[54:59] SPEAKER: you can't really see the loop hanging down,
[55:01] SPEAKER: but there's enough slack that whenever I,
[55:03] SPEAKER: and the Stream Deck is another one
[55:04] SPEAKER: where I would probably just have it sitting
[55:06] SPEAKER: at the back of the desk at all times
[55:08] SPEAKER: with enough slack on that cord down through the cable rack,
[55:11] SPEAKER: but I can pull it forward right up to where I need to use it
[55:14] SPEAKER: and then just kind of pull it in and out
[55:15] SPEAKER: and have the cable just sort of slide through the rack
[55:18] SPEAKER: so that it kind of, you know, still stays tidy
[55:20] SPEAKER: and doesn't, you know, pile up on the floor
[55:23] SPEAKER: that has enough slack to be kind of movable.
[55:25] SPEAKER: - Well, that's what I use the cable locks for, right?
[55:27] SPEAKER: - Okay, oh, do they actually like thread through there?
[55:31] SPEAKER: Like can they move through there?
[55:32] SPEAKER: I thought they were being like gripped tightly in between.
[55:35] SPEAKER: - No, they move, so like, well, you can do it either way.
[55:40] SPEAKER: So if you just put them straight through,
[55:42] SPEAKER: then they'll just fall down and you'll,
[55:45] SPEAKER: just the stump will poke up
[55:46] SPEAKER: and you can pull up the slack, right?
[55:48] SPEAKER: But if you do like a little S through there,
[55:51] SPEAKER: then it basically locks them in place and the slack will,
[55:54] SPEAKER: so like that's how I maintain the straight lines
[55:56] SPEAKER: from the Stream Deck.
[55:57] SPEAKER: The other nice thing about the Stream Deck XL,
[55:59] SPEAKER: at least the one I have, is it has a USB-C port on the back.
[56:02] SPEAKER: So you can use your own cable for it if you want.
[56:04] SPEAKER: So if you want to get one that matches your desk color
[56:06] SPEAKER: or something like that, you can do that.
[56:10] SPEAKER: But yeah, I think, I don't know, if I'm looking at this,
[56:15] SPEAKER: if I'm looking at what I've done here,
[56:16] SPEAKER: I think the next thing for me, I'm probably going to get
[56:18] SPEAKER: a USB hub and see how much stuff I can plug in to a USB hub
[56:23] SPEAKER: so that I only run one USB cable into a Stream PC.
[56:27] SPEAKER: - Interesting, so that's the exact opposite direction
[56:29] SPEAKER: that I feel I have gone in recent years
[56:31] SPEAKER: where I'm trying to run everything
[56:33] SPEAKER: into its own discrete USB port.
[56:35] SPEAKER: - Yeah, I mean, it's one of the, it's like a,
[56:38] SPEAKER: it's a trade-off, right?
[56:40] SPEAKER: 'Cause I feel like I definitely get less reliable.
[56:44] SPEAKER: - I get occasional weirdness when you have too much stuff
[56:46] SPEAKER: plugged into one USB root port.
[56:47] SPEAKER: - Yeah, that's what I'm worried about.
[56:49] SPEAKER: - But also like the Stream PC only has mouse, keyboard,
[56:52] SPEAKER: audio interface, and camera, I think,
[56:54] SPEAKER: is all that's plugged into it.
[56:55] SPEAKER: - Yeah, that's not that big a deal.
[56:58] SPEAKER: As I've been motherboard shopping,
[57:00] SPEAKER: number of USB ports has been a high priority.
[57:02] SPEAKER: - Get a lot of ports.
[57:03] SPEAKER: Well, also how they're wired in is important.
[57:06] SPEAKER: - Yeah, that information is always
[57:08] SPEAKER: like extremely well-documented, isn't it?
[57:10] SPEAKER: - Nope, never, absolutely never.
[57:14] SPEAKER: The, yeah, so I would, I would look at the cable locks.
[57:17] SPEAKER: Like I think you'll like them a lot
[57:19] SPEAKER: and they're not expensive.
[57:20] SPEAKER: It's like 10 bucks for a combo pack or something.
[57:23] SPEAKER: - So like my, okay, from the outside,
[57:25] SPEAKER: my desk looks incredibly tidy.
[57:27] SPEAKER: That wiring job in the back is,
[57:29] SPEAKER: it's, I'm not gonna say it's a huge mess of spaghetti,
[57:31] SPEAKER: but it's like, it's the same thing you said last week
[57:34] SPEAKER: about PCs, right?
[57:35] SPEAKER: Like the more, the more work you do to tidy things up
[57:39] SPEAKER: and make them like compact and integrated
[57:41] SPEAKER: and like out of the way, like the bigger a pain in the ass
[57:44] SPEAKER: it's gonna be next time you have to get in there
[57:45] SPEAKER: and do anything with it.
[57:46] SPEAKER: So like pulling this desk out
[57:49] SPEAKER: and getting through these cables
[57:50] SPEAKER: and like running something new through there
[57:51] SPEAKER: is an absolute ordeal, but when I'm done,
[57:55] SPEAKER: everything is nice and out of the way
[57:56] SPEAKER: and I can't see it and it's great.
[57:57] SPEAKER: - So this is the thing, this is the part that I like.
[58:00] SPEAKER: So about a year ago, I rotated my desk.
[58:02] SPEAKER: When I came back from Palm Desert, actually last summer,
[58:04] SPEAKER: I rotated my desk 'cause my desk had been up against the wall
[58:07] SPEAKER: for 10 years and I was like,
[58:09] SPEAKER: I want to have a wall behind me in my shot.
[58:11] SPEAKER: So I can have like, 'cause I have a bunch of cool art
[58:13] SPEAKER: and I have pictures and I have the game frame
[58:14] SPEAKER: and all this stuff up there.
[58:16] SPEAKER: I rotated the desk 90 degrees.
[58:17] SPEAKER: So now it floats in the middle of the room
[58:19] SPEAKER: and it's sticking out from the wall, like a L.
[58:23] SPEAKER: And it means that I can get to the back of it
[58:25] SPEAKER: without having to lay on the ground
[58:27] SPEAKER: or pull the desk out or anything like that.
[58:29] SPEAKER: And like the only downside is I have to walk by the back
[58:32] SPEAKER: of the monitors and see all the arms and all that shit
[58:34] SPEAKER: every time I come in.
[58:36] SPEAKER: But other than that, it's great.
[58:38] SPEAKER: Like, 'cause it makes it really easy to fix stuff
[58:40] SPEAKER: and it means that when I want to change something,
[58:42] SPEAKER: it's not easier to just let it be, to just half-ass it.
[58:49] SPEAKER: It's easier to fix it and clean it up.
[58:52] SPEAKER: And then I need to like re-put the cable back in
[58:55] SPEAKER: whatever was holding it in place
[58:56] SPEAKER: or else I'll snag it on the way by
[58:57] SPEAKER: and yank something loose and it'd be a disaster, so.
[59:00] SPEAKER: - Now for you to change something,
[59:02] SPEAKER: all you have to do is walk around the desk.
[59:04] SPEAKER: - Yeah, I lift the desk up a little bit
[59:05] SPEAKER: and I walk around it and I lay down.
[59:07] SPEAKER: I have got a good foot rest so I can use that as a pillow
[59:09] SPEAKER: when I'm down there.
[59:10] SPEAKER: - Wow. - Yeah.
[59:11] SPEAKER: - Whereas in my case, like, hey, you know how I've been
[59:14] SPEAKER: running this laptop off of wifi for a while?
[59:16] SPEAKER: - Yeah.
[59:17] SPEAKER: - That's mostly because of what an absolute nightmare
[59:19] SPEAKER: it would be to run more networking behind this desk.
[59:22] SPEAKER: - Well, so the one place I do have a problem,
[59:25] SPEAKER: a bad problem actually, is coming out of the vertebra.
[59:29] SPEAKER: Also, you should get wired to that laptop.
[59:32] SPEAKER: - I know, I know.
[59:33] SPEAKER: That's the thing, I would have to get back there
[59:36] SPEAKER: and put another switch in, put them out of ports
[59:38] SPEAKER: and it's gonna be so much work.
[59:39] SPEAKER: - Well, so this is the place I wonder if I could use
[59:43] SPEAKER: a docking station on a desktop
[59:45] SPEAKER: to solve some of these problems.
[59:47] SPEAKER: 'Cause a docking station with the right USB-C cable
[59:50] SPEAKER: should give me actual USB root hubs at the docking station.
[59:56] SPEAKER: And let me plug in the cameras to the desk
[1:00:03] SPEAKER: rather than have to run them all the way back to the PCs.
[1:00:06] SPEAKER: 'Cause the place that I have a nightmare is there's a,
[1:00:08] SPEAKER: to the right of the desk along the wall,
[1:00:11] SPEAKER: there's all the cables that run back to the streaming PC,
[1:00:15] SPEAKER: which is like five feet behind, three feet behind me.
[1:00:17] SPEAKER: It's five feet from the end of the cable vertebra.
[1:00:20] SPEAKER: And that is a, it's a nightmare.
[1:00:24] SPEAKER: It's really dusty and gross.
[1:00:26] SPEAKER: I can't get in there to clean it easily.
[1:00:28] SPEAKER: Like I need to, probably what I should do
[1:00:29] SPEAKER: is just build a box that lives on top of that
[1:00:33] SPEAKER: and has a little U on one end to,
[1:00:35] SPEAKER: maybe it's box building time.
[1:00:37] SPEAKER: I don't know, I don't know what the solve for that is.
[1:00:38] SPEAKER: I wish there was something I could just buy honestly,
[1:00:40] SPEAKER: 'cause I wouldn't have to fool with it, but.
[1:00:42] SPEAKER: - I haven't looked at like USB-C docking stations
[1:00:44] SPEAKER: and kind of all-in-one hubs in a while, a couple of years,
[1:00:47] SPEAKER: but even then they were getting pretty damn elaborate.
[1:00:49] SPEAKER: I have to imagine those are like pretty great
[1:00:51] SPEAKER: at this point, right?
[1:00:52] SPEAKER: In terms of power delivery, ethernet, maybe even display,
[1:00:55] SPEAKER: like let alone a bunch of USB ports.
[1:00:57] SPEAKER: Like it seems like the kind of all-in-one one thing
[1:01:00] SPEAKER: that you plug everything into market
[1:01:02] SPEAKER: has gotten pretty good.
[1:01:03] SPEAKER: - Yeah, I mean, I would hope so, I don't know.
[1:01:06] SPEAKER: I'd be curious what people think about that.
[1:01:08] SPEAKER: That's a place where I don't know what the best,
[1:01:10] SPEAKER: what the right answer is really.
[1:01:12] SPEAKER: - Yeah, desks.
[1:01:14] SPEAKER: - Yeah, desks.
[1:01:15] SPEAKER: What's on our desks?
[1:01:16] SPEAKER: - They're ever-revolving, it turns out.
[1:01:19] SPEAKER: - So the things that I learned that I didn't know about
[1:01:22] SPEAKER: from watching cable management videos are that,
[1:01:25] SPEAKER: especially if you do custom audio stuff,
[1:01:26] SPEAKER: there are a bunch of places.
[1:01:28] SPEAKER: Well, A, it's not too hard to make like custom XLR cables.
[1:01:31] SPEAKER: If you want one with like a weird right angle
[1:01:33] SPEAKER: or something like that, you can buy the ends,
[1:01:35] SPEAKER: buy the raw cables.
[1:01:37] SPEAKER: And if you're halfway decent at soldering,
[1:01:38] SPEAKER: they're pretty easy to put together.
[1:01:39] SPEAKER: We used to make a bunch of XLR cables
[1:01:41] SPEAKER: in the Whiskey Media days.
[1:01:44] SPEAKER: But you can also get customers made by people
[1:01:46] SPEAKER: who are actually good at it instead of talented dilettantes
[1:01:50] SPEAKER: like we would probably be if we don't do that every day.
[1:01:54] SPEAKER: The reusable zip ties are an absolute game changer.
[1:02:00] SPEAKER: I can't overemphasize that enough.
[1:02:02] SPEAKER: The other thing is I was thinking about
[1:02:04] SPEAKER: putting a mouse mat on my desk
[1:02:05] SPEAKER: and with this light speed pad, that's a little challenging
[1:02:07] SPEAKER: 'cause then there's a hump.
[1:02:09] SPEAKER: And I think C music on the discord
[1:02:11] SPEAKER: pointed out a few months ago
[1:02:13] SPEAKER: that you can just buy a piece of cork
[1:02:15] SPEAKER: that's the same thickness as the light speed pad
[1:02:19] SPEAKER: and place that, like make a cutout
[1:02:22] SPEAKER: for the light speed pad in the cork,
[1:02:24] SPEAKER: set the light speed pad in the cork
[1:02:25] SPEAKER: and then put the mouse mat on top of that.
[1:02:27] SPEAKER: - Oh, will it charge through a mouse mat?
[1:02:30] SPEAKER: - Yeah, it charges through the mouse mat.
[1:02:31] SPEAKER: Like it charges through the,
[1:02:32] SPEAKER: like it'll charge through a pad
[1:02:33] SPEAKER: as long as it's not too, too thick.
[1:02:35] SPEAKER: - Ooh, that's not a bad idea.
[1:02:36] SPEAKER: - And then I get the benefit of the,
[1:02:38] SPEAKER: 'cause like the nice thing about the mouse mat
[1:02:39] SPEAKER: is it makes the keyboard a little quieter too.
[1:02:41] SPEAKER: - Sure.
[1:02:44] SPEAKER: Oh, I didn't even talk about keyboards.
[1:02:45] SPEAKER: I'm gonna just throw this out.
[1:02:46] SPEAKER: - Oh yeah, 'cause you're thinking about
[1:02:47] SPEAKER: going mechanical finally.
[1:02:48] SPEAKER: - Probably, I mean, this thing's fine.
[1:02:50] SPEAKER: It's working fine.
[1:02:51] SPEAKER: I don't need a new keyboard,
[1:02:52] SPEAKER: but it would be nice to type on something that felt better.
[1:02:54] SPEAKER: - Yeah.
[1:02:55] SPEAKER: - Here's a question for you in the audience.
[1:02:58] SPEAKER: - Yeah.
[1:02:59] SPEAKER: - Are there Bluetooth mechanical keyboards
[1:03:02] SPEAKER: with a fingerprint sensor in them?
[1:03:04] SPEAKER: I have not been able to find any.
[1:03:05] SPEAKER: - I think a finger,
[1:03:06] SPEAKER: so I also have been looking at fingerprint sensors lately
[1:03:09] SPEAKER: for Windows Hello purposes.
[1:03:11] SPEAKER: - Yes.
[1:03:12] SPEAKER: Also, I don't want an external,
[1:03:13] SPEAKER: I don't want a separate, freestanding fingerprint sensor.
[1:03:15] SPEAKER: - So I'm gonna tell you what I'm doing
[1:03:16] SPEAKER: with my fingerprint sensor when it gets here.
[1:03:19] SPEAKER: I'm gonna double stick tape it up under the desk.
[1:03:21] SPEAKER: - I was about to, like that hit me as you said,
[1:03:24] SPEAKER: I'm gonna tell you what I'm gonna do with it.
[1:03:26] SPEAKER: I was like, oh, right.
[1:03:27] SPEAKER: I mean.
[1:03:28] SPEAKER: - You have a whole surface under there.
[1:03:29] SPEAKER: - You'd have to crane your, you know,
[1:03:30] SPEAKER: to make sure you can reach it
[1:03:32] SPEAKER: and rotate your hand properly, but that's probably fine.
[1:03:34] SPEAKER: - You just put, well, so all of the stuff
[1:03:36] SPEAKER: that's loose on my desk is stuck down with nanotape.
[1:03:38] SPEAKER: So like the mouse pad, the light speed charger,
[1:03:42] SPEAKER: the wrist rests, the keyboard,
[1:03:44] SPEAKER: all that stuff is nanotaped to the surface.
[1:03:47] SPEAKER: So, you know, just put it, so like you can use,
[1:03:51] SPEAKER: so my thought is I'm gonna use the mouse wrist rest
[1:03:56] SPEAKER: as the reference point and just tape it up underneath
[1:04:00] SPEAKER: where my finger goes when I put my thumb on the mouse pad
[1:04:04] SPEAKER: and the mouse wrist rest in a specific spot,
[1:04:06] SPEAKER: since that doesn't move and then go from there.
[1:04:08] SPEAKER: I'll let you know how that goes.
[1:04:09] SPEAKER: - Ooh, that sounds good.
[1:04:10] SPEAKER: I assume that like standalone fingerprint sensors
[1:04:13] SPEAKER: are a dime a dozen these days.
[1:04:15] SPEAKER: - They're like, it's, they're surprisingly expensive still.
[1:04:18] SPEAKER: They're like, it's like 50 bucks for a good one.
[1:04:21] SPEAKER: - Well, that's not terrible.
[1:04:22] SPEAKER: - I mean, it's, how many times can I type a six letter,
[1:04:26] SPEAKER: six number passcode in for 50 bucks?
[1:04:28] SPEAKER: It's a lot, but also I miss having the thing,
[1:04:31] SPEAKER: like I used to have a camera webcam that saw my face
[1:04:34] SPEAKER: and was like, hey man, I know you.
[1:04:35] SPEAKER: And then I'll unlock my computer for me.
[1:04:37] SPEAKER: And that also was really nice.
[1:04:38] SPEAKER: So I don't know, it's complicated.
[1:04:42] SPEAKER: - I get it.
[1:04:42] SPEAKER: - Is the answer.
[1:04:43] SPEAKER: - Yeah.
[1:04:44] SPEAKER: - I haven't ordered anything yet,
[1:04:45] SPEAKER: but I have looked at it and thought about it a lot, so.
[1:04:47] SPEAKER: - Actually, you know, for front of the matter,
[1:04:51] SPEAKER: how should I even put this, like for our complex,
[1:04:54] SPEAKER: I guess the word mechanical keyboards can be not complex,
[1:04:57] SPEAKER: but you know, like you're changing switches out.
[1:04:58] SPEAKER: You might change things out on a keyboard.
[1:05:00] SPEAKER: It's probably better not to have something
[1:05:01] SPEAKER: like a biometric scanner built into the keyboard itself.
[1:05:05] SPEAKER: Maybe it's actually better to keep that discreet.
[1:05:07] SPEAKER: - I think, I mean, it's really nice on the MacBooks.
[1:05:10] SPEAKER: - Oh yeah, no, I use it all the time.
[1:05:11] SPEAKER: Like that's exactly why I want it in Windows too.
[1:05:14] SPEAKER: - The thing I'll say is the biometric Hello stuff
[1:05:17] SPEAKER: is not as useful in Windows as it is in OS X
[1:05:19] SPEAKER: 'cause it's not as tightly integrated across the board.
[1:05:23] SPEAKER: The thing I want on the keyboard,
[1:05:26] SPEAKER: my drop doesn't have it,
[1:05:27] SPEAKER: but the key crowns often will do a dial, a knob, a knob.
[1:05:32] SPEAKER: - Interesting.
[1:05:33] SPEAKER: - A good knob feels real good.
[1:05:35] SPEAKER: - It's true.
[1:05:36] SPEAKER: - Who doesn't want a knob?
[1:05:37] SPEAKER: - Need a good knob glide.
[1:05:39] SPEAKER: - Exactly.
[1:05:39] SPEAKER: - Need a good glide on your knob.
[1:05:40] SPEAKER: - Yeah, you just want to roll your finger
[1:05:43] SPEAKER: around the edge of the top and watch it spin.
[1:05:45] SPEAKER: I miss my old, what was the Mac knob that they used to sell?
[1:05:52] SPEAKER: Griffin made a knob for the Macs.
[1:05:56] SPEAKER: I can't remember what it was called.
[1:05:57] SPEAKER: - What is that reading?
[1:05:58] SPEAKER: Like what kind of input is that taking?
[1:06:00] SPEAKER: - It's just an analog, just one axis analog.
[1:06:03] SPEAKER: So you can do like the Griffin one, you could map to zoom.
[1:06:06] SPEAKER: Like it was, it had a click and you could map like zoom
[1:06:10] SPEAKER: or like I used to use it in Photoshop
[1:06:12] SPEAKER: and linear editors, nonlinear editors
[1:06:16] SPEAKER: to scroll the timeline, which was awesome.
[1:06:19] SPEAKER: But you could click it and change the function.
[1:06:20] SPEAKER: And that was, it was pretty dope.
[1:06:25] SPEAKER: Yeah, Griffin, what was the Griffin, Griffin knob?
[1:06:28] SPEAKER: I can't, this is going to bug me.
[1:06:31] SPEAKER: It was called the Griffin Power Mate.
[1:06:33] SPEAKER: - Aha.
[1:06:34] SPEAKER: - Yeah.
[1:06:35] SPEAKER: - I believe you can still get them.
[1:06:37] SPEAKER: - Yeah, they still sell them.
[1:06:38] SPEAKER: - Oh, that's a nice looking knob.
[1:06:39] SPEAKER: - It's a good, it's like a cool aluminum knob.
[1:06:42] SPEAKER: It was really, really awesome.
[1:06:43] SPEAKER: I probably have it in the garage still actually.
[1:06:45] SPEAKER: - Microsoft has a Microsoft surface dial
[1:06:48] SPEAKER: that also looks quite stylish.
[1:06:49] SPEAKER: - That only works on surfaces though, I believe.
[1:06:51] SPEAKER: - Oh no.
[1:06:52] SPEAKER: - Yeah.
[1:06:53] SPEAKER: - That's unfortunate.
[1:06:55] SPEAKER: - Sorry, everyone else.
[1:06:56] SPEAKER: - That's highly unfortunate.
[1:06:59] SPEAKER: - I think that's-
[1:07:00] SPEAKER: - Oh, what?
[1:07:01] SPEAKER: - What?
[1:07:02] SPEAKER: - Is this a thing?
[1:07:03] SPEAKER: - What?
[1:07:04] SPEAKER: - I'm only looking at the Amazon listing for this.
[1:07:05] SPEAKER: We could just sit here and talk about
[1:07:06] SPEAKER: disc doohickeys all day long.
[1:07:08] SPEAKER: According to this photo,
[1:07:09] SPEAKER: it looks like you can place the dial on the screen
[1:07:11] SPEAKER: and it will have UI pop up around the dial or the knob.
[1:07:15] SPEAKER: - Yeah.
[1:07:16] SPEAKER: - Well, that's cool.
[1:07:17] SPEAKER: - Yep.
[1:07:17] SPEAKER: - That's cool.
[1:07:18] SPEAKER: - I don't think it works on a whole lot of stuff though.
[1:07:19] SPEAKER: - I bet that is very tightly integrated
[1:07:22] SPEAKER: with the surface experience.
[1:07:23] SPEAKER: - I think it works on Adobe as the demo I've always seen.
[1:07:26] SPEAKER: - Okay.
[1:07:27] SPEAKER: - Yeah.
[1:07:28] SPEAKER: - That's neat.
[1:07:29] SPEAKER: - I also think that's only for the big surface,
[1:07:30] SPEAKER: but I could be wrong.
[1:07:31] SPEAKER: It might work on the little ones too.
[1:07:33] SPEAKER: - I see.
[1:07:34] SPEAKER: - Yeah.
[1:07:34] SPEAKER: I'm a real sucker for that kind of weird future UI stuff.
[1:07:40] SPEAKER: - Sure.
[1:07:41] SPEAKER: - Adobe did a stylus plus a ruler for iPads
[1:07:48] SPEAKER: for a long time until the pencil came out,
[1:07:50] SPEAKER: but the ruler would work.
[1:07:52] SPEAKER: It was basically a flat thing that was little
[1:07:54] SPEAKER: and you put it on the screen
[1:07:57] SPEAKER: and it would make an offset line
[1:08:00] SPEAKER: that was like a few pixels away from it.
[1:08:03] SPEAKER: Then it would lock your drawing on the stylus too.
[1:08:05] SPEAKER: - Wow.
[1:08:06] SPEAKER: - It was really neat.
[1:08:07] SPEAKER: - That's cool.
[1:08:08] SPEAKER: - It made drawing perspective lines really easy.
[1:08:09] SPEAKER: So yeah, I guess that's it for today.
[1:08:11] SPEAKER: - Yeah.
[1:08:12] SPEAKER: - This is, yeah, I don't know, is this a topic?
[1:08:18] SPEAKER: I feel like I learned something today.
[1:08:20] SPEAKER: - Yeah, sure.
[1:08:21] SPEAKER: - I'm envious of your desk though, Brad.
[1:08:23] SPEAKER: - I know, look, it doesn't come easy.
[1:08:25] SPEAKER: - Just to be clear, I'm not so envious
[1:08:27] SPEAKER: that I'm gonna spend any effort at all
[1:08:29] SPEAKER: making my desk have that level of,
[1:08:36] SPEAKER: I'm not disciplined enough to maintain your desk.
[1:08:39] SPEAKER: - Discipline is literally the word I was about to use.
[1:08:41] SPEAKER: It takes work for sure.
[1:08:43] SPEAKER: It adds about like 10 minutes of setup before every stream.
[1:08:47] SPEAKER: I'll say that.
[1:08:48] SPEAKER: - Yeah, I like people to walk in and hit a button and go.
[1:08:51] SPEAKER: Like I can turn on the stream PC and I'm ready to go.
[1:08:54] SPEAKER: - I get it, but working out of your house,
[1:08:56] SPEAKER: like you need some separation, frankly.
[1:08:58] SPEAKER: Like I need this to not look like a work desk all the time.
[1:09:00] SPEAKER: Like sometimes when I'm not working,
[1:09:02] SPEAKER: I just need this to look nice and tidy.
[1:09:04] SPEAKER: - See, what if you had no separation?
[1:09:06] SPEAKER: You just worked all the time.
[1:09:07] SPEAKER: That's the other, that's the American way.
[1:09:09] SPEAKER: - No.
[1:09:10] SPEAKER: - No, is that bad?
[1:09:11] SPEAKER: - You gotta push back against that.
[1:09:13] SPEAKER: - Oh.
[1:09:14] SPEAKER: - You got to invest in yourself.
[1:09:15] SPEAKER: - Look, if you love your job,
[1:09:16] SPEAKER: then it doesn't feel like a job is what I always say.
[1:09:20] SPEAKER: Anyway, this is a bad example.
[1:09:22] SPEAKER: I'm a bad influence here.
[1:09:23] SPEAKER: Don't listen to me.
[1:09:24] SPEAKER: This is the part of the show where we thank our Patrons.
[1:09:26] SPEAKER: - Yeah, thank you, Patrons.
[1:09:27] SPEAKER: I was going to say, as we transitioned to saying,
[1:09:30] SPEAKER: thank you to our Patrons.
[1:09:31] SPEAKER: - Thank you, Patrons.
[1:09:32] SPEAKER: - There is the Desks and Pets channel on the Discord.
[1:09:35] SPEAKER: If anybody wants to, I mean,
[1:09:37] SPEAKER: people will post pictures of their desks
[1:09:38] SPEAKER: in there on the regular, but.
[1:09:39] SPEAKER: - Yeah.
[1:09:40] SPEAKER: - If people want to extra talk about desk strategies
[1:09:44] SPEAKER: and techniques of all kinds,
[1:09:46] SPEAKER: that's a good place to do it.
[1:09:47] SPEAKER: - I will definitely be lurking in there
[1:09:49] SPEAKER: with the added bonus of occasionally seeing a dog or a cat.
[1:09:52] SPEAKER: - Why do I not hang out in Desks and Pets more?
[1:09:54] SPEAKER: It's like, you name that channel,
[1:09:55] SPEAKER: I have to say it is like the best name
[1:09:57] SPEAKER: for a Discord channel industry-wide.
[1:10:00] SPEAKER: - 'Cause I didn't want to have a channel
[1:10:02] SPEAKER: that was exclusive for people who didn't have pets, right?
[1:10:05] SPEAKER: - Well, sure.
[1:10:06] SPEAKER: - I'm pet-less right now.
[1:10:08] SPEAKER: - I mean, yeah, that's fair.
[1:10:09] SPEAKER: I mean, to me, though, what are the two types of photos
[1:10:11] SPEAKER: that everyone loves both posting
[1:10:13] SPEAKER: and looking at other people's of?
[1:10:15] SPEAKER: - Yeah.
[1:10:16] SPEAKER: Desks and Pets.
[1:10:17] SPEAKER: I will always look at people's desks or pets.
[1:10:20] SPEAKER: - People have good solutions, especially,
[1:10:22] SPEAKER: I especially, (laughs)
[1:10:24] SPEAKER: Norm the Bulldog gets posted fairly regularly
[1:10:27] SPEAKER: and his big flappy jowls are funny
[1:10:29] SPEAKER: every time when he's shaking, so.
[1:10:31] SPEAKER: - Norm the Bulldog is an all-star.
[1:10:34] SPEAKER: - A lot of pets right now, not a lot of desks.
[1:10:37] SPEAKER: So maybe I'll clean up my desk and post a good picture.
[1:10:41] SPEAKER: - Oh man, Siridar gave his dog a straight up steak
[1:10:44] SPEAKER: for his birth, his or her birthday.
[1:10:46] SPEAKER: - Wow, happy birthday.
[1:10:47] SPEAKER: - Man, seriously. - I'm gonna stay
[1:10:48] SPEAKER: for my birthday.
[1:10:50] SPEAKER: Anyway, yeah, thank you, patrons.
[1:10:52] SPEAKER: If you would like to support The Tech Pod,
[1:10:54] SPEAKER: if you enjoy this show and you would like us
[1:10:56] SPEAKER: to keep doing it, please consider joining the Patreon
[1:10:59] SPEAKER: and joining the Discord and signing up for the Mastodon.
[1:11:01] SPEAKER: We have all sorts of stuff now.
[1:11:03] SPEAKER: You can go to patreon.com/techpod.
[1:11:05] SPEAKER: Again, it's patreon.com/techpod.
[1:11:07] SPEAKER: And for five bucks a month, you get access to The Discord,
[1:11:10] SPEAKER: a fabulous monthly patron-exclusive episode.
[1:11:14] SPEAKER: You can hang out in desks and pets as much as you want.
[1:11:18] SPEAKER: You can post your pets and/or your desks.
[1:11:21] SPEAKER: Yes, hello. - Oh my God.
[1:11:23] SPEAKER: Ribs posted both a desk and two pets
[1:11:26] SPEAKER: in the exact same post.
[1:11:27] SPEAKER: - In the same picture? - Amazing.
[1:11:28] SPEAKER: - That's nuts.
[1:11:30] SPEAKER: Yeah, I'm just generally, I enjoy this channel a lot.
[1:11:34] SPEAKER: I like it when people post their dogs, cats, and other.
[1:11:39] SPEAKER: - Yeah, it's great.
[1:11:40] SPEAKER: Let me mention real quick,
[1:11:41] SPEAKER: if we can just pivot back to the topic for 30 seconds.
[1:11:44] SPEAKER: - Yeah, of course.
[1:11:45] SPEAKER: - They have an ultrawide.
[1:11:46] SPEAKER: - Yeah.
[1:11:47] SPEAKER: - I was gonna mention, 'cause we're both using,
[1:11:49] SPEAKER: I'm straight up using two monitors in the kind of layout
[1:11:53] SPEAKER: or aspect that one ultrawide would cover, right?
[1:11:56] SPEAKER: - You're a candidate for an ultrawide, I think.
[1:11:58] SPEAKER: - So the thing I was gonna ask about ultrawides,
[1:12:00] SPEAKER: or the thing I like about this
[1:12:02] SPEAKER: is that I can play a game on one monitor
[1:12:03] SPEAKER: and not have to worry about the other monitor
[1:12:05] SPEAKER: switching video modes or making the Discord window obscure.
[1:12:09] SPEAKER: How do people handle that on ultrawides?
[1:12:10] SPEAKER: Like, do they just go borderless window
[1:12:12] SPEAKER: in the middle of the screen
[1:12:13] SPEAKER: and do they still get these sides usable for other windows?
[1:12:16] SPEAKER: - Well, no, usually it fills the whole monitor.
[1:12:18] SPEAKER: - So that's the thing,
[1:12:19] SPEAKER: that I kind of always want to be able to look at a Discord
[1:12:22] SPEAKER: or something.
[1:12:23] SPEAKER: - Well, my ultrawide is one of the early,
[1:12:25] SPEAKER: early, early ultrawides,
[1:12:27] SPEAKER: but it let you set it up also
[1:12:28] SPEAKER: as two independent half-res monitors.
[1:12:31] SPEAKER: - Okay, so that's the thing I was wondering
[1:12:32] SPEAKER: is if you could do something like that.
[1:12:34] SPEAKER: I mean, obviously you can play a game
[1:12:35] SPEAKER: across the whole ultrawide if you want,
[1:12:37] SPEAKER: but I just, I could see all these situations
[1:12:38] SPEAKER: where I would just want to do standard 16 by nine
[1:12:41] SPEAKER: for the game so I could see something else at the same time.
[1:12:43] SPEAKER: - Well, and you're streaming a lot of times, too.
[1:12:45] SPEAKER: - Yeah, there's that.
[1:12:46] SPEAKER: - Which changes, which complicates things
[1:12:47] SPEAKER: 'cause like, ultrawide streaming is bad.
[1:12:49] SPEAKER: You shouldn't do that.
[1:12:50] SPEAKER: - But, yeah, yes.
[1:12:53] SPEAKER: But there's even stuff like,
[1:12:54] SPEAKER: like I was playing Marauders.
[1:12:55] SPEAKER: Have you played Marauders with some friends the other night?
[1:12:57] SPEAKER: - I've watched a bunch of Marauders being played.
[1:12:59] SPEAKER: - Man, Marauders is brutal.
[1:13:01] SPEAKER: - Dude, I would love to play Marauders sometime.
[1:13:02] SPEAKER: I am super, like I-
[1:13:04] SPEAKER: - Yeah, we should play it.
[1:13:05] SPEAKER: It's fun.
[1:13:06] SPEAKER: - One of my friends that I was playing with
[1:13:07] SPEAKER: plays a lot of Tarkov, though,
[1:13:09] SPEAKER: and he described Marauders as like arcade-style Tarkov.
[1:13:12] SPEAKER: - That sounds perfect.
[1:13:12] SPEAKER: - 'Cause streamlined Tarkov.
[1:13:15] SPEAKER: Anyway, Marauders has no spectator mode.
[1:13:18] SPEAKER: It's in early access.
[1:13:19] SPEAKER: Maybe they're gonna add that,
[1:13:20] SPEAKER: but when you die and wipe
[1:13:21] SPEAKER: and somebody else on your team is still in,
[1:13:22] SPEAKER: you're just sitting at the menu doing nothing.
[1:13:24] SPEAKER: - Well, you can like manage your inventory and stuff, right?
[1:13:26] SPEAKER: - Yeah, yeah, but you can't see what they're doing.
[1:13:28] SPEAKER: Like, it'd be nice to watch whoever's left in your squad
[1:13:30] SPEAKER: finish out the round.
[1:13:32] SPEAKER: - Yeah, that's a choice.
[1:13:33] SPEAKER: - And so that was like, that was a situation
[1:13:35] SPEAKER: where like my friend was streaming on Discord
[1:13:36] SPEAKER: so we could see, 'cause he tended, what a surprise,
[1:13:39] SPEAKER: the Tarkov player tended to be the last one standing.
[1:13:42] SPEAKER: - Weird.
[1:13:43] SPEAKER: - But he was streaming to Discord
[1:13:43] SPEAKER: so we could see what he was doing in the game.
[1:13:46] SPEAKER: So like it's useful for multiple reasons
[1:13:48] SPEAKER: to have non-game real estate on your desk.
[1:13:51] SPEAKER: - Yeah, I mean, I often, even at work,
[1:13:53] SPEAKER: like when we're, either like somebody's helping me
[1:13:56] SPEAKER: troubleshoot something on Unreal Ed
[1:13:57] SPEAKER: or like we're replicating a bug,
[1:14:00] SPEAKER: we'll often stream to Discord or teams or whatever
[1:14:04] SPEAKER: so that people can, we have multiple eyes on the problem.
[1:14:06] SPEAKER: It's useful.
[1:14:08] SPEAKER: - Anyway, that's why I tend to stick
[1:14:10] SPEAKER: with two discrete monitors instead of one big ultrawide.
[1:14:12] SPEAKER: - I mean, you could just go with the vertical ultrawide.
[1:14:16] SPEAKER: That's my solution to this problem.
[1:14:19] SPEAKER: Get a tall boy.
[1:14:20] SPEAKER: - One of those three by three D&D alignment images
[1:14:24] SPEAKER: was going around this week except for monitor configuration
[1:14:27] SPEAKER: on your desktop.
[1:14:28] SPEAKER: I don't know that they had the vertical ultrawide on there.
[1:14:31] SPEAKER: That's--
[1:14:32] SPEAKER: - That's chaotic evil.
[1:14:33] SPEAKER: It's gotta be.
[1:14:34] SPEAKER: - I was gonna say, that's a level below chaotic evil.
[1:14:37] SPEAKER: The vertical ultrawide is like the monitor from hell.
[1:14:41] SPEAKER: Like that's way below the worst of the alignments.
[1:14:44] SPEAKER: - So they had a hard, so yeah,
[1:14:47] SPEAKER: I'm definitely chaotic evil on that alignment chart.
[1:14:49] SPEAKER: Anyway.
[1:14:50] SPEAKER: - Thank you, patrons.
[1:14:51] SPEAKER: - Thank you, patrons.
[1:14:52] SPEAKER: We appreciate you and we especially appreciate our,
[1:14:56] SPEAKER: let's see, I closed the window.
[1:14:57] SPEAKER: There we go, the tap.
[1:14:58] SPEAKER: Our executive producer tier patrons,
[1:15:00] SPEAKER: including Nick Johnston,
[1:15:01] SPEAKER: Paddle Creek Games Makers of Fractured Veil,
[1:15:03] SPEAKER: Andrew Slosky, Octothorpe parentheses,
[1:15:06] SPEAKER: hashtag parentheses, Bunny Crimes,
[1:15:09] SPEAKER: Just Wedge, Joel Krauska, Twinkle Twinkie,
[1:15:11] SPEAKER: David Allen and James Kamik.
[1:15:13] SPEAKER: Thank you all so much.
[1:15:14] SPEAKER: We do really appreciate your, everyone's support.
[1:15:17] SPEAKER: - We do.
[1:15:17] SPEAKER: - It makes the show possible.
[1:15:18] SPEAKER: And we will be back next week
[1:15:21] SPEAKER: with another episode of the show.
[1:15:23] SPEAKER: Hey. - We will.
[1:15:24] SPEAKER: - I just wanna shout out a couple of people
[1:15:26] SPEAKER: 'cause the SVB thing is causing some trouble
[1:15:30] SPEAKER: for folks in our circles.
[1:15:33] SPEAKER: The wonderful folks over at keyboardio
[1:15:36] SPEAKER: are running a sale right now of,
[1:15:39] SPEAKER: so they have a lot of inventory and not a ton of cash
[1:15:41] SPEAKER: while their money's tied up in the SVB thing.
[1:15:45] SPEAKER: And they're running a sale.
[1:15:46] SPEAKER: So if you wanted to get a keyboardio model 100 for 20% off,
[1:15:49] SPEAKER: you can right now by going to their site and putting,
[1:15:52] SPEAKER: I think it's keyboardio20 is the code maybe.
[1:15:55] SPEAKER: I can't remember.
[1:15:56] SPEAKER: But Jesse's posted about on Mastodon
[1:15:58] SPEAKER: and I think Twitter as well.
[1:16:00] SPEAKER: They also have like key caps and a bunch of,
[1:16:02] SPEAKER: if you want an Atreus,
[1:16:03] SPEAKER: which is their little portable keyboard,
[1:16:06] SPEAKER: like we like them and want them to keep making,
[1:16:09] SPEAKER: like as Jesse said, we're fine,
[1:16:11] SPEAKER: but having more cash is always nice.
[1:16:15] SPEAKER: And they can run out some inventory too, which is helpful.
[1:16:18] SPEAKER: - Also to be clear, not an ad.
[1:16:19] SPEAKER: - Not an ad.
[1:16:20] SPEAKER: We just like Jesse and keyboardio and what they do
[1:16:25] SPEAKER: and want them to keep being around.
[1:16:27] SPEAKER: And yeah, that's it.
[1:16:30] SPEAKER: So we'll see you all next week.
[1:16:30] SPEAKER: Thanks for listening everybody.
[1:16:32] SPEAKER: (upbeat music)
