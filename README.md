# JUMPZ

Old arcade style game based off of pong made in scratch

<img width="400" height="302" alt="Recording 2026-07-19 152742" src="https://github.com/user-attachments/assets/99bf8008-c822-4816-9e48-f05b0d84e9a3" />

**TRY IT HERE -----> https://scratch.mit.edu/projects/1362933951/ <----- TRY IT HERE**


# FEATURES

- Physics system for ball movment
  
  <img width="476" height="1109" alt="Screenshot 2026-07-19 153958" src="https://github.com/user-attachments/assets/fbef51b8-67cc-456e-b2d7-ab5bf377ae95" />
  
-   Complete scoring system based off of airtime, amount of times you bouce the ball on the paddle, the amount of coins you collect, and the dificulty

-   A high score system
  
   <img width="833" height="708" alt="image" src="https://github.com/user-attachments/assets/d797052d-6261-4fa9-8816-fd1e7cdeb97d" />

-   Plenty of easter eggs :3 (try and find them)


**HOW TO RUN THIS LOCALLY?**

This project was made entirely on scratch so the only thing that you have to do is, press the link, hit the green flag, and enjoy!

**TRY IT HERE -----> https://scratch.mit.edu/projects/1362933951/ <----- TRY IT HERE**

# HOW DOES THIS WORK?


**Physics system:**
 The "ball movement" scripts work by haveing 2 variables that I call xSPEED and ySPEED. Whenever I call the ball movemet script the very first thing I do is move the ball by the amount of xSPEED and ySPEED and then I subtract 1 from each of them to make smooth and life-like motion! Then, I check to see if its touching the paddle. If it is I just incress the ySPEED to a positive number and ajust the xSPEED accordingly. The balls left right movement is random to increase difficulty!

 **High score system:**
  The highscore system works by once the game is over it checks to see if their score is higher than the previous high score. It then sets it to the new high score. To store the high score I use a cloud veriable. 
NOTE FOR TESTERS: If you dont have a scratch acount that has been verified you can't use cloud variables. This might make it look like the High score system doesn't work. DONT WORRY, IT WORKS! Here is a screen shot to prove it:

<img width="710" height="537" alt="Screenshot 2026-07-19 160554" src="https://github.com/user-attachments/assets/51bbd7a3-7227-4de6-9b45-5a55410013ee" />

**scoring system:**
 The scoring system works off of 4 different things

- Air Time
- The number of times you bounce the ball on the paddle
- The amount of coins you collect
- And the difficulty of the coins you collected

All of this is added up to make a complete scoring.
Here is the script to calculate all of this!

<img width="603" height="251" alt="Screenshot 2026-07-19 161335" src="https://github.com/user-attachments/assets/77a40cba-1397-40a6-89ce-493a9a99d748" />

# CREDITS/ACKNOWLAGEMENTS

**music:**
 The music I used is from MoodMode off of pixaby, Thank you!
 
 [moodmode-8-bit-arcade-mode-158814.mp3](https://github.com/user-attachments/files/30171447/moodmode-8-bit-arcade-mode-158814.mp3)

 And also built in sounds from the scratch engine, Thank you!

 **AI**

 AI was used for NO code generation on this project. The only time I used AI on this project was to trouble shoot the problem I was having with the super jump system. NO CODE WAS GENERATED FOR THAT, only just telling me what I did wrong.
