# AnaliseSentimentosTextoSpacy
Repositório contendo scripts responsáveis pela análise de sentimentos em textos utilizando a biblioteca spaCy, uma das bibliotecas de processamento da linguagem natural mais utilizadas no mundo.
O código foi desenvolvido em um curso ministrado pelo professor Jones Granatyr, da plataforma Udemy.

Recursos:
* SpaCy
* Pandas
* NumPy
* SkLearn
* Random
* Seaborn

Documentação oficial da biblioteca: https://spacy.io/api/annotation#text-processing

Google Colab: 
* https://colab.research.google.com/drive/1W97WOylgQqBVlV6Z5HqIVym6Ucn3wyNG#scrollTo=gMIqrGA7jB6j
* https://colab.research.google.com/drive/1Du4H8ktXlqY2NXSrz6TeZAaGbxQc3Xuo#scrollTo=jFAxwObFnIge
 
 
 OBS: É importante ressaltar que os resultados do treinamento não foram os melhores, pois foi utilizado simplesmente para estudar o funcionamento geral da biblioteca. Caso deseje utilizar a mesma base de dados, é importante verificar como as frases estão distribuídas na base de treinamento, se estão classificadas corretamente e com mais precisão. Como é aprendizado de máquina supervisionado, muitas vezes se faz necessário recorrer a ajuda de um especialista em linguística para rotular bem as frases com seus respectivos sentimentos para obter resultados melhores. Ou então, procurar outras técnicas que sejam mais precisas. É muito difícil conseguir bases de dados de frases em português que sejam confiáveis para fins de estudos científicos ou para trabalhar em situações reais (redes sociais como Twitter, por exemplo, já ajuda nessa questão). Muitas empresas provêm soluções utilizando machine learning construindo as suas próprias bases de dados.
 
Também é fundamental verificar as probabilidades em função do número de classes (emoções). Geralmente, quanto menor (mínimo 2 classes), melhor.

Verificar também se existe algum caracter ou termo inadequado que foi utilizado por engano no treinamento do algoritmo, como existência de mais stopwords.
