# SudokuMorphedIntoPhysical3D

First make a demo in [threeJS](https://three.js/), but then make it physical:

A giant multi-color LEDcube (not 9x9x9 LEDs but 4x4x4 for practicality, placed on the corners of 3x3x3 cubes) is used as another way of representing state of a Sudoku being solved. Every LED has 4 possible states (colors):
- this is still an option
- this is no longer an option
- this is the solution
- logical inconsistency

With giant I mean something you can climb through. When you tap the LED it changes from option to no longer an option. When you hold it longer it goes from option to solution. 

I wonder
- if it's fun to play
- how people cooperate
- if people figure out the logic if you don't tell 'm it's a representation of Sudoku

plus: Sudoku is a nice problem to practice parallel programming/logic on, and this cube a nice thing to shape the rather low-level circuitry around.

