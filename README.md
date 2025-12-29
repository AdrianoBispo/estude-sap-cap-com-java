# Guia de Estudos SAP CAP utilizando Java e Spring Boot

![Infografico - Guia de Desenvolvimento SAP CAP com Java](./Infografico%20-%20Arquitetura%20e%20Extensibilidade%20CAP%20Java.png)

Este repositório é um compêndio centralizado de conhecimento e arquitetura para o desenvolvimento de aplicações empresariais utilizando o **SAP Cloud Application Programming Model (CAP)** com o runtime **Java**.

## Filosofia e Abordagem
O CAP Java combina a modelagem declarativa do CDS com a robustez do ecossistema **Spring Boot**. A filosofia é oferecer uma arquitetura "Opinativa, mas Aberta" (Opinionated but Open), onde tarefas repetitivas são automatizadas pelo framework, permitindo foco total na lógica de negócio e na "Captura da Intenção".

## Estrutura do Repositório

Navegue pelos diretórios do nosso projeto:

1.  **[Fundamentos e Modelagem CDS](./01-fundamentos-e-modelagem-cds/README.md)**: A espinha dorsal. Explore a filosofia do CAP, as linguagens CDL, CSN, CXN, o compilador e as técnicas de modelagem performática.
2.  **[Runtime Java Core](./02-runtime-java-core/README.md)**: O coração da aplicação. Entenda a arquitetura modular, a integração com Spring Boot, o gerenciamento de dependências, a lógica de negócios com Event Handlers e a gestão de transações.
3.  **[Dados, Persistência e CQL](./03-dados-persistencia-e-cql/README.md)**: Acesso e manipulação de dados. Domine a arquitetura de persistência, o `CqnService`, `PersistenceService` e a construção de queries tipadas com CQL.
4.  **[Interface de Usuário e Drafts](./04-interface-usuario-e-drafts/README.md)**: A experiência do usuário. Aprenda a criar interfaces ricas com Fiori Elements através de anotações e a gerenciar o estado de rascunho (Drafts).
5.  **[Integrações e Mensageria](./05-integracoes-e-mensageria/README.md)**: Conectando sistemas. Explore o consumo de serviços remotos (OData) e a comunicação assíncrona com SAP Event Mesh e o padrão Transactional Outbox.
6.  **[Segurança e Compliance](./06-seguranca-e-compliance/README.md)**: Protegendo sua aplicação. Implemente autenticação, autorização, logging de auditoria e garanta a privacidade dos dados.
7.  **[Extensibilidade e Multitenancy](./07-extensibilidade-e-multitenancy/README.md)**: Escalando a aplicação. Desenvolva arquiteturas SaaS multi-inquilino e crie modularidade com plugins.
8.  **[DevOps, Qualidade e Operações](./08-devops-qualidade-e-operacoes/README.md)**: Do desenvolvimento à produção. Adote testes automatizados em camadas, otimização, observabilidade e domine o ciclo de desenvolvimento (Inner Loop).

## Organização e Nomenclatura dos Arquivos

Para garantir a organização, a rastreabilidade e a sequência lógica de leitura dos arquivos do projeto, foi então definida a seguinte **Regra de Nomenclatura Hierárquica**: **`DD.SS.FF_Slug_Descritivo`**

1. **DD (Diretório Principal)**: Dois dígitos representando a pasta raiz.
2. **SS (Subdiretório)**: Dois dígitos representando a subpasta.
3. **FF (Fila/Ordem)**: Dois dígitos definindo a ordem de leitura recomendada dentro daquele tópico.
4. **Slug Descritivo**: O nome original ou simplificado do tópico, separado por underlines para legibilidade.

## Links Úteis
  
  ### Documentação Oficial
  - [Capire - Documentação Oficial da SAP CAP](https://cap.cloud.sap/docs/)

  ### SAP Learning - Cursos Oficiais da SAP para você se aprofundar
  - [SAP Learning - Introduction to SAP Cloud Application Programming Model](https://learning.sap.com/courses/introduction-to-sap-cloud-application-programming-model)
  - [SAP Learning - Desenvolva extensões com CAP seguindo o Guia do desenvolvedor SAP BTP](https://learning.sap.com/courses/develop-extensions-with-cap-following-the-sap-btp-developer-s-guide)
  - [SAP Learning - Desenvolvendo um aplicativo SAP Fiori Elements baseado em um serviço CAP OData V4](https://learning.sap.com/courses/developing-an-sap-fiori-elements-app-based-on-a-cap-odata-v4-service)

  ### SAP Tutorials - Aprenda Praticando por meio dos tutoriais oficiais da SAP
  - [Tutorial SAP - Crie um aplicativo comercial usando CAP para Java](httpshttps://developers.sap.com/mission.cap-java-app.html)
  - [Tutorial SAP - Crie um aplicativo com SAP Java Buildpack 2](https://developers.sap.com/tutorials/btp-cf-buildpacks-java-create.html)
  - [Tutorial SAP - Como desenvolver um App de Mensagens dentro do SAP BTP utilizando o Java ou Nodejs](https://developers.sap.com/mission.cp-enterprisemessaging-app-develop.html)

---

_Todo conteúdo presente nesse repositório foi gerado através do Notebook LM com base na documentação oficial da SAP Cloud Application Programming Model._
