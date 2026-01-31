# 📊 Análise de Dados: Otimização de Vendas em Rede de Varejo

Este projeto apresenta uma análise exploratória de vendas de uma rede de lojas de bermudas, com o objetivo de identificar oportunidades de crescimento de faturamento. 

> **Status do Projeto:** Concluído 🚀

## 🎯 O Desafio
Aumentar as vendas de uma rede de 5 lojas distribuídas em diferentes regiões (Campinas, SP, RJ, Uberlândia e Sorocaba).

## 🛠️ Ferramentas Utilizadas
* **Python** (Linguagem principal)
* **Pandas** (Manipulação e tratamento de dados)
* **Google Colab** (Ambiente de desenvolvimento)

## 🔍 Descobertas Chave (Insights)

### 1. Performance por Unidade
Identificamos que a loja **Iguatemi Campinas** lidera o faturamento com **R$ 41.720,00**, enquanto as demais unidades operam em uma média significativamente inferior.

### 2. O Caso da "Bermuda Liso" 🩳
Durante a análise, descobrimos um insight crítico de negócio:
* O produto **Bermuda Liso** gerou um faturamento de **R$ 36.581,00**.
* **Oportunidade Detectada:** Este produto foi vendido exclusivamente na unidade de Campinas. As outras 4 lojas apresentaram estoque/vendas zeradas deste item específico.

### 3. Impacto Financeiro
A "Bermuda Liso" representa cerca de **87% do faturamento da loja líder**. A ausência deste SKU (produto) nas outras unidades é o principal gargalo para o crescimento da rede.

## 🚀 Recomendações Estratégicas
1. **Equalização de Estoque:** Realizar a transferência imediata do modelo "Bermuda Liso" para as outras 4 unidades.
2. **Projeção de Ganho:** Caso as outras unidades repliquem apenas 50% do sucesso de Campinas com este produto, a rede pode ter um incremento de faturamento estimado em mais de **R$ 70.000,00**.

---
## 👨‍💻 Como rodar o projeto
1. Faça o download do arquivo `Vendas.xlsx - Plan1.csv` neste repositório.
2. Abra o arquivo `.ipynb` no Google Colab.
3. Faça o upload da base de dados e execute as células.
