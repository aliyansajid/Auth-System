

# Auth System

This is a robust authentication system built using Next.js, Tailwind CSS, and MongoDB as database. It includes features such as OAuth integration, secure login and signup, password recovery, and route protection.

## Features

- **User Registration:** Allows new users to sign up.
- **User Login:** Secure login with password handling.
- **OAuth Integration:** Supports login via third-party providers (e.g., Google, Facebook).
- **Password Recovery:** Enables users to reset forgotten passwords.
- **Protected Routes:** Restricts access to certain routes based on user authentication status.
- **Session Management:** Handles user sessions securely.

## Demo

You can view the live demo of the application here: [Auth System Demo](https://auth-system-sage.vercel.app/)

## Tech Stack

- **Frontend:**
  - Next.js (React Framework)
  - Tailwind CSS

- **Backend:**
  - Node.js
  - Express.js
  - MongoDB

- **Authentication:**
  - OAuth (for third-party logins)
  - JWT (JSON Web Tokens)
  - bcrypt.js (for hashing passwords)

- **Hosting:**
  - Vercel (for serverless deployment)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/aliyansajid/auth-system.git
   cd auth-system
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Set up environment variables:**

   Create a `.env` file in the root directory and add the following environment variables:

   ```bash
   MONGO_URI=<your-mongodb-uri>
   JWT_SECRET=<your-jwt-secret>
   OAUTH_CLIENT_ID=<your-oauth-client-id>
   OAUTH_CLIENT_SECRET=<your-oauth-client-secret>
   EMAIL_USERNAME=<your-email-account>
   EMAIL_PASSWORD=<your-app-password>
   NEXTAUTH_SECRET=<your-auth-secret>
   NEXTAUTH_URL=<your-next-auth-url>
   ```

4. **Run the application:**

   ```bash
   npm run dev
   ```

   The application will be available at `http://localhost:3000`.

## Usage

- **Register:** Go to `/register` to create a new account.
- **Login:** Go to `/` to log into your account.
- **Password Recovery:** Go to `/forgot-password` to reset your password.
- **Protected Routes:** Access restricted pages (e.g., `/dashboard`) only when logged in.
- **OAuth Login:** Use OAuth provider (Google) for authentication.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/your-feature-name`.
5. Submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Vercel](https://vercel.com/) for hosting
- [MongoDB](https://www.mongodb.com/) for the database
- [OAuth](https://oauth.net/) for third-party authentication
