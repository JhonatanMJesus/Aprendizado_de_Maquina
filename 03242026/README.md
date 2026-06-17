# Aula 24/03/2026 — Regressão Linear Múltipla (v1)

Extensão da regressão linear para múltiplas variáveis preditoras, implementada via equação normal com operações matriciais.

## Conteúdo

### `regressao_multipla.ipynb`
Implementação da Regressão Linear Múltipla do zero:
- Equação normal: **β = (XᵀX)⁻¹Xᵀy**
- Variáveis preditoras utilizadas: quartos, banheiros, área do lote, andares, condição, ano de construção e ano de renovação
- Predição do preço de imóveis do dataset King County
- Operações matriciais com NumPy

### `kc_house_data.csv`
Dataset King County com dados reais de venda de imóveis (Seattle).

## Relação com outras aulas
Esta é a **primeira versão** da implementação de regressão múltipla. A aula `03252026` traz uma versão refinada do mesmo conteúdo.

## Objetivo
Generalizar o modelo de regressão linear para múltiplas features, entendendo a solução analítica via álgebra linear.
