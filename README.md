#  DataDispatch

**DataDispatch** is a 3D pathfinding logic puzzle developed in **Unreal Engine 5**. The game simulates a complex data routing network where players must optimize the flow of information through a grid of logic gates, routers, and obstacles.

*\> Watch the gameplay demo* https://youtu.be/FBZXJke_djw?si=8-7rqVkwME00og03

##  Game Overview

In **DataDispatch**, you act as the system administrator for a corrupted network. Your objective is to guide a **Data Packet** from its source to the **Output Terminal**.

However, simple pathfinding isn't enough. To validate the data, the packet must visit every active **CPU Node** on the grid before exiting.

###  How to Play

1.  **Analyze the Grid:** Observe the starting position, the required checkpoints (CPUs), and the destination.
2.  **Manipulate the Flow:** Click on floor tiles to **rotate their directional arrows**.
3.  **Execute:** Watch the Data Packet follow your path in real-time.
4.  **Win Condition:** The packet must step on **ALL Green CPU tiles** at least once and reach the **Computer Terminal**.

##  Mechanics & Features

As players progress, the network becomes increasingly volatile with new tile types and hazards:

  * **🟩 CPU Nodes (Objectives):** Mandatory checkpoints. You must route the packet to touch every single Green CPU tile to unlock the exit.
  * **🟥 Corrupted Sectors (Hazards):** "Red Do-Not-Touch" tiles. If the packet steps here, the data is corrupted, and the level fails immediately.
  * **📶 Routers (Teleportation):** Linked pairs of tiles that instantly transport the packet across the map, allowing for non-linear solutions.
  * **🚀 Jump Pads:** Launch the packet over gaps or obstacles, adding a vertical dimension to the flat grid logic.

##  Project Context: IRGL Competition

This game was developed specifically for the **Informatics Rally Games and Logic (IRGL)**, a national IT competition for high school students in Indonesia.

  * **Purpose:** Designed to test participants' algorithmic thinking, spatial reasoning, and debugging skills under time pressure.
  * **Division:** IT Game Division.

##  Built With

  * **Engine:** Unreal Engine 5
  * **Logic:** Blueprints Visual Scripting / C++
  * **Platform:** Windows

-----
