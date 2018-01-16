# Project Search Engine

## Abstract

In this new era of Science and Technology, computer is one of the most important components in our life. Works can be done in a better way by the help of computer. The main aim of this project is to create a web based application system which is a search engine application system for the users that will enable them in increasing the efficiency and effectiveness in retrieving the projects. The system will be user-friendly, ease to use and administrate. This application is accurate, user friendly and provides information in less time. This system is developed with an eye towards the future and can easily be updated with new
features, as needed.

## Acronyms and Definition

| Acronym | Definition |
|:-------:|:----------:|
| API | APPLICATION PROGRAMMING INTERFACE |
| DBMS | DATABASE MANAGEMENT SYSTEM |
| JDBC | JAVA DATABASE CONNECTIVITY |
| JSP | JAVA SERVER PAGES |
| JVM | JAVA VIRTUAL MACHINE |
| HTML | HYPER TEXT MARKUP LANGUAGE |
| HTTP | HYPER TEXT TRANSFER PROTOCOL |
| SQL | STRUCTURED QUERY LANGUAGE |
| WWW | WORLD WIDE WEB |
| XML | EXTENSIBLE MARKUP LANGUAGE |

Table of Contents
=================
- [Introduction](#introduction)
  - [About Project Search Engine](#about-project-search-engine)
  - [System Analysis](#system-analysis)
- [Literature Survey](#literature-survey)
  - [Existing System](#existing-system)
  - [Problem Definition](#problem-definition)
- [Software Environment](#software-environment)
  - [Java](#java)
    - [Features of Java](#features-of-java)
    - [Java Server Pages](#java-server-pages)
    - [About HTML](#about-html)
    - [JDBC](#jdbc)
    - [JDBC Drivers](#jdbc-drivers)
    - [Web Application Archives](#web-application-archives)
  - [Oracle](#oracle)
    - [About Oracle](#about-oracle)
    - [Advantages of RDBMS](#advantages-of-rdbms)
    - [Disadvantages of DBMS](#disadvantages-of-dbms)
  - [Apache Tomcat Server](#apache-tomcat-server)
- [Design & Implementation](#design--implementation)
  - [Requirements](#requirements)
    - [Software Requirements](#software-requirements)
    - [Hardware Requirements](#hardware-requirements)
  - [Database design](#database-design)
  - [Modules](#modules)
    - [Search Engine Module](#search-engine-module)
    - [Page Rank](#page-rank)
    - [Keyword_Search](#keyword_search)
    - [How sites get into Search Engines](#how-sites-get-into-search-engines)
  - [DFD diagrams](#dfd-diagrams)
    - [Physical Data Flow Diagrams](#physical-data-flow-diagrams)
    - [Logical Data Flow Diagrams](#logical-data-flow-diagrams)
  - [UML diagrams](#uml-diagrams)
    - [Class Diagram](#class-diagram)
    - [Use-case Diagram](#use-case-diagram)
    - [Activity Diagram](#activity-diagram)
- [Result Analysis](#result-analysis)
  - [Test Cases and Scenarios](#test-cases-and-scenarios)
  - [Test Case Design](#test-case-design)
  - [Validation](#validation)
  - [Results](#results)
- [Conclusion](#conclusion)
- [References](#references)

## Introduction
### About Project Search Engine
**Project Search engine** is the process of improving the volume and quality of traffic to a web site from search engines via "natural" ("organic" or "algorithmic") search results. Usually, a site is presented in the search results or the higher it "ranks", the more searchers will visit that site. Search engine can also target different kinds of search, including image search, local 
search, and industry-specific vertical search engines.

As a marketing strategy for increasing a site's relevance, search engineconsiders how search algorithms work and what people search for. Search engine efforts may involve a site's coding, presentation, and structure, as well as fixing problems that could prevent search engine indexing programs from fully spidery site. Other, more noticeable efforts may include adding  unique  
content  to  a  site,  ensuring  that  content  is  easily indexed  by search engine robots, and making the site more appealing to users.

### System Analysis
Before  going  to  replace  or  planning  for  a  new  system  it  is  essential  to  have  thorough knowledge about the existing system along with estimation or determination of how computers can be 
best used to make its operations more effective. System analysis is a  process of collecting and interpreting facts, diagnosing problems and using the information  to recommend improvements to the system.

Accumulation  of  information  about  the  existing  system  is  called  System  Study. Basically, system analysis is about understanding situation, not solving problems.

## Literature Survey
### Existing System
The earlier system is not computerized. We need to gather the information manually, evaluate it manually and store the projects information in records which is not safe and
secure. It is difficult to store and maintain the projects manually. It is also tedious to maintain all the records.

The whole process of collecting the project records was done manually till date. Maintaining the project records is tedious work to handle and there is a chance of losing
data.The leading search engines, use crawlers to find pages for their algorithmic search results. Pages that are linked from other search engine indexed pages do not need to be
submitted because they are found automatically. Some search engines, operate a paid submission service that guarantee crawling for either a set fee or cost per click. Such
programs usually guarantee inclusion in the database, but do not guarantee specific ranking within the search results.

Search engine crawlers may look at a number of different factors when crawling a site. Not every page is indexed by the search engines. Distance of pages from the root directory of
a site may also be a factor in whether or not pages get crawled.

### Problem Definition
The  proposed  system  is  fully computerized,  which  removes  drawbacks  of existing
system and stores the details of projects. This type of application is accurate, user friendly and 
provides information in less time. This system is developed with an eye towards the future  and can 
easily be updated with new features, as needed.

The proposed project is a web application that will check submitted pages with known search engine 
algorithms and make suggestion to improve the ranking. The ranking algorithm of each search engine 
will store in files. The algorithms will be updated regularly by  studying
the ranking pattern of the search engines.

## Software Environment
### Java
The term java actual refer to more than just a particular language like Core Pascal. Java encompasses several parts, including:
  - **A High Level Language:**
    The Java language is a high level one that at a glance looks very similar to C and C++ but offers many unique features of its own.
  - **Java Byte Code:**
    A compiler,  such  as  Sun’s javac,  transforms  the Java language  source  code to byte code that runs in the JVM.
  - **Java Virtual Machine (JVM):**
    A program, such as Sun’s Java, that runs on a given platform and takes the byte code program as input and interprets them just as if it were a physical processor executing machine code.

#### Features of Java
**Platform Independent**

The Write-Once-Run-Anywhere ideal has not been achieved(tuning for different platforms usually 
required), but closer than with other languages.

**Object Oriented**

- Object oriented throughout-no coding outside of class definitions, including main().
- An extensive class library available in the core language packages.

**Compiler/Interpreter Combo**

- Code is complied to byte codes that are implemented by a Java Virtual Machine(JVM)
-This provides portability to any machine for which a virtual machine has been written.
-The two  types  of  compilation  and interpretation  allow for  extensive code checking andimproved security.

**Robust**

- Exception handling built-in,  storage type checking (that  is,  all  data must be declared an explicit type), local variable must be initialized.

#### Java Server Pages
JSP (Java Server Pages) technology provides a simplified, fast way to create dynamic web content. JSP technology enables rapid development of web-based applications that are 
server-independent and platform-independent.

JSP simply puts Java inside HTML pages. JSP is being turned into a Java file, compiled and loaded. This compilation only happens once, so after the first load, the file doesn't take long to load 
anymore. Every time you change the JSP file, it will be re-compiled again.

Every JSP page will have a corresponding servlet which is generated by ‘JSP Engine’ (which  is  a part  of web  container and  itself  is a servlet)  Corresponding  servlet  for JSP  
is generated only once when JSP is requested for the first time.

![alt text](https://github.com/apuroop-apz/bachelorsMiniProject/blob/master/figures/fig1.png)

The following are the jsp tags that are used for the implementation of the current project.

| TYPE OF TAG | SYNTAX | DESCRIPTION |
|:-----------:|:------:|:-----------:|
| Scriptlet tags | <% code %> | These are inserted into the servlets service() method. |
| Expression tags | <%= and %> | Encloses java expressions, which are evaluated at run time |
| Declaration tags | <%! Java code %> | For processing the request outside of the service() method |
| Comments | <%-- Comment -- %> | A jsp comment, ignored by jsp to scriptlet translator |


##### About HTML
HTML  (Hyper  Text  Markup   Language)  is  a   language  used  to  create   hypertext
documents that have hyper links embedded in them. It consists of tags embedded in the text of a 
document with HTML. We can build web pages or web documents. it is basically a formatting language 
and not a programming language. The browser reading the document interprets mark up tags to help 
format the document sequent display to a reader. HTML is a language for describing structured 
documents. HTML is a platform independent. WWW (World Wide Web) pages are written using HTML. HTML 
tags control in part the representation of the WWW page when view with web browser. The browser 
interprets HTML tags in the web document and displays it. Different browsers show data differently. 

Examples of browsers used to be web pages include:

  - Netscape
  - Internet Explorer
  
##### Structure of an HTML Document:
An HTML document consists of text, which defines the content of the document, and tags, which 
define the structure and appearance of the document. The structure of an HTML document is simple, 
too, consisting of an outer <html> tag enclosing the document header and body:

The basic structure of an HTML document

```html
<Html>
<Head>
<Title>Barebones HTML Document</title>
</head>
<Body>
This illustrates, in a very <I>simple </I>way,
</body>
</html>
```

Each document has  a head and a body, delimited by the  <head> and  <body> tags.
The head is where you give your HTML document a title and where you indicate other parameters the 
browser may use when displaying the document. The body is where you put the actual contents of the 
HTML document. This includes the text for display and document control markers (tags) that advise the browser how to display the text.

#### JDBC
**JDBC** (Java Database Connectivity) is an API developed by Sun Microsystems that
provides a standard way to access data using the Java programming language. Using JDBC,  an 
application can access a variety of databases and run on any platform with a Java Virtual Machine.

It isn't necessary to write separate applications to access different database systems (Oracle
and Sybase, for example). Using JDBC allows you to write one application that can send SQL 
statements to different database systems. SQL is the standard language for accessing  relational 
databases.

The JDBC API defines a set of Java interfaces that encapsulate major database functionality, such 
as running queries, processing results, and determining configuration information.  Because  JDBC  
applications  are  written  in  Java,  applications  work  on  any platform.

The JDBC API makes it possible to do three things:
1.  Establish a connection with a database or access any tabular data source
2.  Send SQL statements
3.  Process the results


#### JDBC Drivers
Today, there are four types of JDBC drivers in use:
1. Type 1: JDBC-ODBC bridge
2. Type 2: partial Java driver
3. Type 3: pure Java driver for database middleware
4. Type 4: pure Java driver for direct-to-database

In  this  project  we  are  using  Type4  driver  which  provides  best  database connectivity for
internet based application.

##### Type 4: Native-Protocol/All-Java Driver:
The native-protocol/all-Java driver (JDBC driver type 4) converts JDBC calls into the
vendor-specific database management system (DBMS) protocol so that client applications can 
communicate directly with the database server. Level 4 drivers are completely implemented in
Java to achieve platform independence and eliminate deployment administration issues.

![alt text](https://github.com/apuroop-apz/bachelorsMiniProject/blob/master/figures/fig2.png)

##### Web Application Archives:
Web clients are packaged in web application archives. In addition to web components, a web application archive usually contains other files, including the following:
1.  Server-side utility classes (database beans and so on).
2.  Of the these classes conform to the JavaBeans component architecture
3.  Static Web content (HTML, image, and sound files, and so on).
4.  Client-side classes (applets and utility classes).

The top-level directory of a WAR is the document root of the application. The document root is JSP 
pages, client-side classes and archives, and static Web resources are stored.
The document root contains a subdirectory called WEB-INF, which contains the following files and 
directories.
a) web.xml: The Web application deployment descriptor
b) Tag library descriptor files.
c) Classes: A directory that contains server-side classes: servlets, utility classes, and JavaBeans components.
d) Lib: A directory that contains JAR archives of libraries (tag libraries and any utility libraries called by server-side classes).

War file is created like this way

**Jar cvf *archiveName*.war**

### Oracle
#### INTRODUCTION
##### Oracle Tables
Oracle stores records relating to each other in a table.  Different tables are created for
the various groups of information. Related tables are grouped together to form a database.

##### Primary Key
Every table in oracle has a field or a combination of fields that uniquely identifies each
record in the table. The Unique identifier is called the Primary Key, or simply the Key. The 
primary key provides the means to distinguish one record fromall other in a table. It  allows the 
user and the database system to identify, locate and refer to one particular record in the database.

##### Relational Database
Sometimes all the information of interest to a business operation can be stored in one
table. Oracle makes it very easy to link the data in multiple tables. Matching an employee to the 
department in which they work is one example. This is what makes oracle a relational database 
management system, or RDBMS. It stores data in two or more tables and enables  you to define 
relationships between the table and enables you to define relationships between the tables.

##### Foreign Key
When a field is one table matches the primary key of another field is referred to as a
foreign key. A foreign key is a field or a group of fields in one table whose values match those of 
the primary key of another table.

##### Referential Integrity
Not only does Oracle allow you to link multiple tables, it also maintains consistency between them. 
Ensuring that the data among related tables is correctly matched is referred to as maintaining 
referential integrity.

##### Data Abstraction
A major purpose of a database system is to provide users with an abstract view of the
data. This system hides certain details of how the data is stored and maintained.

Data abstraction is divided into three levels.
1.  **Physical level**:  This is the lowest level of abstraction at which one describes how the data are actually stored.
2. **Conceptual Level**:  At this level of database abstraction all the attributed  and what data are actually stored is described and entries and relationship among them.
3.  **View level**:  This is the highest level of abstraction at which one describes only part of the database.

#### Advantages of RDBMS
1. Redundancy can be avoided
2. Inconsistency can be eliminated
3. Data can be Shared
4. Standards can be enforced
5. Security restrictions ca be applied
6. Integrity can be maintained
7. Conflicting requirements can be balanced
8. Data independence can be achieved.

#### Disadvantages of DBMS
A significant disadvantage of the DBMS system is cost.   In addition to the cost of
purchasing of developing the software, the hardware has to be upgraded to allow for the extensive 
programs and the workspace required for their execution and storage. While centralization reduces 
duplication, the lack of duplication requires that the database be adequately backed up so that in 
case of failure the data can be recovered.

### Apache Tomcat Server
Apache Tomcat is a web container developed at the Apache Software Foundation. Tomcat implements the 
java server pages specifications from the Sun Microsystems. Tomcat is a web server that supports 
servlets and JSPs. The accompanying Tomcat Jasper compiler compiles JSP’s into servlets.

The Tomcat Servlet engine is often used in combination with Apache HTTP server or other web 
servers.  Tomcat is cross  platform,  running on  any operating system that  has Java
Runtime environment.

## Design & Implementation
### Requirements
#### Software Requirements
1. GUI Tools      : Java, JSP
2. Server         : Apache Tomcat Server 5.1
3. Database       : Oracle9i

#### Hardware Requirements
1. Operating System    : Windows7
2. RAM Size            : 512MB
3. Hard Disk           : 80GB

### Database design
The most  important  aspect  of the system  is  data design.  The data must  be organized according to the system requirements.
The database approach is to store and organize the data in the developing the system.
The database is an integrated collection of data stored in different types of tables.

Some general objectives in establishing a database are as follows
1.  Integrating all data.
2.  Incorporate updations easily.
3.  Provide data security from unauthorized users.

| S.no | Column Name | Data Type | Null able | Constraint |
|:----:|:-----------:|:---------:|:---------:|:----------:|
| 1 | URL | Varchar2 | NO | PK |
| 2 | Count | Number | NO | -- |
**Table1: Keyword Database**

### Modules
#### Search Engine Module:
Search Engine takes the search String which has been entered by user and parses the
query string and generates the search keywords. The keywords are passed to the database as query 
string and get the results. Then the results are displayed based on page ranking.

#### Admin:
In admin module we design the administrator activities like uploading the projects into
database, modifying the database, view the project list existing in database and if admin wish to 
delete project admin can delete the project from database.

#### User:
In user module user can search for the projects by typing keyword if the keyword is
matching with project title or project description then those projects are listed to user from  
that list user can download abstract, documentation or code from the server directly.

#### Page Rank
A specific page's relevance ranking for a specific query currently depends on three factors:
1. Its relevance to the words and concepts in the query
2. Its overall link popularity
3. Whether or not it is being penalized for excessive search engine optimization (SEARCH ENGINE).

Essentially, the more incoming links your page has, the better by [2]. Page Rank is a  tricky
concept because it is circular, as follows: Every page on the Internet has a minimum Page Rank 
score just for existing. 85% of this Page Rank is passed along to the pages that page links to, 
divided more or less equally along its outgoing links. A page's Page Rank is the sum of   the   
minimum   value   plus   all   the   Page   Rank   passed   to   it   via   incoming  links.

#### Keyword_Search

This is the most common form of text search on the Web.  Most search engines do their text query and retrieval.


What is a keyword, exactly?  It can simply be any word on a webpage.  For example, I
used the word "simply" in the previous sentence, making it one of the keywords for this particular 
webpage in some search engine's index. However, since the word "simply" has nothing to do with the 
subject of this webpage (i.e., how search engines work), it is not a very useful keyword. Useful 
keywords and key phrases for this page would be "search," "search engines," "search engine 
methods," "how search engines work," "ranking" "relevancy," "search engine tutorials," etc.  Those 
keywords would actually tell a user something about  the subject.

Unless the author of the Web document specifies the keywords for her document (this
is possible by using Meta tags), it's up to the search engine to determine them.  Essentially, this 
means that search engines pull out and index words that appear to be significant. Since search 
engines are software programs, not rational human beings, they work according to  rules established 
by their creators for what words are usually important in a broad range of documents. The title of 
a page, for example, usually gives useful information about the  subject of the page (if it 
doesn't, it should!). Words that are mentioned towards the beginning of a document (think of the 
"topic sentence" in a high school essay, where you lay out the subject you intend to discuss) are 
given more weight by most search engines. The same goes for words that are repeated several times 
throughout the document.

Some search engines index every word on every page. Others index only part of the document. Most 
search engines handle words and simple phrases. In its simplest form, text search looks for pages 
with lots of occurrences of each of the words in a query, stop words aside. The more common a word 
is on a page, compared with its frequency in the overall language, the more likely that page will 
appear among the search results. Hitting all the words in a query is a lot better than missing 
some.

When ranking results, search engines give special weight to keywords that appear:
1.  High up on the page
2. In headings
3. In BOLDFACE
4. In the URL
5. In the title (important)
6.  In the description.
7. In the ALT tags for graphics.
8. In the generic keywords Meta tags.

More weight is put on the factors that the site owner would find it awkward to fake, such
as inbound link text, page title, and description.

#### How sites get into Search Engines

The base case is that spiders crawl the entire Web, starting from known pages and following all 
links, and also crawling pages that are hand-submitted. Google is pretty much like that still. If a 
site has high Page Rank, it is spidery more often and more deeply.

However, search engines are trying to encourage site owners to pay for the privilege of having 
their pages spidery. One advantage is that you can tweak your page to come up higher in their 
relevancy rankings, and then see if your changes worked.

Finally, you can also pay to appear on a search page. That is, your link will appear when someone 
searches on a specific keyword or key phrase. Google does a good job of making it pretty clear 
which results are paid; others maybe do a not-so-good job.

Paid search results are typically all pay-per-click, based on keyword. The advertiser pays the 
search engine vendor a specific amount of money each time an ad is clicked on, this fee having been 
determined by an auction of each keyword or key phrase.

### DFD diagrams
Data flow diagram is a pictorial representation of the system in which flow of data from
one process to another process is described. A Data Flow is composed of
1.   Data movement shown by arrows.
2.   Transformation or process of data shown by named circle or rounded rectangle.
3.   Sources and destination of data represented by named rectangle.
4.   Static storage or data at rest denoted by an open rectangle that is named.

![alt text](https://github.com/apuroop-apz/bachelorsMiniProject/blob/master/figures/fig3.png)

![alt text](https://github.com/apuroop-apz/bachelorsMiniProject/blob/master/figures/fig4.png)

#### Data Flow Diagrams are of two types:
##### Physical Data Flow Diagrams:
These are implementation-dependent i.e., they show the actual devices, departments,
people, etc., involved in the system.

##### Logical Data Flow Diagrams:
These diagrams describe the system independently of how it is actually implemented,
they show what takes places, rather than how an activity is accomplished.

The DFD is intended to represent information Flow but it is not a flow chart and is not intended 
decision-making, flow of control, loops and other procedural aspects of the system. DFD is a useful 
Graphical tool and is applied at the earlier stages of requirements analysis. It may be further 
refined at preliminary design stage and is used as mechanism for top-level structural design for 
software.

The DFD drawn first at a preliminary level is further expanded into greater details:
1. The context diagram is decomposed and represented with multiple rectangles.
2. Each of these rectangles may be decomposed further and given as more detailed DFD.
3. Explanation of DFD
  - The context diagrams i.e., level-0 and level-1 diagrams are shown below.

##### Context Diagram:

![alt text](https://github.com/apuroop-apz/bachelorsMiniProject/blob/master/figures/fig5.png)

![alt text](https://github.com/apuroop-apz/bachelorsMiniProject/blob/master/figures/fig6.jpg)

**Level-1 Data Flow Diagram**

### UML diagrams
UML  diagrams  are  the  ultimate  output  of  the  entire  project.  All  the  elements,
relationships are used to make a complete UML diagram and the diagram represents the
system.

#### Class Diagram
A  class  diagram  shows  a  set  of  classes,  interfaces  and  collaborations  and   their
relationships.

![alt text](https://github.com/apuroop-apz/bachelorsMiniProject/blob/master/figures/fig7.jpg)

#### Use-case Diagram
A Use-Case diagram shows a set of use-cases and actors and their relationships. Use-
Case is a pattern of behavior the system exhibits. Each use case is a sequence of related 
transactions  performed  by an  actor  and  the system  in  a dialogue.  An  actor  is someone or
something that must interact with the system under development.

![alt text](https://github.com/apuroop-apz/bachelorsMiniProject/blob/master/figures/fig8.jpg)

#### Activity Diagram
An activity diagram is a flow from activity to activity within a system.

##### Activity Diagram for Admin
![alt text](https://github.com/apuroop-apz/bachelorsMiniProject/blob/master/figures/fig9.1.jpg)

##### Activity Diagram for User
![alt text](https://github.com/apuroop-apz/bachelorsMiniProject/blob/master/figures/fig9.2.jpg)



#### Sequence Diagram
A sequence diagram emphasizes the time ordering of messages.

![alt text](https://github.com/apuroop-apz/bachelorsMiniProject/blob/master/figures/fig9.3.jpg)

## Result Analysis
### Test Cases and Scenarios 
#### Test Model
According  to  Ivar  Jacobson,  Grady  Booch  and  James  Rumbaugh,  the  test model
primarily describes how executable components (such as builds) in the implementation model are 
tested by integration and system tests. The test model can also describe how specific aspects of 
the system are to be tested (e.g., whether the user interface is usable and consistent or whether 
the system’s user manual fulfills its purpose). The test model is a collection of test
cases, test procedures, and test components.

![alt text](https://github.com/apuroop-apz/bachelorsMiniProject/blob/master/figures/fig9.4.jpg)

**The Test Model**

If  the  test  model  is  large,  that is,  if it  contains  a large  number  of test  cases,  test
procedures, and/or test components, it may be useful to introduce packages in the model to
manage its size.


#### Test Cases:
A test case specifies one way of testing the system, including what to test with which
input or result, and under which conditions to test. In practice, what to test can be any system 
requirement or collection of requirements whose implementation justifies a test that is  possible 
to perform and that is not too expensive to perform. The following are common test
cases:
1. A test case that specifies how to test a use case or a specific scenario of a use case. Such a
test case includes verifying the result of the interaction between the actors and the system, that 
the pre- and post conditions specified by the use case is satisfied, and that the sequence of 
actions specified by the use case is followed. A test case based on a use case typically specifies 
a “black box” test of the system (i.e., a test of the externally observable behavior
of the system).
2. A test case that specifies how to test a use-case realization design or a specific scenario of
the realization. Such a test case can include verifying the interaction between the components 
implementing the use case. The test cases based on a use-case realization typically specify a 
“white box” test of the system (i.e., a test of the internal interaction
between components of the system).

![alt text](https://github.com/apuroop-apz/bachelorsMiniProject/blob/master/figures/fig9.5.jpg)

**A test case can be derived from, and thereby traceable to, a use case in the use-case model or a use-case realization in the design model.**

#### System Testing
The testing phase is an important part of software development. It is the process of
finding process and missing operations and also a complete verification to determine whether the 
objectives are met and the user requirement are satisfied.

##### Software testing is carried out in three steps:
The first includes unit testing, where in each module is tested to provide its correctness, 
validity and also determine any missing operations and to verify whether the objectives have been 
met. Errors are noted down and corrected immediately. Unit  testing is the important and major part 
of the project. So errors are rectified easily in particular module and program clarity is 
increased. In this project entire system is divided into several modules and is developed 
individually. So, unit testing is conducted to individual modules.

The second step includes Integration testing. It need to be case, the software whose modules when 
run individually and showing perfect results, will also show perfect results when run as a whole. 
The individual modules are clipped under this major module and tested again and verified the 
results. This is due to poor interfacing, which may results in data being lost across the 
interface. A module can have inadvertent, adverse effect on any other or on the global data 
structures, causing serious problems.

The final step involves validation and testing which determines which the software functions as the 
user – expected. Here are some modifications were. In the completion of the
project it is satisfied fully by the end user.

##### Software Testing Techniques:
Software Testing is a critical element of software quality assurance and represents the
ultimate review of specification, designing and coding.

**Testing Objectives**
1. Testing is process of executing a program with the intent of finding an error.
2. A good test case design is one that has a probability of finding an as yet undiscovered error.
3. A successful test is one that uncovers an as yet undiscovered error.

These above objectives imply a dramatic change in view port. Testing cannot show theabsence no defects, it can only show that software errors are present.

#### Test Case Design
Any Engineering product can be tested in one of two ways.

- **White Box Testing**: This testing is also called a Glass Box Testing. In this testing, by knowing 
the specified function that a product has been designed to perform the test can be conducted that 
demonstrates each function is fully operation at the same time searching for errors in each 
function. It is a test case design method that uses the control structure of the procedural design 
to derive test cases.  Basis path testing is a white box testing.

**Basis Path Testing**:
  1. Flow Graph Notation
  2. Cyclamatic Complexity
  3. Deriving Test Cases
  4. Graph matrices.

**Control Structure Testing**:
  1.  Condition Testing
  2.  Data flow Testing
  3.  Loop testing.

- **Black Box Testing**: In this testing by knowing the internal operation of a product, tests
can be conducted to ensure that “all gears mesh” , that is the internal operation performs 
according to specification and all internal components have been adequately exercised. It 
fundamentally focuses on the functional requirements of the software.

The steps involved in black box testing case design are
  1.  Graph based testing methods
  2.  Equivalence partitioning
  3.  Boundary value Analysis
  4.  Comparison testing

#### Software Testing Strategies:
A software testing strategy provides a road map for the software developer. Testing is a set of 
activities that can be planned in advance and conducted systematically. For this reason a template 
for software testing a set of steps into which we can place specific test case design methods 
should be designed for software engineering process. Any software testing strategy
should have the following characteristics.

1. Testing begins  at  the module level  and  works  “outward”  toward  the integration  of the entire computer based system.
2. Different testing techniques are appropriate at different points in time.
3. The developer of the software and an independent test group conducts testing.
4. Testing and Debugging are different activities but debugging must be accommodated in  any testing strategy.

**Unit Testing**:

Unit testing focuses verification efforts is smallest unit in software design(module)
1.  Unit test considerations.
2.  Unit test procedures.

**Integration Testing**:

Integration  testing is  a  systematic  technique  for  constructing the  program  structure  while
conducting  tests  to  uncover  errors  associated  with  interfacing.  There  are  two  types  of
integration testing.

**Top-Down Integration**:

Top down Integration is an Incremental approach to construction of
program structures.Modules are integrated by moving downwards throw the control hierarchy beginning 
with the main  control module.

**Bottom-Up Integration**:

Bottom up integration as its name implies, begins construction and testing 
with automatic modules.

**Regression Testing**:

In this contest of an integration test strategy, regression testing is the re- 
execution of some subset of test that have already been conducted to ensure that changes have
not propagate unintended side effects.

### Validation
At  the  culmination  of  integration  testing,  software  is  completely  assembled  as  a
package; interfacing errors have been uncovered and corrected, and a final series of software tests 
– validation testing– may begin. Validation can be done in many ways. But a simple application is 
that validation succeeds when software functions in a manner that can be reasonably expected by the 
customer.

Reasonable expectation is defined in the software requirement specification– a document that 
describes all user– visible attributes of the software. The specification  contains
a section called a “Validation Criteria”.


#### Validation Test Criteria:
Software validation is  achieved through a series  of Black-Box  tests  that demonstrate
conformity with requirement. A test plan outlines the classes of tests to be conducted, and a test 
procedure defines specific test cases that will be used in an attempt to uncover errors in 
conformity with requirements. Both the plan and procedure are designed to ensure that all 
functional requirements are satisfied; all performances requirements are achieved; documentation is 
correct and human–engineered; and other requirements are met.

After each validation test case has been conducted, one of the two possible conditions exist:
1. The function or performance characteristics confirm to specification and are accepted.
2. A deviation from specification in uncovered and a deficiency list is created.

Deviation or Error discovered at this stage in a project can rarely be corrected prior to scheduled 
completion. It is often necessary to negotiate with the customer to establish a method for 
resolving deficiencies.

##### Configuration Review:
An important element of the validation process is a configuration review. The intent of the review 
is to ensure that all elements of the software configuration have been properly developed, are to 
be catalogued, and have the necessary detail to support. The maintenance phase of the software 
cycle. The configuration review sometimes called an audit.

##### Alpha and Beta Testing:
It is virtually impossible for a software developer to see how the customer will really use a 
program. Instructions may use may be misinterpreted, strange combination of data may be regularly 
used; and output that seemed clear to the tester may be unintelligible to a user in
the field.

When custom software is built for one customer, a series of acceptance tests are
conducted to enable the customer to validate all requirements.

Conducted by the end user rather than the system developer, an acceptance test can range from an 
informal “test drive” to a planned and systematically executed series of tests. In fact, acceptance 
testing can be conducted over a period of weeks, months, thereby uncovering cumulative errors that 
might degrade the system overtime.

If software is developed as a product to be used by many customers, it is impractical to perform 
formal acceptance tests with each one. Most software product builders may use a process called 
alpha and beta testing to uncover errors that only  the end user seems to be able
to find.

A customer conducts the alpha test at the developer’s site. The software is used in a
natural setting with the developer “loosing over the shoulder” of the user and recording error and 
usage problems. Alpha tests are conducted in controlled environments.

The beta test is conducted at one or more customer sites at the end of the user of the software. 
Unlike alpha testing, the developer is generally more present.

Therefore the beta test is a “live” application of the software in an environment that cannot be 
controlled by the developer. The customer records all the problems that are encountered during the 
beta testing and reports these to developer at regular intervals. As a result of problems reported 
during beta tests, the software developer makes modification and then prepares for the release of the software product to the entire customer base.

### Results
#### Home Page
![alt text](https://github.com/apuroop-apz/bachelorsMiniProject/blob/master/figures/fig99.1.jpg)

#### Login Page
![alt text](https://github.com/apuroop-apz/bachelorsMiniProject/blob/master/figures/fig99.2.jpg)

#### Register Page
![alt text](https://github.com/apuroop-apz/bachelorsMiniProject/blob/master/figures/fig99.3.jpg)

#### View Projects
![alt text](https://github.com/apuroop-apz/bachelorsMiniProject/blob/master/figures/fig99.4.jpg)

#### Download files
![alt text](https://github.com/apuroop-apz/bachelorsMiniProject/blob/master/figures/fig99.5.jpg)

## Conclusion

This is fully computerized, which removes drawbacks of existing system and stores
the details of projects. This type of application is accurate, user friendly and provides 
information in less time. This system is developed with an eye towards the future and can easily be 
updated with new features, as needed.

In spite of maintaining the records or files, the projects can be updated in the website. From 
anywhere and whenever necessary the user can search and view the project. If required
the user can download the files from the website.

## References
- “The Complete Reference Java 2, Fifth Edition” by Patrick Naughton and Herbert Schildt.
- “Software Engineering: A Practitioner’s Approach, Fourth Edition” by Pressman R.S.
- “Software Engineering Concepts” by Richard E Fairely.
- “Core JAVA Volume II – Advanced Features” by Cay S. Horstmann, Gary Cornell.
- “Java Network Programming” by Elliotte Rusty Harold.
- “java.security Package” from java.sun.com

