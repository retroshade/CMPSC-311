I - Names
=======================================================================================
Ryan Mysliwiec		rwm5592
Hayley Sundra		hms5333
=======================================================================================

II - Description
=======================================================================================
wordc-mp.c 

The main program, wordc-mp, is used to read a file. The program then takes the file and 
breaks it up into n number of sections (determined by the user at runtime). The program 
then creates a pipe, along with (n - 1) child processes. Each of these processes, along 
with the parent process, will run it's own mini-sort. This is a sort of the subset of 
words in each section. After counting and sorting all the words within the mini-sort, 
the child processes will pipe back into the parent process. The parent process will take
all of these inputs from the pipes and sort them back in with its own mini-sort and 
adding the amounts of each word from each child process to the amount in its own 
mini-sort, creating one large sorted and counted file.

wordc-mp.h 

This file contains all of the library files needed, along with any and all function 
prototypes. In the file, the list list struct is defined, which contains elements for 
each word, the amount of instances of that word. The file also defines a boolean type 
that is used when searching through the linked list to see if there is already an 
instance of any particular word within that list.
=======================================================================================

III - Difficulties, etc.
=======================================================================================

=======================================================================================

IV - System Calls and Library Functions
=======================================================================================
System Calls

-

Library Functions

-

=======================================================================================

V - Design Choices
=======================================================================================

=======================================================================================

VI - Performance Results
=======================================================================================
Pangur Ban

-

Hamlet

-

Arabian Nights

-

=======================================================================================