# Classificação de Imagens com Redes Neurais Convolucionais (CNNs)

## Objetivo do Projeto

O objetivo deste projeto é classificar imagens do dataset **CUHK Face Sketch Database (CUFS)** com base no sexo biológico (masculino ou feminino) utilizando redes neurais convolucionais (CNNs). O problema abordado envolve o desbalanceamento de classes e o tamanho limitado do dataset, que apresenta 134 imagens masculinas e 54 femininas. O projeto aplica técnicas de aprendizado de máquina, como **oversampling com SMOTE**, **Data Augmentation** e **regularização com Dropout**, para treinar um modelo de CNN que possa classificar as imagens de maneira eficaz. Os resultados esperados incluem uma boa acurácia na classificação e a capacidade do modelo de distinguir adequadamente entre as classes masculinas e femininas.

## Instruções para Execução do Código

### Requisitos de Software

- **Python 3.x** (recomendado Python 3.6 ou superior)
- **TensorFlow** (para a implementação da rede neural)
- **Keras** (para facilitar a criação do modelo)
- **OpenCV** (para processamento de imagem)
- **scikit-learn** (para métricas de avaliação)

### Dependências

As dependências necessárias podem ser instaladas usando o arquivo `requirements.txt` ou manualmente. Para isso, execute:

#### Instalação via `requirements.txt`:

Clone este repositório:
   bash
   [git clone https://github.com/usuario/nome-do-repositorio.git](https://github.com/luanaoliveira/HAR-smartphones)


## Principais Conclusões e Considerações
Os resultados obtidos indicaram que o modelo teve desempenho limitado devido ao desbalanceamento de classes entre as imagens masculinas e femininas. A acurácia final foi de 50%, o que é similar a uma classificação aleatória, e o F1-score foi de 0,5221. A matriz de confusão revelou que o modelo obteve maior precisão na classe masculina (71%) e maior recall na classe feminina (69%).

Além disso, a curva ROC obteve uma AUC de 0,57, indicando que o modelo tem uma capacidade limitada de discriminar entre as duas classes. O desbalanceamento no dataset foi um fator crucial para o baixo desempenho.

## Limitações e Pontos de Melhoria
Desbalanceamento do Dataset: O dataset contém significativamente mais imagens masculinas do que femininas, o que pode ser mitigado por meio de pesos ajustados para as classes ou aumentando o número de imagens femininas.
Arquitetura do Modelo: A arquitetura atual da CNN pode ser otimizada para melhorar o desempenho. Experimentar com diferentes camadas e hiperparâmetros pode trazer melhorias.
Aumento do Dataset: Ampliar o número de imagens disponíveis e diversificar o conjunto de dados pode ajudar o modelo a aprender características mais robustas.
Próximos Passos
Melhorar a qualidade e o balanceamento do dataset.
Experimentar com ajustes de hiperparâmetros e novas arquiteturas de rede.
Realizar mais experimentos com técnicas avançadas de balanceamento de classes.


## Autores e Colaboradores

- [Elai Emylle Matos de Lima](https://www.linkedin.com/in/elaimatos/)
- [Luana Oliveira da Silva](https://github.com/luanaoliveira)
