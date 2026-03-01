# filmru – Bug Report №8

## ID: FBR-008

## Title:
- Sidebar – sections lack hover state except “Фильмография”

## Description:
- On actor/celebrity information pages, the sidebar contains sections: “О персоне”, “Фото”, “В центре внимания”, “Лучшие фильмы и сериалы”, “Фильмография”, “Публикации”, “Новости”. Most sections do not react to cursor hover (no visual feedback). However, when navigating to the “Фильмография” section, a new page opens with the same sidebar, and in this case hover states are present. This inconsistency reduces UI clarity.

## Environment:
- OS: Windows 11;
- Browsers:
  - Microsoft Edge (version 145.0.3800.70);
  - Google Chrome (version 145.0.7632.117);
  - Mozilla Firefox (version 148.0).

## Steps:
1. Open the “film.ru” website;
2. Enter the name of any actor/celebrity in the search bar and select the first suggestion in the “Люди” (People) section;
3. Hover the cursor over sidebar sections such as “Фото”, “В центре внимания”, “Лучшие фильмы и сериалы”, “Публикации”, “Новости”;
4. Click on the “Фильмография” section;
5. Observe the hover behavior compared to the “Фильмография” section.

## Expected Result:
- All sidebar sections consistently respond to hover with a visual effect (e.g., color change or highlight), providing clear feedback to the user.

## Actual Result:
- Sidebar sections do not respond to hover, except for the “Фильмография” section on its dedicated page.

## Severity:
- Low.

## Priority:
- Minor.

## Evidence:

### Video:
- ![Bug Evidence](../Media/filmru_sidebar_hoverabsencebug.mp4)
