## Build Open Source software, by Eric Raymond

> *The tribe of hackers, after decades spent in obscurity struggling against hard technical problems and the far greater weight of mainstream indifference and dismissal, has recently begun to come into its own. They built the Internet; they built Unix; they built the World Wide Web; they're building Linux and open-source soft-ware today; and, following the great Internet explosion of the mid-1990s, the rest of the world is finally figuring out that it should have been paying more attention to them all along.*
>
> *The hacker culture and its successes pose by example some fundamental questions about human motivation, the organization of work, the future of professionalism, and the shape of the firm - and about how all of these things will change and evolve in the information-rich post-scarcity economies of the 21st century and beyond. The hacker culture also, arguably, prefigures some profound changes in the way humans will relate to and reshape their economic surroundings. This should make what we know about the hacker culture of interest to anyone else who will have to live and work in the future.*  
> Preface of 'The Cathedral and the Bazaar', Eric S. Raymond

## Introduction

Eric Raymond influenced widely the software industry with the essay *'The Cathedral and the Bazaar'* by being the spark who will impulse the open source movement. In this book, the author opposes two ways to produce software, the classic approach of the Cathedral where software development is done in a centralized & closed environment, and the bazaar style, a decentralized and collaborative production method amplified through the Internet.

The idea of this book came by a combination of circumstance. Eric Raymond was a software developer and was involved in free software. With decades of experience, before starting his writings, he thought he knew how a software should be produce. They were some theories about it like *'The Mythical Man-Month'* from Frederick Brooks predicting that *'complexity and communication costs of a project rise  with the  square of the number of developers'*. For Eric Raymond, big software projects would necessarily need centralization to be done, like it is in proprietary and free software. Linux appear and challenged these models.

Seeing this gap between theory and practice, he tried to formalize some principles inspired by the development process of Linux to apply it to one of his own project : `fetchmail`.
With a successful experimentation, he decided to share his theory with this essay. He wrote 19 lessons about how to produce collaboratively a software.

## Lessons of *'The Cathedral and the Bazaar'*

1. Every good work of software starts by scratching a developer's personal itch.
2. Good programmers know what to write. Great ones know what to rewrite (and reuse)
3. "Plan to throw one away; you will, anyhow."
4. If you have the right attitude, interesting problems will find you.
5. When you lose interest in a program, your last duty to it is to hand it off to a competent successor.
6. Treating your users as co-developers is your least-hassle route to rapid code improvement and effective debugging.
7. Release early. Release often. And listen to your customers.
8. Given a large enough beta-tester and co-developer base, almost every problem will be characterized quickly and the fix obvious to someone.
9. Smart data structures and dumb code works a lot better than the other way around
10. If you treat your beta-testers as if they're your most valuable resource, they will respond by becoming your most valuable resource.
11. The next best thing to having good ideas is recognizing good ideas from your users. Sometimes the latter is better.
12. Often, the most striking and innovative solutions come from realizing that your concept of the problem was wrong.
13. "Perfection (in design) is achieved not when there is nothing more to add, but rather when there is nothing more to take away."
14. Any tool should be useful in the expected way,but a truly great tool lends itself to uses you never expected.
15. When writing gateway software of any kind, take pains to disturb the data stream as little as possible - and never throw away information unless the recipient forces you to!
16. When your language is nowhere near Turing-complete, syntactic sugar can be your friend.
17. A security system is only as secure as its secret. Beware of pseudo-secrets.
18. To solve an interesting problem, start by finding a problem that is interesting to you.
19. Provided the development coordinator has a communications medium at least as good as the Internet, and knows how to lead without coercion, many heads are inevitably better than one.


## Collaborative software production

The idea behind open source is not only to share the source code, it was already the case with free software, but to open the development to external contributor to collaborate actively to produce a software.
There is a porous barrier between user and developer, we can speak about *prosumer*. Users can have technical skills to report bugs, to suggest fixes or improvement, on which it is possible to rely to build a project. At the Internet scale, everyone become a potential co-worker, a peer.

Community around a software will be a *community of interest*. Starting by *'personal itch'*, the problem may be common to multiple people. With this situation, the co-construction of a solution becomes interesting for those different actors, a project will need to attract those people. To incite contribution to the project, it's not possible to give direct order, the goal would be to convince people to participate. According to the Russian anarchist *Pyotr Alexeyvich Kropotkin*: *'[he] began  to  appreciate  the difference  between  acting  on  the  principle  of  command and  discipline  and  acting  on  the  principle  of  common understanding'*.

From a certain scale, a project will get huge benefit from an important pool of talent. It will experiment specific characteristics of collective intelligence. For example with an important community, bugs would be spot faster, *'somebody finds the problem and somebody else understands it'* given by the famous **Linus's Law**: *'given enough eyeballs, all bugs are shallow'*. The contributor being self selected by their interest to the project, the [Delphi effect](https://fr.wikipedia.org/wiki/M%C3%A9thode_de_Delphes) may occur with decision done with a panel of 'expert'.

## Open Source development strategy

To start an open source project, the author explain it may be difficult to originate a project in the bazaar style. In order to attract the interest of others you would need to start with a usable program, it can be a rudimentary but promising proof of concept. It can be buggy, incomplete, poorly documented, but people will need something to start with. Two lessons are *'release early, release often'* and *'plan to throw one away; you will, anyhow'* sharing this idea of **fast prototyping** and **evolution by iteration**.

The quality and the complexity of the code will influence the ability to external contributor to participate. It's not restricted to open source, but to enable other developers to use a code base it will need to be readable and understandable. That's also the idea behind *'smart data structures and dumb code works a lot better than the other way around'*, and it will even help the maintainer during debugging sessions! When a project become important, people will more read the code than write it, the ease with which they can do so will impact their level of contribution.

Collaboration is done through the Internet medium, communications tools will be critical to build an open source project. New possibilities are emerging because IT offers new ways to interact massively, it's exploding traditional method where coordination of the project relied more on individuals. One part of the work to build a successful project would be to have a good **management of information**. To allow anyone to find the information they need as simply and clearly as possible, give way to discuss for the community, explaining way to contribute and so on. A wide variety of more or less efficient tools are usable, with a perpetual evolution when needs, mean and/or scale change.

## Open source advantage over closed source

The benefits are multiple for an open source project compared to a closed project, they can vary and generalities are impossible. In the book, Raymond speak about technical advantage, an open source project may be superior by its efficiency, robustness and security. By improvement coming from a lot of actors, by stressing the program and finding bugs the quality may be superior. Bug resolution may be faster with distributed debugging, multiple person searching together, with the ability to have one person who will find the bug and another one able to fix it, which is almost impossible for closed source software.

> *No closed-source developer can match the pool of talent the Linux community can bring to bear on a problem. Very few could afford even to hire the more than 200 (1999: 600, 2000: 800) people who have contributed to fetchmail!*  
'The cathedral and the Bazaar'

Open Source allow innovation to come from outside. External contributors may bring essential changes to a software, regarding lessons 11 *'The next best thing to having good ideas is recognizing good ideas from your users.'*. With the availability of the source code, innovation can also be faster than closed source environment, people can adapt tools and share their solution who may solve someone problem. *'It is not only debugging that is parallelizable; development and (to a perhaps surprising extent) exploration of design space is, too.'*. Open source benefits from [open innovation](https://en.wikipedia.org/wiki/Open_innovation)!

> *Perhaps in the end the open-source culture will triumph not because cooperation is morally right or software 'hoarding' is morally wrong (assuming you believe the latter, which neither Linus nor I do), but simply because the closed-source world cannot win an evolutionary arms race with open-source communities that can put orders of magnitude more skilled time into a problem.*  
Conclusion of 'The Cathedral and the Bazaar'

*Author: AbcSxyZ  
Comment section: https://github.com/AbcSxyZ/Open-Source-Education/discussions/3  
Find link to the book in [Open Source Education resources](/awesome-open-source-resources.md).*
