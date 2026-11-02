---
episode: 235
title: 225: The Goldblum Conjecture
date: 2024-03-10
guests: none
duration: 1:12:01
---

[00:00] SPEAKER: - Brad, I hate it when I'm listening to music
[00:02] SPEAKER: and I have a playlist that spans decades
[00:04] SPEAKER: and the volume level of the music is all over the place.
[00:08] SPEAKER: - Oh man, I don't think I actually realized it
[00:11] SPEAKER: until you brought this up.
[00:11] SPEAKER: I think this is a hot button issue for me
[00:13] SPEAKER: that has just been waiting for a cold open.
[00:15] SPEAKER: - Man. - Go on.
[00:16] SPEAKER: - Yeah, we were listening to some music.
[00:17] SPEAKER: We had, like I made a playlist of stuff
[00:20] SPEAKER: that we all like in the fam from the '90s and '80s
[00:25] SPEAKER: and 2000s and 2020s.
[00:27] SPEAKER: And you're in the car, you're listening to some music,
[00:29] SPEAKER: you're jamming out, like you listen to some like Cheap Trick,
[00:33] SPEAKER: some stuff that my kid knows
[00:35] SPEAKER: 'cause it was in a Trolls movie.
[00:36] SPEAKER: - Is your daughter a Cheap Trick fan?
[00:38] SPEAKER: - No, not really. - Okay.
[00:39] SPEAKER: - But then you get, look, I couldn't come up with it.
[00:42] SPEAKER: Cheap Trick was just what I thought of in the moment.
[00:43] SPEAKER: It's not really on the list.
[00:45] SPEAKER: But we get to the end of the '80s song
[00:48] SPEAKER: and then it blasts over to something that's current,
[00:50] SPEAKER: some Olivia Rodrigo or something,
[00:52] SPEAKER: and it's like a thousand times louder.
[00:54] SPEAKER: - I guess you crossed the boundary into the loudness wars.
[00:57] SPEAKER: - But I mean, look, we were complaining
[01:00] SPEAKER: about the loudness wars in the '90s.
[01:02] SPEAKER: - True, yes.
[01:03] SPEAKER: - Yeah, it's gotten worse.
[01:04] SPEAKER: - I'm sure it has.
[01:05] SPEAKER: - It's bad.
[01:06] SPEAKER: - Like all audio has gotten worse.
[01:08] SPEAKER: I don't even know where to start.
[01:09] SPEAKER: Like stereo down mixing is awful
[01:11] SPEAKER: for people who don't have 5.1 systems.
[01:13] SPEAKER: Nobody can hear the dialogue
[01:14] SPEAKER: of what they're watching anymore.
[01:16] SPEAKER: - Oh, the secret to that is you just have a center channel
[01:18] SPEAKER: and you disconnect the other channels.
[01:20] SPEAKER: - Seriously, I've got two nice floor speakers
[01:23] SPEAKER: and that's all I've been using for 15 years.
[01:24] SPEAKER: I keep thinking about buying a center channel speaker
[01:26] SPEAKER: just to be able to hear people talk in movies again.
[01:29] SPEAKER: - We do two front speakers and a center channel,
[01:31] SPEAKER: but the real answer is to just get a soundbar and give up.
[01:35] SPEAKER: Or do what Rob Zachney did
[01:36] SPEAKER: and put some like 12 foot tall speakers in there.
[01:38] SPEAKER: - Or you could do what I did
[01:39] SPEAKER: and experiment with using FFmpeg
[01:41] SPEAKER: to create your own stereo mixes of movies,
[01:43] SPEAKER: which works just fine.
[01:46] SPEAKER: - That's too much work, Brad.
[01:47] SPEAKER: - It took a lot of work.
[01:48] SPEAKER: I thought about scripting it across my entire Plex library.
[01:51] SPEAKER: All you do, I mean, literally all you do
[01:52] SPEAKER: is tell it to mix the channels
[01:54] SPEAKER: and boost the center channel by 30%.
[01:56] SPEAKER: Like that's it, that's all it takes.
[01:57] SPEAKER: - This is an audio podcast.
[01:58] SPEAKER: No one can see me shaking my head,
[02:00] SPEAKER: but just know that I shook my head
[02:01] SPEAKER: through that entire FFmpeg bit.
[02:03] SPEAKER: - But I like, I mean, that raises the question for me though
[02:06] SPEAKER: of like, why are Plex and Jellyfin
[02:08] SPEAKER: or your receiver or your TV,
[02:09] SPEAKER: like why are things that handle stereo mixing
[02:11] SPEAKER: not doing that themselves?
[02:12] SPEAKER: - Why don't Spotify and Apple Music normalize?
[02:16] SPEAKER: Like the playlists are a huge part
[02:18] SPEAKER: of Spotify and Apple Music.
[02:20] SPEAKER: Why don't they normalize the volumes across those playlists?
[02:22] SPEAKER: I don't know, man.
[02:23] SPEAKER: - I would say the same thing for game consoles.
[02:25] SPEAKER: Like why are some games on my PS5 way louder than others?
[02:29] SPEAKER: - Yeah, like it's funny.
[02:31] SPEAKER: The first thing I have to do, so it's weird.
[02:34] SPEAKER: I mean, streaming makes things a little bit weird
[02:36] SPEAKER: because normally you just adjust to the volume you want,
[02:37] SPEAKER: right, but like I don't ever adjust the knob
[02:41] SPEAKER: on my headphones or the windows volume.
[02:44] SPEAKER: I always adjust the in-game volume.
[02:46] SPEAKER: - And really?
[02:47] SPEAKER: - Yeah, 'cause I don't,
[02:48] SPEAKER: 'cause like I play Fortnite all the time
[02:50] SPEAKER: and I don't want to have to adjust
[02:50] SPEAKER: the Fortnite audio every time.
[02:52] SPEAKER: So everything's normal, like, okay, here's the problem.
[02:55] SPEAKER: Everything's normalized against Fortnite.
[02:59] SPEAKER: Fortnite is my base level volume.
[03:00] SPEAKER: This is the problem.
[03:01] SPEAKER: - That's a grim state of affairs.
[03:04] SPEAKER: - I mean, look, the Gangnam,
[03:06] SPEAKER: I know what level of a Gangnam's gonna be.
[03:08] SPEAKER: I know when I do the say so.
[03:09] SPEAKER: I know what it's gonna sound like.
[03:11] SPEAKER: And I gotta get my Doja Cat on.
[03:14] SPEAKER: (upbeat music)
[03:25] SPEAKER: (upbeat music continues)
[03:43] SPEAKER: - Welcome to "Brad and Will Made a Tech Pod."
[03:45] SPEAKER: I'm Will.
[03:46] SPEAKER: - I'm Brad.
[03:48] SPEAKER: You sounded a little better this week.
[03:49] SPEAKER: - I don't sound as much like Barry White,
[03:51] SPEAKER: but I'm still in there.
[03:53] SPEAKER: I'm still in that range.
[03:54] SPEAKER: - Is it worth giving up that timbre of voice
[03:57] SPEAKER: to be coughing less?
[03:58] SPEAKER: I would say probably yes.
[03:59] SPEAKER: - I would do anything to be coughing less right now.
[04:02] SPEAKER: I would, if you, like, I would do horrible things.
[04:05] SPEAKER: - Would you pitch up a couple more octaves?
[04:06] SPEAKER: - No, I wouldn't.
[04:07] SPEAKER: That's too far.
[04:08] SPEAKER: So like my chest isn't sore from coughing anymore,
[04:12] SPEAKER: which is nice.
[04:13] SPEAKER: That's a good change.
[04:14] SPEAKER: And I don't wake up in the middle of the night
[04:16] SPEAKER: feeling like I'm choking to death on things
[04:18] SPEAKER: that I have to then hack up.
[04:19] SPEAKER: So that's an improvement.
[04:20] SPEAKER: - Yeah.
[04:21] SPEAKER: - Yeah.
[04:22] SPEAKER: - Quite a winter we're having.
[04:23] SPEAKER: - It's been, this is the winter of my discontent,
[04:25] SPEAKER: it turns out, and my discontent is phlegm.
[04:27] SPEAKER: - Yeah.
[04:28] SPEAKER: Well, good news for you.
[04:29] SPEAKER: - Yeah.
[04:30] SPEAKER: - I just found out hours ago
[04:31] SPEAKER: that it's fucking Daylight Savings this weekend.
[04:34] SPEAKER: - No, this is good Daylight Savings, though.
[04:35] SPEAKER: - Wait, how?
[04:36] SPEAKER: - This is the spring forward one.
[04:38] SPEAKER: Wait, is that the bad one?
[04:39] SPEAKER: That's the one where everybody dies on Monday
[04:40] SPEAKER: 'cause a car crashes.
[04:42] SPEAKER: Be careful tomorrow out there, folks.
[04:44] SPEAKER: Maybe go back and listen to that Daylight Savings episode,
[04:45] SPEAKER: 'cause it was pretty good.
[04:46] SPEAKER: People like that.
[04:47] SPEAKER: - Also remember the disruption in circadian rhythms
[04:50] SPEAKER: leads to an increase in heart disease.
[04:52] SPEAKER: Look, if that's the thing
[04:54] SPEAKER: that's causing our heart disease problems.
[04:56] SPEAKER: - It can't help.
[04:57] SPEAKER: - I have wild misunderstandings about the impact of diet
[05:00] SPEAKER: on heart disease in America.
[05:01] SPEAKER: - Every little bit helps, okay.
[05:03] SPEAKER: - Look, I gotta get out to In-N-Out after this.
[05:04] SPEAKER: It's the, get a burger this afternoon.
[05:08] SPEAKER: Anyway.
[05:08] SPEAKER: - Yeah, anyway, hey, winter's over.
[05:09] SPEAKER: You'll be healed in a matter of hours.
[05:11] SPEAKER: - Thank God, finally.
[05:12] SPEAKER: Finally, our long national nightmare.
[05:14] SPEAKER: It stopped raining for long enough.
[05:15] SPEAKER: I saw sun this week, which was really exciting.
[05:17] SPEAKER: It's rained for so long.
[05:19] SPEAKER: My sister was in town last week,
[05:21] SPEAKER: so we went all over and we did the tour stuff
[05:24] SPEAKER: that she hasn't done on previous visits.
[05:25] SPEAKER: So we went to Muir Woods and she was like,
[05:28] SPEAKER: "Can we go to the zoo?
[05:29] SPEAKER: I haven't been to a zoo in a long time."
[05:30] SPEAKER: And we're like, "Yes, we can go to the zoo."
[05:32] SPEAKER: So we went to the zoo and it rained the entire time.
[05:34] SPEAKER: We were walking around our raincoats looking at elephants
[05:36] SPEAKER: and the animals were all kind of vaguely moist and upset.
[05:39] SPEAKER: - The animals were depressed.
[05:41] SPEAKER: - Yeah, the lion was roaring, that was cool.
[05:43] SPEAKER: We saw lemurs, the lemurs seemed to like the rain.
[05:45] SPEAKER: They were out playing in the rain.
[05:47] SPEAKER: I don't know, it was a good zoo trip.
[05:48] SPEAKER: The giraffes were chill, giraffes are awesome.
[05:51] SPEAKER: No gorillas though, that was a bummer.
[05:53] SPEAKER: - Were they hiding?
[05:54] SPEAKER: - I mean, the gorillas don't like the rain apparently.
[05:56] SPEAKER: They were in their houses.
[05:58] SPEAKER: The gorillas have the freedom to go in and out of the pen
[06:01] SPEAKER: into the smaller house area.
[06:04] SPEAKER: They were in the house area where they have privacy
[06:06] SPEAKER: 'cause they're primates.
[06:07] SPEAKER: - Smart.
[06:08] SPEAKER: - They don't give the monkeys privacy,
[06:09] SPEAKER: but the gorillas get privacy.
[06:11] SPEAKER: I have a lot of questions about this now
[06:12] SPEAKER: that I think about it.
[06:13] SPEAKER: But you know what I don't have questions about?
[06:16] SPEAKER: - What's that?
[06:17] SPEAKER: - Is what makes a good on-stage tech demo?
[06:21] SPEAKER: - Oh.
[06:22] SPEAKER: - So we started out talking about this episode this week
[06:25] SPEAKER: and we both have been aware of this thing
[06:28] SPEAKER: called the mother of all demos for a long time.
[06:31] SPEAKER: But it's a famous presentation by Doug Engelbart
[06:34] SPEAKER: who was at Stanford, at the Stanford Research Institute
[06:38] SPEAKER: I think, and did a demo of his network computer
[06:42] SPEAKER: in like 1968 I think.
[06:44] SPEAKER: We're gonna do a whole episode about the MoEd,
[06:45] SPEAKER: so I don't wanna talk about it too much.
[06:47] SPEAKER: But it's where he demoed basically the first mouse
[06:51] SPEAKER: and the first graphical user GUI for a computer
[06:56] SPEAKER: and things like bi-directional network communications
[07:00] SPEAKER: and like crazy stuff, right?
[07:02] SPEAKER: - Basically in the space of 90 minutes
[07:04] SPEAKER: like it defined the future of computing
[07:06] SPEAKER: or the entirety of what computing would be in the future.
[07:08] SPEAKER: - Yeah, so there were around a thousand people
[07:10] SPEAKER: in attendance at the demo
[07:11] SPEAKER: and the most common feedback from it
[07:14] SPEAKER: was that like this felt like it was 150 years in the future
[07:18] SPEAKER: and it was cool but I'm never gonna be able
[07:19] SPEAKER: to do anything with it.
[07:20] SPEAKER: So I went back to, like just to be clear,
[07:23] SPEAKER: they weren't using glass teletypes at this point
[07:25] SPEAKER: to talk, to do remote network computers.
[07:28] SPEAKER: They were using paper teletypes
[07:29] SPEAKER: where you typed in on a typewriter
[07:31] SPEAKER: and then the words came out on the other side also on paper.
[07:35] SPEAKER: - Yes, it was the '60s.
[07:36] SPEAKER: - Yeah, it was the '60s.
[07:37] SPEAKER: So this is the prototype, right?
[07:39] SPEAKER: This is I think the first one of these.
[07:41] SPEAKER: I think it's safe to say that.
[07:43] SPEAKER: - High watermark.
[07:44] SPEAKER: - Maybe, yeah.
[07:47] SPEAKER: But then this kind of continued, right?
[07:51] SPEAKER: I realize there's one we didn't put on here.
[07:52] SPEAKER: There's the one that started this whole conversation.
[07:55] SPEAKER: But before we get to that,
[07:57] SPEAKER: I wanna talk about what makes a good demo,
[07:58] SPEAKER: what makes a good on-stage demo.
[08:00] SPEAKER: And I think core to this is that it has to show you
[08:02] SPEAKER: something that feels like the future
[08:05] SPEAKER: and it's something that wasn't possible,
[08:07] SPEAKER: you didn't think was possible when you entered the room,
[08:09] SPEAKER: which is harder.
[08:10] SPEAKER: It gets harder every year to do that, I think.
[08:12] SPEAKER: - Yeah, although a theme that I've noticed
[08:14] SPEAKER: as we watch through a bunch of these for this episode
[08:16] SPEAKER: is even the ones that took place 20 plus years ago now
[08:19] SPEAKER: that show technology that today is so old hat,
[08:22] SPEAKER: you don't even think about it,
[08:23] SPEAKER: like it's still possible to recapture that excitement
[08:26] SPEAKER: watching those if you can kind of put yourself back
[08:28] SPEAKER: in that mindset of when that technology did not exist.
[08:31] SPEAKER: Like the best ones of these are still fairly exhilarating
[08:33] SPEAKER: to watch, which we'll get to.
[08:35] SPEAKER: - Incredible, they're still incredible, yeah.
[08:39] SPEAKER: This topic was suggested by Wildcard.
[08:42] SPEAKER: Not exactly this topic,
[08:42] SPEAKER: but Wildcard made a suggestion to kick this off
[08:46] SPEAKER: and on the Discord and the idea was
[08:50] SPEAKER: to talk about this Disney Vision Imagineering Lab VR demo,
[08:53] SPEAKER: which I'm gonna put on the bottom of the list here
[08:54] SPEAKER: 'cause I do wanna talk about it,
[08:55] SPEAKER: but I think that's maybe worth,
[08:57] SPEAKER: I'm kind of curious about this too
[08:58] SPEAKER: in the context maybe of a larger episode about Imagineering.
[09:01] SPEAKER: Anyway, so like there also has to be an element of risk,
[09:05] SPEAKER: right, so that's a big part of it is.
[09:08] SPEAKER: - Or well, let's say there doesn't have to be,
[09:10] SPEAKER: but like if there's not kind of why are you bothering,
[09:13] SPEAKER: you know, 'cause there's plenty of tech demos,
[09:14] SPEAKER: you know, we'll kind of touch on some of these
[09:16] SPEAKER: like motion controls in the mid-aughts on game consoles,
[09:19] SPEAKER: stuff like that, where like,
[09:20] SPEAKER: if you're just gonna do a big manicured produced,
[09:22] SPEAKER: like we shot this on a sound stage in a fake living room
[09:25] SPEAKER: with not real game footage, you know,
[09:27] SPEAKER: like why are you even bothering like concept stuff
[09:29] SPEAKER: or, you know, like the Xbox 360 connects stuff
[09:33] SPEAKER: that turned out to not be real, you know, stuff like that.
[09:35] SPEAKER: It's like people see through that stuff immediately.
[09:38] SPEAKER: So like there should,
[09:39] SPEAKER: let's say there doesn't have to be an element of risk,
[09:40] SPEAKER: but there practically does.
[09:42] SPEAKER: - Like the ones that are good,
[09:44] SPEAKER: I feel like always have an element of,
[09:46] SPEAKER: we're doing this live in front of an audience
[09:48] SPEAKER: and stuff might go wrong, right?
[09:50] SPEAKER: Like it's like when you used to watch the guy
[09:53] SPEAKER: bring the tigers onto Johnny Carson and you were like,
[09:56] SPEAKER: maybe Ed McMahon's gonna get mauled.
[09:57] SPEAKER: That would be good TV, I'd watch that, right?
[10:00] SPEAKER: So there's an element of danger and like sometimes,
[10:05] SPEAKER: but sometimes the tech is so far ahead
[10:08] SPEAKER: that you're like, I don't care.
[10:09] SPEAKER: The AT&T You Will ads, classic example of this.
[10:12] SPEAKER: 'Cause it's like, we were watching these in the early nineties
[10:15] SPEAKER: and they're like, there's a whole series of things
[10:17] SPEAKER: that they promise and you're like,
[10:19] SPEAKER: none of this could possibly ever happen.
[10:20] SPEAKER: And then like 10 years later at all, it happened.
[10:22] SPEAKER: - It's amazing.
[10:23] SPEAKER: So we will publish the show notes for this.
[10:25] SPEAKER: Like we've been doing recently,
[10:26] SPEAKER: people seem to like being able to follow along with links.
[10:28] SPEAKER: We've got links to pretty much every demo
[10:30] SPEAKER: we're gonna be talking about in here that you can watch.
[10:31] SPEAKER: But we did not put the You Will,
[10:34] SPEAKER: this is the AT&T You Will commercial campaign
[10:37] SPEAKER: from the early nineties.
[10:37] SPEAKER: - Have you ever bought a baseball tickets
[10:39] SPEAKER: from an automated teller machine?
[10:41] SPEAKER: - Yeah.
[10:42] SPEAKER: - You Will.
[10:43] SPEAKER: - Wait, is that your Tom Selleck impression?
[10:44] SPEAKER: - No, it was Tom Selleck, right?
[10:46] SPEAKER: Yes, it was Tom Selleck.
[10:47] SPEAKER: - So I went back and watched all of these.
[10:48] SPEAKER: I was, A, I had forgotten it was Tom Selleck narrating.
[10:51] SPEAKER: B, I did not realize David Fincher directed all of those,
[10:54] SPEAKER: which is wild to think about.
[10:56] SPEAKER: I guess he went from that to music videos
[10:58] SPEAKER: to making "Effing 7."
[11:00] SPEAKER: - Well, he did commercials and music videos for a long time.
[11:02] SPEAKER: - Yeah, I knew that.
[11:03] SPEAKER: I just didn't like, you know,
[11:04] SPEAKER: these actually kind of have that distinctive Fincher look
[11:06] SPEAKER: now that I think about it.
[11:07] SPEAKER: But anyway, watching those things,
[11:10] SPEAKER: it's like, okay, it's a lot of video conferencing.
[11:12] SPEAKER: It's a lot of sort of early pre-internet.
[11:15] SPEAKER: Like, have you ever checked out a book
[11:17] SPEAKER: from thousands of miles away?
[11:19] SPEAKER: It's a lot of connectivity, a lot of telephony type stuff.
[11:21] SPEAKER: But the crazy thing watching those things
[11:23] SPEAKER: is that every single one of those things came to pass.
[11:25] SPEAKER: - In like not that much time.
[11:27] SPEAKER: And I also-
[11:28] SPEAKER: - By and large within like a decade.
[11:30] SPEAKER: But I'd say the most forward-looking one
[11:32] SPEAKER: that kind of took me by surprise was,
[11:34] SPEAKER: have you ever made a phone call from your wrist?
[11:37] SPEAKER: And it's somebody talking into a watch to make a phone call.
[11:40] SPEAKER: - Wow.
[11:41] SPEAKER: - I'd say that's probably the longest lead
[11:43] SPEAKER: in all the ideas they present in there.
[11:44] SPEAKER: - 'Cause that was like 2014 or 2013, I guess.
[11:47] SPEAKER: - As well.
[11:47] SPEAKER: - That's when the Apple Watch came out.
[11:49] SPEAKER: There were other watches before that though.
[11:51] SPEAKER: - Maybe 20, yeah, 20-ish years on that one.
[11:53] SPEAKER: Like every one of the ideas in those commercials
[11:56] SPEAKER: not only happened, but is like super old hat these days.
[11:59] SPEAKER: Like there was nothing remotely futuristic
[12:02] SPEAKER: or advanced or unbelievable in those commercials.
[12:05] SPEAKER: Like they were, I guess what I'm trying to say
[12:06] SPEAKER: is they were like, they were shockingly conservative
[12:10] SPEAKER: in the ideas they promised in there
[12:12] SPEAKER: because all of them were probably
[12:13] SPEAKER: in some early stage of development at that point.
[12:15] SPEAKER: - They felt like the distant future of the year 2000
[12:18] SPEAKER: when you saw those ads.
[12:19] SPEAKER: Anyway, don't want to go on.
[12:20] SPEAKER: So another example,
[12:22] SPEAKER: Val's mixed reality trailer for the Vive.
[12:24] SPEAKER: The thing that they put the group,
[12:25] SPEAKER: they did the camera tracking so they could superimpose
[12:28] SPEAKER: the things that people were seeing in VR
[12:30] SPEAKER: on the video screen behind them
[12:32] SPEAKER: and on top of the people was really, really cool.
[12:35] SPEAKER: - I don't think it, I don't think it, sorry, Chet.
[12:36] SPEAKER: I don't think it hangs for this.
[12:37] SPEAKER: It was really good, but, but it,
[12:41] SPEAKER: well, it did promise something that felt like the future.
[12:43] SPEAKER: It was because of the way those videos had to be made.
[12:46] SPEAKER: They were pre-baked and felt pretty safe, right?
[12:48] SPEAKER: It was like, it was clearly a manicured experience
[12:52] SPEAKER: to design, you know, of course all of this is designed
[12:55] SPEAKER: to sell something.
[12:56] SPEAKER: This is the thing to remember.
[12:57] SPEAKER: - I mean, that one, I'm kind of of two minds
[12:59] SPEAKER: because A, yes, it is all faked and kind of manicured
[13:02] SPEAKER: and a little too slick, but on the other hand,
[13:06] SPEAKER: you can't show what's going on inside a VR helmet
[13:08] SPEAKER: for the person in it.
[13:09] SPEAKER: - Oh. - Like there's no way.
[13:11] SPEAKER: - It was brilliant for ways to show the VR
[13:14] SPEAKER: and like the shots where they show the camera view
[13:16] SPEAKER: on a screen and then you can see the person walking around
[13:19] SPEAKER: the green screen in the back are really, really good.
[13:21] SPEAKER: It's really smart.
[13:22] SPEAKER: - Yeah, like, yeah, while it is a person on a green screen,
[13:24] SPEAKER: like it does give you an idea of what the head tracking
[13:26] SPEAKER: and positional tracking would be like if you were in there.
[13:28] SPEAKER: So like, I think it gets the idea across
[13:30] SPEAKER: even though it's easy to look at that and say like,
[13:32] SPEAKER: well, you're just faking a bunch of stuff.
[13:34] SPEAKER: This is whatever.
[13:35] SPEAKER: - As a side note on the VR front,
[13:37] SPEAKER: of all the VR demos I did in the early days of VR stuff,
[13:40] SPEAKER: the behind closed doors vive demo at GDC 2015, I think,
[13:47] SPEAKER: were the gold standard.
[13:49] SPEAKER: Like that was one of those moments for me.
[13:51] SPEAKER: It was a C, I was locked in a small room
[13:54] SPEAKER: with another person.
[13:55] SPEAKER: It wasn't on stage, but it felt high risk
[13:59] SPEAKER: because we had to strap on this thing.
[14:01] SPEAKER: You had to wear a belt that had
[14:02] SPEAKER: your controllers connected to it.
[14:05] SPEAKER: Like there was a person in there to make sure
[14:06] SPEAKER: you didn't trip and fall or yank the cables
[14:08] SPEAKER: out of the wall or something.
[14:10] SPEAKER: And the demos were all incredibly high risk, right?
[14:14] SPEAKER: Like they didn't show any shooting games in that demo loop.
[14:17] SPEAKER: They showed the underwater thing with the whale.
[14:21] SPEAKER: They showed Tilt Brush.
[14:22] SPEAKER: They showed, what else?
[14:24] SPEAKER: They showed, Tilt Brush is a painting app
[14:28] SPEAKER: for people who don't know.
[14:28] SPEAKER: They showed some stuff where like the shop
[14:33] SPEAKER: from Dota got torn up around you.
[14:36] SPEAKER: They showed a bow and arrow game.
[14:39] SPEAKER: They showed a thing where you could spit balloons
[14:40] SPEAKER: and they'd float up to the ceiling.
[14:42] SPEAKER: It was all stuff where your verbs
[14:45] SPEAKER: as a player weren't shooting.
[14:47] SPEAKER: And it felt like that felt so shocking
[14:50] SPEAKER: that you didn't even realize you hadn't played a gun game,
[14:53] SPEAKER: which at that point, every VR demo
[14:54] SPEAKER: had ended with a gun game pretty much.
[14:56] SPEAKER: So anyway, and then I think there's an element
[15:02] SPEAKER: of theatricality here.
[15:03] SPEAKER: - Yeah, I'd put that in there.
[15:05] SPEAKER: That's just basically the Steve Jobs factor.
[15:07] SPEAKER: Like that's what brings this to mind.
[15:10] SPEAKER: Although, I mean, there's a bunch of stuff
[15:11] SPEAKER: we'll talk about on here.
[15:11] SPEAKER: Like there's the Xbox 360 first demo
[15:14] SPEAKER: that was with the tilted stage
[15:15] SPEAKER: and the Jay Allard sitting cross-legged.
[15:17] SPEAKER: We did a 360 episode with Deep Dive last year
[15:20] SPEAKER: or sometime if you wanna go.
[15:21] SPEAKER: We talked way more about that stuff there.
[15:22] SPEAKER: - Yeah, but the Jay Allard one is like,
[15:24] SPEAKER: they're trying desperately to do the thing
[15:26] SPEAKER: that Jobs did, and they're just not good at it.
[15:29] SPEAKER: - There's like the Google Glass one, which we'll get to.
[15:32] SPEAKER: Maybe the worst example of this.
[15:33] SPEAKER: - No, no, no, the Elon Musk ones are all,
[15:35] SPEAKER: the Google Glass one looks like a Beethoven's Fifth Symphony
[15:38] SPEAKER: compared to any time Elon Musk has been on a stage.
[15:40] SPEAKER: - Fair, fair, you know, weirdly,
[15:42] SPEAKER: I've never bothered to watch any instance
[15:44] SPEAKER: of Elon Musk on a stage.
[15:46] SPEAKER: - Good God, they're terrible.
[15:48] SPEAKER: - But it's the thing that a lot of people attempt
[15:51] SPEAKER: and that like Jobs did effortlessly.
[15:53] SPEAKER: And I feel like I always need to provide this disclaimer
[15:56] SPEAKER: like Jobs is a huge asshole.
[15:58] SPEAKER: - Yeah, not a nice person.
[15:59] SPEAKER: - A bunch of aspects of Jobs' personality, complete shit.
[16:02] SPEAKER: But like he had an unbelievable effortless ability
[16:06] SPEAKER: to be a salesman on stage in a way
[16:09] SPEAKER: that was relatable and effective.
[16:11] SPEAKER: - Well, and he had like, I don't mean this dismissively,
[16:15] SPEAKER: but he had like Carney level timing.
[16:17] SPEAKER: His timing was brilliant.
[16:18] SPEAKER: And he would do like, there's a moment,
[16:21] SPEAKER: we'll talk about this.
[16:22] SPEAKER: Actually, we can talk about it now if we want,
[16:23] SPEAKER: but there's a moment when he's doing the MacBook Air reveal,
[16:27] SPEAKER: the first one, when like he's on the stage,
[16:29] SPEAKER: he's talking about other laptops,
[16:32] SPEAKER: other thin and light laptops.
[16:33] SPEAKER: And he's like, well, here's the stuff,
[16:34] SPEAKER: like here's the category, right?
[16:36] SPEAKER: It's like Sony has this one.
[16:37] SPEAKER: I really like the Sony one.
[16:38] SPEAKER: It's a good one, blah, blah, blah.
[16:39] SPEAKER: It's three pounds.
[16:41] SPEAKER: The screen's kind of small.
[16:43] SPEAKER: It's this processor's too slow.
[16:45] SPEAKER: The keyboard's compressed.
[16:47] SPEAKER: So it's like, they fit into this space,
[16:49] SPEAKER: but it makes a bunch of compromises.
[16:50] SPEAKER: And at this point, you're like,
[16:51] SPEAKER: well, they're about to show something
[16:53] SPEAKER: that they don't think has any compromises.
[16:55] SPEAKER: I mean, those of us who bought one of those MacBook Airs
[16:57] SPEAKER: know the compromises were real.
[16:59] SPEAKER: But the point is, he gets to this whole thing
[17:01] SPEAKER: and he's like, and you know,
[17:03] SPEAKER: here's how it fits into the,
[17:06] SPEAKER: here's the physical profile of this Sony laptop that I like.
[17:11] SPEAKER: And then here's the physical cross section
[17:13] SPEAKER: of our MacBook Air, and it's smaller.
[17:16] SPEAKER: And it's not just smaller when you line up the wedge,
[17:19] SPEAKER: 'cause it's wedge shaped like a piece of cheese.
[17:21] SPEAKER: It's not just smaller when you line up the cheese
[17:23] SPEAKER: the same way, but if you flip the cheese around
[17:25] SPEAKER: so the thick side is next to the thin side of one,
[17:28] SPEAKER: it's smaller that way, too.
[17:30] SPEAKER: And then he does this thing where he gets the manila envelope.
[17:34] SPEAKER: He's like, it's so small.
[17:35] SPEAKER: In fact, you can put it in the manila envelope.
[17:37] SPEAKER: They put the manila envelope up on the screen.
[17:39] SPEAKER: Everybody laughs.
[17:40] SPEAKER: He waits a beat.
[17:41] SPEAKER: And he says, in fact, I'm gonna go, let me show you one.
[17:44] SPEAKER: And he walks over and he grabs one
[17:47] SPEAKER: that's been sitting there the entire time
[17:48] SPEAKER: on this high boy table on the stage where his water is.
[17:51] SPEAKER: And he picks up the manila envelope, and he waits a beat.
[17:56] SPEAKER: And the audience kind of does an uneasy chuckle.
[17:59] SPEAKER: They're not sure if they should clap
[18:00] SPEAKER: for the manila envelope.
[18:02] SPEAKER: - There's a bit of a lean forward in your chair.
[18:04] SPEAKER: - Right, they're like, something's gonna happen.
[18:06] SPEAKER: But the thing, and he does this all the way through it.
[18:10] SPEAKER: He does it in the lead in for the segment.
[18:11] SPEAKER: He's like, there's something in the air.
[18:13] SPEAKER: And everybody's like, oh, here it comes.
[18:15] SPEAKER: 'Cause at this point he's trained them
[18:16] SPEAKER: to wait for the thing at the end that's the good thing.
[18:19] SPEAKER: - Carney really is the right word.
[18:21] SPEAKER: - I mean, it is Carney, P.T. Barnum timing, right?
[18:25] SPEAKER: - Yeah, sure.
[18:26] SPEAKER: I mean, even there you can see the contrast
[18:28] SPEAKER: between when he's talking about the Sony laptop,
[18:29] SPEAKER: it's a bunch of boring dimensions and stats
[18:32] SPEAKER: and numbers on screen and diagrams of thickness.
[18:35] SPEAKER: And then when he's ready to show their product,
[18:37] SPEAKER: here it is in front of you in this very stage managed,
[18:41] SPEAKER: it's almost like a magic trick.
[18:42] SPEAKER: It's almost, hey, I'm gonna pull a laptop out of this hat.
[18:46] SPEAKER: - So he does this all the way through, right?
[18:48] SPEAKER: He does it when he starts the segment,
[18:51] SPEAKER: 'cause he knows that people are waiting
[18:52] SPEAKER: to see if there's gonna be the one more thing at the end.
[18:55] SPEAKER: And it's like, it's again, it's the Carney timing.
[18:57] SPEAKER: He's giving, he's established the norms.
[18:59] SPEAKER: He tells them what they're excited about.
[19:01] SPEAKER: And it shows at the end when he puts a manila envelope
[19:05] SPEAKER: up on the screen and people aren't sure
[19:06] SPEAKER: if they should clap for the manila envelope.
[19:08] SPEAKER: It's also, as an aside, I don't think a 25 year old
[19:13] SPEAKER: who's just entered the workforce sees one of those things.
[19:15] SPEAKER: Like that was the most common, mundane thing
[19:16] SPEAKER: in the world then.
[19:17] SPEAKER: And now I haven't seen it in our office memo envelope
[19:21] SPEAKER: in like 10 years at this point.
[19:22] SPEAKER: - Sure, yeah, so I stuck the 2007 iPhone reveal
[19:25] SPEAKER: right at the top of this
[19:26] SPEAKER: for all the reasons we have just described.
[19:28] SPEAKER: I'm sure people have seen it quite a bit and remember it
[19:30] SPEAKER: and we don't have to get too deep into it,
[19:32] SPEAKER: but he kicks it off with another one
[19:33] SPEAKER: of those great stage tricks of, first of all,
[19:35] SPEAKER: this was the, was this a Macworld keynote or WW, or did-
[19:40] SPEAKER: - This one is maybe its own thing.
[19:41] SPEAKER: It was in March.
[19:42] SPEAKER: - Okay, the context I don't have for this
[19:44] SPEAKER: is what people knew going into this.
[19:46] SPEAKER: I don't know.
[19:46] SPEAKER: - We knew that there was something coming.
[19:48] SPEAKER: We knew that they were doing a phone,
[19:49] SPEAKER: but we didn't know a whole lot else other than that.
[19:51] SPEAKER: - Have they said they were doing a phone?
[19:53] SPEAKER: - No, of course not.
[19:54] SPEAKER: - Okay, that's what it is, so-
[19:55] SPEAKER: - No murder was in full effect.
[19:56] SPEAKER: (laughing)
[19:57] SPEAKER: - Right?
[20:00] SPEAKER: From the Apple code of silence.
[20:02] SPEAKER: - It was Macworld, just Macworld 2007 in May of 2013.
[20:07] SPEAKER: - Yeah, so he does another one of the stage tricks of,
[20:09] SPEAKER: hey, we're actually announcing three products today,
[20:11] SPEAKER: a touch, a widescreen touch iPod,
[20:15] SPEAKER: a revolutionary new mobile phone,
[20:18] SPEAKER: and a never before seen internet communicator, whatever.
[20:20] SPEAKER: It's like there are icons on the screen
[20:22] SPEAKER: for all of these things, and then there's a quick-
[20:24] SPEAKER: - He goes through each one, like each bullet point, right?
[20:26] SPEAKER: - Yeah, a little bit, a little bit.
[20:27] SPEAKER: But I mean, it's again, it's like,
[20:29] SPEAKER: God, it's like Carney magician shit.
[20:30] SPEAKER: I mean, it's almost literal sleight of hand
[20:32] SPEAKER: on the screen of the icons whirling around each other
[20:36] SPEAKER: until he's just like, are you getting it yet?
[20:38] SPEAKER: This is actually one product.
[20:40] SPEAKER: - Look, man, in the naughtiest twists were really hot.
[20:43] SPEAKER: M. Night Shyamalan was just blowing up.
[20:46] SPEAKER: We were all about that twist.
[20:47] SPEAKER: We had people we're excited about, lost, whatever.
[20:50] SPEAKER: I don't know.
[20:51] SPEAKER: But yeah, it was, he played the audience.
[20:54] SPEAKER: He played to the audience in a way that typically
[20:59] SPEAKER: nerds in business suits at computer conventions did not.
[21:03] SPEAKER: - Yeah, it makes me wonder watching that moment.
[21:05] SPEAKER: I mean, it's so incredibly obvious in hindsight
[21:07] SPEAKER: when he says, hey, we're doing three products.
[21:09] SPEAKER: Like, it's so obvious he's talking about an iPhone,
[21:10] SPEAKER: but at the time, without the context of what the iPhone was
[21:14] SPEAKER: and would become, like, I wonder how many people,
[21:16] SPEAKER: and it's like a five minute spread,
[21:17] SPEAKER: but I wonder how many people bought that
[21:18] SPEAKER: for the five minutes between him saying,
[21:20] SPEAKER: it's three products, no, it's one.
[21:22] SPEAKER: - Well, but at the time, like the widescreen iPod,
[21:26] SPEAKER: like that was a huge screen for a mobile device.
[21:28] SPEAKER: The fact that you could have a full web browser
[21:31] SPEAKER: in your pocket was shocking.
[21:33] SPEAKER: And like, you know--
[21:36] SPEAKER: - And also phones didn't do all the things
[21:38] SPEAKER: that he was saying this would do, you know?
[21:39] SPEAKER: Like smartphones as defined by the iPhone,
[21:42] SPEAKER: like as music players, as video players, as web browsers,
[21:45] SPEAKER: like, you know, it was not immediately obvious
[21:47] SPEAKER: that he was talking about one phone.
[21:48] SPEAKER: - Look, when he showed the visual voicemail stuff
[21:51] SPEAKER: where you could like connect to your voicemail system
[21:54] SPEAKER: and see a list of all the voicemail message you had
[21:56] SPEAKER: and hit play on a touchscreen,
[21:58] SPEAKER: do like just the multi-touch seemed like magic.
[22:00] SPEAKER: That was novel.
[22:01] SPEAKER: But like, hey, you don't have to dial star whatever
[22:04] SPEAKER: to get your voicemail and then listen to a menu
[22:07] SPEAKER: and be like, press one for the next one, press two to delete.
[22:10] SPEAKER: That was amazing.
[22:11] SPEAKER: That was like, that was the reason I wanted an iPhone,
[22:14] SPEAKER: honestly, 'cause he got a boatload of voicemail at the time.
[22:17] SPEAKER: - Yeah. - Anyway.
[22:17] SPEAKER: - Yeah, anyway, watching this,
[22:19] SPEAKER: it's pretty easy to put yourself back in the 2007 mindset
[22:21] SPEAKER: because they show off all the competition at this point
[22:24] SPEAKER: and they all have giant plastic keyboards
[22:25] SPEAKER: taking up a third of the form factor.
[22:27] SPEAKER: - Yep.
[22:28] SPEAKER: - You know, they have to rule out,
[22:29] SPEAKER: does this, do you need a stylus for this or not?
[22:30] SPEAKER: No, we've created something called multi-touch.
[22:32] SPEAKER: Like that's how early this was that, you know,
[22:34] SPEAKER: none of that stuff was in the common language at that point.
[22:36] SPEAKER: You know, there was also the moment where like,
[22:38] SPEAKER: hey, it runs OS X, by the way.
[22:40] SPEAKER: - So to contrast that with the famous, the iPhone 4,
[22:45] SPEAKER: I think it's WWDC in 2009, probably,
[22:51] SPEAKER: where he tries to do the demo
[22:53] SPEAKER: and show the page running on the,
[22:55] SPEAKER: pages running on two iPhones and the wifi stops working.
[23:00] SPEAKER: And the wifi stops working because in three years,
[23:03] SPEAKER: this is two and a half, three years from that iPhone launch,
[23:07] SPEAKER: every single person in this keynote address,
[23:10] SPEAKER: or not everybody, but he said there were
[23:12] SPEAKER: 570 some wifi hotspots, little boxes with a cellular radio,
[23:18] SPEAKER: a wifi antenna, and a battery
[23:21] SPEAKER: that people were using to get internet for their laptops
[23:24] SPEAKER: so they could do live blogs and whatever
[23:26] SPEAKER: in this keynote address, which was really funny
[23:29] SPEAKER: 'cause like two years before that, I had gone with Brian Lamb
[23:34] SPEAKER: of Gizmodo and we had done the first live blog for,
[23:38] SPEAKER: with photos using one of those same hotspots
[23:41] SPEAKER: and we were one of three people who had one
[23:42] SPEAKER: 'cause nobody knew they existed before them.
[23:45] SPEAKER: Anyway, but he handles the demo fail pretty well.
[23:48] SPEAKER: Like he doesn't flip out,
[23:48] SPEAKER: he doesn't throw a tantrum or anything.
[23:50] SPEAKER: He says, we'll come back to this later, moves on,
[23:53] SPEAKER: and then comes back and is like, hey, here's the deal.
[23:56] SPEAKER: If you wanna see this, we can, if you don't wanna see this,
[23:59] SPEAKER: it's fine, but if you do wanna see this,
[24:00] SPEAKER: some of you have to turn off your wifi hotspots
[24:03] SPEAKER: so that I can do the demo 'cause it's not like,
[24:05] SPEAKER: wifi does not work with 500 radios in a small amount,
[24:08] SPEAKER: 500 access points in a small amount of space.
[24:11] SPEAKER: It's an interesting contrast.
[24:14] SPEAKER: - Yeah, for sure.
[24:15] SPEAKER: And it highlights that element of risk, right?
[24:17] SPEAKER: Like there's a case where the risk kind of didn't pay off,
[24:20] SPEAKER: but also I kind of feel like the bona fides
[24:22] SPEAKER: that are established by something failing on stage
[24:25] SPEAKER: are almost worth it.
[24:27] SPEAKER: - Well, it's like look at the uncharted two one, right?
[24:29] SPEAKER: - Yeah, is that the one where the controller
[24:31] SPEAKER: didn't disconnect it or the Bluetooth failed or something?
[24:33] SPEAKER: - They had to do a fail, they had a failover.
[24:35] SPEAKER: Like they were prepared for it, right?
[24:37] SPEAKER: So they, part of their planning was
[24:38] SPEAKER: we're gonna have multiple machines set up
[24:39] SPEAKER: in exactly the right state.
[24:40] SPEAKER: We can just switch to the failover one
[24:42] SPEAKER: and it'll be fine, right?
[24:46] SPEAKER: Now to contrast that with the Google Glass unveil
[24:49] SPEAKER: at the Moscone Center, this one is interesting
[24:53] SPEAKER: because it has an actual element of physical danger.
[24:55] SPEAKER: I think this is the only one of these
[24:57] SPEAKER: that we have on this list
[24:58] SPEAKER: where people could have actually died.
[25:01] SPEAKER: And it's maybe the most tedious of them all.
[25:04] SPEAKER: So, Sergey Brin's on the stage.
[25:07] SPEAKER: He cuts in to somebody else's presentation
[25:10] SPEAKER: midway through this reveal.
[25:13] SPEAKER: And he's like, "Hey, sorry, we got some stuff
[25:14] SPEAKER: "that's time dependent."
[25:15] SPEAKER: And then has to wait like three minutes
[25:17] SPEAKER: for the thing to be ready to go, right?
[25:21] SPEAKER: So you're like, "Hey, I gotta cut in.
[25:23] SPEAKER: "I'm sorry, I'm sorry, sorry."
[25:25] SPEAKER: And then wait some more.
[25:28] SPEAKER: What he's waiting for is for some people
[25:30] SPEAKER: in squirrel suits to get their dirigible
[25:33] SPEAKER: in place above Moscone Center
[25:35] SPEAKER: so they can jump out of the dirigible
[25:37] SPEAKER: and then zoop down and parachute
[25:40] SPEAKER: onto the roof of Moscone Center.
[25:41] SPEAKER: Now, that sounds cool 'cause they're like,
[25:43] SPEAKER: "We're gonna do this, the parachutists
[25:45] SPEAKER: "are all wearing Google Glass
[25:46] SPEAKER: "and we're gonna hang out with them
[25:48] SPEAKER: "so you can be able to see exactly what they see
[25:49] SPEAKER: "like you're there."
[25:50] SPEAKER: Now, it was 4G, internet, the video quality,
[25:55] SPEAKER: maybe not the best.
[25:57] SPEAKER: But it did work and it was cool.
[25:59] SPEAKER: That part was cool.
[25:59] SPEAKER: You're like, "Man, this is awesome.
[26:00] SPEAKER: "A lot of waiting, but this is cool."
[26:02] SPEAKER: And then they land and you're like,
[26:03] SPEAKER: "Oh man, they almost hit the Intercontinental Hotel
[26:07] SPEAKER: "'cause it's new and it's down there."
[26:08] SPEAKER: And they gotta swerve around the building
[26:10] SPEAKER: and that looks scary.
[26:11] SPEAKER: Man, what if they miss the building?
[26:12] SPEAKER: These guys could really die.
[26:13] SPEAKER: This seems really dangerous.
[26:14] SPEAKER: Moscone is a tall building.
[26:16] SPEAKER: It's not like if they miss the roof
[26:19] SPEAKER: and get hooked up or something.
[26:20] SPEAKER: It could be really dangerous.
[26:22] SPEAKER: So then, they land on the roof
[26:25] SPEAKER: and Sergey's like, and because,
[26:28] SPEAKER: and they have this whole framing for this stunt, right?
[26:32] SPEAKER: First off, the only thing that they're showing
[26:34] SPEAKER: is that they can do Google Hangouts
[26:36] SPEAKER: while you're doing this.
[26:37] SPEAKER: - Right.
[26:39] SPEAKER: - They have this whole framing for the stunt.
[26:40] SPEAKER: They're like, "I gotta get my headset back
[26:42] SPEAKER: "from my bro on the dirigible with the squirrel suit on
[26:45] SPEAKER: "ready to jump out and land on the building
[26:47] SPEAKER: "that I happen to be in."
[26:49] SPEAKER: And they're like, "We're gonna have some bicyclists run
[26:53] SPEAKER: "'cause the building's really wide
[26:55] SPEAKER: "and we're gonna have the bicyclists take the package
[26:57] SPEAKER: "and run it along."
[26:58] SPEAKER: So they ride the bicycles.
[27:00] SPEAKER: They do some sick flips and stuff
[27:02] SPEAKER: but there's clearly jumps placed there for them
[27:04] SPEAKER: because, you know, absolutely a stunt.
[27:07] SPEAKER: And then they get to the edge of the building.
[27:08] SPEAKER: You're like, "Oh, thank God.
[27:09] SPEAKER: "There's probably a stairway or something."
[27:10] SPEAKER: No.
[27:11] SPEAKER: No, they got the repellers.
[27:14] SPEAKER: They got the repel people
[27:16] SPEAKER: and they clip in on the side of the building
[27:18] SPEAKER: and they run down the building.
[27:19] SPEAKER: But one of them, some of them go to the ground
[27:22] SPEAKER: but one guy stops at the third floor where the keynote is
[27:25] SPEAKER: and then he gets in and hands the headset back to another.
[27:29] SPEAKER: See, you look bored with me just describing this.
[27:31] SPEAKER: This is taking way less time than it took them to do it.
[27:33] SPEAKER: - It's like 15 minutes, right?
[27:34] SPEAKER: - Yeah, it's like 10 or 15 minutes.
[27:35] SPEAKER: He hands the package to another bicycle guy
[27:38] SPEAKER: who weaves in and out through the crowd
[27:40] SPEAKER: of the actual attendees all on the Google Hangouts
[27:45] SPEAKER: and then they get to the stage.
[27:46] SPEAKER: And when they get to the stage,
[27:47] SPEAKER: they cut back to the real camera.
[27:48] SPEAKER: You're like, "Oh, thank God I can see stuff again
[27:50] SPEAKER: "'cause everything was not blocky and shitty."
[27:52] SPEAKER: - And two frames a second.
[27:54] SPEAKER: - Yeah, and five frames a second.
[27:55] SPEAKER: So they take something that should be super cool
[27:58] SPEAKER: and just stretch it out
[27:59] SPEAKER: and put this stupid framing thing on it.
[28:01] SPEAKER: And also they only show one cool thing, right?
[28:04] SPEAKER: The Google Hangouts from the plane was cool
[28:07] SPEAKER: for like while they were parachuting down
[28:09] SPEAKER: and then no other point was, anyway.
[28:11] SPEAKER: - Hangouting while parachuting sounds cool on paper
[28:14] SPEAKER: but sometimes when you're planning your stage demo,
[28:17] SPEAKER: maybe you step back and think through the implications
[28:19] SPEAKER: of the stunt you're trying to pull off
[28:20] SPEAKER: and not whether you can do it or not,
[28:22] SPEAKER: but whether you should.
[28:25] SPEAKER: Whether it's actually going to be entertaining
[28:26] SPEAKER: for people to sit there and watch what is required
[28:28] SPEAKER: to make this happen.
[28:29] SPEAKER: - Oh yes, the Goldblum conjecture.
[28:32] SPEAKER: - Yes.
[28:33] SPEAKER: - So okay, so here's another good one though.
[28:35] SPEAKER: We got some good ones.
[28:36] SPEAKER: The source engine demo
[28:37] SPEAKER: from the Half-Life 2 E3 press conference.
[28:40] SPEAKER: - Yeah, so there's like a short list here
[28:42] SPEAKER: of ones that still work for me in a modern context
[28:44] SPEAKER: in terms of are they exciting to watch or not.
[28:47] SPEAKER: I didn't expect this 'cause I saw this live at E3
[28:50] SPEAKER: and of course a video came out
[28:52] SPEAKER: that I watched a hundred times after that.
[28:53] SPEAKER: But yeah, the source engine slash Half-Life 2 demo
[28:56] SPEAKER: from 2003, I think actually tops my list on here.
[29:00] SPEAKER: - It's still rad.
[29:01] SPEAKER: - Like, and part of that, I mean, part of it is
[29:03] SPEAKER: like there's so much advanced video game technology
[29:06] SPEAKER: that you basically had never seen before
[29:07] SPEAKER: in the space of about 10 minutes.
[29:09] SPEAKER: It's not any one thing, it's all of it
[29:11] SPEAKER: 'cause there's like eight different new things there.
[29:13] SPEAKER: But the other thing is like,
[29:15] SPEAKER: why aren't more games doing this stuff today?
[29:18] SPEAKER: Like, I mean, I know some of the practical answers to that
[29:21] SPEAKER: are, you know, it's a lot of work
[29:22] SPEAKER: and maybe there's not as much demand for it now,
[29:24] SPEAKER: but like the material system, the advanced physics.
[29:29] SPEAKER: - Well, everybody does material system now, right?
[29:31] SPEAKER: Like most of the stuff is just table stakes now.
[29:35] SPEAKER: - But the level of different materials
[29:38] SPEAKER: being simulated in this,
[29:39] SPEAKER: maybe we should describe briefly what it is
[29:42] SPEAKER: before we get into it.
[29:43] SPEAKER: Like they, it's split up into two chunks.
[29:45] SPEAKER: The kind of back two thirds of the demo
[29:48] SPEAKER: are them just playing scenes from Half-Life 2.
[29:50] SPEAKER: - Yeah, that's the least interesting part of it though.
[29:52] SPEAKER: - I guess, but it's really the first like 10 minutes
[29:53] SPEAKER: where they have, they basically made a custom map
[29:55] SPEAKER: that is just kind of a fun house
[29:57] SPEAKER: of engine technology features.
[29:59] SPEAKER: And that's the stuff that's exciting.
[30:01] SPEAKER: But like, so it's a lot of physics simulation.
[30:04] SPEAKER: It's like deformable terrain.
[30:07] SPEAKER: It has a lot of materials which tie into the physics
[30:08] SPEAKER: 'cause there's like breakable wood,
[30:10] SPEAKER: there's breakable glass, there are mattresses that deform.
[30:13] SPEAKER: And that's kind of what I was getting at is that like,
[30:14] SPEAKER: you're not seeing that range
[30:15] SPEAKER: of material simulation these days.
[30:18] SPEAKER: It's mostly like some things are breakable
[30:19] SPEAKER: and that's about it.
[30:20] SPEAKER: But like games where like all the wood can be broken
[30:23] SPEAKER: and the structures fall apart or, you know,
[30:25] SPEAKER: like this whatever kind of soft body mattress thing
[30:28] SPEAKER: that they're doing is, you know,
[30:29] SPEAKER: like you don't see as much of that these days.
[30:30] SPEAKER: - So a lot of games have the soft body stuff
[30:33] SPEAKER: and they just don't, you don't have verbs in the game
[30:35] SPEAKER: that let you see the things that like the gravity gun
[30:37] SPEAKER: and Half-Life let you do.
[30:39] SPEAKER: - Yeah, it's fair to a degree, I guess.
[30:40] SPEAKER: - Yeah, the destructible stuff is hard
[30:44] SPEAKER: because you have to make multiple stages
[30:46] SPEAKER: of destruction, right?
[30:48] SPEAKER: So you're multiplying your art assets.
[30:49] SPEAKER: So it's a triple A thing rather than an indie thing.
[30:52] SPEAKER: But like this demo opens on the-
[30:57] SPEAKER: - G-Man.
[30:58] SPEAKER: - G-Man, thank you.
[30:58] SPEAKER: I was gonna say cigarette smoking man, but that's X-Files.
[31:01] SPEAKER: - That's the one they ripped off.
[31:02] SPEAKER: - Yeah, it starts off with like the 1997 Half-Life 1 version
[31:07] SPEAKER: of him and then it cuts to the source engine version
[31:11] SPEAKER: where he has like muscles under the skin.
[31:13] SPEAKER: He has deformable mesh face.
[31:15] SPEAKER: His lip flap is tied to phony muse, his eyes glint
[31:18] SPEAKER: and he has saccades and all the things
[31:20] SPEAKER: that make him look more like a real human.
[31:22] SPEAKER: - Like there's eye tracking with the camera, you know,
[31:23] SPEAKER: like it's just all this stuff that you had never seen
[31:25] SPEAKER: in human characters in video games up to this point,
[31:28] SPEAKER: all happening in one character.
[31:29] SPEAKER: - And it's a full like minute and a half
[31:31] SPEAKER: of you just looking at the face.
[31:32] SPEAKER: It's intense.
[31:34] SPEAKER: - This video we linked is from GameSpy.
[31:36] SPEAKER: From way back then they recorded the video
[31:38] SPEAKER: or the demo while they were in there.
[31:39] SPEAKER: And you can like, you can literally hear people gasp
[31:41] SPEAKER: when they cut to the 2004 G-Man.
[31:44] SPEAKER: - But then they go to like deformable,
[31:46] SPEAKER: they show some deformable terrain.
[31:47] SPEAKER: They show the collision on the terrain deforming
[31:50] SPEAKER: at the same time, which was, that was a lot back then.
[31:54] SPEAKER: And then they show like you using destructible brushes,
[31:59] SPEAKER: basically like shooting pieces of wood
[32:01] SPEAKER: to make things happen in the world that are physics-y.
[32:03] SPEAKER: So like knocking some barrels into the water,
[32:07] SPEAKER: playing pachinko that they've set up on the wall
[32:09] SPEAKER: by rolling barrels down a ramp
[32:11] SPEAKER: and into a series of pegs on the side of the wall.
[32:14] SPEAKER: And then they whip out the gravity gun
[32:16] SPEAKER: and start winging stuff around.
[32:18] SPEAKER: And you're just like, wait, what?
[32:19] SPEAKER: This is, I've never seen anything like this before.
[32:22] SPEAKER: They show like specular surfaces, all different reflections,
[32:26] SPEAKER: different ways lighting affects things like glass and water.
[32:29] SPEAKER: - I mean, I love this bit where they just made a bunch
[32:31] SPEAKER: of extremely fake arbitrary slabs hanging from the ceiling,
[32:34] SPEAKER: just to show off different shader effects.
[32:36] SPEAKER: - Yeah.
[32:37] SPEAKER: - Like it's like the artificialness of it
[32:40] SPEAKER: is what makes it so exciting to me.
[32:41] SPEAKER: It's not like, hey, here's all this stuff
[32:43] SPEAKER: in context in the game.
[32:44] SPEAKER: Here are extremely blatant, obvious examples
[32:48] SPEAKER: of how it works and why.
[32:49] SPEAKER: - Well, so a lot of times you'll do these demo levels
[32:52] SPEAKER: to show how you can use stuff.
[32:54] SPEAKER: So your artists can show each other,
[32:56] SPEAKER: hey, I figured out a new way to do something cool.
[32:58] SPEAKER: You should check this out.
[32:59] SPEAKER: - Yeah, I mean, there's one room in here,
[33:00] SPEAKER: like the least likely thing you would probably ever do
[33:02] SPEAKER: with this stuff is a person made out of water.
[33:05] SPEAKER: - Yeah, well, except for the abyss.
[33:08] SPEAKER: - Unless you're making an abyss game.
[33:09] SPEAKER: - Yeah, or that Janet Jackson music video with Busta Rhymes.
[33:13] SPEAKER: - Fair, fair.
[33:14] SPEAKER: - Yeah, so yeah, this was, I remember sitting through this
[33:19] SPEAKER: and it was all I could do.
[33:21] SPEAKER: I was just writing down notes furiously the whole time
[33:24] SPEAKER: I was watching this at E3 and I couldn't stop.
[33:29] SPEAKER: Like I couldn't keep up to the point that I missed
[33:32] SPEAKER: the first couple of minutes of this Half-Life demo
[33:34] SPEAKER: 'cause I was still trying desperately to write down
[33:36] SPEAKER: everything that they had shown in the engine side.
[33:38] SPEAKER: - It's a really insane encapsulation
[33:40] SPEAKER: of the entire future of video games in less than 10 minutes.
[33:44] SPEAKER: - Yeah, and like I said, it's all stuff that's table stakes.
[33:46] SPEAKER: Now, the one thing that nobody does is the physics weapon
[33:49] SPEAKER: because it's a pain in the ass, makes testing really hard.
[33:52] SPEAKER: - Yeah, I thought about throwing the Doom 3 demo
[33:55] SPEAKER: from around this era.
[33:56] SPEAKER: I think it was 2004 maybe in there.
[33:59] SPEAKER: It's funny, like at the time I was more wowed
[34:03] SPEAKER: by the Doom 3 demo, but it's purely graphics.
[34:06] SPEAKER: It's like shadow, it's lighting and shadowing
[34:07] SPEAKER: and like the really detailed environments
[34:09] SPEAKER: and like environmental animation and stuff like that.
[34:11] SPEAKER: But it's not the character stuff.
[34:13] SPEAKER: It's not the physics as much.
[34:17] SPEAKER: Like the Half-Life demo is much more of a total package
[34:20] SPEAKER: of here is advanced technology that's going to affect
[34:22] SPEAKER: both look and the gameplay and the Doom 3 stuff
[34:25] SPEAKER: is a lot more just look.
[34:27] SPEAKER: - Yeah, well, I mean, the thing about Doom 3
[34:30] SPEAKER: is he shows a lot of moving lights and dynamic shadows.
[34:33] SPEAKER: And that was novel.
[34:35] SPEAKER: - And a lot of heavy machinery animating in the environment
[34:37] SPEAKER: which was also pretty novel and advanced at the time.
[34:39] SPEAKER: But like going back now, like watching that Half-Life 2 demo
[34:43] SPEAKER: is still kind of exhilarating.
[34:46] SPEAKER: Like it's still kind of easy to remember being in that time
[34:49] SPEAKER: and seeing all that stuff for the first time
[34:50] SPEAKER: and feeling like you were like the AT&T stuff,
[34:52] SPEAKER: it's like you're literally looking at the future.
[34:54] SPEAKER: - Well, and it was stuff that impacted gameplay,
[34:56] SPEAKER: just not just what it looks like.
[34:58] SPEAKER: You know, at the end of the day,
[34:59] SPEAKER: that Doom 3 demo showed you more Doom
[35:01] SPEAKER: where you run through quarters and you shoot stuff.
[35:03] SPEAKER: And the Half-Life thing showed you a world
[35:04] SPEAKER: that you could interact with
[35:05] SPEAKER: in a way that we'd never interacted with video games before.
[35:07] SPEAKER: Which was cool.
[35:08] SPEAKER: - Yeah, and characters, human characters also
[35:10] SPEAKER: that felt realistic and interactive.
[35:13] SPEAKER: - People we could talk to.
[35:15] SPEAKER: What do you want to do now?
[35:16] SPEAKER: You want to go to a PlayStation Move maybe?
[35:19] SPEAKER: - Yeah, yeah, so.
[35:21] SPEAKER: - In my head, this is the Jeremy demo.
[35:23] SPEAKER: - Okay, sure.
[35:24] SPEAKER: - This is a GDC 2010 unveil and they did it.
[35:28] SPEAKER: They showed a canned trailer first
[35:30] SPEAKER: and then they showed some like stage demos.
[35:32] SPEAKER: - Yeah, so the canned trailer is,
[35:34] SPEAKER: I think is probably a good example
[35:35] SPEAKER: of the fake living room style of thing
[35:37] SPEAKER: I was talking about before.
[35:38] SPEAKER: - Yeah, this was definitely informed by the Wii,
[35:40] SPEAKER: the early Wii ads where they were showing grandmas
[35:42] SPEAKER: playing bowling and conducting the orchestra
[35:44] SPEAKER: and stuff like that.
[35:45] SPEAKER: - Yeah, I mean, there's a hole in the press conferences
[35:48] SPEAKER: and demos and trailers from this era
[35:50] SPEAKER: showing motion controls of various types
[35:52] SPEAKER: 'cause that was the thing.
[35:53] SPEAKER: - Throw pickle at wall.
[35:55] SPEAKER: Yeah, everybody had fun.
[35:56] SPEAKER: Look, I'm not gonna lie,
[35:58] SPEAKER: I took my Wii home several Christmases in a row
[36:01] SPEAKER: and the whole family, including the grandmother,
[36:03] SPEAKER: would stand up and we would bowl
[36:05] SPEAKER: and we would play tennis and we would play baseball.
[36:06] SPEAKER: It was great, it was wonderful.
[36:08] SPEAKER: - Who didn't do that?
[36:09] SPEAKER: - Yeah, it was maybe that and karaoke revolution
[36:12] SPEAKER: are the two times I've had fun playing video games
[36:14] SPEAKER: with my entire family.
[36:15] SPEAKER: - Yep, yep, 100%.
[36:17] SPEAKER: - But this one was pretty good because they,
[36:20] SPEAKER: so they were late, right?
[36:22] SPEAKER: Like the PlayStation move was three years
[36:24] SPEAKER: after the Wii had launched.
[36:26] SPEAKER: - Four years after the Wii had launched.
[36:27] SPEAKER: - Yeah, Wii was late 2006 and this was 2010 for the reveal.
[36:32] SPEAKER: I don't remember when the move came out.
[36:33] SPEAKER: Yes, they were late, yes.
[36:35] SPEAKER: - There's a whole sequence of this
[36:37] SPEAKER: after they show the trailer and they show like ping pong
[36:39] SPEAKER: and they talk about how awesome ping pong is.
[36:41] SPEAKER: And then they have Jeremy come out
[36:45] SPEAKER: off the side of the stage and he plays ping pong
[36:49] SPEAKER: for maybe 25 seconds each.
[36:51] SPEAKER: Like he plays each game for like 25 seconds.
[36:53] SPEAKER: They do table tennis, you see him playing,
[36:57] SPEAKER: there's a fern in the background so you know it's real.
[37:00] SPEAKER: It's like, it's around the 24 minute, 25 minute mark
[37:03] SPEAKER: of that Sony press conference video in the show notes.
[37:07] SPEAKER: The best one though is when he gets out
[37:10] SPEAKER: and I think he has Nancy play PlayStation move party
[37:14] SPEAKER: which is like their party game where you have to like
[37:15] SPEAKER: get your picture in the picture frame,
[37:17] SPEAKER: you have to say your name, you have to do all the stuff
[37:18] SPEAKER: that you have to do to make a party game.
[37:22] SPEAKER: And then poor Nancy is playing for like,
[37:27] SPEAKER: she does each thing once and then he's like,
[37:28] SPEAKER: okay, we gotta move on to the next one,
[37:30] SPEAKER: we gotta move on to the next one,
[37:31] SPEAKER: we gotta move on to the next one.
[37:32] SPEAKER: And they're just hammering through these demos so, so fast.
[37:37] SPEAKER: It's like, hey, we have exactly 60 minutes
[37:39] SPEAKER: before we have to clear this room.
[37:41] SPEAKER: And if we go over one minute and also we're already running
[37:44] SPEAKER: six minutes late on this 60 minute conference.
[37:48] SPEAKER: So yeah, it's a trip, this one, I'm...
[37:51] SPEAKER: - Yeah, I also, I threw what I think is a famous tech demo
[37:56] SPEAKER: on the far other end of the spectrum from this,
[37:58] SPEAKER: which is Johnny Lee, who I think was a researcher
[38:01] SPEAKER: at the time at Carnegie Mellon.
[38:02] SPEAKER: - God, that one's so good.
[38:03] SPEAKER: - You remember this?
[38:04] SPEAKER: - Yeah.
[38:05] SPEAKER: - I feel like I remember this just like setting the,
[38:07] SPEAKER: this was like kind of pre social media
[38:09] SPEAKER: or maybe when social media
[38:10] SPEAKER: was just really starting to take off.
[38:12] SPEAKER: This kind of set the internet on fire.
[38:13] SPEAKER: It's the guy who set up infrared based head tracking
[38:17] SPEAKER: with Wii remotes and basically just off the shelf technology
[38:21] SPEAKER: that he cobbled together.
[38:22] SPEAKER: - This came out after the Wii had been on available
[38:25] SPEAKER: for like a year.
[38:26] SPEAKER: - Right.
[38:26] SPEAKER: And it's head tracking with the TV as a view port.
[38:30] SPEAKER: And like, we're not talking about a VR headset of any kind.
[38:32] SPEAKER: It's literally just him basically strapping a Wiimote
[38:34] SPEAKER: to the side of his head and walking around
[38:36] SPEAKER: in his living room or in this case, the camera.
[38:38] SPEAKER: He straps the Wiimote to the camera.
[38:40] SPEAKER: - I thought he did a sensor bar, doesn't he?
[38:44] SPEAKER: - Yeah, yeah, yeah, the sensor bar is involved.
[38:45] SPEAKER: So it's for the...
[38:46] SPEAKER: - Yes, he puts a sensor bar in his head
[38:47] SPEAKER: and- - Oh, is that what it is?
[38:48] SPEAKER: Oh, you're right, you're right.
[38:49] SPEAKER: It is the other way around.
[38:50] SPEAKER: It's the Wii remote is attached to the TV.
[38:52] SPEAKER: The sensor bar is the thing that moves.
[38:54] SPEAKER: - I mean, 'cause the sensor bar is just two infrared LEDs
[38:56] SPEAKER: that are a fixed distance apart, right?
[38:58] SPEAKER: There's nothing fancy about it.
[38:59] SPEAKER: But basically it allowed the game to render perceptual 3D
[39:06] SPEAKER: based on your head position in space,
[39:09] SPEAKER: which was really, really novel at the time.
[39:12] SPEAKER: So that he could make it look like things were popping out
[39:14] SPEAKER: of the screen, you could interact with them,
[39:15] SPEAKER: which was really cool.
[39:16] SPEAKER: - That really comes across in that video.
[39:17] SPEAKER: It's still fun to go back and watch this
[39:19] SPEAKER: for a couple of reasons.
[39:20] SPEAKER: For one thing, like I said,
[39:21] SPEAKER: it's on the complete other end of the spectrum
[39:23] SPEAKER: from all these stage demos,
[39:24] SPEAKER: because it's literally him in his living room
[39:26] SPEAKER: with his laptop set up under his TV.
[39:28] SPEAKER: I mean, it says no frills as it gets,
[39:30] SPEAKER: but that effect still works.
[39:31] SPEAKER: Like even an old low res YouTube video.
[39:34] SPEAKER: - Oh yeah, it's fabulous.
[39:35] SPEAKER: - And not being in the room.
[39:36] SPEAKER: I mean, like you still feel like you can see
[39:38] SPEAKER: those little red and white targets floating out of the TV
[39:41] SPEAKER: as he moves around.
[39:42] SPEAKER: Like it's kind of like the ultimate example to me
[39:44] SPEAKER: of the tech bringing all the goods.
[39:47] SPEAKER: Like it doesn't matter what the demo is like
[39:49] SPEAKER: when the tech is that good.
[39:50] SPEAKER: That's all that matters.
[39:51] SPEAKER: - Well, and it's funny 'cause it's the ultimate example.
[39:55] SPEAKER: Like this whole thing is kind of the example of,
[40:00] SPEAKER: this is the version of this.
[40:02] SPEAKER: I don't know if you've ever seen those guys
[40:03] SPEAKER: that do the chalk drawings on the sidewalk
[40:04] SPEAKER: that are like really stretched out and along.
[40:06] SPEAKER: And when you walk up to the street,
[40:06] SPEAKER: looks like there's somebody standing there.
[40:08] SPEAKER: - Yeah, the perspective stuff, yeah.
[40:10] SPEAKER: - So anyway, the thing that I do like about that move demo
[40:14] SPEAKER: that I really like is that they don't come out and say,
[40:16] SPEAKER: "Hey, we have gyroscopes and our stuff is gonna be better
[40:19] SPEAKER: 'cause we have a gyroscope."
[40:20] SPEAKER: 'Cause of course the Wii Motion Plus
[40:23] SPEAKER: was coming out around that time, I think.
[40:26] SPEAKER: But it wasn't super common.
[40:28] SPEAKER: It was an accessory you had to buy.
[40:30] SPEAKER: And they were highlighting it
[40:33] SPEAKER: and they were framing it in the way
[40:35] SPEAKER: that you would play the game, not as a technological thing.
[40:38] SPEAKER: So they were saying, "Hey, look, with this,
[40:39] SPEAKER: you can put top spin on your table tennis serves, right?
[40:43] SPEAKER: You can come over the top and the controller,
[40:45] SPEAKER: we'll pick that up.
[40:46] SPEAKER: You can do things like grab the,
[40:49] SPEAKER: you're not just waggling to reload stuff or whatever."
[40:52] SPEAKER: It was interesting.
[40:53] SPEAKER: Anyway, I love the Johnny Lee remote demo.
[40:58] SPEAKER: - That's great. - It's so good.
[40:59] SPEAKER: - It's great, it's still fun to watch.
[41:01] SPEAKER: - What else we got?
[41:04] SPEAKER: - Let's see, we've got a fair amount of like,
[41:06] SPEAKER: here are some new video game console footage reels,
[41:11] SPEAKER: I guess I would say.
[41:12] SPEAKER: Like here are the game consoles
[41:14] SPEAKER: and what they can do in some nondescript footage
[41:16] SPEAKER: that may or may not be a game,
[41:17] SPEAKER: or in some cases is extremely clearly not a game.
[41:21] SPEAKER: - Like, and just to be clear,
[41:23] SPEAKER: while I love and like really miss the days
[41:28] SPEAKER: of some poor bastard from the game studio,
[41:30] SPEAKER: having to stand behind people from Microsoft
[41:32] SPEAKER: and do connect dancing or whatever in the background,
[41:36] SPEAKER: we're not gonna talk about that.
[41:37] SPEAKER: - No, no, no, no.
[41:38] SPEAKER: - Those were bad for the most part.
[41:40] SPEAKER: - These are good demos.
[41:41] SPEAKER: These are legitimate demos.
[41:43] SPEAKER: All of these, I remember being quite exciting.
[41:44] SPEAKER: I very much miss this style
[41:47] SPEAKER: of new video game console tech demo.
[41:50] SPEAKER: - Yeah, people don't do it anymore, really.
[41:52] SPEAKER: It's mostly reels.
[41:54] SPEAKER: - Yeah, like maybe it's just because of the standards
[41:57] SPEAKER: and the bar are so much higher that,
[41:58] SPEAKER: 'cause like you remember the UE5 demo that they put out
[42:01] SPEAKER: where it's like, it's a very manicured,
[42:03] SPEAKER: I mean, it's legitimate footage,
[42:04] SPEAKER: but it looks like a CG movie.
[42:05] SPEAKER: It's not like, it's not as, you know,
[42:08] SPEAKER: like we will talk about in a minute,
[42:09] SPEAKER: it's not a bathtub full of 8,000 rubber ducks
[42:12] SPEAKER: flying everywhere.
[42:13] SPEAKER: It's a much more like,
[42:15] SPEAKER: here's something that looks like a video game.
[42:16] SPEAKER: You know what I mean?
[42:17] SPEAKER: - Well, yeah, it's funny you say that
[42:18] SPEAKER: 'cause like UE3 did,
[42:20] SPEAKER: like Unreal's done this for a long time.
[42:21] SPEAKER: Like they did the Samaritan demo for UE3.
[42:24] SPEAKER: They did the thing with the,
[42:26] SPEAKER: like with the bandana man from Gears of War
[42:29] SPEAKER: running down the busted ass street.
[42:31] SPEAKER: Like, anyway, yeah, so I wonder if these were a product
[42:36] SPEAKER: of just, hey, we have to come up with something
[42:37] SPEAKER: that shows off what the hardware can do
[42:39] SPEAKER: and here's the five assets we have in three days
[42:42] SPEAKER: to put this together, right?
[42:43] SPEAKER: - Yeah, I guess, you know,
[42:44] SPEAKER: some of these do feel pretty bare bones.
[42:46] SPEAKER: And also again, the bar was lower back then.
[42:47] SPEAKER: Like any amount of new technology, it was impressive.
[42:50] SPEAKER: - Yeah, like in the era when we were moving out
[42:52] SPEAKER: of early 3D stuff especially,
[42:54] SPEAKER: like anytime you got like,
[42:56] SPEAKER: when you got texture filtering on your 3D consoles,
[43:00] SPEAKER: things suddenly started looking a lot better.
[43:01] SPEAKER: - Right, right.
[43:03] SPEAKER: - So what do you, you wanna start with Space World?
[43:04] SPEAKER: - Yeah, like the key examples of this to me
[43:06] SPEAKER: are the 2000 Space World,
[43:08] SPEAKER: Shoshinkai was the show that Nintendo used to put on
[43:10] SPEAKER: in Japan to show off their new games
[43:12] SPEAKER: and technology in their own setting.
[43:16] SPEAKER: It's the extremely famous-
[43:17] SPEAKER: - Wait, they've been doing this that long?
[43:18] SPEAKER: - No, no, well, no, they stopped a long time ago.
[43:21] SPEAKER: God, when was the last Space World?
[43:22] SPEAKER: I can't even remember, like, 2001 actually.
[43:26] SPEAKER: The one after this was the last one.
[43:28] SPEAKER: They only did it for a few years.
[43:30] SPEAKER: Well, '89 to 2001 actually, I'd bring back Space World.
[43:33] SPEAKER: Space World was cool.
[43:35] SPEAKER: But it's this 2001, I mean,
[43:37] SPEAKER: like everybody's seen this footage, no clip.
[43:40] SPEAKER: In their efforts to archive a bunch of old tapes
[43:42] SPEAKER: in higher quality, just put up footage of all this stuff
[43:45] SPEAKER: I think last year sometime in much higher quality.
[43:47] SPEAKER: That's pretty exciting to go watch.
[43:49] SPEAKER: There's two components to this.
[43:51] SPEAKER: There's the very quick, like what was meant as B-roll,
[43:54] SPEAKER: sizzle reel, which is like some actual footage
[43:57] SPEAKER: from Luigi's Mansion, I think some Pokemon stuff.
[44:01] SPEAKER: But of course the one everybody remembers
[44:03] SPEAKER: is the realistic Zelda footage
[44:04] SPEAKER: of Link and Ganon fighting each other,
[44:06] SPEAKER: which was not a game like that.
[44:08] SPEAKER: The Luigi's Mansion stuff, it was stunning.
[44:11] SPEAKER: Yeah, yeah, yeah, it all looks good, for sure.
[44:13] SPEAKER: Well, 'cause it showed deformable polys.
[44:16] SPEAKER: Like they were smooth, Luigi was smooth.
[44:24] SPEAKER: Are you saying Luigi is ever not smooth?
[44:26] SPEAKER: I'm just saying that prior to that,
[44:27] SPEAKER: Luigi had polygonal faces and they were doing,
[44:32] SPEAKER: I assume like normal maps or something to make him,
[44:34] SPEAKER: or tessellation to make him look smooth
[44:38] SPEAKER: in that video and it looked real cool.
[44:40] SPEAKER: Yeah, for sure.
[44:41] SPEAKER: I mean, all the footage in there is impressive.
[44:42] SPEAKER: The reason that Zelda footage is infamous
[44:44] SPEAKER: is because they never actually made a game out of that.
[44:46] SPEAKER: Instead, we got the Wind Waker three years later,
[44:49] SPEAKER: which was an upgrade.
[44:51] SPEAKER: The second best Zelda game of all time?
[44:53] SPEAKER: Like the Wind Waker was an upgrade over this,
[44:56] SPEAKER: whatever, it'd been cool if they did both, but like.
[44:59] SPEAKER: Was the official branding for GameCube two words,
[45:02] SPEAKER: game space cube?
[45:04] SPEAKER: That shouldn't be, no.
[45:06] SPEAKER: It's on this video.
[45:08] SPEAKER: Oh, that might have been pretty interesting.
[45:11] SPEAKER: That was probably pre, like we've finalized
[45:13] SPEAKER: all the branding and marketing around this era.
[45:16] SPEAKER: This is super random.
[45:18] SPEAKER: Maybe I'll try to dig this link up.
[45:20] SPEAKER: Somebody actually found the GameCube from this demo.
[45:23] SPEAKER: Oh wow, really?
[45:24] SPEAKER: And like came into possession of it.
[45:27] SPEAKER: And like, it did an exhaustive breakdown
[45:30] SPEAKER: of like the early IO ports on it
[45:32] SPEAKER: that were not in the final and stuff.
[45:33] SPEAKER: It's like a prototype GameCube of some kind.
[45:35] SPEAKER: I don't know where they got that.
[45:36] SPEAKER: I'll try to find that link.
[45:39] SPEAKER: The 128 Mario thing I'd never seen before, I don't think.
[45:42] SPEAKER: So that's the end of this.
[45:43] SPEAKER: Yeah, the Zelda stuff, it was cool to see the Zelda
[45:46] SPEAKER: looking like that.
[45:46] SPEAKER: And of course, controversy around Wind Waker, whatever.
[45:49] SPEAKER: But the Mario 128, I'd always refer to this
[45:54] SPEAKER: as 128 Marios, I guess.
[45:57] SPEAKER: But I found it in the real one.
[45:58] SPEAKER: It's actually Mario 128 is what they call it.
[46:01] SPEAKER: It's the sequel to Mario 64, twice as good.
[46:04] SPEAKER: Exactly.
[46:05] SPEAKER: Like, it's two Mario 64s taped together.
[46:08] SPEAKER: Yeah, you flip the cartridge halfway through the game.
[46:11] SPEAKER: Yeah, but this is a perfect example
[46:12] SPEAKER: of what you were talking about of like,
[46:14] SPEAKER: oh God, let's just get the assets we have
[46:16] SPEAKER: and put together a demo as fast as we can.
[46:18] SPEAKER: It's literally, we have this one Mario model.
[46:21] SPEAKER: Normally we only do one Mario in a game,
[46:23] SPEAKER: but this time we're gonna do 120.
[46:24] SPEAKER: I mean, didn't they make a game like this at some point?
[46:27] SPEAKER: Isn't it like the Mini-Me's Mario,
[46:28] SPEAKER: like 128 Marios doing stuff?
[46:30] SPEAKER: Not really, they should have.
[46:32] SPEAKER: I can't remember.
[46:33] SPEAKER: They absolutely should have turned us into a game.
[46:34] SPEAKER: Army of Marios.
[46:36] SPEAKER: And there is a longer, it's in the show notes here,
[46:38] SPEAKER: there is a longer like interactive demo
[46:41] SPEAKER: of this being driven on stage
[46:43] SPEAKER: that apparently looks like IGN put up back in the day.
[46:47] SPEAKER: You know, where they actually move camera around,
[46:49] SPEAKER: like spawn more Marios in.
[46:50] SPEAKER: This thing is a nightmare.
[46:51] SPEAKER: They deform the surface that the Marios are standing on,
[46:54] SPEAKER: so it gets both concave and convex and stuff happens.
[46:57] SPEAKER: The Marios are inside boxes.
[46:58] SPEAKER: It's pretty good.
[46:59] SPEAKER: Yeah, it's a good just raw-ass tech demo
[47:03] SPEAKER: of the type I was talking about earlier that I miss.
[47:06] SPEAKER: - Same era, the PS2 one, right?
[47:10] SPEAKER: - Yes.
[47:11] SPEAKER: - I'd never seen this one before.
[47:12] SPEAKER: - The PlayStation 2 rubber ducks,
[47:14] SPEAKER: like famously from the era when I think it was the PS2
[47:16] SPEAKER: that they were pitching as Toy Story quality graphics
[47:19] SPEAKER: or something along those lines.
[47:20] SPEAKER: - Everybody was pitching Toy Story quality graphics
[47:22] SPEAKER: in the early 2000s, yeah.
[47:23] SPEAKER: - I would say the PlayStation 2 rubber duck
[47:25] SPEAKER: is almost right up there with the PS1 T-Rex
[47:28] SPEAKER: and the kind of pantheon of PlayStation tech demos,
[47:31] SPEAKER: but it's basically water physics.
[47:32] SPEAKER: It's basically like, "Hey, look at the transparency
[47:33] SPEAKER: "on this water and the ripples,
[47:34] SPEAKER: "and the fact that we can simulate fluids to some degree
[47:38] SPEAKER: "and have this rubber duck and this little battleship
[47:39] SPEAKER: "bobbing around in there."
[47:41] SPEAKER: - Yeah, it's pretty good.
[47:42] SPEAKER: This is a cool demo.
[47:43] SPEAKER: This was like 1999.
[47:45] SPEAKER: - Yeah, this was kind of in the run up to the PS2.
[47:48] SPEAKER: And then of course they, and this is another thing,
[47:50] SPEAKER: this like kind of goes to what I used to love
[47:52] SPEAKER: about the PlayStation and the way they used to pitch it
[47:54] SPEAKER: was that you kind of add to the mystique
[47:57] SPEAKER: and the visual language
[47:58] SPEAKER: and the kind of like memeification of your ecosystem
[48:02] SPEAKER: by doing stuff like this,
[48:03] SPEAKER: where it's like the T-Rex and the rubber duck
[48:05] SPEAKER: are like part of the sort of PlayStation family.
[48:07] SPEAKER: Those are things you can reference later
[48:09] SPEAKER: in things like Asterisk Playroom.
[48:10] SPEAKER: But they did that in the run up to the PS3.
[48:12] SPEAKER: There is a video out there of Phil Harrison on stage
[48:15] SPEAKER: with the rubber duck demo for the PS3,
[48:18] SPEAKER: where they basically just say,
[48:19] SPEAKER: "Hey, remember the rubber ducks.
[48:20] SPEAKER: "Look what we can do with it now."
[48:22] SPEAKER: And what they can do with that is spawn a lot of ducks
[48:25] SPEAKER: into this bathtub at one time instead of just one of them.
[48:28] SPEAKER: - I like that they're driving the duck around.
[48:30] SPEAKER: I just, I don't,
[48:32] SPEAKER: I wonder if we don't do this anymore
[48:33] SPEAKER: because the hardware is all basically the same.
[48:36] SPEAKER: - That's possible maybe.
[48:38] SPEAKER: And again, like I was saying earlier,
[48:40] SPEAKER: I think like some of this is just kind of old hat now.
[48:42] SPEAKER: Like they wanna show something that looks like a video game
[48:44] SPEAKER: and not just, hey, look at how much better
[48:46] SPEAKER: the fluid physics are.
[48:48] SPEAKER: - 'Cause yeah, it is fair to say at this time
[48:50] SPEAKER: you would buy one game when the game came,
[48:52] SPEAKER: the system came out and then it'd be like a year
[48:54] SPEAKER: before anything else interesting came out a lot of the time.
[48:57] SPEAKER: - Yeah.
[48:58] SPEAKER: - This Phil Harrison, oh, here's the battleships coming in.
[49:01] SPEAKER: I love that you can fast forward
[49:02] SPEAKER: and see when the ducks start to really, really come in
[49:05] SPEAKER: by what's most replayed.
[49:07] SPEAKER: - There's something slightly vulgar about the stream of,
[49:10] SPEAKER: the stream of rubber, yellow rubber ducks
[49:12] SPEAKER: pouring out of the ceiling into this bathtub.
[49:14] SPEAKER: - I wouldn't have never ever thought about that, Ren.
[49:17] SPEAKER: - Well, hey, that's what I'm here for.
[49:19] SPEAKER: - Yeah.
[49:20] SPEAKER: - Anyway, these are just fun raw tech demos.
[49:22] SPEAKER: Like I said, I miss stuff like this.
[49:24] SPEAKER: They're not, they don't have quite the stage presentation
[49:27] SPEAKER: aspect of things, but at a time when the technology
[49:30] SPEAKER: was pretty limited, it was a nice fun way to just show like,
[49:32] SPEAKER: hey, look how much better this stuff's getting.
[49:33] SPEAKER: - Now, okay, so if you didn't have a good demo,
[49:37] SPEAKER: the other thing you could do is just come out on stage
[49:39] SPEAKER: and be real, real sweaty and yell a lot,
[49:43] SPEAKER: which is what Balmer always did.
[49:45] SPEAKER: - Fair.
[49:46] SPEAKER: - Like this, we can't do this without having Balmer,
[49:53] SPEAKER: talking about Balmer coming out and saying developers,
[49:55] SPEAKER: developers, developers, when he is just drenched with sweat
[49:59] SPEAKER: at Bill, I think this was a build or win, heck,
[50:01] SPEAKER: I can't remember, but yeah, developers shout out,
[50:04] SPEAKER: shout out to Steve Balmer, owner of the Clippers, I guess.
[50:08] SPEAKER: - Sure.
[50:08] SPEAKER: - Good, good job, Steve.
[50:09] SPEAKER: - Yes, well, you know, if you're,
[50:11] SPEAKER: if you're up there to hype up, it was like .net,
[50:13] SPEAKER: I think is what they were promoting there.
[50:15] SPEAKER: - Well, what they were hyping up was, hey,
[50:16] SPEAKER: we have a better developer ecosystem than Apple.
[50:20] SPEAKER: - Well, that's the thing.
[50:21] SPEAKER: - Yeah.
[50:21] SPEAKER: - It's like, you're not gonna,
[50:22] SPEAKER: we have a big stage demo of like new APIs or.
[50:25] SPEAKER: - Oh, they did.
[50:25] SPEAKER: - Well, I'm sure they did.
[50:26] SPEAKER: I'm sure they did, but.
[50:27] SPEAKER: - You might not think you're gonna see
[50:31] SPEAKER: a two hour presentation about the 30 new APIs
[50:34] SPEAKER: that are coming to Windows this year.
[50:35] SPEAKER: - Not fair.
[50:36] SPEAKER: - But you will.
[50:37] SPEAKER: - I'm sure there was plenty of that, but.
[50:38] SPEAKER: - You will, Brad.
[50:39] SPEAKER: - In terms of, in terms of a theatrical presentation,
[50:42] SPEAKER: I guess a very large sweaty man,
[50:46] SPEAKER: skipping and jumping around the stage,
[50:48] SPEAKER: yelling at the audiences is about the best you can do.
[50:51] SPEAKER: - Well, there's a real, like there's a real
[50:53] SPEAKER: interesting contrast, 'cause this is around the same time
[50:54] SPEAKER: that Jobs was standing up on stage talking about
[50:56] SPEAKER: three things that were gonna change, you know,
[50:58] SPEAKER: selling a new, three new products.
[50:59] SPEAKER: It's announcing three new products this year, right?
[51:01] SPEAKER: And their approach was, we're gonna just do this
[51:04] SPEAKER: the same way IBM and Microsoft have done this
[51:06] SPEAKER: for a hundred years, and we're gonna do it harder
[51:08] SPEAKER: and yellier than we ever have before.
[51:11] SPEAKER: Anyway.
[51:12] SPEAKER: The, now that did start to change
[51:15] SPEAKER: when they were at more consumer focused shows
[51:16] SPEAKER: like Comdex and stuff like that, or CES,
[51:18] SPEAKER: they would do, Microsoft would do like big fake
[51:21] SPEAKER: living rooms and present you there.
[51:24] SPEAKER: Another great Microsoft moment is Bill Gates at Comdex
[51:29] SPEAKER: in Chicago, when it was still in Chicago,
[51:31] SPEAKER: demoing Windows 98 and how USB would make
[51:35] SPEAKER: devices plug and play.
[51:36] SPEAKER: - Oh, right, this is the infamous one, right?
[51:39] SPEAKER: - You plug in the device, you, it'll install
[51:44] SPEAKER: the drivers automatically and it's just gonna work.
[51:47] SPEAKER: - So, Bill Gates is standing on stage,
[51:49] SPEAKER: he's on Windows 98 PC, he's there with Chris Capocello
[51:52] SPEAKER: who is demoing, like doing the actual demo,
[51:56] SPEAKER: and Chris is all, hey, plug and play devices
[52:01] SPEAKER: are gonna change everything in Windows 98.
[52:03] SPEAKER: When you install a device, you just plug the USB port in
[52:05] SPEAKER: and it's just gonna work, it's gonna install the drivers
[52:08] SPEAKER: and you're good to go, and he plugs it in
[52:10] SPEAKER: and it gets like halfway through installing the drivers
[52:12] SPEAKER: and it just fucking blue screens.
[52:14] SPEAKER: - Like the whoa, like you can hear his jaw turning
[52:17] SPEAKER: to rubber, he's in the middle of his spiel
[52:19] SPEAKER: and he's just like, whoa.
[52:21] SPEAKER: - Well, so there's a pause and like, I assume,
[52:25] SPEAKER: 'cause Bill Gates, everybody knows this,
[52:27] SPEAKER: but Bill Gates has had a reputation of yelling at people
[52:29] SPEAKER: when he thought they were doing something stupid.
[52:32] SPEAKER: And like fucking up the Comdex demo,
[52:34] SPEAKER: probably pretty high on the things that you can do
[52:36] SPEAKER: that are stupid list, but he recovers really well.
[52:39] SPEAKER: - I started to say in the moment, he's got a smile
[52:42] SPEAKER: on his face, but it's not an amused smile.
[52:43] SPEAKER: - It's not, it's a you're gonna die smile.
[52:46] SPEAKER: Yeah, I would not want that smile.
[52:48] SPEAKER: - It's very much a how angry is this guy right now?
[52:51] SPEAKER: - Yeah. - Probably very.
[52:52] SPEAKER: - So, but he says, he says, well, that's why Windows 98
[52:56] SPEAKER: isn't shipping yet.
[52:57] SPEAKER: - Ah, that's not bad.
[52:59] SPEAKER: And like, frankly, it helps that the blue screen
[53:02] SPEAKER: gets a roar of applause from the audience.
[53:04] SPEAKER: Like the, you know, the audience makes it clear
[53:06] SPEAKER: that they are in on the joke and they're not judging this
[53:08] SPEAKER: or it's, you know, it's something everybody can relate to.
[53:11] SPEAKER: - Well, and like in the modern context, you would,
[53:15] SPEAKER: like you would not probably put the demo
[53:17] SPEAKER: that could blue screen out.
[53:18] SPEAKER: But at this point they probably said, look,
[53:20] SPEAKER: there's a one in 10 chance or one in 20 chance
[53:22] SPEAKER: or whatever it's gonna blue screen.
[53:24] SPEAKER: This driver is particularly stable, blah, blah, blah, blah.
[53:26] SPEAKER: And they'd cooked it as best they could.
[53:28] SPEAKER: And then it crashed the one out of 20 times.
[53:31] SPEAKER: Now it's worth mentioning Chris Capocella ended up
[53:33] SPEAKER: being the CMO of Microsoft.
[53:35] SPEAKER: So he didn't get fired into the sun.
[53:37] SPEAKER: - Sure, probably just fine.
[53:39] SPEAKER: - Yeah, he retired last year.
[53:41] SPEAKER: So congratulations, Chris.
[53:43] SPEAKER: - Yeah, also let's be real at this time,
[53:45] SPEAKER: there was no demo with the 0% chance of blue screening.
[53:48] SPEAKER: Like the reality of Windows at this time
[53:50] SPEAKER: was there was always a chance.
[53:52] SPEAKER: - Especially Windows 98 betas.
[53:54] SPEAKER: They were, Windows 98 betas were rowdy.
[53:57] SPEAKER: Let's see, a couple other mentions that we,
[53:59] SPEAKER: so we asked people for suggestions on blue sky
[54:01] SPEAKER: and on Discord and somebody on blue sky suggested
[54:07] SPEAKER: the BB-8 unveil at Celebration, which was really good.
[54:10] SPEAKER: They had shown some footage from the movie.
[54:12] SPEAKER: They showed this ball robot, the ball R2D2 rolling around.
[54:16] SPEAKER: Everybody's like, man, that is a cool robot.
[54:17] SPEAKER: And then at Celebration, they're introducing the cast.
[54:21] SPEAKER: Celebration's Microsoft Star Wars,
[54:22] SPEAKER: not Microsoft, Disney's Star Wars event,
[54:24] SPEAKER: or both Lucas's Star Wars event,
[54:26] SPEAKER: but now it's Disney's Star Wars event.
[54:28] SPEAKER: And they roll out a real life BB-8.
[54:32] SPEAKER: Like it rolls across the stage, it does all this stuff.
[54:34] SPEAKER: It's basically a huge Sphero.
[54:35] SPEAKER: - Right.
[54:36] SPEAKER: - And people lose their shit.
[54:38] SPEAKER: It was really, really a good moment.
[54:39] SPEAKER: - Now like at that time, they made it clear that on set,
[54:41] SPEAKER: they had a functional robot that they were using.
[54:43] SPEAKER: Like people just assumed they were puppeteering
[54:45] SPEAKER: a fake thing on set.
[54:46] SPEAKER: - People assumed it was like people underneath the set
[54:49] SPEAKER: driving the robot across or CG or something, you know.
[54:53] SPEAKER: - Yeah, and so that means it was way before people realized
[54:56] SPEAKER: they were soon going to be able to just pay,
[54:58] SPEAKER: granted a large amount of money,
[54:59] SPEAKER: to have one of these in their homes.
[55:01] SPEAKER: - Well, so they don't,
[55:02] SPEAKER: I don't think they ever made full size ones.
[55:04] SPEAKER: - Well, no, no, but I mean,
[55:05] SPEAKER: but the principle is the same though.
[55:06] SPEAKER: Like the, what I mean is the, the,
[55:08] SPEAKER: the means of locomotion in that robot actually worked.
[55:11] SPEAKER: - Oh yeah, and, and like, just to be clear,
[55:12] SPEAKER: it's Sphero had done this 10 years before, five years,
[55:15] SPEAKER: five years before, probably 10 years before.
[55:17] SPEAKER: - Well, have they done the little thing
[55:18] SPEAKER: of balancing the disc on top of the sphere though?
[55:20] SPEAKER: - Well, but balancing the disc on top of the,
[55:22] SPEAKER: they had not done that in a product yet,
[55:24] SPEAKER: but because of the way this, the robot works inside this.
[55:27] SPEAKER: So the Sphero, for people who don't know,
[55:28] SPEAKER: is a hamster ball robot.
[55:30] SPEAKER: It's a, it's a little,
[55:32] SPEAKER: it's basically a little guy that sits inside the ball
[55:34] SPEAKER: and has rollers that keep it positioned in the ball
[55:37] SPEAKER: so it doesn't rattle around.
[55:39] SPEAKER: And then it has, it has articulated wheels
[55:42] SPEAKER: that let it roll around and control
[55:43] SPEAKER: which way the ball moves.
[55:45] SPEAKER: And BB-8s, you generally work basically the same
[55:48] SPEAKER: with scaled up version of that.
[55:49] SPEAKER: But then there's a magnetic thing on the top
[55:51] SPEAKER: that either allows you to puppet the movement of the head
[55:54] SPEAKER: for some of them, or just, just leans forward,
[55:56] SPEAKER: leans back when it's rolling.
[55:57] SPEAKER: - Right, yeah, but I mean, but you know, bottom line,
[56:00] SPEAKER: it's a pretty potent effect to have this cool looking robot
[56:03] SPEAKER: in your new science fiction movie
[56:04] SPEAKER: that you're promoting,
[56:05] SPEAKER: and then have that robot just come out on stage
[56:06] SPEAKER: and clearly be independent and self, you know,
[56:10] SPEAKER: kind of self propelling.
[56:12] SPEAKER: - Oh yeah, and just to be clear, there's now, you know,
[56:15] SPEAKER: here, what, five, seven,
[56:18] SPEAKER: five years after that trilogy ended,
[56:20] SPEAKER: there's a BB-8 Builders Club,
[56:22] SPEAKER: just like there's an R2 Builders Club
[56:24] SPEAKER: or a Wall-E Builders Club.
[56:26] SPEAKER: And like when we went to Maker Faire,
[56:28] SPEAKER: we saw a BB-8 that somebody had built
[56:29] SPEAKER: and be like printed all their parts and molded,
[56:32] SPEAKER: like done the whole thing.
[56:33] SPEAKER: It was really cool.
[56:34] SPEAKER: - That's wild, I would not have expected that stuff
[56:36] SPEAKER: was that easy to cobble together yet.
[56:38] SPEAKER: - It is not easy to cobble together.
[56:39] SPEAKER: - Not easy, but it's doable, apparently.
[56:41] SPEAKER: - Yeah, it's, I mean, like building an R2,
[56:44] SPEAKER: you're gonna spend thousands of dollars
[56:46] SPEAKER: and probably 10,000 hours assembling,
[56:49] SPEAKER: but yeah, it's a thing you can do.
[56:51] SPEAKER: And somebody's written the software to control the motors
[56:53] SPEAKER: and the whole thing, it's really cool.
[56:54] SPEAKER: - That's cool.
[56:55] SPEAKER: One more coming off the PlayStation stuff that we missed.
[56:58] SPEAKER: I wouldn't have thought of this, but you suggested it,
[56:59] SPEAKER: and I guess technically it does fit here.
[57:02] SPEAKER: The PS4 how to share games with your friends demo.
[57:06] SPEAKER: - The official PlayStation used game instructional video.
[57:09] SPEAKER: - Is that what they call it?
[57:10] SPEAKER: - That's what they called it.
[57:11] SPEAKER: - That's pretty good.
[57:12] SPEAKER: - I, my, friend of the show, Adam Boyce,
[57:16] SPEAKER: my understanding is that he was sitting,
[57:18] SPEAKER: he and Shu were sitting around
[57:20] SPEAKER: watching the Microsoft press conference,
[57:22] SPEAKER: and somebody came up with the idea of doing this
[57:25] SPEAKER: before the PS4 announced conference at E3,
[57:28] SPEAKER: which was later the same day, or maybe the next day,
[57:31] SPEAKER: I can't remember. - It was the same day.
[57:31] SPEAKER: - It was like, that's kind of the famous thing
[57:33] SPEAKER: was that Microsoft announced the $500 price that morning,
[57:36] SPEAKER: and then Sony literally hours later
[57:38] SPEAKER: undercut them by a hundred bucks.
[57:40] SPEAKER: - Well, and, and so Microsoft had announced the price
[57:43] SPEAKER: and they announced that it needed to be always online,
[57:45] SPEAKER: which people lost their minds about.
[57:47] SPEAKER: - Yep, yep.
[57:48] SPEAKER: This is one of the most pronounced examples I can think of,
[57:50] SPEAKER: of just kind of targeted corporate brutality.
[57:53] SPEAKER: One corporation sticking a knife in another.
[57:56] SPEAKER: - So it hangs here because it's high risk, right?
[57:58] SPEAKER: There's clearly shooting something like
[58:00] SPEAKER: in the backstage area behind the conference stage,
[58:03] SPEAKER: or like a hotel room ballroom or something like that.
[58:06] SPEAKER: Someplace with black drape, pipe and drape.
[58:08] SPEAKER: And basically they do, they do the,
[58:12] SPEAKER: here's how to share,
[58:13] SPEAKER: here's how to share a used video game with your friends.
[58:17] SPEAKER: - Here's how to share a PlayStation 4 game
[58:20] SPEAKER: with your friends.
[58:20] SPEAKER: - Yeah, and they do the intro,
[58:23] SPEAKER: and then there's like a little PlayStation swirl
[58:26] SPEAKER: that's like with the step one, blah, blah, blah.
[58:28] SPEAKER: You know, it's a title.
[58:29] SPEAKER: It's like a really good motion graphic that they've set up.
[58:32] SPEAKER: It's unnecessarily long.
[58:35] SPEAKER: And then- - It's step one, yeah.
[58:36] SPEAKER: - It cuts to Shu handing Adam a disc.
[58:42] SPEAKER: - Yeah, whoever did the editing on this
[58:43] SPEAKER: deserves a lot of credit for the comedic rhythm of this.
[58:47] SPEAKER: - Adam looks at the camera and says, "Thank you."
[58:50] SPEAKER: And that's it, that's the whole video.
[58:51] SPEAKER: - Yeah, like technically is, you know,
[58:53] SPEAKER: in terms of whether this belongs on this list or not,
[58:55] SPEAKER: it is a demonstration of a technology.
[58:58] SPEAKER: - Well, and so they could have done it live on stage.
[59:00] SPEAKER: That would have been cooler,
[59:01] SPEAKER: but it wouldn't have had the funny video edit.
[59:03] SPEAKER: The thing about this was,
[59:07] SPEAKER: it contrasted with Microsoft's like 12 step process
[59:10] SPEAKER: for sharing a DRM download only video game
[59:14] SPEAKER: that you had bought on the Xbox with a friend,
[59:16] SPEAKER: which you could do like,
[59:17] SPEAKER: there were all sorts of limitations.
[59:18] SPEAKER: You could do it like five times,
[59:19] SPEAKER: and you can only do it
[59:20] SPEAKER: if everybody was connected to the internet,
[59:21] SPEAKER: and it was like the kind of thing that you looked at,
[59:26] SPEAKER: and you were like, oh, this is designed
[59:27] SPEAKER: so that no one will ever do it.
[59:28] SPEAKER: And Tony was like, hey man,
[59:29] SPEAKER: we're cool if you change to share discs with each other,
[59:31] SPEAKER: that's fine.
[59:32] SPEAKER: - Yeah, famously, Microsoft took such a drubbing
[59:36] SPEAKER: from this situation and largely from this video
[59:39] SPEAKER: that they straight up reversed course on the DRM policy
[59:41] SPEAKER: some weeks later.
[59:42] SPEAKER: - Yeah, yeah.
[59:44] SPEAKER: - Although now quietly,
[59:45] SPEAKER: everybody has arrived at exactly that place.
[59:48] SPEAKER: - Like we ended up right.
[59:48] SPEAKER: Well, yeah, anyway, grim.
[59:52] SPEAKER: Let's see, last one I think on our list.
[59:54] SPEAKER: Is this it?
[59:54] SPEAKER: Have we reached the end already?
[59:55] SPEAKER: - I think so.
[59:56] SPEAKER: - We didn't talk about Doom 3 at Macworld.
[59:58] SPEAKER: - Oh, we passed over that one somehow.
[1:00:00] SPEAKER: - Yeah, we skipped that.
[1:00:01] SPEAKER: - Yeah, that one went with the source engine.
[1:00:03] SPEAKER: Well, we talked about Doom 3.
[1:00:05] SPEAKER: I think the E3 presentation I saw.
[1:00:09] SPEAKER: The one that we have on this list is the somewhat famous,
[1:00:11] SPEAKER: at least at the time it was quite famous,
[1:00:13] SPEAKER: of the Macworld 2001 in Tokyo,
[1:00:15] SPEAKER: where Steve Jobs introduced John Carmack.
[1:00:17] SPEAKER: It was, I don't know if it was the announcement
[1:00:20] SPEAKER: of the GeForce 3,
[1:00:20] SPEAKER: but it was definitely a very early promotion
[1:00:23] SPEAKER: for the GeForce 3.
[1:00:24] SPEAKER: And of course, you know, we've talked about how
[1:00:27] SPEAKER: transformational the GeForce 3 was
[1:00:28] SPEAKER: with programmable shaders and so forth.
[1:00:30] SPEAKER: But it was an interesting confluence of Jobs on Apple,
[1:00:35] SPEAKER: John Carmack and id Software, a new Doom, a new GeForce.
[1:00:39] SPEAKER: Like you do not expect to see things like id Software
[1:00:41] SPEAKER: and GeForce and Doom on an Apple stage.
[1:00:45] SPEAKER: - Yeah, it was like we got up early in the morning
[1:00:47] SPEAKER: or stayed up late at night.
[1:00:48] SPEAKER: I can't remember which one,
[1:00:49] SPEAKER: and we're watching in the conference room in future for this.
[1:00:52] SPEAKER: And it was shocking.
[1:00:53] SPEAKER: - Yeah.
[1:00:54] SPEAKER: - And it came on the heels of Q3 tests.
[1:00:56] SPEAKER: - Yes, yes.
[1:00:57] SPEAKER: So like this was about two years, I guess,
[1:01:00] SPEAKER: after Q3 test famously, the kind of early beta version,
[1:01:04] SPEAKER: demo version of Quake 3 shipped on Mac first.
[1:01:08] SPEAKER: - By like a couple of weeks, right?
[1:01:10] SPEAKER: There was a long time. - At least for like a month.
[1:01:11] SPEAKER: People were so mad.
[1:01:12] SPEAKER: - Yeah.
[1:01:13] SPEAKER: - But they wanted a very small test bed.
[1:01:15] SPEAKER: They wanted like a very small,
[1:01:16] SPEAKER: manageable amount of feedback coming in on the first build,
[1:01:19] SPEAKER: which was easy because very few people could run that game
[1:01:21] SPEAKER: on a Mac at the time.
[1:01:23] SPEAKER: But anyway, like Carmack,
[1:01:25] SPEAKER: which I've actually just talked about recently,
[1:01:27] SPEAKER: Romero, like they were all big Next Step fans that did.
[1:01:30] SPEAKER: So when OS X essentially was the next version of Next Step,
[1:01:33] SPEAKER: they did a lot of development on that platform.
[1:01:35] SPEAKER: So it made sense.
[1:01:36] SPEAKER: That kind of temporary collaboration there
[1:01:39] SPEAKER: obviously did not last.
[1:01:41] SPEAKER: - It was a very unappley,
[1:01:43] SPEAKER: like the fact that because it was unusual for Mac,
[1:01:46] SPEAKER: for jobs to promote violent video games.
[1:01:49] SPEAKER: - Sure.
[1:01:50] SPEAKER: - At that point.
[1:01:51] SPEAKER: - Yeah, yeah.
[1:01:52] SPEAKER: - That was novel.
[1:01:52] SPEAKER: - I still have the clip I downloaded in 2001 of that
[1:01:55] SPEAKER: on my mouse.
[1:01:56] SPEAKER: - What was the date stamp?
[1:01:57] SPEAKER: Do you remember?
[1:01:58] SPEAKER: - It was February, 2001, I believe.
[1:02:00] SPEAKER: - Something like that.
[1:02:00] SPEAKER: - I put it in the Discord.
[1:02:01] SPEAKER: It still had that file lying around when I watched it.
[1:02:04] SPEAKER: And I remembered how fucking blown away I was
[1:02:06] SPEAKER: by the visuals in that thing.
[1:02:08] SPEAKER: And then, you know, I guess the last thing I'll say
[1:02:09] SPEAKER: there is like, kind of like we're alluding to
[1:02:11] SPEAKER: the theatrical aspect of what these demos can be like,
[1:02:14] SPEAKER: like bringing somebody out who you don't expect.
[1:02:17] SPEAKER: It's that straight up like pro wrestling type stuff almost.
[1:02:20] SPEAKER: - Yeah, it's like a booking, right?
[1:02:21] SPEAKER: - Right, they didn't exactly amp it up in that way
[1:02:23] SPEAKER: for this particular instance, but like it's,
[1:02:26] SPEAKER: that's literally like, by God,
[1:02:27] SPEAKER: that's Sean Carmack's music type stuff.
[1:02:29] SPEAKER: Or another one that I think of,
[1:02:31] SPEAKER: I don't know if it actually played out this way
[1:02:32] SPEAKER: in real life.
[1:02:33] SPEAKER: My memory is of the Pirates of Silicon Valley film.
[1:02:36] SPEAKER: - Okay.
[1:02:37] SPEAKER: - The famous Microsoft investment in Apple
[1:02:39] SPEAKER: when Apple was hanging by a thread.
[1:02:41] SPEAKER: - Oh, when Bill Gates came up huge on the screen
[1:02:45] SPEAKER: at Macworld?
[1:02:46] SPEAKER: - Yeah.
[1:02:47] SPEAKER: - In the movie, they dramatize it as Jobs is on stage
[1:02:49] SPEAKER: and then they cut to like a giant Bill Gates on the screen.
[1:02:52] SPEAKER: - It's like the emperor.
[1:02:53] SPEAKER: - Yes, literally like the emperor appearing.
[1:02:55] SPEAKER: I don't know if that's exactly how it played out
[1:02:57] SPEAKER: in real life, but you know, like there can be an aspect
[1:02:59] SPEAKER: of like people you never expected to work together
[1:03:02] SPEAKER: suddenly are here sharing a stage to these kinds of demos.
[1:03:05] SPEAKER: - I don't actually remember which way that,
[1:03:06] SPEAKER: I didn't watch that at the time.
[1:03:07] SPEAKER: It would have been before my day.
[1:03:09] SPEAKER: - Yeah, I also, I don't know if that was even like televised
[1:03:11] SPEAKER: or even recorded for that matter.
[1:03:13] SPEAKER: - Yeah, I mean, there may not be video of it, but.
[1:03:16] SPEAKER: - Also, before we move on, I'm just gonna say this now,
[1:03:18] SPEAKER: we should watch Pirates of Silicon Valley
[1:03:20] SPEAKER: and do an episode about it.
[1:03:21] SPEAKER: - I would watch that.
[1:03:22] SPEAKER: - Soon.
[1:03:23] SPEAKER: - The other one, I think Bill Gates coming out at build
[1:03:26] SPEAKER: or at Alex St. John's DirectX unveil
[1:03:32] SPEAKER: in a trench coat with a shotgun green screened
[1:03:35] SPEAKER: into a doom shot.
[1:03:37] SPEAKER: - Yeah.
[1:03:38] SPEAKER: - Canonically making Bill Gates the doom guy.
[1:03:42] SPEAKER: - I don't know about that.
[1:03:43] SPEAKER: - He walks out, he walks out,
[1:03:45] SPEAKER: he walks out from behind the camera
[1:03:46] SPEAKER: as if he's the avatar of the first person
[1:03:49] SPEAKER: and casually mercs an alien
[1:03:51] SPEAKER: and then talks about how important games are
[1:03:53] SPEAKER: to Microsoft and Windows.
[1:03:56] SPEAKER: - Well, you know, to be fair, unlike Steve Jobs,
[1:03:57] SPEAKER: he actually meant it.
[1:03:58] SPEAKER: - Yeah, yeah, I mean, they invested in games for years.
[1:04:02] SPEAKER: The, let's see, I'm trying to think,
[1:04:04] SPEAKER: there's some other stuff.
[1:04:05] SPEAKER: Oh, the Disney Vision Imagineering one
[1:04:06] SPEAKER: is really interesting too.
[1:04:07] SPEAKER: So this is the one that Wildcard actually suggested
[1:04:10] SPEAKER: we should look at.
[1:04:12] SPEAKER: And it's an Epcot demo from 1994
[1:04:17] SPEAKER: where you're, a group of people gets pulled into a room
[1:04:21] SPEAKER: and they pull a handful of,
[1:04:23] SPEAKER: they talk about what virtual reality is
[1:04:24] SPEAKER: in a very fascinating way.
[1:04:26] SPEAKER: It's worth watching this video if you haven't seen it.
[1:04:28] SPEAKER: It's for a ride called, I think Disney Vision,
[1:04:31] SPEAKER: where the parrot from Aladdin played by Gilbert Gottfried
[1:04:35] SPEAKER: like flies you through a magic carpet thing
[1:04:37] SPEAKER: where you're all wearing big giant CRT based VR headsets.
[1:04:41] SPEAKER: And they do this whole talk and they explain what VR is
[1:04:46] SPEAKER: and then like three people from the audience
[1:04:47] SPEAKER: get to come up and try on the headsets,
[1:04:49] SPEAKER: which are suspended from the ceiling
[1:04:50] SPEAKER: so you don't break your neck.
[1:04:53] SPEAKER: But they don't, and they show you what those people
[1:04:55] SPEAKER: are seeing through the cameras, but they didn't,
[1:04:59] SPEAKER: like, I don't know if it's 'cause the ride had to be open.
[1:05:01] SPEAKER: Like, I don't know why this exists.
[1:05:03] SPEAKER: 'Cause I don't think this ride ever opened.
[1:05:05] SPEAKER: I don't think they ever actually did this ride.
[1:05:08] SPEAKER: I couldn't find anything about it.
[1:05:09] SPEAKER: I looked for it a little bit
[1:05:10] SPEAKER: and maybe that they changed the name
[1:05:11] SPEAKER: and the stuff I was searching for didn't work,
[1:05:13] SPEAKER: but I would love to know from audience
[1:05:15] SPEAKER: if this is a thing that actually happened.
[1:05:19] SPEAKER: - Maybe it's because as soon as the cameras cut,
[1:05:21] SPEAKER: all the participants walked off set
[1:05:23] SPEAKER: and vomited violently everywhere.
[1:05:25] SPEAKER: - Well, so they were running,
[1:05:26] SPEAKER: they talked about frame rates even.
[1:05:27] SPEAKER: And they were like, it seemed like they were talking
[1:05:29] SPEAKER: about 60 frames per second per eye,
[1:05:31] SPEAKER: which should have been okay with CRTs
[1:05:32] SPEAKER: with the image retention, I would think.
[1:05:34] SPEAKER: But...
[1:05:36] SPEAKER: - Like you said, you see the footage,
[1:05:37] SPEAKER: like the head tracking seems reasonably competent.
[1:05:39] SPEAKER: - It seemed okay.
[1:05:41] SPEAKER: And they were doing YAGO, the parrot.
[1:05:43] SPEAKER: Like they were showing 3D models
[1:05:45] SPEAKER: had been created on SGI workstations.
[1:05:47] SPEAKER: Having just come off of that "Doom" and "Quake" episode,
[1:05:50] SPEAKER: the Romero episode, it was interesting
[1:05:51] SPEAKER: 'cause this would have been around the same time.
[1:05:54] SPEAKER: And tools to make 3D models like that
[1:05:56] SPEAKER: were few and far between.
[1:05:58] SPEAKER: So they were on the real edge here.
[1:06:00] SPEAKER: - Yeah, but maybe that was it.
[1:06:02] SPEAKER: Maybe it was just a little too technically advanced
[1:06:04] SPEAKER: to be feasible to deploy at scale or something.
[1:06:07] SPEAKER: Yeah, to have 10, 1,000 people an hour through or whatever.
[1:06:12] SPEAKER: Did you, the other one, did you see the walking floor demo
[1:06:15] SPEAKER: from Imagineering a couple of weeks ago?
[1:06:17] SPEAKER: - No.
[1:06:19] SPEAKER: - Oh, I should have put this on the list.
[1:06:20] SPEAKER: Damn, this is, so this is a video.
[1:06:23] SPEAKER: It doesn't, it's not on stage.
[1:06:25] SPEAKER: It's not...
[1:06:27] SPEAKER: - I have it here.
[1:06:28] SPEAKER: Is this the Disney Imagineer makes history?
[1:06:30] SPEAKER: - Yeah, I believe that's it.
[1:06:33] SPEAKER: - I think I heard, I saw people talking about it.
[1:06:34] SPEAKER: - It's Lanny Smoot, right, the hollow tile floor?
[1:06:37] SPEAKER: - I heard people talking about this.
[1:06:39] SPEAKER: I did not, I did not actually.
[1:06:40] SPEAKER: Yes, that is the video.
[1:06:41] SPEAKER: What is the concept here?
[1:06:43] SPEAKER: - So the concept is a floor that you can walk on
[1:06:45] SPEAKER: that holds you in place while you're walking.
[1:06:47] SPEAKER: - Interesting, okay.
[1:06:48] SPEAKER: - So it moves in the opposite direction
[1:06:50] SPEAKER: that your feet are moving,
[1:06:51] SPEAKER: but it feels like you're walking on a normal floor.
[1:06:53] SPEAKER: - Look at that, yeah, like they've,
[1:06:55] SPEAKER: and then to be clear, this is the type of thing
[1:06:56] SPEAKER: you can only put in a Disney theme park 'cause it's not,
[1:06:59] SPEAKER: well, who knows, maybe in 20 years
[1:07:00] SPEAKER: you'll have this in your living room, but...
[1:07:01] SPEAKER: - I mean, maybe you have this
[1:07:02] SPEAKER: instead of people movers at airports, right?
[1:07:04] SPEAKER: - Maybe, sure.
[1:07:05] SPEAKER: I mean, this is something people have been trying to solve
[1:07:07] SPEAKER: for like, I feel like 15 years ago at E3,
[1:07:09] SPEAKER: I was seeing like weird treadmills
[1:07:12] SPEAKER: hooked up to VR headsets because they want to let you,
[1:07:14] SPEAKER: they want to let you walk in a virtual space
[1:07:16] SPEAKER: while not actually moving around.
[1:07:17] SPEAKER: - I tried so many of those and the vast majority of them
[1:07:21] SPEAKER: were, hey, here's a really slippery disc
[1:07:23] SPEAKER: that you stand in with really slippery shoes on
[1:07:25] SPEAKER: and you buckle your hips in and just kind of move your feet
[1:07:27] SPEAKER: while you're, and none of them work.
[1:07:29] SPEAKER: This looks really cool.
[1:07:31] SPEAKER: I'm interested to try this.
[1:07:33] SPEAKER: - It seems like a good way to load people on and off rides
[1:07:35] SPEAKER: if nothing else, if it goes fast enough.
[1:07:37] SPEAKER: - It looks, it looks very fluid.
[1:07:38] SPEAKER: It looks slippery almost.
[1:07:40] SPEAKER: - Yeah.
[1:07:41] SPEAKER: - It's a striking effect.
[1:07:42] SPEAKER: - At no point did he look like he was going to beef it,
[1:07:44] SPEAKER: which was the other cool thing.
[1:07:45] SPEAKER: - Yeah.
[1:07:46] SPEAKER: - Also good shoes.
[1:07:47] SPEAKER: - Yes, also the footage of him sitting in a chair
[1:07:50] SPEAKER: on this thing and having somebody move the chair
[1:07:53] SPEAKER: on the floor while he's stationary is pretty weird
[1:07:57] SPEAKER: and eye-opening.
[1:07:58] SPEAKER: - It looks like it doesn't go super fast,
[1:07:59] SPEAKER: is the other thing.
[1:08:00] SPEAKER: - Yeah.
[1:08:01] SPEAKER: - But anyway.
[1:08:02] SPEAKER: - Do you have a theme?
[1:08:03] SPEAKER: - Hollow tile floor.
[1:08:04] SPEAKER: - Hollow tile floor.
[1:08:06] SPEAKER: - Hollow tile floor is what they call it.
[1:08:08] SPEAKER: - Hey, there's still new technology yet to be demoed.
[1:08:11] SPEAKER: - Yeah, like I would love to see this on a stage someplace.
[1:08:14] SPEAKER: I bet there's, I wonder what goes underneath it is the thing.
[1:08:16] SPEAKER: I wonder how like, how much mechanism is underneath this
[1:08:19] SPEAKER: on the floor, under the floor.
[1:08:21] SPEAKER: Anyway, so this will do it for us I think this week, Brad.
[1:08:25] SPEAKER: What do you think?
[1:08:26] SPEAKER: - Yeah, I think so.
[1:08:26] SPEAKER: - Tech demos.
[1:08:27] SPEAKER: - Tech demos are fun.
[1:08:28] SPEAKER: They're still fun.
[1:08:29] SPEAKER: They're not as many of them as there used to be.
[1:08:31] SPEAKER: I wish there were more.
[1:08:32] SPEAKER: - Yeah, and we're gonna do,
[1:08:34] SPEAKER: there's a couple of books I wanna read
[1:08:35] SPEAKER: before we do the Mother of All Demos episode.
[1:08:39] SPEAKER: So it'll be a minute.
[1:08:41] SPEAKER: But I think that it would widely regarded,
[1:08:45] SPEAKER: it's widely regarded as the thing that kicked off
[1:08:48] SPEAKER: a lot of the innovations that happened at PARC.
[1:08:51] SPEAKER: The Stanford Research Institute,
[1:08:52] SPEAKER: like a lot of people spun out of that
[1:08:54] SPEAKER: and ended up going to other places, so.
[1:08:56] SPEAKER: - Yeah, I don't wanna burn.
[1:08:58] SPEAKER: We'll save it for that episode.
[1:08:59] SPEAKER: But looking at what was at that thing,
[1:09:01] SPEAKER: for as much credit as PARC gets
[1:09:02] SPEAKER: for inventing things like the GUI and the mouse,
[1:09:04] SPEAKER: like here it all was even before that, so.
[1:09:06] SPEAKER: - Yeah.
[1:09:07] SPEAKER: - There's a whole lineage there.
[1:09:08] SPEAKER: - So anyway, that'll do it for us this week.
[1:09:10] SPEAKER: Thank you all for listening.
[1:09:11] SPEAKER: As always, Brad and Will made a tech pod
[1:09:12] SPEAKER: is 100% listener supported.
[1:09:14] SPEAKER: We don't take ads.
[1:09:14] SPEAKER: - It's true.
[1:09:15] SPEAKER: - So if you would like to support the show,
[1:09:16] SPEAKER: if you would like to reward us for our labors,
[1:09:20] SPEAKER: you can go to patreon.com/techpod.
[1:09:22] SPEAKER: Again, it's patreon.com/techpod
[1:09:24] SPEAKER: and join the 3000 members of our community,
[1:09:27] SPEAKER: either in the discord or just listening
[1:09:29] SPEAKER: to the Patreon exclusive episodes that come out every month.
[1:09:32] SPEAKER: The discord is full of fascinating conversations
[1:09:34] SPEAKER: about all sorts of things,
[1:09:35] SPEAKER: from things we can talk about on the show
[1:09:38] SPEAKER: to yesterday was a bunch of,
[1:09:40] SPEAKER: there was a bunch of food talk in general, I don't know.
[1:09:42] SPEAKER: People were talking about TV shows they like.
[1:09:44] SPEAKER: There's a lot of talking about 3D platformers
[1:09:46] SPEAKER: and like what Mario games are good.
[1:09:48] SPEAKER: - Oh yeah.
[1:09:49] SPEAKER: - I don't know.
[1:09:51] SPEAKER: Like somebody posted a Super Mario Deep Dive,
[1:09:53] SPEAKER: a Super Mario Sunshine Deep Dive that I've never seen.
[1:09:56] SPEAKER: And I kinda wanna go back and play Super Mario Sunshine now,
[1:09:58] SPEAKER: but I don't know if that's a good idea or not.
[1:10:01] SPEAKER: - You could maybe watch a video and be good.
[1:10:03] SPEAKER: - They did talk about the bonus disc
[1:10:07] SPEAKER: that you got for pre-ordering Windmaker though,
[1:10:09] SPEAKER: in there yesterday.
[1:10:10] SPEAKER: Do you remember what it was?
[1:10:10] SPEAKER: - No.
[1:10:11] SPEAKER: - It was Ocarina of Time
[1:10:13] SPEAKER: and the Master Quest for Ocarina of Time.
[1:10:15] SPEAKER: - Wait, not Majora's Mask, just Ocarina?
[1:10:18] SPEAKER: - It might've had Majora's Mask too,
[1:10:19] SPEAKER: but it definitely had two Ocarinas.
[1:10:21] SPEAKER: - I can't believe I had forgotten that
[1:10:22] SPEAKER: 'cause I have that disc in the closet.
[1:10:23] SPEAKER: I pre-ordered the Windmaker and got that disc.
[1:10:26] SPEAKER: - Yeah, so I have that disc as well
[1:10:29] SPEAKER: and I'm gonna go dig it out
[1:10:30] SPEAKER: 'cause I wanna play that Master Quest.
[1:10:31] SPEAKER: I never actually did.
[1:10:32] SPEAKER: - Yeah, that sounds fun.
[1:10:33] SPEAKER: The Discord, let's just say,
[1:10:35] SPEAKER: the Discord is also a great place to go if, for example,
[1:10:38] SPEAKER: you get your hands on the seminal 1988 work,
[1:10:41] SPEAKER: the C programming language by Kernighan and Ritchie.
[1:10:46] SPEAKER: And you wanna ask some programmers,
[1:10:47] SPEAKER: "Hey, should I still read this book in 2024?"
[1:10:50] SPEAKER: - Is it worth reading?
[1:10:50] SPEAKER: - Are there better ways to approach C, for example?
[1:10:53] SPEAKER: - And is it?
[1:10:54] SPEAKER: - I was told that book was written largely
[1:10:56] SPEAKER: as a way to get assembly language programmers into C.
[1:10:59] SPEAKER: So I'm gonna say maybe-
[1:11:00] SPEAKER: - Probably not so much for you.
[1:11:01] SPEAKER: - Might not be the angle for me to approach.
[1:11:04] SPEAKER: I turned to a random page
[1:11:05] SPEAKER: and it was just so much stuff about pointer arithmetic.
[1:11:07] SPEAKER: - There you go.
[1:11:08] SPEAKER: - And I was like, "I don't know if I have time
[1:11:10] SPEAKER: for this or capacity."
[1:11:12] SPEAKER: - But yeah, so you can get anywhere from Windwaker to C.
[1:11:15] SPEAKER: That's what we got.
[1:11:16] SPEAKER: - That's right, and everything in between.
[1:11:18] SPEAKER: - You can go to patreon.com/checkpod for five bucks a month.
[1:11:21] SPEAKER: You can join the community.
[1:11:22] SPEAKER: We, at the end of the month, or at the end of the episode,
[1:11:26] SPEAKER: like to thank our supporters, all of our patrons.
[1:11:28] SPEAKER: So thank you, patrons.
[1:11:29] SPEAKER: - Thank you.
[1:11:30] SPEAKER: - And we want to give an extra special shout out
[1:11:31] SPEAKER: to our executive producer tier patrons,
[1:11:33] SPEAKER: including Paddle Creek Games Makers of Fractured Vale,
[1:11:36] SPEAKER: Andrew Solosky, Jordan Lippett.
[1:11:38] SPEAKER: Bunny Crimes just wants you to pick a shirt.
[1:11:42] SPEAKER: Just Wedge, Joel Krauska, Twinkle Twinkie,
[1:11:44] SPEAKER: David Allen, James Kamek, and Pantheon Makers
[1:11:47] SPEAKER: of the HS3 High Speed 3D Printer.
[1:11:49] SPEAKER: - Thank you, everyone.
[1:11:50] SPEAKER: - Thank you all so much.
[1:11:51] SPEAKER: That'll do it for us this week.
[1:11:52] SPEAKER: We will be back next week with another episode
[1:11:54] SPEAKER: of The Tech Pod.
[1:11:55] SPEAKER: Thank you for listening, and we will see you then.
[1:11:58] SPEAKER: Bye.
[1:11:59] SPEAKER: (upbeat music)
