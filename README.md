# 📊 Análise de Vendas de uma Lojinha Online

Este projeto é uma análise simples e objetiva de um conjunto fictício de vendas, utilizando Pandas, NumPy e Matplotlib para explorar dados, gerar métricas e identificar padrões de desempenho por produto e categoria.
O objetivo é demonstrar domínio de manipulação de dados e boas práticas na construção de um notebook de análise.

---

# 🧰 Tecnologias Utilizadas
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Lab

---

# 📁 Dataset
O arquivo vendas.csv contém:
- `id_venda`
- `data`
- `produto`
- `categoria`
- `quantidade`
- `preco_unitario`

Coluna criada:
`df['receita'] = df['preco_unitario'] * df['quantidade']`

---

# 📈 Principais Análises
 🔹 Receita Total  
 🔹 Receita por Categoria  
 🔹 Produto Mais e Menos Vendido  
 🔹 Produto Mais e Menos Lucrativo  
 🔹 Receita Média por Categoria

 ---

 # 📊 Gráficos
 📌 Receita por Categoria (Barras Verticais)  
 📌 Quantidade Vendida por Produto (Barras Verticais)

 ---

# 📐 Métricas Gerais

Estatísticas descritivas:
`df[['quantidade', 'preco_unitario', 'receita']].describe()`

---

# 📁 Estrutura do Projeto  
/  
├── vendas.csv  
├── AnaliseVendas.ipynb  
└── README.md  

---

# 🎯 Objetivo do Projeto
- Praticar análise de dados com Pandas e NumPy  
- Entender agrupamentos, métricas e estatísticas  
- Criar um mini-projeto profissional para portfólio  
- Visualizar insights com gráficos limpos e diretos

---

# 🔎 Conclusões Sobre o Projeto
A análise permitiu identificar rapidamente os produtos mais vendidos, os menos procurados e as categorias que mais geram receita. Mesmo com um dataset simples, foi possível extrair insights claros e úteis usando Pandas, NumPy e gráficos básicos. O projeto cumpre seu papel de demonstrar domínio de manipulação de dados, organização e visualização. Uma base sólida para análises mais avançadas no futuro.
