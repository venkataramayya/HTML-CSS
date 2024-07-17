# HTML-CSS



   HTML
1. BASIC TAGS
2. FORMATTING TAGS
3. LIST TAGS
4. LINK TAGS
5. image and graphics
6. Audio and video tag
7. table
8. form
9. frame
10. semantic and non-semantic
11. meta
12. programming
==================================================================================
===================================
Attributes of body:
 bg color, text, left margin, top margin, background, title
 FORMATTING TAGS:

 <H1></H1>--> level1
 <H2></H2>--> level2
 <H3></H3>-->level 3
HTML
 <H4></H4>--> level 4
 <H5></H5>--> level 5
 <H6></H6>--> level 6
 ATTRIBUTES OF H1 TO H6
 =======================
 1. ALIGN="LEFT/RIGHHT/CENTER" => IT IS USED TO Specify the alignment. The default is left.
 2.title="..." => It is used to specify tooltip text.
 <marquee></marquee> This tag is used to scroll the text at the top of the text in the browser
 Attributes of <marquee> tag
 =============================
 1. bg color
 2. behavior="scroll/slide/ a"
 scroll amount is used to speed value
 loop=" " It is used to specify how many times it should be scroll
 width=" => specify rjr, marquee width
 heigt=" => It is used to specify marquee height
 hspace=""=> specify horizontal space
 vspace=""=> specify vertical space
 direction="left\right\up\down"=> specify the text direction
 title=" => it is used to specify tooltip text
 FORMATTING TAGS
HTML
===============================
<font></font>==> it is defined to font
<b>..</b>=> it is used to define the bold text
<i>..</..i> it is used to define italic text
<u>..</u>=> it is used to define underline
<br>==> It is used brake line
<center>...</center> => it is used to define center alignment
ATTRIBUTE OF FONT TAGS
==========================
1.face=" ==> It is used to specify the font name
2.size=" => It is used to specify the font size
3.color=" => It is used to specify the text color
FORMATTING TAGS
================
<SUB></sub> ==> It is used to define subscripted text.
<sup></sup>==> it is used to define superscripted text
<del></del>==> it is used to define deleted text.
<strike></strike> ==> It is used to define strike the text
<hr>=> It is used to define horizontal rules
<p> It is used to define the paragraph
<bdo></bdo>=> it is used to define override text direction BDO standard BI direction override
<pre></pre> It is used to define performed text
<progress></progress> => It is used to define progress ber.
<abbr></abbr> => It is used to define the abbreviation of the text
HTML
<adress></adress>It is used to define contact information
Attributes of HHR tag
=========================
color
width
height
size==> It is used to specify thickness.
align="left/right/center"
Attributes of BDO tag
======================
1.dir="ltr/rtl" it is used to specify the text direction
ltr=left to right
rtl=right to left
attributes for <abbr> tag
==============================
1.title=" It is used to specify the tooltip text
Attributes of progress ta
==========================
1.max=" value" => it is used to specify the maximum value of the task.
2. value=" => it is used to specify how much value of the task will be downloaded
HTML
Entities:
=========
this are used for reserved character such as => <,>,&,',",...etc
list of entities:
================
1. &lt;=> it is suse to represent to less than symbol
2.&gt; => it is used to represent to greater than symbol.
3. &amp; => It is used to ampersand symbol
4.&quot; => it is displayed double quotes.
5.&apos; =< it is used to repe=resent single quote
6. &nbsp; => it is used to represent display non-breaking space
7. &pound; => it is used to represent pound currency symbol
&yen; => it is used to display currency symbol;
9.&euro; It displays the euro symbol
10. &cent; => display cent currency symbol
11.&reg; => It displays a registered symbol
12. &copy; it displays copyright symbol
13. 7alpha; => alpha symbol
14. &beta;=> beta symbol
15. &gamma; => gamma symbol
16. &spades; => spade symbol
17. &diams; => diamond symbol
18. &clubs; => club symbol
19. &hearts; => heart symbol
HTML
HTML LIST
===============
There are 3 types of lists:
1. ordered list
2. unordered list
3. description list
list tags
===========
1.<ol>.</ol> => define ordred list
2. <uL>.</ul> define unordered list
3. <li> => It is used to define a list of items
4. <dl> ..</dl> describe description list
5. <dt>...</dt> define description terms
6. <dd> ...</dd> define data description
Attributes of OL tag
==============
type="1/A/a/I/i" => it is used to define specifi type
staer="" => to specify where the list should begin. it allows decimal numbers only
Attributes of ul tag
=====================
type="disc/circle/square/none" => it is used to specify the type.. default is disc
HTML
hyperlinks:
=============
hyperlinks are underlined words or locations on the web page that lead to another document.
There are 2 types of hyperlinks:
1. Page jump links
2. Bookmark hyperlinks
page jump hyperlinks
=====================
there are 2 types of page jump hyperlinks
1. internal hyperlink
2. external hyperlink
internal hyperlink:-
===================
The link between 2 different web pages on the same website is called an internal hyperlink
external hyperlink
========================
 The link between two different web pages on different websites is called an external hyperlink.
Bookmark hyperlink
===============
The link between 2 different locations on the same web page is called a bookmark hyperlink.
Link Tags:
HTML
===============
<a>...</a> => It is used to define a hyperlink. It is called an anchor tag.
<nav>....</nav> => It is used to create a set of navigation tags.
<link > => It is used to create a link between a web page and an external resource.
Attributes of <a> tag
=======================
1. href="..." => it is used to specific the hyperlink reference
2. target="_blank/_self" => It is used to specify whether the page should
display in the same window in another window
 Here _blank indicates another window or tab.&_self indicates the same window
default is _self.
3. atbindex="..." => It is used to specify tab index.
4. name=" => It is used to specify the hyperlink name that is required to create a bookmark link
name.
by default, unvisited links appear in blue, visited hyperlinks appear in purple & active links appear in
red color
These colors can be changed by using the following attributes of the body tag
1.link="." => specify unvisited hyperlink color.
2.vlink="." => specify visited hyperlink color.
2. alink=" => specify active hyperlink color.
To create a bookmark hyperlink follow the following links:
HTML
1. the value of the href and name attribute must be the same link
2. the value of the href attribute must begin with the #symbol
by using a link tag we can create a favicon
favicon is a small image that appears with the title in a title bar in the browser window.
Attribute to link tag:
======================\
1. rel ="icon" => It is used to specify the relationship between the HTML page and the external
resource
2. href="..." => It is used to specify the external resource file patch
Image and graphics tags:
========================
1.<img> => It is used to define an image
2.<map> </map> => it is used to define an image tag
image map means an image with clickable areas
3.<area> => It is used to specify the area of the pixel to click
4.<svg> ..</svg> => It is used to define a drawing area it allows you to draw circles, squares,
rectangles,.. etc..
5.<circle> ..</circle> => used to draw cycle
6. <rect>..<rect> => used to draw rectangle
7. <line>..</line> => used to draw line
HTML
8. <text> ..</text> => It is used to display text in a graphics area.
svg stands for scalable vector graphics.
Attributes of image tag:
=====================
1. src=" "=> specify the source file path
2. width=" => it is used to specify image width
3. eight="" => used to specify image height
Attribute of line tag
=======================
x1= It refers x1 coordinate
x2= It refers x2 coordinate
y1= It refers y1 coordinate
y2= It refers y2 coordinate
stroke= it describes the color of the stroke
stroke-width= it shows the width of the stroke
Audio& video tag
================
1.<audio> ...</audio> => it should contain embed audio content.
2.<video>........../</video> => it should contain some embed video content
3. <source>........</source> => used to define multiple audio and video resources
HTML
Note: the browser will close from top to bottom order.
Attributes of audio and video tags
===================================
1.src="." => It is used to specify the file path
2. width="" => it specifies width of pixel
3. height= " => it specifies the height in Pixel
4. autoplay= "=> it is used to specify that it should also automatically whenever it is loaded
5. controls => it is used to display audio controls
6. muted
7. loop => It is used to specify that it should play again whenever it has been finished
table tags
==========
1.<table> </table> => it is used to create a table
2.<tr></tr> => it is used to define row win a table
3.<th> </th> =>it is used to define header cell in a table
4.<td></td> => It is used to define a data cell in a table
5.<caption> </caption> => it is used to specify the table caption
6.<thead> </thead> => it is used to group a header content
7.<tbody></tbody> => used to group body content
8.<foot></foot> => used to group body content
9.<col > </col> => it is used to format columns
10. <colgroup></colgroup> => used to group columns for formatting
Attributes of table tag
==============================
HTML
1. border=" => It is used to specify the border in Pixel
2. bordercolor=" => It is used to specify the border-color
3. width=" => It is used to specify the border width
4. height=" => It is used to specify the table width
Attributes of tr, th, td tags
===============================
1. align="left/right/center" =>used to specify the text alignment
in the tag center is the default
in the td tag, left is the default
HTML Form tags
================
HTML forms are used to accept the data dynamically from the user, passed to the server
to process & to get the response from the server.
The many HTML forms are.
1. login form
2. registration
3. feedback
4. contact
5. application... etc.
Form tags
==========
1. <form> </form> => it is used to create a form. Here form is a container for many input fields.
2. <input>=> It is used to define the input field. For example, text, password, check box, radio button,
and drop-down list.
3. <label> </label> => It is used to create a label for the input field.
HTML
4. <select> => It is used to create drop-down lists (combo box allows single selection & list box allows
multiple selections.
5.<option> => used to specify the option that can be selected.
6. <optgroup> => It is used to group related options.
Attributes for input tag
=============================
1. type=" => It is used to specify the input field type.
2.name= "” => It is requested to specify tr parameter name.
Value of “type” attribute:
1. text =>used to define a single-line text field
2. password => used to define password field.
3. submit=> used to submit button
4. reset => It is used to define the reset button
In HTML both submit and reset buttons have default functionality.
Whenever the submit button is clicked then the value of the action attribute is executed in a <form>
tag
Whenever a reset button is clicked ten all form field data are erased & default values are stored
Attributes of the label tag:
1.For=” “ => it is used to specify the field name.
HTML
Attributes for the form tag:
1. Action=” => It is used to specify the server file name
Here the value of the action attribute is executed whenever the submit button is clicked
2.Method=”” => It is used to specify the http method name.
There are 7 HTTP methods:
1. get
2. post
3. put
4. delete
5. head
6. options
7. trace
NOTE: default is GET
Difference between GET and POST
Get post
1. It includes for request parameter in a 1. It includes the request parameter in a
request header in a packet, the request parameter in a request body In a packet
2.
3. In this method, the request parameter is displayed 3. In this method, request parameters
are
in an address bar. it is not displayed.
4. In this approach size of the data is limited. 4. in this approach, the size of the data is
not limited
 5. It supports text only. 5. It supports all types of data.
6. it is not secure. 6. It is secure.
7. get request can be cached. 7. Post request never cached.
8. GET requests are stored in browser history. 8. Post requests are not stored in a browser
history.
HTML
9. GET requests can be bookmarked. 9. Post requests cannot be bookmarked.
Attribute of type value:
=========================
12. email => It is used to create an input field that allows to enter email ID
13. tel => Create an input field that allows you to enter a telephone number
14. number => numeric input field that allows numbers only
15. url => It is used to create an input field that allows URLs
16. Search => It is used to create an input field that allows to enter search keyword
17. button => It is used to create a range field. it is like a slider
18. image =>used to create a submit with an image
19. range => used to create a range field. it is like a slider
20. hidden => used to create hidden from the file.
21. color => used to create an input field that allows select color
22. file => It is used to create an input field that allows the selection of file
Attribute of input tag:
========================
4.pattern="" => used to specify
5.min=" => It is used to specify the minimum value in the number field
6. max= " => It is used to specify the maximum value in the number field
7. step=" => It is used to specify the inter value in the number field.
8.multiple=” => It is allowed to select more than one file
9.src=” => It is used to specify the image path for the image field
10. width=” It is used to specify image width
11. height=” => it is used to specify the image height
12. disabled => It is used to specify that the input field should be disabled.
HTML
13. novalidate=> It is used to specify that the input field should not be validated when submitted.
14. autocomplete=” on/off” =>It is used to specify autocomplete mode. The default is on.
15. placeholder=” => used to specify the hint.
16. autofocus=> It is used to specify that the cursor should be placed in that particular input field
when the program is executed.
17. minlength=”” => It is used to specify the minimum no. of character.
18. maxlength=”” => It is used to specify the maximum no. of character.
URL stands for uniform resource locator
URN stands for the uniform resource name
URI stands for resource identifier
 or
 universal resource identifier
HTTP:
========
 HTTP stands for hypertext transfer protocol.
it transfers hypertext.
hypertext means HTML text
that is used by browsers & servers to communicate on the web.
HTTP:
HTML
=======
HTTPS stands for hypertext in an encrypted format.
WWW:
It stands for World Wide Web.
It indicates the browser searching for servers worldwide.
Attribute of form tag:
4. Novalidate=” “=> It is used to specify that the form should be validated when submitted.
5. Autocomplete=” off/on=> used to specify that auto-complete mode. The default is on.
6. Target=” blank/_self” => used to specify that the responses should display in the same
window or a new window
7. Name=” “=> used to specify the format name.
8.
Attributes for <select > tag:
1. Name=” => It is used to specify the request parameter name.
2. Multiple =” => used to specify that multiple values can be selected
3. Size =” => used to specify how many options should be displayed at a time. The default size is
4.
Attributes of <optgroup> tag:
1.label=”” => used to specify the label to the option =group.
HTML
Sematic and non-semantic tags
Semantic tags are used to describe content
Non-semantic tags are used to divide content into designs
These tags are used by browsers, search engines & UI (user interface) developers to
recognize the content.
List of semantic tags:
1.<header>………</header> => It is used to specify header information like company name,
company logo, and author information. Etc.
2. <footer> </footer> => It is used to specify footer information like company address, mail,
mobile number, copyright information…etc
3. <main></main> => It is used to specify the main content
4. <article></article> => it is an alternative <main> tag
5. <section></section> => used to divide main content into no. of modules.
List of non-semantic tags:
1.<div> </div> => used to create a division in a content.
2. <span></span> => used to mark a part of the text.
Meta tags:
Meta tags are used to define metadata.
Metadata means data about data.
Here metadata includes character set, software information, author information, program
description, search keywords, and language. Etc.
Here metadata used y browsers, search engines & UI developers to get data about the
document.
List of <meta> tag:
1.<meta> => It is used to specify the mega data.
2.<base> => used to specify default URL default target for all hyperlinks in a document.
Attribute of meta tag:
1.charset=” => it is used to character set. Eg: UTF-8 stands for Unicode text format 8 bits. It
includes all capital symbols, small letters, digits & special symbols.
2.name=”” => It is used to specify the metadata name including author, keyword,
d=generator, and descriptions. Etc.
3.content=” => used to specify the metadata value.
4. http-equiv => used to specify how long the page has to be refreshed.
HTML
Attributes of <base> tag:
1. Href=” => It is used to specify the default URL for all hyperlinks in an HTML document.
2. Target=” “=> It is used to specify the default target for all hyperlinks in html document
Programming tags:
1. <style></style> => used to embed CSS styles
2. <script> </script> => used to embed client-side script code. e.g.:js
3. <noscript> </noscript> => used to specify alternative content to user. This content is
displayed whenever the browser does not support the script code.
<!DOCTYPE html>:
It indicates html5 version of tags used in this HTML document to the browser.
Deprecated tags in HTML 5:
1.<marquee> </marqee>
2.<font> </font>
3. <strike> </strike>
4.<u> </u>
5.<frameset> </frameset>
6.<frame>
7.<center></center>
Deprecated attributes in HTML:
HTML
1. Bgcolor=””
2. Text=””
3. Background=””
4. Link=””
5. Alink=””
6. Vlink=””
7. Align=””
8. Hspace=””
9. Vspace=””
10. Widt=””
11. Height=””
Global attributes:
Global attributes can be used in all HTML tags.
1.id=”” => It is used to specify the id for an element. It is required while using CSS
2. class=”” => It is used to specify the class name. it also allows you to write multiple class names.
 It is also required while using CSS code.
3. Style=”” => It is used to specify the inline CSS code.
4. Title=” ” =>used to specify the tooltip text.
5. Hidden=”” =>used to hide content
6. Contenteditable=”” => it is used to specify whether content is editable or not. The default is
false.
7.











