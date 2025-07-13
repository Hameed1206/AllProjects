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







