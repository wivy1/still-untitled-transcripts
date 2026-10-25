**Podcast:** Still Untitled: The Adam Savage Project  
**Episode:** 256 - All We Have Left is Magic  
**Date:** 2018-03-13  
**Duration:** 28m 54s  
Episode URL: https://www.youtube.com/watch?v=nVH2XC-FXOs

[00:00:00] Norm: This week's episode of Still Untitled is brought to you by Google's Cloud Platform. Looking to move to the cloud? Check out Google Cloud Platform's weekly podcast, where Google Developer Advocates answer questions, get in the weeds, and talk to experts, customers, and partners about GCP. Learn more and subscribe to the podcast at g co slash gcp podcast. Once again, that's g co slash gcp podcast. And now on with the show.

[00:00:29] Will: Welcome to Still Untitled, the Adam Savage Project. I'm Will.

[00:00:32] Adam: I'm Adam.

[00:00:33] Norm: I'm Norm.

[00:00:33] Adam: Hey, everybody,

[00:00:34] Will: guys! Paddington Two is the best movie I've seen this year.

[00:00:37] Norm: Oh wow!

[00:00:38] Will: I just want to get out of the way up front.

[00:00:39] Adam: As hard as that is for me to like, I I fully get. I see the Rotten Tomatoes ratings of Paddington and Paddington Two like 100% or 98%. I know that it'll change my life. I just haven't gotten around to it yet.

[00:00:52] Will: I didn't like Paddington One as much.

[00:00:54] Adam: Okay,

[00:00:54] Will: Paddington Two. Like I I can't believe I'm saying this. No,

[00:00:59] Adam: No, I can't either.

[00:01:00] Will: It is it is. I watched it again to make sure.

[00:01:00] Adam: Okay.

[00:01:00] Will: I saw it in theaters, and it came out on video the other day. and I watched it again.

[00:01:00] Adam: All right.

[00:01:00] Will: You should watch Paddington too.

[00:01:00] Adam: Okay.

[00:01:11] Norm: You raise the dad quotient.

[00:01:12] Will: It no, no, this isn't a dad business. Look, we talked about Peter Rabbit last week. That's not a good movie.

[00:01:17] Adam: No, no, I feel it. I feel you. I feel you.

[00:01:20] Will: It is a charming, well shot movie.

[00:01:20] Adam: Okay.

[00:01:20] Will: Of the kind that isn't made anymore.

[00:01:26] Norm: Okay.

[00:01:26] Adam: I will watch. I will watch. I will. I promise.

[00:01:26] Will: Okay.

[00:01:26] Adam: I promise.

[00:01:29] Will: There's a sequence. They show the world with Paddington, and then they show the world without Paddington.

[00:01:35] Adam: Oh my gosh! Like Harry in It's a Wonderful Life.

[00:01:38] Will: Think about Shaun of the Dead and Hot Fuzz. Right. It's the same kind of. British comedy. Very very well done.

[00:01:43] Adam: All right.

[00:01:44] Will: It's a lovely film.

[00:01:45] Adam: Okay.

[00:01:46] Will: Go watch Paddington too.

[00:01:47] Norm: I can't help but notice there's something sitting on this table. I want to talk about.

[00:01:51] Will: It's it's yeah. It's the robot from Paddington too.

[00:01:53] Norm: No, it’s.

[00:01:54] Adam: um that’s that’s that’s Cain. He is the villain from RoboCop two.

[00:01:54] Unknown speaker (Will or Adam): The best RoboCop.

[00:01:54] Adam: That is a casting of one of the stop motion models that is was a gift to me from Phil Tippett. It is one of my favorite possessions in the world,

[00:01:54] Will: It’s lovely.

[00:01:54] Adam: and when I got it's all resin, right? Or sorry when when Phil gave it to me, it was almost all just resin, and it didn't stand on its own because the resin's just not strong enough.

[00:02:23] Adam: This this is a puppet in which

[00:02:24] Adam: it's a stop motion puppet in which every joint is pretty much visible, but there is, there is over two hundred parts in this. So when I first got it, I actually paid one of the machinists from Tippett's studio to build parts of the legs so it could stand on its own, and that got it about eighty percent there. And then over the last couple of weeks, I brought in Brett Foxwell, a wonderful machinist who also works at Tippett.

[00:02:48] Norm: He made the armatures for the Force Awakens. Puppets, Dejarik

[00:02:53] Adam: table for the Dejarik

[00:02:54] Norm: table. Yes.

[00:02:55] Adam: Oh, cool. So Brett is wonderful, and he spent a couple weeks in my shop putting more parts into Cain. This is one of those off-camera things that's like going on the back burner in my shop all the time.

[00:03:05] Will: We heard it a couple weeks ago.

[00:03:07] Adam: What's that?

[00:03:07] Norm: We literally heard it on the podcast.

[00:03:08] Adam: Oh, yeah.

[00:03:09] Norm: A couple weeks ago. Yes.

[00:03:10] Adam: And I'm, I now am inspired enough that I've started to take apart the toes and make them myself. So

[00:03:17] Norm: Oh, you’re going to machine them?

[00:03:18] Adam: Yeah. My, My goal is eventually someday for him to be as much metal and aluminum as possible.

[00:03:25] Norm: So that is a like you're talking about 200 parts.

[00:03:27] Adam: Oh, the guts. Years. It'll take me years.

[00:03:27] Norm: Right.

[00:03:27] Adam: Yeah.

[00:03:27] Unknown speaker (Adam or Norm): Does it just?

[00:03:30] Unknown speaker (Norm or Will): piece piece by piece by piece

[00:03:32] Adam: by piece.

[00:03:33] Will: by piece. I I want. I think it might be instructive for people who don't know.

[00:03:33] Adam: Yeah.

[00:03:33] Will: You should explain why Cain is important in the effects world.

[00:03:39] Adam: Well, so so when RoboCop two came out, Cain was without a doubt the most complex stop motion puppet ever built, with four arms and however many points of articulation, probably over 50. The goal when designing him, according to Phil, was to design a puppet that no one could replicate.

[00:04:02] Will: Like the toy manufacturer,

[00:04:03] Adam: the toy manufacturers, they were pissed that the Ed Two Hundred Nine just showed up everywhere after RoboCop, and so Cain was like the anti-copy. Cain has built-in DRM.

[00:04:13] Will: Yeah,

[00:04:13] Adam: he's uncopyable.

[00:04:13] Will: I mean, which which is evidenced by the fact that when people at Phil's shop made a casting for you and presumably some other folks, like you had to do work on it to get, you know, [unclear: it had to be brought / it had to be prop] to stand up and stuff like that. It's a it's a difficult replication.

[00:04:30] Adam: The machinists that put this together, it was months and months and months of work for a team of people to put together the I think five or six puppets that they made for the film. One of them is in Peter Jackson's collection.

[00:04:43] Norm: We saw it on the shelf. Yeah, yeah.

[00:04:43] Will: it's cool.

[00:04:45] Adam: Yeah, and I have to tell you, like, to actually handle it and move the real thing—if you've never held an armature, this is instructive. If you've never held an animation armature, the the thing is, is it's meant to have a Kind of a perfect amount of resistance, without any bounce back, so that the animator can sensitively place each joint in place. Which means that a well-tuned animation armature feels like this real joy to manipulate. And Cain is like off the charts.

[00:05:14] Norm: Well, and they have to be tuned regularly because you

[00:05:17] Adam: tuned to each animator,

[00:05:18] Norm: right,

[00:05:18] Adam: right, right. I mean, not just tuned on set so that they make sure the joints don't drift or droop, but each animator has a feel that they prefer. And so you could, could you? I can't even imagine how many Allen wrenches an animator on set would need to make sure this thing maintains its perfect.

[00:05:35] Will: Well, they're all the same size Allen wrench.

[00:05:36] Adam: Did I just say perfect old tunage?

[00:05:38] Will: I mean, look, perfect old tunage is the name of my grateful dead cover band. Yeah, so you know, sorry, Paul and Storm.

[00:05:44] Norm: What a project.

[00:05:46] Will: I mean, the thing that I was amazed by when we first started talking about stop motion years ago, I think at Fon Davis's studio, was how each the further you get from the anchor point. The the more relaxed each joint gets, so that so that you can adjust a finger without also moving the arm

[00:05:46] Adam: Right, right.

[00:05:46] Will: and and so on and so like it's it's incredible. It's an incredible, incredible thing. This and the canes like this Cain. I mean, it'll look cool in the video, but it looks even better up close. So I hope.

[00:06:10] Adam: I remember being when the movie came out, like doing searches to find out the toys from this. And Hot Toys was supposed to do a version of this. A figure came out a couple years ago, which I have in my collection, and it's lovely. But but this is really this is one of the best pieces in my whole collection, and you know I love Phil. I I owe him I owe him a deep life debt. Someday he will call upon me,

[00:06:39] Adam: Adam.

[00:06:40] Norm: You know it's funny. Well, Last time I visited Phil, he was doing his most recent Kickstarter for Mad God, and they were doing some puppets, and he is work still working on Mad God, and which is a stop motion short film. Unending, many parts

[00:06:54] Adam: been doing for like twenty years. It's amazing

[00:06:56] Norm: from his mind,

[00:06:56] Adam: yeah.

[00:06:56] Norm: And he was working on armatures. He was taking apart armatures from these sixth scale dolls he had bought from China, where it's it's not like the hot toys where they're like ball joints on on on plastic, yeah, yeah, but it was like silicone dolls with metal armatures

[00:06:56] Adam: Oh my gosh!

[00:06:56] Norm: pre built on the inside.

[00:07:17] Adam: No, no,

[00:07:17] Norm: that you could get for like seventy or eighty dollars, and these like musculature, you know, big like Arnold Schwarzenegger type body types,

[00:07:25] Norm: Yes.

[00:07:25] Norm: and he would just take the heads off and put you know like Minotaur heads or something on them.

[00:07:28] Will: My favorite thing when we went to that first Mad God video, we went over there to see was like walking through Phil's graveyard of toys and potential Mad, Mad, Mad God set and costume and creature design stuff. It was incredible.

[00:07:42] Adam: Well, and it you know Jamie and I used to talk about this in light of the of the kind of builds that would come out of his shop. Every shop. Every single shop, whether it's in your closet or in a case or in a building or a room, is a philosophy about how to work, and the things that are kept in that shop inform what then later comes out of that shop. And yeah, I being having been in Phil's space many times and seeing the graveyard, there's a type of shopping that he does with his mind, with his with his aesthetic through that graveyard. That's really important to projects like Mad God, and it's really exciting to watch them grow out of this, you know, labeled boxes of things like long sliders and little balls and

[00:08:28] Will: like scaffold rusted scaffoldings. And yeah,

[00:08:32] Adam: exactly. I finally, I, I because I, I don't know, I was an idiot, I couldn't get around to it, but I finally watched the last two episodes of the Good Place,

[00:08:32] Will: oh,

[00:08:32] Adam: season two.

[00:08:32] Will: Oh, Okay,

[00:08:32] Adam: I just missed those two. What's that?

[00:08:44] Will: Turns out they were really in Shangri-La the whole time.

[00:08:48] Adam: That was. I can't wait for season three.

[00:08:48] Will: Okay,

[00:08:51] Norm: what what a nice. I mean. It is a show that does not. It starts off with a premise, and I know we talked about the show a bunch. It starts off with a premise, but does not stick just with that one premise.

[00:09:00] Adam: No, we’re now on, we're now on a third premise.

[00:09:00] Norm: Yeah, exactly.

[00:09:02] Adam: Not just

[00:09:02] Will: one premise a season. Okay, I got it.

[00:09:04] Adam: Yeah. What what what what else did you guys want to talk?

[00:09:09] Norm: Oh well, yes. Will

[00:09:09] Adam: I had a question for you?

[00:09:11] Adam: Well, I mentioned Frank Oz this morning, and then you said, " Have you seen that show?" He tweets about

[00:09:17] Will: at like eleven o'clock on many nights. Frank Oz will just blast out a retweet.

[00:09:22] Norm: [unclear: Yoda thought / Yoda Thos].

[00:09:22] Adam: Wait, by the way,

[00:09:23] Norm: at [unclear: Yoda / Yodathos].

[00:09:24] Adam: Frank Oz, new to Twitter, is slaying at Twitter.

[00:09:27] Will: I I love like new celebs, like famous people new to Twitter is almost always entertaining or terrible, one or the other.

[00:09:33] Norm: What do you think? Do you think they find that they're surprising engagements, like that they don't they aren't as connected because a lot of times people like Frank Oz or even someone like Phil Tippett, they don't necessarily work. They they're in their studios or doing their work. They're in L. A. Or whatever. But when they go to a convention and get one one on one time with fans, you know it changes their perception of how their own work is perceived.

[00:09:55] Adam: Sure, absolutely, and and and people like you know people like us who have been on Twitter for a long time, we we play within the ethos of Twitter.

[00:10:04] Will: There's a game, yeah.

[00:10:05] Adam: You like, you retweet, you quote, you talk about, you you know, it's all that kind of stuff. So when a new celebrity shows up and they don't they don't quite get it.

[00:10:16] Will: Oh, it's really good

[00:10:16] Adam: in the best way.

[00:10:16] Will: Yeah.

[00:10:16] Adam: But so what they do, like, so what I mean by not getting it is that like what Frank's been doing in posting stories and posting quotes about what it's like to work with Jim and with the other Muppeteers and stories from movies that he directed and movies that he's been in, he is elevating and changing Twitter a bit, like every new arrival, and saying maybe these are the stories that people are interested in. The answer is yes, we are. It's really exciting to see something totally different. show up. Oh, yeah.

[00:10:43] Norm: Thank God for two hundred eighty characters.

[00:10:46] Will: So, what? A couple nights ago, he started tweeting. It's the second or third time I've seen him do this since he since he came on Twitter. Which I assume was for the Dark Crystal re release. Maybe I don't know why he's why he's suddenly on Twitter. Like I don't know why you in twenty eighteen look up and are like, man, I should really get get a Twitter account finally. It's time.

[00:11:02] Adam: I I haven't asked him, but I will. Maybe I will.

[00:11:07] Will: I wouldn't. I probably wouldn't actually. But hey, yeah, but but yeah. So he started tweeting about this magic show in New York that I think is a Broadway

[00:11:15] Adam: in and of itself. It's off Broadway.

[00:11:15] Will: Off Broadway.

[00:11:15] Will: Okay.

[00:11:15] Adam: It's on a small theater off of Union Square in New York, and it's called In and of Itself, and it stars Derek DelGaudio. Derek Delgaudio is an unbelievable magician. A magician. I'm not sure if this is

[00:11:31] Will: what kind of magician is he.

[00:11:32] Adam: Well, he's. I don't. I'm not sure if I'm correct in saying this, but he's a magician that hates magic.

[00:11:38] Norm: I think, I think…

[00:11:39] Norm: hates the routines, or hates the…

[00:11:41] Adam: he doesn't like the. He wants magic to be something. More essential and more pure, and that sounds like a terrible lead-in to something that's going to be pretentious. But

[00:11:53] Will: Penn and Teller hate love magic, but hate magicians. I think

[00:11:56] Adam: so. There's there is a little in the in the same way that Penn and Teller were a left turn for magic, and they really push magic in a new direction. I think I Derek is the same kind of amazing A new direction. In and of itself, is a 70 minute show with six magic tricks in it.

[00:11:56] Will: Wow!

[00:11:56] Adam: And every one of them is the likes of which you haven't seen.

[00:11:56] Will: You’re you’re

[00:12:21] Norm: is it storytelling?

[00:12:22] Will: Breathless.

[00:12:23] Adam: I am. I actually got a little choked up when I when I started to talk about the framework of it. 70 minutes, six magic tricks. I've seen it three times now. It played for the longest time at the Geffen in L. A. , then it moved off Broadway where it's been repeatedly extended, and it's playing through August

[00:12:23] Will: Something.

[00:12:23] Adam: of 2018. Listen, it is worth flying to New York to see this show.

[00:12:44] Norm: It's like a three Michelin star.

[00:12:46] Will: [unclear: Nor do you / Nor where you / we] want to go

[00:12:46] Adam: sitting sitting in a theater and watching this show unfold. Plus, having watched the show, I saw it within the within its first week of opening at the Geffen, and then I saw it a few months later at the Geffen, and then I saw it off Broadway. And a show like this, Derek and Frank Oz directed it.

[00:13:03] Will: Oh, okay.

[00:13:05] Adam: That is why we're talking about it in relation to Frank Oz.

[00:13:07] Will: And good context.

[00:13:08] Adam: Derek reached out to Frank a few years ago and said, " I have this show I want to do. You need to direct it. If you won't direct it, it won't happen."

[00:13:08] Will: Wow.

[00:13:08] Adam: And they've talked, and so this is a show. It's not just like they wrote it and put it up, and now it's been running. They are always working on it. They're always refining it and tightening it, and thinking about its overall trajectory. And I have to say, it's really like what's happening off Broadway is so much different and even deeper and stranger and cooler than the than the Geffen show.

[00:13:41] Will: People describe it as a spiritual experience. Like people come out of it and seem kind of shook.

[00:13:46] Adam: Well,

[00:13:46] Will: in a good way.

[00:13:47] Adam: Yeah, and it feels like that. It definitely feels like that. There's a there there's a mentalism trick in that show that I think I have a bead on how it works, but holy cow, is it mind blowing? And I'm still not positive.

[00:14:01] Norm: Wow, that's like the kind of like pick a word. I know the word you're thinking of, kind of thing, or the

[00:14:06] Adam: it's so much more.

[00:14:08] Norm: But in the essence, like it's reading someone's mind.

[00:14:10] Adam: And look, I I suspect that you know I could find out. There's a couple, you know probably ask Derek. Can he tell me? But I don't want to ask him.

[00:14:10] Will: No,

[00:14:10] Adam: I like this is Julia Sweeney once said, " Magic is all us atheists have left." Um, and I, you know, atheist is a I say agnostic. It's more scientifically pure, I think.

[00:14:10] Will: Yeah,

[00:14:10] Adam: but yes, you sit in that theater and you watch that show happen, and some it's something remarkable, and it's only could happen in that room.

[00:14:37] Will: So the first place I heard about this show was somebody I think South by or Sundance was presenting something and kind of ripped off the initial the initial walking in the theater experience.

[00:14:48] Adam: So I, Yeah, so. When you walk into Derek's,

[00:14:51] Norm: whoa! I don't want.

[00:14:52] Adam: Well, yeah,

[00:14:53] Norm: without getting into spoilers. Yeah,

[00:14:54] Adam: let's. I

[00:14:55] Adam: don't want to get too far into this because

[00:14:56] Will: it's on all the marketing.

[00:14:57] Adam: It telegraphs. Yeah, somebody at South by, and it probably was one of these things where someone said, " You got to figure out something great by tomorrow," and

[00:14:57] Will: yeah,

[00:14:57] Adam: some young intern who really didn't know better. I am really giving them the benefit of the doubt because it was such an obvious lift,

[00:15:10] Will: actually. But Yeah,

[00:15:11] Adam: at Sundance, and they they basically copied this whole framework of the entry into into Derek's show in for this opening at Sundance, and it was shitty. And they were it was a dumb move on that on that part, and it was sad.

[00:15:29] Norm: But when you say six magic tricks in seventy minutes, it means that the seven the construction of the seventy minutes is is the like the performance. It's not just the six tricks.

[00:15:40] Adam: No, it's not about the tricks. The tricks are in service of a narrative, not the other way around,

[00:15:47] Norm: and that's why it's suitable for Broadway and off Broadway.

[00:15:49] Adam: They push. And extend and deepen that narrative.

[00:15:52] Will: So I was going to say, like when we saw Penn and Teller's show in Vegas, which is the most recent big magic show I've seen, they do maybe ten tricks in an hour, hour and a half,

[00:16:02] Norm: maybe a little more than that. Yeah,

[00:16:03] Will: yeah. It's not. It's not. It isn't that much,

[00:16:06] Norm: but the story behind each trick, as they're executing, you know, as they're communicating with the audience, that's the fun part.

[00:16:11] Adam: This is one guy on a small stage telling some autobiographical stories within a framework that is like every good story a universal, a set of universal truths about what it is to be a person and to to realize who you are and and what you are.

[00:16:29] Will: I'm very curious about this.

[00:16:29] Adam: Oh God, it's so good. It’s, I want everyone in the world to see this show.

[00:16:34] Norm: What else has he done? Has he have other like? If you go on YouTube, can you find examples of his presentation?

[00:16:40] Adam: Well, okay. So magicians out there who listen to this podcast, please forgive me, as I am not. Officially a magician, I just know a lot of magicians. I may have some of the facts wrong here.

[00:16:52] Will: You are magician adjacent,

[00:16:52] Adam: but within card magic, most of all the tricks in card magic went started their lives with card hustlers and cheats, and made their way to magicians. There is a unique outlier out there, a type of shuffle called the Zarrow shuffle that actually went from magicians to card cheats. And Derek Delgaudio, one of his early bits of fame was in modifying and coming up with a thing he calls the Delgaudio shuffle, which is a shuffle in which he takes cards, riffle shuffles them, bridge shuffles them, and they are still in the exact same order as when he started.

[00:17:33] Will: How in the hell does he?

[00:17:34] Adam: Okay, I’ve I’ve seen him do it right in front of me, and it's mind-bending. and He's a he's truly a beautiful card mechanic, as well as. A deeply thoughtful storyteller, and so the DelGaudio Shuffle is something you can see on YouTube. You can see people doing it. You can see how remarkable it really is. You can you can purchase, I think, a guide on how to on how to do it. I don't want to know how it's done. And he had another previous run at the Geffen, which was another kind of unmagic show. But Derek is a major. Like, he’s a disclosure. He's a friend of mine. Went out to dinner last time I was in New York and saw the show along with a Carbonaro from the Carbonaro Effect. Okay. And like, it's just it's such a refreshing bit of theater that's totally unique. Let's just say that it's a refreshing bit of theater that's completely unique.

[00:18:28] Will: Currently scheduled to end in August.

[00:18:30] Adam: Currently scheduled to end in August. I think this is the last extension.

[00:18:33] Will: This is it. Okay. Okay. Wow. I got to get to New York.

[00:18:36] Adam: Yep.

[00:18:37] Norm: All right.

[00:18:37] Adam: You got to go.

[00:18:38] Norm: I know. Gonna book those tickets.

[00:18:40] Will: I need an excuse to go to New York.

[00:18:42] Will: I think World Maker Faire is going to be too late.

[00:18:44] Norm: Yeah. Yeah.

[00:18:46] Unknown speaker (Adam or Norm): Okay.

[00:18:46] Adam: What else do we want to talk about? There's one other thing.

[00:18:49] Unknown speaker (Adam or Norm): What was it?

[00:18:49] Norm: While we think about that, I've been following the stuff that's been coming out of South by Southwest.

[00:18:49] Adam: Yes,

[00:18:49] Norm: and we we all love Westworld, the TV show,

[00:18:49] Unknown speaker: Mm-hmm.

[00:18:49] Norm: right? Did you see that at South by they set up a Westworld activation?

[00:19:02] Will: They did. This is the second time they've done it.

[00:19:04] Norm: This is much bigger.

[00:19:05] Will: Oh, really? Is this what we wanted it to be the last time they did it?

[00:19:08] Norm: Yeah, well, I went to the one at New York Comic Con where they had

[00:19:11] Will: I love a good activation.

[00:19:12] Adam: Was this people you could stab.

[00:19:13] Will: I love violence.

[00:19:15] Norm: No violence, no sex.

[00:19:16] Will: They're not people, okay? They're robots.

[00:19:16] Adam: Yeah.

[00:19:19] Norm: They found a ghost town, I guess, outside of Austin and bus people there, hundreds of people, and had like one hundred actors in costume with a four hundred page script for two hours that did a immersive theater experience in the spirit of Westworld.

[00:19:38] Will: Okay, so I did an escape room in LA that was an off brand knockoff Westworld escape room, yeah, and having real actors behaving like the robots do in Westworld, I found to be profoundly disturbing. Like, like

[00:19:50] Norm: yes, because you as a person know that they’re real actors.

[00:19:52] Will: I know that they're a real person,

[00:19:54] Norm: And yet they're inviting you to treat them not as like

[00:19:56] Will: non-human, and it was it was incredibly discomfiting

[00:20:00] Norm: because you have empathy.

[00:20:00] Adam: That sounds really upsetting,

[00:20:01] Will: yeah. I I didn't like like there were women behaving in like it was very uncomfortable. Like I'm I'm all it's it's all of the things that I don't like about interactive.

[00:20:10] Norm: The question is, would you have behaved behaved differently if it was if you knew that it was a robot, if it was not a real person?

[00:20:18] Adam: Oh, it's an impossible question to answer.

[00:20:19] Will: No, I don't think. I mean, look, I don't think I'm going to go to Westworld. Right? If if we have the option to go to Westworld, I'm probably going to opt out.

[00:20:26] Adam: Ah,

[00:20:27] Norm: you don't know. You don't know

[00:20:27] Adam: that. It creeps me the hell out.

[00:20:29] Will: Yeah, I I I stopped watching the show. I I didn't get to the end of the show.

[00:20:33] Adam: Oh, really?

[00:20:33] Will: Yeah.

[00:20:33] Adam: Oh, so look, I love the show. I love the show. I watched it. I watched it all the way through, and there is some. There's some. There's some chaff in that wheat. Like I I felt like at the end of the second season, I felt like there was

[00:20:50] Norm: yeah, and then a first season.

[00:20:51] Adam: There was some slow. Oh, sorry, first season. There was

[00:20:53] Will: The second season was so long. It felt like two.

[00:20:55] Adam: But you know, anything that exposes the world to Evan Rachel Wood and her incredible acting, I'm. We've been fans of hers since she was a genius on Once and Again. She's in, just an unbelievable talent, and actually, the entire cast of that James Marsden and and

[00:21:15] Will: Thandie Newton,

[00:21:17] Adam: Thandie Newton. Oh my God!

[00:21:17] Will: Yeah,

[00:21:17] Adam: she's my favorite character on that show.

[00:21:21] Will: I, I, I have no like the performances are incredible. Yeah, like the show just made me feel really, really bad about humanity in general.

[00:21:21] Adam: Oh, completely, that’s.

[00:21:21] Will: That's why I stopped.

[00:21:31] Adam: Yeah, that’s, it’s. Oh, and and Jeffrey Wright, Jeffrey Wright is one of those actors who is like, holy cow, what an amazing! I mean, he got his big break in Basquiat, Julian Schnabel’s film about the artist Basquiat, and it's that's an incredible film. That's really amazing, and Jeffrey Wright was I showed up in one of the Bond, a couple of Bond films, Felix.

[00:21:52] Will: Um.

[00:21:52] Adam: Oh right, yeah.

[00:21:55] Will: Well, and he was in Hunger Games too, right?

[00:21:57] Adam: I had no idea.

[00:21:57] Will: Yeah.

[00:21:58] Adam: I haven't seen those.

[00:21:59] Will: No, they’re they like like battle royale, but a little slower.

[00:22:03] Adam: Yeah, I'm looking forward to the second season of Westworld. I'm looking forward to some comeuppance from the bots.

[00:22:08] Norm: It's a really interesting. So the two showrunners, Lisa Joy and Jonathan Nolan,

[00:22:13] Adam: Christopher Nolan's writing partner and

[00:22:15] Adam: brother,

[00:22:16] Adam: or brother and writing partner.

[00:22:16] Norm: No, no British accent. So weird. They were at South by Southwest talking about the writing of this show and how this show, I think, like many cultural phenomenons or TV shows that are serialized and come out one week by week, engage with the fans in a certain way, which is in a way that perhaps a Netflix show that drops all its episodes out cannot.

[00:22:16] Adam: I think because

[00:22:16] Norm: you don't have the week to week

[00:22:44] Adam: serialized,

[00:22:45] Norm: serialized Yeah. the week, the wait,

[00:22:46] Will: right? Well, you need you need to think about it, right? Like if you think about if if if they had dropped 23 episodes of Lost at one time, you wouldn't have had that that week. To digest and think about and run through all the potential outcomes.

[00:22:58] Adam: You’ve talked about this. Yeah, you, you. I don’t like bingeing. you have held to watching shows like that one night, one in.

[00:23:03] Will: I've given up on it. At this point, it's all, look, I watched six episodes of The Good Place at once.

[00:23:07] Norm: But, but they're saying like specifically communities like in Reddit had, were so engaged with the show that

[00:23:14] Norm: most of the plot twists and turns that came out of the show were already predicted in one form or another.

[00:23:18] Adam: Oh, sure.

[00:23:19] Norm: And that's something that can't be avoided.

[00:23:21] Adam: Yeah.

[00:23:21] Norm: And the, the, uh, the broader media outside of those communities already know of the communities and then

[00:23:27] Norm: spread like the theories like wildfire. You know, your Entertainment Weeklys, your varieties, all tap into the communities.

[00:23:33] Will: The podcasts and stuff that spring up.

[00:23:35] Norm: They, they do Westworld Space Forum.

[00:23:37] Adam: Yeah.

[00:23:37] Norm: And they, and find all the theories and that if you choose to engage with the show, you will maybe have a likely chance of getting spoiled.

[00:23:46] Norm: So being cognizant of that, they say that they're going to do something different with season two where they're going to embrace that.

[00:23:53] Adam: Oh, so that the, the, excuse me, the trajectory of the show might Be altered by the fan engagement?

[00:23:59] Norm: They are not being specific about it.

[00:24:00] Will: They're going to release one episode a month instead of one episode a week.

[00:24:03] Norm: But I'm really interested in seeing what they're doing.

[00:24:03] Adam: Yeah, yeah, yeah.

[00:24:03] Norm: because you know they're savvy with the internet and the community.

[00:24:09] Adam: Indeed,

[00:24:10] Will: it seems like two decades ago that Westworld came out.

[00:24:10] Adam: Yeah, I know,

[00:24:10] Will: like it literally seems like 10 years ago.

[00:24:17] Norm: There’s been a lot of good stuff out there.

[00:24:18] Will: Well, I wasn't thinking about that, but okay.

[00:24:21] Norm: Oh yes, and a lot of a lot of not so good stuff out there.

[00:24:23] Will: Remember when you woke up this morning? That was three years ago.

[00:24:26] Adam: That was that was the opening of Patton Oswalt's last comedy special, where he gets up on stage and he goes, " Oh, how about that?" And there's a confused pause from the audience, and he goes, " Oh, you guys haven't checked Twitter in the last few minutes?" And there’s this like gasp, and he goes, " Doesn't it suck that we live in a world where that's possible? Like every minute could be like, oh, you don't know about the shit that's just hit the fan?

[00:24:51] Will: Yeah. Oh yeah.

[00:24:54] Unknown speaker (Adam or Will): Woo. Um."

[00:24:56] Norm: Quick hits? Any quick hits?

[00:24:57] Adam: Let's see. Getting ready for Silicon Valley Comic Con.

[00:25:00] Norm: That's right. We are.

[00:25:01] Adam: We have a special guest coming to visit the shop.

[00:25:04] Norm: We're not going to it’s a special project that we will be unveiling

[00:25:07] Adam: at there

[00:25:07] Norm: at Silicon Valley.

[00:25:08] Adam: And we're currently making plans for San Diego and New York beyond that. So the cons are happening.

[00:25:15] Will: I finished Altered Carbon finally.

[00:25:17] Adam: Yes, look, people have been begging us to do a spoiler cast in Altered Carbon. I've only watched the first episode.

[00:25:22] Norm: Can’t muster the energy.

[00:25:23] Will: It's it's hard. Like it's a hard show. I don't know that I would have stuck with it if I hadn't been a. I'm a. I love the books. Richard Richard Morgan's books are really good, even though they're a little misogynist and like where they are now versus where they were when they were written. Yeah. Um. I I don't I don't know that they stuck the landing with Altered Carbon, but I enjoyed watching it for set design and world and and if nothing else, and it hits some real hard high sci high like hard science fiction concepts that are that you don't often see in TV outside of stuff like The Expanse.

[00:25:54] Adam: Um. The the the lead actor Joel.

[00:25:57] Norm: Kinnaman,

[00:25:57] Adam: Kinnaman. Yeah, I wanted to say Edgerton, Kinnaman. Um, one of my favorite voices in Hollywood right now.

[00:26:03] Will: He's got a good. He's got a. He's got a real face for acting, Like he's got a Karl Urban kind of like very unique look.

[00:26:10] Adam: But his like at one point his body is so sculpted it's actually disconcertingly pushed me out of the narrative.

[00:26:19] Will: So is there is the first episode doesn't have the other Takeshi Kovacs right?

[00:26:24] Adam: I don't think so.

[00:26:24] Will: Um, you're Kovatch. So, the other guy who plays. So the setup of the show is that you can be your your consciousness is is fungible. You can be beamed from body to body,

[00:26:35] Adam: uploadable to new body,

[00:26:36] Will: and it's about class warfare. Like the. Right. ultimately, the the whole thing is about the the old people who have had started out with a lot of money were able to transfer from body to body, while the poor is when they run out their first body just get dumped into long term storage, and um the young Takeshi on the planet he grew up on, I like that actor a lot.

[00:26:36] Adam: Oh, okay.

[00:26:36] Will: Like I like, yeah. Like it's a.

[00:26:59] Norm: He was, in the Wolverine.

[00:27:02] Will: Yeah.

[00:27:02] Norm: One of the.

[00:27:02] Norm: Yeah.

[00:27:02] Norm: Japanese actors.

[00:27:03] Will: Um, it's a like I I think not a knock against um what what's his name? Sorry, Norm.

[00:27:09] Norm: Joel Kinnaman.

[00:27:10] Will: Joel Kinnaman. Yeah, but but

[00:27:11] Norm: RoboCop.

[00:27:12] Adam: Uh,

[00:27:12] Adam: The Killing.

[00:27:13] Will: Oh. Okay.

[00:27:14] Adam: Yeah.

[00:27:14] Norm: House of Cards.

[00:27:15] Will: Yeah, yeah. Um. Anyway, yeah, it's I I

[00:27:18] Adam: what is he in House of Cards? So that I've missed the last couple of seasons?

[00:27:20] Norm: He plays the other presidential candidate.

[00:27:23] Adam: Ah. Okay.

[00:27:23] Will: Oh man,

[00:27:24] Norm: the competing one.

[00:27:25] Adam: I have that. This is stuff I hadn't seen yet.

[00:27:28] Will: Like it's interesting. I don't know. I don't know. Like if you're if the first episode grabs you, keep going. You'll be rewarded. If not, the final the last couple episodes are both problematic and really, really incredibly well done, which is it's thought provoking, I guess.

[00:27:40] Adam: Um and in the uh, uh, uh next podcast I want to say we're going to talk about uh we're going to talk about Frank Oz's film Muppet Guys Talking. I’m just giving a shout-out.

[00:27:49] Will: We can see it now?

[00:27:50] Norm: Documentaries.

[00:27:51] Adam: Not quite yet. Um, but. Yeah, maybe I haven't seen it yet. I I I had multiple opportunities. I've just been in the wrong city each time an opportunity has presented itself.

[00:28:03] Norm: Love a good documentary.

[00:28:03] Adam: Yeah.

[00:28:03] Norm: Do you see a South by that? There's a new. There's a documentary about the making of the Last Jedi.

[00:28:08] Adam: Oh, really?

[00:28:09] Norm: Where they followed. I forget the name of the documentarian, but followed Rian Johnson and the cast and crew, where every day on set everyone was mic'd up.

[00:28:18] Adam: Oh wow!

[00:28:19] Norm: And so they just unfettered access. Yeah, can't wait.

[00:28:19] Adam: Ish.

[00:28:19] Norm: Ish. Ish.

[00:28:23] Norm: of course, of course.

[00:28:25] Will: I’m, I’m very excited about watching Last Jedi again. I I I saw it three times in theaters. I didn’t, yeah, I thought it was probably okay, but I’m I’ve been thinking, it's been in the back of my head rattling around.

[00:28:35] Adam: Awesome.

[00:28:35] Will: Yeah.

[00:28:35] Norm: Yeah.

[00:28:35] Will: And you should go watch Paddington too.

[00:28:38] Adam: Paddington two. We're gonna we're gonna bracket this podcast with Paddington two.

[00:28:43] Will: Yeah.

[00:28:43] Adam: I'm gonna watch it this week. I promise.

[00:28:45] Will: Please do.

[00:28:45] Adam: I'm not sure I'm gonna watch it this week, but I'm gonna try.

[00:28:48] Will: See you guys next week.

[00:28:49] Norm: All right.

[00:28:49] Adam: Thanks guys.

[00:28:49] Norm: Bye.
