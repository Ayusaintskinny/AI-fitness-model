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
Features

BMI Calculation (Body Mass Index)
BMI Category Classification
Daily Calorie Needs Calculation (using Mifflin-St Jeor Equation)
Personalized Fitness Recommendations
Activity Level Based Calorie Adjustment
Modular & Clean Function-Based Design
Technologies Used

Python 3
Standard Library (no external dependencies)
How to Run

Install Python 3.8+
Run the script: python main.py
Enter user details as prompted.
Testing Instructions

Test with different BMI ranges (underweight, healthy, overweight, obese)
Validate calorie outputs with online calorie calculators
Test gender variations
Test each activity level (1–5)
Screenshots
<img width="1522" height="1125" alt="Screenshot 2025-11-23 225752" src="https://github.com/user-attachments/assets/49c230f0-e469-46a8-bcbe-1c80f85fd133" />
<img width="1602" height="1132" alt="Screenshot 2025-11-23 225806" src="https://github.com/user-attachments/assets/5334766c-2a91-4648-b413-ed758a203543" />
<img width="1548" height="1110" alt="Screenshot 2025-11-23 225819" src="https://github.com/user-attachments/assets/76200020-ff70-442f-a527-dd9821229a1a" />




