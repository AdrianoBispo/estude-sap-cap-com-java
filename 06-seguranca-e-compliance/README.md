# 07. Segurança e Compliance

Segurança é um cidadão de primeira classe, configurada "Out-of-the-Box".

## Conteúdo

### 1. Autenticação e Autorização
*   **Autenticação:** Integração automática com XSUAA e Identity Authentication Service (IAS).
*   **Autorização:** Definida no modelo CDS com `@restrict` e `@requires`. O runtime Java aplica essas regras automaticamente nas consultas.

### 2. Audit Log e Privacidade
O serviço `AuditLogService` fornece uma API para registrar acesso e modificação de dados sensíveis. Anotações como `@PersonalData` ajudam a automatizar a conformidade com regulamentações de privacidade.
