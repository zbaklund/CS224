# CS 224 Spring 2019 - Programming Assignment 3

For this assignment, we wrote a Python program to simulate an elevator system. For distributing passengers onto their destination floors in a predetermined movement algorithm for the elevator

## Running the program

```
python otis.py mine fast
```
* (mine) is an optional command-line argument -- When present this turns on the algorithm featuring my unique solution in optimizing the passenger to floor movement determinism.

![Elevator run with my algorithm](sample.png "Assign 3")

* (fast) is an optional command-line argument -- When present this optional argument invokes the debug off notation so the print out runs the entire algorithm through to the end and then give you move count and time statistics without having to sit through the entire operation of the algorithm through building output.

![Fast argument used](speed.png "Assign 3")

* As you can see my algorithm optimizes on the number of moves that the elvator operates over. There are less total elevator moves used in completion of traversing passengers to their asserted destination floors.

## Author

* Author: **Zachary Baklund**
* Date: April 29, 2019