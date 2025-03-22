🥘 Speedy Meals

📌 Overview
Speedy Meals is a web application designed to help users find inspiration for quick and delicious meals. Users can create, view, update, and delete meal recipes easily. The application ensures a smooth experience with form validation and easy navigation.

🚀 Features
View Meals: Browse a list of meals with prep times.
Add a New Meal: Fill out a form to add a new meal with a name, cook time, and optional ingredients.
Edit Meal Details: Update meal details, including ingredients and directions.
Delete a Meal: Remove a meal from the list.
🖥️ User Flow
Home Page (/meals)

Displays a table with meal names, prep times, and action buttons (details | edit).
Users can click on details to view a specific meal.
Users can click on edit to update a meal.
A link at the top allows adding a new meal.
Create Meal Page (/meals/new)

Users enter a dish name, total minutes, directions, and optional ingredients.
Fields have validation (e.g., min/max characters, required fields).
Clicking Create submits the form and redirects to the meals list.
Meal Details Page (/meals/:id/details)

Displays meal name, cook time, ingredients, and directions.
A Remove button allows users to delete the meal.
Edit Meal Page (/meals/:id/edit)

Displays the meal details in editable fields.
Updates are reflected in real time.
Clicking Update saves changes and redirects to the meals list.
🛠️ Tech Stack
Frontend: HTML, CSS, JavaScript (React)
Backend: Node.js, Express
Database: MongoDB (if using a database)
Frameworks/Libraries: Bootstrap, Axios (for API requests)
📌 Installation & Setup
Clone the repository

sh
Copy
Edit
git clone https://github.com/yourusername/speedy-meals.git
cd speedy-meals
Install dependencies

sh
Copy
Edit
npm install
Run the application

sh
Copy
Edit
npm start
The app will be available at http://localhost:5173/.

📝 Validations
Dish Name: Required (3–20 characters).
Total Minutes: Required (2–240 minutes).
Directions: Required (min 10 characters).
Ingredients: Optional.
🗑️ Deleting a Meal
Clicking Remove deletes the meal and redirects the user to the main meal list.
📌 Future Enhancements
Add user authentication.
Allow users to upload images for meals.
Implement categories (e.g., breakfast, lunch, dinner).
Add a search feature.
📜 License
This project is open-source and available under the MIT License.
