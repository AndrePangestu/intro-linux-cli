# Course 2 - Complete Intro for Linux and Command Line

# Introduction
The Linux command line is a text interface to your computer.

Also known as shell, terminal, console, command prompts and many others, is a computer program intended to interpret commands.

Allows users to execute commands by manually typing at the terminal, or has the ability to automatically execute commands which were programmed in “Shell Scripts”.

## A bit of history
The Bourne Shell (sh) was originally developed by Stephen Bourne while working at Bell Labs.

Released in 1979 in the Version 7 Unix release distributed to colleges and universities.

The Bourne Again Shell (bash) was written as a free and open source replacement for the Bourne Shell.

Given the open nature of Bash, over time it has been adopted as the default shell on most Linux systems.

## Distros Linux
Linux Distros are Linux operating systems built on the Linux kernel, plus components of a package management system. this component originates from and is GNU-style. It also includes a display or server display and its desktop environment, for use on ordinary desktop operating systems.

### > Best Distros Linux <
<ol>
  <li>Ubuntu</li>
  <li>Debian</li>
  <li>Linux Mint</li>
  <li>Elementary OS</li>
  <li>Fedora</li>
  <li>CentOS</li>
  <li>Slackware</li>
  <li>OpenSUSE</li>
  <li>Kali Linux</li>
  <li>Gentoo Linux</li>
  <li>Manjaro</li>
</ol>


# The CLI

## Basic Commands
<ul>
  <li>
    <b>pwd</b> : This command will simply print out the current working directory.
  </li>
  <li>
    <b>ls</b> : It lists the content of a given directory. The peculiarity of this command is that it supports a wide range of arguments.
  </li>
  <li>
    <b>file</b> : This command will show the kind of a file passed as argument. In the example below, we see john_file with a “.exe” extension, the file command outputs the real file kind, in this case a simple text file.
  </li>
  <li>
    <b>cat</b> : The cat command will print out the content of a text file given as argument.
  </li>
  <li>
    <b>cd</b> : The cd command, which stands for Change Directory, will change your working directory to the one passed as argument.
  </li>
  <li>
    <b>clear</b> : After some time using the terminal, your screen will look messy and confusing. To clear the screen and start all over, type the clear command.
  </li>
  <li>
    <b>cp</b> : The cp command, which stands for copy, is used to create a copy of a file/directory. To create a copy of john_file and call our copy copy_of_john_file we will use the cp command.
  </li>
  <li>
    <b>mv</b> : The mv command, which stands for move, moves a file/folder to a new location, or renames it. To rename the file copy_of_john_file to john_file_renamed we will use the mv. To move the file john_file_renamed inside john_directory we will still use mv.
  
    Note: When specifying a file in the terminal, a trailing forward-slash “/” indicates it is a directory.
  </li>
  <li>
    <b>rm</b> : This command which stands for remove. It is used to delete files, but can delete directories as well if instructed to do so.
  </li>
</ul>
