# Módulo 05 (Parte 2): Mensageria com Event Mesh e Transactional Outbox

![Infográfico sobre Mensageria para Desenvolvedores Java](../Infograficos/05.02.01_Mensageria_Desenvolvedores_Java.png)

Este módulo aborda a comunicação assíncrona, um pilar de arquiteturas de microsserviços resilientes e escaláveis. O CAP Java fornece abstrações poderosas para interagir com um message broker (como o SAP Event Mesh) e implementa padrões essenciais para garantir a consistência dos dados.

## Conteúdo

| Documento | Infográfico | Descrição |
| :--- | :--- | :--- |
| [Mensageria para Desenvolvedores Java](./05.02.01_Mensageria_Desenvolvedores_Java.pdf) | [Visualizar](../Infograficos/05.02.01_Mensageria_Desenvolvedores_Java.png) | Introduz o `MessagingService`, a API do CAP para emitir e consumir eventos de forma declarativa e tipada, simplificando a interação com o SAP Event Mesh. |
| [Transactional Outbox em CAP Java](./05.02.02_Transactional_Outbox_CAP_Java.pdf) | [Visualizar](../Infograficos/05.02.02_Transactional_Outbox_CAP_Java.png) | Explica como o CAP implementa o padrão *Transactional Outbox*. Isso garante que um evento só seja enviado ao broker se a transação de negócio principal for concluída com sucesso, evitando inconsistências. |
