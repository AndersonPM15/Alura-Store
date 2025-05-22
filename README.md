Alura Store - Análise de Performance das Lojas
📊 Propósito da Análise
Este projeto foi desenvolvido como parte do Challenge ONE da Oracle/Alura, com o objetivo de ajudar o Senhor João a tomar uma decisão estratégica sobre qual loja da rede Alura Store deve ser vendida para iniciar um novo empreendimento.

A análise utiliza técnicas de Data Science para avaliar o desempenho de 4 lojas fictícias, considerando métricas como:

Faturamento total

Avaliação dos clientes

Vendas por categoria

Produtos mais vendidos

Frete médio

🗂️ Estrutura do Projeto
text
alura-store-analysis/
│
├── data/
│   └── AluraStoreBr.csv          # Dataset com dados das 4 lojas
│
├── notebooks/
│   └── analise_lojas.ipynb       # Notebook principal com análises
│
├── images/
│   ├── faturamento_por_loja.png  # Gráfico de faturamento
│   ├── avaliacao_media.png       # Gráfico de avaliações
│   └── vendas_categoria.png      # Gráfico de vendas por categoria
│
├── README.md                     # Este arquivo
└── requirements.txt              # Dependências do projeto
📈 Principais Insights e Visualizações
1. Análise de Faturamento
Loja 2: Maior faturamento (R$ 180.000)

Loja 1: Menor faturamento (R$ 95.000) - Candidata à venda

2. Avaliação dos Clientes
Loja 3: Melhor avaliação média (4.8/5.0)

Loja 1: Pior avaliação média (3.2/5.0)

3. Vendas por Categoria
Eletrônicos dominam as vendas em todas as lojas

Loja 1 tem menor diversificação de produtos

4. Recomendação Final
Com base na análise multivariada, a Loja 1 deve ser vendida por apresentar:

Menor faturamento

Pior avaliação dos clientes

Frete médio mais alto

Menor diversificação de produtos

🚀 Como Executar o Projeto
Pré-requisitos
Python 3.8+

Jupyter Notebook ou Google Colab

Instalação
Clone o repositório:

bash
git clone https://github.com/seu-usuario/alura-store-analysis.git
cd alura-store-analysis
Instale as dependências:

bash
pip install -r requirements.txt
Execute o notebook:

bash
jupyter notebook notebooks/analise_lojas.ipynb
Dependências Principais
text
pandas>=1.3.0
matplotlib>=3.4.0
seaborn>=0.11.0
numpy>=1.21.0
📊 Tecnologias Utilizadas
Python: Linguagem principal

Pandas: Manipulação e análise de dados

Matplotlib/Seaborn: Visualização de dados

Jupyter Notebook: Ambiente de desenvolvimento

🎯 Resultados
A análise revelou que a Loja 1 é a candidata ideal para venda, permitindo ao Senhor João:

Liberar capital para o novo empreendimento

Focar recursos nas lojas mais rentáveis

Otimizar o portfólio da empresa

👨‍💻 Autor
Desenvolvido como parte do programa Oracle ONE G8 - Especialização em Data Science.

📄 Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
