# Desafio Criativo DIO - Extraindo Insights de Feedbacks Bancários

Este repositório contém a resolução do Desafio Criativo proposto pela DIO. O objetivo é construir um prompt estruturado para ajudar uma inteligência artificial a analisar comentários de clientes de um banco fictício e gerar melhorias.

---

## Passo 1: Definição da Intenção

* **O que a IA deve analisar:** Quero que a IA analise comentários de clientes sobre o uso do cartão de crédito e do suporte via chat.
* **Quem vai usar o resultado:** O resultado será usado pela equipe de Atendimento ao Cliente.
* **Qual decisão o resultado vai apoiar:** Vai ajudar a decidir quais problemas do aplicativo de cartões precisam ser corrigidos primeiro e como melhorar as respostas do chat.
* **Formato da entrega:** Uma lista simples com os 3 problemas mais falados e 3 sugestões de melhorias rápidas.
* **Critério de qualidade:** O resultado será bom se for fácil de ler e trouxer pontos que realmente ajudam a resolver a vida do cliente.

---

## Passo 2: Contexto e Restrições

* **Contexto:** Estou trabalhando com feedbacks de clientes bancários focados em problemas para desbloquear o cartão de crédito e na demora do atendimento pelo chat.
* **Dados disponíveis:** A base de dados fake contém apenas o texto do comentário do cliente e a nota que ele deu de 1 a 5.
* **Critérios de análise:** A IA deve separar os comentários entre "Problemas com o Cartão" e "Problemas com o Chat", além de classificar se a reclamação é urgente ou calma.

**Cuidados e restrições:**
1. Use apenas os comentários que eu enviar.
2. Não invente reclamações ou dados que não existem no texto.
3. Se o cliente colocou o nome ou número de conta, apague para proteger a privacidade.
4. Escreva com uma linguagem simples, sem palavras muito difíceis.

---

## Prompt Final Gerado

Abaixo está o comando final pronto para ser colado em qualquer IA (como ChatGPT ou Gemini):

> **Prompt:** "Atue como um analista de atendimento bancário iniciante. Quero que você analise uma lista de comentários de clientes sobre problemas com cartão de crédito e atendimento no chat. Separe os comentários em dois grupos (Cartão e Chat) e indique quais são urgentes. Ao final, me entregue uma lista simples com os 3 problemas que mais aparecem e dê 3 sugestões fáceis para resolver isso. Não invente dados e ignore qualquer informação pessoal como nomes ou números. Use um tom simples e direto."
