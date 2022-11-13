# CLASS 9 READING NOTES



### HTML FORMS


**Why are forms so important in web development?**
Because it is one of the main points of interaction between a user and a website or application.



**When designing a form, what are some key things to keep in mind when it comes to user experience?**

It is important to make a quick mockup beforehand to help you define the right set of data you want to ask your user to enter. It is also very important to remember that the bigger the form, the more chances for the user to get frustrated and quit before finishing it, so ask only for the data you absolutely need.



**List 5 form elements and explain their importance.**

1. Form: this is the initial element you will need to use to create a form. It is a container element, just like ‘section’ or ‘footer’, but specifically for containing forms. 

2. Label: this element is the formal way to define a label for an HTML widget and it’s the most important element when building an accessible form.

3. Input: this element is exclusively used to create a field for email addresses. 

4. Textarea: this is the input field for messages and it’s a multiline text field.

5. Button: this element is used to create the actual button that will allow the user to send or submit their data once they have filled our the form.


### LEARN JS


**How would you describe events to a non technical friend?**

Events are actions that happen in the system you are programming, which the system tells you about so your code can react to them. For instance, if the user clicks on a button on your page, you surely want for the page to have a reaction and display whatever that button is supposed to trigger. 


**When using the ‘.addEventListener()’ method, what 2 arguments will you need to provide?**

You will need to provide the name of the event and the function to handle the event. 



**Describe the event object. Why is the target within the event object useful?**

An event object is a parameter that is automatically passed to event handlers to provide extra features and information. ‘Target’ is a property that alway references the element the event occurred upon (sort of like ‘this’ in objects literals).



**What is the difference between event bubbling and event capturing?**

In the capturing event the browser checks to see if the element's outer-most ancestor has a click event handler regiteres on it and runs if so. Then it moves on to the next element inside < html > and repeats the same procedure until it reaches the direct parent of the element that was actually clicke. 

In the bubbling phase, on the other hand, the browser checks to see if the direct parent of the clicled element has a click event handler registered and runs it if so. Then it moves to the next immediate ancestor element and does the same with the following ones until it reaches the < html > element. 

