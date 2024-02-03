# Mouse Mover

This is my attempt to re-create a mouse mover on my [GitHub](https://github.com/ruaine83/Mouse-Mover) page. I had created the first one in Visual Studio C++, but decided that this could be a good exercise to practice my Rust programming.

## Description

The program should, when completed, operate identically as the C++ version. It will monitor the position of the mouse cursor, and if it hasn't moved in a certain amount of time, will select a random position, plot a course to that position with a little jitter to emulate human hand movement (to see if i cna use teh same code later to fool a Captcha). This should keep a system from going into sleep mode due to not detecting mouse movement.

I had originally wrote the first version for a friend who worked via Skype on her phone, but the instance of Skype on her PC would flag her as idle if she wasnt using the PC (it seemed to override the information from the App). A little tool to keep the mouse moving when idle would keep her manager off of her back.

