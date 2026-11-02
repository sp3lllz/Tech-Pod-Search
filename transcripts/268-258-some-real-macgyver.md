---
episode: 268
title: 258: Some Real MacGyver #$@!%
date: 2024-10-27
guests: none
duration: 1:30:30
---

[00:00] SPEAKER: so i plugged a smart plug that tracks power into my server's plug why would you do that to yourself
[00:06] SPEAKER: i was i was curious so we were talking at pc world the other day about small like nuk style
[00:13] SPEAKER: servers and i have this old b-link i think it's a 12th generation celeron back there right now which
[00:17] SPEAKER: is which i bought specifically because it's a real low power drive yeah it's like you know under load
[00:23] SPEAKER: it goes it goes fast enough it has quick sync for video but you can stream something on plex without
[00:28] SPEAKER: it busting up to like 100 watts like my old desktop pc would have right normal normally i would say and
[00:32] SPEAKER: this i definitely fit into this category that this is the type of thing you're better off not knowing
[00:36] SPEAKER: but you have made choices that at least give some reason for optimism yeah look i'm looking at i'm
[00:41] SPEAKER: looking down the barrel of a 500 dollar power bill every month now part of it is because well my god
[00:45] SPEAKER: it's also my car right okay sure so i'm not buying gas sure sure yeah that helps especially around
[00:51] SPEAKER: here as somebody we'll get into it on the main episode is somebody who pumped a lot of gas in
[00:55] SPEAKER: a different part of the country recently gas is very expensive in the bay area yeah but but so
[01:01] SPEAKER: anyway a big chunk of that is car that's fine i'm you know that's part of the deal still cheaper
[01:06] SPEAKER: than gas but i plugged in the the two smart plugs and i unfortunately i didn't have enough unused
[01:12] SPEAKER: ones so i stole them from like the christmas tree plug and one of the holiday lights that we put in
[01:18] SPEAKER: the front windows of the house plugs and didn't really think about the downstream consequences
[01:22] SPEAKER: of that when the server turned off midway through a movie um somebody clapped their hands and oops
[01:28] SPEAKER: plexed behind yeah hey it's time for the it's time for the for the holiday lights to turn off so all
[01:33] SPEAKER: everything turned off anyway i fixed i worked that out that's all better now but it's been interesting
[01:38] SPEAKER: because i was running it versus a 14th gen intel msi box to see like what the the idle draw was
[01:44] SPEAKER: on these on these things and that 12th gen celeron is the is the king that msi box is a little bit
[01:50] SPEAKER: more powerful it has a lot more cores but it still is like seven eight watts constant idle draw and
[01:58] SPEAKER: uh it goes up it goes up about the same place when you put it under load like none of these are real
[02:03] SPEAKER: high load servers they're like you know if somebody logs onto the minecraft server it spikes up for a
[02:08] SPEAKER: second and then comes back down to like two watts higher than it was before but but it's kind of
[02:13] SPEAKER: interesting because i have this dashboard in home assistant that i can look at that shows me how
[02:17] SPEAKER: much power the server is consuming at any moment now which is kind of fun so like here i'll share
[02:24] SPEAKER: i'll share my screen so you can see what i'm talking about oh look at that oh real time yeah
[02:28] SPEAKER: you get like a line graph of what the current consumption is based on what the server is doing
[02:34] SPEAKER: and like when somebody connects to plex it it boosts up and when somebody's off plex it comes
[02:37] SPEAKER: down and it's literally like a little real time like needle gauge like in a car or something you
[02:42] SPEAKER: just watch the needle going up and down well yeah and then there's also graphs over time that update
[02:47] SPEAKER: like every five or ten seconds it seems three to six seconds it seems like so you can get a good
[02:52] SPEAKER: idea of like how much consumption you're using per day and stuff like that it's it's it's it's not
[02:57] SPEAKER: something i realized they've done a lot of work on the power side of home assistant lately that
[03:01] SPEAKER: i hadn't really been paying attention to and it's it's pretty pretty good that's cool i mean that
[03:06] SPEAKER: that's the type of information that you should know but might not want to know i can i can tell
[03:10] SPEAKER: you i've got a ups here the closest i've ever gotten to this is i have a ups and i have just
[03:15] SPEAKER: looked at the ups readout with everything running on it and with my nas which is a 12 600k
[03:22] SPEAKER: my edge router and like two raspberry pies three raspberry pies now i'm doing like 75 to 80 watts
[03:31] SPEAKER: steadily well so it's worth mentioning i don't have the synology with the spinning disks okay
[03:36] SPEAKER: okay this is not your hard drives got it this is just the little server okay that makes me feel
[03:40] SPEAKER: better because i think hard drives add up i think the motors add up because it's spinning all the
[03:44] SPEAKER: time i think the raspberry pies are basically free right the raspberry pies are like a couple of watts
[03:49] SPEAKER: each yes yeah but but yeah i think the if i put the synology in here i think my number would go
[03:55] SPEAKER: up if i put my 24 point port switch in there i think the number would go up pretty significantly
[04:00] SPEAKER: too probably because it's also power over ethernetting like multiple other downstream
[04:05] SPEAKER: switches and i think even the access point but i'm not sure because i don't think any
[04:10] SPEAKER: of my switches are plugged into power maybe the one in my office is plugged into power
[04:14] SPEAKER: the rest of them were just powered over ethernet sure i i my frame of reference for like excessive
[04:18] SPEAKER: wattage still goes back to the the what did i get yelled at for leaving lights on about scale
[04:24] SPEAKER: from back in the day you know and i just think like okay that's just like one 60 watt light
[04:28] SPEAKER: bulb and a little bit extra right that how bad how bad could it be except brad now your 60 watt
[04:33] SPEAKER: light bulb pulls like three watts and uh yeah the the the bulbs are nothing and even the rgb bulbs
[04:41] SPEAKER: are nothing it's it's the future because i could just hear the voice now brad turn off that damn
[04:46] SPEAKER: server
[05:11] SPEAKER: so
[05:15] SPEAKER: welcome to brad and will made a tech pod i'm will i'm brad i'm back welcome back thank you
[05:21] SPEAKER: hi hello we have to be here we toured the tech pod regulars with norm and adam uh and wes over
[05:30] SPEAKER: the last several weeks but you've returned from your voyages yes thank you for holding it down
[05:34] SPEAKER: thank you to all those guys very much for for swinging through it was fun fun looking at the
[05:38] SPEAKER: episode list and just like oh it's a who's who of current and former you know it's it's fun because
[05:43] SPEAKER: when you're not like we've done 250 some episodes of this podcast at this point right there's like
[05:49] SPEAKER: three of them that i can listen to that i wasn't part of sure so i got to listen to the tech pod
[05:54] SPEAKER: when you had vinny on while i was while i was dealing with covid stuff um it's a it's always
[05:58] SPEAKER: a nice treat so yeah thanks yeah yeah thanks to them uh and i guess now we're here to talk about
[06:04] SPEAKER: some of the things i was doing while i was not on this podcast yeah i i am i am wildly curious so
[06:12] SPEAKER: we talked years and years ago after the california wildfires about like getting like a preparation
[06:21] SPEAKER: kit for disaster preparedness kit together and we did that based on like the california i think
[06:26] SPEAKER: there's a 72-hour california website that's like hey here's what you need to survive for the 72
[06:31] SPEAKER: hours after a disaster before you'll start seeing help from the outside like you have to you have to
[06:36] SPEAKER: you should assume that you're going to need to be relatively self-sufficient for up to 72 hours
[06:43] SPEAKER: which i think is a little optimistic given what we know now yeah well depends on you know depends on
[06:48] SPEAKER: the area depends on the scale of the disaster of course but but yes it absolutely could exceed 72
[06:52] SPEAKER: hours but but so you had a trip planned before helene hit yes and uh for the it ended up being
[07:01] SPEAKER: the week after helene uh yeah actually four days let's see so the storm it was funny talking to
[07:07] SPEAKER: neighbors like the kind of what the the range of the storm was was a little different depending on
[07:11] SPEAKER: who you talk to but it was like four solid days of rain but the the peak of the storm was um
[07:16] SPEAKER: uh thursday night friday morning when all the flooding happened when all the flooding happened
[07:20] SPEAKER: yeah so it was kind of in the friday morning when the news was coming out about how bad it had gotten
[07:24] SPEAKER: and our flight was tuesday morning so we we already had just a random trip we were just going
[07:29] SPEAKER: to see my parents for a week uh we already had that trip booked uh four days after the storm hit
[07:35] SPEAKER: so the kind of interesting thing about it from here was that there was a lot of news coming out
[07:42] SPEAKER: from like northeast eastern tennessee like southeastern tennessee and western more eastern
[07:49] SPEAKER: north carolina but there wasn't very much news coming out of ashville um that the greater
[07:55] SPEAKER: ashville area because 40 was like the interstates in and out of town were were closed and i feel
[08:03] SPEAKER: like there weren't a lot of and internet was down pretty much through the entire region so i feel
[08:08] SPEAKER: like there wasn't a lot of news like the news people couldn't get there to do the the their
[08:12] SPEAKER: coverage shots they were going to like elizabethton and irwin and and all these places around northeast
[08:17] SPEAKER: tennessee instead yeah and then if they could have gotten there there was like you said there
[08:20] SPEAKER: was essentially no connectivity in and out of there so getting unless you were maybe satellite
[08:25] SPEAKER: like some kind of satellite uplink probably would have been your only option at that point
[08:28] SPEAKER: those big satellite trucks couldn't couldn't manage the roads it seemed like so right um and then by
[08:34] SPEAKER: the time they could get up there the news cycle had passed and like it was just oh it's a massive
[08:40] SPEAKER: humanitarian problem in ashville good luck yeah for sure um so so just up front what i wanted to
[08:46] SPEAKER: do with this episode is like i got toward the end of the trip and realized how many different like
[08:50] SPEAKER: technical areas i had to touch uh as we were just trying to get by day to day from like electrical
[08:56] SPEAKER: and gas engine generator stuff uh to like house repair you know pulling up flooring mold remediation
[09:04] SPEAKER: type stuff like i kind of i kind of just want to like pick your brain about like your homeowner
[09:07] SPEAKER: knowledge oh god talk about electrical wiring and the way generators work and i mean i've got some
[09:13] SPEAKER: computing stuff in here too that i had to mess with like some um some disaster preparedness
[09:18] SPEAKER: stuff in terms of like portable solar lighting and battery packs and you know x y and z different
[09:24] SPEAKER: things that you know i came in contact with buying a generator like having to having to find and i
[09:30] SPEAKER: started to say like pick out a generator on short notice but like frankly what we were picking out
[09:36] SPEAKER: was whatever they had right like we didn't exactly have a lot of uh inventory to pick from uh when we
[09:41] SPEAKER: had to find a generator quickly so but you know there's there's just a bajillion different little
[09:45] SPEAKER: technical areas of expertise that i had to like try to figure out quickly and i thought it would
[09:49] SPEAKER: be kind of interesting to run a lot of that stuff down yeah i'm before we before we i i'm really
[09:54] SPEAKER: curious what it was like on the ground though like like i've read accounts of what it was like post
[09:59] SPEAKER: katrina and and like our friend friend of the show nathan edwards lived in houston when they
[10:04] SPEAKER: had the big floods uh probably 10 years ago now um and it's it's interesting talking to people who've
[10:12] SPEAKER: been in those situations because there's some stuff that's always different but then there's
[10:15] SPEAKER: also a lot of stuff that's always the same sure um so so um like it was just to be clear it was just
[10:23] SPEAKER: a ludicrous amount of rain in a really short period of time right yeah yeah so our i talked
[10:27] SPEAKER: to our neighbor up the hill who was a civil engineer by training so you can assume he's
[10:32] SPEAKER: probably relatively exacting about his measurements from tuesday night when the
[10:35] SPEAKER: rain started to friday morning after the storm had peaked like i said he measured 32 inches
[10:40] SPEAKER: that's incredible which is you know i've never owned a house i understand that's quite a bit of
[10:44] SPEAKER: water we we've had so when we've had big coastal storms here like sometimes we'll see an inch or
[10:50] SPEAKER: two an hour and that's that's a lot when we when our crawlspace flooded on new year's a few years
[10:56] SPEAKER: ago i can't remember exactly how much it was but it was it was it was fractions of 32 inches over
[11:02] SPEAKER: a two-day 3d you know 72 hour period sure yes it was a substantial amount of water got dumped i
[11:08] SPEAKER: understand i didn't i didn't get to spend a lot of time looking at kind of like the post-mortem on
[11:12] SPEAKER: the storm behavior but it sounds like it sounds like it migrated up from the gulf coast through
[11:17] SPEAKER: the southeast and then it just kind of parked itself over the western north carolina eastern
[11:20] SPEAKER: tennessee area for a while yeah it seems like it came up it carried a bunch of water up through
[11:25] SPEAKER: because like it went through atlanta and georgia and a little bit of south carolina and didn't do
[11:31] SPEAKER: a whole lot of like it was it was a bad storm but it wasn't like apocalyptic like this yeah and then
[11:36] SPEAKER: it seems like once it hit the mountains it didn't have enough juice to get over the mountains so it
[11:40] SPEAKER: just dumped all the water it was still carrying uh and the the my understanding i'm not a meteorologist
[11:46] SPEAKER: but my understanding is that because the air was warmer and because the gulf is warmer you're
[11:51] SPEAKER: getting more water in these storms now than you have in the past which is why you're seeing so
[11:56] SPEAKER: much more rain out of them which seems like it's going to be a significant problem to deal with
[12:01] SPEAKER: in years to come for that area um the whole southeast i mean the whole hurricane everywhere
[12:06] SPEAKER: yeah or even like hurricanes go all the way up the coast now you know like you've got
[12:10] SPEAKER: hurricanes hitting new york these days hurricanes there were hurricanes hitting northern europe
[12:14] SPEAKER: this year yeah it seems fine oh sure um let's see here where to go from there uh well can we talk
[12:22] SPEAKER: about the like i saw a bunch of places roads seem to have washed out yeah there was um there was a
[12:28] SPEAKER: spot about half a mile from my parents house although they had they had done road work putting
[12:33] SPEAKER: in some kind of culvert or something there so it was like kind of a temp pave job yeah but but
[12:37] SPEAKER: fully one entire lane just washed down into the gully uh so we were driving around that the whole
[12:42] SPEAKER: time we were there but um i i should say my i the area that this is the house i grew up in and that
[12:48] SPEAKER: area is about 30 minutes outside of ashville 45 depending on where you're going exactly um we were
[12:54] SPEAKER: incredibly lucky where we were because ashville proper and the areas north of ashville up toward
[13:00] SPEAKER: lake lake lore got it infinitely worse than we did um i don't know anybody that got hurt like i you
[13:06] SPEAKER: know everybody in the neighborhood had water in the house like my parents had close to a foot of
[13:10] SPEAKER: water flow through there but it was all just property damage i don't know anybody that got
[13:14] SPEAKER: hurt but i definitely know people who know people or sorry i know people who have friends who did
[13:19] SPEAKER: yeah if that makes sense like definitely would hear stories from people you talk to of like oh
[13:24] SPEAKER: i've got a friend up around on you know lives on the swan anoa or up around chimney rock or
[13:29] SPEAKER: something who has nothing left but the clothes they were wearing type stuff you know uh we you
[13:35] SPEAKER: heard a lot about a lot of missing people too yes my neighbor neighbor as by the time i left the
[13:39] SPEAKER: neighbor one of the neighbors had a friend up in ashville who still had not been found so
[13:43] SPEAKER: i'd i'd mostly say that you know hearts go out to those people and also to say like you know
[13:47] SPEAKER: things were not great where we're from structurally but like it was it could have
[13:50] SPEAKER: been so much worse for us so i i feel fortunate that it wasn't worse and i feel terrible for the
[13:56] SPEAKER: people up there that's uh but anyway yeah so like the flood waters had all receded by the time we
[14:01] SPEAKER: came in four days later like i'm sure up around ashville and you know where that dam was letting
[14:06] SPEAKER: off excess there was still plenty of standing water but it was mostly all drained out where
[14:10] SPEAKER: where we lived okay but it definitely coming in from the airport was an interesting scene
[14:15] SPEAKER: um i i did a fair amount of homework before we flew out there because it definitely had
[14:18] SPEAKER: some people reach out say was saying like hey i don't know if you should fly out there like
[14:22] SPEAKER: they're saying don't travel in western north carolina right now so i spent a lot of time on
[14:27] SPEAKER: like the north carolina dot has a good road closures website so i was like literally routing
[14:33] SPEAKER: and when we were lucky to be able to get from the airport we flew into the ashville airport
[14:37] SPEAKER: to my parents house without touching interstates yeah yeah um so i very intensively went through
[14:42] SPEAKER: looking at road closures and felt confident we could make it once we got in which we did like
[14:48] SPEAKER: my mom told me that they were seeing around their area they were just seeing like regular people
[14:52] SPEAKER: rolling up with chainsaws on like roads that had downed trees and just going in and like cutting
[14:57] SPEAKER: out enough to open up a lane type stuff before proper road crews were even getting out so like
[15:02] SPEAKER: people were pitching in making things passable so we got there the flight in was fine like we get
[15:08] SPEAKER: there and of course there are like military helicopters idling on the tarmac there's like
[15:12] SPEAKER: big supply trucks going back and forth um probably the craziest thing getting in was phones had mostly
[15:17] SPEAKER: been working the first two three days after the storm yeah for whatever reason the day that we
[15:23] SPEAKER: flew in at verizon at least i don't know about other carriers verizon was utterly non-existent
[15:28] SPEAKER: just down like my our phones once we hit the ground in ashville our phones were just pinging
[15:32] SPEAKER: sos on leak period like zero signal no matter where we went the thing that happened when we
[15:37] SPEAKER: had the power outages for like seven days here is that the towers were good for 48 hours maybe 30
[15:44] SPEAKER: maybe maybe a little bit longer and then the battery backups that they used ran out and then
[15:49] SPEAKER: everything went dark like i guess it probably was something like that but like we'd literally no
[15:53] SPEAKER: data no phone calls no nothing at the airport and there was it turned out to be fine but there was
[15:58] SPEAKER: kind of a miscommunication about when we were going to get in such that our ride didn't show
[16:02] SPEAKER: up for about 90 minutes after we got outside which is like it's fine like the weight was not really
[16:07] SPEAKER: the problem it was more the worry that something bad had happened yeah yeah because we had no way
[16:11] SPEAKER: to get any kind of word in or out so it was more just like okay you know we were kind of like
[16:17] SPEAKER: trying to absorb the conditions on the ground in general you know really just like what's what the
[16:20] SPEAKER: hell's going on out here like our family member has not shown up like i really hope something bad
[16:25] SPEAKER: is not going on it turned out like i said it was basically just a miscommunication so that was not
[16:29] SPEAKER: a big deal but it's it's it really is just really humbling to realize how dependent you are on
[16:34] SPEAKER: magical anywhere communication in your pocket once it goes away like it's really too bad
[16:39] SPEAKER: that kurt cobain didn't live long enough to see gps that's all i know yeah yeah um and you know
[16:44] SPEAKER: like even at the airport like we went and just talked to the ground transportation people because
[16:48] SPEAKER: we were just like oh let's maybe we can just get a car and go home and they were like hey our phones
[16:52] SPEAKER: don't work any better than yours too like there's not much we can do for you so again it's just like
[16:57] SPEAKER: we don't really have a lot of options you know you just are dependent on modern infrastructure
[17:00] SPEAKER: because that's what's there but like once that once that disappears you really is a serious
[17:05] SPEAKER: reality check it seems like there's like time moves differently right yeah for sure so driving
[17:12] SPEAKER: in i mean it was kind of what you would expect it was a lot of roads washed out like lines down
[17:15] SPEAKER: literally everywhere you looked like road signs blown over uh trees down on houses uh you name it
[17:23] SPEAKER: just kind of your standard flood damage that you would expect to see um so what were like once you
[17:30] SPEAKER: were there and settled in what were days like where like could you i assume you weren't driving
[17:34] SPEAKER: around a lot because i assume gas was fairly precious and like you probably didn't have
[17:39] SPEAKER: places like probably there wasn't places you could go to buy stuff if you needed to buy something
[17:43] SPEAKER: right yeah so um everybody in their neighborhood is on well water they're too far out to be on city
[17:48] SPEAKER: water um and so which means when the power is out there's no running water uh so before we got there
[17:54] SPEAKER: there was one neighbor that had a generator who had been running it every afternoon and letting
[17:58] SPEAKER: neighbors who did not have power come and fill up a bunch of you know like five gallon oh that's
[18:03] SPEAKER: beautiful containers so yeah i mean there was a tremendous amount of just like neighbors pulling
[18:07] SPEAKER: together mutual aid community helping itself type you know what i mean yeah generally over the course
[18:13] SPEAKER: of this whole thing but so like everybody was kind of getting water where they could so they could
[18:17] SPEAKER: flush toilets and stuff like that for people who don't know this is the thing i feel i've learned
[18:22] SPEAKER: that a bunch of people don't know if you fill the top tank of your toilet with water even if you
[18:26] SPEAKER: don't have water running in your house the toilet will flush when you push the lever yep it sure
[18:31] SPEAKER: will yeah and important knowledge they even had a system worked out where they had like here's
[18:35] SPEAKER: clean drinkable water here's toilet flush water oh that's that's awesome because like here because
[18:40] SPEAKER: these containers we're using we're not clean enough to want to drink out of but we can still
[18:44] SPEAKER: use the flush toilet type stuff it's yeah on fun watching like people's ingenuity come into effect
[18:49] SPEAKER: when stuff like this is going on but um did you have to boil the well water or do you so yes
[18:54] SPEAKER: they're well that was a topic of frequent debate around there because there was definitely there
[18:58] SPEAKER: was a boil order on for city water yeah and it was kind of like i said the most of the neighbors
[19:04] SPEAKER: around and us all we all kind of assumed that doesn't apply to well water because you would
[19:08] SPEAKER: assume the reservoirs typically are deep enough to not be affected by what's going on with
[19:12] SPEAKER: groundwater but maybe that's naive well i mean i would think so but like if your well had floods
[19:17] SPEAKER: then then you can get flood water into the head of the well which would be bad yeah i mean that's
[19:22] SPEAKER: the thing you know i guess it depends on where the well is being fed from yeah but uh at any rate we
[19:27] SPEAKER: did not boil the well water nobody got sick so it's probably fine probably okay um let us know
[19:33] SPEAKER: in the comments yes uh there was there was only one grocery store in town open when we got there
[19:39] SPEAKER: that's funny the one across the street that my parents usually go to uh the word around
[19:43] SPEAKER: town is it will never reopen because it's right on the bank of a creek oh wow and it like cut out
[19:49] SPEAKER: from underneath yeah like apparently the foundation is damaged enough that that building is probably
[19:53] SPEAKER: just toast that led to an interesting situation where all of their prescriptions are at the
[19:57] SPEAKER: pharmacy in that grocery store which is permanently closed and so no way to call the doctor huh
[20:03] SPEAKER: so we managed to get a call into the doctor's office for the prescription we needed but the
[20:07] SPEAKER: doctor was not there like course thankfully that turned out to be a kind of less essential
[20:12] SPEAKER: medication like the important ones were stocked okay at home so that was fine but but we just
[20:17] SPEAKER: kind of could not get that prescription filled for like a week and a half kind of makes me think
[20:22] SPEAKER: i should start keeping uh paper versions of the prescriptions just in case that was exactly what
[20:28] SPEAKER: happened that was that was one of the like endless tasks that came up and this is a little bit
[20:32] SPEAKER: technical i guess was like okay we got no power we barely have any phone signal to speak of at all
[20:38] SPEAKER: like the data barely works of course the internet is out we need to print these prescriptions how
[20:43] SPEAKER: are we going to do this you know like it was very much yeah because because i guess is that the
[20:47] SPEAKER: standard if you have paper printouts like credible printouts of your prescriptions and a different
[20:52] SPEAKER: pharmacy will take them that was my understanding there are different rules based on the controlled
[20:57] SPEAKER: ness of the substance so if you want like morphine then you have to go you have to have some special
[21:02] SPEAKER: but if you just need like your prescription antihistamines a piece of paper with a
[21:06] SPEAKER: credible looking doctor's signature won't work yeah okay so that's what we were trying to do but
[21:10] SPEAKER: but again that was that that got kind of challenging in itself um anyway so there was
[21:14] SPEAKER: there was only the one grocery store open they were cash only and they were only letting like
[21:18] SPEAKER: 50 people in at a time just because they were afraid there'd be a riot or because it was dark
[21:22] SPEAKER: i get no no the power was on in that part of town by the time we got there so i don't i guess yeah
[21:28] SPEAKER: i assumed it was just a let's manage the flow of people in and out like because some of the
[21:32] SPEAKER: inventory was pretty picked over as well maybe you don't want too many people like all fighting over
[21:36] SPEAKER: the last carton of eggs or whatever um but it was super chill it was very orderly i never ran into
[21:41] SPEAKER: any problems at all okay yeah i mean i assume there weren't people like hoarding toilet paper
[21:46] SPEAKER: or anything ridiculous like that not that i saw okay i mean there's definitely like i said there
[21:50] SPEAKER: was definitely like like eggs were not eggs and hot dogs for example were basically non-existent
[21:55] SPEAKER: for a few days ice was hard very hard to find i i assume that like because like there's i i
[22:02] SPEAKER: assume almost everybody there has a grill so you did a lot of grilling right a decent decent amount
[22:06] SPEAKER: of grilling yeah yeah um it was a lot of uh it was a lot of they have a gas stovetop so it was
[22:10] SPEAKER: a lot of just lighting the stovetop off of a off of a lighter and boiling a lot of stuff like i got
[22:15] SPEAKER: very used to just boiling a pot of water and making instant coffee in the morning okay for example to
[22:20] SPEAKER: the point that i can we continued doing that even if the power came back on um because it was just
[22:25] SPEAKER: faster but uh anyway um what i heard was that the gas station near us was limiting you to 30
[22:32] SPEAKER: gallons a day but we had no need for anywhere near that much okay uh we only had about 17 ish
[22:41] SPEAKER: gallons worth of empty cans okay um so uh we borrowed a generator from the neighbor
[22:48] SPEAKER: like miraculously it came to light that the the neighbor had a built-in like a full in-home
[22:53] SPEAKER: generator oh like a natural gas one or something yes and and a portable so he very graciously let
[22:58] SPEAKER: us borrow that portable um which we brought down and uh actually let's let's say the generator
[23:06] SPEAKER: sorry i'll get to that in more detail uh i'll finish talking about kind of conditions around
[23:12] SPEAKER: um so yeah like like groceries and gas were pretty limited uh like you said um i i did uh
[23:19] SPEAKER: i actually talked to you and you helped me come up with like a checklist of things to do before
[23:23] SPEAKER: i went out there one of them was get a lot of cash yeah which i'm glad i did because we were
[23:28] SPEAKER: kind of going on grocery runs basically every day oh that's good well because i assume you go and
[23:32] SPEAKER: get what they get what you can get right like what they had and also we didn't have a lot of capacity
[23:36] SPEAKER: to keep things cold so right so we were not buying a lot of perishables uh at one time uh we kind of
[23:42] SPEAKER: go like once every day or two or okay for that week we were there before the power came back on
[23:48] SPEAKER: but uh i'm very glad i had that cash um i i assume typically in this kind of situation
[23:55] SPEAKER: like there's a lot of it's one of the things i i i say love but power and utility companies
[24:02] SPEAKER: tend to pull together and send massive amounts of resources from unaffected areas to help people
[24:09] SPEAKER: where they're i assume there's road crews from like a bazillion different power companies there
[24:14] SPEAKER: that was that was one of the craziest like visuals of the whole trip like one of the most like i feel
[24:18] SPEAKER: like i'm in a disaster movie kind of things was like you could not go anywhere in that area
[24:22] SPEAKER: without like just constant giant white trucks uh either either the oversized pickup truck type of
[24:29] SPEAKER: utility vehicle or the full-on giant like tree truck you know with the big crane kind of traction
[24:34] SPEAKER: on the back because they were going around taking or getting up trees absolutely everywhere so like
[24:39] SPEAKER: there's there's a there's a school relatively close to us there's a there's a church you know
[24:44] SPEAKER: mile or two up the road and like you would constantly like anywhere with a giant parking lot
[24:48] SPEAKER: basically you would just see like 20 of those giant trucks like staging in the uh in the parking
[24:54] SPEAKER: lots constantly like day and night and they were just on the roads everywhere um i kind of i kind
[25:00] SPEAKER: of made a little game out of reading like the little side art on all the trucks to see where
[25:03] SPEAKER: they were from um because there were there were plenty of like local duke energy trucks around
[25:08] SPEAKER: but like i saw like a bunch of the crews near us were from kansas city missouri um i saw there
[25:13] SPEAKER: were some from up north um one of our neighbors one of our neighbors ran into a road crew from
[25:20] SPEAKER: montreal nearby i was gonna i was montreal is the classic example because when they had a big ice
[25:25] SPEAKER: storm in the 90s maybe late 80s even i remember like in bristol we sent power trucks up there to
[25:31] SPEAKER: help them out because they had to rerun basically the entire city's electrical because the ice
[25:36] SPEAKER: knocked down all the all the power lines and in the middle of winter when it was like the outside
[25:41] SPEAKER: will kill you right right yeah yeah so so like that neighbor actually speaks a little bit of
[25:45] SPEAKER: french so she like joked about trying to having fun trying to talk to them in her broken french
[25:51] SPEAKER: um but it was just it was everywhere i mean i could not believe the number of utility workers
[25:55] SPEAKER: all over the place and god bless them for for doing it yeah um i heard i heard at least a
[26:01] SPEAKER: couple of linemen got killed uh not not near us but somewhere up north of us like they're like
[26:07] SPEAKER: that that is hazardous work like doing all that electrical work that fast i'm sure
[26:11] SPEAKER: oh yeah in and of itself is very dangerous unstable roads and yes yeah anyway yeah i was
[26:18] SPEAKER: hearing weird i was hearing crazy stories from up um up around like the like the chimney rock area
[26:22] SPEAKER: like the places that absolutely just got kind of washed off the map like you're hearing stories
[26:26] SPEAKER: about they were having to helicopter in utility poles in places because they couldn't get any
[26:30] SPEAKER: trucks up to place them wow so they were literally like using helicopters to to lower and place the
[26:35] SPEAKER: utility poles into the ground like i heard they were using mules in places to get supplies up and
[26:40] SPEAKER: down in the mountainous areas i was going to say i saw some videos some people shared them the tech
[26:45] SPEAKER: pod channels of like a bike youtuber who was hauling stuff around on bikes up washed out roads
[26:51] SPEAKER: and and there was a lot of like mutual aid stuff coming out of restaurants and and places with
[26:58] SPEAKER: kitchens that still were working and like bookstores surprisingly um that that like you
[27:06] SPEAKER: would see people doing a morning meeting every day that was like hey what do people need help
[27:10] SPEAKER: with today and then they apply as much human power as they could to it yeah yeah i you were
[27:16] SPEAKER: seeing that everywhere i was i was really impressed just driving around town like all
[27:19] SPEAKER: over the place you'd see like free barbecue 1 p.m or like you know free hot meals at the elks lodge
[27:24] SPEAKER: just like different different like community organizations clubs whatever churches like all
[27:30] SPEAKER: over the place like just hey come get food no questions asked we never we never made use of
[27:34] SPEAKER: any of that stuff i kind of wonder in retrospect if maybe we should have more but i i just always
[27:38] SPEAKER: felt like there are probably there have to be people worse off than us that need it well yeah
[27:43] SPEAKER: that feels like one of those if you need it you need it right yeah um looking at duke power's
[27:49] SPEAKER: website there's still a thousand households in the greater ashville area it looks like that are that
[27:55] SPEAKER: are knocked out yeah so we we it's kind of a game day by day of text messages coming from them about
[28:02] SPEAKER: like at first it was like uh most customers by friday and then it was okay most customers by
[28:06] SPEAKER: sunday this was sunday being nine days after the storm somewhere around saturday or sunday my mom
[28:13] SPEAKER: got a text message from them saying basically saying your area is going to require significant
[28:18] SPEAKER: reconstruction something something which basically was like okay i guess we're not even in the sunday
[28:22] SPEAKER: group um yeah the the message on the affected people now is uh repairs underway where where
[28:33] SPEAKER: conditions allow disaster recovery and process is what it says in an estimated time of restoration
[28:39] SPEAKER: yeah so it ended up being 11 days for them before the power came back on and this is like we're at a
[28:44] SPEAKER: month now it's the 25th the storm hit on the on the 27th is when the power outage started according
[28:49] SPEAKER: to the website yes and there's still people without power apparently i don't know what the
[28:53] SPEAKER: state of like city water in ashville is that was still a mess by the time i left so um we got a uh
[29:01] SPEAKER: we got a note i was gonna save it for the q a episode but i'm gonna put it here we're gonna do
[29:05] SPEAKER: q a next week by the way yes yeah if anybody anybody wants to write in either questions about
[29:09] SPEAKER: all this stuff or also like some of the stuff we'll cover about like reinforcing your home or
[29:14] SPEAKER: electrical wiring or generators or any of that stuff that you have knowledge about i would love
[29:18] SPEAKER: to hear or if you want to share stories yeah stories as well sure um they said that the the
[29:25] SPEAKER: mapping they they pointed out some mapping resources that are really good in this kind
[29:29] SPEAKER: of situation because they're offline uh organic maps is an app that uh is basically open street
[29:35] SPEAKER: map but it's 100 offline so you can download whatever segments you want in advance uh and then
[29:40] SPEAKER: uh open inframap.org and the us energy mapping system both give complementary tools for figuring
[29:47] SPEAKER: out where your power is coming from and what like what the state of the grid is beyond what the power
[29:52] SPEAKER: company is telling you that's super useful to know because i definitely got hit by that when we went
[29:56] SPEAKER: out uh you know i used to live there but it's been 25 years i don't remember everything and and yeah
[30:01] SPEAKER: google maps not very reliable in a situation where the cellular data is not great i did try to use
[30:06] SPEAKER: the google maps feature to download kind of pre-cache the area data yeah which i had mixed
[30:11] SPEAKER: results with it seemed like it worked for a while but at some point it was trying to hit the cell
[30:15] SPEAKER: network again uh um cellmapper.net is the other thing that they recommended which tells you where
[30:21] SPEAKER: the cell towers are so interesting um and this is this is thomas sent this in okay so thanks thomas
[30:29] SPEAKER: yeah that's cool um let's see yeah i guess just quick stats so the power was out for 11 days it
[30:34] SPEAKER: was just about 14 like one magically magically about just about exactly two weeks after the
[30:41] SPEAKER: storm hit one day we got up and the phones just were working again they had the whole pots lines
[30:46] SPEAKER: no no no i mean like the cell phones just like like data data kind of worked off and on through
[30:52] SPEAKER: that time but it was very much like i have to go stand outside to actually make anything load was
[30:58] SPEAKER: it like you'll get a text message or something like you can get text messages kind of text
[31:02] SPEAKER: messages would come through here and there but it was very spotty like you get a lot of messages
[31:05] SPEAKER: failing to send and stuff like that um but like loading loading web pages was very difficult for
[31:11] SPEAKER: example that was that was the thing about twitter in the early days was that because you could use
[31:16] SPEAKER: 404.04 to send a message to twitter get messages from twitter you could actually get like it was a
[31:21] SPEAKER: really shockingly good distribution method for broad emergency comms for places that didn't have
[31:28] SPEAKER: like text messaging infrastructure set up like the power company um but that's gone now yeah
[31:33] SPEAKER: that was something i thought about constantly so um like i i had my phone on low battery mode like
[31:39] SPEAKER: constantly my iphone um which the way they handle things is kind of annoying because you can't turn
[31:44] SPEAKER: that on permanently basically when you charge the phone back up to what they consider a sufficient
[31:48] SPEAKER: level they will just turn low battery mode off yep and you have to keep going and turning it
[31:52] SPEAKER: back on again but that was that was getting me through an entire day with like very little
[31:56] SPEAKER: battery loss yeah um but it does make you think about how much just like invisible metadata is
[32:02] SPEAKER: going out along with messages these days how much like just from a sheer bytes perspective how much
[32:07] SPEAKER: data needs to go through just to send a simple message these days you know and in a situation
[32:10] SPEAKER: like this where the throughput is incredibly constrained like it does kind of get a little
[32:14] SPEAKER: frustrating when you think about like your twitter example you know it's like that's that's probably
[32:19] SPEAKER: a few hundred bytes at most to send the message right yeah it's a few hundred kilo yeah a couple
[32:24] SPEAKER: kilobytes probably yeah uh so like having having the amount of overhead that goes along with modern
[32:29] SPEAKER: communication that suddenly you can't turn off uh in a situation where you wish you could is kind of
[32:35] SPEAKER: frustrating but uh let's see uh that's pretty much it like the internet it was it was over two weeks
[32:40] SPEAKER: before the cable internet came back up and that was super spotty for another four or five days
[32:44] SPEAKER: after that kind of just going up and or coming up and going down over and over like there were
[32:49] SPEAKER: there were times when it was speed testing at less than a megabit per second which meant basically
[32:53] SPEAKER: nothing was working wow stuff like that so but those are just kind of the stats on how long
[32:57] SPEAKER: stuff took to come back so brad what about this experience has changed your disaster preparedness
[33:04] SPEAKER: plan for living in san francisco here i don't know i mean earthquakes are the biggest danger
[33:09] SPEAKER: here and those are very sporadic but it sure does make me want to keep some water around which is
[33:14] SPEAKER: the recommendation let's just say the water is a big thing we have um we have vinny vinny actually
[33:19] SPEAKER: recommended years ago i think i went camping with him once and he had this thing it's like a big
[33:23] SPEAKER: canvas like a sack that you can fill with water and then it you hang it up in a tree or on a post
[33:29] SPEAKER: or something and gravity feeds through a filter interesting just drain it out the bottom oh and
[33:34] SPEAKER: it's good for i i don't know if it's good for like flood like i probably wouldn't drink flood water
[33:39] SPEAKER: through it but i i've definitely drunk water from a lake through it before wow interesting and that's
[33:45] SPEAKER: that's it's the same kind of filtering you get with like a life straw or something like that
[33:48] SPEAKER: but you can actually get a substantial amount of water with it yeah um yeah definitely keeping
[33:54] SPEAKER: water around is the big one uh obviously that's easier if you're in a bigger place like in an
[33:58] SPEAKER: apartment it's tough to keep however what what's the recommendation is like x number of gallons a
[34:02] SPEAKER: day per person one one gallon per person plus more that's just for drinking and like washing and
[34:07] SPEAKER: making food right right so it's obviously tough to keep a lot of water around in a smaller place but
[34:13] SPEAKER: the thing that hit me you know i grew up there with a well so you know and the power went out
[34:17] SPEAKER: a lot from ice storms and then you know thunderstorms and all kinds of stuff but
[34:21] SPEAKER: we were used to not having running water on a well there the thing i never considered is
[34:26] SPEAKER: you know this was bad enough to disrupt for example ashville city water dramatically like
[34:30] SPEAKER: there were places that just didn't have water and then when they did have it like i said the
[34:33] SPEAKER: boil order was still on after i left with the boil yeah the last thing i saw is that the boil water
[34:38] SPEAKER: is going to be on indefinitely because the water treatment plant got really jacked up right so so
[34:43] SPEAKER: even if you're on city water which does work when the power is out like your water supply might still
[34:47] SPEAKER: be severely compromised if things are bad enough so even even then having some potable water around
[34:52] SPEAKER: is is a must i i've i've um this is the thing i've talked to vinnie about in the past but i've
[34:59] SPEAKER: been thinking about like having a rain barrel just to have toilet flushing water yep um the the the
[35:07] SPEAKER: the big like do you think people are going to sign up for solar and batteries at this point i don't
[35:12] SPEAKER: know uh i've definitely seen more people online talking about like like vinnie advocates for jackery
[35:17] SPEAKER: is one company that does like kind of big whole home battery backup yeah contraptions and you
[35:22] SPEAKER: can get solar cells that attach to those to charge them throughout the day like that we'll get to it
[35:26] SPEAKER: in a minute you know i've messed with generators enough during this trip to think that that might
[35:30] SPEAKER: be a nice a nice clean alternative to generators i don't know how fast those solar cells charge
[35:35] SPEAKER: so you if you want to do a whole house worth of electricity you need quite a few of them
[35:39] SPEAKER: right yeah like yeah like my house is a thousand square feet doing the math on how much power we
[35:44] SPEAKER: use every day i could cover i could get enough power out of a significant percentage of our roof
[35:51] SPEAKER: plus some batteries in the garage to basically run indefinitely assuming that there's no like
[35:56] SPEAKER: assuming a tree doesn't fall in the house and break the panels right sure sure um that that
[36:01] SPEAKER: portable battery backup that he was talking about apparently you can like daisy chain more solar
[36:05] SPEAKER: cells onto those so you can buy extras to make it charge faster which is cool so you like fill
[36:09] SPEAKER: your backyard with them and then yeah um so like i said i talked to you before i left about just
[36:14] SPEAKER: like hey what are some what are some things i haven't thought of that i should bring um
[36:18] SPEAKER: you recommended these little um solar-powered led lanterns that are getting pretty popular
[36:24] SPEAKER: the brand i bought was luminade that's just the one that came up when i searched yeah i i first
[36:30] SPEAKER: got these years and years ago when we bought the house and i was like we need to have a way to have
[36:34] SPEAKER: light if the power goes out um and there was a company called d light that did a thing where they
[36:40] SPEAKER: were it was like a tom's situation where they would make for every light you bought from them
[36:45] SPEAKER: they would put two into like places in the global south where they were using kerosene lanterns and
[36:51] SPEAKER: stuff like that that were burning down houses sure um and yeah it's it's basically just like a little
[36:58] SPEAKER: solar cell it's waterproof you put an led in the bottom and then there's like a plastic cup
[37:04] SPEAKER: basically that diffuses the light out of the led and a little battery and it's enough to get 14
[37:10] SPEAKER: hours of light on a day's charge so so these these were clutch uh i bought some luminade again as the
[37:17] SPEAKER: brand if you want to go look at the ones i i got but um i bought two of the smaller ones on one of
[37:21] SPEAKER: the bigger ones and the thing about these is that they are basically inflatable oh yeah so they
[37:26] SPEAKER: compress or flatten down into basically like a one inch thickness little square and then you kind of
[37:31] SPEAKER: inflate them at night when you want to use them that's it's like two puffs right right or actually
[37:35] SPEAKER: the bigger nicer one i got which was like 100 bucks like you actually didn't even have to
[37:38] SPEAKER: inflate it you just twist it and it would kind of expand on its own it's kind of hard to explain but
[37:43] SPEAKER: it was really cool uh that one the bigger one on the lowest brightness which was still enough to
[37:48] SPEAKER: light like a hallway to go to the bathroom or whatever just fine at night actually had like
[37:53] SPEAKER: 100 hours of runtime it had like a way way brighter modes that were just like you know
[37:57] SPEAKER: three hours or 12 hours but the lowest mode it would run for like from you know four or five
[38:02] SPEAKER: days on a single full charge um they will not charge all the way uh via solar like there's not
[38:09] SPEAKER: enough time okay in the day to fully charge them but they will still give you i think most of a
[38:14] SPEAKER: night's run time on the lowest setting uh if you leave them out all day so the ones that we got are
[38:20] SPEAKER: the d dot light ones and um they have inflatables and then canister ones um it turns out if you have
[38:29] SPEAKER: a way to put them up above you you it's not as bright as like a coleman lantern with those with
[38:34] SPEAKER: the you know the wicks but it they're infinite right like the benefit is that they're infinite
[38:39] SPEAKER: and these you can charge off of usb to get them get them primed up if you need to yeah and in fact
[38:43] SPEAKER: the the bigger one of these i bought had usb out like charging ports for your phone that's nice i
[38:47] SPEAKER: mean i don't know how much charging would get uh off of just a solar charge but it did have that
[38:52] SPEAKER: option which is cool uh yeah these were huge i mean if you're just in an extended power outage
[38:56] SPEAKER: situation just being able to see at a basic level where you're going at night in the middle of the
[39:02] SPEAKER: night looked very great when you're camping too like these these we have in the in the camping
[39:06] SPEAKER: kit i have a one of the inflatable ones a little one that i just when i when i used to backpack i
[39:11] SPEAKER: would hang on the back of the backpack during the day when i was walking and then it would be
[39:15] SPEAKER: charged up at night and i would have camp light when i was making dinner and stuff like that which
[39:18] SPEAKER: was really nice yeah um i got a couple of the um i mean everybody knows about these just a couple
[39:24] SPEAKER: of onker 20 000 milliamp hour battery packs yeah which we didn't have any current ones of we've
[39:30] SPEAKER: been a while since i've owned one of those so it's nice to have now the density has gone up
[39:34] SPEAKER: dramatically since i bought my last ones and i need to replace yeah like i ran we'll get to it
[39:39] SPEAKER: later there was a couple days after i got there there was a work situation i needed to deal with
[39:43] SPEAKER: and i ran my laptop and phone off of one of those battery packs yeah for a time um and then the cash
[39:50] SPEAKER: like i said just this this this situation i've i've always kept like a little bit of cash around
[39:56] SPEAKER: but the situation is going to increase the amount that i keep around yeah it makes sense by a good
[40:01] SPEAKER: bit because having having a few hundred dollars in a situation where you can only buy groceries
[40:05] SPEAKER: with cash is very important yeah um yeah that was it like i you know that's that's what i very
[40:12] SPEAKER: quickly threw together in the time that we had to prepare and like all of it turned out to be useful
[40:16] SPEAKER: like at the time when i ordered all that stuff and went and took several hundred dollars out of the
[40:20] SPEAKER: bank i was like am i is this overkill am i going overboard is this disaster theater am i just
[40:26] SPEAKER: making myself feel better but no like everything i'd got was super useful well and it's also worth
[40:32] SPEAKER: mentioning i don't think you probably would have gone if your parents weren't fairly elderly right
[40:36] SPEAKER: yes yes like that that was a big part of it as well which i'm not going to get into too much but
[40:40] SPEAKER: you know some just kind of like family realities that basically required somebody to be there
[40:46] SPEAKER: well and and but also like if you have 70 year old parents having like you don't want them ripping
[40:52] SPEAKER: carpet out oh definitely or in this case could not like not capable um yeah so um and then also
[40:59] SPEAKER: the neighbors in the in the neighborhood were amazing like i said generally around town there
[41:03] SPEAKER: was tons of like kind of mutual aid stuff around but also like people were people in their
[41:07] SPEAKER: neighborhood were just pulling together in a way that really restores your faith in humanity well
[41:12] SPEAKER: and and like it's nice when like your neighborhood was relatively lightly hit it sounds like right
[41:18] SPEAKER: yeah and like like everybody in the neighborhood had water in the house but but but yes nobody
[41:22] SPEAKER: nobody got flooded out uh although god i feel terrible one of the neighbors just spent like
[41:27] SPEAKER: the better part of a year remodeling their entire downstairs no intensively like remodeled to the
[41:32] SPEAKER: point that they went and stayed with a parent for a few months because it was that level of rebuttal
[41:38] SPEAKER: and the whole downstairs which was fully finished got hit badly well at least they know what it
[41:43] SPEAKER: costs when the insurance comes they can yeah probably be a lot faster the second time um
[41:48] SPEAKER: okay so what we talked about generator i talked to you once or twice while you were gone and we
[41:53] SPEAKER: talked about generators a little bit i think vinnie and i think it's a conversation with
[41:56] SPEAKER: vinnie about generators too yes yes so so they they borrowed that generator right before i got there
[42:02] SPEAKER: um the thing that long story short the thing they didn't realize is that they didn't know they could
[42:08] SPEAKER: hook that generator into the mains of the house do they is their house set up for that so it is
[42:13] SPEAKER: okay but it happened long ago again it's hard to explain but it happened long enough ago and there
[42:17] SPEAKER: was not yeah there was not enough shared knowledge of the setup there let's say to for for everybody
[42:23] SPEAKER: to connect the dots got him and then slowly people came to the realization that like oh wait there is
[42:30] SPEAKER: totally a 240 volt plug here wait hold on you didn't use a mail-to-mail plug to plug the
[42:36] SPEAKER: generator into okay okay okay everything was fine it's just that nobody nobody there had the
[42:40] SPEAKER: expertise and knowledge of the house to know that that could happen until after we got there and
[42:44] SPEAKER: then we slowly pieced together oh wait we totally have a 240 volt cable and a plug into the mains of
[42:51] SPEAKER: the house here and so did you have a cut off so you could cut off the outbound so that you don't
[42:55] SPEAKER: electrify the wires near your house yeah yes there was like a second and i'm getting way out of my
[42:59] SPEAKER: depth here with electrical stuff but there was a second like second circuit breaker box there with
[43:05] SPEAKER: kind of a changeover kind of you can only you can switch it okay you can only throw the breaker
[43:10] SPEAKER: on either the main or the generator at once they can't both be on at the same time if that makes
[43:15] SPEAKER: sense yeah anyway long story short you do that so you don't electrocute line line just to be clear
[43:20] SPEAKER: yeah like they had just been plugging a few appliances and lights straight into the generator
[43:25] SPEAKER: when we got there yeah but then after after we got there and figure out what was what we realized
[43:29] SPEAKER: that we couldn't hook it straight into the house and just turn off the enough breakers that you
[43:33] SPEAKER: didn't overload the generator yes so like it was it was a it was a rapid educational process of
[43:40] SPEAKER: how trying to figure out what was what especially with like very spotty internet like i said but i
[43:44] SPEAKER: sure i sure know what a 240 volt plug looks like now and we'll never forget um some other weird
[43:51] SPEAKER: stuff i ran into like a um i'm sure you've seen this like a 120 volt plug where one of the two
[43:57] SPEAKER: prongs is sideways it's almost like smiley face winking at you oh is that the is that the one you
[44:03] SPEAKER: use for the outbound 120 volt i think that's what that is i was not clear we never ended up using
[44:08] SPEAKER: that but that's what that seemed like yeah um there was a there was a uh an ongoing like
[44:16] SPEAKER: experimental process i guess i would say trying to figure out what in the house was actually wired to
[44:21] SPEAKER: the generator this is this is a 70s construction problem okay that house was built in the early
[44:27] SPEAKER: 70s so that that checks out because trying to figure out what was and was not wired to the
[44:32] SPEAKER: generator and what lunatic thought that was appropriate was an ongoing problem because like
[44:37] SPEAKER: for example none of the overhead lights in the kitchen were were on the generator circuit so i
[44:43] SPEAKER: don't even know if i'm using the right terms here but like whatever whatever subset of the of the
[44:47] SPEAKER: wiring in the house was hooked up to the generator like no lights in the kitchen for example well
[44:51] SPEAKER: so there's two things one is that in the old days they would wire like the things that would end up
[44:57] SPEAKER: on the same circuit were all run in series so like you go from like the the bedroom light to the
[45:04] SPEAKER: other bedroom light to the plug on the edge of the bedroom wall and then be like well that looks like
[45:08] SPEAKER: about enough for 15 amps and then they'd cut that one off interesting okay like the plugs in later
[45:14] SPEAKER: like i want to say 80s or 90s they started doing like okay mass the the main bedroom will all have
[45:21] SPEAKER: all the plugs in the main bedroom will be on the same circuit right but before it was just like
[45:26] SPEAKER: what was convenient when the electrician was running through the house okay that makes way
[45:29] SPEAKER: more sense than yeah because it was just a constant bafflement at who thought this was
[45:34] SPEAKER: a good way to wire things up like the like the bedroom the bedroom at the far end of the house
[45:38] SPEAKER: had a couple of outlets that worked but the bedroom closer to the closer to the the circuit
[45:42] SPEAKER: breaker and the generator hadn't had zero for example i was gonna say and then the other thing
[45:46] SPEAKER: is a lot of times especially in older houses like in the 50s they'd have two plugs per room
[45:52] SPEAKER: right and then at some point you come through and you're like well i gotta get an electrician in
[45:56] SPEAKER: here because like it's the 21st century and we have shit that needs to be plugged in so you run
[46:01] SPEAKER: a lot more cables and then like i have a separate circuit breaker box that the that the new cables
[46:05] SPEAKER: are run out of right they're not they're not in the main panel sure so it's like there's a breaker
[46:10] SPEAKER: that goes to them and then the big breaker that goes to them and then there's another smaller
[46:14] SPEAKER: panel that's hidden someplace that like i'm gonna have to tell whoever buys our house eventually
[46:18] SPEAKER: where where all that stuff is sure is that is that the kind of thing you can get rewired with
[46:22] SPEAKER: a minimum of like like like non-invasively or do you actually have to like tear out wires like
[46:27] SPEAKER: room by room to rewire stuff like that it's really easy to run new wires it's you have to tear out
[46:33] SPEAKER: walls to replace old wires so it's usually easier to just cover up the old wires and disconnect them
[46:38] SPEAKER: and run new wires unless you have to pull out walls for some reason got it okay because there
[46:44] SPEAKER: was there was some idle talk of like maybe we should get some of this redone to make it less
[46:48] SPEAKER: of a pain but i mean it's i was gonna say like here's the the nice thing is if they have the
[46:53] SPEAKER: cutoff for main versus internal power they're already they have the expensive part done for the
[47:00] SPEAKER: i mean obviously panels and batteries and all that stuff are expensive too but it doesn't require a
[47:04] SPEAKER: massive rewiring in a new panel to do the to if they wanted to put solar and get batteries assuming
[47:10] SPEAKER: they have enough sun yeah so like i think that's the conversation right is like the breakers go
[47:17] SPEAKER: through and label all the breakers right because because the other way you can do it is you just
[47:21] SPEAKER: turn off the breakers and then you literally walk around and you test every outlet and every light
[47:24] SPEAKER: and all that stuff and and you find out which ones are which and then you make a map and clearly label
[47:31] SPEAKER: inside the box that is the work that had not been done because only only a small handful of the
[47:36] SPEAKER: breakers were labeled in the box and nobody had mapped out what was what in the house so it was
[47:41] SPEAKER: yeah kind of complicated look my breaker box has dishwasher question mark next to three different
[47:46] SPEAKER: breakers so yeah it's about it's about stuff like that in fact i've got some pictures of it here i'm
[47:50] SPEAKER: going to share my screen with you real quick so we can uh talk about some visual aids here i've got
[47:55] SPEAKER: uh i've got a picture of uh one of the old breakers here that's a breaker box okay some of them have
[48:01] SPEAKER: been written over and scribbled out multiple times yeah uh so you have multiple breaker boxes that's
[48:08] SPEAKER: always exciting so this is this is the one that got added in the like late 90s around 2000 after
[48:12] SPEAKER: enough power outages made people sick of things um so this this was the this was the 240 volt plug
[48:20] SPEAKER: that was discovered and it was like oh wait we can just run this generator straight into the house
[48:24] SPEAKER: rather than just plugging some lights and appliances straight into it i like that the
[48:28] SPEAKER: notes are written in pencil it looks like on the metal uh-huh that's that's a lasting plan they
[48:33] SPEAKER: sure are and it's good that the breaker box was installed upside down it doesn't matter yeah but
[48:38] SPEAKER: also all the yeah okay um anyway um so uh what happened with um the whole generator situation
[48:48] SPEAKER: is that the neighbor who let us borrow that loner uh his his internal his in-home natural gas one
[48:55] SPEAKER: started leaking oil pretty substantially oh boy so he came down a few days later saying i might
[49:00] SPEAKER: need that one back soon so we kind of had to drop everything and go out and find our own i'm
[49:05] SPEAKER: impressed you were able to find one so am i it was it was it blew my mind and at the time i was
[49:09] SPEAKER: like oh maybe are they just like airlifting these things in like i can't believe they found some
[49:13] SPEAKER: yeah i guess they were but like they're like i saw videos of people dropping generators from
[49:18] SPEAKER: chinooks to people up in valleys that had their roads washed out and we're gonna be without power
[49:23] SPEAKER: from weeks i showed you i showed you a video before this i mean obviously can't show it on
[49:27] SPEAKER: the podcast but i was just in the part of the target parking lot one day about to pull out and
[49:31] SPEAKER: i heard a helicopter just looked and it was a chinook flying right over the target there are
[49:34] SPEAKER: there are very specific like they're the people don't know they're the ones that have the two two
[49:39] SPEAKER: propellers two two rotors on the top yeah and they make a real specific sound they sure do they fly
[49:45] SPEAKER: over my house sometimes on the coast sure uh so anyway like like i said we had we barely had
[49:49] SPEAKER: internet but i kind of slogged through that to try to check websites for local places so there's
[49:55] SPEAKER: a lowes and a home depot fairly close and shockingly they actually had generators in stock
[50:00] SPEAKER: so wow so we basically just zipped over there in the pickup truck and bought a generac that day
[50:06] SPEAKER: nice happened to be back over there a couple days later zero generators like they were all gone
[50:10] SPEAKER: yeah sure it was very spotty i think we just got super lucky that we happened to find some that day
[50:15] SPEAKER: the the home depot guy told me that they home depot had sold something like 20 000 generators
[50:20] SPEAKER: in the area in the last week i bet they were shifting stock as fast as they could from other
[50:24] SPEAKER: stores right they also had a big sign up that said no no open box generators returns accepted
[50:30] SPEAKER: no exceptions well so now you're now your folks have a generator just in case yes so i mean that's
[50:35] SPEAKER: a whole thing like man you know we were having to go buy gas every day or two yeah how much how
[50:40] SPEAKER: much gas does a generator use did you run it around the clock no definitely absolutely not
[50:45] SPEAKER: we were trying to be pretty conservative especially on the neighbor's loaner but even after we
[50:49] SPEAKER: got our own we were trying to be pretty judicious about it um i mean like i said there were a lot of
[50:53] SPEAKER: things i had to learn about generators like continuous wattage versus peak wattage and like
[50:57] SPEAKER: how much gas do they burn at sort of idle or at low minimum draw like do they have do they have
[51:02] SPEAKER: a minimum output it sounds like they do like they're like they're always going to burn and
[51:06] SPEAKER: output a floor even if you're not yeah pulling that current from it right well i mean like
[51:11] SPEAKER: presumably you have the fridge on the circuit that's covered so like you're always you're
[51:15] SPEAKER: always running at least you know a couple of watts for the fridge right right so so even even there
[51:20] SPEAKER: we were we were basically running it in the evenings for like five six hours okay uh and
[51:25] SPEAKER: then shutting it off before bed and then maybe like for an hour or two in the morning so just
[51:29] SPEAKER: to get water water tanks and stuff like that yeah flush toilets and stuff like that do they have a
[51:34] SPEAKER: gas hot water heater or electric uh i believe it is a gas okay pretty sure it's gas did you have
[51:41] SPEAKER: hot water when you took showers yes okay uh but but the generator was running then so i but i'm
[51:46] SPEAKER: pretty sure it's gas okay and i assume they're like bottled gas not on a main um i think that's
[51:54] SPEAKER: right okay i think that's right don't quote me on that yeah yeah um but you know like i i i have
[52:01] SPEAKER: never like worked on cars in my life you know like i don't have a lot of combustible or combustion
[52:06] SPEAKER: engine experience so like dealing with the generator was educational like we had to change
[52:11] SPEAKER: the oil on the neighbor generator at one point oh boy uh because apparently you have to change the
[52:15] SPEAKER: oil and generators like very very quickly or very very frequently i should say yeah it's usually it's
[52:20] SPEAKER: every certain number of hours running right yes uh we bought that that generac we got came with
[52:26] SPEAKER: a quart of what they just described as like special generator blend oil huh although they
[52:33] SPEAKER: said use this first before you switch over to regular like store-bought is that for like the
[52:37] SPEAKER: break-in period yeah basically it's basically said it was kind of a break-in period but then
[52:41] SPEAKER: there was kind of a debate in the house because the manual the manual said to use 5w30 oil with
[52:46] SPEAKER: the generator okay um they have like a little temperature chart and they basically said don't
[52:49] SPEAKER: use 10w30 unless it's like 40 degrees fahrenheit or below outside oh so there's a viscosity thing
[52:56] SPEAKER: probably i guess i guess that's what it is that's weird though there were some skepticism from some
[53:00] SPEAKER: old timers around about 5w30 is a pretty light oil but that's what the manual said so that's what we
[53:08] SPEAKER: what we got yeah you'd assume that um yeah i'd assume that once it's i i guess it's just during
[53:14] SPEAKER: the warm-up while it's warming it matters yeah maybe so uh i just i just went by the book on
[53:20] SPEAKER: that but um i mean i guess we don't need to get into like chokes and all kinds of parts of like
[53:25] SPEAKER: it's just like it's just all the fun of a gas lawnmower with uh something that runs and makes
[53:30] SPEAKER: your refrigerator work yep yep uh and then once the power came back on uh i found a lot of
[53:35] SPEAKER: conflicting opinions out there about how you should like store a generator and keep it primed
[53:39] SPEAKER: and ready for use did you drain the gas and all that i unfortunately i did not have time it was a
[53:44] SPEAKER: it turned into a mad scramble before we left mostly working on the basement trying to get
[53:48] SPEAKER: things ready for mediators to come in yeah so unfortunately did not have time to deal with that
[53:52] SPEAKER: but like i or other family are going to be back there again soon enough to deal with it i i would
[53:59] SPEAKER: my assumption would be that you put like worst case you put gas stabilizer in but best case you
[54:04] SPEAKER: probably drain the gas and like does it have a coolant loop it has to rain or is it air cooled
[54:09] SPEAKER: i'm not the person to ask about that well because like like on most gas engines like a boat or a
[54:16] SPEAKER: like motorcycle or whatever like uh sorry not a motorcycle a lawnmower you winterize uh to to if
[54:23] SPEAKER: it has coolant so the coolant doesn't freeze and crack the block right so so you know it's awesome
[54:28] SPEAKER: some people were saying like oh you should you should crank it and run it once a month
[54:32] SPEAKER: that's like a pain in the ass yeah yes i agree but then other people were like drain it other
[54:36] SPEAKER: people were like no let it run down until until the gas is gone yeah um there were a lot of
[54:41] SPEAKER: conflicting opinions but anyway like i said it'll it'll get dealt with in fairly short order this is
[54:46] SPEAKER: one of those ones where i look at what the manual says and probably just do that yeah that's that's
[54:50] SPEAKER: probably the actual right way to go um let's see we talk about some of the work on the house a
[54:55] SPEAKER: little bit yeah um downstairs it is like 80 percent a laminate it's like linoleum type stuff uh no no
[55:03] SPEAKER: like a like a panel oh oh like like pergo and mohawk are brands that you will see there
[55:09] SPEAKER: got it like a faux a faux sort of um hardwood looking material hardwood made of plastic that
[55:15] SPEAKER: you can that that tongue and grooves together in a way that you don't have to actually glue
[55:19] SPEAKER: it to the floor uh or in this case because i pulled a fair amount of it up it's like almost
[55:23] SPEAKER: like a cardboard kind of material underneath the the top weird the top like hard part yeah yeah
[55:29] SPEAKER: like a paper pulpy paper cardboardy kind of thing weird um and then there's a there's a guest bedroom
[55:34] SPEAKER: down there that had carpet in it sadly um so basically after on day two after we got all the
[55:40] SPEAKER: power stuff sorted out and kind of humming along reasonably well we immediately started tearing
[55:45] SPEAKER: carpet out yeah that's that's good i'm sure it was soaking wet no it was like when you when you
[55:50] SPEAKER: walk down there it was like water still squeezing out of the carpet as you would step on it um
[55:56] SPEAKER: so we you know down there with crowbars and uh box cutters tearing that out as fast as we could
[56:02] SPEAKER: and piling it outside yeah um all that to the dump i talked about this a lot on the next land
[56:08] SPEAKER: of ramble cast if people want to go listen to that i won't get into some of the same details
[56:11] SPEAKER: here but there was a whole scene at the dump oh i'm sure you can imagine chaos yeah of people
[56:17] SPEAKER: trying to bring storm debris and stuff in um later on the the county instituted a program there where
[56:23] SPEAKER: they're actually just going to go around and pick up literally everything that they find in every
[56:27] SPEAKER: right of way in the county oh that's nice no questions asked for free man so once that once
[56:32] SPEAKER: that order went out widely because they were actually asking people not to go to the to the
[56:37] SPEAKER: dump because there were like a lot of industrial people coming in and out of there and it was just
[56:41] SPEAKER: a huge mess which we were happy to not do again after we dumped the carpet but once that order
[56:46] SPEAKER: went out and you were driving around you would just see the craziest piles of stuff outside
[56:50] SPEAKER: people's houses like dude not just rolls of carpets but like furniture you know like dressers and
[56:55] SPEAKER: mattresses and just everywhere you went just giant piles of stuff that people would turn out that was
[57:00] SPEAKER: ruined what i assume up there people don't have flood insurance for the most part right you can't
[57:05] SPEAKER: it's some kind of fema directive that flood insurance in western north carolina is not allowed
[57:11] SPEAKER: weird i do not understand but that is the case because they they have a i showed you some
[57:17] SPEAKER: pictures there is a pretty sizable tree limb down yeah i saw on the on the house which as far as i
[57:24] SPEAKER: know is still there because good luck getting tree people out yeah they know they know a tree guy
[57:29] SPEAKER: that they're very friendly with and he was just like hey i'll get to you when i get to you yeah
[57:34] SPEAKER: that's how it kind of works right well the next thing that'll happen is the roofers will come
[57:38] SPEAKER: right when we had we there was a big hail storm in knoxville when i lived there and for the people
[57:43] SPEAKER: like like a double digit percentage of all their homes in the area got their their roofs destroyed
[57:50] SPEAKER: yeah and then next like a month later a bazillion roofers came in from all over the southeast and
[57:57] SPEAKER: like it was it was like people were back in business by the next winter yeah which was which
[58:01] SPEAKER: was nice yeah they'll get there and they they had a guy they know who's kind of a former roof guy
[58:06] SPEAKER: who's a friend came by and looked and said he doesn't think it's gonna leak so hopefully it'll
[58:11] SPEAKER: be fine until it gets fixed yeah hopefully they can get it done before winter though yes uh anyway
[58:16] SPEAKER: so yeah we got the carpet out of there as fast as we could there was just too much stuff everywhere
[58:20] SPEAKER: too much like the entire contents of the guest bedroom had to be loaded out into the main area
[58:24] SPEAKER: with the laminate yeah for example so there was just too much furniture everywhere and also we
[58:28] SPEAKER: were trying our best to dry out a lot of our stuff that got wet yeah which turned out to mostly be my
[58:33] SPEAKER: stuff sadly so we could not pull up that much of the laminate while i was there just because there
[58:37] SPEAKER: was too much stuff on it everywhere yeah yeah so i assume you had to tear out all the walls too up
[58:44] SPEAKER: to whatever the flood water mark was so none of that has happened yet but yes that is coming okay
[58:49] SPEAKER: um like like i said we couldn't even get all the flooring out it was it was very much while i was
[58:54] SPEAKER: there it was very much let's get rid of a bunch of stuff let's figure out what's ruined a fair
[58:59] SPEAKER: amount of non-ruined stuff also got rid of because it turns out an event like this is a good occasion
[59:04] SPEAKER: to just be like you know what we don't need a lot of this stuff like it's time to to simplify so
[59:08] SPEAKER: yeah a lot of while i was there was sifting through stuff drying stuff out consolidating
[59:12] SPEAKER: putting i bought a body ton of plastic bins to consolidate a bunch of stuff into so we kind of
[59:17] SPEAKER: reduced the footprint of the clutter and the belongings down there quite a bit wait did the
[59:21] SPEAKER: duck make the cut bread uh the duck's still up on the china cabinet oh okay i mean it's like i
[59:27] SPEAKER: i don't believe in divine intervention but like this the stuff that got spared down there is
[59:31] SPEAKER: almost hard not to think about something like that because like like a lot of my stuff like i said got
[59:36] SPEAKER: wet but it's mostly all like video game memorabilia and like some of it's of some historical value but
[59:40] SPEAKER: like the true family heirlooms there were multiple cases of like 80 year old photos you know like my
[59:46] SPEAKER: grandparents photos like correspondence from almost you know from 80 plus years ago like
[59:52] SPEAKER: multiple cases of like water is standing on top of the chest that this stuff is in and none of
[59:57] SPEAKER: it got wet like it's crazy how lucky i feel about stuff like that but um anyway yeah it was it was a
[1:00:03] SPEAKER: lot of going through stuff down there um by the time the power came back on like i said it was 11
[1:00:08] SPEAKER: days and it was also like 80 degrees and muggy the entire time so it was incredibly dank down there
[1:00:14] SPEAKER: it did not smell good yeah no i can only imagine and and like i'm sure that there's no like
[1:00:19] SPEAKER: industrial dehumidifiers and like big fans and all that stuff definitely not in fact but my mom had
[1:00:24] SPEAKER: read that in a mold situation like this it's actually bad to run fans because it can spread
[1:00:28] SPEAKER: spores around that makes sense but basically there's only there's only a door and two small
[1:00:33] SPEAKER: windows on that basement so it was basically like this kind of muggy late summer weather
[1:00:37] SPEAKER: and the basement soaked and basically just having the windows and door open to try to air it out and
[1:00:42] SPEAKER: that was it for 11 days which really sucked when the power finally came back on they have three
[1:00:47] SPEAKER: decent standing dehumidifiers down there because it's just a damp basement generally yeah and so i
[1:00:53] SPEAKER: was i was on like empty dehumidifier duty basically 24/7 love that and i could not tell you how much
[1:01:01] SPEAKER: water came out of the air down there um i would guess it was at least 10 gallons a day coming out
[1:01:08] SPEAKER: of those things because i had a big five gallon bucket that it was basically all three dehumidifiers
[1:01:12] SPEAKER: added up to just about that whole five gallon bucket when i emptied them wonderful and i was
[1:01:17] SPEAKER: easily emptying that thing twice a day plus you know like twice a day and into the night you know
[1:01:22] SPEAKER: like the overnight would add another one i mean it was just dozens of gallons of water that came
[1:01:28] SPEAKER: out of the air down there um well and it's yeah and it's like it's in the walls it's in the
[1:01:34] SPEAKER: yeah it's everywhere yeah like when we pulled up the laminate it was under the laminate you know
[1:01:38] SPEAKER: like it was just just water all over the place yeah so let's see so i guess so i assume they'll
[1:01:46] SPEAKER: have the remediation people come when when they get to them yeah so so they finally had their first
[1:01:51] SPEAKER: meeting like three days ago with the guy that's coming in to do both the flooring and remediation
[1:01:56] SPEAKER: stuff um so all the laminate has since been pulled out some family came after i left because we got
[1:02:03] SPEAKER: enough of the stuff out of the basement some other family came and helped take out the laminate which
[1:02:06] SPEAKER: is shockingly easy to pull out that's still like you said that um what's the term for the way that
[1:02:11] SPEAKER: stuff fits together it's tongue and groove and floating is the two eights i've heard it described
[1:02:15] SPEAKER: because like you said it's not glued down it's just it's basically just kept together like by
[1:02:18] SPEAKER: pressure right yeah you look i've taken up linoleum that was epoxied to the subfloor before and that
[1:02:26] SPEAKER: was like that was maybe one of the worst house repair jobs i've ever done i don't know i like
[1:02:31] SPEAKER: i think if i had to do that again i would just cut up the subfloor and put new subfloor in honestly
[1:02:35] SPEAKER: right um it's just so it's just obviously it's just a concrete floor down there but yeah that
[1:02:39] SPEAKER: that laminate was like the the stuff i did have room to pull up is like as easy as you can imagine
[1:02:44] SPEAKER: it literally just lifts right out yeah so that's all been pulled out now when the remediation guy
[1:02:48] SPEAKER: came uh they are going to cut out the bottom two feet of the drywall all the way around okay um
[1:02:54] SPEAKER: and you know i think it's pretty standard mold treatment stuff like they're gonna have to do
[1:02:57] SPEAKER: chemical treatments yeah you just want to keep it from growing when you get it dark and yes
[1:03:02] SPEAKER: wet in there all the all the cabinets in the bathroom and there's a little kitchenette kind
[1:03:06] SPEAKER: of thing down there like all those cabinets are gonna have to be ripped out because they
[1:03:09] SPEAKER: are full of mold inside yeah um stuff like that um i very quickly talking to my mom got a sense
[1:03:15] SPEAKER: of there there are four classes of water damage yeah um that involve things like was it clean
[1:03:20] SPEAKER: water just out of your pipes or was it like flood water was a chemically contaminated flood water
[1:03:26] SPEAKER: you know that sort of thing um so they've got class four which is the worst which means that
[1:03:30] SPEAKER: everything has to come out um they even have they have like sheet vinyl flooring in the bathroom
[1:03:36] SPEAKER: which looks just fine and we just assumed would be fine to stay but this guy said that even even
[1:03:42] SPEAKER: vinyl like that has to come out in a class four because water can get underneath it into the
[1:03:47] SPEAKER: concrete and you can get mold growing in the concrete so i assume that they're gonna have
[1:03:51] SPEAKER: like when the remediation people come they're gonna set up like the big heavy duty industrial
[1:03:55] SPEAKER: dehumidifiers for like a period of time i guess so i don't know because um so even running those
[1:04:01] SPEAKER: three dehumidifiers all day long it was still sitting at like 70 humidity down there for like a
[1:04:06] SPEAKER: week but it turned a corner like kind of overnight one day about a week after the power came back on
[1:04:10] SPEAKER: where all of a sudden they were actually reading more like 45 50. oh um so i think most of the
[1:04:18] SPEAKER: standing moisture just got kind of pulled out eventually from me running those for so long
[1:04:24] SPEAKER: um i wouldn't be shocked if they still do some industrial dehumidifying or something down there
[1:04:30] SPEAKER: yeah um there's been there's been some loose talk about what to put back in there
[1:04:34] SPEAKER: uh definitely no more carpet going down there yeah uh as you can imagine um the initial plan was it
[1:04:41] SPEAKER: sounded like just to put some basic vinyl down like was in the bathroom because the assumption
[1:04:46] SPEAKER: was that would be resilient to any future flooding uh but what this remediation guy has said like i
[1:04:51] SPEAKER: said like that bathroom that sheet in the bathroom has to come out anyway yeah so he said in a bad
[1:04:56] SPEAKER: enough flood you're gonna have to take all the flooring out no matter what it is you should just
[1:04:59] SPEAKER: do painted concrete then i'm serious like they do uh yeah like it's a whole thing they do like fancy
[1:05:06] SPEAKER: looking finished concrete and it looks like wood and now it still is hard like concrete and it's
[1:05:09] SPEAKER: cold like concrete so it's not like interesting yeah i didn't know they did such a thing finished
[1:05:14] SPEAKER: concrete wow you might have to have the like if the concrete's not smooth and shiny enough it
[1:05:18] SPEAKER: might not might not do it yeah it's extremely not but um they're looking at uh they they have like
[1:05:25] SPEAKER: vinyl plank now that is similar to that laminate that they had yeah which is like basic it's kind
[1:05:30] SPEAKER: of water resistant at a basic level like you can spill stuff on it it's fine yeah um but apparently
[1:05:34] SPEAKER: that's actually not really much more expensive than the sheet vinyl and we'll get them a similar
[1:05:40] SPEAKER: kind of fake hardwood look from what they had the pergo that's what the pergo stuff has become now
[1:05:44] SPEAKER: like it's all vinyl yeah you do you just do long sheets of vinyl okay of it's it's not vinyl but
[1:05:50] SPEAKER: it's like it's the same it's the same it's like a manufactured fake hardwood right yeah uh so so you
[1:05:56] SPEAKER: know basically the thought was this is not much more expensive than the sheet vinyl and in a
[1:06:00] SPEAKER: similar flood it's all gonna have to come up anyway yeah so they might as well get the one
[1:06:04] SPEAKER: that looks nicer um that's kind of it they're oh and uh the electrician is going to need to come
[1:06:10] SPEAKER: and replace all the electrical outlets as well is what this guy has said um i mean it makes sense
[1:06:15] SPEAKER: they're all working fine uh at the moments but i'm not sure that's a good idea long term
[1:06:21] SPEAKER: it's like this is this is a electrical plugs cost four dollars yeah yeah so yeah i think i think
[1:06:29] SPEAKER: what he said was the wiring should be fine because the wiring is all insulated but it's exposed at
[1:06:33] SPEAKER: the outlets so that's why the outlets need to come out we had a a very nice electrician from
[1:06:38] SPEAKER: hawaii wrote into the next lander podcast and basically told me exactly this that like hey
[1:06:43] SPEAKER: even if the outlets are working they can have corrosion on them from the water and it's not
[1:06:46] SPEAKER: a good idea to use those long term yeah makes sense yeah you don't want weird shorts yes
[1:06:52] SPEAKER: uh i guess the last stuff i would talk about here is just there's there's some computing stuff and
[1:06:56] SPEAKER: some things i found downstairs stuff yeah you you gave me a hint of this before but let's talk about
[1:07:04] SPEAKER: the connectivity stuff first i think because like this sounds like an enormous pain in the ass and
[1:07:09] SPEAKER: if you just called me and hooked me up with your landlord i would have been happy to drive over
[1:07:12] SPEAKER: there and like send you the file i you know i had i had a couple of family members admonish me for
[1:07:18] SPEAKER: like you know what you should just ask for help more not try to do everything yourselves and it's
[1:07:22] SPEAKER: okay to ask for help yeah i know i really don't like burdening people i mean look i have a family
[1:07:27] SPEAKER: full of people who don't ever ask for help so i understand there's a there's a degree of self
[1:07:32] SPEAKER: reliance that is expected and but it's okay to need help it is it is endemic rugged individualism
[1:07:39] SPEAKER: yeah in the area um this turned out to be this was kind of a fun challenge because it really
[1:07:44] SPEAKER: let me put my preparedness to the test on on remote access to my stuff here uh so a couple
[1:07:49] SPEAKER: days after i got there it turned out i had forgotten to upload one of my local podcast
[1:07:53] SPEAKER: recordings from xlander oops and if i hadn't been able to pull this off it was fine we do like a
[1:07:59] SPEAKER: we do a recording of the kind of video call mix down oh right that can be used in a pinch so it
[1:08:04] SPEAKER: would not have been like the absolute end of the world um but it did turn into kind of a fun
[1:08:09] SPEAKER: challenge of like okay i'm in an extremely uh i'm in a very reduced capability here let's say
[1:08:16] SPEAKER: powers out internet is out phones barely work i don't even know if i can tether to this phone
[1:08:20] SPEAKER: let's see if i can get a 500 megabyte wave file uploaded to dropbox wow um i will say
[1:08:27] SPEAKER: my first thought was so i can turn on everything remotely here my nas and my desktop pc but you
[1:08:32] SPEAKER: turn your nas off when you're out of town yeah i mean 75 watts but i'm not here i don't know
[1:08:40] SPEAKER: i mean nobody's watching plex movie though nobody's watching plex or streaming music here
[1:08:44] SPEAKER: or any of the other stuff okay okay doing podcast stuff or video kind of anyway my first thought was
[1:08:51] SPEAKER: like okay maybe i can remote desktop into my pc and export that file and get it uploaded to dropbox
[1:08:55] SPEAKER: but the way the data was working through the phones i was like okay there's no way the remote
[1:09:00] SPEAKER: desktop is going to be functional yeah um it kind of saved my ass that it turned out i had exported
[1:09:06] SPEAKER: the wave from the project to my nas before i went audacity project yes so the wave was sitting there
[1:09:12] SPEAKER: so i did not have to get audacity open to export a wave to upload it yeah the wave was already
[1:09:18] SPEAKER: sitting there so i kind of had to use like every tool at my disposal and it still took like an hour
[1:09:23] SPEAKER: and a half to get it done um but what i ended up doing because i realized i was like oh wait i can
[1:09:29] SPEAKER: i can access my nas and dropbox and everything without remote desktop i can do it all through
[1:09:33] SPEAKER: like text-based tools yeah that don't push a lot of data through so i did manage to tether my
[1:09:38] SPEAKER: laptop to my phone turn on low data mode there as well to try to prevent any like background
[1:09:43] SPEAKER: mail syncing or whatever okay clogging up the connection wire guarded into my house
[1:09:49] SPEAKER: connected to the pykvm which lets me press the power button on the nas essentially turned out
[1:09:54] SPEAKER: on why are you shaking your head just you could have had it could have already been on that's one
[1:09:58] SPEAKER: extra step and uh i also um i've tried to set that thing up for wake on land but for some reason
[1:10:04] SPEAKER: that's not working at the moment i could have done that as well if you didn't have a pykvm
[1:10:07] SPEAKER: it's turned on yeah but the pykvm makes it a lot easier then i was able to ssh into the nas
[1:10:13] SPEAKER: and because i've set up those r clone tools that hook up to things like dropbox and one drive
[1:10:18] SPEAKER: and google drive so basically anytime i log into my account on my nas it mounts all of my cloud
[1:10:23] SPEAKER: storage buckets as just local directories that's nice so ultimately i was able to ssh into the nas
[1:10:28] SPEAKER: and just basically issue a command to copy just a straight up cp the way file over to dropbox uh
[1:10:36] SPEAKER: or uh sorry in this case it was google drive but anyway i was able to basically get the file where
[1:10:40] SPEAKER: it needed to be for alex to grab it and use it in his edit you could have just sent me a login for
[1:10:45] SPEAKER: your ssh and you know yeah anyway uh i did i did run into ssh key problems that made me have to go
[1:10:51] SPEAKER: in and mess with the ssh d configuration so it would let me log in but anyway that's yeah either
[1:10:56] SPEAKER: here nor there something is always going to break though uh even with all these tools set up but it
[1:11:00] SPEAKER: was kind of nice to be like okay even our clone which sort of felt like a frivolous thing to set
[1:11:05] SPEAKER: up because how often are you going to need to access your google drive for coming from a command
[1:11:09] SPEAKER: line it was like oh in this case i'm actually extremely glad i had that it's funny you say that
[1:11:13] SPEAKER: because i like i haven't bothered to set that up specifically because of that and but it's often
[1:11:19] SPEAKER: a thing where i'm like man it'd be really nice to just be able to copy this into my dropbox
[1:11:23] SPEAKER: so good to know yeah it was cool some real mcgyver shit there brad yes yes it definitely was it was
[1:11:30] SPEAKER: satisfying it felt it felt like you know what i did all that work for a reason okay so let's get
[1:11:35] SPEAKER: to this sad part of the show i guess yeah i mean and again i really want to stress like this is
[1:11:40] SPEAKER: sad as an extremely relative term here like i'm kind of bummed that i lost some some stuff from
[1:11:45] SPEAKER: my early time in the game industry but you know sometimes it's freeing pretty small price to pay
[1:11:50] SPEAKER: well yeah some of the stuff is stuff that i would have maybe considered donating to the video game
[1:11:54] SPEAKER: history foundation at some point now it's ruined um yeah so it just happened to turn out we were
[1:12:00] SPEAKER: storing everything down there in cardboard boxes because my mom worked in education and had a ton
[1:12:05] SPEAKER: of paper boxes from over the years yeah the types of boxes that just printer paper comes in yeah
[1:12:09] SPEAKER: yeah of course um everything was in cardboard boxes it just so happened that most of the stuff
[1:12:13] SPEAKER: along the floor was mine oh so quite a few of my boxes of stuff got wet which is a real bummer
[1:12:19] SPEAKER: a lot of it was just like old video game and computer magazines which i think like
[1:12:22] SPEAKER: basically every magazine on the planet has been scanned and pdfed at this point right
[1:12:27] SPEAKER: i would say they're pretty well archived at this point it feels like so that's that's like kind of
[1:12:31] SPEAKER: a bummer but you know i can still read those magazines online i did have one box of old e3
[1:12:36] SPEAKER: materials from mostly from 1998 e3 that got ruined that's a kind of a heartbreaker like i've got the
[1:12:42] SPEAKER: i've got the full-on like very thick booklet of like show directory here's literally everybody's
[1:12:46] SPEAKER: speaking at e3 here's every booth there's description of every exhibitor like that thing
[1:12:50] SPEAKER: is trashed it's nasty god i'd forgotten that they used to hand that stuff you used to get a bag with
[1:12:55] SPEAKER: that stuff in it when you checked in at e3 yes yes like it was it was a crazy reminder of how much
[1:13:00] SPEAKER: just material like hard copy stuff they gave you at e3 also 98 was the first one i registered as
[1:13:04] SPEAKER: press okay so i had i had grabbed literally every press release in the press room like i had a stack
[1:13:10] SPEAKER: of stuff oh man uh some of which is like it's still legible like it's definitely water damaged
[1:13:14] SPEAKER: but a lot of it is probably still could be scanned uh if there's a need for that kind of stuff like
[1:13:18] SPEAKER: i've got nintendo's entire 1998 like thick e3 packet of like 50 press releases for ocarina of
[1:13:25] SPEAKER: time and the gameboy camera and a bunch of pokemon stuff like uh and that hopefully that stuff is
[1:13:30] SPEAKER: still usable wow lots of stuff like that a lot of random stuff i found apparently i requested
[1:13:35] SPEAKER: a packet of information from number nine somewhere around 95 96 the wow the the hey we make bad video
[1:13:41] SPEAKER: cards yes yes number nine the company that named all their video cards after beetle songs
[1:13:45] SPEAKER: and that seemed like it was going to be legally actionable i've got i've got and it's still it's
[1:13:50] SPEAKER: still fairly legible some of it i definitely got acquainted with which types of print papers stick
[1:13:55] SPEAKER: together and ruin themselves when you separate them and which don't that makes sense it's a lot
[1:13:59] SPEAKER: of the stuff that would get stuck together when i pull the pages apart and just pull all the print
[1:14:02] SPEAKER: off and the coding yeah and some of that number nine stuff is messed up anyway there's just a ton
[1:14:06] SPEAKER: of a ton of weird like marketing materials and so forth i've got pictures of some of the stuff i
[1:14:11] SPEAKER: could be showing you um i also just found a lot of stuff that didn't get ruined but like i said
[1:14:16] SPEAKER: because i was going through and throwing so much stuff out and categorizing and everything
[1:14:20] SPEAKER: i just found a lot of random stuff generally brad there's there's a bullet point here that says
[1:14:26] SPEAKER: found some printouts of usenet posts circa 1996 oh i've got them here's why did you print usenet
[1:14:31] SPEAKER: posts dude because it was the 90s man sometimes you wanted to be able to take it with you look
[1:14:37] SPEAKER: this is this is i guess sometimes you had to take so nuclear hot that you were like i'm gonna save
[1:14:43] SPEAKER: this one well no it was informational stuff like the one you can see here from sai dot lang dot
[1:14:47] SPEAKER: japan which is the quick and dirty guide to japanese grammar oh so it's like reference
[1:14:52] SPEAKER: material is what i had printed out um here you can see uh here's here's my nicely stapled slackware
[1:14:59] SPEAKER: documentation from the late 90s what is this microsoft oh dude congratulations on downloading
[1:15:04] SPEAKER: internet explorer 3.0 sorry yes i i i debated whether to even talk about that oh i there's no
[1:15:11] SPEAKER: way we're not talking about this uh i don't know if i registered for this or what i have a t-shirt
[1:15:17] SPEAKER: i think i've maybe put a picture of that t-shirt on twitter before this is like they oh they mailed
[1:15:22] SPEAKER: this to you yes they i don't know if i registered or if they just had my information somehow and i
[1:15:27] SPEAKER: i basically downloaded internet explorer 3.0 like at the midnight launch because of course i did 32
[1:15:33] SPEAKER: 000 people registered by morning uh we've decided to send free commemorative t-shirts to all of the
[1:15:39] SPEAKER: 32 000 plus users who registered their copies of internet explorer 3.0 during the midnight
[1:15:43] SPEAKER: madness promotion uh when they launched it basically so yes i have i have that t-shirt
[1:15:49] SPEAKER: downstairs somewhere it just has a big like i downloaded it internet explorer 3.0 on t-shirt
[1:15:54] SPEAKER: yes i am yes so i've never been like i've generally i'm not disappointed
[1:16:01] SPEAKER: but downloading internet explorer 3.0 on launch day this is a badge of shame my friend registering
[1:16:08] SPEAKER: it registering it going out of my way to register it before 6 a.m the following morning also just
[1:16:14] SPEAKER: some people know the counterpoint to this is the slackware is the how to get linux documentation
[1:16:21] SPEAKER: like you took pictures of both of these things side by side from around well i just found them
[1:16:25] SPEAKER: in the same box together i mean they're they may be a couple years apart i my recollection of
[1:16:29] SPEAKER: messing with slackware was probably around 1998 or so i don't i don't feel good about this when did
[1:16:34] SPEAKER: when did ie3 come out 96 probably oh that sounds right i think it's look browsers like you were
[1:16:42] SPEAKER: using netscape 2 back then you know like new browsers were a thing look man this is back in
[1:16:47] SPEAKER: the m dollar sign era of microsoft it's when slash had the board logo bill gates like this is i
[1:16:54] SPEAKER: probably shouldn't even show you this article i wrote about windows 95 at the time okay now this
[1:16:59] SPEAKER: is this is fantastic 32-bit preemptive multitasking architecture this is what lets you play doom while
[1:17:04] SPEAKER: defragging your hard drive okay i got it i got to call it hold on no no go back to that go back to
[1:17:09] SPEAKER: that you got to go back to that because you had written in the side gates in like big block text
[1:17:15] SPEAKER: with the s as like a lightning bolt like like in the mega death why i did that oh my god we can't
[1:17:21] SPEAKER: can i please read it please let me read it no i can't man oh it's a bad episode okay fine boom
[1:17:27] SPEAKER: boom this the sound of microsoft's juggernaut windows 95 has been growing louder for months
[1:17:34] SPEAKER: okay i'm not i'm not gonna read the rest of it but this is amazing this is really good
[1:17:39] SPEAKER: i myself have experienced this miracle os miracles and sneer quotes having sneer having
[1:17:46] SPEAKER: having been trampled underfoot by the microsoft propaganda machine at least you were aware i think
[1:17:52] SPEAKER: this was probably for my high school newspaper because there's also a printed out version of it
[1:17:56] SPEAKER: that's okay a bit more formal i worked on the paper for a couple of years some of my high school
[1:18:01] SPEAKER: newspapers got water locked unfortunately but there was a long drying out period of spreading
[1:18:06] SPEAKER: things out on drying racks and stuff to try to salvage as much as i could i i'm going to tell
[1:18:11] SPEAKER: you right now there is an endless amount of embarrassing old computer shit there is so so
[1:18:19] SPEAKER: much that i found that i do not have pictures of and i'm not mentioning to you look if you go back
[1:18:24] SPEAKER: for an extended period of time we can just do uh what's in brad's basement segment it'll be a
[1:18:29] SPEAKER: ten dollar patron tier dude that's like months of podcast fodder um i i gotta there's two things
[1:18:35] SPEAKER: that make me that are shocking like first i had forgotten that there was a time before cdns
[1:18:40] SPEAKER: when download servers would get overwhelmed and you wouldn't be able to download new software
[1:18:44] SPEAKER: when people were excited about it oh yeah that was kind of standard back then but like it's it's
[1:18:48] SPEAKER: been such a long time since that happened like when was the last time like you like call of duty
[1:18:53] SPEAKER: came out today and steam's not collapsed under that weight right like it's it's uh it's it's
[1:19:00] SPEAKER: amazing that that was such a limited period of time in retrospect it was a very different time
[1:19:05] SPEAKER: and then uh the other thing is the idea that microsoft would send out t-shirts to
[1:19:10] SPEAKER: 32 000 people for registering their browser like the like just the amount of money they were
[1:19:16] SPEAKER: spending on browser stuff is incredible to me oh absolutely anyway i've got one of those 32 000
[1:19:22] SPEAKER: shirts and i'm just going to because i'm already all the way down the road of debasing myself here
[1:19:27] SPEAKER: for your yeah what else you got i'm just going to tell you that t-shirt pretty rough shape which
[1:19:32] SPEAKER: means that i wore it a lot i mean look you you not everyone would have the rocks to wear a t-shirt
[1:19:41] SPEAKER: that shows their support for the faces of multinational corporations standing up against
[1:19:45] SPEAKER: the the underdog of mark andreasen it was a different landscape navigator god dude don't
[1:19:51] SPEAKER: even get me started about it remember that like time magazine cover of mark andreasen barefoot
[1:19:55] SPEAKER: look there there's been a lot of barefoot tech geniuses on the cover of time magazine we don't
[1:19:59] SPEAKER: need to get to walk down that path the mark andreasen villain arc is really something to
[1:20:04] SPEAKER: reckon with um at least i was linux curious at the time yeah i was not i was not fully in the
[1:20:10] SPEAKER: tank for microsoft you were in there yes anyway uh maybe someday if i if and when i have more
[1:20:16] SPEAKER: ready access to the archives down there maybe we'll go through some more of this material um
[1:20:22] SPEAKER: what about you said there's hardware down there we've talked about a little bit before i i you
[1:20:26] SPEAKER: know on the subject i think we'll wrap up here pretty quick but on the subject of feeling
[1:20:30] SPEAKER: fortunate about what did and didn't get wet not a single piece of electronics got wet oh that's nice
[1:20:35] SPEAKER: uh and granted if something's not plugged in you know i think probably
[1:20:39] SPEAKER: some some amount of electronics can withstand some amount of water yeah like you want to
[1:20:43] SPEAKER: wash them off with rubbing alcohol right high high percentage out from the alcohol to get the
[1:20:48] SPEAKER: just to keep them from corroding right but if you know but if if some stuff had gotten wet that
[1:20:52] SPEAKER: wouldn't necessarily mean it was dead but but at any rate nothing basically it was basically just
[1:20:56] SPEAKER: paper like pretty much everything i had get wet was almost all just paper well that's good i guess
[1:21:02] SPEAKER: there was there actually was one still fully built computer down there it was the one i had built
[1:21:06] SPEAKER: the last one i had built for my parents before before they were like you know we're just gonna
[1:21:10] SPEAKER: get laptops um and miraculously that case had zero water in it even though it was sitting on the
[1:21:16] SPEAKER: floor like i think it was on the floor i'm not sure where it was actually but oh weird somehow
[1:21:20] SPEAKER: it did not get water in it uh that is a it's an abit kx7 i believe in that machine okay um
[1:21:30] SPEAKER: which probably is some kind of mid period athlon like a thunderbird like a yeah like a thunderbird
[1:21:36] SPEAKER: 1.2 gigahertz is probably what's in there huh uh some kind of some kind of red ati card they were
[1:21:42] SPEAKER: all red then weren't they yeah they were most of them yeah uh so so that is a functional computer
[1:21:48] SPEAKER: presumably i mean it's at least it didn't get wet i don't i mean it may just like be old and
[1:21:52] SPEAKER: might not boot anyway but look next time you go back you should just build one of these and plug
[1:21:56] SPEAKER: it in see how it goes um so like i said as i was cleaning up and consolidating and bending things
[1:22:00] SPEAKER: i found a ton of other hardware scattered through different boxes i found two more abit boards down
[1:22:06] SPEAKER: there a bh6 and a kt7 bh6 is one of the great socket seven boards yes absolutely um some of the
[1:22:14] SPEAKER: stuff some of the stuff was from my old builds and some of it was hand-me-downs because i lived with
[1:22:18] SPEAKER: a roommate for quite a while around this time who would just give me his old stuff when he didn't
[1:22:22] SPEAKER: when he was upgrading okay so i've got quite a bit of extra hardware some of which i've never
[1:22:26] SPEAKER: used down there so so there's that full kt7 or sorry kx7 machine there's a bh6 and kt7
[1:22:32] SPEAKER: motherboards i found a pentium 2 but i've never used this yeah so loose pentium 2 but i never had
[1:22:37] SPEAKER: a pentium 2 i just had a celeron so i think that was one of my roommates i also found i found my
[1:22:42] SPEAKER: loose celeron 300a oh man was it a chip or a slot one uh it's a slot okay um also found that boxed
[1:22:50] SPEAKER: sealed 300a as well uh i found my voodoo one okay which was an orchid card or can we catch this one
[1:22:58] SPEAKER: i believe well no the cannabis with the extra two megabytes of ram was the nice one i felt like the
[1:23:03] SPEAKER: diamond one was the low end the orchid one was the mid-tier and the cannabis was the high end but
[1:23:08] SPEAKER: yeah yeah i think they were i don't know that's true i think they're all the same other than that
[1:23:12] SPEAKER: canopus one pretty much yeah i found i found the uh the tnt one that i had for a while that was
[1:23:18] SPEAKER: made by stb okay i found a voodoo 3 which i had to like google lens to figure out what it was
[1:23:23] SPEAKER: because i saw a 3d effects logo on there that was definitely my roommates because i've never had a
[1:23:27] SPEAKER: voodoo 3 that was already a card i never had any voodoo card past the voodoo one um i also found my
[1:23:34] SPEAKER: asus geforce 256 sdr oh man so there's like a pretty good assortment of CPUs and video cards
[1:23:42] SPEAKER: there i think that was the one of the first video cards i reviewed for maximum pc really asus ddr g
[1:23:47] SPEAKER: force uh this was the sdr one sdr sadly because i needed a card badly um so so yeah like and i also
[1:23:55] SPEAKER: found like a tons i found like two different modems like a land card uh an old video capture
[1:24:01] SPEAKER: card that was definitely not mine um but i think i could probably i could probably get three working
[1:24:07] SPEAKER: retro pcs together out of the stuff i found down there time time to have a land party down there
[1:24:11] SPEAKER: get them get fire up doom or duke nukem and you know let her rip assuming all that stuff works
[1:24:16] SPEAKER: once i get it put together but um and a nice thing the nice thing about atx you know we we kind of
[1:24:21] SPEAKER: lament the fact that atx is a 30 year old standard at this point it's a fairly common topic over on
[1:24:27] SPEAKER: uh on the full nerd yes uh but i guess the nice thing about that is i could buy like new atx power
[1:24:33] SPEAKER: supplies and cases for the stuff right and it should just work that's uh assuming they have
[1:24:38] SPEAKER: the 24 pin with the breakaway because it's probably a 16 pin or 20 pin connector oh power yeah i'll
[1:24:44] SPEAKER: have to look into that but but like worst case you can get in there with a pair of snips and make it
[1:24:48] SPEAKER: make it happen sure um anyway you know it was nice to find all that hardware and know that it still
[1:24:54] SPEAKER: might work kind of incredible yeah like yeah i'm glad i'm glad it wasn't too uh
[1:25:01] SPEAKER: glad it wasn't too much of a disaster yeah uh but none of that stuff was in static bags so i don't
[1:25:05] SPEAKER: know it's dysfunctional it is those circuits are big enough that it's not like yeah static is not
[1:25:13] SPEAKER: that much of a problem yeah you're probably right um well anyway brad i'm glad you're back i'm glad
[1:25:18] SPEAKER: everybody is like for the most part you know it's just it's just property damage yeah yeah totally
[1:25:24] SPEAKER: are you yeah i i mostly just want to do this episode because there were so many sort of
[1:25:28] SPEAKER: technical subjects that i rubbed up against as we were doing this well and like i think it's worth
[1:25:33] SPEAKER: talking about this stuff because it's good like hopefully this will light the fires and under some
[1:25:38] SPEAKER: people who haven't done their preparedness stuff right yeah like yeah like i think that's that kind
[1:25:41] SPEAKER: of the real lesson because you've had people in that area for a long time going like oh we're like
[1:25:46] SPEAKER: kind of immune to climate change here we don't really have a lot of natural disasters of note
[1:25:52] SPEAKER: like i have a an acquaintance who works in that space who when i asked them 10 years ago where you
[1:25:58] SPEAKER: should move if you wanted to be unaffected by climate change they're like well like western
[1:26:02] SPEAKER: north carolina pretty good vermont inland vermont pretty good like up in the mountains eastern
[1:26:09] SPEAKER: colorado all these places i was like oh yeah okay no nothing's safe it's all yeah that's that seems
[1:26:15] SPEAKER: to be the lesson just on the subject of disaster preparedness i think that's the lesson out of this
[1:26:19] SPEAKER: is that nowhere is immune it's all the same climate emergency yes no matter no matter where
[1:26:23] SPEAKER: you live it pays to be at least prepared at a basic level because you never know what might
[1:26:28] SPEAKER: happen well and i mean there was a lot of kind of misinformation about um like what's going on
[1:26:36] SPEAKER: in north carolina with the fema stuff it's been in the news we don't need to recap but that's that's
[1:26:41] SPEAKER: type of stuff i had no idea about until i got back out here basically because i wasn't really able to
[1:26:45] SPEAKER: follow news and social media much there but yeah hearing that there was like man this stuff makes
[1:26:50] SPEAKER: me so mad i don't know if i want to get into it yeah because like the people the the thing the
[1:26:55] SPEAKER: thing when you talk to people who are on the ground in in this kind of a climate this kind of
[1:27:00] SPEAKER: an emergency generally the vibe is that everybody pulls together yeah totally right and and the
[1:27:06] SPEAKER: stuff i saw in the news after i got back out here is that like even even local political leaders
[1:27:11] SPEAKER: who let's say are politically aligned with people spreading the misinformation were like hey fucking
[1:27:16] SPEAKER: stop yeah we've got enough problems here on the ground trying to deal with this in a real way
[1:27:20] SPEAKER: without you spreading conspiracy theories about this nonsense like shut the fuck up
[1:27:24] SPEAKER: yeah yeah get out of the way so that people can do the work yes yes turns out real life trump's
[1:27:31] SPEAKER: what's going on on social media when it comes down to it in so many ways brass yes uh but you know
[1:27:37] SPEAKER: what doesn't trump what's going on on social media is listener supported podcasts right
[1:27:42] SPEAKER: i don't even know what that means yeah actually i don't know if that's right but yeah let's go with
[1:27:46] SPEAKER: it uh brad and will made a tech pod is a listener supported show that means we wouldn't be here
[1:27:50] SPEAKER: without you the listeners who we love and appreciate every single week um if you want
[1:27:56] SPEAKER: to find out how you can support the show you can go to patreon.com slash tech pod again that's
[1:28:01] SPEAKER: patreon.com slash tech pod where for five bucks a month you get access to the patreon the the tech
[1:28:07] SPEAKER: pod discord which is like look sharing interesting things sharing topics talking about problems we're
[1:28:14] SPEAKER: talking about the the arrow lake launch which just so people know we're going to do a big like what's
[1:28:20] SPEAKER: going on with cpu episode what's the x3 x3d embargoes lift and i don't know when that is
[1:28:27] SPEAKER: exactly but it's soon yeah i really want to hear about all this even like a lot going on with cpus
[1:28:31] SPEAKER: lately yeah well we've had new new launches from amd intel hit yeah like earlier this week for
[1:28:37] SPEAKER: people who are listening and then the x3d the gamer focused amd cpus will land later this month
[1:28:43] SPEAKER: or next month i guess um but yeah we we appreciate everybody who supports the show and you can go to
[1:28:48] SPEAKER: patreon.com slash jackpot you get access to the tech pod discord you can get access to the patreon
[1:28:52] SPEAKER: exclusive episode i think the last month's patron exclusive episode was us talking about
[1:28:56] SPEAKER: you getting ready to go on this trip so like there's that and this will bookend nicely if
[1:29:01] SPEAKER: you're interested in that yep um and uh yeah we we um we appreciate all of our patrons but we
[1:29:09] SPEAKER: especially appreciate our executive producer and associate producer to your patrons so
[1:29:14] SPEAKER: on the executive producer front thanks to andrew slosky bunnyfiend david allen james kamek jordan
[1:29:21] SPEAKER: lippett twinkle twinkie and pantheon makers of the hs3 high speed 3d printer uh and at the end
[1:29:29] SPEAKER: of the month we give an extra special shout out to our associate producer to your patrons including
[1:29:34] SPEAKER: alihandra navarro andre m burke andrew dicey shoal dice arthur geese ben tallman brutal kerfluffle
[1:29:42] SPEAKER: eric eric klein felix kramer graham banks jad rita just associate wedge matt walker parentheses
[1:29:50] SPEAKER: walkman 8080 close parentheses mike ethridge nathan phelps sanchik kumar steve lynn thomas
[1:29:57] SPEAKER: shay and tom hilton thank you all so so much we appreciate you all yes we sure do and uh i guess
[1:30:03] SPEAKER: that'll do it for us this week uh we will have a patron episode up soon but we will see you all
[1:30:09] SPEAKER: uh next week with another episode of the tech pod that's right q a yeah send questions tech pod at
[1:30:15] SPEAKER: content.down it's where the questions get turned into answers or the questions seeking answers
[1:30:20] SPEAKER: uh channel on the discord both work see you all next time bye
