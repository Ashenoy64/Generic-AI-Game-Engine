# Generic AI Game Engine

This repository hosts a versatile game engine crafted to accommodate games playable by Generic AI. The engine allows for AI players to interact with games just like human players, providing a flexible framework for various game implementations.

## Overview

The Generic AI Game Engine enables developers to create games where an AI agent can seamlessly participate as a player. The engine operates under specific constraints:

- Games must feature finite states in every game step.
- Games should be deterministic, devoid of randomness.

At present, the engine includes two pre-implemented games: TicTacToe and Connect4. Each game supports four modes:

1. Human vs Human
2. Human vs AI
3. AI vs Human
4. AI vs AI

While the current implementations revolve around two-player dynamics, games are not inherently restricted to this setup.

## Getting Started

To develop a new game compatible with the engine, follow these steps:

1. Inherit from `GamePack.h`.
2. Override all necessary functions tailored to your game.
3. Register the new game in `GameList.h`.

Refer to the `TTT.h` and `Connect4.h` files, which provide insights into the existing game implementations.

Once these steps are executed, the engine will effortlessly integrate your game, facilitating AI players' engagement as per the designated modes.

## License

This project is licensed under the [MIT License](LICENSE), permitting unrestricted use, modification, and distribution in accordance with the stipulated terms.


