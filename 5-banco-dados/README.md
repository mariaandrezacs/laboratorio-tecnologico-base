# Roteiro de Aprendizado - Banco de Dados

Este roteiro foi desenvolvido para guiar você no aprendizado de bancos de dados, essenciais para persistência e gestão de dados em aplicações.

## 📋 Estrutura do Roteiro

O roteiro está organizado em módulos progressivos. Cada módulo deve ser concluído antes de avançar para o próximo.

---

## 🎯 Módulo 1: Fundamentos de Banco de Dados

### Objetivos
- Compreender o que é um banco de dados
- Entender a importância da persistência de dados
- Conhecer diferentes tipos de bancos de dados

### Tópicos
1. **O que é um Banco de Dados?**
   - Definição e propósito
   - Diferença entre dados e informações
   - Por que usar banco de dados
   - Histórico e evolução

2. **Sistemas de Gerenciamento de Banco de Dados (SGBD)**
   - O que é um SGBD
   - Funções do SGBD
   - Exemplos de SGBDs

3. **Tipos de Bancos de Dados**
   - Relacionais (SQL)
   - NoSQL
   - Orientados a objetos
   - Distribuídos
   - Em memória

### Recursos Recomendados
- [MySQL Documentation](https://dev.mysql.com/doc/)
- [PostgreSQL Documentation](https://www.postgresql.org/docs/)
- [MongoDB University](https://university.mongodb.com/)

### Exercícios Práticos
- Pesquisar sobre diferentes tipos de bancos de dados
- Identificar cenários de uso para cada tipo
- Comparar vantagens e desvantagens

---

## 📊 Módulo 2: Modelagem de Dados

### Objetivos
- Aprender a modelar dados corretamente
- Compreender o modelo relacional
- Dominar normalização

### Tópicos
1. **Conceitos de Modelagem**
   - Entidades e atributos
   - Relacionamentos
   - Chaves (primária, estrangeira, candidata)
   - Cardinalidade (1:1, 1:N, N:N)

2. **Modelo Entidade-Relacionamento (MER)**
   - Diagramas ER
   - Notações (Chen, Crow's Foot)
   - Como criar um diagrama ER
   - Ferramentas de modelagem

3. **Normalização**
   - Primeira Forma Normal (1FN)
   - Segunda Forma Normal (2FN)
   - Terceira Forma Normal (3FN)
   - Forma Normal de Boyce-Codd (FNBC)
   - Quando desnormalizar

### Exercícios Práticos
- Criar diagrama ER para um sistema de e-commerce
- Modelar um sistema de biblioteca
- Normalizar tabelas não normalizadas
- Identificar problemas em modelos mal projetados

---

## 🔤 Módulo 3: SQL Básico

### Objetivos
- Dominar os comandos básicos de SQL
- Aprender a consultar dados
- Compreender a estrutura de tabelas

### Tópicos
1. **Comandos DDL (Data Definition Language)**
   - CREATE - Criar tabelas
   - ALTER - Modificar tabelas
   - DROP - Remover tabelas
   - TRUNCATE - Limpar tabelas

2. **Comandos DML (Data Manipulation Language)**
   - SELECT - Consultar dados
   - INSERT - Inserir dados
   - UPDATE - Atualizar dados
   - DELETE - Remover dados

3. **Tipos de Dados**
   - Numéricos (INT, DECIMAL, FLOAT)
   - Texto (VARCHAR, CHAR, TEXT)
   - Data/Hora (DATE, DATETIME, TIMESTAMP)
   - Booleanos
   - Outros tipos

### Exercícios Práticos
- Criar um banco de dados de exemplo
- Criar tabelas com diferentes tipos de dados
- Inserir dados de teste
- Fazer consultas simples
- Atualizar e remover dados

---

## 🔍 Módulo 4: SQL Intermediário

### Objetivos
- Aprender consultas mais complexas
- Dominar filtros e ordenação
- Compreender agregações

### Tópicos
1. **Filtros e Ordenação**
   - WHERE - Filtrar dados
   - ORDER BY - Ordenar resultados
   - LIMIT - Limitar resultados
   - DISTINCT - Remover duplicatas

2. **Operadores e Funções**
   - Operadores de comparação
   - Operadores lógicos (AND, OR, NOT)
   - Operadores LIKE, IN, BETWEEN
   - Funções de agregação (COUNT, SUM, AVG, MIN, MAX)
   - Funções de texto e data

3. **Agrupamento**
   - GROUP BY - Agrupar dados
   - HAVING - Filtrar grupos
   - Combinação com funções de agregação

### Exercícios Práticos
- Fazer consultas com múltiplas condições
- Usar funções de agregação
- Agrupar dados por categorias
- Criar relatórios com GROUP BY
- Usar HAVING para filtrar grupos

---

## 🔗 Módulo 5: JOINs e Relacionamentos

### Objetivos
- Dominar o conceito de JOINs
- Aprender a combinar dados de múltiplas tabelas
- Compreender diferentes tipos de JOIN

### Tópicos
1. **Conceito de JOIN**
   - Por que precisamos de JOINs
   - Como funcionam os JOINs
   - Performance de JOINs

2. **Tipos de JOIN**
   - INNER JOIN - Apenas correspondências
   - LEFT JOIN - Todas da esquerda
   - RIGHT JOIN - Todas da direita
   - FULL OUTER JOIN - Todas de ambos
   - CROSS JOIN - Produto cartesiano

3. **Self JOIN e Subqueries**
   - Self JOIN - Join com a mesma tabela
   - Subqueries - Consultas aninhadas
   - EXISTS e NOT EXISTS
   - Quando usar subqueries vs JOINs

### Exercícios Práticos
- Criar tabelas relacionadas
- Fazer JOINs entre múltiplas tabelas
- Usar diferentes tipos de JOIN
- Resolver problemas com self JOIN
- Comparar performance de subqueries vs JOINs

---

## 📈 Módulo 6: SQL Avançado

### Objetivos
- Aprender tópicos avançados de SQL
- Dominar views e stored procedures
- Compreender triggers e transações

### Tópicos
1. **Views (Visões)**
   - O que são views
   - Criar e modificar views
   - Vantagens e desvantagens
   - Views atualizáveis vs não atualizáveis

2. **Stored Procedures e Functions**
   - O que são stored procedures
   - Criar e executar procedures
   - Funções definidas pelo usuário
   - Parâmetros e retorno

3. **Triggers (Gatilhos)**
   - O que são triggers
   - Quando usar triggers
   - Criar triggers
   - Boas práticas

4. **Transações**
   - Conceito de transação
   - ACID (Atomicidade, Consistência, Isolamento, Durabilidade)
   - COMMIT, ROLLBACK
   - Níveis de isolamento

### Exercícios Práticos
- Criar views para relatórios
- Desenvolver stored procedures
- Implementar triggers para auditoria
- Usar transações para garantir integridade
- Testar diferentes níveis de isolamento

---

## 🗄️ Módulo 7: MySQL/PostgreSQL Prático

### Objetivos
- Instalar e configurar um SGBD
- Praticar com um banco de dados real
- Aprender ferramentas de administração

### Tópicos
1. **Instalação e Configuração**
   - Instalar MySQL ou PostgreSQL
   - Configurar conexões
   - Criar usuários e permissões
   - Segurança básica

2. **Ferramentas de Administração**
   - MySQL Workbench
   - pgAdmin
   - DBeaver
   - Linha de comando

3. **Backup e Restore**
   - Exportar banco de dados
   - Importar banco de dados
   - Backup automático
   - Estratégias de backup

### Exercícios Práticos
- Instalar um SGBD (MySQL ou PostgreSQL)
- Criar um banco de dados completo
- Usar ferramentas gráficas
- Fazer backup e restore
- Configurar usuários com permissões

---

## 📝 Módulo 8: NoSQL

### Objetivos
- Compreender o paradigma NoSQL
- Aprender diferentes tipos de NoSQL
- Praticar com MongoDB

### Tópicos
1. **Conceitos NoSQL**
   - O que é NoSQL
   - Quando usar NoSQL vs SQL
   - CAP theorem
   - Escalabilidade

2. **Tipos de NoSQL**
   - Document (MongoDB, CouchDB)
   - Key-Value (Redis, DynamoDB)
   - Column-family (Cassandra, HBase)
   - Graph (Neo4j, ArangoDB)

3. **MongoDB Prático**
   - Instalação e configuração
   - CRUD básico
   - Consultas avançadas
   - Indexação
   - Aggregation framework

### Exercícios Práticos
- Instalar MongoDB
- Criar um banco de dados NoSQL
- Fazer operações CRUD
- Comparar performance com SQL
- Modelar dados para NoSQL

---

## 🏗️ Módulo 9: Design de Banco de Dados

### Objetivos
- Aprender boas práticas de design
- Compreender performance e otimização
- Dominar indexação

### Tópicos
1. **Boas Práticas de Design**
   - Nomenclatura consistente
   - Escolha de tipos de dados
   - Integridade referencial
   - Restrições (constraints)

2. **Indexação**
   - O que são índices
   - Quando criar índices
   - Tipos de índices
   - Impacto na performance
   - Índices compostos

3. **Otimização de Consultas**
   - EXPLAIN - Analisar planos de execução
   - Identificar gargalos
   - Otimizar JOINs
   - Usar índices eficientemente
   - Caching de consultas

### Exercícios Práticos
- Analisar planos de execução
- Criar índices para melhorar performance
- Otimizar consultas lentas
- Implementar boas práticas de design
- Monitorar performance

---

## 🔒 Módulo 10: Segurança em Banco de Dados

### Objetivos
- Compreender riscos de segurança
- Aprender a proteger dados sensíveis
- Implementar boas práticas de segurança

### Tópicos
1. **Princípios de Segurança**
   - Princípio do menor privilégio
   - Autenticação e autorização
   - Criptografia de dados
   - Auditoria e logs

2. **Ameaças Comuns**
   - SQL Injection
   - Ataques de força bruta
   - Acesso não autorizado
   - Vazamento de dados

3. **Boas Práticas**
   - Parâmetros preparados
   - Validação de entrada
   - Criptografia em repouso e em trânsito
   - Backup seguro
   - Atualizações e patches

### Exercícios Práticos
- Implementar autenticação segura
- Usar parâmetros preparados
- Criptografar dados sensíveis
- Configurar auditoria
- Testar vulnerabilidades

---

## 🎮 Módulo 11: Projetos Práticos

### Objetivos
- Aplicar todos os conceitos aprendidos
- Desenvolver projetos completos
- Ganhar experiência prática

### Projetos Sugeridos
1. **Sistema de E-commerce**
   - Modelar produtos, categorias, pedidos
   - Implementar relacionamentos complexos
   - Criar views para relatórios
   - Otimizar consultas

2. **Sistema de Redes Sociais**
   - Modelar usuários, posts, comentários
   - Implementar grafos de amizade
   - Criar timeline com JOINs
   - Usar NoSQL para dados não estruturados

3. **Sistema de Gestão Escolar**
   - Modelar alunos, professores, disciplinas
   - Implementar matrículas e notas
   - Criar stored procedures para cálculos
   - Gerar relatórios complexos

4. **Sistema de Reservas**
   - Modelar reservas e disponibilidade
   - Implementar transações
   - Evitar conflitos de reserva
   - Criar triggers para validação

---

## 📚 Recursos Complementares

### Livros Recomendados
- "SQL Antipatterns" - Bill Karwin
- "Database Design for Mere Mortals" - Michael J. Hernandez
- "Seven Databases in Seven Weeks" - Eric Redmond

### Canais do YouTube
- Alura
- Rocket Seat
- freeCodeCamp
- Felipe Deschamps

### Plataformas de Prática
- LeetCode (Database)
- HackerRank (SQL)
- SQLZoo
- Mode Analytics SQL Tutorial
- W3Schools SQL

---

## 🎯 Dicas de Estudo

1. **Pratique com dados reais** - Use conjuntos de dados reais para praticar
2. **Entenda o porquê** - Não apenas memorize sintaxe, entenda os conceitos
3. **Use EXPLAIN** - Sempre analise o plano de execução
4. **Normalize primeiro** - Normalize antes de desnormalizar
5. **Teste performance** - Meça o impacto das suas decisões
6. **Documente seu modelo** - Mantenha documentação atualizada
7. **Faça backup** - Sempre faça backup antes de mudanças

---

## ✅ Checklist de Progresso

Use este checklist para acompanhar seu progresso:

- [ ] Módulo 1: Fundamentos de Banco de Dados
- [ ] Módulo 2: Modelagem de Dados
- [ ] Módulo 3: SQL Básico
- [ ] Módulo 4: SQL Intermediário
- [ ] Módulo 5: JOINs e Relacionamentos
- [ ] Módulo 6: SQL Avançado
- [ ] Módulo 7: MySQL/PostgreSQL Prático
- [ ] Módulo 8: NoSQL
- [ ] Módulo 9: Design de Banco de Dados
- [ ] Módulo 10: Segurança em Banco de Dados
- [ ] Módulo 11: Projetos Práticos (mínimo 2 projetos)

---

## 🚀 Próximos Passos

Após completar este roteiro de banco de dados, você estará preparado para:
- Projetar bancos de dados eficientes
- Escrever consultas otimizadas
- Trabalhar com diferentes tipos de bancos de dados
- Implementar segurança em dados
- Integrar banco de dados com aplicações

---

## 💡 Lembre-se

Bancos de dados são o coração da maioria das aplicações. Um bom design de banco de dados pode fazer a diferença entre uma aplicação rápida e escalável ou uma aplicação lenta e problemática. Pratique constantemente e sempre pense em performance e segurança.

**Bons estudos! 🎓**
