I HATE BEES
===========

Mini game to kill bees, just move the mouse over a bee and click, this will decrease its strength

there are 3 kinds of bees: __QueenBee__; __DroneBee__; __WorkerBee__ and a massive book...

A couple of hours experimenting with JS Prototypes, HTML5 elements _<canvas>_ and _<audio>_

## Code

__Bee__ is an "abstract object"

Each _Bee_ type extends the __Bee__ prototype: __WorkerBee__, __DroneBee__ and __QueenBee__

Each __Bee__ has its proprieties and behaviour

__Game__ class is the game context: generates bees _setup_ and as a state _playing_ - should implement State Pattern here

__GameView__ renders to HTML5 current __Game__ context

You can change easily number of bees or add other types of bees

No jQuery, just plain old JS and HTML5

## Rendering

__Sprites__: There is a Image that has all the bees __beesprites.png__, extraction is made with HTML5 DrawCanvas 

## Start

just open **index.html** on your favorite html5 browser.

physics are buggy but serves as a POC
