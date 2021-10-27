Overview
--------

For my scripts, I aimed to execute the same actions for both Windows and Linux. The goal is to move to the Desktop, write "quack quack" to a file named quackpack.txt, and then launch a fun little surprise video for anyone who runs it :)

Windows
-------

For Windows, I wrote a .bat script for the Command Line. I used cd, which I found out works on both Linux and Windows, to change directory. I ran into a bit of difficulty figuring out how to access the Desktop correctly due to the fact that my computer uses OneDrive, but I configured it to work on my laptop and should be able to figure out how to make it run on a computer set up differently in the future. After that, I found that the 'echo' command has a very similar usage between Linux and Desktop as well, and was able to create and write to the file that way. Then, I found how to open a webpage from the command line using 'launch'.

Linux
-----

For Linux, I wrote a .bash script for the bash shell. Again, I used cd and echo to change directory and write to a file. I found that the directories in Linux seem much more intuitive than the ones I have on my Windows computer.  On the other hand, launching a webpage was more difficult, and the way I found to do it was -mwebpage and this relies on the user having python installed. I'm sure there are other ways to do this that I have just not learned yet.
