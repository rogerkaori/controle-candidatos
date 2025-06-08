# Processo Seletivo

Este projeto em Java simula um processo seletivo, analisando o salário pretendido por candidatos e tomando decisões com base em um salário base.

## Como funciona?

O programa principal (`ProcessoSeletivo.java`) executa o seguinte fluxo:

1. Exibe uma mensagem inicial: "Processo Seletivo".
2. Analisa três candidatos com salários pretendidos diferentes: 1900.0, 2200.0 e 2000.0.
3. Para cada salário pretendido, compara-o com o salário base (2000.0) e imprime a decisão:
    - **LIGAR PARA CANDIDATO**: se o salário pretendido for menor que o salário base.
    - **LIGAR PARA O CANDIDATO COM CONTRA PROPOSTA**: se for igual ao salário base.
    - **AGUARDANDO O RESULTADO DOS DEMAIS CANDIDATOS**: se for maior que o salário base.

## Como executar

1. Clone o repositório ou copie o arquivo `ProcessoSeletivo.java`.
2. Compile o arquivo:
   ```bash
   javac candidatura/ProcessoSeletivo.java
