# Guia de Estudos SAP CAP utilizando Java e Spring Boot
Este repositório é um compêndio centralizado de conhecimento e arquitetura para o desenvolvimento de aplicações empresariais utilizando o **SAP Cloud Application Programming Model (CAP)** com o runtime **Java**.

## Filosofia e Abordagem
O CAP Java combina a modelagem declarativa do CDS com a robustez do ecossistema **Spring Boot**. A filosofia é oferecer uma arquitetura "Opinativa, mas Aberta" (Opinionated but Open), onde tarefas repetitivas são automatizadas pelo framework, permitindo foco total na lógica de negócio e na "Captura da Intenção".

## Estrutura do Repositório

Navegue pelo diretórios do nosso projeto:

1.  **[Fundamentos e Modelagem CDS](./01-fundamentos-e-modelagem-cds/README.md)**: A espinha dorsal. CDS, CDL, CSN e a API de Reflexão.
2.  **[Arquitetura e Configuração Spring](./02-arquitetura-e-configuracao-spring/README.md)**: A fusão do CAP com o Spring Boot, gestão de dependências e perfis.
3.  **[Runtime Java Core](./03-runtime-java-core/README.md)**: Como os Event Handlers, Contextos e Transações orquestram a execução.
4.  **[Dados, Persistência e CQL](./04-dados-persistencia-e-cql/README.md)**: O poder do `CqnService`, `PersistenceService` e a construção de queries tipadas.
5.  **[Interface de Usuário e Drafts](./05-interface-usuario-e-drafts/README.md)**: Suporte a Fiori Elements e o mecanismo de Rascunhos (Drafts).
6.  **[Integrações e Mensageria](./06-integracoes-e-mensageria/README.md)**: Consumo de serviços remotos (OData) e Event Mesh.
7.  **[Segurança e Compliance](./07-seguranca-e-compliance/README.md)**: Autenticação, Autorização e Auditoria automatizada.
8.  **[Extensibilidade e Multitenancy](./08-extensibilidade-e-multitenancy/README.md)**: Arquitetura SaaS e desenvolvimento de Plugins modulares.
9.  **[DevOps, Qualidade e Operações](./09-devops-qualidade-e-operacoes/README.md)**: Testes em camadas, Observabilidade e o Inner Loop de desenvolvimento.

## Organização e Nomenclatura dos Arquivos

Para garantir a organização, a rastreabilidade e a sequência lógica de leitura dos arquivos do projeto, foi então definida a seguinte **Regra de Nomenclatura Hierárquica**: **``DD.SS.FF_Slug_Descritivo``**

1. **DD (Diretório Principal)**: Dois dígitos representando a pasta raiz (ex: ``01`` para Fundamentos).
2. **SS (Subdiretório)**: Dois dígitos representando a subpasta (ex: ``01`` para Filosofia).
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
  - [Tutorial SAP - Crie um aplicativo comercial usando CAP para Java](https://developers.sap.com/mission.cap-java-app.html)
  - [Tutorial SAP - Crie um aplicativo com SAP Java Buildpack 2](https://developers.sap.com/tutorials/btp-cf-buildpacks-java-create.html)
  - [Tutorial SAP - Como desenvolver um App de Mensagens dentro do SAP BTP utilizando o Java ou Nodejs](https://developers.sap.com/mission.cp-enterprisemessaging-app-develop.html)

---

_Todo conteúdo presente nesse repositório foi gerado através do Notebook LM com base na documentação oficial da SAP Cloud Application Programming Model._
