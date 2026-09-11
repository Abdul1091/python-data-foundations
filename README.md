# Python Data Foundations

A hands-on learning repository for strengthening Python and NumPy foundations for scientific and data analysis.

This repository documents my progression through Python and numerical computing as part of the **MIT Universal AI Program** and complementary **DataCamp** coursework, followed by independent practice and a small scientific data-analysis project.

My broader programming background includes the **ALX Software Engineering Program**, from foundations through Backend specialization, where I developed and worked on multiple software projects. 

Rather than reproducing course examples, the goal is to demonstrate independent understanding by applying each concept to new problems and progressively integrating the skills into practical scientific applications.

## Learning Sources

* **MIT Universal AI Program** — Python programming and computational foundations
* **DataCamp** — Python and NumPy coursework
* **Independent practice** — exercises designed to reinforce concepts and apply them to scientific and biological problems

## Learning Goals

This repository is being built progressively while I develop practical skills in:

* Python fundamentals & Control Flow
* Data structures (Lists & Dictionaries)
* Functions
* Python packages
* NumPy
* Numerical data analysis
* Applying programming concepts to scientific and biological datasets

## Progress

* [x] Python basics (`01_python_basics.ipynb`)
* [x] Control Flow & Logic (`02_logic_and_decisions.ipynb`)
* [ ] Loops & Debugging (`03_loops_and_debugging.ipynb`)
* [ ] Lists and dictionaries (`04_lists.ipynb`)
* [ ] Functions
* [ ] Python packages
* [ ] NumPy 1D arrays
* [ ] NumPy 2D arrays
* [ ] Biological Sample Analyzer

## Planned Repository Structure

```text
python-data-foundations/
├── README.md
├── pyproject.toml
├── uv.lock
│
├── exercises/
│   ├── 01_python_basics.ipynb
│   ├── 02_logic_and_decisions.ipynb
│   ├── 03_loops_and_debugging.ipynb
│   ├── 04_lists.ipynb
│   ├── 05_dictionaries.ipynb
│   ├── 06_functions.ipynb
│   ├── 07_packages.ipynb
│   ├── 08_numpy_1d.ipynb
│   └── 09_numpy_2d.ipynb
│
└── projects/
    └── biological-sample-analyzer/
        ├── README.md
        ├── analysis.ipynb
        └── data/
```

## Learning Approach

The repository is developed incrementally. Each topic is practiced through independent exercises rather than simply reproducing course examples.

The goal is to move from understanding individual Python concepts to applying them to increasingly realistic data-analysis problems.

Where appropriate, exercises use biological, laboratory, and scientific examples to connect programming concepts with my background in biochemistry and scientific research.

The repository also serves as a record of practical learning: concepts are introduced, practiced, applied, documented, and committed progressively using Git.

## Development Environment

The project uses:

* Python 3.12
* `uv` for Python project and dependency management
* Jupyter for interactive exercises
* NumPy for numerical computing
* Git for version control

## Current Stage

Completed:

- Environment setup (uv, Jupyter, NumPy).

- 01_python_basics.ipynb (variables, data types, arithmetic, indexing, slicing, string methods, interactive input, and capstone report generator).

- 02_logic_and_decisions.ipynb (Boolean truthiness, logical operators, if/elif/else control flow, string normalization in decisions, independent vs. nested conditionals, and Diagnostic Sample Classifier mini-challenge).

- 03_loops_and_debugging.ipynb (loop mechanics with for and while, range sequence generation, accumulator and counter patterns, manual trace tables, error classification, and instrumented debugging of silent logic defects).

- 04_lists.ipynb (list mechanics, mutability vs. string immutability, zero-based/negative indexing, sequence slicing, string parsing with .split(), parallel sequence pairing with zip(), custom sorting using key= and lambda expressions, and Laboratory Sample Manager capstone).

Next Stage: Dictionaries (`05_dictionaries.ipynb`), focusing on key-value mapping structures, lookup efficiency ($O(1)$ time complexity), dictionary methods (`.keys()`, `.values()`, `.items()`), nested dictionary models for structured laboratory samples, dictionary iteration, and data aggregation without external packages.