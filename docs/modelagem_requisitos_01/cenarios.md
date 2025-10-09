## Descrição

Cenários são descrições detalhadas, elaboradas em linguagem natural, que representam situações ou eventos específicos envolvendo a interação entre atores, ambientes e o sistema. Sua principal função é facilitar a compreensão da dinâmica dessas interações, além de ilustrar o funcionamento esperado do sistema, detalhando seu fluxo e comportamento em diversas circunstâncias. Os cenários desenvolvidos neste trabalho estão apresentados nas tabelas.

---

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

## Cenário 2 – Avaliação de Linhas (Requisito não implementado)
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

## Bibliografia
> BARBOSA, Simone D. J.; SILVA, Bruno S. *Interação Humano-Computador.* Rio de Janeiro: Elsevier, 2010.

---

## Histórico de Versão

| Versão | Data       | Descrição                        | Autor(es)      | Revisor       |
|:------:|:-----------|:---------------------------------|:---------------|:--------------|
| 1.0    | 08/10/2025 | Criação da estrutura inicial do documento. | Gabriel Maciel | Fernanda Vaz  |
| 1.1    | 05/10/2025 | Adição dos cenários elaborados.  | Fernanda Vaz   | Gabriel Maciel |
