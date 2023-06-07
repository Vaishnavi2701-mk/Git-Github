<h1>Demystifying Git and GitHub: A Guide to Efficient Version Control and Collaborative Development</h1>

In today's fast-paced world of software development, efficient version control and seamless collaboration are paramount. Enter Git and GitHub—the dynamic duo that has revolutionized the way developers work together, enabling smoother code management, easier collaboration, and enhanced project organization.

In this article, we will delve into the world of Git and GitHub, exploring their fundamental concepts, key features, and the benefits they offer to developers and teams. We'll unravel the mysteries behind version control, branches, pull requests, and much more. Whether you're a beginner looking to grasp the basics or an experienced developer seeking advanced techniques, this guide aims to equip you with the knowledge and tools to harness the full potential of Git and GitHub. Let's demystify Git and GitHub and discover how they can revolutionize the way you build software.

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


```
git 
```
This command displays a list of available Git commands and their descriptions. This serves as a quick reference for using Git in the command-line interface.</br>
```
ls
```
This command will list out all the directories in particular folder.</br> 

```
mkdir
```
If we want to create a directory in a specific folder then we can use this command, eg; cd Desktop, ls, mkdir project.</br> 
```
cd
```
This command (change directory) redirect us to a particular folder or file.</br> 
```
git init
```
There is a repository named "git" (hidden file) is provided by git to every folder which saves all the history and modification we made in a project, it is saved as .git, by doing "git init" we initialized empty repository.</br> 
```
ls -a
```
This means show all the hidden files.</br> 
```
ls -git
```
This command will show everything inside git folder. </br> 
```
touch name.txt
```
This creates new file named "name.txt". </br> 
```
rm -rf
```
This is the command which stands for "remove recursively and forcefully" that is used for forcefully removing files.</br> 
```
git status
```
This command is used to track untracked files and modification we have made in a repository.</br> 

```
git add .
```
This command is used for staging the changed we have made, here "." means it is instructing to stage each and every file we have made inside a specific repository.</br> 

```
git add name.txt
```
This command is used for staging particular file changes, eg; here it is staging a file named "name.txt".</br> 

```
git commit -m "Relevant Message"
```
After staging the changes you have to commit them for which this command is used and after -m we can provide any message related to our commit in " ".</br>  
```
vi name.txt
```
This command will redirect you to a specific file mention there to make changes.</br> 
```
cat name.txt
```
By using this command we can see the content inside a file.</br> 
```
git restore --staged name.txt
```
We can use this command to unstage the changes we have made by mistake before commiting it.</br> 
```
git log
```
This command help us to see all the history of commits we have made including author (who made the commit), a file name( where they made a commit), what changes they have done and time when they made those changes. </br> 
```
git reset f4567ce56f005634ff34be6543825e78b45a8976
```
Consider that we have commited smething which we want to remove, so we have to copy a hash ID of a commit below that and run this command; for an eg, there are 3 commits (commits are staged above each another) they are arranged in a way 3,2,1 so if we want to delete 3rd and 2nd commit we have to reset ID of a 1st commit. If we do "git status" then these 2 commits are said to be untracked in description. </br> 
```
git stash
```
If we want to make some changes in our repository but we dont want to commit them and dont want to lose them at a same time then we can use "git stash" for baking up those changes after staging.</br> 
```
git stash pop
```
If we want to see those changes which we have backed up; we can use this command.</br> 
```
git stash clear
```
If we want to delete those changes who were baked up and not commited; we can use this command.</br> 

<h1> Creating a new repository </h1>

<h4> Step 1 </h4>
As soon as you created your account on GitHub there will be your profile visible on the top right corner and just beside that there will be a "+" icon; click on that icon and you will get an option of "New Repository".

<h4> Step 2 </h4>
Click on that "New Repository" option and give a name to your repository and there will be an option for you to make it "Public" or "Private"; after that click on "Create a Repository" button.

<h1> Connecting Remote repository to Local Repository </h1>
When we create a specific repository on GitHub then it is termed as "Remote Repository" and when we create a repository/folder on our local machine then it is termed as "Local Repository". There will be a situation when we want to connect our remote repository to local repository to work with it on local machine that time we will use some git commands as follows;</br>
```
git remote add origin your_remote_repository_url
```
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

While working with existing project we have to keep in mind that we dont have an access of that particular project and we cannot make direct changes to it. There are several steps we have to follow.

<h3>Step 1: Fork a Repository</h3>
The first thing we have to do is fork a repository. On a project repository there are three options in top right corener, watch, star, fork, click on the "fork" option.

<h3> Step 2: Clone a Repository on your local machine</h3>
Next thing you should to do is clone that URL. We have to clone a project on our local machine and to do so follow a command;

git clone your_project_url</br>


<h3> Step 3: Connect upstream URL</h3>
Next thing you should to do is connect the upstream URL to local project. The URL which is linked to our account is origin URL but the URL from where we forked this project is called "upstream URL" by convention. We have already cloned our origin URL on our local machine but to connect upstream URL with out local host we have to follow a command;

git remote add upstream your_project_url</br>

<h3> Step 4: Navigate to Project directory</h3>
Next step is to navigate to a project directory.
</br>cd "repository_name"</br>
</br>npm i</br>
</br>npm start</br>


<h3> Step 5: Create a new branch</h3>
Now create a new branch where you will make all the changes by;

</br> git branch new_branch </br>

<h3> Step 6: Move HEAD to new branch</h3>
Then move the "Head" to the new_branch so that all the commits will be pushed in new_branch by;

</br> git checkout new_branch </br>
or
</br>git checkout -b my-new-branch</br>

The above command will directly create a new branch and move "Head" towards it at a same time.


<h3> Step 7: Push the changes</h3>
Now we will stage the changes, commit and push to a new branch by;</br>
</br> git add .</br>
</br> git commit -m "Relevant Message"</br>
</br> git push origin "new_branch"</br>


<h3> Step 8: Create a Pull Request</h3>
Finally navigate to your forked repository on GitHub and click on "Compare & Pull Request"  button on the top, add a relevant message if you want to and create a Pull Request.

Once you created a Pull Request admin will get a notification and after reviewing your request admin will merge your branch into main branch.

<h1> What is a Pull Request? </h1>

A pull request is a feature in GitHub (and other Git hosting platforms) that enables collaboration and code review within a Git repository. It provides a way for developers to propose changes they have made in their own branches and request that those changes be merged into a target branch, often the main branch of the repository.

<h1> How to create a Pull Request? </h1>
Follow the step number 8 in " Working with existing project " section to create a Pull Request.

<h2> Note </h2>

While creating multiple pull requests you may have noticed that once you made a pull request you cannot make another pull request by commiting on the same branch. GitHub doesn't allow you to make more that one pull request within a single branch, for every new commit or we can consider to make a new pull request we have to create a new branch.

<h1> Removing a commit from Pull Request by force pushing it </h1>

<h3> Copy the Hash ID</h2>

The first step is copying the hash ID of a commit which is below the commit we want to remove, it is obtained by doing;

git log

<h3> Remove the commit</h2>

Delete that commit by doing;

git reset HASH_ID

<h3> Stage the changes and stash them </h3>

git add .
git stash

<h3> Force Push</h3>
We have deleted the commit but we must force push this because commits are interlinked and our remote repository contain this commit which is not present is local repository.

git push origib your_branch_name -f 

<h1> Merge Pull Request </h1>

As a Project Administrator if you want to merge a pull request then there is simple methos to follow, open a GitHub account, navigate to your repository and open a pull request section where you will find numerous pull requests, open them and you will find a button below "Merge Pull Request" click on that.

<h1> Making forked project even with main project </h1>

As we dont have an access to edit the main project directly same as that the admin of main project doesn't have an access to edit our forked repository. Hence we cannot see merged changes in our forked repository. We can see a message above our forked repository as "This branch is 'n' commits behind" where 'n' denoted the number of commits.

We make it even with our upstream/main repository and there are two ways to do it. First way, we can directly fetch it by using an option in the top right corner of a repository called "fetch upstream". Second is manually we can do it, by using a command; 

git fetch --all --prune

where --all says all the branches and --prune says all the previous one we have deleted. Thereafter we have to reset "main" branch of our forked repository with "main" branch of upstream, which we will do by;

git reset --hard upstream/main 

or we can use a pull command to do this as;

git pull upstream main

<h1> Squash Commits by using Rebase command </h1>

Let's consider we have multiple commits and we want to merge those commits into one single commit then we will use rebase command as follows;

git rebase -i HASH_ID

Here, "-i" means "interactive environment" and HASH_ID is an ID of that commit above which all the commits we want to merge, eg., there are 5,4,3,2,1 commits and if we want to merge 5,4,3,2 into a single commit then we will consider a HASH_ID of 1st commit.
After this command we will get something like this 👇

pick f9ff654 2
pick c6734ee 3
pick y67rr45 4
pick be2874f 5

where we can change any "pick" to squash as "s" which means we can squash those commits into picked commit.

pick f9ff654 2
s c6734ee 3
s y67rr45 4
pick be2874f 5

It means now commit 3rd and 4th will merge into 2nd commit. To get out of it press ESC+:+x, after that it will allow you to type some message and again get out of it by pressing ESC+:+x.

<h1> Using the Hard Flag to reset </h1>

We can reset our commit by using hard flag but we must use it with caution.

git reset --hard upstream/main HASH_ID

<h1> Merge conflict and how to resolve them? </h1>

<h3> What is Merge Conflict </h3>

When more than one person try to make changes in same part of code then it will create merge conflict. And to resolve that we have to make some manual changes. 

<h3> How to resolve Merge Conflict? </h3>

When we click on "Merge Pull Request" it will show a message like "This request contains merge conflict", then click on "Resolve Conflicts" and manually make the relevant changes , click on "Marked as Resolved" and then finaly "Commit Merge".

In GitHub, creating an issue refers to opening a ticket or report to track a problem, bug, feature request, or any other topic related to a repository. Issues provide a structured way for collaboration, communication, and project management within a repository.

To create an issue in GitHub, follow these steps:

1. Navigate to the repository: Go to the repository on GitHub where you want to create the issue.

2. Click on the "Issues" tab: The "Issues" tab is located near the top of the repository page, next to the "Code" tab.

3. Click on the "New issue" button: On the right-hand side of the "Issues" page, you will find a green button labeled "New issue." Click on it.

4. Fill in the issue details:
   - Title: Provide a concise and descriptive title for the issue.
   - Comment: Write a detailed description of the issue, including any relevant information, steps to reproduce a bug, or suggestions for improvements.
   - Labels: Optionally, you can assign labels to categorize the issue (e.g., bug, enhancement, documentation).
   - Assignees: You can assign the issue to one or more individuals who will be responsible for addressing it.
   - Milestone: If your project uses milestones to track progress, you can assign the issue to a specific milestone.
   - Additional Options: GitHub provides various additional options, such as attaching files, linking related issues or pull requests, and more.

5. Preview and Submit: Before submitting the issue, preview the content to ensure everything looks correct. If satisfied, click on the "Submit new issue" button.

Once the issue is created, it becomes a central place for discussion, collaboration, and tracking progress related to the specific topic. Users can comment on the issue, offer solutions, provide additional information, or indicate that they are working on addressing the issue.

Creating issues in GitHub helps to organize and manage tasks, foster communication among project contributors, and maintain a structured workflow for resolving problems or implementing new features.

<h3> Dealing with an issue on Github </h3>

To repond an issue, we can create a related commit to resolve that and in a commit message we can add an issue ID, eg., "I have made changes in response to #4" or if we will write "I fixed #4" then it will automatically close an issue as "fixed" keyword identify that it must be close. Same as that copy the commit hash ID for a particular issue and mention it in the description box as "I have resolve this issue with a commit 5gfkhj5hhkk3427ku789e". This is much relevant because other users can check that for which commit we have resolved which issue and for which issue we have made what commit.


Git and GitHub have become indispensable tools in the world of software development. Their ability to streamline version control, enhance collaboration, and provide a centralized platform for project management has transformed the way teams work together. By adopting Git and embracing GitHub, developers can enjoy the benefits of efficient code management, simplified collaboration, and increased productivity. So, whether you're a solo developer or part of a large team, harnessing the power of Git and GitHub is a must. Embrace the possibilities they offer, explore their vast ecosystem, and unlock the potential for smoother, more efficient development workflows. 
