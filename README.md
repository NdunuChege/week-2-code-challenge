# week-2-code-challenge
This repository contains a simple interactive shopping list application built using HTML, CSS, and JavaScript. The application allows users to add items, mark them as purchased, edit existing items, and clear the list. The shopping list is stored in the browser's local storage, ensuring that data persists across page reloads.

Features Include : 
   Add Items: Users can input an item and add it to the shopping list.
   Mark as Purchased: Users can click on an item to mark it as purchased, which visually indicates that the item has been bought.
   Edit Items: Users can double-click on an item to edit its text.
   Clear List: Users can clear all items from the shopping list.
   Persistence: The shopping list is saved in the browser's local storage, allowing items to persist even after refreshing the page.
   
Technologies Used :
   HTML: For the basic structure of the application.
   CSS: For styling the application.
   JavaScript: For interactivity and handling the logic of the application.
   Local Storage: For data persistence.
   
Code Explanation :
   HTML (index.html)
     The HTML file includes an input field for adding items, buttons for adding items and clearing the list, and an unordered list to display the shopping list.
   CSS (styles.css)
      The CSS file styles the application with a simple design, providing aesthetics to the input field, buttons, and list items.
   JavaScript (script.js)
   Global Variables: Initializes variables to hold HTML elements and the shopping list.
   Local Storage: Loads the shopping list from local storage on page load.
   
Functions:
      renderList(): Renders the items dynamically in the DOM.
     saveToLocalStorage(): Saves the current shopping list to the local storage.
Event Listeners:
      For the "Add" button: Captures user input to add items.
      For individual list items: Allows marking as purchased and editing items on double-click.
      For the "Clear List" button: Clears the shopping list from both the UI and local storage.
