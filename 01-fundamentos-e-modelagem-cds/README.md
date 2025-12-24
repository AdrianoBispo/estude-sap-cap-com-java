# 01. Fundamentos e Modelagem (CDS)

O modelo de domínio é a fonte única da verdade no CAP. Este módulo explora como definir a estrutura e o comportamento da aplicação de forma agnóstica à tecnologia.

## Conteúdo

### 1. Filosofia e Intenção
O foco é capturar o *o que* (intenção do negócio) e deixar o *como* (implementação técnica) para o framework. Utilizamos Aspectos como `cuid` (chaves canônicas) e `managed` (auditoria automática) para criar modelos limpos.

### 2. Linguagens Core: CDL e CSN
*   **CDL (Conceptual Definition Language):** A linguagem legível por humanos usada nos arquivos `.cds`. É projetada para ser concisa e expressiva.
*   **CSN (Core Schema Notation):** O formato JSON compilado e otimizado que o runtime Java consome. É a ponte universal para gerar SQL, OData e outros artefatos.

### 3. Introspecção e Reflexão (`CdsModel`)
Diferente de frameworks estáticos, o CAP Java opera sobre um "Modelo Vivo". A interface `CdsModel` permite navegar programaticamente por todas as entidades, associações e anotações em tempo de execução, habilitando lógicas genéricas poderosas.
