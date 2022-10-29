# READING NOTES 5


**Reflections**

The below topic matters beucause it is a valiable addition to the basics that we already know from HTML and CSS. This helps us display our content in a more unique way. 



### HTML MEDIA 


**What is a real world use case for the 'alt' attribute being used in a website?**

The 'alt' is meant to describe the image in one of few words in case it doesn't appear correctly or for screen readers.



**How can you improve accessibility of images in an HTML document?**

1. If the image is not part of the content, don't add it in HTML but in CSS as a background image. Screen readers shouldn't wase time reading it.

2. If the image provides key information, provide it in the main text or provide the same information in a brief 'alt' text. However do not provide the same information twice as the screen reader will ready it twice.

3. If the image is put inside an < a > tag, to turn it into a link, an accessible link text needs to be provded too. It can be done by writing inside the same < a > element, or inside the image's attribute.

4. Avoid as much as you can putting text into images as these are not readable by screen readers.


**Provide an example of when the 'figure' element would be useful in an HTML document.**

When there are multiple images and captions that describe them in a web page. It would be difficult to understand which caption belongs to which image. However if you use the < figure > and < figurecaption > elements, it is clear for screen readers.


**Describe the difference between a 'gif' image and a 'svg' iamge. Pretend you are explaining it to an elder in your community.**

A 'gif' format is normally for simple images or animations. However 'svg' format is a digital image formed by dependent geometrical objects, which is great for icons, diagrams, etc which must be drawn accurately at different sizes.


**What image type would you use to display screenshot on your website and why?**

I would use 'png' as it reprocudes images precisely and it is supported by more browsers.



###LEARN CSS


**Describe the difference between foreground and background colors of an HTML element. Pretend you are talking to someone with no technical knowledge.**

Most of times an HTML element is going to include text. So you would have the text at the foreground and then its bakground. The foreground color, which is modified with the 'color' property, will then modify the color of the text, while the 'background color' property will modify the boz behind the text.


**Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?**

First of all I would go to Google and search for color combinations for websites and start from there. Normally you get about 4-6 color combinations. I would use these colors to style the background, the background of the heading, the navigation bar, etc. I would also change the font, so it doesn't display good old and boring Times New Roman. I would modify the size of text depending on the content. Even though headings are bigger than the rest of the text, you may want it to display bigger or samaller. I would highlight parts of the content which are important by giving it a different size than the rest of the text, etc. There are infinite ways of making a web site look beautiful with CSS.


**What should you consider when choosing fonts for an HTML douments?**

That some fonts may not be available depending the user's operating system and browser. That is why you should always use fonts that are predictable, such as 'serif' 'sans-serif' and 'monospace'. A good option is to use font stacks, which are stacks that include different fonts, in case one of them is not supported, it will move to the next one.


**What do 'font-size', 'font-weight' and 'font-style' do to HTML text elements?**

The 'font-size' is the size of the text and it is normally set to 16px accross browsers. It is inherited from the element's parent element.

'Font-weight' will make the text bolder. It has a few variants available, however almost always you will use 'normal' and 'bold'.

'Font-style' will italize your text. There is 'normal', 'italic' and 'oblique'.


**Describe two ways you could add spacing around the characters displayed in an 'h1' element.**

By using the 'letter-spacing' and 'word-spacing' properties.