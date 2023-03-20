[[Back to Main Page]](../README.md/#production-guide-for-solo-game-development)

<a name="getting-started"></a>
# [2.] Getting Started

> *"Nobody tells this to people who are beginners, I wish someone told me. All of us who do creative work, we get into it because we have good taste. But there is this gap. For the first couple years you make stuff, it’s just not that good. It’s trying to be good, it has potential, but it’s not. But your taste, the thing that got you into the game, is still killer. And your taste is why your work disappoints you. A lot of people never get past this phase, they quit. Most people I know who do interesting, creative work went through years of this. We know our work doesn’t have this special thing that we want it to have. We all go through this. And if you are just starting out or you are still in this phase, you gotta know its normal and the most important thing you can do is do a lot of work. Put yourself on a deadline so that every week you will finish one story. It is only by going through a volume of work that you will close that gap, and your work will be as good as your ambitions. And I took longer to figure out how to do this than anyone I’ve ever met. It’s gonna take awhile. It’s normal to take awhile. You’ve just gotta fight your way through."* [^1]
>
> *- Ira Glass*

[^1]: Find an extended version of Ira Glass' famous quote on creativity in [this video](https://vimeo.com/85040589).

<a name="toc"></a>
## Table of Contents

> 1. [A Range of Responsibilities](#responsibilities)
>    - 1.1 [Design](#design)
>    - 1.2 [Engineering](#engineering)
>    - 1.3 [Art](#art)
>    - 1.4 [Writing](#writing)
>    - 1.5 [Management](#management)
> 2. [What to Learn (First)](#learn)

<a name="responsibilities"></a>
## 1. A Range of Responsibilities

Making and selling games requires expertise in a number of different fields. Studios usually have dedicated departments for different aspects of the game, whereas you as a solo creator will have to cover all of those areas yourself. This didn't really hit me until after i started out, but the challenges quickly become apparent - game design, level design, writing, programming, asset creation, project management, etc., you're responsible for all of it. How do you manage that, especially when you are still learning the ropes in some or even all of those disciplines?

In short: start small, get an overview of all of the different types of tasks that await you, figure out what you are good at already and where you have gaps of knowledge. You want to get a *basic* level of understanding and competence in all of the important fields so that you don't unexpectedly hit a wall halfway through development. Building and releasing a *very* small and simple game is a good way to action-test your ability to go through the entire process. In the article for the [`Concept Phase`](3_1_ConceptPhase.md) under [`Finding Ideas`](#finding-ideas), I'll provide different ideas and challenges that you can use for your very first game.

What follows is a first *overview* of the different departments a game studio might have: [`Design`](#design), [`Engineering`](#engineering), [`Art`](#art), [`Writing`](#writing), and [`Management`](#management). I will describe the role of each of those departments in the development process, as well as what that means for solo development (more details follow in the rest of the guide).

<a name="design"></a>
### 1.1 Design

A lot of the work the design department does happens early on, during the [`Concept Phase`](2_ConceptPhase.md) and [`Pre-Production`](3_PreProduction.md), which is where the main design of the game is specified. However, where other members of the development team will often come and go, the designer(s) are usually a more persistent presence, monitoring the whole production to keep everything in line with the game's vision.[^2]

[^2]: Adam Kramarzewski and Ennio De Nucci, *Practical Game Design* (Birmingham: Packt Publishing Ltd., 2018), 11 

In detail, the design includes:

- Game Design
- Story Design
- Level Design

As a solo developer, you save the work of having to communicate your design to the various other departments, and you'll have ultimate creative freedom. However, the danger is that this can lead to lazyness in the design process and an "I'll think about it when i get there"-attitude, which can easily kill your project, even after you've put a lot of work into it.

<a name="engineering"></a>
### 1.2 Engineering

The game developers in the engineering department are responisble for the project's source code. They implement all of the features and mechanics described in the detailed design documentation, as well as all of the art assets.

When not coming from a programming background, this part of solo game development can seem particularly daunting. Personally, I found that learning how to code was a pretty enjoyable experience - due to the logical nature of it, the most basic concepts are pretty easy to understand, and you just build on them, bit-by-bit (this guide will try to provide good learning material for starting out). That being said, it helps to bring some pre-existing experience or an understanding of those basic concepts with you. At first, it feels like a lot, but as soon as you develop this skill, you'll find how much can be achieved with simple (and *reusable*) code.

<a name="art"></a>
### 1.3 Art

The art department creates all of the game's assets - 2D-art and UI-elements, 3D-models for objects, environment, and characters, as well as sound effects and music. This can take a lot of time and the work is usually distributed to many different artists working in parallel throughout the entire development of the game, which only underlines the importance of starting [`Production`](3_3_Production.md) with a coherent vision and solid design documentation.

Depending on your background, this can be a massive challenge for creating your first game(s) solo. Fortunately, there are plenty of helpful resources and strategies (covered in this guide) for reducing the workload.

<a name="writing"></a>
### 1.4 Writing

If a game has a story, it usually has dedicated writers. Some studios enable all of the developers to become writers to get lots of individual storylines (and increase the investment in the project), while others comission remote-working freelance writers. Usually, for small to mid-sized teams, there are only a few or just one writer (often the lead designer or narrative designer). Either way, the details of the story and the actual used texts come *after* the overall concept and narrative design have been specified in [`Pre-Production`](3_2_PreProduction.md).

Many solo developers gladly take on the role of the writer, as their games are often centered around strong narrative ideas. However, it is important to consider what you're getting into before writing complex storylines (for example, dialogue systems can be quite complicated to implement).

<a name="management"></a>
### 1.5 Management

Last but not least, the management department covers everything regarding the project's work infrastructure, time schedule, and resources. Even though creating a feasable production plan with *realistic* milestones and due dates is difficult, it is very important - especially when working with a publisher.

When working solo, even seemingly simple games can fall into production-hell if you are not yet familiar with the process yet. A decent amount of preperation and project management can combat this and should be a part of any game development effort, even if nobody but you is watching.

[[Back to Top]](#getting-started)

<a name="learn"></a>
## 2. What to Learn (First)

So, there you go - it's a lot. And a common question to ask yourself at this point is, what should I learn *first*? I could rank the different aspects of game development described above in order of importance, but honestly, they're all equally important. You can find *"Roadmaps"* online that cover all relevant topics that relate to a particular skill, put into a reasonable chronological order. While these can be valuable resources, there is no "correct" order.

Taking all of that into account, I think the most effective way to *actually get you started* on game development and making stuff is to *aggressively* break down the challenges and obstacles you face into the smallest, digestable chunks. The goal is *not to lose momentum*. Here's an example:

1. I want to make a dense and atmospheric first-person 3D-game with vivid characters and deep emotional storytelling.
   - Something slows the momentum: I have never made a game before and don't know where to start. I have a good idea of the story i want to tell, but don't know a lot about designing game mechanics, or programming, etc.
   - Rethinking: I should first get familiar with game development operations by making a smaller project so I can learn the skills necessary for realizing my ideas and getting an understanding of the possibilities and limitations.
2. I want to make a small but fun arcade-like 2D-game playable in the browser.
   - Something slows the momentum: Even with this small project, I am struggling to implement the mechanics, because I am still new to programming. Specifically, I can't figure out how to draw certain UI elements.
   - Rethinking: I should isolate the very specific programming challenge I am facing, and create another, *even smaller* project, just for this challenge.
3. I want to make a small playable test for creating UI elements. While I figure it out, I might find a way to turn this into a tiny minigame that I can release afterwards.
   - ...

Keep in mind that these individual projects don't have to always result in a playable video game. If you want to improve your game design skills, challenge yourself to create only the design for a game - once it is done, save/publish it as a neat documentation or showcase, and then just *move on to the next thing*.

The idea is to be able to look at *results* as soon as humanly possible. When starting out, it will feel unbelievably rewarding to be able to upload a finished project on Itch.io (or just to *have* a finished build) - no matter how tiny the scope of the project is. It also builds a lot of confidence to be able to look back on your catalog of increasingly ambitious projects.

[[Back to Top]](#getting-started)

---

[[Back to Main Page]](../README.md/#getting-started)