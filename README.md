# McGraw-Bot

Author: Nicholas Korte

GitHub - nrkorte

Email - himtoo112@gmail.com


Purpose:
This is a bot that will complete your McGraw Hill Connect homework for you. This bot is to be used for the version of McGraw Hill
Connect that has Multiple Choice, True or False, Multiple Select, Matching, and Ordering questions. This is NOT to be used for
the version of McGraw Hill Connect that has table based inputs as it will not work.


How to use:

1. Install the required dependancies. You will need Python v3.1 or higher, Selenium, and a chromedriver. I recommend you use the 
chromedriver I have on here. For this program to work the chromedriver needs to be named "chromedriver" (without quotes) and needs to be
in the same directory as the bot. Chromedriver should have pop-ups enabled by default but you may need to turn them on manually.

[The program might take 10-15 seconds to start the first time you attempt to open chromedriver]

2a. Running with admin privileges: I recommend this for those that know how to use python programs. First, edit the admin file to include
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
 - I do NOT condone cheating. This program was built after my class was complete using old homeworks that were finished manually by me.


Edit:
New beta for using a JSON file to store questions in a question bank is uploaded. Usage is the same as the main python program except you will run "./json_runner" to run the program instead of "./admin". Additionally, you can run "./clear_bank" to empty the JSON file. This is a beta and I don't have access to McGraw Hill, so any problems will need to put up in an issue with a clear and concise resolution. Thanks!
