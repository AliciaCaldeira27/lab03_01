# Lab03 - Testes Automatizados com Jest e TypeScript

Este repositório apresenta a implementação da **Atividade I do Laboratório 03** da trilha **Web Academy CI/CD**, com foco na utilização de **testes automatizados**, **TypeScript**, **Jest** e **análise de cobertura de código**, integrada a um fluxo de **Integração Contínua (CI)** no GitHub Actions.

---

## Objetivo da Atividade

A atividade teve como objetivo:

- Configurar um ambiente de testes automatizados utilizando **Jest** com **TypeScript**.
- Implementar uma função simples e seu respectivo teste unitário.
- Medir a **cobertura de código** gerada pelos testes.
- Integrar a execução dos testes a um **pipeline de CI** no GitHub Actions, garantindo que o código seja validado a cada `push`.

---

## Implementação Realizada

Durante a atividade foram realizadas as seguintes configurações e implementações:

- Criação de um projeto Node.js com suporte a **TypeScript**, a partir da geração do arquivo `tsconfig.json`.
- Instalação e configuração do **Jest** integrado ao TypeScript por meio do **ts-jest**, definindo o ambiente de teste como `node` no arquivo `jest.config.ts`.
- Criação do arquivo `src/hello_world.ts`, contendo a função `hello`, responsável por retornar uma saudação padrão e permitindo a personalização da mensagem.
- Implementação do teste unitário em `src/hello_world.test.ts`, validando o comportamento esperado da função `hello`.
- Configuração do script `"test": "jest --coverage"` no `package.json`, permitindo a execução dos testes juntamente com o relatório de cobertura.
- Geração automática de relatórios de cobertura, possibilitando a visualização dos arquivos e linhas cobertas pelos testes.
- Estruturação de um workflow no **GitHub Actions** para executar a instalação das dependências, rodar os testes e validar o projeto a cada envio para o repositório, utilizando diferentes versões do Node.js.

---

## Resultados

Com a conclusão da atividade, foi possível: Garantir que o código desenvolvido seja testado automaticamente, verificar a qualidade dos testes por meio da cobertura de código e integrar boas práticas de **Integração Contínua** ao fluxo de desenvolvimento, tornando o repositório mais confiável e alinhado com práticas profissionais de CI/CD.

---
## Repositório

O código encontra-se disponível no repositório GitHub - **master**:

[https://github.com/AliciaCaldeira27/lab03_01](https://github.com/AliciaCaldeira27/lab03_01)

---

### Discente: Alicia Caldeira  
### Curso: Web Academy - UFAM
