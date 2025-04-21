# Sorbonne-Universite-MU4RBI02

# Sevens Card Game Competition Framework

## Project Overview
This document outlines the implementation of a competitive framework for the **Sevens** (並べ, Nana Narabe) card game. You will implement a strategy that competes against those of your classmates to see whose algorithm most effectively wins at the Sevens card game.

### The Game of Sevens
Sevens (also known as Fan Tan or Parliament) is a traditional card game played for generations across Japan and many other countries. It is a game of skill, timing, and strategy where players aim to empty their hands as quickly as possible.

The game starts with the 7 of diamonds on the table. Players can only play cards that are adjacent to cards already on the table (i.e., one rank higher or lower in the same suit). If a player cannot play, they must pass. The first player to empty their hand wins that round, and the other players are required to count the number of cards remaining in their hands. The game iterates into several rounds until one player reaches 50 points, signifying their loss.

### Framework Features
The competition framework offers:
- **Internal mode**: Run games with a default random play strategy.
- **Demo mode**: Run games with built-in sample strategies.
- **Competition mode**: Dynamically load and pit different student-implemented strategies against each other.

## Style Guide
In this project, you are constrained to use the following style guide to maintain your code efficiently:

- Use compiler flags `-Wall -Wextra -Werror -pedantic -pedantic-errors -O3` with `g++` to guarantee C++ norms in your code implementation, optimizing compilation.
- Use C++ 17 standard for modern features (`-std=c++17`).
- Minimize dynamic memory allocation and use STL containers for safer memory management.
- Follow strict variable naming conventions and avoid duplication of code.
- Use `snake_case` for variable and method naming, with new types starting with a capital letter.
- Constants should be declared using SCREAMING_SNAKE_CASE.
- Use `const` where input should be constant and utilize references or pointers when passing arguments.

## Provided Files
You are provided with a collection of files that implement the game framework, including various sample strategies and utilities for dynamic loading of strategy implementations.

## Implementation Roadmap
A roadmap is proposed to guide you through the various tasks in this project, including understanding the strategy interface, studying provided strategies, implementing your strategy, and testing against different modes.

## Your Task
Your task is to implement a strategy for playing the Sevens card game that outperforms the provided sample strategies and those of your classmates.

### Implementation Steps
1. Make a copy of `StudentTemplate.cpp` and rename it to reflect your strategy (e.g., `AggressiveStrategy.cpp`).
2. Rename the class inside to match your strategy name.
3. Implement the required methods, focusing particularly on `selectCardToPlay`, which is where your strategy logic will reside.
4. Implement methods to track game progress if needed.
5. Change the `getName()` method to return your unique strategy name.

## Additional Notes
- For detailed implementation and code examples, refer to the provided files and sample strategies.
- Experiment with different approaches and refine your strategy based on testing outcomes.

---
