# Learn Regular Expressions by Building a Spam Filter

## Overview
This project involves building a simple spam filter using regular expressions. Users can input a message, and the system checks whether the message contains patterns commonly associated with spam. The implementation includes a basic HTML structure for the user interface, CSS for styling, and JavaScript for the functionality.

## Files
- **index.html:** The main HTML file that structures the web page, includes the interface, and links to external styles and scripts.
- **styles.css:** The CSS file for styling the web page, providing a visually appealing and responsive design.
- **main.js:** The JavaScript file containing the logic for the spam filter, utilizing regular expressions to identify potential spam messages.

## HTML Structure
The HTML file (`index.html`) consists of the following sections:
- **Head:** Contains metadata such as character set, viewport settings, and the title of the webpage.
- **Body:** The main body of the webpage with a header, main content, and footer.
  - **Header:** Includes a title and a brief description of the spam filter.
  - **Main Content:** Contains a textarea for inputting a message, a button to check the message for spam, and a paragraph to display the result.
  - **Footer:** Displays a copyright notice.

## CSS Styling
The CSS file (`styles.css`) defines the styling for the webpage, including color schemes, font sizes, button styles, and layout adjustments for responsiveness.

## JavaScript Logic
The JavaScript file (`main.js`) implements the spam filter logic using regular expressions. It defines several regular expressions representing common spam patterns and a deny list containing these patterns. The `isSpam` function checks whether a given message matches any of the spam patterns. The script also handles user input and displays the result dynamically on the webpage.

## Spam Patterns
The regular expressions in the deny list include patterns related to requests for help, mentions of money, promises of free items, references to stocks, and typical salutations used in spam messages.

## How to Use
1. Open `index.html` in a web browser.
2. Enter a message in the textarea.
3. Click the "Check message" button.
4. The result will be displayed below the button, indicating whether the message is likely spam or not.

Feel free to customize the regular expressions and deny list based on specific spam patterns you want to identify.

## Credits
This project was created as a part of the freeCodeCamp curriculum.


