---
title:  "Final Project for ICS3U"
date:   2019-04-16 00:00:01
categories:
- School Class
- School_Grade11
- Project
tags:
- School
- Course
- Computer Science
- Project
---

<h3>Coming soon</h3>

## Shooting Game<br>
<hr>
  <h5>System Part</h5>
    - Start Program
    - Use `w`,`a`,`s`,`d` to move the `player unit`
    - Press `l` to shoot the bullit
    - Use 'esc' to open the option menu
    - If the `player unit` is hit by enemy's attack
      * Decrase the health gauge
      * If there is no health left
        - End the game
        - Record the score to offline DB
      * Reset the location and status of `player unit`
      * Apply panelty in score
    - If the enemy is hit by `player unit's` Bullit
      * Illuminate the <i>hit enemy</i>
      * Make Bullit disappear
      * Increase the score
    - If there are no enemys left
      * Increase the Level
      * Locate new enemys
    - Display the `Real-time` Ranking
      * Update the ranking when every hit occured
