

# Técnicas de Elicitação

## Análise de Documentos

A Análise de Documentos é uma técnica tradicional e fundamental na elicitação de requisitos. Ela consiste na revisão e avaliação sistemática de materiais escritos ou digitais existentes dentro da organização para identificar informações relevantes para o novo sistema.

Essa técnica permite ao engenheiro de requisitos obter um entendimento inicial aprofundado do domínio do problema, dos processos de negócio atuais e de quaisquer restrições ou regras de negócio já estabelecidas, sem a necessidade de envolver ativamente as partes interessadas (stakeholders) o tempo todo.

## Elicitação feita com a Análise de Documentos
# Perfil do Usuário: Passageiro de Transporte Público no DF

| Campo         | Descrição                                                                                                                                 |
|---------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Identificação | Usuário reconhecido pelo sistema como passageiro frequente do transporte público no Distrito Federal. Perfil baseado em dados demográficos e pesquisas de mobilidade urbana. |
| Interação     | - Consulta horários e localização dos ônibus em tempo real via GPS. <br> - Acessa informações sobre frota, linhas e empresas operadoras. <br> - Utiliza o app para planejar deslocamentos diários. |
| Finalidade    | Obter previsibilidade e confiabilidade nos horários dos ônibus. Facilitar o deslocamento para trabalho, estudo e outras atividades cotidianas. |
 <sub><b> Tabela 01.</b> Autoria: Fernanda Vaz</sub>

 ## Perfil Demográfico dos Usuários
| Campo         | Descrição                                                                                                                                 |
|---------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Identificação | Usuários majoritariamente das classes C, D e E, conforme pesquisa da CNT. Inclui estudantes e trabalhadores jovens com renda baixa a média. |
| Interação     | - Dependência diária do transporte coletivo. <br> - Busca por soluções digitais que aumentem a eficiência dos deslocamentos.              |
| Finalidade    | Utilizar o transporte público como principal meio de locomoção, com apoio de ferramentas digitais para reduzir incertezas e atrasos.     |
 <sub><b> Tabela 02.</b> Autoria: Fernanda Vaz</sub>

 ## Requisitos Funcionais
 
| ID    | Requisito Funcional                     | Descrição                                                                 |
|-------|------------------------------------------|---------------------------------------------------------------------------|
| RF01  | Localização em tempo real dos ônibus     | Permitir que o usuário visualize a posição atual dos ônibus via GPS.     |
| RF02  | Consulta de linhas e itinerários         | Exibir todas as linhas disponíveis com itinerários e horários.           |
| RF03  | Filtro por empresa operadora             | Permitir seleção de ônibus por empresa responsável pela linha.           |
| RF04  | Visualização da frota ativa              | Mostrar quais veículos estão em operação naquele momento.                |
| RF05  | Planejamento de rota                     | Sugerir trajetos com base no ponto de origem e destino do usuário.       |

## Requisitos Não Implementados

| ID    | Requisito Não Implementado              | Descrição                                                                 |
|-------|------------------------------------------|---------------------------------------------------------------------------|
| RNI01 | Notificações de chegada                  | Alertar o usuário quando o ônibus estiver próximo ao ponto.              |
| RNI02 | Integração com outros modais             | Planejar rotas com metrô ou bicicleta compartilhada.                     |
| RNI03 | Histórico de viagens                     | Registrar e exibir viagens realizadas pelo usuário.                      |
| RNI04 | Avaliação de linhas                      | Permitir avaliação da qualidade do serviço de cada linha.                |
| RNI05 | Modo offline                             | Disponibilizar funcionalidades básicas sem conexão à internet.           |




## Entrevista

### Introdução
  A entrevista é uma das técnicas mais comuns e antigas de elicitação de requisitos e fundamental na Engenharia de Requisitos. Ela consiste, basicamente, em uma conversa direta entre o engenheiro de requisitos (ou analista) e as partes interessadas (stakeholders) para coletar informações sobre suas necessidades, expectativas e problemas que o software deve resolver.

### Dados

### Entrevistadores
- Entrevistador: João Lucas 
- Gravação: Gabriel Maciel
- Redator: Cauã Nicolas  
### Dados do entrevistado e entrevista 1
- Nome: Artur
- Idade: 23 anos
- Sexo: Masculino
- Região onde reside: Luziânia / GO
- Data da entrevista: 26/09/2025
- Horário: 12:00
- Duração: 14:58 minutos
### Dados do entrevistado e entrevista 2
- Nome: Caio
- Idade: 21 anos
- Sexo: Masculino
- Região onde reside: Gama / DF
- Data da entrevista: 26/09/2025
- Duração: 7:12 minutos
### Dados do entrevistado e entrevista 3
- Nome: Guilherme
- Idade: 20 anos
- Sexo: Masculino
- Região onde reside: Sobradinho / DF
- Data da entrevista: 26/09/2025
- Duração: 11:22 minutos
### Dados do entrevistado e entrevista 4
- Nome: Beatriz
- Idade: 19 anos
- Sexo: Feminino
- Região onde reside: Lago Norte
- Data da entrevista: 26/09/2025
- Duração: 7:35 minutos

## Perguntas e Respostas

### Entrevista 1 - Artur

| Questão | Resposta |
| ------- | -------- |
| Qual a sua idade? | 23 anos |
| Você mora em qual região/bairro do DF? | Luziânia / GO |
| Qual a sua ocupação (estudante, trabalhador, etc.)? | Estudante |
| Com que frequência você utiliza transporte público no seu dia a dia? | Diariamente |
| Você já utilizou aplicativos para a mobilidade urbana? | Sim, moovit |
| Lembra da primeira vez que usou? Como foi sua experiência? | Quando foi fazer o vestibular, mas o local de prova era desconhecido, buscou um app para auxílio na locomoção. |
| Com que frequência você costuma utilizar esses aplicativos? | Diariamente. |
| O que te levou a começar a usar esses aplicativos? | Necessidade para locomoção |
| Quando você abre o app, normalmente, o que está buscando? | Melhores rotas, com horários específicos |
| O que você espera de um aplicativo de transporte público? | Visualização de rotas, horários e interação em tempo real. |
| Quais informações são mais importantes para você? | Horários de rotas e linhas, além da localização em tempo real do transporte. |
| Na sua opinião, os aplicativos atendem às suas necessidades atuais? Por quê? | Sim, pois auxilia e ajuda no planejamento de viagens. |
| Há situações em que eles falham ou não ajudam? Pode me dar um exemplo? | Falta de pontualidade. |
| Que tipo de recurso novo você gostaria de ver nesses apps? | Ampliamento do serviço para áreas remotas, além de notícia e informações sobre o trânsito. |
| Você gostaria que esses apps fossem mais integrados a outros serviços? | Integração com cartão mobilidade, além da informação do preço das passagens. |
---
*Tabela 1: Perguntas e Respostas (Fonte: OLIVEIRA, Cauã. 2025)*

### Entrevista 2 - Caio

| Questão | Resposta |
| ------- | -------- |
| Qual a sua idade? | 21 anos |
| Você mora em qual região/bairro do DF? | Gama / DF |
| Qual a sua ocupação (estudante, trabalhador, etc.)? | Estudante |
| Com que frequência você utiliza transporte público no seu dia a dia? | Diariamente, com frequência. |
| Você já utilizou aplicativos para a mobilidade urbana? | Sim, moovit, df no ponto e cittamobi |
| Lembra da primeira vez que usou? Como foi sua experiência? | Ajudar caminho pra faculdade. |
| Com que frequência você costuma utilizar esses aplicativos? | Diariamente. |
| O que te levou a começar a usar esses aplicativos? | Necessidades de organização para busca de horários para ida e chegada do percurso. |
| Quando você abre o app, normalmente, o que está buscando? | Melhor caminho, rota para chegada ao destino. |
| O que você espera de um aplicativo de transporte público? | Que apresente os horários das linhas com as melhores rotas possível. |
| Quais informações são mais importantes para você? | Localização em tempo real, mapa interativo, e prévia do horário de chegada ao destino. |
| Na sua opinião, os aplicativos atendem às suas necessidades atuais? Por quê? | Sim. |
| Há situações em que eles falham ou não ajudam? Pode me dar um exemplo? | Falta de pontualidade. |
| Que tipo de recurso novo você gostaria de ver nesses apps? | Opção de recarga dentro do aplicativo. |
| Você gostaria que esses apps fossem mais integrados a outros serviços? | Integração com BRB Mobilidade. |

---
*Tabela 2: Perguntas e Respostas (Fonte: OLIVEIRA, Cauã. 2025)*


### Entrevista 3 - Guilherme

| Questão | Resposta |
| ------- | -------- |
| Qual a sua idade? | 20 anos |
| Você mora em qual região/bairro do DF? | Sobradinho/DF |
| Qual a sua ocupação (estudante, trabalhador, etc.)? | Estudante |
| Com que frequência você utiliza transporte público no seu dia a dia? | Uso diário (Moovit) |
| Você já utilizou aplicativos para a mobilidade urbana? | Moovit |
| Lembra da primeira vez que usou? Como foi sua experiência? | Iniciou seu uso durante a pandemia, que se tornou um hábito frequente. |
| Com que frequência você costuma utilizar esses aplicativos? | 3 vezes ao dia (uso diário), usando 3 a 4 dias por semana. |
| O que te levou a começar a usar esses aplicativos? | Facilidade na pesquisa/busca pelos horários do ônibus. |
| Quando você abre o app, normalmente, o que está buscando? | Facilidade em encontrar informações sobre os horários e linhas de ônibus disponíveis. |
| O que você espera de um aplicativo de transporte público? | Busca e pesquisa por linhas, pontos de parada e horários. |
| Quais informações são mais importantes para você? | Horários das linhas e atualização em tempo real da localização do transporte. |
| Na sua opinião, os aplicativos atendem às suas necessidades atuais? Por quê? | Supre a maioria das necessidades, ficando a desejar somente a questão da falta de informação na busca por pontos de parada em determinados locais. |
| Há situações em que eles falham ou não ajudam? Pode me dar um exemplo? | Em situações em que possui ponto de recarga e ponto de parada muito próximos, causando sobreposição de ícones. |
| Que tipo de recurso novo você gostaria de ver nesses apps? | Nenhum recurso novo. |
| Você gostaria que esses apps fossem mais integrados a outros serviços? | Integração com o BRB Mobilidade para recarga do cartão. |

*Tabela 3: Perguntas e Respostas (Fonte: OLIVEIRA, Cauã. 2025)*




## Brainstorm

A técnica de Brainstorming (ou "Tempestade de Ideias") é um método de elicitação de requisitos em grupo focado na geração de um grande volume de ideias em um curto período. É uma ferramenta poderosa para estimular a criatividade e descobrir requisitos inovadores ou que não seriam facilmente identificados em entrevistas individuais ou análise de documentos.

# Histórico de Versões

| Versão | Data       | Descrição                                                      | Autor(es)       | Revisor(es)       |
|--------|------------|----------------------------------------------------------------|----------------|-----------------|
| 0.1    | 29/09/2025 | Criação inicial do Perfil do Usuário e Requisitos.             | Fernanda Vaz   | N/A             |
| 1.0    | 30/09/2025 | Criação inicial do arquivo, adiciona dados obtidos na entrevista. | Cauã Nicolas   | Gabriel Macial  |
| 1.1    | 30/09/2025 | Atualizações e correção das legendas das tabelas e adição da Beatriz. | Fernanda Vaz   | Cauã Nicolas    |


## Bibliografia
>[1] Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1. Acesso em 30 set 2025.
