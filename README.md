# Library Kiosk Logging System

this is my sprint 12 project for the library checkout logging system. built it using plain HTML, CSS and JavaScript (no frameworks).

## What this project does

its a simple book checkout tracker for a local library. the staff can log which book was taken and by which patron. all the data is saved in the browser so it works even without internet.

## Features

- add a book checkout with title and patron id
- all records show up in a table
- data stays saved even after refreshing the page (using localStorage)
- can delete any record from the table
- shows error if you try to submit empty fields

## Technologies used

- HTML
- CSS
- Vanilla JavaScript
- localStorage (for saving data in browser)

## How to run

1. download or clone this repo
2. open the folder in VS Code
3. right click on index.html and click "Open with Live Server"
4. it will open in your browser at http://127.0.0.1:5500

or you can just double click the index.html file to open it directly in browser

## Folder structure

```
library-kiosk/
├── index.html
├── README.md
└── PROMPTS.md
```

## What I learned

- how localStorage works for saving data without a backend
- event delegation for handling dynamic elements
- using filter() to delete items from an array
- DOM manipulation using vanilla JS

## Live Demo

deployed on GitHub Pages:
https://yourusername.github.io/library-kiosk/

(replace yourusername with your actual github username)
