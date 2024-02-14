[![Python Version](https://img.shields.io/badge/python-3.12.2-blue.svg)](https://www.python.org/downloads/)
![GitHub License](https://img.shields.io/github/license/jrodrigotico/python)


## TD-IDF
O 'Term Frequency — Inverse Document Frequency' tem o objetivo de calcular, estatisticamente, o peso de cada palavra em um texto, atribuindo assim, uma importância para cada uma das palavras envolvidas. 

Esses pesos podem ser utilizados posteriormente para: análise de sentimento, modelos de machine learning como 'Naive-Bayes', análises de similaridade, análise de clusters como K-means, entre outras aplicações.

Este projeto visa o estudo sobre o método TF-IDF e suas aplicações, utilizando uma base de dados contendo avaliações do iPhone SE. 
O objetivo é explorar como os resultados do TF-IDF podem ser interpretados e utilizados para análises mais detalhadas e insights significativos sobre as percepções e opiniões dos jogadores em relação ao celular.


## 	:point_down: Download dos dados do Kaggle

```
- Acessar link: https://www.kaggle.com/datasets/kmldas/apple-iphone-se-reviews-ratings

OBS: O script do projeto ('script.ipynb') já está ligado com a fonte de dados 'reviews.csv', pois foi feito o upload desses dados no Github.

```

# 	:construction_worker: Tratamento dos dados

## Retirada de pontuação
Será utilizado 'sub' do módulo 're'. A expressão regular utilizada, r'[^\w\s], corresponde a qualquer caracter que não seja letra ou número. O '^' indica negação, '\w' indica qualquer caracter alfanumérico (letras e números), '\s' indica qualquer espaço em branco. Portanto serão retirados todos os símbolos.

## Retirada de 'stopwords'
Será considerada as stopwords em Inglês e será utilizado: nltk.corpus.stopwords.words('english').

## Stemming
Redução das palavras para a forma 'raíz'. O stemming pode melhorar a precisão da análise, por exemplo buscando palavras semelhantes e simplificando a análise do texto.

Será criada um nova coluna ('avaliacao_new') que representa as avaliações ('avaliacao_texto') reduzidas ('stemmizadas') e sem qualquer tipo de pontuação ou stopwords !


## 	:desktop_computer: Clone do repositório
Clone do repositório:

```
git clone https://github.com/jrodrigotico/TF-IDF-Reviews.git

```

## 	:email: Contato
Para feedbacks, sugestão de melhorias ou relato de problemas, sinta-se à vontade para entrar em contato comigo através do meu perfil no Linkedin:

[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joão-rodrigo-lemes-5603a6154/)
