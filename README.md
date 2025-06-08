# Sistema Solar Animado com CSS Puro

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Status](https://img.shields.io/badge/status-Concluído-success?style=for-the-badge)

Um projeto front-end que recria o Sistema Solar com planetas em órbita, utilizando exclusivamente **HTML e CSS**. O projeto foca no uso de animações CSS e seletores avançados para criar uma experiência dinâmica e interativa sem a necessidade de JavaScript.

**[➡️ Acesse a demonstração ao vivo aqui](https://gabriel-wav.github.io/Sistema-Solar/)**

---

## ✨ Funcionalidades Principais

* **Animação de Órbita Planetária**: Todos os planetas orbitam o Sol em trajetórias circulares.
* **Velocidades de Órbita Distintas**: Cada planeta possui uma duração de animação diferente, simulando as diferentes velocidades orbitais.
* **Menu Interativo de Informações (100% CSS)**: Um menu suspenso permite ao usuário clicar no nome de um planeta para exibir um card com informações e uma imagem, utilizando uma técnica de CSS puro, sem JavaScript.
* **Estrutura Aninhada**: O sistema é construído de forma lógica, com cada planeta posicionado dentro de seu próprio elemento de órbita.

---

## 🛠️ Técnicas de CSS em Destaque

Este projeto é um excelente case de estudo para as seguintes técnicas de CSS:

1.  **Animação com `@keyframes`**:
    * A animação de órbita é criada com uma regra `@keyframes` que rotaciona os elementos de `0deg` a `360deg`.
    * A propriedade `animation` é aplicada a cada `div` de órbita com uma `animation-duration` diferente, o que resulta nas distintas velocidades dos planetas.

2.  **Estrutura Orbital com `divs` Aninhados**:
    * O Sol é o elemento central. Cada planeta está contido em uma `div` que representa sua órbita.
    * As órbitas são círculos transparentes com `border-radius: 50%` e posicionados de forma absoluta em relação ao Sol. A animação é aplicada a essa `div` de órbita.

3.  **Interatividade sem JavaScript (Checkbox Hack)**:
    * O menu de informações funciona com uma técnica conhecida como "Checkbox Hack".
    * Cada item do menu é um `<label>` associado a um `<input type="checkbox">` oculto.
    * Quando o usuário clica no label, o checkbox é marcado.
    * O seletor de irmão adjacente (`~`) do CSS é usado para exibir o `div` de informações correspondente (`.toggle:checked ~ .info { display: block; }`).

---

## 🚀 Como Visualizar

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/gabriel-wav/Sistema-Solar.git](https://github.com/gabriel-wav/Sistema-Solar.git)
    ```
2.  **Navegue até a pasta do projeto:**
    ```bash
    cd Sistema-Solar
    ```
3.  **Abra o arquivo `index.html`** no seu navegador. Não é necessário nenhum servidor web.

---

## 👨‍💻 Autores

* **Gabriel Fernandes** - [@gabriel-wav](https://github.com/gabriel-wav)
* **Danilo Gutierre** - [@danilinhotj187](https://github.com/danilinhotj187)
* **Pedro Henrique** - [@pedroH901](https://github.com/pedroH901)
* **Antônio Ferreira** - [@Antoniojferreira3](https://github.com/Antoniojferreira3)
