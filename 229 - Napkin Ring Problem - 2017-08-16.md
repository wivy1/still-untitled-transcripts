**Podcast:** Still Untitled: The Adam Savage Project  
**Episode:** 229 - Napkin Ring Problem  
**Date:** 2017-08-16  
**Duration:** 31m 53s  
Episode URL: https://www.youtube.com/watch?v=4JGUj_zdZnQ

[00:00:00] Norm: This week's episode of Still Untitled is brought to you by Eero. Whatever your Wi-Fi needs, Eero has the power to seamlessly blanket your home in fast, reliable Wi-Fi via Ethernet, wireless, or any combination. Simply set it on a flat surface or plug it into a wall outlet to expand coverage into any room. Not to mention, with the addition of a third 5 gigahertz radio, the second-generation Eero is now tri-band and twice as fast as its predecessor, which lets customers do more in every room of their home simultaneously. And with the addition of a new Thread radio, Eero can now connect to low-power devices such as locks, doorbells, and other sensors. Meanwhile, Eero Beacon is half the size but is even more powerful than original Eero. Whichever model you choose, with Eero's incredible customer support, you can call and get a hold of a Wi-Fi expert within 30 seconds. I set up my Eero in my home. Plug the beacon into the wall. Has nice night light when the room ambient light goes down. And now I can play my Nintendo Switch. Switch in rooms I previously couldn't even before, maybe even the bathroom. For free overnight shipping, visit eero. dot com and select overnight as the shipping option, and enter " Untitled" at checkout.

[00:01:17] Will: Welcome to Still Untitled, the Adam Savage Project. I'm Will.

[00:01:17] Adam: I'm Adam.

[00:01:20] Norm: And I'm Norm.

[00:01:20] Will: Hello, gentlemen. Hello,

[00:01:20] Adam: Hello.

[00:01:22] Norm: Hey, everyone. Good morning.

[00:01:23] Will: It's been a little while. It's been a hot minute.

[00:01:24] Adam: It has been a hot minute. It's only been like three weeks, right? We talked pre Comic Con?

[00:01:29] Norm: Yes.

[00:01:29] Unknown speaker: Yeah.

[00:01:29] Norm: I don't think we checked in with you.

[00:01:31] Adam: Good God! So it's been it's like three and a half weeks.

[00:01:33] Will: So we talked the week before Comic Con. I think that episode went up while you guys were at Comic Con.

[00:01:33] Norm: Yep.

[00:01:33] Will: And then you were gone.

[00:01:38] Norm: we did something at Comic Con, and then

[00:01:38] Will: I was gone.

[00:01:38] Norm: Yep.

[00:01:42] Will: [unclear: We've all been, we're / You were gone again / We were gone again]

[00:01:43] Norm: We were all gone.

[00:01:44] Adam: I was doing. By the way, I really appreciate that the most random Google searches from me can still yield that famous image of you in the VR goggles.

[00:01:54] Will: Okay, so I was at a thing that I can't talk about because of a lot of reasons, but. And there was a guy doing a presentation.

[00:02:01] Adam: Fight club.

[00:02:02] Will: There was a guy doing a presentation at the Fight Club with PowerPoint about the future of technology, and he got to his VR slide and he clicked over to it, and it was the picture that Norm took of me laying on the Birdly, and I think 2014.

[00:02:17] Norm: Yeah.

[00:02:17] Adam: Wow.

[00:02:19] Will: And

[00:02:19] Adam: is it that long ago already?

[00:02:19] Will: It was either 2014 or 2015.

[00:02:21] Norm: We have strong, well-faced SEO.

[00:02:24] Will: Yeah. Like, look, if you want pictures of white guys in Oculus Rifts tested, has you covered.

[00:02:29] Adam: I was look, I I didn't even log in my head what the search term was, but I was searching for something like Apollo suit connector.

[00:02:29] Will: Yeah.

[00:02:29] Adam: And came across, There you are.

[00:02:40] Norm: It's like four degrees of separation.

[00:02:40] Will: Yeah.

[00:02:40] Norm: They went to [unclear: Europe session / your obsession] on the site, and

[00:02:45] Will: yeah. So it happened, and I said, " Hey, that's me," out loud. It's like room of 20 people while this guy's giving his talk, and he he

[00:02:45] Adam: did they laugh? Did he get a laugh?

[00:02:45] Will: He stopped. Well, we had to talk through it. Like we had to go through the whole thing, and I had to explain it. And then we talked about Birdly because everybody was curious about what that thing was,

[00:02:45] Adam: right?

[00:02:45] Will: Which is still one of my all-time favorite VR experiences.

[00:03:04] Adam: I'm still sad I didn't get to do it.

[00:03:06] Will: Yeah. You were on tour, I think, when we did that. Maybe or away someplace.

[00:03:09] Adam: I missed it by a couple of hours. Yeah, like I could have if I'd flown back home and run to do it, but I couldn't quite do it.

[00:03:15] Will: But anyway, yeah. So, so what's what's been up to this last few weeks?

[00:03:19] Adam: Well, we got back from Comic Con. We had a lovely time there.

[00:03:22] Norm: Yeah, and all our content's out here out by now. The panel is great, actually. One of the things that we. One of the things that we had done at the panel that we we didn't get to do the panel is get a camera on the audience. And the last person who asked a question built

[00:03:22] Adam: Yes.

[00:03:22] Norm: a great Oogie Boogie costume.

[00:03:37] Adam: An amazing full-size Oogie Boogie. Oogie Boogie is the villain from Nightmare Before Christmas.

[00:03:42] Will: Oh,

[00:03:42] Norm: okay. And so he sent over some photos after the fact, and so we have on the site a gallery of his build progress, how he had built the interior wiring, the resourcing, the canvas.

[00:03:42] Adam: He was inspired by my Totoro build.

[00:03:42] Unknown speaker: Oh, nice!

[00:03:42] Norm: Both the Totoro and the Revenant Bear, apparently, too. Right? Yeah.

[00:03:56] Will: Oh, that's awesome.

[00:03:57] Will: Yeah, that's really cool.

[00:03:58] Norm: Yeah.

[00:03:58] Norm: But since then, we also published a video that I want to ask you about because I wasn't on this shoot, Adam.

[00:03:58] Adam: Yeah.

[00:03:58] Norm: And it's when you went to Detroit to visit a bunch of makerspaces.

[00:03:58] Adam: Yes.

[00:03:58] Norm: And one makerspace you visited was actually a factory of sorts. It's a record factory.

[00:04:14] Will: Adam,

[00:04:15] Adam: yeah. Sorry,

[00:04:15] Will: I've I've seen this person perform live ten or twelve times at this point. Yeah. Christmas Christmas shows. Yeah. At the Greek, a bunch.

[00:04:26] Adam: We the the amazing and the amazing and wonderful craftspeople and geniuses at Third Man Records in Detroit. Jack White's Detroit leg of his famous Third Man Records label opened their doors to tested, and we were able to go in and not only cover the the the operation as a lot of news outlets did, the operation of the first brand new record pressing plant in the U.S. in over three decades. They have eight brand new pressing machines, but Jack himself. Was in Detroit and gave us some time to talk about how the limitations of a fully analog system yield better creative results, and it was really inspiring. And I recorded the Brain Candy song live on their stage, and you watched the video.

[00:05:09] Will: Yeah. So

[00:05:09] Adam: that that the whole idea that there was nothing digital between me and the needle cutting the record was amazing to me.

[00:05:18] Norm: So I think with Jack, the way he explained it, he did it was he did in his very a very Jack White way. But the way he talked about how digital is zeros and ones, and as even as fine and as as packed as you can get,

[00:05:18] Adam: yeah,

[00:05:18] Norm: there is still going to be that gap.

[00:05:33] Will: Yeah, the DAC still does, or the ADC still does something. And he

[00:05:36] Adam: And he had, like, you know the jury's out on how much that affects us. I totally you know everyone audio people have their own particular interpretation.

[00:05:44] Norm: but it was it was less about the listening,

[00:05:44] Adam: yeah,

[00:05:44] Norm: and it was more about the recording.

[00:05:47] Adam: It was more about the soul of the recording and his stance, which is lovely and poetic, is that when the needle never lifts, you are getting something much more directly. Akin to, to what was being recorded,

[00:05:59] Will: I and and look, I I can see that, right? You like you're at some point. It's it's the what's the prob— what's the logic problem where you have to walk half the distance to the thing and you're not.

[00:05:59] Adam: Oh, you [unclear: can walk / can’t do].

[00:06:09] Adam: Nothing ever hits the ground.

[00:06:10] Will: Nothing ever hits the ground.

[00:06:11] Adam: it has to go half the distance,

[00:06:12] Will: Halfway, halfway, halfway.

[00:06:13] Adam: infinitely.

[00:06:13] Will: And when you're when you're when you're converting an analog sound signal into a digital signal, something I've done a lot of lately, then you're you're chopping it into infinitesimally smaller and smaller and smaller and smaller pieces, and then converting that into a number.

[00:06:26] Norm: But it's also the fact that you're recording directly to a master. There's no editing. There's no like even

[00:06:32] Will: with previous analog

[00:06:33] Norm: recordings, you could take that, you digitize it, you can edit it. There's there's something at stake here when you're recording directly.

[00:06:41] Adam: There's a mistake in my recording, and we we chose the take with the mistake.

[00:06:46] Will: Well, so so they're recording live, and they're not doing mastery on like a on like reel to reel tapes or anything like that.

[00:06:52] Adam: Also recorded on a reel to reel, but but the recording that we did was cut directly onto a record lathe. Wow. Not to a reel to reel, and then to a record lathe.

[00:06:52] Adam: And by the way, we have

[00:06:52] Norm: Oh.

[00:06:52] Adam: what the five test pressings here. So after this podcast, later on today, we're gonna film me pulling out my record player and listening to these for the first time and giving my acceptance so that we can run these.

[00:07:15] Norm: Yes.

[00:07:16] Adam: Test. Third man test pressing.

[00:07:16] Will: Wow.

[00:07:16] Adam: And by the way,

[00:07:16] Will: wow,

[00:07:16] Adam: the brain candy song is the first song to be recorded on their stage that is also being produced in the plant.

[00:07:29] Norm: Oh. They they have a Excuse me. they have what looks like a I guess they call like a um like a photo booth for music.

[00:07:35] Adam: Yes, they have this old forties photo booth that cut a record on acetate for three minutes.

[00:07:35] Norm: Yeah.

[00:07:41] Unknown speaker: What?

[00:07:42] Will: Okay,

[00:07:42] Will: I want to go. There was something we glossed over this, and I want to go back to it.

[00:07:42] Adam: Okay,

[00:07:42] Will: you said that they're the first brand new record pressing plant, and they're using brand new record pressing machines.

[00:07:51] Adam: Yeah, these are eight brand new machines from Germany.

[00:07:52] Will: So okay, so there's a German factory that's been making record pressing machines all this time, or somebody spun this back up again.

[00:07:58] Adam: That is your guess is as good as mine. Okay. I have not researched that deeply into it.

[00:08:02] Will: I am super curious about the the economics and mechanics of rebuilding this. Like, it's got to be kind of like the like what NASA did with the SLS, where they came in and re. If they're starting from scratch forty years after people stop making records,

[00:08:16] Adam: That’s lost knowledge.

[00:08:18] Will: Yeah, then there has to be lost knowledge, and they have to be going back and recreating all this stuff from from from from 

[00:08:23] Adam: Good question. I don’t know the answer to that. Wow the the the third man people could not have been more welcoming or or helpful. I mean, it was just that was a fantastic trip.

[00:08:34] Norm: And also, just watching it when the recording when you sit up on stage because it is a stage

[00:08:34] Adam: Yeah, a little stage.

[00:08:34] Norm: with an audience,

[00:08:34] Norm: yeah, and you recorded onto a really interesting microphone,

[00:08:44] Adam: a ribbon microphone. So it literally is a ribbon of of stainless steel or some fine material, yeah. And they they set them up in in this. I can't remember what he called it. The figure eight. So that one was pointed, one ribbon was pointed directly at my mouth, and the other was pointed directly at my uke, and they really didn't pick up anything that was outside their their signal band.

[00:09:07] Norm: Okay, okay. Yeah. The way the audio engineer explained

[00:09:09] Adam: is not the way to describe it, but

[00:09:10] Norm: I just the the space in which microphones pick up, like the volume.

[00:09:14] Will: Yeah. It

[00:09:14] Norm: was perfectly. It's it's not like they're not going to get any interference, but I didn't know that you could have mics directional in that form factor.

[00:09:22] Will: Well, that's an old timey kind of mic, too, right? Yeah. Like this is it was it was probably designed specifically for the problem of hey we need somebody who's playing a string instrument at their waist and singing at their mouth.

[00:09:31] Will: Well, and and they didn't have super cardioid condenser mics at that point.

[00:09:34] Adam: And Jack's obsessed with that technology. The oldest technology. It has a lineage and an import to him and to the stuff that he does that is really really cool because he's breathing, breathing breath back into this like humans did this. You don't just speak into a black box and hear it later from black headphones. It is. These sounds have a history, and the way we've recorded them has a history.

[00:09:34] Adam: And it’s beautiful.

[00:09:58] Will: There's an intrinsic nature to the to the sound. That's rad. That's so— I'm so glad you went there. I'm so excited.

[00:09:58] Adam: It was the best.

[00:09:58] Will: Yeah, that's the coolest. Look, you've been to the since I left. You guys have gone to the Large Hadron Collider. You've done a bunch of cool shit. It's far and away.

[00:10:15] Adam: Oh yeah,

[00:10:16] Will: I think the coolest. Yeah. Until you actually go to space.

[00:10:19] Norm: Well, it's in Detroit. You can make a book a plane ticket.

[00:10:21] Adam: I also. I didn't tell Jack this, but I sang his song " Love Interruption" on stage at Bootstock at Comic Con this year. Yeah, I decided to do it. I decided to try it out.

[00:10:30] Will: My my daughter's favorite is from I think the acoustic recording albums, but it's the cover of of the song that he and Meg used to sing when they were in the White Stripes. The song, the the I know the love one another. I love, Jack White, like he's my brother. That song, you know the.

[00:10:48] Adam: It's. I'm sorry, no. Not the way you've just said it.

[00:10:52] Will: No, no, no, not the way I just say it. I say it mushy mouthed and sad. But yeah, yeah, we listen to that a lot. I listen. That is one of those albums that I put in hundreds and hundreds of times. Yeah, if I can't think of what I want to listen to. I just put Jack White on.

[00:11:05] Adam: Yeah, those albums are so awesome. Those ones that have that kind of resonance too.

[00:11:10] Will: They’re all good, but yeah.

[00:11:12] Norm: And then, no, we were back in the office for a week and a half or so, and you did an event at the Exploratorium.

[00:11:20] Adam: Ah, yes,

[00:11:20] Norm: in San Francisco, and

[00:11:21] Adam: Well, Space Fest was last weekend up in up in Napa. Okay, so Al Warden, who visited the shop here earlier this year, and our friend Ryan Nagata was up there showing off some stuff. That was really cool. But the Thursday before Space Fest,

[00:11:36] Norm: the Exploratorium did one of their after dark events, and it was all space themed. And and you brought spacesuits among other types of suits to to have on display that evening. But want to give people who even weren't who even were there what they didn't see, which is that you spent the Two days before that, rebuilding stands for your spacesuits.

[00:11:56] Adam: I spent more than two days before that. But when you when you collect costumes and you want to display them, you want to display them in ways that feel right, that look good, and that is a thorny and complicated issue.

[00:12:10] Will: The first time we did the Comic Con party, and for that matter, the second time we did the Comic Con party,

[00:12:15] Adam: all those mannequins sucked.

[00:12:16] Will: We spent the first time we spent a very reasonable amount, what I thought was a reasonable amount of money on mannequins, and they were terrible.

[00:12:22] Adam: All of them terrible.

[00:12:22] Will: All of them awful.

[00:12:24] Will: And then the second time. The second time we spent slightly more money on mannequins. The second time we spent slightly more money on mannequins, also terrible.

[00:12:24] Unknown speaker: All of them terrible.

[00:12:24] Adam: Yep.

[00:12:24] Will: And and like you look at what you look at what like Deborah Landis did, Nadoolman Landis did at the Lakme exposition.

[00:12:35] Adam: It was not Lakme. It was not Lakme. It was actually the Academy. Was next door to Lakme, but anyway,

[00:12:41] Will: okay. Anyway, but what what they did with mannequins there was

[00:12:44] Adam: unbelievable. Every single one of those mannequins was custom built to the dimensions of the actor that wore the costume. The mannequin was holding up

[00:12:52] Will: and featured like representations of key props and stuff like that, too.

[00:12:56] Adam: So. I have gotten better at mounting my costumes. I have learned more about what are the deal breakers in terms of the mounting points and how rigid they need to be, and how the costume gets filled out. And I'm really proud with the five pieces I brought. I brought Ryan Nagata's a seven L suit. I brought my Mercury suit built by Elizabeth Galleria. I built. I brought my Mike Scott built two thousand and one spacesuit. I brought the EMU suit, right? I brought the yes. Yes. I brought the NASA EMU suit from the education department that's got real Teflon in it. And then I brought the suit of armor that we built in England with Terry English.

[00:12:56] Will: Nice.

[00:12:56] Adam: Because I I think these things all have a lineage to each other. Humans desire to build ourselves a protective shell. And on stage at the Exploratorium, I brought my friend Nicholas de Monchaux, who literally wrote the book on spacesuits. He wrote the book called " Spacesuits" about the history and the development of NASA's.

[00:13:54] Will: Seems like an apropos.

[00:13:54] Adam: Spacesuit.

[00:13:55] Norm: He told some really good stories. This the video of that is actually on Exploratorium's. Facebook page. They did a live stream of that, but something I did not know: why did Sputnik beep?

[00:14:06] Adam: Right. That okay. This is super, super, super cool.

[00:14:10] Will: Was it just so they could track it?

[00:14:11] Adam: No, Okay. it was so that they could track how well it was doing. Here's the thing about Sputnik: is in order to send its radio signals, it used tube technology, right?

[00:14:11] Norm: Oh, radio tubes. Yeah.

[00:14:11] Will: Yeah. Yeah.

[00:14:11] Adam: Yeah. Yeah. Yeah. Yeah. Yeah. But those tubes could not work in the vacuum of space because they needed air

[00:14:33] Will: movement around them

[00:14:34] Adam: to keep them cool. So Sputnik was pressurized with an atmosphere.

[00:14:34] Will: [unclear: So / Is that why / Is that what] it was around?

[00:14:34] Adam: Yes, I guess. Wow. So it was pressurized with an atmosphere so that its radio equipment could work, and the beeping was the radio equipment going, " We work."

[00:14:49] Norm: It was to measure the the atmosphere,

[00:14:49] Will: Wow.

[00:14:49] Norm: The the interval of the beeping was a way of measuring the atmosphere.

[00:14:57] Will: Oh, because if it gets hotter, the beeping's going to go slower and slower and slower, something like that. That

[00:14:59] Norm: Wow. [unclear: so that became more regular than the radio equipment / so that the radio equipment would work]. Wow!

[00:15:02] Will: I assume it was something like they were measuring Doppler because they want to know how fast things were going. But I guess they knew how because they have radar. But that's bonkers.

[00:15:09] Adam: Yeah. So Nicholas is full of wonderful stuff like that. We we we talked about the history of the spacesuit, the development, the design, how Hollywood's gotten it right and wrong. I would have loved to have had the the the Martian spacesuit there, still still being still working on it. But to me, it's I love pointing out to people that the spacesuit is the most futuristic part of the movie, The Martian.

[00:15:31] Will: Oh, far and away. Like the thing, so there's. I would love to look at like the last four or five years of of spacesuits in film, like like from

[00:15:31] Adam: it's been a really good run

[00:15:31] Will: From The Martian,

[00:15:31] Will: and Prometheus and Interstellar,

[00:15:45] Adam: Interstellar, Passengers, even

[00:15:45] Norm: lovely suits in that.

[00:15:48] Will: Yeah, and and kind of like break down what what is potentially what is real now, what's potentially real in the future, and what is pure science fiction.

[00:15:55] Adam: Moon

[00:15:55] Adam: also has some really lovely designs,

[00:15:57] Norm: and all of that is. Some of that's so impractical for the purposes of NASA,

[00:15:57] Unknown speaker: Yeah.

[00:15:57] Norm: mostly because there's no real need to have a spacesuit in the real world that a person gets them by themselves.

[00:15:57] Unknown speaker: Okay.

[00:16:08] Adam: Yeah.

[00:16:08] Will: Or that,

[00:16:08] Norm: right,

[00:16:08] Will: or that it has lights in the faceplate that illuminate your face.

[00:16:11] Adam: Exactly.

[00:16:11] Adam: That's just always going to happen.

[00:16:11] Unknown speaker: Yeah.

[00:16:11] Adam: Yeah.

[00:16:11] Adam: You got you got to watch

[00:16:11] Adam: like Ridley's just going to light the scene. You should watch Thelma and Louise when it looks like they've got a 10k under the dashboard pointed at Susan Sarandon and Geena Davis.

[00:16:23] Will: Oh yeah.

[00:16:23] Unknown speaker: Oh yeah.

[00:16:24] Adam: Like they're driving at night and it's just a giant light on them from inside.

[00:16:26] Will: So I rewatched that movie last year. I assumed that he had like Klieg lights when they were shooting outside in the desert because it is it's just it's just vivid.

[00:16:34] Adam: Yeah.

[00:16:34] Will: Yeah. Anyway,

[00:16:35] Adam: what a great movie. It's

[00:16:36] Will: a fine film.

[00:16:37] Adam: Um. Uh. So yes, spacesuits in film.

[00:16:42] Will: Yes.

[00:16:42] Adam: Wow, that was a derail.

[00:16:43] Will: I didn't mean to. Interstellar. We were talking about the.

[00:16:46] Adam: Talking about that they've gotten better.

[00:16:48] Norm: Yes. Yes. Oh.

[00:16:49] Adam: Yeah.

[00:16:49] Unknown speaker: Go ahead.

[00:16:49] Adam: The thing I was going to point out was my favorite spacesuit in film, and I wore the beautiful FBFX Covenant suit, and I've talked about those my friends there. A lot because they do such amazing work, but their hard suit for Danny McBride for Alien Covenant for for Tennessee is one of the coolest things I've ever seen,

[00:16:49] Unknown speaker: Really?

[00:16:49] Adam: and it is it's it is a full complete hard suit that you can put on like NASA's hard suit in that it's all ball bearing joints and all the ball bearing joints are 3D printed.

[00:17:17] Norm: Yep,

[00:17:18] Will: really?

[00:17:18] Adam: Uh huh. 3D printed races with phenolic balls and a and a 3D printed bearing race that holds those balls in orientation, and it

[00:17:18] Will: wow,

[00:17:18] Adam: it worked.

[00:17:27] Norm: This is the one that looks like a dive suit.

[00:17:28] Will: Yeah, yeah, yeah, it looks like the kind of hard side dive suit that people use right now on the bottom of the ocean. Yeah. So

[00:17:33] Adam: apparently there was a stand in one of those that didn't actually function in Prometheus, and Ridley really liked that, and the FBFX Andrew Down and Grant they they decided to tackle this.

[00:17:33] Unknown speaker: Wow.

[00:17:33] Adam: And the cost of using real bearings like Kaden six and eight and ten inch bearings prohibitive.

[00:17:33] Will: Yeah.

[00:17:33] Adam: I mean, like a the six inch two six inch bearings that are in my Hellboy mecha glove over there. Are retail for over six hundred dollars a piece. Yeah. So when you think about like twenty five bearings within a suit, it's it's impossible.

[00:18:04] Will: You can't do that.

[00:18:04] Unknown speaker: No.

[00:18:06] Adam: So they three D printed them and they totally worked.

[00:18:08] Will: Wow. What? What? What did they use it? What did they three D print on? Like a laser centering printer?

[00:18:13] Adam: No, I think this was filament, but I'm not. Yeah.

[00:18:16] Norm: Really? Oh yeah. Some of that stuff, if you look up close, it looks like finished filament. I don't know about the bearings, but yeah, they're using. Because they need to get it big. Yeah.

[00:18:16] Will: Yeah.

[00:18:16] Norm: These are big pieces.

[00:18:24] Will: Yeah. Yeah. So they put on a big Rostock or something. Yeah. And wow,

[00:18:27] Norm: that's something that's also funny because we have that video where you walked in the FBFX suit from Covenant, right?

[00:18:27] Adam: Yeah.

[00:18:27] Norm: There, there.

[00:18:27] Will: Yeah.

[00:18:27] Norm: I think I'm not sure if it's their EMU, but the one they near the end of the movie. Yeah. Um, and there are so many lights and displays, like actual displays on the gloves,

[00:18:27] Adam: Yeah.

[00:18:27] Norm: displays in the backpacks, and being able to go inside, we could see the source of those displays. Some of them are like their iPod Nanos, 

[00:18:27] Adam: right?

[00:18:27] Norm: iPod Nanos,

[00:18:50] Adam: just little screens that self run. Yeah. Yeah,

[00:18:53] Norm: they run like an Hour of footage,

[00:18:54] Adam: you know. Yeah. Ten years ago, that would have been a little bit of acetate with some LEDs behind, not even some incandescents behind it to light it up, and now it's an actually animated screen.

[00:19:03] Will: And I mean, you look at what you can get on on like Adafruit or something like that,

[00:19:03] Unknown speaker: Totally.

[00:19:03] Will: and you can buy little kits that are like three-inch LCD or OLED screens. The

[00:19:10] Adam: little display on my captain's chair,

[00:19:10] Will: yeah,

[00:19:10] Adam: that's a that was like twenty-five dollars.

[00:19:10] Will: Yeah,

[00:19:10] Adam: yeah,

[00:19:16] Will: bonkers.

[00:19:16] Adam: You used to have to go buy a Sony Watchman.

[00:19:19] Will: Oh boy, here we go. Old man Savage at it again.

[00:19:19] Adam: When I was a kid

[00:19:19] Adam: [unclear: my day, we we had to go to Canal Everlate / We’re gonna go to Canal Webber / Oh my day. We didn’t need that. We had to go to Canal Webber].

[00:19:19] Will: Um,

[00:19:30] Norm: another video we also put up, and this one people have to watch is your build with. Speaking of brain candy, with Michael Stevens,

[00:19:38] Adam: that was so. I built a kendama with kendama, right?

[00:19:38] Norm: Yes, yes.

[00:19:42] Norm: It’s

[00:19:42] Will: Japanese ball and cup thing.

[00:19:43] Norm: Yes.

[00:19:44] Adam: So I built one out of Delrin

[00:19:44] Will: Okay.

[00:19:44] Adam: with Michael Stevens because he's become quite adept at it, and has been working on a Kendama video that I think also went up on Vimeo, Vsauce on

[00:19:44] Will: Okay.

[00:19:44] Adam: Yeah. On last Friday.

[00:19:44] Norm: Yeah.

[00:19:44] Adam: Because I, sorry, I mean, you know, one of the reasons we shot this was because we wanted to let people know that we're touring Brain Candy again. Tickets are on sale at BrainCandyLive.com, and we're touring again in November and December all over the country and a little bit of Canada. And you know what? I just love hanging out with that guy.

[00:20:16] Norm: That, that’s. He seems like a

[00:20:17] Will: delightful nerd.

[00:20:18] Norm: The build video—it's an hour long, but it's like maybe sixty percent of it is about the Kendama and the build. The other forty percent is just watching you guys hang out and ask each other questions and go into deep, random, tangential deep dives into things like the the napkin 

[00:20:34] Adam: ring, napkin ring paradox. Man, we’re totally gonna. Okay, the napkin ring paradox.

[00:20:34] Adam: You ready to have your mind blown?

[00:20:39] Will: I made the eyebrow at you.

[00:20:41] Adam: Okay. So take a take a tennis ball.

[00:20:45] Will: Yeah.

[00:20:45] Adam: And take a a beach ball, three foot diameter beach ball.

[00:20:45] Norm: Yes.

[00:20:45] Adam: Okay. If you bored a hole through the tennis ball,

[00:20:54] Norm: like cored it with a cylinder,

[00:20:56] Adam: you cored it out so that the remaining the remaining ring that you were left with was let's say an inch and a half tall.

[00:21:02] Will: Okay.

[00:21:03] Adam: Okay. So picture that a tennis ball in which I cored it out. There's an inch and a half of ring. Right?

[00:21:08] Will: Right. Right.

[00:21:08] Norm: Yeah. Yeah. Where the interior of the ring is smooth. It’s, it’s

[00:21:11] Adam: yeah. So we're thinking of the tennis ball as a solid.

[00:21:13] Will: You’re talking about a torus at this point.

[00:21:15] Adam: Yes. Yes. Topologically, a torus. Yeah. A toroid. Torus?

[00:21:19] Will: Toroid. You're right. Because a torus would be would be a cylinder all the way around. Okay. This is not. This is. This is anyway.

[00:21:24] Adam: So we've cored a solid ball the size of a tennis ball, and we're left with a a remainder that is an inch and a half tall.

[00:21:24] Unknown speaker: Okay.

[00:21:24] Adam: We do the same thing to the beach ball. We cored the beach ball so that the so that the remaining ring

[00:21:39] Will: is an inch and a half.

[00:21:39] Adam: Is an inch and a half tall. Both rings have the same volume.

[00:21:44] Norm: Now if you take the Earth.

[00:21:45] Will: You mean?

[00:21:45] Norm: And you core.

[00:21:45] Will: Wait. Wait. Wait. Wait. Wait. Hold on a sec. So you need a bigger core. why do both rings have the same volume because the diameter is much bigger.

[00:21:52] Adam: The diameter is bigger. The diameter is bigger, but the thickness is much less, and if their height is the same, their volume is the same.

[00:21:59] Will: Are you talking about the volume inside

[00:21:59] Norm: Not the mass, the volume.

[00:21:59] Will: No, no, I mean I mean the volume inside the the circle or—

[00:21:59] Norm: the volume of the strip,

[00:22:07] Adam: the volume of the ring,

[00:22:08] Norm: the ring.

[00:22:09] Will: Well, but that's because the tennis ball is thicker than the beach ball.

[00:22:13] Adam: No. Okay. So again, picture picture that you're you're you're taking a tennis ball and coring out almost everything, but leaving enough of the tennis ball sphere.

[00:22:22] Will: Yes.

[00:22:23] Adam: So that the out so that that ring that is that you haven’t cored.

[00:22:27] Will: Yeah.

[00:22:28] Adam: The negative space of your core.

[00:22:28] Will: Yeah.

[00:22:28] Adam: Is an inch and a half tall.

[00:22:31] Will: Okay.

[00:22:32] Adam: And then you core a three foot diameter ball. I'm sorry, we'll cut this down so you guys don't have to hear this.

[00:22:37] Will: I’m sorry.

[00:22:37] Norm: no, they're going to get the whole

[00:22:38] Adam: look. It's my problem. I haven't explained it correctly. So then you core out the three foot diameter ball, so that again you're coring almost everything.

[00:22:45] Will: Okay, I get this.

[00:22:46] Adam: And you've got this ring,

[00:22:46] Will: a thin strip.

[00:22:46] Adam: Now the tennis ball ring. The tennis ball ring and the beach ball ring are both the same height.

[00:22:46] Will: Okay.

[00:22:46] Adam: If they're both the same height, they are the same volume, and this continues no matter how big the sphere is.

[00:23:00] Will: But what volume are you talking about? You're talking about the volume of the space inside that ring.

[00:23:00] Norm: No, no, no.

[00:23:00] Adam: No.

[00:23:04] Adam: Take that ring. Take that ring and put it in water. It will displace the same amount of water. The tennis ball as. Doesn't

[00:23:10] Will: it matter how thick the materials that you make the ring out of?

[00:23:15] Norm: This is the paradox.

[00:23:18] Will: I'm so fucking confused right now. Okay. Okay.

[00:23:20] Unknown speaker: No.

[00:23:20] Norm: Oh, boy. No, no, no.

[00:23:20] Adam: No, no.

[00:23:21] Adam: Here we go.

[00:23:22] Norm: Adam’s going to do a drawing.

[00:23:23] Adam: I’m going to do a drawing. Here we go. All right.

[00:23:25] Norm: That’s why it’s hard to wrap

[00:23:27] Norm: your head around.

[00:23:28] Will: That sounds great.

[00:23:29] Norm: And it's not. Yeah, it's not so much a paradox as it is, I guess, a

[00:23:33] Will: weird physical property or something.

[00:23:35] Norm: Yeah. So

[00:23:37] Adam: let's say I core this tennis ball, and so I core this out. So this is gone.

[00:23:42] Will: Yeah.

[00:23:42] Adam: And this is what I'm left with, and it is a ring.

[00:23:46] Will: Yeah.

[00:23:46] Adam: Right.

[00:23:46] Will: Got that.

[00:23:47] Adam: Okay. Now I take a beach ball, and I want to core it so that the resulting ring from the beach ball is also exactly one point five inches high.

[00:23:47] Will: Yeah.

[00:23:57] Norm: Any any similar height.

[00:23:58] Adam: Yeah. And to do that, you realize that the the ring of the beach ball would be incredibly skinny.

[00:24:03] Will: Okay.

[00:24:04] Adam: Right, because I'm removing so much material from the center in order just to get that inch. But

[00:24:10] Will: aren't you just taking an inch and a half section out of the middle of the beach ball?

[00:24:15] Norm: But it's empty in the middle.

[00:24:15] Adam: [unclear: No, it’s empty / No, I’m left].

[00:24:17] Adam: I'm removing the core.

[00:24:17] Will: Okay.

[00:24:17] Adam: I'm removing that and that.

[00:24:21] Norm: And also, what’s in the center?

[00:24:21] Adam: All the way through.

[00:24:22] Will: You know, I get that part.

[00:24:22] Norm: Yeah.

[00:24:22] Will: I. This is this is why it's a paradox. You absolutely flummoxed me today, sir. We're gonna go get the big drill out in a minute, and we're gonna get some tennis balls and beach balls. We’re drilling right through a ball.

[00:24:22] Norm: Yes.

[00:24:34] Adam: And we're left with a with a ring.

[00:24:35] Norm: Yes.

[00:24:35] Adam: Right.

[00:24:35] Norm: Yes.

[00:24:37] Adam: And we're basically if whatever that if you choose a dimension for that ring, no matter how big the ball is,

[00:24:44] Will: the resulting ring is the same [unclear: ball].

[00:24:44] Unknown speaker: Because of the shape of the sphere,

[00:24:44] Will: You're always left with the same edge of the thing. Wow, that is bonkers.

[00:24:49] Adam: And it works even if the sphere is the size of the Earth.

[00:24:52] Norm: Right. Right.

[00:24:52] Will: Well, we tried that.

[00:24:52] Norm: That seems experimentally difficult to prove.

[00:24:52] Will: I mean, I think the people in Canada might be upset.

[00:24:57] Adam: At any rate, we spent some time talking about the napkin ring paradox. Wow! I mean, that's a mind-blowing paradox, and to to demonstrate it is is actually possible using a good lathe.

[00:25:06] Will: So it has to work with a sphere, though it has to be a perfect sphere or something close to a perfect sphere.

[00:25:06] Will: Yeah.

[00:25:06] Adam: Absolutely.

[00:25:06] Will: So the Earth wouldn't work; it's squish.

[00:25:13] Norm: Thank you, Will.

[00:25:15] Adam: This is. Will’s officially the first comment on that YouTube video.

[00:25:21] Will: Well, you know, this is a good time to introduce

[00:25:21] Unknown speaker: slightly pear-shaped, like me.

[00:25:21] Will: to introduce my new podcast. Actually, comma. Um. Wow.

[00:25:33] Unknown speaker: Wow. Wow.

[00:25:33] Adam: Anyway,

[00:25:35] Norm: yeah, the video that build video is full of anecdotes. I

[00:25:38] Adam: watched the whole thing. Look, I I don't watch all the videos that we produce all in their entirety.

[00:25:38] Will: Yeah.

[00:25:38] Adam: Um. Lately, Joey's editing has been just blowing my mind. How much I love the the sword build. Yeah,

[00:25:50] Norm: Excalibur sword build. Yeah, Gunther did this one, and yeah, they're they're really great.

[00:25:55] Adam: They're really lovely. Um. So this one with with with with Michael Stevens was really lovely. Like it is just like that. To hang out.

[00:26:02] Will: Did he come up here?

[00:26:03] Adam: He came up here.

[00:26:03] Will: Okay.

[00:26:04] Norm: Cool. And we actually have a few more videos from that day. He spent a full day with us, so those are going to go out a little bit later. But yeah, if you want to see more of Michael and Adam, they can see him on stage in the fall.

[00:26:14] Adam: Yes.

[00:26:14] Will: So what else is coming up, guys? We got a minute or two left.

[00:26:17] Norm: Um. So last week I spent a couple days down at Frank's shop where we hung out with these guys out of Washington, called CNC Router Parts. They make full-size CNCs that are like a fraction of the cost of like a giant, you know, pre-built Tormach or something. And we built one. We built. They they they sell a CNC kit that's

[00:26:17] Will: Like a mill?

[00:26:37] Norm: four feet by eight feet. Yep. Wow. And they they equipped gave us one with two heads, a two-headed CNC. So they think of like a three-axis 3D printer. Yeah. Uh, one for your rotary tool. Uh huh. And one for a plasma cutter.

[00:26:37] Will: Whoa.

[00:26:37] Norm: So we plasma cut some some sheet metal.

[00:26:37] Will: Nice.

[00:26:37] Norm: Wow. And those these things, the the most interesting to me thing to me though, and I kept asking about this was the drive system they use for the CNCs, because like you know we have some desktop CNCs at our office, and they're perfectly fine. They're a little smaller, you know, a little more self-contained,

[00:27:10] Will: like the Carvey and stuff like that, Right?

[00:27:11] Norm: exactly. And they all use like every three-axis machine, or they use different drive systems, like whether it's a

[00:27:17] Will: what's usually stepper motors on a series of gears and pulleys, Right?

[00:27:20] Norm: Right. But what, yeah, gears and pulleys, or they they have you know your tensioning band, a screw drive, or something. And they were using things where they needed to be fast, need to have a zero very low backlash when it stops acceleration, and very accurate. And this thing moves it like it hauls

[00:27:38] Adam: how many inches per foot, many inches per minute. I don't

[00:27:40] Norm: know, I don't know the exact number, but it was moving when it was cutting like a big sheet of MDF. It was just like chomping through.

[00:27:40] Adam: Awesome.

[00:27:47] Will: How was this compared to the very first MakerBot we built, the cupcake back in twenty ten?

[00:27:52] Unknown speaker: Oh, yeah.

[00:27:52] Norm: That’s right. Pretty good. Pretty good.

[00:27:54] Will: [unclear: I’d say I / Did it blast out a little bit of plastic at the end / I’d say it wasn’t one of those]?

[00:27:55] Adam: [unclear: don’t want to say pretty / …]

[00:27:55] Will: [unclear: good. Yeah / I built / …],

[00:27:56] Adam: one of those.

[00:27:57] Will: How many tries did it take you to get it to work? Just out of curiosity.

[00:28:00] Adam: Okay, so yeah, I built it in my office. They they sent me one when they first sent shipped them out. So I sat there in my office for a couple days and put it together. And I, I, I’m, I’m, I’m not sure I can tell you I got a good print out of it.

[00:28:13] Will: We eventually got okay prints on that.

[00:28:14] Adam: I think I tried three times, and it messed up.

[00:28:17] Unknown speaker: So many

[00:28:17] Norm: putting nuts in nut slots and bolting things together, and

[00:28:20] Will: so many nut slots.

[00:28:20] Norm: Yep, yep.

[00:28:20] Will: We did, we did.

[00:28:20] Adam: Too many

[00:28:24] Adam: nut slots.

[00:28:25] Will: We did five. It took us a week, basically was three days probably to build it. It was a week worth of videos, I think.

[00:28:25] Norm: Yeah.

[00:28:25] Will: And then it was maybe three months before I got a decent print out of it.

[00:28:25] Adam: Wow,

[00:28:35] Adam: This was.

[00:28:36] Adam: I gave mine to my kid's school to fix. [unclear: that didn’t / and] work out.

[00:28:39] Will: Yeah,

[00:28:40] Norm: yeah, a four by eight, which like you can put in a a big four by eight sheet of ply right on top of the machine. They took one day for physical construction, one day for electronics.

[00:28:40] Will: Wow,

[00:28:40] Norm: yeah,

[00:28:49] Unknown speaker: Not bad.

[00:28:50] Norm: Not bad.

[00:28:50] Unknown speaker: [unclear: That’s three / All. That’s awesome / …]

[00:28:50] Unknown speaker: [unclear: people on / That threw people on it / …]

[00:28:50] Will: [unclear: it / …],

[00:28:51] Will: and then like once you had it up and working, everything was kind of worked itself out.

[00:28:54] Norm: A little bit of troubleshooting, but mostly.

[00:28:56] Will: That's awesome.

[00:28:57] Adam: That's fabulous.

[00:28:57] Will: What's the company again?

[00:28:58] Norm: CNC router parts. Yeah, we met him at Maker Faire.

[00:28:58] Adam: Okay,

[00:28:58] Norm: they said they at Maker Faire made crossbows for people.

[00:28:58] Will: That sounds great.

[00:28:58] Norm: And gave them out like

[00:28:58] Norm: ping pong ball crossbows.

[00:28:58] Will: Oh, I was gonna go.

[00:28:58] Norm: ping pong ball crossbows. They're still technically crossbows.

[00:29:11] Adam: Weird

[00:29:12] Adam: Party favor for children

[00:29:13] Norm: every hour. Like, here is a crossbow for you, and a crossbow for you.

[00:29:17] Adam: Yeah, I, I will tell you that as far as television goes, I've been rewatching the first season of Master of None, Aziz Ansari, and the second season is so good, it made me want more, and made us go back and rewatch the first season, which is even better than I remember.

[00:29:34] Norm: Oh,

[00:29:34] Will: um, I wanted to shout out. I, I fell into an Atlas Obscura hole the other day.

[00:29:39] Adam: Oh, such a good site.

[00:29:40] Will: And if you don't know about Atlas Obscura, you should go type it into Google right now and just prepare to lose like four or five hours.

[00:29:47] Adam: I would say if you’re traveling. If you are traveling, Michael Stevens and I turned out to both have the same method on tour, which is Atlas Obscura. Atlas Obscura is one of our very first stops on any given day to find out. Oh, maybe we should go to the haunted insane asylum here.

[00:29:58] Unknown speaker: Well.

[00:29:58] Will: This is like your. This is like your your your restaurant tip, right? Like, like go look and see if Parts Unknown has been.

[00:30:06] Adam: See if Anthony Bourdain has been there. You should go eat there.

[00:30:08] Will: Go where he ate, and you'll be okay.

[00:30:10] Norm: The weird thing, GQ review, a GQ interview with Aziz Ansari.

[00:30:14] Adam: Yeah,

[00:30:14] Norm: he opens with him going to a restaurant, being the writer of the restaurant where I had dinner with Kishore when we were in Paris. The same place. Oh. Random Alley restaurant, that was also a Bourdain recommendation.

[00:30:14] Adam: Wow. Well, there you go.

[00:30:14] Norm: Completely tied into—

[00:30:27] Adam: I mean, he's totally plugged into Bourdain because Cannavale, Bobby Cannavale, he's totally playing Bourdain

[00:30:32] Norm: character in Master of None,

[00:30:34] Adam: and I love that character. He's weird, and he's not necessarily the nicest guy. He's kind of an asshole, but you also really like him.

[00:30:41] Will: Show's really good. It's

[00:30:42] Adam: an impressive, impressive mix. But goddamn, Francesca!

[00:30:45] Norm: I’m going to leave it at that. You can watch the show.

[00:30:49] Will: We’ll be back

[00:30:49] Norm: next week.

[00:30:50] Adam: Thanks, guys.

[00:30:51] Will: Bye, everybody. Have a

[00:30:51] Will: good one.

[00:30:52] Norm: Bye. I want to thank the other sponsor of this week's episode of Still Entitled, and that's Casper. The Casper is an obsessively engineered mattress at a shockingly fair price. Supportive memory foams create an award-winning sleep surface with just the right sink and just the right bounce. I sleep on my Casper and love it. You know who else loves bouncing on it? My dog Ripley, as well. She can't get enough of it. Try Casper for 100 nights, risk-free in your own home. If you don't love it, they'll pick it up and refund you everything. Casper understands the importance of truly sleeping on a mattress before you commit, especially considering you're going to spend a third of your life on it. Free shipping and returns in the U.S. and Canada. And for listeners of Still Entitled, you can get $ 50 toward any mattress purchase by going to www.casper.com/untitled and using the offer code Untitled. Terms and conditions apply. We'll see you next week.

[00:30:52] Unknown speaker: Thank you.
