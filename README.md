# htmlLearn

Elements/tags are like containers for content but there are also void elements which don't hold any content. 

within <html> the lang=en defines the attribute of the language of the content within the HTML file

within <head> is where all the meta information for the file.

within <title> tags the title of the page is put and this corresponds to what is named within a browser tab

<meta> tag stores the meta data for eg charset="UTF-8" is the type of encoding.

<p> tags are required to separate content because if all content is put between one set of these tags then everything will be compressed into one paragraph so the resolution is 

<p>paragraph1<p><p>paragraph2<p>

headings such as <h1> are bolder and bigger naturally and number goes higher the heading size goes smaller</h1>

<strong> element buts anything in between it as bold </strong>

nested and indented elements are child elements of a parent element and any element on the same indentation level are sibling elements.

lorem shortcut prints a lot of dummy text

--Lists
An un ordered list is created through <ul> and to create items within this list indented items should have <li> wrapping them 

--Links and images
To create an HTML link an anchor element <a>should be used</a>
Within the opening <a> tag a href (hypertext reference) has to be put in to actually be taken to another page. Doing so opens the page in the same tab 

Using target attribute means that a link can be opened in a new/separate tab. 

the rel (relationship) attribute describes the relationship between the current page and linked document.
noopener: prevents new pag from manipulating original page
noreferrer: prevents new page from knowing where user came from and includes noopener behaviour

Absolute links include the entire path of a web page. Relative links include the path up to the related directory.

<img src="relative or absoulte path of image">: this tag implies void content due to there being an image and src being the "source" attribute.

The alt attribute can be used instead of the src when an image description is needed because the image itself won't load. 




