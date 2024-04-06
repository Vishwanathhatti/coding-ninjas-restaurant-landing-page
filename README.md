Restaurant Menu Application

Create a responsive Restaurant web application with a Bootstrap-integrated navbar for navigation, search functionality, and filter buttons for categorizing and searching menu items.

Welcome, developers! You are tasked with building a Restaurant Web Application using the supplied HTML, CSS, and JavaScript code (starter kit) for the frontend. This app should allow users to view items, filter items through categories and search items through name.

General requirements
Your solution should retain the structural integrity of the starter kit while introducing functional enhancements and visual refinements to elevate the user experience. The home page or the landing page for Html, CSS and Javascript projects should be 'index.html' .

Must to Use Code Structure

HTML Structure:
● Create an index.html file.
● Link Bootstrap's CSS in the <head> section.
Building the Navbar:
● Use Bootstrap's navbar component for navigation.
● Navbar should have the bootstrap class of (.navbar)
● Include 5 navigation links using class as (.nav-link)
.● Implement a search input field (#search-input) in the navbar.
Building Video Interface:
● The video that will be played should be
(“https://files.codingninjas.in/restaurant-1706081051.mp4”)
● The video should be playing in a loop
● The video should in autoplay.
● The controls of the video should be off .
Implementing the Menu Display:
● Use Bootstrap's card component to display menu items
dynamically.
● Each item should have the .menu-item class and display its
category.
● There are five categories which would be 5 buttons with class
(.nav-link) inside each parent list with class (.nav-item) .
● The 5 buttons should have the text content as “All” , “Starters” ,
“Mains” , “Desserts” , “Beverages” .
● These five buttons will have data-filter as “all” , “starters” ,
“mains” , “desserts” , “beverages” accordingly for filtering
purpose .
● The card for each food item which will be dynamically rendered
should look like this or have this structure :-
● Utilize the provided menu array and add more items if desired.
Filter Buttons & Search Functionality:
● Develop filter buttons for different dish categories.
● Implement click event listeners to filter displayed items based on
category selection.
● Enable search functionality to filter items based on user input in
the #search-input.
<div class="menu-item">
<div class="card">
<img src="${item.img}" class="card-img-top"
alt="${item.title}">
<div class="card-body">
<h5 class="card-title">${item.title}</h5>
<h6 class="card-subtitle mb-2
text-muted">${item.price}</h6>
<p class="card-text">${item.description}</p>
<p class="card-text"><small
class="text-muted">Category: ${item.category}</small></p>
</div>
</div>
</div>
Responsiveness:
Desktop View (1280x720 resolution):
● Ensure consistent styling and layout for desktop screens.
● Display the navbar with navigation links and search input.
● Render menu items with categories.
● Make sure only maximum 3 menu items are rendered in a row
Medium View (768x1024 resolution):
● Include a navbar toggler with class (.navbar-toggler) visible by
default for smaller screens.
● Initially hide navigation links and the search input.
● Implement functionality for the toggler to display the navigation
links and search input upon clicking.
● Make sure only maximum 2 menu items are rendered in a row
Mobile View (375x667 resolution):
● Include a navbar toggler with class (.navbar-toggler) visible by
default for smaller screens.
● Initially hide navigation links and the search input.
● Implement functionality for the toggler to display the navigation
links and search input upon clicking.
● Make sure only maximum 1 menu item are rendered in a row
