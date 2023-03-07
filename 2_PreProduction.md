[[Back to Main Page]](README.md/#production-guide-for-solo-game-development)

# Pre-Production

During Pre-Production, you are going to hash out the most important design decisions. This is done through an iterative process of design and prototyping. You will also consider the resources that will be needed and draw up a plan for the realisation of your game - including an initial timeline - so that you can move on to Production.

<a name="toc"></a>
## Table of Contents

> 1. [Setting Up A Backlog](#backlog)
> 2. [Creating A Game Design Document](#game-design-document)
>    - 2.1 [Structure](#structure)
>    - 2.2 [Modular Approach](#modular-approach)
>    - 2.3 [Iteration](#iteration)

<a name="backlog"></a>
## 1. Setting Up A Backlog

A central element of the development of your game is the backlog. It serves as a neccessary project management framework, hosting all of the important design documents, all tasks that need to get done, as well as a project timeline with milestones and due dates.

Because you are about to create important design documents, it makes sense to set up the backlog early. To begin with, you really only need to *create a dedicated space for your game project, with the ability to add documents and tasks as you go along* (you should start by integrating the Game Concept designed in the previous phase).

There are different project management applications that can be used for this, but my personal pick is [ClickUp](https://www.clickup.com/):

![Image](Images/sc_ClickUp.png)

It is extremely feature-rich and customizable (even the free version). This might make it a bit too much for your first project though, so feel free to use alternatives for your own backlog (i've heard about [Nuclino](https://nuclino.com/), [Milanote](https://milanote.com/) and others).

The specifics of the backlog structure can vary drastically depending on what type of game you are making. Still, if you are going with ClickUp, [here](https://app.clickup.com/template/project/t-90040105296/d6e92afd78aea9a) you can find a template for a space dedicated to the `SLINGSHOT` project used as an example earlier. Once again, consider getting a little help organizing stuff from [ChatGPT](https://chat.openai.com/chat):

![Image](Images/sc_ChatGPT_2.png)

<a name="game-design-document"></a>
## 2. Creating A Game Design Document

What follows is the creation of the most important document of this phase, the Game Design Document (GDD). It will serve as a blueprint for the entire project and builds upon the rough outline provided by the Game Concept.

<a name="structure"></a>
### 2.1 Structure

With your Game Concept figured out, you should now write a *first draft* of the GDD. This means starting with a structure like the one provided below, adjusting it to your Game Concept if neccessary and filling it with content.

```
1. Introduction
    1.1 Overview
    1.2 Purpose
    1.3 Audience
    1.4 Scope
    1.5 References
2. Game Overview
    2.1 Game Concept
    2.2 Design Pillars
    2.3 Narrative Pillars
    2.4 Look And Feel
3. Walkthrough
4. Game World
    4.1. Overview
    4.2. Lore
    4.3. Locations
5. Story
    5.1 Overview
    5.2 Characters
    5.3 Plot
6. Gameplay Mechanics
    6.1 Movement
    6.2 Combat
    6.3 Environmental Interactions
    6.4 Narrative Interactions
    6.5 Progression
7. Levels and Objectives
    7.1 Overview
    7.2 Objectives
    7.3 Level-Specific Game Mechanics
8. User Interface and HUD
    8.1 Menu Design
    8.2 In-game UI Elements
    8.3 HUD design
9. Art Style and Graphics
    9.1 Art Style
    9.2 Character Design
    9.3 Environmental Design
    9.4 Special Effects And Particle Systems
10. Sound Design and Music
    10.1 Sound Effects
    10.2 Background Music And Score
    10.3 Voice acting
11. Multiplayer and Online Features
    11.1 Multiplayer Modes
    11.2 Online Features and Connectivity
    11.3 Matchmaking And Ranking Systems
12. Development and Production
    12.1 Milestones
    12.2 Production Timeline
    12.3 Budget And Resources Required
    12.4 Tools And Software Used
12. Conclusion
    12.1 Summary
    12.2 Future Plans
    12.3 Appendices
```

The structure of a GDD can and will change from project to project. Not every game project will need all of the elements listed above. To provide a concrete example, you can find the GDD for the `SLINGSHOT` project [here](https://share-docs.clickup.com/9004010474/d/h/8cawjza-41/20c1c286a990252). You will notice that several points have been altered or are left out to fit the smaller scope of the Game Concept.

<a name="modular-approach"></a>
### 2.2 Modular Approach

XXX

<a name="iteration"></a>
### 2.3 Prototyping

Prototyping your game means creating a working model of the Game Concept in order to test its feasibility, functionality, and fun factor. It's an essential step in game development that allows developers to experiment with different mechanics, gameplay systems, and visual styles before committing to a full-scale production. Prototyping allows developers to test their game ideas quickly and cheaply, identify potential problems, and make changes to refine the core mechanics and gameplay systems. It's an iterative process that can help developers make better design decisions and create a more polished and enjoyable final product.

Prototyping is an essential step in game development that helps you test and refine the core mechanics and gameplay systems of your game idea. By following these steps, you can create a prototype that accurately reflects your game's vision:
1. Define the *Core Gameplay Mechanics*: Before you start prototyping your game, it's important to define the core gameplay mechanics that you want to test. This will help you stay focused and ensure that your prototype is effective in assessing the feasibility of your game idea. Write down the core mechanics, including how they work and how they interact with one another.
2. Create a *Paper Prototype*: A paper prototype is a low-cost way to quickly iterate on game mechanics and gameplay systems. Draw out the game board or level on paper and create pieces to represent the player and other game objects. Playtest the paper prototype to see if the core mechanics are engaging and fun.
4. Create a *Digital Prototype*: Once you have a solid paper prototype, it's time to create a digital prototype using your chosen game engine or prototyping tool. Create a simple level or game board and add the core mechanics from your paper prototype. Test the prototype with friends or colleagues to get feedback on gameplay and functionality.
5. *Iterate* and Refine: Use feedback from playtests to refine the core mechanics and gameplay systems. Make changes to the digital prototype and test it again. Iterate as many times as necessary until you have a solid prototype that accurately reflects your game's vision.
6. Add *Visuals and Audio*: Once the gameplay systems are refined and working well, it's time to add visuals and audio to the prototype. This will give you a sense of how the game will look and sound, and will help you decide on the art style and audio direction for the final game.
7. *Test* and Iterate Again: Once you have a working prototype with visuals and audio, test it again with a wider group of people. Use feedback to refine the game and iterate until you have a prototype that accurately reflects your game's vision and is fun to play.