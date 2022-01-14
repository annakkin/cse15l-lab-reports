# Lab Report 1

#### *VSCode setup, remote acess, and simple commands* 
<br />
<br />

### Part One: VSCode setup

*Step 1: Installing VScode*

The download link is here: [VSCode](https://code.visualstudio.com/)  (remember to use Safari instead of Chrome!)

A successful download page should look like this:

![sc1](screenshot1.png)

<br />

***

### Part Two: Remote Access

*Step 2: Remotely Connecting*
<br />

First find your course account on [ETS](https://sdacs.ucsd.edu/~icc/index.php) and change your password to activate it. Record your course-specifc username (*cs15lwi22amg*).
![sc2](screenshot2.png)

Then open VSCode terminal and type in `ssh <username>@ieng6.ucsd.edu`. Enter your password if required. If you successfully connect to ieng6 server, your terminal will show a message like this:
![sc3](screenshot3.png)

<br />

***

### Part Three: Commands
*Step 3: Trying Some Commands*

After logging in, you can start with some simple commands:

> `pwd` shows your current location

> `cd ~` directs you to home directory

> `ls` commands (`ls -lat`, `ls -a`, `ls /home/linux/ieng6/cs15lwi22/<username>` )show things in your current directory

> `cp /home/linux/ieng6/cs15lwi22/public/hello.txt ~/` copies the hello.txt file to your home directory

> `cat /home/linux/ieng6/cs15lwi22/public/hello.txt` prints out the content of hello.txt

To log out: 
> `exit`

*Step 4: Moving Files with scp*

*Step 5: Trying Some Commands*

*Step 6: Trying Some Commands*
