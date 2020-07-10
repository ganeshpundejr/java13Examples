# Step by Step guide to push your first project on GitHub:


1) Install GIT BASH
2) Create your Accout in https://github.com/
3) Sign In into https://github.com/

Before executing below steps you must complete above mandatory step(s):

Go to Right top corner and click on + sign

New Repository
Owner / {Enter Repository Name : java13Examples}
Description : {Enter some meaningful describtion : java13Examples}
Select Repository Type : Public / Private
Initialize this repository with a README
Click on Create Repository button

It will create GIT repository

1. Check for Git Version

$ git --version 

2. Clone GIT repository

git clone https://github.com/ganeshpundejr/java13Examples.git java13Examples

3. If we are setting up the git for the first time, we can configure the git with name & email.

$ git config --global user.name "Ganesh Punde"
$ git config --global user.email "ganeshpundejr@gmail.com"

4. Initialize Git Repository

$ git init

5. Add file into GIT Index

$ git add <File_Name>  {{For Single File}}

$ git add .            {{For all the files in current Directory}}

----------------------------------------------------------------------------------------------------
[5.1] Amending a commit without changing its message

$ git commit --amend --no-edit

----------------------------------------------------------------------------------------------------
5. Check GIT status

$ git status

6. Commit changes to GIT repository

$ git commit -m "Java 13 first commit"

7. To get more information about origin. 

$ git remote show -n origin

8. Push changes to remote repository

$ git remote show -n origin

9. Git push changes to orgin master

$ git push -u origin master


******* JAVA 13 Features  *******
What is new in Java 13

<p><a href="https://openjdk.java.net/projects/jdk/13/">Java 13</a> reached General Availability on 17 September 2019, <a href="https://jdk.java.net/java-se-ri/13">download Java 13 here</a> or this <a href="https://jdk.java.net/archive/">openJDK archived</a>.</p>





