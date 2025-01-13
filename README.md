# Bootcamp_Project_Making_Decisions_Based_In_Data

Project Overview
This project involved analyzing A/B test data and prioritizing hypotheses to increase revenue for an online store. The analysis focused on three datasets: Hypotheses Log, Orders Log, and Visits Log. Using the ICE and RICE frameworks, hypotheses were prioritized, and insights from the A/B test were gathered to evaluate differences in performance metrics between groups A and B.

Key Conclusions
Hypothesis Testing and Prioritization
Hypotheses with high Reach scores (close to 10) tend to have significantly higher priority in the RICE framework compared to ICE.

Example: Hypothesis 7, with a Reach of 10, has a RICE score of 112.0, much higher than its ICE score of 11.20.
When Reach scores are low, RICE and ICE values tend to be similar or equal.

Example: Hypothesis 8, with a Reach of 1, has identical RICE and ICE scores (16.2).
The inclusion of the Reach factor in the RICE calculation emphasizes changes that impact a larger number of users, whereas ICE focuses solely on the combination of Impact, Confidence, and Effort.

A/B Testing Results
Cumulative Revenue:

Group B consistently outperformed Group A in cumulative revenue throughout the test period. While the groups started similarly, Group B showed higher revenues starting from 05/08/2019 and maintained this trend until the end of the analysis.
Average Order Size:

Group B also had consistently higher average order sizes compared to Group A, although the statistical test revealed no significant difference in these averages.
Conversion Rate:

Both groups exhibited zigzag patterns in conversion rates. However, Group B had better performance at the start and end of the analysis period, with higher cumulative conversion rates overall.
Price Dispersion:

Most orders were below $5,000, with only three orders exceeding this threshold, indicating that high-value orders are rare.
Outliers and Percentiles:

At the 95th percentile:
- Users: 95% of users placed fewer than 2 orders, with only 5% placing more than this number.
- Orders: 95% of orders had a value below $435.54.
At the 99th percentile:
- Users: 99% placed fewer than 4 orders.
- Orders: 99% of order values were below $900.90.

Final Recommendation
Group B showed better performance across most metrics, including cumulative revenue, average order size, and conversion rates. However, statistical tests did not confirm a significant difference in all metrics. It is recommended to proceed with caution and consider the broader business context before making final decisions.

===========================================================================

Visão Geral do Projeto
Este projeto analisou os dados de um teste A/B e priorizou hipóteses para aumentar a receita de uma loja online. A análise utilizou três conjuntos de dados: Hypotheses Log, Orders Log e Visits Log. Por meio dos frameworks ICE e RICE, as hipóteses foram priorizadas, e insights do teste A/B foram obtidos para avaliar as diferenças de desempenho entre os grupos A e B.

Principais Conclusões
Priorização de Hipóteses
Hipóteses com Reach alto (próximo a 10) têm maior prioridade no framework RICE em comparação com o ICE.

Exemplo: A Hipótese 7, com Reach de 10, tem um valor de RICE (112.0) muito maior que o valor de ICE (11.20).
Quando o valor de Reach é baixo, os valores de RICE e ICE tendem a ser semelhantes ou iguais.

Exemplo: A Hipótese 8, com Reach de 1, apresenta valores iguais para RICE e ICE (16.2).
A inclusão do fator Reach no cálculo do RICE beneficia alterações que afetam um maior número de usuários, enquanto o ICE prioriza apenas a combinação de Impact, Confidence e Effort.

Resultados do Teste A/B
Receita Acumulada:

O Grupo B superou consistentemente o Grupo A em termos de receita acumulada durante o período de teste. Apesar de começarem similares, o Grupo B apresentou receitas maiores a partir de 05/08/2019.
Tamanho Médio dos Pedidos:

O Grupo B também teve tamanhos médios de pedido consistentemente maiores que o Grupo A, embora os testes estatísticos não tenham confirmado uma diferença significativa.
Taxa de Conversão:

Ambos os grupos mostraram um comportamento de zigue-zague na taxa de conversão. Contudo, o Grupo B apresentou melhores taxas no início e no final do período analisado.
Dispersão dos Preços:

A maioria dos pedidos ficou abaixo de $5.000, com apenas três acima deste valor, indicando que pedidos de alto valor são raros.
Outliers e Percentis:

No percentil 95:
- Usuários: 95% realizaram menos de 2 pedidos.
- Pedidos: 95% dos valores foram abaixo de $435,54.
No percentil 99:
- Usuários: 99% realizaram menos de 4 pedidos.
- Pedidos: 99% dos valores foram abaixo de $900,90.

Recomendação Final
O Grupo B demonstrou melhores resultados na maioria das métricas, incluindo receita acumulada, tamanho médio dos pedidos e taxa de conversão. Contudo, os testes estatísticos não confirmaram diferenças significativas em todas as métricas. Recomenda-se cautela na decisão final e a consideração do contexto geral do negócio.