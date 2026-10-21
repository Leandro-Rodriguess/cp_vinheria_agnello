# Vinheria Agnello

Projeto de um site institucional para a **Vinheria Agnello**, desenvolvido como parte do **CP2 da FIAP**, dando continuidade ao projeto do CP1 com a inclusão de efeitos visuais em CSS.

## Descrição do caso da Vinheria Agnello

A Vinheria Agnello é uma empresa tradicional do ramo de vinhos, com mais de 15 anos de atuação e uma loja física em São Paulo. A empresa se destaca pelo atendimento personalizado, oferecendo aos clientes orientações sobre diferentes tipos de vinhos, uvas, regiões produtoras e harmonizações.

Com a evolução do mercado e o aumento das compras pela internet, a Vinheria Agnello passou a considerar a criação de um canal de vendas online. O principal desafio do caso é levar para o ambiente digital a experiência e o atendimento personalizado que já fazem parte da identidade da empresa.

## Sobre o projeto

O site apresenta a Vinheria Agnello e informações sobre o mundo dos vinhos. Nesta etapa, o projeto recebe efeitos visuais com pseudo-classes, pseudo-elementos, animações, transições e transformações em CSS.

## Estrutura do projeto

O projeto é composto por cinco páginas principais, desenvolvidas em HTML e estilizadas com CSS.

### Página Inicial — index.html

Apresenta a Vinheria Agnello, sua proposta e seus principais diferenciais. Contém informações sobre a empresa, os tipos de vinhos, suas características e harmonizações, além de um vídeo, um link externo para o Wine Spectator e um formulário para contato.

### Nossa História — historia.html

Apresenta a história da Vinheria Agnello desde sua fundação em 2011 pelo Sr. Giulio. Aborda a trajetória da empresa durante a pandemia e sua posterior modernização com a participação de Bianca. Também possui uma linha do tempo, informações sobre a equipe, uma explicação sobre ERP, vídeo e formulário de contato.

### Vinhos — vinhos.html

Apresenta os principais tipos de vinhos oferecidos pela Vinheria Agnello: tinto, branco, rosé e espumante. Destaca suas características e harmonizações, além de incluir imagens, uma tabela comparativa e um vídeo sobre como escolher o vinho ideal.

### Uvas — uvas.html

Apresenta informações sobre variedades de uvas utilizadas na produção de vinhos, como Cabernet Sauvignon, Pinot Noir, Chardonnay, Sauvignon Blanc, Malbec e Merlot. Inclui uma tabela comparativa, dicas para escolher a uva ou o vinho ideal e um vídeo explicativo.

### Armazenamento — armazenamento.html

Apresenta os cuidados necessários para armazenar, conservar e transportar vinhos. Inclui orientações para os consumidores, uma tabela com temperaturas e cuidados recomendados, uma imagem do estoque e um vídeo explicativo.

## Organização dos arquivos

- `index.html`: página inicial.
- `pages/`: páginas internas do site.
- `pages/historia.html`: história da Vinheria Agnello.
- `pages/vinhos.html`: tipos de vinhos.
- `pages/uvas.html`: tipos e características das uvas.
- `pages/armazenamento.html`: armazenamento e conservação dos vinhos.
- `CSS/`: arquivos de estilização das páginas.
- `CSS/efeitos.css`: efeitos visuais em CSS.
- `img/`: imagens utilizadas no projeto.

## Tecnologias utilizadas

- HTML5
- CSS3

## Efeitos Visuais

### Página de Vinhos

Os efeitos da página de Vinhos estão definidos no arquivo `CSS/efeitos.css`, com seletores que utilizam a classe `.pagina-vinhos`.

- **Pseudo-classes:** `:hover` para efeitos ao passar o mouse, `:focus` para destacar links em foco e `:first-child` para destacar o primeiro item do menu.
- **Pseudo-elementos:** `::before` para adicionar uma taça antes dos nomes dos vinhos e `::after` para criar uma linha decorativa abaixo deles.
- **Animação:** `@keyframes aparecerVinhos` para fazer o conteúdo principal aparecer gradualmente.
- **Transições:** mudanças suaves na cor dos links e nas transformações das imagens e dos produtos.
- **Transformações:** `scale()` para aumentar levemente as imagens e `translateY()` para mover os produtos para cima ao passar o mouse.

## Links

- [Repositório no GitHub](https://github.com/Leandro-Rodriguess/cp_vinheria_agnello)
- [Wine Spectator](https://www.winespectator.com/)

## Projeto publicado

[Acesse o site da Vinheria Agnello](https://leandro-rodriguess.github.io/cp_vinheria_agnello/)

## Objetivo acadêmico

Este projeto foi desenvolvido no **1º semestre da FIAP**, como parte do **CP2**, com foco na aplicação de pseudo-classes, pseudo-elementos, animações, transições e transformações em CSS.

## Autores

- Leandro Rodrigues Barbosa
- Eduardo Miranda Mororo
- Victor krause Esteves
- Henrrique Nascimento

FIAP — CP2 | 2026
