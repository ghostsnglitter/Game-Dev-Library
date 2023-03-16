# Complete Guide For Solo Game Development

A complete guide that collects ideas, tools and resources for solo game development.

<a name="toc"></a>
## Table of Contents

> 1. [Introduction](#introduction)
>    - 1.1 [Purpose](#purpose)
>    - 1.2 [Important Notes](#important-notes)
> 2. [A Range of Responsibilities](#responsibilities)
>    - 2.1 [Design](#design)
>    - 2.2 [Engineering](#engineering)
>    - 2.3 [Art](#art)
>    - 2.4 [Writing](#writing)
>    - 2.5 [Management](#management)
> 3. [Getting Started](#getting-started)
>    - 3.1 [Finding Ideas](#finding-ideas)
>      - 3.1.1 [Brainstorming](#brainstorming)
>      - 3.1.2 [Inspiration](#inspiration)
>    - 3.2 [What to Learn (First)](#learn)
> 4. [Phases of Game Development](#phases)
>    - 4.1 [Concept Phase](#concept-phase)
>    - 4.2 [Pre-Production](#pre-production)
>    - 4.3 [Production](#production)
>    - 4.4 [Post-Release](#post-release)
> 5. [Distribution](#distribution)
> 6. [General Resources](#resources)

<a name="introduction"></a>
## 1. Introduction

With this guide, I'm trying to provide a flexible tool for getting started with solo game development. It explains in detail what it is necessary to produce and distribute a game from start to finish, helps you create your own workflow, and collects unique and unconventional resources for improving your creative process.

Specifically, this guide covers the different responsibilities you'll have to assume, as well as the different phases of game development, with specific information on the different goals, tools used, organisational strategies and learning materials - always with a focus on *solo* development.

<a name="purpose"></a>
### 1.1 Purpose

If you are an aspiring indie game developer of any skill level, this may serve as a blueprint or valuable reference. If you are a seasoned veteran, this may be little more than an interesting glimpse into my process for [`GHOSTS & GLITTER`](https://www.youtube.com/@ghostsnglitter) - although any input from experts is welcome!

As I'm still trying to develop this process, the guide may be updated regularly. In general, the main goals are always:

```
Maximize
- Flow
- Experimentation
- Quality of final result
```

```
Minimize
- Cost (time, money, effort)
- Risk
- Boring work with boring decisions
```

<a name="important-notes"></a>
### 1.2 Important Notes

Before we go any further, a few important notes up front:
- This guide covers game development in *Unity* (although this only really becomes important during production).
- I am writing this guide alongside the development of my first game, `SLINGSHOT`, which I will be using as an example throughout.

[[Back to Top]](#complete-guide-for-solo-game-development)

<a name="responsibilities"></a>
## 2. A Range of Responsibilities

Making and selling games requires expertise in a number of different fields. Studios usually have dedicated departments for different aspects of the game, whereas you as a solo creator will have to cover all of those areas yourself. This didn't really hit me until after i started out, but the challenges quickly become apparent - game design, level design, writing, programming, asset creation, project management, etc. all become your responsibilities. How do you manage that, especially when you are still learning the ropes in some or even all of those disciplines?

In short: start small, get an overview of all of the different types of tasks that await you, figure out what you are good at already and where you have gaps of knowledge. You want to get a *basic* level of understanding and competence in all of the important fields so that you don't unexpectedly hit a wall halfway through development. Building and releasing a *very* small and simple game is a good way to action-test your ability to go through the entire process. Under 3.1 [`Finding Ideas`](#finding-ideas), I'll provide different ideas and challenges that you can use for your very first game.

What follows is a first *overview* of the different departments a game studio might have: [`Design`](#design), [`Engineering`](#engineering), [`Art`](#art), [`Writing`](#writing), and [`Management`](#management). I will describe the role of each of those departments in the development process, and what that means for solo development (I will go into detail later on in the guide).

<a name="design"></a>
### 2.1 Design

A lot of the work the design department does happens early on, during the [`Concept Phase`](#concept-phase) and [`Pre-Production`](#pre-production), which is where the main design specifications are defined. However, where other members of the development team will often come and go, the designer(s) are usually a more persistent presence, monitoring the whole production to keep everything in line with the game's vision.[^1]

In detail, the design includes:

- Game Design
- Story Design
- Level Design

[^1]: cf. Kramarzewski, Adam, and Ennio De Nucci. 2018. *Practical Game Design*. Packt.

As a solo developer, you save the work of having to communicate your design to the various other departments, and you'll have ultimate creative freedom. However, the danger is that this can lead to lazyness in the design process and an "I'll think about it when i get there"-attitude, which can easily kill your project, even after you've put a lot of work into it.

<a name="engineering"></a>
### 2.2 Engineering

The game developers in the engineering department are responisble for the project's source code. They implement all of the features and mechanics described in the detailed design documentation, as well as all of the art assets.

When not coming from a programming background, this part of solo game development can seem particularly daunting. Personally, I found that learning how to code was a pretty enjoyable experience - due to the logical nature of it, the most basic concepts are pretty easy to understand, and you can build on them, bit-by-bit. That being said, it helps to bring some pre-existing experience or an understanding of those basic concepts with you. When starting out, it feels like a lot, but as soon as you develop this skill, you'll find how much can be achieved with simple (and *reusable*) code.

<a name="art"></a>
### 2.3 Art

The art department create all of the game's assets - 2D-art and UI-elements, 3D-models for objects, architecture, characters, as well as sound effects and music. This can take a lot of time and the work is usually distributed to many different artists, underlining the importance of starting into [`Production`](#production) with solid design documentation.

Depending on your background, this can be a massive challenge for creating your first game(s). Fortunately, there are plenty of helpful resources and strategies (covered in this guide) for reducing the workload, including the usage of third-party assets (an unbelievably important part of solo development that should not be looked down upon).

<a name="writing"></a>
### 2.4 Writing

If a game has a story, it usually has dedicated writers. Some studios turn all developers into writers for lots of individual storylines, others comission remote-working freelance writers. Usually, for small to mid-sized teams, there are only a few or just one writer (often the lead designer or narrative designer).[^1] Either way, the details of the story and the actual used texts come after the overall concept and narrative design has been specified in [`Pre-Production`](#pre-production).

Many solo developers gladly take on the writer role, as their games are often centered around a strong narrative ideas. However, it is important to consider what you're getting into when writing complex storylines.

<a name="management"></a>
### 2.5 Management

Last but not least, the management department covers everything regarding the project's work infrastructure, time schedule, and resources. Even though creating a feasable production plan with milestones and a realistic timeline is extremely difficult, it is very important - especially when working with a publisher.

Even seemingly simple games can fall into production-hell if you are working solo and not yet familiar with the process. A decent amount of preperation and project management can combat this and should be a part of any game development effort, even if nobody but you is watching.

[[Back to Top]](#complete-guide-for-solo-game-development)

<a name="getting-started"></a>
## 3. Getting Started

XXX

<a name="finding-ideas"></a>
### 3.1 Finding Ideas

A game idea is just that - an idea, like `2D game where you can perform a "slingshot" move by clicking and dragging the player character`. No specifics are required at this stage.

<a name="brainstorming"></a>
#### 3.1.1 Brainstorming

A spontaneous, unorganized brainstorming session is always a good way to capture your game idea(s) for the first time. Having it written down clears up space in your mind and helps you remember all of the details you though about. It can also be helpful for playing around with different versions of the same idea. A good web application for brainstorming is [`Kinopio`](https://kinopio.club/):

![Kinopio](img/Kinopio.png "An example board on Kinopio")

It serves as a virtual whiteboard and can help you visually organize and connect ideas. I mostly use it temporarily for mind-mapping and instead collect the most promising game ideas as notes in my [`OneNote`](https://www.onenote.com/?public=1) notebook (which I use for other stuff, too). This makes it easier to quickly write down ideas on my mobile phone.

<a name="inspiration"></a>
#### 3.1.2 Inspiration

Personally, I often can't stop my brain from constantly producing new game ideas, but sometimes I get stuck on something when trying to develop them further. The following approaches can help you find inspiration and getting unstuck:
- *Play games*: Start by playing games, from different genres and platforms, and including games you have already played. Analyze what you enjoy about them, what exactly draws you in. What about them is unique or makes you want to keep playing?
- *Identify a problem to solve*: Think about problems that you or others face in their daily lives. This could be anything from a lack of motivation to exercise to difficulty in learning a new language. Brainstorm ways that a game could help solve this problem.
- *Look for inspiration in other media*: Draw inspiration from books, movies, and TV shows. Consider how you could adapt a particular story or concept into a game.
- *Explore new technology*: Keep up-to-date with new technology and innovations in the gaming industry. Consider how new hardware, such as virtual reality headsets or haptic feedback controllers, could be used to create new gaming experiences.
- *Consider your own passions and interests*: Think about your own hobbies and interests. Consider how you could incorporate these into a game. For example, if you enjoy hiking, you could create a game that simulates a hiking adventure.
- *Combine different ideas*: Try combining different ideas to create something unique. For example, you could combine a puzzle game with a platformer or a survival game with a city-builder.
- *Collaborate with others*: Brainstorm with others and collaborate on game ideas. Consider working with people from different backgrounds and skill sets, such as artists or programmers.
- *Think about your target audience*: Consider who you want to make games for and what they would enjoy. Think about the age group, interests, and gaming experience of your target audience.

<a name="learn"></a>
### 3.2 What to Learn (First)

XXX

[[Back to Top]](#complete-guide-for-solo-game-development)

<a name="phases"></a>
## 4. Phases of Game Development

This is the main part of the guide. What follows are short descriptions of the different phases of game development, with the titles linking to the detailed articles.

<a name="concept-phase"></a>
### 4.1 [Concept Phase](Phases/1_ConceptPhase.md/#concept-phase)

In the Concept Phase, you will funnel your many ideas into a single, clearly defined Game Concept and critically evaluate it. If you are satisfied, you will make the commitment to move into Pre-Production.

<a name="pre-production"></a>
### 4.2 [Pre-Production](Phases/2_PreProduction.md/#pre-production)

During Pre-Production, you are going to hash out the most important design decisions. This is done through an iterative process of design and prototyping. You will also consider the resources that will be needed and draw up a plan for the realisation of your game - including an initial timeline - so that you can move on to Production.

<a name="production"></a>
### 4.3 [Production](Phases/3_Production.md/#production)

In Production, you will implement the specified design. This too is an interative process consisting of different stages, during which the design may need to be updated. The implementation is accompanied by consistent content preparation for public presentation of the game - with an increased commitment towards the release, which will mark the end of this phase.

<a name="post-release"></a>
### 4.4 [Post-Release](Phases/4_PostRelease.md/#post-release)

The Post-Release period is about updating and improving the game, engaging with the community, as well as potentially developing additional content.

[[Back to Top]](#complete-guide-for-solo-game-development)

<a name="distribution"></a>
## 5. Distribution

XXX

[[Back to Top]](#complete-guide-for-solo-game-development)

<a name="resources"></a>
## 6. General Resources

XXX

[[Back to Top]](#complete-guide-for-solo-game-development)