# Project Overview

A series of tests using Jasmine were written against a pre-existing web application that reads RSS feeds.   The application already included Jasmine and a first test suite was already written.

## Tests performed
1. A test was written within the `"RSS Feeds"` suite that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
2. A test was written within the `"RSS Feeds"` suite that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
3. A new test suite named `"The menu"` was created.
4. A test was written within the `"The menu"` suite that ensures the menu element is hidden by default.
5. A test was written within the `"The menu"` suite that ensures the menu changes visibility when the menu icon is clicked. This test has two expectations: does the menu display when clicked and does it hide when clicked again.
6. A new test suite named `"Initial Entries"` was created.
7. A new test was written the `"Initial Entries"` suite that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
8. A new test suite named `"New Feed Selection"` was created.
9. A new test was written with the `"New Feed Selection"` suite that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.

## How to Run the Test
Open up the index.html in the browser.  It is expected that all tests should pass.  The test results will be listed under Jasmin at the bottom of the page.
