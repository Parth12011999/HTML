# Task
<h1 align="center"> Assignment 1 </h1>
<h2 align="center"> HTML </h>
<br><hr>

<p align="left">1.	Are the HTML tags and elements the same thing?</p>
<p align="left">
ANS. HTML tags are the labels or entity used to create web pages. Each tags provides special meaning for the content.
<br>
Wherelse, HTML element is combination of starting tag, content, and ending tag. Mostly website content is written into start tag and an end tag.
</p>

<br><hr>
<p align="left">2.	What are tags and attributes in HTML?</p>
<p align="left">
Ans. HTML tags are the labels or entity used to create web pages. Each tags provides special meaning for the content.
<br>
HTML attributes is used to define character of the HTML element. It is always placed in starting tag of an element and used to provide additional properties to the element.
</p>

<br><hr>
<p align="left">3.	What are void elements in HTML?</p>
<p align="left">
Ans. There is a special group of elements that only have start tags and does not contain any content within it, these elements are called void elements. Void elements doesn’t have ending tags and can only have attributes but do not contain any kind of content. These elements can have backslash before ending of start tag but that is completely optional.
</p>

<br><hr>
<p align="left">4.	What are HTML Entities?</p>
<p align="left">
Ans. HTML provides some method to display reserved characters. Reserved characters are those characters that are either reserved for HTML or those which are not present in the basic keyboard. For instance, ‘<‘ is reserved in HTML language. Sometimes this character needs to display on the web page which creates ambiguity in code. Along with these are the characters which are normally not present in basic keyboard ( £, ¥, €, © ), etc. HTML provides some Entity names and Entity numbers to use these symbols. Entity names are case-sensitive. Entity number is easy to learn.
<br>
Example: &entity_name; or &#entity_number; and  A character entity looks like this: To display a less than sign (<) we must write: &lt; or &#60; 
</p>

<br><hr>
<p align="left">5.	What are different types of lists in HTML?</p>
<p align="left">
Ans. There are four types of list in HTML:
1 Ordered List: An ordered list starts with the ol tag. Each list item starts with the li tag. 
<br>
Example:
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
<br>
2 Unordered List: An unordered list starts with the ul tag. Each list item starts with the li tag.
<br>
Example:
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
<br>
3 Description List:  Description list is a list of terms, with a description of each term. The dl tag defines the description list, the dt tag defines the term (name), and the dd tag describes each term.
<br>
Example:
<dl>
  <dt>Coffee</dt>
  <dd>- black hot drink</dd>
  <dt>Milk</dt>
  <dd>- white cold drink</dd>
</dl>
<br>
4 Nested List: Nested list doesn’t have fixed tag to define a list. It is combination of all the list to each other that we have describe above.
<br>
Example:
<ol>
	<li>Coffee
<ul type=”square”>
  <li>Coffee</li>
  	<dd>Description</dd>
</ul>
</li>
</ol>
</p>
