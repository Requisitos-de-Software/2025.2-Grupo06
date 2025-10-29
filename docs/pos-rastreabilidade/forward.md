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

# Rastreabilidade de Requisitos

## **Requisitos Não-Funcionais**

??? info "RNF01 – As informações de horários e localização dos ônibus devem ser precisas"

    *Autoria: João Gabriel*

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Especificação Suplementar** | Confiabilidade | Representação | Representa os critérios de precisão do RNF01 |
    |**NFR** | SIG - Confiabilidade | Satisfação | Satisfaz o requisito de confiabilidade do sistema |
    |**Artefatos de Elicitação** | [Entrevista (ENT09)](../Elicitacao/elicitacao_entrevista.md#resultados) | Representação | ENT09 representa a necessidade de precisão nas informações |

??? info "RNF02 – Rastreamento dos ônibus em tempo real deve ser confiável e sem falhas"

    *Autoria: João Gabriel*

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Especificação Suplementar** | Confiabilidade | Representação | Representa os critérios de confiabilidade do RNF02 |
    |**NFR** | SIG - Confiabilidade | Satisfação | Satisfaz o requisito de confiabilidade do sistema |
    |**Artefatos de Elicitação** | [Entrevista (ENT13)](../Elicitacao/elicitacao_entrevista.md#resultados) | Representação | ENT13 representa a necessidade de rastreamento confiável |

??? info "RNF03 – Tempo de atualização da localização ≤ 20 segundos"

    *Autoria: João Gabriel*

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Especificação Suplementar** | Desempenho | Representação | Representa os critérios de desempenho do RNF03 |
    |**NFR** | SIG-Desempenho | Satisfação | Satisfaz o requisito de desempenho do sistema |
    |**Artefatos de Elicitação** | [Entrevista (ENT)](../Elicitacao/elicitacao_entrevista.md#resultados) | Representação | ENT representa a necessidade de atualização rápida |

    
??? info "RNF04 – Interface acessível para idosos e pessoas com deficiência visual"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Especificação Suplementar** | *Não identificada* | | |
    |**NFR** | *Não identificado* | | |
    |**Artefatos de Elicitação** | ENT09 | | | 

??? info "RNF05 – Sistema de notificação com som e vibração configuráveis"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Especificação Suplementar** | *Não identificada* | | |
    |**NFR** | *Não identificado* | | |
    |**Artefatos de Elicitação** | ENT09 | | |





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

??? info "RNF09 – Dados de localização e pessoais protegidos conforme LGPD"

    *Autoria: João Ramos*

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 8: Gestão de Usuário e Conta | Representação | A gestão de usuários engloba consentimento, controle e proteção de dados pessoais. |
    |**História de Usuário** | [US30 - Criar conta e fazer login de forma segura](../modelagem_requisitos_02/historias_de_usuario.md#us30---criar-uma-conta-e-fazer-login-de-forma-segura) | Representação | US30 descreve operações que envolvem dados pessoais e autenticação, demandando conformidade com proteção de dados. |
    |**Léxico** | *Não identificado* | — | — |
    |**Casos de Uso** | UC01 (ex.: Avaliação de Linhas) e UC04 (Integração BRB) — pré-condição de usuário autenticado | Representação | Vários casos de uso exigem autenticação e tratamento de dados pessoais; UC04 e UC01 citam pré-condição de usuário autenticado. |
    |**Especificação / NFR** | [Privacidade (RPV01..RPV06)](../modelagem_requisitos_01/especificacao_suplementar.md#privacidade) | Representação | A Especificação Suplementar define requisitos de privacidade (minimização de dados, consentimento, criptografia em repouso, DPIA). |
    |**Artefatos de Elicitação** | [Entrevista (ENT21)](../Elicitacao/elicitacao_entrevista.md#resultados) | Representação | ENT21 é a fonte que destaca a necessidade de proteção de dados pessoais e conformidade com a LGPD. |


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

??? info "RNF12 – Integração segura com sistemas de pagamento (recarga de cartão)"

    *Autoria: João Ramos*

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | [Épico 5: Integração e Recargas](../modelagem_requisitos_02/backlog.md#épico-5---integração-e-recargas) | Representação | O épico agrega funcionalidades de integração com provedores de recarga e pagamento. |
    |**História de Usuário** | [US11 - Oferecer Recarga de Cartão de Transporte](../modelagem_requisitos_02/historias_de_usuario.md#us11---oferecer-recarga-de-cartão-de-transporte) | Representação | US11 descreve a funcionalidade de recarga integrada e suas opções de pagamento. |
    |**Léxico** | *Não identificado* | — | — |
    |**Casos de Uso** | [Tabela 6 - UC04: Integração com BRB Mobilidade (Requisito não implementado)](../modelagem_requisitos_01/casos_de_uso.md#tabela-6---uc04-integracao-com-brb-mobilidade-requisito-nao-implementado) | Representação | UC04 descreve o fluxo de consulta de saldo e recarga via integração com o BRB Mobilidade. |
    |**Cenários** | [Cenário 4 - Integração com BRB Mobilidade (Requisito não implementado)](../modelagem_requisitos_01/cenarios.md#cenário-4---integração-com-brb-mobilidade-requisito-não-implementado) | Representação | Cenário 4 exemplifica o uso da integração para recarga e confirmação de transação. |
    |**NFR / Especificação** | [RC05 - Atomicidade de Transações](../modelagem_requisitos_02/nfr.md#rc05---atomicidade-de-transações), [RS04 - Compatibilidade com APIs Externas](../modelagem_requisitos_02/nfr.md#rs04---compatibilidade-com-apis-externas) | Recurso / Representação | RC05 exige transações atômicas para evitar inconsistência financeira; RS04 garante compatibilidade com APIs externas de pagamento. |
    |**Artefatos de Elicitação** | [Brainstorm (BRS10)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Representação | BRS10 originou a necessidade de integração com meios de pagamento digitais (Pix, carteiras virtuais). |

# Requisitos  não Funcionais

??? info "RF01 – Exibir a localização dos ônibus em tempo real no mapa"

    *Autoria: João Gabriel*

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 1: Rastreamento e Informações em Tempo Real | Agregação | Agrega RF01 como funcionalidade central do épico |
    |**História de Usuário** | US15 | Representação | US15 representa a implementação do RF01 em termos de usuário |
    |**Léxico** | L12: Tempo real | Representação | L12 representa o conceito de tempo real do RF01 |
    |**Casos de Uso** | UC03 | Representação | UC03 modela a interação para exibir localização em tempo real |
    |**Cenários** | CEN03 | Representação | CEN03 descreve situação de uso do RF01 |
    |**Artefatos de Elicitação** | [Análise de Documentos (RF01)](../Elicitacao/elicitacao_analise_documentos.md#requisitos-funcionais), [Entrevista (ENT03)](../Elicitacao/elicitacao_entrevista.md#resultados) | Agregação | Agrega dados de múltiplas fontes de elicitação |

??? info "RF02 – Mostrar o tempo estimado de chegada do ônibus à parada"

    *Autoria: João Gabriel*

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 1: Rastreamento e Informações em Tempo Real | Agregação | Agrega RF02 como funcionalidade complementar do épico |
    |**História de Usuário** | US16 | Representação | US16 representa a implementação do RF02 em termos de usuário |
    |**Léxico** | L09: Agora | Representação | L09 representa o conceito de tempo atual do RF02 |
    |**Casos de Uso** | UC02 | Representação | UC02 modela a interação para mostrar tempo estimado |
    |**Cenários** | CEN01 | Representação | CEN01 descreve situação de uso do RF02 |
    |**Artefatos de Elicitação** | [Entrevista (ENT04)](../Elicitacao/elicitacao_entrevista.md#resultados) | Representação | ENT04 representa a necessidade do RF02 |

??? info "RF03 – Permitir planejamento de viagem com rotas sugeridas"

    *Autoria: João Gabriel*
    
     |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 7: Planejamento de Viagens | Agregação | Agrega RF03 como funcionalidade principal do épico |
    |**História de Usuário** | US17 | Representação | US17 representa a implementação do RF03 em termos de usuário |
    |**Léxico** | L05: Planejar | Representação | L05 representa o conceito de planejamento do RF03 |
    |**Casos de Uso** | UC09 | Representação | UC09 modela a interação para planejamento de viagens |
    |**Cenários** | CEN09 | Representação | CEN09 descreve situação de uso do RF03 |
    |**Artefatos de Elicitação** | [Análise de Documentos (RNI02)](../Elicitacao/elicitacao_analise_documentos.md#requisitos-nao-implementados) | Satisfação | RNI02 satisfaz a necessidade do RF03 |

??? info "RF04 – Permitir pesquisa por linhas e rotas de ônibus"

    *Autoria: João Gabriel*

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 2: Filtragem | Agregação | Agrega RF04 como funcionalidade central do épico |
    |**História de Usuário** | US18 | Representação | US18 representa a implementação do RF04 em termos de usuário |
    |**Léxico** | L11: Pesquisar | Representação | L11 representa o conceito de pesquisa do RF04 |
    |**Casos de Uso** | *Não identificados* | — | — |
    |**Cenários** | *Não identificados* | — | — |
    |**Artefatos de Elicitação** | [Análise de Documentos (RF02)](../Elicitacao/elicitacao_analise_documentos.md#requisitos-funcionais), [Entrevista (ENT01)](../Elicitacao/elicitacao_entrevista.md#resultados) | Agregação | Agrega dados de múltiplas fontes de elicitação |

??? info "RF05 – Apresentar horários de saída e chegada dos transportes"

    *Autoria: João Gabriel*

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 1: Rastreamento e Informações em Tempo Real | Agregação | Agrega RF05 como funcionalidade informativa do épico |
    |**História de Usuário** | US05, US19 | Representação | US05 e US19 representam a implementação do RF05 |
    |**Léxico** | L09: Agora | Representação | L09 representa o conceito de tempo atual do RF05 |
    |**Casos de Uso** | *Não identificados* | — | — |
    |**Cenários** | *Não identificados* | — | — |
    |**Artefatos de Elicitação** | [Entrevista (ENT02)](../Elicitacao/elicitacao_entrevista.md#resultados) | Representação | ENT02 representa a necessidade do RF05 |

??? info "RF13 – Oferecer recarga de cartão de transporte (ex.: integração com BRB Mobilidade)"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 1: Rastreamento e Informações em Tempo Real | | |
    |**História de Usuário** | *Não identificada* | | |
    |**Léxico** | *Não identificado* | | |
    |**Casos de Uso** | *Não identificados* | | |
    |**Cenários** | *Não identificados* | | |
    |**Artefatos de Elicitação** | ENT09 | | |

??? info "RF09 – Indicar lotação do ônibus (vazio, moderado, lotado)"

    *Autoria: João Ramos*

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 4: Avaliar e Reportar | Agregação | A funcionalidade de indicar lotação compõe o conjunto de avaliação e reporte da experiência do usuário. |
    |**História de Usuário** | US03 | Representação | A história detalha a necessidade de visualização e avaliação da lotação das linhas. |
    |**Léxico** | *Não identificado* | — | — |
    |**Casos de Uso** | UC01 | Representação | UC01 modela o fluxo de avaliação/consulta de métricas das linhas, incluindo lotação. |
    |**Cenários** | CEN02 | Representação | Cenário que descreve o usuário consultando a lotação em tempo real. |
    |**Artefatos de Elicitação** | [Entrevista (ENT11)](../Elicitacao/elicitacao_entrevista.md#resultados), [Brainstorm (BRS07)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Representação | ENT11 e BRS07 fundamentam a necessidade de indicar lotação. |

??? info "RF10 – Permitir que usuários reportem a lotação do ônibus (sistema colaborativo)"

    *Autoria: João Ramos*

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 4: Avaliar e Reportar | Representação | O reporte colaborativo é parte das funcionalidades de avaliação e feedback do sistema. |
    |**História de Usuário** | US03 | Representação | A história contempla a ação do usuário em reportar condições do ônibus (lotação). |
    |**Léxico** | *Não identificado* | — | — |
    |**Casos de Uso** | UC01 | Representação | UC01 inclui fluxos de envio e processamento de reports pelos usuários. |
    |**Cenários** | CEN02 | Representação | Cenário exemplifica um usuário reportando a lotação durante a viagem. |
    |**Artefatos de Elicitação** | [Entrevista (ENT11)](../Elicitacao/elicitacao_entrevista.md#resultados), [Brainstorm (BRS03)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Representação | ENT11 e BRS03 são fontes que justificam o desenvolvimento do recurso colaborativo. |

??? info "RF11 – Enviar notificação quando o ônibus estiver a X minutos da parada"

    *Autoria: João Ramos*

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 1: Rastreamento e Informações em Tempo Real | Representação | Notificações baseadas em proximidade fazem parte do rastreamento em tempo real. |
    |**História de Usuário** | US15 | Satisfação | A US que demanda alertas de chegada fundamenta este requisito. |
    |**Léxico** | *Não identificado* | — | — |
    |**Casos de Uso** | UC03 | Representação | UC03 descreve fluxos de rastreamento e envio de notificações ao usuário. |
    |**Cenários** | CEN03 | Representação | Cenário exemplifica o recebimento de notificação quando o veículo se aproxima. |
    |**Artefatos de Elicitação** | [Análise de Documentos (RNI01)](../Elicitacao/elicitacao_analise_documentos.md#requisitos-nao-implementados), [Entrevista (ENT15)](../Elicitacao/elicitacao_entrevista.md#resultados), [Brainstorm (BRS05)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Representação | RNI01, ENT15 e BRS05 suportam a necessidade de notificações de proximidade. |

??? info "RF12 – Enviar alertas sobre atrasos, mudanças de rota ou alterações nos horários"

    *Autoria: João Ramos*

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 1: Rastreamento e Informações em Tempo Real | Representação | Alertas operacionais são parte do escopo de rastreamento em tempo real. |
    |**História de Usuário** | US15 | Representação | A história que trata de informações em tempo real justifica alertas sobre mudanças. |
    |**Léxico** | *Não identificado* | — | — |
    |**Casos de Uso** | UC03 | Representação | UC03 contempla fluxos de monitoramento e notificação diante de eventos operacionais. |
    |**Cenários** | CEN03 | Representação | Cenário descreve usuário recebendo alerta de atraso ou alteração de rota. |
    |**Artefatos de Elicitação** | [Entrevista (ENT05)](../Elicitacao/elicitacao_entrevista.md#resultados), [Brainstorm (BRS05)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Representação | ENT05 e BRS05 são fontes que motivam a implementação de alertas operacionais. |

??? info "RF18 – Listar linhas que passam em uma parada específica"

    *Autoria: João Ramos*

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 2: Filtragem | Representação | A listagem por parada é uma funcionalidade de filtragem e descoberta de linhas. |
    |**História de Usuário** | US01 | Representação | US01 de filtragem representa a necessidade de consultar linhas por parada. |
    |**Léxico** | *Não identificado* | — | — |
    |**Casos de Uso** | UC02 | Representação | UC02 modela a busca/consulta de linhas por critérios (ex.: parada). |
    |**Cenários** | CEN01 | Representação | Cenário descreve usuário consultando linhas que passam em uma parada. |
    |**Artefatos de Elicitação** | [Brainstorm (BRS05)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Representação | BRS05 fundamenta a necessidade de listagem por parada. |

??? info "RF21 – Mostrar alertas de trânsito, acidentes e rotas alternativas"

    *Autoria: João Ramos*

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 1: Rastreamento e Informações em Tempo Real | Representação | Alertas de tráfego complementam o rastreamento e planejamento de rotas em tempo real. |
    |**História de Usuário** | US15 | Representação | A US de informação em tempo real contempla alertas operacionais e alterações de rota. |
    |**Léxico** | *Não identificado* | — | — |
    |**Casos de Uso** | UC03 | Representação | UC03 inclui fluxo de recepção e exibição de alertas de trânsito ao usuário. |
    |**Cenários** | CEN03 | Representação | Cenário exemplifica a notificação de incidente e sugestão de rota alternativa. |
    |**Artefatos de Elicitação** | [Brainstorm (BRS12)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Representação | BRS12 é a fonte que sugere a necessidade de alertas de trânsito e rotas alternativas. |

??? info "RF14 – Permitir integração com o cartão de transporte, incluindo saldo e recarga"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 1: Rastreamento e Informações em Tempo Real | | |
    |**História de Usuário** | *Não identificada* | | |
    |**Léxico** | *Não identificado* | | |
    |**Casos de Uso** | *Não identificados* | | |
    |**Cenários** | *Não identificados* | | |
    |**Artefatos de Elicitação** | ENT09 | | |

??? info "RF15 – Manter histórico de viagens do usuário"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 1: Rastreamento e Informações em Tempo Real | | |
    |**História de Usuário** | *Não identificada* | | |
    |**Léxico** | *Não identificado* | | |
    |**Casos de Uso** | *Não identificados* | | |
    |**Cenários** | *Não identificados* | | |
    |**Artefatos de Elicitação** | ENT09 | | |

??? info "RF16 – Permitir reportar problemas (motorista, ônibus, cobrança) com dados do veículo e horário"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 1: Rastreamento e Informações em Tempo Real | | |
    |**História de Usuário** | *Não identificada* | | |
    |**Léxico** | *Não identificado* | | |
    |**Casos de Uso** | *Não identificados* | | |
    |**Cenários** | *Não identificados* | | |
    |**Artefatos de Elicitação** | ENT09 | | |

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

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 1: Rastreamento e Informações em Tempo Real | | |
    |**História de Usuário** | *Não identificada* | | |
    |**Léxico** | *Não identificado* | | |
    |**Casos de Uso** | *Não identificados* | | |
    |**Cenários** | *Não identificados* | | |
    |**Artefatos de Elicitação** | ENT09 | | |

??? info "RF25 – Ampliar a cobertura e exibir informações também em regiões afastadas do Distrito Federal"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 1: Rastreamento e Informações em Tempo Real | | |
    |**História de Usuário** | *Não identificada* | | |
    |**Léxico** | *Não identificado* | | |
    |**Casos de Uso** | *Não identificados* | | |
    |**Cenários** | *Não identificados* | | |
    |**Artefatos de Elicitação** | ENT09 | | |

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

    *Autoria: João Gabriel*

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 7: Planejamento de Viagens | Agregação | Agrega RF30 como funcionalidade inteligente do épico |
    |**História de Usuário** | US31 | Representação | US31 representa a implementação do RF30 em termos de usuário |
    |**Léxico** | *Não identificado* | — | — |
    |**Casos de Uso** | UC10 | Representação | UC10 modela a interação para previsão inteligente |
    |**Cenários** | CEN10 | Representação | CEN10 descreve situação de uso do RF30 |
    |**Artefatos de Elicitação** | [Brainstorm (BRS02)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Representação | BRS02 representa a necessidade do RF30 |

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

    *Autoria: João Gabriel*

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 8: Gestão de Usuário e Conta | Agregação | Agrega RF37 como funcionalidade central do épico |
    |**História de Usuário** | US32 | Representação | US32 representa a implementação do RF37 em termos de usuário |
    |**Léxico** | *Não identificado* | — | — |
    |**Casos de Uso** | UC01 | Representação | UC01 modela a interação para cadastro e autenticação |
    |**Cenários** | *Não identificados* | — | — |
    |**Artefatos de Elicitação** | [Brainstorm (BRS18)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Representação | BRS18 representa a necessidade do RF37 |


## Tabela de Contribuição

|        Nome          | Contribuição|
|----------------------|-------------|
| Cauã Nicolas         | A preencher |
| Daniel Nunes Duarte  | A preencher |
| Fernanda Vaz         | A preencher |
| Gabriel Maciel       | A preencher |
| João Gabriel         | Adição RNF1 ao RNF3 e RF01 ao RF05, RF37, RF30 |
| João Ramos           | Forward: RF9 ao RF12 e RF18 e RF21; RNF09 e RNF 12 |

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
| 1.3 | 26/10 | Adição RF9 ao RF12 e RF18 e RF21; RNF09 e RNF 12 | João Ramos | Cauã Nicolas |
## Agradecimentos

>Agradecemos o suporte da ferramenta de Inteligência Artificial Generativa Google Gemini no desenvolvimento deste trabalho. Em conformidade com o Código de Conduta da Sociedade Brasileira de Computação (SBC), declaramos que a ferramenta foi utilizada como auxílio na revisão gramatical e estilística do texto, na sugestão de estrutura para seções específicas do artigo, bem como na formatação de tabelas e na descrição de figuras. Ressaltamos que os autores assumem total responsabilidade por todo o conteúdo apresentado, incluindo sua originalidade e precisão. A ferramenta não figura como autora desta publicação.
