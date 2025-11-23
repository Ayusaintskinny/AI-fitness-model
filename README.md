# AI-fitness-model
This code covers essential metrics for basic fitness and health estimation and is appropriate for beginner to intermediate users interested in monitoring their body composition and caloric needs.
  AI-fitness-model
This code covers essential metrics for basic fitness and health estimation and is appropriate for beginner to intermediate users interested in monitoring their body composition and caloric needs.
 AI Fitness & Health Calculator

A simple Python-based health and fitness tool to help you estimate your BMI, daily caloric requirements, and optimal macronutrient intake based on personal data and activity levels.

 Features
 BMI Calculation: Provides your Body Mass Index and health category (Underweight, Healthy, Overweight, Obese).
 BMR Calculation: Computes your Basal Metabolic Rate using the Mifflin-St Jeor equation.
 TDEE Calculation: Estimates your Total Daily Energy Expenditure based on selected activity level.
 Macronutrient Breakdown: Recommends grams of protein, fat, and carbohydrates per day.
 Personalized Advice: Gives fitness and nutrition tips tailored to your BMI category.

 Usage

1. Clone or download this script to your Python environment.
2. Run the script:
3. Input the required details when prompted:
- Gender (male/female)
- Age (in years)
- Weight (in kilograms)
- Height (in centimeters)
- Activity Level (choose from the guide provided)

4. Review your health report:
- BMI and health category
- Basal Metabolic Rate (BMR)
- Total Daily Energy Expenditure (TDEE)
- Recommended daily protein, fat, and carb intake
- Personalized fitness advice

  Activity Levels Reference

| Level | Description                        |
|-------|------------------------------------|
| 1     | Not active                         |
| 2     | Light exercise 1–3 days/week       |
| 3     | Moderate exercise 3–5 days/week    |
| 4     | Hard exercise 6–7 days/week        |
| 5     | Athlete training                   |

  How Macronutrients Are Calculated

- Protein: 20% of total calories (\( \frac{\text{Calories} \times 0.2}{4} \) grams)
- Fat: 25% of total calories (\( \frac{\text{Calories} \times 0.25}{9} \) grams)
- Carbohydrates: 55% of total calories (\( \frac{\text{Calories} \times 0.55}{4} \) grams)

These are suggested for maintenance. Adjust proportions for special goals as needed.

 Customization

To tailor recommendations for specific goals (muscle building, weight loss), modify the macronutrient ratios or calorie expectations in the script.
