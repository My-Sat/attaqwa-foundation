# At-Taqwa Foundation

## Content, Learning & Community Management Platform

At-Taqwa Foundation is a full-stack web application built with **Node.js, Express.js, MongoDB, Mongoose and Pug**.

The platform supports content publishing, user accounts, class management, live-learning activities, questions and answers, messaging, registrations and administrative workflows through a centralized web application.

## Live Application

[https://www.at-taqwafoundation.org/](https://www.at-taqwafoundation.org/)

## Key Features

### User & Admin Accounts

* User registration and authentication
* Administrative accounts
* Session-based authentication
* Password hashing
* User account management
* Admin dashboard
* Protected application areas

### Articles & Content Publishing

* Create and manage articles
* Publish posts and educational content
* Category management
* Rich-text content support
* Content sanitization
* Search functionality

### Video Management

* Add and manage videos
* Video listings
* Categorize published content
* Administrative video management

### Questions & Answers

* Users can submit questions
* Administrative response workflows
* User messaging and notifications
* Stored question-and-answer history

### Classes & Registrations

* Class registration workflows
* Class session management
* User access to registered sessions
* Administrative registration management
* Access-expiry handling and reminders

### Live Classes

* Live class management
* Live-stream scheduling
* Live-class status management
* Administrative live-class controls

### Messaging

* User messages
* Read/unread message tracking
* Navigation notifications
* Communication between users and the application

### Search & SEO

* Site-wide search functionality
* SEO metadata handling
* Canonical URLs
* Open Graph metadata
* Search-engine indexing controls
* Structured page information

## Technology Stack

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose

### Frontend

* Pug
* JavaScript
* HTML
* CSS

### Application Services & Libraries

* Express Session
* Connect Mongo
* bcryptjs
* Express Validator
* sanitize-html
* CKEditor
* Axios
* dotenv

## Project Structure

```text
attaqwa-foundation/
├── controllers/     # Application and business logic
├── middleware/      # Authentication and request middleware
├── models/          # Mongoose data models
├── public/          # Static files and client-side assets
├── routes/          # Express routes
├── services/        # Background and application services
├── utils/           # Shared utilities
├── views/           # Pug templates
├── app.js           # Express application configuration
├── bin/             # Server startup configuration
└── package.json
```

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/My-Sat/attaqwa-foundation.git
```

### 2. Enter the project directory

```bash
cd attaqwa-foundation
```

### 3. Install dependencies

```bash
npm install
```

### 4. Configure environment variables

Create a `.env` file in the project root.

Example:

```env
MONGODB_URI=your_mongodb_connection_string
SESSION_SECRET=your_session_secret
SITE_URL=http://localhost:3000
```

Additional environment variables may be required for optional integrations.

> The `.env` file is excluded from version control and should never be committed to the repository.

### 5. Start the application

For development:

```bash
npm run dev
```

For normal execution:

```bash
npm start
```

## Architecture

The application follows an MVC-style structure:

* **Models** define MongoDB data structures using Mongoose.
* **Controllers** contain application and business logic.
* **Routes** map HTTP requests to controller actions.
* **Middleware** handles authentication and request processing.
* **Services** handle supporting background/application workflows.
* **Views** render the user interface using Pug.

## What This Project Demonstrates

This project demonstrates practical experience with:

* Building full-stack Node.js applications
* Express.js routing and middleware
* MongoDB and Mongoose data modelling
* Authentication and session management
* Administrative dashboards
* User account workflows
* Content-management systems
* Form validation and sanitization
* Class and registration management
* Messaging and notification workflows
* Search functionality
* SEO implementation
* Server-side rendering with Pug
* Working with multi-module application architecture
* Git and GitHub version control

## Security

Sensitive configuration such as MongoDB credentials and session secrets is managed through environment variables and excluded from source control.

User passwords are stored using password hashing, and user-generated content is validated and sanitized before use.

## Author

**Ibrahim Iddrisu Chenti**

Full-Stack JavaScript Developer

**Core technologies:** Node.js, Express.js, React, MongoDB, Mongoose and REST APIs
