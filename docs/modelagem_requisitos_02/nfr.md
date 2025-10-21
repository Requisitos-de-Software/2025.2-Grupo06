## Introdução
O NFR Framework (Framework de Requisitos Não Funcionais) é uma abordagem utilizada para representar e analisar RNF. Segundo Reinaldo Antônio <sup>[1](#ref-1)</sup>, seu objetivo é auxiliar desenvolvedores a implementar soluções personalizadas. Essa abordagem considera as características específicas do sistema — como requisitos funcionais, não-funcionais, prioridades e carga de trabalho — para determinar as alternativas de desenvolvimento mais adequadas (CHUNG et al., 2000).

---

###### Print da Referência 
<p align="center">
<a href="https://ibb.co/HLCpRH1X"><img src="https://i.ibb.co/qLCFhrXx/image.png" alt="image" border="0" width="600"></a>  
<br>
<font size="3">Figura 01 – NFR Framework.</font>
</p>

---

## Softgoal Interdependency Graph
Segundo Reinaldo Antônio <sup>[1](#ref-1)</sup> o "Softgoal Interdependency Graph" (SIG) é um gráfico que registra as análises do desenvolvedor sobre os softgoals (objetivos não-funcionais) e mostra como eles dependem uns dos outros. Essencialmente, os SIGs armazenam todo o histórico das decisões de desenvolvimento e a lógica do projeto de forma visual e resumida.

Conforme Silva <sup>[1](#ref-1)</sup>, após a construção de uma taxonomia de Requisitos Não-Funcionais, é iniciada a criação de um Catálogo de RNFs, organizando todos os requisitos encontrados com suas definições, atributos, restrições e exemplos. Nesta etapa é realizada a construção de um grafo de Interdependência de Softgoal - Softgoal Interdependency Graph (SIG) com os Requisitos Não-Funcionais, adotando a notação do NFR Framework proposto por Chung et al. (2000). Além disso, para a documentação detalhada dos requisitos, adota-se o Cartão de Especificação baseado no cartão (snowcard) do processo Volere (Robertson; Robertson, 2012), que permite a escrita de exemplos do catálogo em um contexto real do sistema. Este cartão foi utilizado por se adequar bem à abordagem de análise de requisitos não-funcionais e por ser bastante utilizado no meio acadêmico.

### Cartão de Especificação de Requisitos

O Cartão de Especificação de Requisitos segue o padrão utilizado no NFR Framework para documentação detalhada de cada requisito não-funcional. Este cartão, baseado no processo Volere, estrutura-se com os seguintes campos:

| Campo | Descrição |
|-------|-----------|
| **Nr Requisito** | Um número sequencial para identificar o requisito |
| **Classificação** | Classificação do tipo de requisito |
| **Descrição** | Declaração única do significado do requisito |
| **Justificativa** | Justificativa sobre a criação do requisito |
| **Origem** | Origem do requisito (stakeholder, norma técnica, etc.) |
| **Critério de Ajuste** | Métrica do requisito que possa ser testada e que deve ser satisfeita |
| **Dependências** | Requisitos relacionados a este |
| **Prioridade** | Um número usado para decidir a importância relativa deste requisito entre os outros RNFs (varia de 1 a 10) |
| **Conflitos** | Requisitos conflitantes com este |
| **Histórico** | Data de criação e de modificações |

---

### Tipos de Softgoal

Existem três tipos de softgoals: **Softgoals NFR**, **Softgoals de Operacionalização** e **Softgoals de Afirmação**. Estes são descritos a seguir:

- **Softgoals NFR:** representam os Requisitos Não Funcionais e podem estar interrelacionados, organizados em catálogos e apresentados de forma hierárquica no desenvolvimento do projeto (CHUNG et al., 2000).

- **Softgoals de Operacionalização:** representam soluções de implementação para satisfazer softgoals NFR ou outros softgoals de operacionalização. Essas soluções incluem operações, processos, representações de dados e restrições no sistema alvo (CHUNG et al., 2000).

- **Softgoals de Afirmação:** permitem que características do domínio (como prioridades e carga de trabalho) sejam consideradas e refletidas nas decisões de projeto, servindo como justificativas para apoiar ou negar escolhas (CHUNG et al., 2000).

<p align="center">
<a href="https://imgbb.com/"><img src="https://i.ibb.co/h1L3Knr7/image.png" alt="Diagrama do Sistema" width="450"></a>  
<br>
<font size="3">Figura 02 – Tipos de Softgoal.</font>
</p>

---

### Tipos de Decomposições

As decomposições refinam softgoals para obter outros mais especializados, auxiliando na construção do projeto. Os quatro tipos principais são:

- **Decomposição de Softgoal NFR:** subdivide um softgoal em outros mais específicos.  
- **Decomposição de Operacionalização:** refina soluções de implementação.  
- **Decomposição de Afirmação (Claims):** detalha justificativas específicas de projeto.  
- **Priorização:** refina um softgoal em outro do mesmo tipo, mas com prioridade associada.  

<p align="center">
<a href="https://imgbb.com/"><img src="https://i.ibb.co/KjWPS9NR/image.png" alt="Tipos de Decomposição" width="600"></a>  
<br>
<font size="3">Figura 03 – Tipos de Decomposição.</font>
</p>

---

### Contribuições

O **NFR Framework** permite diversos tipos de contribuições que descrevem como a satisfação (ou não) de um *softgoal* descendente afeta a satisfação de um *softgoal* ascendente:

- **AND:** todos os descendentes devem ser satisfeitos.  
- **OR:** basta um descendente satisfeito.  
- **MAKE (++)**: contribuição fortemente positiva.  
- **BREAK (--)**: contribuição fortemente negativa.  
- **HELP (+)**: contribuição parcialmente positiva.  
- **HURT (-)**: contribuição parcialmente negativa.  
- **UNKNOWN (?)**: efeito desconhecido.  
- **EQUALS:** relação de equivalência entre *softgoals*.  
- **SOME:** sinal conhecido, mas extensão incerta.

<p align="center">
<a href="https://imgbb.com/"><img src="https://i.ibb.co/JFyhVHhL/image.png" alt="Contribuições AND e OR" width="600"></a>  
<br>
<font size="3">Figura 04 – Exemplos de Contribuições “AND” e “OR”.</font>
</p>

<p align="center">
<a href="https://imgbb.com/"><img src="https://i.ibb.co/bR8NhdgJ/image.png" alt="Contribuições MAKE BREAK HELP HURT" width="600"></a>  
<br>
<font size="3">Figura 05 – Exemplos de Contribuições “MAKE”, “BREAK”, “HELP” e “HURT”.</font>
</p>

---

## SIG Usabilidade

*Autoria: Fernanda Vaz, 2025.*

Os softgoals de usabilidade foram extraídos dos Requisitos de usabilidade da Especificação Suplementar. O diagrama completo deste SIG pode ser visualizado na Figura 06.

<p align="center">
<iframe allowfullscreen frameborder="0" style="width:640px; height:480px" src="https://lucid.app/documents/embedded/929a11a2-17f7-4526-93f0-3c97ddc4d236"></iframe>  
<br>
<font size="3">Figura 06 – Diagrama SIG Usabilidade.</font>
</p>

---

### Especificação dos Softgoals do SIG Usabilidade

Cartão de Especificação



#### Softgoals NFR

<center>
<font size="3">Tabela 01 – Softgoals NFR do SIG Usabilidade.</font>
</center>

| ID | Softgoal | Descrição |
|---|---|---|
| SIG-U01 | Usabilidade | Garantir que o sistema seja acessível e utilizável por todos os usuários. |
| SIG-U02 | Facilidade de Uso | Interface intuitiva e fácil de navegar. |
| SIG-U03 | Acessibilidade | Atender pessoas com deficiências visuais, auditivas e motoras. |
| SIG-U04 | Satisfação do Usuário | Proporcionar experiência positiva. |

---

#### Softgoals de Operacionalização

<center>
<font size="3">Tabela 02 – Softgoals de Operacionalização do SIG Usabilidade.</font>
</center>

| ID | Operacionalização | Softgoal Pai | Descrição |
|---|---|---|---|
| OP-U01 | Cores de alto contraste | SIG-U02 | Facilitar leitura e visibilidade. |
| OP-U02 | Interface intuitiva | SIG-U02 | Navegação clara e ícones reconhecíveis. |
| OP-U03 | Leitores de tela nativos | SIG-U03 | Compatível com TalkBack e VoiceOver. |
| OP-U04 | Modo alto contraste | SIG-U03 | Acessibilidade visual. |
| OP-U05 | Promover eficiência | SIG-U04 | Funcionalidades úteis e objetivas. |
| OP-U06 | Feedback do usuário | SIG-U04 | Coletar avaliações para melhorias. |

---

#### Softgoals de Afirmação

<center>
<font size="3">Tabela 03 – Softgoals de Afirmação do SIG Usabilidade.</font>
</center>

| ID | Afirmação | Softgoal Pai | Descrição |
|---|---|---|---|
| AF-U01 | Promove utilidade e eficiência | SIG-U04 | Interface eficiente aumenta a satisfação. |

---

#### Rastreabilidade

<center>
<font size="3">Tabela 04 – Rastreabilidade dos Softgoals do SIG Usabilidade.</font>
</center>

| Softgoal | Requisito Origem | Descendentes |
|---|---|---|
| SIG-U01 | RA01, RA02, RA03 | SIG-U02, SIG-U03, SIG-U04 |
| SIG-U02 | RA01 | OP-U01, OP-U02 |
| SIG-U03 | RA02, RA03 | OP-U03, OP-U04 |
| SIG-U04 | RA01, RA02, RA03 | OP-U05, OP-U06, AF-U01 |

---

## SIG Desempenho

*Autoria: Gabriel Maciel, 2025.*

![SIG Desempenho](../assets/imagens/nfr/sig_desempenho.svg)

<center>
<font size="3">Figura 07 – Diagrama SIG Desempenho.</font>
</center>

---

#### Softgoals NFR

<center>
<font size="3">Tabela 05 – Softgoals NFR do SIG Desempenho.</font>
</center>

| ID | Softgoal | Descrição |
|---|---|---|
| SIG-D01 | Desempenho | Garantir tempo de resposta e eficiência. |
| SIG-D02 | Tempo de Resposta Rápido | Operações concluídas em tempo aceitável. |
| SIG-D03 | Consumo Eficiente | Reduzir uso de bateria e dados móveis. |
| SIG-D04 | Múltiplos Usuários | Suportar vários usuários simultaneamente. |

---

#### Operacionalização

<center>
<font size="3">Tabela 06 – Softgoals de Operacionalização do SIG Desempenho.</font>
</center>

| ID | Operacionalização | Softgoal Pai | Descrição |
|---|---|---|---|
| OP-D01 | Rastreamento Otimizado | SIG-D02 | Latência máxima de 20s. |
| OP-D02 | Carregamento Rápido | SIG-D02 | Interface principal em até 3s. |
| OP-D03 | Cache de Requisições | SIG-D03 | Minimizar requisições redundantes. |
| OP-D04 | Compressão de Dados | SIG-D03 | Reduzir consumo de rede. |
| OP-D05 | Tamanho Compacto | SIG-D03 | Reduzir tamanho do app. |
| OP-D06 | Cache Local | SIG-D04 | Armazenar dados de paradas localmente. |
| OP-D07 | Servidor Responsivo | SIG-D04 | Suporte simultâneo a múltiplas conexões. |

---

#### Afirmação

<center>
<font size="3">Tabela 07 – Softgoals de Afirmação do SIG Desempenho.</font>
</center>

| ID | Afirmação | Softgoal Pai | Descrição |
|---|---|---|---|
| AF-D01 | Satisfação do Usuário | SIG-D02 | Usuários satisfeitos com a velocidade. |
| AF-D02 | Dispositivos Limitados | SIG-D03, SIG-D04 | Sistema funcional em dispositivos simples. |

---

#### Rastreabilidade

<center>
<font size="3">Tabela 08 – Rastreabilidade dos Softgoals do SIG Desempenho.</font>
</center>

| Softgoal | Requisito Origem | Descendentes |
|---|---|---|
| SIG-D01 | RD01–RD04 | SIG-D02, SIG-D03, SIG-D04 |
| SIG-D02 | RD01, RD02 | OP-D01, OP-D02, AF-D01 |
| SIG-D03 | RD03 | OP-D03, OP-D04, OP-D05, AF-D02 |
| SIG-D04 | RD04 | OP-D06, OP-D07, AF-D02 |

---

### Cartão de Especificação de Requisitos Não-Funcionais do SIG Desempenho

#### RD01 - Rastreamento de Veículos em Tempo Real

| Campo | Descrição |
|-------|-----------|
| **Nr Requisito** | RD01 / RNF03 |
| **Classificação** | Requisito Não-Funcional de Desempenho |
| **Descrição** | O sistema deve rastrear a localização de ônibus em tempo real com latência máxima de 20 segundos entre atualizações. |
| **Justificativa** | Essencial para que passageiros recebam informações precisas sobre a proximidade de ônibus, permitindo melhor planejamento de trajetos. |
| **Origem** | Elicitação de Requisitos: Entrevista (ENT09, ENT13) |
| **Critério de Ajuste** | Latência máxima de 20 segundos; precisão de localização de ±50 metros. |
| **Dependências** | RF35, RD04 |
| **Prioridade** | 9 |
| **Conflitos** | Nenhum |
| **Histórico** | Criado em 21/10/2025 |

#### RD02 - Tempo de Carregamento Rápido

| Campo | Descrição |
|-------|-----------|
| **Nr Requisito** | RD02 / RNF06 |
| **Classificação** | Requisito Não-Funcional de Desempenho |
| **Descrição** | A interface mobile da aplicação deve ser carregada em no máximo 3 segundos em conexões 4G. |
| **Justificativa** | Melhor experiência do usuário e redução de abandono de uso do aplicativo devido a lentidão. |
| **Origem** | Elicitação de Requisitos: Entrevista (ENT17) |
| **Critério de Ajuste** | Tempo de carregamento ≤ 3 segundos; testado em dispositivos com conexão 3G/4G. |
| **Dependências** | OP-D02, RD03 |
| **Prioridade** | 8 |
| **Conflitos** | Nenhum |
| **Histórico** | Criado em 21/10/2025 |

#### RD03 - Consumo Eficiente de Bateria e Dados

| Campo | Descrição |
|-------|-----------|
| **Nr Requisito** | RD03 / RNF10 |
| **Classificação** | Requisito Não-Funcional de Desempenho |
| **Descrição** | O sistema deve suportar pelo menos 10.000 usuários simultâneos com tempo de resposta menor que 2 segundos. |
| **Justificativa** | Permitir acesso a usuários com dispositivos antigos ou com planos de dados limitados, expandindo o alcance do sistema. |
| **Origem** | Elicitação de Requisitos: Análise de Documentos |
| **Critério de Ajuste** | Consumo de bateria ≤ 5% por hora em uso ativo; tamanho do app ≤ 50MB. |
| **Dependências** | OP-D03, OP-D04, OP-D05 |
| **Prioridade** | 7 |
| **Conflitos** | Nenhum |
| **Histórico** | Criado em 21/10/2025 |

#### RD04 - Suporte a Múltiplos Usuários Simultâneos

| Campo | Descrição |
|-------|-----------|
| **Nr Requisito** | RD04 / RNF14 |
| **Classificação** | Requisito Não-Funcional de Desempenho |
| **Descrição** | Os dados de localização de ônibus devem ser sincronizados com o servidor em tempo real, com no máximo 15 segundos de latência. |
| **Justificativa** | Garantir que o sistema mantenha a qualidade de serviço mesmo durante picos de uso, como horários de pico de deslocamento. |
| **Origem** | Elicitação de Requisitos: Brainstorm (BRS15) |
| **Critério de Ajuste** | Suportar ≥ 10.000 usuários simultâneos; tempo de resposta ≤ 2 segundos mesmo em carga máxima. |
| **Dependências** | OP-D06, OP-D07, RD01, RD02 |
| **Prioridade** | 9 |
| **Conflitos** | Nenhum |
| **Histórico** | Criado em 21/10/2025 |

---

## SIG Portabilidade/Compatibilidade

*Autoria: Cauã Nicolas, 2025.*

![SIG Portabilidade](../assets/imagens/nfr/NFR%20Portabilidade.svg)

<center>
<font size="3">Figura 08 – Diagrama SIG Portabilidade.</font>
</center>

---

## Referência bibliográfica 

<a id="ref-1"></a>

> <sup>1.</sup> SILVA, Reinaldo Antônio da. **NFR4ES: um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados.** Recife: Universidade Federal de Pernambuco, 2019.

---

## Bibliografia 

> SANTOS, Fernanda Vaz Duarte dos. **Diagrama NFR Framework** [diagrama]. Lucidchart, 2025.  
> Disponível em: [https://lucid.app/lucidchart/929a11a2-17f7-4526-93f0-3c97ddc4d236](https://lucid.app/lucidchart/929a11a2-17f7-4526-93f0-3c97ddc4d236).  
> Acesso em: 19 out. 2025.

---

## Histórico de Versões

<center>
<font size="3">Tabela 09 – Histórico de Versões.</font>
</center>

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|:-------:|:-----:|:-----------|:------------|:-------------|
| 1.0 | 18/10 | Adição do SIG Usabilidade e introdução | Fernanda Vaz | Gabriel Maciel |
| 1.1 | 20/10 | Adição do SIG Desempenho | Gabriel Maciel | Cauã Nicolas |
| 1.2 | 20/10 | Adição do SIG Portabilidade | Cauã Nicolas | Gabriel Maciel |
| 1.3 | 20/10 | Adição do SIG Acessibilidade | Fernanda vaz  | Gabriel Maciel |
| 1.4 | 21/10 | Adição de Cartões de Especificação dos RNFs do SIG Desemepnho | Gabriel Maciel | |
---

## Agradecimentos

Agradecemos o suporte da ferramenta de Inteligência Artificial Generativa Google Gemini no desenvolvimento deste trabalho.  
Em conformidade com o Código de Conduta da Sociedade Brasileira de Computação (SBC), declaramos que a ferramenta foi utilizada como auxílio na revisão gramatical e estilística, bem como na formatação e estruturação das tabelas e figuras.  
Os autores assumem total responsabilidade pelo conteúdo e originalidade do trabalho.  
A ferramenta **não figura como autora desta publicação**.
