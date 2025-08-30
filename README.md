# git-hooks-scripts

> Scripts for automating and standardizing Git workflows.  
> Scripts de hooks para automação e padronização de fluxos Git.

---

## English

This repository contains my hook scripts to help with tasks like linting, testing, formatting, and validation in Git projects. The scripts can be used with Husky, pre-commit, or directly in the `.git/hooks` folder.

### How to use

1. Clone this repository.
2. Copy the desired scripts to your project's `.git/hooks` folder or configure via Husky/pre-commit.
3. Make the scripts executable (Linux/macOS):  
   `chmod +x script-name.sh`

### Example hooks

- `pre-commit`: runs lint and tests before commit.
- `pre-push`: validates integration before pushing to remote.
- `commit-msg`: checks commit message format.

## Português

Este repositório contém meus scripts de hooks para facilitar tarefas como lint, testes, formatação e validação em projetos Git. Os scripts podem ser usados com Husky, pre-commit, ou diretamente na pasta `.git/hooks`.

### Como usar

1. Clone este repositório.
2. Copie os scripts desejados para a pasta `.git/hooks` do seu projeto ou configure via Husky/pre-commit.
3. Dê permissão de execução aos scripts (Linux/macOS):  
   `chmod +x nome-do-script.sh`

### Exemplos de hooks

- `pre-commit`: executa lint e testes antes do commit.
- `pre-push`: valida integração antes de enviar para o remoto.
- `commit-msg`: verifica padrão da mensagem de commit.

## License / Licença

MIT
