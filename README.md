# ravenous
 First React App

 This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).


 This project is one of the larger independent projects from the Codecademy course, which mimics Yelp, allowing the user to search for restaurants near a location and sort by best match, highest rated, or most reviewed. The Yelp API is utlilzed to search for the restaurants. In this latest iteration:
    - the images are clickable and direct the user to the Yelp page for the restaurant in a new tab
    - the addresses are clickable and direct the user to the Google Maps page for the address
    - the 'location' input now includes autocompletion of addresses

Components:

App.js
    This is the main component, it takes the Yelp API and provides it to the SearchBar component, getting back a list of businesses for BusinessList and subsequently Business

Business.js
    This component populates the html file with information from a single business from BusinessList.js

BusinessList.js
    This component utilizes Business.js to populate a list of businesses from App.js

SearchBar.js   
    This component contains the search bar which is provided the search function from Yelp.js as a prop. This handles the changes to sorting and any other search terms

Yelp.js
    This component resides in the /util directory, contains the Yelp API used by App.js


