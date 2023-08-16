## Password Validation Checker

This is a simple password validation checker that checks if a password meets the following requirements:

* At least 8 characters long
* At least one number (0-9)
* At least one lowercase letter (a-z)
* At least one uppercase letter (A-Z)
* At least one special character (!, @, #, $, %, ^, &, *, _, -, +, =, ., ,)

To use the password validation checker, simply enter your password in the input field. The checker will then automatically check if your password meets the requirements and display a message accordingly.

## Code Explanation

The password validation checker is built using HTML, CSS, and JavaScript. The HTML code defines the structure of the page, the CSS code defines the styling of the page, and the JavaScript code defines the functionality of the page.

The JavaScript code first defines an array of password requirements with corresponding regular expressions and index of the requirement list item. The regular expressions are used to check if the password matches the corresponding requirement. The index of the requirement list item is used to update the class and icon of the requirement item if the requirement is met or not.

The JavaScript code then defines two event listeners: one for the "keyup" event on the password input field and one for the "click" event on the eye icon. The "keyup" event listener checks if the password matches the requirements and updates the class and icon of the requirement items accordingly. The "click" event listener toggles the password input type between "password" and "text" and updates the class of the eye icon accordingly.

## Usage

To use the password validation checker, simply clone the repository and open the index.html file in a web browser. You can then enter your password in the input field and click the "Validate Password" button to check if your password meets the requirements.

I hope this helps!