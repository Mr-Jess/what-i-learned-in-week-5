# Week-5

## Dom Manipulation (Document object model)

* Javascript can manipulate the DOM

* The Document Object Model (DOM) represents that same document so it can be manipulated. The DOM is an object-oriented representation of the web page, which can be modified with a scripting language such as JavaScript.

* Document.querySelector()
  * selects the element
* Document.createDocument()
  * creates the element
* .innerText
  * holds HTML element
* style.background
  * changes the background elements
* parent.appendChild
  *  

* `D.R.Y. = Don't Repeat Yourself`
  * Using a Function will clean up code and make it easier to not repeat yourself.
  * Example
    * function abstraction(element) {
  element.backgroundImage = 'url';
  }

* `W.E.T. = Write Everything Twice.`
* `A.H.A. = Avoid Hasty Abstractions.`

* CSS Dinner 11-18
  * Combine the Universal Selector
**A  ' * '**
  * Adjacent Sibling Selector
Select an element that directly follows another element
**A + B**
  * General Sibling Selector
Select elements that follows another element
**A ~ B**
  * Child Selector
Select direct children of an element
**A > B**
First Child Pseudo-selector
Select a first child element inside of another element
**:first-child**
Only Child Pseudo-selector
Select an element that are the only element inside of another one.
**:only-child**
Last Child Pseudo-selector
Select the last element inside of another element
**:last-child**


* Ugly-Query
  * Ran queries with querySelector and createElements until we have the ugliest page possible
  * [Ugly-Query Project](https://github.com/Mr-Jess/ugly-query/blob/master/main.js)

## Test

* A property that holds the text within an HTML element is:
  * `.innerText`

* What is the syntax that will return the following html: <p id="demo"> This is a demo.</p>
  * `document.querySelector("#demo")`

* What would document.querySelector('h1') return?
  * `the first h1`

* What is the right way to create an image element?
  * `document.createElement('img')`

* how would you change the background color of a div stored in a JavaScript variable named `myDiv`
  * `myDiv.style.background = "red"`
