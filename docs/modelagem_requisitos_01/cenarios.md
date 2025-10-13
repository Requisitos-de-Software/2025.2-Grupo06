## Introdução

> Um cenário é basicamente uma história sobre pessoas realizando uma atividade [(Rosson e Carroll, 2002)](#ref-rosson-carroll). É uma narrativa, textual ou pictórica, concreta, rica em detalhes contextuais, de uma situação de uso da aplicação, envolvendo usuários, processos e dados reais ou potenciais.
> Os cenários podem ser utilizados em diversas etapas do processo, com diferentes objetivos: para descrever uma história num domínio de atividade, visando capturar requisitos e auxiliar no entendimento da atividade, levantar questões sobre a introdução de tecnologia, explorar diferentes soluções de design e avaliar se um produto satisfaz a necessidade dos seus usuários [(Rosson e Carroll, 2002)](#ref-rosson-carroll).
> *Fonte: Adapatado de [BARBOSA; SILVA, 2010](#ref-barbosa-silva)*

---
## Elementos característicos de um cenário (Print)
<a href="https://ibb.co/ZzZhPxzK"><img src="https://i.ibb.co/TMCHStMR/image.png" alt="image" border="0"></a>

## Cenário 1 – Notificações de Chegada (Requisito não implementado)
<span style="color:blue;">Autoria: Fernanda Vaz, 2025.</span>

| **Elemento** | **Descrição** |
| :-----------: | :------------ |
| **Ambiente ou contexto** | Juliana está voltando da faculdade e precisa pegar o ônibus da linha A206 para ir até sua casa. Ela está em um ponto pouco movimentado e perigoso, e quer evitar ficar esperando por muito tempo no ponto de ônibus. O aplicativo de acompanhamento de ônibus está configurado para enviar notificações quando o veículo estiver próximo, permitindo que ela vá para a parada apenas quando o ônibus estiver chegando. |
| **Atores** | Juliana, 23 anos, estudante de Ciência da Computação. Costuma utilizar o transporte público diariamente e faz uso de recursos que otimizam o tempo e aumentam a segurança ao se deslocar. |
| **Objetivos** | Ser avisada com antecedência sobre a aproximação do ônibus, para se preparar para embarcar com segurança e evitar longas esperas no ponto. |
| **Planejamento** | Juliana abre o aplicativo, seleciona a linha A206 e ativa a opção “Notificar quando o ônibus estiver próximo”. Depois, guarda o celular na bolsa. |
| **Ações** | O sistema identifica a localização do ônibus em tempo real e calcula o tempo estimado de chegada ao ponto selecionado. Quando o veículo se aproxima do raio de 500 metros, o aplicativo envia uma notificação sonora e visual para Juliana. |
| **Eventos** | O GPS do ônibus atualiza a posição no sistema central. O servidor processa os dados e dispara a notificação para o celular de Juliana. O aviso aparece na tela com a mensagem: “Atenção! Seu ônibus da linha A206 está a 3 minutos de distância”. |
| **Avaliação** | Juliana interpreta a mensagem, confirma que o ônibus está próximo e se dirige ao ponto. Ela reconhece que o recurso de notificação é útil e melhora sua experiência diária com o transporte. |

---

## Cenário 2 – Avaliar Linhas  (Requisito não implementado)
<span style="color:blue;">Autoria: Fernanda Vaz, 2025.</span>

| **Elemento** | **Descrição** |
| :-----------: | :------------ |
| **Ambiente ou contexto** | Após um longo dia de trabalho, Diego Almeida Fonseca, 36 anos, analista administrativo, está voltando para casa usando a linha A205. Nos últimos dias, ele tem enfrentado atrasos e ônibus superlotados, o que tem afetado sua rotina e seu tempo com a família. O aplicativo que ele utiliza para acompanhar o transporte público oferece a opção de avaliar as linhas. |
| **Atores** | Diego é experiente no uso de transporte público e possui conhecimento intermediário em tecnologia. Ele usa o aplicativo diariamente para planejar seus deslocamentos e valoriza recursos que possibilitem melhorar a qualidade do serviço por meio de feedbacks diretos. |
| **Objetivos** | Registrar sua opinião sobre a linha A205, destacando os atrasos frequentes e a superlotação, com o intuito de ajudar outros passageiros e contribuir para que a empresa de transporte identifique e resolva os problemas operacionais. |
| **Planejamento** | Ao chegar em casa, Diego decide acessar o aplicativo e abrir a seção “Avaliar linha”. Ele reflete sobre os principais pontos negativos da viagem e pensa em como expressar seu feedback de maneira clara e objetiva para que seja útil aos responsáveis pela linha. |
| **Ações** | Diego seleciona a linha A205 em seu histórico, atribui uma nota de 2 estrelas e escreve o comentário: “Ônibus atrasado e veio extremamente lotado”. Em seguida, envia a avaliação no aplicativo. |
| **Eventos** | O sistema registra a avaliação de Diego no banco de dados e atualiza automaticamente a média de pontuação da linha A205. Outros passageiros passam a visualizar a nova nota e o comentário. A empresa de transporte recebe o feedback para análise. |
| **Avaliação** | Diego sente que contribuiu para a melhoria do serviço e percebe que o aplicativo valoriza a participação dos passageiros. Ele fica satisfeito por poder ajudar outras pessoas que enfrentam os mesmos problemas e melhora sua experiência na plataforma. |

---

## Cenário 3 – Rastreamento de múltiplas linhas (Requisito não implementado)
<span style="color:blue;">Autoria: Gabriel Maciel, 2025.</span>

| **Elemento** | **Descrição** |
| :-----------: | :------------ |
| **Ambiente ou contexto** | Diego está retornando do Plano Piloto para o Gama em um ônibus expresso, mas precisa descer no Setor Central do Gama por um imprevisto. Desse ponto, várias linhas podem levá-lo ao Setor Leste. Ele usa o aplicativo para rastrear simultaneamente três linhas diferentes e escolher a melhor opção. |
| **Atores** | Diego Almeida Fonseca, 36 anos, analista administrativo. Usuário experiente de transporte público, valoriza eficiência. Mora no Gama e trabalha no Plano Piloto. |
| **Objetivos** | Visualizar simultaneamente no mapa a localização em tempo real de múltiplas linhas (Linha A, B e C) para escolher a melhor opção de transferência e minimizar o tempo de espera. |
| **Planejamento** | Diego abre o app DF no Ponto, ativa "Rastrear múltiplas linhas" e seleciona três linhas que atendem o Setor Leste. Mantém o mapa aberto para acompanhar o movimento dos ônibus em tempo real. |
| **Ações** | Diego visualiza um mapa interativo com a posição de todos os ônibus das três linhas em ícones coloridos (vermelho, azul e verde). O mapa mostra sua localização atual e o ponto de destino. O sistema atualiza automaticamente as posições a cada poucos segundos. |
| **Eventos** | O GPS dos ônibus transmite posições em tempo real ao sistema. Diego observa no mapa que a Linha C está a 2 km de distância. O app exibe: "Linha A: 8 min", "Linha B: 12 min", "Linha C: 5 min". Diego decide aguardar a Linha C. |
| **Avaliação** | Diego visualiza claramente todos os ônibus e faz uma escolha informada. Pega a Linha C com apenas 3 minutos de espera. Reconhece que a funcionalidade foi essencial para otimizar seu deslocamento, satisfeito com a praticidade e confiabilidade do recurso. |

---
### Validação com usuário real dos Cenários 1 e 2 (Fernanda Vaz)

<iframe width="560" height="315"
  src="https://www.youtube.com/embed/B57AOMl5WTk?start=33"
  title="YouTube video player"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
  referrerpolicy="strict-origin-when-cross-origin"
  allowfullscreen>
</iframe>

## Cenário 4 - Integração com BRB Mobilidade (Requisito não implementado)
<span style="color:blue;">Autoria: Gabriel Maciel, 2025.</span>

| **Elemento** | **Descrição** |
| :-----------: | :------------ |
| **Ambiente ou contexto** | Diego está no trabalho durante o horário de almoço e percebe que o saldo do seu cartão BRB Mobilidade está acabando. Ele precisa recarregar antes de pegar o ônibus no final do expediente, mas não tem tempo para ir até um ponto de recarga físico. Diego lembra que o aplicativo DF no Ponto possui integração com o BRB Mobilidade e decide usar o app para verificar seu saldo e fazer a recarga diretamente pelo celular. |
| **Atores** | Diego Almeida Fonseca, 36 anos, analista administrativo. Usa transporte público diariamente, possui cartão BRB Mobilidade e valoriza soluções práticas que economizem tempo. |
| **Objetivos** | Visualizar o saldo atual do cartão BRB Mobilidade e recarregar o cartão usando cartão de crédito ou Pix, sem precisar se deslocar até um ponto de recarga físico. |
| **Planejamento** | Diego abre o app DF no Ponto, acessa a seção "Meu Cartão" e vincula seu cartão BRB Mobilidade informando o número do cartão. Após vincular, verifica o saldo e seleciona a opção de recarga. |
| **Ações** | Diego visualiza seu saldo atual (R$ 8,50) na tela. Seleciona "Recarregar" e escolhe o valor (R$ 50,00). O app apresenta opções de pagamento: cartão de crédito, débito, Pix ou boleto. Diego escolhe Pix, gera o QR Code e efetua o pagamento pelo app do banco. |
| **Eventos** | O sistema do DF no Ponto comunica-se com a API do BRB Mobilidade para validar o cartão e exibir o saldo. Após o pagamento, o sistema registra a transação e envia os dados para o BRB Mobilidade. Em poucos segundos, o app confirma: "Recarga de R$ 50,00 realizada com sucesso. Novo saldo: R$ 58,50". |
| **Avaliação** | Diego conclui a recarga em menos de 2 minutos sem sair do trabalho. Fica satisfeito com a praticidade de não precisar procurar pontos de recarga e com a rapidez da confirmação. Reconhece que a integração torna o uso do transporte público mais conveniente e prático. |

---

### Validação com usuário real dos Cenários 3 e 4 (Gabriel Maciel)

O vídeo 1 apresenta, entre o trecho 0:19 e 3:17, a validação dos cenários 3 e 4 com um usuário real, mostrando brevemente o uso das funcionalidades de rastreamento de múltiplas linhas e integração com o BRB Mobilidade no aplicativo.

<iframe width="560" height="315" src="https://www.youtube.com/embed/Wl211vLAZI0?si=gvEFU5-uOmm7YEkF&amp;start=19" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

*Vídeo 1: Validação dos Cenários 3 e 4*


## Cenário 5 - Modo Off-line (Requisito não implementado)
<span style="color:blue;">Autoria: João Lucas, 2025.</span>

| **Elemento** | **Descrição** |
| :-----------: | :------------ |
| **Ambiente ou contexto** | Juliana está em casa planejando sua ida à universidade no dia seguinte. Ela sabe que em determinados trechos do trajeto entre sua casa e a FGA a conexão de internet móvel é instável. Para evitar ficar sem informações durante o deslocamento, ela decide baixar previamente os dados das linhas que costuma usar e os horários das paradas próximas. |
| **Atores** | Juliana Ferreira Monteiro, 23 anos, estudante de Ciência da Computação. Usa transporte público diariamente e enfrenta problemas com sinal de internet em algumas regiões. |
| **Objetivos** | Baixar previamente informações sobre linhas, trajetos, paradas e horários para consultar offline quando estiver sem conexão de internet. |
| **Planejamento** | Conectada ao Wi-Fi de casa, Juliana abre o app DF no Ponto, acessa "Configurações" e ativa o "Modo Offline". Seleciona as linhas que usa regularmente e as paradas próximas de casa e da universidade para download. |
| **Ações** | Juliana seleciona para download: trajetos das linhas principais, horários das paradas "Parada X - Residencial" e "Parada Y - FGA", e mapas das rotas. O app baixa os dados (cerca de 15 MB) e confirma: "Dados salvos para consulta offline". |
| **Eventos** | No dia seguinte, no ônibus, Juliana perde o sinal de internet. Ela abre o app, que detecta automaticamente a ausência de conexão e exibe um ícone indicando "Modo Offline ativo". Juliana consulta o trajeto da próxima linha, os horários da parada de destino e quais ônibus passam por lá, tudo sem internet. |
| **Avaliação** | Juliana consegue planejar sua integração mesmo sem internet. Fica satisfeita por poder consultar horários e trajetos offline, evitando ansiedade e incerteza durante o deslocamento. Reconhece que o modo offline é essencial para regiões com sinal instável. |

---

## Cenário 6 - Reportar lotação do ônibus (Requisito não implementado)
<span style="color:blue;">Autoria: João Lucas, 2025.</span>

| **Elemento** | **Descrição** |
| :-----------: | :------------ |
| **Ambiente ou contexto** | Juliana está aguardando o ônibus no ponto próximo à universidade no horário de pico da tarde. Ela precisa decidir se embarca no próximo ônibus que chegar ou espera pelo seguinte. Juliana abre o app DF no Ponto para verificar se outros usuários reportaram a lotação dos ônibus que estão chegando. |
| **Atores** | Juliana Ferreira Monteiro, 23 anos, estudante. Prefere evitar ônibus muito lotados quando possível e valoriza informações colaborativas de outros usuários. |
| **Objetivos** | Visualizar reportes de lotação feitos por outros usuários para decidir qual ônibus pegar, e reportar a lotação do ônibus em que está para ajudar outros passageiros. |
| **Planejamento** | Juliana acessa a lista de ônibus se aproximando do ponto. O app exibe ícones de lotação ao lado de cada ônibus: ícone verde (vazio), amarelo (médio) ou vermelho (lotado), baseados em reportes recentes de usuários. |
| **Ações** | Juliana vê que o primeiro ônibus está marcado com ícone vermelho (9 usuários reportaram "lotado" há 3 minutos). Decide esperar. O segundo ônibus mostra ícone amarelo (5 reportes de "médio"). Juliana embarca e, uma vez dentro, acessa o app e reporta a lotação como "médio" para ajudar outros usuários. |
| **Eventos** | O sistema recebe o reporte de Juliana e atualiza o status do ônibus em tempo real. Outros usuários aguardando em paradas à frente visualizam a informação atualizada. O app exibe: "Lotação reportada: Médio (6 usuários confirmaram nos últimos 5 minutos)". |
| **Avaliação** | Juliana consegue evitar um ônibus muito lotado usando informações colaborativas. Sente-se parte de uma comunidade que se ajuda. Reconhece que o sistema de reporte colaborativo melhora a experiência de todos e permite decisões mais informadas sobre quando e qual ônibus pegar. |

---

### Validação com usuário real dos Cenários 5 e 6 (João Ramos)

O vídeo 2 apresenta, entre o trecho 0:27 e 3:42, a validação dos cenários 5 e 6 com um usuário real, demonstrando o funcionamento do modo offline para consulta de horários e trajetos sem internet, além do sistema colaborativo de reporte de lotação dos ônibus no aplicativo.

<iframe width="560" height="315" src="https://www.youtube.com/embed/rJsODyJZQvk?si=FPa0k0q3IlDfcmQ1&amp;start=27" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

*Vídeo 2: Validação dos Cenários 5 e 6*

## Cenário 7 - Histórico de viagens (Requisito não implementado)
<span style="color:blue;">Autoria: Cauã Nicolas, 2025.</span>

| **Elemento** | **Descrição** |
| :-----------: | :------------ |
| **Ambiente ou contexto** | Isabela está visitando Brasília a trabalho por uma semana. Como autônoma, ela precisa contabilizar suas despesas com transporte para incluir na nota fiscal do projeto. Durante a semana, ela usou várias linhas de ônibus para se deslocar entre o hotel, reuniões com clientes e visitas a obras. No último dia, antes de voltar para casa, ela precisa verificar todas as viagens que fez e seus respectivos custos. |
| **Atores** | Isabela Freitas Corrêa, 30 anos, arquiteta autônoma. Usa transporte público ocasionalmente em viagens e precisa controlar gastos para prestação de contas. |
| **Objetivos** | Acessar o histórico completo de viagens realizadas durante a semana, visualizando linhas utilizadas, horários dos deslocamentos e valores pagos em cada viagem para fazer a prestação de contas. |
| **Planejamento** | Isabela abre o app DF no Ponto, acessa seu perfil e seleciona "Histórico de Viagens". Define o filtro para "Últimos 7 dias" para visualizar todas as viagens da semana. |
| **Ações** | O app exibe uma lista organizada por data mostrando: Segunda - Linha A (08:30, R$ 5,50), Linha B (18:15, R$ 5,50); Terça - Linha C (09:00, R$ 5,50), Linha A (19:00, R$ 5,50); e assim sucessivamente. Isabela exporta o relatório em PDF com o total: 12 viagens, R$ 66,00. |
| **Eventos** | O sistema recupera do banco de dados todos os registros de viagens vinculados ao cartão ou app de Isabela. Organiza cronologicamente com detalhes: data, linha, horário de embarque e valor pago. Gera um resumo total e permite exportação em PDF para comprovação de despesas. |
| **Avaliação** | Isabela consegue rapidamente compilar todas suas despesas com transporte. Fica satisfeita com a praticidade de ter tudo registrado automaticamente e a facilidade de exportar para prestação de contas. Reconhece que o histórico é essencial para quem usa o transporte ocasionalmente e precisa de controle financeiro. |

---

## Cenário 8 - Ampliação da cobertura de informações de transporte do entorno do DF (Requisito não implementado)
<span style="color:blue;">Autoria: Cauã Nicolas, 2025.</span>

| **Elemento** | **Descrição** |
| :-----------: | :------------ |
| **Ambiente ou contexto** | Maria está planejando visitar uma amiga que mora em Luziânia (GO), cidade do entorno do DF. Ela precisa saber quais linhas intermunicipais saem da Rodoviária do Plano Piloto com destino a Luziânia, os horários disponíveis e o tempo de viagem. Maria abre o aplicativo DF no Ponto esperando encontrar essas informações, já que costuma usar o app para suas viagens dentro do DF. |
| **Atores** | Maria Moura Bastos, 65 anos, aposentada. Usa transporte público regularmente no DF e ocasionalmente precisa viajar para cidades do entorno para visitar familiares e amigos. |
| **Objetivos** | Consultar linhas intermunicipais que atendem Luziânia, visualizar horários de saída da Rodoviária, tempo estimado de viagem e pontos de parada na cidade de destino. |
| **Planejamento** | Maria abre o app DF no Ponto, acessa a busca e digita "Luziânia". O sistema reconhece que é uma cidade do entorno e exibe as linhas intermunicipais disponíveis. Ela seleciona a rota "Rodoviária do Plano Piloto → Luziânia Centro". |
| **Ações** | O app exibe as linhas intermunicipais (ex: "Linha A - Brasília/Luziânia"), com horários de saída (06:00, 08:00, 10:00, 12:00...), tempo de viagem (aproximadamente 1h15min) e principais pontos de parada em Luziânia. Maria seleciona o horário das 10:00 e salva como favorito. |
| **Eventos** | O sistema integra dados de empresas de transporte intermunicipal do entorno. Exibe informações atualizadas sobre linhas, horários e itinerários. Quando disponível, mostra também a localização em tempo real dos ônibus intermunicipais. Maria recebe uma notificação: "Linha salva com sucesso. Horário selecionado: 10:00". |
| **Avaliação** | Maria consegue planejar sua viagem a Luziânia sem precisar usar outro aplicativo ou ir até a rodoviária presencialmente para consultar horários. Fica satisfeita com a ampliação da cobertura para o entorno e reconhece que isso torna o app mais completo e útil para quem precisa se deslocar entre o DF e cidades vizinhas. |

---



### Validação com usuário real dos Cenários 7 e 8 (Cauã Nicolas)

O vídeo 3 apresenta, entre o trecho 0:33 e 3:07, a validação dos cenários 7 e 8 com um usuário real, mostrando o uso do histórico de viagens para controle de despesas e a consulta de informações sobre linhas intermunicipais do entorno do DF no aplicativo.

<iframe width="560" height="315" src="https://www.youtube.com/embed/QZcf-jDlhao?si=7Dk0SO2uSn13nDiy&amp;start=33" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

*Vídeo 3: Validação dos Cenários 7 e 8*

---
## Cenário 9 – Planejamento de Viagens (Requisito não implementado)

**Autoria: João Gabriel, 2025.**

| Elemento | Descrição |
|----------|-----------|
| **Ambiente ou contexto** | Matheus está se preparando para uma semana de aulas e compromissos fixos. Ele utiliza diferentes meios de transporte ao longo do dia, combinando carro, ônibus e metrô para ir e voltar da faculdade. Nos últimos dias, ele tem sentido dificuldade em organizar os horários de cada trajeto, o que acaba resultando em atrasos ou esperas longas entre um transporte e outro. O aplicativo **DF no Ponto** passa a oferecer uma funcionalidade de **planejamento de viagens**, permitindo que Matheus monte um roteiro diário, salvando rotas com horários e modais utilizados. |
| **Atores** | Matheus, 21 anos, estudante universitário. Utiliza transporte público e carro diariamente para ir à faculdade e outros compromissos. Valoriza recursos que otimizam tempo e facilitam a organização de sua rotina. Tem familiaridade com tecnologia e costuma planejar seu dia com antecedência. |
| **Objetivos** | Criar um plano de deslocamento completo, reunindo diferentes meios de transporte, horários e conexões em uma única tela. Ter mais controle sobre sua rotina e reduzir atrasos e esperas desnecessárias. |
| **Planejamento** | Matheus abre o aplicativo DF no Ponto, acessa a aba "Planejamento de Viagem" e cria um novo roteiro para a semana. Ele adiciona os horários de saída de casa, seleciona a linha de ônibus, a conexão com o metrô e o trecho final de ônibus até o destino. Em seguida, salva a rota para consulta rápida nos próximos dias. |
| **Ações** | O sistema permite que João insira paradas, linhas e horários estimados, sugerindo conexões ideais com base nas informações oficiais de horários e no histórico de deslocamentos. João confirma o trajeto, adiciona alertas personalizados para cada etapa e ativa notificações para ser avisado com antecedência sobre as saídas. |
| **Eventos** | O sistema registra a rota criada e gera lembretes automáticos próximos dos horários definidos. Ao longo do dia, João recebe notificações como: "Seu ônibus da linha A205 sai em 10 minutos" ou "Hora de ir para a estação de metrô Central". Se houver atrasos detectados no percurso, o app sinaliza com alertas para ajustes no plano. |
| **Avaliação** | Matheus sente que sua rotina está mais organizada e consegue reduzir o tempo de espera entre transportes. Ele reconhece que o planejamento de viagens oferece mais previsibilidade e praticidade, melhorando sua experiência diária de deslocamento. |

---

## Cenário 10 – Análise Preditiva de Horários dos Ônibus com IA (Requisito não implementado)

**Autoria: João Gabriel, 2025.**

| Elemento | Descrição |
|----------|-----------|
| **Ambiente ou contexto** | Juliana está voltando para casa após a aula noturna e costuma pegar o ônibus da linha A208 às 22h30. Apesar do horário fixo no sistema, ela já percebeu que o ônibus frequentemente atrasa ou adianta alguns minutos, dificultando sua organização e aumentando o tempo de espera no ponto, que é pouco movimentado nesse horário. O aplicativo **Dev no Ponto** passa a utilizar uma funcionalidade de **análise preditiva**, baseada no histórico de viagens, para informar com mais precisão o horário real de chegada do ônibus. |
| **Atores** | Juliana Ferreira Monteiro, 23 anos, estudante. Utiliza transporte público diariamente, especialmente em horários noturnos. Preza por segurança e previsibilidade para evitar ficar sozinha em pontos de ônibus à noite. Tem facilidade no uso de aplicativos de mobilidade. |
| **Objetivos** | Receber informações mais precisas sobre o horário de chegada real do ônibus com base em dados históricos e predições inteligentes, evitando esperas longas e aumentando a segurança e confiança no transporte público. |
| **Planejamento** | Juliana abre o aplicativo, seleciona a linha A208 e ativa a opção "Usar previsão inteligente de horário". Ela programa um alerta para ser notificada 5 minutos antes do horário previsto de chegada real, calculado com base em dados anteriores. |
| **Ações** | O sistema analisa dados de localização em tempo real combinados com históricos de atrasos e padrões de trânsito da linha. Com base nisso, estima que, embora o horário oficial seja 22h30, a chegada mais provável será às 22h42. Uma notificação sonora e visual é enviada para Juliana no horário correto, permitindo que ela vá até o ponto com tempo justo. |
| **Eventos** | O algoritmo preditivo atualiza o horário estimado conforme a posição do ônibus muda. Caso ocorra um imprevisto no trajeto, o horário previsto também é ajustado. Na tela, Juliana visualiza a mensagem: "Previsão de chegada: 22h42 (com base em 187 viagens anteriores)". |
| **Avaliação** | Juliana chega ao ponto pouco antes da chegada real do ônibus, evitando tempo de espera desnecessário. Ela reconhece a utilidade da previsão inteligente e sente mais segurança e tranquilidade ao se deslocar em horários noturnos. A funcionalidade melhora sua experiência com o transporte público e aumenta sua confiança no aplicativo. |

<div align="center">

O vídeo 4 apresenta a validação dos cenários 9 e 10 com um usuário real, perguntando se é válido o uso de um possível recurso de planejamento de viagens e predição de rotas por IA.

<iframe width="560" height="315" src="https://www.youtube.com/embed/h7kit9J3hAo" title="Vídeo demonstrativo" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

*Vídeo 4: Validação dos cenários 9 e 10*

</div>

---

## Cenário 11 – Alertas de desvio e interrupção de rota (Requisito não implementado)
<span style="color:blue;">Autoria: Daniel Nunes Duarte, 2025.</span>

| **Elemento** | **Descrição** |
| :-----------: | :------------ |
| **Ambiente ou contexto** | Ana está em casa se arrumando antes de sair para o estágio. Em alguns dias ocorrem obras, desvios ou ocorrências que alteram o itinerário ou interrompem a circulação de determinada linha. Ana precisa saber, com antecedência, se sua linha sofrerá desvios, atrasos significativos ou cancelamentos para ajustar seu horário de saída e evitar perder a conexão. |
| **Atores** | Ana, estudante universitária que utiliza ônibus diariamente para ir ao estágio. Possui familiaridade com apps móveis e depende de informações confiáveis sobre circulação e itinerário. |
| **Objetivos** | Receber alertas em tempo real sobre desvios, interrupções ou mudanças de itinerário nas linhas de interesse, além de receber sugestões de rotas alternativas quando houver impacto no trajeto. |
| **Planejamento** | Ana marca sua linha favorita e ativa a opção "Alertas de desvio/interrupção" nas configurações do aplicativo. Define um raio de notificações para o ponto onde costuma embarcar e opta por notificações por push e notificações na tela inicial. |
| **Ações** | 1. Abrir o aplicativo.
2. Selecionar a linha favorita e o ponto de embarque.
3. Ativar "Alertas de desvio/interrupção" e configurar preferências de notificação.
4. Receber notificação push quando o sistema detectar um desvio, interrupção ou cancelamento que afete a linha/ponto selecionado.
5. Consultar as sugestões de rotas alternativas ou estimativas de atraso oferecidas pelo aplicativo e decidir o horário de saída de casa. |
| **Eventos** | O sistema recebe sinalizações de operadores, sensores ou detecção por GPS de desvios no itinerário; registra interrupções e calcula impacto no tempo de chegada. Em seguida, dispara notificações aos usuários afetados, exibe a causa (obra, acidente, operação) e sugere rotas alternativas ou pontos de embarque diferentes. |
| **Avaliação** | Ana considera a ação bem-sucedida quando recebe o alerta com antecedência suficiente para ajustar sua saída, visualiza alternativas viáveis e consegue embarcar sem grandes atrasos. O sucesso é medido pela redução do tempo de espera imprevisto e pela capacidade do usuário de escolher uma alternativa que minimize o impacto no deslocamento. |

---

## Cenário 12 – Integração ônibus e metrô (Requisito não implementado)
<span style="color:blue;">Autoria: Daniel Nunes Duarte, 2025.</span>

| **Elemento** | **Descrição** |
| :-----------: | :------------ |
| **Ambiente ou contexto** | Suianne utiliza diariamente ônibus e metrô para ir ao trabalho. Em alguns trechos do trajeto ela precisa transferir entre os dois modais e depende de informações precisas sobre a localização e previsão de chegada tanto dos ônibus quanto dos trens do metrô para sincronizar sua saída de casa e as conexões. |
| **Atores** | Suianne, trabalhadora da área de vendas que combina ônibus e metrô em seu deslocamento casa→trabalho. Tem familiaridade com apps de mobilidade e valoriza informações de integração entre modais. |
| **Objetivos** | Visualizar em um único mapa a localização em tempo real dos ônibus e do metrô, com previsões de chegada nas respectivas paradas/estações, para escolher a melhor sequência de embarques e reduzir o tempo de espera. |
| **Planejamento** | Suianne abre o aplicativo DF no Ponto e seleciona as linhas de ônibus e a estação de metrô que fazem parte do seu trajeto. Ela ativa a visualização integrada para monitorar ambos os modais enquanto se aproxima do ponto de conexão. |
| **Ações** | 1. Abrir o aplicativo.
2. Selecionar a linha de ônibus e/ou estação de metrô desejada.
3. Ativar a opção de "Rastrear múltiplos modais" (ônibus + metrô).
4. Visualizar no mapa os ícones diferenciados para ônibus e trens e conferir as previsões de chegada.
5. Decidir o momento de sair de casa ou de seguir para a estação com base nas previsões combinadas. |
| **Eventos** | Os sistemas de GPS dos ônibus e os dados de sinalização do metrô atualizam as posições no sistema central. O servidor cruza as informações e exibe, no app de Suianne, as previsões de chegada e alertas de conexão. Caso haja atraso em um dos modais, o app sugere alternativas (aguardar próximo ônibus, trocar por outra estação/linha ou ajustar a rota). |
| **Avaliação** | Suianne considera o recurso eficaz quando consegue sincronizar as conexões com confiança, reduzindo esperas e evitando perder o trem ou o ônibus de conexão. O sucesso é medido pela redução do tempo total de deslocamento e pelo aumento da previsibilidade das integrações. |

---

## Responsáveis pela elaboração do artefato

| Nome            | Responsabilidade              |
|-----------------|-------------------------------|
| **Cauã Nicolas** | - Elaboração e Validação dos cenários 7 e 8 |
| **Daniel Nunes Duarte** | - Elaboração dos cenários 11 e 12 |
| **Fernanda Vaz** | - Elaboração dos texto de Introdução <br> - Elaboração dos cenários 1 e 2 |
| **Gabriel Maciel** | - Elaboração e Validação dos cenários 3 e 4 |
| **João Ramos** | - Elaboração e Validação dos cenários 5 e 6 |
| **João Ramos** | - Elaboração e Validação dos cenários 9 e 10 |

## Bibliografia

## Referência bibliográfica 

<a id="ref-barbosa-silva"></a>
> BARBOSA, Simone D. J.; SILVA, Bruno S. *Interação Humano-Computador.* Rio de Janeiro: Elsevier, 2010.

<a id="ref-rosson-carroll"></a>
> ROSSON, M. B.; CARROLL, J. M. *Usability Engineering: Scenario-Based Development of Human-Computer Interaction.* San Francisco: Morgan Kaufmann, 2002..

---

## Histórico de Versão

| Versão | Data       | Descrição                        | Autor(es)      | Revisor       |
|:------:|:-----------|:---------------------------------|:---------------|:--------------|
| 1.0    | 08/10/2025 | Criação da estrutura inicial do documento. | Gabriel Maciel | Fernanda Vaz  |
| 1.1    | 05/10/2025 | Adição dos cenários 1 e 2 | Fernanda Vaz   | Gabriel Maciel |
| 1.2    | 10/10/2025 | Adição dos cenários 3 e 4 | Gabriel Maciel   | João Ramos |
| 1.3    | 10/10/2025 | Adição dos cenários 5 e 6 | João Ramos   | Gabriel Maciel |
| 1.4 | 10/10/2025 | Adição dos cenários 7 e 8 | Cauã Nicolas | Gabriel Maciel |
| 1.5 | 12/10/2025 | Adição dos vídeos de Validação com usuário dos Cenários 3 a 4 | Gabriel Maciel | João Ramos, Cauã Nicolas |
| 1.6 | 12/10/2025 | Adição da Validação com usuário dos Cenários 9 a 10 | João Gabriel | João Ramos, Fernanda Vaz |
| 1.7 | 12/10/2025 | Adição do Cenário 11 e Cenário 12; atualização de autores e validação | Daniel Nunes Duarte | --------- |
| 1.8 | 12/10/2025 | Atualização do Cenário 11 para evitar duplicidade com Cenário 3 (alterado para alertas de desvio/interrupção) | Daniel Nunes Duarte | --------- |

## Agradecimentos
>>Agradecemos o suporte da ferramenta de Inteligência Artificial Generativa Google Gemini no desenvolvimento deste trabalho. Em conformidade com o Código de Conduta da Sociedade Brasileira de Computação (SBC), declaramos que a ferramenta foi utilizada como auxílio na revisão gramatical e estilística do texto, na sugestão de estrutura para seções específicas do artigo, bem como na formatação de tabelas e na descrição de figuras. Ressaltamos que os autores assumem total responsabilidade por todo o conteúdo apresentado, incluindo sua originalidade e precisão. A ferramenta não figura como autora desta publicação.