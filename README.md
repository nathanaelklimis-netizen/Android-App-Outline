# TaskTrackr – Android App Project Outline

## Project description
This Android app is designed to help users efficiently manage their daily tasks and priorities. It provides a simple, mobile‑friendly interface where users can create, organize, and track tasks throughout the day. The goal for this term is to deliver a minimal viable product that demonstrates core task management features and a clean, usable design.

## Problem addressing
Many users struggle to keep track of multiple responsibilities across work, school, and personal life using scattered notes, emails, and calendar reminders. This often leads to missed deadlines, forgotten tasks, and inefficient use of time. The app addresses this problem by centralizing tasks in one place, offering clear visibility into what needs to be done and when, and reducing the need to juggle multiple tools.

## Platform
The app will target Android smartphones as the primary platform. Development will be performed using **[MIT App Inventor / Android Studio with Kotlin]** as the main environment. The design will focus on modern Android UI patterns that are easy to navigate on small screens and usable in busy, real‑world contexts.

## Front/Back end support

### Front end
The front end will consist of a set of Android screens that allow users to add, edit, view, and complete tasks. The interface will use simple forms, lists, and buttons to keep interactions clear and intuitive. Visual cues (such as icons and color changes) will highlight task status and priority to help users quickly scan what matters most.

### Back end
The back end will handle data storage and basic business logic. Task data will be stored using **[TinyDB / local storage / Firebase]**, and the app will manage operations such as creating, updating, and deleting tasks. If Firebase is used, it can also support user authentication and cloud‑based data access across devices, allowing users to keep their tasks in sync when they change phones or use multiple devices.

## Functionality

### Core (MVP) features
- Create new tasks with a title and optional description  
- View a list of active and completed tasks  
- Mark tasks as completed or reopen them  
- Edit or delete existing tasks  

### Stretch features (time permitting)
- Add due dates and simple notifications or reminders  
- Categorize tasks (work, school, personal) and filter by category  
- Basic search within the task list  
- Simple analytics (e.g., tasks completed per day)

## Design (wireframes)
Planned screens include:
- **Home screen**: Displays the current list of tasks, grouped by status or due date  
- **Add/Edit task screen**: Allows users to enter or modify task details  
- **Settings / About screen** (optional): Basic preferences and app information  

Wireframes will illustrate the layout of these screens, including the placement of buttons, text inputs, and lists, as well as the navigation flow between them. These wireframes will guide the visual design and help ensure the app remains simple, clean, and easy to use.

## GitHub usage
This repository will store the project outline, design notes, and future implementation files.  
- The **README** contains the high‑level outline and project goals.  
- The **Wiki** will expand on requirements, user stories, and updated wireframes as the app evolves over the term.
  
## Wiki

The full project outline is also available in the
[Project Outline Wiki](../../wiki/Project-Outline).
Add project outline to README
