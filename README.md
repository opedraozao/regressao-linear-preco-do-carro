# regressao-linear-preco-do-carro
Regressão Linear Mútipla utilizada para prever o preço dos automóveis em relação a diferentes atributos em um determinado dataset, sejam eles: potência dos seus respectivos motores, consumo médio na cidade, consumo médio na estrada e as cilindradas.

O modelo utiliza métodos estatítisticos e econométricos para identificar as variaveis dependentes: 'engine-size', 'horsepower', 'city-mpg', 'highway-mpg' e a variável independente: logPrice, que foi derivado da coluna 'price' do DataFrame original, transformação comum em modelos de regressão de preços, pois distribuições de preços tendem a ser assimétricas (skewed), e o logaritmo pode torná-las mais simétricas, o que ajuda o modelo linear a performar melhor.

Após o cálculo da média e do desvio padrão das linhas, é realizado a normalização dos dados da variável X (explicativa), razão entre as variáveis depentendes subtraído pela média e o desvio padrão.

O treinamento dos dados é feito com 75% dos dados do modelo limpo, e com 25% dos dados é realizado o teste do modelo.

Com os dados terinados, foi obtido um R² (coeficiente de determinação) de 0,454 para explicar a relação entre a variável dependente e as variáveis independentes.  

O gráfico abaixo representa com a linha vermelha a regressão obtida através dos dados expostos em azul no gráfico de dispersão a relação entre o preço dos automóveis e as variáveis de potência dos seus respectivos motores, consumo médio na cidade, consumo médio na estrada e as cilindradas:

![image](https://github.com/user-attachments/assets/a3d34439-c681-42e1-bb27-c574808038ee)
 
