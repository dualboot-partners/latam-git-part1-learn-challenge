# Git challenge - Part 1

Let's put into practice everything learned in this lesson by working on a practical example.

## Instructions
Start by cloning this repository on your local machine and pushing it to a new repository on your github account. 

Follow the instructions given below and once you are done, create a PR from `feature-a` to `main` (as mentioned in step 6). In the comments of this PR add the answers to the questions asked below (for example: "4.a- your answer"). Then copy the URL of this PR into the box provided on the learning platform.


**All code changes must be made to the `index.html` file.**


## What you need to do

1.  Create a new branch named `feature-a`

    a. Create a commit updating the user's personal data with your own data (name, country, studies, etc). Push this commit.

    b. Change the nav bar icons for text links. Don't commit.

2.  While you were working on the previous change, you are asked to immediately work on something else, so you need to leave your work in progress for later. This code isn't ready to be committed yet, so you want to **stash** it.

3.  Create another branch from `main` named `feature-b`

    a. Create a commit updating the hero background image.

    b. Create another commit updating the user name.

    c. Create another commit updating the text of the footer.

    d. Push all previous commits

4.  Merge `feature-b` into `main`. While you were working on your branch, other devs may have merged their work into the main branch, so before merging your code, you should try to get the latest version.

    a. What commands would you use and why? What merge method would you use and why? (please answer these questions on the PR as explained in the instructions.)

5.  Now you want to go back to continue with the code stashed in step 2. Commit and push your previously stashed changes into `feature-a.`

6. You have now finished with your code from `feature-a`.

    a. Create a PR in order to merge `feature-a` into main.

    b. Conflicts happened? Solve them and prefer your code.

    c. Commit the conflict resolution changes to `feature-a` and update the PR with this commit.
