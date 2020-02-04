# Notes from HTML & CSS book readings

## Chapter 18 - Process and Design

### Things to consider when designing your website

* Who is the site for?
    * Individuals? Companies?
    * Make up personas based on your target audience and consider them when you have a question about how the site will be used
* Why are people coming to your site?
    * What's their motivation?
    * What are they trying to do? (goal)
    * Figure out their key tasks and motivations
* What information do they need?
* How often will they visit the site?
    * Is it a one-time or rare thing they are trying to do or will they come back often?
    * Will the information need to be updated often?


### Designing your website

* Site map - This is used to organize how you want the information to appear on your website.
    * A card sort can be used to help you create a site map. 
    * Group the information in a way that makes sense for your audience
* Use wireframes to sketch out what your website will look like.
    * Draw on a piece of paper
    * Use tools like Photoshop, Illustrator, or InDesign
    * Use online tools such as [Go Mockingbird](http:gomockingbird.com) or [Lovely Charts](http:lovelycharts.com)
* Use visual design to organize and prioritize information on your website
    * Visual hierarchy -size, color, and style determine the order in which you see things on the page
    * Grouping similar content
* Navigation should communicate what your site is about and how it is organized


## Chapter 1 - Structure
HTML (hyper-text markup language) is used to structure the website.

### HTML
* Uses elements to describe the structure of the page
* An element has an opening tag and a closing tag. 
    * `<p>This is a sample paragraph element.</p>`
* Attributes tell us more about the element. They consist of a name and value.
    * `<p color="blue">This paragraph will be blue.</p>`
* Main elements of a page are:
    * Body - content of the page
    * Head - info about the page 
    * Title - shown in the tab or page frame in the browser 

[Get sample code from the book](www.htmlandcssbook.com/code/)

## Chapter 17 - HTML5 Layout

HTML5 is a new set of elements that provides alternatives to using the `<div>` tag.

### HTML5
* `<div>` elements group items together on the page. HTML5 elements to use instead of a `<div>` are:
    * \<header>
    * \<nav>
    * \<article>
    * \<aside>
    * \<footer>
    * \<section>
    * \<figure>
        * \<figcaption> must be included in \<figure>
    * \<hgroup> - group headings together
    * \<div> - still needed to group things together if the other elements aren't sufficient
* Sometimes the purpose of the element can change depending on where it's located on the page. 
* Older browsers don't support HTML5 so you need to put JavaScript code called the HTML5 shiv or HTML5 shim inside a conditional comment that checks to see if the browser version is less than IE9. The user must have JavaScript enabled or this won't work and they won't be able to see the content of the HTML5 elements.

## Chapter 8 - Extra Markup

* DOCTYPES tells the browser which version of HTML you're using.
* \<!-- comment goes here --> allows you to comment out code in HTML
* id attribute - uniquely identifies an element from other elements on the page
* class attribute - used to identify several elements as being different from other elements on the page
* block elements always start on a new line
* inline elements continue on the same line
* \<div> groups text and elements in a block
* \<span> groups text and elements inline
* \<iframe> creates a window in your page where you can display other pages
* \<meta> allows you to provide information about your page
*  escape characters are used to put special characters on your page 

