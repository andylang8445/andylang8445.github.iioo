---
title:  "Final Project for ICS3U (Grade11 Computer Science)"
date:   2019-05-29 00:00:01
categories:
- School Class
- School_Grade11
- Project
- Computer Science
tags:
- School
- Course
- Computer Science
- Project
- Final Project
- Final Exam
---
<h1>Final Project Doc</h1>

## Shooting Game<br><br>
  <h3> User Part</h3>
  <pre>
  1. Start Program
  2. Display Controls (`w`, `a`, `s`, `d`, `l`, `esc`, etc)
  3. Move `player unit` around the board and destroy your enemies and try not to get hit
  4. When you loose all the health gauge display your `final score` and `rank`
  5. Display the Greeting Screen and goto 1.
  </pre>

  <h3> Programmer Part</h3>
  <pre>
   1. Start Program
   2. Use `w`,`a`,`s`,`d` to move the `player unit`
   3. Press `l` to shoot the bullit
   4. Use 'esc' to open the option menu
   5. If the `player unit` is hit by enemy's attack
     * Decrase the health gauge
     * If there is no health left
       - End the game
       - Record the score to offline DB
     * Reset the location and status of `player unit`
     * Apply panelty in score
   6. If the enemy is hit by `player unit's` Bullit
     * Illuminate the <i>hit enemy</i>
     * Make Bullit disappear
     * Increase the score
   7. If there are no enemys left
     * Increase the Level
     * Locate new enemys
   8. Display the `Real-time` Ranking
     * Update the ranking when every hit occured
     </pre>

   <h3> Pseudocode part</h3>

   <pre>
   1. Start Program
     * Set the basic settings
     * Print the starting screen
      -Show how to play the game
     * Show the loading screen
     * Read the offline DB and load the ranking to the structure array
   do {
       a) If keyboard is hit
         * If the key pressed is one of `w`,`a`,`s`,`d`
           - Move the player unit in the area of the boundary
         * If the key pressed is `l`
           - Shoot the bullet from the location of the `player unit`
         * If the key pressed is 'esc'
           - Display the option of the game
       b) If the `player unit` is hit by enemy's attack
         * Decrase the health gauge
         * If there is no health left
           - End the game
           - Record the score to offline DB
         * Reset the location and status of `player unit`
         * Apply panelty in score
       c) If the enemy is hit by `player unit's` Bullit
         * Illuminate the <i>hit enemy</i>
         * Make Bullit disappear
         * Increase the score
         * If there are no enemys left
           - Increase the Level
           - Locate new enemys
       d) If it's specific enemy's tern to shoot
         * Shoot the bullet
         * Set the cool-time timer for specific enemy to shoot bullet again
       e) Decrease the cool-time timer by 1
       f) Display the `Real-time` Ranking
         * Update the ranking when every hit occured
   } while (health gague is not empty)
   </pre>

   <h3> Flowchart part</h3>
<hr>
  <h3>Due Dates</h3>
   <pre>
    ■ Fix error of player shooting basic bullets: May 31st
    ■ Fix errors of enemy shooting bullets: May 31st
    ■ Make enemy bullets to move in angles(Linear function): June 8th
    ■ Make enemy to move: June 10th
    ■ Display Health gauge: June 5th
    ■ Create the option tab: June 8th
    ■ Create differences in different level: June 10
    ■ Create the user manual & tutorials: June 14th
    ■ Fix other errors: June 14th
   </pre>
<br>
<h3>Nice to have</h3>
 <pre>
  ■ Real-time Ranking
  ■ Add player name input Part
  ■ File I/O for the offline db
 </pre>

<br>
<hr>
