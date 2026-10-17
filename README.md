# QuickNotes

QuickNotes is a simple note-taking web app built with HTML, CSS and vanilla JavaScript. You can add short notes, sort them into Personal, Work or Study categories, search through them and delete them. Your notes are saved in your browser, so they are still there when you come back.

## Features

- Add notes of up to 200 characters
- Choose a category: Personal, Work or Study
- Colour-coded note cards for each category
- Validation with clear error messages for empty or too-long notes
- Delete individual notes
- Live search that ignores upper and lower case
- Note counter ("You have no notes yet.", "You have 1 note.", "You have N notes.")
- Notes saved with localStorage so they survive a page refresh
- Responsive layout that stacks the form on small screens

## How to run locally

1. Clone the repository: `git clone https://github.com/YOUR-USERNAME/quicknotes-app.git`
2. Open the `quicknotes-app` folder.
3. Open `index.html` in your browser (or use the Live Server extension in VS Code).

## What I learned

- How to build a list from an array with `createElement` and `textContent`, and why that is safer than `innerHTML` for user text.
- How to save and load data with `localStorage` using `JSON.stringify` and `JSON.parse`.
- How to use Flexbox and a media query to make a form that works on both large and small screens.
- How to make small, clear Git commits as I finish each part of a project.