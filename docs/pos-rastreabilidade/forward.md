# Forward-From

## Introdução
A rastreabilidade forward-from (pós-rastreabilidade) vincula requisitos a artefatos de desenho, implementação e validação (como código e casos de teste), rastreando-os desde a origem até a entrega. (SAYÃO; LEITE, 2005).

## Metodologia

A rastreabilidade forward-from foi estabelecida mapeando os requisitos para os seguintes artefatos gerados no projeto:

- Casos de Uso (Use Case)

- Histórias de Usuário

- NFR Framework (Requisitos Não Funcionais)

- Especificação Suplementar

- Cenários

- Léxico

O meta-modelo de Toranzo estabelece um conjunto de elos de rastreabilidade que definem os tipos de relacionamentos entre os elementos rastreados. A seguir, apresentam-se os principais elos:

1. **Satisfação**: Indica que a classe de origem possui uma dependência de satisfação com a classe de destino.
2. **Recurso**: A classe de origem demonstra dependência de recurso em relação à classe de destino.
3. **Responsabilidade**: Registra a participação, a responsabilidade e a ação de pessoas sobre os artefatos do projeto.
4. **Representação**: Captura como os requisitos ou outros elementos são modelados ou representados em diferentes linguagens.
5. **Alocado**: A classe de origem está relacionada a uma classe de destino que geralmente representa um subsistema.
6. **Agregação**: Indica a composição de elementos, ou seja, que um elemento é composto por outros.




## Rastreabilidade Forward-From

# Requisitos  não Funcionais

??? info "RNF01 – As informações de horários e localização dos ônibus devem ser precisas"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Especificação Suplementar** | *Não identificada* | | |
    |**NFR** | *Não identificado* | | |
    |**Artefatos de Elicitação** | ENT09 | | |

??? info "RNF02 – Rastreamento dos ônibus em tempo real deve ser confiável e sem falhas"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Especificação Suplementar** | *Não identificada* | | |
    |**NFR** | *Não identificado* | | |
    |**Artefatos de Elicitação** | ENT13 | | |

??? info "RNF03 – Tempo de atualização da localização ≤ 20 segundos"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Especificação Suplementar** | *Não identificada* | | |
    |**NFR** | *Não identificado* | | |
    |**Artefatos de Elicitação** | *Não identificado* | | |

    
??? info "RNF04 – Interface acessível para idosos e pessoas com deficiência visual"

    *Autoria: Cauã Nicolas *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Especificação Suplementar** | [Usabilidade](../modelagem_requisitos_01/especificacao_suplementar.md#usabilidade) | **Responsabilidade** | A especificação define critérios de acessibilidade (WCAG) que a equipe deve implementar. |
    |**NFR** | [SIG Usabilidade](../modelagem_requisitos_02/nfr.md#sig-usabilidade) | **Representação** | O SIG de usabilidade operacionaliza requisitos como suporte a leitores de tela e contraste (RU05 / RU09). |
    |**Artefatos de Elicitação** | [Entrevista (ENT16)](../Elicitacao/elicitacao_entrevista.md#resultados), ENT09 | **Satisfação** | ENT16 e ENT09 indicam a necessidade de interfaces acessíveis e confiáveis para diferentes perfis de usuário. |

??? info "RNF05 – Sistema de notificação com som e vibração configuráveis"

    *Autoria: Cauã Nicolas *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Especificação Suplementar** | [Requisitos do Sistema](../modelagem_requisitos_01/especificacao_suplementar.md#requisitos-do-sistema-portabilidadecompatibilidade) | **Responsabilidade** | A especificação registra que notificações devem ser configuráveis e respeitar preferências do usuário (som/vibração). |
    |**NFR** | [SIG Usabilidade](../modelagem_requisitos_02/nfr.md#sig-usabilidade) | **Representação** | O cartão RU06 / RNF06 (Feedback e Comunicação) define critérios de mensagem e notificações. |
    |**Artefatos de Elicitação** | [Entrevista (ENT15)](../Elicitacao/elicitacao_entrevista.md#resultados), [Entrevista (ENT05)](../Elicitacao/elicitacao_entrevista.md#resultados) | **Satisfação** | ENT15/ENT05 descrevem expectativas de notificações relevantes e configuráveis pelos usuários. |

??? info "RNF06 – Baixo consumo de bateria e dados móveis"

    *Autoria: Fernanda Vaz*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:--|:--|:--|:--|
    | **Especificação Suplementar** | [Portabilidade/Compatibilidade](https://requisitos-de-software.github.io/2025.2-Grupo06/modelagem_requisitos_01/especificacao_suplementar) | **Alocado** | O requisito está alocado ao subsistema de otimização do aplicativo, responsável por reduzir o uso de energia e dados móveis. |
    | **NFR** | [Desempenho](https://requisitos-de-software.github.io/2025.2-Grupo06/modelagem_requisitos_02/nfr) | **Representação** | O NFR de desempenho representa este RNF e define critérios técnicos de otimização. |
    | **Artefatos de Elicitação** | — | — | **Requisito técnico derivado de decisões dos desenvolvedores durante o processo de especificação.** |

??? info "RNF07 – Compatibilidade com dispositivos Android e iOS"

    *Autoria: Fernanda Vaz*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:--|:--|:--|:--|
    | **Especificação Suplementar** | [Compatibilidade](https://requisitos-de-software.github.io/2025.2-Grupo06/modelagem_requisitos_01/especificacao_suplementar) | **Responsabilidade** | A responsabilidade é da equipe de desenvolvimento em garantir a portabilidade e compatibilidade do aplicativo entre plataformas. |
    | **NFR** | [SIG Compatibilidade](https://requisitos-de-software.github.io/2025.2-Grupo06/modelagem_requisitos_02/nfr) | **Representação** | O NFR Framework representa a compatibilidade entre sistemas operacionais, reforçando a necessidade de comportamento uniforme no Android e iOS. |
    | **Artefatos de Elicitação** | [Entrevista (ENT19)](../Elicitacao/elicitacao_entrevista.md#resultados) | **Representação** | A ENT19 originou o requisito, evidenciando a importância da compatibilidade com os sistemas Android e iOS. |

??? info "RNF10 – Tempo de carregamento da tela principal < 3 segundos"

    *Autoria: Gabriel Maciel*

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :--| :-- |
    |**Especificação Suplementar** | [RD02 - Tempo de Carregamento Rápido](../modelagem_requisitos_01/especificacao_suplementar.md#desempenho-print-da-fonte) | Representação | RD02 representa e detalha o requisito RNF10 na Especificação Suplementar |
    |**NFR** | [RD02 / RNF06 - Tempo de Carregamento Rápido](../modelagem_requisitos_02/nfr.md#sig-desempenho) | Representação | O cartão de especificação RD02 no NFR Framework detalha os critérios de ajuste e dependências de RNF10 |
    |**Artefatos de Elicitação** | [Entrevista (ENT17)](../Elicitacao/elicitacao_entrevista.md#resultados) | Satisfação | ENT17 é a fonte de elicitação que satisfaz e fundamenta a necessidade do RNF10 |

??? info "RNF11 – Funcionamento offline para consulta a rotas salvas e horários"

    *Autoria: Gabriel Maciel*

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :--| :-- |
    |**Especificação Suplementar** | *Não identificada* | — | — |
    |**NFR** | [RS02 - Funcionamento Offline](../modelagem_requisitos_02/nfr.md#rs02-funcionamento-offline) | Representação | O cartão de especificação RS02 no NFR Framework detalha os critérios de ajuste e dependências de RNF11 |
    |**Artefatos de Elicitação** | [Análise de Documentos (RNI05)](../Elicitacao/elicitacao_analise_documentos.md#requisitos-nao-implementados), [Entrevista (ENT18)](../Elicitacao/elicitacao_entrevista.md#resultados), [Brainstorm (BRS06)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Satisfação | RNI05, ENT18 e BRS06 são fontes de elicitação que satisfazem e fundamentam a necessidade do RNF11 |


# Requisitos Funcionais

??? info "RF01 – Exibir a localização dos ônibus em tempo real no mapa"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 1: Rastreamento e Informações em Tempo Real | | |
    |**História de Usuário** | US15 | | |
    |**Léxico** | L12: Tempo real | | |
    |**Casos de Uso** | UC03 | | |
    |**Cenários** | CEN03 | | |
    |**Artefatos de Elicitação** | RF01 (Análise de Documentos), ENT03 | | |

??? info "RF02 – Mostrar o tempo estimado de chegada do ônibus à parada"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 1: Rastreamento e Informações em Tempo Real | | |
    |**História de Usuário** | US16 | | |
    |**Léxico** | L09: Agora | | |
    |**Casos de Uso** | UC02 | | |
    |**Cenários** | CEN01 | | |
    |**Artefatos de Elicitação** | ENT04 | | |

??? info "RF03 – Permitir planejamento de viagem com rotas sugeridas"

    *Autoria: *
    
    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 7: Planejamento de Viagens | | |
    |**História de Usuário** | US17 | | |
    |**Léxico** | L05: Planejar | | |
    |**Casos de Uso** | UC09 | | |
    |**Cenários** | CEN09 | | |
    |**Artefatos de Elicitação** | RF05 (Análise de Documentos) | | |

??? info "RF04 – Permitir pesquisa por linhas e rotas de ônibus"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 2: Filtragem | | |
    |**História de Usuário** | US18 | | |
    |**Léxico** | L11: Pesquisar | | |
    |**Casos de Uso** | *Não identificados* | | |
    |**Cenários** | *Não identificados* | | |
    |**Artefatos de Elicitação** | RF02 (Análise de Documentos), ENT01 | | |

??? info "RF05 – Apresentar horários de saída e chegada dos transportes"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 1: Rastreamento e Informações em Tempo Real | | |
    |**História de Usuário** | US05, US19 | | |
    |**Léxico** | L09: Agora | | |
    |**Casos de Uso** | *Não identificados* | | |
    |**Cenários** | *Não identificados* | | |
    |**Artefatos de Elicitação** | ENT02 | | |

??? info "RF06 – Oferecer um mapa interativo com os pontos de ônibus e suas linhas correspondentes"

    *Autoria: Fernanda Vaz*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:--|:--|:--|:--|
    | **Épico** | [Épico 1: Rastreamento e Informações em Tempo Real](../modelagem_requisitos_02/backlog.md#épico-1---rastreamento-e-informações-em-tempo-real) | Representação | O épico modela a visão geral de exibição no mapa |
    | **História de Usuário** | [US06 - Oferecer um Mapa Interativo com os Pontos de Ônibus e suas Linhas Correspondentes](../modelagem_requisitos_02/backlog.md#us06---oferecer-um-mapa-interativo-com-os-pontos-de-ônibus-e-suas-linhas-correspondentes) | Representação | A história de usuário detalha o requisito funcional do mapa |
    | **Léxico** | [Léxico 01: Notificações de Chegada](../modelagem_requisitos_02/lexico.md#léxico-01---notificações-de-chegada) | Representação | O termo "mapa" é representado no léxico do sistema |
    | **Casos de Uso** | [Tabela 5 - UC03: Rastreamento de Múltiplas Linhas](../modelagem_requisitos_02/casos_de_uso.md#tabela-5---uc03-rastreamento-de-múltiplas-linhas-requisito-não-implementado) | Representação | UC03 descreve o fluxo de exibição e atualização dos pontos |
    | **Cenários** | [Cenário 3 - Rastreamento de múltiplas linhas](../modelagem_requisitos_01/cenarios.md#cenário-3---rastreamento-de-múltiplas-linhas) | Representação | Cenário ilustra uma situação prática de uso do mapa |
    | **Artefatos de Elicitação** | [Entrevista (ENT06)](../Elicitacao/elicitacao_entrevista.md#resultados) | Representação | ENT06 representa a origem e fundamentação do RF06 |

??? info "RF07 – Integrar informações de outros modais (metrô, outros ônibus) em rotas multimodais"

    *Autoria: Fernanda Vaz*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:--|:--|:--|:--|
    | **Épico** | [Épico 7: Planejamento de Viagens](../modelagem_requisitos_02/backlog.md#épico-7---planejamento-de-viagens) | Agregação | O épico agrega funcionalidades de múltiplos modais |
    | **História de Usuário** | [US07 - Integrar Informações de Outros Modais (Metrô, Outros Ônibus) em Rotas Multimodais](../modelagem_requisitos_02/historias_de_usuario.md) | Representação | US07 detalha a funcionalidade de integração de rotas |
    | **Casos de Uso** | — | — | — |
    | **Cenários** | [Cenário 12 – Integração ônibus e metrô (Requisito não implementado)](../modelagem_requisitos_01/cenarios.md) | Agregação | Cenário exemplifica o uso da integração multimodal |
    | **Artefatos de Elicitação** | [BRS04](../Elicitacao/elicitacao_brainstorm.md#resultados), [RNI02](../Elicitacao/elicitacao_analise_documentos.md#requisitos-nao-implementados) | Agregação | O requisito agrega fontes externas de dados sobre modais |

??? info "RF08 – Exibir informações de acessibilidade do ônibus (ex.: acessível para cadeirantes)"

    *Autoria: Fernanda Vaz*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:--|:--|:--|:--|
    | **Épico** | [Épico 5: Integração e Recargas](../modelagem_requisitos_02/backlog.md) | Satisfação | O épico visa atender à acessibilidade conforme normas |
    | **História de Usuário** | [US11 - Oferecer Recarga de Cartão de Transporte](../modelagem_requisitos_02/historias_de_usuario.md) | Representação | US08 representa o requisito de informação de acessibilidade |
    | **Casos de Uso** | [Tabela 6 - UC04: Integração com BRB Mobilidade (Requisito não implementado)](../modelagem_requisitos_02/casos_de_uso.md#tabela-6-uc04-integracao-com-brb-mobilidade-requisito-nao-implementado) | Representação | UC04 descreve o fluxo de consulta à acessibilidade |
    | **Cenários** | [Cenário 4 - Integração com BRB Mobilidade (Requisito não implementado)](../modelagem_requisitos_01/cenarios.md#cenario-4-integracao-com-brb-mobilidade-requisito-nao-implementado) | Representação | Cenário apresenta exemplo de uso por pessoa com deficiência |
    | **Artefatos de Elicitação** | [Entrevista (ENT16)](../Elicitacao/elicitacao_entrevista.md#resultados) | Satisfação | ENT16 satisfaz a necessidade de inclusão e acessibilidade |

??? info "RF13 – Oferecer recarga de cartão de transporte (ex.: integração com BRB Mobilidade)"

    *Autoria: Cauã Nicolas*

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | [Épico 5: Integração e Recargas](../modelagem_requisitos_02/backlog.md#épico-5---integração-e-recargas) | Representação | O épico organiza funcionalidades de recarga e integração com provedores externos. |
    |**História de Usuário** | [US09 - Realizar recarga de cartão pelo app](../modelagem_requisitos_02/backlog.md#us09---realizar-recarga-do-cartão) | Representação | A história detalha a interação do usuário para recarga e consulta de saldo. |
    |**Casos de Uso** | [UC05 – Recarga de Cartão](../modelagem_requisitos_01/casos_de_uso.md#tabela-5---uc05-recarga-de-cartão) | Representação | UC05 descreve o fluxo de recarga e integração com BRB Mobilidade. |
    |**Cenários** | [Cenário 4 – Integração BRB Mobilidade](../modelagem_requisitos_01/cenarios.md#cenario-4---integração-com-brb-mobilidade-requisito-nao-implementado) | Representação | Cenário ilustra uso prático da funcionalidade de recarga. |
    |**Especificação Suplementar** | [Requisitos do Sistema](../modelagem_requisitos_01/especificacao_suplementar.md#requisitos-do-sistema-portabilidadecompatibilidade) | **Responsabilidade** | Regras de integração e segurança definidas na especificação orientam a implementação. |
    |**NFR** | [SIG Portabilidade/Compatibilidade](../modelagem_requisitos_02/nfr.md#sig-portabilidadecompatibilidade) | **Representação** | O SIG descreve critérios de compatibilidade e integração com APIs externas (RS04). |
    |**Artefatos de Elicitação** | [Entrevista (ENT07)](../Elicitacao/elicitacao_entrevista.md#resultados) | **Representação** | ENT07 relata a necessidade de integração e recarga do cartão pelo app. |

??? info "RF14 – Permitir integração com o cartão de transporte, incluindo saldo e recarga"

    *Autoria: Cauã Nicolas*

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | [Épico 5: Integração e Recargas](../modelagem_requisitos_02/backlog.md#épico-5---integração-e-recargas) | Representação | O épico contempla integração com prestadores de serviços (ex.: BRB Mobilidade). |
    |**História de Usuário** | [US10 - Visualizar saldo e recarregar cartão](../modelagem_requisitos_02/backlog.md#us10---visualizar-saldo-e-recarga) | Representação | A história define critérios de aceitação e segurança da integração. |
    |**Casos de Uso** | [UC05 – Recarga de Cartão](../modelagem_requisitos_01/casos_de_uso.md#tabela-5---uc05-recarga-de-cartão) | Representação | UC05 cobre saldo, histórico e recarga integrados. |
    |**Cenários** | [Cenário 4 – Integração BRB Mobilidade](../modelagem_requisitos_01/cenarios.md#cenario-4---integração-com-brb-mobilidade-requisito-nao-implementado) | Representação | Cenário demonstra fluxo de autenticação e recarga. |
    |**Especificação Suplementar** | [Requisitos do Sistema](../modelagem_requisitos_01/especificacao_suplementar.md#requisitos-do-sistema-portabilidadecompatibilidade) | **Responsabilidade** | Define requisitos de integração segura e formatos de API aceitos. |
    |**NFR** | [RS04 - Compatibilidade com APIs Externas](../modelagem_requisitos_02/nfr.md#rs04-compatibilidade-com-apis-externas) | **Representação** | RS04 especifica critérios técnicos para integração e autenticação. |
    |**Artefatos de Elicitação** | [Entrevista (ENT07)](../Elicitacao/elicitacao_entrevista.md#resultados) | **Representação** | ENT07 descreve a necessidade de saldo e recarga integrados ao app. |

??? info "RF15 – Manter histórico de viagens do usuário"

    *Autoria: Cauã Nicolas*

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 4: Avaliar e Reportar / Épico 5: Integração e Recargas | Agregação | Histórico de viagens serve como insumo para recompensas, relatórios e recargas. |
    |**História de Usuário** | [US30 - Histórico e recompensas](../modelagem_requisitos_02/backlog.md#us30---histórico-e-recompensas) | Representação | A história define como o histórico será apresentado e usado para pontos/recompensas. |
    |**Casos de Uso** | [UC05 – Recarga de Cartão](../modelagem_requisitos_01/casos_de_uso.md#tabela-5---uc05-recarga-de-cartão) | Representação | UC05 e casos relacionados suportam registro e consulta de viagens. |
    |**Cenários** | *Não identificados* | — | — |
    |**Especificação Suplementar** | [Privacidade](../modelagem_requisitos_01/especificacao_suplementar.md#privacidade) | **Responsabilidade** | Guarda e uso do histórico devem seguir políticas de privacidade e LGPD. |
    |**NFR** | [RPV - Privacidade](../modelagem_requisitos_01/especificacao_suplementar.md#rpv01) | **Representação** | Regras de retenção, consentimento e criptografia definem o tratamento do histórico. |
    |**Artefatos de Elicitação** | [Entrevista (ENT07)](../Elicitacao/elicitacao_entrevista.md#resultados), ENT09 | **Satisfação** | ENT07/ENT09 indicam interesse por histórico e confiabilidade dos dados; privacidade exige consentimento. |

??? info "RF16 – Permitir reportar problemas (motorista, ônibus, cobrança) com dados do veículo e horário"

    *Autoria: Cauã Nicolas*

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | [Épico 4: Avaliar e Reportar](../modelagem_requisitos_02/backlog.md#epico-4-avaliar-e-reportar) | Representação | O épico agrega funcionalidades de avaliação e reporte de problemas. |
    |**História de Usuário** | *Não identificada* | — | — |
    |**Casos de Uso** | *Não identificados* | — | — |
    |**Cenários** | *Não identificados* | — | — |
    |**Especificação Suplementar** | [Usabilidade](../modelagem_requisitos_01/especificacao_suplementar.md#usabilidade) | **Responsabilidade** | Mensagens e relatórios de erro devem ser claros e acionáveis, conforme definição de usabilidade. |
    |**NFR** | [SIG Usabilidade](../modelagem_requisitos_02/nfr.md#sig-usabilidade) | **Representação** | RU06 descreve critérios de feedback e comunicação para reportes e mensagens. |
    |**Artefatos de Elicitação** | [Entrevista (ENT09)](../Elicitacao/elicitacao_entrevista.md#resultados) | **Satisfação** | ENT09 identificou necessidade de feedback confiável e canais para reportar problemas. |

??? info "RF19 – Disponibilizar versão web leve para acesso rápido em pontos de ônibus (via QR Code)"

    *Autoria: Gabriel Maciel*

    |**Elemento** | **Artefatos Relacionados** | Tipo de Elo | Justificativa |
    |:-- | :-- | :--| :-- |
    |**Épico** | [Épico 3: Acessibilidade](../modelagem_requisitos_02/backlog.md#épico-3-acessibilidade) | Agregação | Épico 3 agrega e compõe o requisito RF19 como parte de sua estrutura |
    |**História de Usuário** | [US02](../modelagem_requisitos_02/historias_de_usuario.md#us02---acesso-web-rápido-via-qr-code) | Representação | US02 representa a implementação detalhada do RF19 em termos de funcionalidade do usuário |
    |**Léxico** | *Não identificado* | | |
    |**Casos de Uso** | [UC07](../modelagem_requisitos_01/casos_de_uso.md#tabela-8---uc07-modo-off-line-requisito-não-implementado) | Representação | UC07 modela e representa o fluxo de interação para acessar a versão web via QR Code |
    |**Cenários** | [Cenário 5](../modelagem_requisitos_01/cenarios.md#cenário-5---modo-off-line-requisito-não-implementado) | Representação | Cenário 5 descreve uma situação concreta onde o RF19 é utilizado |
    |**Artefatos de Elicitação** | [Brainstorm (BRS17)](../Elicitacao/elicitacao_brainstorm.md#resultados) | | |

??? info "RF24 – Permitir favoritar linhas ou paradas para acesso rápido"

    *Autoria: Cauã Nicolas*

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 1: Rastreamento e Informações em Tempo Real | Representação | Favoritos melhoram eficiência de acesso a informações recorrentes. |
    |**História de Usuário** | [US22 - Favoritos](../modelagem_requisitos_02/historias_de_usuario.md#us22---permitir-favoritar-linhas-ou-paradas-para-acesso-rápido) | Representação | US22 descreve critérios de aceitação para favoritos. |
    |**Casos de Uso** | [UC05 – Recarga de Cartão (se aplicável)](../modelagem_requisitos_01/casos_de_uso.md#tabela-5---uc05-recarga-de-cartão) | Representação | Casos de uso relacionados à personalização e às preferências do usuário. |
    |**Cenários** | *Não identificados* | — | — |
    |**Especificação Suplementar** | [Usabilidade](../modelagem_requisitos_01/especificacao_suplementar.md#usabilidade) | **Responsabilidade** | Personalização e persistência de preferências definidas na especificação. |
    |**NFR** | [SIG Usabilidade](../modelagem_requisitos_02/nfr.md#sig-usabilidade) | **Representação** | RU08 (Personalização) explica critérios de persistência e usabilidade para favoritos. |
    |**Artefatos de Elicitação** | [Entrevista (ENT14)](../Elicitacao/elicitacao_entrevista.md#resultados) | **Representação** | ENT14 solicita explicitamente a funcionalidade de favoritos. |

??? info "RF25 – Ampliar a cobertura e exibir informações também em regiões afastadas do Distrito Federal"

    *Autoria: Cauã Nicolas*

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 1: Rastreamento e Informações em Tempo Real | Representação | Ampliação de cobertura impacta rastreamento e disponibilidade de dados. |
    |**História de Usuário** | *Não identificada* | — | — |
    |**Casos de Uso** | *Não identificados* | — | — |
    |**Cenários** | *Não identificados* | — | — |
    |**Especificação Suplementar** | [Portabilidade/Compatibilidade](https://requisitos-de-software.github.io/2025.2-Grupo06/modelagem_requisitos_01/especificacao_suplementar) | **Responsabilidade** | Políticas de integração e suporte a ambientes com conectividade limitada são definidas na especificação. |
    |**NFR** | [SIG Portabilidade/Compatibilidade](../modelagem_requisitos_02/nfr.md#sig-portabilidadecompatibilidade) | **Representação** | O SIG documenta requisitos de integração e suporte a diferentes ambientes e APIs. |
    |**Artefatos de Elicitação** | [Entrevista (ENT09)](../Elicitacao/elicitacao_entrevista.md#resultados) | **Satisfação** | ENT09 aponta a necessidade de cobertura e confiabilidade dos dados em diferentes regiões. |

??? info "RF26 – Filtrar ônibus por empresa operadora"

    *Autoria: Gabriel Maciel*

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :--| :-- |
    |**Épico** | [Épico 2: Filtragem](../modelagem_requisitos_02/backlog.md#epico-2-filtragem) | Agregação | Épico 2 agrega e compõe o requisito RF26 como parte de sua estrutura |
    |**História de Usuário** | [US01](../modelagem_requisitos_02/historias_de_usuario.md#us01-filtrar-onibus-por-empresa-operadora) | Representação | US01 representa a implementação detalhada do RF26 em termos de funcionalidade do usuário |
    |**Léxico** | *Não identificado* | — | — |
    |**Casos de Uso** | *Não identificados* | — | — |
    |**Cenários** | *Não identificados* | — | — |
    |**Artefatos de Elicitação** | [Análise de Documentos (RF03)](../Elicitacao/elicitacao_analise_documentos.md#requisitos-funcionais) | | |

??? info "RF28 – Permitir avaliação da qualidade do serviço de cada linha"

    *Autoria: Gabriel Maciel*

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :--| :-- |
    |**Épico** | [Épico 4: Avaliar e Reportar](../modelagem_requisitos_02/backlog.md#epico-4-avaliar-e-reportar) | Agregação | Épico 4 agrega e compõe o requisito RF28 como parte de sua estrutura |
    |**História de Usuário** | [US03](../modelagem_requisitos_02/historias_de_usuario.md#us03-avaliar-qualidade-das-linhas) | Representação | US03 representa a implementação detalhada do RF28 em termos de funcionalidade do usuário |
    |**Léxico** | *Não identificado* | — | — |
    |**Casos de Uso** | [UC01](../modelagem_requisitos_01/casos_de_uso.md#tabela-3-uc01-avaliacao-de-linhas-de-onibus-requisito-nao-implementado) | Representação | UC01 modela e representa o fluxo de interação para avaliar a qualidade do serviço |
    |**Cenários** | [Cenário 2](../modelagem_requisitos_01/cenarios.md#cenario-2-avaliar-linhas-requisito-nao-implementado) | Representação | Cenário 2 descreve uma situação concreta onde o RF28 é utilizado |
    |**Artefatos de Elicitação** | [Análise de Documentos (RNI04)](../Elicitacao/elicitacao_analise_documentos.md#requisitos-nao-implementados) | | |

??? info "RF30 – Previsão inteligente de horários baseada em dados históricos e machine learning"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 7: Planejamento de Viagens | | |
    |**História de Usuário** | US31 | | |
    |**Léxico** | *Não identificado* | | |
    |**Casos de Uso** | UC10 | | |
    |**Cenários** | CEN10 | | |
    |**Artefatos de Elicitação** | BRS02 | | |

??? info "RF31 – Sistema de recompensas por uso sustentável do transporte público"

    *Autoria: Fernanda Vaz*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:--|:--|:--|:--|
    | **Épico** | [Épico 11: Gamificação e Engajamento](../modelagem_requisitos_02/backlog.md) | Satisfação | O épico busca satisfazer objetivos de incentivo ao transporte sustentável |
    | **História de Usuário** | [US38 - Sistema de Gamificação para Incentivar o Uso do Transporte Público](../modelagem_requisitos_02/historias_de_usuario.md#us38-sistema-de-gamificacao-para-incentivar-o-uso-do-transporte-publico) | Representação | US31 descreve a funcionalidade de recompensas ao usuário |
    | **Casos de Uso** | — | — | — |
    | **Cenários** | — | — | — |
    | **Artefatos de Elicitação** | [BRS09](../Elicitacao/elicitacao_brainstorm.md#resultados) | Satisfação | O requisito satisfaz os objetivos organizacionais de sustentabilidade |

??? info "RF32 – Exibir relatórios de impacto ambiental (CO₂ economizado)"

    *Autoria: Fernanda Vaz*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:--|:--|:--|:--|
    | **Épico** | [Épico 9: Sustentabilidade e Impacto Ambiental](../modelagem_requisitos_02/backlog.md#epico-09-sustentabilidade-e-impacto-ambiental) | Recurso | O épico utiliza este requisito como recurso para mensurar impacto |
    | **História de Usuário** | [US10 - Exibir Relatórios de Impacto Ambiental (CO₂ Economizado)](../modelagem_requisitos_02/historias_de_usuario.md#us10-exibir-relatorios-de-impacto-ambiental-co2-economizado) | Representação | US32 detalha o relatório de impacto ambiental |
    | **Casos de Uso** | — | — | — |
    | **Cenários** | — | — | — |
    | **Artefatos de Elicitação** | [BRS11](../Elicitacao/elicitacao_brainstorm.md#resultados) | Recurso | O requisito serve de recurso para avaliação ambiental e organizacional |

??? info "RF34 – Integração com assistentes virtuais (Alexa, Google Assistant)"

    *Autoria: Gabriel Maciel*

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :--| :-- |
    |**Épico** | [Épico 3: Acessibilidade](../modelagem_requisitos_02/backlog.md#epico-3-acessibilidade) | Agregação | Épico 3 agrega e compõe o requisito RF34 como parte de sua estrutura |
    |**História de Usuário** | [US20](../modelagem_requisitos_02/historias_de_usuario.md#us20-integracao-com-assistentes-virtuais) | Representação | US20 representa a implementação detalhada do RF34 em termos de funcionalidade do usuário |
    |**Léxico** | *Não identificado* | — | — |
    |**Casos de Uso** | *Não identificados* | — | — |
    |**Cenários** | *Não identificados* | — | — |
    |**Artefatos de Elicitação** | [Brainstorm (BRS16)](../Elicitacao/elicitacao_brainstorm.md#resultados) | | |

??? info "RF35 – Permitir rastreamento de múltiplas linhas de ônibus simultaneamente no mapa"

    *Autoria: Gabriel Maciel*

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :--| :-- |
    |**Épico** | [Épico 1: Rastreamento e Informações em Tempo Real](../modelagem_requisitos_02/backlog.md#epico-1-rastreamento-e-informacoes-em-tempo-real) | Agregação | Épico 1 agrega e compõe o requisito RF35 como parte de sua estrutura |
    |**História de Usuário** | [US04](../modelagem_requisitos_02/historias_de_usuario.md#us04-rastrear-multiplas-linhas-simultaneamente) | Representação | US04 representa a implementação detalhada do RF35 em termos de funcionalidade do usuário |
    |**Léxico** | *Não identificado* | — | — |
    |**Casos de Uso** | [UC03](../modelagem_requisitos_01/casos_de_uso.md#tabela-4-uc03-rastreamento-de-onibus) | Representação | UC03 modela e representa o fluxo de interação para rastrear múltiplas linhas |
    |**Cenários** | [Cenário 3](../modelagem_requisitos_01/cenarios.md#cenario-3-rastreamento-de-multiplas-linhas-requisito-nao-implementado) | Representação | Cenário 3 descreve uma situação concreta onde o RF35 é utilizado |
    |**Artefatos de Elicitação** | [Entrevista (ENT12)](../Elicitacao/elicitacao_entrevista.md#resultados) | | |

??? info "RF36 – Oferecer suporte multilíngue (português e inglês, no mínimo)"

    *Autoria: Gabriel Maciel*

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :--| :-- |
    |**Épico** | Épico 16: Suporte Multilíngue | Agregação | Épico 16 agrega e compõe o requisito RF36 como parte de sua estrutura |
    |**História de Usuário** | [US21](../modelagem_requisitos_02/historias_de_usuario.md#us21---suporte-multilingue) | Representação | US19 representa a implementação detalhada do RF36 em termos de funcionalidade do usuário |
    |**Léxico** | *Não identificado* | — | — |
    |**Casos de Uso** | *Não identificados* | — | — |
    |**Cenários** | *Não identificados* | — | — |
    |**Artefatos de Elicitação** | [Entrevista (ENT22)](../Elicitacao/elicitacao_entrevista.md#resultados) | | |

??? info "RF37 – Permitir cadastro, login e autenticação de usuários no sistema"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 8: Gestão de Usuário e Conta | | |
    |**História de Usuário** | US32 | | |
    |**Léxico** | *Não identificado* | | |
    |**Casos de Uso** | UC01 | | |
    |**Cenários** | *Não identificados* | | |
    |**Artefatos de Elicitação** | BRS18 | | |


## Tabela de Contribuição

|        Nome          | Contribuição|
|----------------------|-------------|
| Cauã Nicolas         | Adição RNF04 e RNF05, RF13, RF14, RF15, RF16, RF24 e RF25 |
| Daniel Nunes Duarte  | A preencher |
| Fernanda Vaz         | Foward: RNF6 e RNF7, RF05, RF06, RF07, RF08, RF31, RF32 |
| Gabriel Maciel       | A preencher |
| João Gabriel         | Adição RNF1 ao RNF3 e RF01 ao RF05, RF37, RF30 |
| João Ramos           | A preencher |

## Referência bibliográfica 


> <sup>1.</sup>
<a id="ref-1"></a>
> TORANZO, M.; CASTRO, J; MELLO, E. Uma proposta para melhorar o rastreamento de requisitos. PUC-Rio: Workshop em Engenharia de Requisitos, Rio de Janeiro, 2002. Disponível em: http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/toranzo.pdf. Acesso em: 28 de Out de 2025.

> 
## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|:-------:|:-----:|:-----------|:------------|:-------------|
| 1.0 | 25/10 | Criação inicial do documento | Gabriel Maciel | FERNANDA |
| 1.1 | 26/10 | Adição RNF1 - RNF3 e RF01 - RF05, RF37, RF30 | João Gabriel | Gabriel Maciel |
| 1.2 | 28/10 | Adição RNF04 e RNF05, RF13, RF14, RF15, RF16, RF24 e RF25  | Cauã Nicolas | Gabriel Maciel |

## Agradecimentos

>Agradecemos o suporte da ferramenta de Inteligência Artificial Generativa Google Gemini no desenvolvimento deste trabalho. Em conformidade com o Código de Conduta da Sociedade Brasileira de Computação (SBC), declaramos que a ferramenta foi utilizada como auxílio na revisão gramatical e estilística do texto, na sugestão de estrutura para seções específicas do artigo, bem como na formatação de tabelas e na descrição de figuras. Ressaltamos que os autores assumem total responsabilidade por todo o conteúdo apresentado, incluindo sua originalidade e precisão. A ferramenta não figura como autora desta publicação.
