# PublicTest_IntroductionToGit
A testing repository to understund how git works

## `Key-terms` terms that we use in git alot
-  repository
-  branch
-  commit
-  merge


> __IMPORTANT__ : import git extension to your code editor to work remotly.

 
## How open a git repository (import datapath - enter commits etc)
1. Import git repository in cmd
   - go to code button and copu http link of the project
   - create a folder
   - open cmd/bash terminal into that directory
   - write the following `clone` command to import the project to your directory. 
    ```
     git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
    ```
   - press __Enter__ to actually create your own clone
    ```
    $ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
    > Cloning into `Spoon-Knife`...
    > remote: Counting objects: 10, done.
    > remote: Compressing objects: 100% (8/8), done.
    > remove: Total 10 (delta 1), reused 10 (delta 1)
    > Unpacking objects: 100% (10/10), done.

    ```
2. When all the previous process terminates, open up your project using your `code editor`.
----

# A simple cheat-sheet for GIT
----

## Glossary

_`Branch`: Branches represent soecific versiond of a repository that "branch out" from the main project._ 

_`Commit`: A commit represents a specific point in your project history._ 

_`Checkout`: Use the git checkout sommand to switch between branches._ 

_`Origin`: The origin refers to the default version of a repository. Origin also serves as a system alias for communicating with the master branch._ 

_`Pull`: Pull requests represent suggestions for changes to the branch that we work on it._ 

_`Push`: The git push command is used to update remote branches with the latest changes you or your team'members have commited._ 



## Commands

- _only the most important/basic commands_

> __``git init``__:
> Create an empty repository in the project folder


> __``git status``__:
> Display the status of modified files.


> __``git add .``__:
> Add all directory changes to staging.


> __``git log``__:
> Show the history of changes.


> __``git checkout [ branch-name ]``__:
> Switch to a branch.


> __``git checkout -b [ branch-name ]``__:
> Make a new branch and switch to it.
    _is the same as .._
> __``git branch [ branch-name ]``__
> Make a new branch and switch to it.


> __``git branch``__:
> Display a list of all branches.


> __``git branch [ branch-name ]``__:
> Make a new branch and switch to it.


# __HOW TO :__ simple patterns (command sewuence) to start.
## `$` Commit changes and push up your content
 1. git status
 2. git add .
 3. git commit -m "your informative message"
 4. git push


 ```
 $   git pull  // to get all the changes that your partener or team did 
 ```   
