# CPS 218 Chapter 2 Assignment
These are the "Review Questions" for Chapter 2.

## Question 1
What is the default shell on most Linux systems called?

a. SH<br>
b. BSH<br>
c. CSH<br>
d. BASH

### Answer
* d
    * There are other shells (such as [Fish](https://en.wikipedia.org/wiki/Fish_(Unix_shell)) and [Z shell](https://en.wikipedia.org/wiki/Z_shell)), but they aren't mentioned in the text.

## Question 2
What equivalent to the `man` command generally provides an easier-to-read description of the queried command and contains links to other related information?

a. `who`<br>
b. `man help`<br>
c. `man -descriptive`<br>
d. `info`

### Answer
* d

## Question 3
What command can you use to safely shut down the Linux system immediately?

a. `shutdown -c`<br>
b. `shutdown -r`<br>
c. `down`<br>
d. `halt`

### Answer
* d
    * If enabled on your Linux distro, then you might be able to use the equivalent `$ poweroff` command, which is also mentioned in the text.

## Question 4
What command is equivalent to the `man –k <keyword>` command?

a. `find <keyword>`<br>
b. `man <keyword>`<br>
c. `apropos <keyword>`<br>
d. `appaloosa <keyword>`

### Answer
* c

## Question 5
Which of the following is *not* a piece of information that the Fedora installation program prompts you for?
>
a. time zone<br>
b. installation destination<br>
c. firewall settings<br>
d. installation language

### Answer
* c
    * You should set up a firewall shortly after installing a Linux distribution, if this Linux system will be installed on bare metal.

## Question 6
Linux commands entered via the command line are not case sensitive.

a. True<br>
b. False

### Answer
* b
    * This differs from Windows Command Prompt, where commands are not case sensitive.

## Question 7
Which command blanks the terminal screen, erasing previously displayed output?

a. `erase`<br>
b. `clean`<br>
c. `blank`<br>
d. `clear`

### Answer
* d
    * This is a helpful command, if you are in a bare TTY environment without [tmux](https://en.wikipedia.org/wiki/Tmux).

## Question 8
When sitting at a computer running Linux, what key combination do you press to switch to a graphical login screen?

a. <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>F1</kbd><br>
b. <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>F4</kbd><br>
c. <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>F2</kbd><br>
d. <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>F7</kbd>

### Answer
* a
    * Actually the command I use on Manjaro is <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>F7</kbd>.
    * For Linux distros with GUIs yet you don't already know which TTY that the GUI is assigned to, try the function keys <kbd>F1</kbd>-<kbd>F12</kbd> in ascending order.

## Question 9
To install Linux within a virtual machine, you can specify the path to an ISO image that contains the Linux installation media within virtualization software without having to first write the ISO image to a DVD or USB flash drive.

a. True<br>
b. False

### Answer
* a
    * Installing Linux via a VM is relatively much easier than installing on bare metal.

## Question 10
After you log in to a terminal, you receive a user interface called a \_\_\_\_\_.

a. GUID<br>
b. shell<br>
c. text box<br>
d. command screen

### Answer
* b
    * This is true if you log into a TTY session.  If you use the TTY that the GUI is assigned to, then the GUI will launch if you have any display manager that shows a login screen.

## Question 11
Users enter commands directly to the kernel of the Linux operating system.

a. True<br>
b. False

### Answer
* b
    * Referring to the text, there are several critical and distinct levels before any command reaches the Linux kernel.

## Question 12
How can you protect a metacharacter (such as the `$` character) from shell interpretation?

a. Precede it with a `/`.<br>
b. Precede it with a `\`.<br>
c. Precede it with a `$`.<br>
d. It cannot be done because metacharacters are essential.

### Answer
* b
    * This can come in handy when you download YouTube videos via `yt-dlp` and the titles use non-standard UTF characters (at least to a standard keyboard in a terminal emulator session) and wish to play the download video afterward in the CLI with [mpv](https://en.wikipedia.org/wiki/Mpv_(media_player)).

## Question 13
You know a Linux command will perform a desired function for you, but you cannot remember the full name of the command. You do remember it will flush a variable from your system. Which command typed at a command prompt displays a list of commands that would likely contain the command you desire?

a. `man –k flush`<br>
b. `man –k find all`<br>
c. `man flush`<br>
d. `man –key flush`

### Answer
* a
    * It is straightforward to reference the text for this question.
    * Ironically, I can't get this command to work on Manjaro.

## Question 14
Which command displays the users who are currently logged in to the Linux system?

a. `finger`<br>
b. `who`<br>
c. `id`<br>
d. `date`

### Answer
* b
    * This is also straightforward to reference the text for this question.

## Question 15
Which prompt does the root user receive when logged in to the system?

a. `$`<br>
b. `@`<br>
c. `#`<br>
d. `!`

### Answer
* c
    * During daily usage of a personal Linux distribution that is working well, you probably won't be seeing this very often.

## Question 16
Which prompt do regular users receive when logged in to the system?

a. `$`<br>
b. `@`<br>
c. `#`<br>
d. `!`

### Answer
* a
    * This is straightforward to reference the text for this question, if you didn't have experience using Linux.

## Question 17
Which of the following refers to the third primary partition on the second SAS hard disk drive within Linux?

a. `hdb2`<br>
b. `sda3`<br>
c. `hdb3`<br>
d. `sdb3`

### Answer
* d
    * This combines a lot of attributes reference in the text, but it should be doable after laying out all the info for visual inspection.

## Question 18
Which three partitions are typically created at minimum during a Fedora Workstation Linux installation on a system with a UEFI BIOS? (Choose three answers.)

a. `/`<br>
b. `/boot`<br>
c. `swap`<br>
d. `/boot/efi`

### Answer
* a, b, d
    * Anyone who has manually created a swap file should know that the location of the swap file needs a more specific location than the choice given.

## Question 19
If you boot your computer from Linux live media, you will be able to use a fully functional Linux system prior to installing Linux on permanent storage.

a. True<br>
b. False

### Answer
* b
    * This false by default for most live versions of Linux distros, as the OS is loaded into memory and there is no persistent storage.
    * The closest that comes to this is [Tails](https://en.wikipedia.org/wiki/Tails_(operating_system)), but then again this isn't by default and you first need to set up an administrative password before enabling persistent storage.
    * Also the print version of the textbook as a typo and forgot to put the choices of true/false below this question.

## Question 20
Which of the following is not an example of virtualization software that can be used to install Linux within another operating system?

a. Oracle VirtualBox<br>
b. Microsoft Hyper-V<br>
c. Spiceworks<br>
d. UTM

### Answer
* c
    * This is straightforward if reading the text, as Spiceworks wasn't mentioned in Chapter 2 (at least in the context of running VMs).
