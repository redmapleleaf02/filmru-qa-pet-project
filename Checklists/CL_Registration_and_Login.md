# filmru – Checklist. Registration and Login

## 1. General Checks:
- The form opens correctly;
- Fields have correct labels (“Email”, “Password”);
- The “Продолжить” (Proceed) button is inactive when fields are empty;
- Ability to switch between the “Login” and “Register” forms.

## 2. Positive cases:
- Entering the correct login and password –> successful login;
- Registering a new user with valid data –> successful account creation;
- After registration, user is redirected to his personal account; 
- After logging in, user remains on the website page where he logged in.

## 3. Negative cases:
- Empty fields –> error message;
- Incorrect login/password –> error message;
- Password shorter than minimum length –> error message;
- Email without “@” or domain –> error message;
- Use of invalid characters in login/password –> error message.

## 4. UI/UX Checks:
- Error messages are displayed next to the field and are clear to the user;
- The "Show/Hide Password" button works correctly;
- When entering long text, fields do not break the layout;
- Password is hidden by default (asterisks/dots).
