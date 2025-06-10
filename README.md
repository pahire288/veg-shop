Employee Management System
This is a simple, front-end web application for managing a list of employees. It's built entirely with HTML and JavaScript, allowing a user to dynamically add employees, grant them bonuses, and remove them from the list. All operations happen directly in the browser.

Features ✨
Add Employee: Users can input an employee's name, ID, and salary and add them to the system.
Employee Cards: Each added employee is displayed in a dedicated card showing their details.
Fire Employee: Each employee card has a "Fire-Employee" button that, when clicked, removes the employee from the list.
Give Bonus: A "Bonus" button on each card allows a user to add a bonus amount to the employee's base salary. The salary displayed on the card updates to reflect the new total.
Dynamic Interface: The list of employees and their details are updated in real-time without needing to reload the page.
How It Works ⚙️
The application is controlled by a single JavaScript function, AddEmployee(), and a few event listeners.

AddEmployee() function:

This function is triggered when the "ADD Employee" button is clicked.
It reads the values from the name, id, and salary input fields.
It dynamically creates a new div element with the class employee.
This new div is populated with the employee's information, along with a "Fire-Employee" button, a "Bonus" button, and an input field for the bonus amount.
Event Listeners:

Fire Employee: An event listener is attached to the "Fire-Employee" button on each employee card. When clicked, it calls the remove() method on the parent element (div.employee), deleting that card from the display.
Add Bonus: An event listener on the "Bonus" button reads the bonus amount entered, adds it to the employee's initial salary, and updates the salary text on the card to show the new, increased amount.
How to Use 🚀
Open the HTML File: Open the index.html file in any modern web browser.
Fill in Details: Enter the employee's name, ID, and starting salary in the provided input fields at the top.
Add the Employee: Click the "ADD Employee" button. A new card for that employee will appear below.
Grant a Bonus: To add a bonus, type the bonus amount into the "Bonus Amount" field on a specific employee's card and click the "Bonus" button next to it. The salary will update.
Remove an Employee: To remove an employee, simply click the "Fire-Employee" button on their card.
⚠️ Important Note
This is a front-end-only application. All data is stored in the browser's memory and will be lost if you refresh the page. There is no backend database connected to this system.
