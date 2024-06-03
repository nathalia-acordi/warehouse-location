# warehouse-location

### Descrição do Projeto (realizado para a disciplina de Métodos Quantitativos)

Este projeto trata da modelagem de sistemas de distribuição, focando na decisão entre os custos de transporte e os custos operacionais de centros de distribuição. O objetivo é determinar quais armazéns devem ser operados e a quantidade a ser enviada de cada armazém para cada cliente. As variáveis de decisão incluem a abertura de armazéns (yi) e as quantidades enviadas (xij). O modelo minimiza os custos totais, que incluem custos fixos de operação dos armazéns e custos variáveis de operação e transporte.

O modelo base apresenta as seguintes instâncias:

1. Número de armazéns (n)
2. Número de clientes (m)
3. Custos fixos de operação dos armazéns (fi)
4. Custos operacionais e de transporte (cij)
5. Demanda de cada cliente (dj)
6. Capacidades de armazenamento dos armazéns (Ki)
7. Capacidade de produção da planta (P)
8. Tempo máximo de distribuição (T)
9. Número de produtos (p)
10. Novo armazém e cliente adicionados ao modelo

O modelo pode ser estendido para incluir sistemas de distribuição multi-echelon, restrições de capacidade, economias de escala, considerações de tempo de serviço, múltiplos produtos e condições que impedem a divisão de pedidos.
