# Roteiro de Aprendizado - Git e Controle de Versão

Este roteiro foi desenvolvido para guiar você no aprendizado de Git e controle de versão, ferramentas essenciais para qualquer desenvolvedor profissional.

## 📋 Estrutura do Roteiro

O roteiro está organizado em módulos progressivos. Cada módulo deve ser concluído antes de avançar para o próximo.

---

## 🎯 Módulo 1: Fundamentos de Controle de Versão

### Objetivos
- Compreender o que é controle de versão
- Entender por que é essencial para desenvolvimento
- Conhecer diferentes sistemas de controle de versão

### Tópicos
1. **O que é Controle de Versão?**
   - Definição e importância
   - Histórico de mudanças
   - Trabalho em equipe
   - Backup e recuperação

2. **Tipos de Sistemas de Controle de Versão**
   - Sistemas locais (RCS, CVS)
   - Sistemas centralizados (SVN, Perforce)
   - Sistemas distribuídos (Git, Mercurial)

3. **Por que Git?**
   - Popularidade e adoção
   - Performance
   - Branching e merging
   - Comunidade ativa

### Recursos Recomendados
- [Git - Book Oficial](https://git-scm.com/book/pt/v2)
- [Atlassian Git Tutorial](https://www.atlassian.com/git/tutorials)
- [YouTube - Mayk Brito](https://www.youtube.com/@maykbrito)

### Exercícios Práticos
- Pesquisar sobre histórico de controle de versão
- Identificar situações onde controle de versão seria útil
- Comparar diferentes sistemas de controle de versão

---

## 🔧 Módulo 2: Instalação e Configuração

### Objetivos
- Instalar Git no seu computador
- Configurar Git corretamente
- Entender o ambiente Git

### Tópicos
1. **Instalação do Git**
   - Windows (Git for Windows)
   - macOS (Homebrew ou instalador)
   - Linux (apt, yum, dnf)

2. **Configuração Inicial**
   - `git config --global user.name`
   - `git config --global user.email`
   - `git config --global core.editor`
   - Verificar configurações

3. **Primeiros Comandos**
   - `git --version`
   - `git help`
   - `git init`

### Exercícios Práticos
- Instalar Git no seu sistema operacional
- Configurar seu nome e email
- Criar um repositório de teste
- Verificar as configurações

---

## 📝 Módulo 3: Comandos Básicos

### Objetivos
- Dominar os comandos fundamentais do Git
- Entender o ciclo de vida dos arquivos
- Aprender a fazer commits

### Tópicos
1. **Ciclo de Vida dos Arquivos**
   - Untracked (não rastreado)
   - Unmodified (não modificado)
   - Modified (modificado)
   - Staged (preparado)

2. **Comandos Essenciais**
   - `git init` - Inicializar repositório
   - `git status` - Verificar estado
   - `git add` - Adicionar ao staging
   - `git commit` - Salvar mudanças
   - `git log` - Ver histórico

3. **Boas Práticas de Commit**
   - Mensagens claras e concisas
   - Commits atômicos
   - Convenção de mensagens

### Exercícios Práticos
- Criar um projeto simples
- Fazer commits significativos
- Visualizar o histórico de commits
- Praticar diferentes cenários de modificação

---

## 🌿 Módulo 4: Branching e Merging

### Objetivos
- Compreender o conceito de branches
- Aprender a criar e gerenciar branches
- Dominar o processo de merge

### Tópicos
1. **Conceito de Branch**
   - O que é um branch
   - Branch master/main
   - Por que usar branches

2. **Comandos de Branch**
   - `git branch` - Listar branches
   - `git branch <nome>` - Criar branch
   - `git checkout <nome>` - Trocar branch
   - `git switch <nome>` - Alternar branch
   - `git merge <nome>` - Unir branches

3. **Resolvendo Conflitos**
   - O que são conflitos
   - Como identificar conflitos
   - Como resolver conflitos
   - Ferramentas de merge

### Exercícios Práticos
- Criar branches para diferentes features
- Fazer modificações em branches separados
- Praticar merge de branches
- Resolver conflitos de merge

---

## 🔄 Módulo 5: Trabalho Remoto

### Objetivos
- Conectar repositórios locais com remotos
- Aprender a enviar e receber mudanças
- Trabalhar com GitHub/GitLab

### Tópicos
1. **Repositórios Remotos**
   - O que são repositórios remotos
   - GitHub, GitLab, Bitbucket
   - Criar conta em plataforma

2. **Comandos Remotos**
   - `git remote` - Gerenciar remotos
   - `git remote add` - Adicionar remoto
   - `git push` - Enviar mudanças
   - `git pull` - Receber mudanças
   - `git clone` - Clonar repositório

3. **Fluxo de Trabalho**
   - Fork e Clone
   - Branch e Commit
   - Push e Pull Request
   - Code Review

### Exercícios Práticos
- Criar conta no GitHub
- Criar um repositório remoto
- Conectar repositório local com remoto
- Fazer push e pull
- Criar um Pull Request

---

## 🗂️ Módulo 6: Operações Avançadas

### Objetivos
- Aprender comandos avançados do Git
- Entender rebase e cherry-pick
- Dominar ferramentas de recuperação

### Tópicos
1. **Rebase vs Merge**
   - Diferenças entre rebase e merge
   - Quando usar cada um
   - Vantagens e desvantagens

2. **Comandos Avançados**
   - `git rebase` - Rebase de commits
   - `git cherry-pick` - Selecionar commits
   - `git stash` - Salvar mudanças temporariamente
   - `git reset` - Resetar commits
   - `git revert` - Reverter commits

3. **Recuperação de Dados**
   - `git reflog` - Histórico de referências
   - Recuperar commits perdidos
   - Desfazer mudanças

### Exercícios Práticos
- Praticar rebase de commits
- Usar stash para mudanças temporárias
- Recuperar commits deletados
- Comparar rebase vs merge

---

## 🏗️ Módulo 7: Fluxos de Trabalho

### Objetivos
- Conhecer diferentes fluxos de trabalho
- Escolher o fluxo adequado para o projeto
- Implementar boas práticas de equipe

### Tópicos
1. **Fluxos de Trabalho Comuns**
   - Git Flow
   - GitHub Flow
   - GitLab Flow
   - Trunk-Based Development

2. **Estratégias de Branching**
   - Feature branches
   - Release branches
   - Hotfix branches
   - Environment branches

3. **Boas Práticas de Equipe**
   - Code review
   - CI/CD integration
   - Convenções de nomenclatura
   - Documentação

### Exercícios Práticos
- Implementar Git Flow em um projeto
- Praticar code review
- Configurar branches de ambiente
- Documentar o fluxo de trabalho

---

## 🛠️ Módulo 8: Ferramentas e Integrações

### Objetivos
- Conhecer ferramentas gráficas para Git
- Integrar Git com IDEs
- Automatizar processos com Git

### Tópicos
1. **Interfaces Gráficas**
   - GitHub Desktop
   - GitKraken
   - Sourcetree
   - VS Code Git integration

2. **Integração com IDEs**
   - VS Code
   - IntelliJ IDEA
   - Visual Studio
   - Eclipse

3. **Git Hooks**
   - O que são hooks
   - Pre-commit hooks
   - Pre-push hooks
   - Automação com scripts

### Exercícios Práticos
- Usar uma interface gráfica
- Integrar Git com seu IDE
- Criar um hook simples
- Automatizar uma tarefa com hooks

---

## 🎮 Módulo 9: Projetos Práticos

### Objetivos
- Aplicar todos os conceitos aprendidos
- Desenvolver projetos reais usando Git
- Ganhar experiência prática

### Projetos Sugeridos
1. **Portfólio Pessoal**
   - Criar repositório no GitHub
   - Usar branches para diferentes seções
   - Implementar Git Flow
   - Configurar GitHub Pages

2. **Projeto em Equipe**
   - Trabalhar com outra pessoa
   - Usar Pull Requests
   - Resolver conflitos
   - Fazer code review

3. **Contribuição Open Source**
   - Encontrar projeto open source
   - Fazer fork do projeto
   - Criar branch para contribuição
   - Submeter Pull Request

4. **Automatização com Git**
   - Configurar hooks para linting
   - Automatizar testes
   - Integrar com CI/CD

---

## 📚 Recursos Complementares

### Livros Recomendados
- "Pro Git" - Scott Chacon e Ben Straub
- "Version Control with Git" - Jon Loeliger
- "Git Pocket Guide" - Richard E. Silverman

### Canais do YouTube
- Mayk Brito
- Rocket Seat
- Alura
- Felipão Dev

### Plataformas de Prática
- GitHub Learning Lab
- GitLab Learn
- Atlassian Git Tutorial
- Learn Git Branching (interativo)

---

## 🎯 Dicas de Estudo

1. **Pratique diariamente** - Use Git em todos os seus projetos
2. **Não tenha medo de errar** - Git é muito permissivo, você pode sempre voltar atrás
3. **Entenda o porquê** - Não apenas memorize comandos, entenda o conceito
4. **Use a documentação** - `git help` é seu melhor amigo
5. **Participe de comunidades** - GitHub, Stack Overflow, fóruns
6. **Contribua para projetos** - A melhor forma de aprender é praticando
7. **Mantenha seu histórico limpo** - Commits bem feitos facilitam a vida

---

## ✅ Checklist de Progresso

Use este checklist para acompanhar seu progresso:

- [ ] Módulo 1: Fundamentos de Controle de Versão
- [ ] Módulo 2: Instalação e Configuração
- [ ] Módulo 3: Comandos Básicos
- [ ] Módulo 4: Branching e Merging
- [ ] Módulo 5: Trabalho Remoto
- [ ] Módulo 6: Operações Avançadas
- [ ] Módulo 7: Fluxos de Trabalho
- [ ] Módulo 8: Ferramentas e Integrações
- [ ] Módulo 9: Projetos Práticos (mínimo 2 projetos)

---

## 🚀 Próximos Passos

Após completar este roteiro de Git, você estará preparado para:
- Trabalhar em equipe de forma profissional
- Contribuir para projetos open source
- Implementar fluxos de trabalho eficientes
- Automatizar processos com Git hooks
- Integrar Git com ferramentas de CI/CD

---

## 💡 Lembre-se

Git é uma ferramenta essencial para qualquer desenvolvedor. Dominar Git não é apenas sobre memorizar comandos, mas entender os conceitos e fluxos de trabalho. Pratique constantemente e não tenha medo de experimentar.

**Bons estudos! 🎓**
