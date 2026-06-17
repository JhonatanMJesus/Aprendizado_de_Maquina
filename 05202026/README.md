# Aula 20/05/2026 — Perceptron (Implementação Orientada a Objetos)

Refatoração e aprofundamento da implementação do Perceptron utilizando uma classe dedicada com estratégias de inicialização de pesos configuráveis, aplicada nos três cenários de datasets.

## Conteúdo

### `perceptron.ipynb`
Implementação do Perceptron com design orientado a objetos:

**Classe `Perceptron`:**
- Parâmetros configuráveis: `learning_rate`, `n_epochs`, `weight_init`
- Suporte a diferentes estratégias de inicialização de pesos (ex: `"random"`)
- Rastreamento do erro por época (`errors_per_epochs`)

**Pipeline completo por dataset:**
- Carregamento via CSV com função dedicada (`carregar_dados`)
- Conversão de rótulos para `-1` e `1`
- Treinamento e avaliação separados para treino e teste
- Visualização lado a lado: distribuição dos dados vs fronteira de decisão (`plot_comparison`)

**Avaliação nos 3 cenários:**

| Dataset | Arquivo treino | Arquivo teste |
|---------|---------------|--------------|
| Cenário 1 | `train_dataset1.csv` | `test_dataset1.csv` |
| Cenário 2 | `train_dataset2.csv` | `test_dataset2.csv` |
| Cenário 3 | `train_dataset3.csv` | `test_dataset3.csv` |

## Diferença em relação a `05122026`
Enquanto `05122026` foca na lógica do algoritmo, esta aula estrutura o código em uma **classe reutilizável** com inicialização configurável e visualizações comparativas mais elaboradas.

## Relação com outras aulas
- Continuação de `05122026` (implementação inicial do Perceptron)
- Preparação para `05262026` (MLP — Multi-Layer Perceptron)

## Objetivo
Consolidar o Perceptron com código mais estruturado e reutilizável, aprofundando a análise comparativa entre treino e teste nos três cenários.
