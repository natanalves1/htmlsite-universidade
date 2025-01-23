
# Documentação do Arquivo `quem-somos.html`

## **Descrição Geral**
Este arquivo HTML representa a página "Quem Somos" de um site fictício de uma universidade. Ele apresenta informações gerais sobre a instituição, sua visão humorística e seu lema, além de incluir elementos visuais como imagens e uma estrutura básica de navegação.

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
- **`<meta charset="utf-8">`**: Define a codificação de caracteres como UTF-8, permitindo suporte a caracteres especiais como acentos.
- **`<meta name="viewport" content="width=device-width, initial-scale=1">`**: Garante que o layout seja responsivo em dispositivos móveis.
- **`<title>`**: Define o título exibido na aba do navegador como "UNI|HOME".

---

### **3. Corpo do Documento**
O conteúdo principal é exibido dentro da tag `<body>`.

#### **3.1. Estrutura Principal (Tabela)**
```html
<table border="1" width="800" align="center">
```
- **`border="1"`**: Adiciona uma borda de 1 pixel ao redor da tabela.
- **`width="800"`**: Define a largura da tabela como 800 pixels.
- **`align="center"`**: Centraliza a tabela horizontalmente na página.

##### **3.1.1. Cabeçalho**
```html
<tr>
    <td align="center">
        <img src="imagens/logo.png" width="200" height="100">
    </td>
    <td align="center">
        <a href="index.html"> HOME </a> |
        <a href="quem-somos.html"> QUEM SOMOS</a> |
        <a href="contato.html"> CONTATO</a>
    </td>
</tr>
```
- Exibe o logotipo da universidade (`logo.png`) e links de navegação:
  - **`HOME`**: Link para a página inicial.
  - **`QUEM SOMOS`**: Link para a página atual.
  - **`CONTATO`**: Link para a página de contato.

---

##### **3.1.2. Seção "Quem Somos"**
```html
<tr>
    <td colspan="2" align="center">
        <h2> Quem somos? </h2>
        <p>Somos a <strong>UNI</strong>, também conhecida como <strong>FZU (Favor Zerar os Últimos boletos)</strong>.</p>
        <p>Nossa instituição nasceu de uma reunião séria de cinco minutos...</p>
        <p>Aqui, acreditamos que educação não precisa ser chata.</p>
        <p><strong>Nosso lema é:</strong> "Se vai sofrer pra aprender, que seja rindo (ou chorando nos prazos do TCC)."</p>
        <p>Nossa equipe de professores é composta por mestres, doutores e aquele que sabe consertar o projetor...</p>
    </td>
</tr>
```
- **`<h2>`**: Define o título da seção "Quem Somos".
- **`<p>` e `<strong>`**: Utilizados para estruturar o texto com partes destacadas.

---

##### **3.1.3. Imagem e Rodapé**
```html
<tr>
    <td colspan="2">
        <img src="Imagens/alunos.jpeg" width="800">
        <hr>
        <strong> Todos os Direitos Reservados</strong>
    </td>
</tr>
```
- **Imagem**: Mostra uma imagem (`alunos.jpeg`) com largura de 800 pixels.
- **Rodapé**: Inclui um texto com "Todos os Direitos Reservados".

---

## **Arquivos Complementares**
- **`imagens/logo.png`**: Logotipo da universidade.
- **`Imagens/alunos.jpeg`**: Imagem de alunos exibida no rodapé.

---


Apresentei as informações sobre a identidade da universidade de forma leve e humorística, ok? Favor Desconsiderar rs.