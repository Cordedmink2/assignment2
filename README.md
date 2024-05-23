# assignment2
Research Report
Intro
I'm going to do a simple 2D maze game where the player navigates through a randomly generated maze to reach the exit while avoiding AI enemies. The game focuses on combining AI and physics techniques to make a fun and interactive experience.

Chosen Topics and Techniques
Set A:
A1: Physics Simulation
Description: Collision detection and response using Unity's physics engine to handle interactions between the player, enemies, and maze walls.
Rationale: Collision detection ensures realistic interactions within the game, preventing characters from passing through walls and other obstacles.
References: Unity Documentation on Physics: [Unity Physics](https://docs.unity3d.com/Packages/com.unity.physics@1.2/)

A2: Movement
Description: Utilizing steering behaviors like seek and flee for natural movement of the player and enemies - suiting for a maze game.
Rationale: Steering behaviors are not too bad to implement and provide realistic and responsive character movement.
References: Craig Reynolds' Steering Behaviors: Reynolds, Craig. (2002). Steering Behaviors For Autonomous Characters. 

A3: Pathfinding
Description: Implementing the A* algorithm pathfinding for enemies navigating through the maze.
Rationale: A* is an efficient and optimal pathfinding algorithm that balances performance and accuracy, making it good for the real-time navigation needed in a maze game. Pathfinding is the obvious choice for a maze game with AI enimies.
References: Amit’s A* Pages: [Amit’s Game Programming Information](https://www.redblobgames.com/pathfinding/a-star/introduction.html)

Set B:
B2: Action Planning
Description: Using Behavior Trees to structure and manage the decision making process of the enemy AI.
Rationale: Behavior Trees provide a good approach to AI decision-making, making it easier to add complexity over time.
References: Behavior Trees in Game AI: [Behavior Trees for Game AI](https://www.gamedeveloper.com/programming/behavior-trees-for-ai-how-they-work)

B3: Procedural Content Generation
Description: Generating random maze layouts, probably using the Depth-First Search algorithm, to ensure each playthrough is unique.
Rationale: Procedural content generation enhances replayability making the game that much better.
References: Mazes for Programmers (Jamis Buck): pdf uploaded to git repo

3. Conclusion
The techniques chosen for this project aim to create a simple but engaging gameplay experience by combining AI and physics concepts. The use of Unity's physics engine for collision detection, steering behaviors for movement, A* for pathfinding, Behavior Trees for decision-making, and procedural generation for maze creation will result in a cohesive game design.
