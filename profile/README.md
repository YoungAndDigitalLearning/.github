<p align="center">
    <img alt="YDL Logo" src="https://raw.githubusercontent.com/YoungAndDigitalLearning/ydl-front/refs/heads/master/images/YDL-Logo-35px.svg" width="220">
    <h1 align="center">Young And Digital Learning</h1>
</p>

**A full-stack web application developed at Technische Universität Berlin (TU Berlin) in collaboration with the Sprach- und Kulturbörse (SKB).**

An academic software engineering project combining a modern Vue.js frontend, a RESTful backend, and a self-managed Linux deployment environment.

<p align="center">
<a href="https://younganddigitallearning.github.io/" target="_blank" rel="noopener noreferrer"><b>Explore Interactive Demo</b></a>
</p>

**[View the Full Project](https://github.com/YoungAndDigitalLearning/ydl)**
·
**[Explore the Frontend](https://github.com/YoungAndDigitalLearning/ydl-front)**
·
**[Explore the Backend](https://github.com/YoungAndDigitalLearning/ydl-api)**


## Preview

## Application Showcase

Explore the original Young & Digital Learning application,
reconstructed as an interactive portfolio demonstration
with fictional sample data.

### Landing Page

Public entry point featuring announcements, project
branding, and user authentication.

![YDL landing page](../images/screenshots/student/01-landing.png)

### Student Dashboard

Overview of enrolled courses, upcoming events,
and course navigation.

![Student dashboard](../images/screenshots/student/02-dashboard.png)

### Course Management

Students can discover courses, view course details,
and manage their enrollment.

![Course catalog](../images/screenshots/student/04-all-courses.png)

![Course details](../images/screenshots/student/05-german-course.png)

### Course Discussions

Course-related discussions with threaded posts
and replies.

![Course forum](../images/screenshots/student/07-forum.png)
![Course forum thread](../images/screenshots/student/08-forum-thread.png)

### Interactive Quizzes

Interactive exercises with immediate local feedback.

![Interactive quiz](../images/screenshots/student/10-quiz.png)

### Course Calendar

Calendar for upcoming course activities,
assignments, and events.

![Course calendar](../images/screenshots/student/09-calendar.png)

---

_Screenshots show fictional demonstration data.
The original application was developed as an academic project._

---

## About the Project

Young & Digital Learning was developed as part of the _Programming Lab: Social Networking_ course at **TU Berlin**, in cooperation with the university's **Sprach- und Kulturbörse (SKB)**.

The project involved designing, developing, and deploying a full-stack web application using a component-based frontend architecture, REST API communication, and persistent relational data storage.

Beyond application development, the project also covered server configuration and deployment on a self-managed Ubuntu system.

## Technology Stack

<img alt="Tech stack" target="_blank" src="https://raw.githubusercontent.com/YoungAndDigitalLearning/ydl-front/master/images/stack_features.jpg" href="https://raw.githubusercontent.com/YoungAndDigitalLearning/ydl-front/master/images/stack_features.jpg">

| Area                 | Technologies                                        |
| -------------------- | --------------------------------------------------- |
| **Frontend**         | Vue.js, JavaScript, Bootstrap, Sass/SCSS, HTML, CSS |
| **Frontend Tooling** | npm                                                 |
| **Backend**          | Python, Django REST Framework, REST APIs            |
| **Database**         | MariaDB                                             |
| **Deployment**       | Linux (Ubuntu), Nginx, Gunicorn                     |
| **Version Control**  | Git, GitHub, Git Submodules                         |

## Application Architecture

The application follows a client-server architecture with a clear separation between the frontend, backend, and database.

**Frontend — Vue.js**

A browser-based user interface built with Vue.js, using Bootstrap and Sass/SCSS for styling and responsive layouts.

↓

**Backend — Django REST Framework**

A Python-based REST API responsible for handling application requests, business logic, and data access.

↓

**Database — MariaDB**

Relational database used for persistent application data storage.

The application was deployed on a self-managed Ubuntu server, with Nginx serving as a web server and reverse proxy and Gunicorn running the Python backend.

## Project Repositories

The project is organized into three Git repositories, with the frontend and backend integrated into the main repository as Git submodules.

### [ydl — Main Project](https://github.com/YoungAndDigitalLearning/ydl)

The main project repository, bringing together the frontend and backend as Git submodules.

### [ydl-front — Frontend](https://github.com/YoungAndDigitalLearning/ydl-front)

The client-side application developed with Vue.js, JavaScript, Bootstrap, and Sass/SCSS.

**Focus:** Component-based UI development, responsive styling, and REST API integration.

### [ydl-api — Backend](https://github.com/YoungAndDigitalLearning/ydl-api)

The server-side application developed with Python and Django REST Framework, backed by MariaDB.

**Focus:** RESTful API endpoints, backend application logic, and persistent data storage.

## Deployment & Infrastructure

The project was deployed in a self-managed Linux environment.

- **Ubuntu** — Server operating system
- **Nginx** — Web server and reverse proxy
- **Gunicorn** — Python application server
- **MariaDB** — Relational database
- **Git & GitHub** — Source control and project organization

This setup provided practical experience with deploying and operating a full-stack application beyond a local development environment.

## Academic Context

**Institution:** Technische Universität Berlin (TU Berlin)

**Course:** Programming Lab: Social Networking (_Programmierpraktikum Soziale Netzwerke_)

**Collaboration:** Sprach- und Kulturbörse der TU Berlin (SKB)

**Project type:** University software engineering project

---

_Young & Digital Learning is presented here as an academic software development project and a technical portfolio reference._
