---
episode: 251
title: 241: The Computruth About Computex
date: 2024-06-30
guests: none
duration: 1:07:55
---

[00:00] SPEAKER: - Okay, Adam, I made a benchmark for the first time
[00:04] SPEAKER: in about 15 years.
[00:06] SPEAKER: - You made a serious benchmark for serious people, for sure.
[00:10] SPEAKER: - Yeah, we were doing a video for Falcon Northwest
[00:14] SPEAKER: about making a PC, like a PC for games,
[00:18] SPEAKER: and I realized that there's not any real game dev,
[00:22] SPEAKER: like light bank benchmarks or compile benchmarks
[00:24] SPEAKER: and stuff like that, so I loaded up UE5
[00:28] SPEAKER: and built a little, I don't wanna call it,
[00:32] SPEAKER: it's not like a full real life run for a light bake
[00:35] SPEAKER: because that takes a kinda long time to run
[00:38] SPEAKER: for a real production level, but I made something
[00:40] SPEAKER: that I think is fairly representative
[00:41] SPEAKER: of what a light bake looks like
[00:44] SPEAKER: on a production video game, on a video game as video game.
[00:47] SPEAKER: - Yeah, well, and to be fair, it's way more than I know
[00:50] SPEAKER: about any of that game development stuff.
[00:52] SPEAKER: I know hardware, so it was interesting
[00:54] SPEAKER: to see hardware used in a different way.
[00:56] SPEAKER: If people wanna see the video, it's up on PCWorld's
[00:59] SPEAKER: YouTube channel now, sponsored by Falcon Northwest,
[01:01] SPEAKER: thank you, it was a good, it was one of those perfect
[01:05] SPEAKER: testing kinda scenarios where Falcon Northwest
[01:07] SPEAKER: was like, hey, we'd love somebody to test
[01:10] SPEAKER: this game dev stuff on hardware.
[01:12] SPEAKER: We don't have anybody in house who knows game dev stuff,
[01:15] SPEAKER: but we were like, hey, Will, you know this stuff.
[01:18] SPEAKER: - I was available, it turns out.
[01:20] SPEAKER: - You were available, it worked out perfect.
[01:22] SPEAKER: It was a match made in heaven, but yeah,
[01:26] SPEAKER: specifically for Unreal Engine 5, right?
[01:29] SPEAKER: - Yeah, so the thing, so we had two benchmarks that we used.
[01:33] SPEAKER: One is a map compile for the Anacrusis,
[01:36] SPEAKER: which Chet was kind enough to let us use,
[01:38] SPEAKER: which uses the tool chain that we built for the game,
[01:41] SPEAKER: which includes like GPU light bakes.
[01:43] SPEAKER: So instead of doing those math calculations on the CPU,
[01:47] SPEAKER: like you would in the old days,
[01:49] SPEAKER: or if you're really serious about fidelity,
[01:51] SPEAKER: we used a light mask plugin that was GPU accelerated
[01:55] SPEAKER: on the Anacrusis so that we could do light bakes
[01:59] SPEAKER: on all of the artists' computers.
[02:00] SPEAKER: That was the choice we made over there.
[02:02] SPEAKER: They made that choice before I started, for what it's worth.
[02:05] SPEAKER: The thing that we did with UE5,
[02:09] SPEAKER: 'cause I talk about it a little bit in the video,
[02:11] SPEAKER: but I think a lot of people think,
[02:13] SPEAKER: oh, you don't need to do light bakes
[02:15] SPEAKER: or anything like that anymore
[02:15] SPEAKER: because people have ray tracing hardware
[02:19] SPEAKER: that can do real-time lighting and all this crazy stuff.
[02:22] SPEAKER: And while that's true at the high end of the PC,
[02:26] SPEAKER: it's a little bit less true
[02:28] SPEAKER: the further down the hardware, the platforms you get.
[02:32] SPEAKER: So when you're talking about an Xbox Series X or a PS5,
[02:37] SPEAKER: yeah, you can do some dynamic lighting stuff,
[02:39] SPEAKER: but there's still probably some light bakes in there
[02:41] SPEAKER: for even the high-end hardware.
[02:43] SPEAKER: When you're talking about something that's running
[02:44] SPEAKER: on a Switch or an old GeForce 1080 or 2080 computer,
[02:50] SPEAKER: there's Lightmap City up in there.
[02:52] SPEAKER: So you still have to do that math,
[02:54] SPEAKER: and it takes a long time, it turns out,
[02:56] SPEAKER: 'cause you're basically bouncing light
[03:00] SPEAKER: from every light source to every surface in the game
[03:02] SPEAKER: and figure out whether it should be light or dark
[03:04] SPEAKER: based on how far it is from the thing.
[03:06] SPEAKER: And that's computationally expensive.
[03:09] SPEAKER: - Well, and excuse my limited knowledge
[03:12] SPEAKER: for this kind of stuff,
[03:13] SPEAKER: but this is something that happens,
[03:17] SPEAKER: it sounds like it happens at different points
[03:19] SPEAKER: in the process of game development.
[03:21] SPEAKER: You're baking occasionally to just see how things happen,
[03:25] SPEAKER: and then of course you're doing the final bake
[03:27] SPEAKER: before it goes live, is that right?
[03:30] SPEAKER: - Well, yeah, so everybody's process
[03:32] SPEAKER: is different on this stuff.
[03:33] SPEAKER: So some studios will gray box out an entire level,
[03:36] SPEAKER: and it'll just be flat-shaded generic boxes
[03:40] SPEAKER: that are to see how it plays.
[03:43] SPEAKER: - So they'll build the content, the actual gameplay,
[03:45] SPEAKER: and then worry about the lighting and stuff later.
[03:48] SPEAKER: - Yeah, so if you look at, I think Half-Life,
[03:51] SPEAKER: this is the way Valve worked for old Half-Life games.
[03:54] SPEAKER: This is the way Bungie did the old Halo games,
[03:58] SPEAKER: is they would gray box out the level
[04:01] SPEAKER: and build those arenas so that the combat arena was fun.
[04:04] SPEAKER: And then somebody would come through and say,
[04:07] SPEAKER: "Okay, this big giant box is gonna be a big rock,
[04:09] SPEAKER: "and this big giant box is gonna be a blah, blah, blah."
[04:12] SPEAKER: And obviously this is an oversimplification,
[04:15] SPEAKER: 'cause if you're talking about a game
[04:16] SPEAKER: that has a big set piece level,
[04:18] SPEAKER: then they're going to know what that set piece is coming in.
[04:22] SPEAKER: So if they know that the Call of Duty Stalingrad level,
[04:25] SPEAKER: where you're chained to the guy, you grab the gun,
[04:28] SPEAKER: he gets the second clip of ammo,
[04:32] SPEAKER: they know you're gonna run up a big hill,
[04:33] SPEAKER: they know you're gonna start at a boat dock,
[04:35] SPEAKER: and they know that the end of that
[04:36] SPEAKER: is gonna be charging some giant library
[04:38] SPEAKER: or Stalingrad, like a civic building, right?
[04:46] SPEAKER: - Classic.
[04:47] SPEAKER: - Yeah, but if you're just running through corridors
[04:50] SPEAKER: and stuff like that, then yeah, often they start gray boxed.
[04:53] SPEAKER: And those will be full light,
[04:54] SPEAKER: so there's no lighting calculations,
[04:56] SPEAKER: it's just everything is lit, there's no shadows,
[04:58] SPEAKER: there's no dark spaces.
[05:00] SPEAKER: And then as the levels get arted up,
[05:03] SPEAKER: as the environment artists come in
[05:04] SPEAKER: and turn the boxes into chairs and tables and bushes
[05:07] SPEAKER: and shrubbery and cover and all that stuff,
[05:10] SPEAKER: then you start placing lights along with that process, right?
[05:14] SPEAKER: And those lights determine what areas are light
[05:17] SPEAKER: and which areas are dark,
[05:17] SPEAKER: and that's when you start to need to bake those lights,
[05:22] SPEAKER: bake those light maps.
[05:23] SPEAKER: - And that's very computational intensive,
[05:25] SPEAKER: which is why the hardware matters going into that.
[05:29] SPEAKER: And that's what your benchmark was trying to get at, right?
[05:32] SPEAKER: Was like, hey, what are the specific hardware requirements
[05:36] SPEAKER: for doing that specific kind of task, right?
[05:40] SPEAKER: - Yeah, baking the light maps specifically
[05:42] SPEAKER: is a thing that includes a lot of downtime.
[05:44] SPEAKER: So it's often like hit the button and walk away
[05:48] SPEAKER: and go have lunch and then have a walk and then come back.
[05:52] SPEAKER: And that means that that artist can't do anything else
[05:55] SPEAKER: during that time.
[05:56] SPEAKER: Now, there are a bunch of ways around it.
[05:57] SPEAKER: You can build a really fast machine,
[05:59] SPEAKER: like our main environment artist had a giant Threadripper
[06:02] SPEAKER: for the early development process
[06:04] SPEAKER: when they were doing this all in the CPU.
[06:06] SPEAKER: And he ended up doing most of the early light bakes
[06:09] SPEAKER: because he had the big giant CPU.
[06:12] SPEAKER: We switched to the GPU light mass
[06:13] SPEAKER: so that everybody could do it as we got further along
[06:15] SPEAKER: and had more environment artists working
[06:17] SPEAKER: and made a lot of sense.
[06:21] SPEAKER: The other thing you can do
[06:22] SPEAKER: is set up a dedicated workstation someplace
[06:24] SPEAKER: that's just the light bake machine.
[06:25] SPEAKER: And you check in your updates and then you run a script
[06:30] SPEAKER: that says, hey, download the latest updates
[06:31] SPEAKER: and then we'll bake the lights on the following maps.
[06:33] SPEAKER: And it'll just do those sequentially
[06:35] SPEAKER: and then upload them back to your Perforce or GitHub
[06:39] SPEAKER: or whatever you use for code management and asset management.
[06:42] SPEAKER: - Well, I found the video very enlightening
[06:45] SPEAKER: as not a game developer.
[06:46] SPEAKER: So hopefully game developers will find it enlightening.
[06:48] SPEAKER: I will say as of today when we're recording this,
[06:51] SPEAKER: the video is up on PCWorld's YouTube channel
[06:54] SPEAKER: and we do have some developers in our full nerd discord
[06:58] SPEAKER: who are literally talking right now in a background window
[07:01] SPEAKER: that I'm seeing and they're talking about like, yeah,
[07:03] SPEAKER: the different use cases for different hardware.
[07:06] SPEAKER: But specifically one of them was asking about
[07:10] SPEAKER: like if that benchmark is gonna be included
[07:13] SPEAKER: in our future CPU reviews.
[07:15] SPEAKER: Because we at PCWorld like to review components
[07:18] SPEAKER: like CPUs and GPUs and we're always looking for new ways
[07:23] SPEAKER: to benchmark and test and help people.
[07:26] SPEAKER: And one of the questions I had was,
[07:28] SPEAKER: I mean, this is something that you had created personally,
[07:31] SPEAKER: which is indicative, you feel is indicative
[07:35] SPEAKER: of a certain specific part of game development.
[07:40] SPEAKER: But like sometimes I do worry that this is not a benchmark
[07:43] SPEAKER: that anyone could necessarily do on their own.
[07:46] SPEAKER: It's a lot of times it's like, hey, anybody could go down
[07:47] SPEAKER: and download Cinebench and compare scores.
[07:50] SPEAKER: Oh, what is my score versus your score?
[07:52] SPEAKER: It's open nature, but if this is like something
[07:54] SPEAKER: that was developed in house,
[07:56] SPEAKER: is that actually something beneficial to an end user?
[08:00] SPEAKER: - So you can, on this one, you can,
[08:04] SPEAKER: like you have to be a registered Unreal developer,
[08:06] SPEAKER: I think to download UE 5.3.2,
[08:09] SPEAKER: which is what I used for the benchmark.
[08:11] SPEAKER: The assets that I used are all either assets
[08:14] SPEAKER: that ship with the default, with their default UI,
[08:18] SPEAKER: like their default package or things that I had paid,
[08:23] SPEAKER: that I had attained a license to by either clicking the,
[08:26] SPEAKER: hey, this is free or, you know, like just like Epic does
[08:30] SPEAKER: for games that you download from the store,
[08:31] SPEAKER: for game developers, they also do asset packs
[08:33] SPEAKER: that are free all the time,
[08:34] SPEAKER: and if you go through and mash the,
[08:36] SPEAKER: like I just mash those buttons every day.
[08:38] SPEAKER: It's just a thing I do in the morning.
[08:40] SPEAKER: And then you end up getting a lot of like shrubbery
[08:41] SPEAKER: and stuff like that.
[08:42] SPEAKER: So the shrubs in the buildings were part
[08:44] SPEAKER: of one of those packages. - Shrubbery.
[08:46] SPEAKER: - And I believe that we can distribute that.
[08:49] SPEAKER: I'll have to double check, but Gordon has the benchmark
[08:52] SPEAKER: and the instructions for running it.
[08:54] SPEAKER: So like you all are welcome to use it.
[08:55] SPEAKER: Like it's your benchmark.
[08:56] SPEAKER: I developed it for you all at this point.
[08:59] SPEAKER: - Thank you.
[09:00] SPEAKER: Yeah, I guess for me though, yeah,
[09:02] SPEAKER: it's like the question we had somebody in our Discord ask,
[09:04] SPEAKER: like, is this something I could download and run on my own
[09:07] SPEAKER: so I can compare and contrast, you know?
[09:10] SPEAKER: - They could.
[09:11] SPEAKER: They'd have to sign up to be an Unreal developer.
[09:13] SPEAKER: So yeah, it's available.
[09:15] SPEAKER: It's really, really intensely multi-threaded
[09:19] SPEAKER: in a way that a lot of normal software that you use isn't.
[09:22] SPEAKER: Like it's like up there with video encoding
[09:23] SPEAKER: and raw photo processing and stuff like that.
[09:26] SPEAKER: - Like watch out 'cause it could burn down your house.
[09:28] SPEAKER: (upbeat music)
[09:32] SPEAKER: (upbeat music continues)
[09:56] SPEAKER: - Welcome to Brad and Will Made a Tech Pod.
[09:58] SPEAKER: I'm Will.
[09:59] SPEAKER: - And I'm Adam.
[10:01] SPEAKER: Adam's here.
[10:03] SPEAKER: Adam Patrick Murray of PC World is joining us today.
[10:05] SPEAKER: Brad is on assignment this week.
[10:07] SPEAKER: So we are going to, we normally would do Q&A right now
[10:13] SPEAKER: and Adam is good at answering A's.
[10:15] SPEAKER: I listened to him do A's answering on the full nerd
[10:17] SPEAKER: this week, the PC World podcast.
[10:19] SPEAKER: - Very nice.
[10:20] SPEAKER: - But instead I wanted to ask,
[10:23] SPEAKER: like we're coming out of Computex season.
[10:25] SPEAKER: So Computex is a big PC trade show,
[10:29] SPEAKER: PC specific trade show that happens
[10:31] SPEAKER: at the end of spring every year in Taiwan.
[10:34] SPEAKER: Adam you've been for what, a bunch of years at this point,
[10:37] SPEAKER: four or five years, six years?
[10:39] SPEAKER: - Well, my first one was in 2019
[10:41] SPEAKER: and then during the pandemic years, they didn't have them.
[10:44] SPEAKER: So I've only been to three.
[10:46] SPEAKER: I can't remember how many Gordon has been to,
[10:48] SPEAKER: but it's a number of them for sure.
[10:52] SPEAKER: - When I was at Maximum PC, we never went to Computex
[10:55] SPEAKER: because it was kind of expensive to travel to Taiwan.
[10:58] SPEAKER: - Yeah, that's a long flight.
[10:59] SPEAKER: Some people don't like that long flight either.
[11:01] SPEAKER: - Yeah, look, our international travel budget
[11:04] SPEAKER: at Maximum PC was like $4, which wouldn't get us there.
[11:07] SPEAKER: So I think when I asked when our boss was like,
[11:11] SPEAKER: yeah, if you can figure out a freighter you can stow away on,
[11:14] SPEAKER: you're welcome to go, we'll pay for the hotel
[11:15] SPEAKER: once you get there, but we're not paying for airplanes.
[11:20] SPEAKER: But yeah, so we've over the years,
[11:22] SPEAKER: I think one of the things I loved about the work
[11:26] SPEAKER: that the Giant Bomb guys did and what we did at Tested
[11:28] SPEAKER: and stuff like that was talking about,
[11:31] SPEAKER: we talked about the tech that comes out of this
[11:33] SPEAKER: on the PC World podcast.
[11:34] SPEAKER: Brad and I have talked about it a little bit.
[11:36] SPEAKER: It wasn't a huge consumer tech year
[11:39] SPEAKER: in terms of big announcements.
[11:42] SPEAKER: We got a little bit of a hint about what's coming
[11:44] SPEAKER: from the next Intel and AMD CPUs,
[11:47] SPEAKER: but that stuff wasn't really ready.
[11:48] SPEAKER: The Qualcomm Snapdragon Elite X SoC was announced
[11:55] SPEAKER: and kind of released almost immediately thereafter
[11:58] SPEAKER: and it's fine, I don't know that we're gonna do
[12:01] SPEAKER: an episode about that over here.
[12:02] SPEAKER: If you wanna hear about it, we've talked about it
[12:04] SPEAKER: on The Full Nerd a lot over the last couple of weeks.
[12:06] SPEAKER: - Oh yes, Gordon has been diving in real deep.
[12:10] SPEAKER: I know he's recording a video with his findings tomorrow,
[12:13] SPEAKER: so I'm excited to see that. - Oh cool.
[12:16] SPEAKER: But yeah, I think that stuff's interesting
[12:20] SPEAKER: and it comes and goes, but the thing that I love
[12:22] SPEAKER: to talk about, too, is that each trade show
[12:25] SPEAKER: has kind of its own vibe, right?
[12:27] SPEAKER: - Oh yeah, it really does.
[12:28] SPEAKER: - CES, E3, we've talked about both of those a lot.
[12:33] SPEAKER: Norm and Joey and I went to NAB a couple of times.
[12:35] SPEAKER: That was really fun and weird.
[12:36] SPEAKER: - Oh yes, yes.
[12:40] SPEAKER: - NAB is the National Association of Broadcasters
[12:41] SPEAKER: where Canon and Nikon and all the people
[12:44] SPEAKER: who make studio cameras for the Tonight Show
[12:47] SPEAKER: and your local news sell their stuff.
[12:50] SPEAKER: So we're walking in there and it's the same place
[12:53] SPEAKER: that CES happens.
[12:54] SPEAKER: I don't think we really appreciated this,
[12:56] SPEAKER: but they have demo booths set up
[12:59] SPEAKER: that are like local news booths or like a sitcom booth
[13:04] SPEAKER: so you can demo their production cameras live
[13:06] SPEAKER: and it was just super fun.
[13:08] SPEAKER: It was a really fun, goofy thing to walk around and do.
[13:10] SPEAKER: - They would hire models to just sit in these scenarios, too.
[13:14] SPEAKER: The funny thing is I used to review the cameras
[13:18] SPEAKER: on smartphones years ago on one of our sister channels.
[13:21] SPEAKER: I had a series called Last Cam Standing,
[13:24] SPEAKER: which as a photographer I would go real deep
[13:27] SPEAKER: into the testing of smartphone cameras,
[13:29] SPEAKER: which was real fun.
[13:30] SPEAKER: I miss doing it, honestly.
[13:31] SPEAKER: But a couple times we attended NAB as a company
[13:37] SPEAKER: just to attend it, which was kind of cool
[13:39] SPEAKER: to go to a trade show and not have to cover it.
[13:40] SPEAKER: We were just there to experience it, which was cool.
[13:43] SPEAKER: But I actually got to use a lot of those sets
[13:45] SPEAKER: for my camera testing at the same time,
[13:48] SPEAKER: which, hey, it worked out.
[13:50] SPEAKER: It was perfect.
[13:51] SPEAKER: - It's awesome.
[13:51] SPEAKER: They had studio lights set up
[13:54] SPEAKER: and they had outdoor lights set up.
[13:55] SPEAKER: It was really, we went to that more or less as attendees
[13:59] SPEAKER: rather than coverings.
[14:00] SPEAKER: I think we made like three videos out of there,
[14:02] SPEAKER: which was low for us.
[14:04] SPEAKER: We went to the coffee convention, which was amazing
[14:06] SPEAKER: because that was where the best baristas in the world
[14:09] SPEAKER: come to show off the stuff that they're most awesome at
[14:12] SPEAKER: and the espresso machine vendors and the brewed coffee.
[14:17] SPEAKER: It was fun.
[14:17] SPEAKER: It was a fun show that was like,
[14:22] SPEAKER: during the day you drank a ton of coffee
[14:23] SPEAKER: and then in the night everybody went to bars
[14:25] SPEAKER: and drank a whole lot of booze
[14:27] SPEAKER: 'cause you had to kind of even it out through the,
[14:29] SPEAKER: or else your heart would explode on the third day.
[14:32] SPEAKER: It was a good time.
[14:33] SPEAKER: - Well, actually, I guess,
[14:35] SPEAKER: do you think people understand the difference
[14:36] SPEAKER: between a trade show and like a convention?
[14:39] SPEAKER: 'Cause I think a lot of people have been to,
[14:41] SPEAKER: or have thought of like a San Diego Comic-Con
[14:44] SPEAKER: or a TwitchCon or Anime Expo
[14:46] SPEAKER: or something like that versus a trade show,
[14:50] SPEAKER: which, I mean, even some trade shows are more,
[14:53] SPEAKER: some are more business and some are more like actual,
[14:56] SPEAKER: like coming to look at announcements like media coverage.
[15:00] SPEAKER: Do you think people really know the difference?
[15:02] SPEAKER: - Like, I don't, you know, 20 years ago
[15:04] SPEAKER: I could have given you a really good definition
[15:05] SPEAKER: about whether you were there to sell stuff
[15:07] SPEAKER: and whether you were looking at buyers for big markets
[15:09] SPEAKER: and stuff like that.
[15:10] SPEAKER: And I think now they've kind of merged,
[15:12] SPEAKER: like it depends on the market.
[15:14] SPEAKER: Like NAB, definitely a trade show, right?
[15:16] SPEAKER: Like people are there with their products.
[15:18] SPEAKER: There's like guys with suits on and they like,
[15:21] SPEAKER: they have a clip, they have a laptop
[15:23] SPEAKER: that they can take your order on
[15:25] SPEAKER: or like it's an opportunity for you to engage
[15:27] SPEAKER: with the sales department of a big giant company.
[15:30] SPEAKER: E3, when at E3, the last time I went to E3
[15:33] SPEAKER: felt like somewhere of a, somewhat of a split
[15:36] SPEAKER: between a con and a trade show, right?
[15:39] SPEAKER: It was like-- - Yeah, for better or worse.
[15:41] SPEAKER: - Yeah, but it was almost a giant press event more than,
[15:45] SPEAKER: like it's not like the Walmart buyer was walking around
[15:47] SPEAKER: being like, okay, we're gonna buy 30,000 units
[15:50] SPEAKER: of Assassin's Creed this year.
[15:51] SPEAKER: We're gonna buy 10,000 units of Halo Infinite.
[15:54] SPEAKER: We're, you know, like that's what that used to be like
[15:58] SPEAKER: and I don't feel like that had happened at E3
[16:01] SPEAKER: in a really long time.
[16:02] SPEAKER: - Yeah, well, and I've never been,
[16:04] SPEAKER: but I've heard Gamescom like actually has separate days
[16:07] SPEAKER: for trade versus public, which is kind of interesting too.
[16:12] SPEAKER: - That's what happened with E3 at the end too.
[16:13] SPEAKER: Like the end of E3, the first couple of days
[16:16] SPEAKER: were press and industry, and then the last couple of days
[16:18] SPEAKER: were just like you'd buy a $50 ticket
[16:20] SPEAKER: if you lived in LA and go.
[16:22] SPEAKER: And Gamescom does work the same way.
[16:24] SPEAKER: - Well, I can say, so for Computex,
[16:26] SPEAKER: I mean, Computex, it's all about the computer,
[16:29] SPEAKER: a lot of computational stuff,
[16:31] SPEAKER: but there are different levels in it from what I've seen.
[16:35] SPEAKER: Like you have the consumer end,
[16:36] SPEAKER: which is what we cover on PC World,
[16:38] SPEAKER: but there is plenty of stuff for server grade
[16:41] SPEAKER: and large AI kind of stuff.
[16:44] SPEAKER: Like I would say in a lot of ways,
[16:46] SPEAKER: a lot of those companies were focused on B2B kind of stuff
[16:50] SPEAKER: where we're there more for the consumer stuff.
[16:52] SPEAKER: And Computex specifically, their last day
[16:56] SPEAKER: is open to the public, but that's how they integrate
[16:59] SPEAKER: some people, and the crowds were definitely different.
[17:00] SPEAKER: You could feel the difference in the crowd,
[17:03] SPEAKER: but it still wasn't quite like a public day
[17:06] SPEAKER: at a convention or even E3.
[17:10] SPEAKER: I went to one of the final E3s too,
[17:12] SPEAKER: and yeah, it did not feel like that either.
[17:15] SPEAKER: It still felt like mostly work,
[17:17] SPEAKER: people there to do serious work.
[17:19] SPEAKER: - Yeah, and like for a trade show,
[17:24] SPEAKER: the idea that there would be like a big mob,
[17:28] SPEAKER: like if you've been to San Diego Comic-Con,
[17:30] SPEAKER: that you can get into places on the show floor there
[17:33] SPEAKER: that there's just so many people you can't move around,
[17:35] SPEAKER: right, like you just kind of have to get
[17:37] SPEAKER: in the flow of traffic and walk with them.
[17:40] SPEAKER: And there's a couple, like CES has a couple of bottlenecks
[17:43] SPEAKER: that are like that pretty consistently,
[17:45] SPEAKER: but for the most part, there's room to move around.
[17:47] SPEAKER: You can go and you can talk to somebody at a booth.
[17:49] SPEAKER: It's not just a massive crush of people all the time
[17:52] SPEAKER: like there is at Comic-Con.
[17:53] SPEAKER: - And Computex is the same kind of way.
[17:55] SPEAKER: I actually, it was definitely crowded for sure,
[17:57] SPEAKER: and it depended on what booth you were going into,
[18:00] SPEAKER: but for the most part, we could navigate it
[18:02] SPEAKER: except for there was one specific time
[18:05] SPEAKER: during the opening day where two people came through
[18:09] SPEAKER: and security surrounded and just blocked
[18:12] SPEAKER: the flow of traffic.
[18:13] SPEAKER: It was like everything was like to a standstill
[18:16] SPEAKER: and it was very infuriating.
[18:19] SPEAKER: Can you guess what those two people were?
[18:21] SPEAKER: They weren't together.
[18:21] SPEAKER: They were like one came through
[18:23] SPEAKER: and then the next one came through.
[18:24] SPEAKER: - Was it Jen Sun?
[18:27] SPEAKER: - Yeah, one of them was the CEO of Nvidia, Jen Sun Wong.
[18:32] SPEAKER: The other one was the president of Taipei.
[18:35] SPEAKER: So yeah, they actually came through and like that.
[18:39] SPEAKER: I had never seen anything like completely shut down
[18:42] SPEAKER: like that before in the middle of a trade show
[18:44] SPEAKER: with the spectacle and the security
[18:47] SPEAKER: and everybody taking photos and all that kind of stuff.
[18:49] SPEAKER: That was definitely a new experience for me
[18:53] SPEAKER: at this Computex.
[18:54] SPEAKER: - So it's funny, I feel like politicians
[18:57] SPEAKER: used to come to Comdex, which was kind of
[19:00] SPEAKER: the last North American computer trade show
[19:05] SPEAKER: that I think the last one of those was in '98 or '99,
[19:08] SPEAKER: maybe 2000, it was early this millennium.
[19:13] SPEAKER: But yeah, so okay, Computex is all about computers.
[19:18] SPEAKER: I didn't realize that there were,
[19:19] SPEAKER: I thought it was all consumer stuff.
[19:21] SPEAKER: I didn't realize that you were consumer and B2B.
[19:23] SPEAKER: I didn't realize that there were like servers
[19:25] SPEAKER: and data center stuff and all that kind of stuff there too.
[19:27] SPEAKER: - Oh yeah, I mean, so there's two,
[19:32] SPEAKER: the actual Nongong Convention Center has two buildings
[19:36] SPEAKER: and then the main one has two floors.
[19:41] SPEAKER: Like in, usually the consumer stuff is on the top floor
[19:44] SPEAKER: of one of the buildings,
[19:46] SPEAKER: but the rest of it is B2B stuff.
[19:49] SPEAKER: But even on the consumer floor,
[19:51] SPEAKER: like there's a company like Asus
[19:52] SPEAKER: who has a lot of B2B work, you know, customers,
[19:57] SPEAKER: but then also a lot of consumer grade.
[19:59] SPEAKER: And not only did they have some of it separate,
[20:01] SPEAKER: like Asus had a separate ROG booth
[20:04] SPEAKER: for their gaming stuff versus their Asus proper stuff.
[20:07] SPEAKER: But even in the Asus proper,
[20:09] SPEAKER: they had like large data centers
[20:12] SPEAKER: with the latest Nvidia workstation server grade stuff
[20:17] SPEAKER: in there alongside their pro art,
[20:19] SPEAKER: consumer based creation tools and things like that.
[20:23] SPEAKER: So it was very integrated into it,
[20:27] SPEAKER: even though we're there mostly for the consumer stuff, so.
[20:31] SPEAKER: - So, okay, so like at E3,
[20:34] SPEAKER: your big booths are like your big publishers
[20:37] SPEAKER: in your platform.
[20:38] SPEAKER: So it's like Sony and Microsoft and EA
[20:39] SPEAKER: and like once upon a time Activision
[20:42] SPEAKER: and Ubisoft and all those.
[20:43] SPEAKER: At CES, it's like, you know, CES is consumer electronics.
[20:47] SPEAKER: So for a long time it was Intel and Microsoft
[20:49] SPEAKER: and Panasonic and Samsung and--
[20:53] SPEAKER: - LG usually has a pretty big booth.
[20:55] SPEAKER: - LG and folks like that.
[20:57] SPEAKER: And like, they're selling everything
[20:59] SPEAKER: from like washing machines and dryers
[21:01] SPEAKER: and robot vacuums.
[21:02] SPEAKER: - TVs. - Like LG, yeah,
[21:03] SPEAKER: to TVs and phones.
[21:06] SPEAKER: What are the big booths at Computex?
[21:10] SPEAKER: - So for the consumer stuff specifically,
[21:13] SPEAKER: it kind of culminated on that second floor in the middle
[21:16] SPEAKER: and there was four major booths.
[21:19] SPEAKER: Two of them were Asus.
[21:20] SPEAKER: Like I said, one of them was ROG,
[21:22] SPEAKER: the other one was more Asus, brand Asus.
[21:25] SPEAKER: The other one was Gigabyte and the last one was MSI.
[21:28] SPEAKER: So that was kind of like the dead center of the floor.
[21:32] SPEAKER: You could stand there right in the middle
[21:34] SPEAKER: and you're just like looking at these huge booths
[21:36] SPEAKER: surrounding you.
[21:38] SPEAKER: Those were the main four that were huge.
[21:41] SPEAKER: - It's amazing to me that it's motherboard
[21:43] SPEAKER: and video card companies.
[21:44] SPEAKER: I mean, I guess Asus sells PCs as well, laptops as well.
[21:49] SPEAKER: Do Gigabyte do PCs or are they just components?
[21:55] SPEAKER: - That is a good question.
[21:56] SPEAKER: They do have laptops.
[21:57] SPEAKER: They were showing off laptop stuff there.
[21:58] SPEAKER: I can't remember if they do pre-builts or not.
[22:01] SPEAKER: That's actually a good question, but mostly laptops.
[22:04] SPEAKER: - Yeah, yeah.
[22:05] SPEAKER: I mean, I think laptops are--
[22:06] SPEAKER: - And monitors and all that kind of stuff.
[22:08] SPEAKER: So I would say laptop was definitely a huge focus there.
[22:12] SPEAKER: Obviously, there's the whole Snapdragon stuff.
[22:14] SPEAKER: Intel announced Lunar Lake.
[22:16] SPEAKER: You know, AMD announced their new Ryzen AI 300 series.
[22:20] SPEAKER: I mean, there was a lot of news, but yeah,
[22:22] SPEAKER: the major vendors like Intel, AMD and Nvidia
[22:27] SPEAKER: didn't really have booths there.
[22:28] SPEAKER: They were partnered with certain booths.
[22:30] SPEAKER: Like, they definitely had presences there
[22:33] SPEAKER: and a lot of them were official keynotes of Computex.
[22:38] SPEAKER: So their impact was very much felt, but yeah,
[22:41] SPEAKER: it's not like you could walk up to an Intel booth
[22:44] SPEAKER: and check out all their laptops or an Nvidia booth
[22:47] SPEAKER: and check out all their GPUs and things like that.
[22:51] SPEAKER: - It kind of makes less, it's conceptually interesting
[22:55] SPEAKER: to me that there's like a booth for motherboard.
[22:57] SPEAKER: Like, I mean, I guess that's not fair
[22:59] SPEAKER: 'cause Asus, I'm sure, sells way more laptops
[23:01] SPEAKER: than they sell enthusiast motherboards at this point.
[23:04] SPEAKER: - 100%, yeah.
[23:05] SPEAKER: - Yeah, several orders of magnitude probably.
[23:08] SPEAKER: But it's interesting 'cause it's a thing that like,
[23:12] SPEAKER: I haven't been to a PC trade show since Computex shut down
[23:16] SPEAKER: in like 2019, sorry, 1999 or 2000, right?
[23:22] SPEAKER: - I mean, it's fun.
[23:23] SPEAKER: Like, I love it and that's, I mean,
[23:25] SPEAKER: I love Computex for a number of reasons,
[23:27] SPEAKER: but being there specifically just for everyone
[23:31] SPEAKER: to celebrate the PC is awesome.
[23:34] SPEAKER: Like, whether you are in laptops or DIY desktops,
[23:39] SPEAKER: even the server grade stuff,
[23:40] SPEAKER: like everyone's there for computing and rah, rah, yes.
[23:45] SPEAKER: Hardware is amazing,
[23:47] SPEAKER: which is definitely different than the CES.
[23:50] SPEAKER: CES is like all tech and while there is a lot of PC stuff
[23:55] SPEAKER: that we cover at CES, none of it is on any show floor.
[24:00] SPEAKER: It's like all meetings and we're going
[24:02] SPEAKER: from like meeting to meeting where Computex
[24:05] SPEAKER: is really the only trade show that you can go
[24:08] SPEAKER: on a show floor and just see PC stuff.
[24:11] SPEAKER: So that is definitely like a huge difference that I love,
[24:14] SPEAKER: one of the reasons why I love Computex.
[24:16] SPEAKER: - Yeah, at CES, the PC stuff always felt like
[24:20] SPEAKER: a little bit of, it's not an afterthought
[24:22] SPEAKER: 'cause it's not exactly fair, but like they'd be like,
[24:25] SPEAKER: oh, by the way, when you asked to see PC stuff,
[24:27] SPEAKER: they acted, the people who were doing booth tours
[24:30] SPEAKER: or whatever were always like, oh,
[24:32] SPEAKER: oh, well, let me go find somebody.
[24:33] SPEAKER: I don't know who you talked to about that
[24:35] SPEAKER: 'cause we were the first people who asked about that, right?
[24:37] SPEAKER: - Oh, wow, okay, yeah.
[24:39] SPEAKER: - Or you were in some like far away end
[24:41] SPEAKER: of the convention hall where like you had to go
[24:45] SPEAKER: to the West Hall and then go upstairs to the very far back
[24:48] SPEAKER: and then there'd be like, Ace Tech would be back there
[24:51] SPEAKER: with a bunch of all-in-one coolers that they were selling
[24:54] SPEAKER: to other OEMs, not even to consumers, so.
[24:57] SPEAKER: - That's funny.
[24:58] SPEAKER: Well, yeah, like I actually had a personal goal of mine
[25:02] SPEAKER: to never go to the Las Vegas Convention Center during CES
[25:07] SPEAKER: 'cause we never had to.
[25:08] SPEAKER: So I've been going to CES since 2016
[25:11] SPEAKER: and there's only been one time that I've ever set foot
[25:15] SPEAKER: in Las Vegas Convention Center proper
[25:18] SPEAKER: because that's not where the PC stuff is.
[25:21] SPEAKER: Like Las Vegas Convention Center with the three huge halls,
[25:24] SPEAKER: like we said earlier, it's all refrigerators and TVs
[25:28] SPEAKER: and more consumer-based stuff.
[25:31] SPEAKER: They've now expanded also, or I mean, not now,
[25:34] SPEAKER: but a number of years ago, they expanded out into the,
[25:37] SPEAKER: what used to be called the Sands Expo.
[25:39] SPEAKER: Now it's the Venetian Expo Center
[25:41] SPEAKER: and that is usually more like smart home
[25:44] SPEAKER: or biohacking, like smart watches
[25:48] SPEAKER: and fitness kind of stuff. - Rings, yeah.
[25:51] SPEAKER: - So that's kind of the show floor for that stuff
[25:54] SPEAKER: and then most of the PC vendors,
[25:59] SPEAKER: whether it's desktop or laptop,
[26:00] SPEAKER: usually have meeting rooms at the Sands meeting.
[26:05] SPEAKER: There's like an offshoot off to the side of the show floor
[26:08] SPEAKER: that's just like all meeting rooms.
[26:09] SPEAKER: So there's a lot going on there for damn sure,
[26:12] SPEAKER: but not like Computex.
[26:13] SPEAKER: Computex usually get to show up
[26:14] SPEAKER: and look around and be amazed by the spectacle.
[26:18] SPEAKER: - Well, and it's also the place
[26:21] SPEAKER: that like case manufacturers come, right?
[26:23] SPEAKER: So like for your enthusiast PC builder,
[26:27] SPEAKER: which I think is of interest
[26:28] SPEAKER: to the tech pod audience probably,
[26:30] SPEAKER: like you have your fractals and your Leon Lees
[26:34] SPEAKER: and your cooler masters all are set up
[26:37] SPEAKER: with their new hotness for the next year
[26:40] SPEAKER: and you get to kind of see the future
[26:42] SPEAKER: of what cases look like, right?
[26:44] SPEAKER: - Yeah, well, and we have a couple new people on our team.
[26:48] SPEAKER: This was their first time going to a Computex
[26:50] SPEAKER: and a lot of them joked, they were like,
[26:52] SPEAKER: oh my god, everyone has a cooler.
[26:54] SPEAKER: Who doesn't make a cooler?
[26:55] SPEAKER: 'Cause a lot of these vendors
[26:57] SPEAKER: that specialize in something else also were like,
[27:00] SPEAKER: oh yeah, we also have either an AIO
[27:02] SPEAKER: or some air tower cooler. (laughs)
[27:05] SPEAKER: - Yeah, all I can figure is the margins
[27:07] SPEAKER: on AIOs must be real good.
[27:09] SPEAKER: - Well, hey, Zalman still had a booth there.
[27:12] SPEAKER: They were showing off new stuff,
[27:14] SPEAKER: but they still had their typical copper,
[27:18] SPEAKER: what was the name of that?
[27:20] SPEAKER: Just kind of like fanned out CPU.
[27:22] SPEAKER: - Oh, the onion thing?
[27:23] SPEAKER: - Yeah, yeah, yeah, Leo, I don't know how to describe it,
[27:25] SPEAKER: but it's a classic Zalman CPU cooler.
[27:30] SPEAKER: - Yeah, they were always doing low profile
[27:33] SPEAKER: and like really efficient air coolers.
[27:37] SPEAKER: They often would come out of Computex in the old days
[27:40] SPEAKER: with like, hey, we built a case
[27:42] SPEAKER: that's completely passively cooled.
[27:43] SPEAKER: No fans needed it, and you had some crazy heat pipe thing
[27:47] SPEAKER: that went from the CPU up onto the case,
[27:50] SPEAKER: and then the case had a bunch
[27:50] SPEAKER: of aluminum radiator fins on it,
[27:53] SPEAKER: so the whole thing would just get kind of warm.
[27:57] SPEAKER: I don't think it would work
[27:58] SPEAKER: in the modern era, unfortunately.
[27:59] SPEAKER: - Actually, no, there were some manufacturers
[28:02] SPEAKER: who were, I would say, one of the spectacles
[28:04] SPEAKER: at a lot of these booths to get people in,
[28:08] SPEAKER: regardless of whether they were looking
[28:09] SPEAKER: for that company's specific product or not,
[28:12] SPEAKER: was a lot of these booths had hired people to do case mods.
[28:17] SPEAKER: We didn't do one this year,
[28:18] SPEAKER: but last year we actually did a big roundup
[28:20] SPEAKER: of all the case mods that we saw that were cool,
[28:22] SPEAKER: so there was a lot of cool stuff to be had there.
[28:26] SPEAKER: Last year, somebody had built a computer
[28:28] SPEAKER: inside of one of the alien eggs.
[28:31] SPEAKER: - Oh, wow.
[28:32] SPEAKER: - Which was, and then had dry ice coming out of the top
[28:35] SPEAKER: kind of thing, or, yeah, it was, yeah.
[28:37] SPEAKER: Case mods, I am not into case mods myself
[28:41] SPEAKER: 'cause I'm not inclined to work on things like that,
[28:46] SPEAKER: but yeah, there's definitely a lot of cool people
[28:49] SPEAKER: that do cool stuff, and you walk by and you're like,
[28:50] SPEAKER: oh my god, that's a computer?
[28:52] SPEAKER: That's pretty awesome.
[28:54] SPEAKER: - Like, that, the attention to spectacle,
[28:57] SPEAKER: and there used to be, I don't know if they still do this,
[29:00] SPEAKER: but this was, I think this was Gordon's theory,
[29:04] SPEAKER: was that case manufacturers especially
[29:06] SPEAKER: would gin up something that would be impossible
[29:08] SPEAKER: to manufacture, they would show off at Computex
[29:11] SPEAKER: just as a red herring, so everybody else would try
[29:13] SPEAKER: to knock it off and then run, you know,
[29:16] SPEAKER: the tooling costs would run them out of business
[29:18] SPEAKER: theoretically, just cause speed bumps for each other,
[29:21] SPEAKER: chasing impossible-to-manufacture products.
[29:24] SPEAKER: And I mean, I think that used to be the case,
[29:27] SPEAKER: but now I think we're good enough at manufacturing
[29:29] SPEAKER: that there's not really a whole lot that's impossible
[29:31] SPEAKER: to manufacture anymore.
[29:33] SPEAKER: - Yeah, and I would say the, at least since I've been going
[29:37] SPEAKER: to CES and Computex and these kind of trade shows,
[29:40] SPEAKER: the last company that would do spectacle
[29:43] SPEAKER: just for spectacle's sake was like Razer.
[29:45] SPEAKER: Like, usually they would come to a CES
[29:48] SPEAKER: and have some sort of like design that they were like,
[29:51] SPEAKER: you know, kind of cagey about whether this was gonna
[29:53] SPEAKER: come out or not, but it was like the thing of like,
[29:55] SPEAKER: oh my god, did you see what Razer made?
[29:57] SPEAKER: But even they've kind of fallen by the wayside on that.
[30:01] SPEAKER: We don't really see that too much anymore
[30:03] SPEAKER: of like, just really like, you know,
[30:07] SPEAKER: going crazy with something design-wise.
[30:11] SPEAKER: - Yeah, I remember Razer brought a Proto Steam Deck thing
[30:14] SPEAKER: like 12 years ago, 13 years, a long, long time ago to CES.
[30:19] SPEAKER: And it was like, it was a slab computer with two handles
[30:23] SPEAKER: on the side that had their kind of crappy controllers,
[30:25] SPEAKER: sticks on it, and they were like, look, yeah,
[30:27] SPEAKER: you can play games on this thing.
[30:28] SPEAKER: And then I think that shipped, I'd have to go look,
[30:31] SPEAKER: I don't even remember.
[30:33] SPEAKER: But it was, yeah, it feels, I don't know,
[30:37] SPEAKER: it's, I'm interested, so who's, I guess who's not there?
[30:41] SPEAKER: Like Dell and HP and the big American PC vendors there?
[30:45] SPEAKER: - I mean, this is definitely a place for trade shows to,
[30:50] SPEAKER: or I'm sorry, companies that are Asian-based
[30:53] SPEAKER: to kind of like show off, and there's a lot of like,
[30:56] SPEAKER: just to be frank, still like traditions that are not
[31:00] SPEAKER: as accepted in the US.
[31:01] SPEAKER: Like actually there are still a lot of booth babes.
[31:04] SPEAKER: There's a lot of like big flower arrangements
[31:07] SPEAKER: that companies will get at their booths.
[31:10] SPEAKER: You know, it was like, oh hey, congratulations
[31:12] SPEAKER: of what you showed off at the booth.
[31:13] SPEAKER: So, you know, some of it is definitely cultural
[31:17] SPEAKER: in a lot of Asian-based companies.
[31:19] SPEAKER: Most major manufacturers are there in some sort.
[31:22] SPEAKER: Like I said, like Intel, AMD, Nvidia
[31:25] SPEAKER: didn't have their own booth,
[31:27] SPEAKER: but they definitely had a presence there.
[31:29] SPEAKER: There were a couple companies, like actually,
[31:31] SPEAKER: now that I think about it, Razor,
[31:33] SPEAKER: Razor doesn't go to Computex.
[31:35] SPEAKER: So there are definitely some companies
[31:37] SPEAKER: that just don't show up for Computex.
[31:39] SPEAKER: And I don't know if that's because they don't sell
[31:41] SPEAKER: in those markets, in Asian markets,
[31:43] SPEAKER: or I think they just, I mean, especially in today's age,
[31:47] SPEAKER: a lot of these companies have been like,
[31:48] SPEAKER: eh, we can put on our own event and not have to worry
[31:51] SPEAKER: about going to a big trade show.
[31:52] SPEAKER: So there is some of that even.
[31:54] SPEAKER: - And Razor is less B2B and more consumer product, right?
[31:58] SPEAKER: It's not like you're selling your Razor gaming laptop
[32:01] SPEAKER: into your Fortune 500 company, probably.
[32:03] SPEAKER: - True, true, yeah, yeah.
[32:06] SPEAKER: So I would say for the most part,
[32:08] SPEAKER: I mean, representation is pretty big.
[32:10] SPEAKER: Now, I will say there are some companies
[32:12] SPEAKER: that don't exhibit at the show proper, right?
[32:17] SPEAKER: Kind of like E3, and I know we keep coming back
[32:19] SPEAKER: to that analogy, but yeah, like at some point,
[32:21] SPEAKER: EA peeled away from E3 proper.
[32:25] SPEAKER: They still put on an event at the same time as E3,
[32:28] SPEAKER: but it wasn't actually part of E3.
[32:31] SPEAKER: Same thing kinda happens here.
[32:32] SPEAKER: There are a lot of companies who are like,
[32:33] SPEAKER: eh, we don't wanna pay for a booth on the show floor
[32:37] SPEAKER: or something like that, so we're having our own event.
[32:40] SPEAKER: Like, we went to Fractal Design,
[32:42] SPEAKER: which makes a lot of popular cases,
[32:45] SPEAKER: and they had an event on the 88th floor
[32:49] SPEAKER: of the Taipei 101 this year, so they were at the show.
[32:53] SPEAKER: I mean, but they were at the show, so, yeah.
[32:58] SPEAKER: - Like, what are those events like?
[32:59] SPEAKER: Like, at CES, those events are often like,
[33:02] SPEAKER: hey, we're gonna have a CEO stand up
[33:04] SPEAKER: and talk for like five minutes,
[33:06] SPEAKER: and then there'll be hors d'oeuvres,
[33:07] SPEAKER: and you could take pictures of the hardware, maybe.
[33:10] SPEAKER: Talk to engineers if you're really lucky,
[33:12] SPEAKER: or is it the same kind of vibes, or is it?
[33:15] SPEAKER: - I would say it is mostly tailored
[33:17] SPEAKER: for people to come in and get content.
[33:20] SPEAKER: For the most part, like, I went to an NZXT appointment,
[33:23] SPEAKER: and NZXT had everything from their cases
[33:26] SPEAKER: to their new fans to, you know, like,
[33:28] SPEAKER: they actually had a historical thing
[33:30] SPEAKER: 'cause NZXT hit 20 years.
[33:32] SPEAKER: So they had old NZXT cases, like on a timeline kinda thing,
[33:37] SPEAKER: which was pretty cool, so usually they kinda know
[33:40] SPEAKER: that the audience is there to get,
[33:42] SPEAKER: or at least the media are there to get information
[33:46] SPEAKER: and to either make videos like us or write articles,
[33:49] SPEAKER: get photos, all that kinda stuff.
[33:51] SPEAKER: Fractal was actually the only event or briefing
[33:56] SPEAKER: that I went to that actually had us sit down in chairs,
[33:59] SPEAKER: and they had a PowerPoint presentation on the projector.
[34:03] SPEAKER: That's always the worst, just to be honest.
[34:05] SPEAKER: Nothing against fractal, I love fractal,
[34:07] SPEAKER: but I've been to plenty of those kind of events
[34:09] SPEAKER: where, like, you're up on your feet all day,
[34:12] SPEAKER: you have limited sleep, and then they sit you down
[34:14] SPEAKER: to do a PowerPoint presentation, and inevitably,
[34:17] SPEAKER: somebody starts snoring, not to be rude,
[34:20] SPEAKER: it's just everybody's tired, so a lot of times
[34:23] SPEAKER: that is kind of like, oh, please don't do that.
[34:25] SPEAKER: Just bring us in and, you know, kinda show the stuff.
[34:29] SPEAKER: - Well, like, if you have tangible things to touch,
[34:33] SPEAKER: it's always better to handle, like,
[34:35] SPEAKER: let us handle the hardware.
[34:36] SPEAKER: I wanna see the hardware and actually get it,
[34:38] SPEAKER: like, be able to touch it and open it up
[34:40] SPEAKER: and look at it and poke at it if that's possible.
[34:42] SPEAKER: And it's the reason you come to the event.
[34:45] SPEAKER: Like, you could've looked at a presentation on a Zoom.
[34:48] SPEAKER: - Yeah, yeah, and especially for desktop,
[34:51] SPEAKER: DIY desktop builders, like, it is important
[34:54] SPEAKER: to kinda get your hands on something
[34:56] SPEAKER: and feel what it's gonna be like to, you know,
[34:59] SPEAKER: maybe potentially build with it, and that's a lot
[35:02] SPEAKER: of the way that we cover our stuff is like,
[35:04] SPEAKER: hey, you know, what's announced?
[35:06] SPEAKER: What are the key facts about it?
[35:07] SPEAKER: How does it feel initially to kind of build in?
[35:10] SPEAKER: - Unfortunately, like a lot of things, I mean,
[35:13] SPEAKER: companies, maybe they announced a product,
[35:15] SPEAKER: it doesn't come out 'til fall,
[35:17] SPEAKER: so all they have are engineering samples,
[35:18] SPEAKER: so you're still kind of taking some things
[35:20] SPEAKER: with a grain of salt and, I mean, kinda like at E3,
[35:23] SPEAKER: you show up to a game demo and you're like,
[35:24] SPEAKER: well, the game's not final, so there could be bugs.
[35:27] SPEAKER: So, you know, that even happens in this space too, for sure.
[35:31] SPEAKER: So it's definitely interesting,
[35:34] SPEAKER: but usually pretty representative of what, like,
[35:37] SPEAKER: final products are gonna be like.
[35:39] SPEAKER: Very rarely is something behind a case,
[35:42] SPEAKER: or like a glass case, and you're like,
[35:44] SPEAKER: you can't touch it, except for, I will say this year,
[35:48] SPEAKER: Intel put their new Lunar Lake laptops behind glass
[35:53] SPEAKER: and didn't let anybody touch them.
[35:55] SPEAKER: They announced it, and they had laptops at booths,
[35:58] SPEAKER: but they were all behind glass, which was very odd.
[36:02] SPEAKER: - So people couldn't, like, get hands-on
[36:04] SPEAKER: and run benchmarks on 'em, you think,
[36:06] SPEAKER: or was it something from--
[36:08] SPEAKER: - I heard from multiple vendors that, yes,
[36:11] SPEAKER: that was a problem with Meteor Lake,
[36:12] SPEAKER: their previous launch, is that people were getting a,
[36:16] SPEAKER: you know, kind of pulling it off to the side,
[36:17] SPEAKER: running a quick benchmark and gathering some information
[36:21] SPEAKER: based off of, you know, pre-release drivers
[36:23] SPEAKER: and pre-release hardware kinda stuff,
[36:24] SPEAKER: and then coming to a conclusion and, you know, kinda thing,
[36:27] SPEAKER: and so Intel was very much like,
[36:29] SPEAKER: we don't want that this time, so, which,
[36:32] SPEAKER: but then on the other side, that's kind of a bummer for us,
[36:34] SPEAKER: because we couldn't get our hands on the hardware.
[36:37] SPEAKER: We couldn't get any sort of viable information
[36:40] SPEAKER: of like, okay, this is what it feels like to use,
[36:42] SPEAKER: so it's a double-edged sword, right?
[36:45] SPEAKER: You know, every company kind of has
[36:47] SPEAKER: their own different way to do it.
[36:49] SPEAKER: Usually they err on the side of,
[36:51] SPEAKER: hey, here's what we're showing,
[36:52] SPEAKER: and here's what you can mess with,
[36:55] SPEAKER: but this year, Intel was a little more cagey.
[36:58] SPEAKER: - Well, it means if, like, a laptop vendor
[37:00] SPEAKER: does something novel with their physical design,
[37:03] SPEAKER: you're not gonna get the opportunity to handle it,
[37:04] SPEAKER: which stinks.
[37:06] SPEAKER: - Well, and I mean, a good example is I love handhelds.
[37:09] SPEAKER: Like, that's definitely one of my coverage zones
[37:11] SPEAKER: at PC World, handheld PC gaming.
[37:13] SPEAKER: - Steam Deck, Ally. - Steam Deck, ROT Ally,
[37:16] SPEAKER: all that kind of stuff.
[37:17] SPEAKER: Yeah, so the MSI Claw, they announced a new version,
[37:20] SPEAKER: an eight-inch version, called the Claw 8 AI Plus,
[37:26] SPEAKER: 'cause they figured out a way to put AI in the computer,
[37:29] SPEAKER: which is fun. - Thank goodness.
[37:31] SPEAKER: - Who would've thought?
[37:32] SPEAKER: - How many tops? - We have AI
[37:33] SPEAKER: in the computer.
[37:34] SPEAKER: - 48, 50, 52, what are we talking about here?
[37:37] SPEAKER: - Well, so it was a lunar lake-based design,
[37:41] SPEAKER: so they were like, hey, we can't wait to show you
[37:43] SPEAKER: this new handheld, but I literally couldn't even
[37:46] SPEAKER: put it in my hand to feel how the handheld, you know,
[37:50] SPEAKER: was just like, is it comfortable, is it heavy?
[37:54] SPEAKER: You know, like, what are the ergonomics?
[37:56] SPEAKER: - How do the sticks feel? - Exactly, yeah,
[37:58] SPEAKER: 'cause lunar lake was inside, and because Intel asked,
[38:02] SPEAKER: you know, all the vendors to have a lunar lake behind glass,
[38:04] SPEAKER: so that was definitely a real big bummer.
[38:09] SPEAKER: - You mentioned this a minute ago,
[38:10] SPEAKER: and I wanna circle back.
[38:11] SPEAKER: I love when a vendor has either like, hey,
[38:14] SPEAKER: here are all of our, here's the timeline of our products
[38:18] SPEAKER: through the ages.
[38:19] SPEAKER: I remember Cooler Master did a case layout once
[38:21] SPEAKER: where they had like, hey, here's our first aluminum case
[38:22] SPEAKER: up to the modern stuff.
[38:24] SPEAKER: My all-time favorite of that is when Valve
[38:27] SPEAKER: launched the Vive at GDC in 2015, I think.
[38:32] SPEAKER: They had all of their hardware prototypes.
[38:34] SPEAKER: They had an example of each of the hardware prototypes,
[38:37] SPEAKER: and they were all just laid out so you could see
[38:39] SPEAKER: the entire run-up from, hey, here's a thing with cameras
[38:43] SPEAKER: that like, that relies on fiducials on the wall
[38:46] SPEAKER: to track your position in space all the way up
[38:48] SPEAKER: through, you know, shipping product on the end.
[38:52] SPEAKER: And it was really cool to see like, hey,
[38:54] SPEAKER: this is a thing we've been working on for a long time.
[38:56] SPEAKER: Like, it highlighted how much work goes into making
[38:59] SPEAKER: that kind of, you know, any kind of,
[39:02] SPEAKER: a product of any kind of complexity.
[39:04] SPEAKER: - I love that too, yeah.
[39:05] SPEAKER: I do think some companies are probably like,
[39:07] SPEAKER: scared to show off some of that stuff,
[39:09] SPEAKER: either because of, you know, proprietary knowledge
[39:11] SPEAKER: or maybe they, you know, are worried people
[39:13] SPEAKER: will get the wrong idea, but I really do like
[39:16] SPEAKER: when like, prototyping stuff is shown off.
[39:18] SPEAKER: The only example I can think of for prototyping stuff
[39:22] SPEAKER: at this show was ZOTAC announced their new handheld,
[39:27] SPEAKER: handheld PC called the ZOTAC Zone.
[39:31] SPEAKER: And so they actually had like, 3D printed models
[39:35] SPEAKER: of different like, hand shapes and, you know,
[39:37] SPEAKER: that kind of stuff to be like, hey, here's where
[39:39] SPEAKER: we're thinking about ergonomics.
[39:40] SPEAKER: And I really do like hearing the backstory
[39:43] SPEAKER: of a lot of that stuff.
[39:44] SPEAKER: - Well, as somebody who used to make videos on this,
[39:46] SPEAKER: it makes it really easy to make those videos, right?
[39:49] SPEAKER: 'Cause you can sit there and you can walk with a PM
[39:51] SPEAKER: and let them tell the story and have,
[39:54] SPEAKER: they can show and tell, you know, through the different,
[39:56] SPEAKER: through the different iterations and what they learned.
[39:58] SPEAKER: And it ends up being a much more interesting video
[40:00] SPEAKER: than just, our product is running a lunar lake,
[40:04] SPEAKER: blah, blah, blah, at this speed, and we have this many,
[40:07] SPEAKER: our display is this many nits bright
[40:09] SPEAKER: and it has this resolution and you can go up
[40:11] SPEAKER: to 90 frames a second, you know, it's always good
[40:15] SPEAKER: to be able to show rather than tell, so.
[40:17] SPEAKER: - Definitely, I'll say one of the other things
[40:20] SPEAKER: that I love about Computex, I mean, this applies
[40:22] SPEAKER: to any trade show, but for Computex specifically,
[40:25] SPEAKER: usually by like day two or three of the trade show floor
[40:31] SPEAKER: being open, 'cause by that point we've already been there
[40:35] SPEAKER: for like a week, 'cause stuff always happens beforehand.
[40:37] SPEAKER: But the, at some point you start to see these trends.
[40:45] SPEAKER: Like, oh wow, huh, that's interesting.
[40:46] SPEAKER: There's like a new trend that's kind of forming
[40:49] SPEAKER: and I, this year specifically, I did a video on CAM2,
[40:53] SPEAKER: which is a new low profile memory spec
[40:57] SPEAKER: that is meant for laptop, but we actually had
[40:59] SPEAKER: some PC vendors, desktop PC vendors who were experimenting
[41:03] SPEAKER: with that design on motherboards.
[41:07] SPEAKER: And so like, it was not something that was like
[41:11] SPEAKER: a big splash, but like I started noticing like,
[41:15] SPEAKER: huh, that's weird, Asus, MSI, a couple other vendors,
[41:20] SPEAKER: they're starting to experiment with this
[41:22] SPEAKER: and it was mostly like kind of in the corner.
[41:24] SPEAKER: And so I did kind of a, I interviewed all of them,
[41:27] SPEAKER: asked why they're doing it, you know, all the PMs
[41:29] SPEAKER: and stuff like that, and then kind of made a video
[41:32] SPEAKER: based off of my findings on that.
[41:33] SPEAKER: So I really do love like seeing like trends
[41:37] SPEAKER: that kind of evolve and like something that
[41:39] SPEAKER: could potentially be a thing in the future,
[41:41] SPEAKER: or who knows, maybe it's a flash in the pan
[41:43] SPEAKER: and it never comes to fruition.
[41:45] SPEAKER: - Well, to see a step further, I think this is one
[41:48] SPEAKER: of those things that last year was the rear connectors,
[41:51] SPEAKER: right, for motherboards. - Definitely, yes, definitely.
[41:54] SPEAKER: Yeah.
[41:54] SPEAKER: - You know, last year MSI and Asus and Gigabyte,
[41:57] SPEAKER: was that the other one?
[41:58] SPEAKER: Had-- - Gigabyte started the spec
[42:00] SPEAKER: and then yeah, Asus and MSI kind of developed their own.
[42:04] SPEAKER: - For people who don't know, they have motherboard designs
[42:07] SPEAKER: and cases that work with them that put the,
[42:09] SPEAKER: like the ATX power connector and your CPU accessory power
[42:13] SPEAKER: and all the other stuff, and it plugs into the backside
[42:16] SPEAKER: of the motherboard so you don't have to run cables
[42:19] SPEAKER: around the front, you can just jam in the back
[42:20] SPEAKER: and then hide your shame.
[42:21] SPEAKER: - I love it, I've done, yeah, we covered it extensively
[42:25] SPEAKER: last year's Computex, you know, now that some of the products
[42:28] SPEAKER: are on market, I've definitely covered 'em there.
[42:31] SPEAKER: Yeah, I mean, you actually helped me do a video
[42:33] SPEAKER: on the channel with the Corsair 2500X, I think,
[42:37] SPEAKER: was the name of the case.
[42:39] SPEAKER: - Yeah, that was one of their designs that they like
[42:41] SPEAKER: ported over, basically, an old case design
[42:44] SPEAKER: for the new, the holes in the motherboard tray
[42:47] SPEAKER: that fit, line up with the motherboards.
[42:50] SPEAKER: - But yeah, I actually didn't do a, like I was actually
[42:53] SPEAKER: planning on doing a follow-up video for, hey,
[42:57] SPEAKER: backside connector, you know, trends came out
[43:01] SPEAKER: of Computex last year, where do we sit with it
[43:03] SPEAKER: in Computex a year later?
[43:05] SPEAKER: We ran out of time just 'cause there's so much to do,
[43:08] SPEAKER: so I didn't get to do it, but there's definitely
[43:10] SPEAKER: a lot of movement in that space, even though it's like
[43:13] SPEAKER: not as, you know, brand new shiny object
[43:17] SPEAKER: like it was last year.
[43:18] SPEAKER: - The thing I meant to ask you about is if they're gonna
[43:20] SPEAKER: start doing that on ITX boards, 'cause that seems like
[43:22] SPEAKER: the place where really you could use the ease
[43:27] SPEAKER: of plugging in your cables is on small form factors.
[43:33] SPEAKER: - Actually, hmm, that's a good question.
[43:35] SPEAKER: I would say yes, there's been talk, but now that I think
[43:39] SPEAKER: about it, I can't think of an ITX-specific board
[43:41] SPEAKER: that was shown off.
[43:42] SPEAKER: Usually it's full ATX or micro ATX.
[43:46] SPEAKER: I think one of the issues, though, is that a lot of times
[43:49] SPEAKER: the ITX space right now is defaulting
[43:53] SPEAKER: to sandwich-style layouts, so I think the concern is,
[43:58] SPEAKER: you know, in that kind of case, then you're actually
[44:01] SPEAKER: running into problems, so yeah, I think that's probably
[44:03] SPEAKER: why we're not seeing a ton of movement
[44:05] SPEAKER: in the ITX space specifically, but I mean,
[44:08] SPEAKER: it doesn't mean you can't, for sure.
[44:10] SPEAKER: - Yeah, yeah.
[44:11] SPEAKER: Okay, so like anything else, I wanna talk about
[44:14] SPEAKER: the other stuff, 'cause like, part of going to
[44:17] SPEAKER: the big trade show is always, hey, you know,
[44:21] SPEAKER: whether, depending on how you feel about Vegas,
[44:24] SPEAKER: oh man, I got to go be in Vegas for 10 days,
[44:26] SPEAKER: or oh god, I gotta go be in Vegas for 10 days.
[44:28] SPEAKER: - Yeah, no, I'm on that camp.
[44:29] SPEAKER: - Yeah, it's like, I have a 48-hour hard limit
[44:33] SPEAKER: on the amount of time I wanna be in Vegas,
[44:34] SPEAKER: and the more days I go past that, the less I ever
[44:37] SPEAKER: wanna go back to Vegas again.
[44:39] SPEAKER: - Yeah, I've been to Vegas too many times in my life,
[44:42] SPEAKER: and most of them have been trying to do serious work,
[44:46] SPEAKER: and Vegas is not a place to do serious work.
[44:48] SPEAKER: - Yeah, no, no, no, like, when we were doing
[44:51] SPEAKER: tested CES stuff real hard, and bringing like
[44:54] SPEAKER: eight or 10 people, we would do, my days,
[44:57] SPEAKER: a short day was 18 hours, like if I got five hours of sleep,
[45:00] SPEAKER: I was really stoked, so like Vegas is not,
[45:05] SPEAKER: like sleep deprived and having fun Vegas is one thing,
[45:07] SPEAKER: but sleep deprived and trying to work for 18 or 20 hours
[45:10] SPEAKER: a day Vegas is no good.
[45:12] SPEAKER: - And I don't know if you guys have rented this,
[45:14] SPEAKER: but you know, going from meeting to meeting,
[45:16] SPEAKER: sometimes you're actually literally going from
[45:21] SPEAKER: like a hotel or casino to a different hotel,
[45:25] SPEAKER: and I mean, I focus, I'm primarily on the video crew,
[45:28] SPEAKER: I'm the head of video production,
[45:30] SPEAKER: but I used to just start off as a shooter editor,
[45:34] SPEAKER: so I'd always be carrying around a video camera,
[45:36] SPEAKER: and every trip there'd always be a handful of people
[45:39] SPEAKER: who would stop me as I'm trying to rush to my next
[45:42] SPEAKER: appointment, and they'd be like, drunkenly like,
[45:45] SPEAKER: hey, take my photo, take my photo, don't you wanna
[45:47] SPEAKER: take a photo of me, and I'm like, no,
[45:49] SPEAKER: I'm trying to get to work, so get out of my way, please.
[45:53] SPEAKER: - The thing that always killed me was the cab lines
[45:55] SPEAKER: in Vegas, 'cause there's no public transit,
[45:57] SPEAKER: the cab lines were sometimes an hour and a half long,
[46:01] SPEAKER: so our big innovation, like Uber wasn't any better,
[46:05] SPEAKER: 'cause traffic was bad, our big innovation it tested was
[46:09] SPEAKER: our office manager came with us, and she drove a van,
[46:13] SPEAKER: so she would just ferry people around all day
[46:16] SPEAKER: from one stop to the other, and we were able to get
[46:19] SPEAKER: a lot more work done as a result of having easy access
[46:22] SPEAKER: to transportation, and it didn't cost a whole lot,
[46:25] SPEAKER: and she got to come to Vegas and have a couple
[46:26] SPEAKER: of really nice dinners, so she was excited.
[46:28] SPEAKER: - Well, luckily at Computex, most of the things
[46:31] SPEAKER: are centralized around the convention center,
[46:34] SPEAKER: which I appreciate, and then the rest of it
[46:37] SPEAKER: is usually around the Taipei 101 area.
[46:40] SPEAKER: But yeah, like any other trade show, we usually show up
[46:43] SPEAKER: about three days before the actual show floor opens,
[46:48] SPEAKER: because we're taking a lot of pre-brief meetings,
[46:50] SPEAKER: preparing content that will hit some sort of embargo
[46:55] SPEAKER: during announcements, maybe attending the actual keynotes,
[47:00] SPEAKER: and then the show floor proper opens, and then doing
[47:04] SPEAKER: a bunch of coverage from the show floor as well,
[47:07] SPEAKER: so it's usually a trade show for us is about a week's time
[47:12] SPEAKER: of covering, so.
[47:15] SPEAKER: - Well, and the jet lag is gnarly to going to Taiwan
[47:18] SPEAKER: from even the West Coast, so.
[47:20] SPEAKER: - You know, I didn't get hit going there,
[47:23] SPEAKER: I got hit way harder coming back, which in the past,
[47:28] SPEAKER: I never had to do this, but a couple people on my team
[47:31] SPEAKER: had to make that trek going from Computex
[47:34] SPEAKER: to immediately covering E3, literally flying from Taiwan
[47:38] SPEAKER: to LA to cover E3, and the jet lag would hit 'em,
[47:41] SPEAKER: and it was horrible.
[47:43] SPEAKER: I'm so glad I never had to deal with that, 'cause ooh.
[47:46] SPEAKER: - It sounds like hell.
[47:48] SPEAKER: - It's definitely.
[47:49] SPEAKER: - So what's the, so you mostly stay
[47:51] SPEAKER: in the convention center area when you're there?
[47:54] SPEAKER: - No, we usually stay at a, for most of the work,
[47:58] SPEAKER: yes, like in the meetings or around the convention center,
[48:00] SPEAKER: but some of the companies will do it at their headquarters,
[48:04] SPEAKER: because a lot of them are based in Taiwan,
[48:05] SPEAKER: like ASUS has a really large headquarters, MSI,
[48:09] SPEAKER: Cooler Master, Nvidia has an office there too, AMD,
[48:12] SPEAKER: so there's definitely appointments that we go
[48:16] SPEAKER: to specific vendors for, but for the most part,
[48:19] SPEAKER: everybody has some sort of something
[48:21] SPEAKER: around the actual convention center.
[48:24] SPEAKER: - And do you get to do like fab tours
[48:25] SPEAKER: and stuff like that ever, since all that stuff is there too,
[48:27] SPEAKER: or is that in a different part of the island?
[48:30] SPEAKER: - Yeah, so TSMC, which is the largest fab
[48:34] SPEAKER: in the world right now, it supposedly doesn't do
[48:38] SPEAKER: a lot of press-related tours, so we've never looked into it,
[48:43] SPEAKER: and that's kind of the only one
[48:45] SPEAKER: that's within spitting distance of Taipei,
[48:49] SPEAKER: which that's where Computex is, it's specifically in Taipei.
[48:53] SPEAKER: We did do some vendor-specific tours,
[48:56] SPEAKER: like last year Gordon and I went out
[48:58] SPEAKER: even a little bit earlier, and we actually did
[49:01] SPEAKER: a tour of the MSI offices, specifically
[49:04] SPEAKER: around designing laptops, it was actually
[49:07] SPEAKER: a really fun video, I can send you a link
[49:11] SPEAKER: if you want to put it in the show notes or something,
[49:12] SPEAKER: but we essentially got to talk to key people
[49:16] SPEAKER: of the laptop design team, we couldn't see manufacturing
[49:20] SPEAKER: 'cause the actual physical manufacturing
[49:23] SPEAKER: was in mainland China, but we didn't tour that,
[49:26] SPEAKER: but I mean, we talked to the audience development team,
[49:30] SPEAKER: we talked to the actual design team,
[49:33] SPEAKER: we talked to, MSI's one of the only companies
[49:36] SPEAKER: that has in-house rapid prototyping,
[49:41] SPEAKER: or like a case, like the shells for laptops,
[49:45] SPEAKER: so they can easily concept something
[49:47] SPEAKER: and then send it down to be printed
[49:50] SPEAKER: to get a look of what it looks like physically.
[49:53] SPEAKER: They do some initial thermal testing,
[49:56] SPEAKER: they do have a very small anechoic chamber there,
[49:58] SPEAKER: so we got to experience that, that was
[50:00] SPEAKER: a really fun video to put together,
[50:03] SPEAKER: I would love to do more stuff like that.
[50:05] SPEAKER: Another person who does awesome tours like that
[50:08] SPEAKER: is Steve over at Gamers Nexus,
[50:11] SPEAKER: who was a friend of both of our shows,
[50:13] SPEAKER: and yeah, he's really good at going to these companies
[50:18] SPEAKER: and doing tours based off of what they can show.
[50:22] SPEAKER: - Yeah, it's always hard, anytime you're in a factory,
[50:24] SPEAKER: we did a couple of car, we tried to do
[50:27] SPEAKER: a couple of car things once, and the list of,
[50:30] SPEAKER: hey, you can show this, but if this is anywhere
[50:32] SPEAKER: in the shot, you can't use that shot,
[50:34] SPEAKER: and I have to imagine the chip fab,
[50:38] SPEAKER: where everything secret is a nightmare to shoot in.
[50:43] SPEAKER: - Yeah, we have been invited to specific Intel fab tours,
[50:49] SPEAKER: like the last one that we got invited to,
[50:52] SPEAKER: I didn't end up going, my coworker, Mark Hochman,
[50:55] SPEAKER: was in Malaysia, they had a fab tour in Israel
[50:59] SPEAKER: two years ago, I think it was,
[51:01] SPEAKER: they have a fab in Ireland, so I would love
[51:06] SPEAKER: to go on one of these fab tours in the future for sure,
[51:08] SPEAKER: but yeah, it is exactly what you were saying,
[51:11] SPEAKER: like, there's certain parts where you're like,
[51:13] SPEAKER: well, you just can't shoot here, sorry,
[51:15] SPEAKER: we're just gonna give you the information,
[51:16] SPEAKER: or if you shoot here, you're gonna have to be very careful
[51:20] SPEAKER: of what you're showing, maybe blur something out.
[51:24] SPEAKER: - My favorite note ever was when I asked
[51:28] SPEAKER: if you can go into the paint room of an automotive place,
[51:31] SPEAKER: and they were like, well, you could,
[51:33] SPEAKER: but you have to not have any cosmetics on,
[51:35] SPEAKER: because if you have any deodorant or hair product
[51:38] SPEAKER: or makeup or perfume or a clone or anything like that,
[51:43] SPEAKER: it can impact the paint, it can impact the curing
[51:47] SPEAKER: of the paint as it goes on the panels as they come through,
[51:50] SPEAKER: and I was like, so what, the guys who work here
[51:53] SPEAKER: don't wear deodorant?
[51:53] SPEAKER: They're like, no, they have a list,
[51:55] SPEAKER: so they can buy these specific brands
[51:57] SPEAKER: and these flavors of the brands and stuff like that.
[51:59] SPEAKER: I was like, that is nuts.
[52:01] SPEAKER: - Okay, that is nuts, yeah, that's crazy.
[52:05] SPEAKER: Okay, so I think last thing, we gotta talk
[52:08] SPEAKER: about night markets, 'cause night markets,
[52:12] SPEAKER: night markets came up a lot in the,
[52:13] SPEAKER: Gordon and I watched all the keynotes together,
[52:16] SPEAKER: and night markets came up a surprising amount
[52:20] SPEAKER: during even the keynotes.
[52:23] SPEAKER: What's up with night markets, Adam?
[52:24] SPEAKER: - Well, it is very integrated in a lot of Asian cultures,
[52:29] SPEAKER: but specifically Taiwan has these key night markets
[52:33] SPEAKER: all over Taiwan, but in Taipei,
[52:36] SPEAKER: there's some specific ones that are very key,
[52:38] SPEAKER: and yeah, somebody had shared,
[52:42] SPEAKER: I guess there was a Twitter account or something
[52:44] SPEAKER: that was posting which night markets Jensen from Nvidia
[52:48] SPEAKER: was attending, just like, I don't know who,
[52:52] SPEAKER: I guess it's the equivalent of inside gossip
[52:56] SPEAKER: for people who follow large tech CEOs.
[52:59] SPEAKER: I don't know, I don't really follow,
[53:01] SPEAKER: but it is definitely a thing of like, oh man,
[53:04] SPEAKER: this CEO appeared at this night market,
[53:06] SPEAKER: that this night market's gonna get a bunch of boom.
[53:09] SPEAKER: - Well, cool, so for people who don't know night markets,
[53:14] SPEAKER: basically once it gets dark, like nine o'clock,
[53:17] SPEAKER: 10 o'clock at night, it seems like they shut down streets.
[53:20] SPEAKER: - No, earlier than that, more like six,
[53:22] SPEAKER: I think is the earliest one that maybe we went to,
[53:26] SPEAKER: and it depends, a lot of them are actually markets
[53:30] SPEAKER: that are just designated that.
[53:32] SPEAKER: Like, instead of shutting down a street at a certain time,
[53:35] SPEAKER: it's like, no, this little alleyway
[53:37] SPEAKER: is pretty much always blocked off,
[53:40] SPEAKER: 'cause it's not just, a lot of times it's not just about
[53:42] SPEAKER: like food vendors coming up and setting stalls,
[53:45] SPEAKER: a lot of times there's a bunch of businesses
[53:47] SPEAKER: that are selling, you know, tchotchkes
[53:49] SPEAKER: and you know, off-brand Gucci bags to people.
[53:56] SPEAKER: So like in each one of them, and this year,
[53:58] SPEAKER: so I actually went a week early with my wife
[54:01] SPEAKER: to do a personal vacation, so I was able to go
[54:04] SPEAKER: to more night markets than I could
[54:06] SPEAKER: during like a trade show, which was nice,
[54:08] SPEAKER: and so I think I went to like a total
[54:10] SPEAKER: of six different night markets this last trip.
[54:12] SPEAKER: - Oh, cool.
[54:13] SPEAKER: - And each one of them really does have
[54:15] SPEAKER: a distinct like focus and like vibe to it.
[54:19] SPEAKER: It's really cool to do them kind of back to back.
[54:22] SPEAKER: I mean, a lot of things are, I mean,
[54:24] SPEAKER: there's a lot of food, there's a lot of shopping,
[54:26] SPEAKER: a lot of the food can be similar to traditional
[54:29] SPEAKER: Taiwanese stuff, but some of them are like,
[54:31] SPEAKER: oh, if you're gonna go to this night market,
[54:33] SPEAKER: then this specific dish is, you know,
[54:36] SPEAKER: like, you know, specific to this night market,
[54:39] SPEAKER: or oh, you really wanna get the one over here.
[54:41] SPEAKER: There's actually a night market,
[54:43] SPEAKER: I'm gonna butcher the mandarin,
[54:45] SPEAKER: 'cause I'm practicing though, but Ningxia night market
[54:49] SPEAKER: is more for like foodies, I guess where you get
[54:51] SPEAKER: like the really good food stalls and there's way less
[54:55] SPEAKER: of vendor stalls, like selling stuff.
[54:58] SPEAKER: So the focus there is food.
[55:00] SPEAKER: And then another one I went to,
[55:03] SPEAKER: oh, I can't remember the name of it,
[55:05] SPEAKER: but that one like had way more like vendors
[55:07] SPEAKER: and the stalls were kind of in the middle,
[55:09] SPEAKER: but really the appeal was all the shopping
[55:12] SPEAKER: off to the sides, so.
[55:14] SPEAKER: - So what's the food sitch?
[55:15] SPEAKER: Is it like, are we talking about like dumplings
[55:18] SPEAKER: and dim sum kind of stuff, or is it noodles, or is it?
[55:20] SPEAKER: - Everything.
[55:21] SPEAKER: - Really?
[55:22] SPEAKER: - Everything.
[55:23] SPEAKER: I mean, you see a lot of the same things,
[55:26] SPEAKER: like there's always some sort of like fruit stands,
[55:29] SPEAKER: and usually a lot of times there's multiple
[55:31] SPEAKER: across the whole market.
[55:33] SPEAKER: You see a lot of like a traditional Taiwanese snack
[55:36] SPEAKER: is a deep fried sweet potato ball.
[55:40] SPEAKER: So it's very like airy, almost like an eclair kind of thing.
[55:45] SPEAKER: So you just get a bag of those and you're just popping 'em
[55:47] SPEAKER: while you're walking around.
[55:49] SPEAKER: So you'll see a lot of the same kind of things.
[55:54] SPEAKER: But then, yeah, like I said, some of 'em will be like,
[55:57] SPEAKER: oh, we went to this one night market that had this guy
[56:00] SPEAKER: who had corn on the cob and he like would like lather it up
[56:04] SPEAKER: with something and he had these series of holes
[56:08] SPEAKER: that he would put 'em in for different times
[56:10] SPEAKER: and different lengths and I couldn't quite tell
[56:12] SPEAKER: what he was doing with 'em, but it took like 15 minutes
[56:15] SPEAKER: and then he like gave this hot corn on a stick
[56:19] SPEAKER: that looked amazing.
[56:20] SPEAKER: I actually didn't get one, but my coworker got one.
[56:24] SPEAKER: But yeah, and then some of it's really good
[56:27] SPEAKER: and then some of it is oddities for people
[56:31] SPEAKER: from Western cultures.
[56:32] SPEAKER: Like the two major ones are like stinky tofu and durian.
[56:36] SPEAKER: And yeah, I don't wanna be too mean to people
[56:40] SPEAKER: who do love stinky tofu, but oh man,
[56:44] SPEAKER: I remember the very first time I smelled it
[56:46] SPEAKER: and it was not a pleasant experience for me.
[56:49] SPEAKER: I thought there was like an open sewage somewhere
[56:52] SPEAKER: and my instinct in my body was telling me,
[56:54] SPEAKER: "Dude, you need to run, something is wrong."
[56:57] SPEAKER: And then I looked over to the side and I was like,
[57:00] SPEAKER: "Oh no, that's stinky tofu." (laughs)
[57:03] SPEAKER: - What's this, it smells like open sewage?
[57:06] SPEAKER: That seems like a, I've never had stinky tofu.
[57:09] SPEAKER: It's not really something that comes up here
[57:10] SPEAKER: that often it turns out.
[57:11] SPEAKER: - Yeah, no, I mean there are places in the Bay
[57:13] SPEAKER: that you can get it.
[57:15] SPEAKER: I might put together like a big group of us
[57:17] SPEAKER: to go try it or something, but it is fermented.
[57:21] SPEAKER: Usually it's like some sort of fermented concoction
[57:25] SPEAKER: with tofu, fried tofu, at least at the night market vendors,
[57:29] SPEAKER: it's usually fried tofu with some like cabbage
[57:32] SPEAKER: and fermented vegetables and stuff like that.
[57:34] SPEAKER: I, luckily, I am somebody who will try almost anything once
[57:39] SPEAKER: and so I actually have tried stinky tofu twice
[57:43] SPEAKER: despite what my inner body was telling me to not do it.
[57:47] SPEAKER: This past year though, I had a mission to try durian
[57:51] SPEAKER: which, yeah, fresh durian has a reputation
[57:56] SPEAKER: to be very rancid smelling to the point where a lot of like,
[58:00] SPEAKER: you'll see signs up at like airports of like,
[58:03] SPEAKER: "Hey, don't bring durian on planes."
[58:04] SPEAKER: Or hotels will be like,
[58:06] SPEAKER: "Don't bring durian back to your hotel room."
[58:08] SPEAKER: Things like that just 'cause it's so pungent
[58:10] SPEAKER: and it is mostly something that you can only get
[58:13] SPEAKER: in Asian countries like Singapore, Taiwan, places like that.
[58:18] SPEAKER: You can get some durian here in the States
[58:20] SPEAKER: but usually it's frozen when it comes over
[58:22] SPEAKER: and supposedly loses a lot of its potency
[58:25] SPEAKER: but I did try it this year.
[58:27] SPEAKER: I was at, we were at a night market,
[58:30] SPEAKER: there was some fresh durian right there
[58:32] SPEAKER: and I was like, "Okay, cool."
[58:34] SPEAKER: I actually shot a little video.
[58:35] SPEAKER: I should post that somewhere but--
[58:37] SPEAKER: - You should put it on your TikTok, yeah.
[58:38] SPEAKER: - Yeah, I should, yeah.
[58:39] SPEAKER: And it was, I was prepared for the worst
[58:43] SPEAKER: 'cause a lot of people hyped it up as a bad reputation
[58:46] SPEAKER: but luckily it was nowhere near as bad as stinky tofu.
[58:50] SPEAKER: So I was like, my first inclination was like,
[58:55] SPEAKER: "Oh, this isn't that bad.
[58:57] SPEAKER: "I've had way worse."
[58:58] SPEAKER: I didn't like it, I didn't love it.
[59:00] SPEAKER: I mean, I'd get it again just to try it again, I guess.
[59:03] SPEAKER: But whatever, but yeah, it was definitely,
[59:08] SPEAKER: definitely not as bad as stinky tofu.
[59:11] SPEAKER: - Like fermented stuff in general,
[59:13] SPEAKER: it's funny, different people,
[59:15] SPEAKER: like my wife is not a fermented food eater in general
[59:20] SPEAKER: and it's hard. - Same, I hate fermented stuff.
[59:22] SPEAKER: I actually don't like kimchi, anything like that.
[59:25] SPEAKER: So I had a theory that the reason why stinky tofu
[59:28] SPEAKER: hit me harder is because I just don't like fermented stuff.
[59:33] SPEAKER: And so I've asked random people around that I know of like,
[59:36] SPEAKER: "Hey, what do you think of stinky tofu, yes or no?"
[59:40] SPEAKER: Then if it's no, then I'm like,
[59:41] SPEAKER: "Hey, do you actually like fermented stuff anyway?"
[59:45] SPEAKER: I would say this theory does not really hold water
[59:47] SPEAKER: 'cause most of the time it, yeah.
[59:49] SPEAKER: I haven't been able to see a trend, but you know.
[59:52] SPEAKER: - Okay. - Yeah.
[59:53] SPEAKER: - Well, I mean, keep them food scientists, let us know.
[59:57] SPEAKER: Okay, the last thing on our night market list,
[59:59] SPEAKER: you have these capsule toys.
[1:00:03] SPEAKER: - So I will say this isn't just a night market thing.
[1:00:05] SPEAKER: This is literally like everywhere across Taipei.
[1:00:09] SPEAKER: You can't, you literally can't throw a stone
[1:00:11] SPEAKER: without hitting multiple 7-Elevens
[1:00:13] SPEAKER: or other convenience stores.
[1:00:17] SPEAKER: And almost all of them always have
[1:00:19] SPEAKER: some sort of capsule toy machines out front.
[1:00:22] SPEAKER: - Are you talking about like the thing
[1:00:23] SPEAKER: that you put like 50 cents in and you turn the knob
[1:00:25] SPEAKER: and then a little plastic capsule with a toy in it falls out?
[1:00:27] SPEAKER: - Yes, and it is highly addicting for me.
[1:00:33] SPEAKER: And I have spent each trip probably
[1:00:35] SPEAKER: around $100 on capsule toys.
[1:00:38] SPEAKER: - Oh my God, don't play loot box games, dude.
[1:00:41] SPEAKER: - I know, well Clash Royale still gets me.
[1:00:44] SPEAKER: Yeah, the first time I kept all of them
[1:00:48] SPEAKER: in their actual capsule, because then I did some videos
[1:00:51] SPEAKER: when I brought it back home and opened it up with my wife.
[1:00:54] SPEAKER: And so half my suitcase, if the TSA were to open it up,
[1:00:57] SPEAKER: they'd be like, what the hell is this?
[1:01:00] SPEAKER: These are literally all just capsules.
[1:01:03] SPEAKER: This is weird shit, dude.
[1:01:05] SPEAKER: - 99% of them are toys, 1% drugs.
[1:01:08] SPEAKER: - Yeah, oh, you gotta get through 'em to figure out which.
[1:01:11] SPEAKER: But yeah, no, it's fun.
[1:01:12] SPEAKER: It's always like, they're just novelty and they're fun.
[1:01:16] SPEAKER: And I love cats and a lot of times
[1:01:19] SPEAKER: they're like weird cat-based little figurines.
[1:01:22] SPEAKER: And I'm like, okay, well that's a cat sitting on a toilet.
[1:01:25] SPEAKER: That's hilarious, I have to buy it.
[1:01:27] SPEAKER: Yeah, and then I bring it home
[1:01:29] SPEAKER: and sometimes I display 'em, sometimes I don't.
[1:01:32] SPEAKER: - You have a shelf full of cats sitting on toilets
[1:01:35] SPEAKER: and now you have to dust, so congratulations.
[1:01:37] SPEAKER: - Well, and the trend I got this year
[1:01:40] SPEAKER: was capsule toys of capsule toy machines.
[1:01:45] SPEAKER: - Oh wow, that's very meta.
[1:01:46] SPEAKER: - Yeah, literal machines that are capsule toy machines
[1:01:50] SPEAKER: that have little capsule balls.
[1:01:51] SPEAKER: You twist a little thing and it pops out.
[1:01:53] SPEAKER: - What, really?
[1:01:54] SPEAKER: - Yeah, yeah. - That's crazy.
[1:01:55] SPEAKER: - Yeah, and there's different kinds, too.
[1:01:58] SPEAKER: And we got capsule toys of vending machines as well.
[1:02:02] SPEAKER: And literally the vending machines have sodas
[1:02:05] SPEAKER: the size of like super tiny, yeah.
[1:02:10] SPEAKER: - This is the thing, my daughter got into this briefly
[1:02:12] SPEAKER: 'cause she used it when playing with dolls.
[1:02:15] SPEAKER: But there's these things called mini-brands here.
[1:02:18] SPEAKER: - Oh my God, yes.
[1:02:19] SPEAKER: - That are the same idea, like really small.
[1:02:21] SPEAKER: - Same thing. - Yeah.
[1:02:23] SPEAKER: - I know this is not a video podcast,
[1:02:26] SPEAKER: but I'm showing you, so.
[1:02:28] SPEAKER: - You're holding up two, what looks like capsule machines?
[1:02:31] SPEAKER: The focus is locked on your face pretty good, but it's okay.
[1:02:34] SPEAKER: - This white one is a capsule machine and yeah,
[1:02:38] SPEAKER: you can literally hit the button
[1:02:41] SPEAKER: and a little capsule pops out.
[1:02:42] SPEAKER: - That's amazing.
[1:02:44] SPEAKER: - Yeah, it even goes in the drawer.
[1:02:45] SPEAKER: And then this one is a little vending machine.
[1:02:47] SPEAKER: It's like an orange vending machine that has like little--
[1:02:50] SPEAKER: - Have like jelly drinks?
[1:02:52] SPEAKER: Are jelly drinks popular there?
[1:02:53] SPEAKER: - You load the little drink in the back,
[1:02:56] SPEAKER: you hit the button and then it comes out of the bottom.
[1:02:59] SPEAKER: - That's amazing. - It is so tiny.
[1:03:00] SPEAKER: I've actually lost one of them.
[1:03:02] SPEAKER: Oh, and I almost did it again.
[1:03:03] SPEAKER: - Well, that one's in the keys now, it's gone forever.
[1:03:05] SPEAKER: - Yeah, so look how tiny this is.
[1:03:07] SPEAKER: - It's like a pill, it's smaller than a pill.
[1:03:09] SPEAKER: - Dude, smaller than a pill, yeah.
[1:03:11] SPEAKER: This is definitely not safe for children.
[1:03:13] SPEAKER: - Yeah, no, don't give those to kids.
[1:03:14] SPEAKER: That's amazing, that sounds really fun though.
[1:03:17] SPEAKER: - Too fun, too fun, too addicting, yeah, I love it.
[1:03:21] SPEAKER: - Out of curiosity, like those are fancy,
[1:03:24] SPEAKER: like capsule toys when I was a kid
[1:03:25] SPEAKER: were like a thing of caps or something.
[1:03:27] SPEAKER: What does a capsule toy machine cost?
[1:03:31] SPEAKER: - So yeah, they're usually either five, 10 pieces
[1:03:36] SPEAKER: or two to three 50 cent pieces.
[1:03:41] SPEAKER: So the rough translation right now
[1:03:43] SPEAKER: is 100 new Taiwan dollars is three American dollars.
[1:03:50] SPEAKER: So if you use two 50 cent pieces, it's like three bucks.
[1:03:54] SPEAKER: A lot of them, actually some of them
[1:03:55] SPEAKER: even go up to like five 50 cent pieces.
[1:03:59] SPEAKER: So that's essentially like you just plopped,
[1:04:02] SPEAKER: I don't know, I'm not good at math,
[1:04:03] SPEAKER: that's like seven dollars on one.
[1:04:06] SPEAKER: - So if I'm, just to have a point of comparison,
[1:04:11] SPEAKER: like what is a lunch cost at a fast lunch someplace cost,
[1:04:16] SPEAKER: not at a convention center?
[1:04:19] SPEAKER: - Oh, like in Taiwan?
[1:04:20] SPEAKER: - Yeah, in Taiwan.
[1:04:22] SPEAKER: - That's the thing is that food there is dirt cheap.
[1:04:25] SPEAKER: You can get like an amazing meal for like nothing.
[1:04:28] SPEAKER: And it's hard for us because we're in the Bay
[1:04:31] SPEAKER: and like one sandwich can be like 20 bucks,
[1:04:34] SPEAKER: but they're like the same sandwich is probably like 50 cents.
[1:04:37] SPEAKER: Maybe I'm exaggerating,
[1:04:38] SPEAKER: but it's like you can get a lot of food real cheap.
[1:04:41] SPEAKER: That's another reason why I like Taiwan, so.
[1:04:43] SPEAKER: - Okay, well this all sounds good.
[1:04:46] SPEAKER: Thank you, Adam, so much for coming by
[1:04:49] SPEAKER: and sharing a little bit of what Computex is like.
[1:04:52] SPEAKER: It sounds, I've got to go sometime, it sounds fun.
[1:04:55] SPEAKER: - Oh yeah, you definitely should, yeah.
[1:04:57] SPEAKER: Thanks for having me, love hanging out.
[1:05:01] SPEAKER: I'm always honored to be on the show.
[1:05:02] SPEAKER: I listen every week, so.
[1:05:04] SPEAKER: - Well, thanks Adam.
[1:05:05] SPEAKER: And if people want to find out more,
[1:05:06] SPEAKER: I think the PC World YouTube channel
[1:05:08] SPEAKER: probably is the place to go.
[1:05:10] SPEAKER: - PC World YouTube channel, pcworld.com.
[1:05:13] SPEAKER: And I have started a PC World TikTok for anybody inclined,
[1:05:19] SPEAKER: but you know, we're still experimenting over there.
[1:05:21] SPEAKER: - Well, and if you want a PC focused,
[1:05:24] SPEAKER: PC enthusiast focused podcast every Tuesday,
[1:05:26] SPEAKER: the full nerd, well more or less every Tuesday,
[1:05:28] SPEAKER: the full nerd lands over on YouTube
[1:05:31] SPEAKER: and where podcasts are found.
[1:05:32] SPEAKER: - Yeah, the full nerd podcast and Will,
[1:05:34] SPEAKER: you're on pretty often, especially recently.
[1:05:38] SPEAKER: And yeah, we stream it live on YouTube every Tuesday.
[1:05:40] SPEAKER: It's got its own YouTube channel now,
[1:05:43] SPEAKER: youtube.com/hatsymbolthefullnerdpodcast.
[1:05:48] SPEAKER: - Thank you so much for coming by,
[1:05:49] SPEAKER: and we'll talk to you soon.
[1:05:51] SPEAKER: - Damn good time.
[1:05:52] SPEAKER: - Be sure to check out PC World for more great work from Adam.
[1:05:55] SPEAKER: Thanks as always for coming by.
[1:05:57] SPEAKER: And that will do it for us this week.
[1:06:01] SPEAKER: As always, "Brad and Will Made a Tech Bot"
[1:06:03] SPEAKER: is brought to you by listeners.
[1:06:05] SPEAKER: We're 100% listener support, and without you all,
[1:06:07] SPEAKER: we would not be here doing the show every week.
[1:06:09] SPEAKER: So thank you, thank you to everyone who supports the show.
[1:06:12] SPEAKER: If you want to find out how to support the show,
[1:06:14] SPEAKER: you can go to patreon.com/techbot.
[1:06:16] SPEAKER: Again, that's patreon.com/techbot,
[1:06:19] SPEAKER: and where for five bucks a month,
[1:06:20] SPEAKER: you get access to the Patreon exclusive episode
[1:06:22] SPEAKER: that we do every single month.
[1:06:23] SPEAKER: I think this month is gonna be a live tech call-in show.
[1:06:27] SPEAKER: So if you have tech questions, it may have already happened,
[1:06:30] SPEAKER: but hit the Discord and we'll have information
[1:06:32] SPEAKER: on how to join in and answer questions,
[1:06:35] SPEAKER: and then the audio version will go up later
[1:06:36] SPEAKER: on the Patreon-only feed.
[1:06:38] SPEAKER: But yeah, you can go to patreon.com/techbot
[1:06:42] SPEAKER: and sign up to support the show.
[1:06:44] SPEAKER: As always, thank you to all of our patrons,
[1:06:46] SPEAKER: but a very special thank you goes to our executive producer,
[1:06:49] SPEAKER: to your patrons, including Andrew Slosky,
[1:06:52] SPEAKER: Bunny Fiend, Paddle Creek Games makers of Fractured Veil,
[1:06:55] SPEAKER: David Allen, James Kamik, Joel Krauska, Jordan Lippett,
[1:06:59] SPEAKER: Pantheon, makers of the HS3 high-speed 3D printer,
[1:07:03] SPEAKER: and Twinkle Twinkie.
[1:07:04] SPEAKER: And since it's the end of the month,
[1:07:06] SPEAKER: we owe thanks to our associate producer patrons as well,
[1:07:09] SPEAKER: including Alejandro Navarro, Andre M. Burke,
[1:07:13] SPEAKER: Andrew Dicey Scholdyce, Arthur Gies, Ben Tolman,
[1:07:18] SPEAKER: Brutal Kerfuffle, Eric Klein, Felix Kramer,
[1:07:22] SPEAKER: Bram Banks, Jad Rita, Just Associate Wedge, Matt Walker,
[1:07:26] SPEAKER: parentheses Walkman8080, close parentheses,
[1:07:29] SPEAKER: Mike Etheridge, Nathan Phelps, Sanchit Kumar,
[1:07:32] SPEAKER: Steve Lin, Thomas Shea, and Tom Hilton.
[1:07:35] SPEAKER: Thanks everybody, we appreciate all your support.
[1:07:37] SPEAKER: And if you can't support the Patreon, don't worry about it,
[1:07:39] SPEAKER: just leave a nice review of the podcast on iTunes
[1:07:42] SPEAKER: or wherever you listen to your podcasts.
[1:07:43] SPEAKER: And we appreciate everybody who listens to the show
[1:07:46] SPEAKER: every week by this.
[1:07:47] SPEAKER: Thank you all so much, and we will be back next week
[1:07:49] SPEAKER: with another edition of the Tech Bot.
[1:07:51] SPEAKER: See you then.
[1:07:53] SPEAKER: (upbeat music)
