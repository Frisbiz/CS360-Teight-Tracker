# CS360-Weight-Tracker
The Weight Tracker app helps users log their daily weight and monitor progress. The goal was to create a simple app that anyone could use to track weight changes over time. The app stores user data in a database and allows users to add, update, and delete weight entries. It also sends SMS notifications if users allow it.

The app’s design focused on making the interface clean and easy to use. The login screen lets users create an account or log in with existing credentials. The dashboard screen displays weight entries in a list, making it simple to view past records. Each entry has options to edit or delete it. The SMS screen asks for permission to send notifications, but the app still works without this feature if the user denies permission. These features were built to make the app useful without making it complicated.

I started coding by breaking the project into smaller parts. First, I worked on the login system to store user accounts in the database. Then I set up the SQLite database to store weight entries. After that, I connected the app’s buttons to their functions, making sure users could add, update, and delete entries. Testing each feature as I added it helped catch small mistakes before moving on to the next step. This made the whole process easier to manage.

I tested the app using the Android Emulator in Android Studio. Testing was necessary to make sure everything worked like it should. The emulator helped check if the app would behave the same way on different screen sizes. It also revealed that the SMS feature worked as expected and that the app didn’t crash if permission was denied.

One challenge was making sure the app still worked without SMS permission. I had to adjust the code so the app would only try to send messages if permission was granted. This solution made the app more reliable and gave users more control over their privacy.

I was particularly successful in demonstrating my knowledge, skills, and experience in implementing the database features of the app. The SQLite database allows users to save weight entries, which remain accessible even after closing the app. This showcased my ability to manage data persistence effectively. Additionally, I successfully implemented functionality to update and delete entries, ensuring efficient data management. This part of the project highlighted my skills in working with databases, handling user input, and maintaining a smooth user experience while managing stored data.

This project gave me a better understanding of mobile app development. It showed how to connect different parts of an app, from user input to database storage. It also helped me learn how to handle permissions and test for different scenarios.
