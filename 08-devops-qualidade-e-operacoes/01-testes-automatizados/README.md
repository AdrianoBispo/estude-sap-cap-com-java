# Módulo 08 (Parte 1): Testes Automatizados

![Infográfico sobre Testes em Camadas](../Infograficos/08.01.01_Testes_em_Camadas.png)

A qualidade do software é garantida por uma estratégia de testes sólida. Este módulo detalha a abordagem de "testes em camadas" recomendada para aplicações CAP, garantindo que tanto a lógica de negócio isolada quanto a integração completa dos serviços funcionem como esperado.

## Conteúdo

| Documento | Infográfico | Descrição |
| :--- | :--- | :--- |
| [Testes em Camadas](./08.01.01_Testes_em_Camadas.pdf) | [Visualizar](../Infograficos/08.01.01_Testes_em_Camadas.png) | Aprenda a implementar **testes de unidade**, que focam em validar a lógica dos seus `Event Handlers` de forma isolada (com mocks), e **testes de integração**, que usam `@SpringBootTest` e um banco de dados em memória (H2) para validar o fluxo completo da requisição, desde a API OData até a persistência. |
