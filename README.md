<h1 align="center">Homefront</h1>
<h3 align="center">An FPS in Unity</h3>

(add image here)

**Concept:**

Homefront is an innovative strategy FPS that defies genre norms by combining intense tactical gameplay with brain-teasing coding challenges. The multiplayer is set in a high-stakes digital battlefield, players are divided into two teams: Coders and Guardians. Coders face academically stimulating tasks to earn research points, while Guardians engage in strategic combat to infiltrate enemy bases and hack systems. The campaign is set in the same world and propels players into a blend of coding challenges and FPS combat, giving them a taste of both aspects of the game. The story weaves an intricate tapestry of loyalty, betrayal, and redemption against the backdrop of an ever-evolving digital battlefield. Overall, the fusion of coding puzzles with strategic combat offers a unique gameplay experience that challenges both intellect and reflexes.

<br>

**My Team:**

I created this game along with Kyle Zhang, a designer.

<br>

**My Roles in the process:**

* Design:

  * Game design
  
  * Level design
  
  * Writing

* Development:

	* Lead developer

	* Created runtime code compiler for the coding sections

	* Created a system that allows the completion of coding tasks to affect the game world

	* Implemented basic skill tree progression with progress requirements

<br>

**Challenges:**

* Compiling strings as code during runtime:

	* By far, my biggest challenge was taking the strings inputted by the user, and running it as code. At first, I thought I could simply write the strings to a .cs file and then compile that file, but that required refreshing the asset database which removed object references from other scripts, lagged the game, etc

	* Thus, I looked around for packages that would compile C# code, and after some time I found Microsoft's CSharpCodeProvider which did exactly what I needed

* Scope:

	* We have big plans for this game, but it is difficult to keep developing this with only 2 people, so we are trying to find more eager developers

<br>

**Assets:**

* None of the team members are artists, so we decided to use the existing Unity FPS package for the models
