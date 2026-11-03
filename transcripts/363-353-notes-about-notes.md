---
episode: 363
title: 353: Notes About Notes
date: 2026-08-23
guests: none
duration: 1:18:17
---

[00:00] SPEAKER: Did I ever tell you what caused my problem
[00:04] SPEAKER: a couple of weeks ago?
[00:05] SPEAKER: - Did I ever tell you the tale?
[00:06] SPEAKER: - Let me tell you, sit down, Brad.
[00:08] SPEAKER: Let's talk about-
[00:09] SPEAKER: - Sitting around the campfire
[00:10] SPEAKER: and talking about your audio routing.
[00:12] SPEAKER: - Well, you know what?
[00:13] SPEAKER: It wasn't anything audio related for me.
[00:16] SPEAKER: So a couple of weeks ago, we were sitting down to record
[00:19] SPEAKER: and I was in my Linux install, just like I always am.
[00:21] SPEAKER: And things suddenly were inexplicably weird with Audacity.
[00:26] SPEAKER: And it was throwing an error about not enough disk space.
[00:29] SPEAKER: And then when I looked at the amount of disk space
[00:31] SPEAKER: in my home folder, totally fine.
[00:33] SPEAKER: But then I looked at the disk space on root
[00:36] SPEAKER: and it was like, you have zero megabytes available on root,
[00:39] SPEAKER: which turns out to be not good.
[00:41] SPEAKER: - That's bad.
[00:42] SPEAKER: - It was bad.
[00:43] SPEAKER: - I'm an expert, I can tell you that's bad.
[00:45] SPEAKER: - Yeah, and so I looked at it
[00:46] SPEAKER: and I couldn't figure it out in three seconds.
[00:48] SPEAKER: So I did the thing that I do
[00:50] SPEAKER: and cowardly rebooted into Windows
[00:52] SPEAKER: 'cause we were both on a timeline
[00:53] SPEAKER: and had to get the episode done.
[00:56] SPEAKER: And then I came back to it later and I was like,
[00:57] SPEAKER: oh, how do I deal with this?
[00:58] SPEAKER: And what happened was I had apparently at some point
[01:02] SPEAKER: reinstalled Snapper and not set up Snapper culling.
[01:06] SPEAKER: So I had 350 gigabytes of Snapper images filling the drive.
[01:13] SPEAKER: - That'll do it, some snapshots, you mean?
[01:15] SPEAKER: - Snapshots, yeah, yeah.
[01:16] SPEAKER: - Yes, okay.
[01:17] SPEAKER: - And yeah, when I got rid of the last 900 of those,
[01:23] SPEAKER: everything was cool again.
[01:24] SPEAKER: - Look, when you absolutely positively
[01:26] SPEAKER: need to be able to roll back to any point in time
[01:29] SPEAKER: separated by an interval of about 15 minutes
[01:31] SPEAKER: for the last six months?
[01:33] SPEAKER: - I think I had it set to an hour, but yeah.
[01:36] SPEAKER: And yeah, it turns out I could have rolled
[01:38] SPEAKER: all the way back to the moment after the first install
[01:41] SPEAKER: of Cache OS on this machine.
[01:43] SPEAKER: - Were those the defaults?
[01:44] SPEAKER: That seems crazy to me to not ship
[01:46] SPEAKER: with a culling policy in place.
[01:48] SPEAKER: - Well, so this is the rolling distro thing, right?
[01:51] SPEAKER: Is that sometimes they put new features in
[01:53] SPEAKER: and then they add the defaults in
[01:54] SPEAKER: and if you've adjusted those files
[01:56] SPEAKER: between the time those two things happen,
[01:58] SPEAKER: then you don't get the new defaults.
[01:59] SPEAKER: - Trust me, I've seen the Noctolia V4 to V5 calamity
[02:03] SPEAKER: that's going on right now.
[02:05] SPEAKER: - So I thought I had that one yesterday too,
[02:07] SPEAKER: 'cause I've been watching that
[02:08] SPEAKER: and I've been very careful doing updates to it
[02:10] SPEAKER: 'cause I'm a Noctolia guy.
[02:11] SPEAKER: - Yeah, but I bet it wasn't that.
[02:12] SPEAKER: I bet it was the Linux kernel 7.2 driver video issue.
[02:17] SPEAKER: No, 'cause I saw that also was breaking some cachey installs.
[02:20] SPEAKER: - No, you know what I did that was stupid?
[02:22] SPEAKER: This was all me again.
[02:23] SPEAKER: I had updated my Neary config
[02:26] SPEAKER: with a change that made it not validate.
[02:30] SPEAKER: And so when it booted into Neary,
[02:31] SPEAKER: it just didn't read the config file
[02:33] SPEAKER: 'cause it didn't validate.
[02:34] SPEAKER: And so I had the thing with the cachey Noctolia V4 to V5
[02:40] SPEAKER: on my laptop.
[02:42] SPEAKER: And I fixed that by reinstalling,
[02:45] SPEAKER: 'cause the neat thing about the Noctolia stuff
[02:46] SPEAKER: is V4 and V5 can live next to each other.
[02:48] SPEAKER: There's no incompatibilities.
[02:50] SPEAKER: You just have to reinstall Noctolia V4
[02:52] SPEAKER: and re-enable two background services
[02:55] SPEAKER: to make it work again immediately.
[02:57] SPEAKER: Literally, when I fixed it on the laptop,
[02:59] SPEAKER: I just shelled to a different terminal
[03:02] SPEAKER: and logged into text mode and booted it up,
[03:06] SPEAKER: installed those two packages,
[03:07] SPEAKER: and restarted the GUI and everything was fine.
[03:11] SPEAKER: - Yeah, that's cool, I guess.
[03:12] SPEAKER: I guess we should say, just for people who don't know,
[03:14] SPEAKER: I guess the issue is that V5,
[03:17] SPEAKER: they have rewritten the thing in a native framework.
[03:19] SPEAKER: It used to be written in Quickshell.
[03:20] SPEAKER: - Yeah, so Quickshell is like a framework
[03:23] SPEAKER: for UI tooling at an OS level.
[03:28] SPEAKER: And Noctolia is the thing that provides
[03:30] SPEAKER: kind of the things that I think
[03:31] SPEAKER: most people think about their OS,
[03:32] SPEAKER: like the launcher menu and the taskbar
[03:35] SPEAKER: and all the kind of the placement of windows
[03:41] SPEAKER: and all the little widgets for like Bluetooth
[03:42] SPEAKER: and wifi and all that stuff.
[03:44] SPEAKER: - Right, and so V5, they have moved away from Quickshell
[03:46] SPEAKER: and have written it in a native whatever framework,
[03:49] SPEAKER: but apparently upgrading to V5,
[03:52] SPEAKER: it's now looking for a V5 configuration
[03:54] SPEAKER: and not 'cause it does not read a V4 configuration.
[03:56] SPEAKER: And so it just kind of breaks
[03:58] SPEAKER: and this is why I will never run a rolling release
[04:00] SPEAKER: or rolling distro, I should say.
[04:02] SPEAKER: - I mean, you just gotta keep up with your updates.
[04:06] SPEAKER: It's like sheetrock mud, like when you hang sheetrock,
[04:11] SPEAKER: you gotta do muddin' every day
[04:12] SPEAKER: and you gotta keep it sanded.
[04:13] SPEAKER: You gotta apply it at night and sand it in the morning
[04:17] SPEAKER: so you can apply more at night and sand more in the morning.
[04:19] SPEAKER: - It's a strong pitch, you're in Linux,
[04:20] SPEAKER: the sheetrock hanging of operating systems.
[04:23] SPEAKER: - I mean, look, the benefit is that when something new
[04:26] SPEAKER: and hot and exciting comes out,
[04:28] SPEAKER: I get to use it before anybody else.
[04:29] SPEAKER: - Yeah, that's fine, you know.
[04:31] SPEAKER: - Depends on how you wanna live, right?
[04:32] SPEAKER: - There comes a time in a man's life
[04:34] SPEAKER: when new and hot and exciting
[04:35] SPEAKER: is maybe not so new and hot and exciting anymore.
[04:38] SPEAKER: - I mean, you're not wrong, but also,
[04:43] SPEAKER: let me tell you about the new pandoc stuff
[04:47] SPEAKER: I got the other day.
[04:49] SPEAKER: (upbeat music)
[05:18] SPEAKER: - Welcome to Brad and Will Made a Tech Pod.
[05:21] SPEAKER: I'm Will. - I am Brad.
[05:23] SPEAKER: - Hello, Brad. - Hi, hello.
[05:24] SPEAKER: - Happy Friday. - Thank you.
[05:25] SPEAKER: - Or Sunday, depending on whether you're listening
[05:27] SPEAKER: or talking. - That's right.
[05:29] SPEAKER: Temporal distortions are taking place around here.
[05:33] SPEAKER: You mentioned Audacity briefly in the cold open.
[05:36] SPEAKER: - Yeah, I did.
[05:37] SPEAKER: Is there scene drama or is this good?
[05:38] SPEAKER: - Not at all. - Okay, good.
[05:39] SPEAKER: - It seems like Audacity 4.0 might be kind of imminent,
[05:42] SPEAKER: which I'm sort of excited about
[05:44] SPEAKER: as a frequent Audacity user.
[05:47] SPEAKER: - When did we...
[05:48] SPEAKER: We talked to Tantacruel. - Tantacruel.
[05:51] SPEAKER: Yeah, on the Fosbaw. - No longer works there now.
[05:53] SPEAKER: - Yeah, he left the project.
[05:54] SPEAKER: He left the Muse group or whatever the company is
[05:58] SPEAKER: that runs Audacity now.
[06:00] SPEAKER: - So does this mean that my Audacity timeline
[06:03] SPEAKER: will finally scroll smoothly?
[06:05] SPEAKER: - Oh, they basically got...
[06:07] SPEAKER: What is the framework they run on?
[06:08] SPEAKER: WX widgets, I think is what it's called.
[06:10] SPEAKER: The pushing 30-year-old,
[06:14] SPEAKER: 25-year-old GUI that Audacity uses.
[06:19] SPEAKER: They did make some changes at some point
[06:21] SPEAKER: to make it scroll smoothly or...
[06:24] SPEAKER: - It's still chunks, man.
[06:25] SPEAKER: It's still chunks. - Yeah, it's still got...
[06:26] SPEAKER: Anyway, 4.0 is a full-on UI redo.
[06:29] SPEAKER: Like they have moved for the UI to Qt, QT, Qt.
[06:34] SPEAKER: - Ah, I love Qt.
[06:35] SPEAKER: - I guess it's pronounced cute.
[06:36] SPEAKER: I never knew.
[06:37] SPEAKER: I spent 25 years calling it Qt.
[06:40] SPEAKER: Anyway, they put out a beta 2 of 4.0 in June.
[06:45] SPEAKER: - Ooh. - I don't know
[06:46] SPEAKER: how many numbered betas they will be running,
[06:47] SPEAKER: but that does sound like probably a release is imminent
[06:50] SPEAKER: by the end of the year.
[06:51] SPEAKER: - That's promising. - Which is cool
[06:53] SPEAKER: 'cause they've got a little page up
[06:55] SPEAKER: showing what the new UI,
[06:56] SPEAKER: or you can find videos on YouTube of it.
[06:57] SPEAKER: In fact, you can download beta 2 and just install it.
[07:00] SPEAKER: But...
[07:02] SPEAKER: - Have you tried it yet? - I have not.
[07:03] SPEAKER: I'm not gonna bother until...
[07:05] SPEAKER: In fact, even when 4.0 comes out,
[07:06] SPEAKER: I'm not gonna move to it immediately
[07:07] SPEAKER: 'cause it's way, way, way too critical in my workflow
[07:11] SPEAKER: to know what my audio editor is doing.
[07:15] SPEAKER: - Very much the same.
[07:16] SPEAKER: - Probably wait until like a 4.1 to move over or something.
[07:19] SPEAKER: But I'm excited to try it
[07:23] SPEAKER: 'cause they have clearly modernized the interface
[07:25] SPEAKER: in like a profound way.
[07:27] SPEAKER: - I mean, it's made big jumps in the last,
[07:30] SPEAKER: I don't know, five years, six years.
[07:32] SPEAKER: - Ever since they took it over,
[07:33] SPEAKER: the 3.0 series has had unbelievably huge improvements
[07:36] SPEAKER: by the standards of Audacity.
[07:38] SPEAKER: - And yeah, once it stopped being a destructive editor,
[07:40] SPEAKER: all bets were off as far as I'm concerned.
[07:42] SPEAKER: - They got non-destructive in them.
[07:44] SPEAKER: They got all kinds of like meat and potatoes,
[07:46] SPEAKER: audio DAW type stuff that they should have had
[07:48] SPEAKER: for a long time.
[07:49] SPEAKER: But yeah, well, whatever.
[07:51] SPEAKER: We should talk about other software, I suppose.
[07:53] SPEAKER: But I...
[07:55] SPEAKER: My bet is they are angling to make this
[07:58] SPEAKER: the blender of the audio world.
[08:01] SPEAKER: This is what I think this is going toward.
[08:04] SPEAKER: It's like professional enough and DAW-like enough
[08:07] SPEAKER: that it's hopefully, I think they probably are hoping
[08:09] SPEAKER: it'll be like the thing everybody reaches for
[08:11] SPEAKER: if they have light to medium prosumer audio editing needs.
[08:16] SPEAKER: - So the thing I'll say about Blender
[08:18] SPEAKER: is I think Blender's actually transitioned past that.
[08:20] SPEAKER: - Okay, yeah, sure, I can see that.
[08:22] SPEAKER: Like Blender is just the standard now.
[08:24] SPEAKER: - Yeah, it's, I mean, I don't know how much you know,
[08:27] SPEAKER: like when you're doing animation
[08:29] SPEAKER: and like rig and skeleton imports into games
[08:34] SPEAKER: and stuff like that,
[08:36] SPEAKER: basically there's one pipeline for that
[08:38] SPEAKER: regardless of what tool the artists use.
[08:40] SPEAKER: And most studios that are starting now
[08:42] SPEAKER: seem to be using Blender as like the ingest.
[08:44] SPEAKER: For years and years and years, everybody used Maya for that.
[08:46] SPEAKER: - Oh, you mean even people
[08:48] SPEAKER: that have been doing it for a long time?
[08:49] SPEAKER: Like it's just what everybody is standardized on now?
[08:53] SPEAKER: - So usually you do that in like pre-pro
[08:54] SPEAKER: when you're starting a new game.
[08:56] SPEAKER: Like you establish that pipeline 'cause you don't,
[08:58] SPEAKER: but the thing you don't wanna have
[08:59] SPEAKER: is like Bob and Sue and Jim
[09:03] SPEAKER: all working on character rigs and animations
[09:07] SPEAKER: and one using Maya and one using Blender
[09:10] SPEAKER: and one using some screwy weird thing
[09:11] SPEAKER: that I don't know what it would be.
[09:12] SPEAKER: So basically you do all your stuff
[09:15] SPEAKER: in whatever tool you choose,
[09:16] SPEAKER: then you export it to the common format
[09:17] SPEAKER: and then you ingest it through the same pipeline
[09:20] SPEAKER: so that the bugs are consistent and predictable.
[09:24] SPEAKER: Anyway, that doesn't matter.
[09:25] SPEAKER: The point is there's a path from, Blender was definitely
[09:29] SPEAKER: that place that you described like 10 years ago.
[09:31] SPEAKER: And over the last, like since they won an Academy Award
[09:33] SPEAKER: for the cat movie, I think all bets are off
[09:37] SPEAKER: in terms of how seriously people take Blender now.
[09:39] SPEAKER: - That probably goes a very long way
[09:40] SPEAKER: toward legitimizing it in the professional world.
[09:43] SPEAKER: - It turns out the conversations are,
[09:47] SPEAKER: oh, that open source thing that's where weirdos change
[09:49] SPEAKER: when you do an entire feature film in the tool
[09:52] SPEAKER: and it wins awards and it's good.
[09:53] SPEAKER: - Yeah, that's fair.
[09:55] SPEAKER: Anyway.
[09:56] SPEAKER: - But we're not talking about audio today.
[09:57] SPEAKER: - No.
[09:58] SPEAKER: - We're talking about the antithesis of audio.
[10:00] SPEAKER: - Oh.
[10:01] SPEAKER: - Text.
[10:02] SPEAKER: - Oh, the written word.
[10:03] SPEAKER: - Yes.
[10:05] SPEAKER: If a picture is worth a thousand word,
[10:06] SPEAKER: a word is worth a thousandth of a picture
[10:09] SPEAKER: is my understanding.
[10:10] SPEAKER: So you and I both use notes programs.
[10:14] SPEAKER: I think everybody does at this point probably.
[10:16] SPEAKER: - Now we do.
[10:17] SPEAKER: Or I guess I kind of did before
[10:19] SPEAKER: in a very antiquated fashion,
[10:20] SPEAKER: but to-do lists are very hot these days.
[10:23] SPEAKER: I don't know if you've heard everybody's vibe coding
[10:25] SPEAKER: their own to-do list app now.
[10:27] SPEAKER: - Yep, yep.
[10:29] SPEAKER: I used Wunderlist for a long time
[10:30] SPEAKER: before vibe coding was invented.
[10:32] SPEAKER: And then I switched to to-dos
[10:34] SPEAKER: and I've used a whole bunch of different of those apps now.
[10:37] SPEAKER: - Wunderlist?
[10:38] SPEAKER: - Wunderlist got popped by Microsoft.
[10:41] SPEAKER: Wunderlist was an early iOS task list app that was,
[10:45] SPEAKER: I can't remember.
[10:46] SPEAKER: It used one of the kind of popular
[10:48] SPEAKER: getting things done frameworks.
[10:50] SPEAKER: - Oh, this kind of looks like Trello.
[10:53] SPEAKER: Or at least whatever it's turned into now does.
[10:55] SPEAKER: Like there's a large photo of a mountain range
[10:58] SPEAKER: behind your to-do list.
[10:59] SPEAKER: - Well, so I think that Microsoft turned Wunderlist
[11:03] SPEAKER: into the Microsoft to-do app, which is actually okay.
[11:06] SPEAKER: - Oh, I don't know what the Wunderlist is
[11:08] SPEAKER: that I'm looking at then.
[11:11] SPEAKER: - Well, it doesn't exist anymore.
[11:12] SPEAKER: This does look like Trello.
[11:13] SPEAKER: This was a list of lists.
[11:15] SPEAKER: Trello is more than this now.
[11:16] SPEAKER: We can talk about that.
[11:17] SPEAKER: - Different product perhaps.
[11:18] SPEAKER: But anyway, I guess this is a roundabout way of saying
[11:20] SPEAKER: I have finally, I guess I would say modernized my notes
[11:25] SPEAKER: and to-do regime, workflow, whatever you wanna call it.
[11:29] SPEAKER: And I know you have been using this stuff for years.
[11:31] SPEAKER: Anyway, since I've been going through these options
[11:33] SPEAKER: and you use some heavyweight stuff in this space,
[11:36] SPEAKER: it seems like a good time to dig back into this topic
[11:39] SPEAKER: and talk about what we're doing
[11:41] SPEAKER: and what we've discovered and such.
[11:43] SPEAKER: - We can absolutely get into that.
[11:45] SPEAKER: So I think for me, this started with Evernote.
[11:49] SPEAKER: Evernote and OneNote kind of around the same time
[11:51] SPEAKER: a hundred years ago.
[11:52] SPEAKER: - Okay, I just have to ask now,
[11:55] SPEAKER: did Evernote predate SimpleNote?
[11:59] SPEAKER: We don't need to split hairs about what came out first,
[12:01] SPEAKER: but SimpleNote's the first time I ever heard of this.
[12:03] SPEAKER: So I'm just curious if Evernote is even older than that.
[12:06] SPEAKER: - Yeah, so I was using Evernote in the maximum PC days.
[12:09] SPEAKER: - Oh, okay, that is way before.
[12:10] SPEAKER: 'Cause I didn't hear about SimpleNote
[12:11] SPEAKER: until you were working with us at Whiskey.
[12:13] SPEAKER: So that is definitely before.
[12:15] SPEAKER: - I think SimpleNote actually came off of the Diaspora
[12:18] SPEAKER: maybe of like Evernote deciding to charge
[12:22] SPEAKER: in a way that people didn't like.
[12:23] SPEAKER: So Evernote was like a Web 1.0 application almost.
[12:27] SPEAKER: It required a desktop client to access.
[12:31] SPEAKER: Yeah, it wasn't web-based at least in the beginning.
[12:35] SPEAKER: It came around after OneNote.
[12:38] SPEAKER: I think OneNote is actually maybe the grandfather
[12:40] SPEAKER: of all of these.
[12:41] SPEAKER: 'Cause Microsoft rolled out OneNote
[12:43] SPEAKER: with their first go at tablets,
[12:46] SPEAKER: their convertible laptops with the resistive pen screens.
[12:51] SPEAKER: - Oh my God, you're right.
[12:51] SPEAKER: OneNote came out in 2003, that's crazy.
[12:54] SPEAKER: 'Cause the name makes it sound like OneDrive,
[12:56] SPEAKER: which made me assume it's a later,
[12:57] SPEAKER: latter day Teams Office 365-ish thing.
[13:02] SPEAKER: - I think it's the other way.
[13:03] SPEAKER: I think OneDrive is actually named because of OneNote,
[13:05] SPEAKER: but I could be wrong.
[13:06] SPEAKER: - Interesting, okay.
[13:07] SPEAKER: - So OneNote took everything that's good about Outlook
[13:13] SPEAKER: and everything that's bad about Outlook
[13:14] SPEAKER: and made it a Notes app.
[13:15] SPEAKER: It embeds your entire huge,
[13:18] SPEAKER: your list of notes into a monolithic file
[13:23] SPEAKER: that is then these days stored in OneDrive by default,
[13:25] SPEAKER: I think.
[13:27] SPEAKER: You can do things like take pen and ink notes
[13:30] SPEAKER: and do typed notes and do sketches
[13:33] SPEAKER: and all that stuff all in one place,
[13:34] SPEAKER: which is I think really kind of low-key
[13:38] SPEAKER: the coolest thing about OneNote,
[13:39] SPEAKER: but also it's extremely Microsoft-y.
[13:41] SPEAKER: And if you're not using OneDrive,
[13:43] SPEAKER: it's a pain in the butt to sync it.
[13:45] SPEAKER: And there's a whole host of other issues with it these days.
[13:48] SPEAKER: I've stopped using OneNote.
[13:50] SPEAKER: So anyway, I used Evernote for a long time.
[13:51] SPEAKER: And then in the Whiskey Media days,
[13:52] SPEAKER: I think a lot of us switched to SimpleNote
[13:55] SPEAKER: because it was really compelling.
[13:57] SPEAKER: It was just flat text files you saved in a Dropbox folder
[14:00] SPEAKER: and it would work itself out.
[14:02] SPEAKER: - That's right.
[14:03] SPEAKER: I wrote years and years of giant bomb game reviews in,
[14:08] SPEAKER: I was using notational velocity on Mac OS.
[14:10] SPEAKER: Remember that?
[14:11] SPEAKER: - Uh-huh, yep.
[14:12] SPEAKER: - It was a great app.
[14:13] SPEAKER: - Was a great app.
[14:14] SPEAKER: In fact, SimpleNote clients never got better than that,
[14:17] SPEAKER: which is a big part of why we're here
[14:19] SPEAKER: to talk about this actually.
[14:21] SPEAKER: - So I stopped using Evernote
[14:24] SPEAKER: because they wanted to charge like $15 a month
[14:27] SPEAKER: if you wanted more than two devices
[14:29] SPEAKER: hooked up to your account,
[14:30] SPEAKER: which felt icky to me.
[14:31] SPEAKER: - That is always the killer,
[14:32] SPEAKER: is the device limit on stuff like this.
[14:34] SPEAKER: It's never the storage space.
[14:35] SPEAKER: It's always the how many end points
[14:37] SPEAKER: can you access the storage from?
[14:39] SPEAKER: - Yeah, then I switched to SimpleNote
[14:43] SPEAKER: and I stopped using that relatively quickly
[14:45] SPEAKER: because it ate a whole,
[14:48] SPEAKER: it munged up a sink on a whole bunch of folders for me.
[14:51] SPEAKER: - Interesting.
[14:52] SPEAKER: - Yeah, I don't remember why it happened or how it happened,
[14:57] SPEAKER: but it was enough that I was like, I can't trust this.
[14:59] SPEAKER: I gotta do something else.
[15:00] SPEAKER: And then I went to OneNote for a long time
[15:03] SPEAKER: and used that for quite a few years
[15:06] SPEAKER: until fairly recently when I switched over to Notion.
[15:09] SPEAKER: - The games, indie game studios and startups
[15:16] SPEAKER: are pretty universally on Notion these days,
[15:18] SPEAKER: just 'cause it's a kind of one-size-fits-all groupware tool
[15:23] SPEAKER: that you can pay a flat rate per seat in your company.
[15:27] SPEAKER: - If they're charging by the seat,
[15:28] SPEAKER: then I understand why companies are just using that now
[15:30] SPEAKER: 'cause that's the billing model
[15:34] SPEAKER: companies like to engage with.
[15:36] SPEAKER: - Yeah, and for most of this stuff,
[15:39] SPEAKER: the neat thing about Notion
[15:40] SPEAKER: and both its strength and its weakness
[15:43] SPEAKER: is that it does all of this stuff.
[15:44] SPEAKER: So if you want a bug tracking tool like Jira
[15:48] SPEAKER: and a work tracking tool like Jira
[15:49] SPEAKER: that'll let you do Gantt charts and waterfall charts
[15:52] SPEAKER: and all that kind of your agile coding business,
[15:58] SPEAKER: you can have their templates
[15:59] SPEAKER: that will let you build those pages in Notion
[16:01] SPEAKER: that are shared across everybody in your org
[16:03] SPEAKER: or the right people in your org.
[16:04] SPEAKER: - I see why, yes.
[16:05] SPEAKER: Okay, I see why that's so popular.
[16:06] SPEAKER: I will say that is way beyond the needs I had
[16:09] SPEAKER: at the outset of this, which we'll get into.
[16:11] SPEAKER: - Yeah, it is a business-ass business tool
[16:16] SPEAKER: in a lot of ways.
[16:19] SPEAKER: Like I said, Gantt charts, you can do scheduling there.
[16:22] SPEAKER: It has all these, it has a giant template store
[16:25] SPEAKER: that people have uploaded templates
[16:26] SPEAKER: that are both free and paid that will let you do things.
[16:29] SPEAKER: Like all of my time tracking for different clients
[16:32] SPEAKER: is in Notion these days.
[16:34] SPEAKER: So I have an app, I have one app
[16:35] SPEAKER: that'll do hourly tracking.
[16:36] SPEAKER: I have one app that does daily tracking
[16:38] SPEAKER: and they're different for different clients, right?
[16:42] SPEAKER: So all of my stuff, when billing comes
[16:44] SPEAKER: at the end of the month, I hit a button
[16:45] SPEAKER: and it tells me how many hours go in the invoice.
[16:47] SPEAKER: And then I just send that off to the clients.
[16:49] SPEAKER: It's very easy.
[16:50] SPEAKER: - Man, that's a lot of functionality.
[16:52] SPEAKER: - It is wildly functional.
[16:54] SPEAKER: But the thing that is neat about Notion
[16:57] SPEAKER: is that it's at core, it's just a souped up Wiki.
[17:01] SPEAKER: It's, you know, you open a page,
[17:04] SPEAKER: you can make links to another page off of any page.
[17:07] SPEAKER: You can backlink up the chain, up the tree,
[17:10] SPEAKER: you can link all over.
[17:12] SPEAKER: You can turn any block of text into anything,
[17:15] SPEAKER: any other kind of item.
[17:16] SPEAKER: So like, if you have just a bunch of lines of text,
[17:21] SPEAKER: you can turn that into a checklist by highlighting,
[17:23] SPEAKER: by selecting those lines of text, right clicking
[17:25] SPEAKER: and going to turn into, you know, checklist or task list
[17:29] SPEAKER: or whatever your item is.
[17:31] SPEAKER: It's really, really great for taking fast, dirty notes
[17:36] SPEAKER: and turning them into something that's useful
[17:39] SPEAKER: and like, you know, documenting, like working in games,
[17:43] SPEAKER: a lot of the work is documenting the stuff that you've done
[17:45] SPEAKER: and the choices you've made so that the people
[17:47] SPEAKER: who come after you can like reverse engineer
[17:49] SPEAKER: what you've done when they need to figure it out
[17:50] SPEAKER: three or four years down the line.
[17:53] SPEAKER: And a lot of studios for years used like Confluence,
[17:56] SPEAKER: which is a product that Confluence and Jira and Trello
[17:59] SPEAKER: are all the same company these days.
[18:01] SPEAKER: And so you can pay your 10 bucks a month per person
[18:04] SPEAKER: to Confluence and Jira and Trello,
[18:05] SPEAKER: or you can pay it to something like Notion
[18:08] SPEAKER: and get like all of your note-taking stuff in one place.
[18:12] SPEAKER: They've added a ton of AI stuff.
[18:14] SPEAKER: So the reason we're talking about this now
[18:15] SPEAKER: is that a lot of this has changed over the last few years
[18:18] SPEAKER: with the addition of the various levels of bad AI
[18:22] SPEAKER: and occasionally good AI.
[18:25] SPEAKER: One of the things that is pretty good on the Notion stuff
[18:28] SPEAKER: is if you're paying, you can do meeting transcriptions.
[18:30] SPEAKER: So you add it to your meetings
[18:32] SPEAKER: and you get pretty clean attributed transcriptions
[18:37] SPEAKER: of everybody on a Zoom call.
[18:39] SPEAKER: Like it'll put the person's name and put what they say.
[18:42] SPEAKER: And like you can get a nice clean transcription
[18:46] SPEAKER: for people who aren't there.
[18:47] SPEAKER: It doesn't, it offers summaries and stuff like that,
[18:50] SPEAKER: which I find to be pretty high risk
[18:53] SPEAKER: if you're not, if somebody who was in the meeting
[18:55] SPEAKER: and paying attention isn't actually going over them
[18:57] SPEAKER: 'cause it does, it has made up stuff in my experience
[19:00] SPEAKER: on those, I haven't used that in six months
[19:02] SPEAKER: 'cause it was making up too much stuff
[19:04] SPEAKER: to flip the button on and pay for.
[19:06] SPEAKER: - Honestly. - Yeah.
[19:09] SPEAKER: The other thing that it does do though
[19:12] SPEAKER: that's kind of neat these days on the AI front
[19:15] SPEAKER: is you can vibe code those apps that you want.
[19:19] SPEAKER: So like I probably wouldn't use it for the time tracker
[19:22] SPEAKER: just 'cause it's pretty simple
[19:23] SPEAKER: and there's a bunch of templates
[19:24] SPEAKER: in the download store for that.
[19:27] SPEAKER: But for, like if you had, I don't know,
[19:32] SPEAKER: if you wanted to make a content calendar for Nextlander
[19:35] SPEAKER: that had, that was really specific to your organization
[19:39] SPEAKER: and gave you like a form to type stuff in
[19:41] SPEAKER: and then multiple views to see how that data
[19:43] SPEAKER: was in the database, you could totally do that.
[19:45] SPEAKER: It would take about 10 minutes and it's pretty powerful.
[19:48] SPEAKER: I don't think that stuff's available on the free tier.
[19:51] SPEAKER: But the free tier is very robust.
[19:53] SPEAKER: You can hook multiple clients up to it.
[19:54] SPEAKER: You can share pages with people.
[19:56] SPEAKER: Like I've been on the free tier of Notion personally
[19:58] SPEAKER: for years and years and years.
[19:59] SPEAKER: It's never been inadequate for my needs.
[20:01] SPEAKER: - Oh, really? - Oh, you don't pay for it.
[20:02] SPEAKER: - So I get it through most of the people I work with
[20:05] SPEAKER: are paying for it on the accounts
[20:07] SPEAKER: that they provide me inside their intranet
[20:10] SPEAKER: or whatever you call the cloud-based intranet these days.
[20:14] SPEAKER: But yeah, I don't pay for a personal account anymore.
[20:16] SPEAKER: - Apps suite.
[20:18] SPEAKER: Like your kind of Google Workspace style groupware
[20:21] SPEAKER: seems like your Teams, your Office 365.
[20:25] SPEAKER: - The other cool thing is you can do everything
[20:28] SPEAKER: in Notion from the text mode.
[20:29] SPEAKER: Like you don't have to right click at all.
[20:31] SPEAKER: If you want to turn, if you want to make like a task list,
[20:33] SPEAKER: you can type /list.
[20:35] SPEAKER: If you want to make a new page, type /page
[20:37] SPEAKER: and then it opens up a new tab.
[20:38] SPEAKER: - That speaks to me.
[20:39] SPEAKER: - Yeah, if you're a keyboard person,
[20:42] SPEAKER: it's pretty, pretty good.
[20:43] SPEAKER: - It's nice to never lift your hands from the keyboard
[20:46] SPEAKER: if possible. - Oh, and the last thing,
[20:48] SPEAKER: and this is the thing I did at the beginning with Notion.
[20:51] SPEAKER: They provide robust tools to both export
[20:54] SPEAKER: and import data from other products.
[20:56] SPEAKER: So like it was one of the only places
[20:58] SPEAKER: I could get my old recipes out of Evernote with,
[21:00] SPEAKER: 'cause I used Evernote for recipes for years.
[21:04] SPEAKER: It will export like a big giant folder of markdown files.
[21:08] SPEAKER: Now, if you want to move, so for example,
[21:11] SPEAKER: when Studio was shutting down that I helped out,
[21:14] SPEAKER: I helped them export their entire Notion database
[21:17] SPEAKER: from their paid plan that was all group-weared
[21:20] SPEAKER: into one owner free account
[21:24] SPEAKER: so that it was still accessible to them,
[21:25] SPEAKER: but they lost some of the paid features,
[21:27] SPEAKER: like the ability to turn whole chunks
[21:29] SPEAKER: of your Notion database into a Wiki and stuff like that.
[21:33] SPEAKER: - Does it, well, I assume it does export cleanly
[21:36] SPEAKER: to things like markdown.
[21:36] SPEAKER: I mean, it sounds like there's way more formatting
[21:39] SPEAKER: and relational metadata stuff in there
[21:42] SPEAKER: than something like markdown could display or embody.
[21:46] SPEAKER: Like, I assume it just kind of strips out extraneous stuff
[21:49] SPEAKER: and just gives you the flat text files.
[21:52] SPEAKER: - Yeah, so that's exactly what it does.
[21:54] SPEAKER: It doesn't handle the kind of linking around
[21:57] SPEAKER: and the deep trees that you can,
[21:59] SPEAKER: like you can make an infinitely deep Wiki
[22:03] SPEAKER: with links to links to links to links to links in Notion.
[22:07] SPEAKER: Joplin doesn't, like the Joplin and I would say the one,
[22:12] SPEAKER: Obsidian don't really have those kind of concepts
[22:15] SPEAKER: as a software, so it will produce something
[22:18] SPEAKER: that you can then import.
[22:19] SPEAKER: It'll be messy and you'll have to kind of reorganize it
[22:22] SPEAKER: when you get it in the new place.
[22:23] SPEAKER: But it is, it does provide good tools in, good tools out.
[22:27] SPEAKER: Now, the apps and databases that you build in Notion
[22:30] SPEAKER: probably won't come out in a meaningful way, obviously,
[22:33] SPEAKER: but it does give you the raw,
[22:34] SPEAKER: it does give you the raw forms and the tables
[22:36] SPEAKER: and all that stuff, so like the information is there
[22:39] SPEAKER: if you wanna then go vibe code your own Notion app analog.
[22:45] SPEAKER: Ugh, yeah, seems, that seems exhausting.
[22:48] SPEAKER: - Yes, it sure does.
[22:49] SPEAKER: Yeah, I think we've talked about that sometime
[22:52] SPEAKER: in the last few months, like that idea
[22:53] SPEAKER: when LLN started getting big and started proving
[22:56] SPEAKER: to be like decent at generating code or building apps
[22:59] SPEAKER: for people on demand or kind of a la carte,
[23:02] SPEAKER: that idea that like, oh, software as,
[23:06] SPEAKER: software development as a profession,
[23:07] SPEAKER: especially on the low end is dead
[23:09] SPEAKER: because everybody's just gonna make their own apps now,
[23:10] SPEAKER: but like how many end users want to do that?
[23:14] SPEAKER: How many end users actually wanna go through
[23:15] SPEAKER: the upfront cost of specking out even verbally
[23:19] SPEAKER: to a chatbot the app they want and then also staying on top
[23:22] SPEAKER: of making sure it keeps working the way they need it to
[23:25] SPEAKER: as like underlying OS has changed, you know,
[23:27] SPEAKER: like things are always gonna break over time,
[23:29] SPEAKER: like most people just want to do their work.
[23:32] SPEAKER: They don't want to do more work to be able to do their work.
[23:34] SPEAKER: You know, it's like, I think paying five or 10 bucks a month
[23:36] SPEAKER: for a lot of people is gonna continue to be more appealing
[23:39] SPEAKER: than paying an LLN fee and then making
[23:42] SPEAKER: their own to-do app, right?
[23:44] SPEAKER: - I think that's correct, but with an asterisk.
[23:46] SPEAKER: The thing, a VC that I follow that's actually kind of smart
[23:49] SPEAKER: and does a lot of hardware stuff posted an article
[23:51] SPEAKER: and I'll see if I can dig it up and maybe we'll put
[23:53] SPEAKER: in the show notes a week or two ago where they said,
[23:56] SPEAKER: look, if your business has like business intelligence stuff
[24:01] SPEAKER: that is crucial to the way your whole system operates
[24:06] SPEAKER: and you're running that out of spreadsheets,
[24:08] SPEAKER: 'cause like, I don't know if you're like,
[24:10] SPEAKER: do you know why Microsoft made Access?
[24:13] SPEAKER: - Like original Access?
[24:14] SPEAKER: - The original Access software, yeah.
[24:16] SPEAKER: - It was like in the '80s or '90s?
[24:18] SPEAKER: - '90s, but yeah.
[24:20] SPEAKER: They made that because they kept seeing businesses
[24:23] SPEAKER: building things that should have been databases
[24:24] SPEAKER: and spreadsheets.
[24:25] SPEAKER: - Oh yeah, yeah, absolutely.
[24:27] SPEAKER: - And that happens a lot.
[24:28] SPEAKER: Like a lot of times somebody will be like,
[24:30] SPEAKER: oh, okay, I know when the tool you know how to use best
[24:33] SPEAKER: is Excel, everything looks like it should be a spreadsheet.
[24:35] SPEAKER: So you'll have like your content calendar
[24:38] SPEAKER: and your like all of the work that you're doing
[24:41] SPEAKER: on scheduling or go to market or whatever
[24:44] SPEAKER: in a whole buttload of spreadsheets
[24:45] SPEAKER: that are unwieldy and difficult to use.
[24:48] SPEAKER: And his argument was, if you have business crucial,
[24:52] SPEAKER: this is a surprisingly businessy podcast all of a sudden,
[24:54] SPEAKER: but if you have stuff that's important
[24:56] SPEAKER: to the way your business operates
[24:57] SPEAKER: and you're running it out of spreadsheets
[24:58] SPEAKER: and it shouldn't be a spreadsheet,
[25:00] SPEAKER: that's a perfect vibe coding opportunity.
[25:01] SPEAKER: Let the person who made that really complicated
[25:04] SPEAKER: nightmare spreadsheet go in and give them some cloud tokens
[25:07] SPEAKER: and tell them to build an app for it.
[25:09] SPEAKER: And that like, that is exactly the use case for this stuff.
[25:11] SPEAKER: - That's a different, to be clear,
[25:13] SPEAKER: I was talking about the individual end user,
[25:15] SPEAKER: like the consumer level end user, you know,
[25:18] SPEAKER: just the average person who lives a life
[25:20] SPEAKER: and just needs to like keep a list of a to-do list organized
[25:23] SPEAKER: like that's where a lot of the argument
[25:25] SPEAKER: from the LLM advocates was coming from.
[25:28] SPEAKER: It's like, everybody's just gonna make their own apps now.
[25:30] SPEAKER: And I'm like, I think like your average,
[25:34] SPEAKER: your average like working mother, for example,
[25:36] SPEAKER: is not interested in maintaining a to-do list app
[25:38] SPEAKER: on her own, she's just gonna pay the five bucks a month
[25:40] SPEAKER: for whatever the, I don't know what app is appropriate here,
[25:44] SPEAKER: but you know what I mean?
[25:45] SPEAKER: Like people that just have busy lives
[25:47] SPEAKER: and have other concerns are probably gonna be fine
[25:50] SPEAKER: continuing to support like thoughtfully developed software.
[25:54] SPEAKER: - Have you read Harry McCracken?
[25:56] SPEAKER: Harry McCracken, who was the former editor-in-chief
[25:59] SPEAKER: of I think Macworld, I can't remember.
[26:04] SPEAKER: Anyway, Harry's a long time fixture in tech journalism
[26:07] SPEAKER: and is one of the good ones.
[26:09] SPEAKER: - Yeah, I've heard the name.
[26:11] SPEAKER: - He has been writing a series on Fast Company
[26:14] SPEAKER: about vibe coding his own word processing app.
[26:16] SPEAKER: - Oh yes, I saw at least one of these pieces going around.
[26:20] SPEAKER: - And it's worth reading just because like he's,
[26:26] SPEAKER: he's basically built a thing that makes him very happy
[26:28] SPEAKER: and does exactly what all of his other software does
[26:31] SPEAKER: with like two asterisks for the things
[26:33] SPEAKER: that he uses on the day-to-day.
[26:36] SPEAKER: - It's worth digging into it and reading.
[26:40] SPEAKER: - What I learned by vibe coding my own word processor
[26:43] SPEAKER: is the name of at least the first piece on this.
[26:48] SPEAKER: - I feel like maybe he wrote about it
[26:49] SPEAKER: on Jason Snell's blog, Six Colors as well,
[26:52] SPEAKER: but I'm not 100% on that, but anyway.
[26:55] SPEAKER: - Anyway, yeah.
[26:56] SPEAKER: - Yeah, so the vibe coding stuff like probably doesn't apply.
[26:58] SPEAKER: I don't think the AI stuff has really turned on
[27:00] SPEAKER: for free accounts except for maybe the meeting transcription.
[27:02] SPEAKER: - Yeah, for specific businesses that have bespoke needs,
[27:06] SPEAKER: it makes a lot more sense, obviously,
[27:08] SPEAKER: especially where you're paying somebody
[27:09] SPEAKER: to dedicate their time to making the thing
[27:11] SPEAKER: your company needs.
[27:12] SPEAKER: That's obviously a totally different
[27:13] SPEAKER: and potentially more valid use case.
[27:17] SPEAKER: - The other thing about Notion is that it does those things
[27:20] SPEAKER: like Jira and Trello and all the Gantt charts
[27:22] SPEAKER: and waterfall charts and all the producers kind of stuff
[27:25] SPEAKER: well up to a certain scale.
[27:27] SPEAKER: Like once you get above a certain team size,
[27:29] SPEAKER: you probably want a more dedicated piece of software for that
[27:31] SPEAKER: so it's why it's popular in the kind of studios I work with,
[27:34] SPEAKER: the smaller, like under 30 people,
[27:38] SPEAKER: like startups, not necessarily,
[27:41] SPEAKER: like I can't imagine that EA is gonna replace Jira
[27:44] SPEAKER: with a Notion database for their kind of bug tracking
[27:48] SPEAKER: and stuff like that.
[27:49] SPEAKER: - Yeah, that makes sense.
[27:50] SPEAKER: I guess we should talk about my path through this stuff.
[27:52] SPEAKER: - Yeah, let's talk about what you've been,
[27:54] SPEAKER: 'cause you've gone on a kind of a journey discovery here,
[27:56] SPEAKER: it seems like. - A little bit, yeah.
[27:57] SPEAKER: I ended up at a place.
[27:59] SPEAKER: I'll roll back a little bit.
[28:00] SPEAKER: I also used simple, or I'll talk about my needs here
[28:03] SPEAKER: and what prompted all this.
[28:05] SPEAKER: I also use simple note, like I said,
[28:08] SPEAKER: around the time you were using it.
[28:10] SPEAKER: Now that you mentioned it,
[28:11] SPEAKER: yes, I have seen a ton of sync conflicts with simple note,
[28:13] SPEAKER: but I always blamed that on the client I was using
[28:16] SPEAKER: and I don't know if that's fair,
[28:17] SPEAKER: but I never used the official simple note client
[28:20] SPEAKER: and I don't know if that even existed
[28:21] SPEAKER: back when you were using it.
[28:22] SPEAKER: - It did, yeah. - It did, okay.
[28:24] SPEAKER: - I think that the sync conflicts came up
[28:26] SPEAKER: as a result of a big bug that they had
[28:28] SPEAKER: that was interfering when I had my problem with Dropbox.
[28:33] SPEAKER: With Dropbox sync specifically,
[28:35] SPEAKER: the way it does those kind of partial file changes.
[28:38] SPEAKER: And I think that that's what caused my data loss,
[28:40] SPEAKER: if I recall, but it's been a long time.
[28:42] SPEAKER: And then they made some changes
[28:43] SPEAKER: to the way the syncing protocol works as a result of that.
[28:47] SPEAKER: - Okay, okay, I don't think I ever lost,
[28:48] SPEAKER: yeah, I don't think I ever lost data,
[28:50] SPEAKER: but I would definitely end up with duplicate notes
[28:51] SPEAKER: that have like weird suffixes tacked onto the name
[28:54] SPEAKER: and had to try to figure out like,
[28:56] SPEAKER: okay, which one's the real one, the new one here?
[28:58] SPEAKER: - Well, let's look at timestamps.
[29:01] SPEAKER: - No, but the other thing, like I said, though,
[29:02] SPEAKER: is like outside of notational velocity,
[29:04] SPEAKER: I just never liked any of the third-party clients
[29:06] SPEAKER: that existed for Simple Mode.
[29:07] SPEAKER: I mean, at least they allowed third-party clients
[29:09] SPEAKER: and that's cool, but like the Windows ones in particular
[29:11] SPEAKER: were always just like janky afterthoughts
[29:14] SPEAKER: that somebody like started working on five years ago
[29:17] SPEAKER: and has not updated since then, you know?
[29:19] SPEAKER: And it's just like, oh, this kind of still works,
[29:21] SPEAKER: but it's sort of a mess.
[29:22] SPEAKER: - Bad software you download from the Microsoft store.
[29:25] SPEAKER: - The other thing about Simple Mode
[29:27] SPEAKER: is it never stopped working for me,
[29:30] SPEAKER: but I always, especially these days,
[29:32] SPEAKER: I was always just a little surprised
[29:34] SPEAKER: that it was still around every time I would go to use it.
[29:37] SPEAKER: It's just like, wow, I can't believe
[29:38] SPEAKER: this hasn't gotten sold off and then shitified or shut down
[29:41] SPEAKER: or like my, you know, my Skyrim Dawnguard review
[29:45] SPEAKER: is still there from 2012 or whatever year I wrote that,
[29:49] SPEAKER: you know what I mean?
[29:49] SPEAKER: Like, I was just like, this whole endeavor feels
[29:52] SPEAKER: a bit ancient in a way that like,
[29:53] SPEAKER: I don't want to leave valuable data in this anymore.
[29:58] SPEAKER: I kind of want to be able to control it myself
[30:00] SPEAKER: and that's what really prompted this.
[30:01] SPEAKER: Like this really started as an effort to replace Simple Mode
[30:05] SPEAKER: and also to get more organized 'cause I am just not,
[30:08] SPEAKER: I have, especially the last few months
[30:11] SPEAKER: have not been very organized to have a lot of stuff
[30:13] SPEAKER: that has backed up that I need to get done
[30:14] SPEAKER: just on like the personal, you know,
[30:18] SPEAKER: personal maintenance end of like, oh,
[30:19] SPEAKER: there's tax stuff I haven't done and blah, blah, blah.
[30:21] SPEAKER: Like I just need, I need everything in front of me
[30:23] SPEAKER: that needs to be done so I can keep track of it better
[30:26] SPEAKER: so that was the extent of my needs
[30:28] SPEAKER: when I set out to do this.
[30:30] SPEAKER: - I think that they had a service too that they paid for
[30:33] SPEAKER: 'cause I'm looking at this, I find all of my,
[30:37] SPEAKER: I find all of my notes from like 2012 here it looks like.
[30:41] SPEAKER: - On Simple Note?
[30:42] SPEAKER: - On Simple Note still.
[30:43] SPEAKER: - Still got 'em.
[30:44] SPEAKER: To their credit, I will give them credit,
[30:45] SPEAKER: there's a very easy one-click export option.
[30:47] SPEAKER: If you log into your, log into the web interface,
[30:50] SPEAKER: you can click one button and have it give you a zip file
[30:53] SPEAKER: with every single note you have in it
[30:54] SPEAKER: as an individual text file.
[30:56] SPEAKER: - Yeah, here's a link to the Whiskey Media Platform 2.0 docs
[31:00] SPEAKER: from the post Whale Rock purchase I think.
[31:02] SPEAKER: - Wow, man, hot 14-year-old trade secrets on this podcast.
[31:06] SPEAKER: - We got products I love,
[31:08] SPEAKER: the Sennheiser HD 580 headphones, still love those.
[31:12] SPEAKER: - Solid.
[31:12] SPEAKER: - Yeah, a bunch of articles I wrote.
[31:14] SPEAKER: - Those are eternal headphones.
[31:16] SPEAKER: - Yeah, seriously fuck comments, that's just, that's all.
[31:18] SPEAKER: That's the entire note.
[31:20] SPEAKER: Yeah, okay.
[31:22] SPEAKER: Anyway, did Simple Note ever support markdown
[31:27] SPEAKER: or formatting options or did it?
[31:29] SPEAKER: 'Cause I only ever used it as plain text.
[31:32] SPEAKER: - Oh yeah, you could do markdown
[31:34] SPEAKER: from the beginning I think.
[31:35] SPEAKER: - Interesting, maybe the clients I used didn't support that
[31:38] SPEAKER: or I don't know.
[31:39] SPEAKER: - You might've had to flip it on.
[31:40] SPEAKER: - Yeah, that's possible.
[31:41] SPEAKER: Anyway, whatever, I have delineated
[31:43] SPEAKER: why I was trying to get off of Simple Note.
[31:46] SPEAKER: But just to further drive the point home,
[31:47] SPEAKER: all I needed was like a store of notes
[31:52] SPEAKER: that could do like basic formatting,
[31:54] SPEAKER: like markdown style format and a to-do list.
[31:56] SPEAKER: Like I needed something that it was like,
[31:57] SPEAKER: I ideally could like check boxes as I finished things,
[32:01] SPEAKER: you know, and like at least visually represent
[32:03] SPEAKER: when tasks were getting done.
[32:05] SPEAKER: - That makes sense.
[32:06] SPEAKER: - All that is to say, I didn't need anything relational
[32:08] SPEAKER: or hierarchical or any of the stuff that Notion does,
[32:10] SPEAKER: which is probably the biggest reason I didn't look at Notion
[32:12] SPEAKER: for people who love Notion and are wondering why.
[32:15] SPEAKER: - Yeah, but like the other problem with Notion
[32:18] SPEAKER: is it is proprietary backend stuff
[32:21] SPEAKER: and it lives on a service that somebody else is hosting.
[32:23] SPEAKER: - Yeah, so that's what I was trying to get away from.
[32:25] SPEAKER: - Yeah, like I understand not wanting to be part of that.
[32:27] SPEAKER: I don't really have a choice,
[32:29] SPEAKER: so I've leaned in on that front.
[32:31] SPEAKER: - And then, you know, I also wanted a place
[32:32] SPEAKER: I can store or safely store like product keys,
[32:34] SPEAKER: you know, like Windows product keys
[32:36] SPEAKER: or like other things that I just need to keep for years
[32:38] SPEAKER: and be able to refer back to, you know,
[32:40] SPEAKER: and also ephemeral stuff like a doctor's appointment details
[32:45] SPEAKER: and just little stuff to jot down.
[32:47] SPEAKER: I just wanted all that to live in one place.
[32:48] SPEAKER: I didn't want to, I certainly didn't want it to be
[32:50] SPEAKER: like Google docs or anything like that at this point.
[32:52] SPEAKER: - It's really nice to take all of your notes in one place
[32:55] SPEAKER: and have a place that's searchable.
[32:56] SPEAKER: - Yes, yes.
[32:57] SPEAKER: - 'Cause it turns out those two things together
[33:00] SPEAKER: power up your note taking ability
[33:01] SPEAKER: and your ability to work on stuff.
[33:03] SPEAKER: - Like I've also just got like text files
[33:04] SPEAKER: laying all over the place, like just individual,
[33:06] SPEAKER: like a lot of it, like my habit was to just open Notepad
[33:09] SPEAKER: if I was like on the phone with the doctor
[33:10] SPEAKER: and like, you know, and then I'm saving a random text file
[33:13] SPEAKER: with the where and when of my next doctor's appointment.
[33:17] SPEAKER: And it's like, is that on my Windows desktop?
[33:18] SPEAKER: Did I save it on my NAS somewhere?
[33:20] SPEAKER: Like this is not a good system.
[33:22] SPEAKER: - No, the answer when you get the,
[33:24] SPEAKER: when you schedule the next appointment
[33:25] SPEAKER: is just to make the appointment in your calendar,
[33:27] SPEAKER: right that moment.
[33:27] SPEAKER: - Yeah.
[33:28] SPEAKER: - Literally stand there and open it up
[33:30] SPEAKER: and do it while you're at the doctor's office.
[33:32] SPEAKER: - What if you have a calendar
[33:33] SPEAKER: and just didn't use it for stuff like that?
[33:37] SPEAKER: I don't know, it's a little too formal.
[33:40] SPEAKER: - I can't out the person who told me this the other day,
[33:44] SPEAKER: but I was talking to someone and they told me that they're,
[33:46] SPEAKER: I was like, hey, what's your calendar look like
[33:48] SPEAKER: for that day?
[33:49] SPEAKER: And they opened up their alarms app
[33:53] SPEAKER: to see when they have alarms set for Tuesdays and Thursdays.
[33:56] SPEAKER: - Wow.
[33:57] SPEAKER: - And I was like, oh, this is not a tenable way
[34:00] SPEAKER: to handle this.
[34:01] SPEAKER: Why would you do this to yourself?
[34:02] SPEAKER: - I have had some bad experiences with,
[34:05] SPEAKER: I don't know which platform you're talking about,
[34:07] SPEAKER: but alarms on iOS and on the watch especially,
[34:10] SPEAKER: not doing what they're supposed to be doing seemingly.
[34:15] SPEAKER: Anyway, okay, so like I just needed like basic markdown
[34:18] SPEAKER: and a to-do list and like something
[34:19] SPEAKER: that ideally I could control the data myself.
[34:21] SPEAKER: So didn't really look at Notion for reasons mentioned.
[34:24] SPEAKER: I, the other thing is I kind of wanted it to use
[34:27] SPEAKER: like cloud storage I already use, you know?
[34:31] SPEAKER: - Yeah.
[34:32] SPEAKER: - Like and have access to and control to the extent possible
[34:36] SPEAKER: and not pile up another subscription
[34:39] SPEAKER: or another like monthly fee, if possible.
[34:41] SPEAKER: - Yeah, if you're paying for Dropbox or OneDrive
[34:43] SPEAKER: or Google Drive or whatever, it's nice.
[34:45] SPEAKER: It feels like you should be able to use that storage
[34:47] SPEAKER: for all the things.
[34:48] SPEAKER: The promise of Dropbox originally was,
[34:51] SPEAKER: hey, you can buy some storage from us
[34:53] SPEAKER: just like you would a server
[34:54] SPEAKER: and then you can use it with all your stuff.
[34:55] SPEAKER: And that worked for a long time.
[34:56] SPEAKER: - Yes, yes.
[34:57] SPEAKER: So I briefly looked at Obsidian.
[34:59] SPEAKER: I had installed the Obsidian iOS app.
[35:00] SPEAKER: Like a lot of people like Obsidian and like--
[35:02] SPEAKER: - Obsidian's really good.
[35:03] SPEAKER: - Yeah. - Yeah.
[35:04] SPEAKER: - It seemed good.
[35:05] SPEAKER: The thing that kind of made me just not really
[35:06] SPEAKER: give it much of a shot is the sync options on iOS
[35:09] SPEAKER: seem extremely limited from what I could tell.
[35:12] SPEAKER: I haven't looked at it in a little while.
[35:13] SPEAKER: I hope this has not changed since the last time I did this.
[35:15] SPEAKER: But, and I think some of these restrictions
[35:17] SPEAKER: are maybe imposed by iOS, not by Obsidian.
[35:22] SPEAKER: - That I don't know about.
[35:23] SPEAKER: - You can pay the Obsidian fee and sync to their cloud fine
[35:27] SPEAKER: if you want to do that.
[35:27] SPEAKER: But like I said, I was trying not to like get involved
[35:30] SPEAKER: in another proprietary cloud storage option.
[35:33] SPEAKER: - Yeah.
[35:34] SPEAKER: - Other than that though, you can only sync to iCloud
[35:37] SPEAKER: by default on iOS with Obsidian.
[35:40] SPEAKER: - I think that's why that's their way
[35:42] SPEAKER: to get you to pay their $4 a month.
[35:44] SPEAKER: - Yeah, so, and I need this to be cross-platform
[35:47] SPEAKER: 'cause I'm gonna need it on Windows all day long
[35:49] SPEAKER: and like theoretically on Linux at some point as well.
[35:52] SPEAKER: And I just did not want to deal with--
[35:54] SPEAKER: - Obsidian is cross-platform for its worth.
[35:55] SPEAKER: - Yeah, it is.
[35:56] SPEAKER: Yeah, no, no, no.
[35:57] SPEAKER: I mean the cloud storage needed to be accessible on.
[36:00] SPEAKER: And so there, I guess there are probably ways
[36:03] SPEAKER: to get iCloud working persistently on Windows
[36:05] SPEAKER: but I didn't want to deal with that.
[36:07] SPEAKER: Like you could use our clone.
[36:08] SPEAKER: I looked into this, you could use our clone
[36:10] SPEAKER: to mount your iCloud storage the same way.
[36:12] SPEAKER: I already do that and then we'll get to this
[36:14] SPEAKER: 'cause that ended up coming in very handy here.
[36:16] SPEAKER: I already do that for Dropbox, OneDrive and Google Drive.
[36:20] SPEAKER: The iCloud integration with our clone,
[36:23] SPEAKER: if best I could tell, like we'll basically lose
[36:25] SPEAKER: your authentication every 30 days.
[36:27] SPEAKER: And so you have to keep going in
[36:28] SPEAKER: and reauthorizing its access with iCloud every month.
[36:32] SPEAKER: - That's the problem with all non-Apple iCloud syncs
[36:36] SPEAKER: in my experience, including stuff like Apple Music.
[36:38] SPEAKER: Like I have to log into Apple Music every 30 days on Linux.
[36:41] SPEAKER: - Yes, and I just did not want to deal with that either.
[36:45] SPEAKER: And so I kind of just, I was like Obsidian seems
[36:47] SPEAKER: pretty robust but I just didn't want to deal with that stuff.
[36:51] SPEAKER: - If you're paying the four bucks a month to Obsidian,
[36:53] SPEAKER: I think it's quite good.
[36:54] SPEAKER: I think if you're not paying the four bucks a month
[36:56] SPEAKER: to Obsidian, I'm less impressed.
[36:58] SPEAKER: - Yeah, and to further illustrate why I didn't want
[37:01] SPEAKER: to just be in another proprietary cloud sync,
[37:03] SPEAKER: I want these files locally.
[37:04] SPEAKER: I want like, if the company is hit by a meteor tomorrow
[37:08] SPEAKER: and ceases to exist and all of their data centers are gone,
[37:12] SPEAKER: I mean, this is pretty catastrophic.
[37:14] SPEAKER: Like it's not likely to play out that way, but I just wanted--
[37:17] SPEAKER: - Would you say that, but Amazon lost some data centers
[37:20] SPEAKER: recently due to reasons.
[37:21] SPEAKER: - Sure, yes, right, and that did happen.
[37:23] SPEAKER: Look, the world is a bit chaotic right now.
[37:27] SPEAKER: I would hope that Amazon has some like
[37:29] SPEAKER: geographical redundancy, but--
[37:31] SPEAKER: - Here's the interesting thing about that,
[37:32] SPEAKER: is they say, hey, you shouldn't keep your data
[37:34] SPEAKER: in one data center.
[37:36] SPEAKER: Their policy is we have multiple data centers
[37:38] SPEAKER: so you can clone your data across multiples
[37:41] SPEAKER: and pay us more for that.
[37:42] SPEAKER: - I was gonna say, I bet they would love to charge you more
[37:44] SPEAKER: for spreading your data around anyway.
[37:46] SPEAKER: - I mean, I don't know if you remember,
[37:48] SPEAKER: but when we did the Whiskey Media panel of experts
[37:50] SPEAKER: because the data center in Northern Virginia,
[37:53] SPEAKER: their data center in Northern Virginia was out,
[37:58] SPEAKER: that was their official solution to that was,
[38:00] SPEAKER: you shouldn't keep your data in one data center.
[38:03] SPEAKER: - GitHub was profoundly down for like most of Monday
[38:06] SPEAKER: this week, which hit me as I tried to click on a Wiki
[38:09] SPEAKER: hosted on GitHub to try to fix something I was messing with
[38:11] SPEAKER: and like, I guess I'm not doing that right now.
[38:14] SPEAKER: - Nope.
[38:15] SPEAKER: - Anyway, so yeah, like I wanted the files locally
[38:17] SPEAKER: so that if I ever decide to pivot to something else,
[38:20] SPEAKER: I can just take my data and move it to another thing.
[38:23] SPEAKER: - Just out of curiosity, did you, did any of these,
[38:27] SPEAKER: when I went through this whole process and settled on Notion,
[38:29] SPEAKER: the one hole that Notion had that bummed me out
[38:32] SPEAKER: is there's no ability to do like handwritten sketches
[38:34] SPEAKER: on an iPad with a pencil or anything like that?
[38:36] SPEAKER: - Oh, I hadn't, I didn't even look into that stuff.
[38:38] SPEAKER: I don't have a pencil for my iPad
[38:40] SPEAKER: and don't do stuff that way, so.
[38:43] SPEAKER: - So Obsidian didn't do that.
[38:47] SPEAKER: OneNote and Google Keep both do,
[38:48] SPEAKER: which we'll talk about in a little bit.
[38:49] SPEAKER: Notion does not.
[38:50] SPEAKER: And then most of the best options
[38:53] SPEAKER: for that kind of note taking on iOS
[38:54] SPEAKER: seem to be extremely limited to just Mac platforms.
[38:58] SPEAKER: So we're not gonna talk about those today
[39:00] SPEAKER: for folks just who are asking, I guess.
[39:02] SPEAKER: - Real quick, the other one I looked at
[39:04] SPEAKER: before I had got to something I landed on is Logsec.
[39:07] SPEAKER: - I don't know what that is.
[39:08] SPEAKER: I've never heard of that one.
[39:09] SPEAKER: - L-O-G-S-E-Q.
[39:11] SPEAKER: - Okay.
[39:12] SPEAKER: - So there were a couple of open source options, of course,
[39:14] SPEAKER: given my goals, that's what I was gonna lean toward.
[39:16] SPEAKER: - Yeah.
[39:17] SPEAKER: - There are a couple of those that we'll talk about
[39:18] SPEAKER: and Logsec is one of them.
[39:20] SPEAKER: I basically pulled back on that one
[39:23] SPEAKER: as soon as I got to the, how do I sync this
[39:25] SPEAKER: to cloud services part and saw that that stuff
[39:27] SPEAKER: is seemingly quite early with that thing.
[39:31] SPEAKER: And also maybe limited to people
[39:34] SPEAKER: who support the project right now.
[39:36] SPEAKER: Or like you need some kind of like authorization
[39:38] SPEAKER: like by being a donor to even access the sync stuff.
[39:42] SPEAKER: It wasn't clear.
[39:43] SPEAKER: - So you can't leave your stuff in like a Dropbox folder
[39:48] SPEAKER: and it just syncs so you can't put your store
[39:49] SPEAKER: in the Dropbox folder?
[39:50] SPEAKER: - I think ultimately you can do that.
[39:52] SPEAKER: But there was some kind of verification process
[39:54] SPEAKER: you had to go through to be able to access those features,
[39:56] SPEAKER: the sync features because they're early, they're not.
[39:58] SPEAKER: And the other thing is I will cop to not having
[40:03] SPEAKER: like very thoroughly researched the stuff
[40:05] SPEAKER: because I basically was just dabbling
[40:07] SPEAKER: with these different apps until I found one
[40:08] SPEAKER: that did everything I needed.
[40:09] SPEAKER: But I also saw some aspects of Logsec's syncing stuff
[40:14] SPEAKER: had been deprecated or like features had been rolled out
[40:17] SPEAKER: and then gone unsupported, I believe.
[40:20] SPEAKER: Anyway, there were just enough kind of red flags
[40:21] SPEAKER: there on like being able to do the cloud stuff
[40:23] SPEAKER: that I was like, ah, I'll keep poking around.
[40:26] SPEAKER: - It looks like they're on the Obsidian track too
[40:29] SPEAKER: of hey, if you want, we're gonna provide a service.
[40:32] SPEAKER: Like, look, I support them having a service.
[40:35] SPEAKER: I support Obsidian having a service
[40:37] SPEAKER: that they pay for easy syncing.
[40:38] SPEAKER: SimpleNote does the same thing, honestly.
[40:40] SPEAKER: - Yeah.
[40:42] SPEAKER: - 'Cause if that makes their business works and yeah.
[40:45] SPEAKER: Anyway, but not part of your requirements.
[40:47] SPEAKER: - But like, again, the thing for me is like
[40:49] SPEAKER: I already have a million logins for everything
[40:51] SPEAKER: and I already have Dropbox and OneDrive and Google Drive
[40:54] SPEAKER: and a NAS and a VPS, you know, like I've got a lot of stuff
[40:58] SPEAKER: already that I'm keeping up with and like adding another,
[41:01] SPEAKER: yet another service I need to like authorize and log into
[41:04] SPEAKER: is just, it's just too much from the end user perspective.
[41:08] SPEAKER: Real quick before we got to Joplin is the one
[41:10] SPEAKER: that I'm actually using, which we'll talk about,
[41:12] SPEAKER: but you very briefly, you wrote OneNote and Google Keep
[41:15] SPEAKER: in here in between, which you might wanna touch on.
[41:18] SPEAKER: - Yeah, so I think both of these are,
[41:22] SPEAKER: when we talk about, when we've talked about this
[41:23] SPEAKER: in the past, that's the thing that always people always say,
[41:25] SPEAKER: "Hey, I love Google Keep," or "I love OneNote,"
[41:28] SPEAKER: and that's great.
[41:29] SPEAKER: Both of those are fine.
[41:30] SPEAKER: I've had data loss problems on OneNote
[41:33] SPEAKER: that were mostly related to OneDrive syncing problems
[41:35] SPEAKER: because they're really opaque about where they store
[41:37] SPEAKER: your file and where they store your stuff.
[41:40] SPEAKER: The monolithic, the way OneNote saves,
[41:44] SPEAKER: OneNote does let you save a local file, which I do like,
[41:47] SPEAKER: but the way they save it in their obscure OneNote format
[41:50] SPEAKER: and it's like a monolithic giant file
[41:52] SPEAKER: with all of your stuff in it seems incredibly high risk
[41:55] SPEAKER: to me in the era that we live in, so that's out for me.
[41:59] SPEAKER: Also, there's obviously no Linux client for OneDrive.
[42:02] SPEAKER: I think you can use it on the web now,
[42:03] SPEAKER: but if you have it in your One, sorry, for OneNote,
[42:07] SPEAKER: I think you can use it on the web
[42:08] SPEAKER: if you have your OneNote file in a OneDrive folder.
[42:12] SPEAKER: - Yeah, which, like I mentioned, OneDrive does mount
[42:14] SPEAKER: just fine with our clone, so you can do that.
[42:16] SPEAKER: - Yeah, yeah, yeah.
[42:18] SPEAKER: The Google Keep, I'm not interested
[42:21] SPEAKER: because of Google, frankly.
[42:22] SPEAKER: I used Keep for a while when I was on Android phones.
[42:24] SPEAKER: It was really good.
[42:26] SPEAKER: It is one of the few things that does,
[42:28] SPEAKER: that lets you do sketches with text
[42:31] SPEAKER: in a fairly transparent way, but yeah, I'm not, no thanks.
[42:37] SPEAKER: And it's web-based, which I don't love.
[42:38] SPEAKER: - Oh, yeah, no, that's not great.
[42:40] SPEAKER: I am with you.
[42:41] SPEAKER: I mean, I don't know if I've mentioned this here,
[42:42] SPEAKER: but I think I maybe have elsewhere.
[42:44] SPEAKER: Like, I've been thinking for a while
[42:45] SPEAKER: about even getting off of Google
[42:47] SPEAKER: for our basic workspace suites,
[42:50] SPEAKER: like mail and calendar and stuff,
[42:52] SPEAKER: and moving to fast mail or something like that.
[42:54] SPEAKER: - We should do an episode about that,
[42:55] SPEAKER: 'cause my consulting business doesn't have Google Mail,
[42:59] SPEAKER: but I do have to use Google accounts for everything else,
[43:01] SPEAKER: because sharing documents, everybody uses Google Drive
[43:04] SPEAKER: and Google Docs for everything.
[43:06] SPEAKER: So you basically, if you don't have an account,
[43:09] SPEAKER: then you're always eternally logging in as a guest,
[43:12] SPEAKER: which sucks.
[43:13] SPEAKER: You're always gonna need basic Google access
[43:15] SPEAKER: just to work with other people.
[43:17] SPEAKER: But I'm talking about for our work email,
[43:21] SPEAKER: and stuff like that.
[43:22] SPEAKER: - We absolutely don't need to pay for Gmail anymore.
[43:24] SPEAKER: - Yeah, and on the next later side as well,
[43:25] SPEAKER: I need to just start, I need to pop a fast mail trial
[43:29] SPEAKER: and just mess around with it and see how it-
[43:31] SPEAKER: - Let me tell you, I have a code, and you'll get 10% off.
[43:34] SPEAKER: - All right, good to know.
[43:36] SPEAKER: - So yeah, we're not gonna talk about either of those,
[43:38] SPEAKER: just 'cause both of us have spent a fair amount of effort
[43:41] SPEAKER: getting off of Google and moving more services onto Google
[43:44] SPEAKER: at this point is not gonna happen.
[43:45] SPEAKER: - Right, right.
[43:46] SPEAKER: Anyway, okay, Joplin is what I'm using now.
[43:48] SPEAKER: - Yeah, Joplin is I think the juice here,
[43:50] SPEAKER: 'cause I like Joplin a lot.
[43:51] SPEAKER: I used the Joplin for a fair amount of time last year.
[43:53] SPEAKER: - Oh, you did?
[43:54] SPEAKER: - Yeah.
[43:55] SPEAKER: - Oh, I didn't realize that, okay.
[43:56] SPEAKER: - I think it's still installed even.
[43:57] SPEAKER: - Okay, so what is it about Joplin that drew me to it?
[44:00] SPEAKER: I mean, again, it's another of the open source ones,
[44:02] SPEAKER: and it feels like the most purely open source,
[44:05] SPEAKER: like just like, hey, we're just doing this
[44:06] SPEAKER: and putting it out there.
[44:08] SPEAKER: The big one though is I Googled Joplin sync options
[44:12] SPEAKER: and got a page with like two paragraphs on it
[44:16] SPEAKER: that just very straightforwardly said,
[44:17] SPEAKER: here's how this works, it's extremely simple,
[44:19] SPEAKER: here's what the services we support, go nuts.
[44:23] SPEAKER: Synchronization is possible with Joplin Cloud,
[44:25] SPEAKER: Nextcloud, S3, WebDAV, Dropbox, OneDrive,
[44:29] SPEAKER: or the local file system is what they say.
[44:32] SPEAKER: And I was like, cool. - Yeah, that's wild.
[44:33] SPEAKER: - All right, I already use two of those,
[44:35] SPEAKER: or three if you count local file systems.
[44:37] SPEAKER: Also, it's not super material here,
[44:38] SPEAKER: but they mentioned that the cloud storage support
[44:44] SPEAKER: is in the form of like basically a lightweight driver,
[44:46] SPEAKER: like all of the storage backend is built into the thing
[44:49] SPEAKER: and to support new cloud storage options,
[44:53] SPEAKER: people just need to write like a very simple plugin.
[44:56] SPEAKER: - It's like a Lua plugin or something, isn't it?
[44:57] SPEAKER: - Well, I don't know what it's written in,
[44:59] SPEAKER: but they basically just say,
[45:00] SPEAKER: most of the sync process is done at an abstract level
[45:02] SPEAKER: and access to external services like Dropbox
[45:05] SPEAKER: is done via lightweight drivers,
[45:06] SPEAKER: it's easy to support new services
[45:08] SPEAKER: by creating simple drivers
[45:09] SPEAKER: that provide a file system-like interface.
[45:12] SPEAKER: In other words, the ability to read, write,
[45:14] SPEAKER: delete, and list items.
[45:16] SPEAKER: So I get, that's not relevant to us necessarily,
[45:18] SPEAKER: but the point is developers, open source developers
[45:21] SPEAKER: may come along and add other services
[45:23] SPEAKER: in a fairly lightweight way in the future.
[45:25] SPEAKER: That's just a neat detail to me,
[45:27] SPEAKER: whether it actually manifests or not.
[45:29] SPEAKER: - I mean, I think it has manifested though
[45:31] SPEAKER: in judging by all the weird stuff they support.
[45:34] SPEAKER: - Right, yeah, that does seem plausible.
[45:37] SPEAKER: Anyway, I installed it and set it up with Dropbox
[45:39] SPEAKER: and it took five minutes.
[45:40] SPEAKER: Like you authorize it as an app with Dropbox,
[45:43] SPEAKER: you know how most of these platforms
[45:45] SPEAKER: will let you add apps that can access your stuff,
[45:49] SPEAKER: which again, like I basically just had
[45:51] SPEAKER: to kind of log into Dropbox and go through that process.
[45:54] SPEAKER: That was also very easy and then it was syncing to Dropbox.
[45:57] SPEAKER: - Does it store stuff in your Dropbox
[45:58] SPEAKER: like that add apps folder?
[46:00] SPEAKER: - Yeah, I'd never done that before,
[46:02] SPEAKER: but yes, it is in the uppercase A apps folder.
[46:05] SPEAKER: - Yeah, it's funny, that's where like 1Password
[46:07] SPEAKER: and all this stuff used to live
[46:08] SPEAKER: and now hardly anybody uses that anymore, it seems like.
[46:12] SPEAKER: - Interesting.
[46:13] SPEAKER: - I mean, obviously 1Password uses
[46:13] SPEAKER: their own backend service now.
[46:16] SPEAKER: - Here, I'll just get to the biggest con of Joplin though,
[46:20] SPEAKER: because you mentioned this with, which one was it?
[46:24] SPEAKER: - OneNote.
[46:25] SPEAKER: - Yeah, so 1Note is the other offender here.
[46:27] SPEAKER: So Obsidian and LogSec do this the good way.
[46:30] SPEAKER: I don't know about Notion.
[46:30] SPEAKER: I'm guessing Notion is probably all kinds of...
[46:33] SPEAKER: - Notion's all in the cloud.
[46:34] SPEAKER: You don't have a local copy in general.
[46:36] SPEAKER: I mean, I'm sure there's a cache, but it's not like...
[46:37] SPEAKER: - Oh, wow, I didn't realize it was that.
[46:40] SPEAKER: - You flag stuff as what you want available offline.
[46:42] SPEAKER: So like when I'm getting ready to get on a plane
[46:44] SPEAKER: with my laptop, I'd tag the tree.
[46:46] SPEAKER: Like basically I choose the trees I use most recently
[46:49] SPEAKER: to be cached locally.
[46:50] SPEAKER: - Okay, so that is a thousand percent not appropriate
[46:53] SPEAKER: for what I was looking for then,
[46:54] SPEAKER: 'cause I'd want all the data locally.
[46:56] SPEAKER: So Obsidian and LogSec, a couple of their,
[46:58] SPEAKER: or one of their big selling points
[47:00] SPEAKER: is that you can just point them
[47:01] SPEAKER: at a raw directory full of markdown files
[47:04] SPEAKER: and they will just use that and not modify them.
[47:07] SPEAKER: Like you will just continue to have raw markdown files
[47:10] SPEAKER: available on your local device.
[47:12] SPEAKER: - You can actually have multiple clients
[47:13] SPEAKER: attached to that same folder
[47:15] SPEAKER: and all sorts of weird stuff happens, but it works.
[47:17] SPEAKER: - So I really wanted that,
[47:19] SPEAKER: but unfortunately Joplin does not do that.
[47:21] SPEAKER: It kind of abstracts all your notes into a sort of a database
[47:25] SPEAKER: like they are still plain text files,
[47:27] SPEAKER: but they're not readable by the user.
[47:29] SPEAKER: Like you can't just go open your note files
[47:31] SPEAKER: and mess with them.
[47:32] SPEAKER: - So there are,
[47:33] SPEAKER: having tried to do the notion to Joplin import last year,
[47:37] SPEAKER: there are a bunch of tools that work on that database file.
[47:40] SPEAKER: So like there are people who've written software
[47:43] SPEAKER: that lets you manipulate it in ways that make a lot of sense
[47:47] SPEAKER: if you have problems or whatever.
[47:47] SPEAKER: - Oh, you mean the Joplin database or the Joplin database?
[47:50] SPEAKER: Okay, that's good to know.
[47:51] SPEAKER: I mean, yeah, being such an open project,
[47:53] SPEAKER: that's not surprising at all,
[47:54] SPEAKER: but I don't think it's gonna be an issue.
[47:56] SPEAKER: It was not my favorite.
[47:58] SPEAKER: Like it was definitely a like grit my teeth.
[47:59] SPEAKER: Like I really wanted the data to just be like plain text
[48:02] SPEAKER: accessible to me,
[48:03] SPEAKER: even if everything else in the world burns down,
[48:06] SPEAKER: which it's not.
[48:07] SPEAKER: But for a couple of reasons,
[48:09] SPEAKER: I don't think it's gonna matter much.
[48:10] SPEAKER: I mean, it'll let you export everything as Markdown,
[48:12] SPEAKER: of course, locally without ever touching a server.
[48:15] SPEAKER: - Yeah.
[48:16] SPEAKER: - So as long as the installer for a Joplin client
[48:18] SPEAKER: is available somewhere on planet earth,
[48:21] SPEAKER: in the event of civilizational collapse,
[48:23] SPEAKER: I can still export all of my stuff as plain files.
[48:26] SPEAKER: - If we have civilizational collapse,
[48:29] SPEAKER: you're not gonna be using your text files probably.
[48:32] SPEAKER: - I think my stash of windows products keys
[48:34] SPEAKER: is maybe not gonna be my primary concern at that point.
[48:37] SPEAKER: - Well, I was just saying,
[48:38] SPEAKER: but also like it's straightforward
[48:41] SPEAKER: to get the stuff out of there, right?
[48:42] SPEAKER: Like that's the important thing.
[48:44] SPEAKER: - Right.
[48:45] SPEAKER: And so here, the other reason I think it doesn't really
[48:47] SPEAKER: matter what the on-disk format is for me,
[48:49] SPEAKER: is that the Joplin has an end to end encryption option,
[48:52] SPEAKER: which I also flipped on.
[48:54] SPEAKER: - Okay.
[48:55] SPEAKER: - Because I'm storing this in Dropbox
[48:56] SPEAKER: and theoretically my Dropbox could be compromised.
[48:59] SPEAKER: - Ah.
[48:59] SPEAKER: - And somebody could get in there and get the stuff.
[49:02] SPEAKER: In that instance, having plain text files of,
[49:06] SPEAKER: you know, presumably I'm gonna have years and years
[49:08] SPEAKER: worth of personal information in here at some point.
[49:11] SPEAKER: Like having all that plainly readable to anybody
[49:12] SPEAKER: who somehow got into my Dropbox account
[49:14] SPEAKER: was maybe not great anyway.
[49:16] SPEAKER: - The other big benefit of having it in the database
[49:18] SPEAKER: is that the search is basically free
[49:21] SPEAKER: in terms of time and cost and indexing.
[49:23] SPEAKER: - Sure.
[49:24] SPEAKER: - The indexing, when I imported 10 years of Notion Notes
[49:28] SPEAKER: into Obsidian, it took a really, really long time
[49:32] SPEAKER: to build the first index.
[49:33] SPEAKER: - Sure, I could see that.
[49:34] SPEAKER: - And then the search was kind of chonky even after that.
[49:36] SPEAKER: - Right.
[49:37] SPEAKER: So because I'm using the encryption option,
[49:39] SPEAKER: I wouldn't be able to read these files
[49:40] SPEAKER: outside of Joplin anyway.
[49:42] SPEAKER: So maybe not a huge deal since I'm storing it
[49:45] SPEAKER: in a commercial cloud service.
[49:48] SPEAKER: But the encryption was also very easy.
[49:49] SPEAKER: You just put in a passphrase and it encrypts everything
[49:51] SPEAKER: and that's kind of it.
[49:53] SPEAKER: One, two, three, four, five, six.
[49:54] SPEAKER: - Yes.
[49:55] SPEAKER: So currently I'm only using this in Windows and iOS,
[49:57] SPEAKER: but it's synced back and forth just fine
[50:00] SPEAKER: without any issues as far as I can tell.
[50:02] SPEAKER: - The Joplin clients for Linux are good too as I recall.
[50:04] SPEAKER: - I believe it.
[50:05] SPEAKER: I mean, they're Electron based.
[50:07] SPEAKER: Like I assume all of these are.
[50:08] SPEAKER: I mean, the client gobbles hundreds of megabytes of memory
[50:11] SPEAKER: like every other Electron app,
[50:13] SPEAKER: but I think you're just kind of putting up with that
[50:15] SPEAKER: in this world at this point, right?
[50:18] SPEAKER: - I mean, Electron is sadly a cost of doing business,
[50:21] SPEAKER: I think, in a lot of these spaces.
[50:22] SPEAKER: 'Cause like the Notion app is an Electron app.
[50:24] SPEAKER: I feel like the Obsidian app was native on Linux.
[50:28] SPEAKER: - That's possible.
[50:29] SPEAKER: Yeah, I guess I shouldn't paint with an overly broad brush,
[50:31] SPEAKER: but anyway, the Joplin client certainly in Windows
[50:35] SPEAKER: is fairly memory heavy, big footprint, et cetera, et cetera.
[50:40] SPEAKER: I haven't tried this,
[50:41] SPEAKER: but there is a terminal client for Joplin.
[50:43] SPEAKER: - Oh yeah.
[50:44] SPEAKER: - Which is, it's Node.js.
[50:46] SPEAKER: So you need to install a Node backend
[50:50] SPEAKER: or runtime and NPM and all that stuff
[50:53] SPEAKER: if you want to get into it.
[50:55] SPEAKER: It is said to have a vim-like command structure
[50:57] SPEAKER: and a hotkey syntax.
[50:59] SPEAKER: So I'm sure I'll try that as well.
[51:01] SPEAKER: I mean, there is some appeal to running that
[51:03] SPEAKER: and not having to run the big Windows client,
[51:04] SPEAKER: but also Windows client's fine.
[51:06] SPEAKER: I have plenty of RAM.
[51:09] SPEAKER: - I will tell you there have been times
[51:10] SPEAKER: where I've been sitting at a server on a terminal
[51:13] SPEAKER: wishing I had easy access to copy and paste stuff
[51:16] SPEAKER: from my Node's app.
[51:18] SPEAKER: I think keeping it generally GUI driven
[51:20] SPEAKER: with standard copy paste features and all that stuff.
[51:23] SPEAKER: I might try the client, the terminal client at some point,
[51:25] SPEAKER: but it's not really a main selling point for me,
[51:27] SPEAKER: although I'm glad it's there.
[51:29] SPEAKER: - Yeah, I'm just saying like,
[51:30] SPEAKER: if you have Dropbox hooked up on your server
[51:32] SPEAKER: and you want to have, like that gives you a way to paste,
[51:36] SPEAKER: like it lets you do the thing that's hard right now for me,
[51:39] SPEAKER: which is that I do research on a Windows machine.
[51:41] SPEAKER: And if I can't remote into that server from the,
[51:44] SPEAKER: I mean, on a Linux machine, on a desktop machine,
[51:46] SPEAKER: if I can't remote into that server,
[51:48] SPEAKER: 'cause it's down or something,
[51:50] SPEAKER: then I end up having a monitor open with commands
[51:53] SPEAKER: and typing the commands in like a caveman.
[51:55] SPEAKER: - Sure. - And it's not great.
[51:56] SPEAKER: - Oh, you know, actually that's a good argument
[51:57] SPEAKER: for just setting that client up as a fallback
[52:00] SPEAKER: if I can't get to it any other way,
[52:01] SPEAKER: now that you mention it. - Yeah, yeah, yeah.
[52:03] SPEAKER: - That brings me to another,
[52:05] SPEAKER: this is not necessarily a feature of Joplin
[52:07] SPEAKER: that is a good selling point,
[52:07] SPEAKER: but the way I set it up, I think, is worth noting,
[52:12] SPEAKER: which is, okay, I'm trying to think
[52:14] SPEAKER: where to start in the stack here,
[52:16] SPEAKER: because I'm storing the database
[52:17] SPEAKER: or all the files on my Dropbox, as I said,
[52:19] SPEAKER: but it would be nice to,
[52:21] SPEAKER: I think you can see where my mind is.
[52:23] SPEAKER: I'm trying to eliminate points of failure here.
[52:25] SPEAKER: - Yeah. - And so if Dropbox
[52:27] SPEAKER: gets meteors dropped on it tomorrow.
[52:29] SPEAKER: - Well, you'll still have the files
[52:30] SPEAKER: locally on your hard drive.
[52:31] SPEAKER: - Well, I'd have to look,
[52:33] SPEAKER: I don't know how the Windows app handles it, actually.
[52:34] SPEAKER: I don't know if it,
[52:35] SPEAKER: I guess it does probably cache those somewhere,
[52:38] SPEAKER: but that's, even a cache is ephemeral,
[52:39] SPEAKER: like I, you know, the-- - That's true.
[52:41] SPEAKER: - The canonical storage is on the Dropbox,
[52:44] SPEAKER: even if they are occasionally getting mirrored
[52:46] SPEAKER: to the wherever the Windows app lives.
[52:49] SPEAKER: I don't actually know if that's the case or not.
[52:51] SPEAKER: - You can R-clone it, right?
[52:53] SPEAKER: - Yeah, that's exactly where I'm going with this.
[52:54] SPEAKER: So years ago, I've talked about this before,
[52:56] SPEAKER: I set up R-clone mounts on my Linux server
[53:00] SPEAKER: for all my cloud storage stuff,
[53:01] SPEAKER: Dropbox, OneDrive, the various Google drives that I use.
[53:05] SPEAKER: I don't really use it that much.
[53:07] SPEAKER: Like I set it up 'cause it was cool,
[53:09] SPEAKER: and then it's come in handy a little bit here and there,
[53:10] SPEAKER: but it's not like something I use every day.
[53:12] SPEAKER: - Can I ask a stupid question about this?
[53:14] SPEAKER: - Sure.
[53:15] SPEAKER: - How's the performance on the R-clone Dropbox?
[53:18] SPEAKER: - Oh, Dropbox specifically, 'cause I was gonna say,
[53:19] SPEAKER: I think it varies based on how each cloud service
[53:22] SPEAKER: is gonna vary in how it serves data to you,
[53:25] SPEAKER: but it is noticeably slow
[53:28] SPEAKER: because it's not mirroring anything locally.
[53:30] SPEAKER: It's like everything exists on a server,
[53:32] SPEAKER: but you can access those mounts.
[53:33] SPEAKER: I mean, they are literal file system mounts in Linux terms,
[53:37] SPEAKER: just like every other, you know,
[53:38] SPEAKER: just like you mount a USB drive,
[53:40] SPEAKER: you're also mounting these so you can go in the command line
[53:43] SPEAKER: and LS the files in your Dropbox, but it-
[53:46] SPEAKER: - It just takes forever to enumerate for me.
[53:48] SPEAKER: It's like five, 10 seconds sometimes.
[53:49] SPEAKER: - It is, that's probably the biggest reason
[53:52] SPEAKER: I don't use it very much is that it is pretty slow to use,
[53:56] SPEAKER: but it can come in handy
[53:57] SPEAKER: if like the web interface breaks or something.
[54:00] SPEAKER: - Well, it's great for like the G drive
[54:04] SPEAKER: and the other services I use are all really, really fast.
[54:08] SPEAKER: - It's just Dropbox. - Oh, interesting, okay.
[54:11] SPEAKER: - They used to have like a Dropbox cache thing
[54:13] SPEAKER: that would cache the folder structure and stuff like that,
[54:16] SPEAKER: that they've deprecated.
[54:17] SPEAKER: And I don't know what the solution to the,
[54:19] SPEAKER: I wondered if you had found a solution.
[54:20] SPEAKER: - Oh, you mean- - This is why I was asking.
[54:22] SPEAKER: - You mean with our clone and Dropbox?
[54:23] SPEAKER: - Yeah, with our clone and Dropbox.
[54:24] SPEAKER: - Interesting, interesting. - They used to have a hack
[54:26] SPEAKER: that fixed the problem from a usability standpoint.
[54:28] SPEAKER: - Interesting, so I had never,
[54:29] SPEAKER: I'd almost never used my Dropbox mount for whatever reason.
[54:32] SPEAKER: It's mostly been Google Drive.
[54:34] SPEAKER: In fact, here's a, this is a little sidebar.
[54:36] SPEAKER: Here's a random example of why it was nice
[54:39] SPEAKER: to have these things, these mounts sitting around.
[54:42] SPEAKER: Google instituted, I think this is new
[54:44] SPEAKER: or it only started affecting me recently.
[54:47] SPEAKER: Google instituted some security feature in Google Drive
[54:50] SPEAKER: or maybe it's a browser level only feature
[54:52] SPEAKER: where trying to start multiple downloads at one time
[54:55] SPEAKER: gets blocked as a security precaution.
[54:57] SPEAKER: Have you seen that? - Oh.
[55:00] SPEAKER: - Maybe it's a feature of the, I don't know,
[55:02] SPEAKER: the specific Chrome that I, I don't know why this started,
[55:05] SPEAKER: but like at least once a week I download audio stems
[55:10] SPEAKER: from Vinny and Alex from Google Drive for next time
[55:13] SPEAKER: or like when I'm editing the ramble cast,
[55:14] SPEAKER: I need to pull down their local audio recordings
[55:16] SPEAKER: and I would go, I'd always go
[55:17] SPEAKER: and download both of those simultaneously.
[55:21] SPEAKER: And it got to the point where only,
[55:22] SPEAKER: and I always would go in alphabetical order.
[55:25] SPEAKER: So I would like. - A to V.
[55:27] SPEAKER: - Right, so like I basically, I would always download Alex
[55:30] SPEAKER: and then Vinny and for some reason it was,
[55:32] SPEAKER: it got to the point where it was downloading Alex's
[55:34] SPEAKER: and then refusing to download Vinny's.
[55:36] SPEAKER: Weird, and there was no error popping up saying why.
[55:39] SPEAKER: And I was like, what is going on with this file?
[55:41] SPEAKER: And eventually I figured it out.
[55:44] SPEAKER: But in the interim, when it was like, oh, what crap,
[55:46] SPEAKER: I need to get this podcast edited like this morning.
[55:49] SPEAKER: I don't have time to troubleshoot this.
[55:50] SPEAKER: I just went to my Linux mounts for that Google Drive
[55:55] SPEAKER: and just copied the file and the command line over.
[55:58] SPEAKER: And it was like, fine, whatever, I've got the file now.
[56:01] SPEAKER: Eventually, like I said, eventually I figured out
[56:03] SPEAKER: that it was some browser level security thing where it.
[56:06] SPEAKER: - Weird. - It basically treats
[56:07] SPEAKER: multiple downloads at a time as like a malware vector
[56:10] SPEAKER: or some kind of potential for abuse.
[56:13] SPEAKER: And I have this. - That's weird.
[56:14] SPEAKER: Is this in Chrome?
[56:15] SPEAKER: - It is a Chromium build.
[56:17] SPEAKER: I'm using Chromium for that stuff, which is maybe,
[56:20] SPEAKER: maybe they're trialing that actually.
[56:22] SPEAKER: Maybe that's a trial feature in Chromium
[56:24] SPEAKER: that's not rolled out or something, anyway.
[56:26] SPEAKER: - No rolling distros, but rolling browsers.
[56:28] SPEAKER: That's what I'm hearing. - Yeah, well, anyway.
[56:31] SPEAKER: - Get on that Zen life.
[56:32] SPEAKER: - Human beings are a land of contrasts.
[56:35] SPEAKER: - I know, I know.
[56:35] SPEAKER: - And anyway, it was just a random example
[56:37] SPEAKER: of like having that Linux mount for that Google Drive.
[56:40] SPEAKER: It was like, oh, that was handy in a pinch.
[56:41] SPEAKER: And this is another one of those cases
[56:44] SPEAKER: where I've got my Joplin store in a Dropbox,
[56:49] SPEAKER: but I just went and set up a timed job on my NAS
[56:51] SPEAKER: to like every two hours, just rsync the Joplin folder
[56:54] SPEAKER: from my Dropbox to my NAS.
[56:56] SPEAKER: - So then you always have the background.
[56:58] SPEAKER: - Right, right, so I've basically got a mirror
[56:59] SPEAKER: of the Dropbox Joplin stuff on a local machine
[57:03] SPEAKER: which in turn theoretically gets backed up here.
[57:07] SPEAKER: - I do like that a lot.
[57:08] SPEAKER: - Layers of redundancy and backups.
[57:10] SPEAKER: And like I've always got, like I said,
[57:12] SPEAKER: a copy of that data on a machine I own,
[57:15] SPEAKER: which was the goal here.
[57:17] SPEAKER: - I think Joplin, my experience with Joplin
[57:19] SPEAKER: was that if you're just keeping notes for you,
[57:21] SPEAKER: even if you're syncing them across multiple devices,
[57:24] SPEAKER: it's really, really good for that, right?
[57:26] SPEAKER: Like it gives you what you need.
[57:28] SPEAKER: - I don't think it has the same kind of groupware
[57:31] SPEAKER: kind of features that like Notion or Evernote
[57:34] SPEAKER: or any one of the other things has.
[57:36] SPEAKER: - Absolutely not.
[57:37] SPEAKER: I'll briefly touch on the client,
[57:38] SPEAKER: but I really haven't dug that much into it.
[57:40] SPEAKER: But also I don't know that there's all that much
[57:41] SPEAKER: to dig into.
[57:42] SPEAKER: I mean, it's just a text editor.
[57:44] SPEAKER: - Yeah, it's a plain text, I mean.
[57:46] SPEAKER: - It does markdown.
[57:48] SPEAKER: - Yeah, I almost think we, talking about this,
[57:50] SPEAKER: I feel like maybe we should do an episode on markdown.
[57:53] SPEAKER: 'Cause like the story of markdown is fascinating.
[57:55] SPEAKER: - Yeah, I didn't realize it's John Gruver
[57:57] SPEAKER: and Aaron Swartz who made it,
[57:59] SPEAKER: which is like, oh, those are names I know from other domains.
[58:02] SPEAKER: - Yep, you're burning pod here.
[58:03] SPEAKER: I think we have the possibility
[58:06] SPEAKER: of getting one of these people on, I think.
[58:07] SPEAKER: - Totally, oh, interesting.
[58:09] SPEAKER: All right, well, I wrote in our show notes here,
[58:11] SPEAKER: I wrote this has been a good way to learn markdown,
[58:13] SPEAKER: but then I wrote markdown is so simple,
[58:15] SPEAKER: I'm not sure you need to learn it.
[58:17] SPEAKER: So you can learn it in about five minutes.
[58:18] SPEAKER: - Markdown is really easy.
[58:20] SPEAKER: It is, if you spent time on bulletin boards
[58:24] SPEAKER: in the early 2000s or the nine UBBs specifically,
[58:28] SPEAKER: it's very reminiscent of like BB code and all those.
[58:31] SPEAKER: - Or if you were on IRC, you were doing versions of this
[58:33] SPEAKER: with that did not render to formatted texts
[58:35] SPEAKER: that just stayed plain ASCII,
[58:37] SPEAKER: but you still knew what they meant for emphasis.
[58:40] SPEAKER: - But yeah, markdown's real good.
[58:41] SPEAKER: - Like I spent years putting an asterisk around words
[58:45] SPEAKER: on either side to denote like bold or italic kind of emphasis
[58:49] SPEAKER: on IRC without it actually resulting in any,
[58:52] SPEAKER: you know what I mean?
[58:53] SPEAKER: - You can make your lists, you can do all that stuff.
[58:55] SPEAKER: Markdown is quite good.
[58:56] SPEAKER: - Yeah, so I'll say real quick,
[58:58] SPEAKER: I don't know if this is common to some of these others,
[58:59] SPEAKER: but Joplin defaults to this split view editor,
[59:02] SPEAKER: or it's kind of like a, it's a split pane,
[59:04] SPEAKER: like editor on one side and sort of rendered output
[59:07] SPEAKER: on the other.
[59:08] SPEAKER: And there are options there around, I set the editor,
[59:11] SPEAKER: the interactive part to as plain text as possible.
[59:14] SPEAKER: You can, in fact, I think it defaults to a rich text editor
[59:18] SPEAKER: where the bold looks bold and the italics are italics.
[59:20] SPEAKER: - It's like WYSIWYG, yeah.
[59:21] SPEAKER: - Right, but I switched that to just display
[59:23] SPEAKER: the raw markdown, 'cause I was like, like I said,
[59:25] SPEAKER: I was like, ah, there's a good chance to just like see
[59:27] SPEAKER: what the markdown formatting characters are
[59:30] SPEAKER: and learn to use those.
[59:31] SPEAKER: So I'm just kind of writing those manually,
[59:32] SPEAKER: but it's nice 'cause it shows, you know, on one side,
[59:36] SPEAKER: it's got all the asterisks and various bullet lists.
[59:40] SPEAKER: Here's how, you know, you put like a space
[59:42] SPEAKER: and then a hyphen and then a space,
[59:43] SPEAKER: and that turns into bullet list item, for example,
[59:45] SPEAKER: that kind of thing.
[59:46] SPEAKER: And then on the other side, it formats all of that.
[59:48] SPEAKER: So you can see what the output is like
[59:50] SPEAKER: and interact with the check boxes there
[59:52] SPEAKER: and that kind of thing.
[59:53] SPEAKER: - Well, and you can do things like link to other files
[59:57] SPEAKER: and stuff like that and link out, link internally,
[1:00:00] SPEAKER: all that kind of stuff.
[1:00:01] SPEAKER: - I haven't even looked into that stuff yet.
[1:00:03] SPEAKER: - The linking, it turns out the thing that I like most
[1:00:06] SPEAKER: about the Notion is the linking to other stuff
[1:00:08] SPEAKER: 'cause it means that your structure,
[1:00:11] SPEAKER: like it makes it really easy to make pages
[1:00:13] SPEAKER: off of other pages, basically.
[1:00:14] SPEAKER: So like I have a page for each of my recurring meetings
[1:00:18] SPEAKER: with one studio, right?
[1:00:19] SPEAKER: And then each entry in each meeting
[1:00:22] SPEAKER: that I'm taking notes for in there
[1:00:23] SPEAKER: goes into a sub folder, sub file in there.
[1:00:27] SPEAKER: And you can do that kind of stuff in Joplin as well,
[1:00:28] SPEAKER: as I recall.
[1:00:29] SPEAKER: - Yeah, is the check box syntax part of Markdown?
[1:00:33] SPEAKER: That's not a Joplin specific thing, right?
[1:00:35] SPEAKER: - You can make a checklist with Markdown, I believe.
[1:00:39] SPEAKER: Markdown's also extensible in a weird way.
[1:00:42] SPEAKER: - See, yeah, I fully believe it's the kind of thing
[1:00:44] SPEAKER: where it's like, oh, it's a standard,
[1:00:46] SPEAKER: but actually there's like eight different standards
[1:00:48] SPEAKER: and they're all changing all the time or whatever,
[1:00:49] SPEAKER: kind of like regular expressions or something.
[1:00:52] SPEAKER: - So this is, can we talk about,
[1:00:55] SPEAKER: can I share the good word about Pandoc now?
[1:00:57] SPEAKER: - Sure.
[1:00:58] SPEAKER: Well, actually, sorry.
[1:00:59] SPEAKER: I'm just gonna answer my own question before we move on
[1:01:00] SPEAKER: 'cause I have opened markdownlivepreview.com,
[1:01:03] SPEAKER: which is exactly what you think it is.
[1:01:05] SPEAKER: - Okay.
[1:01:06] SPEAKER: - It's just a web-based interactive Markdown thing.
[1:01:07] SPEAKER: And I'm putting the check box syntax
[1:01:10] SPEAKER: that I know from Joplin in here,
[1:01:12] SPEAKER: and it also made a check box,
[1:01:14] SPEAKER: although it's not letting me click it.
[1:01:16] SPEAKER: I think that's probably on the view side.
[1:01:19] SPEAKER: - Yeah, well now it's, anyway,
[1:01:21] SPEAKER: it is turning into a check box here
[1:01:22] SPEAKER: in this other non-Joplin Markdown editor.
[1:01:26] SPEAKER: So I'm gonna say the check boxes are a part of the standard.
[1:01:29] SPEAKER: - Markdown's surprisingly robust.
[1:01:30] SPEAKER: I remember asking, I can't remember if it was Dave or Andy
[1:01:33] SPEAKER: for Markdown support on the Whiskey Media text editor.
[1:01:38] SPEAKER: And they were like, what the hell do you want that for?
[1:01:40] SPEAKER: That's weird.
[1:01:41] SPEAKER: Nobody wants that.
[1:01:42] SPEAKER: I think people want that.
[1:01:43] SPEAKER: Markdown's pretty good.
[1:01:43] SPEAKER: It seems like it's had a life since then.
[1:01:46] SPEAKER: But anyway, real quick,
[1:01:47] SPEAKER: that was like an hour long preamble to say
[1:01:49] SPEAKER: that this to-do list, the centralized to-do list
[1:01:51] SPEAKER: I am now keeping is paying dividends
[1:01:53] SPEAKER: 'cause I am like knocking out tasks kind of left and right
[1:01:57] SPEAKER: in a way that is uncharacteristic for me.
[1:01:59] SPEAKER: Like it's been really nice to just,
[1:02:02] SPEAKER: I've always been somebody
[1:02:03] SPEAKER: who just organizes everything in my head.
[1:02:04] SPEAKER: And for-
[1:02:06] SPEAKER: - After you get too much stuff going,
[1:02:07] SPEAKER: you can't do that anymore.
[1:02:08] SPEAKER: - For reasons of workload or age or personal stuff
[1:02:11] SPEAKER: that's been going on or all of the above,
[1:02:13] SPEAKER: like it's just gotten to be too much.
[1:02:14] SPEAKER: Like I'm just like feeling very overwhelmed
[1:02:17] SPEAKER: by all the things I need to do
[1:02:18] SPEAKER: and not being able to keep them all in my head at one time.
[1:02:20] SPEAKER: And boy, it turns out writing everything down
[1:02:24] SPEAKER: that you need to do as you think of it
[1:02:25] SPEAKER: so it's all in one place.
[1:02:26] SPEAKER: And then crucially, checking,
[1:02:29] SPEAKER: like clicking a little box
[1:02:30] SPEAKER: and checking it off when you're done.
[1:02:32] SPEAKER: - Maintaining that list is my favorite part of the day.
[1:02:35] SPEAKER: - It's yeah, clicking the box and seeing it fill in
[1:02:38] SPEAKER: and seeing the texts go dark and knowing,
[1:02:41] SPEAKER: okay, I did that and it's done.
[1:02:42] SPEAKER: And now I can move it down to the done column.
[1:02:45] SPEAKER: There's a psychological reward component to this
[1:02:48] SPEAKER: that is highly motivating.
[1:02:51] SPEAKER: - When I started the VR company,
[1:02:52] SPEAKER: actually when I was doing testing,
[1:02:54] SPEAKER: I had the same realization like 10 years ago.
[1:02:56] SPEAKER: And I thought it was 'cause I was getting old at the time,
[1:02:58] SPEAKER: which is funny now in retrospect.
[1:03:01] SPEAKER: But I think it's like, if you think about our work lives,
[1:03:06] SPEAKER: you know, in 2003, I was writing 10 articles a month, right?
[1:03:10] SPEAKER: And a couple of reviews and some other little bits
[1:03:12] SPEAKER: and pieces, but it was like,
[1:03:14] SPEAKER: I could have had a post-it note with all the tasks
[1:03:17] SPEAKER: that I needed to do on any given 28 day period
[1:03:21] SPEAKER: and written those down and been pretty good.
[1:03:23] SPEAKER: And then we added the website and that added daily tasks
[1:03:25] SPEAKER: on top of the monthly tasks.
[1:03:27] SPEAKER: And like, and then we started doing video,
[1:03:29] SPEAKER: which meant that I had then editorial review
[1:03:31] SPEAKER: and podcast edits and all the different things
[1:03:33] SPEAKER: I had to look at and review at tested.
[1:03:36] SPEAKER: And then we started traveling all the time.
[1:03:39] SPEAKER: And that added another level of complexity
[1:03:41] SPEAKER: 'cause we had to book the travel
[1:03:42] SPEAKER: and we had to make sure we had confirmation.
[1:03:43] SPEAKER: We had to book the appointments.
[1:03:44] SPEAKER: We had to book the shoots and we had, you know,
[1:03:45] SPEAKER: all this other stuff to do.
[1:03:47] SPEAKER: And at some point in like 2014 or 2013,
[1:03:50] SPEAKER: I was just like, I can't keep track of this all.
[1:03:51] SPEAKER: And that's when I started using Wunderlist.
[1:03:53] SPEAKER: - And then I would add to that,
[1:03:54] SPEAKER: like being now being self-employed
[1:03:55] SPEAKER: has just amplified this effect exponentially
[1:03:58] SPEAKER: because now we are also juggling things
[1:04:00] SPEAKER: that other people at large companies used to do,
[1:04:02] SPEAKER: like payroll and taxes and IT and you name it,
[1:04:06] SPEAKER: AV production stuff.
[1:04:08] SPEAKER: It's a lot of different plates to spin.
[1:04:11] SPEAKER: And you're getting like, you know,
[1:04:13] SPEAKER: I work with four or five different companies
[1:04:14] SPEAKER: at any given time and then also do this podcast
[1:04:16] SPEAKER: and also do stuff with you and Vinny at Nexlander.
[1:04:18] SPEAKER: And like, it's just, it is incredibly helpful
[1:04:22] SPEAKER: both to have a really clean calendar
[1:04:23] SPEAKER: that I update the moment something changes
[1:04:25] SPEAKER: so that my free busy time is always valid.
[1:04:28] SPEAKER: And then having that task list that's constantly updated
[1:04:31] SPEAKER: means that I don't forget.
[1:04:33] SPEAKER: If somebody asks me to do something
[1:04:34] SPEAKER: in an offhand manner in a Slack,
[1:04:36] SPEAKER: if I don't write that down,
[1:04:37] SPEAKER: I will never remember that I'm supposed to do it.
[1:04:39] SPEAKER: Or in my, the way it happens for me
[1:04:41] SPEAKER: is I'll be like doing the dishes or in the shower
[1:04:43] SPEAKER: or some place where I can't do the thing
[1:04:45] SPEAKER: and it'll pop back into my head in an anxious way
[1:04:47] SPEAKER: and go like, oh God, I forgot I needed to do that.
[1:04:49] SPEAKER: And it's been a week, oh crap.
[1:04:51] SPEAKER: And then I still don't get it done
[1:04:53] SPEAKER: 'cause I am never in front of the thing I need to do
[1:04:56] SPEAKER: when I think of it.
[1:04:57] SPEAKER: But I guess to further advocate for this
[1:05:00] SPEAKER: as a lifestyle change,
[1:05:01] SPEAKER: like I was always kind of defiant about this.
[1:05:03] SPEAKER: I was like, I don't need to write that stuff down.
[1:05:05] SPEAKER: I can do it myself.
[1:05:06] SPEAKER: I can do it in my head.
[1:05:07] SPEAKER: I can remember all this stuff.
[1:05:08] SPEAKER: Like there was a certain-
[1:05:10] SPEAKER: - You're freeing yourself, man.
[1:05:11] SPEAKER: - Yeah, there was a certain contrarian kind of impulse
[1:05:14] SPEAKER: that I had about like, I don't want to do more work
[1:05:17] SPEAKER: so I can do work.
[1:05:18] SPEAKER: You know, that's what it was.
[1:05:19] SPEAKER: It was like, I don't wanna maintain another app
[1:05:20] SPEAKER: and have to write stuff down to do it.
[1:05:22] SPEAKER: What if I just did it
[1:05:23] SPEAKER: and skipped all those intermediate steps?
[1:05:24] SPEAKER: But I am here to say that at a certain point
[1:05:28] SPEAKER: that doesn't work anymore.
[1:05:29] SPEAKER: And if you're trying to keep up a lot of stuff,
[1:05:33] SPEAKER: you owe it to yourself to maybe get a little more organized,
[1:05:35] SPEAKER: you will thank yourself.
[1:05:36] SPEAKER: - So I will tell you,
[1:05:38] SPEAKER: when they made me the editor of Maximum PC,
[1:05:41] SPEAKER: John Phillips was like,
[1:05:42] SPEAKER: hey, you gotta go to an organizational class.
[1:05:44] SPEAKER: You gotta learn how to manage time.
[1:05:46] SPEAKER: And I thought it was stupid.
[1:05:48] SPEAKER: And they sent me to one of those Franklin
[1:05:50] SPEAKER: seven habits of highly effective people classes
[1:05:53] SPEAKER: where everybody they're trying to sell like paper binders
[1:05:55] SPEAKER: with your to-do list and your calendar and stuff in it.
[1:05:59] SPEAKER: And it was stupid.
[1:06:00] SPEAKER: And then in the early 2010s,
[1:06:04] SPEAKER: life hackers started writing about,
[1:06:05] SPEAKER: I wanna say it was like 43 folders or something like that.
[1:06:08] SPEAKER: One of those kind of getting things done mechanisms
[1:06:11] SPEAKER: that's like today,
[1:06:12] SPEAKER: like the idea is it's today's tasks, this week's tasks,
[1:06:15] SPEAKER: this month's tasks, and then next month's tasks.
[1:06:18] SPEAKER: And like a lot of that stuff is full of like business,
[1:06:22] SPEAKER: like it's the business equivalent of like new age crystals.
[1:06:24] SPEAKER: - Oh yeah. - Right?
[1:06:25] SPEAKER: - Oh yeah.
[1:06:26] SPEAKER: - But finding a system that lets you record
[1:06:30] SPEAKER: what you need to do and track your time
[1:06:34] SPEAKER: is incredibly worth investing in.
[1:06:36] SPEAKER: Especially like even if you're not busy enough
[1:06:38] SPEAKER: to need that right now at some point in your future,
[1:06:41] SPEAKER: you will be busy enough
[1:06:42] SPEAKER: and it will keep you from going crazy.
[1:06:43] SPEAKER: It'll keep you from burning out.
[1:06:45] SPEAKER: It'll keep you from torturing your stuff.
[1:06:46] SPEAKER: And like the answer for some people is agile
[1:06:49] SPEAKER: and JIRA and waterfall charts and Gantt charts
[1:06:51] SPEAKER: and all that stuff.
[1:06:52] SPEAKER: And for other people it's,
[1:06:54] SPEAKER: I don't think a Gantt chart is actually that
[1:06:55] SPEAKER: when I think about it.
[1:06:56] SPEAKER: But anyway, for other people it's,
[1:07:00] SPEAKER: hey, I have a piece of paper
[1:07:01] SPEAKER: typed on the side of my monitor
[1:07:02] SPEAKER: that I put up a new one every day
[1:07:03] SPEAKER: and it tells me what I need to get done that day.
[1:07:05] SPEAKER: Both of those are equally valid.
[1:07:06] SPEAKER: Like there's no wrong way to do this.
[1:07:09] SPEAKER: Can I make a pitch for you, Brad?
[1:07:11] SPEAKER: - Sure.
[1:07:12] SPEAKER: - I think you should keep your secure stuff
[1:07:13] SPEAKER: in your password manager,
[1:07:14] SPEAKER: like your Windows keys and your,
[1:07:17] SPEAKER: like I have all my account recovery keys
[1:07:19] SPEAKER: except for obviously 1Password,
[1:07:21] SPEAKER: live in a 1Password notes section.
[1:07:26] SPEAKER: - So I basically do that.
[1:07:28] SPEAKER: Like the stuff I'm putting into this Joplin database
[1:07:30] SPEAKER: is lower impact.
[1:07:32] SPEAKER: That's why I was harping on Windows keys, for example,
[1:07:35] SPEAKER: because things that are more sensitive than that
[1:07:37] SPEAKER: are definitely going into the password manager,
[1:07:39] SPEAKER: even when they're not logins.
[1:07:40] SPEAKER: Like you said, I assume you're talking about
[1:07:43] SPEAKER: just like some kind of secure note thing
[1:07:44] SPEAKER: for jotting stuff down in your.
[1:07:46] SPEAKER: - Yeah, 1Password has a notes,
[1:07:48] SPEAKER: has like multiple data types of logins
[1:07:50] SPEAKER: and passwords and server console passwords
[1:07:52] SPEAKER: and stuff like that.
[1:07:53] SPEAKER: But data is just one of them.
[1:07:55] SPEAKER: - I always feel a little weird about talking publicly
[1:07:57] SPEAKER: about which secrets I put where,
[1:07:59] SPEAKER: but maybe I'm having delusions of grandeur
[1:08:01] SPEAKER: and nobody cares that much about my data.
[1:08:04] SPEAKER: - I mean, if somebody gets into my password manager,
[1:08:05] SPEAKER: I've got larger problems, I guess.
[1:08:07] SPEAKER: - That's kind of how I feel, I guess,
[1:08:09] SPEAKER: is that like the decryption phrases for various,
[1:08:12] SPEAKER: like SSH keys are maybe not my biggest concern.
[1:08:15] SPEAKER: If the thing that also has my like financial passwords
[1:08:19] SPEAKER: and it gets breached, that's a bigger concern.
[1:08:22] SPEAKER: - That would be bad.
[1:08:22] SPEAKER: - But you're right, yes.
[1:08:24] SPEAKER: So anything that is like kind of more sensitive
[1:08:26] SPEAKER: than something like a product key
[1:08:27] SPEAKER: or a doctor's appointment thing
[1:08:29] SPEAKER: is going in the password manager.
[1:08:31] SPEAKER: - Can we talk about Pandoc for a sec?
[1:08:33] SPEAKER: 'Cause it is dope.
[1:08:34] SPEAKER: So Pandoc is a tool that lets you convert
[1:08:37] SPEAKER: between Markdown and a bazillion other formats,
[1:08:39] SPEAKER: including like BB code and the Steam Markdown
[1:08:43] SPEAKER: that they've used for 20 years now, 25 years.
[1:08:45] SPEAKER: - Jeez, there's several dozen of these on here.
[1:08:48] SPEAKER: - Oh, and there's more.
[1:08:51] SPEAKER: 'Cause the way you build new formats
[1:08:54] SPEAKER: is with just a really simple Lua plugin.
[1:08:56] SPEAKER: And there are a literal bazillion of them if you search.
[1:09:00] SPEAKER: - Oh, wait, is this a command line tool?
[1:09:01] SPEAKER: - It's both, you can do a command line.
[1:09:03] SPEAKER: There was also some desktop clients,
[1:09:04] SPEAKER: depending on what OS you're on.
[1:09:06] SPEAKER: - I'm looking at pandoc.org to be clear
[1:09:08] SPEAKER: for people who want to follow along.
[1:09:09] SPEAKER: But there are a lot of things on here.
[1:09:11] SPEAKER: - P-A-N-D-O-C, it is, I spent a really long time
[1:09:16] SPEAKER: when I was working on "The Anacrusis"
[1:09:17] SPEAKER: and doing patch notes twice a week sometimes,
[1:09:20] SPEAKER: trying to find something that would let me write
[1:09:22] SPEAKER: my patch notes in a normal human text editor
[1:09:25] SPEAKER: and then export them to Steam's janky BB code based format.
[1:09:29] SPEAKER: And this, it turns out, was the tool.
[1:09:31] SPEAKER: - Oh, this is crazy.
[1:09:32] SPEAKER: I definitely have got to get this.
[1:09:34] SPEAKER: First of all, under lightweight markup formats,
[1:09:37] SPEAKER: not only are there a bunch besides markdown,
[1:09:39] SPEAKER: like re-structured text, ASCII doc, textile,
[1:09:42] SPEAKER: text to tags, mark you a deejot, deejot?
[1:09:46] SPEAKER: - I don't know what that one is.
[1:09:47] SPEAKER: - Anyway, but there are also multiple types of markdown,
[1:09:50] SPEAKER: just like I guessed.
[1:09:51] SPEAKER: This says markdown including common mark
[1:09:53] SPEAKER: and GitHub flavored markdown.
[1:09:56] SPEAKER: But there is-
[1:09:57] SPEAKER: - You can also do media wiki formats.
[1:09:59] SPEAKER: - Yeah, there's wiki markup formats.
[1:10:01] SPEAKER: There's word, you can do word processor formats
[1:10:04] SPEAKER: like doc X and rich text, RTF.
[1:10:06] SPEAKER: You can do EPUB, the ebook format,
[1:10:08] SPEAKER: different types of HTML.
[1:10:09] SPEAKER: Roth, I had occasion to learn what Roth is.
[1:10:13] SPEAKER: - I don't know what that is.
[1:10:15] SPEAKER: - It's like terminal text formatting stuff.
[1:10:18] SPEAKER: XML form, wow, this is like a crazy Swiss army knife of,
[1:10:22] SPEAKER: I mean, that's kind of what their little mascot
[1:10:25] SPEAKER: gadget logo character is here is a little gadget
[1:10:28] SPEAKER: with like eight different arms coming out of it.
[1:10:30] SPEAKER: - It is, so the thing you might not have noticed
[1:10:32] SPEAKER: on this page, but they have to and froms.
[1:10:34] SPEAKER: So those arrows are from this to this.
[1:10:37] SPEAKER: - Yes, arrows show like which directions
[1:10:39] SPEAKER: can be converted to and from,
[1:10:40] SPEAKER: which is also handy for sure.
[1:10:42] SPEAKER: - Yeah, it is an incredible, like if you have,
[1:10:45] SPEAKER: like a lot of times in games,
[1:10:47] SPEAKER: you end up with somebody putting a bunch of data
[1:10:49] SPEAKER: into a spreadsheet that you need,
[1:10:50] SPEAKER: then you need to get into another format.
[1:10:52] SPEAKER: It's incredible for that stuff, right?
[1:10:53] SPEAKER: - Okay, hang on, I'm just gonna run an experiment here.
[1:10:56] SPEAKER: - Okay.
[1:10:57] SPEAKER: - Apt search pandoc.
[1:10:59] SPEAKER: - Oh yeah, it's in there.
[1:11:00] SPEAKER: - Oh wow, that's a lot of stuff that came back actually.
[1:11:02] SPEAKER: - Yeah, there's a bazillion, so there's,
[1:11:04] SPEAKER: if it's like the arch user repository,
[1:11:07] SPEAKER: there'll be like a core pandoc in the main repo
[1:11:09] SPEAKER: and then a bazillion plugins or filters, sorry.
[1:11:12] SPEAKER: - The main tool, but anyway, yes,
[1:11:14] SPEAKER: this is absolutely something I'm going to install and use.
[1:11:16] SPEAKER: There's like, man, ANSI formatted text, CSVs, this is crazy.
[1:11:21] SPEAKER: - It is, and like I said, the stuff that's on their homepage
[1:11:24] SPEAKER: is just the stuff they natively support.
[1:11:26] SPEAKER: - Okay, that's really useful.
[1:11:28] SPEAKER: - There's a bunch of people
[1:11:29] SPEAKER: that have written Haskell plugins for this
[1:11:31] SPEAKER: that will do anything that Haskell knows how to deal with.
[1:11:35] SPEAKER: Like it's wild, it is an, like I said,
[1:11:38] SPEAKER: when I was writing patch notes
[1:11:39] SPEAKER: and I had to post them on five different places,
[1:11:42] SPEAKER: this would let me write it once in markdown
[1:11:44] SPEAKER: and then export it to the five different versions,
[1:11:47] SPEAKER: open that up, copy and paste.
[1:11:48] SPEAKER: And what had been like two hours of copying and formatting
[1:11:52] SPEAKER: and adjusting text became five minutes of pasting
[1:11:55] SPEAKER: in different places.
[1:11:56] SPEAKER: - Doing some worm work over there,
[1:11:57] SPEAKER: some write once, read many.
[1:11:59] SPEAKER: - Yes, yes, I love writing once and reading many.
[1:12:02] SPEAKER: - Love to worm.
[1:12:03] SPEAKER: - Love, love, live to worm.
[1:12:05] SPEAKER: So yeah, that's it, that's our adventure
[1:12:07] SPEAKER: through text editor, note-taking apps, I guess.
[1:12:09] SPEAKER: - I'm reminding myself that's not at all what worm means
[1:12:12] SPEAKER: in the classical sense.
[1:12:15] SPEAKER: - What does worm mean in the classical, write once, really?
[1:12:18] SPEAKER: It's not write once, read many?
[1:12:20] SPEAKER: - No, that is what it, sorry, that is what it stands for.
[1:12:21] SPEAKER: What I mean is that it's a completely different context
[1:12:24] SPEAKER: that that worm is used in.
[1:12:26] SPEAKER: Can I remind you of the existence of a worm drive?
[1:12:29] SPEAKER: - Oh yeah, of course.
[1:12:30] SPEAKER: - This is more of like a physical storage device,
[1:12:34] SPEAKER: like magneto-optical kind of situation.
[1:12:37] SPEAKER: - So you could do backups and stuff like that.
[1:12:40] SPEAKER: - This is like an early post floppy disk term
[1:12:42] SPEAKER: for like pre-CDR post floppy disk,
[1:12:46] SPEAKER: kind of weird magneto-optical stuff,
[1:12:49] SPEAKER: like our Iomega devices worm drives maybe, I don't know.
[1:12:52] SPEAKER: This is-
[1:12:53] SPEAKER: - No, they're write once, write many.
[1:12:55] SPEAKER: - Yeah, of course, yes.
[1:12:56] SPEAKER: So that's, anyway, whatever this podcast needs to end.
[1:12:59] SPEAKER: Maybe we'll do an episode on worm drives or something, but.
[1:13:02] SPEAKER: - Yeah, let's get our worm drive on.
[1:13:04] SPEAKER: It's the whole part, one thing I've realized
[1:13:08] SPEAKER: we didn't talk about at all here is Apple Notes,
[1:13:10] SPEAKER: which has gotten kind of robust and kind of splits the gap
[1:13:13] SPEAKER: between things you can share and things you can keep locally.
[1:13:16] SPEAKER: - I actually had this conversation with my mom
[1:13:17] SPEAKER: when I was telling her like, "Oh, set up this Notes app."
[1:13:19] SPEAKER: And it's like really helping me get organized,
[1:13:21] SPEAKER: but she's only on Apple devices.
[1:13:23] SPEAKER: So when she was asking about it, I was like,
[1:13:24] SPEAKER: "Oh, you should probably just use Apple Notes
[1:13:26] SPEAKER: because you're just on a MacBook and an iPhone."
[1:13:29] SPEAKER: - Well, and it's really nice 'cause like Apple Notes
[1:13:32] SPEAKER: and Reminders both now will sync across other Apple,
[1:13:35] SPEAKER: to other Apple users.
[1:13:37] SPEAKER: The problem I have with them is that they really don't live
[1:13:39] SPEAKER: outside of the Apple ecosystem.
[1:13:41] SPEAKER: So if I want to access that stuff on Linux or Windows,
[1:13:43] SPEAKER: it's using the web app, which sucks.
[1:13:44] SPEAKER: - Yeah, but if you're all Apple all the time,
[1:13:46] SPEAKER: that seems like probably a good option or maybe the option.
[1:13:50] SPEAKER: - Look, my wife and I have shared dog notes
[1:13:53] SPEAKER: and shared dog task lists that are like,
[1:13:56] SPEAKER: "Give the flea medicine,
[1:13:57] SPEAKER: and here's when the next dog appointment is,"
[1:14:00] SPEAKER: and stuff like that, which is really handy.
[1:14:01] SPEAKER: So anyway, that's the end of our Notes.
[1:14:04] SPEAKER: I would love to know what you all use for your Notes apps.
[1:14:07] SPEAKER: What do we miss stuff?
[1:14:08] SPEAKER: Is there stuff out there that is compelling and interesting?
[1:14:11] SPEAKER: I'm also wildly curious what people use Notion for
[1:14:14] SPEAKER: 'cause there's a bunch of really wild use cases
[1:14:17] SPEAKER: for Notion these days.
[1:14:18] SPEAKER: - Yes, give us notes about Notes apps.
[1:14:21] SPEAKER: Give us notes about our notes about Note apps.
[1:14:23] SPEAKER: - Are those Notes notes?
[1:14:24] SPEAKER: - Sure, probably.
[1:14:25] SPEAKER: Yeah, I'm sure people have other suggestions on use cases
[1:14:28] SPEAKER: 'cause this does seem like a pretty broad field.
[1:14:32] SPEAKER: - Yeah, the email address is techpod@content.town,
[1:14:35] SPEAKER: or you can post in the thread in the Discord.
[1:14:38] SPEAKER: And if you're not in the Discord,
[1:14:39] SPEAKER: what the hell are you doing?
[1:14:39] SPEAKER: Get in the Discord.
[1:14:40] SPEAKER: You can go to patreon.com/techpod where for $5 a month,
[1:14:45] SPEAKER: you get access to the Discord.
[1:14:46] SPEAKER: You get access to our monthly Patreon exclusive episode
[1:14:49] SPEAKER: where we're gonna build our own Lua filter for Joplin
[1:14:52] SPEAKER: and for Pandoc.
[1:14:54] SPEAKER: We're not gonna actually do that, but maybe.
[1:14:55] SPEAKER: Actually, I had an idea the other day.
[1:14:58] SPEAKER: But yeah, we're gonna do all that
[1:15:00] SPEAKER: and you can get in there too.
[1:15:02] SPEAKER: Again, it's patreon.com/techpod.
[1:15:04] SPEAKER: There's always interesting conversations going on.
[1:15:07] SPEAKER: Yesterday, people were talking about American fast food
[1:15:11] SPEAKER: and like the rise of the quesarito in Texas,
[1:15:16] SPEAKER: in Texas taquerias, where they're just,
[1:15:20] SPEAKER: people will, you can take a burrito at this place in Texas
[1:15:24] SPEAKER: and if you pay them an extra few bucks,
[1:15:26] SPEAKER: they'll quesarito it by wrapping a quesadilla
[1:15:28] SPEAKER: around the outside of the burrito.
[1:15:30] SPEAKER: And let me go and tell you,
[1:15:31] SPEAKER: that's the kind of food science I'm here for.
[1:15:33] SPEAKER: - So was that, which restaurant?
[1:15:36] SPEAKER: - Oh, that was Freebirds, yeah.
[1:15:38] SPEAKER: - It's Freebirds, yeah.
[1:15:39] SPEAKER: - I've heard of Freebirds.
[1:15:40] SPEAKER: I don't know how widespread they are though.
[1:15:42] SPEAKER: - I've never been to Freebirds,
[1:15:43] SPEAKER: but I assume that when you go in,
[1:15:44] SPEAKER: they're just always playing Freebird.
[1:15:46] SPEAKER: - Problem I have. - Just 24/7 loop.
[1:15:48] SPEAKER: That would be hell.
[1:15:49] SPEAKER: - I don't know about that.
[1:15:50] SPEAKER: Are they Austin based?
[1:15:52] SPEAKER: I think, I feel like they came out of Austin, Texas,
[1:15:55] SPEAKER: primarily, is that correct?
[1:15:57] SPEAKER: - That I don't know.
[1:15:59] SPEAKER: - Do you wanna see?
[1:16:00] SPEAKER: Okay, this is the last thing
[1:16:01] SPEAKER: and then we have to end this podcast,
[1:16:03] SPEAKER: but I'm gonna send you a picture.
[1:16:05] SPEAKER: - Oh, okay.
[1:16:06] SPEAKER: - It has to be AI generated, right?
[1:16:09] SPEAKER: - Man.
[1:16:10] SPEAKER: Oh yeah, I saw that this morning, it's a nightmare.
[1:16:12] SPEAKER: That is the Maggot Burrito, yes, 100% AI generated.
[1:16:15] SPEAKER: - The Xenomorph Breakfast Burrito
[1:16:17] SPEAKER: that some restaurant seems to have put up,
[1:16:19] SPEAKER: like nobody in the chain of getting this printed
[1:16:21] SPEAKER: and put on the restaurant window thought,
[1:16:23] SPEAKER: maybe we shouldn't post this Nightmare Hive Burrito.
[1:16:28] SPEAKER: - The problem, a big problem with the AI stuff
[1:16:30] SPEAKER: is that one person who has the worst ideas
[1:16:32] SPEAKER: in your organization can post any picture
[1:16:35] SPEAKER: they want without having to talk to somebody
[1:16:36] SPEAKER: who has actual skills.
[1:16:38] SPEAKER: And this is emblematic of that.
[1:16:40] SPEAKER: Somebody posted, I think it was in the Discord,
[1:16:43] SPEAKER: actually, the other day, they posted a picture
[1:16:44] SPEAKER: of one of those old letter boards with the push pins
[1:16:47] SPEAKER: that you kind of like, you have the plastic letters
[1:16:50] SPEAKER: and you stick 'em in and there was usually a Coca-Cola
[1:16:52] SPEAKER: or a Pepsi or something on the top of it and it was like,
[1:16:53] SPEAKER: hey, here's the menu for today
[1:16:54] SPEAKER: and it's like hot dog, hamburger.
[1:16:57] SPEAKER: And they said, hey, I like this infinitely better
[1:16:59] SPEAKER: than any one of these AI generated slop menu images.
[1:17:05] SPEAKER: A, because it looks like something and you can read it,
[1:17:08] SPEAKER: but B, all of, when you, I don't know if you've gone
[1:17:11] SPEAKER: to Oakland lately, when you're driving through the corridor
[1:17:13] SPEAKER: on 80 where all the billboards are, they all look the same
[1:17:17] SPEAKER: because everybody's typing the same shit into chat GPT.
[1:17:20] SPEAKER: - It's, yes, the AI generated billboards about AI
[1:17:24] SPEAKER: up and down freeways around San Francisco
[1:17:26] SPEAKER: are a nightmare right now.
[1:17:27] SPEAKER: - Yeah, it's bad.
[1:17:29] SPEAKER: Anyway, patreon.com/checkpod.
[1:17:31] SPEAKER: You too can bitch about AI images in there.
[1:17:33] SPEAKER: It's one of our favorite things to complain about.
[1:17:36] SPEAKER: And you get access to the monthly patron exclusive episode,
[1:17:38] SPEAKER: which will go up next week.
[1:17:40] SPEAKER: It's questions next month.
[1:17:41] SPEAKER: So send your questions in.
[1:17:42] SPEAKER: There's a question seeking answers channel in the discord.
[1:17:44] SPEAKER: You can send them to techpod@content.town.
[1:17:47] SPEAKER: And this is the part where we thank our patrons.
[1:17:49] SPEAKER: So thank you everybody who supports the show,
[1:17:52] SPEAKER: but an extra special thank you goes out
[1:17:54] SPEAKER: to our executive producer, to your patrons,
[1:17:56] SPEAKER: including Infelicitous Rips, Jordan Lippett.
[1:17:59] SPEAKER: You're part of the Bunny Crime Cinematic Universe
[1:18:03] SPEAKER: and James Kamik.
[1:18:03] SPEAKER: Thank you all so, so much.
[1:18:04] SPEAKER: - Yeah, thank you. - Have a good year.
[1:18:05] SPEAKER: - Yeah, we appreciate everybody's support.
[1:18:07] SPEAKER: And we will be back next week
[1:18:09] SPEAKER: with another edition of the TechPod.
[1:18:10] SPEAKER: Until then, please consider the environment
[1:18:13] SPEAKER: before printing this podcast.
[1:18:14] SPEAKER: (upbeat music)
