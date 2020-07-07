# Gist
Gist of all things Software Development and Engineering

Git

     1. Git as a directed acyclic graph --> Finite state automata --> mutable
     2. Git vs svn. Git is distributed, scalable.
     3. Git workflow: feature branch, hot-fix branch, incremental changes
     4. Git commands: config, init, log
     checkout, push, pull, status, commit, branch, merge, fetch

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


Linux commands:

     move a file: mv
     rename a file: mv
     delete a file: rm
     copy a file or directory: cp
     search: grep


Language C# 6.0 


     [Detailed Discussion] : https://www.tutorialspoint.com/csharp/index.htm; https://www.completecsharptutorial.com/basic/; 
     i) OOPs : https://www.c-sharpcorner.com/UploadFile/mkagrahari/introduction-to-object-oriented-programming-concepts-in-C-Sharp/; 
          https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/object-oriented-programming
     ii) Collections : https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/collections; 
          http://www.tutorialsteacher.com/csharp/csharp-collection; http://www.tutorialsteacher.com/csharp/csharp-generic-collections
     iii) Generics : https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/generics/; http://www.tutorialsteacher.com/csharp/csharp-generics
     iv) Delegate and Events : http://csharpindepth.com/Articles/Chapter2/Events.aspx; https://www.c-sharpcorner.com/UploadFile/84c85b/delegates-and-events-C-Sharp-net/
     v) Language Constructs : https://www.tutorialspoint.com/csharp/index.htm
     vi) Exception handling : https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/exceptions/; 
     vii) LINQ : https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/linq/getting-started-with-linq;
                 https://www.tutorialspoint.com/linq/index.htm; https://www.dotnettricks.com/learn/linq
     viii) TPL : https://docs.microsoft.com/en-us/dotnet/standard/parallel-programming/task-parallel-library-tpl; https://www.codeproject.com/Articles/1083787/Tasks-and-Task-                    Parallel-Library-TPL-Multi-threadin
     ix) yeild return : https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/yield;
                        https://www.codeproject.com/Articles/575713/What-is-the-use-of-csharp-Yield-keyword; https://www.kenneth-truyers.net/2016/05/12/yield-return-in-c/
     x) anonymous functions : http
        http://jonskeet.uk/csharp/; https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/language-specification/introduction (Look at this!)
 
     1) Concepts (Abstracted) [Detailed Discussion]
          i) CLS-CTS : https://www.guru99.com/net-framework.html
          ii) CLR : https://www.guru99.com/net-framework.html
          iii) Garbage Collection : https://www.codeproject.com/Articles/1095402/Garbage-Collection-and-Csharp; https://docs.microsoft.com/en-us/dotnet/standard/garbage-collection/
          iv) Managed Code : https://www.codeguru.com/csharp/.net/cpp_managed/article.php/c4871/Managed-Unmanaged-Native-What-Kind-of-Code-Is-This.htm;                         https://social.msdn.microsoft.com/Forums/vstudio/en-US/a3e28547-4791-4394-b450-29c82cd70f70/managed-code-vs-unmanaged-code?forum=csharpgeneral
          v) Boxing : https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/types/boxing-and-unboxing
          vi) Thread Safety : https://www.c-sharpcorner.com/UploadFile/1c8574/thread-safety369/
     
     2) Language C# 6.0 [Detailed Discussion] : https://www.tutorialspoint.com/csharp/index.htm; https://www.completecsharptutorial.com/basic/; 
          i) OOPs : https://www.c-sharpcorner.com/UploadFile/mkagrahari/introduction-to-object-oriented-programming-concepts-in-C-Sharp/; 
               https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/object-oriented-programming
          ii) Collections : https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/collections; http://www.tutorialsteacher.com/csharp/csharp-collection;   http://www.tutorialsteacher.com/csharp/csharp-generic-collections
     iii) Generics : https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/generics/; http://www.tutorialsteacher.com/csharp/csharp-generics
     iv) Delegate and Events : http://csharpindepth.com/Articles/Chapter2/Events.aspx; https://www.c-sharpcorner.com/UploadFile/84c85b/delegates-and-events-C-Sharp-net/
     v) Language Constructs : https://www.tutorialspoint.com/csharp/index.htm
     vi) Exception handling : https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/exceptions/; 
     vii) LINQ : https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/linq/getting-started-with-linq; https://www.tutorialspoint.com/linq/index.htm;                          https://www.dotnettricks.com/learn/linq
     viii) TPL : https://docs.microsoft.com/en-us/dotnet/standard/parallel-programming/task-parallel-library-tpl; https://www.codeproject.com/Articles/1083787/Tasks-and-Task-                    Parallel-Library-TPL-Multi-threadin
     ix) yeild return : https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/yield; 
                        https://www.codeproject.com/Articles/575713/What-is-the-use-of-csharp-Yield-keyword; https://www.kenneth-truyers.net/2016/05/12/yield-return-in-c/
     x) anonymous functions : https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/statements-expressions-operators/lambda-expressions;                                                             https://msdn.microsoft.com/en-us/library/bb549151(v=vs.110).aspx; http://www.tutorialsteacher.com/csharp/csharp-func-delegate
     
     3) IDE and Project settings [Detailed Discussion] : https://msdn.microsoft.com/en-in/library/b142f8e7.aspx
          i) Console Application
          ii) Windows Form Application
          iii) Web Application
          iv) Windows Services : https://www.c-sharpcorner.com/UploadFile/naresh.avari/develop-and-install-a-windows-service-in-C-Sharp/
          v) WebApis : https://docs.microsoft.com/en-us/aspnet/web-api/overview/getting-started-with-aspnet-web-api/tutorial-your-first-web-api
          
     4) Principles and Best Practices [Introductory Discussion]
          i) SOLID principles : https://www.codeproject.com/Tips/1033646/SOLID-Principle-with-Csharp-Example; http://www.dotnetcurry.com/software-gardening/1365/solid-principles
          ii) Design Patterns : http://www.dofactory.com/net/design-patterns
          iii) Unit Testing Frameworks : https://stackify.com/unit-test-frameworks-csharp/; https://www.c-sharpcorner.com/UploadFile/Santhi.M/comparison-of-unit-testing-tools-in-net/
          
     5) ASP.NET [Introductory Discussion] : https://www.tutorialspoint.com/asp.net/; https://www.guru99.com/asp-net-tutorial.html; http://asp.net-tutorials.com/
          i) Page Lifecycle
          ii) GAC and config files
          iii) ISAPI
          iv) Session Management
          v) Authentication and Authorization
          vi) IIS
          
     6) ADO.NET [Detailed Discussion] : https://www.javatpoint.com/ado-net-tutorial; 
          i) Connection
          ii) Command
          iii) Connected and Disconnected Mode
          iv) Transaction Scope
          v) DataReader
          vi) Best Practices



Programming Paradigms:

     Object-oriented
     Functional-programming
     

Finite loops vs infinite loops: while/ for without condition


Time complexity

