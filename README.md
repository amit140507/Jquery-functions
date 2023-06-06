# Jquery-functions

## 1 [.attr()](https://www.w3schools.com/jquery/html_attr.asp)
Get attribute values or set attributes values.

**Example**  
Get Value ```var value = jQuery(a.gt-current).attr("data-gt-lang");```  
Set value ```var value = $("img").attr("width","500");```

## 2 Load after page get load
```
jQuery(window).on("load", function () {

});
```
## 3 Get width of page
[innerWidth](https://www.w3schools.com/jquery/html_innerwidth.asp) this method includes padding, but not border and margin.  
[outerWidth](https://www.w3schools.com/jquery/html_outerwidth.asp)  this method includes padding and border.  
 To include the margin, use outerWidth(true).  
```
var width = jQuery('body').width();
```

## 4 Get height of element
[innerHeight](https://www.w3schools.com/jquery/html_innerheight.asp) this method includes padding, but not border and margin.   
[OuterHeight](https://www.w3schools.com/jquery/html_outerheight.asp) this method includes padding and border.  
Tip: To include the margin, use outerHeight(true). 
```
var footerheight = jQuery("footer").outerHeight();
```

## 5 [.css()](https://www.w3schools.com/jquery/jquery_css.asp) 
To get or set value of a css property.  

**Example**  
```
jQuery("main").css("margin-bottom", "100px");
```
```
$("p").css("background-color", "yellow");
```
## 6  [removeAttr()](https://www.w3schools.com/jquery/html_removeattr.asp)  
The removeAttr() method removes one or more attributes from the selected elements.  
```
jQuery('a.customwpmenu.dropdown-toggle').removeAttr('data-toggle');
```
```
$("p").removeAttr("style");
```

## 7 [appendTo()](https://www.w3schools.com/jquery/html_appendto.asp)
 Insert a <span> element at the end of p element:  
`$("<span>Hello World!</span>").appendTo("p");`
`jQuery('<a class="underlineBtn-2 mobile-readmore" id="read-more-button-light">'+readmore+'</a>').appendTo(".read-more-light");`
 
## [prependTo()](https://www.w3schools.com/jquery/html_prependto.asp)
 
## [append](https://www.w3schools.com/jquery/html_append.asp)
 
## [prepend](https://www.w3schools.com/jquery/html_prepend.asp)
 
     



































