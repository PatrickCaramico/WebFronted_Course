# Projeto 8: Dashboard

Este projeto é a implementação de um painel de controle (dashboard) web, com foco na organização e na apresentação de dados de forma clara e visualmente agradável. O layout principal utiliza CSS Grid para criar uma estrutura de duas colunas, ideal para dashboards, sistemas administrativos e portais internos.

---

### 🛠️ Tecnologias Utilizadas

-   **HTML5**: A estrutura do dashboard é construída com HTML semântico, organizando a navegação (`<nav>`), o cabeçalho (`<header>`) e o conteúdo principal (`<main>`) de maneira lógica.
-   **CSS3**: O projeto demonstra um uso avançado de CSS, com destaque para:
    -   **CSS Grid**: O principal motor do layout, permitindo a criação de uma estrutura de duas colunas (`grid-template-columns`) com facilidade, ideal para a barra de navegação lateral e o conteúdo principal.
    -   **Grid em Sub-componentes**: O conteúdo principal (`<main>`) também utiliza CSS Grid para organizar os cartões de resumo e os gráficos, demonstrando a capacidade de layouts aninhados.
    -   **Propriedades Customizadas (`--primary-color`, `--grey`)**: Para garantir consistência no tema e facilitar a manutenção do código.
    -   **Flexbox**: Utilizado para alinhar itens em componentes menores, como a barra de navegação superior (`.topnav`) e o bloco de resumo (`.summary`).
-   **SVG (Scalable Vector Graphics)**: Os ícones da barra de navegação são SVGs embutidos diretamente no HTML, o que garante escalabilidade, leveza e a possibilidade de estilização via CSS, como a mudança de cor.

---

### ✨ Destaques do Projeto

* **Layout com CSS Grid**: A implementação de um layout de duas colunas, que mantém a navegação lateral fixa (`position: sticky`), é um exemplo prático e eficiente de como usar o CSS Grid em um cenário real.
* **Design Clean e Funcional**: O estilo minimalista e o uso estratégico de cores e espaçamento tornam o dashboard intuitivo e fácil de ler, focando na usabilidade.
* **Flexibilidade do Grid**: O layout do `main` é adaptável. Ao usar `grid-column: span 2` para elementos de largura total e `grid-column: span 1` para elementos de meia largura, o código permite uma organização fluida do conteúdo.

---

### 🚀 Acesso e Execução

O projeto pode ser visualizado diretamente no navegador.

**1. Acesso Online:**
(https://8projeto-dashboard.netlify.app/)

**2. Acesso Local:**
Para rodar o projeto localmente, siga estes passos:

1.  Clone o repositório para sua máquina.
2.  Navegue até a pasta do projeto.
3.  Abra o arquivo `index.html` em seu navegador para começar.

---

### ✍️ Autor

-   **Patrick Souza**
    -   [GitHub](https://github.com/PatrickCaramico)
