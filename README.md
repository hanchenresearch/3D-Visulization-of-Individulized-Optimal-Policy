# 3D Visulization of Individualized Optimal Policy $\pi^\ast(𝑎_{𝑖𝑡}│𝑠_{𝑖𝑡})$
<br />

This is the visualization of daily individualized optimal treatment $a$ (action) allocation conditional on the reading state input $s$ (number of logins, download times and reading time). Download the html file for each day, double-click, and it opens in your browser, e.g., Google Chrome. The interactive 3D space allows for zooming in/out and rotations in any direction. Each dot in the state-action space represents an individual consumer for whom the daily optimal treatment $a_{it}$, denoted by different colors, is plotted against reading state $s_{it}$.

I take a snapshot from the same spatial angle for each day’s visualization and summarize the dynamics in the following figure. It visualizes how the treatment allocation $a_{it}$ dynamically changes in the optimal policy $\pi^\ast(a_{it}|s_{it})$ as the reading state also transits \rightarrow $(s_{it},a_{it}) \rightarrow (s_{i,t+1}, r_{it})$.

<br />

<p align="center">
    Individualized Optimal Sequential Policy of Treatment in a 3D Interactive State-Action Space
</p>

<p align="center">
  <img width="600" src="asset/images/OptimalPolicy.jpg" alt="Daily Visualization">
</p>


