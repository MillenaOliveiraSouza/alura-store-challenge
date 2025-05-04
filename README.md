# Desafio Alura Store

## Propósito da Análise

O objetivo desse projeto foi realizar uma análise exploratória dos dados de uma loja fictícia chamada *Alura Store*, com foco em entender padrões de venda, comportamento dos clientes, desempenho das lojas e produtos mais relevantes. Através dessa análise, buscamos gerar insights que ajudem na tomada de decisões estratégicas, como otimização de estoque, logística e marketing.

## Estrutura do Projeto e Organização dos Arquivos

A estrutura atual do repositório está organizada da seguinte forma:

```
alura-store-challenge/
│
├── alura_store_desafio.ipynb   → Notebook com toda a análise e visualizações
│
└── imagens/                    → Pasta contendo imagens dos gráficos gerados
    ├── grafico_analise_faturamento.png
    ├── grafico_frete_medio_por_loja.png
    ├── grafico_media_avaliacao_lojas.png
    ├── grafico_produtos_mais_menos_vendidos.png
    └── grafico_vendas_por_categoria.png
```

## Exemplos de Gráficos e Insights Obtidos

### 1. Análise do Faturamento

**Insight:** Observamos que determinados períodos do ano apresentam picos de faturamento, sugerindo sazonalidade nas vendas.

![Gráfico - Análise do faturamento](/alura-store-challenge/imagens/grafico_analise_faturamento.png)

---

### 2. Frete Médio por Loja

**Insight:** Algumas lojas apresentam um custo médio de frete bem acima da média, o que pode afetar a experiência do cliente.

![Gráfico - Frete médio por loja](/alura-store-challenge/imagens/grafico_frete_medio_por_loja.png)

---

### 3. Média de Avaliação das Lojas

**Insight:** As lojas com maior faturamento não são necessariamente as mais bem avaliadas, indicando possíveis problemas de atendimento ou entrega.

![Gráfico - Média de avaliação das lojas](/alura-store-challenge/imagens/grafico_media_avaliacao_lojas.png)

---

### 4. Produtos Mais e Menos Vendidos

**Insight:** Há uma concentração grande de vendas em poucos produtos, o que pode indicar que muitos itens do catálogo têm pouca rotatividade.

![Gráfico - Produtos mais e menos vendidos](/alura-store-challenge/imagens/grafico_produtos_mais_menos_vendidos.png)

---

### 5. Vendas por Categoria

**Insight:** Algumas categorias possuem desempenho muito superior a outras, o que pode guiar campanhas específicas de marketing.

![Gráfico - Vendas por categoria](/alura-store-challenge/imagens/grafico_vendas_por_categoria.png)

---

## Instruções para Executar o Notebook

### Passo 1: Clone o repositório
```bash
git clone https://github.com/MillenaOliveiraSouza/alura-store-challenge.git
```

### Passo 2: Instale as dependências
O notebook foi feito no Google Colab, então a maior parte das bibliotecas já estão disponíveis por padrão. Caso queira rodar localmente, instale os seguintes pacotes:

```bash
pip install pandas matplotlib seaborn
```

### Passo 3: Execute o notebook
Abra o arquivo `alura_store_desafio.ipynb` em um ambiente como Jupyter Notebook, Jupyter Lab ou Google Colab para executar todas as células e visualizar os gráficos.

---

## Conclusão

Esse projeto serviu como um exercício prático de análise de dados, permitindo extrair informações valiosas a partir de um conjunto de dados bruto. Os gráficos apresentados ajudam a visualizar padrões e tomar decisões baseadas em dados reais.

---

## Licença

Este projeto é livre para fins educacionais.
