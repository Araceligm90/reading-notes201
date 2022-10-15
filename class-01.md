# CLASS 1 READING NOTES

### GETTING STARTED


**Reflections**

The below information are the foundations of what we will be learning in Code 201, as well as a good recap of what we did on 102. It is important to be already familiar with the below topics in order to get into deeper levels of code.


**How does HTTP send data between computers?**

In order for a user to be able to open a website and see its content, once the address is entered on the browser, the latter goes to the DNS (Domain Name System) server, which is like an address book for websites, and finds the real address of the server where the website he or she is trying to open lives on. Then the browser sends an HTTP (Hypertext Transfer Protocol) request message to the server asking to send a copy of the website to the user trying to access it. In order for this to happen there must be an internet connection that uses TCP/IP, which are communication protocols that define how data travels across the internet.

If the client’s request is approved by the server, it starts sending small amounts of data, called ‘data packets’, which are the website’s files. The browser then puts all the data pieces together and TA-DA, you can now see the website.  


**In which order are the component files parsed?**

The first file that the browser parses is the HTML. Once there, the browser checks for any < link > element references to an external CSS stylesheet and then for any < script > element references to JavaScript files, and when these are found the browser parses them.

The browser then generates an in-memory DOM (Document Object Model) from the parsed HTML, generates an in-memory CSSOM (CSS Object Model) structure from the parsed CSS and executes the parsed JavaScript.

And it is only when these procedures happen that the user can see a website as it looks.


**How can you find images to add to a website?**

Choosing an image should be as easy as typing on Google what you are looking for and saving into your computer the image you like the most. However most images on the web (and Google) are copyrighted, which means that if you were to just take them and publish them in your website, you would be violating copyright. To avoid that, use Google's license filter. You can do so by clicking on the Tools button, then Usage Rights option and choose the Creative Commons Licenses.


**How do you create a String vs a Number in Javascript?**

It is very easy to differentiate a string from a number: strings are always enclosed in single quote marks, while numbers don’t have anything around them.

        let = ‘35’ --> is a string 
        let = 35 --> is a number


**What is a variable and why are they important in JavaScript?**

Variables are basically containers that store values. They are declared by using the ‘let’, ‘const’ or ‘var’ keywords followed by the name you would like to give to said variable.

After declaring the variable, you can then give it a value, or you can do both operations at the same time. Then you can retrieve the value by calling the variable name followed by a semicolon.

        Declaring a variable --> let helloWorld;
        Giving a value to the viarible --> helloWorld = “earth”;
        Doing both at the same time --> let helloWorld = “earth”;
        Calling the value --> helloWorld;

After assigning a value to a variable, you can change it later in the code, unless it is a ‘const’ variable, which will remain constant.

        let helloWorld = “earth”;
        helloWorld = “mars”;

Variables are necessary to make programming interesting and dynamic. If we weren’t able to change values, websites would be static and boring.


### INTRODUCTION TO HTML


**What is an HTML attribute?**

Attributes are related to HTML elements and they contain extra information about said elements, however this information will never appear in the content.



**Describe the anatomy of an HTML element**

And HTML element must have an oppening tag, the content in between and then a closing tag as displayed in the image below:

![HTML element example](HTML_element_structure.png)


**What is the difference between the < section > and < article > element tags?**

The < article > tag is to be used when the information provided within it does make sense on its own and doesn't need to be related to any other part of the page (e.g., a single blog post).

The < section > tag is similar to te above, however it is used to group together a part of the page that encloses different pieces of information interlated. It is s standard to begin each section with a heading.

Note that an < article > tag can be broken into different < section > tags and viceversa depending on the content.


**What elements does a 'typical' website include?**

A typical website would normally include the following elements:

    1. Header: located at the top of the website, in this section you can find the title, logo and perhaps a tagline. This usually stays the same from one webspage to another.

    2. Navigation bar: here the user normally finds the menu buttons, links or tabs. Like the header, this content usually stays the same from one webpage to another.

    3. Main content: here the user finds the information that the webpage will contain, whichever it is. This is the one part of the website that will definitely vary from page to page.

    4. Sidebar: here one finds links, quotes, ads, etc. The information in this part is normally related somehow to the main content. However there are also cases where the user can find a secondary navigation system. 

    5. Footer: this is a strip at the bottom of the page that normally contains fine print, copyright notices, contact info, etc.


**How does metadata influence Search Engine Optimization?**

The head of an HTML document is the part that is not displayed in the web browser, however it contains important information about it, such as the title, links to CSS and other metadata.

It is interesting to use a description that includes keywords relating to the content of the page in the head, as this may make the page appear higher in relevant searches peformerd in search engines. This is known as Search Engine Optimization or SEO.


**How is the < meta > HTML tag used when specifying metadata?**

The < meta > element is used within the head and it can include different kinds of information:

        This will make your web page capable of displaying any language: 

        <meta charset="utf-8" /> 
        
        
        This will provide the name of the author of the web page:

        <meta name="author" />

        And this will provide information about the content of the website:

        <meta content="description" /> 

*Please note that the < meta > tag is self closing.*


### Miscellaneous


**What is the first step to designing a website and what's the most important questions to answer?**

Before you start coding, the first thing you should do is planning ahead the kind of website you would like to have and its functionality. You should first ask yourself *what do I want to accomplish?*.

This is called *project ideation* and is a necessary first step to reach your goal.


**Why should you use an < h1 > element over a < span > elemento to display a top level heading?**

The < h1 > element is the top level heading of your page and it has semantic value. You can virtually make pretty much any element look like a top level heading, for example a < span > element, by styling it with a bigger and bolder font, however it wouldn't have a semnatic value.

HTML should be coded to represent the information that will be provided.


**Describe two things that require JavaScript in the browser.**

- Animate images and control multimedia.
- Store useful values inside variables.
- Running code according to stablished parameters.

**How do you add JavaScript to an HTML document?**

You can add JS with a < script > tag at the end of the < body >.
