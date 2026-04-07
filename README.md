Análise Quantitativa: Simulação de Monte Carlo (GBM)

Modelagem Preditiva e Gestão de Risco para Ativos Financeiros

Este projeto utiliza o modelo de Movimento Browniano Geométrico (Geometric Brownian Motion - GBM) para simular milhares de trajetórias futuras de preços, permitindo uma análise probabilística de ativos em diferentes cenários de mercado.
🚀 Objetivo do Projeto

Diferente de projeções lineares, esta simulação visa mapear a distribuição de probabilidade de um ativo. O modelo foi testado com foco em:

    PETR4.SA: Analisando a volatilidade impactada por fatores geopolíticos globais e commodities.

    RACE.MI (Ferrari): Avaliando a resiliência e o comportamento de ativos do setor de luxo europeu.

 Tecnologias Utilizadas

    yfinance: Extração de dados históricos em tempo real.

    NumPy: Vetorização e geração de números aleatórios para as simulações.

    Pandas: Tratamento de séries temporais e retornos logarítmicos.

    Matplotlib/Seaborn: Visualização avançada com dashboards em Dark Mode.

 Conceitos Quantitativos Aplicados

    Movimento Browniano Geométrico (GBM): Cálculo baseado em Drift (μ) e Volatilidade (σ).

    Value at Risk (VaR 95%): Mensuração da perda máxima potencial em cenários de estresse.

    Intervalos de Confiança: Definição de bandas de probabilidade (P5, Mediana e P95).

    Distribuição Log-Normal: Garantia de que os preços simulados respeitem a barreira de não-negatividade.

 Visualização (Dashboard)

O script gera automaticamente um painel com:

    Trajetórias de Preço: O "leque" de possibilidades futuras ao longo do tempo.

    Histograma de Frequência: A concentração dos preços no último dia da simulação.

    Resumo Estatístico: Tabela com retorno esperado, probabilidade de lucro e métricas de risco.
