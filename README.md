🎮 Geek Store - Análise de Vendas e Desempenho de Produtos

Python Pandas Status

Este repositório contém uma análise de dados robusta e exploração comercial do conjunto de dados da Geek Store. O objetivo principal é extrair insights acionáveis sobre os produtos mais populares, calcular métricas cruciais de receita e lucro, além de segmentar os dados para campanhas focadas de marketing.
📌 Funcionalidades Principais

    Ficha Técnica & Estatísticas: Diagnóstico inicial do tipo dos dados (info()) e descrição de métricas estatísticas principais (describe()).
    Análise de Avaliações: Extração dinâmica dos 5 produtos com maior avaliação (destaques de satisfação) e dos 5 produtos com menor avaliação (oportunidades de melhoria).
    Engenharia de Recursos (Métricas Financeiras):
        Cálculo de Receita Total por produto.
        Cálculo de Lucro Unitário (Preço de Venda - Custo de Fabricação).
        Cálculo de Lucro Final integrado ao volume de vendas.
    Filtros Estratégicos: Segmentação de produtos da categoria de Peças de PC para direcionamento de campanhas de Marketing.
    Exportação: Exportação dos dados tratados de volta para formato CSV prontos para visualização em ferramentas de BI (como Power BI ou Tableau).

📊 Tecnologias Utilizadas

    Python (Linguagem base)
    Pandas (Tratamento e manipulação de dados)
    Google Colab (Ambiente de desenvolvimento)

🛠️ Como Executar o Projeto

    Clone o repositório:

    git clone https://github.com/seu-usuario/vendas-geek-store.git

    Certifique-se de possuir o arquivo original vendas_geek_store.csv no mesmo diretório.
    Instale a dependência necessária:

    pip install pandas

    Execute o script principal ou o notebook Jupyter para gerar os relatórios e o arquivo consolidado vendas_geek_novo.csv.
