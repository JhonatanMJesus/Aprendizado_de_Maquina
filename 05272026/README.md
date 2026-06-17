# Aula 27/05/2026 — K-Means Clustering

Implementação do algoritmo K-Means do zero para aprendizado não supervisionado, aplicado à segmentação de clientes.

## Conteúdo

### `Meu_Kmeans.ipynb`
Implementação completa do K-Means:
- **Inicialização** aleatória dos centroides
- **Passo de atribuição**: cada ponto é associado ao centroide mais próximo pela distância Euclidiana
- **Passo de atualização**: centroides recalculados como média dos pontos do cluster
- Repetição até **convergência** (centroides estabilizam)
- Visualização dos clusters e centroides em cada iteração
- Aplicação: segmentação de clientes por perfil de comportamento

### `dataset_clientes_kmeans.csv`
Dataset com atributos de clientes (ex: renda, frequência de compra, ticket médio) para segmentação em grupos.

### `15. K-means.pdf`
Material teórico de apoio: algoritmo K-Means, escolha do número de clusters (método do cotovelo), limitações e variantes.

## Diferença em relação aos algoritmos anteriores
Todos os algoritmos anteriores eram **supervisionados** (precisavam de rótulos). O K-Means é **não supervisionado**: encontra padrões e agrupa dados sem conhecer os rótulos reais.

## Objetivo
Compreender o paradigma de aprendizado não supervisionado e implementar o K-Means para descobrir estruturas ocultas em dados sem rótulos.
