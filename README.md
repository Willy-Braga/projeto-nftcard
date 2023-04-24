#  NFT Card  - Frontend Mentor 




## Table of contents

- [Visão Geral](#visão-geral)
  - [Screenshot](#screenshot)
- [Meu processo](#meu-processo)
  - [Como foi feito](#construído-com)
  - [ O que eu aprendi](#o-que-eu-aprendi)
  - [Evolução](#evolução)
  - [Recursos úteis](#recursos-úteis)
- [Autor](#autor)


## Visão geral

### Screenshot

![](./design/Design-desktop.png)


## Meu processo

### Construído com

- HTML5 Semântico
- CSS3 
- Flexbox

### O que eu aprendi

Com esse projeto consegui melhorar a centralização de itens, bem como a estilização de imagens, textos, assim como o uso do transition para realizar a transição da tela para a tela com o olho, no uso de variaveis assim facilitando a edição do conteúdo;


```css
.img-link::before{
    content: '';
    background-color: cyan;
    width: 100%;
    height: 100%;
    position: absolute;
    border-radius: 14px;
    opacity: 0;
    transition: 0.3s ease-in-out;
}

.img-link::after{
    content: '';
    background: url(../images/icon-view.svg) center center no-repeat;
    position: absolute;
    width: 100%;
    height: 100%;
    opacity: 0;
    transition: 0.4s ease-in-out;
}

.img-link:hover::before{
    opacity: 0.5;
}

.img-link:hover::after{
    opacity: 1;
}
```

### Evolução

Desejo focar mais na área Flex e Grid e na parte de transições do CSS para melhor estilização dos meus projetos, onde tenho certas dificuldades em centralizar os projetos;


### Recursos úteis

- [Resumo](https://angry-helicopter-3a6.notion.site/Resumos-DevQuest-d9c3dc80b08a4037a35ddb6d90355f0c) - Os meus resumos feitos com base no curso DEVQUEST me ajudaram bastante na criação desse projeto;

## Autor

- Github - [Willy-Braga](https://github.com/willy-braga)
- LinkedIn - [Willy Braga](https://www.linkedin.com/in/willy-braga-2861b3270/)
- Intragram - [@braga.wg](https://www.instagram.com/braga.wg/)

## Agradecimentos

Agradeço ao pessoal do curso [DEVQUEST](https://www.linkedin.com/school/devquest-dev-em-dobro/) por me ajudar na solução desse projeto tanto com as aulas do curso quanto com o video reforço sobre o projeto.

