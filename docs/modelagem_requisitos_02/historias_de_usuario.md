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

### **US01 - Filtrar Ônibus por Empresa Operadora**

*Autoria: Gabriel Maciel, 2025*

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | **RF26/RF03 (Análise de Documentos)** - Filtrar ônibus por empresa operadora |
| **Descrição:** | Como **passageiro do transporte público**, eu quero **filtrar e visualizar ônibus de acordo com a empresa operadora**, para que **eu possa escolher linhas de empresas específicas de minha preferência ou evitar empresas com as quais tive experiências negativas**. |
| **Critérios de Aceitação:** | - O sistema deve exibir uma lista completa de todas as empresas operadoras disponíveis no DF<br>- O passageiro deve poder selecionar uma ou múltiplas empresas para filtrar<br>- O mapa deve exibir apenas os ônibus das empresas selecionadas<br>- O sistema deve mostrar o nome da empresa em cada linha de ônibus listada<br>- O filtro deve ser aplicado em tempo real ao selecionar/desselecionar empresas<br>- O sistema deve permitir limpar todos os filtros com um único clique<br>- O passageiro deve poder salvar suas preferências de empresa como padrão<br>- O sistema deve indicar quantas linhas e veículos estão disponíveis para cada empresa<br>- O filtro deve funcionar em conjunto com outros filtros (por linha, região, etc.)<br>- O aplicativo deve manter as configurações de filtro entre sessões |
| **Prioridade:** | Média |

---

### **US02 - Acesso Web Rápido via QR Code**

*Autoria: Gabriel Maciel, 2025*

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | **RF19/BRS17** - Disponibilizar versão web leve para acesso rápido em pontos de ônibus (via QR Code) |
| **Descrição:** | Como **passageiro aguardando no ponto de ônibus**, eu quero **acessar uma versão web leve do aplicativo através de QR Code**, para que **eu possa consultar informações sobre linhas e horários rapidamente sem precisar instalar o aplicativo completo no meu dispositivo**. |
| **Critérios de Aceitação:** | - Cada ponto de ônibus deve ter um QR Code visível e acessível<br>- Ao escanear o QR Code, o passageiro deve ser direcionado para uma página web responsiva<br>- A versão web deve carregar em menos de 3 segundos<br>- A versão web deve exibir linhas que passam naquele ponto específico<br>- A versão web deve mostrar horários previstos de chegada dos próximos ônibus<br>- A versão web deve funcionar em diferentes navegadores (Chrome, Safari, Firefox)<br>- A interface deve ser otimizada para dispositivos móveis<br>- Não deve ser necessário login ou cadastro para acesso básico<br>- A versão web deve consumir o mínimo de dados móveis possível |
| **Prioridade:** | Média |

---

### **US03 - Avaliar Qualidade das Linhas**

*Autoria: Gabriel Maciel, 2025*

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | **RF28/RNI04** - Permitir avaliação da qualidade do serviço de cada linha |
| **Descrição:** | Como **passageiro regular do transporte público**, eu quero **avaliar a qualidade do serviço de cada linha de ônibus que utilizo**, para que **eu possa compartilhar minha experiência e contribuir para a melhoria do serviço, além de ajudar outros passageiros a escolherem as melhores opções**. |
| **Critérios de Aceitação:** | - O passageiro deve poder atribuir uma nota de 1 a 5 estrelas para cada linha<br>- O sistema deve permitir avaliação de diferentes aspectos (pontualidade, conforto, limpeza, atendimento)<br>- O passageiro deve poder adicionar comentários opcionais sobre a linha<br>- O sistema deve exibir a média de avaliações de cada linha<br>- O passageiro deve poder visualizar avaliações de outros usuários<br>- O sistema deve permitir editar ou excluir avaliações próprias<br>- O passageiro deve ter utilizado a linha recentemente para poder avaliá-la (validação baseada em histórico)<br>- O sistema deve detectar e filtrar avaliações fraudulentas ou ofensivas<br>- As avaliações devem ser ordenadas por data (mais recentes primeiro) |
| **Prioridade:** | Baixa |

---

### **US04 - Rastrear Múltiplas Linhas Simultaneamente**

*Autoria: Gabriel Maciel, 2025*

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | **RF35/ENT12** - Permitir rastreamento de múltiplas linhas de ônibus simultaneamente no mapa |
| **Descrição:** | Como **passageiro que precisa escolher entre várias opções de transporte**, eu quero **rastrear múltiplas linhas de ônibus simultaneamente no mapa**, para que **eu possa visualizar e comparar diferentes opções em tempo real e escolher a melhor alternativa para meu deslocamento**. |
| **Critérios de Aceitação:** | - O sistema deve permitir selecionar até 5 linhas de ônibus para rastreamento simultâneo<br>- Cada linha deve ser exibida no mapa com uma cor ou ícone distintivo<br>- O mapa deve mostrar a posição em tempo real de todos os ônibus das linhas selecionadas<br>- O passageiro deve poder adicionar ou remover linhas do rastreamento a qualquer momento<br>- O sistema deve exibir uma legenda identificando cada linha e sua cor correspondente<br>- Ao clicar em um ônibus no mapa, o sistema deve exibir informações da linha correspondente<br>- O sistema deve atualizar as posições dos ônibus a cada 20 segundos<br>- O aplicativo deve salvar as linhas rastreadas como favoritas para acesso rápido futuro<br>- O sistema deve alertar o passageiro caso a visualização fique sobrecarregada (muitas linhas na mesma região)<br>- O mapa deve permitir zoom e navegação suaves mesmo com múltiplas linhas sendo exibidas |
| **Prioridade:** | Alta |

---

### **US05 - Apresentar Horários de Saída e Chegada dos Transportes**

*Autoria: Fernanda Vaz, 2025.*

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | **RF05** - Exibir horários de saída e chegada dos transportes públicos |
| **Descrição:** | Como **passageiro do transporte público**, eu quero **visualizar os horários previstos de saída e chegada dos ônibus**, para que **eu possa planejar melhor meus deslocamentos e evitar longas esperas nos pontos**. |
| **Critérios de Aceitação:** | - O sistema deve exibir os horários de saída e chegada de cada linha em tempo real<br>- O passageiro deve poder selecionar uma linha e visualizar os horários de todos os pontos do percurso<br>- O sistema deve atualizar automaticamente as previsões de chegada com base na posição do veículo<br>- O usuário deve poder consultar horários planejados e horários previstos (ajustados em tempo real)<br>- O aplicativo deve indicar possíveis atrasos com ícones visuais (ex.: cor amarela ou vermelha)<br>- O passageiro deve poder favoritar linhas para acesso rápido aos horários<br>- O sistema deve funcionar mesmo com conexão instável, mostrando os últimos dados armazenados localmente |
| **Prioridade:** | Alta |

---

### **US06 - Oferecer um Mapa Interativo com os Pontos de Ônibus e suas Linhas Correspondentes**

*Autoria: Fernanda Vaz, 2025.*

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | **RF06** - Exibir pontos de ônibus e linhas em mapa interativo |
| **Descrição:** | Como **passageiro que utiliza transporte público**, eu quero **visualizar em um mapa interativo todos os pontos de ônibus e as linhas que passam por cada um deles**, para que **eu possa identificar o ponto mais próximo e escolher a linha mais conveniente**. |
| **Critérios de Aceitação:** | - O mapa deve exibir todos os pontos de ônibus georreferenciados<br>- O usuário deve poder clicar em um ponto para visualizar as linhas associadas<br>- O sistema deve mostrar o nome do ponto e o código identificador<br>- O mapa deve permitir zoom e movimentação fluida<br>- O usuário deve poder filtrar pontos por linha, região ou acessibilidade<br>- O aplicativo deve atualizar o mapa em tempo real com base na localização atual do usuário<br>- O sistema deve permitir alternar entre visualização de mapa padrão e modo satélite<br>- A interface deve ser responsiva e adaptada para dispositivos móveis |
| **Prioridade:** | Alta |

---
### **US07 - Integrar informações de outros modais (metrô, outros ônibus) em rotas multimodais**

*Autoria: Fernanda Vaz, 2025.*

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | **RF07** - Integrar informações de outros modais de transporte |
| **Descrição:** | Como **passageiro que deseja planejar sua rota**, eu quero **visualizar e integrar informações de diferentes modais de transporte (metrô, ônibus de outras empresas, etc.) no planejamento de rotas**, para que **eu possa escolher a melhor combinação de transportes para chegar ao meu destino**. |
| **Critérios de Aceitação:** | - O sistema deve exibir opções de rotas que combinem ônibus com metrô<br>- O sistema deve incluir informações de linhas de ônibus de diferentes empresas/operadores<br>- O aplicativo deve mostrar pontos de integração entre diferentes modais<br>- As rotas multimodais devem exibir tempo estimado total da viagem<br>- O sistema deve indicar tempo de caminhada entre conexões<br>- O aplicativo deve mostrar tarifas de cada modal separadamente<br>- O usuário deve poder filtrar rotas por preferência de modal<br>- O sistema deve atualizar informações em tempo real de todos os modais integrados |
| **Prioridade:** | Média |

---

### **US08 - Exibir Informações de Acessibilidade do Ônibus**

*Autoria: Fernanda Vaz, 2025.*

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | **RF08** - Exibir informações de acessibilidade dos veículos |
| **Descrição:** | Como **passageiro com mobilidade reduzida**, eu quero **visualizar se o ônibus é acessível para cadeirantes e outras necessidades especiais**, para que **eu possa planejar meu deslocamento com segurança e conforto**. |
| **Critérios de Aceitação:** | - O sistema deve indicar claramente se cada ônibus possui acessibilidade (ex.: ícone de cadeira de rodas)<br>- O usuário deve poder filtrar linhas ou ônibus acessíveis<br>- O sistema deve exibir detalhes como rampa de acesso, assentos preferenciais e suporte para cão-guia<br>- As informações devem estar visíveis tanto na lista quanto no mapa<br>- O sistema deve permitir reportar inconsistências nas informações de acessibilidade<br>- O aplicativo deve garantir contraste e legibilidade dos ícones para acessibilidade visual<br>- O sistema deve manter conformidade com as diretrizes WCAG (Web Content Accessibility Guidelines) |
| **Prioridade:** | Alta |

---

### **US09 - Oferecer recarga de cartão de transporte**

*Autoria: Cauã Nicolas, 2025.*

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | **RF13** - Oferecer recarga de cartão de transporte (ex.: integração com BRB Mobilidade) |
| **Descrição:** | Como **usuário do transporte público**, eu quero **realizar recargas do meu cartão de transporte diretamente pelo aplicativo**, para que **eu possa evitar filas e ter mais praticidade na recarga**. |
| **Critérios de Aceitação:** | - O sistema deve permitir escolher o valor da recarga.<br>- O usuário deve poder pagar com cartão, PIX ou outros meios disponíveis.<br>- O aplicativo deve exibir a confirmação da recarga.<br>- O saldo deve ser atualizado após a confirmação do pagamento.<br>- O sistema deve integrar-se à API do BRB Mobilidade (ou equivalente). |
| **Prioridade:** | Média |

---

### **US10 - Permitir integração com o cartão de transporte**

*Autoria: Cauã Nicolas, 2025.*

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | **RF14** - Permitir integração com o cartão de transporte, incluindo saldo e recarga |
| **Descrição:** | Como **usuário do transporte público**, eu quero **visualizar o saldo e realizar recargas do meu cartão de transporte no aplicativo**, para que **eu possa acompanhar meu consumo e manter o cartão sempre carregado**. |
| **Critérios de Aceitação:** | - O sistema deve permitir o login com o número do cartão de transporte.<br>- O aplicativo deve exibir o saldo atualizado em tempo real.<br>- O sistema deve informar o histórico das últimas recargas.<br>- O saldo deve ser atualizado após cada transação.<br>- A integração deve ser segura e validada pela API oficial. |
| **Prioridade:** | Média |

--- 

### **US11 - Visualizar histórico de viagens**

*Autoria: Cauã Nicolas, 2025.*

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | **RF15** - Manter histórico de viagens do usuário |
| **Descrição:** | Como **passageiro**, eu quero **visualizar meu histórico de viagens realizadas**, para que **eu possa acompanhar meus trajetos, horários e valores gastos**. |
| **Critérios de Aceitação:** | - O sistema deve armazenar data, hora, linha e valor da viagem.<br>- O histórico deve exibir as viagens em ordem cronológica.<br>- O usuário deve poder filtrar por data ou linha.<br>- O histórico deve ser persistente mesmo após sair da conta.<br>- O sistema deve permitir exportar o histórico em formato PDF/CSV. |
| **Prioridade:** | Média |

--- 

### **US12 - Reportar problemas de viagem**

*Autoria: Cauã Nicolas, 2025.*

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | **RF16** - Permitir reportar problemas (motorista, ônibus, cobrança) com dados do veículo e horário |
| **Descrição:** | Como **usuário do transporte público**, eu quero **reportar problemas ocorridos durante uma viagem (como comportamento do motorista, falhas no ônibus ou cobrança incorreta)**, para que **a empresa responsável possa investigar e melhorar o serviço**. |
| **Critérios de Aceitação:** | - O sistema deve permitir selecionar o tipo de problema (motorista, ônibus, cobrança etc.).<br>- O aplicativo deve preencher automaticamente o número do veículo e horário da viagem recente.<br>- O usuário deve poder descrever o problema em campo de texto.<br>- O sistema deve enviar a reclamação para a empresa operadora correta.<br>- O usuário deve receber confirmação de envio e status do problema. |
| **Prioridade:** | Baixa |

---

### **US13 - Visualizar Localização dos Ônibus em Tempo Real no Mapa**

_Autoria: João Gabriel, 2025_

| Campo | Descrição |
|---|---|
| **Origem:** | RF01/ENT03 - Exibir a localização dos ônibus em tempo real no mapa |
| **Descrição:** | Como **passageiro do transporte público**, eu quero **visualizar a localização exata dos ônibus em tempo real no mapa**, para que **eu possa ter certeza de que o ônibus está a caminho e estimar com precisão o tempo de espera no ponto**. |
| **Critérios de Aceitação:** | - O sistema deve exibir ícones de ônibus sobrepostos no mapa interativo.<br>- A posição dos ônibus deve ser atualizada automaticamente a intervalos regulares (ex: a cada 15-30 segundos).<br>- Cada ícone de ônibus deve representar um veículo físico em operação.<br>- Ao tocar no ícone de um ônibus, o sistema deve exibir informações básicas da linha (número, destino).<br>- O mapa deve continuar responsivo e com navegação fluida mesmo com múltiplos ônibus sendo exibidos.<br>- O sistema deve lidar graciosamente com a perda momentânea de conexão, exibindo a última posição conhecida com um indicativo de "dados desatualizados".<br>- A localização deve ser mostrada com uma precisão que permita identificar em qual rua ou avenida o ônibus se encontra. |
| **Prioridade:** | Alta |

---

### **US14 - Consultar Tempo Estimado de Chegada do Ônibus**

_Autoria: João Gabriel, 2025_

| Campo | Descrição |
|---|---|
| **Origem:** | RF02/ENT04 - Mostrar o tempo estimado de chegada do ônibus à parada |
| **Descrição:** | Como **passageiro aguardando no ponto**, eu quero **consultar o tempo estimado de chegada (TEC) do meu ônibus**, para que **eu possa gerenciar meu tempo de espera com mais segurança e tomar decisões (ex: esperar, chamar um táxi, escolher outra rota)**. |
| **Critérios de Aceitação:** | - Ao selecionar um ponto de ônibus no mapa ou em uma lista, o sistema deve listar as linhas que passam por ele.<br>- Para cada linha listada, o sistema deve exibir o tempo estimado de chegada dos próximos ônibus (ex: "Chega em 8 min" ou "Previsto para 14:35").<br>- O TEC deve ser calculado em tempo real com base na localização GPS do ônibus, trânsito e distância do ponto.<br>- A interface deve destacar visualmente se o ônibus está "Próximo" (ex: verde) ou com "Atraso" (ex: laranja/vermelho).<br>- O passageiro deve poder atualizar manualmente a previsão para obter os dados mais recentes.<br>- O sistema deve funcionar para qualquer ponto de ônibus cadastrado no sistema, não apenas para a localização atual do usuário. |
| **Prioridade:** | Alta |

---

### **US15 - Planejar uma Viagem com Rotas Sugeridas**

_Autoria: João Gabriel, 2025_

| Campo | Descrição |
|---|---|
| **Origem:** | RF03 - Permitir planejamento de viagem (origem → destino) com rotas sugeridas |
| **Descrição:** | Como **passageiro que precisa se deslocar pela cidade**, eu quero **planejar uma viagem informando meu ponto de origem e destino para receber rotas sugeridas de ônibus**, para que **eu possa encontrar a melhor opção de itinerário, mesmo em rotas que não conheço**. |
| **Critérios de Aceitação:** | - O sistema deve fornecer um campo para inserir endereço de origem e destino (com suporte a autocompletar).<br>- Deve ser possível usar a localização atual como origem.<br>- O sistema deve calcular e apresentar pelo menos 2-3 opções de rotas diferentes.<br>- Cada rota sugerida deve mostrar: linhas a serem utilizadas, pontos de embarque/desembarque, tempo total de viagem e tempo de caminhada.<br>- A rota deve ser desenhada visualmente no mapa.<br>- O sistema deve priorizar rotas com menor tempo total, menor número de baldeações ou que evitem caminhadas longes (com opção de filtro).<br>- As rotas devem considerar os horários de operação das linhas no momento do planejamento. |
| **Prioridade:** | Média |

---

### **US16 - Pesquisar por Linhas e Rotas de Ônibus**

_Autoria: João Gabriel, 2025_

| Campo | Descrição |
|---|---|
| **Origem:** | RF04/ENT01 - Permitir pesquisa por linhas e rotas de ônibus |
| **Descrição:** | Como **passageiro que sabe qual linha ou destino deseja**, eu quero **pesquisar diretamente por linhas, números de ônibus ou nomes de destinos**, para que **eu possa acessar rapidamente as informações específicas que preciso, sem ter que navegar pelo mapa**. |
| **Critérios de Aceitação:** | - Deve haver uma barra de busca acessível na tela principal.<br>- A busca deve retornar resultados em tempo real ("search as you type").<br>- A pesquisa deve funcionar por número da linha (ex: "0.108.1"), nome do destino (ex: "Rodoviária") ou termo aproximado (ex: "Eixo Sul").<br>- Ao selecionar um resultado, o sistema deve exibir detalhes da linha, como mapa do percurso, horários e pontos de parada.<br>- O sistema deve permitir salvar linhas como "Favoritas" para acesso rápido futuro.<br>- Deve ser possível visualizar todas as linhas de ônibus em uma lista, com opção de ordenar por número ou nome. |
| **Prioridade:** | Alta |

---

### **US17 - Visualizar Horários de Saída e Chegada dos Transportes**

_Autoria: João Gabriel, 2025_

| Campo | Descrição |
|---|---|
| **Origem:** | RF05/ENT02 - Apresentar horários de saída e chegada dos transportes |
| **Descrição:** | Como **passageiro que precisa cumprir horários**, eu quero **visualizar os horários programados de saída e chegada dos ônibus em cada ponto**, para que **eu possa planejar minha ida ao ponto com antecedência e não perder o ônibus**. |
| **Critérios de Aceitação:** | - Ao visualizar os detalhes de uma linha, o usuário deve poder acessar uma aba de "Horários".<br>- O sistema deve exibir uma tabela ou lista com os horários programados de partida dos terminais e chegada aos pontos principais.<br>- Os horários devem ser organizados por dia útil (segunda a sexta), sábado e domingo/feriado.<br>- A interface deve diferenciar claramente entre o horário programado e a previsão em tempo real (TEC da US14).<br>- O usuário deve poder selecionar um ponto específico para ver os horários de passagem previstos naquele local.<br>- Os horários devem ser os oficiais fornecidos pela empresa operadora/DFTrans. |
| **Prioridade:** | Alta |

---

### **US18 - Integração com Assistentes Virtuais**

*Autoria: Gabriel Maciel, 2025*

| Campo | Descrição |
|---|---|
| **Origem:** | RF34/BRS16 - Integração com assistentes virtuais (Alexa, Google Assistant) |
| **Descrição:** | Como **usuário do transporte público**, eu quero **utilizar assistentes virtuais como Alexa ou Google Assistant para acessar informações de ônibus**, para que **eu possa consultar horários, localização de ônibus e planejar viagens sem precisar abrir o aplicativo manualmente**. |
| **Critérios de Aceitação:** | - O sistema deve permitir integração com Alexa e Google Assistant (inicialmente).<br>- O usuário deve poder fazer perguntas de voz como "Qual o próximo ônibus para o Eixo Sul?"<br>- O assistente deve retornar informações de tempo estimado de chegada do ônibus.<br>- O assistente deve permitir consultar saldo do cartão de transporte do usuário.<br>- O assistente deve permitir realizar recargas de cartão (com confirmação de segurança).<br>- O assistente deve autenticar o usuário de forma segura antes de acessar dados pessoais.<br>- A integração deve funcionar de forma responsiva (respostas em menos de 3 segundos).<br>- O usuário deve poder desabilitar a integração a qualquer momento nas configurações da conta. |
| **Prioridade:** | Baixa |

---

### **US19 - Suporte Multilíngue**

*Autoria: Gabriel Maciel, 2025*

| Campo | Descrição |
|---|---|
| **Origem:** | RF36/ENT22 - Oferecer suporte multilíngue (português e inglês, no mínimo) |
| **Descrição:** | Como **usuário que não fala português ou turista visitando o Distrito Federal**, eu quero **utilizar o aplicativo em diferentes idiomas, especialmente em português e inglês**, para que **eu possa compreender facilmente todas as informações sobre linhas, horários e navegação no aplicativo**. |
| **Critérios de Aceitação:** | - O aplicativo deve suportar, no mínimo, português (Brasil) e inglês.<br>- O usuário deve poder alterar o idioma nas configurações do aplicativo.<br>- O idioma selecionado deve ser mantido entre sessões (persistência).<br>- Todos os textos da interface devem estar traduzidos no idioma selecionado (nomes de linhas, horários, mensagens de erro, etc.).<br>- As instruções do sistema e notificações devem estar disponíveis no idioma escolhido.<br>- Os nomes dos destinos e pontos de parada devem ser exibidos em ambos os idiomas quando possível.<br>- A detecção de idioma do dispositivo deve ser usada para pré-definir o idioma do aplicativo na primeira instalação.<br>- O aplicativo deve estar conformidade com as diretrizes de localização internacional (RTL, formatação de números e datas). |
| **Prioridade:** | Média |

---

### **US20 - Permitir favoritar linhas ou paradas para acesso rápido**

*Autoria: Cauã Nicolas, 2025*

| Campo | Descrição |
|---|---|
| **Origem:** | RF24 – Permitir favoritar linhas ou paradas para acesso rápido. |
| **Descrição:** | Como **usuário que utiliza frequentemente determinadas linhas de ônibus**, eu quero **poder favoritar linhas ou paradas específicas**, para que eu **consiga acessá-las rapidamente sem precisar pesquisar toda vez**. |
| **Critérios de Aceitação:** | - O usuário deve conseguir favoritar uma linha ou parada com apenas um toque.<br>- As linhas e paradas favoritas devem aparecer em uma seção dedicada ("Favoritos").<br>- Deve ser possível desfavoritar uma linha ou parada a qualquer momento.<br>- As informações favoritas devem permanecer salvas entre sessões do aplicativo.<br> |
| **Prioridade:** | Média |

---

### **US21 - Ampliar a cobertura e exibir informações em regiões afastadas do DF**

*Autoria: Cauã Nicolas, 2025*

| Campo | Descrição |
|---|---|
| **Origem:** | RF25 – Ampliar a cobertura e exibir informações também em regiões afastadas do Distrito Federal. |
| **Descrição:** | Como **usuário que mora em áreas afastadas do Distrito Federal**, eu quero **ter acesso às informações de linhas e horários de ônibus da minha região**, para que eu possa **planejar minhas viagens com a mesma praticidade que os usuários das regiões centrais**. |
| **Critérios de Aceitação:** | - O sistema deve exibir linhas e horários que atendem regiões mais afastadas do DF.<br>- As informações de localização e tempo estimado de chegada devem funcionar nessas áreas.<br>- A cobertura deve incluir pelo menos as principais paradas e rotas de regiões periféricas.<br>- Deve haver atualização automática quando novas linhas forem adicionadas.<br> |
| **Prioridade:** | Média |

---

### **US22 - Visualizar Lotação Estimada do Ônibus**

*Autoria: João Ramos, 2025*

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | **RF09** - Indicar lotação do ônibus (vazio, moderado, lotado) |
| **Descrição:** | Como **passageiro do transporte público**, eu quero **visualizar a lotação estimada do ônibus (vazio, moderado, lotado) antes que ele chegue ao ponto**, para que **eu possa decidir se embarco neste veículo ou espero o próximo, buscando mais conforto**. |
| **Critérios de Aceitação:** | - O sistema deve exibir um indicador visual claro de lotação (ex: ícones ou cores) para cada ônibus em tempo real.<br>- Os níveis de lotação devem ser "Vazio", "Moderado" e "Lotado".<br>- A informação de lotação deve estar visível na lista de próximos ônibus do ponto e ao selecionar um veículo no mapa.<br>- O sistema deve possuir uma legenda clara explicando o significado de cada indicador de lotação.<br>- A informação de lotação deve ser atualizada em tempo real com base em sensores no veículo ou dados colaborativos (US19).<br>- Caso a informação não esteja disponível, o sistema deve indicar "Lotação não informada". |
| **Prioridade:** | Média |

---

### **US23 - Reportar Lotação do Ônibus (Colaborativo)**

*Autoria: João Ramos, 2025*

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | **R10** - Permitir que usuários reportem a lotação do ônibus (sistema colaborativo) |
| **Descrição:** | Como **passageiro que está dentro do ônibus**, eu quero **reportar o nível de lotação atual do veículo (vazio, moderado, lotado)**, para que **eu possa contribuir com o sistema colaborativo e ajudar outros passageiros a tomar decisões**. |
| **Critérios de Aceitação:** | - O sistema deve permitir o reporte de lotação apenas para passageiros que estão próximos ou dentro da rota do veículo (validação por GPS).<br>- O usuário deve poder escolher entre três opções simples: "Vazio", "Moderado", "Lotado".<br>- O reporte deve ser rápido e acessível (ex: 2 cliques).<br>- O sistema deve agregar os reportes recebidos nos últimos minutos para calcular o status de lotação (usado na US18).<br>- O sistema deve limitar a frequência de reportes por usuário/veículo para evitar spam (ex: um reporte a cada 10 minutos por veículo).<br>- O usuário deve receber uma confirmação visual de que seu reporte foi registrado com sucesso. |
| **Prioridade:** | Média |

---

### **US24 - Receber Alerta de Proximidade do Ônibus**

*Autoria: João Ramos, 2025*

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | **RF11** - Enviar notificação quando o ônibus estiver a X minutos da parada |
| **Descrição:** | Como **passageiro aguardando no ponto**, eu quero **definir um alerta para ser notificado quando o ônibus de uma linha específica estiver a X minutos da minha parada**, para que **eu possa me preparar para o embarque sem precisar checar o aplicativo constantemente**. |
| **Critérios de Aceitação:** | - O usuário deve poder selecionar uma linha e um ponto de parada para ativar o alerta.<br>- O sistema deve permitir que o usuário configure o tempo de antecedência do alerta (ex: 3 min, 5 min, 10 min).<br>- A notificação deve ser enviada como "push notification" no dispositivo móvel.<br>- A notificação deve funcionar mesmo se o aplicativo estiver em segundo plano.<br>- A notificação deve informar claramente a linha e o tempo restante (ex: "Sua linha 108 está a 5 minutos").<br>- O alerta deve ser único (não repetitivo) e ser desativado automaticamente após a notificação ou passagem do veículo.<br>- O usuário deve poder cancelar o alerta a qualquer momento antes de ser disparado. |
| **Prioridade:** | Alta |

---

### **US25 - Receber Alertas de Alterações no Serviço**

*Autoria: João Ramos, 2025*

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | **R12** - Enviar alertas sobre atrasos, mudanças de rota ou alterações nos horários |
| **Descrição:** | Como **passageiro do transporte público**, eu quero **receber alertas e notificações sobre mudanças inesperadas no serviço, como atrasos significativos, mudanças de rota ou alterações de horário**, para que **eu possa me antecipar a problemas e planejar rotas alternativas**. |
| **Critérios de Aceitação:** | - O sistema deve enviar notificações "push" para incidentes relevantes (ex: greves, bloqueios de via, desvios longos).<br>- O usuário deve poder configurar se deseja receber alertas de todas as linhas ou apenas de suas "Linhas Favoritas".<br>- Os alertas devem ser claros, indicando a(s) linha(s) afetada(s), o tipo de problema e a região impactada.<br>- O aplicativo deve ter uma seção de "Avisos" ou "Status do Serviço" onde todos os alertas ativos possam ser consultados.<br>- Os alertas devem ser emitidos pela central de controle ou operadora.<br>- A notificação deve ser removida automaticamente quando o problema for resolvido. |
| **Prioridade:** | Alta |

---

---

### US26 - Consultar Horários e Rotas Salvas Offline

*Autoria: João Ramos, 2025*

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | **RFN-11 (RNI05/ENT18/BRS06)** - Funcionamento offline para consulta a rotas salvas e horários |
| **Descrição:** | Como **passageiro com conexão de internet limitada ou instável**, eu quero **acessar os horários programados das linhas e minhas rotas salvas mesmo estando offline**, para que **eu possa planejar meus deslocamentos essenciais sem depender de uma conexão de dados ativa**. |
| **Critérios de Aceitação:** | - O aplicativo deve armazenar localmente (cache) a tabela de horários programados (dias úteis, sábados, domingos) de todas as linhas.<br>- O usuário deve poder salvar rotas específicas (criadas no planejador de viagem) para acesso offline.<br>- Ao abrir o app sem internet, o sistema deve entrar em "Modo Offline" e exibir um aviso claro.<br>- No Modo Offline, as funções de tempo real (localização de ônibus, TEC) devem ser desabilitadas.<br>- O usuário deve conseguir pesquisar e visualizar os horários programados de qualquer linha.<br>- O usuário deve conseguir acessar sua lista de "Rotas Salvas" offline.<br>- Os dados offline devem ser atualizados automaticamente em segundo plano quando o app estiver online. |
| **Prioridade:** | Média |

---

### US27 - Listar Linhas por Ponto de Parada

*Autoria: João Ramos, 2025*

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | **RF18 (BRS)** - Listar linhas que passam em uma parada específica |
| **Descrição:** | Como **passageiro em um ponto de ônibus**, eu quero **selecionar uma parada (no mapa ou por pesquisa) e ver uma lista de todas as linhas que passam por ela**, para que **eu possa descobrir rapidamente quais são minhas opções de transporte naquela localização**. |
| **Critérios de Aceitação:** | - O usuário deve poder clicar em um ícone de ponto de ônibus no mapa para selecioná-lo.<br>- O usuário deve poder pesquisar por um ponto usando seu código ou nome/endereço.<br>- Ao selecionar um ponto, o sistema deve exibir uma lista clara com todas as linhas de ônibus associadas a ele.<br>- A lista deve mostrar o número da linha e seu destino principal.<br>- O sistema deve exibir o Tempo Estimado de Chegada (TEC) dos próximos veículos de cada linha listada (integração com US14).<br>- O usuário deve poder clicar em uma linha da lista para ver seus detalhes (rota completa, horários). |
| **Prioridade:** | Alta |

---

### US28 - Visualizar Alertas de Trânsito e Rotas Alternativas

*Autoria: João Ramos, 2025*

| **Campo** | **Descrição** |
|-----------|---------------|
| **Origem:** | **RF21 (BRS12)** - Mostrar alertas de trânsito, acidentes e rotas alternativas |
| **Descrição:** | Como **passageiro planejando uma viagem ou já em deslocamento**, eu quero **ser informado sobre incidentes de trânsito (acidentes, congestionamentos, obras) que afetam as rotas de ônibus**, para que **eu possa entender a causa de atrasos e receber sugestões de rotas alternativas**. |
| **Critérios de Aceitação:** | - O sistema deve exibir ícones no mapa indicando a localização e o tipo de incidente de trânsito relevante (ex: acidente, obra, via bloqueada).<br>- O planejador de rotas (US15) deve considerar o trânsito em tempo real para calcular o tempo estimado da viagem.<br>- Se um incidente grave impactar uma rota planejada ou favorita, o sistema deve enviar um alerta (similar à US21).<br>- Ao visualizar uma rota impactada por trânsito, o sistema deve recalcular e sugerir rotas alternativas, se disponíveis.<br>- As informações de trânsito devem ser obtidas de uma fonte externa confiável (ex: API de tráfego).<br>- O usuário deve poder tocar em um ícone de incidente para obter mais detalhes. |
| **Prioridade:** | Média |

---

### US29 - Receber Previsão Inteligente de Horários com Base em Dados Históricos

_Autoria: João Gabriel, 2025_

| Campo | Descrição |
|---|---|
| **Origem:** | RF30/BRS02 - Previsão inteligente de horários baseada em dados históricos e machine learning |
| **Descrição:** | Como **passageiro que depende de horários precisos**, eu quero **receber previsões inteligentes de horários de chegada baseadas em dados históricos e machine learning**, para que **eu possa evitar esperas longas nos pontos, especialmente em horários noturnos, e ter mais segurança e confiança no transporte público**. |
| **Critérios de Aceitação:** | - O sistema deve analisar dados históricos de pelo menos 30 dias para gerar previsões<br>- A previsão inteligente deve considerar: padrões de trânsito, horários do dia, dias da semana e eventos especiais<br>- O usuário deve poder ativar/desativar a "previsão inteligente" nas configurações<br>- O sistema deve exibir o horário previsto com indicação visual de confiabilidade (ex: "Alta confiança" baseada em 100+ viagens)<br>- O usuário deve poder programar notificações personalizadas (ex: "5 minutos antes da chegada prevista")<br>- O sistema deve atualizar as previsões em tempo real conforme a posição do ônibus muda<br>- Deve ser mostrada a base estatística da previsão (ex: "Baseado em 187 viagens anteriores")<br>- A interface deve diferenciar claramente entre horário oficial e horário previsto inteligente<br>- O sistema deve funcionar mesmo com conexão limitada, usando os últimos dados preditivos calculados<br>- O algoritmo deve aprender continuamente com novos dados de viagens |
| **Prioridade:** | Média |

### US30 - Criar Conta e Fazer Login no Aplicativo

_Autoria: João Gabriel, 2025_

| Campo | Descrição |
|---|---|
| **Origem:** | RF37 - Permitir cadastro, login e autenticação de usuários no sistema |
| **Descrição:** | Como **usuário do aplicativo**, eu quero **criar uma conta e fazer login de forma segura**, para que **eu possa acessar funcionalidades personalizadas como favoritos, histórico de viagens, recargas e avaliações**. |
| **Critérios de Aceitação:** | - O usuário deve poder criar conta com e-mail e senha<br>- Deve ser possível fazer login com e-mail e senha<br>- O sistema deve manter a sessão do usuário ativa entre aberturas do aplicativo<br>- Deve haver opção de "Lembrar meus dados" para login automático<br>- O sistema deve permitir recuperação de senha por e-mail<br>- Os dados de login devem ser armazenados de forma segura<br>- O usuário deve poder fazer logout da conta<br>- O sistema deve validar e-mail durante o cadastro<br>- Deve ser possível acessar algumas funcionalidades básicas sem login (modo visitante) |
| **Prioridade:** | Alta |


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
| 1.2 | 19/10 | Adição de Histórias de Usuário de US13 até US17 | João Gabriel | Cauã Nicolas |
| 1.3 | 21/10 | Adição de Histórias de Usuário de US18 e US19 | Gabriel Maciel | João Gabriel |
| 1.4 | 21/10 | Adição de Histórias de Usuário de US20 e US21 | Cauã Nicolas | Gabriel Maciel |
| 1.5 | 21/10 | Adição de Histórias de Usuário de US29 | João Gabriel | Gabriel Maciel |


---

## Agradecimentos

Agradecemos o suporte da ferramenta de Inteligência Artificial Generativa Google Gemini no desenvolvimento deste trabalho. Em conformidade com o Código de Conduta da Sociedade Brasileira de Computação (SBC), declaramos que a ferramenta foi utilizada como auxílio na revisão gramatical e estilística do texto, na sugestão de estrutura para seções específicas do artigo, bem como na formatação de tabelas e na descrição de figuras. Ressaltamos que os autores assumem total responsabilidade por todo o conteúdo apresentado, incluindo sua originalidade e precisão. A ferramenta não figura como autora desta publicação.