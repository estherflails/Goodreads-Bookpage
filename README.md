# Goodreads-Bookpage
This UserScript aims to bring a better experience to the new Goodreads Bookpage by resizing and repositioning the elements on the page.

If you still find the page contents too large, I recommend changing the browser setting to 90% zoom.

[Greasyfork Link](https://greasyfork.org/en/scripts/453992-goodreads-bookpage)

## What it does
- Moves these sections to the right side:
  - Readers also enjoyed
  - Other books in the series
  - Other books by this author
  - Lists featuring this book
  - Book details and editions (This one appears at around the first review to make sure the other sections have enough space even if they don't appear for every book.)
- Resizes and repositions most elements
- Adds a light background color

## What it doesn't do
- Brings "Read Less" back for description and reviews
- Brings elements that existed in the old bookpage but not in the new back, e.g. Quotes, Popular Answered Questions

## Known issues
- In a smaller browser size, elements might partially disappear or overlap each other.

## Changelog
0.5 - Changed the position of "Ratings & Reviews" title so it does not overlap in books that have no summary or author info.

0.6 - Updated to work even if Goodreads includes the language in the url.

0.7 - URL fix

## Screenshot
![image](https://user-images.githubusercontent.com/23014105/198884618-d9f93551-98ef-46f3-bb06-63c3b97a13a6.png)
