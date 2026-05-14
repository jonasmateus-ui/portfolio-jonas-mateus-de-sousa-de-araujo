# 🧩 Desafio Unplugged: Dividir para Conquistar (Sistema de Troco)

## 📝 Descrição do Projeto
[cite_start]Este projeto apresenta a solução de um desafio teórico-prático de **Modularização** e **Pensamento Computacional**[cite: 2]. [cite_start]O objetivo central é aplicar a estratégia de "Dividir para Conquistar" para resolver um problema cotidiano: a automação de um sistema de caixa que calcula o troco ideal utilizando o menor número possível de cédulas[cite: 1, 86].

[cite_start]Diferente de uma abordagem monolítica ("código espaguete"), este projeto foca na **organização modular**[cite: 17, 18]. [cite_start]A lógica foi planejada de forma *unplugged* (papel e caneta), priorizando a lógica sobre a sintaxe e o design da solução antes da implementação[cite: 45, 105].

## 🚀 Pilares do Pensamento Computacional Aplicados
[cite_start]Para a construção deste projeto, foram utilizados os quatro alicerces da computação[cite: 5, 6]:
* [cite_start]**Decomposição:** Quebra do problema complexo em pedaços menores e mais fáceis de gerenciar[cite: 7, 8].
* [cite_start]**Reconhecimento de Padrões:** Identificação de problemas parecidos que já foram solucionados anteriormente[cite: 9].
* [cite_start]**Abstração:** Foco apenas nos detalhes importantes, ignorando informações irrelevantes[cite: 11, 12].
* [cite_start]**Algoritmos:** Criação de passos e regras simples e ordenadas para resolver os sub-problemas[cite: 15].

## 🏗️ Arquitetura do Sistema (Modularização)
[cite_start]O sistema foi desenhado seguindo a anatomia de **funções (caixas pretas)**, garantindo processamento independente e proteção de dados através do escopo local[cite: 32, 37].

### Módulos Principais (A Interface)
[cite_start]A estrutura segue o modelo de **Top-Down Design**, separando o programa principal de suas funções subordinadas[cite: 53, 60]:
* [cite_start]`validar_pagamento()`: Verifica se o valor pago é suficiente para cobrir o total[cite: 90].
* [cite_start]`calcular_troco()`: Retorna a diferença matemática bruta entre o valor pago e o total[cite: 90].
* [cite_start]`decompor_notas()`: Processa a divisão e restos para cada denominação de nota (100, 50, 10, 5 e 1)[cite: 86, 91].

## 📊 Critérios de Qualidade (Clean Code)
[cite_start]O projeto foi avaliado com base em diretrizes de código limpo[cite: 93]:
1. [cite_start]**Princípio DRY (Don't Repeat Yourself):** A lógica vive em um único lugar, evitando repetições desnecessárias[cite: 21, 22].
2. [cite_start]**Alta Coesão:** Cada função realiza estritamente uma única operação, descrita em uma única frase[cite: 25, 26].
3. [cite_start]**Baixo Acoplamento:** O sistema utiliza parâmetros e retornos para manter a independência entre os módulos[cite: 29, 30, 98].
4. [cite_start]**Clareza e Abstração:** A função principal conta a história do fluxo do programa de forma legível[cite: 99, 100].

## 🛠️ Tecnologias e Ferramentas
* [cite_start]**Metodologia:** Aprendizagem Unplugged (Sem telas/compiladores)[cite: 49, 103].
* [cite_start]**Planejamento:** Fluxograma detalhado e Pseudocódigo estruturado[cite: 51, 52].
* [cite_start]**Ferramentas:** Caderno, caneta e lógica computacional[cite: 47].

---
[cite_start]*Este projeto foi desenvolvido sob a orientação do Prof. Diego Marques de Carvalho (Departamento de Ciência da Computação).* [cite: 3]
