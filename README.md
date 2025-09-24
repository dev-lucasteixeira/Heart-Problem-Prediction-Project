# Predição de Doença Cardiovascular

## 🩺 Introdução
Este projeto tem como objetivo **prever a presença de doença cardiovascular** em pacientes a partir de variáveis clínicas e demográficas.  
O trabalho utiliza **Machine Learning** para identificar quais fatores mais contribuem para o risco cardiovascular, apoiando decisões médicas preventivas.

O conjunto de dados contém informações como:
- Idade  
- Sexo  
- Pressão arterial  
- Nível de colesterol  
- Glicemia  
- Fumo, consumo de álcool e atividade física  
- Outros indicadores de saúde

---

## ❓ Perguntas-chave
Durante a análise, buscamos responder:

1. **Quais variáveis têm maior influência** na presença de doença cardiovascular?  
2. Qual é a **acurácia** de diferentes modelos de classificação (Random Forest, etc.)?  
3. Quais são os **principais fatores de risco** segundo a explicabilidade do modelo (SHAP)?  
4. É possível criar um **modelo preditivo confiável** para apoiar triagem clínica?

---

## 🧰 Tecnologias e Bibliotecas
- **Linguagem:** Python 3.x  
- **Análise de Dados:** pandas, numpy  
- **Visualização:** matplotlib, seaborn, SHAP  
- **Machine Learning:** scikit-learn (RandomForestClassifier, métricas, pipeline)  
- **Ambiente:** Jupyter Notebook

---

## 📂 Estrutura do Projeto
├── data/ # Dados brutos ou processados
├── notebooks/ # Jupyter notebooks com EDA, modelagem e SHAP
├── src/ # Scripts auxiliares (pré-processamento, funções)
└── README.md # Este arquivo

yaml
Copy code

---

## 🚀 Passos Principais
1. **Exploração e Limpeza dos Dados**  
   - Tratamento de valores ausentes e outliers  
   - Análise estatística descritiva  

2. **Modelagem Preditiva**  
   - Treinamento do modelo Random Forest  
   - Avaliação com métricas: Acurácia, F1-Score, Matriz de Confusão  

3. **Interpretação do Modelo**  
   - Uso do **SHAP** para identificar as variáveis mais importantes  
   - Visualização de summary plots e force plots

---

## 📊 Resultados
- O modelo Random Forest obteve **alta acurácia (substituir pelo valor obtido)**.  
- As variáveis mais relevantes foram **(ex.: idade, pressão arterial, colesterol)**.  
- Os gráficos SHAP mostraram claramente o impacto de cada feature no risco de doença cardiovascular.

---

## ▶️ Como Reproduzir
1. **Clone** este repositório:
   ```bash
   git clone https://github.com/<seu_usuario>/<nome_do_repo>.git
Crie o ambiente virtual e instale as dependências:

bash
Copy code
pip install -r requirements.txt
Abra os notebooks:

bash
Copy code
jupyter notebook


🏁 Próximos Passos
Testar outros algoritmos (XGBoost, LightGBM).
Ajustar hiperparâmetros com Grid Search/Optuna.
