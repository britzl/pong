# Pong
[Defold](http://www.defold.com) implementation of the classic game Pong. The purpose of this project is purely educational and intended to show how little that is required to create a simple game using Defold.

The game consists of the following key components:

* paddle.script - The script controlling the paddles (both player and AI).
* ball.script - The script controlling the ball movement and collision handling (bounce).
* score.script - The script to keep track of and update the score.
* pong.collection - The main collection for the game. Containing two paddles (each with a sprite and a collision object), one ball (with a sprite and a collision object) and the walls (only collision objects).

## Play Online
HTML5 version: https://britzl.github.io/Pong/
