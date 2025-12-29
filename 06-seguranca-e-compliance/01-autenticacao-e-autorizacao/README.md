# Módulo 06 (Parte 1): Autenticação e Autorização

![Infográfico sobre o Guia Prático de Segurança em Java](../Infograficos/06.01.02_Guia_Pratico_Seguranca_Java.png)

Este módulo aborda os mecanismos pelos quais o CAP protege seus serviços. A autenticação (quem é o usuário?) é tratada de forma transparente pela integração com o XSUAA, enquanto a autorização (o que o usuário pode fazer?) é definida de forma declarativa e poderosa diretamente no modelo de dados.

## Conteúdo

| Documento | Infográfico | Descrição |
| :--- | :--- | :--- |
| [Segurança e Autenticação Geral](./06.01.01_Seguranca_Autenticacao_Geral.pdf) | [Visualizar](../Infograficos/06.01.01_Seguranca_Autenticacao_Geral.png) | Apresenta a arquitetura de segurança do CAP, baseada em OAuth 2.0 e na integração com o serviço XSUAA do SAP BTP. |
| [Guia Prático de Segurança em Java](./06.01.02_Guia_Pratico_Seguranca_Java.pdf) | [Visualizar](../Infograficos/06.01.02_Guia_Pratico_Seguranca_Java.png) | Detalha como usar as anotações `@requires` (para papéis de usuário) e `@restrict` (para privilégios de CRUD) para implementar um modelo de autorização robusto que é automaticamente aplicado pelo runtime. |
