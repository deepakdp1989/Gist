# Gist
Gist of all things Software Development and Engineering

Git

     1. Git as a directed acyclic graph --> Finite state automata --> mutable
     2. Git vs svn. Git is distributed, scalable.
     3. Git workflow: feature branch, hot-fix branch, incremental changes
     4. Git commands: 
          a. config
          b. init, status
          c. add, rm, reset, log
          d. checkout, push, pull, status, commit, branch, merge, fetch
          
Unix Shell Scripts:

     1. df -h : Display disk space statistics
     2. tab: sort of auto-suggestion
     3. ls - list content
     4. cd or cd ~: change to home directory
        cd - : change to previous directory
        cd .. : change to parent directory
        mv - move or rename
        rm -rf remove forcefully and recursively
        grep: pattern matching
        exit, ctrl d - logout
        cat- contents of file
        vi - editor
        i - insert mode
     5. Links - Hard links or Soft Links(Symbolic Links)
          Hard Links - resemble shortcuts in windows
          Soft Links - inode numbers
     6. rwx - read, write, execute
        chmod
     7. System user, Super user, Normal user
     8. 

HTML5

     1. webforms 2.0 - required and autofocus
     2. graphics - svg, canvas
     3. Media
     4. Webstorage (LocalStorage, SessionStorage)
     5. WebWorkers - a js that runs in the background
          (cannot access DOM as accessing DOM isn't thread safe. Non-blocking but synchronous).
          brings threading to JS.
     6. web sockets, sse - communication from server
     7. custom elements

CSS3

     1. media queries - if screen-size this then layout that
     2. layout - responsive (browser size, screen resolution, images)
     3. selectors - id and classes - unique id on same page. not enforced by css but helps in JS getelementbyID
     4. other selectors: type, attribute
     5. table vs div: tables aren't responsive, divs can be.
     6. multi-column layout
     flexbox, CSS-Grid
     7. Object-oriented CSS - mixin and include
     8. CSS preprocessors - SASS, LESS
     9. Bootstrap
     


Javascript

     1. avoid global variables, new, ==, eval(), with
     == converts to matching types
     0==""; //true
     1=='1'; //true
     1==true; // true

     === forces comparison of value and type
     0==""; //false
     1=='1'; //false
     1==true; //false

     2. callbacks, promises, async/await
     aysnc without promises keyword

     Promises allow you to set an operation running (e.g. the fetching of an image from the server)
     and then wait until the result has returned before running another operation.
     Using threads, another thread picks up the other task.

     if you use the async keyword before a function definition.
     you can then use await within the function.
     when you await a promise, the function is paused in a non-blocking way until the promise settles.
     if the promise fulfills, you get the value back.
     if the promise rejects, the rejected value is thrown.

     When we pass a callback function as an argument to another function,
     we are only passing the function's reference as an argument.
     i.e. the callback function is not executed immediately.

     It is "called back" (hence the name) asynchronously somehwere inside the containing function's body.

     The containing function is responsible for executing the callback function when the time comes.

     call backs are versatile - not only do they allow you to control the order in which functions are run and what data is passed between them,
     they also allow you to pass data to different functions depending on circumstances.
     So, you have different actions to run on the response downloaded.

     There are two main types of asynchronous code style you will come across in JS code,
     old style call-backs and newer style promise style code.

     'then' keyword

     XMLHttpRequest

     shorthand arrows:

     () ==> {}

     hello = function()
     {return "hello world";}

     hello = () => 
     {return "hello world"};

     returns value by default

     can skip the () if there is only one parameter

     hello = val => "hello " + val

     https://developer.mozilla.org/en-US/docs/Glossary/Callback_function
     https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Asynchronous/Introducing


Server-side javascript

     Node.js official docs

JS Frameworks

     JQuery
     
     
Relational Databases, SQL, MySQL

     https://github.com/deepakdp1989/MySQL/wiki/Relational-databases-and-SQL


Linux commands:

     move a file: mv
     rename a file: mv
     delete a file: rm
     copy a file or directory: cp
     search: grep


Programming Paradigms:

     Object-oriented
     Functional-programming
     
Design Principles:     
     
     1. Maximum number of colors on a page
     2. UX
     

Finite loops vs infinite loops: while/ for without condition


Time complexity

     Time complexity and Space complexity
     Worst Case
     Average Case
     Best Case

Regular Expressions:

     Validitation - forms
     Email - 
     URLs - 



Authentication

      OAuth2.0
      https://roadmap.sh/guides/basic-authentication
      JWT: https://roadmap.sh/guides/jwt-authentication
      


Security

     OWASP


React, React Native, Redux
