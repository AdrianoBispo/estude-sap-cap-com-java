# Módulo 05: Integrações e Mensageria

![Infográfico sobre o Consumo de Serviços Remotos](./Infograficos/05.01.01_Consumo_Servicos_Remotos.png)

Aplicações modernas raramente vivem isoladas. Este módulo aborda como o CAP Java se conecta a outros sistemas, seja de forma síncrona, consumindo APIs remotas, ou de forma assíncrona, através de uma arquitetura orientada a eventos.

## Tópicos Abordados

Explore os padrões de integração e comunicação através dos seguintes subdiretórios:

- **[01-consumo-servicos-remotos](./01-consumo-servicos-remotos/README.md):** Aprenda a definir e consumir serviços OData externos de forma transparente. O CAP utiliza o conceito de "projeções" para mapear entidades remotas e abstrai a complexidade da comunicação via SAP Cloud SDK.

- **[02-event-mesh-e-outbox](./02-event-mesh-e-outbox/README.md):** Domine a comunicação assíncrona. Entenda como o `MessagingService` se integra ao SAP Event Mesh para emissão e recebimento de eventos, e como o padrão *Transactional Outbox* garante a entrega confiável de mensagens.
