# projeto_mack

# HR Analytics: Predição de Evasão de Colaboradores

Este projeto foi desenvolvido como parte da disciplina **DATA SCIENCE EXPERIENCE** do **MBA em Engenharia de Dados da Universidade Presbiteriana Mackenzie**. O objetivo principal é aplicar um pipeline completo de ciência de dados para prever a evasão (attrition) de colaboradores com base em dados sintéticos de RH inspirados em contextos reais.

## Autor

**Gustavo de Paula de Sousa**  
RA: 10742688  
Curso: MBA em Engenharia de Dados  
Universidade: Universidade Presbiteriana Mackenzie  

---

## Objetivo do Projeto

Construir modelos preditivos capazes de identificar funcionários com maior risco de evasão, permitindo à empresa tomar ações preventivas baseadas em dados. O projeto foca também na explicabilidade dos resultados e na geração de valor para o negócio.

---

## Estrutura do Projeto

├── data/ # Dados brutos e tratados
├── notebooks/ # Notebooks com análises e desenvolvimento do modelo
├── src/ # Scripts Python modularizados
│ ├── preprocessing.py # Limpeza e transformação dos dados
│ ├── features.py # Engenharia de variáveis
│ ├── modeling.py # Treinamento e avaliação dos modelos
│ └── utils.py # Funções auxiliares
├── visualizations/ # Gráficos e imagens geradas durante a análise
├── requirements.txt # Bibliotecas e versões utilizadas
└── README.md # Documentação do projeto

yaml
Copiar
Editar

---

## Tecnologias Utilizadas

- Python 3.11
- Polars
- Scikit-Learn
- XGBoost
- SHAP
- Plotly
- Imbalanced-Learn
- Streamlit

---

## 📊 Metodologia Aplicada

1. **Exploração de Dados (EDA)**  
   Renomeação de colunas, visualização de distribuições e análise estatística.

2. **Engenharia de Atributos**  
   Criação de novas variáveis baseadas em lógica de negócio (ex: senioridade, perfil de risco).

3. **Modelagem**  
   Aplicação de múltiplos algoritmos: Regressão Logística, Random Forest, XGBoost e MLP.  
   Técnicas de desbalanceamento aplicadas: SMOTE, Class Weights.

4. **Validação e Otimização**  
   Validação cruzada estratificada, GridSearchCV para hiperparâmetros, avaliação com métricas robustas.

5. **Interpretação e Visualização**  
   Análises com SHAP, visualizações com Plotly e recomendações práticas.

6. **Deployment**  
   Protótipo de aplicação com Streamlit para demonstrar a viabilidade de uso prático.

---

## 📈 Métricas Utilizadas

- F1-Score e F2-Score (ênfase em Recall)
- AUC-PR (curva precisão-recall)
- MCC (Coeficiente de Correlação de Matthews)
- Acurácia Balanceada
- Otimização de threshold

---

## Requisitos

Instale os pacotes com:

```bash
pip install -r requirements.txt
Observações
O código é original e foi desenvolvido especificamente para esta atividade.

Todas as decisões técnicas foram justificadas ao longo do notebook e nos scripts.

As visualizações estão disponíveis na pasta visualizations/.

Licença
Este projeto é de uso acadêmico, sem fins comerciais.
