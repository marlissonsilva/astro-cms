---
layout: ../../layouts/BlogPost.astro
title: O básico de HTML
description: Veja tags básicas do HTML
publishDate: 2023-10-13T09:54:25.459Z
heroImage: /assets/unnamed.png
---
Os **elementos HTML** **`<h1>`–`<h6>`** representam seis níveis de título de seção. `<h1>` é o nível de seção mais alto e `<h6>` é o mais baixo.

## [Experimente](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/Heading_Elements#experimente)

[MDN Web Docs Interactive Exampl](https://interactive-examples.mdn.mozilla.net/pages/tabbed/h1-h6.html)

Elementos de **cabeçalho** são implementados em seis níveis, `<h1>` é o mais importante e `<h6>` é o de menor importância. Um elemento de cabeçalho descreve brevemente o tópico da seção em que ele está. As informações de cabeçalho podem ser usadas por agentes de usuário, por exemplo, para construir uma tabela de conteúdos para um documento automaticamente.

* *[Categorias do conteúdo](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Content_categories)* [Conteúdos de fluxo](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Content_categories#flow_content), conteúdos de cabeçalho, conteúdos palpáveis.
* *Conteúdo permitido* [Conteúdo com texto](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Content_categories#phrasing_content).
* *Omissão de tag* Não há, porém, as tags de abertura e fechamento são obrigatórias.
* *Elementos pais permitidos* Qualquer elemento que aceite [conteúdos de fluxo](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Content_categories#flow_content); ou como um elemento filho do grupo de elementos de cabeçalho [`<hgroup>`](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/hgroup)
* *Interface DOM* [`HTMLHeadingElement` (en-US)](https://developer.mozilla.org/en-US/docs/Web/API/HTMLHeadingElement "Currently only available in English (US)")

## [Atributos](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/Heading_Elements#atributos)

Esses elementos incluem os [atributos globais](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Global_attributes).

O atributo **align** está Deprecated no HTML 4 e no HTML 5.

## [Exemplos](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/Heading_Elements#exemplos)

### [Todos os cabeçalhos](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/Heading_Elements#todos_os_cabe%C3%A7alhos)

O seguinte código mostra, em uso, todos os níveis de cabeçalho.

```
<h1>Cabeçalho nível 1</h1>
<h2>Cabeçalho nível 2</h2>
<h3>Cabeçalho nível 3</h3>
<h4>Cabeçalho nível 4</h4>
<h5>Cabeçalho nível 5</h5>
<h6>Cabeçalho nível 6</h6>
```