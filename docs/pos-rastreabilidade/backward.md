# Backward-From

## Introdução

Este documento trata da "rastreabilidade para trás" (*backward-from*). Isso significa simplesmente rastrear cada requisito de volta à sua fonte. É o processo de conectar cada "o quê" (o requisito) ao seu "porquê" (a fonte que o solicitou).

---

## Metodologia

A metodologia aplicada baseia-se na análise dos artefatos de requisitos funcionais e não funcionais, associando cada requisito identificado ao documento de origem ou evidência. Essa abordagem busca manter a rastreabilidade bidirecional — tanto *forward-to* quanto *backward-from* —, conforme proposto por Sayão e Leite (2005).

---
## Requisitos Funcionais

| **ID** | **Requisito** | **Categoria** | **Descrição** | **Fonte** |
|:------:|:---------------|:--------------|:---------------|:-----------|
| **01** | **RF01** | Funcional | A preencher | A preencher |
| **02** | **RF02** | Funcional | A preencher | A preencher |
| **03** | **RF03** | Funcional | A preencher | A preencher |
| **04** | **RF04** | Funcional | A preencher | A preencher |
| **05** | **RF05** | Funcional | Apresentar horários de saída e chegada dos transportes | Elicitação de Requisitos: Entrevista (ENT02) |
| **06** | **RF06** | Funcional | Oferecer um mapa interativo com os pontos de ônibus e suas linhas correspondentes | Elicitação de Requisitos: Entrevista (ENT06) |
| **07** | **RF07** | Funcional | Integrar informações de outros modais (metrô, outros ônibus) em rotas multimodais | Elicitação de Requisitos: Análise de Documentos (RNI02), Brainstorm (BRS04) |
| **08** | **RF08** | Funcional | Exibir informações de acessibilidade do ônibus (ex.: acessível para cadeirantes) | Elicitação de Requisitos: Entrevista (ENT16) |
| **09** | **RF09** | Funcional | A preencher | A preencher |
| **10** | **RF10** | Funcional | A preencher | A preencher |
| **11** | **RF11** | Funcional | A preencher | A preencher |
| **12** | **RF12** | Funcional | A preencher | A preencher |
| **13** | **RF13** | Funcional | A preencher | A preencher |
| **14** | **RF14** | Funcional | A preencher | A preencher |
| **15** | **RF15** | Funcional | A preencher | A preencher |
| **16** | **RF16** | Funcional | A preencher | A preencher |
| **17** | **RF17** | Funcional | A preencher | A preencher |
| **18** | **RF18** | Funcional | A preencher | A preencher |
| **19** | **RF19** | Funcional | A preencher | A preencher |
| **20** | **RF20** | Funcional | A preencher | A preencher |
| **21** | **RF21** | Funcional | A preencher | A preencher |
| **22** | **RF22** | Funcional | A preencher | A preencher |
| **23** | **RF23** | Funcional | A preencher | A preencher |
| **24** | **RF24** | Funcional | A preencher | A preencher |
| **25** | **RF25** | Funcional | A preencher | A preencher |
| **26** | **RF26** | Funcional | A preencher | A preencher |
| **27** | **RF27** | Funcional | A preencher | A preencher |
| **28** | **RF28** | Funcional | A preencher | A preencher |
| **29** | **RF29** | Funcional | A preencher | A preencher |
| **30** | **RF30** | Funcional | A preencher | A preencher |
| **31** | **RF31** | Funcional | Sistema de recompensas por uso sustentável do transporte público | Elicitação de Requisitos: Brainstorm (BRS09) |
| **32** | **RF32** | Funcional | Exibir relatórios de impacto ambiental (CO₂ economizado) | Elicitação de Requisitos: Brainstorm (BRS11) |


---

## Requisitos Não Funcionais

| **ID** | **Requisito** | **Categoria** | **Descrição** | **Fonte** |
|:------:|:---------------|:--------------|:---------------|:-----------|
| **01** | **RNF01** | A preencher | A preencher | A preencher |
| **02** | **RNF02** | A preencher | A preencher | A preencher |
| **03** | **RNF03** | A preencher | A preencher | A preencher |
| **04** | **RNF04** | A preencher | A preencher | A preencher |
| **05** | **RNF05** | A preencher | A preencher | A preencher |
| **06** | **RNF06** | Não Funcional | Baixo consumo de bateria e dados móveis.| Analise de documentos |
| **07** | **RNF07** | Não Funcional | Compatibilidade com dispositivos Android e iOS. | Elicitação de Requisitos: Entrevista (ENT19) |
| **08** | **RNF08** | A preencher | A preencher | A preencher |
| **09** | **RNF09** | A preencher | A preencher | A preencher |
| **10** | **RNF10** | A preencher | A preencher | A preencher |

## Elos Funcionais

### EF01
*Autoria: Cauã Nicolas, 2025*

- **Categoria:** Desenvolvimento
- **Elementos Rastreáveis:**
    - **RF13:**
        - Elicitação de Requisitos: Entrevista (ENT07)
- **Elos:**
    - Representação: ENT07 representa RF13
    - Agregação: EP05 agrega RF13
    - Agregação: EP08 agrega RF13
    - Agregação: SIG-PORT agrega RF13

---

### EF02
*Autoria: Cauã Nicolas, 2025*

- **Categoria:** Desenvolvimento
- **Elementos Rastreáveis:**
    - **RF14:**
        - Elicitação de Requisitos: Entrevista (ENT07)
- **Elos:**
    - Representação: ENT07 representa RF14
    - Agregação: EP08 agrega RF14
    - Agregação: SIG-PORT agrega RF14

---

### EF03
*Autoria: Cauã Nicolas, 2025*

- **Categoria:** Desenvolvimento
- **Elementos Rastreáveis:**
    - **RF15:**
        - Elicitação de Requisitos: Análise de Documentos (RNI03)
- **Elos:**
    - Representação: RNI03 representa RF15
    - Agregação: EP07 agrega RF15

---

### EF04
*Autoria: Cauã Nicolas, 2025*

- **Categoria:** Desenvolvimento
- **Elementos Rastreáveis:**
    - **RF16:**
        - Elicitação de Requisitos: Entrevista (ENT20)
- **Elos:**
    - Representação: ENT20 representa RF16
    - Agregação: EP08 agrega RF16

---

### EF05
*Autoria: Cauã Nicolas, 2025*

- **Categoria:** Desenvolvimento
- **Elementos Rastreáveis:**
    - **RF24:**
        - Elicitação de Requisitos: Entrevista (ENT14)
- **Elos:**
    - Representação: ENT14 representa RF24
    - Agregação: EP02 agrega RF24

---   

### EF06
*Autoria: Cauã Nicolas, 2025*

- **Categoria:** Desenvolvimento
- **Elementos Rastreáveis:**
    - **RF25:**
        - Elicitação de Requisitos: Entrevista (ENT08)
- **Elos:**
    - Representação: ENT08 representa RF25
    - Agregação: SIG-DSP agrega RF25
    - Agregação: EP-COB agrega RF25

---

## Elos Não Funcionais

### ENF01
*Autoria: Cauã Nicolas, 2025*

- **Categoria:** Desenvolvimento
- **Elementos Rastreáveis:**
    - **RNF04:**
        - Elicitação de Requisitos: Entrevista (ENT10), Brainstorm (BRS08)
- **Elos:** Agrega SIG-U03
    
---

### ENF02
*Autoria: Cauã Nicolas, 2025*

- **Categoria:** Desenvolvimento
- **Elementos Rastreáveis:**
    - **RNF05:**
        - Priorização de Requisitos: In or Out (RNF05)
- **Elos:**
    - Agregação: RNF05 agrega SIG-U04
    - Agregação: EP06 agrega RNF05

---

## Tabela de Contribuição

|        Nome          | Contribuição|
|----------------------|-------------|
| Cauã Nicolas         | A preencher |
| Daniel Nunes Duarte  | A preencher |
| Fernanda Vaz         | A preencher |
| Gabriel Maciel       | A preencher |
| João Gabriel         | A preencher |
| João Ramos           | A preencher |


## Referência bibliográfica 

<a id="ref-1"></a>

> SAYÃO, M.; LEITE, J. C. S. P. *Rastreabilidade em Requisitos de Software*. In: **Anais do Simpósio Brasileiro de Engenharia de Software (SBES)**, 2005.

---

## Histórico de Versões

| **Versão** | **Data** | **Descrição** | **Autor(es)** | **Revisor(es)** |
|:----------:|:--------:|:--------------|:--------------|:----------------|
| **1.0** | 25/10 | Criação inicial do documento | Gabriel Maciel | A revisar |
| **1.1** | 27/10 | Adição e elaboração de artefatos | Fernanda Vaz | — |

---

## Agradecimentos

>Agradecemos o suporte da ferramenta de Inteligência Artificial Generativa **Google Gemini** no desenvolvimento deste trabalho.  
>Em conformidade com o Código de Conduta da Sociedade Brasileira de Computação (SBC), declaramos que a ferramenta foi utilizada como auxílio na revisão gramatical e estilística do texto, na sugestão de estrutura para seções específicas do artigo, bem como na formatação de tabelas e na descrição de figuras.  
>Ressaltamos que os autores assumem total responsabilidade por todo o conteúdo apresentado, incluindo sua originalidade e precisão.  
>A ferramenta não figura como autora desta publicação.

