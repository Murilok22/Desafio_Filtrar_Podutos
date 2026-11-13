# 🎮 Geek Store — Análise de vendas e desempenho de produtos

Projeto de análise de dados com **Python** e **Pandas** para explorar informações de vendas da Geek Store e transformar os dados em indicadores úteis para decisões comerciais.

## 📌 O que a análise contempla

- **Inspeção dos dados:** tipos de dados, estrutura do conjunto e estatísticas descritivas.
- **Avaliações de produtos:** identificação dos cinco produtos mais e menos bem avaliados.
- **Indicadores financeiros:**
  - receita total por produto;
  - lucro unitário, calculado como preço de venda menos custo de fabricação;
  - lucro total, considerando também o volume de vendas.
- **Filtro por categoria:** seleção de produtos da categoria de peças para PC, útil para análises ou campanhas direcionadas.
- **Exportação:** gravação dos dados processados em um arquivo CSV para uso em ferramentas de análise e visualização, como Power BI e Tableau.

## 🧰 Tecnologias

- Python
- Pandas
- Jupyter Notebook / Google Colab

## 🚀 Como executar

### 1. Clone o repositório

```bash
git clone https://github.com/Murilok22/Desafio_Filtrar_Podutos.git
cd Desafio_Filtrar_Podutos
```

### 2. Instale a dependência

```bash
python -m pip install pandas
```

### 3. Adicione os dados e execute a análise

Coloque o arquivo de entrada `vendas_geek_store.csv` no diretório esperado pelo projeto e execute o script ou notebook de análise. Ao final, os dados tratados podem ser exportados como `vendas_geek_novo.csv`.

> **Observação:** confira no script ou notebook os nomes das colunas e o caminho de entrada esperados. O arquivo CSV de dados não está incluído neste repositório.

## 📁 Arquivos gerados

| Arquivo | Descrição |
| --- | --- |
| `vendas_geek_novo.csv` | Dados processados e indicadores calculados, preparados para análises posteriores. |

## 🎯 Objetivo

Praticar análise e tratamento de dados com Pandas, explorando avaliações, vendas, receitas e lucros para apoiar a compreensão do desempenho dos produtos.
