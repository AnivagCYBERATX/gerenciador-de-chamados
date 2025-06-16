# Projeto Estrutura de Dados - Gerenciamento de Chamados

Este projeto foi desenvolvido em linguagem C com o objetivo de praticar os conceitos de Estrutura de Dados, especialmente **listas encadeadas**. Ele simula um sistema de atendimento de chamados que são organizados por níveis de prioridade (1 - Alta, 2 - Média, 3 - Baixa).

# Funcionalidades

- Inserção de chamados com descrição e prioridade.
- Armazenamento dos chamados em uma lista encadeada ordenada por prioridade.
- Atendimento e remoção do chamado mais prioritário.
- Exibição da lista de chamados pendentes.

# Como compilar e executar

# Compilar
bash
gcc estruturadados.c -o chamados


# Executar
bash
./chamados
`

# Estrutura do Código

- `Chamado`: estrutura que representa um chamado (descrição, prioridade, ponteiro para o próximo).
- `inserirChamado()`: insere um novo chamado na posição correta da lista com base na prioridade.
- `atenderChamado()`: remove o primeiro chamado da lista (maior prioridade).
- `listarChamados()`: exibe todos os chamados pendentes.

## Requisitos

- Compilador GCC ou compatível
- Sistema com suporte a terminal/console
- Visual Studio code (EXEMPLO)
## Autor

Projeto acadêmico desenvolvido para a disciplina de Estrutura de Dados
Feito por Matheus Dos Santos Gavina em conjunto com João Victor.
