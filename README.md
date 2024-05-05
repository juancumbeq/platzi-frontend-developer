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

<br>
<br>

## Cascading and specificity in CSS

<br>
<br>

## Most used display types: block, inline and inline-block

<br>
<br>

## Most used display types: flexbox and CSS grid

<br>
<br>

## Box model

<br>
<br>

## Image collapse

<br>
<br>

## CSS positioning

<br>
<br>

## Z-index and the stacking context

<br>
<br>

## Most used CSS properties and values

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