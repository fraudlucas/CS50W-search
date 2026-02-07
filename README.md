# CS50W-search

A front-end implementation of Google Search, Google Image Search, and Google Advanced Search pages.

**Project 0** from [CS50's Web Programming with Python and JavaScript](https://pll.harvard.edu/course/cs50s-web-programming-python-and-javascript)

> **Note**: This project was created for educational purposes as part of CS50W coursework. It is a learning exercise in HTML, CSS, and web design fundamentals.

## What This Project Is

This repository contains a static website with three pages that replicate the user interface of Google's search services:
- **Google Search**: A main search page with a centered search bar and search buttons
- **Google Image Search**: A dedicated page for image searches
- **Google Advanced Search**: A page with advanced search options for refined queries

The project demonstrates front-end web development skills including HTML structure, CSS styling, form handling, and responsive design principles consistent with Google's design aesthetics.

## How to Run

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge, etc.)
- No server or backend required - this is a static frontend

### Steps

1. **Clone or download the repository**
   ```bash
   git clone <repository-url>
   cd CS50W-search
   ```

2. **Open the main page**
   - Navigate to the project folder
   - Double-click `index.html` to open it in your default browser, OR
   - Right-click `index.html` → Open with → Select your preferred browser

3. **Navigate the site**
   - From the main Google Search page (`index.html`), you can access:
     - Google Image Search by clicking the link in the upper-right
     - Google Advanced Search by clicking the link in the upper-right
   - Each page links back to Google Search for easy navigation

4. **Test the functionality**
   - Enter search queries and click "Google Search" to perform actual Google searches
   - Use "I'm Feeling Lucky" to go directly to the first result
   - Use the advanced search filters to refine your queries

## Specification

## Specification

Your website must meet the following requirements:

* Your website should have at least three pages: one for regular Google Search (which must be called `index.html`), one for Google Image Search, and one for Google Advanced Search.
    * On the Google Search page, there should be links in the upper-right of the page to go to Image Search or Advanced Search. On each of the other two pages, there should be a link in the upper-right to go back to Google Search.
* On the Google Search page, the user should be able to type in a query, click "Google Search", and be taken to the Google search results for that page.
    * Like Google's own, your search bar should be centered with rounded corners. The search button should also be centered, and should be beneath the search bar.
* On the Google Image Search page, the user should be able to type in a query, click a search button, and be taken to the Google Image search results for that page.
* On the Google Advanced Search page, the user should be able to provide input for the following four fields (taken from Google's own [`advanced search`](https://www.google.com/advanced_search) options)
    * Find pages with... "all these words:"
    * Find pages with... "this exact word or phrase:"
    * Find pages with... "any of these words:"
    * Find pages with... "none of these words:"
* Like Google's own Advanced Search page, the four options should be stacked vertically, and all of the text fields should be left aligned.
    * Consistent with Google's own CSS, the "Advanced Search" button should be blue with white text.
    * When the "Advanced Search" button is clicked, the user should be taken to the search results page for their given query.
* Add an "I'm Feeling Lucky" button to the main Google Search page. Consistent with Google's own behavior, clicking this link should take users directly to the first Google search *result for the query, bypassing the normal results page.
    * You may encounter a redirect notice when using the "I'm Feeling Lucky" button. Not to worry! This is an expected consequence of a security feature implemented by Google.
* The CSS you write should resemble Google's own aesthetics.