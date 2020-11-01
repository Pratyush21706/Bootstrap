                 <==================================Lesson 3 ==========================================>

          Bootstrap's Default Settings
Bootstrap's global default font-size is 14px, with a line-height of 1.428.

This is applied to the <body> element and all paragraphs (<p>).

In addition, all <p> elements have a bottom margin that equals half their computed line-height (10px by default).

                             <Bootstrap Normal Heading size>
h1 Bootstrap heading (36px)
h2 Bootstrap heading (30px)
h3 Bootstrap heading (24px)
h4 Bootstrap heading (18px)
h5 Bootstrap heading (14px)
h6 Bootstrap heading (12px)
                              <Bootstrap Typography Tags>
 <small>
In Bootstrap the HTML <small> element is used to create a lighter, secondary text in any heading:
<h1>h1 heading <small>secondary text</small></h1>

<mark>
Bootstrap will style the HTML <mark> element to highlight text.
 <p>Use the mark element to <mark>highlight</mark> text.</p>

<abbr>
Bootstrap will style the HTML <abbr> element to show an abbrebraetion with dotted underline;
<abbr title="World Health Organization">WHO</abbr>

<blockquote>
Bootstrap will style the HTML <blockquote> element to show a line in the left side of the text,

<Reverse Blockquote >
To show the quote on the right, use the .blockquote-reverse class.
<blockquote class="blockquote-reverse">

<dl>
The dl element indicates a description list:
<dt>
Description title
<dd>
Description Dtata
<dl>
    <dt>Coffee</dt>
    <dd>- black hot drink</dd>
    <dt>Milk</dt>
    <dd>- white cold drink</dd>
  </dl>

  <code>
  This tag is used to create special highlight for around the code word or line;
  <p><code>Div</code> Tag Is used to create a section in a page</p>

 <kbd>
  This tag is used to create special highlight around the text to give the text/word a feeling of a key.
<p>Use <kbd>Ctrl+s</kbd> to save a document in vs Code
  
<pre>
it is used to write multiple lines of codes

                    <Contextual Colors and Backgrounds>
Bootstrap also has some contextual classes that can be used to provide "meaning through colors".
The classes for text colors are:<text-muted, .text-primary, .text-success, .text-info, .text-warning, and .text-danger>

The classes for background colors are:<bg-primary, .bg-success, .bg-info, .bg-warning, and .bg-danger>
 
                                     <More Typography Classes>
              <The Bootstrap classes below can be added to style HTML elements further>
.lead	            Makes a paragraph stand out	
.small	          Indicates smaller text (set to 85% of the size of the parent)	
.text-left	      Indicates left-aligned text	
.text-center	    Indicates center-aligned text	
.text-right	      Indicates right-aligned text	
.text-justify	    Indicates justified text	
.text-nowrap	    Indicates no wrap text	
.text-lowercase	  Indicates lowercased text	
.text-uppercase	  Indicates uppercased text	
.text-capitalize	Indicates capitalized text	
.initialism	      Displays the text inside an <abbr> element in a slightly smaller font size	
.list-unstyled	  Removes the default list-style and left margin on list items (works on both <ul> and <ol>)..                 This class only applies to immediate children list items (to remove the default list-style from .                 any nested lists, apply this class to any nested lists as well)	
.list-inline	    Places all list items on a single line	
.dl-horizontal	  Lines up the terms (<dt>) and descriptions (<dd>) in <dl> elements side-by-side. Starts off...                 like default <dl>s, but when the browser window expands, it will line up side-by-side	
.pre-scrollable	  Makes a <pre> element scrollable
