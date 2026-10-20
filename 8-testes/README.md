# Roteiro de Aprendizado - Testes de Software

Este roteiro foi desenvolvido para guiar você no aprendizado de testes de software, essencial para garantir qualidade e confiabilidade em aplicações.

## 📋 Estrutura do Roteiro

O roteiro está organizado em módulos progressivos. Cada módulo deve ser concluído antes de avançar para o próximo.

---

## 🎯 Módulo 1: Fundamentos de Testes

### Objetivos
- Compreender o que são testes de software
- Entender a importância dos testes
- Conhecer diferentes tipos de testes

### Tópicos
1. **O que são Testes de Software?**
   - Definição e propósito
   - Por que testar é importante
   - Custo de bugs em produção
   - Benefícios dos testes

2. **Tipos de Testes**
   - Testes unitários
   - Testes de integração
   - Testes de sistema
   - Testes de aceitação
   - Testes manuais vs automatizados

3. **Pirâmide de Testes**
   - Conceito da pirâmide
   - Testes unitários (base)
   - Testes de integração (meio)
   - Testes E2E (topo)
   - Proporção ideal

### Recursos Recomendados
- [Martin Fowler - TestPyramid](https://martinfowler.com/articles/practical-test-pyramid.html)
- [Testing JavaScript](https://testingjavascript.com/)
- [Google Testing Blog](https://testing.googleblog.com/)

### Exercícios Práticos
- Identificar bugs em código sem testes
- Analisar a pirâmide de testes em um projeto
- Pesquisar sobre ferramentas de teste
- Entender o ciclo de vida de um teste

---

## 🧪 Módulo 2: Testes Unitários

### Objetivos
- Dominar testes unitários
- Aprender a isolar código para teste
- Compreender mocks e stubs

### Tópicos
1. **Conceitos de Testes Unitários**
   - O que são testes unitários
   - Características de um bom teste unitário
   - AAA (Arrange, Act, Assert)
   - Isolamento de código

2. **Ferramentas de Teste**
   - Jest (JavaScript)
   - JUnit (Java)
   - pytest (Python)
   - NUnit (C#)
   - Escolha a ferramenta adequada

3. **Assertions**
   - O que são assertions
   - Tipos de assertions
   - Mensagens de erro customizadas
   - Boas práticas

4. **Mocks e Stubs**
   - Diferença entre mock e stub
   - Quando usar mocks
   - Bibliotecas de mocking
   - Dependency injection

### Exercícios Práticos
- Escrever testes unitários para funções simples
- Criar mocks para dependências externas
- Testar funções com diferentes cenários
- Refatorar código para torná-lo testável

---

## 🔗 Módulo 3: Testes de Integração

### Objetivos
- Aprender a testar integração entre componentes
- Compreender testes de banco de dados
- Dominar testes de APIs

### Tópicos
1. **Conceitos de Integração**
   - O que são testes de integração
   - Diferença para testes unitários
   - Quando escrever testes de integração
   - Desafios comuns

2. **Testes de Banco de Dados**
   - Configurar banco de dados de teste
   - Setup e teardown
   - Testar queries e operações
   - Rollback após testes

3. **Testes de APIs**
   - Testar endpoints REST
   - Supertest (Node.js)
   - Postman/Newman
   - Testar status codes e responses

4. **Testes de Integração com Serviços Externos**
   - Mock de serviços externos
   - Testar integração com APIs de terceiros
   - Testar filas e mensageria
   - Testar cache

### Exercícios Práticos
- Escrever testes de integração com banco de dados
- Testar endpoints de uma API
- Mockar serviços externos
- Criar testes de integração para um sistema completo

---

## 🌐 Módulo 4: Testes E2E (End-to-End)

### Objetivos
- Aprender testes de ponta a ponta
- Dominar ferramentas de automação E2E
- Compreender testes de UI

### Tópicos
1. **Conceitos de Testes E2E**
   - O que são testes E2E
   - Quando usar testes E2E
   - Vantagens e desvantagens
   - Custo de manutenção

2. **Ferramentas E2E**
   - Cypress
   - Playwright
   - Selenium
   - Puppeteer
   - Escolha a ferramenta adequada

3. **Testes de UI**
   - Seletores de elementos
   - Interação com formulários
   - Navegação entre páginas
   - Esperas e sincronização

4. **Boas Práticas E2E**
   - Testar fluxos críticos
   - Evitar testes frágeis
   - Usar data-testid
   - Manter testes independentes

### Exercícios Práticos
- Instalar e configurar Cypress ou Playwright
- Escrever teste E2E para login
- Testar fluxo de compra em e-commerce
- Criar suíte de testes E2E para uma aplicação

---

## 🔄 Módulo 5: TDD (Test-Driven Development)

### Objetivos
- Compreender o ciclo TDD
- Aprender a escrever testes antes do código
- Dominar refatoração guiada por testes

### Tópicos
1. **Conceitos de TDD**
   - O que é TDD
   - Ciclo Red-Green-Refactor
   - Benefícios do TDD
   - Mitos sobre TDD

2. **Ciclo TDD**
   - Red: Escrever teste falho
   - Green: Fazer teste passar
   - Refactor: Melhorar código
   - Repetir o ciclo

3. **Práticas TDD**
   - Escrever testes pequenos
   - Um teste por vez
   - Refatorar constantemente
   - Manter código limpo

4. **Desafios do TDD**
   - Curva de aprendizado
   - Tempo inicial mais lento
   - Mudança de mentalidade
   - Quando não usar TDD

### Exercícios Práticos
- Implementar uma feature usando TDD
- Praticar o ciclo Red-Green-Refactor
- Refatorar código guiado por testes
- Comparar desenvolvimento com e sem TDD

---

## 🎭 Módulo 6: Mocks, Stubs e Spies

### Objetivos
- Dominar técnicas de mocking
- Aprender a isolar dependências
- Compreender test doubles

### Tópicos
1. **Test Doubles**
   - Dummy
   - Stub
   - Mock
   - Spy
   - Fake

2. **Mocking Libraries**
   - Mockito (Java)
   - Sinon (JavaScript)
   - unittest.mock (Python)
   - Moq (C#)

3. **Quando Usar Mocks**
   - Dependências externas
   - Serviços lentos
   - Estados imprevisíveis
   - APIs de terceiros

4. **Anti-patterns de Mocking**
   - Over-mocking
   - Mockar tudo
   - Mockar implementação
   - Testes acoplados

### Exercícios Práticos
- Criar stubs para dependências simples
- Usar mocks para verificar chamadas
- Implementar spies para monitorar comportamento
- Refatorar testes com over-mocking

---

## 📊 Módulo 7: Coverage e Métricas

### Objetivos
- Compreender cobertura de código
- Aprender a medir qualidade de testes
- Dominar ferramentas de análise

### Tópicos
1. **Cobertura de Código**
   - O que é coverage
   - Tipos de coverage (linha, ramo, função)
   - Porcentagem ideal
   - Limitações do coverage

2. **Ferramentas de Coverage**
   - Istanbul (JavaScript)
   - JaCoCo (Java)
   - Coverage.py (Python)
   - dotCover (C#)

3. **Métricas de Teste**
   - Número de testes
   - Tempo de execução
   - Taxa de falha
   - Complexidade ciclomática

4. **CI/CD e Testes**
   - Integrar testes no pipeline
   - Testes em cada commit
   - Testes em pull requests
   - Bloquear deploy se testes falharem

### Exercícios Práticos
- Configurar ferramenta de coverage
- Analisar coverage de um projeto
- Integrar testes no CI/CD
- Definir thresholds de coverage

---

## 🐛 Módulo 8: Testes de Performance e Carga

### Objetivos
- Aprender a testar performance
- Dominar testes de carga
- Compreender testes de estresse

### Tópicos
1. **Conceitos de Performance**
   - O que são testes de performance
   - Métricas importantes (tempo de resposta, throughput)
   - SLA e SLO
   - Quando testar performance

2. **Tipos de Testes de Performance**
   - Testes de carga
   - Testes de estresse
   - Testes de escalabilidade
   - Testes de endurance

3. **Ferramentas de Performance**
   - JMeter
   - k6
   - Gatling
   - Locust
   - Artillery

4. **Análise de Resultados**
   - Identificar gargalos
   - Analisar latência
   - Comparar cenários
   - Otimizar baseado em resultados

### Exercícios Práticos
- Configurar ferramenta de teste de carga
- Criar teste de carga para uma API
- Analisar resultados e identificar problemas
- Comparar performance antes e depois de otimizações

---

## 🔒 Módulo 9: Testes de Segurança

### Objetivos
- Compreender testes de segurança
- Aprender a identificar vulnerabilidades
- Dominar ferramentas de segurança

### Tópicos
1. **Conceitos de Segurança**
   - Por que testar segurança
   - OWASP Top 10
   - Vulnerabilidades comuns
   - Shift left security

2. **Tipos de Testes de Segurança**
   - SAST (Static Application Security Testing)
   - DAST (Dynamic Application Security Testing)
   - Penetration testing
   - Dependency scanning

3. **Ferramentas de Segurança**
   - OWASP ZAP
   - SonarQube
   - Snyk
   - Burp Suite

4. **Boas Práticas**
   - Validar entrada
   - Sanitizar output
   - Usar parâmetros preparados
   - Manter dependências atualizadas

### Exercícios Práticos
- Executar scan de segurança em um projeto
- Identificar vulnerabilidades em dependências
- Corrigir problemas de segurança
- Configurar scanning automático

---

## 🤖 Módulo 10: Testes Automatizados

### Objetivos
- Aprender a automatizar testes
- Dominar frameworks de automação
- Compreender CI/CD para testes

### Tópicos
1. **Automação de Testes**
   - Por que automatizar
   - Quando automatizar
   - Custo-benefício
   - Manutenção de testes

2. **Frameworks de Automação**
   - Selenium WebDriver
   - Cypress
   - Playwright
   - Robot Framework

3. **CI/CD para Testes**
   - GitHub Actions
   - GitLab CI
   - Jenkins
   - CircleCI

4. **Boas Práticas de Automação**
   - Testes independentes
   - Testes determinísticos
   - Testes rápidos
   - Manutenção contínua

### Exercícios Práticos
- Automatizar suíte de testes manuais
- Configurar pipeline de CI/CD
- Executar testes automaticamente em cada commit
- Manter e atualizar testes automatizados

---

## 🎮 Módulo 11: Projetos Práticos

### Objetivos
- Aplicar todos os conceitos aprendidos
- Desenvolver suítes de testes completas
- Ganhar experiência prática

### Projetos Sugeridos
1. **API com Testes Completos**
   - Testes unitários de todas as funções
   - Testes de integração com banco de dados
   - Testes E2E dos endpoints
   - Coverage acima de 80%

2. **Aplicação Web com Testes E2E**
   - Testes E2E para fluxos críticos
   - Testes de login e cadastro
   - Testes de formulários
   - Testes responsivos

3. **Sistema com TDD**
   - Desenvolver feature usando TDD
   - Manter ciclo Red-Green-Refactor
   - Documentar processo
   - Comparar com desenvolvimento tradicional

4. **Pipeline de CI/CD**
   - Configurar testes no pipeline
   - Bloquear deploy se testes falharem
   - Adicionar testes de segurança
   - Monitorar resultados

---

## 📚 Recursos Complementares

### Livros Recomendados
- "Test-Driven Development" - Kent Beck
- "Growing Object-Oriented Software" - Steve Freeman
- "The Art of Unit Testing" - Roy Osherove
- "Working Effectively with Legacy Code" - Michael C. Feathers

### Canais do YouTube
- Testing JavaScript
- Kent C. Dodds
- Alura
- Rocket Seat

### Plataformas de Prática
- Codewars
- LeetCode (com testes)
- HackerRank
- Exercism

---

## 🎯 Dicas de Estudo

1. **Teste tudo** - Não deixe código sem testes
2. **Comece pequeno** - Testes unitários são mais fáceis
3. **Mantenha testes simples** - Testes complexos são difíceis de manter
4. **Use TDD** - Melhora design e qualidade
5. **Refatore constantemente** - Testes dão confiança para refatorar
6. **Automatize** - Testes manuais não escalam
7. **Monitore** - Mantenha testes passando sempre

---

## ✅ Checklist de Progresso

Use este checklist para acompanhar seu progresso:

- [ ] Módulo 1: Fundamentos de Testes
- [ ] Módulo 2: Testes Unitários
- [ ] Módulo 3: Testes de Integração
- [ ] Módulo 4: Testes E2E
- [ ] Módulo 5: TDD
- [ ] Módulo 6: Mocks, Stubs e Spies
- [ ] Módulo 7: Coverage e Métricas
- [ ] Módulo 8: Testes de Performance e Carga
- [ ] Módulo 9: Testes de Segurança
- [ ] Módulo 10: Testes Automatizados
- [ ] Módulo 11: Projetos Práticos (mínimo 2 projetos)

---

## 🚀 Próximos Passos

Após completar este roteiro de testes, você estará preparado para:
- Escrever testes de qualidade
- Implementar TDD no desenvolvimento
- Automatizar suítes de testes
- Integrar testes no CI/CD
- Garantir qualidade de software

---

## 💡 Lembre-se

Testes são um investimento, não um custo. Código bem testado é mais confiável, mais fácil de manter e mais seguro para refatorar. A prática constante é essencial para dominar testes de software.

**Bons estudos! 🎓**
