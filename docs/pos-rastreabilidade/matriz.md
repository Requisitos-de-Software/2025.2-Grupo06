# Matriz de Pós-Rastreabilidade

## Introdução

A matriz de Pós-Rastreabilidade tem como objetivo demonstrar o relacionamento entre os requisitos elicitados e os artefatos gerados nas etapas posteriores do processo de desenvolvimento, como cenários, casos de uso, épicos, protótipos e testes.Ela funciona como uma tabela que conecta as necessidades do cliente aos entregáveis do projeto, garantindo que cada requisito identificado possua uma implementação ou representação nos artefatos seguintes. Dessa forma, assegura-se a completude, consistência e validação do sistema em relação às expectativas do usuário e aos objetivos de negócio.



## Metodologia

A metodologia adotada para a construção da matriz de pós-rastreabilidade consiste em:

1. **Identificação dos Requisitos**  
   Todos os requisitos funcionais (RF) e não funcionais (RNF) foram previamente elicitados a partir de técnicas como **Análise de Documentos**, **Entrevistas** e **Brainstorming**.

2. **Mapeamento dos Artefatos**  
   Cada requisito foi rastreado até os artefatos que o representam, incluindo:
   - **Cenários** [`cenarios.md`](../modelagem_requisitos_01/cenarios.md);
   - **Casos de Uso** [`casos_de_uso.md`](../modelagem_requisitos_01/casos_de_uso.md);
   - **Épicos**  [`backlog.md`](../modelagem_requisitos_02/backlog.md);
   - **Requisitos Não Funcionais** relacionados a **NFR Frameworks** [`nfr.md`](../modelagem_requisitos_02/nfr.md).

---


## Tabela de Contribuição

|        Nome          | Contribuição|
|----------------------|-------------|
| Cauã Nicolas         | Revisão|
| Daniel Nunes Duarte  | Adição de RF17, RF20, RF22, RF27, RF29, RF33, RNF14 e RNF15; atualização da Matriz de Pós-Rastreabilidade |
| Fernanda Vaz         | Elaboração da tabela e dos intens |
| Gabriel Maciel       | Revisão|
| João Gabriel         |Revisão |
| João Ramos           |Revisão |



## Tabela de Pós-Rastreabilidade

| ID | Descrição do Requisito | Classificação da Fonte | Tipo de Elo | Épico / Artefato Relacionado | Cenário | Caso de Uso | Autor(a) |
|:--:|:--|:--:|:--:|:--|:--|:--|:--|
| [RF01](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rf01) | Exibir a localização dos ônibus em tempo real no mapa | Ambiental | Representação | [Épico 1 – Rastreamento e Informações em Tempo Real](../modelagem_requisitos_02/backlog.md#épico-1---rastreamento-e-informações-em-tempo-real) | — | [UC01 – Localização em Tempo Real](../modelagem_requisitos_01/casos_de_uso.md#tabela-1---uc01-localização-em-tempo-real) | João Gabriel |
| [RF02](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rf02) | Mostrar o tempo estimado de chegada do ônibus à parada | Ambiental | Representação | [Épico 1](../modelagem_requisitos_02/backlog.md#épico-1---rastreamento-e-informações-em-tempo-real) | [Cenário 1 – Notificações de Chegada](../modelagem_requisitos_01/cenarios.md#cenário-1---notificações-de-chegada) | [UC02 – Tempo Estimado de Chegada](../modelagem_requisitos_01/casos_de_uso.md#tabela-2---uc02-tempo-estimado-de-chegada) | João Gabriel |
| [RF03](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rf03) | Permitir planejamento de viagem com rotas sugeridas | Organizacional | Satisfação | [Épico 7 – Planejamento de Viagens](../modelagem_requisitos_02/backlog.md#épico-7---planejamento-de-viagens) | [Cenário 9 – Planejamento de Viagens](../modelagem_requisitos_01/cenarios.md#cenário-9---planejamento-de-viagens) | [UC09 – Planejamento de Viagem](../modelagem_requisitos_01/casos_de_uso.md#tabela-9---uc09-planejamento-de-viagens) | João Gabriel |
| [RF04](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rf04) | Permitir pesquisa por linhas e rotas de ônibus | Ambiental | Representação | [Épico 2 – Filtragem de Linhas](../modelagem_requisitos_02/backlog.md#épico-2---filtragem-de-linhas) | — | [UC04 – Busca por Linhas](../modelagem_requisitos_01/casos_de_uso.md#tabela-4---uc04-busca-por-linhas) | João Gabriel |
| [RF05](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rf05) | Apresentar horários de saída e chegada dos transportes | Ambiental | Representação | [Épico 1](../modelagem_requisitos_02/backlog.md#épico-1---rastreamento-e-informações-em-tempo-real) | — | — | João Gabriel |
| [RF06](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rf06) | Oferecer um mapa interativo com os pontos de ônibus e linhas correspondentes | Desenvolvimento | Representação | [Épico 1](../modelagem_requisitos_02/backlog.md#épico-1---rastreamento-e-informações-em-tempo-real) | [Cenário 3 – Rastreamento de múltiplas linhas](../modelagem_requisitos_01/cenarios.md#cenário-3---rastreamento-de-múltiplas-linhas) | [UC03 – Rastreamento de múltiplas linhas](../modelagem_requisitos_01/casos_de_uso.md#tabela-5---uc03-rastreamento-de-múltiplas-linhas-requisito-não-implementado) | Fernanda Vaz |
| [RF07](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rf07) | Integrar informações de outros modais (metrô, ônibus) em rotas multimodais | Ambiental | Agregação | [Épico 7 – Planejamento de Viagens](../modelagem_requisitos_02/backlog.md#épico-7---planejamento-de-viagens) | [Cenário 12 – Integração ônibus e metrô](../modelagem_requisitos_01/cenarios.md#cenário-12---integração-ônibus-e-metrô) | — | Fernanda Vaz |
| [RF08](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rf08) | Exibir informações de acessibilidade do ônibus | Ambiental | Representação | [Épico 3 – Acessibilidade e Usabilidade](../modelagem_requisitos_02/backlog.md#épico-3---acessibilidade-e-usabilidade) | [Cenário 1 – Notificações de Chegada](../modelagem_requisitos_01/cenarios.md#cenário-1---notificações-de-chegada) | — | Fernanda Vaz |
| [RF09](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rf09) | Indicar lotação do ônibus | Ambiental | Representação | [Épico 4 – Avaliar e Reportar](../modelagem_requisitos_02/backlog.md#épico-4---avaliar-e-reportar) | [Cenário 6 – Reportar Lotação](../modelagem_requisitos_01/cenarios.md#cenário-6---reportar-lotação-do-ônibus) | — | João Ramos |
| [RF10](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rf10) | Permitir que usuários reportem a lotação do ônibus | Ambiental | Representação | [Épico 4](../modelagem_requisitos_02/backlog.md#épico-4---avaliar-e-reportar) | [Cenário 6](../modelagem_requisitos_01/cenarios.md#cenário-6---reportar-lotação-do-ônibus) | — | João Ramos |
| [RF11](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rf11) | Enviar notificação quando o ônibus estiver a X minutos da parada | Ambiental | Representação | [Épico 3 – Notificações e Alertas](../modelagem_requisitos_02/backlog.md#épico-3---notificações-e-alertas) | [Cenário 1](../modelagem_requisitos_01/cenarios.md#cenário-1---notificações-de-chegada) | [UC01 – Notificações de Chegada](../modelagem_requisitos_01/casos_de_uso.md#tabela-1---uc01-notificações-de-chegada) | João Ramos |
| [RF12](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rf12) | Enviar alertas sobre atrasos ou alterações de rota | Ambiental | Representação | [Épico 3](../modelagem_requisitos_02/backlog.md#épico-3---notificações-e-alertas) | [Cenário 11 – Alertas de Desvio e Interrupção](../modelagem_requisitos_01/cenarios.md#cenário-11---alertas-de-desvio-e-interrupção-de-rota) | — | João Ramos |
| [RF13](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rf13) | Oferecer recarga de cartão de transporte (BRB Mobilidade) | Desenvolvimento | Representação | [Épico 5 – Integração e Recargas](../modelagem_requisitos_02/backlog.md#épico-5---integração-e-recargas) | [Cenário 4 – Integração BRB Mobilidade](../modelagem_requisitos_01/cenarios.md#cenário-4---integração-com-brb-mobilidade) | [UC05 – Recarga de Cartão](../modelagem_requisitos_01/casos_de_uso.md#tabela-5---uc05-recarga-de-cartão) | Cauã Nicolas |
| [RF15](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rf15) | Manter histórico de viagens do usuário | Desenvolvimento | Representação | [Épico 6 – Histórico e Preferências](../modelagem_requisitos_02/backlog.md#épico-6---histórico-e-preferências) | [Cenário 7 – Histórico de Viagens](../modelagem_requisitos_01/cenarios.md#cenário-7---histórico-de-viagens) | — | Cauã Nicolas |
| [RF17](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rf17) | Exibir preço da passagem por linha ou trajeto | Gerencial | Representação | [Especificação Suplementar](../modelagem_requisitos_01/especificacao_suplementar.md) | — | — | Daniel Nunes Duarte |
| [RF19](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rf19) | Disponibilizar versão web leve para acesso rápido (QR Code) | Ambiental | Agregação | [Épico 3 – Acessibilidade](../modelagem_requisitos_02/backlog.md#épico-3---acessibilidade-e-usabilidade) | [Cenário 5 – Modo Offline](../modelagem_requisitos_01/cenarios.md#cenário-5---modo-off-line) | — | Gabriel Maciel |
| [RF20](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rf20) | Botão de pânico/emergência para alertar motorista e/ou autoridades | Ambiental | Representação | — | — | — | Daniel Nunes Duarte |
| [RF26](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rf26) | Filtrar ônibus por empresa operadora | Organizacional | Satisfação | [Épico 2 – Filtragem de Linhas](../modelagem_requisitos_02/backlog.md#épico-2---filtragem-de-linhas) | — | — | Gabriel Maciel |
| [RF27](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rf27) | Visualizar quais veículos estão em operação no momento | Organizacional | Satisfação | — | — | — | Daniel Nunes Duarte |
| [RF28](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rf28) | Avaliação da qualidade do serviço | Organizacional | Satisfação | [Épico 4](../modelagem_requisitos_02/backlog.md#épico-4---avaliar-e-reportar) | [Cenário 2 – Avaliar Linhas](../modelagem_requisitos_01/cenarios.md#cenário-2---avaliar-linhas) | — | Gabriel Maciel |
| [RF29](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rf29) | Sistema de gamificação para incentivar uso do transporte público | Desenvolvimento | Agregação | — | — | — | Daniel Nunes Duarte |
| [RF31](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rf31) | Sistema de recompensas por uso sustentável | Organizacional | Satisfação | [Épico 11 – Gamificação e Engajamento](../modelagem_requisitos_02/backlog.md#épico-11---gamificação-e-engajamento) | — | — | Fernanda Vaz |
| [RF32](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rf32) | Exibir relatórios de impacto ambiental | Organizacional | Recurso | [Épico 9 – Sustentabilidade e Impacto Ambiental](../modelagem_requisitos_02/backlog.md#épico-9---sustentabilidade-e-impacto-ambiental) | [Cenário 10](../modelagem_requisitos_01/cenarios.md#cenário-10---análise-preditiva-de-horários-dos-ônibus-com-ia) | — | Fernanda Vaz |
| [RF33](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rf33) | Suporte a comandos de voz | Ambiental | Recurso | — | — | — | Daniel Nunes Duarte |
| [RF34](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rf34) | Integração com assistentes virtuais | Gerencial | Agregação | [Épico 3 – Acessibilidade](../modelagem_requisitos_02/backlog.md#épico-3---acessibilidade-e-usabilidade) | — | — | Gabriel Maciel |
| [RF35](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rf35) | Rastrear múltiplas linhas simultaneamente | Gerencial | Representação | [Épico 1](../modelagem_requisitos_02/backlog.md#épico-1---rastreamento-e-informações-em-tempo-real) | [Cenário 3](../modelagem_requisitos_01/cenarios.md#cenário-3---rastreamento-de-múltiplas-linhas) | [UC03](../modelagem_requisitos_01/casos_de_uso.md#tabela-5---uc03-rastreamento-de-múltiplas-linhas) | Gabriel Maciel |
| [RNF06](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rnf06) | Baixo consumo de bateria e dados móveis | Desenvolvimento | Alocado | [Especificação Suplementar – Portabilidade](../modelagem_requisitos_01/especificacao_suplementar.md) | — | — | Fernanda Vaz |
| [RNF07](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rnf07) | Compatibilidade Android e iOS | Desenvolvimento | Responsabilidade | [NFR – SIG Compatibilidade](../modelagem_requisitos_02/nfr.md#sig-compatibilidade) | [Cenário 11](../modelagem_requisitos_01/cenarios.md#cenário-11---alertas-de-desvio-e-interrupção-de-rota) | — | Fernanda Vaz |
| [RNF10](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rnf10) | Tempo de carregamento da tela principal < 3s | Gerencial | Representação | [NFR – Desempenho](../modelagem_requisitos_02/nfr.md#sig-desempenho) | — | — | Gabriel Maciel |
| [RNF11](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rnf11) | Funcionamento offline | Gerencial | Representação | [NFR – RS02 Funcionamento Offline](../modelagem_requisitos_02/nfr.md#rs02-funcionamento-offline) | [Cenário 5 – Modo Offline](../modelagem_requisitos_01/cenarios.md#cenário-5---modo-off-line) | — | Gabriel Maciel |
| [RNF14](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rnf14) | Suporte a múltiplos usuários simultâneos | Ambiental | Responsabilidade | [Brainstorm (BRS15)](../Elicitacao/elicitacao_brainstorm.md#resultados) | — | — | Daniel Nunes Duarte |
| [RNF15](https://requisitos-de-software.github.io/2025.2-Grupo06/Elicitacao/elicitacao_lista_requisitos_elicitados#rnf15) | Personalização da interface | Ambiental | Recurso | [Brainstorm (BRS13)](../Elicitacao/elicitacao_brainstorm.md#resultados) | — | — | Daniel Nunes Duarte |





 *FONTE: FERNANDA VAZ, 2025*









##  Bibliográfia 

<a id="ref-1"></a>
> <sup>1.</sup>
> SAYÃO, M.; LEITE, J. C. S. P. *Rastreabilidade em Requisitos de Software*. In: **Anais do Simpósio Brasileiro de Engenharia de Software (SBES)**, 2005.

<a id="ref-2"></a>
> <sup>2.</sup>
> TORANZO, M.; CASTRO, J; MELLO, E. Uma proposta para melhorar o rastreamento de requisitos. PUC-Rio: Workshop em Engenharia de Requisitos, Rio de Janeiro, 2002. Disponível em: http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/toranzo.pdf. Acesso em: 28 de Out de 2025.

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|:-------:|:-----:|:-----------|:------------|:-------------|
| 1.0 | 25/10 | Criação inicial do documento | Gabriel Maciel | FERNANDA VAZ|
| 1.1 | 28/10 |adição de artefatos no  documento | FERNANDA VAZ | Gabriel Maciel  |
| 1.2 | 28/10 | Adição de RF17, RF20, RF22, RF27, RF29, RF33, RNF14 e RNF15 na Matriz | Daniel Nunes Duarte | --------- |


## Agradecimentos

> Agradecemos o suporte da ferramenta de Inteligência Artificial Generativa **Google Gemini** no desenvolvimento deste trabalho.  
Em conformidade com o Código de Conduta da Sociedade Brasileira de Computação (SBC), declaramos que a ferramenta foi utilizada como auxílio na revisão gramatical e estilística do texto, na sugestão de estrutura para seções específicas do artigo, bem como na formatação de tabelas e na descrição de figuras.  
Ressaltamos que os autores assumem total responsabilidade por todo o conteúdo apresentado, incluindo sua originalidade e precisão.  
A ferramenta não figura como autora desta publicação.
