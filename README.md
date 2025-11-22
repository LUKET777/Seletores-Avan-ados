# 🎯 Selectors Mastery  
Projeto prático de estudo focado em **HTML + CSS**, desenvolvido para treinar e aplicar **seletores avançados**, pseudo-classes, pseudo-elementos e boas práticas de estrutura semântica.

Este projeto foi construído como parte do meu processo de evolução no Front-end, explorando recursos essenciais para escrever CSS mais inteligente, limpo e profissional.

---

## 🚀 Objetivo do Projeto
O objetivo principal deste projeto é treinar:

- Estruturação semântica com **HTML5**
- Seletores avançados:
  - Combinadores (`>`, `+`, `~`)
  - Seletores de atributo (`a[href^=]`, `a[href$=]`)
  - Pseudo-classes (`:hover`, `:nth-child()`, `:not()`, `:first-of-type`)
  - Pseudo-elementos (`::before`, `::after`)
- Criação de cards dinâmicos com hierarquia de seletores
- Transições e microinterações com hover e animações leves

---

## 🧠 Tecnologias Utilizadas
- **HTML5**
- **CSS3**
- Sem frameworks
- Metodologia focada em estrutura limpa e CSS moderno

---

## 📂 Estrutura do Projeto

/
├── index.html
├── style.css
└── README.md


---

## ✨ Funcionalidades de Estudo Presentes no Projeto

### ✔ Pseudo-elementos
Utilização de `::before` para inserir ícones decorativos nos cards.  
Cada card recebeu um ícone diferente utilizando `nth-child()`.

### ✔ Combinadores
Aplicados para estilizar elementos com precisão sem necessidade de muitas classes.

### ✔ Seletores de Atributo
Utilizados em botões e links:
```css
a[href="#"] { ... }
