
# HTML

Check out the live version of the project here: [Live Demo](https://hiranj-rkit-training.github.io/HTML/)






## HTML Tags Reference

| Tag            | Description                                       | Commonly Used Attributes             |
|----------------|---------------------------------------------------|--------------------------------------|
| `<a>`          | Defines a hyperlink                              | `href`, `target`, `rel`              |
| `<div>`        | Defines a division or section                    | `id`, `class`                        |
| `<span>`       | Defines a section within a document               | `id`, `class`                        |
| `<p>`          | Defines a paragraph                               | -                                    |
| `<h1>` to `<h6>` | Defines HTML headings                          | |                                   |
| `<img>`        | Defines an image                                 | `src`, `alt`, `width`, `height`      |
| `<ul>`         | Defines an unordered list                        | -                                    |
| `<ol>`         | Defines an ordered list                          | -                                    |
| `<li>`         | Defines a list item                              | -                                    |
| `<table>`      | Defines a table                                  | -                                    |
| `<tr>`         | Defines a row in a table                         | -                                    |
| `<td>`         | Defines a cell in a table row                    | `colspan`, `rowspan`                 |
| `<th>`         | Defines a header cell in a table row             | `colspan`, `rowspan`                 |
| `<form>`       | Defines an HTML form                             | `action`, `method`, `enctype`        |
| `<input>`      | Defines an input control                         | `type`, `name`, `value`, `placeholder` |
| `<label>`      | Defines a label for an `<input>` element          | `for`                                |
| `<button>`     | Defines a clickable button                       | `type`, `name`, `value`              |
| `<select>`     | Defines a drop-down list                         | `name`, `multiple`                   |
| `<option>`     | Defines an option in a drop-down list            | `value`                              |
| `<textarea>`   | Defines a multi-line text input                   | `name`, `rows`, `cols`               |
| `<link>`       | Defines the relationship between a document and an external resource (most used to link to stylesheets) | `href`, `rel`, `type`                |
| `<script>`     | Defines client-side JavaScript                    | `src`, `type`                        |
| `<meta>`       | Defines metadata about an HTML document          | `name`, `content`, `charset`         |
| `<header>`     | Defines a header for a document or section       | -                                    |
| `<footer>`     | Defines a footer for a document or section       | -                                    |
| `<section>`    | Defines a section in a document                   | -                                    |
| `<article>`    | Defines an article                               | -                                    |
| `<aside>`      | Defines content aside from the content it is placed in | -                                    |
| `<nav>`        | Defines navigation links                         | -                                    |
| `<figure>`     | Defines self-contained content, like illustrations or diagrams | -                                    |
| `<figcaption>` | Defines a caption for a `<figure>` element        | -                                    |
| `<details>`    | Defines additional details that the user can view or hide | `open`                               |
| `<summary>`    | Defines a heading for a `<details>` element       | -                                    |
| `<dialog>`     | Defines a dialog box or interactive component     | `open`                               |
| `<source>`     | Defines multiple media resources for elements like `<video>` and `<audio>` | `src`, `type`                        |
| `<track>`      | Provides text tracks for `<video>` and `<audio>` elements | `src`, `kind`, `label`, `srclang`    |
| `<iframe>`     | Defines an inline frame                           | `src`, `width`, `height`, `name`     |
| `<object>`     | Defines an embedded object, like a flash animation | `data`, `type`, `width`, `height`   |
| `<embed>`      | Defines an embedded object, like multimedia content | `src`, `type`, `width`, `height`    |
| `<param>`      | Defines parameters for an `<object>` element      | `name`, `value`                      |
| `<map>`        | Defines an image map                             | -                                    |
| `<area>`       | Defines a clickable area within an image map      | `shape`, `coords`, `href`, `alt`     |
| `<bdo>`        | Overrides the current text direction              | `dir`                                |
| `<bdi>`        | Isolates a span of text that might be formatted in a different direction | `dir`                                |
| `<cite>`       | Defines the title of a work                        | -                                    |
| `<dfn>`        | Defines a term that is defined in the document    | -                                    |
| `<kbd>`        | Defines keyboard input                            | -                                    |
| `<s>`          | Defines text that is no longer correct or relevant | -                                    |
| `<samp>`       | Defines sample output from a computer program      | -                                    |
| `<small>`      | Defines smaller text                              | -                                    |
| `<strong>`     | Defines important text                            | -                                    |
| `<sub>`        | Defines subscript text                           | -                                    |
| `<sup>`        | Defines superscript text                         | -                                    |
| `<time>`       | Defines a specific time or date                   | `datetime`                           |
| `<mark>`       | Defines text that should be highlighted           | -                                    |
| `<ruby>`       | Defines a ruby annotation (for East Asian typography) | -                                    |
| `<rt>`         | Defines an explanation or pronunciation of a `<ruby>` annotation | -                                    |
| `<rp>`         | Defines what to show for browsers that do not support `<ruby>` annotations | -                                    |
| `<b>`          | Defines bold text                                | -                                    |
| `<i>`          | Defines italic text                              | -                                    |
| `<u>`          | Defines underlined text                          | -                                    |
| `<wbr>`        | Defines where a line break should occur (in text) | -                                    |

## Notes:
- This table includes a broad range of HTML tags with their most frequently used attributes.
- Attributes listed are common but not exhaustive; other attributes may be available depending on the tag.

## 1.1 what is HTML , use of html , about different web browser

### What is HTML?
- HTML stands for `Hyper Text Markup Language`
- HTML is the standard markup language for creating Web pages
- HTML describes the structure of a Web pag
- HTML elements tell the browser how to display the content

### Basic Structure of HTML page

``` code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

### Web Browsers

The purpose of a web browser (Chrome, Edge, Firefox, Safari) is to read HTML documents and display them correctly.

A browser does not display the HTML tags, but uses them to determine how to display the document:


## 1.2 Basic Controls

### `<form>`

The HTML `<form>` element is used to create an HTML form for user input: 

```
<form>
.
form elements
.
</form>
```

there are many Attributes of `<form>` such as:
- action 
- method
- target
- autocomplete
- novalidate

### action
The `action` attribute defines the action to be performed when the form is submitted.

Usually, the form data is sent to a file on the server when the user clicks on the submit button.

### target
The target attribute specifies where to display the response that is received after submitting the form.

The target attribute can have one of the following values:

|Value | Description   |
|------------|------------|
|__blank |The response is displayed in a new window or tab |
|__self |	The response is displayed in the current window  |
|__parent | The response is displayed in the parent frame|
|__top |The response is displayed in the full body of the window |
|framename |The response is displayed in a named iframe | 
  
### method 
The method attribute specifies the HTTP method to be used when submitting the form data.

The form-data can be sent as URL variables (with method="get") or as HTTP post transaction (with method="post").

### autocomplete

The autocomplete attribute specifies whether a form should have autocomplete on or off.

### novalidate

The novalidate attribute is a boolean attribute. 


### <input>
One of the most used form elements is the `<input>` element.

An <input> element can be displayed in many ways, depending on the type attribute.

Here are most common used type of <input> tag:


| Input Type       | Description                                      |
|------------------|--------------------------------------------------|
| `text`           | Default. Defines a single-line text field.       |
| `password`       | Defines a password field.                        |
| `email`          | Defines a field for entering an email address.   |
| `number`         | Defines a field for entering a number.           |
| `submit`         | Defines a submit button.                         |
| `checkbox`       | Defines a checkbox.                              |
| `radio`          | Defines a radio button.                          |
| `file`           | Defines a field for file uploads.                |
| `button`         | Defines a clickable button.                      |
| `date`           | Defines a control for selecting a date.          |
| `datetime-local` | Defines a control for selecting date and time.   |
| `color`          | Defines a color picker.                          |
| `range`          | Defines a range control (slider).                |
| `search`         | Defines a text field for search queries.         |
| `reset`          | Defines a reset button.                          |
| `tel`            | Defines a field for entering a telephone number. |
| `time`           | Defines a control for selecting a time.          |
| `url`            | Defines a field for entering a URL.              |
| `month`          | Defines a control for selecting a month and year.|
| `week`           | Defines a control for selecting a week and year. |
| `hidden`         | Defines a hidden input field.                    |
| `image`          | Defines an image as the submit button.           |


### <label>
The <label> element defines a label for several form elements.

The <label> element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focus on the input element.

The <label> element also help users who have difficulty clicking on very small regions (such as radio buttons or checkboxes) - because when the user clicks the text within the <label> element, it toggles the radio button/checkbox.

The for attribute of the <label> tag should be equal to the id attribute of the <input> element to bind them together.


### SelectBox

The <select> element defines a drop-down list:

```
<label for="cars">Choose a car:</label>
<select id="cars" name="cars" multiple>
  <option value="volvo">Volvo</option>
  <option value="saab" selected>Saab</option>
  <option value="fiat">Fiat</option>
  <option value="audi">Audi</option>
</select>

```
The <option> element defines an option that can be selected.

To define a pre-selected option, add the selected attribute to the option:

Use the multiple attribute to allow the user to select more than one value:

### <textarea>

The <textarea> element defines a multi-line input field (a text area):

### <fieldset>

The <fieldset> element is used to group related data in a form.

The <legend> element defines a caption for the <fieldset> element.


### checkbox
The <input type="checkbox"> defines a checkbox.

Checkboxes let a user select ZERO or MORE options of a limited number of choices.

```
<form>
  <input type="checkbox" id="vehicle1" name="vehicle1" value="Bike">
  <label for="vehicle1"> I have a bike</label><br>
  <input type="checkbox" id="vehicle2" name="vehicle2" value="Car">
  <label for="vehicle2"> I have a car</label><br>
  <input type="checkbox" id="vehicle3" name="vehicle3" value="Boat">
  <label for="vehicle3"> I have a boat</label>
</form>
```

### radio
The <input type="radio"> defines a radio button.

Radio buttons let a user select ONE of a limited number of choices.
```
<form>
  <input type="radio" id="html" name="fav_language" value="HTML">
  <label for="html">HTML</label><br>
  <input type="radio" id="css" name="fav_language" value="CSS">
  <label for="css">CSS</label><br>
  <input type="radio" id="javascript" name="fav_language" value="JavaScript">
  <label for="javascript">JavaScript</label>
</form>

```

### button

The <button> element defines a clickable button:

## 1.3 Control's Attributes

### name
- The name attribute is used to identify form elements for data submission, such as <input>, <textarea>, and <select>.

- Unlike the id attribute, the name attribute can be used multiple times in a document, allowing multiple elements to share the same name.

- When a form is submitted, the value of the name attribute is sent as a key-value pair in the request, with the name being the key and the user input being the value.

- In older versions of HTML, the name attribute was used to create bookmarks, but this is now done using the id attribute.

### id

- The id attribute is used to specify a unique id for an HTML element
- The value of the id attribute must be unique within the HTML document
- The id attribute is used by CSS and JavaScript to style/select a specific element
- The value of the id attribute is case sensitive
- The id attribute is also used to create HTML bookmarks
- JavaScript can access an element with a specific id with the getElementById() method

### class
- The HTML class attribute specifies one or more class names for an element
- Classes are used by CSS and JavaScript to select and access specific elements
- The class attribute can be used on any HTML element
- The class name is case sensitive
- Different HTML elements can point to the same class name
- JavaScript can access elements with a specific class name with the getElementsByClassName() method

### vlaue 

- The value attribute specifies the default value for form elements like <input>, <textarea>, and <option>. For example, it sets the initial content in a text box or the default option in a dropdown menu.

- When a form is submitted, the value attribute determines the data sent to the server. For <input> and <textarea>, the value attribute holds the user’s input or the default value, while for <option>, it specifies the value that is sent if that option is selected.

- JavaScript can manipulate the value attribute of form elements using properties like element.value. This allows scripts to programmatically set or retrieve the value of a form element.

- The value attribute does not affect the visual representation of an element directly; rather, it provides a value that can be used for form processing. For instance, <input value="Default"> shows "Default" in the input field, but the actual value attribute is used when submitting the form.    
## 1.4 Basic Tag with its attribute 

### <img>


```
<img src="pic_trulli.jpg" alt="Italian Trulli">
```
The HTML <img> tag is used to embed an image in a web page.   

The <img> tag has two required attributes:

- src - Specifies the path to the image
- alt - Specifies an alternate text for the image


### <a>


he HTML <a> tag defines a hyperlink. It has the following syntax:

```
<a href="url">link text</a>
```
The most important attribute of the <a> element is the href attribute, which indicates the link's destination.


By default, links will appear as follows in all browsers:

- An unvisited link is underlined and blue
- A visited link is underlined and purple
- An active link is underlined and red



### Meta

The <meta> element is typically used to specify the character set, page description, keywords, author of the document, and viewport settings.

The metadata will not be displayed on the page, but is used by browsers (how to display content or reload page), by search engines (keywords), and other web services.  


```
<meta charset="UTF-8">
<meta name="description" content="Free Web tutorials">
<meta name="keywords" content="HTML, CSS, JavaScript">
<meta name="author" content="John Doe">
```

### Responsive 

Responsive web design is about creating web pages that look good on all devices!

A responsive web design will automatically adjust for different screen sizes and viewports. 


To create a responsive website, add the following <meta> tag to all your web pages:

```
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```


