
<h1>DB Scan</h1>

<p align = center> 
<a href = '#description'>Sobre</a> •
<a href = '#Motivation'>Motivação</a> •
<a href = '#tecnologies'>Tecnologias e bibliotecas</a> •



<h2 id = 'description'> Sobre</h2>


O DBSCAN (Density-Based Spatial Clustering of Applications with Noise) é um algoritmo de clusterização não supervisionado que agrupa pontos com base na densidade dos dados. Ele identifica regiões densas como clusters, conectando pontos que estão próximos entre si (dentro de uma distância chamada epsilon) e que possuem um número mínimo de vizinhos (minPts). Diferente do k-means, o DBSCAN não exige definir o número de clusters previamente e consegue detectar grupos de formas variadas, além de identificar pontos isolados como ruído ou outliers. É especialmente eficaz para dados com formas complexas e presença de ruídos..<br>

Entre os principais usos do DB Scan, destacam-se:

• Detecção de outliers: Identifica automaticamente pontos que não pertencem a nenhum grupo, sendo ideal para detectar anomalias ou valores fora do padrão em conjuntos de dados.<br>

• Análise espacial/geográfica: Muito utilizado para agrupar locais geográficos próximos, como em estudos de tráfego, crimes por região ou agrupamento de sensores.<br>

• Processamento de imagens: Aplicado na segmentação de imagens e detecção de formas ou padrões com densidade variável.<br>

• Reconhecimento de padrões em dados complexos: OÚtil em situações onde os clusters têm formatos irregulares ou não esféricos, algo que algoritmos como k-means não conseguem lidar bem.<br>



<h2 id = 'Motivation'> Motivação</h2>

Esse projeto foi desenvolvido com o intuito de fixação de conhecimento e documentação de atividade prática de aprendizado de técnicas de Machine learning.<br>


<h2 id = 'tecnologies'> Tecnologias e bibliotecas </h2>
<p>Linguagem de programação:<br>
<a href='https://www.python.org'>Python 3.9</a> <br>

Bibliotecas utilizadas:<br> 

1.  <a href='https://plotly.com/python/'>plotly</a> - Responsável pela criação de representações gráficas; <br>
2.	<a href='https://scikit-learn.org/stable/'>sklearn</a> - Utilizada para criação de modelos de Machine Learning; <br>
3.	<a href='https://seaborn.pydata.org/'>seaborn</a> - Utilizada para criação  de representações gráficas; <br>

 IDE:<br>

Para esse projeto, optamos utilizar a aplicação web Google colab.<br>

<a href='https://colab.research.google.com/'>Google Colab</a>
