🏇 DerbyOS Web
High-Performance Monte Carlo Horse Race Simulator

DerbyOS Web is a responsive, browser-based implementation of a stochastic race simulation. Originally conceptualized as a C++ assignment, this project has been refactored into a modern web application using vanilla JavaScript and advanced CSS Grid layouts.

It demonstrates real-time DOM manipulation, state management logic, and a "Glassmorphism" UI design system.

🚀 Live Demo
Experience the simulation live: https://h33t589.github.io/DerbyOS-web/

✨ Features
Monte Carlo Simulation Engine: Probabilistic movement logic where each horse has unique speed and variance traits.
Reactive UI: Updates 60fps using CSS transitions and optimized DOM queries.
Betting System: Complete wallet state management, validation, and payout logic.
System Logging: Real-time terminal-style event logging for race progress.
Responsive Design: Fully fluid layout that adapts to mobile and desktop screens.
🛠️ Tech Stack
HTML5: Semantic structure.
CSS3: Custom Properties (Variables), Grid Layout, Backdrop Filters.
JavaScript (ES6+): Async simulation loops, Event Listeners, DOM manipulation. No external frameworks.
📸 Screenshots
Dashboard View

<img width="1472" height="1291" alt="image" src="https://github.com/user-attachments/assets/ccd866c3-d44c-46a3-95ca-9ba1a7cdb44f" />


A high-fidelity dark mode dashboard showing race progress and system logs.

🧠 How it Works
1. Initialization: The system generates a set of entities (Horses) with randomized statistical attributes (Base Speed, Variance).
2. The Race Loop: A setInterval loop triggers every 50ms.
3. State Update: On every tick, each horse's position is updated based on its attributes + a random probability factor (Monte Carlo).
4. Collision Detection: The engine checks if any entity has reached 100% progress.
5. Resolution: The loop breaks, the winner is determined, and the wallet state is updated based on the user's previous wager.

📝 Future Improvements
 Implement localStorage to save wallet progress between sessions.
 Add audio cues for race start and finish.
 Refactor simulation engine into a separate Web Worker for performance.

🤝 Contributing
This is a personal portfolio project, but feel free to fork it and improve the simulation algorithms!

📄 License
MIT License - feel free to use this code for your own learning.

