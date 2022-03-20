# A Guide to Open Source

An open source manual for contributing to or maintaining an open source project.

# Finding an Open Source Project

# Contributing to an Open Source Project

Once you find an issue or project that you'd like to contribute to, it's time to learn how exactly you can go about contributing. The first step to contributing is exploring the source code. Source code is the original code for the project made and maintained by the creator. This is the official version of the project’s code.
#### Licensing
Depending on the licensing of the code it will tell you what you can do with the source code. This could determine whether you can sell your version or publish it. 

Many open source projects are what is called copyleft. This means that you must maintain the same licensing on your project as the main project. Once you understand what you're allowed to do, it's time to explore.

#### Getting Source Code
You're going to want to create a local copy of the project you'd like to contribute to on your machine. This is the best way to explore the code and test the project for yourself. 

#### Git
First, you’re going to want to install git. To do this, follow these links depending on your OS

- Windows: https://git-for-windows.github.io/
- macOS: https://code.google.com/archive/p/git-osx-installer/downloads
- Linux: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

#### Cloning a Repository
Go to the repository page of the project you are interested in. There will be a button labeled code or clone. This depends on the repository site you are using. [GitHub](https://github.com) for example will have a green ‘CODE’ button. For example, click the green octo-cat in the upper right hand corner of this page to check out the repository for this project. 

Click the ‘CODE’ button and find the link to the repository. Copy this link onto your clipboard. Then you're going to want to open your command line or terminal. This depends on your Operating System. MacOS and Linux use the Unix shell and Windows uses the Command Prompt. The process is the same for both. 

__Example__
![Example of code button on Github](/images/github-example.png "Example on Github")

Open your OS’s shell. You’re going to want to change directories (folders) to where you want to put the project folder. To do this type ‘cd’ then the subsequent folders. For example, if you want to put it on your desktop, you can input ‘cd Desktop’. If you have a folder on your desktop you’d like to put it in you can do ‘cd Desktop/project’. Once you’ve reached your preferred folder you can press enter. 

The next command is 
```shell
git clone [link] 
``` 
instead of the brackets [] place your link instead. This will copy the repository files into the folder you had selected with the cd command. 

Now you’re going to want to open the folder with your preferred IDE. [VScode](https://code.visualstudio.com) is a popular option that has a lot of good features and has many extensions to make coding better. 
#### What to Do With Source Code
You can now explore and run the code for yourself locally on your machine. Your edits will be personal to your local download, for now. 

Contributing doesn't have to be just code. 

You can:
- Add features
- Fix bugs
- Create documentation
- Curate examples of the project's uses
- Restructure layout for usability
- Fix typos
- Answer questions about the project
- Start a newsletter

Your contributions to an open source project can start small  but, everything helps. Creating documentation can help new contributors better understand what they are looking at within the source code. You can document source code by creading full docuemntation sites or just add comments in the code to explain different methods and parts of it.

#### Next Steps
Before you push your changes to the main repository you’ll need to understand workflow and communication within an open source project.
 
### Workflow

Workflow allows the contributors and owners to maintain a good idea of what is happening as the project evolves over time. This is very imporant for large projects; however, even for small projects it can be good to establish good workflow habits. 

Git offers a few ways to 



# Maintaining an Open Source Project