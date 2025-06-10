# Calculadora Simples em Java com Testes JUnit

Este projeto demonstra uma calculadora simples implementada em Java, com testes automatizados utilizando JUnit.

## Funcionalidades

- Soma
- Subtração
- Multiplicação
- Divisão (com tratamento de divisão por zero)

## Estrutura do Projeto


Testes-em-JUnit/
├── src/
│   └── Calculadora.java
├── test/
│   └── CalculadoraTest.java
├── lib/
│   └── junit-platform-console-standalone-1.10.0.jar
├── out/
│   └── (arquivos compilados)
└── README.md


## Como Executar

### 1. Compilar o projeto

Abra o terminal na raiz do projeto e execute:

sh
javac -cp "lib/junit-platform-console-standalone-1.10.0.jar" -d out src/Calculadora.java test/CalculadoraTest.java


### 2. Rodar os testes

sh
java -jar lib/junit-platform-console-standalone-1.10.0.jar --class-path out --scan-class-path


## Requisitos

- Java 8 ou superior
- JUnit Platform Console Standalone (já incluso na pasta lib)

## Observações

- O método de divisão lança uma exceção se o divisor for zero.
- Os testes estão localizados em test/CalculadoraTest.java.

## Autor

João Nicolau Fill da Silva e Diogo Demetrius