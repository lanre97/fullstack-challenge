# Fullstack Technical Test

Welcome to this technical test! The goal is to evaluate your **full-stack development** skills using a modern **TypeScript** stack. You will build a web application that provides **basic user authentication** with JWT and **audio file management** (upload, listing, and playback). Please follow the guidelines below.

---

## Overview

You are required to develop a **Fullstack** application with the following main features:

1. **User Authentication (JWT)**
   - Implement a basic registration and login flow.
   - Use **JSON Web Tokens** (JWT) for authentication and authorization.
   - Protect certain routes/endpoints so only authenticated users can access them.

2. **Audio File Upload & Management**
   - Allow authenticated users to upload their own audio files.
   - Store relevant file data (name, size, upload date, etc.) in the database.
   - Display a list of audio files the user has uploaded.
   - Enable in-browser playback of these audio files (e.g., with the HTML5 `<audio>` element).

3. **Database Integration**
   - Use **PostgreSQL** as the primary database.
   - You may use an ORM such as **Prisma** or **Sequelize** (or any other TypeScript-compatible ORM).

4. **Frontend**
   - Use **React** or **Next.js** (in TypeScript) for the user interface.
   - The application should allow:
     - User registration and login/logout.
     - Audio file uploads.
     - Viewing the list of uploaded audio files.
     - Playback of audio files in the browser.
   - The UI should be **responsive**, adapting to various screen sizes.

5. **Backend**
   - Use **Node.js** with **TypeScript**.
   - Choose **Express** or **NestJS** to create the API.
   - Provide endpoints (REST or GraphQL) to:
     - Register, log in, and log out users.
     - Upload, list, and retrieve audio files.

6. **Error Handling & Validation**
   - Handle authentication errors properly (invalid or expired JWTs).
   - Validate incoming data (user registration fields, file size/type limits, etc.).
   - Provide meaningful error messages and appropriate HTTP status codes.

---

## Technical Requirements

- **Language:** TypeScript (both frontend and backend).
- **Frameworks:**
  - Frontend: **React** or **Next.js** (TypeScript).
  - Backend: **Express** or **NestJS** (TypeScript).
- **Database:** **PostgreSQL**.
- **ORM:** **Prisma**, **Sequelize**, or another TypeScript-compatible ORM.
- **Authentication:** JSON Web Tokens (JWT).
- **File Uploads:** Use any approach you prefer (e.g., [Multer](https://www.npmjs.com/package/multer) with Express, built-in NestJS file upload, or Next.js API routes).
- **Version Control:** Git.

---

## Evaluation Criteria

1. **Functionality**
   - Can users register, log in, and log out properly?
   - Are JWTs issued and validated correctly?
   - Does the file upload and in-browser audio playback work as expected?

2. **Code Quality**
   - Clean, maintainable, and well-organized code.
   - Proper folder structure and separation of concerns.
   - Best practices with TypeScript (types, interfaces, etc.).

3. **Design & Usability**
   - Is the interface intuitive, responsive, and accessible?
   - Is the flow for uploading and playing audio files straightforward?

4. **Documentation**
   - Clear instructions on how to set up and run the project locally.
   - Explanation of significant technical decisions.

---

## How to Submit

1. **Fork** this repository or create a new repository in your GitHub account.
2. Create a branch named after you (e.g., `feature/your-name`).
3. Implement your solution in that branch.
4. Add or update the `README.md` with detailed instructions regarding:
   - How to install dependencies (frontend and backend).
   - How to set up the database (migrations, seeds, environment variables, etc.).
   - How to run the development servers and how to build/serve for production.
   - Any special configurations needed (`.env` files, Docker, etc.).
5. **Create a Pull Request** or share the repository link, indicating how to test your solution.

---

## Delivery

- Ideally, please submit within **2-5 days**.
- If you need more time or have questions, let us know.

---

## Optional Extras

- **Docker** configuration for easier setup of the app and database.
- **Testing** (unit or integration) using frameworks like Jest or Mocha.
- **Additional Security** features (password hashing, rate limiting, etc.).
- **Enhanced UI/UX** features (drag-and-drop uploads, progress bars, playlists, etc.).

---

### Documents

If needed, you can include additional screenshots or references in a `docs/` folder (e.g., `docs/screenshots/`).

---

**Thank you for your participation!**  
We look forward to reviewing your solution and how you approach this challenge. Good luck!
