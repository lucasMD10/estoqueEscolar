# 📦 Controle de Estoque Escolar

Sistema simples de controle de estoque de uniformes escolares, desenvolvido para uso individual, permitindo registrar entradas e saídas de produtos de forma prática e organizada.

O projeto foi pensado para pessoas que gerenciam estoque em casa e precisam de uma forma fácil de acompanhar quantidades disponíveis, evitando perdas, falta de produtos ou desorganização.

---

## 🎯 Objetivo

Este sistema foi criado para auxiliar no controle de uniformes escolares, permitindo:

* registrar produtos disponíveis
* controlar entrada de novos itens
* registrar saída de produtos vendidos
* visualizar rapidamente o estoque atual
* manter um histórico organizado das movimentações

O foco principal é a simplicidade e facilidade de uso, sem necessidade de conhecimentos técnicos avançados.

---

## 🧠 Contexto de uso

O sistema foi desenvolvido para uma pessoa que realiza a venda de uniformes escolares a partir de casa, necessitando de um controle eficiente de:

* quantidade de peças disponíveis
* reposição de estoque
* registro de vendas
* organização geral dos produtos

---

## ⚙️ Tecnologias utilizadas

* HTML
* CSS
* JavaScript
* Firebase (Firestore)
* PWA (Progressive Web App)

---

## 📱 Funcionalidades

* Cadastro de produtos
* Registro de entrada de itens no estoque
* Registro de saída de itens do estoque
* Atualização automática das quantidades
* Interface simples e intuitiva
* Pode ser instalado como aplicativo no celular (PWA)
* Armazenamento em nuvem

---

## 🔒 Configuração do Firebase

Para utilizar o sistema, é necessário criar um projeto no Firebase e inserir suas próprias credenciais no arquivo de configuração.

Exemplo:

```javascript
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT.appspot.com",
  messagingSenderId: "YOUR_ID",
  appId: "YOUR_APP_ID"
};
```

As credenciais podem ser obtidas em:

https://console.firebase.google.com/

---

## 🚀 Como usar

1. Baixar ou clonar este repositório
2. Criar um projeto no Firebase
3. Inserir as credenciais do Firebase no arquivo de configuração
4. Abrir o arquivo `index.html` no navegador
5. Começar a cadastrar os produtos

---

## 📂 Estrutura do projeto

```
estoque-escolar
│
├── index.html
├── manifest.json
├── sw.js
└── README.md
```


---

## 📄 Licença

Este projeto é disponibilizado para fins de estudo e uso pessoal.

---

## 👨‍💻 Autor

Desenvolvido por Lucas Marcondes Delfino.
