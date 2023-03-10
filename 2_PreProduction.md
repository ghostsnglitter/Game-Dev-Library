[[Back to Main Page]](README.md/#production-guide-for-solo-game-development)

capitalize I

# Pre-Production

During Pre-Production, you are going to hash out the most important design decisions. This is done through an iterative process of design and prototyping. You will also consider the resources that will be needed and draw up a plan for the realisation of your game - including an initial timeline - so that you can move on to Production.

<a name="toc"></a>
## Table of Contents

> 1. [Setting Up A Backlog](#backlog)
> 2. [Creating A Game Design Document](#game-design-document)
>    - 2.1 [Structure](#structure)
>    - 2.2 [Elements](#elements)
> 3. [Iteration](#iteration)
>    - 3.1 [Process](#process)
>    - 3.2 [Prototyping](#prototyping)

<a name="backlog"></a>
## 1. Setting Up A Backlog

A central element of the development of your game is the backlog. It serves as an important project management framework, hosting all of the design documents, all tasks that need to get done, as well as a project timeline with milestones and due dates.

Because you are about to create important design documents, it makes sense to set up the backlog early. To begin with, you really only need to *create a dedicated space for your game project, with the ability to add documents and tasks as you go along* (you should start by integrating the Game Concept designed in the previous phase).

There are different project management applications that can be used for this, but my personal pick is [ClickUp](https://www.clickup.com/):

![Image](Images/ClickUp.png)

It is extremely feature-rich and customizable (even the free version). This might make it a bit too much for your first project though, so feel free to use alternatives for your own backlog (i've heard about [Nuclino](https://nuclino.com/), [Milanote](https://milanote.com/) and others).

The specifics of the backlog structure can vary drastically depending on what type of game you are making. Still, if you are going with ClickUp, [here](https://app.clickup.com/template/project/t-90040105296/d6e92afd78aea9a) you can find a template for a space dedicated to the `SLINGSHOT` project used as an example earlier.

<a name="game-design-document"></a>
## 3. Creating A Game Design Document

What follows is the creation of the most important document of this phase, the Game Design Document (GDD). It will serve as a blueprint for the entire project and as a plan for the production phase.

This document may be created in a process of iteration, [prototyping](#prototyping) core gameplay mechanics and ideas before integrating them into the GDD. Afterwards, you should have a comprehensive document with all of the design specifications neccessary to realize the game from start to finish - even though it will likely be updated multiple times during production.

What follows is a - quite expansive - *example* structure for the document. While smaller games will not require all of the sections listed, it is helpful to get an overview of what kinds of things *could* be relevant when designing your game. Below the structure you will find detailed information on specific (those that aren't self-explanatory).

But before that, here are some general notes and ideas on the creation of the Game Design Document:
- As explained in [Setting Up A Backlog](#backlog), you should integrate the GDD into your backlog. Depending on the project management tool you are using, this can enable you to reference tasks, other documents, etc. and vice versa.
- Even with a comprehensive structure like the one below, the individual elements should be kept short and to-the-point. You can use bullet points where it makes sense.
- Include reference images and diagrams - especially for game systems, it can help to use diagrams visualizing processes. A nice and simple web-tool for this is [draw.io](https://app.diagrams.net/).

<a name="structure"></a>
### 3.1 Structure

1. [Introduction](#elements-introduction)
   - 1.1 Overview
   - 1.2 Purpose
   - 1.3 Audience
   - 1.4 Scope
   - 1.5 References
2. Game Overview
   - 2.1 [Game Concept](#elements-game-concept)
   - 2.2 [Gameplay Pillars](#elements-gameplay-pillars)
   - 2.3 [Narrative Pillars](#elements-narrative-pillars)
   - 2.4 [Look And Feel](#elements-look-and-feel)
3. [Walkthrough](#elements-walkthrough)
4. Game World
   - 4.1 Overview
   - 4.2 Lore
   - 4.3 Locations
5. [Story](#elements-story)
   - 5.1 Overview
   - 5.2 Characters
   - 5.3 Plot
6. Gameplay Mechanics
   - 6.1 [Player Actions](#elements-player-actions)
   - 6.2 [Environmental Interactions](#elements-environmental-interactions)
   - 6.3 [Narrative Mechanics](#elements-narrative-mechanics)
   - 6.4 [Systems](#elements-systems)
   - 6.5 [Enemies](#elements-enemies)
   - 6.6 Upgrades
7. [Levels And Objectives](#elements-levels-and-objectives)
   - 7.1 Overview
   - 7.2 Objectives
   - 7.3 Level-Specific Gameplay Mechanics
8. User Interface And HUD
   - 8.1 Menu Design
   - 8.2 In-Game UI Elements
   - 8.3 HUD design
9. Art Style And Graphics
   - 9.1 Art Style
   - 9.2 Character Design
   - 9.3 Environmental Design
   - 9.4 Special Effects And Particle Systems
10. Sound Design And Music
    - 10.1 Sound Effects
    - 10.2 Background Music And Score
    - 10.3 Voice acting
11. Multiplayer And Online Features
    - 11.1 Multiplayer Modes
    - 11.2 Online Features And Connectivity
    - 11.3 Matchmaking And Ranking Systems
12. Development And Production
    - 12.1 [Milestones](#elements-milestones)
    - 12.2 [Production Timeline](#elements-timeline)
    - 12.3 [Budget And Resources Required](#elements-resources)
    - 12.4 [Tools And Software Used](#elements-tools)
12. Conclusion
    - 12.1 Summary
    - 12.2 Future Plans
    - 12.3 Appendices

The structure of a GDD can and will change from project to project. Not every game project will need all of the elements listed above. To provide a concrete example, you can find the GDD for the `SLINGSHOT` project [here](https://share-docs.clickup.com/9004010474/d/h/8cawjza-41/20c1c286a990252). You will notice that several points have been altered or are left out to fit the scope and genre of the game.

<a name="elements"></a>
### 3.2 Elements

<a name="elements-introduction"></a>
#### Introduction
Document-related info.

<a name="elements-game-concept"></a>
#### Game Concept
Link to previously created Game Concept.

<a name="elements-gameplay-pillars"></a>
#### Gameplay Pillars
List 3-5 key game design pillars describing the gameplay.[^1] These should be simple adjectives, for example:

[^1]: This approach comes from Chris Gardiner's GDC talk ["Sunless Skies: A Narrative Postmortem"](https://youtu.be/_sslFBVy5Lc)

1. Fast: The action should start right away. Player movement should feel quick and agile. When players die, they should be able to start over immediately.
2. Emergent: The game should have very simple player actions and objectives, but create increasingly complex situations through the interaction of various game systems.
3. Challenging: It should be a real challenge to stay alive for a long time, creating an intense experience.
4. Rewarding: Learning how the game's ecosystem works and using this knowledge to your advantage should feel extremely rewarding and addicting.

<a name="elements-design-pillars"></a>
#### Narrative Pillars
List 3-5 key narrative design pillars describing the mood, atmosphere, and overall direction of the game's narrative.[^1] These can be sentences or quotes conveying a particular tone. An example from `Sunless Skies`:

1. Stake your Claim
2. Who are you, In the Dark?
3. Conceal your Hand
4. Mind your Manners
5. Nothing is Sacred

<a name="elements-look-and-feel"></a>
#### Look And Feel
Describe the game's aesthetic and game feel with precise vocabulary, for example:

1. Retro: The game should have a low-res, retro look with abstract visuals.
2. Surreal: The ecosystem of this game should feel very strange and dream-like, and the visuals of the game overall should reflect that.
3. Squishy: The game should have a satisfying and organic game feel with lots of squishy animations.

<a name="elements-walkthrough"></a>
#### Walkthrough
Write a short second-preson walkthrough of an example play session. This should not be too long, but provides a good overview of the chronological *experience* of playing the game, without isolating and categorizing the individual game elements. 

<a name="elements-story"></a>
#### Story
Provide a first outline of the story. Key characters and plot points - from start to finish - should be worked out now, during Pre-Production (of course things can still change later on). Detailed writing will happen in the Production phase.

<a name="elements-player-actions"></a>
#### Player Actions
List and describe the core player actions and how they work specifically, including movement, combat actions, etc.

<a name="elements-environmental-interactions"></a>
#### Environmental Interactions
List and describe important environmental interactions, like opening doors, etc.

<a name="elements-narrative-mechanics"></a>
#### Narrative Mechanics
List and describe important narrative mechanics, like dialogue systems, etc.

<a name="elements-systems"></a>
#### Systems
List and describe important systems (that don't fall into the previous categories), like scoring systems, upgrade systems, etc.

<a name="elements-enemies"></a>
#### Enemies
List all enemy types and their features here (this is only an example, depending on the game you might add `Classes` or `Creatures`, etc. under Gameplay Mechanics).

<a name="elements-levels-and-objectives"></a>
#### Levels And Objectives
Provide and overview of the different levels, their objectives, and list level-specific gameplay mechanics. This is only an outline, the details for individual levels should be found in a seperate document created during Production.

<a name="elements-milestones"></a>
#### Milestones
Production milestones may include `First Playable` (first build to give a proper idea of the gameplay, stuff like menus may still be missing), `Vertical Slice` (a short but fully playable sample of the final game that can be used to pitch to studios or investors), `Pre-Alpha` (the majority of the game's content is implemented, enabling you to initiate playtests and make decisions about what needs to get cut or improved), `Alpha` (a feature-complete build of the game, which may still lack certain elements, like art assets, and needs to be further polished and cleansed of bugs, etc.), `Beta` (a complete game build that now needs to be optimized above all else), `Gold Master` (the final game build, ready to be released to the public).[^2]

[^2]: Source: https://www.cgspectrum.com/blog/game-development-process

<a name="elements-timeline"></a>
#### Production Timeline
A rough timeline for Production, giving the individual milestones due dates.

<a name="elements-resources"></a>
#### Budget And Resources Required
An overview of the budget planned for Production, as well as the resources needed (assets for example).

<a name="elements-tools"></a>
#### Tools And Software Used
An overview of all tools used for the development of this game. This should include the specific editor version of Unity (or whatever game endinge is used), the chosen source control software, 3D-modeling software, etc.

<a name="iteration"></a>
## 3. Iteration

The creation of the first draft of the GDD initiates a process of iteration with the goal of properly testing and refining the design.

<a name="process"></a>
### 3.1 Process

XXX

<a name="prototyping"></a>
### 3.2 prototyping

As soon as you have your Game Concept, you can begin prototyping different elements of your game, like an important gameplay mechanic or the art-style.

Prototyping your game means creating a working model in order to test its feasibility, functionality, and fun factor. It's an essential step in game development that allows you to experiment with different mechanics, gameplay systems, and visual styles before committing to a full-scale production. It's an iterative process that can happen in parallel with [Creating A Game Design Document](#game-design-document).

Consider the following tips when creating a prototype for your game:
- Stay *focused* on the specific thing you want to test. If it is a gameplay mechanic, use primitive shapes like circles and triangles to represent actors and objects.
- Create a *paper prototype* as a low-cost way to quickly iterate on game mechanics and gameplay systems.
- Do *playtests* and use feedback to refine the core mechanics and gameplay systems.