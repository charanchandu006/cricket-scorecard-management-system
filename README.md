# Cricket Scorecard Management System

## Overview

The **Cricket Scorecard Management System** is a console-based application developed in **C++** that simulates a real-time cricket match while maintaining comprehensive match statistics and scorecards. The project is designed using **Object-Oriented Programming (OOP)** principles to model various components of a cricket match, including players, teams, innings, bowling, batting, and match events.

The system performs ball-by-ball simulation, updates scorecards dynamically, tracks player performances, and generates detailed match summaries. It also incorporates additional features such as fantasy point calculation, catch ratings, injury handling, and special achievements like hat-tricks and maiden overs, making the simulation more realistic and engaging.

---

## Features

- Toss simulation with randomized outcomes
- Pitch selection affecting match conditions
- Real-time ball-by-ball scoring simulation
- Complete batting scorecards with individual statistics
- Detailed bowling scorecards with economy and wickets
- Extras tracking (Wides, No Balls, Byes, and Leg Byes)
- Catch rating system for fielding performance
- Player injury handling during the match
- Fantasy points calculation based on player performances
- Maiden over detection
- Hat-trick detection for bowlers
- Automatic Man of the Match selection
- Best Catch of the Match recognition
- Top performers summary at the end of the game

---

## OOP Concepts Used

The project demonstrates the practical implementation of several Object-Oriented Programming concepts, including:

- Classes and Objects
- Inheritance
- Polymorphism
- Encapsulation
- Templates
- Operator Overloading

These concepts help organize the application into modular, reusable, and maintainable components.

---

## Project Structure

```
├── main.cpp        # Driver program
├── Cricket.cpp     # Implementation of cricket simulation logic
└── cricket.h       # Class declarations and function prototypes
```

---

## Technologies Used

- C++
- Object-Oriented Programming (OOP)
- Standard Template Library (STL)

---

## Getting Started

### Clone the Repository

```bash
git clone <repository-url>
cd Cricket-Scorecard-Management-System
```

### Compile the Project

```bash
g++ main.cpp Cricket.cpp -o cricket
```

### Run the Application

```bash
./cricket
```

---

## Future Enhancements

The project can be extended with additional features such as:

- Partnership tracking and analysis
- More realistic injury management system
- Match history and data persistence using files or databases
- Enhanced statistics dashboard with player records
- Tournament and league management
- Interactive menu-driven user interface

---

## Learning Outcomes

This project helped strengthen concepts related to:

- Object-Oriented Programming design
- Modular software development
- Simulation-based programming
- Data structures for score and statistics management
- Building large-scale C++ console applications
