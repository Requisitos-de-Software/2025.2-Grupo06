# Backward-From

## Introdução

Este documento trata da "rastreabilidade para trás" (*backward-from*). Isso significa simplesmente rastrear cada requisito de volta à sua fonte. É o processo de conectar cada "o quê" (o requisito) ao seu "porquê" (a fonte que o solicitou).

---

## Metodologia

A metodologia aplicada baseia-se na análise dos artefatos de requisitos funcionais e não funcionais, associando cada requisito identificado ao documento de origem ou evidência. Essa abordagem busca manter a rastreabilidade bidirecional — tanto *forward-to* quanto *backward-from* —, conforme proposto por Sayão e Leite (2005).

### Legendas

- RF: Requisito Funcional
- RNF: Requisito Não Funcional
- EF: Elos Funcionais
- ENF: Elos Não Funcionais
- ENT: Entrevista
- EP: Épicos
- RNI: Requisitos Não Implementados

---
## Requisitos Funcionais

| **ID** | **Requisito** | **Categoria** | **Descrição** | **Fonte** |
|:------:|:---------------|:--------------|:---------------|:-----------|
| **01** | **RF01** | Funcional | Exibir a localização dos ônibus em tempo real no mapa | Elicitação de Requisitos: Análise de Documentos (RF01), Entrevista (ENT03) |
| **02** | **RF02** | Funcional | 	Mostrar o tempo estimado de chegada do ônibus à parada | Elicitação de Requisitos: Entrevista (ENT04) |
| **03** | **RF03** | Funcional | Permitir planejamento de viagem (origem → destino) com rotas sugeridas | Elicitação de Requisitos: Análise de Documentos (RF05) |
| **04** | **RF04** | Funcional | Permitir pesquisa por linhas e rotas de ônibus | Elicitação de Requisitos: Análise de Documentos (RF02), Entrevista (ENT01) |
| **05** | **RF05** | Funcional | Apresentar horários de saída e chegada dos transportes | Elicitação de Requisitos: Entrevista (ENT02) |
| **06** | **RF06** | Funcional | Oferecer um mapa interativo com os pontos de ônibus e suas linhas correspondentes | Elicitação de Requisitos: Entrevista (ENT06) |
| **07** | **RF07** | Funcional | Integrar informações de outros modais (metrô, outros ônibus) em rotas multimodais | Elicitação de Requisitos: Análise de Documentos (RNI02), Brainstorm (BRS04) |
| **08** | **RF08** | Funcional | Exibir informações de acessibilidade do ônibus (ex.: acessível para cadeirantes) | Elicitação de Requisitos: Entrevista (ENT16) |
| **09** | **RF09** | Funcional | Indicar lotação do ônibus (vazio, moderado, lotado) | Elicitação de Requisitos: Entrevista (ENT11), Brainstorm (BRS07) |
| **10** | **RF10** | Funcional | Permitir que usuários reportem a lotação do ônibus (sistema colaborativo) | Elicitação de Requisitos: Entrevista (ENT11), Brainstorm (BRS03) |
| **11** | **RF11** | Funcional | Enviar notificação quando o ônibus estiver a X minutos da parada | Elicitação de Requisitos: Análise de Documentos (RNI01), Entrevista (ENT15), Brainstorm (BRS05) |
| **12** | **RF12** | Funcional | Enviar alertas sobre atrasos, mudanças de rota ou alterações nos horários | Elicitação de Requisitos: Entrevista (ENT05), Brainstorm (BRS05) |
| **13** | **RF13** | Funcional | Oferecer recarga de cartão de transporte (ex.: integração com BRB Mobilidade) | Elicitação de Requisitos: Entrevista (ENT07) |
| **14** | **RF14** | Funcional | Permitir integração com o cartão de transporte, incluindo saldo e recarga | Elicitação de Requisitos: Entrevista (ENT07) |
| **15** | **RF15** | Funcional | Manter histórico de viagens do usuário | Elicitação de Requisitos: Análise de Documentos (RNI03) |
| **16** | **RF16** | Funcional | Permitir reportar problemas (motorista, ônibus, cobrança) com dados do veículo e horário | Elicitação de Requisitos: Entrevista (ENT20) |
| **17** | **RF17** | Funcional | Exibir preço da passagem por linha ou trajeto |  |
| **18** | **RF18** | Funcional | Listar linhas que passam em uma parada específica |  |
| **19** | **RF19** | Funcional | Disponibilizar versão web leve para acesso rápido em pontos de ônibus (via QR Code) | Elicitação de Requisitos: Brainstorm (BRS17) |
| **20** | **RF20** | Funcional | Botão de pânico/emergência para alertar motorista e/ou autoridades |  |
| **21** | **RF21** | Funcional | Mostrar alertas de trânsito, acidentes e rotas alternativas | Elicitação de Requisitos: Brainstorm (BRS12) |
| **22** | **RF22** | Funcional | Permitir compartilhar trajeto em tempo real com outros usuários |  |
| **23** | **RF23** | Funcional | Exibir quantidade de assentos preferenciais e totais no ônibus |  |
| **24** | **RF24** | Funcional | Permitir favoritar linhas ou paradas para acesso rápido | Elicitação de Requisitos: Entrevista (ENT14) |
| **25** | **RF25** | Funcional | Ampliar a cobertura e exibir informações também em regiões afastadas do Distrito Federal | Elicitação de Requisitos: Entrevista (ENT08) |
| **26** | **RF26** | Funcional | Filtrar ônibus por empresa operadora | Elicitação de Requisitos: Análise de Documentos (RF03) |
| **27** | **RF27** | Funcional | Visualizar quais veículos estão em operação no momento | Elicitação de Requisitos: Análise de Documentos (RF04) |
| **28** | **RF28** | Funcional | Permitir avaliação da qualidade do serviço de cada linha | Elicitação de Requisitos: Análise de Documentos (RNI04) |
| **29** | **RF29** | Funcional | Sistema de gamificação para incentivar uso do transporte público | Elicitação de Requisitos: Brainstorm (BRS01) |
| **30** | **RF30** | Funcional | Previsão inteligente de horários baseada em dados históricos e machine learning | Elicitação de Requisitos: Brainstorm (BRS02) |
| **31** | **RF31** | Funcional | Sistema de recompensas por uso sustentável do transporte público | Elicitação de Requisitos: Brainstorm (BRS09) |
| **32** | **RF32** | Funcional | Exibir relatórios de impacto ambiental (CO₂ economizado) | Elicitação de Requisitos: Brainstorm (BRS11) |


---

## Requisitos Não Funcionais

| **ID** | **Requisito** | **Categoria** | **Descrição** | **Fonte** |
|:------:|:---------------|:--------------|:---------------|:-----------|
| **01** | **RNF01** | Não Funcional | As informações de horários e localização dos ônibus devem ser precisas. | Elicitação de Requisitos: Entrevista (ENT09) |
| **02** | **RNF02** | Não Funcional | Rastreamento dos ônibus em tempo real deve ser confiável e sem falhas. | Elicitação de Requisitos: Entrevista (ENT13) |
| **03** | **RNF03** | Não Funcional | Tempo de atualização da localização ≤ 20 segundos. | |
| **04** | **RNF04** | Não Funcional | Interface acessível para idosos e pessoas com deficiência visual. | Elicitação de Requisitos: Entrevista (ENT10), Brainstorm (BRS08) |
| **05** | **RNF05** | Não Funcional | Sistema de notificação com som e vibração configuráveis. | Elicitação de Requisitos: Brainstorm (BRS18) |
| **06** | **RNF06** | Não Funcional | Baixo consumo de bateria e dados móveis. | Análise de Documentos |
| **07** | **RNF07** | Não Funcional | Compatibilidade com dispositivos Android e iOS. | Elicitação de Requisitos: Entrevista (ENT19) |
| **08** | **RNF08** | Não Funcional | Proteção contra reportes falsos de lotação (mecanismo de confiança). | |
| **09** | **RNF09** | Não Funcional | Dados de localização e pessoais protegidos conforme LGPD. | Elicitação de Requisitos: Entrevista (ENT21) |
| **10** | **RNF10** | Não Funcional | Tempo de carregamento da tela principal < 3 segundos. | Elicitação de Requisitos: Entrevista (ENT17) |
| **11** | **RNF11** | Não Funcional | Funcionamento offline para consulta a rotas salvas e horários. | Elicitação de Requisitos: Análise de Documentos (RNI05), Entrevista (ENT18), Brainstorm (BRS06) |
| **12** | **RNF12** | Não Funcional | Integração segura com sistemas de pagamento (recarga de cartão). | Elicitação de Requisitos: Brainstorm (BRS10) |
| **13** | **RNF13** | Não Funcional | Alta disponibilidade do sistema (≥ 98% uptime). | |
| **14** | **RNF14** | Não Funcional | Suporte a múltiplos usuários simultâneos sem lentidão. | Elicitação de Requisitos: Brainstorm (BRS15) |
| **15** | **RNF15** | Não Funcional | Personalização da interface com base em preferências do usuário (tema, acessibilidade). | Elicitação de Requisitos: Brainstorm (BRS13) |

## Elos Funcionais

### EF01
*Autoria: Cauã Nicolas, 2025*

- **Categoria:** Desenvolvimento
- **Elementos Rastreáveis:**
    - **RF13:**
        - Elicitação de Requisitos: Entrevista (ENT07)
- **Elos:**
    - Representação: ENT07 representa RF13
    - Agregação: EP05 agrega RF13
    - Agregação: EP08 agrega RF13

---

### EF02
*Autoria: Cauã Nicolas, 2025*

- **Categoria:** Desenvolvimento
- **Elementos Rastreáveis:**
    - **RF14:**
        - Elicitação de Requisitos: Entrevista (ENT07)
- **Elos:**
    - Representação: ENT07 representa RF14
    - Agregação: EP08 agrega RF14

---

### EF03
*Autoria: Cauã Nicolas, 2025*

- **Categoria:** Desenvolvimento
- **Elementos Rastreáveis:**
    - **RF15:**
        - Elicitação de Requisitos: Análise de Documentos (RNI03)
- **Elos:**
    - Representação: RNI03 representa RF15
    - Agregação: EP07 agrega RF15

---

### EF04
*Autoria: Cauã Nicolas, 2025*

- **Categoria:** Desenvolvimento
- **Elementos Rastreáveis:**
    - **RF16:**
        - Elicitação de Requisitos: Entrevista (ENT20)
- **Elos:**
    - Representação: ENT20 representa RF16
    - Agregação: EP08 agrega RF16

---

### EF05
*Autoria: Cauã Nicolas, 2025*

- **Categoria:** Desenvolvimento
- **Elementos Rastreáveis:**
    - **RF24:**
        - Elicitação de Requisitos: Entrevista (ENT14)
- **Elos:**
    - Representação: ENT14 representa RF24
    - Agregação: EP02 agrega RF24

---   

### EF06
*Autoria: Cauã Nicolas, 2025*

- **Categoria:** Desenvolvimento
- **Elementos Rastreáveis:**
    - **RF25:**
        - Elicitação de Requisitos: Entrevista (ENT08)
- **Elos:**
    - Representação: ENT08 representa RF25

---

## Elos Não Funcionais

### ENF01
*Autoria: Cauã Nicolas, 2025*

- **Categoria:** Desenvolvimento
- **Elementos Rastreáveis:**
    - **RNF04:**
        - Elicitação de Requisitos: Entrevista (ENT10), Brainstorm (BRS08)
- **Elos:** Agrega SIG-U03
    
---

### ENF02
*Autoria: Cauã Nicolas, 2025*

- **Categoria:** Desenvolvimento
- **Elementos Rastreáveis:**
    - **RNF05:**
        - Elicitação de Requisitos: Brainstorm (BRS18)
- **Elos:**
    - Agregação: RNF05 agrega SIG-U04
    - Agregação: EP06 agrega RNF05

---

## Tabela de Contribuição

|        Nome          | Contribuição|
|----------------------|-------------|
| Cauã Nicolas         | A preencher |
| Daniel Nunes Duarte  | A preencher |
| Fernanda Vaz         | A preencher |
| Gabriel Maciel       | A preencher |
| João Gabriel         | A preencher |
| João Ramos           | A preencher |


## Referência bibliográfica 

<a id="ref-1"></a>
> <sup>1.</sup>
> SAYÃO, M.; LEITE, J. C. S. P. *Rastreabilidade em Requisitos de Software*. In: **Anais do Simpósio Brasileiro de Engenharia de Software (SBES)**, 2005.

<a id="ref-2"></a>
> <sup>2.</sup>
> TORANZO, M.; CASTRO, J; MELLO, E. Uma proposta para melhorar o rastreamento de requisitos. PUC-Rio: Workshop em Engenharia de Requisitos, Rio de Janeiro, 2002. Disponível em: http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/toranzo.pdf. Acesso em: 28 de Out de 2025.

---

## Histórico de Versões

| **Versão** | **Data** | **Descrição** | **Autor(es)** | **Revisor(es)** |
|:----------:|:--------:|:--------------|:--------------|:----------------|
| **1.0** | 25/10 | Criação inicial do documento | Gabriel Maciel | Cauã Nicolas |
| **1.1** | 27/10 | Adição e elaboração de artefatos | Fernanda Vaz | Cauã Nicolas |
| **1.2** | 27/10 | Adição de Elos Funcionais (1, 2, 3, 4 e 5) e Elos Não Funcionais (1 e 2) | Cauã Nicolas | — |
| **1.3** | 28/10 | Adição Referência Bibliográfica | João Gabriel | Gabriel Maciel |

---

## Agradecimentos

>Agradecemos o suporte da ferramenta de Inteligência Artificial Generativa **Google Gemini** no desenvolvimento deste trabalho.  
>Em conformidade com o Código de Conduta da Sociedade Brasileira de Computação (SBC), declaramos que a ferramenta foi utilizada como auxílio na revisão gramatical e estilística do texto, na sugestão de estrutura para seções específicas do artigo, bem como na formatação de tabelas e na descrição de figuras.  
>Ressaltamos que os autores assumem total responsabilidade por todo o conteúdo apresentado, incluindo sua originalidade e precisão.  
>A ferramenta não figura como autora desta publicação.

