# Landing Page — estilo Tron

Modelo de landing page num arquivo só, o [`index.html`](index.html): HTML, CSS e JavaScript puro, sem build e sem bibliotecas. A única dependência externa são as fontes do Google Fonts (Exo 2 e Share Tech Mono).

## Visual

- Fundo quase preto, com horizonte brilhando, chão em grade com perspectiva que avança e "motos de luz" deixando rastro.
- Ciano como única cor de luz. O laranja fica reservado para alertas.
- Títulos finos, em maiúsculas e com letras espaçadas. Números e rótulos usam fonte de terminal.
- Cantos retos, botões com canto chanfrado e painéis com cantoneiras de luz.

## Como usar

1. Abra o `index.html` no navegador para ver o modelo.
2. Troque os textos das seções (menu, abertura, números, recursos, contato e rodapé). Apague as que não precisar.
3. Para publicar, use qualquer hospedagem estática: GitHub Pages, Netlify ou outra.

As instruções completas estão no comentário do topo do `index.html`:

- o que define o estilo;
- como trocar a cor principal e as fontes;
- como ajustar ou desligar a animação;
- a lista de componentes (`.btn`, `.panel`, `.stat`, `.card`, `.disc`, `.pill`, `.sect`, `.field`, `.win-bar`);
- cuidados de contraste, acessibilidade e celular.

## Acessibilidade

- Com "reduzir movimento" ativado no sistema, o fundo fica parado.
- Tudo que é clicável tem contorno de foco visível.
- Abaixo de 760 px de largura, as grades viram uma coluna.
