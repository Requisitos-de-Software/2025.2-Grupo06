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

Conforme Silva <sup>[1](#ref-1)</sup>, após a construção de uma taxonomia de Requisitos Não-Funcionais, é iniciada a criação de um Catálogo de RNFs, organizando todos os requisitos encontrados com suas definições, atributos, restrições e exemplos. Nesta etapa é realizada a construção de um grafo de Interdependência de Softgoal - Softgoal Interdependency Graph (SIG) com os Requisitos Não-Funcionais, adotando a notação do NFR Framework proposto por Chung et al. (2000). Além disso, para a documentação detalhada dos requisitos, adota-se o Cartão de Especificação baseado no cartão (snowcard) do processo Volere (Robertson; Robertson, 2012), que permite a escrita de exemplos do catálogo em um contexto real do sistema. Este cartão foi utilizado por se adequar bem à abordagem de análise de requisitos não-funcionais.

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

Os softgoals de desempenho foram extraídos dos Requisitos de Desempenho (RD01-RD04) definidos na Especificação Suplementar. O diagrama completo deste SIG pode ser visualizado na Figura 07.



![SIG Desempenho](../assets/imagens/nfr/sig_desempenho.svg)

<center>
<font size="3">Figura 07 – Diagrama SIG Desempenho.</font>
</center>

---

#### Softgoals NFR

A **Tabela 05** lista os softgoals NFR principais.

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

#### Softgoals de Operacionalização

**Tabela 06** - Tabela de Especificação de Softgoals de Operacionalização do SIG Desempenho


<center>
<font size="3">Tabela 06 – Softgoals de Operacionalização do SIG Desempenho.</font>
</center>

| ID | Operacionalização | Softgoal Pai | Descrição |
|---|---|---|---|
| OP-D01 | Rastreamento Otimizado | SIG-D02 | Implementar rastreamento de veículos com latência máxima de 20 segundos. |
| OP-D02 | Carregamento Rápido da Interface | SIG-D02 | Interface principal carrega em menos de 3 segundos. |
| OP-D03 | Redução de Requisições | SIG-D03 | Minimizar requisições de rede desnecessárias através de cache e sincronização eficiente. |
| OP-D04 | Compressão de Dados | SIG-D03 | Aplicar compressão em dados transmitidos para reduzir consumo de dados móveis. |
| OP-D05 | Tamanho Compacto da Aplicação | SIG-D03 | Manter o tamanho do aplicativo reduzido para economizar espaço de armazenamento em dispositivos com recursos limitados. |
| OP-D06 | Cache de Informações | SIG-D04 | Armazenar dados de linhas, paradas e horários localmente para reduzir carga de requisições ao servidor. |
| OP-D07 | Servidor Responsivo | SIG-D04 | Manter infraestrutura de servidor estável e responsiva para processar múltiplas requisições simultâneas de rastreamento e consulta. |

---

#### Softgoals de Afirmação

A **Tabela 07** especifica os softgoals de afirmação.

<center>
<font size="3">Tabela 07 – Softgoals de Afirmação do SIG Desempenho.</font>
</center>

| ID | Afirmação | Softgoal Pai | Descrição |
|---|---|---|---|
| AF-D01 | Satisfação do Usuário | SIG-D02 | Usuários satisfeitos com a velocidade da aplicação. |
| AF-D02 | Funcionamento em Dispositivos Limitados | SIG-D03, SIG-D04 | Sistema funciona bem em smartphones com recursos reduzidos. |

---

#### Rastreabilidade

<center>
<font size="3">Tabela 08 – Rastreabilidade dos Softgoals do SIG Desempenho.</font>
</center>

| Softgoal | Requisito Origem | Descendentes |
|---|---|---|
| SIG-D01 | RD01, RD02, RD03, RD04 | SIG-D02, SIG-D03, SIG-D04 |
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
| **Histórico** | Criado em 21/10/2025 — Autor: Gabriel Maciel |

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
| **Histórico** | Criado em 21/10/2025 — Autor: Gabriel Maciel |

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
| **Histórico** | Criado em 21/10/2025 — Autor: Gabriel Maciel |

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
| **Histórico** | Criado em 21/10/2025  — Autor: Gabriel Maciel |

---

## SIG Portabilidade/Compatibilidade

*Autoria: Cauã Nicolas, 2025.*

![SIG Portabilidade](../assets/imagens/nfr/NFR%20Portabilidade.svg)

<center>
<font size="3">Figura 08 – Diagrama SIG Portabilidade.</font>
</center>

---

### Cartão de Especificação de Requisitos Não-Funcionais do SIG Portabilidade

#### RS01 - Funcionalidade e Responsividade em Navegadores Móveis

| Campo | Descrição |
|-------|-----------|
| **Nr Requisito** | RS01 |
| **Classificação** | Requisito do Sistema (Funcionalidade / Usabilidade) |
| **Descrição** | A aplicação deve ser funcional e responsiva em navegadores web de dispositivos móveis (celulares). |
| **Justificativa** | Garantir acesso amplo sem necessidade de instalação e assegurar boa experiência em dispositivos móveis. |
| **Origem** | Documento de requisitos / Entrevistas (RFxx) |
| **Critério de Ajuste** | - Layout adaptativo em telas de 320px a 1080px.<br>- Elementos interativos acessíveis e tocáveis conforme WCAG; testes em 3 navegadores móveis principais. |
| **Dependências** | Depende de práticas de CSS responsivo, frameworks front-end e testes de usabilidade. |
| **Prioridade** | 9 |
| **Conflitos** | Pode conflitar com requisitos de desempenho se renderização for pesada. |
| **Histórico** | Criado em 21/10/2025 — Autor: Cauã Nicolas |

#### RS02 - Funcionamento Offline

| Campo | Descrição |
|-------|-----------|
| **Nr Requisito** | RS02 |
| **Classificação** | Requisito do Sistema (Disponibilidade / Operacionalidade) |
| **Descrição** | A aplicação deve funcionar mesmo sem conexão de internet para consulta a rotas salvas e horários. |
| **Justificativa** | Usuários em áreas com conectividade limitada precisam acessar informações básicas sem conexão. |
| **Origem** | Documento de requisitos / Entrevistas (RFxx) |
| **Critério de Ajuste** | - Dados essenciais (rotas e horários salvos) acessíveis offline.<br>- Tempo de sincronização de dados ao reconectar ≤ 10s para atualizações incrementais. |
| **Dependências** | Implementação de cache local (IndexedDB/LocalStorage) e sincronização de dados. |
| **Prioridade** | 9 |
| **Conflitos** | Armazenamento local pode aumentar uso de espaço no dispositivo; segurança de dados offline. |
| **Histórico** | Criado em 21/10/2025 — Autor: Cauã Nicolas |

#### RS03 - Configuração de Notificações (Som e Vibração)

| Campo | Descrição |
|-------|-----------|
| **Nr Requisito** | RS03 |
| **Classificação** | Requisito do Sistema (Notificações / Usabilidade) |
| **Descrição** | O sistema de notificação com som e vibração deve estar devidamente configurável pelo usuário. |
| **Justificativa** | Permitir ao usuário adaptar notificações conforme preferências e necessidades (p.ex., modo silencioso). |
| **Origem** | Documento de requisitos / Entrevistas (RFxx) |
| **Critério de Ajuste** | - Usuário pode ativar/desativar som e vibração independentemente.<br>- Preferências persistidas entre sessões. |
| **Dependências** | API de notificações do navegador/dispositivo; armazenamento de preferências do usuário. |
| **Prioridade** | 8 |
| **Conflitos** | Pode conflitar com políticas de plataforma sobre uso de som/vibração em segundo plano. |
| **Histórico** | Criado em 21/10/2025 — Autor: Cauã Nicolas |

#### RS04 - Compatibilidade com APIs Externas

| Campo | Descrição |
|-------|-----------|
| **Nr Requisito** | RS04 |
| **Classificação** | Requisito do Sistema (Integração) |
| **Descrição** | O sistema deve ser compatível com APIs externas de transporte público e serviços de geolocalização. |
| **Justificativa** | Integração com provedores externos é essencial para dados em tempo real e funcionalidade correta do app. |
| **Origem** | Documento de requisitos / Análise de APIs (RFxx) |
| **Critério de Ajuste** | - Suporte a formatos JSON/GeoJSON e autenticação via API keys/OAuth.<br>- Testes de integração automatizados com provedores principais. |
| **Dependências** | Contratos/SLAs com provedores (BRB Mobilidade, APIs de mapas). |
| **Prioridade** | 9 |
| **Conflitos** | Dependência externa pode afetar disponibilidade; necessidade de adaptação a mudanças de API. |
| **Histórico** | Criado em 21/10/2025 — Autor: Cauã Nicolas |

#### RS05 - Ajuste Automático de Layout

| Campo | Descrição |
|-------|-----------|
| **Nr Requisito** | RS05 |
| **Classificação** | Requisito do Sistema (Usabilidade / Compatibilidade) |
| **Descrição** | A interface deve ajustar automaticamente os elementos visuais para diferentes resoluções de tela, mantendo legibilidade e usabilidade. |
| **Justificativa** | Garantir que usuários em dispositivos diversos tenham experiência consistente e legível. |
| **Origem** | Documento de requisitos / Entrevistas (RFxx) |
| **Critério de Ajuste** | - Tipografia e espaçamento adaptativos; elementos acessíveis em dispositivos pequenos.<br>- Pontuação mínima em testes de usabilidade de 80% para tarefas básicas. |
| **Dependências** | Frameworks de UI responsiva, testes de usabilidade e guidelines WCAG. |
| **Prioridade** | 9 |
| **Conflitos** | Pode conflitar com limitações de layout em dispositivos muito pequenos; trade-offs entre detalhe e simplicidade. |
| **Histórico** | Criado em 21/10/2025 — Autor: Cauã Nicolas |


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
| 1.4 | 21/10 | Adição de Cartões de Especificação dos RNFs do SIG Desempenho | Gabriel Maciel | Cauã Nicolas |
| 1.5 | 21/10 | Adição de Cartões de Especificação dos RNFs do SIG Portabilidade | Gabriel Maciel | Cauã Nicolas |

---

## Agradecimentos

Agradecemos o suporte da ferramenta de Inteligência Artificial Generativa Google Gemini no desenvolvimento deste trabalho.  
Em conformidade com o Código de Conduta da Sociedade Brasileira de Computação (SBC), declaramos que a ferramenta foi utilizada como auxílio na revisão gramatical e estilística, bem como na formatação e estruturação das tabelas e figuras.  
Os autores assumem total responsabilidade pelo conteúdo e originalidade do trabalho.  
A ferramenta **não figura como autora desta publicação**.
