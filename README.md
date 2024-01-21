# Annotationeer
Annotationeer runs on top of the PDF.JS Viewer and enables users to create annotations, bookmarks and formfields. The codebase is plain Javascript and a little mix of JQuery while the right sidebar list linking the annotations in the canvas uses Angular JS.

https://annotationeer.netlify.com

YouTube: [Create annotations in PDF.JS](https://www.youtube.com/watch?v=g2YAn-Yvlss)

Users can create the following annotations:

* Square fill
* Square border
* Circle fill
* Circle border
* Stamp
* Arrow
* Sticky note
* Measurement distance (like in Adobe Acrobat tool)
* Measurement area (like in Adobe Acrobat tool)
* Audio (in MP3 or OGG)
* Free hand drawing
* Free text
* Text Underline
* Text Highlight
* Text Strike-through
* Form fields like text field, checkbox, radio button
* Signature

All annotations come with a comment and properties like background and foreground color, measurement units in inches, centimeter or millimeter and font size to name a few. These same annotations can be accessed through the sidebar as a list where you can scroll through as well as a comments popup window to initiate a chat history for every annotation.

Some nifty features that can be configured based on the user's preference:

* Scales annotations based on zoom value
* Rotates annotations based on page rotation angle
* Tooltips
* Showing annotation list in the left or right sidebar
* Saving all annotations using the save button or through every action
* Watermark in every page
* Screenshot of a selected dragged area in the page converted to an image
* Property popup to modify annotation properties
* Comment popup to modify and add reply comments
* Runs on any PDF.JS version
* Print preview option to include watermark and annotations

These annotations are saved and retrieved through RESTful URLs that I created using Silex PHP Framework and using MySQL as database or Couchbase's NoSQL while producing outputs in JSON format.

The web application can run in IE and Webkit based browsers like Chrome, Firefox and Safari. And, while I do not have any physical tablets or smartphone with a good amount of RAM, this has been tested in an Android emulator.
