[English](README.en.md) | [Русский](README.md)
# Software Development Tools

<div align="center">

<img src="https://play-lh.googleusercontent.com/mArlt7B_0PsBnRIIECGXcWn3xdql8eoFM7ObWsQmcKplMLVJjWr0lxh4Y2PF1IRloJC1xBsu2_Ol-F_nbqDx=w240-h480-rw" alt="NKEiVT" width="120"/>

**Repository of practical assignments for the course "Software Development Tools"**

[NKEiVT](http://www.nke.ru/) — Novosibirsk College of Electronics and Computing Technology

![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white)
![WPF](https://img.shields.io/badge/WPF-68217A?style=flat&logo=windows&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![Wiki](https://img.shields.io/badge/Wiki-Documentation-blue)
[![Status](https://img.shields.io/badge/status-in%20progress-yellow)](#)
[![Works](https://img.shields.io/badge/works-4%20of%2015-brightgreen)](#)
</div>

---
<details>
<summary><b>Table of Contents</b> (click to expand)</summary>

- [About the Repository](#about-the-repository)
- [List of Practical Assignments](#list-of-practical-assignments)
- [Completion Status](#completion-status)
- [Working with the Repository](#working-with-the-repository)
  - [Cloning without Submodules](#cloning-the-repository-without-submodules)
  - [Cloning with Submodules](#cloning-the-repository-with-all-submodules)
  - [Updating Submodules](#updating-submodules)
  - [Cloning the Wiki](#cloning-the-wiki)
  - [Useful Commands](#useful-commands)
- [Repository Structure](#repository-structure)
- [Requirements](#requirements)
- [Authors](#authors)

</details>

---

## About the Repository

This repository is a storage for all practical assignments for the course "Software Development Tools". Each practical assignment is placed in a separate git submodule with its own repository, which allows independent development and versioning of each task.

The repository covers the full course of 15 practical assignments: from classic design patterns (GoF) in C# to the development of full-fledged WPF applications with a SQLite database.

> All reports, diagrams, and examples are available in the repository's [Wiki](https://github.com/Nu-K2/InstrumentalTools/wiki).

## List of Practical Assignments

### Design Patterns (C#)

| № | Topic | Link | Report |
|---|---|---|---|
| 1 | Implementation of core patterns using the "Singleton" pattern in C# | [./practical-01-singleton](https://github.com/Nu-K2/ApplicationSettingsManager) | [Wiki](https://github.com/Nu-K2/InstrumentalTools/wiki/%D0%9F%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0-%E2%84%961.md) |
| 2 | Implementation of the creational "Abstract Factory" pattern in C# | [./practical-02-abstract-factory](https://github.com/Nu-K2/VehicleCreationSystem) | [Wiki](https://github.com/Nu-K2/InstrumentalTools/wiki/%D0%9F%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0-%E2%84%962.md) |
| 3 | Implementation of the structural "Adapter" pattern in C# | [./practical-03-adapter](https://github.com/Nu-K2/PaymentSystemIntegrationSystem) | [Wiki](https://github.com/Nu-K2/InstrumentalTools/wiki/%D0%9F%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0-%E2%84%963.md) |
| 4 | Implementation of the behavioral "Template Method" pattern in C# | [./practical-04-template-method](https://github.com/krill810/Template-Method) | [Wiki](https://github.com/Nu-K2/InstrumentalTools/wiki/%D0%9F%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0-%E2%84%964.md) |

### WPF and C#

| № | Topic | Link | Report |
|---|---|---|---|
| 5 | Developing an application using text components in WPF and C# | [./practical-05-wpf-text-components]() | [Wiki](https://github.com/Nu-K2/InstrumentalTools/wiki/%D0%9F%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0-%E2%84%96-5.md) |
| 6 | Developing an application with multiple forms in WPF and C# | [./practical-06-wpf-multiple-forms](https://github.com/Nu-K2/TaskManager) | [Wiki](https://github.com/Nu-K2/InstrumentalTools/wiki/%D0%9F%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0-%E2%84%96-6.md) |
| 7 | Developing an application with non-visual components in WPF and C# | [./practical-07-wpf-nonvisual-components]() | [Wiki](https://github.com/Nu-K2/InstrumentalTools/wiki/%D0%9F%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0-%E2%84%96-7.md) |
| 8 | Developing a game application in WPF and C# | [./practical-08-wpf-game-app]() | [Wiki](https://github.com/Nu-K2/InstrumentalTools/wiki/%D0%9F%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0-%E2%84%96-8.md) |

### Optimization, Refactoring, and UI

| № | Topic | Link | Report |
|---|---|---|---|
| 9 | Code optimization and refactoring in WPF and C# (basic level) | [./practical-09-refactoring-basic]() | [Wiki](https://github.com/Nu-K2/InstrumentalTools/wiki/%D0%9F%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0-%E2%84%96-9.md) |
| 10 | Code optimization and refactoring in WPF and C# (advanced level) | [./practical-10-refactoring-advanced]() | [Wiki](https://github.com/Nu-K2/InstrumentalTools/wiki/%D0%9F%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0-%E2%84%96-10.md) |
| 11 | User interface development in WPF and C# (basic level) | [./practical-11-ui-basic]() | [Wiki](https://github.com/Nu-K2/InstrumentalTools/wiki/%D0%9F%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0-%E2%84%96-11.md) |
| 12 | User interface development in WPF and C# (advanced level) | [./practical-12-ui-advanced]() | [Wiki](https://github.com/Nu-K2/InstrumentalTools/wiki/%D0%9F%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0-%E2%84%96-12.md) |

### Working with Databases

| № | Topic | Link | Report |
|---|---|---|---|
| 13–15 | Working with a local SQLite database in WPF and C# | [./practical-13-15-sqlite]() | [Wiki](https://github.com/Nu-K2/InstrumentalTools/wiki/%D0%9F%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0-%E2%84%96-13-15.md) |

---
## Completion Status

| № | Assignment | Status |
|---|---|---|
| 1 | Singleton | ✅ |
| 2 | Abstract Factory | ✅ |
| 3 | Adapter | ✅ |
| 4 | Template Method | ✅ |
| 5 | WPF: text components | 🚧 |
| 6 | WPF: multiple forms | 🚧 |
| 7 | WPF: non-visual components | 🚧 |
| 8 | WPF: game application | 🚧 |
| 9 | Refactoring (basic) | 🚧 |
| 10 | Refactoring (advanced) | 🚧 |
| 11 | UI (basic) | 🚧 |
| 12 | UI (advanced) | 🚧 |
| 13–15 | SQLite + WPF | 🚧 |

> Legend: ✅ completed · 🚧 in progress · ❌ not submitted

---
## Working with the Repository

### Cloning the repository (without submodules)

```bash
git clone https://github.com/Nu-K2/InstrumentalTools.git
```

In this case, the practical assignment folders will be empty until you initialize the submodules.

### Cloning the repository with all submodules

```bash
git clone --recurse-submodules https://github.com/Nu-K2/InstrumentalTools.git
```

If the repository has already been cloned without submodules:

```bash
git submodule update --init --recursive
```

### Updating submodules

Pull the latest changes in all submodules:

```bash
git submodule update --remote --merge
```

Or for a specific submodule:

```bash
git submodule update --remote practical-01
```

### Cloning the Wiki

The repository's Wiki is stored as a separate git repository:

```bash
git clone https://github.com/Nu-K2/InstrumentalTools.wiki.git
```

> Wiki home page: https://github.com/Nu-K2/InstrumentalTools/wiki

### Useful commands

| Command | Purpose |
|---|---|
| `git submodule status` | Show the status of submodules |
| `git submodule foreach git pull origin main` | Update all submodules to the latest changes |
| `git pull --recurse-submodules` | Update the main repository and submodules |
| `git clone --recurse-submodules --depth 1 <url>` | Fast clone without history |

---

## Repository Structure

```
InstrumentalTools/
├── README.md                          # ← you are here
├── .gitmodules                        # submodule configuration
├── practical-01-singleton/            # PA #1  — "Singleton" pattern
├── practical-02-abstract-factory/     # PA #2  — "Abstract Factory"
├── practical-03-adapter/              # PA #3  — "Adapter"
├── practical-04-template-method/      # PA #4  — "Template Method"
├── practical-05-wpf-text-components/  # PA #5  — text components
├── practical-06-wpf-multiple-forms/   # PA #6  — multiple forms
├── practical-07-wpf-nonvisual-comp/   # PA #7  — non-visual components
├── practical-08-wpf-game-app/         # PA #8  — game application
├── practical-09-refactoring-basic/    # PA #9  — refactoring (basic)
├── practical-10-refactoring-advanced/ # PA #10 — refactoring (advanced)
├── practical-11-ui-basic/             # PA #11 — UI (basic)
├── practical-12-ui-advanced/          # PA #12 — UI (advanced)
└── practical-13-15-sqlite/            # PA #13–15 — SQLite + WPF
```

---

## Requirements

- [.NET SDK](https://dotnet.microsoft.com/download) 6.0+
- Visual Studio 2022 / Rider / VS Code with the C# extension
- Windows 10/11 (for WPF projects)
- Git 2.13+

---
# Authors
<table> <tr> <td align="center"> <a href="https://github.com/krill810"> <img src="https://github.com/krill810.png" width="100" alt="Bedareva Sofya"/><br/> <sub><b>Bedareva Sofya</b></sub> </a><br/> <a href="https://github.com/krill810">@krill810</a> </td> <td align="center"> <a href="https://github.com/Nu-K2"> <img src="https://github.com/Nu-K2.png" width="100" alt="Storozheva Anna"/><br/> <sub><b>Storozheva Anna</b></sub> </a><br/> <a href="https://github.com/Nu-K2">@Nu-K2</a> </td> </tr> </table>

---
