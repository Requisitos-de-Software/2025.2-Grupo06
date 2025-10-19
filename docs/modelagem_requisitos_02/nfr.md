## Introdução
O NFR Framework (Framework de Requisitos Não Funcionais) é uma abordagem utilizada para representar e analisar RNF. Segundo Reinaldo Antônio <sup>[1](#ref-1)</sup>, seu objetivo é auxiliar desenvolvedores a implementar soluções personalizadas. Essa abordagem considera as características específicas do sistema — como requisitos funcionais, não-funcionais, prioridades e carga de trabalho — para determinar as alternativas de desenvolvimento mais adequadas (CHUNG et al., 2000).

---

###### Print da Referência 
<p align="center">
<a href="https://ibb.co/HLCpRH1X"><img src="https://i.ibb.co/qLCFhrXx/image.png" alt="image" border="0"></a>
 <b>Figura 01 – </b>NFR Framework
 </p>

## Softgoal Interdependency Graph
Segundo  Reinaldo Antônio <sup>[1](#ref-1)</sup> o "Softgoal Interdependency Graph" (SIG) é um gráfico que registra as análises do desenvolvedor sobre os softgoals (objetivos não-funcionais) e mostra como eles dependem uns dos outros. Essencialmente, os SIGs armazenam todo o histórico das decisões de desenvolvimento e a lógica do projeto de forma visual e resumida.


#### Tipos de Softgoal

Existem três tipos de softgoals: Softgoals NFR, Softgoals de Operacionalização e Softgoals
de Afirmação. Estes são descritos a seguir:

- **Softgoals NFR:** representam os Requisitos Não- Funcionais e podem estar interrelacionados, organizados em catálogos e apresentados de forma hierárquica no desenvolvimento do projeto (CHUNG et al., 2000).

- **Softgoals de Operacionalização:** representam soluções de implementação para
satisfazer softgoals NFR ou outros softgoals de operacionalização. Essas soluções
incluem operações, processos, representações de dados, estruturações e restrições
no sistema alvo para atender às necessidades indicadas pelos softgoals NFR e de
operacionalização (CHUNG et al., 2000).


- **Softgoals de Afirmação:** permitem que as características do domínio (como prioridades e carga de trabalho) sejam consideradas e devidamente refletidas no processo
de tomada de decisão. Eles servem como justificativa para apoiar ou negar a forma
como os softgoals são priorizados, refinados e os componentes são selecionados. Os
softgoals de afirmação fornecem as razões para as decisões de desenvolvimento, facilitando a revisão, a justificativa e a mudança do sistema, bem como o aprimoramento
da rastreabilidade(CHUNG et al., 2000).

<p align="center">
  <a href="https://imgbb.com/">
    <img src="https://i.ibb.co/h1L3Knr7/image.png" alt="Diagrama do Sistema" width="400">
 </a>
  <br>
  <b>Figura 02 – </b>Tipos de Softgoal
</p>


####  Tipos de decomposições
As decomposições têm o objetivo de refinar softgoals para obter softgoals mais especializados e estes possam auxiliar na construção do projeto. Os quatro tipos de decomposições
utilizadas pelo NFR Framework são descritos a seguir.

- **Decomposição de Softgoal NFR:** refina ou subdivide um softgoal NFR em outros
específicos (apresentada na Figura 8-A). Isso pode ajudar a dividir grandes problemas em problemas menores e oferece um aspecto útil para lidar com ambiguidades
e prioridades.
- **Decomposição de Operacionalização:**  subdivide um softgoal de operacionalização em outros softgoals de operacionalização mais específicos (apresentada na
Figura 8-B). Operacionalizações são úteis para definir uma solução geral e refiná-la
em soluções mais específicas.

- **Decomposição de Afirmação (Claims):**  refina um softgoal de afirmação em
outros softgoals de afirmação (apresentada na Figura 8-C). Ela é importante para
apoiar ou negar justificativas específicas de projeto.
 - **Priorização:**A priorização é um tipo especial de decomposição, onde ocorre o
refinamento de um softgoal em outro softgoal com o mesmo tipo e tópicos, mas com
uma prioridade associada. (apresentada na Figura 8-D)

<p align="center">
  <a href="https://imgbb.com/">
    <img src="https://i.ibb.co/KjWPS9NR/image.png" alt="Diagrama do Sistema" width="600"> 
 </a>
  <br>
  <b>Figura 03 – </b> Tipos de decomposições
</p>


#### Contribuições

O **NFR Framework** permite a utilização de diversos tipos de contribuições que descrevem como a satisfação (ou não) de um *softgoal* descendente afeta a satisfação de um *softgoal* ascendente.

- **AND**  
  Determina que, se **todos os softgoals descendentes** forem satisfeitos, os **softgoals ascendentes** também serão satisfeitos.

- **OR**  
  Determina que, se **algum softgoal descendente** for satisfeito, o **softgoal ascendente** será satisfeito.

- **MAKE (++)**  
  Fornece uma contribuição **suficientemente positiva** entre um *softgoal* descendente e um ascendente, concebida no nível mais alto de satisfação.  
  Se o *softgoal* descendente for satisfeito, o *softgoal* pai **também será satisfeito**.

- **BREAK (--)**  
  Fornece uma contribuição **suficientemente negativa** entre um *softgoal* descendente e um ascendente, concebida no nível mais alto de negação.  
  Se o *softgoal* descendente for satisfeito, o *softgoal* pai **será negado (não satisfeito)**.

- **HELP (+)**  
  Fornece uma contribuição **parcialmente positiva**.  
  Se o *softgoal* descendente for **parcialmente satisfeito**, o *softgoal* ascendente também será **parcialmente satisfeito**.

- **HURT (-)**  
  Fornece uma contribuição **parcialmente negativa**.  
  Se o *softgoal* descendente for satisfeito, o *softgoal* ascendente será **parcialmente negado**.

- **UNKNOWN (?)**  
  Fornece uma contribuição **desconhecida** entre um *softgoal* descendente e um ascendente.  
  Pode ser tanto **positiva quanto negativa**.

- **EQUALS**  
  Determina uma **relação de equivalência** entre os *softgoals*.  
  O *softgoal* descendente **só será satisfeito** se o *softgoal* ascendente for satisfeito, e **será negado** se o ascendente for negado.

- **SOME**  
  Utilizada quando o **sinal da contribuição é conhecido** (positivo ou negativo), mas a **extensão (parcial ou total)** não é.  
  Se há incerteza entre **HELP** e **MAKE**, usa-se **SOME (+)**.  
  Se há incerteza entre **HURT** e **BREAK**, usa-se **SOME (-)**.

<p align="center">
  <a href="https://imgbb.com/">
    <img src="https://i.ibb.co/JFyhVHhL/image.png" alt="Diagrama do Sistema" width="600"> 
 </a>
  <br>
  <b>Figura 04 – </b> Exemplos de contribuições "AND" e "OR"
</p>

<p align="center">
  <a href="https://imgbb.com/">
    <img src="https://i.ibb.co/bR8NhdgJ/image.png" alt="Diagrama do Sistema" width="600"> 
 </a>
  <br>
  <b>Figura 05 – </b>Exemplos de contribuições ” MAKE", ”BREAK ", ”HELP" e ”HURT"
</p>


## Metodologia


## SIG Usabilidade 



*Autoria: Fernanda Vaz, 2025.*
<p align="center">
<div style="width: 640px; height: 480px; margin: 10px; position: relative;"><iframe allowfullscreen frameborder="0" style="width:640px; height:480px" src="https://lucid.app/documents/embedded/929a11a2-17f7-4526-93f0-3c97ddc4d236" id="Yya1dj9snOkD"></iframe>
 <b>Figura 06 – </b> diagrama usabilidade</div>
</p>

## Referência bibliográfica 

<a id="ref-1"></a>

> <sup>1.</sup> SILVA, Reinaldo Antônio da. NFR4ES: um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Recife: Universidade Federal de Pernambuco, 2019.


## Bibliográfia 
> SANTOS, Fernanda Vaz Duarte dos. Diagrama NFR Framework [diagrama]. Lucidchart, 2025. Disponível em: https://lucid.app/lucidchart/929a11a2-17f7-4526-93f0-3c97ddc4d236/edit?beaconFlowId=49E1CE640021DB5A&invitationId=inv_64680c99-fc02-4e69-add7-7707c5326905&page=0_0
. Acesso em: 19 out. 2025.

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|:-------|:-----|:-----------|:------------|:-------------|
| 1.0 | 18/10 | Adição de introdução | Fernanda Vaz | |


## Agradecimentos

>>Agradecemos o suporte da ferramenta de Inteligência Artificial Generativa Google Gemini no desenvolvimento deste trabalho. Em conformidade com o Código de Conduta da Sociedade Brasileira de Computação (SBC), declaramos que a ferramenta foi utilizada como auxílio na revisão gramatical e estilística do texto, na sugestão de estrutura para seções específicas do artigo, bem como na formatação de tabelas e na descrição de figuras. Ressaltamos que os autores assumem total responsabilidade por todo o conteúdo apresentado, incluindo sua originalidade e precisão. A ferramenta não figura como autora desta publicação.