# ⌨️ TechKeyboards - Mechanical Keyboard Showcase

> *Uma interface imersiva para explorar o mundo dos teclados mecânicos.*

## 📖 Sobre o Projeto

O **TechKeyboards** é uma Landing Page interativa desenvolvida para apresentar diferentes tipos de switches e layouts de teclados mecânicos. O projeto foca em **Experiência do Usuário (UX)** visual, utilizando transições de elementos, manipulação do DOM e efeitos de iluminação via CSS.

A ideia central foi criar um ambiente que remete ao setup de um desenvolvedor ou gamer, utilizando uma paleta de cores "Dark Mode" com destaques em vermelho neon, seguindo a identidade visual do meu portfólio pessoal.

---

## 🚀 Tecnologias Utilizadas

-   **HTML5 Semântico:** Estrutura organizada e acessível.
-   **CSS3 Moderno:**
    -   Uso de **CSS Variables** (`:root`) para consistência de cores.
    -   **Glassmorphism** (Efeito de vidro) nos modais e botões.
    -   **Animações Keyframes** e Transições avançadas.
    -   **Z-Index Management** para controle de camadas visuais.
-   **JavaScript (Vanilla ES6+):**
    -   Lógica de Carrossel (Slider) sem frameworks.
    -   Manipulação de Classes para estados ativos.
    -   Sistema de **Modais Dinâmicos** para detalhes técnicos.

---

## ✨ Funcionalidades Destacadas

### 1. Slider Interativo com "Fade-In" em Cascata
Ao trocar de slide, os elementos (título, descrição, botão) não aparecem todos de uma vez. Foi implementado um `transition-delay` em cascata para criar uma sensação de fluidez e elegância na entrada das informações.

### 2. Botão com Resposta Instantânea (Instant Hover)
Diferente das transições suaves do resto do site, o botão de ação ("Saiba Mais") foi programado para ter uma resposta **instantânea** ao passar o mouse (`transition: none !important`). Isso cria uma sensação de agilidade e "clique tátil", similar a um switch de teclado mecânico.

### 3. Modais de Detalhes Técnicos
Cada teclado possui um modal oculto que é ativado via JavaScript, trazendo especificações técnicas reais (Força de atuação, tipo de switch, etc), mantendo o usuário na mesma página sem recarregamentos.

---

## 🧠 Aprendizados e Desafios

Durante o desenvolvimento do **TechKeyboards**, foquei em resolver desafios como:

* **Gerenciamento de Clique (Pointer Events):** Utilizei `pointer-events: none` nos itens inativos do slider para garantir que botões invisíveis não bloqueassem o clique do usuário.
* **Sincronia de Animações:** Ajustar o tempo das transições para que a imagem do teclado rotacionasse ao mesmo tempo que o texto entrava na tela.
* **Identidade Visual:** Adaptação completa do tema para utilizar variáveis globais, facilitando a manutenção futura das cores do projeto.

---

## 🔧 Como Executar

1.  Clone este repositório:
    ```bash
    git clone [https://github.com/SEU-USUARIO/techkeyboards.git](https://github.com/SEU-USUARIO/techkeyboards.git)
    ```
2.  Abra o arquivo `index.html` no seu navegador preferido.

---

## 📂 Estrutura de Pastas

```bash
/
├── img/             # Imagens dos teclados (PNG com fundo transparente)
├── index.html       # Estrutura principal
├── styles.css       # Estilização global e animações
├── scripts.js       # Lógica do slider e modais
└── README.md        # Documentação
