# Módulo 02: Runtime Java Core

![Infográfico sobre a Arquitetura Modular do CAP Java](./Infograficos/02.01.01_Introducao_Arquitetura_Modular_CAP_Java.png)

Este módulo é o coração da aplicação CAP com Java. Ele detalha como o CAP processa requisições, gerencia o ciclo de vida dos eventos e se integra perfeitamente com o ecossistema Spring Boot para criar aplicações robustas e escaláveis.

## Tópicos Abordados

Explore os componentes centrais do runtime Java através dos seguintes subdiretórios:

- **[01-arquitetura](./01-arquitetura/README.md):** Tenha uma visão geral da arquitetura modular do CAP Java, projetada para aplicações Cloud-Native, e aprenda a configurá-la.

- **[02-gerenciamento-dependencias-maven](./02-gerenciamento-dependencias-maven/README.md):** Entenda como gerenciar as dependências do seu projeto com Maven, utilizando o Bill of Materials (BOM) para garantir a consistência das versões e como realizar upgrades.

- **[03-integracao-spring-boot](./03-integracao-spring-boot/README.md):** Veja como o CAP e o Spring Boot se unem, aproveitando o melhor dos dois mundos para o desenvolvimento de aplicações empresariais.

- **[04-event-handlers-e-logica](./04-event-handlers-e-logica/README.md):** Mergulhe no modelo de programação orientado a eventos do CAP, aprendendo a implementar a lógica de negócio com `Event Handlers` para as fases `@Before`, `@On` e `@After`.

- **[05-contextos-e-transacoes](./05-contextos-e-transacoes/README.md):** Domine o gerenciamento de estado com `RequestContext` e o controle de transações com `ChangeSetContext`, garantindo a integridade dos dados.
