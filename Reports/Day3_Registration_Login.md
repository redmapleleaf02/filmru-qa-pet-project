# filmru – Test Log (25 February 2026)

## Summary:
- Date: 25 February 2026;
- Tester: Yeldos Zhetesuly;
- Project: film.ru exploratory testing;
- Scope: Registration and login testing.

## Activities:
- Prepared **1 checklist** for registration and login coverage;
- Designed **5 test cases**;
- Logged **3 bug reports**.

## Test Cases Executed:
- TC-RL-001;
- TC-RL-002;
- TC-RL-003;
- TC-RL-004;
- TC-RL-005.

## Bug Reports Logged:
- FBR-009;
- FBR-010;
- FBR-011.

## Status:
- Checklist completed;
- All 5 test cases drafted;
- 3 bug reports documented;
- Testing scope for registration and login considered **covered**.

## Notes:
1. No transitions or links between login and registration;
2. When using an email from “tutamail.com” for registration, the password code is not sent;
3. When using an email from “protonmail.com” for registration, the password code arrived after a couple of minutes;
4. No “Resend password code” button;
5. In profile settings, there is a “Удалить эккаунт” (Delete account) button. Spelling error — should be “Удалить аккаунт”;
6. When the login field is filled with spaces and the “Продолжить” (Proceed) button is clicked, the login window reloads;
7. The “Show/Hide Password” button blends into the authorization form because the button itself is black while the login window is dark gray;
8. When clicking on the side areas of the login window, the “Show/Hide Password” button disappears and reappears again if the entered password is deleted and retyped;
9. No frames or hints regarding password strength and security (it is possible to set a password containing only one character);
10. Set a password in account settings with 120 characters (typed “qwerty” 20 times), logged out, and tried to enter this password. The password field accepts a maximum of 60 characters;
11. Requested a password recovery email to an address with the “protonmail.com” domain. The email arrived after more than 10 minutes and only after three requests;
12. Other recovery emails arrived 2–3 hours later in the mailbox.
