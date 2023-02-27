# ID Developmental Blog

## What I learnt through the weeks:

### Week 1

- Web development consists of 3 core pillars which include HTML, CSS and JS

_HTML_

- The basics of HTML, such as the different tags and how it works
- For example, the embedding of youtube link using iFrames
- Used tables to format layout

_CSS_

- The basics of CSS to change background color, font style etc.

_What is a good website_

- A good website must be and have well-designed, functional, easy to use, optimized for mobile, fresh and quality content, readily accessible contact and location and clear call to action.

### Week 2

_CSS_

- Sematic CSS is to give meaning to the code
- header, nav, article, section and more tags can be used
- header tag can be used to group the top of the webpage together, which icludes navigation and logos etc.
- article tag can be used for a particular content in a webpage
- The rules and best practices of CSS
- The different methods to introduce CSS into HTML
- How to "call" an element you want to add CSS to. ID or Classes can be used.

### Week 3

_Forms_

- How to create forms using form tag
- The different types of input that can be used
- Labels are needed to aid the visually impaired
- Validation of forms, for exmaple, whether a field is required
- button tag to submit a form

_CSS_

- Identifying Descendant elements so that descendant selector can be used
- The best practice is a maximum of 3 levels when using descendant selectors
- To give the same CSS to multiple elements, a "," can be used
- Which lines of codes will take precedence, for example, ID selectors have priority and are performed before class selectors because they are more specific.
- @media is used to modify CSS based on the device type and viewport size
- How and when to use relative, absolute and fixed positioning
- Using Z-index gives an element in the webpage a 3-D look
- Flexbox allows flexible layouts, which is useful for reasons such as changing from desktop to mobile view.
- Items in flexbox containers can be arranged differently using properties
- Flexbox properties include: flex-direction, flex-wrap, flex-flow, justify-content, align-items and align-content

_Wireframe_

- It is used to quickly generate ideas, show content hierarchy and establish key functionality
- Static wireframes are considered low-fidelity
- Creating high-fidelity wireframes can help stakeholders have a better visualisation of the final webpage design and funtionality.

### Week 4

_CSS_

- Create responsive images using flexbox so that the images can be auto-resized depending on screen size and device

_GitHub_

- Why github is so important in the IT world. For example, companies can check what you do and your salary will be determined based on that.
- How to create repositories and clone it into VSCode
- How to add-on/ edit/ delete work and save those changes before commiting and pushing back into github

### Week 5/6

_JS_

- Variable names need to be meaningful and unique
- let can be updated but not re-declared
- const cannot be updated or re-declared
- console.log can help inform developers what a code is doing. For example, you will be alerted if there is an issue
- There are 3 main data types: numbers, strings and booleans
- Template literals allows an expression to be inserted into string texts, making the code more readable
- Syntaxing of For loops work is like C#: for (let i = 0; i < 10; i++){}
- Arrays are the "lists" of JS
- There are 2 types of objects: Literal and Function-based
- DOM aids JS in creating dynamic HTML
- Elements can be accessed by using methods such as querySelectorAll(), getElementById() and parentNode

### Week 7

_Event Listeners_

- There are different types of events: UI Events, Keyboard Events, Mouse Events, Focus Events and Form Events
- A funtion will be triggered when an event happens. For example: element.addEventListener('blur', function(){checkUsername(5);}, false);

_Forms_

- Form validation prevents user from entering invalid inputs
- There are 2 layers to form validation: Client and server
- The input types can also include checkbox, radio and dropdown

_JSON Local Storage_

- Local storage allows all open windows and tabs to access the data, as well as store when tab is closed
- In order for security protection, browsers only allows data to be accessed by other pages in the same origin
- Protocol, subdomain, domain and port must all match
- To access storage API, setters/getters or dot notation can be used.
- JSON data consists of {key: value}
- Keys should be placed in double quotes("")
- Values can be a string, number, boolean, array, object or null
- Convert a JavaScript object to a string: JSON.stringify();
- Convert a string to a JavaScript object: JSON.parse();
- To clear or remove storage, localStorage.clear(); or localStorage.removeItem(item key); should be used respectively
- Storage has limitations and try statements can be used when quota exceeds

### Week 8

_JQuery_

- Scripts should be places before the closing body tag as the DOM has already loaded by the time the script is executed
- Makes JS a lot less tedious and time-saving as compared to Vanilla JS
- Multiple selectors can be used by using a comma to separate different search criteria $("li, p")
- $(document).ready() should be used to ensure all HTML elements must be loaded and "safe" before manipulating them
- DOM Traversal can be used after selecting an element. There are different methods including .prev(), .next(), .parent().prev() etc.
- Selector will affect all elements when a modification is made if it returns more than 1 element

_API_

- AJAX is used for loading data into part of a page without having to refresh the entire page
- User does not have to wait for the entire page to load if only a portion of the page is being updated
- Browser can request some data from a server and once that data has been requested while being able to continue loading the rest of the page
- API is able to give a reply with a structured response instead of simply reading a webpage like a human does
- POSTMAN is a tool that makes API development faster, easier and better
- POSTMAN is also an intuitive user interface to send requests, save responses, add tests, and create workflows
- fetch() method starts the process of fetching a resource from a server

### Week 9

_Bootstrap_

- Makes responsive development easier
- No need to build CSS from scratch since Bootstrap provides a collection of syntax for template designs

### Week 12

_NoSQL_

- A mechanism for storage and retrieval of unstructured data
- Has no specific query language, no or very few relationships but has data stored in the format of collections and documents
- Works better for large, unstructured datasets

_RestDB_

- Online NoSQL database
- POSTMAN can be used for testing

### Week 13

_Best Practises_

- Commit messages need to tell readers what was done or changed. They should be meaningful instead of having messages like "final update"
- Files need to be organised and have proper naming conventions. For example, all images/pictures should be grouped together into a folder called "img"

### Week 14

_Lottie Animation_

- JSON-based animation file format
- Perform animations and allow additional interactivity
- Lottie file is significantly smaller than a PNG file or GIF, making the download speed a lot faster
- Free LottieFIles or ready SVG resources can be used to save time since you do not need to create one from scratch
- In order to insert a LottieFile into HTML, you need to copy and paste the generated code of a design from the Lottie website
- JS will be used to determine when you want the animation to be played
- How to convert SVG to Lottie
- How to modify Lottie animations using Lottie editor
