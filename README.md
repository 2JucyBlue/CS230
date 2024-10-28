# CS230
The Gaming Room Software Design Document – Reflection
Client Summary and Requirements
The client, The Gaming Room, is a company looking to expand its current Android game, Draw It or Lose It, into a multi-platform web-based environment. They required a software design that would allow their game to operate across various platforms while ensuring scalability, performance, and security. The game is a team-based drawing and guessing game, requiring support for multiple concurrent games, unique team and player names, and a single-instance architecture to optimize memory and storage usage.

Strengths in Documentation Development
One area I excelled in during the documentation process was the clarity and organization of technical details. I ensured that each section, from system architecture to memory management, was well-defined, enabling developers and stakeholders to understand the design decisions. This clarity is critical in technical documentation, as it bridges the gap between high-level concepts and implementation details, making it easier for the development team to follow.

Value of the Design Document in Development
Working through the design document was extremely beneficial in planning the application architecture before diving into coding. Documenting each component allowed me to think through potential challenges, such as memory constraints and user concurrency, which informed the technical decisions and structure. This process helped me anticipate problems early, leading to a more streamlined and efficient development phase.

Areas for Improvement
If I could revise one part of the design document, it would be the Distributed Systems and Networks section. I would improve it by detailing the load balancing and failover strategies to handle high traffic and server redundancy. Adding more specifics on the communication protocols, like RESTful APIs or WebSockets, would further clarify the integration requirements and enhance scalability and fault tolerance.

Interpreting and Implementing User Needs
To meet the user's needs, I focused on scalability and ease of use, both crucial for an application expected to handle multiple teams and players in real-time. I interpreted the client's need for uniqueness in game and team names and a multi-platform expansion by implementing Singleton and Iterator design patterns. It’s essential to consider user needs because, ultimately, the success of any software application is determined by how effectively it meets its intended purpose and user expectations. Designing with the end-user in mind ensures that the final product is both functional and user-friendly.

Approach to Software Design and Future Strategies
In this project, I adopted a structured approach, using object-oriented design principles like inheritance and encapsulation to create reusable and maintainable code. I focused on scalability, efficiency, and modularity, ensuring that each component could be adapted as the application grew. In the future, I would continue to use this structured approach but place more emphasis on iterative testing and client feedback throughout the design process. Techniques such as UML diagrams and design patterns will remain core tools in analyzing and structuring software applications to achieve clarity and modularity.
