# Backward-From

## Introdução

Este documento trata da "rastreabilidade para trás" (*backward-from*). Isso significa simplesmente rastrear cada requisito de volta à sua fonte. É o processo de conectar cada "o quê" (o requisito) ao seu "porquê" (a fonte que o solicitou).

---


## Metodologia

A metodologia aplicada baseia-se na análise dos artefatos de requisitos funcionais e não funcionais, associando cada requisito identificado ao documento de origem ou evidência. Essa abordagem busca manter a rastreabilidade bidirecional — tanto *forward-to* quanto *backward-from* —, conforme proposto por Sayão e Leite (2005).

Toranzo propõe que as informações que compõem o rastro de requisitos sejam organizadas em quatro níveis distintos. Esta classificação visa estruturar o contexto no qual o sistema está inserido e os artefatos gerados, garantindo que o rastreamento abarque tanto o ambiente externo quanto os detalhes internos do desenvolvimento (SAYÃO; LEITE, 2005; TORANZO et al., 2002).

Os quatro níveis de classificação são:

1. **Ambiental**: Engloba as informações que têm origem no contexto ambiental mais amplo onde a organização está inserida e que podem impactar o sistema em desenvolvimento.
2. **Organizacional**: Reúne informações pertencentes à própria organização, tais como sua missão, objetivos e estratégias, que influenciam os requisitos do sistema.
3. **Gerencial**: Agrega as informações cruciais para a gerência do projeto, auxiliando na associação de tarefas aos requisitos.
4. **Desenvolvimento**: Envolve as informações associadas aos artefatos gerados ao longo do processo de desenvolvimento, incluindo documentos de requisitos, diagramas, códigos, e casos de teste.

Ao enfatizar os níveis ambiental, organizacional e gerencial, Toranzo confere uma atenção especial aos aspectos gerenciais e contextuais do projeto, o que é visto como uma contribuição importante de sua proposta.

O meta-modelo de Toranzo estabelece um conjunto de elos de rastreabilidade que definem os tipos de relacionamentos entre os elementos rastreados. A seguir, apresentam-se os principais elos:

1. **Satisfação**: Indica que a classe de origem possui uma dependência de satisfação com a classe de destino.
2. **Recurso**: 	
A classe de origem demonstra dependência de recurso em relação à classe de destino.
3. **Responsabilidade**: 	
Registra a participação, a responsabilidade e a ação de pessoas sobre os artefatos do projeto.
4. **Representação**: Captura como os requisitos ou outros elementos são modelados ou representados em diferentes linguagens.
5. **Alocado**: 	
A classe de origem está relacionada a uma classe de destino que geralmente representa um subsistema.
6. **Agregação**: 	
Indica a composição de elementos, ou seja, que um elemento é composto por outros.

---

## Tabela de Rastreabilidade Backward-From

A tabela de rastreabilidade backward-from, apresentada neste documento, operacionaliza estes quatro níveis de Toranzo ao mapear cada requisito de volta às suas fontes de origem. Cada linha da tabela representa um requisito do sistema (nível Desenvolvimento) e seus relacionamentos com informações dos níveis Ambiental (contexto externo, stakeholders), Organizacional (objetivos do negócio) e Gerencial (pessoas responsáveis, tarefas associadas). Por meio dos elos de rastreabilidade (Satisfação, Recurso, Responsabilidade, Representação, Alocado e Agregação), estabelece-se um mapeamento explícito que permite identificar não apenas "o quê" foi requisitado, mas também "por quê" foi requisitado e "quem" está envolvido em sua execução. Desta forma, a tabela funciona como um artefato central que documenta e valida a rastreabilidade bidirecional entre requisitos e suas origens, garantindo conformidade com os princípios propostos por Toranzo e Sayão & Leite.

### Legendas

- RF: Requisito Funcional
- RNF: Requisito Não Funcional
- ENT: Entrevista
- RNI: Requisitos Não Implementados

  
| ID do Requisito | Descrição do Requisito | Fonte/Origem | Classificação da Fonte | Tipo de Elo | Autoria |
|-----------------|------------------------|--------------|------------------------|-------------|---------|
|[RF01](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf01) | Exibir a localização dos ônibus em tempo real no mapa | [Análise de Documentos (RF01)](../Elicitacao/elicitacao_analise_documentos.md#requisitos-funcionais), [Entrevista (ENT03)](../Elicitacao/elicitacao_entrevista.md#resultados) | Ambiental | Agregação | João Gabriel |
| [RF02](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf02) | Mostrar o tempo estimado de chegada do ônibus à parada | [Entrevista (ENT04)](../Elicitacao/elicitacao_entrevista.md#resultados) | Ambiental | Representação | João Gabriel |
| [RF03](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf03) | Permitir planejamento de viagem (origem → destino) com rotas sugeridas | [Análise de Documentos (RNI02)](../Elicitacao/elicitacao_analise_documentos.md#requisitos-nao-implementados) | Organizacional | Satisfação | João Gabriel |
| [RF04](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf04) | Permitir pesquisa por linhas e rotas de ônibus | [Análise de Documentos (RF02)](../Elicitacao/elicitacao_analise_documentos.md#requisitos-funcionais), [Entrevista (ENT01)](../Elicitacao/elicitacao_entrevista.md#resultados) | Ambiental | Agregação | João Gabriel |
| [RF05](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf05) | Apresentar horários de saída e chegada dos transportes | [Entrevista (ENT02)](../Elicitacao/elicitacao_entrevista.md#resultados) | Ambiental | Representação | João Gabriel |
| [RF06](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf06) | Oferecer um mapa interativo com os pontos de ônibus | [Entrevista (ENT06)](../Elicitacao/elicitacao_entrevista.md#resultados) | Desenvolvimento | Representação | Fernanda Vaz |
| [RF07](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf07) | Integrar informações de outros modais | [Brainstorm (BRS04)](../Elicitacao/elicitacao_brainstorm.md#resultados), [Análise de Documentos (RNI02)](../Elicitacao/elicitacao_analise_documentos.md#requisitos-nao-implementados) | Ambiental | Agregação | Fernanda Vaz |
| [RF08](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf08) | Exibir informações de acessibilidade | [Entrevista (ENT16)](../Elicitacao/elicitacao_entrevista.md#resultados) | Ambiental | Satisfação | Fernanda Vaz |
| [RF09](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf09) | Indicar lotação do ônibus | [Entrevista (ENT11)](../Elicitacao/elicitacao_entrevista.md#resultados), [Brainstorm (BRS07)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Ambiental | Representação | João Ramos |
| [RF10](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf10) | Reporte colaborativo de lotação | [Entrevista (ENT11)](../Elicitacao/elicitacao_entrevista.md#resultados), [Brainstorm (BRS03)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Ambiental | Representação | João Ramos |
| [RF11](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf11) | Notificações de chegada | [Análise de Documentos (RNI01)](../Elicitacao/elicitacao_analise_documentos.md#requisitos-nao-implementados), [Entrevista (ENT15)](../Elicitacao/elicitacao_entrevista.md#resultados), [Brainstorm (BRS05)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Ambiental | Representação | João Ramos |
| [RF12](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf12) | Alertas de atrasos | [Entrevista (ENT05)](../Elicitacao/elicitacao_entrevista.md#resultados), [Brainstorm (BRS05)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Ambiental | Representação | João Ramos |
| [RF13](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf13) | Recarga de cartão | [Entrevista (ENT07)](../Elicitacao/elicitacao_entrevista.md#resultados) | Desenvolvimento | Representação | Cauã Nicolas |
| [RF14](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf14) | Integração com cartão | [Entrevista (ENT07)](../Elicitacao/elicitacao_entrevista.md#resultados) | Desenvolvimento | Representação | Cauã Nicolas |
| [RF15](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf15) | Histórico de viagens | [Análise de Documentos (RNI03)](../Elicitacao/elicitacao_analise_documentos.md#requisitos-nao-implementados) | Desenvolvimento | Representação | Cauã Nicolas |
| [RF16](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf16) | Reportar problemas | [Entrevista (ENT20)](../Elicitacao/elicitacao_entrevista.md#resultados) | Desenvolvimento | Representação | Cauã Nicolas |
| [RF17](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf17) | Preço da passagem | [Brainstorm (BRS19)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Gerencial | Representação | Daniel Nunes |
| [RF18](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf18) | Linhas por parada | [Brainstorm (BRS05)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Ambiental | Representação | João Ramos |
| [RF19](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf19) | Versão web leve | [Brainstorm (BRS17)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Ambiental |  | Gabriel Maciel |
| [RF20](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf20) | Botão de pânico | [Brainstorm (BRS21)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Ambiental | Representação | Daniel Nunes |
| [RF21](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf21) | Alertas de trânsito | [Brainstorm (BRS12)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Ambiental | Representação | João Ramos |
| [RF22](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf22) | Compartilhar trajeto | [Brainstorm (BRS20)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Ambiental | Representação | Daniel Nunes |
| [RF23](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf23) | Assentos preferenciais |  |  |  |  |
| [RF24](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf24) | Favoritar linhas | [Entrevista (ENT14)](../Elicitacao/elicitacao_entrevista.md#resultados) | Desenvolvimento | Representação | Cauã Nicolas |
| [RF25](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf25) | Informações em regiões afastadas | [Entrevista (ENT08)](../Elicitacao/elicitacao_entrevista.md#resultados) | Desenvolvimento | Representação | Cauã Nicolas |
| [RF26](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf26) | Filtrar por empresa | [Análise de Documentos (RF03)](../Elicitacao/elicitacao_analise_documentos.md#requisitos-funcionais) | Organizacional | Satisfação | Gabriel Maciel |
| [RF27](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf27) | Veículos em operação | [Análise de Documentos (RN04)](../Elicitacao/elicitacao_analise_documentos.md#requisitos-nao-implementados) | Organizacional | Satisfação | Daniel Nunes |
| [RF28](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf28) | Avaliação de linhas | [Análise de Documentos (RNI04)](../Elicitacao/elicitacao_analise_documentos.md#requisitos-nao-implementados) | Organizacional | Satisfação | Gabriel Maciel |
| [RF29](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf29) | Gamificação | [Brainstorm (BRS01)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Desenvolvimento | Agregação | Daniel Nunes |
| [RF30](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf30) | Previsão inteligente | [BRS02](../Elicitacao/elicitacao_brainstorm.md#resultados) | Ambiental | Satisfação | João Gabriel |
| [RF31](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf31) | Recompensas sustentáveis | [Brainstorm (BRS09)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Organizacional | Satisfação | Fernanda Vaz |
| [RF32](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf32) | Impacto ambiental | [Brainstorm (BRS11)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Organizacional | Recurso | Fernanda Vaz |
| [RF33](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf33) | Comandos de voz | [Brainstorm (BRS14)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Ambiental | Recurso | Daniel Nunes |
| [RF34](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf34) | Assistentes virtuais | [Brainstorm (BRS16)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Gerencial | Representação | Gabriel Maciel |
| [RF35](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf35) | Rastreamento múltiplo | [Entrevista (ENT12)](../Elicitacao/elicitacao_entrevista.md#resultados) | Gerencial | Representação | Gabriel Maciel |
| [RF36](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf36) | Suporte multilíngue | [Entrevista (ENT22)](../Elicitacao/elicitacao_entrevista.md#resultados) | Gerencial | Representação | Gabriel Maciel |
| [RF37](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf37) | Cadastro e login | [Brainstorm (BRS18)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Ambiental | Satisfação | João Gabriel |
| [RF38](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf38) | Linhas com ar-condicionado | [Brainstorm (BRS20)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Ambiental |  | Gabriel Maciel |
| [RNF01](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rnf01) | Precisão das informações | [Entrevista (ENT09)](../Elicitacao/elicitacao_entrevista.md#resultados) | Ambiental | Satisfação | João Gabriel |
| [RNF02](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rnf02) | Rastreamento confiável | [Entrevista (ENT13)](../Elicitacao/elicitacao_entrevista.md#resultados) | Ambiental | Satisfação | João Gabriel |
| [RNF03](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rnf03) | Atualização ≤ 20s | [Entrevista (ENT)](../Elicitacao/elicitacao_entrevista.md#resultados) | Ambiental | Satisfação | João Gabriel |
| [RNF04](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rnf04) | Acessibilidade | [Entrevista (ENT10)](../Elicitacao/elicitacao_entrevista.md#resultados), [Brainstorm (BRS08)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Desenvolvimento | Representação | Cauã Nicolas |
| [RNF05](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rnf05) | Notificações configuráveis | [Brainstorm (BRS18)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Desenvolvimento | Representação | Cauã Nicolas |
| [RNF06](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rnf06) | Baixo consumo | — | Desenvolvimento | Alocado | Fernanda Vaz |
| [RNF07](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rnf07) | Compatibilidade Android/iOS | [Entrevista (ENT19)](../Elicitacao/elicitacao_entrevista.md#resultados) | Desenvolvimento | Responsabilidade | Fernanda Vaz |
| [RNF08](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rnf08) | Anti-fraude | — | — | — | — |
| [RNF09](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rnf09) | Proteção LGPD | [Entrevista (ENT21)](../Elicitacao/elicitacao_entrevista.md#resultados) | Ambiental | Representação | João Ramos |
| [RNF10](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rnf10) | Carregamento < 3s | [Entrevista (ENT17)](../Elicitacao/elicitacao_entrevista.md#resultados) | Gerencial | Representação | Gabriel Maciel |
| [RNF11](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rnf11) | Funcionamento offline | [Análise de Documentos (RNI05)](../Elicitacao/elicitacao_analise_documentos.md#requisitos-nao-implementados), [Entrevista (ENT18)](../Elicitacao/elicitacao_entrevista.md#resultados), [Brainstorm (BRS06)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Gerencial | Representação | Gabriel Maciel |
| [RNF12](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rnf12) | Pagamentos seguros | [Brainstorm (BRS10)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Ambiental | Representação | João Ramos |
| [RNF13](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rnf13) | Alta disponibilidade | — | Desenvolvimento | — | Gabriel Maciel |
| [RNF14](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rnf14) | Múltiplos usuários | [Brainstorm (BRS15)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Ambiental | Responsabilidade | Daniel Nunes |
| [RNF15](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rnf15) | Personalização | [Brainstorm (BRS13)](../Elicitacao/elicitacao_brainstorm.md#resultados) | Ambiental | Recurso | Daniel Nunes |

## Tabela de Contribuição

|        Nome          | Contribuição|
|----------------------|-------------|
| Cauã Nicolas         | Rastreabilidade Backward-From dos Requisitos RF13, RF14, RF15, RF16, RF24, RF25, RNF04, RNF05 |
| Daniel Nunes Duarte  | Rastreabilidade Backward-From dos Requisitos RF17, RF20, RF22, RF27, RF29, RF33, RNF14, RNF15 |
| Fernanda Vaz         | Rastreabilidade Backward-From dos Requisito:RNF6 e RNF7, RF05, RF06, RF07, RF08, RF31, RF32 |
| Gabriel Maciel       | Rastreabilidade Backward-From dos Requisitos RF19, RF26, RF28, RF34, RF35, RF36, RNF10, RNF11 |
| João Gabriel         | A preencher |
| João Ramos           | Rastreabilidade Backward-From dos Requisitos: RF09 ao RF12, RF18, RF21, RNF09 e RNF12 |


## Referência bibliográfica 

<a id="ref-1"></a>
> <sup>1.</sup>
> SAYÃO, M.; LEITE, J. C. S. P. *Rastreabilidade em Requisitos de Software*. In: **Anais do Simpósio Brasileiro de Engenharia de Software (SBES)**, 2005.

<a id="ref-2"></a>
> <sup>2.</sup>
> TORANZO, M.; CASTRO, J; MELLO, E. Uma proposta para melhorar o rastreamento de requisitos. PUC-Rio: Workshop em Engenharia de Requisitos, Rio de Janeiro, 2002. Disponível em: http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/toranzo.pdf. Acesso em: 28 de Out de 2025.

---

## Histórico de Versões

| **Versão** | **Data** | **Descrição** | **Autor(es)** | **Revisor(es)** |
|:----------:|:--------:|:--------------|:--------------|:----------------|
| **1.0** | 25/10 | Criação inicial do documento | Gabriel Maciel | Cauã Nicolas |
| **1.1** | 27/10 | Adição e elaboração de artefatos | Fernanda Vaz | Cauã Nicolas |
| **1.2** | 27/10 | Adição das classificações de fonte e tipos de elo para os requisitos RF19, RF26, RF28, RF34, RF35, RF36, RNF10, RNF11 | Gabriel Maciel |
| **1.3** | 28/10 | Adição Referência Bibliográfica | João Gabriel | Gabriel Maciel |
| **1.4** | 28/10 | Preenchimento das classificações de fonte e tipos de elo para os requisitos RF19, RF26, RF28, RF34, RF35, RF36, RNF10, RNF11 | Gabriel Maciel | João Ramos |
| **1.5** | 28/10 | Adição da fonte, classificação e tipos de elos(RF: 9,10,11,12 e 21 RF:12)  | João Ramos | Gabriel Maciel |
| **1.6** | 28/10 | Adição RNF6 e RNF7, RF05, RF06, RF07, RF08, RF31, RF32 | FERNANDA VAZ| Gabriel Maciel |
| **1.7** | 28/10 | Correções da minha parte | João Gabriel| -- |
| **1.8** | 28/10 | Adição RF17, RF20, RF22, RF27, RF29, RF33, RNF14, RNF15 | Daniel Nunes Duarte | -------- |
| **1.9** | 28/10 | Adição RF09 ao RF12, RF18, RF21, RNF09, RNF 12 | João Ramos | Gabriel Maciel |
---

## Agradecimentos

> Agradecemos o suporte da ferramenta de Inteligência Artificial Generativa **Google Gemini** no desenvolvimento deste trabalho.  
Em conformidade com o Código de Conduta da Sociedade Brasileira de Computação (SBC), declaramos que a ferramenta foi utilizada como auxílio na revisão gramatical e estilística do texto, na sugestão de estrutura para seções específicas do artigo, bem como na formatação de tabelas e na descrição de figuras.  
Ressaltamos que os autores assumem total responsabilidade por todo o conteúdo apresentado, incluindo sua originalidade e precisão.  
A ferramenta não figura como autora desta publicação.
