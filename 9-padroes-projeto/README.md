# Roteiro de Aprendizado - Padrões de Projeto (Design Patterns)

Este roteiro foi desenvolvido para guiar você no aprendizado de padrões de projeto, soluções reutilizáveis para problemas comuns em desenvolvimento de software.

## 📋 Estrutura do Roteiro

O roteiro está organizado em módulos progressivos. Cada módulo deve ser concluído antes de avançar para o próximo.

---

## 🎯 Módulo 1: Fundamentos de Padrões de Projeto

### Objetivos
- Compreender o que são padrões de projeto
- Entender a importância dos padrões
- Conhecer a história e classificação

### Tópicos
1. **O que são Padrões de Projeto?**
   - Definição e propósito
   - Origem (GoF - Gang of Four)
   - Por que usar padrões
   - Quando não usar padrões

2. **Princípios SOLID**
   - S - Single Responsibility Principle
   - O - Open/Closed Principle
   - L - Liskov Substitution Principle
   - I - Interface Segregation Principle
   - D - Dependency Inversion Principle

3. **Classificação dos Padrões**
   - Criacionais (Creational)
   - Estruturais (Structural)
   - Comportamentais (Behavioral)

### Recursos Recomendados
- [Refactoring Guru - Design Patterns](https://refactoring.guru/design-patterns)
- "Design Patterns: Elements of Reusable Object-Oriented Software" - GoF
- [Source Making - Design Patterns](https://sourcemaking.com/design_patterns)

### Exercícios Práticos
- Identificar violações dos princípios SOLID em código
- Pesquisar sobre problemas que padrões resolvem
- Entender a diferença entre padrão e algoritmo
- Analisar código existente para identificar oportunidades de padrões

---

## 🏗️ Módulo 2: Padrões Criacionais (Creational)

### Objetivos
- Dominar padrões de criação de objetos
- Aprender a controlar instaciação
- Compreender quando usar cada padrão

### Tópicos
1. **Singleton**
   - Conceito e propósito
   - Implementação básica
   - Thread-safe singleton
   - Quando usar
   - Problemas e críticas

2. **Factory Method**
   - Conceito e propósito
   - Implementação
   - Factory Method vs Simple Factory
   - Quando usar

3. **Abstract Factory**
   - Conceito e propósito
   - Implementação
   - Abstract Factory vs Factory Method
   - Quando usar

4. **Builder**
   - Conceito e propósito
   - Implementação
   - Fluent interface
   - Quando usar

5. **Prototype**
   - Conceito e propósito
   - Clonagem shallow vs deep
   - Implementação
   - Quando usar

### Exercícios Práticos
- Implementar Singleton para configuração
- Usar Factory Method para criar objetos
- Implementar Builder para objetos complexos
- Usar Prototype para clonar objetos
- Comparar diferentes padrões criacionais

---

## 🔗 Módulo 3: Padrões Estruturais (Structural)

### Objetivos
- Dominar padrões de composição de objetos
- Aprender a formar estruturas maiores
- Compreender relações entre objetos

### Tópicos
1. **Adapter**
   - Conceito e propósito
   - Implementação
   - Class adapter vs Object adapter
   - Quando usar

2. **Bridge**
   - Conceito e propósito
   - Implementação
   - Abstração vs Implementação
   - Quando usar

3. **Composite**
   - Conceito e propósito
   - Implementação
   - Estrutura em árvore
   - Quando usar

4. **Decorator**
   - Conceito e propósito
   - Implementação
   - Decorator vs Herança
   - Quando usar

5. **Facade**
   - Conceito e propósito
   - Implementação
   - Simplificar interfaces complexas
   - Quando usar

6. **Flyweight**
   - Conceito e propósito
   - Implementação
   - Compartilhamento de objetos
   - Quando usar

7. **Proxy**
   - Conceito e propósito
   - Implementação
   - Tipos de proxy (virtual, protection, remote)
   - Quando usar

### Exercícios Práticos
- Implementar Adapter para integrar sistemas
- Usar Composite para estruturas hierárquicas
- Implementar Decorator para adicionar comportamentos
- Criar Facade para simplificar API complexa
- Usar Proxy para controle de acesso

---

## 🎭 Módulo 4: Padrões Comportamentais (Behavioral)

### Objetivos
- Dominar padrões de comunicação entre objetos
- Aprender a distribuir responsabilidades
- Compreender interações entre objetos

### Tópicos
1. **Strategy**
   - Conceito e propósito
   - Implementação
   - Strategy vs if/else
   - Quando usar

2. **Observer**
   - Conceito e propósito
   - Implementação
   - Pub/Sub pattern
   - Quando usar

3. **Command**
   - Conceito e propósito
   - Implementação
   - Undo/Redo
   - Quando usar

4. **Iterator**
   - Conceito e propósito
   - Implementação
   - Iteradores internos vs externos
   - Quando usar

5. **Chain of Responsibility**
   - Conceito e propósito
   - Implementação
   - Middleware pattern
   - Quando usar

6. **State**
   - Conceito e propósito
   - Implementação
   - State Machine
   - Quando usar

7. **Template Method**
   - Conceito e propósito
   - Implementação
   - Hooks
   - Quando usar

8. **Mediator**
   - Conceito e propósito
   - Implementação
   - Centralizar comunicação
   - Quando usar

9. **Memento**
   - Conceito e propósito
   - Implementação
   - Undo/Redo com Memento
   - Quando usar

10. **Interpreter**
    - Conceito e propósito
    - Implementação
    - Gramáticas e parsers
    - Quando usar

11. **Visitor**
    - Conceito e propósito
    - Implementação
    - Double dispatch
    - Quando usar

### Exercícios Práticos
- Implementar Strategy para algoritmos variáveis
- Usar Observer para eventos e notificações
- Implementar Command para ações reversíveis
- Usar Chain of Responsibility para middleware
- Implementar State para gerenciar estados complexos

---

## 🎨 Módulo 5: Padrões de Arquitetura

### Objetivos
- Conhecer padrões de arquitetura de software
- Aprender a estruturar aplicações
- Compreender escalabilidade e manutenibilidade

### Tópicos
1. **MVC (Model-View-Controller)**
   - Conceito e componentes
   - Separação de responsabilidades
   - Implementação
   - Quando usar

2. **MVVM (Model-View-ViewModel)**
   - Conceito e componentes
   - Data binding
   - Implementação
   - Quando usar

3. **MVP (Model-View-Presenter)**
   - Conceito e componentes
   - Diferença para MVC
   - Implementação
   - Quando usar

4. **Layered Architecture**
   - Camadas (Presentation, Business, Data)
   - Separação de responsabilidades
   - Vantagens e desvantagens
   - Quando usar

5. **Microservices**
   - Conceito e propósito
   - Monolith vs Microservices
   - Comunicação entre serviços
   - Quando usar

6. **Event-Driven Architecture**
   - Conceito e propósito
   - Event sourcing
   - CQRS
   - Quando usar

### Exercícios Práticos
- Implementar MVC em uma aplicação web
- Criar arquitetura em camadas
- Comparar MVC, MVVM e MVP
- Projetar sistema monolítico vs microservices
- Implementar sistema event-driven

---

## 🔧 Módulo 6: Padrões em Linguagens Específicas

### Objetivos
- Aprender padrões específicos de linguagens
- Compreender idioms e convenções
- Dominar boas práticas por linguagem

### Tópicos
1. **Padrões em JavaScript**
   - Module Pattern
   - Revealing Module Pattern
   - Constructor Pattern
   - Prototype Pattern
   - Observer Pattern (native)

2. **Padrões em Python**
   - Context Manager
   - Decorator (native)
   - Iterator (native)
   - Singleton (idiomático)

3. **Padrões em Java**
   - Dependency Injection
   - DAO Pattern
   - DTO Pattern
   - Service Layer

4. **Padrões em C#**
   - Async/Await Pattern
   - LINQ Pattern
   - Dependency Injection (native)
   - IDisposable Pattern

### Exercícios Práticos
- Implementar Module Pattern em JavaScript
- Usar Context Manager em Python
- Implementar Dependency Injection em Java
- Usar async/await pattern em C#
- Comparar padrões entre linguagens

---

## 🚀 Módulo 7: Anti-Patterns

### Objetivos
- Compreender o que são anti-patterns
- Aprender a identificar e evitar
- Conhecer soluções para anti-patterns

### Tópicos
1. **O que são Anti-Patterns?**
   - Definição e propósito
   - Diferença para padrões
   - Por que identificar anti-patterns
   - Como evitar

2. **Anti-Patterns Comuns**
   - God Object
   - Spaghetti Code
   - Golden Hammer
   - Boat Anchor
   - Dead Code
   - Magic Numbers
   - Hard Coding
   - Copy-Paste Programming

3. **Refatorando Anti-Patterns**
   - Identificar anti-patterns
   - Planejar refatoração
   - Aplicar padrões corretos
   - Testar após refatoração

### Exercícios Práticos
- Identificar anti-patterns em código existente
- Refatorar God Object
- Eliminar Magic Numbers
- Remover Dead Code
- Aplicar padrões para corrigir anti-patterns

---

## 🎮 Módulo 8: Projetos Práticos

### Objetivos
- Aplicar todos os conceitos aprendidos
- Desenvolver projetos usando padrões
- Ganhar experiência prática

### Projetos Sugeridos
1. **Sistema de Pagamentos com Strategy**
   - Implementar diferentes métodos de pagamento
   - Usar Strategy para variar métodos
   - Factory para criar payment methods
   - Observer para notificações

2. **Editor de Texto com Command**
   - Implementar Command para ações
   - Usar Memento para undo/redo
   - Composite para estrutura do documento
   - Visitor para formatação

3. **Sistema de Notificações com Observer**
   - Implementar Observer para notificações
   - Usar Strategy para diferentes canais
   - Chain of Responsibility para filtros
   - Builder para mensagens complexas

4. **Sistema de E-commerce com Padrões Múltiplos**
   - Factory para criar produtos
   - Builder para pedidos
   - Strategy para cálculo de frete
   - Observer para atualizações de estoque
   - Decorator para adicionar funcionalidades

---

## 📚 Recursos Complementares

### Livros Recomendados
- "Design Patterns: Elements of Reusable Object-Oriented Software" - GoF
- "Head First Design Patterns" - Eric Freeman
- "Patterns of Enterprise Application Architecture" - Martin Fowler
- "Clean Architecture" - Robert C. Martin

### Canais do YouTube
- ArjanCodes
- Derek Banas
- Christopher Okhravi
- Tech With Tim

### Plataformas de Prática
- Refactoring Guru
- Source Making
- Design Patterns Library
- GitHub (projetos open source)

---

## 🎯 Dicas de Estudo

1. **Não memorize** - Entenda o problema que o padrão resolve
2. **Pratique** - Implemente padrões em projetos reais
3. **Siga princípios SOLID** - Padrões emergem de bons princípios
4. **Não force** - Use padrões quando realmente necessário
5. **Refatore** - Aplique padrões para melhorar código existente
6. **Estude código** - Analise como frameworks usam padrões
7. **Ensine** - Explicar reforça o conhecimento

---

## ✅ Checklist de Progresso

Use este checklist para acompanhar seu progresso:

- [ ] Módulo 1: Fundamentos de Padrões de Projeto
- [ ] Módulo 2: Padrões Criacionais (Creational)
- [ ] Módulo 3: Padrões Estruturais (Structural)
- [ ] Módulo 4: Padrões Comportamentais (Behavioral)
- [ ] Módulo 5: Padrões de Arquitetura
- [ ] Módulo 6: Padrões em Linguagens Específicas
- [ ] Módulo 7: Anti-Patterns
- [ ] Módulo 8: Projetos Práticos (mínimo 2 projetos)

---

## 🚀 Próximos Passos

Após completar este roteiro de padrões de projeto, você estará preparado para:
- Identificar problemas que padrões resolvem
- Aplicar padrões adequadamente
- Refatorar código usando padrões
- Projetar arquiteturas sólidas
- Escrever código mais manutenível

---

## 💡 Lembre-se

Padrões de projeto são ferramentas, não regras. Não tente encaixar padrões em todo lugar. Use-os quando resolverem problemas reais e melhorem a qualidade do código. A prática constante é essencial para dominar padrões de projeto.

**Bons estudos! 🎓**
