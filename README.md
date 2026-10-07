# 🍰 Portal Gastronómico — Réplica TudoGostoso

<p align="center">

  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">

  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">

  <img src="https://img.shields.io/badge/Lato-Font-0088CC?style=for-the-badge" alt="Lato Font">

</p>

## 🌐 Demonstração Online

<p align="center">

  <a href="https://projeto-tudogostoso.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/Ver%20Projeto-Online-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Ver projeto online na Vercel">
  </a>

</p>

<p align="center">
  <strong>🔗 https://projeto-tudogostoso.vercel.app/</strong>
</p>

## 📌 Sobre o Projeto

Este projeto é uma aplicação **front-end estática** inspirada na estrutura visual de portais de receitas como o **TudoGostoso**.

Desenvolvido a partir de desafios práticos de estilização da plataforma **ProgramadorBR**, o projeto apresenta uma página dedicada à receita de **Bolo de Fubá com Goiabada**, organizando ingredientes, modo de preparo e informações complementares em uma interface visualmente estruturada.

O principal objetivo é praticar a construção de layouts utilizando **HTML5 e CSS3**, explorando organização por cartões, imagens, tipografia, posicionamento de elementos, efeitos de interação e estruturação semântica de conteúdos.

> **Nota:** o projeto é uma recriação para fins educacionais e não possui qualquer afiliação oficial com o portal TudoGostoso.

---

## 🛠️ Detalhes Técnicos

### 🃏 Layout Baseado em Cartões

O conteúdo da receita é dividido em blocos independentes através da classe `.cartao`.

Os cartões utilizam propriedades como:

- `padding` para criar espaçamento interno;
- `border-radius` para criar cantos arredondados;
- margens para separar visualmente as diferentes secções;
- sombras para criar contraste entre os componentes e o fundo.

Esta organização facilita a leitura e cria uma hierarquia visual clara.

### 🖱️ Cursores Personalizados

O projeto utiliza a propriedade `cursor` do CSS para personalizar o ponteiro do rato em determinadas secções.

Exemplo:

```css
cursor: url(...);
```

Diferentes áreas da página podem apresentar cursores temáticos relacionados com o conteúdo apresentado.

Este recurso funciona como um detalhe visual adicional e demonstra a possibilidade de personalizar elementos da interface através de CSS.

### ✨ Estados de Interação

Foram utilizados seletores como `:hover` para criar feedback visual durante a interação do utilizador.

A combinação de sombras e alterações visuais permite destacar elementos quando o cursor passa sobre eles.

Exemplo:

```css
.elemento:hover {
   /* alterações visuais */
}
```

### 🖼️ Banner de Destaque

O cabeçalho da página utiliza uma imagem de destaque através de `background-image`.

A imagem é adaptada ao espaço disponível através de:

```css
background-size: cover;
background-position: center;
```

O uso de `cover` permite preencher a área definida mantendo a proporção da imagem.

### 🧩 Posicionamento de Elementos

As imagens associadas aos ingredientes são posicionadas em conjunto com os respetivos textos, utilizando propriedades como `position: relative` para controlar o posicionamento dentro dos componentes.

---

## 📐 Estrutura e Semântica

A estrutura HTML foi organizada de acordo com a natureza do conteúdo apresentado.

### 🥣 Lista de Ingredientes

Os ingredientes são apresentados através de uma lista não ordenada:

```html
<ul>
   <li>...</li>
   <li>...</li>
</ul>
```

O elemento `<ul>` é adequado porque os ingredientes não dependem de uma ordem específica.

### 👨‍🍳 Modo de Preparo

O modo de preparo utiliza uma lista ordenada:

```html
<ol>
   <li>...</li>
   <li>...</li>
</ol>
```

Neste caso, a ordem dos passos é relevante para a execução da receita, tornando `<ol>` semanticamente apropriado.

### 🎨 Identidade Visual

A cor laranja `#ff6b28` é utilizada como elemento principal da identidade visual da página.

A mesma cor é aplicada em diferentes componentes, como:

- barra de navegação;
- títulos;
- botões;
- elementos de destaque;
- rodapé.

A utilização consistente da paleta ajuda a criar uma identidade visual uniforme.

---

## 💻 Como Executar o Projeto Localmente

Por ser uma aplicação web estática desenvolvida com HTML e CSS, não é necessário instalar dependências ou configurar ferramentas adicionais.

### 1. Clonar o repositório

```bash
git clone https://github.com/SEU-USUARIO/projeto-tudogostoso.git
```

### 2. Aceder ao diretório

```bash
cd projeto-tudogostoso
```

### 3. Executar no navegador

Abra o ficheiro `index.html` diretamente num navegador moderno.

Como alternativa, pode utilizar a extensão **Live Server** no Visual Studio Code para executar o projeto através de um servidor local e visualizar as alterações em tempo real.

---

## 📁 Estrutura do Projeto

```text
projeto-tudogostoso/
│
├── index.html
├── style.css
├── imagens/
│   └── ...
├── cursores/
│   └── ...
└── README.md
```

---

## 📚 Tecnologias e Conceitos Praticados

- HTML5
- CSS3
- HTML Semântico
- CSS Flexbox
- CSS Backgrounds
- CSS Pseudo-classes
- `position: relative`
- Custom Cursors
- Card Layout
- Responsive Design
- Organização de conteúdo

---

## 👨‍💻 Autor

**Rafael Santana** 🚀

> Estudante de Engenharia da Computação, focado no desenvolvimento de interfaces web, arquitetura de componentes, CSS e fundamentos de Engenharia de Software.

---

<p align="center">
  Projeto desenvolvido para fins educacionais e para consolidação de conhecimentos em HTML5, CSS3, CSS Grid, Flexbox e desenvolvimento de interfaces responsivas.
</p>
