# 📝 CRUD com HTML5, Bootstrap e LocalStorage

Este é um projeto simples de CRUD (Create, Read, Update, Delete) que utiliza HTML5, Bootstrap 5 e `localStorage` para armazenar dados no navegador. O formulário é definido dentro de uma tag `<template>` e exibido em um modal (popup). Os dados podem ser baixados como um arquivo JSON.

## 💡 Funcionalidades

- ✅ Interface responsiva com **Bootstrap 5**
- ✅ **Formulário dinâmico** definido em `<template>`
- ✅ Armazenamento em **localStorage**
- ✅ Modal de entrada de dados (popup)
- ✅ **Edição com preenchimento automático** dos dados
- ✅ Confirmação antes da exclusão
- ✅ Botão para exportar os dados em **formato JSON**
- ✅ Código JavaScript **genérico**: basta modificar o formulário no HTML

## 🖼️ Exemplo de Campos

O formulário padrão vem com os campos:

- Nome
- Endereço
- Telefone

Você pode alterar ou adicionar campos diretamente na tag `<template>` no HTML.

## 🗃️ Estrutura dos Arquivos
```
📁 crud-bootstrap-localstorage
├── index.html # HTML com Bootstrap, estrutura da interface e template do formulário
├── crud.js # Código JavaScript genérico para o CRUD
└── README.md # Este arquivo
```

## ▶️ Como Usar

1. Clone ou baixe este repositório.
2. Abra o arquivo `index.html` no navegador.
3. Clique em "Novo Registro" para adicionar dados.
4. Os dados são salvos no `localStorage` automaticamente.
5. Clique em "Baixar JSON" para salvar os dados localmente.

## 🛠️ Como Modificar o Formulário

Você pode personalizar os campos alterando o conteúdo da tag `<template>` no HTML:

```html
<template id="form-template">
  <div class="mb-3">
    <label for="nome" class="form-label">Nome</label>
    <input type="text" class="form-control" name="nome" required>
  </div>
  <!-- Adicione mais campos aqui -->
</template>
```
