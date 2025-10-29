# ShellPath

CodePath WEB103 Final Project

Designed and developed by: Faizan Khan

🔗 Link to deployed app: (placeholder — will add Render URL once deployed)

## About

### Description and Purpose

ShellPath is a small full-stack app that helps learners organize a learning path into milestone-based tasks, track progress, and earn trophies as rewards. Users can create profiles, view a preloaded set of milestone tasks, add/edit/delete tasks, and purchase trophies from a trophy shop. The app is designed to teach and demonstrate RESTful API usage, relational database design, and React front-end routing and state management.

### Inspiration

We were inspired by skill-path builders and gamified learning tools (for example, GOATPath) that break large goals into small, trackable steps and use simple rewards to motivate progress.

## Tech Stack

Frontend:
- React
- React Router
- CSS / simple component styling

Backend:
- Node.js + Express
- PostgreSQL
- Knex.js (or node-postgres) for database queries
- Deployed on Render

## Features

### 1) User Profiles
Registered users can create a profile and view their tasks and trophies.

### 2) Preloaded Milestones
When a user creates a profile, ShellPath seeds a default set of milestone tasks so users can get started immediately.

### 3) Task CRUD (GET, POST, PATCH, DELETE)
Users can view tasks, create new tasks, update existing tasks (title, description, completion status), and delete tasks.

### 4) Trophy Shop & Trophy Case
Users can spend in-app currency to buy trophies in a shop and view purchased trophies on their profile page (many-to-many relationship via a join table).

### 5) Filtering & Sorting
Users can filter tasks by milestone or completion status and sort tasks by priority or due date.

### 6) Modal Task Editor
Add/edit tasks in a modal that overlays the current page so users don't need to navigate away.

### 7) Reset Database
A server route and script allow resetting the database to its default seeded state for easy testing.

### 8) Error Handling & Validation
Forms validate input before submission (e.g., non-empty title). The UI displays friendly error messages when requests fail.

## Installation Instructions

1. Install dependencies for server and client (instructions will depend on final repo layout).
2. Configure Postgres DATABASE_URL and run migrations/seeds.
3. Start server and client locally.

(Full installation and deployment steps will be added in Milestone 3 when server and client code are present.)
