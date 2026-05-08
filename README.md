# Australia Map Coloring (CSP)

## Overview
This project solves the **Australia Map Coloring problem** using a **Constraint Satisfaction Problem (CSP)** approach. The goal is to assign colors to regions such that no adjacent regions share the same color.

---

## Problem Description
- Regions: WA, NT, SA, Q, NSW, V, T  
- Colors used: Red, Green, Blue  
- Constraint: Neighboring regions must have different colors  

---

## Approach
- Model the problem as a **CSP**
- Use a **Backtracking Algorithm**
- Assign colors recursively while checking constraints

---

## How It Works
1. Select an unassigned region  
2. Try assigning a valid color  
3. Check if it violates constraints  
4. Continue recursively  
5. Backtrack if no valid color is found  

---

## Requirements
- Python 3.x  
- No external libraries required  

---

## How to Run (Google Colab)
1. Open Google Colab  
2. Create a new notebook  
3. Paste the code  
4. Run the cell  

---

## Sample Output
