# CLASS 13 READING NOTES


### Local storage and how to use it on websites


**Why whould a developer use local storage for a web application?**

The web information is loaded faster if the data has been stores locally. Additionally, if a user opens a web and the call to the API fails for some reason, the browser would still display information.


**What information should not be stored in local storage?**

Personally Identifiable Information (PII), authentication tokens, user locations and API keys, among others, shouldn't be stored in the local storage as it can be accessed by malicious actors. 


**Local sstoral ca store what type of data? How would you convert it to that type before storing?**

It can only store strings. This can be changed by using the 'JSON.stringfy()' and 'JSON.parse()' methods.

