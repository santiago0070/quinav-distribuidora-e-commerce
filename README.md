📊 E-commerce Analytics: Quinav Distribuidora

🟢 Contextualização & Storytelling
A Quinav Distribuidora recentemente expandiu suas operações para o canal digital. Este projeto visa diagnosticar a performance deste novo braço de faturamento, identificando gargalos logísticos e oportunidades de crescimento em vendas e fidelização.

Paleta de Cores Sugerida: Azul Petróleo (Confiança), Verde Esmeralda (Crescimento/Receita) e Cinza Soft (Neutralidade Técnica).

Business Case: Baixa visibilidade sobre o impacto do tempo de entrega na satisfação do cliente e necessidade de identificar as categorias de produto que sustentam a margem operacional.

🔵 Engenharia de Dados (ETL & Coding)
O pipeline de dados foi desenvolvido em Python utilizando o arquivo quinav_ecommerce_data.csv como fonte principal.  

Tratamento Técnico:

Limpeza e normalização de strings (Categorias e Status).

Tratamento de valores ausentes (NAs) em avaliações para pedidos não entregues.  

Geração de massa de dados sintética com Numpy para simulação de cenários reais.  

KPIs & Regras de Negócio:

Valor Final: Cálculo considerando (Preço Unitário * Quantidade) - Desconto + Frete.  

Penalização de Satisfação: Lógica personalizada que reduz a nota do cliente com base no atraso e tempo total de entrega.  

Performance: Exportação otimizada para .csv, pronta para consumo em ferramentas de BI (Power BI/Tableau).

🟡 Business Intelligence (Insights)
A modelagem segue o esquema Star Schema (Fato/Dimensão) para garantir performance em cálculos DAX complexos.

Hierarquia de Telas:
Dashboard Executivo: Visão macro de Faturamento Total (R$ 5.77M), Ticket Médio (R$ 1,923.38) e Taxa de Cancelamento (9.5%).  

Visão Operacional: Análise detalhada de logística (Avaliação vs. Tempo de Entrega) e performance regional.

Métrica	Valor	Insight de Negócio
Faturamento Total	R$ 5,770,153.06	
Alta capilaridade no primeiro ano.  

Ticket Médio	R$ 1,923.38	
Foco em produtos de alto valor agregado.  

Taxa de Cancelamento	9.5%	
Ponto de atenção para a experiência de checkout/frete.  

Avaliação Média	4.2/5	
Nível de serviço saudável, mas com espaço para otimização.

