# Tutorial: VSCode and Git

## Prerequisites

- [GitHub](https://iraxon.github.io/tutorial-github)

## Intro

VSCode (officially, "Visual Studio Code") is our recommended integrated development environment (IDE). It is not a "training" IDE. It is a real IDE that real programmers use on real projects. For that reason, learning to use VSCode is worth your time.

> [!WARNING]
> VSCode has AI features. Do not use it for coursework without consulting your teacher.

Git is the most common version control system (VCS). A VCS saves the entire history of your code in addition to what you currently have. Services like GitHub use VCS information to properly handle multiple programmers sending changes at the same time.

## Installation

Go to [VSCode's website](https://code.visualstudio.com/Download) and download the installer for your operating system (OS). If you do not know what OS you have, you probably have Windows.

Go to your downloads folder and run the installer. Follow the prompts it gives you until VSCode is successfully installed.

Next, go to [Git's official website](https://git-scm.com/install/) and download the installer for your OS.

Go to your downloads and run the installer.

## The VSCode interface

Open VScode and take a look around. The following are the important things to know:

- Along the top of your screen, near the VSCode logo in the top left, there is the word "File." Clicking this allows you to see the "Open folder" button (near the top) and the "Close folder" button (further down). Most functions of VSCode only work when a folder is open, and some only work when there is not a folder open.
- On the left sidebar, the default option is "Explorer," which allows you to see the files in the folder you have open. (By default there is no folder open, so nothing will show up there.) This is where you can create files when you have a folder open.
- Further down on the left sidebar there is "Source control," which allows you to interact with Git. This is where you will go to save your changes and send them to GitHub.

## Extensions

VSCode allows you to add extensions. Think of these as something like a mod for a game. Unlike some other IDEs, VSCode is designed to be extended. With the right extensions, VSCode can be used for just about any programming task.

Install "GitHub Pull Requests" (it has that exact name). You should also install extensions for your preferred language if you have one.

Go to the "GitHub" tab on the left sidebar, which that extension creates, and sign in to GitHub. This is necessary to use Git properly.

## Your first repository

You now know everything you need to start up a project. Here are the steps:

1. Go to [GitHub](https://github.com) in your browser. Log in if you haven't already. Find the list of repositories on the left and click "New."
2. Write a name ("example" is fine) and a description. Note that the name you write will be **permanently taken**, so you will not be able to have another repository in the future with the same name. You *can* rename repositories, but the old name will still be occupied (it will basically become an arrow that points to the new name).
3. At the bottom, there are three options.
    1. A README file is always good to have, so toggle that on. The README is a text file where you put more information about what your project is.
    2. Select a .gitignore template for the language you use. This keeps unimportant or computer-specific files out of the repository. Don't worry if this doesn't make much sense yet.
    3. The license is a legal document that tells people what they're allowed to do with your code. Not having a license means "Nothing! Don't touch it!" The GNU General Public License v3.0 allows people to make copies or derivatives of your code only if they "pay it forward" and use the same or a similar license. The MIT License allows copies or derivatives without that caveat. All licenses require people to acknowledge that the code is your work.
4. Click "Create repository" once you're done with this.
5. Open VSCode. If you have a folder open, close it. Go to Source Control and click "Clone repository." Then, at the top of your screen, click "Clone from GitHub." Find the repository and clone it to somewhere on your computer.

Congratulations, you have set up your first repository. You will do this every time you start a new project yourself (when joining someone else's project, you will only need to do step 5).

## Your first commit

Now that you have the repository set up, you will not need to go to GitHub that much. Go to the Explorer on the left sidebar and click the new file button (it becomes visible if you mouse near the repository title near the top left). Add a file; it will be a text file. Give it whatever title and content you'd like. You may choose to give it an extension (like .txt) or not. For code, the extension will matter.

Go to Source Control. Observe that your change (adding the file) is visible there. Stage it with the plus icon on the change.

Put a commit message describing your change in the box at the top and then commit the change. Next, sync it to GitHub.

Go to the GitHub repository in your browser and observe that the file you created is now visible there. (You will not need to go check it in the future; this is just to demonstrate how it works.)
