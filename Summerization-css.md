css intro
css its the way which will allow you to create rules that specify how the content of an element should appear. For example, you can specify that the background of the page is cream, all paragraphs should appear in gray using the Arial typeface, or that all level one headings should be in a blue, itali

The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element 
CSS allows you to create rules that control the way that each individual box (and the contents of that box) is presented
- CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration... 
* **Selectors
*  indicate which element the rule applies to. The same rule can apply to more than one element if you separate the element names with commas.**
* **Declarations 
* indicate how
the elements referred to in the selector should be styled. Declarations are split into two parts (a property and a value), and are separated by a color 


**cSS propertIeS affect how eLeMentS are dISpLayed

CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value, separated by a colon. You can specify several properties in one declaration, each separated by a semi-colon.

CSS rules usually appear in a separate document, although they may appear within an HTML p

*why uSe externaL StyLe SheetS?
When building a website there are several advantages to plasing your css rules in a separate style sheet
All of your web pages can share the same style sheet. This is achieved by using the <link> element on each HTML page of your site to link to the same CSS document. This means that the same code does not need to be repeated in every page (which results in less code and smaller html pages 


coloring 
CSS treats each HTML element as if it appears in a box, and the background-color property sets the color of the background for that box.
You can specify your choice of background color in the same three ways you can specify foreground colors: RGB values, hex codes, and color names (covered on the next page).
If you do not specify a background color, then the background is transparent.
By default, most browser windows have a white background, but browser users can set a background color for their windows, so if you want
to be sure that the background is white you can use the background-color property on the <body> element.
We have also used the padding property to separate the text form the edges of the boxes this make it easier to read .
