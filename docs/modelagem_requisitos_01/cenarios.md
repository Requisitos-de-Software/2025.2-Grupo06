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
| **Ações** | O app exibe as linhas intermunicipais (ex: "Linha 200 - Brasília/Luziânia"), com horários de saída (06:00, 08:00, 10:00, 12:00...), tempo de viagem (aproximadamente 1h15min) e principais pontos de parada em Luziânia. Maria seleciona o horário das 10:00 e salva como favorito. |
| **Eventos** | O sistema integra dados de empresas de transporte intermunicipal do entorno. Exibe informações atualizadas sobre linhas, horários e itinerários. Quando disponível, mostra também a localização em tempo real dos ônibus intermunicipais. Maria recebe uma notificação: "Linha salva com sucesso. Horário selecionado: 10:00". |
| **Avaliação** | Maria consegue planejar sua viagem a Luziânia sem precisar usar outro aplicativo ou ir até a rodoviária presencialmente para consultar horários. Fica satisfeita com a ampliação da cobertura para o entorno e reconhece que isso torna o app mais completo e útil para quem precisa se deslocar entre o DF e cidades vizinhas. |

---




## Bibliográfia.
>GOOGLE. Gemini. Versão de 9 de outubro de 2025. [S. l.], 2025. Disponível em: https://gemini.google.com. Acesso em: 9 out. 2025.

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
| 1.1    | 05/10/2025 | Adição dos cenários elaborados.  | Fernanda Vaz   | Gabriel Maciel |
