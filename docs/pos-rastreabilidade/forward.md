# Forward-From

## Introdução
A rastreabilidade forward-from (pós-rastreabilidade) vincula requisitos a artefatos de desenho, implementação e validação (como código e casos de teste), rastreando-os desde a origem até a entrega.

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

---

## Tabela de Contribuição

| Nome | Contribuição |
|------|--------------|
| Cauã Nicolas | Adição [RNF04](#rnf04--interface-acessível-para-idosos-e-pessoas-com-deficiência-visual) e [RNF05](#rnf05--sistema-de-notificação-com-som-e-vibração-configuráveis), [RF13](#rf13--oferecer-recarga-de-cartão-de-transporte-ex-integração-com-brb-mobilidade), [RF14](#rf14--permitir-integração-com-o-cartão-de-transporte-incluindo-saldo-e-recarga), [RF15](#rf15--manter-histórico-de-viagens-do-usuário), [RF16](#rf16--permitir-reportar-problemas-motorista-ônibus-cobrança-com-dados-do-veículo-e-horário), [RF24](#rf24--permitir-favoritar-linhas-ou-paradas-para-acesso-rápido) e [RF25](#rf25--ampliar-a-cobertura-e-exibir-informações-também-em-regiões-afastadas-do-distrito-federal) |
| Daniel Nunes Duarte | Rastreabilidade Forward-From dos Requisitos [RF17](#rf17--exibir-preço-da-passagem-por-linha-ou-trajeto), [RF20](#rf20--botão-de-pânicoemergência-para-alertar-motorista-eou-autoridades), [RF22](#rf22--permitir-compartilhar-trajeto-em-tempo-real-com-outros-usuários), [RF27](#rf27--visualizar-quais-veículos-estão-em-operação-no-momento), [RF29](#rf29--sistema-de-gamificação-para-incentivar-uso-do-transporte-público), [RF33](#rf33--suporte-a-comandos-de-voz-para-facilitar-interação-durante-deslocamentos), [RNF14](#rnf14--suporte-a-múltiplos-usuários-simultâneos-sem-lentidão), [RNF15](#rnf15--personalização-da-interface-com-base-em-preferências-do-usuário) |
| Fernanda Vaz | Forward: [RNF06](#rnf06--baixo-consumo-de-bateria-e-dados-móveis) e [RNF07](#rnf07--compatibilidade-com-dispositivos-android-e-ios), [RF05](#rf05--apresentar-horários-de-saída-e-chegada-dos-transportes), [RF06](#rf06--oferecer-um-mapa-interativo-com-os-pontos-de-ônibus-e-suas-linhas-correspondentes), [RF07](#rf07--integrar-informações-de-outros-modais-metrô-outros-ônibus-em-rotas-multimodais), [RF08](#rf08--exibir-informações-de-acessibilidade-do-ônibus-ex-acessível-para-cadeirantes), [RF31](#rf31--sistema-de-recompensas-por-uso-sustentável-do-transporte-público), [RF32](#rf32--exibir-relatórios-de-impacto-ambiental-co₂-economizado) |
| Gabriel Maciel | Rastreabilidade Forward-From dos Requisitos [RF19](#rf19--disponibilizar-versão-web-leve-para-acesso-rápido-em-pontos-de-ônibus-via-qr-code), [RF26](#rf26--filtrar-ônibus-por-empresa-operadora), [RF28](#rf28--permitir-avaliação-da-qualidade-do-serviço-de-cada-linha), [RF34](#rf34--integração-com-assistentes-virtuais-alexa-google-assistant), [RF35](#rf35--permitir-rastreamento-de-múltiplas-linhas-de-ônibus-simultaneamente-no-mapa), [RF36](#rf36--oferecer-suporte-multilíngue-português-e-inglês-no-mínimo), [RNF10](#rnf10--tempo-de-carregamento-da-tela-principal--3-segundos), [RNF11](#rnf11--funcionamento-offline-para-consulta-a-rotas-salvas-e-horários) |
| João Gabriel | Adição [RNF01](#rnf01--as-informações-de-horários-e-localização-dos-ônibus-devem-ser-precisas) ao [RNF03](#rnf03--tempo-de-atualização-da-localização--20-segundos) e [RF01](#rf01--exibir-a-localização-dos-ônibus-em-tempo-real-no-mapa) ao [RF05](#rf05--apresentar-horários-de-saída-e-chegada-dos-transportes), [RF37](#rf37--permitir-cadastro-login-e-autenticação-de-usuários-no-sistema), [RF30](#rf30--previsão-inteligente-de-horários-baseada-em-dados-históricos-e-machine-learning) |
| João Ramos | Adição [RNF09](#rnf09--dados-de-localização-e-pessoais-protegidos-conforme-lgpd), [RNF12](#rnf12--integração-segura-com-sistemas-de-pagamento-recarga-de-cartão), [RF09](#rf09--indicar-lotação-do-ônibus-vazio-moderado-lotado), [RF10](#rf10--permitir-que-usuários-reportem-a-lotação-do-ônibus-sistema-colaborativo), [RF11](#rf11--enviar-notificação-quando-o-ônibus-estiver-a-x-minutos-da-parada), [RF18](#rf18--listar-linhas-que-passam-em-uma-parada-específica), [RF21](#rf21--mostrar-alertas-de-trânsito-acidentes-e-rotas-alternativas) |

---

# Rastreabilidade de Requisitos

## **Requisitos Não-Funcionais**

??? info "RNF01 – As informações de horários e localização dos ônibus devem ser precisas"

    *Autoria: João Gabriel*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Especificação Suplementar** | [Confiabilidade](../modelagem_requisitos_01/especificacao_suplementar.md#confiabilidade) | Representação | Representa os critérios de precisão do RNF01 |
    | **NFR** | [SIG - Confiabilidade](../modelagem_requisitos_02/nfr.md#sig-confiabilidade) | Satisfação | Satisfaz o requisito de confiabilidade do sistema |
    | **Artefatos de Elicitação** | [Entrevista (ENT09)](../Elicitacao/elicitacao_entrevista.md#resultados) | Representação | ENT09 representa a necessidade de precisão nas informações |

??? info "RNF02 – Rastreamento dos ônibus em tempo real deve ser confiável e sem falhas"

    *Autoria: João Gabriel*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Especificação Suplementar** | [Confiabilidade](../modelagem_requisitos_01/especificacao_suplementar.md#confiabilidade) | Representação | Representa os critérios de confiabilidade do RNF02 |
    | **NFR** | [SIG - Confiabilidade](../modelagem_requisitos_02/nfr.md#sig-confiabilidade) | Satisfação | Satisfaz o requisito de confiabilidade do sistema |
    | **Artefatos de Elicitação** | [Entrevista (ENT13)](../Elicitacao/elicitacao_entrevista.md#resultados) | Representação | ENT13 representa a necessidade de rastreamento confiável |

??? info "RNF03 – Tempo de atualização da localização ≤ 20 segundos"

    *Autoria: João Gabriel*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Especificação Suplementar** | [Desempenho](../modelagem_requisitos_01/especificacao_suplementar.md#desempenho) | Representação | Representa os critérios de desempenho do RNF03 |
    | **NFR** | [SIG-Desempenho](../modelagem_requisitos_02/nfr.md#sig-desempenho) | Satisfação | Satisfaz o requisito de desempenho do sistema |
    | **Artefatos de Elicitação** | [Entrevista (ENT)](../Elicitacao/elicitacao_entrevista.md#resultados) | Representação | ENT representa a necessidade de atualização rápida |

??? info "RNF04 – Interface acessível para idosos e pessoas com deficiência visual"

    *Autoria: Cauã Nicolas*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Especificação Suplementar** | [Usabilidade](../modelagem_requisitos_01/especificacao_suplementar.md#usabilidade) | Responsabilidade | A especificação define critérios de acessibilidade (WCAG) que a equipe deve implementar. |
    | **NFR** | [SIG Usabilidade](../modelagem_requisitos_02/nfr.md#sig-usabilidade) | Representação | O SIG de usabilidade operacionaliza requisitos como suporte a leitores de tela e contraste (RU05 / RU09). |
    | **Artefatos de Elicitação** | [Entrevista (ENT16)](../Elicitacao/elicitacao_entrevista.md#resultados), [Entrevista (ENT09)](../Elicitacao/elicitacao_entrevista.md#resultados) | Satisfação | ENT16 e ENT09 indicam a necessidade de interfaces acessíveis e confiáveis para diferentes perfis de usuário. |

??? info "RNF05 – Sistema de notificação com som e vibração configuráveis"

    *Autoria: Cauã Nicolas*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Especificação Suplementar** | [Requisitos do Sistema](../modelagem_requisitos_01/especificacao_suplementar.md#requisitos-do-sistema-portabilidadecompatibilidade) | Responsabilidade | A especificação registra que notificações devem ser configuráveis e respeitar preferências do usuário (som/vibração). |
    | **NFR** | [SIG Usabilidade](../modelagem_requisitos_02/nfr.md#sig-usabilidade) | Representação | O cartão RU06 / RNF06 (Feedback e Comunicação) define critérios de mensagem e notificações. |
    | **Artefatos de Elicitação** | [Entrevista (ENT15)](../Elicitacao/elicitacao_entrevista.md#resultados), [Entrevista (ENT05)](../Elicitacao/elicitacao_entrevista.md#resultados) | Satisfação | ENT15/ENT05 descrevem expectativas de notificações relevantes e configuráveis pelos usuários. |

??? info "RNF06 – Baixo consumo de bateria e dados móveis"

    *Autoria: Fernanda Vaz*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Especificação Suplementar** | [Portabilidade/Compatibilidade](../modelagem_requisitos_01/especificacao_suplementar.md#portabilidadecompatibilidade) | Alocado | O requisito está alocado ao subsistema de otimização do aplicativo, responsável por reduzir o uso de energia e dados móveis. |
    | **NFR** | [Desempenho](../modelagem_requisitos_02/nfr.md#sig-desempenho) | Representação | O NFR de desempenho representa este RNF e define critérios técnicos de otimização. |
    | **Artefatos de Elicitação** | — | — | Requisito técnico derivado de decisões dos desenvolvedores durante o processo de especificação. |

??? info "RNF07 – Compatibilidade com dispositivos Android e iOS"

    *Autoria: Fernanda Vaz*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Especificação Suplementar** | [Compatibilidade](../modelagem_requisitos_01/especificacao_suplementar.md#portabilidadecompatibilidade) | Responsabilidade | A responsabilidade é da equipe de desenvolvimento em garantir a portabilidade e compatibilidade do aplicativo entre plataformas. |
    | **NFR** | [SIG Compatibilidade](../modelagem_requisitos_02/nfr.md#sig-compatibilidade) | Representação | O NFR Framework representa a compatibilidade entre sistemas operacionais, reforçando a necessidade de comportamento uniforme no Android e iOS. |
    | **Artefatos de Elicitação** | [Entrevista (ENT19)](../Elicitacao/elicitacao_entrevista.md#resultados) | Representação | A ENT19 originou o requisito, evidenciando a importância da compatibilidade com os sistemas Android e iOS. |

??? info "RNF09 – Dados de localização e pessoais protegidos conforme LGPD"

    *Autoria: João Ramos*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | [Épico 8: Gestão de Usuário e Conta](../modelagem_requisitos_02/backlog.md#épico-8---gestão-de-usuário-e-conta) | Representação | A gestão de usuários engloba consentimento, controle e proteção de dados pessoais. |
    | **História de Usuário** | [US30 - Criar conta e fazer login de forma segura](../modelagem_requisitos_02/historias_de_usuario.md#us30---criar-uma-conta-e-fazer-login-de-forma-segura) | Representação | US30 descreve operações que envolvem dados pessoais e autenticação, demandando conformidade com proteção de dados. |
    | **Léxico** | *Não identificado* | — | — |
    | **Casos de Uso** | UC01 (ex.: Avaliação de Linhas) e UC04 (Integração BRB) — pré-condição de usuário autenticado | Representação | Vários casos de uso exigem autenticação e tratamento de dados pessoais; UC04 e UC01 citam pré-condição de usuário autenticado. |
    | **Especificação / NFR** | [Privacidade (RPV01..RPV06)](../modelagem_requisitos_01/especificacao_suplementar.md#privacidade) | Representação | A Especificação Suplementar define requisitos de privacidade (minimização de dados, consentimento, criptografia em repouso, DPIA). |
    | **Artefatos de Elicitação** | [Entrevista (ENT21)](../Elicitacao/elicitacao_entrevista.md#resultados) | Representação | ENT21 é a fonte que destaca a necessidade de proteção de dados pessoais e conformidade com a LGPD. |

??? info "RNF10 – Tempo de carregamento da tela principal < 3 segundos"

    *Autoria: Gabriel Maciel*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Especificação Suplementar** | [RD02 - Tempo de Carregamento Rápido](../modelagem_requisitos_01/especificacao_suplementar.md#desempenho) | Representação | RD02 representa e detalha o requisito RNF10 na Especificação Suplementar |
    | **NFR** | [RD02 / RNF06 - Tempo de Carregamento Rápido](../modelagem_requisitos_02/nfr.md#sig-desempenho) | Representação | O cartão de especificação RD02 no NFR Framework detalha os critérios de ajuste e dependências de RNF10 |
    | **Artefatos de Elicitação** | [Entrevista (ENT17)](../Elicitacao/elicitacao_entrevista.md#resultados) | Satisfação | ENT17 é a fonte de elicitação que satisfaz e fundamenta a necessidade do RNF10 |

??? info "RNF11 – Funcionamento offline para consulta a rotas salvas e horários"

    *Autoria: Gabriel Maciel*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Especificação Suplementar** | *Não identificada* | — | — |
    | **NFR** | [RS02 - Funcionamento Offline](../modelagem_requisitos_02/nfr.md#rs02-funcionamento-offline) | Representação | O cartão de especificação RS02 no NFR Framework detalha os critérios de ajuste e dependências de RNF11 |
    | **Artefatos de Elicitação** | [Análise de Documentos (RNI05)](../Elicitacao/elicitacao_analise_documentos.md#requisitos-nao-implementados), [Entrevista (ENT18)](../Elicitacao/elicitacao_entrevista.md#resultados), [Brainstorm (BRS06)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Satisfação | RNI05, ENT18 e BRS06 são fontes de elicitação que satisfazem e fundamentam a necessidade do RNF11 |

??? info "RNF12 – Integração segura com sistemas de pagamento (recarga de cartão)"

    *Autoria: João Ramos*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | [Épico 5: Integração e Recargas](../modelagem_requisitos_02/backlog.md#épico-5---integração-e-recargas) | Representação | O épico agrega funcionalidades de integração com provedores de recarga e pagamento. |
    | **História de Usuário** | [US11 - Oferecer Recarga de Cartão de Transporte](../modelagem_requisitos_02/historias_de_usuario.md#us11---oferecer-recarga-de-cartão-de-transporte) | Representação | US11 descreve a funcionalidade de recarga integrada e suas opções de pagamento. |
    | **Léxico** | *Não identificado* | — | — |
    | **Casos de Uso** | [Tabela 6 - UC04: Integração com BRB Mobilidade (Requisito não implementado)](../modelagem_requisitos_01/casos_de_uso.md#tabela-6---uc04-integracao-com-brb-mobilidade-requisito-nao-implementado) | Representação | UC04 descreve o fluxo de consulta de saldo e recarga via integração com o BRB Mobilidade. |
    | **Cenários** | [Cenário 4 - Integração com BRB Mobilidade (Requisito não implementado)](../modelagem_requisitos_01/cenarios.md#cenário-4---integração-com-brb-mobilidade-requisito-não-implementado) | Representação | Cenário 4 exemplifica o uso da integração para recarga e confirmação de transação. |
    | **NFR / Especificação** | [RC05 - Atomicidade de Transações](../modelagem_requisitos_02/nfr.md#rc05---atomicidade-de-transações), [RS04 - Compatibilidade com APIs Externas](../modelagem_requisitos_02/nfr.md#rs04---compatibilidade-com-apis-externas) | Recurso / Representação | RC05 exige transações atômicas para evitar inconsistência financeira; RS04 garante compatibilidade com APIs externas de pagamento. |
    | **Artefatos de Elicitação** | [Brainstorm (BRS10)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Representação | BRS10 originou a necessidade de integração com meios de pagamento digitais (Pix, carteiras virtuais). |

??? info "RNF14 – Suporte a múltiplos usuários simultâneos sem lentidão"

    *Autoria: Daniel Nunes Duarte*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Especificação Suplementar** | [Desempenho / Requisitos do Sistema](../modelagem_requisitos_01/especificacao_suplementar.md#desempenho) | Representação | Relaciona-se com requisitos de capacidade e performance que detalham o suporte a múltiplos usuários simultâneos |
    | **NFR** | [SIG - Desempenho / RS - Escalabilidade](../modelagem_requisitos_02/nfr.md#sig-desempenho) | Satisfação | Satisfaz a necessidade de dimensionamento e escalabilidade do sistema |
    | **Artefatos de Elicitação** | [Brainstorm (BRS15)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Representação | BRS15 indicou a necessidade de suportar múltiplos usuários concorrentes sem degradação perceptível |

??? info "RNF15 – Personalização da interface com base em preferências do usuário"

    *Autoria: Daniel Nunes Duarte*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Especificação Suplementar** | [Usabilidade / Privacidade](../modelagem_requisitos_01/especificacao_suplementar.md#usabilidade) | Representação | Relaciona-se com requisitos de usabilidade e privacidade que regem preferências e armazenamento de configurações do usuário |
    | **NFR** | [SIG - Usabilidade](../modelagem_requisitos_02/nfr.md#sig-usabilidade) | Satisfação | Satisfaz a necessidade de adaptação da interface para diferentes perfis e preferências de usuário |
    | **Artefatos de Elicitação** | [Brainstorm (BRS13)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Representação | BRS13 trouxe sugestões de personalização da interface como melhoria de usabilidade |

---

## **Requisitos Funcionais**

??? info "RF01 – Exibir a localização dos ônibus em tempo real no mapa"

    *Autoria: João Gabriel*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | [Épico 1: Rastreamento e Informações em Tempo Real](../modelagem_requisitos_02/backlog.md#épico-1---rastreamento-e-informações-em-tempo-real) | Agregação | Agrega RF01 como funcionalidade central do épico |
    | **História de Usuário** | [US15](../modelagem_requisitos_02/historias_de_usuario.md#us15) | Representação | US15 representa a implementação do RF01 em termos de usuário |
    | **Léxico** | [L12: Tempo real](../modelagem_requisitos_01/lexico.md#l12-tempo-real) | Representação | L12 representa o conceito de tempo real do RF01 |
    | **Casos de Uso** | [UC03](../modelagem_requisitos_01/casos_de_uso.md#uc03) | Representação | UC03 modela a interação para exibir localização em tempo real |
    | **Cenários** | [CEN03](../modelagem_requisitos_01/cenarios.md#cen03) | Representação | CEN03 descreve situação de uso do RF01 |
    | **Artefatos de Elicitação** | [Análise de Documentos (RF01)](../Elicitacao/elicitacao_analise_documentos.md#requisitos-funcionais), [Entrevista (ENT03)](../Elicitacao/elicitacao_entrevista.md#resultados) | Agregação | Agrega dados de múltiplas fontes de elicitação |

??? info "RF02 – Mostrar o tempo estimado de chegada do ônibus à parada"

    *Autoria: João Gabriel*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | [Épico 1: Rastreamento e Informações em Tempo Real](../modelagem_requisitos_02/backlog.md#épico-1---rastreamento-e-informações-em-tempo-real) | Agregação | Agrega RF02 como funcionalidade complementar do épico |
    | **História de Usuário** | [US16](../modelagem_requisitos_02/historias_de_usuario.md#us16) | Representação | US16 representa a implementação do RF02 em termos de usuário |
    | **Léxico** | [L09: Agora](../modelagem_requisitos_01/lexico.md#l09-agora) | Representação | L09 representa o conceito de tempo atual do RF02 |
    | **Casos de Uso** | [UC02](../modelagem_requisitos_01/casos_de_uso.md#uc02) | Representação | UC02 modela a interação para mostrar tempo estimado |
    | **Cenários** | [CEN01](../modelagem_requisitos_01/cenarios.md#cen01) | Representação | CEN01 descreve situação de uso do RF02 |
    | **Artefatos de Elicitação** | [Entrevista (ENT04)](../Elicitacao/elicitacao_entrevista.md#resultados) | Representação | ENT04 representa a necessidade do RF02 |

??? info "RF03 – Permitir planejamento de viagem com rotas sugeridas"

    *Autoria: João Gabriel*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | [Épico 7: Planejamento de Viagens](../modelagem_requisitos_02/backlog.md#épico-7---planejamento-de-viagens) | Agregação | Agrega RF03 como funcionalidade principal do épico |
    | **História de Usuário** | [US17](../modelagem_requisitos_02/historias_de_usuario.md#us17) | Representação | US17 representa a implementação do RF03 em termos de usuário |
    | **Léxico** | [L05: Planejar](../modelagem_requisitos_01/lexico.md#l05-planejar) | Representação | L05 representa o conceito de planejamento do RF03 |
    | **Casos de Uso** | [UC09](../modelagem_requisitos_01/casos_de_uso.md#uc09) | Representação | UC09 modela a interação para planejamento de viagens | 
     | **Cenários** | [CEN09](../modelagem_requisitos_01/cenarios.md#cen09) | Representação | CEN09 descreve situação de uso do RF03 |
    | **Artefatos de Elicitação** | [Análise de Documentos (RNI02)](../Elicitacao/elicitacao_analise_documentos.md#requisitos-nao-implementados) | Satisfação | RNI02 satisfaz a necessidade do RF03 |
    

??? info "RF04 – Permitir pesquisa por linhas e rotas de ônibus"

    *Autoria: João Gabriel*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | [Épico 2: Filtragem](../modelagem_requisitos_02/backlog.md#épico-2---filtragem) | Agregação | Agrega RF04 como funcionalidade central do épico |
    | **História de Usuário** | [US18](../modelagem_requisitos_02/historias_de_usuario.md#us18) | Representação | US18 representa a implementação do RF04 em termos de usuário |
    | **Léxico** | [L11: Pesquisar](../modelagem_requisitos_01/lexico.md#l11-pesquisar) | Representação | L11 representa o conceito de pesquisa do RF04 |
    | **Casos de Uso** | *Não identificados* | — | — |
    | **Cenários** | *Não identificados* | — | — |
    | **Artefatos de Elicitação** | [Análise de Documentos (RF02)](../Elicitacao/elicitacao_analise_documentos.md#requisitos-funcionais), [Entrevista (ENT01)](../Elicitacao/elicitacao_entrevista.md#resultados) | Agregação | Agrega dados de múltiplas fontes de elicitação |

??? info "RF05 – Apresentar horários de saída e chegada dos transportes"

    *Autoria: João Gabriel*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | [Épico 1: Rastreamento e Informações em Tempo Real](../modelagem_requisitos_02/backlog.md#épico-1---rastreamento-e-informações-em-tempo-real) | Agregação | Agrega RF05 como funcionalidade informativa do épico |
    | **História de Usuário** | [US05](../modelagem_requisitos_02/historias_de_usuario.md#us05), [US19](../modelagem_requisitos_02/historias_de_usuario.md#us19) | Representação | US05 e US19 representam a implementação do RF05 |
    | **Léxico** | [L09: Agora](../modelagem_requisitos_01/lexico.md#l09-agora) | Representação | L09 representa o conceito de tempo atual do RF05 |
    | **Casos de Uso** | *Não identificados* | — | — |
    | **Cenários** | *Não identificados* | — | — |
    | **Artefatos de Elicitação** | [Entrevista (ENT02)](../Elicitacao/elicitacao_entrevista.md#resultados) | Representação | ENT02 representa a necessidade do RF05 |

??? info "RF06 – Oferecer um mapa interativo com os pontos de ônibus e suas linhas correspondentes"

    *Autoria: Fernanda Vaz*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | [Épico 1: Rastreamento e Informações em Tempo Real](../modelagem_requisitos_02/backlog.md#épico-1---rastreamento-e-informações-em-tempo-real) | Representação | O épico modela a visão geral de exibição no mapa |
    | **História de Usuário** | [US06 - Oferecer um Mapa Interativo com os Pontos de Ônibus e suas Linhas Correspondentes](../modelagem_requisitos_02/historias_de_usuario.md#us06---oferecer-um-mapa-interativo-com-os-pontos-de-ônibus-e-suas-linhas-correspondentes) | Representação | A história de usuário detalha o requisito funcional do mapa |
    | **Léxico** | [L01: Mapa](../modelagem_requisitos_01/lexico.md#l01-mapa) | Representação | O termo "mapa" é representado no léxico do sistema |
    | **Casos de Uso** | [Tabela 5 - UC03: Rastreamento de Múltiplas Linhas](../modelagem_requisitos_01/casos_de_uso.md#tabela-5---uc03-rastreamento-de-múltiplas-linhas-requisito-não-implementado) | Representação | UC03 descreve o fluxo de exibição e atualização dos pontos |
    | **Cenários** | [Cenário 3 - Rastreamento de múltiplas linhas](../modelagem_requisitos_01/cenarios.md#cenário-3---rastreamento-de-múltiplas-linhas-requisito-não-implementado) | Representação | Cenário ilustra uma situação prática de uso do mapa |
    | **Artefatos de Elicitação** | [Entrevista (ENT06)](../Elicitacao/elicitacao_entrevista.md#resultados) | Representação | ENT06 representa a origem e fundamentação do RF06 |

??? info "RF07 – Integrar informações de outros modais (metrô, outros ônibus) em rotas multimodais"

    *Autoria: Fernanda Vaz*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | [Épico 7: Planejamento de Viagens](../modelagem_requisitos_02/backlog.md#épico-7---planejamento-de-viagens) | Agregação | O épico agrega funcionalidades de múltiplos modais |
    | **História de Usuário** | [US07 - Integrar Informações de Outros Modais (Metrô, Outros Ônibus) em Rotas Multimodais](../modelagem_requisitos_02/historias_de_usuario.md#us07---integrar-informações-de-outros-modais-metrô-outros-ônibus-em-rotas-multimodais) | Representação | US07 detalha a funcionalidade de integração de rotas |
    | **Casos de Uso** | *Não identificados* | — | — |
    | **Cenários** | [Cenário 12 – Integração ônibus e metrô (Requisito não implementado)](../modelagem_requisitos_01/cenarios.md#cenário-12---integração-ônibus-e-metrô-requisito-não-implementado) | Agregação | Cenário exemplifica o uso da integração multimodal |
    | **Artefatos de Elicitação** | [BRS04](../Elicitacao/elicitacao_brainstorm.md#resultados), [RNI02](../Elicitacao/elicitacao_analise_documentos.md#requisitos-nao-implementados) | Agregação | O requisito agrega fontes externas de dados sobre modais |

??? info "RF08 – Exibir informações de acessibilidade do ônibus (ex.: acessível para cadeirantes)"

    *Autoria: Fernanda Vaz*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | [Épico 5: Integração e Recargas](../modelagem_requisitos_02/backlog.md#épico-5---integração-e-recargas) | Satisfação | O épico visa atender à acessibilidade conforme normas |
    | **História de Usuário** | [US08 - Exibir Informações de Acessibilidade do Ônibus](../modelagem_requisitos_02/historias_de_usuario.md#us08---exibir-informações-de-acessibilidade-do-ônibus) | Representação | US08 representa o requisito de informação de acessibilidade |
    | **Casos de Uso** | [Tabela 6 - UC04: Integração com BRB Mobilidade (Requisito não implementado)](../modelagem_requisitos_01/casos_de_uso.md#tabela-6---uc04-integração-com-brb-mobilidade-requisito-não-implementado) | Representação | UC04 descreve o fluxo de consulta à acessibilidade |
    | **Cenários** | [Cenário 4 - Integração com BRB Mobilidade (Requisito não implementado)](../modelagem_requisitos_01/cenarios.md#cenário-4---integração-com-brb-mobilidade-requisito-não-implementado) | Representação | Cenário apresenta exemplo de uso por pessoa com deficiência |
    | **Artefatos de Elicitação** | [Entrevista (ENT16)](../Elicitacao/elicitacao_entrevista.md#resultados) | Satisfação | ENT16 satisfaz a necessidade de inclusão e acessibilidade |

??? info "RF09 – Indicar lotação do ônibus (vazio, moderado, lotado)"

    *Autoria: João Ramos*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | [Épico 4: Avaliar e Reportar](../modelagem_requisitos_02/backlog.md#épico-4---avaliar-e-reportar) | Agregação | A funcionalidade de indicar lotação compõe o conjunto de avaliação e reporte da experiência do usuário. |
    | **História de Usuário** | [US03](../modelagem_requisitos_02/historias_de_usuario.md#us03) | Representação | A história detalha a necessidade de visualização e avaliação da lotação das linhas. |
    | **Léxico** | *Não identificado* | — | — |
    | **Casos de Uso** | [UC01](../modelagem_requisitos_01/casos_de_uso.md#uc01) | Representação | UC01 modela o fluxo de avaliação/consulta de métricas das linhas, incluindo lotação. |
    | **Cenários** | [CEN02](../modelagem_requisitos_01/cenarios.md#cen02) | Representação | CEN02 descreve o usuário consultando a lotação em tempo real. |
    | **Artefatos de Elicitação** | [Entrevista (ENT11)](../Elicitacao/elicitacao_entrevista.md#resultados), [Brainstorm (BRS07)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Representação | ENT11 e BRS07 fundamentam a necessidade de indicar lotação. |

??? info "RF10 – Permitir que usuários reportem a lotação do ônibus (sistema colaborativo)"

    *Autoria: João Ramos*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | [Épico 4: Avaliar e Reportar](../modelagem_requisitos_02/backlog.md#épico-4---avaliar-e-reportar) | Representação | O reporte colaborativo é parte das funcionalidades de avaliação e feedback do sistema. |
    | **História de Usuário** | [US03](../modelagem_requisitos_02/historias_de_usuario.md#us03) | Representação | A história contempla a ação do usuário em reportar condições do ônibus (lotação). |
    | **Léxico** | *Não identificado* | — | — |
    | **Casos de Uso** | [UC01](../modelagem_requisitos_01/casos_de_uso.md#uc01) | Representação | UC01 inclui fluxos de envio e processamento de reports pelos usuários. |
    | **Cenários** | [CEN02](../modelagem_requisitos_01/cenarios.md#cen02) | Representação | CEN02 exemplifica um usuário reportando a lotação durante a viagem. |
    | **Artefatos de Elicitação** | [Entrevista (ENT11)](../Elicitacao/elicitacao_entrevista.md#resultados), [Brainstorm (BRS03)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Representação | ENT11 e BRS03 são fontes que justificam o desenvolvimento do recurso colaborativo. |

??? info "RF11 – Enviar notificação quando o ônibus estiver a X minutos da parada"

    *Autoria: João Ramos*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | [Épico 1: Rastreamento e Informações em Tempo Real](../modelagem_requisitos_02/backlog.md#épico-1---rastreamento-e-informações-em-tempo-real) | Representação | Notificações baseadas em proximidade fazem parte do rastreamento em tempo real. |
    | **História de Usuário** | [US15](../modelagem_requisitos_02/historias_de_usuario.md#us15) | Satisfação | US15 demanda alertas de chegada, fundamentando este requisito. |
    | **Léxico** | *Não identificado* | — | — |
    | **Casos de Uso** | [UC03](../modelagem_requisitos_01/casos_de_uso.md#uc03) | Representação | UC03 descreve fluxos de rastreamento e envio de notificações ao usuário. |
    | **Cenários** | [CEN03](../modelagem_requisitos_01/cenarios.md#cen03) | Representação | CEN03 exemplifica o recebimento de notificação quando o veículo se aproxima. |
    | **Artefatos de Elicitação** | [Análise de Documentos (RNI01)](../Elicitacao/elicitacao_analise_documentos.md#requisitos-nao-implementados), [Entrevista (ENT15)](../Elicitacao/elicitacao_entrevista.md#resultados), [Brainstorm (BRS05)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Representação | RNI01, ENT15 e BRS05 suportam a necessidade de notificações de proximidade. |

??? info "RF13 – Oferecer recarga de cartão de transporte (ex.: integração com BRB Mobilidade)"

    *Autoria: Cauã Nicolas*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | [Épico 5: Integração e Recargas](../modelagem_requisitos_02/backlog.md#épico-5---integração-e-recargas) | Representação | O épico organiza funcionalidades de recarga e integração com provedores externos. |
    | **História de Usuário** | [US09 - Realizar recarga de cartão pelo app](../modelagem_requisitos_02/historias_de_usuario.md#us09---realizar-recarga-de-cartão-pelo-app) | Representação | A história detalha a interação do usuário para recarga e consulta de saldo. |
    | **Casos de Uso** | [UC05 – Recarga de Cartão](../modelagem_requisitos_01/casos_de_uso.md#uc05---recarga-de-cartão) | Representação | UC05 descreve o fluxo de recarga e integração com BRB Mobilidade. |
    | **Cenários** | [Cenário 4 – Integração BRB Mobilidade](../modelagem_requisitos_01/cenarios.md#cenário-4---integração-com-brb-mobilidade-requisito-não-implementado) | Representação | Cenário ilustra uso prático da funcionalidade de recarga. |
    | **Especificação Suplementar** | [Requisitos do Sistema](../modelagem_requisitos_01/especificacao_suplementar.md#requisitos-do-sistema-portabilidadecompatibilidade) | Responsabilidade | Regras de integração e segurança definidas na especificação orientam a implementação. |
    | **Artefatos de Elicitação** | [Entrevista (ENT07)](../Elicitacao/elicitacao_entrevista.md#resultados) | Representação | ENT07 relata a necessidade de integração e recarga do cartão pelo app. |

??? info "RF14 – Permitir integração com o cartão de transporte, incluindo saldo e recarga"

    *Autoria: Cauã Nicolas*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | [Épico 5: Integração e Recargas](../modelagem_requisitos_02/backlog.md#épico-5---integração-e-recargas) | Representação | O épico contempla integração com prestadores de serviços (ex.: BRB Mobilidade). |
    | **História de Usuário** | [US10 - Visualizar saldo e recarregar cartão](../modelagem_requisitos_02/historias_de_usuario.md#us10---visualizar-saldo-e-recarregar-cartão) | Representação | A história define critérios de aceitação e segurança da integração. |
    | **Casos de Uso** | [UC05 – Recarga de Cartão](../modelagem_requisitos_01/casos_de_uso.md#uc05---recarga-de-cartão) | Representação | UC05 cobre saldo, histórico e recarga integrados. |
    | **Cenários** | [Cenário 4 – Integração BRB Mobilidade](../modelagem_requisitos_01/cenarios.md#cenário-4---integração-com-brb-mobilidade-requisito-não-implementado) | Representação | Cenário demonstra fluxo de autenticação e recarga. |
    | **Especificação Suplementar** | [Requisitos do Sistema](../modelagem_requisitos_01/especificacao_suplementar.md#requisitos-do-sistema-portabilidadecompatibilidade) | Responsabilidade | Define requisitos de integração segura e formatos de API aceitos. |
    | **Artefatos de Elicitação** | [Entrevista (ENT07)](../Elicitacao/elicitacao_entrevista.md#resultados) | Representação | ENT07 descreve a necessidade de saldo e recarga integrados ao app. |

??? info "RF15 – Manter histórico de viagens do usuário"

    *Autoria: Cauã Nicolas*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | [Épico 4: Avaliar e Reportar / Épico 5: Integração e Recargas](../modelagem_requisitos_02/backlog.md#épico-4---avaliar-e-reportar) | Agregação | Histórico de viagens serve como insumo para recompensas, relatórios e recargas. |
    | **História de Usuário** | [US30 - Histórico e recompensas](../modelagem_requisitos_02/historias_de_usuario.md#us30---histórico-e-recompensas) | Representação | A história define como o histórico será apresentado e usado para pontos/recompensas. |
    | **Casos de Uso** | [UC05 – Recarga de Cartão](../modelagem_requisitos_01/casos_de_uso.md#uc05---recarga-de-cartão) | Representação | UC05 e casos relacionados suportam registro e consulta de viagens. |
    | **Especificação Suplementar** | [Privacidade](../modelagem_requisitos_01/especificacao_suplementar.md#privacidade) | Responsabilidade | Guarda e uso do histórico devem seguir políticas de privacidade e LGPD. |
    | **Artefatos de Elicitação** | [Entrevista (ENT07)](../Elicitacao/elicitacao_entrevista.md#resultados), [Entrevista (ENT09)](../Elicitacao/elicitacao_entrevista.md#resultados) | Satisfação | ENT07/ENT09 indicam interesse por histórico e confiabilidade dos dados; privacidade exige consentimento. |

??? info "RF16 – Permitir reportar problemas (motorista, ônibus, cobrança) com dados do veículo e horário"

    *Autoria: Cauã Nicolas*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | [Épico 4: Avaliar e Reportar](../modelagem_requisitos_02/backlog.md#épico-4---avaliar-e-reportar) | Representação | O épico agrega funcionalidades de avaliação e reporte de problemas. |
    | **Especificação Suplementar** | [Usabilidade](../modelagem_requisitos_01/especificacao_suplementar.md#usabilidade) | Responsabilidade | Mensagens e relatórios de erro devem ser claros e acionáveis, conforme definição de usabilidade. |
    | **Artefatos de Elicitação** | [Entrevista (ENT09)](../Elicitacao/elicitacao_entrevista.md#resultados) | Satisfação | ENT09 identificou necessidade de feedback confiável e canais para reportar problemas. |

??? info "RF17 – Exibir preço da passagem por linha ou trajeto"

    *Autoria: Daniel Nunes Duarte*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | *Gerencial* | Representação | RF17 relaciona-se a funcionalidades de informação tarifária e gestão de tarifas. |
    | **História de Usuário** | *História de usuário planejada* | Representação | História de usuário futura com origem em BRS19. |
    | **Especificação Suplementar** | [Especificação Suplementar](../modelagem_requisitos_01/especificacao_suplementar.md) | Representação | Pode documentar regras tarifárias, políticas ou processamento de dados relacionados a tarifas. |
    | **Léxico** | *Não identificado* | — | — |
    | **Casos de Uso** | *Não identificados* | — | — |
    | **Cenários** | *Não identificados* | — | — |
    | **Artefatos de Elicitação** | [Brainstorm (BRS19)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Representação | BRS19 fundamenta a necessidade do RF17. |

??? info "RF18 – Listar linhas que passam em uma parada específica"

    *Autoria: João Ramos*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | [Épico 2: Filtragem](../modelagem_requisitos_02/backlog.md#épico-2---filtragem) | Representação | A listagem por parada é uma funcionalidade de filtragem e descoberta de linhas. |
    | **História de Usuário** | [US01](../modelagem_requisitos_02/historias_de_usuario.md#us01) | Representação | US01 representa a necessidade de consultar linhas por parada. |
    | **Léxico** | *Não identificado* | — | — |
    | **Casos de Uso** | [UC02](../modelagem_requisitos_01/casos_de_uso.md#uc02) | Representação | UC02 modela a busca e consulta de linhas com base em critérios como parada. |
    | **Cenários** | [CEN01](../modelagem_requisitos_01/cenarios.md#cen01) | Representação | CEN01 descreve usuário consultando linhas que passam em uma parada. |
    | **Artefatos de Elicitação** | [Brainstorm (BRS05)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Representação | BRS05 fundamenta a necessidade de listagem por parada. |

??? info "RF19 – Disponibilizar versão web leve para acesso rápido em pontos de ônibus (via QR Code)"

    *Autoria: Gabriel Maciel*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | [Épico 3: Acessibilidade](../modelagem_requisitos_02/backlog.md#épico-3---acessibilidade) | Agregação | Épico 3 agrega e compõe o requisito RF19 como parte de sua estrutura |
    | **História de Usuário** | [US02 - Acesso web rápido via QR Code](../modelagem_requisitos_02/historias_de_usuario.md#us02---acesso-web-rápido-via-qr-code) | Representação | US02 representa a implementação detalhada do RF19 em termos de funcionalidade do usuário |
    | **Léxico** | *Não identificado* | — | — |
    | **Casos de Uso** | [UC07 - Modo off-line (Requisito não implementado)](../modelagem_requisitos_01/casos_de_uso.md#uc07---modo-off-line-requisito-não-implementado) | Representação | UC07 modela e representa o fluxo de interação para acessar a versão web via QR Code |
    | **Cenários** | [Cenário 5 - Modo off-line (Requisito não implementado)](../modelagem_requisitos_01/cenarios.md#cenário-5---modo-off-line-requisito-não-implementado) | Representação | Cenário 5 descreve uma situação concreta onde o RF19 é utilizado |
    | **Artefatos de Elicitação** | [Brainstorm (BRS17)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Representação | BRS17 fundamenta a necessidade do RF19 |

??? info "RF20 – Botão de pânico/emergência para alertar motorista e/ou autoridades"

    *Autoria: Daniel Nunes Duarte*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | *Ambiental* | Representação | RF20 atende necessidade de segurança imediata para usuários em risco. |
    | **História de Usuário** | *Não identificada* | — | — |
    | **Léxico** | *Não identificado* | — | — |
    | **Casos de Uso** | *Não identificados* | — | — |
    | **Artefatos de Elicitação** | [Brainstorm (BRS21)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Representação | BRS21 fundamenta a necessidade do mecanismo de alerta emergencial. |

??? info "RF21 – Mostrar alertas de trânsito, acidentes e rotas alternativas"

    *Autoria: João Ramos*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | [Épico 1: Rastreamento e Informações em Tempo Real](../modelagem_requisitos_02/backlog.md#épico-1---rastreamento-e-informações-em-tempo-real) | Representação | Alertas de tráfego complementam o rastreamento e planejamento em tempo real. |
    | **História de Usuário** | [US15](../modelagem_requisitos_02/historias_de_usuario.md#us15) | Representação | US15 contempla avisos e informações dinâmicas do sistema. |
    | **Léxico** | *Não identificado* | — | — |
    | **Casos de Uso** | [UC03](../modelagem_requisitos_01/casos_de_uso.md#uc03) | Representação | UC03 inclui o fluxo de recepção e exibição de alertas de trânsito. |
    | **Cenários** | [CEN03](../modelagem_requisitos_01/cenarios.md#cen03) | Representação | CEN03 exemplifica alertas e recomendações de rota alternativa. |
    | **Artefatos de Elicitação** | [Brainstorm (BRS12)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Representação | BRS12 sugere a necessidade de alertas de trânsito e alternativas de rota. |

??? info "RF22 – Permitir compartilhar trajeto em tempo real com outros usuários"

    *Autoria: Daniel Nunes Duarte*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | *Ambiental* | Representação | RF22 reforça segurança e colaboração entre usuários durante deslocamentos. |
    | **História de Usuário** | *Não identificada* | — | — |
    | **Léxico** | *Não identificado* | — | — |
    | **Casos de Uso** | *Não identificados* | — | — |
    | **Artefatos de Elicitação** | [Brainstorm (BRS20)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Representação | BRS20 fundamenta a necessidade do compartilhamento de trajeto. |

??? info "RF24 – Permitir favoritar linhas ou paradas para acesso rápido"

    *Autoria: Cauã Nicolas*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | [Épico 1: Rastreamento e Informações em Tempo Real](../modelagem_requisitos_02/backlog.md#épico-1---rastreamento-e-informações-em-tempo-real) | Representação | Favoritos melhoram eficiência de acesso a informações recorrentes. |
    | **História de Usuário** | [US22 - Favoritos](../modelagem_requisitos_02/historias_de_usuario.md#us22---permitir-favoritar-linhas-ou-paradas-para-acesso-rápido) | Representação | US22 descreve critérios de aceitação para favoritos. |
    | **Casos de Uso** | [UC05 – Recarga de Cartão](../modelagem_requisitos_01/casos_de_uso.md#uc05---recarga-de-cartão) | Representação | Casos de uso relacionados à personalização e às preferências do usuário. |
    | **Especificação Suplementar** | [Usabilidade](../modelagem_requisitos_01/especificacao_suplementar.md#usabilidade) | Responsabilidade | Personalização e persistência de preferências definidas na especificação. |
    | **Artefatos de Elicitação** | [Entrevista (ENT14)](../Elicitacao/elicitacao_entrevista.md#resultados) | Representação | ENT14 solicita explicitamente a funcionalidade de favoritos. |

??? info "RF25 – Ampliar a cobertura e exibir informações também em regiões afastadas do Distrito Federal"

    *Autoria: Cauã Nicolas*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | [Épico 1: Rastreamento e Informações em Tempo Real](../modelagem_requisitos_02/backlog.md#épico-1---rastreamento-e-informações-em-tempo-real) | Representação | Ampliação de cobertura impacta rastreamento e disponibilidade de dados. |
    | **Especificação Suplementar** | [Portabilidade/Compatibilidade](../modelagem_requisitos_01/especificacao_suplementar.md#portabilidadecompatibilidade) | Responsabilidade | Políticas de integração e suporte a ambientes com conectividade limitada são definidas na especificação. |
    | **Artefatos de Elicitação** | [Entrevista (ENT09)](../Elicitacao/elicitacao_entrevista.md#resultados) | Satisfação | ENT09 aponta a necessidade de cobertura e confiabilidade dos dados em diferentes regiões. |

??? info "RF26 – Filtrar ônibus por empresa operadora"

    *Autoria: Gabriel Maciel*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | [Épico 2: Filtragem](../modelagem_requisitos_02/backlog.md#épico-2---filtragem) | Agregação | Épico 2 agrega e compõe o requisito RF26 como parte de sua estrutura |
    | **História de Usuário** | [US01 - Filtrar ônibus por empresa operadora](../modelagem_requisitos_02/historias_de_usuario.md#us01---filtrar-ônibus-por-empresa-operadora) | Representação | US01 representa a implementação detalhada do RF26 em termos de funcionalidade do usuário |
    | **Léxico** | *Não identificado* | — | — |
    | **Casos de Uso** | *Não identificados* | — | — |
    | **Cenários** | *Não identificados* | — | — |
    | **Artefatos de Elicitação** | [Análise de Documentos (RF03)](../Elicitacao/elicitacao_analise_documentos.md#requisitos-funcionais) | Representação | RF03 fundamenta a necessidade do RF26 |

??? info "RF27 – Visualizar quais veículos estão em operação no momento"

    *Autoria: Daniel Nunes Duarte*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | *Organizacional* | Satisfação | Permite visão operacional em tempo real para planejamento e transparência |
    | **História de Usuário** | *Não identificada* | — | — |
    | **Léxico** | *Não identificado* | — | — |
    | **Casos de Uso** | *Não identificados* | — | — |
    | **Artefatos de Elicitação** | [Análise de Documentos (RNI04)](../Elicitacao/elicitacao_analise_documentos.md#requisitos-nao-implementados) | Satisfação | RNI04 documenta necessidade operacional; RF04 contribui para satisfazer RF27 |

??? info "RF28 – Permitir avaliação da qualidade do serviço de cada linha"

    *Autoria: Gabriel Maciel*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | [Épico 4: Avaliar e Reportar](../modelagem_requisitos_02/backlog.md#épico-4---avaliar-e-reportar) | Agregação | Épico 4 agrega e compõe o requisito RF28 como parte de sua estrutura |
    | **História de Usuário** | [US03 - Avaliar qualidade das linhas](../modelagem_requisitos_02/historias_de_usuario.md#us03---avaliar-qualidade-das-linhas) | Representação | US03 representa a implementação detalhada do RF28 em termos de funcionalidade do usuário |
    | **Léxico** | *Não identificado* | — | — |
    | **Casos de Uso** | [UC01 - Avaliação de Linhas de Ônibus (Requisito não implementado)](../modelagem_requisitos_01/casos_de_uso.md#uc01---avaliação-de-linhas-de-ônibus-requisito-não-implementado) | Representação | UC01 modela e representa o fluxo de interação para avaliar a qualidade do serviço |
    | **Cenários** | [Cenário 2 - Avaliar linhas (Requisito não implementado)](../modelagem_requisitos_01/cenarios.md#cenário-2---avaliar-linhas-requisito-não-implementado) | Representação | Cenário 2 descreve uma situação concreta onde o RF28 é utilizado |
    | **Artefatos de Elicitação** | [Análise de Documentos (RNI04)](../Elicitacao/elicitacao_analise_documentos.md#requisitos-nao-implementados) | Representação | RNI04 fundamenta a necessidade do RF28 |

??? info "RF29 – Sistema de gamificação para incentivar uso do transporte público"

    *Autoria: Daniel Nunes Duarte*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | *Desenvolvimento* | Agregação | Gamificação agrega incentivos para aumentar uso do transporte público e engajamento |
    | **História de Usuário** | *Não identificada* | — | — |
    | **Léxico** | *Não identificado* | — | — |
    | **Casos de Uso** | *Não identificados* | — | — |
    | **Artefatos de Elicitação** | [Brainstorm (BRS01)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Agregação | BRS01 agrega ideias de mecânicas de gamificação aplicáveis ao sistema |

??? info "RF30 – Previsão inteligente de horários baseada em dados históricos e machine learning"

    *Autoria: João Gabriel*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | [Épico 7: Planejamento de Viagens](../modelagem_requisitos_02/backlog.md#épico-7---planejamento-de-viagens) | Agregação | Agrega RF30 como funcionalidade inteligente do épico |
    | **História de Usuário** | [US31](../modelagem_requisitos_02/historias_de_usuario.md#us31) | Representação | US31 representa a implementação do RF30 em termos de usuário |
    | **Léxico** | *Não identificado* | — | — |
    | **Casos de Uso** | [UC10](../modelagem_requisitos_01/casos_de_uso.md#uc10) | Representação | UC10 modela a interação para previsão inteligente |
    | **Cenários** | [CEN10](../modelagem_requisitos_01/cenarios.md#cen10) | Representação | CEN10 descreve situação de uso do RF30 |
    | **Artefatos de Elicitação** | [Brainstorm (BRS02)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Representação | BRS02 representa a necessidade do RF30 |

??? info "RF31 – Sistema de recompensas por uso sustentável do transporte público"

    *Autoria: Fernanda Vaz*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | [Épico 11: Gamificação e Engajamento](../modelagem_requisitos_02/backlog.md#épico-11---gamificação-e-engajamento) | Satisfação | O épico busca satisfazer objetivos de incentivo ao transporte sustentável |
    | **História de Usuário** | [US38 - Sistema de Gamificação para Incentivar o Uso do Transporte Público](../modelagem_requisitos_02/historias_de_usuario.md#us38---sistema-de-gamificação-para-incentivar-o-uso-do-transporte-público) | Representação | US31 descreve a funcionalidade de recompensas ao usuário |
    | **Casos de Uso** | *Não identificados* | — | — |
    | **Cenários** | *Não identificados* | — | — |
    | **Artefatos de Elicitação** | [BRS09](../Elicitacao/elicitacao_brainstorm.md#resultados) | Satisfação | O requisito satisfaz os objetivos organizacionais de sustentabilidade |

??? info "RF32 – Exibir relatórios de impacto ambiental (CO₂ economizado)"

    *Autoria: Fernanda Vaz*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | [Épico 9: Sustentabilidade e Impacto Ambiental](../modelagem_requisitos_02/backlog.md#épico-9---sustentabilidade-e-impacto-ambiental) | Recurso | O épico utiliza este requisito como recurso para mensurar impacto |
    | **História de Usuário** | [US10 - Exibir Relatórios de Impacto Ambiental (CO₂ Economizado)](../modelagem_requisitos_02/historias_de_usuario.md#us10---exibir-relatórios-de-impacto-ambiental-co₂-economizado) | Representação | US32 detalha o relatório de impacto ambiental |
    | **Casos de Uso** | *Não identificados* | — | — |
    | **Cenários** | *Não identificados* | — | — |
    | **Artefatos de Elicitação** | [BRS11](../Elicitacao/elicitacao_brainstorm.md#resultados) | Recurso | O requisito serve de recurso para avaliação ambiental e organizacional |

??? info "RF33 – Suporte a comandos de voz para facilitar interação durante deslocamentos"

    *Autoria: Daniel Nunes Duarte*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | *Ambiental* | Representação | RF33 melhora usabilidade e segurança permitindo interação sem tocar o dispositivo |
    | **História de Usuário** | *Não identificada* | — | — |
    | **Léxico** | *Não identificado* | — | — |
    | **Casos de Uso** | *Não identificados* | — | — |
    | **Artefatos de Elicitação** | [Brainstorm (BRS14)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Representação | BRS14 identifica necessidade de comandos de voz para uso durante deslocamentos |

??? info "RF34 – Integração com assistentes virtuais (Alexa, Google Assistant)"

    *Autoria: Gabriel Maciel*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | [Épico 3: Acessibilidade](../modelagem_requisitos_02/backlog.md#épico-3---acessibilidade) | Agregação | Épico 3 agrega e compõe o requisito RF34 como parte de sua estrutura |
    | **História de Usuário** | [US20 - Integração com assistentes virtuais](../modelagem_requisitos_02/historias_de_usuario.md#us20---integração-com-assistentes-virtuais) | Representação | US20 representa a implementação detalhada do RF34 em termos de funcionalidade do usuário |
    | **Léxico** | *Não identificado* | — | — |
    | **Casos de Uso** | *Não identificados* | — | — |
    | **Cenários** | *Não identificados* | — | — |
    | **Artefatos de Elicitação** | [Brainstorm (BRS16)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Representação | BRS16 fundamenta a necessidade do RF34 |

??? info "RF35 – Permitir rastreamento de múltiplas linhas de ônibus simultaneamente no mapa"

    *Autoria: Gabriel Maciel*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | [Épico 1: Rastreamento e Informações em Tempo Real](../modelagem_requisitos_02/backlog.md#épico-1---rastreamento-e-informações-em-tempo-real) | Agregação | Épico 1 agrega e compõe o requisito RF35 como parte de sua estrutura |
    | **História de Usuário** | [US04 - Rastrear múltiplas linhas simultaneamente](../modelagem_requisitos_02/historias_de_usuario.md#us04---rastrear-múltiplas-linhas-simultaneamente) | Representação | US04 representa a implementação detalhada do RF35 em termos de funcionalidade do usuário |
    | **Léxico** | *Não identificado* | — | — |
    | **Casos de Uso** | [UC03 - Rastreamento de Ônibus](../modelagem_requisitos_01/casos_de_uso.md#uc03---rastreamento-de-ônibus) | Representação | UC03 modela e representa o fluxo de interação para rastrear múltiplas linhas |
    | **Cenários** | [Cenário 3 - Rastreamento de múltiplas linhas (Requisito não implementado)](../modelagem_requisitos_01/cenarios.md#cenário-3---rastreamento-de-múltiplas-linhas-requisito-não-implementado) | Representação | Cenário 3 descreve uma situação concreta onde o RF35 é utilizado |
    | **Artefatos de Elicitação** | [Entrevista (ENT12)](../Elicitacao/elicitacao_entrevista.md#resultados) | Representação | ENT12 fundamenta a necessidade do RF35 |

??? info "RF36 – Oferecer suporte multilíngue (português e inglês, no mínimo)"

    *Autoria: Gabriel Maciel*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | [Épico 16: Suporte Multilíngue](../modelagem_requisitos_02/backlog.md#épico-16---suporte-multilíngue) | Agregação | Épico 16 agrega e compõe o requisito RF36 como parte de sua estrutura |
    | **História de Usuário** | [US21 - Suporte multilíngue](../modelagem_requisitos_02/historias_de_usuario.md#us21---suporte-multilíngue) | Representação | US21 representa a implementação detalhada do RF36 em termos de funcionalidade do usuário |
    | **Léxico** | *Não identificado* | — | — |
    | **Casos de Uso** | *Não identificados* | — | — |
    | **Cenários** | *Não identificados* | — | — |
    | **Artefatos de Elicitação** | [Entrevista (ENT22)](../Elicitacao/elicitacao_entrevista.md#resultados) | Representação | ENT22 fundamenta a necessidade do RF36 |

??? info "RF37 – Permitir cadastro, login e autenticação de usuários no sistema"

    *Autoria: João Gabriel*

    | **Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-------------|:---------------------------|:----------------|:------------------|
    | **Épico** | [Épico 8: Gestão de Usuário e Conta](../modelagem_requisitos_02/backlog.md#épico-8---gestão-de-usuário-e-conta) | Agregação | Agrega RF37 como funcionalidade central do épico |
    | **História de Usuário** | [US32](../modelagem_requisitos_02/historias_de_usuario.md#us32) | Representação | US32 representa a implementação do RF37 em termos de usuário |
    | **Léxico** | *Não identificado* | — | — |
    | **Casos de Uso** | [UC01](../modelagem_requisitos_01/casos_de_uso.md#uc01) | Representação | UC01 modela a interação para cadastro e autenticação |
    | **Cenários** | *Não identificados* | — | — |
    | **Artefatos de Elicitação** | [Brainstorm (BRS18)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Representação | BRS18 representa a necessidade do RF37 |

---

## Bibliográfia

> <a id="ref-1"></a>TORANZO, M.; CASTRO, J; MELLO, E. Uma proposta para melhorar o rastreamento de requisitos. PUC-Rio: Workshop em Engenharia de Requisitos, Rio de Janeiro, 2002. Disponível em: http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/toranzo.pdf. Acesso em: 28 de Out de 2025.

---

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|:------:|:----:|:----------|:----------|:-----------|
| 1.0 | 25/10 | Criação inicial do documento | Gabriel Maciel | Fernanda Vaz |
| 1.1 | 26/10 | Adição RNF1 - RNF3 e RF01 - RF05, RF37, RF30 | João Gabriel | Gabriel Maciel |
| 1.2 | 26/10 | Adição RF9 ao RF12 e RF18 e RF21; RNF09 e RNF12 | João Ramos | Cauã Nicolas |
| 1.3 | 28/10 | Preenchimento das classificações de fonte e tipos de elo para os requisitos RF19, RF26, RF28, RF34, RF35, RF36, RNF10, RNF11 | Gabriel Maciel | João Ramos |
| 1.4 | 28/10 | Adição RNF04, RNF05, RF13, RF14, RF15, RF16, RF24, RF25 | Cauã Nicolas | João Ramos |
| 1.5 | 28/10 | Adição RF17, RF20, RF22, RF27, RF29, RF33, RNF14, RNF15 | Daniel Nunes Duarte | Fernanda Vaz |

---

## Agradecimentos

Agradecemos o suporte da ferramenta de Inteligência Artificial Generativa Google Gemini no desenvolvimento deste trabalho. Em conformidade com o Código de Conduta da Sociedade Brasileira de Computação (SBC), declaramos que a ferramenta foi utilizada como auxílio na revisão gramatical e estilística do texto, na sugestão de estrutura para seções específicas do artigo, bem como na formatação de tabelas e na descrição de figuras. Ressaltamos que os autores assumem total responsabilidade por todo o conteúdo apresentado, incluindo sua originalidade e precisão. A ferramenta não figura como autora desta publicação.
