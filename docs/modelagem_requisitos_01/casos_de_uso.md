## Introdução
O objetivo do diagrama de caso de uso em UML é demonstrar as diferentes maneiras que o usuário pode interagir com um sistema. Um diagrama de caso de uso adequado dá uma visão geral do relacionamento entre casos de uso, atores e sistemas. O caso de uso é representado por uma forma oval rotulada. Bonecos palito representam os atores no processo, e a participação do ator no sistema é modelada com uma linha entre o ator e o caso de uso. Para representar o limite do sistema, desenhe uma caixa em torno do próprio caso de uso. [(Lucidchart, 2025)](#ref-Lucid).


## Metodologia
Segundo o vídeo do [(Lucidchart, 2025)](#ref-Lucid), esses são todos os elementos que podem conter em um caso de uso:

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
<p style="text-align: center; font-size: 0.85em; font-style: italic; color: #000000ff;">
Tabela 1 – Elementos, descrições e representações gráficas do Diagrama de Casos de Uso.  
<span style="color:blue;">Autoria: Fernanda Vaz, 2025.</span>
</p>

---
## Diagrama de Casos de Uso
<p style="text-align: center; font-size: 0.85em; font-style: italic; color: #000000ff;">Figura 1: Casos de uso do app DF no Ponto  
<span style="color:blue;">Autoria: Fernanda Vaz, 2025.</span>
</p>

<div style="width: 640px; height: 480px; margin: 10px; position: relative;"><iframe allowfullscreen frameborder="0" style="width:640px; height:480px" src="https://lucid.app/documents/embedded/080b2523-5076-4f95-b29a-9b0eda02288f" id="LNtYFI8byYwG"></iframe></div>


---

# Especificação de Casos de Uso

### Template Tabela para Especificação de Casos de Uso

### UCXX - Nome do caso de uso

| **Campo**             | **Descrição** |
|----------------------|----------------|
| **Atores**           |                |
| **Frequência de uso**|                |
| **Requisitos**       |                |
| **Pré-Condições**    |                |
| **Condição de entrada** |             |
| **Fluxo principal**  |                |
| **Fluxos alternativos** |             |
| **Fluxos de exceção**|                |
| **Pós-condições**    |                |
| **Data da criação**  |                |
| **Rastreabilidade**  |                |

---

### UC01 - Avaliação de Linhas de Ônibus (Requisito não implementado)
<span style="color:blue;">Autoria: Fernanda Vaz, 2025.</span>

| **Campo**             | **Descrição** |
|----------------------|----------------|
| **Atores**           |  passageiro |
| **Frequência de uso**| Média - utilizado após viagens realizadas pelos usuários |
| **Requisitos**       | RF-01: Sistema deve permitir avaliação de linhas de ônibus
| **Pré-Condições**    | -passageiro autenticado no sistema<br>- Linha de ônibus disponível para avaliação |
| **Condição de entrada** | passageiro acessa a funcionalidade de avaliação de linhas  pelo histórico de linhas |
| **Fluxo principal**  | 1. passageiro seleciona uma linha de ônibus para avaliar<br>2. Sistema exibe formulário de avaliação<br>3. passageiro atribui nota de 1 a 5 estrelas<br>4. passageiro pode adicionar comentário opcional <br>5. passageiro confirma avaliação<br>6. Sistema valida os dados inseridos<br>7. Sistema registra avaliação no banco de dados<br>8. Sistema atualiza média de avaliações da linha<br>9. Sistema exibe mensagem de confirmação<br>10. Sistema retorna à tela anterior |
| **Fluxos alternativos** | **FA01 - Editar avaliação existente:**<br>1. passageiro acessa suas avaliações anteriores<br>2. Seleciona avaliação para editar<br>3. Sistema carrega dados da avaliação<br>4. passageiro modifica nota e/ou comentário<br>5. Prossegue do passo 5 do fluxo principal<br><br>**FA02 - Visualizar avaliações de outros usuários:**<br>1.  passageiro acessa detalhes da linha<br>2. Sistema exibe média de avaliações e lista de comentários<br>3. passageiro pode filtrar por data ou nota<br>4. Sistema ordena avaliações conforme filtro selecionado<br><br>**FA03 - Cancelar avaliação:**<br>1. passageiro clica em "Cancelar" durante preenchimento<br>2. Sistema exibe confirmação "Descartar avaliação?"<br>3. passageiro confirma<br>4. Sistema descarta dados e retorna à tela anterior |
| **Fluxos de exceção**| **FE01 - Falha na conexão de internet:**<br>1. Sistema detecta ausência de conectividade ao tentar salvar<br>2. Exibe mensagem "Não foi possível salvar. Verifique sua conexão"<br>3. Sistema salva avaliação localmente<br>4. Reenvia automaticamente quando conexão for restabelecida<br><br>**FE02 - Comentário com conteúdo inadequado:**<br>1. Sistema detecta palavras ofensivas <br>2. Exibe mensagem "Comentário contém conteúdo inadequado"<br>3. Usuário deve revisar e modificar o comentário<br><br>**FE03 - Erro ao salvar avaliação:**<br>1. Sistema tenta salvar mas ocorre erro no servidor<br>2. Exibe mensagem "Erro ao processar avaliação. Tente novamente"<br>3. Mantém dados preenchidos para nova tentativa<br><br>**FE04 - passageiro já avaliou recentemente:**<br>1. Sistema detecta avaliação duplicada no mesmo dia<br>2. Oferece opção de editar avaliação existente<br>3. Se usuário confirmar, redireciona para FA01 |
| **Pós-condições**    | - Avaliação registrada no banco de dados<br>- Média de avaliações da linha atualizada<br>- Histórico de avaliações do usuário atualizado<br>- Estatísticas da linha recalculadas |
| **Data da criação**  | 10/10/2025 |
| **Rastreabilidade**  | Relacionado com: <br>Consulta de Horários e Rotas<br> Notificações de Chegada<br> Avaliação de linhas<br> Usabilidade da interface |

### UC02- Notificações de Chegada de Ônibus (Requisito não implementado)
<span style="color:blue;">Autoria: Fernanda Vaz, 2025.</span>

| **Campo**             | **Descrição** |
|----------------------|----------------|
| **Atores**           | Passageiro e Serviço de GPS |
| **Frequência de uso**| Alta - utilizado diariamente por passageiros frequentes do transporte público |
| **Requisitos**       | Requisito fucional: Sistema deve enviar notificações de chegada de ônibus<br>Requisito não fucional: Notificações devem ser enviadas em tempo real com latência máxima de 30 segundos<br> |
| **Pré-Condições**    | - Passageiro autenticado no sistema<br>- GPS do dispositivo habilitado<br>- Permissões de notificação concedidas ao aplicativo<br>- Linha de ônibus com rastreamento disponível |
| **Condição de entrada** | Passageiro ativa notificação para uma linha específica de ônibus |
| **Fluxo principal**  | 1. Passageiro seleciona uma linha de ônibus no aplicativo<br>2. Sistema exibe informações da linha e botão "Ativar notificações"<br>3. Passageiro clica em "Ativar notificações"<br>4. Sistema solicita confirmação de ponto de referência (parada atual)<br>5. Passageiro confirma ou seleciona parada desejada<br>6. Sistema inicia monitoramento da localização do ônibus em tempo real<br>7. Sistema detecta que o ônibus está a 1km da parada<br>8. Sistema envia primeira notificação: "Seu ônibus está chegando em aproximadamente 5 minutos"<br>9. Sistema continua monitorando<br>10. Quando ônibus está a 500m, sistema envia notificação: "Seu ônibus está chegando em 2 minutos"<br>11. Sistema mantém notificação ativa até chegada do ônibus<br>12. Após chegada, sistema desativa notificação automaticamente |
| **Fluxos alternativos** | **FA01 - Desativar notificações:**<br>1. Passageiro acessa notificações ativas<br>2. Seleciona linha para desativar<br>3. Sistema para monitoramento imediatamente<br>4. Exibe confirmação "Notificações desativadas"<br><br>**FA02 - Configurar múltiplas linhas:**<br>1. Passageiro ativa notificações para mais de uma linha<br>2. Sistema monitora todas as linhas simultaneamente<br>3. Envia notificações individuais para cada linha<br><br>**FA03 - Ajustar distância de notificação:**<br>1. Passageiro acessa configurações de notificações<br>2. Modifica raio de alerta (500m, 1km, 2km)<br>3. Sistema salva preferência<br>4. Aplica nova configuração ao monitoramento<br><br>**FA04 - Notificação de atraso:**<br>1. Sistema detecta atraso significativo do ônibus<br>2. Envia notificação: "Seu ônibus está com atraso de X minutos"<br>3. Atualiza tempo estimado de chegada |
| **Fluxos de exceção**| **FE01 - Falha na conexão de internet:**<br>1. Sistema detecta perda de conectividade<br>2. Exibe mensagem "Monitoramento pausado. Verifique sua conexão"<br>3. Salva estado atual do monitoramento<br>4. Retoma automaticamente quando conexão for restabelecida<br><br>**FE02 - GPS desabilitado:**<br>1. Sistema detecta que GPS está desligado<br>2. Envia notificação de alerta<br>3. Exibe tela: "Ative o GPS para receber notificações"<br>4. Oferece botão para acessar configurações do dispositivo<br><br>**FE03 - Ônibus não detectado:**<br>1. Sistema não consegue localizar ônibus por mais de 15 minutos<br>2. Envia notificação: "Não foi possível rastrear o ônibus"<br>3. Oferece opção de desativar notificação ou aguardar<br>4. Continua tentando se passageiro optar por aguardar<br><br>**FE04 - Permissão de notificação negada:**<br>1. Sistema detecta falta de permissão ao tentar enviar notificação<br>2. Exibe alerta na tela do app<br>3. Redireciona passageiro para configurações do sistema<br>4. Aguarda concessão de permissão<br><br>**FE05 - Bateria baixa:**<br>1. Sistema detecta nível crítico de bateria (<10%)<br>2. Reduz frequência de atualização de localização<br>3. Notifica passageiro sobre modo de economia ativado |
| **Pós-condições**    | - Notificação de chegada enviada com sucesso<br>- Log de notificação registrado no sistema<br>- Status de monitoramento atualizado<br>- Estatísticas de uso do serviço atualizadas |
| **Data da criação**  | 10/10/2025 |
| **Rastreabilidade**  | Relacionado com:<br> Consulta de Horários e Rotas<br>Avaliação de Linhas<br> Performance de notificações em tempo real<br> Disponibilidade do sistema<br>Precisão de geolocalização |

### UC03 - Rastreamento de Múltiplas Linhas (Requisito Não Implementado)

| **Campo**             | **Descrição** |
|----------------------|----------------|
| **Atores**           | Passageiro e Serviço de GPS (Ônibus e Passageiro) |
| **Frequência de uso**| Média - Utilizada por passageiros que precisam pegar ônibus de múltiplas linhas para chegar ao seu destino |
| **Requisitos**       | |
| **Pré-Condições**    |                |
| **Condição de entrada** |             |
| **Fluxo principal**  |                |
| **Fluxos alternativos** |             |
| **Fluxos de exceção**|                |
| **Pós-condições**    |                |
| **Data da criação**  | 11/10/25 |
| **Rastreabilidade**  |                |


## Bibliografia
<a id="ref-Lucid"></a>
>LUCID SOFTWARE PORTUGUÊS. Tutorial de Caso de Uso UML. YouTube, 25 abr. 2019. Disponível em: https://www.youtube.com/watch?v=ab6eDdwS3rA. Acesso em: 8 out. 2025.

## Referência bibliográfica

<a id="#ref-Lucid"></a>
> LUCID SOFTWARE PORTUGUÊS. Tutorial de Caso de Uso UML. YouTube, 25 abr. 2019. Disponível em: https://www.youtube.com/watch?v=ab6eDdwS3rA. Acesso em: 10 out. 2025.

## Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Revisor |
|:---:|:---|:---|:---|:---|
| 1.0 | 08/10/2025 | Criação da estrutura inicial do documento. | Gabriel Maciel | Fernanda Vaz |
| 1.2 | 10/10/2025 | Criação inicial do caso de uso e adição de elementos individuais | Fernanda Vaz | Gabriel Maciel|
