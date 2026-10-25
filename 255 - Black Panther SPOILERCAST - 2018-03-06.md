**Podcast:** Still Untitled: The Adam Savage Project  
**Episode:** 255 - Black Panther SPOILERCAST  
**Date:** 2018-03-06  
**Duration:** 31m 57s  
Episode URL: https://www.youtube.com/watch?v=nfjS1_-AQgo

[00:00:00] Norm: This week's episode of Still Untitled is brought to you by Google's Cloud Platform. Looking to move to the cloud? Check out Google's Cloud Platform's weekly podcast, where Google Developer Advocates answer questions, get in the weeds, and talk to experts, customers, and partners about GCP. Learn more and subscribe to the podcast at g.co/gcppodcast. Once again, that's g.co/gcppodcast. Now on with the show.

[00:00:33] Will: Welcome to Still Untitled, the Adam Savage Project. I'm Will.

[00:00:34] Adam: I'm Adam,

[00:00:35] Norm: and I'm Norm.

[00:00:36] Adam: Hey, everybody. Hello.

[00:00:38] Will: It's Monday after the Oscars.

[00:00:40] Adam: Yes, we we had a lovely Oscar party last night. We had a ball. We had we had popcorn.

[00:00:45] Norm: I saw that you won some type of Oscars bingo.

[00:00:48] Adam: I won Oscar bingo. There were categories. There were some fun categories.

[00:00:52] Will: A jet ski appears on stage.

[00:00:53] Adam: Oscar bingo.

[00:00:54] Norm: I don't think anyone anticipated that.

[00:00:55] Will: I

[00:00:56] Adam: the jet ski was great.

[00:00:57] Will: I haven't slept yet. I was up all night just. Partying, celebrating—I couldn't get enough.

[00:01:01] Norm: You got a VIP access.

[00:01:03] Will: Yeah, yeah. I was just there.

[00:01:04] Adam: So we had bingo, which my friend Jessica put together, and here were some of the here were some of the categories.

[00:01:11] Will: Oh boy!

[00:01:11] Adam: Cut to crying spouse during acceptance speech. Woody Allen mentioned by name. Mom brought as plus one. Lady in a tuxedo. Publicist in memoriam. Crying speech. Russia joke. Trump associate. Stare at the statue. Tripping on the stairs. Shot of a gracious loser. A thing that did not happen last night.

[00:01:33] Will: That's nice.

[00:01:33] Adam: Mel Gibson. Another thing that didn't happen. Mention pet cause in speech. Dedicate award to dead person. Matt Damon.

[00:01:42] Will: Fucking Matt Damon.

[00:01:43] Norm: Most of those actually happened.

[00:01:44] Adam: Selfie. Camera cuts to joke subject. Fish sex joke. We we had a dispute about this, but it was decided by the house that there was not a fish sex joke.

[00:01:55] Will: So as is as is my tradition post. Birth of my child, I vacate the house on Oscar Day around the time the red carpet stuff starts, so that Gina can like

[00:02:03] Adam: enjoy it.

[00:02:03] Will: can bathe in it without any chance of distraction.

[00:02:07] Adam: Yeah,

[00:02:07] Will: so I saw Peter Rabbit instead of watching the Oscars yesterday, and I don't encourage anybody to do that

[00:02:12] Adam: to do the the full operation or just to see Peter Rabbit.

[00:02:14] Will: No, it's nice to get like if one person is more invested in the whole, you know, the soiree.

[00:02:19] Adam: Yeah,

[00:02:19] Will: it's nice to vacate. I think, but Peter Rabbit, I would say, is probably a hard miss if you have any affinity for Peter Rabbit.

[00:02:25] Adam: Well, I enjoyed the Oscars last night. I, you know, it is often a grind, and this year was no no no difference. But at the same time, a lot of great stuff was deservedly awarded for its excellence.

[00:02:41] Will: Like the they looking at the list of winners, I I got I have very few complaints, which is unusual,

[00:02:47] Norm: isn't it? I mean, leading up to the Oscars past couple years, you have all these math models you see on like Five Thirty Eight, and even I think New York Times did one of like statistical models leading up for the anticipation. And so, isn't it almost like you're watching just to see if the model's wrong?

[00:03:03] Adam: Except that this year, apparently, there was a bunch of writing about how the Best Picture category was really, really hard to predict this year.

[00:03:11] Will: Well, first, it's been hard to predict since they started having up to ten.

[00:03:15] Adam: entries. Right. Yeah, that's true. That's true.

[00:03:16] Will: Second, over the last what two or three years, they've dramatically increased the number of member voting members of the Academy,

[00:03:22] Adam: Yeah.

[00:03:22] Will: bringing in a lot more youthful and diverse crowd.

[00:03:25] Adam: That's good because I read some excerpts of Academy voters and their commentary on films,

[00:03:30] Will: yeah,

[00:03:30] Adam: including things like, " Oh, I really liked Get Out, but when I was watching interviews and saw Jordan Peele pull the race card, I thought that was overdoing it."

[00:03:41] Will: What did they watch the same movie?

[00:03:42] Adam: I know this is an Academy voter too.

[00:03:50] Will: How many? It's like what three or four thousand Academy voters or something.

[00:03:53] Adam: I don't know.

[00:03:54] Adam: I mean,

[00:03:54] Norm: as an institution, it is just—I don't think any more valid than you know the SAG Awards or Independent Spirit Awards. It's just the one that's the most well-known.

[00:04:04] Will: Well, it's they've been doing it for ninety years, and and the Academy Motion Picture Arts and Sciences is like, I mean they're they're movies.

[00:04:13] Norm: Ah, now I know you didn't see this because you didn't watch it, but Adam, did you see the commercial for the museum? That was the the riff on the shining.

[00:04:21] Adam: Yes. So here's what happened. We're fast forwarding through

[00:04:28] Norm: the commercials.

[00:04:28] Adam: Yeah. Through the commercials, and I see a bunch of shots.

[00:04:31] Will: TV, Adam.

[00:04:33] Adam: I see a, DVR, DVR.. I see a bunch of shots clearly from the shining, and I go, " Hey, Jessica, can we rewind and watch this?" And my wife was like, " Are you gonna make us watch a commercial during this? I'm not sure this is a good idea."

[00:04:45] Norm: We did the same thing.

[00:04:45] Adam: I gotta, I'm sorry, but I I think I actually didn't even respond. I was like, " It's already happening. It's starting. I don't need to have this argument because we're about to watch something from the shining," and it turned out to be for

[00:04:58] Norm: the Academy Museum. Yeah, they're opening.

[00:05:00] Adam: Yeah, that was really cool.

[00:05:01] Norm: No, it's super cool.

[00:05:02] Will: Is it is it the same site as like LACMA and all that stuff, or is it somewhere else?

[00:05:06] Norm: I think it's that new museum.

[00:05:07] Will: Okay,

[00:05:07] Norm: That they're open right next door to LACMA.

[00:05:08] Adam: I believe the building in which we cover Deborah Nadoolman Landis's costume exhibit.

[00:05:13] Will: Awesome,

[00:05:13] Will: that's right.

[00:05:14] Adam: Is the site of the new Academy of Motion Picture Arts and Sciences museum.

[00:05:18] Will: That's fabulous.

[00:05:19] Adam: Yeah, and you know, look if they want some Shining props, I might be able to help them out.

[00:05:25] Will: You can. You can. They know who to call.

[00:05:27] Norm: They forked over a pretty penny for some 2001 props.

[00:05:30] Adam: Did they?

[00:05:30] Norm: Well, that the the big lander, right? I think that was them that they bought it.

[00:05:33] Adam: Ah,

[00:05:35] Will: that's very cool. I'm very excited about that.

[00:05:37] Adam: Yeah, no, that's really cool. And so it was like we got to the end of the commercial, and someone who did not realize that my wife and I were having that discussion was like, " Wow, that was really worth watching."

[00:05:47] Norm: Instant validation.

[00:05:49] Adam: I couldn't have scripted this any better.

[00:05:51] Will: And how was the couch last night, Adam?

[00:05:54] Adam: Yeah, it was really fun to watch the to watch the Oscars, especially the force of nature that is Frances McDormand. God, I love her. I love her.

[00:06:02] Will: Was that the first time she won?

[00:06:04] Norm: I don't think so.

[00:06:04] Adam: This is no. I think she's won before.

[00:06:07] Will: Yeah.

[00:06:07] Adam: Okay. Is it possible she won for Marge Gunderson in Fargo?

[00:06:10] Will: I'll look right now while you guys are talking.

[00:06:12] Norm: That's the case.

[00:06:13] Adam: I believe that is the case. Damn, she is such an awesome human. Such a great actress and so forthright and intelligent. Oh my God, I like. I want to meet her just so that we could have a disagreement and I'll be wrong. Like that's that's the degree to which I want her approval.

[00:06:29] Norm: Inclusion riders,

[00:06:30] Adam: what's that?

[00:06:31] Norm: Inclusion riders.

[00:06:32] Adam: Inclusion riders.

[00:06:31] Adam: Also, my I think my favorite moment last night was Best Picture. They, Faye Dunaway and and Maureen Beatty announced that it is a Shape of Water. And Guillermo comes up on stage, gets the envelope, and holds it, looks at it, and turns to the camera and goes, " It is Shape of Water."

[00:06:50] Will: Somebody, I want to say Laura Hall on my Twitter feed, who's a game designer in Portland, had tweeted a picture of the envelope and was like, " Look, they fixed the graphic design problem that made that. Like, there were multiple things that compounded the mistake last year."

[00:07:04] Adam: Right.

[00:07:04] Will: But one of them was that it was designed to be pretty and not to be legible, like the actual envelopes. You couldn't like it; didn't have in big letters

[00:07:11] Adam: Right.

[00:07:11] Will: what the categories was. Just a small line along the bottom, or something like that. And this year, it was like some big ass, like forty point Futura best picture on the outside of the envelope,

[00:07:21] Adam: big enough for old people.

[00:07:22] Will: Yeah.

[00:07:22] Norm: Do they air the science and technical Emmys?

[00:07:26] Will: Oscars, you mean

[00:07:27] Norm: the Oscars? Sorry,

[00:07:28] Adam: I'll. You know what? I don't know, but I suspect you know same in the same way that the Creative Arts Emmys, the Schmies that I have gone to, is cut down to like seventy five minutes and aired on during the daytime on some.

[00:07:45] Norm: Yeah, for the Oscars, it's barely acknowledged. You have like one shot of Patrick Stewart and and some of the some of the recipients.

[00:07:51] Adam: So that's it's not something I've looked up.

[00:07:53] Will: She won for Fargo, too.

[00:07:54] Adam: She did win for Fargo. Good, good. She deserved that too.

[00:07:57] Will: I mean, so one of the things that Gina and I were talking about because she gives me the rundown afterwards after we tuck the kiddo into bed and I watch the last few minutes. Is that last year there were so many incredible performances by women like over the age of fifty?

[00:08:09] Adam: Yeah,

[00:08:09] Will: because if you look at Holly Hunter in The Big Sick, I don't know if you if you saw that, but like she was unbelievable in that movie.

[00:08:15] Adam: Phenomenal. Yep.

[00:08:15] Will: Frances McDormand in Three Billboards was unlike she's ever been before. I think, and and yeah, like it's it was good. It was good all the way around.

[00:08:24] Adam: Yep.

[00:08:25] Norm: The thing I also like is the clips they select to showcase the performances. If you've seen the movies, I always want that's not the necessarily the best clip. I would have chosen a different clip.

[00:08:36] Adam: Maybe they work with the actors, and it's an actor's choice.

[00:08:38] Norm: Yeah.

[00:08:39] Will: Oh, they go actor's choice.

[00:08:40] Adam: I don't know.

[00:08:40] Adam: I have no idea.

[00:08:41] Norm: Yeah, it's all interesting behind the scenes on the production of this you know four hour broadcast that that makes it fascinating.

[00:08:48] Will: This is the first year in a long time that I'd seen the majority of the Best Picture nominees.

[00:08:52] Adam: Yeah, I still had not seen the majority of them, but I've seen enough of the movies this year. How awesome was it to watch Roger Deakins win? And how hilariously has he like been zapped out of an Austin Powers movie?

[00:09:04] Will: Fourteen nominations,

[00:09:06] Norm: and then he went up and thanked. Everyone he's worked with,

[00:09:09] Adam: yeah, no, he's an amazing guy, amazing guy. I, I, I heard this about Blade Runner and other films. He does not have a second unit.

[00:09:18] Norm: All him.

[00:09:19] Adam: he is there for every camera shot. He he doesn't delegate that.

[00:09:23] Will: So typically, a second unit does like exterior shots and stuff without the kind of main actors.

[00:09:27] Adam: Yeah,

[00:09:28] Adam: when you see the plane taking off at the airport, that's a separate team that got up really early to go get that shot.

[00:09:32] Will: Yeah, I mean,

[00:09:33] Adam: on Lord of the Rings, they had I think four and sometimes five units, and I know that Andy Serkis for the Hobbit films directed a lot of the ancillary film crews.

[00:09:44] Will: Huh.

[00:09:45] Will: I mean,

[00:09:46] Will: part of me says, yeah, that's awesome that he's like watches the whole thing. The other part of me says, hey, that's a valuable spot for people who are coming up to like get get time on camera.

[00:09:55] Adam: Yeah, totally. No, I mean that was that was the thing. Those I can't remember if we talked about this on the podcast, but we've talked about it personally so much is that on the behind the scenes of Lord of the Rings, you can watch them having to watch. Two hours plus of dailies every single day from all the multiple camera departments, and the only one who could seem to stay awake till the end of every single session was Peter.

[00:10:17] Will: I mean, look, you you know him better than we do, than I do, obviously. But I mean, he seems like he is just a an unstoppable force, basically.

[00:10:24] Adam: Absolutely, and Coco, Coco won. Lee Unkrich and the Pixar folks got up. That was a lovely set of speeches for Coco's acceptance.

[00:10:33] Norm: One of two awards and best song.

[00:10:35] Will: Best song too. Yeah. I mean, Coco in this year's Best Animated Field was like if it hadn't won one, there would have been. It was a massive crime. I mean, I've I've seen all. Well, I didn't see the I didn't see the becoming Vincent one, but I saw everything else.

[00:10:49] Adam: You saw Boss Baby.

[00:10:50] Will: I saw. Oh, believe me, let me tell you, I've seen some Boss Baby. It's it's Alex Baldwin's finest role. So that's not true. Yeah. No, it's like Coco. We watched Coco again this weekend, and it it is an astounding film.

[00:11:03] Adam: It's so good.

[00:11:03] Will: I think it's my favorite Pixar.

[00:11:05] Adam: Hard to see through the last twenty minutes through the tears.

[00:11:08] Adam: But when he sings to his grandmother.

[00:11:09] Adam: The movie goes. Here's what's going to happen. I'm showing you the inside of the envelope. I'm revealing everything as we go, and you get there, and you're like, " I'm still surprised and moved way past what I expected."

[00:11:21] Will: Well, there was a little bit of a twist in there.

[00:11:21] Adam: There was in the beginning, actually, the first half, the movie led you to believe it was a totally different kind of movie.

[00:11:26] Will: Yeah, yeah.

[00:11:28] Adam: I finally got around to seeing Black Panther. I have been so there's been a lot of busyness in my personal life.

[00:11:36] Will: Back and forth all over the place,

[00:11:37] Adam: Have some announcements to make. I'll have some announcements to make later on this year about some projects that I've had on the on the burner that have been occupying a lot of my time. But suffice it to say, I have not been able to make it out to the damn movies until this weekend when we went and saw Black Panther at the Kabuki.

[00:11:52] Will: What'd you think? Was it good or you know,

[00:11:55] Adam: yeah, unbelievable?

[00:11:56] Adam: I love this shit out of it.

[00:11:59] Adam: What's that?

[00:11:59] Norm: You had gone into it relatively cold.

[00:12:01] Adam: I so we're we're playing around and doing some projects with Broken Nerd, a wonderful maker who I met on Twitter, and he's been doing some Black Panther cosplay props that he's 3D printing and finishing, doing great work on. Watching his videos of. Making Black Panther cosplay props is the only spoiler I allowed myself. I haven't seen a single trailer. I I avoided all plot twists. I'd seen a couple of shots of Michael B. Jordan with his shirt off, because that seems to be inescapable on the web right now.

[00:12:32] Will: I mean, look,

[00:12:32] Adam: but not to anyone's. Not that anyone's complaining. And holy cow, did I love that movie so so much!

[00:12:40] Will: So I walked out of the theater, and it's it's one of like I don't often walk out of the theater and think, man, I would turn around and walk back right in and watch another showing of that. Had it not been the Friday after it opened, I would have turned right back around and gone right back into the next showing because it was exceptional.

[00:12:52] Adam: Angela Bassett, by the way, seems to be using some alien technology to stay looking as badass as as I can possibly imagine. She's a warrior. I loved the general. I loved Shuri. Chadwick Boseman was incredible. I'd read extensively about how they worked on a dialect that wasn't any specific African country, but that really was specific to Wakanda and getting everyone to. Speak that way, and at a certain point, my wife leans over and she's like, " The accents are amazing, and they really were like super consistent."

[00:13:22] Will: Yeah, across all the characters.

[00:13:25] Adam: Talk about world building. Yeah, that was one of the best examples of world building I've ever seen.

[00:13:29] Will: So, I mean that that moment, the reveal,

[00:13:34] Adam: coming through the forest.

[00:13:36] Will: Let's decide what we're going to talk about, and then we should have a spoiler.

[00:13:38] Adam: I think I think it's been out long enough. We can spoil the crap out of this. Oh, you want to talk non-spoiler first?

[00:13:44] Will: I mean, we usually do, just in case, like the three people that haven't seen it yet.

[00:13:47] Adam: Sure,

[00:13:47] Norm: sure, sure. Performances were great.

[00:13:49] Will: Yeah,

[00:13:49] Norm: emotionally resonant.

[00:13:50] Will: Score was fabulous.

[00:13:51] Norm: Score was fabulous. Great world building. What else? Non-spoilery.

[00:13:55] Will: I mean, okay. Just we say the score's fabulous. The soundtrack album is incredible. I don't like.

[00:14:00] Adam: Yeah, no. I haven't downloaded it yet, but that's the next thing.

[00:14:03] Will: Kendrick Lamar made an explicit album, true to the film,

[00:14:08] Adam: Mm hmm.

[00:14:08] Will: for this PG. Is it PG?

[00:14:11] Adam: PG thirteen

[00:14:11] Will: . Yeah, like like it's it's a fabulous album, and and I'm shocked that they got Disney to sign off with putting this fairly explicit album out with a PG-13 movie that's clearly aimed at teenagers. But whatever, all good.

[00:14:27] Adam: Yeah,

[00:14:28] Will: I mean, it seems like it seems like to me that Disney just said, " Hey, here's here's this character. Here are an incredibly talented team of actors and directors and and production writers. The whole thing, go make this film that you want to see." And then they kind of stayed out of their way.

[00:14:45] Adam: It seems and feels and smells exactly like that. Like it is, it is a a complete vision that is joyful. It's dangerous. It's it's beautiful. You know, we've talked coming back from San Diego Comic Con each year that there are touchstone films. A couple years ago, everyone there was so many Reys from from Force Awakens. There, this year, I really think unequivocally, San Diego Comic Con is going to be the Black Panther Comic Con.

[00:15:13] Will: Bunch of middle-aged white guys in Black Panther armor. It's just what everybody needs.

[00:15:16] Adam: God, I hope not. I loved the range of costumes. I loved the range of of of iconography and masks and dress and I mean, one of the things that's great about world building is what you understand, but also what you don't understand. And we've said this before, but I think that Spirited Away is probably the greatest example of this. Is a this is a world with rules, and you're only going to ever learn like one tiny smidgen of them. But you can tell there's an internal consistency and depth, right?

[00:15:51] Norm: And to give you a glimpse into that depth while not feeling superficial and to to show that there is more there,

[00:15:58] Adam: yeah.

[00:15:58] Norm: That I mean, explicitly say it. That is difficult.

[00:16:01] Will: It's one of the things that actually is really interesting about Avatar. Like, like it's a movie that nobody thinks about anymore.

[00:16:06] Norm: Yeah,

[00:16:06] Will: twelve years after it came out or whatever. But you know, it was really clear when you saw the ships and all the all of the world that was set up around telling that relatively simple story.

[00:16:18] Norm: Yeah.

[00:16:18] Will: That James Cameron and the whoever else wrote the film had spent a lot of time thinking about how this works, what the economy of this is, you know, why people would come to this place and and all that, and you get a lot of the same like. So we want to get into spoilers because I.

[00:16:32] Norm: Let's do it.

[00:16:32] Adam: Yeah,

[00:16:33] Adam: let's get into spoilers. Okay, spoilers are happening

[00:16:35] Will: now. So the moment that they fly through the force field and see like Wakanda City, I don't know what it's called.

[00:16:41] Norm: Yeah.

[00:16:41] Will: I was just like, oh right, okay, this is not at all what I was going to,. I was expecting this. This is. This is. There's something really different happening here, and I was really thrilled. Like it was an exciting moment. The theater gasped when I was in there like. And and you don't get that in movies.

[00:16:58] Adam: No, you don't. You don't. And I mean, even so, I'm two and a half weeks behind. The audience clapped at the end of the screening I saw in the middle of the day.

[00:17:07] Will: Yeah.

[00:17:07] Adam: You know, it's a joyful. A joyful movie to watch, and I'm. It's like like you said. I'm going to watch it many times. I'm really looking forward to sinking my teeth into all of that.

[00:17:20] Norm: I mean, the film also has a juggle between this very entertaining popcorn film and a comic book film, and also being aware of its importance to its viewers and the people, the characters, and the people that the film represents. And it doesn't pull that gut punch. It lets you. It has intentionally has the gut punch at the both the end of the film.

[00:17:43] Adam: It doesn't make it subtext. It makes it directly text, and it feels honest and right. And

[00:17:48] Norm: yeah,

[00:17:48] Adam: yeah.

[00:17:48] Norm: I mean, opens up in Oakland, and then when they jump back to that flashback, and you realize it is Michael B. Jordan's character Killmonger looking up at the ship and running up, you know, into the apartment building. That is powerful.

[00:18:00] Will: Yeah,

[00:18:00] Norm: and then how it goes back full circle to the very end, the very last scene nails that landing.

[00:18:06] Will: Yeah, it's the very last scene. It's been a while since I saw it. The very last scene is when Killmonger.

[00:18:09] Norm: No, no, it's in,. In in when they go back to Oakland.

[00:18:12] Will: Oh,

[00:18:12] Norm: and the kid walks up to him, and and says, " Who are you?" And when they reveal themselves, not only to the world but to the kids there,

[00:18:19] Will: yeah.

[00:18:19] Norm: And it's the complete opposite of what his father did, which was to hide and shroud in secrecy.

[00:18:24] Adam: And and Julia turned to me and did when he said, " When the kid says, 'Who are you?'" Julia said in her best, " My wife." In her best,

[00:18:33] Will: My wife.

[00:18:33] Adam: Robert Downey Jr. I am Black Panther.

[00:18:37] Norm: I mean, and that's that's. I mean, it's a riff on that.

[00:18:40] Adam: Yeah,

[00:18:40] Norm: it's a riff on the Batman. You know, at the end of you know Batman Dark Knight, right? It's it's a riff on all that that trope of the superhero revealing

[00:18:48] Adam: Self-actualization.

[00:18:49] Norm: exactly, but it's much more powerful because it's about what the the person asking the question sees in the character.

[00:18:56] Adam: Yeah, and it like I love Marvel for getting out of the way of its own movies.

[00:19:02] Will: That's what sometimes

[00:19:02] Adam: feels like you're watching.

[00:19:04] Will: I mean, it seems like they're doing that more because Thor was kind of the same way. Thor, Thor

[00:19:07] Adam: Ragnarok was like a

[00:19:08] Will: yeah,

[00:19:09] Adam: a deeply New Zealand film and its sense of humor and. Play and folly. I mean, you know, this is a movie with a bunch of jokes that don't feel at all like Hollywood style jokes, and yet they totally scan and work.

[00:19:23] Will: I mean, if they cut across during one of the fight scenes and like Jermaine Clements over there strumming a ukulele and singing, that would have been okay. I would have been okay with that. Yeah, so I mean, I don't know what like. Look, a lot of the stuff in Black Panther, I feel like I am woefully under equipped to to discuss intelligently, and I don't think we need more.

[00:19:40] Adam: I think the cultural implications of Black Panther have been covered extensively, and you know, it's also a great film, and that's

[00:19:47] Norm: that's the

[00:19:48] Adam: loveliest thing about the idea of this type of cultural normalization of bringing people closer together by giving them things to enjoy together.

[00:19:57] Norm: Extremely efficient and competent in its action and its sequences. There is a great video that I think director Ryan Coogler did with Variety or Vanity Fair, where he maps out the casino scene, the fight scene in the casino, and it was one of the first scenes they shot. And it's a series on on that YouTube channel where directors talk, and I think Taika Waititi did same thing for Thor.

[00:20:20] Will: Okay.

[00:20:20] Norm: They have, they they run through the sequence, and then they have screenshots of the sequence, and he literally draws with a pen and and annotates what's going on.

[00:20:30] Adam: Oh, that's great! I I've been avoiding all that stuff since I'm psyched to jump in..

[00:20:33] Norm: Totally should watch it for for Black Panther and for this action sequence, which is just in the casino where it's you know the the three of them in the room, and then the the with Andy Serkis's character, and then when the fight breaks out, even the the beats of that and their positioning and the colors that they're wearing, everything is so thoughtful.

[00:20:52] Adam: You are never abandoned in the physical space. I've you know the action of it.

[00:20:58] Will: There were a couple moments in one of the car chases where you kind of lost when when he gets chucked up in the air, and you're like, ah, where'd he go? What's going on here? And then magically ends up right in the right place.

[00:21:08] Adam: I also want to point out how great a villain Andy Serkis is. He's terrifying.

[00:21:14] Will: He's he's the he's the one armed man, right?

[00:21:16] Adam: Yeah.

[00:21:16] Will: Yeah. That's That is, that's not what I would have pictured Andy Serkis looking like.

[00:21:21] Norm: Oh,

[00:21:21] Adam: you didn't realize? I've seen dozens of movies with Andy Serkis actually present in them.

[00:21:27] Will: So I realize that now, but also I didn't have any idea that that was Andy Serkis. He showed up first in what Civil War or something,

[00:21:33] Will and Norm: or Winter Soldier, Age of Ultron,

[00:21:35] Will: Age of Ultron. Okay, yeah, yeah, that's right.

[00:21:38] Adam: Is he in just one?

[00:21:39] Norm: He's in Age of Ultron when they mention that he stole the vibranium.

[00:21:45] Adam: But isn't he also in Civil War?

[00:21:48] Norm: I don't think he's in Civil War.

[00:21:50] Adam: Okay,

[00:21:50] Norm: his arm gets cut off by Ultron, and that's when he comes back. Yeah,

[00:21:54] Will: comes back with the vibranium arm.

[00:21:55] Norm: Yeah,

[00:21:55] Will: I, I, um, like it's one of the things that bums me out now is when you see a character, like an actor, gets their one shot at the MCU. Get they, whoever makes the movie whiffs it, and you end up with a with an amazing like like the the example of Michael Keaton as Vulture in Spider Man was fine, but like like. You could do a lot more with Michael Keaton than a one-off bad guy.

[00:22:17] Adam: I thought it

[00:22:18] Will: was great. I don't feel like there were any one-off bad guys. There was nobody was one-off wasted. All the characters were good. Killmonger is my favorite Marvel villain with at my least favorite Marvel villain name.

[00:22:30] Adam: Is such a good character, such a yeah, such a great portrayal, such a really good character, and such an intense and incredible death scene.

[00:22:38] Will: Oh yeah,

[00:22:38] Adam: like I was like, oh wow, they wow, wow, yeah,

[00:22:42] Will: yeah,

[00:22:43] Adam: that's great.

[00:22:44] Will: That's really good.

[00:22:45] Adam: Also, Going back to the Academy Awards, I I want to now see a movie with Gal Gadot and Armie Hammer in it, simply because those two are so pretty.

[00:22:54] Will: Yeah,

[00:22:55] Adam: yeah, yeah. We we were we were we were we were talking about the the extreme beauty of a bunch of the. I mean, that's

[00:23:03] Will: really. I mean,

[00:23:04] Norm: Hollywood. We'll find a way.

[00:23:05] Will: Any time you cut to a movie theater filled with normal people during the Oscars, you're like, oh, right, this is why these people are movie stars. That

[00:23:11] Adam: bit was

[00:23:12] Will: weird. Yeah. That bit's always weird. They did it before. Didn't they?

[00:23:15] Adam: Visiting the Proles is a weird thing to

[00:23:17] Will: That was peculiar. One of the Ellen years, they tromped a bunch of people through stage that thought they were on a tour of the Kodak Center or something. Yeah,

[00:23:24] Norm: same thing.

[00:23:24] Adam: Yeah, right, right, right,

[00:23:24] Norm: yeah, this year.

[00:23:26] Will: Yeah, so, so I, I, you know, this is completely off topic. I want to shout out. I finally watched Justice League, which is not a good movie in a lot of really important ways, but it was fun.

[00:23:35] Adam: Okay,

[00:23:35] Will: the score on Justice League that Danny Elfman did,

[00:23:38] Adam: yeah,

[00:23:38] Will: is exceptional.

[00:23:39] Adam: Oh, okay.

[00:23:40] Norm: I didn't like it.

[00:23:40] Will: You didn't like it?

[00:23:41] Adam: What?

[00:23:41] Will: I love that it pulled it like he went through and pulled in everything from like the original his original Batman theme.

[00:00:00] Unknown speaker: That was cool.

[00:23:46] Norm: I think that he was unabashed about the fact that even though not within the same continuity, you can pull a John Williams theme and put it in a Zack Snyder movie.

[00:23:55] Will: Yeah, he's like this is the Superman song, and he used the original John Williams theme. He used the he used like, and the thing that amazed me is that the Wonder Woman theme, which is excellent, the Danny Elfman Batman theme, which is excellent, and the the John Williams Superman theme, which is iconic.

[00:24:10] Adam: Yeah,

[00:24:11] Will: all work together.

[00:24:12] Adam: Amazing

[00:24:12] Will: in the context of of of this film.

[00:24:15] Adam: Okay,

[00:24:15] Will: and and I thought I I thought it was lovely.

[00:24:18] Adam: Um.

[00:24:19] Norm: Speaking of Wonder Woman, you have a sword there,

[00:24:21] Adam: I do.

[00:24:21] Norm: and recently we can tease if you're watching the video. Adam's been working on this sword. Now you didn't build this from scratch.

[00:24:26] Adam: No, no, no, no. This is from a big bad toy store.

[00:24:29] Norm: Yeah, Factory Entertainment.

[00:24:30] Adam: Factory Entertainment makes a an all metal God Killer sword, and this is this is it. The blade is, in terms of accuracy, terrific. The symbols and the etching is pretty darn great. The handle is cast zinc alloy, like a lot of handles from metal movie props.

[00:24:49] Will: So it has the right weight.

[00:24:50] Adam: It does. It has a good weight and a good balance, but at the mold lines of the casting, a lot of detail is lost.

[00:24:58] Norm: Right.

[00:24:58] Adam: Inspired by a video I tweeted earlier this week of an incredible master engraver hand engraving incredible designs into the watch band of a Rolex, and then there's it turns out there's hundreds of hours on YouTube of people engraving stuff. I started to get really into. Carefully filing, and so I've been with mostly with hand files, restoring this handle back to looking as good as it can. And I actually think I'm going to have this plated.

[00:25:28] Norm: Ooh!

[00:25:29] Adam: I think I'm going to take it out to a. But there's a lot of jewelry places here in San Francisco, and have it gold plated to make it extra awesome.

[00:25:35] Norm: And that's the thing with like prop replicas like these because they're they're high end. They're several hundred dollars. Sometimes they're limited edition. When you read the description on their website, I think everything has to be read with a little grain of salt because they say, you know, designed with access to the original prop, but that can mean so many things, right? Did they get the original files? Are they were they given just photos of it? Like how accurate? And that doesn't tell you whether their manufacturing process, you know, all the seam lines that you got rid of in this replica were they in the original prop?

[00:26:07] Adam: Look, I mean, and and the the simplest logical case to make for how hard it is is that master replicas repeatedly had access. To original props and still managed to regularly piss off their fans for getting large details wrong, and by wrong I mean they might have had one detail from one movie on a prop that was in the wrong movie of the franchise, because that happens when you go into the archives. Often the people managing these archives don't know as much as your as your as your base level obsessed fan like me or you,

[00:26:38] Norm: right? And as a licensee, the people who have who pay money to get the rights to make these replicas, they don't always get every all the access because the licensor doesn't care. They they got the money and they'll sign off on something and they have you know those words you know authentic like a certificate of authenticity, but that may not be enough. So I love the idea that you're taking something that you've paid several hundred dollars for and then basically taking it apart,

[00:27:02] Adam: yep,

[00:27:02] Norm: and rebuilding it.

[00:27:04] Adam: And so yeah, we'll we'll we'll show my results when when we're all done. This is not one we're covering on camera because I'm it's probably going to take me dozens of hours of work over many days to do this. So it's just sitting on my bench with some files near it, and every time I have an extra thirty minutes, I kind of work on it for a bit.

[00:27:20] Will: Do you find that kind of work to be a little meditative?

[00:27:22] Adam: Oh, it's entirely meditative. I, I, no longer at this point in my life mind looking at a project like this where I'm not even sure how long it's going to take or how I'm going to finish it. I and, um, from being obsessed with the engraving video, but also specifically Clickspring. I've mentioned Clickspring on the podcast. Holy cow! Go watch Clickspring. Um, this is the guy who does everything out of a shop that is maybe 300 square feet, and a lot of his work is so carefully hand filing with really good lighting and good vise work. Um, it's it's that's gotten me into doing exactly this kind of thing and being like, oh, I can with files. I can't make an unrecoverable mistake like I can with a Dremel, so I can just sit there and slowly look at it from every angle and just make sure it's right.

[00:28:11] Will: It makes a ton of sense. You can you can muck something up in about three tenths of a second with a Dremel.

[00:28:16] Adam: Right, and so I'm now like I did some Dremel work on this today to kind of play around with one of the dragon heads, and I I put it on one of its lowest settings so I could just sit there and really have the gentle control.

[00:28:30] Will: Do you ever vise the Dremel and go the other way? That's that was the thing somebody showed me once. Is you put it you put the the Dremel in a bench vise, and then you can kind of come at the blade from the side.

[00:28:38] Adam: I had not tried that.

[00:28:39] Will: It seems a little dangerous.

[00:28:40] Adam: .  Yeah, I haven't tried that. I am interested in the in the engraving video of the watch. It's clear that the watch is clamped into a special jeweler's vise that holds it, and I actually bought one. But this one specifically turns, so the the engraver has his two hands, his or her two hands on the work, but they're turning the work into the chisel, not the other way around.

[00:29:03] Norm: So you have to only maintain the pressure.

[00:29:05] Adam: Yeah, and so I'm curious what that rig looks like, and I've started to I went and looked for engraver's vise, engraver's work setup. I'm I'm sure somebody listening will will post where I could see this. But it's almost like they've got some sort of Potter's wheel type thing. They're moving with their feet, but it's really heavy and holds this thing rigidly.

[00:29:24] Norm: But you get mechanical assistance and precision.

[00:29:27] Adam: That's what it looks like.

[00:29:28] Will: It seems like you could do like a friction clamp where you just push your foot down to release it and turn, and then let up and or something like that.

[00:29:33] Adam: But they're also doing it while they're moving, and maybe he's got a maybe he or she has a handle over here, and they're doing it. But I feel I'm curious to see a little bit a wider shot of that setup.

[00:29:43] Will: Cool.

[00:29:43] Adam: Speaking of commenting within the comments, I just want to thank the tested community, those who agree with what we talked about last week about gun control, but especially those who don't agree with us who took the time to contribute to the conversation. I thought everybody in the comments comported themselves really respectfully and understood our goal to try and create a dialogue. I was incredibly gratified by the response on on our site on Facebook. On Twitter about about our podcast last week,

[00:30:16] Will: I saw you middle of last week, and you were like, " Hey, the comments on that were really good." I was like, " Wait, what? Really?"

[00:30:23] Norm: I think that's a good place to wrap it up.

[00:30:24] Adam: I think it's a fine place to wrap it up.

[00:30:26] Norm: A couple shout outs. We are about one month away from our first convention we're going to this year, which is Silicon Valley Comic Con here in the Bay Area. It's in San Jose, so if you are in Bay Area or in California, it's not that far of a drive. You can come see us there. We'll probably be doing a podcast. Probably there'll probably be an incognito of some kind.

[00:30:44] Will: Are you setting up a booth again this year?

[00:30:46] Norm: We'll probably be doing a space this year. So come by and say hi. If you just Google Silicon Valley Comic Con, you can find a lot of information.

[00:30:54] Adam: It's a good con. It's a fun con. We've done it the last two years in a row, and it's been great.

[00:30:57] Will: We're in final testing of the Nano Machines episode of the Foo Show, and at the same time, we're almost done with the episode that the three of us recorded a few weeks ago.

[00:31:06] Adam: Oh, Fabulous!

[00:31:06] Will: With your props from the twenty sixteen live show,

[00:31:10] Adam: That's right.

[00:31:10] Will: yeah, the stuff that we scanned, yeah, we built a fake not. Not at all like this, but kind of somewhat inspired by this version of the cave.

[00:31:17] Adam: Felt somewhat familiar,

[00:31:18] Will: and those will both be out real soon. The nano machines episode will be out this week, I think. We're doing final testing on that.

[00:31:24] Norm: Very cool. All right, thanks for watching.

[00:31:26] Adam: Thanks, everybody.

[00:31:26] Unknown speaker: We'll see you next time.

[00:31:27] Will: Bye, guys.

[00:31:27] Adam: Bye.

[00:31:28] Norm: Once again, we want to thank the sponsor of this week's episode, and that's Google's Cloud Platform. What can your data tell you? With Google Cloud Platform, use machine learning at scale to build better products. It predicts so your business can thrive. Learn more about Google's Cloud Platform at g co slash get cloud AI. Once again, that's g co slash get cloud AI. We'll see you next week.
