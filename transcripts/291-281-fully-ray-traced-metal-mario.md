---
episode: 291
title: 281: Fully Ray-Traced Metal Mario
date: 2025-04-06
guests: none
duration: 1:18:33
---

[00:00] SPEAKER: okay guys i did something stupid shameful indeed no i mean look it's it's tree pollen season here in
[00:06] SPEAKER: northern california and i don't know about you but i get a little sneezy oh yeah and earlier this
[00:12] SPEAKER: week i was sneezing so so hard that i bit my tongue harder than i have ever bit my tongue before
[00:19] SPEAKER: e and i thought i might have to go get stitches because it was like bleeding for it like sorry
[00:26] SPEAKER: this is i guess content warning uh it was it went for a long time and it hurt a lot and it still is
[00:33] SPEAKER: a little bit weird and swollen and herdy so my voice sounds weird where i sound like i have a
[00:36] SPEAKER: little bit of a lisp now you know why i'm trying to imagine the mechanics of that when you sneeze
[00:42] SPEAKER: like the what would it take for your tongue to be directly beneath your teeth also do your teeth
[00:46] SPEAKER: really like bite down when you sneeze so my mouth is small yeah let's talk about the size of your
[00:52] SPEAKER: mouth will yeah my mouth is small my tongue is large and and beefy and uh when i got in there
[00:58] SPEAKER: it just clipped it on the back edge like the back side oh i was envisioning like the tip of your
[01:03] SPEAKER: tongue getting no the tip is caught between your front teeth tips totally fine the back
[01:08] SPEAKER: back left side is a nightmare it's real bad you got into the meat of it with like your molars
[01:13] SPEAKER: you go ahead and tell yeah i clipped it with a molar real good and i was like wow that really
[01:17] SPEAKER: hurt and then uh it got worse progressively the more i talked throughout the day i did the next
[01:22] SPEAKER: later podcast after doing this in the morning it wasn't too bad when i started by the end i was
[01:25] SPEAKER: like oh i might have made a mistake that's crazy because you were yeah i was on that podcast with
[01:29] SPEAKER: you and i noticed no difference at all but now now you know well it's it's always the day after
[01:34] SPEAKER: right it's not the day of the injury it's like the day after or the day after that when it gets really
[01:37] SPEAKER: bad but do people still believe that like sneezing is like a miniature orgasm i mean look wasn't that
[01:45] SPEAKER: there's a lot of pain involved in high school that's like somebody's like oh did you know a
[01:50] SPEAKER: sneeze is like a miniature orgasm right i was i think that person doesn't has never experienced
[01:54] SPEAKER: one or the other so yeah so it seems to be getting better but this is the first time i've done any
[02:00] SPEAKER: appreciable talking since that next lander episode and uh i've been i've been going to tell you i'm
[02:06] SPEAKER: never going to sign up to get my tongue pierced after this because damn son this is not what you
[02:12] SPEAKER: want in your mouthful region what do you want your mouthful region no i'm good we can stop there
[02:42] SPEAKER: so welcome to brad and will made a tech pod i'm will i'm brad and i'm adam and yeah oh yeah
[02:52] SPEAKER: he doesn't wait for the intro here he is oh he's just he's just family now you know he can he just
[02:57] SPEAKER: he just enters himself now yeah adam patrick murray of pc world and the full nerd fame is
[03:02] SPEAKER: joining us today because we are talking about something that he is something of a specialist in
[03:07] SPEAKER: that's right also is this is this a first i was on the full nerd this week and now adam is on
[03:12] SPEAKER: the tech pod this week all in the same week that's it's not a full rotation right yeah yeah because
[03:18] SPEAKER: i was on nextlander this week so that's right you were it's just i mean this is the destiny of every
[03:22] SPEAKER: podcast host is to eventually appear on every podcast they come in contact with we're orbiting
[03:28] SPEAKER: a podcast singularity right now um yeah so we're talking about handhelds because switch switch two
[03:34] SPEAKER: was announced uh brad and i and vinny talked about that on the tech on the nextlander show this week
[03:38] SPEAKER: um we probably won't talk too much about the switch stuff on the full nerd next week would
[03:42] SPEAKER: be my guess maybe a little bit but we'll see yeah there is an nvidia chip in there it's a computer
[03:48] SPEAKER: that's true that's true uh thousands of engineer years of effort went into that thing from nvidia
[03:53] SPEAKER: so clearly serious hardware um but yeah we're going to talk about switch stuff we're going to
[03:58] SPEAKER: talk about kind of the overall state of the handheld union because there's stuff happening
[04:02] SPEAKER: there's rumors on the xbox side and then the steam deck uh there's all sorts of weird stuff happening
[04:07] SPEAKER: with steam os so we'll talk about that and then like what's going on with windows and and non
[04:12] SPEAKER: windows pc handhelds so anyway i'm excited i'm excited thanks for letting me be here you're you're
[04:19] SPEAKER: like probably the handheld expert of everyone i know right i think you i mean i know will does
[04:24] SPEAKER: some testing too now but i feel like you probably get your hands on more of these things and anybody
[04:28] SPEAKER: else i know too many through your office yeah i have too many i don't know it's a big pile of them
[04:34] SPEAKER: at the office and they're they're just frankly i guess the fact that there are too many of them
[04:38] SPEAKER: now is kind of why we're doing this episode to a large degree i mean like everybody credits the
[04:42] SPEAKER: steam deck for creating this new sort of market market segment or cottage industry or whatever
[04:46] SPEAKER: you want to call it but i really i feel like the switch one gets kind of short shrift in that
[04:51] SPEAKER: conversation because really it was the switch right i mean it's not it doesn't exist in the
[04:55] SPEAKER: pc space nintendo is in its own silo but there is no steam deck without a switch one right and and
[05:01] SPEAKER: it's like wildly popular right i mean nintendo always traditionally had a home console and a
[05:07] SPEAKER: portable console and i've always been a huge fan of the portable consoles my first console i owned
[05:13] SPEAKER: uh was the the game boy so i have a big affinity for handhelds and yeah the switch was the first
[05:19] SPEAKER: time they were like hey what if what if it was both what if it was a handheld and a home console
[05:25] SPEAKER: in one and people were like that's crazy you can't do that and then they did it and then yeah i feel
[05:30] SPEAKER: like then the pc side was like oh well hold my beer we can do it better yeah i wouldn't surprise
[05:36] SPEAKER: me if valve looked at the success of stuff like hades and uh short hike and all those kinds of
[05:42] SPEAKER: games like the the kind of the kind of wildly successful blower blower um uh like lower hardware
[05:51] SPEAKER: requirement indie games and was like and and saw literally i think it was either hades or dead cells
[05:59] SPEAKER: you could sync your steam progress across to the switch version by putting in a special code and
[06:03] SPEAKER: it would use their little back end thing so like it was like your portable steam version
[06:09] SPEAKER: and that was like hey we should get some of that money man and they did
[06:12] SPEAKER: yeah oh yeah i guess i do like the the the hybrid um the hybrid gimmick is like way de-emphasized
[06:19] SPEAKER: for the steam deck right like i know they do sell a doc you can get third-party docs like you can
[06:22] SPEAKER: play it on a tv but like i feel like i feel like play your steam deck on a tv is not part of the
[06:27] SPEAKER: steam deck story the way that feature is part of the switch story you know so like maybe that's why
[06:32] SPEAKER: the steam deck gets talked about in a slightly different way than the switch to some extent
[06:36] SPEAKER: i would say it's also not as seamless right with the switch the whole thing is just like you slide
[06:41] SPEAKER: it into that dock and everyone has the same dock and then you slide off the the controllers and
[06:47] SPEAKER: you're off to the races i feel like for a steam deck or even any of the other windows based ones
[06:52] SPEAKER: it just takes a little bit more setup and a little more finicky i guess yeah well and
[07:00] SPEAKER: you know to that point like the steam deck just got hdmi cc like last fall last winter like it's
[07:06] SPEAKER: it's it's new like so it couldn't it couldn't automatically turn on your tv for you when you
[07:11] SPEAKER: plugged it in until very recently stuff like that um when you plug in an external controller you
[07:16] SPEAKER: can't wake it up with that or i guess you can now but you couldn't until very recently for that
[07:20] SPEAKER: either so um so yeah it's not it's not as much of a consumer device as like i don't think there's
[07:28] SPEAKER: multi-user mode on the steam deck yet is there can you have more than one account on the steam deck
[07:33] SPEAKER: oh i don't think you can you're right yeah yeah so there's that's an extra weird omission for
[07:40] SPEAKER: a device that runs linux well you can put multiple user accounts on the system level but you'd have
[07:46] SPEAKER: to shell out to the desktop and log out and log back in to get to that probably no even i'm not
[07:51] SPEAKER: crazy enough to do that i and i would say for the handheld stuff i was thinking about this as well
[07:58] SPEAKER: it's like when i dock my switch and i played on the tv sure it has the same graphical power as
[08:04] SPEAKER: handheld mode but there i'm usually accepting of it but i usually personally don't dock my steam
[08:12] SPEAKER: deck i would much rather boot up my gaming pc for a better experience so like i don't know it's it's
[08:19] SPEAKER: weird i in the times that i would have wanted to like dock it the idea of having an egpu has been
[08:27] SPEAKER: like okay this is cool but that's a whole separate road we don't need to go down um and and just
[08:32] SPEAKER: before you write the angry letters in you can do multiple accounts on one steam deck now that is
[08:37] SPEAKER: the thing that they added last january so okay um yeah you click on the profile button in the top
[08:43] SPEAKER: right corner and it lets you log in as somebody else yeah nice okay so so switch to yeah like we
[08:50] SPEAKER: can finally stop following rumors yes because like the rumors all basically turned out to be true i
[08:55] SPEAKER: think we could have had this exact same conversation two months ago because like all the specs are
[08:59] SPEAKER: exactly what has been said for well probably six months now but now now we've got numbers
[09:05] SPEAKER: you know yeah like i'm but i'm you know i'm looking at a nintendo.com page with all these
[09:09] SPEAKER: numbers on them now so they're official i i did go back and look at an article published oh sure
[09:14] SPEAKER: this november 3rd 2023 by one richard ledbetter over at uh digital foundry big fan of those those
[09:22] SPEAKER: people over there and he did a deep dive into the uh the tegra t three no i'm sorry t 239 239
[09:31] SPEAKER: yeah yeah so the processor essentially he was laying out the the specs of that processor
[09:38] SPEAKER: back in 2023 and it does indeed have hdmi 2.1 support at the heart at the chipset level okay
[09:47] SPEAKER: so yeah maybe it's just nintendo not wanting to pay for the actual the rest of the hardware to
[09:53] SPEAKER: output it but i i guess we'll see yeah like i found some reddit threads breaking down like the
[09:57] SPEAKER: real tech display controller that's in the dock apparently i think that came out of some leaked
[10:01] SPEAKER: photos like people but there's no data sheet out there for that real tech chip so no people aren't
[10:05] SPEAKER: quite sure why i mean i think it's also a money thing maybe you know they're trying to cut costs
[10:11] SPEAKER: where they can they think most consumers are on the 4k 60 which i mean it's also again like that
[10:17] SPEAKER: right but like the switch one also just did some weird non-standard stuff right with both the
[10:20] SPEAKER: charging charging profile and the way that it handled video out so like who knows why nintendo
[10:26] SPEAKER: does different anything at a specs level well i will say though i mean if that if that is
[10:31] SPEAKER: something if they're doing some sort of weird magic to be able to dock it and seamlessly have
[10:36] SPEAKER: it pop up on a screen and charge at the same time i'm okay taking that sacrifice because i i do think
[10:43] SPEAKER: that is like super seamless and a really good experience yeah i i guess i'll i've got the since
[10:48] SPEAKER: we're talking about video output out of the dock i'll just read those specs now just to cover that
[10:52] SPEAKER: point um same you know same same dock setup as the original switch maximum of 4k at 60 frames
[10:59] SPEAKER: per second but it will do 120 hertz at 1080p and 1440p so like i think i'm probably okay giving up
[11:06] SPEAKER: 4k 120 1440 120 is not bad on a big tv and like no games are going to be coming anywhere close to 4k
[11:12] SPEAKER: 120 anyway yeah i mean it's the 120 maybe like i don't understand why they do 120 on the handheld
[11:19] SPEAKER: not that like it's just such a weird it's a weird like it's a weird separation and it feels kind of
[11:25] SPEAKER: arbitrary in a very nintendo-y way well it's doing 128 1080p so that's the handheld mode and the
[11:32] SPEAKER: screw you know big screen mode so yeah i'm more confused about why they have a fan in the dock
[11:38] SPEAKER: oh yes because yeah they're like i have actually tried to use uh solutions where like i even
[11:44] SPEAKER: strapped a peltier cooler on the back of my steam deck to try to wick away some heat but i mean
[11:49] SPEAKER: you're at that point you're you're trying to dissipate heat through layers of plastic and it
[11:54] SPEAKER: just it doesn't make sense uh so yeah i saw i saw a lot of reaction to to the fan because they show
[12:01] SPEAKER: the fan in that stream you know which is like kind of pretty un-nintendo like to show the inners of
[12:07] SPEAKER: that thing at all but yeah i saw a bunch of people going like oh the dock helps cool your switch but
[12:11] SPEAKER: like yeah what is the thermal conductivity through the housing of a console is like basically nothing
[12:16] SPEAKER: right so it has to be cooling something in the dock right yeah something in that chipset whether
[12:21] SPEAKER: it charging or maybe that's where some of the upscaling is happening i i'm yeah it just feels
[12:28] SPEAKER: really weird to have a fan in there and i know there's people worrying about like the the speed
[12:35] SPEAKER: the size of it how loud it's going to be because that's obviously people don't want to interject
[12:42] SPEAKER: more noise into their room but i also don't feel like it's going to be
[12:46] SPEAKER: that intrusive especially if it's at a dock under your tv like yeah yeah i mean i i don't
[12:51] SPEAKER: hear the switch fan at all the switch one fan like even handheld even handheld let alone across the
[12:56] SPEAKER: room and in the dock mode like so like i i can't imagine a fan and then the dock is going to have
[13:01] SPEAKER: that much more noise either i'm going to tell you my my launch switch fan got noisy over time i
[13:07] SPEAKER: ended up having to replace it because it started making a weird buzzing rattling noise after a
[13:11] SPEAKER: while but wait you didn't just buy the old version when it came out you know my wife got the old
[13:16] SPEAKER: version came out because you know i'm a good husband i didn't give her my old crappy one when
[13:21] SPEAKER: the good one came out um you're probably right actually like there was they wouldn't need the
[13:26] SPEAKER: type of upscaling hardware that could do higher than 1080p and a handheld that only does 1080p
[13:30] SPEAKER: right so like maybe you're right that that extra scaling stuff is in the dock because that's the
[13:35] SPEAKER: only place you would ever actually use it right i i think it's more likely that they're rendering
[13:39] SPEAKER: a higher resolution to be upscaled when you're in 4k mode and it's going to generate more heat
[13:45] SPEAKER: but but like getting that interface right it's going to be a challenge for them i don't i don't
[13:49] SPEAKER: know like that's a that's a weird one because i have a lot of questions that can be solved by me
[13:54] SPEAKER: spending about 30 minutes with this and we're not going to know until we get 30 minutes with it so
[13:58] SPEAKER: yeah yeah um you know like the the dock output and the screen are the two things that nintendo
[14:04] SPEAKER: does give you specs on like forget forget any actual details about the the nvidia chip but the
[14:10] SPEAKER: screen itself i was pleasantly surprised by the screen i don't know about you guys but
[14:15] SPEAKER: like the the the size of the screen had been reported for weeks but not necessarily all the
[14:19] SPEAKER: specs that they would deliver it's a 7.9 inch screen now versus 6.2 inches on the launch switch
[14:26] SPEAKER: one uh 1080p and six what the oled was what 6.8 i think it's seven six point nine somewhere in the
[14:33] SPEAKER: like six point eight to seven range so yeah oled switch was kind of halfway between launch switch
[14:38] SPEAKER: and uh and switch two yeah it's the same size glass is the launch switch but the actual usable
[14:45] SPEAKER: screen area is larger on the oled yeah so this is basically one one point seven inches bigger than
[14:50] SPEAKER: the launch switch 1080p uh hdr 10 uh and and vrr 120 hertz variable refresh rate so that was
[15:00] SPEAKER: probably the one i i didn't really expect hdr or 120 hertz like nintendo is just so conservative
[15:06] SPEAKER: about specs since i don't know like what was the last like gamecube was the last competitive piece
[15:13] SPEAKER: of hardware they put out with its contemporaries you know ever since then yeah they've lagged so
[15:17] SPEAKER: far behind standards that i would not have expected at hdr or high refresh let alone vrr so like i'm
[15:23] SPEAKER: i'm pretty pleasantly surprised by the screen in that context not necessarily compared to the pc
[15:29] SPEAKER: handhelds on the market oh and i i was arguing with one will smith uh at gdc that nintendo
[15:37] SPEAKER: definitely wasn't going to come out and push any sort of boundaries like that i i yeah i i think
[15:43] SPEAKER: number one we are seeing kind of like a new era of nintendo where they are willing to maybe get out
[15:49] SPEAKER: and talk about some things sure i wish they would get out and talk about more but they definitely
[15:54] SPEAKER: talked about more than i expected to uh and to have like that little mario animation of the
[16:00] SPEAKER: 120 hertz you know like way more marios the other or like even the the pixel like the 720p were 1080p
[16:08] SPEAKER: they had the little white between the pixels on mario's face and i was like oh that that's kind of
[16:12] SPEAKER: cute uh it was it was very much one of those things of like oh that's i wonder how nintendo
[16:17] SPEAKER: thinks of you know very nerdy hardware spec kind of stuff like that number two so the yes i was
[16:28] SPEAKER: i was pleasantly surprised by these seemingly high-end specs for sure i mean other than the
[16:33] SPEAKER: the fact that it's not oled which doesn't surprise me they i think everyone has it right that they're
[16:40] SPEAKER: ready to sell you another one in a couple years and i'm ready to buy one in another couple years
[16:44] SPEAKER: so yeah no one of the hardware sorry to jump in but i read they had a round table at the new york
[16:49] SPEAKER: event they did for for a lot of press and one of the hardware guys was asked you know why didn't
[16:54] SPEAKER: you go oled of course he didn't come out and say hey we want to sell you an oled switch 2 in three
[16:58] SPEAKER: years which i'm sure they do but he also said there have been a lot of advances in lcd's since
[17:03] SPEAKER: we shipped the switch one so we felt comfortable going back like i wonder what he means by that
[17:08] SPEAKER: like there couldn't be any kind of like local dimming in a screen this small right or mini led
[17:13] SPEAKER: or something like that does that work at screens of this size i yeah not that i know of so yeah
[17:23] SPEAKER: the thing the thing that i thought of because i was like to me i thought they were gonna stick
[17:29] SPEAKER: with 720p the steam deck is at 800p so you know whatever essentially the same kind of thing like
[17:36] SPEAKER: it while it is nice to have higher resolutions on windows handhelds like even me like i i don't
[17:43] SPEAKER: think you need like i think the bare minimum is 720p 800p that kind of stuff and so them pushing
[17:50] SPEAKER: to 1080p is surprising and then yeah i thought maybe at the outset like a 90 hertz kind of like
[17:57] SPEAKER: the steam deck oled because i feel like depending on the game you're playing yeah you're probably
[18:02] SPEAKER: not pushing 120 hertz even at 1080p on a lot of these experiences so that to have all these
[18:09] SPEAKER: things thrown out there i was like wow that's awesome they're really shooting for the moon
[18:12] SPEAKER: and i was like wait this is nintendo they're probably not shooting for the moon i bet that
[18:18] SPEAKER: we're finally at some sort of economy of scale for that type of panel where they said hey you know
[18:23] SPEAKER: what we look at at 720p lcd uh or we look at you know oled versions and they're like well actually
[18:32] SPEAKER: you know what the economy of scale doesn't work front on either of those yet but the economy of
[18:36] SPEAKER: scale works here so let's go ahead and do it so i doubt the nintendo people were like yeah we should
[18:42] SPEAKER: really push for the moon here i bet they were just like okay what's what's going to be the most cost
[18:46] SPEAKER: effective one that's going to last us for another eight years okay let's do that one yeah yeah i
[18:51] SPEAKER: think you're almost certainly right because it's a node it's a new likes to make money on their
[18:54] SPEAKER: hardware they don't sell things at a loss or even a break even the the one place that the lcd's have
[19:00] SPEAKER: exceeded oleds in the last few years years is brightness right yeah for sure so we talked about
[19:05] SPEAKER: on nextlander a lot of the oleds in order to get close to the lcd levels of brightness you're
[19:09] SPEAKER: seeing now are like double stacking oled displays so you have two panels and and obviously that adds
[19:15] SPEAKER: to the cost whereas with an lcd you can just put a brighter backlight on and get more juice
[19:21] SPEAKER: i i almost wonder like this is probably a no but i almost wonder if they have shot themselves in the
[19:27] SPEAKER: foot a little bit with the quality of the screen because when the oled model does come along if
[19:32] SPEAKER: you've already got a high refresh high resolution hdr screen on your current switch like i think an
[19:38] SPEAKER: oled model will still sell because like oled quote unquote is a is a like prized marketing term these
[19:44] SPEAKER: days you know what i mean like people i think a lot of people will buy an oled switch to sight
[19:47] SPEAKER: unseen they don't even need to see that it looks better right you're raising your hand like i would
[19:52] SPEAKER: consider it too but but like like you said like modern lcd's look pretty damn good now so like
[19:58] SPEAKER: i wonder if some people are going to look at this thing in two or three years and be like you know
[20:01] SPEAKER: this still looks really good i'm just gonna stick with my launch one yeah and actually i guess i
[20:06] SPEAKER: didn't hear any because like you mentioned there was a an event in new york where people got to get
[20:13] SPEAKER: their hands on it yeah brad nobody from nextlander went to that oh that's not why alex was out okay
[20:19] SPEAKER: yeah i so now that i'm thinking about the coverage i didn't hear anybody specifically talk about the
[20:25] SPEAKER: screen quality and like oh is it as bad as that launch the switch which i mean to be fair it
[20:31] SPEAKER: wasn't as bad i think the steam deck the steam deck launch lcd was even worse than the the nintendo
[20:38] SPEAKER: switch launch lcd but the oled version was a huge upgrade um but yeah i feel like it's it's it's
[20:46] SPEAKER: probably good enough like i feel like people probably would have tried to pick that thing
[20:50] SPEAKER: apart if they were there or who knows it was the first time putting their hands on it so maybe
[20:55] SPEAKER: you just first impression wasn't about that it was about the games or the experience or whatever and
[21:00] SPEAKER: it's not really until we get it home in our hands that we can be like hey you know what this lcd is
[21:05] SPEAKER: it's fine yeah yeah well you know i mean the majority of the games press is focused on
[21:10] SPEAKER: game content and not uh true definitely not hardware specs or even really like hardware
[21:17] SPEAKER: from a more perceptual standpoint i guess i would say you know like even even like the
[21:21] SPEAKER: you know people kind of talk about look and feel a little bit but like the you know there's a reason
[21:25] SPEAKER: that the kind of digital foundries of the world have peeled off into this kind of subcategory
[21:29] SPEAKER: of coverage i think so it's i think it was just a lot more mainstream like games focused coverage
[21:34] SPEAKER: coming out of that first event true well i i i didn't realize till morning this morning when
[21:40] SPEAKER: we were sitting here looking at the the the notes for this episode that when they talked about vrr
[21:48] SPEAKER: they're talking about g-sync right yeah i don't know well like i mean this is an immediate product
[21:54] SPEAKER: so like why not like i can't imagine it's going to be free sync or some proprietary thing it's
[22:01] SPEAKER: probably g-sync right i guess it could just be vrr though right for for for from nintendo's
[22:07] SPEAKER: standpoint i really probably depends on how much it would have added to the cost i don't know
[22:11] SPEAKER: because i mean i know at the like dawn of g-sync it was a lot of extra hardware you needed to run
[22:15] SPEAKER: that maybe maybe at this point it's cheaper so i totally forgot over on nvidia's blog which they
[22:20] SPEAKER: do have some real basic stuff they do have a point here that says very variable refresh rate via
[22:26] SPEAKER: nvidia g-sync in handheld mode wow so it is an actual g-sync panel so they don't they don't say
[22:33] SPEAKER: specifically what level of g-sync because if you don't know there's actually three levels of g-sync
[22:38] SPEAKER: uh g-sync ultimate which requires hardware okay g-sync uh which depends on the panel i believe
[22:46] SPEAKER: it can be hardware or not and then g-sync compatible which that's a lot of cheaper panels
[22:52] SPEAKER: it just means nvidia went through the rigor rigorous testing to say hey you know what this is a
[22:57] SPEAKER: a free sync panel or a vrr panel but they give their stamp of approval
[23:01] SPEAKER: and it's g-sync compatible in this case i bet it's just g-sync compatible i i don't know i mean
[23:07] SPEAKER: i i guess yeah the g-sync the mid-level the one that where most of the monitor the g-sync monitors
[23:12] SPEAKER: live does require a processor and the ultimate is the one that has the latency stuff for the
[23:19] SPEAKER: for the reflex um uh the reflex uh uh latency measurement right yeah and i i don't remember in
[23:27] SPEAKER: this this full article that i mentioned earlier by the by richard uh covering the the t239 uh
[23:35] SPEAKER: great number uh i don't remember that him specifying that it had some sort of like
[23:44] SPEAKER: hardware-based g-sync inside of the the chipset itself because i think that's still like a
[23:49] SPEAKER: separate chip like a uh so it would have to be like an added cost that that's why like it makes
[23:55] SPEAKER: me feel like it's probably g-sync compatible that they worked with nintendo to say hey you know what
[24:00] SPEAKER: you source the good panel we'll put a little compatible stamp on it but also if there's an
[24:06] SPEAKER: soc the nvidia could put the timing the timing chip the g-sync requires in the soc as well
[24:12] SPEAKER: because they know exactly what's going in this box true yeah either way that that dawned on me
[24:18] SPEAKER: this is probably the first windows-based handheld i mean that i can think of that has g-sync
[24:25] SPEAKER: compatibility in it well this isn't a windows-based handheld though i'm sorry i'm sorry
[24:30] SPEAKER: you're right there are no windows-based handhelds that have g-sync compatibility that i can think of
[24:36] SPEAKER: yeah there are not shaking your heads yeah i'm just sitting here resisting i did do a little
[24:41] SPEAKER: looking around what os this might be running i mean nobody knows yet but
[24:45] SPEAKER: because i'm the kind of weirdo that is obsessed with what kinds of operating systems each console
[24:50] SPEAKER: is running what do you think it's b uh what's up you think it's b yeah yeah the switch too runs
[24:56] SPEAKER: bos for sure yeah john louis gas a is coming out of retirement um think of all the videos you can
[25:03] SPEAKER: run at the same time on this thing it's going to be amazing there there's some like very
[25:07] SPEAKER: circumstantial evidence that the first switch runs some version of three of free bsd but it's unknown
[25:13] SPEAKER: because kind of makes stations playstations also run free bsd for what it's worth so
[25:18] SPEAKER: but we don't we don't have to get into that here the thing i'm the most excited about on the screen
[25:22] SPEAKER: i mean all of it really like high res hdr is nice but it's it's the 120 hertz it's the high refresh
[25:27] SPEAKER: and vrr not because i think we're going to get a lot of 120 hertz games but because of all the
[25:33] SPEAKER: options it opens up for developers over time to massage performance on a platform that is going
[25:38] SPEAKER: to be on the market for a long time i mean look at how look at how much the switch one struggled
[25:42] SPEAKER: with performance particularly in handheld mode over time so having support for like a good 40
[25:48] SPEAKER: hertz mode on handheld i mean that's like that's like the thing on the steam deck i gather these
[25:52] SPEAKER: days like tons of people play games at 40 hertz now right because oh i love 40 hertz right yeah
[25:57] SPEAKER: smooth 40 man it's like i don't want to lose 40 i don't think i know and it's weird for people who
[26:03] SPEAKER: have not tried 40 hertz modes like it probably sounds weird for everybody to have regressed from
[26:07] SPEAKER: 60 to 40 and be excited about it but the difference in perceptual smoothness when you're playing it is
[26:15] SPEAKER: like so much more than you think it would be for something that's only 10 frames a second more than
[26:19] SPEAKER: 30. it's it's like i'm playing assassin's creed shadows on the ps5 pro at 40 hertz right now and
[26:24] SPEAKER: it's like it might as well be 60 from my brain's like pleasure centers lighting up at how it feels
[26:30] SPEAKER: to play because it's just as good almost do you leave motion blur on at 40 hertz brad like you
[26:36] SPEAKER: mean in in the game settings game yeah i typically leave everything at default unless it really bugs
[26:41] SPEAKER: me um so i think i think it's probably still warranted there but but but just generally
[26:48] SPEAKER: whether whether developers are going to be doing locked 40 hertz or using the vr
[26:52] SPEAKER: like either way like like the more tools they have to keep games running well as this hardware
[26:56] SPEAKER: ages i think the better like this kind of makes me actually maybe want to play more games in
[27:01] SPEAKER: handheld mode going forward and that's why there's still so many questions for me because the vr range
[27:07] SPEAKER: if it is g-sync compatible and at least comport um according to the nvidia website uh g-sync
[27:14] SPEAKER: compatibility is can be anywhere from 30 to 60 up to 120 that's right okay yeah like if it's if it's
[27:22] SPEAKER: the v if the vr range for this is 60 to 120 then our our locked 40 is you know or unlocked 40 or
[27:29] SPEAKER: whatever is not gonna benefit as much um because there's no way that this is the vr range is from
[27:37] SPEAKER: one to 120 right that that is that requires the extra hardware i bet they wouldn't want to pay for
[27:44] SPEAKER: that's a really good point i had forgotten like a lot of the like free sync implementations are
[27:48] SPEAKER: like from like 48 or 60 up right um yeah most of the windows based handhelds are all like 48
[27:54] SPEAKER: uh to whatever it is uh the the other note i want to put in here is that there's been confusion
[28:01] SPEAKER: around hdr because a lot of people like eh you know hdr and lcd why would they do that
[28:07] SPEAKER: is it going to be dimming zones how are they going to implement it and so the thing is i
[28:14] SPEAKER: actually have a lenovo legion go s here uh this the windows based version is on the market the
[28:20] SPEAKER: steam os one is going to come to market and this i wonder if this is almost the exact same screen
[28:27] SPEAKER: this is this is taller aspect ratio so it's it's 1920 by 1200 but it has all the the same set specs
[28:35] SPEAKER: vr or uh it is lcd it's not oled um it and it actually does have hdr support but the hdr support
[28:45] SPEAKER: is only for video so i was i'm wondering if that's a caveat that people aren't or nvidia or i'm sorry
[28:53] SPEAKER: nintendo is not coming out and specifying is that hey yes the screen can do hdr but it can only do
[28:59] SPEAKER: it in video playback mode like if you're watching a trailer or youtube or something that has hdr
[29:05] SPEAKER: support but the games themselves won't be in hdr i wonder which chipset is that is that an amd
[29:12] SPEAKER: chipset yeah yeah this one is amd yeah yeah i i would think a lot of that would come down so
[29:18] SPEAKER: yeah the hardware support for doing real-time hdr well in in video i mean uh nintendo would
[29:24] SPEAKER: have to would have said if it was if it was only in video mode they would have said something they
[29:28] SPEAKER: wouldn't have acted like it's presented as hey this is an hdr screen yeah so i so i i don't know
[29:35] SPEAKER: i i was trying because i was trying to think of like all the handhelds i have in my possession
[29:40] SPEAKER: i was like okay well what lines up specs wise the closest and it is this lenovo legion go s i mean
[29:46] SPEAKER: lenovo is one of the biggest manufacturers out there they do have you know the capacity to buy
[29:52] SPEAKER: a lot of these kind of kinds of panels so i don't understand why that's only in video mode that's
[29:57] SPEAKER: really weird i mean and maybe i i'm missing something on how to enable it in in games but
[30:04] SPEAKER: yeah i mean if you go to the windows settings it just says hey hdr is only available in video not
[30:11] SPEAKER: normal playback weird so yeah weird uh but once again it's one of those things we got to get our
[30:18] SPEAKER: hands on and see um so and in true nintendo fashion they didn't talk about like total system
[30:25] SPEAKER: power or anything like that um you know what is it the steam deck operates at like 15 watts max i
[30:32] SPEAKER: think and some of the windows the chip is 15 watts the usually the full system you know can be around
[30:39] SPEAKER: 18 depending yeah and and some of the other windows handhelds go up to about 40 or something
[30:45] SPEAKER: ridiculous it depends yeah yeah uh but actually uh some of the youtubers that i follow like uh the
[30:51] SPEAKER: fox retro game core they they did a little bit of math because you on if if you do the math which
[30:58] SPEAKER: i'm not good at math so i'm not going to say how to do the math you have to go watch their videos
[31:02] SPEAKER: uh they are estimating based off of what is being put out here that they're saying the total system
[31:09] SPEAKER: is going to pull 10 watts uh so based off of yeah based off whatever they have on their website and
[31:15] SPEAKER: then nintendo saying the estimate of battery ranges i think it was like two to six hours
[31:20] SPEAKER: or whatever they were saying hey okay you know with with this times this divided by this i don't
[31:26] SPEAKER: know what math it is they're saying that it looks like the whole system is going to pull 10 watts
[31:31] SPEAKER: which that is low that is it's either a super efficient chip uh or you know they're not going
[31:37] SPEAKER: to be pushing it that hard or the thing is is that while we might know the actual like capacity of
[31:43] SPEAKER: the battery maybe nintendo's estimates are being uh or are off not that they're misleading but
[31:50] SPEAKER: they're like oh you know you only get like two hours under heavy gaming but actually maybe in
[31:56] SPEAKER: reality you get like 2.5 which might change that math a little bit maybe bump it up to like 12 uh
[32:03] SPEAKER: 12 watts you know i i'm not quite sure because i mean either way 10 watts is real low yeah although
[32:10] SPEAKER: i think that's pretty consistent with the switch one right like that's i think that that's low by
[32:13] SPEAKER: pc handheld standards right but i yeah yeah switch one was also around 10. i don't remember but i do
[32:21] SPEAKER: remember that math changed a little bit with the oled switch uh that was the other reason why i was
[32:26] SPEAKER: excited about the oled switches because it did get better battery life um there were some uh leaked
[32:33] SPEAKER: photos of prototypes a few weeks ago around january it looks like like tech power up ran some
[32:38] SPEAKER: some photos and people did some eyeballing of size of size of the nvidia chip and it looks like they
[32:43] SPEAKER: they may be a five nanometer i soc in this thing down from like the the that version of nvidia to
[32:50] SPEAKER: tigra or tegra i've asked this question so many times that i could never i say tegra
[32:54] SPEAKER: tegra i think they always said but yeah really i like tegra sounds better to me anyway that
[33:00] SPEAKER: version of the tegra originally shipped on eight nanometers whenever they started shipping it in
[33:04] SPEAKER: development boards a couple years ago but it looks like they may have gotten it down to five
[33:10] SPEAKER: for the switch too so hopefully that helps with with battery life a little bit
[33:14] SPEAKER: and it's seven it's a seven sorry it's uh it's seven cores i think three a 78 p cores and four
[33:23] SPEAKER: a 55 e cores uh eight cores eight cores i don't i don't know how arm does its heterogeneous cores
[33:31] SPEAKER: though oh one one hp core well it's up to the vendor they can do whatever they want or well
[33:36] SPEAKER: what i mean is they have a three tiered thing here apparently they've got there's one arm cortex x1
[33:41] SPEAKER: hp core like high performance core i assume and then there's three a 78 p cores which like the a
[33:46] SPEAKER: 78 is way more common that's like what's in the raspberry pi 4 for example and then for cortex
[33:52] SPEAKER: a 55 e cores anyway anyway i don't know what that that one hp core it must be the super high powered
[33:57] SPEAKER: core it's it's probably for a single threaded stuff yeah would be my guess it's interesting
[34:03] SPEAKER: right i like i i'm really curious to see the nvidia release said that they have uh tensor cores
[34:09] SPEAKER: and uh and uh like dlss support and yeah and ray tracing hardware ray tracing support yeah but like
[34:17] SPEAKER: that that was the extent of it like their language is literally tensor cores boost ai power graphics
[34:22] SPEAKER: rt cores enhance in-game realism like even nvidia didn't come out with any real numbers here
[34:27] SPEAKER: well and uh digital foundry did some some of their own real quick dirty looking at the
[34:34] SPEAKER: the presentations and they they didn't see any evidence of dlss being used in any of the games
[34:40] SPEAKER: they showed off for launch uh which is which is weird i mean well yeah it's weird and it's not
[34:45] SPEAKER: because i like nintendo typically doesn't worry about any sort of anti-aliasing like that's always
[34:52] SPEAKER: been their thing is that they they just give you those clean raw edges anti-aliasing is not a huge
[34:57] SPEAKER: deal for them so i wouldn't expect first party titles to lean heavily on dlss but third party
[35:04] SPEAKER: titles theoretically could so who knows maybe the third party games they showed off were from builds
[35:09] SPEAKER: that didn't have final dlss yeah uh in there i i'm not quite sure either way yeah that is another
[35:15] SPEAKER: huge question mark of like okay when is that going to be used uh i just don't know yeah there there
[35:20] SPEAKER: was some some reporting in the last couple weeks that nintendo has been very conservative about
[35:24] SPEAKER: sending out dev kits for this platform for maybe obvious reasons so maybe yeah developers just
[35:30] SPEAKER: haven't had a lot of time to get up to speed i think i saw digital foundry saying that cyberpunk
[35:34] SPEAKER: 2077 the footage that they saw of it was running at 540p not all of it it was it fluctuated maybe
[35:42] SPEAKER: as low as the lowest counts for 540p so presumably upscaling is going to be a big deal on this thing
[35:49] SPEAKER: going forward for sure yeah i think it just yeah definitely depends on what kind of upscaling this
[35:54] SPEAKER: is ampere technology so i mean we're not going to get dlss 4 uh dlss 3 would be the cap um and then
[36:03] SPEAKER: yeah the amount of like rt units in there that are going to do anything other than real basic
[36:09] SPEAKER: heavy lifting uh i i'm not gonna expect this thing to be in a ray tracing machine no i want look i
[36:16] SPEAKER: want the super mario 64 switch 2 version to have the metal full environment reflections in metal
[36:23] SPEAKER: mario that's all i that's all i want fully reflective metal mario real time real time
[36:28] SPEAKER: metal mario one frame a second yes uh do you want to talk about storage real quick um yeah the the
[36:35] SPEAKER: it's got 256 gig of internal storage which i think is what what the switch one launched with 64 i
[36:42] SPEAKER: want to say no that was 32 man was it was it yeah the original switch was right you're right watch
[36:48] SPEAKER: that's why launch was there's like one game that's right yeah he's like zelda and maybe a couple of
[36:53] SPEAKER: smaller downloads it was horrible that's right i totally forgot about that um they described the
[36:58] SPEAKER: internal storage as ufs which i'm not 100 sure well i did look up the spec for well there's two
[37:07] SPEAKER: things on the tech power up yes uh the tech power up leak from january 2nd uh stated that the
[37:14] SPEAKER: console uses 256 gig flash storage at ufs 3.1 uh so the the 256 number was true so you would think
[37:24] SPEAKER: that based on this leak it is ufs 3.1 and then i also did look at the spec for micro sd i'm sorry
[37:32] SPEAKER: micro sd express yes the new external protocol uh and that is that is also ufs 3 uh and up as
[37:40] SPEAKER: well so yeah that all kind of lines up yeah i'm not i'm not familiar with ufs is that one of those
[37:45] SPEAKER: like external storage speed standards or something it's not just external yeah i think it just is like
[37:52] SPEAKER: a speed standard for like how much throughput you can get okay either way like it seems like
[37:57] SPEAKER: they're putting a priority on that i wouldn't say load times on the switch are horrible they're not
[38:03] SPEAKER: well they're not the worst out there but like this is seems like it's going to be a lot better
[38:08] SPEAKER: yeah yeah i think i saw the the slowest version of the sd cards that this supports again the
[38:14] SPEAKER: standard is micro sd express like they're tiered they're like three tiers of speed but the slowest
[38:18] SPEAKER: one is just under a gigabyte a second which i assume i think that's the one that this uses so
[38:23] SPEAKER: like that's not exactly in viennese speeds but still pretty robust and like you know sure enough
[38:28] SPEAKER: their flagship launch game is a an open world mario kart game you know so like maybe maybe more
[38:33] SPEAKER: more streaming asset type scenarios are going to be more common well it's time around if you would
[38:38] SPEAKER: assume that they were developing this in tandem and knowing that mario this new mario kart was
[38:44] SPEAKER: going to be at launch then yeah that they were probably like oh crap we need really fast storage
[38:50] SPEAKER: to be able to handle this open world look look in the old days your mario kart karts could only be
[38:56] SPEAKER: 250 cc's because the cards the cards couldn't generate frames faster than than the than the
[39:02] SPEAKER: cards could drive now 300 cc's no problem that's how fast the storage is going man 500 cc they
[39:09] SPEAKER: gotta have room for the pro right the the switch switch to max the 14 inch version in three years
[39:16] SPEAKER: yeah i think the micro express stuff is interesting as well it's gonna it's good
[39:22] SPEAKER: like the fact that those cards cap out at 256 256 gigs is is tough it's it's a little distressing
[39:29] SPEAKER: and i have to assume bigger ones will be coming relatively soon the the the sandisk sorry the
[39:34] SPEAKER: sandisk when i looked up it's 60 bucks for a 256 gig right now which is like you know it's not
[39:39] SPEAKER: super cheap but it's also at least not like catastrophically expensive it's not i was looking
[39:44] SPEAKER: over a game spot game spot.com and they were listing out some cards and they do have uh
[39:50] SPEAKER: lexar versions and game stop versions i don't know who's manufacturing these game stop
[39:55] SPEAKER: micro sd express cards but they go up to one terabyte are they on the market now though uh
[40:02] SPEAKER: yeah i'm well i mean you can you can hit the link and it just says temporarily out of stock so i
[40:06] SPEAKER: don't know if it's been released or it hasn't been released or whatnot but okay the the sandisk one
[40:11] SPEAKER: was only 128 or 256 but yeah hopefully oh i see yes two days ago this happened since the next
[40:16] SPEAKER: lander podcast here's a here's a press release lexar ships the world's first one terabyte
[40:22] SPEAKER: micro sd express card so okay so that that's good there will be bigger options probably at launch
[40:27] SPEAKER: then yeah and either way i mean the this this is probably like hopefully overkill uh i mean this is
[40:37] SPEAKER: fast uh i for for our camera that we have at the studio for still photography i use a cf express
[40:45] SPEAKER: card and i actually didn't even know this was a spec until this nintendo thing came out i was like
[40:51] SPEAKER: wow okay so i had never heard of micro sd express until the morning this got announced so i mean i
[40:58] SPEAKER: think the the goal is to make it more like more like actual storage more like make the the cards
[41:04] SPEAKER: more like an ssd though right and and it seems like it manages stuff like right wearing and all
[41:08] SPEAKER: that a little bit better or at least gives a higher connection speed to the system hopefully
[41:13] SPEAKER: i wonder i wonder how much confusion there will be though for people who are not super technically
[41:17] SPEAKER: inclined because these are physically backwards compatible with sd card slots so how many people
[41:23] SPEAKER: are just going to move their card over from their old switch and then like i love the fact that it
[41:27] SPEAKER: doesn't just work it has a mushroom on it it's going to be fine right yeah clearly you need
[41:31] SPEAKER: mushroom cards not mario cards well yeah and i want to see the nintendo like pop-up screen to
[41:37] SPEAKER: be like oh hey you inserted a card you can't use it's gonna have some cute little picture on it you
[41:42] SPEAKER: know like it's gonna fly in and throw a spiky ball at you exactly that cat from the from the we will
[41:49] SPEAKER: be there or the 3ds will be there and it'll be like hey man this card sucks go buy a new one
[41:54] SPEAKER: actually it'll just be tom nook going like this oh god making money let's see i mean there's there's
[42:03] SPEAKER: all i mean we could probably sit here for another two hours talking about all the stuff in this but
[42:06] SPEAKER: like from a tech perspective like the mouse any thoughts on the mouse it looks real uncomfortable
[42:11] SPEAKER: man yeah thumbs down adam's thumbs downing here i mean it's got kind of a vertical mouse look to it
[42:17] SPEAKER: you know like vertical mice are like kind of popular on pcs these days look i have a vertical
[42:21] SPEAKER: mouse on my desk right now this this does not look like any like i i i don't know where people
[42:28] SPEAKER: are going to be playing their switches that they're like oh man i gotta bust switch over
[42:32] SPEAKER: to mouse mode and then are not like running it on their knee or or like we're gonna get lap desks
[42:38] SPEAKER: out so we can play switch games the word out of that event from new york was people saying like
[42:42] SPEAKER: yes this will work on your couch which is what i guess the i think i noticed i mean it may not be
[42:47] SPEAKER: ideal but like the the the little sheath you know that you put over the the rail side or in this
[42:52] SPEAKER: case the magnet side of the joy con to like make it a whole controller it looks like from the photos
[42:57] SPEAKER: of that i saw it looks like there are teflon anti-anti-friction pads like you would have on
[43:03] SPEAKER: the bottom of a gaming mouse it looks like there are pads on those things to make it make it glide
[43:08] SPEAKER: like a proper mouse oh man i want to skepticism here and see i i think this is a nintendo style
[43:14] SPEAKER: gimmick well you know they needed something as a gimmick and i i nobody is going to require this
[43:21] SPEAKER: you can't have a game that's that's only mouse mold motive only so this is always going to be a
[43:26] SPEAKER: second kind of thing right uh the the basketball game i think is is uses it right mouse exclusively
[43:33] SPEAKER: i don't know about i don't know that exclusively it it it strongly implied that you're controlling
[43:39] SPEAKER: the wheelchair wheels and shooting by using the mouse mode well like they could put that on sticks
[43:43] SPEAKER: as well okay i mean either way i yeah i'm not going to use this this looks really stupid uh
[43:51] SPEAKER: and yeah i think it's a gimmick i think developers there'll be some games at launch and then it'll be
[43:56] SPEAKER: one of those gimmicks that nobody uses for the rest of the switch's life absolutely possible
[44:02] SPEAKER: and in fact probably likely i will give it a try for metroid prime 4 though yeah like that they
[44:08] SPEAKER: treehouse did a bunch of streams after the announcement over the next couple days
[44:12] SPEAKER: showing the games pretty extensively like if you want to see some like some just 20 minutes of
[44:16] SPEAKER: donkey kong bonanza or mario card like you can just go to their youtube channel there's like
[44:20] SPEAKER: actually a ton of footage of those games being played live now but the guy playing metroid had
[44:26] SPEAKER: a big old mouse mat on a table in front of him when they were about to cut over to the um to the
[44:31] SPEAKER: game and he had the controllers in mouse mode but then they never cut back to a camera feed of his
[44:36] SPEAKER: hands the whole time he was playing that game because i really wanted to see somebody's hands
[44:40] SPEAKER: in action yeah can you control the dpi is there a switch on it you know i just wanted to see some
[44:46] SPEAKER: action shots of what it's actually like to use that thing in like a high performance situation
[44:49] SPEAKER: but they did not show it well uh i mean look this is the natural evolution of nintendo bringing
[44:55] SPEAKER: gyro controls to the kids with splatoon the kids love gyro controls they they always want hey i
[45:02] SPEAKER: want hybrid modes i can control movement with my joystick and mouse to aim and it's a huge hassle
[45:10] SPEAKER: for everybody on unreal engine so thanks i i think i think this is just going to allow people to do
[45:15] SPEAKER: their taxes on a switch so oh gosh there you go the feedback from people who had hands-on was that
[45:26] SPEAKER: the magnetic magnetic joy con holders were pretty good right yeah i've seen like every comment i've
[45:33] SPEAKER: seen about the vat feature has been like pretty pretty enthusiastic like people going like oh
[45:39] SPEAKER: it feels like the the process of attaching the mag the joy cons with magnets feels way better
[45:43] SPEAKER: than you think like they attach in a way more sturdy way than the rails on the first switch
[45:48] SPEAKER: felt do they have that same sound though where it clicks in that i don't know that classic switch
[45:53] SPEAKER: i would be like out of the speaker i hope so that like that that sound is such a part of the switch
[45:58] SPEAKER: brand identity at this point if they don't have that i feel like that's like a that's because if
[46:02] SPEAKER: it doesn't do it naturally then they gotta add a little bit of this you're right they totally do
[46:07] SPEAKER: how many times did you guys put the little uh the little cover things on upside down
[46:13] SPEAKER: everything maybe the little like things i i use those a lot actually because i'll play like we
[46:21] SPEAKER: just uh went on a flight uh recently and my wife and i like to play mario kart on the plane and i
[46:28] SPEAKER: definitely need those extra little bumpers because without it it yeah can hurt buttons are unhittable
[46:34] SPEAKER: yeah yeah yeah um i think that's it for the switch huh yeah i think that might be it for like
[46:40] SPEAKER: kind of top line interesting tech hardware choices on this thing i'm i'm excited about it i i think
[46:47] SPEAKER: it looks like it's it's basically what i expected but it's like maybe 10 better than i expected
[46:52] SPEAKER: which again is mostly because of nintendo's very conservative nature about hardware design like it
[46:57] SPEAKER: feels it feels like it's not lacking anything i would have wanted out of a new switch for sure
[47:03] SPEAKER: yeah yeah no i'm i'm super excited i mean i'm gonna be excited for it anyway but yeah i i'm
[47:10] SPEAKER: excited for it i think it's gonna have some interesting stuff and yeah i i hope i hope
[47:16] SPEAKER: they made enough that uh i can get my hands on well you can pre-order on uh well hold on never
[47:23] SPEAKER: mind you're you're supposed to be able to pre-order on april 9th and then you could register interest
[47:28] SPEAKER: right now which i did yeah well did you see did you see the story this morning adam i know you've
[47:32] SPEAKER: been yeah no i yeah i saw that they yeah they're saying pre-orders are not going to start yet but
[47:37] SPEAKER: i still have my interest in i i assume they had priced some amount of tariffs into the announced
[47:44] SPEAKER: price but obviously not anywhere near as much as what landed i mean who knows they could be
[47:48] SPEAKER: building them on some uninhabited island someplace that has a really high tariff rate because uh
[47:53] SPEAKER: of our stupid government uh yeah anyway i don't know yeah where the well we don't need to get
[47:58] SPEAKER: with the price stuff let's move okay okay okay um well i think the big question is is this going to
[48:06] SPEAKER: push the windows based handhelds any further what does this mean for the windows side of things
[48:12] SPEAKER: because if this is now the new baseline then then what does that mean for the steam deck a lot of
[48:19] SPEAKER: people are like hey is there going to be a new steam deck coming are we hoping for a new steam
[48:24] SPEAKER: deck anytime soon and i could see nintendo people looking over at the steam deck and be like it's
[48:29] SPEAKER: only an 800p screen it's only got 90 hertz i mean look you're not gonna play mario on your on your
[48:36] SPEAKER: steam deck adam uh that's that's just the way it is it's not gonna the hardware is not fast enough
[48:40] SPEAKER: it turns out yeah there's definitely no way to play a mario game on a steam deck it's truly
[48:45] SPEAKER: impossible whatsoever uh how about playing mario on an xbox handheld wow maybe maybe maybe you're
[48:55] SPEAKER: saying nintendo's gonna buy microsoft yes that's what i'm saying definitely definitely definitely
[49:01] SPEAKER: nintendo has the capital to pull off something like that well what is it today is either today or
[49:06] SPEAKER: yesterday that we're recording this at microsoft turned 50 maybe that was their part of their
[49:09] SPEAKER: announcement right yeah it's today they're like hey to celebrate we're offloading the xbox division
[49:15] SPEAKER: and nintendo is going to buy it yeah that's right um yeah there there are there are these rumors
[49:20] SPEAKER: swirling like picking up a lot of steam actually a lot of them out of windows central reporting
[49:25] SPEAKER: recently about an xbox handheld due possibly this year it sounds like like the the gist of the rumor
[49:32] SPEAKER: is that there is an xbox handheld coming soon but that microsoft is not making it which is
[49:37] SPEAKER: like microsoft has got a long and storied hardware division so for them to not make a like an xbox
[49:43] SPEAKER: branded piece of hardware is unusual if not surprising if they made it it'd probably be arm
[49:49] SPEAKER: and it would have a bunch of ai nonsense that nobody's going to use so maybe getting somebody
[49:55] SPEAKER: who actually makes these is good copilot plus xbox handheld well actually i mean not to not
[49:59] SPEAKER: to put the card before the horse but so like like a lot of this reporting is coming from jez cordon
[50:03] SPEAKER: at windows central like i mentioned and he speculates at the end of their just kind of
[50:07] SPEAKER: big roundup everything we know piece he actually speculates that microsoft possibly will still
[50:12] SPEAKER: make their own handheld some years down the line it kind of sounds like maybe that might be tied
[50:17] SPEAKER: into the next console like the actual next xbox which is probably still another two three years
[50:22] SPEAKER: away um so i almost wonder i almost wonder if this third party xbox handheld initiative is a stop gap
[50:29] SPEAKER: to start like they you know they need to they need to plant a flag in this market that is becoming
[50:34] SPEAKER: like pretty hot right and like they need to get xbox branded hardware out in the handheld space
[50:38] SPEAKER: now and then maybe down the line the next xbox ties into a more like bespoke like maybe maybe
[50:46] SPEAKER: whatever they would be working on in the handheld space would be something that tied in much more
[50:49] SPEAKER: directly to whatever the next xbox is going to be like i do you think they'll use off-the-shelf
[50:54] SPEAKER: hardware i can't imagine they wouldn't work with amd to build a custom apu for well for for this
[51:00] SPEAKER: theoretical like next xbox handheld it would be probably more custom but i don't adam you tell me
[51:05] SPEAKER: i mean the it feels like the the different amd offerings in the windows handheld space are getting
[51:12] SPEAKER: good enough that they absolutely could use something off the shelf for this or whatever
[51:15] SPEAKER: this thing is that might be coming out this year right i think hot take this is all hui
[51:22] SPEAKER: i say i think we're we're reading way too much into these tea leaves i think this is just going
[51:28] SPEAKER: to be a rebrand like okay this is this is going to be this could be an asus rog ally and instead of
[51:36] SPEAKER: white what if it's black right and it's got it's got it's got an xbox button on it that is just
[51:42] SPEAKER: relabeled that they etched off the labeling right and they just put a little xbox button
[51:47] SPEAKER: um and that that's all it is because there is actually a lot of companies out there that work
[51:52] SPEAKER: with xbox to get xbox branded stuff 8bitdo i i have one of their uh retro keyboards right
[51:58] SPEAKER: here they make an xbox branded version of this yes which is xbox yeah like there's the other
[52:06] SPEAKER: keyboards i've seen yeah i don't like it either there's wait does it have like the og original
[52:10] SPEAKER: xbox font or is it styled it's styled after the hell yeah the first xbox um yeah the original
[52:16] SPEAKER: xbox uh it's like 20 bigger than any other keyboard for no reason that you can tell adequately yeah
[52:22] SPEAKER: and some of the keys are really small yeah so i i think you were 100 right i don't even think
[52:27] SPEAKER: it's likely i think you're absolutely right that this is just going to be pretty much an rog ally
[52:33] SPEAKER: but looking like an xbox the the thing that i think might be different here is i feel like i'm
[52:38] SPEAKER: not the only one that's been asking this but i've been asking for like two three years now since the
[52:42] SPEAKER: steam deck really blew up like where is the windows equivalent of steam os you know like you can run
[52:47] SPEAKER: windows on a steam deck or other handheld now but it's like kind of just windows right but like i'm
[52:53] SPEAKER: talking about i'm talking about a windows that would boot up to a nicely styled game launcher
[52:58] SPEAKER: that looks like it fits on a handheld screen it's got like handheld power optimizations and sleep
[53:03] SPEAKER: features and save suspend type integration you know like something that feels more bespokely
[53:09] SPEAKER: designed as a handheld gaming os like where is that windows you know and like i wonder if
[53:14] SPEAKER: that's what's going to launch in conjunction with this that they're waiting for an xbox branded
[53:20] SPEAKER: handheld to be on the market for there to be like a windows that feels like it's made for
[53:24] SPEAKER: handheld gaming you're shaking your head no no i don't think so i i mean it's hard because i've
[53:31] SPEAKER: heard of plenty of companies and i've asked them hey why are you getting in the handheld space
[53:36] SPEAKER: there's a lot of companies like yeah too many to name that i'm like why are you making a handheld
[53:42] SPEAKER: there can't be a huge market there can't be a lot of margin on this like why are you getting into
[53:47] SPEAKER: it and they're like well that's where the excitement is in pc gaming so we want to be there
[53:53] SPEAKER: i think the same thing applies for microsoft sure they probably want to be there because that is
[53:58] SPEAKER: where a lot of the excitement is but when windows is on billions of devices across the world and
[54:05] SPEAKER: you're talking about it you know maybe a handful of million people using handhelds uh then it's
[54:13] SPEAKER: like okay well why would we dedicate all this time and resources to diverting from windows 12 or
[54:19] SPEAKER: whatever to say hey we're gonna go make it a fork of of windows just for handhelds i just can't
[54:26] SPEAKER: imagine it that would make sense for them it seems like it would be better for them to like fix the
[54:34] SPEAKER: problems with windows that make handheld gaming on windows bad like hey what if there's a a
[54:41] SPEAKER: toggle in windows update that lets you get gaming like new gaming optimized drivers instead of like
[54:47] SPEAKER: the safe wiggle drivers right well let me let me stop you to be clear what i'm talking about is
[54:52] SPEAKER: basically just a ui refresh on top of windows i don't i'm not saying they need to go architect a
[54:56] SPEAKER: whole new handheld windows all i meant was like replace the desktop shell with something that is
[55:00] SPEAKER: like the steam os interface that you boot into you know like proper the same big picture is is
[55:05] SPEAKER: maybe a better comparison actually what you're talking about is windows windows 8 right where
[55:10] SPEAKER: they had kind of yeah you would boot into the tiles space area and then you were like oh if i
[55:14] SPEAKER: want to go to my desktop i just hit that desktop tile right i mean that's basically the kind of
[55:19] SPEAKER: thing i mean like under the hood this is still going to be windows in fact like that's the
[55:22] SPEAKER: competitive advantage here because like the one thing they could boast with this that steam os
[55:27] SPEAKER: can't is hey you can play fortnite like you can play valor and you can still play your kernel
[55:32] SPEAKER: anti-cheat style games that do not run in steam os on our handheld but like they need something
[55:38] SPEAKER: like the average person that just wants to play handheld games does not want to see a fucking
[55:41] SPEAKER: windows desktop with a mouse cursor on it when they turn on their windows handheld like it needs
[55:45] SPEAKER: to have a friendly controller centric interface on top of it and that's what i'm talking about
[55:49] SPEAKER: i don't mean like yeah no s under the hood i mean like where is the where is the gaming controller
[55:54] SPEAKER: oriented ui front end to go on top of windows to run on this thing like that's that's the only way
[56:00] SPEAKER: this initiative makes sense to me is if if they're really going to lean into their everything as an
[56:04] SPEAKER: xbox strategy like they need to they need a new unified like handheld and console interface that
[56:10] SPEAKER: can be the same across all devices the number of people who still still work at microsoft who are
[56:16] SPEAKER: there when they shut down media center and tablet editions which were the last times they did these
[56:20] SPEAKER: kind of like reskinned versions of windows for specific purposes probably hardly anybody's still
[56:26] SPEAKER: there so like they don't remember what a debacle they were and they're like i think it's it's not
[56:33] SPEAKER: out of the question i think it's more likely they'll revamp the xbox app to be like a top
[56:39] SPEAKER: level hey you can update your drivers here you can update the os here you can do all the windows
[56:44] SPEAKER: stuff that you need to do here with a joystick interface and and then that makes sense right
[56:49] SPEAKER: and is accessible to everybody else who wants it yeah that could be what i'm talking about
[56:54] SPEAKER: like if it's just the xbox app launches when you turn on the device or whatever that's fine but
[56:58] SPEAKER: it can't be it can't be the desktop is what i'm saying like you can't be looking at desktop icons
[57:02] SPEAKER: and a mouse cursor on an xbox handheld like people are just not going to accept that yeah i mean most
[57:08] SPEAKER: of these don't do that by default anyway most of them have some sort of vendor thing that launches
[57:14] SPEAKER: yeah so that's by default right i think the bigger problem is that you can well you can hook into
[57:21] SPEAKER: other platforms from whatever front end that these companies have and say hey say say microsoft there
[57:28] SPEAKER: is evidence tom warren over at the verge reported this uh was it march 20th that there they had some
[57:34] SPEAKER: sort of ui uh that indicated a steam game in the xbox app on windows like just being shown right
[57:43] SPEAKER: yeah but i don't think it's still going to have that same problem where you might have integration
[57:47] SPEAKER: into that front end but you still are going to have to go to the steam app to log in download
[57:53] SPEAKER: the game uh you know just get some of that that stuff enabled and ready yeah that's probably
[57:59] SPEAKER: known you can have that overlay so yeah and also that's a separate team a team that makes an
[58:05] SPEAKER: overlay for windows to log into a handheld is i think would be different than the team that's
[58:12] SPEAKER: working on the xbox app to be that thing if that makes sense that might be true but i i'm really
[58:18] SPEAKER: i'm really taking a lot of cues from how hard they are leaning into this everything is an xbox
[58:22] SPEAKER: campaign and where that's going with regard to the next console that's coming out and i really feel
[58:27] SPEAKER: like they if they're not doing this they should be doing this that they need to be working on some
[58:32] SPEAKER: kind of unified unified ui and user experience across everything that is apparently now in xbox
[58:37] SPEAKER: for for them to for them to really realize this supposed dream that their ecosystem is everywhere
[58:42] SPEAKER: you want to play a game the weird thing about all of this though is that none of this comes with
[58:47] SPEAKER: hey you can play your xbox games on this oh yeah yeah yes that's we'd super buried the lead on what
[58:53] SPEAKER: this story is apparently setting up which is that this will not play xbox games quote unquote like
[58:59] SPEAKER: the xbox skews of games you have been buying on consoles since the xbox one will not run on this
[59:06] SPEAKER: this is a windows handheld it's just an xbox branded windows handheld so it'll play it would
[59:10] SPEAKER: play any game that is like play anywhere that you bought on an xbox but also has a windows store
[59:15] SPEAKER: pc version yeah not play trying to think of like like rise son of rome right or something
[59:26] SPEAKER: you kind of do have to go that far back though because like so many like most
[59:30] SPEAKER: or maybe not most but a lot of the tentpole xbox releases have microsoft store versions as well
[59:35] SPEAKER: these days so you do have to go right like you do you do have to go a ways back to think of xbox only
[59:40] SPEAKER: games that that never came to microsoft's pc so i was gonna say all of their game pass deals since
[59:47] SPEAKER: they rolled out the ultimate stuff with the cross with you know the xbox and windows versions have
[59:54] SPEAKER: included play anywhere for the with a handful of exceptions yeah and all their first party stuff
[1:00:00] SPEAKER: for almost a decade at this point and that's what i mean i think they've been seeding the ground for
[1:00:05] SPEAKER: this reality for years now that like even even even even if this thing technically only runs
[1:00:09] SPEAKER: windows games and not xbox games from the console like there's functionally not going to be a lot of
[1:00:14] SPEAKER: difference going forward because they are making sure that so many new games run on both platforms
[1:00:19] SPEAKER: but you can't play like your xbox 360 back like cotor on this thing right i mean unless maybe
[1:00:25] SPEAKER: they port that you know like that there's no reason they couldn't make that stuff work outside
[1:00:30] SPEAKER: of like legal restrictions from contractual stuff probably like technically they certainly could
[1:00:35] SPEAKER: bring that 360 compatibility stuff over i think it's it's much more likely that they make it part
[1:00:39] SPEAKER: of your game pass slash yeah yeah whatever cloud play subscription yeah anyway i don't know i feel
[1:00:46] SPEAKER: like they've got interesting opportunities around whatever a an xbox handheld looks like in the next
[1:00:52] SPEAKER: year or two if they if they go that far but we'll see i'll say that they they are probably seeing
[1:01:00] SPEAKER: the imminent launch of steam os versions of these handles and saying well crap we need to have
[1:01:06] SPEAKER: something that indicates what ours is yeah because the lonobo legion go s is a perfect example where
[1:01:11] SPEAKER: they've got two identical devices one is cheaper than the other one says steam os i guess the color
[1:01:19] SPEAKER: is different too for the steam os version but instead of being like oh do you want to buy the
[1:01:23] SPEAKER: steam os version or the non-steam os version they're like oh do you want to buy the steam
[1:01:27] SPEAKER: version or the steam os version or the xbox version right and then the xbox version is
[1:01:33] SPEAKER: actually just windows could that be an easier sell to somebody at best buy who maybe was like oh i
[1:01:39] SPEAKER: don't want windows 11 they're like oh this is just an xbox right because everything's an xbox i'm
[1:01:44] SPEAKER: going to tell you if they sell this and you can't play your xbox games on it people are going to be
[1:01:49] SPEAKER: mad returns yeah maybe i mean how many of those games are there though like i said you know are
[1:01:55] SPEAKER: people trying to play dead rising 3 on this thing probably not man i love dead rising 3 though that's
[1:02:00] SPEAKER: okay it was all right i'm doing a dip into the steam deck stuff just a little bit yeah we we can
[1:02:06] SPEAKER: i mean i feel like it isn't the story there that there isn't much of a story like it's just been
[1:02:11] SPEAKER: kind of like steady as she goes for the steam deck lately right i mean the big the big thing is
[1:02:16] SPEAKER: the rise of steam os on non-valve hardware yeah yeah and also like this is a little bit tangential
[1:02:24] SPEAKER: but there's been talk for like months now that val's is going to do a proper new steam os desktop
[1:02:31] SPEAKER: release i don't know if they've have they ever actually talked about that or is that adams
[1:02:35] SPEAKER: crossing his fingers like i don't know if they've ever i ever actually come out and said that or is
[1:02:39] SPEAKER: that just something people are inferring well the the standalone thing that you should be able to
[1:02:45] SPEAKER: put on any handheld or any laptop or desktop i think is probably in that same family i think
[1:02:51] SPEAKER: it's just more like okay have did they work with the vendor to get it approved when i uh was able
[1:02:57] SPEAKER: to talk with the guys over at valve uh when i met with lenovo at ces that was their thing they're
[1:03:04] SPEAKER: like hey we we want to work with select partners make sure that the experience like all the button
[1:03:09] SPEAKER: mapping all that kind of stuff works by default uh but they'll have an option for steam os that
[1:03:15] SPEAKER: you can just roll your own which i mean you you actually can do right now they have that it's not
[1:03:20] SPEAKER: the same thing it's not yeah i think what you're looking for sorry yeah i mean this is all downstream
[1:03:26] SPEAKER: of everybody hates windows now like that's i mean i'm sure you guys notice like the the groundswell
[1:03:30] SPEAKER: of like directed ire at windows these days is just getting worse and worse and like people are like
[1:03:36] SPEAKER: trying to jump ship you know i think it's certain nerd communities are maybe overrepresented here
[1:03:44] SPEAKER: i've heard it's the year of the linux uh somebody keeps saying that over on the phone i don't know
[1:03:49] SPEAKER: there's a there's a lot of gnashing of teeth about windows out there anyway you see a lot of people
[1:03:53] SPEAKER: going like oh i'd love to move to linux and just tell windows to fuck itself but i want steam os
[1:03:58] SPEAKER: like there are people that don't want to deal with something like bazite that they've never heard of
[1:04:02] SPEAKER: but they would trust a release from valve and so i don't know i i think um my guess is that for
[1:04:10] SPEAKER: the foreseeable future it's going to be hey you can put this on certain handhelds and if you want
[1:04:15] SPEAKER: to have a more desktopy experience bazite's going to be your way to go right right because like
[1:04:19] SPEAKER: support on nvidia is still pretty thorny for that sort of thing so it's getting better but but it's
[1:04:24] SPEAKER: still there's some janky stuff there yeah i mean i've installed an nvidia drivers on two distros
[1:04:30] SPEAKER: recently it's still pretty rough yeah that's that's that's a bummer yeah because i'm excited
[1:04:35] SPEAKER: to try it on laptop but yeah if that's how the bazite people can differentiate themselves say
[1:04:41] SPEAKER: hey you know what steam os is here you're gonna be able to do it on on most of the handhelds but
[1:04:45] SPEAKER: bazite decides to go off in the direction of okay we'll do something that's more laptop and desktop
[1:04:50] SPEAKER: centric that would be super cool yeah i'd be done yeah there are definitely distros that are
[1:04:55] SPEAKER: smoothing that stuff over anyway i didn't mean to divert from actual steam deck handheld well my
[1:05:00] SPEAKER: question is because i don't i don't believe that the there's a steam deck 2 anywhere this year and
[1:05:08] SPEAKER: i i personally would be super surprised even next year either but that that might not rule out a
[1:05:15] SPEAKER: refresh another refresh though right could could they come out and be like hey you know what we
[1:05:21] SPEAKER: bumped the specs of the oled version from 90 to 120 uh or or hey you know what now we're going
[1:05:27] SPEAKER: to give you an option for a higher higher pixel density panel uh you know it's essentially the
[1:05:35] SPEAKER: same thing but just some upgrades here and there yeah i could see that will was will was a you that
[1:05:41] SPEAKER: said on the next liner podcast so something to the effect of like one steam deck per console
[1:05:45] SPEAKER: generation i i feel like that's the thing they're signaling that that's what they're signaling that
[1:05:50] SPEAKER: they're working on is that there'll be one hardware it makes sense because a lot of the value is the
[1:05:55] SPEAKER: stuff like the shader compilation that happens that they do and then they put them up in the
[1:06:00] SPEAKER: servers and you just downloaded the compiled shaders for your hardware and uh for whichever
[1:06:05] SPEAKER: version of the drivers you have so so you're like you you don't have shader compilation waits on
[1:06:11] SPEAKER: steam deck steam deck games for the most part because valve handles that i i'm curious how
[1:06:16] SPEAKER: they're going to handle that when there's new hardware SKUs from Lenovo and other people as
[1:06:19] SPEAKER: well if they're going to do they're taking on that server side stuff uh and how that that's going to
[1:06:24] SPEAKER: go that's a good question but while i agree with you i don't think that rules out refreshes right
[1:06:30] SPEAKER: if they do one steam deck per generation i think we could see maybe one more refresh out of this
[1:06:37] SPEAKER: original steam deck i think they're going to do more colors honestly i think we'll see uh
[1:06:41] SPEAKER: atomic purple i think we're going to see some spice maybe a i don't want to say gamecube orange
[1:06:48] SPEAKER: but i know people who are very into that color transparent anybody yeah i mean i i have my
[1:06:53] SPEAKER: transparent uh limited edition i love it um yeah i i totally i mean i agree with both of you i
[1:06:59] SPEAKER: think absolutely they could they could rev incidental specs on yeah like screen and stuff
[1:07:04] SPEAKER: like that but i think what will meant is like a steam deck two will probably wait until the
[1:07:08] SPEAKER: next generation of consoles which actually did the steam deck one really only come out three years
[1:07:13] SPEAKER: ago uh-huh that's crazy to me that's it feels like it's been on the it's like it feels it's
[1:07:18] SPEAKER: been like it's been a fact of video games for like this entire generation so like it kind of
[1:07:23] SPEAKER: has been though right but it's the fact that it's only three years old seems crazy because it just
[1:07:28] SPEAKER: feels like a bedrock part of how people play games now but but but like it's it's it you're
[1:07:33] SPEAKER: tying it to this generation of consoles because the consoles weren't really readily available until
[1:07:38] SPEAKER: after it was it was out right yeah like i bought an xbox series s in 2022 i bought a
[1:07:45] SPEAKER: playstation 5 in like late 2021 um they were hard to get early on because of the pandemic stuff
[1:07:52] SPEAKER: right yeah so i mean in that context you absolutely could see if if the consoles come out in 27 like
[1:07:58] SPEAKER: seems to be possible at this point like that a steam deck in 28 or something like that i mean
[1:08:04] SPEAKER: that's about a proper life cycle for the first steam deck five six years i think makes sense
[1:08:09] SPEAKER: like it makes sense for them to to like like their whole model look man say what you about valve but
[1:08:17] SPEAKER: but they are let the market do the work and their whole goal with this thing is to to do the hard
[1:08:23] SPEAKER: work so the the other oems they're doing the hard software work up front so that the other vendors
[1:08:30] SPEAKER: can do the hard hardware work long term and and they're going to keep selling them because like
[1:08:34] SPEAKER: the numbers i was hearing out of um the people at gdc are that they're estimating like six million
[1:08:40] SPEAKER: plus units shipped now on the steam deck side um and and like that's not an inconsequential amount
[1:08:48] SPEAKER: of money for valve but compared to 30 of the entire pc games market it's it's pretty small
[1:08:54] SPEAKER: so like if they can if they can kick start this market with the steam deck and then do new
[1:09:00] SPEAKER: hardware every few every once a generation and let asus and lenovo and acer and all the other folks
[1:09:05] SPEAKER: fill in the gaps they're going to absolutely do that yeah and even though i like to collect a
[1:09:10] SPEAKER: bunch uh like i still feel like most people are going to invest in one and they're going to hold
[1:09:14] SPEAKER: on to it for many years so like the up like the potential buyer who bought a steam deck lcd maybe
[1:09:21] SPEAKER: didn't want to spring for an oled is probably still going to be okay with it for a year or two
[1:09:26] SPEAKER: longer until the next one i feel like this time last year you and i went through kind of hands-on
[1:09:32] SPEAKER: like giving me some hands-on experience with a lot of the higher performing handhelds the the the
[1:09:38] SPEAKER: asus uh rgl ax and the and the lenovo one some other stuff and like it was nice but the way i
[1:09:46] SPEAKER: used my steam deck it wasn't impactful at all right like i if i'm going to play something
[1:09:51] SPEAKER: that performance matters i often am streaming from my pc to the steam deck and if i'm playing some
[1:09:56] SPEAKER: some like deep rock galactic uh their vampire survivors game it literally runs great on the
[1:10:02] SPEAKER: steam deck so like perf isn't as much of an issue the screen size doesn't matter as much i'm just
[1:10:08] SPEAKER: looking for a convenient way to play pc games it doesn't involve me sitting in my office for
[1:10:12] SPEAKER: another three hours a night yeah anything else on the windows side adam i know we're starting
[1:10:17] SPEAKER: to see lunar lake stuff shipping there but that's kind of the big the big thing i think right
[1:10:21] SPEAKER: yeah i do have a strix halo based tablet in a lot of people are like oh wow this is going to come
[1:10:29] SPEAKER: to handhelds sometime soon and i say no because what is strix halo adam sorry strix halo is there
[1:10:36] SPEAKER: uh ryzen ai 300 max oh i think that's the name something like that anyway that that's their new
[1:10:43] SPEAKER: apu that has a huge gpu i don't remember like depending on the skew it's either 32 or 40
[1:10:50] SPEAKER: compute units which is just massive compared to the other uh apus that are on the market
[1:10:55] SPEAKER: it's like their workstation apu right yeah it's like a work yeah like i think many pcs are kind of
[1:11:01] SPEAKER: where it's aiming towards and it's like really trying to take on like a mac mini uh kind of thing
[1:11:07] SPEAKER: this is in a tablet form so this is the asus rog flow z13 i i like i love the chip that is a
[1:11:15] SPEAKER: powerful chip but the form factor in this 13 inch tablet is just not doing anything for me and all
[1:11:22] SPEAKER: the all the handheld people that think that are it's going to come to handhelds which would be
[1:11:26] SPEAKER: really cool to have that much graphical horsepower in a handheld uh the operating range for this
[1:11:31] SPEAKER: t uh for the tdp is like 35 to 105 watts or something like that so like getting it in a
[1:11:37] SPEAKER: handheld it would just be stupid you yeah or it would just be like so constrained that it's not
[1:11:45] SPEAKER: actually that much better than any of the other apus on the market um so at ces amd did also
[1:11:53] SPEAKER: announce uh three three full z2 processors so the z2 go has already been released in the lenovo
[1:12:03] SPEAKER: legion go that i have here i'm sorry the lenovo legion go s that i have here um and a couple other
[1:12:10] SPEAKER: handhelds that have announced it uh but we have yet to see the z2 vanilla or the z2 extreme uh
[1:12:19] SPEAKER: even even lenovo for their z2 go i'm sorry for their lenovo legion go s they have two variants
[1:12:26] SPEAKER: of it the the go chip which is essentially not that much more powerful than the steam deck
[1:12:33] SPEAKER: and then rather than going the z2 for the upgraded chip they continue to to put in the z1 extreme
[1:12:40] SPEAKER: which is very interesting to me because that is a it's been around for a couple years it is
[1:12:46] SPEAKER: a really good chipset but it seems to be like it'll operate the same as the z2 vanilla so the
[1:12:52] SPEAKER: with a couple tweaks so that's a really weird messaging on their end to be like oh hey
[1:12:58] SPEAKER: go buy a lenovo legion go s uh do you want the z2 go or the z1 extreme well which one's better well
[1:13:05] SPEAKER: the z1 extreme is better well but the other one has a two in it so yeah it yeah so i i at least
[1:13:13] SPEAKER: as of right now i have not seen any major manufacturers or even any of those shins and
[1:13:17] SPEAKER: base companies announce anything with the z2 vanilla or z2 extreme so that's
[1:13:23] SPEAKER: a little odd for me i don't know if that's a supply chain issue maybe they're you know tsmc is
[1:13:30] SPEAKER: just cranking out other stuff for amd and they're not prioritizing it yet but either way the z1
[1:13:37] SPEAKER: extreme seems to be here at least through the end of this year so see this is the other opportunity
[1:13:42] SPEAKER: that microsoft has on top of unifying a gaming windows interface is just saying here's the xbox
[1:13:49] SPEAKER: handheld like you don't need to worry about which version of an apu is in here you know like that
[1:13:54] SPEAKER: like like you just said like that the market confusion around these different chips and
[1:13:59] SPEAKER: different models from all these different manufacturers starts to get pretty overwhelming
[1:14:04] SPEAKER: at some point but for microsoft to just come in and be like hey this is the xbox handheld this
[1:14:07] SPEAKER: is what we're supporting for the foreseeable future like that feels like like that clarity and
[1:14:12] SPEAKER: singular focus feels like it would be appealing for a lot of people yeah well i i hope it's not
[1:14:19] SPEAKER: if they do a singular device like that i hope it's not the z2 go because that is pretty
[1:14:24] SPEAKER: underwhelming right now like to get this brand new device and and this actually the legion go s is a
[1:14:31] SPEAKER: really nice device but that that z2 go chipset in there is just very underwhelming and yeah just not
[1:14:38] SPEAKER: much faster than a steam deck so like to invest in that right now would be a little short-sighted
[1:14:44] SPEAKER: i mean it depends on the game you're playing but also this thing they had to i think they
[1:14:48] SPEAKER: erased the price by 500 bucks so like it i'm sorry not 550 dollars uh not 500 500 would be a lot uh
[1:14:57] SPEAKER: so yeah i i don't know i think amd is trying to get cheaper chipsets out there to compete
[1:15:05] SPEAKER: closer with the steam deck and the steam os version of the legion go s is getting closer
[1:15:12] SPEAKER: but it's still they can't compete at that price i mean valve is just you know i i would love to
[1:15:19] SPEAKER: know if they take a like if they're at least breaking even with that hardware or if they're
[1:15:25] SPEAKER: like yeah you know what we'll sell a little loss for ever because we don't care we'll make it up in
[1:15:29] SPEAKER: software truly no one outside valve can know like i bet i bet that they have a number you know that
[1:15:36] SPEAKER: they know exactly what the attach rate is for every person who buys a steam deck how many games
[1:15:40] SPEAKER: they buy on the downhill side of that and i bet it is a substantial number of games probably probably
[1:15:48] SPEAKER: well i guess that's it for us then that's a good place to wrap it up uh adam patrick murray thank
[1:15:52] SPEAKER: you for coming by where can people find you uh i run video over a pc world you can either go to
[1:15:58] SPEAKER: youtube and search for pc world or if you want to listen to our pc hardware based podcast that will
[1:16:06] SPEAKER: is is has been on for a little bit then uh check out the podcast the full nerd uh not not because
[1:16:13] SPEAKER: we're like hungry nerds like because we're full we've got a lot of information i believe is the
[1:16:19] SPEAKER: is the thought and and uh it's uh it's it's uh it's found wherever find podcasts are found apple
[1:16:26] SPEAKER: google youtube deezer all the all the good podcast places yeah please hit us up over on deezer it's
[1:16:33] SPEAKER: our number one listen place i'm kidding that's a joke that'll do it for us this week thanks for
[1:16:40] SPEAKER: listening everybody as always brad and will made a tech pod is listener supported we wouldn't be
[1:16:44] SPEAKER: here without you the listeners and if you would like to find out how to support the show you can
[1:16:48] SPEAKER: go to patreon.com slash tech bod again that's patreon.com slash tech bod where for five dollars
[1:16:55] SPEAKER: five bucks that's it that's all we ask you get access to the discord you get access to the
[1:17:00] SPEAKER: patron exclusive episodes where brad talks about compiling his own kernel and no they're like not
[1:17:05] SPEAKER: compile my internal hooking uh like signing uefi bootloader images i didn't do that i've
[1:17:12] SPEAKER: already i've wrote a script to do it to automate the process yep nerd multiple doing this so much
[1:17:18] SPEAKER: that you have to write a script for it uh let's see talk about mounting windows storage spaces
[1:17:22] SPEAKER: in linux um butter fs for windows all sorts of nerd stuff butter fs windows some yes some
[1:17:29] SPEAKER: esoteric shit this week this month uh again it's patreon.com slash tech pod uh and as always we
[1:17:36] SPEAKER: want to thank all of our patrons but especially our executive producer tier patrons including
[1:17:41] SPEAKER: andrew slosky jordan lippett bunny themed twinkle twinkie david allen james kamek jason lee and
[1:17:50] SPEAKER: pantheon makers of the hs3 high speed 3d printer thanks all thank you all so much
[1:17:54] SPEAKER: adam thank you so much for coming by it's always a pleasure to see you sir
[1:17:58] SPEAKER: hey thanks uh i feel honored to be able to show up especially on my vacation yeah i was gonna say
[1:18:03] SPEAKER: you took time out of your time off to be on the podcast so the extra thank you am i ever truly
[1:18:08] SPEAKER: off yeah that's you know that's that's work that's a bigger question to address
[1:18:13] SPEAKER: hopping off all the time is what i say uh we will see you all next week thanks for listening
[1:18:18] SPEAKER: and as always please consider the environment before printing this podcast what if you want
[1:18:23] SPEAKER: to fax it no no faxes ever faxing is never the answer
