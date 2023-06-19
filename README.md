# Random Quote Generator

This is a simple random quote generator implemented using HTML, CSS, and JavaScript. It displays a random quote and its author each time a button is clicked.

## Technologies Used

- HTML

- CSS

- JavaScript

![image](https://github.com/mebenbenyo/random-quote/assets/117006580/ba2b7aa0-5dc7-4e6e-9897-102db10d27e5)

## Setup Instructions

Clone the repository to your local machine or download the source code as a ZIP file.

Open the project folder in your preferred code editor.

## Implementation Details

The quote generator is implemented using JavaScript. Here are the key steps involved:


In the script.js file, an array of JavaScript objects is created to hold the data for the quotes. Each object in the array represents a quote and contains properties for the quote text and the author.


When the "Generate Quote" button is clicked, an event listener is triggered in JavaScript.


The event listener calls a function that selects a random quote from the array of quotes. It uses the Math.random() method to generate a random index within the range of the array length and retrieves the corresponding quote object.


The selected quote and its author are then displayed on the webpage by updating the text content of HTML elements using the innerText property.


## Conclusion

This simple random quote generator provides a basic example of using HTML, CSS, and JavaScript to display random quotes on a webpage. 
