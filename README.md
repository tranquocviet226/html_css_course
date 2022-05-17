### 1. Overview of Web Development
  **1.1. Frontend vs Backend Development**
  ![image](https://user-images.githubusercontent.com/57559641/168515156-cb952249-6732-4677-806d-fd6440c2489d.png)

  **1.2. Static website vs Dynamic website** 
| Static website | Dynamic website  |
|--|--|
|Websites where files are simply sent to browser as they are  | Website files are assemble on the server|
|Without any transfomation  | There are transformation |
|Don't need a server  | Need a server |

  **1.3. Three languages of the Frontend**
  ![image](https://user-images.githubusercontent.com/57559641/168516443-811becbd-ad1e-4c0a-836f-3f3e1ad43f74.png)

### 2. HTML Document structure
HTML stands for Hyper Text Markup Language
```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>

<body>

</body>

</html>
```

### 3. Text Elements
```<h1> - <h6>```: Heading

```<p>```: Paragraph

```<strong>```: The ```<strong>``` tag is used to define text with strong importance. The content inside is typically displayed in <strong>bold</strong>

```<em>```: The ```<em>``` tag is used to define emphasized text. The content inside is typically displayed in <em>italic</em>

```<span>```: The ```<span>``` tag is an inline container used to mark up a part of a text, or a part of a document.

```html
<h1>The Basic Language of the Web: HTML</h1>
<h2>The Basic Language of the Web: HTML</h2>
<h3>The Basic Language of the Web: HTML</h3>
<h4>The Basic Language of the Web: HTML</h4>
<h5>The Basic Language of the Web: HTML</h5>
<h6>The Basic Language of the Web: HTML</h6>

<p>Posted by <strong>Laura Jones</strong> on Monday, June 21st 2027</p>
<p>
  All modern websites and web applications are built using three
  <em>fundamental</em>
  technologies: HTML, CSS and JavaScript. These are the languages of the
  web.
</p>
<span>This paragraph will in line</span>

```

### 4. List Elements
```html
<ul>
  <li>To be able to use the fundamental web dev language</li>
  <li>
    To hand-craft beautiful websites instead of relying on tools like
    Worpress or Wix
  </li>
  <li>To build web applications</li>
  <li>To impress friends</li>
  <li>To have fun 😃</li>
</ul>

<ol>
  <li>To be able to use the fundamental web dev language</li>
  <li>
    To hand-craft beautiful websites instead of relying on tools like
    Worpress or Wix
  </li>
  <li>To build web applications</li>
  <li>To impress friends</li>
  <li>To have fun 😃</li>
</ol>
```

### 5. Images and Attributes
```html
<img 
     src="https://user-images.githubusercontent.com/57559641/168515156-cb952249-6732-4677-806d-fd6440c2489d.png" 
     alt="This is an image"
     width="500"
     height="200"
/>
```

### 6. Hyperlinks
```html
<a href="https://www.google.com/">Google link</a>
```

### 7. Structuring our page
![image](https://user-images.githubusercontent.com/57559641/168518770-d12d541c-db47-4d91-9dd4-50ab77d34ac2.png)

```html
<nav>
  <a href="blog.html">Blog</a>
  <a href="#">Challenges</a>
  <a href="#">Flexbox</a>
  <a href="#">CSS Grid</a>
</nav>
<header>
  <h2>The Basic Language of the Web: HTML</h2>

  <img src="img/laura-jones.jpg" alt="Headshot of Laura Jones" height="50" width="50" />

  <p>Posted by <strong>Laura Jones</strong> on Monday, June 21st 2027</p>

  <img src="img/post-img.jpg" alt="HTML code on a screen" width="500" height="200" />
</header>

<article>
  <p>
    All modern websites and web applications are built using three
    <em>fundamental</em>
    technologies: HTML, CSS and JavaScript. These are the languages of the
    web.
  </p>

  <p>
    In this post, let's focus on HTML. We will learn what HTML is all about,
    and why you too should learn it.
  </p>

  <h3>What is HTML?</h3>
  <p>
    HTML stands for <strong>H</strong>yper<strong>T</strong>ext
    <strong>M</strong>arkup <strong>L</strong>anguage. It's a markup
    language that web developers use to structure and describe the content
    of a webpage (not a programming language).
  </p>
  <p>
    HTML consists of elements that describe different types of content:
    paragraphs, links, headings, images, video, etc. Web browsers understand
    HTML and render HTML code as websites.
  </p>
  <p>In HTML, each element is made up of 3 parts:</p>

  <ol>
    <li>The opening tag</li>
    <li>The closing tag</li>
    <li>The actual element</li>
  </ol>

  <p>
    You can learn more at
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="_blank">MDN Web Docs</a>.
  </p>

  <h3>Why should you learn HTML?</h3>

  <p>
    There are countless reasons for learning the fundamental language of the
    web. Here are 5 of them:
  </p>

  <ul>
    <li>To be able to use the fundamental web dev language</li>
    <li>
      To hand-craft beautiful websites instead of relying on tools like
      Worpress or Wix
    </li>
    <li>To build web applications</li>
    <li>To impress friends</li>
    <li>To have fun 😃</li>
  </ul>

  <p>Hopefully you learned something new here. See you next time!</p>
</article>

<aside>
  <h4>Related posts</h4>

  <ul>
    <li>
      <img src="img/related-1.jpg" alt="Person programming" width="75" width="75" />
      <a href="#">How to Learn Web Development</a>
      <p>By Jonas Schmedtmann</p>
    </li>
    <li>
      <img src="img/related-2.jpg" alt="Lightning" width="75" heigth="75" />
      <a href="#">The Unknown Powers of CSS</a>
      <p>By Jim Dillon</p>
    </li>
    <li>
      <img src="img/related-3.jpg" alt="JavaScript code on a screen" width="75" height="75" />
      <a href="#">Why JavaScript is Awesome</a>
      <p>By Matilda</p>
    </li>
  </ul>
</aside>

<footer>Copyright &copy; 2027 by The Code Magazine.</footer>
```

### 8. Semantic HTML
Semantic elements = elements with a meaning.

A semantic element clearly describes its meaning to both the browser and the developer.

Examples of non-semantic elements: ```<div>``` and ```<span>``` - Tells nothing about its content.

Examples of semantic elements:```header```, ```<form>```, ```<table>```, and ```<article>``` - Clearly defines its content.

- ```<article>```
- ```<aside>```
- ```<details>```
- ```<figcaption>```
- ```<figure>```
- ```<footer>```
- ```<header>```
- ```<main>```
- ```<mark>```
- ```<nav>```
- ```<section>```
- ```<summary>```
- ```<time>```
 
 ### 9. CSS Fundamentals
 CSS stands for Cascading Style Sheets
 
 ### 10. Inline, Internal and External CSS
 **10.1. Inline CSS**
 ```html
<p style="color: red">The paragraph</p>
```
  
  **10.2 Internal CSS**
```html
<head>
 <meta charset="UTF-8" />
 <title>The Basic Language of the Web: HTML</title>
 <style>
  p {
   color: red;
  }
 </style>
</head>

<body>
 <p>The paragraph</p>
</body>
```

**10.3 External CSS**

index.html
```html
<head>
 <meta charset="UTF-8" />
 <link href="style.css" rel="stylesheet" />
 <title>The Basic Language of the Web: HTML</title>
</head>

<body>
 <p>The paragraph</p>
</body>
```

style.css
```css
p {
 color: red;
}
```
### 11. Styling Text
p {
 color: red;
 font-size: 14px;
 font-family: sans-serif;
 font-weight: bold;
 font-style: italic;
 text-transform: uppercase;
 line-height: 1.5;
 text-align: center;
}

### 12. Selectors
index.html 
```html
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<p id="paragraph-id">This is paragraph ID</p>
<p class="paragraph-class">This is paragraph Class</p>
```
style.css

**12.1. Combining selectors**
```css
h1 h2 h3 p {
 color: red;
}
```
**12.2. ID and Class selectors**
```css
#paragraph-id {
 color: green;
}

.paragraph-class {
 color: blue;
}
```

**ID name is unique, do not allow repeat ID name**

### 13. CSS Colors
![image](https://user-images.githubusercontent.com/57559641/168717176-40afc542-2c8c-4f6c-98be-e13ae38a3051.png)

- Every color can be represented  by a combination of **Red**, **Green** and **Blue**
- Each of 3 base colors can take a value between **0** and **255** with leads to 16.8 million colors

```css
 h1 {
  color: red;
 }
 
 h2 {
  color: #ff0000;
 }
 
 h3 {
  color: rgba(255, 0, 0 ,1);
 }
```

- Colors value from **0** - **255**  === **00** - **FF**
- Example: 

 rgb(0, 0, 0) === #000000
 
 rgb(255, 255, 255) === #FFFFFF

### 14. Pseudo classes
index.html
```html
<a>This is red</a>
<a href="#">This is green</a>
```

```css
li:first-child {
 color: red;
}

li:last-child {
 color: green;
}

li:nth-child(2) {
 color: blue;
}

a {
 color: red;
}

a:link {
 color: green;
}

a:visited {
 color: violet;
}

a:hover {
 background-color: green;
}

a:active {
 background-color: green;
}
```

### 15. CSS Priority
![image](https://user-images.githubusercontent.com/57559641/168724545-ac562e95-ec4b-44ef-8839-49a18540cc5d.png)

index.html
```html
<p id="author" class="text author" style="color: orange">Author VietTQ</p>
```

style.css
```css
#author {
 color: red;
}

.author {
 color: green;
}

.text {
 color: yellow;
}

p {
 color: violet !important;
}

```
