
![Image](http://tw.greywool.com/i/1RbjL.jpg)
# Hierarchical Modeling: Modeling and Animating a Quadruped Animal
This project is for demonstrating the basic animation and object modelling with WebGL. Please don't mind my horrible horse model. I didn't have any time to create it in 3D

## About

I was supposed to implement a 2-D hierarchical model for modeling and animating a quadruped animal (e.g., dog, cat, lion, fox, wolf, tiger, cow, ship, or bunny). I used a matrix stack and the WebGL procedures (traversal algorithms) that are used to traverse the hierarchy representing the articulated figure by using the matrix stack.

Essentially, I wrote a sequence of function calls with appropriate transformations and transformation parameters and when I execute that segment, it should produce a hierarchical model of the quadruped animal. When we change the model parameters, it should behave accordingly. I also animated my models by changing the model parameters gradually. The animations are user-specifiable and they are not hard-coded in program.
It has a user interface to display and animate model. Also defined some buttons/sliders for giving transformation parameters for joint angles, and so on. You should easily be able to give a posture to your character using interface and set up an animation using the interface by defining keyframes of an animation. You could save your animations in the form of keyframes (joint parameters) so that you can load and play different animations. I also implemented save/load procedures for this purpose.
