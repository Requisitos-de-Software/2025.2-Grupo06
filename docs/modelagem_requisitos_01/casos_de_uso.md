## Introdução
O objetivo do diagrama de caso de uso em UML é demonstrar as diferentes maneiras que o usuário pode interagir com um sistema. Um diagrama de caso de uso adequado dá uma visão geral do relacionamento entre casos de uso, atores e sistemas. O caso de uso é representado por uma forma oval rotulada. Bonecos palito representam os atores no processo, e a participação do ator no sistema é modelada com uma linha entre o ator e o caso de uso. Para representar o limite do sistema, desenhe uma caixa em torno do próprio caso de uso. [(Lucidchart, 2025)](#ref-Lucid).


## Metodologia
Segundo o vídeo do [(Lucidchart, 2025)](#ref-Lucid), os elementos apresentados na tabela 1, que descreve o elemento e dá um exemplo visual, são todos os elementos que podem conter em um caso de uso.

### Tabela 1: Elementos, descrições e representações gráficas do Diagrama de Casos de Uso

<table border="1" style="border-collapse: collapse; width: 100%; text-align: left;">
  <thead>
    <tr>
      <th>Elemento</th>
      <th>Descrição</th>
      <th>Exemplo Visual</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>Sistema</b></td>
      <td>Representa o escopo do que está sendo desenvolvido (site, aplicativo, processo etc.). É mostrado como um retângulo com o nome do sistema no topo. Tudo o que está dentro pertence ao sistema; o que está fora é externo.</td>
      <td style="text-align: center;">
        <img src="https://i.ibb.co/LsgM4SC/image.png" alt="Retângulo representando o sistema" width="90">
      </td>
    </tr>
    <tr>
      <td><b>Ator</b></td>
      <td>Representa quem ou o que interage com o sistema para atingir uma meta. Pode ser uma pessoa, organização, outro sistema ou dispositivo externo. É exibido como um boneco de palito.</td>
      <td style="text-align: center;">
        <img src="https://i.ibb.co/7dbbfb20/image.png" alt="Ator - figura de palito com círculo como cabeça" width="90">
      </td>
      <tr>
      <tr>
      <td><b>Caso de Uso</b></td>
      <td>Representa uma ação ou funcionalidade do sistema, escrita no infinitivo com verbo (ex: <i>Fazer login</i>, <i>Consultar saldo</i>, <i>Fazer pagamento</i>). É mostrado como uma elipse.</td>
      <td style="text-align: center;">
        <img src="https://i.ibb.co/kVXrhzk9/image.png" alt="Elipse representando caso de uso" width="900">
      </td>
    </tr>
    <tr>
      <td><b> Relacionamento de Associação</b></td>
      <td>Linha sólida entre ator e caso de uso, indicando interação direta (ex: cliente → fazer login).</td>
       <td style="text-align: center;">
        <img src="https://i.ibb.co/fzTpJLbc/ASSOCIA-O.png" alt="Relação de ASSOCIA-O" width="900">
    </td>
    </tr>
    <tr>
      <td><b>Relacionamento de Inclusão (<code>&lt;&lt;include&gt;&gt;</code>)</b></td>
      <td>Indica que um caso de uso base <b>sempre</b> executa outro caso de uso incluído como parte do seu fluxo (ex: <i>Fazer login</i> inclui <i>Verificar senha</i>). Representado por linha tracejada com seta apontando para o caso incluído.</td>
      <td style="text-align: center;">
        <img src="https://i.ibb.co/QFTrLSHb/ICLUS-O.png" alt="Relação de inclusão" width="900">
      </td>
    </tr>
    <tr>
      <td><b>Relacionamento de Extensão (<code>&lt;&lt;extend&gt;&gt;</code>)</b></td>
      <td>Indica que um caso de uso estendido <b>pode</b> ocorrer sob certas condições (ex: <i>Exibir erro de login</i> estende <i>Fazer login</i>). Linha tracejada com seta apontando para o caso base.</td>
      <td style="text-align: center;">
        <img src="https://i.ibb.co/zhDjMWTg/EXTEN-O.png"  alt="Relação de extensão" width="900">
      </td>
    </tr>
    <tr>
      <td><b>Generalização / Herança</b></td>
      <td>Representa especialização entre casos de uso ou atores (ex: <i>Pagar da conta corrente</i> e <i>Pagar da conta poupança</i> herdam de <i>Fazer pagamento</i>). Linha sólida com seta do específico para o geral.</td>
      <td style="text-align: center;">
        <img src="https://i.ibb.co/tpCCmvSw/HERAN-A.png" alt="Generalização - seta sólida" width="150">
      </td>
    </tr>
  </tbody>
</table>

---
## Diagrama de Casos de Uso
<p style="text-align: center; font-size: 0.85em; font-style: italic;">Figura 1: Casos de uso do app DF no Ponto  
<br>Autoria: Fernanda Vaz, 2025.
</p>

<div style="width: 640px; height: 480px; margin: 10px; position: relative;"><iframe allowfullscreen frameborder="0" style="width:640px; height:480px" src="https://lucid.app/documents/embedded/080b2523-5076-4f95-b29a-9b0eda02288f" id="LNtYFI8byYwG"></iframe></div>


---

## Especificação de Casos de Uso

### Modelo de Tabela para Especificação de Casos de Uso

#### Tabela 2 - UCXX: Nome do caso de uso 

| **Campo**                   |  **Descrição** |
|-----------------------------|----------------|
| **Atores**                  |                |
| **Descrição do Caso de Uso**|                |
| **Pré-Condições**           |                |
| **Pós-condições**           |                |
| **Fluxo básico**            |                |
| **Fluxos alternativos**     |                |
| **Fluxos de exceção**       |                |
| **Data da criação**         |                |
| **Rastreabilidade**         |                |


A Tabela 2 foi construída a partir de informações obtidas da documentação de Especificação de Caso de Uso do Ministério da Ciência, Tecnologia, Informações e Comunicações (MCTIC). Este documento definiu que:

- **Atores**: São entidades que interagem com os casos de uso do sistema;
- **Descrição do Caso de Uso**: É uma descrição clara, concisa e compreensível que documenta determinado comportamento (ação) de um sistema. É formatado da seguinte forma:
- **Pré-condições**: É uma descrição do estado em que o sistema deve estar antes da realização do caso de uso em questão;
- **Pós-condições** : É uma descrição do estado em que o sistema poderá se encontrar após o término do caso de uso em questão;
- **Fluxo Básico**: É uma descrição que descreve o que o Ator faz e o que o sistema faz em resposta a essa ação, sem explicitar o "porquê" e nem o "como";
- **Fluxos Alternativos (opcional)**: É uma descrição de um fluxo alternativo devido a variações que podem ocorrer ao fluxo básico. Ao fim deste fluxo, os eventos do fluxo básico são retomados a menos que seja especificado de outra maneira
- **Fluxos de exceção**: É a descrição de um comportamento de exceção que acontece durante o fluxo básico ou alternativo.

Além das informações sobre Especificação de Casos de Uso extraídas da documentação do MCTIC, foram adicionadas, para fins de rastreabilidade, as linhas:

- **Data de criação**: Contém data inicial da criação da especificação do caso de uso;
- **Rastreabilidade**: Contém o ID e a descrição de requisitos funcionais que se relacionam ao caso de uso.

---

A Tabela 3 apresenta a especificação detalhada do caso de uso UC01, que permite aos passageiros avaliar a qualidade das linhas de ônibus através de um sistema de notas e comentários.

### Tabela 3 - UC01: Avaliação de Linhas de Ônibus (Requisito não implementado)

| **Campo**             | **Descrição** |
|----------------------|----------------|
| **Atores**           |  Passageiro |
| **Pré-Condições**    | - Passageiro autenticado no sistema<br>- Linha de ônibus disponível para avaliação |
| **Fluxo principal**  | 1. Passageiro seleciona uma linha de ônibus para avaliar<br>2. Sistema exibe formulário de avaliação<br>3. Passageiro atribui nota de 1 a 5 estrelas<br>4. Passageiro pode adicionar comentário opcional <br>5. Passageiro confirma avaliação<br>6. Sistema valida os dados inseridos<br>7. Sistema registra avaliação no banco de dados<br>8. Sistema atualiza média de avaliações da linha<br>9. Sistema exibe mensagem de confirmação<br>10. Sistema retorna à tela anterior |
| **Fluxos alternativos** | **FA01 - Editar avaliação existente:**<br>1. Passageiro acessa suas avaliações anteriores<br>2. Seleciona avaliação para editar<br>3. Sistema carrega dados da avaliação<br>4. Passageiro modifica nota e/ou comentário<br>5. Prossegue do passo 5 do fluxo principal<br><br>**FA02 - Visualizar avaliações de outros usuários:**<br>1.  Passageiro acessa detalhes da linha<br>2. Sistema exibe média de avaliações e lista de comentários<br>3. passageiro pode filtrar por data ou nota<br>4. Sistema ordena avaliações conforme filtro selecionado<br><br>**FA03 - Cancelar avaliação:**<br>1. Passageiro clica em "Cancelar" durante preenchimento<br>2. Sistema exibe confirmação "Descartar avaliação?"<br>3. Passageiro confirma<br>4. Sistema descarta dados e retorna à tela anterior |
| **Fluxos de exceção**| **FE01 - Falha na conexão de internet:**<br>1. Sistema detecta ausência de conectividade ao tentar salvar<br>2. Exibe mensagem "Não foi possível salvar. Verifique sua conexão"<br>3. Sistema salva avaliação localmente<br>4. Reenvia automaticamente quando conexão for restabelecida<br><br>**FE02 - Comentário com conteúdo inadequado:**<br>1. Sistema detecta palavras ofensivas <br>2. Exibe mensagem "Comentário contém conteúdo inadequado"<br>3. Usuário deve revisar e modificar o comentário<br><br>**FE03 - Erro ao salvar avaliação:**<br>1. Sistema tenta salvar mas ocorre erro no servidor<br>2. Exibe mensagem "Erro ao processar avaliação. Tente novamente"<br>3. Mantém dados preenchidos para nova tentativa<br><br>**FE04 - passageiro já avaliou recentemente:**<br>1. Sistema detecta avaliação duplicada no mesmo dia<br>2. Oferece opção de editar avaliação existente<br>3. Se usuário confirmar, redireciona para FA01 |
| **Pós-condições**    | - Avaliação registrada no banco de dados<br>- Média de avaliações da linha atualizada<br>- Histórico de avaliações do usuário atualizado<br>- Estatísticas da linha recalculadas |
| **Data da criação**  | 10/10/2025 |
| **Rastreabilidade**  | Relacionado com: <br>Consulta de Horários e Rotas<br> Notificações de Chegada<br> Avaliação de linhas<br> Usabilidade da interface |

*Autoria: Fernanda Vaz, 2025*

A Tabela 4 apresenta a especificação detalhada do caso de uso UC02, que define o sistema de notificações automáticas para informar os passageiros sobre a chegada iminente dos ônibus.

### Tabela 4 - UC02: Notificações de Chegada de Ônibus (Requisito não implementado)

| **Campo**             | **Descrição** |
|----------------------|----------------|
| **Atores**           | Passageiro e Serviço de GPS |
| **Pré-Condições**    | - Passageiro autenticado no sistema<br>- GPS do dispositivo habilitado<br>- Permissões de notificação concedidas ao aplicativo<br>- Linha de ônibus com rastreamento disponível |
| **Fluxo principal**  | 1. Passageiro seleciona uma linha de ônibus no aplicativo<br>2. Sistema exibe informações da linha e botão "Ativar notificações"<br>3. Passageiro clica em "Ativar notificações"<br>4. Sistema solicita confirmação de ponto de referência (parada atual)<br>5. Passageiro confirma ou seleciona parada desejada<br>6. Sistema inicia monitoramento da localização do ônibus em tempo real<br>7. Sistema detecta que o ônibus está a 1km da parada<br>8. Sistema envia primeira notificação: "Seu ônibus está chegando em aproximadamente 5 minutos"<br>9. Sistema continua monitorando<br>10. Quando ônibus está a 500m, sistema envia notificação: "Seu ônibus está chegando em 2 minutos"<br>11. Sistema mantém notificação ativa até chegada do ônibus<br>12. Após chegada, sistema desativa notificação automaticamente |
| **Fluxos alternativos** | **FA01 - Desativar notificações:**<br>1. Passageiro acessa notificações ativas<br>2. Seleciona linha para desativar<br>3. Sistema para monitoramento imediatamente<br>4. Exibe confirmação "Notificações desativadas"<br><br>**FA02 - Configurar múltiplas linhas:**<br>1. Passageiro ativa notificações para mais de uma linha<br>2. Sistema monitora todas as linhas simultaneamente<br>3. Envia notificações individuais para cada linha<br><br>**FA03 - Ajustar distância de notificação:**<br>1. Passageiro acessa configurações de notificações<br>2. Modifica raio de alerta (500m, 1km, 2km)<br>3. Sistema salva preferência<br>4. Aplica nova configuração ao monitoramento<br><br>**FA04 - Notificação de atraso:**<br>1. Sistema detecta atraso significativo do ônibus<br>2. Envia notificação: "Seu ônibus está com atraso de X minutos"<br>3. Atualiza tempo estimado de chegada |
| **Fluxos de exceção**| **FE01 - Falha na conexão de internet:**<br>1. Sistema detecta perda de conectividade<br>2. Exibe mensagem "Monitoramento pausado. Verifique sua conexão"<br>3. Salva estado atual do monitoramento<br>4. Retoma automaticamente quando conexão for restabelecida<br><br>**FE02 - GPS desabilitado:**<br>1. Sistema detecta que GPS está desligado<br>2. Envia notificação de alerta<br>3. Exibe tela: "Ative o GPS para receber notificações"<br>4. Oferece botão para acessar configurações do dispositivo<br><br>**FE03 - Ônibus não detectado:**<br>1. Sistema não consegue localizar ônibus por mais de 15 minutos<br>2. Envia notificação: "Não foi possível rastrear o ônibus"<br>3. Oferece opção de desativar notificação ou aguardar<br>4. Continua tentando se passageiro optar por aguardar<br><br>**FE04 - Permissão de notificação negada:**<br>1. Sistema detecta falta de permissão ao tentar enviar notificação<br>2. Exibe alerta na tela do app<br>3. Redireciona passageiro para configurações do sistema<br>4. Aguarda concessão de permissão<br><br>**FE05 - Bateria baixa:**<br>1. Sistema detecta nível crítico de bateria (<10%)<br>2. Reduz frequência de atualização de localização<br>3. Notifica passageiro sobre modo de economia ativado |
| **Pós-condições**    | - Notificação de chegada enviada com sucesso<br>- Log de notificação registrado no sistema<br>- Status de monitoramento atualizado<br>- Estatísticas de uso do serviço atualizadas |
| **Data da criação**  | 10/10/2025 |
| **Rastreabilidade**  | Relacionado com:<br> Consulta de Horários e Rotas<br>Avaliação de Linhas<br> Performance de notificações em tempo real<br> Disponibilidade do sistema<br>Precisão de geolocalização |

*Autoria: Fernanda Vaz, 2025*

A Tabela 5 apresenta a especificação detalhada do caso de uso UC03, que permite aos passageiros visualizar simultaneamente múltiplas linhas de ônibus no mapa e obter informações detalhadas sobre cada uma delas.

<a id="tabela-5---uc03-rastreamento-de-múltiplas-linhas-requisito-não-implementado"></a>
### Tabela 5 - UC03: Rastreamento de Múltiplas Linhas (Requisito não implementado)


| **Campo**                   |  **Descrição** |
|-----------------------------|----------------|
| **Atores**                  | Passageiro e Serviço de GPS (Ônibus e Passageiro)|
| **Descrição do Caso de Uso**| Possibilita ao passageiro visualizar simultaneamente múltiplas linhas de ônibus no mapa e obter informações detalhadas sobre rota e numeração ao clicar em qualquer ônibus |
| **Pré-Condições**           |- **PRE01**: Passageiro deve ter conexão com a internet <br> - **PRE02**: GPS deve estar ativado <br> - **PRE03**: Destino do passageiro deve conter múltiplas linhas de ônibus <br> - **PRE04**: Sistema deve ter dados de rastreamento disponíveis para as linhas |
| **Pós-condições**           |- Sistema exibe simultaneamente múltiplas linhas de ônibus no mapa <br> - Cada linha é representada com cor e ícone distintivos <br> - Passageiro pode acessar informações de rota e numeração de qualquer ônibus <br> - Dados de localização são atualizados em tempo real |
| **Fluxo básico**            | **FB01.** Passageiro acessa a funcionalidade "Ver múltiplas linhas" no mapa <br> **FB02.** Sistema exibe mapa com todas as linhas disponíveis na região <br> **FB03.** Passageiro visualiza ônibus de diferentes linhas com cores/ícones distintos <br> **FB04.** Sistema atualiza posições dos ônibus em tempo real a cada 20 segundos <br> **FB05.** Passageiro clica em um ônibus específico no mapa <br> **FB06.** Sistema exibe popup com informações básicas do ônibus <br> **FB07.** Popup mostra: número da linha, destino, e próxima parada <br> **FB08.** Passageiro clica em "Ver rota completa" <br> **FB09.** Sistema exibe janela detalhada com trajeto completo da linha <br> **FB10.** Sistema destaca rota no mapa com todas as paradas <br> **FB11.** Passageiro pode navegar pelas informações da rota <br> **FB12.** Passageiro fecha detalhes e retorna à visualização geral |
| **Fluxos alternativos**     | **FA01 - Filtrar linhas específicas:** <br> 1. Passageiro acessa filtros no canto superior direito <br> 2. Seleciona linhas específicas para exibir <br> 3. Sistema oculta ônibus das linhas não selecionadas <br> 4. Mapa atualizado mostra apenas linhas filtradas <br> 5. Retorna ao fluxo básico FB04 <br><br> **FA02 - Visualizar informações sem clicar:** <br> 1. Passageiro passa o dedo sobre um ônibus (hover/touch) <br> 2. Sistema exibe tooltip com número da linha <br> 3. Tooltip desaparece quando passageiro move o dedo <br> 4. Retorna ao fluxo básico FB04 <br><br> **FA03 - Buscar linha específica:** <br> 1. Passageiro digita número da linha na barra de busca <br> 2. Sistema destaca todos os ônibus dessa linha <br> 3. Mapa centraliza na região com ônibus da linha <br> 4. Outros ônibus ficam semi-transparentes <br> 5. Retorna ao fluxo básico FB04 |
| **Fluxos de exceção**       | **FE01 - Muitas linhas na região (sobrecarga visual):** <br> 1. Sistema detecta mais de 10 linhas na área visível <br> 2. Exibe mensagem "Muitas linhas na região. Use filtros para melhor visualização" <br> 3. Sistema agrupa ônibus próximos em clusters numerados <br> 4. Passageiro pode aumentar zoom para ver ônibus individuais <br><br> **FE02 - Falha na conexão:** <br> 1. Sistema detecta perda de conectividade <br> 2. Exibe banner "Modo offline - dados podem estar desatualizados" <br> 3. Sistema mantém última posição conhecida dos ônibus <br> 4. Desabilita funcionalidade de clique até conexão retornar <br><br> **FE03 - Ônibus sem dados de rota:** <br> 1. Passageiro clica em ônibus sem informações detalhadas <br> 2. Popup exibe apenas: "Linha X - Informações detalhadas indisponíveis" <br> 3. Sistema oferece opção "Reportar problema" <br> 4. Mantém funcionalidades básicas de visualização <br><br> **FE04 - GPS desabilitado:** <br> 1. Sistema detecta que GPS está desligado <br> 2. Exibe alerta: "Ative o GPS para ver sua localização no mapa" <br> 3. Mapa funciona normalmente, mas sem indicador de posição do usuário <br> 4. Oferece botão para acessar configurações do dispositivo |
| **Data da criação**         |11/10/25|
| **Rastreabilidade**         | **ENT12**: O sistema permite o rastreamento de múltiplas linhas de ônibus simultaneamente no mapa. |

*Autoria: Daniel Nunes Duarte, 2025*

A Tabela 6 apresenta a especificação detalhada do caso de uso UC04, que permite aos passageiros consultar saldo e recarregar o cartão BRB Mobilidade diretamente pelo aplicativo, oferecendo praticidade e agilidade nas transações.

### Tabela 6 - UC04: Integração com BRB Mobilidade (Requisito não implementado)

| **Campo**                   |  **Descrição** |
|-----------------------------|----------------|
| **Atores**                  | Passageiro do transporte público |
| **Descrição do Caso de Uso**| Permite ao passageiro consultar saldo e recarregar o cartão BRB Mobilidade diretamente pelo aplicativo |
| **Pré-Condições**           | - Passageiro autenticado no sistema<br>- Cartão BRB Mobilidade válido<br>- Conexão com internet |
| **Pós-condições**           | - Saldo do cartão atualizado<br>- Transação registrada no sistema |
| **Fluxo básico**            | **FB01.** Passageiro acessa seção "Meu Cartão"<br>**FB02.** Sistema solicita número do cartão BRB<br>**FB03.** Passageiro informa dados do cartão<br>**FB04.** Sistema valida cartão e exibe saldo atual<br>**FB05.** Passageiro seleciona "Recarregar"<br>**FB06.** Sistema exibe valores disponíveis para recarga<br>**FB07.** Passageiro escolhe valor desejado<br>**FB08.** Sistema apresenta opções de pagamento (cartão de débito, crédito ou Pix)<br>**FB09.** Passageiro seleciona forma de pagamento<br>**FB10.** Sistema processa pagamento<br>**FB11.** Sistema confirma recarga e exibe novo saldo |
| **Fluxos alternativos**     | **FA01 - Consultar apenas o saldo:**<br>1. Passageiro acessa "Meu Cartão"<br>2. Sistema exibe saldo sem realizar recarga<br><br>**FA02 - Histórico de transações:**<br>1. Passageiro acessa histórico no cartão vinculado<br>2. Sistema exibe últimas transações realizadas<br><br>**FA03 - Vincular novo cartão:**<br>1. Passageiro acessa "Meu Cartão"<br>2. Sistema detecta ausência de cartão vinculado<br>3. Sistema exibe tela de vínculo de cartão<br>4. Passageiro informa número do cartão BRB<br>5. Sistema valida cartão e solicita confirmação<br>6. Passageiro confirma vínculo<br>7. Sistema registra cartão e retorna ao fluxo básico FB04 |
| **Fluxos de exceção**       | **FE01 - Passageiro sem cartão registrado:**<br>1. Sistema detecta cartão inexistente<br>2. Exibe mensagem "Cartão não encontrado"<br><br>**FE02 - Falha no pagamento:**<br>1. Sistema detecta erro na transação<br>2. Exibe mensagem "Pagamento não processado. Tente novamente"<br><br>**FE03 - Erro de conexão com BRB:**<br>1. Sistema não consegue comunicar com API<br>2. Exibe mensagem "Serviço temporariamente indisponível" |
| **Data da criação**         | 11/10/2025 |

*Autoria: Gabriel Maciel, 2025*

A Tabela 7 apresenta a especificação detalhada do caso de uso UC05, que permite aos passageiros visualizar as viagens realizadas, incluindo horários, rotas, meio de transporte e duração.

### Tabela 7 - UC05: Histórico de Viagens (Requisito não implementado)

| **Campo** | **Descrição** |
|------------|----------------|
| **Atores** | Passageiro|
| **Descrição** | Permite que o passageiro visualize as viagens realizadas recentemente, incluindo horários, rotas, meios de transporte e duração. |
| **Pré-condições** | O passageiro deve estar autenticado no aplicativo e ter realizado pelo menos uma viagem registrada. |
| **Pós-condições** | O sistema exibe uma lista com as viagens concluídas e seus respectivos detalhes. |
| **Fluxo Básico** | 1. O passageiro acessa o menu principal. <br>2. Seleciona a opção “Histórico de Viagens”. <br>3. O sistema busca os registros anteriores. <br>4. O histórico é exibido com data, horário, rota e meio de transporte. |
| **Fluxos Alternativos** | 1a. O passageiro filtra o histórico por data, rota ou meio de transporte. <br>1b. O sistema exibe apenas as viagens filtradas. |
| **Fluxos de Exceção** | 1. Caso o passageiro não possua viagens registradas, o sistema exibe a mensagem “Nenhum histórico encontrado”. <br>2. Se ocorrer falha de conexão, o sistema exibe “Erro ao carregar dados. Verifique sua internet.” |
| **Data de Criação** | 12/10/2025 |
| **Rastreabilidade** | **RNI03** — Relacionado aos requisitos não implementados de registrar e exibir viagens realizadas pelo passageiro. |

*Autoria: Cauã Nicolas, 2025*

A Tabela 8 apresenta a especificação detalhada do caso de uso UC06, que é ampliado a cobertura de informações de transporte púlbico, englobando a área do entorno do Distrito Federal.

### Tabela 8 - UC06: Ampliação da cobertura de informações de transporte do entorno do DF  (Requisito não implementado)

| **Campo** | **Descrição** |
|------------|----------------|
| **Atores** | Administrador do sistema, Sistema (aplicativo) |
| **Descrição** | O caso de uso visa expandir as informações de transporte público para as regiões do entorno do Distrito Federal, permitindo que passageiros dessas áreas também tenham acesso a horários, rotas e dados de deslocamento em tempo real. |
| **Pré-condições** | O sistema deve estar conectado à base de dados atualizada das empresas de transporte do entorno. <br>O administrador deve ter acesso autorizado para cadastrar ou integrar novas informações. |
| **Pós-condições** | As novas rotas e horários do entorno são disponibilizados para consulta pelos passageiros no aplicativo. |
| **Fluxo Básico** | 1. O administrador acessa o painel de gestão do sistema. <br>2. Seleciona a opção “Adicionar nova cobertura de transporte”. <br>3. Insere as informações das linhas e horários das regiões do entorno. <br>4. O sistema valida e salva os novos dados. <br>5. Os passageiros passam a visualizar as novas linhas e rotas disponíveis. |
| **Fluxos Alternativos** | 1a. O sistema realiza integração automática com bases externas de transporte (ex: prefeituras ou consórcios). <br>1b. O administrador apenas confirma a sincronização das informações. |
| **Fluxos de Exceção** | 1. Se houver erro de integração com o banco de dados externo, o sistema exibe “Falha ao sincronizar dados do entorno”. <br>2. Caso os dados inseridos sejam inválidos, o sistema solicita correção antes de salvar. |
| **Data de Criação** | 12/10/2025 |
| **Rastreabilidade** | **ENT08** — Relacionado ao requisito funcional de expansão da cobertura e informações em regiões afastadas do Distrito Federal.  |

*Autoria: Cauã Nicolas, 2025*

A Tabela 8 apresenta a especificação detalhada do caso de uso UC07, que descreve o funcionamento do modo off-line do aplicativo, permitindo aos passageiros acessar informações essenciais mesmo sem conexão à internet, garantindo maior autonomia e acessibilidade durante o uso do sistema.

### Tabela 8 - UC07: Modo Off-line (Requisito não implementado)

| **Campo**                   |  **Descrição** |
|-----------------------------|----------------|
| **Atores**                  | Passageiro |
| **Descrição do Caso de Uso**| Permite ao passageiro baixar previamente dados de linhas, trajetos, paradas e horários para consultar offline quando estiver sem conexão de internet |
| **Pré-Condições**           | - Passageiro autenticado no sistema<br>- Conexão Wi-Fi ou dados móveis disponível para download<br>- Espaço de armazenamento suficiente no dispositivo (mínimo 20 MB) |
| **Pós-condições**           | - Dados salvos localmente no dispositivo<br>- Modo offline ativado e funcional<br>- Informações acessíveis sem necessidade de internet |
| **Fluxo básico**            | **FB01.** Passageiro conecta-se a uma rede Wi-Fi<br>**FB02.** Passageiro acessa "Configurações" no app<br>**FB03.** Passageiro seleciona opção "Modo Offline"<br>**FB04.** Sistema exibe tela de seleção de conteúdo para download<br>**FB05.** Passageiro seleciona linhas de uso frequente<br>**FB06.** Passageiro seleciona paradas próximas de casa, trabalho ou universidade<br>**FB07.** Sistema calcula tamanho do download (ex: 15 MB)<br>**FB08.** Passageiro confirma download<br>**FB09.** Sistema baixa trajetos, horários, mapas das rotas e lista de paradas<br>**FB10.** Sistema salva dados localmente<br>**FB11.** Sistema confirma: "Dados salvos para consulta offline"<br>**FB12.** No dia seguinte, passageiro perde conexão de internet<br>**FB13.** Sistema detecta ausência de conexão automaticamente<br>**FB14.** Sistema exibe ícone "Modo Offline ativo"<br>**FB15.** Passageiro consulta trajeto, horários e paradas sem internet<br>**FB16.** Sistema exibe dados armazenados localmente |
| **Fluxos alternativos**     | **FA01 - Atualizar dados offline:**<br>1. Passageiro acessa "Modo Offline" nas configurações<br>2. Seleciona "Atualizar dados"<br>3. Sistema verifica conexão disponível<br>4. Sistema baixa atualizações de horários e rotas<br>5. Substitui dados antigos pelos novos<br>6. Exibe "Dados atualizados com sucesso"<br><br>**FA02 - Remover dados offline:**<br>1. Passageiro acessa "Modo Offline"<br>2. Seleciona "Gerenciar dados"<br>3. Sistema exibe lista de linhas e paradas salvas<br>4. Passageiro seleciona itens para remover<br>5. Confirma remoção<br>6. Sistema libera espaço de armazenamento<br><br>**FA03 - Download parcial:**<br>1. Passageiro seleciona apenas algumas linhas/paradas<br>2. Sistema reduz tamanho do download proporcionalmente<br>3. Salva apenas conteúdo selecionado<br><br>**FA04 - Sincronização automática:**<br>1. Sistema detecta conexão Wi-Fi<br>2. Verifica se há atualizações disponíveis<br>3. Baixa automaticamente novos horários<br>4. Notifica passageiro: "Dados offline atualizados" |
| **Fluxos de exceção**       | **FE01 - Espaço insuficiente:**<br>1. Sistema detecta falta de espaço durante download<br>2. Exibe mensagem "Espaço insuficiente. Libere XX MB"<br>3. Oferece opção de limpar cache do app<br>4. Passageiro pode escolher menos linhas para reduzir tamanho<br><br>**FE02 - Falha no download:**<br>1. Download é interrompido por perda de conexão<br>2. Sistema salva progresso parcial<br>3. Exibe "Download pausado. Conecte-se para continuar"<br>4. Retoma automaticamente quando conexão retornar<br><br>**FE03 - Dados desatualizados:**<br>1. Sistema detecta que dados offline têm mais de 30 dias<br>2. Exibe banner de alerta: "Dados podem estar desatualizados"<br>3. Sugere atualização quando houver conexão<br>4. Permite uso mas sinaliza como desatualizado<br><br>**FE04 - Tentativa de acessar dado não baixado:**<br>1. Passageiro busca linha não salva no modo offline<br>2. Sistema exibe "Informação não disponível offline"<br>3. Sugere linhas disponíveis salvas<br>4. Oferece download quando conexão retornar<br><br>**FE05 - Dados corrompidos:**<br>1. Sistema detecta erro ao ler dados salvos<br>2. Exibe "Erro nos dados offline. Novo download necessário"<br>3. Remove dados corrompidos automaticamente<br>4. Solicita novo download quando houver conexão |
| **Data da criação**         | 12/10/2025 |
| **Rastreabilidade**         | **ENT06**: O sistema deve funcionar em modo offline com dados previamente baixados<br>**BRS06**: Modo offline com funcionalidades básicas |

*Autoria: João Ramos, 2025*

A Tabela 9 apresenta a especificação detalhada do caso de uso UC08, que permite aos passageiros reportar em tempo real o nível de lotação dos ônibus, contribuindo para a melhoria da experiência dos usuários e para o monitoramento da demanda pelas empresas de transporte.

### Tabela 9 - UC08: Reportar lotação do ônibus (Requisito não implementado)

| **Campo**                   |  **Descrição** |
|-----------------------------|----------------|
| **Atores**                  | Passageiro |
| **Descrição do Caso de Uso**| Permite ao passageiro visualizar reportes de lotação feitos por outros usuários e reportar a lotação do ônibus em que está para ajudar a comunidade de passageiros a tomar decisões informadas |
| **Pré-Condições**           | - Passageiro autenticado no sistema<br>- Conexão com internet ativa<br>- GPS habilitado<br>- Sistema de rastreamento de ônibus operacional |
| **Pós-condições**           | - Reporte de lotação registrado no sistema<br>- Status de lotação do ônibus atualizado em tempo real<br>- Informação disponível para outros usuários<br>- Histórico de reportes do passageiro atualizado |
| **Fluxo básico**            | **FB01.** Passageiro acessa lista de ônibus se aproximando do ponto<br>**FB02.** Sistema exibe ônibus com ícones de lotação ao lado (verde=vazio, amarelo=médio, vermelho=lotado)<br>**FB03.** Sistema mostra quantidade de usuários que reportaram e há quanto tempo<br>**FB04.** Passageiro visualiza que primeiro ônibus está com ícone vermelho (9 reportes de "lotado" há 3 minutos)<br>**FB05.** Passageiro decide esperar próximo ônibus<br>**FB06.** Sistema mostra segundo ônibus com ícone amarelo (5 reportes de "médio")<br>**FB07.** Passageiro embarca no segundo ônibus<br>**FB08.** Passageiro acessa app durante a viagem<br>**FB09.** Sistema detecta que passageiro está em movimento (dentro do ônibus)<br>**FB10.** Sistema exibe botão "Reportar lotação"<br>**FB11.** Passageiro clica em "Reportar lotação"<br>**FB12.** Sistema apresenta opções: "Vazio", "Médio", "Lotado"<br>**FB13.** Passageiro seleciona "Médio"<br>**FB14.** Sistema confirma reporte e atualiza status em tempo real<br>**FB15.** Sistema exibe mensagem: "Lotação reportada: Médio (6 usuários confirmaram nos últimos 5 minutos)"<br>**FB16.** Outros usuários em paradas à frente visualizam informação atualizada |
| **Fluxos alternativos**     | **FA01 - Visualizar apenas sem reportar:**<br>1. Passageiro acessa lista de ônibus<br>2. Visualiza ícones de lotação<br>3. Toma decisão baseada em reportes<br>4. Não realiza próprio reporte<br>5. Sistema mantém reportes existentes<br><br>**FA02 - Alterar reporte anterior:**<br>1. Passageiro reporta lotação como "Médio"<br>2. Lotação aumenta durante trajeto<br>3. Passageiro acessa app novamente<br>4. Sistema detecta reporte recente<br>5. Oferece opção "Atualizar reporte"<br>6. Passageiro seleciona nova classificação<br>7. Sistema substitui reporte anterior<br><br>**FA03 - Visualizar histórico de reportes:**<br>1. Passageiro acessa histórico pessoal<br>2. Sistema exibe lista de reportes anteriores<br>3. Mostra data, hora, linha e lotação reportada<br>4. Passageiro pode verificar padrões de lotação<br><br>**FA04 - Reportar com comentário adicional:**<br>1. Após selecionar nível de lotação<br>2. Sistema oferece campo opcional de comentário<br>3. Passageiro adiciona observação (ex: "Muitos em pé")<br>4. Sistema salva reporte com comentário<br>5. Comentário visível para outros usuários |
| **Fluxos de exceção**       | **FE01 - Tentativa de reportar múltiplas vezes:**<br>1. Passageiro tenta reportar novamente após menos de 2 minutos<br>2. Sistema detecta reporte recente<br>3. Exibe mensagem "Você já reportou recentemente. Aguarde 2 minutos para novo reporte"<br>4. Bloqueia novo reporte temporariamente<br><br>**FE02 - Falha na conexão ao reportar:**<br>1. Passageiro seleciona nível de lotação<br>2. Sistema detecta perda de conexão<br>3. Exibe "Sem conexão. Reporte será enviado quando reconectar"<br>4. Sistema salva reporte localmente<br>5. Reenvia automaticamente quando conexão retornar<br><br>**FE03 - GPS desabilitado:**<br>1. Passageiro tenta reportar lotação<br>2. Sistema não consegue confirmar localização<br>3. Exibe "Ative o GPS para reportar lotação"<br>4. Oferece botão para configurações<br>5. Aguarda ativação do GPS<br><br>**FE04 - Nenhum reporte disponível:**<br>1. Passageiro visualiza ônibus sem ícone de lotação<br>2. Sistema não possui reportes recentes (>15 minutos)<br>3. Exibe "Sem reportes recentes. Seja o primeiro a reportar"<br>4. Incentiva passageiro a fazer primeiro reporte<br><br>**FE05 - Suspeita de spam/reportes falsos:**<br>1. Sistema detecta múltiplos reportes conflitantes do mesmo usuário<br>2. Algoritmo identifica padrão suspeito<br>3. Sistema solicita validação adicional<br>4. Pode temporariamente reduzir peso do reporte do usuário<br>5. Administrador analisa caso se padrão persistir<br><br>**FE06 - Ônibus não identificado:**<br>1. Passageiro tenta reportar mas sistema não identifica qual ônibus<br>2. Exibe "Não foi possível identificar o ônibus. Selecione manualmente"<br>3. Sistema lista ônibus próximos<br>4. Passageiro seleciona linha correta<br>5. Prossegue com reporte |
| **Data da criação**         | 12/10/2025 |
| **Rastreabilidade**         | **ENT11**: O sistema permite que os usuários avaliem e visualizem o nível de lotação do ônibus<br>**BRS03**: Sistema colaborativo de feedback sobre qualidade do serviço |

*Autoria: João Ramos, 2025*

### Tabela 10 - UC09: Planejamento de Viagens (Requisito não implementado)

A Tabela 10 apresenta a especificação detalhada do caso de uso UC09, que tem como objetivo fornecer alertas personalizados com base no perfil do usuário, permitindo que diferentes públicos (como estudantes, idosos ou moradores de regiões periféricas) recebam informações e notificações relevantes sobre o transporte público. Essa funcionalidade busca tornar a experiência mais personalizada, garantindo que cada usuário tenha acesso a informações específicas que impactam diretamente sua rotina de deslocamento.

<div align="center">

<p><strong>Tabela 10</strong> - UC09: Planejamento de Viagens</p>

<table>
  <tr>
    <th>Campo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td><strong>Atores</strong></td>
    <td>Passageiro</td>
  </tr>
  <tr>
    <td><strong>Descrição do Caso de Uso</strong></td>
    <td>Permite ao passageiro planejar suas viagens com antecedência, definindo origem, destino, horário desejado e preferências, para receber sugestões de rotas e alertas personalizados.</td>
  </tr>
  <tr>
    <td><strong>Pré-Condições</strong></td>
    <td>- Passageiro autenticado no sistema<br>- Conexão com internet ativa<br>- GPS habilitado (opcional, caso o usuário não informe manualmente a localização)<br>- Banco de dados de rotas e horários atualizado</td>
  </tr>
  <tr>
    <td><strong>Pós-condições</strong></td>
    <td>- Viagem planejada registrada no perfil do usuário<br>- Rotas e horários armazenados<br>- Alertas automáticos configurados para lembrar o passageiro antes do horário planejado</td>
  </tr>
  <tr>
    <td><strong>Fluxo básico</strong></td>
    <td>
      <strong>FB01.</strong> Passageiro acessa aba "Planejar Viagem" no aplicativo<br>
      <strong>FB02.</strong> Sistema solicita origem e destino<br>
      <strong>FB03.</strong> Passageiro informa dados manualmente ou usa GPS para detectar localização atual<br>
      <strong>FB04.</strong> Sistema solicita data e horário de saída ou chegada desejada<br>
      <strong>FB05.</strong> Passageiro informa preferências (ex: evitar baldeações, priorizar linhas preferidas)<br>
      <strong>FB06.</strong> Sistema processa as informações e busca as rotas disponíveis<br>
      <strong>FB07.</strong> Sistema exibe lista de rotas recomendadas, com tempo estimado de chegada e baldeações<br>
      <strong>FB08.</strong> Passageiro seleciona a rota desejada<br>
      <strong>FB09.</strong> Sistema salva a viagem planejada no perfil do passageiro<br>
      <strong>FB10.</strong> Sistema agenda alerta para horário de saída e possíveis imprevistos<br>
      <strong>FB11.</strong> Passageiro recebe alerta 15 minutos antes do horário de saída planejado
    </td>
  </tr>
  <tr>
    <td><strong>Fluxos alternativos</strong></td>
    <td>
      <strong>FA01 - Inserir paradas intermediárias:</strong><br>
      1. Passageiro informa parada ou local intermediário<br>
      2. Sistema recalcula rota<br>
      3. Exibe novo trajeto com parada incluída<br><br>
      
      <strong>FA02 - Escolher rota alternativa:</strong><br>
      1. Passageiro visualiza mais de uma opção de rota<br>
      2. Seleciona alternativa com menos baldeações<br>
      3. Sistema salva nova rota como principal<br><br>
      
      <strong>FA03 - Editar planejamento:</strong><br>
      1. Passageiro acessa lista de viagens planejadas<br>
      2. Seleciona viagem futura<br>
      3. Edita horário, destino ou preferências<br>
      4. Sistema atualiza dados e alerta agendado
    </td>
  </tr>
  <tr>
    <td><strong>Fluxos de exceção</strong></td>
    <td>
      <strong>FE01 - Falha de conexão:</strong><br>
      1. Sistema perde conexão durante o planejamento<br>
      2. Exibe "Falha ao carregar rotas. Tente novamente"<br>
      3. Mantém informações já digitadas para não precisar recomeçar<br><br>
      
      <strong>FE02 - Nenhuma rota encontrada:</strong><br>
      1. Sistema não encontra rotas para o horário informado<br>
      2. Exibe mensagem: "Nenhuma rota disponível nesse horário"<br>
      3. Sugere horários alternativos<br><br>
      
      <strong>FE03 - GPS desabilitado:</strong><br>
      1. Passageiro tenta usar localização atual<br>
      2. Sistema exibe "Ative o GPS para detectar sua localização"<br>
      3. Usuário pode continuar manualmente<br><br>
      
      <strong>FE04 - Conflito de horário:</strong><br>
      1. Passageiro agenda duas viagens para horários sobrepostos<br>
      2. Sistema alerta sobre conflito<br>
      3. Passageiro decide qual manter ou edita uma delas
    </td>
  </tr>
  <tr>
    <td><strong>Data da criação</strong></td>
    <td>12/10/2025</td>
  </tr>
  <tr>
    <td><strong>Rastreabilidade</strong></td>
    <td><strong>ENT12</strong>: O sistema deve permitir que o usuário planeje viagens com antecedência<br><strong>BRS07</strong>: Planejamento inteligente de rotas com base nas preferências do usuário</td>
  </tr>
</table>

<small style="color:blue;">Autoria: João Gabriel, 2025</small>

</div>

---

### Tabela 11 - UC10: Análise preditiva de horários de ônibus com IA (Requisito não implementado)

A Tabela 11 apresenta a especificação detalhada do caso de uso UC10, que tem como objetivo disponibilizar uma aba de notícias relacionada ao transporte público, integrando informações de fontes externas, como portais de notícias. Essa funcionalidade visa manter os usuários informados sobre ocorrências, mudanças e melhorias no sistema de transporte, contribuindo para uma comunicação mais transparente e eficiente.

<div align="center">

<p><strong>Tabela 11</strong> - UC10: Análise preditiva de horários de ônibus com IA</p>

<table>
  <tr>
    <th>Campo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td><strong>Atores</strong></td>
    <td>Passageiro</td>
  </tr>
  <tr>
    <td><strong>Descrição do Caso de Uso</strong></td>
    <td>Permite ao passageiro visualizar previsões mais precisas sobre horários de chegada e partida de ônibus, considerando fatores dinâmicos como trânsito, histórico de atrasos e condições climáticas.</td>
  </tr>
  <tr>
    <td><strong>Pré-Condições</strong></td>
    <td>- Passageiro autenticado no sistema<br>- GPS habilitado ou ponto de embarque informado<br>- Conexão com internet ativa<br>- Algoritmo de IA operacional com base em dados históricos e em tempo real</td>
  </tr>
  <tr>
    <td><strong>Pós-condições</strong></td>
    <td>- Passageiro recebe previsão de horário atualizada em tempo real<br>- Sistema ajusta alertas automáticos conforme variações no horário estimado<br>- Melhor tomada de decisão pelo passageiro</td>
  </tr>
  <tr>
    <td><strong>Fluxo básico</strong></td>
    <td>
      <strong>FB01.</strong> Passageiro acessa aba "Previsões de Horário"<br>
      <strong>FB02.</strong> Sistema detecta ponto de embarque atual ou selecionado<br>
      <strong>FB03.</strong> Sistema coleta dados históricos da linha e dados em tempo real (GPS do ônibus, trânsito, clima)<br>
      <strong>FB04.</strong> IA processa e calcula tempo estimado de chegada com precisão aumentada<br>
      <strong>FB05.</strong> Sistema exibe horário previsto de chegada e partida com status de confiança (ex: 92%)<br>
      <strong>FB06.</strong> Passageiro decide aguardar ou buscar rota alternativa<br>
      <strong>FB07.</strong> Sistema atualiza previsão automaticamente a cada intervalo configurado (ex: 30s)<br>
      <strong>FB08.</strong> Passageiro recebe notificação caso a previsão mude significativamente<br>
      <strong>FB09.</strong> Sistema armazena dados para otimizar previsões futuras
    </td>
  </tr>
  <tr>
    <td><strong>Fluxos alternativos</strong></td>
    <td>
      <strong>FA01 - Selecionar linha manualmente:</strong><br>
      1. Passageiro opta por digitar linha<br>
      2. Sistema busca dados históricos da linha informada<br>
      3. Exibe previsão personalizada<br><br>
      
      <strong>FA02 - Visualizar confiança da previsão:</strong><br>
      1. Passageiro clica no indicador de confiança<br>
      2. Sistema exibe fatores que influenciam no cálculo (ex: trânsito intenso, chuva)<br><br>
      
      <strong>FA03 - Favoritar linha:</strong><br>
      1. Passageiro marca linha como favorita<br>
      2. Sistema passa a exibir previsões prioritárias dessa linha
    </td>
  </tr>
  <tr>
    <td><strong>Fluxos de exceção</strong></td>
    <td>
      <strong>FE01 - Falha na IA:</strong><br>
      1. Algoritmo não consegue calcular previsão<br>
      2. Sistema exibe horário estimado padrão<br>
      3. Informa: "Previsão avançada temporariamente indisponível"<br><br>
      
      <strong>FE02 - Falha de conexão:</strong><br>
      1. Sistema perde conexão<br>
      2. Exibe "Sem conexão. Previsão não pode ser atualizada"<br>
      3. Mantém última previsão salva<br><br>
      
      <strong>FE03 - Dados insuficientes:</strong><br>
      1. Linha com poucos registros históricos<br>
      2. Sistema informa: "Previsão menos precisa — dados insuficientes"<br><br>
      
      <strong>FE04 - GPS desabilitado:</strong><br>
      1. Passageiro não informa localização e GPS está desligado<br>
      2. Sistema solicita manualmente ponto de embarque
    </td>
  </tr>
  <tr>
    <td><strong>Data da criação</strong></td>
    <td>12/10/2025</td>
  </tr>
  <tr>
    <td><strong>Rastreabilidade</strong></td>
    <td><strong>ENT13</strong>: O sistema deve exibir previsão inteligente de horários com IA<br><strong>BRS08</strong>: Previsão precisa de chegada de ônibus em tempo real</td>
  </tr>
</table>

<small style="color:blue;">Autoria: João Gabriel, 2025</small>

</div>

---

### Tabela 12 - UC11: Compartilhamento de Rotas entre Usuários (Requisito não implementado)

A Tabela 12 apresenta a especificação detalhada do caso de uso UC11, que permite ao passageiro compartilhar rotas e planejamentos de viagem com outros usuários do aplicativo, facilitando coordenação de deslocamentos e caronas.

<div align="center">

<p><strong>Tabela 12</strong> - UC11: Compartilhamento de Rotas entre Usuários</p>

<table>
  <tr>
    <th>Campo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td><strong>Atores</strong></td>
    <td>Passageiro</td>
  </tr>
  <tr>
    <td><strong>Descrição do Caso de Uso</strong></td>
    <td>Permite que um passageiro compartilhe uma rota planejada com contatos ou grupos dentro do aplicativo, incluindo horário estimado, pontos de encontro e instruções adicionais.</td>
  </tr>
  <tr>
    <td><strong>Pré-Condições</strong></td>
    <td>- Passageiro autenticado no sistema<br>- Contatos ou grupos adicionados ao perfil<br>- Conexão com internet ativa</td>
  </tr>
  <tr>
    <td><strong>Pós-condições</strong></td>
    <td>- Rota compartilhada enviada aos contatos selecionados<br>- Notificações de convite/recebimento registradas no sistema</td>
  </tr>
  <tr>
    <td><strong>Fluxo básico</strong></td>
    <td>
      <strong>FB01.</strong> Passageiro acessa a tela de planejamento de viagem<br>
      <strong>FB02.</strong> Insere origem, destino e horário desejado<br>
      <strong>FB03.</strong> Seleciona opção "Compartilhar" e escolhe contatos/grupo<br>
      <strong>FB04.</strong> (Opcional) Adiciona mensagem ou instruções adicionais<br>
      <strong>FB05.</strong> Sistema envia notificações para os contatos selecionados<br>
      <strong>FB06.</strong> Contatos recebem convite com detalhes da rota e opção de aceitar/recusar<br>
      <strong>FB07.</strong> Se aceitarem, sistema agenda lembrete compartilhado e atualiza status
    </td>
  </tr>
  <tr>
    <td><strong>Fluxos alternativos</strong></td>
    <td>
      <strong>FA01 - Compartilhar por link:</strong><br>
      1. Passageiro escolhe gerar link compartilhável<br>
      2. Sistema cria link com validade determinada<br>
      3. Passageiro copia/cola link em outra plataforma<br><br>

      <strong>FA02 - Enviar apenas horário:</strong><br>
      1. Passageiro opta por enviar apenas lembrete de horário<br>
      2. Sistema envia notificação com horário e efeito de lembrete
    </td>
  </tr>
  <tr>
    <td><strong>Fluxos de exceção</strong></td>
    <td>
      <strong>FE01 - Contato não encontrado:</strong><br>
      1. Passageiro seleciona contato removido ou inexistente<br>
      2. Sistema exibe "Contato não encontrado" e remove da seleção<br><br>

      <strong>FE02 - Falha ao enviar notificação:</strong><br>
      1. Sistema detecta erro ao notificar contato<br>
      2. Exibe mensagem "Falha ao enviar convite. Tente novamente"<br>
      3. Sistema registra tentativa para reenvio automático
    </td>
  </tr>
  <tr>
    <td><strong>Data da criação</strong></td>
    <td>12/10/2025</td>
  </tr>
  <tr>
    <td><strong>Rastreabilidade</strong></td>
    <td><strong>ENT14</strong>: Compartilhamento de planejamento de viagens entre usuários</td>
  </tr>
</table>

<small style="color:blue;">Autoria: Daniel Nunes Duarte, 2025</small>

</div>

---

### Tabela 13 - UC12: Acessibilidade e Suporte a Usuários com Deficiência (Requisito não implementado)

A Tabela 13 apresenta a especificação detalhada do caso de uso UC12, que visa garantir que o aplicativo ofereça recursos de acessibilidade, como leitura por voz, contraste alto e navegação por teclado, além de suporte específico para usuários com deficiência.

<div align="center">

<p><strong>Tabela 13</strong> - UC12: Acessibilidade e Suporte a Usuários com Deficiência</p>

<table>
  <tr>
    <th>Campo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td><strong>Atores</strong></td>
    <td>Passageiro (usuário com necessidades de acessibilidade)</td>
  </tr>
  <tr>
    <td><strong>Descrição do Caso de Uso</strong></td>
    <td>Fornece funcionalidades de acessibilidade no aplicativo, incluindo leitor de tela, navegação simplificada, legendas em vídeos e suporte a configurações de contraste e tamanho de fonte.</td>
  </tr>
  <tr>
    <td><strong>Pré-Condições</strong></td>
    <td>- Passageiro autenticado no sistema (opcional para recursos públicos)<br>- Dispositivo compatível com recursos de acessibilidade<br>- Permissões necessárias concedidas (ex: uso de microfone para comandos de voz)</td>
  </tr>
  <tr>
    <td><strong>Pós-condições</strong></td>
    <td>- Preferências de acessibilidade salvas no perfil do usuário<br>- Interface adaptada conforme configuração escolhida</td>
  </tr>
  <tr>
    <td><strong>Fluxo básico</strong></td>
    <td>
      <strong>FB01.</strong> Passageiro acessa "Configurações de Acessibilidade" no app<br>
      <strong>FB02.</strong> Escolhe opções desejadas (leitor de tela, contraste alto, tamanho de fonte)<br>
      <strong>FB03.</strong> Sistema aplica preferências e exibe pré-visualização<br>
      <strong>FB04.</strong> Passageiro confirma alterações<br>
      <strong>FB05.</strong> Sistema salva preferências no perfil e ajusta UI em todas as telas
    </td>
  </tr>
  <tr>
    <td><strong>Fluxos alternativos</strong></td>
    <td>
      <strong>FA01 - Ativar comandos de voz:</strong><br>
      1. Passageiro ativa controle por voz nas configurações<br>
      2. Sistema solicita permissão de microfone e fornece tutorial<br>
      3. Usuário passa a navegar por comandos de voz básicos<br><br>

      <strong>FA02 - Modo somente texto:</strong><br>
      1. Passageiro ativa modo somente texto para leitores braille ou integração com dispositivos assistivos<br>
      2. Sistema reescreve interfaces para formato texto simplificado
    </td>
  </tr>
  <tr>
    <td><strong>Fluxos de exceção</strong></td>
    <td>
      <strong>FE01 - Permissão negada:</strong><br>
      1. Usuário nega acesso ao microfone ou recursos necessários<br>
      2. Sistema exibe instruções para habilitar permissões manualmente<br><br>

      <strong>FE02 - Recurso não suportado pelo dispositivo:</strong><br>
      1. Sistema detecta hardware/SDK incompatível<br>
      2. Exibe mensagem explicativa e oferece alternativas (ex: modo texto)
    </td>
  </tr>
  <tr>
    <td><strong>Data da criação</strong></td>
    <td>12/10/2025</td>
  </tr>
  <tr>
    <td><strong>Rastreabilidade</strong></td>
    <td><strong>BRS09</strong>: Requisitos de acessibilidade e conformidade com normas de usabilidade</td>
  </tr>
</table>

<small style="color:blue;">Autoria: Daniel Nunes Duarte, 2025</small>

</div>


## Responsáveis pela elaboração do artefato

| Nome            | Responsabilidade              |
|-----------------|-------------------------------|
| **Fernanda Vaz** | - Elaboração dos textos de Introdução, Metodologia <br> - Criação inicial do Diagrama de Casos de Uso UML <br> - Elaboração da [Tabela 1](#tabela-1-elementos-descricoes-e-representacoes-graficas-do-diagrama-de-casos-de-uso) <br> - Elaboração do Diagrama de Casos de Uso UML <br> - Elaboração e documentação dos casos de uso UC01 e UC02 |
| **Gabriel Maciel** | - Elaboração e documentação do Modelo de Tabela para Especificação de Casos de Uso <br> - Elaboração e documentação dos casos de uso UC03 e UC04 |
| **Cauã Nicolas** | - Elaboração e documentação dos casos de uso UC05 e UC06 |
| **João Ramos** | - Elaboração e documentação dos casos de uso UC07 e UC08 |
| **João Gabriel** | - Elaboração e documentação dos casos de uso UC09 e UC10 |
| **Daniel Nunes Duarte** | - Elaboração e documentação dos casos de uso UC11 e UC12 |

## Bibliografia
<a id="ref-Lucid"></a>
> LUCID SOFTWARE PORTUGUÊS. Tutorial de Caso de Uso UML. YouTube, 25 abr. 2019. Disponível em: https://www.youtube.com/watch?v=ab6eDdwS3rA. Acesso em: 8 out. 2025.

> MINISTÉRIO DA CIÊNCIA, TECNOLOGIA, INOVAÇÕES E COMUNICAÇÕES. *Especificação de Caso de Uso – Sigla do Projeto*. Brasília: MCTIC, Coordenação Geral de Sistemas, [s.d.]. Disponível em: <https://aprender3.unb.br/pluginfile.php/3210641/mod_resource/content/3/SiglaProjeto_EspecificacaoCasoUso.pdf>. Acesso em: 11 out. 2025.

## Referência bibliográfica

<a id="#ref-Lucid"></a>
> LUCID SOFTWARE PORTUGUÊS. Tutorial de Caso de Uso UML. YouTube, 25 abr. 2019. Disponível em: https://www.youtube.com/watch?v=ab6eDdwS3rA. Acesso em: 10 out. 2025.

> MINISTÉRIO DA CIÊNCIA, TECNOLOGIA, INOVAÇÕES E COMUNICAÇÕES. *Especificação de Caso de Uso – Sigla do Projeto*. Brasília: MCTIC, Coordenação Geral de Sistemas, [s.d.]. Disponível em: <https://aprender3.unb.br/pluginfile.php/3210641/mod_resource/content/3/SiglaProjeto_EspecificacaoCasoUso.pdf>. Acesso em: 11 out. 2025.


## Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Revisor |
|:---:|:---|:---|:---|:---|
| 1.0 | 08/10/2025 | Criação da estrutura inicial do documento. | Gabriel Maciel | Fernanda Vaz |
| 1.2 | 10/10/2025 | Criação inicial do caso de uso e adição de elementos individuais | Fernanda Vaz | Gabriel Maciel|
| 1.3 | 10/10/2025 | Elaboração e documentação do Modelo da Tabela de Especificação de Casos de Uso | Gabriel Maciel | Fernanda Vaz |
| 1.3.1 | 11/10/2025 | Elaboração e documentação dos casos de uso UC03 e UC04 | Gabriel Maciel | Fernanda Vaz |
| 1.3.2 | 12/10/2025 | Elaboração e documentação dos casos de uso UC05 e UC06 | Cauã Nicolas | Gabriel Maciel |
| 1.3.3 | 12/11/2025 | Adição dos casos de uso UC07 e UC08 | Gabriel Maciel, João Ramos | Cauã Nicolas |
| 1.3.3 | 12/11/2025 | Adição dos casos de uso UC09 e UC10 | João Gabriel | Cauã Nicolas |
| 1.4 | 12/10/2025 | Adição dos casos de uso UC11 e UC12 | Daniel Nunes Duarte | ----- |

## Agradecimentos
>>Agradecemos o suporte da ferramenta de Inteligência Artificial Generativa Google Gemini no desenvolvimento deste trabalho. Em conformidade com o Código de Conduta da Sociedade Brasileira de Computação (SBC), declaramos que a ferramenta foi utilizada como auxílio na revisão gramatical e estilística do texto, na sugestão de estrutura para seções específicas do artigo, bem como na formatação de tabelas e na descrição de figuras. Ressaltamos que os autores assumem total responsabilidade por todo o conteúdo apresentado, incluindo sua originalidade e precisão. A ferramenta não figura como autora desta publicação.