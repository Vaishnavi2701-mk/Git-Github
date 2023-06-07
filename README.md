# Git-Github
This repository dives deep into git and github concepts. Cheetsheet is available and everything is explained from basic to advance!

<h1> What is Git? </h1>

By far, the most widely used modern version control system in the world today is Git. Git is a mature, actively maintained open source project originally developed in 2005 by Linus Torvalds, the famous creator of the Linux operating system kernel. A staggering number of software projects rely on Git for version control, including commercial projects as well as open source. Developers who have worked with Git are well represented in the pool of available software development talent and it works well on a wide range of operating systems and IDEs (Integrated Development Environments).

Having a distributed architecture, Git is an example of a DVCS (hence Distributed Version Control System). Rather than have only one single place for the full version history of the software as is common in once-popular version control systems like CVS or Subversion (also known as SVN), in Git, every developer's working copy of the code is also a repository that can contain the full history of all changes.

In addition to being distributed, Git has been designed with performance, security and flexibility in mind.


<h1> What is GitHub? </h1>


At a high level, GitHub is a website and cloud-based service that helps developers store and manage their code, as well as track and control changes to their code. To understand exactly what GitHub is, you need to know two connected principles:

Version control
Git


<h3> What Is Version Control? </h3>
Version control helps developers track and manage changes to a software project’s code. As a software project grows, version control becomes essential. Take WordPress…

At this point, WordPress is a pretty big project. If a core developer wanted to work on one specific part of the WordPress codebase, it wouldn’t be safe or efficient to have them directly edit the “official” source code.

Instead, version control lets developers safely work through branching and merging.

With branching, a developer duplicates part of the source code (called the repository). The developer can then safely make changes to that part of the code without affecting the rest of the project.

Then, once the developer gets his or her part of the code working properly, he or she can merge that code back into the main source code to make it official.

All of these changes are then tracked and can be reverted if need be.

<h3> What Is Git? </h3>
Git is a specific open-source version control system created by Linus Torvalds in 2005.

Specifically, Git is a distributed version control system, which means that the entire codebase and history is available on every developer’s computer, which allows for easy branching and merging.

<h3> What Is GitHub? </h3>
GitHub is a for-profit company that offers a cloud-based Git repository hosting service. Essentially, it makes it a lot easier for individuals and teams to use Git for version control and collaboration.

GitHub’s interface is user-friendly enough so even novice coders can take advantage of Git. Without GitHub, using Git generally requires a bit more technical savvy and use of the command line.

<h1> Why we use Git & Github? </h1>

Git and GitHub are widely used in software development for version control and collaboration. Here's why they are popular:

1. Version Control: Git is a distributed version control system (DVCS) that allows developers to track changes in their codebase over time. It enables them to create multiple branches, experiment with new features, and merge changes seamlessly. Git keeps a complete history of all changes made, making it easier to revert to a previous state if necessary.

2. Collaboration: Git provides a platform for collaboration among developers working on the same project. Multiple developers can work on different features simultaneously without interfering with each other's code. They can merge their changes together using Git's merging capabilities.

3. Code Backup and Recovery: Git allows developers to keep a backup of their code on a remote server, which helps protect against data loss. If a developer's local copy of the code is lost or corrupted, they can clone the repository from the remote server and resume their work.

4. Branching and Forking: Git's branching model enables developers to create separate branches for different features or bug fixes. This allows them to work on independent tasks without affecting the main codebase. Forking is a feature of GitHub that allows developers to create a copy of a repository under their own account. They can make changes to the forked repository independently and propose those changes back to the original repository through pull requests.

5. Open Source Collaboration: GitHub, a web-based hosting service built around Git, has become a hub for open source projects. It provides a platform for developers worldwide to contribute to open source projects by submitting pull requests and participating in discussions. GitHub has social features like issue tracking, project management, and documentation, making it easier for developers to collaborate and coordinate their efforts.

6. Code Reviews: GitHub facilitates code reviews, where developers can review each other's code before merging it into the main codebase. Code reviews improve code quality, catch potential bugs, and provide an opportunity for knowledge sharing and learning among team members.

7. Community and Visibility: GitHub fosters a vibrant community of developers who can discover and explore each other's projects. It promotes visibility for individual developers and allows them to showcase their work, making it easier to find job opportunities and collaborate on interesting projects.

<h1> Download Git </h1>
Download git on you computer/laptop from a link below 👇

https://git-scm.com/downloads

<h1> Download GitHub </h1>
Download GitHub on you computer/laptop from a link below 👇

https://desktop.github.com/

<h1> Some basic linux commands </h1>

1) git :  it displays a list of available Git commands and their descriptions. This serves as a quick reference for using Git in the command-line interface.
2) ls : it will list out all the directories in particular folder
3) mkdir : if we want to create a directory in a specific folder then we can use this command, eg; cd Desktop, ls, mkdir project
4) cd : (change directory) this command redirect us to a particular folder or file
5) git init : there is a repository named "git" (hidden file) is provided by git to every folder which saves all the history and modification we made in a project, it is saved as .git, by doing "git init" we initialized empty repository.
6) ls -a : it means show all the hidden files.
7) ls -git: it will show everything inside git folder
8) touch "name.txt" : this creates new file named "name.txt"
9) rm -rf : which stands for "remove recursively and forcefully" that is used for forcefully removing files.
10) git status : this command is used to track untracked files and modification we have made in a repository.
11) git add . : this command is used for staging the changed we have made, here "." means it is instructing to stage each and every file we have made inside a specific repository.
12) git add name.txt : this command is used for staging particular file changes, eg; here it is staging a file named "name.txt".
13) git commit -m "any message you have to write about a commit" : after staging the changes you have to commit them for which this command is used and after -m we can provide any message related to our commit in " ". 
14) vi name.txt : this command will redirect you to a specific file mention there to make changes.
15) cat name.txt : by using this command we can see the content inside a file.
16) git restore --staged name.txt : we can use this command to unstage the changes we have made by mistake before commiting it.
17) git log : this command help us to see all the history of commits we have made including author (who made the commit), a file name( where they made a commit), what changes they have done and time when they made those changes
18) git reset f4567ce56f005634ff34be6543825e78b45a8976 : consider that we have commited smething which we want to remove, so we have to copy a hash ID of a commit below that and run this command; for an eg, there are 3 commits (commits are staged above each another) they are arranged in a way 3,2,1 so if we want to delete 3rd and 2nd commit we have to reset ID of a 1st commit. If we do "git status" then these 2 commits are said to be untracked in description.
19) git stash : if we want to make some changes in our repository but we dont want to commit them and dont want to lose them at a same time then we can use "git stash" for baking up those changes after staging.
20) git stash pop : if we want to see those changes which we have backed up; we can use this command.
21) git stash clear : if we want to delete those changes who were baked up and not commited; we can use this command.

<h1> Creating a new repository </h1>

<h4> Step 1 </h4>
As soon as you created your account on GitHub there will be your profile visible on the top right corner and just beside that there will be a "+" icon; click on that icon and you will get an option of "New Repository".

<h4> Step 2 </h4>
Click on that "New Repository" option and give a name to your repository and there will be an option for you to make it "Public" or "Private"; after that click on "Create a Repository" button.

<h1> Connecting Remote repository to Local Repository </h1>
When we create a specific repository on GitHub then it is termed as "Remote Repository" and when we create a repository/folder on our local machine then it is termed as "Local Repository". There will be a situation when we want to connect our remote repository to local repository to work with it on local machine that time we will use some git commands as follows;</br>

</br>git remote add origin your_remote_repository_url</br>

The term "origin" is a convention used in Git to refer to the default remote repository. It acts as a reference to the remote repository's URL, allowing you to easily interact with it using Git commands.

If I will do : git remote -v 

It will show all the url's connected with local repository.

<h1> Pushing the changes into remote repository </h1>

There are three main steps while modifying a remote reository in which first we have to stage the changes, second is we have to commit those changes but these changes will reflected only after we push them. Let's take a look how we push our commits;

git push origin master</br>

Here "master" is a name of default branch but we can manipulate the branch name as per pur need.

<h1> What are branches? </h1>
Branches are parallel version of a repository's codebase. It allows developers to work on different features, bug fixes, or experiments in isolation without affecting the main codebase. Each branch represents an independent line of development with its own commits and history.
There is always a main branch which is the default branch in a GitHub repository often named "main" previously known as a "master". It represents the primary branch where the stable and production-ready code resides.  After a branch's changes have been merged into the main branch or are no longer required, the branch can be deleted. Deleting branches helps keep the repository clean and reduces clutter.


<h1> Why we use branches? </h1>
1. Independent Development: Branches allow developers to work on different features or bug fixes independently of each other. Each branch represents a separate line of development, enabling developers to focus on specific tasks without interfering with the main codebase or other ongoing work.

</br>2. Code Isolation: By creating a branch, you can isolate your changes from the main codebase until they are ready to be merged. This isolation helps prevent conflicts and ensures that the main codebase remains stable and unaffected by ongoing development work.

</br>3. Parallel Development: Branches enable multiple developers to work on different features or issues simultaneously. Each developer can create their own branch and make independent changes without stepping on each other's toes. This promotes collaboration, speeds up development, and improves productivity.

</br>4. Code Reviews: Branches facilitate the code review process. When you create a branch for a specific task or feature, you can share it with others for review. Peers or team members can review the code, provide feedback, and suggest improvements before merging the branch into the main codebase.

<h1> Learn Git Branching (Making a new branch & switching to it) </h1>
<img width="1440" alt="Screenshot 2023-06-07 at 10 50 09 AM" src="https://github.com/Vaishnavi2701-mk/Git-Github/assets/89184872/d98309e8-b441-495a-af6a-d9a8fd978600">

</br>In the image shown above it is clearly visible that how branches resides on top of each other. After certain number of commits I have created a new branch named "my_branch" as follows;

git branch my_branch </br>

Now our 'Head' is pointing towards our new branch which is represented as * just because I have passed a command;

git checkout my_branch </br>

<h3> What is Head? </h3>

"Head" refers to the current commit or the current branch you have checked out in your local repository. It is a symbolic reference as * that points to the tip of the currently selected branch. You can use "Head" as a reference to view details and information about the current commit. For example, you can use the command 'git log HEAD' to see the commit history leading up to the current commit.

<img width="1440" alt="Screenshot 2023-06-07 at 10 50 36 AM" src="https://github.com/Vaishnavi2701-mk/Git-Github/assets/89184872/6fbd5132-e4d0-4243-a3eb-b80f184a8aa6">
</br> As shown in the image abouv, you can see all the commits are gone into "my_branch".

<img width="1440" alt="Screenshot 2023-06-07 at 10 51 07 AM" src="https://github.com/Vaishnavi2701-mk/Git-Github/assets/89184872/19ca133f-c6bb-4fb7-93dc-668008b27600">
</br> Now we moved our head to "main" branch again by passing a command "git checkout main, so that all commits are gone into this branch.

<img width="1440" alt="Screenshot 2023-06-07 at 10 51 36 AM" src="https://github.com/Vaishnavi2701-mk/Git-Github/assets/89184872/2bb12a4e-1627-4f89-95e6-db98b2cc4952">
</br> As soon as we passed the command "git merge my_branch", "my_branch" is merged with "main" branch, and now all the changes we have done in the "my_branch" are visible into "main" branch.

<h1> Working with existing project </h1>
