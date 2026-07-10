# Dashboard de Análise de Vendas e Faturamento - Varejo
<img width="960" height="469" alt="Gemini_Generated_Image_pklvibpklvibpklv" src="https://github.com/user-attachments/assets/6392ff48-15e6-4373-b24c-139508f6f4a8" />

📌 Visão Geral do Projeto
Este projeto consiste no desenvolvimento de um dashboard interativo no Power BI para a análise estratégica de faturamento, volume de vendas e desempenho de filiais de uma rede de varejo. O objetivo principal é transformar dados brutos em insights visuais que facilitem a tomada de decisão gerencial.

---

## 💼 Histórico do Projeto (Metodologia STAR)

### **Situação**
A empresa de varejo possuía um grande volume de dados de transações diárias armazenados de forma bruta (em tabelas de vendas). A falta de uma ferramenta centralizada dificultava o acompanhamento em tempo real dos principais indicadores de desempenho (KPIs), como o faturamento total, a quantidade de itens vendidos e a identificação de quais filiais ou canais de venda traziam o melhor retorno.

### **Tarefa**
Minha responsabilidade foi realizar a extração, o tratamento desses dados e a modelagem de um painel gerencial que unificasse essas métricas em uma única tela. O painel precisava ser intuitivo, dinâmico e permitir filtros por período e categorias.

### **Ação**
Para a execução do projeto, segui as seguintes etapas técnicas:
1. **ETL (Extração e Limpeza):** Importei os dados brutos (`fVendas`) para o **Power Query**, onde realizei a limpeza das informações, tratamento de tipos de dados (datas, valores monetários) e remoção de inconsistências.
2. **Modelagem de Dados:** Criei uma estrutura organizada criando uma tabela específica para medidas padronizadas (`_Medidas`), garantindo as boas práticas de desenvolvimento no Power BI.
3. **Cálculos com DAX:** Desenvolvi as métricas de negócio essenciais utilizando a linguagem DAX, garantindo cálculos performáticos de faturamento acumulado e contagem de itens.
4. **Design de Dashboard:** Construí o layout focado na experiência do usuário (UX), posicionando os cartões de KPIs principais no topo e utilizando gráficos de barras e linhas complementares para análises comparativas.

### **Resultado**
Como resultado prático, entreguei um produto de dados que reduz o tempo de análise da diretoria. Agora, os gestores conseguem identificar gargalos de vendas em segundos através dos filtros interativos, otimizando o planejamento estratégico da rede de lojas.

---

## 🛠️ Tecnologias Utilizadas
* **Power BI Desktop** (Modelagem e Visualização)
* **Power Query** (Processo de ETL)
* **Linguagem DAX** (Criação de Medidas)

---

## 📂 Como Visualizar o Projeto
1. Faça o download do arquivo `fVendas.pbix` disponível neste repositório.
2. Certifique-se de ter o *Microsoft Power BI Desktop* instalado em sua máquina.
3. Abra o arquivo para interagir com os gráficos e filtros.
