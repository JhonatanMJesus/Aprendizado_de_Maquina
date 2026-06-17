# Aprendizado de Máquina — FATEC 5º Semestre

Repositório de aulas práticas da disciplina de Aprendizado de Máquina. As pastas seguem o padrão `DDMMAAAA` (data da aula) e progridem do básico de Python até técnicas avançadas de redes neurais e aprendizado não supervisionado.

---

## Fundamentos

### `03042026` — Programação Orientada a Objetos e Python
Revisão de fundamentos de Python com foco em POO.
- Definição e instanciação de classes
- Herança, polimorfismo e encapsulamento
- Aplicação prática: gerenciamento de sensores IoT e autenticação de usuários
- Classes abstratas e métodos polimórficos

**Arquivos:** `Fundamentos.ipynb`, `OOP.ipynb`, `Tarefa0403.ipynb`

---

### `03112026` — Manipulação de Dados com Pandas
Introdução à biblioteca Pandas para análise e manipulação de dados.
- Series e DataFrames: criação e manipulação
- Leitura de arquivos CSV
- Carregamento de datasets externos (Titanic)

**Arquivos:** `pandas.ipynb`

---

## Regressão

### `03162026` — Regressão Linear Simples
Implementação de regressão linear simples do zero com NumPy.
- Cálculo manual dos coeficientes de regressão (a, b)
- Predição de preços de imóveis (dataset King County)
- Visualização de tendências e equação da reta

**Arquivos:** `regressao.ipynb`, `regressao_kc.ipynb`, `Exemplo Regressão Linear.xlsx - Planilha1.csv`, `kc_house_data.csv`, `Regressão Linear.pdf`

---

### Regressão Linear Múltipla
Extensão da regressão linear para múltiplas variáveis preditoras usando o dataset de imóveis King County.
- Equação normal: β = (XᵀX)⁻¹Xᵀy
- Variáveis: quartos, banheiros, área do lote, andares, condição, ano de construção e reforma
- Operações matriciais e álgebra linear aplicadas a ML

**Arquivos em ambas:** `regressao_multipla.ipynb`, `kc_house_data.csv`

> #### `03242026` — Versão inicial
> Primeira implementação da regressão múltipla.
>
> #### `03252026` — Versão refinada
> Continuação da aula anterior com implementação aprimorada e mais features.

---

## Classificação

### Regressão Logística
Regressão logística para classificação binária usando o dataset do Titanic.
- Função de ativação Sigmoid
- Gradiente descendente e função de custo (Cross-Entropy)
- Engenharia de features: idade, tarifa, sexo, classe do passageiro
- Treinamento e avaliação de acurácia

**Arquivos em ambas:** `regressao_logistica.ipynb`, `titanic.csv`

> #### `03312026` — Introdução
> Implementação inicial da regressão logística.
>
> #### `04082026` — Prática expandida
> Continuação com prática estendida no mesmo problema de classificação.

---

### K-Nearest Neighbors (KNN)
Algoritmo KNN implementado do zero para classificação.

> #### `04132026` — Teoria e Implementação
> Implementação do KNN para classificação de tumores (benigno vs. maligno).
> - Cálculo de distância Euclidiana
> - Classificação por votação majoritária
> - Aplicação em diagnóstico médico
>
> **Arquivos:** `analise_knn_tumores.ipynb`, `tumores.csv`, `9. KNN.pdf`

> #### `04142026` — Exercícios de Revisão
> Fixação do algoritmo KNN com três exercícios práticos.
> - Segmentação de consumo de clientes (baixo, médio, alto)
> - Classificação de desempenho de funcionários
> - Análise de fronteiras de decisão e impacto do parâmetro k
>
> **Arquivos:** `respostas.ipynb`, `knn_dataset_exercicio_1.txt`, `knn_dataset_exercicio_2.txt`, `knn_dataset_exercicio_3.txt`, `10. KNN - Exercícios de Revisão e Fixação.pdf`

---

### `04292026` — Árvores de Decisão
Implementação de árvores de decisão do zero.
- Cálculo de entropia e ganho de informação
- Algoritmo recursivo de crescimento da árvore
- Critérios de divisão e separação de nós
- Visualização de fronteiras de decisão
- Aplicação: classificação por idade e salário

**Arquivos:** `arvore_decisao.ipynb`, `dataset.csv`, `11. Árvores de Decisão.pdf`

---

## Redes Neurais

### Perceptron
Algoritmo Perceptron para classificação linear binária.

> #### `05052026` — Teoria
> Material teórico e datasets para estudo do Perceptron.
> - Fundamentos do Perceptron e problemas linearmente separáveis
> - Estratégias de inicialização de pesos
>
> **Arquivos:** `15. Perceptron.pdf`, `train_dataset1-3.csv`, `test_dataset1-3.csv`

> #### `05122026` — Implementação
> Implementação completa do algoritmo de aprendizado Perceptron.
> - Modelo do zero com taxa de aprendizado e épocas configuráveis
> - Gradiente descendente com regra do Perceptron
> - Função de ativação Sign e visualização da fronteira de decisão
> - Rastreamento de erro ao longo das épocas nos 3 datasets
>
> **Arquivos:** `perceptron.ipynb`, `train_dataset1-3.csv`, `test_dataset1-3.csv`

> #### `05202026` — Implementação OO
> Refatoração do Perceptron em classe reutilizável com inicialização de pesos configurável.
> - Classe `Perceptron` com `learning_rate`, `n_epochs` e `weight_init` configuráveis
> - Visualização lado a lado: distribuição dos dados vs fronteira de decisão
> - Avaliação explícita em treino e teste para os 3 cenários
>
> **Arquivos:** `perceptron.ipynb`, `train_dataset1-3.csv`, `test_dataset1-3.csv`

---

### `05262026` — Multi-Layer Perceptron (MLP)
Rede neural multicamada com frameworks modernos.
- Arquitetura com múltiplas camadas ocultas `[50, 128, 64, 4]`
- Funções de ativação: ReLU e Tanh
- Otimizadores: Adam e SGD
- Regularização: Dropout e L2
- Treinamento em mini-batches e Early Stopping
- Monitoramento de loss/acurácia em treino e validação

**Arquivos:** `mlp.ipynb`, `train_dataset0-3.csv`, `test_dataset0-3.csv`, `validation_dataset.csv`

---

## Aprendizado Não Supervisionado

### `05272026` — K-Means Clustering
Algoritmo K-Means implementado do zero para segmentação não supervisionada.
- Inicialização de centroides
- Cálculo de distância Euclidiana e atribuição de clusters
- Atualização iterativa de centroides até convergência
- Aplicação: segmentação de clientes
- Visualização de clusters e centroides

**Arquivos:** `Meu_Kmeans.ipynb`, `dataset_clientes_kmeans.csv`, `15. K-means.pdf`

---

## Visão Geral

| Pasta | Data | Tema | Categoria |
|-------|------|------|-----------|
| `03042026` | 04/03 | POO e Python | Fundamentos |
| `03112026` | 11/03 | Pandas | Fundamentos |
| `03162026` | 16/03 | Regressão Linear Simples | Regressão |
| `03242026` | 24/03 | Regressão Múltipla (v1) | Regressão |
| `03252026` | 25/03 | Regressão Múltipla (v2) | Regressão |
| `03312026` | 31/03 | Regressão Logística (intro) | Classificação |
| `04082026` | 08/04 | Regressão Logística (prática) | Classificação |
| `04132026` | 13/04 | KNN — Implementação | Classificação |
| `04142026` | 14/04 | KNN — Exercícios | Classificação |
| `04292026` | 29/04 | Árvores de Decisão | Classificação |
| `05052026` | 05/05 | Perceptron — Teoria | Redes Neurais |
| `05122026` | 12/05 | Perceptron — Implementação | Redes Neurais |
| `05202026` | 20/05 | Perceptron — Implementação OO | Redes Neurais |
| `05262026` | 26/05 | MLP | Redes Neurais |
| `05272026` | 27/05 | K-Means | Não Supervisionado |
