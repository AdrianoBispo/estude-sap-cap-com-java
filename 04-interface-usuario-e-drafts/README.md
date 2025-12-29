# 05. Interface de Usuário e Drafts

Como o backend Java suporta interfaces Fiori e fluxos de edição complexos.

## Conteúdo

### 1. Fiori Elements e Anotações
As anotações `@UI` no modelo CDS instruem o frontend Fiori Elements sobre layout, colunas e campos de busca. O backend Java serve esses metadados via OData.

### 2. Gestão de Rascunhos (Drafts)
O CAP Java implementa nativamente o suporte a **Drafts** (rascunhos). Quando ativado (`@odata.draft.enabled`), o `DraftService` gerencia automaticamente uma cópia "sombra" dos dados para edição, disparando eventos específicos como `DRAFT_NEW`, `DRAFT_PATCH` e `DRAFT_SAVE`.
