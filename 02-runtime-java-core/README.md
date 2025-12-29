# 03. Runtime Java Core

Este é o motor da aplicação. Aqui aprendemos como o CAP processa requisições e eventos.

## Conteúdo

### 1. Event Handlers e Lógica
Toda a lógica de negócio reside em classes anotadas com `@Component` e `@ServiceName`, implementando a interface `EventHandler`. O ciclo de vida é dividido em fases:
*   **`@Before`**: Validações e interceptação.
*   **`@On`**: Implementação core (ex: leitura/escrita).
*   **`@After`**: Enriquecimento de resultados.

### 2. Contextos e Transações
*   **`RequestContext` & `EventContext`**: Armazenam o estado da requisição (User Info, Tenant, Locale) e são acessíveis via `ThreadLocal` ou injeção.
*   **`ChangeSetContext`**: Gerencia transações automaticamente. O CAP se integra ao gerenciador de transações do Spring, suportando a anotação `@Transactional` para controle fino.
