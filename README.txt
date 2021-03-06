==== COURSE ==== 

Process Oriented Programming (1DT049) Spring 2012

Department of Information Technology 
Uppsala university


==== GROUP ==== 

14 (change this to your group number).


==== PROJECT NAME ==== 

KID is dirty
Because he is playing in the MUD


==== PROJECT DESCRIPTION ==== 

A MUD (Multi User Dungeon) is a text- based online game where players 
perform actions by typing them (such as “go north” or “attack goblin”). 
The world is partitioned into zones, and each player exists in one zone 
at any one time, and can move to neighboring zones. Zones can be occupied 
by several players as well as one or more NPC (Non player characters) that 
can be interacted with (e.g. attacked).


==== GROUP MEMBERS ==== 

900406-0092 eric.arnerlov.4839@student.uu.se
910123-4194 michael.bergroth.5739@student.uu.se
910409-2672 magnus.lang.7837@student.uu.se
840526-0194 mikael.wiberg.6269@studnet.uu.se


==== MAY THE SOURCE BE WITH YOU ==== 

Everything you need to compile and run the system is included in this
directory. 

However, you might want to get the most up to date version of this
directory. 

To fetch the source code for this project type the following command:

FIRST TIME
$ git clone git://github.com/margnus1/kid-mud.git

IF ALREADY FETCHED
$ git pull

==== ERLANG VERSION ====

This software was developed and tested using Erlang R15B01.
     	      	  	    	       
==== MAKE IT HAPPEN ==== 

Using the make utility you can perform the following actions:

make         ==> Compiles the Erlang source files if necessary. 
make archive ==> Creates a gziped tar archive of this directory. 
make clean   ==> Removes all beam files and html files generated by Edoc.
make doc     ==> Generates Edoc documentation in the doc/html directory.
make start   ==> Starts the system.
make test    ==> Runs all Eunit tests.


==== TO COMPILE ==== 

To compile the project, simply type make and press enter.


==== TO RUN AND TEST THE SYSTEM ==== 

Add a short description on how to run and test your system. Here you
might give pointers to more details in the doc/final_presentation.pdf
document. 

If possible, add targets to the Makefile that can be used to start the
system (make start, make start_server, make start_client or similar as
necessary). 

==== MORE INFORMATION (optional) ==== 

 * How to get more information about your project?
 * Who is the main contact person?
 * Do you have a project home page?