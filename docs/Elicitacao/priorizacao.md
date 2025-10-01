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

## Brainstorming

O Vídeo 1 apresenta uma sessão prática de brainstorming, na qual integrantes do grupo debatem e sugerem funcionalidades prioritárias para o aplicativo de transporte público. Durante a discussão, cada participante contribui com requisitos considerados essenciais para o MVP, como localização em tempo real dos ônibus, sistema de alertas, exibição de preços das passagens e possibilidade de compartilhar trajetos com amigos. Essa dinâmica colaborativa evidencia como o brainstorming auxilia na identificação dos requisitos mais relevantes, promovendo consenso entre os envolvidos e direcionando o desenvolvimento do sistema para atender às necessidades dos usuários.

<iframe width="560" height="315" src="https://www.youtube.com/embed/UJ2Fn7aj6bk?si=ea2uyv_JVN4mDAIp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

*Vídeo 1: Priorização de Requisitos por sessão de Brainstorming *

### Bibliografia
>[1] SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 7. Aprender 3. Disponível em: https://aprender3.unb.br/pluginfile.php/3210604/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf 

>[2] WIEGERS, Karl; BEATTY, Joy. *Software requirements*. 3. ed. Redmond: Microsoft Press, 2013.

# Histórico de Versões

| Versão | Data       | Descrição                                                      | Autor(es)       | Revisor(es)       |
|--------|------------|----------------------------------------------------------------|----------------|-----------------|
| 1.0    | 30/09/2025 | Criação inicial do arquivo, adiciona técnica de priorização First Things First. | Cauã Nicolas   | Gabriel Macial  |
| 1.1    | 30/09/2025 | Adiciona técnica de priorização MoSCoW | Gabriel Maciel | Cauã Nicolas |
| 1.1.1    | 30/09/2025 | Adiciona técnica de priorização Brainstorming | Gabriel Maciel | João Lucas |
