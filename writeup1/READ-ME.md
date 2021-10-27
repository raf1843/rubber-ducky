Rubber Duckies:
===============

Inconspicuous and Powerful
--------------------------



Overview
--------

USB Rubber Duckies, or more generally "bad USBs", are incredibly powerful tools with many uses, from red teaming (what we generally think of as hacking) to bringing awareness to security risks. As implied by the name, they are easily disguised as a very generic flash drive, but with different components inside that allow it to perform a wide range of tasks. It can easily be implemented if the hacker has access to the computer for a short period of time, or by taking advantage of the curiosity and naivety of employees. Also, as USBs are so widely used, it works on almost any computer. Overall, the Rubber Ducky's flexibility and ease of use make it a good choice for a wide variety of products, and an even better topic to learn about.

Hardware

Although it looks like a generic USB, the Rubber Ducky has a lot more going on inside. First, it has a 32-bit microcontroller. This is the main thing that makes the rubber ducky so powerful - it controls the actions of the computer and allows it to act like a keyboard. Next, there is also a microSD card reader. This assists in the quick and easy transfer of data required for the Rubber Ducky to work. The micro push-button and LED display simply allow for easier use and understanding of the device. A JTAG interface is included, likely for its debug and emulation capabilities. JTAG uses four signals collectively referred to as Test Access Port (TAP), and is often used to check if the USB is connected properly, called a boundary scan. Finally, the Rubber Ducky uses the widely accepted USB-A connector, which, as mentioned above, makes it very versatile.

The USB port is used because when USB devices like keyboards are connected, most systems will automatically connect and begin accepting data. This means that the Rubber Ducky has few to no obstacles before it can start sending commands and data, and its tasks are completed before anything can be done.


Software
--------

Rubber Duckies are scripted using the aptly named Ducky Script. It is a simple, straightforward language that can be done in any ASCII text-editor. The syntax is clear - each command takes a new line, the command itself is capitalized, and REM is used for commenting. Most commands involve key-strokes or -combos, strings, or delays. The keystrokes are obvious - the Rubber Ducky is intended to act like a keyboard, so it is programmed with keystrokes. Strings can be used to process text. Delays allow the computer to process between commands, as the Rubber Ducky has the power to act so quickly that the computer cannot keep up. 

While there are more details in the actual programming, the idea is that it is simple. The workflow remains largely the same regardless of the target, and the programming language is easy to use and learn. This contributes to making the Rubber Ducky a very flexible tool.


Uses
----

Rubber Duckies can be used to quickly and easily insert malicious code into the target system. This can include a script to create a reverse shell, allowing a remote user to essentially control the target computer. It might also be used to launch a program, go to a website, and essentially any other command if the computer is vulnerable enough. 

These possibilities can be used for cyber awareness as well. It can show employees that not all USBs are safe, and if you find one, you should  not simply plug it in to your computer without a thought. Many Rubber Ducky attacks can be started by the attacker dropping the USB in the company area, meaning the first vulnerability is the employee who picks it up. By showing employees how easy it is for a USB to take control of your computer, it can educate and prevent mistakes.



Citations
---------

<https://docs.hak5.org/hc/en-us/categories/360000982554-USB-Rubber-Ducky>

<https://www.linux.org/threads/usb-rubber-ducky.4464/>

<https://www.intervalzero.com/how-microcontrollers-work/>

<https://www.xjtag.com/about-jtag/what-is-jtag/>

<https://www.ivoidwarranties.tech/posts/kcsec/rubber-ducky-toolkit/>

<https://www.stickpng.com/cat/animals/ducks?page=1>
