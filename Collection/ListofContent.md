<a name="readme-top"> [Back To Main Page](https://github.com/TaihouAnF) </a>


<h1 align="center">💼 Projects </h1>

### [Chainmail](https://github.com/TaihouAnF/Rasterizer) | Aug, 2024
*U of U MEAE rapid prototype project I - Theme: Classic Arcade Game Renovation*

<p align="center">
  <img src="https://github.com/TaihouAnF/TaihouAnF/blob/main/assets/Chainmail-sc"/>
</p> 

* Chain Mail is based off the classic arcade game "Centipede," but this time- you're the centipede! Control multiple chains at once and navigate to the bottom of the screen.

  Try to get your longest chain mail to the bank account to earn the most points possible!
* Game Engineer:
  * Developed enemy movement system which randomly tracking one part of the player as the target, the enemy would move towards with a random part of the player, much like a steering effect.
  * Implemented enemy attacking logic with options to change rate of fire and bullet speed.
  * Designed and created level and difficulty progression system by utilizing player score system, enemy movement system, and enemy attacking logic, providing engaging gameplay experience:
    * Each level has a different goal and the enemy would have different buff.
  * Implemented an extra enemy type which is called "agent". It moves diagonally with random direction, acting like a bullet to prevent the player to reach the target.
* C#, Unity3D
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

### [Rasterizer](https://github.com/TaihouAnF/Rasterizer) | January, 2024
*Personal Learning, following the tutorial from [Code-It-Yourself! 3D Graphics Engine Series](https://youtu.be/ih20l3pJoeU?si=hpAbI-8SmvuPoPUX)*

<p align="center">
  <img src="https://github.com/TaihouAnF/TaihouAnF/blob/main/assets/Rasterizer.png"/>
</p> 

* A 3D Rasterizer built with C++, and going to change low level API using SDL(currently I'm using olcEngine), following the tutorial,
  I transform the knowledge into my own code implementation.
* Engineer:
  * Developed vector, matrix, triangle, and meshes.
  * Implemented projection, lighting based on light source and surface normal, culling using painter's algorithm, and loading object mesh files.
  * Implemented moving camera and mesh clipping.
* Capable of moving a camera and setting up an active scene
* C++, SDL, OpenGL(possibly), 3D Maths
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

### [Iron Jungle](https://github.com/TaihouAnF/Iron-Jungle) | July, 2023
*My First Game Jam: Summer 2023 - Theme: theme is optional*

<p align="center">
  <img src="https://github.com/TaihouAnF/TaihouAnF/blob/main/assets/Iron_Jungle.png"/>
</p>

* Complete Game demo: [**Demo**](https://leption.itch.io/iron-jungle) | A Playthrough Video: [**YouTube Video**](https://youtu.be/sWqLsdyJnhs)
* A 2.5D platformer game with a unique grapple/swinging feature to help you to go up to the destination, developed using Unity3D.
* Game Engineer and Level Designer:
  * Developed the core movement, and grappling/swinging ability of the player using the SpringJoint feature; collaborated with the team to integrate animation and sound with the movement
  * Developed multiple platform behaviors, which various platforms can be created by changing the combination of behaviors
  * Designed **2** distinct levels (easy and medium difficulty)
* **300+** downloads and views on [Itch.io](https://itch.io/) and the number is still growing
* Unity3D, C#, Unity Physics: SpringJoint, Visual Studio, Git
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

### [Beautiful Idle Game - Zombie Cleaning Service](https://github.com/TaihouAnF/Beautiful-Idle-Game) | June, 2023
*Summer Slow Jams 2023: Idle - Theme: “Mutation”*

<p align="center">
  <img src="https://github.com/TaihouAnF/TaihouAnF/blob/main/assets/Zombie_Cleaning.png"/>
</p>

* Complete Game demo: [**Demo**](https://taihoudesu.itch.io/beautiful-idle-game) | A Playthrough Video: [**YouTube Video**](https://youtu.be/pTjxnDoNzSo)
* An isometric view idle game with a little tower defense developed using Unity3D. Purchase and build turrets to kill infinitely spawning "zombies" and get rewards.
* Game Engineer:
  * Developed turret building system in which player can build a turret when clicking on valid tiles
  * Developed range tiles highlighting using Breadth First Search-like algorithm, visualized the turret attack range
  * Developed turret firing feature and implemented a "slow effect" mechanic
  * Developed an in-game shopping system and integrated it with the turret system
* **200+** downloads and plays under the category of "idle" on [Itch.io](https://itch.io/)
* Unity3D, C#, A* Algorithm (for path finding of NPC), Visual Studio, Git
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

### [Shifting Dimension](https://github.com/TaihouAnF/Shifting_Dimension) | May, 2023
*GDTV Game Jam 2023 - Theme: “Life in 2 Dimensions”*

<p align="center">
  <img src="https://github.com/TaihouAnF/TaihouAnF/blob/main/assets/Shifting_dimension.png"/>
</p>

* Complete Game demo: [**Demo**](https://taihoudesu.itch.io/shifting-dimension) | A Playthrough Video: [**YouTube Video**](https://youtu.be/65fz8wysiCg)
* A 2.5D puzzle platformer where you would use a “shifting dimension” feature to stand on platforms, to dodge attacks, and to go past obstacles. The final destination is on the right end of the map.
* Game Engineer and Level Designer:
  * Developed the "Shifting Dimensions" feature and a corresponding movement system using C#
  * Synchronized the character’s animation with the player’s movement using Unity Animator system
  * Applied particle and sound effects in the game to improve visual and auditory feedback given to players
  * Implemented the Tutorial level for players
* **#15** in story and **#80** in theme out of 1000 submissions, and received **500+** views on [Itch.io](https://itch.io/)
* Unity3D, C#, Unity Animator, Visual Studio, Git
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

### [2D/3D Rendering Engine](https://github.com/TaihouAnF/Basic-Rendering-Engine) | Spetember, 2022 - December, 2022

<p align="center">
  <img src="https://github.com/TaihouAnF/TaihouAnF/blob/main/assets/Renderer.png"/>
</p>

* A 2D light simulator and 3D Rendering Engine with Ray-Tracing and Path-Tracing features developed by using C.\
A detailed description can be found in the project.
* Engineer and Maintainer:
  * Simulated light ray propagation (reflecting, refracting, and diffusing) in 2D with point light sources
  * Developed basic backward Ray-Tracing using local [**"Phong Model"**](https://en.wikipedia.org/wiki/Phong_reflection_model) and point light source
  * Improved the previous Ray-Tracer to support more features (including multi-threading, anti-aliasing, area light sources, mappings, etc)
  * Implemented Path-Tracing with Importance Sampling and Explicit light sampling
* The ray-tracing feature passed 98% of benchmark tests, and Path-Tracing feature can generate realistic pictures with low levels of noise
* C, Ray-Tracing, Path-Tracing, Visual Studio Code, Git
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

### [Beep Boop Babies](https://github.com/TaihouAnF/beepboopbabies) | April, 2023
*Level Up Showcase 2023 Toronto - Theme: No Theme*

<p align="center">
  <img src="https://github.com/TaihouAnF/TaihouAnF/blob/main/assets/BBB.png"/>
</p> 

* Game Demo: [**Demo**](https://github.com/TaihouAnF/beepboopbabies/releases/tag/V2.0) | Gameplay Trailer: [**YouTube Video**](https://youtu.be/6aB8FIxI_tw)
* A co-op survival party game where you and your friends run a robot daycare, inspired by overcooked and developed by using Unity3D.
* Engaged as a developer in the middle of development:
  * Developed extra consequences for robotic "babies" (lacking oil, fuel, etc), and the "overcharging" feature for staying too long on charge station
  * Integrated visual notification to warn players for missing NPC's needs
  * Collaborated with model team to implement Level 2 "Space Station"
* The game demo was presented on-site on LevelUp Showcase 2023 Toronto, received positive feedback from players.
* Unity3D, C#, Coroutine, Visual Studio, Git
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

### [PickEasy Website App](https://github.com/TaihouAnF/CSCC01_PickEasy_team01_project) | May, 2020 - Aug, 2020

<p align="center">
  <img src="https://github.com/TaihouAnF/TaihouAnF/blob/main/assets/PickEasy.png"/>
</p>

* A gamified restaurant web app by integrating coupon and achievement system, developed by using python Flask.
* Engineer:
  * Implemented registration & login system for users using Python and MySQL in the 1st sprint 
  * Cooperated actively to build the core feature: Achievement System
  * Designed unit test suites for multiple components throughout the development
* The final demo was approved by the client “PickEasy”, achieving 80% satisfaction rate.
* Python, MySQL, HTML/CSS, Flask, Git, Trello, Scrum
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---
<!---
### [Fighter](https://github.com/TaihouAnF/Fighters) | TBD

<!---
<p align="center">
  <img src="https://github.com/TaihouAnF/TaihouAnF/blob/main/assets/PickEasy.png"/>
</p> 

* A WIP personal game project, inspired by 2D vertical bullet games, developed by using Unity3D.
* Developer, and I will be applying multiple design patterns into the development of the game.
* Unity3D, C#, Blender
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

### [SDL_Demos](https://github.com/TaihouAnF/SDL_Demos) | TBD

<!---
<p align="center">
  <img src="https://github.com/TaihouAnF/TaihouAnF/blob/main/assets/PickEasy.png"/>
</p> 

* A WIP personal game project, replicating famous simple games like Tetris or Pong, in C++.
* Developer, and I will be using skills I learned to make these games in plain C++.
* C++, SDL
<p align="right">(<a href="#readme-top">back to top</a>)</p>
--->
---

