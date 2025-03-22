# 🔐 Interactive Login & Signup Page | Build & Learn

This project is a **React-based Login and Signup Page**. It includes **user authentication**, form validation, and dynamic UI updates using React's `useState` hook.

## 🚀 Features
- **User Registration** with Full Name, Email, Password, and User Type selection.
- **Form Validation** to check required fields, password match, and email format.
- **Dynamic UI Updates** for switching between **Signup and Login** modes.
- **Error Handling** with meaningful messages.
- **Success Messages** after successful Signup/Login.
- **Responsive Design** using CSS (without Tailwind or Bootstrap).

## 🛠️ Tech Stack
- **React.js** (JSX-based components)
- **CSS** (Custom styling)
- **JavaScript (useState, event handling)**

## 📂 Project Structure
```
signup-login-react/
│── public/
│── src/
│   ├── assets/                # Contains icons (user, email, password)
│   ├── components/
│   │   ├── Signup.jsx         # Signup form component
│   │   ├── Login.jsx          # (Optional) Login form component
│   ├── App.jsx                # Main app file
│   ├── main.jsx               # Renders React App
│   ├── styles/
│   │   ├── Signup.css         # CSS styles for Signup form
│   ├── index.css              # Global styles
│── package.json
│── README.md                  # Project Documentation
```

## 📥 Installation
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/dishaaggarwal26/signup-login-react.git
   cd signup-login-react
   ```
2. **Install Dependencies:**
   ```sh
   npm install
   ```
3. **Run the Project:**
   ```sh
   npm run dev
   ```

## 📝 Usage
1. Open `http://localhost:5173/` in your browser.
2. Enter user details in the signup form.
3. Choose **User Type** (Job Seeker / Recruiter).
4. Click **Signup** → Success message appears!
5. Switch to **Login Mode** and try logging in.

## 🛠️ Troubleshooting
- **Missing assets error:** Ensure icons (e.g., `user_icon.png`) exist in the `src/assets/` folder.
- **npm error: Missing script "dev"**
  - Check `package.json` for the script:
    ```json
    "scripts": {
      "dev": "vite"
    }
    ```
  - If missing, add it manually and re-run `npm install`.

## 📌 Future Enhancements
- Backend integration for **storing user data**.
- API authentication with **JWT tokens**.
- Password encryption for security.

## 📜 License
This project is open-source and free to use. 😊





