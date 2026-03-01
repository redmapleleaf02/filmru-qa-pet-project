# filmru – Bug Report №5

## ID: FBR-005

## Title:
- Search bar – Mismatch between displayed and actual number of publications

## Description:
- When searching for “minecraft” and selecting the “Публикации” (Publications) parameter, the search bar displays the message: “Вы искали: minecraft. Найдено записей на сайте: 7”. However, the actual number of publications shown is 6. This creates inconsistency between the displayed count and the real results. This mismatch occurs not only with “minecraft” but also with other queries (e.g., “fable”).

## Environment:
- OS: Windows 11;
- Browsers:
  - Microsoft Edge (version 145.0.3800.70);
  - Google Chrome (version 145.0.7632.117);
  - Mozilla Firefox (version 148.0).

## Steps:
1. Open the “film.ru” website;
2. Type “minecraft” in the search bar and press Enter;
3. Select the “Публикации” (Publications) parameter;
4. Observe the displayed message and compare it with the actual number of results.

## Expected Result:
- The number of publications displayed in the search message matches the actual number of publications shown in the results section.

## Actual Result:
- The search message displays “7 publications found”, but only 6 publications are actually shown.

## Severity:
- Low.

## Priority:
- Minor.

## Evidence:

### Video:
![Bug Video 1](../Media/filmru_searchbarmismatch_bug1.mp4)

![Bug Video 2](../Media/filmru_searchbarmismatch_bug2.mp4)
