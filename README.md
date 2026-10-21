# Guia Tapajós — Landing Page

Landing page responsiva do Guia Tapajós, baseada no briefing e na identidade visual fornecidos.

## Como abrir

Abra `index.html` no navegador, mantendo a pasta `assets` ao lado. Não há instalação nem build.

Para servir localmente:

```sh
python3 -m http.server 8000
```

## Conteúdo e interações

Hero, seis painéis de descoberta, busca, filtros, favoritos locais, fichas demonstrativas, sazonalidade, método de conferência, como funciona, FAQ e CTA final. Os painéis ficam fixos durante a rolagem em desktops com espaço suficiente e viram uma sequência no celular ou com movimento reduzido.

## Integrações

Esta versão é uma apresentação da plataforma. Ainda não inclui backend, cadastro de turistas ou contatos de fornecedores. Os CTAs levam à exploração demonstrativa; substitua-os pela URL da plataforma quando definida. Favoritos ficam apenas no armazenamento local do navegador. A fonte Manrope é carregada pelo Google Fonts.

## Imagens e marca

Marca fornecida pelo Guia Tapajós. Foram removidas margens transparentes, preservando as proporções.

Fotos de Alter do Chão:

- [JorgeFromBrazil — Alter do Chao, Estado do Para, Brazil](https://commons.wikimedia.org/wiki/File:Alter_do_Chao,_Estado_do_Para,_Brazil.jpg)
- [Richard N Horne — Alter do Chão Brazil The Beach](https://commons.wikimedia.org/wiki/File:Alter_do_Ch%C3%A3o_Brazil_The_Beach.jpg)

Ambas sob [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/), redimensionadas e enquadradas via CSS. Os derivados fotográficos permanecem sob a mesma licença. Créditos também disponíveis no rodapé.

## Verificação

JavaScript validado com `node --check`. Busca, filtros, favoritos persistentes, modal, menu mobile, sazonalidade e FAQ conferidos no navegador. Layout conferido em 375×812, 768×1024, 1280×800 e 1440×900, sem rolagem horizontal ou cortes nos painéis.
