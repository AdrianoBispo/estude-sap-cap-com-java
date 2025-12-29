# 08. Extensibilidade e Multitenancy

Arquiteturas avançadas para cenários SaaS e modulares.

## Conteúdo

### 1. Arquitetura Multitenant (SaaS)
O CAP Java suporta multitenancy através do padrão **Sidecar MTX**, que isola dados dos tenants em containers HDI separados e gerencia o ciclo de vida de subscrição (`Subscribe`, `Upgrade`, `Unsubscribe`).

### 2. Plugins e Modularidade
Podemos criar extensões reutilizáveis (Plugins) empacotando modelos CDS e Event Handlers em artefatos Maven. O mecanismo de `AutoConfiguration` do Spring e `ServiceLoader` permite que essas extensões sejam plugadas automaticamente na aplicação consumidora.
