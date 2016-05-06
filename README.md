# Creature Trainer

Hello, Trainer! Welcome to the Creature Trainer! In this world, you will encounter many different creatures in battle. It is up to you to compete and unravel the mysteries of these creatures. The challenge is one that cannot be faced alone. In order to succeed, you must work together with your own team of creatures.

## Compilation Instructions

In order to run the game, first clone the repository to your desired directory. Once you `cd` into the directory, run `make`. This will use g++ to compile all the `.cpp` files and create an output file named `creatureTrainer`. All of this is defined in the `Makefile` included in the project.

You can edit the Makefile and change this output filename to whatever you would prefer by modifying the existing `-o creatureTrainer` at the end of the compile command to `-o <Insert Your Preferred Filename>`.

For example, if you wanted to name the output file to "Pokemon", you would edit the Makefile to contain `g++ main.cpp Party.cpp PrintHelper.cpp Creature.cpp Item.cpp Battle.cpp CreatureType.cpp EECSRandom.cpp Trainer.cpp -o Pokemon`.

**Attention**: If you remove any of the `.cpp` files from the g++ command in the `Makefile`, the program will not run correctly. Furthermore, the `make` command is strict about what it needs to run commands. *Spacing is important*. If you must edit the `Makefile`, be sure to only change the output filename and nothing else.

## How to Play

You have four creatures that you can train to level up and become more powerful! They all start at level 0 once the game begins. There are in-game instructions which tell you how to operate the game. This includes using attacks, potions, scrolls, and rests to make your way to the top!

**Notice**: This game is a "survival" type game. This means that there is no boss at the end or final destination. Theoretically, you can play the game forever (evil laugh).

### Questions, Comments, Concerns?
Email me at yramocan@umich.edu.
