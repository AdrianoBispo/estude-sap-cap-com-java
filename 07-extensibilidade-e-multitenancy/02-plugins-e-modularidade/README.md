# Módulo 07 (Parte 2): Plugins e Modularidade

![Infográfico sobre a Arquitetura de Plugins em Java](../Infograficos/07.02.02_Java_Plugin_Architecture.png)

Este módulo explora como construir aplicações CAP de forma modular, empacotando funcionalidades em "plugins" reutilizáveis. Isso permite compor aplicações complexas a partir de blocos de construção menores e independentes, promovendo o reuso e a manutenibilidade.

## Conteúdo

| Documento | Infográfico | Descrição |
| :--- | :--- | :--- |
| [O Toolkit de Extensibilidade](./07.02.01_Extensibility_Toolkit.pdf) | [Visualizar](../Infograficos/07.02.01_Extensibility_Toolkit.png) | Apresenta as ferramentas e os conceitos para estender modelos CDS existentes, adicionar novos campos a entidades e enriquecer a lógica de negócio de forma não invasiva. |
| [Arquitetura de Plugins em Java](./07.02.02_Java_Plugin_Architecture.pdf) | [Visualizar](../Infograficos/07.02.02_Java_Plugin_Architecture.png) | Detalha como empacotar modelos CDS e seus respectivos `Event Handlers` em um artefato Maven. A aplicação principal pode então consumir este artefato como uma dependência, e o CAP (via Spring `AutoConfiguration`) descobre e integra automaticamente o plugin. |
