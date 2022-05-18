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

## I. HTML Fundamentals
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
 
 ## II. CSS Fundamentals
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
**Last class > First class**

### 16. Universal selector
```css
*{
 color: red;
}

body {
 color: green;
}
```
**```*```** applied style for all elements

**```body```** inherited style for children elements

### 17. CSS Box model
![image](https://user-images.githubusercontent.com/57559641/168726620-1c1a1521-5f1b-4434-83e9-49bceeca341f.png)

```css
p {
 margin: 8px;
 border: 1px solid red;
 padding: 8px;
 color: violet;
 background-color: green;
}
```

### 18. Dimentions and Center our page
```css
.div-1 {
 width: 500px;
 background-color: green;
 margin-left: auto;
 margin-right: auto;
}

.div-2 {
 width: 500px;
 background-color: blue;
 margin: 0 auto;
}
```
### 19. Types of boxes
**19.1 Block-elements**
- Elements occupy 100%  of the parent element's width
- Elements are stacked vertical by default 
- Example: ```div```, ```body```, ```main```, ```header```, ```footer```, ```section```, ```nav```, ```aside```, ```h1 - h6```, ```p```, ```ul```, ```ol```, ```li```,...

**19.2 Inline-elements**
 - Occupy only exactly the **space necessary for its content**
 - **No line-break** after of before the element
 - **Height** and **width** **do not apply**
 - **Paddings** and **margins** are applied only **horizontally**

**19.3 Inline-block elements**
- space necessary for its content
- No line-break
- Height and width can be apply
- Paddings and margins can apply

|Block|Inline|Inline-block|
|--|--|--|
|Elements occupy 100%  of the parent element's width|Occupy only exactly the space necessary for its content|Occupy only exactly the space necessary for its content|
|Elements are stacked vertical by default|No line-break after of before the element|No line-break after of before the element|
|Height and width can be apply|Height and width do not apply|Height and width can be apply|
|Paddings and margins can be apply |Paddings and margins are applied only horizontally|Paddings and margins can be apply|

### 20. Absolute Positioning
![Screenshot from 2022-05-17 13-40-42](https://user-images.githubusercontent.com/57559641/168745706-c6716563-ec2c-40c1-96a9-1f7b54a1bbac.png)

```html
<div class="div-1">
  <div class="div-2">
    <button>Click me</button>
  </div>
</div>
```
```css
.div-1 {
  position: relative;
  background-color: red;
  width: 400px;
  height: 200px;
}
.div-2 {
  background-color: green;
  width: 200px;
  height: 100px;
}
button {
  position: absolute;
  top: 20px;
  right: 20px;
 }
```
![Screenshot from 2022-05-17 13-39-11](https://user-images.githubusercontent.com/57559641/168745435-82a80f30-55a6-46e4-ba5f-8d62cf7d8e29.png)

### 21. Pseudo Elements
index.html
```html
<div>DIV</div>
<p>AAA</p>
<p>BBB</p>
<p>CCC</p>
<h1>Heading</h1>
```
```css
h1::first-letter {
 color: red;
}

p::first-line {
 color: green;
}

/* This is sibling element get the first p tag right after the div tag */
div + p::first-letter {
 color: violet;
}

h1 {
 position: relative;
 background-color: orange;
}

h1::after {
 content: "AFTER";
 color: yellow;
 position: absolute;
 top: -10px;
 right: -20px;
}

h1::before {
 content: "BEFORE";
 color: yellow;
 position: absolute;
 top: -10px;
 left: -20px;
}
```
## III. Layouts Fundamentals
![Screenshot from 2022-05-17 14-46-15](https://user-images.githubusercontent.com/57559641/168757727-cbee3e81-4279-483f-bdfe-01ad574f5875.png)

### 22. Float Layouts
```html
<div class="container clearfix">
  <img src="img/laura-jones.jpg" alt="Headshot of Laura Jones" height="50" width="50" class="author-img" />

  <p id="author" class="author">
    Posted by <strong>Laura Jones</strong> on Monday, June 21st 2027
  </p>
</div>
```

```css
.container {
  background-color: aqua;
}

.author-img {
  float: left;
}

.author {
  float: right;
}

.clearfix::after {
  content: "";
  clear: both;
  display: block;
}
```

### 23. Simple Float layouts
![Screenshot from 2022-05-17 15-28-57](https://user-images.githubusercontent.com/57559641/168766556-e2e14462-8505-4b48-99df-593bf083abca.png)

index.html
```html
<div class="container">
  <header>
    <img src="img/laura-jones.jpg" alt="Headshot of Laura Jones" height="50" width="50" class="author-img" />

    <p id="author" class="author">
      Posted by <strong>Laura Jones</strong> on Monday, June 21st 2027
    </p>
    <div class="clear"></div>
  </header>
 
  <article>Article</article>
 
  <aside>Aside</aside>

  <footer>Copyright</footer>
</div>
```

style.css
```css
* {
 box-sizing: boder-box;
}

.container {
  width: 1200px;
  margin: 0 auto;
}

header {
  background-color: aqua;
}

header::after {
  content: "";
  clear: both;
  display: block;

}

.author-img {
  float: left;
}

.author {
  float: right;
}

article {
  width: 900px;
  height: 800px;
  background-color: violet;
  float: left;
}

aside {
  width: 300px;
  height: 500px;
  background-color: green;
  float: right;
}

footer {
  background-color: yellow;
  clear: both;
}
```

### 24. Box-sizing: border-box
![Screenshot from 2022-05-17 15-41-54](https://user-images.githubusercontent.com/57559641/168769199-40dca23e-777a-4bbc-a008-d784228cfa1d.png)
- ```box-sizing``` default is ```content-box```
- ```box-sizing: border-box``` set **element = padding + border + width/height**

```css
* {
 box-sizing: border-box;
}
```

### 25. Flexbox Layouts
![Screenshot from 2022-05-18 10-27-00](https://user-images.githubusercontent.com/57559641/168951153-04e83f67-1dba-4f15-904f-ee044fdfd3cb.png)


We have basic layout

index.html
```html
<div class="container">
  <div class="el el--1">Item 1</div>
  <div class="el el--2">Item 2</div>
  <div class="el el--3">Item 3</div>
  <div class="el el--4">Item 4</div>
  <div class="el el--5">Item 5</div>
  <div class="el el--6">Item 6</div>
  <div class="el el--7">Item 7</div>
  <div class="el el--8">Item 8</div>
</div>
```
style.css
```css
.el--1 {
  background-color: blueviolet;
}

.el--2 {
  background-color: orangered;
}

.el--3 {
  background-color: green;
  height: 150px;
}

.el--4 {
  background-color: goldenrod;
}

.el--5 {
  background-color: palevioletred;
}

.el--6 {
  background-color: steelblue;
}

.el--7 {
  background-color: yellow;
}

.el--8 {
  background-color: crimson;
}
```
![Screenshot from 2022-05-18 08-56-49](https://user-images.githubusercontent.com/57559641/168941369-bd71420f-9fa0-4632-9c75-15b5a39d6edf.png)

**25.1 Flex**

Then, put ```flex``` layout to them

```css
.container {
 display: flex;
 background-color: gray;
}
```
![Screenshot from 2022-05-18 09-04-30](https://user-images.githubusercontent.com/57559641/168942206-83917167-fb32-4443-bcb3-e76a9e446c6b.png)

**25.2 Flex vertical**

And, put ```align-items: center``` to center vertical, besides, we can put ```flex-start```, ```flex-end```, ```stretch```
```css    
.container {
 display: flex;
 background-color: gray;
 align-items: center;
}
```
![Screenshot from 2022-05-18 09-11-25](https://user-images.githubusercontent.com/57559641/168942896-0b374a2a-bfd8-4987-b4fc-9842c5df7282.png)

**25.3 Flex horizontal**

Put ```justify-content: center``` to center horizontal, besides ```flex-start```, ```flex-end```, ```space-between```, ```space-around```
```css
.container {
 display: flex;
 background-color: gray;
 justify-content: center;
}
```
![Screenshot from 2022-05-18 09-20-54](https://user-images.githubusercontent.com/57559641/168944007-a1ba1c57-b648-4d5c-bab0-464f4df4a6ff.png)

**25.4 Flex Item**

**```align-self```** : ```center```, ```flex-start```, ```flex-end```, ```stretch```
```css
.el--1 {
  align-self: flex-start;
}
.el--2 {
  align-self: flex-end;
}
```
![Screenshot from 2022-05-18 10-37-43](https://user-images.githubusercontent.com/57559641/168952243-8d5626c3-d0ca-4b3d-81f6-f43accf99588.png)


**25.5 Order items**

Default order is **0**, we can specify ```order``` to sort items

```css
.el--1 {
  align-self: flex-start;
  order: 5;
}
.el--2 {
  align-self: flex-end;
  order: 4;
}
.el--3 {
  order: 3;
}
.el--4 {
  order: 2;
}
.el--5 {
  align-self: stretch;
  order: 1;
}
.el--6 {
  order: 0;
}
```
![Screenshot from 2022-05-18 10-46-48](https://user-images.githubusercontent.com/57559641/168953124-3e5bd841-cc73-48d8-b0c1-4812da9ac3ac.png)

**25.6 Space between each item**

We can use **```gap```** property

```css
.container {
  gap: 30px;
}
```
![Screenshot from 2022-05-18 11-00-28](https://user-images.githubusercontent.com/57559641/168954526-4bbdb43c-4d6b-48c3-87a8-288c9a6378b7.png)

**25.7 Flex property**

Default flex item
```css
.el {
 flex-grow: 0;
 flex-shrink: 1;
 flex-basis: auto;
 
 /* The same */
 flex: 0 1 auto;
}
```

**```flex-basics```** to set item width = 100px, when content is large than 100px then the elements extends to fit that content.

```css
.el--1 {
  background-color: blueviolet;
  white-space: nowrap;
}
    
.el {
  flex-basis: 100px;
}
```
![IMG](https://user-images.githubusercontent.com/57559641/168958556-eaab9f5a-665e-4d1c-9419-e6a0184d9d30.png)

**```flex-shrink```** default is **1** mean if items > content then items can resize < 100px, if set to **0** items alway >=100px

```css
.el {
   flex-basis: 100px;
   flex-shrink: 0;
}
```
![Screenshot from 2022-05-18 14-11-47](https://user-images.githubusercontent.com/57559641/168979203-36e8687e-e189-4698-a478-c6ea71c99c91.png)

**```flex-grow```** default **0**, set to **1** will fit items with the same content size
```css
.el {
 flex-shrink: 0;
 flex-grow: 1;
}
```
![Screenshot from 2022-05-18 14-16-19](https://user-images.githubusercontent.com/57559641/168979953-1bbc7f29-6001-498d-a8d7-1ed8ec3e8221.png)

### 26. Grid Layouts
![Screenshot from 2022-05-18 14-49-35](https://user-images.githubusercontent.com/57559641/168986372-697fb032-e7e9-44fc-8b89-23f5fea559a4.png)

index.html
```html
<div class="container">
  <div class="el el--1">Item 1</div>
  <div class="el el--2">Item 2</div>
  <div class="el el--3">Item 3</div>
  <div class="el el--4">Item 4</div>
  <div class="el el--5">Item 5</div>
  <div class="el el--6">Item 6</div>
  <div class="el el--7">Item 7</div>
  <div class="el el--8">Item 8</div>
</div>
```

style.css
```css
.container {
  background-color: lightgray;
  display: grid;
  grid-template-columns: 100px 200px;
}

.el--1 {
  background-color: red;
}

.el--2 {
  background-color: green;
}

.el--3 {
  background-color: blue;
}

.el--4 {
  background-color: violet;
}

.el--5 {
  background-color: yellow;
}

.el--6 {
  background-color: orange;
}

.el--7 {
  background-color: teal;
}

.el--8 {
  background-color: cyan;
}
```

**26.1 ```grid-template-columns```**

![Screenshot from 2022-05-18 14-53-51](https://user-images.githubusercontent.com/57559641/168987203-5dea468b-1b6b-45aa-9280-ec3b8eb7ba4f.png)

Another Grid
```css
.container {
   ...
   grid-template-columns: 100px 200px 100px 200px;
}
```
![Screenshot from 2022-05-18 15-03-29](https://user-images.githubusercontent.com/57559641/168989060-970bcbc0-601c-4c96-8936-1c9d698c8cf0.png)

**26.1 ```grid-template-rows```**

```css
.container {
  background-color: lightgray;
  display: grid;
  grid-template-columns: 100px 200px;
  grid-template-rows: 100px 200px;
}
```
![Screenshot from 2022-05-18 17-09-27](https://user-images.githubusercontent.com/57559641/169015212-16937bc1-3e65-4904-8020-7a0f80ebbe28.png)

**26.1 Gap property**

```css
.container {
 ...
 column-gap: 10px;
 row-gap: 20px;
}
```
![Screenshot from 2022-05-18 17-11-03](https://user-images.githubusercontent.com/57559641/169015564-2d82ecfb-d0b9-4fb7-a2e1-ae965138da44.png)
