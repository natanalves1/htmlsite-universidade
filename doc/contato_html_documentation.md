
# Documentação do Arquivo `contato.html`

## **Descrição Geral**
Este arquivo HTML representa a página de contato de um site fictício de uma universidade. Ele inclui um formulário simples para que os usuários enviem mensagens, além de uma estrutura básica de navegação e um rodapé com imagem e direitos reservados.

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
O conteúdo do site é exibido dentro da tag `<body>`.

#### **3.1. Estrutura Principal (Tabela)**
```html
<table width="800" align="center">
```
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
  - **`QUEM SOMOS`**: Link para a página "Quem Somos".
  - **`CONTATO`**: Link para a página atual.

---

##### **3.1.2. Formulário de Contato**
```html
<form>
    <strong>Seu nome:</strong> <br>
    <input type="text" name="Nome"><br>
    <strong>Seu EMAIL:</strong> <br>
    <input type="text" name="Email"><br>
    <strong>Assunto:</strong> <br>
    <input type="text" name="Nassunto"><br>
    <textarea></textarea><br>
    <input type="submit" value="enviar">
</form>
```
- Inclui campos de entrada para:
  - Nome (`<input type="text" name="Nome">`)
  - E-mail (`<input type="text" name="Email">`)
  - Assunto (`<input type="text" name="Nassunto">`)
  - Texto adicional (`<textarea></textarea>`)
- **`<input type="submit" value="enviar">`**: Botão para enviar o formulário.

---

##### **3.1.3. Imagem e Rodapé**
```html
<tr>
    <td colspan="2" align="center">
        <hr>
        <img src="Imagens/librart.jpeg" width="800">
        <br>
        <hr>
        <strong> Todos os Direitos Reservados</strong>
    </td>
</tr>
```
- **Imagem**: Mostra uma imagem de nome `librart.jpeg` com largura de 800 pixels.
- **Rodapé**: Inclui texto com "Todos os Direitos Reservados".

---

## **Arquivos Complementares**
- **`imagens/logo.png`**: Logotipo da universidade.
- **`Imagens/librart.jpeg`**: Imagem exibida no rodapé.

---
