### GitHub - GitLab
[Short Explanation Video:Nathan Heckman Developer IBM Cloud](https://www.youtube.com/watch?v=wpISo9TNjfU)
[How to Commit Code](https://www.youtube.com/watch?v=SWYqp7iY_Tc&t=11s)
### What is Git?
**Version Control System (VCS) for tracking changes in computer files**
- Distributed version control (Users do not have to be on the same network)
- Coordinates work between multiple developers (tracks every change made on the system)
- Who made what changes and when
- Revert back at any time
- Local & repote repos
**Concepts of Git:** 
  > [Windows download](http://git-scm.com/download/win)  
 [Mac download](http://git-scm.com/download/mac)
- Keeps track of code history
- Takes "snapshots" of files
- User decides when to take a snapshot by making a "commit"
- User decides when to view any snapshot
- User can stage files befoe committing

>Example of use: 
- Let's say you work for a International Goodnews publication company and you're tasked with building a New Project Task app. 
- You would need a Team of Developers. 
  How could they all: Write code at the same time on the same codebase or project without conflict? 
  **_Well, that's where Git GitHub and GitLab come in._** 
  - What is needed is Version Control offered by the Cloud Based GitHub/GitLab a **_Hosted Service_**
  
>**Special Note about GIT:** **_So where Git is actually the underlying system that runs on your local machine, GitHub or GitLab is hosted maybe in the cloud or hosted via the web._**
> Background Information:  You may know GitHub or GitLab as a very diverse community open source community where developers from all over the world can work together and collaborate on different code or projects. 

  How do GitHub and GitLab work together?
  GitHub or GitLab as a very diverse open source community where developers from all over the world can work together and collaborate on different code or projects.
  - Allows you to track your changes
  - The system resides in a state (version). This version or state allows tracking exactly what changes were made at anytime by any member of the product team.

  >The historical state or version is basically a snapshot in time of the working system
  One can make changes on top of a prvious version
  
  **Benifits** 
  So if you introduce a bug or or mess something up, you can always go back with the historical backup that it provides.And revert those changes. 
 -  GitLab/Hub allows a team of developers to actually work on the same code simultaneously and then merge their changes in together to make progress on a project. 
 - Git is typically where the user interacts with using the command line on their local machine, versus GitHub is on the web.
 - It's a website, that's how you interact with GitHub and GitHub

 ### Truck Based Development 
 What is truck like Development?
   And you as a developer, maybe you want to branch off of that main branch of code, make some changes, and then merge your code back into that main branch. Another developer has code changes that branches off of the main branch. These changes have to then be merged back into that main branch. 

 > **That's trunk based development.**

 Example: New Term: Repository
 > Defined: A place to store code and changes to code, and is hosted on the cloud on GitHub. 

**Steps to work on code using Local Machine:**
 1. User is working code housed on a local machine
 2. User creates a clone of the main code 
 3. The repo on the local machine is called a clone
 4. The copy of the main code truck now is on the local machine
 5. The copy is now called a branch. 

 **Steps to merge code using to cloud based GitLab/GitHub**
 1. Once code is completed on local machine (Branch)
 2. User will submit a "Commit" comand to upload code to the cloud
 3. The repo of changes is then refered to as "Pushed" to the cloud
 **Special Note** If other changes happened to the main trunk of code while this branch was being changed and the code is submitted or "Pushed" the user will see a "Merge Conflict". 
 - A reviewer will look over the change conflicts
 - Submit ideas for corrections
 - Approve the newly updated code which now has no conflicts
 - Or find revert the code back prior to any of these later changes and start the commit process over

 > **Nice to Know:** GitLab/GitHub Always has a state (version) that tracks exactly what changes were made at anytime. 

> **Main Idea:**
 GitLb/Hub:Allows a team of developers to work on the same code simultaneously and then merge their changes in together to make progress toward the final product. 

 - **Git:** The user interacts with Git using the command line on a local machine.
  - **GitHub and GitLab:** Are fundamental to developing applications as a team of developer