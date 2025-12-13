# Assignment 6 Part 2 - Writeup

---

## Question 1: Feature Importance

Based on your house price model, rank the four features from most important to least important. Explain how you determined this ranking.

**YOUR ANSWER:**
1. Most Important: Square Feet
2. Bedrooms
4. Bathrooms
5. Least Important: Age

**Explanation:**

I ordered the features by how strong their relationship was with the best-fit line. SquareFeet showed the strongest connection, while Age showed the weakest. I ranked Bedrooms higher than Bathrooms because the data for Bedrooms was more evenly distributed.


---

## Question 2: Interpreting Coefficients

Choose TWO features from your model and explain what their coefficients mean in plain English. For example: "Each additional bedroom increases the price by $___"

**Feature 1:**
SquareFeet
The coefficient for SquareFeet is 121.11, meaning that for every square foot, the house price increases by $121.11.

**Feature 2:**
The coefficient for Age is −950.35, which means that for each year older a house is, its price decreases by $950.35.

---

## Question 3: Model Performance

What was your model's R² score? What does this tell you about how well your model predicts house prices? Is there room for improvement?

**YOUR ANSWER:**
The R² score is 0.9936, which means the model explains about 99.36% of the house prices. This is a really high score, so the model fits the data well. However, even with a high score, the model could still be overfitting, which means it might not work as well on new data.



---

## Question 4: Adding Features

If you could add TWO more features to improve your house price predictions, what would they be and why?

**Feature 1:**
Location

**Why it would help:**

House prices change a lot depending on where the house is. For example, the same house would usually cost more in a city than in a rural area.
**Feature 2:**
Floors

**Why it would help:**
The number of floors can affect the price of a house. Two houses might have the same number of bedrooms and bathrooms, but a two-story house would usually cost more than a one-story house.

---

## Question 5: Model Trust

Would you trust this model to predict the price of a house with 6 bedrooms, 4 bathrooms, 3000 sq ft, and 5 years old? Why or why not? (Hint: Think about the range of your training data)

**YOUR ANSWER:**
I wouldn’t trust this model to predict the price of that house because some of the values are outside the range of the data used to train the model. When a model predicts outside its data range, the result is an estimate and may not be accurate.

