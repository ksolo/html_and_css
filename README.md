# HTML/CSS Overview


## HTML

Hypertext Markup Language (HTML) provides your web pages with structure.  It is made up of a hierarchy of elements and is the foundation of everything else we'll build upon.

An HTML Element is made up of opening and closing tags, attributes, and content (text).

	<p class="intro">This is an intro paragraph</p>
	
If an element is enclosed in another element, is is considered a child element.  In this example, the li elements are children of the ol, and the ol is a parent to the li elements.  The individual li elements are considered siblings.

	<ol>
	  <li>One</li>
	  <li>Two</li>
	  <li>Three</li>
	</ol>
	
This type of terminology will become extremely important as you begin working with JavaScript and we discuss "traversing the DOM"

To learn more about elements and what attributes can be applied to them, please visit https://developer.mozilla.org/en-US/docs/Web/HTML/Element

## CSS

Cascading Style Sheets (CSS) provide the presentation layer.  You can think of CSS as a series of overwrites, with each rule overwriting the default or previously declared style.

A key aspect of CSS is selection. Initially focus on element, class, and id selectors.

	/* example element selectors */
	p { font-size: 16px; }
	div { float: left; }
	
	/* example class selector */
	.intro { color: blue; }
	.italic { font-style: italic; }
	
	/* example id selector */
	#main { width: 960px; }
	
For more information on CSS Selectors, please checkout https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Getting_started/Selectors

