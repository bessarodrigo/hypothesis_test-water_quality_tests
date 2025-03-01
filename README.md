#  Testes de Hipóteses - Teste de Qualidade do pH de Duas Represas de Água
## Média e Variância de duas populações
Estudo realizado com base nos aprendizados do módulo de inferência estatística da [Escola Preditiva](https://www.preditiva.ai/). apliquei o conceito utilizado no Excel e repliquei no Python.

## Problema
Uma empresa responsável por realizar testes de qualidade nas águas das represas que abastecem a região metropolitana da cidade de São Paulo **coletou 100 amostras de água da represa Billings e 110 amostras de água da represa Guarapiranga**.

O órgão de fiscalização suspeita que o **pH das águas da represa Guarapiranga seja superior ao pH das águas da represa Billings**, e solicitou um estudo para confirmação.

Por estarmos trabalhando com amostras e querermos fazer a comparação dos valores dessas populações, precisamos utilizar os Testes de Hipóteses para dar uma resposta confiável para a pergunta: As águas da Guarapiranga possuem um pH superior as águas da Billings?

## Hipóteses
- H0: O pH da Guarapiranga é igual ao pH da Billings, ou: pHG = pHB
- H1: O pH da Guarapiranga é superior ao pH da Billings, ou: pHG > pHB

## Resultado
O resultado da função TESTE.F foi 0,7%. Como o p-valor indica o quão plausível é H0, podemos antecipar que neste teste **H0 se mostra pouco plausível.**

Como o p-valor de 0,7% é menor que o nível de significância de 5%, podemos concluir que existem evidências estatísticas suficientes contra H0 , ou seja, rejeitamos H0.

Relembrando as Hipóteses definidas:
- H0: O pH da Guarapiranga é igual ao pH da Billings, ou: pHG = pHB
- H1: O pH da Guarapiranga é superior ao pH da Billings, ou: pHG > pHB

E como rejeitamos H0, **podemos dizer que existem evidências estatísticas de que a média do pH das águas da Guarapiranga é maior do que a média do pH das águas da Billings.**
  
