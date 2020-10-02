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
  <link rel="stylesheet" href="style.css" />
  <link rel="stylesheet" href="normalize.css" />
  <link href="https://fonts.googleapis.com/css2?family=Crimson+Pro:wght@200;300;400;500;600;700;800;900&display=swap"
    rel="stylesheet" />
  <link
    href="https://fonts.googleapis.com/css2?family=Work+Sans:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600&display=swap"
    rel="stylesheet" />
  <link href="https://fonts.googleapis.com/css2?family=Merriweather:wght@300;400;700;900&display=swap"
    rel="stylesheet" />

  <script src="https://unpkg.com/smartphoto@1.1.0/js/smartphoto.min.js"></script>
  <link rel="stylesheet" href="https://unpkg.com/smartphoto@1.1.0/css/smartphoto.min.css" />
</head>
```

## Usage
Online blog with images
* ul/ol
* blockquote, q
* b, i, a
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
    <article>
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
      <article>
        <div>
          <p>Aspernatur commodi minus totam, nisi quia quod praesentium iusto
          eius maiores tempore perferendis ut alias adipisci! Ullam, libero! Illum!</p>
        </div>
      </article>
     </main>
```
      
### Lists
```
        <ul>
          <li>textik</li>
          <ul>
            <li>textik...</li>
             <ul>
               <li>textik...</li>
               <li>textik...</li>
             </ul>
           </ul>
         </ul>
         <ol>
           <li>textik</li>
           <ol>
             <li>textik...</li>
           </ol>
         </ol>
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

### Footer
```
  <footer>
    <nav>
      <ul>
        <li><a href="#">Footer link 1</a></li>
        <li><a href="#">Footer link 2</a></li>
        <li><a href="#">Footer link 3</a></li>
      </ul>
    </nav>
  </footer>
```

