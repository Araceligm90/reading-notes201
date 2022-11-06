# RCLASS 7 READING NOTES


### Domain Modeling

**Explain why we need domain modeling.**

Domain modeling is the process of creating a conceptual model in code for a specific problem.  



### HTML table basics

**Why sould tables not be used for page layouts?**

Mainly for three reasons:

1. Layout tables reduce accessibility for visually impaired users. Screen readers will think that all the information is somehow connected when it's not.

2. Table layouts involve more complex markup structures that can result in the code being harder to write, maintain and debug.

3. Tables are not automatically responsive, which means that tables are sized according to their content by default and therefore you will need to put the extra work to get the table layout to effectively work across different devices.


**List and describe three different semantic HTML elements used in a < table >**

1. < th > stands for 'table header'.
2. < tr > stands for 'table row'.
3. < td > stands for 'table data'.



### Constructors

**What is a constructor and what are some advantages to using it?**

A constructor allows you to store the data of various object literals in a single piece of code without having to create them whole individually and type their properties for each of them.



**How does the 'this' differ when used in an object literal versus when used in a constructor?**

Within an object, the 'this' only refers to the data of said object, however when you create a constructor the 'this' is applied to the existing and newly created data within the constructor.


### Object prototypes using a constructor.


**Explain prototypes and inheritance via an analogy from your previous work experience.**

In the hotel where I used to work here in Grand Cayman we were trying to get the Forbes 5 Star qualification, which means you are the best of the best. Each of the workers at the Front Desk, each object, had to perform in a certain way so we could get those 5 stars, but then one day one of the employees does a crapy job and we end up not getting our stars, just because of his/her performance, which was crappy and now has been passed into all of the team, like if we were a whole.




