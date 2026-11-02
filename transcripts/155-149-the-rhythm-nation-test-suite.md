---
episode: 155
title: 149: The Rhythm Nation Test Suite
date: 2022-08-28
guests: none
duration: 1:07:59
---

[00:00] SPEAKER: I built something last night and I want to show it to you.
[00:03] SPEAKER: And this is a bad audio podcast, but I know.
[00:05] SPEAKER: Okay. You said it, not me.
[00:07] SPEAKER: Wow.
[00:09] SPEAKER: I built the Lego NES.
[00:10] SPEAKER: Hang on, can you hold that back up?
[00:11] SPEAKER: I'll try to paint a word picture.
[00:13] SPEAKER: I'll describe this tableau.
[00:14] SPEAKER: Paint a word picture.
[00:15] SPEAKER: Wait, is that mushroom a slice of pizza?
[00:18] SPEAKER: It's a quarter round flat piece of Lego.
[00:23] SPEAKER: I don't think mushrooms come in triangular shape.
[00:25] SPEAKER: Look, there's a reason the mushroom is triangular,
[00:26] SPEAKER: but I can't tell you that without spoilers, okay?
[00:29] SPEAKER: Oh, wait, the goombas are also triangular.
[00:31] SPEAKER: But you want to see the best part of this thing?
[00:33] SPEAKER: Let me bring it over to the microphone.
[00:36] SPEAKER: Wow.
[00:38] SPEAKER: It's like a 1-1 flip book.
[00:41] SPEAKER: It's like a tank tread 1-1.
[00:43] SPEAKER: Is that actual 1-1?
[00:44] SPEAKER: Can you hold it back up?
[00:45] SPEAKER: It's actual 1-1.
[00:45] SPEAKER: It's like the back half of 1-1.
[00:46] SPEAKER: It's after the second pitfall.
[00:48] SPEAKER: I did not look at...
[00:50] SPEAKER: Oh yeah, okay, sure.
[00:51] SPEAKER: Yeah, it's after the secondary...
[00:52] SPEAKER: It's like after the pipes before you get to the three stack of the 3-2-1
[00:58] SPEAKER: like block with the star at the top.
[01:00] SPEAKER: Did you follow a plan for that or did you actually lay out that level design yourself?
[01:05] SPEAKER: You know, I just pulled it from my brain.
[01:06] SPEAKER: No, of course I followed a plan.
[01:07] SPEAKER: Are you kidding?
[01:08] SPEAKER: Good God, man.
[01:09] SPEAKER: I don't know.
[01:09] SPEAKER: I'm not that kind of...
[01:10] SPEAKER: I'm okay at Lego, but I am not build 1-1 out of a bunch of Lego pieces in my head good at Lego.
[01:17] SPEAKER: Even after all this time, I don't know if I've got the best read on how technically inclined you are.
[01:23] SPEAKER: Look, I am really, really good at following instructions.
[01:26] SPEAKER: Okay, sure.
[01:27] SPEAKER: And I can take two technologies that already exist and glue them together pretty effectively.
[01:34] SPEAKER: The coolest thing I ever figured out was how to get eye movement right in FU,
[01:38] SPEAKER: which was we weighted every object in the world with the material system
[01:42] SPEAKER: in the thing we built and with general levels of interest.
[01:47] SPEAKER: And then we built a gradient that had a fractional, given some IP here, away today, I guess.
[01:54] SPEAKER: We had a gradient that started with the center point of where your eye is pointing,
[01:57] SPEAKER: the ray that comes straight out from your eye.
[02:00] SPEAKER: And the number got lower the further you got away from there.
[02:04] SPEAKER: So those two things multiplied by each other.
[02:06] SPEAKER: And then your eye just looked at the thing that was the most interesting in that cone of view.
[02:11] SPEAKER: And that gave you pretty good eye movements and saccades and let you focus on things like
[02:17] SPEAKER: other people's eyeballs and mouths and watch the objects that they're holding and things like that.
[02:22] SPEAKER: Now, whoever is defining what is arbitrarily interesting in the scene
[02:25] SPEAKER: suddenly has a lot of power over how the eyes work.
[02:29] SPEAKER: Yeah, we had a really fun one where we left a decimal point out one time.
[02:32] SPEAKER: And there was a beaker in one of the episodes that was just the most interesting thing in the world.
[02:37] SPEAKER: So everybody's eyes tracked it, whether it was in front of them or not.
[02:39] SPEAKER: I wish we lived in a world where a beaker was the most interesting thing to go.
[02:43] SPEAKER: Look, Brad, the thing that was worrisome was when you turned away from the beaker,
[02:45] SPEAKER: your eyes stayed locked onto the beaker.
[02:47] SPEAKER: So your eyes just rolled back into your head the further you went.
[02:52] SPEAKER: And the worst part is there's bigger eyes on the back of the eyeballs in the Fusho models.
[02:58] SPEAKER: Why?
[02:59] SPEAKER: We tried two different size eyes and it was easier to just
[03:02] SPEAKER: do them again than it was to replace them.
[03:04] SPEAKER: You can just peel off the back eye?
[03:07] SPEAKER: Look, man, we're not in the eye peeling business here.
[03:10] SPEAKER: We're making VR content.
[03:11] SPEAKER: It's not eye peeling you do on your own.
[03:14] SPEAKER: That's some saw business.
[03:15] SPEAKER: We're not making that kind of, we're making family-friendly content, Brad.
[03:19] SPEAKER: VR.
[03:21] SPEAKER: It's for kids.
[03:45] SPEAKER: [Music]
[03:51] SPEAKER: Welcome to Brad and Will Made a Tech Pod.
[03:53] SPEAKER: I'm Will.
[03:54] SPEAKER: I'm Brad.
[03:55] SPEAKER: How you doing, Brad?
[03:56] SPEAKER: I'm doing well.
[03:56] SPEAKER: I've noticed that I've felt a little bit of an announcer voice on that intro.
[03:59] SPEAKER: I'm Brad.
[04:01] SPEAKER: I'm Brad.
[04:03] SPEAKER: I'm always jealous of like the radio color guys that sit in the booth and have like,
[04:07] SPEAKER: just like their whole job is to be interesting and have good voices.
[04:11] SPEAKER: For sure, you know who, who I feel like is a, as an underappreciated voice is Rod Roddy.
[04:16] SPEAKER: Oh, Price is Right announcer Rod Roddy.
[04:18] SPEAKER: Yes.
[04:19] SPEAKER: Come on down.
[04:20] SPEAKER: Yeah.
[04:21] SPEAKER: Come on down to that.
[04:21] SPEAKER: Now that's a line.
[04:22] SPEAKER: Come on down.
[04:24] SPEAKER: You're the next contestant.
[04:25] SPEAKER: Do you, do you think, well, okay.
[04:27] SPEAKER: First off, how far back do you think he, like he has to have a radio announcer mic, right?
[04:32] SPEAKER: Like he has a big, like an old timey.
[04:34] SPEAKER: I don't know.
[04:35] SPEAKER: Like Bob Barker was famous for the skinny mic.
[04:38] SPEAKER: I don't know if there, is there a name for that thing?
[04:41] SPEAKER: The one that, well, Vinnie bought one.
[04:43] SPEAKER: Right.
[04:43] SPEAKER: When we were at whiskey, remember?
[04:44] SPEAKER: I remember everyone was very excited that we got the Price is Right mic.
[04:47] SPEAKER: It was, it was.
[04:48] SPEAKER: Ryan in particular, I seem to remember was, I mean, there was, but there was also like,
[04:52] SPEAKER: after we got back to CBS, there was always talk of going and shooting something on the
[04:56] SPEAKER: Price is Right set.
[04:56] SPEAKER: I think there was a lot of Price is Right fandom in that group.
[05:00] SPEAKER: I mean, I love Price is Right.
[05:01] SPEAKER: I don't, I don't, I don't know what it is.
[05:04] SPEAKER: Like, okay.
[05:06] SPEAKER: The Price is Right thing.
[05:07] SPEAKER: There's so many good stories about the Price is Right.
[05:08] SPEAKER: Like there's the guy that, that made the spreadsheet of all the prices and realized
[05:12] SPEAKER: that they just use the same prices over and over again.
[05:14] SPEAKER: If he memorized a few thousand things, then he could exactly hit the price every time.
[05:18] SPEAKER: Wait, hang on.
[05:19] SPEAKER: There was a card counter, but for the Price is Right?
[05:21] SPEAKER: Oh, did you not, have you never heard this story?
[05:23] SPEAKER: I don't think so.
[05:24] SPEAKER: Oh, it's incredible.
[05:24] SPEAKER: They did a documentary about him.
[05:26] SPEAKER: He, he, he like tracked the prices on things for years and went to sit on the show every
[05:32] SPEAKER: day.
[05:33] SPEAKER: And one day he, you know, they, they, they knew him and one day they put him on.
[05:36] SPEAKER: Right.
[05:37] SPEAKER: And he hit the showcase, he hit the first round where you have to guess to get on the
[05:41] SPEAKER: contest.
[05:41] SPEAKER: Exactly.
[05:42] SPEAKER: Right.
[05:42] SPEAKER: I want to say he missed the second round, but he rolled well in the, in the, on the spin,
[05:47] SPEAKER: spin the big wheel bit.
[05:49] SPEAKER: So he went to the showcase and he hit the showcase exactly on the dollar.
[05:53] SPEAKER: No way.
[05:54] SPEAKER: Yeah.
[05:54] SPEAKER: But did you get something special for doing that?
[05:56] SPEAKER: I forget.
[05:57] SPEAKER: Yeah.
[05:57] SPEAKER: You get both showcases if you're within a hundred bucks.
[05:59] SPEAKER: Wow.
[06:00] SPEAKER: And they thought he cheated.
[06:02] SPEAKER: They thought he was cheating.
[06:02] SPEAKER: They thought he had like somebody on the inside or something like that.
[06:04] SPEAKER: So they never had the episode was right after Drew Carey took over and, and like when they
[06:09] SPEAKER: talked to Drew Carey about it, Drew Carey was like, look, I took over this thing that
[06:12] SPEAKER: had been running for 60 years or 50 years or something.
[06:14] SPEAKER: And I was afraid that two months in I had killed it.
[06:16] SPEAKER: Right.
[06:19] SPEAKER: It's fabulous.
[06:20] SPEAKER: I'll dig it up.
[06:20] SPEAKER: I'll put it in the show notes.
[06:21] SPEAKER: Hang on.
[06:21] SPEAKER: Do you kill the show by running an episode with someone who you think cheated or do you
[06:25] SPEAKER: kill it by not honoring your obligation to a guy who won?
[06:28] SPEAKER: But you kill the show by allowing cheaters to prosper.
[06:31] SPEAKER: But is that cheating?
[06:32] SPEAKER: No, it's not.
[06:33] SPEAKER: That's the thing that doesn't sound like cheating to me.
[06:35] SPEAKER: They, they messed up, but it's, it's the thing that they'd been doing for years.
[06:38] SPEAKER: And nobody had, nobody had like internetized it and, you know, done the, see, I wrapped
[06:42] SPEAKER: it back around.
[06:43] SPEAKER: So it's a technology thing.
[06:44] SPEAKER: Wait.
[06:44] SPEAKER: So do they, did they ever make good on the prices?
[06:46] SPEAKER: I assume he got the prices.
[06:47] SPEAKER: I don't think they ever aired the episode.
[06:49] SPEAKER: And that's, I bet, I bet for somebody being that big a fan of that show, I bet that's
[06:53] SPEAKER: the real tragedy.
[06:54] SPEAKER: He used to, he's one of those people who used to go on the show every day and he would
[06:57] SPEAKER: sit in the audience and yell prices to people and was always right.
[07:01] SPEAKER: Like just always consistently right.
[07:03] SPEAKER: Prices, right.
[07:04] SPEAKER: Documentary, perfect bid, the contestant who knew too much.
[07:07] SPEAKER: Yeah.
[07:08] SPEAKER: And, and when I think about it, it may be one layer deeper.
[07:11] SPEAKER: Cause it may be the person who made the perfect bid was sitting in the, was, was not the
[07:16] SPEAKER: person who had done the homework because they knew not to put him on.
[07:19] SPEAKER: It may have been that he was sitting next to the guy's wife and they were yelling.
[07:23] SPEAKER: He was yelling the number to them, to the person who made the perfect bid.
[07:26] SPEAKER: And then the guy who made the perfect bid, I think didn't want to acknowledge that he
[07:30] SPEAKER: had taken the bid from somebody in the audience.
[07:32] SPEAKER: It's it's, it's, it's a, it's a, it's a real web, Brad.
[07:36] SPEAKER: It's on Netflix.
[07:36] SPEAKER: It turns out perfect bid.
[07:38] SPEAKER: Highly recommended.
[07:39] SPEAKER: I watched it like five years ago.
[07:40] SPEAKER: It's it's, it's really good.
[07:41] SPEAKER: Or before the pandemic, maybe I can't remember which.
[07:44] SPEAKER: Yeah.
[07:44] SPEAKER: You should, you would like it.
[07:45] SPEAKER: I believe if you were, I can't believe you didn't ever do anything on prices, right.
[07:48] SPEAKER: On the prices, right.
[07:49] SPEAKER: Set.
[07:49] SPEAKER: Uh, I mean, that was like a boy, wouldn't that be cool if kind of thing.
[07:52] SPEAKER: And then it's like, Oh, that would have to go through eight layers of people who don't
[07:55] SPEAKER: give a shit about us.
[07:56] SPEAKER: If they even know we exist.
[07:58] SPEAKER: I was going to say I would have murdered everyone up to and including Drew Carey to do that.
[08:01] SPEAKER: So it's like shooting inside the big brother house.
[08:03] SPEAKER: I don't think I don't really like, I like big brother.
[08:05] SPEAKER: It's entertaining.
[08:05] SPEAKER: The contests are good.
[08:07] SPEAKER: I, I would love to get to walk around inside that house and see what a fucking disaster
[08:11] SPEAKER: it is after those people live in there for 90 days, it's gotta be real.
[08:15] SPEAKER: Duded.
[08:16] SPEAKER: No, thank you.
[08:16] SPEAKER: I think I, if I remember, I think the talk was of like, Oh, how great would it be to
[08:20] SPEAKER: do game of the year segments on the prices, right?
[08:22] SPEAKER: Set.
[08:23] SPEAKER: That would be amazing.
[08:24] SPEAKER: Like how that's pretty tailor made for that.
[08:26] SPEAKER: Anyway.
[08:27] SPEAKER: Do you think they'd let you put like stuff on the wheel?
[08:29] SPEAKER: That's the thing.
[08:30] SPEAKER: Change the letters, how operational is the equipment when nobody's there?
[08:33] SPEAKER: Right.
[08:33] SPEAKER: Could you, could you, could you do the, the, the yodeler?
[08:37] SPEAKER: Could you do, could you play Plinko?
[08:39] SPEAKER: I don't know.
[08:39] SPEAKER: Where does all that stuff live?
[08:40] SPEAKER: There's a warehouse.
[08:42] SPEAKER: Yeah, I guess so.
[08:43] SPEAKER: It's gotta be a warehouse.
[08:44] SPEAKER: All those machines must be pretty mobile on wheels, casters.
[08:47] SPEAKER: They're all on a lifty dollies.
[08:49] SPEAKER: I bet the ones that had the foot, you know, the foot lift and doll.
[08:52] SPEAKER: Anyway, lifty dollies, lifty dollies, technical term.
[08:55] SPEAKER: It's my favorite fifties musical.
[08:57] SPEAKER: Brad, I have cues.
[08:59] SPEAKER: Oh.
[09:00] SPEAKER: Well, I guess you have cues technically.
[09:02] SPEAKER: I have a bunch of cues.
[09:03] SPEAKER: I believe you have cue.
[09:04] SPEAKER: I have cue.
[09:05] SPEAKER: We're going to turn them into A's though today.
[09:07] SPEAKER: That's what we do here at the last episode of the month.
[09:09] SPEAKER: That's true.
[09:10] SPEAKER: You have one cue from the email inbox?
[09:13] SPEAKER: I do.
[09:14] SPEAKER: You mean techpod@content.town?
[09:16] SPEAKER: I do mean that one.
[09:18] SPEAKER: I'm sorry.
[09:19] SPEAKER: I do mean techpod@content.town.
[09:20] SPEAKER: Thank you.
[09:21] SPEAKER: You gotta say it three times because people won't remember techpod@content.town if you don't do that.
[09:25] SPEAKER: If you have questions you would like to be turned into answers,
[09:28] SPEAKER: you can email them to techpod@content.town.
[09:30] SPEAKER: Or if you are a member of the fabulous techpod patron, which supports this listener supported
[09:34] SPEAKER: podcast, you can go into the questions seeking answers channel and post it there.
[09:38] SPEAKER: And then once a month we pull out the best questions, or at least the ones that strike
[09:41] SPEAKER: our fancy, you know, it's not really a value judgment.
[09:43] SPEAKER: It's more like, Hey, do I want to answer this or not?
[09:45] SPEAKER: And we answer the questions.
[09:47] SPEAKER: Probably not about orange pants though.
[09:49] SPEAKER: So sorry Warbird.
[09:52] SPEAKER: Do you want to read this one or you want me to read it?
[09:53] SPEAKER: You go forward.
[09:55] SPEAKER: I believe this blog article about the power of Janet Jackson may be of some interest.
[09:59] SPEAKER: Jintor.
[10:00] SPEAKER: Yes.
[10:00] SPEAKER: So you didn't see this going around last week.
[10:02] SPEAKER: No, I was pretty busy last week.
[10:04] SPEAKER: That's fair.
[10:04] SPEAKER: Yeah.
[10:05] SPEAKER: It was, it kind of is one of those things that just sort of blew up on tech Twitter for an afternoon.
[10:09] SPEAKER: Yeah.
[10:10] SPEAKER: And it's like, if you, if you're logged out for the three hours and something like this
[10:12] SPEAKER: is going around, then it's, you never see it basically.
[10:17] SPEAKER: Right.
[10:17] SPEAKER: So this is a it's a blog post on like devblogs.microsoft.com,
[10:23] SPEAKER: which gather is just where some Microsoft developers blog.
[10:26] SPEAKER: Are you familiar with the name Raymond chin?
[10:28] SPEAKER: Yeah.
[10:28] SPEAKER: Raymond.
[10:29] SPEAKER: He's he's a person who's been working on windows stuff for a really long time.
[10:34] SPEAKER: Okay.
[10:34] SPEAKER: Great books and stuff.
[10:35] SPEAKER: He's a channel nine guy too.
[10:36] SPEAKER: I believe it's channel nine.
[10:38] SPEAKER: It's MSDNs and Microsoft developer networks, like internal content, TV stuff.
[10:43] SPEAKER: Okay.
[10:44] SPEAKER: Okay.
[10:44] SPEAKER: Yeah.
[10:44] SPEAKER: When this was making the rounds, a bunch of people were like, Oh, Raymond chin, like,
[10:47] SPEAKER: like he was a known figure and I hadn't heard of him before.
[10:50] SPEAKER: A very short version.
[10:52] SPEAKER: This is about God.
[10:53] SPEAKER: When is this from?
[10:55] SPEAKER: It's like 98, early two thousands.
[10:58] SPEAKER: Roughly windows XP era is what he says.
[11:00] SPEAKER: He doesn't put a date on this.
[11:02] SPEAKER: What was this in their hardware testing lab, compatibility lab or something?
[11:06] SPEAKER: Yeah, this is a normal, this is part of the normal Janet Jackson benchmark test.
[11:11] SPEAKER: Yes.
[11:11] SPEAKER: The rhythm nation test suite.
[11:13] SPEAKER: Yeah.
[11:15] SPEAKER: Yeah.
[11:15] SPEAKER: They found that playing the music video for rhythm nation on these laptops would straight
[11:19] SPEAKER: up crash them and maybe destroy the hard drive.
[11:22] SPEAKER: And then they found that it was also happening to competitors laptops.
[11:26] SPEAKER: And it happened like two machines that weren't connected to each other, but were adjacent
[11:30] SPEAKER: to each other.
[11:31] SPEAKER: Then they finally found it was happening to like other laptops surrounding the laptop
[11:35] SPEAKER: playing the video.
[11:37] SPEAKER: Yep.
[11:37] SPEAKER: It turns out that the song contained one of the natural resonant frequencies for the model
[11:41] SPEAKER: of 5,400 RPM laptop, hard drives that these laptops and other manufacturers used.
[11:48] SPEAKER: So like the natural resonant frequency, this is like the idea that this is why you can't
[11:51] SPEAKER: ride horses across the golden gate bridge is because the frequency of when their feet
[11:57] SPEAKER: hit is, is we'll, we'll make the bridge vibrate and then wobble.
[12:02] SPEAKER: Like the Tacoma narrows bridge did in 1940.
[12:04] SPEAKER: Are you making this up?
[12:05] SPEAKER: No, this is a true thing.
[12:06] SPEAKER: Is that really, you're not allowed to ride horses a lot of across a lot of bridges.
[12:09] SPEAKER: Wow.
[12:10] SPEAKER: Yeah.
[12:11] SPEAKER: Huh?
[12:11] SPEAKER: I wouldn't, I wouldn't think magnitude.
[12:14] SPEAKER: Like I could, I could see, I could see the frequencies lining up, but I wouldn't think
[12:17] SPEAKER: that it would be strong enough to actually.
[12:19] SPEAKER: Well, see the thing is each, each impact multiplies.
[12:22] SPEAKER: Oh, sure.
[12:23] SPEAKER: So you hit, you hit at the right point of the wave.
[12:25] SPEAKER: It's like, it's like when you're on a trampoline, you know, you're on a trampoline, two people
[12:28] SPEAKER: were on the trampoline, right?
[12:29] SPEAKER: One person goes up, right?
[12:31] SPEAKER: When they, when would they hit the next person hits and you, and the person gets heated up
[12:35] SPEAKER: even higher.
[12:35] SPEAKER: So the horses do that, but with bridges and then tragedy.
[12:40] SPEAKER: Okay.
[12:40] SPEAKER: So if I ever want to grind San Francisco to a halt.
[12:43] SPEAKER: Yeah.
[12:44] SPEAKER: Just ride, just get a stampede of horses across the bridge.
[12:47] SPEAKER: It's also, this is also why when soldiers are marching and they cross a bridge, they
[12:53] SPEAKER: don't march in unison anymore.
[12:55] SPEAKER: They, they, they vary their foot rhythm.
[12:57] SPEAKER: Interesting.
[12:58] SPEAKER: Yeah.
[12:58] SPEAKER: They're like Fremen.
[12:59] SPEAKER: I'm sorry.
[13:00] SPEAKER: They're like what?
[13:00] SPEAKER: Fremen, you know, from Dune, they, they don't walk with the pattern cause the sandworms
[13:04] SPEAKER: will eat them.
[13:04] SPEAKER: It's the same thing, except for, you know, less resonant frequencies there and more horrible
[13:08] SPEAKER: giant monsters.
[13:09] SPEAKER: I've never experienced Dune in any form.
[13:11] SPEAKER: Well, I know what our next movie is.
[13:13] SPEAKER: Great.
[13:14] SPEAKER: Is that tech enough?
[13:15] SPEAKER: Yeah.
[13:16] SPEAKER: Is it?
[13:16] SPEAKER: I'm going to say yes.
[13:17] SPEAKER: Huh?
[13:18] SPEAKER: Interesting.
[13:19] SPEAKER: And look, the new one's good.
[13:20] SPEAKER: I like it a lot, but we're watching the David Lynch one first cause you can't appreciate
[13:24] SPEAKER: the new one without having the madness of horny sting as, as, uh, as the young Harkonnen.
[13:31] SPEAKER: And poor war games just got its place in line jumped.
[13:34] SPEAKER: Sorry, war games.
[13:35] SPEAKER: So, so this blog goes on to say the manufacturer worked around this problem by adding a custom
[13:39] SPEAKER: filter in the audio pipeline that detected and removed the offending frequencies during
[13:43] SPEAKER: audio playback.
[13:44] SPEAKER: You think, is he talking about a hardware filter?
[13:46] SPEAKER: My guess is a software filter.
[13:48] SPEAKER: Oh yeah.
[13:48] SPEAKER: Okay.
[13:49] SPEAKER: Yeah.
[13:49] SPEAKER: He said a digital version of a do not remove sticker on that audio filter.
[13:52] SPEAKER: So it must be software.
[13:53] SPEAKER: Yeah.
[13:53] SPEAKER: It's a commented in code.
[13:55] SPEAKER: Yeah.
[13:56] SPEAKER: But then that wouldn't survive like an OS swap.
[13:59] SPEAKER: Like what if you put Linux on that?
[14:01] SPEAKER: Well, it's probably just downhill, right?
[14:03] SPEAKER: Oh yeah.
[14:04] SPEAKER: It's probably not in the Linux, but it's probably like all subsequent versions of windows.
[14:06] SPEAKER: Oh yeah, yeah, yeah.
[14:07] SPEAKER: Just filter out.
[14:08] SPEAKER: That's why I mean, if you put something other than windows on here.
[14:11] SPEAKER: I wonder, I wonder, I wonder if I play rhythm nation on my computer now, if it's still
[14:15] SPEAKER: filtering, like, I wonder if I'm not hearing rhythm nation all these years later as Janet
[14:19] SPEAKER: Jackson intended it to be heard because of this audio filter.
[14:23] SPEAKER: We as a nation have been robbed.
[14:25] SPEAKER: It's less of a rhythm nation than it was before.
[14:28] SPEAKER: That's that's man.
[14:29] SPEAKER: You're telling me.
[14:30] SPEAKER: Thanks.
[14:30] SPEAKER: Windows XP.
[14:31] SPEAKER: This is a funny story.
[14:32] SPEAKER: I like that would have been perplexing the computers crashing computers adjacent to,
[14:37] SPEAKER: but not connected to that's a good one, but that was a fun one to diagnose.
[14:41] SPEAKER: Yeah.
[14:42] SPEAKER: I wonder how many hard drives they killed figuring that out.
[14:44] SPEAKER: That's my question.
[14:46] SPEAKER: Too many.
[14:47] SPEAKER: It was a lot.
[14:47] SPEAKER: Too many have fallen.
[14:49] SPEAKER: Yeah.
[14:50] SPEAKER: Okay.
[14:50] SPEAKER: I actually didn't say that.
[14:52] SPEAKER: Did he say killed them or it was just crashing them?
[14:54] SPEAKER: Like it maybe just temporarily disrupted them.
[14:56] SPEAKER: I assume when you're talking about resonant failures on hard drives and that means splatters
[15:00] SPEAKER: started wobbling and whacking into things.
[15:02] SPEAKER: Sure, sure.
[15:04] SPEAKER: The literal definition of a crash.
[15:06] SPEAKER: Fair.
[15:07] SPEAKER: Okay.
[15:07] SPEAKER: Let's move on to Discord questions.
[15:10] SPEAKER: Here is one from Quasar.
[15:13] SPEAKER: Why don't either of you have a Wikipedia page?
[15:16] SPEAKER: I do not fit the, I do not attain the noteworthiness guidelines and, or no one has ever made one
[15:23] SPEAKER: for me and, or I am not going to make my own Wikipedia page because that is sad.
[15:28] SPEAKER: Yes.
[15:28] SPEAKER: The latter two of those were my answer.
[15:30] SPEAKER: I didn't realize, do they actually have like stringent guidelines for who can have a page?
[15:33] SPEAKER: I didn't, I didn't, I thought it was fairly loose.
[15:35] SPEAKER: I thought, I thought it was much more down to did somebody care enough to go make one
[15:39] SPEAKER: and not, not as much like, Oh, you have to meet some bar.
[15:42] SPEAKER: There's a bar.
[15:43] SPEAKER: Is there really?
[15:44] SPEAKER: Yeah.
[15:46] SPEAKER: Hold on.
[15:47] SPEAKER: Notoriety.
[15:49] SPEAKER: You have to be a certain level of notoriety to warrant a Wikipedia page.
[15:52] SPEAKER: Oh yeah.
[15:52] SPEAKER: Notability.
[15:53] SPEAKER: Notability.
[15:54] SPEAKER: That's it.
[15:55] SPEAKER: Notability is a test used by editors to decide whether a given topic warrants its own article.
[16:00] SPEAKER: I know this because I, for a while in the olden times, I used to like to go to people who
[16:08] SPEAKER: didn't have the right notability for a Wikipedia page and put the tag that this does not meet the
[16:13] SPEAKER: notability guidelines on their pages.
[16:15] SPEAKER: Oh man.
[16:16] SPEAKER: That's ruthless.
[16:17] SPEAKER: Not friends, just to be clear.
[16:19] SPEAKER: I mean, you, I'm sure you have seen the individual person Wikipedia pages that are very clearly
[16:25] SPEAKER: contributed to by said person.
[16:26] SPEAKER: Almost all of them that are not like actual celebrities or famous people.
[16:30] SPEAKER: The ones, the ones that are extremely glowing about the person's achievements.
[16:34] SPEAKER: Yes.
[16:35] SPEAKER: The one that looks like they just copied and pasted their CV.
[16:38] SPEAKER: Yeah.
[16:39] SPEAKER: I'm not going to go through this.
[16:41] SPEAKER: I've got the general notability guidelines in front of me, but.
[16:44] SPEAKER: Yep.
[16:45] SPEAKER: I was on the maximum PC page for a long time and I, there used to be a tested page.
[16:48] SPEAKER: I don't know if they still is.
[16:50] SPEAKER: Yeah.
[16:50] SPEAKER: Yeah.
[16:50] SPEAKER: I mean, I think my name is mentioned on a couple of pages more general.
[16:56] SPEAKER: I feel like I probably don't need a Wikipedia page.
[16:58] SPEAKER: I don't know that I've done enough that's of worth to warrant one at this point.
[17:01] SPEAKER: I think I would much prefer not having one actually.
[17:04] SPEAKER: Plus there are other Will Smith's.
[17:06] SPEAKER: And like you said, going and making your own page is pathetic.
[17:09] SPEAKER: Sad.
[17:10] SPEAKER: Yes.
[17:12] SPEAKER: Question from fortune.
[17:14] SPEAKER: Most of the, you can make a podcast at home.
[17:16] SPEAKER: Things I have seen concentrate almost entirely on microphones and other hardware.
[17:19] SPEAKER: Is it possible to spend some time going over the other side of things?
[17:23] SPEAKER: Editing software, distribution, tracking, listener stats, ad reads, et cetera.
[17:26] SPEAKER: That could be a whole episode going over all of that stuff, but we could,
[17:30] SPEAKER: we could summarize quickly some stuff.
[17:32] SPEAKER: Yeah.
[17:34] SPEAKER: There's a bazillion audio editors at this point.
[17:36] SPEAKER: You can do it in audacity easily.
[17:38] SPEAKER: We use audacity and audition and are kind of trying to try working on transitioning to Reaper,
[17:43] SPEAKER: but getting the filtering set up right is a little bit challenging.
[17:48] SPEAKER: Distribution is easy.
[17:51] SPEAKER: Like there are in the old days, you had to set up a WordPress blog and then find someplace
[17:55] SPEAKER: to host the file and like archive.org.
[17:56] SPEAKER: And then you generate a plugin and they generate an RSS feed.
[17:59] SPEAKER: It was a big pain in the ass.
[18:00] SPEAKER: You don't have to do that anymore.
[18:01] SPEAKER: Yeah.
[18:02] SPEAKER: Now you pay solutions.
[18:04] SPEAKER: Yeah, you pay Libsyn five bucks a month or simple cast 15 bucks a month or any number
[18:08] SPEAKER: of other podcasts hosts.
[18:11] SPEAKER: Like they're inexpensive starter plans.
[18:14] SPEAKER: And basically the thing that varies between them is how they charge, if they charge for
[18:20] SPEAKER: overage in terms of numbers of episodes downloaded or numbers of episodes uploaded in some cases.
[18:28] SPEAKER: Some people charge more for hosting for more listeners.
[18:31] SPEAKER: Some people charge more for hosting a IAB, which is the international advertisers
[18:37] SPEAKER: Bureau Bureau, I think internet advertising Bureau for IAB compliant metrics, which means
[18:44] SPEAKER: you can put advertising on your podcast.
[18:46] SPEAKER: Yeah.
[18:46] SPEAKER: Some of the backends that you'll see on podcast hosts literally let you toggle between like
[18:51] SPEAKER: stats by blank metric and IAB stats.
[18:54] SPEAKER: Like there are these specific guidelines for the IAB ones where, and that just happened
[18:59] SPEAKER: in the last gosh, five years for most of them, like this kind of podcast host didn't exist
[19:04] SPEAKER: before like 2015.
[19:06] SPEAKER: Yeah.
[19:06] SPEAKER: Really like the entirety of the podcast, like hosting an advertising business was a gigantic
[19:11] SPEAKER: like fly by night mess up until about that time.
[19:15] SPEAKER: Yeah.
[19:15] SPEAKER: The amount of money we spent hosting the podcast at whiskey media ourselves was pretty stupendous.
[19:21] SPEAKER: Right.
[19:22] SPEAKER: Because there wasn't like, we couldn't just pay somebody 15 bucks a month per podcast
[19:25] SPEAKER: to do it.
[19:26] SPEAKER: Yeah.
[19:26] SPEAKER: The, the other big thing that's happened with advertising is that ads have become entirely
[19:30] SPEAKER: decoupled from the shows they run on now.
[19:33] SPEAKER: Oh, right.
[19:33] SPEAKER: It's all, it's all handled dynamically.
[19:35] SPEAKER: So like you're doing ad reads separately and uploading them into a tool and then like campaigns
[19:39] SPEAKER: are getting sold on the backend and those just get inserted into, into shows at time
[19:44] SPEAKER: of download based on what campaigns are active at the moment.
[19:46] SPEAKER: And where you live and what your demographics are and all that stuff.
[19:49] SPEAKER: And then, and then, yeah, there's all kinds of data harvesting that they use to further
[19:52] SPEAKER: kind of winnow down, which ads you're hearing.
[19:54] SPEAKER: And I mean, the, the dynamic ads are nice from a content creator perspective because
[19:59] SPEAKER: it takes a lot of the overhead of managing ads out of your, out of your pipeline.
[20:03] SPEAKER: Yes.
[20:03] SPEAKER: And also it allows you to monetize your back catalog.
[20:06] SPEAKER: So yes.
[20:06] SPEAKER: So it's funny, like per episode downloads, aren't really a big deal now in terms of advertisers.
[20:11] SPEAKER: It's just how many downloads are you in a week across your whole library of shows.
[20:15] SPEAKER: So like if you've got three years of podcasts before, like when we baked ads into the actual
[20:20] SPEAKER: recording before, once the campaign, like, like say for a six month old podcast where
[20:25] SPEAKER: that campaign ended five months ago, people go and download that episode today.
[20:28] SPEAKER: It's worthless.
[20:29] SPEAKER: Like you make nothing on it.
[20:30] SPEAKER: Yeah.
[20:30] SPEAKER: But I mean the content probably is still good.
[20:32] SPEAKER: But now since they can put active current ads into old episodes than any podcast at
[20:37] SPEAKER: all that gets downloaded is valuable.
[20:39] SPEAKER: Yeah.
[20:39] SPEAKER: So if I were starting a new podcast, I would probably check out on Libsyn.
[20:43] SPEAKER: It's really easy to move podcasts between hosts.
[20:46] SPEAKER: It is.
[20:46] SPEAKER: I mean, we did that exact thing.
[20:48] SPEAKER: Yeah.
[20:48] SPEAKER: I can't, I don't love Libsyn's backend.
[20:51] SPEAKER: It's not great.
[20:52] SPEAKER: It's pretty dated.
[20:53] SPEAKER: I mean, it is, it is, you're getting your $5 a month.
[20:57] SPEAKER: But it is very inexpensive.
[20:59] SPEAKER: Yeah.
[20:59] SPEAKER: And, and if you are just doing something for fun, it doesn't make sense to pay for somebody
[21:04] SPEAKER: that's going to do your IAB, yeah, tricks and all that stuff.
[21:07] SPEAKER: Yeah.
[21:07] SPEAKER: It's a good place to start for sure.
[21:10] SPEAKER: The other thing we haven't talked about is the post stuff.
[21:12] SPEAKER: So once you, once you've edited the audio file and you have a big wave, you have to
[21:17] SPEAKER: add MP3 tags and also do levelator stuff, which is, I think we still used, you still
[21:23] SPEAKER: use levelator, right?
[21:24] SPEAKER: So I still, I still Chuck the export into levelator.
[21:26] SPEAKER: It's an old habits die hard, but also that thing works.
[21:29] SPEAKER: It doesn't hurt anything.
[21:30] SPEAKER: Levelator does audio compression where it kind of brings all the levels up to the same,
[21:34] SPEAKER: same LUTs.
[21:35] SPEAKER: I guess it does a bunch of stuff.
[21:36] SPEAKER: It's kind of like a, there's a secret sauce in there that they've never said exactly all
[21:41] SPEAKER: of the processing that it's doing.
[21:42] SPEAKER: No one's exactly replicated it.
[21:44] SPEAKER: Reaper has a similar function that I, it's a little more complicated that I haven't quite
[21:48] SPEAKER: figured out yet.
[21:49] SPEAKER: Yeah.
[21:49] SPEAKER: There are also like plugins you'll see around like VSTs and stuff that claim to be like,
[21:53] SPEAKER: Hey, this is levelator, but a plugin, like people have tried to recreate it for a long
[21:57] SPEAKER: time.
[21:57] SPEAKER: Also worth mentioning the ultra shawl people who we talked about a couple of weeks ago
[22:04] SPEAKER: released English language documentation the other day.
[22:07] SPEAKER: So I saw that they tweeted at us and we're pretty excited.
[22:10] SPEAKER: Yeah, that was cool.
[22:11] SPEAKER: So I got to go check that out and see if, see if my translated documentation is, is less,
[22:16] SPEAKER: if the new actual translated documentation is better than the machine tracking translated
[22:19] SPEAKER: documentation was, which was fine, but not perfect.
[22:22] SPEAKER: Anyway.
[22:23] SPEAKER: Yeah.
[22:24] SPEAKER: It's never been a better time to start a podcast.
[22:27] SPEAKER: Yeah.
[22:27] SPEAKER: Anybody can do it.
[22:28] SPEAKER: I keep, I keep feeling like, God, who was it that ran, was it the New York times that
[22:33] SPEAKER: ran that story?
[22:33] SPEAKER: Like it's been years now of along the lines of have we reached peak podcast and yet it
[22:39] SPEAKER: seems to keep going.
[22:41] SPEAKER: Sweet summer children waiting for the bottom to fall out.
[22:44] SPEAKER: Yeah, it's fine.
[22:45] SPEAKER: Um, so do you want to talk about this squeaky stuff?
[22:49] SPEAKER: Yeah, we can do that.
[22:50] SPEAKER: I've killed a couple of chairs because of that.
[22:51] SPEAKER: Oh, wow.
[22:52] SPEAKER: You highlighted this one.
[22:53] SPEAKER: So, okay.
[22:53] SPEAKER: Question from meatball in the same vein.
[22:56] SPEAKER: You guys do both do a ton of podcasts and streams.
[22:58] SPEAKER: How do you deal with squeaking chairs, keyboard and mouse clicks and desk bumps?
[23:02] SPEAKER: You try to get gear that's quiet.
[23:03] SPEAKER: And if so, what do you get or do you just figure you can clean it all up in post-production?
[23:07] SPEAKER: Never clean anything in post-production.
[23:09] SPEAKER: That's look, I've been wasting a bunch of my Saturdays then.
[23:16] SPEAKER: Oh, really?
[23:17] SPEAKER: No, not, not as much as I used to.
[23:19] SPEAKER: I thought about getting into that on that last question of actually there was another
[23:23] SPEAKER: question in here.
[23:23] SPEAKER: I don't know if we'll take that one too.
[23:24] SPEAKER: Should we just do the whole podcast block?
[23:26] SPEAKER: We can do a podcast block.
[23:27] SPEAKER: Okay.
[23:27] SPEAKER: Let's, let's do this one and then we'll do the other one I was referring to.
[23:31] SPEAKER: Um, yeah.
[23:32] SPEAKER: Try to try not to have to clean anything in post-production.
[23:35] SPEAKER: Like the goal is to make everything clean enough that you don't have to do post-production.
[23:38] SPEAKER: Absolutely.
[23:39] SPEAKER: Cause it takes a really long time.
[23:41] SPEAKER: I mean, this probably is intuitive, but the problem with editing, cleaning up audio is
[23:46] SPEAKER: you can't see anything visually.
[23:47] SPEAKER: You can't look at a wave form and go like, Oh, that looks like a squeak or somebody bumping
[23:50] SPEAKER: their microphone.
[23:51] SPEAKER: I'll you know what I mean?
[23:52] SPEAKER: Like fixing audio, even just plain editing audio is so tedious because you just have
[23:57] SPEAKER: to don't do that.
[23:58] SPEAKER: God damn it.
[24:00] SPEAKER: I'm not cleaning that up.
[24:02] SPEAKER: No, no, leave it.
[24:02] SPEAKER: I was just my point is it's just annoying.
[24:05] SPEAKER: I know I'm joking, but, um, but yeah, like you can't, you can't just do a
[24:08] SPEAKER: quick survey visual survey of the wave form and pull stuff out.
[24:11] SPEAKER: Like you have to meticulously go through and listen to and re-listen to and it takes forever.
[24:17] SPEAKER: So I bought a mechanical keyboard with really quiet keys.
[24:23] SPEAKER: Well, I bought a mechanical keyboard and then put really quiet switches in it.
[24:26] SPEAKER: Um, I buy the right kind of key caps.
[24:28] SPEAKER: So they're quiet.
[24:28] SPEAKER: I put the keyboard on a piece of neoprene underneath so that the desk doesn't work as
[24:33] SPEAKER: a resonator and make it even louder.
[24:35] SPEAKER: I just, man, I've just talked about this on an Exlinger podcast.
[24:38] SPEAKER: I've got a roll of neoprene that I bought and didn't, that didn't work for the thing
[24:42] SPEAKER: I bought it for.
[24:42] SPEAKER: So now it's just sitting there.
[24:43] SPEAKER: Oh, there you go.
[24:44] SPEAKER: Maybe I should put it to use.
[24:45] SPEAKER: Yeah.
[24:46] SPEAKER: Um, I disassembled a mouse and put a quieter, quieter switches in it, but which wouldn't
[24:51] SPEAKER: quiet.
[24:51] SPEAKER: We talked about that on the tech pod, but one of them partly it was cause one of the
[24:54] SPEAKER: switches broken, but partly it was because I wanted quieter switches.
[24:57] SPEAKER: Um, you, uh, you don't drink things with ice in them.
[25:03] SPEAKER: Um, you don't make any weird mouth sounds if you can help it.
[25:07] SPEAKER: Yup.
[25:07] SPEAKER: You try to cut down, dampen your acoustics, try to cut down on audio bouncing off of walls
[25:12] SPEAKER: and stuff if you can.
[25:14] SPEAKER: Yeah.
[25:14] SPEAKER: That's the next thing I need to do is put foam up on the wall that I face now.
[25:17] SPEAKER: Cause I had it on the, on the old wall and I don't anymore.
[25:20] SPEAKER: And it's, yeah.
[25:21] SPEAKER: Also these, uh, these mics that we got are very directional, I guess is the term.
[25:25] SPEAKER: Yeah.
[25:25] SPEAKER: Like they don't, they don't pick up off-axis audio nearly as much as cheaper mics would.
[25:30] SPEAKER: Yeah.
[25:32] SPEAKER: Um, but, but yeah, the, um, desk bumps, so squeaky chairs, I've had to replace chairs
[25:39] SPEAKER: because they squeaked.
[25:40] SPEAKER: Yes.
[25:41] SPEAKER: Like that is, that is by my old Herman Miller reaction chairs that I had before the chair
[25:45] SPEAKER: I sit in now, uh, eventually they all develop a little bit of a wobble squeak after a long
[25:51] SPEAKER: time and there was no amount of lubing it that was able to fix the problem.
[25:54] SPEAKER: So for that, for that amount of money, they still developed.
[25:58] SPEAKER: Well, it was like 12 years old at that point.
[25:59] SPEAKER: Unacceptable.
[26:00] SPEAKER: Um, yeah, you know, I called them and they offered to replace it with a refurb under
[26:04] SPEAKER: warranty, but they couldn't guarantee that the refurb wouldn't squeak because like they,
[26:09] SPEAKER: in their eyes, a slightly squeaking, the amount of squeak was very negligible, but it still
[26:13] SPEAKER: came through.
[26:14] SPEAKER: That's fair.
[26:15] SPEAKER: I actually just realized something that I didn't even think to mention it cause I just,
[26:19] SPEAKER: I take it for granted, but like a, a mic, like a mic arm, a boom arm or don't put your
[26:24] SPEAKER: microphone on your desk is, is the point like something, something that elevates the mic
[26:30] SPEAKER: off the surface.
[26:31] SPEAKER: I technically use a microphone arm that is bolted to this desk, but it's like four feet
[26:38] SPEAKER: away.
[26:39] SPEAKER: Well, but, but also it's shock absorbed.
[26:41] SPEAKER: So the, so the, the motion of the desk is isolated from the motion of the microphone.
[26:45] SPEAKER: There is some shock absorption in this arm as well.
[26:47] SPEAKER: But like, if you really want to play it safe, you get a floor stand on the wall.
[26:51] SPEAKER: Yes.
[26:52] SPEAKER: Attach the mic to something that is not your desk.
[26:54] SPEAKER: If you really want to play it safe there, but like, but like your, the tripod stand
[26:58] SPEAKER: that most microphones come with is basically a resume turns your desk into a resonating
[27:03] SPEAKER: cavity for the microphone.
[27:04] SPEAKER: Yeah.
[27:05] SPEAKER: This is also why you put shock mounts.
[27:07] SPEAKER: The other thing is a pop filter.
[27:08] SPEAKER: So a pop filter helps you keep from making plosive sounds into your microphone.
[27:17] SPEAKER: See, you use one.
[27:17] SPEAKER: I use the one that's integrated in my mic.
[27:20] SPEAKER: It's probably fine.
[27:21] SPEAKER: I use it.
[27:22] SPEAKER: I only use this external one cause it looks cool.
[27:24] SPEAKER: Yeah.
[27:25] SPEAKER: See, that's why I use the spider mount for my mic.
[27:26] SPEAKER: Cause it looks cool.
[27:27] SPEAKER: Fair.
[27:28] SPEAKER: Fair.
[27:29] SPEAKER: Cause we all know the aesthetics are the most important thing.
[27:31] SPEAKER: It's shiny.
[27:32] SPEAKER: We've established.
[27:33] SPEAKER: It's true.
[27:33] SPEAKER: It's true.
[27:34] SPEAKER: Mine's beige.
[27:35] SPEAKER: I like the beige too.
[27:36] SPEAKER: All right.
[27:36] SPEAKER: At least you didn't get black.
[27:37] SPEAKER: Only bad people get black.
[27:39] SPEAKER: Yep.
[27:39] SPEAKER: And I won't tell Alex you said that.
[27:41] SPEAKER: He's it.
[27:42] SPEAKER: Look, I have a lot of respect for Alex for a lot of reasons, but not that.
[27:45] SPEAKER: He got a black re 20.
[27:47] SPEAKER: Okay.
[27:48] SPEAKER: Last podcast question from wedge for every hour of tech pod.
[27:51] SPEAKER: How many hours of behind the scenes work does it take?
[27:53] SPEAKER: How much time does it take to record an hour of podcasts?
[27:57] SPEAKER: About an hour.
[27:58] SPEAKER: On the back.
[27:59] SPEAKER: Oh, no way, man.
[28:00] SPEAKER: Are you serious?
[28:01] SPEAKER: No, I'm joking.
[28:02] SPEAKER: I'm joking.
[28:02] SPEAKER: Oh, okay.
[28:03] SPEAKER: Yeah.
[28:04] SPEAKER: So like on the prep end, that totally depends on the type of episode.
[28:07] SPEAKER: Yeah.
[28:07] SPEAKER: Q and A's are usually like an hour, probably two, two hours, an hour each for us to read
[28:12] SPEAKER: the questions and filter through the ones we want.
[28:14] SPEAKER: Yeah.
[28:15] SPEAKER: And then another hour of work on both ends for me.
[28:19] SPEAKER: And then you spend sometimes more or less, depending on how the, how the audio quality
[28:22] SPEAKER: is, how much you clean up.
[28:23] SPEAKER: I think I'll just go in sequence here.
[28:24] SPEAKER: So I'll get to that.
[28:25] SPEAKER: Cause it's the last step at the end.
[28:27] SPEAKER: But I would say like the topic episodes are probably the most prep intensive, would you
[28:33] SPEAKER: say?
[28:34] SPEAKER: Yeah.
[28:34] SPEAKER: Like that matter thread one I read, I did probably six hours a year, eight hours of
[28:38] SPEAKER: reading over the course of the week.
[28:39] SPEAKER: Those take a ton of research and like we, we write out detailed notes and everything.
[28:44] SPEAKER: Yeah.
[28:44] SPEAKER: Like, like our, our notes, our notes pages typically run from at least two pages and
[28:50] SPEAKER: sometimes up to six or eight, depending on how much, like, it really depends on how much,
[28:54] SPEAKER: how familiar we are with the topic and whether we're just putting, making notes to remind
[28:58] SPEAKER: us not to forget things or whether we're putting notes there so that it has the actual
[29:01] SPEAKER: information that we want for the podcast.
[29:02] SPEAKER: Yeah.
[29:04] SPEAKER: But they're usually pretty extensive.
[29:05] SPEAKER: I always feel we, I feel like like the notes are an unfortunate thing.
[29:09] SPEAKER: So if we had more time to spend on the show, I would clean them up and post them.
[29:12] SPEAKER: Cause they're kind of useful, but as is like, it's already taking a lot of time.
[29:16] SPEAKER: So I don't want to take another two hours to clean up the notes.
[29:19] SPEAKER: So they're postable anyway.
[29:20] SPEAKER: Plus all those obscenities that you write in there randomly.
[29:23] SPEAKER: Yeah. And the ethnic slurs.
[29:25] SPEAKER: Whoa.
[29:25] SPEAKER: Whoa.
[29:27] SPEAKER: I don't put ethnic slurs in the notes.
[29:30] SPEAKER: Goodness gracious.
[29:33] SPEAKER: The recording, surprisingly.
[29:35] SPEAKER: Okay.
[29:35] SPEAKER: Like on a morning like this where we've got other stuff, we've got actual work after
[29:39] SPEAKER: this to do.
[29:40] SPEAKER: Yeah.
[29:40] SPEAKER: We can get in and out in say 90 minutes for an episode that runs like 45 to an hour.
[29:45] SPEAKER: Yeah.
[29:46] SPEAKER: That's about right.
[29:47] SPEAKER: When we record on Saturdays, it easily will take like three hours total to record.
[29:52] SPEAKER: Oh, like, I don't know how that happens.
[29:54] SPEAKER: Like sometimes we say we chat, chat, chat.
[29:57] SPEAKER: I mean, some of it is lack of discipline.
[29:59] SPEAKER: Like we can get on the call and chat about other stuff.
[30:02] SPEAKER: A lot of it is like talking through the episode and planning out the flow and the structure
[30:07] SPEAKER: stuff like that.
[30:08] SPEAKER: Yeah.
[30:08] SPEAKER: For the more complicated topics, especially, especially it's useful to like talk through
[30:12] SPEAKER: the structure.
[30:13] SPEAKER: Yeah.
[30:13] SPEAKER: Actually, this is like the kind of a slight digression, but like on the subject of discipline
[30:18] SPEAKER: in terms of just like showing up recording and leaving, like when we're working remotely,
[30:22] SPEAKER: it turns out that like getting on video calls to either record stuff or have a meeting is
[30:27] SPEAKER: literally the only time you interact with your coworkers.
[30:31] SPEAKER: Yeah.
[30:31] SPEAKER: So we have that at my full-time job too.
[30:33] SPEAKER: Right.
[30:33] SPEAKER: My day job too.
[30:34] SPEAKER: Exactly.
[30:35] SPEAKER: Basically, I think we tend to just like gab a little more when we should be recording
[30:40] SPEAKER: just because like there is no water cooler anymore.
[30:42] SPEAKER: You know what I mean?
[30:43] SPEAKER: Well, yeah, we like institutionalized a period, a short period at the start of meeting of
[30:49] SPEAKER: like our daily standup meeting where we kind of just talk about whatever we want to talk
[30:53] SPEAKER: about while people are filing in, which is nice.
[30:55] SPEAKER: That's smart probably.
[30:57] SPEAKER: Yeah.
[30:57] SPEAKER: Because yeah, like just lacking that like basic kind of passive social interaction that
[31:03] SPEAKER: you get of just being around people all day.
[31:06] SPEAKER: It's nice to maintain a human connection with your coworkers.
[31:09] SPEAKER: Yes.
[31:10] SPEAKER: Anyway, you take the audio when we're done and sync it up against the, our highly sophisticated
[31:16] SPEAKER: patented sync technology.
[31:19] SPEAKER: Thank you.
[31:23] SPEAKER: I sync that up in Audition and I use Audition just because when we started doing the podcast,
[31:27] SPEAKER: Audacity didn't preview the, like the audio waves that you see don't line up necessarily
[31:33] SPEAKER: with the audio.
[31:34] SPEAKER: In the old days of Audacity, they do now, I believe.
[31:38] SPEAKER: So like I line up the spikes basically from the beeps.
[31:42] SPEAKER: And then I export stems.
[31:46] SPEAKER: Well, I do some filtering.
[31:47] SPEAKER: So I bring, I level everybody out.
[31:50] SPEAKER: I do noise gates on you.
[31:52] SPEAKER: I do that in hardware on me.
[31:53] SPEAKER: So I don't need to do that and do some dynamics passes and stuff like that because Audition
[31:57] SPEAKER: has, it turns out Adobe has a lot of smart engineers doing audio processing stuff.
[32:02] SPEAKER: And then I jam that out and as a bunch of wave files and send it over to you and you
[32:08] SPEAKER: put the music in because you are very good at putting the music so that the beats hit
[32:12] SPEAKER: at the right time.
[32:12] SPEAKER: Cause I don't have an ear for that.
[32:13] SPEAKER: Yeah.
[32:14] SPEAKER: Yeah.
[32:14] SPEAKER: There's a lot more there than just putting music in.
[32:16] SPEAKER: I mean, I know of course.
[32:17] SPEAKER: So you send, you, you give me two waves.
[32:19] SPEAKER: One of you, one of me and I had a guest sometimes.
[32:22] SPEAKER: Yeah.
[32:23] SPEAKER: Yeah.
[32:23] SPEAKER: So gotta like trim up all the ins and outs and, and line up music and stuff like that.
[32:28] SPEAKER: But like the real, the real time sink there is how much time am I going to spend going
[32:32] SPEAKER: through like cleaning up talk overs and long pauses and the ums and stuff like that.
[32:38] SPEAKER: Like I've, I've easily spent three hours doing nothing but going through and I don't do that
[32:43] SPEAKER: as much anymore.
[32:44] SPEAKER: Oh, you like it's, that is an infinite hole.
[32:48] SPEAKER: Yes.
[32:48] SPEAKER: That's exactly the problem is that you could spend, you could spend six hours per episode
[32:52] SPEAKER: making it sound absolutely perfect.
[32:54] SPEAKER: Yeah.
[32:55] SPEAKER: And then, and then completely lose your mind in the process.
[32:58] SPEAKER: Well, so then the process for the tech pod and the FOS pod are a little bit different.
[33:02] SPEAKER: Like the FOS pod, we have more help.
[33:05] SPEAKER: So Matt, our yeah, Matt, our producer and Sabrina, our editor do like Sabrina to goes
[33:10] SPEAKER: through and does all the ums and the ahs and rearranges things.
[33:13] SPEAKER: And Matt does kind of the initial research pass.
[33:20] SPEAKER: So then we can dig in, like he'll, he'll go and find all the good interviews that people
[33:24] SPEAKER: have done and it pulls out highlights from some of the interviews and listens to the
[33:28] SPEAKER: podcast and does all that stuff.
[33:30] SPEAKER: And then a gives us places that we can go if we want to know more and kind of gives
[33:35] SPEAKER: us a basic skeleton for the questions we want to answer the conversation we want to have.
[33:39] SPEAKER: And then with that show, we do the interview.
[33:45] SPEAKER: Then we listen to the interview and kind of rearrange stuff if it needs to, because often
[33:52] SPEAKER: we'll kind of meander during those conversations.
[33:55] SPEAKER: And Sabrina does the, does a couple edits along there to get it first to a structure
[33:59] SPEAKER: that we want and then to a runtime that we want.
[34:03] SPEAKER: And then once that's all done, we record the intro and the outro and any interstitial
[34:07] SPEAKER: segments that we need to explain like concepts that we don't explain well during the interview.
[34:11] SPEAKER: And that's, that's where then it gets published like anything else.
[34:15] SPEAKER: Yeah.
[34:15] SPEAKER: And I do all that stuff like the writing, tagging and all that.
[34:20] SPEAKER: Tagging, coding and tagging, naming, episode naming, writing decks, getting show art together.
[34:25] SPEAKER: Yeah.
[34:25] SPEAKER: Doing all the CMS backend stuff.
[34:27] SPEAKER: Like once you hand files off to me for the tech pod, like I would say like absolute
[34:31] SPEAKER: minimum an hour to 90 minutes to get it totally listenable and put into the system and all
[34:36] SPEAKER: that stuff written and everything like more like two to three hours.
[34:40] SPEAKER: If I actually go through and like the weeks that I don't do that, I feel terrible about
[34:44] SPEAKER: it.
[34:44] SPEAKER: Feel irresponsible.
[34:47] SPEAKER: We should get Sabrina to just do that too.
[34:50] SPEAKER: I could just slap, slap these source files in, put the music on and spit it out in 20,
[34:56] SPEAKER: 30 minutes.
[34:57] SPEAKER: But I just can't, I can't resist at least scrubbing through.
[35:01] SPEAKER: We have latency.
[35:01] SPEAKER: That's the biggest problem is that being remote and I hear it all the time and it makes me
[35:06] SPEAKER: feel really self-conscious because like, like one thing you may notice is we'll do a lot
[35:09] SPEAKER: of things where we begin the, we begin a sentence and say the same couple of words like three
[35:14] SPEAKER: times in a row.
[35:15] SPEAKER: Yeah.
[35:15] SPEAKER: I usually go through into a past taking those out too, just so you know.
[35:18] SPEAKER: So those, those, those, those aren't just us stumbling over our words.
[35:21] SPEAKER: Like that's actually like in the video call there's latency and it actually means like,
[35:25] SPEAKER: Oh, you started saying something at the same time I did.
[35:27] SPEAKER: You know what I mean?
[35:28] SPEAKER: Yeah.
[35:28] SPEAKER: And we cut one out, but not the other maybe or whatever.
[35:31] SPEAKER: Like you second guess yourself when you hear somebody else start talking when you're trying
[35:34] SPEAKER: to talk, you know what I mean?
[35:35] SPEAKER: Yeah.
[35:35] SPEAKER: And you just end up kind of stumbling over stuff.
[35:37] SPEAKER: There, there's a lot of stuff in there that is, that is an artifact of, of recording remotely,
[35:41] SPEAKER: not just not being able to talk well.
[35:44] SPEAKER: Yeah.
[35:44] SPEAKER: And, and leaving that stuff in makes me feel awful, but.
[35:48] SPEAKER: Well, but sometimes it's harder to like, sometimes you end up with something that sounds more
[35:52] SPEAKER: unnatural by cutting around it is what I end up with.
[35:54] SPEAKER: I usually go through and scan the waveforms for places that we're talking over each other
[35:58] SPEAKER: and cut them, cut the obvious ones out.
[36:00] SPEAKER: That's what I've started doing is just scrolling through also and just anywhere that you see
[36:03] SPEAKER: audio overlap is a good cue.
[36:05] SPEAKER: Yeah.
[36:05] SPEAKER: So, so take a listen and see if you can clean some stuff up.
[36:08] SPEAKER: Cause like you could easily, I could easily spend my whole Saturday afternoon doing that
[36:12] SPEAKER: if I didn't resist the urge.
[36:13] SPEAKER: I was going to say then the last thing is all the posting and stuff.
[36:17] SPEAKER: So we post stuff like some of the posting happens automatically, but letting people
[36:20] SPEAKER: know about patron episodes and all that stuff happens manually and we tweet to stir up interest
[36:26] SPEAKER: and generate excerpts and all that stuff.
[36:28] SPEAKER: So it's a lot.
[36:29] SPEAKER: Yeah.
[36:30] SPEAKER: Yeah.
[36:31] SPEAKER: That's something people have never understood about this line of work is that there is
[36:35] SPEAKER: way, way more work to make it happen than what you see.
[36:38] SPEAKER: Yeah.
[36:38] SPEAKER: It's not just sitting, well, I mean, sometimes it's sitting down for the microphone.
[36:41] SPEAKER: Like sometimes you sit down for the microphone and talk about something for an hour, but
[36:45] SPEAKER: that's because you have knowledge that is predates the podcast and right.
[36:49] SPEAKER: And probably also other people doing the heavy lifting.
[36:52] SPEAKER: Yeah.
[36:53] SPEAKER: Of, of getting it ready to post.
[36:55] SPEAKER: Yeah, exactly.
[36:56] SPEAKER: All right.
[36:57] SPEAKER: That's enough about podcasting.
[36:58] SPEAKER: Yeah.
[36:58] SPEAKER: That's a lot of podcasts.
[36:59] SPEAKER: The podcast block is over.
[37:01] SPEAKER: You want to talk about Git?
[37:03] SPEAKER: This is an easy one.
[37:05] SPEAKER: I saw that one.
[37:05] SPEAKER: I don't know.
[37:08] SPEAKER: I used Git all the time.
[37:08] SPEAKER: How much I have to say about it.
[37:10] SPEAKER: Also, there may be a lot of cake batter questions in here if we just go all willy nilly here.
[37:15] SPEAKER: Oh, okay.
[37:16] SPEAKER: Nevermind then.
[37:16] SPEAKER: Oh, it's too late.
[37:17] SPEAKER: Oh, how often do you as non-programmers use Git?
[37:20] SPEAKER: Would you want this interaction to be more or less frequent says cake batter.
[37:23] SPEAKER: I used Git two days ago, I think was last time.
[37:26] SPEAKER: I, I, I store my notes, my, my personal, like, like I write notes in flat text files and
[37:33] SPEAKER: really get them in a folder to pages of info.
[37:38] SPEAKER: Get info.
[37:39] SPEAKER: No.
[37:39] SPEAKER: What's the, what's the, what's their, what's their document thing?
[37:43] SPEAKER: They who?
[37:44] SPEAKER: Git, GitHub.
[37:45] SPEAKER: I put them on GitHub in a private repo where they're all stored and searchable and online
[37:51] SPEAKER: and I can track changes and search them on the web and it's very good.
[37:55] SPEAKER: It's like my own version of simple, simple writer, simple, simple page, simple note.
[38:00] SPEAKER: Yeah. I also use a get to host our press kit install for straight Monday.
[38:06] SPEAKER: So get pages is what I use.
[38:08] SPEAKER: Sorry.
[38:08] SPEAKER: It took me a minute.
[38:09] SPEAKER: Yeah.
[38:09] SPEAKER: Yeah.
[38:10] SPEAKER: Yeah.
[38:10] SPEAKER: I wanted to clarify which service you were talking about because there are certainly,
[38:14] SPEAKER: you know, GitLab is big now like source hut.
[38:17] SPEAKER: There are a lot of other GitHub competitors out there now.
[38:20] SPEAKER: So I really like this.
[38:23] SPEAKER: I do not like using Git.
[38:25] SPEAKER: I would like to do the same thing with some other service that is not Git because that's
[38:29] SPEAKER: how GitHub came about.
[38:30] SPEAKER: Right.
[38:31] SPEAKER: Yes.
[38:31] SPEAKER: Git is like very powerful and not very friendly.
[38:34] SPEAKER: Yeah, that is exactly right.
[38:36] SPEAKER: I've been meaning to store my dot files remotely.
[38:40] SPEAKER: Well, that's a good idea.
[38:41] SPEAKER: I've got like looking around the house here between physical Unix E-boxes and containers
[38:49] SPEAKER: kind of virtual Unix E-boxes inside of those.
[38:51] SPEAKER: There's probably, God, I don't know, 12, 15 Linux and BSD machines around this house.
[38:57] SPEAKER: Wow.
[38:58] SPEAKER: And it would really be nice if I could just like store one .bashrc, for example, and just
[39:04] SPEAKER: have it pull that down everywhere.
[39:07] SPEAKER: Yeah.
[39:08] SPEAKER: But I haven't actually gotten around to figuring that stuff out yet.
[39:11] SPEAKER: I like, I want to save my OBS configurations like that because Git could do that because
[39:16] SPEAKER: it can hold all the assets and everything.
[39:18] SPEAKER: But anyway.
[39:19] SPEAKER: I actually just had to nuke my OBS install this week.
[39:21] SPEAKER: Oh God.
[39:22] SPEAKER: Finally that I've been using since before the pandemic started.
[39:25] SPEAKER: It had gotten like just I have hives.
[39:27] SPEAKER: Like what you mean having to redo everything?
[39:30] SPEAKER: Yeah.
[39:30] SPEAKER: Like sometimes I feel like the idea of cruft and software is overblown, but in this case
[39:34] SPEAKER: it was a hundred percent accurate.
[39:36] SPEAKER: Like it had become essentially unusable, like incredibly unstable.
[39:40] SPEAKER: It would not exit.
[39:41] SPEAKER: It would never exit.
[39:42] SPEAKER: Like this is just a random example, but like every time I quit it, it would hang and I
[39:45] SPEAKER: would have to force quit it.
[39:46] SPEAKER: How, how many scenes do you have a bunch of scenes and stuff?
[39:48] SPEAKER: Quite a few scenes.
[39:49] SPEAKER: Also some of the assets that some of those scenes were pointing at lived on my NAS that
[39:55] SPEAKER: has been unhooked for two months.
[39:56] SPEAKER: Oh, you can't ever put OBS assets toward a NAS.
[39:58] SPEAKER: That's where that's a hundred percent your problem.
[40:00] SPEAKER: Oh no, it works fine when, but when the assets are not there, I don't know if, I don't know
[40:04] SPEAKER: if OBS like it, you know, it throws a warning when you launch it like, Hey, these images
[40:08] SPEAKER: are not there anymore, but I don't know if that causes problems down the line.
[40:11] SPEAKER: It depends on what the assets are.
[40:13] SPEAKER: So because I used to do this, I save a video assets in like a VLC playlist module will
[40:19] SPEAKER: hang OBS without an error.
[40:21] SPEAKER: Cause it's a Mo it's a plugin, the VLC playlist thing is a plugin or something and not a core
[40:26] SPEAKER: part of the OBS.
[40:28] SPEAKER: So it'll just stall while it's waiting for that plugin to load, which is what the problem
[40:32] SPEAKER: I had when I ran stuff off my NAS.
[40:33] SPEAKER: Oh, the problem, the real problem started when I tried to install stream effects a few
[40:37] SPEAKER: months ago, which is weird because a ton of people use stream effects and seems to be
[40:41] SPEAKER: fine for them.
[40:42] SPEAKER: What's stream effects.
[40:43] SPEAKER: It's, it's a pretty popular suite of OBS stuff.
[40:46] SPEAKER: It gives you like real time blur and like transparency and stuff.
[40:49] SPEAKER: You can like, you can do like more advanced overlays.
[40:52] SPEAKER: I can't believe there's no transparency built into OBS.
[40:54] SPEAKER: So does that mean you can do well, there is, but you have to use alpha channels or green
[40:58] SPEAKER: or key stuff out, right?
[40:59] SPEAKER: I mean like real time on the GPU, not like having to make like a, make a mask manually
[41:05] SPEAKER: or something like that.
[41:06] SPEAKER: Can you does that mean you can do like vertical video with the blur blur vertical video in
[41:12] SPEAKER: the background thing?
[41:13] SPEAKER: I think that's exactly what I installed it for and wanted to do.
[41:16] SPEAKER: That's fantastic.
[41:16] SPEAKER: That is, that is in fact exactly what I installed it for and wanted to do, but like it just
[41:20] SPEAKER: never worked for me.
[41:21] SPEAKER: It also might be that your computer is too slow.
[41:23] SPEAKER: What I, what I mean is it never showed up.
[41:24] SPEAKER: Like I installed the plugin and the menu, the stream effects menu literally did not
[41:28] SPEAKER: appear in the interface.
[41:30] SPEAKER: I saw another good OBS plugin the other day.
[41:33] SPEAKER: It lets you do smooth move transitions between scenes.
[41:38] SPEAKER: So you set up two scenes with the more or less the same stuff and you change the size of
[41:42] SPEAKER: one element inside it and then you transition between the two and it just dynamically moves
[41:46] SPEAKER: the small thing to the big thing, the big thing to the small thing.
[41:49] SPEAKER: It's very happy making.
[41:50] SPEAKER: That's pretty good.
[41:51] SPEAKER: Yeah.
[41:51] SPEAKER: Uh, OBS 28 seems pretty good.
[41:54] SPEAKER: Are you on the beta?
[41:55] SPEAKER: No, I'm not using it, but I, I checked out all of the new stuff that is coming to it
[41:59] SPEAKER: and it's some good stuff.
[42:02] SPEAKER: I am excited about it.
[42:03] SPEAKER: I I'm, I'm ready.
[42:04] SPEAKER: They're finally adding native application level audio capture.
[42:08] SPEAKER: Like there's a good plugin for that out there that just works generally.
[42:12] SPEAKER: I haven't had a huge issue with it, but they're finally building it into the application
[42:15] SPEAKER: itself.
[42:15] SPEAKER: You can just say, Hey, capture only the audio from this game or this browser window.
[42:20] SPEAKER: That's cool.
[42:20] SPEAKER: Yeah.
[42:21] SPEAKER: It's good stuff.
[42:22] SPEAKER: I'm hopeful that you'll have the ability to export your setup.
[42:25] SPEAKER: I think Jim talked about that, right?
[42:26] SPEAKER: He talked about it.
[42:27] SPEAKER: He said it's in the pipeline, but he didn't, he didn't give a timeline for it.
[42:29] SPEAKER: I did not see that on the feature list for 28, sadly.
[42:34] SPEAKER: How about a question from Narfinger?
[42:37] SPEAKER: Do you think we should replace version numbers of software with the Ubuntu scheme of year
[42:42] SPEAKER: dot month or the get hash of the commit?
[42:44] SPEAKER: Oh, I like your dot month.
[42:46] SPEAKER: The get hash.
[42:47] SPEAKER: Absolutely not.
[42:47] SPEAKER: That's for that's for maniacs.
[42:49] SPEAKER: That's no, no way.
[42:52] SPEAKER: What he's talking about is, so I think I like the Ubuntu scheme, but I think it only really
[42:56] SPEAKER: makes sense for stuff that comes out on a regular cadence, like a predictable one.
[43:01] SPEAKER: Yeah.
[43:01] SPEAKER: Cause it's always like 0 8 0 4 0 8 0 10 0 8 1 0.
[43:05] SPEAKER: Yeah.
[43:05] SPEAKER: So Ubuntu, Ubuntu ships two manual versions, one in April and one in October.
[43:09] SPEAKER: So it's very easy to say like, Oh, 20 dot 0 4 that's the one that came out in April,
[43:14] SPEAKER: 2020.
[43:15] SPEAKER: Yeah.
[43:15] SPEAKER: What is it?
[43:15] SPEAKER: Every third one is a every, every second, every other year is an LTS.
[43:20] SPEAKER: Is an LTS.
[43:21] SPEAKER: So every, every, every, every even numbered April is an LTS release.
[43:25] SPEAKER: So 2204 that just came out is LTS.
[43:28] SPEAKER: LTS means long-term support, which means they'll support it for 18 months or three years or
[43:32] SPEAKER: something.
[43:32] SPEAKER: I can't remember.
[43:33] SPEAKER: I think Ubuntu LTS is pretty long.
[43:35] SPEAKER: It's Debian LTS.
[43:37] SPEAKER: It's really long.
[43:39] SPEAKER: Yeah.
[43:39] SPEAKER: Debian is funny and weird about that stuff because they just use terms.
[43:42] SPEAKER: There's so busy badger or whatever.
[43:45] SPEAKER: No, no, no.
[43:46] SPEAKER: Well, those are the names.
[43:47] SPEAKER: Those are no, no, the, the adjective animal thing is an Ubuntu thing.
[43:51] SPEAKER: So it's like, yeah, buzz, buzzy, buzzy buzzer.
[43:54] SPEAKER: I don't know.
[43:56] SPEAKER: Debian names after toy story, story characters.
[43:58] SPEAKER: So they're currently on bull's eye.
[44:00] SPEAKER: The next one is bookworm.
[44:02] SPEAKER: That's why, that's why you had Debian Jesse for a while.
[44:06] SPEAKER: What was, what did Debian used to be?
[44:08] SPEAKER: And Debian stretch, they've been doing the toy story thing practically from the beginning.
[44:12] SPEAKER: They also use numbers like, like 10 was Buster.
[44:14] SPEAKER: Debian 10 was Buster.
[44:15] SPEAKER: Debian 11 is bullseye.
[44:17] SPEAKER: 12 will be bookworm.
[44:20] SPEAKER: I just use the numbers.
[44:21] SPEAKER: Anyway, the thing I was gonna say though on their support stuff is they just use terms.
[44:24] SPEAKER: Like the current release is stable.
[44:26] SPEAKER: The next one is testing.
[44:28] SPEAKER: The one after that, that is super alpha is Sid.
[44:31] SPEAKER: And then when you go in the other direction, like stable becomes old stable.
[44:36] SPEAKER: So the previous release is old stable two releases ago is old, old stable.
[44:40] SPEAKER: I love old stable.
[44:42] SPEAKER: I like to stick on old, old stable.
[44:44] SPEAKER: It's look, it's as stable as it gets.
[44:46] SPEAKER: I believe that's right.
[44:47] SPEAKER: Yes.
[44:47] SPEAKER: That's correct.
[44:48] SPEAKER: Old, old stable.
[44:50] SPEAKER: All right.
[44:50] SPEAKER: So Linux is a thing.
[44:55] SPEAKER: I like the numbers.
[44:56] SPEAKER: I like the, I like the year month.
[44:58] SPEAKER: I like the data thing.
[44:59] SPEAKER: So Microsoft also does it for windows semi-annual updates.
[45:02] SPEAKER: You may have noticed like 2, 2, 1, 0, 2, 21, like, like 20.
[45:05] SPEAKER: Like generally it'll be like 22 H one now for half the first half.
[45:09] SPEAKER: So like 22 H one just came out a few months ago.
[45:13] SPEAKER: Yep.
[45:13] SPEAKER: Again, though, I feel like that only really makes sense when everything is on a predictable
[45:17] SPEAKER: schedule like that, because otherwise like there's no frame of reference for how old
[45:22] SPEAKER: or how many versions there have been since something.
[45:24] SPEAKER: If you don't know that they came, kept coming out, you know what I mean?
[45:27] SPEAKER: Yeah.
[45:27] SPEAKER: Like if, you know, if 1904 was your last rule is a release that I'm looking at.
[45:33] SPEAKER: Like, I don't know that there have been more since then, unless I know that they're coming
[45:36] SPEAKER: out every six months.
[45:37] SPEAKER: God, that would be like 118 years old if it was 1904.
[45:40] SPEAKER: The, the I, I, so I have to say I set up some Docker containers this weekend and the way
[45:47] SPEAKER: you can pull different Docker containers from the repo on my NAS.
[45:52] SPEAKER: Like you can, you can subscribe to basically a channel of container and you can get latest
[45:56] SPEAKER: or like I was installing Plex at a Docker container and you can get the Plex pass version
[46:00] SPEAKER: and it just, you know, when you update the Docker container, it just, it just does its
[46:04] SPEAKER: thing and replaces what you have with the new one.
[46:06] SPEAKER: And theoretically it should just work.
[46:08] SPEAKER: It's, it's, it's, it's, I'm, I'm kind of, I'm starting to get into Docker, Brad.
[46:12] SPEAKER: That's, that's the, yeah, I hear good things.
[46:15] SPEAKER: It seems fine.
[46:17] SPEAKER: Yeah.
[46:17] SPEAKER: I still like just an iterated version number for something that is just released haphazardly
[46:21] SPEAKER: because it gives you more information about how many releases there have been.
[46:24] SPEAKER: I like it when big companies say, Hey, we're going to do this.
[46:27] SPEAKER: We're never going to change numbering schemes again.
[46:29] SPEAKER: Oh yeah, that's good.
[46:30] SPEAKER: And then like three, five years later, they changed numbering schemes again.
[46:33] SPEAKER: Windows 10 is the last one is ever.
[46:35] SPEAKER: Oh, S 10 is the last OS 10 ever.
[46:37] SPEAKER: They made it 20 years on that one.
[46:38] SPEAKER: I'll give them that.
[46:39] SPEAKER: And I bet Steve jobs never would have let this happen.
[46:43] SPEAKER: It would still be OS 10.
[46:47] SPEAKER: 10 is the perfect number.
[46:48] SPEAKER: Um, X I is a much shittier Roman numeral.
[46:51] SPEAKER: The last thing I'll mention here is that since I am, I'm on the, like literally probably
[46:55] SPEAKER: this weekend going to just finally slap a vanilla Linux install on my NAS.
[47:01] SPEAKER: Uh, I've been in kernel land a bit and realized how goofy and arbitrary Linux kernel version
[47:07] SPEAKER: numbers are.
[47:08] SPEAKER: Oh yeah.
[47:09] SPEAKER: Like 5.1, nine of the Linux kernel, I think just came out or is about to, and like they
[47:15] SPEAKER: were working on 5.2.
[47:17] SPEAKER: Oh, and then Linus just decided, actually, this is going to be 6.0 instead.
[47:20] SPEAKER: Like flat out, he flat out just said like, I don't like version numbers to get too big.
[47:24] SPEAKER: This is going to be six.
[47:25] SPEAKER: Like that's kind of, we usually get up to about 19 or 20 and then it's like, ah, it's
[47:28] SPEAKER: probably time to roll over to the next one.
[47:30] SPEAKER: So in the old days, it used to be that the version, like in the old, old days, the version
[47:35] SPEAKER: number would increment.
[47:36] SPEAKER: The major version number would increment when something major happened, like a hardware,
[47:39] SPEAKER: usually tied to hardware support or some new instructions or something like that.
[47:43] SPEAKER: So it's nice that he's, he's lightened up in his older age.
[47:46] SPEAKER: Yeah.
[47:46] SPEAKER: That's, that's how the ARIA line was reading, put it at least that this was arbitrary and
[47:51] SPEAKER: like, Hey, Linux six, here we go.
[47:54] SPEAKER: It's time.
[47:55] SPEAKER: Look, he's got to, he's got to get to 11.
[47:57] SPEAKER: So these on par with the other OSs.
[47:59] SPEAKER: That's that's yeah.
[48:01] SPEAKER: Indeed.
[48:02] SPEAKER: Pick up the pace Linux.
[48:03] SPEAKER: Oh gosh.
[48:04] SPEAKER: We had another podcast question that we didn't ask from X amp Rocky.
[48:07] SPEAKER: Well, okay.
[48:08] SPEAKER: We'll reopen the podcast door one more time.
[48:10] SPEAKER: And the Y thread matters episode.
[48:12] SPEAKER: You mentioned that these days you often have topics that can't fill the full length of
[48:15] SPEAKER: an episode.
[48:15] SPEAKER: My question is how do you know when a topic can't fill a full hour?
[48:21] SPEAKER: Usually we do a bunch of research and then we get to a point where like, I don't think
[48:24] SPEAKER: I can talk about this for 45 minutes or an hour.
[48:26] SPEAKER: Yeah.
[48:27] SPEAKER: It's, it's really just kind of a gut feeling.
[48:29] SPEAKER: Like if, if we only get a page of notes and we've been reading a bunch of stuff about
[48:33] SPEAKER: it and we're like, this, this seems kind of boring.
[48:35] SPEAKER: Yeah.
[48:37] SPEAKER: We ha we haven't killed, killed too many of those.
[48:39] SPEAKER: We we've, we've dumped some of them into like a potpourri episode.
[48:42] SPEAKER: We'll do two or three things at a time.
[48:45] SPEAKER: But I don't think we've actually killed anything at this point.
[48:47] SPEAKER: Have we?
[48:48] SPEAKER: I don't think so.
[48:49] SPEAKER: We've done a lot of topics.
[48:50] SPEAKER: It turns out after 160, 150 episodes, it's a lot of podcasts.
[48:55] SPEAKER: Quite literally about three episodes or about three years now.
[48:58] SPEAKER: Yeah.
[48:59] SPEAKER: We burned through a lot of the obvious topics, although not, certainly not all of them because
[49:02] SPEAKER: like we're going to do a Bluetooth episode and it's like, how did we not do that already?
[49:06] SPEAKER: I think we looked at it and we're like, Oh God, I don't want to talk about this.
[49:08] SPEAKER: This is really complicated.
[49:09] SPEAKER: Cause we really need to do it with that.
[49:10] SPEAKER: What a Bluetooth episode means is we really need to do a Bluetooth episode.
[49:13] SPEAKER: And then we also need to do a Bluetooth audio episode because it's complex enough to warrant
[49:16] SPEAKER: its whole own thing.
[49:18] SPEAKER: Yes.
[49:20] SPEAKER: And there's some stuff that's just like obvious trash fires and you want to avoid because
[49:23] SPEAKER: it's just going to make people yell at you on the internet.
[49:25] SPEAKER: So yeah, indeed.
[49:29] SPEAKER: How about a question from Grub in regards to the food story episode do you know anything
[49:39] SPEAKER: about Jim Henson company's live performance capture stuff?
[49:42] SPEAKER: There are parts of that show where a handheld camera is following the animated characters
[49:46] SPEAKER: around and it looked so much like the food shit stuff.
[49:50] SPEAKER: Yeah, they do, there are a lot of ways to do hand fake handheld cameras now that are
[49:55] SPEAKER: real good.
[49:55] SPEAKER: You can even buy plugins for stuff that will, for your animation pipelines, you can draw
[50:00] SPEAKER: the lines in your 3d spaces.
[50:02] SPEAKER: There's all sorts of, there's, there's even like motion tracked version.
[50:04] SPEAKER: So if this is a motion track show, you can put the, like w we did a handheld camera with
[50:09] SPEAKER: foo that I don't think it was ever in anything that was public, but it's like, it was shoulder
[50:14] SPEAKER: mounted.
[50:14] SPEAKER: We, well, we have, we have straight handheld, we had shoulder mounted and you could carry
[50:18] SPEAKER: it around and you'd get like camera bounce.
[50:20] SPEAKER: We could smooth it out just like you do in a video game.
[50:22] SPEAKER: So you'd have like, like, you know, basically gyro, like super duper gyro stabilization
[50:28] SPEAKER: slash the best steady cam operator in the world.
[50:32] SPEAKER: Because it's all just software.
[50:34] SPEAKER: But the Henson stuff, Henson's always been at the forefront of this.
[50:37] SPEAKER: They did like for first they did early animated faces with the hand puppet rigs so that they
[50:43] SPEAKER: could take their puppeteers and use the skill that they have in manipulating puppets and
[50:46] SPEAKER: use that for CG.
[50:48] SPEAKER: They'd build like cool armatures to control that stuff.
[50:51] SPEAKER: I want to say they did, wasn't it Henson that did the Teenage Mutant Ninja Turtle faces,
[50:55] SPEAKER: the animatronic ones for the nineties movies?
[50:58] SPEAKER: That sounds right.
[51:00] SPEAKER: Like, like it's like, there's a, there's a long history of technology and, and a friend
[51:05] SPEAKER: of mine who's a puppeteer offered to introduce me there.
[51:08] SPEAKER: And we just never, like, I never managed to make it happen.
[51:10] SPEAKER: Cause we, like when we were looking at different ways of doing face capture or face animation,
[51:18] SPEAKER: my puppeteer friend of mine was like, you should just have puppeteers do this cause
[51:21] SPEAKER: they'll do a better job than like putting people in front of an iPhone and having them
[51:24] SPEAKER: talking to the iPhone.
[51:26] SPEAKER: But the cost turns out there aren't that many really good puppeteers in the world.
[51:32] SPEAKER: And B the cost of adding a third person to the cost and complexity of adding a third
[51:38] SPEAKER: person to the production, instead of having just a face actor and a voice actor and a
[51:41] SPEAKER: body actor face slash voice and body actor was such that it wasn't.
[51:47] SPEAKER: I couldn't, I didn't, I didn't think it was worth investing in.
[51:50] SPEAKER: No.
[51:51] SPEAKER: It was too scary.
[51:52] SPEAKER: But the thing you just mentioned about like kind of physical interfaces for non-physical
[51:57] SPEAKER: effects reminds me of something on that ILM document and documentary on Disney plus that
[52:01] SPEAKER: I've been watching, which I really need to go watch.
[52:03] SPEAKER: I've got to watch it.
[52:03] SPEAKER: Yeah.
[52:05] SPEAKER: On poltergeist.
[52:07] SPEAKER: I have not seen poltergeist, but I saw this sequence.
[52:09] SPEAKER: I guess there's some kind of like, there's a shot of like some gigantic orifice.
[52:13] SPEAKER: Do you know what I'm talking about?
[52:14] SPEAKER: That undulates.
[52:15] SPEAKER: No, I've never seen poltergeist.
[52:16] SPEAKER: It was poltergeist was a PG movie.
[52:19] SPEAKER: I think it wasn't always at house.
[52:20] SPEAKER: That was one of those movies was shockingly PG rated.
[52:24] SPEAKER: Poltergeist was let's see.
[52:27] SPEAKER: Boy, they don't really a PG.
[52:28] SPEAKER: Yes.
[52:29] SPEAKER: Poltergeist is in fact PG.
[52:32] SPEAKER: Anyway, it's a gigantic orifice.
[52:34] SPEAKER: It's like a giant colon or something that the camera flies into.
[52:38] SPEAKER: Anyway, different segments of it undulate.
[52:40] SPEAKER: Like they could make it like throb and pulse in different places.
[52:43] SPEAKER: Just what I want from my orifices.
[52:44] SPEAKER: A horse who doesn't want a throbbing orifice.
[52:47] SPEAKER: But they hooked that up to like a tiny little segment of a piano.
[52:50] SPEAKER: I don't know if, I don't know if it was like the eight or 10 keys or something, but it
[52:53] SPEAKER: really just looked like, you know, if you sliced the end of a piano off and hooked the
[52:59] SPEAKER: different segments of this orifice up to the different keys on this thing.
[53:02] SPEAKER: And then Spielberg, when he was in the shop saw it and he was like, Oh my God, I want
[53:05] SPEAKER: to play that thing.
[53:07] SPEAKER: Literally played this giant throbbing colon with a tiny segment of a piano.
[53:14] SPEAKER: So interface is a lot of it's like how you control that stuff is often the harder part
[53:18] SPEAKER: of the, like it's often harder to make something do something than it is figuring out how to
[53:22] SPEAKER: control it in the right way.
[53:23] SPEAKER: Yeah.
[53:24] SPEAKER: One other quick thing that I was reading, I didn't realize that this is like the other
[53:27] SPEAKER: direction of what you were talking about.
[53:29] SPEAKER: Like they add fake camera shake to footage now.
[53:31] SPEAKER: Oh yeah.
[53:32] SPEAKER: There's plugins for that in Premiere or After Effects rather.
[53:36] SPEAKER: I was reading that it's like basically automated at this point.
[53:38] SPEAKER: That in fact, I want to say that some visual effects artists had said they can like literally
[53:43] SPEAKER: recognize the fake camera shake patterns in stuff that they watch because it's like all
[53:48] SPEAKER: programmatically done.
[53:49] SPEAKER: If you don't tweak it to make it look distinct, like it's just very obvious.
[53:52] SPEAKER: I can't remember what it was.
[53:53] SPEAKER: There was some footage a few years ago that people were trying to figure out whether it
[54:00] SPEAKER: was real or fake and the camera shake was actually the thing that tipped them off because
[54:06] SPEAKER: somebody was like, Hey, this isn't actually a handheld camera.
[54:08] SPEAKER: This is one of the camera shake algorithms.
[54:10] SPEAKER: And then they recreated the motion precisely by lining up the pattern.
[54:14] SPEAKER: Yeah.
[54:14] SPEAKER: But I mean, it makes sense because if you can smooth something with software, you can
[54:18] SPEAKER: add shake to it in software.
[54:19] SPEAKER: Why not?
[54:20] SPEAKER: True.
[54:21] SPEAKER: Okay.
[54:22] SPEAKER: Quick couple of questions here from Moose.
[54:25] SPEAKER: My significant other heard you mentioned a few months back, Will, that you use a fountain
[54:28] SPEAKER: pen and they're interested in info, your current pen, ink and paper choice.
[54:34] SPEAKER: So I bought a starter kit that was recommended by someone by Lamy or Lamy.
[54:40] SPEAKER: I don't know.
[54:41] SPEAKER: It's a Lamy Safari.
[54:42] SPEAKER: L-A-M-Y.
[54:44] SPEAKER: L-A-M-Y.
[54:44] SPEAKER: And it was like 25 bucks and it came with inquiry fills.
[54:49] SPEAKER: And I just literally finished the first ink.
[54:52] SPEAKER: So I'm still going through the ink that came with it.
[54:54] SPEAKER: I haven't gotten to the next pack yet.
[54:58] SPEAKER: And then the paper I use most of the time is just field.
[55:00] SPEAKER: I use field.
[55:01] SPEAKER: I take notes in field notes, notepads, they're like little shirt pocket size.
[55:07] SPEAKER: I have two sizes.
[55:08] SPEAKER: I have journalist size pads, which are vertical opening, slightly bigger.
[55:12] SPEAKER: And then I have a shirt pocket size pads that I use for most things.
[55:16] SPEAKER: And does it feel very scratchy to write with?
[55:18] SPEAKER: No, it feels really good.
[55:19] SPEAKER: Does it really?
[55:20] SPEAKER: I would have thought that like, like, you know, a ballpoint kind of glides in a nice,
[55:23] SPEAKER: smooth way.
[55:24] SPEAKER: I would, I always thought that, to be honest, I always figured that writing with a fountain
[55:28] SPEAKER: pen was a little bit like nails on a chalkboard of just like really just scratching it across
[55:31] SPEAKER: the paper.
[55:32] SPEAKER: If you are scratching, I think you're pushing too hard.
[55:35] SPEAKER: Like you just want to barely glide it across the surface in my experience.
[55:38] SPEAKER: Oh, that sounds kind of pleasant, actually.
[55:40] SPEAKER: Yeah.
[55:40] SPEAKER: Next time I come, I've got to bring, I have some stuff I got to bring over to you.
[55:43] SPEAKER: So I'll bring it over and you can try it out next time I come over.
[55:45] SPEAKER: That sounds fun.
[55:46] SPEAKER: A question from Shayat.
[55:49] SPEAKER: Have either of you read the Bobiverse books?
[55:51] SPEAKER: If so, your thoughts and opinions.
[55:53] SPEAKER: The main character reminds me of Will, only he spends the books as the virtualized pilot
[55:58] SPEAKER: slash OS of a von Neumann probe.
[56:01] SPEAKER: How would you cope with being an immortal and technologically advanced being free to
[56:04] SPEAKER: wander all the universe, but with only copies of yourself for companionship on your immortal
[56:09] SPEAKER: timescale?
[56:10] SPEAKER: That sounds horrifying.
[56:11] SPEAKER: Oh, okay.
[56:12] SPEAKER: So Bobiverse books are really good.
[56:13] SPEAKER: Like they're, they're, they're, they're not as funny as like your Douglas Adams books,
[56:18] SPEAKER: but they're, they're thought provoking and interesting and weird in a way that I found
[56:22] SPEAKER: quite delightful.
[56:24] SPEAKER: And I, I don't know exactly how to take that Bob reminds you of me, but that's okay.
[56:30] SPEAKER: I guess I liked Bob's approach to that problem, which I'm not going to get into because I
[56:36] SPEAKER: want to spoil like the eight book series or whatever it is, but a highly, highly recommend
[56:42] SPEAKER: reading Bobiverse.
[56:44] SPEAKER: I would look, I mean, his approach is just, this happens in the first like five pages
[56:52] SPEAKER: to 10 pages of the book.
[56:54] SPEAKER: He just starts making copies of himself, which is, I don't know that I would make copies
[57:01] SPEAKER: of myself.
[57:02] SPEAKER: Yeah.
[57:02] SPEAKER: I mean, do they all have full agency because like just spawning a bunch of like techno
[57:06] SPEAKER: gods willy nilly maybe seems like a bad idea.
[57:09] SPEAKER: No, they're just like spaceships.
[57:11] SPEAKER: Okay.
[57:12] SPEAKER: Yeah.
[57:12] SPEAKER: Interstellar spaceships, lots of power, you know, it's fine.
[57:15] SPEAKER: What if one of them comes out evil?
[57:17] SPEAKER: Well, what if Brad, what if, I mean, obviously look, same inputs, same outputs.
[57:24] SPEAKER: You should, should be, should be, they should all be pretty mellow.
[57:27] SPEAKER: I mean, the nice thing about the Bobiverse is that Bob is a pretty chill guy.
[57:32] SPEAKER: So, you know, the, the Bobiverse pretty chill place.
[57:37] SPEAKER: I don't know.
[57:38] SPEAKER: I don't know what, I can't imagine what I would do with an immortal timescale.
[57:41] SPEAKER: That sounds horrifying.
[57:43] SPEAKER: I have no response.
[57:44] SPEAKER: I don't want, I don't want to live long enough to watch stars die.
[57:47] SPEAKER: It's too big a question.
[57:48] SPEAKER: Like I'm sitting here trying to wrap my head around it and I actually just, it's dizzying.
[57:52] SPEAKER: Yeah. Like I think, I think, I think like you'd go through a path where you do some,
[57:56] SPEAKER: like you do some exploring, you'd see some stuff.
[57:59] SPEAKER: It's like, it's like, it's like when you're 30 and you're thinking about having kids,
[58:03] SPEAKER: you're like, I'm going to go to Disney world.
[58:04] SPEAKER: That sounds like it'll be fun.
[58:05] SPEAKER: Then you get to Disney world and they're like, man, I don't know if Disney world is as much
[58:08] SPEAKER: fun as I thought it was.
[58:09] SPEAKER: There's a lot of people here.
[58:09] SPEAKER: It's, it's, I'm a little, little claustrophobic and the rides are kind of like, not like the
[58:14] SPEAKER: rollercoasters are pretty good, but they're not like, you're not going upside down or
[58:17] SPEAKER: anything really cool.
[58:19] SPEAKER: And then you're like, well, maybe I should go do something in nature.
[58:22] SPEAKER: And you go do something in nature and you're like, no, nature's okay.
[58:24] SPEAKER: I guess.
[58:25] SPEAKER: And then you get real into like mountain climbing or some weird hobby.
[58:29] SPEAKER: And then you, then you have to figure out what to do with the last 20 years of your
[58:31] SPEAKER: life and you begin to probably, you know, acid or something.
[58:35] SPEAKER: I don't know.
[58:36] SPEAKER: That's a good way to pass 20 years.
[58:38] SPEAKER: Yeah.
[58:39] SPEAKER: We just watched that episode of Star Trek where they genetically, like a society they
[58:43] SPEAKER: come upon had genetically engineered a way for people to live, let's say 60,000 years
[58:48] SPEAKER: each, something like that.
[58:49] SPEAKER: Yeah.
[58:50] SPEAKER: I think is how the math worked out.
[58:52] SPEAKER: I, I would have to double check the math.
[58:54] SPEAKER: Do you, do you know the episode I'm talking about?
[58:55] SPEAKER: Like the TNG?
[58:56] SPEAKER: No, no, no.
[58:57] SPEAKER: The original series, the premise, the premise is that they, they engineered their biology
[59:01] SPEAKER: in such a way that for every, for every century that they live, their body only ages one
[59:07] SPEAKER: month.
[59:08] SPEAKER: So you can do the math there, but I don't remember that one.
[59:10] SPEAKER: It might be from the, I haven't watched as many of the last season.
[59:12] SPEAKER: Also, it didn't work, killed all the adults.
[59:14] SPEAKER: Like the, the, the rub of the episode is that the virus that they engineered went haywire
[59:19] SPEAKER: and killed all the adults and only the children survived.
[59:21] SPEAKER: So now it's a tiny island society of forever children.
[59:25] SPEAKER: It's Lord of the Flies.
[59:27] SPEAKER: Basically, yes.
[59:27] SPEAKER: Yeah.
[59:28] SPEAKER: No, I have seen that one.
[59:29] SPEAKER: But setting that stuff aside, just the kind of thought experiment of like, how long is
[59:32] SPEAKER: too long to live?
[59:33] SPEAKER: How long, how long before you truly get bored?
[59:35] SPEAKER: Like, like human mind can't even comprehend of the idea of living for a thousand years,
[59:39] SPEAKER: let alone that long.
[59:40] SPEAKER: Yeah.
[59:40] SPEAKER: I think the boredom would be the thing that would get me.
[59:43] SPEAKER: Have you watched Strange New Worlds yet?
[59:45] SPEAKER: No.
[59:45] SPEAKER: You need to watch Strange New Worlds.
[59:46] SPEAKER: Yeah, I should.
[59:47] SPEAKER: It's really good.
[59:48] SPEAKER: You also should watch Lower Decks.
[59:49] SPEAKER: Both of those are very good.
[59:50] SPEAKER: There's a new season at Lower Decks like next week or something.
[59:53] SPEAKER: Okay.
[59:53] SPEAKER: Let's do two more real quick here.
[59:55] SPEAKER: Gauge 006.
[59:56] SPEAKER: I live in an apartment with great Google fiber.
[59:58] SPEAKER: However, there's only one fiber jack in the living room and no ethernet in the walls.
[1:00:02] SPEAKER: What's the best way to get near ethernet speed in my office?
[1:00:05] SPEAKER: A cable in the hallway isn't an option.
[1:00:08] SPEAKER: I'm going to make a novel solution here.
[1:00:11] SPEAKER: Living room in the office, office in the living room.
[1:00:14] SPEAKER: Wait, I'm sorry.
[1:00:14] SPEAKER: Can you just flip flop it?
[1:00:16] SPEAKER: Huh?
[1:00:16] SPEAKER: Yeah, these are arbitrary constructs implied by society.
[1:00:23] SPEAKER: You don't have to follow society's rules.
[1:00:25] SPEAKER: Who's your apartment complex to tell you that's the living room and that's the office?
[1:00:28] SPEAKER: That's fair.
[1:00:29] SPEAKER: That's, you know, live how you want to live.
[1:00:31] SPEAKER: I was going to say the two, I've never tried either of these,
[1:00:34] SPEAKER: but the two classic options are a power outlet, power line networking.
[1:00:40] SPEAKER: I mean, they're fine.
[1:00:41] SPEAKER: Mocha sounds like it's better than my understanding.
[1:00:44] SPEAKER: Again, you can look up numbers like my understanding is the power line networking
[1:00:48] SPEAKER: is less reliable and it has a lot of latency.
[1:00:50] SPEAKER: Yeah, the power line network is more latent than wifi.
[1:00:53] SPEAKER: And also will has a tendency if the wire at the house is wired badly to bleed out to your
[1:01:00] SPEAKER: neighbors.
[1:01:00] SPEAKER: So you have to encrypt it.
[1:01:02] SPEAKER: Oh, yikes.
[1:01:02] SPEAKER: Less of a problem now than it used to be when they were all unencrypted devices.
[1:01:05] SPEAKER: But now it's, it's the same as using WPA with wifi, right?
[1:01:09] SPEAKER: Sure.
[1:01:09] SPEAKER: Sounds like Mocha is probably a way better option from what I gather.
[1:01:13] SPEAKER: That uses coax in your walls.
[1:01:14] SPEAKER: So if you have coaxial cable, like from the cable company installed in multiple places,
[1:01:18] SPEAKER: you can put adapters on there and run through that.
[1:01:21] SPEAKER: And that sounds like it's pretty good.
[1:01:23] SPEAKER: I think the big problem there is it's just pretty expensive.
[1:01:25] SPEAKER: I think like the other 200 boxes, probably for the boxes, a little, little bit of research,
[1:01:30] SPEAKER: like the cheapest I've seen, like a pair of Mocha adapters was like 150 bucks.
[1:01:34] SPEAKER: The the other thing, the other option in this is wifi, a X is pretty good.
[1:01:41] SPEAKER: Wifi six is pretty good.
[1:01:44] SPEAKER: You're going to have a little more latency than you would with a wire.
[1:01:47] SPEAKER: The other, other thing is if you have carpet in your apartment, you can do the old sneaky,
[1:01:53] SPEAKER: run it around the jam, the cable under the trim between the carpet and the trim.
[1:01:58] SPEAKER: And that works great.
[1:01:59] SPEAKER: And no one will ever know what shirt has done it before.
[1:02:02] SPEAKER: Yeah.
[1:02:02] SPEAKER: Just get a skinny, skinny ethernet cable.
[1:02:05] SPEAKER: You can also get flat ethernet cables that might even slide into the trim with hardware
[1:02:09] SPEAKER: if the trim is low enough.
[1:02:11] SPEAKER: Yeah.
[1:02:11] SPEAKER: Like cable purists will tell you that that's not great for signal quality.
[1:02:16] SPEAKER: You know what is, is it better than wifi or worse than wifi?
[1:02:19] SPEAKER: That's the question you have to ask yourself.
[1:02:21] SPEAKER: I think technically they're supposed to be twisted, right?
[1:02:23] SPEAKER: But then again, they also said you couldn't round IDE cables and look at us now.
[1:02:28] SPEAKER: Well, the pairs can still be twisted inside the flat one.
[1:02:31] SPEAKER: Yeah.
[1:02:31] SPEAKER: I think, I think most of them are not as the complaint that I've seen.
[1:02:34] SPEAKER: I think that's, I, yeah.
[1:02:35] SPEAKER: I have a little flat ethernet cable I use for something and it works fine.
[1:02:38] SPEAKER: I, I, what I will tell you is I have taken the four pairs out of ethernet, an ethernet
[1:02:43] SPEAKER: cable before untwisted them, plugged it in and it doesn't work.
[1:02:47] SPEAKER: So they're doing something with the flat cables to make them work.
[1:02:50] SPEAKER: I do not know what it is.
[1:02:51] SPEAKER: Interesting.
[1:02:51] SPEAKER: Yeah.
[1:02:52] SPEAKER: Huh.
[1:02:52] SPEAKER: Okay.
[1:02:53] SPEAKER: Last question.
[1:02:54] SPEAKER: Hit me.
[1:02:54] SPEAKER: That's another cake batter.
[1:02:56] SPEAKER: Should I run for municipal council?
[1:02:58] SPEAKER: Yes.
[1:02:58] SPEAKER: Yes.
[1:02:59] SPEAKER: Absolutely.
[1:02:59] SPEAKER: Extremely yes.
[1:03:01] SPEAKER: Cake.
[1:03:01] SPEAKER: If you get elected to local government, I'm moving to your town or village or Hamlet or
[1:03:05] SPEAKER: whatever it is.
[1:03:07] SPEAKER: I started getting spam asking me to run for office last month or two months ago.
[1:03:11] SPEAKER: Interesting spam.
[1:03:12] SPEAKER: Text spam.
[1:03:13] SPEAKER: Huh.
[1:03:14] SPEAKER: Is that like scam spam?
[1:03:15] SPEAKER: I'm trying to think.
[1:03:15] SPEAKER: What is their angle?
[1:03:16] SPEAKER: Well, so I engaged because I was curious.
[1:03:19] SPEAKER: Maybe it's just actually truly genuinely civic minded responsible citizens.
[1:03:24] SPEAKER: It's an outreach group put together by the DNC.
[1:03:27] SPEAKER: Oh.
[1:03:27] SPEAKER: Trying to get people to run for local office.
[1:03:29] SPEAKER: And they looked at, because they had my information and knew who I was because I had signed up
[1:03:33] SPEAKER: to donate money at some point.
[1:03:35] SPEAKER: They were able to look up my voting records and they were like, Hey, you voted in all
[1:03:38] SPEAKER: the elections.
[1:03:39] SPEAKER: That's pretty good.
[1:03:40] SPEAKER: You're clearly interested.
[1:03:44] SPEAKER: I politely declined because I'm over overburdened right now.
[1:03:47] SPEAKER: I did not want to be the, on the garbage board of Pacifica or whatever they wanted me to
[1:03:50] SPEAKER: run for.
[1:03:51] SPEAKER: But anyway, yes, everybody should run for local office, run for the school board, run
[1:03:55] SPEAKER: for the city council, run for, well, not everybody.
[1:03:58] SPEAKER: If you, if you, if you think some people have more rights than other people, don't run.
[1:04:02] SPEAKER: That's my advice.
[1:04:03] SPEAKER: Yeah.
[1:04:03] SPEAKER: That's, that sounds pretty sound.
[1:04:05] SPEAKER: Yeah.
[1:04:06] SPEAKER: I don't even need to know cake's electoral platform.
[1:04:09] SPEAKER: I think cake's probably fine.
[1:04:10] SPEAKER: It's policy.
[1:04:11] SPEAKER: I'm just going to assume if he gets elected, it'll, it'll be, it'll be a trashcan generating
[1:04:15] SPEAKER: weather data on every corner.
[1:04:17] SPEAKER: And I am, I'm excited for that.
[1:04:19] SPEAKER: Bringing the darkness to city government, local government.
[1:04:22] SPEAKER: I'm all for that.
[1:04:23] SPEAKER: Yes, indeed.
[1:04:24] SPEAKER: All right.
[1:04:25] SPEAKER: Brad.
[1:04:26] SPEAKER: Yes.
[1:04:26] SPEAKER: Are we at the end?
[1:04:27] SPEAKER: Oh, how, how do people, if people enjoyed this episode and would like to submit their
[1:04:30] SPEAKER: own questions, how would they do that?
[1:04:32] SPEAKER: If you're on the discord, go to the questions seeking answers channel and drop them in there.
[1:04:37] SPEAKER: Also, we, we get this pretty regularly.
[1:04:39] SPEAKER: I'll just mention this real quick that we see people once or twice a month saying like,
[1:04:43] SPEAKER: Hey, I can actually see the questions in here right now.
[1:04:44] SPEAKER: That's just an artifact of the way the discord hides questions, hides, hides comments.
[1:04:49] SPEAKER: Yeah.
[1:04:50] SPEAKER: If you're, what is it?
[1:04:51] SPEAKER: I think if you're signed in and in that channel, when somebody asks things, you'll see that.
[1:04:55] SPEAKER: If you are sitting looking at that channel while the people are posting questions, then
[1:04:58] SPEAKER: they won't go away until the next time you exit and come back to the channel.
[1:05:01] SPEAKER: Yes.
[1:05:02] SPEAKER: Yeah.
[1:05:02] SPEAKER: So there's, there's nothing we can do about that part.
[1:05:04] SPEAKER: So like, don't, don't also don't confess to murders or anything like, like, I don't want
[1:05:08] SPEAKER: to have to take legal action in that channel.
[1:05:10] SPEAKER: It's not, this isn't a place.
[1:05:11] SPEAKER: This isn't like confession to take that to your priest.
[1:05:15] SPEAKER: Yeah.
[1:05:16] SPEAKER: This is a Q is turning into A's.
[1:05:18] SPEAKER: Yes, indeed.
[1:05:19] SPEAKER: Or they can send their questions to the email address techpod@content.town.
[1:05:24] SPEAKER: You mean techpod@content.town?
[1:05:25] SPEAKER: I do mean techpod@content.town.
[1:05:28] SPEAKER: And then we will occasionally turn those Q's into A's as well.
[1:05:30] SPEAKER: That's right.
[1:05:31] SPEAKER: Also, we always end up with a surplus.
[1:05:34] SPEAKER: We didn't get to nearly all of these questions today.
[1:05:36] SPEAKER: Look, December is going to be oops all questions month.
[1:05:38] SPEAKER: We're just going to do a whole year's worth of questions in one month.
[1:05:43] SPEAKER: October cast season is coming.
[1:05:45] SPEAKER: Oh man.
[1:05:45] SPEAKER: I haven't done an October cast in a long time.
[1:05:47] SPEAKER: I cannot, I physically cannot stay up for 24 hours anymore.
[1:05:51] SPEAKER: Just can't.
[1:05:51] SPEAKER: You know, Brad, there's two of us.
[1:05:53] SPEAKER: We could do 12 hours each.
[1:05:56] SPEAKER: I'm going to be raising money for AbleGamers next month on Twitch.
[1:05:59] SPEAKER: And for the old timers who liked watching me build Lego back in the day, I've been streaming
[1:06:05] SPEAKER: Lego builds at night, which has been fun lately, but this is the part of the show where we
[1:06:10] SPEAKER: thank our patrons.
[1:06:11] SPEAKER: Thank you, patrons.
[1:06:12] SPEAKER: Because the tech pod is a listener supported show and we appreciate all of you all.
[1:06:16] SPEAKER: You can find out how to chuck your support behind the tech pod at patreon.com/techpod.
[1:06:22] SPEAKER: That's patreon.com/techpod.
[1:06:25] SPEAKER: And you can join the ranks of our supporters, including our executive producer tier supporters.
[1:06:29] SPEAKER: Such as Andrew Slosky, Paddle Creek Games, makers of Fractured Veil, James Kamik, Joel
[1:06:35] SPEAKER: Krauska, Octothorpe, Twinkie has a new pick and place, Wedge assistant and Wedge assistant
[1:06:41] SPEAKER: to the thread club manager.
[1:06:44] SPEAKER: We added an Australia channel to the discord the other day.
[1:06:47] SPEAKER: You did.
[1:06:48] SPEAKER: Yeah.
[1:06:49] SPEAKER: And we added a book club channel so they could have threads for each weeks or months books
[1:06:55] SPEAKER: under the, under the book club channel.
[1:06:57] SPEAKER: We've got multiple clubs now.
[1:07:00] SPEAKER: Yeah.
[1:07:00] SPEAKER: The book club's going places.
[1:07:02] SPEAKER: They're doing, they're doing a lot of, they're picking good books.
[1:07:04] SPEAKER: I'm excited about what they're reading.
[1:07:05] SPEAKER: I think I'm going to read the next one because I can't remember what it was off the top of
[1:07:07] SPEAKER: my head, but I remember looking at the thing.
[1:07:08] SPEAKER: Oh man, that looks pretty good.
[1:07:10] SPEAKER: I might need to get on that too.
[1:07:11] SPEAKER: I've got this new Kindle I need to read more.
[1:07:13] SPEAKER: Yeah.
[1:07:14] SPEAKER: So I ended up getting one of the new Kindles the other day too.
[1:07:17] SPEAKER: When they were on sale again.
[1:07:18] SPEAKER: Paper white.
[1:07:18] SPEAKER: Yeah.
[1:07:19] SPEAKER: Paper white.
[1:07:19] SPEAKER: It's pretty good.
[1:07:20] SPEAKER: It's too big.
[1:07:22] SPEAKER: I can't one hand it as well as I used to.
[1:07:24] SPEAKER: Oh really?
[1:07:24] SPEAKER: I think it's just right.
[1:07:26] SPEAKER: Yeah.
[1:07:26] SPEAKER: Anyway, we also thank our associate producers here, patrons at the, at the end of the month
[1:07:31] SPEAKER: of the Q and a episode.
[1:07:32] SPEAKER: So we would like to thank Andre M Burke, Arthur Geese, Dave Julian, Eric Klein, Graham Banks,
[1:07:38] SPEAKER: Jad Rita, Jason Neelan, Jay Mabey, Joseph Thorne, Nathan Phelps, Steve Lynn, Thomas
[1:07:44] SPEAKER: Shay, and Travis Rosner.
[1:07:45] SPEAKER: Thank you all so, so much.
[1:07:46] SPEAKER: We appreciate you.
[1:07:47] SPEAKER: Yes, thank you.
[1:07:48] SPEAKER: Thank you to all.
[1:07:49] SPEAKER: And I think that's going to do it for us this month.
[1:07:52] SPEAKER: I can confirm it's going to do it.
[1:07:54] SPEAKER: We will see you all next week.
[1:07:58] SPEAKER: Bye everybody.
