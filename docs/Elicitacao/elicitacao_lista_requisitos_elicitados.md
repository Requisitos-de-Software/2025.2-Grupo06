# Tabela Geral de Requisitos Elicitados

## Introdução

Este documento apresenta a consolidação de todos os requisitos elicitados para o sistema de transporte público do Distrito Federal, obtidos através da aplicação de três técnicas distintas de elicitação: Análise de Documentos, Brainstorm e Entrevista. A Tabela 1 reúne de forma organizada os requisitos funcionais (RF) e não funcionais (RNF) identificados, categorizando-os e estabelecendo sua rastreabilidade às fontes originais.

Cada requisito está vinculado à técnica de elicitação que o originou, permitindo o rastreamento completo desde sua identificação até sua documentação final. Esta rastreabilidade é fundamental para garantir a validação dos requisitos e facilitar futuras manutenções e refinamentos do sistema.

### Tabela 1: Lista de requisitos elicitados de todas as técnicas

| ID    | Requisito                                                                                   | Tipo           | Rastreabilidade (origem)                            |
|--------------|---------------------------------------------------------------------------------------------|----------------|-----------------------------------------------------|
| RF01  | Exibir a localização dos ônibus em tempo real no mapa                                       | Funcional      | Elicitação de Requisitos: Análise de Documentos (RF01), Entrevista (ENT03) |
| RF02  | Mostrar o tempo estimado de chegada do ônibus à parada                                      | Funcional      | Elicitação de Requisitos: Entrevista (ENT04) |
| RF03  | Permitir planejamento de viagem (origem → destino) com rotas sugeridas                      | Funcional      | Elicitação de Requisitos: Análise de Documentos (RF05) |
| RF04  | Permitir pesquisa por linhas e rotas de ônibus                                              | Funcional      | Elicitação de Requisitos: Análise de Documentos (RF02), Entrevista (ENT01) |
| RF05  | Apresentar horários de saída e chegada dos transportes                                      | Funcional      | Elicitação de Requisitos: Entrevista (ENT02) |
| RF06  | Oferecer um mapa interativo com os pontos de ônibus e suas linhas correspondentes           | Funcional      | Elicitação de Requisitos: Entrevista (ENT06) |
| RF07  | Integrar informações de outros modais (metrô, outros ônibus) em rotas multimodais           | Funcional      | Elicitação de Requisitos: Análise de Documentos (RNI02), Brainstorm (BRS04) |
| RF08  | Exibir informações de acessibilidade do ônibus (ex.: acessível para cadeirantes)            | Funcional      | Elicitação de Requisitos: Entrevista (ENT16) |
| RF09  | Indicar lotação do ônibus (vazio, moderado, lotado)                                         | Funcional      | Elicitação de Requisitos: Entrevista (ENT11), Brainstorm (BRS07) |
| RF10  | Permitir que usuários reportem a lotação do ônibus (sistema colaborativo)                   | Funcional      | Elicitação de Requisitos: Entrevista (ENT11), Brainstorm (BRS03) |
| RF11  | Enviar notificação quando o ônibus estiver a X minutos da parada                            | Funcional      | Elicitação de Requisitos: Análise de Documentos (RNI01), Entrevista (ENT15), Brainstorm (BRS05) |
| RF12  | Enviar alertas sobre atrasos, mudanças de rota ou alterações nos horários                   | Funcional      | Elicitação de Requisitos: Entrevista (ENT05), Brainstorm (BRS05) |
| RF13  | Oferecer recarga de cartão de transporte (ex.: integração com BRB Mobilidade)               | Funcional      | Elicitação de Requisitos: Entrevista (ENT07) |
| RF14  | Permitir integração com o cartão de transporte, incluindo saldo e recarga                   | Funcional      | Elicitação de Requisitos: Entrevista (ENT07) |
| RF15  | Manter histórico de viagens do usuário                                                      | Funcional      | Elicitação de Requisitos: Análise de Documentos (RNI03) |
| RF16  | Permitir reportar problemas (motorista, ônibus, cobrança) com dados do veículo e horário    | Funcional      | Elicitação de Requisitos: Entrevista (ENT20) |
| RF17  | Exibir preço da passagem por linha ou trajeto                                               | Funcional      | |
| RF18  | Listar linhas que passam em uma parada específica                                           | Funcional      | |
| RF19  | Disponibilizar versão web leve para acesso rápido em pontos de ônibus (via QR Code)         | Funcional      | Elicitação de Requisitos: Brainstorm (BRS17) |
| RF20  | Botão de pânico/emergência para alertar motorista e/ou autoridades                          | Funcional      | |
| RF21  | Mostrar alertas de trânsito, acidentes e rotas alternativas                                 | Funcional      | Elicitação de Requisitos: Brainstorm (BRS12) |
| RF22  | Permitir compartilhar trajeto em tempo real com outros usuários                             | Funcional      | |
| RF23  | Exibir quantidade de assentos preferenciais e totais no ônibus                              | Funcional      | |
| RF24  | Permitir favoritar linhas ou paradas para acesso rápido                                     | Funcional      | Elicitação de Requisitos: Entrevista (ENT14) |
| RF25  | Ampliar a cobertura e exibir informações também em regiões afastadas do Distrito Federal    | Funcional      | Elicitação de Requisitos: Entrevista (ENT08) |
| RF26  | Filtrar ônibus por empresa operadora                                                        | Funcional      | Elicitação de Requisitos: Análise de Documentos (RF03) |
| RF27  | Visualizar quais veículos estão em operação no momento                                      | Funcional      | Elicitação de Requisitos: Análise de Documentos (RF04) |
| RF28  | Permitir avaliação da qualidade do serviço de cada linha                                    | Funcional      | Elicitação de Requisitos: Análise de Documentos (RNI04) |
| RF29  | Sistema de gamificação para incentivar uso do transporte público                            | Funcional      | Elicitação de Requisitos: Brainstorm (BRS01) |
| RF30  | Previsão inteligente de horários baseada em dados históricos e machine learning             | Funcional      | Elicitação de Requisitos: Brainstorm (BRS02) |
| RF31  | Sistema de recompensas por uso sustentável do transporte público                            | Funcional      | Elicitação de Requisitos: Brainstorm (BRS09) |
| RF32  | Exibir relatórios de impacto ambiental (CO₂ economizado)                                    | Funcional      | Elicitação de Requisitos: Brainstorm (BRS11) |
| RF33  | Suporte a comandos de voz para facilitar interação durante deslocamentos                    | Funcional      | Elicitação de Requisitos: Brainstorm (BRS14) |
| RF34  | Integração com assistentes virtuais (Alexa, Google Assistant)                               | Funcional      | Elicitação de Requisitos: Brainstorm (BRS16) |
| RF35  | Permitir rastreamento de múltiplas linhas de ônibus simultaneamente no mapa                 | Funcional      | Elicitação de Requisitos: Entrevista (ENT12) |
| RF36  | Oferecer suporte multilíngue (português e inglês, no mínimo)                                | Funcional      | Elicitação de Requisitos: Entrevista (ENT22) |
| RNF01 | As informações de horários e localização dos ônibus devem ser precisas.                     | Não Funcional  | Elicitação de Requisitos: Entrevista (ENT09) |
| RNF02 | Rastreamento dos ônibus em tempo real deve ser confiável e sem falhas.                      | Não Funcional  | Elicitação de Requisitos: Entrevista (ENT13) |
| RNF03 | Tempo de atualização da localização ≤ 20 segundos.                                          | Não Funcional  | |
| RNF04 | Interface acessível para idosos e pessoas com deficiência visual.                           | Não Funcional  | Elicitação de Requisitos: Entrevista (ENT10), Brainstorm (BRS08) |
| RNF05 | Sistema de notificação com som e vibração configuráveis.                                    | Não Funcional  | |
| RNF06 | Baixo consumo de bateria e dados móveis.                                                    | Não Funcional  | |
| RNF07 | Compatibilidade com dispositivos Android e iOS.                                             | Não Funcional  | Elicitação de Requisitos: Entrevista (ENT19) |
| RNF08 | Proteção contra reportes falsos de lotação (mecanismo de confiança).                        | Não Funcional  | |
| RNF09 | Dados de localização e pessoais protegidos conforme LGPD.                                   | Não Funcional  | Elicitação de Requisitos: Entrevista (ENT21) |
| RNF10 | Tempo de carregamento da tela principal < 3 segundos.                                       | Não Funcional  | Elicitação de Requisitos: Entrevista (ENT17) |
| RNF11 | Funcionamento offline para consulta a rotas salvas e horários.                              | Não Funcional  | Elicitação de Requisitos: Análise de Documentos (RNI05), Entrevista (ENT18), Brainstorm (BRS06) |
| RNF12 | Integração segura com sistemas de pagamento (recarga de cartão).                            | Não Funcional  | Elicitação de Requisitos: Brainstorm (BRS10) |
| RNF13 | Alta disponibilidade do sistema (≥ 98% uptime).                                             | Não Funcional  | |
| RNF14 | Suporte a múltiplos usuários simultâneos sem lentidão.                                      | Não Funcional  | Elicitação de Requisitos: Brainstorm (BRS15) |
| RNF15 | Personalização da interface com base em preferências do usuário (tema, acessibilidade)      | Não Funcional  | Elicitação de Requisitos: Brainstorm (BRS13) |

## Histórico de Versões

| Versão | Data       | Descrição                                           | Autor(es)       | Revisor(es) |
|--------|------------|-----------------------------------------------------|-----------------|-------------|
| 1.0    | 18/10/2025 | Criação inicial da Tabela Geral de Requisitos Elicitados; Consolidação de requisitos da tabela First Things First com requisitos elicitados nas técnicas de elicitação: Análise de documentos, Brainstorm e Entrevista | Gabriel Maciel | João Gabriel |