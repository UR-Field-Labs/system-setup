# A crash course on Github
Neel: 19-05-2024

## What is Github?

Do you have folders filled with versions of digital documents: **draft.doc, draft_final.doc, draft_final_final.doc, draft_final_final_revised.doc…**

Github helps you avoid that. It is a version control software. When you write any digital document and store it on Github, you can save incremental versions of it as you go along. You can load the documents from Github onto other computers. And when you update the document on one computer, you can ensure that copies on other computers are synchronized. Github is mostly used for code development within teams.

- Store code safely.
- Distribute code.
- Maintain versions of code, and recover older versions if a newer one crashes.
- Synchronize all copies of code.

## Things to do before crash course

1. Create or log into your [Github](https://github.com/) account. 
2. Make sure you are part of the Field Lab Github organization by messaging Neel on slack with your Github user ID and the word 'Github'.
3. Download Github desktop [here](https://desktop.github.com/).
4. (Optional) Download Rstudio by following steps [here](https://posit.co/download/rstudio-desktop/). Basically, we will be creating a repository of R scripts, so you can use RStudio to run them if you want. But you don’t need this to understand Github or to follow the crash course.

## Crash Course

### Exercise 1: Create your own repository and populate it.

1. Open github.com. Click create new repository. Give it a name, say ‘test’.
2. Open Github desktop. From Settings, login to your github account.
3. From Github desktop top bar options, say ‘Clone repository.’ Look for ‘test.’ Clone.
4. Add a script.R file with a very basic R line in it e.g. ```print(3+4)```.
5. Follow the 3 github steps: add, commit, push.
    1. Add: add the files you want to update.
    2. Commit: commit to the changes you made. This puts a stamp on the changes of your code on your local machine. You can write explanatory test around it.
    3. Push: push the changes to the Github server so that your committed changes are implemented in all github copies of your code.
6. You can now go to the Github website and see the changes in your repository.

### Exercise 2: Editing from another ‘computer’.

1. On the github website, edit the script directly. Add an extra line to it e.g. ```print(‘hello’)```. Commit it. There is no need to push here because you have made changes directly to the github server.
2. On your github desktop, say ‘Fetch/pull.’ And see the file changes.
3. Add a second file *test2.R*, put some lines of code in it. Then add, commit, push.
4. See the changes on the github website.

### Exercise 3: Working as a team

1. Get into groups of 2 or 3. Designate one person as the leader.
2. Leader will make his/her repository public (at the bottom of the Settings page of the repository).
3. Leader will invite the group members as collaborators (first option on left bar of settings page of repository.)
4. Create a new file ‘story.txt’, with a line “Once upon a time there was a very lonely lion.” Add commit push.
5. Each person then adds one sentence to the story (improv style), one person at a time. Continue until each person has put in 3 sentences.
6. At the end, look at the History on your Github website to see who added what.

## Additional things to know

- Sometimes, organizations such as NTU put additional security, requiring you to connect to a Github account within the NTU organization via an SSH key. This is an added layer of security which is somewhat cumbersome. Talk to Neel if you want to fix this.
- The common way of building new code is to branch. Generally, you have a main working version of code, and each individual team member ‘branches out’ to add features. They write code on their own branch. When the code on the branch is tested, and when the team agrees that the branch should be added, the branch is then merged into the main code.
- Always keep each repository as a separate folder. It is a very bad idea to have a repository within a repository.
