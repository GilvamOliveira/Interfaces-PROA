# 📚 Estudo de Listas em HTML e CSS

Projeto desenvolvido durante meus estudos de **HTML5 e CSS3**, com foco na prática de listas, elementos HTML, seletores CSS e organização básica de uma página web.

O objetivo deste projeto é consolidar os fundamentos aprendidos antes de avançar para estruturas e projetos mais complexos.

---

## 🎯 Objetivo

Praticar e compreender os principais conceitos básicos de HTML e CSS, utilizando exemplos práticos e organizados.

Neste projeto foram trabalhados:

- Listas não ordenadas
- Listas ordenadas
- Listas de definição
- Parágrafos
- Divisões com `div`
- `id`
- `class`
- `span`
- Seletores CSS
- Cores
- Bordas
- Espaçamentos
- Backgrounds
- Organização de arquivos HTML e CSS

---

## 🛠️ Tecnologias utilizadas

- **HTML5**
- **CSS3**
- **Visual Studio Code**

---

## 📁 Estrutura do projeto

```text
estudo-listas-html/
│
├── index.html
│
├── assets/
│   ├── css/
│   │   └── style.css
│   │
│   └── img/
│       └── Listas e Tabelas HTML.jpg
│
└── README.md
```

---

## 📖 Conteúdos praticados

### 🔹 Listas não ordenadas

Utilização da tag `<ul>` com diferentes tipos de marcadores:

```html
<ul type="circle">
    <li>Abacaxi</li>
    <li>Manga</li>
    <li>Melancia</li>
</ul>
```

Foram estudados:

- `circle`
- `square`
- `disc`
- `none`

---

### 🔹 Listas ordenadas

Utilização da tag `<ol>` para criar listas em diferentes formatos.

Exemplos estudados:

- Números
- Letras maiúsculas
- Letras minúsculas
- Números romanos maiúsculos
- Números romanos minúsculos
- Início da contagem utilizando `start`

Exemplo:

```html
<ol start="5">
    <li>Lucas</li>
    <li>Beatriz</li>
    <li>Rafael</li>
</ol>
```

---

### 🔹 Listas de definição

Prática das tags:

- `<dl>`
- `<dt>`
- `<dd>`

Exemplo:

```html
<dl>

    <dt>HTML</dt>

    <dd>
        Linguagem utilizada para estruturar
        páginas da web.
    </dd>

</dl>
```

---

### 🔹 Div

Utilização da tag `<div>` para agrupar elementos relacionados dentro da página.

```html
<div>

    <h3>Exemplo de agrupamento</h3>

    <p>Primeiro parágrafo.</p>
    <p>Segundo parágrafo.</p>

</div>
```

---

### 🔹 ID

Prática da utilização de `id` para identificar elementos específicos.

```html
<p id="paragrafo-destaque">
    Texto de exemplo.
</p>
```

No CSS, o elemento pode ser selecionado utilizando `#`:

```css
#paragrafo-destaque {
    color: white;
}
```

---

### 🔹 Class

Prática da utilização de `class` para aplicar o mesmo estilo em diferentes elementos.

```html
<p class="texto-exemplo">
    Primeiro texto.
</p>

<p class="texto-exemplo">
    Segundo texto.
</p>
```

No CSS:

```css
.texto-exemplo {
    color: green;
}
```

---

### 🔹 Span

Utilização de `<span>` para aplicar uma alteração específica em uma parte do conteúdo.

```html
<p>
    O HTML é utilizado para
    <span id="palavra-destaque">estruturar</span>
    páginas.
</p>
```

---

## 🎨 CSS praticado

Neste projeto também foram utilizados conceitos básicos de CSS, como:

```css
color
background-color
border
border-radius
padding
margin
font-family
font-size
font-weight
text-align
line-height
```

Também foi praticada a utilização de diferentes tipos de seletores:

```css
elemento { }

#id { }

.classe { }
```

---

## 📌 O que estou aprendendo

Este projeto faz parte da minha evolução nos estudos de desenvolvimento web.

Neste momento, meu foco está em construir uma base sólida em:

**HTML → CSS → Estrutura → Estilização → Layout → Projetos**

A intenção é utilizar os próximos projetos para aplicar esses conhecimentos em páginas cada vez mais completas e organizadas.

---

## 🚀 Próximos passos

Após consolidar esses fundamentos, os próximos estudos serão direcionados para:

- Box Model
- `margin`
- `padding`
- `width` e `height`
- `display`
- Flexbox
- Grid
- Posicionamento
- Responsividade
- Estrutura semântica
- Projetos práticos

---

## 👨‍💻 Autor

**Gilvam J. T. de Oliveira**

Projeto criado para fins de estudo e prática de **HTML5 e CSS3**.

---

⭐ Este projeto representa uma etapa da minha evolução nos estudos de desenvolvimento web.
