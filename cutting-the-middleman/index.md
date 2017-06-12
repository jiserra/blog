---
title: Cutting the middleman
excerpt: How I got from just building prototypes to actually build applications.
publishDate: 2017-06-07
---

Back when I started designing interfaces for mobile applications, there weren’t any real prototyping tools; luckily that isn’t the case anymore.

Why do we need prototypes? The short answer is that testing an application early in the design process requires a user to experiment with it. Also, it is very helpful for the developers to see how something is supposed to behave from the very beginning.

Up until a few years ago, the closest thing to modern prototyping was to export the different screens to PNG files and make an HTML page with links connecting them. Needless to say, this proto-prototyping method (pun intended) served the purpose, but it was clear that more tools would be badly needed to keep up with a rapidly-evolving profession.

After a while, the tools began to appear. The first modern examples coming to my mind are the old versions of Flinto and InVision, plus the intricate Origami (originally born as a plugin for an _really_ old Mac tool). I must confess that when I started using these tools, I often found myself overrun by feelings of frustration: the limitations presented by the web-based ones and the complexities attached to Origami did a great job in putting me between a rock and hard place. 

However, it didn’t take long until I came across a new product: Framer. I still consider the appearance of Framer as a lucky strike: in a snap of fingers, my worries were mostly gone. 

Framer allowed me to make (almost) any animation and interaction I wanted. In a reality where the newly launched iOS 7 had left skeuomorphism behind to make room for micro-interactions, this was a must.

There are, of course, some limitations. The iOS developer (or Android, since its adoption of Material Design) always needs to reinterpret the prototype - and there is a clear disadvantage in this flow: the quality of the animation/interaction depends on the engineer’s ability to **correctly interpret the movements meticulously created by the designer**. Several animations libraries were built (Pop by Facebook was one of the first ones) to help with this issue, but it wasn't enough.

In my case, the challenge was double: first of all, I was bound to help the engineers develop apps at work. In addition, I also needed to develop stuff by myself. Until this point, I usually owned 70% of the design process, including wireframes, visual design, UX and prototypes. Yet, I wanted to take things further, to develop a whole app by myself.

## Hitting the wall

I don’t know how usual it is for designers to get deep into coding. I mean - there are all kinds of designers, and while some embrace coding, others react like a cornered cat whenever they come across a line of code. In my case, I’ve always been into coding. It’s something I enjoyed since I was a little kid: I started QBasic in my 16MHz 386 PC, and when 2000's arrived, I started doing stuff in PHP like a maniac.

Even though logic and languages came naturally to me, Objective-C and Java were absolutely indigestible - and still are, but not for lack of trying: I engaged several times but failed miserably each one of them. And, of course, there was Cordova: the webview app is cherished by some, but it’s never worked as a solution for me. If you want a native app capable of 60fps scrolling and native behavior without the restrictions of a webview platform, follow my advice and forget Cordova for good.

When I was just about to convince myself that I was never going to build a mobile application, I came across Fuse and my mind —once again— was blown. Suddenly I was able to make something the way I wanted, using a language I could easily understand. Sure, those were the times of the early, ‘rough around the edges’ beta versions, but from a designer’s perspective it all felt fantastic.

In the beginnings, I was amazed by how easy it was to create extremely detailed micro-interactions. Also —and because the UX language is very declarative on the visual styles— I could create complex components and seamlessly use them in the app. Furthermore, the use of data was pretty easy: thanks to fetch I could use any JSON API and display the data just the way I wanted. To conclude, Fuse featured a great online community, keen to solve doubts on Slack in no time.

## A fresh start

Soon after my romance with Fuse began, I moved to New York City, where I still live. One of the first things I wanted to do after settling in was to connect with other Fuse users living here, but the seemingly easy task soon proved a little more complicated that I thought: there weren’t any meet ups around the Fuse topic. So I embarked in creating the first NYC Fuse Meetup to learn about the local community of developers, and the response was good: the attendants showed surprise about the possibilities offered by Fuse, and I got to organize an equally successful second gathering (stay tuned for the next one!).

What did I learn from this journey? Well, first of all, that Framer is an excellent product that gets better in each new release, but…it still only is a prototyping tool. Surely, we can connect external data sources and make very complex flows, but we can't publish that in a store. 
 
However, those looking for the real deal —taking control of the entire mobile dev process —might want to give Fuse a spin. It has given me the chance to get things going and to see actual working results, so if you have any doubts or questions, just drop me a line and we’ll talk about it!

### TODO
- Put links on things