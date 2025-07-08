# 📊 Análise de Evasão de Clientes – TelecomX

Este projeto tem como objetivo analisar dados de clientes de uma empresa de telecomunicações fictícia, a **TelecomX**, para identificar padrões de evasão (churn) e sugerir ações estratégicas para reduzir a perda de clientes.

---

## 📁 Estrutura do Projeto

- `TelecomX_BR.ipynb` – Notebook principal com todo o fluxo do projeto:
  - Importação e visualização dos dados
  - Limpeza e tratamento
  - Criação de colunas auxiliares
  - Análise exploratória com visualizações
  - Conclusões e recomendações
- `TelecomX_Data.json` – Arquivo de dados original em formato JSON
- `README.md` – Este arquivo de descrição do projeto

---

## 🎯 Objetivo

Entender quais fatores influenciam na decisão dos clientes de cancelarem o serviço e propor soluções baseadas em dados reais.

---

## 🧹 Etapas do Projeto

### 1. Importação e tratamento dos dados
- Conversão de colunas categóricas ("Yes"/"No") para binárias (1/0)
- Normalização de colunas aninhadas
- Criação de colunas úteis como `contas_diarias` e `idoso`
- Conversão de dados numéricos salvos como texto

### 2. Análise exploratória
- Gráficos de contagem (`countplot`) para comparar evasão por perfil
- Boxplots para comparar variáveis financeiras entre quem evadiu e quem ficou
- Heatmap de correlação
- Pie chart com proporção geral de churn

### 3. Geração de insights
- Contrato mensal, falta de serviços adicionais e método de pagamento eletrônico estão entre os principais fatores associados à evasão

### 4. Recomendação de ações
- Incentivos para contratos de longo prazo
- Ofertas de pacotes combinados (segurança, suporte, backup)
- Benefícios para clientes que adotam pagamento automático
- Monitoramento de perfis de risco com base nos dados históricos

---

## 📈 Principais Ferramentas Utilizadas

- Python 3
- Pandas
- Matplotlib
- Seaborn
- Google Colab

---

## 🧠 Conclusões

Clientes com contratos curtos, poucos serviços adicionais e menor tempo de permanência são os que mais evadem. A empresa pode reduzir o churn com ações direcionadas de retenção e fidelização, focando nesses grupos.

---

## 🔗 Autor

**Pedro Camargo**  
Projeto desenvolvido para fins de estudo e prática de análise de dados com Python.

