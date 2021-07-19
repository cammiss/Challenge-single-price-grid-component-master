

# Frontend Mentor - Single price grid component solution

Essa é uma solução do desafio [Single price grid component](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges te ajudar a melhorar suas habilidades de código construindo projetos reais. 

## Tópicos

- [Overview](#overview)
  - [Desafio](#desafio)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [Meu processo](#meu-processo)
  - [Contruído com](#contruído-com)
  - [O que aprendi](#o-que-aprendi)
  - [Continuando o desenvolvimento](#continuando-o-desenvolvimento)
  - [Fontes úteis](#fontes-uteis)
- [Autor](#autor)
- [Aprendizados](#aprendizados)

## Overview

### Desafio

Usuários poderão:

- Visualização do layout em diferentes dispositivos

### Screenshot

![web](C:\Users\rafae\OneDrive\Área de Trabalho\Workspace\single-price-grid-component-master\single-price-grid-component-master\Nova pasta\design-png\web.png)

### Links

- Solution URL: [Frontend Mentor | Single Price Grid Component](file:///C:/Users/rafae/OneDrive/%C3%81rea%20de%20Trabalho/Workspace/single-price-grid-component-master/single-price-grid-component-master/Nova%20pasta/index.html)

## Meu processo

### Contruído com

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### O que aprendi

Neste projeto, pude entender melhor como a semântica do HTML5 trabalha e quanto esse conhecimento me auxiliou durante a construção do código CSS.

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
Escrevendo o CSS code, deparei com dificuldades nas propriedades de alinhamento o que levou um tempo para resolvê-las. Não pude resolver apenas aplicando a propriedade ‘justify-content’ que tem a função de alinhar itens verticalmente. Após pesquisas e leituras, tomei a decisão de aplicar as propriedades ‘padding-top’ e ‘padding-botton' para alinhar os elementos ao centro.

```css
.body {
    background-color: hsl(215, 100%, 93%);
    width: 100%;
    min-height: 493px;
    justify-content: center;
    padding-bottom: 10%;
    padding-top: 10%;
```
### Continuando o desenvolvimento

Como próximo passo, continuarei focando em refinar elementos alinhados nos quais tive dificuldade. Co mais pesquisas e estudos, o código ficará perfeito.

### Fontes úteis

- [O que é CSS? Guia Básico para Iniciantes](https://www.hostinger.com.br/tutoriais/o-que-e-css-guia-basico-de-css) - Me auxiliou a entender propriedades de CSS. É um ótimo blog e continuarei consumindo seus conteúdos.
- [HTML Web Developer](https://web.digitalinnovation.one/track/html-web-developer) - A Dio é uma excelente plataforma de educação que foi responsável pela minha intrudução ao desenvolvimento. Recomendo para aqueles que estão iniciando seus estudos.

## Autor

- Linkedin - [Camila Monteiro](https://www.linkedin.com/in/camila-monteiro-36ba9b93/)
- Github - [cammiss](https://github.com/cammiss)

## Aprendizados

Estou verdadeiramente feliz ao completar este desafio. Escrevi os códigos, porém não posso dizer que cheguei até aqui sozinha. Sou grata às plataformas DIO e Frontend Mentor, que trazem tando aprendizados e inspiração à desenvolvedores.