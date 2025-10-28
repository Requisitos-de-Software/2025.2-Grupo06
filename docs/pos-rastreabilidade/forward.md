# Forward-From

## Introdução
A rastreabilidade forward-from (pós-rastreabilidade) vincula requisitos a artefatos de desenho, implementação e validação (como código e casos de teste), rastreando-os desde a origem até a entrega. (SAYÃO; LEITE, 2005).

## Metodologia

A rastreabilidade forward-from foi estabelecida mapeando os requisitos para os seguintes artefatos gerados no projeto:

- Casos de Uso (Use Case)

- Histórias de Usuário

- NFR Framework (Requisitos Não Funcionais)

- Especificação Suplementar

- Cenários

- Léxico

O meta-modelo de Toranzo estabelece um conjunto de elos de rastreabilidade que definem os tipos de relacionamentos entre os elementos rastreados. A seguir, apresentam-se os principais elos:

1. **Satisfação**: Indica que a classe de origem possui uma dependência de satisfação com a classe de destino.
2. **Recurso**: A classe de origem demonstra dependência de recurso em relação à classe de destino.
3. **Responsabilidade**: Registra a participação, a responsabilidade e a ação de pessoas sobre os artefatos do projeto.
4. **Representação**: Captura como os requisitos ou outros elementos são modelados ou representados em diferentes linguagens.
5. **Alocado**: A classe de origem está relacionada a uma classe de destino que geralmente representa um subsistema.
6. **Agregação**: Indica a composição de elementos, ou seja, que um elemento é composto por outros.

# Tabela de Rastreabilidade de Requisitos

## Requisitos Funcionais

| **ID** | **Requisito** | **Implementado** | **Cenário** | **Léxico** | **Caso de Uso** | **Épico** | **Elos** | **História de Usuário** |
|:------:|:---------------|:----------------:|:-----------:|:----------:|:---------------:|:---------:|:--------:|:-----------------------:|
| [**RF01**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF01) | Exibir a localização dos ônibus em tempo real no mapa | [Não](../Validacao/implementado.md#RF01) | [CEN03](../Modelagem/cenarios.md#CEN03) | [L12](../Modelagem/lexicos.md#L12) | [UC03](../Modelagem/casos-de-uso.md#UC03) | [EP01](../Modelagem/backlog.md#EP01) | [ELO01](../Pos-rastreabilidade/elos.md#ELO01) | [US15](../Modelagem/historias-usuario.md#US15) |
| [**RF02**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF02) | Mostrar o tempo estimado de chegada do ônibus à parada | [Não](../Validacao/implementado.md#RF02) | [CEN01](../Modelagem/cenarios.md#CEN01) | [L09](../Modelagem/lexicos.md#L09) | [UC02](../Modelagem/casos-de-uso.md#UC02) | [EP01](../Modelagem/backlog.md#EP01) | [ELO02](../Pos-rastreabilidade/elos.md#ELO02) | [US16](../Modelagem/historias-usuario.md#US16) |
| [**RF03**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF03) | Permitir planejamento de viagem (origem → destino) com rotas sugeridas | [Não](../Validacao/implementado.md#RF03) | [CEN09](../Modelagem/cenarios.md#CEN09) | [L05](../Modelagem/lexicos.md#L05) | [UC09](../Modelagem/casos-de-uso.md#UC09) | [EP07](../Modelagem/backlog.md#EP07) | [ELO03](../Pos-rastreabilidade/elos.md#ELO03) | [US17](../Modelagem/historias-usuario.md#US17) |
| [**RF04**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF04) | Permitir pesquisa por linhas e rotas de ônibus | [Não](../Validacao/implementado.md#RF04) | — | [L11](../Modelagem/lexicos.md#L11) | — | [EP02](../Modelagem/backlog.md#EP02) | [ELO04](../Pos-rastreabilidade/elos.md#ELO04) | [US18](../Modelagem/historias-usuario.md#US18) |
| [**RF05**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF05) | Apresentar horários de saída e chegada dos transportes | [Não](../Validacao/implementado.md#RF05) | — | [L09](../Modelagem/lexicos.md#L09) | — | [EP01](../Modelagem/backlog.md#EP01) | [ELO05](../Pos-rastreabilidade/elos.md#ELO05) | [US05](../Modelagem/historias-usuario.md#US05), [US19](../Modelagem/historias-usuario.md#US19) |
| [**RF06**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF06) | Oferecer um mapa interativo com os pontos de ônibus e suas linhas correspondentes | [Não](../Validacao/implementado.md#RF06) | — | — | — | [EP01](../Modelagem/backlog.md#EP01) | [ELO06](../Pos-rastreabilidade/elos.md#ELO06) | [US06](../Modelagem/historias-usuario.md#US06) |
| [**RF07**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF07) | Integrar informações de outros modais (metrô, outros ônibus) em rotas multimodais | [Não](../Validacao/implementado.md#RF07) | — | — | — | [EP07](../Modelagem/backlog.md#EP07) | [ELO07](../Pos-rastreabilidade/elos.md#ELO07) | [US07](../Modelagem/historias-usuario.md#US07) |
| [**RF08**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF08) | Exibir informações de acessibilidade do ônibus (ex.: acessível para cadeirantes) | [Não](../Validacao/implementado.md#RF08) | — | — | — | [EP04](../Modelagem/backlog.md#EP04) | [ELO08](../Pos-rastreabilidade/elos.md#ELO08) | [US08](../Modelagem/historias-usuario.md#US08) |
| [**RF09**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF09) | Indicar lotação do ônibus (vazio, moderado, lotado) | [Não](../Validacao/implementado.md#RF09) | — | — | — | [EP01](../Modelagem/backlog.md#EP01) | [ELO09](../Pos-rastreabilidade/elos.md#ELO09) | [US22](../Modelagem/historias-usuario.md#US22) |
| [**RF10**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF10) | Permitir que usuários reportem a lotação do ônibus (sistema colaborativo) | [Não](../Validacao/implementado.md#RF10) | [CEN06](../Modelagem/cenarios.md#CEN06) | — | [UC08](../Modelagem/casos-de-uso.md#UC08) | [EP05](../Modelagem/backlog.md#EP05) | [ELO10](../Pos-rastreabilidade/elos.md#ELO10) | [US23](../Modelagem/historias-usuario.md#US23) |
| [**RF11**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF11) | Enviar notificação quando o ônibus estiver a X minutos da parada | [Não](../Validacao/implementado.md#RF11) | — | — | — | [EP01](../Modelagem/backlog.md#EP01) | [ELO11](../Pos-rastreabilidade/elos.md#ELO11) | [US24](../Modelagem/historias-usuario.md#US24) |
| [**RF12**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF12) | Enviar alertas sobre atrasos, mudanças de rota ou alterações nos horários | [Não](../Validacao/implementado.md#RF12) | — | — | — | [EP01](../Modelagem/backlog.md#EP01) | [ELO12](../Pos-rastreabilidade/elos.md#ELO12) | [US25](../Modelagem/historias-usuario.md#US25) |
| [**RF13**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF13) | Oferecer recarga de cartão de transporte (ex.: integração com BRB Mobilidade) | [Não](../Validacao/implementado.md#RF13) | [CEN04](../Modelagem/cenarios.md#CEN04) | — | [UC04](../Modelagem/casos-de-uso.md#UC04) | [EP07](../Modelagem/backlog.md#EP07) | [ELO13](../Pos-rastreabilidade/elos.md#ELO13) | [US09](../Modelagem/historias-usuario.md#US09) |
| [**RF14**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF14) | Permitir integração com o cartão de transporte, incluindo saldo e recarga | [Não](../Validacao/implementado.md#RF14) | — | — | — | [EP07](../Modelagem/backlog.md#EP07) | [ELO14](../Pos-rastreabilidade/elos.md#ELO14) | [US10](../Modelagem/historias-usuario.md#US10) |
| [**RF15**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF15) | Manter histórico de viagens do usuário | [Não](../Validacao/implementado.md#RF15) | [CEN07](../Modelagem/cenarios.md#CEN07) | — | [UC05](../Modelagem/casos-de-uso.md#UC05) | [EP08](../Modelagem/backlog.md#EP08) | [ELO15](../Pos-rastreabilidade/elos.md#ELO15) | [US11](../Modelagem/historias-usuario.md#US11) |
| [**RF16**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF16) | Permitir reportar problemas (motorista, ônibus, cobrança) com dados do veículo e horário | [Não](../Validacao/implementado.md#RF16) | — | — | — | [EP05](../Modelagem/backlog.md#EP05) | [ELO16](../Pos-rastreabilidade/elos.md#ELO16) | [US12](../Modelagem/historias-usuario.md#US12) |
| [**RF17**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF17) | Exibir preço da passagem por linha ou trajeto | [Não](../Validacao/implementado.md#RF17) | — | — | — | [EP07](../Modelagem/backlog.md#EP07) | [ELO17](../Pos-rastreabilidade/elos.md#ELO17) | [US31](../Modelagem/historias-usuario.md#US31) |
| [**RF18**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF18) | Listar linhas que passam em uma parada específica | [Não](../Validacao/implementado.md#RF18) | — | — | — | [EP02](../Modelagem/backlog.md#EP02) | [ELO18](../Pos-rastreabilidade/elos.md#ELO18) | [US27](../Modelagem/historias-usuario.md#US27) |
| [**RF19**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF19) | Disponibilizar versão web leve para acesso rápido em pontos de ônibus (via QR Code) | [Não](../Validacao/implementado.md#RF19) | — | — | — | [EP03](../Modelagem/backlog.md#EP03) | [ELO19](../Pos-rastreabilidade/elos.md#ELO19) | [US02](../Modelagem/historias-usuario.md#US02) |
| [**RF20**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF20) | Botão de pânico/emergência para alertar motorista e/ou autoridades | [Não](../Validacao/implementado.md#RF20) | — | — | — | [EP10](../Modelagem/backlog.md#EP10) | [ELO20](../Pos-rastreabilidade/elos.md#ELO20) | [US32](../Modelagem/historias-usuario.md#US32) |
| [**RF21**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF21) | Mostrar alertas de trânsito, acidentes e rotas alternativas | [Não](../Validacao/implementado.md#RF21) | — | — | — | [EP07](../Modelagem/backlog.md#EP07) | [ELO21](../Pos-rastreabilidade/elos.md#ELO21) | [US28](../Modelagem/historias-usuario.md#US28) |
| [**RF22**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF22) | Permitir compartilhar trajeto em tempo real com outros usuários | [Não](../Validacao/implementado.md#RF22) | — | — | — | [EP08](../Modelagem/backlog.md#EP08) | [ELO22](../Pos-rastreabilidade/elos.md#ELO22) | [US33](../Modelagem/historias-usuario.md#US33) |
| [**RF23**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF23) | Exibir quantidade de assentos preferenciais e totais no ônibus | [Não](../Validacao/implementado.md#RF23) | — | — | — | [EP04](../Modelagem/backlog.md#EP04) | [ELO23](../Pos-rastreabilidade/elos.md#ELO23) | — |
| [**RF24**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF24) | Permitir favoritar linhas ou paradas para acesso rápido | [Não](../Validacao/implementado.md#RF24) | — | — | — | [EP08](../Modelagem/backlog.md#EP08) | [ELO24](../Pos-rastreabilidade/elos.md#ELO24) | [US20](../Modelagem/historias-usuario.md#US20) |
| [**RF25**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF25) | Ampliar a cobertura e exibir informações também em regiões afastadas do Distrito Federal | [Não](../Validacao/implementado.md#RF25) | [CEN08](../Modelagem/cenarios.md#CEN08) | — | [UC06](../Modelagem/casos-de-uso.md#UC06) | [EP03](../Modelagem/backlog.md#EP03) | [ELO25](../Pos-rastreabilidade/elos.md#ELO25) | [US21](../Modelagem/historias-usuario.md#US21) |
| [**RF26**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF26) | Filtrar ônibus por empresa operadora | [Não](../Validacao/implementado.md#RF26) | — | — | — | [EP02](../Modelagem/backlog.md#EP02) | [ELO26](../Pos-rastreabilidade/elos.md#ELO26) | [US01](../Modelagem/historias-usuario.md#US01) |
| [**RF27**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF27) | Visualizar quais veículos estão em operação no momento | [Não](../Validacao/implementado.md#RF27) | — | — | — | [EP01](../Modelagem/backlog.md#EP01) | [ELO27](../Pos-rastreabilidade/elos.md#ELO27) | [US35](../Modelagem/historias-usuario.md#US35) |
| [**RF28**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF28) | Permitir avaliação da qualidade do serviço de cada linha | [Não](../Validacao/implementado.md#RF28) | [CEN02](../Modelagem/cenarios.md#CEN02) | — | [UC01](../Modelagem/casos-de-uso.md#UC01) | [EP05](../Modelagem/backlog.md#EP05) | [ELO28](../Pos-rastreabilidade/elos.md#ELO28) | [US03](../Modelagem/historias-usuario.md#US03) |
| [**RF29**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF29) | Sistema de gamificação para incentivar uso do transporte público | [Não](../Validacao/implementado.md#RF29) | — | — | — | [EP12](../Modelagem/backlog.md#EP12) | [ELO29](../Pos-rastreabilidade/elos.md#ELO29) | [US36](../Modelagem/historias-usuario.md#US36) |
| [**RF30**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF30) | Previsão inteligente de horários baseada em dados históricos e machine learning | [Não](../Validacao/implementado.md#RF30) | [CEN10](../Modelagem/cenarios.md#CEN10) | — | [UC10](../Modelagem/casos-de-uso.md#UC10) | [EP07](../Modelagem/backlog.md#EP07) | [ELO30](../Pos-rastreabilidade/elos.md#ELO30) | [US31](../Modelagem/historias-usuario.md#US31) |
| [**RF31**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF31) | Sistema de recompensas por uso sustentável do transporte público | [Não](../Validacao/implementado.md#RF31) | — | — | — | [EP12](../Modelagem/backlog.md#EP12) | [ELO31](../Pos-rastreabilidade/elos.md#ELO31) | [US09](../Modelagem/historias-usuario.md#US09) |
| [**RF32**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF32) | Exibir relatórios de impacto ambiental (CO₂ economizado) | [Não](../Validacao/implementado.md#RF32) | — | — | — | [EP14](../Modelagem/backlog.md#EP14) | [ELO32](../Pos-rastreabilidade/elos.md#ELO32) | [US10](../Modelagem/historias-usuario.md#US10) |
| [**RF33**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF33) | Suporte a comandos de voz para facilitar interação durante deslocamentos | [Não](../Validacao/implementado.md#RF33) | — | — | — | [EP04](../Modelagem/backlog.md#EP04) | [ELO33](../Pos-rastreabilidade/elos.md#ELO33) | [US34](../Modelagem/historias-usuario.md#US34) |
| [**RF34**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF34) | Integração com assistentes virtuais (Alexa, Google Assistant) | [Não](../Validacao/implementado.md#RF34) | — | — | — | [EP15](../Modelagem/backlog.md#EP15) | [ELO34](../Pos-rastreabilidade/elos.md#ELO34) | [US18](../Modelagem/historias-usuario.md#US18) |
| [**RF35**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF35) | Permitir rastreamento de múltiplas linhas de ônibus simultaneamente no mapa | [Não](../Validacao/implementado.md#RF35) | [CEN03](../Modelagem/cenarios.md#CEN03) | — | [UC03](../Modelagem/casos-de-uso.md#UC03) | [EP01](../Modelagem/backlog.md#EP01) | [ELO35](../Pos-rastreabilidade/elos.md#ELO35) | [US04](../Modelagem/historias-usuario.md#US04) |
| [**RF36**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF36) | Oferecer suporte multilíngue (português e inglês, no mínimo) | [Não](../Validacao/implementado.md#RF36) | — | — | — | [EP16](../Modelagem/backlog.md#EP16) | [ELO36](../Pos-rastreabilidade/elos.md#ELO36) | [US19](../Modelagem/historias-usuario.md#US19) |
| [**RF37**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RF37) | Permitir cadastro, login e autenticação de usuários no sistema | [Não](../Validacao/implementado.md#RF37) | — | — | [UC01](../Modelagem/casos-de-uso.md#UC01) | [EP08](../Modelagem/backlog.md#EP08) | [ELO37](../Pos-rastreabilidade/elos.md#ELO37) | [US32](../Modelagem/historias-usuario.md#US32) |

---

## Requisitos Não Funcionais

| **ID** | **Requisito** | **Implementado** | **Cenário** | **Léxico** | **Caso de Uso** | **Épico** | **Elos** | **História de Usuário** |
|:------:|:---------------|:----------------:|:-----------:|:----------:|:---------------:|:---------:|:--------:|:-----------------------:|
| [**RNF01**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RNF01) | As informações de horários e localização dos ônibus devem ser precisas | [Não](../Validacao/implementado.md#RNF01) | — | — | — | [EP01](../Modelagem/backlog.md#EP01) | [ELO38](../Pos-rastreabilidade/elos.md#ELO38) | — |
| [**RNF02**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RNF02) | Rastreamento dos ônibus em tempo real deve ser confiável e sem falhas | [Não](../Validacao/implementado.md#RNF02) | — | — | — | [EP01](../Modelagem/backlog.md#EP01) | [ELO39](../Pos-rastreabilidade/elos.md#ELO39) | — |
| [**RNF03**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RNF03) | Tempo de atualização da localização ≤ 20 segundos | [Não](../Validacao/implementado.md#RNF03) | — | — | — | [EP01](../Modelagem/backlog.md#EP01) | [ELO40](../Pos-rastreabilidade/elos.md#ELO40) | — |
| [**RNF04**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RNF04) | Interface acessível para idosos e pessoas com deficiência visual | [Não](../Validacao/implementado.md#RNF04) | — | — | — | [EP04](../Modelagem/backlog.md#EP04) | [ELO41](../Pos-rastreabilidade/elos.md#ELO41) | — |
| [**RNF05**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RNF05) | Sistema de notificação com som e vibração configuráveis | [Não](../Validacao/implementado.md#RNF05) | — | — | — | [EP19](../Modelagem/backlog.md#EP19) | [ELO42](../Pos-rastreabilidade/elos.md#ELO42) | — |
| [**RNF06**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RNF06) | Baixo consumo de bateria e dados móveis | [Não](../Validacao/implementado.md#RNF06) | — | — | — | [EP17](../Modelagem/backlog.md#EP17) | [ELO43](../Pos-rastreabilidade/elos.md#ELO43) | — |
| [**RNF07**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RNF07) | Compatibilidade com dispositivos Android e iOS | [Não](../Validacao/implementado.md#RNF07) | — | — | — | [EP19](../Modelagem/backlog.md#EP19) | [ELO44](../Pos-rastreabilidade/elos.md#ELO44) | — |
| [**RNF08**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RNF08) | Proteção contra reportes falsos de lotação (mecanismo de confiança) | [Não](../Validacao/implementado.md#RNF08) | — | — | — | [EP05](../Modelagem/backlog.md#EP05) | [ELO45](../Pos-rastreabilidade/elos.md#ELO45) | — |
| [**RNF09**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RNF09) | Dados de localização e pessoais protegidos conforme LGPD | [Não](../Validacao/implementado.md#RNF09) | — | — | — | [EP21](../Modelagem/backlog.md#EP21) | [ELO46](../Pos-rastreabilidade/elos.md#ELO46) | — |
| [**RNF10**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RNF10) | Tempo de carregamento da tela principal < 3 segundos | [Não](../Validacao/implementado.md#RNF10) | — | — | — | [EP17](../Modelagem/backlog.md#EP17) | [ELO47](../Pos-rastreabilidade/elos.md#ELO47) | — |
| [**RNF11**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RNF11) | Funcionamento offline para consulta a rotas salvas e horários | [Não](../Validacao/implementado.md#RNF11) | [CEN05](../Modelagem/cenarios.md#CEN05) | — | [UC07](../Modelagem/casos-de-uso.md#UC07) | [EP03](../Modelagem/backlog.md#EP03) | [ELO48](../Pos-rastreabilidade/elos.md#ELO48) | [US26](../Modelagem/historias-usuario.md#US26) |
| [**RNF12**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RNF12) | Integração segura com sistemas de pagamento (recarga de cartão) | [Não](../Validacao/implementado.md#RNF12) | — | — | — | [EP07](../Modelagem/backlog.md#EP07) | [ELO49](../Pos-rastreabilidade/elos.md#ELO49) | — |
| [**RNF13**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RNF13) | Alta disponibilidade do sistema (≥ 98% uptime) | [Não](../Validacao/implementado.md#RNF13) | — | — | — | [EP20](../Modelagem/backlog.md#EP20) | [ELO50](../Pos-rastreabilidade/elos.md#ELO50) | — |
| [**RNF14**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RNF14) | Suporte a múltiplos usuários simultâneos sem lentidão | [Não](../Validacao/implementado.md#RNF14) | — | — | — | [EP22](../Modelagem/backlog.md#EP22) | [ELO51](../Pos-rastreabilidade/elos.md#ELO51) | — |
| [**RNF15**](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#RNF15) | Personalização da interface com base em preferências do usuário | [Não](../Validacao/implementado.md#RNF15) | — | — | — | [EP18](../Modelagem/backlog.md#EP18) | [ELO52](../Pos-rastreabilidade/elos.md#ELO52) | — |


# 🔁 Rastreabilidade Forward-From

??? info "RNF01 – As informações de horários e localização dos ônibus devem ser precisas"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 1: Rastreamento e Informações em Tempo Real | | |
    |**História de Usuário** | *Não identificada* | | |
    |**Léxico** | *Não identificado* | | |
    |**Casos de Uso** | *Não identificados* | | |
    |**Cenários** | *Não identificados* | | |
    |**Artefatos de Elicitação** | ENT09 | | |

??? info "RNF02 – Rastreamento dos ônibus em tempo real deve ser confiável e sem falhas"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 1: Rastreamento e Informações em Tempo Real | | |
    |**História de Usuário** | *Não identificada* | | |
    |**Léxico** | *Não identificado* | | |
    |**Casos de Uso** | *Não identificados* | | |
    |**Cenários** | *Não identificados* | | |
    |**Artefatos de Elicitação** | ENT13 | | |

??? info "RNF03 – Tempo de atualização da localização ≤ 20 segundos"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 1: Rastreamento e Informações em Tempo Real | | |
    |**História de Usuário** | *Não identificada* | | |
    |**Léxico** | *Não identificado* | | |
    |**Casos de Uso** | *Não identificados* | | |
    |**Cenários** | *Não identificados* | | |
    |**Artefatos de Elicitação** | *Não identificado* | | |

    
??? info "RNF04 – Interface acessível para idosos e pessoas com deficiência visual"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 1: Rastreamento e Informações em Tempo Real | | |
    |**História de Usuário** | *Não identificada* | | |
    |**Léxico** | *Não identificado* | | |
    |**Casos de Uso** | *Não identificados* | | |
    |**Cenários** | *Não identificados* | | |
    |**Artefatos de Elicitação** | ENT09 | | | 

??? info "RNF05 – Sistema de notificação com som e vibração configuráveis"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 1: Rastreamento e Informações em Tempo Real | | |
    |**História de Usuário** | *Não identificada* | | |
    |**Léxico** | *Não identificado* | | |
    |**Casos de Uso** | *Não identificados* | | |
    |**Cenários** | *Não identificados* | | |
    |**Artefatos de Elicitação** | ENT09 | | |

??? info "RF01 – Exibir a localização dos ônibus em tempo real no mapa"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 1: Rastreamento e Informações em Tempo Real | | |
    |**História de Usuário** | US15 | | |
    |**Léxico** | L12: Tempo real | | |
    |**Casos de Uso** | UC03 | | |
    |**Cenários** | CEN03 | | |
    |**Artefatos de Elicitação** | RF01 (Análise de Documentos), ENT03 | | |

??? info "RF02 – Mostrar o tempo estimado de chegada do ônibus à parada"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 1: Rastreamento e Informações em Tempo Real | | |
    |**História de Usuário** | US16 | | |
    |**Léxico** | L09: Agora | | |
    |**Casos de Uso** | UC02 | | |
    |**Cenários** | CEN01 | | |
    |**Artefatos de Elicitação** | ENT04 | | |

??? info "RF03 – Permitir planejamento de viagem com rotas sugeridas"

    *Autoria: *
    
    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 7: Planejamento de Viagens | | |
    |**História de Usuário** | US17 | | |
    |**Léxico** | L05: Planejar | | |
    |**Casos de Uso** | UC09 | | |
    |**Cenários** | CEN09 | | |
    |**Artefatos de Elicitação** | RF05 (Análise de Documentos) | | |

??? info "RF04 – Permitir pesquisa por linhas e rotas de ônibus"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 2: Filtragem | | |
    |**História de Usuário** | US18 | | |
    |**Léxico** | L11: Pesquisar | | |
    |**Casos de Uso** | *Não identificados* | | |
    |**Cenários** | *Não identificados* | | |
    |**Artefatos de Elicitação** | RF02 (Análise de Documentos), ENT01 | | |

??? info "RF05 – Apresentar horários de saída e chegada dos transportes"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 1: Rastreamento e Informações em Tempo Real | | |
    |**História de Usuário** | US05, US19 | | |
    |**Léxico** | L09: Agora | | |
    |**Casos de Uso** | *Não identificados* | | |
    |**Cenários** | *Não identificados* | | |
    |**Artefatos de Elicitação** | ENT02 | | |

??? info "RF13 – Oferecer recarga de cartão de transporte (ex.: integração com BRB Mobilidade)"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 1: Rastreamento e Informações em Tempo Real | | |
    |**História de Usuário** | *Não identificada* | | |
    |**Léxico** | *Não identificado* | | |
    |**Casos de Uso** | *Não identificados* | | |
    |**Cenários** | *Não identificados* | | |
    |**Artefatos de Elicitação** | ENT09 | | |

??? info "RF14 – Permitir integração com o cartão de transporte, incluindo saldo e recarga"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 1: Rastreamento e Informações em Tempo Real | | |
    |**História de Usuário** | *Não identificada* | | |
    |**Léxico** | *Não identificado* | | |
    |**Casos de Uso** | *Não identificados* | | |
    |**Cenários** | *Não identificados* | | |
    |**Artefatos de Elicitação** | ENT09 | | |

??? info "RF15 – Manter histórico de viagens do usuário"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 1: Rastreamento e Informações em Tempo Real | | |
    |**História de Usuário** | *Não identificada* | | |
    |**Léxico** | *Não identificado* | | |
    |**Casos de Uso** | *Não identificados* | | |
    |**Cenários** | *Não identificados* | | |
    |**Artefatos de Elicitação** | ENT09 | | |

??? info "RF16 – Permitir reportar problemas (motorista, ônibus, cobrança) com dados do veículo e horário"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 1: Rastreamento e Informações em Tempo Real | | |
    |**História de Usuário** | *Não identificada* | | |
    |**Léxico** | *Não identificado* | | |
    |**Casos de Uso** | *Não identificados* | | |
    |**Cenários** | *Não identificados* | | |
    |**Artefatos de Elicitação** | ENT09 | | |

??? info "RF19 – Disponibilizar versão web leve para acesso rápido em pontos de ônibus (via QR Code)"

    *Autoria: Gabriel Maciel*

    |**Elemento** | **Artefatos Relacionados** | Tipo de Elo | Justificativa |
    |:-- | :-- | :--| :-- |
    |**Épico** | [Épico 3: Acessibilidade](../modelagem_requisitos_02/backlog.md#épico-3-acessibilidade) | Agregação | Épico 3 agrega e compõe o requisito RF19 como parte de sua estrutura |
    |**História de Usuário** | [US02](../modelagem_requisitos_02/historias_de_usuario.md#us02---acesso-web-rápido-via-qr-code) | Representação | US02 representa a implementação detalhada do RF19 em termos de funcionalidade do usuário |
    |**Léxico** | *Não identificado* | | |
    |**Casos de Uso** | [UC07](../modelagem_requisitos_01/casos_de_uso.md#tabela-8---uc07-modo-off-line-requisito-não-implementado) | Representação | UC07 modela e representa o fluxo de interação para acessar a versão web via QR Code |
    |**Cenários** | [Cenário 5](../modelagem_requisitos_01/cenarios.md#cenário-5---modo-off-line-requisito-não-implementado) | Representação | Cenário 5 descreve uma situação concreta onde o RF19 é utilizado |
    |**Artefatos de Elicitação** | [Brainstorm (BRS17)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Satisfação | BRS17 é a fonte de elicitação que satisfaz e fundamenta a necessidade do RF19 |

??? info "RF24 – Permitir favoritar linhas ou paradas para acesso rápido"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 1: Rastreamento e Informações em Tempo Real | | |
    |**História de Usuário** | *Não identificada* | | |
    |**Léxico** | *Não identificado* | | |
    |**Casos de Uso** | *Não identificados* | | |
    |**Cenários** | *Não identificados* | | |
    |**Artefatos de Elicitação** | ENT09 | | |

??? info "RF25 – Ampliar a cobertura e exibir informações também em regiões afastadas do Distrito Federal"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 1: Rastreamento e Informações em Tempo Real | | |
    |**História de Usuário** | *Não identificada* | | |
    |**Léxico** | *Não identificado* | | |
    |**Casos de Uso** | *Não identificados* | | |
    |**Cenários** | *Não identificados* | | |
    |**Artefatos de Elicitação** | ENT09 | | |

??? info "RF26 – Filtrar ônibus por empresa operadora"

    *Autoria: Gabriel Maciel*

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :--| :-- |
    |**Épico** | [Épico 2: Filtragem](../modelagem_requisitos_02/backlog.md#epico-2-filtragem) | Agregação | Épico 2 agrega e compõe o requisito RF26 como parte de sua estrutura |
    |**História de Usuário** | [US01](../modelagem_requisitos_02/historias_de_usuario.md#us01-filtrar-onibus-por-empresa-operadora) | Representação | US01 representa a implementação detalhada do RF26 em termos de funcionalidade do usuário |
    |**Léxico** | *Não identificado* | — | — |
    |**Casos de Uso** | *Não identificados* | — | — |
    |**Cenários** | *Não identificados* | — | — |
    |**Artefatos de Elicitação** | [Análise de Documentos (RF03)](../Elicitacao/elicitacao_analise_documentos.md#requisitos-funcionais) | Satisfação | RF03 é a fonte de elicitação que satisfaz e fundamenta a necessidade do RF26 |

??? info "RF30 – Previsão inteligente de horários baseada em dados históricos e machine learning"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 7: Planejamento de Viagens | | |
    |**História de Usuário** | US31 | | |
    |**Léxico** | *Não identificado* | | |
    |**Casos de Uso** | UC10 | | |
    |**Cenários** | CEN10 | | |
    |**Artefatos de Elicitação** | BRS02 | | |

??? info "RF37 – Permitir cadastro, login e autenticação de usuários no sistema"

    *Autoria: *

    |**Elemento** | **Artefatos Relacionados** | **Tipo de Elo** | **Justificativa** |
    |:-- | :-- | :-- | :-- |
    |**Épico** | Épico 8: Gestão de Usuário e Conta | | |
    |**História de Usuário** | US32 | | |
    |**Léxico** | *Não identificado* | | |
    |**Casos de Uso** | UC01 | | |
    |**Cenários** | *Não identificados* | | |
    |**Artefatos de Elicitação** | BRS18 | | |


## Tabela de Contribuição

|        Nome          | Contribuição|
|----------------------|-------------|
| Cauã Nicolas         | A preencher |
| Daniel Nunes Duarte  | A preencher |
| Fernanda Vaz         | A preencher |
| Gabriel Maciel       | A preencher |
| João Gabriel         | Adição RNF1 ao RNF3 e RF01 ao RF05, RF37, RF30 |
| João Ramos           | A preencher |

## Referência bibliográfica 


> <sup>1.</sup>
<a id="ref-1"></a>
> TORANZO, M.; CASTRO, J; MELLO, E. Uma proposta para melhorar o rastreamento de requisitos. PUC-Rio: Workshop em Engenharia de Requisitos, Rio de Janeiro, 2002. Disponível em: http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/toranzo.pdf. Acesso em: 28 de Out de 2025.

> 
## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|:-------:|:-----:|:-----------|:------------|:-------------|
| 1.0 | 25/10 | Criação inicial do documento | Gabriel Maciel | FERNANDA |
| 1.1 | 26/10 | Adição RNF1 - RNF3 e RF01 - RF05, RF37, RF30 | João Gabriel | Gabriel Maciel |

## Agradecimentos

>Agradecemos o suporte da ferramenta de Inteligência Artificial Generativa Google Gemini no desenvolvimento deste trabalho. Em conformidade com o Código de Conduta da Sociedade Brasileira de Computação (SBC), declaramos que a ferramenta foi utilizada como auxílio na revisão gramatical e estilística do texto, na sugestão de estrutura para seções específicas do artigo, bem como na formatação de tabelas e na descrição de figuras. Ressaltamos que os autores assumem total responsabilidade por todo o conteúdo apresentado, incluindo sua originalidade e precisão. A ferramenta não figura como autora desta publicação.
