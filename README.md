# -YuktiC-oreX-Python-Bug-Demo
# Python Bug Demo — YuktiC-oreX

A simple Python calculator project created to test
AI-powered bug detection and automatic code repair.

## Features

- Addition
- Subtraction
- Multiplication
- Division
- Division-by-zero handling

## Known Issue

The subtraction function currently returns an incorrect result
because it uses addition instead of subtraction.

Example:

Expected:
10 - 5 = 5

Actual:
10 - 5 = 15

## Run the Project

```bash
python calculator.py
```

## Run Tests

Install pytest:

```bash
pip install pytest
```

Run:

```bash
pytest -v
```

## Purpose

This repository contains an intentionally introduced bug
for testing the YuktiC-oreX autonomous code repair platform.
