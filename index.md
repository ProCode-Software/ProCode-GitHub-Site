# ProCode GitHub Website
Welcome to ProCode! At ProCode, you can explore sample codes.
## Get Started with ProCode CSS framework
```html
<link rel="stylesheet" href="https://procode-software.github.io/ProCode-GitHub-Site/procode.min.css">
```
### What is ProCode CSS?
ProCode CSS is a framework you can user for your site.
Example:
```html
<!--Link-->
<link rel="stylesheet" href="https://procode-software.github.io/ProCode-GitHub-Site/procode.min.css">
<!--Element-->
<div class="pc border-2px-red"></div>
```
The **border-2px-red** is the same as the following code in your CSS:
```css
.border-2px-red{
  border: 2px solid red;
}
```
### How to restyle ProCode CSS elements
Restyling buttons and elements with ProCode colors can be common. Here's how:
```html
<!-- Restyleing this: -->
<button class="pc bg-red col-fff">Text</button>
```
```css
button.pc{
  /* The "pc" class is used for ProCode CSS elements. This is an example used for a button */
  background: #008eff !important;
  padding: 10px !important;
  font-size: 20px !important;
 }
 ```
 The example shows:
 - To do this, use the **!important**
