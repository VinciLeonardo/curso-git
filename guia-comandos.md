# Guia Prático de Git e GitHub

Este guia reúne os principais comandos e boas práticas para versionamento com Git.

## 1. Configurações Iniciais
```bash
git config --global user.name "Seu Nome"
git config --global user.email "seu.email@exemplo.com"
```

## 2. Início e Clonagem
```bash
git init
git clone <url-do-repositorio>
```

## 3. Fluxo de Trabalho Básico
```bash
git status
git add .
git commit -m "feat: mensagem do commit"
git push origin <branch>
```

## 4. Branches
```bash
git branch
git checkout -b <nova-branch>
git checkout <branch>
git merge <branch>
```

## 5. Boas Práticas de Commits
- Use mensagens descritivas seguindo Conventional Commits (`feat`, `fix`, `docs`, `refactor`).
- Faça commits atômicos com escopos bem definidos.
- Utilize trailers como `Co-authored-by:` para colaboração em equipe.

## 6. Atalhos �teis
- git log --graph --oneline para visualizar hist�rico em �rvore.
- git stash para salvar altera��es tempor�rias.

## 7. Perguntas Frequentes (FAQ)
- **Como desfazer o ultimo commit mantendo alteracoes?** git reset --soft HEAD~1
