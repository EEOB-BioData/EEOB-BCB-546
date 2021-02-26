---
layout: page
title: EEOB/BCB 546 - Software
sidebar: Software
navigation: 3
icon: <i class='fa fa-laptop'></i> 
---

# EEOB/BCB 546 Software Guide

## Unix

In order to complete computational exercises and the group project for this course, students will need access to a Unix operating system, which is the core for Mac OS X and Linux operating systems.

### Windows Users

A Unix environment can be emulated using the “​Git Bash​” program, by partitioning your hard drive and installing Ubuntu (a free version of Linux),​ or by installing Cygwin​. These solutions for PC users may not be ideal for all course exercises and we can provide access to Mac computers if you would prefer to go this route.

* Git for Windows: ​[https://gitforwindows.org](https://gitforwindows.org) 
* Ubuntu: [​https://help.ubuntu.com/community/Wubi](https://help.ubuntu.com/community/Wubi)
* Cygwin: ​[https://www.cygwin.com](https://www.cygwin.com)

## HPC-Class

Much of the work you will do for this class will be executed on the course cluster: [HPC-Class](https://www.hpc.iastate.edu/guides/classroom-hpc-cluster). To log on to this resource, you need to be on campus or use the ISU VPN. To set up the VPN, follow the instructions on the [ISU HPC site](https://www.hpc.iastate.edu/guides/classroom-hpc-cluster/access-and-login).

To get to your account on the cluster, open your terminal (Unix) or Git-Bash (Windows) and type the following in the command line, but be sure to replace `your_ISU_NETID` with your actual ISU NETID:

```bash
ssh your_ISU_NETID@hpc-class.its.iastate.edu
```

After you execute this command, you will be prompted to input your ISU NETID password. IF you enter the correct password, you will then be in your home directory on the head node of the remote machine.

HPC-Class is a cluster that uses a SLURM scheduler. So to run an analysis on this cluster, you must
submit your job using a SLURM script. There is a script generator that you can use to create this file: [HPC-Class SLURM Script Generator](https://www.hpc.iastate.edu/guides/classroom-hpc-cluster/slurm-job-script-generator).

## Text Editors 

We highly recommend that you use an advanced text editor for this course and your research. Here are some that we like:

* [Visual Studio Code](https://code.visualstudio.com/)
* vim or emacs (Unix, Mac OS X)
* [Sublime Text](http://www.sublimetext.com/) (Unix, Mac OS X, Windows)
* [Atom](https://atom.io/) (Unix, Mac OS X, Windows)
* [BBEdit](https://www.barebones.com/products/bbedit/) (Mac OS X)

For Markdown, you might like to use an application that will render the Markdown as HTML so you can see
the formatted document. There are several nice Markdown editors available (and you can also get plug-ins
for Sublime Text and Atom that can do this). 

* [MacDown](https://macdown.uranusjr.com/) (for Mac OS X only)
* [MarkdownPad](http://markdownpad.com/) (for Windows only)
* [REMARKABLE](https://remarkableapp.github.io/) (for Windows and Linux)
* [typora](https://typora.io/) (free while in beta, for all OS)
* [StackEdit](https://stackedit.io/) (an in-browser editor)

## Programming Environments

For the parts of the course when we are working on programming in R or in Python, we will require that you have a few things installed.

### R

You can work with R by writing text files or by using an IDE (interactive development environment). We recommend using an IDE (RStudio), which requires that you first install R.

* [Download R](https://mirror.las.iastate.edu/CRAN/)
* [RStudio Desktop](https://www.rstudio.com/products/rstudio/download/) -- this is a well-designed IDE for working with R

### Python

It is helpful for us all to use the same Python environment. We recommend using the all-in-one Python installer [Anaconda](http://continuum.io/downloads.html). We will also be using Python 3 for this class. Anaconda will install most of the packages we will need.

The following install instructions are from the [Data Carpentry lesson on Python](http://www.datacarpentry.org/python-ecology-lesson/).

#### Windows

* Download and install [Anaconda](https://www.anaconda.com/download/#windows)
* Download the default Python 3 installer. Use all of the defaults for installation and **make sure to check "Make Anaconda the default Python"**.

#### Mac OS X

* Download and install [Anaconda](https://www.anaconda.com/download/#macos)
* Download the default Python 3 installer. Use all of the defaults for installation.

#### Linux

1. Download the default [Python 3](https://www.anaconda.com/download/#linux) installer.
2. Open a terminal window.
3. Type
```
bash Anaconda-
```
and then press tab. The name of the file you just downloaded should appear.
4. Press enter. You will follow the text-only prompts. When there is a colon at the bottom of the screen press the down arrow to move down through the text. Type yes and press enter to approve the license. Press enter to approve the default location for the files. Type yes and press enter to add Anaconda to your PATH (this makes the Anaconda distribution the default Python).

#### Update

After downloading and installing Anaconda, it is helpful to update the packages. Do this in your terminal window.

```
conda update --all
```


## Slack

All course communication will be conducted via slack. You should have gotten an invitation to join the course slack team called **BioDataSkills** (if not, please contact one of the instructors). Please be sure to check slack regularly for course updates. It is recommended that you download the Slack desktop app ([https://slack.com/downloads](https://slack.com/downloads)), which makes it easier to stay on top of messages. 

