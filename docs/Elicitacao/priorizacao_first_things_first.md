# First Things First

## Introdução

A técnica **"First things first"** refere-se ao processo de **definir as prioridades dos requisitos** de um projeto de software. Em vez de tentar entregar todas as funcionalidades desejadas de uma só vez, essa abordagem foca em identificar e implementar primeiro os requisitos mais importantes para agregar valor ao sistema o mais rápido possível.

A priorização é crucial porque poucos projetos de software conseguem entregar todas as funcionalidades solicitadas na data de entrega inicial devido a limitações de recursos. Além de ajudar a revelar metas conflitantes entre as partes interessadas (stakeholders), resolver conflitos, planejar entregas incrementais ou por etapas e controlar o "scope creep" (aumento descontrolado do escopo).

## Metodologia

Nessa técnica, estão envolvidos:

**Gerente**: No qual está responsável para resolver conflitos, tomar decisões e administração geral de cada requisito.

**Representantes do Cliente**: Fornecem a visão do negócio, ajudando a definir o benefício de cada funcionalidade e a penalidade de não implementar, mostrando quais requisitos são essenciais.

**Desenvolvedores**: No qual fornecem as estimativas de custo (esforço) e de risco associadas à implementação de cada requisito.

### Processo de Cálculo

Para análise e prática dessa técnica, foi inicialmente desenvolvido o valor total, que pode ser calculado usando essa fórmula da seguinte forma:

**valor total = (benefício × peso) + (penalidade × peso)**

Depois de calcular o **valor total** de cada requisito — que resulta da soma ponderada de benefícios e penalidades — passa-se para a estimativa de custos.

Nessa etapa, os **desenvolvedores** avaliam o esforço necessário para implementar cada requisito, atribuindo notas de **1 a 9** conforme critérios como complexidade técnica, integração de interface, reaproveitamento de código, testes e documentação.

Em seguida, é feita a análise de riscos, também em escala de 1 a 9, levando em conta fatores como disponibilidade de equipe, incertezas de viabilidade e o uso de tecnologias pouco conhecidas.

Com isso, a prioridade de cada requisito é calculada por uma fórmula que relaciona o valor obtido com os custos e riscos ponderados.

A prioridade pode ser calculada seguindo a seguinte fórmula:

**prioridade = (valor%) / (custo% × peso do custo + risco% × peso do risco)**

O resultado final é um número de prioridade. **Quanto maior o valor calculado pela fórmula, maior a prioridade da funcionalidade**. Uma planilha foi usada para organizar esses dados e calcular a prioridade final para cada requisito.

## Resultado de Priorização

A priorização dos requisitos permitiu identificar quais funcionalidades e características são mais críticas para o sucesso do sistema, considerando o valor agregado ao usuário, o custo de implementação e os riscos envolvidos. Os requisitos funcionais com maior prioridade concentram-se em funcionalidades essenciais para a experiência do usuário, como localização em tempo real, planejamento de rotas e notificações. Já os requisitos não funcionais destacam a importância de desempenho, segurança, acessibilidade e confiabilidade do sistema. Esse resultado orienta o desenvolvimento incremental, garantindo que os itens de maior impacto sejam entregues primeiro, otimizando recursos e atendendo às expectativas dos stakeholders.

### Pesos Relativos Utilizados

- Benefício: 2
- Penalidade: 1
- Custo: 1
- Risco: 0,5

A Tabela 1 apresenta o resultado da aplicação da técnica First Things First, evidenciando a priorização dos requisitos com base nos critérios de benefício, penalidade, custo e risco. Por meio dessa análise quantitativa, é possível visualizar de forma clara quais funcionalidades devem ser implementadas primeiro para maximizar o valor entregue ao usuário e otimizar os recursos do projeto.

#### Tabela 1: Resultados do First Things First (Fonte: OLIVEIRA, Cauã. 2025)

| ID   | Descrição                                                                                   | Benefício | Penalidade | Valor total | Valor (%) | Custo | Custo (%) | Risco | Risco (%) | Prioridade |
|------|---------------------------------------------------------------------------------------------|-----------|------------|-------------|-----------|-------|-----------|-------|-----------|------------|
| RF01 | Exibir a localização dos ônibus em tempo real no mapa                                      | 9         | 9          | 27          | 0,11      | 7     | 0,78      | 8     | 0,89      | 0,09       |
| RF02 | Mostrar o tempo estimado de chegada do ônibus à parada                                     | 7         | 8          | 22          | 0,09      | 5     | 0,56      | 7     | 0,78      | 0,09       |
| RF03 | Permitir planejamento de viagem (origem → destino) com rotas sugeridas                     | 7         | 6          | 20          | 0,08      | 8     | 0,89      | 4     | 0,44      | 0,07       |
| RF04 | Permitir pesquisa por linhas e rotas de ônibus                                             | 8         | 7          | 23          | 0,09      | 3     | 0,33      | 2     | 0,22      | 0,20       |
| RF05 | Apresentar horários de saída e chegada dos transportes                                     | 6         | 5          | 17          | 0,07      | 8     | 0,89      | 6     | 0,67      | 0,05       |
| RF06 | Oferecer um mapa interativo com os pontos de ônibus e suas linhas correspondentes          | 7         | 7          | 21          | 0,08      | 7     | 0,78      | 8     | 0,89      | 0,07       |
| RF07 | Integrar informações de outros modais (metrô, outros ônibus) em rotas multimodais          | 8         | 2          | 18          | 0,07      | 9     | 1,00      | 9     | 1,00      | 0,05       |
| RF08 | Exibir informações de acessibilidade do ônibus (ex.: acessível para cadeirantes)           | 6         | 4          | 16          | 0,06      | 8     | 0,89      | 6     | 0,67      | 0,05       |
| RF09 | Indicar lotação do ônibus (vazio, moderado, lotado)                                        | 7         | 2          | 16          | 0,06      | 7     | 0,78      | 7     | 0,78      | 0,05       |
| RF10 | Permitir que usuários reportem a lotação do ônibus (sistema colaborativo)                  | 7         | 2          | 16          | 0,06      | 7     | 0,78      | 7     | 0,78      | 0,05       |
| RF11 | Enviar notificação quando o ônibus estiver a X minutos da parada                           | 2         | 2          | 6           | 0,02      | 5     | 0,56      | 6     | 0,67      | 0,03       |
| RF12 | Enviar alertas sobre atrasos, mudanças de rota ou alterações nos horários                  | 6         | 5          | 17          | 0,07      | 8     | 0,89      | 6     | 0,67      | 0,05       |
| RF13 | Oferecer recarga de cartão de transporte (ex.: integração com BRB Mobilidade)              | 8         | 3          | 19          | 0,07      | 8     | 0,89      | 9     | 1,00      | 0,05       |
| RF14 | Permitir integração com o cartão de transporte, incluindo saldo e recarga                  | 7         | 3          | 17          | 0,07      | 8     | 0,89      | 9     | 1,00      | 0,05       |
| RF15 | Manter histórico de viagens do usuário                                                     | 4         | 6          | 14          | 0,06      | 4     | 0,44      | 3     | 0,33      | 0,09       |
| RF16 | Permitir reportar problemas (motorista, ônibus, cobrança) com dados do veículo e horário   | 6         | 5          | 17          | 0,07      | 8     | 0,89      | 7     | 0,78      | 0,05       |
| RF17 | Exibir preço da passagem por linha ou trajeto                                              | 7         | 6          | 20          | 0,08      | 6     | 0,67      | 8     | 0,89      | 0,07       |
| RF18 | Listar linhas que passam em uma parada específica                                          | 5         | 7          | 17          | 0,07      | 7     | 0,78      | 7     | 0,78      | 0,06       |
| RF19 | Disponibilizar versão web leve para acesso rápido em pontos de ônibus (via QR Code)        | 6         | 2          | 14          | 0,06      | 4     | 0,44      | 4     | 0,44      | 0,08       |
| RF20 | Botão de pânico/emergência para alertar motorista e/ou autoridades                         | 4         | 2          | 10          | 0,04      | 3     | 0,33      | 7     | 0,78      | 0,05       |
| RF21 | Mostrar alertas de trânsito, acidentes e rotas alternativas                                | 6         | 5          | 17          | 0,07      | 8     | 0,89      | 7     | 0,78      | 0,05       |
| RF22 | Permitir compartilhar trajeto em tempo real com outros usuários                            | 4         | 6          | 14          | 0,06      | 9     | 1,00      | 8     | 0,89      | 0,04       |
| RF23 | Exibir quantidade de assentos preferenciais e totais no ônibus                             | 2         | 4          | 8           | 0,03      | 7     | 0,78      | 6     | 0,67      | 0,03       |
| RF24 | Permitir favoritar linhas ou paradas para acesso rápido                                    | 7         | 8          | 22          | 0,09      | 7     | 0,78      | 3     | 0,33      | 0,09       |
| RF25 | Ampliar a cobertura e exibir informações também em regiões afastadas do Distrito Federal   | 7         | 7          | 21          | 0,08      | 8     | 0,89      | 8     | 0,89      | 0,06       |
| RNF01| As informações de horários e localização dos ônibus devem ser precisas                     | 6         | 7          | 19          | 0,07      | 8     | 0,89      | 6     | 0,67      | 0,06       |
| RNF02| Rastreamento dos ônibus em tempo real deve ser confiável e sem falhas                      | 7         | 6          | 20          | 0,08      | 2     | 0,22      | 3     | 0,33      | 0,20       |
| RNF03| Tempo de atualização da localização ≤ 20 segundos                                          | 6         | 6          | 18          | 0,07      | 5     | 0,56      | 5     | 0,56      | 0,09       |
| RNF04| Interface acessível para idosos e pessoas com deficiência visual                           | 8         | 9          | 25          | 0,10      | 8     | 0,89      | 8     | 0,89      | 0,07       |
| RNF05| Sistema de notificação com som e vibração configuráveis                                    | 6         | 6          | 18          | 0,07      | 5     | 0,56      | 5     | 0,56      | 0,09       |
| RNF06| Baixo consumo de bateria e dados móveis                                                    | 4         | 5          | 13          | 0,05      | 6     | 0,67      | 6     | 0,67      | 0,05       |
| RNF07| Compatibilidade com dispositivos Android e iOS                                             | 9         | 9          | 27          | 0,11      | 1     | 0,11      | 2     | 0,22      | 0,48       |
| RNF08| Proteção contra reportes falsos de lotação (mecanismo de confiança)                        | 7         | 7          | 21          | 0,08      | 7     | 0,78      | 8     | 0,89      | 0,07       |
| RNF09| Dados de localização e pessoais protegidos conforme LGPD                                   | 9         | 9          | 27          | 0,11      | 8     | 0,89      | 9     | 1,00      | 0,08       |
| RNF10| Tempo de carregamento da tela principal < 3 segundos                                       | 9         | 9          | 27          | 0,11      | 8     | 0,89      | 9     | 1,00      | 0,08       |
| RNF11| Funcionamento offline para consulta a rotas salvas e horários                              | 7         | 5          | 19          | 0,07      | 3     | 0,33      | 4     | 0,44      | 0,13       |
| RNF12| Integração segura com sistemas de pagamento (recarga de cartão)                            | 8         | 6          | 22          | 0,09      | 7     | 0,78      | 8     | 0,89      | 0,07       |
| RNF13| Alta disponibilidade do sistema (≥ 98% uptime)                                             | 9         | 9          | 27          | 0,11      | 9     | 1,00      | 8     | 0,89      | 0,07       |
| RNF14| Suporte a múltiplos usuários simultâneos sem lentidão                                      | 8         | 6          | 22          | 0,09      | 7     | 0,78      | 8     | 0,89      | 0,07       |
| **TOTAL** | | **256**   | **220**    | **732**     | **100,00**| **252**| **100,00**| **251**| **27,89** | **3,26**   |

## Análise dos Resultados

### Requisitos de Maior Prioridade

Os requisitos com maior prioridade calculada foram:

1. **BRN-NF05** (Compatibilidade com dispositivos Android e iOS) - Prioridade: 0,48
2. **ENT-F01** (Permitir pesquisa por linhas e rotas de ônibus) - Prioridade: 0,20
3. **BRN-NF02** (Interface acessível para idosos e pessoas com deficiência visual) - Prioridade: 0,20

### Requisitos Funcionais Prioritários

Entre os requisitos funcionais, destacam-se:

- Pesquisa por linhas e rotas
- Tempo estimado de chegada
- Manter histórico de viagens
- Localização em tempo real

### Requisitos Não Funcionais Prioritários

Os requisitos não funcionais de maior prioridade incluem:

- Compatibilidade multiplataforma
- Acessibilidade
- Funcionamento offline
- Tempo de carregamento otimizado

## Responsáveis pela Elaboração

| Nome            | Responsabilidade              |
|-----------------|-------------------------------|
| Cauã Nicolas | Aplicação da técnica de priorização First Things First |

## Histórico de Versões

| Versão | Data       | Descrição                                           | Autor(es)       | Revisor(es)       |
|--------|------------|-----------------------------------------------------|-----------------|-------------------|
| 1.0    | 30/09/2025 | Criação inicial do arquivo, adiciona técnica de priorização First Things First. | Cauã Nicolas   | Gabriel Maciel  |
| 2.0    | 08/10/2025 | Separação do conteúdo em arquivo específico        | Gabriel Maciel  | Cauã Nicolas |
| 2.1    | 08/10/2025 | Padronização da tabela de requisitos | Gabriel Maciel  | Cauã Nicolas |
| 2.2   | 08/10/2025 | Adiciona tabela de identificação dos responsáveis pela elaboração do documento  | Gabriel Maciel  | João Gabriel |

## Bibliografia

>[1] SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 7. Aprender 3. Disponível em: <https://aprender3.unb.br/pluginfile.php/3210604/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf>

>[2] WIEGERS, Karl; BEATTY, Joy. *Software requirements*. 3. ed. Redmond: Microsoft Press, 2013.