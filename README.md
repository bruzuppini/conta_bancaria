# 🏦 Projeto Conta Bancária

Projeto backend desenvolvido com **TypeScript** e **Node.js**, simulando funcionalidades básicas de um sistema de conta bancária.

A aplicação foi criada com foco em **lógica de programação orientada a objetos**, utilizando classes, tipos e métodos para representar operações bancárias como saque, depósito e consulta de saldo.

---

## ✨ Sobre o projeto

O **Projeto Conta Bancária** tem como objetivo praticar conceitos fundamentais de backend e orientação a objetos, criando uma estrutura simples para representar uma conta bancária e suas principais operações.

O sistema permite simular ações comuns em uma conta, como:

- Criar uma conta bancária
- Consultar saldo
- Realizar depósitos
- Realizar saques
- Aplicar regras básicas de negócio
- Organizar funcionalidades usando classes e tipos do TypeScript

---

## 🛠️ Tecnologias utilizadas

| Tecnologia | Descrição |
|---|---|
| TypeScript | Linguagem principal do projeto |
| Node.js | Ambiente de execução JavaScript |
| Programação Orientada a Objetos | Organização das regras de negócio |
| Lógica de Programação | Estruturação das operações bancárias |

---

## 📚 Conceitos praticados

- Classes
- Objetos
- Métodos
- Atributos
- Tipagem com TypeScript
- Encapsulamento de regras de negócio
- Estruturação de projeto backend
- Simulação de operações bancárias

---

## ⚙️ Funcionalidades

### 💰 Depósito

Permite adicionar um valor ao saldo da conta.

### 🏧 Saque

Permite retirar um valor da conta, respeitando as regras de saldo disponível.

### 📊 Consulta de saldo

Permite visualizar o saldo atual da conta bancária.

---

## 📁 Estrutura do projeto

```txt
projeto-conta-bancaria/
├── src/
│   └── util/
│       └── Colors.ts
├── Menu.ts
├── README.md
├── package.json
├── package-lock.json
└── tsconfig.json
```

> O arquivo `Menu.ts` concentra a execução principal do sistema, enquanto `Colors.ts` auxilia na estilização das mensagens exibidas no terminal.

---

## 🚀 Como executar o projeto

### 1. Clone o repositório

```bash
git clone https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
```

### 2. Acesse a pasta do projeto

```bash
cd SEU-REPOSITORIO
```

### 3. Instale as dependências

```bash
npm install
```

### 4. Execute o projeto

Caso o projeto use `ts-node`, rode:

```bash
npm run dev
```

Ou, se preferir compilar o TypeScript:

```bash
npm run build
npm start
```

---

## 💡 Exemplo de uso

```ts
const conta = new Conta("Bruna", 1000);

conta.depositar(500);
conta.sacar(200);
conta.consultarSaldo();
```

Saída esperada:

```txt
Depósito realizado com sucesso.
Saque realizado com sucesso.
Saldo atual: R$ 1300
```

---

## 🎯 Objetivo

Este projeto foi desenvolvido para praticar a criação de sistemas backend simples utilizando **TypeScript**, **Node.js** e **programação orientada a objetos**, reforçando a organização de regras de negócio por meio de classes e métodos.

---

## 👩‍💻 Autor

Desenvolvido por **Bruna Zuppini Bacchiega**.

---

```txt
☾ código, lógica e organização em cada operação
```
