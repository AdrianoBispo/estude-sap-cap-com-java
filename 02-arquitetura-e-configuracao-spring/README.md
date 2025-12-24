# 02. Arquitetura e Configuração Spring

O CAP Java não roda isolado; ele se integra profundamente ao Spring Boot. Este módulo cobre a fundação técnica da aplicação.

## Conteúdo

### 1. Integração Spring Boot
A biblioteca `cds-framework-spring-boot` fornece autoconfiguração completa. Beans do CAP (como serviços e contextos) são injetáveis via `@Autowired` no contexto do Spring, unindo o melhor dos dois mundos.

### 2. Gerenciamento de Dependências (Maven)
O uso do **Bill of Materials (BOM)** (`cds-services-bom`) é crucial para manter a consistência de versões entre os artefatos do SDK. O plugin `cds-maven-plugin` automatiza a geração de interfaces Java tipadas a partir do modelo CDS.
