## Calorie Counter

**Overview**

The Calorie Counter is a web application designed to help users track their daily calorie intake and expenditure. It allows users to input their daily calorie budget, add entries for different meals and exercises, and calculate the remaining calories for the day.

**Features**

Add Entries: Users can add food and exercise entries for breakfast, lunch, dinner, snacks, and exercise.
Calculate Calories: The application calculates and displays the total calories consumed, burned through exercise, and remaining calories against the budget.
Clear Form: Users can clear all input fields and reset the form.

**Getting Started**

Prerequisites
Basic understanding of HTML, CSS, and JavaScript.
A web browser to run and test the application.

**Installation**

Clone the Repository (if applicable):

bash
Copy code
git clone <https://github.com/XavierBlackwell/Calorie-Counter.git>
Navigate to the Project Directory:

bash
Copy code
cd calorie-counter
Open index.html in a Web Browser: Simply open the index.html file in your web browser to start using the application.

**Usage**

Set Calorie Budget: Enter your daily calorie budget in the input field provided.

Add Entries: Use the dropdown menu to select where you want to add your entry (breakfast, lunch, dinner, snacks, or exercise). Click "Add Entry" to insert a new entry field.

Calculate Remaining Calories: Click "Calculate Remaining Calories" to see the total calories consumed, burned, and remaining.

Clear Form: Click "Clear" to reset all fields and hide the results.

**Code Explanation**

**HTML Structure:**

Contains input fields for calorie budget and entries for meals and exercises.
Includes buttons for adding entries, calculating calories, and clearing the form.
The output section displays results and is hidden by default.

**JavaScript Functions:**

cleanInputString(str): Cleans input strings by removing unwanted characters.
isInvalidInput(str): Checks if the input is in scientific notation.
addEntry(): Adds new input fields for food or exercise based on user selection.
calculateCalories(e): Calculates and displays the remaining calories based on inputs.
getCaloriesFromInputs(list): Retrieves and sums up calorie values from input fields.
clearForm(): Clears all input fields and hides the output.

**Event Listeners:**

addEntryButton: Adds new entry fields when clicked.
calorieCounter: Calculates and displays calorie information on form submission.
clearButton: Clears the form when clicked.
Contributing
If you would like to contribute to this project, please fork the repository, make your changes, and submit a pull request. Your contributions are welcome!

**License**

This project is licensed under the MIT License. See the [MIT License](https://opensource.org/licenses/MIT) for details.