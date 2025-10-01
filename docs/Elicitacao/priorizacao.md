## **$100 Dollars**

### Introdução?

A técnica **$100 Dollars** (ou "Teste dos $100") é um método de priorização colaborativa e rápida que ajuda times a descobrirem o que **realmente tem mais valor** segundo o coletivo. 

A premissa é simples: simular um orçamento limitado para forçar escolhas estratégicas.

#### Como Funciona?

Cada participante recebe **$100 fictícios** para "investir" nos itens que serão priorizados. A distribuição do dinheiro revela não apenas *o que* as pessoas consideram importante, mas *o quanto* consideram importante.

#### Passo a Passo:

1. **Listagem**: Todos os itens (funcionalidades, tarefas, melhorias) são listados claramente
2. **Distribuição**: Cada pessoa distribui seus $100 entre os itens, podendo:
   - Colocar tudo em um único item
   - Distribuir igualmente
   - Ou qualquer combinação entre esses extremos
3. **Votação Anônima**: A distribuição é feita de forma individual e silenciosa
4. **Somatório**: Os valores de todos os participantes são somados para cada item
5. **Ranking**: Os itens são ordenados do maior para o menor valor total


### Como Fizemos
- O mediador das conversas fez uma planilha do excel como todos os requisitos e montando copias dela para 4 participantes preencherem com um valor correspondente a importância que dava para aquele requisito em específico. Feito no Excel simplesmente pra facilitar para que mostre com uma formula se a soma está dando mais ou menos de 100.

![Planilha da Técnica $100 Dollars](../assets/imagens/Excel100Dollars.png)

*Figura 1: Excel utilizado no 100 Dollars - Fonte: João Gabriel*

- Foi feita uma discussão geral entre todos participantes sobre porque escolheram tal requisito como importante, em relação a requisitos em que empatavam pontos etc. Com tudo isso gravado em vídeo para documentação do que **os usuários dava mais prioridade.**

- Por fim, no final da discussão e uma análise dos dados após a discussão com os participantes, fazendo-se se uma média de todos os valores, e assim, colocamos em ordem de importância os requisitos feitos. Os resultados podem ser vistos abaixo.

##  Ranking Final dos Requisitos (Ordenado por Média)

| Posição | ID | Requisito | Média | P1 | P2 | P3 | P4 |
|---------|----|-----------|-------|----|----|----|----|
| 1 | RF01 | **Exibir a localização dos ônibus em tempo real no mapa** | **10.8** | 8 | 20 | 10 | 5 |
| 2 | RF06 | **Oferecer um mapa interativo com os pontos de ônibus e suas linhas correspondentes** | **8.3** | 8 | - | 5 | 8 |
| 3 | RF03 | **Permitir planejamento de viagem (origem + destino) com rotas sugeridas** | **7.5** | 7 | 10 | 10 | 3 |
| 4 | RF04 | **Permitir pesquisa por linhas e rotas de ônibus** | **7.3** | 7 | 5 | 10 | 7 |
| 5 | RF02 | **Mostrar o tempo estimado de chegada do ônibus à parada** | **6.8** | 5 | 10 | 10 | 7 |
| 6 | RF24 | **Permitir favoritar linhas ou paradas para acesso rápido** | **6.5** | 6 | 10 | 1 | - |
| 7 | RF21 | **Mostrar alertas de trânsito, acidentes e rotas alternativas** | **6.5** | 4 | 10 | 3 | 3 |
| 8 | RF09 | **Indicar lotação do ônibus (vazio, moderado, lotado)** | **6.3** | 5 | - | 5 | 7 |
| 9 | RF12 | **Enviar alertas sobre atrasos, mudanças de rota ou alterações nos horários** | **5.8** | 3 | 10 | 5 | 5 |
| 10 | RF18 | **Listar linhas que passam em uma parada específica** | **4.7** | 2 | - | 4 | 8 |
| 11 | RF05 | **Apresentar horários de saída e chegada dos transportes** | **4.5** | 5 | 10 | 3 | - |
| 12 | RF25 | **Ampliar a cobertura para regiões afastadas do DF** | **4.0** | 5 | 5 | - | - |
| 13 | RF10 | **Permitir que usuários reportem a lotação do ônibus** | **4.0** | 4 | 5 | 2 | 6 |
| 14 | RF11 | **Enviar notificação quando ônibus estiver a X minutos** | **3.8** | 4 | - | 3 | 4 |
| 15 | RF13 | **Oferecer recarga de cartão de transporte** | **3.5** | 4 | 3 | - | 4 |
| 16 | RF14 | **Permitir integração com cartão de transporte** | **3.5** | 4 | 4 | - | 4 |
| 17 | RF07 | **Integrar informações de outros modais** | **3.3** | 4 | 2 | 7 | - |
| 18 | RF17 | **Exibir preço da passagem por linha ou trajeto** | **2.8** | 4 | 10 | 2 | 1 |
| 19 | RF19 | **Versão web leve para pontos de ônibus (QR Code)** | **2.8** | 4 | 1 | - | 4 |
| 20 | RF08 | **Exibir informações de acessibilidade do ônibus** | **2.3** | 1 | 4 | 3 | 3 |
| 21 | RF16 | **Permitir reportar problemas** | **2.0** | 1 | 2 | 3 | 3 |
| 22 | RF20 | **Botão de pânico/emergência** | **2.0** | 1 | 2 | 3 | 3 |
| 23 | RF22 | **Permitir compartilhar trajeto em tempo real** | **1.3** | 2 | 2 | 0 | 2 |
| 24 | RF15 | **Manter histórico de viagens do usuário** | **1.3** | 1 | 1 | 2 | 2 |
| 25 | RF23 | **Exibir quantidade de assentos preferenciais** | **1.3** | 1 | 1 | 3 | 1 |

*Legenda: P1, P2, P3, P4 = Participantes 1 a 4*
*Tabela 1: Conclusão 100 Dollars - Fonte: João Gabriel*

## Análise de Consenso entre Participantes

### Requisitos com Maior Consenso (Menor Variação)
1. **RF01** - Localização em tempo real: Todos os participantes deram notas altas (5-20)
2. **RF04** - Pesquisa por linhas: Notas consistentemente boas (5-10)
3. **RF03** - Planejamento de viagem: Boa aceitação geral (3-10)

### Requisitos com Maior Discrepância
1. **RF24** - Favoritar linhas: Variação grande (1-10)
2. **RF17** - Preço da passagem: Opiniões divididas (1-10)
3. **RF06** - Mapa interativo: Um participante não votou

### Conclusão
Com esses dados, poderiamos criar um MVP bem embasado do que grande parte dos perfis de usuário gostariam de ter no aplicativo como o DF No Ponto de forma geral.

### Vídeo

<iframe width="560" height="315" src="https://www.youtube.com/embed/LjKYuKdOKN8" title="Técnica de Priorização $100 Dollars" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

*Vídeo 1: Reunião de priorização de 100 Dollars - Fonte: João Gabriel*



## **First Thing First**
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




 