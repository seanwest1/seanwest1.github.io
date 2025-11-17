
---
layout: post
title: "BASH Basics"
subtitle: "Skip the Manual and Unlock Linux"
tags:
- linux, 
-cli,
- bash
author: "Sean"
---
My recent battles with Linux made it clear going through BASH again would be helpful to me.
But I couldn't imagine it being enlightening for someone else to read.

At university, they didn't just drill syntax, they showed us some basics and then made us solve problems.
That's the best way to learn anything.
Besides, there are much better written basic guides online.
The goal of this post is to encourage you to learn BASH if you have or are thinking of using a Linux machine.
To skip the tedious manual and jump straight into practical application, making the most of your Linux system through the command line.


## What is BASH?

BASH (Bourne Again SHell) is, for most intents and purposes, the language of the CLI in Linux.
The CLI (Command Line Interface) is the text-only interface with Linux, a way to use your computer using a text input, with the results returned as text.
This is opposed to a Graphical User Interface (GUI), which uses a mouse and keyboard input and is common on most consumer computers.
A more in-depth distinction would just get in the way of a useful tool.
BASH is not 100% necessary to use Linux, but it is very versatile and key to accessing what makes Linux so great.
It gives you control of your computer at a fundamental level.
With BASH, if you can perform an action once, you can automate it.
For example, you can write a script to iterate through a directory and rename or convert hundreds of files automatically.

## Why You Should Learn It
BASH's true power lies in scripting, writing a sequence of commands in a file to automate repetitive or complex tasks.
There's a level of responsibility that comes with this control, as you can break your system. However, this is usually only if you aren't careful and run commands that require administrative (root) access (like using sudo).

## My Story with Linux and BASH
My history with Linux, and inextricably, BASH, is a bit of a journey.
In my teens, I bought a computer magazine with a disk that let me make a USB to install Linux. I got an old laptop and somehow managed to set it up to use the internet via Bluetooth from the family computer. I clearly had too much spare time. It required a lot of work just to watch a DVD.

Then came a large gap until I started working.
My interactions were soured until I bought myself a Raspberry Pi.
The community around the Pi was helpful, user-friendly, and large, which made learning much easier.
Most of the commands were ready for me to copy / paste.

I learned BASH more intensely at university about two years ago.
One unit required us to securely log onto the school's network to copy over our programming assignments.
This used SSH (Secure SHell), which relies on the CLI to access other computers via a network.
It seemed a little anachronistic since all the other subjects were just drag-and-drop uploads.

My most recent encounter came from my now Linux gaming PC.
I had to use the CLI to install software to allow me to use my XBOX controllers.
It all seemed to work very well, but I had to dig around on the internet to get my answers.



## Skim the Manual and Move to Practice

The best thing to do is to learn the basics and jump in.
To torture an analogy, let's use a video game:
you need to know where you are, what's around you, and where you can go.

* **Where you are:** Type `pwd` (Print working directory).
* **What is around you:** Type `ls` (List files in the current working directory).
* **Direct where you are going to move:** Type `cd <folder-name>` (Change directory).
* **Create new paths or spaces:** Type `mkdir <new-folder-name>` (Make directory).

As you progress, you learn to use the programs in the environment, and eventually, you can navigate without thinking. In reality, you are navigating the file system, then opening files and running commands for tools other people have written. After enough time, the commands make sense.

### Here are some resources I found helpful online.

#### Interactive Practice Terminals

These let you test commands right in your browser without installing anything.
* **Terminal Temple** - A BASH terminal that gives you an easy way to practice some things without installing or signing into anything.
* **CMD challenge** - Offers progressively more challenging exercises to help you learn the commands.
* **Terminal tutor** - Has the basics of navigating around.
* **learnshell.org** - A little dense but comprehensive.

#### In-Depth Guides & Inspirational Tools
* https://itsfoss.com/hacker-like-linux-terminal-tools/ - One of my favourites.
* https://a.hollywood.computer/ - For a bit of terminal fun.


## Summary
Bash is a very versatile skill to have. It's almost essential for Linux, letting you automate and string together complex tasks. Once you get comfortable with the basics, you unlock the full power and flexibility of the Linux operating system.
