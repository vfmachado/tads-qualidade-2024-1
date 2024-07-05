# Aula 06: Ferramentas e Técnicas Avançadas para Garantia da Qualidade

## Introdução

Nesta aula, detalharemos as ferramentas e técnicas utilizadas para garantir a qualidade no desenvolvimento de software, incluindo definições específicas e exemplos ampliados para cada ferramenta e técnica mencionada.

## Ferramentas de Gestão de Qualidade

### 1. Ferramentas de Análise Estatística

- **Definição**: Utilizam métodos matemáticos para coletar, revisar, analisar e formar conclusões a partir de dados. Essas ferramentas são essenciais para entender comportamentos, identificar tendências e prever futuros desafios no desenvolvimento de software.

#### SPSS (Statistical Package for the Social Sciences)
- **Aplicação**: Utilizado em testes de regressão para prever falhas com base em mudanças de código e histórico de falhas.
- **Caso de Uso Adicional**: Empresas de software utilizam SPSS para otimizar testes de performance, analisando o impacto de diferentes configurações de hardware nos tempos de resposta do software.

#### R
- **Aplicação**: Análise de variabilidade em testes de desempenho para identificar gargalos de performance.
- **Caso de Uso Adicional**: Desenvolvedores podem usar R para simular cenários de uso do usuário e analisar o impacto de novas funcionalidades no desempenho geral do sistema.

### 2. Software de Gerenciamento de Defeitos

- **Definição**: Sistemas projetados para rastrear, gerenciar e documentar bugs encontrados durante o desenvolvimento de software, permitindo uma resolução eficaz e sistemática de problemas.

#### Atlassian JIRA
- **Aplicação**: Gerenciamento de ciclos de vida de defeitos e integração com ferramentas de CI/CD para atualizações em tempo real.
- **Caso de Uso Adicional**: Empresas de desenvolvimento de jogos utilizam JIRA para gerenciar feedbacks de testadores beta e priorizar correções antes do lançamento público.

#### Redmine
- **Aplicação**: Oferece funcionalidades como fóruns e wikis para melhor comunicação entre equipes durante a resolução de bugs.
- **Caso de Uso Adicional**: Organizações de software de código aberto usam Redmine para gerenciar contribuições da comunidade e rastrear bugs através de diferentes versões e distribuições.

### 3. Sistemas de Controle de Versão

- **Definição**: Ferramentas que gerenciam alterações no código-fonte ao longo do tempo, permitindo que várias versões e variantes de código coexistam sem conflito.

#### Git
- **Aplicação**: Usado para facilitar o desenvolvimento colaborativo de projetos de software, onde as alterações são rastreadas em um repositório central.
- **Caso de Uso Adicional**: Desenvolvedores de um grande projeto de e-commerce usam Git para gerenciar alterações durante períodos de promoção, onde várias pequenas alterações são feitas e testadas rapidamente.

#### Mercurial
- **Aplicação**: Ideal para projetos que evoluem rapidamente e têm muitos desenvolvedores trabalhando em paralelo.
- **Caso de Uso Adicional**: Equipes em empresas de software que mantêm várias linhas de base de produtos utilizam Mercurial para gerenciar versões distintas de software adaptadas a diferentes clientes ou mercados.

### 4. Ferramentas de Integração Contínua

- **Definição**: Sistemas que automatizam a compilação, teste e integração de código-fonte, ajudando a detectar erros precocemente e melhorar a qualidade do software continuamente.

#### CircleCI
- **Aplicação**: Executa testes automatizados e constrói sistemas sempre que alterações são feitas, garantindo que o código esteja sempre pronto para produção.
- **Caso de Uso Adicional**: Startups de tecnologia usam CircleCI para garantir que novas funcionalidades sejam integradas e testadas automaticamente em ambientes de staging antes de serem promovidas para produção.

#### GitHub Actions
- **Aplicação**: Automatiza workflows, desde testes e construção até deployment e gestão de releases, diretamente no GitHub.
- **Caso de Uso Adicional**: Desenvolvedores de uma aplicação SaaS utilizam GitHub Actions para orquestrar pipelines de deployment em múltiplos ambientes cloud, garantindo a consistência entre testes e produção.

## Técnicas de Controle de Qualidade

### 1. Testes de Software

- **Definição**: Métodos sistemáticos aplicados para verificar a funcionalidade, segurança, e desempenho do software para assegurar que ele atenda às especificações definidas.

#### Testes Unitários com NUnit
- **Aplicação**: Isolamento e teste de pequenas partes do código para verificar a correção individual.
- **Caso de Uso Adicional**: Desenvolvedores de APIs usam NUnit para validar cada endpoint individualmente, assegurando que respondam corretamente às solicitações antes de serem integradas ao sistema maior.

#### Testes de Aceitação com Cucumber
- **Aplicação**: Execução de scripts baseados em comportamento que validam funcionalidades do ponto de vista do usuário.
- **Caso de Uso Adicional**: Equipes de QA em bancos digitais usam Cucumber para simular transações bancárias e verificar se os resultados atendem às expectativas dos clientes.

### 2. Revisão de Código

- **Definição**: Processo pelo qual código é examinado por outros desenvolvedores com o objetivo de encontrar erros, melhorar a qualidade e aumentar a manutenibilidade.

#### Gerrit
- **Aplicação**: Ferramenta para revisões detalhadas de código que facilita a colaboração e o feedback antes da fusão de código no branch principal.
- **Caso de Uso Adicional**: Empresas de software que praticam integração contínua usam Gerrit para realizar revisões de código rápido e eficiente, mantendo a qualidade alta em ciclos de desenvolvimento acelerados.

### 3. Análise Estática

- **Definição**: Avaliação de software que é realizada sem executar o programa, utilizando ferramentas que examinam o código-fonte para encontrar defeitos, vulnerabilidades de segurança ou desvios de padrões de codificação.

#### SonarQube
- **Aplicação**: Análise contínua do código-fonte para identificar problemas técnicos e de segurança.
- **Caso de Uso Adicional**: Desenvolvedores de plataformas de e-commerce utilizam SonarQube para garantir que o código cumpra com os mais altos padrões de segurança e qualidade antes de cada release.

### 4. Inspeções e Auditorias

- **Definição**: Avaliações formais dos processos de desenvolvimento e produtos de software, verificando conformidade com padrões e regulamentos.

- **Prática**
  - **Uso**: Assegurar que o desenvolvimento de software esteja alinhado com padrões internacionais e melhores práticas do setor.
  - **Caso de Uso Adicional**: Corporações globais realizam auditorias regulares para verificar a conformidade com normas ISO, ajudando a manter a certificação ISO 9001 e melhorando continuamente os processos de qualidade.

## Conclusão

Este aprofundamento nas ferramentas e técnicas de garantia da qualidade oferece aos estudantes uma base sólida para aplicar essas práticas de forma efetiva em ambientes de desenvolvimento real, melhorando a qualidade do software e a satisfação do cliente.


## TRABALHO II

- **Proposta 1 - Projeto de Simulação**: 
Em duplas,  escolham uma ferramenta de cada categoria para implementar em um projeto fictício. Desenvolvam um plano detalhado mostrando como cada ferramenta será integrada ao ciclo de vida de desenvolvimento do software, incluindo metas específicas para cada fase.

- **Proposta 2 - Invetigação de softwares**:
Em duplas, pesquisem sobre uma ferramenta de cada categoria e apresentem um relatório comparativo, destacando as principais características, vantagens e desvantagens de cada uma. Discutam como essas ferramentas podem ser aplicadas em diferentes contextos de desenvolvimento de software.