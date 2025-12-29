# 06. Integrações e Mensageria

Conectando sua aplicação ao mundo exterior de forma síncrona e assíncrona.

## Conteúdo

### 1. Consumo de Serviços Remotos
Utilizamos `RemoteServices` para consumir APIs OData externas (ex: S/4HANA). O CAP utiliza o conceito de **Projeções** para mapear entidades remotas para o modelo local e abstrai a complexidade de destinos e autenticação via SAP Cloud SDK.

### 2. Event Mesh e Outbox
*   **Mensageria:** O `MessagingService` permite emitir e receber eventos de negócio de forma tipada, integrando-se com SAP Event Mesh.
*   **Transactional Outbox:** Garante a consistência eventual, armazenando mensagens no banco de dados na mesma transação do negócio antes de enviá-las ao broker.
