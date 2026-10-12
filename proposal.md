# Proposal

## Introduction (8-12 sentences total)

### What is your research question?

User need in multiplayer video games is often a continuous spectrum, but
many users are only offered a binary choice for accommodation. Can allowing a broader
range of accepted inputs in a video game further address variable accommodation
needs for a player?

### What is the current status of your system?

Currently, there hasn't been time put into the system in use! I will be starting
consistent work on it this week.

### What do you propose to build this semester?

I propose to build a series of gradient accessibility options within an existing
video game! One option would assist players who have difficulty in performing
input sequences quickly, and the other option would assist players who have
difficulty in performing input sequences accurately!

### What is your stretch goal?

My minimal stretch goal is to generate inputs from actual gameplay, identify
sections where the player intended to perform an action but was unable to,
and to run those inputs through the assistive options to see if they
detect intent where the original system failed!

Maximal stretch goal is to have this be rendered by the game (visual
showcases help _so_ much more in conveying ideas!)

### Describe your Teck Stack (languages, framework, hardware (if any))

For this project I would be using C# and the Unity engine, as the game
(Footsies: Rollback Edition) is written in these! Additionally, I would
use xbox game controllers to generate inputs, and to play the game with.

## Aim (1-3 sentences per question)

### What you want to do

I want to add to more nuanced assistive means for multiplayer videogames!

### Why you want to do it

I want to do this to better represent and showcase the nature of accommodation.
User needs are more complex than a simple binary choice, and tuning accommodation
gives a user the means to align their inner expectations with their outer experiences!

### How you plan to do it

I plan to record gameplay inputs and identify sections where misses of player intent
occurred, then to modify the game rules to broaden the range of intent matches,
and to compare the results of the original vs the modified versions!

### How will you know if you succeed

I will have succeeded if the modifications to the game result in player intent
during matches being successfully captured _without_ significant false positive
matches, compared to the base game.

### What are the benefits if the project is successful

Players would be able to have more of their internal intent reflected by
their external gameplay results.

This project would benefit the many users who only need partial forms of
accommodation in gameplay, which would likely allow more users to feel
comfortable about using forms of assistance! Ideally, this work would expand
the scope in which these technologies are thought about and implemented.

## Intellectual Merit & Broader Impacts (5-10 sentences total)

### Effectively a small related works section

The first paper addresses a related area of assistive technology, which actually
helped players _accelerate_ their own means of learning! Contrary to commonly
held belief, those studied who used an assistive technology learned to play
better _more quickly_ than those who didn't.
[1](https://dl.acm.org/doi/abs/10.1145/2967934.2968101)

The second paper talks about how one player knowing that the other was using an
assistive feature did _not_ adversely affect their perception and experience of
the gameplay. This is important to showcase that commonly held beliefs about
how a user making use of assistance might be false, and that _more_ enjoyment
is derived when each user is able to have their respective needs met!
[2](https://dl.acm.org/doi/abs/10.1145/2858036.2858156)

The third paper will hopefully give insight into the _how_ for the research _answer_.
Using directed hypergraphs with fuzzy information might just be the way to match
multiple axis of data input sequences efficiently and quickly!
[3](https://digitalrepository.unm.edu/cgi/viewcontent.cgi?article=3531&context=nss_journal)

### How will your system contribute to science?

This system will (hopefully) explore further applications of directed hypergraphs
using fuzzy membership! They have been used a lot in recent years in the space of
different agents, but through initial searching I haven't yet found papers describing
their use in data stream matching!

### How might it contribute or benefit society if your full vision is realized

If the full vision is realized, then users who have need for varying physical accomodation
in these game spaces will have more of their internal intent showcased through external
means! Ultimately, this research will hopefully help contribute to levelling the
competitive playing field in these forms of games, and allow more people who
need just _some_ assistance to feel more confident in their abilities.

## Solo or Group (3-5 sentences total)

### Are you doing this solo, or name your partner

I am planning to work with Fran Pereira as a cross-course project (for
our 546/Algorithms for Big Data class)

### Describe your ideas to make consistent progress

1. Meeting to draft a timeline for accomplishing each goal of this project!
2. Holding consistent weekly times to meet (whether in person or virtually)
3. Maintaining clear communication about progress/difficulties in the process;
   if either of us have something come up, it's not the end of the world, and
   can be accomodated!

### If you are in a group: what is your role/expertise?

Fran will mostly be working with me on the fuzzy matching means as a joint effort
for our other course! Since I am using this project between 2 courses, I will be
contributing most of the efforts into getting the environment set up, learning
and documenting the use of the repository, and related efforts!

## References

### At least 3 papers closely related to your idea

1. [Does Helping Hurt?: Aiming Assistance and Skill Development in a First-Person Shooter Game (Gutwin et al. 2016)](https://dl.acm.org/doi/abs/10.1145/2967934.2968101)
2. [How Disclosing Skill Assistance Affects Play Experience in a Multiplayer First-Person Shooter Game (Depping et al. 2016)](https://dl.acm.org/doi/abs/10.1145/2858036.2858156)
3. [Directed n-Superhypergraphs Incorporating Bipolar Fuzzy
   Information: A Multi-Tier Framework for Modeling BipolarInformation: A Multi-Tier Framework for Modeling Bipolar
   Uncertainty in Complex NetworksUncertainty in Complex Network (Fujita et al. 2025)](https://digitalrepository.unm.edu/cgi/viewcontent.cgi?article=3531&context=nss_journal)
