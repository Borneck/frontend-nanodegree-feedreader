#Feedreader Test with Jasmine

## Project Overview

In this project you are given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where you come in.

##Steps to Run
1. Download the repo.
2. Open index.html in the browser of your choice.
3. After loading, the test results should be displayed at the bottom of the page.


## What will be tested?

###General feed test
1.Test if there is a value in the allFeed variable or is it undefind.
2.Test if a url with http / s: request.
3.Test if a name has been specified.

### Test the menu
1. When loading the page tests if the hamburger menu is hidden
2. Tests if the hamburger menu appears after clicking.

### Test the first Entry
1. If there is at least one entry after asynchronous loading.

### A new Feed selection test
1. Test entry Select changes in the menu.

## Solutions to pass the test
1. Ensures it has a URL defined and that the URL is not empty.
2. Ensures it has a name defined and that the name is not empty.
3. Ensures the menu element is hidden by default. 
4. Make sure the menu is displayed when clicking, it will disappear when clicked again
5. Write a test suite named "Initial Entries".
6. Ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.
7. Ensures when a new feed is loaded by the loadFeed function that the content actually changes.


