cs012_programs
===================

A repository containing executable programs utilized in CS 012 or CS 012v at 
University of California Riverside. Each executable program is intended for 
use with the online IDE Cloud 9: https://c9.io.

To utilize these executables please clone this repository into a new or current
Cloud 9 workspace. To create a new one just utilize the clone from a URL option
when creating your new workspace.

Once the workspace is created, you can utilize two terminal commands. The first
will pull all new files or modifications and incorporate them into your
Cloud 9 workspace. The second will reset all files you have modified to the 
versions that exist in the primary repository (overwriting without confirming).

* git pull
* git checkout -f



Executing a Program
===================
The ".out" files are the executable files.  So to run an executable named a.out
we type:

run a.out
OR 
run a.out 10

The second run command executes the program for 10 seconds. This is useful when 
the program requires user input and takes longer than 5 seconds to execute.


To go back to the top level home directory we utilize an aliased command "home".

home
