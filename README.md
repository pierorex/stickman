OpenGL project made for a University class.
It's a stickman that is able to move some of its body parts: head, arms, legs, torso.
It is somewhat flexible as every arm and leg has 3 junctions each.

Movement:
  - Select a body part pressing one number between 1-6
  - Move a segment of the selected body part by pressing a letter:
    - 'A' or 'Z': upper segment, clockwise and counter-clockwise, respectively. (head and torso only have this segment)
    - 'S' or 'X': middle segment, clockwise and counter-clockwise, respectively.
    - 'D' or 'C': lower segment, clockwise and counter-clockwise, respectively.


This uses feeglut, OpenGL and C++. It shows how to position the camera, play with the viewport,
handle translations and rotations while nesting matrixes to make independent and dependent transformations.

To compile:
  - Add freeglut's lib and include folders to your compiler's lib and include directories.
  - Compile as you would normally do.