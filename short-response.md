1. If you are collaborating with a classmate what is the first thing that each of the team members needs to do? Why is it important to do this step?

Each team member would need to create a branch to work in. This step is important because working in this way and using pull requests when merging your branch will help to catch any potential bugs or issues in your work, and you would also not interfere with the main branch while you are working.

2. Why do developers use branches?

Developers use branches in order to not interfere with the main branch when working. This is helpful becuase if someone was working in the main branch, it would probably interfere with others abilities to work, and if there was an issue made in the main branch, it would be much harder to fix and correct compared to an issue made in a branch. Errors are also much easier to catch when using branches because you often have others review and add comments on your work before merging into the main branch.

3. What is git? What is github? How does git and github work together?

Git is a command line tool that allows you to track and manage changes to your code, or version control. Github is a web based platform to store repos in the cloud and collaborate with other developers. Git and github work together because github uses git to manage and track changes made to code stored in github, allowing developers to go back to previous versions of their code and see what changes were made.

4. What is wrong with the following command sequence? What should be the correct command sequence?

```
git commit -m "saving work"
git add .
git push
```
The command sequence uses git commit -m "saving work" before git add., which would be incorrect as you have to use git add . before git commit as git commit is used to add a message to your work which you added with git add .. The correct command sequence would be:
```
git add .
git commit -m "saving work"
git push
```