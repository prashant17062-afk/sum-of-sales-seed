Sales Summary Application

This single-page web application provides a summary of sales data fetched from a CSV file. It dynamically calculates the total sales from the 'sales' column and displays this sum on the page, leveraging Bootstrap 5 for a clean and responsive design.

Features:
- Fetches `data.csv` from the same directory where `index.html` is hosted.
- Parses the CSV content to extract and sum numerical values from the 'sales' column.
- Displays the calculated total sales amount prominently on the page.
- Integrates Bootstrap 5 for modern styling and layout.
- Sets a specific page title dynamically upon loading.

Usage:
1. Place `index.html` and your `data.csv` file in the same directory on a web server or open `index.html` directly in a browser (some browsers might have restrictions on local file fetching).
2. Ensure `data.csv` contains a header row, with at least one column named "sales". This column should contain numerical values.
3. Open `index.html` in a web browser. The application will automatically process the CSV and display the total sales.

Example `data.csv` structure (expected to sum to 12345.67 for testing):
product,sales,region
Widget A,1000.50,North
Gadget B,2000.00,South
Tool C,3000.17,East
Accessory D,4000.00,West
Part E,2345.00,Central

License:
This project is licensed under the MIT License.