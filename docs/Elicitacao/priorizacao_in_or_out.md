# In or Out (Dentro ou Fora)

## Introdução

A técnica **In or Out** (Dentro ou Fora) é um método de priorização rápido e decisivo, ideal para definir o escopo inicial de um projeto ou de um **MVP (Produto Mínimo Viável)**. O objetivo é forçar os participantes a fazerem uma escolha binária e clara sobre cada requisito, se ele é absolutamente essencial para a primeira entrega ou pode esperar.

### Como Funciona?

Cada participante, representando um *stakeholder*, recebe uma lista de todos os requisitos propostos. Para cada item da lista, ele deve tomar uma única decisão:

* **IN (Dentro):** O requisito é considerado essencial e deve obrigatoriamente estar na próxima entrega/versão.
* **OUT (Fora):** O requisito é importante, mas não é essencial para a próxima entrega e pode ser implementado em uma fase futura.

Ou seja, não há meio termo. Um requisito não pode estar "meio dentro".

## Metodologia

### Como Fizemos

* Para aplicar a técnica, foi realizada uma reunião com quatro participantes que simularam o papel de *stakeholders* do projeto "DF no Ponto".
* Uma planilha no Excel foi preparada com a lista de todos os Requisitos Funcionais (RFs) e Não Funcionais (RNFs) levantados. Cada participante recebeu uma cópia e marcou "IN" ou "OUT" para cada requisito, com base no que consideravam essencial para o lançamento do MVP.
* Após a votação individual, os resultados foram consolidados em uma tabela única para análise. Os requisitos foram então ordenados pela quantidade de votos "IN" recebidos, do maior para o menor.
* Os resultados da votação e o ranking final podem ser vistos na tabela abaixo.

## Ranking Final dos Requisitos (Ordenado por Votos "IN")

| Posição | ID | Votos "IN" | Votos "OUT" |
|:---:|:---:|:---:|:---:|
| **1** | RF01 | **4** | **0** |
| **2** | RF02 | **4** | **0** |
| **3** | RF04 | **4** | **0** |
| **4** | RF06 | **4** | **0** |
| **5** | RNF01 | **4** | **0** |
| **6** | RNF02 | **4** | **0** |
| **7** | RNF07 | **4** | **0** |
| **8** | RNF09 | **4** | **0** |
| **9** | RNF10 | **4** | **0** |
| **10** | RNF13 | **4** | **0** |
| **11** | RF03 | **3** | **1** |
| **12** | RF05 | **3** | **1** |
| **13** | RF12 | **3** | **1** |
| **14** | RF18 | **3** | **1** |
| **15** | RF24 | **3** | **1** |
| **16** | RF08 | **2** | **2** |
| **17** | RF09 | **2** | **2** |
| **18** | RF11 | **2** | **2** |
| **19** | RF17 | **2** | **2** |
| **20** | RF21 | **2** | **2** |

*Tabela 1: Ranking Parcial do In or Out - Fonte: João Lucas*

## Conclusão

A aplicação da técnica **In or Out** revelou um forte consenso sobre as funcionalidades essenciais para o MVP. Requisitos como localização em tempo real (RF01), tempo estimado de chegada (RF02), mapa interativo (RF06) e a busca por linhas (RF04), juntamente com requisitos não funcionais críticos como precisão (RNF01), confiabilidade (RNF02) e segurança (RNF09), foram unanimemente classificados como "IN".

Isso fornece uma direção clara para a equipe de desenvolvimento, que pode focar na construção de um produto inicial sólido e de alto valor, deixando funcionalidades importantes, mas não essenciais (como recarga de cartão ou histórico de viagens), para iterações futuras.

## Vídeo

[![Vídeo 1: Reunião de priorização de In or Out](https://img.youtube.com/vi/LjKYuKdOKN8/0.jpg)](https://www.youtube.com/watch?v=hJTgQuIg4iY)

*Vídeo 1: Reunião de priorização de In or Out - Fonte: João Lucas*

## Descrição dos Requisitos Funcionais e Não Funcionais

| ID    | Requisito                                                                                   | Tipo           |
|--------------|---------------------------------------------------------------------------------------------|----------------|
| RF01  | Exibir a localização dos ônibus em tempo real no mapa                                       | Funcional      |
| RF02  | Mostrar o tempo estimado de chegada do ônibus à parada                                      | Funcional      |
| RF03  | Permitir planejamento de viagem (origem → destino) com rotas sugeridas                      | Funcional      |
| RF04  | Permitir pesquisa por linhas e rotas de ônibus                                              | Funcional      |
| RF05  | Apresentar horários de saída e chegada dos transportes                                      | Funcional      |
| RF06  | Oferecer um mapa interativo com os pontos de ônibus e suas linhas correspondentes           | Funcional      |
| RF07  | Integrar informações de outros modais (metrô, outros ônibus) em rotas multimodais           | Funcional      |
| RF08  | Exibir informações de acessibilidade do ônibus (ex.: acessível para cadeirantes)            | Funcional      |
| RF09  | Indicar lotação do ônibus (vazio, moderado, lotado)                                         | Funcional      |
| RF10  | Permitir que usuários reportem a lotação do ônibus (sistema colaborativo)                   | Funcional      |
| RF11  | Enviar notificação quando o ônibus estiver a X minutos da parada                            | Funcional      |
| RF12  | Enviar alertas sobre atrasos, mudanças de rota ou alterações nos horários                   | Funcional      |
| RF13  | Oferecer recarga de cartão de transporte (ex.: integração com BRB Mobilidade)               | Funcional      |
| RF14  | Permitir integração com o cartão de transporte, incluindo saldo e recarga                   | Funcional      |
| RF15  | Manter histórico de viagens do usuário                                                      | Funcional      |
| RF16  | Permitir reportar problemas (motorista, ônibus, cobrança) com dados do veículo e horário    | Funcional      |
| RF17  | Exibir preço da passagem por linha ou trajeto                                               | Funcional      |
| RF18  | Listar linhas que passam em uma parada específica                                           | Funcional      |
| RF19  | Disponibilizar versão web leve para acesso rápido em pontos de ônibus (via QR Code)         | Funcional      |
| RF20  | Botão de pânico/emergência para alertar motorista e/ou autoridades                          | Funcional      |
| RF21  | Mostrar alertas de trânsito, acidentes e rotas alternativas                                 | Funcional      |
| RF22  | Permitir compartilhar trajeto em tempo real com outros usuários                             | Funcional      |
| RF23  | Exibir quantidade de assentos preferenciais e totais no ônibus                              | Funcional      |
| RF24  | Permitir favoritar linhas ou paradas para acesso rápido                                     | Funcional      |
| RF25  | Ampliar a cobertura e exibir informações também em regiões afastadas do Distrito Federal    | Funcional      |
| RNF01 | As informações de horários e localização dos ônibus devem ser precisas.                     | Não Funcional  |
| RNF02 | Rastreamento dos ônibus em tempo real deve ser confiável e sem falhas.                      | Não Funcional  |
| RNF03 | Tempo de atualização da localização ≤ 20 segundos.                                          | Não Funcional  |
| RNF04 | Interface acessível para idosos e pessoas com deficiência visual.                           | Não Funcional  |
| RNF05 | Sistema de notificação com som e vibração configuráveis.                                    | Não Funcional  |
| RNF06 | Baixo consumo de bateria e dados móveis.                                                    | Não Funcional  |
| RNF07 | Compatibilidade com dispositivos Android e iOS.                                             | Não Funcional  |
| RNF08 | Proteção contra reportes falsos de lotação (mecanismo de confiança).                        | Não Funcional  |
| RNF09 | Dados de localização e pessoais protegidos conforme LGPD.                                   | Não Funcional  |
| RNF10 | Tempo de carregamento da tela principal < 3 segundos.                                       | Não Funcional  |
| RNF11 | Funcionamento offline para consulta a rotas salvas e horários.                              | Não Funcional  |
| RNF12 | Integração segura com sistemas de pagamento (recarga de cartão).                            | Não Funcional  |
| RNF13 | Alta disponibilidade do sistema (≥ 98% uptime).                                             | Não Funcional  |
| RNF14 | Suporte a múltiplos usuários simultâneos sem lentidão.                                      | Não Funcional  |

*Tabela 2: Priorização de requisitos com In or Out (Fonte: OLIVEIRA, Cauã. BRITO, João. 2025)*

## Análise dos Resultados

### Requisitos Essenciais (100% dos votos "IN")

Os seguintes requisitos receberam consenso total para inclusão no MVP:

**Funcionais:**
- RF01: Localização em tempo real dos ônibus
- RF02: Tempo estimado de chegada
- RF04: Pesquisa por linhas e rotas
- RF06: Mapa interativo

**Não Funcionais:**
- RNF01: Precisão das informações
- RNF02: Confiabilidade do rastreamento
- RNF07: Compatibilidade multiplataforma
- RNF09: Proteção de dados (LGPD)
- RNF10: Tempo de carregamento otimizado
- RNF13: Alta disponibilidade

### Requisitos com Alto Consenso (75% dos votos "IN")

Funcionalidades importantes mas com uma dissidência:
- RF03: Planejamento de viagem
- RF05: Horários de saída e chegada
- RF12: Alertas sobre atrasos
- RF18: Listar linhas por parada
- RF24: Favoritar linhas/paradas

### Requisitos Controversos (50% dos votos)

Funcionalidades que dividiram opiniões igualmente entre essencial e não essencial para o MVP.

## Histórico de Versões

| Versão | Data       | Descrição                                           | Autor(es)       | Revisor(es) |
|--------|------------|-----------------------------------------------------|-----------------|-------------|
| 1.1.3  | 30/09/2025 | Adiciona técnica de priorização in or out | João Lucas| Gabriel Maciel |
| 2.0    | 08/10/2025 | Separação do conteúdo em arquivo específico        | Gabriel Maciel  | João Lucas |

## Bibliografia

>[1] SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 7. Aprender 3. Disponível em: <https://aprender3.unb.br/pluginfile.php/3210604/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf>

>[2] WIEGERS, Karl; BEATTY, Joy. *Software requirements*. 3. ed. Redmond: Microsoft Press, 2013.