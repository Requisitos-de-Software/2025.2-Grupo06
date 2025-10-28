# Backward-From

## Introdução

Este documento trata da "rastreabilidade para trás" (*backward-from*). Isso significa simplesmente rastrear cada requisito de volta à sua fonte. É o processo de conectar cada "o quê" (o requisito) ao seu "porquê" (a fonte que o solicitou).

---

## Metodologia

A metodologia aplicada baseia-se na análise dos artefatos de requisitos funcionais e não funcionais, associando cada requisito identificado ao documento de origem ou evidência. Essa abordagem busca manter a rastreabilidade bidirecional — tanto *forward-to* quanto *backward-from* —, conforme proposto por Sayão e Leite (2005).

Toranzo propõe que as informações que compõem o rastro de requisitos sejam organizadas em quatro níveis distintos. Esta classificação visa estruturar o contexto no qual o sistema está inserido e os artefatos gerados, garantindo que o rastreamento abarque tanto o ambiente externo quanto os detalhes internos do desenvolvimento (SAYÃO; LEITE, 2005; TORANZO et al., 2002).

Os quatro níveis de classificação são:

1. **Ambiental**: Engloba as informações que têm origem no contexto ambiental mais amplo onde a organização está inserida e que podem impactar o sistema em desenvolvimento.
2. **Organizacional**: Reúne informações pertencentes à própria organização, tais como sua missão, objetivos e estratégias, que influenciam os requisitos do sistema.
3. **Gerencial**: Agrega as informações cruciais para a gerência do projeto, auxiliando na associação de tarefas aos requisitos.
4. **Desenvolvimento**: Envolve as informações associadas aos artefatos gerados ao longo do processo de desenvolvimento, incluindo documentos de requisitos, diagramas, códigos, e casos de teste.

Ao enfatizar os níveis ambiental, organizacional e gerencial, Toranzo confere uma atenção especial aos aspectos gerenciais e contextuais do projeto, o que é visto como uma contribuição importante de sua proposta.

O meta-modelo de Toranzo estabelece um conjunto de elos de rastreabilidade que definem os tipos de relacionamentos entre os elementos rastreados. A seguir, apresentam-se os principais elos:

1. **Satisfação**: Indica que a classe de origem possui uma dependência de satisfação com a classe de destino.
2. **Recurso**: 	
A classe de origem demonstra dependência de recurso em relação à classe de destino.
3. **Responsabilidade**: 	
Registra a participação, a responsabilidade e a ação de pessoas sobre os artefatos do projeto.
4. **Representação**: Captura como os requisitos ou outros elementos são modelados ou representados em diferentes linguagens.
5. **Alocado**: 	
A classe de origem está relacionada a uma classe de destino que geralmente representa um subsistema.
6. **Agregação**: 	
Indica a composição de elementos, ou seja, que um elemento é composto por outros.

---

## Tabela de Rastreabilidade Backward-From

A tabela de rastreabilidade backward-from, apresentada neste documento, operacionaliza estes quatro níveis de Toranzo ao mapear cada requisito de volta às suas fontes de origem. Cada linha da tabela representa um requisito do sistema (nível Desenvolvimento) e seus relacionamentos com informações dos níveis Ambiental (contexto externo, stakeholders), Organizacional (objetivos do negócio) e Gerencial (pessoas responsáveis, tarefas associadas). Por meio dos elos de rastreabilidade (Satisfação, Recurso, Responsabilidade, Representação, Alocado e Agregação), estabelece-se um mapeamento explícito que permite identificar não apenas "o quê" foi requisitado, mas também "por quê" foi requisitado e "quem" está envolvido em sua execução. Desta forma, a tabela funciona como um artefato central que documenta e valida a rastreabilidade bidirecional entre requisitos e suas origens, garantindo conformidade com os princípios propostos por Toranzo e Sayão & Leite.

### Legendas

- RF: Requisito Funcional
- RNF: Requisito Não Funcional
- ENT: Entrevista
- RNI: Requisitos Não Implementados

| ID do Requisito | Descrição do Requisito | Fonte/Origem | Classificação da Fonte | Tipo de Elo | Autoria |
|-----------------|------------------------|--------------|------------------------|-------------|---------|
| RF01 | Exibir a localização dos ônibus em tempo real no mapa | | | | João Gabriel |
| RF02 | Mostrar o tempo estimado de chegada do ônibus à parada | | | | João Gabriel |
| RF03 | Permitir planejamento de viagem (origem → destino) com rotas sugeridas | | | | João Gabriel |
| RF04 | Permitir pesquisa por linhas e rotas de ônibus | | | | João Gabriel |
| RF05 | Apresentar horários de saída e chegada dos transportes | | | | João Gabriel |
| RF06 | Oferecer um mapa interativo com os pontos de ônibus e suas linhas correspondentes | | | | Fernanda Vaz |
| RF07 | Integrar informações de outros modais (metrô, outros ônibus) em rotas multimodais | | | | Fernanda Vaz |
| RF08 | Exibir informações de acessibilidade do ônibus (ex.: acessível para cadeirantes) | | | | Fernanda Vaz |
| RF09 | Indicar lotação do ônibus (vazio, moderado, lotado) | | | | João Lucas |
| RF10 | Permitir que usuários reportem a lotação do ônibus (sistema colaborativo) | | | | João Lucas |
| RF11 | Enviar notificação quando o ônibus estiver a X minutos da parada | | | | João Lucas |
| RF12 | Enviar alertas sobre atrasos, mudanças de rota ou alterações nos horários | | | | João Lucas |
| RF13 | Oferecer recarga de cartão de transporte (ex.: integração com BRB Mobilidade) | | | | Cauã Nicolas |
| RF14 | Permitir integração com o cartão de transporte, incluindo saldo e recarga | | | | Cauã Nicolas |
| RF15 | Manter histórico de viagens do usuário | | | | Cauã Nicolas |
| RF16 | Permitir reportar problemas (motorista, ônibus, cobrança) com dados do veículo e horário | | | | Cauã Nicolas |
| RF17 | Exibir preço da passagem por linha ou trajeto | | | | Daniel Nunes Duarte |
| RF18 | Listar linhas que passam em uma parada específica | | | | João Lucas |
| RF19 | Disponibilizar versão web leve para acesso rápido em pontos de ônibus (via QR Code) | | | | Gabriel Maciel |
| RF20 | Botão de pânico/emergência para alertar motorista e/ou autoridades | | | | Daniel Nunes Duarte |
| RF21 | Mostrar alertas de trânsito, acidentes e rotas alternativas | | | | João Lucas |
| RF22 | Permitir compartilhar trajeto em tempo real com outros usuários | | | | Daniel Nunes Duarte |
| RF23 | Exibir quantidade de assentos preferenciais e totais no ônibus | | | | |
| RF24 | Permitir favoritar linhas ou paradas para acesso rápido | | | | Cauã Nicolas |
| RF25 | Ampliar a cobertura e exibir informações também em regiões afastadas do Distrito Federal | | | | Cauã Nicolas |
| RF26 | Filtrar ônibus por empresa operadora | | | | Gabriel Maciel |
| RF27 | Visualizar quais veículos estão em operação no momento | | | | Daniel Nunes Duarte |
| RF28 | Permitir avaliação da qualidade do serviço de cada linha | | | | Gabriel Maciel |
| RF29 | Sistema de gamificação para incentivar uso do transporte público | | | | Daniel Nunes Duarte |
| RF30 | Previsão inteligente de horários baseada em dados históricos e machine learning | | | | João Gabriel |
| RF31 | Sistema de recompensas por uso sustentável do transporte público | | | | Fernanda Vaz |
| RF32 | Exibir relatórios de impacto ambiental (CO₂ economizado) | | | | Fernanda Vaz |
| RF33 | Suporte a comandos de voz para facilitar interação durante deslocamentos | | | | Daniel Nunes Duarte |
| RF34 | Integração com assistentes virtuais (Alexa, Google Assistant) | | | | Gabriel Maciel |
| RF35 | Permitir rastreamento de múltiplas linhas de ônibus simultaneamente no mapa | | | | Gabriel Maciel |
| RF36 | Oferecer suporte multilíngue (português e inglês, no mínimo) | | | | Gabriel Maciel |
| RF37 | Permitir cadastro, login e autenticação de usuários no sistema | | | | João Gabriel |
| RNF01 | As informações de horários e localização dos ônibus devem ser precisas | | | | João Gabriel |
| RNF02 | Rastreamento dos ônibus em tempo real deve ser confiável e sem falhas | | | | João Gabriel |
| RNF03 | Tempo de atualização da localização ≤ 20 segundos | | | | João Gabriel |
| RNF04 | Interface acessível para idosos e pessoas com deficiência visual | | | | Cauã Nicolas |
| RNF05 | Sistema de notificação com som e vibração configuráveis | | | | Cauã Nicolas |
| RNF06 | Baixo consumo de bateria e dados móveis | | | | Fernanda Vaz |
| RNF07 | Compatibilidade com dispositivos Android e iOS | | | | Fernanda Vaz |
| RNF08 | Proteção contra reportes falsos de lotação (mecanismo de confiança) | | | | |
| RNF09 | Dados de localização e pessoais protegidos conforme LGPD | | | | |
| RNF10 | Tempo de carregamento da tela principal < 3 segundos | | | | Gabriel Maciel |
| RNF11 | Funcionamento offline para consulta a rotas salvas e horários | | | | Gabriel Maciel |
| RNF12 | Integração segura com sistemas de pagamento (recarga de cartão) | | | | João Lucas |
| RNF13 | Alta disponibilidade do sistema (≥ 98% uptime) | | | | João Lucas |
| RNF14 | Suporte a múltiplos usuários simultâneos sem lentidão | | | | Daniel Nunes Duarte |
| RNF15 | Personalização da interface com base em preferências do usuário | | | | Daniel Nunes Duarte |

## Elos Funcionais (deprecated)

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

## Elos Não Funcionais (deprecated)

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

> Agradecemos o suporte da ferramenta de Inteligência Artificial Generativa **Google Gemini** no desenvolvimento deste trabalho.  
Em conformidade com o Código de Conduta da Sociedade Brasileira de Computação (SBC), declaramos que a ferramenta foi utilizada como auxílio na revisão gramatical e estilística do texto, na sugestão de estrutura para seções específicas do artigo, bem como na formatação de tabelas e na descrição de figuras.  
Ressaltamos que os autores assumem total responsabilidade por todo o conteúdo apresentado, incluindo sua originalidade e precisão.  
A ferramenta não figura como autora desta publicação.

