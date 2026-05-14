# 🧩 Desafio Unplugged: Dividir para Conquistar (Sistema de Troco)

## 📝 Descrição do Projeto
Este projeto apresenta a solução de um desafio teórico-prático de **Modularização** e **Pensamento Computacional**. O objetivo central é aplicar a estratégia de "Dividir para Conquistar" para resolver um problema cotidiano: a automação de um sistema de caixa que calcula o troco ideal utilizando o menor número possível de cédulas.

Diferente de uma abordagem monolítica ("código espaguete"), este projeto foca na **organização modular**. A lógica foi planejada de forma *unplugged* (papel e caneta), priorizando a lógica sobre a sintaxe e o design da solução antes da implementação.

## 🚀 Pilares do Pensamento Computacional Aplicados
Para a construção deste projeto, foram utilizados os quatro alicerces da computação:
* **Decomposição:** Quebra do problema complexo em pedaços menores e mais fáceis de gerenciar.
* **Reconhecimento de Padrões:** Identificação de problemas parecidos que já foram solucionados anteriormente.
* **Abstração:** Foco apenas nos detalhes importantes, ignorando informações irrelevantes.
* **Algoritmos:** Criação de passos e regras simples e ordenadas para resolver os sub-problemas.

## 🏗️ Arquitetura do Sistema (Modularização)
O sistema foi desenhado seguindo a anatomia de **funções (caixas pretas)**, garantindo processamento independente e proteção de dados através do escopo local.

### Módulos Principais (A Interface)
A estrutura segue o modelo de **Top-Down Design**, separando o programa principal de suas funções subordinadas:
* `validar_pagamento()`: Verifica se o valor pago é suficiente para cobrir o total.
* `calcular_troco()`: Retorna a diferença matemática bruta entre o valor pago e o total.
* `decompor_notas()`: Processa a divisão e restos para cada denominação de nota (100, 50, 10, 5 e 1).

## 📊 Critérios de Qualidade (Clean Code)
O projeto foi avaliado com base em diretrizes de código limpo:
1
