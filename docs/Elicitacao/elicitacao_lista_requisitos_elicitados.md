# Tabela Geral de Requisitos Elicitados

## Introdução

Este documento apresenta a consolidação de todos os requisitos elicitados para o sistema de transporte público do Distrito Federal, obtidos através da aplicação de três técnicas distintas de elicitação: Análise de Documentos, Brainstorm e Entrevista.  
A Tabela 1 reúne de forma organizada os requisitos funcionais (RF) e não funcionais (RNF) identificados, categorizando-os e estabelecendo sua rastreabilidade às fontes originais.

Cada requisito está vinculado à técnica de elicitação que o originou, permitindo o rastreamento completo desde sua identificação até sua documentação final.  
Esta rastreabilidade é fundamental para garantir a validação dos requisitos e facilitar futuras manutenções e refinamentos do sistema.

### Tabela 1: Lista de requisitos elicitados de todas as técnicas

| **ID** | **Requisito** | **Tipo** | **Implementado** | **Rastreabilidade (origem)** |
|:------:|:---------------|:----------|:----------------:|:------------------------------|
| **RF01** | Exibir a localização dos ônibus em tempo real no mapa | Funcional | Sim | Análise de Documentos (RF01), Entrevista (ENT03) |
| **RF02** | Mostrar o tempo estimado de chegada do ônibus à parada | Funcional | Sim | Entrevista (ENT04) |
| **RF03** | Permitir planejamento de viagem (origem → destino) com rotas sugeridas | Funcional | Sim | Análise de Documentos (RF05) |
| **RF04** | Permitir pesquisa por linhas e rotas de ônibus | Funcional | Sim | Análise de Documentos (RF02), Entrevista (ENT01) |
| **RF05** | Apresentar horários de saída e chegada dos transportes | Funcional | Sim | Entrevista (ENT02) |
| **RF06** | Oferecer um mapa interativo com os pontos de ônibus e suas linhas correspondentes | Funcional | Sim | Entrevista (ENT06) |
| **RF07** | Integrar informações de outros modais (metrô, outros ônibus) em rotas multimodais | Funcional | Sim | Análise de Documentos (RNI02), Brainstorm (BRS04) |
| **RF08** | Exibir informações de acessibilidade do ônibus (ex.: acessível para cadeirantes) | Funcional | Sim | Entrevista (ENT16) |
| **RF09** | Indicar lotação do ônibus (vazio, moderado, lotado) | Funcional | Não | Entrevista (ENT11), Brainstorm (BRS07) |
| **RF10** | Permitir que usuários reportem a lotação do ônibus (sistema colaborativo) | Funcional | Não | Entrevista (ENT11), Brainstorm (BRS03) |
| **RF11** | Enviar notificação quando o ônibus estiver a X minutos da parada | Funcional | Sim | Análise de Documentos (RNI01), Entrevista (ENT15), Brainstorm (BRS05) |
| **RF12** | Enviar alertas sobre atrasos, mudanças de rota ou alterações nos horários | Funcional | Sim | Entrevista (ENT05), Brainstorm (BRS05) |
| **RF13** | Oferecer recarga de cartão de transporte (ex.: integração com BRB Mobilidade) | Funcional | Não | Entrevista (ENT07) |
| **RF14** | Permitir integração com o cartão de transporte, incluindo saldo e recarga | Funcional | Não | Entrevista (ENT07) |
| **RF15** | Manter histórico de viagens do usuário | Funcional | Não | Análise de Documentos (RNI03) |
| **RF16** | Permitir reportar problemas (motorista, ônibus, cobrança) com dados do veículo e horário | Funcional | Não | Entrevista (ENT20) |
| **RF17** | Exibir preço da passagem por linha ou trajeto | Funcional | Sim | Entrevista (ENT23) |
| **RF18** | Listar linhas que passam em uma parada específica | Funcional | Sim | — |
| **RF19** | Disponibilizar versão web leve para acesso rápido em pontos de ônibus | Funcional | Sim | Brainstorm (BRS17) |
| **RF20** | Botão de pânico/emergência para alertar motorista e/ou autoridades | Funcional | Não | Brainstorm (BRS21) |
| **RF21** | Mostrar alertas de trânsito e acidentes | Funcional | Sim | Brainstorm (BRS12) |
| **RF22** | Permitir compartilhar trajeto em tempo real com outros usuários | Funcional | Não | Brainstorm (BRS22) |
| **RF23** | Exibir quantidade de assentos preferenciais e totais no ônibus | Funcional | Não | Brainstorm (BRS23) |
| **RF24** | Permitir favoritar linhas ou paradas para acesso rápido | Funcional | Sim | Entrevista (ENT14) |
| **RF25** | Ampliar a cobertura e exibir informações também em regiões afastadas do Distrito Federal | Funcional | Não | Entrevista (ENT08) |
| **RF26** | Filtrar ônibus por empresa operadora | Funcional | Sim | Análise de Documentos (RF03) |
| **RF27** | Visualizar quais veículos estão em operação no momento | Funcional | Sim | Análise de Documentos (RF04) |
| **RF28** | Permitir avaliação da qualidade do serviço de cada linha | Funcional | Não | Análise de Documentos (RNI04) |
| **RF29** | Sistema de gamificação para incentivar uso do transporte público | Funcional | Não | Brainstorm (BRS01) |
| **RF30** | Previsão inteligente de horários baseada em dados históricos e machine learning | Funcional | Sim | Brainstorm (BRS02) |
| **RF31** | Sistema de recompensas por uso sustentável do transporte público | Funcional | Não | Brainstorm (BRS09) |
| **RF32** | Exibir relatórios de impacto ambiental (CO₂ economizado) | Funcional | Não | Brainstorm (BRS11) |
| **RF33** | Suporte a comandos de voz para facilitar interação durante deslocamentos | Funcional | Não | Brainstorm (BRS14) |
| **RF34** | Integração com assistentes virtuais (Alexa, Google Assistant) | Funcional | Não | Brainstorm (BRS16) |
| **RF35** | Permitir rastreamento de múltiplas linhas de ônibus simultaneamente no mapa | Funcional | Não | Entrevista (ENT12) |
| **RF36** | Oferecer suporte multilíngue (português e inglês, no mínimo) | Funcional | Não | Entrevista (ENT22) |
| **RF37** | Permitir cadastro, login e autenticação de usuários no sistema | Funcional | Não | Brainstorm (BRS18) |
| **RF38** | Visualizar linhas que possuem ar-condicionado | Funcional | Não | Brainstorm (BRS20) |
| **RNF01** | As informações de horários e localização dos ônibus devem ser precisas | Não Funcional | Sim | Entrevista (ENT09) |
| **RNF02** | Rastreamento dos ônibus em tempo real deve ser confiável e sem falhas | Não Funcional | Sim | Entrevista (ENT13) |
| **RNF03** | Tempo de atualização da localização ≤ 20 segundos | Não Funcional | Não | ENT23 |
| **RNF04** | Interface acessível para idosos e pessoas com deficiência visual | Não Funcional | Não | Entrevista (ENT10), Brainstorm (BRS08) |
| **RNF05** | Sistema de notificação com som e vibração configuráveis | Não Funcional | Sim | Elicitação de Requisitos: Brainstorm (BRS18) |
| **RNF06** | Baixo consumo de bateria e dados móveis | Não Funcional | Sim | Brainstorm (BRS24) |
| **RNF07** | Compatibilidade com dispositivos Android e iOS | Não Funcional | Sim | Entrevista (ENT19) |
| **RNF08** | Proteção contra reportes falsos de lotação (mecanismo de confiança) | Não Funcional | Não | Brainstorm (BRS25) |
| **RNF09** | Dados de localização e pessoais protegidos conforme LGPD | Não Funcional | Sim | Entrevista (ENT21) |
| **RNF10** | Tempo de carregamento da tela principal < 3 segundos | Não Funcional | Não | Entrevista (ENT17) |
| **RNF11** | Funcionamento offline para consulta a rotas salvas e horários | Não Funcional | Não | Análise de Documentos (RNI05), Entrevista (ENT18), Brainstorm (BRS06) |
| **RNF12** | Integração segura com sistemas de pagamento (recarga de cartão) | Não Funcional | Não | Brainstorm (BRS10) |
| **RNF13** | Alta disponibilidade do sistema (≥ 98% uptime) | Não Funcional | Sim | Brainstorm (BRS26) |
| **RNF14** | Suporte a múltiplos usuários simultâneos sem lentidão | Não Funcional | Sim | Brainstorm (BRS15) |
| **RNF15** | Personalização da interface com base em preferências do usuário | Não Funcional | Não | Brainstorm (BRS13) |
| **RNF16** | Rastreamento dos ônibus em tempo real deve ser confiável (sem falhas críticas) | Não Funcional | Sim | Análise de Documentos (RND01) |
| **RNF17** | Suporte a leitores de tela e ajuste de contraste conforme WCAG 2.1 | Não Funcional | Sim | Análise de Documentos (RND02) |
| **RNF18** | Mensagens de erro devem identificar claramente o elemento que gerou o erro (visual e audível) | Não Funcional | Sim | Análise de Documentos (RND03) |
| **RNF19** | Transações devem ser completadas integralmente ou revertidas (atomicidade) | Não Funcional | Sim | Análise de Documentos (RND04) |
| **RNF20** | Interface deve ajustar automaticamente para diferentes resoluções de tela | Não Funcional | Sim | Análise de Documentos (RND05) |

*Tabela 1: Lista de requisitos elicitados de todas as técnicas - Autoria: Gabriel Maciel, João Ramos, 2025*

---

## Histórico de Versões

| **Versão** | **Data** | **Descrição** | **Autor(es)** | **Revisor(es)** |
|:-----------:|:--------:|:--------------|:---------------|:----------------|
| **1.0** | 18/10/2025 | Criação inicial da Tabela Geral de Requisitos Elicitados; consolidação das três técnicas | [Gabriel Maciel](https://github.com/GabrielMacielBR) | [João Gabriel](https://github.com/JoaoComTil) |
| **1.1** | 27/10/2025 | Adição de links bidirecionais para o documento `forward.md` | [Fernanda Vaz](https://github.com/Fernandavazgit1) | [Cauã Nicolas](https://github.com/cauanicolas) |
| **1.2** | 19/11/2025 | Adição coluna de Requisito Implementado | [João Ramos](https://github.com/Joaolramos) | [Gabriel Maciel](https://github.com/GabrielMacielBR) |
| **1.3** | 19/11/2025 | Adição rastreabilidade dos requisitos | [João Ramos](https://github.com/Joaolramos) | [Gabriel Maciel](https://github.com/GabrielMacielBR) |
| **1.4** | 24/11/2025 | Adição de requisitos não funcionais derivados (RNF16-RNF20) | [João Ramos](https://github.com/Joaolramos) | [Gabriel Maciel](https://github.com/GabrielMacielBR) |
