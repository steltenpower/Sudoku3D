# Sudoku3D (virtual and physical)

What if you'd turn a (simplified) Sudoku like
<img src="https://i.pinimg.com/736x/29/3d/8d/293d8d80dd44ca8d8f4acc24639d0e40--sudoku-kinder-sudoku-for-kids.jpg">
into a 3D-representation similar to
<img src="https://repository-images.githubusercontent.com/55097385/2ffa4f80-5398-11eb-9f54-8e6aaa2a3aa3">
but with horizontal distances varied a bit to show groups, where each LED is multi-colored to show if Z is the value to fill the X,Y square, maybe with: OFF=no (after tap), GREEN=yes (after hold), ORANGE=undetermined, RED=error

I wonder
- if it's fun to play
- how people cooperate
- if people figure out the logic if you don't tell 'm it's a representation of Sudoku

plus: Sudoku is a nice problem to practice parallel playing/programming/logic on, and this cube a nice thing to shape the rather low-level circuitry around.

It can be:
- virtual: http://dkobozev.github.io/webgl/led_cube/
- augmented: <iframe width="560" height="315" src="https://www.youtube.com/embed/ZI6oJJFgACM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
- physical: <img src="https://www.playgroundworld.co.za/wp-content/uploads/2019/10/1.8-CLIMBING-CUBE-1.jpg">

more links for implementation:
=========================
- https://stackoverflow.com/questions/14223249/how-can-i-set-the-position-of-a-mesh-before-i-add-it-to-the-scene-in-three-js/29175325
- https://threejs.org/docs/index.html#manual/en/introduction/Creating-a-scene
