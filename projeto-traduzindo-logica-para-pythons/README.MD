🚀 Exercícios de Lógica: Tradução de Pseudocódigo para Python
Este repositório contém a resolução de uma atividade prática de lógica de programação. O objetivo principal foi traduzir algoritmos complexos descritos em pseudocódigo para a linguagem Python, aplicando conceitos de tipagem, estruturas de repetição e condicionais.

📋 Sobre a Atividade
A atividade consistiu na implementação de quatro funções distintas, cada uma simulando um sistema do mundo real:

Processamento de Vendas: Sistema que valida entradas, calcula subtotais e aplica descontos progressivos (5% e 10%) baseados no valor total da compra.

Análise de Clima: Algoritmo que monitora temperaturas semanais, calcula médias e identifica condições extremas (alertas de perigo para temperaturas acima de 45°C ou abaixo de -5°C).

Sistema de Notas: Gestor de desempenho acadêmico que processa médias e define o status do aluno (Aprovado, Recuperação ou Reprovado).

Simulador de Poupança: Cálculo de crescimento de capital com juros compostos e aportes mensais, incluindo monitoramento de metas financeiras.

🧠 Reflexões Técnicas
Durante o desenvolvimento, foram explorados pontos fundamentais da linguagem Python:

Manipulação de Tipos: A importância da conversão de tipos (casting), visto que a função input() retorna nativamente strings. Sem o uso de int() ou float(), operações aritméticas resultariam em erros de execução ou concatenações inesperadas.

Estruturas de Repetição: O uso da função range() para iterar sobre intervalos. No Python, para incluir o último valor de um intervalo (como em uma simulação de meses), utiliza-se a sintaxe range(inicio, fim + 1), devido à natureza exclusiva do limite superior da função.

Formatação de Saída: Implementação de f-strings para garantir que valores monetários e médias sejam exibidos com precisão decimal adequada.
