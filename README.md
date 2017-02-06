# jQuery.dom
Tiny plugin for jQuery, to create a Dom tree.

Example 1:
```
var element = $.dom({child:[
  {t:"p", id:"text", text:"I'm Text"},  
  {t:"a", text:"I'm link", href:"#text", onClick:function(e) {
    console.log("click");
  }},  
]});
$("body").append(element);
```
Example 2:
```
$("body").dom({child:[
  {t:"p", id:"text", text:"I'm Text"},  
  {t:"a", text:"I'm link", href:"#text", onClick:function(e) {
    console.log("click");
  }},  
]});
```
