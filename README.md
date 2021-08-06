# Frontend Mentor - Profile card component solution

This is my website portfolio made by following a tutorial from a YouTube called [Build a Portfolio Website & Deploy by Traversy Media with Denis Ivy](https://www.youtube.com/watch?v=r_hYR53r61M)

## Table of contents

- [Overview](#overview)
  - [The Objective](#the-objective)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Code Snippets](#code-snippets)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The Objective

- Build out the project to the designs provided

### Screenshot

![](./images/screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

### Code Snippets

Proud of this Semantic HTML:

```html
  <main>
     <header>
       <picture>
         <img srcset="images/image-victor.jpg" alt="profile picture">
       </picture>
     </header>
     <figcaption>
       <strong>Victor Crest</strong> 26
       <br>
       London
     </figcaption>

      
      <section>
        <dl>
          <dt>80K</dt>
          <dd>Followers</dd>
        </dl>
        <dl>
          <dt>803K</dt>
         <dd>Likes<dd>
        </dl>
        <dl>
          <dt>1.4K</dt>
          <dd>Photos</dd>
        </dl>
      </section>
   </main>
```

Proud of this CSS Media Queries:

```css
@media (min-width: 376px) and (max-width: 1439px) {
    body {
        background-position: top -700px left -300px, bottom -650px right -300px;
        background-size: 1050px;
    }
}

@media (min-width: 1440px) {

    body {
        background-position: top -700px left -400px, bottom -700px right -380px;
        background-size: 1200px;
    }

    main {
       max-width: 100%;
       height: fit-content;
       font-size: .95em;
    }


    section {
        font-size: 1em;
    }
}

@media (max-width: 320px) {
    
    body {
        background-position: top -260px left -360px, bottom -260px right -360px;
        background-size: 500px;

    }

    main {
       max-width: 100%;
       max-height: fit-content;
       font-size: .85em;
    }


    section {
        font-size: 1em;
    }

    footer {
        font-size: .85em;
    }
}
```

### Continued development


### Useful resources

- [CSS Tricks for Media Queries for the Standard Devices](https://css-tricks.com/snippets/css/media-queries-for-standard-devices/) - This helped me for the CSS Media Queries.
- [MDN Web Docs CSS Media Queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries) - This is a very helpful concept.


## Author
- Github - [@BenjZP](https://github.com/BenjZP)
- Twitter - [@heybenjjj](https://www.twitter.com/heybenjjj)

## Acknowledgments


