# Machine Learning II: Clusterização de Clientes

## Projeto Final da disciplina de Machine Learning II

--------------------------------------------------------------------------
<h1> <img height="40" width="40" src= "https://github.com/GabriellyAnisio/ML_Customer_Clustering/assets/89808695/e9318220-fe37-4c4d-b7bc-480f38361cd8" /> Descrição do Projeto </h1>

O projeto propõe o uso de técnicas de clusterização para análise de um dataset e aplicação dos conceitos apresentados sobre abordagem não supervisionada ao longo da disciplina de Machine Learning II. 

A disciplina faz parte do programa Santander Coders 2023 que foi ministrada pela Ada Tech e o presente módulo pelo professor Maurício Sobrinho.

Para realização do projeto, a base escolhida é relativa a segmentação de clientes, que pode ser encontrada no kaggle: https://www.kaggle.com/datasets/dev0914sharma/customer-clustering?select=segmentation+data.csv

------------------------------------------------------------------------------
<h1> <img height="40" width="40" src= "https://github.com/GabriellyAnisio/ML_Customer_Clustering/assets/89808695/bdfe7ffc-b013-4b1c-b00e-93ae247fc0a2" /> Arquivos do Projeto </h1>

O projeto é composto pelos seguintes arquivos:
- data: é uma pasta que contém os arquivos em formato "csv" utilizados e gerados para realização das análise.
  - segmentation data.csv: dataset obtido no kaggle. É a base para as análises de clusterização.
  - segmentation data legend.xlsx: arquivo obtido também no kaggle que apresenta informações relativas às legendas dos dados.
  - segmentation_data_clustering.csv: dataset gerado a partir da clusterização e utilizado como base para a análise dos clusters no notebook eda_clusters.ipynb.
  - segmentation_data_clustering_pca.csv: dataset gerado a partir da clusterização que utiliza a técnica de PCA.
- eda.ipynb: notebook que apresenta uma inspeção inicial e análise exploratória do dataset "segmentation data.csv". Também informa a descrição do projeto e os requisitos solicitados para a resolução deste desafio.
- Validacao.ipynb: notebook que apresenta análise sobre a da validação de técnicas de clusterização. Implementa as técnicas: Agrupamento Hierárquico, K-means e Índice de Silhueta.
- clustering.ipynb: notebook que apresenta implementações de técnicas de clusterização. Aborda o Agrupamento Hierárquico (single-link, complete-link, average-link), PCA, Matriz de dissimilaridades e K-means. É o notebook que dá origem as bases "segmentation_data_clustering.csv" e "segmentation_data_clustering_pca.csv".
- eda_clusters.ipynb: notebook realizado após as etapas de validação e clusterização. Apresenta informações relativas aos clusters gerados e análise sobre as características dos clusters diante dos atributos utilizados, visando analisar o perfil de cada cluster.

---------------------------------------------------------------------------

<h1> <img height="40" width="40" src= "https://github.com/GabriellyAnisio/ML_Customer_Clustering/assets/89808695/fc4d9a1f-b635-48d5-a92b-85f122850016" /> Stacks e bibliotecas utilizadas </h1>

Para execução do projeto foi utilizada a linguagem Python nos ambientes Google Colab e VSCode.
As bibliotecas utilizadas foram:
- Pandas
- Matplotlib
- Seaborn
- Sklearn
- Warnings
- NumPy
- Scipy
- Sklearn

----------------------------------------------------------------------------
<h1> <img height="40" width="40" src= "https://github.com/GabriellyAnisio/ML_Customer_Clustering/assets/89808695/048765de-d55b-4738-a7c9-f5d6c270a3ec" /> Equipe do Projeto </h1>

O grupo 03 é composto pelos seguintes integrantes:

|  **Jorge Dantas**  |  **Karen Almeida** | **Maria Gabrielly** | **Nathália Martins**  | **Ricardo Steigleder** |
| ---------------------- | ------------------- | ------------------- | ------------------- | ------------------- |
| <a href="https://www.linkedin.com/in/jorge-dantas-0952bb239/" target="_blank"><img loading="lazy" src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> |  <a href="https://www.linkedin.com/in/karen-almeida-neves/" target="_blank"><img loading="lazy" src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> | <a href="https://www.linkedin.com/in/maria-gabrielly-a-santana-707264204/" target="_blank"><img loading="lazy" src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> | <a href="https://www.linkedin.com/in/nathaliamartinss/" target="_blank"><img loading="lazy" src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> |  <a href="https://www.linkedin.com/in/ricardoendres/" target="_blank"><img loading="lazy" src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> |




