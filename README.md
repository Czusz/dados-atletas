# 🏋️‍♂️ Projeto: Dados de Atletas

Este projeto em JavaScript tem como objetivo receber informações de um atleta e calcular parâmetros como **IMC**, **categoria** e **média válida de notas**, com base nas regras de uma competição.

## 📌 Funcionalidades

- Cadastrar dados de um atleta (nome, idade, peso, altura, notas)
- Calcular e exibir:
  - Categoria (de acordo com a idade)
  - IMC (Índice de Massa Corporal)
  - Média válida (ignorando a maior e menor nota)

## 🛠️ Tecnologias Utilizadas

- JavaScript (ES6)
- Node.js para execução local (opcional)

## 📋 Regras de Negócio

### 📍 Categorias por idade:
| Faixa Etária     | Categoria       |
|------------------|-----------------|
| 9 a 11 anos      | Infantil        |
| 12 a 13 anos     | Juvenil         |
| 14 a 15 anos     | Intermediário   |
| 16 a 30 anos     | Adulto          |
| Demais idades    | Sem categoria   |

### 📍 Cálculo do IMC:
> **Fórmula**: `IMC = peso / (altura²)`

### 📍 Cálculo da Média Válida:
> Remove a **maior** e a **menor** nota e calcula a média das notas restantes.

## ▶️ Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/dados-atletas.git
cd dados-atletas
