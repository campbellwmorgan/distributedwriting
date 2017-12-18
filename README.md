# Distributed Writing Example

This is a proof-of-concept for multiple people contributing to separate narratives where
each git commit hash is written to the ethereum blockchain.

## Pre-requisites

### Markdown

All files are written in markdown - see [markdowntutorial.com](http://www.markdowntutorial.com) to understand how to write formatted text.

Unformatted text is just plain text.

### Git

Git is a version control system that enables multiple people to contribute to files inside a folder.
It keeps a record of every change made to every file and records who did what.

Each change is then "committed" to the shared repository. Each commit is verified by a "hash" which is a hexidecimal string
that represents all text changes made at that point.


In order to avoid editing text on the command line, you will need a git GUI (Graphical User Interface). [Source Tree](https://www.sourcetreeapp.com/) is recommended.

[This](https://www.youtube.com/watch?v=1lBdlh3AGSc) is a good introduction to using sourcetree and Git.

A more in-depth tutorial on git is [here](https://try.github.io/levels/1/challenges/1).

### Github.com

Github is the online location where this "repository" will be stored. In order to contribute to this, you will be required to create
an account with github.

### Text Editor

To edit the files in this directory you should use a text editor. Do not use word processors as they add unnecessary characters to the file.

Unless you have a specialist text editor, the simplest are:

* TextEdit on OSX (Mac)
* Gedit on Linux
* [Notepad ++](https://notepad-plus-plus.org/) on Windows


# Writing

Any user can create a text file in this folder or any sub-folder in this directory.

Ensure that you save the file as a `.md` file so that it will be formatted on github.com

Every line that you write and then `commit` and then `push` to the shared repository will be recorded
along with the time you `commit` it and your username.

See [firstCharacter.md](./firstCharacter.md) as an example
