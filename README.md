Dynamically Sized Sticky Footer
===============================
This is a **dynamically sized** sticky footer that sinks to the bottom of the webpage even if the content doesn't fill the page.
The height does not need to be manually specified and automatically resizes to the content.
It uses css tables with a *table > row > single cell > content* hierarchy.

Benefits Over Other Solutions
-----------------------------
**Dynamic Sticky Footer >> Specified Height Sticky Footer**  
Dynamic Sticky Footer automatically adjusts for any content size. You don't need to keep changing the specified heights because it happens automatically.

**Dynamic Sticky Footer >> Flexbox**  
Dynamic Sticky Footer is supported in many more browsers and much older browsers than Flexboxes. It also uses a much clearer hierarchy to accomplish it.

**Display** (What Dynamic Sticky Footer Uses)  

|Property | ![Google Chrome](http://www.w3schools.com/images/compatible_chrome.gif) | ![Edge](http://www.w3schools.com/images/compatible_edge.gif)| ![Internet Explorer](http://www.w3schools.com/images/compatible_ie.gif) | ![Firefox](http://www.w3schools.com/images/compatible_firefox.gif)| ![Safari](http://www.w3schools.com/images/compatible_safari.gif) | ![Opera](http://www.w3schools.com/images/compatible_opera.gif)|
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
|display | 4.0 | 12.0 | 8.0 | 3.0 | 3.1 | 7.0|

**Flexbox** 

|Property | ![Google Chrome](http://www.w3schools.com/images/compatible_chrome.gif) | ![Edge](http://www.w3schools.com/images/compatible_edge.gif)| ![Internet Explorer](http://www.w3schools.com/images/compatible_ie.gif) | ![Firefox](http://www.w3schools.com/images/compatible_firefox.gif)| ![Safari](http://www.w3schools.com/images/compatible_safari.gif) | ![Opera](http://www.w3schools.com/images/compatible_opera.gif)|
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
|Basic support<br>(single-line flexbox) | 29.0<br>21.0&nbsp;-webkit- | 12.0 | 11.0 | 22.0<br>18.0&nbsp;-moz- | 6.1&nbsp;-webkit- | 12.1&nbsp;-webkit-</td>|
|Multi-line flexbox | 29.0<br>21.0&nbsp;-webkit- | 12.0 | 11.0 | 28.0 | 6.1&nbsp;-webkit- | 17.0<br>15.0&nbsp;-webkit-<br>12.1|

*Courtesy of [w3schools.com](http://www.w3schools.com "w3schools.com")*  
[Display Property](http://www.w3schools.com/cssref/pr_class_display.asp)  
[Flexbox Property](http://www.w3schools.com/css/css3_flexbox.asp)

Quick start
-----------
Check out the files. All the instructions are well explained in each file (especially the .css files).

To view the examples, just download the zip, extract the files, and open any .html file in your browser.

General Rule for Styling
------------------------
In regards to styling, it goes by level.

|       Level        |         Class to style|
|--------------------|-------------------------------|
|Table level styles  | `.sf-container`|
|Row level styles    | `.sf-section-expand`, `.sf-section-fit`|
|Cell level styles   | `.sf-cell`|
|Cell content styles | `.sf-content`|

License
-------
[MIT License](https://opensource.org/licenses/MIT "MIT License on opensource.org")