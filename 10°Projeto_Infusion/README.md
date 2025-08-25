# Projeto 10: Infusion

Este projeto é a implementação de uma landing page completa para uma empresa fictícia, "Infusion". O site é um tema de negócios moderno e demonstra um alto nível de conhecimento em HTML, CSS e JavaScript, com foco em modularidade e interatividade.

---

### 🛠️ Tecnologias Utilizadas

* **HTML5**: A estrutura da página é bem organizada e semântica. A página utiliza a classe `.no-js` no `<body>`, que é removida pelo JavaScript. Isso é uma prática de **progressão aprimorada (progressive enhancement)**, garantindo que o site seja funcional mesmo para usuários com JavaScript desativado.
* **CSS3**: O design utiliza uma abordagem modular, com convenções de nomenclatura de classes (como `people-cards__card` e `hero__title`) para manter a estilização organizada e escalável.
* **JavaScript (ES5)**: O projeto emprega JavaScript puro para criar funcionalidades dinâmicas. O código é bem estruturado em módulos separados (`menu.js`, `carousel.js`, `main.js`), o que facilita a manutenção e a reutilização.
* **CSS Grid**: A seção de artigos recentes (`last-articles__thumbs`) e o layout do rodapé (`footer`) utilizam CSS Grid para criar layouts responsivos e complexos de forma eficiente.
* **Flexbox**: Utilizado em diversas partes do layout, como na navegação do cabeçalho em telas maiores, para alinhar e distribuir itens.
* **Font Awesome**: Biblioteca de ícones externos, usada para o ícone do menu "hamburguer" e os botões de navegação dos carrosséis.

---

### ✨ Destaques do Projeto

* **Modularização com JavaScript**: A principal inovação do projeto é o uso de classes em JavaScript (`Menu` e `Carousel`) para encapsular lógicas específicas.
    * **`main.js`**: Atua como o "controlador" principal, inicializando as classes e passando as configurações necessárias para cada componente, como o menu e os dois carrosséis.
    * **`menu.js`**: Controla a navegação retrátil. O código gerencia a visibilidade do menu "hamburguer" em diferentes tamanhos de tela e as transições de abertura e fechamento, mostrando um alto nível de controle sobre a interface do usuário.
    * **`carousel.js`**: Uma classe genérica de carrossel, reutilizada para a seção de imagens de laptop e para os depoimentos. Isso demonstra uma excelente prática de **reutilização de código**, onde a mesma lógica pode ser aplicada a diferentes elementos HTML.
* **Design Responsivo Dinâmico**: O site se adapta a diferentes tamanhos de tela. O menu "hamburguer" é controlado por JavaScript, garantindo uma transição suave entre a navegação mobile e desktop. Os carrosséis e galerias também ajustam seu layout dinamicamente.
* **Conteúdo Interativo**: O projeto apresenta dois carrosséis dinâmicos: um para imagens de laptop e outro para depoimentos (`quotes`), o que melhora a forma como o conteúdo é apresentado e engaja o usuário.

---

### 🚀 Acesso e Execução

O projeto pode ser visualizado diretamente no navegador.

**1. Acesso Online:**
(https://10projeto-infusion.netlify.app/)

**2. Acesso Local:**
Para rodar o projeto localmente, siga estes passos:

1.  Clone o repositório para sua máquina.
2.  Navegue até a pasta do projeto.
3.  Abra o arquivo `index.html` em seu navegador para começar.

---

### ✍️ Autor

* **Patrick Souza**
    * [GitHub](https://github.com/PatrickCaramico)
