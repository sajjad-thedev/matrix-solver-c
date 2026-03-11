<div align="center">
<h1>Matrix Solver</h1>

**A lightweight C CLI tool for solving systems of linear equations**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Platform](https://img.shields.io/badge/platform-Linux%20%7C%20Windows-lightgrey)]()
[![Language](https://img.shields.io/badge/language-C-orange.svg)]()

[Installation](#installation) • [Usage](#usage) • [Building from Source](#building-from-source) • [Uninstallation](#uninstallation)

</div>

---

## Overview

A command-line tool that solves n×n systems of linear equations using Gaussian elimination with partial pivoting. Handles unique solutions, infinite solutions, and inconsistent systems — with clear output and error messages.

---

## Features

- Solve any n×n system of linear equations
- Calculate matrix determinants
- Automatic solution classification — unique, infinite, or no solution
- Singular matrix detection
- Colorful terminal UI with input validation

---

## Installation

### Linux / macOS

```bash
curl -L https://raw.githubusercontent.com/sajjad-thedev/matrix-solver-c/main/install.sh | bash
```

### Windows (PowerShell — run as Administrator)

```powershell
irm https://raw.githubusercontent.com/sajjad-thedev/matrix-solver-c/main/install.ps1 | iex
```

> On Windows, restart PowerShell after installation to update PATH.

---

## Usage

```bash
matrix-solver
```

The program walks you through entering your matrix dimensions, coefficients, and constants — then outputs the solution.

---

## Building from Source

**Prerequisites:** GCC, Git

```bash
git clone https://github.com/sajjad-thedev/matrix-solver-c.git
cd matrix-solver-c
gcc -o matrix-solver main.c matrix.c -lm
./matrix-solver
```

---

## Project Structure

```
matrix-solver-c/
├── main.c        # UI and input handling
├── matrix.c      # Core math operations
├── matrix.h      # Headers and structs
├── install.sh    # Linux installer
├── install.ps1   # Windows installer
└── README.md
```

---

## Uninstallation

### Linux
```bash
curl -sSL https://raw.githubusercontent.com/sajjad-thedev/matrix-solver-c/main/uninstall.sh | bash
```

### Windows
```powershell
irm https://raw.githubusercontent.com/sajjad-thedev/matrix-solver-c/main/uninstall.ps1 | iex
```

---

## License

MIT — see [LICENSE](LICENSE) for details.

---

## Author

**Sajjad Ahmed**
GitHub: [@sajjad-thedev](https://github.com/sajjad-thedev) • sajjad.thedev@gmail.com

Special thanks to Mr. Hammad Nasir for the idea and testing support.

---

<div align="center">
If this was useful, a ⭐ is appreciated.
</div>
