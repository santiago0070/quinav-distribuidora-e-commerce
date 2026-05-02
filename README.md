Data Intelligence & Supply Chain Analysis: Caso Quinav-Distribuidora
1. Business Case e Contextualização (Etapa 1)
A Quinav-Distribuidora, atuante no setor de suprimentos e e-commerce, enfrentava o desafio de escalar suas operações mantendo a saúde financeira e a satisfação do cliente.

O Problema de Negócio: Necessidade de identificar a correlação entre o tempo de entrega e a taxa de cancelamento, além de otimizar a margem de contribuição por categoria.  

Objetivo: Implementar um pipeline de dados para monitorar o faturamento real (líquido de descontos e fretes) e a eficiência logística regional.  

2. Engenharia de Dados e Business Rules (Etapa 2)
O projeto processou uma volumetria de 3.000 registros operacionais, onde apliquei:

Tratamento de Dados (Python/Pandas): Limpeza de registros inconsistentes e padronização de tipos de dados para garantir a integridade da análise.  

Desenvolvimento de KPIs:

Ticket Médio Real: Calculado após a aplicação de cupons de desconto e custos de frete.  

SLA Logístico: Categorização de pedidos entre "No Prazo" e "Atrasado" para medir o impacto na avaliação do usuário.  

3. Business Intelligence e Arquitetura de Visualização (Etapa 3)
A solução de visualização foi estruturada em uma hierarquia de decisão:

View Executiva: Faturamento total de R$ 5,77M, com foco na performance das categorias "Comida" e "Equipamento Industrial".  

View Operacional: Análise de 908 pedidos com atraso, permitindo identificar que o Sudeste, apesar de ser o maior faturamento (R$ 1,46M), exige atenção na malha logística para evitar churn.
