# Verbs, Objects, and a Theory of Fun

## Learning Goals
By the end of this lesson, students will be able to

- Define what a Verb is in the context of a game's design
- Identify Verbs in well known games
- Define what an Object is in the context of a game's design
- Idenfity Objects in well known games
- Begin hypothesising on how the interactions of Verbs and Objects create fun scenarios

## Fun. (Not the Band)

We can all agree that video games are generally an enjoyable pasttime. Some we can sit down at for a month and find joy, some come and go within a few play sessions, and others bring us joy year after year.

A lot of blood, sweat, tears and ink has been spilled over the years trying to figure out what makes some things fun, and other dull. One of the most interesting and usable theories, put forth by Raph Koster, can be summarized as "Fun is learning via intuition". In other words, we have fun discovering, developing and mastering skills by practicing them. We continue to have fun as long as we are learning under this model, and stop having fun when we stop learning, either because we feel we are no longer mastering new skills, or because we are unable to learn the skills needed to progress.

Take, for example, Candyland by Hasbro. For young children, all of its aspects are new: taking turns, moving pieces, shuffling a deck, having a winner. 

Kids love Candyland.

![A group of children enjoying Candyland](https://www.scholastic.com/content/dam/teachers/blogs/nancy-jang/2017-2018/NJ-moregames-candyland1.JPG)

Adults don't.

![A Saturday Morning Breakfast Cereal comic](https://i.kym-cdn.com/photos/images/original/001/368/118/be5.png)

Most of us have already done the learning that Candyland is meant to impart. Nothing to learn, nothing to gain.

Just a cold, hard stroll to confront the King of Candy.

## Understanding Games and their Mechanics

To talk about how games produce fun (and perhaps even meaning), we need to talk about what the most atomic parts of a game. Lots of smart people have already taken a stab at breaking this down, but my personal favorite in terms of immeadiately usable knowledge has got to be Anna Anthropy and Naomi Clark's concepts of Verbs and Objects.

### Verbs

Assuming that we have some sort of player avatar, a verb is any distinct action that a player can take, performed on or by the player character. In the simplest games, a single verb is associated with a single, fixed outcome, e.g. pressing right on the directional pad will move the avatar to the right.

Verbs coalesce into a set of abilities that define what a character can do.

Mario jumps and runs and shoots fireballs, Pac-Man moves up down left or right, the defender in Space Invaders moves left and right and shoots.

##### Exercise (5 mins):

Pick a character or game you are familiar with from the list below, and break down the possible actions you can take. If there are multiple games or variants to choose from, pick one and note your assumptions.

- Katamari Damacy
- Solitare
- Megaman
- Monopoly
- Donkey Kong
- Baseball/Softball

#### Variety in Verbs (Constraints, Emergence and Elegance)

Two characters can have the same verb, but feel very different. Why?

Part of our job as designers (and in this course, as programmers) is to figure out the details of how each of the verbs we are using works. A jump is not just a jump, but it is the result of a series of decisions:

- What is the maximum height of the jump?
- How long is the jump?
- How much lag is there between when someone hits the button and when the character becomes airborne?
- Is acceleration constanst during the jump, or do we adjust it dynamically?
- Can a character change direction mid air?
- Are there new verbs unlocked when we are airborne?

Knowing this, we can begin to make choices about how we want our game to feel. Is the player fast, or slow? Are they nimble or clumsy? Once they begin an action, are they stuck until they finish that action, or can they cancel certain moves?

##### Exercise (10 mins):
Consider one of the verbs that you brainstormed earlier. How do the rules of the game shape its use? Do systems within the game make it the way it is? How does it differ from other, similar verbs in other games?

<details>
<summary> **Here are some ways you can modify verbs:** </summary>
<br>

Some verbs are different because they are **Constrained**:

- In Space Invaders, you may only have one laser shot on the screen at a time
- In Solitare, you may only use the top card from the deck's 'flipped' pile
- In Dominion, you are initially limited to one purchase and one action per turn
- In Softball, you must pitch the ball underhanded

Some verbs are different because they are **Elegant** (as defined by Jesse Schell in 'The Art of Game Design'):

- In Mario 64, consecutive jumps go higher and higher
- In Downwell, shooting from your feet slows your descent and can eliminate foes
- In Sorry, drawing a 7 allows a player to either spend all of the movement on one pawn, or split the movement between two

Other verbs have **Emergent** properties:

- In Street Fighter 2, being hit by a move can leave an opponent stunned long enough to hit them again, leading to a combo
- In Half-Life 2, a player can reach slightly higher planes if they crouch mid-air
- In Soccer, the defense can force a skilled striker offsides with proper coordination

</details>

This early on, most of the verbs we should be creating should be relatively simple. Focus on verbs that are responsive and constrained, because those are the easiest to play with (consider for a moment, the amount of time it would take to recreate the all the different jumps from one of the 3D Mario games).

Verbs give the players abilities, and ways to express themselves. They are empowering. Most games provide some sort of resistance for players to overcome, or things in the world that react to the verbs the player is using. Objects fulfill that role in our vocabulary.

### Objects



## Referenced Materials

- [A Theory of Fun](https://www.theoryoffun.com/) by Raph Koster
- [A Game Design Vocabulary](https://www.amazon.com/Game-Design-Vocabulary-Foundational-Principles/dp/0321886925) by Naomi Clark and Anna Anthropy
- [Dynamics: The State of the Art](https://www.gdcvault.com/play/1014597/Dynamics-The-State-of-the) by Clint Hocking

## Additional Reading

- [Eniko](https://twitter.com/Enichan) an indie designer who explains a lot of her thinking and work on Twitter
- [Game Anim](https://www.amazon.com/Game-Anim-Video-Animation-Explained/dp/1138094870/ref=asc_df_1138094870/?tag=hyprod-20&linkCode=df0&hvadid=266396064900&hvpos=1o1&hvnetw=g&hvrand=16399335368189957611&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=1027744&hvtargid=pla-635776353047&psc=1) by Johnathan Cooper
- [My Own Garbage Opinions](https://twitter.com/LegendaryVermin) because look, I'm kinda an egoist alright?
