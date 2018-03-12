# Rubik's_Cube_Solver

The goal here is to generate a Rubik's Cube Solver
The **ultimate** goal is to generate a Rubik's cube detector that can:
    * detect the unsolved state of a cube
    * provide solutions for that cube
    * can find soltuions for a non-3x3 cube

Personal ToDos:

* **Model Generation**  
    * Make a cube object
* **Generate Moves**
    * compare 5x5 positional move vs 3x3&edge cases
* **Put this up on GitHub** Pretty self explanatory
* **Manual Solution**
    * generate an algorithm that uses solution methods:
        * Corner Method
        * [Cross Method](http://www.rossnazirullah.com/students/images/Rubiks.pdf)
* **Learned Solution**
    * create learning algorithm to find its own solution.
        * Determine which model to use (maybe forest if not NN)
        * Reward vs 
* **Object Detection**
    * run images (eventually real time video) through a selective search
    * map detected colors to location on cube 

## Fun Facts

* Center side does not move, base stuff around that.
[Rubiks Solutions](https://en.wikipedia.org/wiki/Optimal_solutions_for_Rubik%27s_Cube) info.

## Dependancies

* pandas