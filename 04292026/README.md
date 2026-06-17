# Aula 29/04/2026 — Árvores de Decisão

Implementação de Árvores de Decisão do zero, com base nos conceitos de entropia e ganho de informação.

## Conteúdo

### `arvore_decisao.ipynb`
Implementação completa da Árvore de Decisão:
- Cálculo de **Entropia** para medir impureza dos nós
- Cálculo do **Ganho de Informação** para escolha do melhor atributo de divisão
- Algoritmo recursivo de crescimento da árvore
- Critérios de parada (profundidade máxima, mínimo de amostras)
- Visualização das fronteiras de decisão
- Aplicação: classificação por faixa de idade e salário (acurácia de 100% no treino)

### `dataset.csv`
Dataset com atributos categóricos/numéricos utilizado na construção e avaliação da árvore.

### `11. Árvores de Decisão.pdf`
Material teórico de apoio: conceitos de entropia, ganho de informação, poda e comparação com outros algoritmos.

## Objetivo
Compreender como as Árvores de Decisão particionam o espaço de features de forma interpretável, e implementar o algoritmo ID3 do zero.
