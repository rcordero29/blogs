# blogs

What do you find challenging about coding?

● Often i find challenging is putting the time in to become the programmer i want to
become, this is from either work, lack of motavation, etc

Talk about a project that disappointed you. What would you change?

● A project i did not enjoy and dissapaointed me was mastermind, i struggled
alot with that one and was not happy with my code

List three key things to consider when coding with SEO in mind.

● target audience? layout of site, title

List five or more ways you could optimize a website to be as efficient and scalable as possible.

● condence code, use APIs, better host, image optimazing

# BLOGS 203

If a user attempts to create a resource that already exists—for example, an email address that’s already registered—what HTTP status code would you return?

● 409 > conflict

Consider a responsive site design that requires a full-width image in all responsive states. What would be the correct way to code this to ensure the page loads the smallest image required to fill the space?

● media queries ?

When should you npm and when should you yarn?

● npm vs. Yarn will depend on your requirements, tastes, and preferences

How can you make sure your dependencies are safe?

● audit them

What are the differences between CHAR and VARCHAR data types (MySQL)?

● char = data values in a column are of same length.
VARchar = datatype when we expect the data values in a column are of variable length.

How else can the JavaScript code below be written using Node.Js to produce the same output?

● na

# blogs 204

What is “callback hell” and how can it be avoided?

●use promises

What are "stubs" in Node.js?

●"A stub is a function or object that replaces the actual behavior of a module with a fixed response. The stub can only return the fixed response it was programmed to return."

What are “streams” in Node.JS?

●"Streams are a way to handle reading/writing files, network communications, or any kind of end-to-end information exchange in an efficient way."

What does "chaining" mean in Node.JS?

● calling one method after another on a object

Explain “console” in Node.JS.

● "Node.js console is a global object and is used to print different levels of messages to stdout and stderr. There are built-in methods to be used for printing informational, warning, and error messages."

Explain exit codes in Node.JS. List out some exit codes.

●process.exit()

What is the difference between cluster and non-cluster Index?

●"Clustered Index

-Only one per table
-Faster to read than non clustered as data is physically stored in index order

Non Clustered Index
-Can be used many times per table
-Quicker for insert and update operations than a clustered index"

What are user defined functions? What are all types of user defined functions?

● na no idea


# Class10 (205)

//
How does Node.js handle child threads?
● it gives node the ability to run the process by accessing operating system commands.
How can you listen on port 80 with Node?
●
What tools can be used to assure consistent style?
● JSLint by Douglas Crockford.
● JSHint.
● SLint.
● JSCS.
List out the differences between AngularJS and NodeJS.
● angular is writen entirely in JS where Node is written in c, c++, and JS.
● angular is used for front end where as node is both front nd back\

What are the advantages of NodeJS?
● can be used for both front end and back end, fast, scalable.
What is meant by JSON?
●is an open data interchange format that is both human and machine-readable. (javascript object notation)
Discuss your understanding of Agile so far.
● being scalable and being adapatblility 
How is scrum different from waterfall?
●waterfall has a defined end date, and clear vision, where scrum is more loosely defined and no fear of failure when it comes to deadline
What are the Three Amigos in Scrum?
● the product owner, developer, and quality tester
What is the “timeboxing” of a scrum process called? Describe, please.
● a breakdown of time slots to scheudule time for development and discussion. 
What are the roles of a scrum master and product owner?
●leads the Agile development team and supports the Product Owner by relaying updates to relevant employees. Product Owners manage the product backlog and ensure the company gains maximum value from the product.


# class 12 (206)
What's the difference between operational and programmer errors?
● Operational errors are within the system, programmer errors are bugs in the program.
What is ‘event-driven’ programming?
● Event-driven programming is a programming paradigm in which the flow of program execution is determined by events
What are ‘worker processes’?
● runs the ASP.Net application in IIS
Describe how Node.js can be made more scalable.
● load balancing
Explain global installation of dependencies.
●    " Global installing dependencies puts the module into your Node. js path, which is Operating System dependent) and will be accessible from any project without the need to install it separately for each project while doing the setup.
They allow us to use the packaging as a tool anywhere on the local computer."

Explain RESTful Web Service.
●RESTful web services are light weight, highly scalable and maintainable and are very commonly used to create APIs for web-based applications


# class 14 (207)
Tell me about a project you’re particularly proud of. What did you do that worked out well?
●  so far i am very proud of this review app, its not much as of now but i can see a vision for it.
How do you do testing, and what do you think about it? How would you improve QA?
●  esscential part of coding, i dont enjoy but its necessary to avoid bugs
What tools do you use to find a performance bug?
●  Miniprofiler (.net / ruby / go / node.js)
What is the preferred method of resolving unhandled exceptions in Node.js?
● Using try-catch block
How does Node.js support multi-processor platforms, and does it fully utilize all processor resources?
● The Cluster module is one of the core Node.js modules and it allows running multiple Node.js worker processes that will share the same port.
What is typically the first argument passed to a Node.js callback handler?
● a error