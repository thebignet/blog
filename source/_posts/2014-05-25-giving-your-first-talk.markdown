---
layout: post
title: "Giving your first talk"
date: 2014-05-25 17:26:00 +0200
comments: true
categories: speaking
---

Last thursday, I gave my first tech talk.  My company enfavors its employees to share their knowledge through presentations.  The idea had been in my mind for a long time.  I always admired talkers.  Not because of their charisma, but more because they have knowledge and the spend time preparing and have enough confidence to speak in front of their audience.

Preparation
-----------
I had been preparing my talk for months.  I knew I could get a conference room to present it in.  I needed a time slot too.  Other presenters where ahead of me, but I didn't mind as long as it happened.  I also had to choose wether it would be a lunch presentation or an afterwork one.  I went for the former as it drags more people to it, even though the downside of it that people eat during your talk.

As we were getting closer to the big day, invitations were sent, a Google event was made and I could estimate how many people would come.  It was all very exciting.

But before I could present, I had to make the slides.  I had a subject already.  I'd been a big fan of AngularJS and been using it in a couple of projects and got loads of great feedback from it.  My company gave me a Powerpoint template to start with ... yuck !  The graphics in it dated from the 20th century !  With all these funky slides on the web, I had to find something worth it.  Of course Keynote is good too, has great transitions, and it can even record your presentation, but that was probably too easy and not geeky enough.  As I was to present live web page demos, so a web based presentation it would be.  After searching around, I decided to use [reveal.js](http://lab.hakim.se/reveal-js).  Even though it is open-source, [slides.com](http://slides.com) hosts presentations using it.

So I prepared my slides, organized them, chopped down some infos, so as not to drown my attendees in words.  Procrastination got the better of me and the last 10% of polish were obsessing me.  Fortunately, I had my wife and [@madbrain](https://github.com/madbrain) to reread the slides.  I practiced several times throughout the presentation.  Trust me, this is mandatory.  You might think "I know this, I'll have no problem talking about it".  Believe me, once you start with no audience, you realize a bit of practice is necessary.  Imagine with the audience and pressure.

Giving the talk
---------------
So the big day came.  After some problems with the overhead projector, I got things started.  I have to say it went better than I expected.  The audience was receptive.  I had a survey in the first slides to get interaction and sometimes polled the audience.  The talk was fine all in all.

The demos however, didn't work.  I could not get them to work.  At first I thought that the lack of internet was to blame.  But I had prepared so that the actual demo would reference a local copy of AngularJS while the slide showed that it references a CDN.  I had cloned the repository on my laptop, but in order to get a local copy of AngularJS, I had to run `bower install` for bower dependencies to be retrieved.

I didn't resolve this during the presentation in order to get things going.  I now commited those dependencies to my repo in order to avoid that and have a working copy right after clone.  This can lead to a divergence between the bower.json and the actual dependencies on the repository, but I guess it's a lesser evil.

I really have to hand it to Zach Holman for his great advice on [speaking.io](http://speaking.io).  It really helped me concentrate on what's important for a talk and what's not.

Anyway, here's the [talk](http://thebignet.github.io/talk-angularjs-introduction), it's in French, though.