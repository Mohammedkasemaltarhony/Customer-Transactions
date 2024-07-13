# Customer Transactions

This project is a web application that displays customer transactions. It allows users to filter transactions by customer name and transaction amount, and view detailed transaction summaries in a modal dialog.

## Project Structure


.
├── css
│   └── style.css
├── data
│   └── data.json
├── js
│   └── app.js
├── index.html
└── README.md


## Features

•  [**Filter Transactions**]: Users can filter transactions by customer name and transaction amount.

•  [**Transaction Summary**]: Clicking on a customer name shows a detailed summary of their transactions in a modal dialog.

•  [**Animated Table Rows**]: Table rows are animated using Animate.css for a smooth user experience.

•  [**Chart Visualization**]: Transaction data is visualized using Chart.js.


## Getting Started

### Prerequisites

•  A web browser (e.g., Chrome, Firefox)

•  Internet connection to load external libraries (Animate.css, Chart.js)


### Installation

1. Clone the repository:
```bash
git clone https://github.com/Mohammedkasemaltarhony/Customer-Transactions.git

1. 
Navigate to the project directory:

cd Customer-Transactions

Running the Project
1. 
Open index.html in your web browser.

Project Files
•  index.html: The main HTML file that contains the structure of the web application.

•  css/style.css: The CSS file that contains styles for the web application.

•  data/data.json: The JSON file that contains customer and transaction data.

•  js/app.js: The JavaScript file that contains the logic for fetching data, filtering transactions, and rendering the table and charts.

Example Data Format
The data.json file should have the following structure:

{
"customers": [
{
"id": 1,
"name": "John Doe"
},
{
"id": 2,
"name": "Jane Smith"
}
],
"transactions": [
{
"customer_id": 1,
"date": "2023-07-01",
"amount": 100.00
},
{
"customer_id": 2,
"date": "2023-07-02",
"amount": 150.00
}
]
}

Troubleshooting
Common Issues
•  404 Error for JSON File: Ensure the data.json file is correctly placed in the data folder and the path in the fetch call is correct.

•  Case Sensitivity: Ensure file names and paths are correctly cased, as GitHub Pages is case-sensitive.

Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

Acknowledgements
•  Animate.css

•  Chart.js
