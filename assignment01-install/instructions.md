# Assignment 1: Install Dart & Flutter
*Due: Tuesday, September 1, 2020* 

Your assignment is to install **Flutter**, the framework we'll be using to build applications in DMS 102.  

Note: part of the installation process for Flutter will have you install its dependencies which includes **Dart** and some other required programs depending on whether you're using a Mac or PC, and whether you want to develop apps for Android devices and/or iOS.

- For your reference, the official instructions for installing Flutter from the publisher are here: [Install Instructions from Flutter.dev/docs/getting-started](https://flutter.dev/docs/get-started/install), but they assume you're already a software developer and you have familiarity with working with IDEs (Integrated Development Environments) and using a CLI (Command Line Interface). So...
- Instead of using those instructions by themselves, I recommend these tutorials (below) that do a better job of walking you through the process.
- NOTES:
- As part of these instructions you *do* need to install the dependency: **Git** (not GitHub!)
  - These tutorials: one year old (pretty good); your milage may vary esp. if you don't have your OS updated ...so make sure you install OS updates!
  - The installation process *really does take a long time*, depending on a lot of factors like your connectivity speed and your computer's speed.  Plan accordingly.
- Tutorials:
    - WINDOWS tutorials (parts 1,2,3):<br>
        [How to Install and Setup Flutter for App Development on Windows - Part 1](https://youtu.be/Z2ugnpCQuyw)<br>
        [How to Install and Setup Flutter for App Development on Windows - Part 2](https://youtu.be/8YlJ9RjdpkA)<br>
        [How to Install and Setup Flutter for App Development on Windows - Part 3](https://youtu.be/n9qDNVoe5V8)
    - MAC tutorials (parts 1,2,3,4,5)<br>
      [How to Install and Setup Flutter for App Development on Mac - Part 1](https://youtu.be/hL7pkX1Pfko) *([important note! - see here](#notes))<br>
      [How to Install and Setup Flutter for App Development on Mac - Part 2](https://youtu.be/gv1LScpG0jM)<br>
      [How to Install and Setup Flutter for App Development on Mac - Part 3](https://youtu.be/_p3VbxiVuRU)<br>
      [How to Install and Setup Flutter for App Development on Mac - Part 4](https://youtu.be/3oIFshgMgLA)<br>
      [How to Install and Setup Flutter for App Development on Mac - Part 5](https://youtu.be/H_xusHxICbk)
    - Other Videos
      - [What is Flutter?](https://youtu.be/I9ceqw5Ny-4) (recommended - watch this while you wait for some of the longer installation processes to complete)
      - [Why Choose Flutter?](https://youtu.be/L2OsgmirBwo) (somewhat redundant with the previous video, but also recommended)
      - [Prerequisites for Flutter Development](https://youtu.be/7gegvWBMOTg) (probably *not* useful)
      - [Using Android Studio for Flutter Development - Part 1 - Configuration](https://youtu.be/47keBFllFvQ) (may be good for informational purposes, but probably not useful)
      - [Using Android Studio for Flutter Development - Part 2 - Guided Tour](https://youtu.be/enUdOLgl4Jk) (also probably not useful)

And BTW, here is the link to the channel from where all these videos come from: [London App Brewery](https://www.youtube.com/playlist?list=PLSzsOkUDsvdtl3Pw48-R8lcK2oYkk40cm)



###### Notes

\* Since the recording of these videos some of the instructions *may* need to be changed based on the particulars of your operating system.  In the Mac operating system, the name of the file for setting the "PATH" to Flutter (see timestamp: 5:18) *may* need to be different based on the type of "shell" (command line program) you're using.  

- If you're using "Bash" (look in the title bar of the Terminal window), then the instructions in the video are correct
- If you're using "Zsh" (look in the title bar of the Terminal window), then you need to use filename: **.zshrc**, instead of .bash_profile, so you would type: `vim .zshrc` instead.