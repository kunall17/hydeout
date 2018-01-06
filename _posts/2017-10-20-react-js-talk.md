---
layout: post
title: Talk on React js
comments: true
categories: blog
excerpt_separator:  <!--more-->
---


ReactJS basically is an open-source JavaScript library which is used for building user interfaces mostly for single page applications.

<!--more-->

**Why is ReactJS  gaining so much popularity?**
****
- Super easy to maintain (Javascript).
- Comparatively lesser lines of codes.
- React is extremely efficient.
- The brains behind Facebook are maintaining this project.
- Open source and a lot of contribution going on.
![](https://d2mxuefqeaa7sj.cloudfront.net/s_7C1DA87276F3B1AD8AE81C1BEAEBC25171A2BF424414E933FD9C2E066DBFF426_1508473379584_Screen+Shot+2017-10-20+at+9.52.27+AM.png)

----------

**Which language does it use?**

**JSX (**JavaScript XML) - It is the language which adds XML syntax to Javascript code.


- **Easier -** JSX offers a solid class system much like Java
- **Faster** - JSX performs optimization while compiling the source code to JavaScript.
- **Safer -** In contrast to JavaScript, JSX is statically-typed and mostly type-safe.


----------

**How does it work?**


- Integrating it with the html file and bundling of the js file
- Component structure
- How the state is managed
- Explain the rendering part

Example of JSX using [ECMAScript 2015](https://en.wikipedia.org/wiki/ECMAScript#6th_Edition_-_ECMAScript_2015) JavaScript syntax.


    import React from 'react';

    class App extends React.Component {
      constructor(props) {
        super(props);
        this.state = {
          name: "Some name"
        };
      }
       render() {
          return (
             <div>
                <Header name={this.state.name} />
             </div>
          );
       }
    }

    class Header extends React.Component {
       render() {
          return (
             <div>
                <h1>{this.props.name}</h1>
             </div>
          );
       }
    }
    export default App;


----------

 **A basic example**


    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="UTF-8" />
        <title>Hello World</title>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/react/15.4.2/react.js"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/react/15.4.2/react-dom.js"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/babel-standalone/6.21.1/babel.min.js"></script>
      </head>
      <body>
        <div id="myDiv">
          <!-- Component will render here -->
        </div>
        <script type="text/babel">
          class Greeting extends React.Component {
            render() {
              return (
                <h1>Hello world this is React JS</h1>
              );
            }
          }
          ReactDOM.render(<Greeting />, document.getElementById('myDiv'));
        </script>
      </body>
    </html>


----------

**Pros/Cons**


- **Its fully open source.**
- Easy to use , It allows developers to create fast user interfaces.
- React-JS is used by React Native internally.  
- It also uses the concept called Virtual DOM
![File:DOM-model.svg](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5a/DOM-model.svg/428px-DOM-model.svg.png)



- React.js uses a special syntax called JSX.
- Search engine friendly.
- **React** uses the least abstractions
- It is extremely easy to write UI test cases because the virtual DOM system implemented entirely in JS.
- An open-source library: constantly developing and open to contributions.

**Cons**


- Just a view library at its core
- The library itself is pretty large.
- There is a high dependency on third party libraries.
- Facebook recently changed the open source license recently, which caused a lot of problems, but they reverted it. [But now its MIT]


----------

**How react native is different from react**

React native is used for cross platform development for mobile applications like iOS, Android & even windows (with help of third party applications)


- React Native uses native APIs as a bridge to render components on mobile.
- React Native doesn’t use HTML.


----------

 **Who's using React/React native?**

![From left to right { Facebook,  Facebook ads manager, Instagram, F8 (Conference app by Facebook), Airbnb, Skype, Tesla, Walmart } ](https://d2mxuefqeaa7sj.cloudfront.net/s_7C1DA87276F3B1AD8AE81C1BEAEBC25171A2BF424414E933FD9C2E066DBFF426_1508412592925_Screen+Shot+2017-10-19+at+4.59.40+PM.png)


**{And conclude that React JS is safe to use and an awesome tool to replace web & native apps}**

----------
