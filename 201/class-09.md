# Class Nine

- Why are forms so important in web development?
The <form> element formally defines a form and attributes that determine the form's behavior. HTML Forms are required, when you want to collect some data from the site visitor. For example, during user registration you would like to collect information such as name, email address, credit card, etc.

- When designing a form, what are some key things to keep in mind when it comes to user experience? make sure that you have all the boxes you will need on a website for the customers information. You also want to make sure that it is user friendly and the visitor is able to understand and that it is usable and accesible.


- List 5 form elements and explain their importance.

- input element can be displayed in several ways, depending on the type attribute
text fields  allow users to enter text into a UI

- checkboxes allows you to select single values for submission in a form

- radio buttons allow one to be selected out of them all, whereas checkboxes allow multiple values to be selected.

- submit buttons are used to submit forms. If you want to create a custom button and then customize the behavior using JavaScript

- How would you describe events to a non-technical friend?

- When using the addEventListener() method, what 2 arguments will you need to provide?
Sending arguments to an eventListener's callback function requires creating an isolated function and passing arguments to that isolated function 

- Describe the event object. Why is the target within the event object useful?contains a number of properties that describe the event that occurred.Events are actions or occurrences that happen in the system you are programming, which the system tells you about so your code can react to them.

- What is the difference between event bubbling and event capture
A bubbling event goes from the target element straight up. Normally it goes upwards till <html> , and then to document object
Event capturing means propagation of event is done from ancestor elements to child element in the DOM 