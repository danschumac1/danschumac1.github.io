---
layout: post
title: Herding Sheep with Steering Behaviors in Unity
date: 2026-11-22
description: Building an RTS game with autonomous sheep, flocking behaviors, and some unexpected feedback from my dog.
categories:
  - game-development
tags:
  - unity
  - rts
  - artificial-intelligence
  - steering-behaviors
  - devlog
---
# Herding Sheep with Steering Behaviors in Unity
I'm working on making an RTS and thought sheep would make fun neutral resources. The idea being that you get them nice and fat by taking them to fresh pastures before returning home to shear them for wool or sell them to the meat market. This would cause the two players to have to compete over the best pastures while also protecting their sheep from getting counter-herded by the other player. So far, I'm learning a lot from this project. Learning from my mistakes as a ChatGPT warrior in the game jam, my approach to AI this go-around has been: "Let's pair program, but I'm always in the driver seat. You should never offer explicit code." I learned a lot this way.

I explained how vector steering works to my dad. Basically just pushing objects in different directions based on conditions (e.g. a dog, grass, or other sheep being close by). He asked "Okay, but how is that AI?" It made me think just how far we've come. AI is a stupid term; people should be more specific. :) What we used to call AI is now just game logic. Same for predictive analytics and recommender systems.

I asked ChatGPT to make a graphic showing how the vector steering works. Individually, these behaviors aren't very impressive, but in combination they can be pretty convincing and make the sheep feel alive. 


![Sheep steering behaviors](steeringoverview.png)

Here is a demo of the progress I've made.
<iframe
  width="560"
  height="315"
  src="https://www.youtube.com/embed/GRUwnBtD-K0"
  title="RTS Game Development Demo"
  frameborder="0"
  allowfullscreen>
</iframe>

My dog is so smart...  I swear *she never watches screens for anything else*. She doesn't watch me work, she doesn't watch tv when it is on, or other video games. But she will sit here and watch me herd these silly AI sheep I made. She even occasionally growls at the ones that aren't in their proper places. I take it as a huge compliment; the sheep are real enough to make a border collie jealous. 

<iframe
  width="315"
  height="560"
  src="https://www.youtube.com/embed/bum_hRNWKK0"
  title="My Dog Watching AI Sheep"
  frameborder="0"
  allowfullscreen>
</iframe>

I also forgot to share a moment from the game jam that made me really happy. One of the participants at the game jam was having a grand time seeing how many times she could kill Chudly by mashing E. Wasn't what we intended, but she probably had more fun than anyone else with our game.



![Chudly getting repeatedly killed](ChudlySpam.png)