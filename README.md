# 📇 Lista de Contatos em C

Este é um projeto simples de gerenciamento de contatos feito em linguagem C. O programa permite adicionar, editar, buscar, remover e listar contatos, com persistência em um arquivo binário.

## 💡 Funcionalidades

- ✅ Adicionar novos contatos com verificação de duplicidade de código
- 🔍 Buscar contato por **código** ou **nome**
- 📋 Exibir todos os contatos cadastrados
- ✏️ Editar informações de um contato
- ❌ Remover um contato da lista
- 💾 Salvar e carregar contatos de um arquivo binário (`listasalva.dat`)

## 🛠️ Tecnologias utilizadas

- Linguagem C
- Lista encadeada dinâmica
- Manipulação de arquivos binários

## 📂 Estrutura do Projeto

- `main.c` – Interface do usuário (menu)
- `listaCTT.c` – Implementação das funções da lista
- `listaCTT.h` – Declarações de estruturas e funções

## ▶️ Como executar

1. **Compile os arquivos** com um compilador C:
   ```bash
   gcc main.c listaCTT.c -o lista_contatos
   ```

2. **Execute o programa**:
   ```bash
   ./lista_contatos
   ```

3. A lista será carregada automaticamente do arquivo `listasalva.dat`, se existir.

## 💾 Persistência de dados

- Os contatos são salvos automaticamente em um arquivo binário (`listasalva.dat`) ao encerrar o programa.
- Se a lista estiver vazia, qualquer arquivo anterior será apagado para evitar inconsistências.

## 🧪 Exemplo de uso

```
========== Lista de contatos ACME S.A ==========

MENU:

1 - Inserir novo contato
2 - Exibir lista de contatos
3 - Buscar contato por código
4 - Buscar contato por nome
5 - Editar contato
6 - Remover contato
7 - Encerrar programa
```

## Informações adicionais

Projeto feito na IDE "Code Blocks"

Repositório possui arquivos que facilitam a execução
na IDE "Code Blocks"

## 👨‍💻 Autores

Desenvolvido como projeto de prática em linguagem C por Luan Patrique e Yuri Forkel.

## Imagens

![Menu principal](/menuLista.png)

Menu principal

![Exemplo de visualização de lista](/viewLista.png)
