Análise de Vendas e Pipeline de Limpeza (200k+ registros)


Este projeto demonstra um fluxo completo de ETL (Extract, Transform, Load) e análise exploratória utilizando Python e a biblioteca Pandas. O foco principal foi transformar um dataset bruto de 200.000 linhas em uma base confiável para suporte à decisão.

🚀 Funcionalidades do Projeto
O script realiza o processamento de dados em camadas lógicas:

Limpeza e Integridade:

Remoção de duplicatas baseada em IDs únicos de venda.

Tratamento de valores nulos e inconsistentes (preços e quantidades zero ou negativos).

Padronização de Dados:

Normalização de textos (Capitalização e remoção de espaços extras).

Tratamento de idades fora do range biológico (0-100 anos).

Feature Engineering:

Cálculo de valor_total e ticket_medio.

Mapeamento geográfico de estados para regiões macro do Brasil.

Análise e Agregação:

Ranking de faturamento por estado.

Filtros dinâmicos por período (ano) e categoria de produto.

Criação de Tabelas Dinâmicas (Pivot Tables) para cruzamento de Produto x Estado.

🛠️ Tecnologias Utilizadas
Python 3.x

Pandas: Manipulação e análise de dados.

NumPy: Suporte matemático e tratamento de nulos.

📊 Estrutura de Saída
O projeto gera visões estratégicas, incluindo:

Ranking de Faturamento: Estados que mais geram receita formatados em moeda local.

Matriz de Quantidade: Tabela dinâmica mostrando a capilaridade de cada produto por região.

Como utilizar
Certifique-se de ter o arquivo dataset_pratica_limpeza_200k.csv no mesmo diretório.

Execute o notebook analise_vendas.ipynb.

As saídas serão exibidas diretamente através das funções display().
