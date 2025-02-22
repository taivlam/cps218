# CPS 218 Chapter 1 Assignment
These are the Review Questions for Chapter 1.

## Question 1
Which of the following components comprise an operating system? (Choose all that apply.)

a.  user interface<br>
b.  kernel<br>
c.  device drivers<br>
d.  services

### Answer
* a, b, c, d
    * You should be be aware that these are part of the OS from experience tinkering with Linux components before.

## Question 2
Which of the following kernels are development kernels? (Choose all that apply.)

a. 2.3.4<br>
b. 4.5.5<br>
c. 5.10-rc5<br>
d. 6.0.0

### Answer
* a, c
    * Choice (a) is using the old Linux kernel versioning of "odd minor numbers for release candidates" (for versions equal to or older than `2.5*`).
    * Choice (c) is a release candidate, indicated by the newer practice of using the `*rc` suffix.

## Question 3
Many types of software are available today. Which type of software does Linux represent?

a. open source<br>
b. closed source<br>
c. freeware<br>
d. shareware

### Answer
* a
    * Many Linux applications are primarily licensed under either GPLv2+ or MIT.
    * (You have to visually inspect for software licensing when submitting third-party Linux packages.)

## Question 4
Which of the following are characteristics of OSS?  (Choose all that apply.)

a. The value of the software is directly related to its price.<br>
b. The software is developed collaboratively.<br>
c. The source code for software is available for a small fee.<br>
d. Bugs are fixed quickly.

### Answer
* b, d
    * Regarding basic theoretical principles of Linux, these are true.
    * However, there are some well-regarded projects that are not community-based projects and/or bugs cannot be easily found, despite practices such as using GPLv3 licensing.
        * For example regarding the former, Pop!\_OS is a project run by System76.  While welcoming patches from the community for bug fixes with small scope, System76 ultimately has the ultimate power to dictate what to do regarding steering the project long-term.
        * For example regarding the latter, the Linux kernel has a massive code base, so the average Linux user isn't going to be able to audit the Linux kernel.

## Question 5
To which license does Linux adhere?

a. BSD<br>
b. MIT<br>
c. GNU GPL<br>
d. Apache

### Answer
* c
    * IIRC the Linux kernel is primarily based on the GPLv2 license.

## Question 6
What are some good reasons for using Linux in a corporate environment? (Choose all that apply.)

a. Linux software is unlikely to be abandoned by its developers.<br>
b. Linux is secure and has a lower total cost of ownership than other operating systems.<br>
c. Linux is widely available for many hardware platforms and supports many programming languages.<br>
d. Most Linux software is closed source.

### Answer
* a, b, c
    * This comes from reading the text.

## Question 7
Which of the following are common methods for gaining support for Linux?

a. websites<br>
b. Linux User Groups<br>
c. online forums<br>
d. all these methods

### Answer
* d
    * I don't know how I would feel getting support from the Arch Linux forum (but that's neither here nor there).

## Question 8
Which two people are credited with creating the UNIX operating system? (Choose two answers.)

a. Dennis Ritchie<br>
b. Richard Stallman<br>
c. Linus Torvalds<br>
d. Ken Thompson

### Answer
* a, d
    * You should recognizes these names if you've ever come across the one and only [*The C Programming Language*](https://en.wikipedia.org/wiki/The_C_Programming_Language) book.

## Question 9
On which types of systems can Linux be installed? (Choose all that apply.)

a. IoT devices<br>
b. supercomputers<br>
c. servers<br>
d. workstations

### Answer
* a, b, c, d
    * Just go to the download section for both Fedora and Ubuntu, and you'll see options for at least choices (a, c, d).
    * It's probably the same high level procedure for supercomputers -- however, not everyone has a supercomputer in their own backyard or at home.

## Question 10
Who formed the Free Software Foundation to promote open development?

a. Dennis Ritchie<br>
b. Richard Stallman<br>
c. Linus Torvalds<br>
d. Ken Thompson

### Answer
* b
    * If you have been using Linux by self-learning via the internet and yet you haven't learned this yet, then I don't know what to say.

## Question 11
Which culture embraced the term “GNU” (GNU’s Not UNIX) and laid the free software groundwork for Linux?

a. the hacker culture<br>
b. the BSD culture<br>
c. the cracker culture<br>
d. the artificial intelligence culture

### Answer
* a
    * This is straightforward and comes from reading the text.
    * At least this textbook makes the correct distinction between hackers and crackers.

## Question 12
Linux was developed by \_\_\_\_\_ to resemble the \_\_\_\_\_ operating system.

a. Linus Torvalds, MINIX<br>
b. Linus Torvalds, GNU<br>
c. Richard Stallman, GNU<br>
d. Richard Stallman, MINIX

### Answer
* a
    * This is straightforward and comes from reading the text.
    * Torvalds was the engineer, compared to Stallman.

## Question 13
When the core components of the Linux operating system are packaged together with other OSS, it is called a \_\_\_\_\_.

a. new kernel<br>
b. new platform<br>
c. Linux distribution<br>
d. GNU Project

### Answer
* c
    * This is straightforward and comes from reading the text.
    * Also this comes from familiarity with Linux.

## Question 14
Which common desktop environments are available in most Linux distributions? (Choose all that apply.)

a. GNOME<br>
b. CDE<br>
c. KDE<br>
d. RPM

### Answer
* a, c
    * This is straightforward, matching terms with what was mentioned in the text.
    * Also, the [scene](https://youtu.be/FQM5fU7V-MM) when Tyrell talks about KDE and GNOME to Elliot in [*Mr. Robot*](https://en.wikipedia.org/wiki/Mr._Robot) is deeply ingrained in my psyche.

## Question 15
Which of the following are factors that determine which Linux distribution a user will use? (Choose all that apply.)

a. package manager support<br>
b. hardware platform<br>
c. kernel features<br>
d. language support

### Answer
* a, b, c
    * Language support is somewhat not an issue (at least for common languages) -- at least there seems to be great language support when using GNOME as a desktop environment (or similar options).

## Question 16
What is a common open source web server available for Linux?

a. Samba<br>
b. Apache<br>
c. Squid<br>
d. NFS

### Answer
* b
    * Only Apache and nginx are mentioned in the text.
    * Also you might be familiar with both terms if you have watched Linux YouTube videos.

## Question 17
Which of the following components is required to run Linux virtual machines?

a. container runtime<br>
b. desktop environment<br>
c. hypervisor<br>
d. orchestration software

### Answer
* c
    * You definitely have seen the word "hypervisor" if you spent more than 10 minutes reading the Qubes OS documentation.

## Question 18
Which of the following Linux distributions is likely to be used by a cybersecurity worker?

a. Fedora<br>
b. Ubuntu<br>
c. Kali<br>
d. Gentoo

### Answer
* c
    * I watched all of *Mr. Robot*, which was using Linux technology in 2015.
    * I think I need not elaborate any further.
    * If it was in 2025 or later, I might've paused and looked for [Parrot OS](https://en.wikipedia.org/wiki/Parrot_OS).
        * Personally, I would consider running Parrot Home on bare metal as the host OS, and then use Kali Linux either as a VM or booting live from a USB device.

## Question 19
When Linux is hosted within a container on a cloud provider, what cloud delivery model is being used?

a. IaaS<br>
b. PaaS<br>
c. XaaS<br>
d. SaaS

### Answer
* b
    * This one is straightforward, as this is also from reading the text or using context clues.
    * IaaS would offer options allowing a self-administered but remotely hosted VPS setup that users discuss online.

## Question 20
What component within a CD workflow creates a new virtual machine or container to host the web app?

a. orchestration server<br>
b. testing server<br>
c. code repository server<br>
d. build automation server

### Answer
* d
    * This is straightforward, as this is from reading the text.
