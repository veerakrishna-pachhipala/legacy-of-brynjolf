# Legacy-of-BrynJolf

A CLI(Node.js) implementation of Legacy of BrynJolf.


## Prerequisites

1. [Node.js](https://nodejs.org) and [npm](https://npmjs.com) installed (verified with npm version 6.14.8 and Node v10.16.0).

## Installation and Basic setup
1. Clone or download this repository.
2. Install dependencies using `npm install`.
3. To build use: `npm run build`.

## How to Run:
You can strart CLI in multiple ways:
1. After Build we can use: `npm start` or `node ./dist/index.js`.
2. Without Build we can use: `npm run dev`.

## About Legacy Of BrynJolf:
  Brynjolf, a legendary thief is known to escape even from the most secure rooms. Over the years, the guards have been tightening their security.
  Fearing the future of younger thieves he decidedto start a school of Larceny.
  
  Brynjolf can move `one step`  either to left, right, up or down.He keeps going through empty space until he hits a wall or reaches the exit. If he reaches the exit he wins.The guards copy Bryjolf's direction and run in the samedirection except they don't go through the exit. Theytreat it like a wall.
  #### Symbols:
  1. **.** Means Empty Space.
  2. **G** Means Guards.
  3. **E** Means Exits.
  4. **B** Means Brynjolf(Player).
  5. **X** Means Wall.
  
 Consider Below Room:
 
               ___ ___ ___ ___
              | . | . | . | X |
               ___ ___ ___ ___
              | . | G | . | X |
               ___ ___ ___ ___
              | . | B | . | E |
               ___ ___ ___ ___
              | . | . | G | . |
               ___ ___ ___ ___


 1.  The exit is to the right of Brynjolf. He runs right and the guards do the same too. He goes out of the exit andleaves. This is how it would look: 
 
             ___ ___ ___ ___
            | . | . | . | X |
             ___ ___ ___ ___
            | . | . | G | X |
             ___ ___ ___ ___
            | . | . | B | E |
             ___ ___ ___ ___
            | . | . | . | G |
             ___ ___ ___ ___

 
 2.if BrynJolf(Player) to right,right He Reaches the Exit than means BrynJolf Won.This is how it would look: 
 
     ___ ___ ___ ___
    | . | . | . | X |
     ___ ___ ___ ___
    | . | . | G | X |
     ___ ___ ___ ___
    | . | . | . | E |
     ___ ___ ___ ___
    | . | . | . | G |
     ___ ___ ___ ___
 
 3.If BrynJolf(Player) to Up after right then Guard Will Catch BrynJolf(Player)  than means BrynJolf was Lose.This is how it would look: 
 
     ___ ___ ___ ___
    | . | . | . | X |
     ___ ___ ___ ___
    | . | . | G | X |
     ___ ___ ___ ___
    | . | . | B | E |
     ___ ___ ___ ___
    | . | . | . | G |
     ___ ___ ___ ___
 
  3.If BrynJolf(Player) to left,left,left,left then Guards and BrynJolf(Player)  are unable to Move than means game was undecided.This is how it would look: 

     ___ ___ ___ ___
    | . | . | . | X |
     ___ ___ ___ ___
    | G | . | . | X |
     ___ ___ ___ ___
    | B | . | . | E |
     ___ ___ ___ ___
    | G | . | . | . |
     ___ ___ ___ ___


 
 

