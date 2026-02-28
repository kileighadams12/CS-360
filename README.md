# CS-360

# App Overview and Purpose

The application I developed for this course is a simple Android weight-tracking app called Weight For Me. The main goal of the app is to give users a straightforward way to log their daily weight and look back at their progress over time. Instead of trying to include every possible health feature, the design focuses on the basic task: opening the app, entering a weight, and keeping a clear record of previous entries.

The app also includes an optional SMS notification feature that alerts the user when they reach their goal weight. This allows the app to acknowledge that milestone without requiring the user to constantly check the app themselves.

# User Needs and UI Design

To support these goals, the app includes several main screens. These include a login screen, a screen where users enter their weight and date, a settings screen where users can set a goal weight, and a screen that displays previous entries. Each screen was designed to keep things simple so the user can complete their task without unnecessary steps.

The UI design focuses on clarity and usability. Input fields are clearly labeled, navigation between screens is straightforward, and actions like adding a weight entry are easy to find. The overall goal was to make the experience feel direct and easy to understand, even for someone who is not very familiar with mobile apps.

# Approach to Coding the Application

When working on the code, I approached the project by focusing on one feature at a time instead of trying to build everything at once. I started with the basic structure of the app, then worked through features like login, saving weight entries, and moving between screens.

Testing smaller pieces of the code as I worked helped me understand how everything connected together. This made debugging easier and helped prevent larger problems later in development. Breaking the project into smaller steps made the coding process more manageable and is something I would continue doing in future projects.

# Testing and Debugging

Most testing was done using the Android Emulator. I ran the application frequently while building it to confirm that each feature worked as expected. I also tested both responses to the SMS permission request to make sure the app still functioned correctly if the user denied the permission.

Using breakpoints and log messages helped show where values were updating and when certain functions were being triggered. This testing process was important because even small mistakes in code can stop parts of the application from working properly. Running the app repeatedly helped catch issues related to navigation and data handling before finalizing the project.

# Overcoming Challenges During Development

One of the more challenging parts of development was connecting the XML layout files with the Java code that controls how the app behaves. Making sure buttons triggered the correct actions and that information passed correctly between screens required careful troubleshooting.

Another challenge involved implementing the SMS permission feature. The app had to request permission from the user and still continue working if the permission was denied. Getting that logic to behave correctly required some trial and adjustment.

# Areas of Strength in the Project

One area where I feel the project shows my progress is in connecting the UI design with the app’s functionality. Creating the layouts was one step, but making those screens respond to user input and interact with the rest of the application required a better understanding of how Android apps work.
