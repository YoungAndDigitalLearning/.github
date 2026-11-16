<p align="center">
  <img src="../images/branding/ydl-logo-big.svg" alt="Young & Digital Learning logo" width="260">
</p>
<h1 align="center">Young & Digital Learning</h1>

<p align="center">
  <!-- Website Online/Offline -->
  <a href="https://younganddigitallearning.github.io/">
    <img
      src="https://img.shields.io/website?url=https%3A%2F%2Fyounganddigitallearning.github.io%2F&style=for-the-badge&logo=githubpages&label=Website&up_message=online&down_message=offline&up_color=brightgreen&down_color=red"
      alt="Young and Digital Learning website availability"
    >
  </a>
  </br>
  <!-- Vue.js -->
  <a target="_blank" href="https://github.com/YoungAndDigitalLearning/ydl-front">
    <img
      src="https://img.shields.io/badge/Vue.js-2.x-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white"
      alt="Vue.js 2 frontend"
    >
  </a>
  <!-- Django -->
  <a href="https://github.com/YoungAndDigitalLearning/ydl-api">
    <img src="https://img.shields.io/badge/Python-Django-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python Django backend">
  </a>
  </br>
  <!-- GitHub License -->
  <a target="_blank" href="https://github.com/YoungAndDigitalLearning/ydl-front/blob/master/LICENSE">
    <img alt="GitHub License" src="https://img.shields.io/github/license/YoungAndDigitalLearning/ydl-front?style=for-the-badge">
  </a>
</p>

**An academic full-stack web application developed at Technische Universität Berlin (TU Berlin) in collaboration with the Sprach- und Kulturbörse (SKB).**

Originally developed as an academic software engineering project, Young & Digital Learning combines a **Vue 2 frontend**, a **Django REST Framework API**, and a **MariaDB database**.

The legacy full-stack application has been restored for local development and demonstration using Docker Compose. An **interactive, backend-free demo is now available on GitHub Pages**, featuring fictional student and teacher accounts, browser-local data persistence, and resettable sample content.

The original REST API is also documented through a publicly accessible, read-only OpenAPI/Swagger reference.

<p align="center">
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/YoungAndDigitalLearning/ydl"><strong>Full Project</strong></a> ·
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/YoungAndDigitalLearning/ydl-front"><strong>Frontend</strong></a> ·
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/YoungAndDigitalLearning/ydl-api"><strong>Backend</strong></a> ·
  <a target="_blank" rel="noopener noreferrer" href="https://younganddigitallearning.github.io/"><strong>GitHub Pages</strong></a>
</p>

## Application Showcase

The screenshots below show the restored application with **fictional demo accounts and sample content**. They illustrate both the student experience and the course management tools available to teachers.

### Student Experience

#### Landing Page

Project branding, announcements, and entry points for authentication.

<p align="center"><img src="../images/screenshots/student/01-landing.png" alt="Young & Digital Learning public landing page with course announcements" width="1000"></p>

#### Student Dashboard

Overview of enrolled courses, navigation, and upcoming activities.

<p align="center"><img src="../images/screenshots/student/02-dashboard.png" alt="Student dashboard displaying joined courses and upcoming events" width="1000"></p>

#### Course Discovery and Details

Students can browse available courses, review descriptions, and manage enrollment.

<p align="center"><img src="../images/screenshots/student/04-all-courses.png" alt="Catalog of available language and intercultural courses" width="1000"></p>
<p align="center"><img src="../images/screenshots/student/05-german-course.png" alt="German Conversation A2 course overview for a student" width="1000"></p>

#### Course Forum

Course discussions with dedicated threads and replies.

<p align="center"><img src="../images/screenshots/student/07-forum.png" alt="Course discussion forum with example topics" width="1000"></p>
<p align="center"><img src="../images/screenshots/student/08-forum-thread.png" alt="Discussion thread with student and teacher replies" width="1000"></p>

#### Interactive Quiz

An interactive language exercise with immediate **client-side feedback**. The demo result is not stored as a graded assessment.

<p align="center"><img src="../images/screenshots/student/10-quiz.png" alt="German language multiple-choice quiz in the student interface" width="1000"></p>

#### Course Calendar

Calendar view for example course assignments and events.

<p align="center"><img src="../images/screenshots/student/09-calendar.png" alt="Student course calendar with upcoming activities" width="1000"></p>

#### Mobile Views

Two narrow-screen captures of the student course page and quiz, at a consistent **430 × 932 px** viewport.

<table align="center">
  <tr>
    <td align="center"><img src="../images/screenshots/mobile/01-german-course.png" alt="Mobile view of German Conversation A2 course details" width="280"></td>
    <td align="center"><img src="../images/screenshots/mobile/02-german-quiz.png" alt="Mobile view of the German Conversation A2 quiz" width="280"></td>
  </tr>
  <tr><td align="center"><em>Course details</em></td><td align="center"><em>Interactive quiz</em></td></tr>
</table>

### Teacher Experience

Teachers can manage their courses, edit course content, configure quizzes, and access forms for creating resources and new courses. The screenshots show the available management interfaces, not a claim that every editing workflow has been production-tested.

#### Teacher Dashboard and Course Overview

<p align="center"><img src="../images/screenshots/teacher/01-dashboard.png" alt="Teacher dashboard showing courses taught by the demo teacher" width="1000"></p>
<p align="center"><img src="../images/screenshots/teacher/02-german-course.png" alt="German Conversation A2 course overview from the teacher account" width="1000"></p>

#### Editing a Course and Quiz

<p align="center"><img src="../images/screenshots/teacher/03-edit-course.png" alt="Teacher interface for editing the German Conversation A2 course" width="1000"></p>
<p align="center"><img src="../images/screenshots/teacher/04-edit-quiz.png" alt="Teacher interface for editing course quiz questions and answers" width="1000"></p>

#### Creating Learning Resources and Courses

<p align="center"><img src="../images/screenshots/teacher/05-create-resource.png" alt="Teacher form for adding a learning resource" width="1000"></p>
<p align="center"><img src="../images/screenshots/teacher/06-create-course.png" alt="Teacher form for creating a new course" width="1000"></p>

_All screenshots use fictional demonstration data. The historical application is presented as an academic project and a portfolio reference._

---

## About the Project

Young & Digital Learning was developed as part of the _Programming Lab: Social Networking_ course at **TU Berlin**, in cooperation with the university's **Sprach- und Kulturbörse (SKB)**.

The project involved designing, developing, and deploying a full-stack web application using a component-based frontend architecture, REST API communication, and persistent relational data storage.

Beyond application development, the project also covered server configuration and deployment on a self-managed Ubuntu system.

## Technology Stack

<p align="center"><img src="../images/branding/technology-stack.jpg" alt="Technology stack used in Young & Digital Learning" width="850"></p>

| Area                 | Technologies                                       |
| -------------------- | -------------------------------------------------- |
| **Frontend**         | Vue 2, JavaScript, Bootstrap, Sass/SCSS, HTML, CSS |
| **Frontend Tooling** | Webpack 3, npm (legacy application)                |
| **Backend**          | Python, Django REST Framework, REST APIs           |
| **Database**         | MariaDB                                            |
| **Deployment**       | Linux (Ubuntu), Nginx, Gunicorn                    |
| **Version Control**  | Git, GitHub, Git Submodules                        |

## Application Architecture

The application follows a client-server architecture with a clear separation between the frontend, backend, and database.

---

<p align="center">
  <b>Frontend — Vue.js</b>
  </br>
  <span>A browser-based user interface built with Vue.js, using Bootstrap and Sass/SCSS for styling and responsive layouts.</span>
  </br>
  <span>↓</span>
  </br>
  <b>Backend — Django REST Framework</b>
  </br>
  <span>A Python-based REST API responsible for handling application requests, business logic, and data access.</span>
  </br>
  <span>↓</span>
  </br>
  <b>Database — MariaDB</b>
  </br>
  <span>Relational database used for persistent application data storage.</span>
</p>

The application was deployed on a self-managed Ubuntu server, with Nginx serving as a web server and reverse proxy and Gunicorn running the Python backend.

## REST API Reference

The original Django REST Framework backend exposes the APIs used by the Vue frontend. An archived OpenAPI specification is available as an interactive, **read-only** Swagger UI reference. It documents the original API contract without requiring a running Django server.

<p align="center">
  <a href="https://younganddigitallearning.github.io/ydl-api/"><strong>Explore REST API Documentation</strong></a>
  &nbsp;·&nbsp;
  <a href="https://younganddigitallearning.github.io/ydl-api/openapi.json">Download OpenAPI JSON</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/YoungAndDigitalLearning/ydl-api">View Django Backend</a>
</p>

```mermaid
flowchart LR
    UI["Vue 2 frontend"] --> API["Django REST API"]
    API --> AUTH["Authentication / users"]
    API --> COURSES["Courses / enrollments"]
    API --> CONTENT["Announcements / resources"]
    API --> SOCIAL["Forum / discussions"]
    API --> LEARNING["Quizzes / events"]
```

<small>The schema is a snapshot of the historical backend. All live API execution is disabled in this documentation; the public frontend demo uses fictional local data.</small>


## Project Repositories

The application is organized into three Git repositories, with the frontend and backend integrated into the main repository as Git submodules. The organization also maintains a separate GitHub profile repository and a GitHub Pages repository for the planned public demo.

### [ydl — Main Project](https://github.com/YoungAndDigitalLearning/ydl)

The main project repository, bringing together the frontend and backend as Git submodules.

### [ydl-front — Frontend](https://github.com/YoungAndDigitalLearning/ydl-front)

The client-side application developed with Vue.js, JavaScript, Bootstrap, and Sass/SCSS.

**Focus:** Component-based UI development, responsive styling, and REST API integration.

### [ydl-api — Backend](https://github.com/YoungAndDigitalLearning/ydl-api)

The server-side application developed with Python and Django REST Framework, backed by MariaDB.

**Focus:** RESTful API endpoints, backend application logic, and persistent data storage.

## Local Restoration & Portfolio Demo

The original Vue 2 and Django 2 application has been restored locally using Docker Compose with separate frontend, backend, and MariaDB services. Fictional seeded data supports repeatable feature demonstrations and screenshot capture using Playwright. 

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
