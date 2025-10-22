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

### Épico 1: Rastreamento e Informações em Tempo Real

Tem como objetivo permitir que passageiros acompanhem a localização e status dos ônibus em tempo real, além de fornecer informações precisas e atualizadas sobre horários e pontos de parada, permitindo melhor planejamento e redução do tempo de espera.

| ID | História de Usuário | Prioridade | Rastreabilidade (Origem) | Autoria |
| -- | ------------------- | ---------- | ------------------------ | ------- |
| **US04** | Como **passageiro que precisa escolher entre várias opções de transporte**, eu quero **rastrear múltiplas linhas de ônibus simultaneamente no mapa**, para que **eu possa visualizar e comparar diferentes opções em tempo real e escolher a melhor alternativa para meu deslocamento**. | Alta | **RF35/ENT12** - Permitir rastreamento de múltiplas linhas de ônibus simultaneamente no mapa | Gabriel Maciel |
| **US13** | Como **passageiro do transporte público**, eu quero **visualizar a localização exata dos ônibus em tempo real no mapa**, para que **eu possa ter certeza de que o ônibus está a caminho e estimar com precisão o tempo de espera no ponto**. | Alta | **RF01/ANADOC** - Exibir a localização dos ônibus em tempo real no mapa | João Gabriel |
| **US14** | Como **passageiro aguardando no ponto**, eu quero **consultar o tempo estimado de chegada (TEC) do meu ônibus**, para que **eu possa gerenciar meu tempo de espera com mais segurança e tomar decisões (ex: esperar, chamar um táxi, escolher outra rota)**. | Alta | **RF02/ENT04** - Mostrar o tempo estimado de chegada do ônibus à parada | João Gabriel |
| **US17** | Como **passageiro do transporte público**, eu quero **visualizar os horários previstos de saída e chegada dos ônibus**, para que **eu possa planejar melhor meus deslocamentos e evitar longas esperas nos pontos**. | Alta | **RF05** - Exibir horários de saída e chegada dos transportes públicos | Fernanda Vaz |
| **US06** | Como **passageiro que utiliza transporte público**, eu quero **visualizar em um mapa interativo todos os pontos de ônibus e as linhas que passam por cada um deles**, para que **eu possa identificar o ponto mais próximo e escolher a linha mais conveniente**. | Alta | **RF06** - Exibir pontos de ônibus e linhas em mapa interativo | Fernanda Vaz |
US22|Como **passageiro do transporte público**, eu quero **visualizar a lotação estimada do ônibus (vazio, moderado, lotado) antes que ele chegue ao ponto**, para que **eu possa decidir se embarco neste veículo ou espero o próximo, buscando mais conforto**.|Alta|**RF09** - Indicar lotação do ônibus (vazio, moderado, lotado)|João Ramos
US24|Como **passageiro aguardando no ponto**, eu quero **definir um alerta para ser notificado quando o ônibus de uma linha específica estiver a X minutos da minha parada**, para que **eu possa me preparar para o embarque sem precisar checar o aplicativo constantemente**.|Alta|**RF11** - Enviar notificação quando o ônibus estiver a X minutos da parada|João Ramos
US25|Como **passageiro do transporte público**, eu quero **receber alertas e notificações sobre mudanças inesperadas no serviço, como atrasos significativos, mudanças de rota ou alterações de horário**, para que **eu possa me antecipar a problemas e planejar rotas alternativas**.|Alta|**R12** - Enviar alertas sobre atrasos, mudanças de rota ou alterações nos horários|João Ramos

---

### Épico 2: Filtragem

Tem como objetivo facilitar a localização de linhas, rotas e opções de transporte específicas.

| ID | História de Usuário | Prioridade | Rastreabilidade (Origem) | Autoria |
| -- | ------------------- | ---------- | ------------------------ | ------- |
| **US01** | Como **passageiro do transporte público**, eu quero **filtrar e visualizar ônibus de acordo com a empresa operadora**, para que **eu possa escolher linhas de empresas específicas de minha preferência ou evitar empresas com as quais tive experiências negativas**. | Média | **RF26/RF03 (Análise de Documentos)** - Filtrar ônibus por empresa operadora | Gabriel Maciel |
| **US16** | Como **passageiro que sabe qual linha ou destino deseja**, eu quero **pesquisar diretamente por linhas, números de ônibus ou nomes de destinos**, para que **eu possa acessar rapidamente as informações específicas que preciso, sem ter que navegar pelo mapa**. | Média | **RF04/ANADOC** - Permitir pesquisa por linhas e rotas de ônibus | João Gabriel |
US27|Como **passageiro em um ponto de ônibus**, eu quero **selecionar uma parada (no mapa ou por pesquisa) e ver uma lista de todas as linhas que passam por ela**, para que **eu possa descobrir rapidamente quais são minhas opções de transporte naquela localização**.|Alta|**RF18 (BRS)** - Listar linhas que passam em uma parada específica|João Ramos

---

### Épico 3: Acessibilidade

Tem como objetivo garantir que o sistema atenda às necessidades de todos os usuários, especialmente aqueles com necessidades especiais, oferecendo alternativas de acesso, múltiplos idiomas e interfaces acessíveis para facilitar a interação.

| ID | História de Usuário | Prioridade | Rastreabilidade (Origem) | Autoria |
| -- | ------------------- | ---------- | ------------------------ | ------- |
| **US02** | Como **passageiro aguardando no ponto de ônibus**, eu quero **acessar uma versão web leve do aplicativo através de QR Code**, para que **eu possa consultar informações sobre linhas e horários rapidamente sem precisar instalar o aplicativo completo no meu dispositivo**. | Média | **RF19/BRS17** - Disponibilizar versão web leve para acesso rápido em pontos de ônibus (via QR Code) | Gabriel Maciel |
| **US18** | Como **usuário do transporte público**, eu quero **utilizar assistentes virtuais como Alexa ou Google Assistant para acessar informações de ônibus**, para que **eu possa consultar horários, localização de ônibus e planejar viagens sem precisar abrir o aplicativo manualmente**. | Baixa | **RF34/BRS16** - Integração com assistentes virtuais (Alexa, Google Assistant) | Gabriel Maciel |
| **US19** | Como **usuário que não fala português ou turista visitando o Distrito Federal**, eu quero **utilizar o aplicativo em diferentes idiomas, especialmente em português e inglês**, para que **eu possa compreender facilmente todas as informações sobre linhas, horários e navegação no aplicativo**. | Média | **RF36/ENT22** - Oferecer suporte multilíngue (português e inglês, no mínimo) | Gabriel Maciel |
| **US20** | Como **usuário que utiliza frequentemente determinadas linhas de ônibus**, eu quero **poder favoritar linhas ou paradas específicas**, para que eu **consiga acessá-las rapidamente sem precisar pesquisar toda vez**. | Média | **RF24** - Permitir favoritar linhas ou paradas para acesso rápido | Cauã Nicolas |
| **US21** | Como **usuário que mora em áreas afastadas do Distrito Federal**, eu quero **ter acesso às informações de linhas e horários de ônibus da minha região**, para que eu **possa planejar minhas viagens com a mesma praticidade que os usuários das regiões centrais**. | Média | **RF25** - Ampliar a cobertura e exibir informações também em regiões afastadas do Distrito Federal | Cauã Nicolas |
US26|Como **passageiro com conexão de internet limitada ou instável**, eu quero **acessar os horários programados das linhas e minhas rotas salvas mesmo estando offline**, para que **eu possa planejar meus deslocamentos essenciais sem depender de uma conexão de dados ativa**.|Média|**RFN-11 (RNI05/ENT18/BRS06)** - Funcionamento offline para consulta a rotas salvas e horários|João Ramos
| **US34** | Como **passageiro em deslocamento**, eu quero **utilizar comandos de voz para acessar informações do aplicativo**, para que **eu possa interagir com o sistema de forma segura e prática sem precisar tocar no celular**. | Média | **RF33** - Suporte a comandos de voz para facilitar interação durante deslocamentos | Daniel Nunes Duarte |


---

### Épico 4: Avaliar e Reportar

Tem como objetivo permitir que usuários avaliem o serviço de transporte público e reportem problemas relacionados ao transporte (como falhas no ônibus, comportamento inadequado do motorista ou cobranças incorretas) para contribuir com a melhoria contínua do sistema, além de ajudar outras pessoas a tomar decisões informadas sobre qual ônibus utilizar.

| ID | História de Usuário | Prioridade | Rastreabilidade (Origem) | Autoria |
| -- | ------------------- | ---------- | ------------------------ | ------- |
| **US03** | Como **passageiro regular do transporte público**, eu quero **avaliar a qualidade do serviço de cada linha de ônibus que utilizo**, para que **eu possa compartilhar minha experiência e contribuir para a melhoria do serviço, além de ajudar outros passageiros a escolherem as melhores opções**. | Baixa | **RF28/RNI04** - Permitir avaliação da qualidade do serviço de cada linha | Gabriel Maciel |
| **US12** | Como **usuário do transporte público**, eu quero **reportar problemas ocorridos durante uma viagem (como comportamento do motorista, falhas no ônibus ou cobrança incorreta)**, para que **a empresa responsável possa investigar e melhorar o serviço**. | Baixa | **RF16** - Permitir reportar problemas (motorista, ônibus, cobrança) com dados do veículo e horário | Cauã Nicolas |
US23|Como **passageiro que está dentro do ônibus**, eu quero **reportar o nível de lotação atual do veículo (vazio, moderado, lotado)**, para que **eu possa contribuir com o sistema colaborativo e ajudar outros passageiros a tomar decisões**.|Média|**R10** - Permitir que usuários reportem a lotação do ônibus (sistema colaborativo)|João Ramos
---

### Épico 5: Integração e Recargas

Tem como objetivo integrar o cartão de transporte ao aplicativo, permitindo que o usuário visualize o saldo, realize recargas de forma unificada e tenha acesso às funcionalidades de gerenciamento do cartão, sem necessidade de acessar sistemas externos.

| ID | História de Usuário | Prioridade | Rastreabilidade (Origem) | Autoria |
| -- | ------------------- | ---------- | ------------------------ | ------- |
| **US09** | Como **usuário do transporte público**, eu quero **realizar recargas do meu cartão de transporte diretamente pelo aplicativo**, para que **eu possa evitar filas e ter mais praticidade na recarga**. | Média | **RF13** - Oferecer recarga de cartão de transporte (ex.: integração com BRB Mobilidade) | Cauã Nicolas |
| **US10** | Como **usuário do transporte público**, eu quero **visualizar o saldo e realizar recargas do meu cartão de transporte no aplicativo**, para que **eu possa acompanhar meu consumo e manter o cartão sempre carregado**. | Média | **RF14** - Permitir integração com o cartão de transporte, incluindo saldo e recarga | Cauã Nicolas |

---

### Épico 6: Histórico 

Tem como objetivo permitir que o usuário visualize e acompanhe o histórico de viagens realizadas, oferecendo mais controle sobre deslocamentos, horários e gastos com transporte público.

| ID | História de Usuário | Prioridade | Rastreabilidade (Origem) | Autoria |
| -- | ------------------- | ---------- | ------------------------ | ------- |
| **US11** | Como **passageiro**, eu quero **visualizar meu histórico de viagens realizadas**, para que **eu possa acompanhar meus trajetos, horários e valores gastos**. | Média | **RF15** - Manter histórico de viagens do usuário | Cauã Nicolas |

---

### Épico 7: Planejamento de Viagens

Tem como objetivo permitir que o passageiro planeje viagens integradas utilizando diferentes modais de transporte, com informações sobre acessibilidade e opções de rotas, garantindo inclusão e autonomia para todos os usuários.

| ID | História de Usuário | Prioridade | Rastreabilidade (Origem) | Autoria |
| -- | ------------------- | ---------- | ------------------------ | ------- |
| **US07** | Como **passageiro que deseja planejar sua rota**, eu quero **visualizar e integrar informações de diferentes modais de transporte (metrô, ônibus de outras empresas, etc.) no planejamento de rotas**, para que **eu possa escolher a melhor combinação de transportes para chegar ao meu destino**. | Média | **RF07** - Integrar informações de outros modais de transporte | Fernanda Vaz |
| **US08** | Como **passageiro com mobilidade reduzida**, eu quero **visualizar se o ônibus é acessível para cadeirantes e outras necessidades especiais**, para que **eu possa planejar meu deslocamento com segurança e conforto**. | Alta | **RF08** - Exibir informações de acessibilidade dos veículos | Fernanda Vaz |
| **US28** | Como **passageiro planejando uma viagem ou já em deslocamento**, eu quero **ser informado sobre incidentes de trânsito (acidentes, congestionamentos, obras) que afetam as rotas de ônibus**, para que **eu possa entender a causa de atrasos e receber sugestões de rotas alternativas**. | Média | **RF21 (BRS12)** - Mostrar alertas de trânsito, acidentes e rotas alternativas | João Ramos |
| **US15** | Como **passageiro que precisa se deslocar pela cidade**, eu quero **planejar uma viagem informando meu ponto de origem e destino para receber rotas sugeridas de ônibus**, para que **eu possa encontrar a melhor opção de itinerário, mesmo em rotas que não conheço**. | Alta | **RF03/ANADOC** - Permitir planejamento de viagem (origem → destino) com rotas sugeridas | João Gabriel |
| **US29** | Como **passageiro que depende de horários precisos**, eu quero **receber previsões inteligentes de horários de chegada baseadas em dados históricos e machine learning**, para que **eu possa evitar esperas longas nos pontos, especialmente em horários noturnos, e ter mais segurança e confiança no transporte público**. | Média | **RF30/BRS02** - Previsão inteligente de horários baseada em dados históricos e machine learning | João Gabriel |
| **US31** | Como **passageiro que utiliza o transporte público**, eu quero **visualizar o preço da passagem de cada linha ou trajeto**, para que **eu possa planejar meus gastos e comparar opções de transporte antes de embarcar**. | Média | **RF17** - Exibir preço da passagem por linha ou trajeto | Daniel Nunes Duarte |
| **US35** | Como **usuário do transporte público**, eu quero **visualizar todos os veículos que estão em operação no momento**, para que **eu possa saber quais linhas estão ativas e planejar meus deslocamentos com base na disponibilidade real do serviço**. | Alta | **RF27** - Visualizar quais veículos estão em operação no momento | Daniel Nunes Duarte |

---

### Épico 8: Gestão de Usuário e Conta

Tem como objetivo gerenciar a identidade, autenticação e preferências dos usuários no sistema, proporcionando experiência personalizada e segura.

| ID | História de Usuário | Prioridade | Rastreabilidade (Origem) | Autoria |
|---|---|---|---|---|
| **US30** | Como **usuário do aplicativo**, eu quero **criar uma conta e fazer login de forma segura**, para que **eu possa acessar funcionalidades personalizadas como favoritos, histórico de viagens, recargas e avaliações**. | Alta | **RF37** - Permitir cadastro, login e autenticação de usuários no sistema | João Gabriel |

### Épico 09: Sustentabilidade e Impacto Ambiental

Tem como objetivo promover a conscientização ambiental dos usuários do aplicativo **DF no Ponto**, incentivando o uso contínuo do transporte público por meio da exibição de relatórios sobre a redução das emissões de CO₂.  
Essas funcionalidades visam destacar a contribuição ecológica individual e coletiva dos passageiros, fortalecendo o engajamento com práticas sustentáveis e reforçando o compromisso do sistema com a mobilidade urbana verde.

| ID | História de Usuário | Prioridade | Rastreabilidade (Origem) | Autoria |
| -- | ------------------- | ---------- | ------------------------ | ------- |
| **US09** | Como **usuário consciente sobre sustentabilidade**, eu quero **visualizar relatórios de impacto ambiental que indiquem o quanto de CO₂ deixei de emitir ao utilizar o transporte público**, para que **eu possa acompanhar minha contribuição para a preservação ambiental e ser incentivado a continuar utilizando o transporte coletivo**. | Média | **RF32** – Exibir relatórios de impacto ambiental (CO₂ economizado) | Fernanda Vaz |
| **US10** | Como **usuário consciente e engajado com sustentabilidade**, eu quero **visualizar relatórios de impacto ambiental que mostrem a quantidade de CO₂ que deixei de emitir ao utilizar o transporte público**, para que **eu possa compreender minha contribuição positiva para o meio ambiente e ser incentivado a continuar utilizando o aplicativo de forma sustentável**. | Média | **RF32** – Exibir relatórios de impacto ambiental (CO₂ economizado) – *Elicitação de Requisitos: Brainstorm (BRS11)* | Fernanda Vaz |

---

### Épico 10: Segurança

Tem como objetivo garantir a integridade física e a sensação de segurança dos passageiros durante suas viagens, fornecendo mecanismos ágeis e discretos para alertar motoristas, operadores e autoridades em situações de risco ou emergência.

| ID | História de Usuário | Prioridade | Rastreabilidade (Origem) | Autoria |
| -- | ------------------- | ---------- | ------------------------ | ------- |
| **US32** | Como **passageiro em situação de emergência dentro do ônibus**, eu quero **acessar rapidamente um botão de pânico no aplicativo**, para que **eu possa alertar o motorista e/ou as autoridades competentes de forma discreta e segura**. | Alta | **RF20** - Botão de pânico/emergência para alertar motorista e/ou autoridades | Daniel Nunes Duarte |
| **US33** | Como **passageiro em deslocamento**, eu quero **compartilhar meu trajeto em tempo real com familiares ou amigos**, para que **eles possam acompanhar meu percurso e saber quando cheguei em segurança ao destino**. | Alta | **RF22** - Permitir compartilhar trajeto em tempo real com outros usuários | Daniel Nunes Duarte |

---

### Épico 11: Gamificação e Engajamento

Visa incentivar o uso do transporte público por meio de mecanismos de gamificação, recompensas e reconhecimento de comportamento positivo, tornando a experiência do usuário mais envolvente e estimulando a fidelização ao sistema.

| ID | História de Usuário | Prioridade | Rastreabilidade (Origem) | Autoria |
| -- | ------------------- | ---------- | ------------------------ | ------- |
| **US36** | Como **usuário frequente do transporte público**, eu quero **participar de um sistema de pontuação e recompensas baseado nas minhas viagens**, para que **eu me sinta motivado a utilizar mais o transporte coletivo e ganhar benefícios**. | Média | **RF29** - Sistema de gamificação para incentivar uso do transporte público | Daniel Nunes Duarte |

## Validação(Fernanda Vaz)
<iframe width="560" height="315"
  src="https://www.youtube.com/embed/_up-xi0eqpo"
  title="YouTube video player" frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
  allowfullscreen>
</iframe>

## Validação(João Ramos)
<iframe width="560" height="315"
  src="https://www.youtube.com/watch?v=OPVuApWBT6k"
  title="YouTube video player" frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
  allowfullscreen>
</iframe>

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
| 1.2 | 20/10 | Adição de Épicos  | Cauã Nicolas | Gabriel Maciel |
| 1.2.1 | 20/10 | Refatora Épico 4 e Épico 5 | Gabriel Maciel | João Gabriel |
| 1.2.2 | 20/10 | Adição Épicos 1, 2 e mudança no 7 | João Gabriel | Cauã Nicolas|
| 1.3 | 21/10 | Adição de US18 e US19 ao Épico 3 | Gabriel Maciel | Cauã Nicolas |
| 1.4 | 21/10 | Junção dos Épicos 1 e 7 em um único Épico 1 (Rastreamento e Informações em Tempo Real) | Gabriel Maciel | Cauã Nicolas |
| 1.5 | 21/10 | Adição de US20 e US21 ao Épico 3 | Cauã Nicolas | Gabriel Maciel |
| 1.6 | 21/10 | Adição de US29 e US15 ao Épico 7 | João Gabriel | João Lucas |
| 1.7 | 21/10 | Adição de US31 a US36. Criação dos Épicos 10 e 11. Oganização dos US31 ao US36  | Daniel Nunes Duarte | 
| 1.7 | 21/10 | Adição de itens aos Épicos 2, 3 e 7 | João Lucas | João Gabriel |
-------- |

## Agradecimentos

Agradecemos o suporte da ferramenta de Inteligência Artificial Generativa Google Gemini no desenvolvimento deste trabalho. Em conformidade com o Código de Conduta da Sociedade Brasileira de Computação (SBC), declaramos que a ferramenta foi utilizada como auxílio na revisão gramatical e estilística do texto, na sugestão de estrutura para seções específicas do artigo, bem como na formatação de tabelas e na descrição de figuras. Ressaltamos que os autores assumem total responsabilidade por todo o conteúdo apresentado, incluindo sua originalidade e precisão. A ferramenta não figura como autora desta publicação.
