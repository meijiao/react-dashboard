# Dashboard
Built with React.js

## Screenshot
----
<img src="./dashboardScreenshot.jpg">

## Usage
----
    cd dashboard
    npm install
    npm start

## About
----
* Fields are dynamically generated based on input
* Headers are created by parsing the input for content title
* Data fields are then extracted based on the header title
* Smart Formatting. Conversion of data (e.g. from number to currency) is dynamic and based on input field type

## Component Hierachy
----

* App is the overall container
* App contains Summary and Table
* Table contains Rows
* Each Row contains Fields

----