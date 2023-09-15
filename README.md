# t3-a1-workbook

## Introduction
As a developer (dev) you are sometimes required to prove your knowledge to prospective clients and employers.

## Brief
In order to demonstrate your understanding of fundamental software concepts, you will provide answers to a series of short answer questions.

## Q1	Provide an overview and description of a standard source control process for a large project

Source Control is a crucial process of software development because it helps teams effectively collaborate the management of code commits and version control. This is essential for large scale projects to ensure the code integrity and fluid cooperation. Below are the stages and practices utilised in large scale projects.

### Selecting a Version Control System
Selecting and sticking to a version control system that suits the projects requirements is essential as it allows for fluid collaboration. A good example of Version Control Systems is Git. It has provided developers with the option to branch and merge code cheaply. "Git really changed the way developers think of merging and branching. From the classic CVS/Subversion world I came from, merging/branching has always been considered a bit scary (“beware of merge conflicts, they bite you!”) and something you only do every once in a while." (Driessen, n.d.)

### Branching Strategy
Utilising a branching method is important as it facilitates concurrent development and allows developers to focus on tasks individually without interrupting the work and control flow of the entire team. Github for example provides branching within their repos that allow approved users to clone the source code into a separate branch its intended format with the version control of packages required to run it. 

### Code Review Process
Once developers have have completed their assigned tasks within their branch they submit a pull request. This request is then reviewed by generally a senior programmer to check for any issues/potential errors and suggest recommended changes. Depending on the decision, either pull request is accepted or rejected. If the pull request is accepted the proposed changes of the branch will be merged with the main branch and the source code is updated. 

### Resolve conflicts
This is a step that coincides with the Code review process as programmers working on the same source code can sometimes have conflicts on their proposed changes. The proposed changes from pull requests will need to be reviewed by the team to determine whether the proposed code can be combined or if redundant code is found and needs to be eliminated. 

### Testing and Quality Assurance
When the changes have been merged with the source code. Testing is required to ensure that the changes added to the source code works as intended without any side effects or errors. For example for applications written in Javascript can be tested utilising tools such as Jest, Mocha or Cypress. 

### Release
After all the changes have been examined and tested and approved. The team then releases the source code to production. 

In conclusion the source control process is important because it allows the team to collaborate and ensure proposed changes are correctly monitored and effectively managed. It ensures that the source code until all the review/testing processes have been completed.


## Q2	What are the most important aspects of quality software?

Depending the requirements of the project, the most crucial elements of high quality software can change. However, some typical elements that are frequently seen as crucial for high quality software are as below:

### Reliability 
Software should reliably carry out its tasks as intended without interruptions or errors. It should be able to gracefully handle unforseen inputs or conditios that could trigger an error.

### Functionality
Software should provide the required features/capabilities as outlined within the criteria. It should carry out the tasks it promised as intended for accurately and effectively. 

### Usability 
Software should be designed to be simple and intuitive to use for the targeted userbase. This allows users to explore the options and capabilities with ease. It is important for effective and succinct documentation to be provided to the users so they can undertand the full scale of capabilites of the software.

### Performance
Quality software should be able to efficiently respond quickly providing effective user interactions. The software should be able to effectively handle the expected workload gracefully without any errors. 

### Security 
It is important that Software is designed to safeguard user information and prevent unauthorised access to sensitive data for nefarious purposes. 

### Maintainability
Quality software should be designed with maintenance frameworks and scalability depending on the requirements of the user. It is important that the code is clear and easy to read and accompanied with proper documentation such as version control.  

In conclusion Quality is important in software as this minimises the potential for unintended mishaps and errors "cost of a mistake might be just too high. History knows many examples of situations when software flaws have caused billions of dollars in waste or even lead to casualties: from Starbucks coffee shops being forced to give away free drinks because of a register malfunction, to the F-35 military aircraft being unable to detect the targets correctly because of a radar failure."(Quality Assurance, Quality Control and Testing — the Basics of Software Quality Management, 2020). 

## Q3	Outline a standard high level structure for a MERN stack application and explain the components

MERN stack application is web based application that utilises MERN which consists of (MongoDB, Express.js, React.js, Node.js). It is a well known technology stack and popular amonsgt developers for full stack Javascript applications."MERN Stack is a Javascript Stack that is used for easier and faster deployment of full-stack web applications."(Jasraj, 2021) The MERN stack consists of the following:

#### MongoDB
NoSQL document database that offers exceptional performance, scalability and flexibility while handling complicated data at the same time. It stores data in a flexible format similar to JSON known as BSON or Binary JSON.

#### Express.js
Is a quick and intuitive Node.js application framework. It provides a variety of features and tools to facilitate creation of APIs and web applications. Functions such as Routing, Request and Response handling are sorted by Express.js

#### React.js
React is a Javascript library that allows programmers to create reusable user interface elements and effectively handle application integrity. 

#### Node.js
Node is a Javascript runtime thatallows programmers to write Javascript code to be executed on the server side. Node.js provides a framework that has scalability and event driven architecture for building effective network applications. It allows programmers to utilise Javascript for both Front end and Back end therefore enabling Full stack development in one language. 

### Components of MERN Stack application

#### Front-End 

With the front end of a MERN stack application React.js is used by developers to manage the structure of an application while generating reusable User Interface components. It typically consists of User interface elements, client side logic and views. "React is used for the development of single-page applications and mobile applications because of its ability to handle rapidly changing data"(MERN Stack - GeeksforGeeks, 2019).

#### Back-end and Middle-ware

In regards to the back-end, Node.js and Express.js are utilised to build the MERN stack application. Node.js is responsible for data processing, business logic and communications between databases. Express.js is utilised for the its capabilities in routing and tools in relation to developing APIs. "Rather than writing the code using Node.js and creating loads of Node modules, Express makes it simpler and easier to write the back-end code."(MERN Stack - GeeksforGeeks, 2019).

#### Database

Within the MERN stack application, the databse system used is MongoDB. It is a NoSQL document-database which provides strong capabilities in handling and processing complex data structures. Developers utilise this system to store and retrieve data in a JSON-like format. "MongoDB is flexible and allows its users to create schema, databases, tables, etc. Documents that are identifiable by a primary key make up the basic unit of MongoDB."(MERN Stack - GeeksforGeeks, 2019)


#### Deployment

In the final stage of the MERN stack application, it can be set up using a variety of different systems such as AWS and Azure cloud services or installed into a server utilising tools such as Docker. 


## Q4	A team is about to engage in a project, developing a website for a small business. What knowledge and skills would they need in order to develop the project?

There is quite a few elements that a team would need to consider when it comes to taking on a project. It would require a good balance of technical skills such as project management, technical expertise and communication skills. It is found that the general knowledge and skills required to take on a project such as developing a website for a small business would be the following:

### Front-end Web Development

It is an important consideration whether the team has the required skills and knowledge of Front-end development to apply and develop the website that will meet the consumers requirements. The team should have a strong skill and knowledge base within development frameworks such as React.js or Angular and experience with languages such as HTML, CSS and Javascript. With these skills the team should be able to develop intuitive and responsive websites that would meet the clients requirements. "According to Krug’s first law of usability, the web-page should be obvious and self-explanatory."(Friedman , 2021)

### Back-end Development

The team would need to ensure that they have the required proficiency within back-end development. This would require foundation and understanding of programming languages such as Node.js or Python and experience working with frameworks such as Express.js and Django. Developers would require these crucial skills as they have 

### Database Management

Team should also have a base of knowledge and familiarity of database systems such as Postgres, MySQL and MongoDB, it is crucial so developers can implement data structures, security and maintenance of data. 

### Responsive User Interface Design

Another matter to consider is that although a website that is developed to be efficient or function as intended if it is not visually appealing or responsive, users will not consider using it. Developers would do well to have an understanding and skill base using applications such as Adobe XD, Sketch and Figma because it allows them to consider the visual elements of websites and adaptability with responsive design to attract target users."Very simple principle: If a website isn’t able to meet users’ expectations, then designer failed to get his job done properly and the company loses money."(Friedman , 2021)

### Project Management and Collaboration

While considering the teams capability and the clients requirements for the website, it is crucial for the team to establish the framework of project and how it's progress is managed. It is important to consider the compatibility of developers aswell ensuring that the team has a system in place such as Agile or Scrum to manage the workload and deadlines. Meetings and Huddles are important to encourage collaboration and communicate requirements or changes within the project.

In conclusion it is important that teams consider not only technical ability but also other skills such as design and project management collaboration skills to ensure that when a project such as a website is considered, they will have the required skills to tackle the project with efficiency and effectiveness. 


## Q5	With reference to one of your own projects, discuss what knowledge or skills were required to complete your project, and to overcome challenges

For example when I was developing an API used for booking agents, tour guides and consumers to connect. There was some challenges and skills that were required for the completion of the project. Below were some of the skills and also some challenges that were faced to complete this project. 

### Backend Development

In this project I was required to have a good understanding of implementing the API functions and database. It was important as I needed to establish server side functionality, ability to handle requests, authentication and storing data within the database. I needed a base of knowledge with Python to effectively establish the API requests, functions and error handling with grace. 

### Database Management

Within this project I was required to have a good understanding and base in utilising a Database system with its capabilities. In this project I used Postgres to establish my database, design schemas, managing data storage and implementation of queries. There was definitely challenges in relation to linking different data and ensuring it was functioning as intended in tandem with the API requests. 

### Version Control

Within this project I needed to be experienced in managing the projects data and source code. I used Github as my repo system to establish consistency for my project and keeping track of my changes to the code and notes. It was also required so I could keep track of the packages I utilised for the Python project. 

### Project Management 

For the project I utilised a project management software called Trello to allow me to organise and keep track of the projects tasks and notes. This allowed me to effectively keep track of the progress and any outstanding tasks that need attention. 

In conclusion I had to use alot of different skills and knowledge bases to effectively tackle this project. There was challenges across each element of the project but with the skills and problem solving nature required of a developer I was able to overcome them and accomplish the set task. 

## Q6	With reference to one of your own projects, evaluate how effective your knowledge and skills were for this project, and suggest changes or improvements for future projects of a similar nature

For the example with the API project I developed although I was able to accomplish the task and establish the API I did feel that there some short comings and challenges I could've been more effective at tackling through much deeper and effective research. 

### Backend Development

In this component I believe I could've done further research into example projects and tutorials to understand the full capabilities of Python and effectively utilising it. 

### Database Management

With Postgres I had some challenges with establishing the links between data and the API project. I think with further research and tutorials to effectively circumnavigate the errors and challenges. 

### Project Management 

I had some challenges with the technical aspects of the project but I feel that with more effective task allocation and deadline management I could've done a much more efficient job at completing the API. 


## Q7	Explain control flow, using an example from the JavaScript programming language

in definition Control Flow is the sequence in which statements are carried out in order by a program. Developers are able to control the flow of the source code in specific conditions. For Example, a popular programming language such as Javascript provides a variety of methods to control flow like If-Else Statements, Loops, Ternary Operators and Switch Statements. Below are explanations of the various methods used. 

### Switch Statements

This state gives the developer the option to execute different blocks of code based on specific conditions that are satisfied, if it is not satisfied it will continue down the code block until a condition can be satisfied. The developer is able to handle various possible outcomes gracefully within a single expression. Please see below:

```javascript
let pokemon = "Pikachu";

switch (pokemon) {
  case "pikachu":
    console.log("It's a Pikachu!");
    // Since variable is Pikachu it will console.log the above message and then break
    break;
  case "charmander":
    console.log("It's a Charmander");
    // If in a situation the variable was Charmander it will console.log the above and then break
    break;
  default:
    console.log("Its just another pokemon");
    // If the variable was anything else that didn't meet the specific conditions it will default to the above message
    break;
}
```

### Loops 

This is used to execute specific blocks of code repeatedly until the condition is met. Javascripts provides several variations of Loops for specific situations such as For Loops and Do-While loops. Please below example of For loops 

```javascript
for (let i = 0; i < 5; i++) {
  console.log(i);
  // In this example
  // Variable (i) = 0
  // Condition is if (i) less than 5 then execute console.log but also for each time (i) is used in the expression it will be incremented. Creating a Loop until the condition is not able to be satisfied. 
}
```

### If-Else Statements

This statement is used by developers for executing blocks of code based on specific conditions. If the condition is True then a specific code within that block will be executed. If not then the code within the Else block will be executed. Below is an example:

```javascript
let num = 10;

if (num > 0) {
  console.log("The number is positive.");
} else {
  console.log("The number is negative or zero.");
}
// In this example the variable is 10
// If statement is if the variable is less than 0 then execute the If block or either run Else block.
```


## Q8	Explain type coercion, using examples from the JavaScript programming language

Type Coercion in Javascript is the process of automatic conversion of one data type into another. "This includes conversion from Number to String, String to Number, Boolean to Number etc. when different types of operators are applied to the values."(What Is Type Coercion in JavaScript, 2023) When a function or operator requests a data type that is different from existing data type, a conversion occurs. For example a popular programming language such as Javascript performs Type Coercion which gives developers flexbility but it sometimes can lead to side effects if the process is not fully understood. Below are examples of the types of Coercion by Javascript

### Explicit Coercion

This type of conversion is intentional when converting a value from one data into another by using functions or methods. Please see below example

```javascript
let num = 10;
let str = String(num); // This explicitly converts the number into string data

console.log(str); // Outputs "10" but as a string
```

### Implicit Coercion

In contrast Implicit coercion occurs when Javascript converts the data from one into another without a direct or explicit conversion. This commonly happens when operators or functions are established for different data types. Please see example below:

```javascript
let num = "10";
let str = "5";
// As you can see there is number data type as 10 and a string data type as 5
console.log(num+str);
//  Output of Console.log would be 105
// In the Console.log with the + operator, what happens is that Javascript will apply implicit conversion which changes the number data type into str and concatenates the data. This can lead to unexpected results. 
```


## Q9	Explain data types, using examples from the JavaScript programming language

Within Javascript, numerous data types can be assigned to variables such as Null, Boolean, Number, Undefined, String and Object. Please see below Examples of Data types with explanations. 

### Boolean 

This data type represents a logical entity that is limited to only 2 outcomes being True or False. This Data type is commonly utilised by developers for situations where conditional operations are required. For example:

```javascript
  let isTrue = true;
  let isFalse = false;

  (isTrue == true) // Returns true
  (isFalse == true) // Returns false
```

### Number

This data type is for representing numerics such as integers and floating numbers. For Example

```javascript
let myNumber = 10;
let pi = 3.14159;

console.log(myNumber); // Output is 10
console.log(pi); // Output is 3.14159
```

### Null

Represents the lack of any value intentionally. It is a keyword in Javascript. For example

```javascript
let nullVariable = null;
console.log(nullVariable); // Output is null
```

### Undefined

This data type is used for an undefined value. Developers utilise it as a normal value and global property in Javascript. For example:

```javascript
let randomVariable;
console.log(randomVariable); // Output is undefined
```

### Object

This datatype is used to represent a collection of key value pairs. Developers use it Objects for its capability to hold a variety of data types making it vital in Javascript. For example:

```javascript
let randomObject = { brand: "Toyota", type: "Hatch"};
console.log(randomObject); // Output would be { brand: "Toyota", type: "Hatch"}
```


## Q10	Explain how arrays can be manipulated in JavaScript, using examples from the JavaScript programming language

Javascript uses arrays to store a number of values within a variable. There is a variety of methods and processes that developers can employ to manipulate the data. Please see examples below of various methods that can be used:

### Accessing Array Elements

Elements can be accessed through their Index numbers ranging from 0 and onwards. See below example:

```javascript
let pokemon = ['pikachu', 'charmander', 'squirtle'];
console.log(pokemon[0]); // Output will be Pikachu
console.log(pokemon[1]); // Output will be Charmander
console.log(pokemon[2]); // Output will be Squirtle
```

### Adding Elements to an Array

Developers can add elements into an array through methods such as push() and concat(). See below examples

```javascript
let anime = ['Dragonball', 'Pokemon', 'Hunterxhunter'];
anime.push('One Piece'); // Adds 'One Piece" to the end of the array
  console.log(anime);
```


## Q11	Explain how objects can be manipulated in JavaScript, using examples from the JavaScript programming language


## Q12	Explain how JSON can be manipulated in JavaScript, using examples from the JavaScript programming language


## Q13	For the code snippet provided below, write comments for each line of code to explain its functionality. In your comments you must demonstrates your ability to recognise and identify functions, ranges and classes

```javascript
class Car {
  constructor(brand) {
    this.carname = brand;
  }
  present() {
    return 'I have a ' + this.carname;
  }
}

class Model extends Car {
  constructor(brand, mod) {
    super(brand);
    this.model = mod;
  }
  show() {
    return this.present() + ', it was made in ' + this.model;
  }
}

let makes = ["Ford", "Holden", "Toyota"]
let models = Array.from(new Array(40), (x,i) => i + 1980)

function randomIntFromInterval(min,max) { // min and max included
    return Math.floor(Math.random()*(max-min+1)+min);
}

for (model of models) {

  make = makes[randomIntFromInterval(0,makes.length-1)]
  model = models[randomIntFromInterval(0,makes.length-1)]

  mycar = new Model(make, model);
  console.log(mycar.show())
}
```