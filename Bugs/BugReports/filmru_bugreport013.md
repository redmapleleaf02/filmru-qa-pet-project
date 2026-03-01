# filmru – Bug Report №13

## ID: FBR-013

## Title:
- Inconsistent password visibility toggle across browsers

## Description:
- On Microsoft Edge, the login form provides a button to show/hide the password;
- On Google Chrome and Mozilla Firefox, this functionality is absent;
- This creates inconsistent user experience across browsers.

## Environment:
- OS: Windows 11;
- Browsers:
  - Edge (version 145.0.3800.70) –> password visibility toggle available;
  - Chrome (version 145.0.7632.117) –> toggle absent;
  - Firefox (version 148.0) –> toggle absent.

## Steps:
1. Open film.ru and click on the “Войти” button in Edge, Chrome, and Firefox;
2. Enter email and password in the login form;
3. Observe availability of show/hide password toggle.

## Expected Result:
- Password visibility toggle consistently available across all tested browsers.

## Actual Result:
- Toggle available only in Edge, absent in Chrome and Firefox.

## Severity:
- Low.

## Priority:
- Normal.

## Evidence:

### Video:
![Bug Video](../Media/filmru_toggleabsentbug.mp4)
