---
layout: post
title: Collision Detection and Resolution
---

Programming game physics from scratch can be quite challenging, and one of the most challenging problems of game physics is _collision detection and resolution_. Even the most polished and robust collision detection systems in published games suffer from exploitable bugs in extreme or unexpected situations.

However, sometimes the biggest challenge is getting collision to work properly _at all_, and I've identified several levels of complexity in collision detection and resolution systems programmed from the ground up. Often the type of collisions you're able to program translate to what core mechanics a game ends up with, and this post is written as a guide to choosing collision detection systems more decisively.

## Death On Contact

By far the easiest collision resolution is to destroy any object that contacts another object or the level geometry. You don't have to worry about what to do with an object after it collides, because it is gone. This type is seen in many historically successful games such as [_Asteroids_](https://en.wikipedia.org/wiki/Asteroids_(video_game)) and scrolling shooters such as [_Scramble_](https://en.wikipedia.org/wiki/Scramble_(video_game)). The simplicity makes this technique less prone to bugs, take fewer processor cycles, and gets a major game mechanic out of the way so programmers can focus on other challenges. Death-on-contact even has the side-effect of making a game appear _difficult, challenging,_ and _unforgiving_ to players who enjoy games with those characteristics.

Games for the Atari home computer often employed death-on-contact collision resolution for the sake of code simplicity. [_Fort Apocalypse_](https://en.wikipedia.org/wiki/Fort_Apocalypse) and [_Super Cobra_](https://en.wikipedia.org/wiki/Super_Cobra) are pioneers of the side-scrolling shooter genre, and they leveraged the Atari's pixel-perfect collision detection features to kill the player on contact with any walls, enemies, or projectiles, while building complex and engaging levels around the challenge of avoiding death. As a beginner programmer, death-on-contact collision resolution is a low-effort, high-impact game mechanic to design around and could result in incredible returns if decided upon early.

Pros: Fairly easy, one-and-done resolution.

Cons: No health points, insta-death jarring and unforgiving.

## Damage While In Contact

A less-popular resolution system is to damage a player while contacting certain objects. Games like [_Turrican_](https://en.wikipedia.org/wiki/Turrican) and [_Abe's Amazing Adventure_](https://abe.sourceforge.net/) are some lesser-known but successful titles that subtly incorporate this mechanic.

An advantage of this collision system is that its not necessary to program _knock-back_ or _invulnerability frames_. Normally it would be very annoying to be damaged during _every frame_ an enemy or projectile remains in contact with the player, but if the game is designed around it by providing plenty of "health" and damaging the player by a small amount per "tick", the challenge becomes avoiding prolonged contact. Being able to shoot a baddie that just hit you (instead of being "knocked-back" or "stunned") could even be considered a desirable game mechanic.

Pros: No need to program knock-back or invincibility frames.

Cons: Archaic compared to modern expectations.

## Knockback and Invulnerability Frames

Considered a staple of good game design, its important to consider "invulnerability frames" when programming a game where the player has a number of "health points" rather than instant death on contact. The main purpose of knock-back and invulnerability frames is to prevent the player from being damaged repeatedly after being hit for the first time.

## Top-only Terrain Collision

Ex: [_Super Smash Bros._](https://en.wikipedia.org/wiki/Super_Smash_Bros.)

## Full-geometry Collision Detection and Resolution
