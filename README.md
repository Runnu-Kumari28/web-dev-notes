# web-dev-notes
contains pointer notes on web dev technologies
# HTML
* there is no logic building in HTML file, it contains the structure of the website.
* Inline elements- Do not start a new line, only take needed width. eg- <span>. <img>, <a>
* Block Elements- Starts a new line, Take full width available. eg- <div>, <h1>-<h6>, <p>
## Inline elements: 
* <strong> identifies the text as important, <em> for emphasis, it changes the text into italics.
* <b> and <i> tag is similar to <strong> and <em> tag but they are not semantic.
* <mark> highlights the text.
* <del> adds strike through.
* <ins> adds an underline.
* <sub> is for subscript.
* <sup> is for superscript.
* <span> tag defines a section in a document inline 
## Block elements:
* <div> or division element defines a section in a document/web page in block.
<hr> draws a horizontal line.

## Attributes:


...

## guidelines
* Use lowercase elements names, such as <div> not <DIV>
* Use lowercase attribute names
* Use lowercase file names
* Use camel case for names, classes, ID's, etc such as myClass
* No spaces before or afyer = in attributes. such as title="My Title"
* Avoid long lines of code, break up code
* Do not add blank lines without a reason
* Indent code 2 or 4 spaces (preference)
* Close tags in proper order- such as <p><strong>text</strong></p>
## Comments
* <! -- Headings -->
* command in VS code: ctrl+/
* Not viewable in web page

# CSS
1. Inline CSS
   * syntax: <div style="colour:red">
   * Bad Practise
   * Styling each element separately
   * Not efficient
   * Not scalable
  
2. Internal CSS
   * syntax: <style></style>
   * Better Practise
   * Can only be used in one file
   * Makes file larger
  
   3. External CSS
      * Best Practise
      * Keeps styles separate from HTML
      * Improved readability and reusability
    ### Colors
   * HTML Color Names such as blue, red, yellow, etc.
   * Hexadecimal code such as #FF253F
   * rgb--> (red green blue), maxm limit-255, rgb(255,150, 50)
   * rgba--> (red green blue alpha-range(0-1)/transparency), rgba(255, 150, 50, 1)
   ### Fonts
   * Serif-old Sans Serif-Modern
   * Web Safe Fonts
     ** Arial
     ** Helvetica
     ** Times New Roman
     ** Verdana
   * font-family: Arial, Helvetica, Sans-Serif
  
   * Font-size
     ** px--> absolute units, such as px, tie to physical units of length. Absolute length units approximate the actual measurement on a screen.
     ** em--> Relative units, such as em, are relative to another length value. For example, em is based on the size of an element's font.
     ** if the font size is 16px then 1em would equal 16px. 0.5em would equal 8px.
  *CSS is read from top to bottom, so the last value read by the browser will be displayed on the web page.

     
     
    
  
