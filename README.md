# **Projeto de Machine Learning: Detecção de falhas cardíacas**

## **Descrição do Projeto**  
Este projeto foi desenvolvido para aprofundar os fundamentos de **Machine Learning** aprendidos no livro Hands On do Aurélien Géron, aplicando técnicas de análise exploratória de dados (EDA), pré-processamento, modelagem e avaliação de um modelo. Utilizei um dataset com dados de diversos pacientes com problemas cardíacos:

| **Coluna**          | **Descrição**                                                                 |
|----------------------|-------------------------------------------------------------------------------|
| **Age**             | Idade da pessoa (em anos).                                                   |
| **Sex**             | Sexo da pessoa. Valores:                                                     |
|                      | - "M" para Masculino                                                        |
|                      | - "F" para Feminino                                                         |
| **ChestPainType**    | Tipo de dor no peito. Valores possíveis:                                     |
|                      | - "ATA": Angina Típica                                                     |
|                      | - "NAP": Angina Atípica                                                    |
|                      | - "ASY": Assintomático                                                     |
|                      | - "TA": Angina Transitória                                                 |
| **RestingBP**        | Pressão arterial em repouso (mmHg).                                          |
| **Cholesterol**      | Nível de colesterol sérico (mg/dl).                                          |
| **FastingBS**        | Glicemia de jejum. Valores:                                                 |
|                      | - 1 se glicemia ≥ 120 mg/dl                                                 |
|                      | - 0 caso contrário                                                          |
| **RestingECG**       | Resultado do eletrocardiograma em repouso. Valores:                         |
|                      | - "Normal"                                                                 |
|                      | - "ST": Anomalias de onda ST/T                                             |
|                      | - "LVH": Hipertrofia ventricular esquerda                                  |
| **MaxHR**            | Frequência cardíaca máxima atingida.                                        |
| **ExerciseAngina**   | Angina induzida por exercício. Valores:                                     |
|                      | - "Y" para Sim                                                             |
|                      | - "N" para Não                                                             |
| **Oldpeak**          | Depressão do segmento ST induzida por exercício em relação ao repouso.       |
| **ST_Slope**         | Inclinação do segmento ST durante o exercício. Valores:                     |
|                      | - "Up": Ascendente                                                        |
|                      | - "Flat": Plana                                                           |
|                      | - "Down": Descendente                                                     |
| **HeartDisease**     | Diagnóstico de doença cardíaca. Valores:                                    |
|                      | - 1 para presença de doença cardíaca                                       |
|                      | - 0 para ausência de doença cardíaca                                       |

---

## 🛠️ **Tecnologias e Bibliotecas Utilizadas**  
- **Python** 🐍  
- **Pandas** 📑  
- **NumPy** 🔢  
- **Matplotlib** 📊  
- **Scikit-learn** 🤖  

---

## 🚀 **Principais Etapas do Projeto**  

### 1️⃣ **Análise Exploratória de Dados (EDA)**  
- Histogramas e gráficos de dispersão.  
- Mapas de correlação para identificar relações entre variáveis.  

### 2️⃣ **Aquisição e Preparação dos Dados**  
- Pré-processamento com **pipelines de dados** para garantir as boas práticas de machine learning.  

### 3️⃣ **Modelagem**  
- Algoritmos aplicados: **Florestas aleatórias**.  
- Ajuste de hiperparâmetros com **Grid Search** e **Random Search**.  
- Validação cruzada para garantir robustez nos resultados.  

### 4️⃣ **Avaliação**  
- Métricas utilizadas: F1 score, recall, presicion, ROC, AUC  

---

## 📊 **Resultados**  
Os modelos foram avaliados com métricas robustas, e gráficos comparativos entre valores reais e previstos foram gerados para melhor visualização dos resultados.

---

## 🖼️ **Visualizações Principais**  
- Histogramas mostrando a distribuição das variáveis.  
- Gráficos de dispersão para identificar padrões.  
- Comparação visual entre previsões e valores reais (Matriz de confusão).  

---

## 📚 **Como Executar o Projeto**  

1. Clone este repositório:  
```bash
git clone https://github.com/phaa/hearth-failure-prediction.git
```

2. Crie um ambiente Anaconda:
```bash
conda create -n env python=3.9
```

3. Ative o ambiente
```bash
conda activate env
```

4. Instale as dependências:
```bash
conda install --file requirements.txt
```

5. Execute o Jupyter Lab: 
```bash
jupyter lab
```

5. Abra o arquivo Hearth.ipynb e execute as células.

