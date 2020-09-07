## Object

- Objects group together a set of variables and functions to create a model of something that is recognizable on the website.

    - Variables are know as properties in objects.
    - Functions become know as methods.
    - The name of an object is called a key.
        - There cannot be 2 keys with the same name, because the key is used to access their corresponding values.
    - The value of a property can either be a string, number, Boolean, array or even another object.
    
- Literal notation is the easiest and most popular way to create objects. _Example Below_;

    `var hotel = {
        name: 'quay',
        rooms: 40,
        booked: 25,
        checkAvailability: function() {
            return this.rooms - this.booked;
        }
    };`

 ## Document Object Model

- The DOM specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a webpage while it is in the browser window.
    - The DOM specifies the way the browser should structure the HTML model using a DOM Tree

- The DOM Tree consists of four main types of nodes.
    1. Document Node - the document node is what the entire code should run as. ie. <html>

    2. Element Node - this node is comprised of elemnts that describe that structure of the HTML page. ie. <h1> , <p>

    3. Attribute Nodes - The attributes are what is contained in the element nodes, what the user actually sees as far as the color or format. ie. CSS to edit text.

    4. Text Nodes - The text is the text the user sees on the website. ie. <p>Today is a good day</p>



## Problem Domain

- This article explains why problem domains may be the most difficult part of coding.

- It compares writing code like putting together a very difficult jigsaw puzzle.

- The difficult problem is many problem domains are like a puzzle with a blurry picture or no picture at all.

- 2 things to make a problem domain easier.

    1. Make the problem domain easier

    - By making the problem domain smaller and increasing it slowly so that you understand the full problem domain.


    2. Get a better understanding of the problem domain

        - Take time before coding to really understand the logistics of what you want to build before actually putting in key strokes.    


[<== BACK](README.md)