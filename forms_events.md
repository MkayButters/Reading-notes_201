## Forms

- In HTML form refers to different elements that allow you to collect information from visitors to your site.

- A common known form is the searchbox on googles homepage.

- Serval types of forms include
1. Text input
    - A single line

2. Password input
    - A single line with masked characters

3. Text areaa
    - Multi line text input 

4. Radio buttons
    - Multi buttons user must select 1 option

5. Checkboxes
    - Multiple select of unselect boxes of 1 or more options

6. Drop down boxes
    - User must pick an option on list

7. Submit buttons
    - To submit date from your form to another page

8. Image buttons
    - Similar to submit but allow you to use an image

9. File upload
    - Allows user to upload files to a website

- Every form has an action and a method, get or post.
    - ie. <form action = "link"
            method= get>

- The input element is used to create several different forms
    - It is comprised of type="" , name , size and maxlength
        - Type can be either text, password, radio, checkbox, file, submit, image, hidden, date, email, and search.

## Lists, Tables, and Forms

- Unordered and ordered lists can be changed to many different values even to appear as images.
    - Lists position, style also can be edited with CSS
 
- Tables are created to help organizing information displayed
    - width, padding, text transform, letter spacing, font size, borders, align text, background color and hover are all features of a table

## Events

- When browsing the browser registers different types of events.
    - Interactions create events with a click or a tap on a link.
    - These events trigger a code
    - This code reponds to users.

- When HTML is interacted with on the webpage, if it is written, they trigger some javascript code. Together the following steps and know as event handling

1. Select the element node you want the script to respon to
2. Indicated which event on the selected node will trigger response
3. State the code you want to run when the event occurs

- There are 3 ways to bind HTML to a code

    1. HTML Event handlers
        - Do not use these

    2. Traditional DOM event handlers
        - Use a named function so it fires on your chosen DOM node
        - DOM element node is store in a variable
        - 
    3. DOM level 2 event listeners.
        - Deal with more than one function at a time

- The flow of event matters only when your code has event handlers on an element and one of it ancestors or descendent elements.

- When an event occurs the event object tell you info about the event and the elemeent it happen upon

- You can use event delegation to monitor for events that happen on all of the children of an element

- The most commonly used events are W3C DOM events, although there are other in the HTML5 specification as well as browser-specific events






[<== BACK](README.md)