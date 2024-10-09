# setu-mobile-game-dev-1-2024-assignment-1

## The Assignment

Provided this Tic Tac Toe game in Lua, improve, augment and add in the following categories:

|               | **Gameplay Mechanics**                                                             | **Modding Support**                                                                                         | **User Interface (UI)**                                           | **Code Quality & Extensibility**                               | **Documentation and Distribution**                                             |
| ------------- | ---------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- | -------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| **Starter**   | Basic rules implemented, games ends in draw or win                                 | Modding possible but lacks docs. Minimal mods available.                                                    | Functional but lacks user-friendliness.                           | Basic codebase structure.                                      | Limited README                                                                 |
| **Basic**     | Customizable Grid size (natively selectable, not mod)                              | Basic modding documentation. More mods available.                                                           | Clear and intuitive CLI interface.                                | Reasonably organized code. Mods external to source             | README to guide a developer                                                    |
| **Good**      | Undo, redo, score tracking/persistence, highscores, user profiles, continue game   | Well-documented modding tools. Separate from source.                                                        | Splash screens, options menu, high score UI                       | Clear, concise, encapsulated code. Class structures (or other) | User guide to aid modders                                                      |
| **Excellent** | "AI" opponent (local implementation in lua, will be graded based on effectiveness) | Modding framework documented,  inspiration of framework documented, mods that truly enhance the experience, | Modder-created UI themes.  Responds to events from event handler. | Exemplary moddable code. Coding style documented               | Deployable artefact that can run and is documented, modding process documented |


This assignment will be 30% of your final grade.

### Passing Pathway

|               | **Gameplay Mechanics**                                                                        | **Modding Support**                                      | **User Interface (UI)**                 | **Code Quality & Extensibility**                               | **Documentation and Distribution** |
| ------------- | --------------------------------------------------------------------------------------------- | -------------------------------------------------------- | --------------------------------------- | -------------------------------------------------------------- | ---------------------------------- |
| **Starter**   | Basic rules implemented, games ends in draw or win                                            | Modding possible but lacks docs. Minimal mods available. | Functional but lacks user-friendliness. | Basic codebase structure.                                      | Limited README                     |
| **Basic**     | Customizable Grid size (natively selectable, not mod)                                         |                                                          | Clear and intuitive CLI interface.      |                                                                | README to guide a developer        |
| **Good**      | score tracking/persistence, continue game, high score board (note this is reduced from above) |                                                          |                                         | Clear, concise, encapsulated code. Class structures (or other) |                                    |
| **Excellent** |                                                                                               |                                                          |                                         |                                                                |                                    |

Disclaimer: If you implement the above features/attribute poorly, you may not pass. If you implement them well you may do much better than a pass.

# Submission

1. You must use the github classroom repository and commits should be spread over time
2. The grading rubric at the end of this README must be filled in to highlight the areas you believe you deserve marks, if you do not highlight an area you may not receive marks for it
3. A video showcasing features and modding must be provided, break it into 2.  The game and modding.  Area provided below to provide link.
3. Everything must be contained in this repository
4. Moodle submission [https://moodle.wit.ie/mod/assign/view.php?id=4363102](https://moodle.wit.ie/mod/assign/view.php?id=4363102)
5. Deadline is Sunday 10th November 2023, 23:59, I will not be available on the weekend so please plan accordingly
6. Non response to issues with submission or non response to questions will result in 5% lost for each incident
7. You may be asked to attend an interview to verify your work, the likelihood of this increases if:
    1. You are not attending lab/lectures
    2. Your labs repository/submissions is way behind
    3. You do not commit over time
    4. Suspicion of plagiarism
    5. Particularly weak submission
8. The use of generative AI is not permitted to generate source code or documentation in this assignment (copilot, chatgpt, or otherwise, locally or hosted)
    1. Generative AI is an excellent tool but you risk not learning fundamental skills by relying on it too soon
9. Usage of any published source should be referenced and documented via comments, you may be asked to explain inner workings of such usages
10. You should have a separate docs directory within the repository e.g. docs/gameplay & docs/modding, docs in markdown only and rendering via github. The readme should link to these docs
11. Remember this is 30%, you could go overboard, feel free to highlight where you paid particular attention to quality over quantity or vice versa
12. Comprehension of Lua is the main objective here.  Look into how Lua is used in modding and go for a lite version.
13. You may not use a game engine, this is a Lua assignment, projects using engines will be failed

## Setup Instructions

Please fill in the following information and `commit` and `push`

* Student Number:
* Name: 
* GitHub username: 

## Installing

Maybe you could package the game?

### Lua

Required Lua 5.4.7

### Modules

```
luarocks install penlight
```

## Starting the game

To play:

```
lua src/main.lua
```

Maybe a self contained executable might help players get started

## Mods

Let's get modding.

Importantly, you should be able to add a mod without augmenting the source code.

For idea's [https://answers.microsoft.com/en-us/xbox/forum/all/minecraft-modding/f80d739e-06d0-44da-b766-144402f49f2b](https://answers.microsoft.com/en-us/xbox/forum/all/minecraft-modding/f80d739e-06d0-44da-b766-144402f49f2b)

It might be a good idea to have a directory that contains mods, and a mod loader that loads them in.

That said, as you have ideas for available mods you will likely update the source to create hook methods. So your players should be able to mod without augmenting the source.  Maybe the players don't even see the source.....

### ModPlayerIcons

Available in `src/modPlayerIcons`.

Augments the icons used per player.


## Submission
### Self Assessment Rubric

Use Markdown table extensions for visual studio code to help.

Each entry should be kept succinct.  Point to documentation where required. A table that does not render correctly will result in lost marks

|               | **Gameplay Mechanics** | **Modding Support** | **User Interface (UI)** | **Code Quality & Extensibility** | **Documentation and Distribution** |
| ------------- | ---------------------- | ------------------- | ----------------------- | -------------------------------- | ---------------------------------- |
| **Starter**   |                        |                     |                         |                                  |                                    |
| **Basic**     |                        |                     |                         |                                  |                                    |
| **Good**      |                        |                     |                         |                                  |                                    |
| **Excellent** |                        |                     |                         |                                  |                                    |


### Video Link

Part 1 (or video 1): Gameplay & features
Part 2 (or video 2): Modding
Video Link:

### Checklist

1. Final push to github repository?
2. Documentation added to repo?
3. Video links added to README?
4. Grading Rubric filled in?
5. Zip of repository uploaded to Moodle?