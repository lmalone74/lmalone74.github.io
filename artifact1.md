---
title: Artifacts
---

<p style="text-align: left; font-size: 18px;">
  <a href="/">Home</a> |
  <a href="/artifactshome.html">Artifacts</a> |
  <a href="/projects.html">Projects</a> |
  <a href="/contact.html">Contact</a>
</p>>
<p style="font-size: 13px; color: #666;">
  <strong style="color:#444;">Artifacts:</strong>
  <a href="#code-review">Code Review</a> |
  <a href="/artifact1.html">Artifact One</a> |
  <a href="/artifact2.html">Artifact Two</a> |
  <a href="/artifact3.html">Artifact Three</a>
</p>>

# Artifact One - Farkle Game
**Software Design / Engineering Enhancement**

A C++ Farkle game enhanced from a console application into a Windows GUI with improved architecture and gameplay validation.
>
### [View Original Code (GitHub)](https://github.com/lmalone74/Artifact-One-Farkle-Game/tree/Original-Code) | [View Enhanced Code (GitHub)](https://github.com/lmalone74/Artifact-One-Farkle-Game/tree/Enhanced-Code)
>

For this artifact, I selected the Farkle game developed in IT 312 (2025). The original program was a console-based application written in C++ that allowed multiple players to take turns rolling and banking dice, with the goal of reaching 10,000 points. The application was built using object-oriented programming, with classes such as Dice and Turn managing different aspects of the game logic.

I chose this artifact because it demonstrates my ability to design and extend a complete application using object-oriented principles, while also transitioning an existing program into a more modern and user-friendly format. Although the original version functioned correctly, it relied entirely on console input and output, which limited usability. The enhancement focused on converting the program into a Windows GUI application, allowing users to interact with the game visually. This required separating the user interface from the core game logic and adapting existing functionality to work within an event-driven environment, which in turn required rethinking how game state was managed, as the original implementation relied on sequential console input while the GUI version required event-driven updates and persistent state tracking. Additional improvements included refining scoring logic, preventing invalid actions such as selecting non-scoring dice, and improving overall gameplay flow. These changes demonstrate my ability to extend an existing application and improve both usability and functionality.

Through this process, I developed a stronger understanding of how application architecture impacts flexibility and maintainability, particularly when transitioning from a linear console-based design to an event-driven GUI environment. One of the main challenges was removing the original input and output loops and restructuring the program to work within a GUI framework. This required significant testing to ensure that game rules were enforced correctly and that new bugs were not introduced during the transition. I also recognized that better initial planning, such as creating more complete wireframes, would have improved development efficiency. Feedback and testing helped identify issues in scoring and game flow, leading to a more stable and user-friendly final version. One challenge I encountered was ensuring that scoring rules were enforced correctly in the new interface. During testing, I identified issues such as allowing the same dice to be scored multiple times or selecting non-scoring dice, which required refining validation logic and improving state tracking.

This enhancement supports Outcome 1 through the design and improvement of a computing solution that required restructuring and extending existing functionality. It supports Outcome 2 through the application of object-oriented programming and structured logic to manage game state and scoring. It also supports Outcome 3, as the redesign required clear separation between system components, improving maintainability and overall software design.

