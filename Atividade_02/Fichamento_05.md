# Towards Automating Code Review Activities

R. Tufano, L. Pascarella, M. Tufano, D. Poshyvanyk and G. Bavota, "Towards Automating Code Review Activities," 2021 IEEE/ACM 43rd International Conference on Software Engineering (ICSE), 2021, pp. 163-174, doi: 10.1109/ICSE43902.2021.00027. doi: [https://doi.org/10.1109/ICSE43902.2021.00027]

## 1. Fichamento de Conteúdo

O artigo se inicia descrevendo como a performance é um fator importante para a qualidade de um _software_ e que com o tempo diversas técnicas de teste de performance foram desenvolvidas para determinar locais que possam diminui-la, tais testes englobam tempo de reposta, taxa de transferência, gasto de recursos e outras métricas. Testes de Performance normalmente executam o _software_ em teste (_software under test (SUT)_) com diversas intensidades de carga e por causa disso demanda uma grande quantidade de tempo e recursos para serem planejados e implementados, com essa informação os autores do artigo apresentam um novo _framework_ para auxiliar a determinar a melhor sequência de testes e a carga de informações otimizada para obtenção das métricas necessárias. A ferramenta funciona seguindo dois modelos de _Machine Learning_ realizando os testes de _stress_ usando _SaFReL_ (_self-adaptive fuzzy RL-based_) e testes de carga usando uma metodologia baseada em aprendizado reforçado. O _framework_ foi avaliado em relação a sua velocidade, eficiência e adaptabilidade para concluir os objetivos definidos no treinamento e foi possível identificar que ele foi capaz de trabalhar de forma eficiente mesmo com projetos complexos e com grande carga de dados.

## 2. Fichamento Bibliográfico

- _Code Review_ ( revisão de código): atividade de garantia de qualidade de software na qual uma ou várias pessoas verificam um programa principalmente visualizando e lendo partes de seu código-fonte (Pagina 1).
- _Deep Learning_ (Aprendizagem profunda): Tipo de aprendizado baseado em um conjunto de algoritmos que tentam modelar abstrações de alto nível de dados usando um grafo .(Pagina 2)
- _Crawler_: software que busca na rede de uma forma metódica e automatizada para concluir um determinado objetivo (Pagina 5).

## 3. Fichamento de Citações

- _Code Review is the process of analyzing source code written by a teammate to judge whether it is of sufficient quality to be integrated into the main code trunk. Recent studies provided evidence that reviewed code has lower chances of being buggy [1]–[3] and exhibit higher internal quality [3], likely being easier to comprehend and maintain. Given these benefits, code reviews are widely adopted both in industrial and open source projects with the goal of finding defects, improving code quality, and identifying alternative solutions."_
- _"Bosu and Carver report that developers spend, on average, more than six hours per week reviewing code [4].This is not surprising considering the high number of code changes reviewed in some projects: Rigby and Bird [5] show that industrial projects, such as Microsoft Bing, can undergo thousands of code reviews per month"_
- _First, from the perspective of the contributor (i.e., the developer submitting the code for review), we train a transformer model [7] to “translate” the code submitted for review into a version implementing code changes that a reviewer is likely to suggest. In other words, we learn code changes recommended by reviewers during review activities and we try to automatically implement them on the code submitted for review. This could give a fast and preliminary feedback to the contributor as soon as she submits the code._
- _"The achieved results were promising, with the models able to generate meaningful recommendations in up to 16% (first scenario) and 31% (second scenario) of cases. Still, vast improvements are needed to make such models suitable to be used by developers."_
