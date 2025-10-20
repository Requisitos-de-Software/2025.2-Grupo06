## Introdução
O Registro Pendente de Trabalhos (Backlog) é um artefato essencial nas metodologias ágeis. Conforme Pressman<sup>[1](#ref-1)</sup>, ele é definido como "uma lista com prioridades dos requisitos ou funcionalidades do projeto que fornecem valor comercial ao cliente". Este registro é dinâmico, permitindo que novos itens sejam adicionados a qualquer momento para refletir mudanças. O gerente de produto avalia o registro e atualiza as prioridades continuamente, garantindo que a equipe esteja sempre focada no que gera maior valor.

---

###### Print da Referência 
<a href="https://imgbb.com/"><img src="https://i.ibb.co/pBS7FPFb/image.png" alt="image" border="0"></a>

## Metodologia

Para a construção do Product Backlog deste projeto, adotamos os conceitos fundamentais do desenvolvimento ágil, com ênfase no framework Scrum. Conforme apresentado por Serrano e Serrano<sup>[2](#ref-2)</sup>, o Product Backlog é um artefato central do Scrum que contém todas as funcionalidades desejadas para o produto, organizadas e priorizadas de acordo com o valor de negócio.

### Histórias de Usuário

As histórias de usuário foram elaboradas seguindo o formato padrão estabelecido no desenvolvimento ágil<sup>[2](#ref-2)</sup>: **"Como [tipo de usuário], eu quero [realizar ação], para que [obter benefício]"**. Essa estrutura narrativa, centrada no usuário, permite:

- **Identificar claramente quem** se beneficia da funcionalidade (o ator);
- **Especificar o que** o usuário deseja realizar (a ação);
- **Justificar por que** a funcionalidade é importante (o valor de negócio).

Cada história de usuário foi documentada com os seguintes elementos essenciais:

- **ID**: Identificador único da história (US01, US02, etc.);
- **Descrição**: Narrativa no formato padrão mencionado acima;
- **Prioridade**: Classificação em Alta, Média ou Baixa, baseada no valor de negócio e urgência;
- **Rastreabilidade (Origem)**: Vínculo direto com os requisitos funcionais elicitados, garantindo rastreabilidade bidirecional entre requisitos e histórias.

### Épicos

Os épicos representam agrupamentos de histórias de usuário relacionadas que compartilham um objetivo comum de alto nível<sup>[2](#ref-2)</sup>. Segundo Serrano e Serrano<sup>[2](#ref-2)</sup>, épicos são funcionalidades grandes demais para serem implementadas em uma única iteração, sendo decompostas em histórias de usuário menores e gerenciáveis.

Para este projeto, os épicos foram definidos com base na análise temática das funcionalidades elicitadas, agrupando histórias que:

1. **Compartilham objetivos de negócio similares** (ex: todas relacionadas a rastreamento em tempo real);
2. **Atendem às necessidades de um mesmo perfil de usuário** (ex: funcionalidades de acessibilidade);
3. **Contribuem para uma mesma área funcional do sistema** (ex: mecanismos de filtragem e busca);
4. **Possuem interdependências técnicas** que justificam seu desenvolvimento conjunto.

Cada épico foi estruturado contendo:

- **Nome descritivo**: Uma palavra que sintetiza o tema do épico;
- **Objetivo**: Descrição clara do propósito e valor de negócio do conjunto de funcionalidades;
- **Histórias de Usuário**: Tabela com as histórias agrupadas sob o épico, incluindo ID, descrição completa, prioridade e rastreabilidade.

A priorização das histórias dentro de cada épico foi realizada considerando os critérios estabelecidos por Serrano e Serrano<sup>[2](#ref-2)</sup>: valor de negócio para o cliente, risco técnico, esforço estimado e dependências entre funcionalidades.

---

### Épico 1: Rastreamento

Tem como objetivo permitir que passageiros acompanhem a localização e status dos ônibus em tempo real.

| ID | História de Usuário | Prioridade | Rastreabilidade (Origem) | Autoria |
| -- | ------------------- | ---------- | ------------------------ | ------- |
| **US04** | Como **passageiro que precisa escolher entre várias opções de transporte**, eu quero **rastrear múltiplas linhas de ônibus simultaneamente no mapa**, para que **eu possa visualizar e comparar diferentes opções em tempo real e escolher a melhor alternativa para meu deslocamento**. | Alta | **RF35/ENT12** - Permitir rastreamento de múltiplas linhas de ônibus simultaneamente no mapa | Gabriel Maciel |

---

### Épico 2: Filtragem

Tem como objetivo facilitar a localização de linhas, rotas e opções de transporte específicas.

| ID | História de Usuário | Prioridade | Rastreabilidade (Origem) | Autoria |
| -- | ------------------- | ---------- | ------------------------ | ------- |
| **US01** | Como **passageiro do transporte público**, eu quero **filtrar e visualizar ônibus de acordo com a empresa operadora**, para que **eu possa escolher linhas de empresas específicas de minha preferência ou evitar empresas com as quais tive experiências negativas**. | Média | **RF26/RF03 (Análise de Documentos)** - Filtrar ônibus por empresa operadora | Gabriel Maciel |

---

### Épico 3: Acessibilidade

Tem como objetivo garantir que o sistema atenda às necessidades de todos os usuários, especialmente aqueles com necessidades especiais.

| ID | História de Usuário | Prioridade | Rastreabilidade (Origem) | Autoria |
| -- | ------------------- | ---------- | ------------------------ | ------- |
| **US02** | Como **passageiro aguardando no ponto de ônibus**, eu quero **acessar uma versão web leve do aplicativo através de QR Code**, para que **eu possa consultar informações sobre linhas e horários rapidamente sem precisar instalar o aplicativo completo no meu dispositivo**. | Média | **RF19/BRS17** - Disponibilizar versão web leve para acesso rápido em pontos de ônibus (via QR Code) | Gabriel Maciel |

---

### Épico 4: Avaliação

Tem como objetivo permitir que usuários avaliem e contribuam para a melhoria contínua do serviço de transporte público.

| ID | História de Usuário | Prioridade | Rastreabilidade (Origem) | Autoria |
| -- | ------------------- | ---------- | ------------------------ | ------- |
| **US03** | Como **passageiro regular do transporte público**, eu quero **avaliar a qualidade do serviço de cada linha de ônibus que utilizo**, para que **eu possa compartilhar minha experiência e contribuir para a melhoria do serviço, além de ajudar outros passageiros a escolherem as melhores opções**. | Baixa | **RF28/RNI04** - Permitir avaliação da qualidade do serviço de cada linha | Gabriel Maciel |

---

### Épico 5: Recarga 

Tem como objetivo permitir que os usuários realizem recargas do cartão de transporte diretamente pelo aplicativo, garantindo praticidade e reduzindo a necessidade de filas ou deslocamentos até pontos físicos de atendimento.

| ID | História de Usuário | Prioridade | Rastreabilidade (Origem) | Autoria |
| -- | ------------------- | ---------- | ------------------------ | ------- |
| **US09** | Como **usuário do transporte público**, eu quero **realizar recargas do meu cartão de transporte diretamente pelo aplicativo**, para que **eu possa evitar filas e ter mais praticidade na recarga**. | Média | **RF13** - Oferecer recarga de cartão de transporte (ex.: integração com BRB Mobilidade) | Cauã Nicolas |

---

### Épico 6: Integração 

Tem como objetivo integrar o cartão de transporte ao aplicativo, permitindo que o usuário visualize o saldo e realize recargas de forma unificada, sem necessidade de acessar sistemas externos.

| ID | História de Usuário | Prioridade | Rastreabilidade (Origem) | Autoria |
| -- | ------------------- | ---------- | ------------------------ | ------- |
| **US10** | Como **usuário do transporte público**, eu quero **visualizar o saldo e realizar recargas do meu cartão de transporte no aplicativo**, para que **eu possa acompanhar meu consumo e manter o cartão sempre carregado**. | Média | **RF14** - Permitir integração com o cartão de transporte, incluindo saldo e recarga | Cauã Nicolas |

---

### Épico 7: Histórico 

Tem como objetivo permitir que o usuário visualize e acompanhe o histórico de viagens realizadas, oferecendo mais controle sobre deslocamentos, horários e gastos com transporte público.

| ID | História de Usuário | Prioridade | Rastreabilidade (Origem) | Autoria |
| -- | ------------------- | ---------- | ------------------------ | ------- |
| **US11** | Como **passageiro**, eu quero **visualizar meu histórico de viagens realizadas**, para que **eu possa acompanhar meus trajetos, horários e valores gastos**. | Média | **RF15** - Manter histórico de viagens do usuário | Cauã Nicolas |

---

### Épico 8: Reportar

Tem como objetivo permitir que os usuários reportem problemas relacionados ao transporte público, como falhas no ônibus, comportamento inadequado do motorista ou cobranças incorretas, para que as empresas responsáveis possam tomar providências.

| ID | História de Usuário | Prioridade | Rastreabilidade (Origem) | Autoria |
| -- | ------------------- | ---------- | ------------------------ | ------- |
| **US12** | Como **usuário do transporte público**, eu quero **reportar problemas ocorridos durante uma viagem (como comportamento do motorista, falhas no ônibus ou cobrança incorreta)**, para que **a empresa responsável possa investigar e melhorar o serviço**. | Baixa | **RF16** - Permitir reportar problemas (motorista, ônibus, cobrança) com dados do veículo e horário | Cauã Nicolas |

---

## Referência bibliográfica

<a id="ref-1"></a>

> <sup>1.</sup> PRESSMAN, R. S. *Engenharia de software: uma abordagem profissional*. 7. ed. Porto Alegre: AMGH, 2011.

<a id="ref-2"></a>

> <sup>2.</sup> SERRANO, Milene; SERRANO, Maurício. **Requisitos - Aula 15**. Apresentação de slides. Disponível em: Aprender3. Acesso em: 19 out. 2025.

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|:-------|:-----|:-----------|:------------|:-------------|
| 1.0 | 18/10 | Adição de introdução | Fernanda Vaz | Gabriel Maciel |
| 1.1 | 19/10 | Adição de Metodologia, Épicos e Histórias de Usuário | Gabriel Maciel | Cauã Nicolas |
| 1.2 | 20/10 | Adição de Épicos  | Cauã Nicolas |  |

## Agradecimentos

Agradecemos o suporte da ferramenta de Inteligência Artificial Generativa Google Gemini no desenvolvimento deste trabalho. Em conformidade com o Código de Conduta da Sociedade Brasileira de Computação (SBC), declaramos que a ferramenta foi utilizada como auxílio na revisão gramatical e estilística do texto, na sugestão de estrutura para seções específicas do artigo, bem como na formatação de tabelas e na descrição de figuras. Ressaltamos que os autores assumem total responsabilidade por todo o conteúdo apresentado, incluindo sua originalidade e precisão. A ferramenta não figura como autora desta publicação.