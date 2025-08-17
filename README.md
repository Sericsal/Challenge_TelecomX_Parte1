# 📊 Análise de Evasão de Clientes (Churn) da TelecomX

Este notebook contém uma **análise exploratória de dados (EDA)** dos clientes da **TelecomX**, aplicada a um cenário de negócios real, com o objetivo de identificar padrões associados à **evasão de clientes (Churn)**.

---

## 📂 Conjunto de Dados
O dataset utilizado é **`TelecomX_Data.json`**, contendo informações sobre clientes da empresa, como:

- 👤 Dados demográficos
- 📞 Serviços contratados (Telefone, Internet, TV, Streaming)
- 💳 Informações de conta e pagamentos
- ❌ Status de churn (Cancelou: Sim / Não)

---

## 🔍 Etapas da Análise Exploratório (EDA)

### 🧹 Extração e Limpeza de Dados
- Carregamento dos dados
- Combinação de estruturas aninhadas
- Renomeação de colunas
- Tratamento de valores nulos e "falso nulos"

### 🔄 Transformação de Dados
- Conversão de tipos de dados
- Padronização de valores categóricos

### 📈 Análise Exploratória
- ⏳ Comparativo entre **clientes idosos e não idosos** em relação a tempo de permanência e cobranças
- 👥 Distribuição de clientes e **taxas de cancelamento por gênero**
- 🎁 Comparativo entre clientes com **pacote completo** e **pacote incompleto** e suas taxas de cancelamento
- 💳 Identificação dos **métodos de pagamento mais comuns** entre clientes que cancelaram
- 📊 Análise da distribuição de variáveis numéricas (**Meses_Permanencia, Cobranca_Total**) para clientes que cancelaram e não cancelaram (histogramas)
- 🔍 Determinação do **grupo com maior taxa de cancelamento**

### 📊 Visualizações
- 📉 **Gráficos de barras** para comparar churn por categorias  
- 📈 **Histogramas** para distribuição de variáveis numéricas  
- 📦 **Boxplots** para comparar tempo de permanência por churn  

### 📄 Relatório Final
- Compilação das descobertas, conclusões e recomendações estratégicas

---

## 💡 Principais Descobertas
- ⏱️ Clientes com **menor tempo de permanência** e sem **pacote completo** têm maior probabilidade de cancelar
- 💳 O método de pagamento **"Cheque eletrônico"** está fortemente associado a clientes que cancelaram
- 👩‍🦳👨 Gênero e status de idoso têm menor impacto direto no churn comparado ao tempo de permanência e tipo de pacote
- ⚠️ O grupo com **maior taxa de cancelamento**: **Clientes com Pacote Incompleto**
- 🏆 Grupo **mais fiel**: clientes que contratam **por dois anos (Bianual)**

---

## ⚡ Como Executar o Notebook
1. Abra o notebook em um ambiente Python com as bibliotecas: `pandas`, `numpy`, `matplotlib`  
2. Execute as células **sequencialmente** para replicar a análise  
3. Certifique-se de que o arquivo **`TelecomX_Data.json`** esteja acessível (upload local ou via URL)  

---

## 📄 Relatório Detalhado
Consulte a seção **"📄 Relatório Final"** no notebook para uma descrição aprofundada das análises, conclusões e recomendações.