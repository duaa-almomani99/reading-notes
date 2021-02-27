

Evolution of htMl

Since the web was first created, there have been several different versions of HTML

htMl 4
rElEasEd 1997
With the exception of a few elements added in HTML5 (which have been highlighted), the elements you have seen in this book were all available in HTML 4.
Although HTML 4 had some presentational elements to control the appearance of pages, authors are not recommended to use them any more. (Examples include the <center> element for centering content on a
page, <font> for controlling the appearance of text, and <strike> to put a line through the text — all of these can be achieved with CSS instead.)

xhtMl 1.0
rElEasEd 2000
In 1998, a language called XML was published. Its purpose
was to allow people to write new markup languages. Since HTML was the most widely used markup language around, it was decided that HTML 4 should be reformulated to follow the rules of XML and it was renamed XHTML. This meant that authors had to follow some new, more strict rules about writing markup. 


htMl5
rElEasEd 2000
In HTML5, web page authors do not need to close all tags, and new elements and attributes will be introduced. At the time of writing, the HTML5 specification had not been completed, but
the major browser makers had started to implement many of the new features, and web page authors were rapidly adopting the new markup.
Despite the fact that HTML5
is not yet completed, you can safely take advantage of the new features of the language as long as you endeavour to ensure that users with older browsers will be able to view your pages (even though some of the extra features will not be visible to them 
....
Doctypes
Because there have been several versions of HTML, each web page should begin with a DOCTYPE declaration to tell a browser which version of HTML the page is using 



... <!-- -->
If you want to add a comment to your code that will not be visible in the user's browser, you can add the text between these characters:
<!-- comment goes here --

id attributE
Every HTML element can carry the id attribute. It is used to uniquely identify that element from other elements on the page. Its value should start with a letter or an underscore (not a number or any other character). It is important that no two elements on the same page
have the same value for their id attributes (otherwise the value is no longer unique).



HTML5 LayouT


new HTML5 LayouT element

HTML5 introduces a new set of elements that allow you to divide up the parts of a page. The names of these elements indicate the kind of content you will find in them. They are still subject to change, but that has not stopped many web page authors using them already. 


* navaigraTTicioLne
<nav>
The <nav> element is used to contain the major navigational blocks on the site such as the primary site navigation

* arTicLes
* <article>The <article> element acts as a container for any section of a page that could stand alone and potentially be syndicated.

* Heading garToiucpLes 
* <hgroup>The purpose of the <hgroup> element is to group together a set of one or more <h1> through <h6> elements so that they are treated as one single heading.    

Java script How do I write a script for a web page .... web developers usually talk about three Languages that are used to creat a web pages html css is On html the html gives the pages structure and adds semantics CSS the css enhances the html pages with rules that state how the html content is presented Js here we can change how the pages behave How to use objects methods This one line of java scripts shows how to use object and methods JavaScript runs where it is found on the html When the browser comes across <script> it’s stop the script and then checks if there’s any thing needed

