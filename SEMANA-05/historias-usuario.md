# Documentação de Requisitos: Projeto Marketplace Manager

**Data:** 23/04/2026  
**Papel (Analista/Dev):** David Gimenes Ribeiro Filho  
**Contexto:** Atividade Prática - Semana 05

## 1. Descrição do Aplicativo
O **Marketplace Manager** é um aplicativo mobile focado em microempreendedores que vendem em múltiplas plataformas (Mercado Livre, Shopee e Amazon). O problema central relatado pelo cliente é a dificuldade de sincronizar estoques e responder mensagens de clientes de forma centralizada, evitando penalidades nas plataformas por demora ou falta de produto.

---

## 2. Aplicação do Método CARD
Utilizamos o método para organizar o fluxo de trabalho das histórias:

* **C (Capturar):** Ouvimos as dores do cliente sobre a gestão caótica de estoque e prazos de resposta.
* **A (Aprovar):** Validamos com o cliente quais funcionalidades eram prioritárias para o MVP (Mínimo Produto Viável).
* **R (Refinar):** Quebramos as necessidades brutas em histórias de usuário claras e técnicas.
* **D (Dispensar detalhamento):** Conforme a instrução da atividade, focamos na essência da funcionalidade sem o detalhamento técnico profundo neste momento.

---

## 3. Histórias de Usuário (User Stories)

| ID | História de Usuário | Prioridade |
| :--- | :--- | :--- |
| **US01** | Como vendedor, quero receber notificações de vendas de todos os marketplaces em uma única tela para que eu possa agilizar a expedição. | Alta |
| **US02** | Como vendedor, quero que o estoque seja baixado automaticamente em todas as plataformas quando uma venda ocorrer em uma delas para evitar vendas sem estoque. | Crítica |
| **US03** | Como vendedor, quero responder perguntas de clientes do Mercado Livre diretamente pelo app para manter meu índice de resposta abaixo de 10 minutos. | Alta |
| **US04** | Como vendedor, quero visualizar um gráfico de faturamento diário consolidado para entender a saúde financeira do meu negócio. | Média |

---

## 4. Critérios de Aceite (Exemplo US02)
* O sistema deve sincronizar em menos de 30 segundos após a confirmação do pagamento.
* Caso a API de uma plataforma esteja fora do ar, o sistema deve tentar novamente a cada 1 minuto e notificar o usuário.

---

## 5. Conclusão
O uso do método CARD permitiu filtrar o que é essencial para o sucesso do cliente, transformando desejos vagos em entregas técnicas mensuráveis. O projeto seguirá para a fase de prototipagem de baixa fidelidade.