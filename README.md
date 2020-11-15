# Go Where Ah?

## Introduction
Go Where Ah? Is a website for users to get ideas and inspiration on their next hangout and dining spot in Singapore. This was inspired by the common complaint that Singapore is too small, and the team behind this web app aims to dispel that myth. 

## Installation
1. Before using this app, run load.sql in PhpMyAdmin to create whereToGo database, with ‘bookmark’ table. This file can be found in the following path: ‘app/api/db/load.sql’
2. Ensure that WAMP/MAMP server is up and running before accessing Go Where Ah? In the browser
3. Open the app by accessing ‘localhost/app’. User will be directed to the home page of the site.
4. After screen loads, application is now ready to be explored. 

## Usage

### Accessing most popular searches - food

1. At index.html, scroll down to find the section “the most popular foods and hangouts, here”
2. Clicking on “korean cuisine” will direct user to food.html
3. Upon reaching food.html, the query “korean cuisine” will be passed into the Foursquare API, returning listing results of dining options pertaining to the search.
4. The same will happen when clicking on “french delights”.

### Accessing most popular searches - hangouts

1. At index.html, scroll down to find the section “the most popular foods and hangouts, here”
2. Clicking on “chinatown” will direct user to location.html
3. Upon reaching location.html, the query “chinatown” will be passed into the Foursquare API, returning listing results of places pertaining to the search.
4. The same will happen when clicking on “sentosa”.

### Viewing more information about Singapore’s attractions

1. At index.html, scroll down to find the green section which says “hover for a glimpse”
2. With the four image cards below, a mouse over on any one will reveal text that describes a particular fun fact about Singapore, while blurring the image to the background.
3. Mouse away for the text to disappear and image to return into focus.

### Searching for food recommendations

1. Click on “Food” tab in the navigation bar, and user will be directed to food.html
2. Upon landing, enter a food query into the search box given. For example, searching “coffee”
3. Pressing enter returns food listings with “coffee” in the title after the query is passed into Foursquare API.

### Searching for location recommendations

1. Click on “Location” tab in the navigation bar, and user will be directed to location.html
2. Upon landing, enter a location query into the search box given. For example, searching “jurong”
3. Pressing enter returns food listings with “jurong” in the title after the query is passed into Foursquare API.

### Bookmarking listings

1. From the listings in both the food or location page, there will be a bookmark button on each listing. 
2. Clicking on the button will enable the bookmark function, where the user's selection of this listing will be saved.
3. Clicking on the button again will delete the user's selection from the bookmarks.
4. Click on “bookmark” tab in navigation bar and user will be directed to bookmark.html
5. User’s previous bookmark selections will be displayed on this page.

### Removing bookmarks from bookmark page

1. Click on “Bookmark” tab in navigation bar and user will be directed to bookmark.html
2. Upon seeing the saved listings, the user will see a “Delete Bookmark” button for each listing.
3. Clicking on the “Delete Bookmark” button will remove the bookmark from the page, with an alert confirming with the user that the relevant bookmark will be deleted.

### Viewing maps for food or location listing

1. From the listings in either the food or location page, there will be a “Let’s Go!” button on each listing. 
2. Clicking on the “Let’s Go!” button will open a modal with the name of the listing, address as well as map location indicated.
3. The user will be able to know where exactly the attraction is and therefore figure out how to get there.

### Viewing weather forecast for the day

1. When the user accesses the Go Where Ah? Application, he is able to see the weather predictions for today with the temperature readings on the navbar.
2. The temperature readings indicate the highest temperature for the day, as well as the lowest, using Data.gov.sg 24-hour Weather Forecast API 

## Page Details

### Home Page (home.html)
Presents the most popular searched items, where users can click and be directed to the relevant pages. It also presents fun facts that users can learn about Singapore, with aesthetically pleasing images and colors to welcome the user.

### Food Page (food.html)
On this page, users can search restaurants that offer a particular food that they are craving for, or a restaurant that offers a particular cuisine. This page will then show the relevant results that users will be able to gain more information from and interact with.

### Location Page (location.html)
On this page, users can search places that they are interested in, or an attraction that they have heard of. This page will then show the relevant results that users will be able to gain more information from and interact with.

### Bookmark Page (bookmark.html)
On this page, users will be able to view the bookmarks they have saved, which will be useful if they have done many searches and want to recall the listings that they were interested in visiting. The bookmarks will show the name of the listing they saved, as well as the relevant address. Users will have the option to delete the bookmark as well. 

### About Us Page (aboutus.html)
This page gives an overview of what the site is about, its origins and shares with the user the developers behind the site.

## Authors and Acknowledgement

### Group Members:

1. Marcus Goh Jun Cheong
2. Siti Hindun Binte Murtaza
3. Adrian Poh Eik Yong
4. Thinesh S/O Kalaichelvan
5. Ng Elvin

### API Acknowledgement

1. Google Maps API
2. Data.gov.sg 24-hour-weather Forecast API 
3. Foursquare API
4. Unsplash API
