# ActivityCenter (AC)
My final exam project for Coding Dojo's C#/.NET Core course.
AC shows understanding of Login/Registration, making Database Queries, using Session, Routing, and general HTML/CSS (experimented w/ Bootstrap for this project).

Time Frame: 4.5 hours


# General Features
1. Login & Registration w/ Error Validations
2. Routing to main Activity page after logging in or registering
   - Cannot access page w/o logging in (Session)
   - Displays all future activities (Querying Database)
   - Displays Activity Name, Date & Time, Duration, Creator, and # of Participants 
   - Sorted by Date & Time
3. Create a New Activity w/ Error Validations on the Create New Activity page
   - Only creator can Delete their own activities
4. Join other activities w/ Error Validations
   - Error Validations prevent user from joining an activity w/ overlapping time
5. Logout
   - Clears sessions and returns to Home Page


# Screenshots

**Home Page**
![Home Page](screenshots/DojoActivity_0_1870x975_Home.png?raw=true "Home Page")

**Early Logout**
![Early Logout](screenshots/DojoActivity_0_1870x975_EarlyLogout.png?raw=true "Early Logout")

**Skip Login**
![Skip Login](screenshots/DojoActivity_0_1870x975_SkipLogin.png?raw=true "Skip Login")

**Register Errors**
![Register Errors](screenshots/DojoActivity_1_1870x975_RegisterErrors.png?raw=true "Register Errors")

**Password Errors**
![Password Errors](screenshots/DojoActivity_2_1870x975_PasswordErrors.png?raw=true "Password Errors")

**Register Success**
![Register Success](screenshots/DojoActivity_3_1870x975_RegisterSuccess.png?raw=true "Register Success")
Note: Green text only lasts through one redirect. Goes away on refresh.

**Activity Join**
![Activity Join](screenshots/DojoActivity_4_1870x975_ActivityJoin.png?raw=true "Activity Join")
Note: Green text only lasts through one redirect. Goes away on refresh.

**Activity Page**
![Activity Page](screenshots/DojoActivity_5_1870x975_ActivityPage.png?raw=true "Activity Page")

**Activity Leave**
![Activity Leave](screenshots/DojoActivity_6_1870x975_ActivityLeave.png?raw=true "Activity Leave")
Note: Green text only lasts through one redirect. Goes away on refresh.

**Activity Create Blank**
![Activity Create Blank](screenshots/DojoActivity_7_1870x975_ActivityCreateBlank.png?raw=true "Activity Create Blank")

**Activity Create Filled**
![Activity Create Filled](screenshots/DojoActivity_8_1870x975_ActivityCreateFilled.png?raw=true "Activity Create Filled")

**Activity Create Page**
![Activity Create Page](screenshots/DojoActivity_9_1870x975_ActivityCreatePage.png?raw=true "Activity Create Page")

**Activity Created**
![Activity Created](screenshots/DojoActivity_10_1870x975_ActivityCreated.png?raw=true "Activity Created")
Note: Green text only lasts through one redirect. Goes away on refresh.

**Activity Conflict**
![Activity Conflict](screenshots/DojoActivity_11_1870x975_ActivityConflict.png?raw=true "Activity Conflict")
Note: Green text only lasts through one redirect. Goes away on refresh.

**Activity Delete**
![Activity Delete](screenshots/DojoActivity_12_1870x975_ActivityDelete.png?raw=true "Activity Delete")
Note: Green text only lasts through one redirect. Goes away on refresh.

**Logout**
![Logout](screenshots/DojoActivity_13_1870x975_Logout.png?raw=true "Logout")


#Room for Improvement
• In the tight time frame, I couldn't optimize my error messages as I would have liked. The form erases user input after a failed submit. I tackled this issue in another project <Will Insert Link Here Once on GitHub>.
• Cannot make an event on the same day. But who makes last minute plans these days?
• Should show Active page on the Nav Bar.
• Better UI/UX.
