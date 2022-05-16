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
<a href="https://www.google.com/" />
```
