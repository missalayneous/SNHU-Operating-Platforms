# SNHU-Operating-Platforms
SNHU CS230 Operating Platforms

# Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?
The Gaming Room wanted to expand their existing Android game, Draw It or Lose It, into a web-based version that would work across desktops, laptops, and mobile devices. They needed a scalable platform where multiple teams and players could play at the same time, while making sure that game and team names stayed unique. They also wanted to ensure that only one instance of each game would exist in memory at a time, which influenced the design patterns I recommended.

# What did you do particularly well in developing this documentation?
I think I did a good job clearly outlining the design constraints and offering realistic solutions, like using WebSockets for real-time communication and building the front-end with responsive web technologies. I also feel like I showed strong understanding by incorporating the Singleton and Iterator design patterns to keep the system organized and efficient.

# What about the process of working through a design document did you find helpful when developing the code?
Working through the design document helped me think about the entire system before I started coding. It gave me a clear map of how the players, teams, and games would interact, and made it easier to prioritize what needed to be built first. It also helped me catch potential issues early, especially around scaling and managing unique names.

# If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
If I could revise one part, I would probably expand more on the System Architecture View. Even though it wasn’t required for this project, adding a simple diagram or more details about how the client, server, and storage would interact would have made the design even easier to understand.

# How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
I made sure to keep the users’ needs at the center of the design. I focused on making the game fast, reliable, and accessible across different devices. I also made sure that team and game names stayed unique, and that gameplay would feel smooth with real-time communication. I believe it’s really important to focus on user needs because if the game isn’t easy and enjoyable to use, people won’t stick with it, no matter how well it’s built behind the scenes.

# How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?
I started by carefully understanding the client’s goals and then picking technical solutions that matched those needs, like recommending Linux for hosting and using WebSockets for communication. In the future, I would also add early-stage flowcharts or wireframes to help catch any gaps even earlier. I would continue using design patterns like Singleton and Iterator where they make sense to keep the system scalable and easy to manage.
