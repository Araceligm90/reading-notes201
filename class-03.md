# CLASS 3 READING NOTES


**Reflections**

The information below is improtant because focuses on the fundamentals of HTML, CSS and JavaScript, which is imperative knowledge to have in order to become a good software developer. 


### LEARN HTML

**When should you use an ‘unordered list’ in your HTML document?**

When you want to make a list with bullet points instead of numbers, because the order of the list is meaningless. 


**How do you change the bullet style of unordered list items?**

It can be modified by the nesting level of the list item or through CSS.


**When should you use an ‘ordered list’ vs an ‘unordered list’ in your HTML document?**

When the items you are listed have a meaningful order and you want to determine which one goes first, second, etc.


**Describe two ways you can change the number on list items provided by an ‘ordered list’.**

With the ‘reversed’ attribute you can make the numbers go from highest to lower or with the ‘type’ one you can change from numbers to letters, lower case, upper case, etc. 


### LEARN CSS


**Describe the CSS properties of ‘margin’ and ‘padding’ as characters in a story. What is their role in a story titled ‘The Box Model’?**

My name is Araceli and I am the *content* of this story. Surrounding me I have my direct family, who I like to call my *padding* because they make me feel supported and hugged. After them, there are my cousins and uncles, who I won’t speak about today but that draw the *border*-line between close relatives and distant ones. And then you have all those second cousins and great uncles and such, who are *margin*-ally strangers that your mom makes you huge effusively when you see them as a kid even if you don’t want to.


**List and describe the four parts of an HTML elements box as referred to by the box model.**

The first part, located right in the center, is the content. This element content is then 
surrounded by the padding, the border and then the margin, which is the furthest one from the element content. It is called ‘The Box Model’ because these parts are represented as squared boxes. These boxes can be altered using CSS to provide the desired space between the element content and the other elements in the web page. 



### LEARN JAVASCRIPT

**What data types can you store inside of an ‘array’?**

Numbers, strings, objects and other arrays.


**Is the ‘people’ array a valid JS array? If so, how can I access the values stored? If not, why?**

The 'people' array is a valid array because it contains valid data types which are displayed in a correct way. You can access the different elements by specifying the index number.


**List 5 shorthand operators for assignment in JS and describe what they do.**

- ‘x = f()’ → This is an assignment operator that assigns the ‘f’ value to ‘x’.

- ‘x+= f()’ → This is an addition assignment and represents the following ‘x = x + f()’

- ‘x -= f()’ → This is a subtraction assignment and represents the following ‘x = x - f()’

- ‘x *= f()’ → This is a multiplication assignment and represents the following ‘x = x * f()´

- ‘x /= f()’ → This is a division assignment and represents the following ‘x = x / f()’


**Read the code below and evaluate the last expression and explain what the result would be and why.**

The result would be ‘10dog’ because 10 + false equals 10, as false has a value of 0, and then 10 + ‘dog’ returns a string ‘10dog’.


**Describe a real world example of when a conditional statement should be used in a JS program.**

Imagine a website that designs personalized services for men and women. However the services will be different if you are a man or a woman. So when you enter the website, you have to answer the first question, which is ‘are you a male or a female’? IF you click ‘female’ you will be redirected to a specific following page, whereas (ELSE) IF you click ‘male’ you will be redirected to a completely different one.


**Give an example of when a loop is useful in JS.**

When you want a block of code to repeat itself a specific number of times. Instead of rewriting it every time you want it to run, you create a loop and specify how many times it should run for.