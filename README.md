## Password-Strength-Indicator
Your password will be described as either weak, medium or strong depending on the length and use of different characters/symbols for your password.

## HTML Structure:

The project begins with an HTML structure that includes a simple input box where the user can type their password.
Next to the password field is a button with an arrow icon, which simulates submitting the password.
Below the input field, there's a message that shows the password strength as weak, medium, or strong. This message only appears once the user starts typing a password.

## JavaScript Logic:

The JavaScript code listens for any input in the password field.
When the user starts typing, the strength message is shown. If the password length is less than 4 characters, the password is considered "weak" and the indicator turns red.
If the password is between 4 and 7 characters, it is marked as "medium" and the indicator turns yellow.
Passwords that are 8 characters or longer are considered "strong," and the indicator turns green.

## Real-Time Feedback:

As the user continues to type, the strength message and the color of the input field border update in real time, helping them gauge whether their password is secure enough.
