Learning Material

\*\*\*\*\*\*\*\*\*\*\*\*\*\*



Flaky tests - - - - 

=============



Sometimes pass , sometimes fails

Synchronisation issues

Environment issues





How to validate payment page - - - - 

=============================



Insufficient balance

Expiry card

Credit card limit

Repeated transactions

Payment decline

Timeout



Expiry coupon

Future date coupons

Reused coupons

Using 2 coupons in one

Check stores where it’s only applicable







Why Use static in Java : : : : :

=======================



In Java, static makes variables, methods, or inner classes belong to the class itself rather than any specific instance. This can be especially valuable in test-driven environments common to SDET roles. Here’s how it’s useful:



Static Variables – Shared across all instances. Great for things like counters or shared resources across test classes.  



Static Methods – Call these without needing an object! Ideal for utility methods, like reusable test data generators.  



Static Blocks – Perfect for one-time setups like initializing constants or configuration details.  



Static Inner Classes – Can be used without an outer class instance, making them perfect for helper classes in test frameworks.  



Interview Tip - - - -

If you’re asked about static in an interview, try to explain it with practical examples—mention where you’ve implemented it in your Automation Framework for resource sharing, utility functions, or configuration setup.







What is Operators : : : : :

====================



Int a = 1

Int b = 2

Int c = a+b



In above, a b c are variables

Int is datatype

a+b is expression

\+ is operator

= is assignment operator



Once variables involved in expression then they are operands

So a and b are operands







MongoDB : : : : : :

==============

MongoDB is a popular open-source NoSQL database that stores data in a document- object oriented format, unlike traditional relational databases which store data in tables.



MongoDB stores data as JSON-like documents, making it more flexible and scalable. The name MongoDB is derived from the word humongous



BSON documents are the format used for data stored in MongoDB



BSON binary script object notation

JSON JavaScript object notation



Collections instead of Tables

Documents(BSON) instead of row

Fields instead of columns

MongoDB is schemaless



Features of MongoDB



Aggregation

Aggregation is a powerful feature in MongoDB that allows you to process and analyze data across multiple documents in a collection. It enables you to perform complex data manipulations, transformations, and calculations on large datasets.



Schema-less

Document-Oriented :

Data stored in form of documents

Sharding







SQL : : : : : : : 

==========



𝗜𝗻𝘁𝗲𝗿𝘃𝗶𝗲𝘄𝗲𝗿: You have 2 minutes to solve this SQL query.

Retrieve the department name and the highest salary in each department from the `employees` table, but only for departments where the highest salary is greater than $70,000.



𝗠𝗲: Challenge accepted!



SELECT department, MAX(salary) AS highest\_salary

FROM employees

GROUP BY department

HAVING MAX(salary) > 70000;



I used `GROUP BY` to group employees by department, `MAX()` to get the highest salary, and `HAVING` to filter the result based on the condition that the highest salary exceeds $70,000. This solution effectively shows my understanding of aggregation functions and how to apply conditions on the result of those aggregations.



𝗧𝗶𝗽 𝗳𝗼𝗿 𝗦𝗤𝗟 𝗝𝗼𝗯 𝗦𝗲𝗲𝗸𝗲𝗿𝘀:

It's not about writing complex queries; it's about writing clean, efficient, and scalable code. Focus on mastering subqueries, joins, and aggregation functions to stand out!







###### **JavaScript**



Keywords::

Let -> local scope — to keep private

Var -> Global scope — upto outer function

const -> Value is constant, cannot change



Node.js is Javascript runtime environment

To run Java script we will need this node.js Installed



Console.log(“print”) - this is print statement



Console.log(typeof(10)) - this will print the data type of variable

Above is number



Console.log(typeof(“10”))-

Above is String



Console.log(typeof(true)) -

Above is Boolean



Console.log(typeof(null)) -

Above is object



let a

Console.log(a)

If you try to print without initialising a value is will print - undefined

Console.log(typeof(a)) -

Its type also undefined



If you store null as a value to variable, it will print null

If didn’t specified a value , it is print as undefined



Data types

Number

String

Boolean

Null

Undefined



Create file name.js



How to Create function



Function functionName() {

Logic }



To run we need to call function name

Example:



Function demo(){

Logic }



Demo()



NaN- Not a Number





Arrays

=====

To add value

Use push()

Ref.push(1);

The is will add the value in last of array

We can also add multiple values

Ref.push(1,2,3,4)



To remove value

Ref.pop()

By default it will remove last value



Ref.unshift(10)

To add value in first



Ref.shift()

Remove the first value



Ref.fill(0)

This will replace all value with 0



Ref.fill(0, 1, 3)

This will replace values in between 1 and 3

1 is inclusive and 3 is exclusive



Ref.sort()

To make array in ascending order



Ref.reverse()

To make array n descending order









**API Testing Rest Assured**



Postman support both soap and rest api?



What is 2 tier arch

What is API in local and how it will be look like





API testing also called as Backend testing

Without even UI we can do this testing



Tool used to do API testing

Postman (manual)

Automation API testing tools

Rest API

SOAP UI



Client: Application we have in machine, visible to us

Server: where Application is available or hosted

Consist of basic code part to do actions

Program logic and database

In application we raise request , it will go to server and get the response



1Tier Architecture

Client and server in Same machine

Example: Notepad and system apps



2 Tier Architecture

App in one place and server in another place

Eg, Zomato and google map

2 app access s same server



Different client application accessing the same server



3 Tier Architecture

Client Tier (App UI)



Business logic(App layer which contains program for validation)



Database Tier (layer holds data)

Here server is divided into two

Program logic and Database



Request will be sent from client to business logic

Business logic will send the request and receive the response from database and share to the client





API - Application programming interface



API acts a a mediator that communicates between Front end and Backend



Front end application - web testing

|

Middle Layer (API server) - API testing

|

Back end - Database testing



Without front layer (UI app) we can do API testing



We can directly connect with API layer and get response

We can start testing before UI is developed



We can do testing in application(API) layer



API in local is API

API published in Internet is Webservice



API made to public is accessible by any application like Google Map, payment apps



Http - not secure without encryption

Https- secure with encryption



Encryption and decryption means

The data we will pass will be transcript and go to server

Again it will transcript and come back to us



Host path resource

In url without https it’s URI

Complete url is url

Resource name is URN









𝐐𝐮𝐞𝐬𝐭𝐢𝐨𝐧:Can you walk me through the steps involved in setting up a Selenium Java testing framework from scratch?



𝐀𝐧𝐬𝐰𝐞𝐫:

𝟏. 𝐒𝐞𝐭 𝐔𝐩 𝐘𝐨𝐮𝐫 𝐃𝐞𝐯𝐞𝐥𝐨𝐩𝐦𝐞𝐧𝐭 𝐄𝐧𝐯𝐢𝐫𝐨𝐧𝐦𝐞𝐧𝐭:

\- Install JDK, choose an IDE (e.g., IntelliJ IDEA or Eclipse), and set up Maven.



𝟐. 𝐂𝐫𝐞𝐚𝐭𝐞 𝐚 𝐌𝐚𝐯𝐞𝐧 𝐏𝐫𝐨𝐣𝐞𝐜𝐭:

\- Start a Maven project and configure the project structure (src/main/java for code, 𝐬𝐫𝐜/𝐭𝐞𝐬𝐭/𝐣𝐚𝐯𝐚 for tests).



𝟑. 𝐀𝐝𝐝 𝐃𝐞𝐩𝐞𝐧𝐝𝐞𝐧𝐜𝐢𝐞𝐬 𝐢𝐧 𝐩𝐨𝐦.𝐱𝐦𝐥:

\- Include essential dependencies like Selenium, TestNG, Log4j, WebDriver Manager, and ExtentReports.



𝟒. 𝐒𝐞𝐭 𝐔𝐩 𝐖𝐞𝐛𝐃𝐫𝐢𝐯𝐞𝐫 𝐌𝐚𝐧𝐚𝐠𝐞𝐫:

\- Automate browser driver management to simplify setup.



𝟓. 𝐂𝐫𝐞𝐚𝐭𝐞 𝐭𝐡𝐞 𝐁𝐚𝐬𝐞 𝐂𝐥𝐚𝐬𝐬:

\- Implement WebDriver initialization, @𝐁𝐞𝐟𝐨𝐫𝐞𝐂𝐥𝐚𝐬𝐬 𝐬𝐞𝐭𝐮𝐩, and @𝐀𝐟𝐭𝐞𝐫𝐂𝐥𝐚𝐬𝐬 𝐭𝐞𝐚𝐫𝐝𝐨𝐰𝐧 methods.



𝟔. 𝐂𝐫𝐞𝐚𝐭𝐞 𝐏𝐚𝐠𝐞 𝐎𝐛𝐣𝐞𝐜𝐭 𝐌𝐨𝐝𝐞𝐥 (𝐏𝐎𝐌):

\- Define separate classes for each web page or component to encapsulate interactions with web elements.



𝟕. 𝐖𝐫𝐢𝐭𝐞 𝐓𝐞𝐬𝐭 𝐂𝐚𝐬𝐞𝐬:

\- Use TestNG to write and manage test cases in the src/test/java directory.



𝟖. 𝐋𝐨𝐠𝐠𝐢𝐧𝐠 𝐚𝐧𝐝 𝐑𝐞𝐩𝐨𝐫𝐭𝐢𝐧𝐠:

\- Integrate 𝐋𝐨𝐠𝟒𝐣 for logging and ExtentReports for generating detailed HTML test reports.



𝟗. 𝐑𝐮𝐧𝐧𝐢𝐧𝐠 𝐓𝐞𝐬𝐭𝐬:

\- Create a TestNG XML configuration file to manage test execution.



𝟏𝟎. 𝐂𝐨𝐧𝐭𝐢𝐧𝐮𝐨𝐮𝐬 𝐈𝐧𝐭𝐞𝐠𝐫𝐚𝐭𝐢𝐨𝐧 (𝐂𝐈):

\- Set up CI tools like 𝐉𝐞𝐧𝐤𝐢𝐧𝐬 or GitLab CI to automate test execution and reporting in your build pipeline.





This comprehensive approach not only ensures a well-structured testing framework but also aligns with best practices in test automation. 






Why Java 8 is Still Widely Used Despite Newer Versions.

Java 8 remains popular even with many newer versions available. Here’s why many companies continue to use it:

1. Stability and Maturity :
Java 8 has been around since 2014 and has proven to be stable and reliable. Its extensive testing and long-term support (LTS) have made it a trusted choice. 

2. Backward Compatibility :
Java 8 introduced significant features while maintaining backward compatibility with previous versions, making it easier for companies to upgrade without breaking existing code. 

3. Key Features :
Java 8 introduced several powerful features that significantly improved the language, including:

- Lambdas and Streams : Simplified code and enabled functional programming paradigms. 

- Optional : Enhanced null handling to avoid `NullPointerException`.

- New Date and Time API : Replaced the outdated `java.util.Date` and `Calendar` classes.  

Main Usage and Features of Java 8

Apart from the features already mentioned, here are other key features that make Java 8 a popular choice:

- Default Methods in Interfaces : Allowed interfaces to have method implementations, enabling more flexible and reusable code without breaking existing implementations.

- CompletableFuture API : Simplified handling of asynchronous programming

Common Projects Built with Java 8

Java 8 is used in various types of projects across different industries:

- Enterprise Applications : Many large-scale enterprise applications rely on Java 8 due to its stability and mature ecosystem. Companies in finance, healthcare, and e-commerce often use Java 8 for backend systems.

- Web Applications : Java 8’s improvements in concurrency and the introduction of Streams API make it suitable for building robust and scalable web applications.

- Big Data Solutions : Java 8’s functional programming features and improved performance are advantageous in big data processing frameworks like Apache Hadoop and Apache Spark.

- Microservices : The enhancements in Java 8, such as CompletableFuture and the new Date and Time API, make it a good fit for microservices architecture, enabling better asynchronous programming and date/time handling.

Conclusion

While newer versions of Java offer additional features and improvements, Java 8 remains a popular choice due to its stability, extensive feature set, and backward compatibility. Its introduction of significant enhancements like lambdas, streams, and a new Date and Time API have left a lasting impact, making it a reliable and powerful option for various types of projects.












Manual testing

Testing ensures the software quality

SDLC - model - Approach

BRS. Business
FRS functional
SRS system requirement specification

System.exit
if we use above code Inside try block It will won’t allow finally block to execute
As it exit the execution
This is only condition where finally block won’t execute


Encapsulation For AutomationQA & SDET

 What is Encapsulation?

Encapsulation is one of the fundamental principles of Object-Oriented Programming (OOP) in Java. It is the mechanism of wrapping data (variables) and code (methods) together as a single unit, known as a class. The main idea behind encapsulation is to hide the internal implementation details of an object from the outside world, and provide a well-defined interface to interact with the object.

 Give an example from Automation ?

public class WebDriverManager {
private static WebDriver driver;

private WebDriverManager() {
// Private constructor to prevent instantiation
}

public static WebDriver getDriver() {
if (driver == null) {
// Create a new instance of the WebDriver
System.setProperty("webdriver.chrome.driver", "path/to/chromedriver");
driver = new ChromeDriver();
}
return driver;
}

public static void quitDriver() {
if (driver != null) {
driver.quit();
driver = null;
}
}
}

In this example, the WebDriverManager class encapsulates the WebDriver instance, which is a core component of the Selenium WebDriver API. The driver variable is declared as private static, meaning it can be accessed within the class, and there will be only one instance of the WebDriver shared across the entire test suite.

The class provides two static methods:

getDriver():
This method returns the instance of the WebDriver. If the instance doesn't exist, it creates a new instance of the Chrome WebDriver (ChromeDriver). This method ensures that there is only one instance of the WebDriver at any given time, following the Singleton design pattern.

quitDriver():
This method is responsible for closing the WebDriver instance when it's no longer needed, ensuring proper cleanup of resources.


 Why do we need encapsulation?


Data Hiding:
By making the instance variables private, the internal state of an object is hidden from the outside world, preventing direct access and unintended modifications.

Code Reusability:
Encapsulated classes can be easily reused in other parts of the program or in different applications, as they provide a well-defined interface to interact with the object.

Data Integrity:
By controlling access to the internal state through methods, encapsulation helps in maintaining data integrity by enforcing validation rules or business logic before modifying the data.

Code Maintainability:
Encapsulation is a fundamental concept in Java and OOP, as it helps in writing clean, maintainable, and reusable code by separating the implementation details from the external interface.




Why PlayWright is better then Selenium?

I'll list down some straight forward advantages that PlayWright has over Selenium:

1. No special code to handle browsers like selenium
2. Storage state
3. Built in Reporting and screenshots
4. Retries are made easier
5. Auto waiting and retry assertions
6. VScode extension
7. Isolated sessions
8. Simple integration with GitHub Actions
9. UI Mode and Trace Viewer
10. Does API Testing and is great at it
13. Grouping tests using a Describe Block
14. Accessibility Testing
15. Not having to manage drivers for the Browsers
16. Infinitely better Locator strategies

Now, let's breakdown if PlayWright framework is really better then Selenium Framework! :

Reporting supported by PlayWright is only available with JS, except this I think all other pros mentioned are far better in PlayWright over Selenium.






Java

JDK - Java development kit
|
JRE - Java runtime environment
|
JVM - Java virtual machine

JVM runs the program it will look for main method

Concatenation operator + ( inside sysout)

Primitive and non primitive data type

Non primitive- using data type we will create object to access and we can store multiple data
Primitive- Directly assigned to variable, we can store only one value for a reference

Identifiers
Should start in alphabet or _ or $
Cannot start with numeric or any other symbols
Identifiers cannot take the key words which is predefined in Java
Identifiers are case sensitive

Operators:

The default value of a boolean data type is false .

Default Values
 

Any property that performs more than one function is method overloading

Scanner s = new Scanner(System.in)

String variable
Variable is also an object that can call different methods

Java string pool in heap memory stores string

String is immutable
Objects are instance to the class

Instance variables
Controlled by objects
Each object we create will have a separate copy of instance variable

Stream is a channel between input and output to flow
IO devices
Input and Output devices

Null pointer exception
Array
String
Object


CTA
Call to function

Xpath travel in both directions forward and backward
CSS moved only forward
CSS is fast than Xpath

CSS selector
# - ID


Java archive - JAR
Web archive - WAR
Enterprise archive - EAR

In Java, declaring a class as static is only applicable to inner classes. If an inner class is declared as static, it can be instantiated without needing an instance of the enclosing class. This means the inner static class can access the static members of the outer class directly. However, you cannot declare a top-level class as static. Here is an example:

```java
public class OuterClass {
static class StaticInnerClass {
// Static inner class code
}
}
```

In this example, `StaticInnerClass` can be instantiated without an instance of `OuterClass`.








Guide to breaking down Cucumber for SDETs

Cucumber in QA automation is a tool that facilitates behavior-driven development (BDD) by allowing collaboration between developers, testers, and non-technical stakeholders

1. Installation: Install Cucumber in your project by adding the necessary dependencies based on your programming language. For Java, use Maven or Gradle

2. Understanding Gherkin Syntax: Learn the Gherkin syntax used in Cucumber feature files. Gherkin is a plain-text language that describes the behavior of an application in a structured way

3. Create a Feature File: Write a feature file (e.g., example.feature) using Gherkin syntax. Define the feature, scenarios, and steps that represent the behavior you want to test

Feature: Example Feature
Scenario: Login with valid credentials
Given the user is on the login page
When the user enters valid username and password
Then the user should be logged in successfully

4. Create Step Definitions:Create step definition files (e.g., StepDefinitions.java for Java) to map Gherkin steps to executable code. Define methods for each step

public class StepDefinitions {
@Given("the user is on the login page")
public void navigateToLoginPage() {}

@When("the user enters valid username and password")
public void enterValidCredentials() {}

@Then("the user should be logged in successfully")
public void verifyLoginSuccess() {}

5. Tagging Scenarios: Use tags to organize and selectively run scenarios. Add tags to scenarios in the feature files and specify them when running tests

6. Parameterisation: Use scenario outline tables and examples for parameterisation to run the same scenario with different input values

7. Hooks:Implement hooks to set up and tear down actions before and after scenarios or features

8. Use Background: It is always the best practice to put steps that are repeated in every scenario into the Background. Background step executes before each scenario.

Feature: I want to login into the site with valid and invalid data
Background:
Given I navigate to the Website
Scenario: Login as a new sign-up user with valid data

9. Use Data table: It’s recommended to use Data Table to store the data. We can give data as parameters within the step but once we have a large set of data.

10. Scenario outline: A scenario outline allows you to run the same scenario with different sets of data. It uses the Examples keyword to provide a table of inputs and expected outcomes.

-x-x-




TestNG is a Framework

POM - page object model
It used structure the project, by organising the code logics, it’s a design pattern.


TestNG is used organise test cases efficiently and flexible
We can do grouping and prioritising tests
Supports parallel execution
We can use XML file to manage suite level configuration and parameterisation
We have listeners and reports to listen the test and prepare report

Annotations and Attributes are two important things in TestNG

Annotation customise the order of execution

Attribute is a condition
Dependency and grouping like this

@Test(Enabled = True/False)
Default is true

@Test(alwaysRun = True/False)

@Test(dataProviderClass = “name”)

If data provider method in other class means
@Test(dataProvider = “name”, dataProviderClass = ClassName.class)

@Test(groups = “smoke”)

@Test(groups = {“smoke” , “regression”})

@Test(dependsOnGroups = {“smoke” , “regression”})

@Test(dependsOnMethods= {“method1” , “method2”})

@Test(expectedExceptions = IOException.class)

@Test(invocationCount = 5)

@Test(priority = 1)





selenium architecture

Package with any language
Protocol (json wire protocol, W3C protocol)
Browser driver
Real browser

The difference between Selenium-3 and Selenium-4
1st,
So in selenium 3, so we have used JSON wire protocol, but however, in selenium 4 we are using this W3C protocol

2nd,
In selenium 3, the chrome driver was extended a by Remote WebDriver directly, but however, in selenium 4 the chromium driver extends the Remote web driver, and the chrome Driver & Edge Driver extends the chromium driver
Chromium Driver is the browser engine for many browsers

3rd,
Optimised Selenium Grid in Selenium 4 ::
Unlike Selenium 3, testers would no longer be required to start the hub and node jars every time they want to perform automation testing. In Selenium 4, hub and node are packed in a single jar file. Selenium Grid 4 architecture supports four processes—Session Map, Node, Router, and Distributor. Selenium Grid 4 has more scalable and traceable infrastructure. There are some additional perks like enhanced GUI and built-in support for Docker.

4,
Selenium 4 IDE is available for Firefox and Chrome browser. It is more than just a record and playback testing tool. There is a side-runner tool which allows us to run Selenium tests parallely on local Selenium Grid and cloud-based Selenium Grid. They have also improved the GUI for a better user experience.

5. Relative locators
Relative locator has been introduced in selenium 4 like (above, below, towriteof, toleftof, near )
So we can choose one locator, and we can locate different locator using the above commands
But selenium 3, we have to use a series of find commands to locate the surrounding elementsc
Selenium uses a Java script function getBoundingClientRect() to determine the size and positions of element on a page and uses this information to locate the neighbouring element

6, aChrome DevTools

We can manipulate the geographical location Like if you want to test how your people from different countries use this website by using this function we can point to that geographical location and we can access the application
Also, we can test in various network conditions like 2G 3G and 4G

7,
In selenium 4, decidedcapabilities class has been replaced by options class
So this function helps us to use different browser versions to test application in different browser versions And also OS versions

8,
So new method has been introduced in action class
ContextClick()
Click()
ClickAndHold()
doubleClick() and
release()






HTML
HyperText Markup Language is the code used to structure a web page and its content

So basically HTML structures the web page. So how a content should be visible. So what are the contents should be added to a particular function. Since we have like n number of elements in HTML. So we can use those things to customize a web page. So we have different tags for different function. Like a text in a web page or if you want to add a image. Also if you want to give some heading or a link. So for each and every different contents in a web page we have different tag fnames. So we can enclose such inputs in between those tag names to get the customized web output. So HTML consists a series of elements which we can use to structure our web page with the desired output.
Begins and closes with html tags
DOM HTML is made of tags and attributes

Element

so element so basically element is a part of a web page so whatever we see in a web page so we call them as a function or element. In XML or HTML element can contain some data some text or some image any item it can contain or else it can also be empty it's also considered as a element so a customizable or a typical element includes so a tag a opening tag which consists of some attributes and also some content either text or a link and the particular element tag will be closed so it will also have a closing tag at the end

We use the attribute inside the tags to access the element or function

For testing purposes we can add dummy attributes into a tag name which doesn’t affect the function

Attribute contains
Attribute name and value

Nested tags
Tag and tag
Both tags point to same function

CSS
CSS, Cascading Style Sheets, is the code that styles web content. It is used to decorate my webpage with background images and colors. Like HTML, CSS is not a programming language, it's not a markup language either. CSS is a style sheet language.

Structure tags
<html> The root of the HTML document specifies it as HTML.

<head> Contains head elements such as title, style, and meta tags in the HTML file.
Also contains all scripts

<title> defines the title of HTML document

<body> defines the body of an HTML document containing content like images, tables, and lists, etc.


HTML tags ::

<div> Define a division or a section in an HTML document.

So division means so we can group some of elements under division tag. So we can have n number of division under one division tags. So in a webpage we can divide the webpage into different division. So each division can also have n number of divisions. So depends on the functionalities..

<span> So, under div, we can use span tags to group certain elements
Defines , a generic in-line container

Uses
Maven - xml
Gradle - groovy scripting

Interface having only one method is functional interface

CSS selector only travel in forward (Top to bottom)
Xpath can travel both forward and backward.

Comparing both CSS selector is fast

For CSS selector
To use ID we have to use # before value
Like if Id = home
Then #home

Navigate-to
Navigate-forward
Like these methods coming from
WebDriver-Navigation
| |
Interface Class

Moving kerosal
Some dynamic images or links
Like the top content in hotstar which will have 5 highlights which will display sequential like presentation

Page load means it will wait for complete html DOM to load
Default time is 300seconds

Script load - 30 seconds

To get time
System.currentTimeMillis()






Why we need software ?
Cut down the cost
Improve revenue by reaching customers
To sustain in market by adopting technology
Migrating to different technologies

SDLC methodologies
One of the traditional method
Waterfall (Linear sequential method)
V model (Validation or verification)

Prototype model
Develop in a rapid manner.
Dummy model , initial model , rough draft
If new things added after original requirement is signed that’s is called change request
SOW - Statement of work

SRS- System requirement specification

The Spiral model
Combo of spiral and Iterative

Iterative model or Incremental model
Project is broken to lot of small pieces

Big Bang model
Time and material for billing
Fixed bed for billing

Agile model
Agile- meaning Quickly and easily
Sprint meaning fast

Stages
Client with give requirements which is
Business Requirement Document BRD
-Clients might have an IT team or not

Client will give business requirements, But we use System Requirement means technical stuff other than Business stuffs
-The person who converts BR to SR is Business Analyst / Business Management

Once requirements are prepared
Then We need Infrastructure to deploy the application which is physical server(ENV)
Infrastructure is like a basements and pillar
Which is took care by software Architect who is also called as Tech Lead who understands the complete infrastructure

Then we need Design, Design for each module which will be done by Designers UI/UX Designers
UI - User interface
UX - User experience

Then Start building a website
Developers will work on coding and once a module is done they will test it

Test environment/ Test Bed/ Sand box layer
Which should be similar to production environment but load limit can be less

Testing methodologies

Levels / Types of testing
—————————————————

Agile methodology
Scrum model

Business stakeholders will give the requirement (Input)
Product manager converts requirements to features
Product owner converts same to user stories
Scrum master is like manager for team he is managing everything
Retrospective— Retro - Go back
Inspect - do inspect

Scrum call - Normal status call
We discuss what we did yesterday
What we will do today
If Any road blockers

Each user story will have lot of subtask in it

Testing techniques
Boundary value analysis
Equivalence case partition technique
Decision table based testing (Cause Effect table)
State transition technique
Error guessing technique
Use case widely used in developing tests at systems or acceptance level

Types of test case design techniques
-Specification based
-Structure based
-Experience based


Augmented reality is a mixed reality / Virtual reality
This gives a AI kind of idea for all .


Monolithic and micro services

QA and QA

RAID - Risks Assumptions Issues Dependencies

Risk
Mitigation- Avoidance
Contingency- Issue happened and how to rectify


Test Strategies- OTS - Organisational test strategy
Responsive web design
Types and level testing we have to concentrate
Time and materials - Not Budget concern
Fixed bed - Fixed budget

Test planing and Information we give to clients
List out all our activities & Strategy
Requirements to carry out testing
Deliverable
RAID

Exploratory testing purposes:
End user will explore the application based on his knowledge
Like a end user
Other than requirements we will act like end user to find defects

Adhoc testing
Randomness
Like in a payment page if we click refresh or
back button then page can become unresponsive
This will be not a good sign from user side
To Avoid this do random testing

Data center
Contains servers and databases for a application

Server storage technology
Cloud computing

Scaling
Vertical scaling - increasing same server capacity
Horizontal - Increasing no of servers ( renting servers)

Types of cloud computing
Iaas paas SaaS
Load balancer will clear traffic and divert to server

Compatibility testing
Depends on hardware (device, mobile, system)
Software ( Browser apps, OS platform )

Contract testing
Testing the ApI contact is done properly

Browser stack
Emulator and simulator
Emulator- mobile
Here we can use different systems, os to test our app


Lambda test is competitive for browser stack

Devops will monitor and visualise
The application is availability
Monitor give logs
Visualise conforms availability

Axe and pally are automated tools for accessibility testing

Agile is flexible model
PO decide the release

Legacy website
Legacy - old
Some thing is available for long time/ old

Product backlog
Repository having User stories that yet to prioritise

Epic
|
User Stories
|
Sub tasks

Test scenario is high level action going to perform
Not revealing much information (Abstract)

Test case is low level action on how many ways we are going to perform a action

SLA
Standard level agreement
Service level agreement

Defect Triage
Call to prioritise the defects

3 Amigos
PO
Dev
QA


Java is Object Oriented
It runs with object

Echo - to create or to write
American standard code - 9 14

Concatenation operator +


