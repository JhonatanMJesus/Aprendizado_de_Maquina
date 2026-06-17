# Aula 31/03/2026 — Regressão Logística (Introdução)

Introdução à Regressão Logística para classificação binária, implementada do zero e aplicada ao problema de sobrevivência no Titanic.

## Conteúdo

### `regressao_logistica.ipynb`
Implementação da Regressão Logística:
- Função de ativação **Sigmoid**: σ(z) = 1 / (1 + e⁻ᶻ)
- Função de custo: **Cross-Entropy (Log Loss)**
- Otimização via **Gradiente Descendente**
- Engenharia de features: idade, tarifa, sexo, classe do passageiro
- Treinamento e avaliação de acurácia do modelo

### `titanic.csv`
Dataset do Titanic com informações dos passageiros (idade, sexo, classe, tarifa, sobrevivência).

## Relação com outras aulas
Esta é a **implementação inicial** da Regressão Logística. A aula `04082026` traz uma prática expandida do mesmo conteúdo.

## Objetivo
Compreender a transição da regressão para a classificação, aprendendo a modelar probabilidades e tomar decisões binárias com um limiar.
