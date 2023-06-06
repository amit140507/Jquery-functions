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

## 5 
