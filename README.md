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
The appendTo() method inserts HTML elements at the end of the selected elements.
```
$("<span>Hello World!</span>").appendTo("p");
```  
```
jQuery('<a class="underlineBtn-2 mobile-readmore" id="read-more-button-light">'+readmore+'</a>').appendTo(".read-more-light");
```
 
## [append](https://www.w3schools.com/jquery/html_append.asp)
 The append() method inserts specified content at the end of the selected elements.
```
 $("p").append("<b>Appended text</b>");
```
## [prependTo()](https://www.w3schools.com/jquery/html_prependto.asp)  
 The prependTo() method inserts HTML elements at the beginning of the selected elements.
```
   $("<span>Hello World!</span>").prependTo("p");
```
## [prepend](https://www.w3schools.com/jquery/html_prepend.asp)
The prepend() method inserts specified content at the beginning of the selected elements.  
```
 $("p").prepend("<b>Prepended text</b>");
```
## 8 [.remove()](https://www.w3schools.com/jquery/jquery_dom_remove.asp)  
The jQuery remove() method removes the selected element(s) and its child elements.  
```
$("#div1").remove();
```

## 9 When Click on an element addClass and when click anywhere outside that particular element removeClass
```
  jQuery(".type").on("click", function(a) {
    jQuery(".category-type").addClass("active");
    a.stopPropagation();
  });
  jQuery(document).on("click", function(a) {
    if (jQuery(a.target).is("active") === false) {
      jQuery(".category-type").removeClass("active");
    }
  });
```  
```
  jQuery(".year-dropdown-button").on("click", function(a) {
    jQuery('#date-filter').show();
    jQuery(".year-dropdown").addClass("active");
    a.stopPropagation();
  });
  jQuery(document).on("click", function(a) {
    if (jQuery(a.target).is("active") === false) {
        jQuery('#date-filter').hide();
      jQuery(".year-dropdown").removeClass("active");
    }
  });
  ```
## 10 [clone()](https://www.w3schools.com/jquery/html_clone.asp)  
The clone() method makes a copy of selected elements, including child nodes, text and attributes.  

## 11 [text()](https://www.w3schools.com/jquery/html_text.asp)  
The text() method sets or returns the text content of the selected elements.  
Example:  
**Set value**
```
 $("p").text("Hello world!");
```
**Get value**
```
 $(selector).text()
```

## #12 [val()](https://www.w3schools.com/jquery/html_val.asp)  
The val() method returns or sets the value attribute of the selected elements.  
Example:  
Set Value
```
 $("input:text").val("Glenn Quagmire");
```
Get value
```
 $("input:text").val();
```

## #13 [delay()](https://www.w3schools.com/jquery/eff_delay.asp) 
The delay() method sets a timer to delay the execution of the next item in the queue  
Example:  
```
$("#div1").delay("slow").fadeIn();
```
```
jQuery('.chart-section tr th:nth-child(even)').delay(2000).css("background-color", ""+colour+"10");
```

## 14 []()




























