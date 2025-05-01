# 🥗 Meal Planner and Shopping List Generator

**Course:** CIND 830 - Python Programming for Data Science  
**Institution:** Toronto Metropolitan University  
**Term:** Winter 2025  
**Assignment Type:** Individual

---

## 📋 Description

This Python program is an interactive **Meal Planner and Shopping List Generator**. It utilizes menu-driven programming, loops, and conditional statements. The app scrapes online recipes, allows users to add them to a meal plan, generates shopping lists, and computes statistics on ingredients.

---

## 🔧 Features

- Scrape recipes using `recipe-scrapers` from sites like AllRecipes.com
- Add a **custom recipe** (e.g., family recipe)
- Interactive menu with the following options:
  1. View Recipes
  2. Add Recipe to Meal Plan
  3. View Meal Plan
  4. Generate Shopping List
  5. Calculate Statistics
  6. Exit
- Shopping list is merged and displayed using `Counter` and `tabulate`
- Ingredient statistics include average and median
- Colored terminal output using `termcolor`

---

## 📦 Setup Instructions

1. Clone the repository and open the `.ipynb` file in Jupyter Notebook.

2. Install the required libraries:

```python
%pip install recipe-scrapers termcolor tabulate
