TypeScript: A Dungeon Adventure
----

Congratulations! You thought we had a boring interview planned for you, but today we're going to make a game!

Well, part of a game. We won't finish.

The style of game is a [Roguelike](https://en.wikipedia.org/wiki/Roguelike). It'll look something like
[this](https://upload.wikimedia.org/wikipedia/commons/0/0c/Rogue_Screenshot.png) - a top down dungeon 
made out of ASCII symbols. 

Some defining features of a roguelike:
 - The game uses random dungeon generation, to increase replayability.
 - Death is permanent. Save games don't allow you to recover previous state.
 - It's turn based, not real-time: the world only updates in response to player input.
 - It has a non-modal interface. Every action is available whatever the game / UI state (although it may not succeed)
 - It has complexity arising from the interaction of systems. There's more than one way to accomplish a goal. 
 - Resource management is important.
 - Hack and slash combat is ultra important.
 - A lot of what you discover is consistent within one "run" but will be randomly regenerated if you die. 
   Just because drinking a green potion heals you now doesn't mean it won't turn your next character into a statue.










- [Starter template for prototyping and building CLI tools with Node.js and TypeScript](https://blog.codeleak.pl/2023/02/starter-template-for-prototyping-and_8.html)
