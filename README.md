# 📊 Análise Exploratória de Dados (EDA) - Netflix Daily Top 10

## 🎯 Objetivo
Este projeto tem como objetivo realizar uma **Análise Exploratória de Dados (EDA)** na base `daily_top_10_netflix.csv`, identificando padrões, verificando a qualidade dos dados e extraindo insights relevantes sobre os títulos mais populares da Netflix.

## 🗂️ Escopo da Análise
A análise será focada nos seguintes aspectos:
- **Tipos de dados disponíveis** 📌
- **Período da análise feita** 📆
- **Tamanho da base de dados** 🔍
- **Verificação de valores nulos** ⚠️
- **Identificação de outliers** 📈

## 📁 Fonte dos Dados
Os dados utilizados neste projeto foram fornecidos pela **Rocketseat** e podem ser acessados no seguinte link:
🔗 [Download do dataset](https://efficient-sloth-d85.notion.site/Desafio-EDA-c8c8b2faf153449193b4b9fb0895afa6)

## 🛠️ Tecnologias Utilizadas
- **Python** 🐍
- **Pandas** 🏷️
- **Matplotlib e Seaborn** 📊
- **Jupyter Notebook** 📝

## 📊 Principais Descobertas
### 📌 **1. Tipos de Dados**
A base de dados possui colunas numéricas, categóricas e temporais. Foi necessário converter a coluna `date` para o formato de data.

### 📆 **2. Período da Análise**
> **Data mínima:** 1º de abril de 2020  
> **Data máxima:** 11 de março de 2022  
> O dataset cobre um período de **15 anos**, abrangendo desde os primeiros rankings até os mais recentes.

### 📏 **3. Tamanho da Base de Dados**
> **7.100 linhas** e **10 colunas**.  
> Cada linha representa um título presente no Top 10 da Netflix, contendo informações como rank, tipo (filme ou série) e pontuação de audiência.

### ⚠️ **4. Verificação de Valores Nulos**
Nenhuma coluna apresentou valores nulos evidentes, mas a coluna **"Last Week Rank"** continha o valor **"-"**, que foi tratado e convertido para `NaN`.

### 📈 **5. Identificação de Outliers**
Os histogramas das colunas **"Days In Top 10"** e **"Viewership Score"** indicaram distribuições assimétricas com **caldas longas à direita**, sugerindo que poucos títulos se mantêm no ranking por longos períodos ou possuem altos níveis de audiência.

Os boxplots revelaram que a categoria **"TV Show"** apresenta **maior variabilidade** e mais **outliers** do que os filmes, possivelmente devido à maior duração das séries.

## 📌 Conclusão
A análise mostrou que os **TV Shows** possuem um desempenho mais irregular no ranking, enquanto os **Filmes** tendem a ter ciclos de popularidade mais curtos. Essa informação pode ser útil para estratégias de conteúdo na Netflix.

## 🚀 Como Executar o Projeto
1. Clone este repositório:
   ```sh
   git clone https://github.com/matheusvazdata/ia-desafio-aed
   ```
2. Instale as dependências:
   ```sh
   pip install -r requirements.txt
   ```
3. Execute o Jupyter Notebook:
   ```sh
   jupyter notebook
   ```

## 📌 Autor
Projeto desenvolvido por [Seu Nome](https://github.com/matheusvazdata). Conecte-se comigo no [LinkedIn](https://www.linkedin.com/in/matheusvazdata/)! 🚀

