# Especificação de Requisitos: Marketplace Manager

**Componente:** Engenharia de Software  
**Data:** 23/04/2026

## 1. Requisitos Funcionais (RF)
| ID | Descrição |
| :--- | :--- |
| **RF1** | O sistema deve integrar-se via API com Mercado Livre, Shopee e Amazon. |
| **RF2** | O sistema deve centralizar todas as notificações de vendas em um feed único. |
| **RF3** | O sistema deve atualizar automaticamente o saldo de estoque em todas as plataformas conectadas após uma venda. |
| **RF4** | O sistema deve permitir a resposta de mensagens e perguntas de clientes sem sair da aplicação. |
| **RF5** | O sistema deve gerar relatórios gráficos de faturamento por canal de venda. |

## 2. Requisitos Não Funcionais (RNF)
| ID | Descrição |
| :--- | :--- |
| **RNF1** | **Disponibilidade:** O sistema de sincronização de estoque deve operar 24/7. |
| **RNF2** | **Desempenho:** A sincronização de estoque entre plataformas deve ocorrer em no máximo 30 segundos. |
| **RNF3** | **Segurança:** As credenciais de API dos marketplaces devem ser armazenadas com criptografia AES-256. |
| **RNF4** | **Usabilidade:** A interface mobile deve seguir diretrizes de acessibilidade e ser responsiva. |