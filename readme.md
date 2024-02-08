HTML-
* HTML stands for Hypertext Markup Language.
* we use html for creating strutcture of the website.
* We called HTML as a markup language bcz it contain skeleton strutc of the web page.
* All HTML are written in tag line.
* 
==========================================================
# Structure of an HTML file ::

<html>
<head>
  
    <title>
   My 1st page
    </title>
</head>
<body>
    <h1>Today is Tuesday</h1>
    <h2></h2>
    <h3></h3>        }heading tag is range from h1 to h6.
    <h4></h4>
    <h5></h5>

    <p>hello hello</p>  =paragraph tag used to write descriptions.

    <br>= tag use for line break
    <hr>= tag ufor put horizontal line

  * <img>-Image tag(single tag)
   --------------
    <img src="20200731_092517.jpg" height="200" width="200" alt="currently not found">
  * <a></a> =anchor tag 
    <a href="https://webbocket.com" target="self"> Web-Bocket</a>
       |||
    **href=Hyper reference to the another page/element
    **  <!--(values of target attribute)
        _self=the linked document own(same) page
        _blank=the linked document new page
        _parent=open the linked document  in parent frame
        _top =opens the linked document in full body of window
    -->

   
    
</body>
</html>
============================================================
HTML Formatting::
================
* <b> </b>    =Bold
* <i> </i>    =Italic
* <em> </em>  =emphasized
* <del></del> =deletion text
* <ins></ins> =inserted text
* <sub></sub> =subscripted text
* <sup></sup> =supetrscripted text
* <mark></mark>= highlighted text
-------------------------------------------------------------------
HTML TABLE:
===========
*HTML table gives us a table like structure where we can store our data in row and
 colomn format.
 ..............
<table>
<th>
this is table heading
</th>
<tr>
   this is table row
    <td>
        this is table data
    </td>
</tr>
</table>
...............
---------------------------------------------------------------------
HTML LIST:
==========
 list is of 2 types.
 1. Ordered List.
             1.       I.
             2.       II.
             3.       III.
 2.Unordered List.
    *
    *
    *
    *
-----------------------------------------------------------------------
HTML & Block level Element:
==========================

HTML contains 2 types of Block level elements to 
specify structure of web pages.

 1.<p></p>
 2.<div></div>

 ----------------------------------------------------------------------

# HTML Forms:
 ==========
 it gives us a form like structure so that we can give our data.

 <input type ="text">
 <input type ="password">
 <input type ="submit">
 <input type ="checkbox">
 <input type ="radio-button">
 <input type ="color">
 <input type ="time">
 <input type ="date">
 <input type ="url">
 <input type ="search">
 <input type ="email">
 <input type ="week">
 <input type ="image">
 <input type ="month">
 <input type ="range">
 <input type ="file">
 <input type ="number">
 <input type ="tel">

*******************************                         **************************************
              ********************************************************
                                      ****************

   #  C S S: 
   ----------

   - Stands for Cascading Style Sheet.
   - used for designing and styling the web pages.


   h1 -selector  
   {            
     color:blue;- value
   }   |
      property 
 ............................                              
 - there are 3 types of CSS.
     1. Inline CSS
     2. Internel CSS
     3. External CSS

Inline_CSS:
----------
<p style="back-ground color:green">jhkj dnjh,bhuh</p>

Internal_CSS:
------------
<head>
    <style>
        h1
        {
            color:blue;
        }
        .org
        {
            back-ground color:orange;
        }
        #box1
        {
            border-sizing:border box;
        }
    </style>
</head>

External CSS:
-------------
<head>
 <link rel="stylesheet" href="Style.css">
</head>                          |
                          External Css file name



CSS-Selectors:(5 types)
-------------- 
  1. Class Selector  - .classname{}
  2. ID Selector     - #Id{}
  3. Group Selector  - element1,element2,element3{}
  4. Element Selector -element{}
  5. Universal Selector -*{}
