# Projeto 1 - Correção de Erros

##  Desenvolvedor 

Henrique Bassan Rebechi (22.223.083-1)

##  Problemas corrigidos

- Remoção da quebra de linha (`\n`) nas strings de categoria e descrição
- Validação do valor de prioridade entre 1 e 10
- Tratamento de erros na função `main`
- Uso de `#define` para tamanhos de categoria e descrição

##  Funcionalidades implementadas (enunciado)

- Filtro por categoria na listagem de tarefas
- Exportação de tarefas para arquivo `.txt`
- Salvamento e carregamento com nome de arquivo binário customizado

##  Como compilar

```bash
gcc main.c tarefas.c -o tarefas
