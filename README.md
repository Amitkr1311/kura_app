# SmartNotes

NoteSphere is a content-sharing application designed to let users share curated content such as YouTube videos and Twitter posts in a centralized personal "brain." Users can generate shareable links to share their curated content with others seamlessly.

## Features

- User Authentication: Sign up and sign in to manage personal content.
- Create and Save Content: Add YouTube videos and Twitter links to your brain.
- Share Your Brain: Generate shareable links to share your curated content publicly.
- View Shared Brains: Access other users' shared content by visiting their shareable links.
- Responsive UI built with React and TypeScript.
- Backend implemented with Node.js, Express, and MongoDB.
- State management using Redux.
- Secure API endpoints for user and content management.

## Tech Stack

- Frontend:
  - React (with hooks and TypeScript)
  - Redux or Recoil for state management
  - Axios for HTTP requests
  - React Router for navigation
  - Tailwind CSS for styling

- Backend:
  - Node.js and Express.js
  - MongoDB with Mongoose ODM
  - RESTful API design
  - JSON Web Token (JWT) for authentication (if applicable)

## Installation

### Prerequisites

- Node.js (>=14)
- npm or yarn
- MongoDB (local or remote)

### Setup Backend

1. Clone the repository:
   ```
    https://github.com/Amitkr1311/NoteSphere.git
2. Install dependencies:
  ```
   npm install
  ```
3. Configure environment variables:
Create a `.env` file with:


5. Start the backend server:
  ```
  npm run dev
  ```

### Setup Frontend

1. Navigate to frontend directory:

2. Install dependencies:

3. Configure environment variables (if applicable), for example `.env`:

4. Start the frontend dev server:
  ```
  npm run dev
  ```

5. Open your browser at `http://localhost:3000`.

## Usage

- Sign up or sign in to create your personal brain.
- Add YouTube and Twitter content links to your brain.
- Generate a shareable link to share your brain.
- Visit `/share/{shareLink}` to view shared brains.

## Folder Structure

- `/backend` - Node.js/Express backend API server.
- `/frontend` - React frontend application.
- `/frontend/src/components` - Reusable UI components.
- `/frontend/src/pages` - Feature pages including SharedBrain, Dashboard, Signin, Signup.
- `/backend/models` - Mongoose models.
- `/backend/routes` - Express routes.

## API Endpoints (example)

- `GET /api/v1/brain/:shareLink` - Get shared brain content by share link.
- `POST /api/v1/auth/signup` - Register a new user.
- `POST /api/v1/auth/signin` - Authenticate a user.
- ...

## Contributing

Contributions are welcome! Feel free to open issues, fork the repo, and submit pull requests.

## License

This project is licensed under the MIT License.

---

Made with ❤️ by Amit Kumar

