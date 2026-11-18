# Student Budget and Expense Tracker

## Project Description

The Student Budget and Expense Tracker is a web application designed to help college students manage their personal finances. It allows students to record daily expenses, organize spending into categories, set monthly budgets, and understand their spending habits.

## Problem Statement

Many college students struggle to track their daily spending and stay within their monthly budgets. This application provides a simple way to monitor expenses and make better financial decisions.

## Target Users

College students who want to manage their money, track expenses, and avoid overspending.

## Planned Core Features

- Add, edit, and delete daily expenses.
- Categorize expenses (Food, Transportation, Shopping, and Books).
- Set monthly budgets and track remaining balances.
- View spending charts, expense history, and budget warnings.

## Planned Technology Stack

| Component | Technology |
|---|---|
| Frontend | React |
| Backend | Node.js and Express |
| Database | PostgreSQL |
| Containerization | Docker |
| CI/CD | GitHub Actions |
| Cloud Deployment | Google Cloud Platform |
| Project Management | Jira |
| AI Assistance | GitHub Copilot and ChatGPT |

## AI Integration

GitHub Copilot and ChatGPT will assist with code generation, debugging, test creation, and technical documentation. AI-generated suggestions will be reviewed and tested before implementation.

## Project Management

Jira will be used to organize epics, user stories, subtasks, story points, acceptance criteria, and sprint progress.

## Agile Project Planning

The project follows the Agile Scrum methodology and is organized into three main epics and two development sprints.

### Project Epics

**Epic 1: Expense Management**

This epic focuses on helping students record and manage their daily expenses.

- Add a New Expense
- Edit and Delete Expenses
- Categorize Expenses

**Epic 2: Budget Management**

This epic focuses on helping students set budgets and monitor their spending.

- Set Monthly Budgets
- Display Budget Warning When Limit Is Exceeded
- View Budget Progress

**Epic 3: Spending Reports and Analytics**

This epic focuses on helping students understand their spending through summaries and reports.

- View Total Expenses
- View Spending by Category
- Generate Monthly Spending Reports

### Sprint 1 – MVP Sprint

**Sprint Goal:** Complete the minimum viable version of the application by implementing essential expense tracking, budget management, and basic spending summaries.

**User Stories:**

1. SBT-37 – Add a New Expense
2. SBT-38 – Edit and Delete Expenses
3. SBT-40 – Set Monthly Budgets
4. SBT-43 – View Total Expenses
5. SBT-44 – View Spending by Category

### Sprint 2 – Final Project Sprint

**Sprint Goal:** Complete the remaining features and improve the application's overall functionality through testing and refinement.

**User Stories:**

1. SBT-39 – Categorize Expenses
2. SBT-41 – Display Budget Warning When Limit Is Exceeded
3. SBT-42 – View Budget Progress
4. SBT-45 – Generate Monthly Spending Reports

### User Stories, Subtasks, and Acceptance Criteria

Each user story is divided into smaller, actionable subtasks to make development easier to manage. Acceptance criteria define the expected results and determine when a story is considered complete.

The project uses the following planning structure:

- **Epics:** Organize the project into major functional areas.
- **User Stories:** Describe features from the student's perspective.
- **Subtasks:** Break each user story into smaller development activities.
- **Acceptance Criteria:** Define the conditions that must be met for each user story to be considered complete.
- **Sprints:** Organize development work into two stages: MVP and Final Project.

## Project Status

Planning and project setup in progress.

## Deployment

The Student Budget and Expense Tracker is deployed using Google Cloud Run.

- **Cloud Platform:** Google Cloud
- **Deployment Service:** Cloud Run
- **Containerization:** Docker
- **Web Server:** Nginx
- **CI/CD:** Google Cloud Build connected to GitHub
- **Deployment URL:** https://student-budget-tracker-794151840746.us-central1.run.app

The application is automatically built and deployed when changes are pushed to the main branch of the GitHub repository.

## Project Links

- **GitHub Repository:** https://github.com/Mahibur988/Student-Budget-and-Expense-Tracker
- **Jira Project:** https://mahirahman206.atlassian.net/jira/software/c/projects/SBT/list?jql=project%20%3D%20SBT%20ORDER%20BY%20cf%5B10019%5D%20ASC
- **Confluence Documentation:** https://mahirahman206.atlassian.net/wiki/spaces/SBAET/pages/327950/Project+Overview
- **Live Application:** https://student-budget-tracker-794151840746.us-central1.run.app
