<h1 align="center">
  Mantis Quest
</h1>

## Objective
 
The main goal of this project was to create an educational game that teaches software defect tracking concepts in an engaging way, applying **HTML5, CSS3 and Vanilla JavaScript**. The game mechanics simulate real bug tracking workflows using **MantisBT** as a reference, covering the full defect lifecycle through quizzes, a bug tracker simulator, and boss battles, all presented through a retro arcade interface with CRT visual effects and Web Audio API sound design.
 
---
 
## Contents
 
1. [Project Overview](#project-overview)
2. [Objective](#objective)
3. [Technologies Used](#technologies-used)
4. [Installation and Execution](#installation-and-execution)
5. [Game Modes](#game-modes)
6. [Key Concepts Applied](#key-concepts-applied)
7. [Improvements to Implement](#improvements-to-implement)
8. [Contact](#contact)
---
 
## Project Overview
 
Mantis Quest is a retro arcade-inspired educational game that transforms QA and bug management into an interactive experience. It features a quiz system about MantisBT and Quality Assurance, a bug tracking simulator, a boss battle against critical bugs, an XP and ranking system, and a Hall of Fame, all contained in a single HTML file with no installation required.
 
---
 
## Technologies Used
 
- **HTML5**
- **CSS3**
- **JavaScript (Vanilla ES6+)**
- **Web Audio API**
- **Tabler Icons**
---
 
## Key Features
 
- Retro arcade interface with CRT and pixel visual effects
- Quiz system covering MantisBT, QA, defect management, and severity classification
- Bug tracking simulator where players create, assign, and resolve tickets
- Boss Battle mechanic against "The Big Bug" following real defect lifecycle steps
- XP and score progression with rank system (Junior Development → QA Hero → Bug Master)
- Hall of Fame ranking to track top players
- Retro sound effects generated via Web Audio API
- Fully self-contained: runs directly in the browser with no dependencies
---
 
## Improvements to Implement
 
- Enable a save system using localStorage to preserve progress across sessions
- Add online ranking with backend integration
- Develop multiple boss battles with increasing difficulty
- Expand the quiz bank with more questions and categories
- Optimise layout and interactions for mobile devices
- Implement multiplayer mode
---
 
## Installation and Execution
 
### 1. Clone the repository
 
```bash
git clone https://github.com/your-user/mantisquest.git
cd mantisquest
```
 
### 2. Run the project
 
Simply open the file in your browser:
 
```bash
# macOS/Linux
open mantisquest.html
 
# Windows
start mantisquest.html
```
 
No server, build step, or dependencies required.
 
---
 
## Game Modes
 
### Quiz Mode
Answer questions about MantisBT, QA, defect management, and severity classification to earn XP.
 
### Demo Mode
Simulate a real bug tracking environment: create bugs, define severity, resolve issues, and filter tickets.
 
### Boss Battle
Fight against "The Big Bug" by registering defects, defining severity, assigning developers, and closing issues.
 
### Memorial
A technical overview of MantisBT covering strengths, weaknesses, workflow, and use cases.
 
---
 
## Key Concepts Applied
 
- Single-file HTML5 architecture
- Retro CRT visual effects using CSS animations
- Dynamic DOM manipulation with JavaScript
- Game state management with XP and ranking logic
- Audio synthesis using the Web Audio API
- Bug tracking workflow simulation
- Defect lifecycle education through gamification
- Severity classification and QA concepts
---
 
## Contact
 
For questions, suggestions, or feedback, please open an issue on the repository or contact directly via GitHub.
