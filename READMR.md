# Check-Point 02 – Incremento Visual: Vinharia Agnello em Movimento 🍷✨

## 🧠 Descrição do Projeto
Este projeto consiste no desenvolvimento do portal web para a **Vinharia Agnello**. O objetivo principal é monitorar de forma inteligente variáveis críticas do ambiente (como luminosidade e temperatura) utilizando sistemas embarcados (IoT) para assegurar a preservação ideal e a qualidade dos vinhos finos armazenados em adegas.

## 👥 Integrantes
* **Gabriel Souza** - RM: (Seu RM) - Engenharia e Desenvolvimento de Sistemas (mixtapegbl)

## 📁 Estrutura do Projeto
* `index.html`: Página principal contendo as seções institucionais, apresentação da tecnologia e formulário de contato.
* `src/assets/imgs/`: Diretório reservado para o armazenamento de imagens e identidade visual do projeto.
* `src/css/style.css`: Folha de estilo base responsável pelo layout estrutural, cores corporativas e tipografia.
* `src/css/efeitos.css`: Arquivo focado nas interações dinâmicas, animações e efeitos visuais avançados do CP02.

## 🚀 Link do Projeto
* **Repositório GitHub:** [Inserir o link aqui]
* **GitHub Pages:** [Inserir o link aqui]

## 💫 Seção: Efeitos Visuais Adicionados (Check-Point 02)
Para atender às exigências de estilização e dinâmica do projeto, foram implementados os seguintes recursos no arquivo `efeitos.css`:

* **Pseudo-classes:**
  * `:hover`: Empregado nos links de navegação e botões para fornecer feedback de interatividade.
  * `:focus`: Aplicado aos campos de entrada de dados do formulário para destacar o campo ativo.
  * `:nth-child()`: Utilizado na listagem de cards de soluções para alternar estilizações de borda de forma automatizada.
* **Pseudo-elementos:**
  * `::before`: Insere um elemento decorativo (ícone temático) precedendo os títulos de seções principais do site.
  * `::selection`: Customiza a cor de fundo e do texto no momento em que o usuário seleciona textos na página.
* **Animações (@keyframes):**
  * `fadeInUp`: Animação responsável pelo surgimento suave (opacidade de 0 a 1) combinado com um leve deslocamento vertical ascendente do título principal na seção Hero.
* **Transformações:**
  * `scale()`: Altera a escala dos cards de serviço ao passar o mouse, gerando efeito de profundidade.
  * `translateY()`: Desloca sutilmente o botão de envio para cima quando o mouse passa sobre ele.
* **Transições:**
  * Propriedades de transição (`transition`) suaves configuradas com `0.3s ease-in-out` em todos os componentes clicáveis e interativos para evitar quebras bruscas visuais.
