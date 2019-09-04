## Budget App

I created a budget application using using Jvascript. This aplication not only gave gave me broad understannding of DOM, but also code structuring my code, modules and function creation, event handlers.

#### Languages & Tools used

- HTML
- CSS
- Javascript
- Developed on VS Code
- git

##### JS code snippetd that are helpful!

Clearing HTML fieds and and converting a list to an array (mainly using querrySelectorAll & for each method)....

```JavaScript
clearFields: function() {
      var fields, fieldsArr;
      fields = document.querySelectorAll(
        DOMstrings.inputDesription + ", " + DOMstrings.inputValue
      );

      fieldsArr = Array.prototype.slice.call(fields);
      fieldsArr.forEach(function(current, index, array) {
        current.value = "";
      });

      fieldsArr[0].focus();
    }
```
