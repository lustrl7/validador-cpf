# 🧾 Validador de CPF PRO

Aplicação web para validação de CPF utilizando JavaScript puro, com arquitetura modular inspirada em boas práticas modernas (como separação em `services` e `utils`).

---

## 📑 Sumário

- [Visão Geral](#visão-geral)
- [Funcionalidades](#funcionalidades)
- [Tecnologias](#tecnologias)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Como Executar](#como-executar)
- [Deploy](#deploy)
- [Melhorias Futuras](#melhorias-futuras)
- [Autor](#autor)

---

## 🧭 Visão Geral

Este projeto foi desenvolvido com o objetivo de validar números de CPF utilizando JavaScript, aplicando conceitos de modularização, organização de código e boas práticas de desenvolvimento.

O sistema verifica se o CPF informado possui:

- 11 dígitos;
- Dígitos verificadores válidos;
- Sequências inválidas (ex.: 11111111111).

---

## ⚙️ Funcionalidades

- ✅ Validação completa de CPF
- 🎯 Formatação automática do CPF (000.000.000-00)
- 🚫 Bloqueio de sequências inválidas
- 🧩 Arquitetura modular
- 🌐 Compatível com GitHub Pages

---

## 🛠️ Tecnologias

- HTML5
- CSS3
- JavaScript (ES Modules)
- Git
- GitHub

---

## 🏗️ Estrutura do Projeto

```text
validador-cpf/
│
├── public/
│   ├── index.html
│   └── style.css
│
├── src/
│   ├── main.js
│   ├── services/
│   │   └── cpfValidator.js
│   └── utils/
│       └── format.js
│
├── README.md
└── package.json
```

### Organização

- **public/** → Interface da aplicação
- **services/** → Regras de negócio (validação do CPF)
- **utils/** → Funções auxiliares (formatação)
- **main.js** → Integração entre interface e lógica

---

## ▶️ Como Executar

Clone o repositório:

```bash
git clone https://github.com/lustrl7/validador-cpf.git
```

Acesse a pasta:

```bash
cd validador-cpf
```

Abra o arquivo:

```text
public/index.html
```

---

## 🌐 Deploy

Após publicar no GitHub Pages, o projeto poderá ser acessado em:

```
https://lustrl7.github.io/validador-cpf
```

---

## 🔮 Melhorias Futuras

- Implementar testes automatizados
- Criar API em Node.js
- Melhorar a interface responsiva
- Adicionar validação em tempo real
- Implementar CI/CD com GitHub Actions

---

## 👨‍💻 Autor

Desenvolvido por **Luis** como projeto de estudo para aplicação de JavaScript, arquitetura modular e boas práticas de desenvolvimento.

# Artefatos de Gestão de Riscos

Documentação de apoio ao projeto **Validador de CPF**.

## Arquivos
- matriz-riscos.md
- plano-resposta-riscos.md
- plano-comunicacao.md
