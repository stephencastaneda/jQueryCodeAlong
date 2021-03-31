# jQueryCodeAlong

## Setup Instructions

- Clone the repo to codesandbox 
- Follow the steps below

## Code Along

1. Create a fade in effect using jQuery's `.hide()` & `.fadeIn()` method
*TYPE* 
```
$("li:lt(4)").hide().fadeIn(1500)
```

2. Create a function to remove bullet points when clicked
*TYPE* 
``` javascript
    $("li").on("click", function () {
      $(this).remove();
    }); 
```
3. Add a class that will use your button in the html with the `center` id that's primary function is to center the text. *CSS already exists to make this work in css folder*
*TYPE* 
``` javascript
$("#center").on("click", function () {
  $("body").addClass("center");
});
```

4. Studying at night can be hard on the eyes. Create a dark mode that uses our button in the html with the `dark` id. *CSS already exists to make this work in the css folder*
*TYPE* 
``` javascript
$("#dark").on("click", function () {
  $("body").toggleClass("dark");
});
```
