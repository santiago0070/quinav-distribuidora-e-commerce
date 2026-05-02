📊 Análise de Performance Logística e E-commerce: Quinav-Distribuidora
1. Contextualização e Business Case (Etapa 1)
A Quinav-Distribuidora expandiu suas operações para o canal digital e precisava validar se a infraestrutura logística estava acompanhando o crescimento das vendas.

O Problema: A empresa identificou que, embora o faturamento fosse alto, havia uma percepção de queda na satisfação do cliente relacionada ao tempo de entrega.

Propósito: Analisar o faturamento por categoria e região, identificando como gargalos logísticos impactam diretamente o CX (Customer Experience).

2. Engenharia e Preparação de Dados (Etapa 2)
Utilizando o arquivo quinav_ecommerce_data_5.csv com 3.000 registros, apliquei técnicas avançadas de manipulação de dados com Python (Pandas e NumPy):

Tratamento de Dados: Limpeza de inconsistências e normalização de formatos de data e moeda.  

Regras de Negócio Customizadas:

Criação de indicadores de Faturamento Final considerando Valor Bruto, Frete e Descontos (cupons).  

Simulação de Impacto Logístico: Implementação de lógica condicional para penalizar a avaliação do cliente em pedidos com atraso, permitindo uma análise de correlação entre tempo de entrega e satisfação.  

3. Business Intelligence e Visualização (Etapa 3)
A análise foi dividida em camadas para atender diferentes níveis de decisão:

Nível Executivo (Faturamento):

Faturamento Total: R$ 5,77M.  

Categoria Líder: Comida (R$ 1,00M), seguida por Limpeza.  

Região Estratégica: O Sudeste representa a maior fatia de receita (R$ 1,46M).  

Nível Tático (Operação e Logística):

Status de Distribuição: Identificação de que a maioria dos pedidos é entregue, mas há um volume relevante de 908 pedidos com atraso.  

Taxa de Cancelamento: Estagnada em 9.5%, um KPI crítico para a saúde financeira do e-commerce.  

4. Documentação e Portfólio (Etapa 4)
Este repositório está organizado para garantir a reprodutibilidade do estudo:

/notebooks: Contém o script Python com todo o processo de ETL e geração de gráficos.  

/output: Imagens dos insights gerados (Receita por Categoria, Satisfação vs. Entrega, etc.).  

/data: Base de dados utilizada no projeto.

5. Principais Insights (Etapa 5)
Prioridade Logística no Sudeste: Como a região concentra a maior receita, qualquer redução no tempo de entrega impactará positivamente a maior parte do faturamento.  

Relação Satisfação vs. Entrega: A análise comprovou que a avaliação média de 4.2/5 é sensível a atrasos, sugerindo que a eficiência logística é o principal driver de fidelização.  

Mix de Produtos: O setor de Equipamento Industrial e Comida são os motores de receita, devendo ter prioridade em estoque e campanhas de marketing.
