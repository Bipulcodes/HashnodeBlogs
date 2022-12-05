# Git-The version controller

Git is a version control system, that makes our life moreover a Software engineer's life better by more organising it.

**How to install git?**

Just go to this website [git](https://git-scm.com/downloads)(https://git-scm.com/downloads) and choose your version accordingly like if you are a windows user. If you are a Mac or Linux user you don't have to worry about the downloads because Mac and Linux already contain git. After installation just check with the below command

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1670131218964/d6bf0e57-7d0b-4366-b425-0f4833d1e9d1.png align="left")

There are some major components in this git such as:

**Repository**: This is a folder kind of thing if you want to make it relatable to day-to-day life, But yes this is an important thing for git to track. This contains a major file called ***.gitignore*** . Some of us might think that what is the magic by which git can do this wonder? So the answer is by using ***.gitignore*** this is a pointer kind of thing that always points out if there is any kind of changes in the file. To make this repository you just have to create a folder and then after then open the folder with gitbash and type the below command like this:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1670131543419/291e93ad-256d-4172-8068-df3a6c5b27ce.png align="left")

before

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1670131612715/8249ebca-d0f4-43d7-8d6e-0421f26bcadd.png align="left")

After the git init command

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1670131791369/e9519253-a284-4328-94e5-4a56e6121089.png align="left")

**Git <mark>add</mark> command:**

By this command, we are allowing git to fetch my changes if there are any. To remember you can imagine you are attaching a CCTV camera to a room 😂. Let's apply this command To specify a file to add in this staging area use this bellow command

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1670132360068/77df435c-5712-4e91-8745-f0912098c756.png align="left")

To add all the files in this staging area

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1670132522881/70368515-2b58-404e-bbd7-42362d1399d4.png align="left")

**Git <mark>commit</mark> command:**

By this command, we can record the changes made to the files in a local repository. each commit has a unique ID by this unique id we can fetch this thing. It is always preferred that you should always give a commit message. You can also apply this command like the one below.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1670133325907/2441bd47-e61d-4e86-bb56-14b70c6e3ce4.png align="left")

**Git <mark>status</mark> command:**

This command returns the current state of the repository.

*git status* shows the current working branch. If a file is in the staging area, but not committed, it shows with git status. Or, if there are no changes it’ll return *nothing to commit* you can also apply like this

If there are no changes

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1670133950418/f7442990-22d6-4a75-a33b-65d4ddcc41ee.png align="left")

If there are any changes

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1670134123578/c87cefc5-ae72-4960-8b54-ea6492bd5df9.png align="left")

**git config command:**

With Git, there are many configurations and settings possible. *git config* is how to assign these settings. Two important settings are user ***user.name*** and ***user***[***.email***](http://user.email). These values set what email address and name commits will be from on a local computer. With *git config*, a ***\--global* flag** is used to write the settings to all repositories on a computer. Without a ***\--global* flag** settings will only apply to the current repository that you are currently in.

Global Command -

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1670135406070/8eeedeed-1c39-4e1f-b8a0-174ef3998910.png align="left")

Local Command:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1670135461516/0519de8e-a556-4b9e-8fac-635178c0c1f7.png align="left")

**git <mark>branch</mark> command:**

To determine what branch the local repository is on, add a new branch, or delete a branch. You can apply like this.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1670138963017/aad813b4-b1df-4134-99fd-853ac83d16e4.png align="left")

the way you can play with this command

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1670139056181/53089c7d-d4e9-4f7d-aa7b-727f53753ac8.png align="left")

**git <mark>clone</mark> command:**

To create a local working copy of an existing remote repository or if you want to collaborate with someone, use *git clone* to copy and download the repository to a computer. you can play like this

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1670139287345/7072b464-e512-4fa6-82e1-27e3bfc873a6.png align="left")

### git <mark>push </mark> command:

Sends local commits to the remote repository. *git push* requires two parameters: the remote repository and the branch that the push is for.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1670139409776/2418370a-b3db-4b64-afd3-15dacfdeab44.png align="left")