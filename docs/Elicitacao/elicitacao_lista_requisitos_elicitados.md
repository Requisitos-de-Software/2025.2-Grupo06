# Tabela Geral de Requisitos Elicitados

## Introdução

Este documento apresenta a consolidação de todos os requisitos elicitados para o sistema de transporte público do Distrito Federal, obtidos através da aplicação de três técnicas distintas de elicitação: Análise de Documentos, Brainstorm e Entrevista.  
A Tabela 1 reúne de forma organizada os requisitos funcionais (RF) e não funcionais (RNF) identificados, categorizando-os e estabelecendo sua rastreabilidade às fontes originais.

Cada requisito está vinculado à técnica de elicitação que o originou, permitindo o rastreamento completo desde sua identificação até sua documentação final.  
Esta rastreabilidade é fundamental para garantir a validação dos requisitos e facilitar futuras manutenções e refinamentos do sistema.

### Tabela 1: Lista de requisitos elicitados de todas as técnicas
| **ID** | **Requisito** | **Tipo** | **Implementado** | **Rastreabilidade (origem)** |
|:------:|:---------------|:----------|:----------------:|:------------------------------|
| <a id="rf01"></a>  [RF01](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf01)  | Exibir a localização dos ônibus em tempo real no mapa | Funcional | Sim | Análise de Documentos (RF01), Entrevista (ENT03) |
|  <a id="rf02"></a> [RF02](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf02) | Mostrar o tempo estimado de chegada do ônibus à parada | Funcional | Sim | Entrevista (ENT04) |
| <a id="rf03"></a>  [RF03](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf03) | Permitir planejamento de viagem (origem → destino) com rotas sugeridas | Funcional | Sim | Análise de Documentos (RF05) |
| [RF04](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf04) | Permitir pesquisa por linhas e rotas de ônibus | Funcional | Sim | Análise de Documentos (RF02), Entrevista (ENT01) |
| [RF05](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf05) | Apresentar horários de saída e chegada | Funcional | Sim | Entrevista (ENT02) |
| [RF06](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf06) | Oferecer mapa interativo com pontos e linhas | Funcional | Sim | Entrevista (ENT06) |
| [RF07](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf07) | Integrar informações de outros modais | Funcional | Sim | Análise de Documentos (RNI02), Brainstorm (BRS04) |
| [RF08](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf08) | Exibir informações de acessibilidade | Funcional | Sim | Entrevista (ENT16) |
| [RF09](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf09) | Indicar lotação do ônibus | Funcional | Não | Entrevista (ENT11), Brainstorm (BRS07) |
| [RF10](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf10) | Reportar lotação (colaborativo) | Funcional | Não | Entrevista (ENT11), Brainstorm (BRS03) |
| [RF11](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf11) | Notificação de chegada | Funcional | Sim | Análise (RNI01), ENT15, BRS05 |
| [RF12](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf12) | Alertas de atrasos e mudanças | Funcional | Sim | ENT05, BRS05 |
| [RF13](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf13) | Recarga de cartão | Funcional | Não | ENT07 |
| [RF14](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf14) | Integração com cartão | Funcional | Não | ENT07 |
| [RF15](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf15) | Histórico de viagens | Funcional | Não | Análise (RNI03) |
| [RF16](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf16) | Reportar problemas | Funcional | Não | ENT20 |
| [RF17](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf17) | Exibir preço da passagem | Funcional | Sim | ENT23 |
| [RF18](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf18) | Listar linhas por parada | Funcional | Sim | — |
| [RF19](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf19) | Versão web leve | Funcional | Sim | BRS17 |
| [RF20](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf20) | Botão de pânico | Funcional | Não | — |
| [RF21](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf21) | Alertas de trânsito | Funcional | Sim | BRS12 |
| [RF22](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf22) | Compartilhar trajeto | Funcional | Não | — |
| [RF23](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf23) | Exibir assentos | Funcional | Não | — |
| [RF24](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf24) | Favoritar linhas ou paradas | Funcional | Sim | ENT14 |
| [RF25](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf25) | Exibir informações em regiões afastadas | Funcional | Não | ENT08 |
| [RF26](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf26) | Filtrar ônibus por empresa | Funcional | Sim | Análise (RF03) |
| [RF27](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf27) | Mostrar veículos em operação | Funcional | Sim | Análise (RF04) |
| [RF28](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf28) | Avaliação do serviço | Funcional | Não | Análise (RNI04) |
| [RF29](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf29) | Gamificação | Funcional | Não | BRS01 |
| [RF30](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf30) | Previsão inteligente (ML) | Funcional | Sim | BRS02 |
| [RF31](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf31) | Recompensas sustentáveis | Funcional | Não | BRS09 |
| [RF32](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf32) | Relatórios ambientais | Funcional | Não | BRS11 |
| [RF33](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf33) | Comandos de voz | Funcional | Não | BRS14 |
| [RF34](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf34) | Integração com assistentes | Funcional | Não | BRS16 |
| [RF35](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf35) | Rastreamento de múltiplas linhas | Funcional | Não | ENT12 |
| [RF36](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf36) | Suporte multilíngue | Funcional | Não | ENT22 |
| [RF37](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf37) | Cadastro e autenticação | Funcional | Não | BRS18 |
| [RF38](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rf38) | Linhas com ar-condicionado | Funcional | Não | BRS20 |
| [RNF01](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rnf01) | Informações precisas | Não Funcional | Sim | ENT09 |
| [RNF02](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rnf02) | Rastreamento confiável | Não Funcional | Sim | ENT13 |
| [RNF03](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rnf03) | Atualização ≤ 20s | Não Funcional | Não | ENT23 |
| [RNF04](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rnf04) | Interface acessível | Não Funcional | Não | ENT10, BRS08 |
| [RNF05](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rnf05) | Notificações configuráveis | Não Funcional | Sim | BRS18 |
| [RNF06](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rnf06) | Baixo consumo de bateria | Não Funcional | Sim | — |
| [RNF07](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rnf07) | Compatível com Android/iOS | Não Funcional | Sim | ENT19 |
| [RNF08](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rnf08) | Proteção contra reportes falsos | Não Funcional | Não | — |
| [RNF09](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rnf09) | Proteção LGPD | Não Funcional | Sim | ENT21 |
| [RNF10](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rnf10) | Tela principal < 3s | Não Funcional | Não | ENT17 |
| [RNF11](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rnf11) | Funcionamento offline | Não Funcional | Não | RNI05, ENT18, BRS06 |
| [RNF12](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rnf12) | Pagamento seguro | Não Funcional | Não | BRS10 |
| [RNF13](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rnf13) | Disponibilidade ≥ 98% | Não Funcional | Sim | — |
| <a id="rnf14"></a> [RNF14](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rnf14) | Suporte a múltiplos usuários | Não Funcional | Sim | BRS15 |
| [RNF15](../Elicitacao/elicitacao_lista_requisitos_elicitados.md#rnf15) | Personalização da interface | Não Funcional | Não | BRS13 |


*Tabela 1: Lista de requisitos elicitados de todas as técnicas - Autoria: Gabriel Maciel, 2025*

---

## Histórico de Versões

| **Versão** | **Data** | **Descrição** | **Autor(es)** | **Revisor(es)** |
|:-----------:|:--------:|:--------------|:---------------|:----------------|
| **1.0** | 18/10/2025 | Criação inicial da Tabela Geral de Requisitos Elicitados; consolidação das três técnicas | [Gabriel Maciel](https://github.com/GabrielMacielBR) | [João Gabriel](https://github.com/JoaoComTil) |
| **1.1** | 27/10/2025 | Adição de links bidirecionais para o documento `forward.md` | [Fernanda Vaz](https://github.com/Fernandavazgit1) | [Cauã Nicolas](https://github.com/cauanicolas) |
| **1.2** | 19/11/2025 | Adicão coluna de Requisito Implementado | João Ramos | Gabriel Maciel |

