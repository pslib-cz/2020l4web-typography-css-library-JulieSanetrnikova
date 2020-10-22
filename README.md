# Typography CSS library
**Author:** *Julie Sanetrníková*

## Demo site
Link to **[demo](http://www.github.io)** site for preview.

## Dependecies
```
<link rel="stylesheet" href="normalize.css" />
```

## Implementation
```
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Typography css library</title>
  
  <link rel="stylesheet" href="../typography.css" />
  /* <link rel="stylesheet" href="./layout.css" /> */

  <script src="https://unpkg.com/smartphoto@1.1.0/js/smartphoto.min.js"></script>
  <link rel="stylesheet" href="https://unpkg.com/smartphoto@1.1.0/css/smartphoto.min.css" />
</head>
```

## Usage
Online blog with images
* ul/ol, li
* blockquote, q
* b, em, strong, a
* h1, h2, h3

## Components
### Main header of page
 ```
 <header>
    <h1>Heading 1 - CSS typography library</h1>
    <p class="author"><b>Author: </b>Julie Sanetrníková</p>
    <p class="date">
      <b>Date: </b><time datetime="2020-09-18">18.9.2020</time>
    </p>
 </header>
  ```
  
 ### Header of article 
 ```
   <main>
    <article class="article">
      <header>
        <h2>Heading 2</h2>
        <p class="perex">
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Eveniet
          veniam iste doloribus placeat, laudantium officiis animi totam
          asperiores eius, ad voluptatem, magni praesentium cupiditate
          laboriosam impedit accusantium odit doloremque voluptatum?
        </p>
      </header>
    </article>
   </main>
   ```
   
### Paragraph in article
```
    <main>
      <article class="article">
        <div>
          <p>Aspernatur commodi minus totam, nisi quia quod praesentium iusto
          eius maiores tempore perferendis ut alias adipisci! Ullam, libero! Illum!</p>
        </div>
      </article>
     </main>
```
      
### Image in article
```
        <div class="thumbnails">
          <figure>
            <a href="./.../image.jpg">
              <img src="./.../image.jpg" alt="Image caption" />
              <div>
                <p>Image caption</p>
              </div>
            </a>
          </figure>
        </div>
```


