# Typography CSS library
**Author:** *Richard Komňacký*
## Demo site
Link to **[demo](http://www.github.io)** site for preview.

## Implementation
```
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Normalize</title>
    <link rel="stylesheet" href="typography.css">
</head>
```
## Usage
Download typography.css

This css changes styles of:
* html, body
* header, main, footer
* nav, ul, ol, li
* section, article
* h1, h2, h3
* p, abbr. strong
* a
* figure, figcaption, img

## Components
### Body
```html
<body>
    <header></header>
    <main></main>
    <footer></footer>
</body>
```
### Header with navigation
```html
<header>
    <h1><a href="./index.html">Toto je H1</a></h1>
    <nav>
        <ul>
            <li><a href="">Header</a></li>
            <li><a href="">Main</a></li>
            <li><a href="">Footer</a></li>
        </ul>
    </nav>
</header>
```
### Figure
```html
<figure>
    <img src="./Images/Blue.jpg" alt="Blue">
    <figcaption>Popisek: Modrá barva</figcaption>
</figure>
```
### Article
```html
<article>
     <h3>Toto je H3</h3>
     <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Repellat quae adipisci nihil est possimus
         debitis voluptas tempore et, sit suscipit, rerum, placeat illo qui voluptatum vero mollitia. Ipsum,
         earum eaque.</p>
</article>
```
### Footer
```html
<footer id="3footer">
    <h3>Footer</h3>
    <ul>
      <li>Richard Komňacký</li>
      <li>richard.komnacky@pslib.cz</li>
      <li>02.10.2020</li>
    </ul>
</footer>
```

