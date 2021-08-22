# Análise de Churn

## Descrição

Este é o projeto final do curso de Ciência de Dados na Prática da [VAI Academy](https://www.vai.academy/). Eu vou analisar três datasets para buscar insights sobre os dados, e vou criar um modelo de Machine Learning para prever quais são os clientes mais propensos a darem churn.

A VAI Pet, que é uma empresa fake criada para o projeto final, atua no mercado de animais de estimação há mais de 10 anos com
unidades físicas distribuídas no Nordeste do Brasil e, mais recentemente, com vendas online para todo o país. Além da venda de produtos, também possui em suas lojas físicas a clínica veterinária e serviços estéticos.

Desde o início do ano passado (2020), a VAI Pet iniciou um plano para evoluir a transformação digital da empresa e estruturação dos dados dos clientes para melhorar sua experiência. Com as análises realizadas, decidiram lançar um programa de fidelidade que permite identificar as compras dos clientes nas lojas físicas, onde possuem maior volume de vendas.

O CEO é analítico e orientado a resultados, participa ativamente das transformações da empresa, engaja e orienta o time nos planejamentos estratégicos. Como o time de dados da VAI Pet está focado em outras iniciativas da empresa, o CEO nos enviou a seguinte dúvida, pedindo a nossa ajuda para respondê-la.

- **Análise de churn e retenção de clientes:**
  Uma das prioridades para o próximo ano é aumentar a retenção dos clientes. Qual seria o grupo alvo de clientes para aumentar a retenção, isto é, qual o grupo de clientes que têm mais chance de churn?



## Arquivos usados

Eu vou utilizar os seguintes datasets:

- `cliente.csv`: Contém informação sobre os clientes, como id, sexo, data de nascimento e data da primeiro compra.
- `produto.csv`: Contém informação sobre os produtos que são vendidos na VAI Pet, como id, unidade, e até quatro categorias para cada produto.
- `venda.csv`:  Contém informação sobre as vendas, como id, data da venda, id do cliente, id do produto, quantidade e categoria da venda.



## Softwares

* Python 3.8 ou acima

* Packages: 
  * sklearn,
  * matplotlib, 
  * seaborn, 
  * pandas, 
  * numpy,
  * datetime.



## Licença

Os conteúdos deste repositório são cobertos pela [MIT License](LICENSE).

