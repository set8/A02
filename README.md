# A02
Part 1: **Git** Basics
Install **Git**:
Download and install **Git** from here.
Configure **Git**:
Set your name and email for identification like so:
**git** config --global user.name "Your Name"
**git** config --global user.email "youremail@example.com"


Part 2: **GitHub** Setup
Create a **GitHub** Account:

If you don't have one, sign up at **GitHub**.
Create a New **Repository**:

Log in to **GitHub** and click the "+" icon to create a new **repository**.

Part 4: Working with **Git** and **GitHub**
Initialize **Git** in Your Project:

1. In your WebStorm project directory, open a terminal and run:
**bash**
**git** init

2. Use the following commands to stage and **commit** changes:
**git** add .
**git** **commit** -m "Initial commit"

3. On **GitHub**, find your **repository**'s URL and use this command to link your local **repository**:
git remote add origin <repository_url>

4. Push your local changes to **GitHub**:
**git** **push** -u origin master

5. **Branching** and **Pull Requests** (Optional):
Create **branches** for features, and submit **pull requests** on **GitHub** for collaboration.

**Glossary**

Branch: A separate line of development in Git, allowing you to work on features or fixes without affecting the main codebase.

Clone: The process of creating a local copy of a remote Git repository on your local machine.

Commit: A Git command used to save changes made to files in the repository with a descriptive message.

Fetch: A Git command used to download changes from a remote repository but does not integrate them into your current working branch.

Git: A distributed version control system for tracking changes in source code during software development.

GitHub: A web-based platform for hosting Git repositories and collaboration on software projects.

Merge: The process of integrating changes from one branch into another, typically used to combine feature branches with the main branch.

Merge Conflict: A situation in Git where conflicting changes exist in the files being merged, and manual resolution is required.

Push: A Git command used to upload your local changes to a remote repository, making them accessible to others.

Pull: A Git command used to fetch and integrate changes from a remote repository into your local branch.

Remote: A reference to a repository hosted on a remote server (like GitHub) that you can interact with.

Repository: A storage location for a Git project, containing all the files, history, and branches of a project.

Sources:

https://git-scm.com/doc

https://docs.github.com/en

https://www.jetbrains.com/webstorm/learn/
