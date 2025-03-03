# WeightApp
CS 360 App created using android studio

Overview
The Weight Tracking App was developed to help users log their daily weight, set a goal weight, and track progress over time in a simple and intuitive way. The primary goal was to create an easy-to-use app that provides a user-friendly UI, secure authentication, and notifications when a user reaches their goal weight.

User Needs and Design Considerations
This app was designed to address the needs of users who want to monitor their weight consistently and set achievable goals. To meet these needs, the app includes:

Login Screen: Secure user authentication for data privacy.
Weight Log Screen: A grid display for daily weight entries, with options to add, edit, and delete data.
Goal Weight Screen: A field to set a goal weight, with notifications when the goal is reached.
The UI was designed with clarity and simplicity in mind, ensuring that users can easily navigate the app and complete their tasks without confusion. Logical labels, clear headers, and easy-to-access buttons contribute to a user-centered experience.

Development Approach
I followed a structured approach to development, beginning with UI design and database setup, then implementing core functionalities in incremental steps. Key strategies included:

Modular coding: Separating concerns for better maintainability.
Database management: Using structured tables for weight entries, user authentication, and goal tracking.
Permission handling: Ensuring smooth interaction with SMS notifications.
These techniques will be beneficial for future projects, especially when developing apps that require data management, secure authentication, and real-time notifications.

Testing and Validation
To ensure functionality, I performed:

Unit testing: Verifying login authentication, weight entry storage, and goal weight notifications.
UI testing: Ensuring smooth navigation and proper layout rendering.
Permission testing: Checking SMS notification requests and responses.
Testing is crucial as it helped identify and fix edge cases, UI inconsistencies, and database errors before finalizing the app.

Challenges and Innovations
One major challenge was implementing a seamless user experience for SMS notifications while handling permission restrictions. I overcame this by using runtime permission requests and ensuring the app functions properly even if users deny SMS access.

Key Success Areas
I was particularly successful in implementing a clean and user-friendly UI with structured data management. The app not only meets its functional requirements but also provides a smooth experience with secure authentication, intuitive navigation, and real-time progress tracking.

This project has strengthened my mobile app development skills and provided valuable insights into building scalable and user-friendly applications.
