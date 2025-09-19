# Game-Engines-Week-3-Lab

Me:
Alex Anastasakis - 100892202

Title: 
Bean-ball. The gameplay loop is to get the bean to pickup all of the balls. Try not to fall off the map!


Diagrams:



<img width="710" height="747" alt="image" src="https://github.com/user-attachments/assets/87e67d1f-35fc-4ab4-adc9-f47617a5faa7" />




<img width="1176" height="562" alt="image" src="https://github.com/user-attachments/assets/c3022671-244d-463b-b0eb-37ec7e3c20c7" />



**What system within your project uses a Singleton, and why did you choose this system to adopt the pattern?**
Both the gamemode and the enhanced input subsystem are singletons. I chose to use these systems simply because
they're built in and the quickest to implement. I would consider them bothe necessary pieces of any game made in unreal engine, so by 
getting better at implementing these, it would help me manage my time better on the exam.

**Do you think this design pattern is beneficial for this purpose? Explain why or why not.**
Yes, because the player character does not need to know about score or about the existance of pickups. 
Neither do the pickups need to know about the existance of the player character.
