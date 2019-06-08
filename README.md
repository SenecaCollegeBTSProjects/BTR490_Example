# BTR490_Example

## Team members

### Marcel Jar 
- Github: marceljar 
- Skype: marcel.seneca
- Role: C++ programming, testing, and benevolent dictator for life

## Business Description

Most books and websites introducing the C++ language do not have, in a single place, a complete set of source code to illustrate different concepts. Sometimes, examples of source codes are to be found spread accross multiple different web pages, or worse, accross different chapters in books (sometimes with no way to quickly download them). Also, in many cases, the provided code is not complete. I.e., it is just an excerpt of code that cannot be compiled by itself.

In order to fill this perceived gap, we will create a repository a large number of source code. Each source code will illustrate a particular concept. For example, there will be a source code containing the ubiquitous "Hello World" example. Other source code will illustrate how to implement different types of for loops, another one will implement different if/else statements, etc. Each source code will be complete, i.e. it can be compiled without modifications using any standard C++ compiler. Moreover, each source code will follow closely C++ best coding practices, as detailed by Bjarne Stroustrup (creator of C++), and Herb Sutter (lead software archittect for C++ at Microsoft) in http://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines. A README.md file will be included, containing a detailed explanation for each provided source code, as well as a link to it. In addition, each file will contain a descriptive enough name to allow students to download them all, and later browse them by name.

## Use Cases

### Read Example Source Code

#### Brief description (scope)
This use case describes the process of a student opening an example source code from our repository to read.

#### Actors (users)
Students (more broadly, anyone with access to Github).

#### Preconditions
The student has the README file for this repository open on Github.

#### Basic flow
The student reads through a list of links to source code in the README file, searching for an example that contains source code about a topic that he/she is studying. The student then clicks on the link for the source code provided. Github will then redirect the browser to a page displaying the required example source code.

#### Alternate and/or exception flows
The student can also download the entire repository. Then, he/she can search for the desired source code, based on their filenames, using the file explorer tool of his/her choice.

#### Post-conditions
The desired source code is open on the student's browser.

## Technological Choices

### Front-End Technologies

 This project simply features a repository of examples of C++ source code. All that is to run them is a C++ compiler that abides to the **C++ 11 standard**. Any Linux machine should be able to compile and run this code from the terminal using **g++**. Moreover, any Mac OS machine should be able to quickly download **g++** and use it on the terminal as well. For Windows machines, one can download a number of different C++ compilers and/or IDEs such as Visual Studio, Eclipse, Code::Blocks, and many others. No special libraries are required. 

 *Note: For web-dev projects, this sections should describe all technologies that will run on the client's machine (normally the browser). This would include any Front-End frameworks such as Bootstrap, as well as any JavaScript libraries that run on the Front-End such as React, Vue, or Angular. For mobile apps, this would include all technologies that would run on the phones themselves, including the IDEs used to write the apps.*

### Back-End Technologies

For this project, the objective is to have students compiling and running C++ source code. Hence, all code will run natively in their machines. Therefore, no back-end technologies are required.

*Note: For web-dev as well as mobile application projects, this section should describe all technologies that run on the server-side. This almost always include the database. Also, this would include any server-side technologies such as Node.js, C#, PHP (and its frameworks such as Laravel), Python (and its frameworks such as Django and Flask), amongst oters. This should also include the hardware or cloud service that will be running the server (AWS, Digital Ocean, Google Cloud Services, GoDaddy).*

### Application Programming Interfaces (APIs)

Not relevant for this particular project.

*Note: For web-dev, as well as mobile application projects, this section should describe interactions with other websites and/or services. This can include: APIs to collect payment from PayPal/VISA/MasterCard, APIs to collect data from mapping services, APIs to collect methereological data, APIs to allow login using Facebook/Twitter/Google accounts, etc.*
