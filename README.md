
1.BASIC TAGS
2.FORMATTING TAGS
3.LIST TAGS
4.LINK TAGS
5. image and graphics
6. Audio and video tag

7. table
8. form
9. frame
10. semantic and non semantic
11. meta
12. programming



=====================================================================================================================

Attributes of  body:
  bgcolor,text, left margin, topmargin, background,title

  FORMATTING TAGS:
  
    <H1></H1>--> level1

    <H2></H2>--> level2

    <H3></H3>-->level 3

    <H4></H4>--> level 4

    <H5></H5>--> level 5

    <H6></H6>--> level 6


    ATTRIBUTES OF H1 TO H6
    =======================

    1. ALIGN="LEFT/RIGHHT/CENTER"  => iT IS USED TO Specify the alignment. Default is left.
    2.title="..."  => it is used to specift tool tip text.


    <marquee></marquee>  this tag is used to scrool the text in the top of the text in brpwser

    Attributes of  <marquee> tag
    =============================
    1.bg color
    2. behavior="scroll/slide/ a"
    scrolla maount  it is used to spped value 
    loop="  "   It is used to specify how many times  it should be   scroll

    width=""=> specify rjr ,arquee wiodth
    heigt=""=>  it is used to specify  marquee heighht
    hspace=""=> specify hhoerizental space
    vspace=""=> specify veertical space
    direction="left\right\up\down"=>  specify the text direcytion
    title="" => it is used to specify tool tip text

    FORMATTING TAGS
===============================

<font></font>==>   it is defined to font
<b>..</b>=>   it is used to define the bold text
<i>..</..i>  it is used to define italic text
<u>..</u>=> it is used to define underline
<br>==>it is usecto beraek line
<center>...</center>  => it is used to define center alignment


ATTRIBUTE OF FONT TAGS
==========================

1.face="""  ==>  it is used to specify the font name
2.size="" => it is used to specify  the font size
3.color=""=> it is usec to speciy gtext color

FORMATTIG TAGS
================

<SUB></sub> ==> it is used to define subscripted text.
<sup></sup>==> it is used to define superscripted text
<del></del>==> it is used to define deleted text.
<strike></strike>  ==> It is usec to define  strike the text

<hr>=> It is used to define horizental rules
<p> it is used to define the paragfrfaph
<bdo></bdo>=> it is used to define  override text direction  BDO standarad BI  direction  override
<pre></pre>  It is usec to define performed text
<progress></progress>  => it ias used to define  progress ber.
<abbr></abbr>  => it is usect to define abrovation of te text
<adress></adress>It is used to define contact information


Attributes of hhr tag
=========================
color
widthh
height
size==> it is used to speciy thickness.



align="left/rigt/center"


Attributes of bdo tag
======================
1.dir="ltr/rtl"  it is used to specify the  text direction
			ltr=left to right
			rtl=right to left

attributes for <abbr> tag
==============================
1.title=""  it is used to specify the toll tip text

Attributes of progress ta
==========================

1.max=" value" => it is used to specify maximum value of the task.
2. value=""  => it is used to specify how much  value of the task will be downloaded


Entities:
=========
thsis are used for reserved characyer such as   =>   <,>,&,',",...etc
list of entities:
================
1. &lt;=> it is suse to represent  to lesss tan symbol
2.&gt;  => it is used to represent to greater than symbol.
3. &amp; =>  It is used to ampersand symbol
4.&quot;  => it is display double qotes.
5.&apos;  =< it is used to repe=resent single quote
6. &nbsp;  => it is used to represent  display non breaking space
7. &pound; => it is used to represent pound currency symbol
&yen;  => it is used to display currency symbol;
9.&euro;  It display euro symbol
10. &cent; => diplay cent currency symbol
11.&reg;  => it display registerd symbol
12. &copy;  it display copy right symbol
13. 7alpha;  => alpha symbol
14. &beta;=>  beta symbol
15. &gamma;  => gamma symbol
16. &spades; => spade symbol
17. &diams; =>  diamond symbol
18. &clubs; => club symbol
19. &hearts; => heart symbol







HTML LIST
===============
thare are 3 types of list:

1.orderd list
2.unorderd list
3.description list


list tags
===========

1.<ol>.</ol>  => define ordred list
2. <uL>.</ul>  define unorderd list
3. <li> => it id used to define list of items
4. <dl> ..</dl>  describe description list
5. <dt>...</dt>  define description terms
6.  <dd>  ...</dd>  define data description 



Attributes of  OL iag
==============

type="1/A/a/I/i"  => it is used to define specifi type
staer="" =>   to specify  where the list should 	begin.  it allow decimal number only

Attributes of ul tag
=====================
type="disc/circle/square/none"  => it is used to specify the type.. default is disc

hyperlinks:
=============

hyperlinks are underline words or locations  in te web page taht leadds to other document.


tere are 2 types of yperlinks:
1. page jump links
2. Book mark hyper links


page jump hyper links
=====================
there are 2 types of  paage jump yper links
1.internal hyper link
2. external  hyper link

internal hyper link:-
===================
 The link between 2 different web pages un the same  web site is called internal hyper link

external  hyper link
========================
  thhe link between two differnt web pages in differnt  website  is called as an  external yper link.

Book mark hyper link
===============
 The link between  2 differnt locations in the same web page is called as book mark yper link.

Link Tags:
===============

<a>...</a>  => it is ussed to define hyper link. it is calledas anchor tag.

<nav>....</nav>  =>  It is used to  create  a set of navigation tags.

<link >  =>  It is used to  create a link between web page and external resource.

Attributes of <a> tag
=======================

1. href="..."  =>  it is used to specific  the hyperlink  reference
2. target="_blank/_self"  => it is usesd to specify whherther the page should
 display in the same window in another window
  Here _blank indicates anothhe window or tab.&_self indicates the same window
 default is _self.
3. atbindex="..."  => it is used to specify tab index.
4. name=""  => it is used to specify the yper link name it is required to create a book mark link name.


 by default unvisited hyper links appears blue color, visited hyper link appears purple color & active hyper links  appeared red color
Thhese color can be changed by using the following attributes of body tag

1.link="." => specify unvisited hyper link color.
2.vlink="." => specify visited hyper link color.
2. alink=""  => specify active yper link color.



To create a book mark hyperlink  follow the following links:

1. the value of href and name attribute must ve same link
2. the value of href attribute must begin with #symbol

by using link tag we van vreate favicon

favcom is a small  image thhhat appears withh tittle in a tittle bar in browser window.

Attribute og link tag:
======================\

1.rel ="icon"  => it os used to specify thhe ralation ship between html page and external resource

2. href="..."  => it is used to specify the extrenal resource file pathh


Image and graphics tags:
========================
1.<img>                     =>  It is used to define an image
2.<map> </map>             =>  it is used to define an image tag
image map means an image with clicable areas

3.<area>                  => It is used to specify the area of pixle to click

4.<svg> ..</svg>         =>  it is used to define a drawing area it allow to draw circle, squares, rectangles,.. etc..

5.<circle>  ..</circle>  =>  used to draw cicle
6.  <rect>..<rect>       =>  used to draw  rectangle

7.  <line>..</line>     =>  used to draw line

8. <text> ..</text>     =>it is used to display text in a grapics area.

svg stands for scalable vector graphics.


Attributes of img tag:
=====================
1. src="  "=>  specify the source file path
2. width="" =>  it is used to specify image widt
3. eight="" =>  used to specify image heighht
 


Attribute of line tag
=======================
x1=  It refere x1 coordinate
x2= It refere x2 coordinate
y1= It refere y1 coordinate
y2= It refere y2 coordinate
stroke=  it describe  color of stroke
stroke-width= it shows te width of stroke


Audio& video tag
================

1.<audio> ...</audio>          =>  it should contain embed audio content.
2.<video>........../</video>   =>  it shhould contain some embed video content
3.  <source>........</source>  =>  used to define multiple audio and video resources

Note:  browser wikk ciise from top ti bottom order.

Attributes of audio and video tags
===================================
1.src="."        =>  It is used to specify the file path
2. width=""      =>  it specify width of pixcel
3. height= ""    => it specify te heighth in pixcel
4. autoplay= ""  => it is used to specify that it sould plsu automatically  whenever it is loaded
5. controls      =>  it is usedd to display audio controls
6. muted
7.loop           => it is used to specify that it should play again whenever it has been finised




table tags
========== 
1.<table>  </table>         => it is used to reate a table
2.<tr></tr>                 => it is used to define row win a table
3.<th></th>                 =>it is used to define eader cell in atable
4.<td></td>                 => it is used to define a data cell in a table
5.<caption> </caption>      =>  it is usedd to specify the table caption
6.<thead> </thead>          =>  it is used to group a header content
7.<tbody></tbody>           =>  used to group body content
8.<foot></foot>             =>  used to group body content
9.<col > </col>             => it is used to format columns
10. <colgroup></colgroup>   =>  used to group columns for formatting


Attributes of table tag
==============================
1. border=""             => it is used to specify the border in pixcel
2. bordercolor=""        => it is used tpo specify thr border color
3. width=""              => it is used to specify the border width
4. height=""            =>  it is used to specify the table width

Attributes of  tr, th, td tags
===============================
1. align="left/right/center"  =>used to specify the text alignent
 in th tag  center is default	
 in td tag, left is default

HTML Form tags
================

HTML forms ate used ti accept the data dynamically form te user , passed to server 
to process & to get the responce from the server.


The many html form those are.
	1.login form
	2.registration
	3.feedback
	4.contact
	5.application... etc.
Form tags
==========

1. <form> </form>   => it is yswd to create a form . Here form is a container for maany input fields.
2  <input>  => it is used to define input fileds. For example, text,password, check box, radio button , drop down list.
3. <label> </label>  => it is used to create a label for input field.

Attributes for type tag
=============================
1. type=""  => it is used to specify te input field type. 
2.name= ""  => it is request to specify tr parameter name.

 Value of “type” attribute:
=============================
1.text =>used to define single line text field
2.password => used to define password field.
3. submit=> used to submit button
4. reset => it is used to define reset button
5. checkbox=> it is used to create a ceck box.
6.radio=> it is sued to create a radio button
7.date
8.time
9.datetime-local
10.month
12.week






In html both submit and reset buttons having default functionality.
Whenever submit button is clicked then the value of action attribute is executed in a <form> tag
Whenever reset button is clicked ten all form field data erased & default values are stored

 
Attributes of label tag
============================
1.	For=” “  =>  it is used to specify the field name.

Attributes for form tag
=========================
1.	Action=”” => it is used to specify the server file name
Here the value of action attribute is executed whenever submit button is clicked
2.	Method=”” => it is used to specify http method name.
There are 7 http methods:
======================
1.get
2.post
3.put
4.delete
5.head
6.options
7.trace
NOTE: default is GET
Difference between GET and POST
		Get                                                                     post
1.It includes for request peramter in a                 1. It include the request parameter in a request header in a packet request 
							perameter in a request body In a packet
2.	                    

3.In this method, request parameter is displayed        3. In this method, request parameter are 
in a address bar.					     not displayed.
4.In this approach size of the data is limited. 	4.in this approach, size of the data is not limited

5.It support text only.				        5. It aupport all type of data.
6. it is not secure.					6. It  is secure.
7. get reqest can be cached.				7. Post request never cached.
8. GET request are stored browser history.	        8. Post request are not stored in a browser history.

9. GET request can be book marked.			9. Post request cannot be book marked.



Attribute of type  value:
=========================
12.email    => it is used to create an inout field that allow to enter email id
13. tel     => create an input field tat allow to enter a telephone number
14. number  => numeric input field that allow number only
15. url     => it is used to create an inout field that allow urls
16.search   => it is used to create an inout field that allow to enter search keyword
17.button   =>  it is used to create an  range field . it is like a slider
18.image    =>used to create a submit with image
19. range   => used to create a range filed. it is like a slider
20.hidden   =>  used to create idden from filed.
21.color    => used to create an input field that allow select color
22.file     => it is used to create an input field that allow to select file 


Attribute of input tag:
========================
4.pattern="" => used to specify 
5.min=""  => it is used to specify the minimum value in the number field
6. max= "" => it is used to specify te maximum value in the number field
7. step="" => it is used to specify the inter value in the number field.

URL stands for uniform resource locator
URN  stands for uniform resource name
URI stands for resource identifier
       or
    universal resource identifier


HTTP:
========
  http stands for hyper text transfer protocol.
 it transfer hyper text.
 hyper text means  html text
 it is used by browser & server to communicate on the web.


HTTPS:
=======
HTTPS  stands for hyper text in encrypted format.



  













