# Pagination
# React Pagination Example
This project demonstrates a simple implementation of pagination in React. The application fetches data from an external API and allows users to navigate through the data using paginated buttons. Additionally, users can adjust the number of items displayed per page.

# Features
Fetches data from an API (jsonplaceholder.typicode.com/todos).

Displays data in a paginated table.

Allows navigation between pages (First, Previous, Next, Last).

Adjustable page size (5, 10, 15, 20 items per page).

Shows the current page number and highlights the active page.


# Project Structure

App.js: Contains the main React component with pagination logic.

App.css: Styling for the components.

public/: Contains the static files for the app.

# Explanation of the Code
## State Variables:

items: Stores the full list of data fetched from the API.

pageSize: Manages how many items to show per page.

currentPage: Tracks the current active page.

currentItems: Stores the items that should be displayed on the current page.

pageCount: Keeps track of the total number of pages.

# API Data Fetching:

The data is fetched from the jsonplaceholder API.

The data is loaded when the component first renders using the useEffect hook.

# Pagination:

Users can click on numbered buttons to navigate between pages.

First/Prev/Next/Last buttons for easy navigation.

Dropdown to adjust the number of items displayed per page.

Page Size Options: Modify the <select> dropdown to include different page size options.
