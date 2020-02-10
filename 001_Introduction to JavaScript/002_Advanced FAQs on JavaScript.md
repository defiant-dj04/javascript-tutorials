## What is ECMAScript?

- JavaScript came into the market for the first time in 1995, it was created by Netscape Communications Corporation and designed by Brendan Eich.

- ECMA stands for European Computer Manufacturer's Association.

- ECMAScript is a standardization given to JavaScript so that not every browser can manipulate it based on their needs.
  - **ECMAScript 1:** June 1997
  - **ECMAScript 5:** December 2009
  - **ECMAScript 6:** June 2015
  - **ECMAScript 7:** June 2016
  - **ECMAScript 8:** June 2017
  - **ECMAScript 9:** June 2018
  - **ECMAScript 10:** June 2019


## What is ECMAScript engine?

- A platform that executes source code written in a version of the ECMAScript language standard, for example JavaScript.

- Browsers use this to render JavaScript implementing Just-in-Time (JIT) compilations or variations of that idea.

- ECMAScript engine for different browsers:
  - **V8:** JavaScript engine used by Google Chrome, Node.js and V8.NET
  - **SpiderMonkey:** JavaScript engine used by Gecko applications, including Mozilla Firefox.
  - **Chakra:** JavaScript engine used by Microsoft Edge.
  - **Chakra (JScript 9):** JavaScript engine used by Internet Explorer.
  - **JavaScriptCore:** JavaScript engine used by Safari.
  - **Carakan:** JavaScript engine used by Opera web browser.
  - **Nashorn:** JavaScript engine used by Oracle Java Development Kit (JDK) since version 8.


## What is Babel?

- Babel is a JavaScript compiler, Babel is a toolchain that is mainly used to convert ECMAScript 2015+ code into a backwards compatible version of JavaScript to provide support in current and older browsers or environments.

- Babel is also known as a transpiler, one that converts source code written in one version to another version.
  - e.g. ECMAScript 6 Code (Source Code) ---> Babel ---> ECMAScript 5 Code (Source Code)


## How many ways we can attach our own JavaScript code to a HTML document?

- There are two ways:
  - Using internal / in-document JavaScript.
  - Using external JavaScript


## Where should we place the the JavaScript code in the HTML document?

- A JavaScript code can be placed anywhere in the HTML document. But, typically if the JavaScript code is having a lot of lines of code the best option is to place it at the bottom of the document (mostly, right above closing `</body>` tag), because as JavaScript is an interpreted language so if it is placed at the top then before even loading the page browser will take a lot of time to render the JavaScript code line by line delaying the loading time of the actual page.


## What is DOM?

- DOM stands for Document Object Model.

- ![DOM Image](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5a/DOM-model.svg/800px-DOM-model.svg.png)

- The DOM is an Object Model for XML or HTML document, which treats the document as a tree structure wherein each node is an object representing a part of the document.

- It defines the logical structure of documents and the way a document is accessed and manipulated (Properties, Methods and Events for all HTML elements).

- When a web page is loaded, the browser creates a Document Object Model of the page.

- With the HTML DOM, JavaScript can access and change all the elements of an HTML document.

- The HTML DOM is an API (Programming Interface) for JavaScript:
  - JavaScript can add/change/remove HTML elements
  - JavaScript can add/change/remove HTML attributes
  - JavaScript can add/change/remove CSS styles
  - JavaScript can react to HTML events
  - JavaScript can add/change/remove HTML events