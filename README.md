# Assignment2
First I created index.html page.

I have designed a product page with product filter.

In this assignment i have used vue.js

Now,I have declared productlist variable.

I have created productlist data,products,methods array.

I have created three methods.
```vue.js

removeTags: function (item) {
  this.filtersAppied.pop(item);
},
// set active method
setActive: function (element) {
  if (this.filtersAppied.indexOf(element) > -1){
      this.filtersAppied.pop(element);
  } else {
      this.filtersAppied.push(element);
  }
},
isActive: function (menuItem) {
   return this.filtersAppied.indexOf(menuItem) > -1;
}
    
 ```
 
