# Módulo 06: Segurança e Compliance

![Infográfico sobre Segurança e Autenticação](./Infograficos/06.01.01_Seguranca_Autenticacao_Geral.png)

Segurança não é um adendo, mas uma parte integral do CAP. Este módulo cobre como o framework fornece recursos robustos e declarativos para proteger sua aplicação, desde a autenticação e autorização até a auditoria e conformidade com leis de privacidade.

## Tópicos Abordados

Explore os pilares de segurança do CAP Java através dos seguintes subdiretórios:

- **[01-autenticacao-e-autorizacao](./01-autenticacao-e-autorizacao/README.md):** Aprenda como o CAP se integra com provedores de identidade (como o SAP ID Service) e como definir regras de autorização de forma declarativa no modelo CDS com as anotações `@requires` e `@restrict`.

- **[02-audit-log-e-privacidade](./02-audit-log-e-privacidade/README.md):** Entenda como utilizar o `AuditLogService` para registrar eventos de segurança e como as anotações de privacidade (`@PersonalData`, `@SensitiveData`) ajudam a classificar dados e a cumprir com regulações como a GDPR.
