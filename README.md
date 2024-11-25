# Sistema de Recomendação Amazon - README

## Descrição do Projeto

Este repositório contém o desenvolvimento de um sistema de recomendação baseado em análises de produtos da Amazon, focado na categoria de eletrônicos. O projeto foi criado para atender ao objetivo de recomendar produtos aos usuários com base nas avaliações fornecidas por outros clientes. O sistema utiliza abordagens de aprendizado de máquina para gerar recomendações:

1. **KNN (K-Nearest Neighbors)**: Uma abordagem baseada em similaridade para recomendações.
2. **K-Means**: Uma técnica de clusterização para agrupar usuários ou produtos e gerar recomendações baseadas nesses grupos.

O projeto é desenvolvido como parte de um estudo de caso da disciplina de Ciência de Dados no Centro Universitário de Brasília (CEUB).

---

## Estrutura do Repositório

- **`Notebook_Modelo_Amazon.ipynb`**: Implementação completa do sistema de recomendação utilizando os algoritmos KNN e K-Means.
- **`Trabalho 2.pdf`**: Documento original com o enunciado do estudo de caso e instruções detalhadas.

---

## Conjunto de Dados

O dataset utilizado é o [Amazon Electronics Rating Dataset](https://www.kaggle.com/datasets/vibivij/amazon-electronics-rating-datasetrecommendation/data). Ele contém os seguintes atributos:

- **userId**: Identificador único para cada usuário.
- **productId**: Identificador único para cada produto.
- **rating**: Avaliação do produto dada pelo usuário.
- **timestamp**: Data e hora da avaliação (não utilizado neste projeto).

---

## Objetivos

1. Construir um sistema de recomendação utilizando o algoritmo **KNN**.
2. Construir o mesmo sistema de recomendação utilizando o algoritmo **K-Means**.
3. Comparar os dois métodos, destacando:
   - Diferenças entre as abordagens.
   - Qual método apresenta melhores resultados e por quê.

---

## Ferramentas Utilizadas

- **Python**: Linguagem de programação principal.
- **Bibliotecas**:
  - Pandas: Manipulação de dados.
  - NumPy: Operações matemáticas.
  - Scikit-learn: Implementação dos algoritmos KNN e K-Means.
  - Matplotlib e Seaborn: Visualização de dados.

---

## Implementação

### Parte 1: Sistema de Recomendação com KNN

O algoritmo KNN baseia-se na similaridade entre usuários ou produtos para realizar as recomendações. Os principais passos foram:

1. Carregamento e limpeza dos dados.
2. Cálculo das similaridades utilizando métricas como distância Euclidiana ou cosseno.
3. Recomendação de produtos para usuários com base nos vizinhos mais próximos.

### Parte 2: Sistema de Recomendação com K-Means

O algoritmo K-Means utiliza clusterização para agrupar usuários ou produtos com características semelhantes. Os passos incluem:

1. Carregamento e limpeza dos dados.
2. Agrupamento utilizando o K-Means.
3. Recomendação com base nos grupos gerados.

---

## Resultados e Conclusão

1. **Diferenças entre KNN e K-Means**:
   - KNN é baseado em instâncias e utiliza similaridades diretas entre usuários ou produtos.
   - K-Means agrupa os dados e realiza recomendações com base nos clusters, sendo mais eficiente para grandes volumes de dados.

2. **Melhores Resultados**:
   - O método que apresentou os melhores resultados será detalhado no notebook, com justificativas baseadas em métricas como precisão e recall.

---
