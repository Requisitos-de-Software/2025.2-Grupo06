# Análise de Documentos

## Introdução

A Análise de Documentos é uma técnica tradicional e fundamental na elicitação de requisitos. Ela consiste na revisão e avaliação sistemática de materiais escritos ou digitais existentes dentro da organização para identificar informações relevantes para o novo sistema.

Essa técnica permite ao engenheiro de requisitos obter um entendimento inicial aprofundado do domínio do problema, dos processos de negócio atuais e de quaisquer restrições ou regras de negócio já estabelecidas, sem a necessidade de envolver ativamente as partes interessadas (stakeholders) o tempo todo.

## Elicitação feita com a Análise de Documentos

### Perfil do Usuário: Passageiro de Transporte Público no DF

| Campo         | Descrição                                                                                                                                 |
|---------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Identificação | Usuário reconhecido pelo sistema como passageiro frequente do transporte público no Distrito Federal. Perfil baseado em dados demográficos e pesquisas de mobilidade urbana. |
| Interação     | - Consulta horários e localização dos ônibus em tempo real via GPS. <br> - Acessa informações sobre frota, linhas e empresas operadoras. <br> - Utiliza o app para planejar deslocamentos diários. |
| Finalidade    | Obter previsibilidade e confiabilidade nos horários dos ônibus. Facilitar o deslocamento para trabalho, estudo e outras atividades cotidianas. |

<font size="2"><p style="text-align: center"><b>Tabela 1</b> - Perfil do Usuário: Passageiro de Transporte Público no DF. Autoria: Fernanda Vaz</p></font>

### Perfil Demográfico dos Usuários

| Campo         | Descrição  |
|---------------| ------------------------------------------------------------------------------------------------------------------------------------------- |
| Identificação | Usuários majoritariamente das classes C, D e E, conforme pesquisa da CNT. Inclui estudantes e trabalhadores jovens com renda baixa a média. |
| Interação     | - Dependência diária do transporte coletivo. <br> - Busca por soluções digitais que aumentem a eficiência dos deslocamentos.              |
| Finalidade    | Utilizar o transporte público como principal meio de locomoção, com apoio de ferramentas digitais para reduzir incertezas e atrasos.     |

<font size="2"><p style="text-align: center"><b>Tabela 2</b> - Perfil Demográfico dos Usuários. Autoria: Fernanda Vaz</p></font>

## Requisitos Identificados

### Requisitos Funcionais
 
| ID    | Requisito Funcional                     | Descrição                                                                 |
|-------|------------------------------------------|---------------------------------------------------------------------------|
| RF01  | Localização em tempo real dos ônibus     | Permitir que o usuário visualize a posição atual dos ônibus via GPS.     |
| RF02  | Consulta de linhas e itinerários         | Exibir todas as linhas disponíveis com itinerários e horários.           |
| RF03  | Filtro por empresa operadora             | Permitir seleção de ônibus por empresa responsável pela linha.           |
| RF04  | Visualização da frota ativa              | Mostrar quais veículos estão em operação naquele momento.                |
| RF05  | Planejamento de rota                     | Sugerir trajetos com base no ponto de origem e destino do usuário.       |

<font size="2"><p style="text-align: center"><b>Tabela 3</b> - Requisitos Funcionais identificados</p></font>

### Requisitos Não Implementados

| ID    | Requisito Não Implementado              | Descrição                                                                 |
|-------|------------------------------------------|---------------------------------------------------------------------------|
| RNI01 | Notificações de chegada                  | Alertar o usuário quando o ônibus estiver próximo ao ponto.              |
| RNI02 | Integração com outros modais             | Planejar rotas com metrô ou bicicleta compartilhada.                     |
| RNI03 | Histórico de viagens                     | Registrar e exibir viagens realizadas pelo usuário.                      |
| RNI04 | Avaliação de linhas                      | Permitir avaliação da qualidade do serviço de cada linha.                |
| RNI05 | Modo offline                             | Disponibilizar funcionalidades básicas sem conexão à internet.           |

<font size="2"><p style="text-align: center"><b>Tabela 4</b> - Requisitos Não Implementados identificados</p></font>

## Responsáveis pela Elaboração

| Nome            | Responsabilidade              |
|-----------------|-------------------------------|
| Fernanda Vaz    | Elaboração da Análise de Documentos | 
| João Gabriel    | Elaboração da Análise de Documentos | 

## Histórico de Versões

| Versão | Data       | Descrição                                           | Autor(es)       | Revisor(es) |
|--------|------------|-----------------------------------------------------|-----------------|-------------|
| 1.0    | 29/09/2025 | Criação inicial do arquivo de Análise de Documentos | Fernanda Vaz   | Gabriel Maciel |
| 2.0    | 08/10/2025 | Separação do conteúdo em arquivo específico        | Gabriel Maciel  | Fernanda Vaz |
| 2.1    | 08/10/2025 | Adiciona tabela de identificação dos responsáveis pela elaboração do documento  | Gabriel Maciel  | Fernanda Vaz |

## Bibliografia

>[1] Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1. Acesso em 30 set 2025.

>[2] VAZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira. **Engenharia de Requisitos: software orientado ao negócio**. Rio de Janeiro: Brasport, 2016.