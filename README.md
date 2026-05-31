# 📝 Minhas Tarefas por Dia

<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
</p>

> 🚀 **Gerencie sua rotina:** O aplicativo está publicado e pronto para rodar direto no navegador! [Clique aqui para acessar o app](https://pernisa2.github.io/tarefas-do-dia/)

---

## 📝 Sobre o Projeto

O **Minhas Tarefas por Dia** é uma aplicação web completa (Single Page Application) que permite ao usuário gerenciar listas de tarefas específicas para cada dia da semana. O grande diferencial deste projeto é que os dados não somem ao atualizar a página, pois ele utiliza o armazenamento nativo do navegador para manter a rotina salva. 

Além disso, o app conta com uma ferramenta inteligente que renderiza a interface em um elemento canvas para permitir o download da lista em formato de imagem (PNG).

## 🚀 Principais Funcionalidades

*   **Filtro por Dia da Semana:** Organização isolada de tarefas de Segunda a Domingo.
*   **CRUD Completo:** Criação, leitura, edição e exclusão de tarefas de forma dinâmica na interface.
*   **Persistência de Dados (`LocalStorage`):** Os dados são convertidos em JSON e salvos diretamente no navegador do usuário.
*   **Exportação em PNG:** Integração com a biblioteca externa `html2canvas` para baixar uma captura de tela da lista.
*   **Design Responsivo:** Layout totalmente adaptável para telas de computadores e smartphones (Mobile Friendly).

## 📂 Código Fonte e Estrutura

O projeto foi construído em formato unificado em um arquivo principal, otimizando o carregamento e a execução:
*   `index.html`: Contém a marcação semântica da interface (inputs, seletores e listas).
*   **CSS3 Integrado (`<style>`)**: Estilização moderna utilizando variáveis globais (`:root`), layouts em Grid/Flexbox e animações sutis de interação nos botões.
*   **JavaScript Inteligente (`<script>`)**: Lógica responsável pela manipulação do DOM, escuta de eventos (como a tecla `Enter`), validação de campos vazios e gerenciamento dos estados das tarefas.

## 🕹️ Como Executar o Projeto

Para testar o aplicativo diretamente no navegador:

1. Acesse o link oficial clicando [aqui](https://pernisa2.github.io/tarefas-do-dia/).
2. O aplicativo abrirá imediatamente, pronto para uso!

*Se preferir rodar localmente:*
1. Faça o download ou clone este repositório.
2. Dê um duplo clique no arquivo `index.html`.

## 🛠️ Tecnologias Utilizadas

*   **HTML5:** Estruturação estrutural e acessibilidade básica da aplicação.
*   **CSS3:** Layout moderno com CSS Grid, Flexbox, efeitos de `hover`/`active` e responsividade via `@media`.
*   **JavaScript (ES6):** Manipulação de arrays, métodos de filtragem (`filter`), tratamento de JSON e persistência de dados com `localStorage`.
*   **html2canvas (via CDN):** Biblioteca externa em JavaScript para captura e conversão de elementos HTML em imagens PNG.

---

## 🧑‍💻 Desenvolvedor

*   **GitHub:** [@pernisa2](https://github.com/pernisa2)
