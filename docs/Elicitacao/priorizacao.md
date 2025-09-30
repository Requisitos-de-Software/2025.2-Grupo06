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

| Identificador | Benefício | Penalidade | Valor total | Valor (%) | Custo | Custo (%) | Risco | Risco (%) | Prioridade |
|---------------|-----------|------------|-------------|-----------|-------|-----------|-------|-----------|------------|
| RF01  | 9 | 9 | 27 | 0,12 | 7 | 0,78 | 8 | 0,89 | 0,10 |
| RF02  | 7 | 8 | 22 | 0,10 | 5 | 0,56 | 7 | 0,78 | 0,10 |
| RF03  | 7 | 6 | 20 | 0,09 | 8 | 0,89 | 4 | 0,44 | 0,08 |
| RF04  | 8 | 7 | 23 | 0,10 | 3 | 0,33 | 2 | 0,22 | 0,23 |
| RF05  | 6 | 5 | 17 | 0,08 | 8 | 0,89 | 6 | 0,67 | 0,06 |
| RF06  | 7 | 7 | 21 | 0,09 | 7 | 0,78 | 8 | 0,89 | 0,08 |
| RF07  | 8 | 2 | 18 | 0,08 | 9 | 1,00 | 9 | 1,00 | 0,05 |
| RF08  | 4 | 1 | 9  | 0,04 | 7 | 0,78 | 6 | 0,67 | 0,04 |
| RF09  | 7 | 2 | 16 | 0,07 | 7 | 0,78 | 7 | 0,78 | 0,06 |
| RF10  | 7 | 2 | 16 | 0,07 | 7 | 0,78 | 7 | 0,78 | 0,06 |
| RF11  | 6 | 4 | 16 | 0,07 | 8 | 0,89 | 6 | 0,67 | 0,06 |
| RF12  | 6 | 5 | 17 | 0,08 | 8 | 0,89 | 6 | 0,67 | 0,06 |
| RF13  | 8 | 3 | 19 | 0,09 | 8 | 0,89 | 9 | 1,00 | 0,06 |
| RF14  | 7 | 3 | 17 | 0,08 | 8 | 0,89 | 9 | 1,00 | 0,06 |
| RF15  | 4 | 6 | 14 | 0,06 | 4 | 0,44 | 3 | 0,33 | 0,10 |
| RF16  | 2 | 2 | 6  | 0,03 | 5 | 0,56 | 6 | 0,67 | 0,03 |
| RF17  | 7 | 6 | 20 | 0,09 | 6 | 0,67 | 8 | 0,89 | 0,08 |
| RF18  | 5 | 7 | 17 | 0,08 | 7 | 0,78 | 7 | 0,78 | 0,07 |
| RF19  | 6 | 2 | 14 | 0,06 | 4 | 0,44 | 4 | 0,44 | 0,09 |
| RF20  | 4 | 2 | 10 | 0,05 | 3 | 0,33 | 7 | 0,78 | 0,06 |
| RF21  | 6 | 5 | 17 | 0,08 | 8 | 0,89 | 7 | 0,78 | 0,06 |
| RF22  | 4 | 6 | 14 | 0,06 | 9 | 1,00 | 8 | 0,89 | 0,04 |
| RF23  | 2 | 4 | 8  | 0,04 | 7 | 0,78 | 6 | 0,67 | 0,03 |
| RF24  | 7 | 8 | 22 | 0,10 | 7 | 0,78 | 3 | 0,33 | 0,10 |
| RF25  | 7 | 7 | 21 | 0,09 | 8 | 0,89 | 8 | 0,89 | 0,07 |
| RNF01 | 9 | 9 | 27 | 0,12 | 9 | 1,00 | 8 | 0,89 | 0,08 |
| RNF02 | 8 | 9 | 25 | 0,11 | 8 | 0,89 | 8 | 0,89 | 0,08 |
| RNF03 | 6 | 7 | 19 | 0,09 | 8 | 0,89 | 6 | 0,67 | 0,07 |
| RNF04 | 7 | 6 | 20 | 0,09 | 2 | 0,22 | 3 | 0,33 | 0,23 |
| RNF05 | 6 | 6 | 18 | 0,08 | 5 | 0,56 | 5 | 0,56 | 0,10 |
| RNF06 | 4 | 5 | 13 | 0,06 | 6 | 0,67 | 6 | 0,67 | 0,06 |
| RNF07 | 9 | 9 | 27 | 0,12 | 1 | 0,11 | 2 | 0,22 | 0,55 |
| RNF08 | 7 | 7 | 21 | 0,09 | 7 | 0,78 | 8 | 0,89 | 0,08 |
| RNF09 | 9 | 9 | 27 | 0,12 | 8 | 0,89 | 9 | 1,00 | 0,09 |
| RNF10 | 7 | 7 | 21 | 0,09 | 4 | 0,44 | 6 | 0,67 | 0,12 |
| RNF11 | 7 | 5 | 19 | 0,09 | 3 | 0,33 | 4 | 0,44 | 0,15 |
| RNF12 | 9 | 9 | 27 | 0,12 | 8 | 0,89 | 9 | 1,00 | 0,09 |
| RNF13 | 9 | 7 | 25 | 0,11 | 8 | 0,89 | 8 | 0,89 | 0,08 |
| RNF14 | 8 | 6 | 16 | 0,07 | 7 | 0,78 | 8 | 0,89 | 0,06 |

*Tabela 4: Resultados do First Things First (Fonte: OLIVEIRA, Cauã. 2025)*



| Identificador    | Requisito                                                                                   | Tipo           |
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

*Tabela 4: Priorização de requisitos com First Things First (Fonte: OLIVEIRA, Cauã. 2025)*


