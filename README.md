## Project Description

 **FitBuddy – AI Fitness Plan Generator** is a web-based fitness planning application designed to create personalized 7-day workout plans based on a user's basic information, fitness goal, and preferred workout intensity.

 The application allows users to enter their **name, user ID, age, weight, fitness goal, and workout intensity**. Based on these inputs, FitBuddy automatically generates a weekly exercise plan covering different areas such as full-body training, cardio, strength, core stability, mobility, and flexibility.

 The project also includes a **feedback-based plan refinement feature**. Users can provide feedback such as _“more cardio,” “include more rest days,” “add yoga,”_ or _“more core exercises.”_ The application then modifies the generated plan according to the feedback.

 A separate **Admin / All Users** section stores the users and their generated plans using the browser's **localStorage**. Administrators can view the original and updated plans and delete user records when required.

 ### Key Features

 - **Personalized workout generation** based on fitness goal and intensity.
- Supports four fitness goals:
  - Weight Loss
  - Muscle Gain
  - General Wellness
  - Flexibility
- Three workout intensity levels:
  - Low
  - Medium
  - High
- **7-day workout schedule** with different daily focuses.
- **Nutrition and recovery tips** based on the selected goal.
- **Feedback-based plan customization**.
- **User management dashboard** for viewing generated plans.
- **Local data storage** using browser `localStorage`.
- **Responsive design** suitable for mobile and desktop screens.
- **Dark/light theme support** based on the user's system preference.
- No external backend is required; the demo operates entirely in the browser.

 ### Technologies Used

 - **HTML5** – structures the application.
- **CSS3** – provides responsive styling, layouts, colors, themes, and UI components.
- **JavaScript** – handles form processing, workout-plan generation, feedback adaptation, user management, and local storage.
- **Google Fonts** – uses Oswald and Work Sans for the interface typography.
- **Browser LocalStorage** – stores user information and workout plans locally.

 ### Project Objective

 The main objective of FitBuddy is to provide a simple and interactive fitness assistant that helps users obtain a structured workout routine without manually designing a weekly plan. The project demonstrates how a front-end web application can use user inputs and predefined logic to generate and adapt personalized fitness plans.

 **Note:** Despite the project name, the current implementation is primarily a **rule-based JavaScript fitness-plan generator**, rather than a connection to a real AI model.
