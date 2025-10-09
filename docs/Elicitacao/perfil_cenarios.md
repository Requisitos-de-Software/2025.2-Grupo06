# Cenários

Cenários são uma técnica fundamental no desenvolvimento de sistemas, funcionando como narrativas que descrevem o uso de um sistema a partir da perspectiva do usuário. Essencialmente, são histórias sobre pessoas realizando uma atividade, detalhando a interação entre os atores (usuários ou outros sistemas) e o sistema em desenvolvimento.

**Cenário:** Chegando a tempo no trabalho

**Ator:** Ana, uma estudante universitária que usa o ônibus diariamente para ir ao estágio.

**Situação:** Ana está em casa, terminando de se arrumar. Ela precisa sair no momento certo para não esperar muito tempo no ponto de ônibus, mas também não pode se atrasar para o estágio. Ela decide usar o aplicativo "DF no Posto" para verificar a localização do seu ônibus em tempo real.

---
## Objetivo

- **Por que a Ana quer alcançar esse objetivo?**  
  Para otimizar seu tempo, evitar esperas desnecessárias no ponto de ônibus (ficando exposta ao sol ou à chuva) e garantir que não se atrasará para o estágio.

- **Quais as precondições?**  
  Ana precisa ter o aplicativo instalado em seu celular, conexão com a internet, bateria no celular e saber qual linha de ônibus ela precisa pegar.

- **De quais informações ela precisa?**  
  Ela precisa saber o número da sua linha de ônibus e a localização do ponto onde ela embarcará. O aplicativo, por sua vez, precisa fornecer a localização em tempo real do veículo.  
  **Que outros objetivos estão relacionados?**  
  A necessidade de validar o saldo no seu cartão de transporte e a gestão de seu tempo pela manhã.

---

## Ambiente

- **Em que situação o cenário ocorre?**  
  Ocorre pela manhã, na casa de Ana, antes de sair em direção ao estágio.

- **Que dispositivos e recursos estão disponíveis?**  
  Um smartphone com o aplicativo "DF no Ponto" instalado e acesso à internet.

- **Quais tecnologias são utilizadas?**  
  GPS (tanto no celular de Ana quanto no ônibus), internet móvel/Wi-Fi e a plataforma do aplicativo.

---

## Ator(es)

- **Quem pode alcançar o objetivo?**  
  Qualquer usuário de transporte público do DF que tenha um smartphone e acesso ao aplicativo.

- **Quais características de Ana a auxiliam ou atrapalham?**  
  Auxiliam: familiaridade com aplicativos de celular.  
  Atrapalham: pressa ou ansiedade por conta do horário, o que pode levá-la a interpretar uma informação de forma errada.

- **De quem depende o alcance do objetivo?**  
  Depende da precisão dos dados de GPS fornecidos pelo ônibus, da estabilidade do servidor do aplicativo e da sua própria conexão com a internet.

---

## Planejamento

- **Como a Ana alcançaria o objetivo atualmente (sem o app)?**  
  Ela teria que confiar em horários fixos (muitas vezes imprecisos) ou simplesmente ir para o ponto e esperar, sem saber quanto tempo levaria.

- **Quais as estratégias alternativas?**  
  Ela poderia pedir um carro por aplicativo, o que seria mais caro.  
  Dentro do app, ela pode buscar pela linha ou pelo ponto de ônibus mais próximo.  
  **Que decisões ela precisa tomar?**  
  Com base na localização do ônibus mostrada no mapa, ela precisa decidir se pode esperar mais um pouco em casa ou se precisa sair imediatamente.

---

## Ação

- **Que ações ela realiza?**  
  1. Abrir o aplicativo.  
  2. Buscar pela sua linha de ônibus na barra de pesquisa.  
  3. Selecionar a linha correta.  
  4. Visualizar no mapa onde os ônibus daquela linha estão.  
  5. Clicar no ícone do ônibus mais próximo para ver a previsão de chegada no seu ponto.

- **Quais problemas podem surgir?**  
  O aplicativo pode não encontrar a linha.  
  O mapa pode demorar a carregar.  
  A localização do GPS do ônibus pode estar desatualizada ("ônibus fantasma").  
  A previsão de chegada pode ser imprecisa.

- **Quais erros podem ser cometidos?**  
  Ana pode digitar o número da linha errado ou olhar a previsão para o sentido contrário da sua rota.

---

## Evento

- **Quais eventos disparam a necessidade de alcançar o objetivo?**  
  A aproximação do horário de sair para o estágio ou Universidade.

- **Quais eventos são disparados pela conclusão?**  
  A ação de Ana de sair de casa no momento calculado e pegar o ônibus.

---

## Avaliação

- **Como a Ana sabe se a ação foi concluída com sucesso?**  
  Ela tem sucesso quando o aplicativo exibe o mapa com a localização atualizada do ônibus e uma previsão de tempo de chegada confiável.

- **Qual é o resultado do alcance do objetivo?**  
  O resultado final é Ana chegando ao ponto de ônibus com pouca espera e embarcando no ônibus desejado, a caminho do seu estágio sem atrasos.

---

### Referências Bibliográficas
<a id="APP1" href="#anchor_APP1">1.</a> CENÁRIOS. In: RETRAINING - Guia facetado de Técnicas de Elicitação de Requisitos. Disponível em: [https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-cenarios](). Acesso em: 30 de set. de 2025.

<a id="APP2" href="#anchor_APP2">2.</a> BARBOSA, Simone Diniz Junqueira et al. Interação Humano-Computador e Experiência do usuário. Disponível em:[https://aprender3.unb.br/pluginfile.php/3210628/mod_resource/content/2/ihc-ux-%20Personas.pdf]() . Cap. 8.3 - Cenários Pág 158 à 163. Acesso em: 30 de set. de 2025.

---

### Responsáveis pela Elaboração

| Nome            | Responsabilidade              |
|-----------------|-------------------------------|
| Daniel Nunes    | Elaboração dos cenários |

### Histõrico de Versões

| **Versão** | **Data**     | **Descrição**             | **Autor(es)**           | **Revisor(es)**         |
|------------|--------------|----------------------------|--------------------------|--------------------------|
| 1.0        | 30/09/2025   | Cenários  | [Daniel Nunes Duarte](https://github.com/DanNunes777)  | [Fernanda Vaz](https://github.com/Fernandavazgit1)   |
| 2.0   | 08/10/2025 | Adiciona tabela de identificação dos responsáveis pela elaboração do documento  | Gabriel Maciel  | Daniel Nunes |
