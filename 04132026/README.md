# Aula 13/04/2026 — K-Nearest Neighbors (KNN)

Implementação do algoritmo K-Nearest Neighbors do zero, aplicado ao problema de classificação de tumores em benigno ou maligno.

## Conteúdo

### `analise_knn_tumores.ipynb`
Implementação completa do KNN:
- Cálculo da **distância Euclidiana** entre amostras
- Identificação dos **k vizinhos mais próximos**
- Classificação por **votação majoritária**
- Avaliação do impacto do parâmetro k na acurácia
- Aplicação em diagnóstico médico: classificação de tumores

### `tumores.csv`
Dataset com características de tumores (tamanho, forma, textura, etc.) e rótulo benigno/maligno.

### `9. KNN.pdf`
Material teórico de apoio sobre o algoritmo KNN: conceitos, distâncias, escolha de k e casos de uso.

## Relação com outras aulas
Esta aula cobre a **teoria e implementação** do KNN. A aula `04142026` traz exercícios de revisão e fixação do mesmo algoritmo.

## Objetivo
Entender o funcionamento do KNN como algoritmo baseado em instâncias (lazy learning) e aplicá-lo em um problema real de classificação médica.
