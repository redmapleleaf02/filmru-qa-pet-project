# filmru – Bug Report №11

## ID: FBR-011

## Title:
- Password length inconsistency between creation and login

## Description:
- When setting a password in account settings, the system allows entering up to 120 characters (e.g., repeating “qwerty” 20 times). However, upon logging out and attempting to log in again, the password field accepts a maximum of 60 characters, making it impossible to authenticate with the previously set password.

## Environment:
- OS: Windows 11;
- Browser: Microsoft Edge (version 145.0.3800.70).

## Steps:
1. Open the “film.ru” website and sign in;
2. Go to the profile settings;
3. Set a password with 120 characters (e.g., “qwerty” repeated 20 times);
4. Log out of the account;
5. Attempt to log in with the 120‑character password.

## Expected Result:
- The system either consistently accepts the full password length during login or restricts password length during creation with clear messaging.

## Actual Result:
- The system allows setting a 120‑character password but accepts only 60 characters in the login field.

## Severity:
- Critical (functional + security issue).

## Priority:
- High.
