# Tenzies Game

**React-based dice matching game with confetti celebration**

---

## Table of Contents
1. [About The Project](#about-the-project)  
   [Built With](#built-with)  
2. [How to Play](#how-to-play)  
3. [Getting Started](#getting-started)  
4. [App Screenshots](#app-screenshots)

---

## About The Project

A React implementation of the Tenzies dice game where players must match all 10 dice to win. Features include:
- Interactive dice with "hold" mechanic
- Victory confetti animation
- ARIA accessibility attributes
- Auto-focus on action buttons
- Responsive design

Originally created as an educational project for learning React state management and component interaction.

### Built With
- **React**  
- **Vite**  
- **nanoid** (unique ID generation)  
- **react-confetti** (victory animation)  

---

## How to Play
1. Click "Roll" to generate new dice values  
2. Click individual dice to freeze their current value  
3. Continue rolling until all dice show the same number  
4. Win the game by matching all 10 dice  
5. Click "New Game" to restart  

Key features:  
- Visual feedback for held dice (green background)  
- Screen reader support  
- Instant game reset functionality  
- Responsive touch/click interactions  

---

## Getting Started

1. Clone the repository  
2. Install dependencies:  
```bash
npm install

## App Screenshots
![Tenzies Start](/images/tenzies-start.png)
![Tenzies Started](/images/tenzies-started.png)
![Tenzies Game Proccess](/images/tenzies-game-process.png)
![Tenzies Game Completed](/images/tenzies-game-completed.png)