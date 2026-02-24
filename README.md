# AI_Game-AttackerVsDefender
Run the game:
python AI_Game-AttackerVsDefender\attacker_vs_defender.py

# Attacker vs Defender  
### AI-Powered Turn-Based Strategy Game (Python + Pygame)

A 5×5 grid-based strategic game developed using **Python and Pygame**, featuring an AI opponent powered by a combination of **Genetic Algorithm (DEAP)** and **Fuzzy Logic (scikit-fuzzy)**.

This project demonstrates applied AI decision-making, evolutionary optimization, and game system design within an interactive graphical environment.

---

## 📸 Screenshots

### Opening Page
<p align="center">
  <img src=""C:\Users\mahit\Pictures\Screenshots\Screenshot 2<img width="1368" height="786" alt="Screenshot 2026-02-24 134412" src="https://github.com/user-attachments/assets/d98f5025-7b5d-46de-aa4a-b953238690c5" />
026-02-24 134412.png"" width="700" alt="Opening Page Screenshot"/>
</p>

---

### Gameplay
<p align="center">
  <img src="images/gameplay.png" width="700" alt="Gameplay Screenshot"/>
</p>

---

### Winner Screen
<p align="center">
  <img src="images/winner-screen.png" width="700" alt="Winner Screen Screenshot"/>
</p>

> Replace the image paths above with your actual screenshots.

---

## Features

- Interactive GUI built with **Pygame**
- 5×5 tactical grid system
- Multiple unit types with health-based mechanics
- Turn-based strategy gameplay
- AI opponent using:
  - Genetic Algorithm for move sequence optimization
  - Fuzzy Logic for fitness evaluation
- Sound effects and background music integration
- Object-oriented game architecture

---

##  AI Architecture

The computer opponent does not play randomly. Instead, it:

1. Generates multiple possible move sequences  
2. Evolves them using Genetic Algorithm operations:
   - Selection (Tournament)
   - Crossover (Two-point)
   - Mutation  
3. Evaluates sequences using Fuzzy Logic based on:
   - Unit health states
   - Expected damage impact  
4. Selects the highest-fitness action

This creates a strategic and adaptive AI behavior.

---

##  Technology Stack

- Python 3  
- Pygame  
- NumPy  
- DEAP (Evolutionary Computation Framework)  
- scikit-fuzzy  

---

##  Project Structure

