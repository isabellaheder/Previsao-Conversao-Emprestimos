# Customer-Loan-Conversion-Prediction
### Overview:
Este projeto tem como objetivo desenvolver um modelo de machine learning para prever a probabilidade de clientes aceitarem um empréstimo pessoal, utilizando dados de comportamento financeiro e relacionamento bancário.

O problema é baseado em um cenário real do Thera Bank, que busca aumentar a eficiência de campanhas de marketing direcionadas, reduzindo custos e aumentando a taxa de conversão.

### Objetivo
Construir um modelo de classificação capaz de identificar clientes com maior propensão a contratar empréstimos pessoais, permitindo estratégias orientadas por dados.
____________________________
Dataset: https://www.kaggle.com/datasets/krantiswalke/bank-personal-loan-modelling/data 

### Dicionário de dados:

| Coluna | Significado |
|--------|-------------|
| ID | ID do cliente |
| Age | idade do cliente |
| Experience | anos de experiência profissional |
|Income | Income anual do cliente ($000) |
| ZIP Code | CEP do cliente |
| Family | tamanho da família do cliente |
| CCAvg | média gasta no cartão de crédito por mês ($000) |
| Education | Nível de educação (1: graduação, 2: pós-graduação, 3: avançado/professional) |
| Mortgage | valor do financiamento imobiliário (se tiver) |
| Personal Loan | **TARGET** - 0: Não aceitou o empréstimo; 1: Aceitou o empréstimo |
| Securities Account | cliente possui conta de investimentos no banco (0: não, 1: sim) |
| CD Account | cliente possui um Certificado de Depósito (CD) (0: não, 1: sim) |
| Online | cliente utiliza internet banking (0: não, 1: sim) |
| Credit card | cliente possui cartão de crédito do banco (0: não, 1: sim) |

### Resultado:
- Acurácia: 0.9202020202020202
- Precisão: 0.5266666666666666
- Recall: 0.9080459770114943

Matriz de Confusão:

<img width="539" height="455" alt="e5b4e04c-8c24-4973-8287-0e53190fa4fe" src="https://github.com/user-attachments/assets/822d3363-ba6a-468c-bf99-6b96222c7587" />

