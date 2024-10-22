# Authify

Authify is a secure authentication tool built using the MERN stack (MongoDB, Express.js, React.js, and Node.js). It provides users with a seamless login experience. Authify employs JSON Web Tokens (JWT) for secure session management, ensuring a high level of security for user data.

## Features

### Backend Features
- 🔧 **Backend Setup**: Set up a robust backend using Node.js and Express.
- 🗄️ **Database Setup**: Integrated MongoDB for secure data storage.
- 🔐 **Signup Endpoint**: Users can register for an account.
- 📧 **Sending Verify Account Email**: Verification emails sent to new users upon signup.
- 🔍 **Verify Email Endpoint**: Allows users to verify their email addresses.
- 📄 **Building a Welcome Email Template**: Custom email templates for welcoming new users.
- 🚪 **Logout Endpoint**: Users can securely log out of their accounts.
- 🔑 **Login Endpoint**: Users can log in with their credentials.
- 🔄 **Forgot Password Endpoint**: Enables users to request a password reset.
- 🔁 **Reset Password Endpoint**: Allows users to reset their passwords securely.
- ✔️ **Check Auth Endpoint**: Checks if the user is authenticated.

### Frontend Features
- 🌐 **Frontend Setup**: Established the frontend using React.js.
- 📋 **Signup Page UI**: User-friendly interface for account registration.
- 🔓 **Login Page UI**: Intuitive interface for user login.
- ✅ **Email Verification Page UI**: Page for users to verify their email addresses.
- 📤 **Implementing Signup**: Complete integration of the signup process.
- 📧 **Implementing Email Verification**: Verification process fully implemented.
- 🔒 **Protecting Our Routes**: Ensured secured access to protected routes.
- 🔑 **Implementing Login**: Fully functional login process.
- 🏠 **Dashboard Page**: User dashboard for authenticated users.
- 🔄 **Implementing Forgot Password**: Complete flow for password recovery.

## Technologies Used

- **Frontend:** React.js, Zustand, Axios, React Icons
- **Backend:** Node.js, Express.js, MongoDB, JWT (for session management), bcryptjs
- **Email Service:** Mailtrap
- **Environment Variables:** dotenv for configuration management

## Getting Started

To get started with Authify, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/Authify.git
   ```
   
2. **Navigate to the Project Directory:**
   ```bash
   cd Authify
   ```

3. **Install Dependencies:**
   ```bash
   npm install
   ```

4. **Configure Environment Variables:**
   Create a `.env` file in the root directory and add the required variables:
   ```plaintext
   MONGO_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   MAILTRAP_USER=your_mailtrap_user
   MAILTRAP_PASS=your_mailtrap_password
   ```

5. **Run the Application:**
   ```bash
   npm run dev 
   ```

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to create a pull request.

## Acknowledgments

- Inspired by various authentication projects and frameworks.
- Thanks to the community for their support and feedback.

---

