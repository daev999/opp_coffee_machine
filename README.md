# Coffee Machine (Python OOP)

## Overview
A console-based coffee machine simulation built using Object-Oriented Programming.
The project models real machine components as separate classes.

## How the Machine Works
1. The user selects a drink from the menu
2. The machine checks if resources are sufficient
3. Payment is processed
4. Ingredients are deducted
5. The drink is made

## Classes Explained

### Menu & MenuItem
- Stores available drinks
- Each drink has a name, cost, and ingredients

### CoffeeMaker
- Tracks available resources
- Checks if ingredients are sufficient
- Makes coffee by deducting resources

### MoneyMachine
- Handles payment
- Tracks profit

### main.py
- Controls the program flow
- Connects all classes together

## What I Learned
- How objects interact with each other
- Why passing objects (not strings) matters
- How OOP reduces spaghetti code
- How to read documentation and assemble a system
