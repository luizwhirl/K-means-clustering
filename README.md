# K-means com PCA e Visualização

Projeto de demonstração simples de como se gerar dados sintéticos com o **K-means** e poder se visualizar os resultados num arquivo png após uma **redução de dimensionalidade com PCA**.

## Requisitos

Antes de executar o código, é necessário instalar as seguintes bibliotecas Python:

```bash
pip install numpy matplotlib scikit-learn
```
Mas é só isso mesmo.

## Descrição do Código

### Geração de Dados Sintéticos
- Utiliza `make_blobs` do `sklearn.datasets` para criar um conjunto de dados com **3 clusters distintos**.

### Redução de Dimensionalidade (PCA)
- Aplica **Análise de Componentes Principais (PCA)** para reduzir os dados a **2 dimensões**, facilitando a visualização.

### Clustering com K-means
- Utiliza o algoritmo **K-means** do `scikit-learn` para identificar automaticamente os clusters nos dados.

### Visualização
- Os clusters são visualizados com a biblioteca **matplotlib**.
- **Centróides** são destacados em **vermelho**.
- A imagem gerada é salva como `clusterss.png` no diretório atual.
- Grupos de clusters diferentes possuem cores também diferentes
