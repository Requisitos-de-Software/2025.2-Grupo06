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
    </tr>
    <tr>
      <td><b>Ator Primário</b></td>
      <td>É quem inicia a interação com o sistema (ex: o cliente que abre o aplicativo bancário). Fica posicionado à esquerda do sistema.</td>
      <td style="text-align: center;">
        <img src="https://i.ibb.co/7dbbfb20/image.png" alt="Ator primário - figura de palito" width="90">
      </td>
    </tr>
    <tr>
      <td><b>Ator Secundário</b></td>
      <td>Atua em resposta ao ator primário, reagindo a uma ação (ex: o banco que responde às solicitações do cliente). Fica à direita do sistema.</td>
      <td style="text-align: center;">
        <img src="https://i.ibb.co/7dbbfb20/image.png" alt="Ator secundário - figura de palito" width="90">
      </td>
    </tr>
    <tr>
      <td><b>Caso de Uso</b></td>
      <td>Representa uma ação ou funcionalidade do sistema, escrita no infinitivo com verbo (ex: <i>Fazer login</i>, <i>Consultar saldo</i>, <i>Fazer pagamento</i>). É mostrado como uma elipse.</td>
      <td style="text-align: center;">
        <img src="https://i.ibb.co/kVXrhzk9/image.png" alt="Elipse representando caso de uso" width="90">
      </td>
    </tr>
    <tr>
      <td><b>Associação</b></td>
      <td>Linha sólida entre ator e caso de uso, indicando interação direta (ex: cliente → fazer login).</td>
      <td style="text-align: center;">
        <img src="https://i.ibb.co/Y44DCSFB/image.png" alt="Associação - linha sólida entre ator e caso de uso" width="90">
      </td>
    </tr>
    <tr>
      <td><b>Relacionamento de Inclusão (<code>&lt;&lt;include&gt;&gt;</code>)</b></td>
      <td>Indica que um caso de uso base <b>sempre</b> executa outro caso de uso incluído como parte do seu fluxo (ex: <i>Fazer login</i> inclui <i>Verificar senha</i>). Representado por linha tracejada com seta apontando para o caso incluído.</td>
      <td style="text-align: center;">
        <img src="https://i.ibb.co/Y44DCSFB/image.png" alt="Relação de inclusão" width="90">
      </td>
    </tr>
    <tr>
      <td><b>Relacionamento de Extensão (<code>&lt;&lt;extend&gt;&gt;</code>)</b></td>
      <td>Indica que um caso de uso estendido <b>pode</b> ocorrer sob certas condições (ex: <i>Exibir erro de login</i> estende <i>Fazer login</i>). Linha tracejada com seta apontando para o caso base.</td>
      <td style="text-align: center;">
        <img src="https://i.ibb.co/Y44DCSFB/image.png" alt="Relação de extensão" width="90">
      </td>
    </tr>
    <tr>
      <td><b>Generalização / Herança</b></td>
      <td>Representa especialização entre casos de uso ou atores (ex: <i>Pagar da conta corrente</i> e <i>Pagar da conta poupança</i> herdam de <i>Fazer pagamento</i>). Linha sólida com seta do específico para o geral.</td>
      <td style="text-align: center;">
        <img src="https://i.ibb.co/Y44DCSFB/image.png" alt="Generalização - seta sólida" width="90">
      </td>
    </tr>
    <tr>
      <td><b>Ponto de Extensão</b></td>
      <td>Indica locais dentro de um caso de uso onde comportamentos adicionais podem ser inseridos (ex: no caso <i>Configurar perfil</i>, pontos de extensão permitem acessar <i>Ajuda de perfil</i> ou <i>Informações de privacidade</i>).</td>
      <td style="text-align: center;">
        <img src="https://i.ibb.co/kVXrhzk9/image.png" alt="Elipse com ponto de extensão" width="90">
      </td>

  </tbody>
</table>

<p style="text-align: center; font-size: 0.85em; font-style: italic; color: #030000ff;">
Tabela 1 – Elementos, descrições e representações gráficas do Diagrama de Casos de Uso.  
<span style="color:blue;">Autoria: Fernanda Vaz, 2025.</span>
</p>

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


## Bibliografia
<a id="ref-Lucid"></a>
>LUCID SOFTWARE PORTUGUÊS. Tutorial de Caso de Uso UML. YouTube, 25 abr. 2019. Disponível em: https://www.youtube.com/watch?v=ab6eDdwS3rA. Acesso em: 8 out. 2025.

## Agradecimentos
>Os autores agradecem o auxílio da ferramenta de Inteligência Artificial Generativa (Google Gemini) no processo de revisão gramatical e estilística deste artigo. A tecnologia foi utilizada para aprimorar a clareza, a concisão e a legibilidade do texto, sendo que toda a responsabilidade pelo conteúdo final, precisão técnica e argumentação permanece integralmente dos autores.

## Histórico de Versão

| Versão | Data       | Descrição                                   | Autor(es)     | Revisor         |
|:------:|:-----------|:--------------------------------------------|:--------------|:----------------|
|  1.0   | 08/10/2025 | Criação da estrutura inicial do documento. | GABRIEL MACIEL| FERNANDA VAZ |
|        |            |                                             |               |                 |
|        |            |                                             |               |                 |