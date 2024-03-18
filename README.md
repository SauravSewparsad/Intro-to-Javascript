# Intro-to-Javascript

We have now completed HTML & CSS now we will be diving into Javascript. During my 3 year study at varsity college i have already leanrned javascript, but i could use a refresher.
We will be macking notes of all the sections here and be doing week 0 - week 1 today.

---------------------------------------------------------------------

# Week 0 
Overview:
-JavaScript is a programming language used to make web pages interactive. It is what gives a page life - the interactive elements and animations that engage the user. If you've ever used a search box on a home page, checked a live sports score on a news site, or watch a video, it has likely been produced by JavaScript.

-JavaScript is one of the three pillars of web development - the other two being HTML and CSS. JavaScript was purposely designed to integrate into HTML. All major web browsers support JavaScript, though most give users the option of disabling support for it.

Learning Journey:
- As JS is a higher-level programming language and because the basics of programming are important skills to have, we will spend Week 1 and Week 2 purely on understanding and familiarizing ourselves with JavaScript. In subsequent weeks, we will learn more advanced classes of JavaScript that will help us develop the front-end (ReactJS) and the back-end (ExpressJS) of websites.
- we will look at how 4 modules where week 1-2 will be an intro to javascript, week 3- 5 will be font-end and week 6-8 will be on Expressjs.

--------------------------------------------------------------------
# Week 1 Basic syntax
Day 1: JavaScript 1: Variables, Operators & Assignments

Javascript Basics
- Javascript gives the website functionalality and makes certain buttons work. If javascript was disabled then the web or any mobile app functions would not work properly and people would see a bunch of funny
  things happen.
- Variable is to define a statment and assign the called variable a function.
- To increment operator adds one to the operand and returns a value. To do that you add x++ ( returns value before incrementing) or ++x (returns value after incrementing).
- To decrement operator u need to subtract the operand and return a value. To do that you subtract x--(retuns value before decrement) or --x (returns a value after a decrement).

Variables:
- JavaScript also defines two trivial data types, null and undefined, each of which defines only a single value. In addition to these primitive data types, JavaScript supports a composite data type known as an object. We will cover objects in detail in a separate chapter.
- JavaScript does not make a distinction between integer values and floating-point values. All numbers in JavaScript are represented as floating-point values. JavaScript represents numbers using the 64-bit floating-point format defined by the IEEE 754 standard.
- Like many other programming languages, JavaScript has variables. Variables can be thought of as named containers. You can place data into these containers and then refer to the data simply by naming the container.
-----------------------------------------------------

The day 1 of java is over and i have completed all exercises.

Day 2: Today we begin with day 2 of javascript and we are learning strings and arrays today. Honestly i forgot arrays, because i hardly used them during my studies but they are really important for toring the data to the device, but the down side it only saves for that session unless u hard code the data in. In the first 2 tabs of the lesson they introduced us to what we will be learning and made us watch videos on how strings and arrays work.

Strings:
- A string is a sequence of one or more characters that may consist of letters, numbers, or symbols. Strings in JavaScript are primitive data types and immutable, which means they are unchanging.
- As strings are the way we display and work with text, and text is our main way of communicating and understanding through computers, strings are one of the most fundamental concepts of programming to be familiar with.

I was then given an activity about strings and to take screenshots and submit them. I have done that and now will be going into the array section. The strings activity was to easy and activity 2 with the arrays was really benefitial, learning alot from it. Day 2 is now complete and i will continue with my landing and webpage project for friday.

Day 3: Today i begin javascript day 3, i will be leanring functions today, once i am done with the functions i am going to continue with my landing page.
Notes:
- Always put ur script at the end of the body tag and never anywhere above, this is if you are running the script in an html file. You can create a seperate javascript file and link it to the html like how you would with CSS.
- You can have multiple javascript file and implent them in the html file but it will run the functions in order of the javascript files added to the html.
- Functions can be called more then once and they take argumants.
- Arguments make code reusable.

Functions:
- A function is a group of reusable code which can be called anywhere in your program. This eliminates the need of writing the same code again and again. It helps programmers in writing modular codes. Functions allow a programmer to divide a big program into a number of small and manageable functions.
- Before we use a function, we need to define it. The most common way to define a function in JavaScript is by using the function keyword, followed by a unique function name, a list of parameters (that might be empty), and a statement block surrounded by curly braces.

Day 3 of javascript is now complete and i will now be focusing on the landing page.

Day 4 of javascript has now begun and i am doing this chapter early so i can focus on my landing page and power point. In day 4 i will be learning booleans.

Booleans:
- Booleans are values that can be only one of two things: true or false.
- Anything “on” or “off,” “yes” or “no,” or temporary is a usually good fit for a boolean. It’s useful to store booleans in variables to keep track of their values and change them over time.
- if statements are used to make decisions in code. The keyword if tells JavaScript to execute the code in the curly braces under certain conditions, defined in the parentheses. These conditions are known as Boolean conditions and they may only be true or false.
- The most basic operator is the equality operator ==. The equality operator compares two values and returns true if they're equivalent or false if they are not. Note that equality is different from assignment (=), which assigns the value on the right of the operator to a variable on the left.

day 4 is now complete and i will now continue with my landing page.
Day 5 of Javascript. Today i will be doing a sprint for day 5, reviwing all the activities and things i have leaned in the past 5 days.

-----------------------------------------------------------------------------------

#Week 2: Web Design

Day 1: Introduction to HTML, CSS and JavaScript1
Welcome to week 2! This week you will be working again on the Website that you designed in Module 1 and Module 2. In module 1, you created a Website using only HTML and CSS. Using HTML, you learnt that rather than using a programming language to perform functions, HTML enables you to use tags to identify different types of content and the purposes they each serve to the webpage. Each type of content on the page is "wrapped" in, or surrounded by, HTML tags. We even learned CSS, but now you will then begin to implement Javascript into your web development.
At the end of the week you are expected to master the learning Introduction to HTML, CSS and JavaScript - In this section you will learn how to combine JavaScript with HTML and CSS.

Type Conversion:
- String conversion happens when we need the string form of a value.
- For example, alert(value) does it to show the value.
- Numeric Conversion: Numeric conversion happens in mathematical functions and expressions automatically.
- For example, when division / is applied to non-numbers
- Explicit conversion is usually required when we read a value from a string-based source like a text form but expect a number to be entered. If the string is not a valid number, the result of such a conversion is NaN.
- Boolean Conversion: Boolean conversion is the simplest one. It happens in logical operations (later we’ll meet condition tests and other similar things) but can also be performed explicitly with a call to Boolean(value).
- The conversion rule:
Values that are intuitively “empty”, like 0, an empty string, null, undefined, and NaN, become false.  
Other values become true.
- Formatting Numbers:
JavaScript Number Format: Main Tips:
- Several JavaScript number format methods are offered with this language that you can use to manipulate numeric values.  
- Each number method returns a new value instead of changing the one being used for the method.  
- Every JavaScript number format method may be used on any type of number, including literals, variables, expressions.
- Methods Used For Numbers  
There are a few JavaScript number format methods to keep in mind if you want to manipulate and change numeric values
- toString():
toString() turns the numeric value into a string (a sequence of characters). It can be used with literals, variables or expressions.
- toExponential()  
toExponential() turns numbers into strings as well, but in addition to that, the number that is returned is also rounded and written with exponential notation.
- toFixed()  
The JavaScript toFixed() also turns the number into a string, but with a specific amount of decimals this time. The number of decimals should be specified in the parentheses after the method's name.
- toPrecision():  
The toPrecision() also turns the number into a string, but with a specified length. The length is specified inside the parentheses after the method's name. It is quite similar to JavaScript toFixed() method but counts all numbers, not only decimals.
-Converting Variables to Numbers:
If you find yourself in need to turn a variable into a number, these are the three methods you can use: 
Number()  
parseInt()  
parseFloat()
- Number()  
Number() method is widely used to convert JavaScript variables into numbers. Although, if a number cannot be returned, the program will return NaN (Not a Number).
- parseInt()  
If you want to create a JavaScript integer, you should use parseInt(). It works by parsing a string and then returning the number. Spaces may be present in the string, but only the first number will be returned.
- parseFloat() Method  
parseFloat() method works by parsing a string and then returning a floating point number. Spaces may be present in the string, but only the first number will be returned.
- valueOf()  
valueOf() is used to return a number as a number. When looking at JavaScript code, numbers may be primitive values (typeOf = number) or objects (typeOf = object). The method called valueOf() is used internally to turn number objects into primitive values.

The Document Object Model and JavaScript Syntax
- The Document Object Model is an Application Programming Interface (API) for HTML and XML documents. It does two things for web developers: 
Provides a structural representation of the document
Defines the way that that structure is to be accessed from script.

- Object 
a JavaScript object is any scriptable HTML element, that is, any HTML element within a document that may be accessed through the JavaScript language. Although the browser window is not an HTML element, it too is a scriptable object.
The following are some of the JavaScript objects:
window
document
form
image

- Property
Objects have properties, which you can think of as characteristics of an object. A JavaScript property has a similar relationship to the object it belongs to that an HTML tag attribute has to the tag that contains it. For example, the JavaScript "value" property is to a text field object as the HTML "width" attribute is to a table tag.

- Method
Methods are actions that can be applied directly to objects. Within a web page, methods cause a boring old HTML document to react to the end user. This results in a meaningful experience for the end user which would otherwise be completely one-sided.
- Core APIs in the DOM
document and window objects are the objects whose interfaces you generally use most often in DOM programming. In simple terms, the window object represents something like the browser, and the document object is the root of the document itself. Element inherits from the generic Node interface, and together these two interfaces provide many of the methods and properties you use on individual elements.

Day 1 of week 2 is now complete and i will then continue with improving my portfolio.

Day 2: Today we will be learnning Javascript API. To my knowledge api is data from an external source like a bird website that hold data on bird. So if we then decide to make a bird app we would copy a link and use that link to access the data on our app, that link is called an api.

Additional Javascript tags:
- Calling one function from another function
Code inside a function behaves just like code anywhere else. This means you can call one function from inside another function. This allows you to "nest" functions so that you can create separate functions, which each perform a specific task, and then run them together as a complete process, one right after the other.
- Creating objects with user-defined functions
JavaScript is based on objects: the window is an object, links are objects, forms are objects, even Netscape itself (or other browser) is an object. Using objects can help make programming easier and more streamlined. You can extend the use of objects in JavaScript by making your own. The process uses functions in a slightly modified way. In fact, you'll be surprised how easy it is to make your own JavaScript objects.
 Making a new object entails two steps:
+ Define the object in a user-defined function.
+ Use the new keyword to create (or instantiate) the object with a call to the object function.
- Defining new properties to already-made objects
After an object has been created you can assign a value to it. But instead of just assigning a value to the object itself, you should define a new property for the object, and assign a value to the property.
+ myobject is the name of the user-defined object.
+ property is the name of the property you want to create.
+ value is the value you want to assign.

- Defining properties when you create the object
Another method of defining properties for objects is to include the property names in the object function. You can use this technique to simultaneously create a new object and define the property values. All it takes is a few more lines of code in the object function.
- Operators
  JavaScript has the following types of operators. This section describes the operators and contains information about operator precedence.
  - Assignment Operators
Return value and chaining: 
Like most expressions, assignments like x = y have a return value. It can be retrieved by e.g. assigning the expression or logging it: 
An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = y assigns the value of y to x.

- Destructuring
For more complex assignments, the destructuring assignment syntax is a JavaScript expression that makes it possible to extract data from arrays or objects using a syntax that mirrors the construction of array and object literals.
- Comparison Operators 
A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behaviour generally results in comparing the operands numerically. The sole exceptions to type conversion within comparisons involve the === and !== operators, which perform strict equality and inequality comparisons. These operators do not attempt to convert the operands to compatible types before checking equality.
- Arithmetic operators
An arithmetic operator takes numerical values (either literals or variables) as their operands and returns a single numerical value. The standard arithmetic operators are addition (+), subtraction (-), multiplication (*), and division (/). These operators work as they do in most other programming languages when used with floating point numbers (in particular, note that division by zero produces Infinity).
- Bitwise Operators
A bitwise operator treats their operands as a set of 32 bits (zeros and ones), rather than as decimal, hexadecimal, or octal numbers. For example, the decimal number nine has a binary representation of 1001. Bitwise operators perform their operations on such binary representations, but they return standard JavaScript numerical values.
- Bitwise Logical Operators
Conceptually, the bitwise logical operators work as follows:
+ The operands are converted to thirty-two-bit integers and expressed by a series of bits (zeros and ones). Numbers with more than 32 bits get their most significant bits discarded.
+ Each bit in the first operand is paired with the corresponding bit in the second operand: first bit to first bit, second bit to second bit, and so on.
+ The operator is applied to each pair of bits, and the result is constructed bitwise. For example, the binary representation of nine is 1001, and the binary representation of fifteen is 1111. So, when the bitwise operators are applied to these values

- Bitwise Shift Operators
The bitwise shift operators take two operands: the first is a quantity to be shifted, and the second specifies the number of bit positions by which the first operand is to be shifted. The direction of the shift operation is controlled by the operator used.

Shift operators convert their operands to thirty-two-bit integers and return a result of the same type as the left operand.

- Logical Operators
Logical operators are typically used with Boolean (logical) values; when they are, they return a Boolean value. However, the && and || operators return the value of one of the specified operands, so if these operators are used with non-Boolean values, they may return a non-Boolean value. The logical operators are described in the following table.

- Short-circuit evaluation
As logical expressions are evaluated left to right, they are tested for possible "short-circuit" evaluation using the following rules:

+ false && anything is short-circuit evaluated to false.
+ true || anything is short-circuit evaluated to true.
The rules of logic guarantee that these evaluations are always correct. Note that the anything part of the above expressions is not evaluated, so any side effects of doing so do not take effect.
Note that for the second case, in modern code you can use the new Nullish coalescing operator (??) that works like ||, but it only returns the second expression, when the first one is "nullish", i.e. null or undefined. It is thus the better alternative to provide defaults, when values like '' or 0 are valid values for the first expression, too.

- String Operators
In addition to the comparison operators, which can be used on string values, the concatenation operator (+) concatenates two string values together, returning another string that is the union of the two operand strings.
- Conditional (ternary) Operator 
The conditional operator is the only JavaScript operator that takes three operands. The operator can have one of two values based on a condition.

- Comma Operator 
The comma operator (,) simply evaluates both of its operands and returns the value of the last operand. This operator is primarily used inside a for loop, to allow multiple variables to be updated each time through the loop. It is regarded bad style to use it elsewhere, when it is not necessary. Often two separate statements can and should be used instead.

- Operator Precedence 
The precedence of operators determines the order they are applied when evaluating an expression. You can override operator precedence by using parentheses.

The Document object Model:
Event bubbling:
- Bubbling is what the event itself does.
- The event starts at the element that triggered it (Clicking 1. Element button, An Event Listener would be attached to each element). Then, it bubbles up to each of it’s parent elements until it reaches the document. Any listeners on any of those parent elements would get triggered as it bubbles up. Causing all the events to occur on the page possibly slowing down your application.
- Event proprgation is a line of code where the system will read the api. That e.stopPropagation() halts this “bubbling” of events “up” through the DOM. We stop all the events from the parents occurring. 
- Event Delegation is a technique for listening to event where you delegate a parent element as the listener for all the events that happen inside it. 
So instead of adding Event Listeners to each Button you would just add and event Listener to the parent Element and target the child element.

Regular Expressions:
- A regular expression is a sequence of characters that forms a search pattern. The search pattern can be used for text search and text replace operations.
- Example:
var patt = /w3schools/i; 
Example explained: 
/w3schools/i  is a regular expression. 
w3schools  is a pattern (to be used in a search). 
i  is a modifier (modifies the search to be case-insensitive).

Day 2 is now complete and i will do the flex box that was given to us.

Day 3: Today i will begin with day 3 which will teach us Javascript forms.

JavaScript Methods and “this” Keyword:
- In JavaScript, objects can also contain functions.
- Accessing Object Methods allow you to access an object method using a dot notation. You can access a method by calling an objectName and a key for that method along with (). And you can access property only by calling an objectName and a key.
- JavaScript Built-In Methods has many built-in methods
- Adding a Method to a JavaScript Object is possible with the proper syntax.
- JavaScript this Keyword gives access to property of an object from within a method of the same object, you need to use the this keyword.

Javascript switch statement:
- The switch statement is used to perform different actions based on different conditions.
- Use the switch statement to select one of many code blocks to be executed.
- The switch expression is evaluated once. The value of the expression is compared with the values of each case. If there is a match, the associated block of code is executed. If there is no match, the default code block is executed.
- The break Keyword:
When JavaScript reaches a break keyword, it breaks out of the switch block. This will stop the execution of inside the block. It is not necessary to break the last case in a switch block. The block breaks (ends) there anyway
- The default Keyword 
The default keyword specifies the code to run if there is no case match. If default is not the last case in the switch block, remember to end the default case with a break.
- Common Code Blocks: 
Sometimes you will want different switch cases to use the same code.
- If multiple cases matches a case value, the first case is selected. If no matching cases are found, the program continues to the default label. If no default label is found, the program continues to the statement(s) after the switch.
- Strict Comparison: 
Switch cases use strict comparison (===). 
The values must be of the same type to match. 
A strict comparison can only be true if the operands are of the same type.

Day 3 is now complete and i will begin preparing for the presentaton tomorrow.

Day 4: Today for day 4 of Javascript we are going to revisit most of the new code we have learned this week. I did a few of the excersies that was given to me in the day 4 moduale. After doing the activites i have then completed day 4 of javascript.

---------------------------------------------------------------------------------

#Week 3

Day 1: Today i will be going through week 3 of javascript and today will be going through all 5 days as we will only be working for 3 days this week and alot of things need to be done. 
We will be learning events today for day 1.

Strings Operations
- Strings can be created as primitives, from string literals, or as objects, using the String() constructor
- String primitives and string objects can be used interchangeably in most situations. See "String primitives and String objects" below. String literals can be specified using single or double quotes, which are treated identically, or using the backtick character ` . This last form specifies a template literal: with this form you can interpolate expressions
- There are 2 ways to access string individualy. The first is the  charAt() method and the second is to treat the string like an array object.
- When using bracket notation for character access, attempting to delete or assign a value to these properties will not succeed. The properties involved are neither writable nor configurable.
- A similar result can be achieved using the localeCompare() method inherited by String instances.  Note that a == b compares the strings in a and b for being equal in the usual case-sensitive way. If you wish to compare without regard to upper or lower case characters.

On-Event handlers:
- The on-event handlers are a group of properties offered by DOM elements to help manage how that element reacts to events. Elements can be interactive or non-interactive. Events are actions like being clicked, detecting pressed keys, getting focus, etc. The on-event handler is usually named according to the event it is designed to react to, such as onclick, onkeypress, onfocus, etc.
- You can specify an on<...> event handler for a particular event (such as click) for a given object in different ways:
+ Using an HTML attribute named on{eventtype} on an element, for example:
  "button onclick="return handleClick(event)"
+ Or by setting the corresponding property from JavaScript, for example:
  document.getElementById("mybutton").onclick = function(event) { ... }.

  - Event handlers are called automatically.
  - event - for all event handlers, except onerror.
  - event, source, lineno, colno, and error for the onerror event handler.

  Event handler rules:
  - onabort, Invoked when an event has been aborted. For example, the browser stops fetching media data before it is completely downloaded.
  - oncancel, cancel event handler.
  - oncanplay, Invoked when the browser/user agent can start playing media, but hasn't yet, due to buffering. In other words, if playback were to begin now, it wouldn't play right to the end (due to the
    current playback rate) - it would need to pause during playback in order to load the rest of the media.
  - oncanplaythrough, The browser/user agent estimates that if playback were to begin now, the media resource could be rendered at the current playback rate all the way to its end without having to stop for further buffering.
  - onchange, User has changed the object, then attempts to leave that field (i.e. clicks elsewhere).
  - onclick, Invoked when the user clicked on the object.
  - oncuechange, cuechange event handler.
  - ondblclick, Invoked when the user clicked twice on the object.
  - ondurationchange, Invoked when the length of the media is changed (i.e. the duration attribute has just been updated).
  - onemptied, Invoked when a media resource element suddenly becomes empty (for example, due to a network error).
  - onended, Invoked when the media has reached the end.
  - oninput, input event handler.
  - oninvalid, invalid event handler.
  - onkeydown, Invoked when a key was pressed over an element.
  - onkeypress, Invoked when a key was pressed over an element then released.
  - onkeyup, Invoked when a key was released over an element.
  - onloadeddata, Invoked when the browser/user agent can render the media data at the current playback position for the first time.
  - onloadedmetadata, Invoked when the browser/user agent has just determined the duration and dimensions of the media resource.
  - onloadstart, Invoked when the browser/user agent has started loading the media resource.
  - onmousedown, The cursor moved over the object and the mouse/pointing device was pressed down.
  - onmouseenter, The cursor enters the outer element (not the inner element). Therefore, does not fire again if the cursor enters a descendant of this element.
  - onmouseleave, The cursor leaves the element.
  - onmousemove, The cursor moved while hovering over an object.
  - onmouseout, The cursor moved off the object
  - onmouseover, The cursor moved over the object (i.e. user hovers the mouse over the object).
  - onmouseup, The mouse/pointing device was released after being pressed down.
  - onmousewheel, Invoked when the mouse wheel is being rotated.
  - onpause, Invoked when the media resource has been paused.
  - onplay, Invoked when the media resource starts playback.
  - onplaying, Playback has begun.
  - onprogress, The browser/user agent is fetching media data.
  - onratechange, Invoked when the playback rate has changed (i.e. either the defaultPlaybackRate or the playbackRate has just been updated).
  - onreset, reset event handler.
  - onseeked, Invoked when the seeking IDL attribute changed to false (i.e. the seeking attribute is no longer true)
  - onseeking, Invoked when the seeking IDL attribute changed to true and the seek operation is taking long enough that the user agent has time to fire the event.
  - onselect, Invoked when some or all of the contents of an object is selected. For example, the user selected some text within a text field.
  - onshow, show event handler.
  - onstalled, Invoked when the browser/user agent is trying to fetch media data but the data has stalled (i.e. the data has stopped coming).
  - onsubmit, User submitted a form.
  - onsuspend, The browser/user agent is (intentionally) not currently fetching media data, but has not yet downloaded the entire media resource (i.e. it has suspended the download).
  - ontimeupdate, Invoked when the media's current playback position changed.
  - ontoggle, Invoked when the details element is opened or closed.
  - onvolumechange, Invoked when either the volume attribute or the muted attribute has changed.
  - onwaiting, The next frame of the media is not yet available (but the browser/user agent expects it to become available).

  Dynamic HTML:
  - HTML objects can be changed in two ways:
  + Changing the class of the object - thereby changing the style of the object
  + Using the style property of the object to change the style.
  - And JavaScript functions may be designed in various different ways, for example:
  + An object is referenced directly in the JavaScript function using the id value. This function can then be used to change the style of only that particular object.
+ An object id being passed as an argument to the JavaScript function, so that the style of any object may be changed.
+ An object may be accessed by using the event to determine the object in which the event occurred.

Data Object:
- The Date object is a built-in object in JavaScript that stores the date and time. It provides a number of built-in methods for formatting and managing that data.
- By default, a new Date instance without arguments provided creates an object corresponding to the current date and time. This will be created according to the current computer’s system settings.
- Epoch time, also referred to as zero time, is represented by the date string 01 January, 1970 00:00:00 Universal Time (UTC), and by the 0 timestamp. We can test this in the browser by creating a new variable and assigning to it a new Date instance based on a timestamp of 0.
- Epoch time was chosen as a standard for computers to measure time by in earlier days of programming, and it is the method that JavaScript uses.

Keyboard Events:
- The Keydown Event (onkeydown), The keydown event occurs when the user presses down a key on the keyboard. You can handle the keydown event with the onkeydown event handler. The following example will show you an alert message when the keydown event occurs.
- The Keyup Event (onkeyup), The keyup event occurs when the user releases a key on the keyboard. You can handle the keyup event with the onkeyup event handler. The following example will show you an alert message when the keyup event occurs.
- The Keypress Event (onkeypress), The keypress event occurs when a user presses down a key on the keyboard that has a character value associated with it. For example, keys like Ctrl, Shift, Alt, Esc, Arrow keys, etc. will not generate a keypress event, but will generate a keydown and keyup event.

Form Events:
- The Focus Event (onfocus), The focus event occurs when the user gives focus to an element on a web page. You can handle the focus event with the onfocus event handler.
- The Blur Event (onblur), The blur event occurs when the user takes the focus away from a form element or a window. You can handle the blur event with the onblur event handler.
- The Change Event (onchange), The change event occurs when a user changes the value of a form element. You can handle the change event with the onchange event handler.
- The Submit Event (onsubmit), The submit event only occurs when the user submits a form on a web page. You can handle the submit event with the onsubmit event handler.

Document/Window Event:
- The Load Event (onload), The load event occurs when a web page has finished loading in the web browser. You can handle the load event with the onload event handler.
- The Unload Event (onunload), The unload event occurs when a user leaves the current web page. You can handle the unload event with the onunload event handler.
- The Resize Event (onresize), The resize event occurs when a user resizes the browser window. The resize event also occurs in situations when the browser window is minimized or maximized. You can handle the resize event with the onresize event handler.
