## Git challenge

Let's put into practice everything learned by working on a practical example.

1.  Fork this repository

2.  Create a new branch "feature-a" 

    a.  Create a commit updating the user's personal data with your own data (name, country, studies, etc). Push this commit.
    b.  Change the header left icons for text links. Don't commit.

3.  While you were working on the previous change, you are asked to immediately work on something else, so you need to leave your work in progress code for later. This code isn't ready to be committed yet, so you want to **stash** it.

4.  Create another branch from main named "feature-b" 

    a.  Create a commit updating the hero background image.

    b.  Create another commit updating the user name.

    c.  Create another commit updating the text of the footer.

    d.  Push all previous commits

5.  Merge "feature-b" into main. While you were working on your branch, other devs have merged their work into the main branch, so before merging your code, you should get the latest version.

    a.  What commands would you use and why?
    
    b.  What merge method would you use and why? 

6.  Now you want to go back to continue with the code from step 3. 

    a.  Commit this change in branch feature-a

7. Merge main into "feature-a" 

    a.  What merge method would you use and why? 
    
    b.  Conflicts happened? Solve them and prefer your code.
    
    c.  Commit this merge. 
    
    d.  Push branch feature-a

8. Merge feature-a into main and then delete feature-a because we will not need it anymore.

    a.  What merge method would you use and why?

9. At this point all changes have been merged into our main branch. 

10. Now the client says that they want to go back on the header change. They prefer to leave the icons instead of the text (as it was before) so you need to undo that change.

    a.  What command would you use and why?
