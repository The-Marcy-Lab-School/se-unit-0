# Introduction to the Command Line Interface

## Objectives
FWBAT...
- Understand the "flipped classroom model" and how/why we will employ it in our class.
- Configure their local development environment
- Understand the origins of the command line interface
- Navigate their local file tree using the command line interface
- Create, copy, delete, and move files and directories using the command line interface.
- Understand key file and directory naming conventions

## Vocabulary
* Interface
* Graphical User Interface

## The Why?
* We are used to navigating our technology with an **_interface_** that is visually driven.
* Our normal interfaces use analogies that feel familiar from our everyday lives. We're used to clicking on "folders", saving files to our "desktop", we "scroll", "drag", and "move" images.
* These are features of a **_graphical user interface_**, or a GUI, for short.
* Before we had GUI's, we navigated computers using text commands.
* While GUI's are more user-friendly and easier to develop foundational proficiency, the **_command line interface_** is more powerful and efficient.
* To this day, developers still use the command line interface because of it's ability to perform both repetitive and complex tasks with efficiency.
* The way that we learn in this program may feel different from what you are used to. Instead of me lecturing and sending you off to practice in isolation, I will send you off to explore in isolation and we will practice together.
  * Why? Because, I believe in your innate ability as a learner. My goal is to help you find how you best learn and to develop in your capacity as a learner. We come back together to walk the last mile and extend our learning together.

## Prerequisite
* Complete the Navigating the File System, Viewing and Changing the File System, and Redirecting Input and Output sections of [Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line) on Codecademy.

## Guided Practice

If you have finished setting up your coding environment, you should complete the practice below using your computer's command line.

If you have not finished your environment set up, you can practice using [Repl.it](https://repl.it/languages/bash).

### Directory Set-Up Code-along (15 mins)
1. Type `pwd` to see your working directory. Type `ls` to see  files. 
2. Create the following directory structure
   ```
   Reuben_Ogbonna (or Your Name Here)/
   |
   |-----my_friends/
   |      |
   |      |--kene.txt
   |      |--kenny.txt
   |      |--maya_siliman_bhattacharjee-marcantonio.txt
   |
   |-----my_fellows/
   |      |
   |      |---codenation/
   |      |    |--devonte.txt
   |      |    |--enmanuel.md
   |      |    |--carmen.md
   |      |
   |      |---music/
   |            |--anne.txt
   |            |--kirk.txt
   |
   |-----my_family/            
   ```

  **Be sure to demonstrate the following:**

    - mkdir
      - mkdir -p
    - ls
      - ls with **_options flags_**
        - ls -a
        - ls -l
        - ls -la
    - cd
      - ~
      - .
      - ..
    - touch
    - mv
      - moving a file to a new directory
      - renaming a file using mv
    - rm (-r)
    - cp
    - echo
    - cat
    - more
    - pwd

## Independent Practice (15 mins)
Recreate the following directory structure using only the command line.

```
 Your Workspace/
 |
 |-----my_interests/
 |      |
 |      |--interest1.txt
 |      |--interest2.txt
 |
 |-----my_entertainment/
 |      |
 |      |---music/
 |      |    |--artist1.md
 |      |    |--artist2.md
 |      |
 |      |---television/
 |           |--show1.txt
 |           |--show2.txt
 |
 |-----my_family/            
        |
        |---family_member1.md
        |---family_member2.md
        |---family_member3.md
```
