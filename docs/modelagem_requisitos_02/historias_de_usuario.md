# Histórias de Usuário

## Introdução

A atividade "Ouvir" do Extreme Programming (XP) é usada para gerar as "histórias de usuários", que definem as funcionalidades requisitadas. Segundo Pressman[¹](#ref-1), cada história "é escrita pelo cliente e é colocada em uma ficha. O cliente atribui um valor (uma prioridade) à história".

##### Print da Referência

![Referência Pressman](https://i.ibb.co/fV8V5mPK/image.png)

## Metodologia

Para a elaboração das histórias de usuário deste projeto, foi adotada a metodologia baseada nas diretrizes estabelecidas pela Coordenação Geral de Tecnologia da Informação (CGTI) do Ministério da Agricultura[²](#ref-2). A técnica consiste em transformar os requisitos elicitados em narrativas centradas no usuário, descrevendo funcionalidades do ponto de vista de quem irá utilizá-las.

Cada história de usuário foi estruturada contendo os seguintes elementos essenciais:

- **Origem**: Identificação do requisito funcional ou não funcional que originou a história, incluindo a técnica de elicitação utilizada (Análise de Documentos, Brainstorm ou Entrevista);
- **Descrição**: Narrativa que responde "quem" (o usuário/persona), "o que" (a funcionalidade desejada) e "por que" (o valor ou benefício esperado), seguindo o formato padrão: "Como [tipo de usuário], eu quero [realizar ação], para que [obter benefício]";
- **Critérios de Aceitação**: Conjunto de condições mensuráveis e testáveis que devem ser satisfeitas para que a história seja considerada completa e pronta para implementação;
- **Prioridade**: Classificação da importância da história (Alta, Média ou Baixa) baseada no valor de negócio, impacto para o usuário e urgência de implementação.

Todas as histórias de usuário seguem o [Template de Tabela](#template-de-história-de-usuário) apresentado abaixo, garantindo padronização e consistência na documentação dos requisitos.

### Template de História de Usuário

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | [ID do Requisito/Fonte] - [Descrição resumida do requisito de origem] |
| **Descrição:** | Como **[tipo de usuário]**, eu quero **[ação/funcionalidade desejada]**, para que **[benefício ou valor obtido]**. |
| **Critérios de Aceitação:** | [Lista de condições que devem ser atendidas para que a história seja considerada completa] |
| **Prioridade:** | [Alta/Média/Baixa] |

## Histórias de Usuário

### US01 - Filtrar Ônibus por Empresa Operadora

*Autoria: Gabriel Maciel, 2025*

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | **RF26/RF03 (Análise de Documentos)** - Filtrar ônibus por empresa operadora |
| **Descrição:** | Como **passageiro do transporte público**, eu quero **filtrar e visualizar ônibus de acordo com a empresa operadora**, para que **eu possa escolher linhas de empresas específicas de minha preferência ou evitar empresas com as quais tive experiências negativas**. |
| **Critérios de Aceitação:** | - O sistema deve exibir uma lista completa de todas as empresas operadoras disponíveis no DF<br>- O passageiro deve poder selecionar uma ou múltiplas empresas para filtrar<br>- O mapa deve exibir apenas os ônibus das empresas selecionadas<br>- O sistema deve mostrar o nome da empresa em cada linha de ônibus listada<br>- O filtro deve ser aplicado em tempo real ao selecionar/desselecionar empresas<br>- O sistema deve permitir limpar todos os filtros com um único clique<br>- O passageiro deve poder salvar suas preferências de empresa como padrão<br>- O sistema deve indicar quantas linhas e veículos estão disponíveis para cada empresa<br>- O filtro deve funcionar em conjunto com outros filtros (por linha, região, etc.)<br>- O aplicativo deve manter as configurações de filtro entre sessões |
| **Prioridade:** | Média |

---

### US02 - Acesso Web Rápido via QR Code

*Autoria: Gabriel Maciel, 2025*

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | **RF19/BRS17** - Disponibilizar versão web leve para acesso rápido em pontos de ônibus (via QR Code) |
| **Descrição:** | Como **passageiro aguardando no ponto de ônibus**, eu quero **acessar uma versão web leve do aplicativo através de QR Code**, para que **eu possa consultar informações sobre linhas e horários rapidamente sem precisar instalar o aplicativo completo no meu dispositivo**. |
| **Critérios de Aceitação:** | - Cada ponto de ônibus deve ter um QR Code visível e acessível<br>- Ao escanear o QR Code, o passageiro deve ser direcionado para uma página web responsiva<br>- A versão web deve carregar em menos de 3 segundos<br>- A versão web deve exibir linhas que passam naquele ponto específico<br>- A versão web deve mostrar horários previstos de chegada dos próximos ônibus<br>- A versão web deve funcionar em diferentes navegadores (Chrome, Safari, Firefox)<br>- A interface deve ser otimizada para dispositivos móveis<br>- Não deve ser necessário login ou cadastro para acesso básico<br>- A versão web deve consumir o mínimo de dados móveis possível |
| **Prioridade:** | Média |

---

### US03 - Avaliar Qualidade das Linhas

*Autoria: Gabriel Maciel, 2025*

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | **RF28/RNI04** - Permitir avaliação da qualidade do serviço de cada linha |
| **Descrição:** | Como **passageiro regular do transporte público**, eu quero **avaliar a qualidade do serviço de cada linha de ônibus que utilizo**, para que **eu possa compartilhar minha experiência e contribuir para a melhoria do serviço, além de ajudar outros passageiros a escolherem as melhores opções**. |
| **Critérios de Aceitação:** | - O passageiro deve poder atribuir uma nota de 1 a 5 estrelas para cada linha<br>- O sistema deve permitir avaliação de diferentes aspectos (pontualidade, conforto, limpeza, atendimento)<br>- O passageiro deve poder adicionar comentários opcionais sobre a linha<br>- O sistema deve exibir a média de avaliações de cada linha<br>- O passageiro deve poder visualizar avaliações de outros usuários<br>- O sistema deve permitir editar ou excluir avaliações próprias<br>- O passageiro deve ter utilizado a linha recentemente para poder avaliá-la (validação baseada em histórico)<br>- O sistema deve detectar e filtrar avaliações fraudulentas ou ofensivas<br>- As avaliações devem ser ordenadas por data (mais recentes primeiro) |
| **Prioridade:** | Baixa |

---

### US04 - Rastrear Múltiplas Linhas Simultaneamente

*Autoria: Gabriel Maciel, 2025*

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | **RF35/ENT12** - Permitir rastreamento de múltiplas linhas de ônibus simultaneamente no mapa |
| **Descrição:** | Como **passageiro que precisa escolher entre várias opções de transporte**, eu quero **rastrear múltiplas linhas de ônibus simultaneamente no mapa**, para que **eu possa visualizar e comparar diferentes opções em tempo real e escolher a melhor alternativa para meu deslocamento**. |
| **Critérios de Aceitação:** | - O sistema deve permitir selecionar até 5 linhas de ônibus para rastreamento simultâneo<br>- Cada linha deve ser exibida no mapa com uma cor ou ícone distintivo<br>- O mapa deve mostrar a posição em tempo real de todos os ônibus das linhas selecionadas<br>- O passageiro deve poder adicionar ou remover linhas do rastreamento a qualquer momento<br>- O sistema deve exibir uma legenda identificando cada linha e sua cor correspondente<br>- Ao clicar em um ônibus no mapa, o sistema deve exibir informações da linha correspondente<br>- O sistema deve atualizar as posições dos ônibus a cada 20 segundos<br>- O aplicativo deve salvar as linhas rastreadas como favoritas para acesso rápido futuro<br>- O sistema deve alertar o passageiro caso a visualização fique sobrecarregada (muitas linhas na mesma região)<br>- O mapa deve permitir zoom e navegação suaves mesmo com múltiplas linhas sendo exibidas |
| **Prioridade:** | Alta |

---

### US05 - Apresentar Horários de Saída e Chegada dos Transportes

*Autoria: Fernanda Vaz, 2025.*

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | **RF05** - Exibir horários de saída e chegada dos transportes públicos |
| **Descrição:** | Como **passageiro do transporte público**, eu quero **visualizar os horários previstos de saída e chegada dos ônibus**, para que **eu possa planejar melhor meus deslocamentos e evitar longas esperas nos pontos**. |
| **Critérios de Aceitação:** | - O sistema deve exibir os horários de saída e chegada de cada linha em tempo real<br>- O passageiro deve poder selecionar uma linha e visualizar os horários de todos os pontos do percurso<br>- O sistema deve atualizar automaticamente as previsões de chegada com base na posição do veículo<br>- O usuário deve poder consultar horários planejados e horários previstos (ajustados em tempo real)<br>- O aplicativo deve indicar possíveis atrasos com ícones visuais (ex.: cor amarela ou vermelha)<br>- O passageiro deve poder favoritar linhas para acesso rápido aos horários<br>- O sistema deve funcionar mesmo com conexão instável, mostrando os últimos dados armazenados localmente |
| **Prioridade:** | Alta |

---

### US06 - Oferecer um Mapa Interativo com os Pontos de Ônibus e suas Linhas Correspondentes

*Autoria: Fernanda Vaz, 2025.*

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | **RF06** - Exibir pontos de ônibus e linhas em mapa interativo |
| **Descrição:** | Como **passageiro que utiliza transporte público**, eu quero **visualizar em um mapa interativo todos os pontos de ônibus e as linhas que passam por cada um deles**, para que **eu possa identificar o ponto mais próximo e escolher a linha mais conveniente**. |
| **Critérios de Aceitação:** | - O mapa deve exibir todos os pontos de ônibus georreferenciados<br>- O usuário deve poder clicar em um ponto para visualizar as linhas associadas<br>- O sistema deve mostrar o nome do ponto e o código identificador<br>- O mapa deve permitir zoom e movimentação fluida<br>- O usuário deve poder filtrar pontos por linha, região ou acessibilidade<br>- O aplicativo deve atualizar o mapa em tempo real com base na localização atual do usuário<br>- O sistema deve permitir alternar entre visualização de mapa padrão e modo satélite<br>- A interface deve ser responsiva e adaptada para dispositivos móveis |
| **Prioridade:** | Alta |

---

### US07 - Permitir Busca por Linha, Número ou Destino no Mapa Interativo

*Autoria: Fernanda Vaz, 2025.*

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | **RF07** - Permitir busca de linhas, pontos ou destinos no mapa |
| **Descrição:** | Como **passageiro que deseja planejar sua rota**, eu quero **buscar linhas de ônibus, números de rota ou destinos diretamente no mapa interativo**, para que **eu possa localizar facilmente as opções de transporte que atendem ao meu trajeto desejado**. |
| **Critérios de Aceitação:** | - O sistema deve permitir busca por número da linha, nome do destino ou ponto de interesse<br>- A busca deve exibir resultados em tempo real conforme o usuário digita<br>- Ao selecionar um resultado, o mapa deve centralizar e destacar a linha ou ponto correspondente<br>- O sistema deve permitir salvar buscas recentes<br>- O aplicativo deve sugerir linhas alternativas para o mesmo destino<br>- O campo de busca deve ser acessível em todas as telas do mapa<br>- O sistema deve permitir limpar facilmente o campo de pesquisa |
| **Prioridade:** | Média |

---

### US08 - Exibir Informações de Acessibilidade do Ônibus

*Autoria: Fernanda Vaz, 2025.*

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | **RF08** - Exibir informações de acessibilidade dos veículos |
| **Descrição:** | Como **passageiro com mobilidade reduzida**, eu quero **visualizar se o ônibus é acessível para cadeirantes e outras necessidades especiais**, para que **eu possa planejar meu deslocamento com segurança e conforto**. |
| **Critérios de Aceitação:** | - O sistema deve indicar claramente se cada ônibus possui acessibilidade (ex.: ícone de cadeira de rodas)<br>- O usuário deve poder filtrar linhas ou ônibus acessíveis<br>- O sistema deve exibir detalhes como rampa de acesso, assentos preferenciais e suporte para cão-guia<br>- As informações devem estar visíveis tanto na lista quanto no mapa<br>- O sistema deve permitir reportar inconsistências nas informações de acessibilidade<br>- O aplicativo deve garantir contraste e legibilidade dos ícones para acessibilidade visual<br>- O sistema deve manter conformidade com as diretrizes WCAG (Web Content Accessibility Guidelines) |
| **Prioridade:** | Alta |

---

### US09 - Oferecer recarga de cartão de transporte

*Autoria: Cauã Nicolas, 2025.*

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | **RF13** - Oferecer recarga de cartão de transporte (ex.: integração com BRB Mobilidade) |
| **Descrição:** | Como **usuário do transporte público**, eu quero **realizar recargas do meu cartão de transporte diretamente pelo aplicativo**, para que **eu possa evitar filas e ter mais praticidade na recarga**. |
| **Critérios de Aceitação:** | - O sistema deve permitir escolher o valor da recarga.<br>- O usuário deve poder pagar com cartão, PIX ou outros meios disponíveis.<br>- O aplicativo deve exibir a confirmação da recarga.<br>- O saldo deve ser atualizado após a confirmação do pagamento.<br>- O sistema deve integrar-se à API do BRB Mobilidade (ou equivalente). |
| **Prioridade:** | Média |

---

### US10 - Permitir integração com o cartão de transporte

*Autoria: Cauã Nicolas, 2025.*

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | **RF14** - Permitir integração com o cartão de transporte, incluindo saldo e recarga |
| **Descrição:** | Como **usuário do transporte público**, eu quero **visualizar o saldo e realizar recargas do meu cartão de transporte no aplicativo**, para que **eu possa acompanhar meu consumo e manter o cartão sempre carregado**. |
| **Critérios de Aceitação:** | - O sistema deve permitir o login com o número do cartão de transporte.<br>- O aplicativo deve exibir o saldo atualizado em tempo real.<br>- O sistema deve informar o histórico das últimas recargas.<br>- O saldo deve ser atualizado após cada transação.<br>- A integração deve ser segura e validada pela API oficial. |
| **Prioridade:** | Média |

--- 

### US11 - Visualizar histórico de viagens

*Autoria: Cauã Nicolas, 2025.*

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | **RF15** - Manter histórico de viagens do usuário |
| **Descrição:** | Como **passageiro**, eu quero **visualizar meu histórico de viagens realizadas**, para que **eu possa acompanhar meus trajetos, horários e valores gastos**. |
| **Critérios de Aceitação:** | - O sistema deve armazenar data, hora, linha e valor da viagem.<br>- O histórico deve exibir as viagens em ordem cronológica.<br>- O usuário deve poder filtrar por data ou linha.<br>- O histórico deve ser persistente mesmo após sair da conta.<br>- O sistema deve permitir exportar o histórico em formato PDF/CSV. |
| **Prioridade:** | Média |

--- 

### US12 - Reportar problemas de viagem

*Autoria: Cauã Nicolas, 2025.*

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | **RF16** - Permitir reportar problemas (motorista, ônibus, cobrança) com dados do veículo e horário |
| **Descrição:** | Como **usuário do transporte público**, eu quero **reportar problemas ocorridos durante uma viagem (como comportamento do motorista, falhas no ônibus ou cobrança incorreta)**, para que **a empresa responsável possa investigar e melhorar o serviço**. |
| **Critérios de Aceitação:** | - O sistema deve permitir selecionar o tipo de problema (motorista, ônibus, cobrança etc.).<br>- O aplicativo deve preencher automaticamente o número do veículo e horário da viagem recente.<br>- O usuário deve poder descrever o problema em campo de texto.<br>- O sistema deve enviar a reclamação para a empresa operadora correta.<br>- O usuário deve receber confirmação de envio e status do problema. |
| **Prioridade:** | Baixa |

---


## Referências Bibliográficas

<a id="ref-1"></a>

> ¹ PRESSMAN, R. S. *Engenharia de software: uma abordagem profissional*. 7. ed. Porto Alegre: AMGH, 2011.

<a id="ref-2"></a>

> ² MINISTÉRIO DA AGRICULTURA, PECUÁRIA E ABASTECIMENTO. Coordenação Geral de Tecnologia da Informação (CGTI). *História de Usuário*. Brasília: MAPA/CGTI, [s.d.]. Disponível em: <https://www.gov.br/agricultura/pt-br/acesso-a-informacao/licitacoes-e-contratos/edital/2019/pregao-eletronico-no-05-2018/templates-artefatos/estoria-de-usuario.doc/view>. Acesso em: 19 out. 2025.

---

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|:------:|:----:|:----------|:----------|:------------|
| 1.0 | 18/10 | Adição de introdução | Fernanda Vaz | Gabriel Maciel |
| 1.1 | 19/10 | Adição de Metodologia e Histórias de Usuário de US01 até US04 | Gabriel Maciel | Fernanda Vaz |
| 1.2 | 19/10 | Adição de Histórias de Usuário de US09 até US12 | Cauã Nicolas | Gabriel Maciel |

---

## Agradecimentos

Agradecemos o suporte da ferramenta de Inteligência Artificial Generativa Google Gemini no desenvolvimento deste trabalho. Em conformidade com o Código de Conduta da Sociedade Brasileira de Computação (SBC), declaramos que a ferramenta foi utilizada como auxílio na revisão gramatical e estilística do texto, na sugestão de estrutura para seções específicas do artigo, bem como na formatação de tabelas e na descrição de figuras. Ressaltamos que os autores assumem total responsabilidade por todo o conteúdo apresentado, incluindo sua originalidade e precisão. A ferramenta não figura como autora desta publicação.