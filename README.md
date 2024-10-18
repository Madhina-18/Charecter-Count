
# Character Counter Message Box

This project is a simple *Character Counter Message Box* created using HTML, CSS, and JavaScript. It provides users with a live character count feature while they type in a text area. This project is ideal for practicing JavaScript event handling, DOM manipulation, and CSS styling.

## Features

- *Real-time Character Count*: Displays the number of characters entered in the message box in real-time.
- *Dynamic Styling*: Visual feedback with CSS, such as changing text color when a certain character limit is exceeded.
- *Customizable*: Easily modify the character limit and styling to fit your own needs.

## Technologies Used

- *HTML*: For structuring the message box and character count display.
- *CSS*: For styling the message box and character counter.
- *JavaScript*: For implementing the character count functionality and updating it in real time.

## How It Works

1. *HTML*: 
   - A textarea element is used for the user to input text.
   - A div or span is used to display the character count.

2. *CSS*:
   - Basic styling is applied to make the text area and character counter visually appealing.
   - Optional color change when character limit exceeds.

3. *JavaScript*:
   - An event listener is added to the text area to detect every keystroke.
   - The script counts the length of the text and updates the character count display in real time.

## Installation & Setup

To use or modify this project, follow these steps:

1. *Clone the repository*:
   bash
   git clone <repository-link>
   

2. *Open the project folder*:
   bash
   cd character-counter-message-box
   

3. **Open index.html in your browser**:
   - Right-click on the index.html file and select "Open with" > Your preferred browser.

## Usage

- Type your message in the text area provided, and the character counter will display the number of characters you’ve entered.
- The character limit can be configured by changing a specific value in the JavaScript file.

## Customization

- *Character Limit*: Modify the JavaScript file to set a different character limit.
  javascript
  const characterLimit = 100;  // You can change this value to suit your needs
  
- *Styling*: Customize the look of the text area and counter by updating the CSS.

## Project Example

Here’s an example of how the character counter behaves:

plaintext
[Text Area]
Characters: 150/ 200


