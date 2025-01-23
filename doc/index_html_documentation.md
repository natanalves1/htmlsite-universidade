
# Documentação do Arquivo `index.html`

## **Descrição Geral**
Este é o arquivo principal de um site fictício de uma universidade. Ele apresenta uma estrutura básica com uma tabela centralizada contendo o cabeçalho, imagens, informações sobre a universidade e depoimentos de alunos. O arquivo utiliza elementos HTML simples para exibir o conteúdo de forma organizada.

---

## **Estrutura do Arquivo**

### **1. Declaração do Tipo de Documento**
```html
<!DOCTYPE html>
```
- Define o tipo de documento como HTML5, garantindo compatibilidade com navegadores modernos.

---

### **2. Cabeçalho do Documento**
```html
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title> UNI|HOME</title>
</head>
```
- **`<meta charset="utf-8">`**: Define a codificação de caracteres como UTF-8, suportando caracteres especiais como acentos.
- **`<meta name="viewport" content="width=device-width, initial-scale=1">`**: Garante que o layout seja responsivo em dispositivos móveis.
- **`<title>`**: Define o título exibido na aba do navegador como "UNI|HOME".

---

### **3. Corpo do Documento**
O conteúdo do site é exibido dentro da tag `<body>`.

#### **3.1. Fundo do Site**
```html
<body background="imagens/fundo.png">
```
- Define a imagem `fundo.png` como plano de fundo do site.

---

#### **3.2. Estrutura Principal (Tabela)**
A estrutura principal é composta por uma tabela centralizada:
```html
<table border="1" width="800" align="center">
```
- **`border="1"`**: Adiciona uma borda de 1 pixel ao redor da tabela.
- **`width="800"`**: Define a largura da tabela.
- **`align="center"`**: Centraliza a tabela horizontalmente na página.

##### **3.2.1. Cabeçalho**
```html
<tr>
    <td align="center">
        <img src="imagens/logo.png" width="200" height="100">
    </td>
    <td align="center">
        <a href=""> HOME </a> |
        <a href="quem-somos.html"> QUEM SOMOS</a> |
        <a href="contato.html"> CONTATO</a>
    </td>
</tr>
```
- Exibe o logotipo da universidade (`logo.png`) e links de navegação:
  - **`HOME`**: Link para a página inicial.
  - **`QUEM SOMOS`**: Link para a página "Quem Somos".
  - **`CONTATO`**: Link para a página de contato.

---

##### **3.2.2. Imagem Principal**
```html
<tr>
    <td colspan="2" align="center">
        <img src="imagens/CAMPUS.jpg" height="500" width="1200">
    </td>
</tr>
```
- Exibe uma imagem representando o campus da universidade (`CAMPUS.jpg`).
- **`colspan="2"`**: Faz com que a imagem ocupe toda a largura da tabela.

---

##### **3.2.3. Sobre a Universidade**
```html
<tr>
    <td colspan="2">
        <h2> Sobre a Universidade </h2>
        <strong>Lorem Ipsum Universitatis</strong>
        <p>"Onde seus sonhos viram boletos."</p>
        <p><strong>Missão:</strong> Transformar mentes brilhantes...</p>
        <p><strong>Visão:</strong> Liderar o ranking das faculdades...</p>
        <p><strong>Valores:</strong> Café na veia...</p>
        <p><strong>Cursos:</strong> Engenharia da Procrastinação...</p>
    </td>
</tr>
```
- **`<h2>`**: Define o título principal da seção "Sobre a Universidade".
- **`<strong>` e `<p>`**: Destacam texto e criam parágrafos para detalhar:
  - Missão.
  - Visão.
  - Valores.
  - Cursos oferecidos.

---

##### **3.2.4. Depoimentos de Alunos**
```html
<tr>
    <td colspan="2">
        <h2> Depoimento de Alunos</h2>
        <p><em>"Entrei achando que ia mudar o mundo..."</em>...</p>
        <hr>
        <strong> Todos os Direitos Reservados</strong>
    </td>
</tr>
```
- **`<h2>`**: Título da seção "Depoimento de Alunos".
- **`<em>`**: Estiliza o texto em itálico para destacar os depoimentos.
- **`<hr>`**: Adiciona uma linha horizontal para separar o conteúdo.
- **`<strong>`**: Indica direitos autorais.

---

## **Arquivos Complementares**
- **`imagens/fundo.png`**: Imagem usada como plano de fundo.
- **`imagens/logo.png`**: Logotipo da universidade.
- **`imagens/CAMPUS.jpg`**: Imagem do campus.

---

## **Considerações Finais**
Este arquivo HTML demonstra uma estrutura simples, com tabelas para organizar o conteúdo e imagens para enriquecer a apresentação. Para aprimorar, considere:
- Tornar o site responsivo utilizando CSS.
- Utilizar links externos para os estilos.
- Incluir validações HTML para garantir compatibilidade.
