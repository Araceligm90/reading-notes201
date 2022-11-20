# CLASS 11 READING NOTES


### AUDIO, VIDEO AND IMAGES


**Explain how the ability to use video and audio on the web has evolved since the early 2000s.**

In the early 2000's plugin-based techologies like Flash and Silverlight were needed to reproduce audio and video in web sites. Both of them used to have security and accessibility issues and are now obsolete. Nowadays we have a most convenient way of adding video and audio to our webpage with the < video > an < audio > elements in HTML.


**Describe the use of 'src' and 'controls' attributes in the 'video' element.**

The 'src' attribute contains a path tot he video you want to include.

The 'controls' attribute allows you to add control buttons to the file, such as play, stop, volume control, etc.


**Why is important to have fallback content inside the < video > element?**

It is important to have it because some browsers could fail to reproduce the video or audio embeded, and by adding it you provide an additional way to access media file.



### A COMPLETE GUIDE TO GRID


**How does the Grid layout differ from Flex?**

Grid is designed for two-dimensional layouts (rows and columns at the same time), while Flex is designed for layouts in one dimension (either a row or a column).


**Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.**

Grid containers are grid items placed inside columns and rows. It's the direct parent of all the grid items.

The grid item is every box inside of the grid container. The children of the grid container.

And the grid line are the dividing lines that create the strcuture of the grid.


### REPONSIVE IMAGES


**Besides making a site visually appealing across different screen sizes, why should developers make images responsive?**

Using big images on narrow screens such as chellphones waste bandwith and of course the aesthetics.



**Define the following < img > attributes 'srcset' and 'sizes'. Write an example of how they are used.**

Srcset defines the set of images the browser will be bale to choose between and what size each image is. Each set of image information is separated from the next one by a comma. And for each one we write the filename, a space and the image's intrinsic disth in pixels.

Sizes, on the other hand, defines a set of media condition and indicates what image size would be best to choose, when certain media conditions are true. In this case we write the media condition, a space and the width of the slot the image will fill when the media condition is true.


**How is srcset more helpful for responsive images than CSS or JavaScript?**

When the brower starts to load a page, it preloads any images before the main parser starts to load and interpret the page's CSS and JavaScript.

