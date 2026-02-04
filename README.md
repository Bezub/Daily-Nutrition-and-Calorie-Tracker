# Daily Nutrition and Calorie Intake Tracker

This is a C++ console-based application developed as a group project to help users register and track their daily nutrition and calorie intake. The program assists users in improving their health and fitness by monitoring daily food consumption based on their personal information, such as age, height, weight, and activity level. It also provides personalized food recommendations depending on remaining daily calories.

## Features

- User registration and profile management
- Track daily nutrition and calorie consumption
- View daily targets and summaries
- Add food to daily log (including custom foods)
- Meal recommendations based on remaining calories
- Update weight and recalculate targets
- Automatic daily tracking using a date-handling library

## Technologies Used

- C++
- Standard C++ libraries for file handling and date tracking

## My Contribution

I specifically implemented the **food logging and daily consumption features**, including:

- Adding foods to the daily log and associating them with meal types
- Searching for foods in the pre-existing food database and handling spelling-related matches
- Saving foods with their respective nutrition level and calorie amount to the user's personal file
- Creating functionality for custom food entries if the food was not in the database
- Displaying daily consumption summaries including calories and nutritional information

I also collaborated on overall program structure with my team members.

## How to Run

1. Make sure you have a C++ compiler installed (e.g., `g++`).
2. Open a terminal in the project folder.
3. Compile all the `.cpp` files together:

```bash
g++ main.cpp auth.cpp food.cpp profile.cpp recommendations.cpp utils.cpp -o calorie_tracker
