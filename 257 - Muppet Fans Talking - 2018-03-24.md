**Podcast:** Still Untitled: The Adam Savage Project  
**Episode:** 257 - Muppet Fans Talking  
**Date:** 2018-03-24  
**Duration:** 29m 48s  
Episode URL: https://www.youtube.com/watch?v=f6xleZljF3c

[00:00:03] Will: Welcome to Still Untitled: The Adam Savage Project. I'm Will.

[00:00:06] Adam: I'm Adam,

[00:00:07] Norm: and I'm Norm.

[00:00:07] Will: I just love trolling Norm with it at this point.

[00:00:09] Norm: He's waiting for me to start the podcast.

[00:00:11] Will: The hand was just moving ever so slowly.

[00:00:13] Adam: The the the the um the sort of deep ways you guys control each other is is uh is funny.

[00:00:20] Will: Look, we've known each other for long enough that as you as you have said in the past, we installed each other's switches.

[00:00:20] Adam: Yeah, absolutely.

[00:00:20] Will: Um,

[00:00:28] Adam: well, good afternoon.

[00:00:28] Will: Yeah.

[00:00:28] Will: Hey, welcome back.

[00:00:28] Adam: Thank you. Thank you. I've been I've been home for an inordinately long amount of time, like without big trips for like two months. No, no, not even

[00:00:40] Norm: not not even. But it feels like because it feels like we've seen you a lot when we come to the shop.

[00:00:45] Will: Yeah, I just had a regular like Monday morning date to come over here and and chat for the last few months, which is nice. It's a it's nice to have a schedule.

[00:00:51] Adam: It is really nice. Um, but I was just traveling this week with Joey Fameli, we were down in Palm Springs at Jeff Bezos Mars Conference.

[00:01:02] Norm: Now Mars does not mean Mars the planet.

[00:01:04] Adam: No, it stands for machine learning, artificial intelligence, automation, robotics, and space exploration.

[00:01:14] Will: Oh yeah, the four, the four, the most four most important nouns.

[00:01:18] Adam: Of course, it was about two hundred attendees, two hundred of the just some of the best people in the world in each of those fields, and it was really wonderful. You know, I guess if you looked at it from outside, it looks a little like TED, right? Because there's talks. You several people make presentations on a couple of the mornings, but the the comparison ends there because this is a much more highly curated in every aspect kind of event where dinners each night you're at a table for six people and you're like. Your place has been.

[00:01:55] Will: You have assigned seating.

[00:01:56] Adam: You have assigned seating. So you always sit with, in my experience with Amazon events like this, and this is not the first one I've been to. Um, you're always at your table. There's always someone you know, and there's always someone you don't know.

[00:02:09] Will: So it's like doing a wedding table chart or something, yeah.

[00:02:11] Adam: And they do it really, really well. So I had some of the best conversations I've had in months this week.

[00:02:18] Will: Do you think they're using machine learning for that? Like they feed you into the algorithm. They're like, okay, Adam knows these sixty people.

[00:02:23] Adam: We did. God, we got so much machine learning stuff. Marc Raibert, Boston Dynamics was there showing how Spot Mini navigates through a room.

[00:02:34] Norm: This is the robot from Black Mirror season four.

[00:02:36] Adam: It is not that robot.

[00:02:38] Norm: Oh, it's the one

[00:02:39] Adam: everyone saw Jeff Bezos taking out for a walk the other day.

[00:02:41] Will: Yeah. Is it the one with the hand that opened the doorknob and then the other one goes through? Okay.

[00:02:44] Norm: The yellow one.

[00:02:44] Adam: Yeah.

[00:02:46] Will: That's so cute and menacing.

[00:02:47] Adam: It's really cool. So you got to see how Spot Mini looks at a room. And then estimates the best and and compiles the best way to move through that.

[00:02:56] Norm: And does it have a lidar spinner on top of its head?

[00:02:59] Adam: It doesn't have a lidar spinner on top of its head. Some of their bots do. Spot Mini is using a different kind of machine vision, and I don't actually know its specifics. I just know that there wasn't a big spinning thing on its head.

[00:03:10] Norm: Okay. But the the visualization of what it sees in terms of on the stage, because that's a clip I think I saw on Twitter.

[00:03:10] Adam: Yeah.

[00:03:10] Norm: Someone posting, it was pretty detailed, and it was more more importantly the decision making it was making in terms of how to navigate the environment.

[00:03:10] Norm: Not just the mapping.

[00:03:24] Adam: And it's it's cool the way it breaks it down. So it looks if there's like posts and stuff like this, it first makes a path for its torso, and then it looks at the ground and separates the ground into steppable space, which is green, and unsteppable space, which is red. So if it's like stones, it's looking for the ones in which they the you know it's flat,

[00:03:42] Will: looking at flat, and whether it's like an uneven surface like gravel or roots or something like that.

[00:03:48] Adam: And then in a plan view, what they showed us was it looks at its its Its torso path and the red and green step spaces, and it estimates a cadence.

[00:03:48] Unknown speaker: Huh.

[00:03:48] Adam: And if that cadence doesn't work, it tries a slower one or a faster one until it gets one that seems to work. And it's constantly adjusting this view.

[00:04:07] Norm: So it's it's not standing still, deciding, and then walking. It's doing this while

[00:04:11] Adam: while it's going.

[00:04:12] Will: Wow. When when Norm and I went to that DARPA thing, the robotics challenge, a few years ago, and we were talking to people, one of the things I didn't realize is that most of the robots like always stay over the center of gravity, which is not at all the way normal.

[00:04:12] Adam: Yeah,

[00:04:24] Adam: people don't walk like that.

[00:04:25] Will: We're constantly in a state of falling and just putting the foot out to catch us.

[00:04:29] Adam: And there's this whole thing I can't remember the specifics of it that came out of Cal a long time ago about how all bipedal beings walk in this sort of reverse pendulum mode where you're falling and then you're it's that it's that balance between potential and kinetic energy as you move.

[00:04:44] Will: Yeah, there's there's a it's all it's all in the hips.

[00:04:47] Adam: It turns out it's all in the hips.

[00:04:48] Norm: It's a fine line between looking like you're drunk and looking like You're walking with intention,

[00:04:52] Adam: or, or in the case of Asimo, looking like you just shit yourself.

[00:04:56] Norm: Squat.

[00:04:56] Will: I've soiled myself.

[00:04:58] Adam: My friend Ken Goldberg from Cal also showed how difficult it is for a robot to look down at a bin full of stuff and pick something out.

[00:05:08] Norm: What does that mean?

[00:05:09] Adam: Well, so it looks at a bin full. Like think about the stuff on this table. Now it's going to look at this stuff. First of all, the bottle's a nightmare because it sees through it.

[00:05:09] Norm: Yeah.

[00:05:09] Adam: It's going to look at something like, let's say the bottle isn't clear and it's looking at it. So now it's going to say, okay, I'm going to guess that the highest percentage pick points are here.

[00:05:29] Norm: Okay.

[00:05:29] Adam: Right.

[00:05:29] Norm: Grabbing around the bottle,

[00:05:29] Adam: but it also has to kind of build a model of the object in order to determine that, and it has to estimate the rough physics of that object,

[00:05:37] Norm: like where the center of weight is,

[00:05:37] Adam: right?

[00:05:37] Norm: How much it weighs.

[00:05:37] Adam: Exactly.

[00:05:37] Norm: Because it knows its arm, but its arm has different strength profiles based on how far it's extended,

[00:05:37] Adam: yeah,

[00:05:37] Norm: and how it's grabbing

[00:05:47] Will: and like. How rigid the the thing is like this versus an aluminum can. The aluminum can it's going to grab it and it'll crush it.

[00:05:52] Adam: Well, and this that's part of the estimation process. And then talked he talked he showed some of the items that just can't be picked up, like a washer.

[00:06:01] Will: Oh, yeah, I can see that

[00:06:02] Norm: because there's two so flat.

[00:06:03] Adam: It's it's so flat. You so there's two ways they can pick it up with a grasp or they can pick it up with a suction cup.

[00:06:03] Will: Yeah,

[00:06:03] Adam: and both work great. But like a washer, neither

[00:06:11] Will: it's invisible. Yeah,

[00:06:12] Adam: no.

[00:06:14] Norm: I'm feeling pretty good about team humans now.

[00:06:15] Adam: Clear plastic bottles, a nightmare.

[00:06:15] Will: Oh, interesting.

[00:06:15] Adam: Um, and a bottle of Hershey's chocolate syrup.

[00:06:24] Will: There's the can,

[00:06:24] Adam: no,

[00:06:24] Adam: the bottle, the plastic one with the

[00:06:27] Adam: yeah, yeah. They're like because the stuff in it moves.

[00:06:32] Will: Oh, and it's topologically weird.

[00:06:33] Adam: Topologically weird.

[00:06:35] Will: Oh man, I so I guess that's why like when you look at factory lines, even now in 2018, like there's still at the end of the line or different places along the line where they need to do quality checks. There's humans sitting there watching all the stuff go by.

[00:06:47] Adam: Well, and Ken and I were talking, you know that that thing that you see factory bots do is like one thing precisely every time. Robots are fantastic. But that doesn't mean they're actually good at picking stuff up. That just means they're good at being programmed and repeating their steps.

[00:06:58] Norm: Very precise, some millimeter. Yes, but no variability.

[00:07:02] Adam: No, and to give you an idea, like I think a highly skilled person can pick up six hundred objects an hour, and the best robot in the world is like two hundred.

[00:07:12] Will: Can but robots? But turns out, you know what, Adam? You don't have to pay the robots. So let me tell you,

[00:07:19] Adam: there was also a couple of amazing talks about gravitational wave detection, both from both using LIGO and also using pulsars,

[00:07:27] Will: the newest form of of astronomy.

[00:07:30] Adam: Yeah.

[00:07:30] Will: Yeah.

[00:07:30] Adam: really, really amazing. And so there were talks, there were dinners, but also there's all this after hours stuff, and there's there's there's activities to go to. So there's just tons of time to have these conversations that are literally mind blowing with the people. So at one point, I'm talking to this guy, and he's a Kiwi, and he says, " I'm a rocket scientist, and you know, I'm from New Zealand. " I'm getting his accent terrible. Sorry. And he says, " I said, oh, I was just there. I love your country. I was just there in January." He says, " Oh, I launched my rocket in January. We stopped the whole country." And I'm like, " You stopped the whole country? I think I heard something about that." He's like, " Well, now you're just being polite." And I was like, " No, I don't think so. I think I heard about it." And he's like, " Well, I did add a very special payload to my rocket." I'm like, " Oh, you're the disco ball guy." And he was like, " I'm the disco ball guy." So he launched at the top of his. First of all, his name is Peter Beck, and he established a treaty between the U.S. and New Zealand to allow him a spot on the east coast of New Zealand where he can launch a rocket every 72 hours. He has a greater launch capacity in his one site, New Zealand, than the United States has. And he builds these composite rockets with 3D printed electric motors, and he can launch microsatellites into the into into orbit.

[00:08:51] Will: Is he the guy that's in? No, he's not the guy that's in trouble for launching the unsolicited.

[00:08:56] Adam: Yes, that's him. No, no, no, not that's a different one. No, he launched. But what he launched was a geodesic,

[00:08:56] Will: Yeah, yeah.

[00:08:56] Adam: polished dome that that that flashes as it flies across, and he pissed off astronomers all over the world.

[00:09:09] Will: Oh yeah, because I'm sure it's messing up their plates.

[00:09:09] Adam: Right, exactly.

[00:09:09] Will: Oh man.

[00:09:13] Adam: He, what he was trying to do is so noble. He was attempting to replicate his experience where his father brought him out and said, " Look up, you see that thing moving across the sky? That's a satellite."

[00:09:13] Will: Yeah.

[00:09:13] Adam: And he was like, " Whoa, that's my overview moment. That's the moment at which I realized we weren't, you know, alone. That there was this bigger universe." And he wanted to give that to people. Um, it's going to come out of the atmosphere in a literally like within the next few days. But we got up at 5:31 morning and we actually watched it, and we got to watch it sparkle three times as it went across the sky, and we got a bonus shooting star.

[00:09:47] Will: Was it super bright?

[00:09:48] Adam: Um, it it was brighter than I thought it would be. So it's just spinning, right? So like a disco ball, every now and then that flash comes by you, and sure enough, three times across its arc, low on the northern sky, we were watching, we got to see it flash, and it was actually pretty noticeable.

[00:10:03] Norm: How did he prototype that?

[00:10:05] Adam: That's a good question. I don't know.

[00:10:06] Norm: It's just like you did the math.

[00:10:07] Adam: We had one there, it's just like a polished geodesic hollow aluminum sphere.

[00:10:11] Will: I was going to ask how electric rockets work. Is it is it just like I'm familiar with like peroxide and

[00:10:17] Adam: no? So it's an electric pump that pumps liquid oxygen into the combustion chamber.

[00:10:17] Will: Okay.

[00:10:17] Adam: So they they actually eject their batteries. I'm not going to get the technical technical stuff right, but it's battery powered pumps that he 3D prints.

[00:10:17] Norm: Wow.

[00:10:17] Adam: In like a day, he can 3D print one in a day,

[00:10:37] Will: and he can get small things to orbit. That's bonkers.

[00:10:40] Adam: Yeah. Yeah. No, it's totally amazing. And you know, again, like this was the kind of conversations you were having every every 30 minutes.

[00:10:48] Norm: That's invigorating.

[00:10:48] Adam: Yeah. No, it was,

[00:10:49] Norm: and also incredibly daunting. Well, it's the smartest people in the world.

[00:10:53] Adam: On the last night, Tuesday night, I'm like sitting there talking about what what perfect happiness really is, and I look down at one of the people I'm talking to, and it's Stephen Wolfram. You know, again.

[00:11:04] Norm: Now, if I search " Wolfram Alpha," what is perfect happiness?

[00:11:08] Adam: Maybe he has an answer.

[00:11:10] Will: Well, he quantified everything

[00:11:10] Adam: exactly.

[00:11:13] Adam: It was it was stunning. Joey and I were down there doing a project, which we'll be talking about later.

[00:11:19] Norm: And I think you were able to film some pieces for Tested.

[00:11:19] Adam: We we were.

[00:11:19] Norm: You guys out there will be able to see some some of the event. You also did a talk. I saw in the New York Times. You had some spacesuits down there.

[00:11:29] Adam: I did. I brought down I brought down a sextet of costumes along a similar theme: a 2001 spacesuit, alien spacesuit, Mercury spacesuit, Apollo spacesuit, King Arthur's armor, and my fireman's turnout gear with the helmet and oxygen mask.

[00:11:47] Will: All right. Is the fireman's turnout gear? It's it's real and everything else is…

[00:11:50] Adam: It's real. It's the one I wore on MythBusters for 14 years.

[00:11:50] Norm: Wow.

[00:11:50] Adam: And then I gave a talk about why these six costumes are really important out of my collection and why I wanted to bring them to talk about them. And actually, the work that I was doing down there, the costumes ended up being in a room that I was working and. Funnily enough, you go to going to conferences like this. It's always weird, and you're in a different zone, and you're you know trying to figure out what's going on. And it was so reassuring. I kept calling them my emotional support costumes because having them near me and having people walk in the room and talk to them about it. I was talking to Bezos at one point about the costumes and where these replicas came from. It was really invigorating to have my the things that I love near me.

[00:12:29] Will: Well, I mean, one of the things that that happens when you go to that kind of event is if they do it right, is you end up feeling almost like you're at grown-up summer camp, right?

[00:12:37] Adam: Which is exactly what this felt like.

[00:12:38] Will: Oh, that's that's super cool.

[00:12:38] Adam: Yeah,

[00:12:38] Will: it sounds really fun.

[00:12:40] Adam: It was it was intimate. It was super egalitarian.

[00:12:47] Will: So anybody could just go buy tickets and show up.

[00:12:49] Adam: No, not in that regard. I guess what I mean is there was no at some of these events there can be some toxic strutting from some of the like hyper high level people there. And people who've been to these conferences know what I'm talking about. It it it happens.

[00:13:08] Norm: The hierarchy.

[00:13:09] Adam: Yeah, this one was really. It was just a really even playing field for conversation and for learning from each other.

[00:13:16] Norm: Safe space.

[00:13:16] Adam: I mean, a friend of mine who was an astrophysicist was saying, " You know, I love getting questions from experts in other fields using the wrong words to ask me questions, which makes me think about my work in this whole other way. And so I'm learning about my discipline, talking about it to explain it to someone else.

[00:13:33] Will: Well, I mean, it's one of the things that Norm and I have talked about over the years. Is like the mere act of being able to talk to somebody, a layperson, about what you do, makes you better at understand. Like reshaping the language that you use to discuss something makes you better at understanding the thing yourself.

[00:13:46] Adam: And frankly, I think that's one of the points. I don't. I didn't hear that directly from anybody, but I think that's one of the points of of an event like this is to cross pollinate, is to get collisions, is to engender col unexpected collisions of enthusiasm, of brains, of brain power, of research in order to foment new discoveries.

[00:14:06] Will: I mean, you look at what's come out of Out of commercial space exploration exploitation, I guess, because a couple of billionaires, a few billionaires, decided that they wanted to start building rockets.

[00:14:06] Adam: Yeah,

[00:14:06] Will: and and I mean the same thing happened with VR. The same thing happened with drones. Like, t here is all these all these places that having people come from outside the core areas has done interesting things.

[00:14:26] Adam: It was totally inspiring. I came out

[00:14:26] Unknown speaker: very cool.

[00:14:26] Adam: Came out super inspired. It was fabulous.

[00:14:31] Norm: You know, speaking of astrophysicists, we would be remiss if we did not acknowledge the passing of Stephen Hawking. I don't think we talked about on

[00:14:40] Adam: such a great, such a not just a great mind in the field of astrophysics and his incredible Nobel Prize winning work, but also in the way he was with the world. You know the way he the way he impacted the world, the way he purposefully impacted the world.

[00:14:57] Will: There were two books that I read when I was in middle school that made a massive impact and shaped shaped the person I became. One of them was Hitchhiker's Guide to the Galaxy, which we've talked about here in the past. The other was A Brief History of Time, and the fact that Stephen Hawking, who was the the great mind of our time. Took time to write a book for normals to understand to explain the basics of his work,

[00:14:57] Adam: yeah.

[00:14:57] Will: So that so that like, I had a better understanding of the universe because I took the time to read that book,

[00:14:57] Adam: yeah.

[00:14:57] Will: And and I mean, yeah, we've we've lost one of the great ones.

[00:15:29] Adam: And if you want, yeah, seriously, if you haven't read A Brief History of Time, it's totally ready for you.

[00:15:33] Will: Both both of those both that book and the follow up, which I can't I can never

[00:15:36] Norm: universe in a nutshell.

[00:15:37] Will: Thanks, Norm. Yeah, are are eminently worth your time if you're curious.

[00:15:41] Adam: That's the one I grew up with.

[00:15:41] Adam: young brain.

[00:15:42] Will: Yes,

[00:15:43] Norm: well, I'm young enough that that's the one.

[00:15:43] Norm: I grew up with.

[00:15:44] Will: Yeah,

[00:15:44] Adam: will this go up on Tuesday?

[00:15:46] Norm: No, it's going to go up soon. This is that we're late on this podcast.

[00:15:49] Adam: I know we're late, so it's going to go up today.

[00:15:49] Norm: Yes,

[00:15:49] Adam: okay. So then, I also want to point out, I am wearing a March for Our Lives t shirt because I'm going to the march here in San Francisco tomorrow. I will see you there. There's marches happening all over the country. This is engendered by the amazing young citizens from Stoneman Douglas High School. I, I, I'm so inspired by these kids. They make me feel weepy all the time with their. Incredible energy to effect change.

[00:16:19] Will: I mean, it's it is. They have done something that I would have said three weeks ago was impossible. I guess six weeks ago now was impossible. In that we're actually having conversations about gun control.

[00:16:31] Adam: Real conversations.

[00:16:31] Will: People are showing up.

[00:16:32] Adam: Yeah, and they're not just you want to take all my guns. No, I don't.

[00:16:35] Will: Yeah, I mean, it's well, it's I mean, the work that they're that they're doing is empowering other people that have been doing this for a longer time too. Like if you look at the number of people showing up to Moms Demand Chapter meetings around the country, like there there's there's something happening

[00:16:35] Adam: exactly.

[00:16:35] Will: Um, and we're even starting to see legislative small at this point legislative victories, but there are legislative victories happening, which is exciting. So

[00:16:56] Adam: totally, yeah, totally. Um, so I just wanted to get that out there.

[00:16:59] Norm: Oh, absolutely. Um, one thing that also happened since we recorded last episode was the release of a film that premiered at South by Southwest, I believe, last year. Muppet Guys. Talking.

[00:16:59] Adam: Yes.

[00:16:59] Norm: Now I saw you. You you posted on Twitter that the the folks involved in it, Frank Oz who directed it, and they did some sort of a red carpet online.

[00:17:21] Adam: They did a they did their own premiere because they released the film at MuppetGuysTalking dot com, which is where you can go get it right now,

[00:17:28] Will: just on the website,

[00:17:29] Adam: on the website. And as part of the release, the night before, they had a red carpet event, and it was on Zoom. I think it was on Zoom.

[00:17:29] Norm: Yeah.

[00:17:29] Adam: Um, and I showed up, and uh, Ryan Johnson showed up. I was leaving as Alan Tudyk showed up. I don't know who came after me. Um, but you know, Frank Oz is a friend of mine, and Dave Goelz is a really good friend, and they're two of the nicest humans alive. And the film is amazing. Listening to these Muppeteers talk about, you guys haven't seen it yet.

[00:17:59] Norm: I saw it with you.

[00:17:59] Adam: Yes.

[00:17:59] Norm: Yes, and uh, I don't know them personally, but watching it made them feel like real. And gave me such a better sense of who they were as people.

[00:18:11] Adam: Totally.

[00:18:11] Will: The the the best thing that has come out of every learning I've had about the Muppets and the people who worked on all the Henson projects is that none of them were dicks to each other. Because, like, you like,

[00:18:22] Adam: well, they're they're constantly dicks to each other in this low but in a loving, sweet way.

[00:18:25] Will: Yeah, totally.

[00:18:27] Will: Yeah, but but I mean, it's it's like you you tell you can tell like we've all worked in places where the environment's a little bit toxic and like people are kind of low key shitty to each other all the time, and this is the exact opposite of that.

[00:18:38] Adam: Completely true.

[00:18:38] Will: Yeah,

[00:18:38] Adam: yeah, absolutely. You are totally right.

[00:18:41] Norm: And part of the documentary is a history of how some of the characters were created and some of the weird ways in which, like, the origins of the characters were just from their back and forth.

[00:18:51] Adam: I loved hearing I loved hearing Frank talk about the the the the the variegated history of Miss Piggy, how two different puppeteers voiced her until she found her voice. That Grover just came out fully formed, and how Frank Oz said he's like, I don't know where Grover came from. He goes, but I do. I can't tell you how I get into Grover, and it's a sound. He goes, " Hmm." He's like, and then Frank did the set, and he did. I'm doing it not well.

[00:19:18] Will: It's more of a Yoda when you do it, but it's close.

[00:19:19] Adam: And he did it several times, and you realize, right, this is he's finding this intersection to get into the character. And then they show the characters doing the stuff. They also did this lovely convention within the film, which is the pup talking about being a puppeteer is talking about physical discomfort.

[00:19:19] Unknown speaker: Yeah.

[00:19:19] Adam: Like that is clearly a key part of the job. Like, oh, you're going to be buried under Johnny Carson's couch for an hour and a half, and you got to do this. So as they were telling these stories, and they would talk about their constriction, the filmmakers would then put graphics would draw right over them, so you got to see where the puppet would be and where they would be in space.

[00:19:54] Norm: So the the format of the film is a conversation on literally on couches, the five of them, I believe, just talking for hour and a half and reminiscing. And talking, remember that time when we were filming the movie and we were on that campfire and how did that fire work—well, we were buried underneath the campfire.

[00:20:10] Adam: Well, and how about oh my god,

[00:20:12] Norm: you're talking about the Muppet movie campfire?

[00:20:14] Adam: No, and and Kermit playing the guitar on the thing.

[00:20:14] Norm: It's a banjo, sir.

[00:20:18] Adam: Jim Henson. When Kermit's playing on the log in the lake, Jim Henson is sealed into a barrel with a snorkel that is underwater. So when he came out, it took like 30 minutes for his legs to be able to hold up his weight because they've been under him for so long.

[00:20:35] Will: I like see this is the stuff like the like the the the the bicycle scene in both Muppet movie and then they did a bigger version in the Great Muppet Caper, I think. Both are are like those have been dissected. We know how they worked, right? It was amazing. It was technological marvels, all that stuff. But the fact that Jim Henson contorted himself into a 50-gallon oil drum and was buried in a swamp, like a, is incredibly dangerous, but also amazing that like they would go to that level to get the shots that they wanted.

[00:21:02] Adam: And that was a the repeated refrain of this film was what a magical. Human Henson was how well he engendered love, ingenuity, improvisation, and deep a deep commitment to great storytelling with his crew, and really let them build these characters and find them. I mean, everyone was clearly so, still so inspired by the by the collaboration with Henson.

[00:21:28] Will: And and the other thing, like I, I really encourage everybody who thinks, oh, you need a lot of money to go do something or go build something, to watch that first season of the Muppet Show. You can get the DVD for like seven dollars on Amazon, and the production, like the show, is there, right? The show is as you as you remember it from your childhood, but the production value on that first season could have been done in most midwestern basements. With

[00:21:53] Adam: except, I will tell you, it was still a super expensive show even in that first season.

[00:21:57] Will: I I know it was especially for the time.

[00:21:57] Adam: Yeah,

[00:21:57] Will: but if you look at what like the technological advances that we have now versus we had then, like the TV, like the TV monitoring rigs that they used to do the puppeteering were phenomenally expensive back then. But like the sets were tiny, like they're small sets.

[00:21:57] Adam: Really?

[00:22:25] Will: Yeah, they're like eight feet across most of them. It's it's it is, like is before they had the big, you know, the big the big intro with like the massive grid of all the Muppets in the on the green screen shoots and all that stuff composited together.

[00:22:25] Adam: Yeah,

[00:22:25] Will: I mean, I assume it's composited. Maybe maybe that's all a giant nightmare practical set.

[00:22:29] Adam: I have no idea.

[00:22:30] Will: Yeah, but but like it's it's very modest compared to what it became in the in you know seasons four five whatever the toward the end. Um, I love the Muppets.

[00:22:38] Adam: It's super inspiring. Go to Muppet Guys Talking. It's great. It's a really wonderful film. And I actually brought out a fan-made puppet of me, and he talked to the camera, and I talked to the camera for a little bit. And Frank goes, " Yeah, we'll call you.

[00:22:53] Will: Have we? Have we ever? Have you ever set up like the camera rig? You have everything here. You need to do it.

[00:22:58] Adam: Yeah, I've never tried it. I've never tried it.

[00:22:59] Will: We should set that up over there one day and just get a real high.

[00:23:02] Adam: Yeah, I guess you're right. We could do.

[00:23:04] Norm: We have enough.

[00:23:04] Will: I mean,

[00:23:05] Norm: enough here.

[00:23:06] Will: Look, it's. It's. I think it would be an instructive process.

[00:23:11] Adam: I think you're totally right, but really the trick would maybe to bring

[00:23:14] Will: you need to bring somebody in,

[00:23:15] Adam: call up somebody who knew to help coach us through this.

[00:23:18] Will: Oh, I think you need. I think you need guidance. I think we definitely need guidance.

[00:23:22] Adam: What else has been going on?

[00:23:23] Norm: Well, we released two one day builds. I don't know if we talk about want to talk about those.

[00:23:27] Adam: I love

[00:23:27] Norm: incredibly popular

[00:23:28] Adam: the one day build of my lamps.

[00:23:30] Norm: Yes, which I got this past week.

[00:23:31] Adam: a Twitter stream of of epic proportions of a million different versions of the same thing. I love and not not inspired by my build. Clearly, everyone's building this exactly.

[00:23:40] Norm: Everyone has the problem of in their workbench, in their own workspace, wherever it's at your in your shop or in your garage or at your desk, needing better lighting.

[00:23:49] Will: There's never enough light anywhere.

[00:23:50] Adam: Have you seen the lights that I built?

[00:23:50] Will: No.

[00:23:50] Adam: Oh, I'll show them to you after the podcast. I took these dimmable and color temperature adjustable flat panels that are thirty bucks on Amazon now, and I mounted one to the end of the same lock line.

[00:24:02] Will: Oh, you didn't? You showed me these last time. Yeah, yeah, yeah.

[00:24:04] Adam: And honestly, they've changed my life. I I have been working on a Jason Eaton kit. That I got recently, which we will

[00:24:13] Norm: at some point

[00:24:13] Adam: do some building. I will probably end up featuring it as a paint job,

[00:24:13] Norm: yeah,

[00:24:13] Adam: because it's super involved. But the light, those lights have been completely critical for this work.

[00:24:23] Will: One of the things I did a few years ago that was incredibly good was I got a bus USB bus powered LED light strip that's exactly the length that I could cut to be the length of underneath my monitor.

[00:24:23] Adam: Right,

[00:24:23] Will: my monitor is on an arm.

[00:24:23] Adam: Oh, nice!

[00:24:23] Will: So when my computer's on, the monitor flips on, the USB power comes on, and I have like backlighting on the monitor, which both lights up my desk and helps reduce eye strain. Super duper! Like I love lighting. I love lighting hacks.

[00:24:23] Adam: That's so good.

[00:24:23] Unknown speaker: Cool.

[00:24:50] Norm: Yeah, the only tricky thing is for filming, you just got to have those the refresh rates on your shutter speed, so it's not flickering.

[00:24:57] Adam: Oh, did they flicker in our?

[00:24:58] Norm: No, no, no. We're good. We're good.

[00:24:59] Adam: Color temp too.

[00:24:59] Adam: But so I saw the I saw the comments after I just saw when there was about six or seven of them, and the. I love the fact that everyone's immediately trading different versions and different ways to do this because it's exactly like it's a problem we all have,

[00:24:59] Norm: Yep.

[00:24:59] Adam: and it's not an expensive problem to solve.

[00:25:15] Norm: And if you want the full armature, you can get the lock line and armature wire, or you can just put it on like

[00:25:20] Adam: put someone put one on that on a microphone,

[00:25:22] Norm: a mic stand, yeah, and then put it on a ball head. And

[00:25:24] Adam: I guarantee you, in every dumpster full of stuff out of an apartment that you've ever driven past, there is one of these arms.

[00:25:30] Will: I mean, yeah, I was going to say you can get these lamps at at like before we bought the real ones for the we I had made one out of a a lamp like a lamp head that I got at Target or someplace for like fifteen dollars

[00:25:43] Adam: exactly.

[00:25:44] Norm: And then there is also the week before we published a one day build, which was a collaboration with Bill Duran making the gauntlets your Nazgul gauntlets, which are on your pool table, but then patterning those and making out of foam,

[00:25:57] Adam: which and they look so badass.

[00:25:59] Will: He's so good with foam;

[00:26:00] Adam: you can't even believe how good it looks. And then there is all these folks trying it in. Other materials like Sintra and Warbla and other things.

[00:26:09] Norm: The patterns are free. There, you can find them on on our site or on Bill's video. But you can download them, and if you have a laser cutter or you have some any type of cutter, you can just.

[00:26:16] Will: I mean, he cuts foam with an exact with a with like box cutters.

[00:26:20] Adam: He sharpens his box cutters.

[00:26:20] Norm: Yeah,

[00:26:22] Norm: he brought us a little stone.

[00:26:23] Adam: He does,

[00:26:23] Norm: yes, because they wear out foam.

[00:26:23] Unknown speaker: He does.

[00:26:23] Norm: Yeah.

[00:26:26] Will: we released an episode of the Foo Show this week.

[00:26:28] Adam: Fantastic! Congratulations.

[00:26:30] Will: The nano machines. This is the nano machines episode. We talked to Sean Douglas, who's a scientist. He's at the Department of Molecular Bio Pharmacology or something at UCSF. He's a biochemist and he builds nano machines out of DNA. We start out in a recreation of his lab and we kind of powers of ten down through his lab equipment until we are standing in between the lipid layers of an E. Coli cell, and it works without VR. So if you don't have a VR headset, you can try it out at home.

[00:26:55] Adam: Oh, that's really cool.

[00:26:57] Will: Yeah.

[00:26:57] Norm: So Eames.

[00:26:58] Will: It is. I don't. Let's not go that far. That's that's

[00:27:01] Norm: powers of ten.

[00:27:02] Will: Bit much. Yeah. I mean, I did say powers of ten, which I guess brings it on.

[00:27:02] Will: It's very good.

[00:27:04] Adam: I recently ran into someone who. Had never heard of this film, and I I realize a lot of people haven't. Norm is referring to Charles and Ray Eames' film made, I believe, in conjunction with IBM a long time ago. But that's not important. Charles and Ray Eames, two important mid-century designers, made this incredible film that zooms from the from an atom.

[00:27:28] Norm: Well, it starts off with a picnic, I believe, in in Chicago.

[00:27:28] Adam: Okay,

[00:27:28] Norm: yes, and then it zooms out first, and then goes in.

[00:27:38] Adam: Right, and each time it moves, each time its frame moves, it's by a power of ten.

[00:27:42] Norm: But it's like ten seconds for every power of ten. It's narrated perfectly.

[00:27:46] Adam: It's and it's so beautiful.

[00:27:47] Will: It's on YouTube. You can find it on YouTube.

[00:27:48] Adam: Totally find it for powers of ten right now and go watch it. It's a really important film about about context.

[00:27:55] Will: Like it's the San Francisco at the at the Cal Academy, California Academy of Sciences, the planetarium show there. The first one that they did when they re rolled the new planetarium out was a powers of ten based show, and you. It it it gives you a real sense of scale.

[00:28:11] Adam: Yeah, it's wonderful.

[00:28:12] Will: Very good.

[00:28:12] Norm: Awesome.

[00:28:13] Will: So you can find that on Steam. Anyway, the the Nano Machines episode. Just search for the Foo Show. It's out.

[00:28:18] Adam: The Foo Show.

[00:28:19] Will: The Foo Show.

[00:28:20] Adam: Do you have a theme?

[00:28:20] Will: No, we we we're not. Look, we've sold literally hundreds of copies of the Foo Show. We're not in getting theme music made.

[00:28:20] Adam: No, no,

[00:28:20] Will: not yet. No, no. We're mostly making cartoons.

[00:28:30] Adam: I've been listening to Love It or Leave It, and I love their.

[00:28:30] Adam: Little theme song.

[00:28:32] Will: If you want to jam out some ukulele Foo Show theme real quick, I'll I'll bust out the phone recorder. We'll drop it in the next one.

[00:28:37] Norm: Awesome. I think that does it for this week. Adam, you're going to be at the march in San Francisco. The march is going around all over the country.

[00:28:45] Adam: The march is going all over the country. March for Our Lives. It's tomorrow on Saturday. I will see you in San Francisco. There's also a march in Oakland. The big march is in D.C. And I will see you there.

[00:28:59] Norm: Yeah, and I'll be down in L.A. for for WonderCon in Anaheim. So if

[00:29:03] Adam: you're heading down there tonight,

[00:29:04] Norm: tomorrow morning.

[00:29:04] Adam: Wow.

[00:29:04] Norm: Fly out 6 a.m. Fly back at 8 p.m.

[00:29:09] Will: Oh, that's a fun day.

[00:29:10] Norm: I like those days. First big convention for me this year, so hopefully I'll see some some people at WonderCon.

[00:29:14] Adam: Oh yeah, I have to talk to you after this about looking for some things for me there.

[00:29:19] Norm: Oh okay,

[00:29:20] Will: all right, very mysterious.

[00:29:20] Norm: We're going to take it offline then, and we'll see you next week. Thanks for listening.

[00:29:24] Will: Bye everybody.

[00:29:25] Norm: Bye.

[00:29:25] Norm: Support for today's podcast comes from Google Cloud Platform. Looking to move to the cloud? Check out Google Cloud Platform's weekly podcast, where Google Developer Advocates answer questions, get in the weeds, and talk to experts, customers, and partners about GCP. Learn more and subscribe to the podcast at g co slash gcp podcast. We'll see you next week.
