# Aula 26/05/2026 — Multi-Layer Perceptron (MLP)

Implementação de uma rede neural multicamada (MLP) capaz de resolver problemas não linearmente separáveis, com técnicas modernas de regularização e otimização.

## Conteúdo

### `mlp.ipynb`
Implementação de uma MLP completa:

**Arquitetura:**
- Camadas ocultas: `[50, 128, 64, 4]`
- Funções de ativação: **ReLU** e **Tanh**

**Treinamento:**
- Otimizadores: **Adam** e **SGD**
- Mini-batch gradient descent
- Monitoramento de loss e acurácia em treino e validação

**Regularização:**
- **Dropout** para prevenção de overfitting
- **L2 regularization** (weight decay)
- **Early Stopping** com critério de paciência

**Avaliação:**
- Visualização da fronteira de decisão para classificação multiclasse
- Curvas de aprendizado (loss e acurácia por época)

### Datasets

| Arquivo | Uso |
|---------|-----|
| `train_dataset.csv` + `train_dataset1-3.csv` | Treinamento |
| `test_dataset.csv` + `test_dataset1-3.csv` | Avaliação |
| `validation_dataset.csv` | Validação durante o treinamento |

## Relação com outras aulas
Esta aula é a evolução direta do Perceptron simples (`05052026`, `05122026`), adicionando múltiplas camadas e backpropagation completo.

## Objetivo
Compreender como redes multicamada superam as limitações do Perceptron simples, e aplicar técnicas de regularização para garantir boa generalização.
