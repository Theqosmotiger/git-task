General Information
Frontspot is a community for FE&JS developers driven by EPAM employees. You can find Frontspot videos, articles, podcasts across Internet and this is a part of whole amount of work community is doing right now. 
Frontspot is now working with Buddy Bot for EPAM colleagues. The goal of the project is to create a Telegram bot for epamers. Acquaintance with the company takes place in the game form with various tasks typical for employees.
We are implementing some essential features like Admin Panel and extending current logic to provide even more benefits to those, who want more fun incommunication. 
There are 3 types of users:
SuperAdmin
Admin
User
SuperAdmin - there can be maximum 3 SuperAdmins at one time. They can do everything in the bot, including Creating and Approving the Task, Delete and Send to Rework the task, Making any User an Admin or SuperAdmin, Making any Admin SuperAdmin and contraversa, Seeing all the Users of Telegram bot, Creating and Approving Recognitions, Deleting and Send to Rework Recognitions, Creating and Approving Broadcasts, Deleting and Send to Rework Broadcasts. 
Can work in both Admin Panel as SuperAdmin and on the Telegram bot as a User to test the bot from the User side
Admin - is a person who can administrate the bot from Admin panel ncluding Creating the Task, Seeing all the Users of Telegram bot, Creating Recognitions, Creating Broadcasts.
Admin can be promoted as SuperAdmin and become User by any of SuperAdmins (Only thing to remember there can be max. only 3 SuperAdmins at one time)
Admin can work in both Admin Panel as an Admin and on the Telegram bot as a User to test the bot from the User side
User - is an employee of EPAM who is not Admin and SuperAdmin and who registered in the Telegram bot using their work e-mail and Entered the code to confirm their email address.
User can only use Telegram bot and have NO access to the AdminPanel. User can Do the Task, Skip the Task, Register on the Bot.
There two panels where users can work:
Admin Panel
Telegram bot
Admin Panel - is a web application where Admin and SuperAdmin can administrate the bot managing Tasks, Users, Recognitions, Broadcast and seeing Statistics. You see an example of Admin panel below.



Telegram bot- is a bot on messenger telegram. As a user you should just click on the link, click /start and follow the instructions.

When Admin or SuperAdmin creates the Task the User can see this task on the telegram bot. When User does the task Admin and SuperAdmin can see in the statistics how many users were registered, were Active and others.
Short Summary:
As manager you will be either Admin or Superadmin, the roles are almost similar but have also differences.
All new EPAMers can be Users only (in the beginning until they are not promoted as Admin or Superadmin).
Admin (Superadmin) can work on Task Management, Broadcast, Statistics and Settings, where you can find Admin and User Management.

Critical Success Factors
Adherence to Schedule: Complete development and testing of all planned functionality within the agreed timeline to avoid project delays.
Multi-Language Interface Support: Ensure the bot and Admin Panel are fully functional and user-friendly in all supported languages.
No Major Bugs: At the time of final release, the application should not have any unresolved issues with Critical or Major or Severity. 
Functional Stability: Functional requirements should be clearly defined and stable, with no last-minute changes to the scope that might impact testing or development.
Scalability: The system must handle the anticipated number of users (Admins, SuperAdmins, regular Users) without performance degradation.
Role-Based Access Control: Permissions and restrictions for all user roles (SuperAdmin, Admin, User) must work as specified, without unauthorized access to sensitive features.
Integration Reliability: Seamless communication between the Admin Panel and Telegram bot should be thoroughly validated, with no sync errors.
User Registration and Onboarding: Ensure EPAM colleagues can register with ease using their work email and enjoy a smooth onboarding experience via game-like interactions.
Task Management: SuperAdmin and Admin must successfully create, approve, rework, and delete tasks with proper workflow transitions visible to all participants.
Security Compliance: Protect user data by following security standards to prevent breaches, unauthorized access or data corruption.
Statistics Accuracy: All metrics and analytics (e.g., active users, task completions) must be precise and updated in real-time.
Accessibility: Both the Admin Panel and Telegram bot should meet usability and accessibility standards, catering to diverse user needs.
