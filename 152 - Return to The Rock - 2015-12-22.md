**Podcast:** Still Untitled: The Adam Savage Project  
**Episode:** 152 - Return to The Rock  
**Date:** 2015-12-22  
**Duration:** 31m 37s  
Episode URL: https://www.youtube.com/watch?v=SqndNdkYKtg

[00:00:00] Norm: Hey everybody! This week's episode of Still Untitled is brought to you by Automatic. Automatic is a tiny device that you plug into your car. I actually use one for my car, and it brings your car into the 21st century. Works with any car made after 1996, and installation takes literally seconds. Fits right into that onboard diagnostics port, and when you pair it with your phone, with either an iOS phone or an Android phone, it can keep tabs on your driving habits, your fuel expenses, find out what the check engine light means in plain English, automate your home using Nest or If Then Then That, and you connect Automatic to the apps you use every day, from everything from expense filling to fitness trackers and even crash detection. There's Automatic will detect a crash and even call for help for free, and a human will stay with you on the line until help arrives. So go to automatic.com and use the offer code Untitled when checking out. The normal price is a hundred. Bucks, but the holiday price is eighty dollars, and Still Untitled listeners can get it for seventy dollars sixty nine ninety nine. Buy it before Christmas and get free FedEx two day shipping, and there's a forty five day return policy. So it's pretty great. Check it out. It's automatic dot com, and use the offer code " Untitled" like this podcast. And now on with the show.

[00:01:28] Will: Welcome to Still Untitled, the Adam Savage Project. I'm Will.

[00:01:31] Adam: I'm Adam,

[00:01:31] Norm: and I'm Norm.

[00:01:32] Will: And joining us today, we have a very special guest from NASA.

[00:01:37] Norm: What? Yeah,

[00:01:41] Will: NASA. We have the CTO of NASA, Dave Miller, joining us. Thank you so much for coming by, Dave.

[00:01:45] Dave Miller: Well, thanks for having me, and I can't think of a better place to talk about space exploration than the rock,

[00:01:49] Will: a prison.

[00:01:51] Norm: The prison. Space is just full of rocks. So, Dave, you you are the chief technologist. Of NASA.

[00:01:57] Dave Miller: That’s right.

[00:01:57] Norm: The CTO. So you oversee. Can you give like a little explanation of what you do and what you oversee?

[00:02:04] Dave Miller: Well, when I first arrived, they told me it's an up and out organization, and I had no clue what that meant. But it really means that it's we focus. I I focus on long term strategy and things like technology transfer, how we interact with the with other companies and transfer the technology we do. We also track emerging space, but probably the oh we also roadmap the various technologies we're going to do. But probably the most important is advising the administrator on all things technology. There's a good sort of comparison I can make from who's who's seen the Martian.

[00:02:36] Adam: Oh yeah.

[00:02:38] Unknown speaker: Yeah.

[00:02:38] Dave Miller: And who's read the book?

[00:02:39] Adam: Yeah.

[00:02:39] Dave Miller: Some readers still. That's good. So in there, they. I think he declares himself a space pirate.

[00:02:46] Adam: Yep.

[00:02:47] Norm: Yeah.

[00:02:47] Dave Miller: Okay. So let me give. Let me use that as a way to describe who I am.

[00:02:54] Adam: Nice intro.

[00:02:55] Dave Miller: I think of myself as the pirate. As the Parrot on the pirate's shoulder. So I provide advice to the leadership and the agency, and as long as I keep good, giving good advice, I stay on that shoulder.

[00:03:07] Adam: So it's like, ah, want to use ion engines?

[00:03:09] Dave Miller: Exactly.

[00:03:09] Norm: Amazing. Wow. So you mentioned roadmaps. When we love The Martian, and we've talked about extensively on our podcast, and one of the things we looked about because it's talking about somewhere maybe thirty years, forty years into the future, and that's what you're thinking about those technologies, all all the things that can get us to Mars and beyond.

[00:03:31] Dave Miller: That's right. So right now we're building the world's biggest rocket. It's called the Space Launch System for or SLS. It's going to be bigger than the Saturn V. But once we have that in place and the Orion capsule that goes on top, we have to start building all the tools that are going to help us get out to Mars and and work productively and get back home. So we're working on a round trip in the 2030s.

[00:03:50] Adam: And in addition to that, as a technologist, you're also interfacing these technologies with other space agencies around the world that we're cooperating with. You, I mean, every time you're developing something for the future. You're looping in other partners, right?

[00:04:03] Dave Miller: Absolutely. Space exploration is really an international endeavor. If you look at all our science missions, the rovers on Mars, or Cassini out at Saturn, or or Earth science, or our human exploration space station, it's all an international endeavor. So we have to we we coordinate with the international community every day.

[00:04:20] Adam: You seem like a calm person, but this sounds like the most stressful and all encompassing job I could imagine. I mean, it's it's overwhelming. How many how the facility the facilities all over the world, the technologies it's got to be incredible an incredible amount to just put into your head.

[00:04:36] Dave Miller: Well, the trick is, and I realize realize this early on, you don't have to know it all. You just have to know who knows it.

[00:04:42] Adam: Ah, yes.

[00:04:42] Dave Miller: you got to have a good black book. That's the trick.

[00:04:45] Adam: Okay.

[00:04:46] Norm: What are those technologies that you're you're most excited about?

[00:04:49] Dave Miller: Boy,

[00:04:50] Norm: you see that as the most promising.

[00:04:51] Dave Miller: There's a whole bunch. Some of them are exciting, but they're also to try to get us through some terrifying events. So if you if anyone watched the Curiosity landing on Mars,

[00:05:01] Will: seven minutes of terror.

[00:05:03] Dave Miller: Yes, terror. Seven minutes terror. So a thing to think about is that at the surface of Mars, the thickness of the atmosphere is is about one percent Earth's, and so it's like our atmosphere at a hundred thousand feet. So it's it's really hard to get a to get a bite on that atmosphere. So we're working on a lot of different ways of doing this, like inflatable, high well, HIAD's a name for it, but inflatable deceleration devices that would work at supersonic speeds. It's just a series of events that is seven minutes of terror. And we're trying to figure out since we have to land much larger payloads on the surface, Curiosity was one ton. We have to get a lot more than that to support humans. So you really got to get a bite on that air, and we're going to have to rely a lot more on retropropulsion, basically firing engines to get that last sort of kilometer per second down to a so we can land softly.

[00:05:55] Unknown speaker: Okay. Thank you.

[00:05:55] Will: Wow. And what do you need? Do Do you know? I mean, I don't mean to put you on the spot, but what do you need to land softly? What like what kind of impact speed are we talking about? I know the Soyuz hits pretty hard compared to like our Apollo capsules and the shuttle and stuff like that.

[00:06:07] Dave Miller: Well, you want to get it under about five meters per second, and then let the shock absorbers sort of take the rest of it.

[00:06:14] Will: Wow. We've talked a lot about Mars recently on Still Untitled, and I mean that's only part of what NASA does. A large part of what we've seen recently with like New Horizons is is deep space exploration, you know, beyond the inner orbits and probes that go to Saturn, Jupiter, and and and the other outer planets. Can you tell us a little bit about what's going on there? I know there’s some challenges facing those programs.

[00:06:37] Dave Miller: Yeah, it's when you look at space science and NASA, it's one of four of our directorates. The it's broken into four pieces. there’s study of Earth, Earth science. there’s study of our sun, which drives a lot of our weather on Earth. there’s study of the rest of the solar system, and then there’s the study of everything else, which is astrophysics. And so, anyone been watching what's going on with Pluto?

[00:06:58] Unknown speaker: Yeah,

[00:06:58] Dave Miller: Pluto fans out there.

[00:06:58] Dave Miller: So six months ago, all we had in our images was a dot, and now look at all these landscapes. Anyone see anything missing on Pluto that you would have expected? Craters. There's very few craters. What's causing that? That that says to us that that's a fresh sort of renewing landscape, but it's way you know it's in the deep deep freeze of the outer solar system. We it's something we're still trying to figure out what's going on with that's renewing that surface on on rather short timescales. Another thing, Hubble took another deep field image. So if you don't know what the deep fields are, we we turned Hubble to look at some of the darkest parts in the skies. Like I think the first deep field was in the was in the Big Dipper, which is one of the darker parts of the skies, and let it just sit there and sort of collect light for a long period of time. And what we see are thousands of galaxies.

[00:07:53] Will: If you haven't seen these pictures, they're absolutely astounding. Yeah. If you if you want to feel the smallest you're ever going to feel in your life, imagine the darkest spot in the sky, and then you look at the picture of what's there, and it's it's just You know, it's it's breathtaking.

[00:08:08] Adam: The first time you guys did that, I sat down with my kids. They were probably ten or eleven at that time, and they just the sound. I mean, that when I showed it to them, the sound when they realized that looking at this dark spot was thousands of galaxies, each composed of billions of stars. They were, “Oh!” I mean, it's wonderful, wonderful how accessible that is, and how you—it's just an incredible illumination.

[00:08:35] Dave Miller: To To borrow a phrase from sci-fi, you know, it's really full of stars.

[00:08:41] Will: I mean, so so Hubble is one of the great telescopes, right? There's a there's a handful of others, and two of them, one of them has been in the news a lot lately for finding a bunch of exoplanets.

[00:08:52] Dave Miller: Yeah, the little the little the little satellite that could, the little telescope that could, Kepler. So it's been looking at. Let's see. Let me a little history going all the way back to 1995. In 1995, we knew of nine planets, and then we demoted. Poor old Pluto, but that was in 2006. But now we know of over 2,000, and there's probably three more that are on the yet to be verified list. Three thousand more on the yet to be verified list, and and Kepler was only looking at about one percent of the sky, and the so we can in that one percent we've also identified a handful, maybe eight or ten that are planets about our size in the what we call the well not the technical term the Goldilocks the Goldilocks zone,

[00:09:39] Will: which means not too hot and not too cold.

[00:09:40] Dave Miller: Yeah,

[00:09:40] Dave Miller: not too hot to boil off the water, and it's not too cold to freeze it. It's just right, liquid water on the surface, and so when you take that one percent and you see how many we found, and you extrapolate that around the sky, we estimate there's 11 billion Earth-like planets in the habitable zones in our galaxy alone. So anyone know the Frank Drake equation? So you know it's when I first learned about it, it's it's the product of a bunch of numbers that leads you down to how many intelligent Civilizations could communicate with us, and it seemed like, well, who knows any of these parameters? You know, it's an interesting equation. But, but we've been marching along and starting to answer that. And one of the key ones that we're answering now is how many, you know, Earth-like planets—not only planets around other stars, which we think is on average is at least one—but how many Earth-like planets in a habitable zone are around each each Sun-like star. And so we're really starting to knock that down. And and and the the news is good. You know, we're still in the billions of billions of possibilities to look for intelligence.

[00:10:42] Will: And the amazing thing about the way Kepler works is unlike the earlier methods, we found the first exoplanets with like gravitational wobble by, you know, seeing Jupiter-sized masses moving around.

[00:10:51] Dave Miller: Seven ways to find a planet.

[00:10:52] Will: Oh, seven now?

[00:10:53] Dave Miller: Oh, you're not going to make me lose it.

[00:10:55] Will: No, no, no, it’s okay.

[00:10:56] Will: Go to Wikipedia, guys, if you want to find it.

[00:10:58] Dave Miller: One of them is go take a Polaroid snapshot and bring it home. But okay, but there are there are a bunch of ways.

[00:11:02] Will: Yeah, I mean, you're you're able to find very small bodies.

[00:11:05] Dave Miller: Yeah, yeah.

[00:11:05] Will: In incredible, unimaginable distances.

[00:11:09] Dave Miller: So after you do that, then there's an even more unimaginable thing that. Unimaginable thing we do, and that is if the planet has an atmosphere that is transparent enough, kind of like our atmosphere, that when the planet goes in front of its star from our perspective and it dims the light that we see, that's how we know it's there. Then the light refracts through that atmosphere, and we see it. We see that there are additional molecular absorption. I don't want to get too techie here, but more

[00:11:34] Will: you can nerd out. It's fine.

[00:11:36] Dave Miller: So then you can start to say, does it have water? Does it have oxygen? Might it have oceans. Might it have things. So let me put this in context.

[00:11:42] Adam: So you're able to do spectroscopy on the refraction that’s, wow.

[00:11:45] Dave Miller: that's right

[00:11:46] Will: from from dozens or hundreds of light years away.

[00:11:49] Dave Miller: Yeah, well, the signal’s strong. It's not me, personally.

[00:11:53] Adam: You know we’re not, right?

[00:11:53] Dave Miller: I know who doesn't.

[00:11:55] Will: I should have, yeah. Look at scientists.

[00:11:57] Dave Miller: So let me give you a comparison.

[00:11:58] Unknown speaker: Space is in our name.

[00:11:59] Dave Miller: You probably saw the. You probably saw the. I assume this whole crowd went out and saw the the super moon lunar eclipse.

[00:12:06] Adam: Yeah, yeah.

[00:12:06] Dave Miller: It's not black; it's red, and that's because the sunlight, all the all the sunrises and sunsets from all over the globe. All that reddish light was being focused down on the moon. So think of that as what's happening at these stars, and that light's coming to us, and we can look at that and start to tell about characteristics.

[00:12:26] Adam: I'm just a little bit smarter now than I was 10 minutes ago.

[00:12:29] Will: Yeah, that's amazing. Okay, so we we talked a little bit about deep space with Pluto. One of the things I learned this week, we had a live show earlier this week, and I found out we don't have any deep space missions planned to speak of after. Well, we have the Mars 2020.

[00:12:46] Dave Miller: That's right.

[00:12:47] Will: And then after that,

[00:12:49] Dave Miller: and I think Juno arrives at Jupiter in about next year or so.

[00:12:49] Unknown speaker: Does anybody know? I don’t know.

[00:12:49] Dave Miller: Next summer.

[00:12:55] Will: Next summer. Okay.

[00:12:57] Dave Miller: There's the person that knows everything. Feeds me information.

[00:13:00] Will: But then after that, there's there's we don't have anything planned.

[00:13:03] Dave Miller: We have things in extended mission as well. You know, like New Horizons is now has a new target. It probably goes by some numerical name that I don't don't know, but it's it's heading out into the Kuiper Belt to see to explore new new objects. The James Webb Space Telescope, which is going to look In the infrared, six meters in diameter, are going to unfold out at Earth's Sun L2. Launches in 2018, and is going to see back to about first light, sort of ignition in the universe.

[00:13:32] Will: So hold on, it can see back to the Big Bang?

[00:13:34] Dave Miller: No, I think it sees back to around when first when first stars first ignited. I think that's what's called first light. But you need the chief scientist here to answer all those questions.

[00:13:44] Will: Well, yeah, well, we'll get that next week.

[00:13:45] Norm: You're just the chief technologist.

[00:13:47] Dave Miller: That's right.

[00:13:48] Norm: Can we talk about spinoffs? Will and I were talking about earlier, and when Will was a kid, you were reading magazine. NASA had a magazine called Spinoffs. It was

[00:13:55] Will: a little pamphlet we got.

[00:13:56] Norm: Yeah, about the technologies that trickle.

[00:13:58] Dave Miller: Every year that comes out talks about probably a thousand or so spinoff technologies into non aerospace sectors that that NASA makes every every year, and we publish these. You can download them from our website, NASA Spinoffs. The there's a lot of examples of things that we've spun off.

[00:14:16] Will: Stuff like Velcro and Tang.

[00:14:18] Dave Miller: Wrong.

[00:14:18] Will: All the normal stuff.

[00:14:20] Dave Miller: You know, I thought I thought NASA did Tang, and as a kid, I drank gallons of that stuff. And I thought that was going to qualify me to be an astronaut. I was found out. No.

[00:14:28] Will: They didn’t know Tang.

[00:14:28] Dave Miller: Wasn't good enough. No tang didn't do it. You needed more qualifications than that. But one that really caught my caught me by surprise is in the development of nutrients for astronauts. They came across a natural source for omega three fatty acid, which is a which is a key ingredient of ninety nine percent of infant formula worldwide. So I would have never figured that would have been a those. You probably all most of you have smartphones. That little camera inside the electronics for that was developed through the miniaturization work for imaging systems on on NASA satellites. Anyone have memory foam mattresses.

[00:15:09] Norm: Yeah,

[00:15:09] Unknown speaker: yeah.

[00:15:09] Dave Miller: Okay, memory foam. Those winglets on the end of airplane wings, anti skid runways.

[00:15:16] Will: Really? Hold on. What do the winglets do?

[00:15:17] Dave Miller: The winglets. It. It. It. You want me to get nerdy?

[00:15:20] Will: Yeah, get nerdy.

[00:15:21] Dave Miller: So

[00:15:22] Adam: you are in good company.

[00:15:23] Dave Miller: So high pressure under the wing, low pressure on top of the wing, and at the tip of the wing, the high pressure wants to sneak around and come up onto top side, and that. That induces a that energy into a vortex, a vorticity, and so that helps to prevent that leaking of the high pressure into low pressure.

[00:15:39] Will: So does it increase like efficiency or something?

[00:15:41] Dave Miller: Yes, increase efficiency. Have you been looking at some of the jet engines coming out, and on the back of the cowling, there's sort of this serrated edge. Looks cool, right? But it's more than that. It's it's actually for noise reduction.

[00:15:53] Will: Really?

[00:15:54] Dave Miller: Yep.

[00:15:54] Will: So this is all NASA.

[00:15:56] Dave Miller: This is all NASA.

[00:15:57] Norm: I imagine this technology is trickle down and feedback. Consumer technologies also go back.

[00:16:02] Dave Miller: Oh, that's right. Yeah, there's a lot of tablets and things on station, and there were on shuttle as well. So you know, there's there's a nice sort of feedback there. Let me give you another example: agriculture. Probably in the old days, the farmer would wake up and go milk the cows. Now they log on; they can get remote sensing data about what part of their farm, what actually down to subsections on each field, where they need more moisture, where they might need. Less fertilizer, things like that, so they can really plan out their their their efficiently how to take care of their crops. A lot of the seeding and and harvesting machines are now automatic and run by GPS and can run day and night. There's a mission called GRACE, and I think there's a GRACE 2 coming up, which are two satellites that they fly around, and when they change their distance slightly, it's in response to variations in the Earth's magnetic field, and they can measure because of that motion. This is mind-boggling because of that motion. They can measure the depth of the aquifer in the San Joaquin Valley to like a centimeter.

[00:17:06] Adam: What wow!

[00:17:07] Dave Miller: So they've been tracking the depletion, and it's you know, and it's not even by looking at the San Joaquin Valley; it's just seeing what the what the missing or the effect of you know the variation in gravity that that one centimeter of water would have made on the motion of those satellites.

[00:17:20] Will: Just the missing mass,

[00:17:21] Dave Miller: right?

[00:17:21] Adam: Wow!

[00:17:21] Will: Wow!

[00:17:24] Adam: So I'll bet there's more than one. But what are some of the most significant technological challenges NASA faces moving into the future?

[00:17:34] Dave Miller: Boy, one of them is keeping up with the pace of what's happening, you know, in the in the broader community. You know, we're going to Mars in the 2030s, probably first orbit and and then to land, and and trying to figure out how to plan that out so we can best integrate with the various what we call emerging space companies. Some of those companies are no longer emerging; they're getting they're going prime time now. And you know, what I say to my students, I'm also I'm on leave from my university. I say to my students that we're in the modern age of Howard Hughes, where people make a fortune in a non aerospace field and then spend it all on their passion for aerospace. And we we really want to fan the flames on that and see how we can best work with those companies. And

[00:18:17] Adam: and when you need a civilian to go up to space, I'm just letting you know I'm volunteering right now.

[00:18:22] Dave Miller: You want to be the first?

[00:18:23] Adam: Happy to. I'll be the fifth. I I don't care about the number.

[00:18:27] Will: Now you know, Adam, I sent a letter to Ronald Reagan when I was in fourth grade that said, " Hey, I'd like to be an astronaut. I'm cool with taking the risk. I'm eight, maybe nine. I can't remember." Um. You you said something interesting there that I missed. You said we would first go to orbit around Mars. Are we? Is the plan really to send people to orbit, take the the long trip to Mars in orbit, and then come back like we did with the the early Apollo missions?

[00:18:52] Dave Miller: Well, Apollo eight did that. Yeah. So did Apollo ten. Right. So you know it it you want to you want to take a stepping stone approach. You don't want to try to have too many miracles to happen on one particular mission.

[00:19:04] Will: It's such a long trip though.

[00:19:07] Adam: That would be yeah that would be rough.

[00:19:09] Dave Miller: Are you are you changing your place in line? Should we move you back?

[00:19:11] Will: I mean, I’ll, I’ll.

[00:19:11] Dave Miller: I think Adam's going to move up. He's going to move up one.

[00:19:14] Will: I'll take the chance on seventeen or eighteen.

[00:19:16] Adam: They get a patch. They get a patch that says I went to Mars and only circled.

[00:19:21] Will: All I got was this laugh. Yeah.

[00:19:22] Dave Miller: Well, one you know Apollo eight did that and around the moon and that was one of the most impactful missions we had because and talk about a hail mary pass if you know the history of Apollo eight the lem was late and being developed so they had they pulled it off it was supposed to be an Earth orbit test of the lunar module. And instead, and they heard that the Russians were probably going to make a try, and so they said, " Okay, we're going to reconfigure this mission on the fly." And and it was the it was the first launch of the Saturn V, and there were two test launches before it, and the one just before it had had a double main engine out, so the next flight goes to the moon with people on board. That's a real hail Mary pass.

[00:20:03] Will: It was a Jim Lovell,

[00:20:04] Dave Miller: yeah, and it took the photo of Bill Anders took the photo of Earthrise, which you know changed our whole perspective.

[00:20:14] Will: All of humanity minus two people in this picture,

[00:20:15] Dave Miller: That's right. Yeah, that's right. Minus three.

[00:20:18] Will: All three. Yeah.

[00:20:20] Dave Miller: Don't forget to ask about the super secret.

[00:20:21] Will: Oh yeah, right. So the secret happening tomorrow.

[00:20:23] Adam: Super secret thing.

[00:20:24] Norm: Segue.

[00:20:25] Adam: Segue. Super secret. I don't have a segue. Just tell me what the super secret thing is.

[00:20:28] Dave Miller: Okay, so tomorrow, you know, we we we've been thinking explore. Sorry.

[00:20:31] Will: Oh no, it's tomorrow for you guys, but it'll be in the past for the people listening at home. So congratulations.

[00:20:37] Dave Miller: So if you watch the movie Interstellar, you understand this all. So okay.

[00:20:41] Will: It’s a documentary,

[00:20:42] Norm: right? Segue.

[00:20:42] Dave Miller: Yes. Right. So, um, we've been thinking that the best place to look for life outside Earth is probably at Mars, and and that's probably still a very good shot because we're finding water and liquid water, and we're finding methane, and we found, uh, organic compounds in the fossil record at Mars. We're just getting really close, but the what the ocean worlds in our solar system, and there are a number of them, um, are showing a lot of promise. So Europa has an ocean under a frozen surface, and Enceladus, which I think is only like 500 kilometers in diameter, uh, very near to Saturn, its southern hemisphere has sort of a bulge in it that's a that's a bit of a deep ocean, liquid water, and it has geysers shooting out of it. I don't know if you've seen those photos, but the Cassini spacecraft, which has been up there for 12 years now, going around Mars, going around Saturn, has, uh, flew through it. But tomorrow we're going to fly through it at an altitude of 30 miles, right through it. And the last time we went through, it's got plenty of water. I mean, it freezes. It comes out. It's got ice crystals. But we've also measured organic compounds in it, so it's kind of like a soup. There's stuff coming out of that, uh, It's a briny ocean. There's stuff coming out of there that, uh, that you know. If only we could measure, detect life, and that's a good question. How do you do that? But it that's a very promising place. And tomorrow, think of this: we're gonna with about a one mile accuracy. We're gonna fly thirty miles above the surface of Enceladus, and that's we're flying it from a distance of eight hundred million miles away. That's called threading the needle.

[00:22:25] Adam: That is thrilling.

[00:22:26] Will: So how did how are you? Does Cassini have spectroscopy and stuff? Is that how you're measuring the compounds that are in the water, or is this too specific a question?

[00:22:35] Dave Miller: That's a good one for the chief scientist. Okay, yes, something like that. So we can measure those kind of particles, but we those kind of molecules, but we we don't have the and I don't know what they are.

[00:22:44] Will: It wasn't designed

[00:22:45] Will: to measure life.

[00:22:46] Will: Cassini twelve years ago when we launched it wasn't designed, or twenty years ago when we launched it wasn't designed to. fly through the geyser.

[00:22:51] Dave Miller: Yeah,

[00:22:51] Norm: you mentioned Europa. It makes me think of. The movie Europa Report that we were talking about earlier, where they find life, and I know you watched The Martian.

[00:22:58] Will: Spoilers, by the way.

[00:23:00] Dave Miller: That wasn't for me.

[00:23:02] Norm: Do you get to watch you know science fiction movies, and are there ones that you enjoy? And what about it from your perspective as the CTO of NASA? What are the things you look out for?

[00:23:12] Dave Miller: Well, while I was eating the classic combo box, I was watching Interstellar on my on my on my tablet. I think that's the second time I've watched it. But I like Contact. I think that's that one. That one is timeless.

[00:23:28] Will: Yes.

[00:23:28] Dave Miller: And I also, well, I love watching Discovery Channel and those. Those that's not sci-fi, but you know, I can't get can't get enough of watching the science of it because that's really what they they do is go into the science of Discovery and Science Channel and so forth. That about what's going on throughout the universe and space science and all that. But the thing is to work on the technology alone. Is insufficient. You really got to understand the science side of the side of the problem, so that you know what kind of problems you're trying to solve. And so, working collaboratively is an important thing. So, one of the things I think that we're starting to make strides in the university setting is having students that start to learn both the science and the engineering side of the coin, so that they can speak each other's language and and work better when they they get to NASA.

[00:24:22] Will: So, this is one of the things I love asking folks from NASA. But you know, we have a lot of listeners who are younger who are students, whether in high school, elementary school, or or later. If people want to come work for NASA and help us get to Mars and and beyond, what should they be studying? What should what should they be doing? What should they focus on?

[00:24:40] Dave Miller: Well, you know, it's gotten so broad. I mean, it used to be you know aeronautics and astronautics and and planetary science and astrophysics, but now it's biotechnology, it's medicine. I mean, a lot of the work on space station is contributing to our knowledge of of You know the humans and how they adapt and how that might apply to people on Earth. You know, so there's a there's a broad areas, even you know, law, international laws, treaties, policies. You know,

[00:25:10] Adam: piracy being a pirate.

[00:25:10] Dave Miller: piracy. That's right. That's right.

[00:25:14] Will: So that checks out, right? He was totally right.

[00:25:17] Dave Miller: Oh, he's totally right. Okay, just throw a rope over the other person's spaceship and you got it. It's yours. Okay. Yeah.

[00:25:23] Will: Arr. Um. I assume I assume part of your job is to find stuff that's off the shelf and technologies that off the shelf consumer stuff that you can then apply. I mean, one of the things we were surprised by when we started working with folks that are that are working on orbit on occasion is how much off the shelf computer and camera gear and you know, it's not like they're shooting with custom Hasselblads up there anymore. It's Nikon's and Canons and DSLRs that you have here. What what what's the most like what's the most unusual thing that you've that you've worked with Qualifying to go to space.

[00:25:58] Dave Miller: So I'm going to use a communication trick. I'm going to give you one answer while I try to think about that one.

[00:26:01] Will: That’s perfect.

[00:26:01] Dave Miller: The you know space station when we when space station first became was put together and permanently occupied back 15 years ago. You know to get hardware up on station, you had to go through arduous procedures, made sure everything was just right, and really made it custom. Where right now, actually in the last five years, we've been putting things that are up there much more, you know, as is from from terrestrial research laboratories, and that that's really helped a lot because researchers are used to using microscopes and whatever glove boxes and so forth in their labs on the ground. Might as well just get those up in space so that so that we can get them up quicker, get the research done, and and that the researchers are used to using that kind of equipment.

[00:26:44] Will: Is it just making sure it's qualified for like the fire safety and all that stuff?

[00:26:47] Dave Miller: Yeah, yeah. Most of it is the number one rule is don't hurt. Anything. Don't hurt the crew. Don't hurt the space station, and hopefully, don't hurt your own equipment.

[00:26:58] Will: But but like laptops and iPads and Android tablets and and the it's all just kind of up there, and people are using it now, right?

[00:27:04] Dave Miller: I'm not going to pick a particular vendor, but that's all right. Yes, yes, smartphones and tablets and laptops, and you know, it's kind of like the shuttle where technology evolved, and some of the best computing was actually in the laptops versus what was actually in the shuttle main computers in terms of power, you know, computational power. But you have to be able to adapt that. So, yeah,

[00:27:24] Will: very cool. I think I think we have time for one more. If either of you guys have something,

[00:27:28] Dave Miller: weird astronaut stories, I can tell you.

[00:27:29] Will: Oh, always good for weird astronaut stories.

[00:27:31] Adam: That is exactly what I was going to ask for.

[00:27:33] Dave Miller: Sorry, don't mean to put words in your mouth. So, two stories. The second one's better than the first. The I asked a astronaut. I came back from space station after six months on there on orbit, and and I said, " Tell me something I don't know." And he said, " Well, when we land, we want to do three things." We want to kiss our family. We want to eat our favorite meal. You know, these are the things you've missed, and we want to take a shower. And he said, " I went to take a shower, and you start at the top, right? You lather your hair with the shampoo, and you have to close your eyes." And he fell down. And he realized he had to sit on the floor in order to do that. And the reason is, you know, a lot of your balance is your inner ear, but another part of your balance balance is your visual. Well, your inner ear hasn't helped you at all for the last six months, so your brain shuts it off.

[00:28:24] Unknown speaker: Wow.

[00:28:24] Dave Miller: Says useless sensor. You know, shut it off.

[00:28:26] Unknown speaker: Wow.

[00:28:26] Dave Miller: And then you get on the ground and and you close your eyes and you just fall over. So here's the second one. So this is a shuttle story. So it's a bit of going back in history. But all the important stuff in the shuttles kept in the bay. So they want the astronauts to stay along the hinge line of the shuttle bay doors, where they can't hurt anything, and their legs are way more powerful than. What they then—they're actually more of a menace to equipment than they are useful for moving around. So what they would do is they'd have these handholds along the rails of the shuttle, along the edge, along those hinge lines, so they can move back and forth from the tail to the nose. And the shuttle would typically fly with its bay doors open towards the Earth, just for thermal reasons. So an astronaut was telling me, you know, you're walking along on those handholds with your legs away, thinking I'm doing the world's best handstand. This is fantastic going along. Then all of a sudden, your mind is missing that gravity cue about which way's up, and it flips. And then you realize I'm hanging 250 miles above Earth, which gives you pause for a moment, and then it flips again, and you go, Oh, I'm doing my handhold, and then flips again.

[00:29:35] Adam: That's why they have diapers.

[00:29:37] Dave Miller: That's right. Exactly. I'll leave it at that.

[00:29:41] Will: I think that that is as good a place as any to wrap it up. Thanks to the Bay Area Science Festival for having us out here on Nerd Nite at Alcatraz.

[00:29:49] Adam: Absolutely.

[00:29:49] Will: Thank you all of you guys for coming. The volunteers for the Bay Area Science Festival do amazing work at all of their events.

[00:29:56] Dave Miller: I will ask one more thing. Part of my job is to help people figure out how you can help us, and we made one-stop shopping called NASA Solve, where we put prizes, challenges, crowdsourcing, all kinds of things there. So if you want to help us solve our mission, please go take a look and maybe earn some cash in the meantime.

[00:30:14] Will: So NASA Solve?

[00:30:16] Dave Miller: Just NASA Solve. Yep.

[00:30:16] Will: Okay.  Fantastic.

[00:30:18] Dave Miller: No, web search.

[00:30:19] Will: Oh well, yeah, no Google. Yeah, sorry. Sorry. Your favorite internet search engine.

[00:30:26] Dave Miller: Thank you.

[00:30:26] Will: The Google.

[00:30:27] Will: The Google.

[00:30:29] Will: That'll do it for us this week. We're on every Tuesday. If you enjoy this, we're on iTunes and all the other. Sorry, the internet podcasts.

[00:30:36] Adam: Exactly.

[00:30:40] Will: And we'll be back next week with another show. See you guys next time.

[00:30:43] Dave Miller: Thank you.

[00:30:43] Will: Thank you so much, Dave. Yes.

[00:30:47] Norm: And I want to thank this week's sponsor of Still Untitled, which is Automatic. It's a device that you plug into your car, and you can get really awesome data from your car, moving your car into the twenty-first century. Automatic is a small device plugs into the onboard diagnostics port, and then pairs with your iOS or Android phone, and then you can get driving habits. You can track your fuel usage. It can help tie to other apps to plug into your expense filing or your fitness trackers. You can connect it to Nest. Super easy to use, really powerful, and it's available right now for sixty nine ninety nine for Still Untitled listeners. If you use the offer code Untitled, order today, and you get free FedEx two day shipping before Christmas. Thank you, Automatic, for supporting the podcast, and thank you guys for listening. And we'll see you next week.
