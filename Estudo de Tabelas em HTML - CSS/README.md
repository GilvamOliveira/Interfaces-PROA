# 📊 Estudo de Tabelas em HTML e CSS

Projeto desenvolvido durante meus estudos de **HTML5 e CSS3**, com foco na criação, estruturação e estilização de tabelas.

Este projeto foi criado como prática do conteúdo de **HTML Tables**, estudando os principais elementos utilizados na construção de tabelas em HTML.

---

## 🎯 Objetivo

O objetivo deste projeto é compreender como as tabelas funcionam em HTML e como seus elementos podem ser organizados para apresentar informações de maneira estruturada.

Durante o desenvolvimento, foram praticados:

- Criação de tabelas
- Linhas e células
- Cabeçalhos
- Títulos de tabelas
- Estruturação de tabelas
- Mesclagem de colunas
- Mesclagem de linhas
- Organização de dados
- Estilização utilizando CSS

---

## 🛠️ Tecnologias utilizadas

- **HTML5**
- **CSS3**
- **Visual Studio Code**

---

## 📁 Estrutura do projeto

```text
estudo-tabelas-html/
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

## 📚 Conteúdos estudados

### 1. `<table>`

A tag `<table>` é utilizada para criar uma tabela em HTML.

```html
<table>

    ...

</table>
```

---

### 2. `<tr>`

A tag `<tr>` representa uma **linha da tabela**.

```html
<tr>
    <td>HTML</td>
    <td>Estrutura</td>
</tr>
```

Neste projeto, foram criadas diferentes linhas para demonstrar como os dados são organizados.

---

### 3. `<td>`

A tag `<td>` representa uma **célula de dados**.

```html
<td>Gilvam</td>
<td>HTML</td>
<td>Iniciante</td>
```

Ela é utilizada para inserir as informações dentro das linhas da tabela.

---

### 4. `<th>`

A tag `<th>` representa uma **célula de cabeçalho**.

```html
<tr>
    <th>Aluno</th>
    <th>Curso</th>
    <th>Nível</th>
</tr>
```

No projeto, ela foi utilizada para identificar as colunas das tabelas.

---

### 5. `<caption>`

A tag `<caption>` permite adicionar um título ou descrição à tabela.

```html
<table>

    <caption>
        Notas dos alunos
    </caption>

    ...

</table>
```

No projeto, ela foi utilizada para identificar tabelas como **Notas dos alunos**, **Desempenho da turma** e **Controle de Estudos**.

---

## 🧱 Estrutura da tabela

Também foi estudada a divisão da tabela em diferentes partes:

### `<thead>`

Representa o cabeçalho da tabela.

```html
<thead>

    <tr>
        <th>Aluno</th>
        <th>HTML</th>
        <th>JAVA</th>
    </tr>

</thead>
```

---

### `<tbody>`

Representa o corpo principal da tabela.

```html
<tbody>

    <tr>
        <td>Gilvam</td>
        <td>9,0</td>
        <td>8,5</td>
    </tr>

</tbody>
```

---

### `<tfoot>`

Representa o rodapé da tabela.

```html
<tfoot>

    <tr>
        <th>Média</th>
        <td>8,3</td>
        <td>8,5</td>
    </tr>

</tfoot>
```

A utilização desses elementos ajuda a organizar semanticamente as diferentes partes de uma tabela.

---

## 🔗 `colspan`

O atributo `colspan` permite que uma célula ocupe mais de uma coluna.

Neste projeto, foi utilizado para fazer uma célula ocupar duas colunas:

```html
<th colspan="2">
    Nome
</th>
```

Também foi utilizado na tabela final:

```html
<th colspan="3">
    Resultado da turma
</th>
```

---

## ↕️ `rowspan`

O atributo `rowspan` permite que uma célula ocupe mais de uma linha.

Exemplo utilizado no projeto:

```html
<td rowspan="2">
    HTML e JAVA
</td>
```

Nesse caso, a célula **HTML e JAVA** ocupa duas linhas da tabela.

---

## 📊 Exemplos desenvolvidos

Durante o projeto foram criados exemplos para demonstrar diferentes níveis de utilização das tabelas:

### Tabela básica

Demonstra a utilização de:

- `<table>`
- `<tr>`
- `<td>`

---

### Linhas da tabela

Demonstra especificamente a utilização de:

- `<tr>`

---

### Células

Demonstra a utilização de:

- `<td>`

---

### Cabeçalhos

Demonstra a utilização de:

- `<th>`

---

### Título da tabela

Demonstra a utilização de:

- `<caption>`

---

### Estrutura completa

Demonstra a utilização conjunta de:

- `<caption>`
- `<thead>`
- `<tbody>`
- `<tfoot>`
- `<th>`
- `<td>`

---

### Mesclagem de colunas

Demonstra:

- `colspan`

---

### Mesclagem de linhas

Demonstra:

- `rowspan`

---

### Tabela completa

O último exemplo reúne vários dos conceitos estudados em uma única tabela.

A tabela apresenta:

- Alunos
- Notas de HTML
- Notas de Java
- Status
- Resultado da turma

---

## 🎨 CSS praticado

Além da estrutura HTML, também foram utilizados conceitos de CSS para melhorar a apresentação das tabelas.

Entre eles:

- `background-color`
- `color`
- `border`
- `border-collapse`
- `border-radius`
- `padding`
- `margin`
- `font-size`
- `font-weight`
- `text-align`
- `width`
- `:hover`
- `:nth-child()`

Exemplo:

```css
table {
    width: 100%;
    border-collapse: collapse;
}

th {
    padding: 12px;
}

td {
    padding: 12px;
}
```

Também foi utilizado CSS para criar efeitos visuais nas linhas das tabelas:

```css
tbody tr:hover {
    background-color: #dbeafe;
}
```

---

## 🧠 O que estou aprendendo

Este projeto representa mais uma etapa da minha evolução nos estudos de desenvolvimento web.

Depois de praticar elementos básicos do HTML, como:

- listas;
- parágrafos;
- `div`;
- `span`;
- `id`;
- `class`;

o estudo de tabelas adiciona uma nova forma de organizar informações dentro de uma página.

A ideia é continuar evoluindo gradualmente:

```text
HTML básico
     ↓
Listas
     ↓
Tabelas
     ↓
CSS básico
     ↓
Box Model
     ↓
Flexbox
     ↓
Grid
     ↓
Responsividade
     ↓
Projetos completos
```

---

## 🚀 Próximos passos

Após consolidar os conhecimentos de tabelas, os próximos conteúdos de estudo serão:

- Box Model
- `margin`
- `padding`
- `width` e `height`
- `display`
- Flexbox
- Grid
- Formulários
- HTML semântico
- Responsividade
- Projetos práticos

---

## 👨‍💻 Autor

**Gilvam J. T. de Oliveira**

Projeto desenvolvido para fins de estudo e prática de **HTML5 e CSS3**.

---

⭐ Este projeto representa mais uma etapa da minha evolução no desenvolvimento web.
