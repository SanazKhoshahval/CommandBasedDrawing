Turtle Graphics Simulator
Overview: This Turtle Graphics Simulator is a C-based project designed to demonstrate the fundamental concepts of graphical command execution and state management within a two-dimensional space. The application simulates a "turtle" that moves on a grid based on a series of command inputs that dictate movement direction, pen position (up or down), and drawing operations.

Functionality:

The turtle starts at the top-left corner of a grid (floor), facing south with its pen lifted.
Commands are processed sequentially to move the turtle across the floor to draw alphabetic characters and patterns.
The simulator uses command arrays to control the turtle’s actions, including moving forward, turning left/right, lifting/dropping the pen, and displaying the grid.
The program ensures that the turtle does not move outside the predefined grid boundaries and efficiently handles commands that would lead the turtle off the grid.
Features:

A robust command processing system allowing complex drawing instructions.
Boundary checking to prevent out-of-bounds errors and ensure graceful handling of edge cases.
A visual display of the grid after the turtle completes its drawing tasks, showcasing the final pattern.
Optional advanced features for testing the system's robustness and the turtle's boundary awareness.
How to Run:

Compile the C source files using a standard C compiler like GCC.
Run the executable and observe the output pattern printed on the console.
Use Case: Ideal for educational purposes to demonstrate control structures, arrays, and basic graphics rendering in C programming. It also serves as an engaging way to visualize algorithm paths and command execution sequences.
