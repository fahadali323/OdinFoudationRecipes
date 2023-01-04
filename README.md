# OdinFoudationRecipes
This project contains index page which will have links to few recipes. This project only uses HTML. 
Brief: 
	HTML stands for Hyper text markup language as is a considered as one of many languages for the frontend development.
	Unlike other programming lanauges html is not considered a programming lanuage because it does not features to create variables, function, conditional statements or create loops. 
Elements:
	HTML defines the structure and content of a webpage and so it uses things like elements and tags. Tags are essentially keywords that the browser uses to determine when a particular element has started and when it ends.
	For example:
		<html> and </html> is used to tell the browser that html has started and where it ends.
		<body> and </body> is used to tell the browser when the body element is started. Anything inside these two tags will be outputted onto the screen.
		<P> and </P>       is used for paragraphs.
Text:
	Since content on the web is text-based, this means that most of the Html elements will also be texted based.
	For example:
		<strong> </strong>      is used to make text bold and also puts emphasizes on the text.
        	<em> </em>              is used to make words italics and adds importance to the text. Used for those that need accessibility.
       		<b> </b>                is used to make the text visually bold. has no meaning at all.
        	<i> </i>                is use to make words visually italics.
Lists:
	Lists are another way to display context on the web. 
	For example:
		<i> </i>                is use to make words visually italics.
        	<ul> </ul>              is used to create a list of unordered lists, usually starts with bullet points.
        	<ol> </ol>              is used to create a list of ordered items, starts with numbering.
        	<li> </li>              each item within the list uses this list element. both <ul> and <li> uses this.
Boilerplate:
	Most boilerplate generally start with an opening doctype which tells the browser what version of html to use.
	Then the <html> and </html> are used to tell when a start and end html tags. The <head> and </head> is used to indicate what important inforation is included to tell the browser how to render the rest of the html page. Inside <head> you will find
	<meta charset="utf-8" which is an encoding tag that tells the browser how to display special characters onto the page. And last but not least, you have the <titl> and </title> which tells the browser what name to give to the page tab. 
Links and Images: 
	Like the rest of the above mentioned features, HTML also has links which will allow the us to link to other html pages on the web. Images are another feature in HTML which makes the website visually more appealing.
	Absolute LINK:
		Abosulte links are links that link pages to other websites on the internet. So https://www.google.com
	Relative LINK:
		Relative are links that link to other pags within the the same website as the root link.
	Example:
		absolute path:	 	<a href="http://www.google.com">GOOGLE ME</a>
		relative path:		<a href="pages/about.html">About Me</a>
 
	Another tool to use in html is images. To display an image in html we use the <img> element. Unlike other elements <img> element does not require a closing tag because what ever attribute passed inside the img will be finite so thus it won't require an closing tag.
	Example:
		<src="/images/dog.jpg" alt="a picture of black dog with orange shirt" >
