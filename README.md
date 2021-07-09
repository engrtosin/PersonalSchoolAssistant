# PERSONAL SCHOOL ASSISTANT

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
The aim of this app is to make schooling easier for the user. Because there could be a lot of information to handle and tasks to manage, it may be difficult to keep up while being mentally balanced. This app reduces the burden on the user and allows the user to focus on what matters.
The app allows the user to manage multiple school enrollments (including MOOCs), keep school notes, and also suggest tasks to work on.

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** Education
- **Mobile:** Implements vertical scrolling and tabs for viewing enrollments and tasks.
- **Story:**
- **Market:** App is useful for anyone participating in any form of formal education.
- **Habit:** Students are using the app every day to keep up with school work.
- **Scope:** At the basic level, this app is about organizing the user's tasks and giving suggestions on what to do next.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User can login
* User can logout
* User can register a new account.
* User can specify program enrollments
* User can create a task.
* User can edit a task.
* App can login to and get information from LMS.
* In each enrollment, user can specify enrolled courses.
* User can store notes and other useful information.
* User can see a list of all pending tasks with due dates included as needed.
* Tasks can have tags such as optional, required, urgent...
* Socials: Student collaborations
* There should be persistence in 
* ...

**Optional Nice-to-have Stories**

* User can create an upcoming event (test or exams).* User can see all the pending tasks for a particular course
* User can edit an upcoming event (test or exams).
* User can see grades
* User can get suggestions on grade improvement.
* User can navigate from task details page to necessary LMS page.
* User can create and store a course note.
* User can take a picture and store in the course documents.
* User can add program details and course details.
* ...

### 2. Screen Archetypes

* Login page
   * User can login
   * User can register a new account.
   * ...
* Sign up fragment
   * User can register a new account.
* Register an account page
   * Add a new
* Welcome page showing top-prioritized task (if any) and programs.
   * User can see program enrollments
   * User can see a list of pending tasks with due dates.
   * ...
* All Programs page showing all the enrolled programs.
   * User can add new programs
   * User can see all the programs
* Program Details page showing Program details and all courses.
   * User can specify enrolled courses.
   * User can add program details.
* Course Details page
   * User can see all the pending tasks for a particular course
* Tasks page showing all the tasks
   * User can see all the pending tasks in order of priority 
* Course Documents page showing all the stored documents for a course.
   * User can add documents
   * User can see a list of all the course notes and documents.

### 3. Navigation

**Tab Navigation** (Tab to Screen)
These are the tabs common to all the screens.
* Home tab - to welcome screen
* New task tab - create fragment to create task
* Tasks tab - to tasks screen
* Logout tab - to login screen
* Back tab - to previous screen

**Flow Navigation** (Screen to Screen)

* Login screen
   * Register new account
   * Welcome screen
* Register new account screen
   * Welcome screen
* Welcome screen
   * All programs screen
* All Programs screen
   * Add program fragment
* Program Details screen
   * Course Details screen
* Course Details screen
* Tasks screen
   * Edit task fragment
* Course documents screen
   * External document reader.

## Wireframes
<img src="https://imgur.com/pdLV9q3" width=600>
<img src="https://imgur.com/Q1c5buW" width=600>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 
[This section will be completed in Unit 9]
### Models
[Add table of models]
### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
