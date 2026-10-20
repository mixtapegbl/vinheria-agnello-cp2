# Vinheria Agnello - Check-Point 02

## Descrição do Projeto
A Vinheria Agnello é uma marca tradicional de vinicultura familiar que une a preservação de sua herança secular com a inovação tecnológica. Este portal web foi desenvolvido para refletir a essência artesanal da marca, cobrindo desde o cultivo nos vinhedos até o engarrafamento. Para garantir a máxima qualidade no repouso dos vinhos finos na Câmara de Armazenamento Principal, o projeto integra de forma conceitual a arquitetura microcontrolada do Arduino Uno com sensores de luminosidade e temperatura ambiente, criando uma adega verdadeiramente inteligente capaz de mitigar variações climáticas.

## Estrutura do Projeto
O repositório está organizado de forma modular seguindo a estrutura padrão de diretórios:
- index.html: Página principal e institucional da Vinheria Agnello.
- src/assets/imgs/: Diretório que armazena todas as imagens físicas utilizadas no portal (colheita, barris de carvalho e o protótipo do Arduino).
- src/css/style.css: Arquivo de estilização global estruturado de forma moderna a partir de variáveis centralizadas no escopo :root.
- src/css/efeitos.css: Arquivo exclusivo contendo as animações, transformações e pseudo-elementos visuais adicionados neste incremento.

## Efeitos Visuais
O projeto foi aprimorado com recursos visuais sofisticados através do arquivo efeitos.css para garantir interações fluidas e táteis alinhadas à sofisticação da marca:
- Pseudo-classes aplicadas:
  - :hover: Utilizado nos links do menu de navegação e nos botões principais para fornecer uma resposta visual gradativa e suave ao usuário.
  - :focus: Aplicado aos campos de entrada do formulário para destacar o campo selecionado através de uma borda bordô evidente e sombreamento dinâmico.
  - :nth-child(): Usado na listagem de blocos informativos (cards) para alternar as cores de borda lateral de forma dinâmica entre os elementos pares e ímpares da estrutura.
- Pseudo-elementos aplicados:
  - ::after: Utilizado para gerar de forma automatizada uma linha decorativa refinada em tom dourado cortiça logo abaixo dos títulos principais das seções.
  - ::selection: Customizado para substituir a cor padrão de destaque de texto do navegador pelas cores oficiais bordô da Vinharia Agnello.
- Animações e Movimentos (@keyframes):
  - @keyframes elegantFade: Animação suave combinada com curvas de transição profissionais (cubic-bezier) que faz com que o conteúdo de texto do banner principal surja de baixo para cima com efeito de opacidade assim que a página é carregada.
- Transformações CSS:
  - scale(): Aplicado aos blocos informativos (cards) e elementos visuais para criar um efeito de aproximação imersiva ao passar o mouse.
  - translateY(): Usado para elevar levemente a posição dos botões de envio ao interagir, simulando um efeito físico de flutuação.
  - rotate(): Uma micro-rotação decorativa inserida na seção de destaque tecnológico da adega inteligente ao interagir com o elemento visual do Arduino.

## Integrantes do Grupo
- Gabriel Souza - Líder do Projeto (Grupo Mixtape)

## Links do Projeto
- Repositório no GitHub: https://github.com/mixtapegbl/vinheria-agnello-cp2
- Site publicado no GitHub Pages: https://github.io
