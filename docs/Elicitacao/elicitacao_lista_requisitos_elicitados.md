# Tabela Geral de Requisitos Elicitados

## Introdução

Este documento apresenta a consolidação de todos os requisitos elicitados para o sistema de transporte público do Distrito Federal, obtidos através da aplicação de três técnicas distintas de elicitação: Análise de Documentos, Brainstorm e Entrevista.  
A Tabela 1 reúne de forma organizada os requisitos funcionais (RF) e não funcionais (RNF) identificados, categorizando-os e estabelecendo sua rastreabilidade às fontes originais.

Cada requisito está vinculado à técnica de elicitação que o originou, permitindo o rastreamento completo desde sua identificação até sua documentação final.  
Esta rastreabilidade é fundamental para garantir a validação dos requisitos e facilitar futuras manutenções e refinamentos do sistema.

### Tabela 1: Lista de requisitos elicitados de todas as técnicas

| **ID** | **Requisito** | **Tipo** | **Rastreabilidade (origem)** |
|:------:|:---------------|:----------|:------------------------------|
| [**RF01**](../Pos-rastreabilidade/forward.md#RF01) | Exibir a localização dos ônibus em tempo real no mapa | Funcional | Análise de Documentos (RF01), Entrevista (ENT03) |
| [**RF02**](../Pos-rastreabilidade/forward.md#RF02) | Mostrar o tempo estimado de chegada do ônibus à parada | Funcional | Entrevista (ENT04) |
| [**RF03**](../Pos-rastreabilidade/forward.md#RF03) | Permitir planejamento de viagem (origem → destino) com rotas sugeridas | Funcional | Análise de Documentos (RF05) |
| [**RF04**](../Pos-rastreabilidade/forward.md#RF04) | Permitir pesquisa por linhas e rotas de ônibus | Funcional | Análise de Documentos (RF02), Entrevista (ENT01) |
| [**RF05**](../Pos-rastreabilidade/forward.md#RF05) | Apresentar horários de saída e chegada dos transportes | Funcional | Entrevista (ENT02) |
| [**RF06**](../Pos-rastreabilidade/forward.md#RF06) | Oferecer um mapa interativo com os pontos de ônibus e suas linhas correspondentes | Funcional | Entrevista (ENT06) |
| [**RF07**](../Pos-rastreabilidade/forward.md#RF07) | Integrar informações de outros modais (metrô, outros ônibus) em rotas multimodais | Funcional | Análise de Documentos (RNI02), Brainstorm (BRS04) |
| [**RF08**](../Pos-rastreabilidade/forward.md#RF08) | Exibir informações de acessibilidade do ônibus (ex.: acessível para cadeirantes) | Funcional | Entrevista (ENT16) |
| [**RF09**](../Pos-rastreabilidade/forward.md#RF09) | Indicar lotação do ônibus (vazio, moderado, lotado) | Funcional | Entrevista (ENT11), Brainstorm (BRS07) |
| [**RF10**](../Pos-rastreabilidade/forward.md#RF10) | Permitir que usuários reportem a lotação do ônibus (sistema colaborativo) | Funcional | Entrevista (ENT11), Brainstorm (BRS03) |
| [**RF11**](../Pos-rastreabilidade/forward.md#RF11) | Enviar notificação quando o ônibus estiver a X minutos da parada | Funcional | Análise de Documentos (RNI01), Entrevista (ENT15), Brainstorm (BRS05) |
| [**RF12**](../Pos-rastreabilidade/forward.md#RF12) | Enviar alertas sobre atrasos, mudanças de rota ou alterações nos horários | Funcional | Entrevista (ENT05), Brainstorm (BRS05) |
| [**RF13**](../Pos-rastreabilidade/forward.md#RF13) | Oferecer recarga de cartão de transporte (ex.: integração com BRB Mobilidade) | Funcional | Entrevista (ENT07) |
| [**RF14**](../Pos-rastreabilidade/forward.md#RF14) | Permitir integração com o cartão de transporte, incluindo saldo e recarga | Funcional | Entrevista (ENT07) |
| [**RF15**](../Pos-rastreabilidade/forward.md#RF15) | Manter histórico de viagens do usuário | Funcional | Análise de Documentos (RNI03) |
| [**RF16**](../Pos-rastreabilidade/forward.md#RF16) | Permitir reportar problemas (motorista, ônibus, cobrança) com dados do veículo e horário | Funcional | Entrevista (ENT20) |
| [**RF17**](../Pos-rastreabilidade/forward.md#RF17) | Exibir preço da passagem por linha ou trajeto | Funcional | — |
| [**RF18**](../Pos-rastreabilidade/forward.md#RF18) | Listar linhas que passam em uma parada específica | Funcional | — |
| [**RF19**](../Pos-rastreabilidade/forward.md#RF19) | Disponibilizar versão web leve para acesso rápido em pontos de ônibus | Funcional | Brainstorm (BRS17) |
| [**RF20**](../Pos-rastreabilidade/forward.md#RF20) | Botão de pânico/emergência para alertar motorista e/ou autoridades | Funcional | — |
| [**RF21**](../Pos-rastreabilidade/forward.md#RF21) | Mostrar alertas de trânsito e acidentes | Funcional | Brainstorm (BRS12) |
| [**RF22**](../Pos-rastreabilidade/forward.md#RF22) | Permitir compartilhar trajeto em tempo real com outros usuários | Funcional | — |
| [**RF23**](../Pos-rastreabilidade/forward.md#RF23) | Exibir quantidade de assentos preferenciais e totais no ônibus | Funcional | — |
| [**RF24**](../Pos-rastreabilidade/forward.md#RF24) | Permitir favoritar linhas ou paradas para acesso rápido | Funcional | Entrevista (ENT14) |
| [**RF25**](../Pos-rastreabilidade/forward.md#RF25) | Ampliar a cobertura e exibir informações também em regiões afastadas do Distrito Federal | Funcional | Entrevista (ENT08) |
| [**RF26**](../Pos-rastreabilidade/forward.md#RF26) | Filtrar ônibus por empresa operadora | Funcional | Análise de Documentos (RF03) |
| [**RF27**](../Pos-rastreabilidade/forward.md#RF27) | Visualizar quais veículos estão em operação no momento | Funcional | Análise de Documentos (RF04) |
| [**RF28**](../Pos-rastreabilidade/forward.md#RF28) | Permitir avaliação da qualidade do serviço de cada linha | Funcional | Análise de Documentos (RNI04) |
| [**RF29**](../Pos-rastreabilidade/forward.md#RF29) | Sistema de gamificação para incentivar uso do transporte público | Funcional | Brainstorm (BRS01) |
| [**RF30**](../Pos-rastreabilidade/forward.md#RF30) | Previsão inteligente de horários baseada em dados históricos e machine learning | Funcional | Brainstorm (BRS02) |
| [**RF31**](../Pos-rastreabilidade/forward.md#RF31) | Sistema de recompensas por uso sustentável do transporte público | Funcional | Brainstorm (BRS09) |
| [**RF32**](../Pos-rastreabilidade/forward.md#RF32) | Exibir relatórios de impacto ambiental (CO₂ economizado) | Funcional | Brainstorm (BRS11) |
| [**RF33**](../Pos-rastreabilidade/forward.md#RF33) | Suporte a comandos de voz para facilitar interação durante deslocamentos | Funcional | Brainstorm (BRS14) |
| [**RF34**](../Pos-rastreabilidade/forward.md#RF34) | Integração com assistentes virtuais (Alexa, Google Assistant) | Funcional | Brainstorm (BRS16) |
| [**RF35**](../Pos-rastreabilidade/forward.md#RF35) | Permitir rastreamento de múltiplas linhas de ônibus simultaneamente no mapa | Funcional | Entrevista (ENT12) |
| [**RF36**](../Pos-rastreabilidade/forward.md#RF36) | Oferecer suporte multilíngue (português e inglês, no mínimo) | Funcional | Entrevista (ENT22) |
| [**RF37**](../Pos-rastreabilidade/forward.md#RF37) | Permitir cadastro, login e autenticação de usuários no sistema | Funcional | Brainstorm (BRS18) |
| [**RF38**](../Pos-rastreabilidade/forward.md#RF38) | Visualizar linhas que possuem ar-condicionado | Funcional | Brainstorm (BRS20) |
| [**RNF01**](../Pos-rastreabilidade/forward.md#RNF01) | As informações de horários e localização dos ônibus devem ser precisas | Não Funcional | Entrevista (ENT09) |
| [**RNF02**](../Pos-rastreabilidade/forward.md#RNF02) | Rastreamento dos ônibus em tempo real deve ser confiável e sem falhas | Não Funcional | Entrevista (ENT13) |
| [**RNF03**](../Pos-rastreabilidade/forward.md#RNF03) | Tempo de atualização da localização ≤ 20 segundos | Não Funcional | ENT23 |
| [**RNF04**](../Pos-rastreabilidade/forward.md#RNF04) | Interface acessível para idosos e pessoas com deficiência visual | Não Funcional | Entrevista (ENT10), Brainstorm (BRS08) |
| [**RNF05**](../Pos-rastreabilidade/forward.md#RNF05) | Sistema de notificação com som e vibração configuráveis | Não Funcional | Elicitação de Requisitos: Brainstorm (BRS18) |
| [**RNF06**](../Pos-rastreabilidade/forward.md#RNF06) | Baixo consumo de bateria e dados móveis | Não Funcional | — |
| [**RNF07**](../Pos-rastreabilidade/forward.md#RNF07) | Compatibilidade com dispositivos Android e iOS | Não Funcional | Entrevista (ENT19) |
| [**RNF08**](../Pos-rastreabilidade/forward.md#RNF08) | Proteção contra reportes falsos de lotação (mecanismo de confiança) | Não Funcional | — |
| [**RNF09**](../Pos-rastreabilidade/forward.md#RNF09) | Dados de localização e pessoais protegidos conforme LGPD | Não Funcional | Entrevista (ENT21) |
| [**RNF10**](../Pos-rastreabilidade/forward.md#RNF10) | Tempo de carregamento da tela principal < 3 segundos | Não Funcional | Entrevista (ENT17) |
| [**RNF11**](../Pos-rastreabilidade/forward.md#RNF11) | Funcionamento offline para consulta a rotas salvas e horários | Não Funcional | Análise de Documentos (RNI05), Entrevista (ENT18), Brainstorm (BRS06) |
| [**RNF12**](../Pos-rastreabilidade/forward.md#RNF12) | Integração segura com sistemas de pagamento (recarga de cartão) | Não Funcional | Brainstorm (BRS10) |
| [**RNF13**](../Pos-rastreabilidade/forward.md#RNF13) | Alta disponibilidade do sistema (≥ 98% uptime) | Não Funcional | — |
| [**RNF14**](../Pos-rastreabilidade/forward.md#RNF14) | Suporte a múltiplos usuários simultâneos sem lentidão | Não Funcional | Brainstorm (BRS15) |
| [**RNF15**](../Pos-rastreabilidade/forward.md#RNF15) | Personalização da interface com base em preferências do usuário | Não Funcional | Brainstorm (BRS13) |

*Tabela 1: Lista de requisitos elicitados de todas as técnicas - Autoria: Gabriel Maciel, 2025*

---

## Histórico de Versões

| **Versão** | **Data** | **Descrição** | **Autor(es)** | **Revisor(es)** |
|:-----------:|:--------:|:--------------|:---------------|:----------------|
| **1.0** | 18/10/2025 | Criação inicial da Tabela Geral de Requisitos Elicitados; consolidação das três técnicas | [Gabriel Maciel](https://github.com/GabrielMacielBR) | [João Gabriel](https://github.com/JoaoComTil) |
| **1.1** | 27/10/2025 | Adição de links bidirecionais para o documento `forward.md` | [Fernanda Vaz](https://github.com/Fernandavazgit1) | [Cauã Nicolas](https://github.com/cauanicolas) |
