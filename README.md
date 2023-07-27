# Projeto Final de Data Analytics do Google

## Alan
## Data: 25 de Julho de 2023

### Introdução e Objetivo do Estudo
Este projeto representa a parte principal do programa de certificação do Google Analytics.

### Objetivo do Estudo
O objetivo deste estudo de caso é analisar o comportamento dos membros anuais e dos passageiros não membros, com a finalidade de desenvolver uma estratégia de marketing que incentive os não membros a aderirem ao programa de membros.

### Perguntas
Para alcançar o objetivo proposto, o estudo busca responder às seguintes questões:

1. Qual é o padrão de comportamento dos membros anuais em comparação com os passageiros não membros?
2. Quais são os principais motivos pelos quais os passageiros não membros não aderem ao programa de membros?
3. Quais ações de marketing podem ser implementadas para atrair os não membros e incentivá-los a se tornarem membros anuais?

As respostas a essas perguntas serão fundamentais para orientar a estratégia futura de marketing e aumentar o número de adesões ao programa de membros.

### Preparação dos Dados
O conjunto de dados referente ao trimestre nº 2 de 2019 ao trimestre nº 1 de 2020 foi baixado a partir do link fornecido e salvo na minha área de trabalho local.

### Processamento dos Dados
Os passos realizados na plataforma R para preparar o arquivo final para análise foram os seguintes:

1. Uniformização dos nomes das colunas: Todas as colunas no conjunto de dados foram padronizadas para terem o mesmo nome em todo o arquivo. Isso garante consistência nos dados e facilita a manipulação e análise.
2. Remoção de colunas extras: Foram identificadas quaisquer colunas que não eram comuns a todos os arquivos e, em seguida, essas colunas foram removidas. Isso garante que apenas as informações relevantes para a análise sejam mantidas.
3. Mesclagem das colunas: As colunas foram mescladas em um único arquivo usando a junção externa completa. Isso significa que todas as linhas dos arquivos foram mantidas, mesmo que não houvesse correspondência em alguma coluna específica.
4. Renomeação das linhas: A coluna que indicava se um registro era de um assinante/membro foi renomeada para "Membro", enquanto a coluna que indicava se era de um cliente/casual foi renomeada para "Não Membro". Essa renomeação torna os dados mais claros e compreensíveis.
5. Identificação e registro de outliers: Foram identificados quaisquer valores atípicos nos dados e eles foram registrados em uma coluna separada chamada "Outliers". Essa informação é importante para avaliar a qualidade e a confiabilidade dos dados.

### Pré-Análise dos Dados
Criamos as seguintes colunas:
- Ride Length in Minutes: Isso foi feito subtraindo o horário de início do percurso até o horário final.
- Weekday: Calculado a partir da coluna da hora de início.
- Day name: Calculado a partir da coluna da hora de início.
- Day number: Calculado a partir da coluna da hora de início.
- Year-Month-Quarter: Calculado a partir da coluna da hora de início.

### Conclusão e Recomendação
Após a conclusão do processamento dos dados e pré-análise, este projeto fornece insights valiosos sobre o comportamento dos membros e não membros. Recomenda-se a implementação de ações de marketing direcionadas para incentivar os não membros a se tornarem membros anuais, com foco em promoções, descontos e campanhas específicas para datas estratégicas.

O estudo destaca oportunidades de melhoria para a Cyclistic, como o desenvolvimento de pacotes familiares para uso durante os finais de semana e ofertas especiais durante os períodos de alta demanda, como as férias de verão. A implementação dessas recomendações pode aumentar a adesão ao programa de membros e melhorar o desempenho geral do negócio.

### Nota:
Para uma análise completa, é recomendado consultar o conjunto de dados completo e os resultados detalhados obtidos na análise final. O arquivo final está disponível para referência.
