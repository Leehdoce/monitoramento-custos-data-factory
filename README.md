# 💰 Monitoramento de Custos no Azure Data Factory (Projeto Conceitual)

**Autora:** Letícia Montenegro  
**Desafio DIO:** Criando um Monitoramento de Custos no Data Factory  
**Tipo de Projeto:** Conceitual / Simulado  

---

## 🎯 Objetivo
Este projeto tem como objetivo demonstrar o entendimento sobre **monitoramento de custos no Azure Data Factory**, explicando como seria feito o processo real de criação, configuração e acompanhamento de custos na nuvem Azure.

---

## 🧩 Etapas Conceituais do Projeto

1. **Criação do Recurso (Data Factory)**  
   - Seria criado no portal Azure com nome: `datafactory-monitoramento`.  
   - Região: *East US* (para reduzir custo).  
   - Recurso principal para orquestração de pipelines de dados.  

2. **Criação de Pipelines**  
   - Um pipeline de exemplo: `CargaDiariaCustos`.  
   - Atividades simuladas:
     - Copiar dados de um Azure Blob Storage.  
     - Processar e armazenar em um SQL Database.  
     - Registrar logs de execução.  

3. **Monitoramento e Custos**  
   - Uso do **Azure Monitor** e **Cost Management** para acompanhar consumo.  
   - Configuração de **orçamentos (budgets)** e **alertas automáticos** para evitar gastos excessivos.  
   - Visualização de gráficos e custos estimados por pipeline.

---

## 📊 Dashboard Simulado

O dashboard apresentaria:
- Custo total por pipeline  
- Execuções bem-sucedidas vs. falhas  
- Alertas de orçamento e consumo  

📸 Exemplo ilustrativo:  
![Dashboard Simulado](images/dashboard-simulado.png)

*(Imagem ilustrativa — criada apenas para representar o conceito do projeto.)*

---

## 💡 Insights e Aprendizados
- Compreendi os componentes do **Azure Data Factory** (Pipelines, Linked Services e Datasets).  
- Entendi como o **Cost Management** ajuda a visualizar o uso e custo de recursos.  
- Aprendi a importância de monitorar execução e definir budgets para evitar surpresas financeiras.  
- Reforcei conceitos de **otimização e governança em ambientes de nuvem**.

---

## 🧠 Conceitos-Chave Aplicados
- Data Orchestration  
- Monitoramento de custos  
- Cloud Cost Optimization  
- Alertas e Automação  

---

## 🔗 Repositório do Projeto
[👉 Acesse o repositório no GitHub](https://github.com/Leehdoce/monitoramento-custos-data-factory)

---

📚 **Feito por [Letícia Montenegro](https://github.com/Leehdoce)**  
💻 *Projeto conceitual desenvolvido para o desafio DIO*
