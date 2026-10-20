# WanderLust

WanderLust is a web application for browsing and managing accommodation listings. It allows users to explore properties, view listing details, create and edit listings, and add reviews.

This project is part of my learning journey in full-stack web development. It is built with Node.js, Express.js, MongoDB, and EJS, and is currently under development.

## Features

- View all available listings.
- View individual listing details.
- Create new listings.
- Edit and delete existing listings.
- Add reviews with ratings and comments.
- Delete reviews.
- Validate listing and review data using Joi.
- Render dynamic pages with EJS templates.
- Responsive layouts using Bootstrap.

## Tech Stack

**Backend:** Node.js, Express.js

**Database:** MongoDB, Mongoose

**Frontend:** EJS, HTML, CSS, JavaScript, Bootstrap

**Other tools:** Joi, Method-Override, EJS-Mate, Font Awesome

## Getting Started

### Prerequisites

Install the following before running the application:

- Node.js and npm
- MongoDB Community Server

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/shiv-bhole/wanderlust.git
   ```

2. Navigate to the project directory:

   ```bash
   cd wanderlust
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Make sure your local MongoDB server is running.

5. Start the application:

   ```bash
   node app.js
   ```

6. Open your browser and visit:

   ```text
   http://localhost:8080
   ```

## Project Structure

```text
wanderlust/
├── init/
├── models/
├── public/
│   ├── css/
│   └── js/
├── routes/
├── utils/
├── views/
│   ├── includes/
│   ├── layouts/
│   └── listings/
├── .gitignore
├── app.js
├── package.json
├── package-lock.json
└── schema.js
```

## How It Works

The application uses Express.js to handle requests and Mongoose to interact with MongoDB. EJS templates render dynamic pages using listing and review data stored in the database.

Listings and reviews have separate database models, and Joi is used to validate incoming data.

## Current Status

The project is under development. Core listing and review operations are implemented, and further improvements are planned.

## Planned Improvements

- User registration and login.
- Authentication and authorization.
- Improved form validation and error handling.
- Environment-based configuration for the database connection.
- Deployment to a hosting platform.
- Automated testing.

## License

No license has been added yet.
