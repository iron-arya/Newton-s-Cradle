# Newton's Cradle Simulation ⚙️

## Project Overview

This project is a physics simulation of **Newton's Cradle** built using **Matter.js** and **p5.js**. The simulation demonstrates the conservation of momentum and energy using swinging spheres connected with constraints.

Newton's Cradle is a classic physics device where lifting and releasing one ball transfers energy through the system causing the ball on the opposite end to swing.

---

## Features

* Physics based Newton's Cradle simulation
* Realistic ball collision behavior
* Constraint based suspension system
* Interactive control using keyboard
* Modular object-oriented structure

---

## Technologies Used

* **JavaScript**
* **p5.js** → Rendering
* **Matter.js** → Physics simulation
* **p5.play** → Optional sprite utilities
* **HTML5 Canvas**

---

## Project Structure

NewtonCradle/
│
├── index.html        # Main HTML file
├── sketch.js         # Main simulation logic
├── Bob.js            # Ball physics object
├── Ground.js         # Support structure
├── Suspender.js      # Constraint connections
├── matter.js         # Physics engine
├── p5.play.js        # Graphics helper library
├── p5.sound.js       # Sound library
└── README.md         # Project documentation

---

## How it Works

The simulation consists of:

**Bob class**
Represents the swinging balls using circular Matter bodies.

**Ground class**
Represents the top support beam.

**Suspender class**
Creates constraints connecting balls to the support.

**Sketch file**
Initializes the engine and creates the Newton's cradle structure.

The balls are connected using Matter constraints which act like strings. When force is applied to one ball, momentum transfers through the system.

---

## Controls

| Key        | Action                    |
| ---------- | ------------------------- |
| ↑ Up Arrow | Apply force to first ball |

---

## Installation and Setup

### Method 1 (Simple)

1 Clone repository

git clone https://github.com/yourusername/NewtonsCradle.git

2 Open folder

3 Run index.html in browser

---

### Method 2 (VS Code Recommended)

1 Install VS Code
2 Install Live Server extension
3 Right click index.html
4 Select Open with Live Server

---

## Physics Concepts Demonstrated

* Conservation of momentum
* Conservation of energy
* Elastic collisions
* Constraints and tension
* Force application

---

## Learning Outcomes

This project demonstrates:

* Physics engine integration
* Object oriented JavaScript
* Constraint systems in Matter.js
* Simulation design basics
* Code modularization

---

## Possible Improvements

To make this project stronger:

* Add collision sound effects
* Add UI labels
* Add adjustable ball count
* Add velocity display
* Add pause/reset buttons
* Add drag interaction with mouse
* Improve visuals (strings, shadows)

---

## Author

Arya Patel

Computer Science Student interested in:

* Physics simulations
* Game development
* Web development
* Creative coding

---

## License

Educational project.
