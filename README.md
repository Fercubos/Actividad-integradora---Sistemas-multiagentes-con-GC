# TC2008B: Multi-Agent System Modeling with Computational Graphics

## Overview

This repository contains the code and documentation for the integrative. The project is divided into three main components:

### 1. Multi-Agent Systems

In this part, you manage a warehouse using five robots equipped with advanced sensors. The robots are tasked with organizing the warehouse by navigating, picking up, and stacking objects while avoiding collisions. The focus is on simulating the robots' behavior, optimizing their performance, and proposing strategies to improve efficiency.

### 2. Computational Graphics

This section involves creating a 3D model of the warehouse and robots. The project covers texture mapping, lighting, and basic collision detection. The goal is to visually represent the robots as they perform their tasks in the simulated environment, adding a layer of realism to the simulation.

### 3. Computer Vision

Here, the robots use cameras to identify and classify objects within the warehouse. Various computer vision models, such as YOLO or SAM, are implemented to enable the robots to recognize objects and make informed decisions based on their perceptions.

## Project Structure

- **Part 1: Multi-Agent Systems**
  - Documentation: PDF with agent and environment properties, success metrics, class diagrams, and ontology diagrams.
  - Code: Implemented simulation code for the multi-agent challenge.
  
- **Part 2: Computational Graphics**
  - File: `.unitypackage` containing all necessary assets for 3D rendering and simulation.

- **Part 3: Computer Vision**
  - Vision models and integration code.

## How to Run

1. Clone the repository.
2. Follow the instructions in the Part 1 and Part 2 directories to set up and run the simulations.
3. Use Unity to open the `.unitypackage` file for the 3D simulation.

## Notes

- The project simulates a warehouse with MxN grid spaces, K random objects, and at least 5 robots.
- Maximum execution time is limited by either steps or seconds.
