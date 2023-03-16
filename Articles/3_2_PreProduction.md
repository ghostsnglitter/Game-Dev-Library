[[Back to Main Page]](../README.md/#production-guide-for-solo-game-development)

<a name="pre-production"></a>
# [3.2] Pre-Production

During Pre-Production, you are going to hash out the most important design decisions. This is done through an iterative process of design and prototyping. You will also consider the resources that will be needed and draw up a plan for the realisation of your game - including an initial timeline - so that you can move on to Production.

<a name="toc"></a>
## Table of Contents

> 1. [Setting up a Backlog](#backlog)
> 2. [Creating a Game Design Document](#game-design-document)
>    - 2.1 [Structure](#structure)
>    - 2.2 [Elements](#elements)
> 3. [Managing Risks](#managing-risks)
>    - 3.1 [Risk Analysis](#risk-analysis)
>    - 3.2 [Prototyping](#prototyping)
> 4. [Funding](#funding)

<a name="backlog"></a>
## 1. Setting up a Backlog

A crucial part of your game's development is the backlog. It serves as an important project management framework, housing all the design documents, all the tasks that need to be done, and a project timeline with milestones and due dates.

Since you are about to create important design documents, it makes sense to set up the backlog early. To begin with, you really only need to *create a dedicated space for your game project, with the ability to add documents and tasks as you go along* (you should start by integrating the Game Concept you created in the previous phase). Many of the tasks will come directly from the game design document created in the next step, and can be written as a list of features to be implemented. Of course, you may also want to create task lists for administrative work, etc.

There are different project management applications that can be used for this, but my personal pick is [`ClickUp`](https://www.clickup.com/):

[![ClickUp](../Images/ClickUp.png "An example look on ClickUp's interface")](https://www.google.com/imgres?imgurl=https%3A%2F%2Fclickup.com%2Fimages%2Fv2%2Fviews%2Ftask%2Fboard-view.png&imgrefurl=https%3A%2F%2Fclickup.com%2Ffeatures&tbnid=vDMXfyarHV-RuM&vet=12ahUKEwjO0bGAntT9AhWcwQIHHWXzB8IQMygDegUIARDPAQ..i&docid=kM8svJibefhcEM&w=1299&h=883&itg=1&q=clickup&ved=2ahUKEwjO0bGAntT9AhWcwQIHHWXzB8IQMygDegUIARDPAQ)

It is extremely feature-rich and customizable (even the free version). This might be a bit much for your first project though, so feel free to use alternatives for your own backlog (like [`Nuclino`](https://nuclino.com/) and [`Milanote`](https://milanote.com/)).

The specifics of the backlog structure can vary drastically depending on what kind of game you are making. However, if you are using ClickUp, you can find a template for a space dedicated to the `SLINGSHOT` project [here](https://app.clickup.com/template/project/t-90040105296/d6e92afd78aea9a).

[[Back to Top]](#pre-production)

<a name="game-design-document"></a>
## 2. Creating a Game Design Document

What follows is the creation of the most important document of this phase, the Game Design Document (GDD). It will serve as a blueprint for the entire project, and as a plan for Production. The general *vibe* of the document is to specify the *design* of the game's elements, such as mechanics, in as much detail as possible, while leaving the rest for Production.

You should create a first draft, then complete and refine it through a process of risk management (see 3. [`Managing Risks`](#managing-risks)). Afterwards, you will have a comprehensive document with all of the design specifications neccessary to realize the game from start to finish - even though you will probably be making further adjustments during production.

Here are some general notes and ideas about creating the Game Design Document:
- As explained in 1. [`Setting Up A Backlog`](#backlog), you should integrate the GDD into your backlog. Depending on the project management tool you use, this may allow you to reference specific parts of the GDD in tasks or other documents.
- Even with a comprehensive structure like the one below, the individual elements should be kept short and to the point. You can use bullet-points where appropriate.
- Include images. Especially for game systems, it can be helpful to use diagrams to visualize processes. A nice and simple web tool for this is [`draw.io`](https://app.diagrams.net/). For finding reference images and creating mood boards, [`Pinterest`](https://www.pinterest.de/) is actually a really good option. An amazing solution for quickly generating concept art is [`DALL-E`](https://labs.openai.com):

  ![DALL-E](../Images/DALL-E.png "An example of DALL-E's capabilities in generating concept art")

- It can help to break down the design into four core components:

  ![GameComponents](../Images/GameComponents.png "A game broken down into four core components")

  You can see that all of the components relate to each other. For example, the `Mechanics` - the processes and rules of the game, can only function with the right `Technology` - the technological means through which the player interacts with the game (could be pen & paper in case of a table-top game), are conveyed to the player through an `Aesthetic` - the look, feel, *vibe* of your game, and should be made believable and consistent within the game's `Story` - the sequence of events in your game creating a coherent experience.

  But besides these *dependencies*, the model can also help *design* these components. You could ask yourself "what kind of gameplay mechanics would help convey this story?". You can ask this sort of question for any of the components and in any direction.

<a name="structure"></a>
### 2.1 Structure

This is a - rather detailed - *example* structure for the GDD, with detailed information on specific elements found below. While smaller games won't need all of the sections listed, it's helpful to get an overview of what kinds of things *could* be relevant when designing your game.

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
   - 2.4 [Look and Feel](#elements-look-and-feel)
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
7. [Levels and Objectives](#elements-levels-and-objectives)
   - 7.1 Overview
   - 7.2 Objectives
   - 7.3 Level-Specific Gameplay Mechanics
8. User Interface and HUD
   - 8.1 Menu Design
   - 8.2 In-Game UI Elements
   - 8.3 HUD Design
9. Art Style and Graphics
   - 9.1 Art Style
   - 9.2 Character Design
   - 9.3 Environmental Design
   - 9.4 Special Effects and Particle Systems
10. Sound Design and Music
    - 10.1 Sound Effects
    - 10.2 Background Music and Score
    - 10.3 Voice acting
11. Multiplayer and Online Features
    - 11.1 Multiplayer Modes
    - 11.2 Online Features and Connectivity
    - 11.3 Matchmaking and Ranking Systems
12. Development and Production
    - 12.1 [Milestones](#elements-milestones)
    - 12.2 [Production Timeline](#elements-timeline)
    - 12.3 [Budget and Resources Required](#elements-resources)
    - 12.4 [Tools and Software Used](#elements-tools)
12. Conclusion
    - 12.1 Summary
    - 12.2 Future Plans
    - 12.3 Appendices

The structure can and will vary from project to project. Not every game project will need all the elements listed above. To give a concrete example, you can find the Game Design Document for the `SLINGSHOT` project [here](https://share-docs.clickup.com/9004010474/p/h/8cawjza-190/23fe9611b89720f). You will notice that some items have been altered or omitted to fit the scope and genre of the project.

<a name="elements"></a>
### 2.2 Elements

<a name="elements-introduction"></a>
#### Introduction
Document-related info.

<a name="elements-game-concept"></a>
#### Game Concept
Link to previously created Game Concept.

<a name="elements-gameplay-pillars"></a>
#### Gameplay Pillars
List 3-5 key game design pillars that describe the gameplay.[^1] These should be simple adjectives, e.g:

[^1]: This approach comes from Chris Gardiner's GDC talk ["Sunless Skies: A Narrative Postmortem"](https://youtu.be/_sslFBVy5Lc)

1. Fast: The action should start immediately. Player movement should feel quick and agile. When players die, they should be able to start over immediately.
2. Emergent: The game should have very simple player actions and objectives, but create increasingly complex situations through the interaction of different game systems.
3. Challenging: It should be a real challenge to stay alive for a long time, creating an intense experience.
4. Rewarding: Learning how the game's ecosystem works and using that knowledge to your advantage should feel extremely rewarding and addictive.

<a name="elements-design-pillars"></a>
#### Narrative Pillars
List 3-5 key narrative design pillars that describe the mood, atmosphere, and overall direction of the game's narrative.[^1] These can be sentences or quotes that convey a certain tone. An example from `Sunless Skies`:

1. Stake your Claim
2. Who are you, In the Dark?
3. Conceal your Hand
4. Mind your Manners
5. Nothing is Sacred

<a name="elements-look-and-feel"></a>
#### Look and Feel
Describe the aesthetics and feel of the game using specific vocabulary, e.g:

1. Retro: The game should have a low-res, retro look with abstract visuals.
2. Surreal: The game world should feel very alien and strange, and the overall visuals of the game should reflect that.
3. Squishy: The game should have a satisfying and organic feel with lots of squishy animations.

<a name="elements-walkthrough"></a>
#### Walkthrough
Write a short second-person walkthrough of a sample play session. This should not be too long, but should provide a good overview of the chronological *experience* of playing the game, without isolating and categorizing individual game elements.

<a name="elements-story"></a>
#### Story
Create an initial outline of the story. Key characters and plot points - from beginning to end - should be worked out now, during pre-production (of course, things may change later). Detailed writing will take place during the production phase.

<a name="elements-player-actions"></a>
#### Player Actions
List and describe the core player actions and how they work specifically, like movement, combat actions, etc.

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
#### Levels and Objectives
Provide an overview of the different levels, their objectives, and list level-specific gameplay mechanics. This is only an outline, the details for individual levels should be found in a seperate document created during Production.

<a name="elements-milestones"></a>
#### Milestones
Define the major milestones for Production. These may include `First Playable` (first build to give a good idea of the gameplay, things like menus may still be missing), `Vertical Slice` (a short but fully playable sample of the final game that can be used to pitch to studios or investors), `Pre-Alpha` (the majority of the game's content is implemented, so you can start playtesting and decide what needs to be cut or improved), `Alpha` (a feature-complete build of the game that may still be missing certain elements, such as art assets, and needs further polishing, bug fixing, etc.), `Beta` (a complete build of the game that now needs to be optimized above all else), and `Gold Master' (the final build of the game, ready to be released to the public).[^2]

[^2]: Taken from the CG Spectrum article ["How video games are made: the game development process"](https://www.cgspectrum.com/blog/game-development-process) by Nadia Stefyn.

<a name="elements-timeline"></a>
#### Production Timeline
Create a rough timeline for production by giving the individual milestones due dates.

<a name="elements-resources"></a>
#### Budget and Resources Required
Calculate your budget for Production and list all of the resources needed. This should include a full list of assets that need to be created or licensed (models, textures, sounds, etc.), or a an overview with a reference to a more detailed document.

<a name="elements-tools"></a>
#### Tools and Software Used
Specify what tools are being used to develop this game. This should include the specific editor version of Unity (or whatever game engine you are using), the chosen source control software, 3D modeling software, etc. You could include a diagram visualizing your workflow.

[[Back to Top]](#pre-production)

<a name="managing-risks"></a>
## 3. Managing Risks

With a first draft of the Game Design Document, you can begin an iterative process of testing and refining the design. The approach for this is characterized by finding and minimizing risks (see 3.1 [`Risk Analysis`](#risk-analysis)), more often than not through the creation of working prototypes (see 3.2 [`Prototyping`](#prototyping)).

<a name="risk-analysis"></a>
### 3.1 Risk Analysis

The general process for analysing risks looks as follows:

1. *Identify a potential risk*: The first step is to identify a potential issue that could arise during development. Look through your Game Design Document and identify any areas that could pose a risk to the development process (it usually takes some time and experience to be able to properly spot potential risks). You may find different types of risks:

   - A: A gameplay mechanic could actually be less fun than imagined (design risk).
   - B: The chosen game engine could have trouble handling the desired number of objects/assets on-screen at the same time (technical limitations).
   - C: The amount of art assets that need to be created could blow the scope of the project and cost too much time/money (budget constraints).

2. *Assess the impact and probability of the risk*: Determine the potential impact of the risk on the project, such as how much it could delay the timeline, increase costs, or impact the quality of the final product. Then, estimate the probability of the risk occurring.

   - A: If it's a core gameplay mechanic, it could impact the project dramatically, as most of the other mechanics are going to be centered around it. Depending on the complexity of the game, redesigning it mid-development could delay the timeline a lot.
   - B: This too could have a big impact on development. If only during Production it is found out that the engine in use has some critical limitations, difficult decisions will have to be made. A switch to a different engine could cost a lot of time, while redesign of certain mechanics could hurt the game's vision. This depends on the importance of the particular issue though.
   - C: With more art required than the budget and resources allow, big sacrifices may have to be made during development. This might save some of the work needed for implementation, but having to scale down the entire game will certainly take time too and the original vision of the game may suffer for it. Alternatively, timeline for the project may just have to be delayed.

3. *Prioritize the risk*: Using the impact and probability assessment, determine what priority this risk has so you can focus on high-impact, high-probability risks first, followed by lower impact risks with lower probability.
4. *Develop a risk management strategy*: Once you have assessed the priority of the risk, develop a strategy to manage it.

   - A: Create a [prototype](#prototyping) just for this gameplay mechanic and test it. Try playing around with variations and adjustments until it feels the way it supposed to. In case the prototype fails, find a different design that works.
   - B: Create a [prototype](#prototyping) just for this scenario and treat it as a benchmark. If it is a question of rigid software limitation or feature availability, research the issue online and within the engine's documentation. In case the prototype fails or a limitation is found, find an engine better suited for your game or update the design.
   - C: Create/commission a sample art asset and see how much time/money is required. In case the numbers don't match up with what you had in mind, add extra resources or development time as a buffer, or scale down the game's content.

5. *Review and update the risk analysis regularly*: Risks can change over time, so it is important to review and update the risk analysis regularly throughout the development process.

<a name="Prototyping"></a>
### 3.2 Prototyping

For more specific information on prototyping, here are some general rules and tips:

1. *Answer a question*
2. *Ignore fidelity*
3. *Don't be clingy*
4. *It doesn't have to be digital*
5. *It doesn't have to be interactive*
6. *Start with the toy*

[[Back to Top]](#pre-production)

<a name="funding"></a>
## 4. Funding

XXX

[[Back to Top]](#pre-production)

[[Back to Main Page]](../README.md/#production-guide-for-solo-game-development)