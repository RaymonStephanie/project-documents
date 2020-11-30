Let's Get Started Coder!!
Fill the following Document
____________________________________________________

1. Which one of the following is an Imperative Language??
HTML
CSS
JavaScript(JS)
Answer:
Javascript/JS is a declarative language as it can control the flow of how the program works using statements.
____________________________________________________

2. Which one of the following is a Declarative Language??
HTML
CSS
Java Script

Answer:
HTML is a declarative language as it tells how a website should look, not the rendering of it in the browser. Other common examples include all markup and markdown languages.
____________________________________________________

3. Name two uses of a DIV tag??

Answer:
Most commonly used as flex box containers in css.
Used in websites where the developer does not prefer semantic markup to group elements / in websites where there are is a form in which we need to handle response and request, applying classes to all children( Easy application of classes).
____________________________________________________

4. What is the difference between relative positioning and absolute positioning in HTML?

Answer:
Relative positioning :
Relative positioning allows the use of the normal
``` css
  .container {
    display : flex;
    align-items : center;
    justify-content : center;
  }
  
  .item {
    text-align : center;
    position : relative;
    top : 50px;
    left : 50px;
  }
```

```html 
  <!DOCTYPE html>
    <html>
      <head>
        <link rel="stylesheet" href="./index.css">
      </head>
      <body>
        <div class="container">FlexBox Container!
          <button class="item">Hello, this is button which uses positioning.</button>
          <button class="item">Hello, this is button which uses positioning.</button>
        </div>
      </body>
    </html>
```
to position the current object. For example, if in a flex box container, in css, it’s difficult to position elements. We could use relative positioning to fix this problem. This allows us to position the current item using the normal alignment of the current item ie. diverted from the center aligned position.

Absolute positioning:
Absolute Positioning uses the position of a non-static element to position the current element ie. position the element anywhere on the page.
```css 
  .non-static {
    margin : 0 auto;
    color : cornflowerblue;
  }
  
  .absolute {
    position : absolute;
    left: 200px;
    top: 150px;
    color : cornflowerblue;
  }
```

```html 
  <!DOCTYPE html>
    <html>
      <head>
        <link rel="stylesheet" href="./index.css">
      </head>
      <body>
        <button class="non-static">Hello, this is button which uses non static positioning.</button>
        <button class="absolute">Hello, this is button which uses absolute positioning.</button>
      </body>
    </html>
```

5. What is the use of opacity in CSS??
Answer:
Opacity is a property used in css to style placeholders and text differently.
This can be applied to text to make it pop out or look dim.
This would come in handy when there is a button.
```css 
  button {
    color : rgba(0, 140, 255, 0.25);
    background-color : rgba(0, 140, 255, 0.25);
    border : 5px solid cornflowerblue;
  }
  
  button:hover {
    color : rgba(0, 140, 255, 1);
    background-color : rgba(0, 140, 255, 1);
    border : 5px solid cornflowerblue;
  }
```

```html
  <!DOCTYPE html>
    <html>
      <head>
        <link rel="stylesheet" href="./index.css">
      </head>
      <body>
        <button>Hover on me!</button>
      </body>
    </html>
```
____________________________________________________

6. Which is the programming language used in the React Native Framework??

Answer:
The programming language used in React Native is JSX.
JSX allows the use of "templates" or HTML&CSS (With slightly irritating syntax changes)
inside of Javascript code. Some good examples include VueJS, the react framework (Technically a library).
____________________________________________________

7. Which online editor are we using for creating our apps in React Native Framework??

Answer:
We are using the expo online editor which provides an online react-native IDE along with live preview accross devices.
This helps developers to build responsive apps with HTML, CSS, JS.
____________________________________________________

8. Write the steps to test your first designed app in the online editor on a mobile.

Answer:
Download the expo app on a phone.
Scan the QR Code given in "connect to device" option.
You have the output in your phone.
____________________________________________________

9. What is the use of the render function in React Native Framework??

Answer:
The render function tells the react-native framework that whatever is inside this is going to be a mix of HTML, CSS, JS **which is to be rendered**.
____________________________________________________


10. What is the use of return function  in React Native Framework??

Answer:
The return function returns the render function to the react native library to render all content as an app. Return is generally used to return a value when a function is called.
____________________________________________________

11. What are the various components in your first app that you designed??

Answer:
View, Button, Text were the components that I used to complete my first(not really, but with react native, yes) app.
____________________________________________________
****************************************************
