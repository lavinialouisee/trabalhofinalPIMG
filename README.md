# Trabalho Final - Processamento de Imagens
### Alunos: Lavínia Louise Rosa Santos e Luís Eduardo Cardoso de Santana

## Detecção e Classificação de Dados com Transformada de Hough Circular
Esse repositório contém uma implementação de classificação automática de dados em imagens usando técnicas vistas na matéria de Processamento de Imagens. A solução identifica as circunferências de todos os dados usando CHT e agrupa essas circunferências por proximidade possibilitando detectar cada dado e classificá-lo com base na quantidade de círculos da sua face, ou seja, de 1 a 6. Além disso, o repositório disponibiliza o dataset utilizado e o link para o vídeo de apresentação da solução.

#### A solução segue as seguintes etapas:

1. Leitura da imagem com conversão para escala de cinza
2. Extração de bordas com Sobel
3. Binarização das bordas
4. Detecção das circunferências com a Transformada de Hough Circular
5. Limiarização do acumulador
6. Filtragem dos centros por distância
7. Agrupamento dos centros por distância
8. Classificação pelo número de circunferências em cada dado
9. Exibição dos dados detectados e classificados

#### Intruções de uso no Google Colab:

1. Baixe o dataset que está nesse repositório
2. Baixe o arquivo ipynb do código
3. Abra esse arquivo no Google Colab
4. No colab, crie uma pasta chamada "dataset" e coloque todas as imagens do dataset dentro dela
5. Execute todas as células do notebook mudando o índice da função de carregar imagem para testar diferentes imagens do dataset
