# machine_learning
Modelos de Machine Learn com Python e R

## Modelo 1: Prevendo a Inadimpência de Clientes com MachineLearning em R
---
### Definição do Problema:
* Prever quais clientes poderão deixar de pagar a fatura do cartão de crédito no próximo mês.
* A idéia é fornecer insights para que a empresa possa tomar ações pro-ativas como: limitar as compras feitas com o cartão ou até não aprovar compras acima de um determinado limite.
* O setor de cobranças será afonte de dados do histórico dos clientes, entre os que pagam e que não pagam as faturas.
* O trabalho é criar um modelo de Machine Learning para prever a inadimolência dos clientes do cartão de crédito.
> Dataset: https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients

### This research employed a binary variable, default payment (Yes = 1, No = 0), as the response variable. This study reviewed the literature and used the following 23 variables as explanatory variables:

* X1: Amount of the given credit (NT dollar): it includes both the individual consumer credit and his/her family (supplementary) credit.
* X2: Gender (1 = male; 2 = female).
* X3: Education (1 = graduate school; 2 = university; 3 = high school; 4 = others).
* X4: Marital status (1 = married; 2 = single; 3 = others).
* X5: Age (year).
* X6 - X11: History of past payment'. We tracked the past monthly payment records (from April to September, 2005) as follows: X6 = the repayment status in September, 2005; X7 = the repayment status in August, 2005; . . .;X11 = the repayment status in April, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.
* X12-X17: Amount of bill statement (NT dollar). X12 = amount of bill statement in September, 2005; X13 = amount of bill statement in August, 2005; . . .; X17 = amount of bill statement in April, 2005.
* X18-X23: Amount of previous payment (NT dollar). X18 = amount paid in September, 2005; X19 = amount paid in August, 2005; . . .;X23 = amount paid in April, 2005.

## Valores Missing e Distribuição das Idades
| Valores Missing | Distribuição |
| --------------- | ------------ |
<a href="https://github.com/emariot/machine_learning/blob/main/R/img/valores_missing.png"><img src="https://github.com/emariot/machine_learning/blob/main/R/img/valores_missing.png" align="center" ></a> | <a href="https://github.com/emariot/machine_learning/blob/main/R/img/dist.png"><img src="https://github.com/emariot/machine_learning/blob/main/R/img/dist.png" align="center" ></a>

## Ditribuição da variável categórica e comparação entre os dados originais e de treino
| Variáveis | Original/Treino |
| --------------- | ------------ |
<a href="https://github.com/emariot/machine_learning/blob/main/R/img/dist_val.png"><img src="https://github.com/emariot/machine_learning/blob/main/R/img/dist_val.png" align="center" ></a> | <a href="https://github.com/emariot/machine_learning/blob/main/R/img/var_or_treino.png"><img src="https://github.com/emariot/machine_learning/blob/main/R/img/var_or_treino.png" align="center" ></a>

## Treinamento dos modelos
| Modelo 1 | Modelo 2 | Modelo 3 |
| -------- | -------- | -------- |
<a href="https://github.com/emariot/machine_learning/blob/main/R/img/treino_model_1.png"><img src="https://github.com/emariot/machine_learning/blob/main/R/img/treino_model_1.png" align="center" ></a> | <a href="https://github.com/emariot/machine_learning/blob/main/R/img/treino_model_2.png"><img src="https://github.com/emariot/machine_learning/blob/main/R/img/treino_model_2.png" align="center" ></a> | <a href="https://github.com/emariot/machine_learning/blob/main/R/img/treino_model_3.png"><img src="https://github.com/emariot/machine_learning/blob/main/R/img/treino_model_3.png" align="center" ></a>

## Relevância entre as variáveis do modelo
| Relevância |
| ---------- |
<a href="https://github.com/emariot/machine_learning/blob/main/R/img/var_relevantes.png" ><img src="https://github.com/emariot/machine_learning/blob/main/R/img/var_relevantes.png" align="left" height="400" width="600"  ></a> |
