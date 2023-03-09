[[Back to Main Page]](README.md/#production-guide-for-solo-game-development)

# Pre-Production

During Pre-Production, you are going to hash out the most important design decisions. This is done through an iterative process of design and prototyping. You will also consider the resources that will be needed and draw up a plan for the realisation of your game - including an initial timeline - so that you can move on to Production.

<a name="toc"></a>
## Table of Contents

> 1. [Setting Up A Backlog](#backlog)
> 2. [Prototyping](#prototyping)
> 3. [Creating A Game Design Document](#game-design-document)
>    - 3.1 [Structure](#structure)
>    - 3.2 [Elements](#elements)

<a name="backlog"></a>
## 1. Setting Up A Backlog

A central element of the development of your game is the backlog. It serves as an important project management framework, hosting all of the design documents, all tasks that need to get done, as well as a project timeline with milestones and due dates.

Because you are about to create important design documents, it makes sense to set up the backlog early. To begin with, you really only need to *create a dedicated space for your game project, with the ability to add documents and tasks as you go along* (you should start by integrating the Game Concept designed in the previous phase).

There are different project management applications that can be used for this, but my personal pick is [ClickUp](https://www.clickup.com/):

![Image](Images/sc_ClickUp.png)

It is extremely feature-rich and customizable (even the free version). This might make it a bit too much for your first project though, so feel free to use alternatives for your own backlog (i've heard about [Nuclino](https://nuclino.com/), [Milanote](https://milanote.com/) and others).

The specifics of the backlog structure can vary drastically depending on what type of game you are making. Still, if you are going with ClickUp, [here](https://app.clickup.com/template/project/t-90040105296/d6e92afd78aea9a) you can find a template for a space dedicated to the `SLINGSHOT` project used as an example earlier.

<a name="prototyping"></a>
## 2. Prototyping

As soon as you have your Game Concept, you can begin prototyping different elements of your game, like an important gameplay mechanic or the art-style.

Prototyping your game means creating a working model in order to test its feasibility, functionality, and fun factor. It's an essential step in game development that allows you to experiment with different mechanics, gameplay systems, and visual styles before committing to a full-scale production. It's an iterative process that can happen in parallel with [Creating A Game Design Document](#game-design-document).

Consider the following tipps when creating a prototype for your game:
- Stay *focused* on the specific thing you want to test. If it is a gameplay mechanic, use primitive shapes like circles and triangles to represent actors and objects.
- Create a *paper prototype* as a low-cost way to quickly iterate on game mechanics and gameplay systems.
- Do *playtests* and use feedback to refine the core mechanics and gameplay systems.

<a name="game-design-document"></a>
## 3. Creating A Game Design Document

What follows is the creation of the most important document of this phase, the Game Design Document (GDD). It will serve as a blueprint for the entire project and as a plan for the production phase.

This document may be created in a process of iteration, [prototyping](#prototyping) core gameplay mechanics and ideas before integrating them into the GDD. Afterwards, you should have a comprehensive document with all the design specifications neccessary to realize the game from start to finish - even though it will likely be updated multiple times during production.

First i will provide a - quite expansive - *example* [structure](#structure) for the document. While smaller games will not require all of the sections listed, it is helpful to get an overview of what kinds of things *could* be relevant when designing your game. Below the structure you will find more information on specific [elements](#elements).

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
   - 2.2 [Design Pillars](#elements-design-pillars)
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
   - 6.5 Entities
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
    - 12.1 Milestones
    - 12.2 Production Timeline
    - 12.3 Budget And Resources Required
    - 12.4 Tools And Software Used
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

<a name="elements-design-pillars"></a>
#### Game Design Pillars
List 3-5 key design pillars describing the gameplay, for example:

1. Fast: The action should start right away. Player movement should feel quick and agile. When players die, they should be able to start over immediately.
2. Emergent: The game should have very simple player actions and objectives, but create increasingly complex situations through the interaction of various game systems.
3. Learning through playing: The player should learn how the game's ecosystem works through trial and error. In the early stages of the game, dying should feel like learning and inspire a desire to try again, while later in the game the thrill comes from seeing how far you can push your highscore.

<a name="elements-design-pillars"></a>
#### Narrative Pillars
Repeat the same thing for the game's narrative.

<a name="elements-look-and-feel"></a>
#### Look And Feel
Describe the game's aesthetic and game feel with precise vocabulary, for example:

1. Retro: The game should have a low-res, retro look with abstract visuals.
2. Surreal: The ecosystem of this game should feel very strange and dream-like, and the visuals of the game overall should reflect that.
3. Squishy: The game should have a satisfying and organic game feel with lots of squishy animations.

<a name="elements-walkthrough"></a>
#### Walkthrough
Write a short second-preson walkthrough of an example play session. This should not be too long, but provides a good overview of the chronological *experience* of playing the game, before isolating and categorizing the individual game elements. 

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
List and describe important narrative mechanics, like a dialogue system, etc.

<a name="elements-systems"></a>
#### Systems
List and describe important systems (that don't fall into the previous categories), like scoring systems, upgrade systems, etc.

<a name="elements-levels-and-objectives"></a>
#### Levels And Objectives
Provide and overview of the different levels, their objectives, and list level-specific gameplay mechanics. This is only an outline, the details for individual levels should be in a seperate document created during Production.