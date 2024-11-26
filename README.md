
# People Counter Project

## Description
This is a simple **People Counter** web application that allows users to:
1. **Increment** the count of people entered.
2. **Save** the count as a record of previous entries.

The app displays the total count dynamically and stores a history of saved counts.

---

## Features
- Increment the count with the **INCREMENT** button.
- Save the current count with the **Save** button.
- View saved counts in a "Previous Entries" section.

---

## File Structure
The project consists of three files:

- `index.html`: The structure and content of the web page.
- `index.css`: Styles for the web page (not provided in this example but can be used to enhance the visual appeal).
- `index.js`: JavaScript file to handle the application's functionality.

---

## How It Works

### HTML
- The `count-el` element (`<h2>`) displays the current count.
- The `save-el` element (`<p>`) shows the saved counts.
- Two buttons:
  - **INCREMENT**: Triggers the `increment()` function to update the count.
  - **Save**: Triggers the `save()` function to record the count.

### JavaScript
- **Variables**:
  - `countEl`: Tracks the element displaying the current count.
  - `saveEl`: Tracks the element displaying the saved counts.
  - `count`: A numeric variable to keep track of the total count.

- **Functions**:
  1. `increment()`:
     - Increases the count by 1.
     - Updates the `count-el` element to display the new count.
  2. `save()`:
     - Appends the current count to the `save-el` element, formatted as "count - ".
     - Leaves the current count unchanged.

---

## Installation and Usage

1. Clone or download this project.
2. Open the `index.html` file in any modern web browser.
3. Use the buttons to interact with the application:
   - Click **INCREMENT** to increase the count.
   - Click **Save** to log the current count into the "Previous Entries" section.

---


---

## Future Improvements
- Add a **RESET** button to clear the count and saved entries.
- Style the app with CSS for better visual appeal.
- Store saved entries using browser local storage for persistence.

---

## License
This project is open source and free to use. Feel free to modify and enhance it as needed!



Quick start:

```
$ npm install
$ npm start
````



