# Mini Social Media Project

## Overview

This project is a mini social media application built with Node.js, Express, and PostgreSQL. It includes features such as JWT authentication, email verification, user and post management, and various security measures. The application is designed to demonstrate key aspects of backend development including user management, post creation, comment functionality, and protection against common web vulnerabilities.

## Features

- **User Authentication:**
  - JWT-based authentication
  - Email verification with a token
  - User registration and login

- **Post Management:**
  - Create, read, update, and delete posts
  - Search posts by keyword
  - Filter posts by date
  - Posts expire and are deleted monthly

- **Comment System:**
  - Add, edit, and delete comments on posts
  - View all comments for each post

- **Likes:**
  - Users can like or dislike posts
  - Prevent users from liking their own posts

- **Pagination:**
  - Paginated responses for user posts and comments

- **Security:**
  - Rate limiting to prevent DoS attacks
  - Content Security Policy (CSP)
  - XSS prevention through input sanitization
  - Brute-force attack prevention with account lockout
  - CSRF protection

- **Testing & CI:**
  - Integration and unit tests for authentication and core features
  - Continuous Integration setup with pre-commit hooks

- **Deployment:**
  - Docker setup for containerized deployment
  - PostgreSQL for database management
  - Message brokers integration (if applicable)

## Technologies Used

- **Backend:** Node.js, Express.js
- **Database:** PostgreSQL
- **ORM:** Sequelize
- **Authentication:** JWT
- **Testing:** Jest (or any testing framework of your choice)
- **Containerization:** Docker
- **Message Broker:** (Specify if used)
- **Security Libraries:** Helmet, Express-rate-limit, Csrf, etc.

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/mini-social-media.git
   cd mini-social-media
# social_media
# social_media
# social_media
