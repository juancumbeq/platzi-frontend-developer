# Frontend Developer Course

<p align="center">
  <img src="https://img.shields.io/badge/Curso%20-Finalizado-brightgreen"/>
</p>

<br>

## What did I learn throug this course:
  - Introducction to frontend development
  - HTML layout
  - CSS layout
  - Responsive Design
  - CSS architecture

<br>
<br>

## Index
  - [](#objetivos)


<br>
<br>
<br>

# INTRODUCTION TO FRONTEND DEVELOPMENT
## What is HTML and CSS? What are they used for?

Websites are built using tree essential technologies: HTML, CSS and JavaScript. These tree languages form the foundations of the web.

<br>

### What is HTML?

HTML stands for HyperText Markup Language. It is the code used to build a website structure. In other words, it provides the skeleton where all elements are defined, such as: links, paragraphs, headings, buttons, images, forms, etc.

<br>

### What is CSS?

CSS stands for Cascade Style Sheets. It is the code that describes the presentation of a webpage elements, including layout, colors, fonts and spacing.

<br>

## Render Engines: From Files to Pixels.

Rendering engines are programs that translates our code into a format that browsers can understand. This way, the brower knows what to display on the screen for the user.

<br>

### Which is the browser engine?

Browsers have their own rendering engines: Chrome uses Blink, Edge uses Edge HTML, Safari uses Webkit y Firefox uses Gecko. Each engine compiles code in a slighly different way, but the result is the same: converting files into pixels.

<br>

### Rendering Process

The browser engine performs five steps to compile our code and render it on the screen. These steps are:

  - Transforming the files into an object tree, either HTML or CSS. These are known as the DOM (Document Object Model) and CSSOM (Cascading Style Sheets Object Model), respectively. Each node in the tree represents an element in the HTML or CSS file.
  - Calculating the style for each node in the DOM based on the CSSOM.
  - Determining the dimensions of each node and where it should be placed on the screen.
  - Painting or rendering the various elements as boxes or containers.
  - Compositing all the boxes into different layers to create the final image that is rendered on the screen.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/rendering-procress.png?raw=true" width= "75%" alt="Rendering Process">
</p>

<br>
<br>
<br>

# HTML LAYOUT
## HTML Document Anatomy and its Elements

Before we start writing HTML code, we should understand the structure of a document and its elements

<br>


### What are HTML elements?

Elements are the individual parts that make up an HTML file. Their structure contains:
  - Tags: There are an HTML element. Tags are divided into opening tags, represented by ```<tag>```, and closing tags, represented by ```</tag>```
  - Content: This is the text or other elements enclosed by the tag. This value is optional in some cases.

<br>

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/cheasheet-tags.png?raw=true" width= "99%" alt="Cheatsheet tags">
</p>

<br>

### What are the HTML attributes?

HTML attributes are propeties within the opening tags that control the behavior of the element. Their value is enclosed in quotation marks.

<br>

### What are empty elements?

Empty elements are those that are represented only by an opnening tag. For example, the image tag: ```<img ...>```.

<br>

### What are element nesting?

HTML element nesting involves wrapping several tags within other tags.

Think of each HTML element as a box where you can place other elements or additional boxes. These boxes will vary in size and can be positioned next to one another.

Tags that wrap other tags are called "parent" elements. For example, ```<section>``` is the parent of ```<h1>```, ```<p>```, and ```<ul>```, while ```<ul>``` is the parent of three ``<li>`` tags.

Tags that are contained within other tags are called "child" elements. For example, ``<h1>``, ``<p>``, and ``<ul>`` are children of ``<section>``, while ``<li>`` tags are children of ``<ul>``.

<br>

### Basic structure of an HTML document

The basic structure of an HTML document consists of the following key tags:

  - **Doctype tag**: The ```<!DOCTYPE html>``` tag specifies that the file is handled with HTML5.

  - **html tag**: The ```<html>``` tag defines the root element of an HTML document. All other elements must be contained within this root element. The language of the web page is specified using the **lang** attribute in this tag.

  - **head tag**: The ```<head>``` tag defines meta-information, which is not actual content on the web page. This includes links to CSS and JavaScript files, the title, and the favicon that appears in the browser tab. This is crucial for search engines like Google.

  - **body tag**: The ```<body>``` tag defines the content of the web page. It must be a direct child of ```<html>``` and the parent of all HTML tags except those used for meta-information.

<br>

Example:
```
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <title>Desafío HTML</title>
</head>

<body>
    <h1>Anatomía de un documento HTML y sus elementos</h1>
    <p>Soy un párrafo</p>
    <ul>
      <li>Soy un elemento</li>
      <li>Soy otro elemento</li>
      <li>Mi padre es "ul"</li>
    </ul>
</body>

</html>

```

<br>

### HTML comments

HTML comments are used to annotate something that will be ignored during rendering. To add an HTML comment, it is wrapped between ```<!-- and -->```, regardless of the number of lines.

<br>
<br>

## What is semantic HTML?

Semantic HTML means that each element has its own tag that accurately defines its purpose, avoiding the use of overly general tags like ```<div>``` or ```<span>```.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/semantic-schema.png?raw=true" width= "75%" alt="Semantic Schema">
</p>

<br>

### The problem with the ```div``` tag
The *div* tag defines a generic block of content that lacks semantic value. It's used for design elements like containers.

<br>

### Which tags are semantic?
Semantic tags to define a web page's interface include:

  - ```<header>```: Defines the page's header (not to be confused with ```<head>```).
  - ```<nav>```: Defines a navigation bar with links.
  - ```<section>```: Defines a section of the page.
  - ```<footer>```: Defines a footer for a page or section.
  - ```<article>```: Defines an article, which can have its own header, navigation, section, or footer.
  
Now that you know about semantic tags, try to avoid overusing ```<div>```.

<br>

Example:
```
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <title>Desafío HTML</title>
</head>

<body>
  <header>
    Soy el encabezado
  </header>
  <nav>
    <ul>
      <li>Soy un enlace</li>
      <li>Soy un enlace</li>
      <li>Soy un enlace</li>
    </ul>
  </nav>
  <article>
    Soy un artículo
  </article>
  <section>
    Soy una sección
  </section>

  <footer>Soy el pie de página</footer>
</body>

</html>
```


<br>

### Advantages of Using Semantic HTML
The benefits of using semantic HTML include:

  - Helps make your site more accessible
  - Improves your SEO (Search Engine Optimization)
  - Leads to clearer, more readable, and maintainable code
  - Helps search engines (like Google) find your page
  - [Go deep into the advantages here](https://www.espai.es/blog/2018/01/que-es-el-html-semantico/)

<br>
<br>

## Most used HTML tags

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/most-used-tags.png?raw=true" width= "75%" alt="Most used tags">
</p>

Check the links below to see more information about the most used HTML tags:

  - [htmlreference.io](https://htmlreference.io/)
  - [etiquetas html qué debes conocer](https://platzi.com/blog/etiquetas-html-debes-conocer/)

<br>

Example:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  <nav>
    <ul>
      <li>about us</li>
      <li>contact us</li>
    </ul>
  </nav>
  <section>
    <div>
      <img src="https://images.pexels.com/photos/1741205/pexels-photo-1741205.jpeg?auto=compress&cs=tinysrgb&h=650&w=940" alt="cat">
    </div>
    <div>
      <h1>Cats</h1>
      <p>Cats are awesome</p>
    </div>
  </section>
  <form action="">
    <label for="name">Name</label>
    <input type="text" id="name">
  </form>
  <a href="https://platzi.com/home">Go to Platzi</a>
</body>
</html>
```

<br>
<br>
<br>

# CSS LAYOUT
## Anatomy of a CSS declaration: selectors, properties and values

Before we start writing CSS code, we need to understand the anatomy of a style declaration.

<br>

### What is a CSS declaration?
A CSS declaration is a block that specifies the set of styles to be added to an HTML element. Its structure includes the following:

  - **Selector**: Defines the element or set of elements to which styles will be applied.
  - **Property**: The name of the CSS style.
  - **Value**: The value that the property will take on.

Example:
<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/css-declaration.png?raw=true" width= "75%" alt="CSS declaration">
</p>

<br>

### What are CSS comments?
CSS comments are used to indicate something that should be ignored. To create a CSS comment, wrap it between ```/*``` and ```*/```, regardless of the number of lines.

<br>

### Basic CSS properties
Before starting with CSS, let's use some initial CSS properties:

  - **color**: Sets the text color of an element.
  - **background-color**: Sets the background color for an element.
  - **font-size**: Sets the font size.
  - **width**: Sets the width of an element.
  - **height**: Sets the height of an element.

<br>

### Basic units of measurement
These are the initial units of measurement you should know to set the sizes of elements or typography:

  - **px**: Represents a length in pixels.
  - **%**: Represents a percentage relative to a base measurement.

<br>
<br>

## Selectors types: basics and combiners

Selectors in CSS define the HTML element or set of elements to which styles will be applied. CSS has built-in color names that you can explore. Let's dive deeper into selectors.

<br>

### What are basic selectors?
A basic selector is the minimal CSS expression to apply styles.
```
selector {
  /* Styles */
}
```
<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/basic-selectors.png?raw=true" width= "75%" alt="Basic selectors">
</p>


<br>

### Types of Basic Selectors
#### **1. Type Selector**: 
Selects all elements that match the HTML tag name.
```
div {
    /* All divs in the document */
}
```
Type Selector Challenge:
```
Try setting a background color for 10 <div> tags with a single selector using the background-color property.

HTML file:

<div>Soy el div 1</div>
<div>Soy el div 2</div>
<div>Soy el div 3</div>
<div>Soy el div 4</div>
<div>Soy el div 5</div>
<div>Soy el div 6</div>
<div>Soy el div 7</div>
<div>Soy el div 8</div>
<div>Soy el div 9</div>
<div>Soy el div 10</div>
```
```
CSS file:

div{
  background-color: aqua;
}

/* Ignora esto, por ahora */
* {
  font-size: 1.5rem;
  margin-bottom: 10px;
}
```

Check the demo [here](https://codi.link/PGRpdj5Tb3kgZWwgZGl2IDE8L2Rpdj4NCjxkaXY+U295IGVsIGRpdiAyPC9kaXY+DQo8ZGl2PlNveSBlbCBkaXYgMzwvZGl2Pg0KPGRpdj5Tb3kgZWwgZGl2IDQ8L2Rpdj4NCjxkaXY+U295IGVsIGRpdiA1PC9kaXY+DQo8ZGl2PlNveSBlbCBkaXYgNjwvZGl2Pg0KPGRpdj5Tb3kgZWwgZGl2IDc8L2Rpdj4NCjxkaXY+U295IGVsIGRpdiA4PC9kaXY+DQo8ZGl2PlNveSBlbCBkaXYgOTwvZGl2Pg0KPGRpdj5Tb3kgZWwgZGl2IDEwPC9kaXY+%7CZGl2ew0KICBiYWNrZ3JvdW5kLWNvbG9yOiBhcXVhOw0KfQ0KDQovKiBJZ25vcmEgZXN0bywgcG9yIGFob3JhICovDQoqIHsNCiAgZm9udC1zaXplOiAxLjVyZW07DQogIG1hcmdpbi1ib3R0b206IDEwcHg7DQp9%7C)

<br>

#### **2. Class Selector**
Selects all elements that match the HTML tags with a specific **class** attribute.
```
<!-- HTML File -->
<div class="card">I'm a card</div>
```

To select these elements, use a dot ``.`` followed by the exact class attribute value. This can be any value you want.
```
/* CSS File */
.card {
    /* All tags with the class "card" */
}
```

Multiple class values can exist within a single class attribute, separated by spaces.
```
<!-- HTML File -->
<div class="card card1">I'm a card</div>
<div class="card card2">I'm a card</div>
```
```
/* CSS File */
.card {
    /* All tags with the class "card" */
}

.card1 {
    /* All tags with the class "card1" */
}

.card2 {
    /* All tags with the class "card2" */
}
```

Class Selector Challenge:
```
From a set of <div> tags, try setting a background color to the ones containing the class "card" with a single selector. Then, try setting a different text color for tags containing "card1" and "card2".

HTMl File:

<div>Soy el div 1</div>
<div>Soy el div 2</div>
<div class="card card1">Soy card-1</div>
<div>Soy el div 3</div>
<div>Soy el div 4</div>
<div class="card">Soy solo card</div>
<div>Soy el div 5</div>
<div>Soy el div 6</div>
<div>Soy el div 7</div>
<div class="card card2">Soy card-2</div>
<div>Soy el div 8</div>
<div>Soy el div 9</div>
<div>Soy el div 10</div>
```
```
CSS File:

/*Agrega los selectores aquí */
.card {
  background-color: aqua;
}

.card1{
  color: red;
}

.card2{
  color: blue;
}
/*Agrega los selectores aquí */


/* Ignora esto, por ahora */
* {
  font-size: 1.5rem;
  margin-bottom: 10px;
}
```
Check the demo [here](https://codi.link/PGRpdj5Tb3kgZWwgZGl2IDE8L2Rpdj4NCjxkaXY+U295IGVsIGRpdiAyPC9kaXY+DQo8ZGl2IGNsYXNzPSJjYXJkIGNhcmQxIj5Tb3kgY2FyZC0xPC9kaXY+DQo8ZGl2PlNveSBlbCBkaXYgMzwvZGl2Pg0KPGRpdj5Tb3kgZWwgZGl2IDQ8L2Rpdj4NCjxkaXYgY2xhc3M9ImNhcmQiPlNveSBzb2xvIGNhcmQ8L2Rpdj4NCjxkaXY+U295IGVsIGRpdiA1PC9kaXY+DQo8ZGl2PlNveSBlbCBkaXYgNjwvZGl2Pg0KPGRpdj5Tb3kgZWwgZGl2IDc8L2Rpdj4NCjxkaXYgY2xhc3M9ImNhcmQgY2FyZDIiPlNveSBjYXJkLTI8L2Rpdj4NCjxkaXY+U295IGVsIGRpdiA4PC9kaXY+DQo8ZGl2PlNveSBlbCBkaXYgOTwvZGl2Pg0KPGRpdj5Tb3kgZWwgZGl2IDEwPC9kaXY+%7CLypBZ3JlZ2EgbG9zIHNlbGVjdG9yZXMgYXF1w60gKi8NCi5jYXJkIHsNCiAgYmFja2dyb3VuZC1jb2xvcjogYXF1YTsNCn0NCg0KLmNhcmQxew0KICBjb2xvcjogcmVkOw0KfQ0KDQouY2FyZDJ7DQogIGNvbG9yOiBibHVlOw0KfQ0KLypBZ3JlZ2EgbG9zIHNlbGVjdG9yZXMgYXF1w60gKi8NCg0KDQovKiBJZ25vcmEgZXN0bywgcG9yIGFob3JhICovDQoqIHsNCiAgZm9udC1zaXplOiAxLjVyZW07DQogIG1hcmdpbi1ib3R0b206IDEwcHg7DQp9%7C)

<br>

#### **3. ID Selector**
Selects the unique element that matches the HTML tag with a specific ID attribute. There should only be one ID value for the entire document.
```
<!-- HTML File -->
<button id="delete">Delete</button>
```
To select this element, use a hashtag ```#``` followed by the exact ID attribute value.
```
/* CSS File */

#delete {
    /* The only tag with the ID "delete" */
}
```

ID Selector Challenge:
```
From a set of <button> tags, find the single button for deletion. Try setting a red background color for this element.

HTML File:

<button>Soy el button 1</button>
<button>Soy el button 2</button>
<button>Soy el button 3</button>
<button>Soy el button 4</button>
<button>Soy el button 5</button>
<button>Soy el button 6</button>
<button>Soy el button 7</button>
<button>Soy el button 8</button>
<button>Soy el button 9</button>
<button id="eliminar">¡Elimínalo!!!!!!!!</button>
```
```
CSS File:

/*Agrega los selectores aquí */
#eliminar{
  background-color: red;
}
/*Agrega los selectores aquí */


/* Ignora esto, por ahora */
* {
  font-size: 1.2rem;
  padding: 5px;
  margin-bottom: 10px;
}
```
Check the demo [here](https://codi.link/PGJ1dHRvbj5Tb3kgZWwgYnV0dG9uIDE8L2J1dHRvbj4NCjxidXR0b24+U295IGVsIGJ1dHRvbiAyPC9idXR0b24+DQo8YnV0dG9uPlNveSBlbCBidXR0b24gMzwvYnV0dG9uPg0KPGJ1dHRvbj5Tb3kgZWwgYnV0dG9uIDQ8L2J1dHRvbj4NCjxidXR0b24+U295IGVsIGJ1dHRvbiA1PC9idXR0b24+DQo8YnV0dG9uPlNveSBlbCBidXR0b24gNjwvYnV0dG9uPg0KPGJ1dHRvbj5Tb3kgZWwgYnV0dG9uIDc8L2J1dHRvbj4NCjxidXR0b24+U295IGVsIGJ1dHRvbiA4PC9idXR0b24+DQo8YnV0dG9uPlNveSBlbCBidXR0b24gOTwvYnV0dG9uPg0KPGJ1dHRvbiBpZD0iZWxpbWluYXIiPsKhRWxpbcOtbmFsbyEhISEhISEhPC9idXR0b24+%7CLypBZ3JlZ2EgbG9zIHNlbGVjdG9yZXMgYXF1w60gKi8NCiNlbGltaW5hcnsNCiAgYmFja2dyb3VuZC1jb2xvcjogcmVkOw0KfQ0KLypBZ3JlZ2EgbG9zIHNlbGVjdG9yZXMgYXF1w60gKi8NCg0KDQovKiBJZ25vcmEgZXN0bywgcG9yIGFob3JhICovDQoqIHsNCiAgZm9udC1zaXplOiAxLjJyZW07DQogIHBhZGRpbmc6IDVweDsNCiAgbWFyZ2luLWJvdHRvbTogMTBweDsNCn0=%7C)

<br>

#### **4. Attribute Selector**
Selects elements that match the HTML tag with a specific attribute and value.
```
<!-- HTML File -->
<a href="https://example.com">Visit Example</a>
```

To select these elements, use the tag name followed by square brackets ``[]`` containing the specified attribute and value.
```
CSS File:

a[href="https://example.com"] {
    /* All <a> tags with an href attribute value of "https://example.com" */
}
```

Attribute Selector Challenge:
```
Try setting a background color to all <a> tags that contain the href attribute with the value "https://example.com".

HTML File:
<a href="https://platzi.com">Ir a platzi</a>
<a href="#">Soy un enlace 1</a>
<a href="#">Soy un enlace 2</a>
<a href="#">Soy un enlace 3</a>
<a href="https://platzi.com">Ir a platzi</a>
<a href="#">Soy un enlace 5</a>
<a href="#">Soy un enlace 6</a>
<a href="#">Soy un enlace 7</a>
<a href="https://platzi.com">Ir a platzi</a>
<a href="#">Soy un enlace 8</a>
<a href="#">Soy un enlace 9</a>
```
```
CSS File:
/*Agrega los selectores aquí */
a[href="https://platzi.com"]{
  background-color: greenyellow;
}
/*Agrega los selectores aquí */


/* Ignora esto, por ahora */
* {
  font-size: 1.2rem;
  padding: 5px;
  margin-bottom: 10px;
}

a {
  display: block;
}
```

Check the demo [here](https://codi.link/PGEgaHJlZj0iaHR0cHM6Ly9wbGF0emkuY29tIj5JciBhIHBsYXR6aTwvYT4NCjxhIGhyZWY9IiMiPlNveSB1biBlbmxhY2UgMTwvYT4NCjxhIGhyZWY9IiMiPlNveSB1biBlbmxhY2UgMjwvYT4NCjxhIGhyZWY9IiMiPlNveSB1biBlbmxhY2UgMzwvYT4NCjxhIGhyZWY9Imh0dHBzOi8vcGxhdHppLmNvbSI+SXIgYSBwbGF0emk8L2E+DQo8YSBocmVmPSIjIj5Tb3kgdW4gZW5sYWNlIDU8L2E+DQo8YSBocmVmPSIjIj5Tb3kgdW4gZW5sYWNlIDY8L2E+DQo8YSBocmVmPSIjIj5Tb3kgdW4gZW5sYWNlIDc8L2E+DQo8YSBocmVmPSJodHRwczovL3BsYXR6aS5jb20iPklyIGEgcGxhdHppPC9hPg0KPGEgaHJlZj0iIyI+U295IHVuIGVubGFjZSA4PC9hPg0KPGEgaHJlZj0iIyI+U295IHVuIGVubGFjZSA5PC9hPg==%7CLypBZ3JlZ2EgbG9zIHNlbGVjdG9yZXMgYXF1w60gKi8NCmFbaHJlZj0iaHR0cHM6Ly9wbGF0emkuY29tIl17DQogIGJhY2tncm91bmQtY29sb3I6IGdyZWVueWVsbG93Ow0KfQ0KLypBZ3JlZ2EgbG9zIHNlbGVjdG9yZXMgYXF1w60gKi8NCg0KDQovKiBJZ25vcmEgZXN0bywgcG9yIGFob3JhICovDQoqIHsNCiAgZm9udC1zaXplOiAxLjJyZW07DQogIHBhZGRpbmc6IDVweDsNCiAgbWFyZ2luLWJvdHRvbTogMTBweDsNCn0NCg0KYSB7DQogIGRpc3BsYXk6IGJsb2NrOw0KfQ==%7C)

<br>


#### **5. Universal Selector**
Selects all elements in the document using an asterisk ``*``.
```
* {
    /* All elements */
}
```

Universal Selector Challenge:
```
Try setting a background color to all elements in the document.

HTML File:
<div>
  <ul>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
  </ul>
</div>
<div></div>
<div>
  <ul>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
  </ul>
</div>
<div></div>
<div>
  <ul>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
  </ul>
</div>
<div></div>
```
```
CSS File:

/*Agrega los selectores aquí */
* {
  background-color: papayawhip;
}
/*Agrega los selectores aquí */
```

Check the demo [here](https://codi.link/PGRpdj4NCiAgPHVsPg0KICAgIDxsaT48L2xpPg0KICAgIDxsaT48L2xpPg0KICAgIDxsaT48L2xpPg0KICAgIDxsaT48L2xpPg0KICAgIDxsaT48L2xpPg0KICA8L3VsPg0KPC9kaXY+DQo8ZGl2PjwvZGl2Pg0KPGRpdj4NCiAgPHVsPg0KICAgIDxsaT48L2xpPg0KICAgIDxsaT48L2xpPg0KICAgIDxsaT48L2xpPg0KICAgIDxsaT48L2xpPg0KICAgIDxsaT48L2xpPg0KICA8L3VsPg0KPC9kaXY+DQo8ZGl2PjwvZGl2Pg0KPGRpdj4NCiAgPHVsPg0KICAgIDxsaT48L2xpPg0KICAgIDxsaT48L2xpPg0KICAgIDxsaT48L2xpPg0KICAgIDxsaT48L2xpPg0KICAgIDxsaT48L2xpPg0KICA8L3VsPg0KPC9kaXY+DQo8ZGl2PjwvZGl2Pg0KDQo=%7CLypBZ3JlZ2EgbG9zIHNlbGVjdG9yZXMgYXF1w60gKi8NCiogew0KICBiYWNrZ3JvdW5kLWNvbG9yOiBwYXBheWF3aGlwOw0KfQ0KLypBZ3JlZ2EgbG9zIHNlbGVjdG9yZXMgYXF1w60gKi8NCg==%7C)

<br>

### What Are Combinator Selectors?
A combinator selector is the combination of two or more basic selectors.
```
selector1 selector2 selector3 {
    /* Styles */
}
```
<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/combinator-selectors.png?raw=true" width= "75%" alt="Combinator selectors">
</p>

<br>

### Types of Combinator Selectors
#### **1. Descendant Combinator**
Selects all elements on the right that are descendants of the selector on the left, regardless of depth. These selectors are separated by a space.
```
parent children {
    /* All descendants of the parent */
}

div p {
    /* All <p> descendants of <div> */
}

.container img {
    /* All <img> descendants of the class "container" */
}
```
Descendant Combinator Challenge:
```
Try setting a text color to all <li> tags that are children of the class "container".

HTML File:

<nav>
  <ul>
    <li>Home</li>
    <li>Más opciones</li>
  </ul>
</nav>
<div class="container">
  <ul>
    <li>Lista 1</li>
    <li>Lista 2</li>
    <li>Lista 3</li>
    <li>Lista 4</li>
    <li>Lista 5</li>
    <li>Lista 6</li>
    <li>Lista 7</li>
    <li>Lista 8</li>
    <li>Lista 9</li>
    <li>Lista 10</li>
  </ul>
</div>
<footer>
  <ul>
    <li>Conoce la empresa</li>
    <li>Más actividades</li>
    <li>Acerca de nosotros</li>
  </ul>
</footer>

```

```
CSS File:
* {
  font-size: 1.2rem;
}

/*Agrega los selectores aquí */
.container li{
  color: red;
}
/*Agrega los selectores aquí */
```
Check the demo [here](https://codi.link/PG5hdj4NCiAgPHVsPg0KICAgIDxsaT5Ib21lPC9saT4NCiAgICA8bGk+TcOhcyBvcGNpb25lczwvbGk+DQogIDwvdWw+DQo8L25hdj4NCjxkaXYgY2xhc3M9ImNvbnRhaW5lciI+DQogIDx1bD4NCiAgICA8bGk+TGlzdGEgMTwvbGk+DQogICAgPGxpPkxpc3RhIDI8L2xpPg0KICAgIDxsaT5MaXN0YSAzPC9saT4NCiAgICA8bGk+TGlzdGEgNDwvbGk+DQogICAgPGxpPkxpc3RhIDU8L2xpPg0KICAgIDxsaT5MaXN0YSA2PC9saT4NCiAgICA8bGk+TGlzdGEgNzwvbGk+DQogICAgPGxpPkxpc3RhIDg8L2xpPg0KICAgIDxsaT5MaXN0YSA5PC9saT4NCiAgICA8bGk+TGlzdGEgMTA8L2xpPg0KICA8L3VsPg0KPC9kaXY+DQo8Zm9vdGVyPg0KICA8dWw+DQogICAgPGxpPkNvbm9jZSBsYSBlbXByZXNhPC9saT4NCiAgICA8bGk+TcOhcyBhY3RpdmlkYWRlczwvbGk+DQogICAgPGxpPkFjZXJjYSBkZSBub3NvdHJvczwvbGk+DQogIDwvdWw+DQo8L2Zvb3Rlcj4NCg==%7CKiB7DQogIGZvbnQtc2l6ZTogMS4ycmVtOw0KfQ0KDQovKkFncmVnYSBsb3Mgc2VsZWN0b3JlcyBhcXXDrSAqLw0KLmNvbnRhaW5lciBsaXsNCiAgY29sb3I6IHJlZDsNCn0NCi8qQWdyZWdhIGxvcyBzZWxlY3RvcmVzIGFxdcOtICovDQo=%7C)

<br>

#### **2. Child Combinator**
Selects all elements on the right that are direct children of the selector on the left. These selectors are separated by ``>``.
```
parent > direct_children {
    /* All direct children of the parent */
}

div > p {
    /* All direct children <p> of <div> */
}

.container > img {
    /* All direct children <img> of the class "container" */
}
```

Child Combinator Challenge:
```
Try setting a text color to all <p> tags that are direct children of the class "container".

HTML File:

<div class="container">
  <p>Soy un hijo directo</p>
  <p>Soy un hijo directo</p>
  <p>Soy un hijo directo</p>
  <p>Soy un hijo directo</p>
  <p>Soy un hijo directo</p>
  <p>Soy un hijo directo</p>
  <p>Soy un hijo directo</p>
  <p>Soy un hijo directo</p>
  <p>Soy un hijo directo</p>
  <p>Soy un hijo directo</p>
  <div>
    <p>Soy un hijo indirecto o ñeto</p>
    <p>Soy un hijo indirecto o ñeto</p>
    <p>Soy un hijo indirecto o ñeto</p>
    <p>Soy un hijo indirecto o ñeto</p>
    <p>Soy un hijo indirecto o ñeto</p>
  </div>
</div>
```
```
CSS File:

* {
  font-size: 1.2rem;
}

/*Agrega los selectores aquí */
.container > p {
  color: red;
}
/*Agrega los selectores aquí */
```
Check the demo [here](https://codi.link/PGRpdiBjbGFzcz0iY29udGFpbmVyIj4NCiAgPHA+U295IHVuIGhpam8gZGlyZWN0bzwvcD4NCiAgPHA+U295IHVuIGhpam8gZGlyZWN0bzwvcD4NCiAgPHA+U295IHVuIGhpam8gZGlyZWN0bzwvcD4NCiAgPHA+U295IHVuIGhpam8gZGlyZWN0bzwvcD4NCiAgPHA+U295IHVuIGhpam8gZGlyZWN0bzwvcD4NCiAgPHA+U295IHVuIGhpam8gZGlyZWN0bzwvcD4NCiAgPHA+U295IHVuIGhpam8gZGlyZWN0bzwvcD4NCiAgPHA+U295IHVuIGhpam8gZGlyZWN0bzwvcD4NCiAgPHA+U295IHVuIGhpam8gZGlyZWN0bzwvcD4NCiAgPHA+U295IHVuIGhpam8gZGlyZWN0bzwvcD4NCiAgPGRpdj4NCiAgICA8cD5Tb3kgdW4gaGlqbyBpbmRpcmVjdG8gbyDDsWV0bzwvcD4NCiAgICA8cD5Tb3kgdW4gaGlqbyBpbmRpcmVjdG8gbyDDsWV0bzwvcD4NCiAgICA8cD5Tb3kgdW4gaGlqbyBpbmRpcmVjdG8gbyDDsWV0bzwvcD4NCiAgICA8cD5Tb3kgdW4gaGlqbyBpbmRpcmVjdG8gbyDDsWV0bzwvcD4NCiAgICA8cD5Tb3kgdW4gaGlqbyBpbmRpcmVjdG8gbyDDsWV0bzwvcD4NCiAgPC9kaXY+DQo8L2Rpdj4NCg==%7CKiB7DQogIGZvbnQtc2l6ZTogMS4ycmVtOw0KfQ0KDQovKkFncmVnYSBsb3Mgc2VsZWN0b3JlcyBhcXXDrSAqLw0KLmNvbnRhaW5lciA+IHAgew0KICBjb2xvcjogcmVkOw0KfQ0KLypBZ3JlZ2EgbG9zIHNlbGVjdG9yZXMgYXF1w60gKi8NCg==%7C)

<br>

#### **3. Adjacent Sibling Combinator**
Selects all elements on the right that are adjacent to the selector on the left. These selectors are separated by ``+``.
```
element + adjacent {
    /* Adjacent elements */
}

div + p {
    /* All <p> adjacent to <div> */
}

.container + img {
    /* All <img> adjacent to the class "container" */
}
```
Adjacent means they share the same parent and are placed immediately after another element. For example, in the following code, ``<div>`` is adjacent to ``<h1>``, and ``<p>`` is adjacent to ``<div>``. However, ``<h1>`` is not adjacent to ``<div>``, and ``<div>`` is not adjacent to ``<p>``.
```
<!-- HTML File -->
<h1>I'm a header</h1>
<div>I'm a div</div>
<p>I'm a paragraph</p>
```

Adjacent Sibling Combinator Challenge:
```
Try setting a text color to all <p> tags that are adjacent to <div> tags.

HTML File:

<p>Soy otro párrafo</p>
<div>Soy un div</div>
<p>Soy un párrafo adyacente a div</p>
<p>Soy otro párrafo</p>
<p>Soy otro párrafo</p>
<hr/>
<p>Soy otro párrafo</p>
<div>Soy un div</div>
<p>Soy un párrafo adyacente a div</p>
<p>Soy otro párrafo</p>
<p>Soy otro párrafo</p>
<hr/>
<p>Soy otro párrafo</p>
<div>Soy un div</div>
<p>Soy un párrafo adyacente a div</p>
<p>Soy otro párrafo</p>
<p>Soy otro párrafo</p>
<hr/>
<p>Soy otro párrafo</p>
<div>Soy un div</div>
<p>Soy un párrafo adyacente a div</p>
<p>Soy otro párrafo</p>
<p>Soy otro párrafo</p>
<hr/>
```
```
CSS File:

/*Agrega los selectores aquí */
div + p {
  color: red;
}
/*Agrega los selectores aquí */
```

Check the demo [here](https://codi.link/PHA+U295IG90cm8gcMOhcnJhZm88L3A+DQo8ZGl2PlNveSB1biBkaXY8L2Rpdj4NCjxwPlNveSB1biBww6FycmFmbyBhZHlhY2VudGUgYSBkaXY8L3A+DQo8cD5Tb3kgb3RybyBww6FycmFmbzwvcD4NCjxwPlNveSBvdHJvIHDDoXJyYWZvPC9wPg0KPGhyLz4NCjxwPlNveSBvdHJvIHDDoXJyYWZvPC9wPg0KPGRpdj5Tb3kgdW4gZGl2PC9kaXY+DQo8cD5Tb3kgdW4gcMOhcnJhZm8gYWR5YWNlbnRlIGEgZGl2PC9wPg0KPHA+U295IG90cm8gcMOhcnJhZm88L3A+DQo8cD5Tb3kgb3RybyBww6FycmFmbzwvcD4NCjxoci8+DQo8cD5Tb3kgb3RybyBww6FycmFmbzwvcD4NCjxkaXY+U295IHVuIGRpdjwvZGl2Pg0KPHA+U295IHVuIHDDoXJyYWZvIGFkeWFjZW50ZSBhIGRpdjwvcD4NCjxwPlNveSBvdHJvIHDDoXJyYWZvPC9wPg0KPHA+U295IG90cm8gcMOhcnJhZm88L3A+DQo8aHIvPg0KPHA+U295IG90cm8gcMOhcnJhZm88L3A+DQo8ZGl2PlNveSB1biBkaXY8L2Rpdj4NCjxwPlNveSB1biBww6FycmFmbyBhZHlhY2VudGUgYSBkaXY8L3A+DQo8cD5Tb3kgb3RybyBww6FycmFmbzwvcD4NCjxwPlNveSBvdHJvIHDDoXJyYWZvPC9wPg0KPGhyLz4=%7CLypBZ3JlZ2EgbG9zIHNlbGVjdG9yZXMgYXF1w60gKi8NCmRpdiArIHAgew0KICBjb2xvcjogcmVkOw0KfQ0KLypBZ3JlZ2EgbG9zIHNlbGVjdG9yZXMgYXF1w60gKi8NCg==%7C)

<br>

#### **4. General Sibling Combinator**
Selects all elements on the right that are siblings of the selector on the left. These selectors are separated by ``~``.
```
element ~ siblings {
    /* Sibling elements */
}

div ~ p {
    /* All <p> siblings of <div> */
}

.container ~ img {
    /* All <img> siblings of the class "container" */
}
```
Siblings share the same parent and are placed after one another. For example, in the following code, ``<div>`` and ``<p>`` are siblings of ``<h1>``, but ``<h1>`` is not a sibling of ``<div>``, and ``<div>`` is not a sibling of ``<p>``.
```
<!-- HTML File -->
<h1>I'm a header</h1>
<div>I'm a div</div>
<p>I'm a paragraph</p>
```

General Sibling Combinator Challenge:
```
Try to set a text color for all <p> tags that are siblings of <div>.

HTML File:

<div class="container">
  <p>Soy otro párrafo</p>
  <div>Soy un div</div>
  <p>Soy un párrafo hermano de div</p>
  <p>Soy un párrafo hermano de div</p>
  <p>Soy un párrafo hermano de div</p>
</div>
<hr/>
```
```
CSS File:
/*Agrega los selectores aquí */
div ~ p {
  color: red;
}
/*Agrega los selectores aquí */

```
Check the demo [here](https://codi.link/PGRpdiBjbGFzcz0iY29udGFpbmVyIj4NCiAgPHA+U295IG90cm8gcMOhcnJhZm88L3A+DQogIDxkaXY+U295IHVuIGRpdjwvZGl2Pg0KICA8cD5Tb3kgdW4gcMOhcnJhZm8gaGVybWFubyBkZSBkaXY8L3A+DQogIDxwPlNveSB1biBww6FycmFmbyBoZXJtYW5vIGRlIGRpdjwvcD4NCiAgPHA+U295IHVuIHDDoXJyYWZvIGhlcm1hbm8gZGUgZGl2PC9wPg0KPC9kaXY+DQo8aHIvPg==%7CLypBZ3JlZ2EgbG9zIHNlbGVjdG9yZXMgYXF1w60gKi8NCmRpdiB+IHAgew0KICBjb2xvcjogcmVkOw0KfQ0KLypBZ3JlZ2EgbG9zIHNlbGVjdG9yZXMgYXF1w60gKi8NCg==%7C)


<br>
<br>

## Selectors types: pseudoclasses and pseudoelements
There are other types of selectors, besides basic and combinator selectors, capable of changing a state or adding something extra to the element. These are called pseudo-classes and pseudo-elements.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/pseudoclasses-pseudoelements.png?raw=true" width= "75%" alt="Pseudo-clases and pseudo-elements">
</p>

<br>

### What Are Pseudo-classes?
A pseudo-class defines the style for a special state of an element.

Index of Standard Pseudo-classes: [here](https://developer.mozilla.org/es/docs/Web/CSS/Pseudo-classes#indice_de_las_pseudo-clases_est%C3%A1ndar)

Learn more about pseudo-classes [here](https://css-tricks.com/pseudo-class-selectors/)

<br>

### Syntax
```
selector : pseudo-class { 
    property: value;
}
```

### Some pseudo-classes
  - **:hover**: Represents the state when the cursor is hovering over the element.      
    - [Example](https://codi.link/PGRpdj5TZcOxw6FsYW1lPC9kaXY+%7CZGl2IHsNCiAgZm9udC1zaXplOiAzcmVtOw0KICBjdXJzb3I6IHBvaW50ZXI7DQp9DQoNCmRpdjpob3ZlciB7DQogIGNvbG9yOiByZWQ7DQp9%7C)
  
  - **:active**: Represents the state of an element that is being interacted with (like when a button is clicked). 
    - [Example](https://codi.link/PGEgaHJlZj0iIyI+Q2xpY2tlYW1lPC9hPg==%7CYSB7DQogIGZvbnQtc2l6ZTogM3JlbTsNCn0NCg0KYTpsaW5rIHsNCiAgY29sb3I6IHJlZDsNCn0=%7C)

  - **:visited**: Represents the state of a link that has already been visited.
    - [Example](https://codi.link/PGEgaHJlZj0iIyI+Q2xpY2tlYW1lPC9hPg==%7CYSB7DQogIGZvbnQtc2l6ZTogM3JlbTsNCn0NCg0KYTp2aXNpdGVkIHsNCiAgY29sb3I6IHJlZDsNCn0=%7C)

  - **:not()**: Represents the state when the specified selectors do not match.
    - [Example](https://codi.link/PGRpdj5BenVsPC9kaXY+DQo8ZGl2PkF6dWw8L2Rpdj4NCjxkaXYgY2xhc3M9Im5lZ3JvIj5OZWdybzwvZGl2Pg0KPGRpdj5BenVsPC9kaXY+DQo8ZGl2PkF6dWw8L2Rpdj4=%7CZGl2IHsNCiAgZm9udC1zaXplOiAzcmVtOw0KfQ0KDQpkaXY6bm90KC5uZWdybykgew0KICBjb2xvcjogYmx1ZTsNCn0=%7C)

  - **:nth-child()**: Represents the state where child elements match according to the specified value.
    - Key terms:
      - odd: The child elements in odd positions.
      - even: The child elements in even positions.
    - Mathematical formula: An + B, where A and B are integers.
    - [Example](https://codi.link/PGRpdj4xIE5lZ3JvPC9kaXY+DQo8ZGl2PjIgQXp1bDwvZGl2Pg0KPGRpdj4zIE5lZ3JvPC9kaXY+DQo8ZGl2PjQgTmVncm88L2Rpdj4NCjxkaXY+NSBOZWdybzwvZGl2Pg==%7CZGl2IHsNCiAgZm9udC1zaXplOiAzcmVtOw0KfQ0KDQpkaXY6bnRoLWNoaWxkKDIpIHsNCiAgY29sb3I6IGJsdWU7DQp9%7C)

<br>

### What Are Pseudo-elements?
A pseudo-element defines the style of a specific part of an element.

List of Pseudo-elements: [here](https://developer.mozilla.org/es/docs/web/css/pseudo-elements#lista_de_pseudoelementos)

Learn more about pseudo-elements [here](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements)

<br>

### Syntax
```
selector :: pseudo-element { 
    property: value;
}
```
<br>

### Some pseudo-elements

  - **::before**: Adds content before the element. The content is added using the CSS content property.
    - [Example](https://codi.link/PGgxPlTDrXR1bG88L2gxPg0KPGgyPlN1YnTDrXR1bG9zPC9oMj4NCjxoMj5TdWJ0w610dWxvczwvaDI+DQo8aDI+U3VidMOtdHVsb3M8L2gyPg0KPGgyPlN1YnTDrXR1bG9zPC9oMj4NCjxoMj5TdWJ0w610dWxvczwvaDI+DQo=%7CaDI6YmVmb3JlIHsNCiAgY29udGVudDogIiAqICI7DQogIGNvbG9yOiByZWQ7DQp9%7C)

  - **::after**: Adds content after the element. The content is added using the CSS content property.
    - [Example](https://codi.link/PCEtLSBOYXZiYXIgaW1wcm92aXNhZGEgLS0+DQo8bmF2Pg0KICA8dWw+DQogICAgPGxpPkhvbWU8L2xpPg0KICAgIDxsaT5EZXN0YWNhZG9zPC9saT4NCiAgICA8bGk+RWxlbWVudG9zPC9saT4NCiAgICA8bGk+Q2xhc2VzPC9saT4NCiAgICA8bGk+TcOhcy4uLjwvbGk+DQogIDwvdWw+DQo8L25hdj4NCg==%7CbmF2IHVsIHsNCiAgbGlzdC1zdHlsZTogbm9uZTsNCiAgZGlzcGxheTogZmxleDsNCiAganVzdGlmeS1jb250ZW50OiBzcGFjZS1hcm91bmQ7DQogIGN1cnNvcjogcG9pbnRlcjsNCn0NCg0KbmF2IHVsIGxpOjphZnRlciB7DQogIGNvbnRlbnQ6ICJ8IjsNCiAgbWFyZ2luOiAxcmVtOw0KICBjb2xvcjogcmVkOw0KfQ==%7C)

  - **::first-letter**: Adds styles to the first letter of the text in any element.
    - [Example](https://codi.link/PHA+U295IG90cm8gcMOhcnJhZm88L3A+DQo8cD5Tb3kgb3RybyBww6FycmFmbzwvcD4NCjxwPlNveSBvdHJvIHDDoXJyYWZvPC9wPg0KPHA+U295IG90cm8gcMOhcnJhZm88L3A+DQo8cD5Tb3kgb3RybyBww6FycmFmbzwvcD4NCjxwPlNveSBvdHJvIHDDoXJyYWZvPC9wPg0KPHA+U295IG90cm8gcMOhcnJhZm88L3A+DQo8cD5Tb3kgb3RybyBww6FycmFmbzwvcD4NCjxwPlNveSBvdHJvIHDDoXJyYWZvPC9wPg0K%7COjpmaXJzdC1sZXR0ZXJ7DQogIGNvbG9yOiByZWQ7DQp9DQo=%7C)

<br>
<br>

## Cascading and specificity in CSS
At some point, when you're creating a website, you might encounter issues with styles, such as:

  - Why isn't the color I'm applying taking effect?
  - Why is this element behaving differently?

The issue is likely related to cascade or specificity.

<br>

### What is CSS Cascade?
The cascade is the concept that determines which styles override others, prioritizing those that appear later in the code. Remember that CSS stands for Cascading Style Sheets.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/css-cascade.png?raw=true" width= "75%" alt="CSS Cascade">
</p>


Look at the following code and identify the text color for the ``<h1>`` tag:
```
h1 {
    color: red;
}

h1 {
    color: blue;
}
```
The ``<h1>`` tag will have ``blue`` text because it's declared later in the code. This applies to any CSS property that is repeated elsewhere earlier in the code.

Example of CSS Cascade: [here](https://codi.link/PGgxPkNhc2NhZGE8L2gxPg==%7CaDEgew0KICBjb2xvcjogcmVkOw0KfQ0KDQpoMSB7DQogIGNvbG9yOiBibHVlOw0KfQ==%7C)

However, this happens when the **specificity** of a CSS rule has the same value. But what is specificity?

<br>

### What is CSS Specificity?
Specificity is the value assigned to a CSS rule indicating how specific the style is, allowing browsers to determine which styles override others, regardless of where they are in the code. The style with higher specificity will be applied.

<br>

### Types of Specificity in CSS
There are six types of specificity with their corresponding values, where X is the number of styles containing them. Take a look at this image:

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/specificity.png?raw=true" width= "75%" alt="Specificity">
</p>

<br>

### Values with Higher Specificity
The reserved word ``!important`` is a value for any CSS property that provides a specificity of 10,000, causing it to take precedence over other styles. This is considered a bad practice and should not be used.
```
h1 {
    color: red !important;
}
```

Example of !important [here](https://codi.link/PGgxPkVzcGVjaWZpY2lkYWQ8L2gxPg0K%7CaDEgew0KICBjb2xvcjogcmVkOw0KfQ0KDQpoMSB7DQogIGNvbG9yOiBncmVlbiAhaW1wb3J0YW50Ow0KfQ0KDQpoMSB7DQogIGNvbG9yOiBibHVlOw0KfQ0KDQpoMSB7DQogIGNvbG9yOiBwYXBheWF3aGlwOw0KfQ0K%7C)

<br>

### Inline Styles
Inline styles are CSS properties written directly in HTML using the style attribute within any tag. This is also a bad practice and should be avoided.
```
<h1 style="color: blue;">Specificity</h1>
```

Example of Inline Styles [here](https://codi.link/PGgxIHN0eWxlPSJjb2xvcjogYmx1ZTsiPkVzcGVjaWZpY2lkYWQ8L2gxPg0K%7CaDEgew0KICBjb2xvcjogcmVkOw0KfQ0KDQpoMSB7DQogIGNvbG9yOiBncmVlbjsNCn0NCg0K%7C)

<br>

### Specificity in Selectors
Since you're familiar with selectors, you know that ID selectors are more specific than classes, attributes, and pseudo-classes. The latter are more specific than elements and pseudo-elements. The universal selector has a specificity of zero.

In a project, you should avoid using ``!important`` and inline styles, focusing solely on the specificity of selectors. However, keep in mind that combinator selectors add up the specificity of each basic selector to obtain the total specificity of the CSS rule.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/specificity-selectors.png?raw=true" width= "75%" alt="Specificity selectors">
</p>

If you're using **Visual Studio Code**, hovering over a selector will show the total specificity. Specificity Calculator is a website where you can calculate specificity.

In the other hand, there is a [specificity calculator](https://specificity.keegan.st/)
<br>
<br>

## Most used Display Types: Block, Inline and Inline-block
The ``display`` property sets the type of visual representation for HTML elements without affecting the normal flow of elements.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/display.png?raw=true" width= "75%" alt="Display">
</p>

Some tags have a default display type, such as ``<div>`` which has ``display: block``, ``<span>`` which has ``display: inline``, and ``<button>`` which has ``display: inline-block``.

<br>

### Block Display
``display: block`` means that an element will occupy the entire available width by default, and the next element will be placed below it.

It's possible to add **width** and **height** measurements to these elements.

You can also add all the properties of the box model (don't worry, we'll cover this concept later).

[Example of Block Display](https://codi.link/PGRpdj5Tb3kgZGlzcGxheSBibG9jazwvZGl2Pg0KPGRpdj5Tb3kgZGlzcGxheSBibG9jazwvZGl2Pg0KPGRpdiBjbGFzcz0iY29uX21lZGlkYXMiPlNveSBkaXNwbGF5IGJsb2NrPC9kaXY+DQoNCg==%7CLyogUXVpdGEgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBlbCBjb21wb3J0YW1pZW50byAqLw0KZGl2ew0KICBiYWNrZ3JvdW5kLWNvbG9yOiBhcXVhOw0KICAvKiBtYXJnaW46IDEwcHg7ICovDQogIC8qIHBhZGRpbmc6IDEwcHg7ICovDQp9DQoNCi5jb25fbWVkaWRhcyB7DQogIC8qIHdpZHRoOiAyMDBweDsgKi8NCiAgLyogaGVpZ2h0OiAyMDBweDsgKi8NCn0NCg0KLyogSWdub3JhIGVzdG9zIGVzdGlsb3MsIHBvciBhaG9yYSAqLw0KKiB7DQogIGZvbnQtc2l6ZTogMS4ycmVtOw0KICBtYXJnaW46IDA7DQp9DQoNCg0KDQo=%7C)

<br>

### Inline Display
``display: inline`` means that an element will occupy only the space of its content, and the next element will be placed to its right.

You can't add **width** and **height** measurements to these elements.

Additionally, you can't apply all the box model properties; only the margin property on the horizontal axis works (again, we'll cover this concept later).

[Example of Inline Display](https://codi.link/PHNwYW4+U295IGRpc3BsYXkgaW5saW5lPC9zcGFuPg0KPHNwYW4+U295IGRpc3BsYXkgaW5saW5lPC9zcGFuPg0KPHNwYW4+U295IGRpc3BsYXkgaW5saW5lPC9zcGFuPg0KPHNwYW4+U295IGRpc3BsYXkgaW5saW5lPC9zcGFuPg0KPHNwYW4gY2xhc3M9ImNvbl9tZWRpZGFzIj5Tb3kgZGlzcGxheSBpbmxpbmU8L3NwYW4+DQoNCg==%7CLyogUXVpdGEgeSBhZ3JlZ2EgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBlbCBjb21wb3J0YW1pZW50byAqLw0Kc3BhbnsNCiAgYmFja2dyb3VuZC1jb2xvcjogYXF1YTsNCiAgLyogbWFyZ2luOiAyMHB4OyAqLw0KICAvKiBwYWRkaW5nOiAyMHB4OyAqLw0KfQ0KDQouY29uX21lZGlkYXMgew0KICAvKiB3aWR0aDogMjAwcHg7ICovDQogIC8qIGhlaWdodDogMjAwcHg7ICovDQp9DQoNCi8qIElnbm9yYSBlc3RvcyBlc3RpbG9zLCBwb3IgYWhvcmEgKi8NCiogew0KICBmb250LXNpemU6IDEuMnJlbTsNCiAgbWFyZ2luOiAwOw0KfQ0KDQoNCg0K%7C)

<br>

### Inline-Block Display
``display: inline-block`` combines the advantages of block—being able to set measurements and apply box model properties correctly—with the advantages of inline, allowing elements to be positioned side by side in the same line.

If an element exceeds the total content width, it moves to the next line below.

[Example of Inline-Block Display](https://codi.link/PGJ1dHRvbj5Tb3kgZGlzcGxheSBpbmxpbmUtYmxvY2s8L2J1dHRvbj4NCjxidXR0b24+U295IGRpc3BsYXkgaW5saW5lLWJsb2NrPC9idXR0b24+DQo8YnV0dG9uPlNveSBkaXNwbGF5IGlubGluZS1ibG9jazwvYnV0dG9uPg0KPGJ1dHRvbj5Tb3kgZGlzcGxheSBpbmxpbmUtYmxvY2s8L2J1dHRvbj4NCjxidXR0b24gY2xhc3M9ImNvbl9tZWRpZGFzIj5Tb3kgZGlzcGxheSBpbmxpbmUtYmxvY2s8L2J1dHRvbj4NCg0K%7CLyogUXVpdGEgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBlbCBjb21wb3J0YW1pZW50byAqLw0KYnV0dG9uew0KICAvKiBtYXJnaW46IDEwcHg7ICovDQogIC8qIHBhZGRpbmc6IDEwcHg7ICovDQp9DQoNCi5jb25fbWVkaWRhcyB7DQogIC8qIHdpZHRoOiAzMDBweDsgKi8NCiAgLyogaGVpZ2h0OiAxMDBweDsgKi8NCn0NCg0KLyogSWdub3JhIGVzdG9zIGVzdGlsb3MsIHBvciBhaG9yYSAqLw0KKiB7DQogIGZvbnQtc2l6ZTogMS4xcmVtOw0KICBtYXJnaW46IDA7DQp9DQoNCg0KDQo=%7C)

<br>

### No Display (None)
``display: none`` disables the display of an element, making it as if the element doesn't exist.

[Example of Display None](https://codi.link/PGRpdj48L2Rpdj4NCjxkaXY+PC9kaXY+DQo8ZGl2IGNsYXNzPSJkZXNhcGFyZWNlciI+DQogIEVuIG1pIHNpZ3VpZW50ZSB0cnVjbywgwqF2b3kgYSBkZXNhcGFyZWNlciENCjwvZGl2Pg0KPGRpdj48L2Rpdj4NCjxkaXY+PC9kaXY+DQo=%7CLyogUXVpdGEgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBlbCBjb21wb3J0YW1pZW50byAqLw0KLmRlc2FwYXJlY2Vyew0KICAvKiBkaXNwbGF5OiBub25lOyAqLw0KICBiYWNrZ3JvdW5kLWNvbG9yOiBjb3JuZmxvd2VyYmx1ZTsNCiAgDQp9DQoNCi8qIElnbm9yYSBlc3RvcyBlc3RpbG9zLCBwb3IgYWhvcmEgKi8NCiogew0KICBib3gtc2l6aW5nOiBib3JkZXItYm94Ow0KICBmb250LXNpemU6IDEuMXJlbTsNCiAgbWFyZ2luOiAwOw0KfQ0KDQpib2R5ew0KICBkaXNwbGF5OiBmbGV4Ow0KfQ0KDQpkaXZ7DQogIGJhY2tncm91bmQtY29sb3I6IGNvcmFsOw0KICB3aWR0aDogMTIwcHg7DQogIGhlaWdodDogMTIwcHg7DQogIGZvbnQtd2VpZ2h0OiA4MDA7DQogIHBhZGRpbmc6IDhweDsNCn0NCg0KDQoNCg==%7C)

<br>
<br>

## Most used Display Types: Flexbox and CSS grid
Flexbox and Grid are recent methods for displaying elements, and each has its own features for effectively creating interfaces. Both start from a parent container that gives child elements special positioning powers.

Both are highly useful tools in development, especially for creating user-friendly interfaces that are adaptable to any device, known as responsive design.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/flex-grid.png?raw=true" width= "75%" alt="Flex and grid">
</p>

<br>

### What is Flexbox?
Flexbox involves arranging child elements along a single axis, usually horizontally by default. The parent element or container must have the display property set to **flex**. From there, you can organize the children as needed.

[Example of Flexbox](https://codi.link/PGRpdiBjbGFzcz0iY29udGFpbmVyIj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCjwvZGl2Pg0KDQoNCg0K%7CKiB7DQogIG1hcmdpbjogMDsNCiAgcGFkZGluZzogMDsNCiAgYm94LXNpemluZzogYm9yZGVyLWJveDsNCn0NCg0KLyogUXVpdGEgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBlbCBjb21wb3J0YW1pZW50byAqLw0KLmNvbnRhaW5lcnsNCiAgLyogZGlzcGxheTogZmxleDsgKi8NCn0NCg0KLmNvbnRhaW5lciBkaXYgew0KICB3aWR0aDogMTAwcHg7IA0KICBoZWlnaHQ6IDEwMHB4Ow0KfQ0KDQouY29udGFpbmVyIGRpdjpudGgtY2hpbGQoMm4pew0KICBiYWNrZ3JvdW5kLWNvbG9yOiBhcXVhOw0KfQ0KDQouY29udGFpbmVyIGRpdjpudGgtY2hpbGQoMm4rMSl7DQogIGJhY2tncm91bmQtY29sb3I6IGJyb3duOw0KfQ0KDQoNCg0KDQoNCg0K%7C)

[A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

<br>

### What is Grid?
Grid involves arranging child elements along two axes, like a grid or table. The parent element or container must have the display property set to grid, and you must define the dimensions of the columns and rows. From there, you can organize the children as needed.

[Example of Grid](https://codi.link/PGRpdiBjbGFzcz0iY29udGFpbmVyIj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCjwvZGl2Pg0KDQoNCg0K%7CKiB7DQogIG1hcmdpbjogMDsNCiAgcGFkZGluZzogMDsNCiAgYm94LXNpemluZzogYm9yZGVyLWJveDsNCn0NCg0KLyogUXVpdGEgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBlbCBjb21wb3J0YW1pZW50byAqLw0KLmNvbnRhaW5lcnsNCi8qICAgDQogIGRpc3BsYXk6IGdyaWQ7DQogIGdyaWQtdGVtcGxhdGUtY29sdW1uczogMTAwcHggMTAwcHggMTAwcHg7DQogIGdyaWQtdGVtcGxhdGUtcm93czogMTAwcHggMTAwcHggMTAwcHg7IA0KICAqLw0KDQoNCn0NCg0KLmNvbnRhaW5lciBkaXYgew0KICB3aWR0aDogMTAwcHg7IA0KICBoZWlnaHQ6IDEwMHB4Ow0KfQ0KDQouY29udGFpbmVyIGRpdjpudGgtY2hpbGQoMm4pew0KICBiYWNrZ3JvdW5kLWNvbG9yOiBhcXVhOw0KfQ0KDQouY29udGFpbmVyIGRpdjpudGgtY2hpbGQoMm4rMSl7DQogIGJhY2tncm91bmQtY29sb3I6IGJyb3duOw0KfQ0KDQoNCg0KDQoNCg0K%7C)

[A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
[Flexbox VS Grid](https://platzi.com/blog/flexbox-vs-css-grid-cual-es-la-diferencia/)

<br>
<br>

## Box Model
The box model consists of four elements: margin, border, padding, and content.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/box-model.png?raw=true" width= "75%" alt="box model">
</p>

If you open your browser's developer tools and hover over an HTML element, you'll see a view similar to the previous image in the style section—this is the box model of the selected element.

<br>

### What Is the Content of an HTML Element?
The content of the element, as the name suggests, is everything inside it. This is defined by the **width** and **height** properties, representing the width and height, respectively. If you imagine a box, this value would represent everything you decide to put inside it.
```
div {
    width: 100px;
    height: 100px;
}
```
<br>

### What Are the Borders of an HTML Element?
The border is the outline or edge of an HTML element. If you imagine a box, this would be the box itself. To define a border, you need to use the following three properties:

  - **border-color**: Sets the border color.
  - **border-style**: Defines the style of the border. Options include: none, dotted, dashed, solid, double, groove.
  - **border-width**: Sets the border's thickness.

You can also set all three values in a single **border** property, where order does not matter.
```
div {
    border: [color] [style] [width];
}

div {
    border-color: red;
    border-style: solid;
    border-width: 1px;
}
```

[Example of Borders](https://codi.link/PGRpdiBjbGFzcz0ibm9uZSI+U2luIGJvcmRlPC9kaXY+DQo8ZGl2IGNsYXNzPSJkb3R0ZWQiPkNvbiBwdW50b3M8L2Rpdj4NCjxkaXYgY2xhc3M9ImRhc2hlZCI+Q29uIGd1aW9uZXM8L2Rpdj4NCjxkaXYgY2xhc3M9InNvbGlkIj5Db250aW51bzwvZGl2Pg0KPGRpdiBjbGFzcz0iZG91YmxlIj5kb2JsZSBjb250aW51bzwvZGl2Pg0KPGRpdiBjbGFzcz0iZ3Jvb3ZlIj5Db24gcmVjdWFkcm88L2Rpdj4NCg0KDQo=%7CZGl2ew0KICB3aWR0aDogMTIwcHg7DQogIGhlaWdodDogMTIwcHg7DQp9DQoNCi5ub25lew0KICAvKiBWYWxvciBwb3IgZGVmZWN0byBkZSBkaXYgKi8NCiAgYm9yZGVyOiAzcHggYmxhY2sgbm9uZTsNCn0NCg0KLmRvdHRlZHsNCiAgYm9yZGVyOiAzcHggYmxhY2sgZG90dGVkOw0KfQ0KDQouZGFzaGVkew0KICBib3JkZXI6IDNweCBibGFjayBkYXNoZWQ7DQp9DQoNCi5zb2xpZHsNCiAgYm9yZGVyOiAzcHggYmxhY2sgc29saWQ7DQp9DQoNCi5kb3VibGV7DQogIGJvcmRlcjogM3B4IGJsYWNrIGRvdWJsZTsNCn0NCg0KLmdyb292ZXsNCiAgYm9yZGVyOiA1cHggZ3JlZW55ZWxsb3cgZ3Jvb3ZlOw0KfQ0KDQoNCg0KLyogSWdub3JhIGVzdG9zIGVzdGlsb3MsIHBvciBhaG9yYSAqLw0KKiB7DQogIGZvbnQtc2l6ZTogMS4xcmVtOw0KICBtYXJnaW46IDA7DQp9DQoNCmJvZHl7DQogIGRpc3BsYXk6IGZsZXg7DQogIGZsZXgtd3JhcDogd3JhcDsNCiAgZ2FwOiAxLjVyZW07DQogIG1hcmdpbjogMjBweDsNCiAgZm9udC13ZWlnaHQ6IDgwMDsNCn0NCg0KDQoNCg==%7C)

You can also set individual border values for each position:
```
div {
  border-top: 5px solid blue;
  border-bottom: 5px solid red;
  border-left: 5px solid black;
  border-right: 5px solid yellow;
}
```
<br>

### What Is the Internal Spacing of an HTML Element or Padding?
Padding is the space between the border and the content of an HTML element. If you imagine a box, this would be the space between the box and what you want to put inside it.
```
div {
    padding: 100px;
}
```

[Example of Padding](https://codi.link/PGRpdj5Mb3JlbSBpcHN1bSBkb2xvciBzaXQgYW1ldCBjb25zZWN0ZXR1ciBhZGlwaXNpY2luZyBlbGl0aTwvZGl2Pg0KDQoNCg==%7CLyogUXVpdGEgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBlbCBjb21wb3J0YW1pZW50byAqLw0KZGl2ew0KICB3aWR0aDogMTIwcHg7DQogIGhlaWdodDogMTIwcHg7DQogIGJhY2tncm91bmQtY29sb3I6IGdyZWVueWVsbG93Ow0KICBib3JkZXI6IHNvbGlkIDFweCBibGFjazsNCiAgLyogcGFkZGluZzogMzBweDsgKi8NCn0NCg0KDQoNCi8qIElnbm9yYSBlc3RvcyBlc3RpbG9zLCBwb3IgYWhvcmEgKi8NCiogew0KICBmb250LXNpemU6IDEuMXJlbTsNCiAgbWFyZ2luOiAwLjVyZW07DQp9DQo=%7C)

You can set padding for each position in a single line in the following ways:

  - **padding: [top] [right] [bottom] [left]**, following a clockwise direction.
  - **padding: [top] [right and left] [bottom]**, following the primary axis.
  - **padding: [top and bottom] [right and left]**, following the element's axes.

You can also set individual values for each position:
```
div {
    padding-top: 10px;
    padding-bottom: 15px;
    padding-left: 20px;
    padding-right: 10px;
}
```

<br>

### What Is the External Spacing of an HTML Element or Margin?
**Margin** is the space between the border and another HTML element. If you imagine a box, it’s the space between your box and another box.
```
div {
    margin: 10px;
}
```

[Example of Margin](https://codi.link/PGRpdiBjbGFzcyA9ICJtYXJnaW4iPkxvcmVtIGlwc3VtIGRvbG9yIHNpdCBhbWV0IGNvbnNlY3RldHVyIGFkaXBpc2ljaW5nIGVsaXRpPC9kaXY+DQo8ZGl2PlNveSBvdHJvIGVsZW1lbnRvPC9kaXY+DQoNCg0K%7CLyogUXVpdGEgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBlbCBjb21wb3J0YW1pZW50byAqLw0KZGl2ew0KICB3aWR0aDogMTIwcHg7DQogIGhlaWdodDogMTIwcHg7DQogIGJhY2tncm91bmQtY29sb3I6IGdyZWVueWVsbG93Ow0KICBib3JkZXI6IHNvbGlkIDFweCBibGFjazsNCn0NCg0KLm1hcmdpbiB7DQogIC8qIG1hcmdpbjogMjBweDsgKi8NCn0NCg0KDQoNCi8qIElnbm9yYSBlc3RvcyBlc3RpbG9zLCBwb3IgYWhvcmEgKi8NCiogew0KICBmb250LXNpemU6IDEuMXJlbTsNCiAgbWFyZ2luOiAwOw0KfQ0KDQpib2R5ew0KICBkaXNwbGF5OiBmbGV4Ow0KICBtYXJnaW46IDIwcHg7DQogIGZvbnQtd2VpZ2h0OiA4MDA7DQp9DQoNCg0KDQoNCg==%7C)

You can set margin for each position in a single line in the following ways:

  - **margin: [top] [right] [bottom] [left]**, following a clockwise direction.
  - **margin: [top and bottom] [right and left]**, following the primary axis.
  - **margin: [top and bottom] [right and left]**, following the element's axes.

You can also set individual values for each position:
```
div {
    margin-top: 10px;
    margin-bottom: 15px;
    margin-left: 20px;
    margin-right: 10px;
}
```
<br>

### What Are Default Values?
By default, the browser sets initial values for some CSS properties, like **margin** and **padding**. A good practice is to use the universal selector to reset these values to zero to avoid unexpected errors.
```
* {
    margin: 0;
    padding: 0;
}
```
<br>

### What Is the Total Size of an Element?
The total size of an element is determined by the sum of the values for border, padding, and width or height, depending on the axis. Margin is not included in this calculation.

For example, we define the following styles:
```
div {
  width: 150px;
  height: 150px;
  padding: 20px;
  border: 10px solid gray;
  margin: 30px;
}
```
[Example of Total Measurements](https://codi.link/PGRpdj5Mb3JlbSBpcHN1bSBkb2xvciBzaXQgYW1ldCBjb25zZWN0ZXR1ciBhZGlwaXNpY2luZyBlbGl0aTwvZGl2Pg0KDQoNCg==%7CKiB7DQogIG1hcmdpbjogMDsNCiAgcGFkZGluZzogMDsNCn0NCg0KZGl2ew0KICBiYWNrZ3JvdW5kLWNvbG9yOiBncmVlbnllbGxvdzsNCiAgd2lkdGg6IDE1MHB4Ow0KICBoZWlnaHQ6IDE1MHB4Ow0KICBwYWRkaW5nOiAyMHB4Ow0KICBib3JkZXI6IDEwcHggc29saWQgZ3JheTsNCiAgbWFyZ2luOiAzMHB4Ow0KfQ0KDQoNCg0KDQoNCg0KDQoNCg==%7C)

The total size of the element will be ``210px`` on both axes, where the sum was: ``150`` (height/width) + ``20 x 2`` (padding on both sides) + ``10 x 2`` (border on both sides). If you inspect this element in the developer tools, it will show its size as ``210x210``.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/measurement-example.png?raw=true" width= "75%" alt="Measurement example">
</p>

Even if the elements' dimensions are known this way, you won't always have complete control. So, to set the total size of the element using width and height, not just the content, you can add the box-sizing property.

<br>

## ``Box-Sizing`` Property
The ``box-sizing`` property sets how width and height are calculated—whether they include borders and padding. A best practice is to set this in the universal selector, so all elements follow this approach.
```
* {
  box-sizing: border-box;
}
```

With the ``border-box`` value, the total size of the element will be equal to the specified **width** and **height**, causing the content measurements to adjust according to the borders and padding.

For example, with the styles defined earlier, let's set this new property.

[Example of Box-sizing](https://codi.link/PGRpdj5Mb3JlbSBpcHN1bSBkb2xvciBzaXQgYW1ldCBjb25zZWN0ZXR1ciBhZGlwaXNpY2luZyBlbGl0aTwvZGl2Pg0KDQoNCg==%7CLyogUXVpdGEgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBsbyBxdWUgb2N1cnJlICovDQoqIHsNCiAgbWFyZ2luOiAwOw0KICBwYWRkaW5nOiAwOw0KICAvKiBib3gtc2l6aW5nOiBib3JkZXItYm94OyAqLw0KfQ0KDQpkaXZ7DQogIGJhY2tncm91bmQtY29sb3I6IGdyZWVueWVsbG93Ow0KICB3aWR0aDogMTUwcHg7DQogIGhlaWdodDogMTUwcHg7DQogIHBhZGRpbmc6IDIwcHg7DQogIGJvcmRlcjogMTBweCBzb2xpZCBncmF5Ow0KICBtYXJnaW46IDMwcHg7DQp9DQoNCg0KDQoNCg0K%7C)

The total size of the element will be ``150px`` on both axes, where the content is calculated to ensure the total is what’s specified in **width** and **height**. If you inspect this element in the developer tools, it will show its total size as 150x150 and the content as ``90x90``.


In conclusion, set the total size of the element with width and height, along with box-sizing: border-box, so that the content adjusts to the container's needs.

<br>

### What Is the Problem with Border Size?
To recap, the total size of an element is the sum of three things: the border, the padding, and the content.

Sometimes, you might want to add a border when hovering over an element. This can cause the element to require more space, which can create layout issues if other elements are within the same container.

Look at the following example, and try hovering over an element. What happens?

[Example of Border Problem](https://codi.link/PGRpdj5Mb3JlbSBpcHN1bSBkb2xvciBzaXQgYW1ldCBjb25zZWN0ZXR1ciBhZGlwaXNpY2luZyBlbGl0aTwvZGl2Pg0KPGRpdj5Mb3JlbSBpcHN1bSBkb2xvciBzaXQgYW1ldCBjb25zZWN0ZXR1ciBhZGlwaXNpY2luZyBlbGl0aTwvZGl2Pg0KDQoNCg==%7CLyogUXVpdGEgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBsbyBxdWUgb2N1cnJlICovDQoqIHsNCiAgbWFyZ2luOiAwOw0KICBwYWRkaW5nOiAwOw0KfQ0KDQpkaXZ7DQogIGRpc3BsYXk6IGlubGluZS1ibG9jazsNCiAgYmFja2dyb3VuZC1jb2xvcjogZ3JlZW55ZWxsb3c7DQogIHdpZHRoOiAxNTBweDsNCiAgaGVpZ2h0OiAxNTBweDsNCiAgcGFkZGluZzogMjBweDsNCiAgbWFyZ2luOiAzMHB4Ow0KfQ0KDQpkaXY6aG92ZXJ7DQogIGJvcmRlcjogMTBweCBzb2xpZCBncmF5Ow0KICBjdXJzb3I6IHBvaW50ZXI7DQp9DQoNCg0KDQoNCg0K%7C)

You saw this behavior; you must be careful with what you add because it can cause issues.

The solution is to set a ``transparent`` border of the same size as the existing border. This will keep the element at its total size, with only the color changing.

[Solution to the Problem](https://codi.link/PGRpdj5Mb3JlbSBpcHN1bSBkb2xvciBzaXQgYW1ldCBjb25zZWN0ZXR1ciBhZGlwaXNpY2luZyBlbGl0aTwvZGl2Pg0KPGRpdj5Mb3JlbSBpcHN1bSBkb2xvciBzaXQgYW1ldCBjb25zZWN0ZXR1ciBhZGlwaXNpY2luZyBlbGl0aTwvZGl2Pg0KDQoNCg==%7CLyogUXVpdGEgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBsbyBxdWUgb2N1cnJlICovDQoqIHsNCiAgbWFyZ2luOiAwOw0KICBwYWRkaW5nOiAwOw0KfQ0KDQpkaXZ7DQogIGRpc3BsYXk6IGlubGluZS1ibG9jazsNCiAgYmFja2dyb3VuZC1jb2xvcjogZ3JlZW55ZWxsb3c7DQogIHdpZHRoOiAxNTBweDsNCiAgaGVpZ2h0OiAxNTBweDsNCiAgcGFkZGluZzogMjBweDsNCiAgbWFyZ2luOiAzMHB4Ow0KICAvKiBib3JkZXI6IDEwcHggc29saWQgdHJhbnNwYXJlbnQ7ICovDQp9DQoNCmRpdjpob3ZlcnsNCiAgYm9yZGVyOiAxMHB4IHNvbGlkIGdyYXk7DQogIGN1cnNvcjogcG9pbnRlcjsNCn0NCg0KDQoNCg0KDQo=%7C)

Avoid adding a different size than the original one.

[The Rules of Margin Collapse](https://www.joshwcomeau.com/css/rules-of-margin-collapse/)

[Flexbox - Web Dev Topics](https://learntheweb.courses/topics/flexbox/)

<br>
<br>

## Image Collapse

<br>
<br>

## CSS Positioning

<br>
<br>

## Z-index and the Stacking Context

<br>
<br>

## Most used CSS Properties and Values

<br>
<br>
<br>

# RESPONSIVE DESIGN

## Measurement units

<br>
<br>

## Responsive design

<br>
<br>
<br>

# CSS ARCHITECTURE

## What are the CSS architectures? What are they used for?

## OOCSS, BEM, SMACCSS, ITCSS and Atomic Design

<br>
<br>
<br>

# NEXT STEPS

## CSS for interviews and labor market

<br>
<br>
<br>