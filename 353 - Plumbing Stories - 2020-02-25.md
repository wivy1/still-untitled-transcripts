**Podcast:** Still Untitled: The Adam Savage Project  
**Episode:** 353 - Plumbing Stories  
**Date:** 2020-02-25  
**Duration:** 35m 28s  
Episode URL: https://www.youtube.com/watch?v=fRFSe9GsaiE

[00:00:00] Norm: This week's episode of Still Untitled is made possible with support from Microsoft Surface. Introducing the new Microsoft Surface Laptop 3. With its beautiful touchscreen, you'll experience stunning graphics with razor sharp resolution. Now available with a 13 and a half or 15 inch screen, and with the latest processors, there's no project the Surface Laptop can't handle. It's both light and powerful, so you can get more done on the go. Visit surface dot com slash laptop three to learn more. That's surface dot com slash laptop three.

[00:00:33] Will: Welcome to Still Untitled, the Adam Savage Project. I'm Will.

[00:00:35] Adam: I'm Adam,

[00:00:36] Norm: and I'm Norm.

[00:00:37] Will: Welcome back, lads.

[00:00:37] Adam: Thank you.

[00:00:38] Unknown speaker (Norm or Adam): Thank you.

[00:00:39] Will: Good day, mate.

[00:00:40] Unknown speaker (Adam, Will or Norm): No, no, no.

[00:00:41] Will: Other one. Oh,

[00:00:42] Norm: yeah.

[00:00:43] Will: Yeah. Sorry, Zoe Bell's going to come hunt me down now.

[00:00:45] Norm: Or take you on a safety journey through New Zealand air.

[00:00:49] Will: Did she do the? She does the...

[00:00:50] Norm: She's on the safety video.

[00:00:52] Adam: Yeah, yeah, yeah. Oh, I can't get that song out of my head from the New Zealand safety video.

[00:00:57] Will: I miss good safety videos. Songs.

[00:01:00] Norm: The New Zealand one, because you know the the safety video. Really was pioneered by Virgin America.

[00:01:08] Adam: The exciting and funny safety video.

[00:01:10] Norm: Yeah, well, they did one even before Jon M. Chu directed the famous...

[00:01:14] Will: They did the animated one.

[00:01:15] Norm: They did the animated one.

[00:01:16] Will: Yeah, with the bull.

[00:01:16] Norm: With the nun. It's very Red Bull style animation, if you know, like the Red Bull commercials.

[00:01:21] Will: Oh, you! Oh, you saw it. You definitely saw it.

[00:01:24] Norm: But that one broke ground for what was acceptable in terms of it being entertainment versus just pure safety.

[00:01:30] Adam: Well, it used to. So there used to be this great bit where on Southwest Airlines they would say, " To use your oxygen mask first, stop screaming."

[00:01:38] Norm: Really? What?

[00:01:39] Adam: Oh, yeah. No, no,

[00:01:41] Will: no. Unsubscribe.

[00:01:42] Adam: Really, they said it's important to put your mask on before your children, and if you have more than one child, choose your favorite.

[00:01:49] Unknown speaker (Adam, Will or Norm): Wow.

[00:01:49] Adam: They would say all these.

[00:01:49] Will: They used to be real cheeky.

[00:01:51] Norm: That sounds like a

[00:01:52] Norm: Fight Club thing.

[00:01:53] Adam: It used to be very funny, and then somebody complained, and Southwest had to stop being funny in their safety videos because people didn't think that that was funny.

[00:02:01] Will: There was like a Wired or a Business Insider article about the process. It was like a multi-year process to get that Virgin America the first one, the first video.

[00:02:08] Adam: Listen, I, I wrote to, uh, uh, uh, because the Lord of the Rings people did, uh, uh, what do you call it?

[00:02:17] Will: The New Zealand

[00:02:18] Adam: New Zealand

[00:02:18] Adam: Air Safety video. Uh, I have written to the New Zealand Air people and told them it's my lifelong dream to be in or to produce a safety video for them or anyone else who's listening.

[00:02:31] Will: Any airline?

[00:02:32] Adam: I feel like I was born

[00:02:33] Will: You'll do any of them.

[00:02:33] Norm: not Ryanair.

[00:02:35] Adam: I feel like I was born to record a safety video for an airline, and I think everyone listening is nodding right now because you agree.

[00:02:42] Will: You would be the best bad example ever. Like the way, like the you could be the guy carrying like four bags down the aisle of the airline as you're trying to get on the slide.

[00:02:50] Adam: If you can't show all the bad stuff happening, it could be like each each scene begins with me looking like Wile E. Coyote just after the bad thing has happened. Right, the top half of my body is charred.

[00:03:02] Will: Well, there's a there's the in Vegas. The how to go through security video is all of the Vegas acts as of like 1998 probably.

[00:03:12] Norm: Recently,

[00:03:13] Will: Oh, they redid it?

[00:03:13] Norm: Yeah, so the Star Trek stuff, the Klingons aren't there anymore. They do have skinny Penn and Teller.

[00:03:18] Adam: At any rate, we just got back from New Zealand.

[00:03:21] Adam: New Zealand was amazing.

[00:03:22] Will: Were your arms tired?

[00:03:23] Adam: Um, We we I don't know if you listened to the podcast last week.

[00:03:27] Will: I have not yet,

[00:03:27] Adam: but, uh, we had it. I, within 30 minutes of landing. I was putting a fire out.

[00:03:32] Will: Oh,

[00:03:32] Adam: when I landed in New Zealand last Friday, we talked about it on the podcast last week.

[00:03:36] Unknown speaker (Will or Norm): Oh boy.

[00:03:36] Adam: I literally was like driving with Richard Taylor. His trailer caught on fire. His wife showed up, threw me a fire extinguisher, and I jumped underneath and put a fire out on the trailer.

[00:03:46] Will: Wow!

[00:03:46] Adam: All within like an hour of landing in Wellington.

[00:03:49] Will: You're paying your way in the completely new way.

[00:03:52] Adam: No, just completely fulfilling

[00:03:52] Adam: every expectation about what it's like to hang out with me.

[00:03:54] Will: Yeah,

[00:03:54] Adam: and Richard,

[00:03:55] Will: I've never seen you put a fire out. I'm really disappointed.

[00:03:59] Adam: Um, It was great. We finished off with Friday drinks with the entire Weta workshop. And I mean, we just feel so welcome, and it's the third time we've used the office over there as a production office behind Richard's place and behind Richard's office. It just feels like family.

[00:04:15] Norm: It does. It yeah.

[00:04:17] Will: It seems like you guys. It's like going to camp almost.

[00:04:19] Adam: It is warm and fuzzy, you know. And you know, we walk through, and there's all sorts of amazing things going on, and like there, you know, in a special effects shop, I, I can't talk about a lot of what we saw because a lot of it's proprietary, uh, for different projects that Weta is working on. But I will say that there are a few places more entertainingly absurd than an effects shop in mid-production, because you will see just like lines of the most bizarre things you could imagine, whether it's babies or giant light bulbs, neither of which were at Weta, but you know that kind of thing.

[00:04:53] Will: I remember one time Norm and I went into a shop, and we just saw a line of heads in various states of exploding for a stop motion thing. Right, right. It's like the same head in in frame one, frame two, frame three, frame four. It's like

[00:05:06] Norm: ah. More so than any shop I've been in, and maybe that's, it's not indicative of the shops in the past, because Weta is a very sprawling place.

[00:05:14] Adam: Yeah, it's a rabbit warren.

[00:05:15] Norm: It is

[00:05:16] Adam: different shops and multiple buildings

[00:05:18] Norm: all the time. It's like multiple buildings connected. Like they bought this building, this building, and then open a door here, and things are being constantly rearranged. So it feels more like a college campus than anything.

[00:05:28] Adam: The thing. Go ahead. Sorry.

[00:05:29] Norm: And, and, you know, we visit a lot of shops in LA, and in LA, a lot of shops are big open warehouse spaces because they're storage, and you see everything in one or two rooms. You know, molds are happening here, paintings happening here, and because it's like a rabbit warren, and because it's like a university, it really feels like you know Hogwarts. Um,

[00:05:45] Adam: It also feels like the old Industrial Light and Magic because ILM was the same thing. It was George bought all the buildings on either side of Kerner Boulevard for like half a kilometer, and every building was one of ours. You know, that was the building you went to go get yelled at in. That was the building in which you had to push a million dollar model across the street to go film with it. Literally, you'd be pushing a million dollar model into traffic.

[00:06:08] Norm: And so there are different departments, you know.

[00:06:10] Adam: To get it over to where

[00:06:11] Norm: there are hundreds of people who work there, and

[00:06:13] Adam: Over four hundred people working.

[00:06:15] Will: Wow, really?

[00:06:15] Adam: Yeah,

[00:06:16] Norm: and it's and people are in their own groups, and so everyone has their own little stories, and we're getting glimpses of each of them every time we're in a different room, a different part of the shop. It's like we're popping into, you know, a Harry Potter movie.

[00:06:28] Will: Do they do they have like a family? One of the things I loved when we talked to David Chang years ago is I learned about the family dinner at restaurants where they sit down at the end of service and they talk about what went right and what did. I wonder, like, do they have a family dinner kind of equivalent there?

[00:06:39] Adam: They do a monthly Friday drinks,

[00:06:41] Will: okay.

[00:06:41] Adam: Uh, and, uh, at this Friday drinks, you know, they make announcements about how the company is doing. They celebrated the eighty-third baby born to a Weta staff member since its inception.

[00:06:52] Will: That's so cool.

[00:06:53] Adam: eighty-three babies.

[00:06:54] Norm: Yeah, wow.

[00:06:55] Adam: Yeah.

[00:06:55] Norm: We're at three.

[00:06:58] Adam: But you know, yeah, it's, it's that, um, I just love going there every single time. I leave glowing. I am just so ecstatic, and everyone is so gracious.

[00:07:08] Norm: We're renewed with mana, like it is rejuvenating. It's inspiring. It's humbling, for sure.

[00:07:13] Adam: Oh my god,

[00:07:14] Norm: it's humbling to be there, uh, and it's really great to hear that many of those people feel the same way.

[00:07:19] Adam: Um, and

[00:07:19] Norm: after we leave,

[00:07:20] Adam: you know,

[00:07:20] Will: that's awesome.

[00:07:21] Adam: We love sharing all the stories about how difficult and fun everything is. I got to do some. We shot some pieces of like I got to work with Jules, their head painter, on a rapid fire. What was that? Twenty five minutes tops.

[00:07:34] Norm: It was almost an hour.

[00:07:36] Adam: Was it almost an hour? It felt like twenty five minutes.

[00:07:38] Norm: You had some, and that was the thing. Like we went with the plan because you've watched our people out there have watched our video series. Every time we've been to Weta, it's different. The first time we went twenty sixteen, it was very specifically we're covering these film projects they were working on. It was Ghost in the Shell. We had you embedded with Peter Lyon to make a sword essentially a two day one day build there, and then the last time we went in twenty eighteen, it was a full week for a project that we initiated, which was the short film

[00:08:05] Adam: Farewell to Arms.

[00:08:06] Norm: Very different parameters, right? This time it was. Under the umbrella of a project they're working on, but we said specifically we want Adam to get his hands dirty. We want you getting involved, and they love it when you are working with them and not just interviewing them.

[00:08:20] Adam: And it's very

[00:08:20] Norm: And you got involved.

[00:08:20] Adam: I did get involved. It's very entertaining because each time they give me a person who hasn't worked with me, of course they plot out themselves that I might be an idiot because they haven't seen me actually work. So they plan to get the thing done in case I turn out to be useless. And then each time I, spoiler alert, I turn out to be useful, and that's very entertaining.

[00:08:41] Will: Very nice. It's a good feeling too, right?

[00:08:44] Adam: We all like being handy.

[00:08:45] Will: It turns out being useful is good.

[00:08:47] Adam: Hey, I watched a movie on the way back.

[00:08:48] Unknown speaker (Will or Norm): What'd you watch?

[00:08:48] Adam: Uh, I watched Ready or Not.

[00:08:51] Will: Oh, this is this is a movie, uh, we talked about a little bit a few weeks ago.

[00:08:55] Norm: Samara Weaving, um, and

[00:08:58] Adam: playing Margot Robbie.

[00:08:58] Norm: They are from the same like mold. They're, they're, they're, Jamie Priestley or and yeah,

[00:09:03] Will: Jaime Pressly,

[00:09:04] Norm: Jaime Pressly Margot. Yeah,

[00:09:05] Adam: What, what was her name?

[00:09:06] Norm: Uh, Samara Weaving. She is Hugo Weaving's niece.

[00:09:09] Adam: Ah, she's. Terrific in the film. She has to carry a lot of. She has to carry the movie, and she does. And, uh, it's a it's a movie about, um, a woman marrying into a rich family that has a very spoilers. I think this is a movie totally worth

[00:09:25] Will: The, the the trailer spoils the whole thing,

[00:09:27] Adam: right?

[00:09:27] Will: You know what's happening.

[00:09:29] Adam: The rich family have a deal with the devil, and they have to conduct a ritual every time someone new is introduced into the family. And shit goes really weird and south.

[00:09:38] Will: Yeah, your typical billionaire deal.

[00:09:39] Adam: It's a game. It's a lethal game of hide and seek that turns into much darker, even darker,

[00:09:43] Norm: and great cosplay too in the bloody wedding dress with the the the bandolier

[00:09:48] Adam: with the bandolier and the big elephant killing shotgun. Yes, Um, the movie has, uh, the movie is entertaining. Uh, it overstays many scenes. Overstay their welcome. I felt it.

[00:10:01] Will: So, so when I saw the trailer for this, I assumed it was going to be kind of your Saw, Hostel torture [unclear: or anything].

[00:10:06] Adam: Oh yeah,

[00:10:06] Will: and it's not at all that.

[00:10:07] Adam: No, it's a comedy. It's a horror comedy.

[00:10:08] Will: It's a dark comedy. Yeah,

[00:10:10] Adam: more akin to like very bad things.

[00:10:12] Will: It it was there's a very very much a very bad things it's it's I think it's less dark than very bad things it's more cartoony

[00:10:18] Norm: and she was also in a very similar movie called The Babysitter yeah where she—although she's one of the murderers but also very tongue in cheek horror comedy

[00:10:26] Adam: so I'll say that while I found the film entertaining it has a late third act turn in which somebody who's been unassailably good up till that moment turns immediately bad on a dime

[00:10:41] Norm: and you didn't like that

[00:10:43] Adam: they didn't earn it just full stop the script didn't earn that moment and it like it washed me out of the film

[00:10:49] Will: I know it's been a while since I saw the movie

[00:10:51] Adam: here comes the spoiler her fiance her fiance turns on her she's in here he says when he realizes he's about to lose her

[00:10:57] Will: oh yeah

[00:10:57] Adam: he didn't tell her that his family has a deal with the devil and he knows now that that will make her go away and when she does he will die

[00:11:04] Will: yeah

[00:11:06] Adam: and I, it just he didn't he like he was not set up in any way to be selfish or venal.

[00:11:13] Will: Um, I felt like it was foreshadowed in the early parts of the film, but not like like the thing is I wasn't paying attention to the fiance at all because I thought he was one of the least interesting characters in the movie.

[00:11:23] Adam: Bingo.

[00:11:23] Will: Adrien Brody, uh, his character,

[00:11:26] Adam: Adam Brody,

[00:11:26] Will: Adam Brody,

[00:11:27] Adam: Adam Brody,

[00:11:27] Will: Adam, not Adrien Brody

[00:11:28] Will: from the OC, from the OC, yeah, the OC guy.

[00:11:31] Adam: I have never watched it.

[00:11:32] Will: You were the yeah, you're the wrong age.

[00:11:33] Adam: The bigger guy?

[00:11:34] Norm: No,

[00:11:35] Will: no, no. The the, the, brother-in-law.

[00:11:36] Adam: brother, the brother,

[00:11:38] Adam: the kind of the bearded brother.

[00:11:39] Will: No, the other one, the the younger, the attractive, dark haired, dark curly hair.

[00:11:47] Adam: Yeah, yeah,

[00:11:45] Will: he has a beard.

[00:11:47] Adam: Yeah, yeah,

[00:11:47] Will: I couldn't remember.

[00:11:47] Adam: He does. He's married to the, um, Olivia Munn stand-in. It was like every actor.

[00:11:52] Will: It was a lot of character actors in this movie.

[00:11:54] Adam: There was a lot of character actors who looked like get me an Olivia Munn type, is what it felt like somebody was saying.

[00:11:59] Will: I thought his performance was really good.

[00:12:01] Adam: I did too.

[00:12:01] Will: I thought he was very like he he he he was the one I was I was watching him and Samantha Samara weaving

[00:12:07] Adam: Mm-hmm.

[00:12:07] Will: pretty much exclusively. Like that's that's why I cared about the the patriarch and patriarch were spectacular. You didn't think so?

[00:12:13] Adam: No, I loved Andie MacDowell. Andie MacDowell was fantastic.

[00:12:16] Will: Always good.

[00:12:17] Adam: Andie MacDowell, yeah,

[00:12:19] Norm: as the mom.

[00:12:19] Will: Yeah, the mom,

[00:12:21] Adam: the mom. Anyway, I enjoyed the movie. I found it light and fun. It didn't earn its turn. Yeah, it didn't, it didn't earn that third act turn, which upset me.

[00:12:27] Norm: And if you like horror comedy, what we just spoiled does not ruin the enjoyment of the horror comedy elements of that movie.

[00:12:34] Adam: No, because you turn up to see how bad things are going to get, and also it's surpassingly gory. This movie is a hard R.

[00:12:40] Norm: Yeah, yeah, it's fun gory, like it's schlocky, yeah,

[00:12:42] Will: like um, it's not like.

[00:12:44] Adam: But if you want fun gory, watch Free Fire. That's the

[00:12:47] Adam: movie to

[00:12:48] Adam: watch.

[00:12:48] Norm: We've talked, yeah,

[00:12:49] Adam: we talked about it. Cillian Murphy,

[00:12:50] Adam: Sharlto Copley, Brie Larson, and Armie Hammer in a one-room shoot 'em up.

[00:12:55] Will: Oh, that sounds great.

[00:12:56] Adam: Between the IRA and the Mafia in the nineteen seventies.

[00:12:59] Will: That sounds perfect.

[00:12:59] Norm: Directed it, yeah.

[00:13:01] Adam: Who's that?

[00:13:01] Norm: Ben Wheatley. Ben Wheatley.

[00:13:03] Adam: Ben Wheatley

[00:13:03] Norm: was the guy who, uh.

[00:13:05] Adam: Wait, is he an actor?

[00:13:06] Norm: No,

[00:13:06] Adam: okay.

[00:13:06] Norm: But sounds like a name of the actor.

[00:13:09] Adam: He's. It's beautifully directed. It's really, really fun, and it's, uh, it like yeah.

[00:13:15] Norm: Anyway, uh, Knives Out was not on the flight,

[00:13:18] Adam: Not, not, which I still haven't seen because I'm an idiot. And was not on the flight.

[00:13:22] Norm: We maintain it's a good pairing if you have opportunity to watch Knives Out and Ready or Not. Actually, they're.

[00:13:26] Will: I mean, one is not Knives Out is a much better film.

[00:13:29] Norm: Oh, sure, sure.

[00:13:29] Will: Across the board. It is not. It is not a gory movie at all. So, but it is the same kind of like.

[00:13:35] Norm: Yeah.

[00:13:36] Will: There are there are there is a

[00:13:37] Norm: themes and big houses that

[00:13:40] Will: crazy rich people, big houses, bad things happen.

[00:13:43] Norm: It's always fun to come up with good pairings of movies that don't always feel like they would.

[00:13:46] Will: One of my favorite games

[00:13:47] Norm: fit together. Um, New Zealand Air, great.

[00:13:50] Adam: New Zealand Air is the best

[00:13:52] Norm: entertainment system. Uh, It's free Wi-Fi,

[00:13:55] Adam: free Wi-Fi

[00:13:56] Norm: What? for international flight.

[00:13:57] Adam: I don't know if you found this, but on the way back, the Wi-Fi was fast.

[00:14:00] Norm: Well, so you slept for a lot of the flight.

[00:14:03] Adam: I slept for seven hours.

[00:14:04] Norm: So on the way there, free Wi-Fi worked the whole time. Great,

[00:14:06] Adam: Yeah, but but slow as molasses.

[00:14:08] Norm: Slow.

[00:14:08] Adam: Felt like fourteen four dial up.

[00:14:09] Norm: We were on the same flight back, Adam.

[00:14:10] Adam: Yeah.

[00:14:10] Norm: And the Wi-Fi was off for the first two hours.

[00:14:14] Adam: Ah. Okay.

[00:14:14] Norm: And they have a system where they can not only do a PA announcement for everyone, but they can also do pop-ups. And so there was a pop-up that came on that says, " Sorry, the Wi-Fi is down." And I was like, " Oh my god, I I prepared for this flight with the assumption that Wi-Fi is going to be up. I need my Wikipedia while I'm watching these movies. I need to go to my deep dives. How am I going to pass 11 hours of time? But turns out they can. The pop-ups are they can whoever is running them can type into a keyboard. And so two hours into the flight, when everyone was asleep after the supper service, pop-up. I fix all caps. I fixed the Wi-Fi exclamation exclamation mark. Please be gentle exclamation mark. I was like, I need to grab my phone and take a picture of this because because I could tweet it.

[00:14:58] Will: Oh yeah, that's so good.

[00:14:59] Will: Did it go away?

[00:14:59] Norm: It went away. It popped away.

[00:15:00] Unknown speaker (Adam, Will or Norm): Oh no!

[00:15:00] Norm: I love that you know right. And and oh, that's why, but it was fast because no one realized the Wi-Fi was back on.

[00:15:06] Will: Do you think they rebooted the router?

[00:15:08] Norm: Maybe.

[00:15:09] Will: Yeah. What's what's the plane Wi-Fi fix solution?

[00:15:11] Norm: Not all heroes wear capes.

[00:15:12] Adam: Norm and I we had a meal in Auckland Airport. We had a two two hour layover in Auckland before leaving, and we shared a meal there. And by the way, popo dumplings.

[00:15:24] Will: Oh man!

[00:15:24] Adam: In the Auckland Airport, I had some pork and shrimp dumplings with a a pork steamed pork bun. Those dumplings were legit, as good as any dumplings I've ever had. They were stellar.

[00:15:38] Will: How they set up the kingdom of?

[00:15:39] Norm: I didn't have them.

[00:15:40] Will: Oh, you didn't have them?

[00:15:41] Norm: I had a

[00:15:41] Norm: burger.

[00:15:41] Adam: They were stunning. I actually was eating them so assiduously that it didn't occur to me to tell Norm they were amazing until I was done, and then I was like, " Norm, these were amazing, and I should have given him one." It just didn't even occur to me because I was just plowing them into my face.

[00:15:54] Norm: You know, you're, you said I'm in the middle of composing a tweet about how good these dumplings are. I don't think I should share where we are right now.

[00:16:01] Adam: I literally was going to send it while I was sitting there, because this is something else. I'm way more famous in New Zealand than I am here in the United States.

[00:16:09] Norm: Really?

[00:16:09] Adam: Oh yeah. Everywhere I was going in Wellington, there were people like, " Oh, you're going to fly more planes with Peter Jackson." Everyone is

[00:16:16] Norm: excellent.

[00:16:16] Adam: It's just, yeah, it was very, very sweet. Oh, but because I'd eaten, I did not eat on the flight home.

[00:16:23] Norm: Oh.

[00:16:23] Adam: And the flight attendants are again New Zealand Air flight attendants are just stellar. But they get a little wigged out when you eat when you take nothing.

[00:16:32] Will: Oh yeah.

[00:16:33] Adam: Right when you're like, I'll just have a piece of garlic bread, bread please, and the tea is fine, and I don't even need tea. I just had water for most of the flight, and they get they get very huffy and nervous about you when you don't eat anything.

[00:16:44] Norm: Well, I think they realize for 11 o'clock flight or 11 hour flight, some people if they don't take the food, they get will get cranky later on, and it becomes a problem for them.

[00:16:52] Adam: Oh my goodness! Right, hangry customers must be an awful part of the job.

[00:16:56] Norm: Yeah.

[00:16:56] Will: Long long haul international flight attendants are

[00:16:59] Norm: You gotta keep them fed.

[00:16:59] Will: definitely yeah the don't wear capes heroes of our of our time.

[00:17:03] Adam: We've just another shout out. I don't know if it's even still up, but customershaming dot com, which is a Website where flight attendants share their own horror stories, um, and pictures of the nastiest toenails that people stick into the windows, and

[00:17:17] Norm: Yeah.

[00:17:18] Will: I, there, there used to be a really great, it's probably up, but it's a pilot blog that tells like the pilot horror stories.

[00:17:23] Adam: Yeah,

[00:17:24] Will: it's it's the place, it's the place of the famous, um, I think it was a FedEx flight that they had to emergency land because somebody dropped dumped the cooler with dry ice instead of regular ice into the chemical toilet.

[00:17:36] Adam: Oh my god.

[00:17:36] Will: Yeah, and it like foamed up the entire back of the plane, uh, because the the chemical toilet stuff. But anyway,

[00:17:43] Adam: yeah,

[00:17:43] Will: I love those kind of industry specific nightmare blogs. Yeah, they're really good.

[00:17:49] Norm: Before we continue on with the show, I want to let you know that support for Still Untitled comes this week from Microsoft Surface, introducing the new Microsoft Surface Laptop 3. With its beautiful touchscreen, you'll experience stunning graphics with razor sharp resolution. Now available with a 13 and a half or 15 inch screen, and with the latest processors, there's no project the Surface Laptop can't handle. It's both light. And powerful, so you can get more done on the go. Visit surface dot com slash laptop three to learn more. That's surface dot com slash laptop three. Now back to the show. Speaking of plumbing,

[00:18:26] Will: yeah, you guys did. Like, I came in to a scene.

[00:18:31] Adam: You came in at eleven to do this podcast, and we were like, " We're gonna have to pause." And you were like, " I have a hard out.

[00:18:37] Will: I am such a pain in the ass."

[00:18:39] Adam: No, no, that's that's we have all done this, and you said today I have a hard out, and we said this plumbing repair should take ten minutes,

[00:18:45] Will: and I somewhere

[00:18:46] Adam: in your head,

[00:18:47] Will: I thought I've heard this before.

[00:18:49] Adam: And then, how long did it take?

[00:18:49] Will: About eight minutes. Yeah. You guys, you guys really hammered through it. Um, I, plumbing repair, plumbing is one of those things; it's a nightmare. Like you can get into real trouble in no time.

[00:19:01] Adam: Well, the thing is, is that it's deceptively simple, but the stakes are often quite high. The stakes of a mistake.

[00:19:08] Will: are incredibly high.

[00:19:09] Adam: They get wet and wild in a hurry.

[00:19:12] Will: Well, and and like your minimum. Cost of a of a of a expert emergency repair for a plumber in the Bay Area is between five hundred and a thousand dollars, in my experience. Yeah,

[00:19:21] Adam: it's it's real. Yeah,

[00:19:21] Norm: and your experience may vary.

[00:19:23] Will: Yeah,

[00:19:23] Norm: your success with with those people that you call.

[00:19:25] Will: Yeah,

[00:19:26] Adam: and you know, it's all about having the right parts.

[00:19:28] Unknown speaker (Will or Norm): Yes,

[00:19:28] Adam: and lining them up. So, but there is always something you don't expect. Like you know, you'll turn off the water, and you think it's only going to be for ten minutes. But as you are trying to undo the spigot that you are about to replace on the system, the nipple holding it on cracks, and all of a sudden you have to pull out the welder and weld the thing to that, and then spray some Kroil on there and let it soak for an hour, and then you can hit it with a mallet and slowly you start to like I've been there with all of that stuff, and that's what you pay an expert for. They can see those mistakes before, before you cause them, and they also go to the hardware store once, whereas every home plumber goes to the hardware store like seven times for any repair, no matter how small.

[00:20:09] Will: Well, so my all-time worst—I've made a bad mistake plumbing error was the night before Thanksgiving. We had. I think twenty people coming that year, so we had a table set up in the backyard for a bazillion people, and we, an unnamed person in our family, ran a bunch of potato peels down the garbage disposal, and the potato.

[00:20:30] Adam: Is that bad?

[00:20:30] Will: It's yeah, don't don't put potato peels down the garbage disposal.

[00:20:33] Adam: Okay, they don't

[00:20:34] Will: sweet potatoes are fibrous and they get they get and

[00:20:37] Adam: I know limes limes are an absolute nightmare.

[00:20:39] Will: Look, this here is the the secret tip.

[00:20:42] Norm: Why limes and not a bunch of citrus?

[00:20:44] Adam: I don't know limes are

[00:20:45] Will: lime peels are

[00:20:45] Adam: lime peels are

[00:20:46] Adam: crazy fibrous.

[00:20:48] Will: So the number one tip that I have about plumbing is don't ever use an effing garbage disposal because they're bad for the environment. They're bad for the septic system.

[00:20:56] Adam: Okay,

[00:20:56] Will: and they're they're they clog up your pipe. So

[00:21:00] Adam: so they use potato peels.

[00:21:01] Will: I had finished all of my pre night cooking. I am in the shower and I am sitting there. I am like, wow, that's weird. This potato peels coming out of the emergency overflow drain of the tub.

[00:21:10] Adam: Oh.

[00:21:11] Will: Oh.

[00:21:11] Adam: Oh.

[00:21:12] Will: Oh, so. You know, I go get the plumbing snake as one does.

[00:21:16] Adam: Is it long enough? Is the question.

[00:21:18] Will: It's eleven o'clock at night right now. This is where we're starting this moment. We have one bathroom in the house. We have twenty people coming the next day. So, like, I'm thinking, if I don't fix this, we're going to cancel Thanksgiving for twenty people. So, or we'll have to move someplace else. So we, so I get the snake. I snake nothing. No love.

[00:21:32] Adam: Yeah.

[00:21:32] Will: So I'm like, okay, maybe I can get it from the garbage disposal side. I take the flange off the garbage disposal, and I hear a crack. And the you know the flange that holds the outflow pipe on the garbage disposal just snapped off.

[00:21:43] Adam: Yeah.

[00:21:43] Will: And it's the only thing. It's the thing that makes it seal. So I get the pipe in. I get the snake. No, no love. I pour the Drano at this point. I'm desperate, right? Whatever I can do. I go back and I start snaking further, and I'm like, literally, I'm I'm at the holding the end of the snake with a with a vice grip to turn it because the the I've run out of line, and I feel it bite, and I'm like, oh, thank God. So I finally pull it out, but then I have to fix the leaky garbage disposal in the only kitchen sink we have, and the only way we can do dishes. It was a disaster. The upshot is,

[00:22:14] Adam: at that point, you have to buy a new garbage disposal.

[00:22:16] Will: But it's four o'clock in the morning at this point on Thanksgiving Day.

[00:22:19] Adam: Home Depot,

[00:22:19] Will: really? They open twenty four.

[00:22:22] Adam: They some Home Depots are open twenty four seven.

[00:22:24] Will: I so what I did.

[00:22:25] Adam: I had a job once where I went to Home Depot at two in the morning. Again at four in the morning.

[00:22:29] Will: Oh God! I I just I got the epoxy, the the the two sided stuff.

[00:22:33] Adam: Oh yeah,

[00:22:33] Will: and jammed the flange back in there, and then glued the gasket into place, and it's still not leaking. So,

[00:22:39] Unknown speaker (Adam or Norm): oh wow,

[00:22:39] Will: yeah, that was two years ago. Now

[00:22:41] Adam: the the about, God, at this point, twenty five years ago, I was living down at the end of Hunters Point on Yosemite Street. Um, now denizens of Hunters Point will know Yosemite is where the police station is. There was no police station there back when I lived there. Um, there was no. I think there's even a big box store down there. No, but I was in this mattress factory, and

[00:23:05] Will: like you lived in the mattress factory.

[00:23:06] Adam: I lived in a loft in the in a big open space.

[00:23:09] Will: Yeah,

[00:23:09] Adam: twenty two hundred square feet, and it wasn't meant for living. So. There was just a water pipe sticking out of the floor, so I attached that water pipe and I brazed it to a water heater, and I lived out my fantasy of living inside the movie Diva, which I don't know if you've ever seen. And I had a bathtub in the middle of my living room.

[00:23:26] Will: That sounds awesome.

[00:23:27] Adam: It was it was fabulous. And then after we'd been there about a year, the heating element blew out, and I I actually knew enough to test its continuity, see that it'd blown out. I turned off the water. I removed the heating element, spec'd the one that I needed to get, and planned to get it the next morning. And what I didn't know was that while I thought I'd shut the water off, I hadn't.

[00:23:53] Will: Oh, you turned it on?

[00:23:53] Adam: I know I turned it off mostly, but it slowly filled the water heater and then leaked out the hole where the heater wasn't because I had pulled it out, and I woke up to two inches of water in my entire loft. But it's okay because I live above a clothing warehouse.

[00:24:11] Will: Oh no!

[00:24:11] Adam: You know, Cut Loose clothing over here on Valencia. They used to have their storage warehouse. Underneath my loft space,

[00:24:19] Will: at least it absorbed all the water.

[00:24:21] Adam: Oh my god! I I mean, it was like so. I am using one of those, you know, slop mop buckets.

[00:24:28] Unknown speaker (Will or Norm): Yeah,

[00:24:28] Adam: and I think we went through forty to pick up all the water.

[00:24:31] Will: Two thousand square feet of two inches of water—that is an unbelievable amount of water.

[00:24:34] Adam: And running into the like, I'm shoving rags to keep it from running down the hole into the clothing. And they're banging on the door, and we're like, " We're sorry." Oh, that was that was

[00:24:42] Will: that's a bad day.

[00:24:43] Adam: I still have a picture of me and my ex brother in law standing with like rags on our heads and shirtless in this terrible aftermath.

[00:24:52] Will: God, what a nightmare!

[00:24:53] Adam: But this is this is home plumbing. We we we all have those stories.

[00:24:57] Will: We once upon a time we had a Thanksgiving. All of our stuff happens at Thanksgiving. We had a Thanksgiving where we were the upstairs unit in a two building two bedroom loft, and the downstairs neighbors had gone to their families for Thanksgiving. But something they had left something in the sink, or something. Shit runs downhill.

[00:25:14] Adam: Yeah, yeah, it does.

[00:25:15] Will: And and our dishwater from Thanksgiving aftermath was coming up their sink. And it just it it was a disaster. It was it was in fairness that was way worse for them than it was for us. We weren't, we didn't get along super well with the downstairs neighbors after that. I can't. I don't understand why. Really

[00:25:33] Adam: hilarious.

[00:25:33] Will: Yeah, plumbing is great.

[00:25:35] Adam: What else is going on?

[00:25:37] Norm: Oh, Well, you're doing more travel. I mean, this is gonna be a crazy month of travel.

[00:25:40] Adam: It is gonna be crazy month.

[00:25:41] Norm: You're going to C2E2

[00:25:43] Adam: this weekend. This weekend, yeah, where thing two lives.

[00:25:46] Will: Yeah,

[00:25:46] Adam: Um, and then I will be sliding back through Denver, where thing one lives, because, um, my boys turned twenty one recently. Yeah, Um, very exciting.

[00:25:58] Will: Wow, they were.

[00:25:59] Adam: I know

[00:26:00] Will: thirteen. I think when we first met them.

[00:26:03] Norm: Yeah, math checks out.

[00:26:04] Will: Yeah, that's amazing.

[00:26:05] Adam: 2014,

[00:26:05] Norm: 2012, yeah,

[00:26:07] Will: 2012.

[00:26:07] Adam: Oh, in 2012, yeah, they were thirteen years old. Yeah, right.

[00:26:10] Norm: Yeah, wow. And then you will be. We're not doing a like the most. Most of the team aren't going, but there will be something. To reveal,

[00:26:18] Adam: there will be something to reveal,

[00:26:19] Norm: and we'll have we have videos related to those. I mean, it's, I'm sorry for being so cryptic, but you will not be disappointed, and

[00:26:25] Adam: you will not have to wait too long.

[00:26:26] Norm: And you won't have to wait too long. You will see some cool stuff.

[00:26:28] Will: This weekend?

[00:26:28] Norm: Yes, that is this weekend. Hey, also, like, I completely forgot because we were in New Zealand for a whole week. But literally, the Thursday, the morning before you flew out,

[00:26:39] Adam: we buried the lead

[00:26:39] Norm: that we went backstage to Hamilton.

[00:26:42] Will: That, that video is incredible. It was really fun.

[00:26:45] Norm: So we we did four videos. I can even tell you what they are. And the first one that's out, Adam got to chat with the prop master, and you got

[00:26:54] Adam: so much.

[00:26:54] Norm: When they when we were chatting with the press people, we're like, oh, we want to cover Hamilton. And, of course, the first thing we think are costumes, and we'll be doing something with that eventually. But they're like, what about props? And in my head, I'm like, Hamilton isn't known for props, but yet there are so many

[00:27:10] Adam: tons of props.

[00:27:11] Norm: There are so many props in that show.

[00:27:13] Adam: Cabinet of just the paper props.

[00:27:15] Norm: That was the coolest thing.

[00:27:16] Adam: I know. I know that was awesome.

[00:27:17] Norm: in there in the cabinet. There's a shot of it in the video. Like they have, they have to remake the paper, right? And the guy's like, " We have specifically sixty-five sheets of the Reynolds pamphlet,

[00:27:26] Adam: And they chose, and they chose all these specific pieces of paper. Like the the the when she burns the letter,

[00:27:31] Will: yeah,

[00:27:31] Adam: that's a specific type of paper, and they burned tons

[00:27:34] Adam: and tons of different paper,

[00:27:35] Norm: because they know for duration of burn the song how how much they could burn because the the actress has to be holding it. It's the one piece that actually lights on fire on the show.

[00:27:44] Will: Wow,

[00:27:46] Adam: it's the only real candle in the show. So that's not the lead that I thought we were burying. Well, yeah, and we have three more of those videos.

[00:27:50] Will: Yes, just the ropes. There are hundreds of ropes, and they're all specific.

[00:27:54] Adam: Well, and that's also that's a modern rail. That's a modern, wonderful theater rail.

[00:28:00] Norm: The dueling pistols.

[00:28:01] Will: Oh yeah,

[00:28:02] Adam: yeah, yeah. Yeah, yeah. I got to see the dueling pistols.

[00:28:06] Norm: Yeah,

[00:28:06] Will: that's so cool.

[00:28:06] Adam: Um, No, the lead that I was thinking we were burying, which because we also announced on Thursday that I am the creative director of Silicon Valley Comic Con, heretofore in the future known as SiliCon.

[00:28:15] Will: Yeah, I think it's a great name.

[00:28:18] Adam: I do too. I do too.

[00:28:19] Will: It took a minute for me to like attach to it and be like.

[00:28:22] Adam: No, no, okay, yeah, yeah, that works. Here's the here's the brain process. You see, you hear Silicon Valley Comic Con is changing its name, and you think, okay, how could that go? And then you hear SiliCon, and you're like, hmm, it's very much the sort of first thing most people would think of, which means that could it actually be good? It is actually good. It's actually communicates. It works. It tracks. It scans. Let's do it. And so, yeah, I had the same thing. I thought, oh, no, that actually is great.

[00:28:49] Will: No, I yeah, ah, yeah, okay,

[00:28:51] Adam: um, I'm in. So, uh, there will be ongoing announcements and coverage of this as as we progress towards the October the the the latter half of October dates for SiliCon. You can sign up right now, and we'll put some links below. Um, but for the broadest picture, um, one of the reasons we've been going every year since its inception is because SiliCon, in addition to the wonderful pop culture tracks and the celebrity panels that you can expect at any given con, they've also, uh, put a heavy focus into maker culture and tech and also, uh, science. And this isn't to say that other cons don't, uh, also prioritize those, because it's one of the great things about the cons is that bleed through of all of our favorite things in one place.

[00:29:38] Norm: You just listed some things, some topics that we are well very interested in.

[00:29:41] Adam: Exactly.

[00:29:41] Norm: Science and making [unclear: Norm to your newsletter],

[00:29:44] Adam: and so just suffice to say, I'm very excited about putting together some really specific panels on pop culture, on science, on making, on technology, uh, in order to really widen and deepen the con experience with all the stuff that we love about it.

[00:29:58] Norm: I think that's that's the big story here. Is not just that you're putting your name on it and you're going to be there for the duration and have a bigger presence as creative director. You know, you're going to be actually initiating these tracks.

[00:30:10] Will: You're programming,

[00:30:11] Adam: yes, and and that's that's it's really exciting because we have have point of view and we, you know, we I feel we feel really simpatico with the entire team of SiliCon. We have the same aims. It's that's just feels like we're firing on all cylinders. So I'm really excited what this year portends for that.

[00:30:30] Will: That's so awesome!

[00:30:31] Adam: Yeah,

[00:30:31] Will: that's rad.

[00:30:32] Adam: And again, like, there's a lot more to to say about it, but I think that's enough.

[00:30:36] Norm: But I think people out there, if you, you know, one, you should go. But if people want to pitch us things, feel free to reach out. We're open ideas for for tracks and things.

[00:30:45] Will: What's the best way to do that? Twitter,

[00:30:47] Norm: probably. Twitter, email,

[00:30:49] Adam: email. Um, one of the things is very specifically within maker culture. I want a deeper dive into the sharing the sharing economy that is maker culture. As specific,

[00:31:00] Will: what on earth is that?

[00:31:00] Adam: Was that my Siri? Oh, Siri, somehow I said something that she thought. I didn't. Stop! Stop! Um. Anyway. Uh. Yes, maker cosplay the open source sharing economy of the make of the cosplay community and the maker community. I'm like I love when those two intersect on this deep level, and we plan to help.

[00:31:23] Will: So you want to see some places where people could come and take the. The hard-earned lessons and share them with other people so that they are less hard-earned.

[00:31:29] Adam: Yeah, because what have we been doing the last few years, but just covering wonderful innovations by all sorts of different people working in their shops across the country. It's time to like codify more and more of that of that sharing of information.

[00:31:42] Norm: I love that. Yeah. Before we wrap, I want to give one more shout out. We were there in Wellington for a full week, and we only got basically one day—the last day before we left—to do a little bit of walking around. And you know, we stayed at a hotel that's very close to the Te Papa Museum, and the Te Papa Museum is highly recommended, as always. They have the scale of our War Gallipoli exhibit, which is, I believe, running at least through 2023.

[00:32:03] Unknown speaker (Adam or Will): Yep.

[00:32:03] Norm: This is Weta putting together these six large-scale 2.4x humans and diorama pieces about the the soldiers and the people who participated in Gallipoli. But they also have this exhibit running through March 8th. That's about Alice in Wonderland. It was created by the Australian Center for Moving Image, basically the Aussie version of the New York Museum of Moving Image, which any Institution that celebrates, you know, cinema and television and computer games, and this is about Alice in Wonderland. It's called Wonderland. It's there through March eighth. Highly recommended.

[00:32:38] Will: Is it Any particular version or all versions?

[00:32:39] Norm: It's forty different portrayals of Alice through the history of cinema, because the story of Alice predates cinema, and it's surreal. It's interactive. They have projection mapping, and it's at the Te Papa till March eighth.

[00:32:54] Adam: How amazing!

[00:32:55] Will: I hope it travels.

[00:32:56] Norm: Yeah, it's been to a couple places, but I hope it comes stateside too.

[00:32:59] Will: That would be amazing.

[00:33:00] Norm: Yeah,

[00:33:00] Adam: yeah. And to my friend Peter Beck up there in north of the North Island, Peter, I am sorry I did not get up to see your rockets this time. I really plan to carve out an extra couple of days the next time I come to New Zealand. I promise I will come.

[00:33:15] Norm: We'll be back.

[00:33:16] Adam: Yes, we will be back. We will be back before too long.

[00:33:18] Will: Just relocate tested to to.

[00:33:21] Adam: I think we need the satellite office. I think it's totally clear to everybody.

[00:33:23] Will: Look, I am available. I can go down there if you want. Just say the word. We'll pack up the family.

[00:33:28] Adam: Oh yeah, also Weta is a dog friendly workplace. Times a million, and so I got lots of dog love, including Richard Taylor's new beautiful dog Lottie, who I made best friends with.

[00:33:40] Will: Good snuggles,

[00:33:40] Adam: yeah. She she spent a lot of time just hanging out on my lap, and yeah.

[00:33:45] Norm: Well, what's going on new in your world?

[00:33:47] Will: Uh, new episode of Tech Pod is out this week. It's a Q and A episode. We've done we we made a ranking of Windowses over the last two weeks. Windowses. We started with Windows three point oh, maybe three point one, and went all and and like talked through like it's it was interesting to go through and talk through twenty five thirty years of of of you know what was the dominant operating system for a really long time, still is,

[00:34:09] Norm: yeah,

[00:34:09] Will: and and how things have changed and watch what's gotten better and what's gotten worse. As Microsoft went from selling a packaged good that you can install on your computer to shipping a software as a service that is, you know, maybe not as awesome as just buying a thing and maybe not being the customer. So anyway, you can find that at techpod.content.town.

[00:34:28] Norm: Cool. All right, we'll be back next week. Thanks for listening.

[00:34:30] Will: Thanks, everybody.

[00:34:32] Norm: Hey, everybody. Norm here. Thanks for listening to the podcast. And before I let you go, I need your help. Tested and Still Untitled needs your help in order to keep this show going. We need the help of great advertisers, and we want to make sure those advertisers are the ones you actually want to hear about. So please go to podsurvey dot com slash untitled and take a quick anonymous survey that will help us get to know you better. That way, we can make sure that we're bringing on advertisers who are relevant to you. And once you've completed this quick survey, you can enter for a chance to win a one hundred dollar Amazon gift card. Terms and conditions apply. Once again, that's podsurvey dot com slash untitled. Thank you so much for listening to the show. Thank you for your continued support. Really appreciate you filling out this survey, and we'll see you next time.
