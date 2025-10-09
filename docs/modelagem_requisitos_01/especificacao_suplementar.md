## Introdução
Conforme diretrizes do Ministério da Ciência, Tecnologia e Inovação [(MCTI, 2014)](#ref-mctic), a Especificação Suplementar é um artefato essencial no processo de engenharia de requisitos, destinado a capturar as exigências do sistema não abordadas nos casos de uso. Este documento detalha um vasto conjunto de requisitos não-funcionais e restrições globais, abrangendo desde requisitos legais e regulatórios até os atributos de qualidade que definem a operação do sistema, como usabilidade, confiabilidade, desempenho e suportabilidade. Além disso, a especificação também define restrições técnicas, como ambientes operacionais, requisitos de compatibilidade e limitações de design que devem ser consideradas no projeto.
### Especificação Suplementar (print da fonte)

<blockquote class="imgur-embed-pub" lang="en" data-id="UsIqinQ"><a href="https://imgur.com/UsIqinQ">View post on imgur.com</a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>
> *Autora: *Fernanda Vaz,2025 [MCTI, 2014](#ref-mctic)


## Finalidade
A Especificação Suplementar tem como objetivo documentar todos os requisitos não-funcionais do aplicativo DF no Ponto, incluindo requisitos de sistema, desempenho, confiabilidade, usabilidade, segurança e outros aspectos técnicos e regulatórios que não são capturados nos casos de uso.

## Escopo
Esta especificação aplica-se ao aplicativo móvel DF no Ponto, disponível para plataformas Android e iOS, destinado aos cidadãos do Distrito Federal para acesso a serviços públicos e informações governamentais.

## Usabilidade
A usabilidade representa o esforço necessário para utilizar o aplicativo e a avaliação individual desse uso por um conjunto específico de cidadãos. Abrange aspectos como facilidade de aprendizado, eficiência, memorização, prevenção de erros e satisfação do público-alvo, garantindo uma experiência intuitiva e acessível.
### Usabilidade (print da fonte)
<blockquote class="imgur-embed-pub" lang="en" data-id="G6KeKI6"><a href="https://imgur.com/G6KeKI6">View post on imgur.com</a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>
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

**Tabela 2:** RU - Requisito de Utilidade/Usabilidade

<span style="color:blue;">Autoria: Fernanda Vaz, 2025.</span>

## Confiabilidade
A confiabilidade expressa a capacidade do sistema de manter seu nível de desempenho sob condições estabelecidas durante um período determinado. Contempla aspectos como disponibilidade, maturidade, tolerância a falhas, recuperabilidade e estabilidade, assegurando que o aplicativo opere de forma consistente e resiliente.

### Confiabilidade (print da fonte)
<blockquote class="imgur-embed-pub" lang="en" data-id="K62bCH0"><a href="https://imgur.com/K62bCH0">View post on imgur.com</a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>

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

## Referências bibliográficas

- <a id="ref-mctic"></a>BRASIL. Ministério da Ciência, Tecnologia, Inovações e Comunicações. *Processo de Software do MCTIC: Documento Descritivo*. Brasília, DF: MCTIC, 2014. Disponível em: <https://ps.mctic.gov.br/MCTI-PS/workproducts/resources/PS_DocumentoDescritivo.pdf>. Acesso em: 7 out. 2025.

- <a id="ref-wcag"></a>GUIA WCAG. Disponível em: <https://guia-wcag.com>. Acesso em: 9 out. 2025.

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor |
|:------:|:-----------|:--------------------------------------------|:--------------|:----------------|
| 1.0 | 08/10/2025 | Criação da estrutura inicial do documento. | GABRIEL MACIEL| FERNANDA VAZ |
| 1.2 | 08/10/2025 | Adição de especificação suplementar inicial. | FERNANDA VAZ | GABRIEL MACIEL |