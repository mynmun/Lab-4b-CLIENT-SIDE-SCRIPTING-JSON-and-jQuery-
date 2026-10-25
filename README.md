# JSON and jQuery Assignment

**Student Name:** KHAIRULAMIRIN BIN AZHAR  
**Student ID:** CI240121 
**Course:** BIC21203 
**Assignment:** Create and Structure JSON Data, Retrieve JSON Data, and Compare Native JavaScript with jQuery

## GitHub Repository

[Insert your GitHub repository link here]

## Project Overview

This project demonstrates how to create JSON data, retrieve and display JSON data using native JavaScript, and manipulate HTML elements using jQuery.

## Project Files

```text
Lab4_JSON_jQuery/
├── books.json
├── books.html
├── jquery-dom.html
├── README.md
└── screenshots/
    ├── question1-json.png
    ├── question2-output.png
    ├── question3-dom.png
    └── question3-alert.png
```

## Question 1: Create and Structure JSON Data

**File:** `books.json`

The JSON file contains a top-level `books` array with two book objects. Each object includes a title, author, publication year, and an array of genres.

**How to run and test:**

1. Open `books.json` in Visual Studio Code.
2. Check that all property names and string values use double quotes.
3. Verify that `publicationYear` contains numeric values.
4. Ensure there are no trailing commas.
5. Parse the JSON to confirm that it is valid.

**Expected result:** The JSON file parses successfully and contains both book records.

**Screenshot evidence:** `screenshots/question1-json.png`

## Question 2: Retrieve and Display JSON Data

**File:** `books.html`

The HTML page uses the native JavaScript `fetch()` API to retrieve data from `books.json`. It displays the first book's title, the second book's author, and the genres grouped by book title.

The page uses `textContent` and `createElement()` to display text safely. It also handles unsuccessful requests and invalid JSON data with a user-friendly error message.

**How to run:**

1. Open the project folder in Visual Studio Code.
2. Install the Live Server extension if it is not already installed.
3. Right-click `books.html`.
4. Select **Open with Live Server**.
5. Check the output in your browser.

**Expected output:**

- The Great Gatsby
- Harper Lee
- The Great Gatsby — Fiction, Classics
- To Kill a Mockingbird — Fiction, Coming-of-Age

**Screenshot evidence:** `screenshots/question2-output.png`

## Question 3: Compare Native JavaScript and jQuery

**File:** `jquery-dom.html`

This page uses jQuery 4.0.0 from the official CDN to perform three DOM operations.

| jQuery method | Function |
|---|---|
| `.text()` | Replaces the text of `#myElement` with `Modified Text`. |
| `.addClass()` | Adds the `myStyle` CSS class to `#myDIV`. |
| `.on("click", ...)` | Displays an alert when `#myButton` is clicked. |

**How to run:**

1. Open `jquery-dom.html` using Live Server.
2. Verify that `Original Text` changes to `Modified Text`.
3. Verify that the `myDIV` element has a coral background and 16px padding.
4. Click the **Click me** button.
5. Confirm that the alert displays `Button clicked!`.

**Screenshot evidence:**

- `screenshots/question3-dom.png`
- `screenshots/question3-alert.png`

## Comparison: Native JavaScript and jQuery

**One advantage of native JavaScript:** It supports DOM manipulation through built-in browser APIs without requiring an additional library.

**Why an existing project may use jQuery:** The project may already depend on jQuery and its plugins, so continuing to use it can be more practical than rewriting existing code.

## Reflection

Through this assignment, I learned how to structure JSON data using objects and arrays. I practised retrieving JSON data with the JavaScript `fetch()` API and displaying it on a webpage. I also learned how to manipulate DOM elements using jQuery methods. This assignment improved my understanding of JSON processing and the differences between native JavaScript and jQuery.

## Requirements

- Visual Studio Code or another code editor
- A modern web browser
- Live Server extension for running the HTML files locally
- Internet connection for loading jQuery 4.0.0 from the official CDN

## Conclusion

This assignment demonstrates JSON data creation and validation, asynchronous data retrieval, safe display of text on a webpage, and DOM manipulation using jQuery. The completed files and screenshots provide evidence of the expected functionality.
