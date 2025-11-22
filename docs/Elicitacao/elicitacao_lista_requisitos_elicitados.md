# Tabela Geral de Requisitos Elicitados

## Introdução

Este documento apresenta a consolidação de todos os requisitos elicitados para o sistema de transporte público do Distrito Federal, obtidos através da aplicação de três técnicas distintas de elicitação: Análise de Documentos, Brainstorm e Entrevista.  
A Tabela 1 reúne de forma organizada os requisitos funcionais (RF) e não funcionais (RNF) identificados, categorizando-os e estabelecendo sua rastreabilidade às fontes originais.

Cada requisito está vinculado à técnica de elicitação que o originou, permitindo o rastreamento completo desde sua identificação até sua documentação final.  
Esta rastreabilidade é fundamental para garantir a validação dos requisitos e facilitar futuras manutenções e refinamentos do sistema.

### Tabela 1: Lista de requisitos elicitados de todas as técnicas

| **ID** | **Requisito** | **Tipo** | **Implementado** | **Rastreabilidade (origem)** |
|:------:|:--------------|:---------|:----------------:|:------------------------------|
| <a id="rf01"></a> RF01 | Exibir a localização dos ônibus em tempo real no mapa | Funcional | Sim | Análise de Documentos (RF01), Entrevista (ENT03) |
| <a id="rf02"></a> RF02 | Mostrar o tempo estimado de chegada do ônibus à parada | Funcional | Sim | Entrevista (ENT04) |
| <a id="rf03"></a> RF03 | Permitir planejamento de viagem (origem → destino) com rotas sugeridas | Funcional | Sim | Análise de Documentos (RF05) |
| <a id="rf04"></a> RF04 | Permitir pesquisa por linhas e rotas de ônibus | Funcional | Sim | Análise de Documentos (RF02), Entrevista (ENT01) |
| <a id="rf05"></a> RF05 | Apresentar horários de saída e chegada | Funcional | Sim | Entrevista (ENT02) |
| <a id="rf06"></a> RF06 | Oferecer mapa interativo com pontos e linhas | Funcional | Sim | Entrevista (ENT06) |
| <a id="rf07"></a> RF07 | Integrar informações de outros modais | Funcional | Sim | Análise de Documentos (RNI02), Brainstorm (BRS04) |
| <a id="rf08"></a> RF08 | Exibir informações de acessibilidade | Funcional | Sim | Entrevista (ENT16) |
| <a id="rf09"></a> RF09 | Indicar lotação do ônibus | Funcional | Não | Entrevista (ENT11), Brainstorm (BRS07) |
| <a id="rf10"></a> RF10 | Reportar lotação (colaborativo) | Funcional | Não | Entrevista (ENT11), Brainstorm (BRS03) |
| <a id="rf11"></a> RF11 | Notificação de chegada | Funcional | Sim | Análise (RNI01), ENT15, BRS05 |
| <a id="rf12"></a> RF12 | Alertas de atrasos e mudanças | Funcional | Sim | ENT05, BRS05 |
| <a id="rf13"></a> RF13 | Recarga de cartão | Funcional | Não | ENT07 |
| <a id="rf14"></a> RF14 | Integração com cartão | Funcional | Não | ENT07 |
| <a id="rf15"></a> RF15 | Histórico de viagens | Funcional | Não | Análise (RNI03) |
| <a id="rf16"></a> RF16 | Reportar problemas | Funcional | Não | ENT20 |
| <a id="rf17"></a> RF17 | Exibir preço da passagem | Funcional | Sim | ENT23 |
| <a id="rf18"></a> RF18 | Listar linhas por parada | Funcional | Sim | — |
| <a id="rf19"></a> RF19 | Versão web leve | Funcional | Sim | BRS17 |
| <a id="rf20"></a> RF20 | Botão de pânico | Funcional | Não | — |
| <a id="rf21"></a> RF21 | Alertas de trânsito | Funcional | Sim | BRS12 |
| <a id="rf22"></a> RF22 | Compartilhar trajeto | Funcional | Não | — |
| <a id="rf23"></a> RF23 | Exibir assentos | Funcional | Não | — |
| <a id="rf24"></a> RF24 | Favoritar linhas ou paradas | Funcional | Sim | ENT14 |
| <a id="rf25"></a> RF25 | Exibir informações em regiões afastadas | Funcional | Não | ENT08 |
| <a id="rf26"></a> RF26 | Filtrar ônibus por empresa | Funcional | Sim | Análise (RF03) |
| <a id="rf27"></a> RF27 | Mostrar veículos em operação | Funcional | Sim | Análise (RF04) |
| <a id="rf28"></a> RF28 | Avaliação do serviço | Funcional | Não | Análise (RNI04) |
| <a id="rf29"></a> RF29 | Gamificação | Funcional | Não | BRS01 |
| <a id="rf30"></a> RF30 | Previsão inteligente (ML) | Funcional | Sim | BRS02 |
| <a id="rf31"></a> RF31 | Recompensas sustentáveis | Funcional | Não | BRS09 |
| <a id="rf32"></a> RF32 | Relatórios ambientais | Funcional | Não | BRS11 |
| <a id="rf33"></a> RF33 | Comandos de voz | Funcional | Não | BRS14 |
| <a id="rf34"></a> RF34 | Integração com assistentes | Funcional | Não | BRS16 |
| <a id="rf35"></a> RF35 | Rastreamento de múltiplas linhas | Funcional | Não | ENT12 |
| <a id="rf36"></a> RF36 | Suporte multilíngue | Funcional | Não | ENT22 |
| <a id="rf37"></a> RF37 | Cadastro e autenticação | Funcional | Não | BRS18 |
| <a id="rf38"></a> RF38 | Linhas com ar-condicionado | Funcional | Não | BRS20 |
| <a id="rnf01"></a> RNF01 | Informações precisas | Não Funcional | Sim | ENT09 |
| <a id="rnf02"></a> RNF02 | Rastreamento confiável | Não Funcional | Sim | ENT13 |
| <a id="rnf03"></a> RNF03 | Atualização ≤ 20s | Não Funcional | Não | ENT23 |
| <a id="rnf04"></a> RNF04 | Interface acessível | Não Funcional | Não | ENT10, BRS08 |
| <a id="rnf05"></a> RNF05 | Notificações configuráveis | Não Funcional | Sim | BRS18 |
| <a id="rnf06"></a> RNF06 | Baixo consumo de bateria | Não Funcional | Sim | — |
| <a id="rnf07"></a> RNF07 | Compatível com Android/iOS | Não Funcional | Sim | ENT19 |
| <a id="rnf08"></a> RNF08 | Proteção contra reportes falsos | Não Funcional | Não | — |
| <a id="rnf09"></a> RNF09 | Proteção LGPD | Não Funcional | Sim | ENT21 |
| <a id="rnf10"></a> RNF10 | Tela principal < 3s | Não Funcional | Não | ENT17 |
| <a id="rnf11"></a> RNF11 | Funcionamento offline | Não Funcional | Não | RNI05, ENT18, BRS06 |
| <a id="rnf12"></a> RNF12 | Pagamento seguro | Não Funcional | Não | BRS10 |
| <a id="rnf13"></a> RNF13 | Disponibilidade ≥ 98% | Não Funcional | Sim | — |
| <a id="rnf14"></a> RNF14 | Suporte a múltiplos usuários | Não Funcional | Sim | BRS15 |
| <a id="rnf15"></a> RNF15 | Personalização da interface | Não Funcional | Não | BRS13 |


*Tabela 1: Lista de requisitos elicitados de todas as técnicas - Autoria: Gabriel Maciel, 2025*

---

## Histórico de Versões

| **Versão** | **Data** | **Descrição** | **Autor(es)** | **Revisor(es)** |
|:-----------:|:--------:|:--------------|:---------------|:----------------|
| **1.0** | 18/10/2025 | Criação inicial da Tabela Geral de Requisitos Elicitados; consolidação das três técnicas | [Gabriel Maciel](https://github.com/GabrielMacielBR) | [João Gabriel](https://github.com/JoaoComTil) |
| **1.1** | 27/10/2025 | Adição de links bidirecionais para o documento `forward.md` | [Fernanda Vaz](https://github.com/Fernandavazgit1) | [Cauã Nicolas](https://github.com/cauanicolas) |
| **1.2** | 19/11/2025 | Adicão coluna de Requisito Implementado | [João Ramos](https://github.com/Joaolramos) | [Gabriel Maciel](https://github.com/GabrielMacielBR) |

