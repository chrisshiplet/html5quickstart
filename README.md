html5quickstart v0.9.0
===============
A minimal template to start an HTML5 project without the overhead of Bootstrap (and similar frameworks).

The Responsive Grid was tested in Chrome, Safari, Firefox, IE7+, iOS, and Android's stock browser. 

##Overview
Includes the following features:

**CSS**
- Eric Meyer CSS Reset  
- Responsive Grid Framework  
- Placeholders for popular techniques (including retina graphics)  
- Clearfix class  
- Three accessible visibility classes  
- Basic print stylesheet  

**HTML**
- HTML5 doctype
- CDN-loaded IE shivs for HTML5 & media queries  
- Optional CDN-loaded jQuery  
- Placeholders for popular meta and link tags
- Optimized Google Analytics placeholder

**MISC**
- robots.txt placeholder 

##Documentation
Here's how to use the responsive grid and the various utility classes:

###Responsive Grid
To use the responsive grid, set the wrapper to have classes *.container* and *.row*. Each row has class *.row*, and each column inside a row has class *.col*. The responsive grid has 12 columns, so specify the width of a column by adding class *.span_n* where n is the number of columns to span. Finally, you can use *.offset_n* where n is the number of columns to offset for a left margin.

Here is an example of implementing the responsive grid:

```html
<div class="container row">

    <div class="row">
	    <div class="col span_6">This column has span_6</div>
	    <div class="col span_6">This column has span_6</div>
    </div>
    
    <div class="row">
	    <div class="col span_12">This column has span_12</div>
    </div>
    
    <div class="row">
	    <div class="col span_6 offset_6">span_6 offset_6</div>
    </div>
    
    <div class="row">
	    <div class="col span_4 offset_2">span_4 offset_2</div>
    </div>
    
    <div class="row">
	    <div class="col span_2">span_2</div>
    </div>

</div>
```
###.wrapper
Apply this to your page wrapping div to set the max-width of the layout and keep it centered.

###.clearfix
The classic float clearing fix. Apply clearfix to a floated element to make sure that elements below it clear the float properly.

###.hidden
This hides an element from screen readers and browsers while reflowing content.

###.invisible
This hides an element from screen readers and browsers while maintaining layout.

###.visuallyhidden
This hides an element from browsers, but not screen readers

## Epilogue
That's all for now! Thanks to [Dan Cederholm](http://simplebits.com) and [Ethan Marcotte](http://ethanmarcotte.com/) for their pioneering responsive design advice.

Parts were adapted from [Eric Meyer's CSS Reset](http://meyerweb.com/eric/tools/css/reset/), [Responsive.gs](http://responsive.gs/), and the [HTML5 Boilerplate](http://html5boilerplate.com/).

Feel free to modify and use in your projects as you wish, although a link to [my site](http://nearengine.com) or the [GitHub repo](http://github.com/nearengine/html5quickstart) is always appreciated.