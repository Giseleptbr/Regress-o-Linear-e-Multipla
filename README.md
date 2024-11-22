# Regressao-Linear-e-Multipla

Este repositório apresenta a implementação de modelos de regressão linear simples e múltipla utilizando Python. O projeto inclui a análise das relações entre variáveis e a criação de um modelo estatístico preditivo.

---

## **Objetivos**
1. Explorar as relações entre altura, idade, salário e peso.
2. Aplicar regressão linear simples e múltipla.
3. Avaliar a qualidade dos modelos usando métricas estatísticas.
4. Implementar predições baseadas em entrada do usuário.

---

## **Etapas do Processo**
### **1. Regressão Linear Simples**
- **Descrição**: Modelo que utiliza apenas a altura como variável independente para estimar o peso.
- **Técnicas**:
  - Cálculo dos coeficientes da reta.
  - Análise do coeficiente de determinação (\( R^2 \)).
  - Gráfico de dispersão com a reta ajustada.
  - Correlação de Pearson para verificar a força da relação linear.

### **2. Regressão Linear Múltipla**
- **Descrição**: Modelo que considera múltiplas variáveis independentes (altura, idade e salário) para prever o peso.
- **Técnicas**:
  - Adição de constantes para ajustar o modelo.
  - Análise detalhada dos coeficientes do modelo.
  - Incremento de variáveis para avaliar impacto.
  - Geração de um resumo estatístico do modelo com \( p \)-valores e \( R^2 \text{ ajustado} \).

### **3. Análise Estatística**
- **Correlação**: Geração de uma matriz de correlação para identificar relações entre variáveis.
- **VIF**: Cálculo do Fator de Inflação da Variância para detectar colinearidade.

### **4. Predição**
- **Descrição**: Ferramenta interativa que estima o peso médio com base na altura fornecida pelo usuário.

---

## **Resultados**
Os resultados incluem:
- Coeficientes da regressão linear simples e múltipla.
- Gráfico de dispersão com a reta ajustada.
- Resumo estatístico do modelo (incluindo métricas como \( R^2 \)).
- Matriz de correlação e análise de colinearidade (VIF).
- Predições baseadas em entradas hipotéticas.

---

## **Tecnologias Utilizadas**
- **Python**: Linguagem principal do projeto.
- **Bibliotecas**:
  - `numpy`: Manipulação de arrays e cálculo de métricas.
  - `scipy`: Cálculo da correlação de Pearson.
  - `matplotlib`: Criação de gráficos.
  - `statsmodels`: Modelagem estatística.
  - `pandas`: Manipulação de dados tabulares.
