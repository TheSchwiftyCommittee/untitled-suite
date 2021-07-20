# untitled-suite

Built by:

- Nathan Blaga [GitHub](https://github.com/NJBLAGA)
- Raymond Doan [GitHub](https://github.com/raymonddoan)

## Background/Problem

Whether on a professional level or for personal projects, task management is an effective and efficient tool for project management. "Task management is the term used to describe how project managers identify, monitor, and track the progress of work that needs to be completed on any given day" (Santos 2021). Task management is critical for the effective development and handling of any project, big or small.

Moreover with the current global pandemic of Covid-19, millions of people have been working from home remotely, adding more strain to the day to day dealings and processes of most projects. More than ever, project teams and individuals working from afar, highlights the importance of task management and handling project development in a agile and organised manner.

## Importance

Task management allows teams and individuals to approach a project with a proactive mindset rather than that of a reactive mindset. Creating roadmaps, procedures, and time frames are essential components of project management. They allow for more efficient and effective development, testing, reviewing/ and implementation than reacting to events that are within and beyond the scope of the team. "Managing tasks ensures that teams are able to prioritize their workloads and guard against time-wasting. It is absolutely imperative in the social media age" (Santos 2021).

Task management through an application such as Untitled Suite when handled in a efficient and effective manner can produce many benefits to a project's team. These benefits include but are not limited to:

- Defining the least to most important priorities through a projects lifecycle
- Creates snapshots of the current project and allows a high-level view of the project all at once
- Reveals time constraints and the available time frame for each task
- Aids in optimisation of grouping or sorting tasks in order of prioritisation which in turn aids in a more efficient scheduling system
- Allows management and team members to work efficiently, effectively and at their maximised productivity levels within their own workloads and time frames
- An automated process which is flexible, tailored to each project and team
- Easy learning curve and utilisation allows for easy flow of mindsets and working habits

## Purpose

Untitled Suite's original intention is to provide project managers and their teams a one stop shop for optimising task management. Moreover whether for the development of a major multi-billion dollar project or a do it yourself project around the house, Untitled Suite aims to remind the user of the important things in life. Through its smooth interface and user-friendly experience, the application is one for the modern day agenda. From task management, daily chores around the house, to tracking and planning your own health or personal growth, Untitled Suite offers efficient and effective tools to optimise your work, your lifestyle, you.

## Functionality / Features

### User Account/Profile

Untitled Suite allows a user to create a unique account. Accessing this account upon login will allow users the abilities to the following:

- Modify their profile settings and account details
- View, update and delete any of their saved lists within Tasker
- View, update and delete any tasks within a certain list
- View, update and delete the current state of their calender
- View, update and delete upcoming events stored within the calender
- Review a backlog of calender events that have past

This feature allows users to customise their Tasker, calender and overall user experience to better suit their taste and style. This results in a more fluent and comfortable atmosphere in which users can feel more attached and give a personal touch to their workflow.

### Admin Dashboard/System

The admin system allows a user who has administrative privileges to log into Untitled Suite and perform routine tasks such as:

- Delete the account of any user who is in violation of Untitled Suite's terms and conditions
- Delete the account of any user who breaches the Untitled Suite's payment policy
- Review and allow administrative privileges to any user who fulfills the required screening procedures

All of the above tasks can be accessed from the Admin Dashboard, which acts as the central hub for all admin. This feature will not be able to be viewed or accessed by any user who is not classified as an admin.

### Paypal Intergration

Upon signing up, Untitled Suite offers users a trial tier of the application. This allows the user to the following benefits:

**Trial Tier:**

- Users can create up to 5 unique lists within the Tasker at any given point
- Users will have the ability to create and store unlimited tasks inside these entires
- Users will have access to their calender

At any point users can purchase the premium tier for AUD $5 per month, this allows users to:

**Premium Tier:**

- Users can create unlimited lists within Tasker at any given point.
- Users will have the ability to create and store unlimited tasks inside these entires
- Users will have access to their calender

### Responsive Navbar

Untitled Suite offer its users a responsive and stylish navbar that allows for a smooth experience while navigating between the various components. Built with a mobile first development mindset, the navbar and overall design of the application is handled gracefully across all platforms and devices.

### Responsive Design/ Mobile First Design

Untitled Suite is built with the sole intention to approach any task, easier and clearer then ever before. The design of the application was built for the mobile user on the go, the office desktop and of course for the home tablet. It offers its users a sleek an polished professional look and feel, while offering that personal touch to make the users experience that little bit more enjoyable and smooth. Untitled Suite utilises space and functionality of all its components which delivers a users tasks and events in a presentable and elegant manner.

### Tasker

Whether on the trial or premium tier, Untitled Suite allows users to create lists within Tasker alongside setting tasks to each list. While creating a task, users can set a description, priority and reminder date. User will also be able to choose which list within Tasker, the task will be allocated to.

### Intergrated Calendar System

## Additional Features for Roadmap - Whats next?

### Admin Dashboard/System

The admin system allows a user who has administrative privileges to log into Untitled Suite and perform routine tasks such as:

- Manage and resolve any user complaints
- Review and report any technical issues or bugs

### Profile Customisation

When a user logs into their account, they can access the profile customisation feature that allows them to perform the following actions:

- Update and change their profile avatar image
- Change the colour scheme and background design of their profile within Untitled Suite

### Friends List

(Users are able to add other users to their calendar

### Note-Taking Component

## Target Audience

## Tech Stack

## Dataflow Diagram

## Application Architecture Diagram -> thursday

## User Stories

- As a user, I want to be able to create an account/ profile.

**Solution:**

Utilising the Devise gem, Untitled Suite will have an authentication structure for all users and admins. Users will only be able to access To-Do-lists that belong to their unique profile id.

- As a user, I want to be able to customise my profile avatar, colour scheme and details.

Untitled Suite will provide all users with the ability to change and edit their avatar, colour scheme and details. Through thr profile section located within the navbar, any user can access their profile dashboard and have access to such features.

**Solution:**

- As a user, I want to be able to create to-do lists/checklists.

Untitled Suite allows users once logged in to create up to 5 checklists at a time. Once a user has upgraded their account to premium level, they then have the ability to create unlimited checklists.

**Solution:**

- As a user, I want to be able to have my to-do lists and calender linked.

**Solution:**

Through Untitled Suite's smooth and user-friendly interface, any user can access the calender or their personal to-do lists from anywhere throughout the application. The user will also have to ability to link certain to-do lists to particular days, weeks or months within the calender. This allows the users to set time-frames and reminders within their profiles calender in accordance to particular items requiring attention.

- As a user, I want a user-friendly interface that can function on desktop, tablet and mobile devices with a simplistic design and responsive navigational layout.

**Solution:**

Utilising the extensive library offered by Material-UI, Untitled Suite will provide a very friend, smooth and rich experience in relation to its interface and overall design. The ability for all users to customise their profiles in accordance with their own styles and workflow allows Untitled Suite to provide users with the ultimate utilities experience mixed with each users personal touch.

- As a user, I want assurance of my accounts privacy and safety.

**Solution:**

Utilising Devise's extensive library of security features in addition to built in protocols allows users to create their own profiles, login and use the application within a friendly environment.

- As an admin, I to have access to the admin dashboard.

**Solution:**

Admin will be able to log into the application and have access to an onboard dashboard. This will act as a hub in which all admin, can access the application through a unique way. The Admin dashboard will only be accessible to users who have the status of admin. Other uses will not have access or vision of the dashboard within their experience of the application.

- As an admin, I to be able to view all users.

**Solution:**

Within the Admin dashboard, admin have access to all current users within the application's database. The dashboard will not only display all users but allow admin to perform various actions ( mentioned below).

- As an admin, I to be able to delete a user profile.

**Solution:**

One action available within the dashboard to all Admin is the ability to delete any user. The ability to delete an account will only be exercised if said user has broken, violated the terms and conditions of the application. The deletion of any user is a permanent action and can not be undone once performed.

- As a admin, I want to be able to assign users with admin status.

**Solution:**

The Admin dashboard allows the Admin to also promote users to Admin status. This feature allows for the growth of the admin staff as the growth of the application increases. This action is should be performed with caution and only be used once a user has gone through sufficient screening.

## Wireframes

## Trello Board

[https://trello.com/b/Bj5asYWU/untitled-suite]

![trello-01](./docs/trello-01.png)

## License

## References

Santos, J 12 October 2021, Best Management Software & Tools, apps, project management software reviews, reviewed 15 July 2021, https://project-management.com/task-management-software
