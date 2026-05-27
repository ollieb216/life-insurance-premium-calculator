# Life Insurance Premium Calculator

Interactive Python Shiny app that estimates term life insurance premiums by modeling mortality probabilities with demographic risk factors.

Built as a personal project to develop my understanding of actuarial pricing fundamentals, including how mortality risk, cost loading, and policyholder characteristics drive premium calculation.

## How It Works

The app calculates an estimated annual premium using a simplified mortality model that adjusts a base probability of death by age, sex, BMI, health status, and nicotine usage. A cost loading factor is applied to the expected cost to arrive at the final premium. Users can select a death benefit amount and see real-time monthly and annual premium estimates.

## Risk Factors

- Age (18-75)
- Sex
- BMI (calculated from height and weight inputs)
- General health rating
- Nicotine/tobacco usage
- Death benefit amount ($250K to $10M)

## Tech Stack

- Python
- Shiny for Python
- NumPy

## Run Locally

```
pip install shiny numpy
shiny run --reload life_premium.py
```
