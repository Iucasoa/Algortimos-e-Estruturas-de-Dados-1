# 🛒 TechStore Manager - Sistema de Gerenciamento de Inventário

[![Linguagem](https://img.shields.io/badge/Linguagem-C-blue.svg)](https://www.iso.org/standard/74528.html)
[![Dev-C++](https://img.shields.io/badge/IDE-Dev--C%2B%2B-ff69b4.svg)]()
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Completo-brightgreen.svg)]()

## 📖 Descrição

Projeto prático desenvolvido para a disciplina de **Estrutura de Dados I** da **UFERSA**. O TechStore Manager é um sistema de gerenciamento de inventário que implementa conceitos fundamentais de estruturas de dados lineares, alocação dinâmica de memória e persistência de dados.

## 🚀 Funcionalidades

O sistema simula o gerenciamento de uma loja de informática com dois níveis de acesso:

### Módulo de Usuário
- Cadastro de novos usuários com validação de e-mail
- Sistema de autenticação robusto
- Gerenciamento seguro de credenciais

### Módulo de Inventário (Restrito)
- ✅ Cadastro, edição e exclusão de produtos
- 🔍 Busca de itens por código
- 📊 Ordenação dinâmica por preço (Crescente/Decrescente)
- 🔤 Ordenação alfabética por nome
- 💾 Persistência de dados em arquivos binários

## 🛠️ Conceitos de Estrutura de Dados Aplicados

| Conceito | Descrição |
|----------|-----------|
| **Listas Encadeadas Simples** | Gerenciamento dinâmico de usuários e produtos com inserção e remoção de nós |
| **Alocação Dinâmica** | `malloc` e `free` para gerenciamento eficiente de memória |
| **Algoritmo Bubble Sort** | Ordenação de lista encadeada por preço e nome |
| **I/O de Arquivos** | `fwrite` e `fread` para persistência de structs em disco |

## 💻 Tecnologias Utilizadas

- **Linguagem:** C (C99)
- **Compilador:** GCC
- **IDE Recomendada:** Dev-C++
- **Gerenciamento de Memória:** malloc/free
- **Persistência:** Arquivos binários

## 📋 Pré-requisitos

- **GCC** ou equivalente (compilador C)
- **Git** para clonar o repositório
- **Sistema Operacional:** Windows, Linux ou macOS
- **Espaço em disco:** ~5MB

## 📁 Estrutura do Projeto

```
Algortimos-e-Estruturas-de-Dados-1/
├── Main projeto III.c       # Ponto de entrada e lógica do menu
├── projeto III.c            # Implementação das funções principais
├── tech_store.h             # Definições de structs e protótipos
├── usuarios.dat             # Base de dados de usuários (gerado)
├── produtos.dat             # Base de dados de produtos (gerado)
└── README.md                # Documentação do projeto
```

## 🔧 Como Compilar e Executar

### Opção 1: Usando GCC (Recomendado)

```bash
# Clone o repositório
git clone https://github.com/Iucasoa/Algortimos-e-Estruturas-de-Dados-1.git
cd Algortimos-e-Estruturas-de-Dados-1

# Compile os arquivos
gcc -o techstore "Main projeto III.c" "projeto III.c" -Wall -Wextra

# Execute o programa
./techstore
```

### Opção 2: Usando Dev-C++

1. Abra o projeto `.dev` incluído no repositório
2. Clique em `Ferramentas` → `Compilar`
3. Execute pressionando `F10` ou clicando em `Executar`

## 📝 Como Usar

```
1. Ao iniciar, escolha entre:
   - [1] Criar novo usuário
   - [2] Fazer login
   
2. Após login (apenas admin):
   - Gerenciar inventário
   - Adicionar/remover produtos
   - Visualizar relatórios
   
3. Dados são salvos automaticamente ao sair
```

## 🎓 Aprendizados Principais

- Implementação prática de listas encadeadas
- Gerenciamento manual de memória em C
- Algoritmos de busca e ordenação
- Serialização e persistência de dados
- Boas práticas em programação C

## 📊 Exemplo de Saída

```
========== TechStore Manager ==========
Bem-vindo! Escolha uma opção:
1. Criar Usuário
2. Fazer Login
3. Sair

> 2
Email: user@example.com
Senha: ****
✓ Login realizado com sucesso!

===== Menu Principal =====
1. Cadastrar Produto
2. Listar Produtos
3. Buscar Produto
4. Sair
```

## 🤝 Contribuindo

Este é um projeto acadêmico, mas sugestões e melhorias são bem-vindas!

1. Faça um Fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 👨‍💻 Autor

**Lucas Oassoa**
- GitHub: [@Iucasoa](https://github.com/Iucasoa)
- Universidade: UFERSA

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 📧 Suporte

Encontrou algum bug? Abra uma [Issue](https://github.com/Iucasoa/Algortimos-e-Estruturas-de-Dados-1/issues) para reportá-lo.

## 📚 Recursos Adicionais

- [Tutorial de Listas Encadeadas](https://www.geeksforgeeks.org/linked-list-in-c/)
- [Documentação de Alocação Dinâmica em C](https://www.tutorialspoint.com/c_standard_library/c_function_malloc.htm)
- [Bubble Sort Explicado](https://www.programiz.com/dsa/bubble-sort)

---

**Última atualização:** 2026-03-20 13:08:54