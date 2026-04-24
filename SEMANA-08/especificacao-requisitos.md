# Documento de Especificação de Requisitos de Software (SRS)
**Projeto:** Marketplace Manager Pro  
**Versão:** 1.0  
**Data:** 23/04/2026  
**Responsável:** David Gimenes Ribeiro Filho  

## 1. Escopo do Projeto
O sistema visa centralizar a operação de vendedores multi-canal (Mercado Livre, Shopee e Amazon), automatizando a gestão de estoque e otimizando o SEO de anúncios.

### 1.1. O que o sistema IRÁ desenvolver (In-Scope):
* Integração via API com os três principais marketplaces do Brasil.
* Dashboard de faturamento consolidado.
* Sincronização automática de estoque entre contas.
* Sugestão de títulos otimizados via IA.

### 1.2. O que o sistema NÃO irá desenvolver (Out-of-Scope):
* Emissão de Notas Fiscais (ERP externo necessário).
* Gestão de logística física/entrega própria.
* Integração com lojas físicas (PDV).

## 2. Requisitos Funcionais (RF)
| ID | Nome | Descrição | Prioridade |
| :--- | :--- | :--- | :--- |
| **RF1** | Sincronização de Estoque | Ao vender em um canal, o saldo deve ser atualizado nos demais. | Essencial |
| **RF2** | Central de Mensagens | Interface única para responder perguntas de clientes de todos os canais. | Alta |
| **RF3** | Otimizador de SEO | Sugerir palavras-chave "Long-tail" para melhorar o ranqueamento. | Média |
| **RF4** | Gestão de Preços em Lote | Alterar preços de um SKU em todos os canais simultaneamente. | Alta |

## 3. Requisitos Não Funcionais (RNF)
| ID | Categoria | Descrição |
| :--- | :--- | :--- |
| **RNF1** | Performance | A sincronização de estoque deve ocorrer em até 20 segundos. |
| **RNF2** | Segurança | Autenticação via OAuth 2.0 para acesso às APIs dos Marketplaces. |
| **RNF3** | Disponibilidade | O sistema deve manter 99.5% de uptime (SLA). |
| **RNF4** | Arquitetura | Desenvolvimento em Microserviços para facilitar a escalabilidade. |

## 4. Arquitetura do Sistema
O sistema será baseado em uma arquitetura de **Microserviços** hospedada na AWS, utilizando:
* **Frontend:** React (Web) e React Native (Mobile).
* **Backend:** Node.js/Typescript para processamento assíncrono.
* **Banco de Dados:** PostgreSQL (Dados Relacionais) e Redis (Cache de estoque).