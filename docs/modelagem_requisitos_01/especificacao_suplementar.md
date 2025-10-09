## Introdução
Este documento apresenta a Especificação Suplementar do aplicativo DF no Ponto, complementando os casos de uso com requisitos não-funcionais essenciais para o desenvolvimento e operação da solução. A Especificação Suplementar é um documento que captura todos os requisitos de um sistema de software que não são facilmente documentados nos casos de uso ou histórias de usuário.

## Finalidade
A Especificação Suplementar tem como objetivo documentar todos os requisitos não-funcionais do aplicativo DF no Ponto, incluindo requisitos de sistema, desempenho, confiabilidade, usabilidade, segurança e outros aspectos técnicos e regulatórios que não são capturados nos casos de uso.

## Escopo
Esta especificação aplica-se ao aplicativo móvel DF no Ponto, disponível para plataformas Android e iOS, destinado aos cidadãos do Distrito Federal para acesso a serviços públicos e informações governamentais.

### Funcionalidade
A funcionalidade refere-se à capacidade do sistema de fornecer funções que atendam às necessidades explícitas e implícitas dos cidadãos e do GDF. Engloba aspectos como precisão, adequação, interoperabilidade e segurança das operações realizadas pelo aplicativo DF no Ponto.

| ID | Descrição |
|---|---|
| RF01 | O sistema deve garantir a exatidão de todas as informações exibidas, sincronizando com as bases de dados oficiais. |
| RF02 | O aplicativo deve manter a integridade dos dados durante todas as operações de leitura e escrita. |
| RF03 | Todas as funcionalidades devem estar em conformidade com as especificações dos casos de uso aprovados. |
| RF04 | O sistema deve integrar-se adequadamente com todos os sistemas legados do GDF. |
| RF05 | Mecanismos de autenticação e autorização devem funcionar corretamente em todas as transações. |

**Tabela 1:** RF - Requisito de Funcionalidade

<span style="color:blue;">Autoria: Fernanda Vaz, 2025.</span>

### Utilidade (Usabilidade)
A usabilidade representa o esforço necessário para utilizar o aplicativo e a avaliação individual desse uso por um conjunto específico de cidadãos. Abrange aspectos como facilidade de aprendizado, eficiência, memorização, prevenção de erros e satisfação do público-alvo, garantindo uma experiência intuitiva e acessível.

| ID | Descrição |
|---|---|
| RU01 | Cidadãos devem conseguir utilizar funcionalidades básicas sem treinamento prévio. |
| RU02 | Operações frequentes devem ser realizadas rapidamente com máximo de 2 toques. |
| RU03 | Interface deve ser facilmente memorável para operadores ocasionais. |
| RU04 | A interface deve ser agradável e satisfatória de usar. |
| RU05 | Suporte a leitores de tela e ajuste de contraste conforme WCAG 2.1. |
| RU06 | Mensagens de erro e confirmação devem ser claras e objetivas. |
| RU07 | Padrões visuais e de interação consistentes em todo o aplicativo. |
| RU08 | Permitir ajustes básicos de preferências visuais (tema, fonte, notificações). |

**Tabela 2:** RU - Requisito de Utilidade/Usabilidade

<span style="color:blue;">Autoria: Fernanda Vaz, 2025.</span>

### Confiabilidade
A confiabilidade expressa a capacidade do sistema de manter seu nível de desempenho sob condições estabelecidas durante um período determinado. Contempla aspectos como disponibilidade, maturidade, tolerância a falhas, recuperabilidade e estabilidade, assegurando que o aplicativo opere de forma consistente e resiliente.

| ID | Descrição |
|---|---|
| RC01 | Sistema deve operar sem falhas críticas. |
| RC02 | O sistema deve continuar operando mesmo com falhas parciais. |
| RC03 | Capacidade de recuperar dados e restabelecer operação após falhas em até 3 horas. |
| RC04 | Funcionamento adequado em condições de rede instável com conectividade intermitente. |
| RC05 | Transações devem ser completadas integralmente ou revertidas sem estados parciais. |
| RC06 | Sistema deve detectar e reportar falhas automaticamente em logs. |
| RC07 | Dados devem permanecer consistentes entre diferentes sessões e dispositivos. |

**Tabela 3:** RC - Requisito de Confiabilidade

<span style="color:blue;">Autoria: Fernanda Vaz, 2025.</span>

## Bibliografia
> BRASIL. Ministério da Ciência, Tecnologia, Inovações e Comunicações. Processo de Software do MCTIC: Documento Descritivo. Brasília, DF: MCTIC, 2014. Disponível em: https://ps.mctic.gov.br/MCTI-PS/workproducts/resources/PS_DocumentoDescritivo.pdf. Acesso em: 7 out. 2025.

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor |
|:------:|:-----------|:--------------------------------------------|:--------------|:----------------|
| 1.0 | 08/10/2025 | Criação da estrutura inicial do documento. | GABRIEL MACIEL| FERNANDA VAZ |
| 1.2 | 08/10/2025 | Adição de especificação suplementar inicial. | FERNANDA VAZ | GABRIEL MACIEL |