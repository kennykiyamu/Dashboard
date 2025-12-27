# 📊 Projeto Dashboard de Assinaturas

## 📌 Visão Geral
Este projeto consiste em um **dashboard interativo desenvolvido em Excel**, com foco na análise de **assinaturas de serviços** (planos, renovações e evolução mensal).  

O arquivo `Dashboard.xlsx` organiza dados brutos, cálculos analíticos e elementos visuais para apoiar a tomada de decisão, seguindo uma estrutura clara e organizada.

---

## 🗂 Estrutura do Arquivo

O arquivo `Dashboard.xlsx` é composto pelas seguintes abas:

### 1️⃣ Assets
- Paleta de cores utilizada no dashboard  
- Padronização visual (cores positivas, negativas e neutras)  
- Suporte à consistência visual do painel  

### 2️⃣ Bases
- Base de dados principal do projeto  
- Contém informações como:
  - ID do assinante  
  - Nome  
  - Tipo de plano  
  - Data de início  
  - Renovação automática  
  - Informações temporais (ex.: mês de assinatura)  
- Esta aba **não deve ser alterada diretamente**, pois alimenta os cálculos e gráficos

### 3️⃣ Cálculos
- Tabelas auxiliares e métricas derivadas da base de dados  
- Exemplos de cálculos:
  - Quantidade de assinaturas por mês  
  - Distribuição por tipo de plano  
  - Indicadores agregados (KPIs)  
- Atua como camada intermediária entre os dados brutos e o dashboard

### 4️⃣ Dashboard
- Painel visual final  
- Contém gráficos, indicadores e tabelas dinâmicas  
- Permite análise rápida e intuitiva dos dados

---

## 📊 Dados Utilizados

Os dados utilizados são **dados estruturados de assinaturas**, organizados em formato tabular, representando eventos de contratação e características dos assinantes.

---

## 🔁 Instruções para Reprodução

### Pré-requisitos
- Microsoft Excel (Excel 2019 ou superior recomendado)
- Conhecimento básico em tabelas e gráficos no Excel

### Passo a passo
1. Abra o arquivo `Dashboard.xlsx`
2. Para utilizar novos dados:
   - Insira ou substitua registros **apenas na aba `Bases`**
3. Verifique se os cálculos da aba `Cálculos` foram atualizados corretamente
4. Atualize as tabelas e gráficos:
   - Menu **Dados → Atualizar Tudo**
5. Acesse a aba `Dashboard` para visualizar os resultados

---

## 🛠 Boas Práticas
- Evite editar fórmulas sem conhecimento prévio
- Mantenha o padrão de datas e categorias ao inserir novos dados
- Não exclua colunas da aba `Bases`

---
