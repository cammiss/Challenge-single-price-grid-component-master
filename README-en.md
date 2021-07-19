

# ​Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size

### Screenshot

![web](C:\Users\rafae\OneDrive\Área de Trabalho\Workspace\single-price-grid-component-master\single-price-grid-component-master\challenge-single-price-grid-component-master\design-png\web.png)

### Links

- Solution URL: [Frontend Mentor | Single Price Grid Component](file:///C:/Users/rafae/OneDrive/%C3%81rea%20de%20Trabalho/Workspace/single-price-grid-component-master/single-price-grid-component-master/Nova%20pasta/index.html)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

In this project, I was able to understand better how HTML5’s semantics works and how it helped while writing the CSS code. 

```html
  <header class="body-header">
    <section class="container-header">
      <h1 class="header-title">Join our community</h1>
      <h2 class="header-subtitle">30-day, hassle-free money back guarantee</h2>
      <p class="header-paragraph">Gain access to our full library of tutorials along with expert code reviews.</p>
      <p class="header-paragraph">Perfect for any developers who are serious about honing their skills.</p>
    </section>
  </header>
```
While writing CSS code, I faced an align’s properties problem that took me time to resolve. I couldn’t resolve this just using the property ‘justify-content’ which align items vertically. After researching and reading, I applied ‘padding-top’ and ‘padding-botton' properties to have the element aligned to center.

```css
.body {
    background-color: hsl(215, 100%, 93%);
    width: 100%;
    min-height: 493px;
    justify-content: center;
    padding-bottom: 10%;
    padding-top: 10%;
```
### Continued development

As a next step, I will continue focusing on refining the align items property’s issue. Researching and studying more, the code will be better and perfect.

### Useful resources

- [O que é CSS? Guia Básico para Iniciantes](https://www.hostinger.com.br/tutoriais/o-que-e-css-guia-basico-de-css) - This helped me understand CSS properties. It is a great blog and I will read it going forward.
- [HTML Web Developer](https://web.digitalinnovation.one/track/html-web-developer) - This is an amazing teaching platform which introduced me to development. I'd recommend it to anyone who is beginning.

## Author

- Linkedin - [Camila Monteiro](https://www.linkedin.com/in/camila-monteiro-36ba9b93/)
- Github - [cammiss](https://github.com/cammiss)

## Acknowledgments

I am truly happy to complete this challenge. I code it by myself, however I can say I got here alone. I am grateful to DIO teaching and Frontend Mentor platforms, which brings so much learning and inspiration to developments.