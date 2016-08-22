# Lab - Page Exploration

Modern web browsers include a variety of developer tools to allow us to examine the transmission, structure and functioning of files.   In class, we'll use using the Chrome browser and the [Chrome Developer Tools](https://developer.chrome.com/devtools).

We'll use a couple of those tools in this lab to examine a few pages;  our goal is to **start** understanding the Document Object Model and the transmission of files. 

****

###Step 1
Using the Chrome browser, navigate to [https://it202.github.io/lab-page-exploration/page1.html](https://it202.github.io/lab-page-exploration/page1.html).

Notice that not all of the text is displayed in the same way.

Right-click on some blank part of the window, and select the context-menu option to view the page source.  This is the contents of the file that was delivered to the browser from the server.

Now, right-click on the "Hello World" text, and select the context-menu option to inspect that *element*.  The Developer Tools pane will open to the *Elements* tab, and the selected element will be highlighted.

Notice that the element includes more text than simply the words "Hello World."   What do you see?

At the bottom of the Elements pane, you'll see a listing of the element and its *ancestor* elements.  What happens in the document window when you mouse over each item in the list?

You previously noted differences in how some of the text was displayed.  What's different about the element that contains "Hello World" and the element that contains "Hey, here's some text!" ?


###Step 2
Keep the first page open, and in a new tab, navigate to [https://it202.github.io/lab-page-exploration/page2.html](https://it202.github.io/lab-page-exploration/page2.html).

No text on this page, just an image.

View the source of this page, then inspect the image element.   Note again the hierarchy of elements on the page.

Now let's look at another tab on the Developer Tools.   Click the *Sources* tab to see a nested listing of all the files involved in displaying this page. 


****
##Resources

#Chrome Developer Tools
[https://developer.chrome.com/devtools](https://developer.chrome.com/devtools)

#Document Object Model
[https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)

[https://en.wikipedia.org/wiki/Document_Object_Model](https://en.wikipedia.org/wiki/Document_Object_Model)

[http://www.w3schools.com/js/js_htmldom.asp](http://www.w3schools.com/js/js_htmldom.asp)


