# 04. Dados, Persistência e CQL

O CAP Java abstrai o banco de dados através de serviços e uma linguagem de consulta unificada.

## Conteúdo

### 1. Manipulação de Dados (`CdsData`)
Os dados são representados pela interface `CdsData` (uma extensão de `Map<String, Object>`). Para maior segurança e produtividade, utilizamos interfaces geradas automaticamente (Accessor Interfaces) que permitem acesso tipado (ex: `book.getTitle()`).

### 2. CQL Builder e Queries
*   **CQL (CDS Query Language):** Usamos a API fluente (ex: `Select.from(BOOKS)...`) para construir consultas seguras e portáveis, evitando strings SQL manuais.
*   **Persistence Service:** O serviço técnico que traduz CQN para SQL nativo do banco de dados (HANA, PostgreSQL, H2).
