The aim of this assignment is to test your expertise in various aspects of Django, RESTful principles, coding efficiency, problem-solving skills, and your approach to system design.

It is focused on implementing an in-app notification system. 

Please fork this repository and provide a solution for the first three challenges. 

Implementing challenges 4 and 5 is optional, but will considered an extra bonus for your evaluation. 

Please provide a GitHub link to your solution no later than Monday December 4, (Midnight UTC)


1. **API Design and Implementation Challenge:**
   - **Scenario:** Create a RESTful API endpoint using Django REST Framework that allows sending notifications to a specific user.
   - **Requirements:** 
     - Endpoint should accept parameters like `user_id`, `message`, and `notification_type`.
     - Implement appropriate HTTP methods and status codes.
     - Ensure the API handles errors gracefully and returns informative error messages.
     - Write unit tests for the endpoint.
   - **Evaluation Criteria:** API design skills, understanding of REST principles, error handling, and test-driven development.

2. **Database Modeling Challenge:**
   - **Scenario:** Design a database model to store notifications, including details like sender, receiver, message, timestamp, and read status.
   - **Requirements:**
     - Use Django models to design the database schema.
     - Include methods to mark a notification as read.
     - Optimize the model for efficient retrieval of notifications.
   - **Evaluation Criteria:** Database design skills, efficiency in data retrieval, and Django ORM expertise.

3. **Group Notification Feature:**
   - **Scenario:** Extend the notification system to support sending notifications to a group of users.
   - **Requirements:**
     - Modify or add an API endpoint to handle group notifications.
     - Implement logic to select users based on criteria like group membership or user attributes.
     - Ensure scalability and performance in the solution.
   - **Evaluation Criteria:** Ability to extend existing systems, performance optimization, and understanding of user-group dynamics.

4. **Real-Time Notification Challenge:**
   - **Scenario:** Implement a real-time notification feature using Django Channels or a similar technology.
   - **Requirements:**
     - Notifications should be pushed to users immediately when they are sent.
     - Ensure the solution is scalable and efficient.
     - Include any necessary authentication or security measures.
   - **Evaluation Criteria:** Knowledge of real-time technologies, security considerations, and scalability.

5. **Notification Preferences and Settings:**
   - **Scenario:** Allow users to set preferences for receiving notifications (e.g., email, in-app, frequency).
   - **Requirements:**
     - Create API endpoints for users to set and retrieve their notification preferences.
     - Implement logic to respect these preferences when sending notifications.
     - Address any privacy or data handling concerns.
   - **Evaluation Criteria:** User-centric design, understanding of privacy concerns, and ability to implement custom user settings.

