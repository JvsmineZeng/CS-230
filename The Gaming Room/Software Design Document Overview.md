### Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?
> The Gaming Room (TGR) is a gaming company who had a pre-existing Android-based game, <i>Draw It or Lose It</i>, before they became a client of Creative Technology Solutions (CTS). TGR wanted CTS to scale the game into a web-based application that would run on multiple platforms like Mac, Linux, Windows, and more, since their current staff do not know how to create a multi-platform environment. They also wanted the game to be redesigned so that:
> 1. Only one instance of the game can exist at any time.
> 2. Each instance may have one or more teams.
> 3. Each team may have one or more members.
> 4. Game and team names will be validated to avoid overwriting any game data.
> CTS has also been asked to describe their plans and recommendations for development.

### What did you do particularly well in developing this documentation?
> I did a good job in compartmentalizing information for TGR in digestable amounts. Since TGR staff are not experienced with environment setup, I did my best to explain everything in simple terms under the <i>Design Constraints</i>, <i>Domain Model</i>, <i>Evalulation</i>, and <i>Recommendations</i> sections. These sections allowed me to convey best industry practices to TGR in terms of designing and maintaining a multi-platform application from startup to deployment.

### What about the process of working through a design document did you find helpful when developing the code?
> The Domain Model helped me the most during development - it allowed me to visualize the hierarchy and structure of the <i>Draw It or Lose It</i> application. This, in turn, helped me figure out where to write and configure code that met TGR's requirements for the application. For example, input validation for team and member names were under GameService.

### If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
> I received full marks for this project, but I would add more to the <i>Recommendations</i> section. More specifically, I would elaborate on other cloud services besides AWS (i.e., Microsoft Azure, IBM Cloud, etc.) to allow TGR to pick the best cloud service for their game. I originally referred to AWS for all subsections of <i>Recommendations</i> because it is an industry leader for most game development companies today, but as a developer, I should offer comparison and evaluation of multiple options like I did in the <i>Evaluation</i> section for various operating platforms.

### How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
> I reflected TGR's requirements for game functionality and user experience under the UML diagram and evaluation/recommendations for application deployment. The UML diagram shows how data will be collected and handled throughout the instance of the game, while the evaluation/recommendations offer TGR some insight into physically running the game on a bigger scale than their Android-based version. It is important to consider users' needs in the design process so that the clients provide an interface that properly collects information for the application while keeping users engaged and active on the application.

### How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?
> I approached the software design process as a continuously evolving solutions-oriented process. First, I listen to the client's needs and consider the industry/environment they plan on deploying an application in. Then, I develop a list of recommendations and cautions based on the application's potential efficiency (i.e., using the Singleton Tester to parse through information) and its potential deficiencies (i.e., security problems that might arise from user login). I also do industry research to see what are the current best practices as well as platform/server options for deploying such a project. The software design document attached to this repository is a finalized version of my recommendations and findings, with version updates listed to reflect the changes I made throughout the consultation process.
