<p align="center">
  <img src="https://storage.googleapis.com/kaggle-competitions/kaggle/6322/logos/header.png?GoogleAccessId=web-data@kaggle-161607.iam.gserviceaccount.com&Expires=1721164741&Signature=dVVxDn2u6L0sSmVi3yqvHLpbi1gdk%2BqJKPmbs9RXBuhyFPFjUCfL12e9Ky4q%2BniQ4SoP4wU5g9IZZigpKH9%2FabFtWQSaasRhDyGa%2B9MC9Vf6oC4rKjpImJodHmGwT9Sn5Dsgb9FLbl47Uzf1oqK1RST5CvLodTzuOfYvBVS6bVVRvc3cmj6AQO%2BmWGigDhCN6VfQZHM%2Fpt0C1xl2X2AmEGoRuYddahHN1RiChdFZ%2F6y7TkM%2B0J2yN8pm1Jb5A28Of9oqNSbTqh6BF6nNG2kWEPrMpjLY48owwp2nhAXc86w6UIPN5vQ2AIlKAOw3qUVqx4gxV1Rikqww2G6N7vOv9w%3D%3D" width="500">
</p> 

<h1 align="center">Rastreamento do Desmatamento a Partir de Imagens Satélites</h1>

<h3 align="center">:computer: Projeto Final de Aprendizagem de Máquina do Quinto Semestre - PUC-SP :computer: </h3>
<h4 align="center">Junho/2024</h4>
<p align='center'> :school: Faculdade :school: </p>
 
  </br>
  
### :dancers: Grupo
- Manoela Finotti
- [Melissa Assis da Silva](https://github.com/melassiss)

### :teacher: Instruções para o Trabalho (passadas pelo professor)
Projeto 2:  
Usando dados de satélite para rastrear a pegada humana na floresta amazônica

A cada minuto, o mundo perde uma área de floresta do tamanho de 48 campos de futebol. E o desmatamento na Bacia Amazônica responde pela maior parcela, contribuindo para a redução da biodiversidade, perda de habitat, mudança climática e outros efeitos devastadores. Mas dados melhores sobre a localização do desmatamento e da invasão humana nas florestas podem ajudar os governos e as partes interessadas locais a responder com mais rapidez e eficácia.

Imagens de satélite grosseiras não permitem uma análise detalhada, em especial a aplicação adequada de técnicas de processamento de imagem. Com essas imagens geralmente não conseguimos diferenciar entre causas humanas de perda de florestas e causas naturais. Quando se tem imagens de satélite de alta resolução é possível rastrear as mudanças nas florestas, onde as imagens já demonstraram ser excepcionalmente adequadas para isso.

#### O que você deve fazer:
- Faça a aquisição dos dados e estude com profundidade as informações disponíveis em: https://www.kaggle.com/competitions/planet-understanding-the-amazon-from-space/overview
- A intenção é fazer a rotulação das classes para a localização do objeto, não apenas informar qual objeto existe na imagem.
- Revise a página de dados, que inclui informações detalhadas sobre os rótulos e o processo de rotulagem.
- Você deve desenvolver um programa para calcular o percentual de floresta densa em uma imagem
- Seja livre para fazer esta análise, porém a recomendação é usar segmentação de imagens por cores.
- Tente readequar seu programa para segmentar a imagem em diferentes categorias como floresta, terra para pecuária, estradas, etc.
- Isto é um desafio proposto, é importante tentar esta etapa e caso não tenha sucesso informar o motivo 

### :books: Sobre
Com a descrição feita pelo professor, aqui vão mais algumas informações importantes.

O Jupyter Notebook foi feito pelo [Colab](https://colab.research.google.com/). Portanto ao rodar, indicamos que seja por lá também.

 - Para funcionar é necessária adicionar sua chave API do Kaggle, por [aqui](https://www.kaggle.com/settings).

Além disso, é importante enfatizar que a quantidade de imagens presentes nas pastas de treino e teste, nos limitaram ao fazer um modelo com um treinamento bem feito, portanto os testes ficaram enviezados.

### :bookmark_tabs: Etapas
- [x] Baixar os arquivos
- [x] Começar a analisar quais usaríamos
- [x] Entender os dados
- [X] Prever as tags das imagens satélites
- [x] Cluster - identificar as características em cada imagem
- [x] Aprimorar o cluster para imagens específicas, indicando as cores mais presentes na imagem
- [x] Fazer o cálculo do percentual de desmatamento para estas imagens
- [x] PPT

### :eyes: Status
Concluído :white_check_mark:
