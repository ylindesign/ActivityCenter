# ActivityCenter (AC)
My final exam project for Coding Dojo's C#/.NET Core course.
AC shows understanding of Login/Registration, making Database Queries, using Session, Routing, and general HTML/CSS (experimented w/ Bootstrap for this project).

Time Frame: 4.5 hours


## General Features
1. Login & Registration w/ Error Validations
2. Routing to main Activity page after logging in or registering
   - Cannot access page w/o logging in (Session)
   - Displays all future activities (Querying Database)
   - Displays Activity Name, Date & Time, Duration, Creator, and # of Participants 
   - Sorted by Date & Time
3. Create a New Activity w/ Error Validations on the Create New Activity page
   - User joins new activity once created
   - Only creator can Delete their own activities
4. Join other activities w/ Error Validations
   - Error Validations prevent user from joining an activity w/ overlapping time
5. Logout
   - Clears sessions and returns to Home Page

