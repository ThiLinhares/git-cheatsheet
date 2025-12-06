# 📚 Guia de Estudos e Fluxo de Trabalho Git

![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)

Este repositório serve como uma base de conhecimento e guia de referência rápida para comandos essenciais do **Git** e fluxo de trabalho no **GitHub**. O objetivo é documentar as melhores práticas de versionamento utilizadas em projetos de desenvolvimento e QA.

## 🚀 Comandos Essenciais

### Configuração Inicial
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@exemplo.com"

### Iniciando e Clonando
| Comando | Descrição |
| :--- | :--- |
| `git init` | Inicia um novo repositório local. |
| `git clone [url]` | Baixa um projeto e todo o seu histórico de versão. |

### Fluxo Diário (Stage & Commit)
# Adicionar alterações ao palco (staging area)
git add .

# Salvar alterações com uma mensagem descritiva
git commit -m "feat: adiciona nova funcionalidade de login"

### Trabalhando com Branches
Para não quebrar a branch principal (`main`), utilizamos branches para novas features ou correções.

# Criar e mudar para uma nova branch
git checkout -b feature/nova-funcionalidade

# Listar branches
git branch

# Voltar para a main
git checkout main

### Sincronizando com o Repositório Remoto
# Enviar alterações para o GitHub
git push origin feature/nova-funcionalidade

# Trazer atualizações do remoto para o local
git pull origin main

## 🤝 Padrões de Commit (Conventional Commits)

Adoto o padrão de **Conventional Commits** para manter o histórico organizado:

- `feat`: Uma nova funcionalidade.
- `fix`: Correção de um bug.
- `docs`: Alterações apenas na documentação.
- `style`: Formatação, falta de ponto e vírgula, etc (sem alteração de código).
- `refactor`: Refatoração de código em produção.
- `test`: Adição ou refatoração de testes.

## 🔗 Referências Úteis

- [Documentação Oficial do Git](https://git-scm.com/doc)
- [Guia Prático de Markdown](https://www.markdownguide.org/)

---
Desenvolvido por **Thiago Linhares**
