# ✈️ Plan With Love - Trip Planner

A dynamic React web application that showcases a list of travel destinations, allowing users to interact with tour cards by filtering options and toggling detailed information.

## 🚀 Features

* **Dynamic Card Rendering:** Displays a curated list of tours with images, prices, and titles.
* **Interactive Content:** "Read More" / "Show Less" functionality to toggle long descriptions without cluttering the UI.
* **Remove Items:** A "Not Interested" button that removes specific tours from the list (State Management).
* **Refresh Functionality:** When all tours are removed, a "Refresh" button allows the user to reload the original data.
* **Responsive Design:** Styled with CSS Flexbox for a clean layout on different screen sizes.

## 🛠️ Tech Stack

* **Frontend Library:** React JS
* **Styling:** CSS3 (Custom Grid/Flexbox layout)
* **Data Handling:** JavaScript (ES6)

## 📂 Project Structure

* **App.js:** The root component that manages the main state (`tours`) and handles the logic for removing tours and refreshing the list.
* **Tours.js:** A container component that iterates through the data and renders individual Card components.
* **Card.js:** A presentational component that handles its own local state for the "Read More" toggle feature.
* **data.js:** A static data file containing the array of tour objects.

## 🧠 Key Concepts Applied

This project demonstrates proficiency in the following React concepts:
1.  **useState Hook:** Managing local component state (toggling descriptions) and global application state (list of tours).
2.  **Props & Prop Drilling:** Passing data and functions (`removeTour`) from parent to child components.
3.  **Conditional Rendering:**
    * Switching between "Read More" and "Show Less".
    * Displaying the "Refresh" UI when the tours list is empty.
4.  **List Rendering:** Using `map()` to dynamically generate components based on data arrays.
5.  **Event Handling:** Managing click events for user interactions.

## 💻 How to Run Locally

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/05adi/trip-plan.git](https://github.com/05adi/trip-plan.git)
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd trip-plan
    ```

3.  **Install dependencies:**
    ```bash
    npm install
    ```

4.  **Start the application:**
    ```bash
    npm start
    ```

The app will launch in your browser at `http://localhost:3000`.
