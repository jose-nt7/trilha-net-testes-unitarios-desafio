# 🧪 Desafio DIO | Testes Unitários com C#

![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET%206-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![xUnit](https://img.shields.io/badge/xUnit-Testes%20Unit%C3%A1rios-blue?style=for-the-badge)

## 📌 Sobre o Projeto

Este projeto foi desenvolvido como parte do desafio prático da **Trilha .NET da Digital Innovation One (DIO)**, com o objetivo de aplicar conceitos de testes unitários utilizando C#, .NET e o framework xUnit.

O desafio consiste em implementar testes automatizados para validar funcionalidades relacionadas à manipulação de listas de números inteiros e operações com strings.

A implementação busca contribuir para a qualidade, confiabilidade e manutenção do software, identificando possíveis falhas e verificando o comportamento esperado dos métodos.

## 🚀 Tecnologias Utilizadas

- **C#** — Linguagem de programação.
- **.NET 6** — Plataforma de desenvolvimento.
- **xUnit** — Framework para testes unitários.
- **Visual Studio Code** — Ambiente de desenvolvimento.
- **Git e GitHub** — Versionamento e gerenciamento do código.

## 📂 Estrutura do Projeto

O projeto está dividido em dois componentes principais:

**TestesUnitarios.Desafio.Console**

Contém as classes responsáveis pelas funcionalidades do sistema:

- `ValidacoesLista.cs`
- `ValidacoesString.cs`

**TestesUnitarios.Desafio.Tests**

Contém as classes responsáveis pela execução dos testes automatizados:

- `ValidacoesListaTests.cs`
- `ValidacoesStringTests.cs`

## ✅ Testes Implementados

### Validações de Listas

Foram implementados e validados seis testes unitários:

1. Remover números negativos de uma lista.
2. Verificar se o número 9 está presente na lista.
3. Verificar se o número 10 não está presente na lista.
4. Multiplicar os elementos de uma lista por 2.
5. Retornar o maior número de uma lista.
6. Retornar o menor número de uma lista.

### Validações de Strings

Foram implementados quatro testes unitários:

1. Verificar a quantidade de caracteres da palavra "Matrix".
2. Verificar se determinada palavra existe em um texto.
3. Verificar se determinada palavra não existe em um texto.
4. Verificar se um texto termina com uma palavra específica.

## 🧠 Conceitos Aplicados

Durante o desenvolvimento do desafio, foram aplicados conceitos como:

- Testes unitários automatizados.
- Organização de testes com o padrão AAA (Arrange, Act, Assert).
- Utilização dos atributos `[Fact]` do xUnit.
- Validação de resultados com `Assert.Equal()`.
- Verificação de condições com `Assert.True()` e `Assert.False()`.
- Testes de cenários positivos e negativos.

## ⚙️ Como Executar o Projeto

### Pré-requisitos

- .NET SDK compatível com o projeto.
- Git instalado.

### 1. Clonar o repositório

```bash
git clone https://github.com/jose-nt7/trilha-net-testes-unitarios-desafio.git
```

### 2. Acessar o diretório

```bash
cd trilha-net-testes-unitarios-desafio
```

### 3. Restaurar as dependências

```bash
dotnet restore
```

### 4. Executar os testes

```bash
dotnet test
```

O comando executará os testes unitários e apresentará os resultados no terminal.

## 📊 Resultados

O projeto contempla **10 testes unitários**, distribuídos entre validações de listas e strings.

- 6 testes de listas aprovados.
- 4 testes de strings implementados, aguardando validação final.

## 🎯 Objetivo de Aprendizagem

Este desafio permitiu aprofundar conhecimentos em desenvolvimento C# e testes automatizados, reforçando a importância de validar funcionalidades e prevenir regressões durante a evolução de sistemas.

## 📚 Referência

Projeto baseado no desafio educacional da **Digital Innovation One (DIO)** — Trilha .NET: Testes Unitários com C#.

🔗 [Digital Innovation One](https://www.dio.me/)

---

Desenvolvido como parte dos estudos e aprimoramento profissional em desenvolvimento de software com C# e .NET.
