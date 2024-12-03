Dynamic Form Generator
This is a React project that dynamically generates forms based on the selected type. Users can fill out the form, track their progress using a progress bar, and view submitted data in a table format. The application is styled using CSS and supports CRUD operations for managing submitted data.

Features
Dynamic Form Generation: Select different form types to generate custom forms.
Progress Tracking: Shows a progress bar to indicate form completion.
CRUD Operations: Add, view, and delete form entries dynamically.
Table Management: Each form type has its own table, and tables are removed automatically when all entries are deleted.
Responsive Design: The application is designed to adapt to various screen sizes.
Form Types
User Information

First Name (Required)
Last Name (Required)
Age (Optional)
Address Information

Street (Required)
City (Required)
State (Dropdown, Required)
Zip Code (Optional)
Payment Information

Card Number (Required)
Expiry Date (Required)
CVV (Required)
Cardholder Name (Required)
Prerequisites
Ensure you have the following installed:

Node.js: Version 14 or higher
npm: Comes bundled with Node.js
A modern web browser (e.g., Chrome, Edge, Firefox)
Installation and Running the Application
Clone the Repository

bash
Copy code
git clone https://github.com/shivank-coder/Dynamic-Form.git
cd dynamic-form-generator
Install Dependencies

bash
Copy code
npm install
Start the Development Server

bash
Copy code
npm start
Open the Application

Once the server starts, open your browser and navigate to:

arduino
Copy code
http://localhost:3000
File Structure
DynamicForm.js: Contains the main logic for form generation, CRUD operations, and table management.
index.js: Entry point of the application.
App.js: Root component where DynamicForm is used.
App.css: Styles for the application.
Usage
Select a form type from the dropdown.
Fill out the fields as per the form requirements.
Submit the form to view the data in the corresponding table.
Use the Delete button to remove specific entries.
Once all entries for a form type are deleted, the table is automatically removed.
Technologies Used
React: For building the UI components.
CSS: For styling the application.
JavaScript (ES6+): For handling application logic.
Add screenshots of the application here to demonstrate its functionality.

Future Enhancements
Add persistent storage using local storage or a database.
Support for editing existing entries.
Integration with a backend API for data storage.
