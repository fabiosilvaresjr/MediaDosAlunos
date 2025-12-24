# 🧮 Calculadora de Média Escolar

> Projeto focado em **Lógica Condicional** e operações matemáticas básicas com JavaScript.

Esta aplicação simples recebe o nome e duas notas de um aluno, calcula a média aritmética e determina automaticamente se o aluno foi **Aprovado** ou **Reprovado** com base em uma nota de corte (Média 7).

## 🚀 Tecnologias Utilizadas

- **HTML5** (Estrutura da página)
- **JavaScript** (Lógica matemática e condicional)

## ⚙️ Funcionalidades

- [x] **Entrada de Dados:** Captura o nome e as notas do usuário via `prompt`.
- [x] **Conversão de Tipos:** Tratamento dos dados de entrada usando `Number()` para garantir que o sistema some números, e não concatene textos.
- [x] **Cálculo Matemático:** Realiza a média aritmética `(n1 + n2) / 2`.
- [x] **Tomada de Decisão:** Utiliza a estrutura condicional `if/else` para definir o status de aprovação.
- [x] **Feedback:** Exibe o resultado final e a média calculada diretamente na tela.

## 🧠 Aprendizados e Destaques do Código

Este projeto consolidou conceitos essenciais de programação:

1. **Coerção de Tipos (Type Casting):** Aprendi que o `prompt` sempre retorna um texto (String). Para fazer contas, é obrigatório converter para número usando `Number()` ou `parseFloat()`. Sem isso, o código daria erro de cálculo.
2. **Estruturas Condicionais (`if/else`):** Implementação da lógica de aprovação:
   - *SE* a média for maior ou igual a 7 -> Aprovado.
   - *SENÃO* -> Reprovado.
3. **Precedência de Operadores:** Uso correto dos parênteses `(nota1 + nota2) / 2` para garantir que a soma aconteça antes da divisão.

## 📦 Como rodar o projeto

1. Clone este repositório.
2. Abra o arquivo `index.html` no navegador.
3. Insira os dados solicitados e veja se você passaria de ano!

---
Desenvolvido por **Fabio** durante estudos de Lógica de Programação.
