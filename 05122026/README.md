# Aula 12/05/2026 — Perceptron (Implementação)

Implementação completa do algoritmo de aprendizado Perceptron do zero, testado nos três cenários de datasets da aula anterior.

## Conteúdo

### `perceptron.ipynb`
Implementação do Perceptron com:
- Inicialização de pesos e bias
- Função de ativação **Sign**: ŷ = sinal(wᵀx + b)
- **Regra de aprendizado do Perceptron**: Δw = η · (y - ŷ) · x
- Hiperparâmetros configuráveis: taxa de aprendizado (η) e número de épocas
- Rastreamento do erro ao longo das épocas
- Visualização da **fronteira de decisão** aprendida
- Avaliação nos três datasets com análise comparativa

### Datasets de Treino e Teste
Os mesmos três pares de datasets introduzidos em `05052026`:

| Arquivo | Descrição |
|---------|-----------|
| `train_dataset1.csv` / `test_dataset1.csv` | Cenário 1 |
| `train_dataset2.csv` / `test_dataset2.csv` | Cenário 2 |
| `train_dataset3.csv` / `test_dataset3.csv` | Cenário 3 |

## Relação com outras aulas
Esta aula é a **implementação prática** do conteúdo teórico apresentado em `05052026`. A aula `05262026` avança para redes multicamada (MLP).

## Objetivo
Implementar o Perceptron do zero e observar empiricamente sua capacidade de separar classes linearmente separáveis, preparando a base para redes neurais mais profundas.
