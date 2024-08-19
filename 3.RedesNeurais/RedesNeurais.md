## Redes Neurais 

Quando trabalhamos com visão computacional não podemos deixar de fora as redes neurais, e em especifico as redes neurais convulocionais(CNN), elas foram projetadas para
especificamente pra lidarem com dados visuais. 

## Como Funcionam as CNNs: 
Elas utilizam uma arquitetura de camada, onde cada camada é responsável por aprender diferentes aspectos da imagem
1- Camada Convulocionais: Responsável por aplicar filtros (ou kernels) à imagem de entrada para detectar padrões  básicos, como linhas, bordas, cores. Quanto mais aprofundada
a rede, mais complexo é a identificação 
2- Camada de Pooling: Reduzem a dimensionalidade das respresentações internas, mantendo as características mais importantes. 
3- Camada Fully Connected: Essa camada conecta a caracterista extraidas a classes específicas. Funciona como uma forma de classificar as informacoes visuais e processdas pelas
camadas anteriores. 

## Ferramenta 
Para criarmos as CNNs, iremos utilizar do tensorflow e o do keras, eles possuem várias facilidades que encurtam o processo e torna mais simples criar sua própria rede neural 
para conseguir treinar sua rede neural basta instalar o tensorflow, é recomendado usar uma versão 2.0 a cima, segue a documentacao do tensorflow https://www.tensorflow.org/?hl=pt-br

## Instalacao 
```bash
pip install tensorflow

## Uso
Irei criar um .ipynb mosrando um exemplo simples de como criar uma CNN
