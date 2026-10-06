# 📚 Biblioteca Digital UniFECAF

> Projeto acadêmico de desenvolvimento front-end autoral para a disciplina de **Design Web** do Centro Universitário UniFECAF.

---

## 📌 Sobre o Projeto

A **Biblioteca Digital UniFECAF** é uma interface web responsiva e acessível desenvolvida para facilitar o acesso de alunos e professores ao acervo acadêmico, livros em destaque e serviços prestados pela biblioteca institucional.

O projeto foi construído do zero utilizando HTML5 e CSS3 puros, seguindo as diretrizes de usabilidade, layout responsivo (*mobile-first*) e identidade visual da UniFECAF.

---

## 🎨 Identidade Visual e Design

* **Paleta de Cores Institucional:**
  * `Azul Escuro (#002244)`: Cabeçalho, rodapé e estrutura principal.
  * `Azul Médio (#004B93)`: Títulos de seções e elementos de suporte.
  * `Ciano (#00D2FF)`: Botões de ação (CTA) e destaques visuais.
  * `Cinza Claro (#F4F6F9)`: Fundo das seções alternadas para conforto visual.
* **Tipografia:** Fontes do sistema sans-serif (`Segoe UI`, `Roboto`) para leitura limpa e carregamento rápido.
* **Layout:** Estrutura organizada em cartões (*cards*), navegação por âncoras no menu fixo e grid adaptável sem rolagem lateral em dispositivos móveis.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação semântica do conteúdo (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`).
* **CSS3:** Estilização, variáveis de cor (`:root`), layouts modernos com **CSS Grid** e **Flexbox**, além de **Media Queries** para responsividade mobile.

---

## 📱 Responsividade e Acessibilidade

* Layout 100% responsivo ajustado para telas de computadores, tablets e smartphones.
* Ajuste de colunas dinâmico para evitar rolagem horizontal em dispositivos menores.
* Uso de atributos `alt` em imagens e estrutura de cabeçalhos hierárquicos (`<h1>` a `<h3>`) para acessibilidade.

---

## 📁 Estrutura de Arquivos

```text
biblioteca-unifecaf/
│
├── index.html                  # Página principal do projeto
├── README.md                   # Documentação do repositório
├── css/
│   └── style.css               # Estilização e responsividade
└── assets/
    └── imagens/                # Capas dos livros e recursos visuais