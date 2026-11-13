# Conscious Stupidity

**A top-down 2D action game inspired by Grand Theft Auto 2, built with C++ and SFML.**

Conscious Stupidity is my largest personal game development project. It is an exploration of 2D game development, combining gameplay mechanics, entity management, collision handling, game states and a custom graphical interface.

The project is built from the ground up using C++ and SFML, with an emphasis on separating gameplay systems into independent components.

## Gameplay

The game features a top-down perspective with an environment containing vehicles, characters, NPCs and interactive objects.

### Features

- Top-down 2D gameplay.
- Vehicle representation and gameplay.
- Player character and NPC entities.
- Projectile and bullet systems.
- Collision detection.
- Interactive objects and items.
- Obstacles and landscape management.
- Enemy elimination counter.
- Custom main menu and pause menu.
- Settings menu with resolution and volume controls.

## Architecture

The project is organized into several systems responsible for different aspects of the game.

| System | Responsibility |
|---|---|
| `Engine` | Main game engine and execution |
| `StateEngine` | Game state management |
| `GameState` | Main gameplay state |
| `MenuState` | Main menu |
| `PauseState` | Pause menu |
| `SettingState` | Game settings |
| `MainCharacter` | Player character |
| `NPC` | Non-player characters |
| `Car` | Vehicle entity |
| `Collision` | Collision handling |
| `Landscape` | Environment management |
| `Obstacle` | Obstacles |
| `Item` | Game objects and items |
| `Bullets` | Projectile management |
| `NPC_Configurator` | NPC configuration |

This structure separates entities, game states, world components and gameplay logic, making the project easier to extend and maintain.

## Technologies

- **C++** — primary programming language.
- **SFML** — graphics, window management and multimedia functionality.
- **Visual Studio** — development environment.

## Screenshots

<!-- Add your gameplay and menu screenshots here -->

### Gameplay

<img width="1278" height="719" alt="Screenshot 2026-11-13 211000" src="https://github.com/user-attachments/assets/262b74cd-9dfa-40cb-a6a5-9c895fbcfa61" />


### Pause Menu

<img width="1275" height="717" alt="Screenshot 2026-11-13 211022" src="https://github.com/user-attachments/assets/4b653048-151b-4693-91b7-6759ca218714" />

### Settings

<img width="1278" height="715" alt="Screenshot 2026-11-13 211046" src="https://github.com/user-attachments/assets/c872e65c-07b1-4fee-914f-2d57f330b448" />

## Building

The project uses Visual Studio and SFML.

1. Clone the repository:

   ```bash
   git clone https://github.com/pekkaone/SFML-Game-gta2-parody.git
   ```

2. Open the Visual Studio solution.
3. Configure the SFML dependencies if necessary.
4. Build and run the project.

## Project Status

A personal long-term game development project.

The project represents my exploration of C++ software architecture, game development and implementing interconnected gameplay systems using SFML.

## Author

Developed by [pekkaone](https://github.com/pekkaone).
