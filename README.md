# ✈️ Painel de Desempenho Executivo - Aviação Brasileira

![Dashboard Overview](Dashboard_Aviação_Final.png)

📥 **[Clique aqui para aceder e descarregar o ficheiro Power BI (.pbix) completo](https://drive.google.com/file/d/1ac2BKbq4cb6QXcPRLEmwdy52g7zW2-Mf/view?usp=drive_link)**

## 📌 Sobre o Projeto
Este é o módulo de Visualização de Dados de um projeto *End-to-End* focado no setor da aviação. O objetivo deste painel em Power BI é analisar **mais de 1 milhão de registos de voos**, fornecendo *insights* operacionais a executivos e diretores através de um *dashboard* de alta performance.

## 🛠️ Stack Tecnológico e Arquitetura
*   **Power BI:** Ferramenta de visualização ligada diretamente à arquitetura *cloud* (Databricks) utilizando *Personal Access Tokens* (PAT).
*   **Linguagem DAX:** Criação de medidas calculadas (`[Média Atraso Partida]`, `[% Pontualidade]`, lógicas de cancelamento).
*   **UI/UX para Dados:** Aplicação de *Data Storytelling*, paletas corporativas e *Data Bars* para direcionar a tomada de decisão.

## 🔗 Engenharia de Dados (Back-end)
A etapa de ETL (Extração, Transformação e Carga), limpeza de dados e criação da arquitetura *One Big Table* (`obt_voos`) foi realizada em **Databricks & PySpark**. 
👉 **[O código completo da Engenharia de Dados pode ser acedido no repositório pipeline-dados-voos](https://github.com/diogodforte-alt/pipeline-dados-voos)**.

## 🚀 Destaques do Dashboard
1.  **Paleta de Cores Focada:** Azul escuro corporativo para comportamentos normais e Laranja estritamente para alertas (Voos Cancelados e Atrasos).
2.  **Insights Gerados:** Identificação clara de gargalos operacionais (ex: diferença de tempo de atraso médio entre aeroportos de grande fluxo como SBGR e SBSP).
