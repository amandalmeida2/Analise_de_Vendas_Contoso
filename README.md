# Contoso Sales
## Visão geral:
Projeto de análise de vendas do banco de dados Contoso Retail, o dashboard foi desenvolvido com Power BI e teve como objetivo identificar os principais fatores que influenciam as vendas da empresa Contoso.

### Necessidades identificadas antes do desenvolvimento do Dashboard:

**•	Dificuldade com Grande Volume de Dados:** O grande volume de dados dificultava a exportação do sistema atual e a manipulação das informações em planilhas, especialmente ao utilizar macros e tabelas dinâmicas.

**•	Segmentação de Dados:** Havia uma necessidade de segmentar os dados de maneira simples e interativa, categorizando-os por filiais, categorias de produtos e períodos de tempo.

**•	Medição de Desempenho e Performance ao Longo do Tempo:** A empresa precisava medir o desempenho e a performance ao longo do tempo, com foco em variações anuais e mensais.

### Modelo e Fonte de Dados
O banco de dados Contoso Retail é bem estruturado e organizado, o que facilita a análise e a modelagem de dados. Para o projeto, foi necessário realizar uma modelagem e organização adicionais dos dados para atender aos requisitos específicos da análise. Isso incluiu a preparação de dados, criação de relações e a definição de métricas chave, assegurando que as informações estivessem prontas para serem usadas de forma eficiente no Power BI.
 
Para permitir uma análise detalhada e precisa dos dados de vendas, foram criadas medidas específicas proporcionando uma visão clara do desempenho financeiro da empresa, como:

**•	Custos:** Cálculo dos custos associados aos produtos vendidos.

**•	Receitas:** Total das receitas geradas pelas vendas.

**•	Lucro:** Diferença entre receitas e custos, representando o lucro bruto.

**•	Quantidades Vendidas:** Número total de unidades vendidas.

Além dessas, também foram desenvolvidas medidas temporais, incluindo:

•	Receitas do Último Ano

•	Lucro do Último Ano

•	Custo do Último Ano

•	Quantidades Vendidas no Último Ano

Essas medidas temporais permitem realizar comparações entre diferentes períodos, facilitando a análise de tendências e variações ao longo do tempo.

### Tabela DimCalendário
Para aprimorar a análise temporal e possibilitar uma visualização mais detalhada das vendas ao longo do tempo, foi criada uma Tabela DimCalendário. Esta tabela é um componente essencial no modelo de dados, oferecendo uma estrutura robusta para a análise de tendências e variações temporais.
 

Com essa analise chegamos ao dashboard interativo, que contem filtros de categorias, de periodo, de classe de produtos. O dashboard conta tambem com menu lateral para aplicar os filtros 
Esse dashboard interativo desenvolvido no Power BI oferece uma visualização clara e acessível dos dados de vendas da Contoso Retail. Ele foi projetado para facilitar a análise e a interpretação dos dados, proporcionando uma experiência de usuário intuitiva.

### Principais Funcionalidades

**•	Menu Lateral de Filtros:** O dashboard inclui filtros que permitem aos usuários ajustar a visualização dos dados conforme suas necessidades:

**• Categorias de Produtos:** Selecione categorias específicas para ver dados detalhados por tipo de produto.

**•Período:** Escolha o período de tempo para análise, como ano, trimestre ou mês.

**•Classe de Produtos:** Filtre os dados com base em diferentes classes de produtos.
