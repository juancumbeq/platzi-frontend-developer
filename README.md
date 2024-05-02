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

### The Problem with the div Tag
The *div* tag defines a generic block of content that lacks semantic value. It's used for design elements like containers.

<br>

### Which Tags Are Semantic?
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

<br>
<br>
<br>

# RESPONSIVE DESIGN

<br>
<br>
<br>

# CSS ARCHITECTURE

<br>
<br>
<br>

# NEXT STEPS