# CPP-01

## Overview

This repository contains a series of C++ exercises focused on object-oriented programming, memory management, and class design. Each exercise is organized into its own subdirectory (`ex00` to `ex05`) and demonstrates fundamental concepts using practical examples.

All code is written in C++98 and uses standard build tools (Makefiles) for compilation.

---

## Contents

### ex00 - Zombie Creation

- Learn about dynamic and stack allocation.
- Implement a `Zombie` class.
- Functions:
  - `newZombie(std::string name)` – creates a zombie on the heap.
  - `randomChump(std::string name)` – creates a zombie on the stack and announces.
- Build executable: `Zombie`

### ex01 - Zombie Horde

- Manage arrays of objects with dynamic memory.
- Implement a function to create a horde of zombies.
- Class: `Zombie`
- Function: `Zombie* zombieHorde(int N, std::string name)`
- Build executable: `Zombie`

### ex02 - Brain

- Simple demonstration of class encapsulation.
- Build executable: `Brain`

### ex03 - HumanA & HumanB

- Explore composition and references/pointers in classes.
- Implement `HumanA` (holds a reference to a `Weapon`) and `HumanB` (holds a pointer).
- Classes: `HumanA`, `HumanB`, `Weapon`
- Build executable: `violence`

### ex04 - Replace

- Text processing: replace occurrences of a string in a file.
- Build executable: `replace`

### ex05 - Harl

- Simple logger example with multiple levels of output.
- Class: `Harl` with methods for `debug`, `info`, `warning`, and `error`.
- Build executable: `Harl`

---

## Build Instructions

Each exercise has its own Makefile. To build an exercise, navigate to its directory and run:

```sh
make
```

To clean build files:

```sh
make clean
```

To remove all build artifacts:

```sh
make fclean
```

To rebuild:

```sh
make re
```

---

## Requirements

- **Compiler:** C++98 compatible compiler (e.g., `g++`)
- **OS:** Unix/Linux recommended

---

## Author

- Othmane Farissi ([Othmane-Farissi](https://github.com/Othmane-Farissi))

---

## License

This project is for educational purposes.
