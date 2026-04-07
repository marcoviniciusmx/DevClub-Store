<h1 align="center">Tech Store</h1>

<p align="center">
  Landing page interativa desenvolvida para apresentação de produtos de tecnologia, com foco em experiência visual, transições suaves e destaque para itens em formato de vitrine digital.
</p>

<p align="center">
  <a href="#-about-the-project">Sobre o projeto</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#-features">Funcionalidades</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#-technologies">Tecnologias</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#-project-structure">Estrutura</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#-layout-and-design-decisions">Layout e decisões de design</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#-getting-started">Como executar</a>
</p>

<br>

<img src="./img/Mockup - TechStory.png" alt="Mockup TechStory" width="100%">
---

## 🏠 About the project

Este projeto foi desenvolvido como uma landing page para exibição de produtos tecnológicos, com proposta visual moderna e foco em apresentação de itens de forma impactante e dinâmica.

A página funciona como uma espécie de **showcase interativo**, permitindo alternar entre diferentes produtos com botões de navegação laterais, indicadores visuais e troca automática de destaque em intervalos de tempo. O objetivo principal é valorizar os produtos por meio de uma interface mais premium e envolvente.

Durante o desenvolvimento, foram trabalhados conceitos importantes de estruturação visual, manipulação do DOM, controle de estado simples, animações com CSS e atualização dinâmica dos elementos ativos da interface.

---

## 🧰 Features

- Header fixo com logo e navegação
- Vitrine principal de produtos tech
- Estrutura em formato de carrossel
- Alternância manual entre produtos
- Alternância automática a cada 5 segundos
- Indicador numérico do item ativo
- Indicadores visuais por dots
- Destaque visual do produto selecionado
- Animações de entrada e saída entre slides
- CTA “Saiba Mais” em cada produto
- Elementos decorativos com círculos futuristas
- Interface visual com pegada premium e tecnológica

---

## 💻 Technologies

Este projeto foi desenvolvido com as seguintes tecnologias:

- HTML5
- CSS3
- JavaScript
- Google Fonts
- Manipulação do DOM
- Animações e transições com CSS

---

## 👷 Project structure

A estrutura principal do projeto está organizada em blocos como:

- Header
- Navegação
- Área principal de vitrine
- Lista de produtos
- Botões de navegação
- Indicadores visuais

Arquivos principais do projeto:

- `index.html`
- `style.css`
- `scripts.js`
- `img/` para imagens dos produtos

---

## 🎨 Layout and design decisions

O projeto utiliza uma identidade visual com estética futurista, baseada em fundo escuro, azul neon e tipografia com aparência tecnológica. Essa combinação é coerente com a proposta de uma vitrine digital de produtos premium.

Alguns pontos de destaque no layout:

- fundo escuro com gradiente para dar profundidade
- uso de azul neon para reforçar sensação tecnológica
- tipografia `Orbitron` para títulos com aparência futurista
- animações de entrada para imagens, títulos, descrições e botões
- indicadores visuais que reforçam a noção de navegação entre produtos
- composição centralizada para destacar os itens em tela
- elementos circulares decorativos para enriquecer o cenário visual

---

## ⚙️ Functional rules

A lógica principal da aplicação funciona assim:

- apenas um produto fica ativo por vez
- ao clicar nas setas, o item ativo muda para o anterior ou para o próximo
- ao chegar no último item, a navegação volta para o primeiro
- ao voltar antes do primeiro item, a navegação vai para o último
- os dots acompanham visualmente o slide ativo
- o número exibido também é atualizado conforme o item atual
- existe uma rotação automática a cada 5 segundos

---

## 🛍️ Products showcased

Os produtos apresentados atualmente na vitrine são:

- Apple Watch Serie 13
- Air Pod Max
- Vision Pro

---

## 🔰 Getting Started

### Prerequisites

Antes de começar, você vai precisar ter instalado:

- Git
- Um navegador de sua preferência

---

### Clone the repository

```bash id="f3b8wn"
git clone https://github.com/seu-usuario/tech-store.git
