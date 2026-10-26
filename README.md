# Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?

The Gaming Room was the client, and they wanted to expand their existing Android game, Draw It or Lose It, into a web application that could run across different operating systems. The game needed to support multiple games, teams, and players while making sure each had unique identifiers, game names, and team names. They also wanted the application to use a single instance of the GameService class to manage the games.

# What did you do particularly well in developing this documentation?

I think I did well at comparing the different operating systems and explaining their advantages and disadvantages. I have personal experience with all of these operating systems and I was able to look at Linux, Windows, macOS, and mobile devices to determine which would work best for the application. I also think I did a good job explaining why Linux would be a good choice for hosting the game, especially when considering cost, security, and compatibility. 

# What about the process of working through a design document did you find helpful when developing the code?

Working through the design document helped me better understand how the different parts of the application needed to work together before writing the code. The UML diagram was especially helpful because it showed the relationships between the Game, Team, Player, and GameService classes. Having these relationships planned out made it easier to understand how to use inheritance and the singleton pattern when developing the application.

# If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

If I could revise one part of my documentation, I would probably expand on the system architecture. I explained how the application would use a client server architecture, but I think adding a diagram showing how the server, database, and different client devices communicate would make the design easier to understand. It would also help show how the application could support multiple users at once.

# How did you interpret the user's needs and implement them into your software design? Why is it so important to consider the user's needs when designing?

I started by looking at the requirements The Gaming Room provided and identifying what the application needed to do. Since the game needed to work across multiple operating systems that is web based, I recommended a Linux server approach and Java backend. I also used object oriented programming principles to organize the game, team, and player information while preventing duplicate names. Considering the user's needs is important because the application needs to meet the client's expectations rather than just function correctly from a technical standpoint.

# How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

I approached the design by first identifying the requirements and then breaking the application into smaller components. I used UML diagrams to understand the relationships between classes and researched different operating systems to determine the best platform for the application. In the future, I would absolutely continue using UML diagrams and design patterns to plan applications before writing code. I would also spend more time considering security, scalability, and how the application might need to change as more users begin using it.
