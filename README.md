## GitHub workflow exercise

The goal is to give participants experience with collaboration using Git. 

An M&Ms guessing game will be coded, here a short intro:

Imagine a coffee shop and the owner wants to start a small initiative - some gamification where one can win a free coffee plus a piece of cake. 
So they prepare a jar with between 100 - 200 normal sized M&Ms (the owner knows the number) and the idea is that each client has five guesses to get the number of M&Ms correctly. 


## FIRST OF ALL:

If you use AI for coding, please stick to the very issue/ task that is given. Just solve the minimal unit as described. LLM's tend to blow up code suggestions and it might be that you're already 
solving the entire problem, which is not the idea here.

## Start

The entire game is broken down into minimal steps and for each step, an issue will be created on GitHub. It's starts as easy as setting up the main function with a print statement.

1) Pick an issue (also called ticket in certain environments)
   * Assign yourself to the issue:
       * On the right-hand side of the issue > Assignees
   * Optional: You can label it In Progress if you want to use labels to track status

2) Create a new branch
   From the main branch, create a new branch locally or use GitHub
   Use branch naming convention! like feature/add-initial-game-starting-message
   (others: bugfix/, refactor/, ...)

3) Make changes and Commit
   Update the file related to the issue, keep it as minimal as requested.
   Commit your changes and write a commit message according to issue/ ticket on GitHub (this is convention!)

4) Push the branch and open a pull request
   like: git push origin feature/add-initial-game-starting-message
   Then go to gitHub and click "Compare & pull request" to open a PR

   What is usually written there:
     * Mention the issue by writing:
         Closes #1 (auto-closes the issue when PR is merged)
     * Summarize what one did in the description
     * Request a review (if you're doing reviews)

6) Review and Merge (typically another person than steps 1-4)
     * Someone reviews the PR (could be you or a teammate)
     * Discuss suggestions in comments if needed
     * Once approved, the PR is merged into main

6) Clean up
   * Delete the branch (optional but tidy)
   * The issue is automatically closed if they used Closes #X in the PR
