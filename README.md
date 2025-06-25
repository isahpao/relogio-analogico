# 

### 

# 🕒 PROJETO RELÓGIO ANALÓGICO SVG


## 📌 Descrição

Este projeto foi desenvolvido como parte do curso de **formação básica em JavaScript**, com o objetivo de colocar em prática conceitos de manipulação de tempo, animação e uso do SVG para criar elementos visuais interativos. A proposta é simular um relógio analógico funcional, com ponteiros que se movimentam de acordo com a hora atual do sistema.

> 💡 **Objetivo pessoal:** Aprimorar a lógica com JavaScript, explorar o SVG e praticar a criação de interfaces visuais interativas e precisas.

## ✨ Funcionalidades

- 🕰️ **Ponteiros dinâmicos:** O relógio atualiza automaticamente a cada segundo, com ponteiros de horas, minutos e segundos em movimento.
- 🎯 **Centralização perfeita:** Os ponteiros giram em torno de um ponto central fixo com transformações suaves.
- 🎨 **Estilo personalizável:** Estrutura e visual do relógio personalizáveis via CSS e SVG.

## 🔍 Funcionamento Lógico do Sistema

1. **Captura da hora atual:** Utiliza `Date()` para obter horas, minutos e segundos do sistema.
2. **Cálculo dos ângulos:** Os valores são convertidos em graus para rotacionar os ponteiros via `transform: rotate()`.
3. **Atualização constante:** O `setInterval()` garante que o relógio se atualize a cada segundo.

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estruturação da página.
- **CSS3**: Estilização do layout e ponteiros.
- **SVG**: Criação do mostrador e dos ponteiros do relógio.
- **JavaScript**: Lógica de tempo e animação.

## 🧠 Aprendizados

- Entendimento prático sobre `SVG` como elemento visual em HTML.

## 🔗 Demonstração Online

[Clique aqui para acessar a versão online](https://isahpao.github.io/relogio-analogico/)

## 📷 Preview

![Preview do projeto](https://github.com/isahpao/relogio-analogico/blob/main/Um-Rel%C3%B3gio-Anal%C3%B3gico-por%C3%A9m-digital-06-24-2025_09_56_PM.png?raw=true)


## 🚀 Como Rodar o Projeto Localmente

Este é um projeto **estático** (HTML, CSS e JavaScript puro), portanto **não requer instalação de dependências**.

Para testar localmente, siga os passos abaixo:

### **1️⃣ Clone o repositório**

```bash
git clone https://github.com/isahpao/relogico-analogico

```

### **2️⃣ Acesse a pasta do projeto**

```bash

cd relogio-analogico

```

### **3️⃣ Execute o projeto**

Abra o arquivo index.html diretamente no navegador
ou utilize uma extensão como o Live Server no VS Code para uma visualização mais dinâmica.
