# Progress-Bar

This C program simulates the progress of multiple tasks by displaying real-time progress bars in the terminal. 
It creates up to ten tasks, each with its own randomly assigned step value that determines how quickly it progresses. 
The progress for each task is updated every second and shown as a horizontal bar made of `=` characters, giving a visual representation of how much work has been completed.
Each task starts from 0% and updates until it reaches 100%. The screen is cleared before every update to give the appearance of animation, and the progress bars are redrawn with their updated values. 
The simulation continues running until all tasks are marked as complete. Once everything finishes, a message is printed to indicate that all tasks are done.
The code uses a simple `struct` to store task-related information and includes functions to clear the screen and print each progress bar. 
It’s also compatible with both Windows and Unix-like systems, thanks to a platform-specific check in the `clear_screen` function. 
This project is a fun way to practice working with arrays, structs, loops, and basic terminal animation using C.


