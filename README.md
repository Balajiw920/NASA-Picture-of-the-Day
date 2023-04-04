# NASA-Picture-of-the-Day

Project Overview (100 Marks)
Task
Build a web page that retrieves data from NASA's Picture of the Day API, allowing the user to select a date from a form and send it in the query params. The page should allow the user to save their searches to local storage and display their past searches on the page. The page should also display the current image of the day when it loads.

Problem Statement
Create an HTML file with a form that allows the user to select a date and a submit button. The form should have an ID of "search-form" and the input field should have an ID of "search-input".


Create a section in the HTML file with an ID of "current-image-container" where the data will be shown.


Create an unordered list in the HTML file with an ID of "search-history" where the user's past searches will be displayed.


Create a CSS file to style the HTML elements.


Create a JavaScript file with the following functions:


getCurrentImageOfTheDay(): This function should fetch the data for the current date from the NASA API and display it in the UI. This function runs when the page loads.
getImageOfTheDay(): This function should fetch the data for the selected date from the NASA API and display it in the UI. It should also save the date to local storage and also show it in the search history unordered list.
saveSearch(): This function should save a date to local storage. As shown in the recording, you need to just save the dates in an array.
addSearchToHistory(): This function should add the date to the search history list in the Ui. You need to get the searches array from localstorage and display it as an unordered list in the ui. When a user clicks on the specific list item, you need to fetch the data for that specific date all over again and show it in the black div.
Make sure when the user clicks the list item , you show the search results again on the screen in the div as shown in the ui reference.
