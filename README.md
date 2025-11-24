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

CSS----------

Basic stlying rules where made up of a selector, property and value. Property and value paris are declarations.

Selectors refer to the HTML elements which the CSS declaration rules apply to essentially what is being selected for the rules.

 "* is the universal selector meaning the declarations will cover entire document

 Type selector will use all elements of a given element type and its syntax si the element name. Eg: h1 is the chosen element so all headings 1 will be affected by the declaration. 

 Class selector will select all elements with given class. A class is just an attribute within an element tag. Syntax in CSS is .className

 Multiple classes can be added to one element and are simply separated by a space within the same speech marks.

 ID selectors work similarly to class selectors but an element can only have one ID. CSS syntax is  #idName

 Selectors can be grouped if two share the same declaration. 
 syntax is selector1, selector2
 Each selector can have its own unique declarations as well they just need to be declared separately. 

 Chaining selectors allows elements with two classes/a class and ID to have the same declarations. syntax is class/id1class/id2

 Some elements can also be selected based on descendant combinations. If an element is indented into another element and they have the correct classes then they can share declaration but an element with the same class as the indented ones won't share the declaration. 

 The colour property can have its value defined by hex or RGB, the same with background colour. 

 A font-family uses speech marks while a generic family name doesn't. A list of these can be generated for the browser to choose from. 

 font-size will set size of the font. 

 font-weight affects how bold the text 

 text-align will align text horizontally within an element, center is an example value. 

 An <img> will by default have the default images height and width but this can bbe adjusted for both either with specific values or with one having specific values and one with auto to proportionately change. 

 Can add CSS to HTML via external where a link is added to the css file in the html head. 

 Can add it internally to the HTML file by placing all selectors and declarations within <style> elements

 inline CSS means it can be added directly one HTML element by placing it into the tag with the style attribute. 

 









