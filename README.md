# Contoso Sales
## Visão geral:
Projeto de análise de vendas do banco de dados Contoso Retail, o dashboard foi desenvolvido com Power BI e teve como objetivo identificar os principais fatores que influenciam as vendas da empresa Contoso.

<img  width="500" src="https://github.com/amandalmeida2/Contoso_Sales/blob/main/Imagens/Dashboard.png?raw=true">
<a href="https://github.com/amandalmeida2/Contoso_Sales.git"> Clique aqui</a>  para acessar o repositório no Github.
<br></br>
<a target="_blank" href="https://app.powerbi.com/view?r=eyJrIjoiNDFiMDBkOWMtYjRmYS00ZjFmLTgwZTEtYWM1YzgxZmViYWExIiwidCI6Ijc1OGRlZGVlLTk1YmItNGU2Mi05MWU2LTU3OTRiMTUwZjFhYSJ9" >Clique aqui</a> e acesse a solução desenvolvida.
<br></br>

### Necessidades identificadas antes do desenvolvimento do Dashboard:

**•	Dificuldade com Grande Volume de Dados:** O grande volume de dados dificultava a exportação do sistema atual e a manipulação das informações em planilhas, especialmente ao utilizar macros e tabelas dinâmicas.

**•	Segmentação de Dados:** Havia uma necessidade de segmentar os dados de maneira simples e interativa, categorizando-os por filiais, categorias de produtos e períodos de tempo.

**•	Medição de Desempenho e Performance ao Longo do Tempo:** A empresa precisava medir o desempenho e a performance ao longo do tempo, com foco em variações anuais e mensais.

### Modelo e Fonte de Dados
O banco de dados Contoso Retail é bem estruturado e organizado, o que facilita a análise e a modelagem de dados. Para o projeto, foi necessário realizar uma modelagem e organização adicionais dos dados para atender aos requisitos específicos da análise. Isso incluiu a preparação de dados, criação de relações e a definição de métricas chave, assegurando que as informações estivessem prontas para serem usadas de forma eficiente no Power BI.

<img  width="500" src="https://github.com/amandalmeida2/Contoso_Sales/blob/main/Imagens/Modelo%20de%20dados%20PBI.png?raw=true">

### Medidas 

<img align="left" width="300" src="https://raw.githubusercontent.com/amandalmeida2/Contoso_Sales/a78f752406a5de36355072d50caa205be08a1afe/Imagens/Medidas.png"> 
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
 
<img  width="500" src="https://github.com/amandalmeida2/Contoso_Sales/blob/main/Imagens/Tabela%20Dimcalendario.png?raw=true">
Com essa analise chegamos ao dashboard interativo, que contem filtros de categorias, de periodo, de classe de produtos. O dashboard conta tambem com menu lateral para aplicar os filtros 
Esse dashboard interativo desenvolvido no Power BI oferece uma visualização clara e acessível dos dados de vendas da Contoso Retail. Ele foi projetado para facilitar a análise e a interpretação dos dados, proporcionando uma experiência de usuário intuitiva.

### Principais Funcionalidades
 <img  width="500" src="https://github.com/amandalmeida2/Contoso_Sales/blob/main/Imagens/Dashboard%20-%20Filtro.png?raw=true">

**•	Menu Lateral de Filtros:** O dashboard inclui filtros que permitem aos usuários ajustar a visualização dos dados conforme suas necessidades

**• Categorias de Produtos:** Selecione categorias específicas para ver dados detalhados por tipo de produto.

**•Período:** Escolha o período de tempo para análise, como ano, trimestre ou mês.

**•Classe de Produtos:** Filtre os dados com base em diferentes classes de produtos.

### Conclusões e insights

A análise dos dados de vendas da Contoso Retail revelou uma série de tendências e padrões importantes que podem orientar estratégias futuras. Abaixo estão os principais achados e recomendações baseadas nos dados:

**Redução no Total de Vendas:** Observou-se uma redução nas vendas totais ao longo dos anos: em 2007, as vendas foram de 4,6 bilhões, diminuindo para 4,1 bilhões em 2008 e 3,7 bilhões em 2009. Apesar dessa queda nas vendas totais, as quantidades vendidas aumentaram de 17 milhões em 2007 para 19,8 milhões em 2009.

**Mudança na Composição dos Produtos:** A proporção de produtos da classe "Economy" aumentou significativamente, de 36% em 2007 para 64% em 2009. Este crescimento pode explicar a redução no valor total das vendas, já que produtos de classe "Economy" geralmente têm margens de lucro mais baixas.

**Mudança no Canal de Vendas:** Embora as lojas físicas ainda sejam o principal canal de vendas, houve um aumento considerável nas vendas online ao longo dos anos. Isso destaca a importância crescente do e-commerce no mix de vendas da empresa.
