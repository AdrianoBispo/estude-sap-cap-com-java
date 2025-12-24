# 09. DevOps, Qualidade e Operações

Garantindo a qualidade do código e a operação eficiente em produção.

## Conteúdo

### 1. Testes Automatizados
Adotamos uma pirâmide de testes:
*   **Testes de Unidade:** Focados na lógica pura dos Handlers (usando Mockito).
*   **Testes de Serviço/Integração:** Usando `@SpringBootTest` e `MockMvc` para validar o fluxo completo, incluindo a tradução OData->CQN e persistência em banco H2 em memória.

### 2. Otimização e Observabilidade
*   **Inner Loop:** O comando `mvn cds:watch` acelera o desenvolvimento local com reinício automático.
*   **Observabilidade:** Integração com **OpenTelemetry** para rastreamento distribuído e logging estruturado, além de suporte a JMX e Actuators para monitoramento da saúde da aplicação.
