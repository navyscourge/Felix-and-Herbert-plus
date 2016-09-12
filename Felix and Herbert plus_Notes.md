---
title: Felix and Herbert plus - Notes for Tutors
language: en-GB
embeds: "*.png"
...

#Introduction:
This project is a tutor led introduction to Scratch. The class should be given the explanation of each step, then follow the instructions in the project. They should be encouraged to stop after completing the step, so that everyone can keep up. For those completing early, ask them to consider the related questions.

There are several concepts introduced here, although the code used is short. Ensure that the class understands what each does, and why it works. The class does not need to be able to create new programs using these concepts. Additional projects will be used to do this.

##Resources
The class should have the scratch editor open, with a new project. They should be familiar, but not necessarily proficient, with the Scratch editor. Standard graphics are used.

##Learning Objectives
+ For the Curriculum:
	+ Algorithms; the code blocks, importance of accuracy,
	+ Debug; programming errors, 'missing functionality',
	+ Understanding the logic of the program.

#Part 1: Planning { .activity }
"We are going to make a game where you control a mouse (Herbert) and a cat (Felix) chases you. If you avoid being caught your score goes up, but get caught and your score goes down. We are going to tell the computer what to do to make the game work".

"It is usually better to plan things before we start. Imagine we are organising a play. We need a stage with scenery, some actors with costumes, some sounds and the play script (stage directions and speeches). We will create a mouse, a cat, a single backdrop (background) and the instructions to make each do what we want. Refer to the Project. Do each step then wait to be told to continue".

##Part 1 checklist (see Project) { .check }

+ Select the existing sprite (a cat), change the name, shrink it a bit, move it to the centre of the screen.
+ Select the stage and choose the backdrop (background).
+ Add a new sprite, select the sprite Mouse1, change the name, shrink it (as done for Felix).

Note: we are not using sounds in this lesson, we are not editing the pictures of the cat, mouse or stage.

#Part 2: What does Herbert do? { .activity }
"We are going to control Herbert. The easiest way is to use the computer mouse as the place where Herbert should be".

##Part 2 checklist (see Project) { .check }
+ Add the script to Herbert so he follows your mouse pointer. See **code blocks** below.
+ Test your project; answer the questions (if possible).

##Code blocks { .check }
+ A script is a set of connected blocks. It must start with an `Event block`. Drag `When (green flag) clicked` into the Scripts area for Herbert.
+ Drag the `forever` block under the first block. You should see it connect.
+ Drag the `goto` block into the gap of the `forever` block. You should see it connect, filling the gap. Select the `mouse-pointer` value from the list (down-arrow).
+ Drag the `point towards` block below the `goto` block, inside the gap of the `forever` block. You should see it connect, growing the gap. Select the `Felix` value from the list (down-arrow).
+ Check that both blocks are inside the `forever` block.

##Part 2 summary
"We should now have our Stage, two actors, and Herbert doing what we want. If everyone is happy, we'll move on. Save your project".

#Part 3: What does Felix do? { .activity }
"We are going to make Felix run towards Herbert. We can make it look like Felix is running by using 2 costumes with the legs in different positions; see how that works".

##Part 3 checklist (see Project) { .check }
+ Add the script to Felix so he moves towards Herbert (as done for Herbert).
+ Use a second Costume to Felix so he appears to run (it should already be there).
+ Does this look like you have made a game?

