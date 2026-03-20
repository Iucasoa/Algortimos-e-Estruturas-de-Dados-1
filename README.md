# 🛒 TechStore Manager - Sistema de Gerenciamento de Inventário

Este projeto foi desenvolvido como trabalho prático para a disciplina de **Estrutura de Dados I** na **UFERSA**. O objetivo é aplicar conceitos de alocação dinâmica, estruturas de dados lineares e persistência de dados em arquivos.

## 🚀 Funcionalidades

O sistema simula o gerenciamento de uma loja de informática com dois níveis de acesso:

- **Módulo de Usuário:** Cadastro de novos usuários com validação de e-mail e sistema de login.
- **Módulo de Inventário (Restrito):** - Cadastro, edição e exclusão de produtos.
  - Busca de itens por código.
  - Ordenação dinâmica por preço (Crescente/Decrescente).
  - Ordenação alfabética por nome.
- **Persistência de Dados:** Todos os dados são salvos em arquivos binários (`usuarios.dat` e `produtos.dat`), garantindo que as informações não sejam perdidas ao fechar o programa.

## 🛠️ Conceitos de Estrutura de Dados Aplicados

- **Listas Encadeadas Simples:** Utilizadas para gerenciar tanto a lista de usuários quanto a de produtos, permitindo inserção e remoção dinâmica de nós.
- **Alocação Dinâmica de Memória:** Uso de `malloc` e `free` para gerenciamento eficiente da memória RAM durante a execução.
- **Algoritmos de Ordenação:** Implementação do algoritmo **Bubble Sort** para organizar a lista encadeada com base em diferentes critérios (preço e nome).
- **Manipulação de Arquivos:** Uso das funções `fwrite` e `fread` para armazenamento de structs em disco.



## 💻 Tecnologias Utilizadas

- **Linguagem:** C
- **IDE recomendada:** Dev-C++ (projeto inclui arquivo `.dev`)
- **Compilador:** GCC

## 📁 Estrutura do Projeto

- `Main projeto III.c`: Ponto de entrada do programa e lógica do menu.
- `projeto III.c`: Implementação das funções de manipulação das listas e arquivos.
- `tech_store.h`: Definição das `structs` e protótipos das funções.
- `*.dat`: Arquivos de base de dados (gerados na execução).

## 🔧 Como Executar

1. Clone o repositório:
   ```bash
   git clone [https://github.com/lucasoa/NOME-DO-REPOSITORIO.git](https://github.com/lucasoa/NOME-DO-REPOSITORIO.git)
