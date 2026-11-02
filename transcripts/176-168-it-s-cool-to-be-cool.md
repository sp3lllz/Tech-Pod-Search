---
episode: 176
title: 168: It's Cool to Be Cool
date: 2023-01-22
guests: none
duration: 1:06:18
---

[00:00] SPEAKER: - So Brad, last week when chat was on,
[00:02] SPEAKER: he said something that kind of stuck with me.
[00:04] SPEAKER: - Well, that could be a lot of things, but sure.
[00:06] SPEAKER: - He said, you guys with your NASA's blah, blah, blah,
[00:11] SPEAKER: freaks, I don't know.
[00:12] SPEAKER: - Freaks, I can tell you freaks was the operative word used.
[00:16] SPEAKER: - So right now, today, January 20th, 2023,
[00:20] SPEAKER: if you go to the Steam page for the anacrusis,
[00:24] SPEAKER: by the way, price dropped last week, it's 20 bucks now,
[00:26] SPEAKER: you can get it around Xbox, Steam, wherever, 20 bucks.
[00:29] SPEAKER: - Is that a permanent?
[00:30] SPEAKER: - 20 bucks, permanent price drop.
[00:31] SPEAKER: Well, I don't know about permanent,
[00:33] SPEAKER: like we might go back up when we get out of early access,
[00:34] SPEAKER: but that's, yeah, we did a poll and the people were like,
[00:38] SPEAKER: hey, if the game was 20 bucks,
[00:39] SPEAKER: I'd recommend it to my friends, they buy it, whatever.
[00:42] SPEAKER: So we're gonna try it and see, listen to the people.
[00:44] SPEAKER: I'm not gonna say the thing that the other guy says.
[00:46] SPEAKER: Anyway, the point is, at the top of that,
[00:49] SPEAKER: you'll see a thing that says,
[00:50] SPEAKER: hey, watch the developer stream.
[00:52] SPEAKER: Do you know where that's running from right now?
[00:53] SPEAKER: - Where is that running from right now?
[00:54] SPEAKER: - It's running from a Docker container
[00:57] SPEAKER: that's running FFmpeg on my NAS, Chet.
[01:00] SPEAKER: - What?
[01:01] SPEAKER: - On my NAS.
[01:02] SPEAKER: - I'm just gonna pull the curtain back here
[01:04] SPEAKER: in the show notes.
[01:06] SPEAKER: Bullet point number one, cold open, suck it, Chet.
[01:13] SPEAKER: Hey, you know what?
[01:14] SPEAKER: Turns out having a box sitting around with compute in it
[01:16] SPEAKER: that is on 24/7 and connected to the internet,
[01:18] SPEAKER: you can do some fun stuff with it.
[01:20] SPEAKER: And when you have that sitting there,
[01:22] SPEAKER: you have ideas for more fun stuff to do.
[01:24] SPEAKER: And sometimes those ideas benefit your workplace.
[01:27] SPEAKER: - Yeah, well, look, I'm gonna go and tell you.
[01:29] SPEAKER: It's like all you have is a hammer, everything's a nail.
[01:33] SPEAKER: - That's for sure.
[01:34] SPEAKER: - When you have it always on computer,
[01:36] SPEAKER: there's almost always something cool
[01:37] SPEAKER: you can come up to do with it.
[01:38] SPEAKER: - We talked about it.
[01:39] SPEAKER: We talked about it three years ago.
[01:40] SPEAKER: Oh my God, almost three years ago now.
[01:42] SPEAKER: Like when we went to work from home out of nowhere,
[01:45] SPEAKER: like I immediately started finding stuff for my NAS
[01:48] SPEAKER: to do that benefited work in all kinds of ways
[01:51] SPEAKER: in terms of streaming and storage.
[01:52] SPEAKER: And yeah, it's nice to have a tool, B-Link.
[01:55] SPEAKER: - Yeah.
[01:56] SPEAKER: - B-Link just doing it for you.
[01:58] SPEAKER: - Look, I gotta talk about my B-Link
[02:00] SPEAKER: 'cause the B-Link is some hot stuff.
[02:02] SPEAKER: - Your off-brand NUC.
[02:03] SPEAKER: - Look, it was really, it was way, NUCs are expensive now.
[02:06] SPEAKER: - NUCs are very expensive, you're not wrong.
[02:07] SPEAKER: They are hundreds of dollars.
[02:09] SPEAKER: - Yeah, and like, well,
[02:11] SPEAKER: but I mean, we're gonna talk about it in the episode.
[02:12] SPEAKER: We're gonna talk about other stuff too.
[02:13] SPEAKER: So just pre-AMBL for the people who are scared
[02:17] SPEAKER: that we're talking about server stuff in the cold open.
[02:19] SPEAKER: - That's at the end.
[02:20] SPEAKER: - Yeah, we're doing a grab bag today.
[02:22] SPEAKER: There's, we had like five topics
[02:24] SPEAKER: that we thought were probably worth talking about
[02:25] SPEAKER: and we cut it down to three or maybe four
[02:27] SPEAKER: if you want to count Suck It, Chet as a topic.
[02:30] SPEAKER: And I think we have a good show for you today.
[02:35] SPEAKER: - Well, now we have to prove it.
[02:36] SPEAKER: - Oh no.
[02:37] SPEAKER: (upbeat music)
[02:52] SPEAKER: (upbeat music continues)
[03:05] SPEAKER: - Welcome to "Brad and Will Made a Tech Pod."
[03:08] SPEAKER: I'm Will.
[03:08] SPEAKER: - I'm Brad.
[03:09] SPEAKER: - Yeah, but the always on,
[03:11] SPEAKER: I think we called it getting nasty back in the day.
[03:14] SPEAKER: - Mm-hmm, I think that's right.
[03:16] SPEAKER: - I believe that was our moniker
[03:17] SPEAKER: for finding something to do with an always on computer
[03:20] SPEAKER: that happened to be in your house.
[03:21] SPEAKER: - I believe, I believe that was the original name
[03:24] SPEAKER: of the kind of networking channel on the Discord.
[03:27] SPEAKER: - Yes.
[03:28] SPEAKER: - Before I changed it to just network things,
[03:30] SPEAKER: which I thought was maybe a little more G rated.
[03:33] SPEAKER: - I think people find it easier now
[03:35] SPEAKER: and it's less likely to attract shit posters, so.
[03:38] SPEAKER: Anyway, a lot of stuff,
[03:40] SPEAKER: like it was kind of a bonkers news week this week.
[03:43] SPEAKER: - Yeah, and not in a great way in most cases.
[03:46] SPEAKER: In fact, in just about all cases,
[03:48] SPEAKER: was there a single good piece of news?
[03:52] SPEAKER: I mean, there's been some nice space stuff,
[03:54] SPEAKER: there's been some other, like there's been a,
[03:57] SPEAKER: look, we're gonna talk about a couple of bad news stories.
[04:01] SPEAKER: - Yeah.
[04:02] SPEAKER: - Maybe with a little bit of a silver lining on one of them.
[04:04] SPEAKER: - Okay, all right, I look forward to hearing what that is.
[04:07] SPEAKER: - There's gonna be some schadenfreude,
[04:09] SPEAKER: and then we're gonna talk about my Beelink.
[04:11] SPEAKER: I bought a little Beelink server machine
[04:13] SPEAKER: that I'm using as a, it's like 150,
[04:16] SPEAKER: I think I paid 200 bucks for it
[04:18] SPEAKER: 'cause I bought the slightly upgraded version.
[04:20] SPEAKER: But it's a little compute cube
[04:23] SPEAKER: that has a Celeron N5-105 in it,
[04:26] SPEAKER: and 16 gigs of RAM, and a 500 gig SSD.
[04:30] SPEAKER: And I paid 200 bucks for it,
[04:31] SPEAKER: and I screwed it onto the wall of my garage.
[04:33] SPEAKER: - Now you're home labbing.
[04:35] SPEAKER: - Yeah, yeah, and I think I'm gonna put a little box
[04:38] SPEAKER: around it with a Sharpie that says server.
[04:41] SPEAKER: - That would be cool.
[04:42] SPEAKER: I don't think I like the term home lab.
[04:45] SPEAKER: I'm not sure, I can't decide,
[04:46] SPEAKER: but every time I say it or see it, I'm not sure.
[04:50] SPEAKER: - I associate it with Reddit in a way
[04:52] SPEAKER: that I associate some things that I find unpleasant,
[04:54] SPEAKER: like the idea of the PC master race,
[04:57] SPEAKER: which is a fucking terrible phrase.
[04:59] SPEAKER: - Well, at least to be fair,
[05:00] SPEAKER: like the term home lab is not fraught
[05:02] SPEAKER: in the same like racialized kind of way.
[05:05] SPEAKER: It's more just a little like grading in a non-specific way
[05:08] SPEAKER: that I can't quite define.
[05:10] SPEAKER: - Yeah, and it's like, I like the idea,
[05:13] SPEAKER: like conceptually, I'm gonna say,
[05:16] SPEAKER: I like the idea of an, hold on, Brad,
[05:19] SPEAKER: was that a Seaman Pro Club mug?
[05:21] SPEAKER: - Whoa, do you wanna try pronouncing that again?
[05:24] SPEAKER: - Brad, was that a Seaman Pro Shop mug?
[05:28] SPEAKER: That is pretty incredible.
[05:29] SPEAKER: - Yes, that is a Seaman Pro Shops coffee mug, yes.
[05:33] SPEAKER: - That is exquisite.
[05:34] SPEAKER: Anyway, I think it's because of the Reddit association.
[05:39] SPEAKER: - That's all it is, and like that's maybe not fair,
[05:42] SPEAKER: or maybe that's-
[05:42] SPEAKER: - No, 'cause that home lab subreddit
[05:44] SPEAKER: is a fine community of people, like from what I can tell.
[05:47] SPEAKER: - Honestly, there's just some vague recollection
[05:51] SPEAKER: of like forum SIGs 20 years ago with people posting
[05:54] SPEAKER: like 20 line breakdowns of their gaming rig or something.
[05:57] SPEAKER: You know what I mean?
[05:58] SPEAKER: It's like that hot rod culture of like, I don't know,
[06:01] SPEAKER: like I like the activity.
[06:03] SPEAKER: I don't know that some of the fervor around it is warranted.
[06:07] SPEAKER: - It's kind of like the everyday carry thing,
[06:09] SPEAKER: which went from being about like having a nice flashlight
[06:11] SPEAKER: and maybe a multi-tool in your pocket
[06:13] SPEAKER: to like what gun are you carrying now?
[06:16] SPEAKER: And like it got kind of weirdly extreme.
[06:19] SPEAKER: - It's one of those things where the means become the end.
[06:21] SPEAKER: You know, it's no longer like,
[06:22] SPEAKER: hey, I'm building this like home network stuff
[06:24] SPEAKER: to do things with.
[06:25] SPEAKER: It's like, I just need to make this thing
[06:27] SPEAKER: as big and bad-ass as I can.
[06:30] SPEAKER: - You know, I'm basically just running
[06:31] SPEAKER: a small company's IT department in my garage for no reason,
[06:35] SPEAKER: other than because it's available to me.
[06:37] SPEAKER: And I have like, once you have a rack,
[06:39] SPEAKER: you're gonna fill it, I think is the lesson of the home lab.
[06:42] SPEAKER: - Yeah, and then to be clear, do what makes you happy.
[06:44] SPEAKER: You know, like have fun with it.
[06:45] SPEAKER: - I certainly do.
[06:46] SPEAKER: I don't know.
[06:47] SPEAKER: There's something, it's not the doing it,
[06:49] SPEAKER: it's the kind of like, I don't know,
[06:51] SPEAKER: the kind of cheesy subculture around it is what,
[06:55] SPEAKER: okay, nevermind.
[06:56] SPEAKER: - You know what we're doing?
[06:57] SPEAKER: We're doing the thing that Chet did to us last week.
[06:58] SPEAKER: We're gatekeeping, Brad.
[06:59] SPEAKER: - I'm not here to judge.
[07:00] SPEAKER: - We're kink shaming.
[07:01] SPEAKER: - Well, it's gatekeeping.
[07:03] SPEAKER: They're fine to do it.
[07:04] SPEAKER: Just like, hey, maybe don't be,
[07:06] SPEAKER: to be a certain way when you talk about it, which is cool.
[07:08] SPEAKER: - Keep it to yourself, man.
[07:10] SPEAKER: - It's cool to be cool.
[07:11] SPEAKER: - Yeah.
[07:13] SPEAKER: So, okay, first news item, this one sucks.
[07:15] SPEAKER: There's no silver lining here.
[07:16] SPEAKER: - Yeah.
[07:17] SPEAKER: - There were a ton of layoffs this week,
[07:21] SPEAKER: including at, Microsoft laid off 10,000 people,
[07:25] SPEAKER: which is an incredible number of people,
[07:28] SPEAKER: at game studios, at main Microsoft campus,
[07:31] SPEAKER: around the world.
[07:32] SPEAKER: - Yeah.
[07:33] SPEAKER: - Amazon laid off a ton of people.
[07:34] SPEAKER: - I think Amazon was more.
[07:35] SPEAKER: I think, wasn't Amazon like 18,000?
[07:37] SPEAKER: - I didn't, I thought it was eight,
[07:39] SPEAKER: but I keep it wrong.
[07:40] SPEAKER: - No, Amazon is 18,000 positions, which is absolute.
[07:44] SPEAKER: - Google announced layoffs this morning,
[07:46] SPEAKER: as we were getting ready to record.
[07:47] SPEAKER: I don't have the details on that one yet.
[07:49] SPEAKER: - I think they're also in five figures.
[07:55] SPEAKER: 12,000, yeah, geez.
[07:57] SPEAKER: - I mean, that is, there's very little reason
[08:01] SPEAKER: to do this right now, given the amount of money
[08:03] SPEAKER: that these companies are still making.
[08:05] SPEAKER: It seems like it's literally just, hey, Facebook laid off
[08:10] SPEAKER: a bunch of people and Twitter laid off a bunch of people,
[08:11] SPEAKER: and a bunch of other people laid off a bunch of people,
[08:13] SPEAKER: and shareholders are going, hey, why aren't we laying off
[08:15] SPEAKER: a bunch of people?
[08:16] SPEAKER: We should lay off people too, everybody's laying off people.
[08:19] SPEAKER: And it sucks, it's a bad policy.
[08:23] SPEAKER: - Yeah, condolences, I mean, you know, smaller scale
[08:25] SPEAKER: in terms of numbers, layoffs hit people we know
[08:28] SPEAKER: in the games media.
[08:28] SPEAKER: - Yeah, well, and Riot, Giant Bomb, all over the place.
[08:33] SPEAKER: - So condolences to everyone who has lost their job
[08:36] SPEAKER: and their healthcare, it sucks a lot.
[08:38] SPEAKER: It's a shit start to the year.
[08:41] SPEAKER: Yesterday on an Ex-Lander stream,
[08:42] SPEAKER: I declared this shit January and I'm sticking to it.
[08:45] SPEAKER: - I think that's probably, well, so if you know jobs,
[08:49] SPEAKER: post them, help people if you can.
[08:50] SPEAKER: - Yes, yes, for sure.
[08:52] SPEAKER: - That's, and that goes for folks in the Discord too.
[08:54] SPEAKER: We have a job hunting channel that has,
[08:58] SPEAKER: it's gotten a lot of people jobs over the last few years.
[09:00] SPEAKER: - Yeah, it's cool, or even just advice, you know,
[09:02] SPEAKER: like just increasing your odds,
[09:04] SPEAKER: even if you don't have a direct lead or whatever.
[09:07] SPEAKER: - If we have people in there who are good at negotiating
[09:09] SPEAKER: pay raises and salaries and stuff like that,
[09:11] SPEAKER: then they can, they've been very generous with their time.
[09:13] SPEAKER: - Yeah, or, you know, even just stuff like, you know,
[09:15] SPEAKER: giving people sample interview questions, you know,
[09:17] SPEAKER: people who do interviews as part of their job
[09:20] SPEAKER: can help people who are about to take interviews.
[09:22] SPEAKER: - Yeah.
[09:23] SPEAKER: - Things like that.
[09:24] SPEAKER: I'm sure you've encountered this,
[09:26] SPEAKER: the narrative about all these layoffs
[09:28] SPEAKER: generally has been like, oh,
[09:30] SPEAKER: we hired way too much during the pandemic
[09:32] SPEAKER: and then growth didn't reflect that headcount increase.
[09:36] SPEAKER: Like that's what, that seems to be the line
[09:38] SPEAKER: for most places.
[09:40] SPEAKER: - I mean, here's the thing, everybody is seeing
[09:42] SPEAKER: a contraction in revenue as people stay home.
[09:45] SPEAKER: Like the companies that were making a bunch of money,
[09:46] SPEAKER: like Microsoft and Sony, and I mean,
[09:50] SPEAKER: I actually don't think Sony's done layoffs yet,
[09:51] SPEAKER: but like the game industry saw a massive explosion
[09:56] SPEAKER: in profit in 2020 because everybody was staying home, right?
[10:01] SPEAKER: The thing is we're still above the 2020 numbers
[10:03] SPEAKER: when people started hiring up.
[10:05] SPEAKER: So, you know, this is just taking a little bit
[10:08] SPEAKER: of a trim off the top and saving the people at the top
[10:13] SPEAKER: that get the big paychecks a little bit more money.
[10:16] SPEAKER: - Yeah, we might still be above the 2020 numbers,
[10:19] SPEAKER: but are we enough above them to keep these employees
[10:22] SPEAKER: asks the executive?
[10:24] SPEAKER: - Well, I think that there's a, and this is gonna,
[10:27] SPEAKER: it's funny, so we're gonna talk about Apple here for a sec.
[10:31] SPEAKER: Big shout out to Tim Cook for cutting his pay.
[10:34] SPEAKER: I mean, part of it was a response to last year.
[10:36] SPEAKER: They overpaid him and shareholders
[10:38] SPEAKER: were not thrilled with that.
[10:40] SPEAKER: - Yeah, and you know, I mean,
[10:41] SPEAKER: we should point out like post-pay cut,
[10:44] SPEAKER: I think he's still taking home like $50 million this year.
[10:48] SPEAKER: - Tim Cook's gonna be fine, Brad.
[10:49] SPEAKER: Don't, you don't have to worry about him.
[10:50] SPEAKER: - Yeah, sure, so I mean, like, you know,
[10:51] SPEAKER: certainly it's easy to sneer at this for some people,
[10:54] SPEAKER: but like it is, you know, like Iwata did that at Nintendo
[10:58] SPEAKER: years and years ago when they underperformed and like,
[11:00] SPEAKER: you know, whether or not he is still like
[11:03] SPEAKER: the wildly compensated, it's still a lot more
[11:06] SPEAKER: than most other CEOs are doing.
[11:08] SPEAKER: - Well, he's less, he is less compensated than another,
[11:14] SPEAKER: than CEOs at comparable sized companies are.
[11:16] SPEAKER: Like when you're talking about the largest company
[11:18] SPEAKER: in the world or the third largest company in the world
[11:20] SPEAKER: by market cap, he is much, much less compensated
[11:24] SPEAKER: than those folks.
[11:25] SPEAKER: Now, like, is it still right that he makes $49 million
[11:30] SPEAKER: and somebody who's assembling phones in a factory
[11:31] SPEAKER: is making $2 an hour?
[11:33] SPEAKER: No, fuck that, that's terrible.
[11:35] SPEAKER: But at least they're not laying off tens of thousands
[11:38] SPEAKER: of people and he's not taking a pay cut at the same time.
[11:42] SPEAKER: - Yeah, do they commit to no layoffs?
[11:44] SPEAKER: - No, of course not, nobody ever commits
[11:46] SPEAKER: to no layoffs, Brad.
[11:47] SPEAKER: - Okay, sure.
[11:49] SPEAKER: - The thing, the other thing that I think
[11:52] SPEAKER: this is all highlighting is so much of how a company
[11:57] SPEAKER: is doing in the eyes of Wall Street and Stark Market
[11:59] SPEAKER: and analysts and all that stuff has to do with the growth.
[12:03] SPEAKER: And we're reaching a point with Apple and Google
[12:07] SPEAKER: in terms of smartphone share where there's not
[12:08] SPEAKER: any more growth to be had.
[12:10] SPEAKER: Like the easy growth is done.
[12:11] SPEAKER: Everybody who's gonna buy a smartphone before long
[12:13] SPEAKER: will have a smartphone.
[12:14] SPEAKER: And then we get into Apple and Google going at each other
[12:18] SPEAKER: to eat into each other's smartphone markets
[12:20] SPEAKER: and they're increasingly entrenched
[12:21] SPEAKER: and growth isn't going to drive those massive
[12:24] SPEAKER: trillion dollar scale businesses anymore.
[12:26] SPEAKER: And we're going to have to, the last century
[12:32] SPEAKER: of economics growth for the world, GDP,
[12:36] SPEAKER: has been based on bringing stuff that people have
[12:38] SPEAKER: in the West to the other less developed parts of the world.
[12:42] SPEAKER: And that stops.
[12:45] SPEAKER: When everybody gets a cellphone, you can't sell
[12:48] SPEAKER: more cellphones to people that don't have cellphones.
[12:51] SPEAKER: Nobody's gonna buy two smartphones.
[12:52] SPEAKER: Most people aren't gonna buy, some people buy
[12:54] SPEAKER: two smartphones, I know.
[12:55] SPEAKER: But anyway, the upshot is we're gonna have,
[12:58] SPEAKER: like the growth focus is one of the things
[13:01] SPEAKER: that is destroying the planet.
[13:02] SPEAKER: And we have to, as a society and as an economy,
[13:07] SPEAKER: you know, get rid of the people who are really
[13:09] SPEAKER: enthusiastic about that.
[13:10] SPEAKER: I, you know, the French had solutions for this.
[13:13] SPEAKER: That's all I'm saying.
[13:13] SPEAKER: - Interesting choice of words, sure.
[13:16] SPEAKER: Speaking of haircuts.
[13:18] SPEAKER: - Yeah.
[13:21] SPEAKER: - Yeah, you know, socioeconomic system that did not
[13:25] SPEAKER: prioritize endless unsustainable growth
[13:27] SPEAKER: and that did not constantly empower psychopaths
[13:30] SPEAKER: at all levels of management and government
[13:32] SPEAKER: would be pretty cool.
[13:34] SPEAKER: - Hey, speaking of psychopaths, New York Times.
[13:37] SPEAKER: - Sorry, I just, there was a, God, who ran it?
[13:41] SPEAKER: It was a New York Times, Washington Post.
[13:43] SPEAKER: I forget, one of the major newspapers ran a big story
[13:46] SPEAKER: this week that was highlighting, mostly highlighting
[13:48] SPEAKER: passages from a paper from like 2018.
[13:50] SPEAKER: It's been a few years.
[13:51] SPEAKER: I think the study was done in the wake of Trump
[13:53] SPEAKER: getting elected and stuff, but like,
[13:55] SPEAKER: it was a pair of psychologists in somewhere in Scandinavia,
[13:59] SPEAKER: maybe Norway, and anyway, strong determination
[14:03] SPEAKER: that, yeah, I mean, news to nobody that psychopath do,
[14:08] SPEAKER: like people with actual demonstrable psychopathic traits
[14:12] SPEAKER: tend to do very well in the systems of government
[14:15] SPEAKER: and corporate management that we currently have.
[14:18] SPEAKER: And also, I mean, following on from that,
[14:20] SPEAKER: like in the environment of extreme polarization
[14:22] SPEAKER: that we're in, they do even better,
[14:24] SPEAKER: that those types of people even more
[14:25] SPEAKER: tend to rise to the top.
[14:27] SPEAKER: Anyway, it was very grim.
[14:29] SPEAKER: - That sounds fun.
[14:30] SPEAKER: What a fun read.
[14:32] SPEAKER: Okay, so I've been talking about Tesla
[14:36] SPEAKER: and full self-driving and autopilot for,
[14:39] SPEAKER: it seems like 10 years now, it's not been quite that long,
[14:41] SPEAKER: but we talked about this on,
[14:43] SPEAKER: this is only a test a long time.
[14:45] SPEAKER: First with kind of awe and then with,
[14:47] SPEAKER: oh, this is gonna get people killed
[14:49] SPEAKER: and it's gonna set back the actual cause
[14:51] SPEAKER: of self-driving cars a long way
[14:53] SPEAKER: because these people are clearly assholes.
[14:55] SPEAKER: - What was there?
[14:56] SPEAKER: I mean, I wasn't really paying close attention
[14:58] SPEAKER: to the stuff back then.
[14:59] SPEAKER: Was there a period of pure awe for you guys on that show
[15:02] SPEAKER: before reality started kicking in?
[15:04] SPEAKER: - Yeah, I mean, look, absolutely.
[15:07] SPEAKER: I will, when you see, so there's a,
[15:11] SPEAKER: what is now a famous video
[15:14] SPEAKER: and I'm gonna go to the actual Vimeo page.
[15:16] SPEAKER: It's called Full Self-Driving Hardware on All Teslas.
[15:19] SPEAKER: It's from six years ago, so that would've been 2016.
[15:23] SPEAKER: That was after I was off, this is only a test,
[15:24] SPEAKER: but he was talking about this before then
[15:27] SPEAKER: as a conceptual thing, I think, before that.
[15:34] SPEAKER: It showed somebody sitting there with their thumbs
[15:36] SPEAKER: just kind of resting on the steering wheel of the car
[15:37] SPEAKER: and driving around a neighborhood in Palo Alto,
[15:39] SPEAKER: it looks like, and getting on 280 and getting off 280
[15:43] SPEAKER: and merging onto the, on and off the freeway
[15:46] SPEAKER: and pulling into a parking lot
[15:47] SPEAKER: and you're like, this is fucking incredible, right?
[15:49] SPEAKER: This is truly magic, even if the demo is cooked,
[15:52] SPEAKER: which, oh, by the way, spoiler alert, it was fucking cooked.
[15:55] SPEAKER: - So when did that come out?
[15:56] SPEAKER: Was that just this week? - Yesterday, three days ago.
[15:58] SPEAKER: - Literally just the last few days that it,
[16:00] SPEAKER: I think that was testified by a Tesla engineer, right?
[16:04] SPEAKER: Or former?
[16:05] SPEAKER: - Somebody went on the record
[16:06] SPEAKER: with either the New York Times or the Verge,
[16:09] SPEAKER: but also it was part of the discovery
[16:11] SPEAKER: in one of the many lawsuits against Tesla
[16:15] SPEAKER: from people whose family members were killed
[16:17] SPEAKER: by cars that were in autopilot or full software.
[16:19] SPEAKER: So, okay, so history.
[16:21] SPEAKER: There's autopilot driver assist system,
[16:23] SPEAKER: which was basically like every other driver assist system
[16:26] SPEAKER: in the world in that it would keep in a lane kind of,
[16:30] SPEAKER: and it would keep you from smashing into a car
[16:32] SPEAKER: in front of you on the freeway if you were driving
[16:34] SPEAKER: and not like, it was like adaptive cruise control basically.
[16:37] SPEAKER: - And then to be clear as someone
[16:38] SPEAKER: who doesn't drive regularly, like every car maker
[16:41] SPEAKER: has some version of that, right?
[16:43] SPEAKER: - Not at the time, like it was a new technology.
[16:46] SPEAKER: - Oh now, these days though, what I mean.
[16:48] SPEAKER: - These days everybody, like it's an option on most cars.
[16:51] SPEAKER: - Kind of, it's the thing that'll just beep at you
[16:52] SPEAKER: if it senses that you're drifting into the other lane,
[16:55] SPEAKER: that kind of thing.
[16:55] SPEAKER: - No, it'll actually turn the wheel.
[16:57] SPEAKER: - Or it's actually corrective, right?
[16:58] SPEAKER: - Yeah, like if you, like I drove a Hyundai
[17:00] SPEAKER: when I had to go to LA a few months ago
[17:02] SPEAKER: or years ago now, I guess,
[17:04] SPEAKER: that had the full self-driving Nissan,
[17:07] SPEAKER: like rental cars often have it
[17:09] SPEAKER: and it'll keep you in the lane
[17:10] SPEAKER: and it uses cameras generally
[17:11] SPEAKER: to see where the lines on the road are and the markers are.
[17:15] SPEAKER: And usually it starts with like a little nudge on the wheel
[17:17] SPEAKER: and then it'll actually turn the wheel
[17:19] SPEAKER: to get you back in the lane if you're drifting.
[17:21] SPEAKER: And then the adaptive cruise control
[17:22] SPEAKER: will break and accelerate to keep you
[17:24] SPEAKER: at a specified distance from the cars in front of you.
[17:26] SPEAKER: And if like traffic on the freeway stops,
[17:29] SPEAKER: the car will stop.
[17:32] SPEAKER: So this New York Times article came out earlier this week
[17:35] SPEAKER: and it's mostly reporting it seems like
[17:39] SPEAKER: is based on discovery from these trials
[17:41] SPEAKER: that are happening around the country right now.
[17:44] SPEAKER: And I'm gonna go and tell you, it's damning.
[17:47] SPEAKER: - It's pretty damning. - It's worse than I expected.
[17:48] SPEAKER: - It's kind of terrifying in a lot of ways,
[17:50] SPEAKER: not just in terms of the technology
[17:52] SPEAKER: that is now being employed on the road,
[17:56] SPEAKER: but also in the sense that you're seeing these people
[17:59] SPEAKER: that are in the grip of ideological blind faith,
[18:03] SPEAKER: I guess is the only way I can describe it.
[18:05] SPEAKER: - Delusional is what I would say.
[18:06] SPEAKER: - It's kind of chilling.
[18:09] SPEAKER: This was in the New York Times Magazine.
[18:10] SPEAKER: The title of the piece is Elon Musk's
[18:12] SPEAKER: Appetite for Destruction.
[18:14] SPEAKER: - Yeah.
[18:20] SPEAKER: The story is a reporter who reports on these,
[18:24] SPEAKER: he talks about these fatal car crashes that killed people.
[18:30] SPEAKER: And then he goes out and finds people
[18:33] SPEAKER: who are seemingly rational human beings
[18:36] SPEAKER: who also self-identify as Tesla fans
[18:39] SPEAKER: who wanna show them how good the software actually is.
[18:42] SPEAKER: - It's funny, he kind of starts this piece
[18:44] SPEAKER: by talking about the two categories of people
[18:48] SPEAKER: who wouldn't talk to him about this topic.
[18:52] SPEAKER: One of whom is people engaged in litigation
[18:54] SPEAKER: so they can't speak on the advice of counsel.
[18:57] SPEAKER: And I believe the other type was people
[18:59] SPEAKER: who didn't want to disparage Tesla or Elon Musk
[19:03] SPEAKER: in public because they love both so much
[19:05] SPEAKER: despite having bad experiences with full self-driving.
[19:09] SPEAKER: - Yeah, that seems right.
[19:11] SPEAKER: - So what I'm getting at is the filtering mechanism
[19:13] SPEAKER: for who would speak for the story
[19:15] SPEAKER: turned out to be the zealots, the true believers,
[19:17] SPEAKER: the people who, like you said, are delusional.
[19:22] SPEAKER: - Well, and the pattern with the,
[19:25] SPEAKER: okay, so there's multiple parts of this.
[19:26] SPEAKER: One is he finds people who are actually
[19:31] SPEAKER: in non-fatal, for the most part, accidents
[19:38] SPEAKER: where they, like one guy was driving down,
[19:41] SPEAKER: I think highway one,
[19:42] SPEAKER: or basically just a road in Laguna Beach,
[19:45] SPEAKER: and the car swerved out of the lane
[19:49] SPEAKER: while it was in self-driving
[19:50] SPEAKER: and smashed into the back of a parked police car.
[19:52] SPEAKER: - Yes, yes, along with what they describe
[19:55] SPEAKER: as a very simple two-lane straight mile stretch of road.
[20:01] SPEAKER: They never, I guess, arrived at a reason
[20:03] SPEAKER: for this specific bug,
[20:04] SPEAKER: but they said in this period of time,
[20:07] SPEAKER: FSD had a tendency to smash into police cars,
[20:10] SPEAKER: parked police cars.
[20:11] SPEAKER: - The flashing lights were listed as a,
[20:14] SPEAKER: maybe in one of the other articles,
[20:15] SPEAKER: but that guy said stationary objects are a problem
[20:19] SPEAKER: and flashing lights are confusing.
[20:21] SPEAKER: So, you know, be careful driving your Teslas
[20:23] SPEAKER: around stationary objects.
[20:25] SPEAKER: - I just, I don't think we need to get any further
[20:26] SPEAKER: into describing the details of this piece
[20:29] SPEAKER: before we just go, how is this possible
[20:32] SPEAKER: that it's allowed for this thing to be beta tested
[20:34] SPEAKER: in this state on public roads, putting people in danger?
[20:37] SPEAKER: I just cannot.
[20:39] SPEAKER: - Well, I do think it's worth talking about
[20:42] SPEAKER: the way this is presented,
[20:43] SPEAKER: 'cause that's the crux of a lot of these lawsuits,
[20:45] SPEAKER: it sounds like.
[20:46] SPEAKER: They're talking about the way autopilot is presented
[20:48] SPEAKER: as something more than a driver assist, right?
[20:53] SPEAKER: As a, hey, like the video starts,
[20:58] SPEAKER: the video that Tesla posted, the famous video
[21:00] SPEAKER: with painted black playing in the background
[21:02] SPEAKER: starts with Elon testing a link
[21:06] SPEAKER: that says Tesla drives itself
[21:08] SPEAKER: and the video opens with white text on a black screen
[21:11] SPEAKER: that says the person in the driver's seat
[21:13] SPEAKER: is only there for legal reasons.
[21:14] SPEAKER: He's not doing anything.
[21:15] SPEAKER: The car is driving itself.
[21:16] SPEAKER: The video is a fucking lie.
[21:18] SPEAKER: - Yeah.
[21:19] SPEAKER: - Like there was somebody maintaining the gas and the brake.
[21:22] SPEAKER: They don't know, they don't say how it happened,
[21:23] SPEAKER: but multiple people at Tesla testified or told reporters
[21:28] SPEAKER: that it was a cooked video on a pre-planned course
[21:32] SPEAKER: that was not representative of the software
[21:34] SPEAKER: that was in the place.
[21:35] SPEAKER: Now, the thing that happened immediately after this
[21:37] SPEAKER: is a bunch of dipshits got out in their Teslas,
[21:39] SPEAKER: downloaded the software as soon as it was available,
[21:41] SPEAKER: and then did the exact same fucking thing
[21:43] SPEAKER: in a way that endangers everybody else that's on the road.
[21:46] SPEAKER: Now, like some fundamentals.
[21:48] SPEAKER: People are shit at driving cars, right?
[21:51] SPEAKER: I think everybody who's spent any time on an American road
[21:54] SPEAKER: will agree that as a country, not great drivers.
[21:58] SPEAKER: People are distracted.
[21:59] SPEAKER: People are turning around yelling at their kids.
[22:01] SPEAKER: They're swerving all over the place.
[22:03] SPEAKER: - Road raging.
[22:04] SPEAKER: - They're angry.
[22:05] SPEAKER: They're going too fast.
[22:06] SPEAKER: They're weaving.
[22:07] SPEAKER: I am fucking first in line.
[22:09] SPEAKER: - Falling too close behind.
[22:10] SPEAKER: - Yeah, I am all about letting the machines take over
[22:14] SPEAKER: and drive cars for us.
[22:14] SPEAKER: I think that is a great idea long-term.
[22:17] SPEAKER: Now, the problem, this is the thing we talked about
[22:19] SPEAKER: and this is only a test a lot.
[22:20] SPEAKER: The problem, so apologies for remapping
[22:23] SPEAKER: decade-old arguments at this point,
[22:25] SPEAKER: but the problem is that when people,
[22:30] SPEAKER: when new technology replaces something
[22:32] SPEAKER: that people have traditionally done,
[22:33] SPEAKER: people are inherently skeptical of it
[22:35] SPEAKER: and are unlikely to trust the machines out of the gate,
[22:40] SPEAKER: which is why companies like Waymo, Google,
[22:43] SPEAKER: and a bunch of others were incredibly careful
[22:45] SPEAKER: with the self-driving technology.
[22:47] SPEAKER: Only using it on their campuses at first.
[22:48] SPEAKER: They were doing incredibly limited things.
[22:50] SPEAKER: They had people sitting behind the wheel of the car
[22:54] SPEAKER: with constant attention, hands on the wheel,
[22:56] SPEAKER: ready to take over when the machine made a mistake,
[22:57] SPEAKER: 'cause the machines make mistakes, right?
[23:00] SPEAKER: So any mistake that kills people,
[23:03] SPEAKER: even though ultimately getting self-driving cars online
[23:06] SPEAKER: will probably save more lives than it takes
[23:07] SPEAKER: during the beta period
[23:08] SPEAKER: that we're all suffering through right now,
[23:11] SPEAKER: any perception of the machines being bad at this
[23:15] SPEAKER: and killing people unnecessarily
[23:17] SPEAKER: is going to result in legislation and litigation
[23:19] SPEAKER: and it will slow the whole thing down.
[23:21] SPEAKER: So you can't be an asshole about it.
[23:24] SPEAKER: You have to be smart and you have to be deliberate
[23:26] SPEAKER: and you have to be safe.
[23:29] SPEAKER: And now, as, when we're gonna put links to the article,
[23:32] SPEAKER: you should read the article.
[23:34] SPEAKER: As reported in this incredible article in New York Times,
[23:39] SPEAKER: they had, they believed that the ethics,
[23:42] SPEAKER: Tesla, Musk, believed that the ethics
[23:45] SPEAKER: of getting self-driving cars online
[23:49] SPEAKER: was such that no matter what the cost was getting it online,
[23:53] SPEAKER: they would ultimately save more lives.
[23:56] SPEAKER: Therefore, whatever they needed to do was necessary,
[23:58] SPEAKER: including cooking videos
[23:59] SPEAKER: and releasing software that wasn't ready
[24:01] SPEAKER: and they knew had problems and they knew would kill people.
[24:04] SPEAKER: - Yeah, when I say this is an article about blind faith,
[24:06] SPEAKER: I mean it in two senses.
[24:07] SPEAKER: One, blind faith on the part of Tesla fans
[24:10] SPEAKER: for Tesla and Elon Musk's mission.
[24:14] SPEAKER: Also blind faith on his part
[24:15] SPEAKER: toward his kind of utilitarian view of philanthropy
[24:20] SPEAKER: or how do you wanna term his like,
[24:23] SPEAKER: I mean, is he termed like long-termism thrown around?
[24:26] SPEAKER: You know, he's got some abstract belief in, you know,
[24:33] SPEAKER: if I can claim to be serving a vast number
[24:38] SPEAKER: of future humans who don't exist,
[24:40] SPEAKER: then it's than any kind of excesses
[24:42] SPEAKER: that harm existing living actual humans now are justifiable.
[24:47] SPEAKER: - Well, yeah, it's like a savior complex, right?
[24:49] SPEAKER: - Yes, yes.
[24:51] SPEAKER: - They didn't, so as an example,
[24:56] SPEAKER: they didn't wanna put driver monitoring in them,
[24:58] SPEAKER: which ensures that the driver's paying attention
[25:00] SPEAKER: and actually, you know, driving the car
[25:02] SPEAKER: when the autopilot stuff was on.
[25:05] SPEAKER: I mean, honestly, even naming it autopilot that long ago
[25:09] SPEAKER: is offensively stupid at this point to me.
[25:12] SPEAKER: - It's probably disingenuous.
[25:13] SPEAKER: I mean, a big part of the problem here
[25:14] SPEAKER: you can see reading this piece is the messaging
[25:16] SPEAKER: because they even point out that there's fine print
[25:18] SPEAKER: around full self-driving that for I'm sure legal reasons
[25:22] SPEAKER: specifies like, hey, this is,
[25:23] SPEAKER: I don't remember what the term is,
[25:25] SPEAKER: but they describe it in the fine print as a driver assist
[25:28] SPEAKER: at the same time that he is out there
[25:29] SPEAKER: and of course everybody's gonna pay attention
[25:31] SPEAKER: to what the, you know, once in a century industrialists,
[25:35] SPEAKER: entrepreneur, genius brainchild is saying.
[25:37] SPEAKER: - Real life Tony Stark, I think is what we used to call him.
[25:40] SPEAKER: - Right, like the straight up propaganda.
[25:43] SPEAKER: I don't really, I can't think of another word for it
[25:45] SPEAKER: coming out of his mouth
[25:46] SPEAKER: is what's gonna get all the attention
[25:47] SPEAKER: and he's out there saying like, oh, it's perfect.
[25:49] SPEAKER: We're gonna save so many lives.
[25:50] SPEAKER: Like computers drive cars better than humans do.
[25:53] SPEAKER: Like, come on, like it's infuriating.
[25:56] SPEAKER: - Yeah, like, look, here is the,
[26:00] SPEAKER: here is the, Musk said in 2019,
[26:03] SPEAKER: if you have a system that's at
[26:04] SPEAKER: or below human level reliability,
[26:06] SPEAKER: then driver monitoring makes sense.
[26:08] SPEAKER: But if your system is dramatically better,
[26:10] SPEAKER: more reliable than a human,
[26:11] SPEAKER: then monitoring doesn't help much.
[26:12] SPEAKER: That's a tweet, I think.
[26:15] SPEAKER: One of the legal complaints says it explicitly,
[26:18] SPEAKER: which is Tesla's contact conduct was despicable
[26:21] SPEAKER: and so contemptible that it would be looked down upon
[26:23] SPEAKER: and despised by ordinary decent people.
[26:25] SPEAKER: - Yeah, that's kind of where I'm at with the whole thing.
[26:27] SPEAKER: I mean.
[26:29] SPEAKER: - We don't need to go build the labor further, but yeah.
[26:33] SPEAKER: It's like, this is like Ralph Nader,
[26:37] SPEAKER: unsafe at any speed territory,
[26:39] SPEAKER: except for this feels much more real than the Ralph Nader,
[26:42] SPEAKER: like the Ralph Nader stuff.
[26:46] SPEAKER: Yeah, bad design.
[26:49] SPEAKER: I don't know.
[26:50] SPEAKER: I'm not an expert on that kind of, that era of car design.
[26:52] SPEAKER: It seems like maybe he went a little,
[26:54] SPEAKER: it was a little overblown.
[26:55] SPEAKER: I now treat, when I see a Tesla on the road in front of me,
[26:58] SPEAKER: like I've said this before in this podcast,
[27:00] SPEAKER: there's a place on one where I watch them swerve
[27:02] SPEAKER: off of the road and come back on every fucking day.
[27:04] SPEAKER: - Wow.
[27:05] SPEAKER: - Yeah.
[27:06] SPEAKER: - I mean, dude, I,
[27:09] SPEAKER: the deployment of this feature in this state
[27:11] SPEAKER: is just such an example of reckless, arrogant excess
[27:15] SPEAKER: that I don't know what to say about it.
[27:16] SPEAKER: I mean, like, obviously there's value in this feature
[27:19] SPEAKER: if and when it works properly,
[27:20] SPEAKER: but it seems like that should come from like defined
[27:23] SPEAKER: industry-wide standards that all automakers collaborate on
[27:26] SPEAKER: and adhere to, right?
[27:27] SPEAKER: Like not one, you know,
[27:30] SPEAKER: like there's one guy just kind of going off on his own
[27:33] SPEAKER: and shoving this thing out into the world
[27:34] SPEAKER: and killing people with it.
[27:36] SPEAKER: - Yeah, like, I think that, I mean,
[27:39] SPEAKER: the applying that this is the long-term,
[27:44] SPEAKER: ultimately this feature will save more lives
[27:46] SPEAKER: than it costs metrics to this.
[27:49] SPEAKER: It means that these people shouldn't be trusted
[27:52] SPEAKER: to roll out the software, right?
[27:55] SPEAKER: And they absolutely shouldn't be trusted to self-report data
[27:58] SPEAKER: about crashes and safety and need monitoring.
[28:00] SPEAKER: Like, I think that's, if anything comes of this,
[28:03] SPEAKER: I hope to God that they get this done in the next two years
[28:06] SPEAKER: before the next election cycle,
[28:08] SPEAKER: because like at this point, when I see a Tesla on the road,
[28:11] SPEAKER: I'm treating it like the same way I treat somebody
[28:13] SPEAKER: who I see that's swerving and I think might be drunk
[28:16] SPEAKER: before I call the, you know, the police on the drunk driver.
[28:19] SPEAKER: - Yeah, it's all very frustrating.
[28:22] SPEAKER: Like the fact that this is happening this way,
[28:24] SPEAKER: it just feels like another example to me
[28:25] SPEAKER: of the kind of degenerated regulatory environment
[28:28] SPEAKER: that we're in that also allows egg makers
[28:30] SPEAKER: to triple their prices in the space of a year
[28:33] SPEAKER: and increase their profits a thousand percents
[28:36] SPEAKER: and nothing happened, you know what I mean?
[28:38] SPEAKER: Like it just did corporate excess is just,
[28:40] SPEAKER: hey, not news to anybody.
[28:42] SPEAKER: It's a bit out of control.
[28:44] SPEAKER: - Well, and to contrast it with,
[28:47] SPEAKER: like there's a couple of self-driving startups
[28:51] SPEAKER: in San Francisco, Waymo and Cruz
[28:53] SPEAKER: are both letting people order self-driving rides on maps.
[28:56] SPEAKER: And I think one of them is driverless now and Waymo,
[28:59] SPEAKER: I think Cruz doesn't have drivers anymore and Waymo does.
[29:02] SPEAKER: People post videos of those cruise cars
[29:05] SPEAKER: doing weird shit all the time, right?
[29:09] SPEAKER: But they don't, they seem to air on the side
[29:13] SPEAKER: of extreme safety and they're mostly in places
[29:15] SPEAKER: where they're going at very low speeds,
[29:16] SPEAKER: like 25 or 40 miles an hour at the outside.
[29:19] SPEAKER: Like they're not getting on freeways.
[29:21] SPEAKER: The Waymo cars still have people in the car.
[29:24] SPEAKER: It's a safer, more measured approach
[29:25] SPEAKER: and it's in an extremely limited geographical area.
[29:28] SPEAKER: So it's a much more tractable problem.
[29:30] SPEAKER: So-
[29:31] SPEAKER: - I'm sorry, I see those Waymo cars
[29:34] SPEAKER: everywhere around here with a little spinny device
[29:39] SPEAKER: on the top.
[29:40] SPEAKER: - You should take a ride in one, Brad, and report back.
[29:44] SPEAKER: But my point is, like I do, I firmly believe
[29:48] SPEAKER: that when we get to a point where this technology
[29:50] SPEAKER: is good and reliable, it will save a lot of lives.
[29:54] SPEAKER: Like I think that Tesla is wrong with that.
[29:56] SPEAKER: I think that using that as an excuse to be reckless
[29:58] SPEAKER: and dangerous is offensive and stupid
[30:00] SPEAKER: and they should be regulated,
[30:03] SPEAKER: they should have the shit regulated out of them.
[30:04] SPEAKER: - Yes, absolutely.
[30:05] SPEAKER: Like the goal itself, obviously,
[30:07] SPEAKER: the value of the goal is self-evident,
[30:08] SPEAKER: but it should be achieved in a collaborative
[30:12] SPEAKER: and measured way.
[30:14] SPEAKER: Last thing I'll mention about this, just again,
[30:16] SPEAKER: with the kind of religious conviction
[30:18] SPEAKER: that a lot of people seem to have about this stuff.
[30:20] SPEAKER: The other major example of someone
[30:22] SPEAKER: who would talk to this reporter who had issues
[30:24] SPEAKER: with their full self-driving was less catastrophic
[30:27] SPEAKER: than plowing into a police cruiser.
[30:29] SPEAKER: It was, I think it was just running a red light
[30:31] SPEAKER: and nobody was injured.
[30:32] SPEAKER: - Yeah.
[30:33] SPEAKER: - But there's an example given in here
[30:34] SPEAKER: of he's part of a Tesla Reddit community
[30:36] SPEAKER: and he got a ton of shit from other people
[30:38] SPEAKER: in this community for posting a video of that happening.
[30:40] SPEAKER: It's like, here's tangible video evidence
[30:42] SPEAKER: of this thing malfunctioning
[30:44] SPEAKER: and everybody is basically attacking him
[30:46] SPEAKER: for undermining their faith or whatever.
[30:47] SPEAKER: And he clearly is also a true believer,
[30:49] SPEAKER: but he's at least got enough sense to say like,
[30:51] SPEAKER: hey, if we don't point out their examples,
[30:53] SPEAKER: how are they going to improve?
[30:54] SPEAKER: I'm sorry, if we don't point out their faults,
[30:56] SPEAKER: how are they going to improve on them?
[30:59] SPEAKER: - And there's an example of,
[31:00] SPEAKER: I think it's that guy or one of the other ones that says,
[31:03] SPEAKER: here's a place where it always has problems.
[31:04] SPEAKER: And then he'd gotten an update that night
[31:06] SPEAKER: before the reporter got in the car with him.
[31:08] SPEAKER: And guess what?
[31:10] SPEAKER: It was fixed at that time.
[31:11] SPEAKER: - It was fixed, but then proceeded
[31:13] SPEAKER: to have a half a dozen other issues
[31:14] SPEAKER: on the way home from there.
[31:15] SPEAKER: - Well, and also at the conclusion of the article
[31:20] SPEAKER: is the reporter running a Tesla and driving the route
[31:24] SPEAKER: that was the cause of a fatal accident
[31:27] SPEAKER: for the people that weren't in the Tesla.
[31:29] SPEAKER: - Right, the Tesla ran a red light and hit two poor schmucks
[31:34] SPEAKER: that were just on the road at the same time.
[31:35] SPEAKER: - Yes, and killed them.
[31:37] SPEAKER: - And killed them, and that seemed to not be fixed.
[31:41] SPEAKER: - Yes, yes.
[31:41] SPEAKER: - The implication is that that was not fixed.
[31:43] SPEAKER: - Yes.
[31:44] SPEAKER: - Anyway.
[31:45] SPEAKER: - That's a pretty pointed way to end this piece.
[31:46] SPEAKER: Last thing I'll say, look, I get quoting a novelist,
[31:50] SPEAKER: maybe a little trite here,
[31:51] SPEAKER: but I really liked the quote from Jeanette Winterson,
[31:55] SPEAKER: the novelist in this piece.
[31:57] SPEAKER: "True believers would rather see governments topple
[31:59] SPEAKER: than history rewritten than scuff the cover of their faith."
[32:03] SPEAKER: Like that really sums up kind of everything going on
[32:06] SPEAKER: in this article, I think.
[32:07] SPEAKER: Anyway.
[32:08] SPEAKER: (upbeat music)
[32:15] SPEAKER: - Since the dawn of Twitter, basically,
[32:17] SPEAKER: third-party clients have been a key feature
[32:20] SPEAKER: to the point that like when Twitter needed
[32:22] SPEAKER: to make its own desktop client,
[32:24] SPEAKER: its own mobile client for iOS,
[32:28] SPEAKER: instead of building their own internally,
[32:30] SPEAKER: they just went out and bought one of the popular
[32:33] SPEAKER: third-party clients for Mac and iOS.
[32:36] SPEAKER: Tweety.
[32:37] SPEAKER: - Tweety, wasn't it?
[32:38] SPEAKER: Yeah, man, I was a fairly enthusiastic paid Tweety user,
[32:41] SPEAKER: and then they just came and bought it and killed it.
[32:43] SPEAKER: - Yep, that's when I switched to Tweetbot,
[32:45] SPEAKER: if I recall, or shortly thereafter.
[32:49] SPEAKER: To the point that one of the third-party clients,
[32:51] SPEAKER: Twitterific, basically was the origin of the Bluebird,
[32:55] SPEAKER: like Twitterific's Bluebird and Twitter's Bluebird
[32:57] SPEAKER: are different, but Twitter didn't have a Bluebird logo
[33:00] SPEAKER: before that, it was the little, it was a word mark.
[33:03] SPEAKER: And Twitterific was the first one that used tweet, I think.
[33:07] SPEAKER: I'm not sure, I'm not 100% on that, that is--
[33:09] SPEAKER: - As a verb?
[33:10] SPEAKER: As an action? - That's a verb, to tweet.
[33:11] SPEAKER: The button said tweet on Twitterific.
[33:14] SPEAKER: - And as Twitterific, well, not anymore,
[33:16] SPEAKER: but up until like three days ago,
[33:18] SPEAKER: was Twitterific still going strong?
[33:19] SPEAKER: - 16 years, until earlier this week.
[33:22] SPEAKER: So last week, several of the third-party clients
[33:28] SPEAKER: stopped working, most of the developers posted a tweet
[33:31] SPEAKER: saying that they had API.
[33:33] SPEAKER: So, back story, the third-party clients
[33:37] SPEAKER: don't scrape Twitter, you don't log into a webpage
[33:39] SPEAKER: or something like that, and it scrapes the information off.
[33:41] SPEAKER: They have a third-party API, originally it was just
[33:43] SPEAKER: the main Twitter API that you could connect to
[33:45] SPEAKER: with limited stuff, and then they eventually spun it out
[33:48] SPEAKER: into a third-party API so that it could handle
[33:50] SPEAKER: different levels of traffic.
[33:53] SPEAKER: And API is an application programming interface,
[33:55] SPEAKER: it's basically a software interface for software
[33:57] SPEAKER: that can get machine-readable data into and out of your app.
[34:00] SPEAKER: - Yeah, it lets you query them for specific data
[34:02] SPEAKER: instead of all the data.
[34:03] SPEAKER: - Yeah.
[34:05] SPEAKER: So, they cut off the, Twitter cut off the API access
[34:10] SPEAKER: for developers who were breaking, without saying anything,
[34:13] SPEAKER: for several days, like just Tweetbot, Twitterific,
[34:17] SPEAKER: Phoenix for Android, and a couple of other Twitter clients
[34:21] SPEAKER: just stopped working without any warning whatsoever.
[34:25] SPEAKER: And this was characterized by a bunch of people
[34:28] SPEAKER: on like a Friday night at eight o'clock saying,
[34:30] SPEAKER: "Hey, is Tweetbot broken?"
[34:32] SPEAKER: - That's, so that was kind of where I left off
[34:34] SPEAKER: with this topic, I hadn't caught up to the fact
[34:35] SPEAKER: that they had put out a statement and everything,
[34:37] SPEAKER: because that's, the reason I bring that up
[34:40] SPEAKER: is that this is very indicative of just where Twitter
[34:42] SPEAKER: is at these days, that things break and you don't know why.
[34:45] SPEAKER: And it's like, is this due to lack of engineering resources
[34:48] SPEAKER: now, self-inflicted, or have they made a policy change
[34:50] SPEAKER: and not bothered to tell anybody?
[34:51] SPEAKER: It's like, the way the whole, the thing is run
[34:54] SPEAKER: is so ramshackle and unpredictable now
[34:56] SPEAKER: that you just kind of throw up your hands
[34:58] SPEAKER: at things like this and go, "Well, who knows?"
[35:00] SPEAKER: - Yeah, well, and as we'll see by how it actually,
[35:04] SPEAKER: how they did eventually, several days later,
[35:06] SPEAKER: decide to message it, it's kind of chicken shit.
[35:10] SPEAKER: So it's another point of note, third-party clients,
[35:15] SPEAKER: because they use an external API,
[35:16] SPEAKER: traditionally don't get ads delivered.
[35:19] SPEAKER: So if you use, if you pay five bucks a year for Tweetbot,
[35:22] SPEAKER: you don't ever see an ad on Twitter,
[35:23] SPEAKER: which is a real, I mean, like,
[35:25] SPEAKER: that's worth five bucks a year to me.
[35:26] SPEAKER: - Sure.
[35:29] SPEAKER: - So first, a few days later, after this API turn-off,
[35:34] SPEAKER: they posted it, oh, it's also worth mentioning,
[35:36] SPEAKER: several other third-party clients,
[35:39] SPEAKER: like Hootsuite, for example, and TweetDeck,
[35:42] SPEAKER: which is a Twitter-owned third-party client
[35:45] SPEAKER: that they brought in as a professional-level tool.
[35:47] SPEAKER: Hootsuite is, I mean, there's a consumer-level version
[35:50] SPEAKER: of Hootsuite, but it's mainly something that people pay,
[35:53] SPEAKER: like if you do corporate communications,
[35:54] SPEAKER: if you do customer support through Twitter,
[35:57] SPEAKER: if you're like Comcast or somebody like that
[36:00] SPEAKER: that has a large Twitter support presence,
[36:02] SPEAKER: you probably use something that's similar to Hootsuite,
[36:03] SPEAKER: and presumably they're using a paid API key
[36:06] SPEAKER: rather than a free API key like Tweetbot
[36:08] SPEAKER: and this kind of smaller indie third-party clients.
[36:10] SPEAKER: Anyway, a few days after this, they said,
[36:15] SPEAKER: Twitter just posted a tweet that said,
[36:17] SPEAKER: hey, we're killing, we're enforcing rules
[36:22] SPEAKER: that have been long, we're enforcing longstanding rules
[36:24] SPEAKER: and cutting off AP access for software
[36:26] SPEAKER: that breaks those rules.
[36:28] SPEAKER: And everybody looks at the developer third-party rules,
[36:30] SPEAKER: like, what the fuck rules is Tweetbot
[36:32] SPEAKER: or Twitter horrific or Tweety breaking?
[36:35] SPEAKER: Nobody knows, right?
[36:36] SPEAKER: There's no, like, they were traditionally very careful
[36:38] SPEAKER: to stay within the rules, 'cause, you know,
[36:40] SPEAKER: your entire business depends on this.
[36:42] SPEAKER: A few days even after that, they update
[36:46] SPEAKER: the developer guidelines, the developer rules,
[36:51] SPEAKER: to say, use or access the licensed materials
[36:54] SPEAKER: to create or attempt to create a substitute
[36:56] SPEAKER: or similar service or product
[36:57] SPEAKER: to the Twitter applications is forbidden.
[37:00] SPEAKER: Weird, what a weird coincidence.
[37:01] SPEAKER: So-
[37:02] SPEAKER: - Okay, so they were retroactively slapped
[37:05] SPEAKER: with a rule that didn't exist?
[37:07] SPEAKER: - It's a Kafka-esque situation for developers
[37:12] SPEAKER: of third-party apps, yeah.
[37:15] SPEAKER: Basically what they're saying is, hey,
[37:17] SPEAKER: the business that you've spent 15 or 16 years
[37:20] SPEAKER: in Twitterific's case, or a little bit less
[37:22] SPEAKER: in Tweetbot's case and Phoenix's case,
[37:24] SPEAKER: building on our platform in good faith
[37:27] SPEAKER: with full knowledge and in full display
[37:30] SPEAKER: and with a fully authorized API key
[37:34] SPEAKER: for, you know, the last decade plus,
[37:38] SPEAKER: is suddenly inconvenient to our business,
[37:40] SPEAKER: even though, like, third-party clients in these days
[37:43] SPEAKER: are used by a tiny, tiny, tiny fraction of users, right?
[37:48] SPEAKER: But probably that mostly the legacy blue checks
[37:51] SPEAKER: that Musk doesn't like.
[37:53] SPEAKER: - Sure, but probably more than enough to,
[37:56] SPEAKER: I mean, clearly more than enough
[37:57] SPEAKER: to sustain development of these apps
[37:58] SPEAKER: and provide a living to the developers, presumably.
[38:02] SPEAKER: - Good businesses for these small teams, yeah.
[38:05] SPEAKER: And most of these teams are pretty,
[38:06] SPEAKER: like, I think Tweetbot is two or three people.
[38:08] SPEAKER: It's a small company.
[38:12] SPEAKER: Anyway, that's it, that's the whole story.
[38:15] SPEAKER: At this point, I think it's pretty safe to say
[38:17] SPEAKER: Dan Gilmore said something along these lines,
[38:19] SPEAKER: and I tend to agree with him.
[38:20] SPEAKER: I was thinking it beforehand,
[38:22] SPEAKER: but you'd have to be really stupid
[38:27] SPEAKER: to build any kind of business on top of Twitter
[38:30] SPEAKER: in an era when they're unpredictable and capricious.
[38:34] SPEAKER: I mean, maybe, like, actively malicious
[38:37] SPEAKER: to people who are building stuff
[38:39] SPEAKER: that makes money on their platform.
[38:41] SPEAKER: - I don't think there's any maybe
[38:42] SPEAKER: about their demonstrated malice, but anyway.
[38:46] SPEAKER: I mean, this has always been the danger
[38:48] SPEAKER: of this kind of thing.
[38:49] SPEAKER: This is just an extremely egregious example
[38:51] SPEAKER: of people building a livelihood
[38:54] SPEAKER: on top of a massive corporate platform
[38:56] SPEAKER: and then subjecting themselves to the whims
[38:58] SPEAKER: and edicts of that platform.
[39:01] SPEAKER: Like, you know, it's the same thing with YouTube
[39:03] SPEAKER: and Twitch and Patreon and you name it.
[39:06] SPEAKER: Like, it's great right up until it isn't.
[39:10] SPEAKER: - But you can typically expect large corporations
[39:14] SPEAKER: to behave in a predictable way if it makes them money, right?
[39:17] SPEAKER: - That's what makes this egregious,
[39:18] SPEAKER: is nobody expected this globe-spanning social media platform
[39:22] SPEAKER: to go private and suddenly be unilaterally controlled
[39:26] SPEAKER: by someone who seems a little unhinged.
[39:28] SPEAKER: - Yeah, I think that's a little bit unhinged
[39:33] SPEAKER: is a good way to describe it, yeah.
[39:34] SPEAKER: So anyway, that's that.
[39:38] SPEAKER: - Huh, that's, man, that sucks.
[39:39] SPEAKER: I have, I just have submitted
[39:41] SPEAKER: to using the official stuff years ago,
[39:43] SPEAKER: so I have not really been aware
[39:45] SPEAKER: of the state of third-party clients at this point.
[39:47] SPEAKER: - Well, so third-party clients,
[39:48] SPEAKER: once you reached a certain account volume,
[39:52] SPEAKER: the third-party clients kind of broke down
[39:54] SPEAKER: because they didn't have access to full API.
[39:58] SPEAKER: So like, the server-side mute lists
[40:00] SPEAKER: and stuff like that stopped working.
[40:01] SPEAKER: - Oh, you mean in terms of the types of data you could get?
[40:04] SPEAKER: - Yeah, so like, I couldn't, on the official clients,
[40:07] SPEAKER: I could filter my replies to only show people who follow me.
[40:12] SPEAKER: - Okay. - That stuff like that
[40:13] SPEAKER: didn't work on the third-party API, so.
[40:17] SPEAKER: - Interesting, I assumed that there would be a problem
[40:19] SPEAKER: with one of these apps potentially being rate-limited
[40:22] SPEAKER: in terms of the number of requests
[40:23] SPEAKER: it can make per second, per minute.
[40:25] SPEAKER: - So there is that, there's also a limit
[40:28] SPEAKER: to the total number of keys that they would issue,
[40:30] SPEAKER: and then you'd have to get an extension
[40:31] SPEAKER: when you sold more copies than that,
[40:33] SPEAKER: or if you sold more copies than that.
[40:34] SPEAKER: The unfortunate thing is,
[40:39] SPEAKER: like, it's not like they're not gonna maintain these APIs,
[40:43] SPEAKER: like, look, if they had come out and said,
[40:45] SPEAKER: "Hey, we're gonna move the engineers
[40:46] SPEAKER: "that maintain these third-party APIs onto other things
[40:49] SPEAKER: "because it's time-consuming and expensive
[40:51] SPEAKER: "to maintain these," like, that is a valid,
[40:53] SPEAKER: like, I could believe that.
[40:55] SPEAKER: So, you know, we're gonna turn this off in six months,
[40:58] SPEAKER: we're gonna turn this off in three months,
[41:00] SPEAKER: migrate your customers off,
[41:01] SPEAKER: give them a chance to transition off of this thing
[41:05] SPEAKER: that they've been using for a long time.
[41:07] SPEAKER: Like, that's actually okay with me.
[41:10] SPEAKER: I mean, it's not great, but I understand that,
[41:13] SPEAKER: and, like, maintaining a third-party API
[41:14] SPEAKER: in addition to the main API that they use internally
[41:17] SPEAKER: is undoubtedly expensive.
[41:19] SPEAKER: However, they have paying customers that pay for API access,
[41:22] SPEAKER: so they're gonna continue maintaining these third-party APIs.
[41:25] SPEAKER: All they're saying is, "Yo, you're not,"
[41:27] SPEAKER: and the best part about this is they didn't even say,
[41:29] SPEAKER: "Hey, if you wanna pay for API access, you can keep going,"
[41:32] SPEAKER: right, they just turned it off
[41:34] SPEAKER: and didn't say shit to these people for two weeks.
[41:36] SPEAKER: - I feel like that is indicative of the level
[41:39] SPEAKER: of kind of reality distortion going on
[41:41] SPEAKER: around the behavior of Twitter these days,
[41:43] SPEAKER: that when you point out like,
[41:45] SPEAKER: "Oh, they could have given a three-month notice
[41:47] SPEAKER: that, hey, this is a policy change we are making,
[41:49] SPEAKER: here is your window to make your own changes,
[41:51] SPEAKER: to accommodate it,"
[41:52] SPEAKER: that's how any one of these large tech companies
[41:55] SPEAKER: would have handled this, right?
[41:56] SPEAKER: Like, it took you spelling that example out.
[41:59] SPEAKER: - Yeah, even Google, who loves killing stuff,
[42:02] SPEAKER: doesn't just fucking turn off.
[42:05] SPEAKER: They don't say, "Hey, we're gonna shut this down tonight."
[42:07] SPEAKER: - And again, not just shut it down,
[42:09] SPEAKER: but the Orwellian step of retroactively trying to justify it
[42:13] SPEAKER: with a rule that didn't exist.
[42:15] SPEAKER: - So anyway, Hootsuite still works.
[42:17] SPEAKER: - Man, the musk of this episode
[42:19] SPEAKER: is getting a little too strong.
[42:20] SPEAKER: I can't, I'm having a hard time breathing.
[42:22] SPEAKER: Why don't we move on?
[42:23] SPEAKER: (upbeat music)
[42:30] SPEAKER: - I think I'm going to be very happy
[42:31] SPEAKER: with this new machine I bought, Brad.
[42:33] SPEAKER: - Yeah?
[42:34] SPEAKER: - Are you going to be, or are?
[42:35] SPEAKER: - I am, like, it's been fun.
[42:37] SPEAKER: It's been a fun, so I replaced my big, heavy,
[42:40] SPEAKER: expensive-to-run desktop Haswell-E,
[42:45] SPEAKER: FreeBSD 100% power consumption all the time server.
[42:49] SPEAKER: - Oh, well, I wouldn't say that.
[42:50] SPEAKER: The FreeBSD's power management is pretty good these days.
[42:53] SPEAKER: It's not quite Linux, but I ran a PowerD-V fairly often,
[42:59] SPEAKER: and it does clock down like you would expect.
[43:02] SPEAKER: It supports most of the Intel C-States.
[43:04] SPEAKER: - I put the monitor on it and was like,
[43:07] SPEAKER: this is costing me, yeah, so it was bumping me up
[43:11] SPEAKER: into a higher tier of electrical usage,
[43:13] SPEAKER: which was costing me probably 30 bucks a month.
[43:15] SPEAKER: - Oh, my God.
[43:16] SPEAKER: - Like, not all the time, but sometimes.
[43:18] SPEAKER: - Man, as somebody who rebuilt their equivalent
[43:23] SPEAKER: heavy NAS server machine into another heavy NAS
[43:27] SPEAKER: when the first one died a few months ago,
[43:28] SPEAKER: you're really making me question my life choices right now.
[43:31] SPEAKER: - $30?
[43:32] SPEAKER: - Well, but you also, well, okay, A,
[43:34] SPEAKER: I have more people using stuff in my house.
[43:37] SPEAKER: I'm in a neighborhood where there are fewer people.
[43:39] SPEAKER: I also changed rate plans since that time,
[43:42] SPEAKER: so I'm on a time-of-use plan now,
[43:44] SPEAKER: which means I get better rates, and I'm not.
[43:48] SPEAKER: PG&E does this thing that I think is kind of bullshit
[43:49] SPEAKER: where they compare your usage to your neighbor's usage,
[43:51] SPEAKER: and if you're higher usage to them,
[43:53] SPEAKER: then you get charged more
[43:55] SPEAKER: once you get into the higher tiers.
[43:56] SPEAKER: - What?
[43:57] SPEAKER: - Yeah, it seems like it should be illegal,
[43:59] SPEAKER: because, like, how is location relevant there?
[44:03] SPEAKER: - You know, that is, well, presumably,
[44:05] SPEAKER: the houses are the same era in construction,
[44:07] SPEAKER: so they're, like, the same level of inefficiency
[44:09] SPEAKER: and same number of rooms and stuff like that.
[44:10] SPEAKER: - Right, but I mean, your draw from the grid
[44:12] SPEAKER: is the same no matter where you are, right?
[44:16] SPEAKER: - Look, man, I'm not an expert.
[44:17] SPEAKER: The point is, when I got the electric car,
[44:21] SPEAKER: then we switched to time-of-use,
[44:23] SPEAKER: which means we pay a different rate
[44:24] SPEAKER: from, like, midnight to 3 p.m.
[44:26] SPEAKER: than we do from 3 p.m. to midnight, basically.
[44:30] SPEAKER: And the 3 p.m. to midnight is more expensive,
[44:32] SPEAKER: 'cause that's a higher consumption time
[44:33] SPEAKER: for the overall generation and transmission of the grid.
[44:37] SPEAKER: Anyway, the upshot is I wanted to build a server,
[44:40] SPEAKER: I wanted to replace that big, heavy server
[44:42] SPEAKER: with two machines that were both combined,
[44:46] SPEAKER: theoretically, be less power consumptive
[44:48] SPEAKER: than the big machine.
[44:49] SPEAKER: Now, I realize as we're talking about this
[44:51] SPEAKER: that I haven't actually plugged in the monitor yet,
[44:54] SPEAKER: so I may have played myself,
[44:56] SPEAKER: but we'll see.
[44:58] SPEAKER: - Well, you know, Synology and that little...
[45:00] SPEAKER: It's a B-Link, we should say.
[45:02] SPEAKER: - Yeah, it's a B-Link.
[45:05] SPEAKER: I got the 11th Gen N5105, 16 gig, 500 gig SSD,
[45:10] SPEAKER: 16 gig RAM, 500 gig SSD version.
[45:12] SPEAKER: - Actually, you know what?
[45:14] SPEAKER: Let me know when you do monitor that stuff.
[45:16] SPEAKER: I wonder.
[45:17] SPEAKER: I bet I could see those things collectively amounting
[45:20] SPEAKER: to anywhere from 60 to 90 watts, maybe.
[45:25] SPEAKER: - Well, so the CPU on both of them,
[45:26] SPEAKER: there's three hard drives in the NAS.
[45:29] SPEAKER: The CPU is typically around 5% on both machines.
[45:34] SPEAKER: It spikes up a little bit
[45:35] SPEAKER: when I'm doing a Plex transcode to 20,
[45:38] SPEAKER: or when somebody's on the Minecraft server.
[45:40] SPEAKER: Anyway, so the upshot is I put Ubuntu Server on this thing,
[45:44] SPEAKER: and I spent five days trying to get
[45:47] SPEAKER: the hardware-accelerated transcode working for Plex.
[45:49] SPEAKER: - I enjoyed witnessing your rare appearance
[45:52] SPEAKER: in the Linux channel and the Discord,
[45:54] SPEAKER: where I spend a lot of my time.
[45:55] SPEAKER: It was fun to see you becoming acquainted with systemd
[45:59] SPEAKER: and got weird Docker networking idiosyncrasies
[46:03] SPEAKER: and passing a render device through to your Plex container.
[46:08] SPEAKER: - Well, it's funny as somebody who's dipped in and out
[46:10] SPEAKER: of Linux stuff over the last decade or two at this point.
[46:16] SPEAKER: It's funny what stuff comes back immediately,
[46:18] SPEAKER: like my fstab, no problems.
[46:20] SPEAKER: I got those mounts down.
[46:21] SPEAKER: I can mount stuff left and right like crazy.
[46:23] SPEAKER: It's no issue.
[46:25] SPEAKER: I'd never had to pass through.
[46:26] SPEAKER: I'd never had to do hardware-accelerated drivers
[46:28] SPEAKER: for anything before, right?
[46:29] SPEAKER: I'd never had to deal with that.
[46:31] SPEAKER: And it took a long time to get that stuff working,
[46:34] SPEAKER: mainly because, let's see, I think this is a Jasper Lake.
[46:38] SPEAKER: Our friends who work at Intel and are listening to this
[46:40] SPEAKER: are probably yelling at their computers right now.
[46:43] SPEAKER: It's a little Celeron,
[46:45] SPEAKER: but it does have good hardware-accelerated
[46:47] SPEAKER: encode and decode of video.
[46:49] SPEAKER: So that specifically Plex can do tone mapping
[46:53] SPEAKER: on 4K HDR Blu-ray rips to make them work on 1080p TVs
[47:00] SPEAKER: so that I don't have to think about that shit
[47:02] SPEAKER: on the clients when I want to watch something
[47:04] SPEAKER: on the TV in the bedroom or whatever.
[47:08] SPEAKER: And it'll do that for multiple streams at a time.
[47:11] SPEAKER: So in order for this, versus on the big PC,
[47:15] SPEAKER: it would spike the CPUs to do that same thing.
[47:18] SPEAKER: - Oh, 'cause that Haswell did not have,
[47:20] SPEAKER: did it have any form of Quick Sync at all?
[47:22] SPEAKER: - No, Haswell does not have Quick Sync
[47:24] SPEAKER: 'cause there's no GPU on those.
[47:25] SPEAKER: - That's a server chip, right?
[47:26] SPEAKER: - Server chip, yeah.
[47:29] SPEAKER: So I put in a GPU and was doing it on an Nvidia card,
[47:32] SPEAKER: which is not, obviously-
[47:34] SPEAKER: - That's a lot of power for a machine
[47:35] SPEAKER: that doesn't even have a monitor.
[47:37] SPEAKER: - Beefy, yeah, beefy.
[47:39] SPEAKER: So this 5105, it's like 2.4 gigahertz,
[47:43] SPEAKER: 2.9 gigahertz processor up to,
[47:45] SPEAKER: on the boost clocks and all that.
[47:46] SPEAKER: But mostly it just runs, it ticks along at a real low speed
[47:49] SPEAKER: and just is serving files, it's not even serving files,
[47:53] SPEAKER: it's just streaming stuff on Plex.
[47:55] SPEAKER: - We have two things about your Plex.
[47:56] SPEAKER: So someone who uses your Plex on a somewhat regular basis.
[48:00] SPEAKER: Number one, I am a conscientious Plex user
[48:02] SPEAKER: and I'm quite sure that I'm only using it in the hours
[48:04] SPEAKER: that your time of use rate is lowest.
[48:09] SPEAKER: I tend to only be on there late on a Saturday night
[48:11] SPEAKER: or something.
[48:12] SPEAKER: - Yeah.
[48:14] SPEAKER: - But the other thing, oh, the other thing
[48:17] SPEAKER: is in the last week or so.
[48:19] SPEAKER: - It's gotten good, right?
[48:20] SPEAKER: - The speed of the buffering is like,
[48:23] SPEAKER: there's no comparison at all.
[48:24] SPEAKER: Like there barely is any buffering.
[48:26] SPEAKER: Like it would buffer like a, and I'm not even,
[48:29] SPEAKER: I think I set my options on your Plex
[48:31] SPEAKER: to play original files 'cause we're eight miles
[48:34] SPEAKER: or whatever apart and we both have gigabit upstream.
[48:37] SPEAKER: - Yeah.
[48:37] SPEAKER: - It's like, why not just play the full file
[48:39] SPEAKER: and not make you transcode or whatever?
[48:41] SPEAKER: But I guess sometimes maybe it does transcode anyway.
[48:42] SPEAKER: So if you have to, like a lot of things
[48:45] SPEAKER: trigger transcodes that you might not expect.
[48:46] SPEAKER: Like if you have subtitles on a client
[48:49] SPEAKER: that doesn't support soft subtitles and stuff like that.
[48:51] SPEAKER: - Yeah, so anyway, on the previous setup,
[48:54] SPEAKER: buffering was like five plus seconds just to play something.
[48:58] SPEAKER: And it's like almost instantaneous now.
[49:00] SPEAKER: It's a very big change.
[49:01] SPEAKER: - Yeah, well, and you can skip forward and back
[49:03] SPEAKER: and stuff like that while you're playing without,
[49:05] SPEAKER: like if you miss something, you've rewind a little bit
[49:07] SPEAKER: and then jack up the whole playback.
[49:08] SPEAKER: - Yeah.
[49:11] SPEAKER: - It's funny, my daughter has habitually turned on subtitles
[49:14] SPEAKER: since she started reading
[49:16] SPEAKER: 'cause she likes to read the subtitles.
[49:18] SPEAKER: It's like fun practice.
[49:20] SPEAKER: And as a result, Plex has become a little less popular
[49:24] SPEAKER: in the house because I didn't have subtitles on
[49:26] SPEAKER: over the last few months since we switched to NAS
[49:29] SPEAKER: instead of the big machine.
[49:31] SPEAKER: Anyway, the upshot is I learned how to use Docker this week.
[49:38] SPEAKER: I learned that in order to get hardware accelerated
[49:41] SPEAKER: Plex transcode on the 5105,
[49:43] SPEAKER: I had to be running a newer kernel
[49:45] SPEAKER: than shipped by default with Ubuntu 2210.
[49:51] SPEAKER: - Yes, it seems like a lot of your issues did arise
[49:54] SPEAKER: from just having a pretty new CPU
[49:56] SPEAKER: and not having good driver support.
[49:59] SPEAKER: - It's an 11th gen, it's not that new.
[50:01] SPEAKER: - Well.
[50:02] SPEAKER: - It's newish, it's the Diet Coke of new.
[50:05] SPEAKER: - Like as someone who keeps quite an eye
[50:06] SPEAKER: on kernel development these days,
[50:08] SPEAKER: I'm gonna say that support for new hardware is,
[50:14] SPEAKER: I'll say this, it's a hell of a lot faster
[50:15] SPEAKER: than FreeBSD, it's not Windows.
[50:17] SPEAKER: - Yeah, fair.
[50:18] SPEAKER: - In terms of support coming on for online for new hardware,
[50:22] SPEAKER: Linux does lag still these days a bit.
[50:24] SPEAKER: - So anyway, I spent a week installing on the metal,
[50:27] SPEAKER: learning how to use Docker,
[50:29] SPEAKER: still not getting Docker to work,
[50:31] SPEAKER: trying a bazillion driver changes and software config files
[50:34] SPEAKER: and trying a million things
[50:36] SPEAKER: and sending a bunch of stuff to text files
[50:38] SPEAKER: and piping things all over the place.
[50:40] SPEAKER: - I love type.
[50:41] SPEAKER: - I mean, okay, it is nice to get just like,
[50:44] SPEAKER: when you have your NAS mounted
[50:45] SPEAKER: and I wanna read something on my desktop
[50:47] SPEAKER: and not having to read in the shell
[50:48] SPEAKER: and I just pipe it to a text file in a folder
[50:50] SPEAKER: that I can access from my Windows machine
[50:52] SPEAKER: and just open it up in Notepad Plus
[50:53] SPEAKER: and watch the text come in, it's pretty cool.
[50:56] SPEAKER: But the TLDR is, once I updated the kernel,
[51:00] SPEAKER: everything worked.
[51:01] SPEAKER: So probably like if I'd run instead of the LTS version
[51:05] SPEAKER: of Ubuntu, which is 22,
[51:07] SPEAKER: I started doing 204- - 2204 is LTS.
[51:11] SPEAKER: - Didn't do what I needed.
[51:12] SPEAKER: If I had run the 23, the testing version
[51:17] SPEAKER: of the next release instead of the stable version
[51:19] SPEAKER: of the last release, I probably would have been fine.
[51:22] SPEAKER: But upgrading the kernel fixed the problem
[51:24] SPEAKER: and now I have hardware accelerated Plex
[51:26] SPEAKER: and tone mapping and the whole thing,
[51:28] SPEAKER: which feels pretty good.
[51:32] SPEAKER: - Yeah, it was fun watching you play through
[51:34] SPEAKER: or play out some of that stuff.
[51:36] SPEAKER: I've done, I also run Plex in container,
[51:38] SPEAKER: different kind of container, but it was a good object lesson
[51:44] SPEAKER: in the everything is a file philosophy of Unix and Linux.
[51:48] SPEAKER: - Yeah.
[51:49] SPEAKER: - Because that render device, the quick sync,
[51:51] SPEAKER: the video encode engine on that CPU,
[51:54] SPEAKER: just like every other piece of hardware in your machine
[51:56] SPEAKER: just shows up as a file in /dev.
[51:59] SPEAKER: And so like passing that through to a container
[52:02] SPEAKER: often is just a process of mounting that file
[52:06] SPEAKER: in the container or depending on how you're doing privileges
[52:09] SPEAKER: and stuff, in my case, like creating a user
[52:12] SPEAKER: in that container and giving it group read access,
[52:15] SPEAKER: read write access to that, you know what I mean?
[52:17] SPEAKER: Like it's so interesting coming from the Windows world
[52:20] SPEAKER: of like device manager and installing drivers
[52:22] SPEAKER: from websites and stuff like that.
[52:24] SPEAKER: Just the every piece of hardware is a file thing
[52:28] SPEAKER: is such a different paradigm and it's kind of awesome
[52:30] SPEAKER: when, you know, again, you can map concepts
[52:33] SPEAKER: you already know to that, you know, like I said,
[52:35] SPEAKER: you can just assign group ownership to users
[52:37] SPEAKER: and now they can access that device,
[52:39] SPEAKER: but you can even do things like you can cat from that device
[52:42] SPEAKER: to a file and get a raw image jump of whatever is in
[52:45] SPEAKER: the frame buffer or whatever.
[52:46] SPEAKER: I might be kind of messing up the details a little bit there,
[52:48] SPEAKER: but it's like, you know, all these little utilities
[52:51] SPEAKER: that you know how to use work on these hardware devices,
[52:53] SPEAKER: just like they would a text file.
[52:54] SPEAKER: It's kind of awesome.
[52:55] SPEAKER: - Well, so part of the challenge I had was that
[52:57] SPEAKER: that dev slash DRI, which is the driver for the Intel GPU
[53:01] SPEAKER: was showing up when I had the wrong kernel installed,
[53:05] SPEAKER: but that kernel didn't know how to talk to,
[53:07] SPEAKER: 'cause the drivers are essentially like the interface
[53:10] SPEAKER: for the drivers and the hardware is embedded in the kernel.
[53:14] SPEAKER: I wasn't able to use the quick sync stuff
[53:16] SPEAKER: 'cause the kernel didn't know what to do with it.
[53:17] SPEAKER: So it was just ignoring that part of the chip.
[53:20] SPEAKER: Anyway, that part doesn't matter.
[53:21] SPEAKER: The nice thing is after I got this going,
[53:23] SPEAKER: I was able to set up a Docker, a Minecraft server in Docker
[53:26] SPEAKER: for a Java Minecraft instance,
[53:28] SPEAKER: like really super fast, no problem.
[53:32] SPEAKER: And then I did the thing that we talked about
[53:34] SPEAKER: in the cold open with the FFmpeg.
[53:36] SPEAKER: I think that's running in a systemd script
[53:37] SPEAKER: on the metal right now, not in a Docker container,
[53:40] SPEAKER: but I'll move it over at some point.
[53:41] SPEAKER: And Docker is neat compared to BSD jails,
[53:46] SPEAKER: but I miss the ability to just say,
[53:48] SPEAKER: hey, each of these gets its own IP address
[53:50] SPEAKER: and shows up on its own machine
[53:51] SPEAKER: and not have to deal with a bunch of port forwarding
[53:53] SPEAKER: and the Docker infrastructure.
[53:55] SPEAKER: - Yeah, I think there are ways to do that
[53:57] SPEAKER: with Docker containers, but how--
[53:59] SPEAKER: - You have to have the Mac VLANs and a bunch of nonsense.
[54:01] SPEAKER: And it seemed like a lot of trouble.
[54:05] SPEAKER: I also have been documenting everything I've done on this
[54:08] SPEAKER: in a note, in notes so that when I have to recreate it
[54:11] SPEAKER: at some point in the future,
[54:11] SPEAKER: I'll be able to do that, which is nice.
[54:14] SPEAKER: - See, I did not do that.
[54:15] SPEAKER: And when I, so I moved this NAS to straight Linux,
[54:18] SPEAKER: no web UI, no, you know, application layer
[54:22] SPEAKER: or handholding in late August, beginning of September.
[54:26] SPEAKER: - Yeah, just in that time of life.
[54:29] SPEAKER: - I made it maybe three months, two and a half months
[54:32] SPEAKER: before I hosed the system badly enough
[54:34] SPEAKER: that I couldn't figure out how to recover it
[54:35] SPEAKER: and just wipe and reinstall.
[54:38] SPEAKER: - Oh no.
[54:39] SPEAKER: - I F'd up, it's a long story.
[54:42] SPEAKER: I messed up the bootloader.
[54:44] SPEAKER: Something bad happened to the grub partition
[54:46] SPEAKER: and I couldn't figure out how to rebuild it properly.
[54:48] SPEAKER: So I just said, it'd be easier to wipe this.
[54:50] SPEAKER: Anyway, point is--
[54:52] SPEAKER: - Declaring Linux bankruptcy is what I used to call that.
[54:54] SPEAKER: - Yes, having not documented any,
[54:56] SPEAKER: all of the things I had done to that machine,
[54:58] SPEAKER: it was like a slow month long process
[55:00] SPEAKER: of like every couple of days, remembering like,
[55:02] SPEAKER: oh, I forgot to go set that other thing up.
[55:04] SPEAKER: Like, oh, I need to go set the ZFS arc size again.
[55:07] SPEAKER: I forgot to do that, you know what I mean?
[55:08] SPEAKER: It's probably the note taking is good.
[55:11] SPEAKER: - The note taking, I mean, it was nice
[55:13] SPEAKER: 'cause it meant that I could find,
[55:14] SPEAKER: like when I accidentally closed the window in Firefox
[55:16] SPEAKER: and I closed 35 tabs
[55:17] SPEAKER: that had all the different how-tos I was using,
[55:19] SPEAKER: it was nice 'cause the one that was the good one
[55:21] SPEAKER: was still in the notes and I could just click on it
[55:23] SPEAKER: and go back to where I left off.
[55:27] SPEAKER: The next thing I think is to set up a Linux GSM instance
[55:31] SPEAKER: in a Docker container on that
[55:33] SPEAKER: so I can set up some quake servers and stuff like that.
[55:35] SPEAKER: - I am running Linux GSM as we speak
[55:38] SPEAKER: to run a Valheim server for some friends.
[55:41] SPEAKER: It's nice, it's a little clunky in some ways,
[55:43] SPEAKER: but I think it's probably still better
[55:45] SPEAKER: than doing it all yourself.
[55:47] SPEAKER: - So the experiment here was that I was unsure
[55:51] SPEAKER: if the little, 'cause my NAS has a small Celeron in it too.
[55:55] SPEAKER: It may even be the same processor.
[55:56] SPEAKER: The difference is that the NAS,
[55:58] SPEAKER: because it's Synology's Linux,
[56:00] SPEAKER: I can't do stuff like update kernel and things like that.
[56:02] SPEAKER: And they're usually pretty good about that,
[56:04] SPEAKER: but also I'm fine having this stuff
[56:07] SPEAKER: running on a separate machine.
[56:08] SPEAKER: It turns out with NFS and all that, it was pretty easy.
[56:11] SPEAKER: - That's the beauty of the flat Linux install,
[56:13] SPEAKER: not the appliance type true NAS or whatever sort of thing,
[56:17] SPEAKER: is you can just do whatever you want.
[56:19] SPEAKER: - Yeah, there's a certain freedom there.
[56:21] SPEAKER: I think my next thing is gonna be looking
[56:23] SPEAKER: at the Linux containers that are more like,
[56:25] SPEAKER: you had told me about a couple of them yesterday.
[56:27] SPEAKER: - Yeah, that's what I do.
[56:28] SPEAKER: That's also what the Debian project leader does.
[56:31] SPEAKER: It feels so vindicated.
[56:32] SPEAKER: I use LXC, or I think it's actually pronounced Lexi,
[56:36] SPEAKER: but who knows how to pronounce anything in Linux,
[56:39] SPEAKER: which is, the distinction is that Docker
[56:41] SPEAKER: is application level containers.
[56:42] SPEAKER: All that's in that container is the application
[56:44] SPEAKER: and its dependencies.
[56:45] SPEAKER: There's nothing else in there.
[56:46] SPEAKER: And LXC is more like FreeBSD jails, where it's a full system.
[56:50] SPEAKER: It's a whole ass Linux in each container.
[56:52] SPEAKER: - So that means I can have a different kernel running on?
[56:55] SPEAKER: - No, no, no, just like application containers,
[56:58] SPEAKER: it does run on the same.
[57:00] SPEAKER: - Okay.
[57:00] SPEAKER: - Yeah, you'd need a VM to do that sort of thing.
[57:03] SPEAKER: - But like they each have a file system
[57:04] SPEAKER: that I can then put something in the mount Fstab for?
[57:11] SPEAKER: - Yes, exactly.
[57:12] SPEAKER: It feels much more like a full Linux system.
[57:15] SPEAKER: I mean, there are some things that are proxied
[57:16] SPEAKER: from the host system, like proc and sys
[57:18] SPEAKER: and some of those kind of suitable systems
[57:21] SPEAKER: that refer to hardware are just passed through.
[57:23] SPEAKER: And so you do get some weird issues where,
[57:26] SPEAKER: like if you look at memory usage in the container,
[57:28] SPEAKER: you're only gonna see what it's using
[57:29] SPEAKER: and not what the whole system,
[57:30] SPEAKER: like it's aware of some things, not others.
[57:32] SPEAKER: But anyway, it is much more of a full Linux system.
[57:35] SPEAKER: And then part of the cool thing there is that,
[57:37] SPEAKER: like I'm running all of my main service containers
[57:40] SPEAKER: on Ubuntu 22.04, 'cause it's LTS.
[57:42] SPEAKER: And it's like, oh, this is good and sturdy.
[57:45] SPEAKER: I've got a, what I think of as kind of
[57:46] SPEAKER: a Swiss army knife container that's Arch.
[57:49] SPEAKER: And that, then I can just install
[57:51] SPEAKER: all the bleeding edge bullshit that Arch offers
[57:54] SPEAKER: in a sandbox and I can use it
[57:56] SPEAKER: and not worry about hosing the main system.
[57:58] SPEAKER: But I also ran into a situation where like,
[58:00] SPEAKER: I wanted to set up the unify controller,
[58:01] SPEAKER: which runs the, the Ubiquity access points.
[58:05] SPEAKER: For-
[58:06] SPEAKER: - There's a good doctor image for that, for what it's worth.
[58:08] SPEAKER: - Yeah, I know, I know, I know.
[58:10] SPEAKER: But for various reasons, their dependencies
[58:12] SPEAKER: are so out of date that I couldn't install those
[58:14] SPEAKER: on Ubuntu 22.04, but I was able to just go grab
[58:17] SPEAKER: an Ubuntu 20.04 image that did have the older dependencies
[58:20] SPEAKER: that needed and just spin that container up
[58:23] SPEAKER: on that Ubuntu instead.
[58:25] SPEAKER: So like, you got a lot of flexibility there.
[58:26] SPEAKER: Like, like I could try Fedora.
[58:28] SPEAKER: Like I would, I would like to,
[58:30] SPEAKER: I would like to get my head around the Red Hat tool chain
[58:32] SPEAKER: with DNF and Yum and like all their package management stuff.
[58:35] SPEAKER: And you can very easily just spin up a Fedora container
[58:38] SPEAKER: with this and jump in there and mess around with that stuff.
[58:40] SPEAKER: It's-
[58:41] SPEAKER: - That's cool.
[58:42] SPEAKER: - It's pretty neat.
[58:43] SPEAKER: - Pretty neat.
[58:44] SPEAKER: - Yeah, that's how I feel about the server.
[58:46] SPEAKER: - Yeah, I'm even doing stuff, sorry, I'll stop.
[58:48] SPEAKER: But I'm hosting, you know, all those,
[58:51] SPEAKER: all those containers live on ZFS and so I'm using,
[58:53] SPEAKER: I made one Ubuntu container and installed like
[58:55] SPEAKER: all the common stuff I would want in it,
[58:57] SPEAKER: build dependencies and shell set up stuff and whatever.
[59:00] SPEAKER: And then I'm actually just using,
[59:01] SPEAKER: and that's on its own data set.
[59:02] SPEAKER: And I'm just using ZFS clones to clone that off,
[59:07] SPEAKER: serialize that as many times as I need more services.
[59:09] SPEAKER: And they use, they use zero extra space
[59:12] SPEAKER: until you change anything in there.
[59:14] SPEAKER: - Oh, that's awesome.
[59:14] SPEAKER: - So it's like, that's like a two gig container
[59:17] SPEAKER: or something at the base,
[59:18] SPEAKER: but new services use no space until you add
[59:21] SPEAKER: or change things in there.
[59:22] SPEAKER: It's kind of a nice efficient way to handle stuff.
[59:24] SPEAKER: - That's really cool.
[59:26] SPEAKER: The other thing of note is this Beelink thing
[59:28] SPEAKER: has two ethernet ports.
[59:30] SPEAKER: So if you're looking and thinking about
[59:31] SPEAKER: a lightweight PF sense router, it's 150.
[59:36] SPEAKER: You can get the 50, I think it's the 5005 version is,
[59:42] SPEAKER: is a, sorry, the 5095 version is a $150.
[59:50] SPEAKER: Like it, then they go seem to go on sale fairly often.
[59:53] SPEAKER: - Yeah, I bet that would make a pretty nice router
[59:55] SPEAKER: for PF sensor, open sensor, Bios, whatever you want to.
[59:59] SPEAKER: - Whatever your home rolled out.
[1:00:01] SPEAKER: I don't think I'm that crazy yet, but.
[1:00:02] SPEAKER: - Yeah.
[1:00:03] SPEAKER: - It's an option there, but yes.
[1:00:05] SPEAKER: Anyway, cool.
[1:00:06] SPEAKER: There's a little project update for you.
[1:00:08] SPEAKER: I'm sure we'll have more on the patron episode this month.
[1:00:10] SPEAKER: - Yeah, I'm, the next step for me on that is to,
[1:00:14] SPEAKER: is to move that FFmpeg thing into a,
[1:00:17] SPEAKER: something that doesn't involve me opening a terminal
[1:00:19] SPEAKER: and typing some stuff.
[1:00:20] SPEAKER: Oh, I also bought an SSH client for my iPad, Brad.
[1:00:24] SPEAKER: - Oh.
[1:00:25] SPEAKER: - I bought the fancy panic one.
[1:00:27] SPEAKER: - Oh, did they make one?
[1:00:28] SPEAKER: Oh yeah, I've seen that, right?
[1:00:29] SPEAKER: I bought, I bought Shelly a few years ago,
[1:00:31] SPEAKER: so I haven't gotten any others, but.
[1:00:34] SPEAKER: - It's, it is called Prompt, which is a good name
[1:00:39] SPEAKER: for a SSH client.
[1:00:40] SPEAKER: - Yes, I've seen that.
[1:00:41] SPEAKER: Their stuff looks so nice.
[1:00:42] SPEAKER: - It's very pretty.
[1:00:43] SPEAKER: I like panic a lot.
[1:00:45] SPEAKER: - Also, there's something cool about like SSHing
[1:00:47] SPEAKER: on your phone into your NAS and running HTOP
[1:00:50] SPEAKER: or something like that.
[1:00:51] SPEAKER: And just seeing this big, like seeing this big text mode,
[1:00:54] SPEAKER: like text user interface, colorful thing on your phone.
[1:00:59] SPEAKER: It's, it's like a weird retro futuristic thing.
[1:01:01] SPEAKER: - It makes me think about a future where our phones,
[1:01:07] SPEAKER: like, I mean, I know on Android,
[1:01:08] SPEAKER: you can access command line and stuff like that.
[1:01:09] SPEAKER: So it's a choice that I've made.
[1:01:11] SPEAKER: I realized that, but yeah, I wish that there was,
[1:01:14] SPEAKER: I wish that there was more command line stuff on the phone.
[1:01:16] SPEAKER: - Can you, can you, just on a stock,
[1:01:18] SPEAKER: not a rooted Android phone?
[1:01:19] SPEAKER: - You have to get a boot manager.
[1:01:21] SPEAKER: I don't know if it still can be used to be able to.
[1:01:23] SPEAKER: - Man, there have been numerous times
[1:01:26] SPEAKER: I wished you could get to a command line on an iPhone.
[1:01:28] SPEAKER: Anyway, we should wrap this up.
[1:01:29] SPEAKER: - I'm going to tell you, if you're, if you're,
[1:01:32] SPEAKER: if your partner and family are living in an iOS ecosystem,
[1:01:35] SPEAKER: you're trapped at this point.
[1:01:37] SPEAKER: - Yeah, no, it's like the watch is too good.
[1:01:39] SPEAKER: I'm, I'm here.
[1:01:40] SPEAKER: - Yeah. Yeah. Okay.
[1:01:41] SPEAKER: And on that note, this has been a real,
[1:01:45] SPEAKER: a real voyage of discovery.
[1:01:47] SPEAKER: - Yeah. Again, again, condolences to everybody
[1:01:50] SPEAKER: who was losing their jobs out there.
[1:01:51] SPEAKER: That's awful.
[1:01:55] SPEAKER: Let us know if we can help.
[1:01:56] SPEAKER: - Yeah, good.
[1:01:57] SPEAKER: And, and, and, and don't hesitate to ask for help.
[1:01:59] SPEAKER: Like it's like the thing, the thing,
[1:02:02] SPEAKER: the thing that my first boss at a magazine told me
[1:02:05] SPEAKER: as a budding journalist, after I'd signed the papers
[1:02:08] SPEAKER: that said I was going to come work there was,
[1:02:10] SPEAKER: when you work in the, in this business,
[1:02:12] SPEAKER: you can be sacked at any moment.
[1:02:14] SPEAKER: It won't be because of anything you did wrong.
[1:02:15] SPEAKER: It won't be because your work wasn't good enough.
[1:02:17] SPEAKER: It won't be because you, like, you,
[1:02:19] SPEAKER: you didn't kick ass, right?
[1:02:21] SPEAKER: It's because somebody in a suit, higher up the chain,
[1:02:25] SPEAKER: looked at some numbers and wanted one of the numbers
[1:02:27] SPEAKER: to be bigger than the other.
[1:02:28] SPEAKER: And the easiest way to do that was to cut people's jobs.
[1:02:32] SPEAKER: And, and it sucks.
[1:02:33] SPEAKER: And I was like, you know,
[1:02:34] SPEAKER: you told me this before I quit my good job
[1:02:35] SPEAKER: and moved to California,
[1:02:37] SPEAKER: probably would have not taken this job.
[1:02:39] SPEAKER: It's like, that's why I told you after you signed the papers.
[1:02:42] SPEAKER: - Oh boy, oh boy.
[1:02:44] SPEAKER: - Anyway, the upshot is it's not your fault.
[1:02:46] SPEAKER: You didn't do anything wrong.
[1:02:47] SPEAKER: Don't, don't, especially if it's the first time
[1:02:51] SPEAKER: you've been through this, it hits hard and it sucks.
[1:02:54] SPEAKER: - Yes, for sure.
[1:02:55] SPEAKER: - But you're going to get through it and you'll be okay.
[1:02:58] SPEAKER: And on that note, I mean,
[1:03:00] SPEAKER: hopefully our patrons don't want to cut jobs here
[1:03:02] SPEAKER: 'cause there's not that, there's not that much fat on the,
[1:03:04] SPEAKER: on the old, on the old podcast side of beef.
[1:03:08] SPEAKER: - Tech Pot Inc runs pretty, pretty lean.
[1:03:12] SPEAKER: - But we would, this is a listener supported show
[1:03:14] SPEAKER: and we want to thank our patrons as always.
[1:03:17] SPEAKER: - Yes, we do. Thank you, patrons.
[1:03:18] SPEAKER: - Thank you, patrons.
[1:03:20] SPEAKER: We especially want to thank our executive producer
[1:03:22] SPEAKER: tier patrons, including Nick Johnston,
[1:03:25] SPEAKER: Paddle Creek Games Makers, Fractured Veil, Andrew Slosky.
[1:03:29] SPEAKER: Octothorpe Bunny Crime is brought to you
[1:03:30] SPEAKER: by Nightmares Goats doing HVAC, period.
[1:03:34] SPEAKER: This is a, this is a direct Twitch reference.
[1:03:37] SPEAKER: Just Wedge, Joel Krauska, Twinkle Twinkie, and James Kamik.
[1:03:41] SPEAKER: Thank you all so much.
[1:03:42] SPEAKER: We really appreciate your support.
[1:03:44] SPEAKER: - We do.
[1:03:45] SPEAKER: - And everyone's support, frankly.
[1:03:47] SPEAKER: So yeah, that's, that's it for us this week.
[1:03:52] SPEAKER: The, like, I apologize for doing a news episode
[1:03:56] SPEAKER: 'cause we don't generally do these,
[1:03:57] SPEAKER: but that Tesla, like A, I feel vindicated as shit,
[1:04:01] SPEAKER: B, that Tesla, everybody should read that Tesla article
[1:04:05] SPEAKER: if you get in a car on the reg, so.
[1:04:07] SPEAKER: - It's a bit chilling.
[1:04:08] SPEAKER: - It is a bit chilling.
[1:04:09] SPEAKER: It is, it is right to your congressional representative
[1:04:13] SPEAKER: and/or senator level of chilling as far as I'm concerned.
[1:04:15] SPEAKER: Anyway.
[1:04:16] SPEAKER: - Anyway, we'll be back with the ever lighthearted topic
[1:04:19] SPEAKER: next week of questions.
[1:04:22] SPEAKER: - Is it questions already?
[1:04:23] SPEAKER: - Yeah, we were, we were very late on questions.
[1:04:26] SPEAKER: - Oh, right, 'cause we did the, yeah.
[1:04:28] SPEAKER: - The December questions spilled over,
[1:04:29] SPEAKER: so we are right back again.
[1:04:31] SPEAKER: Questions seeking answers on the Discord or, or?
[1:04:36] SPEAKER: - Or the techpod@content.town is the email address.
[1:04:40] SPEAKER: - That's right, techpod@content.town
[1:04:43] SPEAKER: is where to send some questions that we will answer.
[1:04:45] SPEAKER: - And, and we got good feedback last week
[1:04:48] SPEAKER: about the third, the not Patreon Patreon.
[1:04:52] SPEAKER: I don't know if we have a timeline on setting that up,
[1:04:55] SPEAKER: but I think we are going to turn off the $2 tier very soon.
[1:04:59] SPEAKER: I know I've said this before.
[1:05:00] SPEAKER: - Eventually, maybe.
[1:05:01] SPEAKER: - Look, it's-
[1:05:02] SPEAKER: - Probably.
[1:05:03] SPEAKER: - Change is scary, Brad.
[1:05:06] SPEAKER: But, but if, if you are, if you are interested in that,
[1:05:09] SPEAKER: at some point, like I think the plan,
[1:05:11] SPEAKER: my thought now is that if we turn off the $2 tier on Patreon
[1:05:14] SPEAKER: we should turn on an equivalent thing on the other platform.
[1:05:19] SPEAKER: 'Cause the, 'cause the, just so people,
[1:05:21] SPEAKER: for full transparency, the problem with the $2 tier
[1:05:22] SPEAKER: on Patreon is that with their cut at,
[1:05:25] SPEAKER: at smaller patronage levels, lower patronage levels,
[1:05:29] SPEAKER: their cut goes up.
[1:05:30] SPEAKER: So we basically, like we don't get very much money
[1:05:33] SPEAKER: from Patreon on $2 subs, which is fine.
[1:05:35] SPEAKER: Like we're, we're, we're okay.
[1:05:37] SPEAKER: But we would like to offer services
[1:05:41] SPEAKER: like a Mastodon account for people.
[1:05:43] SPEAKER: And the other thing might work better for that.
[1:05:46] SPEAKER: Anyway, that's where we're at.
[1:05:47] SPEAKER: - To be explored in the future.
[1:05:49] SPEAKER: - Yeah, but I'm, I'm going to say this is the hard cutoff
[1:05:53] SPEAKER: and we're going to turn it off on the 29th.
[1:05:55] SPEAKER: - Whoa, damn it.
[1:05:56] SPEAKER: - Before the 29th, so, so.
[1:05:58] SPEAKER: - Decisions just being made right here on the show.
[1:06:00] SPEAKER: - I'm sorry.
[1:06:01] SPEAKER: We, we can discuss further if you want.
[1:06:03] SPEAKER: We talked about it before.
[1:06:04] SPEAKER: - Yeah.
[1:06:05] SPEAKER: - We can record this if you want, I'm sorry.
[1:06:06] SPEAKER: - You should just rip the bandaid off.
[1:06:07] SPEAKER: No, it's okay.
[1:06:08] SPEAKER: - Yeah.
[1:06:11] SPEAKER: Neither of us like making decisions.
[1:06:13] SPEAKER: Anyway, we'll see you all next week.
[1:06:14] SPEAKER: Have a good one.
[1:06:15] SPEAKER: Bye.
[1:06:16] SPEAKER: (upbeat music)
