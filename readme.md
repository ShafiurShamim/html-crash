# HTML CRASH

## Basic Structure
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Basic Structure</title>
</head>
<body>
    
</body>
</html>
```
## Elements

An HTML element is one that has a start tag, some content, and an end tag.

<pre>
&lt;tagname&gt; Content &lt;/tagname&gt;
    &uarr;                   &uarr;
Starting Tag          Ending Tag
</pre>

## Attributes
HTML attributes provide additional information about HTML elements.
Attributes are always specified in the start tag.
Attributes usually come in name/value pairs like: name="value".
A tag can have multiple attributes.

```html
<a href="www.example.com">Link</a>
<!-- The href feature specifies the URL of the page to which the link goes -->
```

## Block & Inline Elements
Every HTML element has a default display value, depending on what type of element it is.

There are two display values: block and inline.

### Block-level Elements

A block-level element always starts on a new line.
A block-level element always takes up the full width available (stretches out to the left and right as far as it can).
A block-level element has a top and a bottom margin, whereas an inline element does not.

```html
<address> <article> <aside> <blockquote> <canvas> <dd> <div> <dl> <dt> <fieldset> <figcaption> <figure> <footer> <form> <h1> <h2> <h3> <h4> <h5> <h6> <header> <hr> <li> <main> <nav> <noscript> <ol> <p> <pre> <section> <table> <ul> <video
```

### Inline Elements

An inline element does not start on a new line.
An inline element only takes up as much width as necessary.

```html
<a> <abbr> <b> <bdo> <br> <button> <cite> <code> <dfn> <em> <i> <img> <input> <kbd> <label> <map> <object> <output> <q> <samp> <select> <small> <span> <strong> <sub> <sup> <textarea> <time> <var>
```


[Source w3schools.com](https://www.w3schools.com/html/html_blocks.asp)

## Text Formatting
```html
<p>
    Lorem ipsum <b>dolor</b>  <strong>sit amet</strong> consectetur adipisicing 
    elit. <i>Temporibus</i> nesciunt <em>eligendi</em> facilis <mark>incidunt qui</mark>  
    vero sit,<small>ratione</small>  eos <del>delectus</del>  
    quae <ins>obcaecati</ins>  distinctio, asperiores <sub>nam</sub>
    officia <sup>modi</sup>  molestias totam, suscipit labore?
</p>
```
## Headings
```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```
## Lists
```html
<h3>Unorderd List</h3>

<ul>
    <li>Milk</li>
    <li>Apple</li>
    <li>Potato</li>
</ul>


<h3>Orderd List</h3>

<ol type="A">
    <li>Milk</li>
    <li>Apple</li>
    <li>Potato</li>
</ol>


<h3>Description List</h3>

<dl>
    <dt>Milk</dt>
        <dd>Milk is a good source of many essential nutrients.</dd>
    <dt>Apple</dt>
        <dd>Apples are nutritious.</dd>
    <dt>Potato</dt>
        <dd>Potatoes are rich in vitamins.</dd>
</dl>

<!-- Nested List -->
<h3>Nested List</h3>

<ul>
    <li>Tea
        <ul>
            <li>Black Tea</li>
            <li>Green Tea</li>
        </ul>
    </li>
    <li>Coffee
        <ul>
            <li>Hot Coffee</li>
            <li>Cold Coffee</li>
        </ul>
    </li>
    <li>Suger
        <ul>
            <li>Brown Suger</li>
            <li>White Suger</li>
        </ul>
    </li>
</ul>
```
## Image

```html
<img src="images/monkey.png" alt="Monkey" width="400" height="300">
```
## Hyperlink
```html
<a href="https://google.com" target="_blank">Google</a>
```
## Table
```html
<table border="2">
    <tr>
        <th>Name</th>
        <th>Age</th>
    </tr>
    <tr>
        <td>John Doe</td>
        <td>36</td>
    </tr>
    <tr>
        <td>Jenny Doe</td>
        <td>30</td>
    </tr>
</table>
```
## Form
```html
<form action="" method="">
    Username: <input type="text" name="name">
    Password: <input type="password" name="password">
    <button type="submit">Login</button>
</form>
```
## Audio
```html
<audio controls>
    <source src="media/bark.mp3" type="audio/mpeg">
</audio>
```
## Video
```html
<video controls>
    <source src="media/rc-car.mp4" type="video/mp4">
</video>
```

## Iframe
```html
<iframe src="headings.html" width="200" height="200" frameborder="2"></iframe>
```

## Miscellaneous

```html
<!-- The <script> tag is used to embed a client-side script -->
<script>
    console.log('Hello World!')
</script>


<!-- The <style> tag is used to define style information (CSS) for a document. -->
<style>
    body{
        background:purple;
    }
</style>

<!-- The External Resource Link element
The <link> HTML element specifies relationships between the current document and an external resource.  -->
<link rel="stylesheet" href="style.css">


<!-- Meta -->
<!-- Meta tags provide additional information to the browser about documents -->
<meta name="description" content="Free Web tutorials">
<meta name="keywords" content="HTML, CSS, JavaScript">


<!-- The Document Base URL element
The <base> HTML element specifies the base URL to use for all relative URLs in a document. There can be only one <base> element in a document. -->

<head>
    <base href="https://example.com" target="_blank">
</head>
<body>
    <img src="images/monkey.png" atl="Monkey">
    <a href="lists.html">Lists</a> 
</body>

```
