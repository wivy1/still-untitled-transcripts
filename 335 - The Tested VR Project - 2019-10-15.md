**Podcast:** Still Untitled: The Adam Savage Project  
**Episode:** 335 - The Tested VR Project  
**Date:** 2019-10-15  
**Duration:** 49m 46s  
Episode URL: https://www.youtube.com/watch?v=m7aqiOUOibI

[00:00:00] Norm: Today's episode of Still Untitled is made possible with support from Widex, a global leader in premium hearing aid technology. Widex offers sophisticated hearing technology to meet all budgets and lifestyle needs. In fact, their latest Evoke hearing aid tech connects to most modern media devices for wireless streaming of phone calls, music, and of course, podcasts like Still Untitled right into your hearing aids. You may not know it, but Adam himself uses the latest Widex model called Evoke, and he listed it as one of his top tech items of 2018. Today's hearing aids are truly at the front line of innovation. If you, a family member, or a friend are experiencing hearing loss, getting tested and treated now is the best course of action. Widex wants to give you, our listeners, the opportunity to try their hearing aids for yourselves with no obligation to purchase. Simply go to widex.com/tested. That's w-i-d-e-x.com/tested to learn where you can trial Widex hearing aids near you. Now on with the show. Welcome to Still Untitled, the Adam Savage Project. I'm Norm.

[00:01:04] Adam: I'm Adam.

[00:01:05] Joey Fameli: I'm Joey,

[00:01:06] Norm: and

[00:01:06] Eric Cheng: I'm Eric.

[00:01:07] Adam: Joey Fameli. Eric Cheng. Hello. How are you?

[00:01:10] Norm: Yeah, we have a special lineup this week. We are we have Joey in the office, and we had to have you in the office because Eric, we invited you to come in to kind of geek out about some projects that we've been working on over here at Tested, and also something that you've been working on in your in your kind of travels. So

[00:01:30] Adam: Yeah, it is really delightful to have Joey, like to see you in a second state, because we were we all just left New York together. We were all in New York like three days ago, and now you're here. So it's just it's it's delightful to see you in two different states so quickly.

[00:01:43] Joey Fameli: Yeah,

[00:01:44] Adam: yeah, exactly.

[00:01:45] Joey Fameli: Thanks for having me.

[00:01:47] Norm: People who may not know, or people actually, if you watch Tested for a long time, you've seen Eric because Eric, you you're the guy that like introduced us to. A lot of cool tech.

[00:01:59] Adam: That's that's been our friendship since since its inception. Eric brought a a a Lytro camera over to the MythBusters set. But at this point, like ten years ago or more,

[00:02:09] Eric Cheng: something like that. It's hard to remember now.

[00:02:12] Adam: And then when we were working with DJI, you were you were there, and we were doing some stuff with you there. And now now you have brought you've brought VR into the tested sphere, and that's been like it's been really exciting. The announcements that we just made, and we'll talk about it, are the are the tip of an iceberg that's been like eighteen months in development or give or take.

[00:02:32] Eric Cheng: Yeah, absolutely. It's been a thanks for having me on again.

[00:02:35] Adam: Of course,

[00:02:35] Eric Cheng: it's it's been it's always a pleasure. And I mean, I've enjoyed this because you are storytellers by nature, and the things that I'm interested in are new technologies that enable new forms of storytelling, and that's so it's always felt like a perfect match.

[00:02:52] Adam: And like. This progression from the small experiment that Norman and I did in the cave. Well, let's let's just let's talk this one through. Let's walk through this history because I think it's really interesting and and instructive. Because we didn't figure anything out, we ended up solving some problems. There's a whole bunch of other problems to still solve, right, within this frame. But like we executed this project, and and where it began was with the Oculus Go. All of us at Tested ended up grabbing them as soon as they came out, and we're playing with them and talking about the content and starting to play with our own.

[00:03:31] Norm: And this was a year. This is like last spring.

[00:03:33] Adam: It was last year.

[00:03:34] Norm: It was like a year ago. And in terms of the the VR space, because we're talking about video and VR, you know, people have had desktop headsets for a couple of years now, and there's kind of this big boom, from my perspective, of people making you know cameras to film video for viewing in headsets. Now they were all different because I know like Samsung had some off the shelf 360 cameras, and people started. Building their own GoPro rigs way back, but really around last year there was this sea change in terms of like the Go being really accessible, the image quality being good, and then also the cameras being 3D and 3D 180 being where a lot of people ended up making their hardware.

[00:04:13] Adam: Well, and we were playing around with some of the cameras and doing small things with them, and then I think just one afternoon, Norm and I shot just five minutes of me messing around on a workbench in 3D in stereo VR.

[00:04:29] Norm: Yes, this was I think the Lenovo had a small like like their Daydream you know 3D 180 camera, and I was reviewing it, and I was like okay, and I'd gone through a couple experiments of filming, of course, like the dog, right, and and things of the house, and trying to get sports, and like some things were cool, and some things were like, and from our video production perspective, like. This is not like how we would shoot any other video,

[00:04:58] Adam: right? And you can't tell until you shoot it and look at it. There's like literally no way to kind of even think through it because it's so different in terms of how you interface and and your your your mental emotional interface with the with with the material that you've shot.

[00:05:11] Norm: And so I went to the cave, and you were working on a project, and I brought the camera over. I said, " Okay, this is kind of cool. I want to see if I can just run it while you were futzing with something." And we put on a tripod and ran it, and put the headset on and watched it. And it was really compelling.

[00:05:26] Adam: both of us were like, " Holy shit! Holy cow! This it just there's an intimacy to it." And all of us have watched tons of videos of craftspeople in our fields doing things that we want to do. And you know, ninety percent of those videos are terribly edited with bad sound, and still we're like obsessed with watching other people do this stuff. And there was a way in which that stereo VR made it sing. That felt so intimate, and then I guess like a couple of days later, you were like Eric Cheng’s already made a video on this, and you had shot that wonderful crafts person up in Portland.

[00:06:00] Eric Cheng: Yeah, it was it was Bob Kramer up in Washington, our mutual friend, an amazing kitchen knife maker.

[00:06:05] Adam: Incredible.

[00:06:05] Eric Cheng: And we spent a whole day there shooting the entire process of making a kitchen knife with the Z Cam K1 Pro. So this is sort of the next gen, bigger sensor cameras, and it was the same sort of thing. You know, we shot it essentially blind. You know, onset monitoring at that point was virtually impossible, and so it was really an experiment. Sounds like it was similar to what what you had done. We shot it, and then it took a long time to be able to view the footage and to you know craft the the story, which ended up being twenty six minutes long. But what I remember the most about that is the first time a lot of my colleagues even saw this footage, and of course the people we you know on the public saw it. I mean, I watched people get into headset and. Almost literally not move for 26 minutes, and when they came out, they didn't talk about the format or the novelty of being able to look around. They talked about the story and feeling like they had been in his studio with him,

[00:07:00] Adam: Right.

[00:07:01] Eric Cheng: and that was the you know one of these moments where I thought, wow, this is really like teleportation.

[00:07:05] Adam: And there was an aspect to that video when I watched it. So I'll be honest: the first time I got to go, I spent two days looking up every piece of content there was for it, and I I couldn't believe how bad 90% of it was. And then, I mean, and then I one of the things I realized is when people try and make narratives, they try and they've been trying thus far to make them using film techniques, which require a certain pace of cutting, and it wasn't working. I never felt like I was getting into a space. And the thing about your video is that you were holding your shots for long enough for me to feel like I was in a place and forget that I was watching a video because the cuts are more. It weirdly, the cuts feel. How do I say this? In the beginning of film. Like back at the turn of the twentieth century, the nineteenth to the twentieth century, there was a theory that like to cut to something too different would be jarring to people, and so they didn't do it, and they needed title cards between and other techniques. And weirdly, cutting too quickly in VR is jarring. It feels as jarring as they were surmising it was in in film. All this is by way of saying there are brand new rules to this format in way and and it requires a level of exploration, and that level of exploration is something that Joey, you and and Eric dove deep into after we'd filmed these videos. But we're getting ahead of ourselves.

[00:08:27] Joey Fameli: I was going to say, just to just to go off that? I think the way I was trying to think about it when I was editing this, you know, because I instinctively want to cut, right? I want to move it, but the way I had to really rewire my brain was to think, okay, the the viewer is actually doing the editing by the focus of what they're looking at, right? And that kind of calmed me down as like let the let you know let the scene breathe so that they can look at these little things

[00:08:49] Adam: Yeah.

[00:08:49] Joey Fameli: in the space, and that is kind of Their way of, you know, focusing or editing. That's

[00:08:55] Adam: but it's at a much slower periodicity than a normal,

[00:08:58] Joey Fameli: right? Yeah,

[00:08:59] Adam: than a normal video.

[00:08:59] Joey Fameli: But I kind of had to fight myself almost.

[00:09:01] Adam: Well, at the same time, I also think like one of the things I love about your editing is how much silence that our tested videos have, and that's from you of like I think getting into the builds and knowing, seeing the shop practice, and kind of being more honest about how that story works because there's lots of periods of silence and just concentration

[00:09:21] Joey Fameli: and letting like sound, ambient sound, kind of create the the mood and the the piece itself.

[00:09:25] Adam: Exactly. So to get to just to go back to where the story was, after we cut our little thing and started talking to you, we all shot that first video in this in the Oculus series here in the cave as a kind of a test, just to like let's try this all out. And you guys were placing camera. I mean, there was the main camera, the main like stereo camera, like that one there. That was We knew that was going to be the middle of the whole thing, but then you you had all these other shots, and there's this way of like, I hope this will work later. I hope this is useful to me at some point in the future. And you place cameras all over the place. So let let's talk about that process of of choosing choosing where to put those cameras before you'd even built an editing pipeline.

[00:10:09] Joey Fameli: Right. So I mean, well, just to put this in context, if you haven't seen, we did an eight part series, featuring eight different makers, where we um, yeah just traveled around and went into their workshops and had them build stuff. And Norman and I—

[00:10:22] Adam: and the experience is that when you put on the goggles, you're sitting at the other side of the workbench from these makers, and you're in their shops and in their space and watching them do their. thing.

[00:10:29] Norm: Which goes back to the very first test, which was literally across the workbench. The way you have your the little leather working demo you did, you know, we quickly realize the camera is, the avatar for the viewer. So where do we want the viewer to be when they're if they're a new visitor that's welcome into a space? Well, they want to be the best place. The Best seat in the house is going to be across the workbench,

[00:10:52] Joey Fameli: right? And then just going from there, we would just think about what what are the areas that they can't get to, right? Like sitting that close to a welding, you know, a welding bench, or like being that close to a bandsaw. Like, will that be disorienting, or will that be someplace that the viewer can kind of, you know, almost be become a fly on the wall that they couldn't do as a as a human? Um,

[00:11:13] Norm: Because we could do that in traditional flat screen video. Like, you can do very artsy shots, like right up to a [bandsaw?]

[00:11:18] Joey Fameli: right, yeah. You're kind of determining the point of view of the person,

[00:11:22] Norm: and you don't think about you don't you don't have to worry about comfort.

[00:11:24] Joey Fameli: No, yeah,

[00:11:25] Norm: but we did that. We we also put cameras on the other side of a lathe, right, where the the person could never stand because it was it's floating above the lathe. But I think viewing it, your brain acclimates very well.

[00:11:38] Adam: I agree. It it totally does. Um, the the resolution of the current Iteration of VR does not allow for hyper; it's just not good enough for like super fine. Like I couldn't do a kit bashing video right now. It just it would be very hard for you to see the tips of my fingers and the little things I'm working on, and that required us for our builds to shoot some close-ups, and that engendered the question: How do you shoot a close-up in VR? What just do you blink and suddenly go closer? What is what is the language? So you put cameras around, and you also had a handheld to do punch-ins, knowing that maybe we could somehow use those. And I know that you ended up with the solution that you ended up with in the videos, which is just sort of fly in a card. But I'd love you guys to speak to the kind of the development of how the close-up works because I know it went through a bunch of different iterations.

[00:12:35] Joey Fameli: Yeah, we did. You have it on the Bob Kramer video at all? So I think

[00:12:39] Eric Cheng: no, no. I mean, I had done a bunch of experiments, precisely to address the problem that Adam talked about, which is I mean, it's both about overall resolution, which we can talk about later, because a lot went into making. You know the the current iteration of how to playback video, such high high resolution, high quality. But it's also that the cameras can only be so close. I keep pointing here because there is actually a camera right there shooting in one hundred and eighty. But they can only be so close due to things like you know. You talk about this a lot in projections, but convergence, you know, like convergence accommodation conflict, things like that. And so there are still some technical pieces that the whole industry is is interested in solving, and we're seeing little pieces of that develop. But the storytelling techniques that are used in cinematography, which are you know that you have a director with a a goal of telling a story, and they have to do this elaborate. I mean, I heard I I think the normal the average cut in a feature length movie is is only a few seconds these days, something like that.

[00:13:36] Joey Fameli: Yeah, yeah.

[00:13:36] Eric Cheng: And that is crazy. You know, the amount of work it takes to craft a story with three second cuts over ninety minutes or two hours is staggering. And so I think one of the things that That is so appealing to this format for me is that the story sort of is about the place and feeling like you're in that location without having that cinematographer working.

[00:13:57] Adam: Well, you so you describe to me the most important aspect of this, which is the videos I find the stuff in VR I find most compelling is the stuff that allows me to look around, not the stuff that is attempting to tell me where where to go and where to look. That's interesting, and that's exactly what that is. Is it feels so much more autonomous to be the one I'm guiding my focus. The camera isn't dragging me there, and so there was a way in which when you so you got you eventually came up with a the close up on a on a fly in flag at a to a certain extent.

[00:14:30] Joey Fameli: Yeah, essentially we did a picture you know picture in picture and just put this object into I guess the 3D space and then

[00:14:39] Norm: which is not trivial.

[00:14:40] Adam: And the picture in picture was 2D.

[00:14:42] Norm: Yes,

[00:14:42] Joey Fameli: right. Yeah,

[00:14:43] Norm: and we we talked about like could the picture in picture Be 3D? Could it be a diorama inside already a stereo space? And technically, yes, but that would be very complicated to do. depending on where you place that picture,

[00:14:59] Eric Cheng: and also getting the stereo source at a different scale,

[00:15:02] Norm: right? Yes, yes, yeah. The problem of macro because that's one of the first things. Like, how could we could we capture something small? And you would think, can you just move a camera lower, right? And moving a camera lower and closer doesn't solve the problem because one, there's focal lengths. Like these cameras have a sweet spot for distance that an object is, and the height really mattered. Like we shot everything at like close to eye level.

[00:15:30] Adam: In fact, at the release party, a short person came up to me and said, " I really appreciate your choice of where the height was placed." In general, in VR, they found the height was often disconcerting to them, and they felt like we hit this perfect sweet spot. I really appreciated that.

[00:15:47] Eric Cheng: Yeah, and that that height sweet spot is not obvious.

[00:15:50] Adam: Right,

[00:15:50] Eric Cheng: everything is shot essentially at chin level on a medium height person, and I think there are some theories that I've heard talking to friends that in that tall people bend down to look at stuff, and short people can they don't stand on stools to look at stuff. You know, it's very rare, so it's more likely that a tall person is is used to a this

[00:16:08] Adam: adjusting their height down,

[00:16:10] Norm: which I don't know if that's true, but it's. No lateral movement either. But it's kind of just tilting down. But as long as the subject, you know, and as we're traveling around, like the one thing we told all the makers to do is please talk to the camera as if that's the person you're talking to. That helped really connect them, the viewer, to the the content.

[00:16:29] Adam: So this I'm going to drift quite far afield and get abstract here for a second, but I think it's important for young makers or filmmakers or listeners to the podcast who listen to this, who've seen our content. It's easy to look at the output of something that's polished and professional, which I feel like our videos really are, and think, oh well, that's how someone does that sort of thing. And the answer is, we figured it out on the fly. And truth be told, while there are brilliant people all around the world playing in this exact space and trying all sorts of different amazing things, all of us collectively are out at this precipice. And one of the things I said at the Oculus party was, I remember in film school we studied the Potemkin steps from Sergei Eisenstein's Battleship Potemkin, and we study that because it's the first time in film history, arguably, but that a filmmaker did a jump cut to explain action. You cut from these stairs to a woman with a bullet hole in her glasses, and you knew you saw a soldier shoot. You saw the bullet hole, and you knew she'd been shot. And that was the first time anyone figured that out in film that you could juxtapose these things, and your brain would fill in the rest. And here we are making these films, and you guys are doing the same kind of thing, like the card flying in. That may be something we're doing in twenty years. That it's just standard, or maybe there's a much better solution. This is this field we're in. So you know, if you're a maker and you're wondering what you can contribute to the world with your making, and you're thinking, " Well, everything's already been discovered, and everyone's really smart," it's like there's so many places to jump in and sort of like figure something out and tell a story in a different way that may radically give people a brand new way of looking at stuff.

[00:18:12] Eric Cheng: I like to think of the the path to the question or the answer. I don't know. You know, how long is that path in a given field? And the shorter it is, usually the more interested I am. I am in going to that space.

[00:18:22] Adam: Right.

[00:18:22] Eric Cheng: You know,

[00:18:23] Adam: right. Of like, nobody knows what's going on over here. Let's let's keep on playing around. I was to sing our to toot our horn, and we didn't do anything that we were like there was no consciousness behind it. But one of the things I loved most in VR was the MythBusters VR. On our last run on MythBusters, when I drove through a mile and a half of our props, we put the the 360 camera on the hood of my car. And so you were just on the hood of a car racing down Alameda Runway at forty miles an hour, and there was nothing else going on except you were getting that view, and it was so compelling to get that view. I was like, I just want to drive through Stuttgart, or Tokyo, or or Machu Picchu. I just want to be the fly on the wall, flying around.

[00:19:05] Norm: It was like those series of videos where you're in the front of a train.

[00:19:08] Adam: Oh, are there?

[00:19:08] Norm: Oh, I mean, in cut screen.

[00:19:10] Adam: Oh, yes, yes, yes.

[00:19:11] Norm: Love watching those hyperlapses on trains.

[00:19:14] Adam: That wonderful, wonderful 1905 drive down Market Street.

[00:19:18] Norm: Yeah,

[00:19:19] Adam: from the Mission all the way to the Embarcadero, and then somebody replicated that last year. But like I've watched that three or four times. That long, you know, just I'm the fly going through. Anyway, I'm getting ahead.

[00:19:31] Norm: Eric, I mean, in addition to the the Bob Kramer piece, you've done a lot of traveling, and I've seen like you post pictures of the places. Like, how do you pick those places, and what's been the best response from the people you're filming, and also like from your own Viewing of it,

[00:19:46] Eric Cheng: I think there. I mean, my my goals. I usually have two goals. One is workflow development, you know. So I'm out shooting because there's no there's no way to get that experience without actually shooting and going through the whole workflow over and over again. Especially in a field that is changing so quickly, you know, like like this one, where the cameras change, the tool set changes, the you know, encodings change. You know, every at every level of detail, things are changing sort of constantly. But the second thing is, I have recorded quite a bit of family life with these cameras, and I have not found any form of that sort of historical capture. I'm like a a pack rat with with imagery, you know. So I shoot all this stuff on a daily basis and and organize it all. It's actually it's it's it's kind of painful to organize this kind of data daily. You know, I capture some data and I dream about like just deleting everything and uploading it to the cloud.

[00:20:36] Norm: Give us a sense of the scale of data.

[00:20:36] Eric Cheng: Yeah, well, I have I probably have forty or fifty terabytes of data at home that I have to constantly back up, you know, and have to. That's a whole other project.

[00:20:47] Adam: Just to be really clear, like the entirety of Toy Story One was like six terabytes.

[00:20:53] Eric Cheng: Okay, well, so I'm on Toy Story, you know, nine.

[00:20:58] Adam: Oh, and by the way, at that point in time, I think the entire internet was only like twenty terabytes. Yeah. Back in the back in the nineties.

[00:21:07] Eric Cheng: So it's it's another passionate area of mine, which is storage and backup. But the the sort of family capture stuff. So I did interviews of my wife's parents and you know my my kids. Like my wife, you know, the day before we went to the hospital to give birth, all in this format. And when I go back and look at those videos, it really does feel like I'm back in that moment. And so I'm not sure what it's like for other people to go. And I think anyone who cares about somebody who sees sees that person in this format will feel like they're there in front of them. And we see it in the tested piece. We see it in other pieces where someone's talking to camera. But there's something at a different level when it's when I when there's something when there's like. A precious feeling to that capture, you know. And so I'm thinking of this as as archiving for the future. You know, what what are the moments that I can capture for my kids? And so that is a lot of what drives me to push immersion and and intimacy in the format as much as possible.

[00:21:59] Norm: And even if it's like the only people who that will connect to or relate to the most is family, it it for them it's it matters that much. I mean, even for the makers, some of the people who now because we shot this over the past year and now they've seen it, some some of them have moved spaces or have changed their spaces drastically. For them, it is a time capsule

[00:22:17] Adam: Right, right, right.

[00:22:17] Norm: because they get to experience their old space, which then they may have photos of, but never have documented in this way.

[00:22:23] Adam: And the tiniest way, it's that for me too, because depending on the detritus that's sitting on the shelves behind me, I can tell almost to the week of when what project I was working on.

[00:22:31] Eric Cheng: Actually, I don't. I remember I came in here with a high resolution 360 pano rig, and it was just sort of a random test one day. And you said, " Yeah, come over and shoot it." And I shot all these pictures, which are like hundreds of. Megapixels, maybe even a gigapixel. And I remember one day you used it to zoom in on on text on one of those drawers to tell somebody where to find something.

[00:22:52] Adam: Did you really?

[00:22:52] Eric Cheng: You were traveling. Yeah, I remember. They're like it's in. I said like the sixth drawer down in that cabinet right there because you could zoom in and see the text. So that kind of captures is is a moment. Just it's a time capsule.

[00:23:03] Adam: Have you ever seen Wim Wenders’ film " Until the End of the World"?

[00:23:07] Eric Cheng: I have not.

[00:23:08] Adam: Have we talked about this?

[00:23:09] Eric Cheng: I don’t think so.

[00:23:09] Adam: So this is a super important movie and really is worth watching. I believe it came out in 1990. Hold on, just a second. Until the end of the world. Until the end of the world, 1991. So it comes out in 1991 and presages laptops, tablets, digital advertising, GPS. It it the main character is driving and she's in traffic and. She pulls off the road, and her car says, " You are leaving the marked route, Claire. I cannot guide you any more, Claire." Right? And it's like that's ten years before we were getting that stuff. But what the film is ultimately about is that it's about a scientist, Max von Sydow, who invents a machine that can record your dreams, and it can record your experiences. So you put it on, and what you see is what the person later on watching the recording sees in every way. Like you are in the space. It does it with brain waves rather than visual imagery directly. And William Hurt in the film is you. He's traveling around the world, gathering experiences, interviewing family members, and getting as much data as he can into this format before bringing it back to his dad in the in the outback of Australia, where he's got this protected compound. And ultimately, what happens in that is that they discover that if you wear the rig while you are sleeping, you can record your dreams. And these people end up in this compound in the outback of Australia, addicted to watching their dreams.

[00:24:47] Joey Fameli: Interesting.

[00:24:47] Adam: It's riveting. It's a phenomenal movie. It's one of my favorites. Sam Neill is in it. Solveig Dommartin and Jeanne Moreau plays William Hurt's mom. Max von Sydow plays the scientist. It's a super important science fiction movie, and you will find so much to connect with in this film.

[00:25:09] Eric Cheng: Is that good or bad?

[00:25:10] Adam: No, it's great. It's great because that's what this kind of thing takes. It takes a little bit of obsession, and look, it's really fun to step out on the precipice of a technology and a mode of communicating, and find ways in which it can resonate even deeper because we're looking for that experience for ourselves, and then ancillaryly, we're looking to give that experience to others.

[00:25:34] Eric Cheng: So this precipice that you talk about, I think it's really interesting because I think this particular precipice has been a journey of hundreds of years, or maybe a hundred something years. But panorama, you know, I was actually in your bathroom, and you know, you have a. A picture. You have a bunch of pictures printed out. You know, that's a panorama in there of of a of a workbench, and that kind of work has happened since the beginning of film. You know, people have been doing panoramic photography and looking for ways to experience it. Other than a giant print, there was no way to look at it in the past.

[00:26:06] Adam: In fact, perhaps the inventor of cinema, Edward Muybridge, shot some incredible panoramas from the top of Nob Hill here in San Francisco in like eighteen seventy five, eighteen eighty. It's like, and they would display them in galleries,

[00:26:23] Eric Cheng: right,

[00:26:23] Adam: all around the room. So you'd stand in this gallery and be looking at a vista of San Francisco.

[00:26:31] Norm: Field of view.

[00:26:32] Joey Fameli: Yeah,

[00:26:33] Eric Cheng: field of view, and finally a way to display things that breaks borders. You know, that's the rectilinear framing that that we've been working with for so long. I mean, I think storytelling has almost visual storytelling has almost always been framed. You know, in theater, it's framed by

[00:26:48] Adam: the proscenium.

[00:26:48] Eric Cheng: Yeah, proscenium. So that concept is really well understood, and I think. Part of this, the you know, this development of storytelling in a new medium is about understanding what happens when you break through that frame framing.

[00:27:01] Joey Fameli: And I was going to ask, how has your experience been with? Because this is something that I find I cannot explain to people. I have to put this headset on them. Whereas, like, oh, you know, media throughout the years, you can kind of show people pretty easily. This you and explain it, but this you really have to put this headset onto people. How's your experience been with this? Have you had luck kind of, I don't know, wrapping people's minds around it in easier way than just showing it to them?

[00:27:28] Eric Cheng: I think I think there's no replacement for showing to someone in headset. But I think maybe the closest thing would be a three D Omnimax film, you know, dome theater that's three D. Some people have been in those. It tends to be documentaries at you know science museums and stuff like that. But three D films and IMAX are probably similar.

[00:27:46] Adam: At the same time, I think that that I I think that it's easy to think of it like that, but There's a way in which when people say, " Well, if I put on VR, how do I know where to look?" Right, and the answer is, " Well, when you walk around the world, how do you how do you know where to look? You look at the things that are important." So there are ways in which, like when you look at those beautiful videos on magic and neuroscience, and you look at magicians like Penn and Teller who've worked deeply with neuroscientists to help understand this, and pickpockets like Apollo Robbins, attention management specialists, and none of them think that it's a mystery about where we're going to look in VR. I don't think I haven't spoken to them directly, but like these are performers, and on a stage as a performer, I know where the audience is going to look most of the time. I'm I'm guiding their focus. I'm telling a story, and there's a way in which I think a lot of VR content that I've seen does not trust the viewer to actually look where the action is. And there's always like blinking arrows telling me where to look. And like I play a puzzle game. I I've played with a few puzzle games, and what I kept on experiencing with them was I'd be like looking around this room, and somebody would go. Look in the red drawer, and I'd be like, " Fuck everybody! I don't want to do. Don't tell me what to do."

[00:29:02] Norm: I mean, sorry, I made the yell.

[00:29:04] Eric Cheng: I think there is there is also a responsibility on the creative side. You know, the the creators cannot do things that give people an overwhelming sense of FOMO. You know, when three hundred and sixty first came out, there was a lot, or right now, there is still a lot of experimentation. But one of the most natural things for a creator to do is put the camera in the middle. You know, we we could put a three hundred and sixty camera in the middle of here, and the overwhelming sensation, I think, aside from feeling like your head is in the middle of a table, which is maybe not ideal, is to make people look around constantly for something,

[00:29:33] Adam: right?

[00:29:33] Eric Cheng: And that can be very taxing on somebody.

[00:29:36] Norm: Yeah, we see that a lot. Like the have a conversation. There'd be a lot of these like scripted scenes, like you are in the middle of interrogation. You are literally in the middle of, yeah, you know, a heist scene. Yeah, theoretically, it sounds cool, but you are asking a lot.

[00:29:50] Eric Cheng: I mean, it could be used to to make that feeling for you know to give this person a feeling of. Of insecurity, I think it could be used. But imagine, like, if you had shot this, shot tested VR in three sixty, what would have changed?

[00:30:03] Joey Fameli: Well, I mean,

[00:30:04] Adam: from a pipeline perspective,

[00:30:06] Unknown speaker: yeah, from a creative, from a creators'

[00:30:08] Unknown speaker (Adam or Norm): perspective, I'm not sure how much would be added.

[00:30:11] Joey Fameli: There would have been a lot of wall.

[00:30:13] Adam: Yeah, and there's a lot of people. I read the comments on the on the Oculus app, and there were just a few negative comments that didn't like the fact that they couldn't look behind them. But to be perfectly honest, within the storytelling that we're doing, there's no reason to need to look behind them. Which is why, as soon as you said, " Now I'm mostly concentrating on 180 right now," Norm and I were both like, " Oh yeah, that totally checks out." Like for the most part, I'm sitting on a couch, and even though I have access to some large spaces, it's very specific content that I'd want to go in and have complete like three sixty movement around me. And not to say that there's not a place for both, but I really get how much 180 Can help refine the focus for specific stories.

[00:30:55] Joey Fameli: Yeah, I mean, like I think, like you were saying, if you want to create, like I can see three hundred and sixty being like a horror narrative, right? Where you are trying to create a certain sense of, you know, unknowing or or FOMO. But for our intents and purposes, there was no. It just didn't. It didn't make sense.

[00:31:08] Norm: The spaces would have the spaces we would have picked would have been completely different. We would have looked to spaces where people have tools or work in a space where it is three hundred and sixty, and and most of the people don't work that way. You know, they need doors, and you know, most shops have

[00:31:26] Adam: right. I am curious about the actual pipeline. So you you get back to your your your edit suite, and you've got the the stereo VR, and then you've got all these other camera coverage. How do you start? How did you start to work out the pipeline of how to parse this stuff just for yourself before cutting it together?

[00:31:44] Joey Fameli: It was a it was a process. I mean, eight episodes. I probably didn't feel super confident in. A good, you know, being on my own and a good having a good pipeline until like episode four.

[00:31:54] Adam: Wow!

[00:31:54] Joey Fameli: I mean, because there was all a lot of new data. You having to stitch things together. You having to really media manage everything, and then on top of that, you're working with software that's you know relatively new or

[00:32:05] Adam: right. Editing itself requires a massive sort of dump into your head and wrapping your head around all this material, and then you're doing that at the same time as you're using technology that's brand new and some of it's buggy and not necessarily perfect.

[00:32:16] Joey Fameli: Right. Yeah. I mean, just getting getting to the edit suite, I think, was was the challenge. But once I got into Premiere, like it's you know, it's it was it was familiar enough that I can cut. But then, um, and then just going through, like, you really have to you have to watch it in headset, right? So it was it wasn't where I can edit, look at a little screen, like, nope, that video is great, export. It was I'd edit a video and be like, all right, let's let's try this out.

[00:32:41] Adam: So did you have to keep uploading sample videos up to the headset to watch them, or does can it be part of the pipeline?

[00:32:47] Joey Fameli: I had a I had a headset that was doing like a live feed.

[00:32:50] Adam: Oh, good, good, good.

[00:32:51] Joey Fameli: So basically, I would go through and I'd cut it. Then I'd watch it in the live feed, and then I'd do like a color pass, and then try it on a few different headsets just to make sure you know things are being displayed properly.

[00:33:01] Adam: Oh, nice! Is there a real difference between how the headsets each do that?

[00:33:05] Joey Fameli: Yeah, yeah. I mean,

[00:33:05] Adam: I didn't realize that.

[00:33:06] Joey Fameli: And then like your computer monitor, like

[00:33:08] Adam: it's yeah, yeah. Of course,

[00:33:09] Joey Fameli: I've always relied on scopes to kind of tell me where whites were, where where the lows were, and that helped. But like there was also little slight differences with the headsets and stuff. So just making sure that all was consistent across what to go in the Quest, and then and then there's a whole audio discussion that we can.

[00:33:27] Adam: Oh my God! Right, audio is a whole separate thing because we're using 3D audio,

[00:33:31] Joey Fameli: and I'm not an audio guy. So

[00:33:33] Eric Cheng: neither am I. But I think one thing Joey said is is really important. The the previewing in headset is absolutely mandatory. You really just don't know what the piece is going to look like until it's viewed in headset. And I have seen creators create a piece of of media and share it without ever having seen it in headset, and it's It just means that it's not targeting; it's not being made targeting headsets. You know, it's made for other forms of 360 consumption. So, my feeling is that the editing process needs to be really tightly coupled with with headset viewing.

[00:34:05] Adam: And for instance, I was looking at. I started looking at what what was available on YouTube on the Oculus browser and the YouTube VR content, and one of the things I found was, you know, when you're looking at the YouTube content not in 360 VR but in the 2D where it's big and wide, there's an aspect to it where the contrast ratio and the the super wide angle looks so compelling and kind of really beautiful. And then when you on a lot of them you click to the full 3D 360 and it it craps the bed, right? You're way closer into it, and the resolution drops significantly, and it doesn't have that same compelling feeling. And again, it's it's it's dependent on going into the environment rather than looking at it from outside.

[00:34:47] Joey Fameli: There was during production, going back to the picture-in-picture when we were shooting the close-ups with the. You know, sixty-nine camera, and then looking at the feed of the of the of the VR camera on the computer screen, iPad, I'd be like, " All right, let me just punch in on this picture in picture camera, get close, and then you put the headset on. I'm like, I see, I'm like, I'm closer in the VR set that I am in that camera,

[00:35:08] Adam: Right.

[00:35:08] Joey Fameli: just because of the way, you know, you're the way you're looking at that on a two D surface. So we were overcompensating by like zooming in on the sixty-nine camera way more than we should have because I knew at that point going into editing, like this is not gonna.

[00:35:21] Norm: And so much of this almost analogous to the very early days of film filmmaking because we were essentially like testing daily shots.

[00:35:28] Adam: Right.

[00:35:28] Norm: Like we were doing a couple on the first few of these videos and trips, we'd shoot a bunch different distances, and then there's a whole process to ingest that, to upload that to a headset, and then in the hotel room, literally going through, oh, I like version three the best. So next day, that's the those are distances that we measure out and

[00:35:46] Norm: and and film for, yeah.

[00:35:48] Adam: So, just casting our minds forward, if we do more of these, like, are there some specific things you're dying to try out, or that you feel like didn't quite nail that, or excited about adding some aspect?

[00:36:03] Norm: Well, the techs already changed, right?

[00:36:04] Adam: Is it really?

[00:36:05] Norm: Yeah. There's a whole there's like second generation of the camera that that we use that now does what sixty fps.

[00:36:12] Eric Cheng: Sixty, yeah,

[00:36:12] Adam: amazing.

[00:36:13] Joey Fameli: Where's where's where's motion land now? Where are we at with there? Is people are people trying that?

[00:36:17] Adam: What do you mean?

[00:36:18] Norm: Well, we, we.

[00:36:19] Adam: Movement of the camera.

[00:36:19] Joey Fameli: Yeah. So we all had everything locked off.

[00:36:21] Adam: Right.

[00:36:21] Joey Fameli: We talked briefly at the um the launch event about you know how to deal with motion, how to move the camera on some kind of motion control system, or or what um and if that would add anything of importance.

[00:36:32] Adam: Here's a question. Um, sometimes in VR, when I'm looking at the a static shot like like our videos, and I do this, I move my head in. Obviously, it doesn't move with me, and there are times when I've been like. Shit! Like I want that. Is there a possibility that a current or future camera has a high enough resolution to do a false zoom for me within just the space of my head, so that as I move my head within this eighteen-inch circle, I do get a kind of a false actual VR space?

[00:37:03] Eric Cheng: Yeah, I have seen some creators do that on the on the playback side. You know, where they're faking six-DOF movement. You know, within some very small head volume, you can move your head around, and forward and backward is usually done by zooming because there's no real 3D information. You know, it's just stereoscopic. Um,

[00:37:19] Adam: But within a small frame, that might be enough? How, what's your experience of that?

[00:37:22] Eric Cheng: Yeah, it's it's interesting. I've I've seen it done pretty effectively. I think it also depends how close objects are. If objects are very close, and you would expect motion parallax, and you don't get it,

[00:37:32] Adam: right,

[00:37:32] Eric Cheng: it can feel a little bit off. Um, uh, yeah, and but I think this whole space moving cameras, it's it's uh, there's a lot of debate in the industry about it. Because there hasn't been enough done, you know. Every everybody who's done moving camera shots understands how they feel about the stuff that they've shot, but they don't have a greater sense of what it means for storytelling in the medium itself, not yet.

[00:37:54] Adam: There's an so right now. I'd like to just ask the audience something, which is if you guys have specific questions about this process, these technologies, I'd love you guys to put them in the comments, and then we can come back in a month or two and answer some of these questions because we still have our own questions about this. Again, this is sort of brand new territory, and I like the idea of starting a dialogue because, as far as I'm concerned, I want to make a ton more of these.

[00:38:22] Norm: And we hear a lot from people who watched who like not only people who've watched that are makers that would love to have their own stuff filmed, and that's really kind of opened the floodgates in terms of the creative side and and coming up with ideas, but also people who want to experiment filming, and it's not difficult. To buy something for a couple hundred dollars off the shelf and start at least getting good quality at 180 VR.

[00:38:46] Adam: Sorry, before I forget, there's a build I know I want to do if we do another one of these, and I'm going to write it down.

[00:38:51] Norm: But Eric, like you brought some of the cameras here,

[00:38:54] Eric Cheng: I did,

[00:38:54] Norm: and like I recognize some that I've used, but like, what are some of your experiences?

[00:38:59] Eric Cheng: But Joey, do you want to show the camera that was used to shoot Tested VR?

[00:39:01] Joey Fameli: Yes, this is the this is the ZCam K1 Pro. This is what we used, and this is we have rigged up here. I have a video on that should be up now on Tested where I talk a little bit about it, and then there's also a video where we rigged it up. I mean, but this is essentially just the production camera,

[00:39:17] Norm: Micro Four Thirds sensor,

[00:39:19] Joey Fameli: Micro Four Thirds sensor. Yeah, two two fixed lenses.

[00:39:22] Adam: And you can't adjust the parallax on that, can you?

[00:39:25] Eric Cheng: No, it's it's set for around 64 millimeters average human IPD. These are very wide angle lenses. These are I think they're 220s.

[00:39:33] Joey Fameli: Right.

[00:39:34] Eric Cheng: From that, you get 180 degrees on each eye, and it works really well. So you see the quality that comes from here. The output is somewhere around 5K, five to 5.7K at 30 frames a second. These are consumer cameras. This is on a rail because I typically have these on a rail, extended out forward. This is these are hybrid cameras. The Vuze XR.

[00:39:56] Joey Fameli: Oh. That

[00:40:00] Adam: was a sexy.

[00:40:02] Eric Cheng: Let's do it again. Ready?

[00:40:03] Unknown speaker (Eric Cheng or Norm): Flips out.

[00:40:03] Eric Cheng: So there are a few. I brought a few of these cameras.

[00:40:06] Adam: Can I take this one on vacation with me?

[00:40:08] Eric Cheng: Sure. That's the Vuze XR. This is the Insta 360 Evo, also a hybrid stereo 180 and 360 camera. So you can fold it like this and lock it in place, and it becomes 360.

[00:40:19] Adam: Wow.

[00:40:19] Eric Cheng: And so there are a few of these cameras now. Actually, these are all the cameras that are out right now as we're filming this. This is it. And this is a Kanda KuCam, which has three three different lenses, so you can shoot in 180 mode here. Audience is over there, and then. You can flip it up here and shoot in 360. So, you know, these are smaller sensor consumer cameras, generally much less costly than something like this, and they all shoot in formats that look pretty good in headset. You know, you can get close to what we shot. Of course, I think the larger sensor makes things a lot cleaner and sharper in general.

[00:40:55] Norm: Lighting matters a lot.

[00:40:56] Adam: What does

[00:40:57] Norm: lighting?

[00:40:57] Adam: How so?

[00:40:58] Norm: I mean, just having because the smaller sensor enough light, having a good amount of light.

[00:41:04] Eric Cheng: Yeah, and I think that's one of the things that we're looking forward to going forward. Is this as the camera market matures? You know, in in traditional filming, the cameras can basically shoot in darkness,

[00:41:13] Adam: Right.

[00:41:13] Eric Cheng: and we are the sensors are just being integrated at a slower pace in this in this smaller area. But the newer cameras we're seeing are are very good in low light, and they're also shooting at 60 frames a second. So we may not want to get into motion and 30 frames a second, 60 you know headset refresh rates in this discussion. But motion is another one of these issues, not just camera motion, but the subject motion. You know, if you're shooting at 30 frames a second and you walk across, the you know the walk next to the camera very close, people will see that as a stutter, and that's something that 60 frames a second helps with a lot.

[00:41:49] Norm: Especially if we can't adjust the shutter, because we had no ND on on.

[00:41:52] Joey Fameli: Yeah, you can't adjust the shutter, but that was how you were essentially controlling the exposure.

[00:41:57] Norm: We can't lock our shutter and say our ideal shutter. Yeah. Frame rate. Yeah.

[00:42:00] Joey Fameli: Yeah. Wait. So the the K the the second camera has bigger sensor, 30 super 35.

[00:42:06] Eric Cheng: It's the same size sensor, it's an updated sensor, but it has dual native ISO, so right yeah 2500, which is great. Um, and it also has you can put any lens on, so you can choose a lens with adjustable aperture.

[00:42:06] Unknown speaker (Adam, Norm, or Eric Cheng): Oh wow,

[00:42:06] Eric Cheng: which this one doesn't have. Um.

[00:42:18] Unknown speaker (Adam, Norm, or Eric Cheng): Wow.

[00:42:18] Eric Cheng: Yeah. So the first gen one, the one we're shooting with here, has adjustable aperture, and then they revved it with a different lens that is fixed at f 2.5, which is very challenging because it's very stroby. You know, all the shutter shutter exposures, the exposures are super short.

[00:42:32] Norm: Yeah, there's so many of these little interesting lessons learned about, like you know, if one eye sees a light but the other eye doesn't see the light because then you know your brain doesn't

[00:42:41] Joey Fameli: right

[00:42:42] Norm: like that as much

[00:42:43] Joey Fameli: from a set design standpoint. You kind of want to throw some practicals up, but then once you get in headset, you realize that these are interacting with the lenses different in different ways because maybe one blocked.

[00:42:52] Adam: Fascinating.

[00:42:53] Joey Fameli: Yeah. Now I I can take this into Adobe Premiere and like I said, everything's there and I can edit with it pretty easily. Are there I guess are there other options if you were doing like a consumer version? Do they have their own little editing suites or is it pretty easy just to go straight from the camera to the headset?

[00:43:06] Eric Cheng: Yeah, they're they're all basically the same in terms of workflow, which is great because you don't have to learn anything new once you've learned that. But they they they get stitched, and I use stitched in air quotes because it's not really stitching; it's taking a factory calibration from the camera because these lenses, you know, in traditional stereo, Adam, you've worked in traditional stereo, right? So the the lenses. And the film plane or the sensors are are aligned and calibrated meticulously, you know, because they have to be perfectly matched. That has all essentially gone away. Now we're we're doing digital calibration. So they're calibrating the lenses. They're taking pictures of the lenses and lining them up in a calibration profile, and then that is used to.

[00:43:45] Adam: So they've solved it with the software.

[00:43:47] Eric Cheng: They've solved it. It's probably not as good as having a proper stereographer do it, but it gets the ninety-nine percent of people who don't, ninety-nine point nine percent of people who don't have access to a stereographer, it gets them. It makes them able to create this kind of content. So it basically unwraps the each lens according to that calibration and lines it up, and it's usually very close.

[00:44:06] Adam: This is reminding me of this back in the in the in the eighties. There, somebody figured out. I remember this was a big thing within stereos within home stereos. Someone figured out this ideal relationship between your main speaker and your woofers and your tweeters, and there was this ideal sort of cabinet with the right amount of airflow, and that was what everyone was doing for their speakers. And then I. Met John Meyer of Meyer Sound early on in our MythBuster days, and I said, " Do you have some special alchemy for your speakers?" And he went, " Hell no, we do it all with software." Yeah, bits move a lot faster than the speed of sound.

[00:44:38] Eric Cheng: Yeah, you drag the microphone in the middle and it plays.

[00:44:40] Adam: I put feedback loops in my speakers, and I get whatever I want out of them. And this sounds like digitally, the same thing is happening.

[00:44:46] Eric Cheng: Yeah, I mean, so what I said was was a simplification, but the important thing is that it happens automatically for most of these. So they're all of these cameras ship with some free tool that just converts what comes out of camera to a half-rectangular format, which is the standard for this in this space, and that gets pulled into Premiere, and Premiere can it connects to a headset, and you can view it in you know Oculus Rift, any connected headset in real time. So you can actually edit from from headset.

[00:45:12] Adam: Wow! Wow! From headset.

[00:45:14] Eric Cheng: Yeah, it's a live view. Anytime you put the headset on, it shows you the timeline.

[00:45:18] Joey Fameli: I was putting stuff. I was putting like titles and images in there, and just had the headset on. I was doing you know adjustments. I was watching things.

[00:45:24] Adam: Oh, that's so cool!

[00:45:24] Joey Fameli: Yeah, it was it was neat.

[00:45:27] Norm: And it all goes out the content, right? Like it. Even if you don't have the technical know-how, or like, it's not that difficult to put one of these on a tripod and film your family and like do interviews with your family members. But like, all three of us have newborns, and I've been filming.

[00:45:45] Adam: Welcome to the club, gentlemen.

[00:45:46] Norm: And like, it's it's been amazing because like, there's a real time distortion effect with having a newborn, as I'm sure you remember, right? Like, a year feels like five years, but you don't remember what happened.

[00:45:59] Adam: And at the end of that year, feels like six minutes

[00:46:01] Norm: exactly, right? And we've been filming the baby like you know semi regularly, once a month. And when he goes to bed, we put on a headset and watch, like the and we see the changes way more clearly than we remember it.

[00:46:16] Adam: Wow!

[00:46:17] Eric Cheng: Oh, you capture all the movements and you know their sort of way of being in headset, and it doesn't. I mean, this rig on a rail, so one of these consumer cameras. I travel with this all the time. I mean, that's why it's on here. I usually have there's a spatial audio recorder all in one from Zoom that sits right here in the back, and I just I literally just shove this in my bag and I pull it out and put it on a tripod. That's the part that I think a lot of people have to get used to. Is that if you stabilize the camera, you're going to get great results.

[00:46:43] Adam: Right.

[00:46:43] Eric Cheng: You try to handhold it; it can work, but it might not.

[00:46:48] Adam: Interesting.

[00:46:49] Joey Fameli: I was just talking to I was just talking to a professional snowboarder. We're at a we're at a YouTube event, and she was she was like, I want to do 180 3D video, but I want to like hold it while I'm snowboarding. I'm like, I don't know if that's the best idea. Like, but it was like it's like you're right there with me. I'm like, well, you should try it first.

[00:47:07] Adam: Try.

[00:47:07] Joey Fameli: I think with any of these, I think you do one session, you record once, take it to editing, view it. Like you've already learned so much. Like you'll walk out of there learning so much.

[00:47:15] Adam: It's iterative. You just got to keep on trying things. And some of them are not going to work, and some of them are going to be make you sick, and some of them are going to be awesome and transformative. And I think your experience of describing. What it's like to see your family because you've been doing this for so much longer than than us and most people. That emotional experience. It's important to remember that the first time people were watching film, and they filmed a train coming towards the screen, people were running out of the theater watching footage of a train come towards the screen because that was such a new experience to them. The optical illusion felt real, and so there was an emotional connection to that, even in what looks super primitive to us now. And that emotional connection to to using technology for storytelling is driving the innovation we've been talking about all podcast. It's really exciting. It's it's just a super exciting space to be in.

[00:48:09] Eric Cheng: It is, and the the pace at which it's evolving is also staggering. I mean, it's it's so amazing to look back. You know, before we might have had to look back years or decades to see fundamental change, and I feel like we are. We are now seeing it sort of on a you know one or two year cycle where the cameras evolve like formats are changing underneath. And one of the challenges in this space is that you know in normal media 4K is currently sort of the the upper practical limit. You know a lot of consumer cams, our phones shoot 4K. Most people don't play back in 4K, but typically all of the devices that you would use in the ecosystem handle it. We are sort of starting at 4K in this space, and so one of the the challenges has been figuring out how to you know play back 5K, 6K

[00:48:52] Adam: Right.

[00:48:52] Eric Cheng: video, and then when it gets to 60 frames a second, that's going to be another challenge. And so that's a lot of what's happening in in the headset is you know our headsets play back 5K, 5.7K video, and it and it makes a visible difference. And so we're right at that bar where things where people are starting to talk about the content and not the fact that they can look around.

[00:49:13] Adam: Right, right, exactly.

[00:49:15] Norm: Well, thank you so much, Eric, for joining us, and thank you for introducing us to. Awesome technology.

[00:49:20] Adam: But thanks for playing in this really, really fun sandbox because we—it's been really rewarding, and we're really proud of what we all got to make together.

[00:49:28] Norm: Yes, there are links below if you want to check out the Tested VR app to watch this all this content. And like Adam said, post your questions about how we thought through and how we did all this production in the comments below. And we'll be back next week.

[00:49:40] Adam: Yes.

[00:49:40] Joey Fameli: All right. All

[00:49:41] Adam: Right. Bye, guys.

[00:49:42] Norm: Bye.
