## Introdução

Conforme as diretrizes do Ministério da Ciência, Tecnologia e Inovação [(MCTI, 2014)](#ref-mctic), a Especificação Suplementar é um artefato essencial no processo de engenharia de requisitos, destinado a capturar as exigências do sistema não abordadas nos casos de uso. Este documento detalha um vasto conjunto de requisitos não-funcionais e restrições globais, abrangendo desde requisitos legais e regulatórios até os atributos de qualidade que definem a operação do sistema, como usabilidade, confiabilidade, desempenho e suportabilidade. Além disso, a especificação também define restrições técnicas, como ambientes operacionais, requisitos de compatibilidade e limitações de design que devem ser consideradas no projeto.

A presente especificação aplica-se ao aplicativo móvel DF no Ponto, disponível para plataformas Android e iOS, destinado aos cidadãos do Distrito Federal para acesso a informações de transporte público em tempo real.

## Tabela de contribuição

|        Nome          | Contribuição |
|----------------------|--------------|
| Cauã Nicolas | A preencher. |
| Daniel Nunes | A preencher. |
| Fernanda Vaz | - [Especificação Suplementar dos Requisitos de Usabilidade](#usabilidade) |
| Gabriel Maciel | - [Especificação Suplementar dos Requisitos de Desempenho](#desempenho) <br> - Revisão e correções do documento (Versão 2.0) |
| João Gabriel | A preencher. |
| João Ramos | A preencher. |


## Metodologia

A elaboração desta Especificação Suplementar fundamenta-se nas diretrizes estabelecidas pelo Processo de Software do MCTIC [(MCTI, 2014)](#ref-mctic), que define este artefato como um documento complementar aos casos de uso, capturando requisitos não-funcionais e restrições globais do sistema. Conforme sugerido pelo MCTIC, a especificação suplementar abrange requisitos de usabilidade, confiabilidade, desempenho, suportabilidade, além de restrições de design, implementação, interface e requisitos físicos.

Para a construção deste documento, adotou-se uma abordagem sistemática que engloba as seguintes etapas metodológicas:

1. **Identificação de Requisitos Não-Funcionais**: A partir dos requisitos elicitados nas etapas anteriores do projeto (entrevistas, brainstorming e análise de documentos), foram identificados e categorizados os requisitos que extrapolam a funcionalidade direta do sistema, incluindo aspectos de qualidade, desempenho e restrições técnicas.

2. **Categorização Conforme Modelo FURPS+**: Os requisitos não-funcionais foram organizados seguindo o modelo FURPS+ (*Functionality, Usability, Reliability, Performance, Supportability*), adaptado conforme as diretrizes do MCTIC. Esta categorização permite uma visão estruturada e abrangente dos atributos de qualidade do sistema.

3. **Definição de Métricas e Critérios Mensuráveis**: Para cada categoria de requisito não-funcional, foram estabelecidos critérios objetivos e mensuráveis, permitindo a verificação e validação durante as fases de desenvolvimento e testes. Por exemplo, para requisitos de desempenho, foram definidos tempos máximos de resposta e capacidade de usuários simultâneos.

4. **Rastreabilidade com Artefatos de Elicitação**: Cada requisito não-funcional foi rastreado até sua origem nos artefatos de elicitação (análise de documentos, entrevistas, brainstorming), garantindo a transparência e justificativa para cada especificação estabelecida.

5. **Conformidade com Normas e Padrões**: Os requisitos foram definidos em conformidade com normas técnicas e regulamentações aplicáveis, incluindo as diretrizes de acessibilidade WCAG (*Web Content Accessibility Guidelines*) para requisitos de usabilidade, e a Lei Geral de Proteção de Dados (LGPD) para requisitos de privacidade e segurança.

Esta metodologia garante que a Especificação Suplementar esteja alinhada tanto com as boas práticas da engenharia de requisitos quanto com as necessidades específicas do contexto do aplicativo DF no Ponto, proporcionando uma base sólida para o desenvolvimento e validação do sistema.

## Usabilidade

A Tabela 3 apresenta os Requisitos de Usabilidade, que representam o esforço necessário para utilizar o aplicativo e a avaliação individual desse uso por um conjunto específico de cidadãos. Abrange aspectos como facilidade de aprendizado, eficiência, memorização, prevenção de erros e satisfação do público-alvo, garantindo uma experiência intuitiva e acessível.

??? info "Tabela 2: Requisitos de Usabilidade (RU) - Versão 1.0"

    Por não haver correspondência real com os requisitos elicitados a partir das técnicas de elicitação, a a partir da Tabela 2, foi criada a Tabela 3, que readapta os requisitos desta tabela correlacionando-os com os [requisitos não-funcionais da tabela geral](../Elicitacao/elicitacao_lista_requisitos_elicitados.md).

    **Autoria:** Fernanda Vaz, 2025

    | ID | Descrição |
    |---|---|
    | RU01 | Cidadãos devem conseguir utilizar funcionalidades básicas sem treinamento prévio. |
    | RU02 | oferecer resultados precisos para o usuário |
    | RU03 | Interface deve ser facilmente memorável para passageiros que usam ocasionalmente. |
    | RU04 | A interface deve ser agradável e satisfatória de usar. |
    | RU05 | Suporte a leitores de tela e ajuste de contraste conforme [WCAG](#ref-wcag) (*Web Content Accessibility Guidelines*). |
    | RU06 | Mensagens de erro e confirmação devem ser claras e objetivas. |
    | RU07 | Padrões visuais e de interação consistentes em todo o aplicativo. |
    | RU08 | Permitir ajustes básicos de preferências visuais (tema, fonte, notificações). |
    | RU09 | A interface deve ser adaptável para diferentes tipos de usuário (como usuários com deficiência visual, auditiva ou motora). |

### Tabela 3: Requisitos de Usabilidade (RU) - Versão 2.0

| ID | Descrição | Rastreabilidade | Autoria |
|----|-----------|-----------------|---------|
| RU01 | Interface acessível para idosos e pessoas com deficiência visual | [RNF04](../Elicitacao/elicitacao_lista_requisitos_elicitados.md) | Fernanda Vaz, Gabriel Maciel |
| RU02 | Sistema de notificação com som e vibração configuráveis | [RNF05](../Elicitacao/elicitacao_lista_requisitos_elicitados.md) | Fernanda Vaz, Gabriel Maciel |
| RU03 | Compatibilidade com dispositivos Android e iOS | [RNF07](../Elicitacao/elicitacao_lista_requisitos_elicitados.md) | Fernanda Vaz, Gabriel Maciel |
| RU04 | Personalização da interface com base em preferências do usuário | [RNF15](../Elicitacao/elicitacao_lista_requisitos_elicitados.md) | Fernanda Vaz, Gabriel Maciel  |
| RU05 | Suporte a leitores de tela e ajuste de contraste conforme [WCAG](#ref-wcag) (*Web Content Accessibility Guidelines*). | Conformidade com Padrões Internacionais [WCAG 2.1 AA](#ref-wcag) | Fernanda Vaz |
| RU06 | Sempre que uma mensagem de erro for exibida, ela deve identificar claramente qual é o elemento que gerou o erro de forma visual e audível (exemplo: mudança de cor no elemento + um ícone de alerta + uma mensagem em texto). |  Conformidade com Padrões Internacionais [WCAG 2.1 AA](#ref-wcag) (Critério de Sucesso 3.3.1 - Identificação de erro) | Fernanda Vaz, Gabriel Maciel |

## Confiabilidade

A Tabela 5 apresenta os Requisitos de Confiabilidade, que expressam a capacidade do sistema de manter seu nível de desempenho sob condições estabelecidas durante um período determinado. Contempla aspectos como disponibilidade, maturidade, tolerância a falhas, recuperabilidade e estabilidade, assegurando que o aplicativo opere de forma consistente e resiliente.

??? info "Tabela 4: Requisitos de Confiabilidade - Versão 1.0"

    Por não haver correspondência real com os requisitos elicitados a partir das técnicas de elicitação, a partir da Tabela 4, foi criada a Tabela 5, que readapta os requisitos não-funcionais desta tabela correlacionando-os com os [requisitos não-funcionais da tabela geral](../Elicitacao/elicitacao_lista_requisitos_elicitados.md).

    Autoria: Fernanda Vaz e João Ramos, 2025.

    | ID | Descrição |
    |---|---|
    | RC01 | Sistema deve operar sem falhas críticas. |
    | RC02 | O sistema deve continuar operando mesmo com falhas parciais. |
    | RC03 | Capacidade de recuperar dados e restabelecer operação após falhas. |
    | RC04 | Funcionamento adequado em condições de rede instável com conectividade intermitente. |
    | RC05 | Transações devem ser completadas integralmente ou revertidas sem estados parciais. |
    | RC06 | Sistema deve detectar e reportar falhas automaticamente em logs. |
    | RC07 | Dados devem permanecer consistentes entre diferentes sessões e dispositivos. |

### Tabela 5 - Requisitos de Confiabilidade (RC) - Versão 2.0

| ID | Descrição | Rastreabilidade | Autoria |
|----|-----------|-----------------|---------|
| RC01 | Alta disponibilidade do sistema (≥ 98% uptime) | [RNF13](../Elicitacao/elicitacao_lista_requisitos_elicitados.md) | Fernanda Vaz, Gabriel Maciel |
| RC02 | Suporte a múltiplos usuários simultâneos sem lentidão | [RNF14](../Elicitacao/elicitacao_lista_requisitos_elicitados.md) | Fernanda Vaz, Gabriel Maciel |
| RC03 | As informações de horários (de saída e chegada) e localização dos ônibus devem ser precisas (horário com precisão de ±5 minutos, localização com precisão de ±100 metros) | [RNF01](../Elicitacao/elicitacao_lista_requisitos_elicitados.md) | João Ramos, Gabriel Maciel | 
| RC04 | Tempo de atualização da localização (dos ônibus) ≤ 20 segundos | [RNF03](../Elicitacao/elicitacao_lista_requisitos_elicitados.md) | João Ramos, Gabriel Maciel |

## Desempenho

O desempenho define as características de eficiência do sistema, incluindo tempos de resposta para transações, a taxa de transferência de dados e a capacidade de usuários simultâneos que o sistema pode acomodar. Conforme as diretrizes, esta seção detalha os requisitos de performance e a utilização de recursos como memória e disco, garantindo que a aplicação opere dentro dos parâmetros esperados.

### Tabela 6 - Requisitos de Desempenho (RD) - Versão 2.0

| ID | Descrição | Rastreabilidade | Autoria |
|---|---|---|---|
| RD01 | O tempo de rastreio de um veículo em tempo real deve ser menor que 20 segundos. | [RNF03](../Elicitacao/elicitacao_lista_requisitos_elicitados.md) | Gabriel Maciel |
| RD02 | O tempo de carregamento da tela principal deve ser inferior a 3 segundos. | [RNF10](../Elicitacao/elicitacao_lista_requisitos_elicitados.md) | Gabriel Maciel |
| RD03 | O aplicativo deve apresentar baixo consumo de bateria e dados móveis durante o uso. | [RNF06](../Elicitacao/elicitacao_lista_requisitos_elicitados.md) | Gabriel Maciel |
| RD04 | O sistema deve suportar múltiplos usuários simultâneos sem apresentar lentidão ou degradação de performance. | [RNF14](../Elicitacao/elicitacao_lista_requisitos_elicitados.md) | Gabriel Maciel |

## Requisitos do Sistema (Portabilidade/Compatibilidade)

Os Requisitos de Sistema definem todas as condições necessárias para suportar o aplicativo, garantindo sua correta operação em diferentes ambientes. Esta seção especifica as plataformas de hardware, os sistemas operacionais e as redes suportadas, assegurando que o produto esteja em conformidade com os padrões de plataforma aplicáveis (como Windows, Android, iOS, etc.) e interaja corretamente com outros softwares e periféricos definidos.

??? info "Tabela 7: Requisitos do Sistema (RS) - Versão 1.0"

    Por não haver correspondência real com os requisitos elicitados a partir das técnicas de elicitação, a partir da Tabela 4, foi criada a Tabela 5, que readapta os requisitos não-funcionais desta tabela correlacionando-os com os [requisitos não-funcionais da tabela geral](../Elicitacao/elicitacao_lista_requisitos_elicitados.md).

    Autoria: Cauã Nicolas, 2025.

    | ID | Descrição | Rastreabilidade | Autoria |
    |---|---|---|---|
    | RS01 | A aplicação deve ser funcional e responsiva em navegadores web de dispositivos móveis (celulares) |
    | RS02 | A aplicação deve funcionar mesmo sem conexão de internet para consulta a rotas salvas e horários. |
    | RS03 | O sistema de notificação com som e vibração devem estar devidamente configuráveis. |
    | RS04 | O sistema deve ser compatível com APIs externas de transporte público e serviços de geolocalização. |
    | RS05 | A interface deve ajustar automaticamente os elementos visuais para diferentes resoluções de tela, mantendo legibilidade e usabilidade. |

### Tabela 8: Requisitos do Sistema (RS) - Versão 2.0

| ID | Descrição | Rastreabilidade | Autoria |
|---|---|---|---|
| RS01 | A aplicação deve ser funcional e responsiva em navegadores web de dispositivos móveis (celulares) | [RF19](../Elicitacao/elicitacao_lista_requisitos_elicitados.md) | Cauã Nicolas |
| RS02 | A aplicação deve funcionar mesmo sem conexão de internet para consulta a rotas salvas e horários. | [RNF11](../Elicitacao/elicitacao_lista_requisitos_elicitados.md) | Cauã Nicolas |
| RS03 | O sistema de notificação com som e vibração devem ser configuráveis. | [RNF05](../Elicitacao/elicitacao_lista_requisitos_elicitados.md) | Cauã Nicolas |
| RS04 | A interface deve ajustar automaticamente os elementos visuais para diferentes resoluções de tela, mantendo legibilidade e usabilidade. | Conformidade com Padrões Internacionais [WCAG 2.1 AA](#ref-wcag)| Cauã Nicolas |

## Padrões aplicáveis

Esta seção lista todos os padrões com os quais o produto deverá estar em conformidade, incluindo padrões legais e reguladores, padrões de comunicações, padrões de conformidade com plataformas e padrões de qualidade e segurança, conforme as diretrizes do MCTIC [(MCTI, 2014)](#ref-mctic). A Tabela 10 apresenta os padrões aplicáveis presentes nessa seção, os quais o DF No Ponto deve estar em conformidade.

| ID | Padrão Aplicável | Autoria |
|----|------------------|---------|
| [PA01](#pao1---lei-geral-de-proteção-de-dados-lgpd---brasil) | Lei Geral de Proteção de Dados (LGPD) | Gabriel Maciel, Daniel Nunes Duarte |
| [PA02](#pa02---transport-layer-security-tls-12-ou-superior) | Transport Layer Security (TLS) 1.2 ou superior | Gabriel Maciel, Daniel Nunes Duarte |
| [PA03](#pa03---norma-isoiec-27001-segurança-da-informação) | Norma ISO/IEC 27001 (Segurança da Informação) | Gabriel Maciel, Daniel Nunes Duarte |
| [PA04](#pa04---protocolo-oauth-20) | Protocolo OAuth 2.0 | Gabriel Maciel, Daniel Nunes Duarte |

??? info "Segurança e Privacidade - Versão 1.0"

    A seção de Padrões aplicáveis realinha os requisitos não-funcionais presentes abaixo em padrões e normas correspondentes, como especificado pela definição de Especificação Suplementar do [MCTIC](#ref-mctic)

    ### Segurança

    #### Tabela 9 - Requisitos de Segurança (RSE)

    A seção de Segurança descreve os requisitos para proteger o aplicativo e os dados dos usuários contra ameaças, ataques e acessos não autorizados. Ela cobre mecanismos de autenticação, autorização, criptografia, registro de eventos (logging) e monitoramento de incidentes.

    | ID | Descrição |
    |---|---|
    | RSE01 | O sistema deve utilizar autenticação forte para todos os usuários (ex.: OAuth2 ou autenticação multifator para operações sensíveis). |
    | RSE02 | Todas as comunicações entre cliente e servidor devem ser criptografadas usando TLS 1.2 ou superior. |
    | RSE03 | Senhas e credenciais devem ser armazenadas usando hashing seguro (ex.: bcrypt, Argon2) com salt. |
    | RSE04 | Deve existir um mecanismo de controle de sessão que invalide sessões inativas e permita logout remoto. |
    | RSE05 | Registro (logging) de eventos de segurança (tentativas de login, alterações de privilégios, erros críticos) para auditoria. |
    | RSE06 | Proteção contra ataques comuns (XSS, CSRF, injeção de SQL) aplicando validação e sanitização de entrada. |

    <span style="color:blue;">Autoria: Daniel Nunes Duarte, 2025.</span>

    ### Privacidade

    #### Tabela 10 - Requisitos de Privacidade (RPV)

    Esta seção define os requisitos de privacidade e proteção de dados pessoais dos usuários do aplicativo, em conformidade com a legislação aplicável (por exemplo, LGPD) e melhores práticas de minimização de dados e transparência.

    | ID | Descrição |
    |---|---|
    | RPV01 | Coleta de dados deve ser limitada ao mínimo necessário para a finalidade declarada e informada ao usuário. |
    | RPV02 | Deve ser fornecido um termo de consentimento claro e acessível, permitindo que o usuário aceite ou recuse coleta de dados sensíveis. |
    | RPV03 | Usuários devem ter mecanismos para visualizar, corrigir e solicitar exclusão de seus dados pessoais. |
    | RPV04 | Dados pessoais armazenados devem ser criptografados em repouso quando tecnicamente viável. |
    | RPV05 | Logs e backups que contenham dados pessoais devem ter acesso restrito e retenção limitada conforme política da organização. |
    | RPV06 | Deve ser realizada uma avaliação de impacto sobre a proteção de dados (DPIA) para funcionalidades que processem dados sensíveis. |

    <span style="color:blue;">Autoria: Daniel Nunes Duarte, 2025.</span>

### PAO1 - Lei Geral de Proteção de Dados (LGPD) - Brasil

O sistema deve estar em conformidade com a [Lei 13.709/2018](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm), garantindo a proteção de dados pessoais dos usuários, inclusive direitos de acesso, correção, exclusão e consentimento informado. A Tabela 11 apresenta requisitos não-funcionais criados a partir desta conformidade.

#### Tabela 11 - Requisitos Não-Funcionais que se relacionam com a LGPD (RNFPA01)

| ID | Descrição | Autoria |
|---|---|---|
| RNFPA01.01 | Coleta de dados deve ser limitada ao mínimo necessário para a finalidade declarada e informada ao usuário. | Daniel Nunes Duarte |
| RNFPA01.02 | Deve ser fornecido um termo de consentimento claro e acessível, permitindo que o usuário aceite ou recuse coleta de dados sensíveis. | Daniel Nunes Duarte |
| RNFPA01.03 | Usuários devem ter mecanismos para visualizar, corrigir e solicitar exclusão de seus dados pessoais. | Daniel Nunes Duarte |
| RNFPA01.04 | Dados pessoais armazenados devem ser criptografados em repouso quando tecnicamente viável. | Daniel Nunes Duarte |
| RNFPA01.05 | Logs e backups que contenham dados pessoais devem ter acesso restrito e retenção limitada conforme política da organização. | Daniel Nunes Duarte |
| RNFPA01.06 | Deve ser realizada uma avaliação de impacto sobre a proteção de dados (DPIA) para funcionalidades que processem dados sensíveis. | Daniel Nunes Duarte |

### PA02 - [Transport Layer Security (TLS)](https://datatracker.ietf.org/doc/html/rfc5246) 1.2 ou superior

Todas as comunicações entre cliente e servidor devem ser criptografadas utilizando TLS 1.2 ou versões mais recentes para garantir segurança nas transmissões de dados.  A Tabela 12 apresenta requisitos não-funcionais criados a partir desta conformidade.

#### Tabela 12 - Requisitos Não-Funcionais que se relacionam com o TLS 1.2 ou superior (RNFPA02)

| ID | Descrição | Autoria |
|---|---|---|
| RNFPA02.01 | Todas as comunicações entre cliente e servidor devem ser criptografadas usando TLS 1.2 ou superior. | Daniel Nunes Duarte |

### PA03 - [Norma ISO/IEC 27001](https://www.iso.org/standard/27001) (Segurança da Informação)

O sistema deve implementar práticas de segurança da informação conforme a norma ISO/IEC 27001, incluindo autenticação forte, logging de eventos e proteção contra ataques.

#### Tabela 13 - Requisitos Não-Funcionais que se relacionam com a Norma ISO/IEC 27001 (RNFPA03)

| ID | Descrição | Autoria |
|---|---|---|
| RNFPA03.01 | O sistema deve utilizar autenticação forte para todos os usuários (ex.: OAuth2 ou autenticação multifator para operações sensíveis). | Daniel Nunes Duarte |
| RNFPA03.02 | Senhas e credenciais devem ser armazenadas usando hashing seguro (ex.: bcrypt, Argon2) com salt. | Daniel Nunes Duarte |
| RNFPA03.03 | Registro (logging) de eventos de segurança (tentativas de login, alterações de privilégios, erros críticos) para auditoria. | Daniel Nunes Duarte |
| RNFPA03.04 | Proteção contra ataques comuns (XSS, CSRF, injeção de SQL) aplicando validação e sanitização de entrada. | Daniel Nunes Duarte |

## Referências bibliográficas

<a id="ref-mctic"></a>
>BRASIL. Ministério da Ciência, Tecnologia, Inovações e Comunicações. *Processo de Software do MCTIC: Documento Descritivo*. Brasília, DF: MCTIC, 2014. Disponível em: <https://ps.mctic.gov.br/MCTI-PS/workproducts/resources/PS_DocumentoDescritivo.pdf>. Acesso em: 7 out. 2025.

>BRASIL. Ministério da Ciência, Tecnologia, Inovações e Comunicações. *Especificação Suplementar - Template MCTIC*. Brasília, DF: MCTIC, 2014. Disponível em: <https://pdm.mctic.gov.br/MCTIC-PDM/guidances/examples/resources/SiglaProjeto_EspecificacaoSuplementar.docx>. Acesso em: 19 nov. 2025.

<a id="ref-wcag"></a>
>GUIA WCAG. Disponível em: <https://guia-wcag.com>. Acesso em: 9 out. 2025.

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor |
|:------:|:-----------|:--------------------------------------------|:--------------|:----------------|
| 1.0 | 08/10/2025 | Criação da estrutura inicial do documento. | Gabriel Maciel | Fernanda Vaz |
| 1.2 | 08/10/2025 | Adição de especificação suplementar inicial. | Fernanda Vaz | Gabriel Maciel |
| 1.3 | 12/10/2025 | Adição de componentes de Desempenho e Requisitos do Sistema para especificação suplementar. | João Ramos | Gabriel Maciel |
| 1.4 | 12/10/2025 | Adição de especificações suplementares (Segurança, Privacidade) | Daniel Nunes Duarte | Gabriel Maciel |
| 1.5 | 19/10/2025 | Adição de novos requisitos não-funcionais relacionados a desempenho | Gabriel Maciel | A revisar |
| 2.0 | 19/11/2025 | Adição da metodologia; Remoção das seções Finalidade e Escopo; Adição de referência ao template de Especificação Suplementar do MCTIC | Gabriel Maciel | A revisar |
| 2.1 | 20/11/2025 | Adição da Tabela 2: Requisitos de Usabilidade - Versão 2.0, que readapta os requisitos da antiga tabela com requisitos não-funcionais elicitados | Gabriel Maciel | A revisar |

## Agradecimentos

> Agradecemos o suporte da ferramenta de Inteligência Artificial Generativa Google Gemini no desenvolvimento deste trabalho. Em conformidade com o Código de Conduta da Sociedade Brasileira de Computação (SBC), declaramos que a ferramenta foi utilizada como auxílio na revisão gramatical e estilística do texto, na sugestão de estrutura para seções específicas do artigo, bem como na formatação de tabelas e na descrição de figuras. Ressaltamos que os autores assumem total responsabilidade por todo o conteúdo apresentado, incluindo sua originalidade e precisão. A ferramenta não figura como autora desta publicação.
