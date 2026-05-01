# 🛡️ Algoritmo de Auditoria de Dados de Vendas

## 📝 Descrição do Projeto
Este projeto foi desenvolvido para atuar como uma camada de segurança em transações financeiras, utilizando Python para identificar discrepâncias de dados (**outliers**) que podem distorcer médias e mascarar erros ou fraudes[cite: 2, 3]. 

O foco principal é a aplicação de **Lógica de Negócio** voltada para auditoria, estabelecendo uma "Margem de Tolerância" — o limite de erro aceitável sem comprometer a visão geral das finanças[cite: 2].

## 🚀 Funcionalidades
*   **Análise de Discrepância (Outliers):** Identifica valores que estão "fora da curva" e que podem distorcer a média do grupo[cite: 2].
*   **Protocolo de Quarentena:** Se a média das vendas atingir o `LIMITE_SEGURANCA` (padrão: 10.000), o sistema entra em estado de alerta máximo[cite: 3].
*   **Revisão Manual Automatizada:** O sistema sinaliza vendas individuais que excedem a média em 5 vezes, permitindo uma normalização dos dados para um resultado mais fiel à realidade[cite: 2, 3].
*   **Gestão de Limites:** Permite que um gestor altere o limite de segurança global para liberar o sistema após uma quarentena[cite: 3].

## 💻 Tecnologias Utilizadas
*   **Linguagem:** Python 3.x[cite: 3].
*   **Conceitos de Dados:** Normalização, Tratamento de Outliers e Teste de Mesa[cite: 2].

## 📊 Resultados e Aprendizados (Teste de Estresse)
Durante o desenvolvimento, foram realizados testes manuais para validar a lógica:
*   **Detecção de Erros:** Em um cenário com vendas de 100, 200 e 5.000, observou-se que a média (1.766,67) pode impedir que o alerta dispare se o multiplicador for muito alto. Isso reforçou a importância de ajustar as constantes de verificação para cada modelo de negócio[cite: 2].
*   **Segurança de Variáveis:** Identificou-se que o uso de variáveis globais para limites de segurança (como a `LIMITE_SEGURANCA` no código) oferece riscos de integridade, pois podem ser alteradas por outras partes do programa ou acessos indevidos[cite: 2, 3].
*   **Interatividade:** O projeto superou desafios técnicos iniciais sobre a captura de dados via `input()`, garantindo que o computador interprete as entradas como números (float) e não apenas como texto (string)[cite: 2, 3].

## 🔧 Como Executar
1. Clone este repositório.
2. Certifique-se de ter o arquivo `projeto_algoritmo_de_auditoria_de_dados.py`.
3. Execute o script:
   ```bash
   python projeto_algoritmo_de_auditoria_de_dados.py
