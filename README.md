# Catch hidden bugs!

## Learning objectives

- Locate a bug using manual QA methods.
- Clone an existing repository.
- Use the git bisect command for debugging.
- Understand the importance of thoughtful, intentional problem-solving.

### Estimated time: 1h

## Exercise

In this exercise, you will **find and fix 2 bugs**.

*IMPORTANT NOTE: Read **all** instructions before you start this exercise.*

### Instructions

- Clone [curriculum-tools-buggy-restaurant](https://github.com/microverseinc/curriculum-tools-buggy-restaurant).
- Run the project on your local machine according to the instructions in its README file. _Make sure that you can open the website in your browser._

#### Bug #1
- The bug is described as:
    - **Current behavior**: as a user, when I click the "Contact" link in the navigation, nothing happens.
    - **Expected behavior**: as a user, when I click the "Contact" link in the navigation, I am taken to a page with restaurant contact information.
- Reproduce the bug in your local version of the project.
- Use the `git bisect` command to find out in which commit a bug was introduced.
- Fix the bug! ❌🐛
- Verify that the website behaves as expected after your fix.

_Note: There is no need to commit your changes now._

#### Bug #2
- The bug is described as:
    - **Current behavior**: as a user, when I open the menu page, I can see menu items overlapping.
    - **Expected behavior**: as a user, when I open the menu page, I can see menu items ordered into two columns and two rows.
- Reproduce the bug in your local version of the project.
- Use the ` git bisect` command to find out at which commit a bug was introduced.
- Fix the bug! ❌🐛
- Verify that the website behaves as expected after your fix.

_Note: There is no need to commit your changes now._

#### 5-minute long video
Once you know the solution to the two bugs, prepare a short video to demonstrate your process.

- Choose 1 bug (or both if you have the time) and record a [Loom video](https://www.loom.com/) where you:
    - Undo the changes that resolved the bug, so you're back at the initial state.
    - Show a reproduction of the bug in your local environment.
    - Use `git bisect` to locate the commit that introduced the bug.
    - Walk through the process of solving the bug.
    - Explain how you can verify that the bug is resolved.
- Your video should not be longer than 5 minutes.
- The link to the loom video should be submitted as the outcome of this exercise.

_Note: Please do not share your video or code with other students! Let them have fun with bugs!_

### Submit your exercise

[Read this FAQ for a reminder on how to submit your exercise.](https://microverse.zendesk.com/hc/en-us/articles/360061344234)

Now go to your Student Dashboard and submit your exercise.
Paste a link to the loom video you have recorded.

------

_If you spot any bugs or issues in this activity, you can [open an issue with your proposed change](https://github.com/microverseinc/curriculum-transversal-skills/blob/main/git-github/articles/open_issue.md)._

