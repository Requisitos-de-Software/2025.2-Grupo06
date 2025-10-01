# Técnicas de Priorização


## Descrição dos requisitos funcionais e não funcionais

A Tabela 1 apresenta a lista completa de requisitos funcionais e não funcionais identificados para o sistema, categorizando cada item conforme seu tipo. Essa organização facilita a visualização das funcionalidades essenciais e das características de qualidade esperadas, servindo como base para as etapas de priorização descritas posteriormente.

| ID        | Requisito                                                                                           | Tipo           |
|-----------|-----------------------------------------------------------------------------------------------------|----------------|
| ENT-F01   | Permitir pesquisa por linhas e rotas de ônibus                                                       | Funcional      |
| ENT-F02   | Apresentar horários de saída e chegada dos transportes                                               | Funcional      |
| ENT-F03   | Mostrar em tempo real a localização do ônibus buscado                                                | Funcional      |
| ENT-F04   | Informar o tempo estimado de chegada do ônibus ao ponto de parada                                    | Funcional      |
| ENT-F05   | Enviar alertas sobre atrasos, mudanças de rota ou alterações nos horários                            | Funcional      |
| ENT-F06   | Oferecer um mapa interativo com os pontos de ônibus e suas linhas correspondentes                    | Funcional      |
| ENT-F07   | Permitir integração com o cartão de transporte, incluindo saldo e recarga                            | Funcional      |
| ENT-F08   | Ampliar a cobertura e exibir informações também em regiões afastadas do Distrito Federal             | Funcional      |
| ENT-NF01  | Apresentar informações atualizadas e confiáveis, minimizando problemas de pontualidade               | Não Funcional  |
| ENT-NF02  | Interface intuitiva, clara e de fácil navegação, mesmo para novos usuários                           | Não Funcional  |
| BRN-F01   | Exibir a localização dos ônibus em tempo real no mapa                                                | Funcional      |
| BRN-F02   | Mostrar o tempo estimado de chegada do ônibus à parada                                               | Funcional      |
| BRN-F03   | Permitir planejamento de viagem (origem → destino) com rotas sugeridas                               | Funcional      |
| BRN-F04   | Integrar informações de outros modais (metrô, outros ônibus) em rotas multimodais                    | Funcional      |
| BRN-F05   | Exibir informações de acessibilidade do ônibus (ex.: acessível para cadeirantes)                     | Funcional      |
| BRN-F06   | Indicar lotação do ônibus (vazio, moderado, lotado)                                                  | Funcional      |
| BRN-F07   | Permitir que usuários reportem a lotação do ônibus (sistema colaborativo)                            | Funcional      |
| BRN-F08   | Enviar notificação quando o ônibus estiver a X minutos da parada                                     | Funcional      |
| BRN-F09   | Oferecer recarga de cartão de transporte (ex.: integração com BRB Mobilidade)                        | Funcional      |
| BRN-F10   | Manter histórico de viagens do usuário                                                               | Funcional      |
| BRN-F11   | Permitir reportar problemas (motorista, ônibus, cobrança) com dados do veículo e horário             | Funcional      |
| BRN-F12   | Exibir preço da passagem por linha ou trajeto                                                        | Funcional      |
| BRN-F13   | Listar linhas que passam em uma parada específica                                                    | Funcional      |
| BRN-F14   | Disponibilizar versão web leve para acesso rápido em pontos de ônibus (via QR Code)                  | Funcional      |
| BRN-F15   | Botão de pânico/emergência para alertar motorista e/ou autoridades                                   | Funcional      |
| BRN-F16   | Mostrar alertas de trânsito, acidentes e rotas alternativas                                          | Funcional      |
| BRN-F17   | Permitir compartilhar trajeto em tempo real com outros usuários                                      | Funcional      |
| BRN-F18   | Oferecer conteúdo de entretenimento durante a viagem (ex.: jogos, notícias)                          | Funcional      |
| BRN-F19   | Exibir quantidade de assentos preferenciais e totais no ônibus                                       | Funcional      |
| BRN-F20   | Permitir favoritar linhas ou paradas para acesso rápido                                              | Funcional      |
| BRN-NF01  | Tempo de atualização da localização do ônibus ≤ 20 segundos                                          | Não Funcional  |
| BRN-NF02  | Interface acessível para idosos e pessoas com deficiência visual                                     | Não Funcional  |
| BRN-NF03  | Sistema de notificação com som e vibração                                                            | Não Funcional  |
| BRN-NF04  | Baixo consumo de bateria e dados móveis                                                              | Não Funcional  |
| BRN-NF05  | Compatibilidade com dispositivos Android e iOS                                                       | Não Funcional  |
| BRN-NF06  | Proteção contra reportes falsos de lotação (mecanismo de confiança)                                  | Não Funcional  |
| BRN-NF07  | Dados de localização e pessoais protegidos por LGPD                                                  | Não Funcional  |
| BRN-NF08  | Tempo de carregamento da tela principal < 3 segundos                                                 | Não Funcional  |
| BRN-NF09  | Funcionamento offline para consulta a rotas salvas e horários                                        | Não Funcional  |
| BRN-NF10  | Integração segura com sistemas de pagamento (recarga de cartão)                                      | Não Funcional  |
| BRN-NF11  | Alta disponibilidade do sistema (≥ 98% de uptime)                                                    | Não Funcional  |
| BRN-NF12  | Suporte a múltiplos usuários simultâneos sem lentidão                                                | Não Funcional  |

*Tabela 1: *

## MoSCoW

### Introdução

A técnica MoSCoW é um método amplamente utilizado para definir prioridades em projetos, especialmente em ambientes ágeis. Seu nome é um acrônimo formado pelas iniciais das quatro categorias de classificação de requisitos:

- **Must have (Deve ter)**: Requisitos essenciais e obrigatórios para o sucesso do projeto. Sem eles, a entrega não pode ser considerada concluída.

- **Should have (Deveria ter)**: Requisitos importantes, mas não críticos. Sua ausência pode ser tolerada temporariamente, embora cause impacto.

- **Could have (Poderia ter)**: Requisitos desejáveis que agregam valor, mas cuja ausência não compromete o resultado final.

- **Won’t have (Não terá por agora)**: Requisitos acordados como fora do escopo da entrega atual, podendo ser considerados em versões futuras.


***Fonte:** WIEGERS, Karl; BEATTY, Joy. *Software requirements*. 3. ed. Redmond: Microsoft Press, 2013.*

A Tabela 2 apresenta os requisitos elicitados priorizados pela técnica MoSCoW.

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


*Tabela 2: Tabela de requisitos priorizados pela técnica MoSCoW.*

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

A Tabela 3 apresenta o resultado da aplicação da técnica First Things First, evidenciando a priorização dos requisitos com base nos critérios de benefício, penalidade, custo e risco. Por meio dessa análise quantitativa, é possível visualizar de forma clara quais funcionalidades devem ser implementadas primeiro para maximizar o valor entregue ao usuário e otimizar os recursos do projeto.

| ID        | Benefício | Penalidade | Valor total | Valor (%) | Custo | Custo (%) | Risco | Risco (%) | Prioridade |
|-----------|-----------|------------|-------------|-----------|-------|-----------|-------|-----------|------------|
| BRN-NF05  | 9         | 9          | 27          | 0,11      | 1     | 0,11      | 2     | 0,22      | 0,48       |
| ENT-F01   | 8         | 7          | 23          | 0,09      | 3     | 0,33      | 2     | 0,22      | 0,20       |
| BRN-NF02  | 7         | 6          | 20          | 0,08      | 2     | 0,22      | 3     | 0,33      | 0,20       |
| BRN-NF09  | 7         | 5          | 19          | 0,07      | 3     | 0,33      | 4     | 0,44      | 0,13       |
| BRN-NF08  | 7         | 7          | 21          | 0,08      | 4     | 0,44      | 6     | 0,67      | 0,11       |
| BRN-F02   | 7         | 8          | 22          | 0,09      | 5     | 0,56      | 7     | 0,78      | 0,09       |
| BRN-F20   | 7         | 8          | 22          | 0,09      | 7     | 0,78      | 3     | 0,33      | 0,09       |
| BRN-F10   | 4         | 6          | 14          | 0,06      | 4     | 0,44      | 3     | 0,33      | 0,09       |
| BRN-F01   | 9         | 9          | 27          | 0,11      | 7     | 0,78      | 8     | 0,89      | 0,09       |
| BRN-NF03  | 6         | 6          | 18          | 0,07      | 5     | 0,56      | 5     | 0,56      | 0,09       |
| BRN-F14   | 6         | 2          | 14          | 0,06      | 4     | 0,44      | 4     | 0,44      | 0,08       |
| BRN-NF07  | 9         | 9          | 27          | 0,11      | 8     | 0,89      | 9     | 1,00      | 0,08       |
| BRN-NF10  | 9         | 9          | 27          | 0,11      | 8     | 0,89      | 9     | 1,00      | 0,08       |
| ENT-NF02  | 8         | 9          | 25          | 0,10      | 8     | 0,89      | 8     | 0,89      | 0,07       |
| BRN-NF11  | 9         | 7          | 25          | 0,10      | 8     | 0,89      | 8     | 0,89      | 0,07       |
| ENT-NF01  | 9         | 9          | 27          | 0,11      | 9     | 1,00      | 8     | 0,89      | 0,07       |
| BRN-F03   | 7         | 6          | 20          | 0,08      | 8     | 0,89      | 4     | 0,44      | 0,07       |
| BRN-F12   | 7         | 6          | 20          | 0,08      | 6     | 0,67      | 8     | 0,89      | 0,07       |
| BRN-NF12  | 8         | 6          | 22          | 0,09      | 7     | 0,78      | 8     | 0,89      | 0,07       |
| ENT-F06   | 7         | 7          | 21          | 0,08      | 7     | 0,78      | 8     | 0,89      | 0,07       |
| BRN-NF06  | 7         | 7          | 21          | 0,08      | 7     | 0,78      | 8     | 0,89      | 0,07       |
| ENT-F08   | 7         | 7          | 21          | 0,08      | 8     | 0,89      | 8     | 0,89      | 0,06       |
| BRN-NF01  | 6         | 7          | 19          | 0,07      | 8     | 0,89      | 6     | 0,67      | 0,06       |
| BRN-F13   | 5         | 7          | 17          | 0,07      | 7     | 0,78      | 7     | 0,78      | 0,06       |
| ENT-F02   | 6         | 5          | 17          | 0,07      | 8     | 0,89      | 6     | 0,67      | 0,05       |
| ENT-F05   | 6         | 5          | 17          | 0,07      | 8     | 0,89      | 6     | 0,67      | 0,05       |
| BRN-F15   | 4         | 2          | 10          | 0,04      | 3     | 0,33      | 7     | 0,78      | 0,05       |
| BRN-F06   | 7         | 2          | 16          | 0,06      | 7     | 0,78      | 7     | 0,78      | 0,05       |
| BRN-F07   | 7         | 2          | 16          | 0,06      | 7     | 0,78      | 7     | 0,78      | 0,05       |
| BRN-F09   | 8         | 3          | 19          | 0,07      | 8     | 0,89      | 9     | 1,00      | 0,05       |
| BRN-F16   | 6         | 5          | 17          | 0,07      | 8     | 0,89      | 7     | 0,78      | 0,05       |
| BRN-F08   | 6         | 4          | 16          | 0,06      | 8     | 0,89      | 6     | 0,67      | 0,05       |
| BRN-NF04  | 4         | 5          | 13          | 0,05      | 6     | 0,67      | 6     | 0,67      | 0,05       |
| ENT-F07   | 7         | 3          | 17          | 0,07      | 8     | 0,89      | 9     | 1,00      | 0,05       |
| BRN-F04   | 8         | 2          | 18          | 0,07      | 9     | 1,00      | 9     | 1,00      | 0,05       |
| BRN-F17   | 4         | 6          | 14          | 0,06      | 9     | 1,00      | 8     | 0,89      | 0,04       |
| BRN-F05   | 4         | 1          | 9           | 0,04      | 7     | 0,78      | 6     | 0,67      | 0,03       |
| BRN-F19   | 2         | 4          | 8           | 0,03      | 7     | 0,78      | 6     | 0,67      | 0,03       |
| BRN-F11   | 2         | 2          | 6           | 0,02      | 5     | 0,56      | 6     | 0,67      | 0,03       |
| TOTAL     | 256       | 220        | 732         | 100,00    | 252   | 100,00    | 251   | 27,89     | 3,26       |


*Tabela 3: Resultados do First Things First (Fonte: OLIVEIRA, Cauã. 2025)*

## **In or Out (Dentro ou Fora)**

### Introdução

A técnica **In or Out** (Dentro ou Fora) é um método de priorização rápido e decisivo, ideal para definir o escopo inicial de um projeto ou de um **MVP(Produto Mínimo Viável)**. O objetivo é forçar os participantes a fazerem uma escolha binária e clara sobre cada requisito, se ele é absolutamente essencial para a primeira entrega ou pode esperar.

#### Como Funciona?

Cada participante, representando um *stakeholder*, recebe uma lista de todos os requisitos propostos. Para cada item da lista, ele deve tomar uma única decisão

* **IN (Dentro):** O requisito é considerado essencial e deve obrigatoriamente estar na próxima entrega/versão.
* **OUT (Fora):** O requisito é importante, mas não é essencial para a próxima entrega e pode ser implementado em uma fase futura.

Ou seja, não há meio termo. Um requisito não pode estar "meio dentro".

### Como Fizemos

* Para aplicar a técnica, foi realizada uma reunião com quatro participantes que simularam o papel de *stakeholders* do projeto "DF no Ponto".
* Uma planilha no Excel foi preparada com a lista de todos os Requisitos Funcionais (RFs) e Não Funcionais (RNFs) levantados. Cada participante recebeu uma cópia e marcou "IN" ou "OUT" para cada requisito, com base no que consideravam essencial para o lançamento do MVP.
* Após a votação individual, os resultados foram consolidados em uma tabela única para análise. Os requisitos foram então ordenados pela quantidade de votos "IN" recebidos, do maior para o menor.
* Os resultados da votação e o ranking final podem ser vistos na tabela abaixo.

### Ranking Final dos Requisitos (Ordenado por Votos "IN")

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
| ... | ... | ... | ... |

*Tabela 3: Ranking Parcial do In or Out - Fonte: João Lucas*

### Conclusão

A aplicação da técnica **In or Out** revelou um forte consenso sobre as funcionalidades essenciais para o MVP. Requisitos como localização em tempo real (RF01), tempo estimado de chegada (RF02), mapa interativo (RF06) e a busca por linhas (RF04), juntamente com requisitos não funcionais críticos como precisão (RNF01), confiabilidade (RNF02) e segurança (RNF09), foram unanimemente classificados como "IN".

Isso fornece uma direção clara para a equipe de desenvolvimento, que pode focar na construção de um produto inicial sólido e de alto valor, deixando funcionalidades importantes, mas não essenciais (como recarga de cartão ou histórico de viagens), para iterações futuras.

### Vídeo

[![Vídeo 1: Reunião de priorização de In or Out](https://img.youtube.com/vi/LjKYuKdOKN8/0.jpg)](https://www.youtube.com/watch?v=hJTgQuIg4iY)

*Vídeo 1: Reunião de priorização de In or Out - Fonte: João Lucas*

### Bibliografia

>[1] SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 7. Aprender 3. Disponível em: https://aprender3.unb.br/pluginfile.php/3210604/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf 
>[2] WIEGERS, Karl; BEATTY, Joy. *Software requirements*. 3. ed. Redmond: Microsoft Press, 2013.

# Histórico de Versões

| Versão | Data       | Descrição                                                      | Autor(es)       | Revisor(es)       |
|--------|------------|----------------------------------------------------------------|----------------|-----------------|
| 1.0    | 30/09/2025 | Criação inicial do arquivo, adiciona técnica de priorização First Things First. | Cauã Nicolas   | Gabriel Macial  |
| 1.1    | 30/09/2025 | Adiciona técnica de priorização MoSCoW | Gabriel Maciel | Cauã Nicolas |
| 1.1.1  | 30/09/2025 | Adiciona técnica de priorização Brainstorming | Gabriel Maciel | João Lucas |
| 1.1.2 | 30/09/2025 | Adiciona técnica de priorização $100 | João Gabriel | Gabriel Maciel | 
| 1.1.3 | 30/09/2025 | Adiciona técnica de priorização in or out | João Lucas| Gabriel Maciel | 
| 1.1.4  | 30/09/2025 | Remove técnica de priorização Brainstorming | Gabriel Maciel | João Lucas |