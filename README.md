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
  - [INTRODUCCTION TO FRONTEND DEVELOPMENT](#introduction-to-frontend-development)
    - [What are HTML and CSS? What are they used for?](#what-is-html-and-css-what-are-they-used-for)
      - [What is HTML?](#what-is-html)
      - [What is CSS?](#what-is-css)
    - [Render Engines: From Files to Pixels](#render-engines-from-files-to-pixels)
      - [Which is the browser engine?](#which-is-the-browser-engine)
      - [Rendering Process](#rendering-process)

  - [HTML LAYOUT](#html-layout)
    - [HTML Document Anatomy and its Elemtns](#html-document-anatomy-and-its-elements)
      - [What are HTML Elements](#what-are-html-elements)
      - [What are HTMl Attributes](#what-are-the-html-attributes)
      - [What are Empty Elements](#what-are-empty-elements)
      - [What are Element Nesting](#what-are-element-nesting)
      - [Basic Stucture of an HTML Document](#basic-structure-of-an-html-document)
      - [HTML Comments](#html-comments)
    - [What is Semantic HTML](#what-is-semantic-html)
      - [The Problem with the div Tag](#the-problem-with-the-div-tag)
      - [Which Tags are Semantic](#which-tags-are-semantic)
      - [Advantages of Using Semantic HTML](#advantages-of-using-semantic-html)
    -[Most used HTML Tags](#most-used-html-tags)

  - [CSS LAYOUT](#css-layout)
    - [Anatomy of a CSS Declaration: Selectors, Properties and Values](#anatomy-of-a-css-declaration-selectors-properties-and-values)
      - [What is a CSS Declaration](#what-is-a-css-declaration)
      - [What are CSS Comments](#what-are-css-comments)
      - [Basic CSS Properties](#basic-css-properties)
      - [Basic Units of Measurement](#basic-units-of-measurement)
    - [Selectors Types: Basics and Combiners](#selectors-types-basics-and-combiners)
      - [Types of Basic Selectors](#types-of-basic-selectors)
      - [What Are Combinator Selectors?](#what-are-combinator-selectors)
      - [Types of Combinator Selectors](#types-of-combinator-selectors)
    - [Selectors Types: Pseudoclasses and Pseudoelements](#selectors-types-pseudoclasses-and-pseudoelements)
      - [What Are Pseudo-classes?](#what-are-pseudo-classes)
      - [Syntax](#syntax)
      - [Some Pseudo-classes](#some-pseudo-classes)
      - [What Are Pseudo-elements?](#what-are-pseudo-elements)
      - [Syntax](#syntax-1)
      - [Some Pseudo-elements](#some-pseudo-elements)
    - [Cascading and Specificity in CSS](#cascading-and-specificity-in-css)
      - [What is CSS Cascade?](#what-is-css-cascade)
      - [What is CSS Specificity?](#what-is-css-specificity)
      - [Types of Specificity in CSS](#types-of-specificity-in-css)
      - [Values with Higher Specificity](#values-with-higher-specificity)
      - [Inline Styles](#inline-styles)
      - [Specificity in Selectors](#specificity-in-selectors)
    - [Most used Display Types: Block, Inline and Inline-block](#most-used-display-types-block-inline-and-inline-block)
      - [Block Display](#block-display)
      - [Inline Display](#inline-display)
      - [Inline-Block Display](#inline-block-display)
      - [No Display (None)](#no-display-none)
    - [Most used Display Types: Flexbox and CSS grid](#most-used-display-types-flexbox-and-css-grid)
      - [What is Flexbox?](#what-is-flexbox)
      - [What is Grid?](#what-is-grid)
    - [Box Model](#box-model)
      - [What Is the Content of an HTML Element?](#what-is-the-content-of-an-html-element)
      - [What Are the Borders of an HTML Element?](#what-are-the-borders-of-an-html-element)
      - [What Is the Internal Spacing of an HTML Element or Padding?](#what-is-the-internal-spacing-of-an-html-element-or-padding)
      - [What Is the External Spacing of an HTML Element or Margin?](#what-is-the-external-spacing-of-an-html-element-or-margin)
      - [What Are Default Values?](#what-are-default-values)
      - [What Is the Total Size of an Element?](#what-is-the-total-size-of-an-element)
    - [``Box-Sizing`` Property](#box-sizing-property)
      - [What Is the Problem with Border Size?](#what-is-the-problem-with-border-size)
    - [Image Collapse](#image-collapse)
    - [CSS Positioning](#css-positioning)
      - [Position Properties](#position-properties)
      - [Static Position](#static-position)
      - [Relative Position](#relative-position)
      - [Absolute Position](#absolute-position)
      - [Nearest Parent Element with Relative Positioning](#nearest-parent-element-with-relative-positioning)
      - [Difference between Relative and Absolute Positioning](#difference-between-relative-and-absolute-positioning)
      - [Fixed Position](#fixed-position)
      - [Sticky Position](#sticky-position)
    - [Z-index and the Stacking Context](#z-index-and-the-stacking-context)
      - [What are Planes and Axes?](#what-are-planes-and-axes)
      - [What is the z-index Property?](#what-is-the-z-index-property)
    - [Most used CSS Properties and Values](#most-used-css-properties-and-values)
      - [Text Properties](#text-properties)
      - [Rounded Borders](#rounded-borders)
      - [Challenge](#challenge)

  - [RESPONSIVE DESIGN](#responsive-design)
    - [Measurement Units](#measurement-units)
      - [What are Absolute Measurements?](#what-are-absolute-measurements)
      - [What are Relative Measurements?](#what-are-relative-measurements)
      - [Difference Between ``rem`` and`` em``](#difference-between-rem-and-em)
      - [Difference Between Percentages and Screen Width/Height](#difference-between-percentages-and-screen-widthheight)
      - [Problem with Text Measurements](#problem-with-text-measurements)
    - [Responsive Design](#responsive-design)
      -[Developer Tools for Media Queries](#developer-tools-for-media-queries)

  - [CSS ARCHITECTURE](#css-architecture)
    - [What are the CSS architectures? What are they used for?](#what-are-the-css-architectures-what-are-they-used-for)
      - [Goals of CSS Architectures](#goals-of-css-architectures)
      - [Best Practices for CSS Architectures](#best-practices-for-css-architectures)
    - [OOCSS, BEM, SMACCSS, ITCSS and Atomic Design](#oocss-bem-smaccss-itcss-and-atomic-design)
      - [What is Object-Oriented CSS?](#what-is-object-oriented-css)
      - [What is BEM: Block, Element, and Modifier?](#what-is-bem-block-element-and-modifier)
      - [What is the Scalable and Modular Architecture for CSS?](#what-is-the-scalable-and-modular-architecture-for-css)
      - [What is the Inverted Triangle CSS Architecture?](#what-is-the-inverted-triangle-css-architecture)
      - [What is Atomic Design?](#what-is-atomic-design)

  - [NEXT STEPS](#next-steps)


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

### Which is the Browser Engine?

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


### What are HTML Elements?

Elements are the individual parts that make up an HTML file. Their structure contains:
  - Tags: There are an HTML element. Tags are divided into opening tags, represented by ```<tag>```, and closing tags, represented by ```</tag>```
  - Content: This is the text or other elements enclosed by the tag. This value is optional in some cases.

<br>

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/cheasheet-tags.png?raw=true" width= "99%" alt="Cheatsheet tags">
</p>

<br>

### What are the HTML Attributes?

HTML attributes are propeties within the opening tags that control the behavior of the element. Their value is enclosed in quotation marks.

<br>

### What are Empty Elements?

Empty elements are those that are represented only by an opnening tag. For example, the image tag: ```<img ...>```.

<br>

### What are Element Nesting?

HTML element nesting involves wrapping several tags within other tags.

Think of each HTML element as a box where you can place other elements or additional boxes. These boxes will vary in size and can be positioned next to one another.

Tags that wrap other tags are called "parent" elements. For example, ```<section>``` is the parent of ```<h1>```, ```<p>```, and ```<ul>```, while ```<ul>``` is the parent of three ``<li>`` tags.

Tags that are contained within other tags are called "child" elements. For example, ``<h1>``, ``<p>``, and ``<ul>`` are children of ``<section>``, while ``<li>`` tags are children of ``<ul>``.

<br>

### Basic Structure of an HTML Document

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

### HTML Comments

HTML comments are used to annotate something that will be ignored during rendering. To add an HTML comment, it is wrapped between ```<!-- and -->```, regardless of the number of lines.

<br>
<br>

## What is Semantic HTML?

Semantic HTML means that each element has its own tag that accurately defines its purpose, avoiding the use of overly general tags like ```<div>``` or ```<span>```.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/semantic-schema.png?raw=true" width= "75%" alt="Semantic Schema">
</p>

<br>

### The Problem with the ```div``` Tag
The *div* tag defines a generic block of content that lacks semantic value. It's used for design elements like containers.

<br>

### Which Tags are Semantic?
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

## Most used HTML Tags

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
## Anatomy of a CSS Declaration: Selectors, Properties and Values

Before we start writing CSS code, we need to understand the anatomy of a style declaration.

<br>

### What is a CSS Declaration?
A CSS declaration is a block that specifies the set of styles to be added to an HTML element. Its structure includes the following:

  - **Selector**: Defines the element or set of elements to which styles will be applied.
  - **Property**: The name of the CSS style.
  - **Value**: The value that the property will take on.

Example:
<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/css-declaration.png?raw=true" width= "75%" alt="CSS declaration">
</p>

<br>

### What are CSS Comments?
CSS comments are used to indicate something that should be ignored. To create a CSS comment, wrap it between ```/*``` and ```*/```, regardless of the number of lines.

<br>

### Basic CSS Properties
Before starting with CSS, let's use some initial CSS properties:

  - **color**: Sets the text color of an element.
  - **background-color**: Sets the background color for an element.
  - **font-size**: Sets the font size.
  - **width**: Sets the width of an element.
  - **height**: Sets the height of an element.

<br>

### Basic Units of Measurement
These are the initial units of measurement you should know to set the sizes of elements or typography:

  - **px**: Represents a length in pixels.
  - **%**: Represents a percentage relative to a base measurement.

<br>
<br>

## Selectors Types: Basics and Combiners

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

## Selectors Types: Pseudoclasses and Pseudoelements
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

### Some Pseudo-classes
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

### Some Pseudo-elements

  - **::before**: Adds content before the element. The content is added using the CSS content property.
    - [Example](https://codi.link/PGgxPlTDrXR1bG88L2gxPg0KPGgyPlN1YnTDrXR1bG9zPC9oMj4NCjxoMj5TdWJ0w610dWxvczwvaDI+DQo8aDI+U3VidMOtdHVsb3M8L2gyPg0KPGgyPlN1YnTDrXR1bG9zPC9oMj4NCjxoMj5TdWJ0w610dWxvczwvaDI+DQo=%7CaDI6YmVmb3JlIHsNCiAgY29udGVudDogIiAqICI7DQogIGNvbG9yOiByZWQ7DQp9%7C)

  - **::after**: Adds content after the element. The content is added using the CSS content property.
    - [Example](https://codi.link/PCEtLSBOYXZiYXIgaW1wcm92aXNhZGEgLS0+DQo8bmF2Pg0KICA8dWw+DQogICAgPGxpPkhvbWU8L2xpPg0KICAgIDxsaT5EZXN0YWNhZG9zPC9saT4NCiAgICA8bGk+RWxlbWVudG9zPC9saT4NCiAgICA8bGk+Q2xhc2VzPC9saT4NCiAgICA8bGk+TcOhcy4uLjwvbGk+DQogIDwvdWw+DQo8L25hdj4NCg==%7CbmF2IHVsIHsNCiAgbGlzdC1zdHlsZTogbm9uZTsNCiAgZGlzcGxheTogZmxleDsNCiAganVzdGlmeS1jb250ZW50OiBzcGFjZS1hcm91bmQ7DQogIGN1cnNvcjogcG9pbnRlcjsNCn0NCg0KbmF2IHVsIGxpOjphZnRlciB7DQogIGNvbnRlbnQ6ICJ8IjsNCiAgbWFyZ2luOiAxcmVtOw0KICBjb2xvcjogcmVkOw0KfQ==%7C)

  - **::first-letter**: Adds styles to the first letter of the text in any element.
    - [Example](https://codi.link/PHA+U295IG90cm8gcMOhcnJhZm88L3A+DQo8cD5Tb3kgb3RybyBww6FycmFmbzwvcD4NCjxwPlNveSBvdHJvIHDDoXJyYWZvPC9wPg0KPHA+U295IG90cm8gcMOhcnJhZm88L3A+DQo8cD5Tb3kgb3RybyBww6FycmFmbzwvcD4NCjxwPlNveSBvdHJvIHDDoXJyYWZvPC9wPg0KPHA+U295IG90cm8gcMOhcnJhZm88L3A+DQo8cD5Tb3kgb3RybyBww6FycmFmbzwvcD4NCjxwPlNveSBvdHJvIHDDoXJyYWZvPC9wPg0K%7COjpmaXJzdC1sZXR0ZXJ7DQogIGNvbG9yOiByZWQ7DQp9DQo=%7C)

<br>
<br>

## Cascading and Specificity in CSS
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
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/box-model.png?raw=true" width= "50%" alt="box model">
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

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/measurement-example-2.png?raw=true" width= "75%" alt="Measurement example 2">
</p>

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
Margin collapse occurs when two adjacent block elements have a certain margin value, causing those margins to overlap into a single value, which is the larger of the two.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/image-collapse.png?raw=true" width= "75%" alt="Image collapse">
</p>

Look at the following code, change the display value to inline-block, and observe the result.

[Example of Margin Collapse](https://codi.link/PGRpdj5Mb3JlbSBpcHN1bSBkb2xvciBzaXQgYW1ldCBjb25zZWN0ZXR1ciBhZGlwaXNpY2luZyBlbGl0aTwvZGl2Pg0KPGRpdj5Mb3JlbSBpcHN1bSBkb2xvciBzaXQgYW1ldCBjb25zZWN0ZXR1ciBhZGlwaXNpY2luZyBlbGl0aTwvZGl2Pg0KPGRpdj5Mb3JlbSBpcHN1bSBkb2xvciBzaXQgYW1ldCBjb25zZWN0ZXR1ciBhZGlwaXNpY2luZyBlbGl0aTwvZGl2Pg0KPGRpdj5Mb3JlbSBpcHN1bSBkb2xvciBzaXQgYW1ldCBjb25zZWN0ZXR1ciBhZGlwaXNpY2luZyBlbGl0aTwvZGl2Pg0KDQoNCg0K%7CKiB7DQogIG1hcmdpbjogMDsNCiAgcGFkZGluZzogMDsNCiAgYm94LXNpemluZzogYm9yZGVyLWJveDsNCn0NCg0KLyogUXVpdGEgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBsbyBxdWUgb2N1cnJlICovDQpkaXZ7DQogIC8qIGRpc3BsYXk6IGlubGluZS1ibG9jazsgKi8NCiAgbWFyZ2luOiA0MHB4Ow0KICBiYWNrZ3JvdW5kLWNvbG9yOiBncmVlbnllbGxvdzsNCiAgd2lkdGg6IDgwJTsNCiAgaGVpZ2h0OiA1MHB4Ow0KICBwYWRkaW5nOiAxMHB4Ow0KfQ0KDQoNCg0KDQoNCg0K%7C)

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/image-collapse-2.png?raw=true" width= "75%" alt="Image collapse 2">
</p>

As you can see, when you change the display, this behavior disappears. Additionally, in Flexbox and Grid, margin collapse does not occur. Be mindful of the margins you set on block-type elements.


<br>
<br>

## [CSS Positioning](https://github.com/juancumbeq/platzi-frontend-developer/blob/main/resources/repo/curso-1/posicionamiento.html)
CSS positioning refers to how an element is placed relative to its parent element and the normal flow of the document. The normal flow of the document is the order of elements established in the HTML.

An element's position is defined using the ``position`` property with the following possible values:

  - static
  - relative
  - absolute
  - sticky

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/CSS-positioning.png?raw=true" width= "75%" alt="CSS positioning">
</p>

<br>

### Position Properties
In addition to the ``position`` property, there are four properties that determine an element's position relative to its parent: top, bottom, left, and right.
```
div {
    top: 10px;
    bottom: 15px;
    left: 20px;
    right: 10px;
}
```
These values are relative to the nearest parent with ``position: relative``.

If both top and bottom are defined, top takes precedence. If both left and right are defined, left takes precedence (depending on the configured language).

<br>

### Static Position
``position: static`` is the default value for all HTML elements. It respects the normal flow of the document, and positioning properties cannot be set.

[Example of Static Position](https://codi.link/PGRpdiBjbGFzcz0iY29udGFpbmVyIj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCjwvZGl2Pg0KDQoNCg0K%7CKiB7DQogIG1hcmdpbjogMDsNCiAgcGFkZGluZzogMDsNCiAgYm94LXNpemluZzogYm9yZGVyLWJveDsNCn0NCg0KLmNvbnRhaW5lcnsNCiAgd2lkdGg6IDEwMCU7DQoNCn0NCg0KLyogUXVpdGEgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBlbCBjb21wb3J0YW1pZW50byAqLw0KLmNvbnRhaW5lciBkaXYgew0KICB3aWR0aDogMTAwcHg7IA0KICBoZWlnaHQ6IDEwMHB4Ow0KLyogDQogIHRvcDogMTBweDsNCiAgYm90dG9tOiAxNXB4Ow0KICBsZWZ0OiAyMHB4Ow0KICByaWdodDogMTBweDsgDQogICovDQp9DQoNCi5jb250YWluZXIgZGl2Om50aC1jaGlsZCgybil7DQogIGJhY2tncm91bmQtY29sb3I6IGFxdWE7DQp9DQoNCi5jb250YWluZXIgZGl2Om50aC1jaGlsZCgybisxKXsNCiAgYmFja2dyb3VuZC1jb2xvcjogYnJvd247DQp9DQoNCg0KDQoNCg0KDQo=%7C)

<br>

###  Relative Position
``position: relative`` respects the normal flow of the document but allows positioning properties to be set.

[Example of Relative Position](https://codi.link/PGRpdiBjbGFzcz0iY29udGFpbmVyIj4NCiAgPGRpdiBjbGFzcz0icmVsYXRpdmUiPjwvZGl2Pg0KICA8ZGl2PjwvZGl2Pg0KICA8ZGl2PjwvZGl2Pg0KICA8ZGl2PjwvZGl2Pg0KICA8ZGl2PjwvZGl2Pg0KICA8ZGl2PjwvZGl2Pg0KICA8ZGl2PjwvZGl2Pg0KICA8ZGl2PjwvZGl2Pg0KICA8ZGl2PjwvZGl2Pg0KPC9kaXY+DQoNCg0KDQo=%7CKiB7DQogIG1hcmdpbjogMDsNCiAgcGFkZGluZzogMDsNCiAgYm94LXNpemluZzogYm9yZGVyLWJveDsNCn0NCg0KLmNvbnRhaW5lcnsNCiAgd2lkdGg6IDEwMCU7DQp9DQoNCi5jb250YWluZXIgZGl2IHsNCiAgd2lkdGg6IDEwMHB4OyANCiAgaGVpZ2h0OiAxMDBweDsNCn0NCg0KLyogUXVpdGEgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBlbCBjb21wb3J0YW1pZW50byAqLw0KLmNvbnRhaW5lciAucmVsYXRpdmV7DQogIC8qIHBvc2l0aW9uOiByZWxhdGl2ZTsgKi8NCiAgLyogdG9wOiA1MHB4OyAqLw0KICAvKiBsZWZ0OiA1MHB4OyAqLw0KfQ0KDQouY29udGFpbmVyIGRpdjpudGgtY2hpbGQoMm4pew0KICBiYWNrZ3JvdW5kLWNvbG9yOiBhcXVhOw0KfQ0KDQouY29udGFpbmVyIGRpdjpudGgtY2hpbGQoMm4rMSl7DQogIGJhY2tncm91bmQtY29sb3I6IGJyb3duOw0KfQ0KDQoNCg0KDQoNCg0K%7C)

<br>

###  Absolute Position
``position: absolute`` removes the element from the normal flow of the document, allowing positioning properties to be set.

In the following example, notice what happens to the first element relative to the others.

[Example of Absolute Position](https://codi.link/PGRpdiBjbGFzcz0iY29udGFpbmVyIj4NCiAgPGRpdiBjbGFzcz0iYWJzb2x1dGUiPjE8L2Rpdj4NCiAgPGRpdj4yPC9kaXY+DQogIDxkaXY+MzwvZGl2Pg0KICA8ZGl2PjQ8L2Rpdj4NCiAgPGRpdj41PC9kaXY+DQo8L2Rpdj4NCg0KDQoNCg==%7CKiB7DQogIG1hcmdpbjogMDsNCiAgcGFkZGluZzogMDsNCiAgYm94LXNpemluZzogYm9yZGVyLWJveDsNCiAgZm9udC1zaXplOiAxLjVyZW07DQp9DQoNCi8qIEltcG9ydGFudGUgZWwgcG9zaXRpb24gKi8NCi5jb250YWluZXJ7DQogIHBvc2l0aW9uOiByZWxhdGl2ZTsNCiAgd2lkdGg6IDEwMCU7DQp9DQoNCi5jb250YWluZXIgZGl2IHsNCiAgd2lkdGg6IDEwMHB4OyANCiAgaGVpZ2h0OiAxMDBweDsNCn0NCg0KLyogUXVpdGEgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBlbCBjb21wb3J0YW1pZW50byAqLw0KLmNvbnRhaW5lciAuYWJzb2x1dGV7DQogIC8qIHBvc2l0aW9uOiBhYnNvbHV0ZTsgKi8NCiAgLyogbGVmdDogMTUwcHg7ICovDQogIC8qIHRvcDogNTBweDsgKi8NCn0NCg0KLmNvbnRhaW5lciBkaXY6bnRoLWNoaWxkKDJuKXsNCiAgYmFja2dyb3VuZC1jb2xvcjogYXF1YTsNCn0NCg0KLmNvbnRhaW5lciBkaXY6bnRoLWNoaWxkKDJuKzEpew0KICBiYWNrZ3JvdW5kLWNvbG9yOiBicm93bjsNCn0NCg0KDQoNCg0KDQoNCg0KDQo=%7C)

You may have noticed that the "2" element appears to vanish, but in reality, it's being positioned behind the element with absolute positioning, which is out of the normal document flow. This behavior is due to the Z-axis and the stacking context.

<br>

### Nearest Parent Element with Relative Positioning
An element with ``position: absolute`` will move up, down, left, or right in relation to the nearest parent element with ``position: relative``.

If there's no parent with ``position: relative``, the absolute positioned element will move relative to the root element of the document.

In the following example, you will see several parent containers, including ``<html>`` and ``<body>``. Follow the steps and observe the behavior. Ignore the initial styles; they're there to establish the exercise structure.

[Example of Positioning with Different Parent Containers](https://codi.link/PHA+Qm9keTwvcD4NCjxkaXYgY2xhc3M9ImFidWVsbyI+DQogIDxwPkFidWVsbzwvcD4NCiAgPGRpdiBjbGFzcz0icGFkcmUiPg0KICAgIDxwPlBhZHJlPC9wPg0KICAgIDxkaXYgY2xhc3M9Imhpam8iPg0KICAgICAgPHA+SGlqbzwvcD4NCiAgICA8L2Rpdj4NCiAgPC9kaXY+DQo8L2Rpdj4=%7CLyogRWwgZWplcmNpY2lvIGVzdMOhIGhhc3RhIGFiYWpvICovDQoNCiogew0KICBtYXJnaW46IDA7DQogIHBhZGRpbmc6IDA7DQogIGJveC1zaXppbmc6IGJvcmRlci1ib3g7DQogIHRleHQtYWxpZ246IGNlbnRlcjsNCn0NCg0KaHRtbHsNCiAgbWFyZ2luOiAyMHB4Ow0KICBib3JkZXI6IDFweCByZWQgc29saWQ7DQp9DQoNCmJvZHkgew0KICBtYXJnaW46IDIwcHg7DQogIGJhY2tncm91bmQtY29sb3I6IHdoZWF0Ow0KICBib3JkZXI6IDFweCBibGFjayBzb2xpZDsNCn0NCg0KcCB7DQogIGZvbnQtc2l6ZTogMS41cmVtOw0KICBmb250LXdlaWdodDogYm9sZDsNCiAgbWFyZ2luLWJvdHRvbTogNTBweDsNCg0KfQ0KDQouYWJ1ZWxvew0KICB3aWR0aDogMTAwJTsNCiAgaGVpZ2h0OiAxMDB2aDsNCiAgYmFja2dyb3VuZC1jb2xvcjogeWVsbG93Z3JlZW47DQp9DQoNCi5wYWRyZXsNCiAgd2lkdGg6IDc1JTsNCiAgaGVpZ2h0OiA3NSU7DQogIGJhY2tncm91bmQtY29sb3I6IGNhZGV0Ymx1ZTsNCn0NCg0KLmhpam97DQogIHdpZHRoOiAxNTBweDsNCiAgaGVpZ2h0OiAxNTBweDsNCiAgYmFja2dyb3VuZC1jb2xvcjogcm9zeWJyb3duOyANCn0NCg0KDQovKiBMbyDDum5pY28gcXVlIHF1aWVybyBxdWUgZW50aWVuZGFzIGVzIHF1ZSBoYXkgMyBjb250ZW5lZG9yZXMsIGxvcyBjdcOhbGVzIA0KLyogUXVpdGEgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBlbCBjb21wb3J0YW1pZW50byAqLw0KDQoNCi5oaWpvIHsNCiAgLyogcG9zaXRpb246IGFic29sdXRlOyAqLw0KICAvKiB0b3A6IDA7ICovDQp9DQoNCi8qIMK/IFBvciBxdcOpIHN1Y2VkacOzIGVzdG8gPyAqLw0KDQpodG1sIHsNCiAgLyogcG9zaXRpb246IHJlbGF0aXZlOyAqLw0KfQ0KDQpib2R5IHsNCiAgLyogcG9zaXRpb246IHJlbGF0aXZlOyAqLw0KfQ0KDQouYWJ1ZWxvew0KICAvKiBwb3NpdGlvbjogcmVsYXRpdmU7ICovDQp9DQoNCi5wYWRyZSB7DQogIC8qIHBvc2l0aW9uOiByZWxhdGl2ZTsgKi8NCn0NCg0KLyogwr8gQWhvcmEgZW50ZW5kaXN0ZSA/ICovDQoNCg0KDQoNCg0KDQoNCg0K%7C)

As you may have noticed, the movement of the element with position: absolute is based on the nearest parent element with ``position: relative``.

<br>

### Difference between Relative and Absolute Positioning
Relative and absolute positioning are two types of CSS positioning that determine how elements are placed within a webpage. Here's a breakdown of the key differences:

**Relative Positioning:**
  - **Definition**: With position: relative, an element is positioned relative to its normal position in the document's flow. The original space it occupies remains, even if it's moved.
  - **Movement**: You can use properties like top, right, bottom, and left to move the element from its normal position. However, this shift is relative to where the element would be in the natural document flow.
  - **Parent Context**: A relatively positioned element does not affect other elements' placement in the document flow. Other elements retain their usual positions, and the document flow remains largely unaltered.
  - **Use Case**: It's often used to adjust an element's position slightly while maintaining the overall layout structure. It's useful for creating subtle shifts without removing an element from the document's flow.

<br>

**Absolute Positioning:**
  - **Definition**: With position: absolute, an element is completely removed from the document's normal flow. It's positioned relative to the nearest ancestor with position: relative, or to the document's root if no relative ancestor is found.
  - **Movement**: The element can be positioned anywhere on the page using top, right, bottom, and left, without affecting the layout of surrounding elements. It can overlap or stack with other elements.
  - **Parent Context**: Absolute positioning relies on the context of a parent element with position: relative (or other non-static positioning). If there's no relative parent, it will position relative to the entire page (<html> or <body>).
  - **Use Case**: It's useful for creating layered effects, overlays, or when precise positioning is required. Because it doesn't reserve space in the normal flow, it can lead to overlapping content if not used carefully.

<br>

**Conclusion:**

Relative Positioning maintains the general structure and flow of the document, allowing for minor adjustments relative to where the element would normally be.
Absolute Positioning removes the element from the normal flow and can be used for more complex layouts or effects, but requires a parent with a defined position to avoid unexpected behavior. It can create issues with stacking and overlapping if not used with caution.

<br>

### Fixed Position
``position: fixed`` removes the element from the normal document flow and fixes it in place; positioning properties can be set.

In the following example, scroll through the document to observe the behavior before and after setting the fixed position.

[Example of Fixed Position](https://codi.link/PG5hdj5EZSBncmFuZGUgcXVpZXJvIHNlciB1bmEgYmFycmEgZGUgbmF2ZWdhY2nDs248L25hdj4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQoNCg0KDQo=%7CKiB7DQogIG1hcmdpbjogMDsNCiAgcGFkZGluZzogMDsNCiAgYm94LXNpemluZzogYm9yZGVyLWJveDsNCiAgZm9udC1zaXplOiAxLjFyZW07DQp9DQoNCi8qIERlc3Bsw6F6YXRlIHBvciBlbCBkb2N1bWVudG8geSBkZXNwdcOpcyBxdWl0YSBsb3MgY29tZW50YXJpb3MgeSBvYnNlcnZhIGVsIGNvbXBvcnRhbWllbnRvICovDQoNCm5hdiB7DQogIC8qIHBvc2l0aW9uOiBmaXhlZDsgKi8NCiAgLyogdG9wOiAwOyAqLw0KICBiYWNrZ3JvdW5kLWNvbG9yOiBjb3JuZmxvd2VyYmx1ZTsNCiAgd2lkdGg6IDEwMCU7DQogIGhlaWdodDogYXV0bzsNCiAgcGFkZGluZzogMjBweDsNCn0NCg0KcCB7DQogIHBhZGRpbmc6IDEwcHg7DQp9DQoNCg0KDQoNCg0KDQoNCg0K%7C)

<br>

### Sticky Position
``position: sticky`` removes the element from the normal document flow and fixes it in place while its parent container is visible; positioning properties can be set.

In the following example, scroll through the document and notice the behavior before and after applying the sticky position.

[Example of Sticky Position](https://codi.link/PGRpdj4NCiAgPHA+U295IHVuIHDDoXJyYWZvIDE8L3A+DQogIDx1bD4NCiAgICA8bGk+RWxlbWVudG8gMTwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDI8L2xpPg0KICAgIDxsaT5FbGVtZW50byAzPC9saT4NCiAgICA8bGk+RWxlbWVudG8gNDwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDU8L2xpPg0KICAgIDxsaT5FbGVtZW50byA2PC9saT4NCiAgICA8bGk+RWxlbWVudG8gNzwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDg8L2xpPg0KICAgIDxsaT5FbGVtZW50byA5PC9saT4NCiAgICA8bGk+RWxlbWVudG8gMTA8L2xpPg0KICA8L3VsPg0KICA8cD5Tb3kgdW4gcMOhcnJhZm8gMjwvcD4NCiAgPHVsPg0KICAgIDxsaT5FbGVtZW50byAxPC9saT4NCiAgICA8bGk+RWxlbWVudG8gMjwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDM8L2xpPg0KICAgIDxsaT5FbGVtZW50byA0PC9saT4NCiAgICA8bGk+RWxlbWVudG8gNTwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDY8L2xpPg0KICAgIDxsaT5FbGVtZW50byA3PC9saT4NCiAgICA8bGk+RWxlbWVudG8gODwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDk8L2xpPg0KICAgIDxsaT5FbGVtZW50byAxMDwvbGk+DQogIDwvdWw+DQogIDxwPlNveSB1biBww6FycmFmbyAzPC9wPg0KICA8dWw+DQogICAgPGxpPkVsZW1lbnRvIDE8L2xpPg0KICAgIDxsaT5FbGVtZW50byAyPC9saT4NCiAgICA8bGk+RWxlbWVudG8gMzwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDQ8L2xpPg0KICAgIDxsaT5FbGVtZW50byA1PC9saT4NCiAgICA8bGk+RWxlbWVudG8gNjwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDc8L2xpPg0KICAgIDxsaT5FbGVtZW50byA4PC9saT4NCiAgICA8bGk+RWxlbWVudG8gOTwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDEwPC9saT4NCiAgPC91bD4NCiAgPHA+U295IHVuIHDDoXJyYWZvIDQ8L3A+DQogIDx1bD4NCiAgICA8bGk+RWxlbWVudG8gMTwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDI8L2xpPg0KICAgIDxsaT5FbGVtZW50byAzPC9saT4NCiAgICA8bGk+RWxlbWVudG8gNDwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDU8L2xpPg0KICAgIDxsaT5FbGVtZW50byA2PC9saT4NCiAgICA8bGk+RWxlbWVudG8gNzwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDg8L2xpPg0KICAgIDxsaT5FbGVtZW50byA5PC9saT4NCiAgICA8bGk+RWxlbWVudG8gMTA8L2xpPg0KICA8L3VsPg0KICA8cD5Tb3kgdW4gcMOhcnJhZm8gNTwvcD4NCiAgPHVsPg0KICAgIDxsaT5FbGVtZW50byAxPC9saT4NCiAgICA8bGk+RWxlbWVudG8gMjwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDM8L2xpPg0KICAgIDxsaT5FbGVtZW50byA0PC9saT4NCiAgICA8bGk+RWxlbWVudG8gNTwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDY8L2xpPg0KICAgIDxsaT5FbGVtZW50byA3PC9saT4NCiAgICA8bGk+RWxlbWVudG8gODwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDk8L2xpPg0KICAgIDxsaT5FbGVtZW50byAxMDwvbGk+DQogIDwvdWw+DQogIDxwPlNveSB1biBww6FycmFmbyA2PC9wPg0KICA8dWw+DQogICAgPGxpPkVsZW1lbnRvIDE8L2xpPg0KICAgIDxsaT5FbGVtZW50byAyPC9saT4NCiAgICA8bGk+RWxlbWVudG8gMzwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDQ8L2xpPg0KICAgIDxsaT5FbGVtZW50byA1PC9saT4NCiAgICA8bGk+RWxlbWVudG8gNjwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDc8L2xpPg0KICAgIDxsaT5FbGVtZW50byA4PC9saT4NCiAgICA8bGk+RWxlbWVudG8gOTwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDEwPC9saT4NCiAgPC91bD4NCiAgPHA+U295IHVuIHDDoXJyYWZvIDc8L3A+DQogIDx1bD4NCiAgICA8bGk+RWxlbWVudG8gMTwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDI8L2xpPg0KICAgIDxsaT5FbGVtZW50byAzPC9saT4NCiAgICA8bGk+RWxlbWVudG8gNDwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDU8L2xpPg0KICAgIDxsaT5FbGVtZW50byA2PC9saT4NCiAgICA8bGk+RWxlbWVudG8gNzwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDg8L2xpPg0KICAgIDxsaT5FbGVtZW50byA5PC9saT4NCiAgICA8bGk+RWxlbWVudG8gMTA8L2xpPg0KICA8L3VsPg0KICA8cD5Tb3kgdW4gcMOhcnJhZm8gODwvcD4NCiAgPHVsPg0KICAgIDxsaT5FbGVtZW50byAxPC9saT4NCiAgICA8bGk+RWxlbWVudG8gMjwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDM8L2xpPg0KICAgIDxsaT5FbGVtZW50byA0PC9saT4NCiAgICA8bGk+RWxlbWVudG8gNTwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDY8L2xpPg0KICAgIDxsaT5FbGVtZW50byA3PC9saT4NCiAgICA8bGk+RWxlbWVudG8gODwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDk8L2xpPg0KICAgIDxsaT5FbGVtZW50byAxMDwvbGk+DQogIDwvdWw+DQogIDxwPlNveSB1biBww6FycmFmbyA5PC9wPg0KICA8dWw+DQogICAgPGxpPkVsZW1lbnRvIDE8L2xpPg0KICAgIDxsaT5FbGVtZW50byAyPC9saT4NCiAgICA8bGk+RWxlbWVudG8gMzwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDQ8L2xpPg0KICAgIDxsaT5FbGVtZW50byA1PC9saT4NCiAgICA8bGk+RWxlbWVudG8gNjwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDc8L2xpPg0KICAgIDxsaT5FbGVtZW50byA4PC9saT4NCiAgICA8bGk+RWxlbWVudG8gOTwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDEwPC9saT4NCiAgPC91bD4NCiAgPHA+U295IHVuIHDDoXJyYWZvIDEwPC9wPg0KICA8dWw+DQogICAgPGxpPkVsZW1lbnRvIDE8L2xpPg0KICAgIDxsaT5FbGVtZW50byAyPC9saT4NCiAgICA8bGk+RWxlbWVudG8gMzwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDQ8L2xpPg0KICAgIDxsaT5FbGVtZW50byA1PC9saT4NCiAgICA8bGk+RWxlbWVudG8gNjwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDc8L2xpPg0KICAgIDxsaT5FbGVtZW50byA4PC9saT4NCiAgICA8bGk+RWxlbWVudG8gOTwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDEwPC9saT4NCiAgPC91bD4NCjwvZGl2Pg==%7CKiB7DQogIG1hcmdpbjogMDsNCiAgcGFkZGluZzogMDsNCiAgYm94LXNpemluZzogYm9yZGVyLWJveDsNCiAgZm9udC1zaXplOiAxLjFyZW07DQp9DQoNCi8qIERlc3Bsw6F6YXRlIHBvciBlbCBkb2N1bWVudG8geSBkZXNwdcOpcyBxdWl0YSBsb3MgY29tZW50YXJpb3MgeSBvYnNlcnZhIGVsIGNvbXBvcnRhbWllbnRvICovDQoNCnAgew0KICAvKiBwb3NpdGlvbjogc3RpY2t5OyAqLw0KICAvKiB0b3A6IDA7ICovDQogIGJhY2tncm91bmQtY29sb3I6IGNvcm5mbG93ZXJibHVlOw0KICBwYWRkaW5nOiAxMHB4Ow0KfQ0KDQpsaSB7DQogIG1hcmdpbjogMjBweCAzMHB4Ow0KfQ0KDQoNCg0KDQoNCg0KDQoNCg0K%7C)

[Check the practice file](https://github.com/juancumbeq/platzi-frontend-developer/blob/main/resources/repo/curso-1/posicionamiento.html)
<br>
<br>

## [Z-index and the Stacking Context](https://github.com/juancumbeq/platzi-frontend-developer/blob/main/resources/repo/curso-1/z-index.html)
The stacking context refers to the overlapping of layers or elements along the Z-axis of the browser. This is crucial to avoid one element obscuring another.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/stacking-context.gif?raw=true" width= "75%" alt="Stacking context">
</p>

<br>

### What are Planes and Axes?
The browser consists of three planes and axes: width or X; height or Y; and depth or Z.

  - The positive X-axis points to the right.
  - The positive Y-axis points downward.
  - The positive Z-axis points toward the user.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/browser-planes-axes.png?raw=true" width= "75%" alt="Browser planes and axes">
</p>


These concepts are crucial for moving HTML elements from one point to another.

<br>

### What is the z-index Property?
The stacking context is configured using the ``z-index`` property.

By default, all elements have a value of ``auto``, meaning the order is defined by the structure of the HTML. The earliest elements will be at the back, and the later ones will be at the front.

If a positive value is set, the element is positioned in front of others. If a negative value is set, it is positioned behind.

If an element has a higher ``z-index`` than another, it will be in front. However, if an element has a lower ``z-index`` than others, its children will never be on top, even if their ``z-index`` is higher.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/z-index.png?raw=true" width= "75%" alt="Z-index">
</p>

[Example of Stacking Contexts](https://codi.link/PGRpdiBjbGFzcz0icmVkIj5SZWQ8L2Rpdj4NCjxkaXYgY2xhc3M9ImJsdWUiPkJsdWUNCiAgPGRpdiBjbGFzcz0ieWVsbG93Ij4NCiAgICBZZWxsb3cgKGhpam8gZGUgYmx1ZSkNCiAgPC9kaXY+DQo8L2Rpdj4=%7CLyogUXVpdGEgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBlbCByZXN1bHRhZG8gKi8NCg0KZGl2IHsNCiAgLyogcG9zaXRpb246IGFic29sdXRlOyAqLw0KfQ0KDQoucmVkew0KICAvKiB6LWluZGV4OiA1OyAqLw0KICAvKiB0b3A6IDUwcHg7ICovDQp9DQoNCi5ibHVlew0KICAvKiB6LWluZGV4OiA0OyAqLw0KICAvKiBsZWZ0OiA1MHB4OyAqLw0KfQ0KDQoueWVsbG93ew0KICAvKiB6LWluZGV4OiA2OyAqLw0KICAvKiByaWdodDogLTIwcHg7ICovDQogIC8qIHRvcDogNDBweDsgKi8NCn0NCg0KDQovKiBJZ25vcmEgbG9zIHNpZ3VpZW50ZXMgZXN0aWxvcyAqLw0KDQoqIHsNCiAgbWFyZ2luOiAwOw0KICBwYWRkaW5nOiAwOw0KICBib3gtc2l6aW5nOiBib3JkZXItYm94Ow0KICBmb250LXNpemU6IDEuMXJlbTsNCn0NCg0KZGl2IHsNCiAgd2lkdGg6IDIwMHB4Ow0KICBoZWlnaHQ6IDIwMHB4Ow0KfQ0KDQoucmVkew0KICBiYWNrZ3JvdW5kLWNvbG9yOiByZ2IoMjQ2LCAxMDgsIDEwOCk7DQp9DQoNCi5ibHVlew0KICBiYWNrZ3JvdW5kLWNvbG9yOiByZ2IoMTAyLCAxMDIsIDI0OSk7DQp9DQoNCi55ZWxsb3d7DQogIHdpZHRoOiAxNTBweDsNCiAgaGVpZ2h0OiAxNTBweDsNCiAgYmFja2dyb3VuZC1jb2xvcjogeWVsbG93Ow0KfQ0KDQoNCg0K%7C)

As you can see in the image, the element with the class "yellow" has a higher ``z-index`` than "red," but it isn't on top because its stacking context is within the stacking context of the "blue" element. Similarly, it will never be behind its parent element.

[Quiz](https://gist.github.com/teffcode/e0b3e89df22ecf5374527deaf31b11ca)

[Check the practice file](https://github.com/juancumbeq/platzi-frontend-developer/blob/main/resources/repo/curso-1/z-index.html)

<br>
<br>

## [Most used CSS Properties and Values]((https://github.com/juancumbeq/platzi-frontend-developer/blob/main/resources/repo/curso-1/propiedades-mas-usadas.html))
The most commonly used CSS properties are as follows, grouped into typical sections, some of which we are already familiar with:

  - Display
  - Margin
  - Padding
  - Border
  - Width
  - Height
  - Color
  - Background

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/common-css-properties.png?raw=true" width= "75%" alt="Common CSS properties">
</p>

Also, if you'd like to explore all existing CSS properties, you can visit the [CSS Reference website](https://cssreference.io/).

<br>

### Text Properties
The properties for manipulating text and typography are:

  - **font-size**: Sets the font size.
  - **font-weight**: Sets the text's boldness, with values from 100 to 900 in intervals of 100; 100 being thin and 900 being bold.
  - **font-family**: Sets the font type.
text-align: Sets the text alignment: right, left, center, or justify.
  - **color**: Sets the text color.

<br>

### Rounded Borders
The property that sets rounded borders is ``border-radius``.

[Example of Rounded Borders](https://codi.link/PGRpdiBjbGFzcz0iYm9yZGVyIj48L2Rpdj4NCjxkaXYgY2xhc3M9ImNpcmNsZSI+PC9kaXY+%7CZGl2IHsNCiAgd2lkdGg6IDIwMHB4Ow0KICBoZWlnaHQ6IDIwMHB4Ow0KICBiYWNrZ3JvdW5kLWNvbG9yOiBicm93bjsNCiAgbWFyZ2luOiAyMHB4Ow0KICBkaXNwbGF5OiBpbmxpbmUtYmxvY2s7DQp9DQoNCi5ib3JkZXJ7DQogIGJvcmRlci1yYWRpdXM6IDM1cHg7DQp9DQoNCi5jaXJjbGV7DQogIGJvcmRlci1yYWRpdXM6IDUwJTsNCn0NCg0KDQo=%7C)

<br>

### Challenge
Try to create a business card. You can base your design on the work of your classmates in the "Contributions" section.

You can use the following code as a reference.

[Example](https://codi.link/PHNlY3Rpb24+DQogIDxkaXYgY2xhc3M9ImNhcmQiPg0KICAgIDxpbWcgc3JjPSJodHRwczovL2ltYWdlcy5wZXhlbHMuY29tL3Bob3Rvcy8xMDU2MjUxL3BleGVscy1waG90by0xMDU2MjUxLmpwZWc/YXV0bz1jb21wcmVzcyZjcz10aW55c3JnYiZoPTY1MCZ3PTk0MCIgYWx0PSJjYXQiPg0KICAgIDxwPkNhdDogTWltaTwvcD4NCiAgICA8cD5Mb3ZlPC9wPg0KICA8L2Rpdj4NCjwvc2VjdGlvbj4=%7Cc2VjdGlvbiB7DQogIHdpZHRoOiAxMDAlOw0KICBkaXNwbGF5OiBmbGV4Ow0KICBqdXN0aWZ5LWNvbnRlbnQ6IGNlbnRlcjsNCn0NCg0KLmNhcmQgew0KICB3aWR0aDogMzAwcHg7DQogIGhlaWdodDogMzAwcHg7DQogIGJhY2tncm91bmQ6IHBhcGF5YXdoaXA7DQogIGJvcmRlci1yYWRpdXM6IDIwcHg7DQogIG92ZXJmbG93OiBoaWRkZW47DQp9DQoNCi5jYXJkIGltZyB7DQogIHdpZHRoOiAxMDAlOw0KfQ0KDQouY2FyZCBwIHsNCiAgdGV4dC1hbGlnbjogY2VudGVyOw0KfQ0KDQouY2FyZCBwOm50aC1jaGlsZCgzKSB7DQogIGNvbG9yOiBUdXJxdW9pc2U7DQp9%7C)

[Check the practice file]((https://github.com/juancumbeq/platzi-frontend-developer/blob/main/resources/repo/curso-1/propiedades-mas-usadas.html))

<br>
<br>
<br>

# RESPONSIVE DESIGN
## [Measurement Units]((https://github.com/juancumbeq/platzi-frontend-developer/blob/main/resources/repo/curso-1/unidades-de-medida.html))
Units of measurement determine the length for a specific element or typography. There are two types of measurements: absolute and relative.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/measurement-units.png?raw=true" width= "75%" alt="Measurement units">
</p>

<br>

### What are Absolute Measurements?
Absolute measurements are fixed values, so the measurement does not change. The most commonly used absolute unit is pixels ``(px)``, while others are used less frequently but are still worth knowing.

| Unit | Name                    | Equivalence            |
|------|-------------------------|------------------------|
| px   | pixels                  | 1 px = 1/96 in         |
| cm   | centimeters             | 1 cm = 96/2.54 px      |
| mm   | milimeters              | 1 mm = 1/10 cm         |
| Q    | quarters of a milimeter | 1 Q = 1/4 mm           |
| in   | inches                  | 1 in = 2.54 cm = 96 px |
| pc   | picas                   | 1 pc = 1/6 in          |
| pt   | points                  | 1 pt = 1/72 in         |

<br>

### What are Relative Measurements?
Relative measurements are variable values, so the measurement depends on an external value. These need to be used with caution, as a small change can lead to unexpectedly large sizes.

| Unit | Depends On                                               |
|------|----------------------------------------------------------|
| em   | the containing element                                   |
| rem  | the root element                                         |
| vm   | 1% of the screen width                                   |
| vh   | 1% of the height                                         |
| vmin | 1% of the smallest screen dimension                      |
| vmax | 1% of the largest screen dimension                       |
| ch   | the width of the character "0" in the containing element |
| lh   | the line height of the containing element                |

<br>

### Difference Between ``rem`` and`` em``
The ``em`` unit depends on the containing element's size. If an element has a font-size of ``20px``, then ``1em`` is equivalent to ``20px``, and ``2em`` would be ``40px``, and so on.

The ``rem`` unit depends on the root element. The font-size of the root element is usually ``16px``, so ``2rem`` is equivalent to ``32px``, and so on.

[Example of em Measurement](https://codi.link/PGRpdiBjbGFzcz0ibml2ZWwxIj4NCiAgPHA+TGV0cmEgZGUgMjBweDwvcD4NCiAgPGRpdiBjbGFzcz0ibml2ZWwyIj4NCiAgICA8cD5MZXRyYSBkZSAyMHB4PC9wPg0KICAgIDxkaXYgY2xhc3M9Im5pdmVsMyI+DQogICAgICA8cD5MZXRyYSBkZSA0MHB4PC9wPg0KICAgICAgPGRpdiBjbGFzcz0ibml2ZWw0Ij4NCiAgICAgICAgPHA+TGV0cmEgZGUgODBweDwvcD4NCiAgICAgIDwvZGl2Pg0KICAgIDwvZGl2Pg0KICA8L2Rpdj4NCjwvZGl2Pg==%7CKiB7DQogIG1hcmdpbjogMDsNCn0NCg0KLm5pdmVsMSB7DQogIC8qIFB1ZWRlcyBjYW1iaWFyIGVzdGUgdmFsb3IgKi8NCiAgZm9udC1zaXplOiAyMHB4Ow0KfQ0KDQoubml2ZWwyIHsNCiAgLyogdGFtYcOxbyA9IDIwcHggKiAxID0gMjBweCAqLw0KICBmb250LXNpemU6IDFlbTsNCn0NCg0KLm5pdmVsMyB7DQogIC8qIHRhbWHDsW8gPSAyMHB4ICogMiA9IDQwcHggKi8NCiAgZm9udC1zaXplOiAyZW07DQp9DQoNCi5uaXZlbDQgew0KICAvKiB0YW1hw7FvID0gNDBweCAqIDIgPSA4MHB4ICovDQogIGZvbnQtc2l6ZTogMmVtOw0KfQ0KDQoNCg==%7C)

In developer tools, you can view the font size in pixels.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/example-measurements.png?raw=true" width= "75%" alt="Measurement example">
</p>

[Example of rem Measurement](https://codi.link/PGRpdiBjbGFzcz0ibml2ZWwxIj4NCiAgPHA+TGV0cmEgZGUgMjBweDwvcD4NCiAgPGRpdiBjbGFzcz0ibml2ZWwyIj4NCiAgICA8cD5MZXRyYSBkZSAxNnB4PC9wPg0KICAgIDxkaXYgY2xhc3M9Im5pdmVsMyI+DQogICAgICA8cD5MZXRyYSBkZSAzMnB4PC9wPg0KICAgICAgPGRpdiBjbGFzcz0ibml2ZWw0Ij4NCiAgICAgICAgPHA+TGV0cmEgZGUgMzJweDwvcD4NCiAgICAgIDwvZGl2Pg0KICAgIDwvZGl2Pg0KICA8L2Rpdj4NCjwvZGl2Pg==%7CLm5pdmVsMSB7DQogIC8qIFB1ZWRlcyBjYW1iaWFyIGVzdGUgdmFsb3IgKi8NCiAgZm9udC1zaXplOiAyMHB4Ow0KfQ0KDQoubml2ZWwyIHsNCiAgLyogdGFtYcOxbyA9IDE2cHggKiAxID0gMTZweCAqLw0KICBmb250LXNpemU6IDFyZW07DQp9DQoNCi5uaXZlbDMgew0KICAvKiB0YW1hw7FvID0gMTZweCAqIDIgPSAzMnB4ICovDQogIGZvbnQtc2l6ZTogMnJlbTsNCn0NCg0KLm5pdmVsNCB7DQogIC8qIHRhbWHDsW8gPSAxNnB4ICogMiA9IDMycHggKi8NCiAgZm9udC1zaXplOiAycmVtOw0KfQ0KDQoNCg==%7C)

<br>

### Difference Between Percentages and Screen Width/Height
Percentages represent the size relative to the total size of the parent element. If the parent element is ``20px``, then ``100%`` would be ``20px``.

On the other hand, the units ``vw`` (view width) and ``vh`` (view height) represent the size relative to the total screen size. If an element has a size of ``100vw``, it takes up ``100%`` of the screen's width.

If an element occupies the full screen size, then only at that point does ``100%`` equal ``100vw`` or ``100vh``.

<br>

### Problem with Text Measurements
Browsers have an option to change text size. With absolute measurements, the text size will not change, which can be a problem for users.

With relative measurements, the text size changes based on the root element's font size, which is a good solution for accessibilit``y. The ``rem`` unit is particularly useful for this.

However, the default ``rem`` is equivalent to ``16px``, which can be confusing when using larger values. To address this, you can adjust the root element's font-size so that ``1rem`` is equal to ``10px``.

In the ``<html>`` tag, change the ``font-size`` property to ``62.5%``, based on a simple ratio: if ``16px`` is ``100%``, what percentage represents 10px?
```
html {
    font-size: 62.5%;
}
```

With this change, 1rem will equal 10px, allowing you to use it without issue, and your text will adapt to user preferences.

[Check the practice file]((https://github.com/juancumbeq/platzi-frontend-developer/blob/main/resources/repo/curso-1/unidades-de-medida.html))

<br>
<br>

## [Responsive Design]((https://github.com/juancumbeq/platzi-frontend-developer/blob/main/resources/repo/curso-1/diseño-responsivo.html))
Responsive Design is a set of tools that ensure your site looks good across various screen sizes, including adjustments for images, typography, page internationalization, and more.

Currently, most websites are accessed from mobile devices, so ensuring that your site is responsive on any device is crucial for optimizing revenue.

<br>

### What Are Media Queries?
Media queries are CSS rules that define different behaviors or styles within a certain range of screen sizes. This helps set the layout of the website for different screen types: desktops, tablets, and mobile devices.

There are two types of media queries:

  - ``max-width / max-height``: Sets a maximum range for certain behaviors.
  - ``min-width / min-height``: Sets a minimum range for certain behaviors.

These values function similarly to conditionals; as long as the condition is met, certain styles will be applied.

<br>

### Structure of a Media Query
The structure of a media query begins with ``@media``, followed by the type of media query that establishes a range, with the CSS rules enclosed within that range.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/media-queries.png?raw=true" width= "75%" alt="Media queries">
</p>

```
@media (max-width: 750px) {
    div {
        color: red;
    }
    p {
        background-color: red;
    }
}
```

<br>

### Developer Tools for Media Queries
To check if the changes are applied correctly, developer tools are very helpful.

Open your browser's developer tools and click on "Toggle device tool." This allows you to manipulate the screen size and see at what pixel widths certain styles are applied.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/dev-tool-media-queries.png?raw=true" width= "75%" alt="Media queries">
</p>

Use the following example to visualize how styles change depending on the screen's length. You can examine the media query in the code snippet. Although the example only changes the color of two elements, any property can be modified, so feel free to experiment.

[Example of Media Queries](https://codi.link/PGRpdiBjbGFzcz0iY2FyZDEiPjwvZGl2Pg0KPGRpdiBjbGFzcz0iY2FyZDIiPjwvZGl2Pg0KDQo=%7CKiB7DQogIG1hcmdpbjogMDsNCiAgcGFkZGluZzogMDsNCiAgYm94LXNpemluZzogYm9yZGVyLWJveDsNCn0NCg0KYm9keSB7DQogIHdpZHRoOiAxMDB2dzsNCiAgaGVpZ2h0OiAxMDB2aDsNCn0NCg0KLmNhcmQxew0KICB3aWR0aDogMTAwJTsNCiAgaGVpZ2h0OiAyNSU7DQogIGJhY2tncm91bmQtY29sb3I6IGJyb3duOw0KfQ0KDQouY2FyZDIgew0KICB3aWR0aDogNTAlOw0KICBoZWlnaHQ6IDc1JTsNCiAgYmFja2dyb3VuZC1jb2xvcjogY2hhcnRyZXVzZTsNCn0NCg0KQG1lZGlhIChtaW4td2lkdGg6IDUwMHB4KXsNCiAgLmNhcmQxIHsNCiAgICAgIGJhY2tncm91bmQtY29sb3I6IGNoYXJ0cmV1c2U7DQogIH0NCg0KICAuY2FyZDIgew0KICAgIGJhY2tncm91bmQtY29sb3I6IGJyb3duOw0KICB9DQp9DQoNCg==%7C)

[Check the practice file]((https://github.com/juancumbeq/platzi-frontend-developer/blob/main/resources/repo/curso-1/diseño-responsivo.html))

<br>
<br>
<br>

# CSS ARCHITECTURE
## [What are the CSS architectures? What are they used for?]()
CSS architectures involve managing CSS code with a series of rules and patterns to facilitate readability, maintainability, and scalability.

The code you've worked with so far doesn't resemble reality, as you will likely handle several hundred or thousands of lines of code. CSS architectures aim to maintain a standard in the code so that anyone can add or remove functionality without much effort.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/css-architecture.png?raw=true" width= "75%" alt="CSS architecture">
</p>

<br>

### Goals of CSS Architectures
The goals of CSS architectures are:

  - **Predictable**: The code should be as simple as possible.
  - **Reusable**: The code should be as non-redundant as possible to avoid issues with specificity.
  - **Maintainable**: The code should be easy to manage for adding or removing styles.
  - **Scalable**: The code should be able to grow as needed.

<br>

### Best Practices for CSS Architectures
The best practices for CSS architectures are:

  - **Guidelines and Standards**: Define rules within your workgroup about how the code should be written.
  - **Documentation**: Establish a brief explanation of the code and guidelines, which is especially useful for new team members to get familiar with what they should do.
  - **Components**: Define each element of your page in a componentized manner, handling them in parts, and then combine them into a whole.

<br>
<br>

## [OOCSS, BEM, SMACCSS, ITCSS and Atomic Design]()
Now that you understand what it means to work with a CSS architecture, let's explore the most common ones when working with CSS code.

<br>

### What is Object-Oriented CSS?
The **OOCSS (Object-Oriented CSS)** architecture involves separating the main structure from the skin or mask.

In other words, it involves having objects that are the main structures. These objects are wrapped in a skin that can change while keeping the structure intact.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/oocss.png?raw=true" width= "75%" alt="OCCSS">
</p>

<br>

### What is BEM: Block, Element, and Modifier?
The **BEM (Block-Element-Modifier)** architecture is one of the most widely used today. It involves managing elements through classes defined by blocks, elements, and modifiers.

  - **Block**: The main structure that contains multiple elements.
  - **Element**: The HTML element referenced by the container.
  - **Modifier**: A specific style for the element, such as a button with a different color, often related to specificity.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/bem.png?raw=true" width= "75%" alt="BEM">
</p>

You can learn more about this architecture in the following article:

[BEM Guide for CSS | Falcon 9 Rocket by SpaceX](https://platzi.com/blog/bem/)

<br>

### What is the Scalable and Modular Architecture for CSS?
The **SMACSS (Scalable and Modular Architecture for CSS)** architecture defines the order of components that will be placed in folders. Combining these components results in a styled web page.

  - **Base**: Basic elements like buttons, headings, links.
  - **Layout**: Page structure, related to Responsive Design.
  - **Modules**: Elements that contain the base elements.
  - **State**: Styles related to element behavior, often tied to pseudo-classes and pseudo-elements.
  - **Themes**: A set of styles that define your web page's look.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/smacss.png?raw=true" width= "75%" alt="SMACSS">
</p>

<br>

### What is the Inverted Triangle CSS Architecture?
The **ITCSS (Inverted Triangle CSS)** architecture involves separating project files by adjustments, tools, elements, and other categories. This is done to manage specificity, clarity, and scale.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/itcss.png?raw=true" width= "75%" alt="ITCSS">
</p>

<br>

### What is Atomic Design?
The Atomic Design architecture is also one of the most widely used today. It involves managing elements as a minimum structure, where the combination of several of these results in the styles for a web page. It is based on the minimal structure of matter: atoms.

  - **Atoms**: The minimum structure, like buttons, links, headings, etc.
  - **Molecules**: A combination of atoms.
  - **Organisms**: A combination of molecules.
  - **Templates**: A combination of organisms.
  - **Pages**: A combination of templates.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-frontend-developer/blob/main/readme_images/atomic-design.png?raw=true" width= "75%" alt="Atomic Design">
</p>

<br>
<br>
<br>

# NEXT STEPS
### [CSS Battle](https://cssbattle.dev/)
### [Codepen](https://codepen.io/)
### [Coderbyte](https://coderbyte.com/challenges)
### [Frontend Mentor](https://www.frontendmentor.io/challenges)

<br>
<br>
<br>

# Author

This project was developed by *Juan Cumbe*. If you have any questions or suggestions about the project, feel free to contact me via [e-mail](mailto:hello@juancumbe.com) or my [Linkedin](https://www.linkedin.com/in/juancumbeq/) profile. 