#  Muito bem-vindo(a) ao meu Portfólio de Análise e Ciência de Dados! 🎲
---

## Sobre

Olá! Eu sou o **Daniel Estrella Couto**.

→ Atuo há **2 anos com projetos práticos em Análise e Ciência de Dados**, desenvolvendo soluções com foco em extração de valor, apoio à decisão e automação inteligente.  

→ Tenho mais de **10 anos de experiência com dados aplicados à engenharia civil**, atuando com planejamento, indicadores, relatórios, integração de informações e otimização de processos.  

→ Possuo domínio técnico em **Python, SQL, Power BI, Looker e GCP (BigQuery, Data Lakes)**, com experiência em pipelines de dados, dashboards, análise exploratória e visualização interativa.    

→ Experiência em **análise de dados e estatística aplicada**, incluindo análise descritiva, correlação, testes de hipótese, intervalos de confiança e experimentos com testes A/B.  

→ Detenho conhecimento apurado em  **Machine Learning**, com expertise em algoritmos supervisionados (classificação com Random Forest, XGBoost, LightGBM, SVM; regressão com Linear, Ridge, Lasso) e **técnicas não-supervisionadas** (K-Means, DBSCAN, PCA). Experiência prática em validação cruzada, otimização de hiperparâmetros, seleção de features e definição de métricas alinhadas ao negócio (Precision, Recall, F1-Score, AUC-ROC).

→ Tenho conhecimento prático em redes neurais (MLP, CNN, LSTM) com soluções aplicadas em **Visão Computacional** (classificação de imagens, Transfer Learning), **Processamento de Linguagem Natural** (análise de sentimentos, classificação de textos) e **Deep Learning** (arquiteturas e otimização). Experiência com TensorFlow/Keras e PyTorch, incluindo fine-tuning de modelos pré-treinados e técnicas de regularização.

→ Tenho experiência em desenvolvimento e consumo de **APIs**, criando soluções REST em produção (FastAPI, AWS) e integrando APIs de IA (Vertex AI, Azure Cognitive Services) com processamento multimodal, autenticação em nuvem e manipulação de dados entre sistemas.
  
→ Formação complementar pela **Alura** em **Python (análise de dados), Data Science, Machine Learning, SQL avançado, Power BI e Metodologias Ágeis**.

---

## Tech Stack

Data & Analytics: Python · SQL · Pandas · NumPy · Scikit-learn · Excel Avançado
Machine Learning: XGBoost · LightGBM · CatBoost · Random Forest · SVM
MLOps & Automação: MLflow · DagsHub · DVC · GitHub Actions · Pytest
Cloud & Infrastructure: AWS (Lambda, API Gateway, ECR, S3, CloudWatch) · GCP (BigQuery, Data Lakes) · Docker
Visualização & BI: Power BI · Looker Studio · Matplotlib · Seaborn
Versionamento & Colaboração: Git · GitHub

---

## Projetos

---

> 🚧 **Desculpe a poeira!** Este portfólio está em construção e expansão constante — projetos já finalizados estão sendo organizados e adicionados para melhor atender suas curiosidades e mostrar, com dados, o que eu posso construir.

---

### Quantum Finance – Plataforma de Machine Learning para Score de Crédito | Python · AWS · MLOps · Streamlit

**Objetivo do projeto:**  
Desenvolver uma **plataforma completa de Machine Learning end-to-end** que demonstra o ciclo de vida de uma solução de inteligência artificial em produção, desde o pré-processamento de dados até a entrega de uma aplicação funcional para o usuário final, com foco em previsão de score de crédito.

**Contexto de negócio:**  
A necessidade de automatizar e escalar a previsão de score de crédito exigiu uma solução robusta que não apenas entregasse um modelo preciso, mas que também garantisse reprodutibilidade, rastreabilidade e governança em um ambiente de produção. O projeto integra três camadas especializadas: modelagem e experimentação, API de inferência serverless e aplicação web interativa, com automação completa via CI/CD.

**Ferramentas e Tecnologias:**  
- **Engenharia de Dados:** Python 3.10+, Pandas, NumPy, DVC (versionamento de dados)
- **Modelagem de ML:** Scikit-learn, LightGBM, CatBoost, XGBoost, StackingClassifier
- **MLOps:** MLflow, DagsHub, GitHub Actions, Pytest
- **Infraestrutura e Backend:** AWS (Lambda, API Gateway, ECR, S3, CloudWatch), Docker
- **Frontend:** Streamlit, Streamlit Cloud
- **Versionamento:** Git, GitHub

**Técnicas aplicadas:**  
- [✓] Pré-processamento avançado com imputação por clustering KMeans e tratamento de outliers
- [✓] Mitigação de data leakage com identificação preventiva de variáveis problemáticas
- [✓] Engenharia de features com normalização e padronização de dados
- [✓] Experimentação sistemática com múltiplos algoritmos (Random Forest, XGBoost, LightGBM, CatBoost)
- [✓] Otimização de hiperparâmetros com GridSearchCV e RandomizedSearchCV
- [✓] Construção de ensembles com StackingClassifier combinando LightGBM e CatBoost
- [✓] Validação cruzada externa para garantir generalização robusta
- [✓] Métricas alinhadas ao negócio, priorizando Recall na classe de alto risco
- [✓] Testes automatizados com Pytest para integridade do modelo e código
- [✓] CI/CD com GitHub Actions orquestrando deploy entre repositórios
- [✓] Arquitetura serverless na AWS com monitoramento via CloudWatch
- [✓] API RESTful com autenticação segura e observabilidade em produção

**Resultados alcançados:**  
- [✔] Dataset otimizado: balanceado, livre de data leakage e pronto para modelagem
- [✔] Modelo de alta performance: Ensemble Stacking alcançou **Recall superior a 0.83** na classe 'Poor' em validação cruzada externa
- [✔] Pipeline reprodutível: solução totalmente documentada desde ingestão até registro do modelo
- [✔] Automação completa: CI/CD integrado sincronizando modelo, API e frontend
- [✔] Observabilidade em produção: monitoramento contínuo com CloudWatch e auditoria de predições em S3
- [✔] API escalável: arquitetura serverless garantindo alta disponibilidade e elasticidade
- [✔] Interface intuitiva: aplicação Streamlit com consumo em tempo real da API

**Estrutura do Projeto:**  
O projeto está organizado em três repositórios especializados:

| Repositório | Descrição |
| :--- | :--- |
| **[Modelagem e Experimentação](https://github.com/DanielllCouto/quantum-finance-credit-score)** | Pipeline completo de dados, notebooks de experimentação, treinamento e testes. Implementa pré-processamento avançado, engenharia de features e otimização de modelos. |
| **[API de Inferência](https://github.com/DanielllCouto/quantum-finance-api-credit-score)** | Código da API RESTful, infraestrutura como código e pipeline de CI/CD. Responsável por servir o modelo em produção com alta disponibilidade e observabilidade. |
| **[Frontend com Streamlit](https://github.com/DanielllCouto/quantum-finance-app-credit-score)** | Aplicação web interativa que consome a API de inferência. Implementa normalização de dados, montagem de payloads e exibição visual de resultados. |

**Fluxo End-to-End:**  
Dados brutos → Pré-processamento e engenharia de features → Experimentação com múltiplos algoritmos → Rastreamento de experimentos no MLflow → Registro do modelo campeão → Testes automatizados → Deploy automático da API na AWS → Consumo via aplicação Streamlit

🔗 **[Acessar visão geral do projeto no GitHub](https://github.com/DanielllCouto/quantum-finance-credit-score-project)**

---


###  TheLook Fintech – Data Analytics e Visualização Estratégica | BigQuery · Looker · SQL

**Objetivo do projeto:**  
Fornecer respostas analíticas para questões críticas do time financeiro da fintech por meio de modelagem relacional, relatórios otimizados e dashboards estratégicos integrados à nuvem.

**Contexto de negócio:**  
A TheLook Fintech precisava monitorar melhor seu fluxo de caixa, compreender o comportamento dos clientes que contratam empréstimos, identificar riscos geográficos e propor evoluções estratégicas a partir de dados internos e externos. O projeto foi pensado para atender diferentes níveis de tomada de decisão — do operacional ao estratégico — com entregas automatizadas e visuais acessíveis.

**Ferramentas e Tecnologias:**  
- **Cloud:** Google Cloud Platform – BigQuery, Looker Studio Enterprise  
- **Linguagem:** SQL  
- **Ambiente:** Looker Enterprise, BigQuery Console, VSCode  
- **Versionamento:** GitHub

**Técnicas aplicadas:**  
- [✓] Modelagem relacional e criação de tabelas auxiliares no BigQuery  
- [✓] Integração de dados externos com transformação via SQL  
- [✓] Agregações, filtros, rankeamentos e desaninhamento de dados  
- [✓] Visualizações interativas e condicionais no Looker  
- [✓] Ativação de funcionalidades como filtros cruzados e autoatualização  
- [✓] Estruturação documental e sugestões de indicadores futuros

**Resultados alcançados:**  
- [✔] Monitoramento do fluxo de caixa com dados agregados por período  
- [✔] Potencial aumento de vendas com relatórios de motivos dos empréstimos  
- [✔] Redução do risco de inadimplência com rastreamento de regiões críticas  
- [✔] Detecção de clientes com alto potencial de fidelização para ações de marketing e retenção  
- [✔] Dashboards responsivos com indicadores-chave de crédito e risco  
- [✔] Base consolidada para projetos futuros com IA e automações

**Visualização de parte da entrega final:**  
![Dashboard Final - TheLook Fintech](https://github.com/DanielllCouto/thelook-fintech-data-analytics-gcp/blob/main/imagens/fase%205_8-%20dashboad%20final.png)  
*Dashboard interativo com 4 visualizações principais, incluindo alertas e atualizações automatizadas.*

🔗 [Acessar projeto no GitHub](https://github.com/DanielllCouto/thelook-fintech-data-analytics-gcp)

---

Conecte-se comigo no [LinkedIn](https://www.linkedin.com/in/daniel-estrella-couto) ou explore outros repositórios aqui no [GitHub](https://github.com/DanielllCouto)

