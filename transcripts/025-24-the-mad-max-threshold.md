---
episode: 25
title: 24: The Mad Max Threshold
date: 2020-03-01
guests: none
duration: 38:39
---

[00:00] SPEAKER: All right, well, here's the real reason that I wanted to do this podcast with you.
[00:02] SPEAKER: Hit me.
[00:03] SPEAKER: So I can ask you questions.
[00:05] SPEAKER: Is it just a formal way for me to get my own curiosity satiated?
[00:10] SPEAKER: Here I am.
[00:11] SPEAKER: I can look things up on Wikipedia real good.
[00:14] SPEAKER: We ended last week with me rambling about buying a serial to USB cable.
[00:19] SPEAKER: Yeah, I'm really into this idea.
[00:20] SPEAKER: Setting up a com port. Yeah, now you're excited.
[00:22] SPEAKER: This is a great idea.
[00:23] SPEAKER: As a kind of an ancillary topic to that, what the hell is a UART?
[00:27] SPEAKER: Because that's something I've run into setting this thing up,
[00:29] SPEAKER: and then you also mentioned UARTs, I think, talking about PS2 ports for mice and keyboards.
[00:34] SPEAKER: Modems, probably.
[00:35] SPEAKER: A couple weeks ago, but I basically have seen that acronym related to a bunch of the kind of internal core technology on motherboards,
[00:42] SPEAKER: and I've always wondered what that was.
[00:44] SPEAKER: It's funny you mention this because I happen to have a Wikipedia page open right this moment.
[00:48] SPEAKER: Wait, what are you saying? I could have just answered this myself.
[00:50] SPEAKER: Oh, it's fine. Let me Google that for you.
[00:52] SPEAKER: Okay.
[00:52] SPEAKER: A Universal Asynchronous Receiver Transmitter, or UART, is how it looks like it's pronounced according to the Wikipedia Pronunciation Guide,
[01:01] SPEAKER: is a computer hardware device for asynchronous serial communication in which the data format and transmission speeds are configurable.
[01:09] SPEAKER: Oh, you mean the BOD?
[01:11] SPEAKER: Yeah, so it can say, look, I want to send binary data at this speed, or I want to send ASCII data at this speed.
[01:17] SPEAKER: So it's just a bucket, I think, a pipe that you can pour data into, and it can be a fat pipe.
[01:22] SPEAKER: Well, it can be that fat, but it can be pretty fat by 1960s standards, or not that fat by modern standards.
[01:29] SPEAKER: Okay, so when you're dealing with devices that plug into computers and the way they communicate with the hardware, that's going through UART in a lot of cases.
[01:38] SPEAKER: And for serial stuff, yes.
[01:40] SPEAKER: Pre-USB?
[01:41] SPEAKER: Pre-USB would be my guess.
[01:43] SPEAKER: Printer ports, modems, game ports, perhaps?
[01:46] SPEAKER: It used to be a chip. This used to be an actual physical chip that would be on a board.
[01:50] SPEAKER: Okay.
[01:51] SPEAKER: Probably just integrated into the motherboard chipset now?
[01:54] SPEAKER: Probably, it's just like 50 transistors somewhere in there these days.
[01:57] SPEAKER: Okay.
[01:58] SPEAKER: The XR17V252 is a dual quad and octal 66 megahertz PCI bus UART with power management support, register set, FIFOs, which is first in, first out, I think, I can't remember, level counters, so it's basically like all the stuff you need for the modem except for the modem bit.
[02:17] SPEAKER: All right, consider me edified on this topic. I'm sure this will be great knowledge to have in the scenario that we're about to discuss on this episode.
[02:25] SPEAKER: Yeah, it's exactly what we need.
[02:27] SPEAKER: This is really going to save your bacon someday.
[02:47] SPEAKER: (upbeat music)
[03:04] SPEAKER: Welcome to Brad and Will Made a Tech Pod.
[03:07] SPEAKER: Hi, Will.
[03:08] SPEAKER: Hi, Brad.
[03:08] SPEAKER: How's it going?
[03:09] SPEAKER: Good, man. How about you?
[03:10] SPEAKER: Good. For now.
[03:11] SPEAKER: Look, man.
[03:12] SPEAKER: What if things go bad?
[03:13] SPEAKER: You've got to be eternally, I learned this from Wing Commander 4, the price of freedom is eternal vigilance.
[03:19] SPEAKER: Is that where that, that can't be where that comes from.
[03:21] SPEAKER: No, it's from like, like Alexander Hamilton or Ben Franklin or somebody said it, but Malcolm McDowell said it to me in like 1995 and it really stuck with me.
[03:29] SPEAKER: Anything Malcolm McDowell has ever said to me.
[03:31] SPEAKER: You know, it turned out he was kind of a fascist in that game.
[03:34] SPEAKER: What is?
[03:34] SPEAKER: Spoilers.
[03:35] SPEAKER: Yeah, I could, okay.
[03:36] SPEAKER: Yeah, so.
[03:36] SPEAKER: He's good at that kind of thing.
[03:37] SPEAKER: But the point is you got to be ready at all times.
[03:40] SPEAKER: Yeah, and it actually, it's, it's amazing how much that doing this podcast has gotten me thinking about this stuff.
[03:45] SPEAKER: Like after we did InfoSec, I locked down a bunch of my financial and email stuff and I'm going to buy a fire safe to put documents and stuff in.
[03:53] SPEAKER: I have a YubiKey.
[03:54] SPEAKER: Yeah, you've got a YubiKey.
[03:55] SPEAKER: I already had a fire safe, but I have a YubiKey.
[03:56] SPEAKER: It's probably time to go all the way and just talk about, you know, your basic human needs.
[04:01] SPEAKER: Look, I find, so we live in a, in a area that is prone to unpredictable emergencies, earthquakes, sometimes fires.
[04:10] SPEAKER: Okay, yeah, like, you know, when you get down to it, there are not a lot of places that are not prone to some kind of disaster.
[04:16] SPEAKER: Yeah, but like hurricanes, you can at least, you know that there's hurricanes coming, you got like a few days notice.
[04:20] SPEAKER: I mean, I grew up in the hurricane territory, you know, even when you know they're coming, they're pretty bad.
[04:24] SPEAKER: No, it's, oh, no doubt.
[04:25] SPEAKER: It is bad news, but the point is after watching, I mean, this is something the federal government has told us for years to do, but after watching the aftermath of Katrina and how long people in New Orleans and the south Louisiana coast and in Houston.
[04:40] SPEAKER: After the floods there a few years ago, we're just completely on their own hurricane Sandy wildfires in Northern California.
[04:47] SPEAKER: Exactly.
[04:48] SPEAKER: Stuff has been rough the last few years.
[04:50] SPEAKER: You have to be prepared to feed, clothe, house, clean yourself.
[04:57] SPEAKER: You have to Maslow's hierarchy of needs yourself for, I think a week probably is the number that we shoot for.
[05:03] SPEAKER: The federal government says 72 hours.
[05:05] SPEAKER: I don't have that kind of confidence in FEMA.
[05:08] SPEAKER: I mean, you do get into a weird guessing game.
[05:10] SPEAKER: I guess I would say of like, how much is enough to sustain you?
[05:14] SPEAKER: And then what is the point where having supplies isn't going to matter anymore?
[05:18] SPEAKER: You know what I mean?
[05:18] SPEAKER: Like, yeah, I guess what I'm getting at is like, okay, let's say, what is, what is the number of days before things have gotten so bad that if you still need supplies by that time, then like extra supplies aren't going to help.
[05:27] SPEAKER: I think that is the Mad Max threshold, right?
[05:31] SPEAKER: Hey, we have a title already.
[05:32] SPEAKER: You get what I'm saying?
[05:34] SPEAKER: You get what I'm saying though?
[05:35] SPEAKER: Yeah, no, it's like, yeah, maybe it's two weeks.
[05:37] SPEAKER: I don't know.
[05:37] SPEAKER: But like at some point you've got to tell yourself, like, okay, if the water is not back on and there's no food available after two weeks, then society has probably broken down to the point that like an extra week worth of water is not going to be enough.
[05:49] SPEAKER: Across the Mad Max threshold, clearly.
[05:52] SPEAKER: So the basic idea, we went to ready.gov, which is the, the, the Department of Homeland Security last updated in 2016, just so you know, so it's clean 2014.
[06:02] SPEAKER: So it's clean, still trustworthy, trustworthy information.
[06:06] SPEAKER: If you, their, their basic idea is that you need to have a disaster supplies kit that supports everybody in your family, including pets for at least 72 hours.
[06:17] SPEAKER: And their basic guidelines are real good.
[06:19] SPEAKER: So it's like one gallon of water per person per day for at least three days.
[06:23] SPEAKER: And that's potable water.
[06:24] SPEAKER: Potable water.
[06:24] SPEAKER: Need to be able to drink it.
[06:26] SPEAKER: I, I have a mixture of gallons, like one gallon containers and just a shitload of bottles. So you don't have to open and contaminate the one gallon containers unless you're actually going to use a lot of water.
[06:40] SPEAKER: Like if you have to wash dishes or something.
[06:42] SPEAKER: Cause you know, if you're just drinking water for yourself, then the, then the bottles are fine.
[06:46] SPEAKER: Yeah.
[06:46] SPEAKER: If you're going to buy this in a store, you need distilled water.
[06:50] SPEAKER: It doesn't matter.
[06:50] SPEAKER: Cause they don't last.
[06:52] SPEAKER: Nothing lasts longer.
[06:53] SPEAKER: Like you have to cycle.
[06:54] SPEAKER: So one of the guidelines is you have to cycle the food stuff out every year to three years, depending on what it is.
[06:59] SPEAKER: Okay.
[07:00] SPEAKER: So when you're purchasing this stuff, think about the things you're going to want to eat one to three years.
[07:06] SPEAKER: So every year, just, just open it and consume the water you've got and buy more.
[07:09] SPEAKER: So what we do is we buy groceries from Amazon and when they send you cold items, they put frozen water bottles in there and all of the frozen water bottles go on the back of the shelf.
[07:19] SPEAKER: And we pull off the new water bottles when we need water bottles, either for like keeping coolers cold or for, you know, whatever we use water.
[07:27] SPEAKER: And that's good water.
[07:28] SPEAKER: I mean, it's fine.
[07:28] SPEAKER: Okay.
[07:29] SPEAKER: It'll keep you alive.
[07:30] SPEAKER: Drinkable.
[07:30] SPEAKER: Yeah, it's, it's, it's like, it's like Dasani bottle.
[07:33] SPEAKER: It's like their generic brand bottled water that they sell.
[07:36] SPEAKER: Yeah.
[07:36] SPEAKER: And that's I guess the, the one gallon per person per day.
[07:39] SPEAKER: Like that's the rate of consumption.
[07:41] SPEAKER: That is that's for washing plus some cleaning and like dishes and stuff like that.
[07:45] SPEAKER: It's the idea of drinking and dripping.
[07:47] SPEAKER: Okay.
[07:47] SPEAKER: So that's everything you need.
[07:48] SPEAKER: You also need to include pets, right?
[07:50] SPEAKER: Your pet obviously won't use a gallon per day.
[07:52] SPEAKER: But the reason I ask is like, when you get into water and food, if you're actually in this scenario, then you have to think about on a per day basis, how to ration.
[07:59] SPEAKER: Yeah.
[07:59] SPEAKER: So that's kind of what I was thinking about of like, okay, let's say you actually are in a disaster scenario.
[08:03] SPEAKER: Like you've got your gallon for the day.
[08:04] SPEAKER: Do you want to space it out?
[08:06] SPEAKER: Like, do you want to, how do you want to make sure that you just drink when you're thirsty?
[08:09] SPEAKER: Yeah.
[08:09] SPEAKER: Okay.
[08:10] SPEAKER: The other thing is you have to think about sometimes it gets really hot.
[08:12] SPEAKER: So like in the summertime, you're going to drink a lot more water.
[08:14] SPEAKER: So that's why you have a gallon, even though you need, you know, eight or 10 ounces or something to survive.
[08:19] SPEAKER: You need a three day supply of non-perishable food.
[08:21] SPEAKER: Yeah.
[08:21] SPEAKER: So you want calorically dense, relatively small stuff.
[08:24] SPEAKER: One of the things that the California earthquake readiness authority recommends is buying stuff like Insure, which is, tastes horrible.
[08:32] SPEAKER: It's revolting, but it has basically two cans of Insure is everything that an adult needs to stay alive.
[08:38] SPEAKER: Nutrient wise?
[08:39] SPEAKER: Nutrient wise.
[08:39] SPEAKER: Not calorie wise though.
[08:41] SPEAKER: It's super high caloric.
[08:42] SPEAKER: Is it really?
[08:42] SPEAKER: It's for people who can't eat or drink a whole lot.
[08:45] SPEAKER: Yeah.
[08:46] SPEAKER: So like you can, like, it's not perfect, obviously.
[08:50] SPEAKER: I'm sure if you'd eat that for six months, you're going to get micronutrient failure and have all sorts of problems.
[08:54] SPEAKER: Right.
[08:55] SPEAKER: I think we have somebody in the other room who could probably answer these questions way better than me.
[08:58] SPEAKER: Sure.
[09:00] SPEAKER: But the point is like energy bars, the survival boxes of food that Jeff makes fun of all the time.
[09:09] SPEAKER: Like freeze dried stuff is good.
[09:10] SPEAKER: What about straight up just canned food?
[09:12] SPEAKER: You don't want stuff that's too, too salty.
[09:14] SPEAKER: Oh, sure.
[09:14] SPEAKER: Canned food is often too salty.
[09:16] SPEAKER: Yeah.
[09:16] SPEAKER: So I was thinking like beans and spam and stuff like that.
[09:19] SPEAKER: I think, I think that stuff like, look, I think if you're in a situation where you're going to be eating this stuff for 10 days, probably variety is the spice of life.
[09:26] SPEAKER: Okay, sure.
[09:27] SPEAKER: You know, it's a little taste of spam.
[09:29] SPEAKER: It's going to be real, real delicious after five days of Insure.
[09:32] SPEAKER: So, but I feel like, I feel like when we put all this stuff together, we did this when my daughter was born and we've, we are at the point where we have to cycle food again.
[09:42] SPEAKER: We're thinking about what food we're going to replace, what we're going to replace the food that we have with.
[09:47] SPEAKER: A mixture of stuff that's shelf stable for a really long time, so you don't have to buy it every three years is nice.
[09:52] SPEAKER: But then also having stuff like builders bars.
[09:54] SPEAKER: So you have like protein bars and, and you know, nori and stuff like that, that is shelf stable and lasts a long time, but is going to not - talking to astronauts about what it's like to eat on the international space station where they're mostly shelf stable food.
[10:08] SPEAKER: The thing they crave more than anything else is like a piece of lettuce or an apple.
[10:11] SPEAKER: Something fresh.
[10:12] SPEAKER: Literally when they open the cargo supply ships, they come in and they get the apples that the people loaded in.
[10:17] SPEAKER: Like the, the Americans and the Westerners get apples and fruit and lettuce, and they have salads and stuff like that.
[10:22] SPEAKER: The Russians get raw onions and just chomp around right off of the, right off of the, of the soy, the progress ship.
[10:30] SPEAKER: Yeah.
[10:30] SPEAKER: They want the roughage.
[10:32] SPEAKER: Brad, it seems like you've brought show and tell.
[10:33] SPEAKER: Yeah.
[10:34] SPEAKER: I didn't actually think to mention this when we first got into this list.
[10:36] SPEAKER: I wasn't sure if I should bring it up now or at the end, but what you see before you is, I guess, is this your kit?
[10:43] SPEAKER: The extent of my disaster preparedness kit.
[10:45] SPEAKER: I mean, we have canned food and we just keep a lot of canned food around in general.
[10:48] SPEAKER: So there is like definitely some stuff we could subsist on.
[10:50] SPEAKER: Well, like stuff like, like dried ramen and stuff like that is good too.
[10:54] SPEAKER: Cause that stuff lasts forever.
[10:55] SPEAKER: And what if you don't have heat?
[10:56] SPEAKER: Well, I guess you're going to want a camp stove, like a camp stove is going to, we'll get there.
[11:00] SPEAKER: Okay.
[11:00] SPEAKER: Yeah.
[11:01] SPEAKER: Of course though, it's pretty salty, but anyway, let's see.
[11:04] SPEAKER: What do you have?
[11:05] SPEAKER: A single pack of, uh, that's the astronaut ice cream.
[11:08] SPEAKER: Oh, that's a cookies and cream ice cream sandwich as sold at the air and space museum in Washington, DC.
[11:12] SPEAKER: Yeah.
[11:12] SPEAKER: Also got a little baggie of, uh, what is this?
[11:14] SPEAKER: Two MREs, three MREs?
[11:15] SPEAKER: I think that's three, maybe.
[11:17] SPEAKER: I have to fess up.
[11:18] SPEAKER: Pretty sure these MREs, we'll see if this is vegetable lasagna.
[11:21] SPEAKER: Are these Chach MREs?
[11:23] SPEAKER: I'm pretty sure the astronaut ice cream and the MREs came as promotional material.
[11:28] SPEAKER: One was Kerbal and one was Call of Duty with video games.
[11:31] SPEAKER: Wow.
[11:32] SPEAKER: I think these MREs are probably 10 years old, at least maybe 15.
[11:36] SPEAKER: They last a long time.
[11:38] SPEAKER: I know that's the whole idea.
[11:39] SPEAKER: I mean, there's a YouTube channel where a guy eats like one or two food.
[11:42] SPEAKER: Yes.
[11:43] SPEAKER: I wouldn't do that.
[11:44] SPEAKER: One time I ate a piece of really old gum.
[11:46] SPEAKER: It was like 80s trading card gum.
[11:48] SPEAKER: It was, it was, it just crumbled into like grains.
[11:52] SPEAKER: It was bad.
[11:52] SPEAKER: Yeah.
[11:53] SPEAKER: Okay.
[11:53] SPEAKER: So three days supply of non-perishable food, I think go a little bit longer than that.
[11:57] SPEAKER: Think about what you're going to want to eat.
[11:59] SPEAKER: Think about if you have to cycle it out, what you want to eat at some point in the future.
[12:01] SPEAKER: And it's in a non-emergency or like a camping situation.
[12:06] SPEAKER: Flashlight.
[12:06] SPEAKER: This is important.
[12:07] SPEAKER: Yeah.
[12:08] SPEAKER: So should we.
[12:09] SPEAKER: We can talk about your radio.
[12:10] SPEAKER: We want to get to the third and final and maybe perhaps the only actually useful item in my kit.
[12:14] SPEAKER: Are you a KQED member or is this a separate purchase?
[12:17] SPEAKER: Oh, this is separate.
[12:18] SPEAKER: Okay.
[12:19] SPEAKER: I have a little, this is an Eaton brand.
[12:21] SPEAKER: I'm gonna have to look it over to make sure I remember everything it does.
[12:23] SPEAKER: It's a crank powered radio.
[12:26] SPEAKER: Okay.
[12:26] SPEAKER: Slash flashlight.
[12:28] SPEAKER: Does it have batteries too?
[12:29] SPEAKER: Just, yes.
[12:29] SPEAKER: Okay.
[12:29] SPEAKER: So we'll get to that.
[12:30] SPEAKER: Cause I have a question about that.
[12:31] SPEAKER: Let's see.
[12:32] SPEAKER: So it's got, so it's a radio.
[12:33] SPEAKER: It's like an AM, maybe AM/AFM at least AM.
[12:36] SPEAKER: It's got, it has a flashlight.
[12:38] SPEAKER: Yeah.
[12:39] SPEAKER: So it's got a flashlight.
[12:40] SPEAKER: It's actually got something on the back there.
[12:41] SPEAKER: It's got USB ports on the back to charge crank charger.
[12:44] SPEAKER: USB is what I assume.
[12:46] SPEAKER: That's a solar cell.
[12:46] SPEAKER: That's a little solar cell.
[12:47] SPEAKER: So it's both solar and crank powered.
[12:49] SPEAKER: That solar cell is not big enough to do much.
[12:51] SPEAKER: Probably not.
[12:52] SPEAKER: No.
[12:53] SPEAKER: Like you're not going to charge your phone off of that.
[12:55] SPEAKER: No.
[12:57] SPEAKER: But it's.
[12:57] SPEAKER: I mean, maybe for a little bit.
[12:58] SPEAKER: You can crank.
[12:59] SPEAKER: Yeah.
[13:00] SPEAKER: Converge kinetic energy.
[13:02] SPEAKER: It's like that, that thing that panic's making.
[13:04] SPEAKER: Phone.
[13:05] SPEAKER: Yeah.
[13:06] SPEAKER: Yeah.
[13:06] SPEAKER: So it's, it's, it's basically radio, flashlight, charger.
[13:09] SPEAKER: The radio is on the list because as we learned last year, when our power was out for three days,
[13:15] SPEAKER: the cell service goes away when the batteries at the cell tower stopped working,
[13:19] SPEAKER: which is about 48 hours in my case.
[13:21] SPEAKER: Oh, wow.
[13:21] SPEAKER: So you guys actually need the radio?
[13:24] SPEAKER: We didn't have a radio.
[13:25] SPEAKER: Oh no.
[13:26] SPEAKER: And let me tell you when there's wildfires burning all around you.
[13:28] SPEAKER: Yeah.
[13:29] SPEAKER: You're you, you end up doing seemingly unhinged things,
[13:33] SPEAKER: like walking out in the backyard at two o'clock in the morning going.
[13:36] SPEAKER: Oh, nope.
[13:37] SPEAKER: Does it smell like smoke yet?
[13:38] SPEAKER: We're probably good.
[13:39] SPEAKER: Probably fine.
[13:39] SPEAKER: I don't see a glow on the horizon.
[13:41] SPEAKER: Yeah, this is what we did see a glow on the horizon.
[13:43] SPEAKER: That's the problem.
[13:43] SPEAKER: Cause we see like daily city had lights.
[13:46] SPEAKER: So we just went out.
[13:47] SPEAKER: Yeah.
[13:47] SPEAKER: Anyway, what about your car radio?
[13:48] SPEAKER: Was that not?
[13:48] SPEAKER: Well, that would have been really smart, Brad.
[13:50] SPEAKER: Okay.
[13:51] SPEAKER: I hadn't considered that until you said that just now.
[13:53] SPEAKER: Okay.
[13:54] SPEAKER: Well, next time.
[13:55] SPEAKER: Yeah.
[13:56] SPEAKER: If you don't get one, the more we learned before we move on real quick, I was just
[13:58] SPEAKER: going to ask, I bet I've had this thing for 15 years.
[14:02] SPEAKER: Yeah.
[14:02] SPEAKER: Probably changed the batteries.
[14:03] SPEAKER: That's what I was going to ask.
[14:04] SPEAKER: So I've never pulled the little cardboard pull tab to actually connect the batteries
[14:08] SPEAKER: that it shipped with.
[14:09] SPEAKER: Do you think they're still good?
[14:10] SPEAKER: I'll bring the volt meter next time and we can find out we'll do an experiment.
[14:13] SPEAKER: They're NIM, nickel metal hydride.
[14:15] SPEAKER: Yes.
[14:15] SPEAKER: Those will be no nickel metal hydride is Enel loops.
[14:18] SPEAKER: So they should be like 70% charge.
[14:20] SPEAKER: Okay.
[14:20] SPEAKER: Well, maybe less.
[14:22] SPEAKER: No, no.
[14:22] SPEAKER: Like that's the stop at 60 or 70% losing charge.
[14:27] SPEAKER: I don't think they ever completely discharged, but I could be wrong.
[14:29] SPEAKER: Well, the bigger question for me is less how much charge they still have in them and more
[14:32] SPEAKER: if they can be charged, like would they still work?
[14:34] SPEAKER: Yeah, they should be fine.
[14:35] SPEAKER: Okay.
[14:35] SPEAKER: Especially if you crank it real hard.
[14:39] SPEAKER: Done.
[14:40] SPEAKER: I have two names for this podcast.
[14:43] SPEAKER: All right, cool.
[14:44] SPEAKER: So I do have one item in my thing that's actually possibly kind of used.
[14:47] SPEAKER: So I want to talk about some stuff that I've added to our kit after various minor emergencies.
[14:52] SPEAKER: The one thing real quick before we move on that I was going to add about the radio is I
[14:55] SPEAKER: guess at least, I mean, this may be less so for you, but I would think in my case, being
[14:58] SPEAKER: in the middle of a city, like there's probably, if nothing else, there's going to be straight
[15:02] SPEAKER: up like loudspeakers.
[15:03] SPEAKER: You think?
[15:04] SPEAKER: In some way, right?
[15:05] SPEAKER: Surely, surely they've accounted for that.
[15:06] SPEAKER: I like that optimism.
[15:08] SPEAKER: Surely the city has just got some way to very loudly yell what's going on to people.
[15:13] SPEAKER: Look, I'm watching what happens, what's happened in China as they're figuring out how to deal
[15:16] SPEAKER: with coronavirus and thinking that probably there will be no, like if there is a legitimate
[15:22] SPEAKER: emergency, the infrastructure will be entirely dedicated to ameliorating the emergency and
[15:27] SPEAKER: not human comfort.
[15:28] SPEAKER: I guess you're right.
[15:29] SPEAKER: There is some kind of, I don't know if it's like an air raid siren.
[15:33] SPEAKER: There's some kind of early warning error.
[15:35] SPEAKER: Well, there's earthquake and tsunami sirens.
[15:38] SPEAKER: Okay.
[15:38] SPEAKER: Maybe that's what they're testing.
[15:39] SPEAKER: They test it around noon sometimes.
[15:41] SPEAKER: By the way, do you know about the quake alert thing?
[15:43] SPEAKER: Oh.
[15:44] SPEAKER: So you can sign up for a service if you live in an earthquake area in California that is
[15:49] SPEAKER: called Quake Alert.
[15:51] SPEAKER: You know how sometimes you log into Twitter and you see people tweeting about an earthquake
[15:54] SPEAKER: and then you feel it a few seconds later?
[15:55] SPEAKER: Oh, I've never had that experience.
[15:57] SPEAKER: Oh.
[15:57] SPEAKER: I always feel it and then go to Twitter to see everybody going, "Earthquake!"
[16:00] SPEAKER: Well, so I've had a couple of times where I was sitting and I happened to be looking
[16:03] SPEAKER: at Twitter and I saw like East Bay people tweeting about an earthquake and then I would
[16:06] SPEAKER: feel it like five seconds later.
[16:08] SPEAKER: No kidding.
[16:08] SPEAKER: So because the internet moves at the speed of light and the earthquake moves at the speed
[16:13] SPEAKER: of waves through dirt, basically Quake Alert will send you a notification when there's
[16:18] SPEAKER: about to be an earthquake.
[16:19] SPEAKER: Okay.
[16:19] SPEAKER: So they've already detected it starting?
[16:21] SPEAKER: They've detected it.
[16:22] SPEAKER: Okay.
[16:22] SPEAKER: I thought where you were going with that was they were predicting it, but my understanding
[16:26] SPEAKER: is predicting quakes is basically impossible.
[16:27] SPEAKER: It's like you get five or 10 seconds head start on like, you know to bend over and kiss
[16:32] SPEAKER: your ass goodbye, not that you can actually do it anyway.
[16:37] SPEAKER: Okay.
[16:37] SPEAKER: So first aid kit, flashlight.
[16:40] SPEAKER: I have a couple more flashlights.
[16:41] SPEAKER: I have these little lanterns that are, I have a pretty good size solar cell on the top.
[16:45] SPEAKER: Yeah.
[16:45] SPEAKER: We've got one of those two actually.
[16:46] SPEAKER: That thing is incredible with the power that was out.
[16:48] SPEAKER: LED lamp.
[16:50] SPEAKER: Because like the one that we have two, one is a D-light, which is the good one.
[16:53] SPEAKER: Deep dot light you can get from Amazon.
[16:56] SPEAKER: I'll put a list of all this stuff in the show notes and people can get it from Amazon or
[16:59] SPEAKER: whatever they want.
[17:00] SPEAKER: But you put in the sun during the day and then you get 14 hours of light at night, which
[17:04] SPEAKER: it turns out is a lifesaver when the power's out for an extended period of time.
[17:07] SPEAKER: Sure.
[17:08] SPEAKER: Candle's not the worst thing to have around.
[17:09] SPEAKER: Obviously there's some fire hazard there.
[17:11] SPEAKER: A little bit of a fire hazard, but you know, those tealight candles, the watch battery
[17:15] SPEAKER: ones will run for a hundred hours on a watch battery.
[17:18] SPEAKER: So those things are mega cheap.
[17:20] SPEAKER: Yeah.
[17:20] SPEAKER: You can buy a pack of like 20 of those for 10 bucks.
[17:23] SPEAKER: If you, yeah, Pier One or Daiso or Ikea sells them for very inexpensive too.
[17:29] SPEAKER: A first aid kit, just normal first aid kit stuff.
[17:31] SPEAKER: Bandages, cold packs, bug, like Benadryl type stuff.
[17:37] SPEAKER: Something if you get bug, because if you're in an earthquake, you're probably sleeping
[17:40] SPEAKER: in the backyard.
[17:41] SPEAKER: So you're going to get bug bites.
[17:43] SPEAKER: You're going to get sunburn, sunscreen.
[17:45] SPEAKER: Like a bottle of, you know, you can get isopropyl alcohol for super cheap.
[17:48] SPEAKER: Exactly.
[17:49] SPEAKER: A bottle of that around for disinfecting.
[17:50] SPEAKER: Always.
[17:52] SPEAKER: Extra batteries.
[17:53] SPEAKER: We have a big sack of just AA batteries.
[17:56] SPEAKER: You know, they're in the box so they don't drain.
[17:58] SPEAKER: The disposable kind.
[17:59] SPEAKER: Disposable kind, yeah.
[18:01] SPEAKER: N95 masks.
[18:02] SPEAKER: And if you have a beard, you have to have a razor so you can actually get shaved down
[18:06] SPEAKER: enough that they work.
[18:07] SPEAKER: Yeah.
[18:07] SPEAKER: Because N95 mask does nothing for me.
[18:10] SPEAKER: That was the real eye opening experience.
[18:13] SPEAKER: Was it two years?
[18:13] SPEAKER: I can't keep track of time.
[18:15] SPEAKER: Was it last year or two years ago when the terrible awful fires?
[18:17] SPEAKER: Santa Rosa was when we got the bad smoke.
[18:19] SPEAKER: That was two years ago.
[18:20] SPEAKER: Was it two years ago now?
[18:20] SPEAKER: Last year we had bad fires, but they were further away and we didn't get as smoky.
[18:23] SPEAKER: So that two years ago, that incident where, you know, like everywhere you went, like they
[18:28] SPEAKER: were shoving masks in your face.
[18:29] SPEAKER: Like at work every day, they were like, hey, don't forget your mask on the way home.
[18:32] SPEAKER: Like it was like...
[18:33] SPEAKER: It was bad.
[18:34] SPEAKER: We strongly recommend that you wear a mask when you're outdoors.
[18:36] SPEAKER: This is not a just to make yourself feel better.
[18:39] SPEAKER: This is like the particulate load in the air right now is hazardous to your health.
[18:44] SPEAKER: There will be a cancer cluster around Northern California in 10 years from the shit we breathed
[18:50] SPEAKER: two years ago.
[18:51] SPEAKER: I have no doubt.
[18:51] SPEAKER: Oh, that's not good to hear.
[18:53] SPEAKER: That makes me feel...
[18:54] SPEAKER: I'm not a medical professional.
[18:55] SPEAKER: It's just an opinion, but like a lot of garbage.
[18:58] SPEAKER: It's a weird feeling in the air too.
[19:00] SPEAKER: Like not, I don't mean...
[19:01] SPEAKER: It's hard to breathe.
[19:01] SPEAKER: No, no, no.
[19:02] SPEAKER: I don't mean like physically in the air.
[19:03] SPEAKER: I mean, that sucks too.
[19:04] SPEAKER: But I mean more like psychologically the feel of like oppression, it feels oppressing.
[19:09] SPEAKER: Kind of, yeah.
[19:10] SPEAKER: And it's something that's going to be a lot more noticeable in the city.
[19:14] SPEAKER: Because you're in the shared...
[19:16] SPEAKER: I was in the burbs and I didn't get it as much.
[19:18] SPEAKER: I also didn't leave the house much.
[19:19] SPEAKER: It's just stuff like, I mean, seeing everybody everywhere you go wearing those masks and
[19:22] SPEAKER: like the change in just like the color of the air because of the haze.
[19:26] SPEAKER: Everything was yellow.
[19:27] SPEAKER: Yeah, everything was yellow.
[19:28] SPEAKER: And like you're hearing announcements being made.
[19:31] SPEAKER: It feels a little bit like a disaster area.
[19:33] SPEAKER: You know what I mean?
[19:34] SPEAKER: Like it raises your hackles a little bit.
[19:36] SPEAKER: Like it makes you subconsciously go like, something is off here and it's not good.
[19:41] SPEAKER: It was very discomforting.
[19:43] SPEAKER: And that's nothing compared to what the people in the actual fire zone were suffering.
[19:47] SPEAKER: And it's also nothing compared to like much worse disasters than this.
[19:49] SPEAKER: So I'm just, you know, it was just a taste of what that's like.
[19:52] SPEAKER: So I can't even imagine what a true disaster situation is actually like to be in the middle of.
[19:57] SPEAKER: I mean, it's got to be...
[19:59] SPEAKER: I mean, I have friends whose houses burned in Santa Rosa and they said it was horrific.
[20:02] SPEAKER: So, okay, dust mask, moist towelettes, whistle.
[20:07] SPEAKER: A lot of moist towelettes.
[20:08] SPEAKER: We have multiple boxes of baby wipes, like 150, 250 wipes.
[20:13] SPEAKER: You can get big baby wipes for like sponge bathing yourself.
[20:16] SPEAKER: Like you'd get if you're in the hospital.
[20:18] SPEAKER: I was going to say, you probably don't want to burn much of your water on bathing and
[20:22] SPEAKER: washing and cleaning if you don't have to.
[20:23] SPEAKER: The least you have to do, I would think.
[20:25] SPEAKER: Yeah.
[20:26] SPEAKER: Because the water is the hard thing.
[20:28] SPEAKER: And also there are other things you can do to make your way.
[20:30] SPEAKER: If you live near a water source, I have one of those filter straws.
[20:37] SPEAKER: I have a couple of those filter straws and I have a UV disinfectant and a filter bag.
[20:42] SPEAKER: Okay.
[20:42] SPEAKER: I was just about to ask about a UV.
[20:44] SPEAKER: Yeah.
[20:44] SPEAKER: So Vinnie introduced me to this years ago when we were camping.
[20:46] SPEAKER: Okay.
[20:47] SPEAKER: But it's basically a UV light, a really UV ABC light, I assume.
[20:53] SPEAKER: I don't know how it works.
[20:54] SPEAKER: You chuck it in this big canvas bag, fill the bag with water and then leave it there
[20:59] SPEAKER: for a couple of hours and it'll disinfect what's in the water.
[21:02] SPEAKER: And then the bottom of the bag filters out whatever particulates it.
[21:05] SPEAKER: Oh, wow.
[21:06] SPEAKER: Probably doesn't take out stuff like heavy metals.
[21:08] SPEAKER: Yeah, yeah.
[21:08] SPEAKER: It's just for bacteria.
[21:09] SPEAKER: But it's just for bacteria and stuff that'll make you sick.
[21:11] SPEAKER: So when we were camping, we were camping by a lake and he was able to go down and scoop
[21:18] SPEAKER: up like a 10 gallon bag of the water, put this light in it, and then like an hour later,
[21:22] SPEAKER: we would have as much water as we needed.
[21:24] SPEAKER: As long as you're confident you're not downstream from any industrial pollutants, you should be.
[21:29] SPEAKER: Also, won't work with salt water.
[21:31] SPEAKER: Yeah.
[21:31] SPEAKER: Yeah.
[21:32] SPEAKER: So a whistle is important.
[21:35] SPEAKER: I mean, if you really want to get crazy, there are ways to distill salt water if you have to sell.
[21:40] SPEAKER: If you want to build a still, it's beyond the scope of this podcast, but I salute you.
[21:43] SPEAKER: Yes.
[21:44] SPEAKER: A wrench to turn off your gas.
[21:45] SPEAKER: Okay.
[21:45] SPEAKER: You should always, always, always have a big pipe wrench near where you can find it.
[21:52] SPEAKER: When the person drove through my next door neighbor's house last summer, they literally
[21:56] SPEAKER: drove their car through the living room of this friend of mine, our neighbors.
[22:00] SPEAKER: The first thing we did was jump out and somebody had a big pipe wrench and they
[22:03] SPEAKER: shut the gas down for the house and we didn't blow up the neighborhood.
[22:06] SPEAKER: That was something I read about recently in a discussion about good kind of best practices
[22:10] SPEAKER: for home ownership, which sadly means it's nothing I need to worry about right now.
[22:13] SPEAKER: But that was something people were saying was like, "Hey, when you..."
[22:16] SPEAKER: I guess this also goes for renting, even if you don't buy a house.
[22:19] SPEAKER: You need to know where the gas comes out.
[22:20] SPEAKER: Yeah, exactly.
[22:20] SPEAKER: When you move into your first house, not just the gas, but also the water, all that stuff,
[22:25] SPEAKER: know exactly how the breakers work and know exactly how to turn off the water at a moment's
[22:28] SPEAKER: notice and I guess the gas as well.
[22:30] SPEAKER: Just make sure that you give that stuff a trial run and are confident.
[22:34] SPEAKER: You don't want to have to figure that stuff out while something's on fire.
[22:37] SPEAKER: Yes.
[22:37] SPEAKER: Or flooding or whatever.
[22:38] SPEAKER: Yeah.
[22:39] SPEAKER: And the gas is bad because it can turn your house into a fuel air bomb, which will explode
[22:45] SPEAKER: and blow.
[22:46] SPEAKER: You know, when that happened in San Bruno, while we were doing the Big Live Live show,
[22:49] SPEAKER: it was a horrific disaster.
[22:51] SPEAKER: People were killed.
[22:51] SPEAKER: I still have nightmares about that incident.
[22:53] SPEAKER: Yeah.
[22:53] SPEAKER: Like that's just one of those act of God things of like, this could happen anywhere.
[22:57] SPEAKER: It wasn't an act of God.
[22:58] SPEAKER: It was negligence on PG&E's part.
[23:00] SPEAKER: I know exactly whose fault it was, but what I mean is there's no way to see it coming.
[23:03] SPEAKER: Yeah, no.
[23:04] SPEAKER: Like that could happen anywhere and there's zero way to avoid it.
[23:07] SPEAKER: Well, one of the ways you can avoid it is by knowing where the wrench is to turn on.
[23:10] SPEAKER: But you're right.
[23:11] SPEAKER: What I mean is you on the street walking down the sidewalk, like there's no way for you
[23:14] SPEAKER: to know it's going to happen because it happens in a split second.
[23:17] SPEAKER: Terrible luck.
[23:17] SPEAKER: Yeah.
[23:18] SPEAKER: A can opener.
[23:19] SPEAKER: It turns out it's important if you have canned food.
[23:22] SPEAKER: Garbage bags, plastic ties, so that you have places to poop and put the poop.
[23:27] SPEAKER: Yeah.
[23:28] SPEAKER: Composting toilet.
[23:29] SPEAKER: If you think you're going to have to camp in your backyard for a while is not a bad idea.
[23:32] SPEAKER: So you can get a five gallon drywall mud bucket and put a toilet seat on top of that.
[23:37] SPEAKER: Okay.
[23:37] SPEAKER: And put a shower curtain around it and have a nice private bathroom.
[23:40] SPEAKER: And then you put sawdust on top of the poop and the pee.
[23:42] SPEAKER: Yeah.
[23:43] SPEAKER: And then when you need to, you dig a hole and you dump the contents of that bucket into the hole.
[23:47] SPEAKER: Really gives new meaning to the phrase mud bucket.
[23:49] SPEAKER: Oh boy.
[23:51] SPEAKER: Let's move on.
[23:52] SPEAKER: Maps, paper maps, because your phone won't work.
[23:54] SPEAKER: Yeah.
[23:55] SPEAKER: Cell phone chargers and a backup battery.
[23:58] SPEAKER: When the power was out a few years ago, I was able to get for $55 or $60 a three-fold huge
[24:05] SPEAKER: solar panel.
[24:06] SPEAKER: It's two square feet, probably, that you can unfold, put in the backyard.
[24:11] SPEAKER: You can hook up multiples of them.
[24:12] SPEAKER: You angle them up toward the sun and they'll charge...
[24:16] SPEAKER: Theoretically, you use them to charge your phone.
[24:18] SPEAKER: I found it was much more effective to just put them in the backyard with a backup battery on it
[24:21] SPEAKER: and let it charge a backup battery.
[24:23] SPEAKER: I'm sure they don't come with their own batteries.
[24:25] SPEAKER: There's nowhere for the power to go unless you're charging something.
[24:27] SPEAKER: Something has to be plugged in.
[24:29] SPEAKER: But for 30 bucks, you can get a really nice backup battery that will charge two phones
[24:36] SPEAKER: at this point.
[24:37] SPEAKER: That was a losing proposition if you used your phone very much.
[24:43] SPEAKER: You would never generate as much power with the sun as you would spend by spending five
[24:49] SPEAKER: hours on the phone that day.
[24:50] SPEAKER: So you still want to ration your use and keep it for emergencies.
[24:57] SPEAKER: I was going to ask, I don't know if you have any sense of the tiny little crank on this
[25:00] SPEAKER: radio that I've got.
[25:01] SPEAKER: It's like a three, four-inch crank.
[25:03] SPEAKER: I think you're going to have to crank it real hard.
[25:05] SPEAKER: Yeah, I was going to ask.
[25:06] SPEAKER: I mean, that's probably a similar situation of you're just barely going to get any phone
[25:10] SPEAKER: out of this, right?
[25:11] SPEAKER: That seems largely ineffective to me, but I don't know.
[25:14] SPEAKER: I mean, how hard is it to crank?
[25:15] SPEAKER: I've never tried it.
[25:16] SPEAKER: I've never turned this thing on.
[25:17] SPEAKER: Well, give it a try.
[25:17] SPEAKER: Let her rip.
[25:18] SPEAKER: I don't know what it would actually do if I.
[25:21] SPEAKER: Oh, that's okay.
[25:22] SPEAKER: Oh, the radio on?
[25:23] SPEAKER: It started the clock.
[25:24] SPEAKER: Oh, okay.
[25:25] SPEAKER: We'll set the clock real quick.
[25:26] SPEAKER: Okay.
[25:27] SPEAKER: I'm just going to sit here and look at this clock.
[25:28] SPEAKER: It says 12 PM.
[25:30] SPEAKER: There we go.
[25:30] SPEAKER: Nailing it.
[25:31] SPEAKER: Not remotely accurate, but pet food.
[25:33] SPEAKER: If you have pets, you need food for your pets, water for your pets too.
[25:36] SPEAKER: Yes, the clock has gone off.
[25:39] SPEAKER: Yes.
[25:39] SPEAKER: The batteries aren't plugged in.
[25:40] SPEAKER: Power is no longer being generated.
[25:43] SPEAKER: Prescription meds, non-prescription meds, pain pills, antihistamines, antacids, laxatives,
[25:50] SPEAKER: anti-diarrhea medicine, glasses and contact lens stuff.
[25:56] SPEAKER: If you need that, any baby stuff you need, some cash.
[26:01] SPEAKER: We have seeds in case society completely breaks down.
[26:04] SPEAKER: No kidding.
[26:04] SPEAKER: I'm kidding.
[26:05] SPEAKER: We don't have seeds.
[26:05] SPEAKER: I was going to say, that's very optimistic and forward thinking.
[26:08] SPEAKER: Look, at some point, the only thing people are going to be able to use is the seeds.
[26:12] SPEAKER: Yeah.
[26:12] SPEAKER: Your family documents.
[26:14] SPEAKER: So your passport and stuff like that.
[26:15] SPEAKER: The local warlord is going to require you to pay the seeds in tribute at that point.
[26:19] SPEAKER: Look, it's either seeds or blood.
[26:20] SPEAKER: You can decide.
[26:21] SPEAKER: Oh, boy.
[26:22] SPEAKER: Look, man, I got some tomatoes.
[26:25] SPEAKER: I got some lettuce.
[26:26] SPEAKER: I got some artichokes.
[26:27] SPEAKER: Yeah.
[26:28] SPEAKER: Turns out he loved artichokes.
[26:29] SPEAKER: Oh, boy.
[26:30] SPEAKER: Sleeping bags for everyone.
[26:31] SPEAKER: Okay.
[26:32] SPEAKER: Our tent is right next to the emergency kit.
[26:35] SPEAKER: It's not in there, but our camping tent is there.
[26:36] SPEAKER: That's something you mentioned before that I haven't even thought about.
[26:39] SPEAKER: And I guess different disasters are going to be different, but especially in an earthquake
[26:42] SPEAKER: situation, you might actually not be able to stay indoors.
[26:44] SPEAKER: Yeah.
[26:44] SPEAKER: You might not be able to go back in your house.
[26:46] SPEAKER: This might be more than just the breakdown of supply lines to keep you alive.
[26:49] SPEAKER: It might actually be like the structural integrity of your home has drawn away.
[26:54] SPEAKER: So, like I said, the tent, who knows?
[26:57] SPEAKER: One of the things that we got that we added is this combination pry bar, hammer, nail
[27:03] SPEAKER: puller.
[27:03] SPEAKER: It's an all-in-one kind of multi-tool sort of thing.
[27:07] SPEAKER: It's like a hammer scale multi-tool there.
[27:09] SPEAKER: So you can drive tent stakes, you can pull tent stakes out.
[27:13] SPEAKER: If you need to pry open a door that's jammed shut because the house shifted, you can do
[27:17] SPEAKER: that.
[27:18] SPEAKER: If you need to knock a hole in the wall, you can do that.
[27:20] SPEAKER: That sounds good to have.
[27:20] SPEAKER: And also like an actual hand-sized multi-tool, like a Leatherman type thing.
[27:23] SPEAKER: Yeah.
[27:24] SPEAKER: Leatherman, incredibly useful.
[27:25] SPEAKER: Also great to have.
[27:26] SPEAKER: Also, I don't know if we talked about, what is that key chain I got?
[27:28] SPEAKER: The Gerber Shard?
[27:30] SPEAKER: Yeah, that thing's amazing.
[27:31] SPEAKER: Speaking of multi-tools, Gerber Shard is the name of it.
[27:34] SPEAKER: It's seven bucks.
[27:35] SPEAKER: It's a tiny little metal.
[27:37] SPEAKER: It's just a machined piece of metal.
[27:38] SPEAKER: There's no moving parts.
[27:39] SPEAKER: I think it's just folded and stamped probably.
[27:41] SPEAKER: Yeah.
[27:43] SPEAKER: It's like a pry bar.
[27:44] SPEAKER: It's like a little thumb-sized pry bar.
[27:46] SPEAKER: For pulling nails.
[27:47] SPEAKER: The idea, I bought one years ago because I was ruining expensive car keys by using them
[27:54] SPEAKER: to pry stuff open.
[27:55] SPEAKER: Yeah.
[27:56] SPEAKER: And this is $7, so if I ruin this, I just buy another one.
[27:59] SPEAKER: Yeah.
[27:59] SPEAKER: But it has a couple of bad screwdrivers that you would never use except for when you really,
[28:04] SPEAKER: really need a screwdriver and don't have one.
[28:06] SPEAKER: Yes, they are rough to use.
[28:07] SPEAKER: I've tried that in a pinch if that's all you had.
[28:10] SPEAKER: And a nail puller and a little bit of a sharpened edge so you can cut stuff.
[28:13] SPEAKER: You can open boxes.
[28:15] SPEAKER: It's got a can opener and bottle opener, stuff like that.
[28:18] SPEAKER: Okay, so sleeping bags, warm blankets, tent, multiple changes of clothes appropriate for
[28:23] SPEAKER: your climate, shoes that you can walk in because you might have to do some serious walking.
[28:26] SPEAKER: So either hiking boots, tennis shoes, something ideally that's waterproof, something that's
[28:30] SPEAKER: comfortable.
[28:31] SPEAKER: Waterproof, good arch support.
[28:34] SPEAKER: Bleach to disinfect water.
[28:36] SPEAKER: So the easiest way to disinfect water is a couple of drops of bleach in there.
[28:39] SPEAKER: Okay.
[28:40] SPEAKER: Yeah.
[28:42] SPEAKER: 1% is solution.
[28:43] SPEAKER: So one part, 99 parts.
[28:45] SPEAKER: You mean that's what you're buying?
[28:46] SPEAKER: No, that's what you want to do to disinfect is my understanding.
[28:49] SPEAKER: Okay.
[28:50] SPEAKER: So a couple drops per...
[28:51] SPEAKER: I don't know.
[28:51] SPEAKER: That's just the idea of putting any bleach in something I'm going to drink sounds horrifying.
[28:54] SPEAKER: Drunk pool water.
[28:55] SPEAKER: I guess.
[28:57] SPEAKER: Let's see.
[28:58] SPEAKER: Rainwear.
[28:59] SPEAKER: If you live in a rainy climate, especially while it matches in a waterproof container,
[29:03] SPEAKER: lighters good too, those long lighters with the candle lighters with the long nose or
[29:08] SPEAKER: make it easy to light fires.
[29:10] SPEAKER: I have some fire starters that are like paraffin wax.
[29:14] SPEAKER: Okay.
[29:15] SPEAKER: So they're slightly flammable, but they burn for a fairly long time.
[29:19] SPEAKER: They're like little cubes about the size of like a dog biscuit or something.
[29:22] SPEAKER: It's like one inch by one inch by one inch.
[29:23] SPEAKER: Sure.
[29:24] SPEAKER: And you can put them underneath your tinder and it means that you don't have to...
[29:29] SPEAKER: It's just an easy...
[29:30] SPEAKER: You don't have to have paper or anything to get a fire started if you're having a hard
[29:32] SPEAKER: time, cooking supplies, like a mess kit, feminine supplies, personal hygiene items.
[29:39] SPEAKER: So tampons, pads, all that stuff, paper and pencil, and then stuff to entertain yourself,
[29:45] SPEAKER: books and games and puzzles and all that stuff.
[29:48] SPEAKER: God, I guess that's a situation where a Kindle is not going to be adequate anymore.
[29:52] SPEAKER: Kindle is great.
[29:52] SPEAKER: Actually, as long as it lasts.
[29:54] SPEAKER: I mean, granted the battery lasts forever.
[29:55] SPEAKER: So two weeks you could charge the Kindle on the solar panel in like 10, 20 minutes probably.
[29:59] SPEAKER: And I'm sure read a book.
[30:00] SPEAKER: And if you're in a situation of relative luxury, you could get books downloaded over your phone.
[30:05] SPEAKER: Yeah.
[30:06] SPEAKER: If things aren't dire enough, you need to be worrying about more serious concerns.
[30:10] SPEAKER: Oh yeah.
[30:10] SPEAKER: There are ways to get more books onto your Kindle if you can
[30:13] SPEAKER: keep it powered and the cell connection is alive.
[30:15] SPEAKER: And even when the fire was bad, I mean, if things are really bad,
[30:20] SPEAKER: you assume you're not gonna have internet, right?
[30:21] SPEAKER: Yeah.
[30:22] SPEAKER: But I remember seeing a picture during Sandy in New York where the one person on the block
[30:28] SPEAKER: who had power because they had a generator had run an extension cord out to the front
[30:32] SPEAKER: with like 55 ends on it.
[30:34] SPEAKER: And everybody was there plugging in their phones and charging their phones.
[30:36] SPEAKER: So like community.
[30:38] SPEAKER: Community comes together.
[30:39] SPEAKER: People come together.
[30:39] SPEAKER: People come together.
[30:41] SPEAKER: The other thing that the ready.gov recommends is that you keep a go bag at your workplace.
[30:47] SPEAKER: Especially that's intense.
[30:49] SPEAKER: Well, like you and I wear sneakers to work, so it's not as much of an issue,
[30:51] SPEAKER: but it's like you wear high heels to work.
[30:52] SPEAKER: Oh, sure.
[30:53] SPEAKER: You want to have a pair of sneakers.
[30:55] SPEAKER: You want to have comfortable, warm clothes.
[30:56] SPEAKER: Professional business wear is not survival wear.
[30:59] SPEAKER: No, you want to be able to walk from your off workplace to your house
[31:03] SPEAKER: or whatever your meeting point is for your family.
[31:06] SPEAKER: And that's kind of the big stuff.
[31:07] SPEAKER: Like books and puzzles were really important when our power was out last year.
[31:11] SPEAKER: We were in the house, which was a blessing.
[31:13] SPEAKER: You know, if you have a gas stove.
[31:16] SPEAKER: Yeah, I was gonna ask if you wanted to elaborate on the camp stove situation a little bit.
[31:20] SPEAKER: Yeah, we have...
[31:21] SPEAKER: What are we talking?
[31:22] SPEAKER: Propane?
[31:23] SPEAKER: Putane?
[31:24] SPEAKER: What's going on?
[31:25] SPEAKER: Let's see, the main...
[31:28] SPEAKER: I don't know what ours...
[31:28] SPEAKER: We have a jet boil that's good for boiling water really fast
[31:32] SPEAKER: and making coffee and oatmeal and stuff like that that we use when we're camping.
[31:35] SPEAKER: I want to get one of those Coleman white gas camp stoves of the two...
[31:40] SPEAKER: Kind of the two burner fold up kind that looks like a briefcase almost.
[31:44] SPEAKER: Okay.
[31:45] SPEAKER: Just because we do a lot of car camping now with the kiddo, not as much backpacking and stuff.
[31:50] SPEAKER: I can't imagine there's any kind of sensible electric alternative at this point.
[31:55] SPEAKER: I mean, you can do solar ovens and stuff like that, but those are real...
[31:58] SPEAKER: In my experience, those are useless.
[31:59] SPEAKER: Okay.
[32:00] SPEAKER: I'm sure that if you live in Arizona, they're great.
[32:02] SPEAKER: Sure.
[32:02] SPEAKER: But in terms of like something battery powered, I can't imagine the energy efficiency just...
[32:06] SPEAKER: No, you need there to cook food.
[32:08] SPEAKER: You want something flammable.
[32:09] SPEAKER: The way you can with some propane or the white gas.
[32:14] SPEAKER: I don't know if they do the white gas anymore.
[32:15] SPEAKER: I feel like my...
[32:18] SPEAKER: The jet boil thing is propane, I think.
[32:21] SPEAKER: The canisters last a long time.
[32:23] SPEAKER: You want to know how long, what your use rate of that is.
[32:25] SPEAKER: So experiment a little bit before you get into an actual emergency, make sure.
[32:29] SPEAKER: But the nice thing is you shouldn't be able to store two weeks worth of gas
[32:33] SPEAKER: in four or five canisters at the most.
[32:36] SPEAKER: Do you know much about the kind of relative, like the practical differences in the relative
[32:40] SPEAKER: efficiency of your propanes and your butanes and your kerosines and...
[32:43] SPEAKER: No.
[32:44] SPEAKER: Just they're all just different petrochemicals.
[32:46] SPEAKER: Yeah.
[32:46] SPEAKER: Their energy density is really going to be high compared to batteries though.
[32:50] SPEAKER: Well, yeah, of course, of course.
[32:51] SPEAKER: I just didn't know if there was one that was better in this kind of situation.
[32:54] SPEAKER: I know very little about that stuff.
[32:56] SPEAKER: I feel like...
[32:56] SPEAKER: Get a chemical engineer in here.
[32:58] SPEAKER: I feel like a lot of the reasons we use those different gases is the different volatility
[33:03] SPEAKER: of butane versus propane probably makes a butane lighter less likely to explode.
[33:08] SPEAKER: Okay.
[33:10] SPEAKER: It's like one of the...
[33:12] SPEAKER: This is great advice from my grandfather, but he told me never light a fire...
[33:17] SPEAKER: Never light your burn pile with gasoline.
[33:19] SPEAKER: Okay.
[33:20] SPEAKER: 'Cause it explodes, the vapor explodes.
[33:22] SPEAKER: Sure.
[33:22] SPEAKER: He used heating oil or kerosene to do that is what his recommendation was.
[33:27] SPEAKER: Yeah.
[33:28] SPEAKER: Time-moderated advice passed down from Smith to Smith.
[33:31] SPEAKER: It's the best kind.
[33:32] SPEAKER: Yeah.
[33:32] SPEAKER: It's gotten you this far.
[33:34] SPEAKER: I haven't killed myself yet.
[33:35] SPEAKER: I don't burn a lot of brush piles, it turns out, in these days.
[33:38] SPEAKER: My parents here last week, I have some brush in the yard 'cause I have to do the thing
[33:43] SPEAKER: where you trim trees and then dull it out to the compost over a period of two or three
[33:48] SPEAKER: weeks to get rid of it all.
[33:49] SPEAKER: They're like, "Well, oh, right.
[33:51] SPEAKER: You can't just do a burn pile here, right?"
[33:53] SPEAKER: I was like, "No, you can't just do a burn pile in the suburbs."
[33:55] SPEAKER: Not such a good idea.
[33:56] SPEAKER: It would be frowned upon.
[33:57] SPEAKER: Especially such a fire-prone area.
[33:59] SPEAKER: Yeah.
[34:00] SPEAKER: So yeah, that's the kind of high points.
[34:03] SPEAKER: Okay.
[34:03] SPEAKER: I think the Kindle is a good add to the kit.
[34:07] SPEAKER: Yeah.
[34:08] SPEAKER: When I first thought of it in my mind, it seemed kind of frivolous, but I guess because
[34:11] SPEAKER: the battery does last so long, it actually isn't the worst thing to have.
[34:15] SPEAKER: Yeah, the biggest problem we had when the power was out, especially with kids, was keeping
[34:22] SPEAKER: everybody entertained.
[34:23] SPEAKER: People going stir crazy.
[34:25] SPEAKER: Yeah.
[34:25] SPEAKER: And then you also have to think about things like, even if the power is just out, which
[34:29] SPEAKER: is all we had where we were, the street lights and stuff all went out.
[34:33] SPEAKER: All of the infrastructure stuff went out.
[34:34] SPEAKER: So no cell phone, even if we had had battery backup on our internet, it wouldn't have
[34:40] SPEAKER: worked.
[34:42] SPEAKER: So you're going to have a lot more time than you're used to, and you're not going
[34:45] SPEAKER: to be able to fill it with Netflix or your video games or whatever it is you do for fun.
[34:49] SPEAKER: Definitely not.
[34:50] SPEAKER: So, you know, board games, it turns out are real handy.
[34:53] SPEAKER: Yeah.
[34:53] SPEAKER: Yeah.
[34:53] SPEAKER: Growing up in the deck of cards, too.
[34:55] SPEAKER: I don't know how much you had to deal with this, but growing up in a heavily wooded part
[34:58] SPEAKER: of North Carolina.
[34:59] SPEAKER: I just went on walks a lot.
[35:01] SPEAKER: Especially a part where Duke Power was not interested in ever burying the power lines.
[35:05] SPEAKER: Yeah.
[35:06] SPEAKER: We definitely dealt with extended power outages just about every year.
[35:09] SPEAKER: Like the worst was probably like four or five days at a time.
[35:12] SPEAKER: Oh, God.
[35:14] SPEAKER: We had a bunch of like three, four days, and then we had one that was two weeks when we
[35:18] SPEAKER: had an ice storm.
[35:19] SPEAKER: Did you guys have a well?
[35:20] SPEAKER: No.
[35:20] SPEAKER: That's the real problem.
[35:21] SPEAKER: Yeah.
[35:23] SPEAKER: My parents are on a well now.
[35:24] SPEAKER: They have a generator because they're on a well.
[35:26] SPEAKER: My parents do too now, but they certainly did not want to ask for a well.
[35:29] SPEAKER: Back then they were a lot more expensive.
[35:30] SPEAKER: That meant that when the power was out, the water was also out.
[35:33] SPEAKER: So you were not flushing any toilets, you were not bathing, you were kind of in, yeah.
[35:38] SPEAKER: When I was at my grandmother's one year, she was on a well and we would walk down to the
[35:41] SPEAKER: creek and get water to flush toilets.
[35:44] SPEAKER: Oh, that's a good idea.
[35:45] SPEAKER: We would carry like a 10 gallon bucket back because you can just, if you don't know, you
[35:49] SPEAKER: just pour the water at the top of the toilet and then you flush like normal.
[35:52] SPEAKER: Yeah, that's just physics at that point.
[35:54] SPEAKER: Yeah.
[35:54] SPEAKER: But my father growing up in Virginia used to tell stories of multi-week power outages
[36:00] SPEAKER: on a well and it sounded horrific.
[36:02] SPEAKER: Yes.
[36:04] SPEAKER: So I'm glad we're past that.
[36:05] SPEAKER: Take care of yourself.
[36:06] SPEAKER: Get, prepare yourself.
[36:07] SPEAKER: Just be ready.
[36:08] SPEAKER: You know.
[36:10] SPEAKER: Look, this is a thing you can go to Costco, you can buy a big garbage can that has most
[36:15] SPEAKER: of the stuff in here that you'll need that'll serve as a base layer.
[36:18] SPEAKER: Yeah.
[36:19] SPEAKER: You're talking something like with a lid that would be waterproof.
[36:21] SPEAKER: Yeah.
[36:24] SPEAKER: Ours is in the garage just because we have a small backyard, but ideally you'd put in
[36:28] SPEAKER: the backyard in a covered area where it's protected from sun and just leave it out there
[36:34] SPEAKER: for the core stuff.
[36:35] SPEAKER: And I feel like if we can't get into the garage, we have larger problems.
[36:39] SPEAKER: Totally.
[36:40] SPEAKER: That's past the Mad Max threshold.
[36:41] SPEAKER: Yeah, that's definitely past the Mad Max threshold.
[36:44] SPEAKER: Yeah.
[36:44] SPEAKER: I don't want to be a doomsayer or anything, but as talk about more extreme climate disasters
[36:50] SPEAKER: keeps ramping up, it's not the worst idea to think about this stuff.
[36:53] SPEAKER: The way I look at it is if you're prepared and you don't require, you don't have to go
[36:57] SPEAKER: to a shelter, you don't have to rely on other people, you can also avoid a lot of the other
[37:02] SPEAKER: after effects of bad natural disasters, like the secondary diseases that people get and
[37:09] SPEAKER: spread due to close proximity and bad conditions and all that.
[37:13] SPEAKER: Yeah.
[37:13] SPEAKER: Cheery episode.
[37:14] SPEAKER: Yeah, this is a real heartbeat.
[37:16] SPEAKER: Well, but I mean, look, ounce of prevention is worth a pound of cure.
[37:20] SPEAKER: There's that Smith wisdom again.
[37:21] SPEAKER: Yeah, there we go.
[37:24] SPEAKER: Let's see if you have questions or I would love to hear what you all have put in your
[37:28] SPEAKER: kits, especially people who've been through disasters, because I know we have some listeners
[37:31] SPEAKER: who were in Houston and in Louisiana and in New York and all sorts of places that they've
[37:36] SPEAKER: been actually impacted by this stuff.
[37:38] SPEAKER: So I would love to hear the stuff that you would add to your kit after this.
[37:42] SPEAKER: Honestly, I could not have enough battery backups.
[37:46] SPEAKER: Cigarette lighter phone chargers are good, because then you can charge off your...
[37:49] SPEAKER: Get a fast charge in your car.
[37:51] SPEAKER: We would often go for a drive when our power was out and recharge the battery backups that
[37:56] SPEAKER: way, because that was faster than the solar panel.
[37:58] SPEAKER: Sure.
[37:59] SPEAKER: But yeah, let us know what's in your kits, let us know what you learned in your disasters,
[38:02] SPEAKER: let us know what you would do different, let us know what we said was what the government
[38:05] SPEAKER: says is wrong.
[38:07] SPEAKER: And the email address is techpod@content.town.
[38:10] SPEAKER: We'll be back next week with more TechPod.
[38:12] SPEAKER: Thanks, Will.
[38:13] SPEAKER: Thanks, Brad.
[38:13] SPEAKER: See you next time.
[38:14] SPEAKER: Bye.
[38:29] SPEAKER: Bye.
