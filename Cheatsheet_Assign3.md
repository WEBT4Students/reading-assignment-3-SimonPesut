<!DOCTYPE html>
<html>
  <head>
    <title>CheatSheet</title>
    
  </head>
  <body bgcolor = "lightblue"> 
    <h1 align="center">CheatSheet</h1>

    <h2>World Wide Web General</h2>
    
<h3>What are the most essential technologies that made the World Wide Web such a success?</h3><br/>
    
     1. HTTP server, World Wide Web, Mosaic, Navigator, Java(Script), Internet Explorer <br/>

<h3>How are resources (html pages, images, etc) addressed in the web?</h3><br/>
    
     2. They are linked by hyperlinks and URIs. <br/>
    
<h3>What are the general components of a url?</h3><br/>
    
     3. It indicates a protocol (http), a hostname (www.example.com), and a file name (index.html). 
    
    <h2>Web Server</h2>
  
 <h3>What is a web server?</h3><br/>

    1. A web server is computer software and underlying hardware that accepts requests via HTTP or its secure variant HTTPS.<br/>
  
<h3> What does a web server?</h3><br/>
  
    2. A user agent, commonly a web browser or web crawler, initiates communication by making a request for a web page or other resource <br/>
    &nbsp;&nbsp;&nbsp;&nbsp;using HTTP, and the server responds with the content of that resource or an error message. <br/>
    &nbsp;&nbsp;&nbsp;&nbsp;A web server can also accept and store resources sent from the user agent if configured to do so<br/>

 <h3>How can content be stored on a web server?</h3><br/>

    3. <strong>Static content:</strong> A resource sent from a web server can be a preexisting file available to the web server<br/>
    &nbsp;&nbsp;&nbsp;&nbsp;<strong>Synamic content:</strong> Or it can be generated at the time of the request by another program that communicates with the server software.<br/>
 
 <h3>How is content in webpages described?</h3><br/>
  
    4.Web browsers can typically be configured with a built-in menu. Depending on the browser, the menu may be named Settings, Options, or 
    &nbsp;&nbsp;&nbsp;&nbsp;Preferences.

    <h2>Web Client</h2>
  
<h3>What is a web client?</h3><br/>
  
    1. It is application software for accessing the World Wide Web or a local website.<br/>

<h3>What does a web client?</h3><br/>
  
    2. When a user requests a web page from a particular website, the web browser retrieves its files from a web server and then graphically
    &nbsp;&nbsp;&nbsp;&nbsp;renders the page on the user's screen.
  
<h3>Web Client and Web Browser is the same?</h3><br/>
  
    3. A web browser is specific kind of web client which shows whole website

    <h2>Hello World</h2>

<h3>What is the html head element?</h3><br/>
  
    1. It is a container for metadata (data about data) and is placed between the html tag and the body tag.<br/>
  
<h3>What does !DOCTYPE html mean?</h3><br/>
  
    2. It is an "information" to the browser about what document type to expect.<br/>
  
<h3>What are the two top most elements within the html element?</h3><br/>
  
    3. Tags and Markups<br/>
  
<h3>How to emphasize a text and how is it displayed in the browser?</h3><br/>

    4. With the <strong>em</strong> Tag. The content inside is typically displayed is italic.<br/>
  
<h3>How to mark up important ext and how is it displayed in the browser?</h3><br/>

    5. With the <strong>strong</strong> tag. The content inside is typically displayed in bold.<br/>

<hr>
<h2 align="center">HTML</h2>

<h3>Properly name the components of HTML elements</h3><br/>

    The <strong>html</strong> element is the root element and defines the entire HTML document.<br/>
    Then inside the html element there is a body element<br/>

    The <strong>body</strong> element defines the body of the document.<br/>
    Then inside the body element there are two other elements: <strong>h1 and p</strong><br/>

    The <strong>h1</strong> element defines a heading<br/>
    The <strong>p</strong> element defines a paragraph<br/>

<h3>Identify void elements and how they are denoted</h3><br/>
 
    The <strong>br</strong> tag defines a line break, and is an empty element without a closing tag.<br/>

<h3>Identify attributes</h3><br/>
 
    The <strong>a</strong> tag defines a hyperlink. The href attribute specifies the URL of the page the link goes to<br/>
    The <strong>img</strong> tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be displayed<br/>
    The img tag should also contain the width and height attributes, which specify the width and height of the image (in pixels)<br/>
    The required <strong>alt</strong> attribute for the img tag specifies an alternate text for an image, if the image for some reason cannot be displayed<br/>
    This can be due to a slow connection, or an error in the src attribute, or if the user uses a screen reader.<br/>
    The <strong>style</strong> attribute is used to add styles to an element, such as color, font, size, and more<br/>
    You should always include the <strong>long</strong> attribute inside the html tag, to declare the language of the Web page. This is meant to assist search engines and browsers.<br/>
    The <strong>title</strong> attribute defines some extra information about an element<br/>

<h3>Write down the correct DOCTYPE declaration for html 5</h3><br/>
 
    <strong>!DOCTYPE html</strong><br/>

<h3>Write down syntactically correct statements for the following elements</h3><br/>

<h4>Article (article)</h4><br/> 

<h4>Body (body)</h4><br/>

    The <strong>body</strong> element defines the body of the document.<br/>
    Then inside the body element there are two other elements: <strong>h1 and p</strong><br/>

<h4>line break (br)</h4><br/>

    The <strong>br</strong> tag defines a line break, and is an empty element without a closing tag.<br/>

<h4>Headings (h1, ...)</h4><br/>

    h1 defines the most important heading. h6 defines the least important heading<br/>
    h1 headings should be used for main headings, followed by h2 headings, then the less important h3, and so on.<br/>

<h4>Section with meta-information (head)</h4><br/>

    The head element is a container for metadata (data about data) and is placed between the html tag and the body tag.<br/>

<h4>Top level element (html)</h4><br/>

    The <strong>html</strong> element is the root element and defines the entire HTML document.<br/>
    Then inside the html element there is a body element<br/>

<h4>Image named Team.jpg (img src="Team.jpg")</h4><br/>

    The img tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be displayed<br/>

<h4>Paragraph (p)</h4><br/>

    HTML paragraphs are defined with the <strong>p</strong> tag<br/>

<h4>Section (section)</h4><br/>

<h4>Label appearing in the title bar (title)</h4><br/>

    The title element defines the title of the document. The title must be text-only, and it is shown in the browser's title bar or in the page's tab.<br/>

    The title element is required in HTML documents!<br/>
    
    The content of a page title is very important for search engine optimization (SEO)! The page title is used by search engine algorithms to decide the order when listing pages in search results.<br/>
    
    The title element:<br/>
    
    defines a title in the browser toolbar<br/>
    provides a title for the page when it is added to favorites<br/>
    displays a title for the page in search engine-results<br/>
    So, try to make the title as accurate and meaningful as possible!<br/>

<h4>Link to other pages (a)</h4><br/>

    The <strong>a</strong> tag defines a hyperlink<br/>

<h4>Comment</h4><br/>

    You can add comments to your HTML source by using the following syntax<br/>
    Notice that there is an exclamation point (!) in the start tag, but not in the end tag<br/>

    With comments you can place notifications and reminders in your HTML code<br/>

    Comments can be used to hide content.<br/>
    This can be helpful if you hide content temporarily<br/>
    You can also hide more than one line. Everything between them will be hidden from the display<br/>

    Comments can be used to hide parts in the middle of the HTML code<br/>

<h4>Head with title and meta elements</h4><br/>

<hr>
<h2 align="center">CSS</h2>

<h3>Name the components of a css rule properly</h3><br/>

    The selector points to the HTML element you want to style.

    The declaration block contains one or more declarations separated by semicolons.

    Each declaration includes a CSS property name and a value, separated by a colon.

    Multiple CSS declarations are separated with semicolons, and declaration blocks are surrounded by curly braces

<h3>Use combinators properly: direct child, descendant, adjacent sibling, sibling</h3><br/>   

    descendant selector (space)<br/>
    child selector (>)<br/>
    adjacent sibling selector (+)<br/>
    general sibling selector (~)<br/>
    
<h3>Specify colors by color names and in hexadecimal notation</h3><br/>

    red = Tomate = #ff6347<br/>
    blue = DodgerBlue = #1E90FF<br/>
    grey = gray = #808080<br/>
    violet = violet = #EE82EE<br/>
    orange = Orange = #FFA500<br/>
    black = black = #000000<br/>
    white = white = #FFFFFF<br/>
    Maroon	#800000M<br/>
    Purple	#800080<br/>
    Yellow = #FFFF00<br/>	
    Olive = #808000<br/>
    Lime = #00FF00<br/>	
    Green = #008000<br/>	
    Aqua = #00FFFF<br/>	
    Teal = #008080<br/>	
    Blue = #0000FF<br/>	
    Navyb = #000080<br/>
    Fuchsia = #FF00FF<br/>	
    purple = #800080<br/>

<h3>Declarations for color, background color</h3><br/>

    h1 style="color:Tomato;">Hello World h1<br/>
    h1 style="background-color:DodgerBlue;">Hello World h1<br/>

<h3>Pseudo classes for the a element</h3><br/>

    :hover<br/>
    :active<br/>
    :focus<br/>
    :focus-within<br/>
    :visited<br/>
    :link<br/>
    :hover<br/>

<h3>Declaration for background image</h3><br/>

    background-image: url("paper.gif");<br/>

<h3>Declaration for text alignment (left, right, center, justify)</h3><br/>

    h1 {<br/>
      text-align: center;<br/>
    }<br/>
  
    h2 {<br/>
      text-align: left;<br/>
    }<br/>
  
    h3 {<br/>
      text-align: right;<br/>
    }<br/>

    div {<br/>
      text-align: justify;<br/>
    }<br/>

<h3>Declaration for text decoration (overline, underline, line-through)</h3><br/>

    h1 {<br/>
      text-decoration-line: overline;<br/>
    }<br/>
  
    h2 {<br/>
      text-decoration-line: line-through;<br/>
    }<br/>
  
    h3 {<br/>
      text-decoration-line: underline;<br/>
    }<br/>
  
    p {<br/>
      text-decoration-line: overline underline;<br/>
    }<br/>

<h3>Declaration for text transformation (uppercase, lowercase, capitalize)</h3><br/>

    p.uppercase {<br/>
        text-transform: uppercase;<br/>
      }<br/>
      
      p.lowercase {<br/>
        text-transform: lowercase;<br/>
      }<br/>
      
      p.capitalize {<br/>
        text-transform: capitalize;<br/>
      }<br/>

<h3>Identify the difference between serif and sans-serif fonts</h3><br/>

    So, in a nutshell, serif fonts have those decorative lines or tapers (also commonly referred to as “tails” or “feet”) while sans serif fonts don't<br/>

<h3>Declarations for font families</h3><br/>
    
    body {<br/>
        font-family: "Times New Roman", Times, serif;<br/>
    }<br/>
    body {<br/>
        font-family: Arial, Helvetica, sans-serif;<br/>
    }<br/>

<h3>Declarations for font style normal and italic</h3><br/>

    p.normal {<br/>
        font-style: normal;<br/>
    }<br/>
      
      p.italic {<br/>
        font-style: italic;<br/>
    }<br/>
    
<h3>Declarations for font sizes</h3><br/>

    
    h1 {<br/>
        font-size: 40px;<br/>
    }<br/>
      
      h2 {<br/>
        font-size: 30px;<br/>
    }<br/>
      
      p {<br/>
        font-size: 14px;<br/>
    }<br/>

<h3>Declarations for font weights</h3><br/>

    font-weight: normal;<br/>
<hr>
<h2 align="center">Html for lists</h2><br/>
<h3>1.Start tags for</h3><br/>
<h4><div style="text-indent:10px;">-> an ordered list</div></h4><br/>
<div style="text-indent:10px;">&lt;ol&gt;</div><br/>
<h4><div style="text-indent:10px;">-> an unordered list</div></h4><br/>
<div style="text-indent:10px;">&lt;ul&gt;</div><br/>
<h4><div style="text-indent:10px;">-> a description list</div></h4><br/>
<div style="text-indent:10px;">&lt;dl&gt;</div><br/>
<h4><div style="text-indent:10px;">-> a list item</div></h4><br/>
<div style="text-indent:10px;">&lt;li&gt;</div><br/>
<h4><div style="text-indent:10px;">-> a description term</div></h4><br/>
<div style="text-indent:10px;">&lt;dt&gt;</div><br/>
<h4><div style="text-indent:10px;">-> a description data</div></h4><br/>
<div style="text-indent:10px;">&lt;dd&gt;</div><br/>
ss
<hr>
<h2 align="center">Css for lists</h2><br/>


  </body>
</html>
