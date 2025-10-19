## Introdução
Conforme diretrizes do Ministério da Ciência, Tecnologia e Inovação [(MCTI, 2014)](#ref-mctic), a Especificação Suplementar é um artefato essencial no processo de engenharia de requisitos, destinado a capturar as exigências do sistema não abordadas nos casos de uso. Este documento detalha um vasto conjunto de requisitos não-funcionais e restrições globais, abrangendo desde requisitos legais e regulatórios até os atributos de qualidade que definem a operação do sistema, como usabilidade, confiabilidade, desempenho e suportabilidade. Além disso, a especificação também define restrições técnicas, como ambientes operacionais, requisitos de compatibilidade e limitações de design que devem ser consideradas no projeto.
### Especificação Suplementar (print da fonte)

<a href="https://ibb.co/5Zn0QsF"><img src="https://i.ibb.co/BkrphTN/image.png" alt="image" border="0"></a>
> *Autora: *Fernanda Vaz,2025 [MCTI, 2014](#ref-mctic)


## Finalidade
A Especificação Suplementar tem como objetivo documentar todos os requisitos não-funcionais do aplicativo DF no Ponto, incluindo requisitos de sistema, desempenho, confiabilidade, usabilidade, segurança e outros aspectos técnicos e regulatórios que não são capturados nos casos de uso.

## Escopo
Esta especificação aplica-se ao aplicativo móvel DF no Ponto, disponível para plataformas Android e iOS, destinado aos cidadãos do Distrito Federal para acesso a serviços públicos e informações governamentais.

## Usabilidade
A usabilidade representa o esforço necessário para utilizar o aplicativo e a avaliação individual desse uso por um conjunto específico de cidadãos. Abrange aspectos como facilidade de aprendizado, eficiência, memorização, prevenção de erros e satisfação do público-alvo, garantindo uma experiência intuitiva e acessível.
### Usabilidade (print da fonte)
<a href="https://ibb.co/CKFdJqMd"><img src="https://i.ibb.co/tp5fZSxf/image.png" alt="image" border="0"></a>
> *Autora: *Fernanda Vaz,2025 [MCTI, 2014](#ref-mctic)

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

**Tabela 2:** RU - Requisito de Utilidade/Usabilidade

<span style="color:blue;">Autoria: Fernanda Vaz e João Ramos, 2025.</span>

## Confiabilidade
A confiabilidade expressa a capacidade do sistema de manter seu nível de desempenho sob condições estabelecidas durante um período determinado. Contempla aspectos como disponibilidade, maturidade, tolerância a falhas, recuperabilidade e estabilidade, assegurando que o aplicativo opere de forma consistente e resiliente.

### Confiabilidade (print da fonte)
<a href="https://imgbb.com/"><img src="https://i.ibb.co/zVq9f94W/image.png" alt="image" border="0"></a>

| ID | Descrição |
|---|---|
| RC01 | Sistema deve operar sem falhas críticas. |
| RC02 | O sistema deve continuar operando mesmo com falhas parciais. |
| RC03 | Capacidade de recuperar dados e restabelecer operação após falhas. |
| RC04 | Funcionamento adequado em condições de rede instável com conectividade intermitente. |
| RC05 | Transações devem ser completadas integralmente ou revertidas sem estados parciais. |
| RC06 | Sistema deve detectar e reportar falhas automaticamente em logs. |
| RC07 | Dados devem permanecer consistentes entre diferentes sessões e dispositivos. |

**Tabela 3:** RC - Requisito de Confiabilidade

<span style="color:blue;">Autoria: Fernanda Vaz, 2025.</span>

## Desempenho
O desempenho define as características de eficiência do sistema, incluindo tempos de resposta para transações, a taxa de transferência de dados e a capacidade de usuários simultâneos que o sistema pode acomodar. Conforme as diretrizes, esta seção detalha os requisitos de performance e a utilização de recursos como memória e disco, garantindo que a aplicação opere dentro dos parâmetros esperados.

### Desempenho (print da fonte)
<a href="https://ibb.co/1t56SXb2"><img src="https://i.ibb.co/cSHLm8xT/Captura-de-tela-de-2025-09-28-23-39-57111111111.png" alt="Captura-de-tela-de-2025-09-28-23-39-57111111111" border="0"></a>

| ID | Descrição | Rastreabilidade |
|---|---|---|
| RD01 | O tempo de rastreio de um veículo em tempo real deve ser menor que 20 segundos. | RNF03 - Elicitação de Requisitos |
| RD02 | O tempo de carregamento da tela principal deve ser inferior a 3 segundos. | RNF10 - Elicitação de Requisitos: Entrevista (ENT17) |
| RD03 | O aplicativo deve apresentar baixo consumo de bateria e dados móveis durante o uso. | RNF06 - Elicitação de Requisitos |
| RD04 | O sistema deve suportar múltiplos usuários simultâneos sem apresentar lentidão ou degradação de performance. | RNF14 - Elicitação de Requisitos: Brainstorm (BRS15) |


**Tabela 4:** RD - Requisito de Desempenho

<span style="color:blue;">Autoria: Gabriel Maciel, 2025.</span>

## Requisitos do Sistema
Os Requisitos de Sistema definem todas as condições necessárias para suportar o aplicativo, garantindo sua correta operação em diferentes ambientes. Esta seção especifica as plataformas de hardware, os sistemas operacionais e as redes suportadas, assegurando que o produto esteja em conformidade com os padrões de plataforma aplicáveis (como Windows, Android, iOS, etc.) e interaja corretamente com outros softwares e periféricos definidos.

### Requisitos do Sistema (print da fonte)
<a href="https://ibb.co/RpNB5wnW"><img src="https://i.ibb.co/6R81dCh5/Captura-de-tela-de-2025-10-12-20-25-322222222222.png" alt="Captura-de-tela-de-2025-10-12-20-25-322222222222" border="0"></a>

| ID | Descrição |
|---|---|
| RS01 | A aplicação deve ser funcional e responsiva em navegadores web de dispositivos móveis(celulares) |


**Tabela 5:** RS - Requisito do Sistena

<span style="color:blue;">Autoria: Cauã Nicolas, 2025.</span>

## Segurança

A seção de Segurança descreve os requisitos para proteger o aplicativo e os dados dos usuários contra ameaças, ataques e acessos não autorizados. Ela cobre mecanismos de autenticação, autorização, criptografia, registro de eventos (logging) e monitoramento de incidentes.

| ID | Descrição |
|---|---|
| RSE01 | O sistema deve utilizar autenticação forte para todos os usuários (ex.: OAuth2 ou autenticação multifator para operações sensíveis). |
| RSE02 | Todas as comunicações entre cliente e servidor devem ser criptografadas usando TLS 1.2 ou superior. |
| RSE03 | Senhas e credenciais devem ser armazenadas usando hashing seguro (ex.: bcrypt, Argon2) com salt. |
| RSE04 | Deve existir um mecanismo de controle de sessão que invalide sessões inativas e permita logout remoto. |
| RSE05 | Registro (logging) de eventos de segurança (tentativas de login, alterações de privilégios, erros críticos) para auditoria. |
| RSE06 | Proteção contra ataques comuns (XSS, CSRF, injeção de SQL) aplicando validação e sanitização de entrada. |

**Tabela 6:** RSE - Requisito de Segurança

<span style="color:blue;">Autoria: Daniel Nunes Duarte, 2025.</span>

## Privacidade

Esta seção define os requisitos de privacidade e proteção de dados pessoais dos usuários do aplicativo, em conformidade com a legislação aplicável (por exemplo, LGPD) e melhores práticas de minimização de dados e transparência.

| ID | Descrição |
|---|---|
| RPV01 | Coleta de dados deve ser limitada ao mínimo necessário para a finalidade declarada e informada ao usuário. |
| RPV02 | Deve ser fornecido um termo de consentimento claro e acessível, permitindo que o usuário aceite ou recuse coleta de dados sensíveis. |
| RPV03 | Usuários devem ter mecanismos para visualizar, corrigir e solicitar exclusão de seus dados pessoais. |
| RPV04 | Dados pessoais armazenados devem ser criptografados em repouso quando tecnicamente viável. |
| RPV05 | Logs e backups que contenham dados pessoais devem ter acesso restrito e retenção limitada conforme política da organização. |
| RPV06 | Deve ser realizada uma avaliação de impacto sobre a proteção de dados (DPIA) para funcionalidades que processem dados sensíveis. |

**Tabela 7:** RPV - Requisito de Privacidade

<span style="color:blue;">Autoria: Daniel Nunes Duarte, 2025.</span>

## Referências bibliográficas
<a id="ref-mctic"></a>
>BRASIL. Ministério da Ciência, Tecnologia, Inovações e Comunicações. *Processo de Software do MCTIC: Documento Descritivo*. Brasília, DF: MCTIC, 2014. Disponível em: <https://ps.mctic.gov.br/MCTI-PS/workproducts/resources/PS_DocumentoDescritivo.pdf>. Acesso em: 7 out. 2025.

<a id="ref-wcag"></a>
>GUIA WCAG. Disponível em: <https://guia-wcag.com>. Acesso em: 9 out. 2025.

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor |
|:------:|:-----------|:--------------------------------------------|:--------------|:----------------|
| 1.0 | 08/10/2025 | Criação da estrutura inicial do documento. | Gabriel Maciel | Fernanda Vaz |
| 1.2 | 08/10/2025 | Adição de especificação suplementar inicial. | Fernanda Vaz | Gabriel Maciel |
| 1.3 | 12/10/2025 | Adição de componentes de Desempenho e Requisitos do Sistema para especificação suplementar. | João Ramos | Gabriel Maciel |
| 1.4 | 12/10/2025 | Adição de especificações suplementares (Segurança, Privacidade) | Daniel Nunes Duarte | Gabriel Maciel |
| 1.5 | 19/10/2025 | Adição de novos requisitos não-funcionais relacionados a desempenho | Gabriel Maciel | |

## Agradecimentos
>>Agradecemos o suporte da ferramenta de Inteligência Artificial Generativa Google Gemini no desenvolvimento deste trabalho. Em conformidade com o Código de Conduta da Sociedade Brasileira de Computação (SBC), declaramos que a ferramenta foi utilizada como auxílio na revisão gramatical e estilística do texto, na sugestão de estrutura para seções específicas do artigo, bem como na formatação de tabelas e na descrição de figuras. Ressaltamos que os autores assumem total responsabilidade por todo o conteúdo apresentado, incluindo sua originalidade e precisão. A ferramenta não figura como autora desta publicação.
