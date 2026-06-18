# RepoNest

A full-stack GitHub explorer that allows users to discover GitHub profiles and repositories with personalized features.

## Features

- GitHub OAuth authentication using Passport.js
- Search GitHub users and repositories
- Like and save GitHub profiles
- View saved profiles
- Filter top-starred repositories by programming language
- Secure server-side session management with cookies

## Tech Stack

- Frontend: React
- Backend: Node.js, Express.js
- Authentication: GitHub OAuth, Passport.js
- Database: MongoDB
- Session Management: Express Session + Cookies

## How It Works

Users sign in with their GitHub account to access protected features. RepoNest fetches data from the GitHub API, while MongoDB stores user information and saved profiles. User sessions are securely managed on the server using cookies.

## Run Locally

```bash
# Clone the repository
git clone <repo-url>

# Install frontend dependencies
cd frontend
npm install

# Install backend dependencies
cd ../backend
npm install

# Start the frontend
npm run dev

# Start the backend
npm start
```

## Author

Built by Saksham Nargas.
