# Draw It or Lose It - Software Design Documentation  
**Author**: Jacob Hasbrook  

## Overview  

**Client**: The Gaming Room  
**Project Goal**: My objective was to develop a scalable, web-based game application called **Draw It or Lose It**. The Gaming Room wanted a transformation from an Android only app to a cross-platform experience that would allow multiple players and teams with unique identifiers to interact seamlessly. I used the Singleton pattern to maintain one active instance of the game at any time, ensuring consistent client-server interactions across various platforms, including desktops, mobile devices, and web browsers.

---

## Project Questions & Insights ##

### 1. **Who was the client, and what software did they want designed?**  
   The Gaming Room, my client, requested a multiplayer game application, **Draw It or Lose It**. They wanted to extend the game’s functionality beyond Android to support multiple platforms, enabling seamless operation and player management. This required scalable infrastructure and robust team management within the game.

### 2. **What aspects of the documentation did I do particularly well?**  
   I believe I effectively captured the client’s requirements, addressing critical details in platform constraints, scalability, and security considerations. This clarity ensured that the development plan remained aligned with the client’s vision and objectives throughout the process.

### 3. **What was helpful about working through a design document during development?**  
   The design document served as a blueprint, allowing me to streamline the coding process by organizing objectives and structuring the application. By breaking down complex requirements early on, it simplified the implementation and testing phases, allowing for a more focused and efficient development process.

### 4. **If I could revise one part of my work, what would it be and why?**  
   I would revise the **Recommendations section** for greater conciseness and improved clarity. A more structured layout that clearly distinguishes critical security features from infrastructure recommendations would enhance readability and better highlight essential components.

### 5. **How did I interpret the user’s needs and implement them into my design?**  
   I translated the user’s requirements into a modular system design, using the Singleton pattern to centralize control and ensure a unified, scalable experience. By considering the user’s needs, I aimed to create an efficient, engaging design that accommodates seamless gameplay across multiple platforms.

### 6. **How did I approach designing the software, and what techniques would I use in the future?**  
   My approach utilized **Object-Oriented Programming (OOP)** principles and **client-server architecture**, creating a centralized repository for game and player data. For future projects, I would consider incorporating **microservices** for individual components like user login, game state management to offer flexible scaling and easier maintenance, especially in high-demand, multi-user applications.
