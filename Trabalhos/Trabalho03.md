# Trabalho III - Plano de Teste de Software

## ENTREGA PARA O DIA 30/08/2024

** O trabalho pode ser feito em dupla ou individual. **

Criar um plano de teste de software para um sistema de sua escolha. Você pode escolher um sistema real ou fictício, desde que seja possível descrever os tipos de testes a serem realizados, os casos de teste, e os cenários de aplicação. O plano de teste deve seguir a estrutura sugerida abaixo.

O item 2 (Tipos de Testes) deve incluir pelo menos 3 tipos de testes, como testes de unidade, integração, funcional, desempenho, aceitação, instalação, etc. Para cada tipo de teste, 2 casos mínimos obrigatórios, é necessário descrever o objetivo, os casos de teste, e as ferramentas que serão utilizadas.

O item 3 (Casos de Teste) é onde você deve detalhar os casos de teste a serem aplicados em cada tipo de teste, incluindo pré-condições, passos a seguir, dados de entrada e resultados esperados.

O item 5 (Cenários de Aplicação) é onde você deve definir dois cenários de teste, um em uma feature existente e outro em uma feature proposta. Para cada cenário, descreva os tipos de teste a serem aplicados e os resultados esperados.

# **Plano de Teste de Software**

## **1. Introdução**
   - **Objetivo:** 
     - Descrever os objetivos do plano de teste. Exemplo: "O objetivo deste plano de teste é assegurar que o software [Nome do Software] atenda aos requisitos especificados, identificando defeitos e garantindo a qualidade do produto final."
   - **Escopo:**
     - Definir os itens que serão testados. Exemplo: "O escopo dos testes inclui funcionalidades principais como autenticação de usuários, processamento de pedidos, e integração com o sistema de pagamentos."
   - **Ferramentas de Teste:**
     - Mencionar as ferramentas que serão utilizadas, como JUnit para testes de unidade, PHPUnit para testes PHP, Selenium para testes funcionais, etc. Decidir se os testes serão automatizados, manuais, ou uma combinação de ambos.

## **2. Tipos de Testes**
   - **Testes de Unidade**
     - **Objetivo:** Verificar a correta implementação das menores unidades de código.
     - **Casos de Teste:** Descrever os casos de teste para unidades de código individuais. Exemplo: Teste de métodos de classes, validação de entradas, etc.
     - **Ferramentas:** Exemplo: JUnit, NUnit, PHPUnit.

   - **Testes de Integração**
     - **Objetivo:** Garantir que diferentes módulos ou serviços do software funcionem bem juntos.
     - **Casos de Teste:** Descrever os casos que envolvem a integração entre diferentes módulos. Exemplo: Integração entre o módulo de login e o módulo de pagamentos.
     - **Ferramentas:** Exemplo: TestNG, Apache JMeter.

   - **Testes Funcionais**
     - **Objetivo:** Validar que o software cumpre com as funcionalidades exigidas.
     - **Casos de Teste:** Descrever os casos que testam as funcionalidades do sistema. Exemplo: Testar o fluxo completo de um pedido, desde a adição ao carrinho até a confirmação do pagamento.
     - **Ferramentas:** Exemplo: Selenium, Cucumber.

   - **Testes de Desempenho**
     - **Objetivo:** Avaliar como o software se comporta em termos de rapidez, escalabilidade e estabilidade sob cargas variáveis.
     - **Casos de Teste:** Descrever cenários de teste para medir tempo de resposta, throughput, etc. Exemplo: Testar o sistema sob carga de 1000 usuários simultâneos.
     - **Ferramentas:** Exemplo: Apache JMeter, Gatling.

   - **Testes de Aceitação**
     - **Objetivo:** Confirmar que o software está pronto para ser entregue ao cliente final, de acordo com os critérios de aceitação.
     - **Casos de Teste:** Descrever os casos que envolvem a validação dos requisitos do cliente. Exemplo: Verificação de que todas as funcionalidades principais são acessíveis e funcionam como esperado.
     - **Ferramentas:** Exemplo: TestRail, FitNesse.

   - **Testes de Instalação**
     - **Objetivo:** Garantir que o software pode ser instalado corretamente em todos os ambientes suportados.
     - **Casos de Teste:** Descrever os casos que validam o processo de instalação em diferentes ambientes. Exemplo: Testar a instalação em um ambiente Windows, Linux, e MacOS.
     - **Ferramentas:** Exemplo: InstallShield, Wix Toolset.

## **3. Casos de Teste**
   - **Descrição:** Detalhar os casos de teste a serem aplicados em cada tipo de teste, incluindo pré-condições, passos a seguir, dados de entrada e resultados esperados.
   - **Cobertura:** Indicar a abrangência dos casos de teste, explicando se todos os cenários críticos foram contemplados ou se há algum componente que não foi testado.

## **4. Relatório de Resultados**
   - **Resultados dos Testes:** Relatar os resultados obtidos após a execução dos testes, incluindo os casos que passaram e falharam.
   - **Cobertura de Testes:** Avaliar se a cobertura foi suficiente. Caso tenha havido falhas, identificar os componentes que deveriam ter sido testados, mas não foram.

## **5. Cenários de Aplicação**
   - **Cenário 1: Teste em Feature Existente**
     - Escolher uma funcionalidade já existente e aplicar testes de unidade, integração, funcional e desempenho.
     - Exemplo: Testar o módulo de login, verificando a correta integração com o sistema de autenticação, e medir a resposta sob carga.

   - **Cenário 2: Teste em Feature Proposta**
     - Definir uma funcionalidade que poderia ser adicionada ao software e aplicar testes funcionais, de desempenho, de aceitação e de instalação.
     - Exemplo: Propor e testar a adição de uma nova funcionalidade de notificação por e-mail, incluindo a instalação do serviço em diferentes ambientes.

## **6. Conclusão**
   - Resumir as descobertas e apresentar recomendações para melhorias ou próximos passos.

