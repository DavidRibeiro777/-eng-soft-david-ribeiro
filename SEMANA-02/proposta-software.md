# Proposta de Intervenção Técnica e Ética: O Dilema da IA Contratadora

**Curso:** Tecnologia em Sistemas para Internet  
**Módulo:** 3  
**Data:** 03/03/2026  
**Componente Curricular:** Engenharia de Software  
**Professor:** Gaio B. Oliveira  
**Time:** [DAVID GIMENES RIBEIRO FILHO
]

## 1. Introdução e Análise do Cenário
O desenvolvimento de sistemas de IA para recrutamento enfrenta um desafio crítico: a reprodução de vieses históricos. No cenário atual, a startup encontra-se em um impasse entre a pressão comercial de investidores e a responsabilidade ética e legal de entregar um produto justo e em conformidade com a **LGPD (Lei Geral de Proteção de Dados)**.

## 2. Fundamentação Ética (ACM/IEEE & Sommerville)
Nossa proposta baseia-se nos princípios de Engenharia de Software descritos por Sommerville e no Código de Ética da ACM/IEEE:

* **Cláusula 1.03 (ACM/IEEE):** Determina que o software só deve ser aprovado se houver crença fundamentada de que ele é seguro e atende às especificações, sem degradar a qualidade de vida. Lançar uma IA com viés discriminatório viola este princípio fundamental.
* **Cláusula 3.01 (ACM/IEEE):** Obriga o profissional a garantir que o produto atenda aos mais altos padrões profissionais. Ocultar um erro de viés para acelerar o lançamento é uma falha de integridade técnica.
* **Responsabilidade Profissional (Sommerville):** Como engenheiros, temos a obrigação de conhecer a lei e garantir que o software não seja usado de forma discriminatória contra grupos minoritários.

## 3. Comparativo de Soluções Técnicas

| Solução | Prós | Contras | Risco Jurídico (LGPD) |
| :--- | :--- | :--- | :--- |
| **Lançar Imediatamente** | Receita rápida; vantagem competitiva. | Discriminação algorítmica; danos à imagem. | **Altíssimo** (Art. 20 - Revisão Humana). |
| **Human-in-the-loop** | Reduz a autonomia perigosa da IA; maior justiça. | Processo de triagem mais lento para o cliente. | **Baixo** (Decisão não é 100% automatizada). |
| **Auditoria de Dados** | Corrige a raiz do problema (viés estatístico). | Atraso de 4 semanas no lançamento. | **Mínimo** (Prevenção de danos). |
| **Toolkit de XAI** | Transparência total no processo de rejeição. | Exposição da lógica interna (Propriedade Intelectual). | **Excelente** (Cumpre dever de transparência). |

## 4. Proposta de Intervenção Selecionada
Para atingir a **Excelência Dev**, o time propõe uma abordagem híbrida que equilibra ética, técnica e viabilidade de negócio:

1.  **Auditoria e Limpeza de Dados (Prioridade 1):** Optamos pelo atraso de 4 semanas. Financeiramente, o custo de um mês de atraso é significativamente menor do que multas da ANPD (que podem chegar a 2% do faturamento) e processos judiciais coletivos.
2.  **Implementação de Camada XAI (Explicabilidade):** Adotaremos a transparência. Se um candidato for rejeitado, o sistema deve fornecer os critérios técnicos utilizados, permitindo o direito de defesa e revisão conforme a lei.
3.  **Monitoramento Pós-Lançamento:** Criação de um dashboard interno para monitorar desvios demográficos em tempo real após a entrega.

## 5. Conclusão
A integridade de um Engenheiro de Software não é negociável. Adiar o lançamento em 4 semanas para garantir a equidade do algoritmo não é apenas uma escolha ética, mas uma estratégia financeira inteligente para evitar a falência da startup por riscos jurídicos previsíveis.