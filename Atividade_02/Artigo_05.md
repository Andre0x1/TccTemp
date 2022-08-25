# Towards Automating Code Review Activities

R. Tufano, L. Pascarella, M. Tufano, D. Poshyvanyk and G. Bavota, "Towards Automating Code Review Activities," 2021 IEEE/ACM 43rd International Conference on Software Engineering (ICSE), 2021, pp. 163-174, doi: 10.1109/ICSE43902.2021.00027. doi: [https://doi.org/10.1109/ICSE43902.2021.00027]

## 1. Fichamento de Conteúdo

Um das tarefas que mais gastam tempo do desenvolvedor é a atividade de _Code Review_, que apesar de ser extremamente importante para a garantia de um produto de qualidade pode gastar cerca de seis horas semanais, além de aumentar os custos gerais do projeto. O artigo propõe uma maneira de otimizar o processo de _Code Review_ utilizando modelos baseados em _Deep Learning_ para analisar e e indicar parte do código necessário para serem revisadas. Para realizar o treinamento do modelo apresentado foi criado um _Crawler_ cuja função era de buscar e minerar repositórios que possuíssem a tarefa de _Code Review_ realizada frequentemente, em seguida foi analisada quais eram as sugestões mais comuns, obtendo mais de 17,194 sugestões de código para treinar o modelo. Apesar de terem sido encontrados alguns fatores que pudessem colocar a genuinidade dos resultados apresentados, os autores do artigo conseguiram obter informações promissoras sobre o futuro do projeto, onde o modelo conseguiu gerar cerca de 16% ~ 31% de comentários úteis para serem utilizados na revisão do código.

## 2. Fichamento Bibliográfico

- _Code Review_ ( revisão de código): atividade de garantia de qualidade de software na qual uma ou várias pessoas verificam um programa principalmente visualizando e lendo partes de seu código-fonte (Pagina 1).
- _Deep Learning_ (Aprendizagem profunda): Tipo de aprendizado baseado em um conjunto de algoritmos que tentam modelar abstrações de alto nível de dados usando um grafo .(Pagina 2)
- _Crawler_: software que busca na rede de uma forma metódica e automatizada para concluir um determinado objetivo (Pagina 5).

## 3. Fichamento de Citações

- _Code Review is the process of analyzing source code written by a teammate to judge whether it is of sufficient quality to be integrated into the main code trunk. Recent studies provided evidence that reviewed code has lower chances of being buggy [1]–[3] and exhibit higher internal quality [3], likely being easier to comprehend and maintain. Given these benefits, code reviews are widely adopted both in industrial and open source projects with the goal of finding defects, improving code quality, and identifying alternative solutions."_
- _"Bosu and Carver report that developers spend, on average, more than six hours per week reviewing code [4].This is not surprising considering the high number of code changes reviewed in some projects: Rigby and Bird [5] show that industrial projects, such as Microsoft Bing, can undergo thousands of code reviews per month"_
- _First, from the perspective of the contributor (i.e., the developer submitting the code for review), we train a transformer model [7] to “translate” the code submitted for review into a version implementing code changes that a reviewer is likely to suggest. In other words, we learn code changes recommended by reviewers during review activities and we try to automatically implement them on the code submitted for review. This could give a fast and preliminary feedback to the contributor as soon as she submits the code._
- _"The achieved results were promising, with the models able to generate meaningful recommendations in up to 16% (first scenario) and 31% (second scenario) of cases. Still, vast improvements are needed to make such models suitable to be used by developers."_
