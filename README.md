# Wall Builder Unreal Engine Project

This Unreal Engine project showcases a system for generating walls using splines. It includes functionality for creating, modifying, and deleting walls dynamically within the game environment.

## Table of Contents

- [Introduction](#introduction)
- [Usage](#usage)
- [Features](#features)
- [Sample](#Sample)

## Introduction

The project consists of two main classes:

1. **WallSpline**
   - Represents a spline-based wall generation system.
   - Handles the creation, modification, and deletion of wall segments based on spline points.
   - Allows undo functionality for removing spline points and associated wall segments.
   - Provides methods for generating walls and managing spline mesh components.

2. **WallBuilderController**
   - Acts as a player controller managing the wall building process.
   - Utilizes input actions to interact with the game world (e.g., left-click for adding spline points, right-click for creating new walls, undoing actions).
   - Manages multiple instances of WallSpline for building and managing multiple walls simultaneously.
   - Provides functionality for deleting individual walls, all walls, and navigating between walls.

## Usage

### Building Walls
- Left-click on the game environment to add spline points and start building a wall.
- Right-click to finalize the current wall and start a new one.

### Undo and Delete
- Press 'Z' or use the undo functionality to remove the last added spline point or delete the current wall if no points remain.
- Use the provided actions to delete individual walls or all walls in the scene.

### Navigation
- Navigate between multiple walls using the provided functionality to switch focus between wall building operations.

## Features

- **Dynamic Wall Generation:** Utilizes splines to dynamically generate walls in the game environment based on user input.
- **Undo Functionality:** Allows users to undo actions such as adding spline points or deleting walls, providing a flexible editing experience.
- **Multiple Wall Support:** Supports the creation and management of multiple walls simultaneously, enhancing scene complexity and design possibilities.
- **Interactive Input Actions:** Utilizes intuitive input actions (e.g., left-click, right-click) for adding spline points, creating new walls, and managing construction.
- **Customizable Meshes and Materials:** Provides flexibility to customize spline meshes and materials, allowing for diverse visual styles and themes in wall construction.
- **Navigation Controls:** Includes functionality for navigating between walls, enabling users to focus on specific wall-building operations efficiently.
- **User-Friendly Interface:** Offers a straightforward interface for wall building, making it accessible and easy to use for users of varying skill levels.
- **Contributions and Customization:** Allows for contributions and customization, providing a platform for community-driven improvements, new features, and bug fixes.

## Sample

1. **Sample Construction Demo Snapshot**
   - 

2. **Sample Project Video**
   - https://drive.google.com/file/d/15sx4A3glYcf9WUYHzOIdyGokpj2tIhle/view?usp=drive_link
  
