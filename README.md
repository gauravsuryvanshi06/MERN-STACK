# Frontend

This frontend project is developed to interact seamlessly with backend APIs for managing and analyzing product transactions. It provides a user-friendly interface featuring a table and various charts based on data fetched from the backend.

## Usage

To use the frontend application, follow these steps:

1. Ensure the backend API is deployed and accessible.
2. Clone the frontend repository to your local machine.
3. Install the necessary dependencies using your preferred package manager (e.g., npm or yarn).
4. Run `npm install` or `yarn install`.

## Features

### Transactions Table

#### Select Month Dropdown
1. Displays options from January to December.
2. Defaults to March.
3. Allows selecting a different month to display transactions.

#### Transactions List
1. Utilizes the transactions listing API to populate the table.
2. Displays transactions for the selected month regardless of the year.
3. Filters transactions based on title, description, or price using the search box.
4. Clears the search box to display the initial list of transactions for the selected month.
5. Loads the next or previous page of data using Next and Previous buttons.

### Transactions Statistics
1. Shows the total sale amount, total sold items, and total unsold items for the selected month.
2. Fetches data from the API to populate the statistics box.

### Transactions Bar Chart
1. Displays a bar chart showing the price ranges and the number of items in each range for the selected month.
2. Uses the selected month from the dropdown (above the table) to fetch data from the API.
