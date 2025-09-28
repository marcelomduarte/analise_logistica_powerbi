# 🚚 Análise Logística

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black) ![Power Query](https://img.shields.io/badge/Power%20Query-107C41?style=for-the-badge&logo=microsoft-excel&logoColor=white) ![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)

## 🎯 Sobre o Projeto

Dashboard interativo desenvolvido em Power BI para análise da performance logística, fornecendo indicadores-chave que permitem avaliar a eficiência do transporte, prazos de entrega e ocorrências relacionadas às operações. O projeto oferece insights estratégicos para otimização da cadeia de suprimentos e melhoria da eficiência operacional.

## 🖼️ Visualizações do Dashboard

### Página Inicial

![Capa](/reports/exports/images/slide1.png)
*Interface principal com acesso rápido às análises*

### Dashboard Analítico

![Análise](/reports/exports/images/slide2.png)
*Visão completa dos KPIs logísticos e análises detalhadas*

## 🌐 Dashboard Online

[![Acessar Dashboard Power BI](https://img.shields.io/badge/🔗%20Acessar%20Dashboard%20Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://app.powerbi.com/view?r=eyJrIjoiOGQ1Y2FhYjYtMGQ3Yy00M2M1LThhYmEtNGJmNzdjZTk3MjI4IiwidCI6IjdlYmVmODBjLTEwMjctNDEyOS1iNDg0LWNjZjJiZDNmZDU4ZiJ9&pageName=ReportSection48e0040a0e337e0e0b00)

## 💡 Insights e Benefícios

- Monitoramento de volumes expedidos e faturamento

- Análise OTIF (On Time In Full) por período

- Performance de transportadoras (OTD - On Time Delivery)

- Ocorrências em Notas Fiscais (Avaria e Extravio)

- Mapa interativo com origem das entregas

- Métricas estratégicas como Order Cycle Time e peso bruto movimentado

Esses indicadores permitem uma tomada de decisão orientada a dados, com foco em redução de custos logísticos, melhoria do nível de serviço e otimização da operação.

## 📁 Estrutura do Projeto

```text
📁 analise_estoque_powerbi/
├── 📁 data/                              
│   └── raw/                                              # Dados brutos 
│      ├── NotasFiscais/                                                             
│      └── Clientes.xlsx                             
│ 
├── 📁 reports/                                           # Relatórios e análises
│   ├── powerbi/                                         
│   │   └── link_dashboard_logistica_v1.txt         
│   └── exports/                                           # Arquivos exportados
│       └── images/
│           ├── slide1.png                                 # Capturas de Tela
│           └── slide2.png                      
│
└── 📄 README.md                                           # Documentação do projeto
```

## 🛠️ Tecnologias Utilizadas

- **Excel**: Fonte de dados estruturada (bd_estoque.xlsx)
- **Power Query**: ETL (Extract, Transform, Load) e transformação de dados
- **Power BI Desktop**: Desenvolvimento do dashboard e modelagem de dados
- **DAX (Data Analysis Expressions)**: Criação de medidas calculadas e KPIs
- **Power BI Service**: Publicação e compartilhamento online do dashboard

## ⚙️ Processo de Desenvolvimento

### 1. **Extração de Dados (Extract)**

- Importação de dados de múltiplas fontes (Excel, CSV)
- Conexão com bases de notas fiscais e cadastro de clientes
- Validação da integridade dos dados

### 2. **Transformação (Transform)**

- Limpeza e padronização dos dados com Power Query
- Criação de dimensões e tabelas fato
- Tratamento de dados ausentes e inconsistências

### 3. **Modelagem de Dados**

- Desenvolvimento do modelo estrela (Star Schema)
- Criação de relacionamentos entre tabelas
- Otimização da performance das consultas

## 📋 Recomendações Estratégicas

1. **Aprimorar Transportadoras** → Incentivar melhoria de performance em empresas com baixo índice de entregas no prazo

2. **Reduzir Ocorrências** → Monitorar causas de avarias e extravios para diminuição de perdas

3. **Otimizar Rotas** → Analisar trajetos e ajustar planos de transporte para redução do Order Cycle Time
