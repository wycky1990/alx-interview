
Short Specializations
Average: 103.23%
0x09. Island Perimeter
Algorithm
Python
 Weight: 1
 Project will start Jun 16, 2025 7:00 AM, must end by Jun 20, 2025 7:00 AM
 Checker will be released at Jun 17, 2025 7:00 AM
 An auto review will be launched at the deadline
For the “0. Island Perimeter” project, you will need to apply your knowledge of algorithms, data structures (specifically matrices or 2D lists), and iterative or conditional logic to solve a geometric problem within a grid context. The goal is to calculate the perimeter of a single island in a grid, where the grid is represented by a 2D array of integers. Understanding how to navigate and analyze 2D arrays and apply logical operations to determine the conditions for perimeter calculation is crucial for this task.

Concepts Needed:
2D Arrays (Matrices):

Accessing and iterating over elements in a 2D array.
Understanding how to navigate through adjacent cells (horizontally and vertically).
Conditional Logic:

Applying conditions to determine whether a cell contributes to the perimeter of the island.
Counting Techniques:

Developing a method to count the edges that contribute to the island’s perimeter.
Problem-Solving Strategies:

Breaking down the problem into smaller tasks, such as identifying land cells and calculating their contribution to the perimeter.
Python Programming:

Nested loops for iterating over grid cells.
Conditional statements to check the status of adjacent cells.
Resources:
Python Official Documentation:

Nested Lists: Understanding how to work with lists within lists in Python.
GeeksforGeeks Articles:

Python Multi-dimensional Arrays: A guide to working with 2D arrays in Python effectively.
TutorialsPoint:

Python Lists: Explains how to create, access, and manipulate lists in Python, which is essential for working with a grid.
YouTube Tutorials:

Python 2D arrays and lists
By understanding these concepts and utilizing the provided resources, you will be equipped to approach the problem methodically. You’ll need to iterate over the grid, apply logical operations to identify the perimeter of the island, and account for the specific conditions described in the task. This project not only tests your algorithmic thinking but also reinforces your ability to manipulate data structures and apply logical reasoning to solve problems.

Additional Resources
Mock Technical Interviews
Requirements
General
Allowed editors: vi, vim, emacs
All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.4.3)
All your files should end with a new line
The first line of all your files should be exactly #!/usr/bin/python3
A README.md file, at the root of the folder of the project, is mandatory
Your code should use the PEP 8 style (version 1.7)
You are not allowed to import any module
All modules and functions must be documented
All your files must be executable
Tasks
0. Island Perimeter
mandatory
Create a function def island_perimeter(grid): that returns the perimeter of the island described in grid:

grid is a list of list of integers:
0 represents water
1 represents land
Each cell is square, with a side length of 1
Cells are connected horizontally/vertically (not diagonally).
grid is rectangular, with its width and height not exceeding 100
The grid is completely surrounded by water
There is only one island (or nothing).
The island doesn’t have “lakes” (water inside that isn’t connected to the water surrounding the island).
guillaume@ubuntu:~/0x09$ cat 0-main.py
#!/usr/bin/python3
"""
0-main
"""
island_perimeter = __import__('0-island_perimeter').island_perimeter

if __name__ == "__main__":
    grid = [
        [0, 0, 0, 0, 0, 0],
        [0, 1, 0, 0, 0, 0],
        [0, 1, 0, 0, 0, 0],
        [0, 1, 1, 1, 0, 0],
        [0, 0, 0, 0, 0, 0]
    ]
    print(island_perimeter(grid))

guillaume@ubuntu:~/0x09$ 
guillaume@ubuntu:~/0x09$ ./0-main.py
12
guillaume@ubuntu:~/0x09$ 
Repo:

GitHub repository: alx-interview
Directory: 0x09-island_perimeter
File: 0-island_perimeter.py
Copyright © 2025 ALX, All rights reserved.

