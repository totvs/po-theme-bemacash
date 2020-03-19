# PO Theme - Totvs Bemacash Theme

Tema da Bemacash para aplicações desenvolvidas com [PO UI](http://po-ui.io).

### Como usar o tema

O **PO UI** possui o seu próprio tema, mas disponibilizamos um dos tema usados pela equipe do
[Bemacash][bemacash].

Para utilizá-lo, instale o pacote `@totvs/po-bemacash-theme` conforme abaixo:

```
npm i --save @totvs/po-bemacash-theme
```

Em seguida, atualize o arquivo `angular.json` para utilizar o tema.

```json
"styles": [
  "node_modules/@totvs/po-bemacash-theme/css/po-theme-custom.min.css"
]
```

> Leia mais sobre [como criar seu próprio tema customizado do PO UI][create-theme-customization].

[bemacash]: https://bemacash.com.br
[create-theme-customization]: https://po-ui.io/guides/create-theme-customization
