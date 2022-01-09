# SNOW-Angular-Intro

- This is not the version of Angular( Angular) that ServiceNow Uses (AngularJS).
- It is still good to learn and create Apps with. 
- I will post another repositor for AngularJS.

## History of Angular
- Angular is a TypeScript-based open-source framework used to develop dynamic web applications.
- Angular is a Single Page Application (SPA) Framework. An SPA is a web application that fits on a single page. 
- All our code (JavaScript , HTML , CSS ) is retrieved with a single page load. Navigation between pages is performed without refreshing the whole page.

## Single Page Application
- A Single Page Application (SPA) is a web application that fits on a single page in the browser. 
- All our JavaScript, HTML, CSS code retrieved by the browser with a single page load. 
- Navigation between pages performed without refreshing the whole page. 
- SPA uses AJAX and HTML5 to build responsive web applications.
- Examples of single-page apps - Gmail, Google Maps, Facebook, Twitter, Trello, etc.,

## Advantages of SPAs
- Fast and responsive - SPAs update only the required content instead of the entire page for each request to the server. The HTML/CSS/Scripts are only loaded once throughout the lifespan of an application. Only data is transmitted back and forth. This significantly improves the website’s speed.
- Caching capabilities - SPA sends a request to the server and caches all received data locally. Then it can reuse this data and work even offline. If a user has poor connectivity, local data can be synchronized with the server when the connection allows.
- SPA provides a pleasant user experience on desktops as well as on mobile phones, since it only changes the content and not the page.

## Disadvantages of SPAs
- Doesn’t Perform Well With SEO (Search engine optimization).
- Security - SPAs are less secure towards Cross-site scripting (XSS) attacks.
- While overall performance is better, more data is frontloaded which can make the first page load a little slower
-Frameworks like AngularJS, Angular, Ember.js, ExtJS, Knockout.js, Meteor.js, React and Vue.js uses SPA principles to create a web application.

## Features of Angular
### CROSS PLATFORM
- Progressive Web Apps
- Use modern web platform capabilities to deliver app-like experiences. High performance, offline, and zero-step installation.
- Native
- Build native mobile apps with strategies from Cordova, Ionic, or NativeScript.
- Desktop
- Create desktop-installed apps across Mac, Windows, and Linux using the same Angular methods you've learned for the web plus the ability to access native OS APIs.

### SPEED AND PERFORMANCE
Code Generation
Angular turns your templates into code that's highly optimized for today's JavaScript virtual machines, giving you all the benefits of hand-written code with the productivity of a framework.
Universal
Serve the first view of your application on Node.js®, .NET, PHP, and other servers for near-instant rendering in just HTML and CSS. Also paves the way for sites that optimize for SEO.
Code Splitting
Angular apps load quickly with the new Component Router, which delivers automatic code-splitting so users only load code required to render the view they request.

### PRODUCTIVITY
Templates
Quickly create UI views with simple and powerful template syntax.
Angular CLI
Command line tools: start building fast, add components and tests, then instantly deploy.
IDEs
Get intelligent code completion, instant errors, and other feedback in popular editors and IDEs.

### FULL DEVELOPMENT STORY
Testing
With Karma for unit tests, you can know if you've broken things every time you save. And Protractor makes your scenario tests run faster and in a stable manner.
Animation
Create high-performance, complex choreographies and animation timelines with very little code through Angular's intuitive API.
Accessibility
Create accessible applications with ARIA-enabled components, developer guides, and built-in a11y test infrastructure.

## Angular versions
- AngularJS or Angular 1 - October 20, 2010 
- Angular 2 - September 14, 2016 
- Angular 4 - March 23, 2017 
- Angular 5 - November 1, 2017 
- Angular 6 - May 4th, 2018 
- Angular 7 - October 18, 2018 
- Angular 8 - May 28, 2019 
- Angular 9 - February 6, 2020
- Angular is commonly referred to as Angular 2+ or by one of the above versions, to distance the modern framework from the original AngularJS.

![image](https://user-images.githubusercontent.com/12488769/148702887-019be7eb-4c85-4fdb-aeee-d65de58b1de0.png)

## AngularJS vs Angular2+ ( or Angular)
![image](https://user-images.githubusercontent.com/12488769/148702907-8a184802-ed1d-415d-aa0e-f1efcbbbdbd3.png)

## Angular
- Angular uses the TypeScript language, which has features like :
- Static Typing
- Object-Oriented Programming based on classes
- Support for reactive programming using RxJS

## Building Blocks of Angular
The main building blocks of Angular are modules, components, templates, metadata, data binding, directives, services, and dependency injection. 
![image](https://user-images.githubusercontent.com/12488769/148702957-fee50348-d916-48f3-a15e-e696ed37da80.png)

## Node.js
- Node.js is an open-source, cross-platform run-time environment built on Chrome's V8 JavaScript engine.
- Node.js is used to execute JavaScript code outside of a web browser. 
- It provides a library of various JavaScript modules, which simplifies the development of web applications.
- Global companies like Netflix, Facebook, Walmart Linkedin, Uber, etc., use Node.js for building their applications. 
- It has helped companies create various applications like social media apps, video and text chat engines, real-time tracking apps, online games, and collaboration tools

## npm -  Node package manager
- npm is a package manager for the JavaScript programming language. 
- It is the default package manager for the JavaScript runtime environment -Node.js.
- npm consists of three components – 
- The website - The website discovers packages, set up profiles, and manage access to public or private packages.
- The Command Line Interface (CLI) - The CLI runs from a terminal and allow us to interact with npm. 
- The registry -  The registry is a public database of JavaScript packages comprised of software and metadata.

## Why node.js for Angular
- We use Node.js and npm as tools for building Angular or React apps. 
- Angular is a front-end framework used to create a web application and is written in Typescript. 
- The browser only understands JavaScript code, so we need to compile Typescript (.ts file) to plain JavaScript (.js file). 
- We use Node.js and npm to perform this compilation, then we can deploy them in production

## Installation of node and npm
- We need to add Node.js and an npm package manager to our development environment.
- Download Node.js from nodejs.org and install it. 
-  To check the version, run node -v in a terminal.
- The npm CLI gets installed with Node.js by default. 
- To check that you have installed npm, run npm -v in a terminal. npm can install packages in a node_modules folder in our working directory
![image](https://user-images.githubusercontent.com/12488769/148703088-963a7193-fd8b-4ec0-8707-914dcc5b5dac.png)

## package.json
- All npm packages contain a file, usually in the project root, called package.json. 
- This file is used to give information to npm that allows it to identify the project as well as handle the project's dependencies. 
- This file contains metadata relevant to the project, such as project description, the version of the project, license information, etc.,
- Node.js generates a package.json file by running the npm init command in the terminal. 
- The generated package.json file contains a name, version, description, main (entry point), any scripts, the author, and license type of our project.
![image](https://user-images.githubusercontent.com/12488769/148703136-37a84302-f522-432d-a101-5033da5dcf27.png)

## structure of package.json
- dependencies - The Dependencies section in the package.json file is essential for running applications. 
- It contains a list of packages or modules installed using npm that are required to run the project.
devDependencies - The DevDependencies section in the package.json file is used only for developing applications. 
- It contains a list of packages or modules that are required only for development. 
- These packages are installed only on the developer's machine and will not be run for a production 

## Webpack
- In our web application, we use many javascript files that are added into the HTML pages via <script> tags. 
- For each user request, the browser loads these bunch of script files inside the HTML page. 
- This is inefficient as it reduces the page speed since the browser requests each script file separately.
- This can be solved by bundling several files together into one file to be downloaded by the browser in one single request.
- Module bundlers are used to bundle a group of JavaScript modules with their dependencies and merge them into a single file in the correct order, which can be executed by the browser.
- Webpack is a powerful static module bundler for JavaScript applications that packages all modules in our application into a bundle and serves it to the browser.
- Webpack builds a dependency graph when it processes the application. 
- It starts from a list of modules defined in its config file (webpack.config.js) and recursively builds a dependency graph that includes every module our application needs, then packages all of those modules into a small bundle that can be loaded by the browser.



