
# GS - 4SIS
Classificação de Imagens de Pulmão Saudável e com Câncer

Descrição do Projeto:

Este projeto visa desenvolver uma Rede Neural Convolucional (CNN) para a classificação de imagens relacionadas à saúde pulmonar. O objetivo é utilizar técnicas de aprendizado profundo para a prevenção e diagnóstico precoce de doenças pulmonares, contribuindo para a qualidade de vida e bem-estar da população.


Requisitos:
Python 3
Bibliotecas: NumPy, TensorFlow, Matplotlib, PIL, scikit-learn

Instalação de Dependências:
pip install numpy tensorflow matplotlib pillow scikit-learn

Passo-a-passo:
1. Abra o arquivo de preferencia no Google Colab.
2. Importe as imagens.
3. Execute o codigo.

Descrição Técnica:
O código utiliza uma CNN com duas camadas de convolução e camadas de MaxPooling para extrair características das imagens. A rede é treinada utilizando um conjunto de imagens de pulmão classificadas como saudáveis ou com câncer. O modelo é compilado com a função de perda categorical_crossentropy e otimizador adam.

Avaliação do Modelo:
Ao final do treinamento, o modelo é avaliado usando um conjunto de teste separado. A acurácia do modelo é exibida como métrica de desempenho.

Grupo:
Caio Rodrigues Bosnic Barbosa RM84862
Lucas Nobrega Mansano RM85388
Nicolas Costa Oliveira RM84991