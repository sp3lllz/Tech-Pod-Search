---
episode: 318
title: 308: NEW Lake???
date: 2025-10-12
guests: none
duration: 1:03:53
---

[00:00] SPEAKER: Brad when I was at that Intel tech tour thing a couple of weeks ago, which by the way, videos
[00:03] SPEAKER: up on PC world and the full nerd. Now we should talk more about that. Adam. Well, I think we'll
[00:09] SPEAKER: have Adam on in a couple of weeks. I talked to him about it and he's, it seems game. So,
[00:13] SPEAKER: but I got to talk to Intel. We talked to a bunch of Intel fellows. We only talked to a couple of
[00:16] SPEAKER: them on camera. Adam talked to tap about GPU stuff and wide computing. Let me stop you real quick.
[00:24] SPEAKER: When you say fellows, is that like fellas, like fellers, like colloquial, some chums, some pals,
[00:30] SPEAKER: or is that like, is that a fellow, like a distinguished person of import and prestige?
[00:36] SPEAKER: It's a distinguished person of import and prestige. It's like, think about like a,
[00:41] SPEAKER: like a university chair. Yes. That's like a collegial. That's how I would describe them.
[00:46] SPEAKER: That's what I figured you meant, but anyway, go on. So I got to talk to, we talked to tap of course,
[00:53] SPEAKER: Tom Peterson, who's their GPU guy. He's been around for a hundred years doing stuff at Nvidia
[00:58] SPEAKER: and Intel and all sorts of places. I, I got to talk to Steven Robinson briefly. Who's in charge
[01:07] SPEAKER: of X 86. Oh, it's a big job. The instruction set, which was, I was not prepared to have that kind of
[01:14] SPEAKER: conversation with someone. He was kind of intense, been very technical and very nice. But I got to
[01:19] SPEAKER: spend some time and interviewed. What are their software architects? What are the Intel fellows,
[01:23] SPEAKER: software architects, architects named Roger, Roger Chabu squire, who is in charge of thread director,
[01:31] SPEAKER: which I've spent a lot of time running benchmarks on Intel CPU's and AMD CPU's as well. And I'm
[01:37] SPEAKER: pretty familiar with how the technology on both of those CPU's handles the weird nature of their
[01:46] SPEAKER: non homogenous architectures now. And we got, we sat down and talked for like 20 minutes about
[01:52] SPEAKER: how thread director works, why it's important, why it's a really hard problem.
[01:56] SPEAKER: Like if you are interested in that stuff, you should go to the full nerd channel on YouTube
[02:00] SPEAKER: and watch the video. Cause I would love to be able to do more videos like that. And we're trying to
[02:05] SPEAKER: put the kind of the hardcore, the more enthusiast, deep dive nerd business on that full nerd channel,
[02:11] SPEAKER: instead of maybe on the PC world channel where people mostly come looking for like laptop reviews
[02:16] SPEAKER: and stuff like that. But also I mean, that's like, yes, that is deep dive nerd business,
[02:19] SPEAKER: but it's also something that's just becoming increasingly really relevant to anybody who
[02:23] SPEAKER: runs a modern CPU because they're all going heterogeneous in some fashion. Like AMD's got
[02:28] SPEAKER: its split core design with cores on different dies. Intel has got big and little P and E cores.
[02:34] SPEAKER: AMD, I believe on the public roadmap is also going to start doing big and little cores.
[02:40] SPEAKER: Intel is going to start splitting. If you look at the Nova Lake leaks, Intel is going to start
[02:44] SPEAKER: splitting cores across dies. Like everybody's going to have scheduling issues is the point
[02:48] SPEAKER: I'm trying to make like scheduling needs to get better soon. And so like, this is something that
[02:54] SPEAKER: is going to affect everybody who's buying new PCs. So that's exciting to hear. Well,
[02:58] SPEAKER: even, even the mobile stuff does it like Qualcomm and Apple, silicon all has big little and split
[03:05] SPEAKER: cores and stuff. You mentioned Apple here, the nature of Apple's tightly vertically integrated
[03:11] SPEAKER: approach to hardware and software starts to show its worth because do you ever hear anything about
[03:16] SPEAKER: scheduling issues on MacOS? You sure don't. No. Well, one of the things that was interesting
[03:20] SPEAKER: talking to Rajshree was that I didn't understand how neither the OS nor the hardware has complete
[03:29] SPEAKER: information about what the state of the CPU is. Right? That's my understanding of thread director
[03:33] SPEAKER: is hardware in the CPU, giving some hints or feedback to the OS, to the scheduler, right?
[03:38] SPEAKER: That is exactly how she described it. Yes. Yeah. But, but as she said, Microsoft owns the
[03:43] SPEAKER: scheduler. The thing that, the thing that happens is, you know, sometimes it's not worth then I'm,
[03:50] SPEAKER: I'm paraphrasing. So if you want to hear her actually explain this much better than me go,
[03:55] SPEAKER: go look at the video. But the gist is when they look at a thread and they're and they're like,
[04:01] SPEAKER: Oh, this is on the wrong core. The thread director sends a hint and then the OS thread scheduler
[04:07] SPEAKER: decides if it's going to act on the hint or not based on things that it knows, like how much
[04:12] SPEAKER: longer that thread is scheduled to run. Cause like, if the threads only scheduled to run for
[04:16] SPEAKER: another 50,000 clock cycles, which is apparently like the timeframe that they're talking about in
[04:20] SPEAKER: a lot of these cases, which just to be clear, billions of clock cycles per second. So 50,000
[04:26] SPEAKER: is like 200,000th of a second. Then ends up it like the cost of moving it to another,
[04:33] SPEAKER: another core might be higher than the time that it's going to take to take to continue running on
[04:39] SPEAKER: the nonoptimal core. And, and so we talked about other stuff too. Like one of the things they're
[04:44] SPEAKER: doing on mobile processors, they're using the E-cores more for like gaming, because it turns out
[04:49] SPEAKER: the E-cores and games are pretty analogous to what is happening on consoles. If you put eight
[04:56] SPEAKER: E-cores on a game that requires eight cores, you're going to get better performance than
[05:00] SPEAKER: four Ps and eight and four Es stuff like that. So anyway, it was, it was a really interesting
[05:05] SPEAKER: conversation. I will definitely pull that up. Most of the stuff we talked about there was about
[05:10] SPEAKER: Phantom Lake and about their upcoming Panther Lake. I keep wanting to be Panther, Phantom Lake.
[05:20] SPEAKER: I'm envisioning the YouTube thumbnail new lake. Look look Scooby-Doo just is rolling out to
[05:26] SPEAKER: Fortnite at the end of the month or later this week or something. So I got Phantom Lake on my
[05:31] SPEAKER: brain. They also talked about Clearwater Forest, which is the data center part, which is like
[05:36] SPEAKER: a whole buttload of these 18A compute tiles. And then by the time you hear this, there'll be a
[05:41] SPEAKER: video with me and Adam and Mark Hochman up on the PC world channel. I think maybe a full nerd. I
[05:47] SPEAKER: don't know where we talk about what it was like to go inside the 18A fab and like bunny suit up and
[05:52] SPEAKER: get to walk and walk in the floor where they make the CPU's and see wavers getting turned into footage
[05:58] SPEAKER: of you in a bunny suit. There is not footage. They did not even take a picture. So they had some try
[06:05] SPEAKER: on bunny suits in like the waiting room that I put on. I have pictures of that. I'll send you
[06:09] SPEAKER: pictures of that, but we didn't, we didn't get to have the real bunny suit pictures because they
[06:14] SPEAKER: taken away our cameras and phones and all that stuff. Highly sensitive facility. I get it anyway.
[06:20] SPEAKER: That's Hey. Yeah. I'm excited to be excited about CPU's again.
[06:50] SPEAKER: [inaudible]
[06:53] SPEAKER: Welcome to bread and will made a tech pod. I'm well, I'm Brad today.
[07:00] SPEAKER: We're doing something a little different. Are we? No, it's the same thing. We always do.
[07:05] SPEAKER: I feel like, you know, you gotta have a, when you, when you, when you listen to the radio,
[07:09] SPEAKER: they're always like, let's do it. Let's, let's kick this off a brand new way.
[07:13] SPEAKER: Um, no. So, uh, we, we have stuff that we, that we like we're doing a toolbox episode. We haven't
[07:18] SPEAKER: done one in a minute. We like episode or, you know, things we've been tinkering with, like things
[07:23] SPEAKER: we've dug into and are enthusiastic about and might want to pass on to other people who might
[07:27] SPEAKER: also like them. Yeah. Good, good vibe stuff. Uh, I got to, can I start, I got, I got, I got a good
[07:34] SPEAKER: kickoff with one of the very first recommendations we made years and years and years ago that the
[07:40] SPEAKER: people, the people craved and it became a defining characteristic for a while when I went to Amazon
[07:46] SPEAKER: and I looked at this particular product, it also then would show me a bunch of other shit
[07:50] SPEAKER: tech pod people liked. I think I know where this is going. Proceed. So I used to buy nanotape in
[07:57] SPEAKER: sheets or rolls. Sheets? Yeah. I've never seen it in sheets. I've only seen rolls. What is a sheet?
[08:04] SPEAKER: Like a square shape, kind of situation. Do you buy it in stacks? So before I could buy it before
[08:10] SPEAKER: Amazon had it before alien tape or whatever was advertising on late night TV, I used to get nanotape
[08:16] SPEAKER: from inventables, which is the, they, they make, um, they make, uh, CNC, CNC routers, home CNC routers,
[08:23] SPEAKER: and they were selling sheets of it as a, like a way to finish the bottom of things that you
[08:27] SPEAKER: make with it. So this sticks in place. Interesting. So that's where I, I had one of those that lasted
[08:31] SPEAKER: for years and years and years where I've just kind of little strips that I needed to year in there.
[08:35] SPEAKER: Um, but then the tape, the tape stuff is good. It's really, really stickier, a lot stickier than
[08:40] SPEAKER: the inventable stuff. Cause it's a little bit, uh, squashier, I think. And that gives you more
[08:44] SPEAKER: room to push the air out of the bubbles for people who don't know nanotape is just a kind of soft,
[08:49] SPEAKER: squishy, bubbly tape that has really, really small, uh, bubbles on, on either one or both sides
[08:58] SPEAKER: that when you push on it, it suctions stuff onto, you can stick a smooth thing to another
[09:03] SPEAKER: smooth thing with it. And it'll stay on for ever for a really long time until you scrape it off.
[09:08] SPEAKER: And then when you scrape it off, it just comes right off. There's no residue or anything.
[09:13] SPEAKER: I started buying it in dot form so you can get it on like a sheet, like an eight by 12 sheet with
[09:18] SPEAKER: like a bunch of dots just stuck on and you peel them off and it's much easier to manage than the,
[09:24] SPEAKER: than the wide tapes than the, than the, uh, cause you, cause a, the round size usually is about what
[09:30] SPEAKER: I need for like one or two of those will do exactly what I want. And I don't have to have
[09:35] SPEAKER: scissors cause it's hard to cut cause it always sticks to the scissors. And like the, the dot form
[09:41] SPEAKER: is pretty good. Occasionally they'll like roll up and get crumpled in on each other. But for the
[09:45] SPEAKER: most part, you can just peel off a dot, jam it onto something and then jam the thing you want to
[09:48] SPEAKER: stick to it on that. And you're good to go. You put like a little grid shape, I guess,
[09:52] SPEAKER: if you've got a bigger surface, you can just kind of arrange them in a pattern that you think is.
[09:57] SPEAKER: Yeah. So I have a couple of things that are longer. I have one on either end,
[10:01] SPEAKER: maybe one in the middle. It's nice because the dots are easier to pry off than the,
[10:07] SPEAKER: than the, the tape too. I, as always be thoughtful about surfaces you put this stuff on cause it will
[10:14] SPEAKER: pull like finish off of things. If you're not care if it's, if it's a delicate finish,
[10:19] SPEAKER: I definitely seen people pull the paper off their sheet rock before, which you don't want.
[10:24] SPEAKER: Interesting. Does nanotape stick to it? I would think there's just enough surface variation in
[10:28] SPEAKER: sheet rock that it wouldn't stick super well. Cause these are suction cups to be clear for
[10:32] SPEAKER: people who have not used it. And there's no adhesive here. It's, it's, you can envision,
[10:36] SPEAKER: you know, how a suction cup behaves like it needs to have a pretty clean, flat surface to stick to.
[10:42] SPEAKER: Well, so it depends on your paint is my, is my guess. So if you have a, like a shiny paint
[10:46] SPEAKER: finish, it's probably going to be less porous and more likely to stick. Also, it depends on how you
[10:51] SPEAKER: try to remove it. Like if you get in there with a putty knife and kind of slide it in between the
[10:56] SPEAKER: paint and the wall, it'll pop right off the tape in the wall. It'll pop right off. If you don't
[11:03] SPEAKER: do that and just pull it straight off, like a, like a ham fisted Tyro, you're probably gonna
[11:07] SPEAKER: pull a chunk of wall off with it if you're not careful. So, so yeah, dot nanotape in dot form,
[11:14] SPEAKER: big fan. All right. That sounds good. Yeah. What do you got? You got anything? We bouncing
[11:20] SPEAKER: back and forth. I could go all at once, but I've only got two things, but they're kind of bigger
[11:25] SPEAKER: things. I bought a raft of new SD cards, micro SD cards for my raspberry pies that are, that are the
[11:32] SPEAKER: SanDisk max endurance. I just became aware of SanDisk's high and max endurance line of micro SD
[11:37] SPEAKER: cards recently and decided to give them a shot. What, what occasioned this is the new version of
[11:44] SPEAKER: raspberry pie. OS just came out. Trixie based yes. Based on, so Debbie and Trixie came out in early
[11:49] SPEAKER: August and here we are two months later and they have now put out the first raspberry pie image
[11:54] SPEAKER: based on it. So I was just like, oh, you know, like some of my pies are pretty old around here.
[11:59] SPEAKER: And you're using them for stuff like your nut server. So I'll just, I'll do the inventory
[12:04] SPEAKER: here. I've got a pie for, yeah. That runs one blocky instance. Home assistance. Yeah. A cups
[12:13] SPEAKER: air print server cups is the, what is it? Common Unix printing system or something. It's,
[12:18] SPEAKER: yeah. It's a thing that enables air print support for my printers. You have a printer, honestly,
[12:22] SPEAKER: Brad. Why? That's dude. I bought, I bought the brother laser. Everybody bought in 2008 and it's
[12:29] SPEAKER: still going just fine. I finally had to retire my brother laser that I really bought in 2008.
[12:34] SPEAKER: Cause it, it was making a squeaking noise that I couldn't fix. Yeah. Mostly use it for printing
[12:39] SPEAKER: shipping labels. That's 90% of what we use it for. Anyway, the pie for that's what I will do.
[12:47] SPEAKER: If I ever get around to doing this NAS backup to external target, what I got hung up on was trying
[12:57] SPEAKER: to decide if I want to encrypt the backup drives or not. And if I do, then that's a whole, that's
[13:02] SPEAKER: that's a whole new stack of learning how DM crypt works and Lux and making a bunch of decisions
[13:08] SPEAKER: around drive encryption that I just don't have the energy for. I'm the one who has the Linux
[13:12] SPEAKER: pod. So I'm putting it off for another couple of months. Anyway, I've got a PI two in here that runs
[13:17] SPEAKER: another blocky instance and nuts, which is hooked up to the UPS to monitor that. And I've got a PI
[13:23] SPEAKER: one that has been out of service for a while, but I'm about to put it back into service as
[13:29] SPEAKER: an airplay target. Wow. That's what, which is ironically is what I bought it for in 2012. I
[13:35] SPEAKER: don't want to derail this with Raspberry Pi talk, but I, my, my, my first raspberry PI one model B
[13:40] SPEAKER: that I bought in 2012, I bought to run something called share play on, which basically just is,
[13:45] SPEAKER: it becomes an airplay target, but you can have kind of a crappy audio process. So the I don't
[13:51] SPEAKER: know if this has changed actually, but yeah, the first, at least couple generations of PI
[13:56] SPEAKER: have got terrible analog audio output, but the, the fix back then was to buy a little, no name,
[14:01] SPEAKER: $5 USB sound card. I mean, people call them sound cards. They're not cards they're basically look
[14:06] SPEAKER: like a USB thumb drive with a DAC. Yeah. It's a USB DAC is what it actually is. But even in
[14:12] SPEAKER: 2012, you could buy a $5, like literally unbranded, no name, USB DAC that sounded
[14:19] SPEAKER: infinitely better than the terrible. I think it's like, I forget the audio terminology. Is it,
[14:23] SPEAKER: it's a PWM output. I think on the original PI, not a, there is no DAC. There is no DAC on the
[14:30] SPEAKER: original PI is that it uses PWM output, which sounds God awful. Anyway, I'm going to dig that
[14:35] SPEAKER: little USB DAC out. And what this is for is when I get back to tinkering with desktop Linux again,
[14:44] SPEAKER: I like to listen to music while I'm sitting around tinkering with stuff. And if you're doing a bunch
[14:48] SPEAKER: of rebooting back into the UEFI and like running Linux installs and being at a command line and a
[14:53] SPEAKER: fresh install, you can't listen to music on your PC. So I'm going to set this PI one back up as an,
[15:00] SPEAKER: as an airplane target again, to sit here and I can plug my speakers into it and stream music off my
[15:05] SPEAKER: mask to it while the PC is in some like frequently rebooting state. Okay. Anyway, I was along with my
[15:12] SPEAKER: headphones on for that, but I appreciate that. Well, but I have nothing to play the music off of.
[15:16] SPEAKER: You have a phone. Not the same. Okay. Okay. I get it. What's the deal with the high endurance? Like
[15:24] SPEAKER: there's a lot of work happening in SD cards right now. I randomly stumbled on these just searching
[15:30] SPEAKER: around and they are targeted. They're advertised. Sandisk like advertises them as being primarily
[15:36] SPEAKER: for like car dashboard cameras and other sort of like constantly recording, constantly writing
[15:42] SPEAKER: scenarios, which as a sidebar, like I kind of can't believe manufacturers make dashcams that
[15:49] SPEAKER: write to SD card because SD cards die constantly when you write to them all the time. I'm like,
[15:55] SPEAKER: so I'm of two minds here, right? Cause like one mind says if they did an SSD,
[15:59] SPEAKER: it's going to constantly wear out too. It's just going to take a little bit longer than that than
[16:03] SPEAKER: the SD card, but if it was internal, then you probably just have to throw out the dash cam and
[16:08] SPEAKER: buy a new dash cam. You're not wrong. You're not wrong. So like, is it better to just have an
[16:13] SPEAKER: infinite supply of SD cards going in and out of this thing or better than having to junk a camera
[16:18] SPEAKER: with integrated storage? Absolutely. Yeah. I wonder are we, are we ripe for some kind of like
[16:23] SPEAKER: low cost in via like, uh, like user insertable in VME, like enclosed in VME sort of situation
[16:30] SPEAKER: kind of feels like it, but I don't know. Let me pitch an idea to you. What if you had
[16:33] SPEAKER: a really small spinning disc and, and then you had these magnetic read, write heads that kind of
[16:38] SPEAKER: rode above the disc and they wrote bits onto the circular tracks of that disc, almost like a record
[16:45] SPEAKER: or a CD and they just spun really fast. So you get the data on and off and you could like write
[16:51] SPEAKER: to them forever and they would never degrade. Well, I mean, forever is a long time, but yeah,
[16:56] SPEAKER: let's say, sure. Maybe the mechanics of the drive would fail long before the writable aspect of them
[17:01] SPEAKER: would fail. Yeah. Yeah. That's probably a good way to think about that. We could call them
[17:07] SPEAKER: a platter, a platter storage or something. I don't know. I don't know what we'd call them,
[17:11] SPEAKER: but we'll workshop that one. That's weird. So, yeah, I, uh, I did a little looking around
[17:18] SPEAKER: before I bought these. They're, they're not much more expensive than regular SD cards to be clear.
[17:23] SPEAKER: Okay. Like a 32 gig high endurance card is 10 bucks. A 32 gig max endurance card,
[17:29] SPEAKER: I think is 14, but like not too far out of line of what you pay for regular SD cards. And also like,
[17:36] SPEAKER: I know that you can boot Raspberry Pis off of other things now, like you can
[17:40] SPEAKER: enable some USB boots, but I, I, I just, I didn't want to hang in an SSD off the side of this
[17:45] SPEAKER: Raspberry Pi. Like I wanted it to be tidy. It's all the, all the Pis are crammed into very small
[17:50] SPEAKER: spaces. Like I don't want a bunch of extra cable cruft and device cruft hanging off of them. Cause
[17:55] SPEAKER: I want them to fit in the tiny cubby holes and nooks where they live. It's, it's really
[18:00] SPEAKER: unfortunate that they don't have that, that, uh, that little SSD header. Yeah. So they're getting
[18:06] SPEAKER: there. Like, um, the Pi 5 does ship with an NVMe capability through the, I guess it's the GPIO pins
[18:13] SPEAKER: or there's, so there is a header on the Pi 5 that gives you very basic NVMe support, but you still
[18:19] SPEAKER: need like a hat for that. You still need to like integrate that into a case. Well, yeah. So like my,
[18:24] SPEAKER: my home assistant yellow has on it, an NVMe socket, but it's, it uses the socketed version
[18:30] SPEAKER: of the Pi 5. So you're, it's the compute module, not the, not the typical board. Yeah. The Pi 4,
[18:35] SPEAKER: there are cases out there that have like little USB bridges to an SSD mount on the case. So you
[18:40] SPEAKER: can put an SSD in, but I, the case I bought for my Pi 4 was pretty that, and I don't feel like
[18:45] SPEAKER: buying another case. Like anyway, also like I, I just have a bit of an indignance about things not
[18:51] SPEAKER: working right. Or like, uh, yeah. Features being included that don't work as I've like, I'd like,
[18:57] SPEAKER: yeah, these things are, these things are supposed to boot off of SD cards. Like I'm going to make
[19:01] SPEAKER: the fucking SD card work, right. Yeah. And just to be clear, like for the stuff that you're using,
[19:06] SPEAKER: the only problem is writing logs probably, right? Yeah. And I put a log to ram on all my Pis. So
[19:11] SPEAKER: like that helps mitigate them anyway. But the, I was using a very old crappy SD card in my Pi 4,
[19:16] SPEAKER: which is the important one because it needs to run home assistant. Gotcha. If all the lights
[19:20] SPEAKER: stopped working. Yeah. There's problems. That's very annoying. That's why I bought a yellow is
[19:24] SPEAKER: because I didn't want to think about this anymore. And that Pi 4 had been getting weird. Like when I
[19:27] SPEAKER: would do like an app update or whatever, it had been getting very slow. This was a very old SD.
[19:31] SPEAKER: It was like a 10 year old SD card and it was getting like very noticeably slow to do disc
[19:38] SPEAKER: operations on and Trixie, the Trixie Pi OS came out and I was just like, yeah, it's just time to,
[19:42] SPEAKER: to do a wipe and everything. I did some. Have you done the migration yet for the home system?
[19:49] SPEAKER: Yes. So actually home systems running on my NAS right now. Oh, uh, wild. I moved it over
[19:55] SPEAKER: there and it's like, when you, when everything's containerized, it's like amazing how fast it is to,
[20:00] SPEAKER: to migrate something like that. I literally, uh, in preparation for wiping that Pi 4, I copied the
[20:07] SPEAKER: home assistant config directory over to the NAS, copied the system D unit file over that I used to
[20:12] SPEAKER: spin up the container and like ran the container, ran the service and it just started right up and
[20:17] SPEAKER: went. And I don't, you don't have any like Z-wave or Zigbee radios or anything like that on your
[20:22] SPEAKER: home assistant. So that's, yeah, that's, that's the difference. I don't pass any hardware in
[20:26] SPEAKER: to the, uh, yeah. If I was doing like Bluetooth or had had one of those, yeah, like USB radios
[20:31] SPEAKER: that you're talking about, it would have been certainly a bit more of a config thing, but.
[20:36] SPEAKER: It's still not hard, but it's a pain in the butt. It's like more, it's more difficult. I like having
[20:40] SPEAKER: it on its own device, honestly, for that reason. So I did a little googling around before I bought
[20:45] SPEAKER: these. I found a, uh, I found a blog post. Another is another one of these like amazingly incredibly
[20:52] SPEAKER: in depth, like this person must be an engineer type posts, uh, of somebody who tested these things.
[20:58] SPEAKER: And by tested, I mean, this is, this is kind of fun. Cause I didn't even know like what an SD card
[21:03] SPEAKER: looks like inside. I tested, I mean, they literally removed the outer, like epoxy layer on the card
[21:09] SPEAKER: to expose all the test pads on the card. And built an interface board.
[21:15] SPEAKER: And then soldered the board that they built the diagnostic board to the test pads on there and
[21:19] SPEAKER: like pulled a ton of information. And basically like, you know, I'm, I'm certainly not educated
[21:24] SPEAKER: enough to check this person's work, but they determined that these cards are actually using a
[21:29] SPEAKER: better, well, higher quality, more durable form of NAND than the cheaper cards. I forget,
[21:37] SPEAKER: do SD cards have controllers on them or are they relying on the device to be the controller person
[21:41] SPEAKER: goes into that in this blog post, I don't have it in front of me right now. I think it's all one
[21:47] SPEAKER: unit, I believe was the determination there. The controller and the storage are all one monolithic
[21:52] SPEAKER: unit on an SD card. I guess, I guess that makes sense. Cause they're so tiny that would kind of
[21:55] SPEAKER: have to be right. Yeah. Anyway, this person to the best of their determination found that these
[22:02] SPEAKER: cards are using the SanDisk Toshiba 3D TLC flash, which is like, I guess again, somewhat higher
[22:09] SPEAKER: quality and more durable than what's in the cheaper cards. Yeah. I went to the launch for
[22:13] SPEAKER: the 3D flash. Really? Oh yeah. It was at the Exploratorium. Oh, wow. Okay. I guess it was a
[22:18] SPEAKER: big deal then. We were really excited about it. And apparently the max endurance cards are using
[22:23] SPEAKER: that 3D flash in a, in a slightly even more durable way than the regular high endurance ones.
[22:28] SPEAKER: Yeah. He does say that he wasn't able to like tell what the controller is doing because of the way
[22:32] SPEAKER: the whole thing works. So this is also, I don't know if you've considered the scientific testing
[22:37] SPEAKER: or not. I mean, the methodology seemed sound, but it was just one person. But I also found a person
[22:41] SPEAKER: on the Raspberry Pi forums who had done some informal testing with these things where they
[22:46] SPEAKER: basically set up a test that they like automated tests that kind of wrote, you know, like 164
[22:52] SPEAKER: kilobyte files and then 110 megabyte files, blah, blah, blah, you know, like kind of like that
[22:57] SPEAKER: and let it run. They didn't say what regular SD card they tested with. They just said it was a
[23:01] SPEAKER: known brand. I wish they had said kind of the brand and model they used, but they managed to
[23:07] SPEAKER: kill the mainstream, like regular SD card after several hundred write cycles or so I don't have
[23:12] SPEAKER: the, I should pull the thread up in front of me. It was like, they don't last long if you're doing
[23:16] SPEAKER: a lot of small writes is the TLDR. They managed to kill a regular mainstream name brand SD card,
[23:23] SPEAKER: like relatively quickly with this. And then they tried, tried the high endurance card and basically
[23:27] SPEAKER: like it ran several times more of the test cycles than the regular card had and did not kill the
[23:33] SPEAKER: card. So they actually just killed the test and didn't get it to the point where it would kill it.
[23:38] SPEAKER: It seems like these things do work as advertised based on all the stuff that I looked into. And
[23:42] SPEAKER: like I said, they're not that much more expensive than the regular ones. They are seemingly a little
[23:49] SPEAKER: bit slower, I will say. Like if you look at this, even the quoted read write speeds, the SanDisk
[23:55] SPEAKER: lists are a bit lower than like your kind of ultra or extreme SD cards. And even in practice,
[24:00] SPEAKER: I've put Trixie on the Pi 4 and have been setting it up. And like when you do an app to update,
[24:05] SPEAKER: you know, and it has to kind of like build package manifests or whatever, and read them like that
[24:10] SPEAKER: does seem a little bit noticeably slower than on the old kind of like extreme card I had in there.
[24:15] SPEAKER: But like, how often are you actually working with stuff like that? Like I'll take,
[24:20] SPEAKER: I'll take slightly, slightly slower disk operations in exchange for ideally never buying an SD card
[24:29] SPEAKER: again for these Pi's. Cause also this is a bigger topic that we shouldn't get into on this episode,
[24:32] SPEAKER: but I think I'm done buying Raspberry Pi's. I don't see myself kind of ever buying another one
[24:38] SPEAKER: considering how expensive the proposition is getting versus what you can get in like a small
[24:41] SPEAKER: x86 box. So like, I think I'm good on Pi's and I just basically wanted to like buy a round of
[24:47] SPEAKER: high quality SD cards to hopefully the last round, hopefully never. Yeah. I did not buy one of these
[24:52] SPEAKER: for my Pi KVM because that one, it has, it has, I put a brand new SD card in it when I set it up,
[24:58] SPEAKER: but that thing, that thing uses an entirely read only file system. Oh, so it should be fine. So it
[25:04] SPEAKER: kind of never writes to the disk unless you're doing updates on it. So like that one's probably
[25:08] SPEAKER: going to be fine for a long time anyway. So I was going to say the, the other option,
[25:11] SPEAKER: and this is what I used for my, for my FreeNAS box when it was, cause you know,
[25:18] SPEAKER: you put it in the FreeNAS box off of USB thumb drives usually, and they had the same problem
[25:22] SPEAKER: if you were writing a lot to them. I was, I was, I bought, I bought a stack of USB thumb drives
[25:27] SPEAKER: when I was running TrueNAS and I was averaging about like six or eight months per pair of drives
[25:31] SPEAKER: before they would die. Yeah. They would just, they just didn't last long. So I bought USB SSDs so you
[25:38] SPEAKER: can get like a 2230 NVMe SSD that's in a USB shell that you just hang off the front and it solved the
[25:45] SPEAKER: problem for me entirely. Yeah. I ended up doing the same except just internal SATA SSDs because
[25:49] SPEAKER: I have a bus adapter in there that handles all the hard drives. So I had spare motherboard SATA ports.
[25:54] SPEAKER: So at some point, at some point I just bought a pair of $20 Crucial SSDs.
[25:58] SPEAKER: Like 128 gig SSDs or something. Basically the same price as a USB thumb drive. And
[26:04] SPEAKER: they've been going for years without problems. Yep. Last thing I'll say really quick here for
[26:10] SPEAKER: Linux nerds who really care, like Wendell, if you're listening, might care about this.
[26:16] SPEAKER: We got to get Wendell on this podcast, man. Look, man, I just got to spend one of the,
[26:21] SPEAKER: I got to spend time with a bunch of really interesting folks at that tech days thing,
[26:25] SPEAKER: the tech door thing and, and getting to talk to Wendell about Linux shit for, for lunches and
[26:32] SPEAKER: dinners sometimes was a delight. Wendell's a delightful even being. I listened to the
[26:36] SPEAKER: Dolby diaries with him on it and like every single thing he brought up on there is something I wanted
[26:39] SPEAKER: to talk to him further about. But the thing I was gonna say really quick is the, it looks like
[26:45] SPEAKER: the Raspberry Pi people may have done some basic mitigation for SD card ware in Trixie or in their
[26:52] SPEAKER: version of Trixie that they're putting out because. It's about damn time. It's not like, it's not,
[26:56] SPEAKER: I don't understand why they don't do log to RAM on the log folders.
[27:00] SPEAKER: So that's exactly where I'm going with this. I've been installing log to RAM on my Pis for ages,
[27:04] SPEAKER: which is something you can set up. It would not be hard to do yourself. This just packages up in
[27:08] SPEAKER: a nice script that just does it for you. But all log to RAM is doing is creating a RAM drive and
[27:13] SPEAKER: then mounting the log path on that RAM drive so that your logging all goes into RAM rather than
[27:17] SPEAKER: ever. I think it does, it does get written out to disk, like on an interval that you can configure,
[27:21] SPEAKER: but not constantly is the key. And that's the thing. It's like one big write is better than
[27:26] SPEAKER: a hundred thousand small writes. And the trade-off there is you're giving up some amount of RAM,
[27:30] SPEAKER: but it's not that much RAM. I mean, we're logging text files here basically. Well, and if it crashes
[27:35] SPEAKER: while there's log in memory, then you'll lose that log. So it makes it hard to diagnose that stuff.
[27:39] SPEAKER: But for the kind of applications you use on these things, it probably doesn't matter. Probably don't
[27:43] SPEAKER: need your logs that badly. But Trixie out of the box on Pis is mounting the journal D log path in
[27:50] SPEAKER: slash run. Is that the RAM drive? So yeah, slash run is typically mounted on a temp FS, which is a
[27:57] SPEAKER: RAM based file system in Linux. It's weird. Cachey mounts external drives on run slash media slash
[28:06] SPEAKER: something now. Yeah. Like anything can get mounted anywhere in Linux as we know. Right. Right. They
[28:12] SPEAKER: could just be doing something custom there, but I have my, my PI two is still running the bullseye
[28:18] SPEAKER: version and they were not mounting the journal D log path in run in bullseye. Okay. So this is
[28:25] SPEAKER: a change they have made at some point that may have been the case with bookworm than the last
[28:29] SPEAKER: version, but at any rate, like they are they are taking some steps to, to mitigate this themselves,
[28:36] SPEAKER: but it's just, it's just the journal D logging. It's not anything else that, that logs to the,
[28:42] SPEAKER: the classic logging path of slash var slash log, it's still written to disk and there's still plenty
[28:48] SPEAKER: of other stuff that still writes there. And so it's still worth installing log to RAM, I think
[28:52] SPEAKER: there, but between these higher endurance cards and getting pretty much all the logging mounted
[28:57] SPEAKER: into RAM, I'm pretty optimistic. I will just never have to buy an SC card again for these things or
[29:02] SPEAKER: ever worry about it again. Yeah. Which is pretty exciting. We'll see. Stay tuned. I'll check back
[29:08] SPEAKER: in five years. On the SD card front. This is a small note. I saw that Lexar announced that they
[29:14] SPEAKER: have one terabyte switch to compatible cards as express cards now, which like for people who just
[29:21] SPEAKER: have like two games installed on their switches is no problem. And the switch, the switch two games
[29:25] SPEAKER: are still pretty reasonable size for the, for the amount of capacity on the drives that they ship
[29:30] SPEAKER: with. But this was exciting because I wasn't going to buy, like, I, I, I did not buy an extra card
[29:37] SPEAKER: for my switch two out of the gate because they only, I think the biggest they had was 256 gigs,
[29:44] SPEAKER: which basically doubled your capacity on that, on that device. And that didn't feel like, like
[29:49] SPEAKER: I didn't, I, I hate buying a launch card and then six months later having a second one and
[29:55] SPEAKER: then having this extra launch, this extra small card that I'm just never going to do anything
[29:58] SPEAKER: with. Yep. That's how you end up putting an old used card into something like a raspberry pie
[30:02] SPEAKER: down the line. Cause you have an old one that's been used a bunch and then like, oops, that was
[30:06] SPEAKER: a mistake. But also like 256 gigs is too big for a raspberry pie, right? Like I'm not going to put
[30:11] SPEAKER: 256 gigs on my raspberry pie. But when you have a smaller card, that's a, that's a cast off or a hand
[30:17] SPEAKER: me down because you bought a bigger one, then you got to find something to do with it. Yeah. I,
[30:20] SPEAKER: um, anyway. Okay. So that, that I just wanted to hit that on the switch two front. Oh, go ahead.
[30:25] SPEAKER: Well, go ahead. I'll, I'll, I'll mention my switch two thing at the end. I was going to say on the
[30:29] SPEAKER: switch two front, I finally I've, I've, I've bought and sent back a bunch of grips over the
[30:34] SPEAKER: last two, three months. And I finally got, uh, ones that I like the switch grip, exclamation
[30:41] SPEAKER: point by Savage Raven, sorry, switch grip, exclamation point Savage Raven by skull and
[30:46] SPEAKER: company is great. I'm looking at the Amazon page now skull and company Neo grip and ergonomic rip
[30:53] SPEAKER: hard shell with replaceable grips, or Nintendo switch to it's the product name on Amazon product
[30:59] SPEAKER: names are so bad. It's bad. Like, like it, so it has all the requirements that I needed. It
[31:05] SPEAKER: will, uh, you can dock it with the grips on, which is important. The case stand still works
[31:11] SPEAKER: with the grips on. Is that the case that there are some that you can't dock with grips on?
[31:17] SPEAKER: Some of them have the full back and then that'll block the slot. So you can't put it in this,
[31:20] SPEAKER: in the slot. That seems like a real pain. Um, I mean, that's the way both all of the switch one
[31:26] SPEAKER: grips that we had were for both my, my switch, my wife's, uh, OLED and my daughter's well,
[31:31] SPEAKER: daughter's like, doesn't have a dock, but, um, you just pop, like they pop on and off. It's not like
[31:36] SPEAKER: it's, you know, there's, there's clips that kind of be slighted in and out of,
[31:40] SPEAKER: it's not like taking a phone case off or something like that. Nothing that complicated.
[31:43] SPEAKER: Um, but this one has, it ships with three different grip shapes. Like there's a shallow
[31:50] SPEAKER: one, a medium one and a big chonky boy with like, uh, almost like a finger spot at the top. And,
[31:56] SPEAKER: uh, I, of those three, we found something that everybody in the house that uses the switch likes.
[32:01] SPEAKER: So, uh, and it makes holding it much more comfortable for extended play sessions. It
[32:05] SPEAKER: was 30 bucks, which is kind of more than I wanted to pay for this. Uh, but like compared to fucking
[32:12] SPEAKER: up my hands, playing switch games, I'm all for it. So switch grip seems like it's been a fairly
[32:17] SPEAKER: contentious subject so far, although mainly that's based on people not being happy with the dbrand
[32:22] SPEAKER: one. Yeah. The dbrand one, I didn't like at all. I was really disappointed. Did you try it? Yeah.
[32:27] SPEAKER: Okay. Like that was the one that where the grips were like falling off. I think it was like the
[32:31] SPEAKER: switch was like falling out of the grips, which is kind of not what you want. Yeah. Like the problem
[32:37] SPEAKER: I had was either it was too hard to take all of them, either they were too hard to take off so
[32:41] SPEAKER: that you couldn't get like standalone, you couldn't pop the grips off easily or like it blocked the
[32:48] SPEAKER: kickstand or blocked the, um, the X, the, the, the, the dock, or it was like a big giant rubber
[32:56] SPEAKER: silicone thing that you had to like wedge the whole thing in. And then it collects as a bunch
[33:00] SPEAKER: of grime around the edges when it's in there, which is gross. Um, so yeah, like this was,
[33:06] SPEAKER: this is the one of the ones that I have tried. This is the one I liked the most. I really,
[33:09] SPEAKER: really, really detested of all of them. The ones that are just like silicone wrappers for the joy
[33:17] SPEAKER: cons that have like lumps on the bottom to make them a little more grippy. Those, those were the
[33:22] SPEAKER: absolute worst of all of them. Cause then they just made the joy cons not fit right. And they
[33:27] SPEAKER: were uncomfortable and the grips were too squishy and like the whole thing just stunk. So yeah,
[33:33] SPEAKER: highly recommend. Good, good to know. I think I might finally go ahead and buy a switch too.
[33:37] SPEAKER: It's like, I'm going to tell you Donkey Kong Bonanza. Oh yeah, no, that's, that is,
[33:43] SPEAKER: that's the game to buy it for. Like, I know multiple people who have said it's their game
[33:48] SPEAKER: of the year. Like I absolutely need to play Bonanza. It is, it is a remarkable game. It is
[33:53] SPEAKER: not at all what I was expecting. It is follows the legacy because that's the Odyssey team, right?
[33:58] SPEAKER: Yes. Yeah. It, it is definitely follows that lineage in a, in the most positive way. Um,
[34:06] SPEAKER: I'm also going to pick up that remaster for galaxy and galaxy two, because like,
[34:11] SPEAKER: I think I have galaxy one in some switch one collection that I bought 3d all stars that came
[34:16] SPEAKER: out about five years ago has galaxy one in it, but I verified that they actually have done more
[34:21] SPEAKER: work on these new versions or well, galaxy two never came out on the switch. So this is new, but
[34:26] SPEAKER: the galaxy one version here is better than the one that was in 3d all stars. They did more work
[34:31] SPEAKER: on it. So it runs at 4k and stuff like that. And does it, does it, do they, did they work
[34:36] SPEAKER: on the control stuff? So you don't have to do the waggle stuff as much. I think that was already
[34:40] SPEAKER: done for the three all stars version, but yes, that is, you can, I mean, yeah, these are fully
[34:44] SPEAKER: playable on switch to control schemes. Um, but I'm getting, I'm getting like review code offers for
[34:51] SPEAKER: other switch to exclusive games now. Like I need to just get that damn hardware in here.
[34:57] SPEAKER: Yeah, it's, it's interesting. I don't have a good sense of how like non Nintendo games are doing on
[35:02] SPEAKER: that thing yet, but it seems like it's like, it seems like they've slowed down the, the number
[35:09] SPEAKER: of Indies that have access to the store in a way that they're maybe being a little bit more
[35:13] SPEAKER: thoughtful about it. And there's not as many like anti games in there. Oh, that, that has been,
[35:17] SPEAKER: I mean, the lack of, um, lack of if kid distribution has been kind of a major topic
[35:22] SPEAKER: of discussion in the Nintendo community. Oh yeah. I knew that over the last few months, cause there
[35:27] SPEAKER: are plenty of indie developers who still don't have dev kids. Look, there's a, there's a couple
[35:31] SPEAKER: of discords I'm in with a bunch of indie developers and the yo, who has a Nintendo switched to dev kit
[35:37] SPEAKER: threads are extensive. So yeah. Interesting. Anyway. Um, I, I, I've talked about these before
[35:45] SPEAKER: I want to hit them again because I got them for my AirPods pro and, uh, they're really, really good.
[35:51] SPEAKER: The comply soft foam tips for IEMs, you can get them for pretty much any in-ear monitor headphones.
[35:57] SPEAKER: Um, and they replace the, the kind of silicone-y soft flanged, like the rubber that kind of loops
[36:04] SPEAKER: back on itself. And then you jam it in your ears. I can't use in-ear monitors without these at this
[36:11] SPEAKER: point. The soft stuff makes my, I actually, it honestly irritates the skin in my ears. Generally.
[36:17] SPEAKER: Um, I think I have some sort of mild reaction to whatever the rub, whatever plastic they use for
[36:22] SPEAKER: that. But the foam tips are seal in better. They make them feel like they're in more securely,
[36:27] SPEAKER: which is great for standalone non tethered earbuds. Cause I feel like I'm less likely to
[36:32] SPEAKER: lose them and they do a much better job isolating. And they're like, they don't last forever as the
[36:37] SPEAKER: only knock against the comply tips. Uh, they're like good for probably two, three months each.
[36:42] SPEAKER: I usually buy one, like three pack a year for about 20 bucks. And, uh, that lasts me the whole
[36:47] SPEAKER: year. So you're still on AirPod pros two, correct? I am on AirPod pros two. I don't plan to upgrade
[36:53] SPEAKER: until these wear out. So you're not, you're not commenting on cause they did do new tips for the
[36:57] SPEAKER: threes, which you have not tried. So the tips on the threes are a hybrid of the rubber and foam
[37:04] SPEAKER: behind them to kind of give you the best of both worlds. I don't, my, the reviews I read looked at
[37:10] SPEAKER: them and were like, Hey, these are already ripped for some, like I think Linus tech tips famously
[37:15] SPEAKER: ripped one of the, one of the test buds when they were, when they were testing those.
[37:20] SPEAKER: Um, I, I really, I just, I really strongly like the reason I don't like IEMs generally is those,
[37:27] SPEAKER: those shitty tips. Sure. Yeah. I think I might still get some pros three. I hate the naming
[37:31] SPEAKER: on those things. I hate like the AirPod pros three. Well, it's just hard to say for whatever
[37:38] SPEAKER: reason you go to the Apple store. They only have one kind of AirPod pro there. I'm sorry. It's not
[37:42] SPEAKER: AirPod pros. It's AirPods pro. Right. Look, this is like an attorney's general situation, I guess.
[37:48] SPEAKER: Let's just move on. But the kind of shit people argue about in newsrooms. I think I'm still, yes,
[37:53] SPEAKER: we, yes, we, we had arguments all the time. We're not arguments. We had discussions all the time
[37:58] SPEAKER: about like how much to add here to the stupid branding of various companies. Like, do you,
[38:03] SPEAKER: do you honor, do you honor their, their branding when it says that the game name should be entirely
[38:07] SPEAKER: capitalized? Probably not. Nope. Inner caps are fine though. Oh, see, we didn't do inner caps.
[38:12] SPEAKER: It was all first cap. You get to get a proper noun just like everybody else at maximum PC.
[38:17] SPEAKER: Does the C in StarCraft get capitalized? Nope. All right. Call of duty, call duty, not of,
[38:24] SPEAKER: even if it's on the box. Sure. I think I'm still going to get some pro threes. I have, I have seen
[38:32] SPEAKER: like, I don't put a lot of stock in this stuff. Like the, like the extreme obsessive headphone
[38:37] SPEAKER: community has got thoughts about the sound stage on them or the, you know, frequency response or
[38:43] SPEAKER: whatever. But like, I, I find I am very not picky about how things sound. Like if it, if it sounds
[38:48] SPEAKER: quote unquote good to me, I'm generally fine with it. The, the, the bigger one is probably not a
[38:54] SPEAKER: deal breaker, but I have been looking at the switch to subreddit people testing Bluetooth headphones
[38:58] SPEAKER: with the switch to seems like, I don't, did I talk about this recently? Like, this seems like there
[39:03] SPEAKER: is probably still just enough latency, even with the switch to Bluetooth headphones that
[39:08] SPEAKER: it might be too much from it's like 150 milliseconds or something. I, I don't know.
[39:14] SPEAKER: So I loaded up crypto, the crypto, the neck, the Zelda version of crypto,
[39:18] SPEAKER: the Necrodancer on the switch to see how it was sure. And it didn't impact my ability to
[39:24] SPEAKER: play that game, but also I am super shitty at that game. So maybe it's a bad, bad test for me.
[39:29] SPEAKER: I've played a ton of crypto, the Necrodancer on switch. I love that game. You should,
[39:33] SPEAKER: did you do the calibration or actually does it have calibration in handheld mode?
[39:38] SPEAKER: I don't think it does the calibration in handheld mode, but I can't remember.
[39:41] SPEAKER: They can make assumptions about the response time, the handheld hardware anyway.
[39:47] SPEAKER: But but so here's the thing in terms of usability and lifestyle and the amount of like,
[39:55] SPEAKER: I use those every single day. The, the ANC stuff is so good that when it's like loud here and I
[40:01] SPEAKER: want to take a nap, I just put them in my ears and close my eyes. And it's maybe a little dangerous
[40:05] SPEAKER: because I don't hear people like people have to come touch me to wake me up because I won't hear
[40:09] SPEAKER: them come into the room. I think that the, the assumption that I read, I think it was MKBHD said
[40:17] SPEAKER: that he thinks that the increase in ANC that they said from the twos to the threes were because of
[40:22] SPEAKER: the new tip design, not because of anything that changed in the actual electronics really.
[40:26] SPEAKER: I think they said that too, that the ice of the new, the better isolation was a big part
[40:30] SPEAKER: of the new ANC. So if you're using the soft foam, if you, if you get the aftermarket soft foam tips,
[40:35] SPEAKER: you're going to be like two thirds of the way there with the old ones, which is why I'm not
[40:38] SPEAKER: upgrading. Sure. Like I, they are phenomenal. It's a phenomenal sound quality aside in terms of like
[40:48] SPEAKER: what it does, the transparency and adaptive modes when you're walking around out in the world. Like
[40:52] SPEAKER: if I'm walking around with them on and I want to not have people sneak up on me, you put the
[40:57] SPEAKER: transparency mode on or the adaptive mode on it just filters out like the filters out the traffic
[41:02] SPEAKER: noise of the city, but you still hear people talking and footsteps and dogs barking and stuff
[41:07] SPEAKER: like that. So yeah, they would be so much more convenient on for travel and on flights that I
[41:11] SPEAKER: think I would, I think I would, frankly, if I care enough about switch latency, I would rather,
[41:15] SPEAKER: I could still just bring my old wired noise canceling buds for the switch if I really care
[41:21] SPEAKER: that much, but the otherwise the AirPods would be so much more convenient. Yep. Do you want to talk
[41:27] SPEAKER: about, let me, let me hit one or two more updates. One is that I bought after giving you a bunch of
[41:34] SPEAKER: grief for it. When I was at central computer a few weeks ago, I bought this guy. When did you
[41:39] SPEAKER: give me grief for it? What is griefable about that? Those things are super useful. When we were
[41:46] SPEAKER: at a micro center and you were like, Oh, and I was like, Hey, you can just buy a USB adapters for
[41:52] SPEAKER: your external drive problem that you were having back making your, your backup images. I was like,
[42:01] SPEAKER: why don't you just buy five of these external USB-C to SATA docks? And so I went ahead and
[42:09] SPEAKER: bought one because I was at central and they had them and they were like, it was like 10 bucks.
[42:12] SPEAKER: This thing is fricking awesome. This is okay. This is USB-C to SATA to be clear. Yeah. It's
[42:17] SPEAKER: USB-C to SATA and it has like a hard connector that just lines up with both the power and the
[42:23] SPEAKER: data. So I had one of these before that was an external dongle and you had to have a big giant
[42:28] SPEAKER: power brick with a molex to the SATA connector and all the huge pain in the ass kind of was iffy
[42:33] SPEAKER: working. This thing is a packaged product. I just plug it into the front port of my computer and
[42:38] SPEAKER: plug whatever physical spinning hard drives, SSDs, it doesn't matter. So everything works.
[42:43] SPEAKER: That's the distinction here then. Cause I've got, I've had a couple of those that are old USB-A
[42:47] SPEAKER: 3.0 to SATA for years. Right. So they're great for SSDs. They, there's no way they would power
[42:54] SPEAKER: these 7,200 RPM hard drives that I, or these are maybe 5,400, but still I don't think I would power
[42:59] SPEAKER: power three and a half inch platter drives, but is that thing like explicitly designed to do that?
[43:05] SPEAKER: It says on the back SSD 2.5 inch hard drive and SSD with any capacity. I have not tried to put a
[43:14] SPEAKER: 10 K hard drive onto it. Sorry. Did you say 2.5 inch? 2.5 and 3.5 inch. It says on the package,
[43:22] SPEAKER: it'll do three and a half inch. Okay. That's all right. Well, if they're saying, I mean, you know,
[43:26] SPEAKER: USB-C can deliver quite a bit of power. Yeah. It's been pretty good so far. I put several big,
[43:33] SPEAKER: giant old 7,200 RPM hard drives on it at work. So, and this is a unit tech smart link Manta
[43:40] SPEAKER: is what it is. I mean, now motherboards just need to start shipping more high power USB-C ports.
[43:46] SPEAKER: Yeah. Yeah. That's true. That would be nice. Cause they were usually only like one or two on there.
[43:52] SPEAKER: Yeah. This, this saved me from having to open up the case when I had wanted to pull
[43:56] SPEAKER: some stuff off of an old SSD that was my daughter's computer that I'd pulled out.
[44:00] SPEAKER: Yes. Yeah. That's useful stuff to have around. I inherited a kind, a kind friend
[44:08] SPEAKER: handed down his it's a Sabrent like two hard drive dock. You definitely, you definitely saw
[44:14] SPEAKER: these things around the whiskey media office. Like we definitely, it's basically the little,
[44:17] SPEAKER: you plug the hard drive in like it's a video game cartridge. This is a, this is a two bay one.
[44:22] SPEAKER: And this one is powered. It does have an external brick and it's USB three out, but it's nice to
[44:28] SPEAKER: have some option, whether it's the newer USB-C adapter you just bought or this, this dock that
[44:32] SPEAKER: I've got now, it's nice to have an option to just plug loose hard drives into a machine without
[44:37] SPEAKER: having to open the machine up and essentially turn it off to plug a hard drive into the board.
[44:42] SPEAKER: Absolutely. I had one of those docks that I ended up getting rid of just cause it was,
[44:46] SPEAKER: it was so big and it had a huge giant power brick and like I didn't, it took up more space
[44:51] SPEAKER: than for the amount of times I used it. It took up a lot of space. This thing I can coil up and
[44:56] SPEAKER: put in a drawer and when I needed it, I'll just go buy another one. Cause I won't be able to find it
[45:00] SPEAKER: in the drawer probably. So there you go. Yep. You want to talk about VR virtual reality?
[45:07] SPEAKER: This is somewhat random. I'm not quite sure what spurred me to this other than I was just kind of
[45:12] SPEAKER: curious about it. Have you heard about the Oasis driver for the windows mixed reality headsets?
[45:18] SPEAKER: Yeah. This is the thing that unjail breaks the, the mixed reality headsets and like make some
[45:23] SPEAKER: work without that bad mixed reality interface thing that Microsoft had. Well, yeah. So there's
[45:28] SPEAKER: no jailbreak involved. This is in fact, I don't have this in front of me, but I'm positive. I
[45:32] SPEAKER: have read at some point this driver was written by a Microsoft employee. I believe this was written
[45:36] SPEAKER: by somebody who worked on the mixed reality headsets. It seems like a thing. Yeah. I'm honestly,
[45:41] SPEAKER: I'm kind of surprised that Microsoft didn't just open source the whole thing and be like,
[45:45] SPEAKER: Hey, community, here you go. There might be some weird thing there because the driver he
[45:49] SPEAKER: has written is explicitly closed source. Like he said, he's not going to open source it. There
[45:53] SPEAKER: might be proprietary stuff in there that is dodgy to make open. I'm not sure. I think we've talked
[46:00] SPEAKER: about this in the past though, the Microsoft fully entirely killed support for the windows
[46:05] SPEAKER: mixed reality headsets. I think it was 24 H two of windows 11 that removed entirely removed the
[46:12] SPEAKER: software stack that you need to run those things. So they were basically just completely dead
[46:15] SPEAKER: useless e-waste. Now this driver is out and I did some digging into what it would actually
[46:21] SPEAKER: require to use it. Cause I was really curious. I have not actually set this up myself for reasons.
[46:28] SPEAKER: I will explain in a minute. Okay. But I did look into it. The driver it's called Oasis driver for
[46:34] SPEAKER: windows mixed reality is the full title is on steam. It's free. You can just go on steam and
[46:38] SPEAKER: add it to your library and run it. And then at that point, once you have it installed,
[46:43] SPEAKER: it just runs steam VR games like anything else. So in a lot of ways, this is better than the
[46:49] SPEAKER: old setup, I think. Oh yeah. This is what everybody wanted. Did you have a windows
[46:53] SPEAKER: mixed reality headset? I had to have one to test stuff. So I have a Lenovo headset.
[46:57] SPEAKER: Okay. I've also got the Lenovo Explorer. I bought it because like it was, it was one of those deals
[47:02] SPEAKER: where like shortly after it came out, it became clear the whole product line was kind of moribund.
[47:07] SPEAKER: So they immediately fire sale priced it. Yeah. It was like a hundred bucks or something
[47:12] SPEAKER: ridiculous. I got the like deluxe package with controllers that launched at four 50,
[47:17] SPEAKER: except I paid one 99 for it two months after it came out. But you remember it had the whole
[47:24] SPEAKER: windows. It was a huge mess using it with stuff like steam VR, because it had the windows mixed
[47:28] SPEAKER: reality portal that was Microsoft's own like steam VR home like space. You remember that?
[47:34] SPEAKER: Yeah. Well, it was like a layer that lived on, like basically you had to launch into that and
[47:39] SPEAKER: then you launched steam VR. It was a huge mess because you loaded into Microsoft's version was
[47:44] SPEAKER: you were on top of a skyscraper. Remember that mid-century modern house with a bunch of screens
[47:50] SPEAKER: everywhere. So you had to load into one virtual environment and then from within that environment
[47:54] SPEAKER: load into the other steam VR virtual environment. Like it was just a giant mess. It was the bad
[47:59] SPEAKER: version of cyberpunk. This drive. Yeah. Yes. You had to incept deeper. This was this driver removes
[48:04] SPEAKER: that entire thing. Like the whole windows mixed reality portal, the entire Microsoft stack is gone.
[48:10] SPEAKER: Like effectively running this driver turns a mixed reality headset just into a generic steam VR
[48:15] SPEAKER: headset. So like room set up is all done through steam VR. Like everything that you would do to
[48:20] SPEAKER: configure the headset is all effectively just a steam VR experience. Now it's almost like if they
[48:26] SPEAKER: had done this in the first place, they'd people would still be making those headsets, but then
[48:30] SPEAKER: they wouldn't be able to embrace and extend into the headset anyway. The compatibility matrix for
[48:37] SPEAKER: this is slightly rough. It does not work on any version of windows 10, unfortunately, but also
[48:42] SPEAKER: the mixed reality portal still works on windows 10. So you don't need it. Did they not deprecate
[48:46] SPEAKER: it from 10? They didn't deprecate it on 10. Oh, interesting. Okay. Well, that's fine then
[48:50] SPEAKER: on Nvidia, you need 23 H2 or newer of windows 11 on AMD, you need 24 H2 or newer, and it does not
[48:56] SPEAKER: work on Intel GPUs at all. So, okay. So the Intel GPU thing sucks, but the needing 24 H2 is fine
[49:04] SPEAKER: because it goes away on 24 H2. If you're on 23 H2, just stay, stay on the old portal and it works.
[49:09] SPEAKER: Well, I can also, um, I should say 23 H2. I'm still running 23 H2 and support for that ends
[49:15] SPEAKER: in a month. So it's time to, it's time to move on. 25 H2 is in the wings. It's just waiting there,
[49:22] SPEAKER: ready to break your shit. Yeah. There there's a little unlock process you have to do, which again,
[49:26] SPEAKER: I have not done myself, but I went through the tutorial for it per headset and per computer.
[49:31] SPEAKER: It's a one-time process, but it's basically just like launching the thing from steam,
[49:35] SPEAKER: clicking unlock, and then it like pops up a terminal window and you have to plug and unplug
[49:39] SPEAKER: the headset and then it just does the thing. And that's it. That's the jailbreak as I understand
[49:44] SPEAKER: it. Right. It looks like it takes 10 seconds and you only have to do it once per computer,
[49:48] SPEAKER: per headset. Even if you unplug and replug the headset, you don't have to do it again.
[49:51] SPEAKER: Yes. Yeah. It's not every time you use the headset it's once, unless you wipe and reinstall windows
[49:56] SPEAKER: or change to a new computer, you do it once and that's it. Okay. That's awesome. So like,
[50:00] SPEAKER: it seems awesome that this exists. And like, if everything I've read from people using it,
[50:03] SPEAKER: it seems like it works just fine. Um, it's I love resurrecting old hardware, just like pulling that
[50:08] SPEAKER: raspberry PI one out of a box to turn it back into an AirPlay target is very satisfying to me. Like I
[50:13] SPEAKER: put my previous router that I was using before I got this edge router. Uh, I I'm using that as a
[50:18] SPEAKER: wireless bridge for my mister, which is across the room, not near ethernet, you know, like it's just
[50:23] SPEAKER: nice to use old stuff for new purposes, but it's, it's rad that people can use their mixed reality
[50:29] SPEAKER: headsets now in a kind of better, more convenient fashion than they used to. I will pull this out
[50:33] SPEAKER: of the, to go to e-waste pile and put it back in the, give to a friend pile. Yes. Now the reason I
[50:39] SPEAKER: have not tried this myself, I started to, but there's two things. Number one, my mixed reality
[50:43] SPEAKER: headset is buried deep in the closet. Now, like it would be pulling out a lot of boxes and going
[50:48] SPEAKER: through, pulling stuff out. The other reason is I was, I started to do that. And then I was like,
[50:52] SPEAKER: you know what, before I do that, I should give the PlayStation VR two PC adapter another shot. Oh,
[50:57] SPEAKER: cause I tried that thing when it came out a year ago, one of the eight people that bought a
[51:02] SPEAKER: PlayStation VR two, it seems, I mean, it's a nice headset. I know there are nicer PC headsets now,
[51:07] SPEAKER: but it's, it's way nicer than that Lenovo Explorer I've got. I will tell you for the price, it is a
[51:12] SPEAKER: pretty banger headset. Yeah. That's, that's the, that's the vibe I've gotten from the VR
[51:16] SPEAKER: enthusiast community on PC is it's not the best headset out there, but for, and especially because
[51:20] SPEAKER: I've discounted the hell out of it now, it's even cheaper than it was at launch. And like for the
[51:25] SPEAKER: price, it's a very good headset. I had a lot of problems with that adapter when it came out. I
[51:29] SPEAKER: think that was a year ago. I think it was last fall. Like I had, I had like stuttering bad
[51:35] SPEAKER: tracking on the controllers. Like it just was not a usable experience for me reason. I tried. So
[51:41] SPEAKER: again, I was like, eh, let's just do the due diligence and see if that is VR twos and stuff
[51:46] SPEAKER: is any better before I get out. The MR worked fine. It worked flaw, basically flawlessly.
[51:53] SPEAKER: So as awesome as it is, is that that Oasis driver is out for the MR headsets. Now, I guess I don't
[51:58] SPEAKER: need it because I went through the whole onboarding pairing process for the PSVR two again yesterday
[52:04] SPEAKER: on the PC. And it all just worked. Like I don't have a lot more to say there other than like, Oh,
[52:11] SPEAKER: it did pull updates for both controllers and the headset pulled updates through the PC app,
[52:17] SPEAKER: the Sony PC app that launches out of steam. So I don't know if maybe they've updated some things
[52:21] SPEAKER: to make it work better. Like I had, like I said, I had major controller tracking issues a year ago,
[52:27] SPEAKER: but they have a little utility in there that tests like Bluetooth quality. And I was getting like
[52:32] SPEAKER: 97, 98% signal strength on the Bluetooth or the controllers. So like it just kind of worked.
[52:38] SPEAKER: Is the only way to buy that thing still in the horizon called the mountain bundle?
[52:42] SPEAKER: The adapter or the VR thing. Wait, what do you mean VR thing? The headset?
[52:47] SPEAKER: The VR headset. Oh no, it looks like there's a standalone skew that just should be,
[52:51] SPEAKER: Oh, it's not any cheaper as the, as the thing it's like 400 bucks for the bundle or for the
[52:56] SPEAKER: standalone headset. Okay. Do you, do you have to buy a separate dongle to work with the PSVR
[53:01] SPEAKER: on the PC? The dongle is, I can't remember how much it might be like 50 bucks. That seems like
[53:07] SPEAKER: the cheapest they would be willing to sell you something. Just 60 bucks. It's $60. It's just a
[53:11] SPEAKER: little USB breakout box that you, that you plug display port and USB into and then the headset in.
[53:17] SPEAKER: So it's basically 450 bucks and you get a, a 460. Yeah. 460 to use it on a PC. Yeah. That's pretty
[53:23] SPEAKER: good. Yeah. It's not bad. I mean, I don't know if that, I don't, if you were only buying it for PC,
[53:27] SPEAKER: I don't think I'd say to get this one necessarily. I don't, I don't, I don't know how well Sony's
[53:32] SPEAKER: going to support it over time. I'm guessing I would not hold my breath for there to be a lot
[53:37] SPEAKER: of long-term support for that adapter. Like if you really just want a PC headset, I think you're
[53:42] SPEAKER: probably better off getting a PC headset, but if you, if you want to play one of the five PSVR two
[53:46] SPEAKER: games on PlayStation as well, then it's a better option, I guess. I mean, the thing is the PC
[53:51] SPEAKER: headsets have all gotten really expensive, like the big screen and all those are all like,
[53:54] SPEAKER: they're premium for real enthusiasts. It seems like that market has skewed upward toward the
[54:00] SPEAKER: people who really want a premium VR experience. Cause those are the only people still using VR.
[54:04] SPEAKER: And I think I'd buy the PlayStation thing rather than buying like the quest three S and so
[54:10] SPEAKER: basically this is the same price as a meta quest three, cause that's four 99. So like, yeah,
[54:17] SPEAKER: I don't know. That feels pretty good. Yeah. It's yeah. I mean, again, like I,
[54:21] SPEAKER: my experience has been better now, but like a lot of people have Bluetooth issues with
[54:25] SPEAKER: like adapters not working and stuff. Like I don't know that it's the most compatible PC VR
[54:31] SPEAKER: experience. Like it might be worth a shot if you're looking for a PC headset, but it is wired
[54:37] SPEAKER: still. Right. Yes, it is wired. So that is the, that is the knock. Yeah. It's not, not my favorite,
[54:42] SPEAKER: but I didn't use it a ton yesterday, but I will say like, stop me if you've heard of this one
[54:47] SPEAKER: before that it should, the steam VR home sure looked way better than on that old man. One is
[54:53] SPEAKER: reality headset, much, much higher resolution, low led screens versus the lower res LCDs and
[55:00] SPEAKER: that thing. Like it was just like, Oh wow, this is what this is supposed to look like.
[55:04] SPEAKER: Yeah. Even, even like the last wave of mixed reality headsets, like the Samsung mixed reality
[55:08] SPEAKER: headset, the last wave one was fucking great compared. It was up there with the index compare
[55:13] SPEAKER: in terms of image quality, which was the Samsung Odyssey plus was like the, the MR headset to get,
[55:20] SPEAKER: I kind of wish I had like gotten that on fire sale, but well, and like the, and like it was
[55:25] SPEAKER: comparable to the index and then the index is now not, not the state of the art obviously anymore.
[55:30] SPEAKER: Cause it's been five years since that thing came out. But anyway, like I VR it's back,
[55:35] SPEAKER: get back to me in like two years. There's so many games coming out right now that I will never have
[55:39] SPEAKER: time for this, but I think I could actually like play half-life Alex now finally on this
[55:43] SPEAKER: PS VR would be a good experience. You should play half-life. Alex is so freaking good. It's it's
[55:49] SPEAKER: like, like one day we're going to look back on half-life Alex. Like we do the vet track Vectrex
[55:53] SPEAKER: now. Right. I walked around this basically all I did after I got, got it working yesterday was,
[55:58] SPEAKER: you know, all those environments that you can download in steam VR home to walk around in.
[56:01] SPEAKER: There's one in there. That's like somebody, I don't forget the character's name, but it's
[56:04] SPEAKER: somebody's lab from half-life two or from half-life Alex. Oh, is it Kleiner's lab or
[56:09] SPEAKER: Kleiner? It's somebody else. I don't remember the name. Maybe I can't remember, but you may have
[56:15] SPEAKER: seen it. There's like a button and a shelf that you can press to the shelf descends and reveals
[56:20] SPEAKER: the hidden lab. And you can walk around. Anyway, you can see the hand attachment from that game.
[56:24] SPEAKER: You remember that the little mechanical glove that has your like hearts, the health meter on it and
[56:30] SPEAKER: stuff like just walking up to and looking at that little hand controller in like the diegetic health
[56:36] SPEAKER: meter stuff made me really want to play half-life Alex all of a sudden. You should do an Alex
[56:42] SPEAKER: stream. I've streamed VR before. I don't know if I'm eager to go back to that. You, there are ways
[56:50] SPEAKER: you can do that that will work and be a better viewing experience than you've had in the past.
[56:54] SPEAKER: Maybe, maybe. Anyway, the main thing is there is an unbelievable amount of stuff in this room right
[57:00] SPEAKER: now. Well, that's true. A lot of it that I need to prep for donation or storage in the closet or
[57:04] SPEAKER: selling. And if, and when I ever get that done in five years, there will be a ton of floor space in
[57:10] SPEAKER: this room. So actually it's true. It will be a very good VR space at that point. That's true.
[57:15] SPEAKER: I think that says, Oh, I have one last hit. So I moved everything hanging under the PC and I got
[57:20] SPEAKER: rid of that spine that was doing my cable management from the floor to the desk. So for
[57:24] SPEAKER: the sit stand desk, mainly because of the spine broke eventually, which was disappointing because
[57:29] SPEAKER: it was not an expensive thing. But I got a vivo heavy duty under desk mount for the PC. I talked
[57:36] SPEAKER: about this a little bit a couple months ago, but I've had it up now long enough that I'm willing to
[57:40] SPEAKER: like give it a wholehearted endorsement. It's it's I got rid of the spine because now I'm hanging the
[57:45] SPEAKER: PC and most of the cables are all just all at desk level, not going to the floor. So yeah, I have this
[57:53] SPEAKER: under desk mount is basically like two metal loops with some grabbers on the bottom and a couple of
[57:59] SPEAKER: slides and you kind of slide one side off to get access to the PC. You can actually slide it open
[58:05] SPEAKER: enough that I don't have to take it all the way out if I just want to open up the side and like
[58:08] SPEAKER: dust it out or whatever. It's been, it's been super good. I'm a big fan of, of how it works
[58:14] SPEAKER: and it's made the sit stand much more manageable. So now I've also gone and there's a bunch of
[58:22] SPEAKER: people that sell like 3d printed mounts for specific audio devices that you can then use
[58:29] SPEAKER: them to fasten things up underneath the desk. So like, I got one for my steel series headset box.
[58:34] SPEAKER: I got one it's a little more generic, I think for the Motu. I didn't, I couldn't find one that was
[58:38] SPEAKER: specific for the Motu M4. Oh, wait a minute. Yeah. What are these attached to? Like I am,
[58:43] SPEAKER: I am like obsessed with mounting things under my desk. I am, I'm obsessed with just hiding all of
[58:48] SPEAKER: my technology. So I don't see it. I like a nice tidy desktop and like, I've got an Astro Pro
[58:54] SPEAKER: TR mix amp. I've got this Motu M4. I've got this rack mounted DBX. Like not all of it is mounted
[59:00] SPEAKER: currently. Some of it is, but like I, anyway, go on. What is, what is, what is this thing called
[59:04] SPEAKER: that you're talking about? Well, so they're just like little, they're little 3d printed,
[59:07] SPEAKER: basically they're sides. Oh, these are all just like, I thought, I thought you meant this was
[59:10] SPEAKER: like some commercial product line. This is all just like user design stuff. Well, no, they're
[59:15] SPEAKER: commercial printed. Like, like that's the thing is commercial printing is a real thing now. Like if
[59:18] SPEAKER: there's print farms, I thought you meant this was like, I needed to just go on thingiverse and
[59:22] SPEAKER: download a thing and print it myself or something. I mean, I'm sure you can do that for a lot of this
[59:26] SPEAKER: stuff. The ones that I, I, I figured was worth $12 to just pay somebody to do that work for me.
[59:32] SPEAKER: Of course. You know, what we're talking about, some of the equipment we're talking about is
[59:36] SPEAKER: not light. Like this Motu M4 is largely made of metal. Like it needs a pretty sturdy mount. And so
[59:41] SPEAKER: well, so, but if that's something that's strong enough, if the thing that the things that I bought
[59:46] SPEAKER: are printed like a hundred percent infill. So they're solid plastic. And like, I, I had to
[59:52] SPEAKER: kind of eyeball it to realize it was a 3d printed 3d printed item. So basically it's just, you, you
[59:59] SPEAKER: get the two sides and I think the Motu one is they do the same one for the M2 and M4 because they're
[1:00:05] SPEAKER: the same shape, but just wider. And then you place them further apart and then you can either screw
[1:00:11] SPEAKER: them into the bottom of your desk. You can put like double-sided foam tape or something on them.
[1:00:15] SPEAKER: If you want, I suppose you could do nano tape if you wanted to live on the edge. But they just go
[1:00:20] SPEAKER: up underneath the desk and then you have access to them at the depth that you want without having
[1:00:26] SPEAKER: to do anything else. So I have like my headphone dongle thing is there. My my headphone, I have a
[1:00:33] SPEAKER: hook to hang the headphones on underneath the desk. I have the Motu down there. All of that
[1:00:38] SPEAKER: stuff is just under the desk. So now my desk is free to get filled with crap, just the way I like
[1:00:42] SPEAKER: it. And it's fantastic. Great. Highly recommended. Is the motorized desk, the sit-stand desk you're
[1:00:48] SPEAKER: using like it doesn't have any problem with the extra weight of the PC? It hasn't so far. It's
[1:00:53] SPEAKER: rated for up to 250 pounds. I don't know where near 250 pounds. Okay. Yeah. I, and I do, I did
[1:01:00] SPEAKER: make an effort. So I think at some point I'm going to move the streaming PC over here too and hang it
[1:01:04] SPEAKER: on the other side, just down low. Just balance the center of gravity on the desk. Well, I, but
[1:01:10] SPEAKER: also the streaming box, I'm getting ready to move it to a, uh, uh, an ITX machine, uh, because I've
[1:01:16] SPEAKER: been testing external and internal capture cards lately. And it turns out the USB-C 3.2 external
[1:01:23] SPEAKER: capture cards are indistinguishable from the internal capture cards. Um, if I ever moved more
[1:01:30] SPEAKER: fully to Linux, I might have to think about that because I'm, I'm in the worst possible situation
[1:01:34] SPEAKER: of using an internal Elgato capture card, which has the least possible Linux support.
[1:01:39] SPEAKER: Look, I will tell you my Avramedia 4k internal capture card is just a PCI express to USB bridge
[1:01:48] SPEAKER: and it works perfectly in Linux. Yeah, I believe it. The one we should wrap this up. I don't need
[1:01:52] SPEAKER: to go down this rabbit hole. The one nice thing about that Elgato card I use is that, and I don't
[1:01:55] SPEAKER: remember how they're doing this exactly. It does not present an exclusive video source to windows.
[1:02:00] SPEAKER: Like, you know, most devices it's like, if OBS is using it, then you can't also open it as a device
[1:02:05] SPEAKER: in like a video call because it'll just be like device in use or whatever. That Elgato card is
[1:02:09] SPEAKER: able to multiplex the video source so that you can use it in as many apps as you want simultaneously,
[1:02:15] SPEAKER: which is super nice, but it works like the virtual cam that OBS basically kind of seamlessly,
[1:02:21] SPEAKER: which is, it turns out to be really convenient. But anyway, I guess that'll do it for us today.
[1:02:25] SPEAKER: Yeah. Yeah. Hopefully there's some stuff in there that you, the listener found useful or
[1:02:29] SPEAKER: interesting to follow up on. Yeah. I'll, I'll put links for the stuff I talked about. We'll
[1:02:36] SPEAKER: put them in show notes, I guess, whether you see them in your client or not is up to your client,
[1:02:40] SPEAKER: because you can always go to techpod.content.town and they'll be there or we'll put them in there.
[1:02:44] SPEAKER: I'll put, I'll put stuff in the thread in the discord, if you're in the discord too.
[1:02:48] SPEAKER: And if you want to get in the discord, you're not in there. You can do that by joining the Patreon
[1:02:52] SPEAKER: and supporting the podcast. We're listening to support it. So we're not here. If it weren't for
[1:02:55] SPEAKER: you, we wouldn't be here. And if you want to find out how you can support the show, you can go to
[1:03:00] SPEAKER: patreon.com/techpod. Again, it's patreon.com/techpod where for five bucks a month,
[1:03:05] SPEAKER: you get access to the discord. You get the monthly patron exclusive episode.
[1:03:10] SPEAKER: And you support the show. Like I said, we appreciate each and every one of you.
[1:03:15] SPEAKER: We do. But we especially appreciate our executive producer tier supporters, including Jason Lee,
[1:03:22] SPEAKER: Infelicitous Rips, Andrew Slosky, Jordan Lippett, Bunny Money, Twinkle Twinkie, David Allen,
[1:03:29] SPEAKER: James Kamik, and Pantheon, makers of the HS3 high-speed 3D printer. Thank you all so much.
[1:03:35] SPEAKER: Thank you to everyone.
[1:03:37] SPEAKER: And that'll do it for us this week. We'll be back next week with another edition of The Tech Pod.
[1:03:43] SPEAKER: As always, please consider the environment before printing this podcast.
