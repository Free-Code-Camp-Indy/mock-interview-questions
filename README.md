# freeCodeCampIndy Mock Interview Questions

## Introductory Questions

* How did you get into programming?
* What would your ideal job description be? Technologies involved?
* What will you need to learn on this job?
* Brag about yourself
* Who are programmers that you follow or admire?
* What are the best online sources for keeping up-to-date on the industry?
* What are some recent announcements for a technology you use?
* What are some hobby technologies you enjoy?
* What are you currently learning about?
* How would this job differ from your current job? What will you have to learn?

## Behavioral Questions

* Describe the most challenging project you have worked on, and what made it challenging, and what steps you took to work efficiently.
* Tell me about a time when you have worked with a difficult person, and how the situation was resolved.
* Tell me about a time when you have had to step up to be a leader without having the title.
* Tell me about a time when you have worked significantly outside of your job description.
* Tell me about a time when you have failed.
* What is a significant improvement you have contributed proactively to a company, outside of projects?

## General Programming Questions

* Describe Big O notation, and an example of each type that you can name.
  * 1 	Constant
  * logn	Logarithmic
  * n	Linear
  * 2n	Exponential
* Describe the stack versus the heap.
* Describe passing by reference and by value. Does JavaScript pass by reference?
  * Pass by Value passes a copy of the value. Same value, different variable.
  * Pass by Reference passes the reference to the same variable.
  * Some people confuse this, easy to miss on an interview. Many higher level languages like JavaScript passes “by copy of reference”, not the reference itself. So if you reassign the whole object, it won’t change the object.

## Networking Questions

* Describe the HTTP protocol
* Compare TCP with UDP
* Describe what you know about DNS. How does a DNS lookup occur? What are two of the most common DNS record types?

## API Questions

* When designing a RESTful API, what criteria do you use to decide between putting data in a querystring or the body?
* What are some of the most common HTTP status codes? 200s? 300s? 400s? 500s?
* What is idempotency and how does it apply to REST verbs? When would you use PUT vs POST? Why would you Upsert vs Insert/Update?
* How does the Authentication header work?
* What headers control browser caching?
* How does a Rewrite differ from a Redirect?
* Compare Etags versus Expires headers.

## Security Questions

* What is CORS?
* What is Cross Site Scripting?
* How do injection attacks work?
* How do denial of service attacks work?
* What is Cross-Site Request Forgery?

## Database Questions

* How do indexes work?
* Compare a clustered versus a non-clustered index.
* When would you choose NoSQL over a Relational database, or vice versa?
* Describe how Group By clauses work
* Compare Inner Join with Left Outer Join in relational databases

## Open-ended Questions

* If you were to make a Battleship game (web, mobile, command line, or desktop, your choice), what technologies would you choose, and why? Feel free to include favorite libraries, tools, databases, etc.
* If you were to make a Battleship game, what features or technical considerations would you have?
* Describe what happens when you press Enter to go to Google.com. What about when you type in the search box?
* Implement a stock ticker. How do you handle displaying all of the data quickly to the end user?
* You want your product to scale to be as large as Facebook. What challenges will you have, and what tools or approaches might you take?
* A customer complains your website is slow. How do you troubleshoot the issue?
* Tell me in depth about the best program you have ever created or worked on.

## CSS Questions

* What are different methods and pitfalls of vertically and horizontally aligning elements? (margin auto)
* How do Align Items and Justify Content work in Flexbox? What are different ways to Justify Content?
* Describe different ways you can create a footer with a scrollable box above it.
* Describe how media queries work.
* Describe how transitions and keyframes work.

## Git Questions

* Describe how Git commits work.
* How can you undo a commit?
* How can you undo a command like git reset HEAD~1 --hard?
* Compare rebasing with merging.

## JavaScript-based Questions

* What data types are there in JavaScript?
* What is the difference between double equals and triple equals?
* Describe how "this" works in JavaScript.
* What is a closure? Give an example use of one.
* Compare Callbacks, Promises, and Async Await.
* How can you iterate properties of an object?
* Describe some newer features in JavaScript, preferably more than just let/const/arrow functions/destructuring.
* Is Javascript single-threaded? Describe the event loop.

## Mock Interview Problems

* Fizz Buzz
* Palindrome Evaluator
* Recursive Fibonacci Generator
* Using some type of iteration, output a 16 x 16 image that is a box with an "X" touching each corner.
