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
