# Calendar
1. Replace `<your_account>` with your Github username in the link
    - [DEMO LINK](https://<your_account>.github.io/layout_miami/)
2. This project requires you to work with `git` manually:
    - Fork and clone the project
    - `npm i` and `npm start` to start the development
    - `git checkout -b <branch-name>` create new branch and switch on it
    - write your code in `src` folder. `dist` is generated by `gulp` from your source files
    - `git add .` and `git commit -m 'your message'` to save you work locally
    - `git push origin <branch-name>` to send your code to github 
    - `npm run deploy` to publish you changes to `gh-pages`
    - Create a PR with `[DEMO LINK]` in the description
---

## Task
Display a calendar in the middle of the screen. The HTML of the calendar needs to have the following structure:

```html
    <div class="calendar calendar-30 calendar-tue">
        <div></div>
        <div></div>
        <!--
        ...
        31 child divs in total
        ...
        -->
        <div></div>
    </div>
```
- Use SASS (.scss) for this task. Please do not use JavaScript.
- Use the given HTML (don't change anything or add numbers 1 through 31).
- The first day of the week is Monday. (the first column)
- The `calendar-30` classname here means that the month has 30 days, and `calendar-tue` means that the first day of the month is Tuesday.
- Your calendar should also accept the following alternative classnames and display itself accordingly: `calendar-28`, `calendar-29`, `calendar-30`, `calendar-31`; `calendar-mon`, `calendar-tue`, `calendar-wed`, `calendar-thu`, `calendar-fri`, `calendar-sat`, `calendar-sun`.
- Each day must be represented by a 100px × 100px #eeeeee-colored cell (including 1px black borders).
- The gap between the cells must be 1 pixel.
- The date should be written in the middle of the corresponding cell with Arial 30px font.
- Upon hovering over a cell, the cursor should become pointer.
- The hovered cell has to become pink
  - (**Optional**) Move it up by `20px`.
  - (**Optional**) both of these properties are to be animated with the duration of half a second.

## Here is a preview: 
![reference image](reference.png).
