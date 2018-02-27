This project was completed in Eclipse during my Spring 2017 semester with Aasish Basani (listed as a collaborator) for my Fundamentals of Computer Science II course. 

The directions for the game are as follows:
- To choose the size of the maze that is currently played, edit the two values for width and height of the maze in the initMaze method(the first method in the MazeExamples class)
- Once the game is running use the arrow keys to control the player square (the cyan square)
- The goal is to navigate the maze from the beginning (green square) to the end (magenta square)
- If the player is moving on the correct path the animated search will present a blue trail, but if you waver from 
 the correct path then the incorrect step will display orange 
- The incorrect steps are counted and the total number of wrong steps is displayed upon winning the game.
- If the player reaches the end, the game will end and a winning screen will be displayed
- To display the correct path before reaching the end, click b to display it using breadth first search or d using depth first search 
- To restart the game with another random maze use r

To run the game in Eclipse: 
- Download the code as a zip
- Create a new java project
- Add the two jar files as external libraries
- Create a new file in the src folder either using the Maze.java existing file or pasting it in to a new file
- Create a java application run configuration with the main class being tester.Main and for the program arguments input MazeExamples
- Run the program to play the game

