# SOLID-WASTE


Hello everyone!

Welcome to the project. 

To start I will give you some instructions:
1. Clone the repo:
   ```
   git init
   ```
   then
   ```
   git clone insertRepoURL
   ```
   If you have cloned the repo you have all the latest code.

Lets say now you have been working for a long time and want to **push** the code. Use the following commands:
1. ```
   git add .
   ```
   This command gathers all the files.
2. ```
   git commit -m "message"
   ```
   This command makes all the gathered files ready to be committed on the repository. In the quotation marks you write a small description to explain what changes you have made.
3. ```
   git push origin HEAD
   ```
   Finally, you push the code to the repository. The code will be pushed on the branch you were currently on.

It can happen that when you start to work after a while there may have been several changes made by the other collaborators to the repo and now you do not have the latest code on your local machine. For that purpose we will always **pull** the code before we start working. The command for that is:
1. ```
   git pull
   ```

# IMPORTANT  (branching)

Github works with the help of branches. In the start you only have the **main** branch. This main branch contains the finalise code. Whenever you start to work on something make sure you make a new branch. Now the question is how do you do that? 

The steps are as follows:

1. Pull the latest code.
2. Make a new branch.
   ```
   git branch branch-name
   ``` 
3. Shift to that branch by using the command:
   ```
   git checkout branch-name
   ```

**REMEMBER**: always check what branch you are on before you start to working other wise you can make changes to main branch which we do not want. 

Now that you have made your branch and pushed the code to that branch with the above instructions, we need to merge it with the main or anyother branch for that matter. For that purpose, the simplest method you can use is open up github on your browser. Navigate to the _pull requests_ tab and then create a new pull request. Let me know once the pull request has been created. I will check the conflicts and errors, resolve them and the merge your branch with the main. Now the main has the lastest code. 


I hope this guide will be helpful and get you started. 

Let's get this SPROJ done!


