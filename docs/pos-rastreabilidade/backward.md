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
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF01">RF01</a> | Exibir a localização dos ônibus em tempo real no mapa | <a href="../Elicitacao/elicitacao_analise_documentos.md#requisitos-funcionais">Análise de Documentos (RF01)</a>, <a href="../Elicitacao/elicitacao_entrevista.md#resultados">Entrevista (ENT03)</a> | Ambiental | Agregação (Agrega dados do Análise de Documentos (RF01) e ENT03) | João Gabriel |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF02">RF02</a> | Mostrar o tempo estimado de chegada do ônibus à parada | <a href="../Elicitacao/elicitacao_entrevista.md#resultados">Entrevista (ENT04)</a> | Ambiental | Representação (ENT04 representa RF02) | João Gabriel |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF03">RF03</a> | Permitir planejamento de viagem (origem → destino) com rotas sugeridas | <a href="../Elicitacao/elicitacao_analise_documentos.md#requisitos-nao-implementados">Análise de Documentos (RNI02)</a> | Organizacional | Satisfação (RNI02 satisfaz RF03) | João Gabriel |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF04">RF04</a> | Permitir pesquisa por linhas e rotas de ônibus | <a href="../Elicitacao/elicitacao_analise_documentos.md#requisitos-funcionais">Análise de Documentos (RF02)</a>, <a href="../Elicitacao/elicitacao_entrevista.md#resultados">Entrevista (ENT01)</a> | Ambiental | Agregação (Agrega dados do Análise de Documentos (RF02) e ENT01) | João Gabriel |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF05">RF05</a> | Apresentar horários de saída e chegada dos transportes | <a href="../Elicitacao/elicitacao_entrevista.md#resultados">Entrevista (ENT02)</a> | Ambiental | Representação (ENT02 representa RF05) | João Gabriel |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF06">RF06</a> | Oferecer um mapa interativo com os pontos de ônibus e suas linhas correspondentes | <a href="../Elicitacao/elicitacao_entrevista.md#resultados">Entrevista (ENT06)</a> | Desenvolvimento|Representação (ENT06 representa RF06) | Fernanda Vaz |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF07">RF07</a> | Integrar informações de outros modais (metrô, outros ônibus) em rotas multimodais | <a href="../Elicitacao/elicitacao_brainstorm.md#resultados">Brainstorm (BBRS04)</a>, <a href="../Elicitacao/elicitacao_analise_documentos.md#requisitos-nao-implementados">Análise de Documentos (RNI02)</a> | Ambiental |Agregação (RF07 agrega dados de diferentes modais) | Fernanda Vaz |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF08">RF08</a> | Exibir informações de acessibilidade do ônibus (ex.: acessível para cadeirantes) | <a href="../Elicitacao/elicitacao_entrevista.md#resultados">Entrevista (ENT16)</a> |Ambiental |Satisfação (atende às normas de acessibilidade e necessidades do usuário) | Fernanda Vaz |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF09">RF09</a> | Indicar lotação do ônibus (vazio, moderado, lotado) | <a href="../Elicitacao/elicitacao_entrevista.md#resultados">Entrevista (ENT11)</a>, <a href="../Elicitacao/elicitacao_brainstorm.md#resultados">Brainstorm (BRS07)</a> | Ambiental | Representação | João Ramos |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF10">RF10</a> | Permitir que usuários reportem a lotação do ônibus (sistema colaborativo) | <a href="../Elicitacao/elicitacao_entrevista.md#resultados">Entrevista (ENT11)</a>, <a href="../Elicitacao/elicitacao_brainstorm.md#resultados">Brainstorm (BRS03)</a> | Ambiental | Representação | João Ramos |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF11">RF11</a> | Enviar notificação quando o ônibus estiver a X minutos da parada | <a href="../Elicitacao/elicitacao_analise_documentos.md#requisitos-nao-implementados">Análise de Documentos (RNI01)</a>, <a href="../Elicitacao/elicitacao_entrevista.md#resultados">Entrevista (ENT15)</a>, <a href="../Elicitacao/elicitacao_brainstorm.md#resultados">Brainstorm (BRS05)</a> | Ambiental | Representação | João Ramos |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF12">RF12</a> | Enviar alertas sobre atrasos, mudanças de rota ou alterações nos horários | <a href="../Elicitacao/elicitacao_entrevista.md#resultados">Entrevista (ENT05)</a>, <a href="../Elicitacao/elicitacao_brainstorm.md#resultados">Brainstorm (BRS05)</a> | Ambiental | Representação | João Ramos |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF13">RF13</a> | Oferecer recarga de cartão de transporte (ex.: integração com BRB Mobilidade) | <a href="../Elicitacao/elicitacao_entrevista.md#resultados">Entrevista (ENT07)</a> | Desenvolvimento | Representação (ENT07 representa RF13) | Cauã Nicolas |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF14">RF14</a> | Permitir integração com o cartão de transporte, incluindo saldo e recarga | <a href="../Elicitacao/elicitacao_entrevista.md#resultados">Entrevista (ENT07)</a> | Desenvolvimento | Representação (ENT07 representa RF14) | Cauã Nicolas |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF15">RF15</a> | Manter histórico de viagens do usuário | <a href="../Elicitacao/elicitacao_analise_documentos.md#requisitos-nao-implementados">Análise de Documentos (RNI03)</a> | Desenvolvimento | Representação (RNI03 representa RF15) | Cauã Nicolas |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF16">RF16</a> | Permitir reportar problemas (motorista, ônibus, cobrança) com dados do veículo e horário | <a href="../Elicitacao/elicitacao_entrevista.md#resultados">Entrevista (ENT20)</a> | Desenvolvimento | Representação (ENT20 representa RF16) | Cauã Nicolas |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF17">RF17</a> | Exibir preço da passagem por linha ou trajeto | <a href="../Elicitacao/elicitacao_brainstorm.md#resultados">Brainstorm (BRS19)</a>  | Gerencional | Representação (BRS19 representa RF17) | Daniel Nunes Duarte |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF18">RF18</a> | Listar linhas que passam em uma parada específica | <a href="../Elicitacao/elicitacao_brainstorm.md#resultados">Brainstorm (BRS05)</a> | Ambiental | Representação | João Ramos |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF19">RF19</a> | Disponibilizar versão web leve para acesso rápido em pontos de ônibus (via QR Code) | <a href="../Elicitacao/elicitacao_brainstorm.md#resultados">Brainstorm (BRS17)</a> | Ambiental | | Gabriel Maciel |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF20">RF20</a> | Botão de pânico/emergência para alertar motorista e/ou autoridades | <a href="../Elicitacao/elicitacao_brainstorm.md#resultados">Brainstorm (BRS21)</a>  | Ambiental | Representação (BRS21 representa RF20) | Daniel Nunes Duarte |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF21">RF21</a> | Mostrar alertas de trânsito, acidentes e rotas alternativas | <a href="../Elicitacao/elicitacao_brainstorm.md#resultados">Brainstorm (BRS12)</a> | Ambiental | Representação | João Ramos |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF22">RF22</a> | Permitir compartilhar trajeto em tempo real com outros usuários | <a href="../Elicitacao/elicitacao_brainstorm.md#resultados">Brainstorm (BRS20)</a>  | Ambiental | Representação (BRS20 representa RF22) | Daniel Nunes Duarte |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF23">RF23</a> | Exibir quantidade de assentos preferenciais e totais no ônibus | | | | |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF24">RF24</a> | Permitir favoritar linhas ou paradas para acesso rápido | <a href="../Elicitacao/elicitacao_entrevista.md#resultados">Entrevista (ENT14)</a> | Desenvolvimento | Representação (ENT14 representa RF24) | Cauã Nicolas |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF25">RF25</a> | Ampliar a cobertura e exibir informações também em regiões afastadas do Distrito Federal | <a href="../Elicitacao/elicitacao_entrevista.md#resultados">Entrevista (ENT08)</a> | Desenvolvimento | Representação (ENT08 representa RF25) | Cauã Nicolas |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF26">RF26</a> | Filtrar ônibus por empresa operadora | <a href="../Elicitacao/elicitacao_analise_documentos.md#requisitos-funcionais">Análise de Documentos (RF03)</a> | Organizacional | Satisfação (RF03 satisfaz RF26) | Gabriel Maciel |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF27">RF27</a> | Visualizar quais veículos estão em operação no momento | <a href="../Elicitacao/elicitacao_analise_documentos.md#requisitos-nao-implementados">Análise de Documentos (RN04)</a> | Organizacional | Satisfação (RF04 satisfaz RF27) | Daniel Nunes Duarte |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF28">RF28</a> | Permitir avaliação da qualidade do serviço de cada linha | <a href="../Elicitacao/elicitacao_analise_documentos.md#requisitos-nao-implementados">Análise de Documentos (RNI04)</a> | Organizacional | Satisfação (RNI04 satisfaz RF28) | Gabriel Maciel |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF29">RF29</a> | Sistema de gamificação para incentivar uso do transporte público | <a href="../Elicitacao/elicitacao_brainstorm.md#resultados">Brainstorm (BRS01)</a> | Desenvolvimento | Agregação (BRS01 agrega para RF29) | Daniel Nunes Duarte |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF30">RF30</a> | Previsão inteligente de horários baseada em dados históricos e machine learning |BRS02 |Ambiental | Satisfação (BR02 satisfaz o RF30) | João Gabriel |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF31">RF31</a> | Sistema de recompensas por uso sustentável do transporte público | <a href="../Elicitacao/elicitacao_brainstorm.md#resultados">Brainstorm (BRS09)</a>  |Organizacional |Satisfação (RF31 satisfaz objetivo organizacional de sustentabilidade) | Fernanda Vaz |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF32">RF32</a> | Exibir relatórios de impacto ambiental (CO₂ economizado) |  <a href="../Elicitacao/elicitacao_brainstorm.md#resultados">Brainstorm (BRS11)</a> |Organizacional | Recurso (RF32 serve como recurso para mensurar resultados de sustentabilidade)| Fernanda Vaz |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF33">RF33</a> | Suporte a comandos de voz para facilitar interação durante deslocamentos | <a href="../Elicitacao/elicitacao_brainstorm.md#resultados">Brainstorm (BRS14)</a> | Ambiental | (Recurso BRS11 ggera recurso para RF33) | Daniel Nunes Duarte |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF34">RF34</a> | Integração com assistentes virtuais (Alexa, Google Assistant) | <a href="../Elicitacao/elicitacao_brainstorm.md#resultados">Brainstorm (BRS16)</a> | Gerencial | Representação (BRS16 representa RF34) | Gabriel Maciel |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF35">RF35</a> | Permitir rastreamento de múltiplas linhas de ônibus simultaneamente no mapa | <a href="../Elicitacao/elicitacao_entrevista.md#resultados">Entrevista (ENT12)</a> | Gerencial | Representação (ENT12 representa RF35) | Gabriel Maciel |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF36">RF36</a> | Oferecer suporte multilíngue (português e inglês, no mínimo) | <a href="../Elicitacao/elicitacao_entrevista.md#resultados">Entrevista (ENT22)</a> | Gerencial | Representação (ENT22 representa RF36) | Gabriel Maciel |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF37">RF37</a> | Permitir cadastro, login e autenticação de usuários no sistema | <a href="../Elicitacao/elicitacao_brainstorm.md#resultados">Brainstorm (BRS18)</a> | Ambiental | Satisfação (satisfaz o Épico 8 - Gestão de Usuário e Conta) | João Gabriel |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF38">RF38</a> | Visualizar linhas que possuem ar-condicionado | <a href="../Elicitacao/elicitacao_brainstorm.md#resultados">Brainstorm (BRS20)</a> | Ambiental | | Gabriel Maciel |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RNF01">RNF01</a> | As informações de horários e localização dos ônibus devem ser precisas | <a href="../Elicitacao/elicitacao_entrevista.md#resultados">Entrevista (ENT09)</a> | Ambiental | Satisfação (Satisfaz o SIG - Confiabilidade) | João Gabriel |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RNF02">RNF02</a> | Rastreamento dos ônibus em tempo real deve ser confiável e sem falhas | <a href="../Elicitacao/elicitacao_entrevista.md#resultados">Entrevista (ENT13)</a> | Ambiental | Satisfação (Satisfaz o SIG - Confiabilidade) | João Gabriel |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RNF03">RNF03</a> | Tempo de atualização da localização ≤ 20 segundos | <a href="../Elicitacao/elicitacao_entrevista.md#resultados">Entrevista (ENT)</a> | Ambiental | Satisfação (Satisfaz o SIG-Desempenho) | João Gabriel |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RNF04">RNF04</a> | Interface acessível para idosos e pessoas com deficiência visual | <a href="../Elicitacao/elicitacao_entrevista.md#resultados">Entrevista (ENT10)</a>, <a href="../Elicitacao/elicitacao_brainstorm.md#resultados">Brainstorm (BRS08)</a> | Desenvolvimento | Representação (ENT10 representa RNF04) | Cauã Nicolas |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RNF05">RNF05</a> | Sistema de notificação com som e vibração configuráveis | <a href="../Elicitacao/elicitacao_brainstorm.md#resultados">Brainstorm (BRS18)</a> | Desenvolvimento | Representação (BRS18 representa RNF05) | Cauã Nicolas |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RNF06">RNF06</a> | Baixo consumo de bateria e dados móveis | --- |Desenvolvimento |Alocado (vinculado a subsistemas de otimização de desempenho) | Fernanda Vaz |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RNF07">RNF07</a> | Compatibilidade com dispositivos Android e iOS | <a href="../Elicitacao/elicitacao_entrevista.md#resultados">Entrevista (ENT19)</a>  |Desenvolvimento |Responsabilidade (da equipe de desenvolvimento em garantir compatibilidade multiplataforma) | Fernanda Vaz |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RNF08">RNF08</a> | Proteção contra reportes falsos de lotação (mecanismo de confiança) | | | | |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RNF09">RNF09</a> | Dados de localização e pessoais protegidos conforme LGPD | <a href="../Elicitacao/elicitacao_entrevista.md#resultados">Entrevista (ENT21)</a> | Ambiental | Representação | João Ramos |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RNF10">RNF10</a> | Tempo de carregamento da tela principal < 3 segundos | <a href="../Elicitacao/elicitacao_entrevista.md#resultados">Entrevista (ENT17)</a> | Gerencial | Representação (ENT17 representa RNF10) | Gabriel Maciel |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RNF11">RNF11</a> | Funcionamento offline para consulta a rotas salvas e horários | <a href="../Elicitacao/elicitacao_analise_documentos.md#requisitos-nao-implementados">Análise de Documentos (RNI05)</a>, <a href="../Elicitacao/elicitacao_entrevista.md#resultados">Entrevista (ENT18)</a>, <a href="../Elicitacao/elicitacao_brainstorm.md#resultados">Brainstorm (BRS06)</a> | Gerencial | Representação (ENT18 representa RNF11) | Gabriel Maciel |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RNF12">RNF12</a> | Integração segura com sistemas de pagamento (recarga de cartão) | <a href="../Elicitacao/elicitacao_brainstorm.md#resultados">Brainstorm (BRS10)</a> | Ambiental | Representação | João Ramos |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RNF13">RNF13</a> | Alta disponibilidade do sistema (≥ 98% uptime) | --- | Desenvolvimento | | Gabriel Maciel |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RNF14">RNF14</a> | Suporte a múltiplos usuários simultâneos sem lentidão | <a href="../Elicitacao/elicitacao_brainstorm.md#resultados">Brainstorm (BRS15)</a> | Ambiental | Responsabilidade (BRS15 representa RNF14)| Daniel Nunes Duarte |
| <a href="../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RNF15">RNF15</a> | Personalização da interface com base em preferências do usuário | <a href="../Elicitacao/elicitacao_brainstorm.md#resultados">Brainstorm (BRS13)</a> | Ambiental | Recurso (BRS13 representa RNF15) | Daniel Nunes Duarte |

## Tabela de Contribuição

|        Nome          | Contribuição|
|----------------------|-------------|
| Cauã Nicolas         | Rastreabilidade Backward-From dos Requisitos RF13, RF14, RF15, RF16, RF24, RF25, RNF04, RNF05 |
| Daniel Nunes Duarte  | Rastreabilidade Backward-From dos Requisitos RF17, RF20, RF22, RF27, RF29, RF33, RNF14, RNF15 |
| Fernanda Vaz         | Rastreabilidade Backward-From dos Requisito:RNF6 e RNF7, RF05, RF06, RF07, RF08, RF31, RF32 |
| Gabriel Maciel       | Rastreabilidade Backward-From dos Requisitos RF19, RF26, RF28, RF34, RF35, RF36, RNF10, RNF11 |
| João Gabriel         | A preencher |
| João Ramos           | Rastreabilidade Backward-From dos Requisitos: RF09 ao RF12, RF18, RF21, RNF09 e RNF12 |


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
| **1.2** | 27/10 | Adição das classificações de fonte e tipos de elo para os requisitos RF19, RF26, RF28, RF34, RF35, RF36, RNF10, RNF11 | Gabriel Maciel |
| **1.3** | 28/10 | Adição Referência Bibliográfica | João Gabriel | Gabriel Maciel |
| **1.4** | 28/10 | Preenchimento das classificações de fonte e tipos de elo para os requisitos RF19, RF26, RF28, RF34, RF35, RF36, RNF10, RNF11 | Gabriel Maciel | João Ramos |
| **1.5** | 28/10 | Adição da fonte, classificação e tipos de elos(RF: 9,10,11,12 e 21 RF:12)  | João Ramos | Gabriel Maciel |
| **1.6** | 28/10 | Adição RNF6 e RNF7, RF05, RF06, RF07, RF08, RF31, RF32 | FERNANDA VAZ| Gabriel Maciel |
| **1.7** | 28/10 | Correções da minha parte | João Gabriel| -- |
| **1.8** | 28/10 | Adição RF17, RF20, RF22, RF27, RF29, RF33, RNF14, RNF15 | Daniel Nunes Duarte | -------- |
| **1.9** | 28/10 | Adição RF09 ao RF12, RF18, RF21, RNF09, RNF 12 | João Ramos | Gabriel Maciel |
---

## Agradecimentos

> Agradecemos o suporte da ferramenta de Inteligência Artificial Generativa **Google Gemini** no desenvolvimento deste trabalho.  
Em conformidade com o Código de Conduta da Sociedade Brasileira de Computação (SBC), declaramos que a ferramenta foi utilizada como auxílio na revisão gramatical e estilística do texto, na sugestão de estrutura para seções específicas do artigo, bem como na formatação de tabelas e na descrição de figuras.  
Ressaltamos que os autores assumem total responsabilidade por todo o conteúdo apresentado, incluindo sua originalidade e precisão.  
A ferramenta não figura como autora desta publicação.
