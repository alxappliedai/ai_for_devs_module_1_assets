# Project Specification: Polling App with QR Code Sharing (AI-Assisted Development)

## 1. Introduction & Project Goal

This project involves building a **Polling Application with QR Code Sharing** as part of the "AI for Developers" program. The application allows users to register, create polls, and share them via unique links and QR codes for others to vote on.

**The primary goal of building this project within the course is to provide practical, step-by-step experience in leveraging various AI-powered development tools across the entire software development lifecycle.** 

We will actively use AI tools for planning, UI generation, code writing, testing, debugging, and deployment as we build this application together.

## 2. Core Application Features

The completed application will include the following features:

* **Poll Management (for logged-in users):**
    * Ability to create a new poll with a question and multiple answer options.
    * A dashboard or view listing polls created by the user.
    * Functionality to view the results of a specific poll.
    * Ability to edit or delete created polls.
* **Voting Mechanism:**
    * Public access to polls via unique URLs.
    * Interface for users to vote on a poll option.
    * Implementation to handle vote recording (and potentially prevent multiple votes).
* **Sharing & Access:**
    * Automatic generation of a unique, shareable link for each created poll.
    * Generation and display of a QR code encoding the unique poll link.
* **User Authentication:**
    * User registration (using Supabase Auth).
    * User login/logout.
* **Results Display:**
    * Visual representation of vote counts or percentages for each poll option (e.g., on the poll page).

## 3. User Roles within the Application

* **Poll Creator (Registered User):** Logs in, creates/manages polls, shares polls (link/QR), views results.
* **Voter (Registered and or Anonymous User):** Accesses a poll via link/QR code, casts a vote.

## 4. Technical Foundation

* **Platform:** Web Application.
* **Architecture:** Full-stack application built using the chosen framework.
* **Data Persistence:** Utilizing the selected database service for user data, polls, and votes.
* **Key Functionality:** Includes QR code generation and unique link handling.
* **Deployment:** The project build process will culminate in deploying the application.

## 5. AI Tool Integration During Development

Throughout the course modules, as we build this application, we will integrate and demonstrate the use of various AI tools, including:

* **Planning & Design:** Using AI Chat (e.g., ChatGPT, Claude) to help structure data models, define API routes within Next.js, or outline user flows.
* **UI Generation:** Employing tools like `v0.dev` to rapidly create and iterate on UI components for forms, displays, and layouts using libraries like `shadcn/ui`.
* **Code Generation & Assistance:** Leveraging AI Code Assistants (e.g., GitHub Copilot, Codeium, Cursor) extensively within the IDE (like VS Code or Cursor) to write Next.js components (React), API route handlers, database interaction logic (Supabase client), utility functions, etc.
* **Testing:** Exploring how AI Chat or specific tools can assist in generating test ideas, unit test structures (e.g., using Jest/Vitest), or integration tests for API routes.
* **Debugging:** Utilizing AI debugging features in IDEs or prompting AI Chat tools to help understand errors, refactor code, or explain complex segments.
* **Terminal Assistance:** Showcasing AI-powered terminals (e.g., Warp, Aider) for streamlining setup, package management, and deployment commands.

## 6. Chosen Technology Stack

The course project will be built using the following technologies:

* **Framework:** Next.js (App Router)
* **Database & Auth:** Supabase
* **Utility Libraries:** Such as shadcn, qrcodejs, ...etc
* **Deployment Platform:** Vercel

## 7. Project Outcomes

Upon completion of the relevant course modules, the outcomes will be:

1. **Completed Source Code:** A Git repository (e.g., on GitHub) containing the full source code of the polling application, with a commit history reflecting the AI-assisted development process.
2. **Live Deployed Application:** A publicly accessible URL showcasing the functional, deployed application on Vercel.
3. **Comprehensive README.md:** A detailed README file within the repository explaining:
    * The project's purpose and features.
    * Instructions for setting up and running the project locally.
    * The specific technology stack used.
    * **Key examples and explanations of how different AI tools were integrated and utilized during the build process.**
