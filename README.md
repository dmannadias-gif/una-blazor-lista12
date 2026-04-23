# 🌱 EcoMonitor - Lista 12 (Blazor)

## 📌 Identificação

**Nome:** Anna Vitória Rocha Dias

**Curso:** Análise e Desenvolvimento de Sistemas (ADS)

**Disciplina:** Interação Humano-Computador e UX

**Professor:** Daniel Henrique Matos de Paiva

---

## 🎯 Objetivo do Projeto

O objetivo deste projeto é desenvolver uma aplicação em Blazor chamada **EcoMonitor**, capaz de registrar ações sustentáveis realizadas pelo usuário e exibir seu impacto em tempo real.

A aplicação utiliza conceitos de:

* Componentização
* Reutilização de código
* Manipulação de estado
* Interatividade com o usuário

---

## 🧩 Funcionalidades

✔ Registro de ações sustentáveis através de botões
✔ Contador dinâmico de pontos
✔ Componentes reutilizáveis
✔ Alteração visual conforme progresso
✔ Barra de progresso (desafio extra)
✔ Mensagem de conquista ao atingir meta

---

## 🧠 Heurísticas de Nielsen Aplicadas

### 1. Visibilidade do Status do Sistema

O sistema informa constantemente ao usuário seu progresso através do contador atualizado em tempo real.

### 2. Feedback Imediato

Ao clicar no botão, o usuário recebe uma resposta instantânea (aumento dos pontos), tornando a interação clara e intuitiva.

---

## ⚙️ Explicação Técnica

O componente `EcoStatus` foi desenvolvido para ser reutilizável utilizando **parâmetros**.

### 🔹 Uso do `[Parameter]`

O atributo `[Parameter]` permite que valores sejam passados para o componente, como:

* `Titulo` → nome da ação
* `Peso` → valor somado ao contador

Isso possibilita reutilizar o mesmo componente com diferentes configurações.

### 🔹 Estado do Componente

A variável `total` armazena o estado atual dos pontos, sendo atualizada a cada interação do usuário.

---

## 🏗️ Estrutura do Projeto

* `EcoStatus.razor` → Componente reutilizável
* `Home.razor` → Página principal com instâncias do componente
* `Program.cs` → Configuração da aplicação

---

## ▶️ Como Executar o Projeto

### 1. Clonar o repositório

```bash
git clone https://github.com/seu-usuario/una-blazor-lista12.git
cd una-blazor-lista12
```

### 2. Executar o projeto

```bash
dotnet run
```

### 3. Acessar no navegador

```
https://localhost:5001
```

---

## 🚀 Tecnologias Utilizadas

* .NET
* Blazor
* C#
* HTML / CSS

---

## 🏆 Desafio Extra

✔ Implementação de barra de progresso
✔ Exibição de mensagem especial ao atingir 100 pontos

---

## 📌 Considerações Finais

O projeto demonstra na prática como utilizar Blazor para criar interfaces interativas e reutilizáveis, aplicando conceitos importantes de UX e desenvolvimento moderno.

---
