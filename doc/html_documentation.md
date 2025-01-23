
# Documentação HTML - Organizada e Traduzida

---

## **Documentação: Linguagem HTML**

### 1. Criando um Arquivo HTML:
- Crie um arquivo no editor de código e salve com a extensão `.html`.
- Escreva o conteúdo desejado.
- Salve as edições (`Ctrl + S` no Sublime Text).
- Abra o arquivo no navegador para verificar a apresentação visual.

---

### 2. Estruturação do HTML:

#### Tipo de Documento (Tipagem):
```html
<!DOCTYPE html>
```
Define a versão do HTML utilizada no documento.

#### Estrutura Básica:
```html
<html>
  <head>
    <meta charset="utf-8"> <!-- Define a codificação do texto -->
    <title>Título do Documento</title> <!-- Título da Página -->
  </head>
  <body>
    <!-- Conteúdo principal -->
  </body>
</html>
```

---

### 3. Elementos Comuns:

#### Cabeçalho e Títulos:
```html
<h1> Título Principal </h1> <!-- Maior Tamanho -->
<h6> Título Menor </h6> <!-- Menor Tamanho -->
```

#### Parágrafos:
```html
<p>Seu texto aqui.</p>
```

#### Quebras de Linha:
```html
<br>
```

#### Linha Horizontal:
```html
<hr>
```

---

### 4. Listas:

#### Lista Não Ordenada:
```html
<ul type="circle">
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
```

#### Lista Ordenada:
```html
<ol type="1">
  <li>Item A</li>
  <li>Item B</li>
</ol>
```

---

### 5. Imagens:
```html
<img src="caminho/para/imagem.jpg" width="600" alt="Descrição da imagem">
```

---

### 6. Links (Âncoras):
```html
<a href="https://www.exemplo.com">Texto do Link</a>
```

---

### 7. Tabelas:

#### Estrutura Básica:
```html
<table>
  <tr>
    <th>Coluna 1</th>
    <th>Coluna 2</th>
  </tr>
  <tr>
    <td>Item 1</td>
    <td>Item 2</td>
  </tr>
</table>
```

#### Mesclar Linhas:
```html
<td colspan="2">Mesclando Colunas</td>
```

#### Mesclar Colunas:
```html
<td rowspan="2">Mesclando Linhas</td>
```

---

### 8. Formularios e Elementos Interativos:

#### Estrutura Básica:
```html
<form action="processa.php" method="post">
  <input type="text" name="usuario">
  <input type="password" name="senha">
  <button type="submit">Enviar</button>
</form>
```

#### Seleção:
```html
<select>
  <option>Opção 1</option>
  <option>Opção 2</option>
</select>
```

---

## **Translation: HTML Documentation**

### 1. Creating an HTML File:
- Create a file in your code editor and save it with the `.html` extension.
- Write the desired content.
- Save your changes (`Ctrl + S` in Sublime Text).
- Open the file in a browser to check the visual presentation.

---

### 2. HTML Structure:

#### Document Type (Doctype):
```html
<!DOCTYPE html>
```
Specifies the HTML version used.

#### Basic Structure:
```html
<html>
  <head>
    <meta charset="utf-8"> <!-- Defines text encoding -->
    <title>Document Title</title> <!-- Page Title -->
  </head>
  <body>
    <!-- Main Content -->
  </body>
</html>
```

---

### 3. Common Elements:

#### Headers:
```html
<h1>Main Title</h1> <!-- Largest Size -->
<h6>Smallest Title</h6> <!-- Smallest Size -->
```

#### Paragraphs:
```html
<p>Your text here.</p>
```

#### Line Breaks:
```html
<br>
```

#### Horizontal Line:
```html
<hr>
```

---

### 4. Lists:

#### Unordered List:
```html
<ul type="circle">
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
```

#### Ordered List:
```html
<ol type="1">
  <li>Item A</li>
  <li>Item B</li>
</ol>
```

---

### 5. Images:
```html
<img src="path/to/image.jpg" width="600" alt="Image description">
```

---

### 6. Links (Anchors):
```html
<a href="https://www.example.com">Link Text</a>
```

---

### 7. Tables:

#### Basic Structure:
```html
<table>
  <tr>
    <th>Column 1</th>
    <th>Column 2</th>
  </tr>
  <tr>
    <td>Item 1</td>
    <td>Item 2</td>
  </tr>
</table>
```

#### Merging Rows:
```html
<td colspan="2">Merging Columns</td>
```

#### Merging Columns:
```html
<td rowspan="2">Merging Rows</td>
```

---

### 8. Forms and Interactive Elements:

#### Basic Structure:
```html
<form action="process.php" method="post">
  <input type="text" name="user">
  <input type="password" name="password">
  <button type="submit">Submit</button>
</form>
```

#### Selection:
```html
<select>
  <option>Option 1</option>
  <option>Option 2</option>
</select>
```
