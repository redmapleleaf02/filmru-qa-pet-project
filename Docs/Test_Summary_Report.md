# filmru – Test Summary Report (TSR)

## Project Information:
- Project: film.ru exploratory testing;
- Tester: Yeldos Zhetesuly;
- Test Period: 23 February 2026 – 01 March 2026;
- Scope: Functional, UI/UX, Mobile, and Cross-Browser Testing.

## Test Artifacts:
- Checklists prepared: 6;
- Test cases executed: 24;
- Bug reports documented: 13.

## Test Coverage:
- **Functional Testing**: Registration, login, profile settings, search, collections, reviews/comments, video content, articles, social features;
- **UI/UX Testing**: Hover states, sidebar navigation, hamburger menu, layout responsiveness;
- **Mobile Testing**: Search parameters, password handling, spelling error reproduction;
- **Cross-Browser Testing**: Edge, Chrome, Firefox; verification of bug reproducibility and identification of browser-specific inconsistencies.

## Key Findings:
- **Search System**: Parameters “By date” and “Alphabetical” do not function (FBR-004); mismatch between displayed and actual number of publications (FBR-005); missing parameters in mobile version (FBR-012);
- **UI/UX Issues**: Hover effect absent on “Войти” button (FBR-001); sidebar and hamburger menu lack scroll-bars (FBR-002, FBR-003); sidebar sections inconsistent in hover states (FBR-008);
- **Profile Settings**: Spelling error “Удалить эккаунт” (FBR-009); no password strength indicators (FBR-010); password length inconsistency between creation and login (FBR-011);
- **Cross-Browser Specific**: Password visibility toggle available only in Edge, absent in Chrome and Firefox (FBR-013);
- **Other**: Homepage layout lacks responsive design (FBR-006); sidebar “О персоне” section unresponsive (FBR-007).

## Severity Distribution:
- Critical: 1 (FBR-011);
- Major: 1 (FBR-010);
- Medium: 2 (FBR-004, FBR-012);
- Low/Minor: 8 (FBR-001, FBR-002, FBR-003, FBR-005, FBR-006, FBR-007, FBR-008, FBR-013);
- Trivial: 1 (FBR-009).

## Status:
- All planned checklists executed;
- 24 test cases completed;
- 13 bug reports documented with evidence (screenshots/videos);
- Testing scope considered **covered** for functional, UI/UX, mobile, and cross-browser aspects.

## Conclusion:
- The film.ru exploratory testing project identified multiple usability, functional, and security issues across desktop, mobile, and cross-browser environments. While most defects are minor, two high-severity issues (password strength indicators and password length inconsistency) pose significant risks. The project is now formally closed, with all findings documented and linked to evidence for portfolio presentation.
