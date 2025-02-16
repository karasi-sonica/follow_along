Project Description
Ecommerce-Follow-Along is a comprehensive project designed to guide developers through the process of building an e-commerce application from scratch. This project will cover various aspects of web development, including front-end design, back-end integration, and database management, providing a hands-on learning experience.

Milestone 1: Project Overview
In this session, we focused on the foundational elements of the Ecommerce-Follow-Along project. Key topics covered included:

1. Project Setup
We initialized the GitHub repository and set up the basic structure for our application.
2. Technology Stack
An overview of the technologies that will be utilized throughout the project:
Node.js: JavaScript runtime for the back-end.
Express.js: Web framework for building the back-end API.
MongoDB: NoSQL database to store application data.
React (MUI): Front-end framework using React with Material-UI for UI components.
3. Version Control
Introduction to Git and GitHub for version control.
Emphasized best practices for committing code and managing branches.
4. Development Environment
Configuration of local development environments to ensure consistency across team members.

Milestone 2: Project Overview

In this Milestone we had done the Login Page for the users to enter their login credentials to achieve this we first created a root directory using vite and then we installed all the required dependencies after that we created the 2 folders "components\auth" and "pages" within src with required files once this is done we written the required code in App.css,tailwind.config.js we then installed axios using npm then we written code in postcss.config.js and then we finished off the required tasks by writing code in Login.jsx in components and pages folders and then we even updated Routes.jsx and hence created a login page to check whether we got the correct output we used the command "npm run dev" which led us to the output!!

Milestone 3: Project Overview

In this Milestone we had dedicated the respective folders into our Backend folder to organize our code effectively to avoid confusion then we created a Node.js server to handle all of the API request required and then we connected our project with MongoDB where MongoDB is a database to manage and store all the data that is created on our website we made a basic error handling code to check our website then we also checked the required things and hence we got output !!!

Milestone 4: Project Overview 

In this Milestone Firstly we installed multer and bcryptjs in our Backend folder and then we created an User model to design how the Data given by the users should look in the database to do this we first started to write the required code in user.js,multer.js and in app.js after this we get required result!!

Milestone 5: Project Overview

In this Milestone first we started off by adding a SignupPage and it's route then we written the code for the signup page in Signup.jsx in components and pages both the folders and we even updated the Routes.jsx and Validation.js and then again we checked out desired output using the command "npm run dev" and hence i got the desired output exactly 

Milestone 6: Project Overview

Encrypting Passwords and Storing User Data
In this milestone, the focus was on enhancing the security and data handling during the user registration process. Key achievements include:

Password Encryption:
Utilized bcrypt to hash user passwords during the signup process to ensure secure storage.
Replaced plain-text password storage with hashed passwords in the database.
Complete User Data Storage:
Stored all user information, including name, email, and the hashed password, in the database using the User model.
Ensured sensitive data is handled securely and adheres to best practices.
Validation Enhancements:
Added additional backend validation to verify that required fields are provided during signup.
Prevented duplicate user registrations by ensuring email uniqueness in the database.
API Integration:
Updated the registration endpoint (/api/users/register) to handle password hashing and data storage seamlessly.
Live Coding Walkthrough:
Demonstrated the implementation of these features during a live coding session, explaining the importance of password encryption and secure data handling.
This milestone significantly enhances the application's security by protecting user credentials and laying a solid foundation for authentication and authorization in future milestones.


Milestone 7: Project Overview

In this milestone i created the login endpoint to authenticate users securely. This involved accepting user credentials (email/username and password) via a POST request and retrieving the corresponding user data from the database. I implemented password validation using bcrypt, comparing the entered password with the stored hashed password to ensure authentication. For successful logins, I generated a token (e.g., JWT) for session management. I also handled various error scenarios, such as invalid input, non-existent users, and incorrect passwords, returning appropriate HTTP status codes and messages. Finally, I thoroughly tested the endpoint to ensure its reliability and security.

Milestone 8: Project Overview

In this milestone i created a reusable Card Component that dynamically accepts props like product name, image, and price, allowing for modular and scalable design. The component is styled to display the details cleanly and intuitively. For the Homepage Layout, I designed a responsive grid layout (or used flexbox) to showcase multiple card components in an organized and visually appealing manner. This ensures a user-friendly interface, with proper spacing, alignment, and adaptability across different screen sizes. Both the card component and layout were tested for responsiveness and seamless integration.

Milestone 9: Project Overview

In this milestone, we created a frontend form for taking product input details and multiple images.

- Created a form to input product details
- Added functionality to upload multiple images

Milestone 10: Project Overview

This milestone focuses on building a product schema and creating a POST endpoint to validate and store product details in MongoDB using Mongoose.

### Key Objectives:

Product Schema:

- Define the structure for product data, including fields like:
- name (string, required)
- description (string)
- price (number, required)
- imageUrl (string, URL format)
- Ensure proper validation (e.g., required fields, correct data types).

Endpoint Creation:

Develop a POST API endpoint to receive product data.
Validate the data before saving it to MongoDB.
Store only valid product details in the database.
Importance of Validation:

Prevents inconsistent or incorrect data from being stored.
Maintains data integrity and avoids database corruption.
Reduces errors and unexpected behavior in applications.

Milestone 12: Project Overview

In this milestone, we focused on creating an endpoint to fetch and display products specific to a user based on their email, and rendering that data dynamically on the frontend.

### Key Achievements:
- *Endpoint for Product Retrieval*: Created an API endpoint to fetch all products associated with a user's email from MongoDB.
- *Frontend Integration*: Wrote a function to send a request to the backend and receive the user-specific products data.
- *Dynamic Data Rendering*: Displayed the retrieved products dynamically on the frontend using the product card component.
- *Data Filtering*: Implemented filtering logic on the backend to ensure that only products tied to the authenticated user's email are sent to the client.

Milestone 15: Project Overview

we created a responsive navigation bar (Navbar) that includes links to essential pages in our application:

✅ Home – The main landing page.
✅ My Products – Displays all products added by the user.
✅ Add Product – A form to add new products.
✅ Cart – Shows selected items for purchase.

### Key Features Implemented:
- *Responsive Design*:The Navbar adapts to different screen sizes using CSS media queries or flexbox/grid layout.
A hamburger menu for smaller screens improves usability.

- *Smooth Navigation*:We ensured smooth page transitions using React Router (if applicable) or regular navigation techniques.
Each link is clearly labeled for easy access.

- *Global Accessibility*:The Navbar component is added to all pages, making navigation consistent and user-friendly.