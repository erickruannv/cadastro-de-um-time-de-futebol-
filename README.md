# Sistema de Cadastro de Time de Futebol

Este projeto consiste em um sistema simples de **cadastro de jogadores de futebol**, desenvolvido na linguagem **Pascal**. Ele foi criado com o objetivo de aplicar os princípios básicos da **Engenharia de Software**, contemplando a análise de requisitos, validação de dados e organização estrutural de código.

## 💡 Objetivo

Criar um sistema funcional que permita o cadastro de jogadores de um time de futebol, garantindo que os dados inseridos estejam corretos e sigam critérios pré-estabelecidos.

## ⚙️ Funcionalidades

- ✅ Cadastro de até 5 jogadores
- ✅ Validação de e-mails contendo o caractere `@`
- ✅ Aceita somente jogadores com mais de 16 anos
- ✅ Escolha da categoria entre 6 opções:
  - Categoria de base
  - Categoria profissional
  - Sub 20
  - Sub 19
  - Sub 18
  - Sub 17
- ✅ Exibição dos dados válidos ao final da execução

## 📋 Requisitos Funcionais

- **RF01**: O sistema deve permitir o cadastro de cinco jogadores.  
- **RF02**: O sistema deve validar se o e-mail contém o caractere `@`.  
- **RF03**: O sistema deve aceitar apenas jogadores com idade superior a 16 anos.  
- **RF04**: O sistema deve permitir a seleção de uma categoria entre seis opções pré-definidas.  
- **RF05**: O sistema deve exibir os dados cadastrados ao final da execução.

## 🧪 Plano de Testes

| Teste | Nome           | E-mail            | Idade | Categoria | Resultado Esperado               |
|-------|----------------|-------------------|-------|-----------|----------------------------------|
| T1    | João Silva     | joao@email.com    | 17    | 1         | Cadastro realizado               |
| T2    | Maria Souza    | mariasemarro.com  | 18    | 2         | Erro no e-mail                   |
| T3    | Pedro Andrade  | pedro@email.com   | 15    | 3         | Erro na idade                    |
| T4    | Ana Costa      | ana@email.com     | 20    | 9         | Erro na categoria                |
| T5    | Bruno Oliveira | bruno@email.com   | 22    | 2         | Cadastro realizado               |

## 🛠️ Tecnologias Utilizadas

- **Linguagem**: Pascal  
- **Recursos**:
  - Vetores para armazenamento de dados
  - Laços de repetição (`for`, `while`)
  - Condicionais (`if`, `else`)
  - Estruturas de validação

## 🧑‍💻 Autoria

Desenvolvido por:

- **Erick Ruan Nunes Vieira**

Colaboradores:

- Mateus Heitor da Silva Sá  
- Cassio Emanuel Santos Sousa  
- Bilsã Ferreira de Carvalho Júnior

## 🏫 Informações Acadêmicas

- **Disciplina**: Algoritmo e Programação  
- **Curso**: Engenharia de Software  
- **Professor(a)**: Amélia Acácia de Miranda Batista  
- **Instituição**: Centro Universitário Santo Agostinho – Teresina/PI

---

📁 Este projeto é acadêmico e tem fins didáticos.

