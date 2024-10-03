# 🧮 Calculadora em Java

Este projeto é uma **calculadora simples** desenvolvida em Java, que permite realizar operações aritméticas básicas, como **adição**, **subtração**, **multiplicação** e **divisão**. A aplicação utiliza a entrada de números e operadores do usuário e retorna o resultado da operação.

## 🚀 Funcionalidades

- Adição (`+`)
- Subtração (`-`)
- Multiplicação (`*`)
- Divisão (`/`)

## 📋 Pré-requisitos

Para rodar o projeto, você precisará de:

- [Java JDK 8+](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
- Um terminal ou IDE que suporte Java (como [IntelliJ IDEA](https://www.jetbrains.com/idea/), [Eclipse](https://www.eclipse.org/ide/), [VS Code](https://code.visualstudio.com/), ou qualquer outro de sua preferência).

## 💻 Como usar

1. Clone este repositório ou baixe o arquivo ZIP:

   ```bash
   git clone https://github.com/seu-usuario/calculadora-java.git
   ```

2. Abra o projeto em sua IDE ou terminal.

3. Compile e execute o programa:

   - Usando o terminal:
     ```bash
     javac Calculator.java
     java Calculator
     ```

4. Insira os números e escolha a operação desejada quando solicitado.

### Exemplo de uso:

```bash
Digite o primeiro número: 86
Digite o segundo número: 43
Digite a operação (+, -, *, /): *
86.0 * 43.0: 3698
```

## 🛠️ Tecnologias Utilizadas

- **Java**: Linguagem de programação utilizada para o desenvolvimento da calculadora.
- **Scanner**: Utilizado para capturar entradas do usuário via console.

## 🔍 Detalhes da Lógica

A calculadora aceita dois números e um operador (+, -, *, /). Com base no operador fornecido pelo usuário, o programa realiza a operação correspondente e exibe o resultado. Além disso, o programa verifica se o resultado é um número inteiro ou decimal e, se for inteiro, remove as casas decimais ao exibir.

### Tratamento de Erros

- **Divisão por zero**: Caso o usuário tente dividir um número por zero, o programa interrompe a operação e exibe uma mensagem de erro.

- **Operação inválida**: Se o usuário inserir um operador que não seja reconhecido, o programa retorna uma mensagem indicando uma operação inválida.

## ✨ Melhorias Futuras

- [ ] Adicionar suporte para operações avançadas, como exponenciação e radiciação.
- [ ] Implementar uma interface gráfica (GUI) para tornar o uso mais intuitivo.
- [ ] Melhorar o tratamento de erros com mensagens mais detalhadas.
