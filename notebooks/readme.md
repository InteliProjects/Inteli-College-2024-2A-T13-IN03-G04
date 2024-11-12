# Notebooks

Esta pasta contém os notebooks desenvolvidos ao longo das sprints do projeto. Cada arquivo documenta o progresso das etapas de análise e modelagem. Os notebooks foram exportados diretamente do Google Colab. Abaixo estão descrições dos arquivos presentes:

- **sprint2_initial_analysis.ipynb**: Contém a análise exploratória de dados (EDA), incluindo limpeza, pré-processamento e geração de hipóteses. Este foi o primeiro notebook gerado após o entendimento de negócio realizado na primeira sprint.

- **sprint3_base_clustering.ipynb**: Focado na clusterização dos dados. Foram explorados métodos como K-Means, com identificação do número ideal de *clusters* (k), seleção de *features* e análise dos resultados obtidos.

- **sprint4_tunning_models.ipynb**: Neste notebook, diferentes algoritmos de clusterização (DBSCAN, K-Means, Gaussian Mixture, Spectral Clustering e Affinity Propagation) são comparados. O processo inclui a otimização de hiperparâmetros e análise das métricas para avaliar o desempenho de cada modelo.

- **tuss.csv**: Essa é a tabela de Terminologia Unificada da Saúde Suplementar (TUSS) com limpezas feitas pelo grupo SGESP. Esse arquivo vai auxiliar os notebooks nas análises.

- **requirements.txt**: Arquivo com todas as importações necessárias para rodar os notebooks.

- **streamlit**: Aplicação visual do UNIDATA, utilizando a biblioteca streamlit, com essa aplicação é póssivel fazer análises automatizadas dos *clusters*, apenas importando a base que se deseja analisar e filtrar de acordo com as *features* escolhidas.