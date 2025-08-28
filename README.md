To-Do List Program in Python
Purpose	
The purpose of this program is to help you manage your daily tasks.
With this program, you can:
1.	View all tasks
2.	Add a new task
3.	Delete a task
4.	Exit the program
Theory of To-Do List Program in Python
Introduction
A To-Do List program is a simple application that helps users add, view, and delete tasks.
It is one of the most common beginner projects in Python because it teaches the use of loops, conditions, lists, and functions.
Working
1.	Tasks Storage
o	A list is used to store all tasks.
Example: tasks = []
2.	Menu System
o	A menu with options is displayed again and again using while True.
o	The user chooses from 1 to 4.
3.	Add Task
o	If the user chooses option 2, the program asks for a new task and saves it into the list using .append().
4.	View Tasks
o	If the user chooses option 1, all tasks are displayed using a loop (for).
o	If the list is empty, it shows "No tasks yet".
5.	Delete Task
o	If the user chooses option 3, they enter the task number.
o	The task is removed using .pop().
6.	Exit
o	If the user chooses option 4, the program prints "Goodbye" and stops using break.
Key Python Concepts Used
•	List → to store multiple tasks.
•	Loop (while True) → to keep the program running until exit.
•	Condition (if-elif-else) → to check user choice.
•	Functions like append() and pop() → to add and remove tasks.
•	Break → to stop the infinite loop.
Conclusion
The To-Do List program is a practical example of how Python can be used for daily life applications.
It helps beginners understand input/output, lists, loops, and conditions in Python.
This program can also be improved by saving tasks to a file or adding deadlines.
 

 
 
