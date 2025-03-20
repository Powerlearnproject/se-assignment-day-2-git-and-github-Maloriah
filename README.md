[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/8wgCKhpZ)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=18709525&assignment_repo_type=AssignmentRepo)
# se-day-2-git-and-github
## Explain the fundamental concepts of version control and why GitHub is a popular tool for managing versions of code. How does version control help in maintaining project integrity?
Version control is a system that assists in monitoring and tracking changes made to a file or code. 
Version control is important in that it allows multiple developers to work on the code at the same time without having to affect each others work.
It allows collaboration while maintaining code integrity during software development.
Version control helps in maintaining project integrity by :
1. Tracking changes overtime.
2. Fostering collaboration where every developer can work on the code without compromising each other's code.
3. Branching and merfing allows changes to be made separately from the main repository which protects the main repo from being compromised without surety.
4. It stores all the project activities history which helps in seeing changes made to the project, who made the changes and why the changes were made.
   
## Describe the process of setting up a new repository on GitHub. What are the key steps involved, and what are some of the important decisions you need to make during this process?

Step 1: Sign up/ sign in on github
Step 2: Create a new repository from the + sign on the top right corner.
Step 3: Name the repository.
Step 4: Choose whether to make it public or private
Step 5: Edit the read me file to add description on what your project is about and all the relevant information about about the project.
Step 6: Create files and folders for these repository either locally on git by cloning the repository to your local machine or from the online github editor.

Important decisions to make during this process is whether or not you want your repository to be private or public and whether or not to fill/edit the READ-ME file.

## Discuss the importance of the README file in a GitHub repository. What should be included in a well-written README, and how does it contribute to effective collaboration?
A READ-ME file is important in a github repository because it allows you write all the impoortant information about a project.
A well-writen README file should include:
What the project does
How useful it is
Who uses it
Who maintains it
How to get started on the project
Where and how is help needed

## Compare and contrast the differences between a public repository and a private repository on GitHub. What are the advantages and disadvantages of each, particularly in the context of collaborative projects?

Public repository - Anyone on the internet can see this repository but only those chosen to edit can edit. However, it is disadvantaged in that there is no privacy especially for sensitive projects.
Private repository - Not everyone can see or edit the repository. Only those chosen to view and edit the repository can do so. However, it is disadvantaged in that it limits collaborations and contributions.

## Detail the steps involved in making your first commit to a GitHub repository. What are commits, and how do they help in tracking changes and managing different versions of your project?

Step 1: Clone the repository to the local machine using the "git clone URL" command.
Step 2: Change the local machine's current directory using "cd name of repo folder" command
Step 3: Make updates or changes locally on the repo.
Step 4: Check the repo status, check all the files that have been added, updated or deleted and not saved yet. Use the "git status" command.
Step 5: Track all the files that have been added before saving using the "git add ." command(. means all).
Step 6: Check all the changes to be commited using the "git status" command again.
Step 7: Save the changes using the "git commit -m "initial commit"" command.
Step 8: Connect local machine to github account.
Step 9: Create a SSH key using the "ssh key gen" command to prove to github that you are the owner of your account.
Step 10: Make the changes live on the github website using the "git push origin main" command. (origin shows the location of git repo while Main/master shows the branch to push the changes to)

Commit helps in tracking changes overtime and gives a history of all the changes made, why they were made and by whom. They also allow you to go back to the different versions of the project meaning you can manage and recover mistakes easily.

## How does branching work in Git, and why is it an important feature for collaborative development on GitHub? Discuss the process of creating, using, and merging branches in a typical workflow.

Branching allows developers to work on code separately and silmutaneously without affectin the main code. It is important because it reduces risks of altering the Main branch when adding codes or making changes and is also good for collaboration.

1.Check how many branches there are using the "git branch" command. In the case that no other branches exist it will only show thw main branch. e.g *master, meaning you are on the master branch.
2.Create a new branch using the git checkout -b feature-branchname. A switch automatically from the main branch to the new branch.
3.Modify the files in the new branch
4.Check the status of the branch using the  "git status" command.
5.Track all the files added using the "git add " command.
6.Commit/save the changes using the "git commit -m "new feature"" command. The changes are only saved on branch.
7.Switch back to the main branch using the "git checkout main" command.
8.Merge the feature branch to main branch using the "git merge" command.
9.Then push these changes to github using the "git push" command.

## Explore the role of pull requests in the GitHub workflow. How do they facilitate code review and collaboration, and what are the typical steps involved in creating and merging a pull request?

Pull requests have your code pulled into another branch or to the main branch or download changes from github to local machine.
Make changes on the readme file on github
Commit the changes
Use "git pull origin command" to update the changes on the locl git.


## Discuss the concept of "forking" a repository on GitHub. How does forking differ from cloning, and what are some scenarios where forking would be particularly useful?

Forking is creating a copy of someone elses repository, enabling you to make changes without affecting the original project.
Forking creates a copy on your github while cloning creates a copy on local machine
Contributing to public repositories where you are not allowed to make changes.

## Examine the importance of issues and project boards on GitHub. How can they be used to track bugs, manage tasks, and improve project organization? Provide examples of how these tools can enhance collaborative efforts.

Project boards help in organizing tasks. Tasks or bugs can be logged in and assisgned to individual developers to work on them and the team can track the process.

## Reflect on common challenges and best practices associated with using GitHub for version control. What are some common pitfalls new users might encounter, and what strategies can be employed to overcome them and ensure smooth collaboration?

Merge conflicts: Occur when two people edit the same part of the code and try to merge it to the main branch at the same time.
Solution: Communicate frequently, and resolve conflicts promptly.
