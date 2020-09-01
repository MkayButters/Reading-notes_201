## Links

- Links are created using the `<a>` element.
- `href` is used inside the opening `<a>` tag to link

- Between the opening and closing `<a>` tag is where you put what you want the user to see and click on to access your link.
- When using a link to another website use the __absolute URL__,  which is the whole web address.

- When using a link to other pages within your site use the name of the file within the folder you are making the website you are in, know as the __relative URL__.

- On larger webpages it is smart to organize the code by placing the pages for each different section of the site into a new folder.

- The top level is know as the __root__ folder. This folders inside are described as in a family tree _parent/child_ or _grandparent/grandchild_.

- Email links also can be used with the `mailto:` element contained within the opening `<a>` element using the `href` tag to link it.

- To have the link open in a new window, use the element `target="_blank"` at the end of the opening `<a>` tag.

- To link to a certain part of the page, use the `id=` attribute inside the tag you want to redirect to. Then add a link to the id using the `<a href=` in your code to link to where you want to have the link

## Layout

- CSS treats each HTML element as if its in its own box.

- Positioning schemes are used in CSS to control the layout of the page

    - Using normal flow scheme, every block level element appears on a new line
    - Using the relative positioning scheme, the element is shifted to the top, bottom, right, or left of where it should have been placed.
    - Using the absolute positioning scheme, takes the element out of normal flow, which means that it does not affect the position of any of the other elements.

- The z-index is a noteable element to use in future projects.

- The `float` property allows you move an element in normal flow to place is far right or far left as possible of the containing element.

- Using the property `clear` will make sure no other elements touch the sides (left or right) of the element.

- In this day and age there is many different devices that will be accessing your website. It is important that the design works on a range of different screens.

- Most web designers create pages of around 960-1000 pixels in width.

- Fixed width layout designs do not change sizes as the users browser window is increased or decreased.

    - This is done by using the specific pixel rule (px), in your elements.

- Liquid layout stretches and contracts based on the size of the users browser window.

    - This is done by using a percentage rule (%), inside your element.

- CSS frameworks is a tool to make life easier by providing the code for common tasks.

## Functions

- A function lets you group a series of statements together to perform a specific task.

- Functions also offer a way to store the steps needed to acheive a task. The script can then ask to perform all of those steps when they are required.

- When a function is asked to perform its task it is known as calling the function.

- When the function is expected to provide a response, the response is known as a return value.

- To create a function first give it a name then write the statements needed to acheive its task inside curly brackets. This is known as function declaration.
    - A function declaration creates a function that you can call later in your code.

- The location where you declare a variable will affect where it can be in the code. This is known as the variables scope.

## Pair Programming

- Pair programming is the practice of two developers sharing a single workstation to interactevly complete a coding task together. 

- Pair programming commonly involves two roles: _Driver_ and __Navigator__

    - The _Driver_ is the only one with their hands on the keeyboard and handling the mechanics of coding.
    - The __Navigator__ uses their words to guide the drivers without any direct input onto the computer.

- Coding is similar to foreign language classes; using listening, speaking, reading, and writing skills to help learn about it.

- The old saying "two heads are better than one" is true in this instance. Pair programming has many benifits such as:

    1. __Greater Efficiency.__

        - Takes slightly longer but produces higher quality output, or code
        - With two people it is easier to catch mistakes
    2. __Engaged Collaboration.__

        - The experiance can be more engaging and easier to focus on, like a workout buddy.
        - Can problem solve quicker with 2 people rather than being stuck on a problem for a while.
    3. __Learning from Fellow Students.__

        - Different people have different approaches to tackle a similar problem to reach the same solution.
        - Working with someone will expose you to different problem solving techniques that you can integrate into your code for an easier experiance.
    4. __Social Skills.__

        - Of course, working with someone else will help you develop better social skills.
        - Social skills are a valuable asset in a career in coding.
    5. __Job Interview Readiness.__

        - Mostly all coding jobs include working with a team so this should help with the interview process if they ask to pair program with a current employee in an interview
    6. __Work Environment Readiness.__

        - Many work enviorments already utilize pair programming so lets hit the ground running!



[<== BACK](README.md)