[[Back to Main Page]](../README.md/#production-guide-for-solo-game-development)

<a name="getting-started"></a>
# [2.] Getting Started

XXX

<a name="toc"></a>
## Table of Contents

> 1. [A Range of Responsibilities](#responsibilities)
>    - 1.1 [Design](#design)
>    - 1.2 [Engineering](#engineering)
>    - 1.3 [Art](#art)
>    - 1.4 [Writing](#writing)
>    - 1.5 [Management](#management)
> 2. [What to Learn (First)](#learn)
> 3. [Finding Ideas](#finding-ideas)
>    - 3.1 [Brainstorming](#brainstorming)
>    - 3.2 [Inspiration](#inspiration)
>    - 3.3 [Challenges](#challenges)

<a name="responsibilities"></a>
## 1. A Range of Responsibilities

Making and selling games requires expertise in a number of different fields. Studios usually have dedicated departments for different aspects of the game, whereas you as a solo creator will have to cover all of those areas yourself. This didn't really hit me until after i started out, but the challenges quickly become apparent - game design, level design, writing, programming, asset creation, project management, etc., you're responsible for all of it. How do you manage that, especially when you are still learning the ropes in some or even all of those disciplines?

In short: start small, get an overview of all of the different types of tasks that await you, figure out what you are good at already and where you have gaps of knowledge. You want to get a *basic* level of understanding and competence in all of the important fields so that you don't unexpectedly hit a wall halfway through development. Building and releasing a *very* small and simple game is a good way to action-test your ability to go through the entire process. In section 3.1 [`Finding Ideas`](#finding-ideas), I'll provide different ideas and challenges that you can use for your very first game.

What follows is a first *overview* of the different departments a game studio might have: [`Design`](#design), [`Engineering`](#engineering), [`Art`](#art), [`Writing`](#writing), and [`Management`](#management). I will describe the role of each of those departments in the development process, and what that means for solo development (I will go into detail later on in the guide).

<a name="design"></a>
### 1.1 Design

A lot of the work the design department does happens early on, during the [`Concept Phase`](2_ConceptPhase.md/#concept-phase) and [`Pre-Production`](3_PreProduction.md/#pre-production), which is where the main design specifications are defined. However, where other members of the development team will often come and go, the designer(s) are usually a more persistent presence, monitoring the whole production to keep everything in line with the game's vision.[^1]

In detail, the design includes:

- Game Design
- Story Design
- Level Design

[^1]: cf. Kramarzewski, Adam, and Ennio De Nucci. 2018. *Practical Game Design*. Packt.

As a solo developer, you save the work of having to communicate your design to the various other departments, and you'll have ultimate creative freedom. However, the danger is that this can lead to lazyness in the design process and an "I'll think about it when i get there"-attitude, which can easily kill your project, even after you've put a lot of work into it.

<a name="engineering"></a>
### 1.2 Engineering

The game developers in the engineering department are responisble for the project's source code. They implement all of the features and mechanics described in the detailed design documentation, as well as all of the art assets.

When not coming from a programming background, this part of solo game development can seem particularly daunting. Personally, I found that learning how to code was a pretty enjoyable experience - due to the logical nature of it, the most basic concepts are pretty easy to understand, and you can build on them, bit-by-bit. That being said, it helps to bring some pre-existing experience or an understanding of those basic concepts with you. When starting out, it feels like a lot, but as soon as you develop this skill, you'll find how much can be achieved with simple (and *reusable*) code.

<a name="art"></a>
### 1.3 Art

The art department creates all of the game's assets - 2D-art and UI-elements, 3D-models for objects, architecture, and characters, as well as sound effects and music. This can take a lot of time and the work is usually distributed to many different artists, underlining the importance of starting into [`Production`](3_3_Production.md/#production) with solid design documentation and a coherent vision.

Depending on your background, this can be a massive challenge for creating your first game(s). Fortunately, there are plenty of helpful resources and strategies (covered in this guide) for reducing the workload, including the usage of third-party assets (an unbelievably important part of solo development that should not be looked down upon).

<a name="writing"></a>
### 1.4 Writing

If a game has a story, it usually has dedicated writers. Some studios turn all developers into writers for lots of individual storylines, others comission remote-working freelance writers. Usually, for small to mid-sized teams, there are only a few or just one writer (often the lead designer or narrative designer).[^1] Either way, the details of the story and the actual used texts come after the overall concept and narrative design has been specified in [`Pre-Production`](3_2_PreProduction.md/#pre-production).

Many solo developers gladly take on the writer role, as their games are often centered around strong narrative ideas. However, it is important to consider what you're getting into before writing complex storylines (dialogue systems can be quite difficult to set up as well).

<a name="management"></a>
### 1.5 Management

Last but not least, the management department covers everything regarding the project's work infrastructure, time schedule, and resources. Even though creating a feasable production plan with milestones and a realistic timeline is difficult, it is very important - especially when working with a publisher.

Even seemingly simple games can fall into production-hell if you are working solo and are not yet familiar with the process. A decent amount of preperation and project management can combat this and should be a part of any game development effort, even if nobody but you is watching.

[[Back to Top]](#getting-started)

<a name="learn"></a>
## 2. What to Learn (First)

XXX

[[Back to Top]](#getting-started)

<a name="finding-ideas"></a>
## 3. Finding Ideas

A game idea is just that - an idea, like `2D game where you can perform a "slingshot" move by clicking and dragging the player character`. No specifics are required at this stage.

<a name="brainstorming"></a>
### 3.1 Brainstorming

A spontaneous, unorganized brainstorming session is always a good way to capture your game idea(s) for the first time. Having it written down clears up space in your mind and helps you remember all of the details you though about. It can also be helpful for playing around with different versions of the same idea. A good web application for brainstorming is [`Kinopio`](https://kinopio.club/):

![Kinopio](../Images/Kinopio.png "An example board on Kinopio")

It serves as a virtual whiteboard and can help you visually organize and connect ideas. I mostly use it temporarily for mind-mapping and instead collect the most promising game ideas as notes in my [`OneNote`](https://www.onenote.com/?public=1) notebook (which I use for other stuff, too). This makes it easier to quickly write down ideas on my mobile phone.

<a name="inspiration"></a>
### 3.2 Inspiration

Personally, I often can't stop my brain from constantly producing new game ideas, but sometimes I get stuck on something when trying to develop them further. The following approaches can help you find inspiration and getting unstuck:
- *Play games*: Start by playing games, from different genres and platforms, and including games you have already played. Analyze what you enjoy about them, what exactly draws you in. What about them is unique or makes you want to keep playing?
- *Identify a problem to solve*: Think about problems that you or others face in their daily lives. This could be anything from a lack of motivation to exercise to difficulty in learning a new language. Brainstorm ways that a game could help solve this problem.
- *Look for inspiration in other media*: Draw inspiration from books, movies, and TV shows. Consider how you could adapt a particular story or concept into a game.
- *Explore new technology*: Keep up-to-date with new technology and innovations in the gaming industry. Consider how new hardware, such as virtual reality headsets or haptic feedback controllers, could be used to create new gaming experiences.
- *Consider your own passions and interests*: Think about your own hobbies and interests. Consider how you could incorporate these into a game. For example, if you enjoy hiking, you could create a game that simulates a hiking adventure.
- *Combine different ideas*: Try combining different ideas to create something unique. For example, you could combine a puzzle game with a platformer or a survival game with a city-builder.
- *Collaborate with others*: Brainstorm with others and collaborate on game ideas. Consider working with people from different backgrounds and skill sets, such as artists or programmers.
- *Think about your target audience*: Consider who you want to make games for and what they would enjoy. Think about the age group, interests, and gaming experience of your target audience.

<a name="challenges"></a>
### 3.3 Challenges

XXX

[[Back to Top]](#getting-started)

[[Back to Main Page]](../README.md/#production-guide-for-solo-game-development)