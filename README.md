# 🎬 Projeto Cine — Simulação de Phishing

<div align="center">


</div>

---

## 📌 Sobre o projeto

O **Projeto Cine** é um projeto escolar desenvolvido para demonstrar, de maneira prática e educativa, como uma página aparentemente legítima pode induzir um usuário a fornecer informações.

A página simula uma inscrição para um projeto de filmes e, após o preenchimento do formulário, apresenta uma explicação sobre **phishing**, seus riscos e formas de prevenção.

> ⚠️ **Importante:** este projeto é exclusivamente educacional. Os dados digitados no formulário **não são armazenados, enviados ou coletados**.

---

## 🎯 Objetivo

O principal objetivo é aumentar a conscientização sobre **Segurança da Informação**, mostrando que uma página bonita e aparentemente confiável não significa necessariamente que ela seja segura.

A simulação ajuda a demonstrar a importância de:

* 🔎 Verificar o endereço do site;
* 🔗 Conferir links antes de clicar;
* ⚠️ Desconfiar de mensagens urgentes;
* 🔐 Nunca fornecer dados pessoais em páginas desconhecidas;
* 🧠 Pensar antes de clicar ou enviar informações.

---

## ✨ Características

* 🎬 Interface temática de cinema;
* 🖤 Tema escuro;
* 🔴 Elementos em vermelho neon;
* ✨ Efeitos de brilho;
* 💫 Animações CSS;
* 🌟 Efeitos de hover;
* 🖱️ Interações nos elementos;
* 📱 Design responsivo;
* 🎥 Vídeo educativo sobre phishing;
* 🛡️ Página explicativa após a simulação;
* 🔒 Nenhuma informação é armazenada;
* ⚡ Projeto leve e desenvolvido sem frameworks.

---

## 🖥️ Demonstração

### Página de inscrição

A primeira página apresenta uma interface de inscrição fictícia:

```text
┌─────────────────────────────────────┐
│          ▶ PROJETO CINE             │
│                                     │
│   Entre para o Projeto de Filmes.   │
│                                     │
│   Nome completo                     │
│   [____________________________]    │
│                                     │
│   Série / Turma    Matrícula        │
│   [____________]   [___________]   │
│                                     │
│   ⚠ Simulação educativa             │
│                                     │
│        [ Enviar inscrição → ]       │
└─────────────────────────────────────┘
```

### Página de alerta

Depois da tentativa de envio, o usuário é direcionado para uma página educativa que explica que aquela situação era uma **simulação de phishing**.

---

## 🔐 Segurança da simulação

O formulário **não possui backend** e não envia os dados para nenhum servidor.

O JavaScript apenas impede o envio tradicional do formulário e redireciona o usuário:

```javascript
document.getElementById("formulario").addEventListener("submit", function(event) {
    event.preventDefault();
    window.location.href = "alerta.html";
});
```

Dessa forma, o projeto pode ser utilizado para demonstrações sem realizar coleta de informações.

> **Utilize apenas dados fictícios durante a apresentação.**

---

## 🧰 Tecnologias utilizadas

| Tecnologia    | Utilização                   |
| ------------- | ---------------------------- |
| HTML5         | Estrutura das páginas        |
| CSS3          | Design, animações e efeitos  |
| JavaScript    | Interação e redirecionamento |
| YouTube Embed | Conteúdo educativo           |

---

## 📂 Estrutura do projeto

```text
projeto-filmes/
│
├── index.html       # Página principal
├── alerta.html      # Página educativa
├── style.css        # Estilos e animações
└── README.md        # Documentação
```

### `index.html`

Página principal da simulação, contendo o formulário fictício de inscrição.

### `alerta.html`

Página educativa apresentada após a simulação, contendo explicações e dicas de segurança.

### `style.css`

Arquivo responsável pelo visual do projeto, incluindo:

* Cores;
* Layout;
* Responsividade;
* Animações;
* Efeitos neon;
* Sombras;
* Transições;
* Efeitos de interação.

### `README.md`

Documentação do projeto.

---

## 🚀 Como executar

### Localmente

Não é necessário instalar nenhuma dependência.

Basta baixar o projeto e abrir:

```text
index.html
```

em um navegador.

### GitHub Pages

O projeto também pode ser hospedado gratuitamente utilizando o **GitHub Pages**.

No repositório:

```text
Settings
   ↓
Pages
   ↓
Deploy from a branch
   ↓
main / root
```

Depois da publicação, o GitHub disponibilizará uma URL para acessar o projeto.

---

## 🎓 Finalidade acadêmica

Este projeto foi desenvolvido como uma atividade de **Segurança da Informação**, com o objetivo de demonstrar conceitos relacionados a:

* Phishing;
* Engenharia social;
* Segurança de dados;
* Conscientização digital;
* Identificação de páginas suspeitas;
* Boas práticas de navegação.

O projeto **não tem finalidade de capturar credenciais ou informações reais**.

---

## ⚠️ Aviso

Este projeto deve ser utilizado somente para **fins educacionais e de conscientização**.

Não utilize esta estrutura para coletar senhas, credenciais, dados bancários ou outras informações pessoais de terceiros.

---

## 👨‍💻 Projeto

**Projeto Cine — Segurança da Informação**

📅 **Ano:** 2026

🎓 **Finalidade:** Projeto escolar

---

<div align="center">

### 🛡️ Pense antes de clicar.

**Verifique antes de enviar.**

</div>
