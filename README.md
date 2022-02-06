![261439306_612866583465099_6202014850573516966_n](https://user-images.githubusercontent.com/88898006/152449698-d89942b0-36ee-4faf-bf8c-efd7a29e9d14.jpg)

# ColoRAS
O ***ColoRAS*** é um projeto que tem o intuito de utilizar visão computacional associada ao machine learning para identificar cores e roupas em imagens disponibilizadas pelo usuário e retornar para o mesmo um “score” baseado em sua combinação destas, tendo em vista a grande propagação da moda e do DIY fashion (do it yourself fashion), é uma alternativa para auxiliar no processo criativo do usuário.

### Utilização:
> O programa analisa as duas cores predominantes na imagem e, com base em uma pesquisa feita com os alunos da UNESP,  fornece uma nota para essa combinação. Utilizando uma base de dados, uma rede neural analisa os valores de cores identificados na foto e devolve, com base na nota e combinação de cores referentes a base de dados, uma nota para o usuário..

### Aplicação:
> É destinado para o uso livre para o lazer e benefício do usuário.

### Ferramentas utilizadas para o software:
- OpenCV;
- Numpy;
- ColorSys;
- Pandas;
- TensorFlow

### Dataset da rede neural de segmentação disponíveil em:
> https://drive.google.com/drive/folders/1QoVK6ILudBUJpok84zLvM5DVYNNQj6eo

## Instalação dos Pré-requisitos:

1 - Criar o environment do Conda com o python 3.9 ou utilizar o google colab:
`conda create -n myenv python=3.9`

2 - Clonar o repositório:
`git clone https://github.com/RAS-Unesp-Bauru/ColoRAS`

3 - Instalar a biblioteca OpenCV:
`pip install opencv-python`

4 - Instalar a biblioteca Numpy.:
`pip install numpy`

5 - Instalar a biblioteca Tensorflow:
`pip install --upgrade tensorflow`

6 - Instalar a biblioteca Pandas:
`pip install pandas`

7 - Instalar a biblioteca ColorSys:
`pip install pycopy-colorsys`







 
