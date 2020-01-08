# Nextstrain course

This repository contains the essential files for creating a [nextstrain build](https://nextstrain.org/) for running and visualizing phylogeographic analyses of pathogen spread using genomic data.

Keep the **Author** and **License** sections, and edit the rest of this README file as you wish, creating a description of your project using the [GitHub Markdown](https://guides.github.com/features/mastering-markdown/), with topics and subtopics.

## Getting started

### 1. For windows users

Native Linux and Mac Users are all set, and can move on to step #2. Windows users, however, must install a Linux subsystem before being able to install nextstrain. Access [this link](https://nextstrain.org/docs/getting-started/windows-help) for a step-by-step guide about how to [setup Linux on Windows](https://docs.microsoft.com/en-us/windows/wsl/install-win10) (please choose 'Ubuntu 18.04 LTS'), and how to launch Linux and [create a user account and password](https://docs.microsoft.com/en-us/windows/wsl/initialize-distro) on command line.

### 2. Learning basic UNIX commands

Familiarize yourself with basic UNIX commands for navigating and managing files and folders in a command line interface (Terminal). In this environment you can perform all simple tasks you usually do using mouse clicks: copy, move, delete, access, and create files and folders. All you need to do is to type a few commands. Below you can find the main commands required to operate in a Terminal. Please access [this page](http://cheatsheetworld.com/programming/unix-linux-cheat-sheet/) to learn a few more commands. Please practice their use before the class, so that you are able to navigate from/to directories ("folders") and manage files and folders in command line interfaces.

Creating, Moving and Deleting | Navigating directories | Checking content
------------ | ------------- | -------------
**mkdir** folderX → *create folderX* | **cd** folderX → *move into folderX* | **ls** → *list files and folders*
**mv** → *move files/folder from/to another directory* | **cd ..** → *go back to previous folder* | **head** → *see the first 10 lines of a file*
**rm** → *delete files/folders from a directory* | **pwd** → *check you current directory* | **tail** → *see the last 10 lines of a file*

### 3. Installing nextstrain

[Click here](https://github.com/grubaughlab/nextstrain_course/blob/master/nextstrain_installation.pdf) to download the guidelines to install nextstrain. That document provides instructions on how to install `augur` (bioinformatics pipeline) and `auspice` (visualization tool). For more information concerning installation, visit this [nextstrain page](https://nextstrain.org/docs/getting-started/local-installation) for


### 4. Creating a nextstrain build
[Click here](https://github.com/grubaughlab/nextstrain_course/blob/master/nextstrain_tutorial.pdf) to download the course handout with a step-by-step tutorial on how to prepare your working directory (files and folders), run `augur`, and visualize the results with `auspice`. Please check [this webiste](https://neherlab.org/201910_RIVM_nextstrain.html) for more information about the distinct functionalities of nextstrain.

## Author

* **Anderson Brito & Grubaugh Lab** - [WebPage](grubaughlab.com) - grubaughlab@gmail.com

## License

This project is licensed under the MIT License.
