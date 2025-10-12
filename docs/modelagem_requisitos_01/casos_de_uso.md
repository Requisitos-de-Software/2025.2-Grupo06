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

A Tabela 5 apresenta a especificação detalhada do caso de uso UC03, que permite aos passageiros visualizar simultaneamente múltiplas linhas de ônibus no mapa e obter informações detalhadas sobre cada uma delas.

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
| **Rastreabilidade**         | ENT07: O aplicativo permite integração com o cartão de transporte, incluindo saldo e recarga.|

A Tabela 7 apresenta a especificação detalhada do caso de uso UC05, que permite aos passageiros vizualizar as viagens realizadas, incluindo horários, rotas, meio de transporte e duração.


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


## Responsáveis pela elaboração do artefato

| Nome            | Responsabilidade              |
|-----------------|-------------------------------|
| **Fernanda Vaz** | - Elaboração dos textos de Introdução, Metodologia <br> - Criação inicial do Diagrama de Casos de Uso UML <br> - Elaboração da [Tabela 1](#tabela-1-elementos-descricoes-e-representacoes-graficas-do-diagrama-de-casos-de-uso) <br> - Elaboração do Diagrama de Casos de Uso UML <br> - Elaboração e documentação dos casos de uso UC01 e UC02| 
| **Gabriel Maciel** | - Elaboração e documentação do Modelo de Tabela para Especificação de Casos de Uso <br> - Elaboração e documentação dos casos de uso UC03 e UC04 |
| **Cauã Nicolas** | - Elaboração e documentação dos casos de uso UC05 e UC06 |

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

## Agradecimentos
>>Agradecemos o suporte da ferramenta de Inteligência Artificial Generativa Google Gemini no desenvolvimento deste trabalho. Em conformidade com o Código de Conduta da Sociedade Brasileira de Computação (SBC), declaramos que a ferramenta foi utilizada como auxílio na revisão gramatical e estilística do texto, na sugestão de estrutura para seções específicas do artigo, bem como na formatação de tabelas e na descrição de figuras. Ressaltamos que os autores assumem total responsabilidade por todo o conteúdo apresentado, incluindo sua originalidade e precisão. A ferramenta não figura como autora desta publicação.