# Stranger Things — The Experience

Landing page desenvolvida durante o curso **Dev Art**, do [Gustavo Campelo](https://www.instagram.com/_gustavocampelo/), com foco em animações avançadas com GSAP e design imersivo inspirado na série Stranger Things da Netflix.

## Sobre o projeto

O projeto consiste em uma landing page promocional para um evento temático da série, com foco em experiência visual e animações sofisticadas.

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- [GSAP](https://gsap.com/) — animações (ScrollTrigger, ScrollSmoother, SplitText)

## Funcionalidades

- Preloader animado com o logotipo em SVG
- Efeito parallax no hero com ScrollSmoother
- Animação de texto letra por letra com SplitText
- Cards com animação de entrada por scroll
- Efeito marquee (letreiro infinito) no footer e na seção de cidades

## Melhorias feitas após o curso

Ao revisar o projeto depois de finalizar o curso, identifiquei e corrigi problemas de responsividade que não foram abordados nas aulas:

- A seção de cidades exibia a lista cortada em telas de celular — o layout estático não cabia em telas pequenas
- Substituí a lista estática pelo efeito marquee nas resoluções abaixo de 1400px, aproveitando a mesma animação já existente no footer
- Ajustei o espaçamento entre os itens da lista nas resoluções maiores, que havia sumido após a reestruturação do HTML
