# Singularity
A coding project originally written by Brendan Rood in 2020.
Revised by Brendan Rood, Connor Hagen, and Jet Li in the Spring of 2024.

## Installation Instructions:
1: Install all included fonts in this folder. (InhumanBB.ttf)
2: Run the most recent included version of singularity. (.exe, ..., ...)

## Game Overview:
Singularity is a game inspired by SCP-079, in which you embody a computer attempting to destroy the viruses
in your system, while also performing the functions vital to keep yourself alive.

If you'd like to read up on SCP-079, more info can be found here: http://www.scp-wiki.net/scp-079

## Game Instruction:
Once you start the game you will be presented with 28 rectangles, each holding a character within. These represent
the servers you have access to. The game starts with a configurable number of viruses hidden throughout your
servers. You can either click on the servers or use your keyboard to type on the screen.
It costs 25 energy to press enter and what you type can do various things.
Beware! pressing backspace is one of these expensive things!

Typing any alias of the scan command, ('scrub', 'scan', 'disinfect', 'antivirus', 'check', 'clean'), followed
by a character will execute the process of investigating that server, and, if a virus is found within, destroying
it. The command will investigate whatever the last character of the provided entry is.
!!You can investigate any number of server simultaneously!!

NOTE: While a server is investigated, the user will not be able to type the corresponding key.

To represent the struggle against entropy, the user will be required to type back randomized prompts that appear
at the bottom of the screen. These prompts begin blue but fade to red as they approach their expiration. If a
prompt expires, it will do damage to your overall health.

If your health reaches 0, you lose.
If you successfully find and destroy all the viruses, you win.

There are easter eggs.

Good Luck!


## Addendum:
If you encounter significant performance issues, go to Singularity.cfg and change
"BinaryBG = True" to "BinaryBG = False"

If you are a MacOS user, you will need to execute Singularity through the terminal. 
cd into the directory where Singularity has been installed, into the /Singularity 
directory containing a directory called _internal as well as the Singularity executable, and the Config,
then enter ./Singularity to launch.
If you try to launch it through finder, the terminal window opens wherever your terminal usually starts,
rather than running the program from within the proper /Singularity directory where it can reference
its assets.