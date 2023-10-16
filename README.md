To run these files you need python3 and pygame.
pygame can be installed in the home directory with the following command: python3 -m pip install -U pygame --user
I did 'pip install pygame' because I dont care if it is global.

To use tester.py you will need to update the complete paths in both the import statements of csp.py, backtracking.py, and validate.py and the file name of the main function to match your own directory structure.

To use these files the way you want you will need to modify the main function in display.py to change the board and the algorithm you want to use, and then run the script. There are some unsolved boards in /testing/boards/ if you want to try some out, or you can make your own as long as you format it as a 2d list of ints.
There are commands in the main functions already that serve as examples.

