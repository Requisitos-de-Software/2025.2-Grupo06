## Introdução

A atividade "Ouvir" do Extreme Programming (XP) é usada para gerar as "histórias de usuários", que definem as funcionalidades requisitadas. Segundo Pressman<sup>[1](#ref-1)</sup>, cada história "é escrita pelo cliente e é colocada em uma ficha. O cliente atribui um valor (uma prioridade) à história".

### Print da Referência

<a href="https://imgbb.com/"><img src="https://i.ibb.co/fV8V5mPK/image.png" alt="image" border="0"></a>

## Metodologia

Para a elaboração das histórias de usuário deste projeto, foi adotada a metodologia baseada nas diretrizes estabelecidas pela Coordenação Geral de Tecnologia da Informação (CGTI) do Ministério da Agricultura<sup>[2](#ref-2)</sup>. A técnica consiste em transformar os requisitos elicitados em narrativas centradas no usuário, descrevendo funcionalidades do ponto de vista de quem irá utilizá-las.

Cada história de usuário foi estruturada contendo os seguintes elementos essenciais:

- **Origem**: Identificação do requisito funcional ou não funcional que originou a história, incluindo a técnica de elicitação utilizada (Análise de Documentos, Brainstorm ou Entrevista);
- **Descrição**: Narrativa que responde "quem" (o usuário/persona), "o que" (a funcionalidade desejada) e "por que" (o valor ou benefício esperado), seguindo o formato padrão: "Como [tipo de usuário], eu quero [realizar ação], para que [obter benefício]";
- **Critérios de Aceitação**: Conjunto de condições mensuráveis e testáveis que devem ser satisfeitas para que a história seja considerada completa e pronta para implementação;
- **Prioridade**: Classificação da importância da história (Alta, Média ou Baixa) baseada no valor de negócio, impacto para o usuário e urgência de implementação.

Todas as histórias de usuário seguem o [Template de Tabela](#template-de-tabela-para-as-historias-de-usuario) apresentado abaixo, garantindo padronização e consistência na documentação dos requisitos.

### Template de História de Usuário

| **Campo** | **Descrição** |
| - | - |
| **Origem:** | [ID do Requisito/Fonte] - [Descrição resumida do requisito de origem] |
| **Descrição:** | Como **[tipo de usuário]**, eu quero **[ação/funcionalidade desejada]**, para que **[benefício ou valor obtido]**. |
| **Critérios de Aceitação:** | [Lista de condições que devem ser atendidas para que a história seja considerada completa] |
| **Prioridade:** | [Alta/Média/Baixa] |

## Histórias de Usuário

### US01 - Filtrar Ônibus por Empresa Operadora

| **Campo** | **Descrição** |
| - | - |
| **Origem:** | **RF26/RF03** - Filtrar ônibus por empresa operadora |
| **Descrição:** | Como **passageiro do transporte público**, eu quero **filtrar e visualizar ônibus de acordo com a empresa operadora**, para que **eu possa escolher linhas de empresas específicas de minha preferência ou evitar empresas com as quais tive experiências negativas**. |
| **Critérios de Aceitação:** | - O sistema deve exibir uma lista completa de todas as empresas operadoras disponíveis no DF<br>- O passageiro deve poder selecionar uma ou múltiplas empresas para filtrar<br>- O mapa deve exibir apenas os ônibus das empresas selecionadas<br>- O sistema deve mostrar o nome da empresa em cada linha de ônibus listada<br>- O filtro deve ser aplicado em tempo real ao selecionar/desselecionar empresas<br>- O sistema deve permitir limpar todos os filtros com um único clique<br>- O passageiro deve poder salvar suas preferências de empresa como padrão<br>- O sistema deve indicar quantas linhas e veículos estão disponíveis para cada empresa<br>- O filtro deve funcionar em conjunto com outros filtros (por linha, região, etc.)<br>- O aplicativo deve manter as configurações de filtro entre sessões |
| **Prioridade:** | Média |

### US02 - Acesso Web Rápido via QR Code

| **Campo** | **Descrição** |
| - | - |
| **Origem:** | **RF19/BRS17** - Disponibilizar versão web leve para acesso rápido em pontos de ônibus (via QR Code) |
| **Descrição:** | Como **passageiro aguardando no ponto de ônibus**, eu quero **acessar uma versão web leve do aplicativo através de QR Code**, para que **eu possa consultar informações sobre linhas e horários rapidamente sem precisar instalar o aplicativo completo no meu dispositivo**. |
| **Critérios de Aceitação:** | - Cada ponto de ônibus deve ter um QR Code visível e acessível<br>- Ao escanear o QR Code, o passageiro deve ser direcionado para uma página web responsiva<br>- A versão web deve carregar em menos de 3 segundos<br>- A versão web deve exibir linhas que passam naquele ponto específico<br>- A versão web deve mostrar horários previstos de chegada dos próximos ônibus<br>- A versão web deve funcionar em diferentes navegadores (Chrome, Safari, Firefox)<br>- A interface deve ser otimizada para dispositivos móveis<br>- Não deve ser necessário login ou cadastro para acesso básico<br>- A versão web deve consumir o mínimo de dados móveis possível |
| **Prioridade:** | Média |

### US03 - Avaliar Qualidade das Linhas

| **Campo** | **Descrição** |
| - | - |
| **Origem:** | **RF28/RNI04** - Permitir avaliação da qualidade do serviço de cada linha |
| **Descrição:** | Como **passageiro regular do transporte público**, eu quero **avaliar a qualidade do serviço de cada linha de ônibus que utilizo**, para que **eu possa compartilhar minha experiência e contribuir para a melhoria do serviço, além de ajudar outros passageiros a escolherem as melhores opções**. |
| **Critérios de Aceitação:** | - O passageiro deve poder atribuir uma nota de 1 a 5 estrelas para cada linha<br>- O sistema deve permitir avaliação de diferentes aspectos (pontualidade, conforto, limpeza, atendimento)<br>- O passageiro deve poder adicionar comentários opcionais sobre a linha<br>- O sistema deve exibir a média de avaliações de cada linha<br>- O passageiro deve poder visualizar avaliações de outros usuários<br>- O sistema deve permitir editar ou excluir avaliações próprias<br>- O passageiro deve ter utilizado a linha recentemente para poder avaliá-la (validação baseada em histórico)<br>- O sistema deve detectar e filtrar avaliações fraudulentas ou ofensivas<br>- As avaliações devem ser ordenadas por data (mais recentes primeiro) |
| **Prioridade:** | Baixa |

### US04 - Rastrear Múltiplas Linhas Simultaneamente

| **Campo** | **Descrição** |
| - | - |
| **Origem:** | **RF35/ENT12** - Permitir rastreamento de múltiplas linhas de ônibus simultaneamente no mapa |
| **Descrição:** | Como **passageiro que precisa escolher entre várias opções de transporte**, eu quero **rastrear múltiplas linhas de ônibus simultaneamente no mapa**, para que **eu possa visualizar e comparar diferentes opções em tempo real e escolher a melhor alternativa para meu deslocamento**. |
| **Critérios de Aceitação:** | - O sistema deve permitir selecionar até 5 linhas de ônibus para rastreamento simultâneo<br>- Cada linha deve ser exibida no mapa com uma cor ou ícone distintivo<br>- O mapa deve mostrar a posição em tempo real de todos os ônibus das linhas selecionadas<br>- O passageiro deve poder adicionar ou remover linhas do rastreamento a qualquer momento<br>- O sistema deve exibir uma legenda identificando cada linha e sua cor correspondente<br>- Ao clicar em um ônibus no mapa, o sistema deve exibir informações da linha correspondente<br>- O sistema deve atualizar as posições dos ônibus a cada 20 segundos<br>- O aplicativo deve salvar as linhas rastreadas como favoritas para acesso rápido futuro<br>- O sistema deve alertar o passageiro caso a visualização fique sobrecarregada (muitas linhas na mesma região)<br>- O mapa deve permitir zoom e navegação suaves mesmo com múltiplas linhas sendo exibidas |
| **Prioridade:** | Alta |

## Referência bibliográfica

<a id="ref-1"></a>

> <sup>1.</sup> **PRESSMAN, R. S.** *Engenharia de software: uma abordagem profissional*. 7. ed. Porto Alegre: AMGH, 2011.

<a id="ref-2"></a>

> <sup>2.</sup> **MINISTÉRIO DA AGRICULTURA, PECUÁRIA E ABASTECIMENTO. Coordenação Geral de Tecnologia da Informação (CGTI).** *História de Usuário*. Brasília: MAPA/CGTI, [s.d.]. Disponível em: <https://www.gov.br/agricultura/pt-br/acesso-a-informacao/licitacoes-e-contratos/edital/2019/pregao-eletronico-no-05-2018/templates-artefatos/estoria-de-usuario.doc/view>. Acesso em: 19 out. 2025.


## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|:-------|:-----|:-----------|:------------|:-------------|
| 1.0 | 18/10 | Adição de introdução | Fernanda Vaz | Gabriel Maciel |
| 1.0 | 18/10 | Adição de Metodologia e Histórias de Usuário de US01 até US04 | Fernanda Vaz | Gabriel Maciel |

## Agradecimentos

> Agradecemos o suporte da ferramenta de Inteligência Artificial Generativa Google Gemini no desenvolvimento deste trabalho. Em conformidade com o Código de Conduta da Sociedade Brasileira de Computação (SBC), declaramos que a ferramenta foi utilizada como auxílio na revisão gramatical e estilística do texto, na sugestão de estrutura para seções específicas do artigo, bem como na formatação de tabelas e na descrição de figuras. Ressaltamos que os autores assumem total responsabilidade por todo o conteúdo apresentado, incluindo sua originalidade e precisão. A ferramenta não figura como autora desta publicação.