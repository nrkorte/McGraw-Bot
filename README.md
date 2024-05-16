# McGraw-Bot

Author: Nicholas Korte

GitHub - nrkorte

Email - etroknick@gmail.com
Discord - segc_


Purpose:
This is a bot that will complete your McGraw Hill Connect homework for you. This bot is to be used for the version of McGraw Hill Connect that has Multiple Choice, True or False, Multiple Select, Matching, and Ordering questions. This is NOT to be used for the version of McGraw Hill Connect that has table-based inputs as it will not work.


How to use:

1. Install the required dependencies. To do this, download the contents of this GitHub repository and open up a terminal. Change directories until you see the files and type `chmod 777 ./dependencies` and then `./dependencies` to install all of them. After this is done, you should have everything you need to start the program. This is a LINUX-based program and needs to be run as such. This means that it can be run directly from the terminal of a Mac or Linux computer, but if you are on Windows, you will need to run it from a Linux terminal. There are many ways to go about that, but the easiest in my opinion is to run it from VSCode.

[The program might take 10-15 seconds to start the first time you attempt to open Chromedriver]

2a. Running with admin privileges: I recommend this for those who know how to use Python programs. First, edit the admin file to include
your Canvas username and password as well as the Canvas link to your assignment. In the terminal type ./admin to start the program.

2b. Running with user privileges: Type ./bot_init into the terminal and follow the prompts as they come up. This will start the program
and each time you run it you will have to retype those prompts.

3. Enjoy! I recommend not using your computer while this is active as it will be performing right clicks, tabs, and other actions that 
can make using your computer difficult. Additionally, the program goes endlessly so when it hits something that it doesn't recognize at
the end the program will likely crash on its own. This isn't a problem.


Reported Bugs:
  - Ordering questions is still failing and will always get them wrong. I no longer have access to McGraw Hill Connect and will not be
 able to spend any time debugging this.
  - If the program spits an error at you, read it closely and follow the directions. Selenium is a volatile language and can cause errors
  that might not happen again. I wrote this program to only sleep for as long as I would need it to, your computer, if it is slower, might
  need more time. My general recommendation is that, if the program fails, start it again.

Disclaimer:
 - I do NOT condone cheating. This program was built after my class was completed using old homeworks that were finished manually by me.


Edit:
A new beta for using a JSON file to store questions in a question bank is uploaded. Usage is the same as the main python program except you will run "./json_run" to run the program instead of "./admin". Additionally, you can run "./clear_bank" to empty the JSON file. This is a beta and I don't have access to McGraw Hill, so any problems will need to put up in an issue with a clear and concise resolution. Thanks!

Edit 2:
Remember that ChatGPT is your friend here, if you are struggling to get the program to start, that AI is a wonderful debugger. I will no longer be responding to user-side errors to help out. If there is a genuine issue with the code that needs fixing, please create an issue and I will do my best to answer how to fix it or I will fix it myself. Thanks!