# MoSCoW

## Introdução

A técnica MoSCoW é um método amplamente utilizado para definir prioridades em projetos, especialmente em ambientes ágeis. Seu nome é um acrônimo formado pelas iniciais das quatro categorias de classificação de requisitos:

- **Must have (Deve ter)**: Requisitos essenciais e obrigatórios para o sucesso do projeto. Sem eles, a entrega não pode ser considerada concluída.

- **Should have (Deveria ter)**: Requisitos importantes, mas não críticos. Sua ausência pode ser tolerada temporariamente, embora cause impacto.

- **Could have (Poderia ter)**: Requisitos desejáveis que agregam valor, mas cuja ausência não compromete o resultado final.

- **Won't have (Não terá por agora)**: Requisitos acordados como fora do escopo da entrega atual, podendo ser considerados em versões futuras.

## Metodologia

A aplicação da técnica MoSCoW seguiu um processo estruturado de análise e classificação dos requisitos previamente identificados. A equipe avaliou cada requisito considerando:

- **Importância para o usuário final**
- **Impacto no funcionamento básico do sistema**
- **Dependências técnicas entre requisitos**
- **Viabilidade de implementação no escopo atual**

## Resultados da Priorização MoSCoW

A Tabela 1 apresenta os requisitos elicitados priorizados pela técnica MoSCoW.

### Tabela 1: Tabela de requisitos priorizados pela técnica MoSCoW

| Classificação MoSCoW | ID    | Descrição                                                                                         |
|-----------------------|-------|---------------------------------------------------------------------------------------------------|
| Must Have | RF01  | Exibir a localização dos ônibus em tempo real no mapa                                            |
| Must Have | RF02  | Mostrar o tempo estimado de chegada do ônibus à parada                                           |
| Must Have | RF03  | Permitir planejamento de viagem (origem → destino) com rotas sugeridas                           |
| Must Have | RF04  | Permitir pesquisa por linhas e rotas de ônibus                                                   |
| Must Have | RF05  | Apresentar horários de saída e chegada dos transportes                                           |
| Must Have | RF06  | Oferecer um mapa interativo com os pontos de ônibus e suas linhas correspondentes                |
| Must Have | RF07  | Integrar informações de outros modais (metrô, outros ônibus) em rotas multimodais                |
| Must Have | RF08  | Exibir informações de acessibilidade do ônibus (ex.: acessível para cadeirantes)                 |
| Could Have | RF09  | Indicar lotação do ônibus (vazio, moderado, lotado)                                              |
| Could Have | RF10  | Permitir que usuários reportem a lotação do ônibus (sistema colaborativo)                        |
| Must Have | RF11  | Enviar notificação quando o ônibus estiver a X minutos da parada                                 |
| Must Have | RF12  | Enviar alertas sobre atrasos, mudanças de rota ou alterações nos horários                        |
| Could Have | RF13  | Oferecer recarga de cartão de transporte (ex.: integração com BRB Mobilidade)                    |
| Could Have | RF14  | Permitir integração com o cartão de transporte, incluindo saldo e recarga                        |
| Could Have | RF15  | Manter histórico de viagens do usuário                                                           |
| Could Have | RF16  | Permitir reportar problemas (motorista, ônibus, cobrança) com dados do veículo e horário         |
| Must Have | RF17  | Exibir preço da passagem por linha ou trajeto                                                    |
| Must Have | RF18  | Listar linhas que passam em uma parada específica                                                |
| Could Have | RF19  | Disponibilizar versão web leve para acesso rápido em pontos de ônibus (via QR Code)              |
| Could Have | RF20  | Botão de pânico/emergência para alertar motorista e/ou autoridades                               |
| Must Have | RF21  | Mostrar alertas de trânsito, acidentes e rotas alternativas                                      |
| Won't Have | RF22  | Permitir compartilhar trajeto em tempo real com outros usuários                                  |
| Could Have | RF23  | Exibir quantidade de assentos preferenciais e totais no ônibus                                   |
| Must Have | RF24  | Permitir favoritar linhas ou paradas para acesso rápido                                          |
| Could Have | RF25  | Ampliar a cobertura e exibir informações também em regiões afastadas do Distrito Federal         |
| Must Have | RNF01 | As informações de horários e localização dos ônibus devem ser precisas                           |
| Must Have | RNF02 | Rastreamento dos ônibus em tempo real deve ser confiável e sem falhas                            |
| Must Have | RNF03 | Tempo de atualização da localização ≤ 20 segundos                                                |
| Must Have | RNF04 | Interface acessível para idosos e pessoas com deficiência visual                                 |
| Must Have | RNF05 | Sistema de notificação com som e vibração configuráveis                                          |
| Must Have | RNF06 | Baixo consumo de bateria e dados móveis                                                          |
| Must Have | RNF07 | Compatibilidade com dispositivos Android e iOS                                                   |
| Could Have | RNF08 | Proteção contra reportes falsos de lotação (mecanismo de confiança)                              |
| Must Have | RNF09 | Dados de localização e pessoais protegidos conforme LGPD                                         |
| Must Have | RNF10 | Tempo de carregamento da tela principal < 3 segundos                                             |
| Could Have | RNF11 | Funcionamento offline para consulta a rotas salvas e horários                                    |
| Could Have | RNF12 | Integração segura com sistemas de pagamento (recarga de cartão)                                  |
| Must Have | RNF13 | Alta disponibilidade do sistema (≥ 98% uptime)                                                   |
| Must Have | RNF14 | Suporte a múltiplos usuários simultâneos sem lentidão                                            |

*Tabela 1: Requisitos identificados através da técnica de Brainstorm - Autor: Gabriel Maciel, 2025*

## Análise dos Resultados

### Must Have (Deve ter)

Os requisitos classificados como "Must Have" representam as funcionalidades essenciais para o funcionamento básico do sistema. Incluem:

- Funcionalidades core como localização em tempo real, busca por linhas e planejamento de viagens
- Requisitos de usabilidade e acessibilidade fundamentais
- Características de desempenho e segurança críticas

### Should Have (Deveria ter)

Nesta aplicação específica, não foram identificados requisitos na categoria "Should Have", indicando uma clara separação entre funcionalidades essenciais e opcionais.

### Could Have (Poderia ter)

Funcionalidades que agregam valor mas não são críticas para o lançamento inicial:

- Recursos colaborativos como reporte de lotação
- Integrações avançadas com sistemas de pagamento
- Funcionalidades offline

### Won't Have (Não terá por agora)

Funcionalidades acordadas como fora do escopo atual:

- Recursos sociais como compartilhamento de trajeto
- Funcionalidades de entretenimento

## Bibliografia

>[1] WIEGERS, Karl; BEATTY, Joy. *Software requirements*. 3. ed. Redmond: Microsoft Press, 2013.

>[2] SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 7. Aprender 3. Disponível em: <https://aprender3.unb.br/pluginfile.php/3210604/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf>

### Responsáveis pela Elaboração

| Nome            | Responsabilidade              |
|-----------------|-------------------------------|
| Gabriel Maciel    | Aplicação da técnica de priorização MoSCoW |

##  Histórico de Versões

| Versão | Data       | Descrição                                           | Autor(es)       | Revisor(es) |
|--------|------------|-----------------------------------------------------|-----------------|-------------|
| 1.1    | 30/09/2025 | Adiciona técnica de priorização MoSCoW | Gabriel Maciel | Cauã Nicolas |
| 2.0    | 08/10/2025 | Separação do conteúdo em arquivo específico  | Gabriel Maciel  | Cauã Nicolas |
| 2.1    | 08/10/2025 | Padronização da tabela de requisitos | Gabriel Maciel  | Cauã Nicolas |
| 2.2   | 08/10/2025 | Adiciona tabela de identificação dos responsáveis pela elaboração do documento  | Gabriel Maciel  | Cauã Nicolas |

## Agradecimentos
>>Agradecemos o suporte da ferramenta de Inteligência Artificial Generativa Google Gemini no desenvolvimento deste trabalho. Em conformidade com o Código de Conduta da Sociedade Brasileira de Computação (SBC), declaramos que a ferramenta foi utilizada como auxílio na revisão gramatical e estilística do texto, na sugestão de estrutura para seções específicas do artigo, bem como na formatação de tabelas e na descrição de figuras. Ressaltamos que os autores assumem total responsabilidade por todo o conteúdo apresentado, incluindo sua originalidade e precisão. A ferramenta não figura como autora desta publicação.
