# Técnicas de Priorização

## MoSCoW

### Introdução

A técnica MoSCoW é um método amplamente utilizado para definir prioridades em projetos, especialmente em ambientes ágeis. Seu nome é um acrônimo formado pelas iniciais das quatro categorias de classificação de requisitos:

- **Must have (Deve ter)**: Requisitos essenciais e obrigatórios para o sucesso do projeto. Sem eles, a entrega não pode ser considerada concluída.

- **Should have (Deveria ter)**: Requisitos importantes, mas não críticos. Sua ausência pode ser tolerada temporariamente, embora cause impacto.

- **Could have (Poderia ter)**: Requisitos desejáveis que agregam valor, mas cuja ausência não compromete o resultado final.

- **Won’t have (Não terá por agora)**: Requisitos acordados como fora do escopo da entrega atual, podendo ser considerados em versões futuras.


***Fonte:** WIEGERS, Karl; BEATTY, Joy. *Software requirements*. 3. ed. Redmond: Microsoft Press, 2013.*

A tabela N apresenta os requisitos elicitados priorizados pela técnica MoSCoW.

| Classificação MoSCoW | ID       | Descrição                                                                                         |
|-----------------------|----------|-------------------------------------------------------------------------------------------------|
| Must Have | ENT-F01  | Permitir pesquisa por linhas e rotas de ônibus                                                   |
| Must Have | ENT-F02  | Apresentar horários de saída e chegada dos transportes                                           |
| Must Have | ENT-F03  | Mostrar em tempo real a localização do ônibus buscado                                            |
| Must Have | ENT-F04  | Informar o tempo estimado de chegada do ônibus ao ponto de parada                                |
| Must Have | ENT-F05  | Enviar alertas sobre atrasos, mudanças de rota ou alterações nos horários                        |
| Must Have | ENT-F06  | Oferecer um mapa interativo com os pontos de ônibus e suas linhas correspondentes                |
| Could Have | ENT-F07  | Permitir integração com o cartão de transporte, incluindo saldo e recarga                        |
| Could Have | ENT-F08  | Ampliar a cobertura e exibir informações também em regiões afastadas do Distrito Federal         |
| Must Have | ENT-NF01 | Apresentar informações atualizadas e confiáveis, minimizando problemas de pontualidade           |
| Must Have | ENT-NF02 | Interface intuitiva, clara e de fácil navegação, mesmo para novos usuários                       |
| Must Have | BRN-F01  | Exibir a localização dos ônibus em tempo real no mapa                                            |
| Must Have | BRN-F02  | Mostrar o tempo estimado de chegada do ônibus à parada                                           |
| Must Have | BRN-F03  | Permitir planejamento de viagem (origem → destino) com rotas sugeridas                           |
| Must Have | BRN-F04  | Integrar informações de outros modais (metrô, outros ônibus) em rotas multimodais                |
| Must Have | BRN-F05  | Exibir informações de acessibilidade do ônibus (ex.: acessível para cadeirantes)                 |
| Could Have | BRN-F06  | Indicar lotação do ônibus (vazio, moderado, lotado)                                              |
| Could Have | BRN-F07  | Permitir que usuários reportem a lotação do ônibus (sistema colaborativo)                        |
| Must Have | BRN-F08  | Enviar notificação quando o ônibus estiver a X minutos da parada                                 |
| Could Have | BRN-F09  | Oferecer recarga de cartão de transporte (ex.: integração com BRB Mobilidade)                    |
| Could Have | BRN-F10  | Manter histórico de viagens do usuário                                                           |
| Could Have | BRN-F11  | Permitir reportar problemas (motorista, ônibus, cobrança) com dados do veículo e horário         |
| Must Have | BRN-F12  | Exibir preço da passagem por linha ou trajeto                                                    |
| Must Have | BRN-F13  | Listar linhas que passam em uma parada específica                                                |
| Could Have | BRN-F14  | Disponibilizar versão web leve para acesso rápido em pontos de ônibus (via QR Code)              |
| Could Have | BRN-F15  | Botão de pânico/emergência para alertar motorista e/ou autoridades                               |
| Must Have | BRN-F16  | Mostrar alertas de trânsito, acidentes e rotas alternativas                                      |
| Won't Have | BRN-F17  | Permitir compartilhar trajeto em tempo real com outros usuários                                  |
| Won't Have | BRN-F18  | Oferecer conteúdo de entretenimento durante a viagem (ex.: jogos, notícias)                      |
| Could Have | BRN-F19  | Exibir quantidade de assentos preferenciais e totais no ônibus                                   |
| Must Have | BRN-F20  | Permitir favoritar linhas ou paradas para acesso rápido                                          |
| Must Have | BRN-NF01 | Tempo de atualização da localização do ônibus ≤ 20 segundos                                      |
| Must Have | BRN-NF02 | Interface acessível para idosos e pessoas com deficiência visual                                 |
| Must Have | BRN-NF03 | Sistema de notificação com som e vibração                                                        |
| Must Have | BRN-NF04 | Baixo consumo de bateria e dados móveis                                                          |
| Must Have | BRN-NF05 | Compatibilidade com dispositivos Android e iOS                                                   |
| Could Have | BRN-NF06 | Proteção contra reportes falsos de lotação (mecanismo de confiança)                              |
| Must Have | BRN-NF07 | Dados de localização e pessoais protegidos por LGPD                                              |
| Must Have | BRN-NF08 | Tempo de carregamento da tela principal < 3 segundos                                             |
| Could Have | BRN-NF09 | Funcionamento offline para consulta a rotas salvas e horários                                    |
| Could Have | BRN-NF10 | Integração segura com sistemas de pagamento (recarga de cartão)                                  |
| Must Have | BRN-NF11 | Alta disponibilidade do sistema (≥ 98% de uptime)                                                |
| Must Have | BRN-NF12 | Suporte a múltiplos usuários simultâneos sem lentidão                                            |


*Tabela N: Tabela de requisitos priorizados pela técnica MoSCoW.*

## Referências


WIEGERS, Karl; BEATTY, Joy. *Software requirements*. 3. ed. Redmond: Microsoft Press, 2013.
## First Thing First
### Introdução
A técnica **"First things first"** refere-se ao processo de **definir as prioridades dos requisitos** de um projeto de software. Em vez de tentar entregar todas as funcionalidades desejadas de uma só vez, essa abordagem foca em identificar e implementar primeiro os requisitos mais importantes para agregar valor ao sistema o mais rápido possível. 

A priorização é crucial porque poucos projetos de software conseguem entregar todas as funcionalidades solicitadas na data de entrega inicial devido a limitações de recursos. Além de ajudar a revelar metas conflitantes entre as partes interessadas (stakeholders), resolver conflitos, planejar entregas incrementais ou por etapas e controlar o "scope creep" (aumento descontrolado do escopo).  

Nessa técnica, estão envolvidos: 

**Gerente**: No qual está responsável para resolver conflitos, tomar decisões e administração geral de cada requisito. 

**Representantes do Cliente**: Fornecem a visão do negócio, ajudando a definir o benefício de cada funcionalidade e a penalidade de não implementar, mostrando quais requisitos são essenciais. 

**Desenvolvedores**: No qual fornecem as estimativas de custo (esforço) e de risco associadas à implementação de cada requisito. 

Para análise e prática dessa técnica, foi inicialmente desenvolvido o valor total, que pode ser calculado usando essa fórmula da seguinte forma: 

**valor total = (benefício * peso) + (penalidade * peso)**

Depois de calcular o **valor total** de cada requisito — que resulta da soma ponderada de benefícios e penalidades — passa-se para a estimativa de custos. 
Nessa etapa, os **desenvolvedores** avaliam o esforço necessário para implementar cada requisito, atribuindo notas de **1 a 9** conforme critérios como complexidade técnica, integração de interface, reaproveitamento de código, testes e documentação. 

Em seguida, é feita a análise de riscos, também em escala de 1 a 9, levando em conta fatores como disponibilidade de equipe, incertezas de viabilidade e o uso de tecnologias pouco conhecidas. 

Com isso, a prioridade de cada requisito é calculada por uma fórmula que relaciona o valor obtido com os custos e riscos ponderados. 

A prioridade pode ser calculada seguindo a seguinte fórmula: 

**prioridade = (valor%) / (custo% * peso do custo + risco% * peso do risco)** 

O resultado final é um número de prioridade. **Quanto maior o valor calculado pela fórmula, maior a prioridade da funcionalidade**. Uma planilha foi usada para organizar esses dados e calcular a prioridade final para cada requisito. 

### Resultado de Priorização
A priorização dos requisitos permitiu identificar quais funcionalidades e características são mais críticas para o sucesso do sistema, considerando o valor agregado ao usuário, o custo de implementação e os riscos envolvidos. Os requisitos funcionais com maior prioridade concentram-se em funcionalidades essenciais para a experiência do usuário, como localização em tempo real, planejamento de rotas e notificações. Já os requisitos não funcionais destacam a importância de desempenho, segurança, acessibilidade e confiabilidade do sistema. Esse resultado orienta o desenvolvimento incremental, garantindo que os itens de maior impacto sejam entregues primeiro, otimizando recursos e atendendo às expectativas dos stakeholders.

**Peso relativo:**
- Benefício: 2 
- Penalidade: 1 
- Custo: 1 
- Risco: 0,5 

| ID     | Benefício | Penalidade | Valor total | Valor (%) | Custo | Custo (%) | Risco | Risco (%) | Prioridade |
|--------|-----------|------------|-------------|-----------|-------|-----------|-------|-----------|------------|
| RNF07  | 9         | 9          | 27          | 0,11      | 1     | 0,11      | 2     | 0,22      | 0,48       |
| RF04   | 8         | 7          | 23          | 0,09      | 3     | 0,33      | 2     | 0,22      | 0,20       |
| RNF04  | 7         | 6          | 20          | 0,08      | 2     | 0,22      | 3     | 0,33      | 0,20       |
| RNF11  | 7         | 5          | 19          | 0,07      | 3     | 0,33      | 4     | 0,44      | 0,13       |
| RNF10  | 7         | 7          | 21          | 0,08      | 4     | 0,44      | 6     | 0,67      | 0,11       |
| RF02   | 7         | 8          | 22          | 0,09      | 5     | 0,56      | 7     | 0,78      | 0,09       |
| RF24   | 7         | 8          | 22          | 0,09      | 7     | 0,78      | 3     | 0,33      | 0,09       |
| RF15   | 4         | 6          | 14          | 0,06      | 4     | 0,44      | 3     | 0,33      | 0,09       |
| RF01   | 9         | 9          | 27          | 0,11      | 7     | 0,78      | 8     | 0,89      | 0,09       |
| RNF05  | 6         | 6          | 18          | 0,07      | 5     | 0,56      | 5     | 0,56      | 0,09       |
| RF19   | 6         | 2          | 14          | 0,06      | 4     | 0,44      | 4     | 0,44      | 0,08       |
| RNF09  | 9         | 9          | 27          | 0,11      | 8     | 0,89      | 9     | 1,00      | 0,08       |
| RNF12  | 9         | 9          | 27          | 0,11      | 8     | 0,89      | 9     | 1,00      | 0,08       |
| RNF02  | 8         | 9          | 25          | 0,10      | 8     | 0,89      | 8     | 0,89      | 0,07       |
| RNF13  | 9         | 7          | 25          | 0,10      | 8     | 0,89      | 8     | 0,89      | 0,07       |
| RNF01  | 9         | 9          | 27          | 0,11      | 9     | 1,00      | 8     | 0,89      | 0,07       |
| RF03   | 7         | 6          | 20          | 0,08      | 8     | 0,89      | 4     | 0,44      | 0,07       |
| RF17   | 7         | 6          | 20          | 0,08      | 6     | 0,67      | 8     | 0,89      | 0,07       |
| RNF14  | 8         | 6          | 22          | 0,09      | 7     | 0,78      | 8     | 0,89      | 0,07       |
| RF06   | 7         | 7          | 21          | 0,08      | 7     | 0,78      | 8     | 0,89      | 0,07       |
| RNF08  | 7         | 7          | 21          | 0,08      | 7     | 0,78      | 8     | 0,89      | 0,07       |
| RF25   | 7         | 7          | 21          | 0,08      | 8     | 0,89      | 8     | 0,89      | 0,06       |
| RNF03  | 6         | 7          | 19          | 0,07      | 8     | 0,89      | 6     | 0,67      | 0,06       |
| RF18   | 5         | 7          | 17          | 0,07      | 7     | 0,78      | 7     | 0,78      | 0,06       |
| RF05   | 6         | 5          | 17          | 0,07      | 8     | 0,89      | 6     | 0,67      | 0,05       |
| RF12   | 6         | 5          | 17          | 0,07      | 8     | 0,89      | 6     | 0,67      | 0,05       |
| RF20   | 4         | 2          | 10          | 0,04      | 3     | 0,33      | 7     | 0,78      | 0,05       |
| RF09   | 7         | 2          | 16          | 0,06      | 7     | 0,78      | 7     | 0,78      | 0,05       |
| RF10   | 7         | 2          | 16          | 0,06      | 7     | 0,78      | 7     | 0,78      | 0,05       |
| RF13   | 8         | 3          | 19          | 0,07      | 8     | 0,89      | 9     | 1,00      | 0,05       |
| RF21   | 6         | 5          | 17          | 0,07      | 8     | 0,89      | 7     | 0,78      | 0,05       |
| RF11   | 6         | 4          | 16          | 0,06      | 8     | 0,89      | 6     | 0,67      | 0,05       |
| RNF06  | 4         | 5          | 13          | 0,05      | 6     | 0,67      | 6     | 0,67      | 0,05       |
| RF14   | 7         | 3          | 17          | 0,07      | 8     | 0,89      | 9     | 1,00      | 0,05       |
| RF07   | 8         | 2          | 18          | 0,07      | 9     | 1,00      | 9     | 1,00      | 0,05       |
| RF22   | 4         | 6          | 14          | 0,06      | 9     | 1,00      | 8     | 0,89      | 0,04       |
| RF08   | 4         | 1          | 9           | 0,04      | 7     | 0,78      | 6     | 0,67      | 0,03       |
| RF23   | 2         | 4          | 8           | 0,03      | 7     | 0,78      | 6     | 0,67      | 0,03       |
| RF16   | 2         | 2          | 6           | 0,02      | 5     | 0,56      | 6     | 0,67      | 0,03       |
| TOTAL  | 256       | 220        | 732         | 100,00    | 252   | 100,00    | 251   | 27,89     | 3,26       |

*Tabela 1: Resultados do First Things First (Fonte: OLIVEIRA, Cauã. 2025)*


### Descrição dos requisitos funcionais e não funcionais
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

*Tabela 2: Priorização de requisitos com First Things First (Fonte: OLIVEIRA, Cauã. 2025)*

### Bibliografia
>[1] SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 7. Aprender 3. Disponível em: https://aprender3.unb.br/pluginfile.php/3210604/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf 




