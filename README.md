# Lesson 3.5: DOM Manipulation, Part 2

## Overview
This lesson focused on using JavaScript to dynamically modify the style of elements on a webpage. The `.style` property of JavaScript provides an interface to change or add CSS styling to an element.

## .style Property
   - The `.style` property lets you get or set inline styles of an element.
   - It provides a way to add to or modify CSS styling of a webpage directly through JavaScript.

The general format for using `.style` is:

```javascript
    selector.style.cssProperty = "value";
```

Example: To set the width of an image:

```javascript
    firstImg.style.width = "400px";
```

### Four Steps for Styling with JS
   - **Selector**: Choose the HTML element you want to style.
   - **.style Property**: Used to access the style of the chosen element.
   - **CSS Property**: Decide which style property you want to change.
   - **Value**: Set the desired value for that property.

   **Example**: To set a div's background color to purple:

   ```javascript
   div1.style.backgroundColor = "purple";
   ```

## Camel Casing in JavaScript
   - CSS properties that have two words are written in camel case when using them in JavaScript.
   - Remove any hyphens and capitalize the first letter of the second word.
     
     | CSS           | JavaScript       |
     |---------------|------------------|
     | background-color | backgroundColor |
     | font-size        | fontSize        |

   **Example**:

   ```javascript
   header.style.backgroundColor = "black";
   header.style.color = "lightGreen";
   ```

## **Key Takeaways**

- JavaScript provides a powerful tool in the `.style` property to dynamically adjust styles.
- Remember to use camel case for CSS properties that are typically hyphenated when using them in JavaScript.

## **Further Reading**
For those interested in diving deeper, consider looking into:

- [MDN Web Docs on Element.style](https://developer.mozilla.org/en-US/docs/Web/API/Element/style)
- [W3Schools on JavaScript Style](https://www.w3schools.com/js/js_htmldom_css.asp)

Happy coding! 🚀